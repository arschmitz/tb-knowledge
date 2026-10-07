<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:18:52.319Z","paths":["mailnews/news/src/NntpNewsGroup.sys.mjs","mailnews/search/src/nsMsgFilterService.cpp"],"source":{"reference":"knowledge-record:8b7a475fafbe1934c7186abfbbae6fbca5bfdda28428401c16f77a44be5cbc2c","recordId":"8b7a475fafbe1934c7186abfbbae6fbca5bfdda28428401c16f77a44be5cbc2c","status":"supported","publicationKey":"7daea9b9359bb82900769b4044b4793349c4911eff09c756bd29dad8fdf668c0"}} -->
# Filter actions use different owning mutation boundaries

The accepted NNTP applyFilterHit calls its owning database with the filtering header messageKey for read and unread. Post-search filters instead delegate read/unread/flagged actions through curFolder, while KillSubthread gets each header key and calls m_curFolderDB->MarkKilled, checking its result. Preserve each action owner when migrating the flag API; replacing all of these with one direct header-bit operation would skip the checked boundaries. This is a scoped caller observation, not proof of identical notification or server behavior across filters. This is source and test-code inspection. Complete Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mailnews/news/src.

## Evidence

[Lesson record](../records/8b7a475fafbe1934c7186abfbbae6fbca5bfdda28428401c16f77a44be5cbc2c.json).

- [Supporting record](../records/27c574e8c262ea963fa7d36524761bd9fa11883106097c554b10829441e7c24d.json)
- [Supporting record](../records/2af451aa08e0a9998ea24aa67eb596caa36c0870c016036fb825e51412161100.json)
- [Supporting record](../records/b02538a5046d6f2bc33a7e5edb19f212b3729963f584dd6d9fb86b53bf051563.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
