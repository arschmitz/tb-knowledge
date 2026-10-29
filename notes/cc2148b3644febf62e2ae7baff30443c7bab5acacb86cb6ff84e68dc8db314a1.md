<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T06:13:59.242Z","paths":["mailnews/base/public/nsIMsgProgress.idl","mailnews/base/src/nsMsgProgress.cpp"],"source":{"reference":"knowledge-record:cc2148b3644febf62e2ae7baff30443c7bab5acacb86cb6ff84e68dc8db314a1","recordId":"cc2148b3644febf62e2ae7baff30443c7bab5acacb86cb6ff84e68dc8db314a1","status":"supported","publicationKey":"ea2cfc4e4e332fa2f56326796298c6a6a6e3d6385839f205ed58c0a97b959009"}} -->
# The progress listener null-registration comment differs from the implementation

The registerListener documentation says a null listener produces NS_ERROR_INVALID_ARG. RegisterListener instead retains an early null guard that returns NS_OK. UnregisterListener does not share that no-op and returns NS_ERROR_INVALID_ARG when it cannot obtain a weak reference. Keep those concrete method contracts separate when reviewing callers or correcting the documentation. The mismatch is present in the owned weak-listener change and the fixed accepted source; this study does not choose or implement a behavior change.

Scope: nsIMsgProgress API documentation.

## Evidence

[Lesson record](../records/cc2148b3644febf62e2ae7baff30443c7bab5acacb86cb6ff84e68dc8db314a1.json).

- [Supporting record](../records/8f8b366bfea6d8a0d5eb886fa8962d2eb9930477e5a6210c26cdc7a6bc41e784.json)
- [Supporting record](../records/bacfd47659d9a0cf929312cdbad0fb2f334d5fd894c506dfb45ab7eaca2bc227.json)
- [Supporting record](../records/f722eda2f87dbd625941c47cd92a91f8a8803820d2980f6973b1f314dd3cb868.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
