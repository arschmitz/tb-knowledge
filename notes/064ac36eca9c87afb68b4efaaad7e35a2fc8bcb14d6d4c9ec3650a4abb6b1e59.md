<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T01:37:17.654Z","paths":["calendar/base/content/widgets/calendar-invitation-panel.inc.xhtml","calendar/base/content/widgets/calendar-minidate.inc.xhtml","mail/base/content/aboutMessage.xhtml","mail/base/content/messenger.xhtml"],"source":{"reference":"knowledge-record:064ac36eca9c87afb68b4efaaad7e35a2fc8bcb14d6d4c9ec3650a4abb6b1e59","recordId":"064ac36eca9c87afb68b4efaaad7e35a2fc8bcb14d6d4c9ec3650a4abb6b1e59","status":"supported","publicationKey":"22008cc87652f84535a11ed9a655d725c3ee4c505631edc2ca294df67ea7b2f9"}} -->
# Calendar template fragments use .inc.xhtml at their include consumers

The invitation-panel and minidate template fragments use .inc.xhtml, and both message documents include those exact filenames. The historical rename preserves each fragment blob exactly and updates the two consumers. This local suffix communicates a preprocessor include role; it is not a rule for standalone XHTML documents. The commit title says minimonth, but the actual file is minidate. No build or rendered UI test ran.

Scope: Calendar invitation and minidate template naming.

## Evidence

[Lesson record](../records/064ac36eca9c87afb68b4efaaad7e35a2fc8bcb14d6d4c9ec3650a4abb6b1e59.json).

- [Supporting record](../records/1e9de11aa4a0dd0f1f16ada808f80e899ea63d934859744801cb72eee76491b7.json)
- [Supporting record](../records/2ec805ab4ac44bc880b7253621307b05f49de0857ee65dfd3dd227f2899f06a2.json)
- [Supporting record](../records/342f5782ddcfdd87f01e8801e9918de840a1b7c32d4415e33f9696ba12bc22e9.json)
- [Supporting record](../records/86fa9025a9c7fe7d78209d7f262f158688da07064e0398eec9e17f35ff41bf48.json)
- [Supporting record](../records/d00c2cd67108450c1f0c7858dbeeb0573ef503d2a115b4dbbd97098345244396.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
