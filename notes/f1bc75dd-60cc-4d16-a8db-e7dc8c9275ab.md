<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["2d06bd97f8465c673b398f21dd97bed8fc9bc3c18881d52690ea0b69c9d95504"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/b6555af2-7c18-46de-962c-4a8630cf437b.md"}} -->
# firefox/testing JavaScript function map 1156

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/accumulator-set-to-initial-value.js

Blob: `ddc00b9910974d928f457e7f7990c8f75fa5760a`. Role: imported-path,test-path,source. Parse: module.

- reducer @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/check-fn-after-getting-iterator.js

Blob: `065f958cc135640bb54503fedb5cbfc9ba7e651a`. Role: imported-path,test-path,source. Parse: module.

- get @16-19; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @16-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- next @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @22-26

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/descriptor.js

Blob: `716e25c280b2695052bc3b4191f5c05d7e8bde90`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/empty-iterator-without-initial-value-throws.js

Blob: `902dd6e7c0f1ae4161d446948061ac479db3e3e9`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/error-from-correct-realm.js

Blob: `76db994f07754b2ebf34e8016b15a91adbc3ebf1`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/iterator-empty-return-initial-value.js

Blob: `67a6e13ac18f3c13a85b9842193baa76e08ea185`. Role: imported-path,test-path,source. Parse: module.

- reducer @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/iterator-next-return-non-object-throws.js

Blob: `2dc9f1b328f6047ac856769265d694c387bcfe33`. Role: imported-path,test-path,source. Parse: module.

- constructor @15-18; FunctionExpression; parameters=1; async=false; generator=false
- next @20-22; FunctionExpression; parameters=0; async=false; generator=false
- sum @25-25; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-23

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/left-associative.js

Blob: `0bb9a18552671586b7e3fff1afa2b1ea144a33be`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/length.js

Blob: `7d908933a1f01acd4f092641c1b1ab9aa1384bfe`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/name.js

Blob: `cbc759b81fcf860f6f6a64e93f6ca9349ccf7bf2`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/next-throws-iterator-not-closed.js

Blob: `73d7864fa33466656146832b596c3654875d1db6`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- return @20-22; FunctionExpression; parameters=0; async=false; generator=false
- sum @25-25; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-23

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/no-initial-value-set-accumulator-to-first-value.js

Blob: `c0a00b29988e447eea4aa856a0abeaa17cabaa3c`. Role: imported-path,test-path,source. Parse: module.

- reducer @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/proxy.js

Blob: `daed39411056d6a36eb3d4225de97f92b49e2275`. Role: imported-path,test-path,source. Parse: module.

- get @18-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- next @26-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class Counter @24-34

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/reduce.js

Blob: `894d20bccf2a71b61b21fc20ab5df21e7a5ce757`. Role: imported-path,test-path,source. Parse: module.

- reducer @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/reducer-not-callable-throws.js

Blob: `b4b89f915828e3edc488ad89a8cfd57cda84ce88`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-18

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/reducer-throws-iterator-closed.js

Blob: `80fda0f9c60f22e648b24f1a1ea489048715d067`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- return @20-22; FunctionExpression; parameters=0; async=false; generator=false
- reducer @25-25; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-23

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/this-not-iterator-throws.js

Blob: `a49eec76757afb616b85128248a4b3e24847462a`. Role: imported-path,test-path,source. Parse: module.

- sum @14-14; ArrowFunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/reduce/value-throws-iterator-not-closed.js

Blob: `ab228ef6bdaf211378a485f007f60bff0fcca06e`. Role: imported-path,test-path,source. Parse: module.

- next @16-22; FunctionExpression; parameters=0; async=false; generator=false
- get @17-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- return @25-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class TestIterator @15-28
- Class TestError @14-14

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/check-fn-after-getting-iterator.js

Blob: `c026d662dcb4455c35f59e93a75cdafde8fd34de`. Role: imported-path,test-path,source. Parse: module.

- get @16-19; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @16-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- next @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @22-26

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/coerce-result-to-boolean.js

Blob: `9d10f0e85ecdc468ed975d71bc842860895dbc0c`. Role: imported-path,test-path,source. Parse: module.

- fn @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/descriptor.js

Blob: `d5c34dfbb8d774b5c46052b7afc91dd12bc2d92d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/error-from-correct-realm.js

Blob: `7639cc1eb4820598b39d0171b56839e14f7635bc`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/fn-not-callable-throws.js

Blob: `dfc328c137bec3e0d18e4a3d802f052940dea329`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/fn-throws-close-iterator.js

Blob: `c1d444fdd9fa785ac8cf2780ebc7d23837c43bf3`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- return @20-22; FunctionExpression; parameters=0; async=false; generator=false
- fn @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-23

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/length.js

Blob: `752956fa0c6fca81da107080b1223494a67cbf97`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/name.js

Blob: `2e0ee3257d7e282ebb663f619d49a36d65de4446`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/next-throws-iterator-not-closed.js

Blob: `b96852a0e82ef69e8bf9a9aea82bb76963a80331`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- return @20-22; FunctionExpression; parameters=0; async=false; generator=false
- fn @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-23

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/proxy.js

Blob: `ed90cec204e7fe4a135cd501b882692e5f86fa2b`. Role: imported-path,test-path,source. Parse: module.

- get @18-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- next @26-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Counter @24-34

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/return-false-if-none-match.js

Blob: `3b1e4167da8cfa649485b150f9b9f591867cc544`. Role: imported-path,test-path,source. Parse: module.

- fn @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/short-circuit-on-true.js

Blob: `a4cbed66e3dd35a885e61c64a26e939f91661405`. Role: imported-path,test-path,source. Parse: module.

- fn @16-19; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/this-not-iterator-throws.js

Blob: `170dadd949787ea8c4f12d7e139a0738426acd9f`. Role: imported-path,test-path,source. Parse: module.

- fn @14-14; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/some/value-throws-iterator-not-closed.js

Blob: `a5785f08e5165a755d4ddddf09bd244f88158af4`. Role: imported-path,test-path,source. Parse: module.

- next @16-22; FunctionExpression; parameters=0; async=false; generator=false
- get @17-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- return @25-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class TestIterator @15-28
- Class TestError @14-14

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take-drop-throw-eagerly-on-negative.js

Blob: `3d2069247004a8c63f67da1db4f3cc360a707eea`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take-drop-throw-eagerly-on-non-integer.js

Blob: `9e9b36db55f4f4d46bcca813af5663f9164ee9e5`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @18-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take/close-iterator-when-none-remaining.js

Blob: `a3b1e8a983de146b28f67676f5a008f6254cd894`. Role: imported-path,test-path,source. Parse: module.

- next @17-19; FunctionExpression; parameters=0; async=false; generator=false
- return @22-25; FunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @16-26

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take/length.js

Blob: `cc3067448f7a09a8fc4685240e4f7591b612d73f`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take/name.js

Blob: `10096e207b6db76aa0e476aa44df29e6742fe421`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/take/take-more-than-available.js

Blob: `3b035c92c7cd8b045a6262cfc6be7575dc1f08e4`. Role: imported-path,test-path,source. Parse: module.

- next @31-33; FunctionExpression; parameters=0; async=false; generator=false
- return @36-39; FunctionExpression; parameters=1; async=false; generator=false
- Class TestIterator @29-40

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/create-in-current-realm.js

Blob: `38dd7369689a80d9a527268b9b8e4b775491e635`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/descriptor.js

Blob: `05b8bab9dcb3eedbec727abb3d97f799ffbaefb3`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/iterator-empty.js

Blob: `0c26c724ee554a6049a3409512126d502f4a9750`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/length.js

Blob: `0e92655d9cf076a532facbae3459687a64cdedf7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/name.js

Blob: `41bd6afe6d8039d94b73ebd491ccf98ae5e2dca7`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/next-throws.js

Blob: `08a0b483860f4cac574f3bd015ea030510d7cfb2`. Role: imported-path,test-path,source. Parse: module.

- next @15-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @14-18

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/proxy.js

Blob: `a4dc4685a7e3f32ccb24d1c323f6e5cb464a5db8`. Role: imported-path,test-path,source. Parse: module.

- get @18-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- next @26-33; FunctionExpression; parameters=0; async=false; generator=false
- Class Counter @24-34

### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/this-not-iterator-throws.js

Blob: `0a36dcd7ea266a54d7a2fd168d1e342d83c2ef06`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/toArray.js

Blob: `cb4e9de1a08f82c67792635513378c3794fa8939`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Iterator/prototype/toArray/value-throws-iterator-not-closed.js

Blob: `4eeb1966ec7e921c5522d14f444553ac7ff712d5`. Role: imported-path,test-path,source. Parse: module.

- next @16-22; FunctionExpression; parameters=0; async=false; generator=false
- get @17-21; ArrowFunctionExpression; parameters=3; async=false; generator=false
- return @25-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class TestIterator @15-28
- Class TestError @14-14

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/cyclic-stringify-unrelated.js

Blob: `0b8a14ce721ce88d084dea8ef2322e1aefe05f3d`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @17-20; FunctionExpression; parameters=2; async=false; generator=false
- toString @25-29; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/cyclic-stringify.js

Blob: `d01c77bd4804f6103cbced435dccceb0af4a6835`. Role: imported-path,test-path,source. Parse: module.

- get @18-18; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-33; FunctionExpression; parameters=0; async=false; generator=false
- get @42-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-57; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-arguments.js

Blob: `dbb66642ce73d46877428809e757f7c6c7fdbc4e`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-crockford-01.js

Blob: `9578d978e3791b0f005e5c92434e5e23fc880103`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-mega-huge-array.js

Blob: `af53b2f948e852df2d230d5f3d94c95f75bdb53e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-number-syntax.js

Blob: `87efc763c9b176688dcb7c31c722528fd7688baa`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-octal-syntax-error.js

Blob: `6db5a0f897e27159551bef1694a62f1ac5111c3a`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-primitives.js

Blob: `fe5390beca24f20f50e8bb6d2ccd5b263ce5f08c`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-reviver-array-delete.js

Blob: `6c636ca7d66376576fb66dd090c34a54f01bc3fc`. Role: imported-path,test-path,source. Parse: module.

- revive @19-24; FunctionExpression; parameters=2; async=false; generator=false
- reviver @49-54; FunctionExpression; parameters=2; async=false; generator=false
- revive @62-67; FunctionExpression; parameters=2; async=false; generator=false
- reviver @73-78; FunctionExpression; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-reviver.js

Blob: `cdc9df6ba9442cc888684f932a95c969c421339f`. Role: imported-path,test-path,source. Parse: module.

- doubler @10-18; FunctionDeclaration; parameters=2; async=false; generator=false
- dontCallMe @33-36; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @38-40; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-syntax-errors-01.js

Blob: `06dfc49c60cdec5a952eb10de480d74477ea90e2`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-syntax-errors-02.js

Blob: `6ab40121ce9d2a374e7ded5f6413ae8f11ffe6af`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-syntax-errors-03.js

Blob: `0a96b5c4882f3b5d002157d974d054e690696536`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse-with-source.js

Blob: `32869059dd0ce183a7b12fde663165f15c068f24`. Role: imported-path,test-path,source. Parse: module.

- checkJSONParseWithSource @12-91; FunctionExpression; parameters=0; async=false; generator=false
- reviver @15-22; FunctionDeclaration; parameters=3; async=false; generator=false
- replace_c_with_same_val @81-89; FunctionDeclaration; parameters=3; async=false; generator=false
- checkRawJSON @93-106; FunctionExpression; parameters=0; async=false; generator=false
- assertIsRawJson @94-101; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @104-104; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkIsRawJSON @108-113; FunctionExpression; parameters=0; async=false; generator=false
- checkUseAsPrototype @115-120; FunctionExpression; parameters=0; async=false; generator=false
- assertErrorComesFromCorrectRealm @127-132; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @128-128; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-136; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @137-137; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @139-139; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @140-140; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @141-141; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @142-142; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @143-143; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/parse.js

Blob: `0b5320a29b3dec44f585b22efb1643a6653830c3`. Role: imported-path,test-path,source. Parse: module.

- assertIsObject @9-13; FunctionDeclaration; parameters=1; async=false; generator=false
- assertIsArray @15-22; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/regress-459293.js

Blob: `a5cd8b9acbb547c9d39a8a77dea2fc0ab11ffb5d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/small-codepoints.js

Blob: `2bc75a537b4ff11d1efd6b6580bd691f8bf591e1`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-boxed-primitives.js

Blob: `9bdbfc01ce7d32c39c53ad5cfaa21fae748755d1`. Role: imported-path,test-path,source. Parse: module.

- redefine @13-18; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-66; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-71; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-80; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-83; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-95; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @98-100; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-call-replacer-once.js

Blob: `64df1722c19a96085d6807a8d822965095fdd1ec`. Role: imported-path,test-path,source. Parse: module.

- replacer @14-20; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-call-toJSON-once.js

Blob: `c97d082b8b3b03f6bbc32d143a810a782fb3f52c`. Role: imported-path,test-path,source. Parse: module.

- toJSON @16-19; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @18-18; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-dropping-elements.js

Blob: `1bcd231710301c630f8fd819dabc311e542c81f5`. Role: imported-path,test-path,source. Parse: module.

- bar @12-12; FunctionExpression; parameters=0; async=false; generator=false
- bar @14-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-gap.js

Blob: `ad8c56b9b4307ed4b41770727e9b168fa48bf3b7`. Role: imported-path,test-path,source. Parse: module.

- String.prototype.toString @45-45; FunctionExpression; parameters=0; async=false; generator=false
- Number.prototype.valueOf @49-49; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-ignore-noncallable-toJSON.js

Blob: `666969678cf5d0e4461198c01675bdc9f6c98441`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-large-replacer-array.js

Blob: `3a7bdaed6759c799b344c8e189de1498d979c5d5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-missing-arguments.js

Blob: `7c44f94ab641d786785968e8b987056d023f332d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-nonarray-noncallable-replacer.js

Blob: `5772191ba510828174c1280fc6b6a1587b67df6e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-primitives.js

Blob: `7a905d02060e9f5533816010726a22bd7c961159`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-boxed-elements.js

Blob: `f878418768b947bc1f2e5dd676577e3bfd721b37`. Role: imported-path,test-path,source. Parse: module.

- Number.prototype.toString @21-21; FunctionExpression; parameters=0; async=false; generator=false
- String.prototype.toString @25-25; FunctionExpression; parameters=0; async=false; generator=false
- Number.prototype.toString @29-29; FunctionExpression; parameters=0; async=false; generator=false
- String.prototype.toString @33-33; FunctionExpression; parameters=0; async=false; generator=false
- Number.prototype.valueOf @45-45; FunctionExpression; parameters=0; async=false; generator=false
- String.prototype.valueOf @49-49; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-duplicated-element.js

Blob: `d6723cb67d1a8ceb559baba3c8b9a7dfafb8dafe`. Role: imported-path,test-path,source. Parse: module.

- two @15-18; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-edgecase-jsid-elements.js

Blob: `dd1027af6230dbaa8485646ed433716701913a7f`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-hijinks.js

Blob: `7f86ccd16e63465671ff75a6cc701db62c92adde`. Role: imported-path,test-path,source. Parse: module.

- get @16-23; FunctionExpression; parameters=0; async=false; generator=false
- get @37-41; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-skipped-element.js

Blob: `82add871aa31ebbcc1c48c8cfc6e7bd42063cb24`. Role: imported-path,test-path,source. Parse: module.

- toString @14-14; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-array-trailing-holes.js

Blob: `642a012dc333f308f910ca84bb4c9db2c01d5943`. Role: imported-path,test-path,source. Parse: module.

- nobj.toString @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer-with-array-indexes.js

Blob: `6c05ab5018c3f33c0b0a1b0aaadcea7ac36b2096`. Role: imported-path,test-path,source. Parse: module.

- replacer @17-44; FunctionDeclaration; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-replacer.js

Blob: `f37f5715ded7db29de4dbdcd3e78c7cdfa1286c9`. Role: imported-path,test-path,source. Parse: module.

- returnObjectFor1 @14-19; FunctionDeclaration; parameters=2; async=false; generator=false
- returnArrayFor1 @20-25; FunctionDeclaration; parameters=2; async=false; generator=false
- returnNullFor1 @26-31; FunctionDeclaration; parameters=2; async=false; generator=false
- returnStringForUndefined @32-37; FunctionDeclaration; parameters=2; async=false; generator=false
- returnCycleObjectFor1 @39-44; FunctionDeclaration; parameters=2; async=false; generator=false
- returnCycleArrayFor1 @46-51; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @57-57; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @61-61; FunctionExpression; parameters=2; async=false; generator=false
- censor @65-70; FunctionDeclaration; parameters=2; async=false; generator=false
- censor2 @78-83; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @108-108; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @128-130; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @132-134; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-139; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-special-escapes.js

Blob: `732dc5b87798ec88ea2473674f2196ba716928f5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify-toJSON-arguments.js

Blob: `44ab531fbe47a7f1d17bb8f33eb9b9d6ab16ad62`. Role: imported-path,test-path,source. Parse: module.

- toJSON @16-21; FunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/stringify.js

Blob: `d3add2d06f9d279a250a3ac7a0980ab6aef47b35`. Role: imported-path,test-path,source. Parse: module.

- assertStringify @10-13; FunctionDeclaration; parameters=2; async=false; generator=false
- foo @57-57; FunctionExpression; parameters=1; async=false; generator=false
- toJSON @60-60; FunctionExpression; parameters=0; async=false; generator=false
- Y @65-68; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @71-71; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @78-78; FunctionExpression; parameters=0; async=false; generator=false
- X @87-87; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/JSON/trailing-comma.js

Blob: `8ea72d5f6e25e77886deb04da7641daa2611ca15`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/NaN-as-key.js

Blob: `74da6ed474ac4422571fbf65767b225483ccbc8b`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/constructor-iterator-close.js

Blob: `5ee9ad3faeb468c4e460433048102ecc6bddf5cb`. Role: imported-path,test-path,source. Parse: module.

- test @11-64; FunctionDeclaration; parameters=2; async=false; generator=false
- getIterable @17-44; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @20-41; FunctionExpression; parameters=0; async=false; generator=false
- next @23-31; FunctionExpression; parameters=0; async=false; generator=false
- return @32-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-87; FunctionExpression; parameters=0; async=false; generator=false
- set @95-97; FunctionExpression; parameters=2; async=false; generator=false
- set @100-102; FunctionExpression; parameters=2; async=false; generator=false
- add @113-115; FunctionExpression; parameters=1; async=false; generator=false
- add @118-120; FunctionExpression; parameters=1; async=false; generator=false
- modifier @132-139; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @134-137; FunctionExpression; parameters=0; async=false; generator=false
- modifier @145-152; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @147-150; FunctionExpression; parameters=0; async=false; generator=false
- modifier @158-165; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @160-163; FunctionExpression; parameters=0; async=false; generator=false
- modifier @171-178; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @173-176; FunctionExpression; parameters=0; async=false; generator=false
- modifier @184-192; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @186-190; FunctionExpression; parameters=0; async=false; generator=false
- modifier @198-206; ArrowFunctionExpression; parameters=2; async=false; generator=false
- get @200-204; FunctionExpression; parameters=0; async=false; generator=false
- modifier @215-220; ArrowFunctionExpression; parameters=2; async=false; generator=false
- iterator.return @216-219; FunctionExpression; parameters=0; async=false; generator=false
- modifier @226-231; ArrowFunctionExpression; parameters=2; async=false; generator=false
- iterator.return @227-230; FunctionExpression; parameters=0; async=false; generator=false
- modifier @238-243; ArrowFunctionExpression; parameters=2; async=false; generator=false
- iterator.return @239-242; FunctionExpression; parameters=0; async=false; generator=false
- modifier @249-254; ArrowFunctionExpression; parameters=2; async=false; generator=false
- iterator.return @250-253; FunctionExpression; parameters=0; async=false; generator=false
- done @271-271; FunctionExpression; parameters=0; async=false; generator=false
- value @281-281; FunctionExpression; parameters=0; async=false; generator=false
- Class MyWeakSet @117-121
- Class MySet @112-116
- Class MyWeakMap @99-103
- Class MyMap @94-98

### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/constructor-iterator-primitive.js

Blob: `050a7aae9e0737cbfc4135c492c822c470c84df3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @30-32; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/forEach-selfhosted-behavior.js

Blob: `4f0247f8f309210797a6e140a9d9f19da0d13e90`. Role: imported-path,test-path,source. Parse: module.

- throwSyntaxError @15-18; FunctionDeclaration; parameters=0; async=false; generator=false
- lalala @20-20; FunctionDeclaration; parameters=0; async=false; generator=false
- Function.prototype.call @28-28; FunctionExpression; parameters=0; async=false; generator=false
- Function.prototype.call @35-35; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/getter-name.js

Blob: `8e354fc4374088e722817f9fd928078f7c4c921c`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/iterable.js

Blob: `198623f224d9e3041da7a85a5d7d76115b2fc1a6`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-13; FunctionExpression; parameters=0; async=false; generator=false
- next @14-14; FunctionExpression; parameters=0; async=false; generator=false
- value @23-27; FunctionExpression; parameters=0; async=false; generator=false
- next @26-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/iterator-thisv-error.js

Blob: `299619f9a4a97e2a42ece0fa9d80f1badf1a3852`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Map/symbols.js

Blob: `a0fe19f20e2b7b906d7cdaf171012045729b604e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/20.2.2.ToNumber.js

Blob: `69625c13e3f186f1b0378d9267982cc7a71bab03`. Role: imported-path,test-path,source. Parse: module.

- TestNumber @23-26; FunctionDeclaration; parameters=1; async=false; generator=false
- valueOf @29-32; FunctionExpression; parameters=0; async=false; generator=false
- test @36-42; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/acosh-approx.js

Blob: `8a8d99219f10f9e07cafe4388f60a586eb34dbbc`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/acosh-exact.js

Blob: `233aa31d477ca92e5d5424482677a8f66ce65bdc`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/asinh-approx.js

Blob: `04843f61355413649a70a8e0dfa28eb29db84679`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/asinh-exact.js

Blob: `779b49df61f50daaba8d4918b7553d82edbc3bb6`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/atanh-approx.js

Blob: `19795cca61cd699815fb94ed85b75e3b41e62dd6`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/atanh-exact.js

Blob: `0794af8e5a8320209f3bdcb7ca085fb7f649029d`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/cbrt-approx.js

Blob: `4585e166a4e669e085eab8ff1264d1775cf3be4e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/cbrt-exact.js

Blob: `f8f13da6fa97e697f6d2087577b278f61047f16a`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/clz32.js

Blob: `e06bdbf643c37d5848bdfa7a21c60d032e44a2f5`. Role: imported-path,test-path,source. Parse: module.

- valueOf @23-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/cosh-approx.js

Blob: `ee2466f24760e730c3b99f83120e33a6b6d1181e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/cosh-exact.js

Blob: `e1cb4535b3b6427f3dd7307ff185a113150320a5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/exp-exact.js

Blob: `90c8b71790602868dc2b7ff1d4aa33e8ff6fc026`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/expm1-approx.js

Blob: `30333fe7ad5f7151c678ea12908c648a83428c8c`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/expm1-exact.js

Blob: `be67d3e8a7c677a72a30a50c2402c275b64d6180`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/expm1-monotonicity.js

Blob: `192a971dfd3426f26c5a8fcf619ea89583b295d0`. Role: imported-path,test-path,source. Parse: module.

- test @11-14; FunctionDeclaration; parameters=3; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/f16round.js

Blob: `d86257c8c5817d8935483ac26a3316d7c8ca9ebc`. Role: imported-path,test-path,source. Parse: module.

- toFloat16 @23-94; FunctionDeclaration; parameters=1; async=false; generator=false
- roundTiesToEven @54-56; FunctionDeclaration; parameters=1; async=false; generator=false
- roundToFloat16 @65-91; FunctionDeclaration; parameters=1; async=false; generator=false
- maxValue @107-113; FunctionDeclaration; parameters=2; async=false; generator=false
- minValue @129-131; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/fround.js

Blob: `59fb7c19998d06b99cb483cc89e6be9043d8183e`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @22-29; FunctionExpression; parameters=0; async=false; generator=false
- f @24-27; FunctionDeclaration; parameters=1; async=false; generator=false
- maxValue @42-48; FunctionDeclaration; parameters=2; async=false; generator=false
- minValue @65-67; FunctionDeclaration; parameters=2; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log10-approx.js

Blob: `817c846813f88bb2eaf10d8970a5f3d9cd3bcadd`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log10-exact.js

Blob: `fe08df54e7a0a4e870575ee75279bec4337cca29`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log1p-approx.js

Blob: `6ab61e92edc814309f19b4090c51b9ad1af1a7c0`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log1p-exact.js

Blob: `c8949028ddf95f34f4f5671d46873d67e0a19c9e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log2-approx.js

Blob: `5fae833fe28132556d6a6c7c7d83a574a53d1f02`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/log2-exact.js

Blob: `92b37182ae1ec3723d55759720b5b3c330418d0e`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/sign.js

Blob: `cdd1bdcf3f94a3c1996506f05717d7f4d1abab10`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/sinh-approx.js

Blob: `ab0a07805f6d0ced256353d958458a64e77b2848`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/sinh-exact.js

Blob: `2a131aec5116d1e67a4ef4dbceaa6be2d5b47466`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/tanh-approx.js

Blob: `6c11f669037a0a12fae722ecb5d838ee20d2babf`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/tanh-exact.js

Blob: `4bd6856d1a512a6dd65297acbd3ee521b7f23003`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Math/trunc.js

Blob: `cbc06706679c6e589e2838ee795fcf19ec7ae6ef`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/0x-without-following-hexdigits.js

Blob: `d3f658b06abab6c966be04881fb8042878f36493`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-15; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/15.7.3.7-EPSILON.js

Blob: `8767d584e48bcb52e71943238d0f8425261b1ab6`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/15.7.4.2.js

Blob: `020d69c833a587b34dde517f1f1ba0bb76cecdb3`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @12-12; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; FunctionExpression; parameters=0; async=false; generator=false
- testAround @23-29; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/20.1.2.10-MIN_SAFE_INTEGER.js

Blob: `d85d98127d1327d2d994b97cefb142b5b9b755e6`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/20.1.2.6-MAX_SAFE_INTEGER.js

Blob: `3eeea6474a2e2b3e1b7179aefe0a8b4269659e91`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/20.1.3.2-toExponential.js

Blob: `d6b6a3f49f50b5c8b11f6b27ea6f9159b6e590d2`. Role: imported-path,test-path,source. Parse: module.

- valueOf @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @39-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/20.1.3.2-toPrecision.js

Blob: `0db643d20e78444749447fe1b431691cb2335d63`. Role: imported-path,test-path,source. Parse: module.

- valueOf @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @39-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/20.1.3.3-toFixed.js

Blob: `fd8eee0e9e306a2e492442b964d32ed5bacf1b47`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/conversion-invalid-precision.js

Blob: `9187351ae91cfca1a95f431aa1447ae375adf352`. Role: imported-path,test-path,source. Parse: module.

- test @13-17; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/defaultvalue.js

Blob: `e7745ec332c687a281b964b864b0ea3fb6658e98`. Role: imported-path,test-path,source. Parse: module.

- n2.valueOf @19-19; FunctionExpression; parameters=0; async=false; generator=false
- n3.toString @23-23; FunctionExpression; parameters=0; async=false; generator=false
- testEquality @26-38; FunctionDeclaration; parameters=0; async=false; generator=false
- n2.valueOf @32-32; FunctionExpression; parameters=0; async=false; generator=false
- n3.toString @36-36; FunctionExpression; parameters=0; async=false; generator=false
- n2.toString @48-48; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @52-52; FunctionExpression; parameters=0; async=false; generator=false
- testNumberAddition @55-67; FunctionDeclaration; parameters=0; async=false; generator=false
- n2.toString @61-61; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @65-65; FunctionExpression; parameters=0; async=false; generator=false
- n2.toString @77-77; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @81-81; FunctionExpression; parameters=0; async=false; generator=false
- testNonNumberAddition @84-96; FunctionDeclaration; parameters=0; async=false; generator=false
- n2.toString @90-90; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @94-94; FunctionExpression; parameters=0; async=false; generator=false
- n2.valueOf @108-108; FunctionExpression; parameters=0; async=false; generator=false
- n3.toString @112-112; FunctionExpression; parameters=0; async=false; generator=false
- testPropertyNameToNumber @115-129; FunctionDeclaration; parameters=0; async=false; generator=false
- n2.valueOf @123-123; FunctionExpression; parameters=0; async=false; generator=false
- n3.toString @127-127; FunctionExpression; parameters=0; async=false; generator=false
- n2.toString @139-139; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @143-143; FunctionExpression; parameters=0; async=false; generator=false
- testInOperatorName @146-158; FunctionDeclaration; parameters=0; async=false; generator=false
- n2.toString @152-152; FunctionExpression; parameters=0; async=false; generator=false
- n3.valueOf @156-156; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/isSafeInteger-01.js

Blob: `37f4ede01ef7119d3ee1d1c72e8aece6e8d69ba5`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/numericSeparator.js

Blob: `f67e5bb7eeddd0e88a3875261440081fd7e1062c`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @11-11; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/parseFloat-01.js

Blob: `f52789508f737c6b5d067ac22288869ace5fcbac`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/parseInt-01.js

Blob: `c0ee8b594509a2bdfa53e73c6d509fcc39cf109b`. Role: imported-path,test-path,source. Parse: module.

- toString @18-18; FunctionExpression; parameters=0; async=false; generator=false
- toString @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false
- toString @79-79; FunctionExpression; parameters=0; async=false; generator=false
- toString @81-81; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @94-94; FunctionExpression; parameters=0; async=false; generator=false
- valueOf @121-121; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/parseInt-default-to-decimal.js

Blob: `b41b678a5ce894e8e95f08e5be5385f5e7d4eef3`. Role: imported-path,test-path,source. Parse: module.

- strictParseInt @17-17; FunctionDeclaration; parameters=1; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/toExponential-values.js

Blob: `1415b96037fbaeb4b4835f10e0b0325207d2cf08`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/toFixed-values.js

Blob: `726879abb859d7ea7a571cdcd600d63bc479f20f`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/toPrecision-values.js

Blob: `e55e5eb803d4416dd65562a370b116930a216d6b`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/toString-radix-handling.js

Blob: `d8052728dc0c90a7ad5b8fd1ba2406e63dc0bd73`. Role: imported-path,test-path,source. Parse: module.

- test @13-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @14-16; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/Number/tonumber-string-hex.js

Blob: `daba403aaa50119d3ad6e3db3a4e20e75881f169`. Role: imported-path,test-path,source. Parse: module.


### testing/web-platform/tests/third_party/test262/test/staging/sm/PrivateName/constructor-args.js

Blob: `7277f2ef058fd5a52ff5811924729647a9a09112`. Role: imported-path,test-path,source. Parse: module.

- constructor @11-13; FunctionExpression; parameters=1; async=false; generator=false
- constructor @21-26; FunctionExpression; parameters=0; async=false; generator=false
- Class B @20-27
- Class A @9-14

### testing/web-platform/tests/third_party/test262/test/staging/sm/PrivateName/error-outside-class.js

Blob: `291545c212b3b5bfb219adab9ee7c5b6457f014f`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/PrivateName/home-object-when-preceded-by-computed-key.js

Blob: `bfb1ef7a5ea3413283e652a58ea4a36a5a11c4d4`. Role: imported-path,test-path,source. Parse: module.

- m @10-10; FunctionExpression; parameters=0; async=false; generator=false
- m @11-11; FunctionExpression; parameters=0; async=false; generator=false
- toString @15-17; FunctionExpression; parameters=0; async=false; generator=false
- key @21-21; FunctionExpression; parameters=0; async=false; generator=false
- m @25-25; FunctionExpression; parameters=0; async=false; generator=false
- m @26-26; FunctionExpression; parameters=0; async=false; generator=false
- key @33-33; FunctionExpression; parameters=0; async=false; generator=false
- m @35-35; FunctionExpression; parameters=0; async=false; generator=false
- m @36-36; FunctionExpression; parameters=0; async=false; generator=false
- Class (anonymous) @31-37
- Class (anonymous) @20-27
- Class Base @9-12

### testing/web-platform/tests/third_party/test262/test/staging/sm/PrivateName/illegal-in-class-context.js

Blob: `d0ada3399c8dfb817a0921efe49ce08e7a6d9bf8`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @10-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/third_party/test262/test/staging/sm/PrivateName/illegal-in-identifier-context.js

Blob: `b2113b6dbd6f5cd39585ae78d3f378a3cac2dd72`. Role: imported-path,test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [b6555af2-7c18-46de-962c-4a8630cf437b.md](b6555af2-7c18-46de-962c-4a8630cf437b.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `2d06bd97f8465c673b398f21dd97bed8fc9bc3c18881d52690ea0b69c9d95504`.
