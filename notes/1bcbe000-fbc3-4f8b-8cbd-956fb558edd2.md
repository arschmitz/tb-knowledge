<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["b5077659f1dc4007acb283b8a9b170daf47055d0174d97e3b1d57d7cc6825511"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/e68e33b0-3298-4fd7-98ae-e4933d9efc1b.md"}} -->
# firefox/testing JavaScript function map 1121

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/third_party/test262/test/language/statements/class/scope-static-meth-paramsbody-var-close.js

Blob: `b26d03cb96f910cca7057b46cf9ced99ebf25dc9`. Role: imported-path,test-path,source. Parse: module.

- m @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probe @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class C @24-31

### testing/web-platform/tests/third_party/test262/test/language/statements/class/scope-static-meth-paramsbody-var-open.js

Blob: `6dc9f47c74e210fcc176630d1b5e85b1232b63fb`. Role: imported-path,test-path,source. Parse: module.

- m @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probeParams @27-27; FunctionExpression; parameters=0; async=false; generator=false
- probeBody @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class C @26-31

### testing/web-platform/tests/third_party/test262/test/language/statements/class/scope-static-setter-paramsbody-var-close.js

Blob: `c3dd67391138ace72d61d08bf41153c882dc5fc0`. Role: imported-path,test-path,source. Parse: module.

- a @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probe @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class C @24-31

### testing/web-platform/tests/third_party/test262/test/language/statements/class/scope-static-setter-paramsbody-var-open.js

Blob: `ba0c2efd733e0225ef8c9a4dfe17ab80288f8450`. Role: imported-path,test-path,source. Parse: module.

- a @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probeParams @27-27; FunctionExpression; parameters=0; async=false; generator=false
- probeBody @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class C @26-31

### testing/web-platform/tests/third_party/test262/test/language/statements/class/setter-length-dflt.js

Blob: `ef19376bd4a2ceffd48d2def55d9d433e14aa769`. Role: imported-path,test-path,source. Parse: module.

- m @33-33; FunctionExpression; parameters=1; async=false; generator=false
- Class C @33-33

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-classelementname-abrupt-completion.js

Blob: `e173f443302f93c31b617b8c3f2faf2982d51d64`. Role: imported-path,test-path,source. Parse: module.

- f @25-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false
- Class C @30-32

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-gen-method-param-dflt-yield.js

Blob: `95bbefe3e28001b313f10d49b32754834937040d`. Role: imported-path,test-path,source. Parse: failed.

Failure: Yield expression cannot be a default value


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-abrupt.js

Blob: `c8270c10e789ffbd600481db0d51e42de3bd2c54`. Role: imported-path,test-path,source. Parse: module.

- Class C @29-38

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-arguments-functions.js

Blob: `152d6f535b113aaea48a24cd0a25ea6463899e4f`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=1; async=false; generator=true
- (anonymous) @29-31; FunctionExpression; parameters=1; async=true; generator=false
- Class C @19-33

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-arguments-methods.js

Blob: `1ef423dc3917ae196807b1c9f18b1c49922d5ecb`. Role: imported-path,test-path,source. Parse: module.

- method @25-27; FunctionExpression; parameters=1; async=false; generator=false
- accessor @28-30; FunctionExpression; parameters=0; async=false; generator=false
- accessor @31-33; FunctionExpression; parameters=1; async=false; generator=false
- gen @34-36; FunctionExpression; parameters=1; async=false; generator=true
- async @37-39; FunctionExpression; parameters=1; async=true; generator=false
- Class C @22-42
- Class (anonymous) @24-40

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-await-binding-invalid.js

Blob: `3f43b9139dbae7fe71575c26486e1eb1a4ce7110`. Role: imported-path,test-path,source. Parse: failed.

Failure: Cannot use await in class static initialization block


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-await-binding-valid.js

Blob: `fe10bb9c54904c9e5d0ca54407b4779513599c55`. Role: imported-path,test-path,source. Parse: script.

- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class C @14-18
- Class await @16-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-expr-new-target.js

Blob: `10d3477160ccd140280c4b219e91f382cd8a494c`. Role: imported-path,test-path,source. Parse: module.

- Class C @17-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-expr-this.js

Blob: `4d6f6ca295f3d0ac50d5a4f135ea3a386e83dd32`. Role: imported-path,test-path,source. Parse: module.

- Class C @17-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-arguments.js

Blob: `1f791bfc3ee68f3a89ed4d1c9fbee3e9a78330fc`. Role: imported-path,test-path,source. Parse: failed.

Failure: Cannot use arguments in class static initialization block


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-await.js

Blob: `06e511551c99f606216c1619f5007082329343df`. Role: imported-path,test-path,source. Parse: failed.

Failure: Cannot use await in class static initialization block


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-label-dup.js

Blob: `352c37ed471df32fe087877265d399d2310655bc`. Role: imported-path,test-path,source. Parse: failed.

Failure: Label 'x' is already declared


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-lex-dup.js

Blob: `59312e49cd61cebc111cd52a613959e7b2f1c648`. Role: imported-path,test-path,source. Parse: failed.

Failure: Identifier 'x' has already been declared


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-lex-var.js

Blob: `2e78d2762cb4ebf2a7f098c1e944d45fdb788221`. Role: imported-path,test-path,source. Parse: failed.

Failure: Identifier 'x' has already been declared


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-return.js

Blob: `dda77131326000e519064d6c0f37d472228f0ffd`. Role: imported-path,test-path,source. Parse: module.

- f @21-27; FunctionDeclaration; parameters=0; async=false; generator=false
- Class C @22-26

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-super-call.js

Blob: `66e6bf136bf6b88c012cc9015006da0e15a1f954`. Role: imported-path,test-path,source. Parse: failed.

Failure: super() call outside constructor of a subclass


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-undefined-break-target.js

Blob: `fa11b904bfe5800b7c62373ac4eda5b2a6b0ffe6`. Role: imported-path,test-path,source. Parse: failed.

Failure: Unsyntactic break


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-undefined-continue-target.js

Blob: `389245a0e0045e11181f073811de33dd769c37c0`. Role: imported-path,test-path,source. Parse: failed.

Failure: Unsyntactic continue


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-invalid-yield.js

Blob: `60ab3925126c7a3d9de9d0f9fe062e6975b63be4`. Role: imported-path,test-path,source. Parse: failed.

Failure: The keyword 'yield' is reserved


### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-lex-close.js

Blob: `f7a21511a5f08ad9898c093e74163d80d9bc8e6c`. Role: imported-path,test-path,source. Parse: module.

- Class C @18-25

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-lex-derived.js

Blob: `664ad0990f36541e396c08a9823ed5c6688ffaae`. Role: imported-path,test-path,source. Parse: module.

- Class C @17-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-lex-open.js

Blob: `cc74cd5321e11a472c41a2971d1201427d11e23e`. Role: imported-path,test-path,source. Parse: module.

- Class C @18-27

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-private.js

Blob: `849698fb1d543edd4091532aa6a8508be723c781`. Role: imported-path,test-path,source. Parse: module.

- Class C @17-23

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-var-close.js

Blob: `adc4f299e463412a4704ac9ab1344e839b0d989e`. Role: imported-path,test-path,source. Parse: module.

- Class C @18-25

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-var-derived.js

Blob: `d2cf286e59202c42020034f2a762ed307ba82cee`. Role: imported-path,test-path,source. Parse: module.

- Class C @18-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-scope-var-open.js

Blob: `b8152112c1e03952fbf13dfcfba652a47af03421`. Role: imported-path,test-path,source. Parse: module.

- Class C @18-27

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-sequence.js

Blob: `335dc9dd172830b87f97119cb7dd404c13bfb7da`. Role: imported-path,test-path,source. Parse: module.

- Class C @24-33

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-statement-list-optional.js

Blob: `038f1bf287ae4ae94478d0bb01c990e5a3cdb86b`. Role: imported-path,test-path,source. Parse: module.

- Class C @16-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-init-super-property.js

Blob: `ebfc5f60835bbfbe696cc6146f490bcdb3686995`. Role: imported-path,test-path,source. Parse: module.

- Parent @14-14; FunctionDeclaration; parameters=0; async=false; generator=false
- Class C @18-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-method-gen-non-configurable-err.js

Blob: `249f647d8507b17062c07a487460fbf8096c53ea`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @15-17; FunctionExpression; parameters=0; async=false; generator=false
- prototype @16-16; FunctionExpression; parameters=0; async=false; generator=true
- Class C @16-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-method-length-dflt.js

Blob: `d788d37f1a32a04dfdf00336f60d99fe3de97bbc`. Role: imported-path,test-path,source. Parse: module.

- m @33-33; FunctionExpression; parameters=1; async=false; generator=false
- m @44-44; FunctionExpression; parameters=2; async=false; generator=false
- m @55-55; FunctionExpression; parameters=2; async=false; generator=false
- m @66-66; FunctionExpression; parameters=3; async=false; generator=false
- Class C4 @66-66
- Class C3 @55-55
- Class C2 @44-44
- Class C1 @33-33

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-method-non-configurable-err.js

Blob: `ddf24fb50d29fecbfdbfed2c3d1251524d255b28`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false
- prototype @15-15; FunctionExpression; parameters=0; async=false; generator=false
- Class C @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/static-method-param-yield.js

Blob: `03aa07de37a6a512d7f373ea22f956ad7b51d313`. Role: imported-path,test-path,source. Parse: failed.

Failure: The keyword 'yield' is reserved


### testing/web-platform/tests/third_party/test262/test/language/statements/class/strict-mode/arguments-callee.js

Blob: `f940a326a9811182509ae7f250cf8bd6fe302393`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @8-10; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @8-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/strict-mode/with.js

Blob: `9bb227a4de0a505d6d5be61916378b97f2eed624`. Role: imported-path,test-path,source. Parse: failed.

Failure: 'with' in strict mode


### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-AggregateError.js

Blob: `04f49766cbd066f00f7bb68ad6b6448eb2fffd97`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Array.js

Blob: `dc1d5776a73781171186e1837fe3e12f0cd35629`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-ArrayBuffer.js

Blob: `178905b12acef0763670dcf1769251756719c2e3`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-BigInt64Array.js

Blob: `d9e9bfd3f8f80cc40584c31ac71fcee7214b08b2`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-BigUint64Array.js

Blob: `9afc89352b3a6bdf34d8745416368c3951662ff5`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Boolean.js

Blob: `018cbf115c9caa8acf32270b84a3e82e0249ca09`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-DataView.js

Blob: `eca5d125f5dbd35cd25590f6e9c6b26956eb71f1`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Date.js

Blob: `a08d3d4ad0d4462c2bbe2d4824556497c820a87a`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Error.js

Blob: `62cbab9b862e0f0caf07c22f4658da263a3ef382`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-EvalError.js

Blob: `67ce2288786e34e71b7595e4d94cdbdc6cf24e07`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Float32Array.js

Blob: `07edce6b861a424c560faf42d9dfa5cea9b0a1e2`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Float64Array.js

Blob: `581dbd79d2f5e26f1c1de41e0085acbf0592c8cc`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Function.js

Blob: `c474772da0e238b4cf48fb31bab784211c07a5a1`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Int16Array.js

Blob: `92b1de81ae8ffce41d7eeace2b5742de21a13541`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Int32Array.js

Blob: `e87645e8befe311e2284fbb5b4f5af689e42e792`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Int8Array.js

Blob: `d7d1d0b4851ddd7a3d72615f631160e11b39a553`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Map.js

Blob: `9ba5e4e1646cc4d8c787040effb72069823c5102`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Number.js

Blob: `b8b95555163abb53f3a70f5a7bfc30853335d422`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Object.js

Blob: `ab02825c735dcddedba72189e0093d142088e92e`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Promise.js

Blob: `2cd8270de51f26c0a73e283723b083fc67780019`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-RangeError.js

Blob: `fe2b27920fa37f7c000e137d5795e01780b00230`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-ReferenceError.js

Blob: `5635b3ec34f7ded05ee0e7a4940ce5df7a9760ce`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-RegExp.js

Blob: `ab06263a9757c07c2b314330b3ed7faf46c631f1`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Set.js

Blob: `c4801cc9c1bf52a28c7713e24171f015a1b85b14`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-SharedArrayBuffer.js

Blob: `e116e1cdbbe39ca4e6283f85ff5ff059976dac4d`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-String.js

Blob: `b8cdd758e3a7ae2daad3df0503567db6d887ef26`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-SyntaxError.js

Blob: `67f8fd9236a4ffcd3d0365377a06d9a7cba4752e`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-TypeError.js

Blob: `7a323ce406e7efafe13be05e6b3bd59fe75befa8`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-URIError.js

Blob: `9ea363299bb8cbfc4e5eae6889520f290780f38f`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @10-10

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Uint16Array.js

Blob: `9e9fe5ce3973cc7296edf1d0c56a48b5bdb6a35b`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Uint32Array.js

Blob: `72cdfd6aa62728f4c275c8c8d3e13fecc94b6ff4`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Uint8Array.js

Blob: `2df0004f67da9806bd596512bb05764a3efa61a9`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-Uint8ClampedArray.js

Blob: `b00ab809074e07c8b811bbf6ab8e3b3908ad2966`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-WeakMap.js

Blob: `0a861b7a1a3bf1afffaea4b99bc413fcadf75bb3`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-WeakRef.js

Blob: `7a07fe08d06cc4e27dfdecec4a725b50c9656ad8`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass-builtins/subclass-WeakSet.js

Blob: `5008810e865145eb454a1d9aa0753036b3ee76f6`. Role: imported-path,test-path,source. Parse: module.

- Class Subclass @11-11

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/binding.js

Blob: `20d03efd54ba0b1b4b8c5f06f5d4aa61ab6c3872`. Role: imported-path,test-path,source. Parse: module.

- constructor @9-12; FunctionExpression; parameters=2; async=false; generator=false
- constructor @17-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- Class Subclass @16-21
- Class Base @8-13

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Array/contructor-calls-super-multiple-arguments.js

Blob: `ad7a57b2f425af2b538242e68e0baf4b67b5be02`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-21; FunctionExpression; parameters=2; async=false; generator=false
- Class Sub @18-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Array/contructor-calls-super-single-argument.js

Blob: `dfcbd6cafd9bc06b0219b4de0d35957bba580917`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-20; FunctionExpression; parameters=1; async=false; generator=false
- Class Sub @17-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Array/length.js

Blob: `09b0bad10f18143a114212a6da6815adeb89b4c4`. Role: imported-path,test-path,source. Parse: module.

- Class Ar @18-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Array/regular-subclassing.js

Blob: `087efb14ceb3079bd98fdbea62e07334d75ec41f`. Role: imported-path,test-path,source. Parse: module.

- Class Sub @14-14

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Array/super-must-be-called.js

Blob: `6716b32a8e8a4d798dae902d261058a5a2de0242`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @27-29; FunctionExpression; parameters=0; async=false; generator=false
- Class A2 @26-30
- Class A @18-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/ArrayBuffer/regular-subclassing.js

Blob: `8b32fb6be791237e57f7c84ff98dc8983319e083`. Role: imported-path,test-path,source. Parse: module.

- Class AB @19-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/ArrayBuffer/super-must-be-called.js

Blob: `ea7c4cb87f5fd1cf3f2acdd9f318316ae05cffed`. Role: imported-path,test-path,source. Parse: module.

- constructor @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- constructor @28-30; FunctionExpression; parameters=1; async=false; generator=false
- Class AB2 @27-31
- Class AB1 @19-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Boolean/regular-subclassing.js

Blob: `8ffb91d61b2a731a18ba6ca900aef1023b8cdbb1`. Role: imported-path,test-path,source. Parse: module.

- Class Bln @14-14

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Boolean/super-must-be-called.js

Blob: `de77a4159040986b443babbf93fb507d9a67a8a2`. Role: imported-path,test-path,source. Parse: module.

- constructor @16-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false
- constructor @25-27; FunctionExpression; parameters=0; async=false; generator=false
- Class Bln2 @24-28
- Class Bln @15-17

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/DataView/regular-subclassing.js

Blob: `2e1c2587513ebf39a40c57a160682cbbcf9ad95a`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- Class DV @19-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/DataView/super-must-be-called.js

Blob: `aded58263981fd11339bc2600238959d565fe84d`. Role: imported-path,test-path,source. Parse: module.

- constructor @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=0; async=false; generator=false
- constructor @30-32; FunctionExpression; parameters=1; async=false; generator=false
- Class DV2 @29-33
- Class DV1 @19-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Date/regular-subclassing.js

Blob: `357b02bd805e86469551f1985dc2fad2a4a6c7a9`. Role: imported-path,test-path,source. Parse: module.

- Class D @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Date/super-must-be-called.js

Blob: `a5148035d53df3687b23cf7714a76d8c85d70c75`. Role: imported-path,test-path,source. Parse: module.

- constructor @22-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=0; async=false; generator=false
- constructor @30-32; FunctionExpression; parameters=1; async=false; generator=false
- Class D2 @29-33
- Class D @21-23

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Error/message-property-assignment.js

Blob: `e87d30d01be38275df9d0680f91228616c3b8a00`. Role: imported-path,test-path,source. Parse: module.

- Class Err @22-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Error/regular-subclassing.js

Blob: `9d72367fee268d0fbcf9f4d10531e4493d5c8af4`. Role: imported-path,test-path,source. Parse: module.

- Class CustomError @17-17

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Error/super-must-be-called.js

Blob: `a6ea8bba50c4f785a2be6ee6ba9424fafe758c0d`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Function/instance-length.js

Blob: `acdb7df6ffc9256f2c5a58db67218df28c20a056`. Role: imported-path,test-path,source. Parse: module.

- Class Fn @19-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Function/instance-name.js

Blob: `4a0cdffb1f14a6d6666e7cef1d47ae04fc4d00cf`. Role: imported-path,test-path,source. Parse: module.

- Class Fn @28-28

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Function/regular-subclassing.js

Blob: `afd014e11610eede0359095f804ad877c140202d`. Role: imported-path,test-path,source. Parse: module.

- Class Fn @16-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Function/super-must-be-called.js

Blob: `a4d353543d004e19e781d7b4133175bb250f68d7`. Role: imported-path,test-path,source. Parse: module.

- constructor @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- constructor @29-31; FunctionExpression; parameters=0; async=false; generator=false
- Class Fn2 @28-32
- Class Fn @20-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/GeneratorFunction/instance-length.js

Blob: `614f2d80f54e493a57fa4339fc92985f1972945d`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=true
- Class GFn @23-23

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/GeneratorFunction/instance-name.js

Blob: `4cadc718750d6c7a6d723857fb1f8ce1a3a19d43`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @33-33; FunctionExpression; parameters=0; async=false; generator=true
- Class GFn @35-35

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/GeneratorFunction/instance-prototype.js

Blob: `dd4965815679791346d15a9fb618193cc00ab15c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=true
- Class GFn @23-23

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/GeneratorFunction/regular-subclassing.js

Blob: `01f83fc96d8180fef885832fac7ed77e4449854a`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=true
- Class Gfn @22-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/GeneratorFunction/super-must-be-called.js

Blob: `21e877a8fb9af87b269bd1c041015549557775ae`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=true
- constructor @24-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-29; FunctionExpression; parameters=0; async=false; generator=false
- constructor @32-34; FunctionExpression; parameters=0; async=false; generator=false
- Class GFn2 @31-35
- Class GFn1 @23-25

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Map/regular-subclassing.js

Blob: `edc4f5b4c5262746bb68a6b6917fbe564f02ae8c`. Role: imported-path,test-path,source. Parse: module.

- Class M @18-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Map/super-must-be-called.js

Blob: `5f8011acbf18f420aacd7e1cb205e846511ca107`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @27-29; FunctionExpression; parameters=0; async=false; generator=false
- Class M2 @26-30
- Class M1 @18-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/EvalError-message.js

Blob: `e7427246fe17df88877c38d71961ac0bf3f943ee`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/EvalError-name.js

Blob: `be46dc30a77fdc8debb52f82be9f58fbabe9df48`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/EvalError-super.js

Blob: `db24f2fab1af5c2ece76a6463999d7077cbbbe55`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/RangeError-message.js

Blob: `10b018d479326564a7b9a6af2d54e6a475f66078`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/RangeError-name.js

Blob: `de6545f4ec9915abcab114e1ec1ffb9e70694383`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/RangeError-super.js

Blob: `5d6a31c43f43afc61eeff113dd87c9f652a173be`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/ReferenceError-message.js

Blob: `6c9432d0ec9fe35c19ae65993acdf85334c5ff9d`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/ReferenceError-name.js

Blob: `00a08705d54402b6a1b8308e7bdb4912a88679c7`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/ReferenceError-super.js

Blob: `b547ed69e1c5e700796a1cb8364f8c902bc88451`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/SyntaxError-message.js

Blob: `c90450b6ec8046b564837b4669bdfa33f9188c71`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/SyntaxError-name.js

Blob: `f0b7921dc20a1e3a4a479155b3a08e6fe130c2da`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/SyntaxError-super.js

Blob: `d25b62f7d7e3f88900fedf28d40261a77a5705f9`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/TypeError-message.js

Blob: `fb19633a53973b82bd4b6cbe147dbbec80077d33`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/TypeError-name.js

Blob: `a5e87135dddbffe7517c4d31bef6fac363a30f9a`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/TypeError-super.js

Blob: `49bed762c1c1428e8c03e05126bd90a27072f313`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/URIError-message.js

Blob: `03438676c0db0757701b8363b18bf60e71d2c458`. Role: imported-path,test-path,source. Parse: module.

- Class Err @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/URIError-name.js

Blob: `d931918c227738e35858390adb7b2e1945cb62d2`. Role: imported-path,test-path,source. Parse: module.

- Class Err @15-15

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/NativeError/URIError-super.js

Blob: `dcb62c5b1f07b6b81f0c7db2d32058f094090a35`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- Class CustomError @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Number/regular-subclassing.js

Blob: `5b950c17892735ede16424ec88b2d64df0830b07`. Role: imported-path,test-path,source. Parse: module.

- Class N @18-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Number/super-must-be-called.js

Blob: `d8bad81113c22641575f01dd293e8254aeda2b00`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @27-29; FunctionExpression; parameters=0; async=false; generator=false
- Class N2 @26-30
- Class N @18-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Object/constructor-return-undefined-throws.js

Blob: `b181446f157d9d8ff6ef6cee54a5bf167a78e6af`. Role: imported-path,test-path,source. Parse: module.

- constructor @30-32; FunctionExpression; parameters=0; async=false; generator=false
- constructor @36-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- Class Obj2 @35-37
- Class Obj @29-33

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Object/constructor-returns-non-object.js

Blob: `f222baa7d549b1c2d247ddefc9131f420bbb99b2`. Role: imported-path,test-path,source. Parse: module.

- constructor @33-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- Class Obj @32-36

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Object/regular-subclassing.js

Blob: `9d53996b66cd70920c0a05d6a65d2b2edcd9228a`. Role: imported-path,test-path,source. Parse: module.

- Class Obj @13-13

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Object/replacing-prototype.js

Blob: `edf4a2d562bdac9f12cc11f27c4947f9434d46df`. Role: imported-path,test-path,source. Parse: module.

- valueOf @14-16; FunctionExpression; parameters=0; async=false; generator=false
- Class Obj @13-17

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Promise/regular-subclassing.js

Blob: `26f79a9480ff9fd4f675253e4b78e32f0527e5f3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-31; FunctionExpression; parameters=0; async=false; generator=false
- Class Prom @19-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Promise/super-must-be-called.js

Blob: `8e80073bcaec1b20001e2a7854d0481bbd57f6b9`. Role: imported-path,test-path,source. Parse: module.

- constructor @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- constructor @28-30; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; FunctionExpression; parameters=0; async=false; generator=false
- Class Prom2 @27-31
- Class Prom1 @19-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Proxy/no-prototype-throws.js

Blob: `a752318ba7828b8395fc9caeece5403c4f66cd7c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- Class P @31-31

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/RegExp/lastIndex.js

Blob: `be9b9ec400c73b2c047fac26af7b607d00402935`. Role: imported-path,test-path,source. Parse: module.

- Class RE @16-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/RegExp/regular-subclassing.js

Blob: `c8df362fdf93326db5c3cca2fa3443dad9abf2f6`. Role: imported-path,test-path,source. Parse: module.

- Class RE @18-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/RegExp/super-must-be-called.js

Blob: `f5cbc7c5d7e8ae58f28d7a7bb8eb064ef3d2934e`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @27-29; FunctionExpression; parameters=0; async=false; generator=false
- Class RE2 @26-30
- Class RE1 @18-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Set/regular-subclassing.js

Blob: `dd591b2545558fb3ed28749b0ace35ff5dec60a1`. Role: imported-path,test-path,source. Parse: module.

- Class S @18-18

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Set/super-must-be-called.js

Blob: `74192487366c5e8da8433bbd3894cafe93c4d126`. Role: imported-path,test-path,source. Parse: module.

- constructor @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- constructor @27-29; FunctionExpression; parameters=0; async=false; generator=false
- Class S2 @26-30
- Class S1 @18-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/String/length.js

Blob: `522b33c8f434ee6817e8fdf58804a1dc71734747`. Role: imported-path,test-path,source. Parse: module.

- Class S @16-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/String/regular-subclassing.js

Blob: `6704b4420dd416c8c1728962021c07c947b089c9`. Role: imported-path,test-path,source. Parse: module.

- Class S @17-17

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/String/super-must-be-called.js

Blob: `48a5bda8da505e7ed8f86f32ab3a6df0d4b7b5b7`. Role: imported-path,test-path,source. Parse: module.

- constructor @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- constructor @26-28; FunctionExpression; parameters=0; async=false; generator=false
- Class S2 @25-29
- Class S1 @17-19

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Symbol/new-symbol-with-super-throws.js

Blob: `b2e2a28c2ad0dee022c8428a63144ecd7f9f8f69`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- constructor @28-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-35; FunctionExpression; parameters=0; async=false; generator=false
- Class S2 @27-31
- Class S1 @21-21

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/Symbol/symbol-valid-as-extends-value.js

Blob: `fe045493b680d6a4f2ae1bb8b92b950501a9cb88`. Role: imported-path,test-path,source. Parse: module.

- Class S @17-17

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/TypedArray/regular-subclassing.js

Blob: `61b4e132c6366061e9b455f41da9ecd702e9033c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-27; FunctionExpression; parameters=1; async=false; generator=false
- Class Typed @22-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/TypedArray/super-must-be-called.js

Blob: `de27fb8852e3b81c1a562d8e0af9807316fad609`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @21-37; FunctionExpression; parameters=1; async=false; generator=false
- constructor @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- constructor @31-33; FunctionExpression; parameters=0; async=false; generator=false
- Class TypedWithSuper @30-34
- Class Typed @22-24

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/WeakMap/regular-subclassing.js

Blob: `87b7540d5fc27475817bba9ec23f9889a606d095`. Role: imported-path,test-path,source. Parse: module.

- Class WM @20-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/WeakMap/super-must-be-called.js

Blob: `ba425418e92eae1c71f0b1382d1428168629c423`. Role: imported-path,test-path,source. Parse: module.

- constructor @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- constructor @29-31; FunctionExpression; parameters=0; async=false; generator=false
- Class M2 @28-32
- Class M1 @20-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/WeakSet/regular-subclassing.js

Blob: `9a0fbc3d7d8975f416b4fa28f5ff5e95c1a565b2`. Role: imported-path,test-path,source. Parse: module.

- Class WS @20-20

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtin-objects/WeakSet/super-must-be-called.js

Blob: `052c54322080103ccf40571291d24aebc7f870e0`. Role: imported-path,test-path,source. Parse: module.

- constructor @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- constructor @29-31; FunctionExpression; parameters=0; async=false; generator=false
- Class WS2 @28-32
- Class WS1 @20-22

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/builtins.js

Blob: `608a799b95ae78582adafb6712dee251502cc164`. Role: imported-path,test-path,source. Parse: module.

- constructor @9-13; FunctionExpression; parameters=0; async=false; generator=false
- Class ExtendedUint8Array @8-14

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/class-definition-evaluation-empty-constructor-heritage-present.js

Blob: `a8c395bac8c9439be282aeb9d27c2e07a9315b43`. Role: imported-path,test-path,source. Parse: module.

- constructor @13-15; FunctionExpression; parameters=0; async=false; generator=false
- Class B @18-27
- Class A @12-16

### testing/web-platform/tests/third_party/test262/test/language/statements/class/subclass/class-definition-null-proto-contains-return-override.js

Blob: `9a5b1ec6df9fb76a752db5edc82f1f4c33e4d2a8`. Role: imported-path,test-path,source. Parse: module.

- constructor @25-27; FunctionExpression; parameters=0; async=false; generator=false
- Class Foo @24-28

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [e68e33b0-3298-4fd7-98ae-e4933d9efc1b.md](e68e33b0-3298-4fd7-98ae-e4933d9efc1b.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `b5077659f1dc4007acb283b8a9b170daf47055d0174d97e3b1d57d7cc6825511`.
