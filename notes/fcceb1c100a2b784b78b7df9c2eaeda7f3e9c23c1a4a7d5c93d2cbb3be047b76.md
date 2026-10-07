<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T01:09:06.293Z","paths":["mail/base/content/FilterListDialog.js","mail/base/content/msgHdrView.js","mail/components/addrbook/content/aboutAddressBook.js"],"source":{"reference":"knowledge-record:fcceb1c100a2b784b78b7df9c2eaeda7f3e9c23c1a4a7d5c93d2cbb3be047b76","recordId":"fcceb1c100a2b784b78b7df9c2eaeda7f3e9c23c1a4a7d5c93d2cbb3be047b76","status":"provisional","publicationKey":"1e1e295a39811ffaf588761c312350dd062151909aacddb55252f92d22b4a1a8"}} -->
# Use one coherent options object when calling native XUL openPopup

For the native menupopup overload, use openPopup(anchor, { position, triggerEvent }) when those values are needed. Mixing an options object with old positional arguments can discard the trigger event even when the popup appears. Current filter/header/address book sites preserve the event in the object. Defaults can omit position. Do not impose this signature on unrelated application popup wrappers.

Scope: popup-ui.

## Evidence

[Lesson record](../records/fcceb1c100a2b784b78b7df9c2eaeda7f3e9c23c1a4a7d5c93d2cbb3be047b76.json).

- [Supporting record](../records/874ec30ea0b31da2078bfb82c72d361bcda82fb74cbfa6c9ef754554a19c4d3a.json)
- [Supporting record](../records/c686be574d20184de770fc40f8d12a765ca7a0243f9d0eab311a233d91163ee0.json)
- [Supporting record](../records/ce4537a21c2888d01c093c88eccba679d12f7da9c1d03e22f584c0cf04e6d5af.json)
- [Supporting record](../records/fdfa044700fa32fe4e5c02df0b7586196b26032bfb878b5b7bec26ce13a9d9fd.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
