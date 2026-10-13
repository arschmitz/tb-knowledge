<!-- knowledge: {"repository": "thunderbird", "at": "2026-10-13T08:34:30.203378+00:00", "paths": ["mail/modules/DNS.worker.mjs", "mail/modules/DNS.sys.mjs", "mail/modules/moz.build", "calendar/providers/caldav/CalDavProvider.sys.mjs", "calendar/test/browser/browser_calDAV_discovery.js"], "source": {"reference": "Git commit 87d0159c7149a43253964c2cb6917939557dc799", "revision": "87d0159c7149a43253964c2cb6917939557dc799", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "worker-body-study-20261013", "verification": "Checked bodies, receivers and named assertions; run evidence uses older native build"}} -->
# Thunderbird Unix DNS worker parses bounded query records and preserves explicit failure limits

Full worker569 lines read. load_libresolv:19–349 opens OS-specific libc/resolv
candidates, tries alternative symbol names and closes library if declaring a
required symbol fails. It declares search/query/name-expand/name-skip/16/32-bit
read functions. Runtime lookup uses res_search, not the separately declared
res_query. Query buffer is1024 bytes; DNS header/question/resource fixed sizes
guide offsets. Native library ABI implementation is external imported system code.

lookup:271–347 calls native search, returns [] for negative result, reads question
and answer counts, skips compressed question/name data and validates resource
payload against returned length. _safe_get16/32:164–190 validate index+field size
against that length. It does not separately cap returned length to allocated
buffer size in this body. Actual truncation behavior and ctypes array bounds are
separate targets; no native buffer exploit/runtime failure is asserted.
Only matching requested type is mapped; each result adds type,nsclass,signed32-bit
ttl. Invalid skipped name can return[]; invalid payload throws Error instead.

_mapAnswer:206–266 reads SRV priority/weight/port and expanded host, MX priority/
host, and TXT length-prefixed strings copied to separate arrays before readString.
TXT uses enclosing payload length for loop but does not check each txtlen against
remaining record bytes before copying. Host expansion failure sets null, then
SRVRecord/MXRecord constructors call host.toLowerCase:525–553, which can throw
TypeError. Thus [] and rejection/error are distinct failure shapes. No TTL caching,
sorting or SRV retry is done here; detector consumes returned fields later.

worker.execute:558–562 creates an OS wrapper per request and synchronously calls
its method. Both wrappers define close but this execute body never calls close.
Actual native library finalizer/declared function ownership is traced separately;
absence of explicit close is not proof that every lookup permanently leaks a
library. DNS singleton shutdown terminates promise worker, while per-query record
parsing and library lifetime are distinct ownership scopes.

Browser Calendar DNS test replaces srv/txt methods with arrays, checks detector
query names/list results and bypasses native worker entirely. The checked XMPP
SRV test checks sorting supplied records, not libresolv decoding. Neither proves
this parser's success/error cleanup. No real DNS or Unix parser product test ran.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Exact paths and ranges/named test anchors
refer to these commits. Use `git show REVISION:repository-relative-path`.
Production, generated-module template, build, test/helper and native code roles
are separated above. Inference and unresolved error/lifetime targets stay explicit.
Static assertions are distinct from observed build-scoped passes. Private files,
logs/indexes and local paths stay outside shared knowledge. Suite, immutable
prior records and deliberate instructions are unchanged.
