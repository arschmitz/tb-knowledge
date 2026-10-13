<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["296aef255db319c37b12617bde1360ec09a950850daf502be94e29b9034f631c"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/daaa8aea-d250-4143-a81d-35806f7921dd.md"}} -->
# firefox/testing JavaScript function map 773

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/cookies/set-and-delete-document-cookie.window.js

Blob: `5dcd12ba5cc771be187c5e468ed9c6df3a5b37c3`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/cookies/third-party-cookies/resources/test-helpers.js

Blob: `c76ac716161ae0f0a4ba2f697fc66433c2c60d13`. Role: test-path,source. Parse: module.

- testHttpCookies @1-5; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-4; ArrowFunctionExpression; parameters=0; async=true; generator=false
- assertHttpOriginCanAccessCookies @7-19; FunctionDeclaration; parameters=1; async=true; generator=false
- assertThirdPartyHttpCookies @21-42; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @31-41; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testDomCookies @44-48; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @45-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertDomCanAccessCookie @50-56; FunctionDeclaration; parameters=2; async=false; generator=false
- testCookieStoreCookies @58-63; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=0; async=true; generator=false
- assertCookieStoreCanAccessCookies @65-72; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getCookieTestName @74-79; FunctionDeclaration; parameters=3; async=false; generator=false
- getCookieAssertDesc @81-86; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/cookies/value/value-overwrite.https.window.js

Blob: `799e2c8082f9a4b947d43c778ac620199b650480`. Role: test-path,source. Parse: module.

- setCookiesViaHTTP @15-19; FunctionDeclaration; parameters=1; async=true; generator=false
- getCookiesViaHTTP @23-27; FunctionDeclaration; parameters=0; async=true; generator=false
- cookieValue @29-37; FunctionDeclaration; parameters=2; async=false; generator=false
- overwriteTest @44-58; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @45-57; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @115-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-123; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @117-117; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_already_expired.https.window.js

Blob: `f3bbe0ea560974e9486941384e75a58d2d6a4637`. Role: test-path,source. Parse: module.

- (anonymous) @6-22; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @24-41; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_attribute_change.https.window.js

Blob: `611d19113f107601e0adaf71d803dc1855daad12`. Role: test-path,source. Parse: module.

- (anonymous) @16-32; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @34-42; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @45-53; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @57-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @71-83; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_document_cookie.https.window.js

Blob: `1937ebdae35942840dc3b641b5907f334048f3fb`. Role: test-path,source. Parse: module.

- (anonymous) @6-64; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @67-79; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @81-95; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @97-151; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @154-176; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @179-191; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_http_cookie_and_set_cookie_headers.https.window.js

Blob: `8517995acfe746bbff09243597d6d319e3af1bc2`. Role: test-path,source. Parse: module.

- (anonymous) @6-48; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @51-63; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @65-79; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @82-103; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @106-151; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @154-166; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @169-237; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_no_change.https.window.js

Blob: `5f9c2927433fc408c70c005789dc0bcc34d46caa`. Role: test-path,source. Parse: module.

- (anonymous) @6-19; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @21-43; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_no_name_and_no_value.https.window.js

Blob: `4498caf59689cc3da875d1c56937f6d2a235cb5d`. Role: test-path,source. Parse: module.

- (anonymous) @6-58; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_no_name_equals_in_value.https.window.js

Blob: `13d721786c9a140b05ed5291c6096c894053f78b`. Role: test-path,source. Parse: module.

- (anonymous) @6-45; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/change_eventhandler_for_no_name_multiple_values.https.window.js

Blob: `60c6c16518ae767d2dab68e62af8967b9890072b`. Role: test-path,source. Parse: module.

- (anonymous) @6-41; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieListItem_attributes.https.any.js

Blob: `9dd832624bb4f5f787c6b6c3b4f7dca492e4e21f`. Role: test-path,source. Parse: module.

- assert_cookie_keys @19-22; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @24-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-49; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @42-44; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @51-63; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @56-58; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-78; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @71-73; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @81-93; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @86-88; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @95-111; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @104-106; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @113-128; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @121-123; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @130-145; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @131-143; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @136-138; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieListItem_attributes.https.window.js

Blob: `9f4aa5e3c00db9d58209de5399d228cb8d4a70df`. Role: test-path,source. Parse: module.

- assert_cookie_keys @17-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @22-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-67; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @50-52; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @69-84; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @74-76; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @87-102; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @92-94; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @105-120; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @110-112; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @122-141; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @131-133; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @143-161; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @151-153; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @163-181; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @164-179; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @169-171; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @183-201; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @185-187; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStoreManager_getSubscriptions_empty.https.any.js

Blob: `8cfd732f304509582ff8c9be97e8e90e6c06e8ed`. Role: test-path,source. Parse: module.

- (anonymous) @7-28; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStoreManager_getSubscriptions_multiple.https.any.js

Blob: `e2538013c93220ec79c08bee4d79c07a0b342620`. Role: test-path,source. Parse: module.

- CompareStrings @12-14; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @16-77; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @70-70; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStoreManager_getSubscriptions_single.https.any.js

Blob: `4f1053266043636e7ed2c004f2942ae3fac9164b`. Role: test-path,source. Parse: module.

- (anonymous) @7-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-41; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_delete_arguments.https.any.js

Blob: `757eef7ade4bcc7b4df05ee2dc87a929fd9a51d3`. Role: test-path,source. Parse: module.

- (anonymous) @8-16; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @10-12; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-27; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @38-41; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @43-55; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-50; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @57-64; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @66-75; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @78-93; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @85-88; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @95-112; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @103-106; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @114-128; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @120-123; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @130-147; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @140-143; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-158; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @160-173; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @162-164; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @175-184; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @177-179; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @186-195; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @188-190; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @197-207; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @200-202; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @209-222; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @224-231; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @226-228; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_delete_basic.https.any.js

Blob: `08a1fac5afe1ed5c2713e60674fadc3d0be7e620`. Role: test-path,source. Parse: module.

- (anonymous) @6-13; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_event_arguments.https.window.js

Blob: `bcb698eeb0d6ce760033ba628120ebf7772a1084`. Role: test-path,source. Parse: module.

- (anonymous) @3-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-65; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_event_basic.https.window.js

Blob: `c0075d6adcdd9a3438dfd3df622bf35883bf4110`. Role: test-path,source. Parse: module.

- (anonymous) @3-24; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @4-6; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_event_delete.https.window.js

Blob: `d0fee1ab1d03cd3835f3b9e5828d4aef7eb45710`. Role: test-path,source. Parse: module.

- (anonymous) @3-39; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @4-6; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @41-75; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @42-44; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cookieStore.onchange @48-55; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_event_overwrite.https.window.js

Blob: `427e7dcbb7ce0ff1627a2f45a2a407d1c0189dc3`. Role: test-path,source. Parse: module.

- (anonymous) @3-37; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @4-6; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @11-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-26; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_getAll_arguments.https.any.js

Blob: `fecd2945a877124ff99222092e58fd7e9ea95746`. Role: test-path,source. Parse: module.

- (anonymous) @6-23; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @25-42; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @27-29; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @44-58; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-48; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @50-52; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @60-74; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @62-64; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-68; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @76-91; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @78-80; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @82-84; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @93-108; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @95-97; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @110-125; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @112-114; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @128-133; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @135-147; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @137-139; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @150-160; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @152-154; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @162-179; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @164-166; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @181-196; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @184-186; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @198-207; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @200-202; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_getAll_multiple.https.any.js

Blob: `10dcacbd688d6c23364e3e8e1b946196cd0b4387`. Role: test-path,source. Parse: module.

- (anonymous) @6-29; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @16-18; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_getAll_set_basic.https.any.js

Blob: `dee78e1867c7e0be04e779b4bfd949250540c289`. Role: test-path,source. Parse: module.

- (anonymous) @6-16; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_getAll_set_creation_url.https.any.js

Blob: `d09c4aad4f87712afd70faf8111ee21f88d5f1a8`. Role: test-path,source. Parse: module.

- (anonymous) @6-33; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @16-18; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_get_arguments.https.any.js

Blob: `a6bbc1a2f152d46b24ad0bf36af0b0bdd2c3050c`. Role: test-path,source. Parse: module.

- (anonymous) @6-13; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-22; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @17-19; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-33; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @37-39; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-56; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-50; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @58-72; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @74-88; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @76-78; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @91-96; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @98-102; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @105-110; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @112-128; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @114-116; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @130-144; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @133-135; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @146-154; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @148-150; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_get_delete_basic.https.any.js

Blob: `9337669afd5b61d821e9945bd2f3299d8afb8bad`. Role: test-path,source. Parse: module.

- (anonymous) @6-14; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_get_set_basic.https.any.js

Blob: `127f758f5f0b8154dccc74f2b6e81d3b0d2562a9`. Role: test-path,source. Parse: module.

- (anonymous) @6-15; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-10; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_get_set_creation_url.https.any.js

Blob: `71f8108095f0e78518f73f5086eb0d2d4dee1253`. Role: test-path,source. Parse: module.

- (anonymous) @6-32; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @16-18; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_get_set_ordering.https.any.js

Blob: `fe564e55fc4a6d9111a1be35888a750d5ccba9ac`. Role: test-path,source. Parse: module.

- (anonymous) @6-25; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @7-11; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-52; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @29-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_set_arguments.https.any.js

Blob: `fe1d1451b13dde4f2cf3221049505984b4daeda8`. Role: test-path,source. Parse: module.

- (anonymous) @7-18; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @11-13; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @20-30; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @24-26; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-35; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @37-40; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @42-51; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @45-47; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @67-72; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @75-90; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @84-86; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-106; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @101-103; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @108-121; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @115-117; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @123-135; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @130-132; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @137-145; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @147-150; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @152-165; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @159-161; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @167-176; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @178-189; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @192-216; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @198-200; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @203-205; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @213-213; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @218-233; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @227-229; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @235-251; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @246-248; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @253-271; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @257-259; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @263-265; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @273-287; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @281-283; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @289-309; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @301-304; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @311-320; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @322-337; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @324-326; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @339-349; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @351-361; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @363-376; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @378-390; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @392-418; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_set_limit.https.any.js

Blob: `0bd9ceec08d55308fba01e46270d6b16e0b35043`. Role: test-path,source. Parse: module.

- cookieParamsWithNameAndValueLengths @6-8; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @58-68; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_set_maxAge.https.window.js

Blob: `eb9b6d2069f442dd812b9a0364b818d787240796`. Role: test-path,source. Parse: module.

- (anonymous) @4-15; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @17-27; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @29-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-57; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_set_path.https.window.js

Blob: `0222f8aaf0d98c67a587e81321776b41f343b315`. Role: test-path,source. Parse: module.

- (anonymous) @5-17; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @11-13; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-23; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @25-46; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-30; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_special_names.https.any.js

Blob: `7431609df6e4d40d2b752ea67567e8914dbe34e4`. Role: test-path,source. Parse: module.

- (anonymous) @6-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7-15; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @17-26; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-32; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @35-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-42; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @44-56; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @60-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-64; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @67-76; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @79-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @80-93; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_subscribe_arguments.https.any.js

Blob: `098f80dd825904820476f57cc6605194807db2aa`. Role: test-path,source. Parse: module.

- (anonymous) @7-37; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-66; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @60-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-90; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-83; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @92-122; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @124-159; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @129-129; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @139-139; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @147-147; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/cookieStore_subscriptions_empty.https.window.js

Blob: `907a34b4de6632f5e91adbcd606839a92eead320`. Role: test-path,source. Parse: module.

- (anonymous) @5-13; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/encoding.https.any.js

Blob: `f5d2ca15e717a0837f1e08031ab682db5aa965ea`. Role: test-path,source. Parse: module.

- (anonymous) @7-15; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-25; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @19-21; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/httponly_cookies.https.window.js

Blob: `836f47da3f6e0f8f2c89445d1b2fbdfdf9ddc9e6`. Role: test-path,source. Parse: module.

- (anonymous) @5-53; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @32-34; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-49; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @56-63; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @67-75; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @77-108; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @79-81; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/idlharness.https.any.js

Blob: `2ffa714420bfc11161f2c59dc54b568e43afd214`. Role: test-path,source. Parse: module.

- (anonymous) @13-44; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/resources/always_changing_sw.sub.js

Blob: `9fdf99848fa50316e275cd6636a5755270a9bb1e`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/cookiestore/resources/cookie-test-helpers.js

Blob: `ac1edce9ca3845f33f6e291bc81937ce685fff71`. Role: test-path,source. Parse: module.

- getCookieString @23-29; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @26-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getCookieStringHttp @37-57; FunctionDeclaration; parameters=1; async=true; generator=false
- getCookieBinaryHttp @65-88; FunctionDeclaration; parameters=1; async=true; generator=false
- setCookieStringHttp @92-121; FunctionDeclaration; parameters=1; async=true; generator=false
- setCookieBinaryHttp @126-153; FunctionDeclaration; parameters=1; async=true; generator=false
- getCookieStringDocument @158-162; FunctionDeclaration; parameters=0; async=true; generator=false
- setCookieStringDocument @165-169; FunctionDeclaration; parameters=1; async=true; generator=false
- observeNextCookieChangeEvent @178-184; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @181-183; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @182-182; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyCookieChangeEvent @186-206; FunctionDeclaration; parameters=3; async=true; generator=false
- cookie_test @211-231; FunctionDeclaration; parameters=2; async=true; generator=false
- deleteAllCookies @214-221; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @217-220; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @223-230; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/resources/empty_sw.js

Blob: `2b0ae226121503789d63d405670becb09e51b833`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/cookiestore/resources/helpers.js

Blob: `8d5dddef6577fc534a68c9e8415854e4c64901fd`. Role: test-path,source. Parse: module.

- self.createIframe @8-14; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @8-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- self.createServiceWorker @24-42; ArrowFunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.waitForMessage @48-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.sendMessageOverChannel @59-72; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @60-71; FunctionExpression; parameters=2; async=false; generator=false
- messageChannel.port1.onmessage @62-68; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookieStore_cross_origin.js

Blob: `ac59b703dd75656adb7ad248a4826ef0983a3c4c`. Role: test-path,source. Parse: module.

- isWindow @2-2; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isWorker @3-3; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-13; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_already_expired.https.any.js

Blob: `4ccf245e1ca583cbd47361fcfed5994916a6dae2`. Role: test-path,source. Parse: module.

- WorkerActivationPromise @8-16; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @9-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- RunOnceCookieChangeReceivedPromise @18-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @19-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @20-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-52; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-86; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-78; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_mismatched_subscription.https.any.js

Blob: `1dfd6a2177c1875e1dc6bfc39e0bd00823d44d34`. Role: test-path,source. Parse: module.

- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-34; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_multiple_subscriptions.https.any.js

Blob: `bc7199e7d366640a5d2765642f27cf825c5d082c`. Role: test-path,source. Parse: module.

- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- RearmCookieChangeReceivedPromise @25-29; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-67; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-53; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_no_change.https.any.js

Blob: `fbbeeda4031c67b3d1a905cca27829e7486aef12`. Role: test-path,source. Parse: module.

- WorkerActivationPromise @9-17; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @10-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- RunOnceCookieChangeReceivedPromise @20-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @22-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-61; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @71-128; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @85-90; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-120; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_overlapping_subscriptions.https.any.js

Blob: `9ed65c73a816b7f0036dbf587f276c687d8498d4`. Role: test-path,source. Parse: module.

- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- RearmCookieChangeReceivedPromise @25-29; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-84; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-46; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-58; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_cookiechange_eventhandler_single_subscription.https.any.js

Blob: `a9db40dd544904fe99e0a92083918c889746be98`. Role: test-path,source. Parse: module.

- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-38; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/cookiestore/serviceworker_oncookiechange_eventhandler_single_subscription.https.any.js

Blob: `24b91706cb3c22766b5a269e2bff667f9f18320c`. Role: test-path,source. Parse: module.

- (anonymous) @9-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- self.oncookiechange @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-38; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/core-aam/arianotify/resources/aria-notify-helpers.js

Blob: `c1b3a535fbc0bc618609904b1b8c3912eb229d3b`. Role: test-path,source. Parse: module.

- tryCallAriaNotify @2-9; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/cors/access-control-expose-headers-parsing.window.js

Blob: `a139ff6f1e71d3839c167f5ee8fa77d026fd2ca5`. Role: test-path,source. Parse: module.

- (anonymous) @1-1; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1-1; ArrowFunctionExpression; parameters=1; async=false; generator=false
- runTests @3-15; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4-14; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @9-12; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cors/cors-safelisted-request-header.any.js

Blob: `e840990fb2db2b367fa148ed499c456901384368`. Role: test-path,source. Parse: module.

- safelist @7-23; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8-22; ArrowFunctionExpression; parameters=1; async=true; generator=false
- request @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @80-82; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cors/preflight-cache-partitioning.sub.window.js

Blob: `6b37a843c40fbafa2d2fb855c007fc1999b98360`. Role: test-path,source. Parse: module.

- (anonymous) @8-42; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @21-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- window.onmessage @22-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- window.onmessage @34-37; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/cors/support.js

Blob: `2dde95d9a07be7c8682d6743efa837ac2b120923`. Role: test-path,source. Parse: failed.

Failure: Unexpected token {


### testing/web-platform/tests/cpu-performance/cpu-performance.https.window.js

Blob: `9814bd7209175dcf2b1effc0723013cc137c9130`. Role: test-path,source. Parse: module.

- (anonymous) @1-8; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/credential-management/idlharness.https.window.js

Blob: `26d7c493b045399871fa9b941e0e5a03208d2454`. Role: test-path,source. Parse: module.

- (anonymous) @12-36; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/credential-management/support/origin-bound-report.js

Blob: `4d0c7cd183631b2a21ff59ca9cd619c772544c47`. Role: test-path,source. Parse: module.

- (anonymous) @4-62; ArrowFunctionExpression; parameters=0; async=true; generator=false
- post @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- operation @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- operation @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- operation @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/credential-management/support/otpcredential-helper.js

Blob: `e07e9f5be359e9173b6c916d91d8ce1f87260885`. Role: test-path,source. Parse: module.

- handleNextOTPRequest @36-36; FunctionExpression; parameters=1; async=true; generator=false
- createBrowserSpecificMockImpl @43-48; FunctionDeclaration; parameters=0; async=true; generator=false
- expectOTPRequest @52-59; FunctionDeclaration; parameters=0; async=false; generator=false
- andReturn @54-57; FunctionExpression; parameters=1; async=true; generator=false
- createChromiumMockImpl @64-113; FunctionDeclaration; parameters=0; async=true; generator=false
- constructor @68-79; FunctionExpression; parameters=0; async=false; generator=false
- ?.interceptor_.oninterfacerequest @73-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleNextOTPRequest @81-83; FunctionExpression; parameters=1; async=false; generator=false
- receive @85-108; FunctionExpression; parameters=0; async=true; generator=false
- abort @110-110; FunctionExpression; parameters=0; async=true; generator=false
- Class (anonymous) @67-111
- Class MockWebOTPService @25-37
- Module /resources/test-only-api.m.js @9; ImportDeclaration
- Module /gen/third_party/blink/public/mojom/sms/webotp_service.mojom.m.js @65; dynamic-import-literal

### testing/web-platform/tests/css/compositing/support/plus-lighter.js

Blob: `a5d1a34d7ff9afc19a4bdc2bde26a0c794a01cd5`. Role: test-path,source. Parse: module.

- plusLighter @3-14; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @6-13; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @9-10; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Module ./utils.js @1; ImportDeclaration

### testing/web-platform/tests/css/compositing/support/utils.js

Blob: `eb369ce2e58f0a25e1ff543b2ed53e2e2ac99b06`. Role: test-path,source. Parse: module.

- multiplyAlpha @1-8; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-7; ArrowFunctionExpression; parameters=2; async=false; generator=false
- unmultiplyAlpha @10-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @11-18; ArrowFunctionExpression; parameters=2; async=false; generator=false
- clamp01 @21-25; FunctionDeclaration; parameters=1; async=false; generator=false
- toPercent @27-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toCSSColor @28-31; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-align/resources/alignment-parsing-utils.js

Blob: `d26d3f4da78914301dc945ea6029b6877877fcae`. Role: test-path,source. Parse: module.

- checkPlaceShorthand @27-61; FunctionDeclaration; parameters=6; async=false; generator=false
- checkPlaceShorthandLonghands @63-78; FunctionDeclaration; parameters=5; async=false; generator=false
- checkPlaceShorthandInvalidValues @80-90; FunctionDeclaration; parameters=4; async=false; generator=false
- checkValues @92-98; FunctionDeclaration; parameters=5; async=false; generator=false
- checkBadValues @100-107; FunctionDeclaration; parameters=4; async=false; generator=false
- checkInitialValues @109-115; FunctionDeclaration; parameters=5; async=false; generator=false
- checkInheritValues @117-128; FunctionDeclaration; parameters=3; async=false; generator=false
- checkLegacyValues @130-140; FunctionDeclaration; parameters=3; async=false; generator=false
- checkSupportedValues @142-147; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-anchor-position/support/test-common.js

Blob: `d5cf1861c112b0ae8ec2bfb28b9aa893128ca14b`. Role: test-path,source. Parse: module.

- assert_fallback_position @3-23; FunctionDeclaration; parameters=3; async=false; generator=false
- waitUntilNextAnimationFrame @25-27; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- window.checkLayoutForAnchorPos @36-44; FunctionExpression; parameters=2; async=true; generator=false

### testing/web-platform/tests/css/css-animations/animationevent-interface.js

Blob: `37fa4cd282bdda668091054765ecca06a7447270`. Role: test-path,source. Parse: module.

- (anonymous) @1-230; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2-5; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7-10; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-31; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-57; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @59-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @65-69; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-74; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @81-84; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-89; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-94; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-99; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @101-104; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-114; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @116-119; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @121-125; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @123-123; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-130; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @132-135; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-140; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @142-145; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @147-150; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-155; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @157-160; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @162-165; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @167-170; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @172-176; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @174-174; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @178-182; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @179-181; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @184-188; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @185-187; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @190-194; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @191-193; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @196-200; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @197-199; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @202-206; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-205; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @208-212; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @209-211; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @214-219; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @221-229; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-animations/support/testcommon.js

Blob: `49c9863147ee365aff5c23f852d71856df8ab17c`. Role: test-path,source. Parse: module.

- assert_times_equal @28-30; FunctionDeclaration; parameters=3; async=false; generator=false
- assert_time_equals_literal @35-37; FunctionDeclaration; parameters=3; async=false; generator=false
- assert_frames_equal @42-72; FunctionDeclaration; parameters=3; async=false; generator=false
- assert_frame_lists_equal @77-87; FunctionDeclaration; parameters=2; async=false; generator=false
- addElement @101-113; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addDiv @125-127; FunctionDeclaration; parameters=2; async=false; generator=false
- addStyle @139-155; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @151-153; FunctionExpression; parameters=0; async=false; generator=false
- waitForFrame @160-164; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @161-163; FunctionExpression; parameters=2; async=false; generator=false
- waitForNextFrame @169-180; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @171-179; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @172-178; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForAnimationFrames @189-205; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @191-204; FunctionExpression; parameters=2; async=false; generator=false
- handleFrame @192-202; FunctionDeclaration; parameters=0; async=false; generator=false
- fastEventsTimeout @212-214; FunctionDeclaration; parameters=0; async=false; generator=false
- armTimeoutWhenReady @222-229; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @223-228; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @225-225; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForAllAnimations @236-238; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @237-237; ArrowFunctionExpression; parameters=1; async=false; generator=false
- flushComputedStyle @246-249; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-borders/corner-shape/resources/corner-utils.js

Blob: `3a156436bc3af3c870a00abdc99368afab3dc2cb`. Role: test-path,source. Parse: module.

- offset_for_curvature @6-19; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- superellipse @27-37; FunctionDeclaration; parameters=2; async=false; generator=false
- superellipse_t_for_x @39-43; FunctionDeclaration; parameters=2; async=false; generator=false
- superellipse_t_for_y @45-49; FunctionDeclaration; parameters=2; async=false; generator=false
- adjust_corner_for_spread @51-63; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @57-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- adjust_spread @65-72; FunctionDeclaration; parameters=4; async=false; generator=false
- resolve_corner_params @74-152; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @121-151; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-borders/corner-shape/resources/render-corner-shape.js

Blob: `44714a0d88a2572f8bc0fe5bdeb58a313b570b99`. Role: test-path,source. Parse: module.

- constructor @10-13; FunctionExpression; parameters=2; async=false; generator=false
- scale @19-21; FunctionExpression; parameters=1; async=false; generator=false
- length @26-28; FunctionExpression; parameters=0; async=false; generator=false
- normalized @33-36; FunctionExpression; parameters=0; async=false; generator=false
- perpendicular @41-43; FunctionExpression; parameters=0; async=false; generator=false
- fromPoints @50-52; FunctionExpression; parameters=2; async=false; generator=false
- sum @58-61; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @60-60; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @60-60; ArrowFunctionExpression; parameters=2; async=false; generator=false
- dot @68-70; FunctionExpression; parameters=2; async=false; generator=false
- cross @79-81; FunctionExpression; parameters=2; async=false; generator=false
- extend_point @91-94; FunctionDeclaration; parameters=2; async=false; generator=false
- line_intersection @103-113; FunctionDeclaration; parameters=2; async=false; generator=false
- segment_line_intersection @123-146; FunctionDeclaration; parameters=2; async=false; generator=false
- adjusted_radius_dimension @154-160; FunctionDeclaration; parameters=3; async=false; generator=false
- outset_adjusted_border_radius @170-176; FunctionDeclaration; parameters=5; async=false; generator=false
- normalized_superellipse_half_corner @184-189; FunctionDeclaration; parameters=1; async=false; generator=false
- corner_clip_out_path @203-356; FunctionDeclaration; parameters=9; async=false; generator=false
- clamp @214-216; FunctionDeclaration; parameters=3; async=false; generator=false
- map_point_to_corner @289-293; FunctionDeclaration; parameters=5; async=false; generator=false
- t_arr @295-312; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @311-311; ArrowFunctionExpression; parameters=2; async=false; generator=false
- draw_contoured_path @365-447; FunctionDeclaration; parameters=5; async=false; generator=false
- adjusted_inset @376-379; FunctionDeclaration; parameters=5; async=false; generator=false
- add_corner @410-421; FunctionDeclaration; parameters=1; async=false; generator=false
- render @456-527; FunctionDeclaration; parameters=5; async=false; generator=false
- create_ref_canvas @530-541; FunctionDeclaration; parameters=4; async=false; generator=false
- create_ref @543-551; FunctionDeclaration; parameters=3; async=false; generator=false
- create_actual @553-608; FunctionDeclaration; parameters=3; async=false; generator=false
- create_element_with_corner_shape @626-681; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @670-676; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class Vector2D @1-82

### testing/web-platform/tests/css/css-borders/corner-shape/resources/resolve-corner-style.js

Blob: `a890c57b868e45648eaf097c97163d214a9a1d92`. Role: test-path,source. Parse: module.

- resolve_corner_style @14-56; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @15-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-54; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-conditional/container-queries/support/cq-testcommon.js

Blob: `8d1e03f2073fd2073bdbd0270ec9aa112030e55d`. Role: test-path,source. Parse: module.

- assert_implements_size_container_queries @1-4; FunctionDeclaration; parameters=0; async=false; generator=false
- assert_implements_scroll_state_container_queries @6-9; FunctionDeclaration; parameters=0; async=false; generator=false
- assert_implements_style_container_queries @11-23; FunctionDeclaration; parameters=0; async=false; generator=false
- cleanup_container_query_main @25-29; FunctionDeclaration; parameters=0; async=false; generator=false
- set_container_query_style @31-36; FunctionDeclaration; parameters=1; async=false; generator=false
- test_cq_rule_invalid @38-45; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @40-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_cq_rule_valid @47-54; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @49-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_cq_condition_invalid @56-62; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @57-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_cq_condition_valid @66-77; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @67-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_cq_condition_known @79-81; FunctionDeclaration; parameters=1; async=false; generator=false
- test_cq_condition_unknown @83-85; FunctionDeclaration; parameters=1; async=false; generator=false
- test_container_name_invalid @87-93; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @88-92; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_container_name_valid @95-101; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @96-100; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_cq_condition_serialization @103-110; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @104-109; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-counter-styles/counter-style-at-rule/support/counter-style-testcommon.js

Blob: `a3615e92ff0678d5e7b2aad0a20076cd1ac07d6e`. Role: test-path,source. Parse: module.

- test_counter_style_descriptor @1-45; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @24-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_valid_counter_style_descriptor @47-50; FunctionDeclaration; parameters=3; async=false; generator=false
- test_invalid_counter_style_descriptor @52-54; FunctionDeclaration; parameters=2; async=false; generator=false
- test_counter_style_name @56-74; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @61-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_valid_name @76-78; FunctionDeclaration; parameters=1; async=false; generator=false
- test_invalid_name @80-82; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-display/support/util.js

Blob: `08024b52d5fd82e18fc482888164cbe127239329`. Role: test-path,source. Parse: module.

- eachDisplayContentsElementIn @1-23; FunctionDeclaration; parameters=4; async=false; generator=false

### testing/web-platform/tests/css/css-easing/testcommon.js

Blob: `9fd25b86507258b900911df892540bdb1ae17cd3`. Role: test-path,source. Parse: module.

- createDiv @5-7; FunctionDeclaration; parameters=2; async=false; generator=false
- createElement @12-22; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- pxToNum @25-27; FunctionDeclaration; parameters=1; async=false; generator=false
- cubicBezier @30-65; FunctionDeclaration; parameters=4; async=false; generator=false
- xForT @31-34; FunctionDeclaration; parameters=1; async=false; generator=false
- yForT @36-39; FunctionDeclaration; parameters=1; async=false; generator=false
- tForX @41-54; FunctionDeclaration; parameters=1; async=false; generator=false
- bezierClosure @56-64; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-exclusions/resources/helper.js

Blob: `6cd9ffddc4089463fd7ceb60cb13854c5908a42d`. Role: test-path,source. Parse: module.

- checkLinePos @1-14; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/css/css-flexbox/support/scrollbars.js

Blob: `5b61b499c0fa49b5476339ed625d1687fe85cafc`. Role: test-path,source. Parse: module.

- createLeafNode @5-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createContentNode @14-22; ArrowFunctionExpression; parameters=3; async=false; generator=false
- createContainerNode @24-29; ArrowFunctionExpression; parameters=3; async=false; generator=false
- createContainerRow @31-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-42; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-font-loading/support/fontfaceset-loading-worker.js

Blob: `73579756614c2e5b191c9264a32701f57aade84b`. Role: test-path,source. Parse: module.

- onconnect @1-8; FunctionExpression; parameters=1; async=true; generator=false
- e.ports.[computed].onmessage @2-7; ArrowFunctionExpression; parameters=0; async=true; generator=false

### testing/web-platform/tests/css/css-fonts/support/font-family-keywords.js

Blob: `db30af841097d2b7fe5dcb5e9337c9b8b2444052`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-fonts/support/fonts/gsubtest-features.js

Blob: `52b2e2e24995712e513acc5babb5d68eaeeaad20`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-fonts/support/js/font-variant-features.js

Blob: `4b56fee193956710b847ba79c5f9c3a5a7d15a33`. Role: test-path,source. Parse: module.

- createFeatureTestTable @135-218; FunctionDeclaration; parameters=4; async=false; generator=false

### testing/web-platform/tests/css/css-fonts/support/js/variation-sequences.js

Blob: `84c5a1a9c77932b9b4aedc2be24a38e148bae00d`. Role: test-path,source. Parse: module.

- range @51-53; FunctionExpression; parameters=1; async=false; generator=true
- isEmpty @54-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- permutations @58-67; FunctionExpression; parameters=1; async=false; generator=true
- getMatchedFamilyForVariationSequence @69-92; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @84-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- generateContent @94-112; FunctionDeclaration; parameters=4; async=false; generator=false
- generateVariationSequenceTests @114-119; FunctionDeclaration; parameters=1; async=false; generator=false
- getFontFamilyValue @115-117; ArrowFunctionExpression; parameters=3; async=false; generator=false
- generateVariationSequenceRefs @121-125; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-grid/abspos/support/positioned-grid-descendants.js

Blob: `d45df4bc2231cbda5dee1bafc3f386f008024d79`. Role: test-path,source. Parse: module.

- runTests @13-73; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @70-72; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-grid/alignment/support/style-change.js

Blob: `766d140d2b239bcc0c11e92481c5ff302d12db5c`. Role: test-path,source. Parse: module.

- evaluateStyleChange @1-5; FunctionDeclaration; parameters=4; async=false; generator=false
- evaluateStyleChangeMultiple @6-14; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-grid/grid-definition/support/testing-utils.js

Blob: `ef3282898e645ee32ffb83ece8997e46fa4daccd`. Role: test-path,source. Parse: module.

- (anonymous) @1-61; FunctionExpression; parameters=0; async=false; generator=false
- checkGridTemplateColumns @3-7; FunctionDeclaration; parameters=2; async=false; generator=false
- checkGridTemplateRows @9-13; FunctionDeclaration; parameters=2; async=false; generator=false
- testGridTemplateColumnsRows @15-23; FunctionDeclaration; parameters=6; async=false; generator=false
- (anonymous) @16-22; FunctionExpression; parameters=0; async=false; generator=false
- testGridTemplateColumns @25-31; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @26-30; FunctionExpression; parameters=0; async=false; generator=false
- testGridTemplateRows @33-39; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @34-38; FunctionExpression; parameters=0; async=false; generator=false
- checkGridTemplateAreas @41-45; FunctionDeclaration; parameters=2; async=false; generator=false
- testGridTemplateAreas @47-53; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @48-52; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-grid/support/grid-child-utils.js

Blob: `5e0c5caad12a879e68637b7ba058e44a89eafa01`. Role: test-path,source. Parse: module.

- GridChildHelper @12-16; FunctionDeclaration; parameters=2; async=false; generator=false
- GridChildHelper.prototype.runTest @25-45; FunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-highlight-api/historical.window.js

Blob: `9b735f855dc5b1704d10a5b4916c42b13eec0ed3`. Role: test-path,source. Parse: module.

- (anonymous) @5-7; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-highlight-api/idlharness.window.js

Blob: `7e9f3c44047cc533a4a0d9af1f7839b7e75741c9`. Role: test-path,source. Parse: module.

- (anonymous) @11-16; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-highlight-api/painting/resources/run-after-layout-and-paint.js

Blob: `75d3e279a4cd6916f769a68f2c7f246e8ad354dc`. Role: test-path,source. Parse: module.

- runAfterLayoutAndPaint @3-11; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @6-10; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7-9; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-image-animation/resources/image-animation-utils.js

Blob: `5e94131ed38f56e3a8db521015c4423236913eb0`. Role: test-path,source. Parse: module.

- waitForFrameTime @1-13; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @2-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- tick @4-10; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-images/support/testHelper.js

Blob: `e2806336e1b7d020141ca692a74ef5cf5f9834b7`. Role: test-path,source. Parse: module.

- paintCanvases @1-19; FunctionDeclaration; parameters=0; async=false; generator=false
- populateElements @21-30; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-inline/alignment-baseline/support/variant-class.js

Blob: `86d46464254d44b567750dac35c12b886685ae66`. Role: test-path,source. Parse: module.

- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-inline/dominant-baseline/support/variant-class.js

Blob: `86d46464254d44b567750dac35c12b886685ae66`. Role: test-path,source. Parse: module.

- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-inline/initial-letter/resources/initial-letter-variants.js

Blob: `a3eceae8a92f5ccdc5e1860b0e0401c917819450`. Role: test-path,source. Parse: module.

- setupInitialLetterTestVariants @3-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- replaceTextStart @43-75; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-inline/text-box-trim/parsing/values.js

Blob: `536f4a48c58bd68e4e26aba93cd2535e0e9a8e50`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-inline/text-box-trim/support/variant-class.js

Blob: `d1ca547cfd79bfa1dc1a8f64f62e63099b9c6cce`. Role: test-path,source. Parse: module.

- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-layout-api/child-constraints/support/layout-child-sizes-worklet.js

Blob: `5956c9a70c2ba650318fd6bbbc859f1cc8002f08`. Role: test-path,source. Parse: module.

- parseNumber @3-7; FunctionDeclaration; parameters=1; async=false; generator=false
- childInputProperties @10-21; FunctionExpression; parameters=0; async=false; generator=false
- intrinsicSizes @23-23; FunctionExpression; parameters=0; async=true; generator=false
- layout @24-66; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @25-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- equalityFunc @57-59; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class (anonymous) @9-67
- Module /common/arrays.js @1; ImportDeclaration

### testing/web-platform/tests/css/css-layout-api/constraints/support/constraints-fixed-block-size.js

Blob: `25d73ef61568477784a002dfeb591b7f5c8d0b30`. Role: test-path,source. Parse: module.

- inputProperties @2-4; FunctionExpression; parameters=0; async=false; generator=false
- intrinsicSizes @6-6; FunctionExpression; parameters=0; async=true; generator=false
- layout @7-21; FunctionExpression; parameters=4; async=true; generator=false
- Class (anonymous) @1-22

### testing/web-platform/tests/css/css-layout-api/constraints/support/constraints-fixed-inline-size.js

Blob: `3636f366547342a04253864016bf89ed392ea48a`. Role: test-path,source. Parse: module.

- intrinsicSizes @2-2; FunctionExpression; parameters=0; async=true; generator=false
- layout @3-8; FunctionExpression; parameters=4; async=true; generator=false
- Class (anonymous) @1-9

### testing/web-platform/tests/css/css-layout-api/edges/support/edges.js

Blob: `b70a42f398c34f0d3a7981fec16447ffa8a1e97e`. Role: test-path,source. Parse: module.

- parseNumber @3-7; FunctionDeclaration; parameters=1; async=false; generator=false
- inputProperties @10-17; FunctionExpression; parameters=0; async=false; generator=false
- intrinsicSizes @19-19; FunctionExpression; parameters=0; async=true; generator=false
- layout @20-37; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class (anonymous) @9-38
- Module /common/arrays.js @1; ImportDeclaration

### testing/web-platform/tests/css/css-layout-api/layout-child/support/layout-child-worklet.js

Blob: `70d1b7e4572bd09b2c201705bf643e2979caccf1`. Role: test-path,source. Parse: module.

- inputProperties @4-6; FunctionExpression; parameters=0; async=false; generator=false
- childInputProperties @8-10; FunctionExpression; parameters=0; async=false; generator=false
- intrinsicSizes @12-12; FunctionExpression; parameters=0; async=true; generator=false
- layout @13-25; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @15-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class (anonymous) @3-26
- Module /common/arrays.js @1; ImportDeclaration

### testing/web-platform/tests/css/css-layout-api/position-fragment/support/layout-position-child-worklet.js

Blob: `7d5c494952d58038a6bc71719be3c6d8d6e363cb`. Role: test-path,source. Parse: module.

- childInputProperties @2-7; FunctionExpression; parameters=0; async=false; generator=false
- intrinsicSizes @9-9; FunctionExpression; parameters=0; async=true; generator=false
- layout @10-19; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class (anonymous) @1-20

### testing/web-platform/tests/css/css-logical/resources/test-box-properties.js

Blob: `ef1854f97de4c93c3156540ed81101fcc9993578`. Role: test-path,source. Parse: module.

- createBoxPropertyGroup @41-67; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createCornerPropertyGroup @82-102; FunctionDeclaration; parameters=2; async=false; generator=false
- createSizingPropertyGroup @110-124; FunctionDeclaration; parameters=1; async=false; generator=false
- runTests @132-297; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @133-135; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @134-134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-148; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-170; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @206-218; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @223-238; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @246-265; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @272-293; FunctionExpression; parameters=0; async=false; generator=false
- Module ./test-shared.js @1; ImportDeclaration

### testing/web-platform/tests/css/css-logical/resources/test-logical-values.js

Blob: `7a039379cbddcbd3df0bf793636b932fe2fafbbc`. Role: test-path,source. Parse: module.

- runTests @17-27; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-25; FunctionExpression; parameters=0; async=false; generator=false
- Module ./test-shared.js @1; ImportDeclaration

### testing/web-platform/tests/css/css-logical/resources/test-shared.js

Blob: `7a1da2e649708a0ed7d6d9dbe76322ce67bd266b`. Role: test-path,source. Parse: module.

- testCSSValues @93-97; FunctionDeclaration; parameters=3; async=false; generator=false
- testComputedValues @99-104; FunctionDeclaration; parameters=3; async=false; generator=false
- makeDeclaration @106-112; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-mixins/resources/utils.js

Blob: `b29cd48d92c24f0a1e598185da7621a6984b3240`. Role: test-path,source. Parse: module.

- test_all_templates @19-31; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- find_target @35-45; FunctionDeclaration; parameters=1; async=false; generator=false
- test_all_shadows @49-61; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @52-59; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-navigation/tentative/resources/test-navigation.js

Blob: `9967dbcee833b6a288a6bfaa6a2c09b47a6d4f7c`. Role: test-path,source. Parse: module.

- matches @1-3; FunctionDeclaration; parameters=2; async=false; generator=false
- get_match_result @5-11; FunctionDeclaration; parameters=1; async=false; generator=false
- assert_match_result @13-21; FunctionDeclaration; parameters=4; async=false; generator=false
- test_navigation @23-77; FunctionDeclaration; parameters=6; async=true; generator=false
- navigation.onnavigate @29-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- precommitHandler @32-35; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handler @36-39; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @72-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- navigation.onnavigatesuccess @72-73; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-overflow/scroll-markers/support/scroll-marker-support.js

Blob: `2a047f72436bb9a39005c52877d121a3be6409dc`. Role: test-path,source. Parse: module.

- verifySelectedMarker @4-14; FunctionDeclaration; parameters=4; async=false; generator=false

### testing/web-platform/tests/css/css-overflow/support/scroll-axis-lock.js

Blob: `87e5b80856fe7694dfe7c21ee2d945e29ed1527e`. Role: test-path,source. Parse: module.

- test_driver_touch_scroll @3-16; FunctionDeclaration; parameters=4; async=false; generator=false
- test_driver_wheel_scroll @18-23; FunctionDeclaration; parameters=3; async=false; generator=false
- check_scroll_axis_lock @44-143; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @115-117; ArrowFunctionExpression; parameters=1; async=false; generator=false
- scroll_is_axis_locked @145-191; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @156-189; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @190-190; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-paint-api/resources/imported-module.mjs

Blob: `2a23b334143b92e1388fea23d9b5d793dfbd25f5`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-paint-api/resources/utils.js

Blob: `e9686441361326b996c73bfd084bd2f5a0bb1648`. Role: test-path,source. Parse: module.

- registerAndInterpolateProperty @3-16; FunctionDeclaration; parameters=1; async=false; generator=false
- expectWorkletValues @24-53; FunctionDeclaration; parameters=2; async=false; generator=false
- ensureArray @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=2; async=false; generator=false
- expectWorkletValue @56-58; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/css/css-position/resources/ref-rectangle.js

Blob: `c94c15720f12aaac9a56c839d3867f98d56efcb8`. Role: test-path,source. Parse: module.

- createIndicatorForStickyElements @5-34; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @9-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-32; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-position/resources/sticky-util.js

Blob: `074c25c81f4759e41253b14e2893b407bfeda7da`. Role: test-path,source. Parse: module.

- setupStickyTest @20-73; FunctionDeclaration; parameters=2; async=false; generator=false
- setupNestedStickyTest @83-109; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/css/css-properties-values-api/resources/utils.js

Blob: `642c02f96e52bd9815ae5ffe02a99cc72a1a9504`. Role: test-path,source. Parse: module.

- generate_name @4-6; FunctionDeclaration; parameters=0; async=false; generator=false
- any_initial_value @9-45; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- generate_property @52-74; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- all_syntaxes @76-94; FunctionDeclaration; parameters=0; async=false; generator=false
- with_style_node @96-105; FunctionDeclaration; parameters=2; async=false; generator=false
- with_at_property @107-118; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @117-117; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_with_at_property @120-122; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_with_style_node @124-126; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @125-125; ArrowFunctionExpression; parameters=0; async=false; generator=false
- animation_test @128-150; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @133-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- discrete_animation_test @152-181; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @153-180; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkAtProgress @169-172; ArrowFunctionExpression; parameters=2; async=false; generator=false
- transition_test @183-224; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @184-223; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @198-205; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @199-202; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @204-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- no_transition_test @226-245; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @227-244; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_initial_value_valid @247-253; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @249-252; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_initial_value_invalid @255-261; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @256-260; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @259-259; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-properties-values-api/support/alt/alt.js

Blob: `f25e18beeb8d70932e418865488dff9a3b0d94cf`. Role: test-path,source. Parse: module.

- reg_url @1-8; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-properties-values-api/support/main/main.js

Blob: `169ed7b53c16a145df8598e0888e1271d288d5c7`. Role: test-path,source. Parse: module.

- reg_url @1-8; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-pseudo/support/selections.js

Blob: `4396bfa326b1d55b0b0e1786ad345d9754de1a35`. Role: test-path,source. Parse: module.

- selectRangeWith @14-29; FunctionDeclaration; parameters=1; async=false; generator=false
- selectNodeContents @35-46; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- trySpellcheck @56-72; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @63-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createRangeForTextOnly @74-83; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/css/css-ruby/support/ruby-dynamic-insertion.js

Blob: `0bf6cd969779db94866a58ab7b534d2f53a5b99a`. Role: test-path,source. Parse: module.

- window.onload @1-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6-41; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-ruby/support/ruby-dynamic-removal.js

Blob: `c703e7601e4f3a84e7d7739baf5841e16a46e3f0`. Role: test-path,source. Parse: module.

- getElements @1-3; FunctionDeclaration; parameters=1; async=false; generator=false
- window.onload @4-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-scroll-snap/snap-after-relayout/multiple-aligned-targets/resources/common.js

Blob: `b4d0dbcb64f1f0496d249d2089b294aeed82d198`. Role: test-path,source. Parse: module.

- scrollToAlignedElements @12-50; FunctionDeclaration; parameters=3; async=true; generator=false
- verifySelectedSnapTarget @57-90; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @69-74; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- runScrollSnapSelectionVerificationTest @94-112; FunctionDeclaration; parameters=7; async=true; generator=false
- (anonymous) @102-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- shiftLayoutToAlignElements @119-127; FunctionDeclaration; parameters=3; async=false; generator=false
- runLayoutSnapSeletionVerificationTest @132-156; FunctionDeclaration; parameters=5; async=true; generator=false
- (anonymous) @151-153; ArrowFunctionExpression; parameters=1; async=false; generator=false
- focusAndAssert @158-161; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-scroll-snap/snap-events/resources/common.js

Blob: `c4a06b02fad08d3af46e7feb52959a782de94b88`. Role: test-path,source. Parse: module.

- checkSnapEventSupport @1-9; FunctionDeclaration; parameters=1; async=false; generator=false
- assertSnapEvent @11-19; FunctionDeclaration; parameters=2; async=false; generator=false
- snap_test_setup @21-28; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @25-27; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_snap_event @30-49; FunctionDeclaration; parameters=4; async=true; generator=false
- test_scrollsnapchange @51-53; FunctionDeclaration; parameters=3; async=true; generator=false
- waitForEventUntil @55-84; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @57-83; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @59-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @71-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForEventsUntil @86-98; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @87-97; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @89-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @93-96; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForSnapEvent @105-113; FunctionDeclaration; parameters=4; async=false; generator=false
- waitForScrollSnapChangeEvent @115-117; FunctionDeclaration; parameters=2; async=false; generator=false
- getScrollbarToScrollerRatio @119-125; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-scroll-snap/snap-events/resources/user-scroll-common.js

Blob: `d5982ae1653fa06036ddf6e5ddd4c3896025671a`. Role: test-path,source. Parse: module.

- snap_event_touch_scroll_helper @7-18; FunctionDeclaration; parameters=2; async=false; generator=false
- snap_event_scrollbar_drag_helper @24-42; FunctionDeclaration; parameters=3; async=false; generator=false
- test_no_snap_event @48-63; FunctionDeclaration; parameters=4; async=true; generator=false
- test_no_scrollsnapchange @65-67; FunctionDeclaration; parameters=3; async=true; generator=false
- test_no_scrollsnapchanging @69-71; FunctionDeclaration; parameters=3; async=true; generator=false

### testing/web-platform/tests/css/css-scroll-snap/support/common.js

Blob: `1cdce56e71babca3585c906ac9660bdb2b4432fb`. Role: test-path,source. Parse: module.

- keyPress @16-23; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForAnimationEnd @30-56; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @38-55; ArrowFunctionExpression; parameters=2; async=false; generator=false
- tick @39-53; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForEvent @59-63; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitForScrollEvent @65-67; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForWheelEvent @69-71; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForScrollTo @73-86; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @74-85; ArrowFunctionExpression; parameters=2; async=false; generator=false
- scrollListener @75-80; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitForNextFrame @88-99; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @89-98; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @91-97; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-shadow/part/support/shadow-helper.js

Blob: `94accd6b1f9b095fda0079f7b86b866d88ffee01`. Role: test-path,source. Parse: module.

- getElementByShadowIds @3-17; FunctionDeclaration; parameters=2; async=false; generator=false
- installCustomElement @20-33; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @22-30; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @21-31

### testing/web-platform/tests/css/css-shapes/shape-outside/supported-shapes/support/rounded-rectangle.js

Blob: `3e624322a43397e542444819f7b4ecccd939bd02`. Role: test-path,source. Parse: module.

- ellipseXIntercept @1-4; FunctionDeclaration; parameters=3; async=false; generator=false
- scanConvertRoundedRectangleOutside @6-36; FunctionDeclaration; parameters=4; async=false; generator=false
- genLeftRoundedRectFloatShapeOutsideRefTest @38-49; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @42-46; FunctionExpression; parameters=1; async=false; generator=false
- getRoundedRectLeftEdge @51-60; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @55-58; FunctionExpression; parameters=1; async=false; generator=false
- genRightRoundedRectFloatShapeOutsideRefTest @62-73; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @67-71; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-shapes/shape-outside/supported-shapes/support/subpixel-utils.js

Blob: `50bf0989f114f651c7e7481b0c090ffa3f8c1154`. Role: test-path,source. Parse: module.

- (anonymous) @1-26; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @4-15; FunctionDeclaration; parameters=0; async=false; generator=false
- snapToLayoutUnit @19-21; FunctionExpression; parameters=1; async=false; generator=false
- ceilSnapToLayoutUnit @22-24; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-shapes/shape-outside/supported-shapes/support/test-utils.js

Blob: `906fe6560884c05a65879d9b4dc847e359e56bf4`. Role: test-path,source. Parse: module.

- verifyTextPoints @1-27; FunctionDeclaration; parameters=4; async=false; generator=false

### testing/web-platform/tests/css/css-shapes/shape-outside/values/support/parsing-utils.js

Blob: `e438ab9fa937472fe085c5054cc4c412a6bfc04f`. Role: test-path,source. Parse: module.

- (anonymous) @1-892; FunctionExpression; parameters=0; async=false; generator=false
- testInlineStyle @2-7; FunctionDeclaration; parameters=2; async=false; generator=false
- testComputedStyle @9-26; FunctionDeclaration; parameters=2; async=false; generator=false
- testShapeMarginInlineStyle @28-36; FunctionDeclaration; parameters=2; async=false; generator=false
- testShapeMarginComputedStyle @38-64; FunctionDeclaration; parameters=2; async=false; generator=false
- testShapeThresholdInlineStyle @66-72; FunctionDeclaration; parameters=2; async=false; generator=false
- testShapeThresholdComputedStyle @74-95; FunctionDeclaration; parameters=2; async=false; generator=false
- buildTestCases @99-130; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @105-128; FunctionExpression; parameters=1; async=false; generator=false
- isAbsoluteLength @132-135; FunctionDeclaration; parameters=1; async=false; generator=false
- buildPositionTests @137-213; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @142-145; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @148-200; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @202-209; FunctionExpression; parameters=1; async=false; generator=false
- buildRadiiTests @215-261; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @221-224; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @227-258; FunctionExpression; parameters=1; async=false; generator=false
- buildInsetTests @263-288; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @268-271; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @273-285; FunctionExpression; parameters=1; async=false; generator=false
- buildPolygonTests @290-307; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @294-305; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @295-304; FunctionExpression; parameters=1; async=false; generator=false
- buildCalcTests @309-327; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @311-325; FunctionExpression; parameters=1; async=false; generator=false
- unique @329-338; FunctionDeclaration; parameters=1; async=false; generator=false
- setUnit @340-353; FunctionDeclaration; parameters=5; async=false; generator=false
- roundCssNumber @355-358; FunctionDeclaration; parameters=1; async=false; generator=false
- convertToPx @360-412; FunctionDeclaration; parameters=1; async=false; generator=false
- roundResultStr @414-432; FunctionDeclaration; parameters=1; async=false; generator=false
- generateInsetRoundCases @434-474; FunctionDeclaration; parameters=2; async=false; generator=false
- insetRound @444-446; FunctionDeclaration; parameters=1; async=false; generator=false
- serializedInsetRound @448-459; FunctionDeclaration; parameters=3; async=false; generator=false
- each @476-482; FunctionDeclaration; parameters=2; async=false; generator=false
- setupFonts @487-498; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @494-497; FunctionExpression; parameters=2; async=false; generator=false
- restoreFonts @500-510; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @501-508; FunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-shapes/spec-examples/support/spec-example-utils.js

Blob: `6939b753aad8bc17aebe58673a6e2001f59c07a2`. Role: test-path,source. Parse: module.

- approxShapeTest @1-16; FunctionDeclaration; parameters=4; async=false; generator=false
- runTest @7-14; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-sizing/responsive-iframe/resources/slow.js

Blob: `3f3652caf198748a86867b1e925871096f080e26`. Role: test-path,source. Parse: module.

- (anonymous) @7-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-text/support/get-char-advances.js

Blob: `0fd7332c4ea13240c3ad7416ab147071c47b267d`. Role: test-path,source. Parse: module.

- getCharAdvances @11-70; FunctionDeclaration; parameters=1; async=false; generator=false
- walk @17-42; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @44-52; FunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-text/text-group-align/support/test-helpers.js

Blob: `27b6a7baf160b6a6ebcd14ccc7f51c56b930c15c`. Role: test-path,source. Parse: module.

- generateSimpleTest @7-18; FunctionDeclaration; parameters=1; async=false; generator=false
- generateSimpleReference @20-36; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-text/text-spacing-trim/support/highlight-chars.js

Blob: `07172f021aaaf58554fe6237994442423549623a`. Role: test-path,source. Parse: module.

- highlightChars @7-51; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @53-56; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-text/text-spacing-trim/support/variant-class.js

Blob: `28cf85ff9f65b4b962250104080c9990382a28db`. Role: test-path,source. Parse: module.

- (anonymous) @10-10; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-text/text-spacing-trim/support/variant-feature.js

Blob: `4fee3e43c548844759f0baee23d1c21776cb47d4`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-text/text-transform/math/italic-mapping.js

Blob: `ba17d3f6b608161239d9bf5ba41f45c949b82532`. Role: test-path,source. Parse: module.


### testing/web-platform/tests/css/css-transforms/animation/support/transform-interpolation-reftests.js

Blob: `4070aec84abb3fed35d0187616d42a650b299d64`. Role: test-path,source. Parse: module.

- initialStyle @96-104; FunctionDeclaration; parameters=1; async=false; generator=false
- finalStyle @106-110; FunctionDeclaration; parameters=1; async=false; generator=false
- styleBody @112-117; FunctionDeclaration; parameters=0; async=false; generator=false
- createTests @152-177; FunctionDeclaration; parameters=1; async=true; generator=false
- createRefs @181-198; FunctionDeclaration; parameters=1; async=true; generator=false

### testing/web-platform/tests/css/css-transitions/support/generalParallelTest.js

Blob: `f8ad77ecde5957171ed9f1434fa842d92ac54479`. Role: test-path,source. Parse: module.

- (anonymous) @1-248; FunctionExpression; parameters=1; async=false; generator=false
- setup @7-10; FunctionExpression; parameters=2; async=false; generator=false
- _setupDom @12-48; FunctionExpression; parameters=2; async=false; generator=false
- computedStyle @23-25; FunctionExpression; parameters=1; async=false; generator=false
- computedStyle @33-35; FunctionExpression; parameters=1; async=false; generator=false
- computedStyle @43-45; FunctionExpression; parameters=1; async=false; generator=false
- _setupEvents @50-62; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @51-61; FunctionExpression; parameters=1; async=false; generator=false
- handler @52-58; FunctionExpression; parameters=1; async=false; generator=false
- teardown @64-69; FunctionExpression; parameters=2; async=false; generator=false
- sliceStart @71-74; FunctionExpression; parameters=2; async=false; generator=false
- transitionsStarted @75-78; FunctionExpression; parameters=2; async=false; generator=false
- sliceDone @80-85; FunctionExpression; parameters=2; async=false; generator=false
- done @87-91; FunctionExpression; parameters=1; async=false; generator=false
- addStyles @93-106; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @98-105; FunctionExpression; parameters=1; async=false; generator=false
- getStyle @108-125; FunctionExpression; parameters=1; async=false; generator=false
- _getStyleFor @127-133; FunctionExpression; parameters=2; async=false; generator=false
- _addClass @135-141; FunctionExpression; parameters=3; async=false; generator=false
- _removeClass @143-149; FunctionExpression; parameters=3; async=false; generator=false
- startTransition @151-156; FunctionExpression; parameters=1; async=false; generator=false
- startValueCollection @158-213; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @161-180; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @162-179; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @163-177; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @181-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @189-212; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @191-191; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @193-211; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @198-210; FunctionExpression; parameters=1; async=false; generator=false
- stopValueCollection @215-217; FunctionExpression; parameters=1; async=false; generator=false
- assertExpectedEventsFunc @220-226; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @221-225; FunctionExpression; parameters=0; async=false; generator=false
- assertIntermediateValuesFunc @228-245; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @229-244; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-transitions/support/helper.js

Blob: `d8a13f09fae42164de63247a8901f399be5035fc`. Role: test-path,source. Parse: module.

- (anonymous) @5-368; FunctionExpression; parameters=1; async=false; generator=false
- root.setStyle @12-37; FunctionExpression; parameters=2; async=false; generator=false
- serializeStyles @39-49; FunctionDeclaration; parameters=1; async=false; generator=false
- root.computedStyle @53-58; FunctionExpression; parameters=3; async=false; generator=false
- root.reflow @61-63; FunctionExpression; parameters=0; async=false; generator=false
- root.extend @66-74; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @67-71; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-70; FunctionExpression; parameters=1; async=false; generator=false
- root.domFixture @79-95; FunctionExpression; parameters=1; async=false; generator=false
- root.assert_times_equal @111-113; FunctionExpression; parameters=3; async=false; generator=false
- root.assert_time_equals_literal @118-120; ArrowFunctionExpression; parameters=3; async=false; generator=false
- root.assert_end_events_equal @126-131; FunctionExpression; parameters=4; async=false; generator=false
- root.assert_end_event_batch_equal @141-178; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @159-162; ArrowFunctionExpression; parameters=2; async=false; generator=false
- sortByPropertyName @164-165; ArrowFunctionExpression; parameters=2; async=false; generator=false
- root.addDiv @190-206; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @199-203; FunctionExpression; parameters=0; async=false; generator=false
- root.addStyle @218-235; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @230-232; ArrowFunctionExpression; parameters=0; async=false; generator=false
- root.waitForFrame @240-244; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @241-243; ArrowFunctionExpression; parameters=1; async=false; generator=false
- root.waitForAnimationFrames @253-269; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @255-268; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleFrame @256-266; FunctionDeclaration; parameters=0; async=false; generator=false
- root.waitForAllAnimations @276-277; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @277-277; ArrowFunctionExpression; parameters=1; async=false; generator=false
- root.frameTimeout @290-318; ArrowFunctionExpression; parameters=3; async=false; generator=false
- waitAFrame @294-310; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @300-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @312-315; ArrowFunctionExpression; parameters=1; async=false; generator=false
- root.supportsStartingStyle @320-324; ArrowFunctionExpression; parameters=0; async=false; generator=false
- root.waitForTransitionEnd @332-336; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @333-335; ArrowFunctionExpression; parameters=1; async=false; generator=false
- root.assertTransitionKeyframes @350-366; FunctionExpression; parameters=4; async=false; generator=false

### testing/web-platform/tests/css/css-transitions/support/properties.js

Blob: `3f5d98e6125b9c5973f74a00f8c85c4e5b114049`. Role: test-path,source. Parse: module.

- (anonymous) @1-416; FunctionExpression; parameters=1; async=false; generator=false
- length @9-30; FunctionExpression; parameters=0; async=false; generator=false
- length-em @31-35; FunctionExpression; parameters=0; async=false; generator=false
- percentage @36-41; FunctionExpression; parameters=0; async=false; generator=false
- color @42-48; FunctionExpression; parameters=0; async=false; generator=false
- rectangle @49-54; FunctionExpression; parameters=0; async=false; generator=false
- font-weight @55-61; FunctionExpression; parameters=0; async=false; generator=false
- number @62-68; FunctionExpression; parameters=0; async=false; generator=false
- number[0,1] @69-75; FunctionExpression; parameters=0; async=false; generator=false
- integer @76-81; FunctionExpression; parameters=0; async=false; generator=false
- shadow @82-87; FunctionExpression; parameters=0; async=false; generator=false
- visibility @88-93; FunctionExpression; parameters=0; async=false; generator=false
- auto-length @94-96; FunctionExpression; parameters=0; async=false; generator=false
- border-radius @98-103; FunctionExpression; parameters=0; async=false; generator=false
- image @104-115; FunctionExpression; parameters=0; async=false; generator=false
- background-size @116-120; FunctionExpression; parameters=0; async=false; generator=false
- box-shadow @121-126; FunctionExpression; parameters=0; async=false; generator=false
- vertical @127-131; FunctionExpression; parameters=0; async=false; generator=false
- horizontal @132-136; FunctionExpression; parameters=0; async=false; generator=false
- font-stretch @137-141; FunctionExpression; parameters=0; async=false; generator=false
- transform @142-146; FunctionExpression; parameters=0; async=false; generator=false
- position @147-153; FunctionExpression; parameters=0; async=false; generator=false
- display @154-159; FunctionExpression; parameters=0; async=false; generator=false
- object-view-box @160-166; FunctionExpression; parameters=0; async=false; generator=false
- assemble @329-357; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @334-353; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @336-352; FunctionExpression; parameters=1; async=false; generator=false
- root.getPropertyTests @359-361; FunctionExpression; parameters=0; async=false; generator=false
- root.getMissingPropertyTests @363-365; FunctionExpression; parameters=0; async=false; generator=false
- root.getUnspecifiedPropertyTests @367-369; FunctionExpression; parameters=0; async=false; generator=false
- root.getFontSizeRelativePropertyTests @371-385; FunctionExpression; parameters=0; async=false; generator=false
- root.filterPropertyTests @387-414; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @396-398; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @401-411; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-transitions/support/runParallelAsyncHarness.js

Blob: `7293bf92d06fa9b6c8b8ad5d4063a398dd5ccb26`. Role: test-path,source. Parse: module.

- (anonymous) @1-156; FunctionExpression; parameters=1; async=false; generator=false
- DomContentLoadedPromise @60-66; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @61-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @62-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- root.runParallelAsyncHarness @68-154; FunctionExpression; parameters=1; async=true; generator=false
- noop @75-75; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-94; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @91-93; FunctionExpression; parameters=1; async=false; generator=false
- runLoop @96-150; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @107-109; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @115-121; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-120; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-119; FunctionExpression; parameters=0; async=false; generator=false
- concludeSlice @127-147; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @128-141; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @130-134; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @131-133; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @138-140; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/css/css-transitions/support/vendorPrefix.js

Blob: `1e7eed04818a06e4723fb8d1f2df2e258ab5df8b`. Role: test-path,source. Parse: module.

- (anonymous) @5-86; FunctionExpression; parameters=1; async=false; generator=false
- camelCase @11-15; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @12-14; FunctionExpression; parameters=2; async=false; generator=false
- root.addVendorPrefix @18-26; FunctionExpression; parameters=1; async=false; generator=false
- root.addValueVendorPrefix @29-37; FunctionExpression; parameters=2; async=false; generator=false
- root.getVendorPrefix @40-63; FunctionExpression; parameters=1; async=false; generator=false
- root.getValueVendorPrefix @66-83; FunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/resources/testhelper.js

Blob: `ae61879fddfa49de9067d469c7168ebd1b8ffe74`. Role: test-path,source. Parse: module.

- assert_numeric_type_equals @1-9; FunctionDeclaration; parameters=2; async=false; generator=false
- assert_color_channel_approx_equals @11-51; FunctionDeclaration; parameters=2; async=false; generator=false
- epsilonForUnitType @16-29; FunctionDeclaration; parameters=1; async=false; generator=false
- assert_style_value_equals @55-140; FunctionDeclaration; parameters=3; async=false; generator=false
- assert_style_value_array_equals @143-148; FunctionDeclaration; parameters=2; async=false; generator=false
- assert_style_value_array_unordered_equals @160-176; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @164-175; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @165-173; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createDivWithStyle @190-198; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @194-196; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createDivWithoutStyle @202-209; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @205-207; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createInlineStyleMap @213-215; FunctionDeclaration; parameters=2; async=false; generator=false
- createElementWithInlineStyleMap @217-220; FunctionDeclaration; parameters=2; async=false; generator=false
- createComputedStyleMap @224-226; FunctionDeclaration; parameters=2; async=false; generator=false
- createElementWithComputedStyleMap @228-231; FunctionDeclaration; parameters=2; async=false; generator=false
- createDeclaredStyleMap @235-237; FunctionDeclaration; parameters=2; async=false; generator=false
- createRuleWithDeclaredStyleMap @239-247; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @243-245; ArrowFunctionExpression; parameters=0; async=false; generator=false
- loadImageResource @252-261; FunctionDeclaration; parameters=2; async=false; generator=false
- assert_matrix_approx_equals @263-266; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/cssKeywordValue-invalid.any.js

Blob: `923247acbe89ebc1489183151a0b3897ad818caa`. Role: test-path,source. Parse: module.

- (anonymous) @7-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @8-8; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/cssKeywordValue-value.any.js

Blob: `8c14ab4a02188c8ed7dd88d0cedc741daea86cc0`. Role: test-path,source. Parse: module.

- (anonymous) @16-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/cssKeywordValue.any.js

Blob: `776b6e2dd54e8d8f8fbc463ed8627421b3efcbdb`. Role: test-path,source. Parse: module.

- (anonymous) @16-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/cssUnparsedValue-empty.any.js

Blob: `3750303dfdf03167b675891afffe85f2652782d8`. Role: test-path,source. Parse: module.

- (anonymous) @8-11; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/numeric-objects/add-two-types.tentative.any.js

Blob: `a41faf0699afb2a3a7ad330c864bf517b34e1049`. Role: test-path,source. Parse: module.

- (anonymous) @20-20; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-61; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-68; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/numeric-objects/arithmetic.tentative.any.js

Blob: `ccdd7a5b7d25b1611f74d7c57b9fa5f7ea8bd1dd`. Role: test-path,source. Parse: module.

- (anonymous) @23-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @73-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @94-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @99-104; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @113-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @118-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @125-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @132-136; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @138-142; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @144-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @146-146; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @147-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @151-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @153-153; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @158-162; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @161-161; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/css/css-typed-om/stylevalue-subclasses/numeric-objects/create-a-type.tentative.any.js

Blob: `de799c3e541bb130855cf6ea5004deef594e6a51`. Role: test-path,source. Parse: module.

- (anonymous) @8-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-46; ArrowFunctionExpression; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [daaa8aea-d250-4143-a81d-35806f7921dd.md](daaa8aea-d250-4143-a81d-35806f7921dd.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `296aef255db319c37b12617bde1360ec09a950850daf502be94e29b9034f631c`.
