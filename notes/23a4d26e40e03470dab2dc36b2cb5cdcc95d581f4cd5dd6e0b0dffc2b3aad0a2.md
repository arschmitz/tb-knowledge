<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:34:44.592Z","paths":["mailnews/imap/src/nsImapService.cpp","mailnews/imap/test/unit/test_fetchWhileLocked.js"],"source":{"reference":"knowledge-record:23a4d26e40e03470dab2dc36b2cb5cdcc95d581f4cd5dd6e0b0dffc2b3aad0a2","recordId":"23a4d26e40e03470dab2dc36b2cb5cdcc95d581f4cd5dd6e0b0dffc2b3aad0a2","status":"supported","publicationKey":"0165239a38b2bffca7b4a884cad55814a7affe311b274b8c28a2b1dd90bb002b"}} -->
# Guard document-shell decisions when the message consumer is headless

Current LoadMessage checks aDisplayConsumer before reading its browsing context and active state. Headless consumers such as the lock test pass null. The mark-read/peek decision also accounts for the automatic-marking preference, delayed marking and the explicit markRead=false URI option. Cache availability is recorded separately. Guarding this optional consumer preserves non-UI service calls; it does not establish that every downstream listener is optional.

Scope: mailnews/imap/src.

## Evidence

[Lesson record](../records/23a4d26e40e03470dab2dc36b2cb5cdcc95d581f4cd5dd6e0b0dffc2b3aad0a2.json).

- [Supporting record](../records/06ad5d628557907eb0217f42f55e5d070e4f9dcc4a0b5b3f06fb8630d51949df.json)
- [Supporting record](../records/701f473862230f1766dec50769eef9833455409654d97d2bc4db7a874a2fb26a.json)
- [Supporting record](../records/b5c7e0ab18a0230b3ec7309556f2023a3065c42ef085c437842d90fbca69e9fa.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
