<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:20:56.753Z","paths":["mail/components/preferences/jar.mn","mail/components/preferences/preferences.js","mail/components/preferences/preferences.xhtml","mail/components/preferences/test/browser/browser.toml"],"source":{"reference":"knowledge-record:a3a2f211bdceaebb7cef472cd586ce8f37a63c15615fb1a67fa7df801fccbac4","recordId":"a3a2f211bdceaebb7cef472cd586ce8f37a63c15615fb1a67fa7df801fccbac4","status":"supported","publicationKey":"583b0dae8fae422ce6b5a91f9f8f5b852c6a14a5eb68944b78fd9138da3a3fdc"}} -->
# A preferences pane needs registration as well as its source file

Appearance is packaged by jar.mn, exposed through the appearancePane ES module getter, registered with paneAppearance, and included in the preferences page. Its browser_appearance.js test is registered in the current TOML manifest. Preserve those entry points when adding a related pane module; source existence alone does not make it loadable. The historical .ini test registration remains historical. These source relationships were inspected, without launching preferences. Complete Bugzilla and historical Phabricator timeline/inline discussion remains pending.

Scope: mail / components.

## Evidence

[Lesson record](../records/a3a2f211bdceaebb7cef472cd586ce8f37a63c15615fb1a67fa7df801fccbac4.json).

- [Supporting record](../records/3e513d8c97b637ad4854c09c91254b94d5ae306b486b5a2507ed3f0da4dd138c.json)
- [Supporting record](../records/683f505f27dd6590648e641f4501738838281446931dc76cf26c9a4b0e463c10.json)
- [Supporting record](../records/9ece3232124af1532e07deede2c03a9d42c5db9ff8b2801014eb63ee5e832054.json)
- [Supporting record](../records/e284616245c16cd8cf93ea70583d7577fced50191c5abf9a105cb26f24da8f2d.json)
- [Supporting record](../records/ecd5d58480e3fb2cd714970a5ca70e81bd015644a1b17329dc220f512cb6dd5d.json)
- [Supporting record](../records/feabbca00f4bc78a1e74784fc0dba77d086c02bfece91f9816cf0627e6df029f.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
