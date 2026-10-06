<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:25:16.910Z","paths":[],"source":{"reference":"knowledge-record:2db5f2914da82acd004bc9cbcef29fef40e4f4ace3c64fcca206d0c4c00ca922","recordId":"2db5f2914da82acd004bc9cbcef29fef40e4f4ace3c64fcca206d0c4c00ca922","status":"provisional","publicationKey":"b51a3ce3a6c277f972789025bb9b6dbbc421d6fd443689b69f845c6535ee8f77"}} -->
# Thunderbird established Phabricator patch-review workflow

Fetch exact revisions with `moz-phab patch --raw --skip-dependencies D####`, record the SHA-256 digest, and never silently review local `HEAD`. Import only in `Review comm checkout`, not a sibling clone or Git worktree; invoke `/Users/aschmitz/.local/bin/coderabbit` explicitly. [Task 1][Task 2]

Scope: general.

## Evidence

[Lesson record](../records/2db5f2914da82acd004bc9cbcef29fef40e4f4ace3c64fcca206d0c4c00ca922.json).

- [Supporting record](../records/7cb4034d2a4c9f6f1aefc25d0ac80b73b23ed901e871db8a950b6f90e3c7c051.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
