<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:25:18.042Z","paths":[],"source":{"reference":"knowledge-record:0010de45b57105863de22e5fd049f13ec5aa8cded00edb9dbf6945599b1f493b","status":"provisional","publicationKey":"5203c2d6821deb9b8c1232ea01c811f7266ebafa2ef8ddda083bab025ee2a7de"}} -->
# Thunderbird CI intermittent triage and deterministic browser-test cleanup

IMAP idle does not mean status UI is idle: `FeedbackService.reportStatus()` queues `window.postMessage`. Drain one `TestUtils.waitForTick()` in shared `clearStatusBar()` before checking meteors/progress state. [Task 3]

Scope: general.

This is a workflow or historical planning observation.

## Evidence

[Shared lesson record](../records/0010de45b57105863de22e5fd049f13ec5aa8cded00edb9dbf6945599b1f493b.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `b8678f3bb992a687e78ab8060659614a3ee94abbac54e38a0e857693bac7b94e`, `78f2754945ae97a17bb5c0ae6c5d097d580e5d02c867d2300f52e9d4d61755bb`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `70e8efb0654af5f17f9532e8cb55cc445471904d2f5f4d252ff35ba83fb08f53`, `04b831bed75d242b54902eb1e33441e2908976eba640ae430a425ab5ae567b46`.
