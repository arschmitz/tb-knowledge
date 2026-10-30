<!-- knowledge: {"repository":"thunderbird","at":"2026-10-30T15:50:03.620Z","paths":["mailnews/news/src/NntpChannel.sys.mjs"],"source":{"reference":"knowledge-record:cdafca99d2ccb3000a01772490b29b3a37bfd7addc3d07fecd775a3c4bed4c9e","recordId":"cdafca99d2ccb3000a01772490b29b3a37bfd7addc3d07fecd775a3c4bed4c9e","status":"supported","publicationKey":"632bb3c53a4eb2a3a39faac3d98448fd37ccca66f454ae6e80752e639d8102a6"}} -->
# The NNTP channel clears its retained listener after normal completion callbacks

The cache/offline pump and server article completion callbacks clear the channel's retained listener after notifying it, then mark the channel no longer pending. The listener can own a MIME converter or memory-cache tee. These are normal-path releases: preceding callbacks and state/commit operations are not enclosed by finally, so the assignments do not prove exception or cancellation cleanup. The owned landing also clears an expired-article completion path that is absent from the later accepted file.

Scope: Thunderbird NNTP channel listener lifetime.

## Evidence

[Lesson record](../records/cdafca99d2ccb3000a01772490b29b3a37bfd7addc3d07fecd775a3c4bed4c9e.json).

- [Supporting record](../records/08caec63b1d2e99a3238a969229cd34d38cf5fb670bd74e25ee107f654a5bf06.json)
- [Supporting record](../records/0f571a309f4e6060f2fb33f05650808545af0c7cc646e338f3e5393fddef9058.json)
- [Supporting record](../records/3c351fab2408ca904c933f67d618071407c79c6ac0d2f474978995b40c3281e7.json)
- [Supporting record](../records/49b4f1829e821bbba979b1d2a35e9b53ad8fb448530a9a7495cafa5c52a4b5fa.json)
- [Supporting record](../records/bfbfb765f5d1606b7998f6d9a9bf528681bc5cb86e1ce4a25ac47543ebe89f86.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
