<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T15:44:20.426236+00:00","paths":["calendar/providers/storage/calStorageHelpers.sys.mjs"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"ingestion-pilot-20261013T145636Z","language":"JavaScript","fileRole":"production","component":"calendar","publicationKey":"pilot-body-contract-map:f2cfe3e6-fcea-4fe1-b26a-936b7fd45b2e","revisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"verification":"Source bodies and scoped callers/tests checked by analysis agent; independent audit is separate and sampled. Derived map sections are not another independent evidence source."}} -->
# calendar/providers/storage/calStorageHelpers.sys.mjs source body contracts and relationship limits

These sections explain source bodies. They retain conditions, state, results, ownership, tests and unresolved relationships from the focused body analysis. This map restates the same analysis as the focused notes; it is not another independent confirmation. Contract IDs identify sections, not knowledge JSON record filenames. Full component behavior and passing tests are not certified.

## getTimezone at 76 to 92

Evidence: `calendar/providers/storage/calStorageHelpers.sys.mjs:76-92` at `87d0159c7149a43253964c2cb6917939557dc799`.

```json
{
  "id": "b616d8c631bb6714ef799f6d54d52babf585dc749fecee5a6734797f2b097bb3",
  "repository": "thunderbird",
  "revision": "87d0159c7149a43253964c2cb6917939557dc799",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "calendar/providers/storage/calStorageHelpers.sys.mjs",
  "symbol": "getTimezone",
  "lineRange": [
    76,
    92
  ],
  "sourceSHA256": "c5a799b1bc3913d180b4931c4a1864d152e50c2d9a29e9f353a9139b7808697d",
  "bodySHA256": "6f4c8ae5fa422fb066a95e5e94e013c02d515e11f06039da8d5ff9bc9860041a",
  "language": "JavaScript",
  "runtime": "privileged Calendar module",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "newDateTime decodes stored timezone id/definition.",
  "stateReads": [
    "foreign cache",
    "timezone text"
  ],
  "stateWrites": [
    "foreign cache new entry"
  ],
  "resultAndCompletion": "Returns timezone from full-definition cache or Calendar timezone service.",
  "errors": "Parsing/service errors not caught here.",
  "ownership": "Module cache strongly retains foreign timezone object.",
  "cleanup": "No eviction in module.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2f105ad2-5e17-4db6-85bd-b41adea42f5e",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## newDateTime at 104 to 128

Evidence: `calendar/providers/storage/calStorageHelpers.sys.mjs:104-128` at `87d0159c7149a43253964c2cb6917939557dc799`.

```json
{
  "id": "fc5eeb124d0e589f6ed5cf4b64145b01617a691d4a1c36dd0f54202722c68e2c",
  "repository": "thunderbird",
  "revision": "87d0159c7149a43253964c2cb6917939557dc799",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "calendar/providers/storage/calStorageHelpers.sys.mjs",
  "symbol": "newDateTime",
  "lineRange": [
    104,
    128
  ],
  "sourceSHA256": "c5a799b1bc3913d180b4931c4a1864d152e50c2d9a29e9f353a9139b7808697d",
  "bodySHA256": "66957470a66f7aa46054eaec6c9cafa45a30d766a091c65ef68a839656353617",
  "language": "JavaScript",
  "runtime": "privileged Calendar module",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Storage row reconstruction passes native time/timezone.",
  "stateReads": [
    "nativeTime",
    "timezone lookup"
  ],
  "stateWrites": [
    "repaired timestamp",
    "date nativeTime/timezone"
  ],
  "resultAndCompletion": "Returns date object after conversion or floating assignment.",
  "errors": "Unknown zone logs; malformed conversion may throw.",
  "ownership": "Returned date owned by caller; foreign zone additionally cached.",
  "cleanup": "No explicit release.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [
    {
      "repository": "thunderbird",
      "revision": "87d0159c7149a43253964c2cb6917939557dc799",
      "path": "calendar/test/unit/test_calStorageHelpers.js",
      "symbol": "testNewDateTimeWithIcalTimezoneDef",
      "lineRange": [
        5,
        25
      ],
      "linkClass": "direct",
      "runEvidence": "saved-storage-product-test-results.json",
      "runEnvironment": "Thunderbird159.0a1/build20261006201633/darwinarm64/nativeRevisionUnknown"
    }
  ],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "2f105ad2-5e17-4db6-85bd-b41adea42f5e",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## Validation and limits

Source revisions and ranges are pinned. The analysis agent read the implementation and recorded scoped callers and assertions. Independent peer checks cover a subset and retain corrections; other sections remain provisional. A direct test link is an assertion relationship, not an observed test pass. Controlled probes and product results retain their own environment limits. Imported or generated implementations, unsupported branches, dynamic calls and native platform behavior require the stated follow-up evidence.

Related focused notes from the same analysis (not independent supporting sources):

- [Storage dates preserve foreign timezone definitions and distinguish missing date bindings from truthy row fields](2f105ad2-5e17-4db6-85bd-b41adea42f5e.md)
