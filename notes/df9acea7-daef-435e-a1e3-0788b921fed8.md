<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.134Z","paths":["mail/components/calendar/content/calendar-dialog.mjs"],"source":{"reference":"https://phabricator.services.mozilla.com/D284210","status":"provisional","publicationKey":"43414131c598a95320364685bedcdb6f71bab87302bf8beca343031035b2f5c4"}} -->
# Close an open Calendar dialog before replacing its item

When the read dialog is already open and a different event is selected, close it before updating its data. This avoids showing stale content while the new item loads and positions.

Scope: calendar-dialog.

Paths:

- `mail/components/calendar/content/calendar-dialog.mjs`

## Evidence

[Shared lesson record](../records/b886afc4743257ca9aa82497fa044f3a4e2b46b6b94acc9123c37a67bfc9ce1c.json).

- https://phabricator.services.mozilla.com/D284210
- https://github.com/thunderbird/thunderbird-desktop/commit/eff657b4ff6c3433fb7304544a90eb14df3117ea

Source record: `4cfd9fb1e2870eb52f77248e82bd17aeaad1ccbe8aee888b49c90e1385720fc8`

~~~
if (this.open) {
+      this.close();
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `6a05a0e6dbd7c4b2f3509af452833a71f888b4a3f58624a68efcd8ba96e74249`.
