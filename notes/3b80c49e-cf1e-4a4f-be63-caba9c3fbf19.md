<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T06:32:22.698606+00:00", "paths": ["mail/components/calendar/content/calendar-event-edit-save.mjs", "mail/components/calendar/content/calendar-event-create-edit-dialog.mjs", "mail/components/calendar/content/calendar-event-calendar-options.mjs", "mail/components/calendar/test/unit/test_calendarEventEditSave.js", "mail/components/calendar/test/unit/xpcshell.toml"], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "architecture-body-continuation-20261013", "verification": "Read local implementation bodies and stated callers, consumers, and assertions; no product tests run", "component": "calendar", "language": "JavaScript", "runtime": "privileged Gecko or Thunderbird code; test harnesses named in body", "fileRole": "production; test and build evidence named in body"}} -->
# saveCalendarEventEdit live state, completion values, cancellation, and tests

The entire `calendar-event-edit-save.mjs` local implementation was read. The
caller is the open, edit-ready dialog's `save()`,
`calendar-event-create-edit-dialog.mjs:432–468`. It supplies the real occurrence
prompt and the host's modify transaction, with response mode from
`X-MOZ-SEND-INVITATIONS`.

The function reads source, edit session, and draft. It returns `unavailable`
without work unless source is ready, mode is edit, operation is idle/error, and
the draft exists. It creates a request ID, clones draft values, retains baseline
object identity, and dispatches `operationStarted` before entering the edit queue.

`isCurrent`, lines 69–79, requires the same source request ID, the same baseline
object, and the same Save request ID. Each has a specific lifetime. A reset,
replacement source, default initialization that replaces baseline, or a new
operation can invalidate the request. The check does not cancel a provider write
already underway.

Within the queue, lines 84–151, Save reloads the latest occurrence and checks
source permission, invitation status, destination existence/writability/event
support, and move/delete/add permission. A stale request returns the unchanged
identity before changing storage. The occurrence prompt can return null; this
throws the local `save-cancelled` marker. A second current check follows the
prompt. Save clones the chosen item, applies the draft's changed base fields,
then applies enabled optional fields or removes disabled ones.

For a calendar move it can replace the organizer ID/name from destination
properties. If the organizer does not match the destination access-control
addresses, it clones the organizer and sets `SENT-BY` to the first address.
It adapts the scheduling agent, makes the event immutable, and awaits the host
transaction. Successful whole-series date changes request queued occurrence
shifts. The callback returns a plain identity with the selected calendar ID.

After queue completion, current requests dispatch success and return
`{status: "success", identity}`. Stale completion dispatches the guarded release
action and returns `stale`. Caught current errors dispatch only a plain error code
and return `cancelled` for the local marker or `error` otherwise. Live objects and
the error object are not returned into Redux. Setup before the try, including
cloning/dispatch, is not covered by that catch. There is no transport abort or
storage rollback implemented by this helper.

The whole 1,661-line unit test file was read, including helpers. Its `save` helper
uses real `CalModifyTransaction` commits with scheduling response NONE unless
overridden. Setup registers memory calendars; selected tasks register a storage
destination. `saveWithDuplicateId` temporarily intercepts provider error reporting
and restores it in finally. The manifest lists the file at line 13; registration
is not a run result.

Direct checks include successful edit/move and undo/redo; retained disabled-row
values after failure; rejection of duplicate requests; stale success/failure;
overlap and move aliases; prompt cancellation; live read-only/item/move permission;
invitation edit rejection; base/optional-field dirty-state separation; local
timezone/date changes; notification code/old/new data and serializable results;
guarded release of only the original stale request; recurrence shifting; and
failed-move recovery. Specific queue, recurrence, and recovery records give their
exact task anchors.

Scheduling is replaced with a collector in the dispatch-data and recovery tasks.
Those are direct assertions of dispatch arguments and absence, not remote delivery
tests. Error paths using a delayed fake `transact` do not check a real provider
failure. Unit setup bypasses production controls; it does not establish every
browser interaction, organizer `SENT-BY` variant, field adapter, or provider.

## Source and validation

Thunderbird revision: `87d0159c7149a43253964c2cb6917939557dc799`. Firefox revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.
Paths and line ranges in this note refer to those commits. Read the source with
`git show REVISION:repository-relative-path` in the corresponding repository.
This note records checked static behavior. It does not record a passing product
test, a build result, or all possible runtime states. The test links describe
the assertions that were read. No deliberate instructions or source files changed.
