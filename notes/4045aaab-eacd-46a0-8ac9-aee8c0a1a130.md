<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.216Z","paths":["mail/components/extensions/schemas/messageDisplay.json","mail/components/extensions/test/browser/browser_ext_messageDisplay.js","mail/components/extensions/schemas/messageDisplay.json"],"source":{"reference":"https://bugzilla.mozilla.org/show_bug.cgi?id=1898147","status":"supported","publicationKey":"15f6012a33c1fc462deb927ce77b73e4f609e6aa9cf0be3749316b7bddad82d7"}} -->
# Use the multi-message display event for Manifest V3

The extension API first exposed onMessageDisplayed for one message. A later onMessagesDisplayed event handles both one message and a multi-selection. Bug 1898147 kept the old event for Manifest V2 but removed it from Manifest V3, and retained the MV3 persistent listener test for the plural event. Current schema still has that gate. When implementing or reviewing MV3 extensions, use onMessagesDisplayed and handle a list even if the present UI path usually selects one message.

Scope: Extension APIs.

Paths:

- `mail/components/extensions/schemas/messageDisplay.json`
- `mail/components/extensions/test/browser/browser_ext_messageDisplay.js`
- `mail/components/extensions/schemas/messageDisplay.json`

## Evidence

[Shared lesson record](../records/6b4998bf3934e1afc93c0deea10ab7613677da02bc063021b792ed01b18d17d1.json).

- https://bugzilla.mozilla.org/show_bug.cgi?id=1898147
- https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6
- https://github.com/thunderbird/thunderbird-desktop/commit/76ab537da0a01e35005d507f64b86c33cce13853
- https://phabricator.services.mozilla.com/D211149

Source record: `b4ff6e9bcfaa1f6c21c5eace79f990ed9c7c57da311b74944e021267cd53059b`

~~~
"name": "onMessageDisplayed",
        "type": "function",
        "max_manifest_version": 2
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `16acb327cb95c8e906f38b5269bbf84cab7b14c5442581b660d5be7c8f3b7526`, `d467c9127acf91b44ecea5b903ddb7093aeea68868751924b5241057a98d2924`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `641ad89ec78d2d62b410b47349e3b91b674a281d2596d2210796d724623ab8fc`.
