<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T04:22:36.693Z","paths":["mailnews/test/fakeserver/GraphServer.sys.mjs"],"source":{"reference":"knowledge-record:0e89792ba7f0021a4bd38cad0ab3cdb3ca6eb4d12afb0af0adfcc8359d642cf0","recordId":"0e89792ba7f0021a4bd38cad0ab3cdb3ca6eb4d12afb0af0adfcc8359d642cf0","status":"supported","publicationKey":"74247b6733f648a2c2c4eaf1c8b921179bbf808ea15b5b2be251f2fc2bf45207"}} -->
# The initial Graph mock has a separate empty-page token edge

The historical final-page branch tests the currentChanges array itself rather than its length. An empty array remains truthy, so this branch can use at(-1) with no last change when building a token. The initial create-batching test does not exercise an empty incremental continuation. The accepted later mock obtains nextOffset from getChanges instead; that helper was not audited here, so this does not claim a reproduced failure or a fully verified current cure.

Scope: Graph message-sync mock paging.

## Evidence

[Lesson record](../records/0e89792ba7f0021a4bd38cad0ab3cdb3ca6eb4d12afb0af0adfcc8359d642cf0.json).

- [Supporting record](../records/b399f30183746ad7e1baed70a2f7f29c799058b8f6c6e22cf7ef42c4f6e96d8d.json)
- [Supporting record](../records/d9e7022dca2078e3b06a2605d3a955a31690308cb1311ec25aee440f81eaf890.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
