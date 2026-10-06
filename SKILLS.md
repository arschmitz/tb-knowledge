# Standalone Thunderbird skills

These are shareable versions of the Thunderbird workflows used in tb-tools and
personal agent sessions. They keep the same review and validation criteria.
They do not replace console prompts or personal skills. The console's task
permissions, checkout selection and response schema still apply to console work.

| Task | Skill | Main result |
| --- | --- | --- |
| Review another developer's patch | [thunderbird-review](skills/thunderbird-review/SKILL.md) | Full independent and accessibility review with exact patch anchors and retained Review-checkout experiments. |
| Verify the author's local patch | [thunderbird-verify-local-patch](skills/thunderbird-verify-local-patch/SKILL.md) | Full assessment of the current local patch, without replacing or editing it. |
| Write tests | [thunderbird-write-tests](skills/thunderbird-write-tests/SKILL.md) | Focused behavior-based regression coverage, manifest registration and matching-build validation. |
| Debug a CI failure | [thunderbird-debug-ci-failure](skills/thunderbird-debug-ci-failure/SKILL.md) | Exact per-job cause accounting, existing-error matches and validated requested repairs. |
| Resolve a conflict | [thunderbird-resolve-conflict](skills/thunderbird-resolve-conflict/SKILL.md) | One coherent conflict batch that preserves both behaviors and unrelated work. |

## Use with any agent

Give the agent the selected SKILL.md path and the task. Read only that skill and
the references it calls for. Each folder contains its own needed references;
copying one folder does not require another skill or a running tb-tools console.

Supply the Working or Review `comm` checkout and paired Gecko root as appropriate,
the patch/task identity and any available evidence. Give the path to this shared
knowledge clone. The skills use relevant notes and records and save useful new
lessons. AGENTS.md and CONSUMING.md define that workflow.

The portable versions discover configured checkouts, build directories and tools
instead of embedding one person's paths. They retain the separation of external
Review and author-side Working tasks, coequal accessibility review, independent
CodeRabbit assessment, exact anchors, matching-source tests, build recovery,
complete CI accounting and guarded conflict state. An unavailable tool, source
or review is an explicit coverage gap, not invented evidence.

## Use with Codex

Copy the selected skill folder into `$CODEX_HOME/skills`, or `~/.codex/skills`
when CODEX_HOME is unset. Keep these standalone folder names. If a target folder
already exists, compare it before changing it. Do not replace a personal skill,
symlink it to these files, or change its invocation settings as part of an install.

Installed invocation examples:

```text
$thunderbird-review Review the supplied Phabricator patch in the configured Review checkout.
$thunderbird-verify-local-patch Verify my current local patch against its first parent.
$thunderbird-write-tests Add regression coverage for the specified behavior.
$thunderbird-debug-ci-failure Investigate every failed job in the supplied Try.
$thunderbird-resolve-conflict Resolve the current conflicts and leave the rebase waiting.
```

## Maintain the criteria

These instructions adapt the existing personal patch-review skill, its
accessibility and anchor references, and the console Review, Verify Local Patch,
implementation/test, CI assessment/repair and conflict workflows. Older imported
workflow lessons provide failure context; current console criteria take priority
where they differ. The CI skill retains the current existing-signature rule:
an exact independent existing error does not need an identical base or platform.

When changing a workflow, compare the standalone and specialized versions before
declaring them equivalent. Preserve the original criteria; change checkout/tool
discovery and output integration only where portability requires it. Update these
instructions deliberately. Automatic learning must not rewrite skills. Notes and
records remain immutable evidence; skill instructions are separately reviewed
documents and are not inserted into the lesson or learning indexes.

Only Markdown SKILL.md files and Markdown references are included. Indexing,
capture, learning and sync implementation stays in tb-tools. There are no bundled
executables, credentials, machine paths, private reviews or personal transcripts.
No skills are installed into a user's machine by cloning or syncing this repository.
