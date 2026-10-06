<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.064Z","paths":["mail/themes/shared/mail/colors.css"],"source":{"reference":"knowledge-record:e6eea2f7ab8fe0ebfeea872a820c077f47e785942fa949e0fe17dbd9ba74ba98","status":"provisional","publicationKey":"1462bbb4e48c075e163411a5358f2cd760e95e41b86917ab57cb0f1f840954a3"}} -->
# Review Bolt token use at the component

The recorded Thunderbird accessibility-review guidance treats Bolt semantic `--color-*` tokens as expected theme tokens. For high contrast mode (HCM) review, inspect how each component uses those tokens for states, borders, and shadows, and check its `prefers-contrast` and `forced-colors` behavior. Token use alone was not a reported defect. This is intended review guidance; check the current tokens and component before applying it.

Scope: Thunderbird accessibility review.

Paths:

- `mail/themes/shared/mail/colors.css`

## Evidence

[Shared lesson record](../records/e6eea2f7ab8fe0ebfeea872a820c077f47e785942fa949e0fe17dbd9ba74ba98.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `41e53c433a5a4b48aa621f076c9da9f611d3fda36f5d1da71f0253258ccbd52c`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `a64cf89e07e67db4bd4ba9112db9e414d5dfa146343563e75d005d3c2cfb0189`.
