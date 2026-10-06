<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.147Z","paths":["mail/base/content/widgets/tree-view.mjs"],"source":{"reference":"https://phabricator.services.mozilla.com/D284929","status":"provisional","publicationKey":"281a5c343fdd557282a3db3fdd29e87477b3e13c1950753dbe0db2180a76f2b5"}} -->
# Separate tree display and selection roles

BaseTreeView creates and updates the HTML table and allows normal keyboard navigation without selection. TreeView adds selection and its own key handling. Choose the base class when a tree only displays nested content.

Scope: tree-accessibility.

Paths:

- `mail/base/content/widgets/tree-view.mjs`

## Evidence

[Shared lesson record](../records/7321eb5054cfee795f9732b7964e832f171dd396c085441eb0d568ff5f7d8d6c.json).

- https://phabricator.services.mozilla.com/D284929
- https://github.com/thunderbird/thunderbird-desktop/commit/c2310831dfbc0ad01a4325f10be0b515b01c91e9

Source record: `4de1ed280ec875d0c9ab04e3195574d258a1f1828a6c65c3faee8d66d270ff2b`

~~~
export class BaseTreeView extends HTMLElement
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `e1fee072e4af397f64e522b9f6f581a49242fa37f3cb28bb95d7d5e38e8dc1f2`.
