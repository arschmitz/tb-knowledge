<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["abf9bbb39e9b3f697ca8db280529b112c83a785cb92bbc0f3673eafcfe88a1cc"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/f809f23a-79e7-4f39-9998-93be25e97da1.md"}} -->
# firefox/testing JavaScript function map 1042

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/scope-static-meth-paramsbody-var-close.js

Blob: `6b55004eac08e7867dadc2381513986e68978af9`. Role: imported-path,test-path,source. Parse: module.

- m @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probe @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @24-31

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/scope-static-meth-paramsbody-var-open.js

Blob: `d79b67180fb85d4b11407cfd1beb68bdff6e72c2`. Role: imported-path,test-path,source. Parse: module.

- m @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probeParams @27-27; FunctionExpression; parameters=0; async=false; generator=false
- probeBody @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @26-31

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/scope-static-setter-paramsbody-var-close.js

Blob: `1ded6d1b4ed0d9b8c8b2b40ef2d9d7529974b644`. Role: imported-path,test-path,source. Parse: module.

- a @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probe @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @24-31

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/scope-static-setter-paramsbody-var-open.js

Blob: `002216b51a78e4448764108aa7a370d13f8cda25`. Role: imported-path,test-path,source. Parse: module.

- a @27-30; FunctionExpression; parameters=1; async=false; generator=false
- probeParams @27-27; FunctionExpression; parameters=0; async=false; generator=false
- probeBody @29-29; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @26-31

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/setter-length-dflt.js

Blob: `1994a8b325ac879f3072957d732430edda613d58`. Role: imported-path,test-path,source. Parse: module.

- m @33-33; FunctionExpression; parameters=1; async=false; generator=false
- Class (anonymous) @33-33

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/static-gen-method-param-dflt-yield.js

Blob: `249eefec3b8946c6f963c96732ef76ad61544387`. Role: imported-path,test-path,source. Parse: failed.

Failure: Yield expression cannot be a default value


### testing/web-platform/tests/third_party/test262/test/language/expressions/class/static-init-await-binding.js

Blob: `c99b04c55e26259358c511e5b84b7455c6070190`. Role: imported-path,test-path,source. Parse: failed.

Failure: Cannot use await in class static initialization block


### testing/web-platform/tests/third_party/test262/test/language/expressions/class/static-init-await-reference.js

Blob: `f27128a2f0517e0c1c44e72f3bf184a1dcffbbe2`. Role: imported-path,test-path,source. Parse: script.

- constructor @20-22; FunctionExpression; parameters=1; async=false; generator=false
- Class C @17-25
- Class (anonymous) @19-23

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/static-method-length-dflt.js

Blob: `37af321767bd3890709a767b4260afb15486ddf3`. Role: imported-path,test-path,source. Parse: module.

- m @33-33; FunctionExpression; parameters=1; async=false; generator=false
- m @42-42; FunctionExpression; parameters=2; async=false; generator=false
- m @51-51; FunctionExpression; parameters=2; async=false; generator=false
- m @60-60; FunctionExpression; parameters=3; async=false; generator=false
- Class (anonymous) @60-60
- Class (anonymous) @51-51
- Class (anonymous) @42-42
- Class (anonymous) @33-33

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/static-method-param-dflt-yield.js

Blob: `bfc9714d5f9ace33fe740728bd7304fd975a4dcd`. Role: imported-path,test-path,source. Parse: failed.

Failure: The keyword 'yield' is reserved


### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-AggregateError.js

Blob: `25017adeecf65ec86e999cf8676a65683b8d923c`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Array.js

Blob: `301b080129595e320784fdef130806ba5754abca`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-ArrayBuffer.js

Blob: `ecd765689bfedae89f926b28c0eb5dc2109cbed3`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-BigInt64Array.js

Blob: `af2594aa88e7cf9c51376c69c797b66c7bd9b640`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-BigUint64Array.js

Blob: `69d60a120d8f3e1b64ba593f30389aa60929eead`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Boolean.js

Blob: `36d3396ac01d3439ea01012fd9aa2e313d06a85d`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-DataView.js

Blob: `44ae378eec30b4b460f145c8bbfbb0ba3c7f0ed0`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Date.js

Blob: `7c37351dbfa46e834cee095e7ab8c5b9cc0d3dd6`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Error.js

Blob: `246f5e9847195712651299d4f354445c6921df71`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-EvalError.js

Blob: `097ec860a007cdd969051e1fb4797d42c542dd8f`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Float32Array.js

Blob: `4d9425b966d71b8692e511acb087b7f2ba445c05`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Float64Array.js

Blob: `5bf436b936e7fba5a6ca197145253bf48757e60a`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Function.js

Blob: `3bddba955a0dbd607fcd6280059fe7dfb20f0302`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Int16Array.js

Blob: `440db2e9b141a32002f794abbaca9ae90fe63580`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Int32Array.js

Blob: `236d3a9507d452b14083517f6db7993450d414ea`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Int8Array.js

Blob: `4dd7da55090e8f6731cc248931ec135c762d519e`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Map.js

Blob: `4f03e6844fcabbae6eae7b88ba48b99fd3b5e2b9`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Number.js

Blob: `cb4e474f61e05fd6b4944b86f29732a994743e91`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Object.js

Blob: `cb85bf8e959814af42a19aedd26889d632d646cf`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Promise.js

Blob: `be4441b7eabfea2c2d0f5a55df8b6675718881be`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-RangeError.js

Blob: `ad604286a3e2338deb74c8d5975e6bb7d741d45e`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-ReferenceError.js

Blob: `bd206a5f1d476433870d4ed71d62893e13c3ddda`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-RegExp.js

Blob: `6c592b6d91b6cbc4de2ac7f9cd8ba5674b7dd4cd`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Set.js

Blob: `638d7d4e8d1aa31db45af3c38f843c11add53459`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-SharedArrayBuffer.js

Blob: `ddac1f035e09fcfdbad7609e3c2d95b760eed7d7`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-String.js

Blob: `f16ed354a7b39a22c99c3f750f6f012c0c5fd254`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-SyntaxError.js

Blob: `b6d211321f084eb611234d96d7c5d4c70bfedeac`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-TypeError.js

Blob: `4964421e25dc196cf89d550dbed2a3a3f943ff8b`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-URIError.js

Blob: `0a64a36184fb0c4605e8a8c671e169b2b4e4a995`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @10-10

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Uint16Array.js

Blob: `4880572afea2136c8c2b6a6830240dc4eb30d762`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Uint32Array.js

Blob: `65345c26a3dd27a01e8f65613908aee7f1b8c4c7`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Uint8Array.js

Blob: `bf7c2d197d877cfcff7811b89bd24ab005193f13`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-Uint8ClampedArray.js

Blob: `2c28237901e8e4fa7a54a9f26ebedf4b2e03547c`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-WeakMap.js

Blob: `71953ea8f96e5d51f2c9286be6ecc84aa5254495`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-WeakRef.js

Blob: `fc322d8e423c14777c076e74d2713dc5d7628188`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/class/subclass-builtins/subclass-WeakSet.js

Blob: `ff00b60f106e19366d96adf65ac5d7592c347001`. Role: imported-path,test-path,source. Parse: module.

- Class (anonymous) @11-11

### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/abrupt-is-a-short-circuit.js

Blob: `94dd038372b5cdf532235911a78cb83c22c3600c`. Role: imported-path,test-path,source. Parse: module.

- poison @38-40; FunctionDeclaration; parameters=0; async=false; generator=false
- morePoison @42-44; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-58; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/cannot-chain-head-with-logical-and.js

Blob: `de17de9f94fa7485f79b90e46269a32c8d5c4b2e`. Role: imported-path,test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/cannot-chain-head-with-logical-or.js

Blob: `de9ff3fffb88b2fecb24998a09ce647d8a31b529`. Role: imported-path,test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/cannot-chain-tail-with-logical-and.js

Blob: `a279608cc64040824ec4439825f93f4c24bbc6bd`. Role: imported-path,test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/cannot-chain-tail-with-logical-or.js

Blob: `0849f76139b2f4b05a7c51ec69ffe3746bac7eac`. Role: imported-path,test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable-if-parenthesis-covered-logical-and.js

Blob: `1787895536bc6a2b7fd5f75d426ff9a2c9262389`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable-if-parenthesis-covered-logical-or.js

Blob: `24061320593aea132b580c3e6689ee6eb6ec5b4b`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable-with-bitwise-and.js

Blob: `f88b4155d52d8be8118a6d8ae8409d95d3f242ac`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable-with-bitwise-or.js

Blob: `e6441bca3632cd94db108b7ffa20d94db6919f25`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable-with-bitwise-xor.js

Blob: `230c590a4cc01a81228c60799cccd75e82614dd1`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/chainable.js

Blob: `948645f9a12453b59e10b48005b75c393a951097`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/follows-null.js

Blob: `64068a5a5591333e76b8a50508f806cc07c5b47c`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/follows-undefined.js

Blob: `050a91775ff47fd966e67744ae49bbaf47811e14`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-0.js

Blob: `54ec3a54f1e4320cd8f668a460f6ff81a8354ea7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-42.js

Blob: `b3c58b542783a68bbccf001ad63bba573be62aa0`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-empty-string.js

Blob: `0868fc800ed1db9411e8691df15e8089e61f5f15`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-false.js

Blob: `d11733f9e43a0a057b221d5b1b393ea327ef1b33`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-object.js

Blob: `dce37d765ef8e1cef21fbb9a1808706c694e9cf0`. Role: imported-path,test-path,source. Parse: module.

- toString @39-41; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @42-44; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-string.js

Blob: `38c60eafe4623fd474f17c71d01d985ac58ab476`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-symbol.js

Blob: `fccfded6815c4ed6b2e0a6af1dc365a1eb56992a`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-number-true.js

Blob: `778f8087fdefd13f1d496ae78af1f45ebfd0d12d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/short-circuit-prevents-evaluation.js

Blob: `b064f5a2a6b962a3cf87a961f827304a12c81c63`. Role: imported-path,test-path,source. Parse: module.

- poison @38-40; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/tco-pos-null.js

Blob: `93c24453a32d0308cc4a5f5976262d197591535a`. Role: imported-path,test-path,source. Parse: module.

- f @19-25; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/coalesce/tco-pos-undefined.js

Blob: `0065123eb19eb60562c370a2d55cefdfa0dac9ea`. Role: imported-path,test-path,source. Parse: module.

- f @19-25; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/S11.14_A1.js

Blob: `e0b832aec1da1913b8c1a64fea0065d20f153bc9`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/S11.14_A2.1_T1.js

Blob: `28fdfc1740e45dc037cc68da43dcbc4477c4352c`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/S11.14_A2.1_T2.js

Blob: `e359d686140241e14a0a625fd19b1be82ad625d9`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/S11.14_A2.1_T3.js

Blob: `9951774bdd0b8dee1b4e837201b55e38de77e115`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/S11.14_A3.js

Blob: `19c66e84b20d7fadf87e0315ca2f1da3b30f5227`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/comma/tco-final.js

Blob: `b1e3ac311f508e40349e890303d448f7c85c4f6f`. Role: imported-path,test-path,source. Parse: module.

- f @12-18; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-1-s.js

Blob: `446461885f9d6446f37357883ea8375cf045548d`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-10-s.js

Blob: `1e652ce26f30944126764e40c19ff94a93b3ae73`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-11-s.js

Blob: `73286235122e77b0b1fce5b64a3552d7cfb114e9`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-12-s.js

Blob: `77f073ad05a5683a9dc626b8f4afdb500290dcb7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-13-s.js

Blob: `b7ba510f27d3963a5f75da6fda7fb661707f3ba6`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-14-s.js

Blob: `1d1250a3c0377f7030a96e9d03cdbd3f8d52bed5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-15-s.js

Blob: `5d012053b0103957d1ccf4bf36b8d93f38c88b49`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-16-s.js

Blob: `728a7c95f2ac85f4637d8caea690a3a642a2e0b7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-17-s.js

Blob: `3dfd78f82a3a7bd127a4e2f8d80afcecef92ac60`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-18-s.js

Blob: `4d192b1d1d634f650217f03751580f76c29b83d4`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-19-s.js

Blob: `92cfd5ff1a84f71eb1df71fb62ec99e415d672f2`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-2-s.js

Blob: `1a66d33b12a258e3bfd1c3099a3baba3d5b91f6c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-20-s.js

Blob: `e087cdc712bf0bafcd0c75ef956665ae0f74b647`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-21-s.js

Blob: `5cce65f80f4fc62c776497cb763a2881c7225bb8`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-22-s.js

Blob: `5851179448cf475bb5eef1de77909b702fe8815b`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-23-s.js

Blob: `d209ecbf51eec3c31aa2da8f8985c95de8a75f9f`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-24-s.js

Blob: `42bec67e91f75f72e97d585f8fd746093342d2a4`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-25-s.js

Blob: `f3c4b11c3aa356c82082f5bcb6757b230ed2f871`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-26-s.js

Blob: `bdd0e68a3163181f7c844c4e2dde9077a497814b`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-27-s.js

Blob: `f87a5a2dfdd66dff2abd318c8628c22b1733d927`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-28-s.js

Blob: `3bf144daeb0b89637364255daf104cc673574934`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-29-s.js

Blob: `ed8091fcfedc4da6f81b1d02f792897093321887`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-30-s.js

Blob: `26f120d3f5cf268de1eb004c3b00c8fa0466ba4f`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-31-s.js

Blob: `0d6786620878e27ab00d3c0d80e1d20b624d2e6a`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-32-s.js

Blob: `8182307d6088a9c453dac84ee7a8987208565488`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-33-s.js

Blob: `c0883a6e5665b1303e40520ee04b011e8c1b66e3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-34-s.js

Blob: `b4becc6d0b44bbf244a89a93b98adc9d7fc37b67`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-35-s.js

Blob: `81829ff160113b62f35cb1e5a69bc77a548277a6`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-36-s.js

Blob: `7eb331477ca0ca99080bd66a446ba503117eec00`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-37-s.js

Blob: `4d8aa3b8f3676f8744247f375531aeb3012cf854`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-38-s.js

Blob: `9b39dca4fb59d0af6f56e2aafdd541853ffa160a`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-39-s.js

Blob: `ebd44377c6924339305a6e4af5e4ea04b2219b26`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-4-s.js

Blob: `aeecd46c7a0bfbf0932d9e0101798cbc204383e1`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-40-s.js

Blob: `28f57bd4c33b86e73d383f39f6cedb700018c422`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-41-s.js

Blob: `d5d567d97c42f4fdaec2f1e2c24c329d338e3e7b`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-42-s.js

Blob: `860fefca8d258c62ae638a1dad89272b0acc9cfe`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-43-s.js

Blob: `b25ca2ba1b4ddef9ad1f9055888f3b6dba521ebe`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-44-s.js

Blob: `9489059879a6593679f3758310f3ff17c11b7c90`. Role: imported-path,test-path,source. Parse: module.

- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-45-s.js

Blob: `93cfaa2490ec82c867e899a221213163b9c562fb`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-46-s.js

Blob: `26bc4c6e7d2f197cbcb807db3b1e2e1437bc6b17`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-47-s.js

Blob: `75805899fe69000aa88790bd72ebb8897c535561`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-48-s.js

Blob: `920b643ccbf901094e3828be4c1b148bd6d71135`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-49-s.js

Blob: `48f3aedbf5654c7074e842f67a3e883ac789f8cd`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-5-s.js

Blob: `16654674aa065c3fa25f92c5d0dfe2e8fa5a4db0`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-50-s.js

Blob: `2e46189b66c52b96e63d961ee3c708ed9cdaa09c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-51-s.js

Blob: `53d27cb234daa80271371e8f78e69fbc1be5f6cc`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-52-s.js

Blob: `e0f5b604e9473d4d68c448a43e496fa845a30961`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-53-s.js

Blob: `335a8ba0a7172cb2a040ee82429367dec97f9e38`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-54-s.js

Blob: `f0c9a4930292a3efb7c20fdcbec7317048d85b58`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-55-s.js

Blob: `9a56c0a23687b4be682b1a63f5ada0630d15eec8`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-6-1gs.js

Blob: `78f9962bba7f1e6813d7afc2a2d613ccffb3cd58`. Role: imported-path,test-path,source. Parse: script.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-6-s.js

Blob: `14084ba7e2fc3aa2b6f3512e647b739758740402`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-8-s.js

Blob: `ecd1cd83265accfb739a6bb012fefd20216ee373`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/11.13.2-9-s.js

Blob: `50836f4f629626f9749a2af19cbd943668550253`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.1.js

Blob: `3dd3320b66c28fefc1ed625630a4311c82e5d2c7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.10.js

Blob: `d0dc6e7b24a38aea188d11f249feb6d48a18c609`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.11.js

Blob: `3a895f92dfe5b599a5c8a125278c51dafd00a51e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.2.js

Blob: `d70114702522a9f4442529c17c29e64f7e166703`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.3.js

Blob: `76149853a8164f495a26548a03821ba656a5a3b2`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.4.js

Blob: `966a008a2d65d8d7720a1b478d2dbca523b9c3f7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.5.js

Blob: `8da97ff84e5803d12faa7ab9dc13383d977d521d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.6.js

Blob: `dbfae949d6c5c45d6056ecfc51f03bfbecaac0f9`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.7.js

Blob: `0d0ca46406d74a65835ed335cb24a0c3a770d57f`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.8.js

Blob: `2283331c7edcd7ce38401f5fddab037627593a5a`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T1.9.js

Blob: `38a7ee8292463521805985badd9ce28476ebe283`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.1.js

Blob: `cf76dd18560a22551cff968c530a24fc863f50bc`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.10.js

Blob: `7e71b774f7d97413808a96bae8666f33ed3b79c5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.11.js

Blob: `a4dbbe369a8d1bbb891e8ef3b87d4a4c0156c053`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.2.js

Blob: `d84dc9764e8a646e92e958f7ce0c188cbc52fa85`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.3.js

Blob: `bbbbb62f65ad48e06a815a3303339f9f7f424653`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.4.js

Blob: `f00225b0256ba6b35b5c86bfaa4ef5b700cb13bb`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.5.js

Blob: `1c08a3585e72b61d21db9693a2a5624bcdca20df`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.6.js

Blob: `033611a4ea9b773ff49831851656841ab6a0ba9a`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/language/expressions/compound-assignment/S11.13.2_A2.1_T2.7.js

Blob: `9dccbb6d39acb07f3f980d56fbc725fa211da224`. Role: imported-path,test-path,source. Parse: module.


## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [f809f23a-79e7-4f39-9998-93be25e97da1.md](f809f23a-79e7-4f39-9998-93be25e97da1.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `abf9bbb39e9b3f697ca8db280529b112c83a785cb92bbc0f3673eafcfe88a1cc`.
