<!-- knowledge: {"repository":"thunderbird","at":"2026-10-18T01:24:17.417Z","paths":["calendar/base/modules/utils/calIteratorUtils.sys.mjs"],"source":{"reference":"knowledge-record:3a3da26a06d1a2a7f1dac85d8b1f9b34fce44323e4d13cdedfacb4bccadb4f2d","recordId":"3a3da26a06d1a2a7f1dac85d8b1f9b34fce44323e4d13cdedfacb4bccadb4f2d","status":"supported","publicationKey":"febe3cd3e0710efbf94bbf4b49e9e4087508dc28886e8909a459b044e6fc80ca"}} -->
# Calendar’s yielding iterator completes through its callback

cal.iterate.forEach dispatches batches on the event queue and returns before iteration finishes. Its completed callback runs on exhaustion or BREAK. The removed require-jsdoc directive is only lint compatibility; the scheduling contract remains. Do not treat this helper as Array.prototype.forEach or replace it mechanically with a synchronous loop. No scheduling test ran.

Scope: Calendar yielding iteration.

## Evidence

[Lesson record](../records/3a3da26a06d1a2a7f1dac85d8b1f9b34fce44323e4d13cdedfacb4bccadb4f2d.json).

- [Supporting record](../records/4ae24f57b299e177fea0f5957b6ce305caa212e1faafd061b37dea9adc0a32e9.json)
- [Supporting record](../records/b741a5f49ffd94453160dedd612c97f7174096d3260c6bdb98b0fc58876931e8.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
