<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T07:17:40.822Z","paths":["mailnews/base/src/nsMsgDBView.cpp"],"source":{"reference":"knowledge-record:ee485c2dedd0e85cf49c7d673cfcdafa9e48573e2d2b623adde091c9ed0f0f4b","recordId":"ee485c2dedd0e85cf49c7d673cfcdafa9e48573e2d2b623adde091c9ed0f0f4b","status":"supported","publicationKey":"6ac1012ad4fd5a2cf85d2f488d3a9bf3b916014fe11d21d08b526d6e2dbb5ee2"}} -->
# The date connector cache uses pointer absence rather than empty text as its lazy sentinel

The StaticAutoPtr phase resets sConnectorPattern to nullptr and allocates its locale pattern only when the pointer is absent. It copies the stored string before substituting weekday and time placeholders. A present empty string no longer triggers the old IsEmpty retry condition. Keep pointer presence, stored text and explicit reinitialization distinct; this source inspection does not prove locale formatting success, teardown or runtime cache behavior.

Scope: db-view-date-connector-pointer-cache.

## Evidence

[Lesson record](../records/ee485c2dedd0e85cf49c7d673cfcdafa9e48573e2d2b623adde091c9ed0f0f4b.json).

- [Supporting record](../records/71c5c3b754f0a5b3840e81af0af48ee46fb993898ccf061ca8076462ae2a850c.json)
- [Supporting record](../records/a86b70da90d02f2d824151c99834f2b4d2db000ef7f6e196444d7e4bf2c3d38a.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
