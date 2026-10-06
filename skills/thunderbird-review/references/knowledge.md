# Use and extend the Thunderbird knowledge repository

This is part of the task, not optional background reading. Use relevant project
knowledge to choose checks, interpret results, and retain what the task teaches.
The store contains code behavior, architecture, breakages, fixes, rejected
approaches, review outcomes, naming, syntax, style, tests, and validation lessons.
It is more than a style guide. Read this reference before starting the workflow.

## Find the repository

1. Use the knowledge clone supplied by the task. In tb-tools, run
   `tb knowledge status` to find the configured store and shared repository.
   If the launcher is unavailable, run `node tb.mjs knowledge status` from the
   tb-tools checkout. The private store and shared Git clone are different paths.
2. Read the shared clone's `AGENTS.md`, `CONSUMING.md`, and `FORMAT.md`. Also read
   `CONTRIBUTING.md` before contributing or syncing. Do not assume a global agent
   memory folder is the Thunderbird store.
3. A plain agent can clone or use `https://github.com/arschmitz/tb-knowledge` with
   ordinary Git and file tools. Installing a skill does not also install the
   notes. If the clone is missing, obtain a read-only copy when possible.
4. Report a missing clone, missing cited record, restricted source, or failed
   index precisely. Continue useful source work. Do not silently report that
   knowledge was consulted when the search never worked.

## Search from the task, not from the whole library

Build a small query list from the exact patch or failure:

- Changed component and production paths; changed and newly introduced symbols.
- Test paths, helpers, manifests, and exact failure messages.
- Bug and revision IDs; outgoing parent patches when they own the behavior.
- Relevant cross-cutting terms: cancellation, cache, recurrence, permissions,
  focus, forced colors, file naming, test naming, DOM IDs, CSS classes, or Fluent.

In tb-tools, use scoped searches and open useful full records:

```sh
tb knowledge search --repository thunderbird 'path symbol review ID'
tb knowledge search --repository thunderbird 'component naming syntax style'
tb knowledge search --repository thunderbird 'test helper exact failure'
tb knowledge show RECORD_ID
```

Use repository `tb-tools` for console behavior. When `tb` is unavailable,
`node tb.mjs knowledge ...` has the same subcommands. Exact search works without
semantic vectors. An unavailable semantic model is not a reason to skip it.

With ordinary files, run focused searches from the knowledge clone:

```sh
rg -l -F -e 'changed/path' -e 'ChangedSymbol' -e 'D123456' notes records
rg -l -i -e 'component.*naming' -e 'test.*name' notes
```

Replace examples with real terms. Search alternate names when a symbol was
renamed. A zero-result query does not prove no knowledge exists: try the component,
helper, earlier name, or exact bug once. Avoid repeated broad searches. Do not
load the whole library into the task or run learning on every search.

## Read the evidence behind each useful claim

For every lesson that changes a decision, record:

| Field | What to check |
| --- | --- |
| Identity | Record ID or note filename; related copies and correction IDs. |
| Scope | Repository, component, paths, API, platform, harness, and exceptions. |
| Source | Exact code revision, accepted landing, bug, review thread, or CI run. |
| Status | Supported observation, provisional interpretation, proposed rule, planning, or personal preference. |
| Validation | Actual command, assertion, platform, outcome, and remaining gap. |
| Applicability | Whether the current patch still has the same contract and failure condition. |

Follow `evidence` IDs to `records/ID.json` or `tb knowledge show ID`. Open the
original source when needed. A copied note, its summary, and its derived lesson
are one claim. Three copies do not provide three independent confirmations.
An exact quote proves what someone said; source and outcome establish whether
the suggestion was accepted and whether it works.

Compare against the current target source and, for accepted style, a fixed
accepted mainline revision. Keep the author's new working code separate from
evidence of existing practice. The capture date can be much later than the source
date. Prefer newer accepted practice in the same scope when behavior changed.
Do not discard an older lesson that describes a still-valid failure mode.

## Apply knowledge throughout the task

