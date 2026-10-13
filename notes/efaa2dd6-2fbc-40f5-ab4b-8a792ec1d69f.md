<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T15:44:20.416387+00:00","paths":["storage/mozStorageAsyncStatement.cpp"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"ingestion-pilot-20261013T145636Z","language":"C++","fileRole":"production","component":"storage","publicationKey":"pilot-body-contract-map:efaa2dd6-2fbc-40f5-ab4b-8a792ec1d69f","revisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"verification":"Source bodies and scoped callers/tests checked by analysis agent; independent audit is separate and sampled. Derived map sections are not another independent evidence source."}} -->
# storage/mozStorageAsyncStatement.cpp source body contracts and relationship limits

These sections explain source bodies. They retain conditions, state, results, ownership, tests and unresolved relationships from the focused body analysis. This map restates the same analysis as the focused notes; it is not another independent confirmation. Contract IDs identify sections, not knowledge JSON record filenames. Full component behavior and passing tests are not certified.

## AsyncStatement::initialize at 96 to 147

Evidence: `storage/mozStorageAsyncStatement.cpp:96-147` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "956abb54538c6b74d002866b2b61d44de59777d58dd4e45ad378d9446aed31f7",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::initialize",
  "lineRange": [
    96,
    147
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "acba9df8a67e4e5c774da20605ffcfdc3fe145078e2ffd3122356d95b0b4eeb7",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Connection::CreateAsyncStatement2547-2568 constructs actual AsyncStatement and invokes initialize(this,mDBConn,aSQLStatement).",
  "stateReads": [
    "aDBConnection readiness",
    "aNativeConnection",
    "aSQLStatement"
  ],
  "stateWrites": [
    "mDBConnection",
    "mNativeConnection",
    "mSQLString"
  ],
  "resultAndCompletion": "Returns NS_OK without preparing SQL on caller thread.",
  "errors": "Debug assertions check owner/native pointer; debug LIKE check warns and does not reject.",
  "ownership": "Strong connection owner is stored; native pointer is borrowed.",
  "cleanup": "Destructor proxies release to opening target.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "linkClass": "executes",
      "evidence": "native-tests.json",
      "limits": "execute-only native test file"
    }
  ],
  "unknowns": [
    "CreateAsyncStatement receiver/guard/allocation/initialize/ownership-return body was checked after freezing; full Connection initialization, SQL parsing and platform paths remain separate scopes."
  ],
  "support": "directly-observed-source-body",
  "noteId": "24f70549-76e7-4a5b-83f3-ba882d502594",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::getParams at 149 to 179

