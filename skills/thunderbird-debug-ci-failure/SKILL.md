---
name: thunderbird-debug-ci-failure
description: Investigate Thunderbird Treeherder or Taskcluster failures, attribute every failed job from exact logs and source, and validate requested repairs without hiding existing or unknown failures.
---

# Debug a Thunderbird CI failure

Continuous integration (CI) runs builds and tests remotely. Start with the selected
push and task artifacts, not a red dashboard label. Keep the observed run outcome,
patch attribution and repair state separate. Use simple, direct English.

## Identify the run and evidence

- Record the requested revision, tested `comm` and Gecko revisions, parent/base,
  complete outgoing stack, push ID, every requested failed job ID, run/retry,
  platform, configuration and chunk. Verify the investigation checkout, HEAD,
  status and its relationship to the tested source. Current source and old tested
  evidence can differ; retain both identities.
- Inspect supplied saved evidence and local full logs first. Read compact indexes
  and grouped signatures before large files. Use Taskcluster artifact listings,
  task status/runs, suite-specific `errorsummary.log`, available test summaries
  and relevant `live_backing.log` sections. Excerpts are indexes, not all errors.
  Fetch missing evidence through raw artifacts and JSON APIs. Use Treeherder
  push/job IDs to identify tasks; do not infer causality from its web page.
- Record `USE_ARTIFACT`, `COMM_HEAD_REV`, `GECKO_HEAD_REV`, artifact platform and
  actual installed artifact/source identity. A task that publishes artifacts and
  one that consumes an older binary are different. Native API/JavaScript mismatch
  across unrelated tests can be a build-provenance problem.
- Read the shared knowledge clone's AGENTS.md and search exact failure signatures,
  paths, tests and symbols in `notes/` and `records/`. Recheck original evidence
  and current source. Reuse matching prior investigation and relevant existing
  parent/child fixups. Do not repeat completed analysis or duplicate another
  worker's repair. Respect access limits, HTTP 429 and `Retry-After`; cache fetched
  evidence and stop repeated failed requests.

## Account for every job

1. Keep a checklist keyed by every requested job ID. Split each job into distinct
   test/subtest/error/target signatures. Group identical signatures across jobs
   and platforms for efficient investigation, while retaining every affected ID.
2. Search the supplied comparison index first. When more comparison evidence is
   needed, inspect recent `comm-central`, `try-comm-central` and `try` pushes,
   including other authors; the console uses batches of up to 50 recent pushes.
   Group matches locally before analysis. Treeherder bug suggestions are leads:
   confirm the actual error in raw evidence.
3. A matching existing error on an independent run is evidence for `unrelated`.
   Cite its exact signature and source/run URL. The match need not have the same
   job name, base, author, platform, settings or artifact mode. Intermittent errors
   and errors across source updates can be existing. A red job name alone is not
   a match, and another run containing the same target patch is not independent
   baseline evidence. Stop reinvestigating a positively matched error; analyze
   additional unmatched errors in that job separately.
4. For an unmatched error, trace the tested patch, parent and relevant outgoing
   stack to the failing source/test. A defect in a submitted parent patch is in
   scope; it does not need a separate parent Try for attribution. Use `patch` when
   concrete source/test evidence connects the failure to that stack. Identify the
   owning commit instead of choosing the tested tip by default.
5. Inspect retry `reasonResolved`, each run's status and artifacts. Worker shutdown,
   cancellation, missing/truncated logs or incompatible provenance can leave the
   cause `unknown`. A later retry does not silently rewrite the earlier outcome.
   For max-runtime jobs, find browser-test completion and manifest summaries:
   timeout may occur after tests during profile processing.
   `*** End BrowserChrome Test Results ***` is one useful completion marker.
6. Explain every material error before assigning the job's cause. If material
   failures remain unexplained, use `unknown` and list the known parts and exact
   gap. Pursue missing evidence or a focused experiment when feasible. Never
   guess a pass to save work. Return each supplied job exactly once.

All-existing/unrelated errors mean no patch-caused failure, including build errors.
The console calls that attribution result `Pass`; the original job remains failed.
Do not require a repair or rebase for a positively matched existing error.
Reserve a `comm-central` build-failure category for raw logs proving that exact
failure on mainline; do not use it for any intermittent or infrastructure error.

## Accessibility failures

Reduce a suite-specific accessibility errorsummary into unique message, target,
test and count rows. Use the available test summary from the artifact listing;
`summary.jsonl` may exist when the expected suite-specific file does not. Separate
behavior/source buckets before changing code.

Inspect Gecko's `testing/mochitest/tests/SimpleTest/AccessibilityUtils.js`, especially
`assertCanBeClicked()`. Trace the composed click target and nearest interactive
accessible in the production DOM. Distinguish wrappers, child actions and hidden
test controls. Establish visibility before clicking. Trace command enablement,
current selection and permissions when toolbar focus changes an action's state.
Fix actual semantics/focus/behavior; do not add labels to the wrong descendant or
disable accessibility checks. Local macOS results do not prove a Linux CI repair.

## Repair when requested

Use the assigned isolated repair checkout and matching private build directory.
Recheck current source, interrupted edits, existing fixups and ownership of the
parent/child scope before editing and before publication. Repair only proven
patch-caused defects still present now. Preserve intended behavior, accessibility
and meaningful tests. Do not hide errors, weaken checks or copy obsolete fixes.

Run focused checks and matching-source builds/tests with `AUTOCLOBBER=1`. Recover
clobber or missing artifacts in the private directory before declaring a blocker.
A fresh directory needs a full Mach build before faster frontend builds. Do not
share a live writable object directory. If startup provenance cannot be settled
locally, propose a concrete matching-source full-build Try experiment and report
what was already checked. Submit only under existing task authorization.
Keep a required Rust/native compatibility block for patch-caused code until a
matching build can validate it. An existing unrelated build failure does not
create a patch repair requirement.

Choose the owning current outgoing commit with source/history/blame evidence.
Keep each fixup within that commit's scope; list exact changed and deleted paths,
each root cause, cumulative changes, checks and gaps. If current code already
fixes the old failure, give source/test evidence; do not create an empty fixup.
Keep recovery refs outside active patch discovery. Do not commit, change refs,
rebase, push or post a new Try during a diagnosis-only or source-only repair pass.
Resume authorized recoverable work through validation and the requested rerun;
stop duplicate retries or publication when ownership or outcome is uncertain.

## Deliver and retain evidence

Use the requested schema. For per-job JSON classification, return
`failures: [{id, cause, reason, evidence}]`, with `cause` equal to `patch`,
`unrelated` or `unknown`, exact job IDs and cited log/signature/source/baseline
references. Include no prose when JSON-only was requested. Otherwise give that
same complete accounting and the repair/check results in readable form.

Preserve historical verdicts and distinguish local validation, selected CI rerun,
waiting work and genuinely running work. Do not claim the CI failure is fixed
until the relevant run provides that evidence. Save reusable source-linked lessons
under the shared clone's AGENTS.md and FORMAT.md; keep restricted artifacts and
raw personal logs private. State unavailable knowledge or evidence precisely.
