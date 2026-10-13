<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["intl/strres/tests/unit/test_bug397093.js","intl/uconv/tests/unit/head_charsetConversionTests.js","intl/uconv/tests/unit/test_bug116882.js","intl/uconv/tests/unit/test_bug317216.js","intl/uconv/tests/unit/test_bug321379.js","intl/uconv/tests/unit/test_bug340714.js","intl/uconv/tests/unit/test_bug381412.Big5-HKSCS.js","intl/uconv/tests/unit/test_bug381412.Big5.js","intl/uconv/tests/unit/test_bug381412.euc-kr.js","intl/uconv/tests/unit/test_bug381412.euc_jp.js","intl/uconv/tests/unit/test_bug381412.gb2312.js","intl/uconv/tests/unit/test_bug381412.js","intl/uconv/tests/unit/test_bug396637.js","intl/uconv/tests/unit/test_bug399257.js","intl/uconv/tests/unit/test_bug457886.js","intl/uconv/tests/unit/test_bug522931.js","intl/uconv/tests/unit/test_bug563283.js","intl/uconv/tests/unit/test_bug563618.js","intl/uconv/tests/unit/test_bug601429.js","intl/uconv/tests/unit/test_bug715319.dbcs.js","intl/uconv/tests/unit/test_bug715319.euc_jp.js","intl/uconv/tests/unit/test_bug715319.gb2312.js","intl/uconv/tests/unit/test_charset_conversion.js","intl/uconv/tests/unit/test_decode_8859-1.js","intl/uconv/tests/unit/test_decode_8859-10.js","intl/uconv/tests/unit/test_decode_8859-11.js","intl/uconv/tests/unit/test_decode_8859-13.js","intl/uconv/tests/unit/test_decode_8859-14.js","intl/uconv/tests/unit/test_decode_8859-15.js","intl/uconv/tests/unit/test_decode_8859-2.js","intl/uconv/tests/unit/test_decode_8859-3.js","intl/uconv/tests/unit/test_decode_8859-4.js","intl/uconv/tests/unit/test_decode_8859-5.js","intl/uconv/tests/unit/test_decode_8859-6.js","intl/uconv/tests/unit/test_decode_8859-7.js","intl/uconv/tests/unit/test_decode_8859-8.js","intl/uconv/tests/unit/test_decode_8859-9.js","intl/uconv/tests/unit/test_decode_CP1250.js","intl/uconv/tests/unit/test_decode_CP1251.js","intl/uconv/tests/unit/test_decode_CP1252.js","intl/uconv/tests/unit/test_decode_CP1253.js","intl/uconv/tests/unit/test_decode_CP1254.js","intl/uconv/tests/unit/test_decode_CP1255.js","intl/uconv/tests/unit/test_decode_CP1256.js","intl/uconv/tests/unit/test_decode_CP1257.js","intl/uconv/tests/unit/test_decode_CP1258.js","intl/uconv/tests/unit/test_decode_CP874.js","intl/uconv/tests/unit/test_decode_gb18030.js","intl/uconv/tests/unit/test_decode_gbk.js","intl/uconv/tests/unit/test_decode_macintosh.js","intl/uconv/tests/unit/test_decode_x_mac_cyrillic.js","intl/uconv/tests/unit/test_decode_x_mac_ukrainian.js","intl/uconv/tests/unit/test_encode_8859-1.js","intl/uconv/tests/unit/test_encode_8859-10.js","intl/uconv/tests/unit/test_encode_8859-11.js","intl/uconv/tests/unit/test_encode_8859-13.js","intl/uconv/tests/unit/test_encode_8859-14.js","intl/uconv/tests/unit/test_encode_8859-15.js","intl/uconv/tests/unit/test_encode_8859-2.js","intl/uconv/tests/unit/test_encode_8859-3.js","intl/uconv/tests/unit/test_encode_8859-4.js","intl/uconv/tests/unit/test_encode_8859-5.js","intl/uconv/tests/unit/test_encode_8859-6.js","intl/uconv/tests/unit/test_encode_8859-7.js","intl/uconv/tests/unit/test_encode_8859-8.js","intl/uconv/tests/unit/test_encode_8859-9.js","intl/uconv/tests/unit/test_encode_CP1250.js","intl/uconv/tests/unit/test_encode_CP1251.js","intl/uconv/tests/unit/test_encode_CP1252.js","intl/uconv/tests/unit/test_encode_CP1253.js","intl/uconv/tests/unit/test_encode_CP1254.js","intl/uconv/tests/unit/test_encode_CP1255.js","intl/uconv/tests/unit/test_encode_CP1256.js","intl/uconv/tests/unit/test_encode_CP1257.js","intl/uconv/tests/unit/test_encode_CP1258.js","intl/uconv/tests/unit/test_encode_CP874.js","intl/uconv/tests/unit/test_encode_gb18030.js","intl/uconv/tests/unit/test_encode_gbk.js","intl/uconv/tests/unit/test_encode_macintosh.js","intl/uconv/tests/unit/test_encode_x_mac_cyrillic.js","intl/uconv/tests/unit/test_input_stream.js","intl/uconv/tests/unit/test_unEscapeNonAsciiURI.js","intl/uconv/tests/unit/test_unEscapeURIForUI.js","intl/uconv/tests/unit/test_unmapped.js","intl/uconv/tests/unit/test_utf8_illegals.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/intl JavaScript function map 189

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### intl/strres/tests/unit/test_bug397093.js

Blob: `a2bb1eb2363716d83980b67d3dfbdafc05442b17`. Role: test-path,source. Parse: module.

- run_test @16-39; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/head_charsetConversionTests.js

Blob: `4fbf6e9af7250089fc85f352acc4536ebdfba273`. Role: test-path,source. Parse: module.

- CreateScriptableConverter @3-10; FunctionDeclaration; parameters=0; async=false; generator=false
- checkDecode @12-47; FunctionDeclaration; parameters=4; async=false; generator=false
- checkEncode @49-80; FunctionDeclaration; parameters=4; async=false; generator=false
- testDecodeAliases @82-87; FunctionDeclaration; parameters=3; async=false; generator=false
- testEncodeAliases @89-94; FunctionDeclaration; parameters=3; async=false; generator=false
- testDecodeAliasesInternal @96-102; FunctionDeclaration; parameters=3; async=false; generator=false
- testEncodeAliasesInternal @104-110; FunctionDeclaration; parameters=3; async=false; generator=false

### intl/uconv/tests/unit/test_bug116882.js

Blob: `5e76b30aa4fd5922c25ed86d16564feedd273dee`. Role: test-path,source. Parse: module.

- run_test @9-11; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug317216.js

Blob: `cc10ef313e114d48389183c75bef07da793687e4`. Role: test-path,source. Parse: module.

- testCase @97-126; FunctionDeclaration; parameters=4; async=false; generator=false
- padBytes @131-137; FunctionDeclaration; parameters=1; async=false; generator=false
- padUnichars @139-145; FunctionDeclaration; parameters=1; async=false; generator=false
- flip @148-150; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @152-165; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://gre/modules/NetUtil.sys.mjs @12; ChromeUtils-import-literal

### intl/uconv/tests/unit/test_bug321379.js

Blob: `338f59688e743c122c58afb22b78c7306afc6aa7`. Role: test-path,source. Parse: module.

- run_test @4-35; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug340714.js

Blob: `fdd30543f2dd3674d967b9e62f78ac4f491ad97c`. Role: test-path,source. Parse: module.

- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- makeText @32-37; FunctionDeclaration; parameters=2; async=false; generator=false
- testCase @39-106; FunctionDeclaration; parameters=5; async=false; generator=false
- run_test @108-123; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://gre/modules/NetUtil.sys.mjs @14; ChromeUtils-import-literal

### intl/uconv/tests/unit/test_bug381412.Big5-HKSCS.js

Blob: `4108dc109089d0cf3c2c71a51cc19d218e340534`. Role: test-path,source. Parse: module.

- dumpStrings @3-18; FunctionDeclaration; parameters=2; async=false; generator=false
- error @20-23; FunctionDeclaration; parameters=3; async=false; generator=false
- run_test @25-64; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug381412.Big5.js

Blob: `45c8bafc83b28791ae102f926821bb9003edc353`. Role: test-path,source. Parse: module.

- dumpStrings @3-18; FunctionDeclaration; parameters=2; async=false; generator=false
- error @20-23; FunctionDeclaration; parameters=3; async=false; generator=false
- run_test @25-64; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug381412.euc-kr.js

Blob: `58d36c76f4d89959fde9df2a1de3f058fad6fe3f`. Role: test-path,source. Parse: module.

- dumpStrings @3-18; FunctionDeclaration; parameters=2; async=false; generator=false
- error @20-23; FunctionDeclaration; parameters=3; async=false; generator=false
- run_test @25-64; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug381412.euc_jp.js

Blob: `7e07eb9e69f97a92c7cf6e8026bfb4571372d7bc`. Role: test-path,source. Parse: module.

- error @8-24; FunctionDeclaration; parameters=3; async=false; generator=false
- test @26-74; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @76-92; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug381412.gb2312.js

Blob: `df680dadaec6c7997a8764f4bf15ad16fffa47e5`. Role: test-path,source. Parse: module.

- error @3-19; FunctionDeclaration; parameters=3; async=false; generator=false
- run_test @21-60; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug381412.js

Blob: `89849bf5e68c76de97f768b649459184fc74b59c`. Role: test-path,source. Parse: module.

- error @3-19; FunctionDeclaration; parameters=3; async=false; generator=false
- run_test @21-60; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug396637.js

Blob: `6aac53e5d10ba7f0bf79f602e0f8a1f8d443f7ac`. Role: test-path,source. Parse: module.

- run_test @7-9; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug399257.js

Blob: `9acd3e9b386e1ac322b918e16d4bf998ff35eb3d`. Role: test-path,source. Parse: module.

- run_test @5-80; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug457886.js

Blob: `21c303690163c9bec89d41dd3bec96d9ad82e669`. Role: test-path,source. Parse: module.

- run_test @10-12; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug522931.js

Blob: `2dae8d72e9f70a80df6ecc01a97d2d9c72330e17`. Role: test-path,source. Parse: module.

- run_test @2-4; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug563283.js

Blob: `49c13dcfcb4b48f1885560664812f1c2386c45fe`. Role: test-path,source. Parse: module.

- run_test @44-53; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug563618.js

Blob: `f2d8a6e353ccf6b2dacc0feffad059ea37cb1f3c`. Role: test-path,source. Parse: module.

- testCase @44-91; FunctionDeclaration; parameters=4; async=false; generator=false
- run_test @93-99; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://gre/modules/NetUtil.sys.mjs @7; ChromeUtils-import-literal

### intl/uconv/tests/unit/test_bug601429.js

Blob: `af5d357c50f04a35f14e775fc87f7f28fc8d2111`. Role: test-path,source. Parse: module.

- run_test @4-84; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug715319.dbcs.js

Blob: `3ba405a925c07983866a6a5f98e4110364cc095a`. Role: test-path,source. Parse: module.

- error @9-25; FunctionDeclaration; parameters=3; async=false; generator=false
- IsASCII @27-29; FunctionDeclaration; parameters=1; async=false; generator=false
- test @31-42; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @44-56; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug715319.euc_jp.js

Blob: `537d073d14580fe0d1e8ce5f2727c9f27e216ea8`. Role: test-path,source. Parse: module.

- error @8-24; FunctionDeclaration; parameters=3; async=false; generator=false
- IsASCII @26-28; FunctionDeclaration; parameters=1; async=false; generator=false
- IsNotGR @30-32; FunctionDeclaration; parameters=1; async=false; generator=false
- test @34-59; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @61-77; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_bug715319.gb2312.js

Blob: `f780ab81d178363865d9b3f87ad5dd3b7031f67c`. Role: test-path,source. Parse: module.

- error @8-24; FunctionDeclaration; parameters=3; async=false; generator=false
- IsASCII @26-28; FunctionDeclaration; parameters=1; async=false; generator=false
- test @30-63; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @65-87; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_charset_conversion.js

Blob: `edbc83b83c70055c493585f85c72b371a449532d`. Role: test-path,source. Parse: module.

- run_test @7-44; FunctionDeclaration; parameters=0; async=false; generator=false
- test_utf8_1 @71-87; FunctionDeclaration; parameters=0; async=false; generator=false
- test_cross_conversion @89-119; FunctionDeclaration; parameters=0; async=false; generator=false
- StorageStream @123-125; FunctionDeclaration; parameters=0; async=false; generator=false
- getUnicharInputStream @127-139; FunctionDeclaration; parameters=2; async=false; generator=false
- getBinaryInputStream @141-153; FunctionDeclaration; parameters=1; async=false; generator=false
- equalStreams @155-169; FunctionDeclaration; parameters=2; async=false; generator=false
- equalUnicharStreams @171-193; FunctionDeclaration; parameters=2; async=false; generator=false
- stringToCodePoints @195-199; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @196-198; FunctionExpression; parameters=1; async=false; generator=false
- lowbits @201-203; FunctionDeclaration; parameters=1; async=false; generator=false
- Pipe @205-207; FunctionDeclaration; parameters=0; async=false; generator=false
- UTF8 @217-219; FunctionDeclaration; parameters=1; async=false; generator=false
- readUnit @224-303; FunctionExpression; parameters=0; async=false; generator=false
- UTF16 @315-329; FunctionDeclaration; parameters=2; async=false; generator=false
- readUnit @333-372; FunctionExpression; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-1.js

Blob: `d820b35ca8ada129c8b57a7b7e1f5a8f80deb16a`. Role: test-path,source. Parse: module.

- run_test @24-26; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-10.js

Blob: `47e934817e27dc1bf5508a1d71b87b0c36040055`. Role: test-path,source. Parse: module.

- run_test @20-22; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-11.js

Blob: `b647ec503c37040be8fd5b39bc27baab55f90646`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-13.js

Blob: `91443e6bee166bbb8afbefef0c74cc2b2c3398a4`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-14.js

Blob: `d1fdcb204cdeb9127e6a054c049fb8b1dbc63451`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-15.js

Blob: `7344fb55a84128d41506823cd959ca48fe9a06fe`. Role: test-path,source. Parse: module.

- run_test @19-21; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-2.js

Blob: `0e3c15bdee6cd84d806ccf6837bcc19b97aa2984`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-3.js

Blob: `011f82de8729e5e5a92e98eb3b0274efb53f80b6`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-4.js

Blob: `6a8b89c2efe9e7d47084940a76d55a1a906842f9`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-5.js

Blob: `220a12ab3a436c944f3c885dd7dfd4b55acbf7c3`. Role: test-path,source. Parse: module.

- run_test @20-22; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-6.js

Blob: `9c94ef8673c0a5a24e6cb8a79464cd2c161f578a`. Role: test-path,source. Parse: module.

- run_test @23-25; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-7.js

Blob: `9d743423457bc755d07dd6cca399a32d330aca8a`. Role: test-path,source. Parse: module.

- run_test @25-27; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-8.js

Blob: `c7b758bf030e1825400f067d6e5ad8953b509ae7`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_8859-9.js

Blob: `1582e2093fb37d173f4cb729b666fb66d71ae1ed`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1250.js

Blob: `d044c6780132b5fd7d1dff2536292242f26556e6`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1251.js

Blob: `01153e86503b1a08739e575c1940e5ce9a1ba852`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1252.js

Blob: `d41d7d72a35a6617c614f039945089d3d9b43289`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1253.js

Blob: `880e2dae7440fdf310771a98754dbc5cc97ec0c8`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1254.js

Blob: `f4af7e2088b3d62e3d805b5e68b18639a5e15f6d`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1255.js

Blob: `57e1b54636e2a92e9b9066dd339d5f7f8d253a25`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1256.js

Blob: `b91e448a461cb6e7ba9c342840fef8b65f2b3305`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1257.js

Blob: `a61bf2e87057618906ee1c99db80bb09a13b3ee7`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP1258.js

Blob: `422e9a7985c9c36902e891edd11d36145c910c2b`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_CP874.js

Blob: `7f05e7669c518329b0bf7bbdd545f443ac340c22`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_gb18030.js

Blob: `ca5796bbaa4f5102fec7ebf9116b713e1a0b3863`. Role: test-path,source. Parse: module.

- run_test @14-16; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_gbk.js

Blob: `6e4414722d931e5e92b8a6d3b6a97ae82a3a1d7b`. Role: test-path,source. Parse: module.

- run_test @13-15; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_macintosh.js

Blob: `5504a630ec185c7eab8ceaee95bf00cf1f76cd36`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_x_mac_cyrillic.js

Blob: `ad783b0e964c7a6c01a5b5d2daa3556a8c281cb5`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_decode_x_mac_ukrainian.js

Blob: `b8b3d63018abadd11ae7197a0824a477438f4f3d`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-1.js

Blob: `f5a6559de17dcd635d9a4473629b340b96850d4d`. Role: test-path,source. Parse: module.

- run_test @24-26; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-10.js

Blob: `2ecad6013f8b2a961265931eae1ba908112ba2b0`. Role: test-path,source. Parse: module.

- run_test @20-22; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-11.js

Blob: `7011c266886c643b3c0fbd7ec4c3310bd878927c`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-13.js

Blob: `cf6ad98466d7b206b28d3850bbe54507724f4eca`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-14.js

Blob: `9a0e8dc00a5020d518240589a085aeb22e44bd7c`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-15.js

Blob: `ed5cd2ec90036e1eefe1cb2f70ec29c411f06b26`. Role: test-path,source. Parse: module.

- run_test @19-21; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-2.js

Blob: `1b34672bcb8ad9e22348e568bd99d3d716b79618`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-3.js

Blob: `fff62434319ae593b5bd403a292176a85e353631`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-4.js

Blob: `192d13fd52a9f71f881b20e56aedf6d5ec25f952`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-5.js

Blob: `fb2a05a6935600daa561984dc8aa6ce3e97a2b86`. Role: test-path,source. Parse: module.

- run_test @20-22; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-6.js

Blob: `1768b89d82ebf61e7eec509ad4e35d7a67d65217`. Role: test-path,source. Parse: module.

- run_test @23-25; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-7.js

Blob: `3452130e744394cd40d50511e7d23a1284ddac72`. Role: test-path,source. Parse: module.

- run_test @25-27; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-8.js

Blob: `12402dfb56f69f54b53fb411ec864900611938f0`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_8859-9.js

Blob: `7658ebe5ef3819fea4e84172f81592dfd5796a0b`. Role: test-path,source. Parse: module.

- run_test @22-24; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1250.js

Blob: `5b5c0d2f0a5687df1ab1139f60e3bdfdf05b5c82`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1251.js

Blob: `52d15d8731694868c412e6cdfc4a2c22b1ad7cf8`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1252.js

Blob: `2f997914081754699825b0c5c532b9928633aa3a`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1253.js

Blob: `a7ba34cb9faeeb42ff20b0498bf717f020b1106f`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1254.js

Blob: `593a33841ee2525f51a7bea098956b35952bc5e1`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1255.js

Blob: `6da4cd53a2fafa9fc0051b31d269c9937dc479ea`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1256.js

Blob: `c8fbbb6192fa8a053b77ba93b2a7a6f65ccf4fa9`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1257.js

Blob: `d56241ef881762e243fdfc58fe804782f8199ba2`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP1258.js

Blob: `e60a2f79ba6c29ee1452b60747f70a315b7ee1df`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_CP874.js

Blob: `18158ef7e1e0df71aed9ef3560c2ea808ab4033d`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_gb18030.js

Blob: `c080e67535a6e6af0bb659a8309ae3804c9433f8`. Role: test-path,source. Parse: module.

- run_test @13-15; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_gbk.js

Blob: `50763b9dabd9774211bfed19d8ea7add3c40329e`. Role: test-path,source. Parse: module.

- run_test @13-15; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_macintosh.js

Blob: `949d0aaf7ca7c2b16ca69db61b1104ef84a13e55`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_encode_x_mac_cyrillic.js

Blob: `ac27c57cc48c0e718a2029fb6114bb39c24ba2b8`. Role: test-path,source. Parse: module.

- run_test @11-13; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_input_stream.js

Blob: `b33fb98356fc45c1d774b07b2be95bc38d9176f9`. Role: test-path,source. Parse: module.

- test_char @13-25; FunctionDeclaration; parameters=1; async=false; generator=false
- run_test @27-41; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_unEscapeNonAsciiURI.js

Blob: `f4479592444de601f61f392a05d7d41834b62c90`. Role: test-path,source. Parse: module.

- run_test @2-58; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_unEscapeURIForUI.js

Blob: `7f2fb167ccdd88aac1a3a9e39061d7b2ce7dfd12`. Role: test-path,source. Parse: module.

- run_test @2-23; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_unmapped.js

Blob: `13ee13c20ecd717dd5eebad5c9b500deda587952`. Role: test-path,source. Parse: module.

- run_test @5-86; FunctionDeclaration; parameters=0; async=false; generator=false

### intl/uconv/tests/unit/test_utf8_illegals.js

Blob: `e2ceb2665031460ad4661291dbbe33b76900ad0d`. Role: test-path,source. Parse: module.

- testCaseInputStream @119-156; FunctionDeclaration; parameters=2; async=false; generator=false
- run_test @158-164; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://gre/modules/NetUtil.sys.mjs @5; ChromeUtils-import-literal

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
