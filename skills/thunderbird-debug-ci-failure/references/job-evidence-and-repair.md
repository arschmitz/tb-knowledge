# Investigate exact CI jobs and validate repairs

Read this for a Treeherder/Taskcluster investigation. Treat the supplied job set
as the accounting boundary. Reuse saved evidence and knowledge; fetch missing or
changed artifacts through primary APIs. Do not continue an unrelated history scan.

## Build an evidence inventory

Record push/project, tested comm and Gecko revisions, outgoing stack, target task
IDs, Treeherder job IDs, task run/retry, platform, configuration and chunk. These
identities can differ. Keep the URL and local cache location for each artifact.
Do not derive the tested revision from the current checkout alone.

For every requested job, inspect available task status/runs and artifact listings.
Typical primary Taskcluster API routes are:

```text
<Taskcluster-root>/api/queue/v1/task/<taskId>
<Taskcluster-root>/api/queue/v1/task/<taskId>/status
<Taskcluster-root>/api/queue/v1/task/<taskId>/runs/<runId>/artifacts
```

Use the root and artifact URLs actually returned by the environment. Read JSON
errors and access status. Do not guess artifact names or assume `latest` selects
the requested failed retry. Select its run explicitly. Follow pagination when
needed to locate required artifacts; do not scrape a dashboard as log evidence.

Inventory suite-specific `errorsummary.log`, test summaries, raw
`live_backing.log`, build logs and any crash/timeout artifacts. When an expected
summary is absent, inspect listings for alternatives such as `summary.jsonl`.
Preserve explicit missing-evidence records and run IDs. Cache completed evidence;
refresh unfinished tasks. Respect HTTP 429 and `Retry-After`; do not repeatedly
refetch inaccessible artifacts or review pages.

## Split jobs into real errors

Extract distinct test, subtest, message, target, and result signatures. Preserve
the literal error and source lines. Normalized grouping may remove incidental
timestamps/paths, but must not merge materially different assertions or targets.
Group the same signature across chunks/platforms and investigate it once while
retaining every affected requested ID.

Use this ledger:

| Job/run | Signature | Raw evidence | Independent existing match | Source link | Cause/gap |
| --- | --- | --- | --- | --- | --- |
| Actual requested ID | Exact test/message/target | Artifact and line/section | Push/job URL and same error | Tested/current path and owner | Patch, unrelated, or unknown |

Read context before and after the error. The final summary can hide an earlier
crash, startup failure, leak, accessibility assertion, or second failed test.
Compact evidence is a navigation index; expand the relevant raw sections when
attribution depends on them. Inspect all material signatures before classifying
a job. Another worker's full completed analysis can be reused with provenance.

## Existing-error evidence versus patch causality

Search the supplied comparison index and knowledge first. When evidence is
missing, examine recent `comm-central`, `try-comm-central`, and `try` runs in
batches, including other authors. Group signatures locally before further
requests. The console's normal comparison batches contain up to 50 recent pushes;
that is an efficiency limit, not proof of a match. Stop once a genuine independent
match is found for that signature and continue unmatched signatures.

An exact matching existing error does not need the same author, base, platform,
job label, settings, or artifact mode. Verify the failure text/target and that
the comparison run is independent of the target patch. A Treeherder bug suggestion
or another red job with the same label is only a lead. Another run containing the
same faulty outgoing patch cannot establish an unrelated baseline.

For unmatched errors, trace the tested patch and its submitted parents to the
failure. Read relevant source, tests, callers, dependency changes and provenance.
Identify the actual mechanism. A parent patch in the submitted stack can be
responsible without its own separate Try. Do not assign the cause to the tip by
default, or call it unrelated merely because the changed line is in a parent.

| Evidence | Correct decision |
| --- | --- |
| Same exact error on an independent run | `unrelated` for that signature, with match reference. |
| Tested outgoing code concretely causes the unmatched failure | `patch`, with mechanism and owning commit. |
| Several unrelated errors plus one unexplained material error | Job remains `unknown`; list the established parts and gap. |
| One concrete patch error plus other fully explained unrelated errors | `patch`, with every error accounted for. |
| Logs missing/truncated, worker cancellation, unresolved provenance | `unknown` unless other evidence settles every material cause. |
| Old failed source is repaired in current source | Retain the old attribution; separately report current repair evidence. |

Do not turn an observed failed job into a passed run. All-independent existing
errors can mean the patch attribution is `Pass` in the console, while the jobs
remain red. A generic infrastructure/intermittent error is not a mainline build
failure: that category needs raw evidence of the exact `comm-central` build error.

## Provenance, retries, timeouts, and build errors

