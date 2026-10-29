<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T10:09:41.584Z","paths":["mailnews/search/src/nsMsgLocalSearch.cpp","mailnews/search/src/nsMsgSearchSession.cpp","mailnews/local/src/nsLocalMailFolder.cpp"],"source":{"reference":"knowledge-record:2dfdfdb019d84cf13c0afc6428dfddbf58c47be4feb8b35dd946884b572acbf3","recordId":"2dfdfdb019d84cf13c0afc6428dfddbf58c47be4feb8b35dd946884b572acbf3","status":"supported","publicationKey":"426f19c8dfd6fbf01d12e5dcf7f25f587ad917b0f20083706cbfa2e4d7e7f329"}} -->
# A failed local folder reparse skips the paused search scope before resuming

A missing or outdated local summary pauses the search and gives the folder a completion listener. On failure, that listener skips the current paused scope before resuming the timer; success resumes without skipping. SkipSearch rejects an unpaused or out-of-range call and releases the folder database reference before advancing. The original startup failure callback was synchronous; accepted code later dispatches it through the event loop to avoid re-entrancy. No repair or test execution is claimed.

Scope: search/local-reparse.

## Evidence

[Lesson record](../records/2dfdfdb019d84cf13c0afc6428dfddbf58c47be4feb8b35dd946884b572acbf3.json).

- [Supporting record](../records/6b38c1beef0caa671987fabef9ef8b01fd90013b04fc8a9d84b94b1f023d2ad1.json)
- [Supporting record](../records/756cbd5ad4767ac468f8e2a784257c64e02eef62d8c9dc1e2aba8b5316b4cfc5.json)
- [Supporting record](../records/7ae85f0770425c10adcbe60e0290762db2eeb3ea8856037b19ecd26e35714925.json)
- [Supporting record](../records/7e0ccb40f6bb7abec822dfd126e9e438dfebc45d1438f8e6544be0b1d405936b.json)
- [Supporting record](../records/ee29a42e84156664c1027dbec4f984aa917b5d835c921d6ce56cf3bb9284f9ee.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
