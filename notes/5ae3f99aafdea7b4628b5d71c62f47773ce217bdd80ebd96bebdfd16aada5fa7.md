<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T14:15:15.412Z","paths":["mailnews/base/src/FolderLookupService.cpp","mailnews/base/src/FolderLookupService.h","mailnews/base/src/VirtualFolderWrapper.sys.mjs"],"source":{"reference":"knowledge-record:5ae3f99aafdea7b4628b5d71c62f47773ce217bdd80ebd96bebdfd16aada5fa7","recordId":"5ae3f99aafdea7b4628b5d71c62f47773ce217bdd80ebd96bebdfd16aada5fa7","status":"supported","publicationKey":"1e8568095f539d7949c077ab5cbdb58f3710b5ad8274e0c78488a97aad29e9a6"}} -->
# Native folder lookup separates empty results from creation errors

The 6609eec6c046cf90ae524534c163923fae49c12d migration clears folder outputs before successful empty lookup paths and uses nsCOMPtr::forget to transfer returned ownership. GetExisting returns nsCOMPtr or null directly. Its header still describes invalid-argument failure although the direct-return helper has no output argument. Missing URI schemes and factory failures are errors in native creation. VirtualFolderWrapper trims and removes empty stored scopes, catches each lookup exception, then filters missing results. Its adapter remains at the fixed revision. The native validity helper reads the root after the parent even when a parent is set; the deleted JavaScript helper short-circuits root access in that case. The Panorama root path returns after database-backed initialization, and IMAP trash lookup uses a separate output owner so its input folder remains available for the URI helper fallback. These are scoped source contracts, not proof of full native/JavaScript equivalence or a performance gain. Added slash and percent tests assert URI strings and lack messages. No test ran.

Scope: Folder lookup native optional result and virtual-folder adapter.

## Evidence

[Lesson record](../records/5ae3f99aafdea7b4628b5d71c62f47773ce217bdd80ebd96bebdfd16aada5fa7.json).

- [Supporting record](../records/13fac631438e43fcab69ca9be7ad185632f3a2064a96cb1e2b00e1aa021f964b.json)
- [Supporting record](../records/1919049d22dbe1efb8609eca1313119b9856d396b12363d874b3d0bfb027fced.json)
- [Supporting record](../records/1b422e6730b937ce1895ad3cbc2f3a47dcd00f316ca6b1b330897f54322215c5.json)
- [Supporting record](../records/389676f4cf43b483d75ba03bcae2f7b640df5c5ed4044b2454d6dfb57aff6465.json)
- [Supporting record](../records/66de428ddfe968f0505680fd0258e8688f2272a70d741ce9ebcbd17a6acbf042.json)
- [Supporting record](../records/a1ba979dc94856e74c7350e9a9f0ad3c974e1f495adfa7bcfe04704aa44e56ff.json)
- [Supporting record](../records/a40e979bd73085e64f274bb83a277a97b707caddd55dd97e565898aa66e81b21.json)
- [Supporting record](../records/cff107ddb7ccd6a717134e29086924c7e6a8d4dae446bb924c6bf92474b6dc8d.json)
- [Supporting record](../records/e16aa66d76c8eddfa62b21de0fa9491f9c98b4ea7acac501641d28e82426d35e.json)
- [Supporting record](../records/f12cd81d24e62c7d835125770db4965ada942f017bb65a47909dc20e060ff3ab.json)
- [Supporting record](../records/f7964797b286dd930677f48d2bbb1f59545b0cdedd9e1c2d0455bfc34759a5c0.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
