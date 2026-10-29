<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T16:43:49.266Z","paths":["mail/themes/shared/mail/common.css","mail/themes/shared/jar.inc.mn","mail/components/preferences/preferences.xhtml"],"source":{"reference":"knowledge-record:4e8cfef128a46ee85fd64fdafbe7481ecbb421d5881e9d0bbb9c9d6d7e417caf","recordId":"4e8cfef128a46ee85fd64fdafbe7481ecbb421d5881e9d0bbb9c9d6d7e417caf","status":"supported","publicationKey":"a7eff98b8cc052797dffd02645f48152febd909e3728a03cfb5800594987f006"}} -->
# The common stylesheet overrides the new sidebar-size token

The port replaces --in-content-sidebar-width with --size-sidebar at host/root scope and keeps auto. Thunderbird maps global in-content/common.css to its own common sheet, and Preferences requests that URL. The sheet still imports common-shared and layout styles. This proves the comm token override and consumer route; the upstream token implementation and rendered sidebar dimensions remain outside the checked scope.

Scope: Thunderbird in-content common stylesheet tokens.

## Evidence

[Lesson record](../records/4e8cfef128a46ee85fd64fdafbe7481ecbb421d5881e9d0bbb9c9d6d7e417caf.json).

- [Supporting record](../records/063709278b29bb805f908602e827c7d2a9d17df27229e905559c5b9c7761a041.json)
- [Supporting record](../records/83c1557326ba3211ca6d7677b238db63c87979d9e3ac1e25fc8560eba754aa62.json)
- [Supporting record](../records/8c461cf15629d54dc8027241dcfe52c0bf75e671ad6ec266ecb92e42fa32406c.json)
- [Supporting record](../records/e2da55f819b6e1a6374008af25a91419bbb468798a692ecfc105ade52bfe6081.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
