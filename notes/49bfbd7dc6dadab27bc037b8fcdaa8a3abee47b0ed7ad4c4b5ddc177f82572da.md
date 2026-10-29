<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T09:03:41.481Z","paths":["mailnews/base/src/nsMsgFolderCache.cpp"],"source":{"reference":"knowledge-record:49bfbd7dc6dadab27bc037b8fcdaa8a3abee47b0ed7ad4c4b5ddc177f82572da","recordId":"49bfbd7dc6dadab27bc037b8fcdaa8a3abee47b0ed7ad4c4b5ddc177f82572da","status":"supported","publicationKey":"d7b333637c8c61c7c34b153c2ca988d2a2c31895f7061041dc98e9746e814f0b"}} -->
# Folder cache JSON transfers occur after the rename and parse guards

The cleanup passes two local Json::Value objects as rvalues with std::move. Rename first rejects collisions, removes the old entry and updates mKey before assigning through Obj. Cache loading first rejects read, parse and root-type failures before assigning the temporary root. Both locals have no later use. The source preserves those guard and ownership boundaries; it does not prove an allocation count or speedup.

Scope: Folder cache JSON value transfer.

## Evidence

[Lesson record](../records/49bfbd7dc6dadab27bc037b8fcdaa8a3abee47b0ed7ad4c4b5ddc177f82572da.json).

- [Supporting record](../records/9980d7571af7abb4e02bd517884489bacdedb6b6160370ad71a5e8f1eb76e9bf.json)
- [Supporting record](../records/cc174d2aeeac3bf0b05ad113ce71fac76addb5a9da44e5de3d07eb608fa9ebd5.json)
- [Supporting record](../records/dca4d48de696e443aaf3264799d6ebb45336300e09c3cc08381ace7bef602dee.json)
- [Supporting record](../records/e9920f17f4019292428f30dcff913869f7c230191a1b9dcdc7d4a5006cb4143b.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
