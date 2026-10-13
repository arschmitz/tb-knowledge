<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T04:47:12.984805+00:00", "paths": ["mail/components/calendar/content/calendarEventCreateEditDialogTemplate.inc.xhtml", "mail/components/calendar/content/calendar.inc.xhtml", "mail/components/calendar/content/calendar-event-create-edit-dialog.mjs", "mail/locales/en-US/messenger/calendarDialog.ftl", "mail/themes/shared/mail/calendar/calendarDialog.css", "mail/themes/shared/jar.inc.mn", "mail/base/content/messenger.xhtml", "mail/components/calendar/test/browser/files/calendarEventCreateEditDialog.xhtml", "mail/components/calendar/test/browser/browser_calendarEventCreateSave.js"], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "status": "supported", "study": "architecture-relationships-20261013", "verification": "Static implementation, caller, consumer, and named assertion review; tests not run"}} -->
# Verified chain: Calendar template, Fluent status, CSS scope, packaging, and UI tests

Scope: Thunderbird Calendar UI. Production markup, JavaScript, CSS, localization, packaging, test markup, and browser tests have separate roles.

## The checked consumers

`messenger.xhtml` includes `calendar.inc.xhtml`, which includes `calendarEventCreateEditDialogTemplate.inc.xhtml`. The template defines `calendarEventCreateEditDialogTemplate`, the Save button's `.calendar-event-save` class, the `.calendar-event-save-status` span, and the dialog body's `.calendar-event-create-edit-dialog-body` class.

The dialog's `connectedCallback()` gets this exact template ID, clones its content into the dialog, and registers the exact Save button selected inside that dialog. This is a checked connection through a cloned node tree, not a class-name match between unrelated files.

`#renderSave()` finds the body inside that same dialog and sets `aria-busy`. It disables Save while work is pending or after success. It sets the status span's Fluent ID to `calendar-event-saving`, `calendar-event-save-failed`, or `calendar-event-save-idle` according to the operation. The template supplies `calendar-event-save` for the button.

`connectedCallback()` requests `messenger/calendarDialog.ftl`. That file defines all four IDs. The failure ID gives retry text; the idle ID produces empty text. The status span has `role="status"` and `aria-live="polite"`. These attributes and the translated text have different responsibilities.

## CSS and packaging

`messenger.xhtml` loads `chrome://messenger/skin/calendar/calendarDialog.css`. `mail/themes/shared/jar.inc.mn` maps that resource to `mail/themes/shared/mail/calendar/calendarDialog.css`. The style rule `[is="calendar-event-create-edit-dialog"]` scopes nested rules, including the header, calendar selector, and scrollable body. The dialog sets this exact `is` attribute; the template supplies those descendant classes.

This proves the production resource link, package mapping, scope selector, and markup consumers at the pinned source. It does not prove every computed style or the effect of every later style rule. The browser fixture loads the same stylesheet and its own copied dialog template, plus shared widget styles.

## Tests and important limits

Direct: `test_rowTogglePendingFailureAndKeyboardRetry` reads the exact Save/status/body nodes and asserts busy state, disabled/enabled Save, failure Fluent ID, retry text, accessible status role, and polite live behavior. `test_keyboardSaveSelectedCalendarAndUndoRedo` checks the button's accessible name and keyboard focus.

Executed but not directly asserted in these tasks: the general CSS layout rules and package resolution. A displayed fixture does not prove the production template and fixture template cannot drift apart. The two templates are separate source files. A later pass should check their shared contract and production-window integration tests.

Possible only: another CSS or Fluent occurrence with the same name. Resource discovery maps do not prove it applies to this document. Changes to template IDs, class names, Fluent IDs, package paths, busy state, or live-region attributes can affect both the production path and these tests.

## Original evidence and validation

- [New Calendar event Save validates a snapshot and rejects stale completion](9fef655b-20e0-4446-83d4-f5ee6658e8d8.md)

The source paths and symbols above are stable anchors at `87d0159c7149a43253964c2cb6917939557dc799`. Use `git show REVISION:path` in the corresponding source clone. Both revisions are recorded for cross-repository chains. The implementation, callers, consumers, and stated test assertions were read. This is static evidence. No product tests or build ran for this study, and no past passing result is imported. Test registration, execution coverage, direct assertions, and observed passing runs are separate facts. Unread branches and unresolved targets remain gaps.
