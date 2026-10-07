<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T07:37:16.174Z","paths":["mail/base/content/mailContext.js"],"source":{"reference":"knowledge-record:7ace0b47dfdd34ab90e786809a9e50ef392f2ece17ddbcbee3f49f829ac4ddac","recordId":"7ace0b47dfdd34ab90e786809a9e50ef392f2ece17ddbcbee3f49f829ac4ddac","status":"supported","publicationKey":"3581e74f9f01bc6856c6ec1f50bd93101a4defa5e5042b326bf6d945e348aff2"}} -->
# A browser context can have no local window document when saving a link

1955 changes the sourceDocument argument to browsingContext.window?.document. Current Save Link and Save Image both use that optional local-window access. Preserve absence of a local window for remote content; the fix does not grant access to a remote document or prove all saveURL parameters are optional. The system principal and other arguments remain explicit in this call. This is static source and test-code inspection. No runtime, build, lint or live accessibility check ran. Full Bugzilla and historical review timeline and inline discussion remain pending; source landing does not prove approval of a proposed manual rule.

Scope: mail context save behavior.

## Evidence

[Lesson record](../records/7ace0b47dfdd34ab90e786809a9e50ef392f2ece17ddbcbee3f49f829ac4ddac.json).

- [Supporting record](../records/19a69049845051fe9a6da421162fe33f3cfa03897339179cbd7875b281756287.json)
- [Supporting record](../records/841ead4d2d56bf50aabb90c526e9dc53b1e487b78037346d646be511ce12997f.json)
- [Supporting record](../records/fdeae941507437d4d8df4d0fc449a91aca6a35cdabe1a1cc9a302eae3b038adf.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
