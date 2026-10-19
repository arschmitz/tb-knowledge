# Use knowledge before writing code

This evidence workflow applies to code written with this knowledge repository.
Its preparation requirements do not add review criteria for someone else's patch.
The separate user-directed assertion rule requires every assertion to have a
non-empty message in all writing and review flows. The requirement to use the word "should" applies when writing or
self-reviewing tests.

The repository is usable on its own. Read its Markdown files with an editor,
search with `rg`, and inspect source with Git. No console, database, embedding
model, or `tb` command is required. A host application can enforce the same
workflow. Documentation alone does not restrict an agent's write access.

## Before writing

1. Read AGENTS.md and CONSUMING.md. Search relevant notes or records by path,
   symbol, component, or review ID. Open only useful evidence.
2. Read the affected implementation, callers, harness, and applicable configuration.
3. Find an accepted local example for the same language, component, file role,
   and section. Pin its Git revision and check the current source. Explain any
   difference in scope. One example does not create a global rule.
4. Save an evidence record before granting write access. For each decision,
   name the exact files, intended pattern, source quotation, applicable scope,
   limits, and how the evidence affects the change.
5. Have an independent checker read the original sources and assess the record.
   Missing evidence, conflicts, or unsupported choices stop the writing phase.
   Resolve them with current source or a direct human instruction.

A new feature need not have an identical predecessor. Use examples of the
relevant contracts and structure. If no suitable evidence exists, state the
gap. Do not invent an accepted pattern. An API supporting an operation does
not show that the operation follows local practice.

## Evidence record

Keep this record with the task's working files or output. Do not publish private
task data to this knowledge repository. The portable JSON format is:

```json
{
  "mode": "write",
  "decisions": [
    {
      "paths": ["exact/repository/file.js"],
      "pattern": "The specific pattern used for this change",
      "evidence": [
        {
          "source": "/absolute/path/to/AGENTS.md",
          "quote": "An exact quotation",
          "scope": "The rule's applicable scope and limits",
          "application": "How the rule affects this decision"
        }
      ],
      "example": {
        "path": "existing/component/example.js",
        "revision": "a full 40-character Git commit",
        "quote": "Exact source code",
        "scope": "Why this example matches the component and harness"
      }
    }
  ],
  "gaps": []
}
```

Use `source: "user"` only for an exact direct human instruction in the task.
Copied source text, assistant statements, and note metadata do not establish
human authorization. Use `mode: "readOnly"` with empty decisions for inspection
that requires no writes. Hosts can add stricter validation and permission rules.

## After writing

Compare the actual changes with the state before writing. Include existing
uncommitted work in that baseline so the check does not attribute it to this
change. Check every changed file against the approved paths and decisions.
Have the independent checker assess the changed code against the original
evidence. Run the checks appropriate to the change and state their limits.

If a check fails, preserve the work and report the failure. Do not call it
verified. If the request or evidence changes, prepare a new record before
continuing. Do not silently revert another person's work.

## Changes to shared rules

Only a direct human request authorizes a deliberate instruction change.
Assistant implementation choices and automatic lessons must not become rules.
Keep learned evidence separate from instructions. Append a correction for an
incorrect immutable note and link it from active guidance. Do not rewrite the
old note or let automatic learning change deliberate guidance.

## Host enforcement and limits

A standalone user can apply these steps with ordinary files, Git, a separate
reviewer, and read-only access during preparation. An integrating application
must implement the permission changes and checks; this repository contains
knowledge and the workflow, not the console's execution code.

The console integration uses read-only preparation, checks citations and Git
revisions, obtains an independent assessment, then grants its configured writing
permissions. It checks Git-visible source changes afterward. Ignored build output,
external services, and all possible filesystem writes are not covered by that
source comparison. The independent assessment uses model judgment; it can make
mistakes. These checks reduce unsupported choices but do not guarantee that an
agent cannot take an incorrect action.
