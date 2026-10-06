# Accessibility criteria

Use this pass for every patch. Its depth follows the changed surface; its weight
equals functional review. Mark coverage as `PASS`, `FAIL`, `N/A`,
`NEEDS_MANUAL_TEST`, or `NOT_CHECKED`, with brief evidence.

- Trace the rendered Document Object Model (DOM), the actual interactive target,
  and its nearest accessible ancestor. Prefer native controls. Check role, name,
  description, value, state and relationships. Do not label a visual child when
  the failing interactive target is its wrapper or ancestor.
- Check Tab/Shift+Tab order, Enter/Space, composite-widget arrows, Escape, visible
  focus, pointer/keyboard parity and a screen-reader path. For dialogs, check
  initial focus, containment, focus return, every close/cancel route, cleanup and
  reopening with new data.
- Check asynchronous loading, success and error announcements, localized status,
  `aria-busy`, and disabled/busy/inert behavior. Check focus when content appears,
  disappears or is replaced. Removing an alert still requires a suitable status
  mechanism when updates must be announced. Inspect scheduling priority and work
  while hidden; eager rendering must not block users or bypass partial/loading UI.
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
- Check behavior-based tests. Use available `AccessibilityUtils` helpers.
  Dynamic UI can use `startAxeMutationObserver` or
  `startAxeMutationObserverInWindow` from `AxeHelpers.sys.mjs`. Check that the
  assertions exercise the changed keyboard, focus and state path.

For a new or materially changed component, read the current
[MZLA Front End Accessibility Component Checklist](https://docs.google.com/spreadsheets/d/10oMi8soyhtiOc01gfhCgFMyarhSDU3zERYt4SgVED7o/edit).
Select applicable areas for semantics, names/descriptions, keyboard, focus,
input/errors, state changes, announcements, contrast/reflow and motion. Do not
rely on an old item count. Record access gaps. Group failures by root cause;
do not paste the whole checklist into a review comment.

Pay special attention to stale asynchronous completion, cancellation that has
not started before replacement, partial/loading UI, close paths that bypass
cleanup, mouse-only handles/drop targets, wrapper/inner-button confusion, and
forced colors that remove a boundary or focus cue. For shared Calendar openers,
trace both feature-gated new dialogs and legacy summary-dialog routes.
