<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T03:58:22.086Z","paths":["mailnews/base/test/unit/test_folderCompact.js"],"source":{"reference":"knowledge-record:f6cf1ad534ceed1ef4edd5f7b288b00d3cf66deedfec06f9652f5aa7d7871fbd","recordId":"f6cf1ad534ceed1ef4edd5f7b288b00d3cf66deedfec06f9652f5aa7d7871fbd","status":"supported","publicationKey":"ed7e0360a19fb7df94108a8c00d3f416e52591258bdf14dcb336c8b7b51fff42"}} -->
# Modernize compaction tests with named tasks while retaining their shared state

Entry 1082 replaces an indirect gTestArray runner with setup and named add_task phases. The accepted test still intentionally carries gFolders and copied messages across those tasks. Each phase awaits real copy/delete listeners and compares the surviving key array before and after compaction. Use named phases and useful state assertions; the change does not imply these particular tasks are independent or safe to reorder. This note is based on source inspection. Tests were not run, and full review discussion remains pending.

Scope: mailnews/base/test.

## Evidence

[Lesson record](../records/f6cf1ad534ceed1ef4edd5f7b288b00d3cf66deedfec06f9652f5aa7d7871fbd.json).

- [Supporting record](../records/62b6cd202c622ecee6ecfb579e3f472cdd3342f78856afa08109bdc826a3da1a.json)
- [Supporting record](../records/70562347b099029e5eeea920d2849613cd73cba59faf4f4ab41f9207c72ad6f4.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
