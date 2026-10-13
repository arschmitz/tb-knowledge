<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["d982508cf81dab5fa077685e7753bbe71f55db117804d1368ecef0c86a1f8eb2"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/7eb86fed-25a3-46cd-90d8-cd5afc753604.md"}} -->
# firefox/js JavaScript function map 647

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/test262/language/statements/class/elements/static-as-valid-static-field.js

Blob: `88f818f28c210708434222aaa8fa7cf56390aaa4`. Role: test-path,source. Parse: module.

- Class C @18-20

### js/src/tests/test262/language/statements/class/elements/static-comp-name-init-err-contains-arguments.js

Blob: `eff2ee5b0a5fd5e17c872bfca3e921e6da98ed8a`. Role: test-path,source. Parse: failed.

Failure: Cannot use 'arguments' in class field initializer


### js/src/tests/test262/language/statements/class/elements/static-comp-name-init-err-contains-super.js

Blob: `8ea327730ff2fa0ffa3442f1b1b9f2f0025941c1`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/static-field-anonymous-function-length.js

Blob: `17c4b304b24fed2ce1c095c6b819b339e00d2716`. Role: test-path,source. Parse: module.

- field @51-51; ArrowFunctionExpression; parameters=2; async=false; generator=false
- field @52-52; FunctionExpression; parameters=0; async=false; generator=false
- accessPrivateField @54-56; FunctionExpression; parameters=0; async=false; generator=false
- Class C @50-58

### js/src/tests/test262/language/statements/class/elements/static-field-anonymous-function-name.js

Blob: `9fe93ca1569b1afe76b759a6b201a8b6f002d91f`. Role: test-path,source. Parse: module.

- field @60-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- field @61-61; FunctionExpression; parameters=0; async=false; generator=false
- accessPrivateField @63-65; FunctionExpression; parameters=0; async=false; generator=false
- Class C @59-67

### js/src/tests/test262/language/statements/class/elements/static-field-declaration.js

Blob: `3bdd8ae3e39f3244c9212d971645fff55eb51127`. Role: test-path,source. Parse: module.

- Class C @73-78

### js/src/tests/test262/language/statements/class/elements/static-field-init-this-inside-arrow-function.js

Blob: `e10becfcc23e9d4c7e9e88c617d8243a237cc6d0`. Role: test-path,source. Parse: module.

- f @60-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class C @59-61

### js/src/tests/test262/language/statements/class/elements/static-field-init-with-this.js

Blob: `17541878f8b4c45a0601fb5544e58c2c11ec0356`. Role: test-path,source. Parse: module.

- Class C @59-63

### js/src/tests/test262/language/statements/class/elements/static-field-initializer-error.js

Blob: `e15ee8a192ff890bb3320533244e08f075db8906`. Role: test-path,source. Parse: module.

- initThrows @47-49; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @51-58; FunctionExpression; parameters=0; async=false; generator=false
- Class C @52-55

### js/src/tests/test262/language/statements/class/elements/static-field-redeclaration.js

Blob: `8dc0da889a6e0a32cc6112b50e9f6528052eff53`. Role: test-path,source. Parse: module.

- g @62-64; FunctionExpression; parameters=0; async=false; generator=false
- Class C @59-66

### js/src/tests/test262/language/statements/class/elements/static-fielddefinition-initializer-abrupt-completion.js

Blob: `c5985614d713a13162021725a0113b65d85296f3`. Role: test-path,source. Parse: module.

- f @25-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false
- Class C @30-32

### js/src/tests/test262/language/statements/class/elements/static-literal-init-err-contains-arguments.js

Blob: `5cd22121010626dfd79027c0fa0d35cd4028692d`. Role: test-path,source. Parse: failed.

Failure: Cannot use 'arguments' in class field initializer


### js/src/tests/test262/language/statements/class/elements/static-literal-init-err-contains-super.js

Blob: `562c076edc0a974da87e5b72fc6ad5a1f2d8ce89`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/static-private-fields-proxy-default-handler-throws.js

Blob: `8752878264832edf99d49bc0590fd2b72cdda7a4`. Role: test-path,source. Parse: module.

- x @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- Class C @16-21

### js/src/tests/test262/language/statements/class/elements/static-private-getter-access-on-inner-arrow-function.js

Blob: `d316074af081461b028dc4837237a630b502602f`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=0; async=false; generator=false
- access @32-38; FunctionExpression; parameters=0; async=false; generator=false
- arrowFunction @33-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-39

### js/src/tests/test262/language/statements/class/elements/static-private-getter-access-on-inner-class.js

Blob: `5242a5170ee60c1ee0250b011c045eeeaeedf790`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=0; async=false; generator=false
- access @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-37
- Class (anonymous) @32-36

### js/src/tests/test262/language/statements/class/elements/static-private-getter-access-on-inner-function.js

Blob: `f1556f68b0a3c653ad03bd70734d079436e55805`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=0; async=false; generator=false
- access @32-40; FunctionExpression; parameters=0; async=false; generator=false
- innerFunction @35-37; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-41

### js/src/tests/test262/language/statements/class/elements/static-private-getter.js

Blob: `cf40d3fd0ea6f47151661a985c427b75086f8f8f`. Role: test-path,source. Parse: module.

- f @43-45; FunctionExpression; parameters=0; async=false; generator=false
- access @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-55; FunctionExpression; parameters=0; async=false; generator=false
- Class C @42-50

### js/src/tests/test262/language/statements/class/elements/static-private-init-err-contains-arguments.js

Blob: `30ee50c85572407263e8aa0c8c0c2d929a0bf3f3`. Role: test-path,source. Parse: failed.

Failure: Cannot use 'arguments' in class field initializer


### js/src/tests/test262/language/statements/class/elements/static-private-init-err-contains-super.js

Blob: `114c6d710944ce3ae375cce2231ec68060fa369f`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/static-private-method-access-on-inner-arrow-function.js

Blob: `2145cefe5a96d6166288ebd63170d2bc24593dc5`. Role: test-path,source. Parse: module.

- f @28-28; FunctionExpression; parameters=0; async=false; generator=false
- g @29-35; FunctionExpression; parameters=0; async=false; generator=false
- arrowFunction @30-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-37

### js/src/tests/test262/language/statements/class/elements/static-private-method-access-on-inner-function.js

Blob: `7e4d1b3a4a1b36b8d796e31b589e28d398db78d5`. Role: test-path,source. Parse: module.

- f @28-28; FunctionExpression; parameters=0; async=false; generator=false
- g @29-37; FunctionExpression; parameters=0; async=false; generator=false
- innerFunction @32-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-39

### js/src/tests/test262/language/statements/class/elements/static-private-method-and-instance-method-brand-check.js

Blob: `21a112a88ca99defb8f9e6ca2cd17dd50bffbc16`. Role: test-path,source. Parse: module.

- f @36-38; FunctionExpression; parameters=0; async=false; generator=false
- access @40-42; FunctionExpression; parameters=0; async=false; generator=false
- instanceMethod @44-46; FunctionExpression; parameters=0; async=false; generator=false
- instanceAccess @48-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-59; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-63; FunctionExpression; parameters=0; async=false; generator=false
- Class C @35-51

### js/src/tests/test262/language/statements/class/elements/static-private-method-referenced-from-instance-method.js

Blob: `380b6409a7bd51c03da9079cff0b2f92e680c7d3`. Role: test-path,source. Parse: module.

- f @28-28; FunctionExpression; parameters=0; async=false; generator=false
- g @29-31; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-33

### js/src/tests/test262/language/statements/class/elements/static-private-method-subclass-receiver.js

Blob: `cf7c904247c9d0845fdb4c53b4c3a1e4f352a904`. Role: test-path,source. Parse: module.

- f @28-28; FunctionExpression; parameters=0; async=false; generator=false
- g @29-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false
- Class D @33-33
- Class C @27-31

### js/src/tests/test262/language/statements/class/elements/static-private-setter-access-on-inner-arrow-function.js

Blob: `224f85738b02b9ec33c244f0a5a5e1389aeeaea7`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=1; async=false; generator=false
- access @32-38; FunctionExpression; parameters=0; async=false; generator=false
- arrowFunction @33-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-39

### js/src/tests/test262/language/statements/class/elements/static-private-setter-access-on-inner-class.js

Blob: `77fcb12d4ed31528febb5e2742ead89dcc44ef98`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=1; async=false; generator=false
- access @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-38
- Class (anonymous) @32-36

### js/src/tests/test262/language/statements/class/elements/static-private-setter-access-on-inner-function.js

Blob: `3781181dd72db6cec989bfad2e530bab6e5682c7`. Role: test-path,source. Parse: module.

- f @28-30; FunctionExpression; parameters=1; async=false; generator=false
- access @32-40; FunctionExpression; parameters=0; async=false; generator=false
- innerFunction @35-37; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- Class C @27-41

### js/src/tests/test262/language/statements/class/elements/static-private-setter.js

Blob: `c39699206f286870da6248b1aa3c585d007913b5`. Role: test-path,source. Parse: module.

- f @43-45; FunctionExpression; parameters=1; async=false; generator=false
- access @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-56; FunctionExpression; parameters=0; async=false; generator=false
- Class C @42-50

### js/src/tests/test262/language/statements/class/elements/static-string-literal-name-init-err-contains-arguments.js

Blob: `9be6b180256e54b68b368c0c5d0e3034e8d09f45`. Role: test-path,source. Parse: failed.

Failure: Cannot use 'arguments' in class field initializer


### js/src/tests/test262/language/statements/class/elements/static-string-literal-name-init-err-contains-super.js

Blob: `6cbe221dcc39c483cfd8f5ca0759b5247a8e3762`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/string-literal-name-init-err-contains-arguments.js

Blob: `efdb64b913985b4f2c64ab1be9fc087251b1d34a`. Role: test-path,source. Parse: failed.

Failure: Cannot use 'arguments' in class field initializer


### js/src/tests/test262/language/statements/class/elements/string-literal-name-init-err-contains-super.js

Blob: `d5bc2d2ddb0dfc9b084f5e0c331cd89a3c7a78e1`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/super-access-from-arrow-func-on-field.js

Blob: `39b381e1ea8086ea3964c65df4b9479fb984230a`. Role: test-path,source. Parse: module.

- func @22-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- staticFunc @26-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class C @21-29

### js/src/tests/test262/language/statements/class/elements/super-access-inside-a-private-getter.js

Blob: `72cb666ec7a9b2ca05adedcaf62b6aeb2eaf91c2`. Role: test-path,source. Parse: module.

- method @34-36; FunctionExpression; parameters=0; async=false; generator=false
- m @40-42; FunctionExpression; parameters=0; async=false; generator=false
- access @44-46; FunctionExpression; parameters=0; async=false; generator=false
- Class C @39-47
- Class A @33-37

### js/src/tests/test262/language/statements/class/elements/super-access-inside-a-private-method.js

Blob: `df4478828f2c3b69bc9abd126304d5224a6f73fb`. Role: test-path,source. Parse: module.

- method @31-33; FunctionExpression; parameters=0; async=false; generator=false
- m @37-39; FunctionExpression; parameters=0; async=false; generator=false
- access @41-43; FunctionExpression; parameters=1; async=false; generator=false
- Class C @36-44
- Class A @30-34

### js/src/tests/test262/language/statements/class/elements/super-access-inside-a-private-setter.js

Blob: `3a95d15c89926d2bea401c6d72d3ed3895f64e07`. Role: test-path,source. Parse: module.

- method @33-35; FunctionExpression; parameters=1; async=false; generator=false
- m @39-41; FunctionExpression; parameters=1; async=false; generator=false
- access @43-45; FunctionExpression; parameters=0; async=false; generator=false
- Class C @38-46
- Class A @32-36

### js/src/tests/test262/language/statements/class/elements/super-fielddefinition-initializer-abrupt-completion.js

Blob: `f19282782fd66e242108892362f2fac01583c8cf`. Role: test-path,source. Parse: module.

- f @40-42; FunctionDeclaration; parameters=0; async=false; generator=false
- constructor @49-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-56; FunctionExpression; parameters=0; async=false; generator=false
- Class C @48-52
- Class A @44-46

### js/src/tests/test262/language/statements/class/elements/syntax/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/class-heritage-array-literal-arrow-heritage.js

Blob: `725572fa813bea6988df1968280de524bf1e800c`. Role: test-path,source. Parse: failed.

Failure: Unexpected token )


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/class-heritage-array-literal-async-arrow-heritage.js

