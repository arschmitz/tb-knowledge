<!-- knowledge: {"repository":"thunderbird","at":"2026-10-29T06:58:52.656Z","paths":["docs/adr/records/0002-imap-should-not-use-uid-as-message-key.md","docs/adr/records/index.md"],"source":{"reference":"knowledge-record:4efe0d15aefadad4fda66601dafafb05c10baa403bbebecdccbad44017cdaa25","recordId":"4efe0d15aefadad4fda66601dafafb05c10baa403bbebecdccbad44017cdaa25","status":"supported","publicationKey":"66522369a1c051b6484e442acd9ddc5ac0626862a2e5791f5ee05313ae51e2c3"}} -->
# ADR0002 records approved UID separation and a coordinated migration plan

ADR0002 is marked Approved and records the decision to store IMAP server UID separately while the database manages a stable messageKey. It calls for auditing ambiguous UID/key uses, avoiding nsMsgKey for protocol UIDs, and landing forward migration with the main change. It describes redownload/Repair Folder as a possible downgrade route and treats advance compatibility support as a policy option. These are accepted architecture-document statements, not proof the migration is implemented, a measured recovery result, or authorization to edit user instructions. Current conversion bodies are checked separately. Required review has a removed human body, so this source-only note gives no full-audit credit.

Scope: docs/architecture/imap.

## Evidence

[Lesson record](../records/4efe0d15aefadad4fda66601dafafb05c10baa403bbebecdccbad44017cdaa25.json).

- [Supporting record](../records/b3e138157696b5cfa1dfabe7e106aaca18ecc334994a3d688f76563c429d1115.json)
- [Supporting record](../records/d7927885195339bdecab0d6e3918980f3fa06a120864f042c3ec2f2bdc03bc3d.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
