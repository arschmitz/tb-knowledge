<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T02:16:09.843Z","paths":["mailnews/base/src/nsMsgQuickSearchDBView.cpp","mailnews/base/src/nsMsgDBView.cpp","mailnews/base/test/unit/test_nsMsgDBView.js"],"source":{"reference":"knowledge-record:788e7ecd3bdac2cd1a4ede4ad83ef6d7cecb3f8d63891ce5707abdc197cf0911","recordId":"788e7ecd3bdac2cd1a4ede4ad83ef6d7cecb3f8d63891ce5707abdc197cf0911","status":"supported","publicationKey":"a794229f973b31c37353b492d814d8d804b8562dacb5219a917f43ee9d78979c"}} -->
# Quick-search root sorting needs base sort metadata even for ascending IDs

SortThreads first orders message keys by ID and builds a unique sorted root-key list. It then sets m_sortType to byNone, swaps in the root list and always calls nsMsgDBView::Sort before rebuilding the thread rows. Entry 701 removes the ascending-byId shortcut. The base Sort path updates and saves sort information unless its valid same-sort fast path applies; resetting the type avoids that shortcut here. Manual optimization proposal for this path: check lifecycle and persisted sort side effects before removing an apparently redundant sort. This is compatible with the existing lesson about removing a truly redundant sort that masked bad levels; the two changes concern different classes and side effects. The inspected existing quick-search test checks levels, not every ascending-order persistence case.

Scope: quick-search-thread-sort.

## Evidence

[Lesson record](../records/788e7ecd3bdac2cd1a4ede4ad83ef6d7cecb3f8d63891ce5707abdc197cf0911.json).

- [Supporting record](../records/1205cdf281be038cf75c0c0f63214e9e0c0fa1c6658b9308d9e152118a685cbe.json)
- [Supporting record](../records/294286571b13416d51905bc60b42141b7c8fbcf5c13a7696e7a3dd4a0453c168.json)
- [Supporting record](../records/7842ec28da2c742eee59b144202e8734c334b37eeed40fe48c39b7b7a56066c0.json)
- [Supporting record](../records/953553f37ea2fb695de8e067b59ba7bf508117619a8e320604891aa369be4672.json)
- [Supporting record](../records/9ce3def4cd57a8e231c2eb2b8022c5b09fce8d5e20737970e420dcac15035fed.json)
- [Supporting record](../records/c48daaf6b66976bbd2db60c1f925a77ac3ba9183afa0d4b80cfdfa0d229ef1c1.json)
- [Supporting record](../records/efb17ddec45123922feff0688781aae1146be47002943a9fe90935a121675e37.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
