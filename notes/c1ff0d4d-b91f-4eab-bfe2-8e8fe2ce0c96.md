<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["9c1cb694b21faf835988cb003918f56507a596cbed673b70dc0ba0d893c7d51e"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/7ee67609-e080-45b3-a0b1-aa16a2488dcc.md"}} -->
# firefox/js JavaScript function map 569

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/test262/language/expressions/class/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/class/static-gen-method-param-dflt-yield.js

Blob: `25fef6b7e4f3967d491712a2645afb86ed5cd046`. Role: test-path,source. Parse: failed.

Failure: Yield expression cannot be a default value


### js/src/tests/test262/language/expressions/class/static-init-await-binding.js

Blob: `adfc00c8b314e410a331c57a7e2ff311f5e33918`. Role: test-path,source. Parse: failed.

Failure: Cannot use await in class static initialization block


### js/src/tests/test262/language/expressions/class/static-init-await-reference.js

Blob: `ee37e95ddebd31dff09fa6239c670d860088c474`. Role: test-path,source. Parse: script.

- constructor @20-22; FunctionExpression; parameters=1; async=false; generator=false
- Class C @17-25
- Class (anonymous) @19-23

### js/src/tests/test262/language/expressions/class/static-method-length-dflt.js

Blob: `6706704a5c6a3675ef48e8700d9370f4db93d8d2`. Role: test-path,source. Parse: module.

- m @33-33; FunctionExpression; parameters=1; async=false; generator=false
- m @42-42; FunctionExpression; parameters=2; async=false; generator=false
- m @51-51; FunctionExpression; parameters=2; async=false; generator=false
- m @60-60; FunctionExpression; parameters=3; async=false; generator=false
- Class (anonymous) @60-60
- Class (anonymous) @51-51
- Class (anonymous) @42-42
- Class (anonymous) @33-33

### js/src/tests/test262/language/expressions/class/static-method-param-dflt-yield.js

Blob: `651d2470e69d97c1bdb3a800f5f8b551786f0c0e`. Role: test-path,source. Parse: failed.

Failure: The keyword 'yield' is reserved


### js/src/tests/test262/language/expressions/class/subclass-builtins/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/class/subclass-builtins/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-AggregateError.js

Blob: `f786da087d626ed63c7001a66c9dafd543d97084`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Array.js

Blob: `cd4372ef2cf9365005ac68a0b4fd1ebf15d87fd6`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-ArrayBuffer.js

Blob: `3cc43323d2b8404ec6b711f5d4ec8de4d3783ccc`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-BigInt64Array.js

Blob: `3ac3ee4c1e8e7b119e4f8000a7ffac247a153403`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-BigUint64Array.js

Blob: `2930d817a803c14c6161d8cc7b073c2745dfd996`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Boolean.js

Blob: `367987224b45b590130ce86b008495c0e344b435`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-DataView.js

Blob: `61980eecbb666fde175b7d2953d0e6d5af18a0be`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Date.js

Blob: `7481a844d84f9430545e326645d57d2bac5c5367`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Error.js

Blob: `47f359b9105dcab83195f5c239231de3f5018d75`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-EvalError.js

Blob: `2fa23ce6561ed6f129b40ace44fef51b2c841002`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Float32Array.js

Blob: `e97b6a9c7a96770597e8f9bafa345bcfde4211fc`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Float64Array.js

Blob: `03f107e67c8cd3b23badd4c3b3157cd9df8972a2`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Function.js

Blob: `a78cb3c833be523d58f68ca42b6b8164630ad649`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Int16Array.js

Blob: `2db4ba9cd325f70c4b879dbba0dde2e8d21f8319`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Int32Array.js

Blob: `998a7ec0b0406c818eae4c5e911a7a268f811302`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Int8Array.js

Blob: `3da14a4171e573d62a51c81e1ed989467bdf9c53`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Map.js

Blob: `5d642e0d338f94f3cbe85082d9995e90c8becfa9`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Number.js

Blob: `970578e470a789b8199ec3fa7192d5d5c8f64bd8`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Object.js

Blob: `c5a3b317f11462d102c5bfe209b2aa4b227a7f48`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Promise.js

Blob: `e9f59dd1515d20402aa1cf085a40b61e66aa2450`. Role: test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-RangeError.js

Blob: `d08b268c100c28eaa179547f7100b71544d9e215`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-ReferenceError.js

Blob: `76d69bb8bb9ca02751d0a4afe6f2e94891d5044a`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-RegExp.js

Blob: `cbcb238f79c7b2f8cca32bc31b7bac89e5738efd`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Set.js

Blob: `abf77b7a3eba55e8d196cf01ae54c7fe48670042`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-SharedArrayBuffer.js

Blob: `ff42b128e55ecd1e655f1d6abc1c295930ee82a5`. Role: test-path,source. Parse: module.

- Class (anonymous) @12-12

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-String.js

Blob: `b5197f212a9108357dbf90548e79d074dbfa5873`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-SyntaxError.js

Blob: `71120e6eb515d11d83a6364aa7338cb406d3d7ca`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-TypeError.js

Blob: `0990fda4edea2fc49b41e40ff887ef4ca18fddf7`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-URIError.js

Blob: `69d04e2375b11effc1df7757ca09480ae5b4db4b`. Role: test-path,source. Parse: module.

- Class (anonymous) @10-10

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Uint16Array.js

Blob: `4d0898087c0e47a6b7f3811da7d41424016e37e0`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Uint32Array.js

Blob: `ebb0a690230c8cf25a4dd16c30537ffcc6243829`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Uint8Array.js

Blob: `fe118ed742b31643543f79106e9952a0f3101910`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-Uint8ClampedArray.js

Blob: `a23e7662b306385ea393f8a71b58b48052c453c0`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-WeakMap.js

Blob: `8af4b9fc98818d6e9275bfe13c44962e996ed815`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-WeakRef.js

Blob: `2174688a67e6577bd6b3747a06d4fef6e01b5e53`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/class/subclass-builtins/subclass-WeakSet.js

Blob: `0d03d32ff9464df52a6684dfe60fe3a0e8bc5164`. Role: test-path,source. Parse: module.

- Class (anonymous) @11-11

### js/src/tests/test262/language/expressions/coalesce/abrupt-is-a-short-circuit.js

Blob: `fb04d2c0acfbacbeb67ee5d36f45cad6b6358b3c`. Role: test-path,source. Parse: module.

- poison @38-40; FunctionDeclaration; parameters=0; async=false; generator=false
- morePoison @42-44; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-58; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/coalesce/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/cannot-chain-head-with-logical-and.js

Blob: `3341112b8bbdd2c9ff24c5a03363057d4a650153`. Role: test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### js/src/tests/test262/language/expressions/coalesce/cannot-chain-head-with-logical-or.js

Blob: `2cbcae754948dd4b1b279cdd9d33371d015bf3af`. Role: test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### js/src/tests/test262/language/expressions/coalesce/cannot-chain-tail-with-logical-and.js

Blob: `b11323b4fa2f8b727197f8f9498865b7a80de63d`. Role: test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### js/src/tests/test262/language/expressions/coalesce/cannot-chain-tail-with-logical-or.js

Blob: `98326f3dc4c7504440a03ad3c004d2a756007330`. Role: test-path,source. Parse: failed.

Failure: Logical expressions and coalesce expressions cannot be mixed. Wrap either by parentheses


### js/src/tests/test262/language/expressions/coalesce/chainable-if-parenthesis-covered-logical-and.js

Blob: `edcf93b5570f6f0b9a6221b2dccc9ce6515daaf9`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/chainable-if-parenthesis-covered-logical-or.js

Blob: `79e9a6dd9ee29d7ecd92cb31a8fd1400145e4fd4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/chainable-with-bitwise-and.js

Blob: `dac7e04fc4774b2164c2c55185f7b49b342bba9b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/chainable-with-bitwise-or.js

Blob: `214d4fd9aa1778c86ce7824c275e03f3d911a6fa`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/chainable-with-bitwise-xor.js

Blob: `a3b6ad4ab04bfb3b712e61845b795fe236bed543`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/chainable.js

Blob: `09ad90452ab7ab9a97300868306aa073579e45b0`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/follows-null.js

Blob: `82a95419ef99599daca0a2d8028d694145ae0d29`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/follows-undefined.js

Blob: `0728ed1ff27f32c70b9cafc11e0d8e359631e559`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-0.js

Blob: `547f62a1cf2f66f8e8f67b060a8d25a953a1aeea`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-42.js

Blob: `b30d905f2f76470c2df95afcf0533f55cc41dad1`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-empty-string.js

Blob: `c513e2cbc79a2b443888f539454a451f2ad6be4b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-false.js

Blob: `d2357293933c84afe209b20fefee7b82f7f823df`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-object.js

Blob: `5f2eee11e7680563e46c6c8f283ac6417ee1eece`. Role: test-path,source. Parse: module.

- toString @39-41; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @42-44; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-string.js

Blob: `9979a685cce6895d6ef14dfd2d3faf9c4bbb6422`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-symbol.js

Blob: `827c6e8535f5d8853c24e28454fd4daf9d789435`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-number-true.js

Blob: `9b24181ab3e095e7d26f7af57491c5192ca5f337`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/coalesce/short-circuit-prevents-evaluation.js

Blob: `14cbd109e4787fe9a3071de184177271c48126c3`. Role: test-path,source. Parse: module.

- poison @38-40; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/coalesce/tco-pos-null-strict.js

Blob: `9030e2227c780dc616c75d351c67d05986e8a094`. Role: test-path,source. Parse: module.

- f @21-27; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/language/expressions/coalesce/tco-pos-undefined-strict.js

Blob: `70f6ff59ec000781a7f219ce9ab747e1601446cd`. Role: test-path,source. Parse: module.

- f @21-27; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/language/expressions/comma/S11.14_A1.js

Blob: `ed057b15fd9cb9edc8d0e0bfd9d5f11d1df74ea9`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/S11.14_A2.1_T1.js

Blob: `dae097909724af4af56090e4483d8599606dd513`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/S11.14_A2.1_T2.js

Blob: `ae38566aef705533aa93749f070ab8e05bc332d6`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/S11.14_A2.1_T3.js

Blob: `758858f8e820a5f416842e842304fe9de290b97a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/S11.14_A3.js

Blob: `27e20205a1c80fdbfbe88a57a0b800b96b70fd87`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/comma/tco-final-strict.js

Blob: `f3998eb21c3500980466211f7c61f07b6479f139`. Role: test-path,source. Parse: module.

- f @14-20; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-1-s.js

Blob: `860b8ea7f80d6544d5a4c6ec1410ad5f1f478246`. Role: test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-10-s.js

Blob: `2faafbc2c3f87b2769041db91cdc9d8339e58847`. Role: test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-11-s.js

Blob: `eacdde129d901774fe4f00d481721f9473271512`. Role: test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-12-s.js

Blob: `64140e987a2c9bc1cc7b94348188602939af9f95`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-13-s.js

Blob: `fb4937114724183293a83b4f43a350895eb92380`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-14-s.js

Blob: `e765268f7dc893cee77954540ec163e14caa0e2f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-15-s.js

Blob: `7ddb8bc132de1c623d6378f129cf4842e2f276c9`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-16-s.js

Blob: `33163dc7a927b7f67d85dece35cf48f6bce16459`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-17-s.js

Blob: `6ad052276d2322c0f5071bce3de91636ec53eef1`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-18-s.js

Blob: `75bd0d8e4f9c04d015487182d40595796589b050`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-19-s.js

Blob: `dfe7f7f8e5b1cd04e89791fa6217d2f3acc8a30f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-2-s.js

Blob: `a5010a29ec409529d9f78ec9e9b2630196d62f69`. Role: test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-20-s.js

Blob: `dbecd1e14d610da62b8b51200ff38364a8e038d0`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-21-s.js

Blob: `525d3374a4a02cabd1e53d26058fc74105fd1b74`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-22-s.js

Blob: `e8fd2bac20fad3ae386268cf5103b11daa42b96c`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-23-s-strict.js

Blob: `dbfb3f9fdb115f77bbf9f2d71ab05dc3b7a7963d`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-24-s-strict.js

Blob: `4f827d66c45eeb47590914206bf572115ccf46d0`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-25-s-strict.js

Blob: `761ab24cc48454db0dec9a2f1734db41eb54e0e7`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-26-s-strict.js

Blob: `63d5b60be30bb47ad801a8e59e852c82218e1423`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-27-s-strict.js

Blob: `ac762ff2f3f9508bc7ce3650f689cd30638a1ea3`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-28-s-strict.js

Blob: `ab81ebf7e54235d848bb954b04322c3a5bf092e5`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-29-s-strict.js

Blob: `2f532dcc83dc71285450a68357d2c89c2edc72bb`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-30-s-strict.js

Blob: `e4be71b5bfcec7efe0b675398b99d51eebf4b45a`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-31-s-strict.js

Blob: `151abacdd2bb571fdaa50c400cf1319ca82b97e8`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-32-s-strict.js

Blob: `8c3f5cc1459f9e31f2d87d2b73126239e84f2098`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-33-s-strict.js

Blob: `a8bf7c873a99b9d56324bf58db837eb3af2130ab`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-34-s-strict.js

Blob: `d00083772395d9c1fe473ed212796f879c9d6cd1`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-35-s-strict.js

Blob: `4b30aabdf90a7cb2340767205b17ec29a5d85c40`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-36-s-strict.js

Blob: `0a475a6aad135334b93390fb196e0cf9f75746b0`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-37-s-strict.js

Blob: `46ca3ff6085166f05b361b54da5e9f9be07eef82`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-38-s-strict.js

Blob: `392974d4c7c2c470c6dd75f1baa1b6de3ab2a5b7`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-39-s-strict.js

Blob: `c23720a86b3702be66058e5fa01e362c2c7240ca`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-4-s.js

Blob: `1bb1260b969a54d14d1499fe578a7c6ac05e83a6`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-40-s-strict.js

Blob: `04bc4602d4bdf838d4530a7bd881882fc1ffc781`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-41-s-strict.js

Blob: `29d9c2fe2180a77d9f79a2802bf623a8a7e96871`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-42-s-strict.js

Blob: `5e5a07de71f99e8f325d29b8bd33447756803eac`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-43-s-strict.js

Blob: `4a0468bd1519f4db524ea191a8fe1e76154b72ce`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-44-s-strict.js

Blob: `8264e12584cede6ae731e1c653bce99ba937d0f3`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-45-s-strict.js

Blob: `3e6aca427de7ea0faf3fa71ebdf442af4b372415`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-46-s-strict.js

Blob: `fe68ee898533835ba624fbb242b95f5c8f1072cd`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-47-s-strict.js

Blob: `8b9086b469d2614e8a5c00e78371a0fdb6d760c0`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-48-s-strict.js

Blob: `89ec389e677d8e1a517b789a13f25fe8238d4b82`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-49-s-strict.js

Blob: `5636fadc11ce98cec2eca299e5229fc8ac6f0509`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-5-s.js

Blob: `ec5931d0e6674c204d242dfa9ac96526544b1b50`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-50-s-strict.js

Blob: `a3ddae6c1a7de03ae3b84801e7b0b0993998bd8c`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-51-s-strict.js

Blob: `e257753fff94cd1c9cd9306445b98612db10847f`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-52-s-strict.js

Blob: `650f489673bb1b0d7562f1cd2123089460c13f77`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-53-s-strict.js

Blob: `4ba94616ce7a4b744c6eddcc63d3571ce0be6c33`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-54-s-strict.js

Blob: `3f50e7bd1a88899004263f752d61b4c941376519`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-55-s-strict.js

Blob: `f3e49586aa8ad0cb77e768886755f0e67837b089`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-6-1gs-strict.js

Blob: `e8aa0127d3f9f10073966ee19583321afd73002c`. Role: test-path,source. Parse: failed.

Failure: Assigning to eval in strict mode


### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-6-s.js

Blob: `9e3576dfcb0895a1ed8e7d550d60b48325a4c8b2`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-8-s.js

Blob: `820436d1dd98a6f0468e3ae848ec7769663b7c7e`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/11.13.2-9-s.js

Blob: `19586dc2ec35908e83ce16ca58bbe525aa885bdc`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.1.js

Blob: `7e2334171d4fada6225aa5b59196aa537c5e5eb3`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.10.js

Blob: `c5be69d56841f28cf7bdd94f5b8a35865821fbb4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.11.js

Blob: `210c91c8d2ef264f0523df600a0ccefe28ef2545`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.2.js

Blob: `955514fd90afc19a555c1e3c52b6b893a3bc1f48`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.3.js

Blob: `f7ca64f6f50fa5abc07320dc8c13c75e13307ffe`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.4.js

Blob: `0bd848bd884f46dc033f3fe2f936ae0b2942b18a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.5.js

Blob: `9e35143575b459593aa0346eb85916c3d9f910ed`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.6.js

Blob: `8f6a835c17028652a3414a82cba0dad39705c4b5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.7.js

Blob: `844b57e2b13c175ea066b42d635e6d244c456f44`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.8.js

Blob: `88a43f406b5e923ad0e81c6bea30a7ff2462ecf8`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T1.9.js

Blob: `c51adfbd94d01747f5b37cda947ca78312613699`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.1.js

Blob: `b9a3dace1c3eaa0b9a7597281f04973bd0754645`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.10.js

Blob: `2875b2aac783ccbc52269171874c0b3496e9b797`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.11.js

Blob: `72f3178b6760b83c635a44200d05a88d5a8baa8d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.2.js

Blob: `b029bb82b292e12c1c42664ee89cbf399a10f484`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.3.js

Blob: `8a26baad37e5d8e9605133e5b2b5726cd343b1d1`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.4.js

Blob: `1c646645563b3476d0263adcc5322a56865bedd2`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/expressions/compound-assignment/S11.13.2_A2.1_T2.5.js

Blob: `59e817b30c337428abc3aca4ef1f30d701d0fb14`. Role: test-path,source. Parse: module.


## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [7ee67609-e080-45b3-a0b1-aa16a2488dcc.md](7ee67609-e080-45b3-a0b1-aa16a2488dcc.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `9c1cb694b21faf835988cb003918f56507a596cbed673b70dc0ba0d893c7d51e`.
