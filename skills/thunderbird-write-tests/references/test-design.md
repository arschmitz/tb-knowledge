# Design a Thunderbird regression test

Read the existing tests, manifest, head files, production callers, and relevant
knowledge before writing. The test must expose a meaningful wrong result. It must
also fit this component's accepted harness and naming family.

## Choose the layer that reaches the contract

| Contract | Likely existing layer; inspect the actual component |
| --- | --- |
| Parsing, serialization, module/service state, protocol decisions | xpcshell unit/integration tests with established service fixtures. |
| Privileged window, rendered DOM, selection, keyboard, focus, prompts | Thunderbird browser-chrome/Mochitest with product helpers. |
| Application startup/restart or cross-window lifecycle already covered there | Existing Marionette/application harness. |
| Native interface or compiled behavior | Existing native or matching integration harness and normal build. |

Use the existing layer that can reproduce the bug. Do not introduce a new test
framework to avoid learning the product's harness. A unit test of a helper cannot
alone prove that a UI calls it with the correct item, permission, or route.
Likewise, a UI test is unnecessary when a stable module contract fully owns the
failure. Add another layer only for an uncovered boundary.

## Turn acceptance criteria into evidence

Create a table before editing:

| Criterion or known breakage | Required precondition | Action | Observable assertion | Test/task |
| --- | --- | --- | --- | --- |
| Exact contract | State that made the bug possible | Real operation | Expected result and timing | Existing/new path and name |

For each material criterion, choose cases that differ in failure mechanism:

- Normal success with actual data and current selected identity.
- Absence/empty data, invalid input, duplicate or boundary values when meaningful.
- Error and retry, cancellation/close, replacement, and cleanup/reopen.
- Relevant permissions/read-only state and feature-gated/legacy entry points.
- Keyboard, focus, names/state/announcements for affected UI.

Omit redundant cases with a reason. Do not inflate coverage with input variations
that exercise the same branch and assert no new contract. Do not weaken an
assertion or add a skip to turn a failing meaningful case green.

## Names, files, and registration

- Inspect neighboring manifest entries and filenames. Browser files often use
  `browser_` and unit files `test_`, but follow the actual family and harness.
  Preserve camel/dashed stems and exact case in that directory.
- Use a named task for each distinct scenario under the local accepted pattern.
  Describe the behavior and condition. Do not require one casing across all tasks.
  For example, message-command tests use `test_shift_delete_prompt`; other
  components use camelCase after the test prefix.
- Name fixtures/helpers for their data or action. Keep setup helpers separate
  from assertions unless the accepted helper deliberately verifies that action.
- Register test and support files in the actual TOML/INI manifest. Check defaults,
  head files, support files, relative paths and build registration. A file on disk
  may not be packaged or discovered without these changes.
- Use `skip-if` or platform conditions only for a demonstrated platform/harness
  limitation under project policy. State which coverage remains elsewhere.
- Keep MPL notices and per-file environment/configuration consistent with the
  family. Use commlint and the manual style/naming reference on new tests too.

## Fixtures and state ownership

Use the component's existing helpers to create accounts, folders, messages,
address books, calendars, events, windows, and documents. Confirm helpers create
the state the test claims; a convenient sample may miss permissions or recurrence.
Use fixed relevant values and isolated profiles/files. Avoid live network,
accounts, secrets, wall-clock assumptions, locale-specific literal text, or
uncontrolled server replies in ordinary regression tests.

Mock a nondeterministic external boundary when needed, not the behavior under
test. A stub returning the expected result can conceal a wrong production call.
Inspect whether data is shared or copied and whether cleanup belongs to the test
or helper. Register cleanup immediately after acquiring a resource, so an early
failed assertion does not leak it.

Restore changed preferences, accounts, calendar data, observers, listeners,
files, windows, tabs, frames, timers, promises and fake services. Do not use broad
cleanup that removes another test's state. Check teardown after cancellation and
errors, not just success. Reopen or run the next scenario to expose retained state
when the production lifecycle changed.

