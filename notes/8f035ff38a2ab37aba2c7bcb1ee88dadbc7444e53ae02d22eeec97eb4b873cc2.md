<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T05:26:41.865Z","paths":["mail/themes/shared/mail/popupPanel.css"],"source":{"reference":"knowledge-record:8f035ff38a2ab37aba2c7bcb1ee88dadbc7444e53ae02d22eeec97eb4b873cc2","recordId":"8f035ff38a2ab37aba2c7bcb1ee88dadbc7444e53ae02d22eeec97eb4b873cc2","status":"supported","publicationKey":"467783d275466bbe9af2aa76d95fff13034f067b6b67ba730a08b977d13acfe1"}} -->
# The contact-popup tint patch targets the menu and icon descendants explicitly

The original contact-popup patch applies -moz-context-properties, fill and stroke to both #editContactAddressBookList and its .menu-icon descendants. That makes the descendant selector explicit rather than relying only on inherited tint. The accepted file later contains only the parent tint block, so the original descendant rule is not a current invariant. Icon pixels, contrast and the upstream menu cascade were not validated.

Scope: contact-popup-css.

## Evidence

[Lesson record](../records/8f035ff38a2ab37aba2c7bcb1ee88dadbc7444e53ae02d22eeec97eb4b873cc2.json).

- [Supporting record](../records/318c346006738046c05d47de7a4dcd44c5a43b9510eeacb9e1e8bcd3fab6e995.json)
- [Supporting record](../records/517f8caf3ba5d0e0f19a0eb5c2ffb9819ae350ad11fc5bb79d0149d4eb07e736.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
