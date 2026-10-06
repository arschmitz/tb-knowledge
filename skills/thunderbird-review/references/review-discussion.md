# Read discussion and resolve every relevant concern

Use the browser for Bugzilla and Phabricator context. An API summary, revision
description, or comment count can omit inline code-change requests. Do not publish
comments or replies as part of reading them.

## Establish the exact version

Record bug/revision links, current diff/version and the exact requested patch.
Review a supplied older version when that is the task; use newer discussion as
context and identify which version each concern addresses. Download the exact raw
patch when anchors are needed, keep it outside source, and record its digest.
Recheck freshness when the user says the patch changed or questions an anchor.

## Read context efficiently and completely

1. Read bug description, acceptance criteria, linked requirements, and relevant
   comments. Follow a related bug only when it supplies a required contract,
   regression, dependency, or known fix. Keep unrelated history out of the task.
2. Read revision description, test plan, author explanation, overall comments,
   inline threads, replies, requested changes, and acceptance history.
3. Expand collapsed and outdated/resolved inline threads that bear on this patch.
   Check the actual code location and version. An outdated anchor can discuss a
   still-current contract; a resolved flag alone does not prove the fix is correct.
4. Inspect earlier stack revisions when a current comment depends on them. Do
   not review only files that already have comments.
5. Reuse saved unchanged context. Fetch only missing or updated discussion.
   Record inaccessible/private reviews and specific browser/tool failures.
   On HTTP 429, stop repeated requests and respect `Retry-After`. Do local source
   work while access is unavailable; do not invent the missing discussion.

## Build a concern ledger

| Concern | Version/location | Source and caller evidence | Check/result | Disposition |
| --- | --- | --- | --- | --- |
| Reviewer/bot/author statement | Raw patch version and anchor | Actual contract | Exact test or static proof | Valid, resolved, rejected, discussion, or unverified |

Use the author's intended behavior as a claim to check, not automatic approval.
Use a reviewer's suggestion as a hypothesis to test, not a command. For example,
a shorter expression can lose an invariant, a label on a child can miss the real
accessible wrapper, and cancellation before work starts can miss stale completion.
Trace source and use a focused experiment before endorsing those changes.

Keep unanswered actionable concerns visible. Do not repeat a concern already
fixed in the target. Explain a rejection with the contract and concrete evidence.
If part of the concern is valid, separate the accepted part from the unsupported
part. Capture accepted and rejected outcomes in knowledge when useful.

## Convert findings to useful comments

State what is wrong, when it happens, the user/code consequence, and the smallest
required action. Link evidence and use exact current/raw-diff coordinates under
the task's output rules. Do not mention an unrelated alternative just to praise
the preferred approach. Preserve quoted source text, identifiers and URLs.

Style comments identify the applicable config or scoped convention and give
specific replacement wording/code. Classify optional preferences as nits or
discussion. Architecture advice without a concrete current failure is nonblocking.
Do not omit genuine naming, grammar, comment, or formatting issues because a
formatter passed. Do not ask for a rewrite of untouched legacy files.

When replying is explicitly authorized, keep one reply attached to its exact
thread. In tb-tools, inline replies use `PHID-XCMT-*`; forward only the reply body.
Fail closed if that inline identity is unavailable. Never substitute a detached
revision comment for an intended inline reply. Confirm remote state before
retrying an uncertain post to avoid duplicate comments. Reading this reference
does not itself authorize posting.

## Report coverage

List the bug/revision versions read, inaccessible context, relevant concern
dispositions, remaining questions, and how discussion changed checks/findings.
Keep original evidence separate from interpretation and runtime proof. The report
must remain complete when a review is private or a page is rate-limited.
