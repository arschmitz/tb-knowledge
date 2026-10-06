# Review formatting, syntax, style, and names

Read this for code review and local verification. For tests, repairs, and conflict
resolutions, use the sections that cover the changed files. Check both enforced
formatting and manual conventions. A formatter pass does not cover naming,
comments, architecture, or behavior. Use the knowledge workflow for source checks.

## Establish which rules apply

1. Inspect the target revision's `.editorconfig`, paired Gecko `.prettierrc.js`,
   nested Prettier configuration, `comm/eslint.config.mjs`, lint ignore lists,
   `.stylelintrc.js`, and the applicable language formatter. Configuration can
   change; do not impose values remembered from an older checkout.
2. Check generated and third-party paths before demanding manual formatting.
   Inspect manifest/resource generation and applicable exclusions. An excluded
   changed file still needs source review; an exclusion is not a clean lint result.
3. Search knowledge for this component's file/test names, CSS/DOM conventions,
   syntax decisions, comment style, and explicit exceptions. Read the evidence.
4. Compare new code with several relevant accepted siblings. Use the same module,
   UI family, test harness, and language. Record the accepted revision. A local
   unlanded patch is not evidence of an established convention.
5. Distinguish a required config rule, accepted scoped pattern, and proposed
   preference in every finding. Recommend a defensible new convention as a
   proposal when it is not yet policy. Do not call it a lint error.

Useful configuration checks from the source examined for these skills:

| Area | Observed configuration; recheck in the target checkout |
| --- | --- |
| Files | UTF-8, LF, final newline, and no trailing whitespace; patch/diff whitespace has an EditorConfig exception. |
| Shared Prettier | Two spaces, `arrowParens: "avoid"`, `trailingComma: "es5"`, width 80. |
| Shared CSS Prettier | CSS parser and width 160 override to avoid wrapping selectors. |
| Calendar Prettier | Nested `calendar/.prettierrc` uses width 100 with two spaces, LF, avoid arrow parentheses, and ES5 trailing commas. |
| EditorConfig languages | C/C++/JS/markup/CSS generally use two spaces; Python and Rust use four; Makefile families use tabs. Local formatter config remains decisive. |
| comm ESLint | `prefer-const` is enabled with the destructuring override; Mozilla rules and path-specific environments also apply. |
| comm Stylelint | Logical properties and double-colon pseudo-elements are configured. Several checks have explicit Gecko exceptions or are disabled. |

EditorConfig width and formatter width can differ. Do not report a long CSS
selector solely because the general EditorConfig value is 80. Nested configuration
can replace inherited behavior. Check the formatter's actual result for that file.
Read enabled ESLint/JSDoc rules before reporting a tag or spacing preference.
For example, the examined Mozilla JSDoc config permits both `@return` and
`@returns`; do not demand one spelling from preference alone.

## Run checks without changing an assessment

Run `git diff --check` for the exact patch, then `../mach commlint` from `comm`
with explicit changed paths. Confirm each path and applicable linter were selected.
Check ignored files and warnings. Report parser errors separately from style.
Do not substitute generic `mach lint`: it can use a different Thunderbird CSS path.
For an assessment-only task, do not use `--fix` or apply a formatter. For an
authorized edit, a focused `../mach commlint --fix PATH` can apply current rules;
inspect its diff and preserve unrelated changes. Do not reformat untouched files.

Manual checks still include indentation that hides control flow, misleading
blank-line grouping, stale disable comments, unnecessary exceptions, mixed line
endings, missing license/resource metadata, and accidental encoding characters.
Use the actual per-file rules for wrapping, quotes, semicolons, parentheses,
trailing commas, braces, import spacing, and alignment. Do not maintain a competing
handwritten formatter or demand unrelated mechanical cleanup.

## Names: inspect each namespace separately

| Name kind | Questions to answer |
| --- | --- |
| Files | Does the stem match this accepted component family? Is case exact on case-sensitive systems? Are paired UI files, imports, resources, manifests, and support files updated together? |
| System modules | Is `.sys.mjs` appropriate for this privileged module? Does a reusable exported class use its established family name? Do not rename all engine files to match one class. |
| Classes and factories | Does the name describe the role and follow accepted UpperCamelCase in this family? Is a mixin named as a mixin? Preserve required framework/platform names. |
| Functions and methods | Does the verb match the result and side effects? Does a load method start work, return data, or await completion? Do not hide async completion or destructive work behind a getter-like name. |
| Variables and booleans | Does the name identify the actual object, unit, collection, identity, or state? Are `is`, `has`, `can`, and `should` used where this family uses them? Avoid a name with the opposite meaning or a broad name for one parsed header. |
| Constants and private fields | Use this component's accepted conventions and access model. Do not add `_`, `g`, or all-caps by inference. Rename callers and documentation when changing a contract. |
| DOM IDs | Is the ID unique and stable, with the component/pane prefix where used? Follow script-addressed lowerCamelCase where supported; inspect existing dashed-ID families separately. |
| CSS classes | Does a shared class mean the same thing in every consumer? Follow dashed shared classes where supported; check legacy camelCase exceptions and selector collisions. |
| Fluent IDs | Use the accepted dashed component namespace. Keep IDs stable for unchanged meaning; apply current localization rules for changed messages. Never copy DOM naming into Fluent mechanically. |
| Test files and tasks | Keep the harness prefix and component filename family. Name the behavior and condition so a failed task identifies the scenario. A bug number alone or `test1` hides the contract. |

