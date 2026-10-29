<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T22:00:17.502Z","paths":["calendar/base/content/item-editing/calendar-item-iframe.js","calendar/base/content/item-editing/calendar-item-iframe.xhtml","calendar/locales/en-US/calendar/calendar.ftl"],"source":{"reference":"knowledge-record:8cee07a80cb4922fbcaca80629bafee55ffbc93f2b9a9cb19698fbc6cfeac259","recordId":"8cee07a80cb4922fbcaca80629bafee55ffbc93f2b9a9cb19698fbc6cfeac259","status":"supported","publicationKey":"1aab7a72b6a2cf5b36f6311096b4a9a1697c0afc03456045fdb6cc772858441b"}} -->
# The attachment-removal migration also adds confirmation for one attachment

deleteAllAttachments now returns immediately for zero attachments and asks for confirmation for every positive count, including one. Previously it skipped the prompt below two. DOM removal, gAttachMap reset and updateAttachment now happen only after confirmation. The existing command still reaches the handler and the synchronous Fluent resource supplies count-aware prompt text. This is an interaction change as well as localization; no prompt, cancellation, keyboard or attachment test was run.

Scope: Calendar item editor attachment removal.

## Evidence

[Lesson record](../records/8cee07a80cb4922fbcaca80629bafee55ffbc93f2b9a9cb19698fbc6cfeac259.json).

- [Supporting record](../records/37a74a9538da33c3e0ba57d6c841b5bded13092a36544db849b04081d555a01d.json)
- [Supporting record](../records/5f53c7798be47291673e40c781ed193a56ffeb2f602eb95298dbab7f1cef7361.json)
- [Supporting record](../records/9b867eaabe78ab2b83547be5d3b824333b59428f2d56cbfa6001526d9cb70d97.json)
- [Supporting record](../records/dd963854c55c39684974021e52029df9382721ccddf83842a422fc77219154a0.json)
- [Supporting record](../records/edcb71d634724f9c55256ac43a035e17b8ddf07b2f689d7ec1dbc3ee33119d10.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
