<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T04:57:43.415Z","paths":["mail/components/accountcreation/content/widgets/account-hub-header.mjs","mail/components/accountcreation/templates/accountHubHeaderTemplate.inc.xhtml","mail/locales/en-US/messenger/accountcreation/accountHub.ftl"],"source":{"reference":"knowledge-record:2894795f5effbd0ea6659caa3acaa1ad4d46b998ff1a6be44f215ade0e31fffa","recordId":"2894795f5effbd0ea6659caa3acaa1ad4d46b998ff1a6be44f215ade0e31fffa","status":"supported","publicationKey":"ddb2c7c0afe739e3763d7f3ba4610ec8be1740604736a2088ad134c5ad3c542a"}} -->
# Account Hub branding refresh separates split visual text from the complete welcome message

On first-run header refresh, Account Hub selects two visual Fluent IDs, adds aria-hidden attribute presence to those spans and unhides a separate complete welcome string with the brand placeable. Subsequent-run reverses those states. The step attribute triggers refresh, while the header samples isFirstRun itself. The source establishes these DOM changes; attribute-presence and visibility tests do not establish actual screen-reader output.

Scope: account-hub.

## Evidence

[Lesson record](../records/2894795f5effbd0ea6659caa3acaa1ad4d46b998ff1a6be44f215ade0e31fffa.json).

- [Supporting record](../records/110fc8e3169b704cd39b18e64f941082cb2f128c3833bb060d1d88378d3ae830.json)
- [Supporting record](../records/332f09bf37fee4e893619e337cfc50cb6082595f7600897facfcc704b892d621.json)
- [Supporting record](../records/6bf5cd94d8a22979434606fbdd919fe58936e6db227463d4603177b2ec8085f6.json)
- [Supporting record](../records/a3d724f7febf5fd18d944ca9ca2437c1b5552a32db81b64ceafc79927231a8b9.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