Blob: `64b65965edccd759cbbb7367e8c799cd9cde6b1f`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =>


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method-accessor-get.js

Blob: `048f87ae90a8ca8f70e7c82bad9c2719753ac154`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method-accessor-set.js

Blob: `f1e82d42421ac2f13516847eacddce01baa20d82`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method-async-gen.js

Blob: `c01c57926d9ba2368a5c91afed79a6439cfb62f1`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method-async.js

Blob: `b1680d7470eb14e8cb70bf99494f714b96ff2b44`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method-gen.js

Blob: `8bc33c89ba6a1d11051ac7a1a4e9d484ef3229be`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-method.js

Blob: `792f66b8991f787def31f6a8e4dae2b339a7179c`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-private-no-reference.js

Blob: `3a2f9fc0ec37a4e3ca72da1f01041c0f0a97f436`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-call-expression-privatename.js

Blob: `adcb626c91897a75ad008476c801d61ea10703a5`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method-accessor-get.js

Blob: `d95a5b6e45c2245ddfdaed88266dfeae82e94e5d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method-accessor-set.js

Blob: `76c28d6d14320477c69c46b56082a0248c3ce4b4`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method-async-gen.js

Blob: `6716eb230d2677e23e93261a6c00b4f710c1d55d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method-async.js

