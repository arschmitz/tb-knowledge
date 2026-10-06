<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.238Z","paths":["mail/base/content/contentAreaClick.js","mail/components/addrbook/content/aboutAddressBook.xhtml"],"source":{"reference":"https://phabricator.services.mozilla.com/D211136","status":"provisional","publicationKey":"1a29eea880ed58fcba6cc9aeb88d996415bff822602f649a1da331f7867ab3fc"}} -->
# Address book search button images exposed an unrelated content click interception

The address book replacement uses empty-src icon images in search-bar buttons. During D211136 review, the author found about:addressbook lives in a content browser whose contentAreaClick handler treated any image click as an attachment image, so button clicks were intercepted. The landed patch guarded that old handler with target.src. That handler is absent from the current checkout, so this is a historical breakage lesson: when putting icon images inside buttons in a content browser, test actual clicks through the host click handler, not only widget events.

Scope: Address book content click interaction.

Paths:

- `mail/base/content/contentAreaClick.js`
- `mail/components/addrbook/content/aboutAddressBook.xhtml`

## Evidence

[Shared lesson record](../records/4a4b84e5c94c2f840c1f528214420b101f213689ab4a35cef72a0f34d8ae318d.json).

- https://phabricator.services.mozilla.com/D211136
- https://github.com/thunderbird/thunderbird-desktop/commit/785c6a086a97561bec784599bb13923a7e32d07f

Source record: `3c05c2899656de5fda124bdd86783d5e910a59dced6c98882eb656cc25075514`

~~~
+    if (HTMLImageElement.isInstance(target) && target.src) {
~~~

Source record: `3c05c2899656de5fda124bdd86783d5e910a59dced6c98882eb656cc25075514`

~~~
+        <img slot="search-button" src="" alt="" />
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `6c9eb41ddbd15210a9bc64f5c58f8d1a44b48a0ce0dfcdd17289f4314f4a8464`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `f2dc56493c13495753c975363fa6f8a2a2b23c9017c1f02918127edf9cc97341`.
