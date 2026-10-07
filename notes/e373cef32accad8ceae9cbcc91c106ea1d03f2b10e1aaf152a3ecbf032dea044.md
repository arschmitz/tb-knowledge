<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T07:06:20.490Z","paths":["mail/test/browser/shared-modules/NewMailAccountHelpers.sys.mjs","mail/test/browser/shared-modules/CleanupHelpers.sys.mjs"],"source":{"reference":"knowledge-record:e373cef32accad8ceae9cbcc91c106ea1d03f2b10e1aaf152a3ecbf032dea044","recordId":"e373cef32accad8ceae9cbcc91c106ea1d03f2b10e1aaf152a3ecbf032dea044","status":"supported","publicationKey":"7868b06d1c9b1e132c0c21f56636dca3b123c3c316ac9693d4f49cb3760946b1"}} -->
# Keep one-account cleanup distinct from baseline-preserving test cleanup

The deleted remove_email_account stopped after removing the first account whose default identity matched an address. The accepted CleanupHelpers records initial server/account/outgoing keys, then removes only objects not present at the start. These are different scopes; the commit does not establish a direct replacement or that the broader cleanup should run whenever one account is removed. Choose cleanup based on the fixture’s ownership, and preserve pre-existing test-manifest objects. This is static source and test-code inspection at the fixed accepted revision. No runtime, build, lint or live accessibility check ran. Full Bugzilla and historical review timeline and inline discussion remain pending.

Scope: mail test cleanup scope.

## Evidence

[Lesson record](../records/e373cef32accad8ceae9cbcc91c106ea1d03f2b10e1aaf152a3ecbf032dea044.json).

- [Supporting record](../records/0246951958c64ad7db113c57b0d7742c16be2252d8dcbf529dee3ee98a58a79d.json)
- [Supporting record](../records/9970221147688885a8f1be8fc0515d1b9b394ddb2e834a306e18643992e68175.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
