<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.220Z","paths":["mail/themes/shared/mail/tree-listbox.css","mail/base/content/about3Pane.xhtml","mail/base/test/browser/browser_cardsView.js"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/18f747268e17696b4cb9eb9b5ff16ecbc6f9d76b","status":"supported","publicationKey":"73f1160380504a6aae61e3a3864a0f2a3c846dc2ae476203a704dfc5d798f43b"}} -->
# Rename shared CSS classes through markup, code, and browser tests

The review asked to replace thread-card-container with the generic card-container because the container served both message and address book cards. The final patch changed message markup, common CSS, and browser_cardsView.js to use card-container; current markup and tree CSS keep that name. The browser test queries the class and checks the card height. When a class becomes shared, use one generic name at all consumers and update tests that select it. CSS classes in this area use lowercase words joined by hyphens; scope this naming observation to these tree and card components.

Scope: Tree views.

Paths:

- `mail/themes/shared/mail/tree-listbox.css`
- `mail/base/content/about3Pane.xhtml`
- `mail/base/test/browser/browser_cardsView.js`

## Evidence

[Shared lesson record](../records/b1674412b08060566e511c270b4e6972262d9bdf8faa9ae999a594b41775646b.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/18f747268e17696b4cb9eb9b5ff16ecbc6f9d76b
- https://phabricator.services.mozilla.com/D209025
- https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6

Source record: `b8d979cb8de077878d3eca9970648720eb04b5ff58e91d1c0e200fd5887174ba`

~~~
<div class="card-container">
~~~

Source record: `33d795b1885d795c13a9a7e049861607126bcf46808ecc00eaef3fe68a5cf4a9`

~~~
const tableData = tableRow.querySelector(".card-container");
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `605980aaa8a1676eae921617e8868e8792c42ee6e85ba5893af591b3258e5322`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `4867f25ee6fd3d8b4a676796674d6b0f5b5cc1514d9cc3cec3210a6f001a1aa0`.
