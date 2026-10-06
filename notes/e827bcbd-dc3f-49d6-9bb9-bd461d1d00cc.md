<!-- knowledge: {"repository":"thunderbird","at":"2026-10-06T19:28:47.178Z","paths":["mailnews/base/src/nsMsgGroupView.cpp"],"source":{"reference":"https://phabricator.services.mozilla.com/D209662","status":"supported","publicationKey":"782e91dccaa7a4e6802ffe0971d4466ffeecf6fcc388ec7dac79fcfc3aaa012a"}} -->
# Recheck grouped-view indices after base deletion mutates the view

Bug 1894895 crashed in nsMsgGroupView::OnHdrDeleted after switching folders and deleting messages. The code captures viewIndexOfThread and rootDeleted before nsMsgDBView::OnHdrDeleted, which can remove a row from m_keys. The accepted patch checks both the remaining child count and IsValidIndex again before using the index or removing the dummy row; on invalid state it logs a warning and rebuilds the view. It reads GetNumChildren directly instead of NumRealChildren, whose arithmetic could underflow for an empty dummy group. A pre-mutation bounds check does not protect a post-mutation access.

Scope: Grouped message view.

Paths:

- `mailnews/base/src/nsMsgGroupView.cpp`

## Evidence

[Shared lesson record](../records/0fb2cb22c0f2be5ea7e63cd4e29165cf3c6df91af4f56ca7656129eb23de8b48.json).

- https://phabricator.services.mozilla.com/D209662
- https://bugzilla.mozilla.org/show_bug.cgi?id=1894895
- https://github.com/thunderbird/thunderbird-desktop/commit/f086dfa7e88f

Source record: `b4a9b84d27413ca29f76ca501188ab3d6dc7aacb12aa8ff767f4c4b79580961c`

~~~
if (!numChildren || !IsValidIndex(viewIndexOfThread)) {
~~~

## Validation and limits

Status: **supported**. This backfill preserves earlier findings and their uncertainty. It does not count unstudied commits as complete. Historical test outcomes remain reported outcomes. No runtime tests or builds were rerun for publication.

Some source material is an older import or lacks independent public-access confirmation. Its useful lesson is included as recorded context. Raw personal transcripts stay outside this repository. Exact earlier evidence IDs: `54f0c862c253900f14bdb0560c62baae2808cf7f678478cd9fe518b084cf39c4`, `5b7fd95b8140637be673620763847e3f821293478cf5368bc27876652a56ee93`.

## Correction

The earlier capture stayed in the private local store. This contribution places the learned claim in the shared repository. Earlier lesson records: `c148f4b2839be206de347e22d8643a202eb0458f23043928e6d7554ebcc1f2b2`.
