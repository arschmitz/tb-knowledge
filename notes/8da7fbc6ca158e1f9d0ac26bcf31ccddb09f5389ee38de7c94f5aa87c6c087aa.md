<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:41:44.854Z","paths":["mail/base/content/modules/DarkReader.mjs","mail/base/test/unit/test_darkReader.js"],"source":{"reference":"knowledge-record:8da7fbc6ca158e1f9d0ac26bcf31ccddb09f5389ee38de7c94f5aa87c6c087aa","recordId":"8da7fbc6ca158e1f9d0ac26bcf31ccddb09f5389ee38de7c94f5aa87c6c087aa","status":"supported","publicationKey":"496d6084a34a9e31078c5f0a6288c3f27162df4f5dbd3247f00c1cea93c15edc"}} -->
# Treat DarkReader luminance and contrast as this heuristic’s functions

1127 exposes the color helpers and adds tests for invalid colors, white/black contrast, white/#ccc contrast and transparency. luminance is a weighted sum of raw 0–255 color channels, and contrast divides those values with 0.05 offsets. These checks support this implementation's threshold behavior; they do not establish a WCAG relative-luminance calculation or an accessibility compliance result. Keep heuristic names/limits clear before using the function for another contrast decision.

Scope: Dark-reader color heuristic and test limit.

## Evidence

[Lesson record](../records/8da7fbc6ca158e1f9d0ac26bcf31ccddb09f5389ee38de7c94f5aa87c6c087aa.json).

- [Supporting record](../records/0ed150605e164162bbc5f043b7ac0961af2ff6024232a20186e33b7c7559f30f.json)
- [Supporting record](../records/3c6026308b94b9a548c4db4ebd5fc1ba6975782a0587a52d92c22e0bc72eeb6a.json)
- [Supporting record](../records/572659cf896f66da6f6542378d1bccd2113cc94ecac4f0bbd0148f1c1fee47e0.json)
- [Supporting record](../records/799af5f8dbb4f38482112c9470c558c66886b2fe2910598c5cf06d748d7f6434.json)
- [Supporting record](../records/ae61a213b7fcd47d78a445543b873766fc28a8e57c7ea894eece3fcc1514dfce.json)
- [Supporting record](../records/d63e85e93f69fb21110d114ebfa7cb94bdcada86571c9129a435ab207edd0405.json)
- [Supporting record](../records/da405e2b1c9293013994eb3deb82da09f491ad005a0058394d27f4abbf03974b.json)
- [Supporting record](../records/f77dd189fa36766f8a14f26770b95f1dfbdeae276df31ba84a407f18700cd7c7.json)
- [Supporting record](../records/f928081cf27993a20ad00e1617ce32bb59a26fb5a7aac99c5f513b4e6969d7e2.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
