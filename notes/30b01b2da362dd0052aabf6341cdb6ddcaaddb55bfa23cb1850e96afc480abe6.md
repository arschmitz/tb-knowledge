<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T22:53:05.840Z","paths":["mail/test/browser/composition/browser_smtpCancel.js","mailnews/compose/test/unit/test_smtpCancel.js","mailnews/compose/content/sendProgress.js"],"source":{"reference":"knowledge-record:30b01b2da362dd0052aabf6341cdb6ddcaaddb55bfa23cb1850e96afc480abe6","recordId":"30b01b2da362dd0052aabf6341cdb6ddcaaddb55bfa23cb1850e96afc480abe6","status":"supported","publicationKey":"2933a76a919965cb56f737060bf8ca113772abb1a88cbb67478f16561b2f503f"}} -->
# SMTP cancellation tests separate progress routing, queued sends and request status

The browser case checks progress Cancel routing through a fake outgoing request and records whether its cancel callback actually ran. Unit cases separately cover active/queued MessageSend status through a fake send callback and direct request cancellation with a fake server. Their expected structures require NS_ERROR_ABORT without reported success, while fixed observation/time-out windows and substituted callbacks limit the coverage. Accepted later production cancellation and preference-setup changes are separate phases; no test was executed.

Scope: SMTP cancellation regression test coverage.

## Evidence

[Lesson record](../records/30b01b2da362dd0052aabf6341cdb6ddcaaddb55bfa23cb1850e96afc480abe6.json).

- [Supporting record](../records/a92afc641206d4bc9a839e45f0b37aaf60b9a3b1bcd810a295dd862471980ecd.json)
- [Supporting record](../records/c890f226dc2ae1aee7a33838e045ca1accaa5b3d3e6758159ef8d659d826e2a1.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
