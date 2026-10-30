<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T17:13:51.242Z","paths":["mailnews/base/src/OAuth2.sys.mjs","mailnews/base/test/unit/test_oAuth2Module.js"],"source":{"reference":"knowledge-record:f6ca6e8ffed9fa60f2a4eb19544ccff9c58fafc4c6af947f384e8e726b9f0a4f","recordId":"f6ca6e8ffed9fa60f2a4eb19544ccff9c58fafc4c6af947f384e8e726b9f0a4f","status":"supported","publicationKey":"9e011f9bcba202e586d630492f7cd34662f29396c78293959412728d213d599d"}} -->
# Issuer identification uses exact configured strings and an origin-based fallback

When issuerIdentifier is configured, checkResultURL requires the decoded iss query value to equal it exactly; the added tests accept URL encoding but reject a trailing slash or missing identifier. With no configured identifier, a nonempty iss is parsed and its origin must match the authorization endpoint's origin. This keeps scheme/host/port comparison rather than the proposed looser domain comparison. The helper finally requires code parameter presence. Its new URL(iss) fallback has no local catch, and the new task does not test malformed identifiers, so its Boolean JSDoc is not an all-input no-throw guarantee. These are static source and assertion contracts, not protocol/security execution.

Scope: OAuth callback issuer validation.

## Evidence

[Lesson record](../records/f6ca6e8ffed9fa60f2a4eb19544ccff9c58fafc4c6af947f384e8e726b9f0a4f.json).

- [Supporting record](../records/02934d62e83958f5d593bdd9a219579923281d06db3331fa72d2af5205c67b0a.json)
- [Supporting record](../records/1a76f61f621840d16ebf254338224ccd343a0f753ca1ed6885365f18017d8933.json)
- [Supporting record](../records/46a7998d2d65f8489c05e8c1eb0c7145be10efe1efd4e6f336d00061942442a1.json)
- [Supporting record](../records/6b07f8b45d0a12e7479bf56346eec947053fc23eee5c73dacc4780488408fb10.json)
- [Supporting record](../records/791575c38d2cde24f328c71230fdf55a442a53eef178b55bf0d13807b49031c0.json)
- [Supporting record](../records/b806d02d5d2ead318606eb4ce321641419b9f3e0c9423e3360fbaf4ca66b1014.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
