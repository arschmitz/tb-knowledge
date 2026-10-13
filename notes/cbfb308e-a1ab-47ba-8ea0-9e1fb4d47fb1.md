<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T07:14:49.817411+00:00", "paths": [], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "ics-native-body-study-20261013", "verification": "Implementation bodies and named callers/assertions read; observed execution has its own scope"}} -->
# ICS provider and native file-write coverage closes missing body and test links

This pass adds body/caller/state/result/error/ownership/test analysis to the prior
structural maps; no repeated census or automated link-site expansion was needed.

- [ICS Calendar queue, lock ownership, callback ordering, and mutation result limits](ce4bf3f0-4a84-48aa-b5b0-db7cc711eb56.md)
- [ICS download and parse completion, memory replacement, and error preservation](ad489428-6807-4539-99d9-c0716fb4217a.md)
- [ICS serialization and file or HTTP write completion cross different boundaries](1493e123-1336-4136-be3e-8ebca7322420.md)
- [ICS backup names, retention, preference reads, and async failure ownership](b7344a01-b388-4d80-9361-7df001be0fc2.md)
- [ICS HTTP and file transport hooks read validators and decide whether to reuse or write](de5d7ca4-ed06-4d57-a9ee-c7baa3224873.md)
- [ICS connection failure and restoration change notification and provider state](467e762f-45e5-42fa-b3f3-d3252e1280dd.md)
- [ICS local writes call Gecko IOUtils for temporary-file replacement and promise settlement](f3d5fb67-74e7-4816-bc07-2d63b437b5c0.md)
- [Calendar HTTP preparation and certificate exception callbacks retain actual owners and receivers](53d854f0-1476-426b-86cc-dcd0d96fc119.md)
- [ICS exact-source completion experiment resolves an add after write preparation fails](9df354ad-28e5-4ab8-b7ff-a4a426019a07.md)
- [Cached and uncached ICS provider test files passed in the existing macOS build](e4a1c179-afc4-4ba0-95c4-4d45a4b6f5e2.md)
- [Published provider and stream records were imported locally and retrieved independently](804d4336-5d4c-492b-b47c-d52566f6770d.md)

All local bodies read: CalICSCalendar.sys.mjs1266 lines,
ConnectionNotifications.sys.mjs90, ICSServer.sys.mjs161; provider head251,
cached ICS test227, uncached ICS test56; browser cache-toggle test92.
Native IOUtils write/create-unique/state/dispatch/move helpers were read only in
the recorded ranges, not the whole 3000-plus-line source. Full UTF-8 and unique-file
tests plus helper read; generic binary write tests read only cited sections.
Pinned identities and range scopes are retained in a private ledger.

Adds direct wipe/refill and server deletion test relationships that were missed
by the earlier root Calendar unit-test pass. Distinguishes fixture server limits,
execution-only generic writer/CRUD links, possible username test, and unrun
browser/native assertions. Two installed ICS files passed; controlled error
completion is a separate mock result. No source policies or old notes changed.

Next unresolved boundaries remain work to perform: full parser/serializer bodies,
ICS queue memory rejection/cancel, all HTTP channel callbacks, ETag XPath result,
survival-area balancing, backup-copy rejection and cleanup, native OS file moves
and shutdown, provider manager cache-toggle/view owners, CalDAV provider request
and response bodies, other source still carrying structural-only coverage.
Earlier parser failures remain explicit, and Suite stays excluded. Work continues
from these specific gaps rather than treating this checkpoint as whole-codebase
behavior completion.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Paths and ranges refer to these commits.
Read exact source with `git show REVISION:repository-relative-path`.
Observed source relationships and inferred effects are distinguished above.
Test existence and static assertion links are separate from observed runs.
No product code, deliberate instructions, immutable old records, or Suite changed.
