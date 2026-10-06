<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:25:18.036Z","paths":[],"source":{"reference":"knowledge-record:f9f82c9c15e042a3e350f8cfde986393b63cb25bc2a29bd503f9a959c67018bb","status":"provisional","publicationKey":"610281d70032b20cfc68e80c61bd93918cda41981fa380bb1fa456b52bb8ec0c"}} -->
# Thunderbird Calendar create/edit attribute-driven source loader

Preserve `nativeTime` as an exact string: it is signed 64-bit microseconds, so `Number` loses precision and `BigInt` is not JSON-compatible. New Redux consumers use serializable snapshots; raw `calIEvent` retention is explicit opt-in for legacy read-dialog compatibility. [Task 2]

Scope: calendar.

This is a workflow or historical planning observation.

## Evidence

[Shared lesson record](../records/f9f82c9c15e042a3e350f8cfde986393b63cb25bc2a29bd503f9a959c67018bb.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `3dcb023be62c4dc4f0c4c2d8ea40389a606456ad5376a7d8a7e89f9329ce6fef`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `899dd201969fc903b890edd8fd9031db345e324af9f9957ff02ddfd548ad4a04`.
