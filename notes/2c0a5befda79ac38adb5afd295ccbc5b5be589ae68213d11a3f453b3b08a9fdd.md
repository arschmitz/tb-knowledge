<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T11:34:08.515Z","paths":["mail/modules/MailE10SUtils.sys.mjs","mail/base/content/browserRequest.js","mail/base/content/specialTabs.js"],"source":{"reference":"knowledge-record:2c0a5befda79ac38adb5afd295ccbc5b5be589ae68213d11a3f453b3b08a9fdd","recordId":"2c0a5befda79ac38adb5afd295ccbc5b5be589ae68213d11a3f453b3b08a9fdd","status":"supported","publicationKey":"d9f19ef45b7a1f0b60ecbec83611fb8e2610df0fe4251072e204d120ae20594c"}} -->
# MailE10SUtils predicts with a parsed URI but loads the original URL string

The port names the string parameter url, parses a separate nsIURI for predictRemoteTypeForURI and still sends the original string to fixupAndLoadURIString. It supplies browser.documentGlobal as prediction context and preserves the existing principal fallback and remote-presence decision. Actual request and content-tab callers pass strings, but the inspected wrapper does not prove all fixup inputs or the external engine predictor have equivalent behavior. This is a local type/name and call-boundary fact, not a global naming rule or process-isolation guarantee.

Scope: Thunderbird browser process-selection wrapper.

## Evidence

[Lesson record](../records/2c0a5befda79ac38adb5afd295ccbc5b5be589ae68213d11a3f453b3b08a9fdd.json).

- [Supporting record](../records/26367fc2ae9e1a428664eb853416748c9fbdbbaa101b738502f8c7b5f3a94236.json)
- [Supporting record](../records/6907ccfd8ea30ac7b2153c4cfdc2cea54e6b4fa5f5c3cdb54e8e45246a1ed693.json)
- [Supporting record](../records/6c9a7fb06f9658526e4288ab6537a74de6c47e589029dcb90597ea23b04a3ddf.json)
- [Supporting record](../records/be52a69de9fd9556b868ae442d964b09000185b4b0785e3e6e5ba46073116e59.json)
- [Supporting record](../records/dc91fe117b83c069b60e78a5998ee9f8be7f7fad0a9c93a89f80b0dd12eab14e.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
