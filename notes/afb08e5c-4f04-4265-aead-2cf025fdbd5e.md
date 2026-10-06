<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.186Z","paths":["taskcluster/kinds/release-update-verify-config/kind.yml"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/7747d7856f90","status":"supported","publicationKey":"9c656a92b750f9042043dc6dae1f20599b0d739b136cf18bc08f695b259f4d6b"}} -->
# Move the release-update verification watershed when a channel migration changes update paths

Bug 1894087 says update-verify tests for Thunderbird 115.11.0 and later needed the last ESR 115 watershed at 115.10.2 after a channel change. The 2024 release-update-verify-config change updates only the esr115 by-release-type value. D210030 was accepted without an inline change request, and Bugzilla records an esr115 approval. This version is historical; do not reuse it as the current watershed without checking the present release config. The lesson is that channel migration changes the valid update starting points used by release verification.

Scope: Release update verification.

Paths:

- `taskcluster/kinds/release-update-verify-config/kind.yml`

## Evidence

[Shared lesson record](../records/69b12601e68a30382028c87bc32506d210dcd39765b1661fddafce327ec600f8.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/7747d7856f90
- https://bugzilla.mozilla.org/show_bug.cgi?id=1894087
- https://phabricator.services.mozilla.com/D210030

Source record: `bfeea1d2e2af32fb0b85f04dea399ae7476b8df9d871e6a8adfb2385aba3082c`

~~~
esr115: "115.10.2"
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `608f99387faab52a0c3f251d21d30feb9212563f3ca0b86963c4c09c1ef7ad7d`, `ef7c8315d70f9f9b4b0bba2139ab72df6f82b3f6f5e6f30e01037597b3facac4`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `db2a18ab462502bfba38c2e7fbe2177f209cbd4618aea7ab3d6817f70a654cb4`.
