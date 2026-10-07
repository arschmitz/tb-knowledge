<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T00:47:50.662Z","paths":["mail/test/marionette/manifest.toml","mail/test/marionette/test_sessionstore.py","mail/test/marionette/scripts/get_tabs.js"],"source":{"reference":"knowledge-record:b1bcd34e4ca89aa2aced7bfddfc0ef9bbaaeab2bf3c08f98f5cf364c618bc100","recordId":"b1bcd34e4ca89aa2aced7bfddfc0ef9bbaaeab2bf3c08f98f5cf364c618bc100","status":"provisional","publicationKey":"783c87edf6055b8dc1b84ecfa956dea9ec3cf92926666cdae94a5e825eafbe5e"}} -->
# Use test_ for discovered Marionette methods and native files for substantial script helpers

This is a scoped manual naming/readability proposal for mail/test/marionette. Test methods use test_; helpers such as check_json_file and subtest_simple_tab do not. The accepted review moves substantial JS from a Python string to a support file; the current helper is scripts/get_tabs.js. Use an action-specific script name, register the support path, and retain its real .js ending. Browser test files still use browser_ and task function spellings vary, including testGetDisplayedMessages_MV3 and test_getSelectedMessagesWithOpenContextMenu; this batch does not justify a repository-wide function-case rule.

Scope: mail/test/marionette.

## Evidence

[Lesson record](../records/b1bcd34e4ca89aa2aced7bfddfc0ef9bbaaeab2bf3c08f98f5cf364c618bc100.json).

- [Supporting record](../records/6da90334e46c294ccd447783d2cc9fd09cee7a9fc7ceafb345ff91b102a8098c.json)
- [Supporting record](../records/7e7f6be3c373868a29d04df37fdbe8984908dcd3c9bc0c807bc53c8c585ccfaa.json)
- [Supporting record](../records/94b4dc4886b5d47136c31d84f7a5928b9b39e9c7ea60ff7117c32098dacae84a.json)

## Validation and limits

Status: **provisional**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
