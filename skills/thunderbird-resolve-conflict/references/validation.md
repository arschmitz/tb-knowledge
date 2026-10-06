# Exact local validation and build recovery

Read this before running checks. The task's checkout and mutation permissions
still apply. A command is evidence only for the source, build, paths, assertions,
and platform it actually exercised.

## Record the validation target

Keep one small record with:

- `comm` path, paired Gecko root, branch, HEAD, target, base, and dirty work.
- Production/test paths and what each check must prove.
- Gecko revision, object directory, build mode, mozconfig source, platform,
  binary path, and whether the binary/resources match the target source.
- Original author patch versus any local proving edits.
- Exact command, working directory, exit status, selected paths/tests, assertion
  result, timeout/skip/warning, and relevant log location.

Use read-only Git inspection first. For a committed target:

```sh
git status --short
git rev-parse HEAD
git show --no-patch --format=fuller TARGET
git diff --name-status BASE..TARGET
git diff --check BASE..TARGET
git ls-files -u
```

Replace uppercase examples with verified revisions. For a working-tree request,
inspect `git diff` and `git diff --cached` separately and record their combined
scope. Include untracked files only when they belong to the task. Do not replace
the actual target with HEAD or the published patch for convenience.

## Static and formatting checks

From `comm`, run `../mach commlint` on explicit changed paths. Use current target
configuration, not a generic formatter run with default settings. Confirm the
paths/languages selected and note ignored files. `no files linted` does not prove
the patch clean. Use direct syntax checks only when meaningful for that language
and environment. `node --check PATH` can parse applicable JS modules, but cannot
validate privileged imports, DOM behavior, type correctness, or Gecko runtime.

For assessment, do not use `--fix`. For authorized source edits, a focused fix
run is allowed; inspect its diff afterward. If the path performance check itself
blocks a known checkout, the configured environment may use
`MOZ_SKIP_PATH_PERFORMANCE_CHECK=1 ../mach commlint PATH`. Explain the setup
exception; do not use it to suppress source lint errors.

Check final whitespace for every relevant layer: author commit, unstaged edit,
and staged resolution. A passing committed diff check says nothing about newly
created untracked tests until they are inspected.

## Select a build that can prove the behavior

Build from the paired Gecko root, where `mach` lives. Do not run an initial build
from `comm` and accidentally target `comm/faster`. Read the active build setup
before changing it. Use the configured supported Python and toolchain.

| Changed surface | Build requirement |
| --- | --- |
| Compatible frontend resources | An established artifact build may suffice; refresh resources/manifests before testing. |
| Fresh object directory | One complete `./mach build` before `./mach build faster`. |
| C++, Rust, WebIDL, native API, build configuration | A matching normal build, or the exact supported build mode that covers the change. Faster frontend updates alone cannot prove compatibility. |
| Unknown native/artifact relationship | Inspect provenance; use a matching normal build when compatibility remains uncertain. |

Give every source worktree its own writable object directory. Never share a live
object directory between Working, Review, CI repair, or two agents. Shared compiler
caches and compatible immutable completed artifact snapshots may be reused.
Verify snapshot compatibility and then create private writable build state.
A source worktree without build configuration is not a build-capable experiment.

If a private mozconfig is required, place it outside source and derive it from the
project's supported configuration. Select that file with the normal `MOZCONFIG`
mechanism. Record the object directory and supported settings. Do not modify a
user's active mozconfig or source tree merely to run an assessment. Avoid inventing
configure flags. Discovery and a build probe are required before claiming setup.

## Recover a setup failure before declaring a blocker

Inspect the first causal diagnostic, not just the final exit status:

