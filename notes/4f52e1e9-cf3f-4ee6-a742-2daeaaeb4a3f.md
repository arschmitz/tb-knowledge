<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["dom"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["98939e1ada8d8101e26c95caf21659cd37a8f33a646c83a4dbc14b6469c25e8a"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/d2866cf1-a2cf-4ed2-9df6-4b4601e1980a.md"}} -->
# firefox/dom JavaScript function map 179

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### dom/tests/mochitest/localstorage/localStorageCommon.js

Blob: `07d5ba9f88e401b464b5bd23d5e492c9543a5a8b`. Role: test-path,source. Parse: module.

- localStorageFlush @1-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @3-5; FunctionExpression; parameters=0; async=false; generator=false
- observe @10-13; FunctionExpression; parameters=3; async=false; generator=false
- localStorageReload @19-36; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @25-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-35; FunctionExpression; parameters=0; async=false; generator=false
- localStorageFlushAndReload @38-54; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @44-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-53; FunctionExpression; parameters=0; async=false; generator=false
- localStorageClearAll @56-93; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @61-85; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @62-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @70-82; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @71-82; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @90-92; FunctionExpression; parameters=0; async=false; generator=false
- localStorageClearDomain @95-109; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @106-108; FunctionExpression; parameters=0; async=false; generator=false
- os @111-113; FunctionDeclaration; parameters=0; async=false; generator=false
- notify @115-117; FunctionDeclaration; parameters=1; async=false; generator=false
- localStorageEnableTestingMode @122-132; FunctionDeclaration; parameters=1; async=false; generator=false

### dom/tests/mochitest/pointerlock/pointerlock_utils.js

Blob: `050d1610704fd68a2398054ba30eb3557c242630`. Role: test-path,source. Parse: module.

- window.ok @10-12; FunctionExpression; parameters=2; async=false; generator=false
- window.is @14-16; FunctionExpression; parameters=3; async=false; generator=false
- window.isnot @18-20; FunctionExpression; parameters=3; async=false; generator=false
- window.todo @22-24; FunctionExpression; parameters=2; async=false; generator=false
- window.todo_is @26-28; FunctionExpression; parameters=3; async=false; generator=false
- window.todo_isnot @30-32; FunctionExpression; parameters=3; async=false; generator=false
- window.info @34-36; FunctionExpression; parameters=1; async=false; generator=false
- SimpleTest.waitForExplicitFinish @41-43; FunctionExpression; parameters=0; async=false; generator=false
- SimpleTest.finish @45-48; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-62; FunctionExpression; parameters=0; async=false; generator=false
- inFullscreenMode @66-68; FunctionDeclaration; parameters=1; async=false; generator=false
- addFullscreenChangeContinuation @77-112; FunctionDeclaration; parameters=3; async=false; generator=false
- checkCondition @80-92; FunctionDeclaration; parameters=0; async=false; generator=false
- onFullscreenChange @93-110; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @101-101; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @104-105; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @107-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @108-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @108-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/TestUtils.sys.mjs @2; ChromeUtils-import-literal

### dom/tests/mochitest/script/file_blocked_script.sjs

Blob: `b246dad607c5f1a86f20e1d1d1593fa849369be9`. Role: test-path,data-or-other. Parse: module.

- setGlobalState @5-14; FunctionDeclaration; parameters=2; async=false; generator=false
- QueryInterface @8-10; FunctionExpression; parameters=1; async=false; generator=false
- getGlobalState @16-22; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=1; async=false; generator=false
- finishBlockedRequest @24-32; FunctionDeclaration; parameters=3; async=false; generator=false
- handleRequest @34-68; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/tests/mochitest/script/slow.sjs

Blob: `39a75acd8670c494e6a1426f4b1d04c28a4a7865`. Role: test-path,data-or-other. Parse: module.

- handleRequest @1-13; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @6-9; FunctionExpression; parameters=0; async=false; generator=false

### dom/tests/mochitest/script/subdir/bug1656248_import.mjs

Blob: `7a4e8a723a40729b6e762041efee0922abd27bd9`. Role: test-path,source. Parse: module.


### dom/tests/mochitest/script/subdir/bug1656248_script.mjs

Blob: `ee65a6046a928e08d1a34c39c7e4f2684c8a21b2`. Role: test-path,source. Parse: module.

- (anonymous) @3-3; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-4; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ./bug1656248_import.mjs @2; dynamic-import-literal

### dom/tests/mochitest/script/test_bug1788532_moduleA.mjs

Blob: `d667aac48265b2503446dc5fd777ad147ea45102`. Role: test-path,source. Parse: module.

- (anonymous) @4-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module ./test_bug1788532_moduleB.mjs @3; dynamic-import-literal

### dom/tests/mochitest/script/test_bug1788532_moduleB.mjs

Blob: `71e2e7009b0e654711deb741e996e8363b5005bb`. Role: test-path,source. Parse: module.

- Module ./test_bug1788532_moduleA.mjs @2; ImportDeclaration

### dom/tests/mochitest/sessionstorage/interOriginSlave.js

Blob: `c4d423154228faa597ba6968fd6c472da7e457e3`. Role: test-path,source. Parse: module.

- postMsg @1-3; FunctionDeclaration; parameters=1; async=false; generator=false
- onMessageReceived @7-18; FunctionDeclaration; parameters=1; async=false; generator=false
- ok @20-26; FunctionDeclaration; parameters=2; async=false; generator=false
- is @28-34; FunctionDeclaration; parameters=3; async=false; generator=false
- finishTest @36-40; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/tests/mochitest/sessionstorage/interOriginTest.js

Blob: `4d2654e5dc16fa60c1727ec07c5bab34d6b0dd14`. Role: test-path,source. Parse: module.

- onMessageReceived @11-43; FunctionDeclaration; parameters=1; async=false; generator=false

### dom/tests/mochitest/storageevent/interOriginFrame.js

Blob: `f4b3d6c9ab936983c8a548b3c10f06878c6f6246`. Role: test-path,source. Parse: module.

- postMsg @6-14; FunctionDeclaration; parameters=2; async=false; generator=false
- onMessageReceived @18-38; FunctionDeclaration; parameters=1; async=false; generator=false
- ok @40-46; FunctionDeclaration; parameters=2; async=false; generator=false
- is @48-54; FunctionDeclaration; parameters=3; async=false; generator=false
- todo @56-58; FunctionDeclaration; parameters=3; async=false; generator=false
- finishTest @60-63; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/tests/mochitest/storageevent/interOriginTest2.js

Blob: `733f88a32d414d5ba2afc16fd62641e5e46f2621`. Role: test-path,source. Parse: module.

- onMessageReceived @16-60; FunctionDeclaration; parameters=1; async=false; generator=false

### dom/tests/mochitest/webcomponents/head.js

Blob: `23c91d63be04624fb9b8658b4d1d6a0755def7aa`. Role: test-path,source. Parse: module.

- createIframe @12-26; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @13-25; FunctionExpression; parameters=2; async=false; generator=false
- iframe.onload @15-17; FunctionExpression; parameters=0; async=false; generator=false
- iframe.onerror @18-20; FunctionExpression; parameters=0; async=false; generator=false

### dom/tests/mochitest/webcomponents/htmlconstructor_autonomous_tests.js

Blob: `75b42389cca50c573f6457452c96dd3d7036c1bf`. Role: test-path,source. Parse: module.

- (anonymous) @2-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @33-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @84-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ElementWithNonObjectPrototype @85-93; FunctionDeclaration; parameters=0; async=false; generator=false
- Class X @32-37

### dom/tests/mochitest/webcomponents/htmlconstructor_builtin_tests.js

Blob: `bb69659427e9b1fbf80b0313c281c5e28014761d`. Role: test-path,source. Parse: module.

- (anonymous) @132-312; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @136-310; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @139-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-143; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @151-158; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @153-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @161-174; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @167-169; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @181-193; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @185-187; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @198-212; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @204-206; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @216-283; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @219-222; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @228-230; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @286-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ElementWithNonObjectPrototype @287-296; FunctionDeclaration; parameters=0; async=false; generator=false
- Class X @218-223
- Class X @199-199
- Class X @182-182

### dom/tests/mochitest/webcomponents/upgrade_tests.js

Blob: `6dc78c390780f19bad7e9b9a2875ed30dc50434e`. Role: test-path,source. Parse: module.

- test_upgrade @1-14; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @3-6; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @9-13; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @18-26; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @28-37; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @39-58; FunctionExpression; parameters=3; async=false; generator=false
- constructor @42-47; FunctionExpression; parameters=0; async=false; generator=false
- window.onerror @51-54; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @60-81; FunctionExpression; parameters=3; async=false; generator=false
- constructor @62-67; FunctionExpression; parameters=1; async=false; generator=false
- window.onerror @71-74; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @84-105; FunctionExpression; parameters=3; async=false; generator=false
- constructor @86-91; FunctionExpression; parameters=1; async=false; generator=false
- window.onerror @95-98; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @111-129; FunctionExpression; parameters=3; async=false; generator=false
- constructor @113-118; FunctionExpression; parameters=0; async=false; generator=false
- window.onerror @122-125; FunctionExpression; parameters=5; async=false; generator=false
- Class MyOtherElement @112-119
- Class InstantiatesItselfBeforeSuper @85-92
- Class InstantiatesItselfAfterSuper @61-68
- Class ThrowCustomElement @41-48
- Class MyCustomElement @30-30
- Class MyCustomElement @19-19

### dom/tests/mochitest/whatwg/file_structuredCloneAndExposed.sjs

Blob: `e352078e2a5dff6e523ae8b1f73bcd32dacf8b86`. Role: test-path,data-or-other. Parse: module.

- handleRequest @3-22; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/tests/mochitest/whatwg/postMessage_structured_clone_helper.js

Blob: `b457fd2d2ff1ab30a576edbbb63da7b3e1b97baf`. Role: test-path,source. Parse: module.

- getTestContent @1-62; FunctionDeclaration; parameters=0; async=false; generator=true

### dom/tests/reftest/bug591981-script.js

Blob: `818596af3c37c495bce6b6730fafd26feba172f2`. Role: test-path,source. Parse: module.


### dom/tests/reftest/script592366-2.js

Blob: `c3c8e143e39a499436fc8c467c70d77f37cdb68c`. Role: test-path,source. Parse: module.


### dom/tests/unit/test_Fetch.js

Blob: `28c60a4757381111ff820ec0a90a6f0e7e8fc909`. Role: test-path,source. Parse: module.

- getBaseUrl @16-18; FunctionDeclaration; parameters=0; async=false; generator=false
- createTestData @21-36; FunctionDeclaration; parameters=1; async=false; generator=false
- readDataFromRequest @39-56; FunctionDeclaration; parameters=1; async=false; generator=false
- writeDataToResponse @59-66; FunctionDeclaration; parameters=2; async=false; generator=false
- test_GetData @69-129; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-95; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @99-123; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @118-122; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @124-128; FunctionExpression; parameters=1; async=false; generator=false
- test_GetDataNoInit @132-164; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-144; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @147-158; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @153-157; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @159-163; FunctionExpression; parameters=1; async=false; generator=false
- test_get40x @167-183; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @178-182; FunctionExpression; parameters=1; async=false; generator=false
- test_get50x @185-212; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @196-203; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @207-211; FunctionExpression; parameters=1; async=false; generator=false
- test_getTestFailedConnect @215-227; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @219-221; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @222-226; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_mozError @229-241; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @233-235; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @236-240; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_request_mozError @243-256; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @248-250; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @251-255; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_PostJSONData @259-301; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @265-279; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @288-295; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @296-300; FunctionExpression; parameters=1; async=false; generator=false
- test_PostTextData @304-355; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @313-327; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @336-349; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @350-354; FunctionExpression; parameters=1; async=false; generator=false
- test_https @357-382; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @365-368; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @371-373; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @374-376; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @377-381; ArrowFunctionExpression; parameters=0; async=true; generator=false
- run_test @384-395; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @392-394; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @393-393; FunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/httpd.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/NodeServer.sys.mjs @360; ChromeUtils-import-literal

### dom/tests/unit/test_PromiseDebugging.js

Blob: `d8cd4209fa086127ebaaa09b9b2cbf785bfc4437`. Role: test-path,source. Parse: module.

- run_test @1-20; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @4-6; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-17; FunctionExpression; parameters=0; async=false; generator=false

### dom/tests/unit/test_bug319968.js

Blob: `efde6843f0a70a4635dc4eb8fecd7eee938a652d`. Role: test-path,source. Parse: module.

- run_test @6-19; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/tests/unit/test_bug465752.js

Blob: `19c03a0e4da9b981efa878e14379bed1de361b3a`. Role: test-path,source. Parse: module.

- run_test @6-26; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/tests/unit/test_xhr_init.js

Blob: `0f7255806ec8a22fbfa3833c6f5bc993d7428bf1`. Role: test-path,source. Parse: module.

- run_test @1-21; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/url/tests/browser_download_after_revoke.js

Blob: `e343eee9eac6b1d5b4b3b88ad98b8aa5c4822fe6`. Role: test-path,source. Parse: module.

- test @1-99; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @11-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-97; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @20-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onOpenWindow @30-50; FunctionExpression; parameters=1; async=false; generator=false
- onModalLoad @35-47; FunctionDeclaration; parameters=0; async=false; generator=false
- onCloseWindow @51-51; FunctionExpression; parameters=0; async=false; generator=false
- onDownloadAdded @59-65; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @74-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-90; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/url/tests/esm_url_worker.js

Blob: `467129ebc89f81964f7188278cfec7a6563a0a50`. Role: test-path,source. Parse: module.

- onmessage @1-82; FunctionExpression; parameters=1; async=false; generator=false
- worker.onmessage @4-6; FunctionExpression; parameters=1; async=false; generator=false

### dom/url/tests/file_url.sys.mjs

Blob: `91bbe2bfa6bc022df068eda64fc1fbd2ecb999df`. Role: test-path,source. Parse: module.

- checkFromESM @1-22; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/url/tests/file_worker_url.sys.mjs

Blob: `761082f76b4da29c097dfc5f8a809c9e171e4f07`. Role: test-path,source. Parse: module.

- checkFromESM @1-21; FunctionDeclaration; parameters=3; async=false; generator=false
- worker.onmessage @3-11; FunctionExpression; parameters=1; async=false; generator=false
- worker.onerror @13-18; FunctionExpression; parameters=1; async=false; generator=false

### dom/url/tests/protocol_worker.js

Blob: `81e761ee0ef389b64d7f7a58ce94a443a938ea7e`. Role: test-path,source. Parse: module.

- ok @3-5; FunctionDeclaration; parameters=2; async=false; generator=false
- is @7-9; FunctionDeclaration; parameters=3; async=false; generator=false
- finish @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/url/tests/test_bug883784.sys.mjs

Blob: `5d646d17cae14b7c04271e95343860c1b7eb6f5e`. Role: test-path,source. Parse: module.

- start @2-35; FunctionExpression; parameters=3; async=false; generator=false
- worker.onmessage @4-24; FunctionExpression; parameters=1; async=false; generator=false
- xhr.onreadystatechange @10-16; FunctionExpression; parameters=0; async=false; generator=false
- xhr.onerror @17-21; FunctionExpression; parameters=0; async=false; generator=false
- worker.onerror @27-32; FunctionExpression; parameters=1; async=false; generator=false

### dom/url/tests/urlApi_worker.js

Blob: `b1f00eb3ee03b5784d281c6c58290a90b08bbb29`. Role: test-path,source. Parse: module.

- ok @1-4; FunctionDeclaration; parameters=2; async=false; generator=false
- is @6-13; FunctionDeclaration; parameters=3; async=false; generator=false
- onmessage @16-356; FunctionExpression; parameters=0; async=false; generator=false

### dom/url/tests/urlSearchParams_commons.js

Blob: `4a1308b94b61bc0b9195843f18b8f07bba531b61`. Role: test-path,source. Parse: module.

- testSimpleURLSearchParams @7-28; FunctionDeclaration; parameters=0; async=false; generator=false
- testCopyURLSearchParams @30-43; FunctionDeclaration; parameters=0; async=false; generator=false
- testURL @45-61; FunctionDeclaration; parameters=0; async=false; generator=false
- testParserURLSearchParams @63-113; FunctionDeclaration; parameters=0; async=false; generator=false
- testEncoding @115-133; FunctionDeclaration; parameters=0; async=false; generator=false
- testCopyConstructor @135-153; FunctionDeclaration; parameters=0; async=false; generator=false
- testOrdering @155-168; FunctionDeclaration; parameters=0; async=false; generator=false
- testDelete @170-180; FunctionDeclaration; parameters=0; async=false; generator=false
- testGetNULL @182-196; FunctionDeclaration; parameters=0; async=false; generator=false
- testSet @198-250; FunctionDeclaration; parameters=0; async=false; generator=false
- testIterable @252-314; FunctionDeclaration; parameters=0; async=false; generator=false
- testZeroHandling @315-327; FunctionDeclaration; parameters=0; async=false; generator=false
- testCTORs @329-380; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/url/tests/urlSearchParams_worker.js

Blob: `6c752987dbd1eaeb23ab2c69e89419c95392729d`. Role: test-path,source. Parse: module.

- ok @3-6; FunctionDeclaration; parameters=2; async=false; generator=false
- is @8-15; FunctionDeclaration; parameters=3; async=false; generator=false
- runTest @26-34; FunctionDeclaration; parameters=0; async=false; generator=false
- onmessage @36-46; FunctionExpression; parameters=0; async=false; generator=false

### dom/url/tests/url_exceptions_worker.js

Blob: `8bbd641136c5c82278f6b1607a174dd1edbf3714`. Role: test-path,source. Parse: module.

- ok @1-3; FunctionDeclaration; parameters=2; async=false; generator=false
- onmessage @5-38; FunctionExpression; parameters=0; async=false; generator=false

### dom/url/tests/url_worker.js

Blob: `4c6c902f77f8d9b6e12cf14880dc91c3b4681369`. Role: test-path,source. Parse: module.

- onmessage @1-96; FunctionExpression; parameters=1; async=false; generator=false
- worker.onmessage @4-6; FunctionExpression; parameters=1; async=false; generator=false

### dom/view-transitions/test/browser/browser_tab_detach_vt.js

Blob: `201b05f5c220b5c85641b0f093df7c2e5620f990`. Role: test-path,source. Parse: module.

- detachTab @20-34; FunctionDeclaration; parameters=1; async=true; generator=false
- test_tab_detach_active_vt @37-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @45-52; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-48; FunctionExpression; parameters=0; async=true; generator=false

### dom/vr/test/mochitest/VRSimulationDriver.js

Blob: `5b197b88e461a4c42849dfef1621b6cb23a99aa3`. Role: test-path,source. Parse: module.

- (anonymous) @4-95; FunctionExpression; parameters=0; async=false; generator=false
- AttachWebVRDisplay @7-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-16; FunctionExpression; parameters=1; async=false; generator=false
- SetVRDisplayPose @21-37; FunctionExpression; parameters=6; async=false; generator=false
- SetEyeResolution @39-41; FunctionExpression; parameters=2; async=false; generator=false
- SetEyeParameter @43-63; FunctionExpression; parameters=8; async=false; generator=false
- SetMountState @65-67; FunctionExpression; parameters=1; async=false; generator=false
- UpdateVRDisplay @69-71; FunctionExpression; parameters=0; async=false; generator=false
- AttachVRController @73-80; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-77; FunctionExpression; parameters=1; async=false; generator=false

### dom/vr/test/mochitest/WebVRHelpers.js

Blob: `e19294a236817e7613b668d1b1a1090e99f9203b`. Role: test-path,source. Parse: module.

- (anonymous) @1-19; FunctionExpression; parameters=0; async=false; generator=false
- RequestPresentOnVRDisplay @4-10; FunctionExpression; parameters=3; async=false; generator=false

### dom/vr/test/mochitest/requestPresent.js

Blob: `a2f9dd4d1143236f2734a7faa21ff0d0d9328c06`. Role: test-path,source. Parse: module.

- attachVRDisplay @5-12; FunctionDeclaration; parameters=1; async=false; generator=false
- setupVRDisplay @14-33; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @21-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- validateNewVRDisplay @37-58; FunctionDeclaration; parameters=2; async=false; generator=false
- validateDisplayNotPresenting @62-74; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/vr/test/mochitest/runVRTest.js

Blob: `13511b877a26c156e6f7c854fc4f71a1d4df689a`. Role: test-path,source. Parse: module.

- runVRTest @1-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @12-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/vr/test/reftest/VRSimulationDriver.js

Blob: `971cdb8626fbfe285403241e5c7c7262e848da0e`. Role: test-path,source. Parse: module.

- (anonymous) @5-60; FunctionExpression; parameters=0; async=false; generator=false
- AttachWebVRDisplay @8-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-16; FunctionExpression; parameters=1; async=false; generator=false
- SetVRDisplayPose @21-27; FunctionExpression; parameters=6; async=false; generator=false
- SetEyeResolution @29-31; FunctionExpression; parameters=2; async=false; generator=false
- SetEyeParameter @33-37; FunctionExpression; parameters=8; async=false; generator=false
- SetMountState @39-41; FunctionExpression; parameters=1; async=false; generator=false
- UpdateVRDisplay @43-45; FunctionExpression; parameters=0; async=false; generator=false

### dom/vr/test/reftest/webgl-util.js

Blob: `42f1c5ccd532e89418fee8589aa2a1b9d4319859`. Role: test-path,source. Parse: module.

- (anonymous) @1-61; FunctionExpression; parameters=0; async=false; generator=false
- createShaderById @6-31; FunctionDeclaration; parameters=2; async=false; generator=false
- createProgramByIds @33-55; FunctionDeclaration; parameters=3; async=false; generator=false

### dom/webauthn/WebAuthnRelatedOriginFetcher.sys.mjs

Blob: `1bafa6e8eb4053d0278f7f12ef172fbbaad3eab6`. Role: source. Parse: module.

- validateRelatedOrigins @18-61; FunctionDeclaration; parameters=2; async=false; generator=false
- fetchAndValidateRelatedOrigin @68-141; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @87-99; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @94-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @95-95; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @134-134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkRelatedOriginRequest @150-160; FunctionExpression; parameters=5; async=false; generator=false
- _run @162-194; FunctionExpression; parameters=4; async=true; generator=false
- _showAndroidPrompt @196-217; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @206-216; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _showDesktopPrompt @219-280; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @242-242; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callback @243-246; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @251-251; ArrowFunctionExpression; parameters=1; async=false; generator=false
- callback @252-255; ArrowFunctionExpression; parameters=0; async=false; generator=false
- eventCallback @263-268; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _resolve @282-286; FunctionExpression; parameters=0; async=false; generator=false
- _reject @288-292; FunctionExpression; parameters=0; async=false; generator=false
- _userCancel @294-298; FunctionExpression; parameters=0; async=false; generator=false
- cancel @300-314; FunctionExpression; parameters=0; async=false; generator=false
- Class WebAuthnRelatedOriginFetcher @143-315
- Module resource://gre/modules/AppConstants.sys.mjs @5; ImportDeclaration

### dom/webauthn/tests/browser/browser_abort_visibility.js

Blob: `56fe8d6311ef18b1aceb64bf1da8c9174c0a9d66`. Role: test-path,source. Parse: module.

- test_setup @10-17; FunctionExpression; parameters=0; async=true; generator=false
- assertStatus @24-35; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @28-32; FunctionExpression; parameters=0; async=true; generator=false
- waitForStatus @37-63; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @42-58; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @43-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startMakeCredentialRequest @65-98; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @66-97; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @89-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startGetAssertionRequest @100-133; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @101-132; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @123-125; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @126-129; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_switch_tab @137-164; FunctionDeclaration; parameters=0; async=true; generator=false
- waitForWindowActive @166-171; FunctionDeclaration; parameters=2; async=false; generator=false
- test_new_window_make @173-193; FunctionDeclaration; parameters=0; async=true; generator=false
- test_new_window_get @195-215; FunctionDeclaration; parameters=0; async=true; generator=false
- test_minimize_make @217-246; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @238-238; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_minimize_get @248-277; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @269-269; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webauthn/tests/browser/browser_fido_appid_extension.js

Blob: `8ca57e9aaa22093d9b0aa440b3ea7747db0cf20f`. Role: test-path,source. Parse: module.

- test_appid @18-76; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_same_site_appid @78-116; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @102-105; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @106-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_appid_unused @118-172; FunctionExpression; parameters=0; async=true; generator=false

### dom/webauthn/tests/browser/browser_webauthn_cert_override.js

Blob: `15ee1cea6f2506fb408c9146df5517de1f8685c3`. Role: test-path,source. Parse: module.

- test_webauthn_with_cert_override @9-125; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @33-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-73; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @128-134; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-142; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @144-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-158; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @160-166; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webauthn/tests/browser/browser_webauthn_conditional_mediation.js

Blob: `40dd3a31dd69d23921d47077a010ec1c0657482d`. Role: test-path,source. Parse: module.

- test_webauthn_modal_request_cancels_conditional_get @17-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_webauthn_resume_conditional_get @64-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @83-83; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startConditionalGet @121-136; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @126-128; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @129-131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_conditional_gets_in_two_tabs_coexist @138-174; FunctionExpression; parameters=0; async=true; generator=false
- test_promote_one_tab_leaves_other_pending @176-202; FunctionExpression; parameters=0; async=true; generator=false
- test_promote_then_promote_in_other_tab @206-240; FunctionExpression; parameters=0; async=true; generator=false
- test_modal_in_other_tab_leaves_conditional_pending @244-275; FunctionExpression; parameters=0; async=true; generator=false
- test_tab_close_clears_pending_conditional_get @280-305; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @290-290; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @302-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_webauthn_select_autofill_entry @307-370; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @329-329; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @339-348; ArrowFunctionExpression; parameters=2; async=false; generator=false

### dom/webauthn/tests/browser/browser_webauthn_ipaddress.js

Blob: `6658ae5f02ca320bf8bdb2287de5083fc79f4ea2`. Role: test-path,source. Parse: module.

- test_setup @11-15; FunctionExpression; parameters=0; async=true; generator=false
- test_appid @17-30; FunctionExpression; parameters=0; async=true; generator=false

### dom/webauthn/tests/browser/browser_webauthn_prompts.js

Blob: `74507ccd78afd2b5232cc2a0944072c2ff75de86`. Role: test-path,source. Parse: module.

- waitForPopupNotificationSecurityDelay @21-35; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @27-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_setup_usbtoken @37-44; FunctionExpression; parameters=0; async=true; generator=false
- test_setup_softtoken @52-63; FunctionExpression; parameters=0; async=true; generator=false
- promiseNavToolboxStatus @70-82; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @72-75; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @75-80; ArrowFunctionExpression; parameters=0; async=false; generator=false
- promiseFullScreenPaint @84-86; FunctionDeclaration; parameters=1; async=false; generator=false
- triggerMainPopupCommand @88-96; FunctionDeclaration; parameters=1; async=false; generator=false
- verifyAnonymizedCertificate @100-108; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @102-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyDirectCertificate @110-126; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_register @128-148; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_register_escape @150-170; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @160-160; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sign @172-192; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @182-182; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sign_escape @194-214; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @204-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sign_password_manager @218-290; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @238-240; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @252-271; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @272-272; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_switching @294-339; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @304-304; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @315-315; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @327-327; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_window_switching @343-391; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @353-353; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @357-357; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @366-366; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @379-379; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_register_direct_with_consent @393-412; FunctionDeclaration; parameters=0; async=true; generator=false
- test_register_direct_without_consent @414-433; FunctionDeclaration; parameters=0; async=true; generator=false
- test_select_sign_result @435-465; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @451-451; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_fullscreen_show_nav_toolbar @467-503; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @487-487; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_fullscreen_dom @505-538; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @510-512; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @523-523; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webauthn/tests/browser/head.js

Blob: `7ad1a1207b9e36d880fd3ba4c016981736f8d68c`. Role: test-path,source. Parse: module.

- add_virtual_authenticator @23-41; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- remove_virtual_authenticator @43-48; FunctionDeclaration; parameters=1; async=false; generator=false
- addCredential @50-83; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeCredential @85-91; FunctionDeclaration; parameters=2; async=true; generator=false
- memcmp @93-108; FunctionDeclaration; parameters=2; async=false; generator=false
- arrivingHereIsBad @110-112; FunctionDeclaration; parameters=1; async=false; generator=false
- expectError @114-119; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @116-118; FunctionExpression; parameters=1; async=false; generator=false
- promiseWebAuthnMakeCredential @122-172; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @131-170; FunctionExpression; parameters=1; async=false; generator=false
- copy @160-160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @163-169; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseWebAuthnGetAssertion @174-212; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @178-210; FunctionExpression; parameters=1; async=false; generator=false
- copy @197-197; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @200-209; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseWebAuthnGetAssertionDiscoverable @214-237; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @222-235; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @234-234; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkRpIdHash @239-252; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @242-251; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseNotification @254-265; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @255-264; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shown @256-263; FunctionExpression; parameters=0; async=false; generator=false

### dom/webauthn/tests/cbor.js

Blob: `3e1f300df35185ec0e7ab0ea65ed998d32970809`. Role: test-path,source. Parse: module.

- (anonymous) @25-406; FunctionExpression; parameters=2; async=false; generator=false
- encode @30-184; FunctionDeclaration; parameters=1; async=false; generator=false
- prepareWrite @36-52; FunctionDeclaration; parameters=1; async=false; generator=false
- commitWrite @53-55; FunctionDeclaration; parameters=0; async=false; generator=false
- writeFloat64 @56-58; FunctionDeclaration; parameters=1; async=false; generator=false
- writeUint8 @59-61; FunctionDeclaration; parameters=1; async=false; generator=false
- writeUint8Array @62-67; FunctionDeclaration; parameters=1; async=false; generator=false
- writeUint16 @68-70; FunctionDeclaration; parameters=1; async=false; generator=false
- writeUint32 @71-73; FunctionDeclaration; parameters=1; async=false; generator=false
- writeUint64 @74-81; FunctionDeclaration; parameters=1; async=false; generator=false
- writeTypeAndLength @82-98; FunctionDeclaration; parameters=2; async=false; generator=false
- encodeItem @100-172; FunctionDeclaration; parameters=1; async=false; generator=false
- decode @186-395; FunctionDeclaration; parameters=3; async=false; generator=false
- tagger @191-191; FunctionExpression; parameters=1; async=false; generator=false
- simpleValue @193-193; FunctionExpression; parameters=0; async=false; generator=false
- commitRead @195-198; FunctionDeclaration; parameters=2; async=false; generator=false
- readArrayBuffer @199-201; FunctionDeclaration; parameters=1; async=false; generator=false
- readFloat16 @202-220; FunctionDeclaration; parameters=0; async=false; generator=false
- readFloat32 @221-223; FunctionDeclaration; parameters=0; async=false; generator=false
- readFloat64 @224-226; FunctionDeclaration; parameters=0; async=false; generator=false
- readUint8 @227-229; FunctionDeclaration; parameters=0; async=false; generator=false
- readUint16 @230-232; FunctionDeclaration; parameters=0; async=false; generator=false
- readUint32 @233-235; FunctionDeclaration; parameters=0; async=false; generator=false
- readUint64 @236-238; FunctionDeclaration; parameters=0; async=false; generator=false
- readBreak @239-244; FunctionDeclaration; parameters=0; async=false; generator=false
- readLength @245-259; FunctionDeclaration; parameters=1; async=false; generator=false
- readIndefiniteStringLength @260-268; FunctionDeclaration; parameters=1; async=false; generator=false
- appendUtf16Data @270-300; FunctionDeclaration; parameters=2; async=false; generator=false
- decodeItem @302-389; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/webauthn/tests/u2futil.js

Blob: `263f4d3ef6b885534a6dd1d2e93c9fa315fb9f1d`. Role: test-path,source. Parse: module.

- addVirtualAuthenticator @27-77; FunctionDeclaration; parameters=6; async=true; generator=false
- (anonymous) @44-64; ArrowFunctionExpression; parameters=6; async=false; generator=false
- (anonymous) @67-74; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setUserVerified @79-89; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @82-87; ArrowFunctionExpression; parameters=2; async=false; generator=false
- handleEventMessage @91-101; FunctionDeclaration; parameters=1; async=false; generator=false
- log @103-109; FunctionDeclaration; parameters=1; async=false; generator=false
- local_is @111-117; FunctionDeclaration; parameters=3; async=false; generator=false
- local_isnot @119-125; FunctionDeclaration; parameters=3; async=false; generator=false
- local_ok @127-130; FunctionDeclaration; parameters=2; async=false; generator=false
- local_doesThrow @132-140; FunctionDeclaration; parameters=2; async=false; generator=false
- local_expectThisManyTests @142-150; FunctionDeclaration; parameters=1; async=false; generator=false
- local_completeTest @152-164; FunctionDeclaration; parameters=0; async=false; generator=false
- local_finished @166-168; FunctionDeclaration; parameters=0; async=false; generator=false
- string2buffer @170-172; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @171-171; ArrowFunctionExpression; parameters=2; async=false; generator=false
- buffer2string @174-183; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @179-181; FunctionExpression; parameters=1; async=false; generator=false
- bytesToBase64 @185-193; FunctionDeclaration; parameters=1; async=false; generator=false
- base64ToBytes @195-204; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @200-202; FunctionExpression; parameters=1; async=false; generator=false
- bytesToBase64UrlSafe @206-211; FunctionDeclaration; parameters=1; async=false; generator=false
- base64ToBytesUrlSafe @213-223; FunctionDeclaration; parameters=1; async=false; generator=false
- hexEncode @225-229; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @227-227; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hexDecode @231-233; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @232-232; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasOnlyKeys @235-238; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @237-237; ArrowFunctionExpression; parameters=1; async=false; generator=false
- webAuthnDecodeCBORAttestation @240-268; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @263-266; FunctionExpression; parameters=1; async=false; generator=false
- webAuthnDecodeAuthDataArray @270-347; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @337-346; FunctionExpression; parameters=1; async=false; generator=false
- importPublicKey @349-366; FunctionDeclaration; parameters=1; async=false; generator=false
- deriveAppAndChallengeParam @368-380; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @373-379; FunctionExpression; parameters=1; async=false; generator=false
- assemblePublicKeyBytesData @382-393; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @390-390; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @391-391; ArrowFunctionExpression; parameters=2; async=false; generator=false
- assembleSignedData @395-402; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @397-397; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @399-399; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @400-400; ArrowFunctionExpression; parameters=2; async=false; generator=false
- assembleRegistrationSignedData @404-419; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @412-412; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @413-413; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @414-414; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @416-416; ArrowFunctionExpression; parameters=2; async=false; generator=false
- sanitizeSigArray @421-431; FunctionDeclaration; parameters=1; async=false; generator=false
- verifySignature @433-464; FunctionDeclaration; parameters=3; async=false; generator=false
- addCredential @466-504; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @482-482; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @486-500; ArrowFunctionExpression; parameters=4; async=false; generator=false
- removeCredential @506-517; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @509-515; ArrowFunctionExpression; parameters=2; async=false; generator=false

### dom/webauthn/tests/webauthn-wellknown.sjs

Blob: `7f1f45b71c004df2f1d5d9de777918ddc8ef49e3`. Role: test-path,data-or-other. Parse: module.

- handleRequest @9-230; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/webauthn/tests/well-known-webauthn-state.sjs

Blob: `7bfaa5842a479cb8a8c2fcb14c36758ee13dacc1`. Role: test-path,data-or-other. Parse: module.

- handleRequest @8-15; FunctionDeclaration; parameters=2; async=false; generator=false

### dom/webgpu/tests/cts/checkout/.eslint-resolver.js

Blob: `32ca14b25ecc83eade4751ae3194ff8233341c55`. Role: test-path,source. Parse: module.

- exports.resolve @8-24; FunctionExpression; parameters=3; async=false; generator=false

### dom/webgpu/tests/cts/checkout/.eslintrc.cjs

Blob: `c2f7d3b8c633d0160f28ee06803063508d32cb8d`. Role: test-path,source. Parse: module.


### dom/webgpu/tests/cts/checkout/Gruntfile.js

Blob: `8dfcf191a792bbe0ff2e48058339467bd8e609f7`. Role: test-path,source. Parse: module.

- module.exports @19-328; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- registerTaskAndAddToHelp @232-235; FunctionDeclaration; parameters=3; async=false; generator=false
- addExistingTaskToHelp @236-238; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @240-249; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @321-327; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @323-323; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/babel.config.js

Blob: `ad977bc510ee91925d3d8040ba806e0c48126bab`. Role: test-path,source. Parse: module.

- module.exports @1-21; FunctionExpression; parameters=1; async=false; generator=false
- shouldPrintComment @19-19; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/prettier.config.js

Blob: `9f4053f719e77ba6d2cc2df8c84ad145006d4afb`. Role: test-path,source. Parse: module.


### dom/webgpu/tests/cts/checkout/src/common/tools/setup-ts-in-node.js

Blob: `89e91e8c9df3ef442732773505c535f7bb6612a1`. Role: test-path,source. Parse: module.

- Module._resolveFilename @16-47; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @49-51; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/src/external/petamoriken/float16/float16.js

Blob: `1031e2bcda2eb804d921dcaf6bf3e1756d8e1fe3`. Role: test-path,source. Parse: module.

- uncurryThis @26-30; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @27-29; ArrowFunctionExpression; parameters=2; async=false; generator=false
- uncurryThisGetter @31-38; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @74-90; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Uint16ArrayFrom @157-159; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @164-164; FunctionExpression; parameters=0; async=false; generator=true
- next @188-191; FunctionExpression; parameters=0; async=false; generator=false
- values @194-196; FunctionExpression; parameters=0; async=false; generator=false
- safeIfNeeded @199-209; FunctionDeclaration; parameters=1; async=false; generator=false
- next @213-216; FunctionExpression; parameters=0; async=false; generator=false
- wrap @227-231; FunctionDeclaration; parameters=1; async=false; generator=false
- isObject @233-238; FunctionDeclaration; parameters=1; async=false; generator=false
- isObjectLike @239-241; FunctionDeclaration; parameters=1; async=false; generator=false
- isNativeTypedArray @242-244; FunctionDeclaration; parameters=1; async=false; generator=false
- isNativeBigIntTypedArray @245-251; FunctionDeclaration; parameters=1; async=false; generator=false
- isArrayBuffer @252-262; FunctionDeclaration; parameters=1; async=false; generator=false
- isSharedArrayBuffer @263-273; FunctionDeclaration; parameters=1; async=false; generator=false
- isAnyArrayBuffer @274-276; FunctionDeclaration; parameters=1; async=false; generator=false
- isOrdinaryArray @277-285; FunctionDeclaration; parameters=1; async=false; generator=false
- isOrdinaryNativeTypedArray @286-294; FunctionDeclaration; parameters=1; async=false; generator=false
- isCanonicalIntegerIndexString @295-307; FunctionDeclaration; parameters=1; async=false; generator=false
- hasFloat16ArrayBrand @310-326; FunctionDeclaration; parameters=1; async=false; generator=false
- roundTiesToEven @329-331; FunctionDeclaration; parameters=1; async=false; generator=false
- roundToFloat16 @337-353; FunctionDeclaration; parameters=1; async=false; generator=false
- roundToFloat16Bits @388-393; FunctionDeclaration; parameters=1; async=false; generator=false
- convertToNumber @425-429; FunctionDeclaration; parameters=1; async=false; generator=false
- ToIntegerOrInfinity @431-437; FunctionDeclaration; parameters=1; async=false; generator=false
- ToLength @438-446; FunctionDeclaration; parameters=1; async=false; generator=false
- SpeciesConstructor @447-463; FunctionDeclaration; parameters=2; async=false; generator=false
- IsDetachedBuffer @464-473; FunctionDeclaration; parameters=1; async=false; generator=false
- defaultCompare @474-503; FunctionDeclaration; parameters=2; async=false; generator=false
- isFloat16Array @507-510; FunctionDeclaration; parameters=1; async=false; generator=false
- assertFloat16Array @511-515; FunctionDeclaration; parameters=1; async=false; generator=false
- assertSpeciesTypedArray @516-539; FunctionDeclaration; parameters=2; async=false; generator=false
- getFloat16BitsArray @540-559; FunctionDeclaration; parameters=1; async=false; generator=false
- copyToArray @560-567; FunctionDeclaration; parameters=1; async=false; generator=false
- get @579-587; FunctionExpression; parameters=3; async=false; generator=false
- set @588-593; FunctionExpression; parameters=4; async=false; generator=false
- getOwnPropertyDescriptor @594-601; FunctionExpression; parameters=2; async=false; generator=false
- defineProperty @602-612; FunctionExpression; parameters=3; async=false; generator=false
- constructor @615-664; FunctionExpression; parameters=3; async=false; generator=false
- from @665-742; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @695-699; FunctionExpression; parameters=2; async=false; generator=false
- of @743-764; FunctionExpression; parameters=1; async=false; generator=false
- keys @765-769; FunctionExpression; parameters=0; async=false; generator=false
- values @770-778; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @773-777; FunctionExpression; parameters=0; async=false; generator=true
- entries @779-787; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @782-786; FunctionExpression; parameters=0; async=false; generator=true
- at @788-798; FunctionExpression; parameters=1; async=false; generator=false
- with @799-822; FunctionExpression; parameters=2; async=false; generator=false
- map @823-847; FunctionExpression; parameters=2; async=false; generator=false
- filter @848-864; FunctionExpression; parameters=2; async=false; generator=false
- reduce @865-889; FunctionExpression; parameters=2; async=false; generator=false
- reduceRight @890-914; FunctionExpression; parameters=2; async=false; generator=false
- forEach @915-927; FunctionExpression; parameters=2; async=false; generator=false
- find @928-939; FunctionExpression; parameters=2; async=false; generator=false
- findIndex @940-952; FunctionExpression; parameters=2; async=false; generator=false
- findLast @953-964; FunctionExpression; parameters=2; async=false; generator=false
- findLastIndex @965-977; FunctionExpression; parameters=2; async=false; generator=false
- every @978-995; FunctionExpression; parameters=2; async=false; generator=false
- some @996-1013; FunctionExpression; parameters=2; async=false; generator=false
- set @1014-1053; FunctionExpression; parameters=2; async=false; generator=false
- reverse @1054-1059; FunctionExpression; parameters=0; async=false; generator=false
- toReversed @1060-1076; FunctionExpression; parameters=0; async=false; generator=false
- fill @1077-1086; FunctionExpression; parameters=2; async=false; generator=false
- copyWithin @1087-1092; FunctionExpression; parameters=3; async=false; generator=false
- sort @1093-1101; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1097-1099; ArrowFunctionExpression; parameters=2; async=false; generator=false
- toSorted @1102-1124; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1120-1122; ArrowFunctionExpression; parameters=2; async=false; generator=false
- slice @1125-1177; FunctionExpression; parameters=2; async=false; generator=false
- subarray @1178-1195; FunctionExpression; parameters=2; async=false; generator=false
- indexOf @1196-1219; FunctionExpression; parameters=2; async=false; generator=false
- lastIndexOf @1220-1242; FunctionExpression; parameters=2; async=false; generator=false
- includes @1243-1268; FunctionExpression; parameters=2; async=false; generator=false
- join @1269-1274; FunctionExpression; parameters=1; async=false; generator=false
- toLocaleString @1275-1280; FunctionExpression; parameters=1; async=false; generator=false
- SymbolToStringTag @1281-1285; FunctionExpression; parameters=0; async=false; generator=false
- isTypedArray @1303-1305; FunctionDeclaration; parameters=1; async=false; generator=false
- getFloat16 @1307-1311; FunctionDeclaration; parameters=3; async=false; generator=false
- setFloat16 @1312-1319; FunctionDeclaration; parameters=4; async=false; generator=false
- f16round @1321-1323; FunctionDeclaration; parameters=1; async=false; generator=false
- Class Float16Array @614-1286

### dom/webgpu/tests/cts/checkout/standalone/third_party/jquery/jquery-3.3.1.min.js

Blob: `4d9b3a258759c53e7bc66b6fc554c51e2434437c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.noConflict @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.isNumeric @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.holdReady @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.proxy @2-2; FunctionExpression; parameters=2; async=false; generator=false
- i @2-2; FunctionExpression; parameters=0; async=false; generator=false
- undelegate @2-2; FunctionExpression; parameters=3; async=false; generator=false
- delegate @2-2; FunctionExpression; parameters=4; async=false; generator=false
- unbind @2-2; FunctionExpression; parameters=2; async=false; generator=false
- bind @2-2; FunctionExpression; parameters=3; async=false; generator=false
- hover @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.t @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.r @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.e @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- offsetParent @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- position @2-2; FunctionExpression; parameters=0; async=false; generator=false
- offset @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- setOffset @2-2; FunctionExpression; parameters=3; async=false; generator=false
- w.expr.pseudos.animated @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.t @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.fn.load @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.parseHTML @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- e.i @2-2; FunctionExpression; parameters=0; async=false; generator=false
- t.converters.script json @2-2; FunctionExpression; parameters=0; async=false; generator=false
- jsonpCallback @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- abort @2-2; FunctionExpression; parameters=0; async=false; generator=false
- send @2-2; FunctionExpression; parameters=2; async=false; generator=false
- n @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- text script @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- abort @2-2; FunctionExpression; parameters=0; async=false; generator=false
- send @2-2; FunctionExpression; parameters=2; async=false; generator=false
- s.onreadystatechange @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- n @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.ajaxSettings.xhr @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.expr.pseudos.visible @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.expr.pseudos.hidden @2-2; FunctionExpression; parameters=1; async=false; generator=false
- unwrap @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- wrap @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- wrapInner @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- wrapAll @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w._evalUrl @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.t @2-2; FunctionExpression; parameters=4; async=false; generator=false
- getScript @2-2; FunctionExpression; parameters=2; async=false; generator=false
- getJSON @2-2; FunctionExpression; parameters=3; async=false; generator=false
- ajax @2-2; FunctionExpression; parameters=2; async=false; generator=false
- k @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- abort @2-2; FunctionExpression; parameters=1; async=false; generator=false
- statusCode @2-2; FunctionExpression; parameters=1; async=false; generator=false
- overrideMimeType @2-2; FunctionExpression; parameters=1; async=false; generator=false
- setRequestHeader @2-2; FunctionExpression; parameters=2; async=false; generator=false
- getAllResponseHeaders @2-2; FunctionExpression; parameters=0; async=false; generator=false
- getResponseHeader @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ajaxSetup @2-2; FunctionExpression; parameters=2; async=false; generator=false
- Ut @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- Xt @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- zt @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- _t @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- a @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- Ft @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- serializeArray @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- serialize @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.param @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- i @2-2; FunctionExpression; parameters=2; async=false; generator=false
- jt @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.parseXML @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- teardown @2-2; FunctionExpression; parameters=0; async=false; generator=false
- setup @2-2; FunctionExpression; parameters=0; async=false; generator=false
- n @2-2; FunctionExpression; parameters=1; async=false; generator=false
- triggerHandler @2-2; FunctionExpression; parameters=2; async=false; generator=false
- trigger @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- simulate @2-2; FunctionExpression; parameters=3; async=false; generator=false
- trigger @2-2; FunctionExpression; parameters=4; async=false; generator=false
- Tt @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.valHooks.[computed].get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- set @2-2; FunctionExpression; parameters=2; async=false; generator=false
- set @2-2; FunctionExpression; parameters=2; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- val @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- hasClass @2-2; FunctionExpression; parameters=1; async=false; generator=false
- toggleClass @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- removeClass @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- addClass @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- xt @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- mt @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- vt @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- set @2-2; FunctionExpression; parameters=1; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- prop @2-2; FunctionExpression; parameters=3; async=false; generator=false
- removeProp @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- prop @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- ht.t @2-2; FunctionExpression; parameters=3; async=false; generator=false
- set @2-2; FunctionExpression; parameters=3; async=false; generator=false
- removeAttr @2-2; FunctionExpression; parameters=2; async=false; generator=false
- set @2-2; FunctionExpression; parameters=2; async=false; generator=false
- attr @2-2; FunctionExpression; parameters=3; async=false; generator=false
- removeAttr @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- attr @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.fn.delay @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- r.stop @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.fx.stop @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.fx.start @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.fx.timer @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.fx.tick @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.e @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.t @2-2; FunctionExpression; parameters=3; async=false; generator=false
- finish @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- stop @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- r @2-2; FunctionExpression; parameters=1; async=false; generator=false
- animate @2-2; FunctionExpression; parameters=4; async=false; generator=false
- a @2-2; FunctionExpression; parameters=0; async=false; generator=false
- fadeTo @2-2; FunctionExpression; parameters=4; async=false; generator=false
- w.speed @2-2; FunctionExpression; parameters=3; async=false; generator=false
- r.complete @2-2; FunctionExpression; parameters=0; async=false; generator=false
- prefilter @2-2; FunctionExpression; parameters=2; async=false; generator=false
- tweener @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- pt @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- stop @2-2; FunctionExpression; parameters=1; async=false; generator=false
- createTween @2-2; FunctionExpression; parameters=2; async=false; generator=false
- u @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- ft @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- ct @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- a.empty.fire @2-2; FunctionExpression; parameters=0; async=false; generator=false
- lt @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- ut @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- st @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- at @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- swing @2-2; FunctionExpression; parameters=1; async=false; generator=false
- linear @2-2; FunctionExpression; parameters=1; async=false; generator=false
- set @2-2; FunctionExpression; parameters=1; async=false; generator=false
- set @2-2; FunctionExpression; parameters=1; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- run @2-2; FunctionExpression; parameters=1; async=false; generator=false
- cur @2-2; FunctionExpression; parameters=0; async=false; generator=false
- init @2-2; FunctionExpression; parameters=6; async=false; generator=false
- tt @2-2; FunctionDeclaration; parameters=5; async=false; generator=false
- css @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- expand @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- set @2-2; FunctionExpression; parameters=3; async=false; generator=false
- get @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- css @2-2; FunctionExpression; parameters=4; async=false; generator=false
- style @2-2; FunctionExpression; parameters=4; async=false; generator=false
- get @2-2; FunctionExpression; parameters=2; async=false; generator=false
- et @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- Ze @2-2; FunctionDeclaration; parameters=6; async=false; generator=false
- Ke @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- Je @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- Qe @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- _e @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- get @2-2; FunctionExpression; parameters=0; async=false; generator=false
- Fe @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- scrollboxSize @2-2; FunctionExpression; parameters=0; async=false; generator=false
- reliableMarginLeft @2-2; FunctionExpression; parameters=0; async=false; generator=false
- pixelPosition @2-2; FunctionExpression; parameters=0; async=false; generator=false
- pixelBoxStyles @2-2; FunctionExpression; parameters=0; async=false; generator=false
- boxSizingReliable @2-2; FunctionExpression; parameters=0; async=false; generator=false
- n @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- t @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- $e @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.e @2-2; FunctionExpression; parameters=1; async=false; generator=false
- replaceWith @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- html @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- clone @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- empty @2-2; FunctionExpression; parameters=0; async=false; generator=false
- after @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- before @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- prepend @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- append @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- text @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- remove @2-2; FunctionExpression; parameters=1; async=false; generator=false
- detach @2-2; FunctionExpression; parameters=1; async=false; generator=false
- cleanData @2-2; FunctionExpression; parameters=1; async=false; generator=false
- clone @2-2; FunctionExpression; parameters=3; async=false; generator=false
- htmlPrefilter @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Ie @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- Re @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Me @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- Pe @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- Oe @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- He @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- Le @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- off @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- one @2-2; FunctionExpression; parameters=4; async=false; generator=false
- on @2-2; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- handle @2-2; FunctionExpression; parameters=1; async=false; generator=false
- which @2-2; FunctionExpression; parameters=1; async=false; generator=false
- stopImmediatePropagation @2-2; FunctionExpression; parameters=0; async=false; generator=false
- stopPropagation @2-2; FunctionExpression; parameters=0; async=false; generator=false
- preventDefault @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.Event @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.removeEvent @2-2; FunctionExpression; parameters=3; async=false; generator=false
- postDispatch @2-2; FunctionExpression; parameters=1; async=false; generator=false
- _default @2-2; FunctionExpression; parameters=1; async=false; generator=false
- trigger @2-2; FunctionExpression; parameters=0; async=false; generator=false
- trigger @2-2; FunctionExpression; parameters=0; async=false; generator=false
- trigger @2-2; FunctionExpression; parameters=0; async=false; generator=false
- fix @2-2; FunctionExpression; parameters=1; async=false; generator=false
- addProp @2-2; FunctionExpression; parameters=2; async=false; generator=false
- set @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- handlers @2-2; FunctionExpression; parameters=2; async=false; generator=false
- dispatch @2-2; FunctionExpression; parameters=1; async=false; generator=false
- remove @2-2; FunctionExpression; parameters=5; async=false; generator=false
- add @2-2; FunctionExpression; parameters=5; async=false; generator=false
- y.handle @2-2; FunctionExpression; parameters=1; async=false; generator=false
- De @2-2; FunctionDeclaration; parameters=6; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- i @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Se @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- ke @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- Ee @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- xe @2-2; FunctionDeclaration; parameters=5; async=false; generator=false
- ve @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- ye @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- toggle @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- hide @2-2; FunctionExpression; parameters=0; async=false; generator=false
- show @2-2; FunctionExpression; parameters=0; async=false; generator=false
- fe @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- ce @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- ue @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- se @2-2; FunctionExpression; parameters=4; async=false; generator=false
- ae @2-2; FunctionExpression; parameters=2; async=false; generator=false
- promise @2-2; FunctionExpression; parameters=2; async=false; generator=false
- s @2-2; FunctionExpression; parameters=0; async=false; generator=false
- clearQueue @2-2; FunctionExpression; parameters=1; async=false; generator=false
- dequeue @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- queue @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- _queueHooks @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- dequeue @2-2; FunctionExpression; parameters=2; async=false; generator=false
- a @2-2; FunctionExpression; parameters=0; async=false; generator=false
- queue @2-2; FunctionExpression; parameters=3; async=false; generator=false
- removeData @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- data @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- _removeData @2-2; FunctionExpression; parameters=2; async=false; generator=false
- _data @2-2; FunctionExpression; parameters=3; async=false; generator=false
- removeData @2-2; FunctionExpression; parameters=2; async=false; generator=false
- data @2-2; FunctionExpression; parameters=3; async=false; generator=false
- hasData @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ne @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- te @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- hasData @2-2; FunctionExpression; parameters=1; async=false; generator=false
- remove @2-2; FunctionExpression; parameters=2; async=false; generator=false
- access @2-2; FunctionExpression; parameters=3; async=false; generator=false
- get @2-2; FunctionExpression; parameters=2; async=false; generator=false
- set @2-2; FunctionExpression; parameters=3; async=false; generator=false
- cache @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Q @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- Y @2-2; FunctionExpression; parameters=1; async=false; generator=false
- G @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- V @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- z @2-2; FunctionExpression; parameters=7; async=false; generator=false
- t @2-2; FunctionExpression; parameters=3; async=false; generator=false
- _ @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- ready @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.fn.ready @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.readyException @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.Deferred.exceptionHook @2-2; FunctionExpression; parameters=2; async=false; generator=false
- when @2-2; FunctionExpression; parameters=1; async=false; generator=false
- s @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Deferred @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- o.[computed] @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- promise @2-2; FunctionExpression; parameters=1; async=false; generator=false
- then @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- a @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- l @2-2; FunctionExpression; parameters=0; async=false; generator=false
- pipe @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- catch @2-2; FunctionExpression; parameters=1; async=false; generator=false
- always @2-2; FunctionExpression; parameters=0; async=false; generator=false
- state @2-2; FunctionExpression; parameters=0; async=false; generator=false
- $ @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- W @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- I @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- w.Callbacks @2-2; FunctionExpression; parameters=1; async=false; generator=false
- fired @2-2; FunctionExpression; parameters=0; async=false; generator=false
- fire @2-2; FunctionExpression; parameters=0; async=false; generator=false
- fireWith @2-2; FunctionExpression; parameters=2; async=false; generator=false
- locked @2-2; FunctionExpression; parameters=0; async=false; generator=false
- lock @2-2; FunctionExpression; parameters=0; async=false; generator=false
- disabled @2-2; FunctionExpression; parameters=0; async=false; generator=false
- disable @2-2; FunctionExpression; parameters=0; async=false; generator=false
- empty @2-2; FunctionExpression; parameters=0; async=false; generator=false
- has @2-2; FunctionExpression; parameters=1; async=false; generator=false
- remove @2-2; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- add @2-2; FunctionExpression; parameters=0; async=false; generator=false
- t @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- u @2-2; FunctionExpression; parameters=0; async=false; generator=false
- R @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- w.fn.e @2-2; FunctionExpression; parameters=2; async=false; generator=false
- contents @2-2; FunctionExpression; parameters=1; async=false; generator=false
- children @2-2; FunctionExpression; parameters=1; async=false; generator=false
- siblings @2-2; FunctionExpression; parameters=1; async=false; generator=false
- prevUntil @2-2; FunctionExpression; parameters=3; async=false; generator=false
- nextUntil @2-2; FunctionExpression; parameters=3; async=false; generator=false
- prevAll @2-2; FunctionExpression; parameters=1; async=false; generator=false
- nextAll @2-2; FunctionExpression; parameters=1; async=false; generator=false
- prev @2-2; FunctionExpression; parameters=1; async=false; generator=false
- next @2-2; FunctionExpression; parameters=1; async=false; generator=false
- parentsUntil @2-2; FunctionExpression; parameters=3; async=false; generator=false
- parents @2-2; FunctionExpression; parameters=1; async=false; generator=false
- parent @2-2; FunctionExpression; parameters=1; async=false; generator=false
- P @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- addBack @2-2; FunctionExpression; parameters=1; async=false; generator=false
- add @2-2; FunctionExpression; parameters=2; async=false; generator=false
- index @2-2; FunctionExpression; parameters=1; async=false; generator=false
- closest @2-2; FunctionExpression; parameters=2; async=false; generator=false
- has @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.fn.init @2-2; FunctionExpression; parameters=3; async=false; generator=false
- is @2-2; FunctionExpression; parameters=1; async=false; generator=false
- not @2-2; FunctionExpression; parameters=1; async=false; generator=false
- filter @2-2; FunctionExpression; parameters=1; async=false; generator=false
- find @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w.filter @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- j @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- N @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- S @2-2; FunctionExpression; parameters=2; async=false; generator=false
- k @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.select @2-2; FunctionExpression; parameters=4; async=false; generator=false
- oe.compile @2-2; FunctionExpression; parameters=2; async=false; generator=false
- Ee @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- o @2-2; FunctionExpression; parameters=5; async=false; generator=false
- Ce @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- Te @2-2; FunctionDeclaration; parameters=6; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=4; async=false; generator=false
- we @2-2; FunctionDeclaration; parameters=5; async=false; generator=false
- be @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- xe @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- me @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- ve @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- oe.tokenize @2-2; FunctionExpression; parameters=2; async=false; generator=false
- ye @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- text @2-2; FunctionExpression; parameters=1; async=false; generator=false
- button @2-2; FunctionExpression; parameters=1; async=false; generator=false
- input @2-2; FunctionExpression; parameters=1; async=false; generator=false
- header @2-2; FunctionExpression; parameters=1; async=false; generator=false
- parent @2-2; FunctionExpression; parameters=1; async=false; generator=false
- empty @2-2; FunctionExpression; parameters=1; async=false; generator=false
- selected @2-2; FunctionExpression; parameters=1; async=false; generator=false
- checked @2-2; FunctionExpression; parameters=1; async=false; generator=false
- focus @2-2; FunctionExpression; parameters=1; async=false; generator=false
- root @2-2; FunctionExpression; parameters=1; async=false; generator=false
- target @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=4; async=false; generator=false
- PSEUDO @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- CHILD @2-2; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ATTR @2-2; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- CLASS @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- TAG @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=0; async=false; generator=false
- PSEUDO @2-2; FunctionExpression; parameters=1; async=false; generator=false
- CHILD @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ATTR @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.getText @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.uniqueSort @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.error @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.escape @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.attr @2-2; FunctionExpression; parameters=2; async=false; generator=false
- oe.contains @2-2; FunctionExpression; parameters=2; async=false; generator=false
- oe.matchesSelector @2-2; FunctionExpression; parameters=2; async=false; generator=false
- oe.matches @2-2; FunctionExpression; parameters=2; async=false; generator=false
- oe.setDocument @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- r.find.ID @2-2; FunctionExpression; parameters=2; async=false; generator=false
- r.filter.ID @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- r.find.ID @2-2; FunctionExpression; parameters=2; async=false; generator=false
- r.filter.ID @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- oe.isXML @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ge @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- he @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- de @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- pe @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- fe @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- ce @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- le @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- ue @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- se @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- ae @2-2; FunctionDeclaration; parameters=0; async=false; generator=false
- t @2-2; FunctionDeclaration; parameters=2; async=false; generator=false
- oe @2-2; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false
- re @2-2; FunctionExpression; parameters=0; async=false; generator=false
- ne @2-2; FunctionExpression; parameters=2; async=false; generator=false
- ee @2-2; FunctionExpression; parameters=3; async=false; generator=false
- O @2-2; FunctionExpression; parameters=2; async=false; generator=false
- D @2-2; FunctionExpression; parameters=2; async=false; generator=false
- C @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- map @2-2; FunctionExpression; parameters=3; async=false; generator=false
- grep @2-2; FunctionExpression; parameters=3; async=false; generator=false
- merge @2-2; FunctionExpression; parameters=2; async=false; generator=false
- inArray @2-2; FunctionExpression; parameters=3; async=false; generator=false
- makeArray @2-2; FunctionExpression; parameters=2; async=false; generator=false
- trim @2-2; FunctionExpression; parameters=1; async=false; generator=false
- each @2-2; FunctionExpression; parameters=2; async=false; generator=false
- globalEval @2-2; FunctionExpression; parameters=1; async=false; generator=false
- isEmptyObject @2-2; FunctionExpression; parameters=1; async=false; generator=false
- isPlainObject @2-2; FunctionExpression; parameters=1; async=false; generator=false
- noop @2-2; FunctionExpression; parameters=0; async=false; generator=false
- error @2-2; FunctionExpression; parameters=1; async=false; generator=false
- w.fn.extend @2-2; FunctionExpression; parameters=0; async=false; generator=false
- end @2-2; FunctionExpression; parameters=0; async=false; generator=false
- eq @2-2; FunctionExpression; parameters=1; async=false; generator=false
- last @2-2; FunctionExpression; parameters=0; async=false; generator=false
- first @2-2; FunctionExpression; parameters=0; async=false; generator=false
- slice @2-2; FunctionExpression; parameters=0; async=false; generator=false
- map @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- each @2-2; FunctionExpression; parameters=1; async=false; generator=false
- pushStack @2-2; FunctionExpression; parameters=1; async=false; generator=false
- get @2-2; FunctionExpression; parameters=1; async=false; generator=false
- toArray @2-2; FunctionExpression; parameters=0; async=false; generator=false
- w @2-2; FunctionExpression; parameters=2; async=false; generator=false
- x @2-2; FunctionDeclaration; parameters=1; async=false; generator=false
- m @2-2; FunctionDeclaration; parameters=3; async=false; generator=false
- e @2-2; FunctionExpression; parameters=1; async=false; generator=false
- e @2-2; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2-2; FunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/tools/eslint-plugin-gpuweb-cts/index.js

Blob: `1f5bb211aab5b29c1f531834507e070735005ae5`. Role: test-path,source. Parse: module.


### dom/webgpu/tests/cts/checkout/tools/eslint-plugin-gpuweb-cts/tabs-anywhere.js

Blob: `e4bc4f0ecdcb9c90c45f2ae87a524572bf58d329`. Role: test-path,source. Parse: module.

- create @10-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Program @14-27; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/tools/eslint-plugin-gpuweb-cts/trailing-space-anywhere.js

Blob: `070ae5c193e59e9dfa877ded436178054348dfcc`. Role: test-path,source. Parse: module.

- create @10-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Program @14-27; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webgpu/tests/cts/checkout/tools/websocket-logger/main.js

Blob: `eb14e73fac77c7794c9d4ff5912d6f247b1a5e63`. Role: test-path,source. Parse: module.

- (anonymous) @12-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-23; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @18-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module fs/promises @1; ImportDeclaration
- Module ws @2; ImportDeclaration

### dom/webgpu/tests/mochitest/test_basic_canvas.worker.js

Blob: `cec6d6f21075b9e820f3ff304cf63df7182a5b62`. Role: test-path,source. Parse: module.

- (anonymous) @1-32; FunctionExpression; parameters=1; async=true; generator=false

### dom/webgpu/tests/mochitest/test_submit_render_empty.worker.js

Blob: `334230c3c1296bc065b7ad880fa4bcb7eac5d32d`. Role: test-path,source. Parse: module.

- (anonymous) @1-49; FunctionExpression; parameters=1; async=true; generator=false

### dom/webgpu/tests/mochitest/worker_wrapper.js

Blob: `83048c58d202f6a9b7120a6bdfbf8624b0b1a6d9`. Role: test-path,source. Parse: module.

- workerWrapperFunc @7-20; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @10-14; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @11-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- runWorkerTest @22-29; FunctionDeclaration; parameters=3; async=true; generator=false

### dom/webserial/tests/browser/browser_webserial_bfcache.js

Blob: `be0e138a551b507bb652d20d4c08edb236d2374e`. Role: test-path,source. Parse: module.

- (anonymous) @10-20; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_serial_disallows_bfcache @22-56; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-37; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-49; ArrowFunctionExpression; parameters=0; async=true; generator=false

### dom/webserial/tests/browser/browser_webserial_blocked_icon.js

Blob: `2f905b60826265afff9ada7cbe82e78edcb8b350`. Role: test-path,source. Parse: module.

- (anonymous) @12-25; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-24; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testBlockedIconAppearsWhenDenied @27-74; FunctionExpression; parameters=0; async=true; generator=false

### dom/webserial/tests/browser/browser_webserial_chooser.js

Blob: `29faa5a33ecc287a9d87ff3b8bdb6917ae7e5f60`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testChooserCancel @21-67; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-35; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @52-62; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testChooserNoPorts @69-127; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @79-84; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @108-118; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @124-126; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testChooserSelection @129-192; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @142-144; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @152-156; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @167-175; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @182-185; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testChooserDismissedOnNavigation @194-280; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @207-213; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @212-212; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @231-235; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @247-251; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @268-276; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testChooserSelectSecondDevice @282-368; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @294-298; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @349-362; ArrowFunctionExpression; parameters=0; async=true; generator=false

### dom/webserial/tests/browser/browser_webserial_permission_gated.js

Blob: `bb24dc561f62883c1c30ba651705cc73e0136050`. Role: test-path,source. Parse: module.

- (anonymous) @38-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-61; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testRequestPort @64-346; FunctionExpression; parameters=0; async=true; generator=false
- trackSitePermission @72-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @88-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @116-126; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @140-143; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @168-178; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @196-200; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @222-230; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @247-250; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @249-249; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @272-275; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @285-295; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @304-313; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testIframeRequestPort @348-489; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @365-367; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @373-377; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @391-399; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @419-423; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @422-422; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @440-442; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @445-455; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observe @447-452; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @460-469; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testRequestPortLocalhost @491-643; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @494-500; FunctionExpression; parameters=2; async=false; generator=false
- cleanup @503-505; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @504-504; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @525-529; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @546-554; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @566-569; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @586-594; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @604-607; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @624-634; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testRequestPortFile @645-785; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @667-671; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @688-696; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @708-711; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @728-736; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @746-749; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @766-776; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/httpd.sys.mjs @25; ChromeUtils-import-literal

### dom/webserial/tests/browser/browser_webserial_permission_revoke.js

Blob: `28d9f7c8ac2ab01ac75e056aeb89fc166210bdab`. Role: test-path,source. Parse: module.

- (anonymous) @7-17; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testPermissionRevocation @19-104; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-30; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-76; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-75; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @80-93; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @96-99; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webserial/tests/browser/browser_webserial_sharing_icon.js

Blob: `2e21900602002250a7013d56bbbf5053adafad00`. Role: test-path,source. Parse: module.

- isIconVisible @10-14; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForIconVisible @16-18; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForIconHidden @20-22; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- requestAndOpenPort @26-35; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @27-34; ArrowFunctionExpression; parameters=1; async=true; generator=false
- openPortFromWorker @40-56; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @41-55; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @44-54; ArrowFunctionExpression; parameters=2; async=false; generator=false
- worker.onmessage @45-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- worker.onerror @52-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-68; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @63-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testSharingIconAppearsFromWorker @70-126; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @76-80; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @93-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @100-111; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @101-110; ArrowFunctionExpression; parameters=2; async=false; generator=false
- content.testWorker.onmessage @102-108; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @114-118; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @121-123; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testSharingIconWithMultiplePorts @128-211; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @136-148; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @157-159; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @164-168; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @171-173; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @184-186; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @197-199; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @204-208; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testSharingIconReopen @213-236; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @220-222; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @225-227; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @230-232; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testSharingIconHiddenOnDeviceDisconnect @238-270; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @244-257; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @260-266; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @261-263; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testSharingIconHiddenOnNavigation @272-284; FunctionExpression; parameters=0; async=true; generator=false
- testSharingIconHiddenOnWorkerTerminate @286-309; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @290-294; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @301-303; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testSharingIconHiddenOnIframeRemoval @311-345; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @319-327; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @322-324; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @339-341; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testSharingStateIsPerTab @347-392; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @363-365; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @367-367; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @385-387; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testSharingHelperCountClampsAtZero @394-425; FunctionExpression; parameters=0; async=true; generator=false
- notify @402-409; FunctionDeclaration; parameters=1; async=false; generator=false

### dom/webserial/tests/browser/worker_open_close.js

Blob: `b0812969b2ec2647554b558d09020d153c367323`. Role: test-path,source. Parse: module.

- self.onmessage @5-32; FunctionExpression; parameters=1; async=true; generator=false

### dom/webserial/tests/mochitest/serial_test_utils.js

Blob: `df50848ce9436e9b97b7c827756fc9349b40bf89`. Role: test-path,source. Parse: module.

- throws @11-22; FunctionExpression; parameters=3; async=false; generator=false
- rejects @24-29; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _assertExpected @32-40; FunctionDeclaration; parameters=3; async=false; generator=false
- cleanupSerialPorts @45-84; FunctionDeclaration; parameters=0; async=true; generator=false
- simulateDeviceConnection @86-100; FunctionDeclaration; parameters=5; async=true; generator=false
- simulateDeviceDisconnection @102-104; FunctionDeclaration; parameters=1; async=true; generator=false

### dom/webserial/tests/mochitest/serial_worker.js

Blob: `a339292b02d97a5f8613bb5052ae167f702c198c`. Role: test-path,source. Parse: module.

- test @6-12; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @14-68; FunctionDeclaration; parameters=0; async=true; generator=false
- navigator.serial.onconnect @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- navigator.serial.ondisconnect @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testListener @43-45; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_access.js

Blob: `ff23ae67b03e77c191c0bfb263b0c6a6e97ac1da`. Role: test-path,source. Parse: module.

- test @6-12; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @14-101; FunctionDeclaration; parameters=0; async=true; generator=false

### dom/webserial/tests/mochitest/serial_worker_disconnect.js

Blob: `6e15b8b2f3554ef5409f13436db68e744fb24333`. Role: test-path,source. Parse: module.

- test @5-7; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @9-44; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- port.ondisconnect @24-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_forget.js

Blob: `583b0a78c6a90af549d59ce1808cb153050f8b8e`. Role: test-path,source. Parse: module.

- test @6-12; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @14-42; FunctionDeclaration; parameters=0; async=true; generator=false

### dom/webserial/tests/mochitest/serial_worker_forget_and_signal.js

Blob: `07fc06828d2b156bd17f262ec1efdf2a4af7bb95`. Role: test-path,source. Parse: module.

- test @6-12; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @14-49; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @16-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.onmessage @17-21; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_hotplug.js

Blob: `95d8a872f96190b17cfba6c171e82e2bc6c646ff`. Role: test-path,source. Parse: module.

- test @5-7; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @9-53; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @21-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- port.ondisconnect @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_main_forget.js

Blob: `b3cc8b90a2bbcd096c60721e6653f89d5faf1c26`. Role: test-path,source. Parse: module.

- test @6-12; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @14-51; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @23-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.onmessage @24-28; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_open.js

Blob: `09a710312b1602d86890ea5162649a426cd6c428`. Role: test-path,source. Parse: module.

- test @5-7; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @9-62; FunctionDeclaration; parameters=0; async=true; generator=false

### dom/webserial/tests/mochitest/serial_worker_reconnect.js

Blob: `2f07a2f837674893691488338c855ff391fea8b5`. Role: test-path,source. Parse: module.

- test @5-7; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @9-55; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @24-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- port.ondisconnect @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- port.onconnect @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false

### dom/webserial/tests/mochitest/serial_worker_stream_transfer.js

Blob: `e82070ddcc630ab2362def5061d6674832b7ab61`. Role: test-path,source. Parse: module.

- test @5-11; FunctionDeclaration; parameters=2; async=false; generator=false
- self.onmessage @13-41; FunctionExpression; parameters=1; async=true; generator=false
- testReadableTransfer @43-68; FunctionDeclaration; parameters=1; async=true; generator=false
- testWritableTransfer @70-85; FunctionDeclaration; parameters=1; async=true; generator=false
- testBothTransfer @87-122; FunctionDeclaration; parameters=1; async=true; generator=false

### dom/webserial/tests/mochitest/serial_worker_wait_and_getports.js

Blob: `90235e8883d294dce93fc66ad8246fc30a444505`. Role: test-path,source. Parse: module.

- test @5-11; FunctionDeclaration; parameters=2; async=false; generator=false
- runTests @13-47; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @19-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.onmessage @20-24; ArrowFunctionExpression; parameters=1; async=false; generator=false

### dom/websocket/tests/websocket1.worker.js

Blob: `85743bf82de613c5bb3aa70f6e75b76bc32b3535`. Role: test-path,source. Parse: module.


### dom/websocket/tests/websocket2.worker.js

Blob: `5ce7c53597fcc07b300d47efaf376034356af5b7`. Role: test-path,source. Parse: module.


### dom/websocket/tests/websocket3.worker.js

Blob: `930a74495851003270dab3fef64f157385a4650c`. Role: test-path,source. Parse: module.


### dom/websocket/tests/websocket4.worker.js

Blob: `6b8cda07b8ead7e09ee199699570beb775940540`. Role: test-path,source. Parse: module.


### dom/websocket/tests/websocket5.worker.js

Blob: `56229b26608f8963c5712f3e0b87050cd95327cc`. Role: test-path,source. Parse: module.


### dom/websocket/tests/websocket_basic_worker.js

Blob: `7ee783b537a689439629a0204abf6f4bd8a23bed`. Role: test-path,source. Parse: module.

- onmessage @1-48; FunctionExpression; parameters=1; async=false; generator=false
- worker.onmessage @4-6; FunctionExpression; parameters=1; async=false; generator=false
- ws.onopen @28-31; FunctionExpression; parameters=0; async=false; generator=false
- ws.onclose @33-33; FunctionExpression; parameters=0; async=false; generator=false
- ws.onerror @35-37; FunctionExpression; parameters=0; async=false; generator=false
- ws.onmessage @39-47; FunctionExpression; parameters=1; async=false; generator=false

### dom/websocket/tests/websocket_helpers.js

Blob: `65b95506ff8a07122ab3a79dbf080d57cc547952`. Role: test-path,source. Parse: module.

- shouldNotOpen @6-9; FunctionDeclaration; parameters=1; async=false; generator=false
- shouldCloseCleanly @11-17; FunctionDeclaration; parameters=1; async=false; generator=false
- shouldCloseNotCleanly @19-27; FunctionDeclaration; parameters=1; async=false; generator=false
- ignoreError @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- CreateTestWS @31-48; FunctionDeclaration; parameters=2; async=false; generator=false
- ws.onerror @43-45; FunctionExpression; parameters=1; async=false; generator=false
- forcegc @50-53; FunctionDeclaration; parameters=0; async=false; generator=false
- feedback @55-58; FunctionDeclaration; parameters=0; async=false; generator=false
- finish @60-62; FunctionDeclaration; parameters=0; async=false; generator=false
- doTest @64-72; FunctionDeclaration; parameters=0; async=false; generator=false

### dom/websocket/tests/websocket_https_worker.js

Blob: `1b0bfc7ee135896ff9488cd65840e0ebff59a3cc`. Role: test-path,source. Parse: module.

- onmessage @1-15; FunctionExpression; parameters=0; async=false; generator=false
- ws.onerror @6-8; FunctionExpression; parameters=0; async=false; generator=false
- ws.onopen @9-11; FunctionExpression; parameters=0; async=false; generator=false

### dom/websocket/tests/websocket_loadgroup_worker.js

Blob: `8681288c409cc5a5120832c2d12aae2f30c935cc`. Role: test-path,source. Parse: module.

- onmessage @1-26; FunctionExpression; parameters=1; async=false; generator=false
- worker.onmessage @4-6; FunctionExpression; parameters=1; async=false; generator=false
- ws.onopen @15-17; FunctionExpression; parameters=0; async=false; generator=false
- ws.onclose @19-21; FunctionExpression; parameters=0; async=false; generator=false
- ws.onerror @23-25; FunctionExpression; parameters=0; async=false; generator=false

### dom/websocket/tests/websocket_sharedWorker.js

Blob: `541f757e49ad6d58e0102cd79f874529b4487cbc`. Role: test-path,source. Parse: module.

- onconnect @2-35; FunctionExpression; parameters=1; async=false; generator=false
- ws.onopen @7-14; FunctionExpression; parameters=0; async=false; generator=false
- ws.onclose @16-16; FunctionExpression; parameters=0; async=false; generator=false
- ws.onerror @18-24; FunctionExpression; parameters=0; async=false; generator=false
- ws.onmessage @26-34; FunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [d2866cf1-a2cf-4ed2-9df6-4b4601e1980a.md](d2866cf1-a2cf-4ed2-9df6-4b4601e1980a.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `98939e1ada8d8101e26c95caf21659cd37a8f33a646c83a4dbc14b6469c25e8a`.
