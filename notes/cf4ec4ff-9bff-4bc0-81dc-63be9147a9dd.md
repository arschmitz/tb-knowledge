<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T15:44:20.425678+00:00","paths":["calendar/providers/storage/CalStorageModelBase.sys.mjs"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"ingestion-pilot-20261013T145636Z","language":"JavaScript","fileRole":"production","component":"calendar","publicationKey":"pilot-body-contract-map:cf4ec4ff-9bff-4bc0-81dc-63be9147a9dd","revisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"verification":"Source bodies and scoped callers/tests checked by analysis agent; independent audit is separate and sampled. Derived map sections are not another independent evidence source."}} -->
# calendar/providers/storage/CalStorageModelBase.sys.mjs source body contracts and relationship limits

These sections explain source bodies. They retain conditions, state, results, ownership, tests and unresolved relationships from the focused body analysis. This map restates the same analysis as the focused notes; it is not another independent confirmation. Contract IDs identify sections, not knowledge JSON record filenames. Full component behavior and passing tests are not certified.

## CalStorageModelBase.constructor at 34 to 38

Evidence: `calendar/providers/storage/CalStorageModelBase.sys.mjs:34-38` at `87d0159c7149a43253964c2cb6917939557dc799`.

```json
{
  "id": "3bd027f0f2b72169d0cb4deecfbdd510d51f295660f7bc0dab9206fbeaeee5a9",
  "repository": "thunderbird",
  "revision": "87d0159c7149a43253964c2cb6917939557dc799",
  "pairedRevisions": {
    "thunderbird": "87d0159c7149a43253964c2cb6917939557dc799",
    "firefox": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"
  },
  "path": "calendar/providers/storage/CalStorageModelBase.sys.mjs",
  "symbol": "CalStorageModelBase.constructor",
  "lineRange": [
    34,
    38
  ],
  "sourceSHA256": "6ab595a60113f80a4ca5600fbfbe81ec2d3a1baae47ee63d097ca9ff5c8c7c0b",
  "bodySHA256": "9a6a22668bae4b3d091393ce38b8a261c620b6a72d7bb8cd3e38da13e923cba2",
  "language": "JavaScript",
  "runtime": "privileged Calendar module",
  "role": "production",
  "analysisOrigin": "reuse",
  "fullLocalBodyRead": true,
  "triggerOrCaller": "Factory creates concrete model.",
  "stateReads": [
    "constructor args"
  ],
  "stateWrites": [
    "db",
    "statements",
    "calendar"
  ],
  "resultAndCompletion": "Constructs shared model ownership.",
  "errors": "No local failure.",
  "ownership": "Model retains wrapper/statement collection/calendar; Calendar retains models.",
  "cleanup": "Native release remains separate from JavaScript collection.",
  "cancellation": "No cancellation operation in this body.",
  "tests": [],
  "unknowns": [
    "All callers and all native platform/error paths are not certified by this local body contract."
  ],
  "support": "directly-observed-source-body",
  "noteId": "08a6d007-3e6d-4753-ba75-4c2bee487201",
  "reviewStatus": "draft-contract-awaiting-parent-independent-check"
}
```

## Validation and limits

Source revisions and ranges are pinned. The analysis agent read the implementation and recorded scoped callers and assertions. Independent peer checks cover a subset and retain corrections; other sections remain provisional. A direct test link is an assertion relationship, not an observed test pass. Controlled probes and product results retain their own environment limits. Imported or generated implementations, unsupported branches, dynamic calls and native platform behavior require the stated follow-up evidence.

Related focused notes from the same analysis (not independent supporting sources):

- [Storage calendar wipe clears item maps and deliberately retains recurring offline flag maps](71f2d1c6-20f7-4df4-b905-effba4c6e3bc.md)
- [Storage provider registration packages concrete model owners and its localized name](08a6d007-3e6d-4753-ba75-4c2bee487201.md)