Evidence: `storage/mozStorageAsyncStatement.cpp:149-179` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "5e0cd92aae82319c10bf1f8802de6b8b56a4c876b52288e486d09d7f64d59825",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::getParams",
  "lineRange": [
    149,
    179
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "ed1fc7da614ef68489329c41164fbc98d9cd1293d1a083f85b350b1578dbd2fa",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "AsyncStatement BOILERPLATE_BIND_PROXIES instantiates native BindByName/BindByIndex, which call this class getParams then forward to the returned binding row.",
  "stateReads": [
    "mParamsArray",
    "array.length"
  ],
  "stateWrites": [
    "mParamsArray creation",
    "row added/unlocked",
    "array locked"
  ],
  "resultAndCompletion": "Returns borrowed first hidden binding row.",
  "errors": "Allocation or AddParams failure returns null via NS_ENSURE checks.",
  "ownership": "Hidden row stays owned by array; array by statement until transfer to StatementData.",
  "cleanup": "Array creation on later request is separate from an earlier transferred array.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_bind_js_params_helper_by_name",
      "lineRange": [
        546,
        564
      ],
      "linkClass": "possible",
      "runEvidence": "native-tests.json",
      "runEnvironment": "Thunderbird160.0a1/build20261013101249/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "Native binding proxy receiver was checked in StorageBaseStatementInternal.h210-246 plus AsyncStatement.cpp330-331. The separate AsyncStatementJSHelper::getParams getter and its helper holder body remain unreviewed."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2b758461-1505-40aa-9480-aff90d8ec608",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::~AsyncStatement at 190 to 202

Evidence: `storage/mozStorageAsyncStatement.cpp:190-202` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "f177b798bf6662be76c0e31dbcb2240268b9394af3a02fe8a55d0002a4e17c80",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::~AsyncStatement",
  "lineRange": [
    190,
    202
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "636bd901fbb9ff986a7728f8a476715499312b2b2750206a5e2af9e69f3d64ca",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Last retained statement reference is released.",
  "stateReads": [
    "mDBConnection opening target",
    "mAsyncStatement"
  ],
  "stateWrites": [
    "async native pointer cleanup",
    "mDBConnection forget on wrong target"
  ],
  "resultAndCompletion": "Destroys statement after destructorAsyncFinalize.",
  "errors": "Proxy-release status ignored in this body.",
  "ownership": "Pending StatementData/finalizer references prevent early destruction.",
  "cleanup": "Proxies connection release to opening target when needed.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "Garbage-collection timing and failed proxy dispatch were not run."
  ],
  "support": "directly-observed-source-body",
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::getOwner at 224 to 224

Evidence: `storage/mozStorageAsyncStatement.cpp:224-224` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "d0cb1e882918a1dd10b13eb89793b89878b4d27d5dc61f54791ed5412919db59",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::getOwner",
  "lineRange": [
    224,
    224
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "92f54555fe29a47a6009ea676d671fe081df0784e1f5396a4abc6bd1a41463ea",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Connection::ExecuteAsync checks statement owner identity.",
  "stateReads": [
    "mDBConnection"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Returns borrowed Connection pointer.",
  "errors": "No local error.",
  "ownership": "Retained connection remains owned by statement.",
  "cleanup": "No cleanup.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "24f70549-76e7-4a5b-83f3-ba882d502594",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::getAsyncStatement at 226 to 253

Evidence: `storage/mozStorageAsyncStatement.cpp:226-253` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "11b05b9e9f2025f4d023e1d358296498b29e4e97340e3e89744f1e2df0de6a0a",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::getAsyncStatement",
  "lineRange": [
    226,
    253
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "062957d1b0610e85a031ac617866969c0b7c69fb9a3c9e487cc120ac885603cb",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "StatementData::getSqliteStatement requests native statement on helper thread.",
  "stateReads": [
    "mAsyncStatement",
    "mSQLString",
    "mNativeConnection"
  ],
  "stateWrites": [
    "mAsyncStatement on first successful prepare"
  ],
  "resultAndCompletion": "Outputs cached prepared pointer and returns SQLITE_OK; failure outputs null and returns SQLite code.",
  "errors": "Preparation failure logs code/SQL; debug assertion prohibits opening target.",
  "ownership": "Native pointer belongs to statement owner.",
  "cleanup": "Finalize/destructor clears or finalizes pointer.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "Full Connection::prepareStatement and SQLite parser internals are separate scopes."
  ],
  "support": "directly-observed-source-body",
  "noteId": "24f70549-76e7-4a5b-83f3-ba882d502594",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::getAsynchronousStatementData at 255 to 262

Evidence: `storage/mozStorageAsyncStatement.cpp:255-262` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "545760d1e4e9bb7e13e6ff5661f97911f2eb0e9bf893a89e68482584351a5b36",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::getAsynchronousStatementData",
  "lineRange": [
    255,
    262
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "c06d23ef0d9d6b0e9d1b19f37299b226db03e02e0df1077dd3ad633eb4e87727",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Connection or statement ExecuteAsync builds request data.",
  "stateReads": [
    "mFinalized",
    "mParamsArray"
  ],
  "stateWrites": [
    "mParamsArray forgotten"
  ],
  "resultAndCompletion": "Returns StatementData with null lazy native pointer and transferred array.",
  "errors": "Finalized statement returns NS_ERROR_UNEXPECTED.",
  "ownership": "StatementData strongly retains this owner and submitted array.",
  "cleanup": "Executor resets and clears data.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "24f70549-76e7-4a5b-83f3-ba882d502594",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::Finalize at 286 to 300

Evidence: `storage/mozStorageAsyncStatement.cpp:286-300` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "28da6b3f5c1080faa40eb27ec954f601ac5b87cd0c205274fdd8d6e5927d4f0c",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::Finalize",
  "lineRange": [
    286,
    300
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "6f4c662d9553b23da28575db8a823339143b7d11cc177e0fa949f26f492f9bde",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "extended",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Calendar statement collection calls finalize during teardown.",
  "stateReads": [
    "mFinalized",
    "mStatementParamsHolder"
  ],
  "stateWrites": [
    "mFinalized=true",
    "parameter holder=null"
  ],
  "resultAndCompletion": "Returns NS_OK, including repeated finalize; schedules native cleanup.",
  "errors": "No cleanup-dispatch error propagated by called asyncFinalize.",
  "ownership": "Queued finalizer retains owner; parameter holder reference removed.",
  "cleanup": "Clears JavaScript parameter holder and schedules async native finalization.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_finalized_statement_does_not_crash",
      "lineRange": [
        463,
        474
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
  "noteId": "b6ae8c6e-201f-4af4-ae71-d08024d0ab33",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## AsyncStatement::BindParameters at 303 to 315

Evidence: `storage/mozStorageAsyncStatement.cpp:303-315` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "8440537b0ca3eb2d4fc2af177641172d30460d15b209130ce5c51c5c6d9aee4b",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::BindParameters",
  "lineRange": [
    303,
    315
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "c757af438e6af8e04a88135ea6c04a97ce55ee62d0f8a1ba4d0d033f5648e500",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Calendar item model binds complete array before executing batch.",
  "stateReads": [
    "mFinalized",
    "array.getOwner",
    "array.length"
  ],
  "stateWrites": [
    "mParamsArray",
    "array.lock"
  ],
  "resultAndCompletion": "Returns NS_OK once array is stored and locked.",
  "errors": "Finalized/wrong-owner/empty array returns NS_ERROR_UNEXPECTED.",
  "ownership": "Statement retains array before array clears back reference.",
  "cleanup": "Later getAsynchronousStatementData transfers array.",
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
    },
    {
      "repository": "firefox",
      "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
      "path": "storage/test/unit/test_statement_executeAsync.js",
      "symbol": "test_bind_empty_array",
      "lineRange": [
        817,
        828
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

## AsyncStatement::GetState at 318 to 325

Evidence: `storage/mozStorageAsyncStatement.cpp:318-325` at `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`.

```json
{
  "id": "572d476edff29aa56dc4d673f8906f6a94ff7c88148adce4530dcc0f49c8e0e8",
  "repository": "firefox",
  "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "storage/mozStorageAsyncStatement.cpp",
  "symbol": "AsyncStatement::GetState",
  "lineRange": [
    318,
    325
  ],
  "sourceSHA256": "4d5d6650b70d09c70b04295ddd15f11a88b42f27e102f82e717252e22708a778",
  "bodySHA256": "c4933a139da6ae17a003d904fd199bd73f1c89ad2c0f03f8d1425bfe94bb9ef8",
  "language": "C++",
  "runtime": "native storage",
  "role": "production",
  "analysisOrigin": "new",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Consumers inspect statement.state before using params.",
  "stateReads": [
    "mFinalized"
  ],
  "stateWrites": [],
  "resultAndCompletion": "Outputs INVALID when finalized, READY otherwise; returns NS_OK.",
  "errors": "No local failure.",
  "ownership": "No ownership change.",
  "cleanup": "No cleanup.",
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

## Validation and limits

Source revisions and ranges are pinned. The analysis agent read the implementation and recorded scoped callers and assertions. Independent peer checks cover a subset and retain corrections; other sections remain provisional. A direct test link is an assertion relationship, not an observed test pass. Controlled probes and product results retain their own environment limits. Imported or generated implementations, unsupported branches, dynamic calls and native platform behavior require the stated follow-up evidence.

Related focused notes from the same analysis (not independent supporting sources):

- [Gecko storage locks binding rows and arrays while checking their actual owners](2b758461-1505-40aa-9480-aff90d8ec608.md)
- [Gecko asynchronous execution takes each bound parameter array and retains its statement owner](24f70549-76e7-4a5b-83f3-ba882d502594.md)
- [Gecko statement finalization shares cleanup with the asynchronous connection close path](b6ae8c6e-201f-4af4-ae71-d08024d0ab33.md)