Check `COMM_HEAD_REV`, `GECKO_HEAD_REV`, `USE_ARTIFACT`, artifact platform and
revision, installed binary, task dependencies, build mode and resource packaging.
A task that builds/publishes artifacts differs from a consumer using older native
binaries. Widespread JS/native API mismatch can reflect provenance. Inspect the
first build/compiler error, not just cascade errors or a failed final command.

For each retry, retain `reasonResolved`, start/end, status and artifact source.
Do not let a later green retry silently erase the first failure. For max-runtime,
check the last active phase: browser completion can precede profile processing or
worker timeout. Look for `*** End BrowserChrome Test Results ***`, test/manifest
summaries and subsequent work. A timeout after test completion is a different
failure mechanism from a hanging test. State exactly what completed.

## Accessibility error investigation

Group errorsummary entries by message, actual target, test and count. Trace the
composed DOM and nearest interactive accessible, including wrappers/inner buttons.
Read Gecko `AccessibilityUtils.js`, especially `assertCanBeClicked()`, and the
test's helper. Establish visible/selected/enabled state before clicking. A hidden
test control, focus-derived command flag, and production unnamed action need
different fixes. Consult the full accessibility reference and relevant knowledge.

Do not label the wrong descendant, disable a11y checks, skip the test, or weaken
assertions to conceal a failure. Fix actual semantics and interaction when source
is wrong. Fix setup when the test acts before its intended control is visible.
Keep Linux CI and local macOS evidence separate.

## Make a repair only when requested

Before editing, verify the assigned isolated checkout, current outgoing owner,
dirty/staged work, existing parent/child fixups and pending work by another actor.
Search knowledge for the exact failure and rejected repairs. Recheck whether the
historical defect is still present now. A diagnosis task does not authorize commits,
branch movement, rebase, push, review comments or a new Try.

For each remaining patch defect:

1. State the failure condition and why the owning patch causes it.
2. Pick the smallest fix preserving intent, contracts and accessibility.
3. Add meaningful focused regression coverage where the contract lacks it.
4. Check syntax, manual style/naming, commlint and the final diff.
5. Validate with matching source/binaries and the relevant private build mode.
6. Inspect final errors, prior findings and cumulative fixup scope.

Use the validation reference for private object directories, full initial builds,
`AUTOCLOBBER=1`, and build-capable recovery. Native/Rust compatibility remains a
required gap for a patch-caused native change until a matching build proves it.
An independent unrelated build failure does not create a patch repair requirement.

Keep each fixup in its owning commit's scope. Verify source/history/blame evidence
before assigning ownership; list exact changed/deleted paths. If current code
already fixes the defect, give source/test evidence and make no empty fixup.
If publication is authorized, recheck source and existing fixups immediately
before it. Confirm remote outcome before retrying an uncertain action. Keep
recovery refs outside active patch discovery. Do not duplicate another worker's fix.

Run a requested authorized rerun after local checks. Choose the relevant jobs
and record the tested source and run URLs. Keep pending, genuinely running,
completed, failed, cancelled and unsubmitted states distinct. Do not keep starting
duplicate runs when ownership or prior submission outcome is unresolved.

## Report and learn

Return every supplied job ID exactly once with `cause`, `reason`, and `evidence`
under the caller's schema. Include all material error accounting, independent
matches, ownership, repair/current-source state, exact local checks, rerun state
and remaining gaps. Use pure JSON when requested. Do not remove `unknown` to make
the result look complete.

For the console diagnosis schema, use
`{"failures":[{"id":"exact job ID","cause":"patch|unrelated|unknown","reason":"concrete cause and gaps","evidence":["exact references"]}]}`.
Add `failureCategory: "comm-central"` only with the required exact mainline build
evidence. Do not replace unknown with unrelated merely because the artifact is
inaccessible. Continue useful evidence recovery and identify the remaining gap.

For the console repair schema, return nonempty string fields `causes`, `changes`,
`validation`, and `limits`, plus the full current owning `targetHash`, source-based
`targetReason`, and `files` array of exact relative changed/deleted paths. Include
the full cumulative fixup, not just the last edit. Exclude scratch/build files.
Use the caller's supported `alreadyFixed`, `needsFreshTry`, or revised assessment
only when evidence supports that no-commit disposition; do not invent extra
schema fields or create an empty fixup. The caller owns staging/publication in a
source-only repair turn. Correct a malformed report without repeating completed
research, editing finished code, or rerunning valid tests.

Save reusable exact-signature comparisons, failure mechanisms, provenance lessons,
and successful/rejected repairs through the knowledge workflow. Keep public URLs,
revision, scope, observed run result and attribution separate. Raw private logs
remain private. A historical CI verdict is evidence for later work, not authority
to declare a future push passed.
