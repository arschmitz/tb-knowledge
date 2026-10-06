# Consume this knowledge

tb-tools with Codex is the main consumer. It provides exact search, local semantic
search, cited learning, source checks, private capture, and Git sync. Other agents
can use the same notes and records with file and Git tools. They do not need to
run the console or an AI learning job.

## Start with a task

Read AGENTS.md. Identify the repository (`thunderbird` or `tb-tools`), component,
changed paths, symbols, bug number, and review number. Search only those terms:

```sh
rg -l 'CachedStore|deleted|getAllIDs' notes records
rg -l 'test name|file name|camel|kebab|class name|CSS|DOM' notes
```

Open the useful files. Follow each lesson's `evidence` IDs to
`records/<ID>.json`. Check the original source, its revision, tests, and limits.
An exact quote confirms that the source said something. It does not prove the
interpretation or current runtime behavior.

For syntax, naming, and style, distinguish component patterns, accepted review
requests, and proposed rules. Prefer newer accepted source in the same scope.
Keep rules outside lint and formatting visible. Preserve older counterexamples
and exceptions. The human publication style guide remains a separate draft.

## Optional tb-tools index

Use Node.js 22.13 or later and the tb-tools checkout. Put local caches in a
separate directory. A fresh clone is enough to rebuild exact search:

The implementation is available on the tb-tools default branch,
[`master`](https://github.com/arschmitz/tb-tools/tree/master).
This is console code; this knowledge repository keeps only data and consumer
instructions.

```sh
node /path/to/tb-tools/commands/knowledge/cli.mjs rebuild \
  --directory /path/to/local-cache --repository-directory /path/to/thunderbird-knowledge
node /path/to/tb-tools/commands/knowledge/cli.mjs search \
  --directory /path/to/local-cache --repository-directory /path/to/thunderbird-knowledge \
  --repository thunderbird 'path symbol bug review'
node /path/to/tb-tools/commands/knowledge/cli.mjs catalog \
  --directory /path/to/local-cache --repository-directory /path/to/thunderbird-knowledge \
  --repository thunderbird
```

`catalog` returns lesson titles, component scope, status, paths, and record files.
Filter it locally to browse style, tests, architecture, or breakages. It does not
publish a guide or establish policy. `show RECORD_ID` returns a complete record.
Search groups a lesson with its summary and Markdown mirrors. Separate claims
and conflicting accounts remain separate.

The SQLite database is disposable for retrieval. Rebuilding from the shared clone
does not restore private sources, past learning cursors, budgets, or vectors.
Retain an existing cache during ordinary updates. Do not delete it on each task.
`index` builds optional local semantic vectors; it needs the console's model
dependency and may download model files. Exact search works without those files.

For a console reader, set `ai.knowledge.repositoryDirectory` to the clone and
`ai.knowledge.push` to `false`. Keep `shareRepositories` empty. See the console's
`docs/knowledge.md` for writer settings and maintenance.

## Provenance and copies

`supported` means a narrow claim has checked code or kept review evidence.
`provisional` means it still needs source checks. Imported historical summaries
are provisional when the original private evidence is unavailable. A summary,
its copied lesson, and its Markdown note are one claim, not three confirmations.

`source.originalLessons`, `source.priorLessons`, `source.portableCopies`, and
Markdown `source.recordId` identify related copies. Original private IDs can be
retained for audit without including private content. Missing private evidence
must remain an explicit gap. `source.sourceAt` keeps the original evidence date;
a later publication date does not make an old claim a newer accepted practice.

Portability corrections append new records. Prefer the corrected copy for usable
URLs. Old immutable records can still contain obsolete paths to the capturing
computer. Those paths do not give a new clone access to its logs. Use retained
public push, job, source, bug, or review links. Record inaccessible sources.

## Contribute

Any agent can add a focused Markdown note using FORMAT.md and CONTRIBUTING.md.
Use a new filename. Explain what was learned, why, where it applies, source links,
validation, and uncertainty. Follow up with a separate correction if needed.
Keep raw personal or restricted evidence outside this repository.

Console writers can record evidence and submit a cited lesson batch through
`tb knowledge record --file evidence.json` and
`tb knowledge lesson --file lessons.json`. The latter uses the extraction schema
in the console's `learning.mjs`; it validates evidence IDs and exact quotes.
`tb knowledge publish` publishes eligible project lessons and syncs the shared
checkout. Normal console maintenance does this automatically within its budget.
No hand editing of content-addressed records is needed.
