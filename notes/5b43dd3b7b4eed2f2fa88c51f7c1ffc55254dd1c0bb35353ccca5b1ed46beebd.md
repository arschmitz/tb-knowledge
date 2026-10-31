<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T07:02:15.845Z","paths":["mail/base/content/widgets/glodaFacet.js","mail/base/content/glodaFacetView.js","mailnews/db/gloda/modules/GlodaFundAttr.sys.mjs","mailnews/db/gloda/modules/NounMimetype.sys.mjs","mailnews/db/gloda/modules/GlodaQueryClassFactory.sys.mjs"],"source":{"reference":"knowledge-record:5b43dd3b7b4eed2f2fa88c51f7c1ffc55254dd1c0bb35353ccca5b1ed46beebd","recordId":"5b43dd3b7b4eed2f2fa88c51f7c1ffc55254dd1c0bb35353ccca5b1ed46beebd","status":"supported","publicationKey":"22c1d1d35a7d86420acdafff1a0bb87015cf9eb3c684451d293a1c33272c3731"}} -->
# The unchecked attachment facet resets its selector but reinstates an attachment-presence query

The base checked setter removes the facet constraint before calling checkStateChanged. The subclass's unchecked branch then resets the dropdown and calls the replacement helper with empty trueGroups. For the registered attachmentTypes Category helper, that empty list creates an in-constraint that tests attachment presence. Resetting visible all state therefore does not prove the constraint stays removed. The accepted code retains this source sequence; no search or UI reproduction was run.

Scope: Filtered checkbox state callback and actual Gloda constraint receiver.

## Evidence

[Lesson record](../records/5b43dd3b7b4eed2f2fa88c51f7c1ffc55254dd1c0bb35353ccca5b1ed46beebd.json).

- [Supporting record](../records/0a4cee12358dfd3a3827ebb4b1190382621ffe3e482a90cec56a386558212563.json)
- [Supporting record](../records/30f9af949e95d0464cb96408637658c5f745a72bba2ba23a8a720f9638d1ce43.json)
- [Supporting record](../records/4de4c4b7b1aafda4e622bd4ecfa58e418d0bcbf27128ada7bdd1cf9ae2f7c2e6.json)
- [Supporting record](../records/bc22e36a15581ac9b076e585327ba05c2957abd614d467816b4cfbb0667bda7b.json)
- [Supporting record](../records/c45519859ca2d6f52395664a5d3f221dbe77c699e1d81588368060bf598b0967.json)
- [Supporting record](../records/d5a3ca3dcc0e3d080a7ab8ee2b46b0ecb3245c4ba99a59ed2015a9bd85189b0e.json)
- [Supporting record](../records/d6d068a27c91cc97368c6900885ab5b4111e7f55d154502e2dc6fbb3374375d9.json)
- [Supporting record](../records/f15d558b43eeb2760efa5fb132be9a69dc1a481d3898e0631c22bbc07faec6eb.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
