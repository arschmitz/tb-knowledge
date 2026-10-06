<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.105Z","paths":["mailnews/base/src/nsMsgDBFolder.cpp"],"source":{"reference":"https://phabricator.services.mozilla.com/D306636","status":"provisional","publicationKey":"650173579d081e4f7d25016f04195e7642a4278b8f126918ae4d4a76896222a5"}} -->
# Guard auto-compaction against nested event loops

The modal compact dialog spins an event loop. An autosync timer or another compact event can then reenter database commit and corrupt Mork iterators. A scoped reentrancy guard lets only one auto-compaction cycle run at a time.

Scope: mail-database.

Paths:

- `mailnews/base/src/nsMsgDBFolder.cpp`

## Evidence

[Shared lesson record](../records/58fc6da5f502a94710b4da3f0501808d845a2b62e6fc16fdda938cbaa27e8779.json).

- https://phabricator.services.mozilla.com/D306636
- https://github.com/thunderbird/thunderbird-desktop/commit/49d2d48ef8b93f0e983ad3f74864382cef8799ec

Source record: `e08df9aa2ab6915233843d64c870ee08f3d8e2df216c361b79a87c6b05d8187f`

~~~
gAutoCompactInProgress = true
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `225e3f50b75b0ddc1e53f99ba4a8f830de49b7a9bd7e283e627fd2d1025f1d9f`.
