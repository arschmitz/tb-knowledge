<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T01:53:06.600Z","paths":["taskcluster/kinds/l10n-bump/kind.yml"],"source":{"reference":"knowledge-record:ccd780c4f8fa7f735caa833bdaceb7c2fd4c8ad1b3bdb060fd588cefd965bd4b","recordId":"ccd780c4f8fa7f735caa833bdaceb7c2fd4c8ad1b3bdb060fd588cefd965bd4b","status":"supported","publicationKey":"f456285785e5598bbc41a3f6acd06d89b5d71bf70ce22540757ea94a9035a18c"}} -->
# The l10n bump edits separate the dontbuild value from its configuration shape

The initial commit removes a project-specific false override while keeping by-project/default:true. A separate follow-up replaces that keyed shape with scalar dontbuild:true, which the fixed kind retains. ignore-closed-tree is a separate setting, with a later ESR branch name. The selected kind delegates to Gecko transforms; neither a same-named comm helper nor the decision DONTBUILD flag establishes that imported worker/schema contract. No taskgraph or build execution proved an outcome.

Scope: Thunderbird localization bump worker configuration.

## Evidence

[Lesson record](../records/ccd780c4f8fa7f735caa833bdaceb7c2fd4c8ad1b3bdb060fd588cefd965bd4b.json).

- [Supporting record](../records/07f5fc102703a893153844b77ccc985fb36a516a4ab3125d4dd2eb859ea0bfc3.json)
- [Supporting record](../records/79f1dd6d596544fc59434a6aa3d53989cee2ed333609ff1560bbc8bdc5fad053.json)
- [Supporting record](../records/aea19ec9413c7a9d3a14a32b570e3c8006ae31e20fdea8af6bf6b96e87c85b95.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
