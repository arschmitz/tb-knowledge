---
name: thunderbird-verify-local-patch
description: Perform an author-side self review of an exact local Thunderbird patch, its behavior and accessibility, without replacing it with the published patch or editing source during assessment.
---

# Verify a local Thunderbird patch

This is the full author-side assessment pass. Use the configured Working `comm`
checkout and its paired Gecko parent. Keep external Review checkouts out of this
task. A published Phabricator patch is context; it must not replace newer local
work. Use simple, direct English and preserve exact code and evidence.

## Select and understand the local patch

- Record branch, HEAD, status, staged and unstaged changes, unresolved paths,
  target commit, first parent, commit message, stack and descendant branches.
  When selecting by review ID, inspect matching local commits and use the latest
  local copy by Git commit time. Verify its identity. If multiple copies have
  different intent, do not silently choose one. For an explicit working-tree
  request, record its actual diff separately from committed work.
- Confirm the checkout and binary match the selected local target. If another
  revision is checked out, report the setup gap; do not silently switch it or
  claim runtime coverage for the selected patch from that other revision.
- Review the exact committed target diff against its first parent and the full
  stack as context. Explain the original purpose, required behavior and which
  commit owns each affected contract. Inspect every changed production file and
  relevant tests even when no reviewer commented.
- Locate the shared knowledge clone, read AGENTS.md, and search scoped paths,
  symbols, bug and review IDs in `notes/` and `records/`. Check cited revisions
  against current source. Read current Phabricator discussion and relevant
  Bugzilla context in the browser, including inline change requests. Record
  inaccessible context and rate limits. Comments and old lessons are hypotheses.

## Assessment boundaries

Do not edit source or tests, stage, commit, amend, switch or rewrite branches,
create worktrees, replace the local patch, post replies, or change Phabricator
state in this assessment. Build/test outputs and temporary configuration belong
in private build directories outside source. Existing focused tests and static
checks are allowed. If a proving edit is needed, report the experiment required;
apply it only under a task that authorizes source/test changes.

## Full self review

1. Trace callers, state ownership, persistence, API boundaries, cleanup,
   established sibling code and test contracts. Check current behavior instead
   of accepting a name, green test, automated review or reviewer suggestion.
2. Check regressions, architecture, asynchronous order, cancellation, stale
   completion, errors, performance, test durability, naming, comments, spelling,
   grammar, punctuation, localization and nearby style. Use project file/test,
   class/ID, symbol and syntax lessons beyond lint. Prefer newer accepted practice
   in the same scope; preserve explicit exceptions and original intent.
3. Perform the full coequal accessibility pass in
   [references/accessibility.md](references/accessibility.md). Include semantics,
   names, keyboard, focus, dynamic announcements, visual/forced colors,
   localization and durable test coverage. Trace user-facing consequences even
   for a non-UI patch. Include both new and legacy Calendar dialog routes when a
   shared opener or parameter changes.
4. Run the configured or discovered CodeRabbit executable after checking that
   executable with `--version`:
   `coderabbit review --agent --committed --base FIRST_PARENT`.
   Revalidate useful findings independently. Record completion, actual findings
   and failures. Zero findings or incomplete output is not approval.
   If it is unavailable, identify the checked tool and complete the independent
   assessment with that coverage gap.
5. Run `git diff --check FIRST_PARENT..PATCH`, `../mach commlint` from `comm`,
   and relevant direct syntax/static checks. Confirm the checks selected changed
   paths. `no files linted` is not patch validation.
6. Build from the paired Gecko root with matching source and binaries. Give this
   run a private writable object directory; never share a live one. A fresh
   directory needs a complete `./mach build` before `./mach build faster`.
   Attempt isolated build recovery with `AUTOCLOBBER=1` for clobber, missing
   resources or stale manifests before declaring runtime validation blocked.
   Use a normal build for native/WebIDL/build changes or uncertain compatibility.
   Copied binaries with frontend overlays do not prove runtime behavior.
7. Run the narrowest existing tests that exercise each important contract.
   Include `--enable-a11y-checks` for relevant browser tests. Confirm actual test
   selection, assertion coverage and final outcome. A startup failure, timeout
   or platform skip does not become a passing runtime check. Record local and
   selected CI coverage separately.
   If browser discovery reports `UNKNOWN TEST`, select the full test path with
   `../mach mochitest -f browser --subsuite thunderbird comm/REPOSITORY_RELATIVE_TEST_PATH`,
   plus relevant headless/accessibility options.

## Findings and useful lessons

Return the required schema when the caller supplies one. Otherwise lead with
actionable findings ordered by severity. Include the original purpose, behavior
contract, stack context, inspected source/discussion, independent review,
CodeRabbit and each validation result or concrete limitation. Findings need a
stable ID, current source path/line when known, concern, recommendation,
assessment, rationale, evidence, required change and narrow change summary.
Use `recommendation: "change"` or `"discussion"`, and `requiresChanges: true` only
for a justified source change. Include each finding's `validation` and
`changeSummary`; the patch context records `purpose`, `behaviorContract`,
`stackContext`, `evidence` and `validation`.

Keep justified repairs in unchanged code. Local current-source coordinates are
valid here; Phabricator inline anchors are not required. Distinguish changes from
discussion suggestions. Do not propose or post review replies. If no finding
survives, say so and retain the coverage limits. Leave the local patch and index
unchanged.

Save reusable findings under the shared clone's AGENTS.md and FORMAT.md workflow;
retain source references, rejected suggestions, validation and uncertainty. Keep
private evidence local. A missing knowledge clone is a reported gap, not a reason
to skip the self review.
