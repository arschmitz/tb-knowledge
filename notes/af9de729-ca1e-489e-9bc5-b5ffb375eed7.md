<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.211Z","paths":["mail/components/addrbook/content/modules/AddrBookDataAdapter.mjs"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/7b16ac0eac11960cde85b0f5244c5e5f92046d63","status":"supported","publicationKey":"d341cc4d702fd5fccf6aac04d2a8e42961020f29a09f918057ebec417fba3ccd"}} -->
# Build Address Book cells from ordered vCard values with legacy fallback

AddrBookDataRow formats multiple email, phone, and postal address values for a single table cell. For vCard contacts it uses prioritized values such as getAllValuesSorted("tel") and getAllValuesSorted("adr"); for legacy cards it reads Work/Home and other fields. It removes empty entries and joins with Services.intl.ListFormat. The xpcshell test adds, reprioritizes, and removes multiple values, checking the displayed text after each update. Current code still has these branches.

Scope: Address Book data.

Paths:

- `mail/components/addrbook/content/modules/AddrBookDataAdapter.mjs`

## Evidence

[Shared lesson record](../records/d451e61da696fd2fcdf8679bc81760b488f479aa29b5120c7cbdd589ecd90abb.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/7b16ac0eac11960cde85b0f5244c5e5f92046d63
- https://phabricator.services.mozilla.com/D208448
- https://bugzilla.mozilla.org/show_bug.cgi?id=1890731
- https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6

Source record: `efba16b8a6d3c2c31ae121c9965566a731c8cff3dedd1ea2cc062afdac63d4ed`

~~~
vCardProperties.getAllValuesSorted("tel");
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `3ebd56fb77fd3c46db96f3bd30b64e8281807fb1fdf5d8e8687de3ae74bf80d9`, `43b4ec6c5c83e9a330e85853f5bd492cabdd333871d31234172be48b81bb9481`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `31f5c949730a211044a840665d4386fd2485ff70e16504bc3b5c2f02e5b3470b`.
