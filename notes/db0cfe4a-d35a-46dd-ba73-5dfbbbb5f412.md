<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.180Z","paths":["mailnews/base/prefs/content/am-archiveoptions.xhtml"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/5a9f215a1030","status":"supported","publicationKey":"1ed545e921e80a7a5516c8d3f2b28d45b97572e4099e95e55051741c6c44f548"}} -->
# Convert the archive dialog and its resource registration together

D208387 replaced DTD entities in am-archiveoptions.xhtml with matching data-l10n-id values and a normal <link rel="localization"> in the head. The review required removal of the old DTD entry from mail/locales/jar.mn. The accepted patch also kept <!DOCTYPE html>; removing the external DTD did not mean dropping the document type. This is a complete migration across UI, Fluent resource, packaging registration, and migration script. The current dialog still uses the Fluent resource, though its preview markup changed later.

Scope: Archive dialog localization.

Paths:

- `mailnews/base/prefs/content/am-archiveoptions.xhtml`

## Evidence

[Shared lesson record](../records/31e952c2425c32728cfb5a52d2f0722085695bdd2d71f1ffe0bceeba365c810d.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/5a9f215a1030
- https://bugzilla.mozilla.org/show_bug.cgi?id=697706
- https://phabricator.services.mozilla.com/D208387

Source record: `7205f6076c6c2d1b6e4836130a7f0fef7af37e03206884a1af1c94c76f15270f`

~~~
rel="localization"
      href="messenger/preferences/am-archiveoptions.ftl"
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `ed84d2999c6a256447130914b333653439eb424d724e6b4c03cb233d95f33c1c`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `92c5a3de54404ae2a11aad63159a3a409ac27fc22df530057a359359bf75b85b`.
