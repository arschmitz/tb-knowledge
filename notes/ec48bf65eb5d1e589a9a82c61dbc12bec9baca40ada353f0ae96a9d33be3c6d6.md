<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T21:33:38.739Z","paths":["mail/test/browser/composition/browser_sandwichedImageForward.js","mail/test/browser/composition/data/text-sandwiched-inline-image.eml"],"source":{"reference":"knowledge-record:ec48bf65eb5d1e589a9a82c61dbc12bec9baca40ada353f0ae96a9d33be3c6d6","recordId":"ec48bf65eb5d1e589a9a82c61dbc12bec9baca40ada353f0ae96a9d33be3c6d6","status":"supported","publicationKey":"ac2906345025251262b7ae46447cdc498218615a3b88e7ff7889e525df44903e"}} -->
# The sandwiched-image forward test checks text and attachment metadata, not image equivalence

The fixture places an inline PNG between two unnamed us-ascii text/plain parts. The browser task directly checks that both text fragments are quoted and that the one attachment is pixel.png, image/png and nonempty. It does not compare image contents, visual position or cover mixed charsets/named text/HTML in this case. The helper and assertions were inspected; no browser or compose run occurred.

Scope: MIME inline-forward browser test limits.

## Evidence

[Lesson record](../records/ec48bf65eb5d1e589a9a82c61dbc12bec9baca40ada353f0ae96a9d33be3c6d6.json).

- [Supporting record](../records/4d149d230abb955b6f428a62eeb2d65a2f3920742318970f7d46f28709428fab.json)
- [Supporting record](../records/58d552bb321477b5d4c663377707ef5ff08b3604b1d98d043c44422dabb38a07.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
