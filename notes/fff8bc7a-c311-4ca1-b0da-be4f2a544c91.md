<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.105Z","paths":["mail/base/content/widgets/pane-splitter.js"],"source":{"reference":"https://phabricator.services.mozilla.com/D307929","status":"provisional","publicationKey":"99db7946eb57963245926eb7d7a3c9e9f6c84f04588f2fe28ab1a9fb11761dbe"}} -->
# Coerce optional values before toggleAttribute

Element.toggleAttribute(name, undefined) toggles the attribute instead of removing it. Coerce the pane splitter's disabled state to a boolean, or a normal undefined syntheticView value can disable the splitter in later tabs.

Scope: mail-ui.

Paths:

- `mail/base/content/widgets/pane-splitter.js`

## Evidence

[Shared lesson record](../records/f62da95a95b23eb5bd3175caced2ae22a00d80622f265fb5531682bde9c5b146.json).

- https://phabricator.services.mozilla.com/D307929
- https://github.com/thunderbird/thunderbird-desktop/commit/1917056b32c480c9d88f085566ddfbbee5096593

Source record: `3330e469158762eb1d80d900a3632cde84cbeb5c6f6191c941b0b1b3d62bfc62`

~~~
this.toggleAttribute("disabled", !!disabled)
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `971acda0066926697e50800c79fe6111a9be4efadab7fd1b76799a06e17cb8c9`.