Blob: `6e0de9f02e7bb53509bf8b04784f12070b5c28eb`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method-gen.js

Blob: `34b4efadd98b7caf3f40925df6fe84fe9578a295`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-method.js

Blob: `2cfddf0c62681af39e5d2f053f456148fe56f23f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-private-no-reference.js

Blob: `0b939313b71ac04565b90e223b9f0493007d1be1`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-covered-err-delete-member-expression-privatename.js

Blob: `c532a4fa2db141a772e5c5b523abd6667a0c5640`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method-accessor-get.js

Blob: `375e2833c81d11b8f198c2e49f8039187bcc7a7a`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method-accessor-set.js

Blob: `b339bee24d85929074344907c0805b4bf1a84599`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method-async-gen.js

Blob: `4d5768d06f8e981c3ccc7a4d5396857fe4da6962`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method-async.js

Blob: `65f6b800af066a41c0b21127748f60869eab8b4f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method-gen.js

Blob: `e06dbede598c45c7292502df2bf0a9c303e2be35`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-method.js

Blob: `8de8b86e6ee8aa2d5892c2c2349636c669679d20`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-private-no-reference.js

Blob: `a4b681b2c0497e3ed4fbfd518c2aef97bc1a03ea`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-call-expression-privatename.js

Blob: `23398a4b22993f05c8c939a04068df541306e910`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method-accessor-get.js

