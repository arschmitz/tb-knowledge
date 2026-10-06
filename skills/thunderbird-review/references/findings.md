# Exact anchors and review output

Derive Phabricator inline anchors from the requested raw unified diff. In
`@@ -42,7 +50,9 @@`, start the new-side counter at 50. Advance for context and
`+` lines; do not advance for `-` lines or the no-newline marker. Use a changed
`+` line in the correct file. Validate the whole selected range before giving an
exact replacement. Local checkout or experiment line numbers are not patch
anchors.
Mode-only changes have no changed source-line anchor. Report their old/new modes
as non-inline context. A broad multi-file repair is not a safe narrow replacement;
explain that scope instead of inventing suggestion text.
Do not count `+++` headers as additions. Check rename destination, new-file flag,
and every line of a multi-line range. An added file still uses its raw hunk
coordinates. A deletion-only hunk may have no eligible changed new-side anchor.
For moved code, use the actual eligible destination range, not an old local line.

If the repair belongs in unchanged code, label that location as
`actual edit location/context` and provide a non-inline suggestion. Never invent
an inline anchor. When a caller requires inline-only output, omit an item with no
eligible changed-line anchor from that array and report the limitation separately
when its schema permits. A raw patch that cannot be applied can still be reviewed
with clearly identified nearby source; runtime, automated review and exact
checkout-line coverage remain unverified.

Use `P1`, `P2`, `P3`, and `nit` consistently. Do not turn optional cleanup into a
blocking defect. Return the user's required schema when one is supplied.
For the console Review schema, preserve `patchContext`, `issues`, and `coverage`:

- `patchContext`: `purpose`, `behaviorContract`, `stackContext`, `evidence`,
  `validation`.
- Each issue: stable `id`, `severity`, `title`, `filePath`, `lineNumber`,
  `lineLength`, `isNewFile`, `comment`, `codeSuggestion`, `isDeletion`, `rationale`,
  `validation`.
- `coverage`: `summary`, `accessibility`, `codeRabbit`, `static`, `runtime`,
  `context`. Include formatting/manual style and knowledge use in the appropriate
  allowed fields rather than dropping them or inventing incompatible fields.

Only return eligible changed new-side anchors in an inline-only issues array.
Use a safe exact replacement string without Markdown fences for `codeSuggestion`.
Leave it empty when no safe exact replacement exists. `isDeletion: true` means
delete exactly the selected range with no replacement; it is not a missing
suggestion. Explain useful non-inline concerns in allowed context fields.
Otherwise include:

1. Patch identity: revision, digest, exact base, checked-out revision and Review
   checkout; original purpose, behavior contract and stack context.
2. Findings first, in severity order. Each has a short title, exact anchor or
   non-inline context, concrete failure condition, source/test evidence,
   paste-ready requested change, and a minimal safe suggestion when justified.
   For an exact suggestion, provide only the replacement text for its chosen
   range; distinguish deletion from an empty or absent suggestion.
3. Nonblocking architecture suggestions and worthwhile nits, with the same
   evidence and accurate coordinates.
4. Accessibility coverage and checklist statuses.
5. Formatting and manual style coverage: per-file configuration, file/test and
   symbol names, DOM/CSS/Fluent conventions, syntax, comments/JSDoc, applicable
   lessons, real nits, and proposed conventions. A formatter pass is only one row.
6. CodeRabbit completion and findings, independent review coverage, exact static
   and runtime commands/results, build result, CI/platform limits, and gaps.
7. Callers, contracts, sibling implementations and tests inspected. State which
   discussion was read or inaccessible and how existing comments were resolved.
8. Knowledge used: record/note references, their current-source check and what
   they changed; new source-linked lessons, saved IDs/paths and capture/sync gaps.
9. Local experiments: purpose, changed paths, retained diff, outcome and limits.

Before returning any finding, check its location against the recorded raw patch,
the original target behavior, and the final experiment state. Use one underlying
issue per comment when it has one fix. Avoid several comments for the same cause.
Include independent unchanged-code concerns as non-inline context when allowed.
Do not omit them merely because the changed-line anchor is elsewhere.

Use a concrete explanation rather than a verdict alone:

```text
When [real condition], [current code] causes [observed consequence].
[Source/test evidence] confirms the contract. Please [minimal action].
Validation: [actual result or exact needed experiment].
```

For a style nit, replace the failure claim with the specific scoped inconsistency
and the applicable accepted example/configuration. Do not invent a behavioral
consequence to make an optional preference sound severe.

A passing lint, build, different-platform test, or modified experiment does not
establish that the original runtime behavior or selected CI job passed. If there
are no findings, say so and retain the coverage and limits. Supply comments for
review; publishing them requires authorization.
