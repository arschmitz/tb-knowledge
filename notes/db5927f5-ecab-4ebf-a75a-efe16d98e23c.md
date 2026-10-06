<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.066Z","paths":[],"source":{"reference":"knowledge-record:a89e5fb814583f547c21778e67131768cc384b089c345c513f7cc6eb4d334567","status":"provisional","publicationKey":"a05d77a7320c616b0ae6aa113bc2643e2b7bed6ee5c78d3d38b5b014965b4511"}} -->
# Keep both manual-config behaviors in a conflict

The recorded Account Hub conflict resolution combined `previousStep` selection with optional hostname clearing in `#initManualConfig()`. The merged behavior cleared both incoming and outgoing hostnames for IMAP/POP3 when `clearHostnames` was set. Use this as context for that conflict only; compare the current base, both sides, and call sites before resolving a new one.

Scope: Account Hub manual configuration.

This is a workflow or historical planning observation.

## Evidence

[Shared lesson record](../records/a89e5fb814583f547c21778e67131768cc384b089c345c513f7cc6eb4d334567.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `acef27673f679d0107ef90906177f56083b75aca43c6b3847e9ae201dc32b8e6`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `251221cb24630c157e9bd201099691c265e241034d6cf1cedf8fd85ff09b7f23`.
