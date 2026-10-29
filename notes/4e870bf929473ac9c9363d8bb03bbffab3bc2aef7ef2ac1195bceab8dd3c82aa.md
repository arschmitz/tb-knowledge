<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T06:02:49.492Z","paths":["mailnews/base/src/nsSubscribableServer.cpp","mailnews/base/src/nsSubscribableServer.h"],"source":{"reference":"knowledge-record:4e870bf929473ac9c9363d8bb03bbffab3bc2aef7ef2ac1195bceab8dd3c82aa","recordId":"4e870bf929473ac9c9363d8bb03bbffab3bc2aef7ef2ac1195bceab8dd3c82aa","status":"supported","publicationKey":"cffab112625b9253d5e345f18bef6a67033baab05cd28ac3e4f3c1df82e2056b"}} -->
# Seven historical subscription tree callbacks reject invalid rows before lookup

The follow-up adds negative and upper-bound row checks to IsContainer, IsContainerOpen, GetParentIndex, HasNextSibling, GetLevel, ToggleOpenState and GetCellProperties. Invalid rows return NS_ERROR_INVALID_ARG before mRowMap access; ToggleOpenState also returns before mutation. This broadens the earlier name-column-only fix. The accepted class no longer implements nsITreeView, so these guards describe the historical interface rather than the current subscription UI.

Scope: subscription-tree-historical-input-bounds.

## Evidence

[Lesson record](../records/4e870bf929473ac9c9363d8bb03bbffab3bc2aef7ef2ac1195bceab8dd3c82aa.json).

- [Supporting record](../records/587ba66a8976d618973209158d1c44d63abd3c9ebc664f86432045bced8fe32f.json)
- [Supporting record](../records/89db6aca75d7115913de4b0ecabc4c8f86752ef088983a6922a7f90ccb71c8c4.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
