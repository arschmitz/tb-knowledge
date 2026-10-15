<!-- knowledge: {"repository":"tb-tools","at":"2026-10-15T07:37:36.146Z","paths":[],"source":{"reference":"knowledge-record:ed6cdd722bd1cf8ff8ece451ea1c5afaaaca78c10da3b7ff45c6a04cb98882e7","recordId":"ed6cdd722bd1cf8ff8ece451ea1c5afaaaca78c10da3b7ff45c6a04cb98882e7","status":"provisional","publicationKey":"1f1a0400dd0fc0c16f7bcea5f1d2f46d47388cbd935a0977e7625bfdfcfcca2c"}} -->
# Commands patch-review conflict recovery, single-patch fallback, and capacity status

`Try applying only this patch` calls `/api/review/<id>/apply-single` with `--skip-dependencies` on pinned main, persists `singlePatchOnly`, includes it in review context, and visibly reports omitted parents. Clean imports resume; conflicts use the same resolver; reject another attempt while resolution is pending. [Task 2]

Scope: console.

## Evidence

[Lesson record](../records/ed6cdd722bd1cf8ff8ece451ea1c5afaaaca78c10da3b7ff45c6a04cb98882e7.json).

- [Supporting record](../records/128b4e3392e8e0fcdcef45e82a512f97458290355cf82d14781492fc62502391.json)

## Validation and limits

Status: **provisional**. Recorded interpretation. Original private evidence is unavailable to other consumers; this summary is not independent verification.
