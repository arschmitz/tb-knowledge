<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T02:49:37.266Z","paths":["mail/components/accountcreation/modules/GuessConfig.sys.mjs"],"source":{"reference":"knowledge-record:f3a3c5ce57ed5de07624f953f2cf8de57eb4bcc50e600fe5be6fe8ea5c5a4ec0","recordId":"f3a3c5ce57ed5de07624f953f2cf8de57eb4bcc50e600fe5be6fe8ea5c5a4ec0","status":"supported","publicationKey":"12ede3f4c3883434b2c72c62a01975b00ddd7fe246e0f1c0bc799bce49e41cf5"}} -->
# Reject strict certificate failures with the NSS diagnostic

838 makes account discovery throw an exception carrying the NSS service error message for a certificate failure when requireGoodCert is true. The current path also logs hostname and port and rejects through its catch/abort path. The relaxed path still delegates to processCertError. Preserve this strict-versus-interactive distinction rather than swallowing the reason or treating every connection failure as a certificate prompt.

Scope: Account discovery certificate policy.

## Evidence

[Lesson record](../records/f3a3c5ce57ed5de07624f953f2cf8de57eb4bcc50e600fe5be6fe8ea5c5a4ec0.json).

- [Supporting record](../records/053dd4fa439c1ddfa020d001177a883f2b341e66c683aa0c38ad9066cf5b2993.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
