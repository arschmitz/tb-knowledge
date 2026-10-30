<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T15:07:21.306Z","paths":[],"source":{"reference":"knowledge-record:2dae7c8a9adff58a679c4f3b04ead4bcffb8a8d71c67eaf555025bdb5be67f7b","recordId":"2dae7c8a9adff58a679c4f3b04ead4bcffb8a8d71c67eaf555025bdb5be67f7b","status":"provisional","publicationKey":"791ac2767316070a00311cf26c8d6c1d14459f14a47bc322b0929cf8fdb1b789"}} -->
# Thunderbird Bug 2061218 split, necessity analysis, review fixups, and autosquash

Cross-calendar move calls destination `addItem()` before source `deleteItem()`; deletion can fail after creation and leave duplicates, which supports basic failed-move recovery. Revision-checked storage cleanup and cache identity protection were not justified by a normal reproduction here. [Task 2]

Scope: general.

## Evidence

[Lesson record](../records/2dae7c8a9adff58a679c4f3b04ead4bcffb8a8d71c67eaf555025bdb5be67f7b.json).

- [Supporting record](../records/ea1dfc3f665ad4bf9b7c9413bc14c0551825674b6796c427f45f75c8aca60e7b.json)

## Validation and limits

Status: **provisional**. Recorded interpretation. Original private evidence is unavailable to other consumers; this summary is not independent verification.
