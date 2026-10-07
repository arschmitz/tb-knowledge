<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T04:25:26.122Z","paths":["rust/ews_xpcom/src/client/change_read_status.rs"],"source":{"reference":"knowledge-record:b93edc9389c4564fbc47ffbf9ddacf44f2da8e975592fe73effda2e7740ca6ed","recordId":"b93edc9389c4564fbc47ffbf9ddacf44f2da8e975592fe73effda2e7740ca6ed","status":"supported","publicationKey":"06794dff2598914de38c2096abf173a7dff86afa1a631ff082539a11c01a8277"}} -->
# EWS conflict resolution follows the missing ChangeKey constraint

The accepted read-status operation sends change_key: None and explicitly selects AlwaysOverwrite because the source says AutoResolve requires a ChangeKey. Keep that constraint and TODO beside this choice when changing the request. It is a scoped current workaround, not a blanket instruction to overwrite remote conflicts. The relevant 2024 change and accepted source were read; no concurrent update, server conflict or review discussion was examined. Full Bugzilla and Phabricator discussion remains pending.

Scope: EWS read-status conflict policy.

## Evidence

[Lesson record](../records/b93edc9389c4564fbc47ffbf9ddacf44f2da8e975592fe73effda2e7740ca6ed.json).

- [Supporting record](../records/1ea283e8ebd201441c8eb2040f8c60f5334893dc32769f46dd9f32418b4737e0.json)
- [Supporting record](../records/253bcb3c088b68df25db54a507734879e9492b3251ebd40af9949290cd7037c0.json)
- [Supporting record](../records/46a20f3441c5ad8627d59f73f64df68179f041d4d91415fbbbda12b52808ca7e.json)
- [Supporting record](../records/7144855fda3d4d69a5cc6a1aec8630e6e0e5b64e3e7be232d33e9dc1a7fe9600.json)
- [Supporting record](../records/ea502b1248a97f6890d25443a194930fd217512c2a62333ec19ef00993e45707.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
