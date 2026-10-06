<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.141Z","paths":["mailnews/imap/public/ImapTypes.idl"],"source":{"reference":"https://phabricator.services.mozilla.com/D291677","status":"provisional","publicationKey":"837e322f479bbfd9d5a0e06a31fef2ee2cd6583fe6e530c271c74506ff5545f3"}} -->
# Keep IMAP UIDs distinct from local message keys

An IMAP UID names a server message while nsMsgKey names a local database record. Pass ImapUid through IMAP interfaces to show that distinction, even though XPCOM currently cannot enforce a strong type against every numeric cast.

Scope: imap.

Paths:

- `mailnews/imap/public/ImapTypes.idl`

## Evidence

[Shared lesson record](../records/5d21a224b65b9cc97b70bfef4ecc74ac9cedd872556a7e8289b47af6a3a3b74d.json).

- https://phabricator.services.mozilla.com/D291677
- https://github.com/thunderbird/thunderbird-desktop/commit/00ac5e1813879d6c97ed230125430490c678419e

Source record: `9bb7ed3e594ecd6f4043cd14ad552955ee06b3ef782197fa219808418be55872`

~~~
typedef unsigned long ImapUid
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `c8faa7dbf171ea0e5c6c22acb12372313ea10f0a996127d78806a99bddab8753`.
