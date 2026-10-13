<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T08:01:12.504073+00:00", "paths": ["calendar/providers/caldav/modules/CalDavRequestHandlers.sys.mjs", "calendar/providers/caldav/CalDavCalendar.sys.mjs", "calendar/providers/caldav/modules/CalDavRequest.sys.mjs", "calendar/test/unit/test_caldav_requests.js", "calendar/test/unit/providers/test_caldavCalendar_cached.js"], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "caldav-body-study-20261013", "verification": "Bodies, receivers and named callers/assertions read; execution results have separate scope"}} -->
# CalDAV WebDAV sync tracks tokens, server deletions, pages and changed item fetches

CalDavWebDavSyncHandler:402–807 owns calendar, collection URI, listener, reported
ETags, fetch queue, new token and additional-page state. doWebDAVSync XML-escapes
the stored token or sends empty token for a full listing, sets REPORT/Depth1,
and supplies itself to LegacySAXRequest. Awaiting its commit reaches header
completion, not awaited DOM/storage completion; see [request lifecycle](7b3c6223-e72d-4ade-b71d-edcf00d38784.md).

onStart/onStop:493–579 accept207. Rate-limit429 and the checked403 error body
notify failure without applying full deletion. Other client errors with a token
clear/persist that token and retry full sync; remaining errors report DAV failure.
startDocument starts batch. endDocument:598–653 ends/fails on unhandled errors;
for a full listing without additional page, deletes known paths not reported;
then ends batch and either starts Multiget with new token/page state or saves
token and starts another sync/finalizes. These transitions are actual receiver
calls into the calendar and storage, not structural links based on token names.

endElement:690–805 interprets404 as deletion and awaits deleteTargetCalendarItem,
catching/logging per-item errors. Calendar content plus href+ETag records a path
and queues changed ETag for fetch. Its status condition uses raw indexOf results
for204/200/201; -1 is truthy in JavaScript. Therefore it is not an exact success
status check. The directory-ignore condition likewise uses indexOf truthiness.
507 marks more pages without comparing response URL. Other relevant unexpected
responses increment unhandledErrors. Every25 response entries await a timer to
yield the event loop. Full removal waits for the final page; a partial page is
not proof that unreported local items disappeared remotely.

Direct cached testSyncError1:182–233 checks existing item, rate-limit refresh,
NS_OK/not-disabled and retention after recovery. testSyncError2:235–281 creates
four items, resets saved sync token, refreshes across pages and asserts all four
remain. These check preservation/page outcome. They execute token and fetch
branches but do not directly assert every token persistence ordering, status
truthiness or batch-cleanup failure. Requests tests923–935/954–970 directly
assert non-ASCII decoded logXML with mocked calendar storage, not full reconcile.
Those source assertions were read; cached runtime was not run here and requests
runtime failed during setup. Remaining malformed XML/status and rejected storage
branches are explicit gaps, not claimed verified connections.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. All paths and ranges refer to these commits.
Use `git show REVISION:repository-relative-path` to read exact evidence.
Production privileged JavaScript, test bodies, fixtures and build files are
identified separately. Direct source observations do not establish runtime reachability
outside the checked callers. Inferred effects and unresolved branches are marked.
Test links describe assertions, not assumed passes. The run record gives the build limits.
Suite, immutable prior evidence and deliberate instructions were not changed.