Check names at every reference: imports, lazy getters, chrome/resource URLs,
`moz.build`, TOML/INI manifests, selectors, `getElementById`, event handlers,
`aria-labelledby`/`aria-describedby`, tests, Fluent, and documentation. A case-only
rename may pass locally and fail on another filesystem. IDs can be public API or
persisted keys; do not rename them as cosmetic cleanup without checking consumers.

## Concrete scoped knowledge to consult

These are examples from this repository, not rules for every Thunderbird file.
Retrieve the full records and compare them with current accepted code:

- `2dddb0eea2e6da23f794a70bcb2b6360b573d13caa0a88335dfd4be4b7b12df9`:
  address-book modules such as `VCardUtils.sys.mjs` and `AddrBookCard.sys.mjs`;
  paired `aboutAddressBook.js/.xhtml`; listbox modules such as
  `tree-listbox-mixin.mjs`; `TreeListboxMixin` as a factory name.
- `049106b5b9ec1f430c775ac07d1f107bb7abd57957bb378f9969f8105a029fa0`:
  reusable Sync `CachedStore.sys.mjs` uses its exported class name and explains
  its round-trip contract. Lowercase engine module names remain a separate family.
- `cdbdc3778062595d61367b1a24fcc111ce371f12dd20f9adb526894057c264bc`:
  address-book `booksPaneCreateContact`, shared `sidebar-panel-header` and
  `icon-button`, and Fluent `books-pane-create-contact-button`. Existing `bookRow`,
  `noDelete`, and `readOnly` do not justify a blanket rename.
- `56930e346e9686a97ac5bfcedcfe86d2b0122e9c7f0b3efaaaaa7847f30a70aa`:
  AutoTreeView column IDs have an actual uniqueness/safe-character contract.
  They become selectors and row classes. Inspect the guard and its tests when
  changing columns; naming here affects behavior.
- `d781b9fa2d8e3b1654a2a32240d7e9160c1408776c546e7e4bc6846eb497c580`:
  POP3 queue names follow the connection lifecycle (`_connectionWaitingQueue`,
  `_busyConnections`, `onFree`). The same lesson explains why completion must
  wait for writing to finish, rather than a timed poll.
- `eea33a9d5620426d102ae56e7251ad877676091ee235ff32cd268d2306dfb3ac`:
  reviewed message-command tests use `KEY_Delete`, behavior names such as
  `test_shift_delete_prompt`, and assert the displayed confirmation text.

These IDs identify records in the knowledge clone or console index. A copied
skill remains usable without them, but must report missing source verification.
Retrieve only examples relevant to this task. Do not load every record listed.

## JavaScript syntax and API style beyond formatting

- Use current lint for `const`/`let`, imports, unused values, and syntax. Separately
  inspect whether a reference is intentionally mutable and who owns mutation.
- Check equality, truthiness, and defaults against real values: `0`, `false`,
  empty string, `null`, and `undefined` can mean different things. `??` and `||`
  are not interchangeable. A shorter expression must retain the old contract.
- Optional chaining is suitable when absence is valid. It must not silently skip
  a required initialized control or hide a broken invariant. A guard needs an
  intentional return/error/state outcome, not merely avoidance of an exception.
- Check operator precedence, ternary branches, Boolean negation, fall-through,
  early returns, and destructuring defaults for readable and correct meaning.
  Avoid multi-purpose expressions that obscure state updates or error handling.
- Check `async`/`await`, returned promises, event callbacks, and fire-and-forget
  work. Who observes rejection? Which operation can be replaced? Does completion
  still belong to the current item/window? A naming cleanup cannot fix that alone.
- Preserve receiver binding and listener identity when changing method/arrow
  syntax. Check callback removal, `this`, lifecycle hooks, and shared helpers.
- Follow the accepted import/lazy-load pattern in this environment. Do not import
  a privileged platform module into a content context or eagerly load expensive
  modules as a stylistic simplification.
