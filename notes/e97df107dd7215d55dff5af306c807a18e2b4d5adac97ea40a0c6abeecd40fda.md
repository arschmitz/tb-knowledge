<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T12:43:59.117Z","paths":["taskcluster/test/params/cr-onpush.yml"],"source":{"reference":"knowledge-record:e97df107dd7215d55dff5af306c807a18e2b4d5adac97ea40a0c6abeecd40fda","recordId":"e97df107dd7215d55dff5af306c807a18e2b4d5adac97ea40a0c6abeecd40fda","status":"supported","publicationKey":"1707453f088ccbd5d3143cc689e45f4e3d3278ce1449e6dd6b3cddaa76792650"}} -->
# The import-style removal also edits a historical release-128 taskgraph fixture

The owned CSS-removal patch deletes one accountSetup.css entry from files_changed in a fixture whose app_version is 128.0 and whose comm_head_rev names a historical release commit. Post-landing review says that historical path may be expected and requests re-addition only if an actual test fails. No such failure or taskgraph run is established. The fixed comparison fixture has later 153.0 revision/list metadata, so its changed contents do not validate the earlier fixture edit. Keep the source-file deletion, historical fixture identity and later fixture phase separate.

Scope: Release taskgraph test-fixture scope.

## Evidence

[Lesson record](../records/e97df107dd7215d55dff5af306c807a18e2b4d5adac97ea40a0c6abeecd40fda.json).

- [Supporting record](../records/0ddf30caec123de3850863941bb5f24798ed3183aa02bea6b3c9a2e93406bce9.json)
- [Supporting record](../records/480306321caeeb566d793796f2371017031da7d8fbd600fba37a47e1c405e212.json)
- [Supporting record](../records/7cf9fedcc22eb251c4a4a007bab0b72ae8505a7458f5b85adc3ebcc0d2f3b46a.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
