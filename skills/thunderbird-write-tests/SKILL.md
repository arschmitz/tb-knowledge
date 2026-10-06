---
name: thunderbird-write-tests
description: Add focused Thunderbird regression tests that prove behavior, use the right comm harness and manifests, cover accessibility and asynchronous state, and run with matching source and binaries.
---

# Write Thunderbird tests

Write the smallest durable test set for the requested behavior. Preserve the
patch's intended behavior and accessibility. A test must detect a real failure;
matching implementation text, internal call counts or incidental markup is not
enough. Use simple, direct English in names, comments and the report.

## Establish the contract and harness

1. Verify the selected Working `comm` checkout, paired Gecko parent, branch, HEAD,
   dirty state, staged work, unresolved paths and patch/stack scope. Preserve
   unrelated changes. Do not substitute a Review checkout or published patch for
   the author's current work. A review experiment uses only the configured
   Review checkout under that review task's permissions.
2. Read the behavior contract, callers, state ownership, nearest sibling tests,
   test helpers, fixtures and manifest. Locate the shared knowledge clone, read
   AGENTS.md and search relevant paths/symbols in `notes/` and `records/`. Check
   source revisions. Use established file and test names, setup/cleanup and
   harness conventions. Do not invent a global naming rule from one example.
3. Choose the existing product harness that reaches the behavior. Use xpcshell
   for module/service behavior without UI; browser-chrome/Mochitest for privileged
   window, keyboard, focus and DOM behavior; existing Marionette coverage when
   the scenario crosses application lifecycle boundaries. Inspect the component's
   actual harness and manifest instead of imposing a new framework.
4. Map each requested acceptance criterion to an assertion and the state that
   makes the regression observable. State any justified omitted case. Cover
   meaningful success, failure, boundaries, cleanup and reopening; avoid a
   matrix of equivalent cases with no added failure signal.

## Author behavior-based coverage

- Assert user-visible results and stable API contracts. For a slotting failure,
  test the assigned slot or rendered behavior, not just the names/order of slot
  attributes. For permissions or command state, assert which action the current
  selected objects can perform rather than a stale focus-derived flag.
- Use actual product controls and existing helpers. Establish the state that
  makes a control visible before clicking it. A synthetic click on hidden content
  can hit a different visible target. Avoid brittle pixel or selector assumptions
  when an established semantic target exists.
- Wait for the actual asynchronous condition or event. Do not add arbitrary
  sleeps. To prove cancellation, let the first operation start before replacing
  it, then prove its stale completion cannot update current state. Check rejected
  work, close/cancel cleanup, listener removal and reopen with fresh data.
- Use deterministic fixtures. Restore preferences, observers, accounts, files,
  timers, windows and other state through the harness's cleanup support. Avoid
  external network or live credentials in normal tests. Mock only the boundary
  that prevents a reliable test; keep the behavior under test real.
- For affected UI, cover the actual accessible target, role/name/state, keyboard
  parity, focus entry/return, dynamic announcements and cleanup. Use available
  `AccessibilityUtils` helpers and, where justified, `AxeHelpers.sys.mjs` mutation
  observers. DOM attributes alone do not prove keyboard or accessibility behavior.
  Include both feature-gated and legacy routes when a shared opener changes.
- Register new files, support files and conditions in the actual TOML/INI
  manifest. Verify path spelling and component naming conventions. Keep platform
  exclusions narrow and supported by evidence. Do not skip failures or weaken
  assertions to get a pass.

## Run and prove the test

Build from the paired Gecko root. Use a private writable object directory with
matching source and binaries. A fresh directory needs a complete `./mach build`
before `./mach build faster`. Artifact builds suit compatible frontend/resource
changes; native code, WebIDL, build configuration and uncertain compatibility
need a normal build. Do not overlay frontend resources onto copied binaries or
share a live object directory.

Use `AUTOCLOBBER=1` for isolated recovery. Missing resources, stale manifests,
`Strict mode enabled, test paths must exist`, or `No rule to make target
'comm/faster'` are setup failures. Refresh/build from the Gecko root and retry
before declaring local validation blocked. Record an unrecoverable blocker only
after a build-capable recovery attempt.

Run `../mach commlint` from `comm`, direct relevant checks, and the focused test
with the selected build configuration. Add `--enable-a11y-checks` to applicable
browser runs. Confirm that the new test was discovered, its assertions ran and
the process completed. Where practical, prove the regression test fails for the
old behavior or a narrow deliberate defect in an isolated experiment, then passes
for the intended behavior. Restore experiment edits and recheck the final diff.
Do not claim detection from a harness failure before the assertion.
If filename-only discovery reports `UNKNOWN TEST` for a Thunderbird browser test,
use its full path with `../mach mochitest -f browser --subsuite thunderbird
comm/REPOSITORY_RELATIVE_TEST_PATH`, plus relevant headless/accessibility options.

Broaden testing only for a concrete remaining risk or required gate. Local success
does not prove a different-platform CI run. State timeouts, skips and partial
coverage precisely. Keep source changes within the requested task; a discovered
production defect does not justify an unrelated rewrite.

## Deliver and learn

Report test paths, manifest changes, the acceptance-criterion mapping, exact
commands/outcomes, regression-detection evidence and gaps. Use
`Minimum test coverage:` when drafting an implementation story. Review the final
diff and confirm unrelated work remains. Commit, amend or publish only within the
task's authorization.

Save useful test-harness and behavior lessons in the shared knowledge clone using
AGENTS.md and FORMAT.md, with source references, validation and uncertainty. Keep
private test data and raw logs local. If knowledge is unavailable, report the gap
and follow the current source and harness.
