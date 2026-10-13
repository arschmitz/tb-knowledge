<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:06:59.705Z","paths":["browser/components/backup/BackupService.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","parser":"espree 10.3.0","language":"JavaScript","fileRole":"source","bodyFactRulesVersion":1,"verification":"Pinned blob digest checked; narrow whole-body rules and lexical binding resolution; no contextual behavior certification","component":"browser","runtime":"privileged-system-module","classificationBasis":"Saved path heuristic plus pinned imported/generated-list matches; pilot matcher is not an authoritative lint-rule interpreter.","imported":false,"generated":false}} -->
# firefox browser/components/backup/BackupService.sys.mjs direct local body contracts

These are deterministic explanations of complete simple local bodies at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. They are added body facts, not a complete behavior analysis. Parameter binding must succeed before each body runs. Caller contracts, method receivers, cross-file consumers, tests, and runtime branches remain unverified. Names inferred from properties or assignments are navigation labels. No product test pass is claimed.

## PROFILE_FOLDER_NAME at 1097 to 1099

Evidence: `browser/components/backup/BackupService.sys.mjs:1097-1099`; body SHA-256 `0899ced763d2dbe2367040e503f10c25f8750396954488aaab3183f727f4e12b`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "backups". This is the body return value; constructor invocation can ignore it.

## SNAPSHOTS_FOLDER_NAME at 1107 to 1109

Evidence: `browser/components/backup/BackupService.sys.mjs:1107-1109`; body SHA-256 `f671cedbf212107edd9f9f55c3a187efd9da42e8603a290d6364eaab7d92a85f`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "snapshots". This is the body return value; constructor invocation can ignore it.

## MANIFEST_FILE_NAME at 1116 to 1118

Evidence: `browser/components/backup/BackupService.sys.mjs:1116-1118`; body SHA-256 `36d79263614ababeb9f27444b123c4229b46623280c59c5ad6323adbe1574013`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "backup-manifest.json". This is the body return value; constructor invocation can ignore it.

## POST_RECOVERY_FILE_NAME at 1152 to 1154

Evidence: `browser/components/backup/BackupService.sys.mjs:1152-1154`; body SHA-256 `eb08a66dfe9f09f34386cbf3c110421e7f028e0179fca38cfd1494ba88b1777e`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "post-recovery.json". This is the body return value; constructor invocation can ignore it.

## ARCHIVE_ENCRYPTION_STATE_FILE at 1162 to 1164

Evidence: `browser/components/backup/BackupService.sys.mjs:1162-1164`; body SHA-256 `5382bca517ea2333ba3417cadbe495bc676db0dac02dbe74cf4ed841b053d965`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "enc-state.json". This is the body return value; constructor invocation can ignore it.

## RECOVERY_ZIP_FILE_NAME at 1181 to 1183

Evidence: `browser/components/backup/BackupService.sys.mjs:1181-1183`; body SHA-256 `d736e853fca00a2614bf1685a842be43f83a7edd979055a0d4af9db49150cf2d`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "recovery.zip". This is the body return value; constructor invocation can ignore it.

## ARCHIVE_TEMPLATE at 1243 to 1245

Evidence: `browser/components/backup/BackupService.sys.mjs:1243-1245`; body SHA-256 `5e85346adad46dd024ab6f87f91774f5eda2cb6a227cb93a04471ebe9e44d434`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "chrome://browser/content/backup/archive.template.html". This is the body return value; constructor invocation can ignore it.

## WRITE_BACKUP_LOCK_NAME at 1266 to 1268

Evidence: `browser/components/backup/BackupService.sys.mjs:1266-1268`; body SHA-256 `6bc2c20710841c8a17b21cc085738074af2326b9af8105705de33e27fecb4bc7`; rule `return-primitive`.

After parameter binding succeeds, the local body returns "write-backup". This is the body return value; constructor invocation can ignore it.

## REGENERATION_DEBOUNCE_RATE_MS at 1276 to 1278

Evidence: `browser/components/backup/BackupService.sys.mjs:1276-1278`; body SHA-256 `bd2692919a4a95ae8e8c0399ca1fa91357c5ba9d1d9e15ddb3ba592d4782eed4`; rule `return-primitive`.

After parameter binding succeeds, the local body returns 10000. This is the body return value; constructor invocation can ignore it.

## Validation and limits

All listed bodies passed the narrow syntax rules; preceding actions, generators, class constructors, parameter defaults/destructuring, and async parameter returns are not accepted by these rules. Complex bodies remain in the private work queue. A whole-file parse does not mean all functions were analyzed. Literal return facts cannot establish API ownership, cross-file callers, test coverage, or passing runtime results. Imported/generated/test role flags retain their original scope.
