<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:25:06.481Z","paths":["mail/test/browser/folder-display/browser_messagePane.js","mail/base/content/widgets/message-pane.mjs"],"source":{"reference":"knowledge-record:697d38dbaa4e5f1cf01790e77d8cdb1f40c721fded744daeefb9ed7b1a4f0dac","recordId":"697d38dbaa4e5f1cf01790e77d8cdb1f40c721fded744daeefb9ed7b1a4f0dac","status":"supported","publicationKey":"4e7c84fbdc974eac4cfc7586d208060ba79ed6082ae8dcad133aefcf53c6cf20"}} -->
# Message-pane archive tests cover both previous display modes

The new regression file creates one-message and three-message folders, archives the selected messages, and checks that the corresponding single or multimessage browser is hidden. It retains both scenarios in accepted source. Those visibility assertions support the user-visible clearing symptom, but do not by themselves inspect the hidden content, collapsed-pane path or assistive-technology state. Proposed tests extending this family should choose the prior display mode explicitly. Static source and test-code inspection only. Full Bugzilla and Phabricator timeline and inline discussion remains pending. No runtime or live accessibility result is claimed.

Scope: Message pane regression tests.

## Evidence

[Lesson record](../records/697d38dbaa4e5f1cf01790e77d8cdb1f40c721fded744daeefb9ed7b1a4f0dac.json).

- [Supporting record](../records/17d3552354c195d8c358d5d7bdd539f1f532d34ca6b274ae62cc3ee46ee7bf95.json)
- [Supporting record](../records/c7fd9a56d26c1232d5d3d518adbc5f0014f7d2b888f3d2f5850efabcddcc8c7a.json)
- [Supporting record](../records/f22c0caa0cdedbaa5c55dad41a645356b49e9db54211c95e9ed3cec41beb9b50.json)
- [Supporting record](../records/f6ab3f150d5f78d76e07bcb7002afdde2f27641b867e03b121fe5cc67eed1f38.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
