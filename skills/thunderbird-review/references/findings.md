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

If the repair belongs in unchanged code, label that location as
`actual edit location/context` and provide a non-inline suggestion. Never invent
an inline anchor. When a caller requires inline-only output, omit an item with no
eligible changed-line anchor from that array and report the limitation separately
when its schema permits. A raw patch that cannot be applied can still be reviewed
with clearly identified nearby source; runtime, automated review and exact
checkout-line coverage remain unverified.

Use `P1`, `P2`, `P3`, and `nit` consistently. Do not turn optional cleanup into a
blocking defect. Return the user's required schema when one is supplied.
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
5. CodeRabbit completion and findings, independent review coverage, exact static
   and runtime commands/results, build result, CI/platform limits, and gaps.
6. Callers, contracts, sibling implementations and tests inspected. State which
   discussion was read or inaccessible and how existing comments were resolved.
7. Local experiments: purpose, changed paths, retained diff, outcome and limits.

A passing lint, build, different-platform test, or modified experiment does not
establish that the original runtime behavior or selected CI job passed. If there
are no findings, say so and retain the coverage and limits. Supply comments for
review; publishing them requires authorization.
