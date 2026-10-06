<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.235Z","paths":["tools/lint/commlint/__init__.py","tools/lint/rustfmt.yml"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6","status":"supported","publicationKey":"4279b07a6eecc22fe325d27bc81dc61c314e8c4aa296e75a4e7e79fec2f0978c"}} -->
# Thunderbird rustfmt lint turns formatting differences into CI errors and specifies edition

The 2024 rust_lint wrapper added --check and an explicit --edition 2021 because standalone rustfmt did not infer Cargo.toml edition, and promoted parse_issues warnings to errors so Treeherder marked format failures orange. Review confirmed that Try result. Current wrapper uses --edition 2024, returns early on no paths so rustfmt does not wait on stdin, and treats a missing binary as an error in MOZ_AUTOMATION while allowing local lint to continue. Use the current edition and wrapper behavior when interpreting lint outcomes; the 2024 edition value is historical.

Scope: Rust lint CI behavior.

Paths:

- `tools/lint/commlint/__init__.py`
- `tools/lint/rustfmt.yml`

## Evidence

[Shared lesson record](../records/878ed203d9f6f445cfe5091b3c2e46484e04dacb6d7c22eef36085ff8958ab0f.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/46228449fd6
- https://github.com/thunderbird/thunderbird-desktop/commit/1e0f4f21f9a0643ce4a4efedd804873644d3732e
- https://bugzilla.mozilla.org/show_bug.cgi?id=1896934
- https://phabricator.services.mozilla.com/D210845

Source record: `b0e089d829104d9a323a2c90d8c858211e86a9ee1f28375f7c7125f39954d58f`

~~~
cmd_args.extend(["--check", "--edition", "2024"])
~~~

Source record: `eb8682feb4294ab0a0a776e8e1b8936948d354b93b49b0a2c35f020786655c6f`

~~~
wraps: commlint:rust_lint
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `4ec40675bdfa55df5d3017a112f59337c0971c27607c036274dd67845af9c980`, `d017623c9694ff5217c7b2d83bae62ceb0ce257383608da20adbd0617868ae7a`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `55c848e795bdf1ffbbfb78005faeb6a2c0b42cf1f7cb9a2c02947bce07772d1e`.
