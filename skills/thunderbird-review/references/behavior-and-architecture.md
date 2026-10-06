# Review code behavior and architecture

Read this with the exact patch and relevant knowledge records. Inspect every
changed production file and its tests, including files without reviewer comments.
The goal is to explain what the patch does, how Thunderbird uses it, and which
failure condition a proposed finding would prevent.

## Establish intent before judging implementation

- Explain the user/task problem and expected observable result.
- Read relevant bug requirements and all applicable current review threads in
  the browser. Use cached unchanged context; fetch only missing or changed evidence.
- Identify the patch's first parent or supplied exact base and dependencies in
  its outgoing stack. A parent patch may own an API changed by the tip.
- Read relevant knowledge about architecture, known breakages and rejected fixes.
  Separate accepted code from planning notes and an author's unlanded experiment.
- Write the important invariants: what must always be true, who owns data, which
  operation completes it, and what happens on failure/cancel/close.

For each material change, keep this trace:

| Change | Entry point/callers | State or data owner | Observable result | Protecting test or gap |
| --- | --- | --- | --- | --- |
| Actual path/symbol | Direct caller and relevant user action | Component/service/API | Success and failure contract | Exact assertion or needed experiment |

Search references with `rg` and read bodies, not only call-site names. Follow
renames, imports, resources and shared helpers. Inspect immediate unchanged code
when it owns the bug. A finding may belong there rather than on a changed line.

## State, data, and persistence

- Who creates, reads, mutates, caches, serializes, and clears each object?
- Does identity include the account/calendar/folder, item, recurrence, window,
  route, or session dimensions the consumer needs?
- Does a route or selection change update related fields atomically? Can an old
  recurrence ID, selection, cached row, or previous account leak into the next item?
- Check defaults, absent values, duplicate IDs, empty collections, missing objects,
  read-only objects, permissions, and invalid input at the real boundary.
- Check persistence and migration: stored preferences, column/sort keys, schema,
  unknown fields and forward-compatible data. A style rename can break stored keys.
- Check copies versus shared references, invalidation, initialization before read,
  and ownership of mutable native/platform objects.
- Check behavior when reopening, reloading, switching feature flags, or retrying.
  Success on first open does not prove later state is fresh.

## Asynchronous work and lifecycle

Trace the timeline explicitly when ordering matters:

1. Schedule/start operation A and record its current identity.
2. Change selection/route or close/cancel the owner.
3. Start operation B when relevant.
4. Resolve or reject A after that change.
5. Verify only current work can update visible/persisted state.
6. Verify cleanup and B still complete correctly.

Check whether cancellation actually reaches the provider. `AbortSignal` alone
does not prove a provider stops. If it ignores cancellation, generation/request
identity may still be required. Check queued callbacks, animation frames, promise
rejections, observers, listener removal, timer cancellation and destroyed windows.
Test cancellation after A starts; cancelling an unstarted operation is weaker proof.

Check busy/loading/error state during every transition, partial rendering, ready
before show, focus, announcements, and work scheduled while hidden. Do not trade
responsive UI for eager synchronous work. Close, Escape, cancel, successful Save,
error, and replacement paths may have different cleanup routes.

The scoped POP3 lesson
`d781b9fa2d8e3b1654a2a32240d7e9160c1408776c546e7e4bc6846eb497c580`
links lifecycle naming to correctness: timed polling can release a shared Inbox
while a client is still writing. Completion belongs to the actual action-done
path. Consult it for protocol queue work, not as a universal queue implementation.
Calendar source/route notes may describe planning or local work; verify accepted
source before presenting that architecture as a project contract.

## Errors and external boundaries

- Distinguish expected absence, invalid input, recoverable error, cancellation,
  and programming invariant failure. Check the user's result in each case.
- Does a catch handle the error or silently turn failure into success? Is a
  rejected promise observed? Is the error attached to the still-current operation?
- Preserve user choices and credentials across retry only where the API allows.
  Check origin/account boundaries, selected identity, and filename/path contracts.
- Check native JS interfaces, WebIDL/XPCOM, extension APIs, worker/content/chrome
  boundaries, serialization, and resource availability after build packaging.
- Inspect relevant permissions and command enablement against the current
  selected objects, not an incidental focus-derived flag.
- Check logging for useful context without secrets or temporary debug dumps.

## Architecture and performance

- Reuse established services/helpers when their contract fits. Check whether an
  extraction preserves initialization, context, ownership, and failure handling.
- Keep presentation separate from shared data/lifecycle logic where the current
  component does so. Do not demand a redesign merely because another component
  uses a different framework.
- Check repeated I/O, synchronous blocking work, unnecessary recomputation,
  broad DOM rebuilds, observer storms, retained listeners/data, and large lists.
- Check extension or downstream consumers of shared APIs. Inspect all consumers
  before changing a common selector, module, or signature.
- Explain the concrete current failure for blocking architecture feedback.
  A defensible improvement without such a failure belongs in nonblocking advice.

## Tests and review feedback

Read what tests assert, their setup, actual interaction, state waits, and cleanup.
Can a wrong implementation still pass? Does the assertion exercise the changed
path, actual slot, permission, visible control, error, or stale completion?
Check meaningful success, failure and boundary cases, then choose focused
experiments for remaining risks. Avoid duplicate coverage of equivalent cases.

For each existing comment or automated finding, record the hypothesis, original
intent, source/callers checked, result, validation, and disposition. Retain valid
feedback; withdraw resolved/stale concerns; reject a superficial cleanup that
breaks the contract. A bot finding, reviewer preference, author explanation and
accepted landing are different evidence types. Never infer a rule from silence.

A final finding names the failure condition, affected behavior, exact evidence,
minimal required change, and validation. Include supported style nits and
nonblocking architecture suggestions separately. Record specific lessons about
how the component works and why a failure occurred, including rejected approaches.
