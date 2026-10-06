<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:25:18.055Z","paths":[],"source":{"reference":"knowledge-record:75492466c0b446156d6a86fa7775cc92d15a1170e621ecf36aeeeed39f403852","status":"provisional","publicationKey":"5dd0de12e8073bc236b300c73ef8a0e368313b8c09cbd3b0337fa479d87ecf81"}} -->
# Thunderbird Calendar create/edit dialog static foundation

Feature slices inject into `mail/base/content/state/store.mjs` `rootReducer`. Store only cloned plain snapshots/baselines, draft values, dirty sections, validation, and operation state; retain raw `calIEvent` objects in the existing session-scoped private cache. Route attributes `calendar-id`, `event-id`, and optional `recurrence-id` remain authoritative. [Task 2]

Scope: calendar.

This is a workflow or historical planning observation.

## Evidence

[Shared lesson record](../records/75492466c0b446156d6a86fa7775cc92d15a1170e621ecf36aeeeed39f403852.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `8af8b6f41766bb8342a07c95f6815b1507a04ce57880432611a88ce01da3e54d`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `808c8d733afed4c7fb05fc8e66ceabc0fe2a7df3984323add8e068a01a1aacbc`.
