<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:57:44.694Z","paths":["mailnews/db/panorama/public/nsILiveView.idl","mailnews/db/panorama/src/LiveView.cpp","mailnews/db/panorama/test/xpcshell/test_liveView.js"],"source":{"reference":"knowledge-record:b5b740b10e165cba5e5e4f7b7a73b1c0aa92de8ffad0ce1fa0cc0c45f5afe631","recordId":"b5b740b10e165cba5e5e4f7b7a73b1c0aa92de8ffad0ce1fa0cc0c45f5afe631","status":"supported","publicationKey":"a9bdd3b1d65af3e90b0ae3b4555b35340454ccfad342753c880c60b7a5f95ae1"}} -->
# Use the current asynchronous LiveView interface rather than its initial pagination API

The first LiveView returned synchronous counts and selectMessages(limit, offset), with zero limit bound as SQL -1. Fixed accepted nsILiveView declares Promise counts and a Promise selectMessages without those limit arguments. Current folder tests await the query. A leftover selectMessages(1, 0) call in the emoji test does not declare a current pagination contract. Preserve historical versus current interface boundaries when reusing examples. This is static source and test-code inspection. Full Bugzilla and review timeline and inline discussion remains pending. No runtime, build, lint or live accessibility validation ran.

Scope: Panorama LiveView API evolution.

## Evidence

[Lesson record](../records/b5b740b10e165cba5e5e4f7b7a73b1c0aa92de8ffad0ce1fa0cc0c45f5afe631.json).

- [Supporting record](../records/22f0ac624140bba9f825d0d4ee12983c21a05f02b814072140ecd1a1eb661289.json)
- [Supporting record](../records/3f4a07753a5cc64b9e0aea77692769da37629a253408a9d7fdefc6e8a9d99dbb.json)
- [Supporting record](../records/7a2e2eceb59ba3fde387785173943c0da9fcbd385026c3790b64de374f9487ec.json)
- [Supporting record](../records/a266bd8150c30c8f571194db87330ee5fedbe950b29f896537fad05494f0a6d0.json)
- [Supporting record](../records/b594d15bdae417cb4063fb54d98ea40665c29e5591d0b6e96bd9f67dfa9ddb1e.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
