<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["devtools"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["9a35b5aeae6a69046113168fae29a18badfeed2284cc85a3dc7f13a4e16fabf6"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/52efd019-3d6d-43a4-9d7f-335d9470a6eb.md"}} -->
# firefox/devtools JavaScript function map 119

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### devtools/client/jsonview/components/JsonBreadcrumb.mjs

Blob: `cb8444e5630c4b0a79e2f3006c3a79f7aaa63e04`. Role: source. Parse: module.

- propTypes @21-30; FunctionExpression; parameters=0; async=false; generator=false
- defaultProps @32-34; FunctionExpression; parameters=0; async=false; generator=false
- renderBreadCrumb @36-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-49; ArrowFunctionExpression; parameters=2; async=false; generator=false
- render @52-61; FunctionExpression; parameters=0; async=false; generator=false
- Class JsonBreadcrumb @20-62
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @7; ImportDeclaration

### devtools/client/jsonview/components/JsonPanel.mjs

Blob: `e5ccc35c049d3979673d0b5d88fbdd832b25c0d4`. Role: source. Parse: module.

- isObject @32-34; FunctionDeclaration; parameters=1; async=false; generator=false
- propTypes @42-56; FunctionExpression; parameters=0; async=false; generator=false
- splitPath @75-80; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @82-91; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @93-96; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @98-100; FunctionExpression; parameters=0; async=false; generator=false
- onKeyPress @102-104; FunctionExpression; parameters=0; async=false; generator=false
- onRowSelected @106-112; FunctionExpression; parameters=1; async=false; generator=false
- updateBreadcrumbs @117-137; FunctionExpression; parameters=1; async=false; generator=false
- onFilter @139-160; FunctionExpression; parameters=1; async=false; generator=false
- renderValue @162-190; FunctionExpression; parameters=1; async=false; generator=false
- renderTree @192-214; FunctionExpression; parameters=0; async=false; generator=false
- render @216-259; FunctionExpression; parameters=0; async=false; generator=false
- getJsonValueType @272-282; FunctionDeclaration; parameters=1; async=false; generator=false
- Class JsonPanel @41-260
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @9; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @10; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @11; ImportDeclaration
- Module resource://devtools/client/shared/components/tree/TreeView.mjs @13; ImportDeclaration
- Module resource://devtools/client/shared/components/tree/ObjectProvider.mjs @14; ImportDeclaration
- Module resource://devtools/client/jsonview/components/JsonToolbar.mjs @15; ImportDeclaration
- Module resource://devtools/client/jsonview/components/JsonBreadcrumb.mjs @16; ImportDeclaration
- Module resource://devtools/client/shared/components/reps/reps/constants.mjs @18; ImportDeclaration
- Module resource://devtools/client/shared/components/reps/reps/rep.mjs @22; ImportDeclaration
- Module resource://devtools/client/shared/jsonl-utils.mjs @23; ImportDeclaration

### devtools/client/jsonview/components/JsonToolbar.mjs

Blob: `dd85eb3d603cdfcf65d25c42e5f2340d24a40f0d`. Role: source. Parse: module.

- propTypes @24-29; FunctionExpression; parameters=0; async=false; generator=false
- constructor @31-37; FunctionExpression; parameters=1; async=false; generator=false
- onSave @41-43; FunctionExpression; parameters=0; async=false; generator=false
- onCopy @45-47; FunctionExpression; parameters=0; async=false; generator=false
- onCollapse @49-51; FunctionExpression; parameters=0; async=false; generator=false
- onExpand @53-55; FunctionExpression; parameters=0; async=false; generator=false
- render @57-83; FunctionExpression; parameters=0; async=false; generator=false
- Class JsonToolbar @23-84
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @8; ImportDeclaration
- Module resource://devtools/client/jsonview/components/SearchBox.mjs @10; ImportDeclaration
- Module resource://devtools/client/jsonview/components/reps/Toolbar.mjs @13; ImportDeclaration

### devtools/client/jsonview/components/LiveText.mjs

Blob: `7ad39c12eca04d51edde3aa190b287328aba8d13`. Role: source. Parse: module.

- propTypes @17-21; FunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @23-25; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @27-34; FunctionExpression; parameters=0; async=false; generator=false
- render @36-38; FunctionExpression; parameters=0; async=false; generator=false
- Class LiveText @16-39
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @8; ImportDeclaration

### devtools/client/jsonview/components/MainTabbedArea.mjs

Blob: `31f100312248764814ad9990493d0a84d99ccef8`. Role: source. Parse: module.

- propTypes @28-44; FunctionExpression; parameters=0; async=false; generator=false
- constructor @46-58; FunctionExpression; parameters=1; async=false; generator=false
- onTabChanged @60-65; FunctionExpression; parameters=1; async=false; generator=false
- onProfileSize @67-69; FunctionExpression; parameters=0; async=false; generator=false
- renderToolbarButton @71-84; FunctionExpression; parameters=0; async=false; generator=false
- render @86-137; FunctionExpression; parameters=0; async=false; generator=false
- renderToolbarButton @92-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class MainTabbedArea @27-138
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @8; ImportDeclaration
- Module resource://devtools/client/jsonview/components/JsonPanel.mjs @10; ImportDeclaration
- Module resource://devtools/client/jsonview/components/TextPanel.mjs @13; ImportDeclaration
- Module resource://devtools/client/jsonview/components/HeadersPanel.mjs @16; ImportDeclaration
- Module resource://devtools/client/shared/components/tabs/Tabs.mjs @19; ImportDeclaration

### devtools/client/jsonview/components/SearchBox.mjs

Blob: `9d4694394a861c47f015d9b42a8b24939f800532`. Role: source. Parse: module.

- propTypes @19-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @26-36; FunctionExpression; parameters=1; async=false; generator=false
- onSearch @38-51; FunctionExpression; parameters=1; async=false; generator=false
- doSearch @53-55; FunctionExpression; parameters=1; async=false; generator=false
- onClearButtonClick @57-63; FunctionExpression; parameters=0; async=false; generator=false
- onKeyDown @65-72; FunctionExpression; parameters=1; async=false; generator=false
- render @74-94; FunctionExpression; parameters=0; async=false; generator=false
- ref @84-86; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class SearchBox @18-95
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @7; ImportDeclaration

### devtools/client/jsonview/components/TextPanel.mjs

Blob: `0ec51692c758cccb03c46502ecc1f6a3385b486b`. Role: source. Parse: module.

- propTypes @23-30; FunctionExpression; parameters=0; async=false; generator=false
- constructor @32-35; FunctionExpression; parameters=1; async=false; generator=false
- render @37-49; FunctionExpression; parameters=0; async=false; generator=false
- Class TextPanel @22-50
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @8; ImportDeclaration
- Module resource://devtools/client/jsonview/components/TextToolbar.mjs @10; ImportDeclaration
- Module resource://devtools/client/jsonview/components/LiveText.mjs @13; ImportDeclaration

### devtools/client/jsonview/components/TextToolbar.mjs

Blob: `601a4a6d2bd040afc1f4a263809d57768fba4838`. Role: source. Parse: module.

- propTypes @18-23; FunctionExpression; parameters=0; async=false; generator=false
- constructor @25-30; FunctionExpression; parameters=1; async=false; generator=false
- onPrettify @34-36; FunctionExpression; parameters=0; async=false; generator=false
- onSave @38-40; FunctionExpression; parameters=0; async=false; generator=false
- onCopy @42-44; FunctionExpression; parameters=0; async=false; generator=false
- render @46-73; FunctionExpression; parameters=0; async=false; generator=false
- Class TextToolbar @17-74
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @7; ImportDeclaration
- Module resource://devtools/client/jsonview/components/reps/Toolbar.mjs @9; ImportDeclaration

### devtools/client/jsonview/components/reps/Toolbar.mjs

Blob: `f82b3013a0fcee9a8a09900edac7571a8b69c3a8`. Role: source. Parse: module.

- propTypes @13-17; FunctionExpression; parameters=0; async=false; generator=false
- render @19-21; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @28-34; FunctionExpression; parameters=0; async=false; generator=false
- render @36-39; FunctionExpression; parameters=0; async=false; generator=false
- Class ToolbarButton @27-40
- Class Toolbar @12-22
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @7; ImportDeclaration

### devtools/client/jsonview/converter-child.js

Blob: `2ad96b9eb477bd31607e6a286fad6f16eedcbafc`. Role: source. Parse: module.

- (anonymous) @34-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- wrappedJSObject @54-56; FunctionExpression; parameters=0; async=false; generator=false
- convert @68-70; FunctionExpression; parameters=1; async=false; generator=false
- asyncConvertData @72-75; FunctionExpression; parameters=3; async=false; generator=false
- getConvertedType @77-85; FunctionExpression; parameters=2; async=false; generator=false
- onDataAvailable @87-92; FunctionExpression; parameters=4; async=false; generator=false
- onStartRequest @94-160; FunctionExpression; parameters=1; async=false; generator=false
- onStopRequest @162-173; FunctionExpression; parameters=2; async=false; generator=false
- decodeAndInsertBuffer @176-183; FunctionExpression; parameters=2; async=false; generator=false
- fixSave @198-227; FunctionDeclaration; parameters=2; async=false; generator=false
- getHttpHeaders @229-249; FunctionDeclaration; parameters=1; async=false; generator=false
- visitHeader @238-240; FunctionExpression; parameters=2; async=false; generator=false
- visitHeader @243-245; FunctionExpression; parameters=2; async=false; generator=false
- getAllStrings @252-260; FunctionDeclaration; parameters=0; async=false; generator=false
- getWindowForRequest @272-282; FunctionDeclaration; parameters=1; async=false; generator=false
- getRequestLoadContext @290-306; FunctionDeclaration; parameters=1; async=false; generator=false
- exportData @309-347; FunctionDeclaration; parameters=3; async=false; generator=false
- initialHTML @350-407; FunctionDeclaration; parameters=1; async=false; generator=false
- element @352-359; FunctionDeclaration; parameters=3; async=false; generator=false
- insertJsonData @413-430; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @414-426; FunctionExpression; parameters=2; async=false; generator=false
- keepThemeUpdated @432-445; FunctionDeclaration; parameters=1; async=false; generator=false
- listener @433-435; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @439-442; FunctionExpression; parameters=0; async=false; generator=false
- onContentMessage @448-463; FunctionDeclaration; parameters=1; async=false; generator=false
- createInstance @465-467; FunctionDeclaration; parameters=0; async=false; generator=false
- Class Converter @47-184

### devtools/client/jsonview/json-size-profiler.mjs

Blob: `37ad9af6b924775fc39677603f8cfc560dfa200a`. Role: source. Parse: module.

- constructor @32-87; FunctionExpression; parameters=3; async=false; generator=false
- internString @95-102; FunctionExpression; parameters=1; async=false; generator=false
- getOrCreateFrame @111-123; FunctionExpression; parameters=2; async=false; generator=false
- getOrCreateStack @132-143; FunctionExpression; parameters=2; async=false; generator=false
- getStack @153-164; FunctionExpression; parameters=3; async=false; generator=false
- advanceToPos @185-206; FunctionExpression; parameters=1; async=false; generator=false
- advanceByAsciiChars @213-216; FunctionExpression; parameters=1; async=false; generator=false
- parsePrimitive @225-240; FunctionExpression; parameters=3; async=false; generator=false
- exitScope @245-250; FunctionExpression; parameters=0; async=false; generator=false
- recordBytesConsumed @267-300; FunctionExpression; parameters=0; async=false; generator=false
- recordSamples @305-329; FunctionExpression; parameters=0; async=false; generator=false
- getCurrentScope @336-351; FunctionExpression; parameters=0; async=false; generator=false
- skipWhitespace @356-364; FunctionExpression; parameters=0; async=false; generator=false
- parseValue @371-393; FunctionExpression; parameters=1; async=false; generator=false
- parseObject @400-470; FunctionExpression; parameters=1; async=false; generator=false
- parseArray @477-525; FunctionExpression; parameters=1; async=false; generator=false
- parseString @532-534; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @533-533; ArrowFunctionExpression; parameters=0; async=false; generator=false
- parseStringValue @541-585; FunctionExpression; parameters=0; async=false; generator=false
- parseNumber @592-611; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @593-610; ArrowFunctionExpression; parameters=0; async=false; generator=false
- parseBool @618-628; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @619-627; ArrowFunctionExpression; parameters=0; async=false; generator=false
- parseNull @635-643; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @636-642; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getSeparatorStack @651-653; FunctionExpression; parameters=0; async=false; generator=false
- getParseErrorStack @660-662; FunctionExpression; parameters=0; async=false; generator=false
- parseJsonlines @680-713; FunctionExpression; parameters=0; async=false; generator=false
- isValidRecord @726-733; FunctionExpression; parameters=2; async=false; generator=false
- parse @740-880; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @782-786; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @849-849; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createSizeProfile @892-895; FunctionDeclaration; parameters=3; async=false; generator=false
- Class JsonSizeProfiler @25-881

### devtools/client/jsonview/json-viewer.mjs

Blob: `a1f8dec9f9e94bdbc224904955952b978b26fdbe`. Role: source. Parse: module.

- expandAllNodes @50-89; FunctionDeclaration; parameters=2; async=false; generator=false
- walkTree @53-76; FunctionDeclaration; parameters=2; async=false; generator=false
- expandBucketsWithMatches @94-141; FunctionDeclaration; parameters=2; async=false; generator=false
- walkTree @97-128; FunctionDeclaration; parameters=2; async=false; generator=false
- onCopyJson @148-151; FunctionExpression; parameters=0; async=false; generator=false
- onSaveJson @153-160; FunctionExpression; parameters=0; async=false; generator=false
- onCopyHeaders @162-182; FunctionExpression; parameters=0; async=false; generator=false
- onSearch @184-189; FunctionExpression; parameters=1; async=false; generator=false
- onPrettify @191-223; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-214; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onCollapse @225-228; FunctionExpression; parameters=0; async=false; generator=false
- onExpand @230-235; FunctionExpression; parameters=0; async=false; generator=false
- onProfileSize @237-298; FunctionExpression; parameters=0; async=true; generator=false
- messageHandler @272-280; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @287-287; ArrowFunctionExpression; parameters=1; async=false; generator=false
- copyString @306-317; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @309-312; ArrowFunctionExpression; parameters=1; async=false; generator=false
- dispatchEvent @325-335; FunctionDeclaration; parameters=2; async=false; generator=false
- parseJSON @342-424; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @347-349; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @351-359; ArrowFunctionExpression; parameters=0; async=true; generator=false
- data @375-377; FunctionExpression; parameters=0; async=false; generator=false
- text @379-381; FunctionExpression; parameters=0; async=false; generator=false
- headers @383-385; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @426-442; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @427-441; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @436-440; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://devtools/client/shared/vendor/react-dom.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @8; ImportDeclaration
- Module resource://devtools/client/jsonview/components/MainTabbedArea.mjs @10; ImportDeclaration
- Module resource://devtools/client/shared/components/tree/TreeView.mjs @11; ImportDeclaration
- Module resource://devtools/client/shared/components/tree/ObjectProvider.mjs @12; ImportDeclaration
- Module resource://devtools/client/shared/components/reps/reps/constants.mjs @13; ImportDeclaration
- Module resource://devtools/client/shared/components/reps/reps/rep-utils.mjs @14; ImportDeclaration
- Module resource://devtools/client/shared/jsonl-utils.mjs @15; ImportDeclaration
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @16; ImportDeclaration

### devtools/client/jsonview/test/browser_json_refresh.js

Blob: `e145c61102e4bae0f9bc7d0b08439d11ee9c2ad2`. Role: test-path,source. Parse: module.

- (anonymous) @8-99; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-54; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @65-97; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_access_data.js

Blob: `703d5a289d031feff53363826c1fc950a742d822`. Role: test-path,source. Parse: module.

- getConsoleMessages @14-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_console_welcome_message @28-56; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getJSONViewData @61-67; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @64-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testJSONViewData @75-80; FunctionDeclaration; parameters=2; async=true; generator=false
- test_jsonview_data_object @82-91; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_array @93-95; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_primitive @97-99; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_string @101-103; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_null @105-107; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_invalid_json @109-114; FunctionExpression; parameters=0; async=true; generator=false
- test_jsonview_data_large_array @116-122; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_jsonview_text @124-134; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @129-131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_jsonview_headers @136-152; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @144-146; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_array_buckets.js

Blob: `c8974d5d0bb5e677dd4da2c032990657cd6fd744`. Role: test-path,source. Parse: module.

- loadJsonData @14-17; FunctionDeclaration; parameters=1; async=true; generator=false
- getBucketLabels @22-31; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @23-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasBuckets @36-43; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @37-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_small_array_no_buckets @45-56; FunctionExpression; parameters=0; async=true; generator=false
- test_medium_array_has_buckets @58-76; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-61; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_expand_bucket @78-115; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @89-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @105-112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_large_array_bucket_size @117-129; FunctionExpression; parameters=0; async=true; generator=false
- test_very_large_array_bucket_size @131-143; FunctionExpression; parameters=0; async=true; generator=false
- test_nested_buckets @145-196; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @151-151; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @156-166; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @160-161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @173-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @178-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @179-189; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_breadcrumb.js

Blob: `ed55d05d6f3a2b6999496f71c771ab2e668f9692`. Role: test-path,source. Parse: module.

- (anonymous) @9-337; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-55; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-90; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-131; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-166; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @181-205; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @208-257; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @260-305; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @316-336; FunctionExpression; parameters=0; async=false; generator=false
- assertBoolean @339-382; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @343-380; FunctionExpression; parameters=2; async=false; generator=false
- assertNumber @384-427; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @388-425; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_bug_1380828.js

Blob: `6d698e893003e74cc8c491e84f2569c2b6372e6e`. Role: test-path,source. Parse: module.

- (anonymous) @10-15; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-22; FunctionExpression; parameters=0; async=true; generator=false
- testPrettyPrintButton @24-32; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_chunked_json.js

Blob: `56fe611486b342596357c172680ffa4ae1d8a63e`. Role: test-path,source. Parse: module.

- (anonymous) @8-90; FunctionExpression; parameters=0; async=true; generator=false
- write @93-109; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @98-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @99-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkText @110-112; FunctionDeclaration; parameters=1; async=true; generator=false
- server @114-121; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @115-120; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_content_type.js

Blob: `63143bbece983c3c742ce789e7c2d9b58936335b`. Role: test-path,source. Parse: module.

- (anonymous) @29-72; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-71; FunctionExpression; parameters=0; async=false; generator=false
- testType @74-102; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @77-93; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @82-88; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @94-100; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_copy_headers.js

Blob: `faa6e4335467488e1edb4276a8493815d0966ef1`. Role: test-path,source. Parse: module.

- (anonymous) @8-38; FunctionExpression; parameters=0; async=true; generator=false
- setup @27-33; FunctionExpression; parameters=0; async=false; generator=false
- validator @34-36; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_copy_json.js

Blob: `35503097e36e97a06bfda02419916003b832a13d`. Role: test-path,source. Parse: module.

- (anonymous) @8-34; FunctionExpression; parameters=0; async=true; generator=false
- setup @26-28; FunctionExpression; parameters=0; async=false; generator=false
- validator @29-32; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_copy_rawdata.js

Blob: `0685b7c5d30f3a9e340cc0562d6a2cace3fbcc58`. Role: test-path,source. Parse: module.

- (anonymous) @11-62; FunctionExpression; parameters=0; async=true; generator=false
- setup @26-32; FunctionExpression; parameters=0; async=false; generator=false
- setup @50-56; FunctionExpression; parameters=0; async=false; generator=false
- validator @57-60; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_csp_json.js

Blob: `4416bccf15c8dc7b43539f295f8bc5db9e95ddf5`. Role: test-path,source. Parse: module.

- (anonymous) @8-33; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-32; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_data_blocking.js

Blob: `f36d39dcc8af823f0a6d8cea3a8b86d83fdfc77c`. Role: test-path,source. Parse: module.

- test_blocked_data_exposure @22-60; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-59; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @41-49; FunctionExpression; parameters=0; async=false; generator=false
- test_converter_abort_should_stop_data_sending @65-114; FunctionExpression; parameters=0; async=true; generator=false
- getInterface @83-86; FunctionExpression; parameters=0; async=false; generator=false
- setProperty @89-89; FunctionExpression; parameters=0; async=false; generator=false
- onStartRequest @94-98; FunctionExpression; parameters=0; async=false; generator=false
- onDataAvailable @99-101; FunctionExpression; parameters=0; async=false; generator=false
- test_converter_principal_needs_matching @123-174; FunctionExpression; parameters=0; async=true; generator=false
- getInterface @141-144; FunctionExpression; parameters=0; async=false; generator=false
- setProperty @147-147; FunctionExpression; parameters=0; async=false; generator=false
- cancel @148-150; FunctionExpression; parameters=1; async=false; generator=false
- onStartRequest @155-157; FunctionExpression; parameters=0; async=false; generator=false
- onDataAvailable @158-160; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_empty_object.js

Blob: `af3dfbc007d1f759a29c56880d07dd342ca28bfc`. Role: test-path,source. Parse: module.

- testRootObject @6-16; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @7-15; FunctionExpression; parameters=0; async=true; generator=false
- testNestedObject @18-43; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-42; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_encoding.js

Blob: `be49af39d24df5d6a542a15f0e4812bb61858e4e`. Role: test-path,source. Parse: module.

- (anonymous) @6-67; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_expand_collapse.js

Blob: `04e0834f2a861baf9c93c884935eac147e79bbe3`. Role: test-path,source. Parse: module.

- (anonymous) @6-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-40; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_favicon.js

Blob: `b03bf1a94d664058cc15fef385f3448693a707f2`. Role: test-path,source. Parse: module.

- test_favicon @14-46; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-24; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @26-30; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/httpd.sys.mjs @10; ChromeUtils-import-literal

### devtools/client/jsonview/test/browser_jsonview_filter.js

Blob: `1dd093da5b193a896091d05591ed82c7d8c7c7ed`. Role: test-path,source. Parse: module.

- (anonymous) @8-27; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_filter_clear.js

Blob: `70ece7ee038481da53d75ea79fe6b5feaa66beb2`. Role: test-path,source. Parse: module.

- clickAndWaitForFilterClear @9-49; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-43; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-81; FunctionExpression; parameters=0; async=true; generator=false
- getFilterInputValue @83-85; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_iframes_ignored.js

Blob: `193076b6046367ec5548f949739b563a7a1c4845`. Role: test-path,source. Parse: module.

- (anonymous) @8-40; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-39; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_ignore_charset.js

Blob: `ffd00a35e35904c17ee34529336bfb5fa6c0dc94`. Role: test-path,source. Parse: module.

- (anonymous) @6-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_initial_focus.js

Blob: `3e74e992541a408c70753e1c432bbde9297e5f3f`. Role: test-path,source. Parse: module.

- (anonymous) @8-33; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-20; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @22-32; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_invalid_json.js

Blob: `9dd957fa5e17ba0f56623d84b10c08263e90f24c`. Role: test-path,source. Parse: module.

- (anonymous) @8-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_jsonl.js

Blob: `c452469476e7def65f1a4fcbef1f4c89f463eaf3`. Role: test-path,source. Parse: module.

- getRowsCount @6-8; FunctionDeclaration; parameters=0; async=false; generator=false
- testContentTypeSniffing @10-31; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @22-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testLineByLineParsing @33-62; FunctionExpression; parameters=0; async=true; generator=false
- testNoPrettyPrintForJsonl @64-79; FunctionExpression; parameters=0; async=true; generator=false
- testSaveAsRestoresJsonlContentType @81-115; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @102-108; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testExtensionFallback @117-137; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @123-134; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_manifest.js

Blob: `8072324cf1c95a0e56aad9ea228f251410408b13`. Role: test-path,source. Parse: module.

- (anonymous) @8-15; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_multipart_response.js

Blob: `b7841ab1d79e42c9bbab44e6d263f4a29f146fd1`. Role: test-path,source. Parse: module.

- test_json_in_multipart_response @11-37; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-34; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_nojs.js

Blob: `38459617a2b4d148831782db4e7fee205de4a346`. Role: test-path,source. Parse: module.

- (anonymous) @6-26; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_nul.js

Blob: `746846796b05bd2eea8af9be34618885a1280270`. Role: test-path,source. Parse: module.

- (anonymous) @6-15; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_numbers.js

Blob: `1d965ad830d3195a6326b50e013d6bb1470a682d`. Role: test-path,source. Parse: module.

- (anonymous) @6-172; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-134; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-28; ArrowFunctionExpression; parameters=2; async=false; generator=false
- testBigNumberNotNested @174-226; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @177-208; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_object-type.js

Blob: `221413b3727017a1519b9c8bb0bd2bf403c5ce0f`. Role: test-path,source. Parse: module.

- (anonymous) @6-84; FunctionExpression; parameters=0; async=true; generator=false
- getRowsCount @86-88; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_profile_size.js

Blob: `464d14fbc6759dc92862e30d241b2bbe225677ff`. Role: test-path,source. Parse: module.

- (anonymous) @10-18; FunctionExpression; parameters=0; async=true; generator=false
- bytesByLeafFrame @30-41; FunctionDeclaration; parameters=1; async=false; generator=false
- totalProfiledBytes @51-56; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=2; async=false; generator=false
- utf8Length @58-60; FunctionDeclaration; parameters=1; async=false; generator=false
- testProfileSizeButtonExists @62-77; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @70-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testProfileSizePostMessage @79-174; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @87-131; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-130; FunctionExpression; parameters=1; async=false; generator=false
- postMessage @105-125; FunctionExpression; parameters=2; async=false; generator=false
- close @126-126; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @134-137; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-145; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @142-144; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testProfileCreation @176-209; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithJsonl @211-246; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithInvalidJsonlLine @248-277; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithTruncatedJsonlLine @279-310; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithJsonlSeparators @312-335; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithJsonlUtf8 @337-363; FunctionExpression; parameters=0; async=true; generator=false
- testProfileCreationWithUtf8 @365-396; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @179; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @214; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @251; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @282; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @315; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @340; ChromeUtils-import-literal
- Module resource://devtools/client/jsonview/json-size-profiler.mjs @368; ChromeUtils-import-literal

### devtools/client/jsonview/test/browser_jsonview_row_selection.js

Blob: `b2e3c3f991e9d396b7cbfc24b30a8f51d398539e`. Role: test-path,source. Parse: module.

- (anonymous) @6-84; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @30-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-48; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-65; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-75; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @78-83; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-133; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @104-106; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @135-237; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @144-159; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @161-170; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @175-188; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @194-223; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @230-235; FunctionExpression; parameters=1; async=false; generator=false
- assertRowSelected @239-255; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @243-248; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_save_json.js

Blob: `c490aa0104090d436780a6568d1553dcac3dc904`. Role: test-path,source. Parse: module.

- awaitSavedFileContents @18-62; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-61; ArrowFunctionExpression; parameters=2; async=false; generator=false
- MockFilePicker.showCallback @20-60; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mockTransferCallback @38-56; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-50; ArrowFunctionExpression; parameters=0; async=true; generator=false
- createTemporarySaveDirectory @64-73; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @78-83; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @85-132; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @134-145; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @147-158; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_serviceworker.js

Blob: `c8be1a939a30c168b650c1cf331903eed2e09fce`. Role: test-path,source. Parse: module.

- (anonymous) @10-86; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-43; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @31-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-82; ArrowFunctionExpression; parameters=1; async=true; generator=false
- countRows @88-90; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_slash.js

Blob: `f8abeca7befcd7546977a08116814cad8bf3cdc6`. Role: test-path,source. Parse: module.

- (anonymous) @6-16; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/jsonview/test/browser_jsonview_theme.js

Blob: `c66d197256663a37ff34da26fa8678de3750a110`. Role: test-path,source. Parse: module.

- (anonymous) @8-25; FunctionExpression; parameters=0; async=true; generator=false
- getTheme @27-29; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_url_linkification.js

Blob: `d5c0095095f89d2ca7e4bd90691bd2328911b41c`. Role: test-path,source. Parse: module.

- (anonymous) @8-25; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-46; FunctionExpression; parameters=0; async=true; generator=false
- testLinkNavigation @59-88; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @67-82; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/browser_jsonview_valid_json.js

Blob: `b42ff642deeac7cb92e99273701e552d137e7661`. Role: test-path,source. Parse: module.

- (anonymous) @8-43; FunctionExpression; parameters=0; async=true; generator=false
- countRows @45-47; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/jsonview/test/chunked_json.sjs

Blob: `554b62bafdb02a7324842480e9cf390acee38aa6`. Role: test-path,data-or-other. Parse: module.

- setResponse @6-8; FunctionDeclaration; parameters=1; async=false; generator=false
- getResponse @9-15; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @11-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleRequest @17-39; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/jsonview/test/head.js

Blob: `503eba8609a1b846f74f3b73ed1accab51bc46a1`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addJsonViewTab @48-131; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @66-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @67-78; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-77; ArrowFunctionExpression; parameters=2; async=false; generator=false
- requirejs.onError @71-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @87-126; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @108-112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @120-124; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clickJsonNode @136-143; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @140-142; ArrowFunctionExpression; parameters=1; async=false; generator=false
- selectJsonViewContentTab @148-180; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @152-179; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @161-173; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @164-169; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getElementCount @182-192; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @188-190; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getElementText @194-205; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @200-203; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getElementAttr @207-218; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @213-216; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getRowText @226-234; FunctionDeclaration; parameters=1; async=true; generator=false
- focusElement @236-249; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @242-247; ArrowFunctionExpression; parameters=1; async=false; generator=false
- sendString @257-274; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @263-272; ArrowFunctionExpression; parameters=2; async=false; generator=false
- waitForTime @276-278; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @277-277; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitForFilter @280-310; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @281-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-308; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @294-305; FunctionExpression; parameters=1; async=false; generator=false
- normalizeNewLines @312-314; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/json_multipart.sjs

Blob: `3ed7cd567e29febab50f8b8048c389b2adcc66a4`. Role: test-path,data-or-other. Parse: module.

- handleRequest @14-33; FunctionDeclaration; parameters=2; async=true; generator=false
- sleep @35-41; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @36-39; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/jsonview/test/passthrough-sw.js

Blob: `019d218bc2fb44c82945454591fe1e56413c8ba4`. Role: test-path,source. Parse: module.

- (anonymous) @3-5; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/.eslintrc.mjs

Blob: `25ad7312cd8110faae85ec849e271cef6cd12c47`. Role: source. Parse: module.

- Module globals @5; ImportDeclaration

### devtools/client/memory/actions/allocations.js

Blob: `47bc68e1c292d4e904a1a1f6a92176f2ae61f8ca`. Role: source. Parse: module.

- exports.toggleRecordingAllocationStacks @11-32; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-31; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/actions/census-display.js

Blob: `9abd16d99b0b641a9c2ccdb5771c603d00fa736d`. Role: source. Parse: module.

- exports.setCensusDisplayAndRefresh @12-17; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @13-16; FunctionExpression; parameters=1; async=true; generator=false
- exports.setCensusDisplay @25-39; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/diffing.js

Blob: `1442cbc0a721868608554cce510742c3d9d8f785`. Role: source. Parse: module.

- exports.toggleDiffing @26-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-34; FunctionExpression; parameters=1; async=false; generator=false
- exports.selectSnapshotForDiffing @42-50; FunctionExpression; parameters=1; async=false; generator=false
- exports.takeCensusDiff @59-138; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @64-137; FunctionExpression; parameters=1; async=true; generator=false
- exports.refreshDiffing @147-167; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @148-166; FunctionExpression; parameters=1; async=false; generator=false
- exports.selectSnapshotForDiffingAndRefresh @176-185; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @177-184; FunctionExpression; parameters=1; async=true; generator=false
- exports.expandDiffingCensusNode @192-197; FunctionExpression; parameters=1; async=false; generator=false
- exports.collapseDiffingCensusNode @204-209; FunctionExpression; parameters=1; async=false; generator=false
- exports.focusDiffingCensusNode @216-221; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/filter.js

Blob: `1b48c140bc24faa353306b1e2bd17d05884bebc3`. Role: source. Parse: module.

- exports.setFilterString @15-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-35; ArrowFunctionExpression; parameters=3; async=false; generator=false
- exports.setFilterStringAndRefresh @39-44; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @40-43; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/front.js

Blob: `3ae10ea9cc2c7695183306583c5d9e0c562ec6bf`. Role: source. Parse: module.

- exports.updateMemoryFront @12-17; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/io.js

Blob: `bedd5d8bfc90b00537ae54550cecbcf82be264d5`. Role: source. Parse: module.

- exports.pickFileAndExportSnapshot @27-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-41; FunctionExpression; parameters=1; async=true; generator=false
- exports.exportSnapshot @44-62; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @45-61; FunctionExpression; parameters=1; async=true; generator=false
- exports.pickFileAndImportSnapshotAndCensus @64-78; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-77; FunctionExpression; parameters=1; async=true; generator=false
- importSnapshotAndCensus @80-102; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @81-101; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/actions/label-display.js

Blob: `cd90fcff3bb268dc3e072ea10da2a196ec08ef75`. Role: source. Parse: module.

- exports.setLabelDisplayAndRefresh @16-22; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @17-21; FunctionExpression; parameters=1; async=true; generator=false
- exports.setLabelDisplay @29-43; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/refresh.js

Blob: `33401fa29975d107f4e7df38d6dd484f8399fc1f`. Role: source. Parse: module.

- exports.refresh @18-49; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-48; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/actions/sizes.js

Blob: `c5a98e23e9feffab2c8d5f869f5ed5cba6b1799e`. Role: source. Parse: module.

- exports.resizeShortestPaths @8-13; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/snapshot.js

Blob: `c8e44e1a7c2bd83d3bed97feb99aa39168394df1`. Role: source. Parse: module.

- exports.takeSnapshotAndCensus @39-53; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @40-52; FunctionExpression; parameters=1; async=true; generator=false
- exports.computeSnapshotData @63-83; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @67-82; FunctionExpression; parameters=1; async=true; generator=false
- exports.selectSnapshotAndRefresh @92-101; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @93-100; FunctionExpression; parameters=1; async=true; generator=false
- exports.takeSnapshot @109-132; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @110-131; FunctionExpression; parameters=1; async=true; generator=false
- getCacheKey @142-144; FunctionExpression; parameters=2; async=false; generator=false
- task @146-168; FunctionExpression; parameters=5; async=true; generator=false
- makeTakeCensusTask @184-280; FunctionDeclaration; parameters=1; async=false; generator=false
- getCacheKey @203-205; FunctionExpression; parameters=2; async=false; generator=false
- task @207-278; FunctionExpression; parameters=5; async=true; generator=false
- getDisplay @286-286; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getFilter @287-287; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getCensus @288-288; ArrowFunctionExpression; parameters=1; async=false; generator=false
- canTakeCensus @292-294; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getDisplay @301-301; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getFilter @302-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getCensus @303-303; ArrowFunctionExpression; parameters=1; async=false; generator=false
- canTakeCensus @307-309; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.getCurrentCensusTaker @326-337; FunctionExpression; parameters=1; async=false; generator=false
- exports.focusIndividual @344-349; FunctionExpression; parameters=1; async=false; generator=false
- exports.fetchIndividuals @360-442; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @366-441; FunctionExpression; parameters=1; async=true; generator=false
- exports.refreshIndividuals @449-488; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @450-487; FunctionExpression; parameters=1; async=true; generator=false
- exports.refreshSelectedCensus @496-516; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @497-515; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @498-498; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.refreshSelectedTreeMap @524-544; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @525-543; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @526-526; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getCacheKey @557-559; FunctionExpression; parameters=2; async=false; generator=false
- task @561-587; FunctionExpression; parameters=5; async=true; generator=false
- getCacheKey @601-603; FunctionExpression; parameters=2; async=false; generator=false
- task @605-644; FunctionExpression; parameters=5; async=true; generator=false
- getCacheKey @656-658; FunctionExpression; parameters=3; async=false; generator=false
- task @660-712; FunctionExpression; parameters=6; async=true; generator=false
- getCacheKey @726-728; FunctionExpression; parameters=2; async=false; generator=false
- task @730-747; FunctionExpression; parameters=4; async=true; generator=false
- exports.refreshSelectedDominatorTree @755-784; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @756-783; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @757-757; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.selectSnapshot @792-797; FunctionExpression; parameters=1; async=false; generator=false
- exports.clearSnapshots @804-837; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @805-836; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @806-813; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @815-815; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @827-832; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @828-831; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.deleteSnapshot @845-858; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @846-857; FunctionExpression; parameters=1; async=true; generator=false
- exports.expandCensusNode @865-871; FunctionExpression; parameters=2; async=false; generator=false
- exports.collapseCensusNode @878-884; FunctionExpression; parameters=2; async=false; generator=false
- exports.focusCensusNode @892-898; FunctionExpression; parameters=2; async=false; generator=false
- exports.expandDominatorTreeNode @905-911; FunctionExpression; parameters=2; async=false; generator=false
- exports.collapseDominatorTreeNode @918-924; FunctionExpression; parameters=2; async=false; generator=false
- exports.focusDominatorTreeNode @932-938; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/actions/task-cache.js

Blob: `c472cb69da0bfdaa28dd669bbd967684624001eb`. Role: source. Parse: module.

- constructor @14-16; FunctionExpression; parameters=0; async=false; generator=false
- get @24-26; FunctionExpression; parameters=1; async=false; generator=false
- put @35-39; FunctionExpression; parameters=2; async=false; generator=false
- remove @46-53; FunctionExpression; parameters=1; async=false; generator=false
- TaskCache.declareCacheableTask @65-105; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-104; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-103; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @82-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @88-99; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TaskCache @13-54

### devtools/client/memory/actions/tree-map-display.js

Blob: `38de0478c3a9749e57e0ac9e9395125a676d8770`. Role: source. Parse: module.

- exports.setTreeMapAndRefresh @15-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @16-19; FunctionExpression; parameters=1; async=true; generator=false
- exports.setTreeMap @28-42; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/actions/view.js

Blob: `5f1ab5c26355f59c45b6b420ffba32c25ea521b4`. Role: source. Parse: module.

- exports.changeView @18-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-26; FunctionExpression; parameters=1; async=false; generator=false
- exports.popView @33-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-41; FunctionExpression; parameters=1; async=false; generator=false
- exports.changeViewAndRefresh @51-56; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @52-55; FunctionExpression; parameters=1; async=true; generator=false
- exports.popViewAndRefresh @64-69; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-68; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/app.js

Blob: `7719a41327b2d32a833f2b532f058cd1503474ea`. Role: source. Parse: module.

- propTypes @95-112; FunctionExpression; parameters=0; async=false; generator=false
- childContextTypes @114-120; FunctionExpression; parameters=0; async=false; generator=false
- defaultProps @122-124; FunctionExpression; parameters=0; async=false; generator=false
- constructor @126-132; FunctionExpression; parameters=1; async=false; generator=false
- getChildContext @134-140; FunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @142-147; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @149-151; FunctionExpression; parameters=0; async=false; generator=false
- onKeyDown @153-174; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @155-155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _getCensusDisplays @176-188; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @178-181; ArrowFunctionExpression; parameters=2; async=false; generator=false
- _getLabelDisplays @190-200; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @192-195; ArrowFunctionExpression; parameters=2; async=false; generator=false
- _getTreeMapDisplays @202-210; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @204-207; ArrowFunctionExpression; parameters=2; async=false; generator=false
- render @212-430; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @230-230; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @234-235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @236-237; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onCensusDisplayChange @248-249; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onImportClick @250-251; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClearSnapshotsClick @252-252; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onTakeSnapshotClick @253-254; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onToggleRecordAllocationStacks @255-256; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setFilterString @259-260; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onToggleDiffing @262-262; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onLabelDisplayChange @266-267; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onTreeMapDisplayChange @269-270; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onViewChange @271-271; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onSave @282-282; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDelete @283-283; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onViewSourceInDebugger @291-293; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onSnapshotClick @294-295; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onLoadMoreSiblings @296-303; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onPopView @304-304; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onViewIndividuals @306-318; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onFocusIndividual @319-325; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onCensusExpand @326-341; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onCensusCollapse @342-357; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onCensusFocus @358-373; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onDominatorTreeExpand @374-389; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDominatorTreeCollapse @390-405; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDominatorTreeFocus @406-421; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onShortestPathsResize @422-424; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mapStateToProps @437-439; FunctionDeclaration; parameters=1; async=false; generator=false
- Class MemoryApp @94-431

### devtools/client/memory/components/Census.js

Blob: `536f8069bd2e443d926afb862bb36aedb2883186`. Role: source. Parse: module.

- propTypes @27-37; FunctionExpression; parameters=0; async=false; generator=false
- render @39-91; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getParent @64-67; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getChildren @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isExpanded @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderItem @73-86; ArrowFunctionExpression; parameters=5; async=false; generator=false
- getRoots @87-87; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getKey @88-88; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Census @26-92

### devtools/client/memory/components/CensusHeader.js

Blob: `ea8d95495285874200fc18f8c49c311a526ed151`. Role: source. Parse: module.

- propTypes @15-19; FunctionExpression; parameters=0; async=false; generator=false
- render @21-76; FunctionExpression; parameters=0; async=false; generator=false
- Class CensusHeader @14-77

### devtools/client/memory/components/CensusTreeItem.js

Blob: `f862bb49b5716bdc64a3f2e491d166e38ea254d8`. Role: source. Parse: module.

- propTypes @27-41; FunctionExpression; parameters=0; async=false; generator=false
- constructor @43-46; FunctionExpression; parameters=1; async=false; generator=false
- shouldComponentUpdate @48-56; FunctionExpression; parameters=1; async=false; generator=false
- toLabel @58-81; FunctionExpression; parameters=2; async=false; generator=false
- render @83-182; FunctionExpression; parameters=0; async=false; generator=false
- onClick @131-138; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class CensusTreeItem @26-183

### devtools/client/memory/components/DominatorTree.js

Blob: `8eac21f547c8e1f481476524ccb847eaf8c6f263`. Role: source. Parse: module.

- propTypes @40-44; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @46-48; FunctionExpression; parameters=1; async=false; generator=false
- render @50-64; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @72-78; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @80-82; FunctionExpression; parameters=1; async=false; generator=false
- render @84-107; FunctionExpression; parameters=0; async=false; generator=false
- onClick @101-101; ArrowFunctionExpression; parameters=0; async=false; generator=false
- propTypes @111-120; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @122-130; FunctionExpression; parameters=1; async=false; generator=false
- render @132-230; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-136; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getParent @143-146; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getChildren @147-155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isExpanded @156-160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onExpand @161-177; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onCollapse @178-184; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onFocus @185-191; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderItem @192-224; ArrowFunctionExpression; parameters=5; async=false; generator=false
- getPercentSize @220-221; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRoots @225-225; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getKey @226-227; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class DominatorTree @110-231
- Class DominatorTreeSiblingLinkClass @71-108
- Class DominatorTreeSubtreeFetchingClass @39-65

### devtools/client/memory/components/DominatorTreeHeader.js

Blob: `74fe638e971be566eb812733c847fea47ed5b516`. Role: source. Parse: module.

- propTypes @14-16; FunctionExpression; parameters=0; async=false; generator=false
- render @18-48; FunctionExpression; parameters=0; async=false; generator=false
- Class DominatorTreeHeader @13-49

### devtools/client/memory/components/DominatorTreeItem.js

Blob: `25898ebbf50da70c8cc882108a95a0d7e909e741`. Role: source. Parse: module.

- render @30-32; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @38-48; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @50-57; FunctionExpression; parameters=1; async=false; generator=false
- render @59-171; FunctionExpression; parameters=0; async=false; generator=false
- Class DominatorTreeItem @37-172
- Class SeparatorClass @29-33

### devtools/client/memory/components/Heap.js

Blob: `6fc1c343ef6b56fe34e7c561019a21cc477d8fa2`. Role: source. Parse: module.

- getState @72-94; FunctionDeclaration; parameters=4; async=false; generator=false
- shouldDisplayStatus @106-124; FunctionDeclaration; parameters=3; async=false; generator=false
- getStateStatusText @134-144; FunctionDeclaration; parameters=2; async=false; generator=false
- shouldDisplayThrobber @154-156; FunctionDeclaration; parameters=1; async=false; generator=false
- getError @167-203; FunctionDeclaration; parameters=3; async=false; generator=false
- propTypes @213-234; FunctionExpression; parameters=0; async=false; generator=false
- constructor @236-246; FunctionExpression; parameters=1; async=false; generator=false
- _renderHeapView @255-269; FunctionExpression; parameters=2; async=false; generator=false
- _renderInitial @271-282; FunctionExpression; parameters=1; async=false; generator=false
- _renderStatus @284-299; FunctionExpression; parameters=3; async=false; generator=false
- _renderError @301-307; FunctionExpression; parameters=3; async=false; generator=false
- _renderCensus @309-361; FunctionExpression; parameters=5; async=false; generator=false
- onExpand @354-354; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onCollapse @355-355; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onFocus @356-356; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _renderTreeMap @363-365; FunctionExpression; parameters=2; async=false; generator=false
- _renderIndividuals @367-427; FunctionExpression; parameters=4; async=false; generator=false
- _renderDominatorTree @429-466; FunctionExpression; parameters=4; async=false; generator=false
- render @468-543; FunctionExpression; parameters=0; async=false; generator=false
- Class Heap @212-544

### devtools/client/memory/components/Individuals.js

Blob: `8d445daae38216ecbc483b46ca28b04dbbfaaadd`. Role: source. Parse: module.

- propTypes @27-34; FunctionExpression; parameters=0; async=false; generator=false
- render @36-67; FunctionExpression; parameters=0; async=false; generator=false
- getParent @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getChildren @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isExpanded @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onExpand @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onCollapse @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderItem @51-62; ArrowFunctionExpression; parameters=5; async=false; generator=false
- getPercentSize @58-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRoots @63-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getKey @64-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Individuals @26-68

### devtools/client/memory/components/IndividualsHeader.js

Blob: `7857e994cbe217f64872520367a9482461fab625`. Role: source. Parse: module.

- propTypes @14-16; FunctionExpression; parameters=0; async=false; generator=false
- render @18-48; FunctionExpression; parameters=0; async=false; generator=false
- Class IndividualsHeader @13-49

### devtools/client/memory/components/List.js

Blob: `d24ff5c53a76f9e624f588e6e3882942fffa6a91`. Role: source. Parse: module.

- propTypes @19-25; FunctionExpression; parameters=0; async=false; generator=false
- render @27-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-41; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onClick @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class List @18-44

### devtools/client/memory/components/ShortestPaths.js

Blob: `afde4814ab39f1918f69d818ade7ff599a57b5f3`. Role: source. Parse: module.

- stringifyLabel @27-54; FunctionDeclaration; parameters=2; async=false; generator=false
- propTypes @57-64; FunctionExpression; parameters=0; async=false; generator=false
- constructor @66-70; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @72-76; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @78-80; FunctionExpression; parameters=1; async=false; generator=false
- componentDidUpdate @82-86; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @88-92; FunctionExpression; parameters=0; async=false; generator=false
- _renderGraph @94-155; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @138-143; FunctionExpression; parameters=0; async=false; generator=false
- render @157-193; FunctionExpression; parameters=0; async=false; generator=false
- Class ShortestPaths @56-194

### devtools/client/memory/components/SnapshotListItem.js

Blob: `c714ab49ed3ae2b892b405fc356926554c65cbaf`. Role: source. Parse: module.

- propTypes @29-38; FunctionExpression; parameters=0; async=false; generator=false
- render @40-139; FunctionExpression; parameters=0; async=false; generator=false
- onClick @108-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @117-120; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class SnapshotListItem @28-140

### devtools/client/memory/components/Toolbar.js

Blob: `da5486d0958acb936a43448a074cdb7bc96e1692`. Role: source. Parse: module.

- propTypes @17-40; FunctionExpression; parameters=0; async=false; generator=false
- render @42-306; FunctionExpression; parameters=0; async=false; generator=false
- onChange @83-88; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @85-85; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-99; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChange @112-112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChange @139-144; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-141; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @146-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChange @181-186; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @189-197; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChange @218-218; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Toolbar @16-307

### devtools/client/memory/components/TreeMap.js

Blob: `4856e8511172859aacc5ad836cecdb33aedd8577`. Role: source. Parse: module.

- propTypes @15-19; FunctionExpression; parameters=0; async=false; generator=false
- constructor @21-26; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @28-33; FunctionExpression; parameters=0; async=false; generator=false
- shouldComponentUpdate @35-39; FunctionExpression; parameters=1; async=false; generator=false
- componentDidUpdate @41-47; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @49-53; FunctionExpression; parameters=0; async=false; generator=false
- _stopVisualization @55-60; FunctionExpression; parameters=0; async=false; generator=false
- _startVisualization @62-67; FunctionExpression; parameters=0; async=false; generator=false
- render @69-74; FunctionExpression; parameters=0; async=false; generator=false
- Class TreeMap @14-75

### devtools/client/memory/components/tree-map/canvas-utils.js

Blob: `375f13764f856c6db591db26c70c334a85c59bc3`. Role: source. Parse: module.

- constructor @35-46; FunctionExpression; parameters=2; async=false; generator=false
- destroy @52-56; FunctionExpression; parameters=0; async=false; generator=false
- createContainingDiv @67-72; FunctionDeclaration; parameters=1; async=false; generator=false
- createCanvas @81-96; FunctionDeclaration; parameters=2; async=false; generator=false
- handleResizes @105-131; FunctionDeclaration; parameters=2; async=false; generator=false
- resize @109-119; FunctionDeclaration; parameters=0; async=false; generator=false
- removeResizeHandlers @128-130; FunctionExpression; parameters=0; async=false; generator=false
- Class Canvases @29-57

### devtools/client/memory/components/tree-map/color-coarse-type.js

Blob: `5914fc042cac8c9de7b059487d882e8c69db8777`. Role: source. Parse: module.

- findCoarseTypeIndex @28-36; FunctionDeclaration; parameters=1; async=false; generator=false
- depthColorFactor @44-46; FunctionDeclaration; parameters=1; async=false; generator=false
- typeColorFactor @54-56; FunctionDeclaration; parameters=1; async=false; generator=false
- colorCoarseType @64-70; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/components/tree-map/drag-zoom.js

Blob: `1a753d1179fd88074faabf8ec8630c1aefb413ef`. Role: source. Parse: module.

- constructor @28-68; FunctionExpression; parameters=3; async=false; generator=false
- createUpdateLoop @91-149; FunctionDeclaration; parameters=3; async=false; generator=false
- update @94-139; FunctionDeclaration; parameters=0; async=false; generator=false
- restartLoopingIfStopped @144-148; FunctionExpression; parameters=0; async=false; generator=false
- setHandlers @159-179; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @160-160; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeHandlers @175-178; FunctionExpression; parameters=0; async=false; generator=false
- setDragHandlers @190-234; FunctionDeclaration; parameters=4; async=false; generator=false
- startDrag @193-196; FunctionDeclaration; parameters=0; async=false; generator=false
- stopDrag @198-201; FunctionDeclaration; parameters=0; async=false; generator=false
- drag @203-221; FunctionDeclaration; parameters=1; async=false; generator=false
- removeListeners @228-233; FunctionExpression; parameters=0; async=false; generator=false
- setScrollHandlers @246-296; FunctionDeclaration; parameters=4; async=false; generator=false
- handleWheel @249-289; FunctionDeclaration; parameters=1; async=false; generator=false
- removeListener @293-295; FunctionExpression; parameters=0; async=false; generator=false
- getScrollDelta @304-310; FunctionDeclaration; parameters=1; async=false; generator=false
- keepInView @319-340; FunctionDeclaration; parameters=2; async=false; generator=false
- Class DragZoom @22-69

### devtools/client/memory/components/tree-map/draw.js

Blob: `824676f287dc6a0bcbd7d756b10670fb04d28c72`. Role: source. Parse: module.

- exports.setupDraw @54-74; FunctionExpression; parameters=3; async=false; generator=false
- drawFullTreemap @59-64; FunctionDeclaration; parameters=0; async=false; generator=false
- drawZoomedTreemap @66-69; FunctionDeclaration; parameters=0; async=false; generator=false
- exports.configureD3Treemap @82-124; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=1; async=false; generator=false
- depthSortedNodes @119-123; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=2; async=false; generator=false
- exports.drawTruncatedName @139-154; FunctionExpression; parameters=5; async=false; generator=false
- exports.drawText @172-225; FunctionExpression; parameters=6; async=false; generator=false
- exports.drawBox @237-261; FunctionExpression; parameters=5; async=false; generator=false
- exports.drawTreemap @271-300; FunctionExpression; parameters=3; async=false; generator=false
- borderWidth @286-289; FunctionDeclaration; parameters=1; async=false; generator=false
- positionZoomedCanvas @310-315; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/components/tree-map/start.js

Blob: `5b2f69d6a44c1bc66c8ab42c4fc9a4d09233a406`. Role: source. Parse: module.

- startVisualization @21-40; FunctionExpression; parameters=3; async=false; generator=false
- stopVisualization @36-39; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/constants.js

Blob: `a7c362df09ce0dc985197c2e34db3fb2ccf47bf0`. Role: source. Parse: module.

- tooltip @157-162; FunctionExpression; parameters=0; async=false; generator=false
- tooltip @169-172; FunctionExpression; parameters=0; async=false; generator=false
- tooltip @179-182; FunctionExpression; parameters=0; async=false; generator=false
- tooltip @207-210; FunctionExpression; parameters=0; async=false; generator=false
- tooltip @216-219; FunctionExpression; parameters=0; async=false; generator=false
- tooltip @231-234; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/dominator-tree-lazy-children.js

Blob: `a37975a48220ec3bc8efa676e72c9b85fcf90c2a`. Role: source. Parse: module.

- DominatorTreeLazyChildren @15-18; FunctionDeclaration; parameters=2; async=false; generator=false
- DominatorTreeLazyChildren.prototype.key @27-29; FunctionExpression; parameters=0; async=false; generator=false
- DominatorTreeLazyChildren.prototype.isFirstChild @38-40; FunctionExpression; parameters=0; async=false; generator=false
- DominatorTreeLazyChildren.prototype.parentNodeId @47-49; FunctionExpression; parameters=0; async=false; generator=false
- DominatorTreeLazyChildren.prototype.siblingIndex @56-58; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/initializer.js

Blob: `1eb869093730c95ef421ad3fd501bdb76441dfa9`. Role: source. Parse: module.

- initialize @31-48; FunctionExpression; parameters=1; async=true; generator=false
- updateFront @50-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- destroy @54-65; FunctionExpression; parameters=0; async=false; generator=false
- onStateChange @74-89; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/memory/models.js

Blob: `fa9ee605ca726670d9dbb72c1e3564eba9712bd5`. Role: source. Parse: module.

- catchAndIgnore @43-53; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @44-52; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @107-126; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-148; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @152-176; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @208-260; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @266-266; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @292-310; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @326-333; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @344-364; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @368-391; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @402-414; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @437-469; FunctionExpression; parameters=1; async=false; generator=false
- view @509-545; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @510-526; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @528-544; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/panel.js

Blob: `9528964de34d8632d3ef2f2f5d73477e98adaa76`. Role: source. Parse: module.

- constructor @11-28; FunctionExpression; parameters=3; async=false; generator=false
- open @29-41; FunctionExpression; parameters=0; async=true; generator=false
- _onTargetAvailable @43-49; FunctionExpression; parameters=1; async=true; generator=false
- destroy @53-70; FunctionExpression; parameters=0; async=false; generator=false
- Class MemoryPanel @10-71
- Module resource://devtools/shared/loader/browser-loader.sys.mjs @18; ChromeUtils-import-literal

### devtools/client/memory/reducers.js

Blob: `964f2c5cfd7148f02580d8d0a83737ac8e540b14`. Role: source. Parse: module.


### devtools/client/memory/reducers/allocations.js

Blob: `895e61676d7fe447027ed9b413e25e8a14e29cb7`. Role: source. Parse: module.

- handlers.[computed] @12-22; FunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @24-35; FunctionExpression; parameters=1; async=false; generator=false
- module.exports @42-48; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/census-display.js

Blob: `59a9d9ca5c8c8984c2c9cbe0390aaeff6ee22c7f`. Role: source. Parse: module.

- handlers.[computed] @14-16; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @18-24; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/diffing.js

Blob: `f017276ff23bef07c811ae7331b0c741e66a3243`. Role: source. Parse: module.

- handlers.[computed] @21-28; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @30-42; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @44-79; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @81-101; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @103-125; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @127-132; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @134-148; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @150-164; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @166-171; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @173-176; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/errors.js

Blob: `ad1c8bd62169ec4f52bd63ceb9dfdc800754f32c`. Role: source. Parse: module.

- module.exports @15-21; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/filter.js

Blob: `3a1ad7d8cbf5245206d39361388dc9375847624d`. Role: source. Parse: module.

- filterReducer @8-14; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/front.js

Blob: `92ff6c151c070c71a202d92c721c0cf813c26b9e`. Role: source. Parse: module.

- module.exports @9-11; ArrowFunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/individuals.js

Blob: `57b096f870dfa2494b518a639d19923af2a7f33e`. Role: source. Parse: module.

- handlers.[computed] @18-20; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @22-34; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @36-39; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @41-47; FunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @49-71; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @73-79; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @81-84; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/label-display.js

Blob: `678930a91a00075d69014aa867f19128a9af662e`. Role: source. Parse: module.

- handlers.[computed] @15-17; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @19-22; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/sizes.js

Blob: `f79e9f6b28e02bf20d39b1660600fe5a99473530`. Role: source. Parse: module.

- handlers.[computed] @13-15; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @17-20; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/snapshots.js

Blob: `d510a169c93466085438cf5c6379423c49038523`. Role: source. Parse: module.

- handlers.[computed] @22-28; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @30-32; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @34-40; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @35-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @44-50; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @45-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @52-61; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @56-60; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @63-79; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @74-78; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @81-99; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @94-98; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @101-116; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @104-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @118-130; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @125-129; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @132-145; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @140-144; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @147-162; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @150-161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @164-179; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @165-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @181-196; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @182-195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @198-208; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @199-207; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @210-212; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @211-211; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @214-216; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @215-215; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @218-220; FunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @222-226; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @224-224; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @228-234; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @229-232; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @236-251; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @243-250; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @253-274; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @257-273; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @276-300; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @280-299; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @302-347; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @306-346; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findFocused @319-335; FunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @349-369; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @353-368; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @371-391; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @375-390; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @393-408; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @397-407; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @410-439; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @414-438; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @441-495; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @445-494; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlers.[computed] @497-512; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @500-511; ArrowFunctionExpression; parameters=1; async=false; generator=false
- module.exports @514-520; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/tree-map-display.js

Blob: `7f145e818191ac1421a7a6404c436ae7dafb6a9e`. Role: source. Parse: module.

- handlers.[computed] @15-17; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @19-22; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/reducers/view.js

Blob: `99dab7ef0370085005a0383bdc3b8ae839ebef6d`. Role: source. Parse: module.

- handlers.[computed] @14-20; FunctionExpression; parameters=2; async=false; generator=false
- handlers.[computed] @22-42; FunctionExpression; parameters=2; async=false; generator=false
- module.exports @49-52; FunctionExpression; parameters=2; async=false; generator=false

### devtools/client/memory/store.js

Blob: `9739ca0fd57f87653666fbe1d59a96c68cb7bcd6`. Role: source. Parse: module.

- module.exports @10-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_allocationStackDisplay_01.js

Blob: `e145732b7ab5aed927cea344ad0df94d05a5eb98`. Role: test-path,source. Parse: module.

- (anonymous) @23-52; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_allocationStackDisplay_02.js

Blob: `b9c80c394c308e59b08a0fb1a3e5824855a489d3`. Role: test-path,source. Parse: module.

- (anonymous) @23-51; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_clear_snapshots.js

Blob: `333459cc3e551b01d02c025b8e3eac41589c104d`. Role: test-path,source. Parse: module.

- (anonymous) @16-78; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @32-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-61; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_diff_01.js

Blob: `638586f667cb3be8e6acde04579ecea4367e1a4f`. Role: test-path,source. Parse: module.

- (anonymous) @16-86; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @41-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-58; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_displays_01.js

Blob: `7e9561796d5cf91c35fe7b490f0925f0e6f25076`. Role: test-path,source. Parse: module.

- (anonymous) @16-49; FunctionExpression; parameters=1; async=true; generator=false
- $$ @21-23; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @30-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findNameCell @43-48; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_dominator_trees_01.js

Blob: `374d1d65baa18408b149048287c920315f155ebd`. Role: test-path,source. Parse: module.

- (anonymous) @23-184; FunctionExpression; parameters=1; async=true; generator=false
- expandAllEagerlyFetched @48-58; FunctionExpression; parameters=1; async=false; generator=false
- findDeepest @63-78; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @95-95; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @108-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @127-128; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findNewDeepest @141-158; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @176-176; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_dominator_trees_02.js

Blob: `fea3603c526f9eb3b4eece08a06d7ba92dd1f997`. Role: test-path,source. Parse: module.

- clickOnNodeArrow @19-25; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @27-81; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @44-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @75-78; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_filter_01.js

Blob: `7f2e39ac2086479078a1fff98a056f0084bf98c7`. Role: test-path,source. Parse: module.

- (anonymous) @20-107; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @33-36; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @87-90; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_fission_switch_target.js

Blob: `5d0d474d7632df41ced65eba2494dd5c164a65f0`. Role: test-path,source. Parse: module.

- (anonymous) @17-52; ArrowFunctionExpression; parameters=0; async=true; generator=false
- takeAndWaitSnapshot @54-72; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @55-71; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getNodeNames @74-79; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_individuals_01.js

Blob: `7be5fb2ac446a1f0fc28c6a02c23e0018115bcd2`. Role: test-path,source. Parse: module.

- (anonymous) @20-74; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @32-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @66-68; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_keyboard-snapshot-list.js

Blob: `7a2e2e12f79ae7d874dac9372a3b1fbef76a5e1d`. Role: test-path,source. Parse: module.

- (anonymous) @19-112; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @39-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @75-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @85-87; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @96-98; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_keyboard.js

Blob: `642eacd43c1cdff777135adacf673faa42c9a01f`. Role: test-path,source. Parse: module.

- waitUntilFocused @20-30; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @23-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitUntilExpanded @32-40; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @35-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-111; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/browser_memory_no_allocation_stacks.js

Blob: `086bc77ef549308b17947551bb1a483ee103d4de`. Role: test-path,source. Parse: module.

- (anonymous) @20-54; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/browser_memory_no_auto_expand.js

Blob: `f4e9800f2837aefe7829f45c85055b504fac94b3`. Role: test-path,source. Parse: module.

- (anonymous) @20-49; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/browser_memory_percents_01.js

Blob: `8e9202b705f9fe8077f38beb66527caefe697397`. Role: test-path,source. Parse: module.

- checkCells @19-30; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @32-62; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/browser_memory_refresh_does_not_leak.js

Blob: `c44eb0652890829409c87837b755897a972eaa9b`. Role: test-path,source. Parse: module.

- getWindowsInSnapshot @21-36; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @56-139; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @106-106; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_simple_01.js

Blob: `acafb46ca19b0e77d77cf3dfea6d0be7dabc9763`. Role: test-path,source. Parse: module.

- (anonymous) @17-60; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_transferHeapSnapshot_e10s_01.js

Blob: `169a968653682417b580cb66424c2f5c7eda6942`. Role: test-path,source. Parse: module.

- (anonymous) @14-34; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/browser_memory_tree_map-01.js

Blob: `97e69f6f6d2c3091b7d841c162ff1a8a5fa6d133`. Role: test-path,source. Parse: module.

- (anonymous) @15-136; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @58-60; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/test/browser/browser_memory_tree_map-02.js

Blob: `f48bb66c13ca60ae9b7bfd9f6bacee1e92e341f1`. Role: test-path,source. Parse: module.

- (anonymous) @17-199; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/memory/test/browser/head.js

Blob: `a85a08b0a2ebc1377a7ae2c15591727872720d34`. Role: test-path,source. Parse: module.

- ?.openMemoryPanel @24-30; FunctionExpression; parameters=1; async=true; generator=false
- ?.closeMemoryPanel @35-40; FunctionExpression; parameters=1; async=true; generator=false
- makeMemoryTest @53-75; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @54-74; FunctionExpression; parameters=0; async=true; generator=false
- dumpn @77-79; FunctionDeclaration; parameters=1; async=false; generator=false
- waitUntilDominatorTreeState @92-107; FunctionDeclaration; parameters=2; async=false; generator=false
- predicate @93-104; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-102; ArrowFunctionExpression; parameters=2; async=false; generator=false
- takeSnapshot @109-118; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clearSnapshots @120-128; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @123-126; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @126-126; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setCensusDisplay @134-156; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @147-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @148-148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getDisplayedSnapshotStatus @164-167; FunctionDeclaration; parameters=1; async=false; generator=false
- getSelectedSnapshotIndex @174-178; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @176-176; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitUntilSnapshotSelected @186-193; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @189-191; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitUntilCensusState @200-223; FunctionDeclaration; parameters=3; async=false; generator=false
- predicate @201-220; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @206-206; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @211-218; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createRAFMock @236-253; FunctionDeclaration; parameters=0; async=false; generator=false
- mock.nextFrame @240-246; FunctionExpression; parameters=0; async=false; generator=false
- mock.raf @248-251; FunctionExpression; parameters=1; async=false; generator=false
- floatEquality @262-269; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/memory/test/chrome/head.js

Blob: `26e4457ab20fb4c97b5c295f40d7c00e4679c99d`. Role: test-path,source. Parse: module.

- (anonymous) @19-32; FunctionExpression; parameters=0; async=false; generator=false
- noop @87-87; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getPercentBytes @109-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getPercentCount @110-110; ArrowFunctionExpression; parameters=0; async=false; generator=false
- makeTestDominatorTreeNode @128-154; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @137-137; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @148-150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- makeTree @158-168; FunctionExpression; parameters=1; async=false; generator=false
- makeTestCensusNode @280-289; FunctionDeclaration; parameters=0; async=false; generator=false
- onNextAnimationFrame @329-331; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @330-330; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @330-330; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderComponent @338-349; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @339-348; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @343-346; ArrowFunctionExpression; parameters=0; async=false; generator=false
- dumpn @351-353; FunctionDeclaration; parameters=1; async=false; generator=false
- Module resource://devtools/shared/loader/browser-loader.sys.mjs @6; ChromeUtils-import-literal
- Module resource://testing-common/Assert.sys.mjs @13; ChromeUtils-import-literal

### devtools/client/memory/test/xpcshell/head.js

Blob: `1c935b52c8a7b0efacbef3dccf9dc7f06d9c7e6f`. Role: test-path,source. Parse: module.

- (anonymous) @12-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-41; FunctionExpression; parameters=0; async=false; generator=false
- dumpn @43-45; FunctionDeclaration; parameters=1; async=false; generator=false
- initDebugger @47-51; FunctionDeclaration; parameters=0; async=false; generator=false
- StubbedMemoryFront @53-56; FunctionDeclaration; parameters=0; async=false; generator=false
- StubbedMemoryFront.prototype.attach @58-60; FunctionExpression; parameters=0; async=true; generator=false
- StubbedMemoryFront.prototype.detach @62-64; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-70; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @76-76; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @81-81; FunctionExpression; parameters=0; async=true; generator=false
- waitUntilSnapshotState @84-97; FunctionDeclaration; parameters=2; async=false; generator=false
- predicate @85-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-87; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=2; async=false; generator=false
- findReportLeafIndex @99-114; FunctionDeclaration; parameters=2; async=false; generator=false
- waitUntilCensusState @116-139; FunctionDeclaration; parameters=3; async=false; generator=false
- predicate @117-136; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @122-122; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @127-134; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createTempFile @141-150; FunctionDeclaration; parameters=0; async=true; generator=false
- waitForDispatch @169-191; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @171-190; ArrowFunctionExpression; parameters=1; async=false; generator=false
- predicate @174-185; ArrowFunctionExpression; parameters=1; async=false; generator=false
- run @186-188; ArrowFunctionExpression; parameters=3; async=false; generator=false
- Module resource://gre/modules/FileUtils.sys.mjs @18; ChromeUtils-import-literal
- Module moz-src:///devtools/platform/jsdebugger.sys.mjs @24; ChromeUtils-import-literal

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_01.js

Blob: `9511ba413fcd431f05e7a6d9cff03f9a8fdffd0e`. Role: test-path,source. Parse: module.

- (anonymous) @17-41; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_02.js

Blob: `09f1fa6b54bebb5d6727be6574f6a707b955df24`. Role: test-path,source. Parse: module.

- (anonymous) @19-61; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_03.js

Blob: `b920c5264bd83e7d882e2fc1103a60b450796520`. Role: test-path,source. Parse: module.

- (anonymous) @18-52; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_04.js

Blob: `723029c90b970c805999e3962806cc0c8de2acc0`. Role: test-path,source. Parse: module.

- (anonymous) @18-55; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_05.js

Blob: `485e0f05139bb5eca264a6176f6e76870dacb140`. Role: test-path,source. Parse: module.

- (anonymous) @17-53; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- deleteHeapSnapshot @34-36; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-clear-snapshots_06.js

Blob: `0fe84daaea1f9bc1c47e999b5da45ed250f88ffa`. Role: test-path,source. Parse: module.

- (anonymous) @21-68; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-export-snapshot.js

Blob: `c481ab1315f3ca7c3b707951a560a11d4a1fddf6`. Role: test-path,source. Parse: module.

- (anonymous) @19-45; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-filter-01.js

Blob: `b16e66a62c78baf1c7470bd46204567a0fdbf48d`. Role: test-path,source. Parse: module.

- (anonymous) @12-23; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/memory/test/xpcshell/test_action-filter-02.js

Blob: `828b976aa31564e12c99424c90632ea45eb73aab`. Role: test-path,source. Parse: module.

- (anonymous) @23-88; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-filter-03.js

Blob: `2fcc3e9156b548be233ee5b9e3a5703f8c58903b`. Role: test-path,source. Parse: module.

- (anonymous) @25-69; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-import-snapshot-and-census.js

Blob: `3e97f7c45f75d0b3675875073e1d821682e2867c`. Role: test-path,source. Parse: module.

- (anonymous) @24-135; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- expectStates @47-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- stripUnique @124-134; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-import-snapshot-dominator-tree.js

Blob: `3c11268e94f86af7f448dc1039b87949d5f9d19f`. Role: test-path,source. Parse: module.

- (anonymous) @25-76; FunctionExpression; parameters=0; async=true; generator=false
- expectStates @50-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- hasExpectedState @84-100; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-select-snapshot.js

Blob: `f4abac423bb2e3b822f526e08ff9b8fe42537cbc`. Role: test-path,source. Parse: module.

- (anonymous) @15-42; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isDone @44-46; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-set-display-and-refresh-01.js

Blob: `6f1332c3398ca13dec1d76dcadf7b52996503336`. Role: test-path,source. Parse: module.

- (anonymous) @32-186; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @63-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @86-86; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @112-112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @128-128; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @132-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @146-146; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @166-166; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @171-171; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-set-display-and-refresh-02.js

Blob: `2b2b91bc972ea1001fc38d3c30fe811668796680`. Role: test-path,source. Parse: module.

- (anonymous) @35-74; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @70-70; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-set-display.js

Blob: `dfc14f609a5066d82a48c5026d42ef64ae145a6e`. Role: test-path,source. Parse: module.

- (anonymous) @30-74; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-take-census.js

Blob: `005208024bb407e1e08835c0eccf641a42bfacc7`. Role: test-path,source. Parse: module.

- (anonymous) @25-70; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @34-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @60-60; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-take-snapshot-and-census.js

Blob: `ce7d166aca445d4686393686037d74e2093c6e35`. Role: test-path,source. Parse: module.

- (anonymous) @17-65; FunctionExpression; parameters=0; async=true; generator=false
- expectStates @27-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-55; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-take-snapshot.js

Blob: `e8bd46898c3aceb6061a4bcc17b3fa5354cbb712`. Role: test-path,source. Parse: module.

- (anonymous) @15-61; FunctionExpression; parameters=0; async=true; generator=false
- checkState @25-50; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-toggle-inverted-and-refresh-01.js

Blob: `6744390ecd98f15f02c9a9443c8792e3b36d755e`. Role: test-path,source. Parse: module.

- (anonymous) @25-98; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @86-86; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/memory/test/xpcshell/test_action-toggle-inverted-and-refresh-02.js

Blob: `7047f6410ec1867730458196dca93f7f6def39b6`. Role: test-path,source. Parse: module.

- (anonymous) @26-82; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-63; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [52efd019-3d6d-43a4-9d7f-335d9470a6eb.md](52efd019-3d6d-43a4-9d7f-335d9470a6eb.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `9a35b5aeae6a69046113168fae29a18badfeed2284cc85a3dc7f13a4e16fabf6`.
