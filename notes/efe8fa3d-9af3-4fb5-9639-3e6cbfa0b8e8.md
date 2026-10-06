<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.135Z","paths":["calendar/providers/caldav/CalDavCalendar.sys.mjs"],"source":{"reference":"https://phabricator.services.mozilla.com/D281620","status":"provisional","publicationKey":"c360da1fde8c937ca414e7a1c853802b45757a6a3b30758486e2889b47ae05b7"}} -->
# Refresh CalDAV organizer identity when the identity preference changes

A CalDAV calendar's organizer identity can be cached in ACL properties. When imip.identity.key changes, clear the cached organizer and identity fields before filling them again; stale identity data can make an invite look like it belongs to another user.

Scope: caldav.

Paths:

- `calendar/providers/caldav/CalDavCalendar.sys.mjs`

## Evidence

[Shared lesson record](../records/432a0ffdc46ca84a5e7042f07743a6fef78ae08c410be7490b7fad2f15c598a2.json).

- https://phabricator.services.mozilla.com/D281620
- https://github.com/thunderbird/thunderbird-desktop/commit/8d137d88bc1d90ba50a004eacede1e902c66cfce

Source record: `d3dc5019a435e9459da2bb24738eaa09990bd121900209808eee5ab5069fa9a0`

~~~
delete this.mACLProperties.organizerId
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `f3c23882f2a9aee6ac2141b164066a0632a980d2d0887d260112b282287bb12c`.
