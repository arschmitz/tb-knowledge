<!-- knowledge: {"repository":"thunderbird","at":"2026-10-17T22:14:58.747Z","paths":["mail/extensions/openpgp/content/modules/RNP.sys.mjs","mail/extensions/openpgp/content/modules/msgRead.sys.mjs","mail/extensions/openpgp/content/ui/enigmailMessengerOverlay.js","mail/modules/AttachmentInfo.sys.mjs"],"source":{"reference":"knowledge-record:9fe972f5f2bac67f3e1eb2692ca17fda1cfffc38f54fad14a46b70b27edfbda4","recordId":"9fe972f5f2bac67f3e1eb2692ca17fda1cfffc38f54fad14a46b70b27edfbda4","status":"supported","publicationKey":"5dd57a20e0ac3005743867d83ec80697968466c19255d0e9458e63285c081e64"}} -->
# Finding a signature attachment is separate from verifying its bytes

The attachment matcher returns the first matching AttachmentInfo, or undefined. It checks an escaped filename pattern and retains the equal-name/application-pgp-signature fallback that review rejected removing. A later consumer fetches bytes, can decrypt the data and then calls RNP verification. The RNP helper converts verifyDetached exitCode with logical not. Keep those steps separate: a filename or MIME-type match is not successful cryptographic verification. Current raw-message retrieval and file saving differ from the original patch, and exception cleanup and trust internals remain outside scope. No signature verification or disk I/O ran.

Scope: OpenPGP attachment verification.

## Evidence

[Lesson record](../records/9fe972f5f2bac67f3e1eb2692ca17fda1cfffc38f54fad14a46b70b27edfbda4.json).

- [Supporting record](../records/02f3b63a1d34e9dd72c009c3c8ce900ba5de3238256eed12d717058c503c53a9.json)
- [Supporting record](../records/20206d5d3c743354ab4f64a52f25bf3217c19381f57a6df31d3c6cab04e1670c.json)
- [Supporting record](../records/6b8c669f76eeb46cd073422df0093458695875548f8a08be6d17f680ed639412.json)
- [Supporting record](../records/864279277c7b04474e0ab4042b8e31968d2fc3abe2ba8a9255c8a217b5214657.json)
- [Supporting record](../records/b59478d465f21b544c6120ceae54eab9b4523f8c9bd57f8275745d26f3bc01a9.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
