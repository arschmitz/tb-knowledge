<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.180Z","paths":["mail/locales/en-US/messenger/preferences/am-archiveoptions.ftl"],"source":{"reference":"https://phabricator.services.mozilla.com/D208387","status":"supported","publicationKey":"ba18579b7d18729ec6929a8d6e569e353dddadb6df09b719319c167b1c1a1603"}} -->
# Carry translator constraints into the Fluent resource

D208387 review requested the old localization notes for the Archives and Inbox labels after the DTD-to-Fluent move. The accepted FTL keeps comments saying each name must match the default folder name. The controls carry .label and .accesskey attributes, while ordinary text such as the dialog title is a simple Fluent value. Current archive-options FTL still has those folder-name comments; later HTML preview markup changed the folder names to simple -label values. Choose the Fluent value shape for its target and preserve translator meaning.

Scope: Archive dialog localization.

Paths:

- `mail/locales/en-US/messenger/preferences/am-archiveoptions.ftl`

## Evidence

[Shared lesson record](../records/9dfbc321a88c766e45fa696c46dd1a91876beb2095e0bed2a9e3adb72c3cc2f1.json).

- https://phabricator.services.mozilla.com/D208387
- https://github.com/thunderbird/thunderbird-desktop/commit/5a9f215a1030
- https://bugzilla.mozilla.org/show_bug.cgi?id=697706

Source record: `a6c2443d8d758d392c2578e74d19e27f65c22062586dc7f1930e58e107f6ce1d`

~~~
# This should match the default name for the "Archives" folder.
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `4a4e7144b6130ea197aaaaf766fc58e62f0869cc541c47bf9486649940b2d4eb`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `2416ced8be3d99a313e29ede5011471659b5de8514093bb4d07aed9ade4b75e3`.