| Diagnostic or symptom | Required response |
| --- | --- |
| Clobber required | Retry the matching build with `AUTOCLOBBER=1` in the private object directory. |
| Missing test path/resource or stale manifest | Check path case, manifest registration and source revision; refresh/build from Gecko and retry selection. |
| `Strict mode enabled, test paths must exist` | Distinguish an invalid path from stale built tests; verify the source and built manifest. |
| `No rule to make target 'comm/faster'` | Correct the build root and finish initial build setup. |
| Artifact download/startup failure | Check artifact platform/revision and installed binary; attempt a compatible private artifact build or normal build. |
| Unsupported Python/toolchain | Use an available supported version and verify the actual executable/configuration. |
| Native JS/API mismatch | Check Gecko/comm/binary provenance; a frontend overlay cannot repair an incompatible native binary. |

Do not reset, clean, or clobber source. `AUTOCLOBBER=1` authorizes build-directory
recovery, not deletion of a checkout. Keep the first failure and replacement
command/outcome. If recovery fails, report the exact remaining external/toolchain
cause and what build-capable recovery was attempted. Do not label validation
blocked after only a source-only worktree or stale binary attempt.

## Run the test that reaches the change

Choose the harness from the current manifest and accepted siblings. Read its
head/setup helpers and relevant build registration. Use the narrowest meaningful
test and then broaden only for a concrete remaining risk or required gate.

From `comm`, typical entry points use `../mach test` with the actual test path,
or the component's explicit xpcshell/browser command. Check current `--help` and
product flags rather than assuming every filename is discoverable in every mode.
For `UNKNOWN TEST` on a Thunderbird browser test, use the full path explicitly:

```sh
../mach mochitest -f browser --subsuite thunderbird comm/REPOSITORY_RELATIVE_TEST_PATH
```

This path is relative to the Gecko source root. Replace the placeholder with the
existing test, and add current headless and `--enable-a11y-checks` options where
applicable. Do not repeatedly retry the same filename-only discovery failure.

For each run, verify:

1. The requested test was selected, rather than another file with the same stem.
2. Startup reached the behavior and intended assertions.
3. All relevant tasks completed; inspect failure and summary counts.
4. Accessibility checks covered actual interactions when applicable.
5. The process exited and the final harness result is known.
6. The source and binary were still the recorded target.

A platform skip, zero selected tests, startup error, timeout, or crash before the
assertion is not a pass. A failing regression assertion can prove detection; a
missing module or harness crash cannot. Keep known unrelated failures separate
from the target assertion outcome, with evidence.

## Proving edits and test causality

In external Review, run the unmodified author patch first. Make a minimal
uncommitted experiment only when the review permits it. Retain useful experiment
edits and show their diff separately. The result validates the experiment, not
the original patch. Assessment-only Verify must not edit source to obtain proof.

For authorized test writing, use an isolated old-behavior or deliberate-defect
experiment when feasible. Preserve unrelated work, restore only your experiment,
and rerun the final intended state. Do not revert or stash the user's patch just
to demonstrate red/green. Record the exact assertion that distinguishes behavior.

Run CodeRabbit against the actual diff when required. Resolve the configured or
discovered executable, check that executable's `--version`, and read supported
modes before selecting committed, uncommitted, or combined changes. Do not make
a commit only to feed automated review. If the tool cannot target the exact commit
or excludes part of the diff, state that gap and review it independently. Recheck
its findings with source, callers, and tests. Empty/incomplete output is not approval.

## Evidence and completion

Use a validation table with separate rows for diff/whitespace, formatting/lint,
syntax, CodeRabbit, build, focused runtime, accessibility, and selected CI jobs.
Use `PASS`, `FAIL`, `N/A`, `NOT_RUN`, or `BLOCKED` with evidence. Reserve `BLOCKED`
for an identified remaining cause after the relevant recovery attempt.

After edits, inspect final source, all diff layers, index, unmerged paths, and
unrelated work again. Rerun only checks invalidated by changes or unresolved risk.
Do not claim a different platform's CI passed from local macOS tests. Do not call
an old failed CI job repaired until the relevant rerun supplies evidence.
Save a useful new build/harness lesson with revision, diagnostic, recovery,
command, outcome, scope, and uncertainty through the knowledge workflow.
