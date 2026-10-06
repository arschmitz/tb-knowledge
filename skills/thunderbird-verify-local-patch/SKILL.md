---
name: thunderbird-verify-local-patch
description: Verify the author's exact local Thunderbird patch using project knowledge, full behavior/style/accessibility review, current browser discussion and matching-source checks, without editing or replacing it during assessment.
---

# Verify a local Thunderbird patch

This is the full author-side assessment pass. Use the configured Working `comm`
checkout and its paired Gecko parent. Keep external Review checkouts out of this
task. A published Phabricator patch is context; it must not replace newer local
work. Use simple, direct English and preserve exact code and evidence.

## Required references and knowledge workflow

Start with [knowledge.md](references/knowledge.md). Find the shared clone and
read its agent/consumer instructions. Search changed paths, symbols, bug/review
IDs, known behavior/breakages, test helpers, syntax/style and naming conventions.
Use `tb knowledge search --repository thunderbird 'terms'` and
`tb knowledge show ID`, or scoped `rg` searches in `notes/` and `records/`.
Follow useful lessons to their original evidence; compare target source and
fixed accepted siblings. Keep the applied/rejected/inapplicable decision ledger.
Do not mistake an imported plan or newer local patch for accepted architecture.
Capture specific new lessons and report saved references and access/sync gaps.

Read [behavior and architecture](references/behavior-and-architecture.md) for
contract/caller/state tracing, [review discussion](references/review-discussion.md)
for every relevant inline concern, [style and formatting](references/style-and-formatting.md)
for the manual pass, [accessibility](references/accessibility.md) for the coequal
UI/lifecycle pass, and [validation](references/validation.md) before tool runs.
Use [assessment output](references/assessment-output.md) to check final findings
and complete coverage. Every reference is inside this standalone folder.

## Required formatting and manual style pass

Inspect per-file formatter/lint rules and nested overrides, then check file/test
names, class/function/variable names, DOM IDs, CSS classes, Fluent IDs, syntax,
comments/JSDoc, CSS tokens/selectors and localized wording. Search the repository's
scoped conventions and accepted/rejected style feedback. Check exact case and
all consumers of a renamed symbol or resource. Do not edit to make lint pass.
Report formatting and manual conventions separately, including concrete nits,
proposed rules and ignored/unverified paths. A green formatter is partial coverage.

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
   Apply the behavior, style and discussion references to every changed file.
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