- Prefer an existing public contract to a second near-identical helper. Trace all
  callers before extracting or widening an API. Remove temporary debug output.

The store includes proposed future syntax rules in record
`287d38a047ea2dd42245fe6505f6c6d14f1f9467033128210e36d5c5e9c5f45f`.
They include strict equality with deliberate exceptions, named async tasks,
invariant-aware optional chaining, and meaningful booleans. The record explicitly
does not establish project policy. Use its reasons to assess edited code; label
an unenforced preference as a proposal. Platform-specific inline style can be a
valid exception. Do not turn a provisional historical summary into a mandate.

## Comments and JSDoc

- Comments describe the current contract and surprising reason, constraint,
  ownership, ordering, or workaround. Avoid explaining obvious syntax or a
  superseded implementation. A keyboard shortcut or release codename can change;
  use the stable action or role when that is the real contract.
- Use short complete sentences for explanatory prose, correct spelling, and
  punctuation. Follow the local width and formatter. Preserve exact identifiers,
  URLs, required notices, quoted review text, and API terminology.
- When changing public/component interfaces, check parameter names, types,
  optional/default/null values, return value or promise, thrown/rejected errors,
  side effects, and ownership. Documentation must match actual behavior.
- Check `@typedef`, `@property`, callbacks, event payloads, and private field types
  where the class already documents them. Do not leave a stale type after a
  signature or state change. Do not demand JSDoc for every trivial local variable.
- Keep a workaround's bug reference and its current condition. Remove stale TODOs
  or justify them. A disable directive needs the narrow rule/scope and reason;
  do not suppress a new failure to avoid understanding it.
- Search the provisional review summary
  `c320e8b2c5cc4e1021c44ea1be87825f7deb8180ab0f84a34c8a5efb3dcbbb82`
  for public JSDoc/comment/localization lessons. Check its cited accepted change
  before using it as authority; original review access may be missing.

## CSS, markup, and localization

- Reuse the component's shared widgets, classes, and semantic design tokens.
  Inspect all consumers before changing a shared selector. A visually convenient
  class name can collide elsewhere. Do not copy a temporary historical rename
  without checking the current shared stylesheet.
- Check selector scope and specificity, custom-element boundaries, inheritance,
  cascade order, states, and actual rendered/composed DOM. Structural selectors
  such as `:last-child` must still target the intended control after siblings
  change. Prefer stable named hooks when structure is not the contract.
- Use logical properties under current rules. Check right-to-left layout,
  writing direction, zoom, long translations, empty/long content, local scrolling,
  and text scaling. Font-relative units suit text-dependent sizing; there is no
  blanket `rem` rule. Exact pixel geometry can have a justified platform purpose.
- Check light/dark and forced colors for borders, icons, selection, disabled,
  hover, focus, fill, and shadows. Bolt semantic `--color-*` tokens are normal
  defaults; inspect their consumer and states before flagging a token.
- Prefer reusable CSS for presentation where it fits the component. Dynamic
  geometry and Gecko chrome behavior can require inline style. Explain such an
  exception rather than banning it from one general lesson.
- Markup IDs, labels, roles, slots, `data-*`, localization attributes, and script
  selectors must agree. Do not use CSS-generated punctuation as translated text.
- Keep complete Fluent IDs discoverable in literal strings or a useful nearby
  comment for dynamic IDs. Check arguments, attributes, pluralization, access
  keys, translator comments, and whether changed meaning needs a new ID/migration
  under the current localization workflow. Do not mechanically migrate an
  unchanged string or invent translation policy from one old review.

## Test style and other languages

Review test filenames, named tasks, harness-specific assertion APIs, messages,
helper names, fixture names, and manifest entries together. Describe the expected
behavior in assertion messages. Separate values when that gives useful failure
diagnostics; do not impose one assertion per line by preference. Use actual events
or state conditions, cleanup support, and modern key descriptors where supported.
Check real prompt/status text when it is part of the requested behavior.

For C++, Rust, Python, IDL, build files, and configuration, read their current
formatters, lint, and accepted siblings. Check names, ownership, errors, comments,
and API compatibility in that language. JavaScript casing, nullability, or file
extensions do not define another language's rules. Preserve MPL notices on new
source files where that family requires them.

## Report this pass explicitly

Give `PASS`, `FAIL`, `N/A`, or `NOT_CHECKED` for applicable formatting/lint,
file/test names, symbol names, DOM/CSS/Fluent names, syntax, comments/JSDoc, and
CSS/localization style. Include the config or lesson/source and its scope.
Do not call skipped or ignored files passed. For a style comment, name the actual
line, inconsistency, applicable rule/evidence, and concrete requested wording or
code. Separate required failures, worthwhile nits, and proposed conventions.
Retain legitimate style findings even when automated formatting passes.
