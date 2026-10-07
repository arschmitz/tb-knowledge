<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:58:22.105Z","paths":["mail/base/content/widgets/folder-tree-row.mjs","mail/test/browser/folder-pane/browser_folderPaneHeader.js"],"source":{"reference":"knowledge-record:4fffd2ddef1e136ee12788d4b1ffb4bfadfb560ad40358e454cf6b00d3f0dfa4","recordId":"4fffd2ddef1e136ee12788d4b1ffb4bfadfb560ad40358e454cf6b00d3f0dfa4","status":"supported","publicationKey":"454eef6ea01a2cc4f1f2a21169e5bc0c638c12a3abfb02e0b340647e56a5d3af"}} -->
# Use the same visibility preference for visible folder columns and accessible labels

The row’s ARIA label adds total count and size only when their persisted column preference is enabled. Current tests independently wait for the expected ARIA label and check the column labels for the Favorite row. Accessible name consistency is part of this setter fix, not merely cosmetic column hiding. This is static/test-source inspection only; spoken output and focus were not observed. This note is based on source inspection. Tests were not run, and full review discussion remains pending.

Scope: mail/base/content.

## Evidence

[Lesson record](../records/4fffd2ddef1e136ee12788d4b1ffb4bfadfb560ad40358e454cf6b00d3f0dfa4.json).

- [Supporting record](../records/2eea0e995eac997c7cea37e51e79a1764f204627fe358ec8c01c784105f0b89e.json)
- [Supporting record](../records/365588b61ab6580226b32d0bd1beb60bf86a6f14a87fc913d557f5fc82c2734f.json)
- [Supporting record](../records/4be31918fa9d7660cd1fc5c66faa22fc96b2d7cc978d32db7bbef3a48eb67026.json)
- [Supporting record](../records/60b328760ea606dcafb394205f66fc36471dcf7f79a6b88a03c15be48c8ea5fd.json)
- [Supporting record](../records/9d57244a2e362c0ab99a5119dfaffb8372589b6b9c76c8bfc3f45cabe8fe83b7.json)
- [Supporting record](../records/adda3f9f8fa4defd35d4d04f082505606a29add12e36ddea8f0463bd9fe20faf.json)
- [Supporting record](../records/bf1251077240b92849843f34cd86da001f4cb68773c58c75834a7edcdd297c56.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
