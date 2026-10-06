# Durable record schema

Implementation and validation belong to tb-tools under `commands/knowledge/`.
This document lets other consumers read the durable data without SQLite or Codex.
The repository contains data and instructions. It does not contain executable
indexing or learning code.

SKILLS.md and `skills/<name>/SKILL.md` with their Markdown references are reviewed
workflow instructions. They are not JSON records or Markdown knowledge notes.
The console accepts their regular, non-executable files during Git sync and does
not add their text to evidence, lessons or extraction jobs. They can be updated
through deliberate review; immutable note/record correction rules do not apply
to instruction edits.

## JSON records

Each `records/<id>.json` file contains one UTF-8 JSON object:

| Field | Meaning |
| --- | --- |
| `version` | Schema version. Current records use `1`. |
| `id` | Lowercase SHA-256 digest of the object with `id` removed. |
| `kind` | `evidence` or `lesson`. |
| `visibility` | `shared` in this Git repository. Local stores can also use `private`. |
| `repository` | Stable project identity, usually `thunderbird` or `tb-tools`. |
| `at` | Date with timezone. Do not treat a publication date as source acceptance. |
| `title` | Short readable title when present. |
| `paths` | Array of repository-relative paths. Empty for a workflow lesson. |
| `text` | Evidence or claim text, at most 2,000,000 characters. |
| `source` | Source type, references, revision, provenance, and validation limits. |

Canonical JSON sorts object keys recursively, omits undefined object fields,
retains array order, and has no added whitespace. Primitive values use JSON
encoding. The digest excludes `id` and any trailing file newline. Consumers should
validate the digest before indexing. Use tb-tools to create JSON records; other
agents should add Markdown notes instead of inventing digests.

A lesson also has `component`, `status`, `evidence`, `quotes`, and `supersedes`.
`evidence` contains record IDs in the same repository. Each quote has an `id`
and exact `text` from that evidence. Resolve the full dependency chain. A missing
original private source does not become available through a copied summary.

Statuses are `provisional`, `supported`, `disputed`, and `superseded`. A newer
date does not retire an older claim. The console only applies `supersedes` from
a supported lesson with the same component and paths and explicit replacement
evidence. Portability and mirror aliases group copies; they do not resolve
conflicting interpretations.

## Source fields

Source fields vary by capture type. Preserve unknown fields when reading.

- `type`: for example `code-snapshot`, `review-feedback`, `shared-note`,
  `historical-lesson-summary`, `lesson-publication`, or `extraction`.
- `revision`, `file`, `reference`, `url`: exact source anchors when available.
- `verified`, `accepted`, `reverted`: recorded checks or review outcomes.
- `sourceAt`: original evidence date retained by later publication or correction.
- `originalLessons`, `priorLessons`, `portableCopies`, `recordId`: links between
  a claim and its copies. These are not independent evidence.
- `privateEvidence`: original private IDs retained for audit. Their content is
  deliberately absent from the shared clone.
- `basis`, `verification`, `evidenceAvailability`: interpretation and access limits.

Personal task transcripts and legacy memory files cannot be shared as raw
records. Useful project claims derived from those sources can be shared as
provisional summaries after repository authorization. Their exact private quotes
remain private. Do not promote such summaries to verified code evidence.

## Markdown notes

FORMAT.md defines the one-line JSON metadata header. The console creates a
`shared-note` evidence record from the header and Markdown body. Metadata needs
`repository`, `at`, `paths`, and `source.reference`. A human note is evidence,
not an automatically supported lesson. A generated lesson note links to its
lesson JSON and carries `source.recordId` or a publication key.

## Local index and queue

The console builds SQLite full-text search and optional vectors outside Git.
Learning jobs have `pending`, `done`, or `skipped` state. `skipped` includes
derived mirrors and CI observations retained for direct search. It does not mean
the code or history was studied. Completed history coverage uses its separate
durable checkpoint. A learning budget cannot establish study completion.
