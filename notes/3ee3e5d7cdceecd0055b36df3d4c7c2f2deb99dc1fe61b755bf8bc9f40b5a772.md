<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T05:26:06.572Z","paths":["mail/base/test/browser/browser_statusFeedback.js"],"source":{"reference":"knowledge-record:3ee3e5d7cdceecd0055b36df3d4c7c2f2deb99dc1fe61b755bf8bc9f40b5a772","recordId":"3ee3e5d7cdceecd0055b36df3d4c7c2f2deb99dc1fe61b755bf8bc9f40b5a772","status":"supported","publicationKey":"407ad249963ba03ae7a37d7aa79672923e6b651bdfccbdc4de916129b44c3d5b"}} -->
# Status tests observe each displayed mutation rather than only the final text

The accepted browser status test waits for the queue to empty, captures value mutations and checks the first ten expected messages from a burst of twenty-five reports. This provides an ordering oracle for the retained messages. It does not prove that every later message is permanently discarded or validate all throbber timers. No timer or UI runtime ran here. This is static source and test-code inspection. Full Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mail/base/test.

## Evidence

[Lesson record](../records/3ee3e5d7cdceecd0055b36df3d4c7c2f2deb99dc1fe61b755bf8bc9f40b5a772.json).

- [Supporting record](../records/c28ec0c7cba9b1db8fe84ee6e2712385872da66973591ba70370f566bc09e625.json)
- [Supporting record](../records/db81e8ab51cf287054a02cf3e9aeba0b31691247cb4c5e5d430ee3f48fa33c97.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
