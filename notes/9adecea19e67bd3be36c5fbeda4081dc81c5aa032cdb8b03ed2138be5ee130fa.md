<!-- knowledge: {"repository":"thunderbird","at":"2026-10-28T23:30:04.457Z","paths":["taskcluster/comm_taskgraph/loader/test.py","taskcluster/kinds/test/kind.yml"],"source":{"reference":"knowledge-record:9adecea19e67bd3be36c5fbeda4081dc81c5aa032cdb8b03ed2138be5ee130fa","recordId":"9adecea19e67bd3be36c5fbeda4081dc81c5aa032cdb8b03ed2138be5ee130fa","status":"supported","publicationKey":"a193a4c828f26a90ba961500f8e460f58a840c283026f9f64fe5a08551fe800d"}} -->
# The comm test loader expands existing builds and test sets before transforms

The test kind selects comm_taskgraph.loader.test. Its loader finds builds by platform/type, rejects duplicate build keys, skips missing platforms and raises for unknown test sets. It creates per-platform test descriptions and yields them to transforms. The original local clone had five loader arguments; accepted code later forwards write_artifacts too. The computed signing map is not consumed by get_test_platforms in this source. These are generator contracts, not a successful decision-task run or proof every signing dependency resolves. No taskgraph or build ran.

Scope: Taskcluster comm test loader source contract.

## Evidence

[Lesson record](../records/9adecea19e67bd3be36c5fbeda4081dc81c5aa032cdb8b03ed2138be5ee130fa.json).

- [Supporting record](../records/476f9ebca691cffba350c54a2843dbe70b97c052aa807ef113df84ccb8a8ebef.json)
- [Supporting record](../records/5f3a171937edf1eb422af49cc372bf159019e98017cf8bc6dbbaf29728813207.json)
- [Supporting record](../records/7a9e6c3062c3a02aeb7e987138daeba2fad68112b05290d591786f89d557d279.json)
- [Supporting record](../records/a4f3ec89478ddf4611b59bf1c1bd73dfda2a7f00fff78f7b3ccaf90aca407971.json)
- [Supporting record](../records/c3684b8befe7c2fe45f5d61bcaebc4849c11d46716d917b8816530596af76887.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
