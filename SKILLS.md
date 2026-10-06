# Standalone Thunderbird skills

These are shareable versions of the Thunderbird workflows used in tb-tools and
personal agent sessions. They keep the same review and validation criteria.
They do not replace console prompts or personal skills. The console's task
permissions, checkout selection and response schema still apply to console work.

Each entrypoint requires knowledge use and contains detailed references inside
its own folder. These cover actual Thunderbird behavior, breakages and rejected
approaches, style beyond formatting, exact checks, and evidence-based completion.
The references explain what to inspect, what proves the result, and what a future
agent should retain. They are not a replacement for the repository's notes.

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

Start with that folder's `references/knowledge.md`. Find the knowledge clone,
read its AGENTS.md/CONSUMING.md, search relevant paths/symbols and lessons, follow
evidence, and compare the target with accepted source. Keep a compact decision
ledger. After work, append useful source-linked lessons through the documented
note or console API workflow and report their saved references and gaps.

## Detailed coverage

| Reference in each folder | What it requires |
| --- | --- |
| `knowledge.md` | Discovery, targeted retrieval, evidence/status/scope checks, accepted/rejected feedback, decision use, durable capture, corrections, privacy and safe sync. |
| `style-and-formatting.md` | Actual configuration and overrides; file/test/module/class/symbol/DOM/CSS/Fluent names; syntax meaning; comments/JSDoc; CSS states/tokens; localization; scoped examples from the knowledge records. |
| `accessibility.md` | Actual accessible target/tree, names/relationships, keyboard and focus, dynamic state, zoom/layout/forced colors, localization, product helpers and current component checklist. |
| `validation.md` | Exact source/diff, selected lint/test paths, private matching builds, artifact/native compatibility, recovery, actual assertions, experiments and separate local/CI evidence. |

Review and Verify also include behavior/architecture tracing and detailed browser
discussion handling. Review covers raw-diff anchors and paste-ready comments;
Verify covers read-only local assessment output. Write Tests includes harness,
fixture, task/file/manifest, async timeline, assertion, cleanup and detection
details. CI includes exact artifacts/runs, signatures, independent comparison,
causality, ownership and repair. Conflict includes index stages, orientation,
conflict classes, combined contracts, concurrent edits and precise staging.

Read only sections applicable to the task, but do not skip a required pass because
a tool passed. Every final report includes manual style and knowledge coverage
alongside behavior, accessibility and validation evidence. Specific failures and
gaps remain visible; examples do not establish global policy.

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

Check these decision cases when changing the skills:

- A formatter passes, but a new file/DOM/CSS name violates an applicable scoped
  convention: the manual pass must still produce a concrete style finding.
- A retrieved lesson is provisional or from a private local plan: it must be
  checked against source and must not be promoted to accepted project policy.
- A reviewer proposes a shorter expression that loses a null/permission/lifecycle
  contract: inspect callers and tests, then reject or refine the suggestion.
- A cancellation test cancels before work starts: strengthen its timeline so it
  detects a late stale result, and assert current state/cleanup.
- One CI error has an independent existing match and another is unexplained:
  preserve the match, investigate the other error, and retain `unknown` if needed.
- A marker-free conflict drops a required route/import/cleanup change: inspect
  both contracts, restore the dependency, and verify index plus combined behavior.
- A test path exists but a fresh worktree has no matching build: attempt private
  build-capable recovery rather than claim runtime validation is impossible.
- A task teaches a useful exception or rejected fix: append a cited contribution,
  report its location, and preserve earlier immutable evidence.

Copied common references are deliberate so every folder works by itself. When
updating `knowledge.md`, `style-and-formatting.md`, `validation.md` or
`accessibility.md`, review and apply the change to each copy. Do not replace them
with links outside an installed skill folder. Criteria review and document
validation do not substitute for measured performance on real agent tasks.

Only Markdown SKILL.md files and Markdown references are included. Indexing,
capture, learning and sync implementation stays in tb-tools. There are no bundled
executables, credentials, machine paths, private reviews or personal transcripts.
No skills are installed into a user's machine by cloning or syncing this repository.
