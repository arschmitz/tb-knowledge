<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T14:29:58.626Z","paths":["mail/test/browser/keyboard/browser_pdfSpace.js"],"source":{"reference":"knowledge-record:4f6fde4bd4601bb9fc992e9df9461c5d27feb2c47f06beffbedafc439bd1389b","recordId":"4f6fde4bd4601bb9fc992e9df9461c5d27feb2c47f06beffbedafc439bd1389b","status":"supported","publicationKey":"7bcd1b12db3d8818f379b69016784199db8a06290262b8e473056569da9ab78e"}} -->
# The PDF save test observes an actor message rather than a downloaded file

The new Ctrl+S test waits for PDF text-layer rendering and intercepts sendAsyncMessage. It resolves only when that intercepted call is PDFJS:Save, then reaches an unconditional assertion. It deliberately avoids a real download, so it does not assert file contents or a saved path. The override deletes itself on its first invocation; a different first message is forwarded and leaves the local Promise unresolved. Those are static scope and ordering limits, not an observed intermittent failure.

Scope: PDF content-tab browser test.

## Evidence

[Lesson record](../records/4f6fde4bd4601bb9fc992e9df9461c5d27feb2c47f06beffbedafc439bd1389b.json).

- [Supporting record](../records/7445dd339c31aec2f4e580e7addf3426f6b0a0ddbe094eba111ff53b9e0ab32d.json)
- [Supporting record](../records/a770df0a9a40dcfea4f30f254aef71b5ff0e589aebf0d0b8a35106775a88862c.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
