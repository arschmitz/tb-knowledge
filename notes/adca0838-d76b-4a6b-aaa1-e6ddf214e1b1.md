<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.205Z","paths":["mail/themes/osx/mail/messenger.css"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/8ec37a6da449^","status":"supported","publicationKey":"794672828c63aad21aabfb97bdc7240d54e05b657f4751704f08316f2e205937"}} -->
# Check shared theme tokens in every window that inherits them

Bug 1897638 removed a macOS messenger.css override after --toolbar-field-border-color: transparent made Address Book edit-contact fields lose their borders. The rule had been added for toolbar styling in Bug 1887617, but the token reached another surface. Before adding a shared theme token override, check dialogs and content that use that token on the same platform and native-theme setting. The accepted fix returned to shared colors.

Scope: macOS theme.

Paths:

- `mail/themes/osx/mail/messenger.css`

## Evidence

[Shared lesson record](../records/65bf84c8a41e58dca21f19611f891f793a5a7a3a802077d7a0c632f745a655b2.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/8ec37a6da449^
- https://phabricator.services.mozilla.com/D210888
- https://bugzilla.mozilla.org/show_bug.cgi?id=1897638

Source record: `935b763d7ef57f582100148b1f01db9bf3b1d9577261e692c86b432fe8cb2a08`

~~~
--toolbar-field-border-color: transparent;
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `4b434db20e0bf0e36d8a1e729089e36e646d0938fe741e017b094b5432e1088e`, `d35cff8c10906487b3cf49f93f5b2b20ba4906f78e0ea27270ef8671cc4b5450`, `f935d9e3c1ba617e689b49c6210af6a0ae3ce86a2eb62fef9899d8ac0924186e`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `602eaedadc91c05e99bff2ca916069ddf8612ab443fa9174f061bd88d4ad259a`.
