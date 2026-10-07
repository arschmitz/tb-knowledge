<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:30:55.795Z","paths":["mailnews/db/panorama/content/LiveViewDataAdapter.mjs","mailnews/db/panorama/public/nsILiveView.idl"],"source":{"reference":"knowledge-record:6fcdb8bcdef70e2aa38c0a64beed68308ccfdbdcc5debcbb963b16aaf7a7a948","recordId":"6fcdb8bcdef70e2aa38c0a64beed68308ccfdbdcc5debcbb963b16aaf7a7a948","status":"supported","publicationKey":"5fd8c8fe427536c65eefea4efae7d769d41d84c07990634eef7c1d075eaaf03c"}} -->
# Use named native column constants rather than their historical numbers

Current unread maps to READ_FLAG and flagged maps to MARKED_FLAG. Their accepted enum values follow the added RECIPIENTS entry and differ from the original flag-column landing numbers. Use the named constants at this JavaScript/native seam; do not copy a numeric value from an older diff. This is the inspected LiveView API, not a claim that its enum numbering is a permanent external serialization format. This is static source evidence. No runtime, build, lint or live accessibility check was run. Full Bugzilla and Phabricator discussion remains pending.

Scope: Panorama native column identifiers.

## Evidence

[Lesson record](../records/6fcdb8bcdef70e2aa38c0a64beed68308ccfdbdcc5debcbb963b16aaf7a7a948.json).

- [Supporting record](../records/4baa381814952d31965570c0a5a4ea4f9c6aeca74d4f08c3ad1bec7a4181dc3d.json)
- [Supporting record](../records/8694381799b9dfdaa9c453ea950565959bf60970ce1d6ccc0fb54be809c776ec.json)
- [Supporting record](../records/9436d9e646f0a7bf65f98685283d8f4d1d6f43555e45d7057e71fa4554048e93.json)
- [Supporting record](../records/f92c9509c3e4c67dcf5f80ca0c31865d58e4ca9f4637d5962feec2cd380378e3.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
