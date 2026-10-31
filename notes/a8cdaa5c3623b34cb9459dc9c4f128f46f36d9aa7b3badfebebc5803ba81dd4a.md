<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T07:20:52.486Z","paths":[".zed/tasks.json"],"source":{"reference":"knowledge-record:a8cdaa5c3623b34cb9459dc9c4f128f46f36d9aa7b3badfebebc5803ba81dd4a","recordId":"a8cdaa5c3623b34cb9459dc9c4f128f46f36d9aa7b3badfebebc5803ba81dd4a","status":"supported","publicationKey":"ea6f5d422afaa59b58443fa652fe879bfce196ac99469e0cdb3fbbb7671319b2"}} -->
# The Zed task file calls the parent mach command and passes the current file to test

The owned task file declares8editor actions with command strings that point to ../mach. Run Test uses command ../mach and arguments test and $ZED_FILE. The file declares no working directory, so successful invocation still depends on the editor's working-directory and variable-expansion contracts, which were not paired or run here. This is scoped configuration evidence, not a build/run guarantee or a global editor convention.

Scope: Developer editor task configuration.

## Evidence

[Lesson record](../records/a8cdaa5c3623b34cb9459dc9c4f128f46f36d9aa7b3badfebebc5803ba81dd4a.json).

- [Supporting record](../records/63adaa2b4609720b2400e7e5d9e45ab900d70782fa3632b299855202a015299b.json)
- [Supporting record](../records/b3acaf768115b448eff8a13cd12e3d79fe98900f47278452fe783c863146e009.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
