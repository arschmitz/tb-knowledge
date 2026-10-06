# Exact local assessment output

Use the caller's schema when supplied. Otherwise lead with actionable findings
ordered by severity, followed by coverage and limits. Assess the author's actual
local target, not an older published patch. Do not edit or stage the source.
For the console, return JSON with `patchContext` and `comments`. Each comment
uses `id`, `filePath`, `lineNumber`, `content`, `recommendation`, `assessment`,
`rationale`, `validation`, `requiresChanges`, and `changeSummary`. Use the allowed
context/validation fields to retain knowledge, style and accessibility coverage.
Do not add a posting action or require Phabricator anchors to fit this schema.

## Context and findings

Record `purpose`, `behaviorContract`, `stackContext`, `evidence`, and `validation`
for the patch. Include target/first parent, actual checkout HEAD, dirty/staged
scope, important callers/dependencies and source/binary identity.

Each finding needs a stable ID, accurate current source path/line, concrete
concern, recommendation, assessment, rationale, evidence, required action,
`validation`, and `changeSummary`. Use `recommendation: "change"` or `"discussion"`;
use `requiresChanges: true` only for a justified source change. State the trigger,
consequence, smallest repair, applicable contract/style evidence, and test or
experiment needed. Do not claim an unrun proving edit was tested.

Keep valid repairs in unchanged code. These use current local coordinates;
Phabricator raw-diff inline anchors are not required. A discussion suggestion
must not masquerade as a required defect. Worthwhile style nits remain visible,
with the config or scoped convention and precise requested change.

## Required coverage

- Every changed production file and relevant tests; immediate callers, state/data
  ownership, lifecycle, errors, stack contracts and known breakages.
- Current bug/review discussion and disposition of relevant inline concerns;
  inaccessible sources and stale/resolved findings explicitly identified.
- Formatter/lint configuration and selected paths, plus manual file/test/symbol,
  DOM/CSS/Fluent names, syntax, comments/JSDoc, CSS and localization checks.
- Full applicable accessibility matrix with source, test and manual gaps.
- CodeRabbit exact mode/completion/findings and independent revalidation.
- Exact whitespace, syntax, lint, build, runtime, a11y and CI evidence as separate
  rows. Confirm test selection/assertions and matching source/binaries.
- Knowledge references used, current-source checks, decision effects, saved new
  lessons and capture/sync/access limits.
- Evidence that source, index, branches and Phabricator state stayed unchanged.

Say no actionable findings only after all applicable source passes. Keep unrun,
failed, ignored or blocked validation visible. A passing formatter, CodeRabbit
stream, build or test does not replace the other passes. Do not propose review
replies or post them during this assessment.
