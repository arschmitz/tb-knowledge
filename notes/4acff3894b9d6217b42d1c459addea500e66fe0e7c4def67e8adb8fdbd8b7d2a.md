<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:18:52.283Z","paths":["mail/components/addrbook/test/browser/browser_display_card.js","mailnews/test/resources/MockExternalProtocolService.sys.mjs"],"source":{"reference":"knowledge-record:4acff3894b9d6217b42d1c459addea500e66fe0e7c4def67e8adb8fdbd8b7d2a","recordId":"4acff3894b9d6217b42d1c459addea500e66fe0e7c4def67e8adb8fdbd8b7d2a","status":"supported","publicationKey":"c6dff3005b781e29abd218b509ab155b571c1052f4f97b81713e1131cc77da3a"}} -->
# A contact link test must wait for the actual external handoff

The accepted browser_display_card test gets promiseLoad before the click and asserts the resulting exact URI. It scrolls the xmpp anchor into view first. The mock replaces the XPCOM service and resolves when loadURI is called; this proves an attempted service handoff in the test, not that an operating-system application successfully opened. No browser test ran. This is source and test-code inspection. Complete Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mail/components/addrbook.

## Evidence

[Lesson record](../records/4acff3894b9d6217b42d1c459addea500e66fe0e7c4def67e8adb8fdbd8b7d2a.json).

- [Supporting record](../records/024c7f5e23ce3a0c0fca0b5fcb16716651b7af55bc0558dd50bea43516cd2000.json)
- [Supporting record](../records/977252e4a6d189c738b9c4c5b0de252b752143c66c66b1e083fedccce62ce001.json)
- [Supporting record](../records/a677994397d80b31fb4b3d79d75b0686999a7fcee0807d69cc7e14458eaf14ec.json)
- [Supporting record](../records/bd7ad04f3510801f58e46ab84f4758240bc81fef758e5b4d78099c8bc0c0219f.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
