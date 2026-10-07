<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:11:15.961Z","paths":["mail/base/test/browser/browser_clickLinks.js"],"source":{"reference":"knowledge-record:e3c682df78b98c6e3acefd1cd54377ae1ac2a9f1cbc9ddaaf4e5a2b311d71f8a","recordId":"e3c682df78b98c6e3acefd1cd54377ae1ac2a9f1cbc9ddaaf4e5a2b311d71f8a","status":"supported","publicationKey":"61ced14026f379a17d8c9e63ce4fbd576f91acc43cf50a9a178922345cf5bc0d"}} -->
# Await each external-link assertion before starting the next click

The historical 928 test calls its asynchronous click_element helper four times without awaiting it. The accepted test awaits each click, waits for MockExternalProtocolService.promiseLoad, checks the URL and resets the mock. The newer source establishes the preferred sequencing for this test; it is not proof that the original patch caused an observed intermittent failure. Each asynchronous test helper must be joined before cleanup or the next operation consumes shared state.

Scope: Message link test asynchronous sequencing.

## Evidence

[Lesson record](../records/e3c682df78b98c6e3acefd1cd54377ae1ac2a9f1cbc9ddaaf4e5a2b311d71f8a.json).

- [Supporting record](../records/37f700a12776c119a674c0ca2167791bd0762926b67299597b91000a72514a95.json)
- [Supporting record](../records/b81158a449a9bc9ef3c725e14e4e00d53007006cb8697fa9320487907b0217b4.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