Blob: `ff62273759c7687c6a8ad0a45128143e6592af2b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method-accessor-set.js

Blob: `443d044fe88c027dcd5cb4f35dcad79a273b35df`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method-async-gen.js

Blob: `957c608694dbc9abb071526387fb99989a9b9c53`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method-async.js

Blob: `9d3045d1fe62f7c92e10680e8ae93cfb1d04292d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method-gen.js

Blob: `841b0e7a85aa409ebbfdaf4fb124d1f873af6de7`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-method.js

Blob: `75017d0272aaf0b03ac57d56080fd5dcb4bede93`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-private-no-reference.js

Blob: `b36c9bfe9dd480c67ca0f16f3eb92289292e0a3b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-err-delete-member-expression-privatename.js

Blob: `f2abd8f4dfe20113778b5b1c03b47abb8d2071f9`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method-accessor-get.js

Blob: `b4cc315b3269027afc7d4d02f4a13016dcf55a57`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method-accessor-set.js

Blob: `439cc8f1b3c88df8e47a569a488d2a95736e3f16`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method-async-gen.js

Blob: `af61de31e4f2fb5f4a2e0ddafea8f6b1a2dd6d3b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method-async.js

Blob: `793a1001524a4446752be8aec97e1f96c40a7616`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method-gen.js

