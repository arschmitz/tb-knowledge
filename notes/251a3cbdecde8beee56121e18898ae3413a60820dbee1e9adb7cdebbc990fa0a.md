<!-- knowledge: {"repository":"thunderbird","at":"2026-10-17T21:45:28.999Z","paths":["mail/base/test/unit/head_mailbase.js","mail/base/test/unit/test_migrateTryStartTLS.js","mail/base/test/unit/test_qrExport.js"],"source":{"reference":"knowledge-record:251a3cbdecde8beee56121e18898ae3413a60820dbee1e9adb7cdebbc990fa0a","recordId":"251a3cbdecde8beee56121e18898ae3413a60820dbee1e9adb7cdebbc990fa0a","status":"supported","publicationKey":"00cf336ad7794783ea95aecde826d76c7c80ad9a9096b70ae36b794f8a853f7d"}} -->
# Move test-only dependencies out of a shared head when only a few tests use them

The mail/base/test/unit head now only initializes the profile. test_migrateTryStartTLS.js and test_qrExport.js import MailServices themselves; unused shared imports and the directory-wide mailShutdown cleanup are removed. The bug links this setup to a permanent test failure, while review reports that the repair works. This supports the dependency split in this test directory. It is not a blanket rule against shared heads or cleanup hooks. No test was executed here.

Scope: Test head dependencies.

## Evidence

[Lesson record](../records/251a3cbdecde8beee56121e18898ae3413a60820dbee1e9adb7cdebbc990fa0a.json).

- [Supporting record](../records/1c081e7b6d2a567295a9653799edaab378481c0e8e262025f44db51ed43cf909.json)
- [Supporting record](../records/38ab993da0cbd7595d1b0019939d675060fd75cf3e74cef03415f8d42c8ceabb.json)
- [Supporting record](../records/580b6b325d4985b34ca36d14f552bd9d953ca3e1bf344e0315d2315c1f9ad76c.json)
- [Supporting record](../records/d0e67df33150188abc489f48d0f94fa8764cf1968d9f022787adeb1b3551c14f.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
