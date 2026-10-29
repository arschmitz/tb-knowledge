<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T09:17:13.148Z","paths":["mailnews/protocols/ews/src/EwsFolder.cpp","mailnews/protocols/exchange/src/ExchangeFolder.cpp","mailnews/protocols/exchange/src/ExchangeListeners.cpp","mailnews/protocols/exchange/test/unit/test_folder_operations.js"],"source":{"reference":"knowledge-record:fe4c1e17dbf26eb35be3292f0be2bd6eedb6d12a07ec7fed9a31d8b78cbddf51","recordId":"fe4c1e17dbf26eb35be3292f0be2bd6eedb6d12a07ec7fed9a31d8b78cbddf51","status":"supported","publicationKey":"a1a809da1eb00549c1a18b2f29bd91ac084b10ad7a8891698b81cbe0e56abd18"}} -->
# Trash failure notification tolerates an absent URL listener

EmptyTrash accepts an optional URL listener. The failure callback now checks it before forwarding the operation status to OnStopRunningUrl, and returns NS_OK when no notification target exists. That return describes handling the callback, not a successful remote deletion. Remote success still precedes local deletion and its stop notification. The current null-listener test covers success, not forced failure; no crash or callback run was reproduced.

Scope: Exchange trash completion listener.

## Evidence

[Lesson record](../records/fe4c1e17dbf26eb35be3292f0be2bd6eedb6d12a07ec7fed9a31d8b78cbddf51.json).

- [Supporting record](../records/33f88ccc6075a32af645478c8ad797ee3b203d0fdd64462e8dd3152dd621c639.json)
- [Supporting record](../records/55400847cccfbfd10c9903ca2df8d701195303c607071d3fedcede1f018c56f3.json)
- [Supporting record](../records/9d551f2d33a9843d4f3d2f7a0daabb12cdf4e4272b9100e537679b1bc5edf042.json)
- [Supporting record](../records/ae673bcda2f3eb9f60e27de125ff2545c85d071810c3d1d20e59c5985d62c984.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
