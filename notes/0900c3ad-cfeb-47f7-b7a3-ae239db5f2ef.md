<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:44:20.418798+00:00","paths":["storage/StorageBaseStatementInternal.cpp"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","language":"C++","fileRole":"production","component":"storage","publicationKey":"pilot-body-contract-map:0900c3ad-cfeb-47f7-b7a3-ae239db5f2ef","revisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"verification":"Source bodies and scoped callers/tests checked by analysis agent; independent audit is separate and sampled. Derived map sections are not another independent evidence source."}} -->
# storage/StorageBaseStatementInternal.cpp source body contracts and relationship limits

These sections explain source bodies. They retain conditions, state, results, ownership, tests and unresolved relationships from the focused body analysis. This map restates the same analysis as the focused notes; it is not another independent confirmation. Contract IDs identify sections, not knowledge JSON record filenames. Full component behavior and passing tests are not certified.

## AsyncStatementFinalizer::Run at 41 to 51

Evidence: `storage/StorageBaseStatementInternal.cpp:41-51` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "c96fd1fdb7f26688ef53108509bd7c565bd6a9c64ab6d4761b6009f13f91e3b9",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "AsyncStatementFinalizer::Run",
  "lineRange": [
    41,
    51
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "a7e7b38217e0b99a7594610a73ef7e3a1046ff49415ab8f9c49caf1b8f61cb6a",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Explicit base asyncFinalize queues this event.",
  "stateReads": [
    "mStatement native pointer",
    "connection opening target"
  ],
  "stateWrites": [
    "sqlite finalized",
    "mAsyncStatement=null",
    "mStatement forgotten"
  ],
  "resultAndCompletion": "Runs cleanup on helper thread then returns NS_OK.",
  "errors": "Native finalize result ignored; proxy release status not handled.",
  "ownership": "Event strongly retains statement and connection.",
  "cleanup": "Statement release is sent to opening target.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## LastDitchSqliteStatementFinalizer::Run at 87 to 95

Evidence: `storage/StorageBaseStatementInternal.cpp:87-95` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "0ac9f219c0e5b153cf96fe94c9648bbcc7a3ea9f7908d9ed052b833d5e8f041b",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "LastDitchSqliteStatementFinalizer::Run",
  "lineRange": [
    87,
    95
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "a6ccf08994e32c842fd3bb4c04ddeea23a2c6c86fc3c3c1b97513e106466276a",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Statement destructor invokes or queues last native cleanup.",
  "stateReads": [
    "mAsyncStatement",
    "connection opening target"
  ],
  "stateWrites": [
    "sqlite finalized",
    "mAsyncStatement=null",
    "mConnection forgotten"
  ],
  "resultAndCompletion": "Returns NS_OK after native finalize and proxy release.",
  "errors": "Ignores finalize/proxy-release return values.",
  "ownership": "Event owns raw native pointer and retains connection.",
  "cleanup": "Releases connection on opening target.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## StorageBaseStatementInternal::asyncFinalize at 108 to 124

Evidence: `storage/StorageBaseStatementInternal.cpp:108-124` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "d273cc2bce65a899e105452feaf4fb3120012a8146d53daa1acb0942b5d34999",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "StorageBaseStatementInternal::asyncFinalize",
  "lineRange": [
    108,
    124
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "ca65acf8ec2128a634704be7397800a4a8e468246896360ef0edcc72027de557",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Explicit statement Finalize requests helper-thread cleanup.",
  "stateReads": [
    "connection async target"
  ],
  "stateWrites": [
    "queued retaining finalizer when target exists"
  ],
  "resultAndCompletion": "Returns void; no target lets connection close own cleanup.",
  "errors": "Dispatch failure ignored to let close win.",
  "ownership": "Finalizer retains statement/connection while queued.",
  "cleanup": "Close path finalizes native statements if no helper target.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## StorageBaseStatementInternal::destructorAsyncFinalize at 126 to 150

Evidence: `storage/StorageBaseStatementInternal.cpp:126-150` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "c50ca30bf7e8ef7727f4c6c60ad3eed8b0ee65e62a1cdd027bd10bc6c75c3afd",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "StorageBaseStatementInternal::destructorAsyncFinalize",
  "lineRange": [
    126,
    150
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "21612d74d38e633963726290a12e836faf905ab00572910255097816bc8d7adf",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Last statement reference invokes destructor.",
  "stateReads": [
    "mAsyncStatement",
    "opening target",
    "async target"
  ],
  "stateWrites": [
    "mAsyncStatement=null"
  ],
  "resultAndCompletion": "Queues or directly runs last-ditch cleanup; does nothing when native pointer absent.",
  "errors": "Dispatch failure ignored; connection shutdown expected to own native cleanup.",
  "ownership": "Finalizer retains connection and owns native pointer.",
  "cleanup": "Clears local pointer regardless of dispatch branch.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## StorageBaseStatementInternal::NewBindingParamsArray at 153 to 160

Evidence: `storage/StorageBaseStatementInternal.cpp:153-160` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "de41f30545152540408ff9a27f265579fb7bcbe025ad43a7c1eadc1c9c3d1d2b",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "StorageBaseStatementInternal::NewBindingParamsArray",
  "lineRange": [
    153,
    160
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "884a01f26bc34cae2654bab6d3451e81439ad1d0913b00305a57fa43b688c48f",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Calendar prepareAsyncStatement or script helper requests array.",
  "stateReads": [
    "this owner"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Returns new owning binding-array reference.",
  "errors": "Out-of-memory return check.",
  "ownership": "New array retains this statement owner.",
  "cleanup": "Later binding locks array and removes back reference.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## StorageBaseStatementInternal::ExecuteAsync at 163 to 180

Evidence: `storage/StorageBaseStatementInternal.cpp:163-180` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "a403c6934a812db12b5060a2dcf5c6069bee7576369332a74f5878cef923ffd8",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/StorageBaseStatementInternal.cpp",
  "symbol": "StorageBaseStatementInternal::ExecuteAsync",
  "lineRange": [
    163,
    180
  ],
  "sourceSHA256": "e2c3d68fa4bd852c043e754ed9adefcac786f80b0748be777eb4afd004a4e708",
  "bodySHA256": "0ceac4210dd77ddcedd25f9c02e7dab821444a3845c08ae72f010572b3b93fb8",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "extended",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Statement-specific executeAsync submits one statement.",
  "stateReads": [
    "own bound data",
    "connection/native pointer"
  ],
  "stateWrites": [
    "transferred request data"
  ],
  "resultAndCompletion": "Returns pending handle via executor; request completion is callback-driven.",
  "errors": "getAsynchronousStatementData or executor setup errors propagate.",
  "ownership": "Executor owns statement data and callback; caller can retain pending handle.",
  "cleanup": "Executor resets/clears after execution.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_multiple_results",
      "lineRange": [
        830,
        840
      ],
      "linkClass": "executes",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "24f70549-76e7-4a5b-83f3-ba882d502594",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## Validation and limits

Source revisions and ranges are pinned. The analysis agent read the implementation and recorded scoped callers and assertions. Independent peer checks cover a subset and retain corrections; other sections remain provisional. A direct test link is an assertion relationship, not an observed test pass. Controlled probes and product results retain their own environment limits. Imported or generated implementations, unsupported branches, dynamic calls and native platform behavior require the stated follow-up evidence.

Related focused notes from the same analysis (not independent supporting sources):

- [Gecko asynchronous execution takes each bound parameter array and retains its statement owner](24f70549-76e7-4a5b-83f3-ba882d502594.md)
- [Gecko statement finalization shares cleanup with the asynchronous connection close path](b6ae8c6e-201f-4af4-ae71-d08024d0ab33.md)
