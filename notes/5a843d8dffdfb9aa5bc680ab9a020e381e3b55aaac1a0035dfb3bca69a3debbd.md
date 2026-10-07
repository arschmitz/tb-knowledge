<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T02:49:37.270Z","paths":["mailnews/base/test/gtest/TestMsgMboxWrite.cpp"],"source":{"reference":"knowledge-record:5a843d8dffdfb9aa5bc680ab9a020e381e3b55aaac1a0035dfb3bca69a3debbd","recordId":"5a843d8dffdfb9aa5bc680ab9a020e381e3b55aaac1a0035dfb3bca69a3debbd","status":"supported","publicationKey":"76a8657fafeb82d67ee287fa233ae4481f9a50ec88e29902560a0305e7d09eb4"}} -->
# Know what a normalized storage test stops asserting

839 strips sender/time contents from both actual and expected From lines in the basic mbox write test. This avoids runtime timestamp differences while retaining separator and body comparisons. It also means that test does not assert the exact new envelope metadata. Use a dedicated metadata assertion for metadata behavior; do not treat a normalized structural comparison as proof of all serialized fields.

Scope: Mbox writer test scope.

## Evidence

[Lesson record](../records/5a843d8dffdfb9aa5bc680ab9a020e381e3b55aaac1a0035dfb3bca69a3debbd.json).

- [Supporting record](../records/2cce1668ed6d0f25fbc70da8cf840baac6ab1a4aed1304fb69f3070df816a112.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
