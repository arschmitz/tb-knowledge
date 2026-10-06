<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.222Z","paths":["mailnews/base/public/nsIMsgPluggableStore.idl","mailnews/local/src/nsMsgBrkMBoxStore.cpp"],"source":{"reference":"https://phabricator.services.mozilla.com/D207101","status":"supported","publicationKey":"4e140e0a694af16193e426c3ffd8433833f1bf9e8dc2564e2491dc585cd660b2"}} -->
# The accepted store callback name is onRetentionQuery

D207101 discussed names for the keep-or-discard callback. A reviewer suggested getShouldKeepMessage; the author preferred onRetentionQuery because the callback is a query during store compaction, and that name landed. Keep the exact onRetentionQuery API name when extending this listener. This decision is scoped to this API; it does not establish a general rule against get-prefixed methods.

Scope: Folder compaction naming.

Paths:

- `mailnews/base/public/nsIMsgPluggableStore.idl`
- `mailnews/local/src/nsMsgBrkMBoxStore.cpp`

## Evidence

[Shared lesson record](../records/91863b6f751814308770d545828db453c7432813984bacfcc9577228e3c1b707.json).

- https://phabricator.services.mozilla.com/D207101
- https://github.com/thunderbird/thunderbird-desktop/commit/f7b619bbf4c05af790095adc8c6dba0b8a86848c
- https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6

Source record: `a62a1b895df2f1ac072193060d4d43ac00d7afd3148d2d655f38c742ec9ca28a`

~~~
.onRetentionQuery() - to ask if message should be kept or not.
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `8caf61413f4a880cfb3c8cea2d0cbbc51e7092ed72739acc7a469863239980ed`.
