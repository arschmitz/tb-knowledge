<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T01:21:41.754Z","paths":["mailnews/base/src/OAuth2Providers.sys.mjs","mailnews/base/src/OAuth2Module.sys.mjs","mailnews/base/src/OAuth2.sys.mjs","mailnews/base/test/unit/test_oAuth2Providers.js"],"source":{"reference":"knowledge-record:f1e482e524fe36aeebe8f287dbba8edbfa38ccc4a7f68457bf6fea648fc17f23","recordId":"f1e482e524fe36aeebe8f287dbba8edbfa38ccc4a7f68457bf6fea648fc17f23","status":"supported","publicationKey":"6d7d863ed887b509e2a2ea743d0d0cc1c2d3aa1ef8bbf1d96a5f887de176079a"}} -->
# ATT OAuth host support reuses Yahoo lookup without adding browser isolation

The owned change replaces protocol-specific Yahoo host entries with yahoo.com and adds att.net, both mapped to login.yahoo.com with mail-w. Its existing lookup removes complete leftmost hostname labels, so mail subdomains reach the parent-domain mapping. The accepted implementation retains these keys with wider scopes, lowercase built-in lookup and later extension/type rules; those are separate phases. Mail and outgoing initialization pass the configured server hostname and username. Current OAuth object reuse checks login origin, authorization endpoint, username and required-scope containment. The checked internal request-window start path independently selects private/non-private mode from the global mailnews.oauth.usePrivateBrowser preference; these paths do not select a per-user browser container. Generic subdomain assertions and ATT/Yahoo exchange-rejection assertions are direct source evidence, not live ATT mail authentication or cookie-isolation tests. No login or test ran.

Scope: mailnews/oauth/provider-lookup.

## Evidence

[Lesson record](../records/f1e482e524fe36aeebe8f287dbba8edbfa38ccc4a7f68457bf6fea648fc17f23.json).

- [Supporting record](../records/2da257579684a5f8852655a670c42ffaee48196b1077a4cd5a70c7161c552cde.json)
- [Supporting record](../records/456ef1bbed8c01ed3a31684e3f46fd935fcb6f5d12903e8ef38c0902c2410240.json)
- [Supporting record](../records/b1e24f9259f17098cb4f7e9cb6de3c8fb24c4d695e8b582b99227f1eb2d615d7.json)
- [Supporting record](../records/c647aa1c264491fed18f836a107094e4f3af1983a3886288942430b87984c83b.json)
- [Supporting record](../records/dc34e732399b141fe5250ab730c5d72eafd7e9d5b39c0291512845a980d3416a.json)
- [Supporting record](../records/de0b88aa30c51536df528875c58fa5b22d2bfd6eadd9f1fa21bc2df784b37662.json)
- [Supporting record](../records/f6e2e7d24cdf95251943516db793761c3542d458b21b9b5ea8321ce9349c7bde.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
