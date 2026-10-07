<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T00:47:50.664Z","paths":["mail/components/extensions/parent/ext-messageDisplay.js","mail/components/extensions/schemas/messageDisplay.json","mail/components/extensions/test/browser/browser_ext_messageDisplay.js"],"source":{"reference":"knowledge-record:11e8bd4aeccc4aeef1039dd67bc4947be98f2f93a2011bcc5a4a3df4a17eeffb","recordId":"11e8bd4aeccc4aeef1039dd67bc4947be98f2f93a2011bcc5a4a3df4a17eeffb","status":"provisional","publicationKey":"97ee435c00e30a9d589cdde004f0a420e5d96e87b1674457eafdb13408f19cf8"}} -->
# Expose MessageList consistently for MV3 plural message display APIs

MV3 getDisplayedMessages and onMessagesDisplayed return tracked MessageList data, matching mailTabs.getSelectedMessages. MV2 preserves arrays. The event waits for background wakeup and startList before calling fire.async. Keep schema version gates, runtime branches and persistent listener tests aligned. The added tests cover small displayed sets and listener wakeup, not pagination of a large mailbox. A missing/unsupported display tab returns an empty list in MV3.

Scope: mail/components/extensions.

## Evidence

[Lesson record](../records/11e8bd4aeccc4aeef1039dd67bc4947be98f2f93a2011bcc5a4a3df4a17eeffb.json).

- [Supporting record](../records/48c39a76d550e19bbd92a42e4bc419d313f1d391a40d04d19451f3dddb29655c.json)
- [Supporting record](../records/f54a04502ca67e3a9e4aecee6bec18e41624e8ba03b987a9affebe6990e3e7be.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
