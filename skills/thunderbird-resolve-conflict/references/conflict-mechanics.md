# Reconcile Git conflicts without losing behavior

Read the current index and operation metadata before choosing a side. Resolve the
whole requested conflict batch, not just marker blocks. Search knowledge for the
affected contracts/dependencies before editing. The current Git state is authority.

## Snapshot state and establish orientation

Record HEAD/branch, status, staged and unstaged diffs, untracked files, conflict
paths, each index stage/blob/mode, operation metadata, and active commit. Useful
read-only commands from the selected `comm` checkout:

```sh
git status --short
git ls-files -u
git diff --name-only --diff-filter=U
git diff --cached --name-status
git diff --name-status
git rev-parse --git-path rebase-merge
git rev-parse --git-path rebase-apply
git rev-parse --git-path MERGE_HEAD
git rev-parse --git-path CHERRY_PICK_HEAD
```

`--git-path` reports a location; inspect whether its actual metadata exists.
Detached HEAD alone does not establish a rebase. Inspect the current operation's
commit/onto/base information and repository status. For paths that can contain
whitespace, use NUL-delimited Git output with a parser, not shell word splitting.

For a text conflict, inspect stages and commits:

```sh
git show :1:PATH
git show :2:PATH
git show :3:PATH
git diff --cc -- PATH
```

Stage 1 is the common base, 2 is ours, 3 is theirs when present. During rebase,
ours usually represents the rebased upstream/current accumulated state and theirs
the commit being replayed. Explain the actual identities; informal branch names
can reverse that meaning. An absent stage is meaningful for additions/deletions,
not a reason to fabricate content. Check renames and modes separately.

Record the content hash of each affected working file as well as stages. Preserve
unrelated staged entries and manual edits. Keep recovery material outside source
when needed. Do not reset, clean, stash, switch, abort or rewrite history as a
shortcut. Do not move branches from assumed hashes.

## Construct one coherent behavior resolution

For each conflicting change, build this map:

| Path/change | Base behavior | Incoming intent | Replayed/local intent | Combined contract | Validation |
| --- | --- | --- | --- | --- | --- |
| Actual conflict | What existed | What one side adds/fixes | What the other adds/fixes | Both retained or justified incompatibility | Caller/test/check |

Read relevant commits, unchanged callers, tests, resource/build manifests and
knowledge decisions. Do not choose an entire side merely because it removes
markers or has newer syntax. Prefer newer accepted style only after behavior and
dependency requirements are settled.

Check specific conflict classes:

- **Independent additions:** retain both changes with correct ordering and
  registration; remove accidental duplicates without deleting a distinct contract.
- **Signature/rename changes:** update implementations, imports, lazy getters,
  callers, docs, resource URLs, selectors and tests together. A marker-free caller
  can still use the old signature.
- **Lifecycle changes:** preserve cancellation, generation guards, cleanup,
  listener identity, ready-before-show and error/busy state from both sides.
- **State/route changes:** keep related identity fields atomic and clear stale
  values. A Calendar route can include recurrence; inspect the current setter
  contract instead of separately assigning attributes by inference.
- **UI changes:** preserve actual accessible targets, names, keyboard/focus,
  selection, permissions, localized text, forced colors and legacy/feature routes.
- **Manifest/resource changes:** keep both required tests/assets/modules and the
  correct case, conditions and order. Check duplicates and removed support files.
- **Modify/delete:** explain whether the behavior moved elsewhere or still needs
  the file. Do not recreate an obsolete file or delete a needed change by default.
- **Rename/rename or rename/delete:** identify destinations and all consumers;
  stage requested old/new paths deliberately after the decision.
- **Binary, symlink, mode, or non-regular files:** inspect actual type/metadata.
  Do not invent text resolution. Report a concrete unresolved choice when needed.

If both requested contracts cannot coexist, isolate the conflict and explain
which decision is missing. Complete independent authorized resolutions meanwhile.
Do not silently drop behavior or expand the task into an unrelated refactor.

## Guard against concurrent work

Before applying a proposal, compare current index stage/blob/mode and working
content to the snapshot. If another actor changed them, read and reconcile the new
state. Do not overwrite a manual resolution using an old proposal. Recheck again
before staging and before final reporting.

Paths must remain inside the selected checkout and must not escape through a
symlink. Inspect file type before writing. A read-only console proposal returns
edits against its exact captured line ranges and source snapshot; it must not
edit/stage/continue. The caller handles application after validating the snapshot.
For insertion/deletion, use its supported representation; do not guess schema.

In a direct resolution task, apply the coherent batch and stage only the exact
requested resolved paths, including authorized deletions. Never use `git add .`,
`git add -A` without path scope, or a whole-tree checkout of ours/theirs. Preserve
pre-existing staged work and show the resolution's scope separately where possible.

## Validate the combined result

1. Scan the conflict paths for physical line-anchored `<<<<<<<`, `=======`, and
   `>>>>>>>` markers. Inspect matches in context: a legitimate separator elsewhere
   does not establish a Git conflict.
2. Recheck `git ls-files -u` and the full requested conflict list. Marker removal
   does not resolve the index, and a staged file does not prove its behavior.
3. Inspect unstaged and staged combined diffs against both sides/base. Explain
   each contract retained and any deliberate replacement.
4. Check imports, signatures, names/case, manifests/resources, localization,
   syntax, manual style, and `../mach commlint` on resolved paths.
5. Run `git diff --check` and `git diff --cached --check` as applicable.
6. Run focused tests for the combined behavior, including keyboard/focus/a11y
   when affected. Use matching-source private builds and recovery from the
   validation reference. A setup failure is not a test outcome.
7. Recheck state and unrelated staged entries immediately before completion.

For a rebase, inspect relevant surrounding stack dependencies, not just the
current replayed commit. If source requires an additional change outside the
requested conflict paths, explain that dependency and apply only within the
task's authorization. Do not claim complete resolution while a required import
or public contract remains broken.

Stop at resolved/staged/validated state unless advancement is authorized. Do not
run `git rebase --continue`, `git merge --continue`, or
`git cherry-pick --continue` just because all conflicts are staged. If ref/history
repair is separately requested, use actual reflogs and expected-old-value guards
after checking dependent refs and retaining recovery evidence.

## Deliver and learn

Report exact resolved/staged/deleted paths, remaining unmerged entries, the
combined diff, behaviors retained from each side, checks and gaps, unrelated work
preserved, and whether the sequencer was left waiting or advanced by authorization.
Capture useful dependency/contract lessons with revisions, both intents,
resolution reason and validation. A generic note saying markers were removed
does not teach a future agent how the code works.
