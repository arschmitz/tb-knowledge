<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.102Z","paths":["mailnews/imap/src/nsImapGenericParser.cpp"],"source":{"reference":"https://phabricator.services.mozilla.com/D323565","status":"provisional","publicationKey":"9b78c9eadb48b982338c13c4d2828cafbb96d2ded2fcdc17860125817838ffa8"}} -->
# Enforce IMAP tokenizer bounds in release builds

Malformed IMAP responses can pass pointers outside the tokenizer buffer. Validate offsets and paren-group state at runtime and mark a syntax error; an assertion alone does not prevent invalid pointer movement or a crash.

Scope: imap.

Paths:

- `mailnews/imap/src/nsImapGenericParser.cpp`

## Evidence

[Shared lesson record](../records/4eabcccf1cce702832777ade1eb818e3044dbfd7c685ebce320afc0dffc93939.json).

- https://phabricator.services.mozilla.com/D323565
- https://github.com/thunderbird/thunderbird-desktop/commit/facc3c3723f143b8fff0960d5ca1fed7ff29967e

Source record: `6ccd4f027576e26cdea03924ad652a4cc86db060d3f8e64183541eb4b2ba51f5`

~~~
SetSyntaxError(true, "cannot advance beyond end of fLineOfTokens")
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `7a462fdc0f7e75930820323491c5ead3bdaa118c1943147e39363c862429b444`.