Blob: `221b83ffa462acb7a3b44ed0dfc78a1c9668aabc`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-method.js

Blob: `52f0c2e2bbe812e2cffeede270930d801662fed5`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-private-no-reference.js

Blob: `4ef6ac94fa4be98fc2669093aa595790fc106fe5`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-call-expression-privatename.js

Blob: `5bcb6fb94962a6fca44508b0b675425754ad34e8`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method-accessor-get.js

Blob: `eaeb4e0774c2c6fcf3d916799df19a160a578135`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method-accessor-set.js

Blob: `4db71f162537f686010adc1409026840b5419a2b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method-async-gen.js

Blob: `ef92e690b56b8067e6de6b2d63696f47339e1a28`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method-async.js

Blob: `22ad4c627cc05b7aab06acbfe971ec40bf6eb2a2`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method-gen.js

Blob: `f2fce899b8a2b45dff689e89bf1ba66d41e93707`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-method.js

Blob: `eaffab246425411eff49c235354a0e5dbd27e976`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-private-no-reference.js

Blob: `a8c4055cb7f313aeb3ec05205253050740e57f51`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/field-delete-twice-covered-err-delete-member-expression-privatename.js

Blob: `e8279b2f4545f7e6e63bd5818268eabc1fa626d7`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method-accessor-get.js

Blob: `2c5e260919f64833348f5aae79a1fde150409789`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method-accessor-set.js

Blob: `851b778f9ed7a3df6c681c4081a0f2ec89cb72e8`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method-async-gen.js

Blob: `8c8f1c875770f02a591004c6035bea017aaf8a62`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method-async.js

Blob: `cb2f115354b2263c83ac323ad776e9499417e438`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method-gen.js

Blob: `a43392bdfaa8fd243c315121a5f7c87be25a34cb`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-method.js

Blob: `e72c2385fcb969da876427de017d029949796a70`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-private-no-reference.js

Blob: `6d0fba7c35d15ae4efb3051a0cce836a16151e80`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-call-expression-privatename.js

Blob: `be6e92d1f8abc7d16ce4a1e303107b3c53d68453`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method-accessor-get.js

Blob: `64dc05295648ef28b1b1040027bde9148138b4c7`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method-accessor-set.js

Blob: `d9459ce491945aa44b30e54052d321f5a454854a`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method-async-gen.js

Blob: `21a539de83feeab0e535a7687e0edf481d55951b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method-async.js

Blob: `a5094182f6c6f099955f358745aad571ee95bca4`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method-gen.js

Blob: `9b60741fedb65a515d2889cc0074da1c4cd421b0`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-method.js

Blob: `dcb09ae29148b519e0bca45f85ac97cf861ac3e1`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-private-no-reference.js

Blob: `ef2bbcd03114906bd6972adb318bb6e7335d7286`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-covered-err-delete-member-expression-privatename.js

Blob: `07c1c079c6219a56e98cd53cf30bff67b2490de9`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method-accessor-get.js

Blob: `53d75c453b7e2830d59d12193c309b58df7bb4f6`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method-accessor-set.js

Blob: `6f2aa7fd920746bee0bf8d25aa9a4cc96fc0a5d2`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method-async-gen.js

Blob: `7e393a5f54492df32610049f3fb29a1aad68465f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method-async.js

Blob: `d9e120e5022613b0ae504b787b7a5838d16f50be`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method-gen.js

Blob: `93c7464d970b946aec556bcb46131a9ac870b17a`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-method.js

Blob: `c42ec8900770941bc371fe9c669aefb5fed14e21`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-private-no-reference.js

Blob: `195ace594ae9247d1b96d838a2555eeeb1db24b7`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-call-expression-privatename.js

Blob: `3b157abf71f443e0e159587ef559e2541dc1b3b9`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method-accessor-get.js

Blob: `145d32372d7a7fafef6b0153aed012788cda1155`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method-accessor-set.js

Blob: `478d90b58e6f365e8f810c17108c8e14bbb49161`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method-async-gen.js

Blob: `ed9a763511bb2100eaae9964ae9d8efde022251a`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method-async.js

Blob: `235ef7cafe32986c66ffd595aeb8af33f3a288ab`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method-gen.js

Blob: `2fef15be78e69ec975740b495f853b67200a117f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-method.js

