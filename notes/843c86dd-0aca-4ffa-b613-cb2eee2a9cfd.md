<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["90eeb501a80050e73f36d6099c259201b7fa5bf8749474cd1fed2a0895a4d281"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/ebc146d5-2e1d-4a02-8310-45d97b8c2e7a.md"}} -->
# firefox/testing JavaScript function map 809

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/third_party/test262/test/annexB/language/expressions/template-literal/legacy-octal-escape-sequence-strict.js

Blob: `30aa313347952831e7b019bf165d0e83acdb2580`. Role: imported-path,test-path,source. Parse: script.


### testing/web-platform/tests/third_party/test262/test/annexB/language/expressions/typeof/emulates-undefined.js

Blob: `34b4a17e4e544db9d9c1534585be3a50c6ab7638`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/annexB/language/expressions/yield/star-iterable-return-emulates-undefined-throws-when-called.js

Blob: `272e180527c81a30c2b644f863ad232e3893c976`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false
- next @16-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=true
- (anonymous) @24-31; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/expressions/yield/star-iterable-throw-emulates-undefined-throws-when-called.js

Blob: `219aef8a57efcebaac7f297595bc8f366eb59f12`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @27-27; FunctionExpression; parameters=0; async=false; generator=false
- next @28-28; FunctionExpression; parameters=0; async=false; generator=false
- return @30-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; FunctionExpression; parameters=0; async=false; generator=true
- (anonymous) @39-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-block-scoping.js

Blob: `921f952330b88eca13f2f56c987e5830b86c41ff`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-37; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-block-fn-no-init.js

Blob: `d978ac52907b657903be34db4fab653fd5da5bd3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-29; FunctionExpression; parameters=0; async=false; generator=false
- f @21-21; FunctionDeclaration; parameters=0; async=false; generator=false
- f @25-25; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-block-fn-update.js

Blob: `c471951fd2386ead647f09bad26092b2ea376429`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-37; FunctionExpression; parameters=0; async=false; generator=false
- f @27-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-fn-no-init.js

Blob: `30f5ace2e6de9a8c37cd3635e9685186d1b93351`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-27; FunctionExpression; parameters=0; async=false; generator=false
- f @21-21; FunctionDeclaration; parameters=0; async=false; generator=false
- f @24-26; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-fn-update.js

Blob: `5e9171862c249b6c121a2254ade0aaa3722ed57d`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-37; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @34-36; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-var-no-init.js

Blob: `4f88007a8e022132b26a91cdc2f245ad1489c35e`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-26; FunctionExpression; parameters=0; async=false; generator=false
- f @22-22; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-existing-var-update.js

Blob: `b342cec491673eb140890d4d393a99f544b15c22`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-35; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-init.js

Blob: `f87480eea573da292be17cd38d2b640cf556298b`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-30; FunctionExpression; parameters=0; async=false; generator=false
- f @26-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-no-skip-try.js

Blob: `9ef62ab3e34a83b018df989c9aae07d7f9dab125`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-49; FunctionExpression; parameters=0; async=false; generator=false
- f @38-38; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-arguments.js

Blob: `c90306cd5c0ddd14dab1374ab0ff70863ade24d5`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-35; FunctionExpression; parameters=0; async=false; generator=false
- arguments @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @38-46; FunctionExpression; parameters=1; async=false; generator=false
- arguments @42-42; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @49-57; FunctionExpression; parameters=1; async=false; generator=false
- arguments @53-53; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-dft-param.js

Blob: `de796b08f0a6cbd85d9d7832e68751f83c66be63`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-27; FunctionExpression; parameters=1; async=false; generator=false
- f @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-block.js

Blob: `4232e6d3b12b75e4704e45f4512b0f9e36c7ff93`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-for-in.js

Blob: `afa222b5dcbf52316977497a94649cf09ecfb0d4`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-for-of.js

Blob: `4f97af8a48f8e4eb35a3afa6588070adcbaf6100`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-for.js

Blob: `50bfb7a0d5cfcdf3e545b5c03152f054d4f56a07`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-switch.js

Blob: `c32cdef5c11e4fa7d00fb1df5104afd985af7b9a`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err-try.js

Blob: `999dcd77a05be1b0336bc55926df5057b763dce9`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-56; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=0; async=false; generator=false
- f @43-43; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-early-err.js

Blob: `4398e9401a92b8d2d12559e8c9104083442b93ea`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-28; FunctionExpression; parameters=0; async=false; generator=false
- f @24-24; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-skip-param.js

Blob: `7df8c07bd1744f99aaf00685161e9ed3cc832116`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-27; FunctionExpression; parameters=1; async=false; generator=false
- f @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-func-update.js

Blob: `654b027ad59900ea469645ce14b3f3a9e449cbdc`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-33; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-nested-blocks-with-fun-decl.js

Blob: `d3fc1274ba5ff8b14558cf0da706c88b5110a688`. Role: imported-path,test-path,source. Parse: module.

- g @22-38; FunctionDeclaration; parameters=0; async=false; generator=false
- f @27-27; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/block-decl-nostrict.js

Blob: `9ac8aad8239c82cc716b85f4f77cec01513c7130`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-35; FunctionExpression; parameters=0; async=false; generator=false
- f @27-27; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/function-redeclaration-block.js

Blob: `ae40db9f619f69555de4a5e9a3602cd3128bca7c`. Role: imported-path,test-path,source. Parse: script.

- a @18-18; FunctionDeclaration; parameters=0; async=false; generator=false
- a @18-18; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/function-redeclaration-switch.js

Blob: `1970859bc297d55eb45c483281709088003021bb`. Role: imported-path,test-path,source. Parse: script.

- a @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- a @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-block-scoping.js

Blob: `779dda0ffdd3bbbee5a9d8ffbe66a95166eef50e`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-44; FunctionExpression; parameters=0; async=false; generator=false
- _f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-block-fn-no-init.js

Blob: `ed262aaed91cdfd4bd3d9e3bc0d467f77df46f9a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-block-fn-update.js

Blob: `82f6c9ea1aff315928f2511180904704cf76a483`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @36-38; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-fn-no-init.js

Blob: `b753e76222c50952fb6d2e1e82c864ae8923070d`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-34; FunctionExpression; parameters=0; async=false; generator=false
- _f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-fn-update.js

Blob: `fe5f69deb1f6035356ec3adbf847ea158a1119af`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-43; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-var-no-init.js

Blob: `6c0de80c597f1165549cd689d51f42d4323fa6fd`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-33; FunctionExpression; parameters=0; async=false; generator=false
- _f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-existing-var-update.js

Blob: `a553e028b1466d847dfbdc3a50088f0d487edcd1`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-42; FunctionExpression; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-init.js

Blob: `5af4a64f167a411742b97b56ea9f9cbe01762cf6`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @29-37; FunctionExpression; parameters=0; async=false; generator=false
- _f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-no-skip-try.js

Blob: `116556ec8e529beea0e135bba723e2ac40100a8f`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-56; FunctionExpression; parameters=0; async=false; generator=false
- _f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false
- f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-dft-param.js

Blob: `962b5bc25136d6626b023e5c7a16ade18c9d8007`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- _f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-block.js

Blob: `bbab78eb61dc8fb31c76b50c21966ca40a8cecf8`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- _f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-for-in.js

Blob: `0e0a8647bfe7412c791c149c04b064b948e28043`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-for-of.js

Blob: `7466fc98403451bcc2e2a75ca84981ae1bcf558f`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-for.js

Blob: `da3a2afd88c564a75f7423c1e48ed6d176799f1a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-switch.js

Blob: `9e9f65790f8e7e25ff9af0fc95d0e6094e2c7f36`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- _f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err-try.js

Blob: `3cc92b4d826575619a48a4e05731d89f6e9aaa29`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- _f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-early-err.js

Blob: `680920e7b81f72b79830d0f5f6fc20946908f4be`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-35; FunctionExpression; parameters=0; async=false; generator=false
- _f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-skip-param.js

Blob: `b1de048a0013d56eaf16751b5681687bf1bdaf43`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- _f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-a-func-update.js

Blob: `8bd72b996b4096081857633eb3552f0fe54312e7`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-40; FunctionExpression; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-block-scoping.js

Blob: `272b22b96733a10f62fe71fc35c203dea1a5ebf2`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-44; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-block-fn-no-init.js

Blob: `5b511416a39cbf95c8cd91273052f8e5c389b04b`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-block-fn-update.js

Blob: `2d0c12666ad20d13a826117ebb79c046bec8847d`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @36-38; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-fn-no-init.js

Blob: `6525470cec7e1a3ab5f633a9840e9f7c0a7bdaae`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-34; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-fn-update.js

Blob: `9c911066ef2bd56c0d8df27023f530af52ca46c4`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-43; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-var-no-init.js

Blob: `4e179f44e1283e03b2345589f497cc87822319a2`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-33; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-existing-var-update.js

Blob: `e3fc8d4fd57603c46dcafdb83b831cd9b372318f`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-42; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-init.js

Blob: `5615c7d214b9a772427fa251a4bb4f4d7b898e0a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @29-37; FunctionExpression; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-no-skip-try.js

Blob: `3d147795217794c18db1f435334ef123f5417510`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-56; FunctionExpression; parameters=0; async=false; generator=false
- f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-dft-param.js

Blob: `f5fb84041dee133a2544935ed6814a632a83c255`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-block.js

Blob: `30ed4cfe399148736ec703ffed7d25eac34f3240`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-for-in.js

Blob: `dedb95dea8a0dbb94c76c53acb3c7cadeba4487d`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-for-of.js

Blob: `ea6cebf7d23e029221403099a1825f0e70b83d6b`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-for.js

Blob: `55642ba1e86919ccc2e270236066ee73b454bd2a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-switch.js

Blob: `6f3f8829911f0a578766c3fedf2d13bebc270fa9`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err-try.js

Blob: `e8c9966c0f21da7561f62f6493f245e0198ed672`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-early-err.js

Blob: `50855602ec52649fcf7e74219dff9d0d7f095d1d`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-35; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-skip-param.js

Blob: `8305d38c7b05016a898db0b1ba3c90d48ce5dd9a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-decl-b-func-update.js

Blob: `2a8647d23735f42a0d96a0588fe6bebf1ff441f2`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-40; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- _f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-block-scoping.js

Blob: `2c5412878f424609c67e75d3938f12f5fe5a4701`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-44; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-block-fn-no-init.js

Blob: `e0906c6ca56738a7137ec6823c1fa16f803eed01`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-block-fn-update.js

Blob: `d9a0dd10b9d5d788ba2103f8803cf66293e84afd`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @36-38; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-fn-no-init.js

Blob: `c17092b319ab7896fc550b757ca3cac46df14b2b`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-34; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-fn-update.js

Blob: `ae8c341a06f5d5c7a67e6529edfedcf64dd46504`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-43; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-var-no-init.js

Blob: `471235e65f4d2f24eef94e8916ba76e8b280d6e9`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-33; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-existing-var-update.js

Blob: `c203f7074fd66fc509895d96ceb8239e9e1657f7`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-42; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-init.js

Blob: `b4e5af873f09f8afcc5abaf6304b9923e5bfec56`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @29-37; FunctionExpression; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-no-skip-try.js

Blob: `a062708b21d317461b1d021d2503424d7611b27e`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-56; FunctionExpression; parameters=0; async=false; generator=false
- f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-dft-param.js

Blob: `b5084dbbf60397990d38bf629d61e17ad648a8dc`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-block.js

Blob: `7b0a374fdd739d8e3a6e5dfb3c7f56d9f16a4907`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-for-in.js

Blob: `153290071a44fcbd077eeff141aea8d1b2aec776`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-for-of.js

Blob: `e7f8682be7774ab1ccc5b9b4b01dfd8aa44a30f7`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-for.js

Blob: `222b58d0e0ed9dbac2ba21f0ff41be26cce96bc9`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-switch.js

Blob: `ca46eeffc44b857da95cd7154f7de46075c82c22`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err-try.js

Blob: `5194cca30030f211d2db3a1077d409dc6c53f03f`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-early-err.js

Blob: `0868a357133eb014a5e9609a139efc5a5b75f476`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-35; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-skip-param.js

Blob: `3f13c11689590c53214393ad185cc7944c5537d8`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-else-stmt-func-update.js

Blob: `2831d66bfb0a3e224a4de8b8cc0949fa79c698b1`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-40; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-block-scoping.js

Blob: `ed63305da6eabd58824079b5fcfc8ee56cde9537`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-44; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-block-fn-no-init.js

Blob: `2926ec300c39dd0866a4d8905fc9f6c988c6c4f0`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-block-fn-update.js

Blob: `b9b33df2d784bef37caea015b88e710bdbe1becf`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @36-38; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-fn-no-init.js

Blob: `0db68f821f5e07c293301298dc7e7fb954e20522`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-34; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-fn-update.js

Blob: `eec1d5c05a40a753290ce68f592ec303fd0982bd`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-43; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-var-no-init.js

Blob: `8e9ead866a2c7b1b7bde9ef01ab96d9c414d4e42`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-33; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-existing-var-update.js

Blob: `48ff60e0b8cbc566a4e7437d3a35fe3cf4fa36cc`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-42; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-init.js

Blob: `0b7e22a135ccdec16a0d397ea8cb9cbe30a5ecaa`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @29-37; FunctionExpression; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-no-skip-try.js

Blob: `84359fef3976d9aed1a465b61afa7e18fee8441a`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-56; FunctionExpression; parameters=0; async=false; generator=false
- f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-dft-param.js

Blob: `bf64090470c241d2db73d117c6524a44904cce64`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-block.js

Blob: `e1a134faea2523f8511d8d628d49dcd71749af5e`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-for-in.js

Blob: `908ebb85e1e59983127e4be2fd974bb2afdca030`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-for-of.js

Blob: `9ec5a66e427af94f518eff9f62bcb27305061951`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-for.js

Blob: `1ee913d6dd02b1aaee1271db856c63b2f192608e`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-switch.js

Blob: `871fad07f365cee0891a98e5dfe273f932bcb17e`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err-try.js

Blob: `d57c42aa70e893e7a595a484aad85815408bbe11`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-early-err.js

Blob: `57f9160f42edea0439409cf86420d2953d265df4`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-35; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-skip-param.js

Blob: `8076167c8671e93404e61c8e64a3d321aa2f31a9`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-decl-no-else-func-update.js

Blob: `9773a95e0a4d82681cba221863e3e2526bbefe2d`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-40; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-block-scoping.js

Blob: `44544d98e7970057a4771106ffbaaa0caa1bc827`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-44; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-block-fn-no-init.js

Blob: `10ea7aef6ac3b47247307eb30c50066e3dcea5e3`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-block-fn-update.js

Blob: `3d9e6bdaa815751086f97eb8ecce6fca4fa643f8`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @36-38; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-fn-no-init.js

Blob: `ada56d4b3c4f4d0df9653ade35bbb88fd7653c46`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-34; FunctionExpression; parameters=0; async=false; generator=false
- f @29-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @31-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-fn-update.js

Blob: `20235da6a33f029b3b0db25946401d975365c5e4`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false
- f @41-43; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-var-no-init.js

Blob: `01cfdc00e7a7ef291833b2a89181d0ad30556462`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @26-33; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-existing-var-update.js

Blob: `6e8ade6e7182b14c445c519d77cac9f969002b95`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-42; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-init.js

Blob: `13823932cfa9a10ce5672d75d9cd6e41181e05d8`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @29-37; FunctionExpression; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-no-skip-try.js

Blob: `7b804bc177bdfe880042d79a81ff6b60a078c943`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-56; FunctionExpression; parameters=0; async=false; generator=false
- f @46-46; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-dft-param.js

Blob: `28594bd434839ef5d44798ef095cf4c0422be532`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-block.js

Blob: `2376885f62eb2847ee1de9fc61c85cc2a3e62671`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @40-40; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-for-in.js

Blob: `5c59d28e42131992ab9c8ed8c5995eab2fe2967b`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-for-of.js

Blob: `ccecc68781fbcceb3b610c94487df0b02d79cfa6`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-for.js

Blob: `8c5fe82f52843324af02d0d608f1e63b9ac18ce3`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-switch.js

Blob: `5f13333d75f925ae683f4c7c195bbebda7f13112`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @27-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- f @41-41; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err-try.js

Blob: `8481795e5671f4c05ec0fc7ae9439b0b84c65a48`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @37-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- f @51-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-early-err.js

Blob: `171f8cfd0cefd474753c86e3f21c9e570e558aa8`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-35; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-skip-param.js

Blob: `c5ab2620d2343ab629d92ae43c741b0ad67ca965`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- f @31-31; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/if-stmt-else-decl-func-update.js

Blob: `1ff55e7405faa43623a7df2c405d58c7cbc6b402`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @34-40; FunctionExpression; parameters=0; async=false; generator=false
- f @37-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-decl-nostrict.js

Blob: `6be9587e095017bcb85c0fc4eec949c51371a2c3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-36; FunctionExpression; parameters=0; async=false; generator=false
- f @28-28; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-block-scoping.js

Blob: `c7c3d5610790aaf781b821c76d1d1936101b8d76`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-38; FunctionExpression; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-block-fn-no-init.js

Blob: `12436b651a7c1a97adfd3592b0b59172bd4fe328`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-30; FunctionExpression; parameters=0; async=false; generator=false
- f @21-21; FunctionDeclaration; parameters=0; async=false; generator=false
- f @26-26; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-block-fn-update.js

Blob: `9207cc893df4e513332c1aa26efe164f33f7605c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-38; FunctionExpression; parameters=0; async=false; generator=false
- f @27-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-fn-no-init.js

Blob: `e1c5dedbeba6f71ceba4f2f346ebae0cf19a4203`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-28; FunctionExpression; parameters=0; async=false; generator=false
- f @22-22; FunctionDeclaration; parameters=0; async=false; generator=false
- f @25-27; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-fn-update.js

Blob: `64d37a4b14d514b3f0ff149d3eb0e39fdbc2df50`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-38; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @35-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-var-no-init.js

Blob: `719ca419b9a925fc3390978d5eabaf52ebef7ac0`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-27; FunctionExpression; parameters=0; async=false; generator=false
- f @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-existing-var-update.js

Blob: `a51d8c604449beeb701606f4ccd73f17d7fb771e`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-36; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-init.js

Blob: `637fc0bded3aaafa2aa4681826b4206b99978fcb`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-31; FunctionExpression; parameters=0; async=false; generator=false
- f @27-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-no-skip-try.js

Blob: `a8e427435c993098be145877cfe3eb4e0ae40ba7`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-50; FunctionExpression; parameters=0; async=false; generator=false
- f @39-39; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-dft-param.js

Blob: `b394083b38cb236a93804165fdba0ae37f065068`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-28; FunctionExpression; parameters=1; async=false; generator=false
- f @24-24; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-block.js

Blob: `12935a18cb2538545c938e716d3cf8192a02e0b0`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-for-in.js

Blob: `fd6bd8fa1201cd71611b7d510256756cc8fe72ee`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-for-of.js

Blob: `74d165fffc9a1be0781e42aefe8c0cde6e17b2ef`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-for.js

Blob: `3fdcde35fea63fc414c9caa9078e65c60ad8484d`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @32-32; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-switch.js

Blob: `0ec1e2d8013d19997517634d8d249af338497ab8`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err-try.js

Blob: `a3ea8e95b50b566b2ec4c7f6561d326ae1032cfd`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-57; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=0; async=false; generator=false
- f @44-44; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @49-51; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-early-err.js

Blob: `abe24defd0c7c98c723cca873dc041fc89fa2c0b`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-29; FunctionExpression; parameters=0; async=false; generator=false
- f @25-25; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-skip-param.js

Blob: `7d013b251a0a647f5eb042569f4916f07cace338`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-28; FunctionExpression; parameters=1; async=false; generator=false
- f @24-24; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-case-func-update.js

Blob: `2733e73d47a8b45912b49aeeb68ba58c1b349728`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-34; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-decl-nostrict.js

Blob: `9b66c97a8f89ff7d2e439fadfbda5e68bd7e876b`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-36; FunctionExpression; parameters=0; async=false; generator=false
- f @28-28; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-block-scoping.js

Blob: `eb54833bdd892849f2cfdfb25e4a553266ffdff6`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @28-38; FunctionExpression; parameters=0; async=false; generator=false
- f @33-33; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-existing-block-fn-no-init.js

Blob: `8925fab956a10310be45d364bafca9b9ce1938e5`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-30; FunctionExpression; parameters=0; async=false; generator=false
- f @21-21; FunctionDeclaration; parameters=0; async=false; generator=false
- f @26-26; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-existing-block-fn-update.js

Blob: `4a28093047b6b6860f9b388c05d7203eeb1d3c24`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-38; FunctionExpression; parameters=0; async=false; generator=false
- f @27-29; FunctionDeclaration; parameters=0; async=false; generator=false
- f @34-34; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-existing-fn-no-init.js

Blob: `781289ecc85020679ec4732aebf02348bc5a4a83`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-28; FunctionExpression; parameters=0; async=false; generator=false
- f @22-22; FunctionDeclaration; parameters=0; async=false; generator=false
- f @25-27; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-existing-fn-update.js

Blob: `50a946675cd2ea65e2ad1f16aeb9aab529c002bf`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @25-38; FunctionExpression; parameters=0; async=false; generator=false
- f @30-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f @35-37; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/annexB/language/function-code/switch-dflt-func-existing-var-no-init.js

Blob: `a3db19d45d6f8d25c748ec91e25282e68366f311`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-27; FunctionExpression; parameters=0; async=false; generator=false
- f @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [ebc146d5-2e1d-4a02-8310-45d97b8c2e7a.md](ebc146d5-2e1d-4a02-8310-45d97b8c2e7a.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `90eeb501a80050e73f36d6099c259201b7fa5bf8749474cd1fed2a0895a4d281`.
