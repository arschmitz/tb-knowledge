<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.177Z","paths":["taskcluster/kinds/repo-update/kind.yml"],"source":{"reference":"https://phabricator.services.mozilla.com/D209693","status":"supported","publicationKey":"16ea05f5c88b783a5e9c0203ecc8f6715cc9c5f5cb26eb81366847e12db10f8a"}} -->
# Do not conflate Taskcluster Notify API scopes with notification routes

Bug 1895002 explains why the original Rust automation notification grant was too narrow: Notify API calls need a notify:matrix-room:... scope, while routing a task completion uses a notify.matrix-room....on-any route grant. Colon and period separators matter. The first comm patch changed per-level task routes and scopes but was backed out for decision failures. Bugzilla records a correction in the separate ci-configuration repository; the comm patch was later relanded with identical file contents. The external scope correction and comm config need to be checked together when notifications fail. This lesson does not claim the backout alone proves which taskgraph expression failed.

Scope: Rust automation Taskgraph.

Paths:

- `taskcluster/kinds/repo-update/kind.yml`

## Evidence

[Shared lesson record](../records/9d57e5a6b71a29e1e4f5fb1b1c423f476c92d8413d3d58353f1891690288bd52.json).

- https://phabricator.services.mozilla.com/D209693
- https://github.com/thunderbird/thunderbird-desktop/commit/69b29f2c4b2
- https://bugzilla.mozilla.org/show_bug.cgi?id=1895002

Source record: `7fdf466001d348ad1b74bfb64e3c54ff2c86966b5be15c5eda7263b18b0f5faf`

~~~
- notify:matrix-room:!TWztIhgqLawNpRBZTC:mozilla.org
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `422bd1dd442babdc063b85dce2da2b33bf9dff1afc35c872add59c469915fb62`, `dc66cb37fae55225ac6a022f764bf3534a801ede01c2462798858e2c605fe03b`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `82763a12f50e6a78a822833bc769b5d4cc953632342f323802687d0e05bc76c0`.
