<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T08:04:35.942Z","paths":["mailnews/base/public/nsIMsgPluggableStore.idl","mailnews/base/src/FolderCompactor.cpp"],"source":{"reference":"knowledge-record:1aa4eb0caf6fdb7eaf69988d929bbb187468aaf7f0aaf92ebcf04f5e757c7cac","recordId":"1aa4eb0caf6fdb7eaf69988d929bbb187468aaf7f0aaf92ebcf04f5e757c7cac","status":"supported","publicationKey":"4c804118dba90cd04de2338a255dcc55b53be84537a66f7d0cac5a06ea33e25e"}} -->
# Final compaction sizes are valid only on success and header patching can increase size

The IDL states that oldSize/newSize are undefined for a failure result and that X-Mozilla header patching can increase store size. FolderCompactor accumulates recovered-space telemetry only on success, while its completion callback still receives the arithmetic result with the status. Scoped caller recommendation: gate any interpretation of the byte difference by successful status rather than assuming every compaction shrinks or every failure has meaningful sizes. This is static source and test-code inspection at the frozen accepted revision. No runtime, build, lint or live accessibility check ran. Full Bugzilla and Phabricator timeline and inline discussion remain pending; a landing does not prove approval of a proposed manual rule.

Scope: mbox compaction final size contract.

## Evidence

[Lesson record](../records/1aa4eb0caf6fdb7eaf69988d929bbb187468aaf7f0aaf92ebcf04f5e757c7cac.json).

- [Supporting record](../records/488a6b0b98520ff632997c98a25ab3630c513df88b009712a7ef87bcd0c39450.json)
- [Supporting record](../records/86b94499e18fb2e6e95f11afcebff4b145cac57cabf87e97d72ff2e82b5b8fb4.json)
- [Supporting record](../records/9ddb347935b34ab92f1720532969215032a9297b1cab6fbdfd7236340e92f57e.json)
- [Supporting record](../records/f492a908a4c9371c7ad7322a303cc7dcbb306980fd309caa0db6de23a879d234.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
