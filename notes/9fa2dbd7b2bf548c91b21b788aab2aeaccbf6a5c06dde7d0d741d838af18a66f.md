<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T14:41:47.573Z","paths":["taskcluster/kinds/source-test/mozlint.yml","taskcluster/test/params/cc-nightly-desktop.yml"],"source":{"reference":"knowledge-record:9fa2dbd7b2bf548c91b21b788aab2aeaccbf6a5c06dde7d0d741d838af18a66f","recordId":"9fa2dbd7b2bf548c91b21b788aab2aeaccbf6a5c06dde7d0d741d838af18a66f","status":"supported","publicationKey":"9453a7205e5f0a16437c77bf4c3f237d93f8fd4becb81925d84754aed98ac06b"}} -->
# Black CI removal drops both the task and its existing-task fixture

The comm port removes the py-black source-test task and the matching source-test-mozlint-py-black entry from the nightly fixture. Ruff remains a separate task. This source change controls CI task routing; it does not by itself remove the local lint wrapper or prove formatting results. The local cleanup is a separate history entry. No lint or taskgraph run was performed.

Scope: Taskcluster Python lint task routing.

## Evidence

[Lesson record](../records/9fa2dbd7b2bf548c91b21b788aab2aeaccbf6a5c06dde7d0d741d838af18a66f.json).

- [Supporting record](../records/5cbe0a84ebe0a54cc543e99aaca6f0918bf01205d5f5a30cb50d381f5fd0ac63.json)
- [Supporting record](../records/a4d4a52e21f236bad34e0b0a834e7b8f5ed5bf04a5c179d4c87398daadad0c0a.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