## Asynchronous proof without sleeps

Wait for the event or state transition that owns completion. Establish the wait
before triggering the action so a fast event cannot be missed. Use accepted
event/state helpers and their cleanup/timeout behavior. Avoid arbitrary sleeps,
shorter timeouts, and polling a flag unrelated to actual completion.

For stale-result/cancellation coverage:

1. Start operation A with identity A and prove its provider started.
2. Hold its completion at the external boundary.
3. Replace with B or close/cancel the owning UI.
4. Release A, including rejection where relevant.
5. Assert A cannot update current data, visibility, busy/error state or focus.
6. Complete B and assert its correct result and cleanup.

This detects providers that ignore `AbortSignal`, stale callbacks, and guards
attached to the wrong identity. Cancelling before A starts does not test those
failures. Assert final order/state, not an internal callback count unless count
is itself the API contract. Let real production scheduling run where possible.

## UI interactions and accessibility

Use the actual product control, not a hidden duplicate or convenient descendant.
Establish visibility, selected item, enabled permission, and the relevant window
before interaction. Read the helper's behavior: synthetic clicks on hidden
controls can expose a different accessible target.

Use modern DOM key descriptors such as `KEY_Delete` where the current helper
supports them. Scoped knowledge record
`eea33a9d5620426d102ae56e7251ad877676091ee235ff32cd268d2306dfb3ac`
also requires asserting confirmation text in the reviewed message-command cases.
Check localized expected text through accepted product helpers, then choose the
button/action. A prompt opening alone does not prove it asks the right question.

For slots, check `assignedSlot` or `assignedElements()` and behavior with real
content. Slot attribute spelling alone can pass while nothing renders. For
keyboard/focus changes, invoke the key, inspect the actual focused element and
result, then close/reopen and check focus return. For role/name/state, use the
actual interactive accessible and supported helpers, including
`--enable-a11y-checks` for applicable browser runs. Read the accessibility
reference for the full coequal pass and dynamic axe-observer criteria.

## Assertions that explain failure

Use the harness's accepted assertion API. Match strict equality/type/collection
checks to the contract. Prefer a message that states the expected behavior and
condition. When two values fail differently, separate assertions so the log
identifies which one broke. Do not demand separate assertions for an atomic
contract whose established helper already gives useful diagnostics.

Assert stable results: data, ordering, permission, selected/focused identity,
rendered/composed target, lifecycle or error. Avoid incidental class order,
source-string matching, arbitrary pixel geometry, or private call counts unless
those are the contract. Check the negative outcome where necessary: obsolete data
did not overwrite B, a read-only action did not run, or a cancelled upload did not
leave required side effects.

Review for false passes. Could a no-op implementation, wrong selected item,
always-true flag, immediately resolved stub, or unstarted cancellation still pass?
If yes, strengthen preconditions and observable assertions.

## Prove discovery, detection, and final behavior

Follow the validation reference for matching-source builds and harness recovery.
Confirm the exact test/tasks and relevant assertions ran. For `UNKNOWN TEST`, use
the full Thunderbird browser path, not repeated filename-only retries.

When feasible, demonstrate the specific regression assertion fails under old
behavior or a narrow intentional defect in an isolated experiment. A harness
crash does not prove detection. Restore your experiment without touching unrelated
work, then run the final intended state. If red/green proof cannot be done within
scope, explain which assertion would fail and the limitation; do not claim proof.

Self-review the final production/test relationship, cleanup, manifests, syntax,
manual style and full applicable accessibility criteria. Use CodeRabbit on the
actual diff without creating a commit just for it. Keep independent review and
automated results distinct. Broaden tests only for a concrete remaining risk.

## Deliver and retain lessons

Report the criterion/assertion map, paths/tasks/manifests, exact commands and
outcomes, detection evidence, final self-review, platform limits, and unrun cases.
Use `Minimum test coverage:` when writing an implementation story. Capture useful
harness, cleanup, naming, behavior and breakage lessons through the knowledge
workflow. Include the failure mechanism and the assertion that protects it.
