<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T01:12:57.600Z","paths":["mail/components/cloudfile/metrics.yaml","calendar/metrics.yaml","mail/components/compose/metrics.yaml","mail/metrics.yaml"],"source":{"reference":"knowledge-record:b6abea2628bd352418eb8b5c9ad31aca2c4e53ce1a7c24f7ef9ca9fcc6f51a3e","recordId":"b6abea2628bd352418eb8b5c9ad31aca2c4e53ce1a7c24f7ef9ca9fcc6f51a3e","status":"supported","publicationKey":"1e19d0af3f82a727a5dc0b50f604cdb5d42bb1b1057dcf9b46002add374c78ef"}} -->
# Use a plain YAML description for one line and describe units and label meaning

The accepted preference review removed an unnecessary folded scalar marker for a one-line description. Current metrics also describe uploaded bytes and give calendar type examples. Proposed manual syntax/style rule: use a plain single-line description when it fits; use folded prose for real multiple-line text, and explain units/population/labels where needed. Current files are not perfectly consistent: compose_type still uses > for one line and UI source examples still have old underscore values. Update nearby prose from actual current emitters.

Scope: telemetry-schema.

## Evidence

[Lesson record](../records/b6abea2628bd352418eb8b5c9ad31aca2c4e53ce1a7c24f7ef9ca9fcc6f51a3e.json).

- [Supporting record](../records/2c9519722f51b6d7010f8a4e6d42e156c43a1af2775b251f8da83da7f42fa590.json)
- [Supporting record](../records/9a9cd2e800e42104d0eccf951e7633846f161157b9f85e878fbd2e0ca575e586.json)
- [Supporting record](../records/d36675e3092e02521630fe56355371a873d42b1ea4a52acb77d102d4677ba637.json)
- [Supporting record](../records/efb7ae85e75d7644bfc002af55ec19bca27f40838ca01ff17911f262cf43eafb.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
