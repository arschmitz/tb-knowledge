<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T15:24:25.555247+00:00", "paths": ["browser/components/firefoxview/opentabs.mjs"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "supported", "study": "ingestion-pilot-20261013T145636Z", "verification": "Checked body behavior, callers and named assertions; runtime results are separately scoped", "bodyContractCount": 3}} -->
# Firefox View owns BookmarkList and turns lookup results into row indicators

Each section is a checked body contract at Firefox revision `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. These records describe source behavior. They do not promote source patterns into coding policy.

## OpenTabsInView.start

Evidence: [OpenTabsInView.start:100-130](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/browser/components/firefoxview/opentabs.mjs#L100-L130).

Trigger: View visible callback starts tab display.

Guards already-started state, installs tab listeners, marks cards active, schedules initial-window readiness update and creates BookmarkList from all tab URLs. List observer requests updates on view cards.

Result and completion: Synchronous undefined. Bookmark counts are fetched later by card update.

Errors: No separate error handling in this body; caller receives thrown errors or promise rejection.

Ownership and cleanup: View owns BookmarkList and stops its listeners when hidden/disconnected. Native tab-target/ready promise details not read.

## OpenTabsInView.stop

Evidence: [OpenTabsInView.stop:144-167](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/browser/components/firefoxview/opentabs.mjs#L144-L167).

Trigger: View hidden/disconnected callback stops observation.

Guards inactive state, pauses cards, removes tab/recency/search listeners and calls bookmarkList.removeListeners. Does not await list finalization.

Result and completion: Synchronous undefined. Card updates already underway are not canceled by this body.

Errors: No separate error handling in this body; caller receives thrown errors or promise rejection.

Ownership and cleanup: Releases active listener registrations; retained view bookmarkList reference remains until restart replaces it.

## OpenTabsInViewCard.updateBookmarkStars

Evidence: [OpenTabsInViewCard.updateBookmarkStars:644-660](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/browser/components/firefoxview/opentabs.mjs#L644-L660).

Trigger: updated lifecycle callback invokes async bookmark indicator refresh.

Copies current tabItems array and checks each row sequentially with BookmarkList.isBookmark. Adds bookmark indicator for truthy result; removes it for false/undefined. Recomputes primary localization ID and writes array back after loop.

Result and completion: Resolves undefined after rows update. No generation/stale-row guard in this body.

Errors: Lookup rejection rejects; updated does not await/catch the call in the read range.

Ownership and cleanup: Uses the enclosing module or object state; this body does not release that owner.

Unresolved: Firefox View rendering and accessibility tests were not read/run; BookmarkList unit tests directly check its results but do not assert this consumer UI.

## Validation and limits

The implementation ranges and listed test assertions were read from the pinned Git revision. Fully read files and selected ranges are counted separately. Native storage, DOM event delivery, rendering and unlisted callers remain outside these body contracts. Test existence does not establish that a test passes. The coordinator records actual run results with build and environment evidence. No source, tests or deliberate instructions were changed.
