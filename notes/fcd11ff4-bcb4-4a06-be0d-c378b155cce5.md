<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.185Z","paths":["mail/components/extensions/schemas/browserAction.json"],"source":{"reference":"https://phabricator.services.mozilla.com/D210127","status":"supported","publicationKey":"5ce217d91f16280cd8f35af89895a2c5014880fd4aef7e644a36e9db6a9261c3"}} -->
# Accept harmless Firefox action manifest keys while marking Thunderbird behavior clearly

After the unified toolbar removed MV3 action.default_area, a simple Firefox extension with that key could fail to install in Thunderbird. The 2024 fix makes default_area an optional string in the action schema, marks it deprecated and ignored, and points developers to allowed_spaces. The runtime does not use its value. The same patch changes other schema deprecation text from “Unsupported on Thunderbird at this time.” to “Unsupported on Thunderbird.” D210127 was accepted without a requested code change. Current browserAction.json still accepts default_area and describes it as deprecated and ignored. Preserve compatibility with harmless known manifest properties without promising to implement them.

Scope: Extensions and WebExtension schemas.

Paths:

- `mail/components/extensions/schemas/browserAction.json`

## Evidence

[Shared lesson record](../records/e617319c861b340d951293c2e8be36115206f434412303a0c5b12babaebd7b62.json).

- https://phabricator.services.mozilla.com/D210127
- https://github.com/thunderbird/thunderbird-desktop/commit/3e6c7229c835
- https://bugzilla.mozilla.org/show_bug.cgi?id=1896288

Source record: `639e5e25971de161c8dcaf259f826848171362d62d0d1ad9a305d6aa2557bddd`

~~~
"deprecated": "Unsupported on Thunderbird."
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `040dc62ba181f6e2ab5b009a07fe364431266a14c7a931cf3252763aedd68b4e`, `dd6f454026e5c087ed663101eecffd0489affa27ed3355c255a8d4e80209e7da`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `16342044b0459f6dc6f341ba2d12a41139d8c0bfdc326619b06298ccb6009a7a`.
