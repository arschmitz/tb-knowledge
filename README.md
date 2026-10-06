# Thunderbird shared memory

This repository is the shared knowledge itself. It holds evidence, review lessons,
scoped style preferences, code history, and explanations of how Thunderbird works.
An AI can use it with ordinary file and Git tools. No package installation or
running console is required.

Start with [AGENTS.md](AGENTS.md). Follow [CONTRIBUTING.md](CONTRIBUTING.md) when
adding knowledge and [FORMAT.md](FORMAT.md) when writing a note.
Read [CONSUMING.md](CONSUMING.md) for task retrieval and index setup, and
[SCHEMA.md](SCHEMA.md) for the durable record format.
Use [SKILLS.md](SKILLS.md) to select a standalone review, local verification,
test-writing, CI-debugging or conflict-resolution workflow.

- `notes/`: focused Markdown notes with scope, evidence, and uncertainty. Initial
  notes preserve selected knowledge from earlier work. They remain provisional.
- `records/`: immutable evidence and cited lessons captured by the console. Files
  use a digest of their content as their name. Search can be rebuilt from these
  records and the Markdown notes.
- `AGENTS.md`: how to retrieve, apply, and extend this memory.
- `skills/`: shareable workflow instructions and references. These retain the
  specialized criteria without requiring the console or replacing personal skills.

Search, automatic capture, learning, and sync code belong to the tb-tools console,
not this repository. Local indexes, models, personal task history, and private
sources stay in `~/.tb-tools/knowledge`. This repository works without those caches.

## Sharing through GitHub

The shared remote is [arschmitz/tb-knowledge](https://github.com/arschmitz/tb-knowledge).
Give readers read access and approved contributors write access. Set each clone's
`origin` remote to that repository. Use a separate clone for each writer.

Set `ai.knowledge.repositoryDirectory` in tb-tools to this checkout. The console
reads its memories, adds eligible evidence, commits new files, and syncs `origin`
at most once every five minutes while running. It commits locally before a
remote exists. `push: false` disables automatic commits and pushes for readers.
Git host permissions enforce actual access. No force-push is used.

Different uniquely named contributions normally merge without text conflicts.
Conflicting claims still need evidence to resolve them. Shared instruction changes
require deliberate review and may require a manual merge.

History-study findings, syntax and naming lessons, and older project imports feed
this repository. Console writers publish useful scoped lessons for enabled
repositories automatically. Raw private sources stay local; their useful claims
retain explicit provenance and uncertainty. See CONSUMING.md for copied summaries,
portability corrections, and missing-source limits. The human style guide remains
a separate publication draft.
