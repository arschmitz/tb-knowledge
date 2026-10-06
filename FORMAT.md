# Note format

Create `notes/<new-unique-id>.md`. Use a lowercase UUID from `uuidgen` or another
UUID tool. Do not reuse a filename or edit a previous contribution.

Start with one metadata line containing valid JSON, then ordinary Markdown:

```markdown
<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T12:00:00Z","paths":["calendar/example.js"],"source":{"reference":"Exact commit or review URL","status":"provisional"}} -->
# One focused observation

Describe what was learned and where it applies.

## Evidence

Give the exact revision, path, comment, outcome, and relevant supporting quote.
Name the author or reviewer when known. Separate their statement from your inference.

## Validation and limits

State what ran, its result, and what remains unverified. Describe planning as planning.

## Correction

If applicable, identify the old note or record and the replacement evidence.
```

Replace the example values with real evidence. Use repository `tb-tools` for
console knowledge. Empty `paths` is valid for a workflow preference; otherwise
use repository-relative paths. The date must include a timezone.

The console indexes this as shared evidence. It does not mark the claim as
verified merely because the note exists. Derived lessons must validate their
citations and exact supporting quotes.

`records/<SHA-256>.json` holds console-generated evidence or lessons. SHA-256 is
a digest of the complete record content. Do not hand-edit these files or invent
digests. An AI without console tools should add a Markdown note instead.
