<!-- knowledge: {"repository":"thunderbird","at":"2026-10-07T06:18:52.294Z","paths":["mailnews/news/src/NewsDownloader.sys.mjs"],"source":{"reference":"knowledge-record:1dfcfb3bcdbe0c8becf11ded9dcf3b7f6ed35eee9e87ac8600e45795e7fa802c","recordId":"1dfcfb3bcdbe0c8becf11ded9dcf3b7f6ed35eee9e87ac8600e45795e7fa802c","status":"supported","publicationKey":"9704cf1b4bdf3fa8591aa0b55672a27b8df6a7fda8e56e375318658434f604fd"}} -->
# Later news downloading separates server concurrency from folder order

The fixed NewsDownloader runs separate NNTP servers through Promise.all, but awaits each offline folder within a server and each article within a folder. It resets saveArticleOffline and refreshes disk size after normal completion. Those normal-path resets are not a finally guarantee if a synchronous fetch call throws. Favor this later implementation over the retired native iterator, with execution and exception cleanup still untested. This is source and test-code inspection. Complete Bugzilla and historical review timeline/inline context remain pending. No Thunderbird runtime, build, lint or live accessibility validation ran.

Scope: mailnews/news/src.

## Evidence

[Lesson record](../records/1dfcfb3bcdbe0c8becf11ded9dcf3b7f6ed35eee9e87ac8600e45795e7fa802c.json).

- [Supporting record](../records/baf72db616b56d9ae0405835e8fab09efc3bd4c79b7af8132ce6b3fbf958a89a.json)

## Validation and limits

Status: **supported**. Quoted evidence supports the claim; its interpretation still needs current-source checks.