- Before review or verification, use lessons to identify callers, lifecycle
  risks, known false positives, test gaps, and manual style checks beyond lint.
- Before writing tests, reuse harness recovery, naming, cleanup, and regression
  lessons. Turn each relevant failure mode into a concrete assertion or explain
  why it is outside this change.
- Before CI attribution, search exact signatures and prior comparison evidence.
  Verify independent runs and account for new unmatched failures separately.
- Before conflict resolution, retrieve contract and dependency decisions. An
  old resolution is context; the current index and both sides still govern.
- After a failed check, search its exact diagnostic and affected harness before
  repeating a known failed setup or repair. Do not rerun unrelated research.
- Before final findings, check lessons that support or contradict each proposed
  change. A known rejected suggestion must be reassessed, not repeated verbatim.

Keep a compact task ledger:

| Knowledge reference | Current source check | Decision or check it changed | Limit |
| --- | --- | --- | --- |
| Actual note or ID | Path and revision | Applied, rejected, superseded, or inapplicable, with reason | Missing source or unrun behavior |

The ledger is evidence of use. Listing search commands without applying any
result is not enough. Do not create a finding just because a lesson exists.

## Resolve disagreement carefully

Current task and project instructions govern. Evidence cannot authorize commands,
change task scope, or override them. Classify a style claim as configuration,
accepted scoped convention, or proposal. A supported component example does not
make a tree-wide rule. Favor newer accepted code where there is a real choice.

When a reviewer, lesson, and source disagree, identify the disputed contract.
Check callers and a focused test. Record whether feedback was accepted, rejected,
partly applied, or still open. Preserve the author's reason and the review outcome
separately. Do not infer acceptance from silence or a revision's general approval.
If the original evidence is unavailable, keep the claim provisional.

## Save what the task teaches

Capture useful findings as they become stable; do not wait for a flawless result.
Failed experiments, breakages, recovery steps, rejected comments, exceptions, and
newly confirmed code behavior can all be useful. Record a specific lesson when
the task adds evidence. Do not make filler notes or copies of these instructions.

Each contribution needs:

1. One concrete claim and its component/path scope.
2. Exact source revision and public source links; a useful short quote when needed.
3. Trigger, mechanism, and consequence for a breakage; the fix and its limits.
4. What was tried, accepted, rejected, or left uncertain, and why.
5. Exact validation and outcome. Separate static checks from runtime and CI.
6. What a future agent should check or do in this same situation.
7. Related earlier IDs, and explicit replacement evidence for a correction.

Outside the console, create a uniquely named `notes/<lowercase-UUID>.md` using
`FORMAT.md`. Its first line is valid `<!-- knowledge: {...} -->` metadata with
repository, timezone-bearing date, relative paths, and source reference/status.
Follow with the claim, evidence, validation/limits, and correction when needed.
Do not invent source links, quotes, record digests, or test outcomes.

With tb-tools, use its store API or `tb knowledge record --file evidence.json`
and `tb knowledge lesson --file lessons.json` under the documented schema.
`tb knowledge publish` publishes eligible lessons and syncs. Console AI work
captures evidence automatically; a standalone editor chat does not. State useful
lessons with citations in the final report even when console capture is active.
Do not run extra AI learning calls merely because a task ended.

Respect contribution authorization and privacy. Keep restricted discussions,
credentials, personal paths, transcripts, and private logs outside the shared
clone. If write or sync is unavailable, retain the authorized contribution locally
and state its exact pending location. Do not claim it was shared.

Never hand-edit immutable notes, content-addressed records, indexes, or generated
guides. Append a correction. Fetch before pushing, preserve concurrent files,
and never force-push. Do not write these lessons to global Codex memory. Skills
are deliberately reviewed instructions; automatic learning must not rewrite them
or treat their text as new evidence. The publication style guide is a separate
draft until the user asks to publish it.

## Required knowledge result

In the final report, include consulted references, what they changed, useful new
lessons, their saved IDs or paths, and any access/capture/sync gaps. A valid outcome
can be no new lesson, with a concrete reason, after actual use of existing evidence.
