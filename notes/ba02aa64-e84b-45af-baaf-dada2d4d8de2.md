<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.111Z","paths":[".stylelintrc.js"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/bf94a3eac5060512d6be39eb1e59fcae8f6f4059","status":"provisional","publicationKey":"8c015c93ed67158cc6ae5cd6127f78bfa2c927459d1b0fb9e4b66a127f61dc9d"}} -->
# Use logical CSS properties

Enforced at the inspected source revision: Stylelint requires logical CSS properties for direction-sensitive sizing, margins, padding, and borders where logical equivalents exist.

Scope: style-css.

Paths:

- `.stylelintrc.js`

## Evidence

[Shared lesson record](../records/9e60c6d345b58cfa7f0ce27b874dc39e656adfc17a77de8deaa0c2553cc32f58.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/bf94a3eac5060512d6be39eb1e59fcae8f6f4059

Source record: `a1eb29826edd764631bee9ce959992b9117dcf6fb5ef2bf128b735427a5b8b7d`

~~~
"csstools/use-logical": "always"
~~~

## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `bea21cad949eeb4ab3e27539c104c18cafd187a645a832e66820fb26eaa3e1e6`.
