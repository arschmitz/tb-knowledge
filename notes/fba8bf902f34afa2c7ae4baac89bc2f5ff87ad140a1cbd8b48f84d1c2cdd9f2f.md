<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T00:58:43.672Z","paths":["mail/components/preferences/test/browser/head.js"],"source":{"reference":"knowledge-record:fba8bf902f34afa2c7ae4baac89bc2f5ff87ad140a1cbd8b48f84d1c2cdd9f2f","recordId":"fba8bf902f34afa2c7ae4baac89bc2f5ff87ad140a1cbd8b48f84d1c2cdd9f2f","status":"provisional","publicationKey":"2a291e853243cc21306e59a59c3fe0a735066dd7f9e4fbe0246e185be7dca619"}} -->
# Keep async callback completion in the helper documentation

D214683 explicitly requests that promiseSubDialog docs state the callback may be async and its returned promise is awaited. Current JSDoc says possibly async, open-and-focused callback, window argument; implementation awaits callback before preparing close. Describe completion ordering in docs instead of merely calling something a callback. This is a supported helper contract beyond formatting.

Scope: mail/components/preferences.

## Evidence

[Lesson record](../records/fba8bf902f34afa2c7ae4baac89bc2f5ff87ad140a1cbd8b48f84d1c2cdd9f2f.json).

- [Supporting record](../records/16273e44f014efdae241a9b3ce8c1a44b19955acf7456b83881f84b9202f1ece.json)
- [Supporting record](../records/1d91974731fb1415d4c3fe8ee0197865461d7dd4af757accb635d45ba231350f.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
