# Accessibility criteria

Use this pass for every patch. Its depth follows the changed surface; its weight
equals functional review. Mark coverage as `PASS`, `FAIL`, `N/A`,
`NEEDS_MANUAL_TEST`, or `NOT_CHECKED`, with brief evidence.
Read the sections that cover the patch and explain any `N/A`. A non-UI filename
alone does not make user-facing state, localization, or lifecycle inapplicable.

## Semantics, names, and relationships

- Trace the rendered Document Object Model (DOM), the actual interactive target,
  and its nearest accessible ancestor. Prefer native controls. Check role, name,
  description, value, state and relationships. Do not label a visual child when
  the failing interactive target is its wrapper or ancestor.
- Inspect the actual accessible tree where tools permit, not only attributes.
  Check native role, computed name/description, selected/checked/expanded/disabled
  state, value and relevant relationships. An empty string, hidden label, broken
  ID reference, duplicate ID, or visual-only title can leave the control unnamed.
- Check text labels, icon-only buttons, tooltip/name differences, help/error text,
  heading structure, table/list/tree semantics, grouped controls and dialog names.
  Decorative icons should not create duplicate names. Preserve useful context for
  repeated actions such as a row's Delete button.
- Check `aria-labelledby`, `aria-describedby`, `aria-controls`, `aria-expanded`,
  and active-descendant references across rerender/close/reopen. Do not add ARIA
  that conflicts with native behavior or announces an unsupported widget model.

## Keyboard and focus
- Check Tab/Shift+Tab order, Enter/Space, composite-widget arrows, Escape, visible
  focus, pointer/keyboard parity and a screen-reader path. For dialogs, check
  initial focus, containment, focus return, every close/cancel route, cleanup and
  reopening with new data.
- Start with keyboard-only use from the preceding control. Verify entry, action,
  navigation and exit, including reverse order. Check composite-widget tab stops
  and arrow/Home/End behavior where the widget contract requires them.
- Check accessible button activation on both keyboard and pointer paths. Native
  Enter/Space behavior can differ from a synthetic `click`. Do not duplicate
  handlers so one key activates twice.
- Verify focus when an item disappears, an error appears, a menu closes, a dialog
  is cancelled, or an asynchronous operation replaces content. A stale reference
  must not return focus to a detached or hidden element.
- For custom resize, drag, reorder, or drop controls, verify an effective keyboard
  route. Focus alone is not equivalent operation. Check Escape/cancel behavior
  and feedback for the resulting order/value.
- Check disabled, hidden and inert states together. An inactive subtree should
  not keep focusable controls or receive product actions through a test helper.

## Dynamic state and lifecycle
- Check asynchronous loading, success and error announcements, localized status,
  `aria-busy`, and disabled/busy/inert behavior. Check focus when content appears,
  disappears or is replaced. Removing an alert still requires a suitable status
  mechanism when updates must be announced. Inspect scheduling priority and work
  while hidden; eager rendering must not block users or bypass partial/loading UI.
- Verify announcements correspond to the current operation. Rapid updates should
  not announce an obsolete result after a new selection or after dialog close.
  Check initial live-region creation versus updating existing text and whether
  the actual accessible target exposes busy/error/complete state.
- Preserve context and focus while partial content arrives. Check empty results,
  failures, retry, cancellation and reopening. Busy UI must communicate progress
  while allowing the intended cancel route.
- For alerts/prompts, inspect exact displayed and announced text and available
  actions. Do not replace a necessary announcement with only color or a toast
  that vanishes before it can be read.

## Visual states, layout, and localization
- Check readable labels/help/errors, zoom, reflow, scrolling, focus indicators,
  and cues that do not depend on color alone. Check forced colors and high
  contrast in all relevant states: selected, disabled, focus, hover, borders,
  icons, fills and shadows. Thunderbird Bolt semantic `--color-*` tokens are normal
  defaults; inspect the component that consumes them instead of flagging the
  token itself.
  For pane/layout changes, check empty/short content and long lists separately,
  including local scroll containment at size extremes.
- Check Fluent IDs, labels, comments, names, grammar, keyboard hints, file/format
  constraints and equivalent instructions or alternate text.
- Inspect the final consuming styles for all interactive states, rather than a
  token name alone. Forced colors can remove a background/shadow that supplied
  the only boundary. Focus must remain visible against selected/hover states.
- Test zoom and long localized labels in the changed layout. Check clipping,
  overlap, horizontal scrolling, fixed/minimum sizes, and whether a panel can
  scroll without moving an unrelated header or action outside reach.
- Check right-to-left ordering, logical spacing, access-key collisions in the
  same context, pluralization and descriptions that still explain constraints.
  Placeholder text is not a sufficient permanent label. A label/Fluent change
  can affect accessible name even when no JS code changes.
- Honor the product's reduced-motion behavior where animation changes. Verify
  essential state/action remains clear when motion is reduced or absent.

## Behavior-based accessibility tests
- Check behavior-based tests. Use available `AccessibilityUtils` helpers.
  Dynamic UI can use `startAxeMutationObserver` or
  `startAxeMutationObserverInWindow` from `AxeHelpers.sys.mjs`. Check that the
  assertions exercise the changed keyboard, focus and state path.
- Read the assertion helper and source target. Establish visibility and the
  intended selected object before interaction. A toolbar wrapper, inner button,
  hidden duplicate, and accessible ancestor can be different targets.
- Use browser `--enable-a11y-checks` for applicable runs. Inspect actual helper
  failures and composed DOM before adding labels or weakening an assertion.
  Automatic checks do not prove keyboard navigation, focus return, announcements,
  or screen-reader usability; state what needed manual confirmation.
- For dynamic axe observers, establish observation before the mutation and end
  it through the supported helper/cleanup. Inspect every relevant failure; a
  passing startup scan does not cover content added later.
- Include tests for the real role/name/state, keyboard action, focus after close,
  and stale/cleanup behavior when changed. DOM attributes alone are weaker proof
  than the operation and resulting accessible state.

## Current component checklist and report

For a new or materially changed component, read the current
[MZLA Front End Accessibility Component Checklist](https://docs.google.com/spreadsheets/d/10oMi8soyhtiOc01gfhCgFMyarhSDU3zERYt4SgVED7o/edit).
Select applicable areas for semantics, names/descriptions, keyboard, focus,
input/errors, state changes, announcements, contrast/reflow and motion. Do not
rely on an old item count. Record access gaps. Group failures by root cause;
do not paste the whole checklist into a review comment.
Use the current primary document when accessible; saved knowledge is context,
not proof that the external checklist has stayed unchanged.

Report a compact matrix for semantics/names, keyboard, focus, dynamic states,
visual/forced colors, localization, and tests. Each row names the source/control,
check or assertion, result and manual/access gap. Include blockers alongside
functional findings with the same evidence standard. Mark a genuine inapplicable
area with its reason; never mark an unrun screen-reader check as passed.

Pay special attention to stale asynchronous completion, cancellation that has
not started before replacement, partial/loading UI, close paths that bypass
cleanup, mouse-only handles/drop targets, wrapper/inner-button confusion, and
forced colors that remove a boundary or focus cue. For shared Calendar openers,
trace both feature-gated new dialogs and legacy summary-dialog routes.
