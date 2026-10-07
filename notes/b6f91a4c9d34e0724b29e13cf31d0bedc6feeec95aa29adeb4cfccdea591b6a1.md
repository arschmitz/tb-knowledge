<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:11:15.938Z","paths":["mail/test/browser/message-reader/browser_convertToEventOrTask.js"],"source":{"reference":"knowledge-record:b6f91a4c9d34e0724b29e13cf31d0bedc6feeec95aa29adeb4cfccdea591b6a1","recordId":"b6f91a4c9d34e0724b29e13cf31d0bedc6feeec95aa29adeb4cfccdea591b6a1","status":"supported","publicationKey":"1ab5728d0dc2bbd432ab40b04ead4abe7365dbee7898478d725b0a04af1988d1"}} -->
# Wait for the copied message before closing its source window

922 fixes an intermittent test by waiting until its new destination folder contains one message before closing the message window and clicking row zero. Closing the window or opening the folder alone does not prove that the copy has become visible. Use the operation result required by the next step as the wait condition. The source observes folder count, not the copy callback status. The linked green Try run was not opened.

Scope: Message conversion test synchronization.

## Evidence

[Lesson record](../records/b6f91a4c9d34e0724b29e13cf31d0bedc6feeec95aa29adeb4cfccdea591b6a1.json).

- [Supporting record](../records/a493b7592809241398203cb75bd38002b7793b4b2e3f95252d660cf7f1b616b0.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
