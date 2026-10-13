# Thunderbird development workflow

These are deliberate user-directed instructions for Thunderbird work. Read this
file before source edits or Git changes. The knowledge repository works with
ordinary files and Git. No console application is required.

## Start with the instructions and current state

Read this repository's AGENTS.md and CONSUMING.md, the affected checkout's
AGENTS.md files, and the applicable task skill. Search relevant knowledge and
check it against current source. Do this before choosing an implementation or
Git operation. Follow CODE-EVIDENCE.md for code-writing decisions.

Record the task, target bug or revision, source checkout, branch, HEAD, first
parent, staged and unstaged changes, and unresolved paths. For a published
revision, check its current diff and base. A branch containing the patch is not
necessarily the branch that owns the requested change. Do not put a parent's
fix on a descendant's branch merely because that checkout is active.

Keep inspection and implementation permissions distinct. A verification request
does not authorize changes to a patch. If the user subsequently requests fixes,
apply the development workflow before making those changes. Preserve existing
work. Do not attribute pre-existing changes to this task.

## Branch names

Use `Bug-<bug number>` for a Thunderbird development branch. If that name is
already in use and a separate branch is needed, use the next numeric suffix:
`Bug-2061199_2`, `Bug-2061199_3`, and so on. Check all existing branch names before
choosing the next suffix. Do not replace this convention with a general agent
branch prefix. Keep an existing correct branch when it fits the task.

This names Thunderbird development branches. It does not rename unrelated
branches or change a prepared read-only review checkout's branch convention.
The console's `getNextBugBranchName` in `commands/graph/branches.mjs` implements
the numeric naming convention; standalone users can choose it with ordinary Git.

## Fixes to an existing patch

Create a separate `fixup! <target commit subject>` commit for requested fixes to
an existing Thunderbird patch. Use `git commit --fixup=<target commit>` and add
a useful body explaining the changes, validation, and remaining limits.
Do not amend or squash the original patch as a substitute for this fixup.

Check the exact target before committing. Put the fixup directly above the
intended target commit. Keep it within that patch's requested scope. Stage only
those files. Preserve the original patch's message and identity. Leave unrelated
branches and dependent patches unchanged unless the user requests their update.
If the work spans multiple patches, identify each owning patch before creating
its fixup; do not silently put all changes in one patch.

The console's `formatTryFixupMessage` in `commands/graph/try-repair.mjs` uses the
same fixup subject and includes detailed validation. Its Try-specific metadata
and history are not required for an ordinary local fixup. Do not invent Try
results or submit Try when the user has excluded it.

## Corrections during work

If the user points out a missed rule or wrong workflow, stop the affected action.
Read the relevant instruction and inspect the current state again. Correct the
plan before another edit or Git change. Do not continue from the rejected plan,
choose a replacement convention from memory, or treat an acknowledgement as
having repaired the work. Preserve recoverable changes while correcting the
branch or patch attribution.

## Finish the work

Check the final diff against the instructions and approved scope. Run appropriate
validation and report its actual limits. Verify the fixup's first parent, branch
name, commit message, changed paths, and working-tree status. Report the commit
and any remaining uncommitted work. Passing tests alone do not complete a request
to fix a patch. Do not leave authorized fixes uncommitted without explaining a
specific blocker.

Do not publish to Phabricator, squash fixups, or rewrite dependent history without
the required user authorization. Shared knowledge contributions follow this
repository's CONTRIBUTING.md.

## Authority and limits

The branch naming and separate-fixup requirements were explicitly reaffirmed by
the user during the D332509 correction on 2026-10-13. The requirement to use the
knowledge repository before acting and to revisit the workflow after corrections
was also explicit in that discussion. These are instructions, not automatically
learned preferences. Source helper names above are supporting implementation
references, not requirements to install the console.

Automatic learning must not edit these instructions. A later deliberate human
instruction can change them. This document gives agents a required workflow;
it does not claim to mechanically restrict a standalone chat's tools.
