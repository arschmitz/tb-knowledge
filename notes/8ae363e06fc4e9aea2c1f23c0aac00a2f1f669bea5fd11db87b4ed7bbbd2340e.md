<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T17:40:19.890Z","paths":["mail/components/accountcreation/test/browser/browser_oAuthGranularScopes.js","mailnews/base/src/OAuth2Module.sys.mjs"],"source":{"reference":"knowledge-record:8ae363e06fc4e9aea2c1f23c0aac00a2f1f669bea5fd11db87b4ed7bbbd2340e","recordId":"8ae363e06fc4e9aea2c1f23c0aac00a2f1f669bea5fd11db87b4ed7bbbd2340e","status":"supported","publicationKey":"210eea67a682768a80517ce4b8f733bb0965ff034ff3acc076f7c51aa2ed56f9"}} -->
# Granular OAuth tests separate verifier settlement, telemetry and token cleanup

The original test handles the verifier promise first, then waits for any telemetry before asserting its expected event. Its expected-failure path separately polls for a saved refresh token and clears logins, but ignores the polling rejection; that is not an assertion of completed persistence. The current OAuth success path awaits token storage, while the later accepted browser test retries whole flows and explicitly requires succeeded telemetry. Preserve these stages and original-versus-later test phases; no intermittent cure or imported observer timing is established by source alone.

Scope: Account creation OAuth browser test ordering.

## Evidence

[Lesson record](../records/8ae363e06fc4e9aea2c1f23c0aac00a2f1f669bea5fd11db87b4ed7bbbd2340e.json).

- [Supporting record](../records/0a881bde6cbf80be5bfe68b7943aca5a32f13c1cc0951ff6cc1fc5e13686a0d9.json)
- [Supporting record](../records/494da00a03379b86dbd3bfefde07529f766e5c0e3db254c5b65f3bd4551f0b6d.json)
- [Supporting record](../records/709645ec3dfc1f7aa82649fcb67be5a111b6e3cd863f63e962f94dd42392b47a.json)
- [Supporting record](../records/c8a2d8554f0f897375b76f485e31b691cc12b49221eeee100a1164e9995bea4b.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
