<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:05:09.628Z","paths":["mailnews/base/test/unit/test_oAuth2Providers.js","mailnews/base/src/OAuth2Providers.sys.mjs"],"source":{"reference":"knowledge-record:ae2574f072573fbeb0875fee29ef8bcc3fc435e5c5e13b9ad4ced2c5daeafcce","recordId":"ae2574f072573fbeb0875fee29ef8bcc3fc435e5c5e13b9ad4ced2c5daeafcce","status":"supported","publicationKey":"dff52a9b2587be2e39c788bd8a997321599dd53cc02376df531b85e714d93a8b"}} -->
# OAuth provider tests preserve fresh object identity and distinct scope fields

The accepted provider tests change properties on one getHostnameDetails return object and then request another object to check that the mutation did not persist. They also assert allScopes and requiredScopes independently for each supported activity and Microsoft Exchange/EWS. For this return-object API, recommend checking both value meaning and instance independence; replacing an array with a shared mutable object would change more than syntax. This is scoped test guidance. No test, build or runtime operation was run. Full Bugzilla and Phabricator discussion is pending; source adoption does not establish reviewer approval.

Scope: OAuth provider object test boundaries.

## Evidence

[Lesson record](../records/ae2574f072573fbeb0875fee29ef8bcc3fc435e5c5e13b9ad4ced2c5daeafcce.json).

- [Supporting record](../records/128d0e4f5fd8fa23a7064a76fc2c3bd62dbe11aded79fb09a3ec58b32aa4f8d1.json)
- [Supporting record](../records/6b783553f9473fb61da996230520e36581fd6234420f4dc3b52d02cdec914620.json)
- [Supporting record](../records/789b3f8872bd9eccc9057281e1f20ecdc6742a5127ce522d3d30c10b08c5d782.json)
- [Supporting record](../records/7e591eb431eb9fd51513b12269dfa0900e94fd83058f72db1f01b29a624ad0fa.json)
- [Supporting record](../records/8dc6350d7da22d94687ad5002f5a687027308b51b7abfd89bf3c451bd27bf39c.json)
- [Supporting record](../records/ab2126a8b3df340825130682d11e5ccb556917be40716d06941933d02fb017e9.json)
- [Supporting record](../records/ceae28da08a4aa1ebc260d47f37c2560ef92240fa35beaa70e0ea1f23d49e27b.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
