<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T07:46:43.046Z","paths":["mail/test/browser/account/browser_serverSettings.js"],"source":{"reference":"knowledge-record:ef5d7e396b342c8ae9ec06aefbdbdf64373619e7bf89862ad4fa6bad8fe5d3eb","recordId":"ef5d7e396b342c8ae9ec06aefbdbdf64373619e7bf89862ad4fa6bad8fe5d3eb","status":"supported","publicationKey":"4a0964ed3c533dc11dde252ce3bc14b863d21dc5d5640471e88624e6da7a9adf"}} -->
# EWS settings reset sends keyboard input through the reopened control's window

The test closes its first advanced dialog, reopens settings and focuses ewsUrlElementReopened. The fix sends KEY_Delete through that reopened element's ownerGlobal, matching the following sendString call, instead of using the old element's window. It then accepts the new dialog and directly checks the incoming server's original URL was restored. Accepted source retains that receiver choice with later documentGlobal/exchangeUrl names. This is static event-target and assertion scope, not a reproduced native exception or a proven cure for the other reported test failure.

Scope: EWS advanced server-settings test window lifetime.

## Evidence

[Lesson record](../records/ef5d7e396b342c8ae9ec06aefbdbdf64373619e7bf89862ad4fa6bad8fe5d3eb.json).

- [Supporting record](../records/444ada3d3df26c5a123e79150b1f3644dc0c11ddf936589d883713a96dcd4f53.json)
- [Supporting record](../records/6db6cee48ddcfa4ad23fcc3d857545abcd9ae091079f43beedb5e5a72a53399c.json)
- [Supporting record](../records/93039283fbe3cb9349cc773b2aeb53fd9ff8777154e733c922306da899a2db69.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
