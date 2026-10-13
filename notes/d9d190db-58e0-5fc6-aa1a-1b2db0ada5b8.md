<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T16:29:28Z","paths":["mailnews/base/src/MsgAsyncPrompter.sys.mjs"],"language":"JavaScript","role":"production","component":"mailnews/base/src","runtime":"privileged ES module; component registration observed","source":{"reference":"https://github.com/mozilla/releases-comm-central/blob/87d0159c7149a43253964c2cb6917939557dc799/mailnews/base/src/MsgAsyncPrompter.sys.mjs#L133-L155","revision":"87d0159c7149a43253964c2cb6917939557dc799","pairedRevisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"status":"provisional","study":"short-pipeline-test-20261013","analysisId":"js-doAsyncAuthPrompt-133","bodyHash":"fceb158347148c874ccb465c7b765f21eb71a885c183e46957037df2a7053e81","reviewer":"short_rust","reviewScope":{"id":"js-doAsyncAuthPrompt-133","level":"body-only","openWork":["Integer-key ordering and inherited enumerable keys are language implications; affected real request keys not demonstrated.","Selected caller and source-test links verified; complete dependency, ownership, dynamic receiver, and assertion coverage is not closed by this bounded packet."]}}} -->
# MsgAsyncPrompter.doAsyncAuthPrompt behavior in mailnews/base/src/MsgAsyncPrompter.sys.mjs

Returns while any prompt is active. Otherwise selects the first enumerable key by for-in, returns for a falsy key, increments count and dispatches a new runnable. Selection follows object enumeration order, not a separately maintained FIFO. Empty-string keys cannot be dispatched by this path.

## State read

- asyncPromptInProgress > 0
- Enumerated pendingPrompts keys
- hashKey truthiness

## State changed

- Increments asyncPromptInProgress before native dispatch

## Calls and triggers

- Called by queueAsyncAuthPrompt ordinary branch and run completion. Instantiates RunnablePrompter and dispatches through Services.tm.mainThread.

## Result and consumers

Undefined; queued listener observes later completion.

## Errors

No rollback if constructor/dispatch/logging throws after count increment.

## Async completion

Schedules, does not await runnable. Pauses ordinary queue while jump requests contribute positive active count.

## Ownership and cleanup

New runnable retains service; entry remains retained until run deletes it.

## Tests

- {"classification":"executes","path":"mail/components/accountcreation/test/browser/browser_verifyConfig.js","start":242,"end":261,"verifies":"OAuth request reaches normal dispatch, but queue ordering/count assertions are absent."}

## Unknowns

- Integer-key ordering and inherited enumerable keys are language implications; affected real request keys not demonstrated.

## Independent review scope

{"id":"js-doAsyncAuthPrompt-133","level":"body-only","openWork":["Integer-key ordering and inherited enumerable keys are language implications; affected real request keys not demonstrated.","Selected caller and source-test links verified; complete dependency, ownership, dynamic receiver, and assertion coverage is not closed by this bounded packet."]}

## Evidence

[mailnews/base/src/MsgAsyncPrompter.sys.mjs:140-149](https://github.com/mozilla/releases-comm-central/blob/87d0159c7149a43253964c2cb6917939557dc799/mailnews/base/src/MsgAsyncPrompter.sys.mjs#L140-L149)

```text
    let hashKey = null;
    for (hashKey in this.pendingPrompts) {
      break;
    }

    if (!hashKey) {
      return;
    }

    this.asyncPromptInProgress++;
```

## Validation and limits

A separate reader checked this body against pinned source. A mechanical check confirmed the recorded quote and line anchors. These checks do not prove every runtime target or test outcome. No product test run is claimed by this record. Newness: new.
