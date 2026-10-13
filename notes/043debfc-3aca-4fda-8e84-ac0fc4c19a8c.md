<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:37:23.628Z","paths":["parser"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-relationships-20261013","parser":"espree 10.3.0"}} -->
# firefox/parser returns relationship candidates 7405

Each row is an observed syntax site: exact path, line range, enclosing function, written receiver or target, and literal key when available. This is added relationship coverage; definitions and imports remain in the earlier maps. Runtime targets, shared object identity, callback lifetimes, and matching-name links are unresolved unless a focused behavior note verifies them. A matching event, preference, Fluent ID, selector, or method name does not prove a connection.

Role flags come from path heuristics plus the pinned third-party/generated exclusion lists. Imported and generated files are evidence of that source, not project policy. A generated marker alone is not ownership proof. The test category retains test-like call sites; the written receiver still needs verification; an assertion site does not prove which production behavior it checks or that it passed.

- parser/htmlparser/tests/mochitest/browser_viewsource.js:21-21; function=anonymous@20; role=test-path,source; runtime=unresolved; return-expression; target=content.document.body.textContent; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/browser_ysod_telemetry.js:20-20; function=anonymous@19; role=test-path,source; runtime=unresolved; return-expression; target=content.document.documentElement.innerHTML; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:216-216; function=addLevels; role=test-path,source; runtime=unresolved; return-expression; target=buf; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:132-132; function=fragmentToTestOutput; role=test-path,source; runtime=unresolved; return-expression; target=addLevels().slice(); resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:115-121; function=createFragmentWalker; role=test-path,source; runtime=unresolved; return-expression; target=elt.ownerDocument.createTreeWalker(); resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:119-119; function=anonymous@118; role=test-path,source; runtime=unresolved; return-expression; target=ConditionalExpression; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:106-106; function=docToTestOutput; role=test-path,source; runtime=unresolved; return-expression; target=addLevels().slice(); resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:78-78; function=parseTestcase; role=test-path,source; runtime=unresolved; return-expression; target=ArrayExpression; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:22-22; function=trimString; role=test-path,source; runtime=unresolved; return-expression; target=s.replace().replace(); resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_datreader.js:18-18; function=startsWith; role=test-path,source; runtime=unresolved; return-expression; target=BinaryExpression; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_web_testrunner.js:81-106; function=makeFragmentTestChecker; role=test-path,source; runtime=unresolved; return-expression; target=callback@81-106; resolution=unresolved-runtime-target
- parser/htmlparser/tests/mochitest/parser_web_testrunner.js:63-77; function=makeTestChecker; role=test-path,source; runtime=unresolved; return-expression; target=callback@63-77; resolution=unresolved-runtime-target

## Validation and limits

The file parsed as a module or script. These rows record syntax, not executed branches. Suite is excluded. Non-JavaScript sites, aliases, computed keys, dynamically constructed topics, macros, and receiver implementations need separate checks. No complete call graph, behavior coverage, listener removal pairing, ownership proof, test assertion coverage, or passing test result is claimed. Read implementations and callers before changing behavior.
