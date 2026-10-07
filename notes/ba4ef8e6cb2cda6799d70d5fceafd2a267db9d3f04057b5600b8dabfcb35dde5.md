<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:20:56.749Z","paths":["mail/modules/MailUtils.sys.mjs","mail/components/preferences/appearance.mjs"],"source":{"reference":"knowledge-record:ba4ef8e6cb2cda6799d70d5fceafd2a267db9d3f04057b5600b8dabfcb35dde5","recordId":"ba4ef8e6cb2cda6799d70d5fceafd2a267db9d3f04057b5600b8dabfcb35dde5","status":"supported","publicationKey":"16cc1c016655a98c657143dd5033a285e8948834bffe70f53ee4a5cdbfbdc6d3"}} -->
# A finished folder traversal is not proof that every view write succeeded

At the fixed accepted source, takeActionOnFolderAndDescendents catches and warns for each action failure, then continues and resolves when its generator ends. Appearance awaits that helper and unconditionally shows the success notification. Proposed test: make one commitViewState fail and check whether the UI should report a partial result. This is a static error-reporting gap; no actual failed folder write or false notification was reproduced. Do not infer all writes succeeded from the helper promise alone. Complete Bugzilla and historical Phabricator timeline/inline discussion remains pending.

Scope: mail / modules.

## Evidence

[Lesson record](../records/ba4ef8e6cb2cda6799d70d5fceafd2a267db9d3f04057b5600b8dabfcb35dde5.json).

- [Supporting record](../records/926de08ca418ed3f895c00d587492ec70ddee237a60a8bfde2df3d5dc026aa47.json)
- [Supporting record](../records/ce58b2cfb5ad364ff1787e328dbdb97975d0381220a16287261a14f549cbdd23.json)
- [Supporting record](../records/ecd5d58480e3fb2cd714970a5ca70e81bd015644a1b17329dc220f512cb6dd5d.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
