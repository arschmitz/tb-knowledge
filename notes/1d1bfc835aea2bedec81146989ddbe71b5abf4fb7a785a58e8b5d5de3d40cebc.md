<!-- knowledge: {"repository":"thunderbird","at":"2026-10-14T18:34:16.043Z","paths":[],"source":{"reference":"knowledge-record:1d1bfc835aea2bedec81146989ddbe71b5abf4fb7a785a58e8b5d5de3d40cebc","recordId":"1d1bfc835aea2bedec81146989ddbe71b5abf4fb7a785a58e8b5d5de3d40cebc","status":"provisional","publicationKey":"41478ad81c87ab8d331993fe17a2cb05b9d799e26a6bceb9ba96f422523fb6c0"}} -->
# Thunderbird and Firefox source-ingestion evidence and publication

Focused behavior evidence: `MailGlue` has ordered observer-based startup/shutdown cleanup; `CalCalendarManager` owns provider registration, cached calendars, timers, and teardown; `CalCachedCalendar` completes remote work before cache changes and guards duplicate completion; `saveCalendarEventCreate` uses Redux request IDs/baselines to reject stale results; Firefox starts via `nsBrowserApp.cpp` and `XRE_main*`; `GetServiceLocked` releases its monitor around user code. [Task 2]

Scope: general.

## Evidence

[Lesson record](../records/1d1bfc835aea2bedec81146989ddbe71b5abf4fb7a785a58e8b5d5de3d40cebc.json).

- [Supporting record](../records/710a7d7c64680af60daf18a55b4bd850984e38aca7884121478d1cd577fefe93.json)

## Validation and limits

Status: **provisional**. Recorded interpretation. Original private evidence is unavailable to other consumers; this summary is not independent verification.
