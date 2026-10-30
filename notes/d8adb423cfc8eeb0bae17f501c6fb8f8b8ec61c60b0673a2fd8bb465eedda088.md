<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T04:25:56.348Z","paths":["mailnews/base/src/nsMsgI18N.cpp"],"source":{"reference":"knowledge-record:d8adb423cfc8eeb0bae17f501c6fb8f8b8ec61c60b0673a2fd8bb465eedda088","recordId":"d8adb423cfc8eeb0bae17f501c6fb8f8b8ec61c60b0673a2fd8bb465eedda088","status":"supported","publicationKey":"075b4056527263db448f97192e24a72490fc29a841b4b7c882a67bd4fbe0e325"}} -->
# Modified UTF-7 conversion validates reported output and positive input progress

Each conversion call starts with a 100-byte output allowance, rejects a reported output length outside 0–100 and rejects consumed input at or below zero before append and pointer advance. Finish output has the same length guard. Converter return statuses and consumed <= remaining input are not explicitly checked. Failure may leave earlier valid chunks in the destination. The round-trip caller ignores the nsresult and compares strings. These are precise source limits, not a complete converter-safety or crash-cure claim; no failure injection or native run occurred.

Scope: MailNews modified UTF-7 wrapper bounds.

## Evidence

[Lesson record](../records/d8adb423cfc8eeb0bae17f501c6fb8f8b8ec61c60b0673a2fd8bb465eedda088.json).

- [Supporting record](../records/6ec841ac356291b3fb4f02619c2d6db59947124164ad59e2290eda828608ce0d.json)
- [Supporting record](../records/a28b2b6f0da9f6089c380f6c0886708bdb8c92463987f07b3cbd279e6f35010f.json)
- [Supporting record](../records/ae4baaeefdaeedd4620d5ac8094c5fc247ddbdf5ca3566b34772cbcbbe686968.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
