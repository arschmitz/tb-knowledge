<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T02:02:16.321Z","paths":["mail/base/content/widgets/pane-splitter.js","mail/base/test/browser/widgets/browser_paneSplitter.js"],"source":{"reference":"knowledge-record:ffdcdcb3ebc021cfe0cec703a2d5b422ebe9545ddf5e7c4a284e7c8e784acb3c","recordId":"ffdcdcb3ebc021cfe0cec703a2d5b422ebe9545ddf5e7c4a284e7c8e784acb3c","status":"supported","publicationKey":"43a3a97772e95d1c54889606bc125dacc60e52ab222eb0549a2f4a1ce404ea09"}} -->
# Splitter accessibility uses separator orientation and a complete keyboard lifecycle

Current standalone pane splitters expose role separator and keyboard focus; embedded handles that resize their own container stay out of the normal tab order. aria-orientation describes the separator axis, which is opposite the resized axis. aria-controls identifies the resized pane, and aria-valuenow follows the rounded actual size or is removed when it is unavailable. Each relevant repeated arrow keydown changes size, but one resize lifecycle starts on the first keydown and ends on release or blur. The current test asserts repeated resizing, the accessible value and the four lifecycle events. These are static source and test assertions; no assistive-technology or keyboard execution was performed.

Scope: accessibility.

## Evidence

[Lesson record](../records/ffdcdcb3ebc021cfe0cec703a2d5b422ebe9545ddf5e7c4a284e7c8e784acb3c.json).

- [Supporting record](../records/3d10926a59e4cb6fc0669c0fbd4f8b0fdab9cc6eb2e9cdf02a2966dadb411604.json)
- [Supporting record](../records/6c3efd4fcd427c508784d4b5f435238dc2ab5382a0c58a37f9ab8827e3b8ecb6.json)
- [Supporting record](../records/8364146a323e398f8879b3ea8395b41015d7b972e52b5a55df0f11072d4152f1.json)
- [Supporting record](../records/ba34aac0d4347d0e4965b1b1cdb6f4fff2eaf07d1506f4119aa1b4956aeb5b57.json)
- [Supporting record](../records/c4f48e72fdc582899c214b55ec33641cb00219b3e2eea8fd85ba16029958cb59.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
