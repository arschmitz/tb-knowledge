<!-- knowledge: {"repository":"thunderbird","at":"2026-10-31T05:18:16.437Z","paths":["mailnews/mime/src/mimemrel.cpp","mailnews/mime/test/unit/test_multipart_related_svg.js"],"source":{"reference":"knowledge-record:7bf1e409a52d83dafe67a1195fc5c44c8c89bab26b8eceee3bf7dd44dc3ffedb","recordId":"7bf1e409a52d83dafe67a1195fc5c44c8c89bab26b8eceee3bf7dd44dc3ffedb","status":"supported","publicationKey":"b94a80856a1a53fba23fd0999e5a44f8d09931d5323f86de98072c5354f59246"}} -->
# Related SVG URLs retain the declared type, while the regression checks bytes and channel metadata

The original change adds the part content type to the related resource URL so the declared SVG type can reach raw-part loading. The accepted helper uses URLParams to set and serialize type and filename. With inline attachments disabled, the regression test asserts decoded SVG bytes and channel contentType; later assertions also check the two URL parameters. These checks do not render SVG pixels or prove all protocol/channel parsers. No test or parser ran here.

Scope: MIME related SVG resource URLs.

## Evidence

[Lesson record](../records/7bf1e409a52d83dafe67a1195fc5c44c8c89bab26b8eceee3bf7dd44dc3ffedb.json).

- [Supporting record](../records/35601fb8e8efb26fc1a9fd0d6c312542dca3cfd86864add153de392ca1bf9be6.json)
- [Supporting record](../records/c9139e4df089b8a7b44216f3d64a15891de73c34059c86288e221e000abddc13.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
