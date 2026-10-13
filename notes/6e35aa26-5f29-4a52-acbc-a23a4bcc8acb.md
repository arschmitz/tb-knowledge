<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["80ed72f4740f36707df227b1820a99b808a832a3a3979fee7599d8c210a1e2e0"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/5d4898d5-df42-44fc-aead-3a8cf6035396.md"}} -->
# firefox/js JavaScript function map 436

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/test262/built-ins/Temporal/Duration/compare/argument-propertybag-optional-properties.js

Blob: `25226b7de501a226f09adbea60794b03e6d97c9b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/argument-string-fractional-units-rounding-mode.js

Blob: `02a04ed5b4b7f73e8d63242dbc8bc8b9296054a7`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/argument-string-negative-fractional-units.js

Blob: `9e0e32ea5bc3273cd5b5c71098acd842007dd2cf`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/basic.js

Blob: `ba9e5fb80b2bdf1d1fe7744bd210ca1b572c6a18`. Role: test-path,source. Parse: module.

- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/blank-duration.js

Blob: `255e877e9ee87974990de7189715a9e5dd7cacac`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/builtin.js

Blob: `bc3ae30fef327fab8575a7b1408401621c3a97ac`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/calendar-possibly-required.js

Blob: `dd4082ef02e8effa59765413c5a05399d8c01feb`. Role: test-path,source. Parse: module.

- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/calendar-temporal-object.js

Blob: `e2d4441a741280d0c4b7c376dd0286e47e8ac8ad`. Role: test-path,source. Parse: module.

- (anonymous) @24-28; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/compare-no-precision-loss.js

Blob: `5676436903e05193cdefa1bc8cecdcd4b6cd147b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/duration-out-of-range-added-to-relativeto.js

Blob: `cb8c1157d71217b5a51eb5275106b100b2a07f48`. Role: test-path,source. Parse: module.

- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/exhaustive.js

Blob: `a38fa79320b5457b0e6bc205b886dfa79b6d0d0b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/instances-identical.js

Blob: `f23233dc8e35bd8b2843a4dfc776c554e6fb5794`. Role: test-path,source. Parse: module.

- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/length.js

Blob: `9a8e1d5697c7850dfffc9152ea8648b6fc2c3369`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/name.js

Blob: `240758f60e43eea899625259f230ff80bb49f535`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/not-a-constructor.js

Blob: `2c4dadec9384569f846542695c569d20c8089fc5`. Role: test-path,source. Parse: module.

- (anonymous) @16-18; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/options-object.js

Blob: `b2a08779e8b3a20bb37bf747bf2369e669ad3d2c`. Role: test-path,source. Parse: module.

- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/options-read-before-algorithmic-validation.js

Blob: `704cbc93c8624bb680c9cabdd1287a7972050953`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/options-undefined.js

Blob: `214a16df845043b6d33b51b721615afe1e72c35b`. Role: test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/options-wrong-type.js

Blob: `3e6e89cf451e1f1a8d3537ee6004d6a4bb631a78`. Role: test-path,source. Parse: module.

- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/order-of-operations.js

Blob: `57356728027fe39592fb78f3cac6ef9a0397c935`. Role: test-path,source. Parse: module.

- (anonymous) @91-95; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkTemporalObject @101-108; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @102-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- get @104-106; FunctionExpression; parameters=0; async=false; generator=false
- createOptionsObserver @170-172; FunctionDeclaration; parameters=1; async=false; generator=false
- createDurationPropertyBagObserver @174-187; FunctionDeclaration; parameters=11; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/prop-desc.js

Blob: `1a290efaff3f429530cf6abaec829228f1594926`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-argument-propertybag-calendar-invalid-iso-string.js

Blob: `3f9a488ae207bf4e75d582833f166ab88bc7fe72`. Role: test-path,source. Parse: module.

- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-argument-string-calendar-invalid-iso-string.js

Blob: `39ad432301ad12b2c8823d52ed5a14325dab1c5c`. Role: test-path,source. Parse: module.

- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-hour.js

Blob: `09ff7218c8cf2ea340cdc4f226f109144e7952b0`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-month.js

Blob: `c8b1e036cd2c8a10d3af202abd20380ff9b13d0b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-no-fractional-minutes-hours.js

Blob: `55f54e31420678131853d64500905c8b1431111d`. Role: test-path,source. Parse: module.

- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-plaindate-add24hourdaystonormalizedtimeduration-out-of-range.js

Blob: `9a7a0d6ef4ad00fa054d0962b6a14d08a5917c06`. Role: test-path,source. Parse: module.

- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-infinity-throws-rangeerror.js

Blob: `e5d0dc51abd79f2c6a518bac54ff06d807af0a92`. Role: test-path,source. Parse: module.

- (anonymous) @16-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-invalid-offset-string.js

Blob: `317d79a22e1bd457361a55edfd1c36ea118c4748`. Role: test-path,source. Parse: module.

- (anonymous) @24-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-invalid.js

Blob: `1432fa1d8f9179df86d28bf74b569a04ee148217`. Role: test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-optional-properties.js

Blob: `7a97f806d281340aa87d422663e3f23cfa89287f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-timezone-string-datetime.js

Blob: `cf3959a556098cff28a84579168b3e4741ff874e`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @60-62; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-timezone-string-leap-second.js

Blob: `5afbc2c7458c9758d8fa317aaeeee40b901b31a3`. Role: test-path,source. Parse: module.

- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-timezone-string-year-zero.js

Blob: `57d48a7c3ac7fc5ce85a8ed2933aef961e494da1`. Role: test-path,source. Parse: module.

- (anonymous) @15-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-timezone-string.js

Blob: `627f98c349bd7259c8a8772c37fd5f1ee47e5e59`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-propertybag-timezone-wrong-type.js

Blob: `514e8b8a328d5177083e3029332be32ea5af78a2`. Role: test-path,source. Parse: module.

- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-string-invalid.js

Blob: `679db9e9d6c8308da93684b0d1ab08111b085705`. Role: test-path,source. Parse: module.

- (anonymous) @21-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-string-limits.js

Blob: `8b85e7c52c9bd8ad40f90bffe5a3719c84fa5ba9`. Role: test-path,source. Parse: module.

- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-string-wrong-offset.js

Blob: `2693b1adf065f614528c06d38d8908670c293aec`. Role: test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-string.js

Blob: `08a25217496307a31ca21e21796dd054751a09fe`. Role: test-path,source. Parse: module.

- (anonymous) @26-29; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-sub-minute-offset.js

Blob: `f49c6d72b5d32b61cffe1db600c9baa091d74947`. Role: test-path,source. Parse: module.

- action @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-undefined-throw-on-calendar-units.js

Blob: `6072bd795e120b259c9b0eeea5fd880a9bd16a05`. Role: test-path,source. Parse: module.

- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-year.js

Blob: `8bb23e2da66ca83d4cb51545d13700bdeccc666b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/relativeto-zoneddatetime-negative-epochnanoseconds.js

Blob: `7aa811c9eb37aac2a12631ce5bdf4924b16a1fa4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/compare/shell.js

Blob: `eda1477282520548ae28183583fd14cd1502d6cd`. Role: test-path,source. Parse: module.

- isConstructor @13-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/throws-when-target-zoned-date-time-outside-valid-limits.js

Blob: `6f7b3ffb13ae4446428bc7697641f824e7ec3d55`. Role: test-path,source. Parse: module.

- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/compare/year-zero.js

Blob: `4adbc80ddbbc9c9274758c9128621c04c5ecf7d1`. Role: test-path,source. Parse: module.

- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/constructor.js

Blob: `9d2e7e676c6ddf30f70d0b138af851fc1af80dfb`. Role: test-path,source. Parse: module.

- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/days-undefined.js

Blob: `8e79041131bc157e066fa133fac538859dc7a092`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/fractional-throws-rangeerror.js

Blob: `b13c7ead70e7dabc21fd7c25c6f6ded539a6ee2f`. Role: test-path,source. Parse: module.

- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-duration-max.js

Blob: `af9f721949b0f6515f693c9e14fa44571e32519a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-duration-out-of-range.js

Blob: `77fbdc9f7a14192e498ffc63d0b77339be4d0e91`. Role: test-path,source. Parse: module.

- (anonymous) @56-56; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-duration-precision-exact-numerical-values.js

Blob: `2bece633b826c8a7109685a67946f2d388241f52`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-duration.js

Blob: `59eaffb2235aeff477e2047cb31ff956f6fbbc91`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-existing-object.js

Blob: `6f44cd0c03dea1a869766c3c044e0bfa9d0e18f1`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-non-string.js

Blob: `e9b87fd135cfdf4a7e05cb169643053127a45bb6`. Role: test-path,source. Parse: module.

- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-object-invalid.js

Blob: `bc378f03687ffd685f5db56c44b103b5c9dd24e6`. Role: test-path,source. Parse: module.

- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-propertybag-optional-properties.js

Blob: `0ebd0dc95e0faca3fdb946093af7d36a60833842`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-propertybag.js

Blob: `80a750270fe47d2c37c1dfecc96468288f564661`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-fractional-precision.js

Blob: `459fd26c37f23fbf6aa9c7b895710eae1c2359b8`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-fractional-units-rounding-mode.js

Blob: `bcbdb292fca748403e0e6e379ce5b461db8968e5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-fractional-with-zero-subparts.js

Blob: `292dc1b7126c5129ce78b97d92839f22b23d4cb8`. Role: test-path,source. Parse: module.

- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-invalid.js

Blob: `f86c5dad617235ce300b2b628e6d59a497745275`. Role: test-path,source. Parse: module.

- (anonymous) @55-55; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-is-infinity.js

Blob: `25ab94955568b877f665531e5a5b4ca7f9969884`. Role: test-path,source. Parse: module.

- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string-negative-fractional-units.js

Blob: `3caf5fc2eb42f7ab6126aef6808a68d991e8ed10`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/argument-string.js

Blob: `cc838187477013e73df4023cf57575ca135ff303`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/blank-duration.js

Blob: `340265b17091872ab1ebcb5ab5a5e12421d3b1d5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/builtin.js

Blob: `5a67e03f52e4a7aad45ed668276ffd3ee31fb31d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/get-property-throws.js

Blob: `f9b6206228b0dafbd2f0675fb3d7a120572fb90d`. Role: test-path,source. Parse: module.

- name @64-66; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @70-70; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/infinity-throws-rangeerror.js

Blob: `465f40b9c7f21b9f56ac256f4dea9b30d9880740`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @19-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/invalid-type.js

Blob: `27b400d37c2b8709167c2f0fb35aaff18cdb1579`. Role: test-path,source. Parse: module.

- (anonymous) @67-67; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/length.js

Blob: `c01e3aa8a5166c886be1b3f7b8e16931b5241ae5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/lower-limit.js

Blob: `93d5461931a7df162a351fbc9bb313c59b5460b4`. Role: test-path,source. Parse: module.

- (anonymous) @25-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-37; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/name.js

Blob: `eb84fdc56813aefc8c4f4e55c848e4caba40d99e`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/negative-inifinity-throws-rangeerror.js

Blob: `dec4380531c443371a28d417ed0c9bbefcb65672`. Role: test-path,source. Parse: module.

- (anonymous) @13-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @19-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/non-integer-throws-rangeerror.js

Blob: `1cf31580ff2922ebbfda37a24091eebfaf79eeb2`. Role: test-path,source. Parse: module.

- (anonymous) @23-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/not-a-constructor.js

Blob: `e9c2a5d6550cfc6f7731efb3212f50b87af2249c`. Role: test-path,source. Parse: module.

- (anonymous) @16-18; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/order-of-operations.js

Blob: `a17d63c60f3a5ad30b80bbf6e7c91a1f887bedc3`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/prop-desc.js

Blob: `f3e34fb55770d0b0bf7533cd7222b89bda75be96`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/shell.js

Blob: `eda1477282520548ae28183583fd14cd1502d6cd`. Role: test-path,source. Parse: module.

- isConstructor @13-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/from/string-with-skipped-units.js

Blob: `b6e79b60ebb09b9c23457091a896a5ea07fb11a7`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/from/subclassing-ignored.js

Blob: `a6802d3938aaf2be6b4fa825657edccba2f1be3a`. Role: test-path,source. Parse: module.

- (anonymous) @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/get-prototype-from-constructor-throws.js

Blob: `630c316aac64216ce4452800b64736e07df81b32`. Role: test-path,source. Parse: module.

- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false
- get @35-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-42; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/hours-undefined.js

Blob: `820c75d622258559a11037fd70d9f33e7ae8d672`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/infinity-throws-rangeerror.js

Blob: `0df75944418f4db9d796a47fdda6c0824e783e35`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- O @23-23; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @80-80; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/invalid-type.js

Blob: `3dabb62997e053c2eb46c08ce4f68de0636aff0b`. Role: test-path,source. Parse: module.

- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/large-number.js

Blob: `70007ecde133b830e902419580c3af05893da6a1`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/length.js

Blob: `0e0748acd0d74909d4053fb4b96140ef8196313b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/lower-limit.js

Blob: `55b6406ef898a384f7539e6d7c525520529fd1f5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/max.js

Blob: `8cc866fa6909d2b22fc72bfb67356373cbbdc2b4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/microseconds-undefined.js

Blob: `42ff2a962aba9a34dfca6a7e4d22bdb9e2d3acdd`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/milliseconds-undefined.js

Blob: `cddc1ee8735d473bc878cebe96fc8d5a33bfdd06`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/minutes-undefined.js

Blob: `993f76b296eac2255958bfd039835986973bdb03`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/mixed.js

Blob: `ae7f0c4069cf3c91922bb4a96e8f61d6bec86759`. Role: test-path,source. Parse: module.

- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/months-undefined.js

Blob: `526c523f59c3e7a623684fa8a32310f8c1935fc8`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/name.js

Blob: `b35da70bdecfdc62cb594fbb1114d5e48be5cf49`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/nanoseconds-undefined.js

Blob: `3d186ed64628cf2cc826550e0f1cb35ca87c464d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/negative-infinity-throws-rangeerror.js

Blob: `cb25820ff4d80f0badf409533812931ace01ed46`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- O @23-23; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @80-80; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/out-of-range.js

Blob: `5eab2620663be8e330517e988fdecc7b92130573`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prop-desc.js

Blob: `e6d24f4b51bc23c5969f14218db94243003796e4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/basic.js

Blob: `275b8d369614372d129941f2ccfc9c9803256447`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/branding.js

Blob: `2e341fd15b79332bc72a90cd2d19f800dd645d1f`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/builtin.js

Blob: `e699e3e0e6d52775d6d3cc8c17402582f2f6ace5`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/length.js

Blob: `6349fa1b8c862326e3d88874278ac281edf9211b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/name.js

Blob: `fe8fd6fe2be59596200f6fe6db7387c28930da7d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/new-object.js

Blob: `3210711449fcec397805c09d7e8332a929b5b033`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/not-a-constructor.js

Blob: `338939d33e7b577ee90074bfcc919c1a7ecfcd76`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/prop-desc.js

Blob: `49ed01dd2b13b047b6a0f72a4f52f319f73a14f3`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/shell.js

Blob: `eda1477282520548ae28183583fd14cd1502d6cd`. Role: test-path,source. Parse: module.

- isConstructor @13-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/abs/subclassing-ignored.js

Blob: `b29ed069909ab7017fbdac15a7ba41d75759a60c`. Role: test-path,source. Parse: module.

- (anonymous) @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-duration-max.js

Blob: `2e3d009987cc8c16bc805c9f912c070ee8abb75a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-duration-out-of-range.js

Blob: `a0b30ac61abdad2a304e622dc2018ec7127c108f`. Role: test-path,source. Parse: module.

- (anonymous) @58-58; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-duration-precision-exact-numerical-values.js

Blob: `3810427fee042539d0c7d6b6e6b66c1832f6e574`. Role: test-path,source. Parse: module.

- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-invalid-property.js

Blob: `77b16745d2e198771477cc007bf1f847e000a3b7`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-mixed-sign.js

Blob: `26e6a13da335d488c9872e603a69f51b75501ec0`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-not-object.js

Blob: `a4c30e70ad61770bf360f7a422c2f65cc8cdae2e`. Role: test-path,source. Parse: module.

- (anonymous) @12-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-propertybag-optional-properties.js

Blob: `21cb0d93b590fddc32fb2d4f2907285e4bddf39f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-singular-properties.js

Blob: `78ac4c2a0cf5277d815d4c33603f911c62ddab86`. Role: test-path,source. Parse: module.

- (anonymous) @24-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-string-fractional-units-rounding-mode.js

Blob: `f7456fea973e6bbd9ffcec9f47b545b85d6043de`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-string-negative-fractional-units.js

Blob: `4dbd149c5eea3ccf3b4d022418394ecec4b213c7`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/argument-string.js

Blob: `cb043be3bae4509e45cf6fb4b1fbfbb8a85f7b39`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/balance-negative-result.js

Blob: `cf1b8ad807469c97f327945a2f61e8812522ac04`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/balance-negative-time-units.js

Blob: `993a4eabc7a14c1069375a1298e61dcac4a2bd1a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/basic.js

Blob: `220437bd6f3dfa39365e51b357f9d520d3fab79e`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/blank-duration.js

Blob: `09127ea8ab2006844e29c6ff73d50f8c1c440039`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/branding.js

Blob: `8171aaa3dc898541ddc7dfc79d1ee61fe2938b13`. Role: test-path,source. Parse: module.

- (anonymous) @17-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/builtin.js

Blob: `531305ea8945415cd485ec429c7936b15fa1d0fa`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/float64-representable-integer.js

Blob: `7dcf2464d2a649a9306939326419f6f0b8a2e480`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/infinity-throws-rangeerror.js

Blob: `5d46ca6ab7992b325ce7acb372a1489f886c907e`. Role: test-path,source. Parse: module.

- (anonymous) @15-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @21-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/length.js

Blob: `c8162fbb3ee439d82e7d02f3cc10a75cdc615967`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/name.js

Blob: `79e706d0f32e7fa659b52d671484efabdcbcee4f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/nanoseconds-is-number-max-safe-integer.js

Blob: `4185f23a83dc136ea1071cc82d494f75ee35348a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/negative-infinity-throws-rangeerror.js

Blob: `8839634de08c6f6683339d560499b08402edf21b`. Role: test-path,source. Parse: module.

- (anonymous) @15-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueOf @21-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/no-calendar-units.js

Blob: `b49c6087baf179627e28105c854362bfae298da6`. Role: test-path,source. Parse: module.

- (anonymous) @16-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/non-integer-throws-rangeerror.js

Blob: `58f40bec3981567dded6ebe69b9e5513d2bc9f21`. Role: test-path,source. Parse: module.

- (anonymous) @24-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/not-a-constructor.js

Blob: `cfdd60c053bad2d49d0c34232001da6ba6cfbc41`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/order-of-operations.js

Blob: `16453802febaf0e528bad3afc0a8c6f1c5a56c79`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/precision-exact-mathematical-values.js

Blob: `95eaf3a6182a9562b1e2c60eb5bc335d0fb84f1e`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/precision-no-floating-point-loss.js

Blob: `3bdeb8b9b32482ec8fd373a990369ae305affd76`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/prop-desc.js

Blob: `d03c1b03166368e5ee7f0302419daa94ea766f93`. Role: test-path,source. Parse: module.


### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/result-out-of-range-1.js

Blob: `8aa11e93eb6f295573dec874996b4b11da3cd1fe`. Role: test-path,source. Parse: module.

- (anonymous) @29-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/result-out-of-range-2.js

Blob: `016cf10b573f14f51c98b1f8bfa913adc7860663`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/result-out-of-range-3.js

Blob: `58de83d97eade9cecd1c1119f4c1855cc1a4e6e0`. Role: test-path,source. Parse: module.

- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/shell.js

Blob: `eda1477282520548ae28183583fd14cd1502d6cd`. Role: test-path,source. Parse: module.

- isConstructor @13-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/add/subclassing-ignored.js

Blob: `59afb2df5f6724ec44926b86230aaf10d6a7a1fb`. Role: test-path,source. Parse: module.

- (anonymous) @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/test262/built-ins/Temporal/Duration/prototype/blank/basic.js

Blob: `612f899bebb8d077e060f7af34616cd4040d40a8`. Role: test-path,source. Parse: module.


## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [5d4898d5-df42-44fc-aead-3a8cf6035396.md](5d4898d5-df42-44fc-aead-3a8cf6035396.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `80ed72f4740f36707df227b1820a99b808a832a3a3979fee7599d8c210a1e2e0`.
