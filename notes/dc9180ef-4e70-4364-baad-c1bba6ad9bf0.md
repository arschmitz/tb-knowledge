<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T07:31:22.704574+00:00", "paths": ["dom/streams/UnderlyingSourceCallbackHelpers.cpp", "dom/streams/UnderlyingSourceCallbackHelpers.h", "dom/streams/ReadableStream.cpp", "dom/file/Blob.cpp", "dom/fetch/Fetch.cpp", "dom/webtransport/api/WebTransportReceiveStream.cpp", "dom/streams/StreamUtils.h", "testing/web-platform/tests/FileAPI/blob/Blob-stream.any.js"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revisions": {"thunderbird": "87d0159c7149a43253964c2cb6917939557dc799", "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"}, "status": "supported", "study": "native-stream-body-study-20261013", "verification": "Implementation bodies and named callers/assertions read; observed execution has its own scope"}} -->
# Gecko native input streams own asynchronous read waits, worker references, and shutdown cleanup

Production Gecko C++. Full local helper bodies and inline header read. This is
a native byte-stream branch. Calendar's ordinary array streams instead use the
checked [JS callback adapter](626a1a55-ba5a-447c-851e-db8c3267dbae.md); no cross-link is invented from the
shared word stream.

Actual creators: Blob::Stream,Blob.cpp315–347, creates an input, native non-async
adapter and CreateByteNative. FetchBody<GetBody>,Fetch.cpp1664–1716, lazily creates
and retains stream for Request/Response body, locks when already consumed, and
handles/follows abort signal. WebTransportReceiveStream::Create44–66 converts its
DataPipeReceiver into nsIAsyncInputStream, creates async adapter, sets native byte
controller and retains stream by ID in WebTransport. Complete Blob/Fetch/WebTransport
ownership/abort bodies remain external scopes beyond these entry ranges.
CreateByteNative/SetUpByteNative,ReadableStream.cpp1332–1369, sets byte controller
with default highWaterMark0. This branch pulls on reads rather than greedily
reading the whole input when stream object is created.

NonAsyncInputToReadableStreamAlgorithms retains nsIInputStream. First pull,
CPP578–600, transfers it through NS_MakeAsyncNonBlockingInputStream and creates
InputToReadableStreamAlgorithms. Doing this only at first pull avoids starting
native read at construction. Later pulls reuse async adapter. Header313–333
releases async resources and/or closes retained original input; getter/setter
for unread stream preserve identity and require no prior read.

Async adapter CPP239–276 owns current serial event target, InputStreamHolder,
stream and one pull promise. Pull creates promise, starts actual AsyncWait on
owning target and returns it. A wait failure propagates into stream error.
Holder161–230 owns nsIAsyncInputStream, weak callback pointer, strong worker
references and a temporary strong algorithms reference while wait is outstanding.
Successful AsyncWait saves those references; OnInputStreamReady clears wait
worker ref and transfers algorithms reference into callback. This prevents pending
read promises/source from being collected before input readiness. Worker Init
also creates a worker ref cycle; shutdown/global teardown breaks it and closes input.

OnInputStreamReady280–350 ignores closed adapter, reads Available, treats stream
closed as graceful close, propagates other errors, and pulls bytes only with an
active pull promise. Successful pull resolves undefined and clears that promise,
then subscribes to closure-only wait. That promise means one pull attempt is done;
consumer's read request carries bytes separately. Closure-only registration failure
passes errorResult.StealNSResult rather than the failed rv in this body; exact
impact on overriding error mappings remains a separate unresolved branch.

PullFromInputStream401–498 limits each read to min(available, current caller buffer
when BYOB,256MB). BYOB means the reader supplies its own buffer. Fills buffer and
reports actual bytes to byte controller; ordinary reads allocate Uint8Array and
enqueue actual bytes. Zero read means closed, not a zero-filled data chunk.
Buffer errors propagate; allocation failures become TypeError. Raw memory access
has a scoped no-GC guard during native read; byte controller internals remain
another source scope.

ReleaseObjects513–524 closes input with STREAM_CLOSED, runs holder shutdown,
clears input and pull promise. Pending read requests are settled by stream close
or error rather than that helper pull promise. CloseAndRelease500–511 releases
resources then closes native readable stream. ErrorPropagation532–557 treats
STREAM_CLOSED specially, otherwise builds error and errors native stream. Default
BuildErrorValue559–569 emits generic TypeError and does not expose exact nsresult;
subclasses can override. Holder shutdown deliberately may drop algorithms with
an unsettled promise during global teardown; that is a shutdown-specific design
limit, not a general cancellation policy.

Direct WPT Blob-stream.any.js was read in full: non-Unicode exact bytes55–62,
empty output48–53, dropping Blob and collecting during each read64–74, collecting
after starting stream consumption76–85, and BYOB output87–94. The basic PASS
case39–46 checks each returned byte without a separate length assertion. These
are direct byte/ownership checks for Blob public path, not tests of all wait
failure, worker shutdown, Fetch abort or WebTransport owner removal branches.
They were read, not run in this pass.

## Evidence scope

Thunderbird `87d0159c7149a43253964c2cb6917939557dc799`; Firefox `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Paths and ranges refer to these commits.
Read exact source with `git show REVISION:repository-relative-path`.
Observed source relationships and inferred effects are distinguished above.
Test existence and static assertion links are separate from observed runs.
No product code, deliberate instructions, immutable old records, or Suite changed.
