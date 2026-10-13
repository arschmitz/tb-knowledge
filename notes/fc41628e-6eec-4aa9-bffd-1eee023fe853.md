<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T15:24:25.555247+00:00", "paths": ["toolkit/components/places/BookmarkList.sys.mjs", "toolkit/components/places/PlacesTransactions.sys.mjs"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "supported", "study": "ingestion-pilot-20261013T145636Z", "verification": "Checked body behavior, callers and named assertions; runtime results are separately scoped", "bodyContractCount": 0}} -->
# Exact Places JavaScript probe distinguishes grouping and cache outcomes from native runtime claims

## Observed controlled outcomes

An exact-body JavaScript probe reached four narrow outcomes:

- Two standalone NewBookmark transactions both started their insert before either insert completed. `transact()` bypasses `_mainEnqueuer`; source overview text describing every operation as serialized does not establish that guarantee here.
- Repeated `entry(0)` calls returned the same array object. The implementation returns a live alias despite its snapshot comment.
- With a prior independent undo entry, a batch whose first insert failed and second insert succeeded returned an undefined first slot and merged the successful member into the prior entry. `batchIndex` is the original accumulated result position, so the first successful member did not force a new entry in this scenario.
- Constructing BookmarkList with a URL, immediately removing its listeners, then calling `isBookmark` still fetched that pending URL and returned true. `setTrackedUrls([])` did not empty the pending hash set.

These are reached outcomes in the controlled JavaScript environment. They are not a reproduction of native SQLite behavior, a live browser UI defect, a real timer timeout or a product test pass.

## Evidence

[toolkit/components/places/PlacesTransactions.sys.mjs:253-266](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/PlacesTransactions.sys.mjs#L253-L266); [toolkit/components/places/PlacesTransactions.sys.mjs:314-354](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/PlacesTransactions.sys.mjs#L314-L354); [toolkit/components/places/PlacesTransactions.sys.mjs:429-435](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/PlacesTransactions.sys.mjs#L429-L435); [toolkit/components/places/PlacesTransactions.sys.mjs:539-570](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/PlacesTransactions.sys.mjs#L539-L570).

[toolkit/components/places/BookmarkList.sys.mjs:101-167](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/BookmarkList.sys.mjs#L101-L167); [toolkit/components/places/BookmarkList.sys.mjs:227-237](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/toolkit/components/places/BookmarkList.sys.mjs#L227-L237).

## Validation and limits

Run time: `2026-10-13T15:05:16.665Z`. Runtime: Node.js `v26.3.1`, macOS (`darwin`) on `arm64`. Source revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Source SHA-256 values: PlacesTransactions `3fc512565f85ef05ec3da881b329e0cd99628549bdbfb59c306e8201d15c9e87`; BookmarkList `ba7f41c5f73e7928ffeea5550f1b84daca432b671be8cb37e2ae4395329a4fd1`.

The actual module bodies ran with fake storage, logger, timer, Places observer service and DeferredTask. Import/export syntax was adapted for the isolated JavaScript context; function bodies were unchanged. The probe did not invoke timeout callbacks. New assertion messages contain "should". Native/event scheduling, UI reachability and real database locking remain unverified.
