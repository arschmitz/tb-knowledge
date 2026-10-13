<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T16:29:28Z","paths":["xpcom/rust/moz_task/src/executor.rs"],"language":"Rust","role":"production","component":"xpcom/rust/moz_task","runtime":"Gecko native XPCOM event targets","source":{"reference":"https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/xpcom/rust/moz_task/src/executor.rs#L238-L251","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","pairedRevisions":{"thunderbird":"87d0159c7149a43253964c2cb6917939557dc799","firefox":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b"},"status":"provisional","study":"short-pipeline-test-20261013","analysisId":"rust-executor-238","bodyHash":"eb6efcb8f6f4766098cc72a3fda65ba58492e37072b82663cafa15ffb8d7bcf6","reviewer":"short_native","reviewScope":{"id":"rust-executor-238","level":"body-only","openWork":["Imported async-task internals, native scheduling targets, or exhaustive external callers remain outside this checked body-and-local-call slice.","Direct tests for all body branches and failure/cancellation cases are not established; no test was run."]}}} -->
# TaskBuilder::spawn_local behavior in xpcom/rust/moz_task/src/executor.rs

Allocates shared spawn configuration with current thread target and the original options. Gives owned future and scheduling closure to async_task, schedules initial runnable, then wraps the handle.

## State read

- self name/priority/options/future; current XPCOM thread

## State changed

- new Arc<TaskSpawnConfig>; async_task task; initial queued runnable

## Calls and triggers

- get_current_thread().expect at239; async_task::spawn_local creates runnable/handle; callback calls schedule(config.clone(), runnable); runnable.schedule triggers initial work.

## Result and consumers

AsyncTask<F::Output>; it resolves to the future output when polled successfully. Does not return a Result for dispatch failure.

## Errors

Current-thread lookup panics via expect. Dispatch errors are logged inside schedule. Cancelled underlying handle is exposed as Pending by AsyncTask::poll.

## Async completion

Initial runnable is scheduled immediately. Future is polled on target, wakes schedule more runnables. Dropping wrapper cancels by documented dependency contract; detach retains execution; cancel waits.

## Ownership and cleanup

Arc config is retained by scheduler and each runnable closure; explicit/current target has a RefPtr. Future is moved into async_task. Non-Send futures are accepted; schedule enables fallible release only when on target thread.

## Tests

- {"classification":"direct","path":"xpcom/rust/gtest/moz_task/test.rs","start":31,"end":75,"verifies":"Rust_Future asserts current main-thread state in MyFuture::poll at32 and eventual6 for spawn_local at63-64. Test source was read; no execution result is claimed."}

## Unknowns

- async-task internals and concrete native scheduling implementation not read.

## Independent review scope

{"id":"rust-executor-238","level":"body-only","openWork":["Imported async-task internals, native scheduling targets, or exhaustive external callers remain outside this checked body-and-local-call slice.","Direct tests for all body branches and failure/cancellation cases are not established; no test was run."]}

## Evidence

[xpcom/rust/moz_task/src/executor.rs:238-251](https://github.com/mozilla-firefox/firefox/blob/1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b/xpcom/rust/moz_task/src/executor.rs#L238-L251)

```text
    pub fn spawn_local(self) -> AsyncTask<F::Output> {
        let current_thread = get_current_thread().expect("cannot get current thread");
        let config = Arc::new(TaskSpawnConfig {
            name: self.name,
            priority: self.priority,
            options: self.options,
            target: SpawnTarget::EventTarget(RefPtr::new(current_thread.coerce())),
        });
        let (runnable, task) = async_task::spawn_local(self.future, move |runnable| {
            schedule(config.clone(), runnable)
        });
        runnable.schedule();
        AsyncTask::new(task)
    }
```

## Validation and limits

A separate reader checked this body against pinned source. A mechanical check confirmed the recorded quote and line anchors. These checks do not prove every runtime target or test outcome. No product test run is claimed by this record. Newness: new.
