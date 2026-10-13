<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T16:29:28Z","paths":["mailnews/base/src/MsgAsyncPrompter.sys.mjs"],"language":"JavaScript","role":"production","component":"mailnews/base/src","runtime":"privileged ES module; component registration observed","source":{"reference":"https://github.com/mozilla/releases-comm-central/blob/87d0159c7149a43253964c2cb6917939557dc799/mailnews/base/src/MsgAsyncPrompter.sys.mjs#L246-L246","revision":"87d0159c7149a43253964c2cb6917939557dc799","pairedRevisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"status":"provisional","study":"short-pipeline-test-20261013","analysisId":"js-user-result-246","bodyHash":"e3593d720fc5963eaba80bebe7bffb23a85cc3901edceb7e6b6a1ac2368e6f44","reviewer":"short_rust","reviewScope":{"id":"js-user-result-246","level":"body-only","openWork":["Nested callback shares parent behavior; not independent chain.","Selected caller and source-test links verified; complete dependency, ownership, dynamic receiver, and assertion coverage is not closed by this bounded packet."]}}} -->
# promptUsernameAndPassword fulfillment callback behavior in mailnews/base/src/MsgAsyncPrompter.sys.mjs

Assigns fulfilled private-method result into local result and returns that assigned value.

## State read

- ok callback argument

## State changed

- Enclosing result

## Calls and triggers

None recorded.

## Result and consumers

Returns ok to then-chain; synchronous wrapper reads stored result.

## Errors

Not invoked on rejection.

## Async completion

Promise fulfillment callback; no independent operation/cancellation.

## Ownership and cleanup

Closure retains result binding until reaction runs.

## Tests

- {"classification":"no-verified-link","path":"mailnews/base/src/MsgAsyncPrompter.sys.mjs","start":246,"end":246,"verifies":"No direct callback assertion."}

## Unknowns

- Nested callback shares parent behavior; not independent chain.

## Independent review scope

{"id":"js-user-result-246","level":"body-only","openWork":["Nested callback shares parent behavior; not independent chain.","Selected caller and source-test links verified; complete dependency, ownership, dynamic receiver, and assertion coverage is not closed by this bounded packet."]}

## Evidence

[mailnews/base/src/MsgAsyncPrompter.sys.mjs:246-246](https://github.com/mozilla/releases-comm-central/blob/87d0159c7149a43253964c2cb6917939557dc799/mailnews/base/src/MsgAsyncPrompter.sys.mjs#L246-L246)

```text
      .then(ok => (result = ok))
```

## Validation and limits

A separate reader checked this body against pinned source. A mechanical check confirmed the recorded quote and line anchors. These checks do not prove every runtime target or test outcome. No product test run is claimed by this record. Newness: new.
