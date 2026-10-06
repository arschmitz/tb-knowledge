<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.129Z","paths":["mail/test/browser/composition/browser_emlActions.js"],"source":{"reference":"https://phabricator.services.mozilla.com/D286557","status":"provisional","publicationKey":"7804fbe46ada316350befd00001fe8df6749c8f3981b715ac12b2734519d530f"}} -->
# Bind a mock file picker to the focused compose window

When a browser test has more than one compose window, the mock file picker must use the browsing context of the window that will open it. Focus that window before the action so the picker and action use the same context.

Scope: browser-tests.

Paths:

- `mail/test/browser/composition/browser_emlActions.js`

## Evidence

[Shared lesson record](../records/dcb7a7ef7aedd9a34aa25ed706e58ec7abcdebba540811c0aa9687a604dbb6dd.json).

- https://phabricator.services.mozilla.com/D286557
- https://github.com/thunderbird/thunderbird-desktop/commit/bf0114af09d92cae5456ff6c083b461ef3212df1

Source record: `0336ef147758369148bfedd5a6d1e54ead8a95d33766da72a056f212d56f0a4e`

~~~
SpecialPowers.MockFilePicker.init(msgc2.browsingContext)
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `65e33a46590bceda7a85482f0cdfff1428914041e457f5b9cd1eac1b020e800b`.
