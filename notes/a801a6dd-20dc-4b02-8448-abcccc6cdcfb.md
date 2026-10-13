<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:37:23.628Z","paths":["mailnews"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-relationships-20261013","parser":"espree 10.3.0"}} -->
# thunderbird/mailnews ownership relationship candidates 900

Each row is an observed syntax site: exact path, line range, enclosing function, written receiver or target, and literal key when available. This is added relationship coverage; definitions and imports remain in the earlier maps. Runtime targets, shared object identity, callback lifetimes, and matching-name links are unresolved unless a focused behavior note verifies them. A matching event, preference, Fluent ID, selector, or method name does not prove a connection.

Role flags come from path heuristics plus the pinned third-party/generated exclusion lists. Imported and generated files are evidence of that source, not project policy. A generated marker alone is not ownership proof. The test category retains test-like call sites; the written receiver still needs verification; an assertion site does not prove which production behavior it checks or that it passed.

- mailnews/test/resources/PromiseTestUtils.sys.mjs:295-308; function=PromiseTestUtils.promiseFolderDeleted; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:272-285; function=PromiseTestUtils.promiseFolderAdded; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:235-260; function=PromiseTestUtils.promiseFolderNotification; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:209-223; function=PromiseTestUtils.promiseFolderEvent; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:144-144; function=onStopRequest; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:124-127; function=constructor; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:103-103; function=onStopCopy; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:64-67; function=constructor; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:43-43; function=OnStopRunningUrl; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/PromiseTestUtils.sys.mjs:25-28; function=constructor; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Promise; resolution=unresolved-runtime-target
- mailnews/test/resources/ServerTestUtils.sys.mjs:93-93; function=(top-level); role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Map; resolution=unresolved-runtime-target
- mailnews/test/resources/ServerTestUtils.sys.mjs:64-64; function=createServer; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=serverConstructors.[computed]; resolution=unresolved-runtime-target
- mailnews/test/resources/SmimeUtils.sys.mjs:67-67; function=loadCertificateAndKey; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/SmimeUtils.sys.mjs:25-25; function=viewCert; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/SmimeUtils.sys.mjs:18-18; function=setPKCS12FilePassword; role=test-path,source; runtime=privileged-module-path-candidate; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/alertTestUtils.js:457-463; function=promptPassword; role=test-path,source; runtime=unresolved; construct; target=LoginInfo; resolution=unresolved-runtime-target
- mailnews/test/resources/alertTestUtils.js:443-443; function=promptPassword; role=test-path,source; runtime=unresolved; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/alertTestUtils.js:416-422; function=promptUsernameAndPassword; role=test-path,source; runtime=unresolved; construct; target=LoginInfo; resolution=unresolved-runtime-target
- mailnews/test/resources/alertTestUtils.js:392-394; function=promptUsernameAndPassword; role=test-path,source; runtime=unresolved; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/filterTestUtils.js:81-81; function=createFilter; role=test-path,source; runtime=unresolved; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/filterTestUtils.js:68-68; function=createFilter; role=test-path,source; runtime=unresolved; construct; target=Error; resolution=unresolved-runtime-target
- mailnews/test/resources/logHelper.js:514-514; function=_wrapped_do_throw; role=test-path,source; runtime=unresolved; construct; target=_Failure; resolution=unresolved-runtime-target

## Validation and limits

The file parsed as a module or script. These rows record syntax, not executed branches. Suite is excluded. Non-JavaScript sites, aliases, computed keys, dynamically constructed topics, macros, and receiver implementations need separate checks. No complete call graph, behavior coverage, listener removal pairing, ownership proof, test assertion coverage, or passing test result is claimed. Read implementations and callers before changing behavior.
