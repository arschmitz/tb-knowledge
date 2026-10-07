<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T04:44:29.474Z","paths":["chat/protocols/matrix/matrixAccount.sys.mjs","chat/protocols/matrix/matrixTextForEvent.sys.mjs"],"source":{"reference":"knowledge-record:bbc1284d3cedf07ffff42f79b7dbbe02f095e896262c1d0da4dbcdd1e62a2aff","recordId":"bbc1284d3cedf07ffff42f79b7dbbe02f095e896262c1d0da4dbcdd1e62a2aff","status":"supported","publicationKey":"9fbf532ccdb6d2b4cac201fcae576d10f37de27c8fc2381200e6219dd2b7559b"}} -->
# Use the Matrix membership enum at the SDK boundary while preserving event keys

The owned 1276 code replaces membership string comparisons with MatrixSDK.KnownMembership values in room lifecycle and localized event rendering. The MATRIX_EVENT_HANDLERS handlers remain named ban, invite, join and leave because those keys select protocol event cases. A scoped source pattern is to use the SDK enum for comparisons without mechanically changing wire/event-map keys or Fluent IDs. This is specific to this integration, not an all-enums project rule. This is source and test inspection only. Full Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility check ran.

Scope: chat/protocols/matrix.

## Evidence

[Lesson record](../records/bbc1284d3cedf07ffff42f79b7dbbe02f095e896262c1d0da4dbcdd1e62a2aff.json).

- [Supporting record](../records/0d7ba03a254666c2c3b098635c1104d3579f61983e2d377344c99d76ec3577e5.json)
- [Supporting record](../records/568fa0225e887a1db85d9f85966dc8bfa506acc0ae230a9a20e2c936df271e40.json)
- [Supporting record](../records/679d617376efc1689ba98588e53e468909713d1f760915e6de882487a629340d.json)
- [Supporting record](../records/6892ae0a7e608d450e145acf3900e5bda4859897bca48c9948bbd4e189269c87.json)
- [Supporting record](../records/75177bfdd0729c98b1c07e0443a330a0777f0eb8dcea97c80dbef7bf9f03541c.json)
- [Supporting record](../records/82c879b9b03aaeac2fb7a57eda155d7aa98d6b38b3210fbc38a7d5056af5b371.json)
- [Supporting record](../records/a9730efbb60e7774467fb070f7b89cd6b750256b69c789456368fa6f6c9127b5.json)
- [Supporting record](../records/ef6b085f2bfed286b98faa60d2237bbd8a84aa31374375bcf2469fa214c780ee.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
