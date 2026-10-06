<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.053Z","paths":[],"source":{"reference":"knowledge-record:78d52f74c2ef66c83609876fa232ba391f027c0064beba1d42752857ac7aac53","status":"provisional","publicationKey":"bc7fb47b12b26f846b8369a54b40954deeeaab2bddeffaac09a5d335b631858e"}} -->
# Thunderbird Git Phabricator CodeRabbit and manual reviews

D321072 review: verify the complete event-to-model-to-render route, not just child events. `new-reminder` used invalid `CustomEventInit` key `bubble` rather than `bubbles` and had no mounted dialog/reminder-row consumer; `Math.floor(inSeconds / 60)` silently changes 90 seconds to one minute; showing/hiding the inline form needs focus transfer/restoration. `git diff --check` and `node --check` passed, but runtime tests were unavailable in the isolated clone. [Task 14]

Scope: general.

This is a workflow or historical planning observation.

## Evidence

[Shared lesson record](../records/78d52f74c2ef66c83609876fa232ba391f027c0064beba1d42752857ac7aac53.json).

- See the original record IDs below. This imported claim has no independently checked public source link.



## Validation and limits

Status: **provisional**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `5b13a508230378dc63c2bbfe2967bf976020937df22a4631b80d06539ff96bb3`, `7115b8fc32c01c99388af92ed2173edd3ec58fa5b21003e7b2dc894a333481b5`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `1f1f1e0db55885bc8ab79833d2b1fe02cf25e1d45fba7df40459902e06aea2ad`, `894dd838628f0ea48594e0c3bdfe18100f154efe5b3ffda34d9760a5778f72e2`.
