<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["devtools/client/debugger/src/workers/parser/tests/fixtures/resolveToken.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/arrow-function.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/binding-types.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/block-statement.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-declaration.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-expression.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-property.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/complex-nesting.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/expressions.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/flowtype-bindings.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/fn-body-lex-and-nonlex.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/for-loops.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/function-declaration.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/function-expression.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/jsx-component.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/out-of-order-declarations.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/pattern-declarations.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/simple-module.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/switch-statement.js","devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/try-catch.js","devtools/client/debugger/src/workers/parser/tests/fixtures/statements.js","devtools/client/debugger/src/workers/parser/tests/fixtures/thisExpression.js","devtools/client/debugger/src/workers/parser/tests/fixtures/var.js","devtools/client/debugger/src/workers/parser/tests/getScopes.spec.js","devtools/client/debugger/src/workers/parser/tests/helpers/index.js","devtools/client/debugger/src/workers/parser/tests/mapBindings.spec.js","devtools/client/debugger/src/workers/parser/tests/mapExpression.spec.js","devtools/client/debugger/src/workers/parser/tests/mapOriginalExpression.spec.js","devtools/client/debugger/src/workers/parser/tests/sources.spec.js","devtools/client/debugger/src/workers/parser/utils/ast.js","devtools/client/debugger/src/workers/parser/utils/getFunctionName.js","devtools/client/debugger/src/workers/parser/utils/helpers.js","devtools/client/debugger/src/workers/parser/utils/parse-script-tags/customParse.js","devtools/client/debugger/src/workers/parser/utils/parse-script-tags/index.js","devtools/client/debugger/src/workers/parser/utils/parse-script-tags/parseScriptFragment.js","devtools/client/debugger/src/workers/parser/utils/tests/ast.spec.js","devtools/client/debugger/src/workers/parser/worker.js","devtools/client/debugger/src/workers/pretty-print/index.js","devtools/client/debugger/src/workers/pretty-print/pretty-fast.js","devtools/client/debugger/src/workers/pretty-print/tests/prettyFast.spec.js","devtools/client/debugger/src/workers/pretty-print/worker.js","devtools/client/debugger/src/workers/search/get-matches.js","devtools/client/debugger/src/workers/search/index.js","devtools/client/debugger/src/workers/search/project-search.js","devtools/client/debugger/src/workers/search/tests/get-matches.spec.js","devtools/client/debugger/src/workers/search/worker.js","devtools/client/debugger/test/mochitest/browser_dbg-async-stepping.js","devtools/client/debugger/test/mochitest/browser_dbg-asyncstacks.js","devtools/client/debugger/test/mochitest/browser_dbg-audiocontext.js","devtools/client/debugger/test/mochitest/browser_dbg-backgroundtask-debugging.js","devtools/client/debugger/test/mochitest/browser_dbg-bfcache.js","devtools/client/debugger/test/mochitest/browser_dbg-blackbox-all.js","devtools/client/debugger/test/mochitest/browser_dbg-blackbox-original.js","devtools/client/debugger/test/mochitest/browser_dbg-blackbox.js","devtools/client/debugger/test/mochitest/browser_dbg-breaking-from-console.js","devtools/client/debugger/test/mochitest/browser_dbg-breaking.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoint-skipping-console.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoint-skipping.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-actions.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-columns.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-functional.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-shortcut.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-source-maps.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-ui-state.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-debugger-statement.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-duplicate-functions.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-in-evaled-sources.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-list.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-popup.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-reloading-with-source-changes.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-reloading.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-same-file-per-target.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-scroll-to-log.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-sourcemap-with-sections.js","devtools/client/debugger/test/mochitest/browser_dbg-breakpoints.js","devtools/client/debugger/test/mochitest/browser_dbg-browser-toolbox-unselected-pause.js","devtools/client/debugger/test/mochitest/browser_dbg-browser-toolbox-workers.js","devtools/client/debugger/test/mochitest/browser_dbg-call-stack.js","devtools/client/debugger/test/mochitest/browser_dbg-chrome-create.js","devtools/client/debugger/test/mochitest/browser_dbg-console-async.js","devtools/client/debugger/test/mochitest/browser_dbg-console-eval.js","devtools/client/debugger/test/mochitest/browser_dbg-console-link.js","devtools/client/debugger/test/mochitest/browser_dbg-console-map-bindings.js","devtools/client/debugger/test/mochitest/browser_dbg-console.js","devtools/client/debugger/test/mochitest/browser_dbg-content-script-sources.js","devtools/client/debugger/test/mochitest/browser_dbg-continue-to-here-click.js","devtools/client/debugger/test/mochitest/browser_dbg-continue-to-here.js","devtools/client/debugger/test/mochitest/browser_dbg-custom-formatters.js","devtools/client/debugger/test/mochitest/browser_dbg-debug-line.js","devtools/client/debugger/test/mochitest/browser_dbg-debugger-buttons.js","devtools/client/debugger/test/mochitest/browser_dbg-dom-mutation-breakpoints-fission.js","devtools/client/debugger/test/mochitest/browser_dbg-dom-mutation-breakpoints.js","devtools/client/debugger/test/mochitest/browser_dbg-eager-eval-skip-pause.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-exception.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-gutter.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-highlight.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-horizontal-scroll.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-mode.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-scroll.js","devtools/client/debugger/test/mochitest/browser_dbg-editor-select.js","devtools/client/debugger/test/mochitest/browser_dbg-ember-original-variable-mapping-notifications.js","devtools/client/debugger/test/mochitest/browser_dbg-es-module-worker.js","devtools/client/debugger/test/mochitest/browser_dbg-es-module.js","devtools/client/debugger/test/mochitest/browser_dbg-eval-throw.js","devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints-fission.js","devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints-unsupported.js","devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints.js","devtools/client/debugger/test/mochitest/browser_dbg-event-handler.js","devtools/client/debugger/test/mochitest/browser_dbg-expressions-error.js","devtools/client/debugger/test/mochitest/browser_dbg-expressions-focus.js","devtools/client/debugger/test/mochitest/browser_dbg-expressions-thread.js","devtools/client/debugger/test/mochitest/browser_dbg-expressions-watch.js","devtools/client/debugger/test/mochitest/browser_dbg-expressions.js","devtools/client/debugger/test/mochitest/browser_dbg-extension-inspectedWindow-debugger-statement.js","devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-breakpoint.js","devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-pause-exceptions.js","devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-sources.js","devtools/client/debugger/test/mochitest/browser_dbg-fission-project-search.js","devtools/client/debugger/test/mochitest/browser_dbg-fission-switch-target.js","devtools/client/debugger/test/mochitest/browser_dbg-gc-breakpoint-positions.js","devtools/client/debugger/test/mochitest/browser_dbg-gc-sources.js","devtools/client/debugger/test/mochitest/browser_dbg-go-to-line.js","devtools/client/debugger/test/mochitest/browser_dbg-html-breakpoints.js","devtools/client/debugger/test/mochitest/browser_dbg-idb-run-to-completion.js","devtools/client/debugger/test/mochitest/browser_dbg-iframes.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-cache.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions-inline-script.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions-position.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-preview.js","devtools/client/debugger/test/mochitest/browser_dbg-inline-script-offset.js","devtools/client/debugger/test/mochitest/browser_dbg-inspector-integration.js","devtools/client/debugger/test/mochitest/browser_dbg-keyboard-navigation.js","devtools/client/debugger/test/mochitest/browser_dbg-keyboard-shortcuts-modal.js","devtools/client/debugger/test/mochitest/browser_dbg-keyboard-shortcuts.js","devtools/client/debugger/test/mochitest/browser_dbg-layout-changes.js","devtools/client/debugger/test/mochitest/browser_dbg-link-reload.js","devtools/client/debugger/test/mochitest/browser_dbg-log-events.js","devtools/client/debugger/test/mochitest/browser_dbg-log-point-mapping.js","devtools/client/debugger/test/mochitest/browser_dbg-log-points-workers.js","devtools/client/debugger/test/mochitest/browser_dbg-log-points.js","devtools/client/debugger/test/mochitest/browser_dbg-many-breakpoints-same-line.js","devtools/client/debugger/test/mochitest/browser_dbg-merge-scopes.js","devtools/client/debugger/test/mochitest/browser_dbg-message-run-to-completion.js","devtools/client/debugger/test/mochitest/browser_dbg-minified.js","devtools/client/debugger/test/mochitest/browser_dbg-navigation-when-paused.js","devtools/client/debugger/test/mochitest/browser_dbg-navigation.js","devtools/client/debugger/test/mochitest/browser_dbg-no-duplicate-breakpoints-on-frame-reload.js","devtools/client/debugger/test/mochitest/browser_dbg-old-breakpoint.js","devtools/client/debugger/test/mochitest/browser_dbg-outline-filter.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/devtools JavaScript function map 92

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### devtools/client/debugger/src/workers/parser/tests/fixtures/resolveToken.js

Blob: `4660f0f568bed932265dc276e9a78479682d4fa4`. Role: test-path,source. Parse: module.

- getA @4-6; FunctionDeclaration; parameters=0; async=false; generator=false
- setB @8-10; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @12-19; FunctionExpression; parameters=2; async=false; generator=false
- insideClosure @14-16; FunctionDeclaration; parameters=2; async=false; generator=false
- withMultipleScopes @21-40; FunctionDeclaration; parameters=0; async=false; generator=false
- innerScope @23-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/arrow-function.js

Blob: `4ec72fd45063a0900051b354cc108d2c31e0d09e`. Role: test-path,source. Parse: module.

- outer @3-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-10; FunctionExpression; parameters=0; async=false; generator=false
- inner @7-9; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/binding-types.js

Blob: `8c9cc05d1d6c1033e9b04500578fcd83b1001a2b`. Role: test-path,source. Parse: module.

- fn @6-6; FunctionDeclaration; parameters=0; async=false; generator=false
- method @8-10; FunctionExpression; parameters=0; async=false; generator=false
- inner @17-20; FunctionExpression; parameters=0; async=false; generator=false
- blockFn @23-23; FunctionDeclaration; parameters=0; async=false; generator=false
- Class cls @7-11
- Module  @1; ImportDeclaration
- Module  @2; ImportDeclaration
- Module  @3; ImportDeclaration
- Module  @4; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/block-statement.js

Blob: `5e64d1180f396cd202e93cae1936e487123331ea`. Role: test-path,source. Parse: module.

- third @7-7; FunctionDeclaration; parameters=0; async=false; generator=false
- Class Fourth @8-8

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-declaration.js

Blob: `1c2c74dcbc471f21ffa6c0e3f74cf4246fa6985b`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-expression.js

Blob: `16b6841d7187b473744907d1d5355e3532898684`. Role: test-path,source. Parse: module.

- method @4-10; FunctionExpression; parameters=0; async=false; generator=false
- m @6-8; FunctionExpression; parameters=0; async=false; generator=false
- Class Outer @3-11
- Class (anonymous) @5-9

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/class-property.js

Blob: `a80cad3a87fc9f69caea6d2a9d828715c44873a6`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/complex-nesting.js

Blob: `40763f556fd78aaa423399d9ae35056926289fb6`. Role: test-path,source. Parse: module.

- named @1-29; FunctionDeclaration; parameters=3; async=false; generator=false
- root @10-26; FunctionDeclaration; parameters=0; async=false; generator=false
- fn @11-23; FunctionDeclaration; parameters=1; async=false; generator=false
- arrow @18-21; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/expressions.js

Blob: `6698acd8e8c601b4da0f7ce0b44415f5829b5ebb`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/flowtype-bindings.js

Blob: `385797c044cd26e00aa9268e9646849d97a34028`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/fn-body-lex-and-nonlex.js

Blob: `a7f6d7670a18928112537cfa3b8e3bd0d6112c8e`. Role: test-path,source. Parse: module.

- fn @1-5; FunctionDeclaration; parameters=0; async=false; generator=false
- fn2 @7-11; FunctionDeclaration; parameters=0; async=false; generator=false
- nonlex @8-8; FunctionDeclaration; parameters=0; async=false; generator=false
- fn3 @13-17; FunctionDeclaration; parameters=0; async=false; generator=false
- fn4 @19-23; FunctionDeclaration; parameters=0; async=false; generator=false
- nonlex @20-20; FunctionDeclaration; parameters=0; async=false; generator=false
- Class Thing @21-21
- Class Thing @15-15

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/for-loops.js

Blob: `747eeeae7da5481fc90eaba8b450b035a2f4a419`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/function-declaration.js

Blob: `759374b437c6a302c099734ccd0f235320dd9677`. Role: test-path,source. Parse: module.

- outer @3-3; FunctionDeclaration; parameters=1; async=false; generator=false
- middle @6-10; FunctionDeclaration; parameters=1; async=false; generator=false
- inner @7-7; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/function-expression.js

Blob: `436413533e4dba956b73b388d7bc34000e73b951`. Role: test-path,source. Parse: module.

- fn @3-3; FunctionExpression; parameters=1; async=false; generator=false
- withName @5-7; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/jsx-component.js

Blob: `ffe1c1dfce0b12a7cd307e05d3d120636257c0e2`. Role: test-path,source. Parse: module.

- Module  @1; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/out-of-order-declarations.js

Blob: `4f36d9fc387ed55cf59665c175bdff769f8e9960`. Role: test-path,source. Parse: module.

- root @3-19; FunctionDeclaration; parameters=0; async=false; generator=false
- callback @10-16; FunctionDeclaration; parameters=0; async=false; generator=false
- fn @15-15; FunctionDeclaration; parameters=0; async=false; generator=false
- Module ./src/mod @21; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/pattern-declarations.js

Blob: `6810ef4614f043a9cb6bc84684cd5c12d804ec53`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/simple-module.js

Blob: `b25cc7a8633ce8b3aee96a43ffc2728b21289778`. Role: test-path,source. Parse: module.

- fn @9-9; FunctionDeclaration; parameters=0; async=false; generator=false
- Module foo @1; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/switch-statement.js

Blob: `7163c3811d14ea00c7cb237c005c6afa563796d2`. Role: test-path,source. Parse: module.

- two @17-17; FunctionDeclaration; parameters=0; async=false; generator=false
- Class three @21-21

### devtools/client/debugger/src/workers/parser/tests/fixtures/scopes/try-catch.js

Blob: `8ccf4db592f2793eeaf629d007ffd0619d887ef4`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/fixtures/statements.js

Blob: `f2c113570e98ff462e52ed4df9efd5cb5af966bd`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/fixtures/thisExpression.js

Blob: `dd398db42611e6cc57f4da307418d2fce5284ec4`. Role: test-path,source. Parse: module.

- constructor @2-6; FunctionExpression; parameters=0; async=false; generator=false
- bar @8-10; FunctionExpression; parameters=0; async=false; generator=false
- Class Test @1-11

### devtools/client/debugger/src/workers/parser/tests/fixtures/var.js

Blob: `509ad368e87d12c86f184d703a09ec7873f33c2c`. Role: test-path,source. Parse: module.


### devtools/client/debugger/src/workers/parser/tests/getScopes.spec.js

Blob: `a2d394ae96f81163cbc0ea9afe92f279ef9e0044`. Role: test-path,source. Parse: module.

- (anonymous) @12-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ../getScopes @6; ImportDeclaration
- Module ./helpers @7; ImportDeclaration
- Module jest-in-case @8; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/helpers/index.js

Blob: `47c358ae6656b3c8afc0bfb0ac894424812cc7f2`. Role: test-path,source. Parse: module.

- getFixture @12-17; FunctionDeclaration; parameters=2; async=false; generator=false
- getSourceContent @19-37; FunctionDeclaration; parameters=2; async=false; generator=false
- getSource @39-43; FunctionDeclaration; parameters=2; async=false; generator=false
- populateSource @45-57; FunctionDeclaration; parameters=2; async=false; generator=false
- getOriginalSource @59-61; FunctionDeclaration; parameters=2; async=false; generator=false
- getOriginalSourceWithContent @63-72; FunctionDeclaration; parameters=2; async=false; generator=false
- populateOriginalSource @74-86; FunctionDeclaration; parameters=2; async=false; generator=false
- Module fs @5; ImportDeclaration
- Module path @6; ImportDeclaration
- Module ../../../../utils/test-mockup @8; ImportDeclaration
- Module ../../sources @9; ImportDeclaration
- Module ../../../../utils/async-value @10; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/mapBindings.spec.js

Blob: `3731ac1dd5c4a15b6bd3eeb13e9571edcc9f4b63`. Role: test-path,source. Parse: module.

- format @11-13; FunctionDeclaration; parameters=1; async=false; generator=false
- excludedTest @15-22; FunctionDeclaration; parameters=1; async=false; generator=false
- includedTest @24-31; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @33-161; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ../mapBindings @5; ImportDeclaration
- Module ../utils/ast @6; ImportDeclaration
- Module jest-in-case @7; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/mapExpression.spec.js

Blob: `45d7b9531d1ccf7b86a8532885ac36053f55f128`. Role: test-path,source. Parse: module.

- test @9-31; FunctionDeclaration; parameters=1; async=false; generator=false
- formatAwait @33-35; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @37-876; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ../mapExpression @5; ImportDeclaration
- Module prettier @6; ImportDeclaration
- Module jest-in-case @7; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/mapOriginalExpression.spec.js

Blob: `4949d65cd9bc02510755f22e2b36184ad129c348`. Role: test-path,source. Parse: module.

- formatOutput @8-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mapOriginalExpression @13-14; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @16-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-65; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @67-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @81-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ../mapExpression @5; ImportDeclaration
- Module prettier @6; ImportDeclaration

### devtools/client/debugger/src/workers/parser/tests/sources.spec.js

Blob: `e84ae4ad22786f4d2f53cae64e44ad5c714e1322`. Role: test-path,source. Parse: module.

- (anonymous) @7-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ../sources @5; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/ast.js

Blob: `6bd3efe538915582e2c7e4b203b1910caf41f38b`. Role: source. Parse: module.

- _parse @12-17; FunctionDeclaration; parameters=2; async=false; generator=false
- parse @66-79; FunctionDeclaration; parameters=2; async=false; generator=false
- htmlParser @83-85; FunctionDeclaration; parameters=1; async=false; generator=false
- vueParser @88-93; FunctionDeclaration; parameters=1; async=false; generator=false
- parseVueScript @94-115; FunctionDeclaration; parameters=1; async=false; generator=false
- parseConsoleScript @117-138; FunctionDeclaration; parameters=1; async=false; generator=false
- parseScript @140-142; FunctionDeclaration; parameters=2; async=false; generator=false
- getAst @144-189; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @174-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clearASTs @191-195; FunctionDeclaration; parameters=1; async=false; generator=false
- replaceNode @197-209; FunctionDeclaration; parameters=2; async=false; generator=false
- Module ./parse-script-tags @5; ImportDeclaration
- Module @babel/parser @6; ImportDeclaration
- Module @babel/types @7; ImportDeclaration
- Module ../sources @8; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/getFunctionName.js

Blob: `1fe85a5c697383c6011580e867f016f9e794e224`. Role: source. Parse: module.

- getFunctionName @10-96; FunctionDeclaration; parameters=2; async=false; generator=false
- Module @babel/types @5; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/helpers.js

Blob: `91503dafd0f222bf865cd37c3b1026f7c07eb390`. Role: source. Parse: module.

- isFunction @7-14; FunctionDeclaration; parameters=1; async=false; generator=false
- isAwaitExpression @16-23; FunctionDeclaration; parameters=1; async=false; generator=false
- isYieldExpression @25-32; FunctionDeclaration; parameters=1; async=false; generator=false
- getMemberExpression @34-54; FunctionDeclaration; parameters=1; async=false; generator=false
- _getMemberExpression @35-50; FunctionDeclaration; parameters=2; async=false; generator=false
- getVariables @56-86; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @71-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addPatternIdentifiers @98-111; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @101-101; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addIdentifiers @113-127; FunctionDeclaration; parameters=3; async=false; generator=false
- isTopLevel @131-133; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @132-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- nodeLocationKey @135-137; FunctionDeclaration; parameters=1; async=false; generator=false
- Module @babel/types @5; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/parse-script-tags/customParse.js

Blob: `5c7fed480da3c6fc273aa4098fdb7a5478e1ae28`. Role: source. Parse: module.

- getType @17-27; FunctionDeclaration; parameters=1; async=false; generator=false
- getCandidateScriptLocations @29-68; FunctionDeclaration; parameters=2; async=false; generator=false
- parseScripts @70-72; FunctionDeclaration; parameters=2; async=false; generator=false
- calcLineAndColumn @74-83; FunctionDeclaration; parameters=2; async=false; generator=false
- adjustForLineAndColumn @85-94; FunctionDeclaration; parameters=2; async=false; generator=false
- parseScriptTags @96-129; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @100-106; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Module @babel/types @8; ImportDeclaration
- Module ./parseScriptFragment.js @10; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/parse-script-tags/index.js

Blob: `e85d0cdc53d1953c5655af7cad26e461cb2536da`. Role: source. Parse: module.

- parseScript @17-31; FunctionDeclaration; parameters=1; async=false; generator=false
- parseScripts @33-35; FunctionDeclaration; parameters=2; async=false; generator=false
- extractScriptTags @37-47; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @38-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- parseScriptTags @49-51; FunctionDeclaration; parameters=2; async=false; generator=false
- Module @babel/types @8; ImportDeclaration
- Module @babel/parser @9; ImportDeclaration
- Module ./customParse.js @11; ImportDeclaration

### devtools/client/debugger/src/workers/parser/utils/parse-script-tags/parseScriptFragment.js

Blob: `11dfe4dc1b2ce8c3b14b9e133a3a56dafb97eca2`. Role: source. Parse: module.

- parseToken @10-24; FunctionDeclaration; parameters=2; async=false; generator=false
- parseAttributes @26-108; FunctionDeclaration; parameters=2; async=false; generator=false
- parseFragment @110-152; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/src/workers/parser/utils/tests/ast.spec.js

Blob: `e8d29642053796a56cf59b99c22584f502b56ec3`. Role: test-path,source. Parse: module.

- (anonymous) @24-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ../ast @5; ImportDeclaration
- Module ../../sources @6; ImportDeclaration
- Module jest-in-case @7; ImportDeclaration
- Module ../../../../utils/test-mockup @9; ImportDeclaration

### devtools/client/debugger/src/workers/parser/worker.js

Blob: `21fbc5f842c8cbf60b39bf4b22bca43b48990201`. Role: source. Parse: module.

- clearAllHelpersForSources @12-16; FunctionDeclaration; parameters=1; async=false; generator=false
- Module ./utils/ast @5; ImportDeclaration
- Module ./getScopes @6; ImportDeclaration
- Module ./sources @7; ImportDeclaration
- Module ./mapExpression @8; ImportDeclaration
- Module ../../../../shared/worker-utils @10; ImportDeclaration

### devtools/client/debugger/src/workers/pretty-print/index.js

Blob: `4c158b24d9366e543876c0015cb28bf773e4ad67`. Role: source. Parse: module.

- constructor @13-15; FunctionExpression; parameters=1; async=false; generator=false
- prettyPrint @21-31; FunctionExpression; parameters=1; async=true; generator=false
- prettyPrintInlineScript @33-43; FunctionExpression; parameters=1; async=true; generator=false
- getSourceMap @45-47; FunctionExpression; parameters=1; async=false; generator=false
- Class PrettyPrintDispatcher @12-48
- Module devtools/shared/string @5; ImportDeclaration
- Module devtools/client/shared/worker-utils @6; ImportDeclaration

### devtools/client/debugger/src/workers/pretty-print/pretty-fast.js

Blob: `a60d691d3d39608836195843e13745032ecc2e4c`. Role: source. Parse: module.

- prettyFast @11-13; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @124-144; FunctionExpression; parameters=1; async=false; generator=false
- getPrettifiedCodeAndSourceMap @209-252; FunctionExpression; parameters=1; async=false; generator=false
- write @268-308; FunctionExpression; parameters=4; async=false; generator=false
- writeToken @316-373; FunctionExpression; parameters=1; async=false; generator=false
- getTokens @382-411; FunctionExpression; parameters=1; async=false; generator=false
- onComment @388-396; FunctionExpression; parameters=6; async=false; generator=false
- handleToken @422-502; FunctionExpression; parameters=2; async=false; generator=false
- maybePopStack @507-524; FunctionExpression; parameters=1; async=false; generator=false
- maybeIncrementIndent @526-537; FunctionExpression; parameters=1; async=false; generator=false
- shouldDecrementIndent @539-547; FunctionExpression; parameters=1; async=false; generator=false
- maybeDecrementIndent @549-559; FunctionExpression; parameters=1; async=false; generator=false
- addComment @575-594; FunctionExpression; parameters=5; async=false; generator=false
- prependWhiteSpace @603-665; FunctionExpression; parameters=1; async=false; generator=false
- ensureNewline @640-645; ArrowFunctionExpression; parameters=0; async=false; generator=false
- maybeAppendNewline @674-682; FunctionExpression; parameters=1; async=false; generator=false
- isArrayLiteral @696-715; FunctionDeclaration; parameters=2; async=false; generator=false
- isObjectLiteral @728-741; FunctionDeclaration; parameters=2; async=false; generator=false
- isRoundBracketStartingLongParenthesis @754-810; FunctionDeclaration; parameters=3; async=false; generator=false
- isIdentifierLike @918-923; FunctionDeclaration; parameters=1; async=false; generator=false
- isASI @937-962; FunctionDeclaration; parameters=2; async=false; generator=false
- isLineDelimiter @975-988; FunctionDeclaration; parameters=2; async=false; generator=false
- needsSpaceAfter @998-1017; FunctionDeclaration; parameters=2; async=false; generator=false
- needsSpaceBeforePreviousToken @1019-1053; FunctionDeclaration; parameters=1; async=false; generator=false
- isBreakContinueOrReturnStatement @1055-1061; FunctionDeclaration; parameters=1; async=false; generator=false
- needsSpaceBeforePreviousTokenKeywordAfterNotDot @1063-1072; FunctionDeclaration; parameters=1; async=false; generator=false
- needsSpaceBeforeClosingParen @1074-1082; FunctionDeclaration; parameters=1; async=false; generator=false
- needsSpaceBetweenTokens @1093-1128; FunctionDeclaration; parameters=2; async=false; generator=false
- needsSpaceBeforeClosingCurlyBracket @1130-1136; FunctionDeclaration; parameters=1; async=false; generator=false
- needsLineBreakBeforeClosingCurlyBracket @1138-1148; FunctionDeclaration; parameters=1; async=false; generator=false
- templateSanitizerReplaceFunc @1199-1201; FunctionDeclaration; parameters=2; async=false; generator=false
- stringSanitize @1207-1214; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1208-1213; ArrowFunctionExpression; parameters=2; async=false; generator=false
- templateSanitize @1215-1220; FunctionDeclaration; parameters=1; async=false; generator=false
- belongsOnStack @1225-1239; FunctionDeclaration; parameters=1; async=false; generator=false
- Class PrettyFast @104-683

### devtools/client/debugger/src/workers/pretty-print/tests/prettyFast.spec.js

Blob: `1ad7af92ee1f355efa4a95b10894ecfc9cf369ce`. Role: test-path,source. Parse: module.

- (anonymous) @461-461; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @468-486; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @479-483; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ../pretty-fast @10; ImportDeclaration
- Module devtools/client/shared/vendor/source-map/source-map @11; ImportDeclaration

### devtools/client/debugger/src/workers/pretty-print/worker.js

Blob: `abbf4554c04b990f1fc1d6c6813a4ba0ad0c66d0`. Role: source. Parse: module.

- prettyPrint @12-22; FunctionDeclaration; parameters=1; async=false; generator=false
- prettyPrintInlineScript @24-76; FunctionDeclaration; parameters=1; async=false; generator=false
- getSourceMapForTask @84-92; FunctionDeclaration; parameters=1; async=false; generator=false
- Module ../../../../shared/worker-utils @5; ImportDeclaration
- Module ./pretty-fast @6; ImportDeclaration

### devtools/client/debugger/src/workers/search/get-matches.js

Blob: `972dea68181936966a434aa0e82290d8e468232b`. Role: source. Parse: module.

- getMatches @8-45; FunctionDeclaration; parameters=3; async=false; generator=false
- Module ../../utils/assert @5; ImportDeclaration
- Module ../../utils/build-query @6; ImportDeclaration

### devtools/client/debugger/src/workers/search/index.js

Blob: `928bbf50e67e80c2be89ee3a66125edf9e5521d4`. Role: source. Parse: module.

- constructor @10-12; FunctionExpression; parameters=1; async=false; generator=false
- Class SearchDispatcher @9-17
- Module devtools/client/shared/worker-utils @5; ImportDeclaration

### devtools/client/debugger/src/workers/search/project-search.js

Blob: `f3751b57c4554b994447c82970bfad7dd9a06cae`. Role: source. Parse: module.

- findSourceMatches @9-28; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @17-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- truncateLine @41-70; FunctionDeclaration; parameters=2; async=false; generator=false
- Module ./get-matches @7; ImportDeclaration

### devtools/client/debugger/src/workers/search/tests/get-matches.spec.js

Blob: `30b0ce316d9dee066f11f54a715b01ad0dd37aa4`. Role: test-path,source. Parse: module.

- (anonymous) @7-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module ../get-matches @5; ImportDeclaration

### devtools/client/debugger/src/workers/search/worker.js

Blob: `b452697516c9152d1328d8e39ee6a63a0df55531`. Role: source. Parse: module.

- Module ./get-matches @5; ImportDeclaration
- Module ./project-search @6; ImportDeclaration
- Module ../../../../shared/worker-utils @7; ImportDeclaration

### devtools/client/debugger/test/mochitest/browser_dbg-async-stepping.js

Blob: `f9ce94c2ac608771e7792484b3c9d7ac79bc14c5`. Role: test-path,source. Parse: module.

- test @9-23; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-asyncstacks.js

Blob: `b432f8337e2795a4c314a48515bcdfb206503bfa`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-audiocontext.js

Blob: `f77fedbe2adc5e37255edcb1c5e6c0b2f6214cf4`. Role: test-path,source. Parse: module.

- (anonymous) @10-20; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-backgroundtask-debugging.js

Blob: `0d424c61875ad73a6c38e3c9500326e824db0b3a`. Role: test-path,source. Parse: module.

- test_backgroundtask_debugger @37-166; FunctionExpression; parameters=0; async=true; generator=false
- existingProcessClose @71-74; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @77-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- log @113-114; ArrowFunctionExpression; parameters=2; async=false; generator=false
- info @115-116; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @123-127; ArrowFunctionExpression; parameters=1; async=true; generator=false
- ?.selectors.scopeNode @125-126; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @130-132; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @131-131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-158; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/BackgroundTasksTestUtils.sys.mjs @29; ChromeUtils-import-literal

### devtools/client/debugger/test/mochitest/browser_dbg-bfcache.js

Blob: `0c4416547226a6570e97a5df88100ea5b0b5e28b`. Role: test-path,source. Parse: module.

- (anonymous) @11-21; FunctionExpression; parameters=0; async=true; generator=false
- testSourcesOnNavigation @23-39; FunctionDeclaration; parameters=0; async=true; generator=false
- testDebuggerPauseStateOnNavigation @41-76; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- goBack @78-85; FunctionDeclaration; parameters=1; async=true; generator=false
- goForward @87-94; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-blackbox-all.js

Blob: `ad084a30ce7e8691fedb7992b2d3f353429bc3f9`. Role: test-path,source. Parse: module.

- testBlackBoxOnMultipleFiles @29-133; FunctionExpression; parameters=0; async=true; generator=false
- testHideAndShowBlackBoxedFiles @135-198; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @157-157; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @180-180; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @186-186; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForBlackboxCount @200-205; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @203-203; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertSourceNodeIsBlackBoxed @207-215; FunctionDeclaration; parameters=3; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-blackbox-original.js

Blob: `a752b404d2e7f2532a24cfce2a6fe6d2f4287101`. Role: test-path,source. Parse: module.

- (anonymous) @9-53; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-blackbox.js

Blob: `6606ca1b51c747f9decc06660483de6f31b05233`. Role: test-path,source. Parse: module.

- testAllBlackBox @32-47; FunctionExpression; parameters=0; async=true; generator=false
- testBlackBoxOnReload @50-123; FunctionExpression; parameters=0; async=true; generator=false
- testBlackBoxOnToolboxRestart @125-173; FunctionExpression; parameters=0; async=true; generator=false
- testBlackBoxRangeColumns @175-189; FunctionExpression; parameters=0; async=true; generator=false
- testBlackBoxSource @191-311; FunctionDeclaration; parameters=2; async=true; generator=false
- testBlackBoxMultipleLines @313-414; FunctionDeclaration; parameters=2; async=true; generator=false
- testBlackBoxSingleLine @416-511; FunctionDeclaration; parameters=2; async=true; generator=false
- assertContextMenuDisabled @513-522; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @514-514; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertGutterBlackBoxBoxContextMenuItems @532-580; FunctionDeclaration; parameters=2; async=true; generator=false
- assertSourceTreeBlackBoxBoxContextMenuItems @589-613; FunctionDeclaration; parameters=2; async=true; generator=false
- assertEditorBlackBoxBoxContextMenuItems @623-758; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breaking-from-console.js

Blob: `222f127e539d53b9db2590884dec511c528d7cbf`. Role: test-path,source. Parse: module.

- (anonymous) @11-38; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breaking.js

Blob: `03c6ab3255b56ff3e3766d371f14af8a51a7c5cd`. Role: test-path,source. Parse: module.

- (anonymous) @9-78; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-75; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoint-skipping-console.js

Blob: `73acdce3c111b5f990eb7e5be0419c9a77c16100`. Role: test-path,source. Parse: module.

- (anonymous) @12-20; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoint-skipping.js

Blob: `a55cdd8f9974578de57a5e2e0d55c58a9701563f`. Role: test-path,source. Parse: module.

- (anonymous) @12-50; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- skipPausing @52-55; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleBreakpoint @57-62; FunctionDeclaration; parameters=2; async=false; generator=false
- disableBreakpoint @64-68; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-actions.js

Blob: `4150f552a1db6cb91a944429ea411036a8f11eb4`. Role: test-path,source. Parse: module.

- (anonymous) @8-21; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-79; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @73-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openFirstBreakpointContextMenu @81-84; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-columns.js

Blob: `33e50191241ea22e012af52d920b60ed90b19a10`. Role: test-path,source. Parse: module.

- (anonymous) @7-43; FunctionExpression; parameters=0; async=true; generator=false
- enableFirstBreakpoint @45-52; FunctionDeclaration; parameters=1; async=true; generator=false
- enableSecondBreakpoint @54-63; FunctionDeclaration; parameters=1; async=true; generator=false
- shiftClickDisable @66-71; FunctionDeclaration; parameters=1; async=true; generator=false
- shiftClickEnable @74-79; FunctionDeclaration; parameters=1; async=true; generator=false
- setConditionalBreakpointFromColumnMarker @81-94; FunctionDeclaration; parameters=3; async=true; generator=false
- setLogPointFromColumnMarker @96-110; FunctionDeclaration; parameters=3; async=true; generator=false
- disableBreakpoint @112-124; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @117-120; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeFirstBreakpoint @126-132; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-functional.js

Blob: `f91ab962020c80d91f5c75a58183d46fd4c7a629`. Role: test-path,source. Parse: module.

- (anonymous) @9-66; FunctionExpression; parameters=0; async=true; generator=false
- setConditionalBreakpoint @68-79; FunctionDeclaration; parameters=3; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-shortcut.js

Blob: `56930e08472786cb8c64e8244080ad1fb32d2770`. Role: test-path,source. Parse: module.

- (anonymous) @10-124; FunctionExpression; parameters=0; async=true; generator=false
- enableFirstColumnBreakpoint @127-134; FunctionDeclaration; parameters=1; async=true; generator=false
- enableSecondColumnBreakpoint @136-145; FunctionDeclaration; parameters=1; async=true; generator=false
- setLogBreakpointWithKeyboardShortcut @147-150; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-source-maps.js

Blob: `98e4a21a6402c2cea6741f3078222f84842cc38a`. Role: test-path,source. Parse: module.

- (anonymous) @10-26; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-cond-ui-state.js

Blob: `c1d40e66452f94a964df7de4697209f130bba626`. Role: test-path,source. Parse: module.

- (anonymous) @9-132; FunctionExpression; parameters=0; async=true; generator=false
- waitForBreakpointWithoutCondition @134-139; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @135-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setConditionalBreakpoint @141-149; FunctionDeclaration; parameters=3; async=true; generator=false
- assertConditonalBreakpointPanelFocus @151-164; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-debugger-statement.js

Blob: `349ddfee975f910a96befa642a071f676cec90e3`. Role: test-path,source. Parse: module.

- (anonymous) @9-82; FunctionExpression; parameters=0; async=true; generator=false
- waitForBreakpointWithoutCondition @84-89; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @85-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- findBreakpoints @91-94; FunctionDeclaration; parameters=3; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-duplicate-functions.js

Blob: `08ddac730faa731f24b178ce4065ba393805f954`. Role: test-path,source. Parse: module.

- (anonymous) @11-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-in-evaled-sources.js

Blob: `b166ea70d20e917f8da8a6031a557ff716844b30`. Role: test-path,source. Parse: module.

- (anonymous) @30-92; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-list.js

Blob: `a4373907be463e5f17ff7a503374904d0d8d8423`. Role: test-path,source. Parse: module.

- testBreakpointsListForMultipleTargets @10-75; FunctionExpression; parameters=0; async=true; generator=false
- testBreakpointsListForOriginalFiles @77-116; FunctionExpression; parameters=0; async=true; generator=false
- testBreakpointsListForIgnoredLines @118-189; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @179-186; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-popup.js

Blob: `37120f7026820b06099a499d4a3f85ad90cc3980`. Role: test-path,source. Parse: module.

- isPopupPaused @25-29; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- openPopup @31-51; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @39-42; FunctionExpression; parameters=1; async=false; generator=false
- closePopup @53-62; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @58-60; FunctionExpression; parameters=0; async=false; generator=false
- testPausedByBreakpoint @64-103; FunctionExpression; parameters=0; async=true; generator=false
- testPausedByDebuggerStatement @105-127; FunctionExpression; parameters=0; async=true; generator=false
- testPausedInTwoPopups @129-231; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @151-151; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @171-184; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onAvailable @172-183; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testClosingOriginalTab @233-252; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-reloading-with-source-changes.js

Blob: `a95599a2b4e25dbdb4fd5dce48b25332d444e224`. Role: test-path,source. Parse: module.

- (anonymous) @15-24; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @28-73; ArrowFunctionExpression; parameters=2; async=false; generator=false
- testBreakpointInFunctionRelocation @77-186; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-reloading.js

Blob: `d30cb06f9a072b10b938a06fb3e2de424728640b`. Role: test-path,source. Parse: module.

- (anonymous) @13-73; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertSourceDoesNotExist @121-124; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-same-file-per-target.js

Blob: `b1de4acbdd0552c34284a7bd535b7f160bd140c6`. Role: test-path,source. Parse: module.

- (anonymous) @9-109; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-84; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-scroll-to-log.js

Blob: `d7dd9d792b6307c66459c60d7558db8d689a4c80`. Role: test-path,source. Parse: module.

- (anonymous) @10-61; FunctionExpression; parameters=0; async=true; generator=false
- openBreakpointContextMenu @63-66; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints-sourcemap-with-sections.js

Blob: `3b02e81481a20ddb49de5a5da3de2a13154e0a5f`. Role: test-path,source. Parse: module.

- (anonymous) @10-30; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-breakpoints.js

Blob: `6aa6a42a73ffe7d9089b9664b74647789bf56eb7`. Role: test-path,source. Parse: module.

- testEnableDisableBreakpoints @7-75; FunctionExpression; parameters=0; async=true; generator=false
- testBreakpointsKeyboardEvents @78-121; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @108-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testEnableDisableAllBreakpointsWithShortcut @124-167; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @136-137; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-137; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @162-163; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @163-163; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggleBreakpoint @169-173; FunctionDeclaration; parameters=2; async=false; generator=false
- disableBreakpoint @175-179; FunctionDeclaration; parameters=2; async=true; generator=false
- enableBreakpoint @181-185; FunctionDeclaration; parameters=2; async=true; generator=false
- cleanupBreakpoints @187-205; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-browser-toolbox-unselected-pause.js

Blob: `a5a2ac9a17606520b082e1058444e73be48d48c7`. Role: test-path,source. Parse: module.

- (anonymous) @17-74; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-46; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @51-54; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-67; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-browser-toolbox-workers.js

Blob: `27461ef1eebd93b5da0db0dc2eb01d9d92da5912`. Role: test-path,source. Parse: module.

- (anonymous) @19-98; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-89; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- hasWorker @63-66; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @84-85; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-call-stack.js

Blob: `277c75461aba62984c6ac32547e7626204591916`. Role: test-path,source. Parse: module.

- testBasicFrames @10-46; FunctionExpression; parameters=0; async=true; generator=false
- testFrameNavigation @48-134; FunctionExpression; parameters=0; async=true; generator=false
- testGroupFrames @136-229; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-151; FunctionExpression; parameters=0; async=false; generator=false
- toggleButton @231-234; FunctionDeclaration; parameters=1; async=false; generator=false
- assertFrameContent @236-250; FunctionDeclaration; parameters=4; async=false; generator=false
- assertSelectedLocation @252-260; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @253-258; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createMockAngularPage @264-298; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @273-280; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @285-294; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-chrome-create.js

Blob: `6edf1e8745d53262b76ab643555ac43128d4a66a`. Role: test-path,source. Parse: module.

- (anonymous) @23-65; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-36; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onRun @31-34; ArrowFunctionExpression; parameters=3; async=false; generator=false
- Module resource://devtools/client/framework/browser-toolbox/Launcher.sys.mjs @19; ChromeUtils-import-literal

### devtools/client/debugger/test/mochitest/browser_dbg-console-async.js

Blob: `caa122eb241a2a7b759a1ab9015d3efc230b374a`. Role: test-path,source. Parse: module.

- (anonymous) @11-42; FunctionExpression; parameters=0; async=true; generator=false
- hasMessageByType @44-50; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-console-eval.js

Blob: `751d24005cb30dd155367b46cb2aa0d0b985501a`. Role: test-path,source. Parse: module.

- (anonymous) @10-26; FunctionExpression; parameters=0; async=true; generator=false
- waitForConsolePanelChange @28-37; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @31-36; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-35; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-console-link.js

Blob: `e5e8d76793625dea9a889046183716c2db07fabb`. Role: test-path,source. Parse: module.

- (anonymous) @10-24; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-console-map-bindings.js

Blob: `085b048fb6093a76d50d29c84c37c13705acb4d7`. Role: test-path,source. Parse: module.

- (anonymous) @7-21; FunctionExpression; parameters=0; async=true; generator=false
- getSplitConsole @26-40; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @33-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- evaluate @42-47; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-console.js

Blob: `f8a168f3aab6b569f03677926eebf01942ddd867`. Role: test-path,source. Parse: module.

- (anonymous) @7-30; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-content-script-sources.js

Blob: `35f8e213e0d4e6a01543011b54ea6583a552c5b2`. Role: test-path,source. Parse: module.

- (anonymous) @9-152; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @142-142; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @149-149; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-continue-to-here-click.js

Blob: `641f3f9b284df615a61cb5b9cd02e8faed20e5bb`. Role: test-path,source. Parse: module.

- (anonymous) @9-44; FunctionExpression; parameters=0; async=true; generator=false
- cmdClickLine @46-48; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-continue-to-here.js

Blob: `e5cda0e3c80b1fbb8202969a27fe628257839250`. Role: test-path,source. Parse: module.

- (anonymous) @7-39; FunctionExpression; parameters=0; async=true; generator=false
- continueToLine @41-48; FunctionDeclaration; parameters=2; async=true; generator=false
- continueToColumn @50-58; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-custom-formatters.js

Blob: `a3bece4964500b3bf878db483ed4548e91a3b4c5`. Role: test-path,source. Parse: module.

- (anonymous) @12-159; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @140-143; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-debug-line.js

Blob: `7266f80545d5b432d0eb99f867c5fc647345e435`. Role: test-path,source. Parse: module.

- (anonymous) @10-58; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-debugger-buttons.js

Blob: `eeb71fe4c5309790f77007d42042bdd6fe2ca700`. Role: test-path,source. Parse: module.

- (anonymous) @16-99; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clickButton @101-105; FunctionDeclaration; parameters=2; async=false; generator=false
- clickStepOver @107-110; FunctionDeclaration; parameters=1; async=true; generator=false
- clickStepIn @112-115; FunctionDeclaration; parameters=1; async=true; generator=false
- clickStepOut @117-120; FunctionDeclaration; parameters=1; async=true; generator=false
- clickResume @122-124; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-dom-mutation-breakpoints-fission.js

Blob: `81c1ad2d509979e841d3b5624ce8e1ba6061d22e`. Role: test-path,source. Parse: module.

- (anonymous) @34-110; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-59; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-94; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-dom-mutation-breakpoints.js

Blob: `aff826aa025a9f4f3730f30e6a226a99007b3478`. Role: test-path,source. Parse: module.

- (anonymous) @18-184; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @102-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-107; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-122; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-129; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @134-136; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @139-139; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @149-151; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @154-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @170-172; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-eager-eval-skip-pause.js

Blob: `dcd8f4605bbdcb47c4a3468a0670153701b1b3dd`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-exception.js

Blob: `6ec1c562ac29babfc77531774c7aca207aa1c190`. Role: test-path,source. Parse: module.

- testEditorExceptionClose @9-15; FunctionExpression; parameters=0; async=true; generator=false
- openActiveTabContextMenuAndSelectCloseTabItem @17-26; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-gutter.js

Blob: `4e1ae73aa00a910fb86a319cd26979094b0754f8`. Role: test-path,source. Parse: module.

- testGutterBreakpoints @14-31; FunctionExpression; parameters=0; async=true; generator=false
- testGutterBreakpointsInIgnoredSource @33-80; FunctionExpression; parameters=0; async=true; generator=false
- testGutterBreakpointsForSourceWithIgnoredLines @82-139; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-highlight.js

Blob: `117fece80a67df06d9158bd1b817b178aaa95257`. Role: test-path,source. Parse: module.

- (anonymous) @11-50; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-horizontal-scroll.js

Blob: `a21508b591b713ede44afca95af436ac70396858`. Role: test-path,source. Parse: module.

- testHorizontalScrolling @10-187; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @43-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getFirstVisibleColumn @93-105; FunctionDeclaration; parameters=0; async=false; generator=false
- getLastVisibleColumn @106-112; FunctionDeclaration; parameters=0; async=false; generator=false
- testColumnBreakpointsLimitAfterHorizontalScroll @190-233; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-mode.js

Blob: `6f809c2dcdc208818e033a4bf0ed558f222b49e9`. Role: test-path,source. Parse: module.

- (anonymous) @10-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-scroll.js

Blob: `14ed434a15b5de2007070b54feb4627bb1d4e746`. Role: test-path,source. Parse: module.

- testScrollingOnPauseAndSourceSwitching @19-79; FunctionExpression; parameters=0; async=true; generator=false
- testIsPositionVisible @88-238; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @113-115; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getFirstVisibleLine @130-135; FunctionDeclaration; parameters=0; async=false; generator=false
- getLastVisibleLine @136-140; FunctionDeclaration; parameters=0; async=false; generator=false
- testColumnBreakpointsLimitAfterVerticalScroll @240-284; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-editor-select.js

Blob: `9c397b0099a4c910eb042269cb70f1833edacb91`. Role: test-path,source. Parse: module.

- (anonymous) @12-99; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-ember-original-variable-mapping-notifications.js

Blob: `530831a0e3caba6419d7566e8f48af8a3f0c219e`. Role: test-path,source. Parse: module.

- (anonymous) @15-72; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-69; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getScopeNotificationMessage @74-78; FunctionDeclaration; parameters=1; async=false; generator=false
- getExpressionNotificationMessage @80-84; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-es-module-worker.js

Blob: `8cca4b63b482463aefe9fbe8864ac786bfdf66a6`. Role: test-path,source. Parse: module.

- (anonymous) @13-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-29; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @34-76; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @49-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-75; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-es-module.js

Blob: `f09e5b65cccbb6927722eed12ade82b380cf65a3`. Role: test-path,source. Parse: module.

- (anonymous) @12-30; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @32-41; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @45-55; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @60-121; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @74-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @110-112; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-eval-throw.js

Blob: `803037d921498fa687e1c543de387b5987b3329e`. Role: test-path,source. Parse: module.

- (anonymous) @10-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints-fission.js

Blob: `d8f378e64eff22155af4d46a3160037009d8b463`. Role: test-path,source. Parse: module.

- (anonymous) @9-46; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @41-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- invokeAndAssertBreakpoints @48-66; FunctionDeclaration; parameters=1; async=true; generator=false
- invokeInTabRemoteFrame @68-81; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @73-79; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints-unsupported.js

Blob: `55e6a64f9c1166139c5dddd1cdd7d13a8193efee`. Role: test-path,source. Parse: module.

- (anonymous) @11-67; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-event-breakpoints.js

Blob: `997ee3983986497ae1902583828e7fd128190314`. Role: test-path,source. Parse: module.

- (anonymous) @7-293; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @188-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @199-207; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @296-334; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @327-329; ArrowFunctionExpression; parameters=0; async=false; generator=false
- invokeOnElement @336-345; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @341-343; ArrowFunctionExpression; parameters=2; async=false; generator=false
- flushPendingContentEvents @350-352; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @351-351; ArrowFunctionExpression; parameters=0; async=false; generator=false
- invokeComposition @354-369; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-event-handler.js

Blob: `10acc9f118166f02c1b7a4f25fd122ef7711bb76`. Role: test-path,source. Parse: module.

- (anonymous) @11-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-expressions-error.js

Blob: `fd38d0cec6e5e5d806f6de88ec4aaf1a7cab5c18`. Role: test-path,source. Parse: module.

- (anonymous) @15-33; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-expressions-focus.js

Blob: `17fad40bccfec931864c0045d11fc9ab669b5be3`. Role: test-path,source. Parse: module.

- (anonymous) @9-53; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-38; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-expressions-thread.js

Blob: `ca0406844ba2fac9cffbab21cbe22aaed90baede`. Role: test-path,source. Parse: module.

- (anonymous) @15-100; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-expressions-watch.js

Blob: `5f2c6aba40b90caf441e69a45f9cc0ce46f33ff5`. Role: test-path,source. Parse: module.

- (anonymous) @15-87; FunctionExpression; parameters=0; async=true; generator=false
- getRefreshExpressionsElement @89-91; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-expressions.js

Blob: `ac1ea50fdb3904fa1be0b4f7974665d3479754d9`. Role: test-path,source. Parse: module.

- (anonymous) @15-109; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @96-98; FunctionExpression; parameters=0; async=false; generator=false
- assertEmptyValue @111-119; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-extension-inspectedWindow-debugger-statement.js

Blob: `790b0366b98760cc211121890e72a83e391a3d00`. Role: test-path,source. Parse: module.

- (anonymous) @10-31; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @34-59; FunctionExpression; parameters=0; async=true; generator=false
- installAndStartExtension @61-88; FunctionDeclaration; parameters=0; async=true; generator=false
- devtools_page @62-65; FunctionDeclaration; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-breakpoint.js

Blob: `04e94eb49affbae010e392a25297a938941e4f92`. Role: test-path,source. Parse: module.

- (anonymous) @9-93; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isThreadElementPaused @95-97; FunctionDeclaration; parameters=1; async=false; generator=false
- getThreadElementPausedBadge @99-101; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-pause-exceptions.js

Blob: `6c2b6147e4d097d86b30292d5b3bdd39cae4c38a`. Role: test-path,source. Parse: module.

- (anonymous) @10-54; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-fission-frame-sources.js

Blob: `5e0220097ff2811428da180b290dc775af45e9e7`. Role: test-path,source. Parse: module.

- (anonymous) @9-44; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-fission-project-search.js

Blob: `0e0316a0432c1783873ab602e5463f54b95b927c`. Role: test-path,source. Parse: module.

- (anonymous) @10-52; FunctionExpression; parameters=0; async=true; generator=false
- assertFileResult @37-51; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @39-40; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-fission-switch-target.js

Blob: `6500942d0ab420eeec94302ef563a819af3f0a63`. Role: test-path,source. Parse: module.

- (anonymous) @11-32; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-gc-breakpoint-positions.js

Blob: `881118527d6f12afca4acc243c5382355fee5418`. Role: test-path,source. Parse: module.

- (anonymous) @9-28; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-gc-sources.js

Blob: `e4a6da536a49b1bd8d205f88c91048825e124093`. Role: test-path,source. Parse: module.

- (anonymous) @12-29; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-go-to-line.js

Blob: `14cd9227847c6a7ee5b0e53d01763e79f98a3782`. Role: test-path,source. Parse: module.

- (anonymous) @9-84; FunctionExpression; parameters=0; async=true; generator=false
- assertEnabled @86-88; FunctionDeclaration; parameters=1; async=false; generator=false
- assertDisabled @90-92; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForGoToLineBoxFocus @94-96; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @95-95; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertLine @98-106; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-html-breakpoints.js

Blob: `6a0c2dc42a01a748e287b35574143326314d92f8`. Role: test-path,source. Parse: module.

- (anonymous) @7-54; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-idb-run-to-completion.js

Blob: `dcd4a11463e6aac9ff133f5aadf5d73908ac0cb6`. Role: test-path,source. Parse: module.

- (anonymous) @10-15; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-iframes.js

Blob: `4ed46f587581247bdabb59c5f0c78ed8269fc181`. Role: test-path,source. Parse: module.

- (anonymous) @17-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-cache.js

Blob: `0e209afab542e21c11ae701e263bca0c9bc3218e`. Role: test-path,source. Parse: module.

- (anonymous) @20-34; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @38-131; FunctionExpression; parameters=0; async=true; generator=false
- makeChanges @137-139; FunctionDeclaration; parameters=0; async=false; generator=false
- getPageValue @141-145; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @142-144; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions-inline-script.js

Blob: `2977672524be51dddd56d1e2784052a56f2fccd3`. Role: test-path,source. Parse: module.

- (anonymous) @10-34; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions-position.js

Blob: `e5db201af19ea8346958259f4e791b399b30b95e`. Role: test-path,source. Parse: module.

- waitForElementsWithSelector @10-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @11-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-42; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-exceptions.js

Blob: `56c0f0eeeddb5ded9ece8f2f73c715c24c0f4dd9`. Role: test-path,source. Parse: module.

- (anonymous) @10-38; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-preview.js

Blob: `ddd7806074ac6b5c69c9c8289c9cdea50bd0a2d4`. Role: test-path,source. Parse: module.

- testInlinePreviews @9-218; FunctionExpression; parameters=0; async=true; generator=false
- testInlinePreviewsWithExplicitResourceManagement @220-265; FunctionExpression; parameters=0; async=true; generator=false
- invokeFunctionAndAssertInlinePreview @267-276; FunctionDeclaration; parameters=1; async=true; generator=false
- checkInspectorIcon @278-315; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @291-293; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @296-305; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inline-script-offset.js

Blob: `640ea1538e01172cd8b52d5569c0a13e55dd36d4`. Role: test-path,source. Parse: module.

- (anonymous) @11-45; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-inspector-integration.js

Blob: `60720ea678f254cdcf4ccb0f9776e6aa7f1639fb`. Role: test-path,source. Parse: module.

- (anonymous) @10-104; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-218; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @123-124; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-141; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @149-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @167-191; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @169-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getBoxModelHighlighterInfoBarEl @172-175; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @176-177; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-keyboard-navigation.js

Blob: `1737de390bcc635b26e63a69533dfea4dd72426c`. Role: test-path,source. Parse: module.

- (anonymous) @9-60; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-keyboard-shortcuts-modal.js

Blob: `d293d3d56f97656d493776c7dff89ea4ce6e8bf1`. Role: test-path,source. Parse: module.

- (anonymous) @11-35; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getShortcutsModal @37-39; FunctionDeclaration; parameters=1; async=false; generator=false
- pressKeyboardShortcut @41-49; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-keyboard-shortcuts.js

Blob: `3a2f9ffd6fbe8cccc4b63a0be252ffa026b4f9c1`. Role: test-path,source. Parse: module.

- (anonymous) @11-38; FunctionExpression; parameters=0; async=true; generator=false
- pressResume @40-43; FunctionDeclaration; parameters=1; async=false; generator=false
- pressStepOver @45-48; FunctionDeclaration; parameters=1; async=false; generator=false
- pressStepIn @50-53; FunctionDeclaration; parameters=1; async=false; generator=false
- pressStepOut @55-58; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-layout-changes.js

Blob: `0f006c61fe365dbc55b7e61f66a0b65500dd28d2`. Role: test-path,source. Parse: module.

- (anonymous) @16-23; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-42; FunctionExpression; parameters=0; async=true; generator=false
- testLayout @44-50; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getHost @52-57; FunctionDeclaration; parameters=1; async=false; generator=false
- switchHost @59-62; FunctionDeclaration; parameters=2; async=true; generator=false
- resizeToolboxWindow @64-80; FunctionDeclaration; parameters=2; async=false; generator=false
- resizeWindow @82-86; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @88-91; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-link-reload.js

Blob: `f7a5ba801a61f8cf78ef629403466914d5c8a329`. Role: test-path,source. Parse: module.

- (anonymous) @12-45; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-30; FunctionExpression; parameters=0; async=false; generator=false
- waitForReload @47-65; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onAvailable @52-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-log-events.js

Blob: `1232c5893bb8f1bc1dbebb5e1e5c2e5dffc02471`. Role: test-path,source. Parse: module.

- (anonymous) @11-29; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-log-point-mapping.js

Blob: `521e59b2709d83b987d665da6b57a27a6e74eadc`. Role: test-path,source. Parse: module.

- (anonymous) @11-43; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-log-points-workers.js

Blob: `894513bbfeb547f04599283f708213d2f3d380b0`. Role: test-path,source. Parse: module.

- (anonymous) @11-26; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-log-points.js

Blob: `967c3719fbd4fb2be254d79febe1e04f4ea54612`. Role: test-path,source. Parse: module.

- (anonymous) @11-241; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @164-166; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @206-207; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-many-breakpoints-same-line.js

Blob: `d6d1fc30c76179f0dd8910a6aec6c7987c9d4bea`. Role: test-path,source. Parse: module.

- (anonymous) @13-22; FunctionExpression; parameters=0; async=true; generator=false
- testSimpleAndLog @24-55; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- testLogUpdates @57-85; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @79-81; FunctionExpression; parameters=0; async=false; generator=false
- waitForMessageByType @87-93; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-merge-scopes.js

Blob: `48dfd26a48a9b5c23983d79b7073885bebbf6bbe`. Role: test-path,source. Parse: module.

- (anonymous) @9-41; FunctionExpression; parameters=0; async=true; generator=false
- expectLabels @43-51; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-message-run-to-completion.js

Blob: `a168c9233da877d9e846688b6ad768e05c2d8aee`. Role: test-path,source. Parse: module.

- (anonymous) @10-24; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-minified.js

Blob: `1a15d1588a777e735855fbb82ed980bf1cbba105`. Role: test-path,source. Parse: module.

- (anonymous) @9-25; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-navigation-when-paused.js

Blob: `b4382c416fae995d016b09b20098ed8fd3b0d367`. Role: test-path,source. Parse: module.

- (anonymous) @7-42; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-navigation.js

Blob: `158b0403c74a86986d3a5215eaf19671b5fbc46a`. Role: test-path,source. Parse: module.

- (anonymous) @19-69; FunctionExpression; parameters=0; async=true; generator=false
- countSources @71-73; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-no-duplicate-breakpoints-on-frame-reload.js

Blob: `fa9fc375178346a1b92befc647045bc9cc6a3529`. Role: test-path,source. Parse: module.

- (anonymous) @10-63; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertBreakpointsList @65-95; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-old-breakpoint.js

Blob: `7fe68e2d2e9672618c80317db411d6e2e85c98ff`. Role: test-path,source. Parse: module.

- (anonymous) @10-71; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @76-114; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @104-111; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/debugger/test/mochitest/browser_dbg-outline-filter.js

Blob: `966fbc714d722b55542209494ef009f773e7b065`. Role: test-path,source. Parse: module.

- (anonymous) @9-78; FunctionExpression; parameters=0; async=true; generator=false
- getItems @80-82; FunctionDeclaration; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
