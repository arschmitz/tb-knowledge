<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.244Z","paths":["mail/components/extensions/test/browser","mail/components/extensions/test/xpcshell"],"source":{"reference":"https://github.com/thunderbird/thunderbird-desktop/commit/80c729ea2822c3d083d42b22e5a6ff69f153fde2","status":"provisional","publicationKey":"b7762d30d60118f2a006235a72f0e5f641cdbe79622e2fd190de3d9a21646aed"}} -->
# Extension test files use harness prefix and underscore segments

For new tests under mail/components/extensions/test, follow the local harness family: browser_ext_<api>_<behavior>.js for browser tests and test_ext_<api>_<behavior>.js for xpcshell tests. Use an _mv3 suffix for a separate Manifest V3 variant where the family already does so. Keep API tokens such as mailTabs, getFull and folderModes in their actual camelCase within underscore-separated segments. The fixed endpoint survey has129browser_ext_ and47test_ext_ files out of185JS files; head-ews.js/head-imap.js/head-nntp.js are helper-file dash exceptions. This is a directory-scoped convention, not a universal ban on dashes or camelCase test task names.

Scope: style/extensions-test-files.

Paths:

- `mail/components/extensions/test/browser`
- `mail/components/extensions/test/xpcshell`

## Evidence

[Shared lesson record](../records/f9a32efbc4ae08bd93894dc36f730e804a28f81fe6c00a50486c9864ac510d5c.json).

- https://github.com/thunderbird/thunderbird-desktop/commit/80c729ea2822c3d083d42b22e5a6ff69f153fde2
- https://github.com/thunderbird/thunderbird-desktop/commit/0b93f0f7a926ed94c8a0646f18b6734ec7cc0f6d



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Supporting source excerpts and references are included in the shared records.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Detailed study origin: detailed-batch-228-257.
