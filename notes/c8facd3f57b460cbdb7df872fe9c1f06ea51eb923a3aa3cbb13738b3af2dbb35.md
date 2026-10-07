<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T07:37:16.181Z","paths":["mail/components/accountcreation/views/email.mjs","mail/components/accountcreation/content/widgets/email-sync-accounts-form.mjs","mail/components/accountcreation/content/widgets/email-added-success.mjs","mail/components/accountcreation/content/widgets/account-hub-step.mjs","mail/components/accountcreation/content/widgets/account-hub-header.mjs"],"source":{"reference":"knowledge-record:c8facd3f57b460cbdb7df872fe9c1f06ea51eb923a3aa3cbb13738b3af2dbb35","recordId":"c8facd3f57b460cbdb7df872fe9c1f06ea51eb923a3aa3cbb13738b3af2dbb35","status":"supported","publicationKey":"de9c1d5ee95f28675a9aa4008e7b2a67a00035041d4927346207aa3f1b046b7b"}} -->
# Discovery-result notifications need a check after loading cleanup

Current #fetchSyncAccounts requests a success/info notification, then calls #stopLoading. #stopLoading calls #clearNotifications on the current subview. Both success and sync forms extend AccountHubStep; its clear method forwards to the header, where notification text is emptied. Proposed focused test: complete each empty/found/error discovery branch and check the intended notification after notification and cleanup operations have finished. This is a static ordering concern, not reproduced disappearance or a failure attributed to the 1956 patch. The source state branch and the final visible notice are separate claims. This is static source and test-code inspection. No runtime, build, lint or live accessibility check ran. Full Bugzilla and historical review timeline and inline discussion remain pending; source landing does not prove approval of a proposed manual rule.

Scope: account hub notification lifetime.

## Evidence

[Lesson record](../records/c8facd3f57b460cbdb7df872fe9c1f06ea51eb923a3aa3cbb13738b3af2dbb35.json).

- [Supporting record](../records/07b4e6ab8e08a5c07b0a825ce01cd15bb0fd59258eb4b37d2506fed679feb1d6.json)
- [Supporting record](../records/0808d311febf977e536b7849b0d465afe9baf30132b077b4b9d30c8230667df5.json)
- [Supporting record](../records/10a7d06684294dcf59e2ed78c88cfff9311ea9638340651dc861472059a98143.json)
- [Supporting record](../records/10c2faf5392cf2793b5af532031ffc6b48319dd4b1761462052c6c79d8caa34d.json)
- [Supporting record](../records/154550c3f02cf4f13173be059d8e0366a36f41333e30f4bbb59ea1be9b9d573e.json)
- [Supporting record](../records/1bff2ad3cf7d2e67ea9858166df4b2d84a45f1d2a9adc0efa304f5094a6d4884.json)
- [Supporting record](../records/4f5bdf7f865b1451c73a5f7a05d4d03da406caa6b19b11d0dd785bb9ef882c4e.json)
- [Supporting record](../records/6583b56c14f3e2572ea29abfbcdad592f5474c41365180337f12ee7542c1db2a.json)
- [Supporting record](../records/79aace82cde888c7f084612cddbcf2199b1cf546aecaec11edc4fa859ef530e2.json)
- [Supporting record](../records/89620e3ecc719cdf139aeb500ff05f983489c7aac84ed0c10571bfb1655932f7.json)
- [Supporting record](../records/c5dc72ceddb50eb934fbffe770a5b4b9611e955fe151779ea27298500b4ccff4.json)
- [Supporting record](../records/d45f7c149543b4c9477e837bc458566d15b2a58e87dddff6a0da242b75d140e5.json)
- [Supporting record](../records/d5177f504bf7432fa08f7f3a9ab1410aa648527ee59f6fc7e372f435df715722.json)
- [Supporting record](../records/df840b0d9f91c9d2f0739d68caf903bb1515bfbe413e2139a141831cf15ba954.json)
- [Supporting record](../records/f2d7064d5c52766c6570a8b60290aba7873f940eeaf8d31540f860e256d2bbd2.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
