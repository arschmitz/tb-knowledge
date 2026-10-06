<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.119Z","paths":["mail/components/accountcreation/modules/AccountConfig.sys.mjs"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/bf94a3eac5060512d6be39eb1e59fcae8f6f4059","status":"supported","publicationKey":"36e07ab4b0702dd293e2ba5cd0158e7068187d75a3dc3cd0a132e14e152b7225"}} -->
# Use sys.mjs for shared system modules

A JavaScript module imported through Thunderbird's resource module paths uses the .sys.mjs suffix. For a module centered on a named type or constructor, a matching PascalCase stem such as AccountConfig.sys.mjs makes it easy to find. Other module stems in this directory vary; match the nearby API.

Scope: style-naming.

Paths:

- `mail/components/accountcreation/modules/AccountConfig.sys.mjs`

## Evidence

[Shared lesson record](../records/d4d67675f63b6dee5d4f4af5367e002b114a698fd1b8bfeb3beaeda5d6ad0c10.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/bf94a3eac5060512d6be39eb1e59fcae8f6f4059

Source record: `7ecf233a6f6ad1798a6dbe593a9ae195230e60ed50e88528eb23aeecc09b1e5e`

~~~
export function AccountConfig() {
~~~

Source record: `a35a09f06f742364fe37f1a281ba8bc6b3684c824355b479df70204563e0f29f`

~~~
export function AccountConfig() {
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `a1a54de10121e3c15023141b188f8fac5705589dc1b46fc6a3df6b3fed3914eb`, `3a51d4cf76a6e3b76821b8be537b7dacd16c8c455721b4a8b931514457a384a6`.
