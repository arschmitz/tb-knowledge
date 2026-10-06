<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.201Z","paths":["mailnews/base/src/nsMsgSearchDBView.cpp"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/6fb2ea1383b5","status":"supported","publicationKey":"df2a3a99b237c8013753311fe037f782c5ae58dbadfb443100742f99299b7d41"}} -->
# Batch synthetic search tree notifications across one search

nsMsgSearchDBView opens a tree update batch in OnNewSearch and closes it in OnSearchDone. This prevents an update for every message hit while the synthetic results list fills. Bug 1896913 measured about 12 to 4 seconds for roughly 800 results in a debug build; the exact timing is historical and workload-specific. The pattern came from nsMsgXFVirtualFolderDBView and remains in current code. Keep begin/end paired, including completion paths, if search lifecycle changes.

Scope: Search results view performance.

Paths:

- `mailnews/base/src/nsMsgSearchDBView.cpp`

## Evidence

[Shared lesson record](../records/c53edb256ab36860befbd1eca7e837789cd78274e556e0cf3265bb102e9fc31d.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/6fb2ea1383b5
- https://bugzilla.mozilla.org/show_bug.cgi?id=1896913
- https://phabricator.services.mozilla.com/D210494

Source record: `f33e245d969e287d0ad69dae4b3f182e1ed37acb2f7d5855522130dc438ae44b`

~~~
mJSTree->BeginUpdateBatch();
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `47ddb24a297eaf96b45470c8dfcf363269de22c424ce0102accb178f79a800db`, `6f21103c325cf26b10003d1079c66b1fd0aced2d8a67e3f9a08f2feccf13cc9d`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `5a1ee2cf09aa985c15711a974ae1575a2ef0cf603ef4f7a2d2c10346623c4396`.
