<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:26:06.554Z","paths":["mailnews/base/src/FolderCompactor.cpp"],"source":{"reference":"knowledge-record:ea5115bc1aeefeff22ea55ddfe9cbbb92dfa170824e3f5a04150cfa7795e0dd4","recordId":"ea5115bc1aeefeff22ea55ddfe9cbbb92dfa170824e3f5a04150cfa7795e0dd4","status":"supported","publicationKey":"836352c602958217c579844d41cb84c1aa04819642d96ffab98c44bc5eb055d7"}} -->
# Malformed IMAP offline storage and local mbox data receive different caller recovery

After batch compaction, accepted code queries the failing folder as nsIMsgImapMailFolder. IMAP emits folder-needs-repair to redownload server data; local folders instead show compactFolderStorageCorruption because a broken mbox cannot be rescanned reliably. Do not generalize IMAP redownload repair to irreplaceable local data. This caller distinction is separate from previously recorded offline metadata invalidation and skipping untrusted header rewrites. This is static source and test-code inspection. Full Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mailnews/base/src.

## Evidence

[Lesson record](../records/ea5115bc1aeefeff22ea55ddfe9cbbb92dfa170824e3f5a04150cfa7795e0dd4.json).

- [Supporting record](../records/154e70f56fd17c50c6c3004f088a7819a82841d790e08a0f53c0d7c07f3d1159.json)
- [Supporting record](../records/579dd35b7149c796ab93ac9ec23e34dded7ca14ac20f3e2dde5606eabff88438.json)
- [Supporting record](../records/74fb229b7db9eb0f755554ed6cf62793a920a866f22b8a95b39165499fadb85f.json)
- [Supporting record](../records/9ceb5f6bf37bf550323548596973772a6ac7d5b51f59346b46b073bfa0d81cd4.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
