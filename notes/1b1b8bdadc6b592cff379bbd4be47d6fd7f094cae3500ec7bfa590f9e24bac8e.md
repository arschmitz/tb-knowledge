<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T04:44:06.636Z","paths":["mailnews/mime/src/mimecms.cpp","mailnews/extensions/smime/nsCMS.cpp","mailnews/extensions/smime/msgReadSMIMEOverlay.js"],"source":{"reference":"knowledge-record:1b1b8bdadc6b592cff379bbd4be47d6fd7f094cae3500ec7bfa590f9e24bac8e","recordId":"1b1b8bdadc6b592cff379bbd4be47d6fd7f094cae3500ec7bfa590f9e24bac8e","status":"supported","publicationKey":"d1cabb2ad70153af04f5603530e3fb65de7b23776c7e905739d71c8558be4d79"}} -->
# Signature algorithm metadata is separate from signature verification success

The listener classifies the verification result, then retrieves signature and digest names on both the failure and success paths. GetTopLevelSignerInfo checks signed structure rather than verification success, and the panel shows the names when present. The exact landing therefore does not restrict signature metadata to successfully verified signatures. Encryption metadata has a different explicit SUCCESS guard. These are source conditions; no malformed message, verification failure or live panel was exercised.

Scope: S/MIME signature-status and metadata display.

## Evidence

[Lesson record](../records/1b1b8bdadc6b592cff379bbd4be47d6fd7f094cae3500ec7bfa590f9e24bac8e.json).

- [Supporting record](../records/289830f17922b2c144fa0273debb96dc4a656eb29fdbb2e8cb6b0bb79efbb275.json)
- [Supporting record](../records/716cd971d0e5c03061bf960279dc330458d5b915ec5a612093c62d9328efa6bb.json)
- [Supporting record](../records/8c5b859e2dacdac7986d34ff6f01939b2ee474817738df5d93f75e058b2c56fc.json)
- [Supporting record](../records/b0d8d071c4c1291d748105233497ce581651e708e7df1c3efa7f07789a980d78.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
