# Thunderbird knowledge center

This package stores evidence and builds reusable knowledge for Thunderbird work.
It runs without tb-tools. The tb-tools console is its main integration and uses
the same store, record format, learning limits, and sync implementation.

Node.js 22.13 or later and Git are required. Meaning-based search uses an optional
local model. Exact search and Git sync work without that dependency. Learning
requires an authenticated Codex CLI. Search, record, import, and sync do not call AI.

## Standalone use

This directory is a complete package. Copy it to another checkout or install it:

```sh
npm install -g /absolute/path/to/thunderbird-knowledge
tb-knowledge status
tb-knowledge search --repository thunderbird 'calendar attendee focus'
tb-knowledge show RECORD_ID
tb-knowledge record --file evidence.json
tb-knowledge watch
```

You can also run `node /path/to/knowledge/cli.mjs` without installing a command.
The default data directory is `~/.tb-tools/knowledge`. Use `--directory` to choose
another. No running console, source checkout, or tb-tools configuration is required.
The standalone command does not read `~/.tb.json`.

`watch` runs maintenance until stopped. It indexes, learns, and syncs with the
same stored budget as the console. It does not observe unrelated editor activity.
Outside tb-tools, an agent or integration must submit evidence with `record` or
the JavaScript store API. Inside tb-tools, capture and maintenance are automatic.

An evidence file contains one JSON object:

```json
{
  "repository": "thunderbird",
  "title": "Attendee focus review outcome",
  "text": "Exact observation, review feedback, and outcome. Include test limits.",
  "paths": ["calendar/base/content/example.js"],
  "source": {
    "type": "review-feedback",
    "reference": "Exact review URL or local evidence path",
    "revision": "Exact commit hash",
    "author": "Known author or reviewer"
  }
}
```

Use real values. Evidence defaults to private. Only set `visibility` to `shared`
when the destination's readers may access it. Lessons inherit evidence privacy.
Direct lesson creation through the command is rejected; extraction must validate
citations and exact quotes first. Imported and personal task records stay private.

Pass standalone settings with `--config /path/to/knowledge-settings.json`:

```json
{
  "directory": "~/.tb-tools/knowledge",
  "semantic": true,
  "importLegacy": false,
  "maxCallsPerDay": 4,
  "maxContextChars": 10000,
  "remote": "",
  "push": false,
  "shareRepositories": [],
  "command": "codex"
}
```

Readers use `push: false`. Authorized writers use `push: true`. tb-tools supplies
these same settings through `ai.knowledge` in `~/.tb.json`. Learning runs as a
bounded, read-only, temporary Codex session with native memory disabled.

## Agent instructions

Every command creates or refreshes the data directory's `AGENTS.md`. It explains
targeted retrieval, evidence checks, capture, privacy, and shared contribution
rules. The console supplies the same instructions on every turn because a file
outside a source checkout is not automatically inherited by that checkout.
For another agent, add a short pointer to this file in that project's `AGENTS.md`.
Do not copy the whole growing library into instructions or prompts.

## Shared Git data

Use a separate, initially empty Git repository for shared knowledge data. Do not
initialize it with a README. This package's source repository is separate from
that data repository. The shared data branch accepts only validated
`records/<SHA-256>.json` files. SHA-256 is a digest of the complete record content.

- Each person has a local store and their own Git credentials. Grant readers read
  access and only approved contributors write access on the Git host. A local
  `push: false` setting is not a permission boundary.
- Use `tb-knowledge sync` or automatic maintenance. Never force-push the data
  branch. A concurrent push fetches the winning state, combines both sets of
  records, and retries up to four times. Offline or exhausted retries retain local
  evidence for the next run.
- Never edit or delete a shared record. A correction is a new record with its
  evidence. Identical records use the same filename. Different evidence uses
  different files, so cooperating writers do not edit the same source file.
- Git merging does not decide truth. Preserve conflicting claims and their scope.
  A lesson supersedes another only with explicit replacement evidence in the same
  scope. Recent timestamps alone are insufficient.
- Keep SQLite indexes, model files, generated guides, `AGENTS.md`, private records,
  and local patch histories out of the shared data repository. Separate bare Git
  repositories hold private history and shared transport so private parent
  commits cannot enter the shared branch.
- Invalid remote files stop sync. They are never checked out or executed. A
  writer who bypasses these rules can break sync; the client cannot guarantee
  correct behavior by arbitrary manual Git writers.

The record format is the durable interface. Search indexes and guides can be
rebuilt. The growing corpus remains on disk; each task retrieves a bounded set.
Daily learning limits constrain AI cost. The package does not promise to capture
every fact from every tool; callers must provide useful evidence and report gaps.

## Publish the package source to GitHub

This repository contains package code, instructions, and tests. It contains no
collected knowledge or credentials. Run `npm install` and `npm test` before
publishing. Add your chosen GitHub remote and push this source repository normally.
In tb-tools, replace the local `file:../thunderbird-knowledge` dependency with your
GitHub repository URL pinned to a tested commit, then run `npm install` to update
the lockfile. No package registry is required for a Git dependency.

Use a different empty repository for shared knowledge records. Configure its URL
as `remote` in the knowledge settings. Do not point data sync at this code
repository; the sync validator intentionally rejects source files.