Blob: `baf9e90077c7ca8f410e20f174fd6217b4b30a8f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-private-no-reference.js

Blob: `eb8974ebbd7fa54245c4b90d97bcec74d8a9b61d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-err-delete-member-expression-privatename.js

Blob: `452281c26f22c540ab8b977dcae7af4d489d36e1`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method-accessor-get.js

Blob: `92d223ff9100814f0a695e1400010d5c6babba1b`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method-accessor-set.js

Blob: `8ff0ddbe26316e8ee605f8d37c4009f84ee561a4`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method-async-gen.js

Blob: `341667136268d92164dab1efb3ff95b82884ca20`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method-async.js

Blob: `159cc68a91c2a2b291371c091516743ca1bb7275`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method-gen.js

Blob: `7b67503b9ca051eb6861a479b22508904f20c90d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-method.js

Blob: `e42ca69e69520553040ac2a1a42b406b82daec23`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-private-no-reference.js

Blob: `894e6dec11082d331db6973ac91142db10951f20`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-call-expression-privatename.js

Blob: `3369ed70369ca59e1cf5fcb939b42724d8b2cf3e`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method-accessor-get.js

Blob: `f2d177b212fa87f42b8d1d5986c01a91baf94ec3`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method-accessor-set.js

Blob: `5dc1a2ce6b39ce22868f535b7a04451b50f56246`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method-async-gen.js

Blob: `587b65efaa558f41d3a5f967d10463e01daa3b4e`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method-async.js

Blob: `f76f8015b9f5dc5539200453b993966d6ba8c91c`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method-gen.js

Blob: `573901042bdec9425681e5911488cd8b23047fad`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-method.js

Blob: `e5467a13e39ffede95239d6760d1ef56fc78854f`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-private-no-reference.js

Blob: `568d177eaf523af9db890422cd07b293eae0ab4d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/method-delete-twice-covered-err-delete-member-expression-privatename.js

Blob: `60ba271d21f64ce5fc54712664c6537b7b5e975d`. Role: test-path,source. Parse: failed.

Failure: Private fields can not be deleted


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/delete/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-class-body-ctor-duplicate.js

Blob: `db30575dd61e080bf44e67fa0fd75773098ad840`. Role: test-path,source. Parse: failed.

Failure: Duplicate constructor in the same class


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-ctor-super-no-heritage.js

Blob: `70fbce6ef24b462bec875f855990b93d657f805a`. Role: test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-field-identifier-invalid-ues-error.js

Blob: `8da16c99045eaafff2cbb8daa1ed871a861f5320`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-field-identifier-invalid-zwj-error.js

Blob: `6b445d097d5779b9e8f398cbdc08652352d443f4`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-field-identifier-invalid-zwnj-error.js

Blob: `da49b2eddb1917b8494550033f6a1243d00eccf2`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-fields-same-line-error.js

Blob: `be7608def169304d36177ed05e8087715af9f4b7`. Role: test-path,source. Parse: failed.

Failure: Unexpected token y


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-private-environment-on-class-heritage-array-literal.js

Blob: `de14f96cd798270ad07c6d6c0b676347b1ff4d5a`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =>


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-private-environment-on-class-heritage-chained-usage.js

Blob: `94986520f9f69b4db4bc8926bda200a48d3aaeed`. Role: test-path,source. Parse: failed.

Failure: Private field '#foo' must be declared in an enclosing class


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-private-environment-on-class-heritage-function-expression.js

Blob: `2d65e00933c71b483a1df1430829af61515ae0ca`. Role: test-path,source. Parse: failed.

Failure: Private field '#foo' must be declared in an enclosing class


### js/src/tests/test262/language/statements/class/elements/syntax/early-errors/grammar-private-environment-on-class-heritage-obj-literal.js

Blob: `014716a7741d3dd4bf0ad5caf7b2487df1d17231`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =>


## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [7eb86fed-25a3-46cd-90d8-cd5afc753604.md](7eb86fed-25a3-46cd-90d8-cd5afc753604.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `d982508cf81dab5fa077685e7753bbe71f55db117804d1368ecef0c86a1f8eb2`.
