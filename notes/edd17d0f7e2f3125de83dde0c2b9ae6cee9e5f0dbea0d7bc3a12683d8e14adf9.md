<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T00:52:41.147Z","paths":["mail/base/content/mailWindowOverlay.js"],"source":{"reference":"knowledge-record:edd17d0f7e2f3125de83dde0c2b9ae6cee9e5f0dbea0d7bc3a12683d8e14adf9","recordId":"edd17d0f7e2f3125de83dde0c2b9ae6cee9e5f0dbea0d7bc3a12683d8e14adf9","status":"supported","publicationKey":"bf1803adc8f76f2e70eb663ed56aea194881367f373dd3973406f9a9ad408a47"}} -->
# Use model sorting capability rather than visible columns as the menu gate

goUpdateThreadPaneSortMenu reflects primarySortType/order and threaded/grouped state. It no longer disables a sort key because its column is hidden in another layout. This permits Order Received when misleading Date headers make it useful and supports cards layout without visible columns. Group By Sort still has a separate list of supported sort types. Keep sort capability separate from presentation visibility. The historical browser regression test was read; no sort-menu, keyboard or layout run was performed.

Scope: Message list model and presentation.

## Evidence

[Lesson record](../records/edd17d0f7e2f3125de83dde0c2b9ae6cee9e5f0dbea0d7bc3a12683d8e14adf9.json).

- [Supporting record](../records/2770114dec3443b50fd8db2368ab78ff3659af5f1db09f685726b5d8190f7350.json)
- [Supporting record](../records/97302618d92c8482ab8742dc63c1f5a91720192d6390efbf8325471f12223191.json)
- [Supporting record](../records/b9958950ae04dc247446e1ee753f94a0dce8ce82f9c7b593109ded8c9e23e363.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
