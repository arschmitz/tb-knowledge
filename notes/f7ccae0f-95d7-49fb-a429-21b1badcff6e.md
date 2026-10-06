<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.155Z","paths":["mailnews/base/src/nsMsgSearchDBView.cpp"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/a90a934a34c5c2707578df121e9905955ed4024d","status":"supported","publicationKey":"20c523da13d3fe8311b0cab63191636f05f32ad1b8a510d6d84d4dc563c137d2"}} -->
# Save sort choice even when a search view is empty

A quick-filtered cross-folder view may have zero rows while a new search is running. nsMsgSearchDBView::Sort must still store sort type and order in that case, or the next filter update restores the prior sort. The patch added an empty-view regression test.

Scope: message search views.

Paths:

- `mailnews/base/src/nsMsgSearchDBView.cpp`

## Evidence

[Shared lesson record](../records/7d29be9099f1ab25642b60854137d10810ab926f9c7ef2bb64d5ed8ef55ad3de.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/a90a934a34c5c2707578df121e9905955ed4024d
- https://bugzilla.mozilla.org/show_bug.cgi?id=1893799

Source record: `1acd1a9ea41d892fa8b7243ab7c99b15c49ac148a9e1086ecf5a572cead008ed`

~~~
SaveSortInfo(sortType, sortOrder);
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `8899fb9f5e17ce88eabf617502f03a4453ca348629a986bd7d253112e0ee670a`.
