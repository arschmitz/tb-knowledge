<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.134Z","paths":["calendar/base/content/today-pane-agenda.js"],"source":{"reference":"https://phabricator.services.mozilla.com/D282319","status":"provisional","publicationKey":"e350c031b951d0c738a671a967571abdd2c6624a41888e13c8ec9e8a094adf48"}} -->
# Initialize the agenda only with an active calendar

The agenda should not activate when all calendars are deactivated. Check the calendar-deactivated state before initializing; the deactivator can call ensureInitialized later when a calendar becomes active.

Scope: calendar-agenda.

Paths:

- `calendar/base/content/today-pane-agenda.js`

## Evidence

[Shared lesson record](../records/8cadd088538798fa266a78873c824df30d553e89c036eba14fcaf77211aa4fb4.json).

- https://phabricator.services.mozilla.com/D282319
- https://github.com/thunderbird/thunderbird-desktop/commit/952e540e484b957a2da53469d7b09c6ad735a876

Source record: `016ea697d9d7175e5c5cfe7e34519602e413126fd5ee187eb640cf658e7d3c10`

~~~
document.documentElement.hasAttribute("calendar-deactivated")
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `bc24f5db63d65f88dca57957d0a8fa1f80cda1247362ff5dd52a58922d76c7c6`.
