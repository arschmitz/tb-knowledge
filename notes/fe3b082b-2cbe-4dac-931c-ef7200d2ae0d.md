<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T08:01:12.504073+00:00", "paths": ["calendar/providers/caldav/modules/CalDavRequestHandlers.sys.mjs", "calendar/providers/caldav/CalDavCalendar.sys.mjs", "calendar/providers/caldav/modules/CalDavRequest.sys.mjs", "calendar/providers/caldav/modules/CalDavUtils.sys.mjs", "calendar/test/unit/test_caldav_requests.js"], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "caldav-body-study-20261013", "verification": "Bodies, receivers and named callers/assertions read; execution results have separate scope"}} -->
# CalDAV XML handlers buffer network bytes and reconcile ETag listings with local storage

XMLResponseHandler:27–141 owns byte chunks, a binary stream reader, channel and
decoded text. onDataAvailable reads the supplied byte count into Uint8Array chunks.
It is not incremental SAX parsing: handleResponse decodes accumulated bytes using
channel charset or UTF-8, builds a DOM with DOMParser, then walks it. _walk:96–141
awaits endElement and recurses through child/sibling nodes; callbacks get local
names and an empty namespace string. A caught parse exception calls fatalError
without an immediate return. A returned parser-error DOM needs separate checking.
reset clears chunks/channel/decoded response for the next multiget batch.

CalDavUtils:16–71 resolves D/DAV, C/CalDAV, A/Apple and CS/CalendarServer prefixes,
builds namespace strings from tag prefixes and returns null for unknown names.
Request PropfindResponse:888–924 instead uses namespace URI plus local name for
canonical property names and combines propstat properties under href. Decorators:
777–881 convert known types to hrefs, arrays, Sets or text; missing privileges
with 404 map to null. Unknown properties use trimmed text or null. Consumers
must distinguish namespace-aware property processing from handler local-name
dispatch. A matching XML local name alone does not prove the namespace.

CalDavEtagsHandler:151–392 receives calendar, base URI and changelog listener.
On successful207 stop it awaits DOM walk, starts backing batch, compares stored
paths with itemsReported and deletes missing items, then ends batch in finally.
Deletion here removes href index before awaiting backing delete, but does not
use the same complete itemInfo/metadata cleanup as deleteTargetCalendarItem.
The path scope expression uses baseUri.length in a substr comparison although
actual callers supply a URI object; native/string conversion impact is unresolved.
It starts Multiget for missing/changed ETags, otherwise reports completion and
can emit onLoad for deletions or poll inbox. Header and stop errors can each
notify failure; request commit does not await the whole stop body.

Response callbacks only record calendar content with href+ETag, ignore collection
entries and normalize some server content-type variants. ETag comparison uses
actual mHrefIndex→mItemInfoCache item record. This is not a same-name lookup.
Mutating listing/parse/target storage changes can affect deletion and refill.

Direct request tests737–783 check actual Propfind typed values and null missing
property;937–970 check both UTF-16 decoder paths. test_caldav_client:912–918
asserts one item and its Japanese title through a registered real provider, so it
checks a returned-item chain rather than XML text alone. Source assertions do
not check every namespace ambiguity, removal ordering or rejected storage write.
The requests runtime attempt failed before these assertions.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. All paths and ranges refer to these commits.
Use `git show REVISION:repository-relative-path` to read exact evidence.
Production privileged JavaScript, test bodies, fixtures and build files are
identified separately. Direct source observations do not establish runtime reachability
outside the checked callers. Inferred effects and unresolved branches are marked.
Test links describe assertions, not assumed passes. The run record gives the build limits.
Suite, immutable prior evidence and deliberate instructions were not changed.
