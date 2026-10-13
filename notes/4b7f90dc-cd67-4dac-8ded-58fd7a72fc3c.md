<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["0c163e31aaffe4960055fde6d6674926404c416033136ad020f5c595ef06bce0"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/d055617a-c542-4feb-9394-e5fb87fa0eb7.md"}} -->
# firefox/js JavaScript function map 308

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/non262/regress/regress-420919.js

Blob: `124172377fdbd3964e82c760857d044ca45e4bb0`. Role: test-path,source. Parse: module.

- test @16-32; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-422348.js

Blob: `8cb159f193d9f61f1cfd02ccb0e0e6ed4830aa2d`. Role: test-path,source. Parse: module.

- test @17-34; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-424311.js

Blob: `4744f9ab8a8d42245706e129363f395112a508ff`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-425360.js

Blob: `398c3fbbbad024353321b82cc8b8b3cd26ecabde`. Role: test-path,source. Parse: module.

- finishtest @12-17; FunctionDeclaration; parameters=0; async=false; generator=false
- throwBlah @19-22; FunctionDeclaration; parameters=0; async=false; generator=false
- window.onload @30-30; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-426827.js

Blob: `09c1bdea83e067030a86dd74fb84b176969617de`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-427798.js

Blob: `00e4f0c25a623bb337672e778b685e8a98d7f164`. Role: test-path,source. Parse: module.

- test @16-54; FunctionDeclaration; parameters=0; async=false; generator=false
- f @21-42; FunctionDeclaration; parameters=1; async=false; generator=false
- f @27-27; FunctionExpression; parameters=0; async=false; generator=false
- f @35-35; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-433279-01.js

Blob: `3d7798b88cca46633b815931a81a164616ef8781`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-433279-02.js

Blob: `b1b1f06e842d9f404d27ab332f19b682eefd84d8`. Role: test-path,source. Parse: module.

- test @15-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-433279-03.js

Blob: `78a71b4d763cc3cca1a46ee2cb771246d923b1f9`. Role: test-path,source. Parse: module.

- test @15-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-438415-01.js

Blob: `d3bba8240f4f65ab46abc5d530c12e08d9caf48c`. Role: test-path,source. Parse: module.

- test @15-23; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-438415-02.js

Blob: `f31db49aec42e811ed807d7e220e642e3294c1be`. Role: test-path,source. Parse: module.

- test @15-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-440926.js

Blob: `17ede9069df1ffd6d82b86017d4bc4a7df4f720d`. Role: test-path,source. Parse: module.

- test @15-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-442333-01.js

Blob: `c1a45dcd61002b32408bf93a6f700ba62be8fa71`. Role: test-path,source. Parse: module.

- test @16-33; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-450369.js

Blob: `46b357c04d805c1c70fa5867f69cbb5531bd1f04`. Role: test-path,source. Parse: module.

- (anonymous) @84-273; FunctionExpression; parameters=0; async=false; generator=false
- f @86-88; FunctionDeclaration; parameters=1; async=false; generator=false
- Date.prototype.toJSON @90-100; FunctionExpression; parameters=0; async=false; generator=false
- stringify @113-214; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @129-137; FunctionExpression; parameters=1; async=false; generator=false
- parse @218-271; FunctionExpression; parameters=2; async=false; generator=false
- walk @221-234; FunctionDeclaration; parameters=2; async=false; generator=false
- test @282-305; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-450833.js

Blob: `9b82649b2ce8f02162cb2ce04ed82e1eeddf9eff`. Role: test-path,source. Parse: module.

- test @16-41; FunctionDeclaration; parameters=0; async=false; generator=false
- f @24-29; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-451322.js

Blob: `b2c03a58cac248b7da0a221b38e83e3bcfd9440d`. Role: test-path,source. Parse: module.

- test @17-33; FunctionDeclaration; parameters=0; async=false; generator=false
- f @23-28; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-451884.js

Blob: `f10e84580a0d7959614dc194a1cf481be857f19e`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-451946.js

Blob: `b70b80d5959c94488f797d2a6978073bcbcd6f51`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452008.js

Blob: `83e29a8c7bc137c5ba38c23cd03c68e886e6f661`. Role: test-path,source. Parse: module.

- test @16-147; FunctionDeclaration; parameters=0; async=false; generator=false
- copy_ @44-51; FunctionDeclaration; parameters=2; async=false; generator=false
- copyInt_ @54-60; FunctionDeclaration; parameters=2; async=false; generator=false
- greater @63-81; FunctionDeclaration; parameters=2; async=false; generator=false
- mont_ @94-131; FunctionDeclaration; parameters=4; async=false; generator=false

### js/src/tests/non262/regress/regress-452170.js

Blob: `4c4d582daa2e57ca01828d6bf4e6c2d5d0d66909`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452333.js

Blob: `0b2b3f655a7a12db45ecabebd753cd8066b5cedf`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452336.js

Blob: `100f5d59785d8772eb9e000e1e5db555b38bc2b5`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452346.js

Blob: `0ac4d4db26661db13d5d80272b119a69253b6288`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452491.js

Blob: `57f2e8eb490f43bf10fe29ed820c85ccbea89b77`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452495.js

Blob: `c21f805ecd9679a247851e2c6ca4e5795024724d`. Role: test-path,source. Parse: module.


### js/src/tests/non262/regress/regress-452498-006.js

Blob: `1e0c851961d6974ff82556ef7ca3a7428f3d9339`. Role: test-path,source. Parse: module.

- test @16-41; FunctionDeclaration; parameters=0; async=false; generator=false
- foo @23-28; FunctionDeclaration; parameters=0; async=false; generator=false
- f @25-25; FunctionExpression; parameters=0; async=false; generator=false
- g @26-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-027.js

Blob: `6b160d011fd5c7e55f64cff966a6b80aadad22ce`. Role: test-path,source. Parse: module.

- test @16-31; FunctionDeclaration; parameters=0; async=false; generator=false
- f @25-25; FunctionDeclaration; parameters=1; async=false; generator=false
- g @25-25; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-030.js

Blob: `76ea0fa259bf591e3c9a3179c0f7f77bd227dd21`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false
- f @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-040.js

Blob: `1ae132c059261fac61793c59d7df03a582b36c39`. Role: test-path,source. Parse: module.

- test @16-33; FunctionDeclaration; parameters=0; async=false; generator=false
- m @23-28; FunctionDeclaration; parameters=0; async=false; generator=false
- a @25-25; FunctionDeclaration; parameters=0; async=false; generator=false
- b @26-26; FunctionDeclaration; parameters=0; async=false; generator=false
- ?.c @27-27; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-050.js

Blob: `637cc069e409c0d525485877f4a239a389701906`. Role: test-path,source. Parse: module.

- test @16-39; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-052-a.js

Blob: `d91db2d5e4b15edf0d43d6ae7593069af082f934`. Role: test-path,source. Parse: module.

- test @19-38; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-058.js

Blob: `87cdc18faa548e2307a45771220a7edccfac11a4`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false
- foo @23-23; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-062.js

Blob: `0b61201b6bf3029b0953c57839c78a9c4791a2bc`. Role: test-path,source. Parse: module.

- test @16-40; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-063.js

Blob: `707e131ce6ff579f08987068bd2ae97f2097649d`. Role: test-path,source. Parse: module.

- test @16-31; FunctionDeclaration; parameters=0; async=false; generator=false
- f @23-28; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-071.js

Blob: `c09e5f5e1e0fe0adba1ba02ab0f76994f8c090ac`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-072.js

Blob: `b9b1b3aad25fa12664371fff4fcebef1c4bbcb3f`. Role: test-path,source. Parse: script.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false
- p @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-073.js

Blob: `239608ffd5c06871ff346b3af5329b39179dabcb`. Role: test-path,source. Parse: module.

- test @16-34; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-074.js

Blob: `6d23960000ba86c9655c014ce09ddef82a51b7d8`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-075.js

Blob: `11edf7539778775e58c74d2c23b7324ad1758853`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false
- p @23-23; FunctionExpression; parameters=0; async=false; generator=false
- p @24-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-076.js

Blob: `4ed8ddf288e6170c5dd517a4980eb232143c91e3`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-082.js

Blob: `4c770f803261b2b1ac3944368ce4955d30178942`. Role: test-path,source. Parse: module.

- test @16-76; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- x @25-25; FunctionDeclaration; parameters=0; async=false; generator=false
- g @34-38; FunctionDeclaration; parameters=1; async=false; generator=false
- foo @57-61; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-092.js

Blob: `d4cd5fc17220fc12ee68c516d47cd8f950250f5b`. Role: test-path,source. Parse: module.

- test @16-36; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-102.js

Blob: `5e9e77dfb1ac046d9fe63af8361fda6689c8f4ba`. Role: test-path,source. Parse: script.

- test @16-62; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- x @25-25; FunctionDeclaration; parameters=0; async=false; generator=false
- x @25-25; FunctionDeclaration; parameters=0; async=false; generator=false
- f @30-36; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @31-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; FunctionExpression; parameters=0; async=false; generator=false
- f @45-48; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-104.js

Blob: `979dcd831b38f7011beb80f66e4473e481a6f8f0`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=1; async=false; generator=false
- a @23-23; FunctionDeclaration; parameters=0; async=false; generator=false
- b @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-111.js

Blob: `81bea8439ee022e6ebeb8757fbcfb92a92af7bff`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-112.js

Blob: `e2ab346cffcc80192e248eb470cfbf316aa414fe`. Role: test-path,source. Parse: module.

- test @16-35; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-114-a.js

Blob: `1ce081abbd78d379b100c0834862289e37a98278`. Role: test-path,source. Parse: module.

- test @16-39; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-114.js

Blob: `c61205781b19ef0fdd590645fbd01771ad07b85a`. Role: test-path,source. Parse: module.

- test @16-46; FunctionDeclaration; parameters=0; async=false; generator=false
- y @23-23; FunctionExpression; parameters=0; async=false; generator=false
- y @30-30; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-116.js

Blob: `f0663c0fab640f546109b1f301ed663f526c11b4`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-117.js

Blob: `d50ca31458824a36db0a9ac5cfba015c8d04c8da`. Role: test-path,source. Parse: script.

- test @16-77; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @37-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-56; FunctionExpression; parameters=0; async=false; generator=false
- x @56-56; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-118.js

Blob: `02bdf4d67c2551f7ee8abeeed955b18c5a203095`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-121.js

Blob: `d5489bf52c42419658827134cd563f2b5bfe0a90`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false
- x @24-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-123.js

Blob: `e04e7cb608e818a4b8fe55f6362c4829a73f993b`. Role: test-path,source. Parse: module.

- test @16-55; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @36-36; FunctionExpression; parameters=0; async=false; generator=false
- x @36-36; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-48; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-129.js

Blob: `6fdbe792ebcc2d0357bc09c1df14cb3a291b6889`. Role: test-path,source. Parse: module.

- test @16-46; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @36-36; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-131.js

Blob: `88a18a8e0c117703cfa93929062f7972eaf52a4d`. Role: test-path,source. Parse: module.

- test @16-45; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-135.js

Blob: `c77ed0856aa088a3ac2840f9f976aeb2e6906ce7`. Role: test-path,source. Parse: script.

- test @16-42; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @29-29; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-155.js

Blob: `6d1804e54967f7f0b3085dcd25bfc23ac2f71074`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-160.js

Blob: `da8a30b2d0ca70da205bf3a3f779658da1b33e7d`. Role: test-path,source. Parse: module.

- test @17-25; FunctionDeclaration; parameters=0; async=false; generator=false
- w @23-23; FunctionExpression; parameters=1; async=false; generator=false
- y @23-23; FunctionExpression; parameters=1; async=false; generator=false
- z @23-23; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-168-1.js

Blob: `891f39620bedf90bf5ad9bdeebfde829aea65dad`. Role: test-path,source. Parse: module.

- test @17-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-176.js

Blob: `72eb74741820938f149d6b3c0a5425d9600c56a5`. Role: test-path,source. Parse: module.

- test @17-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-181.js

Blob: `435096c116a2ee4eff106d8c2396e5d3d95d28c5`. Role: test-path,source. Parse: script.

- test @17-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-185.js

Blob: `c64175cdd808fb23941e332c8c8a66b08ae88c10`. Role: test-path,source. Parse: module.

- test @17-33; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-187.js

Blob: `abeac7e761c997c3b376d5f2c545dfd99e73b6bc`. Role: test-path,source. Parse: module.

- test @17-32; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-191.js

Blob: `8828819c56b6e64a0668118c08eb5ba501c6ef17`. Role: test-path,source. Parse: module.

- test @17-43; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452498-192.js

Blob: `e94481f95b1c8a85a94640a4331c78f3b98ff035`. Role: test-path,source. Parse: script.

- test @17-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452573-01.js

Blob: `69010aea806eb962e2edb36627b0564803329bc3`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452573-02.js

Blob: `6b06fac48a0ef68c9ddf22d569b6452bc2fd3ec9`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452703.js

Blob: `d3137e01b356310fd9cf8e30398809046d6597ed`. Role: test-path,source. Parse: module.

- (anonymous) @15-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452713.js

Blob: `1979a232ba60c5f08503cd459f394ecb91ebf864`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452724-01.js

Blob: `5e0d5d6186bca7a17b03b609380dbb8bee8f2dc2`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452724-02.js

Blob: `2c6f5a561c83bf1ef401c0c019dec3a48d7932ef`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452742-01.js

Blob: `e2d02499f970ca723c3887d3a4462f647285f93e`. Role: test-path,source. Parse: script.

- test @16-47; FunctionDeclaration; parameters=0; async=false; generator=false
- a @25-36; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-452742-02.js

Blob: `6efacb4d21edc401158a0cb12bcf6ce885b51ec9`. Role: test-path,source. Parse: script.

- test @16-52; FunctionDeclaration; parameters=0; async=false; generator=false
- a @25-28; FunctionDeclaration; parameters=0; async=false; generator=false
- b @30-35; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452853.js

Blob: `505e161e72a7146e9f185204b594a029cc6b5067`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452884-01.js

Blob: `3b9b676f8321136de152db9416915fba90340d66`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452884-02.js

Blob: `82ad11ae45a4c863d8d9057f74f3f4dc0ceab239`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-452960.js

Blob: `02b9195a832b88848a7b7e1c0cfcf3b58c0ad646`. Role: test-path,source. Parse: module.

- test @15-27; FunctionDeclaration; parameters=0; async=false; generator=false
- f @21-21; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453024.js

Blob: `e33014ea23552e3ee864ee48960c09b84db116dc`. Role: test-path,source. Parse: module.

- test @15-32; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453049.js

Blob: `5d7d8c3d573d58e07e6c8710f4c496abce6c0c33`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453051.js

Blob: `32baf824f5c9ea30fd36f67d7c9df079dba4bd67`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453173.js

Blob: `61237c9975bce24cd9504e3bd1158f5202dac886`. Role: test-path,source. Parse: module.

- test @15-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453397.js

Blob: `02b92830637d703fa70b85e1475b8ec30c432059`. Role: test-path,source. Parse: module.

- test @16-42; FunctionDeclaration; parameters=0; async=false; generator=false
- computeEscapeSpeed @22-27; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-453701.js

Blob: `56082bdcb71c599c3c8457e8567a21131c99ccd5`. Role: test-path,source. Parse: module.

- test @15-25; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-453747.js

Blob: `f67bebbc84f59b64ea1e5f39d57bbaf444509e83`. Role: test-path,source. Parse: module.

- test @15-33; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @21-29; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-454682.js

Blob: `7b99df7db2f2badf5be06232d06e6682b44aa21a`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-454981.js

Blob: `e9dd94b102345d0a2139af5d03c7d12b663b19e1`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- f1 @22-25; FunctionDeclaration; parameters=0; async=false; generator=false
- f0 @23-23; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455605.js

Blob: `08beb130791c815d12a71a126758851640727add`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455748.js

Blob: `a8e9ab9767dd9c161f437d7da9f70aeecaa9d721`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455758-01.js

Blob: `a3ca13e673c9f72695f4b827ca9e21ebf579fd44`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455758-02.js

Blob: `c036e269d501f4ccb78df36a4e4afe7ba55b55f6`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455775.js

Blob: `8b16215bcf9806abd2e25860903b675df13ef96b`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455981-01.js

Blob: `f852fbde4843d4ef22222bf94761efd87891a6b6`. Role: test-path,source. Parse: module.

- test @16-32; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-455981-02.js

Blob: `c1808dd119e09790e0ae08df9f49e7a34255ef48`. Role: test-path,source. Parse: module.

- test @16-32; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456470.js

Blob: `192ee5b7a9186459c09a5d9b27ed302873f5be51`. Role: test-path,source. Parse: module.

- test @16-34; FunctionDeclaration; parameters=0; async=false; generator=false
- x @22-27; FunctionDeclaration; parameters=0; async=false; generator=false
- a @23-25; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456477-01.js

Blob: `60b402b16260937a9850f1da1f08c0493351f758`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456477-02.js

Blob: `3895b95cdbb49e3582b89c046f6974f1f41dedbf`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456494.js

Blob: `ef8d9dba9502c91bcb1f96ab43c72011472b5fc9`. Role: test-path,source. Parse: module.

- test @16-35; FunctionDeclaration; parameters=0; async=false; generator=false
- k @22-24; FunctionDeclaration; parameters=1; async=false; generator=false
- f @25-31; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456540-01.js

Blob: `3af72b4b54932cc052084d4c7469769895b82eb4`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-456540-02.js

Blob: `dfb6a2f6783a9d3e541463371d9f7c639d3daf20`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-457065-01.js

Blob: `26505aa6edc61c83cffc73609a9e81d6948b8690`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-457065-02.js

Blob: `c2a949086c8ee9cf1cfa4aec74067f12e7670f05`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-457065-03.js

Blob: `edcad4446a6c560c9db570de0a3c761e6ab501b4`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-457456.js

Blob: `af3959a1f7e3163d4884fae9d450b611bb0b6d33`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-457778.js

Blob: `df01e425275aa11adefb5a8e8b7c9903cbb251b0`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-458076.js

Blob: `fe8c318aeddc334766f5c7a18b0489858815e182`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-458851.js

Blob: `996779466ccfb1f5dd70ac1a2fa93cf0cedaa4c3`. Role: test-path,source. Parse: module.

- f @15-23; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-459185.js

Blob: `a8f4dcdd1ea98310b362534ba6959d53f388f29b`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-459186.js

Blob: `3ec76daa6c6cfff06a431be49256ace2b4290868`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-459389.js

Blob: `3d49136ba0745de6479b892c8156b213c33045c2`. Role: test-path,source. Parse: module.

- SNI.MetaData.Parameter @19-38; FunctionExpression; parameters=0; async=false; generator=false
- ?.addParameter @22-26; FunctionExpression; parameters=2; async=false; generator=false
- ?.getParameter @27-33; FunctionExpression; parameters=2; async=false; generator=false
- ?.getKeys @34-37; FunctionExpression; parameters=0; async=false; generator=false
- SNI.MetaData.Manager @39-42; FunctionExpression; parameters=0; async=false; generator=false
- SNI.Ads.Url @45-49; FunctionExpression; parameters=0; async=false; generator=false
- Ad @50-54; FunctionDeclaration; parameters=0; async=false; generator=false
- DartAd @55-57; FunctionDeclaration; parameters=0; async=false; generator=false
- AdUrl @58-58; FunctionDeclaration; parameters=0; async=false; generator=false
- AdRestriction @59-64; FunctionDeclaration; parameters=0; async=false; generator=false
- AdRestrictionManager @65-100; FunctionDeclaration; parameters=0; async=false; generator=false
- isActive @70-77; FunctionDeclaration; parameters=2; async=false; generator=false
- startMatch @78-88; FunctionDeclaration; parameters=3; async=false; generator=false
- isMatch @89-99; FunctionDeclaration; parameters=2; async=false; generator=false
- FoodAd @108-113; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-459628.js

Blob: `fc8af9fe5d96718c019ab03ae586f45d5c6147c0`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-459990.js

Blob: `af2a04ef03cbc839d6ddfc05fd58631d2f1dc54b`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-460024.js

Blob: `c7d78e046f85c55082fc4ebe0f2d0c92b98e94ae`. Role: test-path,source. Parse: module.

- test @16-35; FunctionDeclaration; parameters=0; async=false; generator=false
- doeval @30-30; FunctionDeclaration; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-460117.js

Blob: `419800b04a267950cd2e789d0fce3655f4c37fe1`. Role: test-path,source. Parse: module.

- test @16-41; FunctionDeclaration; parameters=0; async=false; generator=false
- t @21-30; FunctionDeclaration; parameters=2; async=false; generator=false

### js/src/tests/non262/regress/regress-460886-01.js

Blob: `73797b3d4245abab03ef85061d88370fd697a921`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-460886-02.js

Blob: `863395458c969030bdf94201720b2403ac644db6`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-461307.js

Blob: `ca782703ae4da3f745011363959080646874e650`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-461723.js

Blob: `9becb5e601ae306902bc004d6b6dca5e761a4671`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-462071.js

Blob: `4ea388c8632969d581b19285e9cc1dba47997561`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-462282.js

Blob: `2c7ab61e30020f28d5ae250484e5b7ea961d198c`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-462292.js

Blob: `4e391d3b7dc637cbad142876a9948f48f870feed`. Role: test-path,source. Parse: failed.

Failure: Assigning to rvalue


### js/src/tests/non262/regress/regress-462388.js

Blob: `11f72e596707a8a64e9b441072a4cbc75c22b946`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-462407.js

Blob: `ff41299557a011a7b3124085719430f2747a0001`. Role: test-path,source. Parse: module.

- f @15-15; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-462879.js

Blob: `050a1fad2e94feae27fcb107b817c402bf3d4db1`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-462989.js

Blob: `489995474999c6a56f4d840c5c78aa9f65d8082d`. Role: test-path,source. Parse: module.

- a @15-19; FunctionDeclaration; parameters=0; async=false; generator=false
- b @21-25; FunctionDeclaration; parameters=0; async=false; generator=false
- t @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-463259.js

Blob: `864b43f46dd64101b6204762c0307ba6f610de88`. Role: test-path,source. Parse: module.

- (anonymous) @17-19; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-463782.js

Blob: `437c04a0a02f9e5407d00f04af19115c9e1d53b3`. Role: test-path,source. Parse: module.

- dateCheck @15-17; FunctionDeclaration; parameters=0; async=false; generator=false
- dateToString @18-23; FunctionDeclaration; parameters=0; async=false; generator=false
- placeAd2 @25-59; FunctionDeclaration; parameters=0; async=false; generator=false
- templateCheck @28-54; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-464096.js

Blob: `ddca018da3f676e54c6db10b6d3f468fce38db69`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-464334.js

Blob: `48872c079d5c81d7896ecf90eb2432f46b202afc`. Role: test-path,source. Parse: module.

- test @16-32; FunctionDeclaration; parameters=0; async=false; generator=false
- g @21-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-464403.js

Blob: `5aaf594bcdb6be22af51b831603b5b69aa70bf12`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-464418.js

Blob: `e2c42ed95610f04cc3725e293f7bac4c67de2618`. Role: test-path,source. Parse: module.

- test @18-42; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-464862.js

Blob: `338b51799632dc5d3ca4295ec4be674f5ea6d883`. Role: test-path,source. Parse: module.

- ygTreeView @14-16; FunctionDeclaration; parameters=1; async=false; generator=false
- ygTreeView.prototype.init @18-18; FunctionExpression; parameters=1; async=false; generator=false
- ygNode @20-20; FunctionDeclaration; parameters=0; async=false; generator=false
- ygNode.prototype.init @24-32; FunctionExpression; parameters=3; async=false; generator=false
- ygNode.prototype.appendChild @34-39; FunctionExpression; parameters=1; async=false; generator=false
- ygNode.prototype.getElId @41-41; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.getNodeHtml @43-43; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.getToggleElId @45-45; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.getStyle @47-51; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.hasChildren @53-53; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.getHtml @55-60; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.getChildrenHtml @62-67; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.renderChildren @69-69; FunctionExpression; parameters=0; async=false; generator=false
- ygNode.prototype.completeRender @71-76; FunctionExpression; parameters=0; async=false; generator=false
- ygRootNode @80-82; FunctionDeclaration; parameters=1; async=false; generator=false
- ygTextNode @86-89; FunctionDeclaration; parameters=3; async=false; generator=false
- ygTextNode.prototype.setUpLabel @91-95; FunctionExpression; parameters=1; async=false; generator=false
- ygTextNode.prototype.getNodeHtml @97-106; FunctionExpression; parameters=0; async=false; generator=false
- buildUserTree @108-113; FunctionDeclaration; parameters=0; async=false; generator=false
- addMenuNode @115-117; FunctionDeclaration; parameters=3; async=false; generator=false

### js/src/tests/non262/regress/regress-464978.js

Blob: `4b974450141873acbe6fc7352ebc29ad4d2140ed`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465013.js

Blob: `22d7080a284a436ad88dfa327f19c9572b2b2154`. Role: test-path,source. Parse: module.

- test @16-35; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @24-31; FunctionExpression; parameters=1; async=false; generator=false

### js/src/tests/non262/regress/regress-465132.js

Blob: `071db71b2e6ad7bfc88b4968219d9b7fa827f9b2`. Role: test-path,source. Parse: module.

- test @16-38; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465133.js

Blob: `37648ff9a5c44a4ffec456146899a00956b4e825`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465135.js

Blob: `62ef71051e9e6303184289d9074652833f78df30`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465136.js

Blob: `83c23f208c1fcb886977738abd09d2498be76316`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465137.js

Blob: `0bf004638c239c784fe5f1a86b0944f658b9f170`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465220.js

Blob: `fedb0371c5c7c5a23c7cdd0ae8d4f9972a0b7238`. Role: test-path,source. Parse: module.

- test @16-39; FunctionDeclaration; parameters=0; async=false; generator=false
- toString @26-26; FunctionExpression; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465234.js

Blob: `705a9f843f79f33c0123bea011a575afda7321b9`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465236.js

Blob: `911fe5a483fc67ac7782ae8c7cf46c729c0ac120`. Role: test-path,source. Parse: module.

- test @16-24; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465239.js

Blob: `8603c00ea31e7145cf37f5f4562475befdac43a9`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465241.js

Blob: `e269f7f2edd28e7908c93b2e2758d86d69bb5807`. Role: test-path,source. Parse: module.

- test @16-29; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465249.js

Blob: `6730c30a4193e98c863517597b8f45a809177197`. Role: test-path,source. Parse: module.

- test @16-26; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465261.js

Blob: `5fb229d202c484b972bbee7e26f8cef0843b3e47`. Role: test-path,source. Parse: module.

- test @16-30; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465262.js

Blob: `60e5963f0bc1ee3088a1d82d52cf074fe5f1c426`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465272.js

Blob: `38ab3aeda6f1eedca568a8b56c977f4f2ea365d7`. Role: test-path,source. Parse: module.

- test @16-28; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465308.js

Blob: `282e674887f196013a19c3559bc7825b427adb0b`. Role: test-path,source. Parse: module.

- test @16-27; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465347.js

Blob: `8f1a3fef4a4278b71f924223e67196de0ddcbe54`. Role: test-path,source. Parse: module.

- test @16-48; FunctionDeclaration; parameters=0; async=false; generator=false

### js/src/tests/non262/regress/regress-465366.js

Blob: `1b32d61e6bcf6af953e68ca60d9197acc04fa0b3`. Role: test-path,source. Parse: module.

- test @16-35; FunctionDeclaration; parameters=0; async=false; generator=false
- f @22-29; FunctionDeclaration; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [d055617a-c542-4feb-9394-e5fb87fa0eb7.md](d055617a-c542-4feb-9394-e5fb87fa0eb7.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `0c163e31aaffe4960055fde6d6674926404c416033136ad020f5c595ef06bce0`.
