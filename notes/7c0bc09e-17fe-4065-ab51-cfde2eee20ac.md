<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["f731d094c4dbe8848ca38c86586b050eae3f7f2058de98707fc2d7e26ad84443"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/b7e2831c-544c-4b65-a016-2b3fa842f020.md"}} -->
# firefox/js JavaScript function map 403

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/test262/built-ins/Promise/prototype/catch/not-a-constructor.js

Blob: `3afa8a1021f0ec6e5972fb946d34f16837a2d8f6`. Role: test-path,source. Parse: module.

- (anonymous) @30-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/catch/prop-desc.js

Blob: `ed7d63bbce5da2a10fcc01b5be53379e6391c7c4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/catch/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/catch/this-value-non-object.js

Blob: `888c8b39f50097eb142bebeb2a95a9cdf30f14c4`. Role: test-path,source. Parse: module.

- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/catch/this-value-obj-coercible.js

Blob: `4f71abec7ab1ec7d95cec9b90a6e65c9aa9ae985`. Role: test-path,source. Parse: module.

- Boolean.prototype.then @26-28; FunctionExpression; parameters=0; async=false; generator=false
- Number.prototype.then @33-35; FunctionExpression; parameters=0; async=false; generator=false
- String.prototype.then @40-42; FunctionExpression; parameters=0; async=false; generator=false
- Symbol.prototype.then @47-49; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/catch/this-value-then-not-callable.js

Blob: `861f78bd9aca940dbbcff1b29d2779bd807b3115`. Role: test-path,source. Parse: module.

- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-55; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-61; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-67; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-73; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/catch/this-value-then-poisoned.js

Blob: `190776f246232a01ecc6fa770c6e40149e72d3b3`. Role: test-path,source. Parse: module.

- get @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/catch/this-value-then-throws.js

Blob: `39cd7cf5de40c27e8517de3aed044df804caa203`. Role: test-path,source. Parse: module.

- then @33-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/invokes-then-with-function.js

Blob: `033051d03c4caeb02e369dab16b5969d3250fd9b`. Role: test-path,source. Parse: module.

- (anonymous) @11-11; FunctionExpression; parameters=0; async=false; generator=false
- target.then @19-28; FunctionExpression; parameters=2; async=false; generator=false
- originalFinallyHandler @30-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-65; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/invokes-then-with-non-function.js

Blob: `ca7b36445ccb215cead3130099d762fe5d1a3379`. Role: test-path,source. Parse: module.

- (anonymous) @10-10; FunctionExpression; parameters=0; async=false; generator=false
- target.then @19-28; FunctionExpression; parameters=2; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/is-a-function.js

Blob: `19abfde2fa5e20a6080998e6c4e62d7426e26e59`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/is-a-method.js

Blob: `741b127248214d34df66f155e9f54cb0722d7dd6`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/length.js

Blob: `1146a91f1d69e99ce6c97c50a14a32478c69ef31`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/name.js

Blob: `ad825c9f5310d5cd2465a121ed110399aaac7306`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/not-a-constructor.js

Blob: `61ba99df53592a9d6cd81aff8e5b45b489b8a862`. Role: test-path,source. Parse: module.

- (anonymous) @30-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/prop-desc.js

Blob: `82bcc4fcf7013cf329659a1af1e639dc4093b562`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/rejected-observable-then-calls-PromiseResolve.js

Blob: `ecdbbdd1647600ad5a2bf36faa23476c70b6d846`. Role: test-path,source. Parse: module.

- Promise.prototype.then @34-37; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @39-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MyPromise @26-26

### js/src/tests/test262/built-ins/Promise/prototype/finally/rejected-observable-then-calls-argument.js

Blob: `49cb4840ff5bc4a7a4142c7c2c286aefb99dba88`. Role: test-path,source. Parse: module.

- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- Promise.prototype.then @43-69; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class MyError @21-21

### js/src/tests/test262/built-ins/Promise/prototype/finally/rejected-observable-then-calls.js

Blob: `2d4dd9caaf630e64d62cf07e5ac211695e1a200c`. Role: test-path,source. Parse: module.

- no.then @15-18; FunctionExpression; parameters=0; async=false; generator=false
- yes.then @22-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-31; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/rejection-reason-no-fulfill.js

Blob: `3903e7778ba607dfece9c9a65f3ffed1b1339a9a`. Role: test-path,source. Parse: module.

- (anonymous) @18-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-30; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/rejection-reason-override-with-throw.js

Blob: `66b6a468b32adf73331c7d9fe758bd99dbddb1e2`. Role: test-path,source. Parse: module.

- (anonymous) @18-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-30; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/resolution-value-no-override.js

Blob: `4951119385bbee162f81ab1ea7b81dbec5d7cc22`. Role: test-path,source. Parse: module.

- (anonymous) @16-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-23; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/resolved-observable-then-calls-PromiseResolve.js

Blob: `137448ae6f91fb371668f20a58ce78e2e0e140b7`. Role: test-path,source. Parse: module.

- Promise.prototype.then @34-37; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @39-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MyPromise @26-26

### js/src/tests/test262/built-ins/Promise/prototype/finally/resolved-observable-then-calls-argument.js

Blob: `0f9fc558c5b1f42ac65ea3b567399b9501219880`. Role: test-path,source. Parse: module.

- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Promise.prototype.then @34-55; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/resolved-observable-then-calls.js

Blob: `4f2341bfb063212c4576a3dcf26267ef50f3fdff`. Role: test-path,source. Parse: module.

- yes.then @15-18; FunctionExpression; parameters=0; async=false; generator=false
- no.then @22-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-31; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/finally/species-constructor-throws.js

Blob: `c1b7003a8955b8cdc520210867e3b802337ad977`. Role: test-path,source. Parse: module.

- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/species-constructor.js

Blob: `00c1127836cb6511a1490bed48b7aba08091a88f`. Role: test-path,source. Parse: module.

- constructor @15-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class FooPromise @14-19

### js/src/tests/test262/built-ins/Promise/prototype/finally/subclass-reject-count.js

Blob: `6bf6504a224373dc1b1994dca70f54891a1b790e`. Role: test-path,source. Parse: module.

- constructor @14-17; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class FooPromise @13-18

### js/src/tests/test262/built-ins/Promise/prototype/finally/subclass-resolve-count.js

Blob: `6af753fa66c0fb30a97d5d560b4240d8ebac2c85`. Role: test-path,source. Parse: module.

- constructor @14-17; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class FooPromise @13-18

### js/src/tests/test262/built-ins/Promise/prototype/finally/subclass-species-constructor-reject-count.js

Blob: `9e9995fc919def5667375306428471be62b5c9c2`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class FooPromise @10-14

### js/src/tests/test262/built-ins/Promise/prototype/finally/subclass-species-constructor-resolve-count.js

Blob: `e5049b734969ab4df5e2335d553bfbcdfc26cf87`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class FooPromise @10-14

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-non-object.js

Blob: `8c9ec2e7bdd35e91ba522ea925fd3be5ff269fd8`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-proxy.js

Blob: `15ca9b1d7c51d1256c2e766e02a841ec82f9b4bc`. Role: test-path,source. Parse: module.

- Promise.prototype.then @14-16; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-then-not-callable.js

Blob: `ad5c687d6b8c81127315e02184a0f291390fa93b`. Role: test-path,source. Parse: module.

- thrower @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-then-poisoned.js

Blob: `44e41739892d8e23d88f548bfbee9ad2cd757a59`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; FunctionExpression; parameters=0; async=false; generator=false
- get @13-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-then-throws.js

Blob: `536ed241713edeebcf41df31acb08996bb808932`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; FunctionExpression; parameters=0; async=false; generator=false
- thrower.then @13-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/finally/this-value-thenable.js

Blob: `dccb5be50c8c2605d5274b9cf8d896a8fdbb3656`. Role: test-path,source. Parse: module.

- Thenable @11-11; FunctionExpression; parameters=0; async=false; generator=false
- Thenable.prototype.then @12-12; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/no-promise-state.js

Blob: `096249ac1d63be4f2d3f3b8434449f8409a87e55`. Role: test-path,source. Parse: module.

- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/prop-desc.js

Blob: `01a836d2380ab33056b45cb7ec44c89460ab129c`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/proto.js

Blob: `d0fb702c393c64a05d73b1846f77aadc0328c717`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.4_A1.1_T1.js

Blob: `30133bb8963975d17e21a8467c286a087fa4b8fb`. Role: test-path,source. Parse: module.

- (anonymous) @18-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.4_A2.1_T1.js

Blob: `2b504506bb9a760f920ea0c883a267d8b9e39df4`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.4_A2.1_T2.js

Blob: `c689e07f99e1fbf1d77501fb1fc0638203d8b01a`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-39; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.4_A2.1_T3.js

Blob: `dc1f0d723378d79ef07962038fdfc73ca6db7ba1`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @30-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A1.1_T1.js

Blob: `959bc284dc8e7d02132348fefd62fc04218e4899`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A1.1_T2.js

Blob: `c89023e08383f6538f1c816337f512db2fccd5e7`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A2.1_T1.js

Blob: `a4e20bae960361f2e7f9526439916d3684087626`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A2.1_T2.js

Blob: `4a982b5675d1b6bd74412e9c9c269dea65a2ed66`. Role: test-path,source. Parse: module.

- ZeroArgConstructor @12-12; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A4.1_T1.js

Blob: `8fc66ab9642cd3d655b8b0cd031559320686f7c3`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A4.1_T2.js

Blob: `3aeca23d955aa6c6442d188592e46cbde88d51aa`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-22; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A4.2_T1.js

Blob: `5b1ac21b2714fd85ee739ae02752734fb1e57ced`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A4.2_T2.js

Blob: `5efe836020e4df71c3b18a51d2e03a561ba67b04`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-22; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A5.1_T1.js

Blob: `2f0b062faef0efe1eebacaf62c92d970eafd1a31`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @24-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-36; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A5.2_T1.js

Blob: `6e09de73a171dbff84920375c60c73192bd127c3`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @26-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-38; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/S25.4.5.3_A5.3_T1.js

Blob: `87a2b2271b1b857d659a8f729dc894ff2a1e0814`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-42; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/capability-executor-called-twice.js

Blob: `de6cea80256ff147fb8d94a04623d48fe1fa09cd`. Role: test-path,source. Parse: module.

- constructor @29-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-36; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @39-45; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @50-56; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-70; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @62-68; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @64-64; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-83; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @75-81; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-96; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @88-94; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @92-92; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-92; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @28-36

### js/src/tests/test262/built-ins/Promise/prototype/then/capability-executor-not-callable.js

Blob: `ed3dee89ae1c1aea9511020ffbe6d1905d6a07cb`. Role: test-path,source. Parse: module.

- constructor @31-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-46; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @42-44; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-57; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @51-55; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-68; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @62-66; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @72-79; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @73-77; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @75-75; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-90; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @84-88; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @86-86; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @94-101; FunctionExpression; parameters=0; async=false; generator=false
- constructorFunction @95-99; FunctionExpression; parameters=1; async=false; generator=false
- Class (anonymous) @30-38

### js/src/tests/test262/built-ins/Promise/prototype/then/context-check-on-entry.js

Blob: `794407fa72294a92e9dafd6e006f410de0612fa4`. Role: test-path,source. Parse: module.

- constructor @17-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-access-count.js

Blob: `9c54c46ac46eac28b368e8a7ca0472941af9b975`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false
- get @37-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-52; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-custom.js

Blob: `0ad80c75133627291efbd764e90e9f36a5e73377`. Role: test-path,source. Parse: module.

- executor @17-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- constructor @20-26; FunctionExpression; parameters=1; async=false; generator=false
- p1.constructor @30-30; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @19-27

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-null.js

Blob: `a0b6df2a9e7ed867a96cedf1b30cc37dceb9760c`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-poisoned.js

Blob: `c0bb06362d6a007df8b7fd0a307d5fd15ef7c367`. Role: test-path,source. Parse: module.

- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-throws.js

Blob: `2f909cce80efb603b88a1ac7e415e87e6712975b`. Role: test-path,source. Parse: module.

- BadCtor @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/ctor-undef.js

Blob: `513f9d6cb6cc5eef29febf78cd37e0dbc8c87914`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/deferred-is-resolved-value.js

Blob: `fd2f6f1cf513dccf995d470a60e043cea6ef72d9`. Role: test-path,source. Parse: module.

- constructor @45-59; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @48-51; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=1; async=false; generator=false
- Class P @44-60

### js/src/tests/test262/built-ins/Promise/prototype/then/length.js

Blob: `2ada466b80b444079eef0ed75178002d250c6ae2`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/name.js

Blob: `82402ea992a2567d185551bf5a3b9c728aba5c6d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/not-a-constructor.js

Blob: `d04c89e111804e38659c543e9cfe1521d4524f8b`. Role: test-path,source. Parse: module.

- (anonymous) @30-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/prfm-fulfilled.js

Blob: `89d5e2de5fecd75dd7aa34aa3d55acfcca4efab3`. Role: test-path,source. Parse: module.

- (anonymous) @24-26; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-34; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/prfm-pending-fulfulled.js

Blob: `93204370cdbc2f10ab1791670e762e23192767b6`. Role: test-path,source. Parse: module.

- (anonymous) @25-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/prfm-pending-rejected.js

Blob: `b65b5596ce071a9f9a1008afd039eae0ffb66ab6`. Role: test-path,source. Parse: module.

- (anonymous) @25-27; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-37; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/prfm-rejected.js

Blob: `4b74b5f3cb66342b0236292f27c27576cf0be1ec`. Role: test-path,source. Parse: module.

- (anonymous) @24-26; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-36; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/prop-desc.js

Blob: `a52a5ab2c1b57ede2fd2020436149b075ece809c`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/prototype/then/reject-pending-fulfilled.js

Blob: `7795f1bb2a0eda863e0d472c2e63a839f03fcd62`. Role: test-path,source. Parse: module.

- (anonymous) @26-28; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-47; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/reject-pending-rejected.js

Blob: `72c27c684c28f425405532fa38514797eda2a0b1`. Role: test-path,source. Parse: module.

- (anonymous) @27-29; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-48; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/reject-settled-fulfilled.js

Blob: `56dbd6fff3c9ab96ec0b2e6c9eb11537fa9459e5`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-54; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/reject-settled-rejected.js

Blob: `0f87c6bb01a32f739c8601452b75981c0dad427c`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @41-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-54; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-non-obj.js

Blob: `fd6602988ba402f87bc170caca87ed42665579cc`. Role: test-path,source. Parse: module.

- (anonymous) @26-28; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-non-thenable.js

Blob: `e71b639f39450fbaebc8bf8cfc35ef5ceacc685f`. Role: test-path,source. Parse: module.

- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-50; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-52; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-poisoned-then.js

Blob: `88c3cd57a526f82f368d3db04fd0650f1d4c9607`. Role: test-path,source. Parse: module.

- get @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-52; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-prms-cstm-then.js

Blob: `147ce71f22af2a4d4d6f3a241a21539c94f84955`. Role: test-path,source. Parse: module.

- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=1; async=false; generator=false
- thenable.then @42-44; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-48; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-57; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-59; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-self.js

Blob: `1191706a68e075bd35d6a793e3aa4f1ffec332a4`. Role: test-path,source. Parse: module.

- (anonymous) @28-30; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-51; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-fulfilled-thenable.js

Blob: `52ad8d2366099354a85fb6c27df3bbe21922b6e2`. Role: test-path,source. Parse: module.

- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-53; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @53-55; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-non-obj.js

Blob: `1480ad1f5f7bbc289b859148721c3e8bce8fc72f`. Role: test-path,source. Parse: module.

- (anonymous) @27-29; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-43; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-non-thenable.js

Blob: `19764d8de7a6c4287857144e4179f49440ef256c`. Role: test-path,source. Parse: module.

- (anonymous) @35-37; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-51; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-53; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-poisoned-then.js

Blob: `542c6e7eadec2061bb04ddb7daebccdde857fad5`. Role: test-path,source. Parse: module.

- get @31-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-37; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-53; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-prms-cstm-then.js

Blob: `4a3fbc16749c52108f0f6f56fc07f9243721a47e`. Role: test-path,source. Parse: module.

- (anonymous) @35-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=2; async=false; generator=false
- thenable.then @43-45; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @47-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-58; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-60; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-self.js

Blob: `7a31dc46bc9c328ec1129c3fa67b07fda8da9215`. Role: test-path,source. Parse: module.

- (anonymous) @29-31; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-52; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-pending-rejected-thenable.js

Blob: `775bb1f79f9be9f492852599a7f31e2b990f9600`. Role: test-path,source. Parse: module.

- (anonymous) @35-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-54; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-56; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-non-obj.js

Blob: `5f6494fa3a454aa071a37daed4931b004c6c08e4`. Role: test-path,source. Parse: module.

- (anonymous) @32-34; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-48; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-non-thenable.js

Blob: `3ca031489f6054919bb26fd5cf623b3e8adda70f`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-56; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-58; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-poisoned-then.js

Blob: `ab5ee4a7273a482d4a8be94bbaa015020e194b19`. Role: test-path,source. Parse: module.

- get @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-51; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-58; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-prms-cstm-then.js

Blob: `5594511e3442232bdc00ecaea4cf9d88dd3b7999`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=1; async=false; generator=false
- thenable.then @48-50; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-63; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-65; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-self.js

Blob: `89c4f064b8aa49fd11641a0e86ded86bf6f191c5`. Role: test-path,source. Parse: module.

- (anonymous) @34-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-57; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-fulfilled-thenable.js

Blob: `f978984c3640acabc3952cb835cab653420b19d1`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-59; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-61; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-non-obj.js

Blob: `1d39308386c49ba4b6af873b05aa7a3bf57c204a`. Role: test-path,source. Parse: module.

- (anonymous) @32-34; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-48; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-non-thenable.js

Blob: `eae6797f1a54e9a55d793b77eb0e10b2cef1dc77`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-56; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-58; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-poisoned-then.js

Blob: `2f33c820bb87a37b9d9b9fd6a8793648740fe3a4`. Role: test-path,source. Parse: module.

- get @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-51; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-58; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-prms-cstm-then.js

Blob: `303a5315b0adfde5ac3937a2a4baa4dd534a4561`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=2; async=false; generator=false
- thenable.then @48-50; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-63; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-65; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-self.js

Blob: `a585ca9b2ebeaeb82dd539c6dd1e477f17587b38`. Role: test-path,source. Parse: module.

- (anonymous) @34-36; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @39-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-57; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/resolve-settled-rejected-thenable.js

Blob: `827ff855f68e8809961acb99e9f6b46e57576aca`. Role: test-path,source. Parse: module.

- (anonymous) @40-42; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-48; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-59; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-61; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-invoke-nonstrict.js

Blob: `61fd431b65a37aff3bd6d860b4bcea5bf41f8c72`. Role: test-path,source. Parse: module.

- (anonymous) @19-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-invoke-strict-strict.js

Blob: `3c0ab9a54d0557da38adc34c30d21f0995255856`. Role: test-path,source. Parse: module.

- (anonymous) @20-37; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-39; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-next-abrupt.js

Blob: `ec9ab0172bf639ee4b5b43418a9cf898315914bb`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-46; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-next.js

Blob: `13fb4ca62f26a897305ca514dc6bcc4d39dddf01`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-54; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-return-abrupt.js

Blob: `a394847ce9a7701635b24de533bd85a4b01451d3`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-51; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-fulfilled-return-normal.js

Blob: `5acd838f06bc480b59df546539c36ea5c3210e13`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-49; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-51; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-identity.js

Blob: `d559176177bfe5b7871a13d5365c6ba72cf50c6d`. Role: test-path,source. Parse: module.

- (anonymous) @17-23; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-invoke-nonstrict.js

Blob: `0b548a01f53eadf96ac55ea3f0b342fb1acde101`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-38; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-invoke-strict-strict.js

Blob: `09f0954c0df9e8f4de53a61c505bce90c2cdf9ed`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-39; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-next-abrupt.js

Blob: `681f4fabc188e3d39947912af9ad3a71cefae24b`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-46; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-next.js

Blob: `d88d3e1a48450896a1d7b47eb7e4d6ec6d0560f3`. Role: test-path,source. Parse: module.

- (anonymous) @19-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-54; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-return-abrupt.js

Blob: `8b894568537c288c149083e8cab2e551c5af7e46`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-51; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-rejected-return-normal.js

Blob: `d29489baa8132978d5c8e3e89aaeba94f958d133`. Role: test-path,source. Parse: module.

- (anonymous) @33-35; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-49; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-51; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/rxn-handler-thrower.js

Blob: `6961da914eec83536248c627fadf37fc8bf37314`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-25; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/prototype/then/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A1.1_T1.js

Blob: `fadedf1e242d884b38cf88398867268af56dcb67`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A2.1_T1.js

Blob: `0200158ab594b330d3fde8710b486ad0864a37a3`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A2.2_T1.js

Blob: `1adfb40d633d6ff439dfcbfa3d29b99b9a299794`. Role: test-path,source. Parse: module.

- (anonymous) @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-19; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A2.2_T2.js

Blob: `3555d007f734090230e33e4db54a62b9d042fde7`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-17; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A2.2_T3.js

Blob: `7e8f21d0daf2acbee1ddb4d965386d5e583de57f`. Role: test-path,source. Parse: module.

- get @19-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A3.1_T1.js

Blob: `8e015624621c0f4296177a399627161e21b57e22`. Role: test-path,source. Parse: module.

- ZeroArgConstructor @14-14; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A3.1_T2.js

Blob: `ac83127e8fc24b6cb5807b284ab49b94666988cb`. Role: test-path,source. Parse: module.

- BadPromiseConstructor @14-16; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A4.1_T1.js

Blob: `e4602242f2e74822bf9ef4c3335f9499bb3f0e1e`. Role: test-path,source. Parse: module.

- iterThrows.[computed] @15-21; FunctionExpression; parameters=0; async=false; generator=false
- next @17-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A4.1_T2.js

Blob: `c8aeb4602f4029f6cee3e9572caca3c43bebc721`. Role: test-path,source. Parse: module.

- get @15-27; FunctionExpression; parameters=0; async=false; generator=false
- next @17-25; FunctionExpression; parameters=0; async=false; generator=false
- get @20-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A5.1_T1.js

Blob: `e8dfc87992c9106547ac1a56ab08f6f28768775b`. Role: test-path,source. Parse: module.

- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A6.1_T1.js

Blob: `27dd872a3c5a452d751f94e47c3e163cfd5bdf29`. Role: test-path,source. Parse: module.

- (anonymous) @19-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A6.2_T1.js

Blob: `5be746bfab40fd93cd51bc281a8d79636f695c8f`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-36; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.1_T1.js

Blob: `768f25c8427741bf71644e5bcacdd8245df1e27b`. Role: test-path,source. Parse: module.

- (anonymous) @21-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-37; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.1_T2.js

Blob: `72b7200f85963e4956058b77d4fccb73f027cd9e`. Role: test-path,source. Parse: module.

- (anonymous) @16-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-37; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.1_T3.js

Blob: `ce763b023abddf698a5ad2ebe07ea270c263a98c`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-37; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.2_T1.js

Blob: `b38ba8eae62e3eb869fa1efea5c770ded147988d`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-29; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-39; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.3_T1.js

Blob: `303441a11d6c2efba50eaa2217d2b4d038bb7cd1`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/S25.4.4.3_A7.3_T2.js

Blob: `7081e0b3f7ebe849883a8c546764b02c352dbeae`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-18; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Promise/race/capability-executor-called-twice.js

Blob: `47dc31e96dfe3b29a492b12e138b85964cca20c8`. Role: test-path,source. Parse: module.

- fn1 @26-32; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @30-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; FunctionExpression; parameters=0; async=false; generator=false
- fn1.resolve @33-35; FunctionExpression; parameters=0; async=false; generator=false
- fn2 @40-46; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- fn2.resolve @47-49; FunctionExpression; parameters=0; async=false; generator=false
- fn3 @54-60; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @56-56; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-58; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-58; FunctionExpression; parameters=0; async=false; generator=false
- get @62-62; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-66; FunctionExpression; parameters=0; async=false; generator=false
- fn4 @70-76; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @72-72; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-74; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-74; FunctionExpression; parameters=0; async=false; generator=false
- get @78-78; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-82; FunctionExpression; parameters=0; async=false; generator=false
- fn5 @86-92; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @90-90; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @90-90; FunctionExpression; parameters=0; async=false; generator=false
- get @94-94; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-98; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/capability-executor-not-callable.js

Blob: `d5e5bc4783d76204ea9a327c952475236dc31383`. Role: test-path,source. Parse: module.

- (anonymous) @28-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-31; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-41; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-51; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-62; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-61; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-59; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-72; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @67-71; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-69; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-82; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-81; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/ctx-ctor-throws.js

Blob: `81988b5dea227bed89e068de87916c1352878daa`. Role: test-path,source. Parse: module.

- CustomPromise @20-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/ctx-ctor.js

Blob: `105b3fba4c7330c1ee3592814ce71e8ba5d16693`. Role: test-path,source. Parse: module.

- constructor @24-28; FunctionExpression; parameters=1; async=false; generator=false
- Class SubPromise @23-29

### js/src/tests/test262/built-ins/Promise/race/ctx-non-ctor.js

Blob: `5b6b4d7af4d6e1fd567b351d70a0f9319e6491d3`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/ctx-non-object.js

Blob: `c2dd20aa00cb9825b4c9dfa11ff688feabe66fce`. Role: test-path,source. Parse: module.

- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/invoke-resolve-error-close.js

Blob: `a152a8b46c7ed1d4d8ce2c32c946f45a1a29d32a`. Role: test-path,source. Parse: module.

- iterDoneSpy.[computed] @28-41; FunctionExpression; parameters=0; async=false; generator=false
- next @30-35; FunctionExpression; parameters=0; async=false; generator=false
- return @36-39; FunctionExpression; parameters=0; async=false; generator=false
- Promise.resolve @43-45; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/invoke-resolve-error-reject.js

Blob: `00a17b05688fc43a343bf2990f37fae065218919`. Role: test-path,source. Parse: module.

- CustomPromise @27-29; FunctionExpression; parameters=1; async=false; generator=false
- CustomPromise.resolve @31-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-41; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/invoke-resolve-get-error-reject.js

Blob: `d5cb47473089ce5d31906cdf07f4f68ab8728210`. Role: test-path,source. Parse: module.

- get @29-31; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/invoke-resolve-get-error.js

Blob: `8c0b8224f929fd83c4ca62fdc07faebfb11f30eb`. Role: test-path,source. Parse: module.

- (anonymous) @25-27; FunctionExpression; parameters=0; async=false; generator=false
- get @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-41; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Promise/race/invoke-resolve-get-once-multiple-calls.js

Blob: `38a700ed212423aaf8cd16e39c0bac56e7ad5bb1`. Role: test-path,source. Parse: module.

- get @29-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-34; FunctionExpression; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [b7e2831c-544c-4b65-a016-2b3fa842f020.md](b7e2831c-544c-4b65-a016-2b3fa842f020.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `f731d094c4dbe8848ca38c86586b050eae3f7f2058de98707fc2d7e26ad84443`.
