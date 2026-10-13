<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T07:04:56.477975+00:00", "paths": [], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "provider-stream-body-study-20261013", "verification": "Scoped implementation and caller reads; test assertion links checked; execution evidence is separate"}} -->
# Provider and stream body coverage extends the existing ingestion without repeating the census

This pass reuses the existing census, symbol maps and relationship-site records.
It adds checked implementation/receiver/caller/test relationships for missing
provider, stream, listener and conflict behavior. Existing immutable evidence is
preserved; deliberate instructions and source files were not edited.

- [Memory Calendar item ownership, modification checks, and deletion results](d5525182-1c3b-44b0-b884-628ae793c06c.md)
- [Memory Calendar query filters, offline flags, and stream completion](2533a78a-1621-46bd-853b-14b093449c5c.md)
- [Cached Calendar construction, forwarding, observers, and refresh lifetime](55ff1379-dcc7-4998-98e9-5e6c756cbd6d.md)
- [Cached Calendar full synchronization, conflict decisions, and pending promise state](14b243b1-6109-4ba9-be50-d66b7b09c49c.md)
- [Cached Calendar offline replay and UID conflict response transfer](d101f4f8-ec5c-476d-b24d-0a133286bb55.md)
- [Cached Calendar modify and delete completion, offline fallback, and error boundaries](136d02e0-8196-4513-b49a-d763668afe02.md)
- [Calendar bounded streams: count, buffering, closure, and consumer cancellation](7d993b50-8d13-4bfe-8370-e91b00be5ce0.md)
- [Calendar stream iteration crosses Gecko reader locks, completion, and release](450fde4b-f244-4729-a6ad-7184d64e8fa4.md)
- [Calendar observer snapshots, batch ownership, and OperationGroup cancellation order](a3e61d84-1dc0-47d3-9d1c-84f712e4b2f6.md)
- [FreeBusy service provider fan-out, result meaning, cancellation, and direct checks](1723fcfd-17f6-4b34-828b-ad24adfb866f.md)
- [Calendar provider properties, identities, scheduling filters, and registry lifetime](8f8ea086-ed09-4e20-b77f-ed42397af300.md)
- [Calendar conflict prompt connects decision state, DOM changes, Fluent IDs, and packaging](1fecfd15-4844-42c4-8d16-2314a935d7f3.md)
- [Provider and stream boundary experiments use pinned bodies with controlled runtime mocks](6003e9eb-1aa2-4b14-a0d6-ff0d8071a0aa.md)
- [Calendar provider and stream test run: seven pass, two CalDAV setup failures](e613241b-b978-4446-90b6-85aef3170232.md)

Full local production bodies read: CalMemoryCalendar.sys.mjs (517 lines),
CalCachedCalendar.sys.mjs (1078), CalReadableStreamFactory.sys.mjs (310),
calIteratorUtils.sys.mjs (278), calDataUtils.sys.mjs (325),
calProviderUtils.sys.mjs (994), CalFreeBusyService.sys.mjs (97),
calendar-conflicts-dialog.js (40) and its XHTML. Gecko
ReadableStreamDefaultReader.cpp (452) was read in full. External dependencies
remain separate scopes; reading a file is not proof of all runtime states.

Full test bodies read: test_providers.js, test_calreadablestreamfactory.js,
test_calIteratorUtils.js, test_calProviderUtils.js, test_utils.js,
test_freebusy_service.js, test_caldav_offline_modify_playback.js,
test_ics_offline_playback.js and test_caldav_uidCollision.js.
Gecko default-reader WPT was read only in cited ranges. No product pass is
claimed by this coverage record; test attempts/results have separate evidence.

Newly resolved important links include actual provider callback field consumption,
cache versus remote observer forwarding, conflict prompt argument identity,
offline reply transfer to fetched server copy, custom iterator to native reader
ownership, and tests that assert view query results after reconnect.
Missing apparent coverage was identified: commented offline tasks and an iterator
assertion that assigns instead of comparing. Tests that bypass the modal UI are
kept distinct from direct UI tests.

Remaining work stays active: all provider transport/refresh/queue bodies; native
controller scheduling and full cancellation; iterator caller cleanup paths;
storage journal persistence/restart; HTTP/auth/certificate native receivers;
unverified error and cancellation tests; other files still carrying only
automated maps. Earlier parser failures remain failures until separately repaired
or read. Suite remains excluded. These gaps guide the next reads; they are not
an excuse to stop at this checkpoint or claim exhaustive understanding.

## Source scope

Thunderbird: `87d0159c7149a43253964c2cb6917939557dc799`. Firefox: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. All source ranges refer to these commits.
Use `git show REVISION:repository-relative-path` in the named repository.
This is checked static behavior in the stated scope. Test links describe the
assertions read. They do not establish a passing run. Runtime experiments and
test-run limits are recorded separately. No instructions or product code changed.
