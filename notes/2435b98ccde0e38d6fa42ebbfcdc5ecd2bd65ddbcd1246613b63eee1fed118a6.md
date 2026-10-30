<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T21:59:11.743Z","paths":["taskcluster/kinds/release-early-tagging/kind.yml","taskcluster/config.yml"],"source":{"reference":"knowledge-record:2435b98ccde0e38d6fa42ebbfcdc5ecd2bd65ddbcd1246613b63eee1fed118a6","recordId":"2435b98ccde0e38d6fa42ebbfcdc5ecd2bd65ddbcd1246613b63eee1fed118a6","status":"supported","publicationKey":"957bd558e276ea7fbe9c62c45b473c89e938e032c98976d6a644f6a5e5301779"}} -->
# Early Lando tagging stays a promote-phase buildN action

The early-tagging port selects the shared lando worker and declares one buildN tag action in the promote phase. It does not add the release-version-bump kind version-update action. Try selects staging repositories by release type. Accepted source later supplies an explicit revision through task context and updates repository/ESR names. Declared actions and phase do not establish a successful remote tag.

Scope: Thunderbird Lando early release tagging.

## Evidence

[Lesson record](../records/2435b98ccde0e38d6fa42ebbfcdc5ecd2bd65ddbcd1246613b63eee1fed118a6.json).

- [Supporting record](../records/5391ad6e2a4545d0a23b607efa4f70648c01a635197ee45be4e167be45ed5e06.json)
- [Supporting record](../records/6e86007b96eec76e5f0de819dd549c0793e91563f6605b75746c2b885ca8c2b1.json)
- [Supporting record](../records/869f1135cc7b7701824b29f5eb4e1303399018cb7041be76ce14257e6df9df22.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
