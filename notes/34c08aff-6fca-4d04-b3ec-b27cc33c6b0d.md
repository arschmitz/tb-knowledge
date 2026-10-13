<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["7f60a3fd0d74d27dc80d4a3040684ef943f8404a7ebab0d6913e8cf59d0e2643"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/024b68f6-ed8e-49a6-930c-2b0e5dadb003.md"}} -->
# firefox/testing JavaScript function map 792

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/this.js

Blob: `996a439df0b752654f79b88d9320304d3959c8b3`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/throw-error.js

Blob: `9769c84b23341cf0c6d80a7f4f52149a99da4d6b`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/throw-nested.js

Blob: `f1801ea366fb81c41441ea1377f166d2b90cd661`. Role: test-path,source. Parse: module.

- Module ./throw.js @1; ImportDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/throw.js

Blob: `cef7918216dc83d95219fbfe78dfd10c7fe8c004`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/throw2.js

Blob: `2931eec500dee612d20b160961c7fa8e23b99a86`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked.any.js

Blob: `820f995aaf6900ea097ef0f5068c7d482d7a095f`. Role: test-path,source. Parse: module.

- (anonymous) @1-5; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @7-11; ArrowFunctionExpression; parameters=1; async=true; generator=false
- Module ./sibling-imports-not-blocked__microtask__parent.js @2; dynamic-import-literal
- Module ./sibling-imports-not-blocked__task__parent.js @8; dynamic-import-literal

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__microtask__check-get-sync.js

Blob: `063697310a0747ad4cc4f762cd7e89f9707cea5b`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__microtask__check-set-async.js

Blob: `98930fed0b7a55d9194d502db075362617359c1b`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__microtask__parent.js

Blob: `a28fcef9cb137c7bbc06ef0ca3bc22144c3a536e`. Role: test-path,source. Parse: module.

- Module ./sibling-imports-not-blocked__microtask__check-set-async.js @1; ImportDeclaration
- Module ./sibling-imports-not-blocked__microtask__check-get-sync.js @2; ExportNamedDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__task__check-get-sync.js

Blob: `833acdd7ecd97af56c67e58422320713cfae38d7`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__task__check-set-async.js

Blob: `0973b3c65a0bd56f7e0bc2a9ff4118d7382e46a6`. Role: test-path,source. Parse: module.

- (anonymous) @2-2; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/module/top-level-await/sibling-imports-not-blocked__task__parent.js

Blob: `56ee5134d7571bf615febd7f9651be94dda370ce`. Role: test-path,source. Parse: module.

- Module ./sibling-imports-not-blocked__task__check-set-async.js @1; ImportDeclaration
- Module ./sibling-imports-not-blocked__task__check-get-sync.js @2; ExportNamedDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/moving-between-documents/ordering/helper.js

Blob: `cb5f45eb0d656a09c8f12aa37c1127f2752f1c09`. Role: test-path,source. Parse: module.

- runDelayEventTest @1-31; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @11-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-30; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/moving-between-documents/resources/moving-between-documents-helper.js

Blob: `fb9d459ec385e0cbba292ca5ca1886b2b7d76480`. Role: test-path,source. Parse: module.

- createDocument @3-60; FunctionDeclaration; parameters=5; async=false; generator=false
- (anonymous) @4-59; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onMessage @14-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- proceed @23-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- runTest @120-236; FunctionDeclaration; parameters=5; async=true; generator=false
- scriptOnError @148-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @187-187; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @221-235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @222-234; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @227-232; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @238-245; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @239-243; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/bom-utf-8.js

Blob: `fb88bdda2afbafa3b4074ed6140db73a7bb77268`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/cocoa-module.js

Blob: `24360a7bfe7e05a0cb253841367e71dc1e93b5c7`. Role: test-path,source. Parse: module.

- taste @2-4; FunctionExpression; parameters=0; async=false; generator=false
- Class Cocoa @1-5

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/dynamically-created-defer-script.js

Blob: `5d8ce66459d121426e37588c642697d883a4eceb`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/exports-cocoa.js

Blob: `02967bc63191ec7c0b153b0cb831d97cfc93217f`. Role: test-path,source. Parse: module.

- Module ./cocoa-module.js @1; ImportDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/flag-setter.js

Blob: `3274e5bfeb26c627f5c887784e239c45b01de876`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/load-error-events-helpers.js

Blob: `bbd6b09c6cf811855cb1fa299855b9cee55a66c3`. Role: test-path,source. Parse: module.

- event_test @4-11; FunctionDeclaration; parameters=3; async=false; generator=false
- onLoad @15-27; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @16-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onError @28-39; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @29-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onExecute @42-47; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/script-sets-flag.js

Blob: `336dbde6da04b7c9a7381bd6643616aa825a1851`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/script-type-and-language-js.js

Blob: `d357bc49944df2791d351c05f66a3d377ee25acf`. Role: test-path,source. Parse: module.

- testAttribute @1-19; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2-16; FunctionExpression; parameters=0; async=false; generator=false
- testTypeShouldRun @20-22; FunctionDeclaration; parameters=1; async=false; generator=false
- testLanguageShouldRun @23-25; FunctionDeclaration; parameters=1; async=false; generator=false
- testTypeShouldNotRun @26-28; FunctionDeclaration; parameters=1; async=false; generator=false
- testLanguageShouldNotRunUnlessSVG @29-36; FunctionDeclaration; parameters=1; async=false; generator=false
- testParserInsertedDidNotRun @46-50; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @94-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @95-95; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @98-101; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @99-99; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @103-103; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @108-108; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @112-115; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @114-114; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-117; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @118-118; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @129-129; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-136; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @134-134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @135-135; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @137-137; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @140-140; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-141; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/set-script-executed.js

Blob: `a6095097dd7e17b1e5370b739b31d361f8fdaf7b`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/syntax-error.js

Blob: `40dc81dcfacd8f484e0b476cdc6be8d15a551570`. Role: test-path,source. Parse: failed.

Failure: Unexpected token cannot


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/resources/throw.js

Blob: `be53dd1ef3fb31ab71cd42b5b3d7416b35961c87`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/script-not-executed-after-shutdown.js

Blob: `ccdf14c0cd47d93f9e06c792171475e432960b2a`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/support/script-onload-insertion-point-helper.js

Blob: `8a96a0b783e19c5f19c2ae88149da66091140f2f`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/charset-bom.any.js

Blob: `6d1c342e6d0ec093fcedd7bb8fe298ca6e4158b9`. Role: test-path,source. Parse: module.

- (anonymous) @4-7; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-12; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-17; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module ./bom-utf-8.txt @5; dynamic-import-literal
- Module ./bom-utf-16be.txt @10; dynamic-import-literal
- Module ./bom-utf-16le.txt @15; dynamic-import-literal

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/file.js

Blob: `0ca232e371205140e9b39ba0020b864e58eb3cd5`. Role: test-path,source. Parse: failed.

Failure: Unexpected token file


### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/ignore-content-type.any.js

Blob: `d538df1ce76651420bed880d3a977a6f94949d34`. Role: test-path,source. Parse: module.

- (anonymous) @135-138; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/ignore-extension.any.js

Blob: `350b489a06fa3d35db6049dc6c337389b9eea006`. Role: test-path,source. Parse: module.

- (anonymous) @4-7; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/integrity-matches.js

Blob: `92b7bfdba93b82e36a0200b3190d3da08f06241a`. Role: test-path,source. Parse: module.

- Module ./file @1; ImportDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/integrity-mismatches.js

Blob: `530099d8c192f2382bc685930117ce20a59e5467`. Role: test-path,source. Parse: module.

- Module ./file @1; ImportDeclaration

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/repeated-imports.any.js

Blob: `d2e2b0983a61e80ddfc6d78063046cbe2573a130`. Role: test-path,source. Parse: module.

- (anonymous) @4-13; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @15-24; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @26-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @38-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @52-64; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @66-75; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @77-89; ArrowFunctionExpression; parameters=1; async=true; generator=false
- Module ./file.txt @6; dynamic-import-literal
- Module ./file.txt @11; dynamic-import-literal
- Module ./file.txt#2 @18; dynamic-import-literal
- Module ./file.txt#2 @22; dynamic-import-literal

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/serviceworker-dynamic-import.js

Blob: `fceb2ab40d7b06f424166a577d5819f574366748`. Role: test-path,source. Parse: module.

- onmessage @1-5; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-4; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ./file @2; dynamic-import-literal

### testing/web-platform/tests/html/semantics/scripting-1/the-script-element/text-module/serviceworker.js

Blob: `65047d27a3ef0c344500565186bac8d739fdb315`. Role: test-path,source. Parse: module.

- Module ./file @1; ImportDeclaration

### testing/web-platform/tests/html/semantics/selectors/case-sensitivity/values.window.js

Blob: `1973398bff89b62e8bd644fe8a1e5f35bf5c6ed7`. Role: test-path,source. Parse: module.

- (anonymous) @49-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @83-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @84-89; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @85-85; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/selectors/pseudo-classes/checked-indeterminate.window.js

Blob: `167cbdd37fa1d4fe99b099417a8677381a0ae353`. Role: test-path,source. Parse: module.

- (anonymous) @1-27; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/selectors/pseudo-classes/input-checkbox-switch.tentative.window.js

Blob: `b5d9898a640e9efe2a8a9b3c0dc3f25872c5fb3d`. Role: test-path,source. Parse: module.

- (anonymous) @1-9; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/selectors/pseudo-classes/utils.js

Blob: `7a2fb77f105705b2ece7b7e495a3673f59faef94`. Role: test-path,source. Parse: module.

- getElementsByIds @1-7; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @3-5; FunctionExpression; parameters=1; async=false; generator=false
- testSelectorIdsMatch @9-14; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @10-13; FunctionExpression; parameters=0; async=false; generator=false
- testSelectorElementsMatch @16-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/semantics/tabular-data/html-table-section-element.js

Blob: `68b68ceed80b450c66951f605fc3d7dacac4be85`. Role: test-path,source. Parse: module.

- testRowsAttribute @2-22; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/semantics/the-button-element/command-and-commandfor/resources/invoker-utils.js

Blob: `4261f9c0d32fa2911a3a8ce252246e55a655655f`. Role: test-path,source. Parse: module.

- waitForRender @1-3; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2-2; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clickOn @4-16; FunctionDeclaration; parameters=1; async=true; generator=false
- hoverOver @17-27; FunctionDeclaration; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/syntax/parsing/foster-parenting-moved-table.window.js

Blob: `957ab35b7e440da2dfa75b60636688b0245a6a50`. Role: test-path,source. Parse: module.

- markupFor @41-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- parse @58-65; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @61-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- iframe.onload @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- roots @68-70; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- brokenLinks @75-100; FunctionDeclaration; parameters=1; async=false; generator=false
- name @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- walk @79-97; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @88-94; ArrowFunctionExpression; parameters=2; async=false; generator=false
- secondInsertion @104-111; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @106-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- placement @113-120; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @125-128; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @130-140; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/html/syntax/parsing/named-character-references-data.js

Blob: `48ab30e4738feb1c95b2d4ad0a381c15c61e38d3`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/syntax/parsing/resources/adoption-agency-reparenting.js

Blob: `434d29695eb6b07c192de8a301c0f0cd3bb8db58`. Role: test-path,source. Parse: module.

- serialize @7-17; FunctionDeclaration; parameters=1; async=false; generator=false
- tree @19-21; FunctionDeclaration; parameters=1; async=false; generator=false
- parseInIframe @25-32; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @28-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/syntax/parsing/resources/common.js

Blob: `b3ac9ece70c433f2b01fe8ad18afcf98d3042b32`. Role: test-path,source. Parse: module.

- mark_diffs @1-24; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/html/syntax/parsing/resources/template.js

Blob: `b249fb64c71c16f1b6cefcc59668699f769a2341`. Role: test-path,source. Parse: module.

- is_single_node @34-37; FunctionDeclaration; parameters=1; async=false; generator=false
- substitute @39-63; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @59-61; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-61; FunctionExpression; parameters=1; async=false; generator=false
- substitute_single @66-135; FunctionDeclaration; parameters=2; async=false; generator=false
- do_substitution @70-82; FunctionDeclaration; parameters=1; async=false; generator=false
- substitute_attrs @94-106; FunctionDeclaration; parameters=2; async=false; generator=false
- substitute_children @108-132; FunctionDeclaration; parameters=2; async=false; generator=false
- make_dom_single @137-172; FunctionDeclaration; parameters=1; async=false; generator=false
- make_dom @176-188; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @184-186; FunctionExpression; parameters=1; async=false; generator=false
- render @190-193; FunctionDeclaration; parameters=2; async=false; generator=false
- expose @196-209; FunctionDeclaration; parameters=2; async=false; generator=false
- extend @211-214; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/html/syntax/parsing/resources/test.js

Blob: `8630d36bd437f4e11953cd4bfcff2078c0e7cfdb`. Role: test-path,source. Parse: module.

- (anonymous) @10-337; ArrowFunctionExpression; parameters=0; async=false; generator=false
- serializeTree @28-89; FunctionDeclaration; parameters=1; async=false; generator=false
- walk @34-86; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @70-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=2; async=false; generator=false
- makeDocRunner @94-106; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @95-105; ArrowFunctionExpression; parameters=1; async=false; generator=false
- iframe.onload @97-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-114; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @115-119; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @120-124; ArrowFunctionExpression; parameters=2; async=false; generator=false
- innerHTML @125-143; ArrowFunctionExpression; parameters=1; async=false; generator=false
- parseDat @156-202; FunctionDeclaration; parameters=1; async=false; generator=false
- isSectionHeading @163-167; ArrowFunctionExpression; parameters=1; async=false; generator=false
- normalise @168-174; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @196-201; ArrowFunctionExpression; parameters=1; async=false; generator=false
- printDiff @204-223; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @210-214; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @234-234; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @241-241; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @242-332; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @243-243; ArrowFunctionExpression; parameters=1; async=false; generator=false
- escapeForName @249-255; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @249-255; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @292-308; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @310-310; ArrowFunctionExpression; parameters=0; async=false; generator=false
- runNext @319-327; ArrowFunctionExpression; parameters=1; async=false; generator=false
- record @323-323; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @324-326; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @324-326; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @333-336; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @334-334; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/syntax/parsing/support/DOMContentLoaded-defer.js

Blob: `35ce9327bfc3bea185a0717e2acbd82a4967680d`. Role: test-path,source. Parse: module.

- (anonymous) @1-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-12; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/syntax/parsing/support/svg-script-self-closing.js

Blob: `6dd286e7bc01f28dfa9d1565d45c3429c2359689`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/syntax/speculative-parsing/resources/speculative-parsing-util.js

Blob: `b675665ca9863918b1f12a7c3bade197247574ae`. Role: test-path,source. Parse: module.

- expect_fetched_onload @1-13; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @2-4; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-12; ArrowFunctionExpression; parameters=0; async=true; generator=false
- compare_with_nonspeculative @15-43; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @16-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-41; ArrowFunctionExpression; parameters=0; async=true; generator=false
- split_header @45-53; FunctionDeclaration; parameters=1; async=false; generator=false
- get_result @55-58; FunctionDeclaration; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/syntax/xmldecl/support/test_support.js

Blob: `806f3f074f8ab7d993351a34291de1c2e73a1e8e`. Role: test-path,source. Parse: module.

- runAllTests @1-33; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @11-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/user-activation/resources/utils.js

Blob: `f426b187f8fda133f7c5b6ed6e2827d57619fe87`. Role: test-path,source. Parse: module.

- delayByFrames @1-9; FunctionDeclaration; parameters=2; async=false; generator=false
- recurse @2-7; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @6-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getEvent @13-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @14-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- consumeTransientActivation @25-33; FunctionDeclaration; parameters=0; async=true; generator=false
- receiveMessage @38-51; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @39-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @40-49; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/atob/base64.any.js

Blob: `fbb64042932a2890ed448e632bfa7366fcc2739f`. Role: test-path,source. Parse: module.

- mybtoa @6-41; FunctionDeclaration; parameters=1; async=false; generator=false
- btoaLookup @47-64; FunctionDeclaration; parameters=1; async=false; generator=false
- btoaException @66-74; FunctionDeclaration; parameters=1; async=false; generator=false
- testBtoa @76-90; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @83-83; FunctionExpression; parameters=0; async=false; generator=false
- toString @101-101; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @113-119; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @130-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toString @145-145; FunctionExpression; parameters=0; async=false; generator=false
- toString @146-146; FunctionExpression; parameters=0; async=false; generator=false
- runAtobTests @149-165; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @154-163; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @156-156; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/closing-the-input-stream/load-event-after-location-set-during-write.window.js

Blob: `d5c8469bafac20a967d8acb32dcb85bdff96cc3f`. Role: test-path,source. Parse: module.

- (anonymous) @5-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-13; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/005.js

Blob: `ebfd7e2585284cd52326c995bad0809a08c5249d`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/006.js

Blob: `ebfd7e2585284cd52326c995bad0809a08c5249d`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/007.js

Blob: `31fcf18d493b7a842b770ed49f972f9b5c829281`. Role: test-path,source. Parse: module.

- (anonymous) @1-4; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/008-1.js

Blob: `ef90c722b7915c510da0f2ef76d6ad353738a8a1`. Role: test-path,source. Parse: module.

- (anonymous) @1-3; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/008.js

Blob: `367597515d76d07773ebb4f532eed1d4c684f45f`. Role: test-path,source. Parse: module.

- (anonymous) @1-4; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/010-1.js

Blob: `fd815bab7711a97f17980efe7aad2212615cfc94`. Role: test-path,source. Parse: module.

- (anonymous) @1-4; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/010.js

Blob: `bb328ad55afb52408562f1ee58ac334d115481f6`. Role: test-path,source. Parse: module.

- (anonymous) @1-4; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/011-1.js

Blob: `944b70d2d0b1b72f25c4a005420e3ee633954123`. Role: test-path,source. Parse: module.

- (anonymous) @1-5; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/011.js

Blob: `ce47bcd283fe105d8141067479c081352c1d6acf`. Role: test-path,source. Parse: module.

- (anonymous) @1-5; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/012.js

Blob: `7ab4c6b386feaa322cb218c8032af2979c64394b`. Role: test-path,source. Parse: module.

- (anonymous) @2-5; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/013.js

Blob: `b5ce5f27da07144bf6e549f92cdc49423989dee4`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/contentType.window.js

Blob: `5a912038749f9410aefd44e1614027cc5f650359`. Role: test-path,source. Parse: module.

- (anonymous) @11-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/during-readystatechange.window.js

Blob: `49d5051c2564c257f916c00d2d73864d129b0a77`. Role: test-path,source. Parse: module.

- (anonymous) @6-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/iframe_005.js

Blob: `bf038f70049ae6f2ca152ba09ae10377a4d7dea7`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/module-dynamic-import.mjs

Blob: `74d242753706c09739d03e3bc8e9c7f33657e8a2`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/module-static-import-delayed.mjs

Blob: `45478d6f638afd4621f540d6b0861df045707fed`. Role: test-path,source. Parse: module.

- (anonymous) @1-5; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/module-static-import.mjs

Blob: `74d242753706c09739d03e3bc8e9c7f33657e8a2`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/module-tla-import.mjs

Blob: `74d242753706c09739d03e3bc8e9c7f33657e8a2`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/nested-document-write-external.js

Blob: `bf91daf986e8ccf0aaf1c2a96ca6ca31036c41b0`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/document-write/resources/mutation-observer-iframe-script.js

Blob: `0267705294ab7bac0243bb1ffde09f7bb3d44cc2`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/html-unsafe-methods/resources/did-run.js

Blob: `6cd92dc98bbc25e15dcd72501e97f54c75e06f76`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/html-unsafe-methods/resources/parseHTMLUnsafe-iframe.js

Blob: `4a0b56869beb568af3bd261fc46e1b915ed7d7c8`. Role: test-path,source. Parse: module.

- window.doParse @1-3; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/html-unsafe-methods/resources/parseHTMLUnsafe-url-tests.js

Blob: `88344d127cee3cc749c34c714f8c5e73b009f8e4`. Role: test-path,source. Parse: module.

- (anonymous) @1-1; ArrowFunctionExpression; parameters=1; async=false; generator=false
- assertURL @3-7; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @15-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-27; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-35; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/abort-refresh-immediate.window.js

Blob: `8d045b9e0ab56874c5eb32367ed56274e0e94a22`. Role: test-path,source. Parse: module.

- (anonymous) @5-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-92; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-119; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @98-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @99-117; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @108-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @114-116; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/abort-refresh-multisecond-header.window.js

Blob: `8c6c1267c4e899a78bd3ad0e67fd8491fd139606`. Role: test-path,source. Parse: module.

- (anonymous) @8-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/abort-refresh-multisecond-meta.window.js

Blob: `2895f959e55dc3cf2fdfc933c751699b09438b50`. Role: test-path,source. Parse: module.

- (anonymous) @8-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/abort-while-navigating.window.js

Blob: `e3efeffb8b3af56d365336dba357e0d76f7295aa`. Role: test-path,source. Parse: module.

- (anonymous) @1-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @94-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @103-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @114-131; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-129; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-149; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @135-135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @153-179; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @155-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @156-177; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @167-171; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @174-176; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/abort.sub.window.js

Blob: `b2f05cf056d54a0602a55a8dda7c67cb94883055`. Role: test-path,source. Parse: failed.

Failure: Unexpected token {


### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/aborted-parser.window.js

Blob: `ba7278ef18adb42b3f527a9c27ff3a51bdb4dbf7`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-30; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/active.window.js

Blob: `f96710999adedff334a656cacdde0fa8d561fd0c`. Role: test-path,source. Parse: module.

- assertOpenIsEffective @1-21; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-61; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-82; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @84-87; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @89-98; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-94; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-exception-vs-return-origin.sub.window.js

Blob: `b20c3e3f31798efb2ee151ee752c0ce56dbb0b68`. Role: test-path,source. Parse: module.

- setEntryToTopLevel @7-9; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @11-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-60; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-86; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @65-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-116; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-114; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @102-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-108; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-exception-vs-return-xml.window.js

Blob: `45a67f925bc10f5d5dfd7bb744850f050dc45dcf`. Role: test-path,source. Parse: module.

- (anonymous) @1-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-20; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-side-effects-ignore-opens-during-unload.window.js

Blob: `98ffba20a1a17ce12881c68a736db5a81d3e3289`. Role: test-path,source. Parse: module.

- (anonymous) @4-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9-14; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-side-effects-same-origin-domain.sub.window.js

Blob: `f5edd7aed9c19cb884fb399441d714542a700e3b`. Role: test-path,source. Parse: module.

- (anonymous) @6-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-12; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-side-effects-synchronous-script.window.js

Blob: `fb26c70a9cb76e7ff99bc87939a0a828ccc9d578`. Role: test-path,source. Parse: module.

- (anonymous) @3-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-16; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/bailout-side-effects-xml.window.js

Blob: `bbfc015c68e95d5aa8526936adf9693bcacef973`. Role: test-path,source. Parse: module.

- (anonymous) @3-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/beforeunload.window.js

Blob: `1e2f891c1766bb1bcf37855476d952b09e4faab2`. Role: test-path,source. Parse: module.

- (anonymous) @4-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-16; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/crbug-583445-regression.window.js

Blob: `3809c2e081a543da4d79423122e4ae765d28dda8`. Role: test-path,source. Parse: module.

- nextMessage @13-19; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @14-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @21-126; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @65-118; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-113; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-111; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/custom-element.window.js

Blob: `1ad06b3d372c7fda351893da9e8a009d3134dfa6`. Role: test-path,source. Parse: module.

- constructor @16-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class CustomElement @15-24

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/encoding.window.js

Blob: `f0d133a5329017814f21b206934a554955d15f88`. Role: test-path,source. Parse: module.

- (anonymous) @1-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-11; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/event-listeners.window.js

Blob: `df07124d811135cafcfa9908ece9410f19ccdefa`. Role: test-path,source. Parse: module.

- (anonymous) @5-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @96-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @98-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @103-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-136; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @124-124; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @126-126; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @138-165; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @140-161; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @147-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @150-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @167-174; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @169-169; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @176-196; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @178-178; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @179-194; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @186-192; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @198-210; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @212-219; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @215-215; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @221-228; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @224-224; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @230-244; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @232-240; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @236-236; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @246-258; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @249-249; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @262-277; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @265-265; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @267-267; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @279-291; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @281-281; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @283-286; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @293-308; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @299-299; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @300-302; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @304-306; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/history-state.window.js

Blob: `7fb172a141cf93330d6ec718d200e5845cd32f39`. Role: test-path,source. Parse: module.

- (anonymous) @1-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-28; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/history.window.js

Blob: `0134da24f07bb4d653703d2d3d0c3575a32e8f34`. Role: test-path,source. Parse: module.

- (anonymous) @14-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/ignore-opens-during-unload.window.js

Blob: `43506a22a46da53885a2b5a0888095bc52b460ca`. Role: test-path,source. Parse: module.

- (anonymous) @2-2; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-4; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-55; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/mutation-observer.window.js

Blob: `34e73146a9d8e4ecab1e74a0079cd721e7306e59`. Role: test-path,source. Parse: module.

- (anonymous) @1-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-16; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/no-new-global.window.js

Blob: `d4a9296fca66d3017c267a8d8951bef2dcbee238`. Role: test-path,source. Parse: module.

- (anonymous) @5-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testIdentity @17-48; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @18-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/quirks.window.js

Blob: `0ff0bb99443677b8f8844c8ecedef22c408f2bac`. Role: test-path,source. Parse: module.

- (anonymous) @1-9; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-74; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/readiness.window.js

Blob: `729a958700bb8d5e5f9d8717287ea114badbb662`. Role: test-path,source. Parse: module.

- (anonymous) @4-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-12; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/reload.window.js

Blob: `279020f64da8421e118a447bae1373da2e98d9c1`. Role: test-path,source. Parse: module.

- (anonymous) @19-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-51; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/remove-initial-about-blankness.window.js

Blob: `f2575de77657d70140c1715fe1e61832a4352e81`. Role: test-path,source. Parse: module.

- (anonymous) @7-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-63; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/resources/document-open-side-effects.js

Blob: `7cb86dcba0236d1e161989e95de172ebbf7852e0`. Role: test-path,source. Parse: module.

- assertDocumentIsReadyForSideEffectsTest @1-3; FunctionDeclaration; parameters=2; async=false; generator=false
- assertOpenHasNoSideEffects @5-8; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/tasks.window.js

Blob: `887adcb7393ee3bf3acfcba1a6a7d820f0ebb6ff`. Role: test-path,source. Parse: module.

- taskTest @18-54; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-59; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @61-74; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @66-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @76-80; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @82-89; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @84-86; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-106; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @100-103; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/type-argument-plaintext.window.js

Blob: `ab1d9706a46a848f753e6ad25ad86454d92b8f1d`. Role: test-path,source. Parse: module.

- (anonymous) @8-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/type-argument.window.js

Blob: `9174008da33b7faeba91169efe3ace6e1dc87704`. Role: test-path,source. Parse: module.

- (anonymous) @8-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/unload.window.js

Blob: `e275a4987a0859b160a0f91de6c8896b90bdab31`. Role: test-path,source. Parse: module.

- (anonymous) @4-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-17; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/url-entry-document-sync-call.window.js

Blob: `f20b4341e36cb2bba00f21e452c0e6bcfa529238`. Role: test-path,source. Parse: module.

- (anonymous) @2-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-4; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-10; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/url-entry-document.window.js

Blob: `c3a1c3a874f3577716d3d8075b2e91a5d257ad43`. Role: test-path,source. Parse: module.

- (anonymous) @1-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-16; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/url-fragment.window.js

Blob: `0c528935b52db9f2bc85cdd52659c300bfda5f5a`. Role: test-path,source. Parse: module.

- (anonymous) @1-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-4; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-25; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/html/webappapis/dynamic-markup-insertion/opening-the-input-stream/url.window.js

Blob: `4e7c649f4533958112e6bd1dd59537619d7cc62d`. Role: test-path,source. Parse: module.

- (anonymous) @1-9; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-36; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-93; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @88-88; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/microtask-queuing/queue-microtask-exceptions.any.js

Blob: `01f32ac9ba14962fa99d4b263a8ca0f5a0daa161`. Role: test-path,source. Parse: module.

- (anonymous) @8-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/microtask-queuing/queue-microtask.any.js

Blob: `e67765fade3bc64883782ffde985c915444832be`. Role: test-path,source. Parse: module.

- (anonymous) @4-6; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleEvent @13-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/microtask-queuing/queue-microtask.window.js

Blob: `78cdcfc5d989a81882a10b7d70050408aadfe924`. Role: test-path,source. Parse: module.

- queueMicrotaskViaMO @5-10; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @15-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/event-loops/resources/async.js

Blob: `5b6470d5a447e60acfba9393d42811a93f9adb18`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/scripting/event-loops/resources/common.js

Blob: `e2279f93ddb09d14d7065c89357ab102e0ba0ce0`. Role: test-path,source. Parse: module.

- log_test @8-20; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @9-19; FunctionExpression; parameters=1; async=false; generator=false
- log @11-17; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/event-loops/resources/defer.js

Blob: `d8498d274fb6f714c7394868970ee7da63910ac6`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-idl-attribute-realm.window.js

Blob: `710feea2cbd184f6ee2f5484959fa19d226f0bc5`. Role: test-path,source. Parse: module.

- (anonymous) @3-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getErrorRealm @48-59; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/resources/no-op-worker.js

Blob: `3918c74e446336be4151ea3bdad00f4d9e6df47a`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/resources/worker-with-syntax-error.js

Blob: `dc9a0dbf4a11a30f28e2079154a673797e5d2d6f`. Role: test-path,source. Parse: failed.

Failure: Unexpected token 3


### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/synthetic-errorevent-click.worker.js

Blob: `177a99e2ce1d7f61c1fca5e2e87a9bc3dc6a1c9d`. Role: test-path,source. Parse: module.

- (anonymous) @6-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/workerglobalscope-runtime-error.worker.js

Blob: `264fef810dfc7c17479596d617cd4861fd84b0b5`. Role: test-path,source. Parse: module.

- (anonymous) @6-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-32; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/workerglobalscope-synthetic-errorevent.worker.js

Blob: `a14f6e01a9bbe414bbbffda2d64bce5e65ba63b6`. Role: test-path,source. Parse: module.

- (anonymous) @6-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-33; FunctionExpression; parameters=5; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-processing-algorithm-error/workerglobalscope-synthetic-event.worker.js

Blob: `a3e16ded885626732dc186fbec70443b57674cdf`. Role: test-path,source. Parse: module.

- (anonymous) @6-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-removal.window.js

Blob: `a20e2ec1d2e63ef4e5a1479b4d16c60d08c0c280`. Role: test-path,source. Parse: module.

- (anonymous) @3-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @67-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/event-handler-spec-example.window.js

Blob: `abf46882aabda3184052e471ab94c542e01eeef7`. Role: test-path,source. Parse: module.

- (anonymous) @1-1; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-22; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-41; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/invalid-uncompiled-raw-handler-compiled-late.window.js

Blob: `2892a4c3ab98740dc2fa8240b91217ff6dd49e17`. Role: test-path,source. Parse: module.

- (anonymous) @3-16; FunctionExpression; parameters=0; async=false; generator=false
- window.onerror @5-7; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/invalid-uncompiled-raw-handler-compiled-once.window.js

Blob: `b39b54b0e9cea49e4628b72ddd84e236cb57e77a`. Role: test-path,source. Parse: module.

- window.onerror @4-6; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/invalid-uncompiled-raw-handler-keeps-position.window.js

Blob: `f9443bf99a0a9dfd937d8d1cf3bd618a3734aa1c`. Role: test-path,source. Parse: module.

- (anonymous) @3-20; FunctionExpression; parameters=0; async=false; generator=false
- window.onerror @5-7; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false
- div.onclick @17-17; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/events/resources/event-handler-body.js

Blob: `ae2f5409a37888f1366e5deaa51f40f9a4fc9507`. Role: test-path,source. Parse: module.

- handlersInInterface @4-6; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5-5; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- runEventHandlerReflectionTest @24-70; FunctionDeclaration; parameters=9; async=false; generator=false
- f @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @48-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @60-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-64; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/integration-with-the-javascript-agent-formalism/atomics-wait-async.https.any.js

Blob: `3a3ea40d773f9b36314e714a17212f8ceed1f660`. Role: test-path,source. Parse: module.

- (anonymous) @3-11; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @13-25; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/integration-with-the-javascript-agent-formalism/requires-failure.https.any.js

Blob: `fddf85dbede1a36d4f161b638f19c39f8300ac47`. Role: test-path,source. Parse: module.

- (anonymous) @3-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/integration-with-the-javascript-agent-formalism/requires-success.any.js

Blob: `0da449a7cff8aa18ad06822bd2da1d868db5af6c`. Role: test-path,source. Parse: module.

- (anonymous) @3-9; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/integration-with-the-javascript-agent-formalism/resources/notify-worker.js

Blob: `2780e5bc34eec9e49d4311459cd7fc285fbe3f65`. Role: test-path,source. Parse: module.

- onmessage @1-5; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/syntax-error-in-setInterval.js

Blob: `afec114458b37a31f28bc6833a93dfb604ed2f84`. Role: test-path,source. Parse: module.

- (anonymous) @2-8; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-7; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/syntax-error-in-setTimeout.js

Blob: `427542b42ec39d555599894e175393b4f157918d`. Role: test-path,source. Parse: module.

- (anonymous) @2-7; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3-6; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/syntax-error.js

Blob: `0f74a6fca63abdec0e7ed36c71ac7cf1fca5a02d`. Role: test-path,source. Parse: failed.

Failure: Unexpected token )


### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/undefined-variable-in-setInterval.js

Blob: `c2a017a2abfbe4bac9720139f83ae0775c2e9ecc`. Role: test-path,source. Parse: module.

- (anonymous) @2-8; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4-7; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/undefined-variable-in-setTimeout.js

Blob: `6fa54cda9fb847dce7d9cc5bd5078d07f0f3f25a`. Role: test-path,source. Parse: module.

- (anonymous) @2-7; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3-6; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/support/undefined-variable.js

Blob: `e73a62ceda3c31228d1557cb4cfdafb156d740aa`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/unhandled-promise-rejections/support/promise-rejection-events-many-promises.js

Blob: `af8cd9332eee0eda01a94986a362caa18a1dc234`. Role: test-path,source. Parse: module.

- rejectMany @16-25; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForEvents @29-46; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @30-45; FunctionExpression; parameters=1; async=false; generator=false
- listener @33-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- recordEvents @49-59; FunctionDeclaration; parameters=3; async=false; generator=false
- listener @51-55; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-57; FunctionExpression; parameters=0; async=false; generator=false
- tick @61-63; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @62-62; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-77; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-76; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @71-71; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-96; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @83-89; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @84-86; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-88; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-93; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-95; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @99-124; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-113; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @107-109; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-121; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @118-118; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @121-123; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @126-146; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @136-138; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-143; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @143-145; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @149-171; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @152-154; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @154-164; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @158-162; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @159-161; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @164-170; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @168-168; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @174-211; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @179-201; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @180-196; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @190-194; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @191-193; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @198-200; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-210; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @205-205; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/processing-model-2/unhandled-promise-rejections/support/promise-rejection-events.js

Blob: `036e1784dbb79e07cd533256cd391583191f4aa8`. Role: test-path,source. Parse: module.

- (anonymous) @14-21; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-32; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @34-45; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-44; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-58; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-57; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @54-56; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @60-74; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-65; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-73; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-71; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-94; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @81-81; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @84-88; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @85-87; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-93; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @89-91; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-117; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @101-101; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @103-116; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @104-115; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-114; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @108-113; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @109-111; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @119-128; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @123-123; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @125-127; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-139; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @134-134; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-138; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-154; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @145-145; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @147-153; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @148-152; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @149-151; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @156-163; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @160-160; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-181; FunctionExpression; parameters=1; async=false; generator=false
- unhandled @168-176; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @170-173; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @187-195; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @191-191; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @194-194; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @197-205; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @201-201; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @204-204; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @208-218; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @212-212; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @215-217; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @217-217; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @221-235; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @225-225; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @228-230; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @230-234; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @231-233; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @238-252; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @242-242; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @245-247; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @247-251; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @248-250; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @255-273; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @259-259; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @262-268; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @263-267; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @264-266; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @268-272; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @269-271; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @276-288; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @280-280; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-287; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @283-285; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @286-286; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @291-298; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @294-294; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @297-297; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @305-316; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @309-309; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @312-315; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @314-314; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @319-332; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @323-323; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @325-327; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @328-331; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @330-330; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @335-353; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @340-340; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @341-341; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @343-347; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @344-346; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @349-352; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @351-351; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @360-376; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @364-364; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @367-375; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @368-374; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @369-373; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @370-372; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @371-371; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @378-396; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @382-382; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @384-395; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @386-394; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @387-393; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @388-392; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @389-391; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @390-390; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @399-417; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @403-403; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @405-416; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @407-415; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @408-414; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @409-413; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @410-412; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @411-411; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @420-436; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @424-424; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @427-435; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @428-434; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @429-433; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @430-432; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @431-431; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @438-456; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @442-442; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @444-455; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @446-454; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @447-453; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @448-452; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @449-451; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @450-450; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @459-477; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @463-463; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @465-476; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @467-475; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @468-474; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @469-473; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @470-472; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @471-471; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @489-504; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @493-493; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @496-498; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @500-503; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @502-502; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @506-518; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @510-510; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @513-517; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @514-516; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @515-515; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @521-539; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @525-525; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @527-537; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @528-536; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @529-535; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @530-534; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @531-533; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @532-532; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @542-560; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @546-546; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @549-559; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @550-558; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @551-557; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @552-556; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @553-555; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @554-554; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @568-585; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @572-572; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @575-577; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @579-584; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @580-583; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @582-582; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @587-601; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @591-591; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @594-600; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @595-599; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @596-598; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @597-597; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @604-624; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @608-608; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @610-622; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @611-621; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @612-620; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @613-619; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @614-618; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @615-617; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @616-616; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @627-647; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @631-631; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @634-646; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @635-645; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @636-644; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @637-643; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @638-642; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @639-641; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @640-640; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @650-688; FunctionExpression; parameters=1; async=false; generator=false
- unhandled @656-663; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @658-661; FunctionExpression; parameters=0; async=false; generator=false
- handled @664-673; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @666-671; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @678-680; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @681-687; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @683-686; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @685-685; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @690-725; FunctionExpression; parameters=1; async=false; generator=false
- unhandled @695-702; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @697-700; FunctionExpression; parameters=0; async=false; generator=false
- handled @703-712; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @705-710; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @718-724; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @720-723; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @722-722; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @731-749; FunctionExpression; parameters=1; async=false; generator=false
- l @733-745; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @735-737; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @738-744; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @740-742; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @759-790; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @767-773; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @769-772; FunctionExpression; parameters=0; async=false; generator=false
- l @775-780; FunctionDeclaration; parameters=1; async=false; generator=false
- checkSequence @782-789; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @784-786; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @792-822; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @799-805; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @801-804; FunctionExpression; parameters=0; async=false; generator=false
- l @807-812; FunctionDeclaration; parameters=1; async=false; generator=false
- checkSequence @814-821; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @816-818; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @824-876; FunctionExpression; parameters=1; async=false; generator=false
- unhandled @834-858; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @838-856; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @839-842; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @844-847; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @849-852; FunctionExpression; parameters=0; async=false; generator=false
- handled @860-865; FunctionDeclaration; parameters=1; async=false; generator=false
- checkSequence @867-875; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @869-872; FunctionExpression; parameters=0; async=false; generator=false
- queueTask @885-900; FunctionDeclaration; parameters=1; async=false; generator=false
- d.ontoggle @888-890; FunctionExpression; parameters=0; async=false; generator=false
- channel.port1.onmessage @896-896; FunctionExpression; parameters=0; async=false; generator=false
- mutationObserverMicrotask @902-913; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @904-904; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @911-911; FunctionExpression; parameters=0; async=false; generator=false
- onUnhandledSucceed @915-927; FunctionDeclaration; parameters=3; async=false; generator=false
- l @916-924; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @918-921; FunctionExpression; parameters=0; async=false; generator=false
- onUnhandledFail @929-950; FunctionDeclaration; parameters=2; async=false; generator=false
- unhandled @930-936; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @932-934; FunctionExpression; parameters=0; async=false; generator=false
- handled @937-943; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @939-941; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @947-949; FunctionExpression; parameters=0; async=false; generator=false
- ensureCleanup @952-959; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @953-958; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/scripting/reporterror.any.js

Blob: `b9e7ba25bc6a3938783f7bf32472ba422e815ae2`. Role: test-path,source. Parse: module.

- (anonymous) @7-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- name @31-34; FunctionExpression; parameters=0; async=false; generator=false
- message @35-38; FunctionExpression; parameters=0; async=false; generator=false
- fileName @39-42; FunctionExpression; parameters=0; async=false; generator=false
- lineNumber @43-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/webappapis/structured-clone/structured-clone-battery-of-tests-harness.js

Blob: `00a86fa74b9a968dabae400f57dd32ffb836aa2c`. Role: test-path,source. Parse: module.

- runStructuredCloneBatteryOfTests @16-45; FunctionDeclaration; parameters=1; async=false; generator=false
- setup @18-18; FunctionExpression; parameters=0; async=false; generator=false
- preTest @19-19; FunctionExpression; parameters=0; async=false; generator=false
- postTest @20-20; FunctionExpression; parameters=0; async=false; generator=false
- teardown @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-41; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/webappapis/structured-clone/structured-clone-battery-of-tests-with-transferables.js

Blob: `c9ffa1e54de9bf6394f02ff4916476f0ed74512b`. Role: test-path,source. Parse: module.

- f @3-8; FunctionExpression; parameters=1; async=true; generator=false
- f @13-19; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- f @24-33; FunctionExpression; parameters=1; async=true; generator=false
- f @38-43; FunctionExpression; parameters=1; async=true; generator=false
- f @48-56; FunctionExpression; parameters=2; async=true; generator=false
- f @61-69; FunctionExpression; parameters=2; async=true; generator=false
- f @74-81; FunctionExpression; parameters=2; async=true; generator=false
- f @86-96; FunctionExpression; parameters=1; async=true; generator=false
- f @101-120; FunctionExpression; parameters=1; async=true; generator=false
- f @125-132; FunctionExpression; parameters=1; async=true; generator=false
- f @137-147; FunctionExpression; parameters=1; async=true; generator=false
- f @152-162; FunctionExpression; parameters=1; async=true; generator=false
- f @167-176; FunctionExpression; parameters=2; async=true; generator=false
- f @181-190; FunctionExpression; parameters=2; async=true; generator=false
- Class ReadableStreamSubclass @116-116

### testing/web-platform/tests/html/webappapis/structured-clone/structured-clone-battery-of-tests.js

Blob: `9a1a710d8a57d4e3574cd92a9d905b2ea69242b9`. Role: test-path,source. Parse: module.

- check @5-18; FunctionDeclaration; parameters=4; async=false; generator=false
- f @8-15; FunctionExpression; parameters=1; async=true; generator=false
- compare_primitive @20-22; FunctionDeclaration; parameters=2; async=false; generator=false
- compare_Array @23-32; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @24-31; FunctionExpression; parameters=2; async=true; generator=false
- compare_Object @34-43; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @35-42; FunctionExpression; parameters=2; async=true; generator=false
- enumerate_props @45-51; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @46-50; FunctionExpression; parameters=2; async=true; generator=false
- compare_Boolean @119-125; FunctionDeclaration; parameters=2; async=false; generator=false
- compare_obj @131-140; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @133-139; FunctionExpression; parameters=2; async=false; generator=false
- compare_Date @191-197; FunctionDeclaration; parameters=2; async=false; generator=false
- compare_RegExp @211-226; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @213-225; FunctionExpression; parameters=2; async=false; generator=false
- func_RegExp_flags_lastIndex @227-231; FunctionDeclaration; parameters=0; async=false; generator=false
- func_RegExp_sticky @232-234; FunctionDeclaration; parameters=0; async=false; generator=false
- func_RegExp_unicode @235-237; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @245-245; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @246-246; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @251-251; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @252-252; FunctionExpression; parameters=0; async=false; generator=false
- compare_Error @257-265; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @272-276; ArrowFunctionExpression; parameters=0; async=false; generator=false
- compare_Blob @279-296; FunctionDeclaration; parameters=3; async=true; generator=false
- func_Blob_basic @297-299; FunctionDeclaration; parameters=0; async=false; generator=false
- b @302-304; FunctionDeclaration; parameters=1; async=false; generator=false
- encode_cesu8 @305-315; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @309-313; FunctionExpression; parameters=1; async=false; generator=false
- func_Blob_bytes @316-325; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @317-324; FunctionExpression; parameters=0; async=false; generator=false
- func_Blob_empty @330-332; FunctionDeclaration; parameters=0; async=false; generator=false
- func_Blob_NUL @334-336; FunctionDeclaration; parameters=0; async=false; generator=false
- compare_File @354-359; FunctionDeclaration; parameters=2; async=true; generator=false
- func_File_basic @360-362; FunctionDeclaration; parameters=0; async=false; generator=false
- compare_FileList @365-373; FunctionDeclaration; parameters=2; async=false; generator=false
- func_FileList_empty @374-378; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @380-380; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @381-381; ArrowFunctionExpression; parameters=0; async=false; generator=false
- compare_ArrayBuffer @383-389; FunctionDeclaration; parameters=2; async=false; generator=false
- compare_ArrayBufferView @391-405; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @393-404; FunctionExpression; parameters=2; async=false; generator=false
- compare_ImageData @406-413; FunctionDeclaration; parameters=2; async=false; generator=false
- func_ImageData_1x1_transparent_black @414-418; FunctionDeclaration; parameters=0; async=false; generator=false
- func_ImageData_1x1_non_transparent_non_black @420-429; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @431-431; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @432-432; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @433-433; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @434-434; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @438-442; FunctionExpression; parameters=0; async=false; generator=false
- check_circular_property @444-448; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @445-447; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @449-453; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @454-458; FunctionExpression; parameters=0; async=false; generator=false
- check_identical_property_values @459-463; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @460-462; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @464-467; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @468-471; FunctionExpression; parameters=0; async=false; generator=false
- check_absent_property @473-477; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @474-476; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @478-482; FunctionExpression; parameters=0; async=false; generator=false
- Foo @479-479; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @484-488; FunctionExpression; parameters=0; async=false; generator=false
- check_writable_property @490-496; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @491-495; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @497-501; FunctionExpression; parameters=0; async=false; generator=false
- check_configurable_property @503-509; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @504-508; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @510-514; FunctionExpression; parameters=0; async=false; generator=false
- f @518-530; FunctionExpression; parameters=2; async=true; generator=false
- testProperty @521-523; FunctionExpression; parameters=0; async=false; generator=false
- get_canvas_1x1_transparent_black @536-541; FunctionDeclaration; parameters=0; async=false; generator=false
- get_canvas_1x1_non_transparent_non_black @543-554; FunctionDeclaration; parameters=0; async=false; generator=false
- compare_ImageBitmap @556-562; FunctionDeclaration; parameters=2; async=false; generator=false
- f @566-571; FunctionExpression; parameters=1; async=true; generator=false
- f @577-582; FunctionExpression; parameters=1; async=true; generator=false
- f @588-593; FunctionExpression; parameters=1; async=true; generator=false
- f @599-604; FunctionExpression; parameters=1; async=true; generator=false
- f @610-615; FunctionExpression; parameters=1; async=true; generator=false
- f @621-626; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @631-631; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @632-641; ArrowFunctionExpression; parameters=2; async=false; generator=false
- f @646-653; FunctionExpression; parameters=2; async=true; generator=false
- f @658-668; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @673-676; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @677-679; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @684-688; ArrowFunctionExpression; parameters=0; async=false; generator=false
- f @693-707; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @712-716; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @721-725; ArrowFunctionExpression; parameters=0; async=false; generator=false
- f @730-739; FunctionExpression; parameters=2; async=true; generator=false
- f @744-753; FunctionExpression; parameters=2; async=true; generator=false
- Class FileSubclass @674-674

### testing/web-platform/tests/html/webappapis/structured-clone/structured-clone.any.js

Blob: `1358a71fc03d4e06fe8ae2701fc647d4892e9e5d`. Role: test-path,source. Parse: module.

- structuredClone @8-12; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [024b68f6-ed8e-49a6-930c-2b0e5dadb003.md](024b68f6-ed8e-49a6-930c-2b0e5dadb003.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `7f60a3fd0d74d27dc80d4a3040684ef943f8404a7ebab0d6913e8cf59d0e2643`.
