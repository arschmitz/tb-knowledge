<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.100Z","paths":["mailnews/imap/src/nsImapMailFolder.cpp"],"source":{"reference":"https://phabricator.services.mozilla.com/D330649","status":"provisional","publicationKey":"e9d490e3db8d0c77563b5db684b7eb385bd72905c5e5674294634db4f7e3fbf9"}} -->
# Map IMAP UIDs to database message keys before deletion

In IMAP deletion notifications, the server supplies UIDs. Convert them with MsgKeysFromUids before deleting message-store and database entries. A UID is no longer safe to use as an nsMsgKey.

Scope: imap.

Paths:

- `mailnews/imap/src/nsImapMailFolder.cpp`

## Evidence

[Shared lesson record](../records/5bea928548f298bd9a453b2419842896e41cb634de3fb739eb1cb8ba520c95ab.json).

- https://phabricator.services.mozilla.com/D330649
- https://github.com/thunderbird/thunderbird-desktop/commit/0b93f0f7a926ed94c8a0646f18b6734ec7cc0f6d

Source record: `a22537f487d7eb497a2055a3e16415fee3fd55f2d0f7f20de7ea522718f2abaf`

~~~
MsgKeysFromUids(mDatabase, uids)
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `99f0270bb632064dc19af2838e506b40b09bf4ba0ba506bbb1923ba53e976b0e`.
