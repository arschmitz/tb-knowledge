<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T00:37:49.880Z","paths":["mail/base/content/messageWindow.xhtml","mail/base/content/messenger.xhtml","mail/components/customizableui/CustomizableUI.sys.mjs","mail/components/customizableui/content/panelUI.js","mail/components/customizableui/moz.build"],"source":{"reference":"knowledge-record:acfabcaabbea0e3f12abc0dedde8decb4e537b2a9d29df02ae2ecb1e0eba60c6","recordId":"acfabcaabbea0e3f12abc0dedde8decb4e537b2a9d29df02ae2ecb1e0eba60c6","status":"supported","publicationKey":"0d91bf1a59ad70f7f7c78c70df038b97b45fe0107f85b35f81d39261d6406959"}} -->
# Customizable UI source-address migration updates document scripts and module imports together

The historical migration changes both document script URLs, both lazy-import consumers and the parent build list together, while deleting the old content jar packaging. panelUI.js remains a classic deferred script; the .sys.mjs files retain ES module APIs. The fixed main document retains the source-addressed loader, but its standalone message-window counterpart was later removed. Preserve the actual document/module roles when changing these paths. This scoped source relationship is not a global URI rule or a successful loader, menu, focus or build test.

Scope: Customizable UI loading.

## Evidence

[Lesson record](../records/acfabcaabbea0e3f12abc0dedde8decb4e537b2a9d29df02ae2ecb1e0eba60c6.json).

- [Supporting record](../records/2d5793446c217c720cc340903e201bbe4e4e29ed01456747b2158556690fde86.json)
- [Supporting record](../records/37a3e54c305dc52e03c76dc3e6a0c5cfd11fbde0bba04d11ecf4304927d74930.json)
- [Supporting record](../records/4ed4cdaf3eabbbf6754bf3f6c892c6be6aa8c64633ec7fa723730da01212b2a3.json)
- [Supporting record](../records/a78a9dbbb5abfbd75e71694a8e4e4d8e2cac4d0d70890fa680b79b83252c29de.json)
- [Supporting record](../records/f7e071fc0366662678307c9c7f4cc0915c5eea43b471b2c4b04cc3e0640fd177.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
