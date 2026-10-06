<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.252Z","paths":["mail/base/content/about3Pane.js","mail/base/content/mailCommon.js"],"source":{"reference":"knowledge-record:583ca5dfdd7686959e1a3313ed9557ba387985e49a9b0604e7f25c3a7f75d9a8","status":"provisional","publicationKey":"b5b7246ae65e0696eb775d43ea19fcc6e198af7fcd3c5205ab7f2dd9b40094fb"}} -->
# Distinguish selected rows from the context-menu target

When right-clicking outside a selected folder range, an override folder can be the command target without changing the range. When acting on the range, intersect capabilities and snapshot rows before mutating the tree. Entry292 disables single-folder views and shortcuts while multiple folders are selected instead of leaving stale gFolder/DB view references. Current code retains the context override and clears the active single-folder view.

Scope: folder-pane multiselection behavior.

Paths:

- `mail/base/content/about3Pane.js`
- `mail/base/content/mailCommon.js`

## Evidence

[Shared lesson record](../records/583ca5dfdd7686959e1a3313ed9557ba387985e49a9b0604e7f25c3a7f75d9a8.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `7235a4d38a1b98e163421874cfaaf30b3220ef0ca124a9a35213da588f416b1f`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Detailed study origin: detailed-batch-288-317.
