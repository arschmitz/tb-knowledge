<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T17:48:48.226Z","paths":["mail/base/content/msgHdrView.js","mail/test/browser/message-header/browser_messageHeader.js"],"source":{"reference":"knowledge-record:b66a8b4a0ffef81560cb6762fff31aea8865b0e9af4f77acc4cbca99c2fbd8c2","recordId":"b66a8b4a0ffef81560cb6762fff31aea8865b0e9af4f77acc4cbca99c2fbd8c2","status":"supported","publicationKey":"08c91527984e3955cf64e708c819cd0e7bff585b4f58d11810b4d4cd8dc58019"}} -->
# List management popup preserves an already encoded mailto value

List-ID popup extraction prefers a mailto alternative and strips angle/whitespace delimiters without applying encodeURI again. The direct regression assertion preserves the subject percent20 sequence in the exact menu value. Activation consumes that value for composeEmailTo or openUILink. This is encoded-URI preservation in this parser/menu path, not end-to-end unsubscribe validation or a general header trust rule. No runtime test.

Scope: message-header-list-management.

## Evidence

[Lesson record](../records/b66a8b4a0ffef81560cb6762fff31aea8865b0e9af4f77acc4cbca99c2fbd8c2.json).

- [Supporting record](../records/697294616579179554a46459dcf89d2d21200fc4acd6c1ebf6ebbb277475a0d8.json)
- [Supporting record](../records/a9b86351c9444942a0c06d8b0e8943c22424952addfee4cc1b2185b96a98199b.json)
- [Supporting record](../records/c596a93a46aaaa66f787f1b390cc1856b4e159015eb6e443031ec8bbed8d259c.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
