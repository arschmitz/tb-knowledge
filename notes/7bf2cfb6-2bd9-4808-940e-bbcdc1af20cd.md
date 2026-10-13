<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:44:20.412308+00:00","paths":["storage/mozStorageBindingParamsArray.cpp"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","language":"C++","fileRole":"production","component":"storage","publicationKey":"pilot-body-contract-map:7bf2cfb6-2bd9-4808-940e-bbcdc1af20cd","revisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"verification":"Source bodies and scoped callers/tests checked by analysis agent; independent audit is separate and sampled. Derived map sections are not another independent evidence source."}} -->
# storage/mozStorageBindingParamsArray.cpp source body contracts and relationship limits

These sections explain source bodies. They retain conditions, state, results, ownership, tests and unresolved relationships from the focused body analysis. This map restates the same analysis as the focused notes; it is not another independent confirmation. Contract IDs identify sections, not knowledge JSON record filenames. Full component behavior and passing tests are not certified.

## BindingParamsArray::BindingParamsArray at 15 to 17

Evidence: `storage/mozStorageBindingParamsArray.cpp:15-17` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "af76c8ffd9d041ac7110d03ce50824baba3d60f39035b72df2f8b25ccb3ea107",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::BindingParamsArray",
  "lineRange": [
    15,
    17
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "09c3e327f62180b1c558a74a8774f5cd665a9756c8d0602e5bd365ea336a6d84",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "StorageBaseStatementInternal::NewBindingParamsArray creates this with its receiver as owner.",
  "stateReads": [
    "aOwningStatement"
  ],
  "stateWrites": [
    "mOwningStatement",
    "mLocked=false"
  ],
  "resultAndCompletion": "Constructs an empty unlocked array.",
  "errors": "No local error return.",
  "ownership": "Array initially strongly owns creating statement; rows not yet stored.",
  "cleanup": "lock clears the owner reference.",
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

## BindingParamsArray::lock at 19 to 26

Evidence: `storage/mozStorageBindingParamsArray.cpp:19-26` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "e07b52f2e1078f0ad302b0d074a4f0ed9aebdc75cf1d428bb170a830edf949ee",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::lock",
  "lineRange": [
    19,
    26
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "ac965f141d72863a920aa6dd0b381734e920e295dd729d9d67b68e070fc471e2",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "AsyncStatement::BindParameters and Statement::BindParameters retain and lock submitted arrays.",
  "stateReads": [
    "mLocked"
  ],
  "stateWrites": [
    "mLocked=true",
    "mOwningStatement=null"
  ],
  "resultAndCompletion": "Returns void after blocking future row creation/addition.",
  "errors": "Debug assertion detects already locked array.",
  "ownership": "Statement now owns array, so dropping array-to-statement reference avoids a cycle.",
  "cleanup": "Clears statement reference immediately.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_bind_params_array_already_locked",
      "lineRange": [
        749,
        765
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## BindingParamsArray::getOwner at 28 to 30

Evidence: `storage/mozStorageBindingParamsArray.cpp:28-30` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "ea6f761a69bd4596c73494d11c83f294766658457e7e9b1a8f261beba3edc14a",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::getOwner",
  "lineRange": [
    28,
    30
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "24a471425a452590edeb6dd1c97051488962ea314e2c79f450e6de0fa01ced4d",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Statement/AsyncStatement BindParameters compare returned pointer against actual receiver.",
  "stateReads": [
    "mOwningStatement"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Returns borrowed creating statement pointer; returns null after array locking.",
  "errors": "No local error.",
  "ownership": "No new ownership is transferred.",
  "cleanup": "No cleanup in getter.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_not_right_owning_statement",
      "lineRange": [
        799,
        814
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## BindingParamsArray::NewBindingParams at 38 to 47

Evidence: `storage/mozStorageBindingParamsArray.cpp:38-47` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "9b38514bcf48a1af597ea2bacaa310313df09eb06643f418121bbf783a76f0ce",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::NewBindingParams",
  "lineRange": [
    38,
    47
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "070403c54c213acc30e7d4fa9a026ef84654f5769e60254cc32c735127434777",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Calendar database prepareAsyncParams asks array for a row.",
  "stateReads": [
    "mLocked",
    "mOwningStatement"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Returns a newly owning mozIStorageBindingParams reference produced by owner.newBindingParams.",
  "errors": "Locked array or null produced row returns NS_ERROR_UNEXPECTED.",
  "ownership": "Row initially retains array, which retains statement.",
  "cleanup": "Later AddParams locks row and clears its back references.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_no_binding_params_from_locked_array",
      "lineRange": [
        767,
        782
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## BindingParamsArray::AddParams at 50 to 64

Evidence: `storage/mozStorageBindingParamsArray.cpp:50-64` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "260d837719cbddd4561d4dd10de75886254c130346e89e874900fc2fd266ad02",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::AddParams",
  "lineRange": [
    50,
    64
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "1a5b61819df2dc3a90d6c1fb2c62d1c1ce4c6123c27213b5bca68c21a13f61d5",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Calendar item preparation adds each completed binding row.",
  "stateReads": [
    "mLocked",
    "row.getOwner"
  ],
  "stateWrites": [
    "mArray append",
    "row.lock"
  ],
  "resultAndCompletion": "Returns NS_OK after storing and locking row.",
  "errors": "Locked array or row from a different array returns NS_ERROR_UNEXPECTED.",
  "ownership": "Array gains strong row reference before row releases owner references.",
  "cleanup": "Row lock breaks reverse ownership.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_not_right_owning_array",
      "lineRange": [
        784,
        797
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    },
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_bind_params_already_locked",
      "lineRange": [
        734,
        747
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## BindingParamsArray::GetLength at 67 to 70

Evidence: `storage/mozStorageBindingParamsArray.cpp:67-70` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "5af22e6d0d02bd5da5307a6ea04810b413a97073ae06e1cb99d2eae76ae20522",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageBindingParamsArray.cpp",
  "symbol": "BindingParamsArray::GetLength",
  "lineRange": [
    67,
    70
  ],
  "sourceSHA256": "c793749ecafbe1dc6c4c5e22a3eac30939de40ab7deb6f6eba82a00ea4779f32",
  "bodySHA256": "d649f90c0948ced58953440b99bca862b0bd8eac762d1f8a42c8cdf6462192b4",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Script-visible array.length exposes stored row count.",
  "stateReads": [
    "mArray length"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Writes exact stored row count and returns NS_OK.",
  "errors": "No local guard/error.",
  "ownership": "Does not transfer rows.",
  "cleanup": "No cleanup.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_bind_multiple_rows_by_name",
      "lineRange": [
        593,
        617
      ],
      "linkClass": "direct",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## Validation and limits

Source revisions and ranges are pinned. The analysis agent read the implementation and recorded scoped callers and assertions. Independent peer checks cover a subset and retain corrections; other sections remain provisional. A direct test link is an assertion relationship, not an observed test pass. Controlled probes and product results retain their own environment limits. Imported or generated implementations, unsupported branches, dynamic calls and native platform behavior require the stated follow-up evidence.

Related focused notes from the same analysis (not independent supporting sources):

- [Gecko storage locks binding rows and arrays while checking their actual owners](2b758461-1505-40aa-9480-aff90d8ec608.md)
