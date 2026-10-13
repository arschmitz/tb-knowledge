<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T07:54:56.710Z","paths":["mail/base/test/browser/widgets/files/autoTreeView.mjs","mail/base/test/browser/widgets/browser_autoTreeView.js"],"source":{"reference":"knowledge-record:ef22368dadfbabbc1d2bba3c030b2eb80482f19fa9efa17d5524eaaf78e7d0c0","recordId":"ef22368dadfbabbc1d2bba3c030b2eb80482f19fa9efa17d5524eaaf78e7d0c0","status":"provisional","publicationKey":"6551a2198c0352fcb97c4b4de72d94b5606c0c9b3df808fb5589fa76b82253cd"}} -->
# Explain the drag fixture target and workaround scope

Proposal for the auto-tree drag fixture: keep a workaround comment tied to the concrete synthesized action and the linked issue. The historical label repeats Colour so the header-cell centre contains text; the comment says only header text can be dragged and links Bug 1908314. This is deliberate fixture geometry, not a production label or a naming convention. The fixed fixture no longer repeats the label, and its retained drag helper computes actual header-button centres and starts/ends a test drag session. Read that current path before copying the workaround. No widget drag, linked bug or accessibility test was run.

Scope: mail/base/test/browser/widgets.

## Evidence

[Lesson record](../records/ef22368dadfbabbc1d2bba3c030b2eb80482f19fa9efa17d5524eaaf78e7d0c0.json).

- [Supporting record](../records/b14c9906a2e80a84541f4322bdde820cb8a5d6b3e44a5a8fda174abfd0095817.json)
- [Supporting record](../records/cddc6146dfeafa95bd40d4b7f103550b5335881696c1d4574d7115cbb2627535.json)
- [Supporting record](../records/d13211af81b76efaefc719672919e3550dc32241a9474c29ba3442f40b4d553f.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
