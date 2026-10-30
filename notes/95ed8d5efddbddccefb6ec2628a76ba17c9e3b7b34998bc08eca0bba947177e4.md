<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T13:22:06.481Z","paths":["mailnews/protocols/exchange/src/ExchangeService.cpp","mailnews/protocols/exchange/test/unit/test_exchange_service.js"],"source":{"reference":"knowledge-record:95ed8d5efddbddccefb6ec2628a76ba17c9e3b7b34998bc08eca0bba947177e4","recordId":"95ed8d5efddbddccefb6ec2628a76ba17c9e3b7b34998bc08eca0bba947177e4","status":"supported","publicationKey":"b5d6299279351c0e6017004be8e62edf25bb75d0edebe63b5ba87d38074d10a2"}} -->
# Exchange URL scheme mapping and whole-URI identity are separate contracts

The original mapping patch accepts both message and x-moz channel schemes for EWS and Graph, while still running the path/ref transformation. Its four assertions check schemes only. Fixed accepted GetUrlForUri instead forwards an existing x-moz URI as-is before the message-URI rewrite. Scheme coverage does not establish full path/query/ref identity or actual message loading.

Scope: Thunderbird Exchange message URL conversion.

## Evidence

[Lesson record](../records/95ed8d5efddbddccefb6ec2628a76ba17c9e3b7b34998bc08eca0bba947177e4.json).

- [Supporting record](../records/42a3bf0ea6959e96f94589d3ae576356fab09128fefda132a97d16165698e2eb.json)
- [Supporting record](../records/54bd14b5562dbc3f99454f2576e99b96f0f6a8a036806c7b3c94f1bd547e83a0.json)
- [Supporting record](../records/d0960baf1f62f17eb959587ce2dc36edcb9777c5b6565b69aec8052c8ce16faa.json)
- [Supporting record](../records/ef9e788f97839585d7b2681b8a6f0c7c9ee537e5ebe32a27c9a7a1caa1ecca11.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
