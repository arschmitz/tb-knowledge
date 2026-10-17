<!-- knowledge: {"repository":"thunderbird","at":"2026-10-17T21:39:23.950Z","paths":["mailnews/search/test/unit/test_copyThenMoveManual.js","mailnews/test/resources/PromiseTestUtils.sys.mjs","mailnews/search/src/nsMsgFilterService.cpp"],"source":{"reference":"knowledge-record:5f548dcae6c6aeaae2cd1a24119c107106dc068f2c74aa08cafcaa5e49cead6f","recordId":"5f548dcae6c6aeaae2cd1a24119c107106dc068f2c74aa08cafcaa5e49cead6f","status":"supported","publicationKey":"b2b490e5a86340fb6753a69465f86e32933e6d0d82fffb07ec22c4b3b9871818"}} -->
# Await the filter operation before checking copy-then-move results

The copy-then-move test originally waited for a folder move event and two acknowledged100ms workarounds. The follow-up passes PromiseMsgOperationListener into each filter API and awaits its promise before checking destination and inbox counts. The native executor calls OnStopOperation with its final result at OnEndExecution. The adapter forwards an optional wrapped callback first and resolves only for exact NS_OK; fixed code rejects an Error for other status values. A throwing wrapped callback or repeated executor notification is not covered by these success-path assertions. Reported --verify passes are attributed, not reproduced here.

Scope: Scoped EWS and mail filter contracts.

## Evidence

[Lesson record](../records/5f548dcae6c6aeaae2cd1a24119c107106dc068f2c74aa08cafcaa5e49cead6f.json).

- [Supporting record](../records/316be1b5a9b776ce89d13cfe61e55016a543d31df38ccb26fcf854f830d9a410.json)
- [Supporting record](../records/36bc0fb46af287a7ea86b02801a2bf5ac74ef54e7739cd8f0138a2ece7ef3e98.json)
- [Supporting record](../records/8fbceb25850195abe04ed590dbde43e6b5ed20ae2881934f3e9d2c8f31266dfd.json)
- [Supporting record](../records/fd975e37f08e0dbff83f7d78119525d44e2988cb738e9692f2d62600d2ae6348.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
