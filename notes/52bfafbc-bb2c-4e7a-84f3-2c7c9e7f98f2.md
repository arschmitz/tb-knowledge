<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["8830693ba8774f05a1f94d3f3e29d90c63312f65028064fe9749de36a28f51e7"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/95c5101d-274c-4955-be22-73affe3514be.md"}} -->
# firefox/testing JavaScript function map 782

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.extraargs.cache.worker.js

Blob: `f508d5262e0608a2cbe64dd894aa47e4d438e83a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.extraargs.create.worker.js

Blob: `d1bfbcc683cfcaf4223aac69a78c7296c187aaeb`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.invalid.args.worker.js

Blob: `faea21714d56f0d9843a21eb364eece9c50afd5b`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @24-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.prototype.worker.js

Blob: `dd41239d00c37c73f4833e7bcd5d28f5340bda34`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.shared.worker.js

Blob: `8e53475756329718e26e95d5c7d5127cce8a4ff7`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-25; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.type.exists.worker.js

Blob: `239c3e902eacb61428c776e95d9f13c287ea0244`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.type.extend.worker.js

Blob: `9832c5ca77f0559a93e67d122d1f3fc779d0a8ec`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false
- self.OffscreenCanvasRenderingContext2D.prototype.fillRectGreen @19-23; FunctionExpression; parameters=4; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.type.prototype.worker.js

Blob: `459975d32d2c7be264ee1b70206d9ac452ee37fd`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.type.replace.worker.js

Blob: `e6793d1bf56d94fd4cb1aaecfe059d3b5f19e4bb`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-29; FunctionExpression; parameters=0; async=false; generator=false
- self.OffscreenCanvasRenderingContext2D.prototype.fillRect @20-24; FunctionExpression; parameters=4; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.canvas.context.unique.worker.js

Blob: `90687bfd07e6fff5936132b2f255f3dbfbc260c4`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-context/2d.getContext.options.any.js

Blob: `930f7722ee0eae02674c6773751d04c69f4bb384`. Role: test-path,source. Parse: module.

- (anonymous) @1-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- alpha @11-14; FunctionExpression; parameters=0; async=false; generator=false
- willReadFrequently @15-18; FunctionExpression; parameters=0; async=false; generator=false
- desynchronized @19-22; FunctionExpression; parameters=0; async=false; generator=false
- colorSpace @23-31; FunctionExpression; parameters=0; async=false; generator=false
- toString @26-29; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.color.worker.js

Blob: `11d6b9f098e7bed4c47c2aa9dbd9ace9f4b29764`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.2dstate.worker.js

Blob: `4b2b4b62a5cb54c1d701c89b672b2db7567f2894`. Role: test-path,source. Parse: module.

- (anonymous) @9-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @39-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-67; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @79-87; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @89-97; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @99-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @109-117; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @119-127; ArrowFunctionExpression; parameters=1; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.clip.worker.js

Blob: `80554b0a3fdf11bfda72bc92b4d2ce640f5f2395`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.different.worker.js

Blob: `6074d4f2a2c88eda4d8f91fd0b931fda6bbb7f01`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-25; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.gradient.worker.js

Blob: `9029b48056fa03e60236505b159f067bb689d9d8`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.path.worker.js

Blob: `0ab12872aee4a3ce6b0e9122e7222661e543d38e`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.pattern.worker.js

Blob: `c4870a6f998b9b63d90c37613dd2cbce5d0e3e02`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.same.worker.js

Blob: `48d24750ac4e85e638c8b6ad6e9386b3f68b61d3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.initial.reset.transform.worker.js

Blob: `218e64fa5dc34070ec5b84b2f3b86edceadc256f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.readonly.worker.js

Blob: `5baef1b374057326c91b25030a88756cf3119728`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-25; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.reference.worker.js

Blob: `7a1f0c5ab498a3c7acb9cd17c71561fce0b73088`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.default.worker.js

Blob: `78fce5aef8d510a1366cec79a6ace66c1e53cfbf`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.idl.set.zero.worker.js

Blob: `21535da0eb335eec3f73548d8350fc946d8e1726`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.idl.worker.js

Blob: `42002e8355fd5f53a64b66ec60b8370d92059552`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-32; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.decimal.worker.js

Blob: `1267bb205a94034bb790e7aa0910f0fcdfce763b`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.em.worker.js

Blob: `2f0642d99790ab1009709051bc6f5c9d61c8830a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.empty.worker.js

Blob: `b1eee3a5b226f1627e243537e4f70f6c3ec72eb3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.exp.worker.js

Blob: `8c8b4cc715efae513b7d5071b55084d5013d2361`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.hex.worker.js

Blob: `b685aaffa2d9c5d99c8c03e6ee1b77a7ef832aa4`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.junk.worker.js

Blob: `f4822f4bd954618d238c15fa2db7724d3649a8dc`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.minus.worker.js

Blob: `322b992eda24947c04e3eff3c5dec6e3133f37f7`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.octal.worker.js

Blob: `ce518e35c7ad6b4305c6c0dacec11630feb74835`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.onlyspace.worker.js

Blob: `c186a4c08bab5f604b843c9ebd936fe62202cc3d`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.percent.worker.js

Blob: `f38a1862d41aecfd3052f73d2df76eff0b0c8a15`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.plus.worker.js

Blob: `bb45a1e4fa07954b54aa0b742e77571a99253ec0`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.space.worker.js

Blob: `967a0939d806700df42c67481dbdb71a79a2a8de`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.trailingjunk.worker.js

Blob: `ffebcd97f1ec2aab95c5caf3951ed0c45ba9a4b3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.whitespace.worker.js

Blob: `fb7ba47975ae150e22e63908d9260ecb5a9660aa`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.parse.zero.worker.js

Blob: `1363bff7728a1e6a091818f3588b8026eb8efcac`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.reflect.setidl.worker.js

Blob: `3b3ced124ab2bda792db0c00ce6dfc3e4fe18320`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.attributes.reflect.setidlzero.worker.js

Blob: `d440a9d807a7877ce7af903f7de99112187fcc93`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.invalid.attributes.idl.worker.js

Blob: `8adb7a514c542bbf3acf19be4c0922bc4d46fb4a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.size.large.worker.js

Blob: `a763704131a55f958c0971407c626d5437ec74ae`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-25; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.type.delete.worker.js

Blob: `409e12cd0d0d090dbef46a221e7ba96d06b17029`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-22; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/canvas-host/2d.canvas.host.type.name.worker.js

Blob: `ea50e4f7f0c4266db762be78fbeda58095c71c1e`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/color-type/2d.color.type.u8p3.to.f16srgb.to.u8p3.worker.js

Blob: `7b8eb3d687f8413542db20a1f4e08c339a1ace48`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/color-type/2d.color.type.u8p3.to.u8srgb.to.u8p3.worker.js

Blob: `0d03eacf4b6cffe8bb4dcd94069bbf6ecf1ce95f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-38; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/color-type/2d.color.type.u8srgb.to.f16p3.to.u8srgb.worker.js

Blob: `85f48acf251dbd201ed04dcc5b513f93476baf21`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-39; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/color-type/2d.color.type.u8srgb.to.u8p3.to.u8srgb.worker.js

Blob: `f4d0ebacbcc35c8b14a20ff1172f5fcb00dda7a2`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-38; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.clear.worker.js

Blob: `3f17857e4ceb549550f59b2b3d55129e1096aed1`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.copy.worker.js

Blob: `75c504990bad5932fc037547cac39bab09e6e00e`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.destination-atop.worker.js

Blob: `fcdd5efe7df59d9ea61b3040270b05946d9fe77a`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.destination-in.worker.js

Blob: `5d507461ecfce702000fa60a27adbef7badf8cad`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.destination-out.worker.js

Blob: `7958eccfac3bd65526791bd8ca8efdf82cb0e629`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.destination-over.worker.js

Blob: `aea0df09c35466c6eba6f60721f8c9a6a5f1bf0c`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.lighter.worker.js

Blob: `0ec46bf886daec47af85d736ef03166016da67e6`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.source-atop.worker.js

Blob: `197660894fdecfc3e11842ff47875a5ca04edb23`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.source-in.worker.js

Blob: `293b9c12415bde9a71a52a4f30814a0b4d6805b3`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.source-out.worker.js

Blob: `49ff15abf8871226cbd0cab4e42b17150e9e987b`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.source-over.worker.js

Blob: `9f2d549d8f009f0673913f1d4e58ab31baa973b0`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.canvas.xor.worker.js

Blob: `4e70cf2b881dc0c1a311aa9b3d3cd8b63373e82f`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.clear.worker.js

Blob: `5c9194a10ee666451e085c05cbfb99e5309dab5c`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.copy.worker.js

Blob: `4f237bc1c0d3612e0b91231c8d71a6c3f1182b45`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.destination-atop.worker.js

Blob: `e7c73bbcc77cb0501aedea189a02b1fb8de6e532`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.destination-in.worker.js

Blob: `a340717a5f216e3e9a8619f6d6274deb9b1a2316`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.destination-out.worker.js

Blob: `50667de828a580c6c6ab1f817684732702eb045f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.destination-over.worker.js

Blob: `5c638f991648b557e014bdaf1e7a3e5e6e398d28`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.lighter.worker.js

Blob: `0958131684c55b335654b46e1ba972d29569b7ce`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.source-atop.worker.js

Blob: `a7645265f9b09a369bf025d92c14b7b36548f04e`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.source-in.worker.js

Blob: `5ba3a3554a64859ef50852d3039f0878b241e9e5`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.source-out.worker.js

Blob: `2a575f189294ea6a57ed94ccd114427551ce13b8`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.source-over.worker.js

Blob: `37cd50f0b209626a0276bf0483783a79fcde7b98`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.clip.xor.worker.js

Blob: `358434b34e44004c60aef5d81ea7b3d1ca5400cd`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.canvas.worker.js

Blob: `ede4733a8315521b495ecd1b79d2fa30ea17ebf4`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.canvascopy.worker.js

Blob: `f61859d2310c210e817a12dbc6811748988f388e`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.canvaspattern.worker.js

Blob: `7ecd568fae8943511a41e1d76b4ee03556ff01e2`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-31; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.default.worker.js

Blob: `8acbd6a37fcbd05bdfa7cba6e3044f4d9937990f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.fill.worker.js

Blob: `3ea8aa7ebeeb79bcef05c8ef3fcab66c0b18673d`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.image.worker.js

Blob: `1a181a1cc1a176b458334f5aa4a4489d8674181a`. Role: test-path,source. Parse: module.

- (anonymous) @9-23; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.imagepattern.worker.js

Blob: `cb8f1413a2d95baded7079dbbba8f0c9951c2da3`. Role: test-path,source. Parse: module.

- (anonymous) @9-24; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.invalid.worker.js

Blob: `4ca577ad440a1cce21137d30f33fa263825ef626`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-30; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.globalAlpha.range.worker.js

Blob: `76ea8199098457c5b47328660fbfaf883fe9ddd6`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-33; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.clear.worker.js

Blob: `e60b521f6a93ef03c138d96b757145eee1b24b74`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.copy.worker.js

Blob: `a6b90d892e8e0de58605b11d174a2c661e12d220`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.destination-atop.worker.js

Blob: `99962b16fc4d806f1780042c8cb84e0d25f69dc6`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.destination-in.worker.js

Blob: `39d11f567f562caec49a4dd6312d189f1bca2a30`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.destination-out.worker.js

Blob: `843652a86b813cf352cfb45c72f058b48382b84e`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.destination-over.worker.js

Blob: `3bb9d4ee37213662cf1517f4f63975ec7bee82d1`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.lighter.worker.js

Blob: `d361064a1ce43f561061e741c3b084a6b5076997`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.source-atop.worker.js

Blob: `067bbfa682e6940f4be3e889d9037abc72597b7a`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.source-in.worker.js

Blob: `7b5ffbc63277859d94c1f5096d4fb94b16ff3e21`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.source-out.worker.js

Blob: `fe785a5e24af5b58a94b8391172e3b79ad932b19`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.source-over.worker.js

Blob: `a9304b305efdab3950e202b63656e3e74f6f656e`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.image.xor.worker.js

Blob: `c8822bc98f5ad930f8cf56f9ff2a5a80d10399d6`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.casesensitive.worker.js

Blob: `db1b54f5efef392e4f34996c15064f295868449c`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.clear.worker.js

Blob: `947dd16c5f962002ff9d71be739ea5c709b73a2c`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.darker.worker.js

Blob: `528f6b93d949c6a112f51222894a41b9dd4d9caa`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.default.worker.js

Blob: `ffdb75ad75a04d9b5b1415c4d432e8f2883a21e6`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-21; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.get.worker.js

Blob: `a266f1d537d5a06b8044ccd60d8f03756ce6726d`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.highlight.worker.js

Blob: `800c4605e6241f97846cb7a85e340f960885d623`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.nullsuffix.worker.js

Blob: `1c1d5124a3479b82373ad8d533b50b00553bce1f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.over.worker.js

Blob: `f75a462e935549e57b645a70995b17bdbd501c3d`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.operation.unrecognised.worker.js

Blob: `23a6630e82a7fa0b619a653bf7826f387fbd76b6`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-23; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.clear.worker.js

Blob: `c49ec7a322ffd100cf12421a69d9c04f1f388ee3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.copy.worker.js

Blob: `ee4baecbd2ab178f84303e8dbdb677cc82297641`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.destination-atop.worker.js

Blob: `8829971c6b6638276ef0bd7d3fcd268cc1f6a9af`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.destination-in.worker.js

Blob: `fe9e461717967cdfe3e96b7627f6644601978f4a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.destination-out.worker.js

Blob: `05ec2fae16ff5484bc7662c767eb6b929ed8dc8b`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.destination-over.worker.js

Blob: `5c171fc282b9e90417f006cc34b5c0fce2c85143`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.lighter.worker.js

Blob: `353389221dab293b86834978944afa8f6f56d41f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.source-atop.worker.js

Blob: `27e1c253ce028772be36b95511e96db311176708`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.source-in.worker.js

Blob: `7dfdb07075cd18ae9599931b87cb3e29b9cf5706`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.source-out.worker.js

Blob: `82525492675740a20344496d86b98629b03efbd3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.source-over.worker.js

Blob: `1c82a95c3637620f1b0b04bf8dbad394486e084a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.solid.xor.worker.js

Blob: `cb098ebab1a2f03569faf3ac1f77038e1da18d33`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.clear.worker.js

Blob: `8f30463c4173db92a8eec0831a64ea07b7861679`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.copy.worker.js

Blob: `6b9ea9dbcfbb93a576cfaefedb9874afd352f656`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.destination-atop.worker.js

Blob: `3247632e53aa31fed808c64554287d42f23160a7`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.destination-in.worker.js

Blob: `c9205230c0ef82586619ce9a092c380f8653a4ce`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.destination-out.worker.js

Blob: `1a5409589b4dac125255c24534246ff9879eee39`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.destination-over.worker.js

Blob: `37eb785d673d10e53e2d533889a8ea4edd171cf3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.lighter.worker.js

Blob: `3d890affd909c9745d12293d04b2444060b4a64a`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.source-atop.worker.js

Blob: `d56ef6e2e401c7f102379bb89ddaa5653ce57379`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.source-in.worker.js

Blob: `58ad13bc5e7ca9b6b5f478cdc6e1edb66f6b78c5`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.source-out.worker.js

Blob: `62ec8959550f5d9e2af2c870431c589e00cfafbd`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.source-over.worker.js

Blob: `494a45f848e78edaad197286ab5e8d188b280ea7`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.transparent.xor.worker.js

Blob: `4b65667ed81febf10902bb82c19d2abfccd6e6b1`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.fill.copy.worker.js

Blob: `50f3ed0f222ffe800ce156300ea59226ce553250`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.fill.destination-atop.worker.js

Blob: `9a84b0894a769660ae9950071443482e53c16557`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.fill.destination-in.worker.js

Blob: `aa24ba97a60860f9df8c268d82dbbdd093185692`. Role: test-path,source. Parse: module.

- (anonymous) @12-14; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-28; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.fill.source-in.worker.js

Blob: `33e326d1f47e83b0fc51274b24b73f5c5de1910f`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.fill.source-out.worker.js

Blob: `1d39b364b0e5bf0e8844ff0e928fc8f2400ec8a3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-27; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.image.copy.worker.js

Blob: `e93962ce6d6eb9d48b75edfa5f0466875e4e05a7`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.image.destination-atop.worker.js

Blob: `3cea3620424f878be6ac100315fb31271f7b1739`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.image.destination-in.worker.js

Blob: `d96c112d646362f4b3d6970e18c8894e0867f8c6`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.image.source-in.worker.js

Blob: `5b6bad7d38c2edfee91d1a99a7389f7f37d0e208`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.image.source-out.worker.js

Blob: `fa44cb7556de195f172c16eafec63ed790c327ec`. Role: test-path,source. Parse: module.

- (anonymous) @9-21; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.nocontext.copy.worker.js

Blob: `251f8ac5fa43bdc70a4f143a8fbf08c6b5db13e7`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.nocontext.destination-atop.worker.js

Blob: `4ed132e87ed72dcb3086dcf064ba3900ac8eafaa`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.nocontext.destination-in.worker.js

Blob: `d33eb3544cdb26f9038aa1ce1145ba84a2781fd3`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.nocontext.source-in.worker.js

Blob: `eb90a7e3b8be441dea8bb1cf09dc1420bb8633a2`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.nocontext.source-out.worker.js

Blob: `269adf9dcbb85b0083e81df6721f8d14b78c4ac8`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-26; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.pattern.copy.worker.js

Blob: `bd59189e6d3784e29b5b3b8474a2314437582bbf`. Role: test-path,source. Parse: module.

- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.pattern.destination-atop.worker.js

Blob: `17ebb53db00f94e6a4acc37824c32e4edc03cb50`. Role: test-path,source. Parse: module.

- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.pattern.destination-in.worker.js

Blob: `62ae7f569d7dc7e605f3aefb3d0eefcb62924c31`. Role: test-path,source. Parse: module.

- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.pattern.source-in.worker.js

Blob: `03a3b2f072f3db6af67a946b6bed4508f1a7b0ae`. Role: test-path,source. Parse: module.

- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/compositing/2d.composite.uncovered.pattern.source-out.worker.js

Blob: `0fff24429130136285845d4772cde864a86e9beb`. Role: test-path,source. Parse: module.

- (anonymous) @9-22; ArrowFunctionExpression; parameters=1; async=true; generator=false

### testing/web-platform/tests/html/canvas/offscreen/conformance-requirements/2d.conformance.requirements.basics.worker.js

Blob: `b16a39fd3c978067a79f7ad1f94506577fcc3689`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-56; FunctionExpression; parameters=0; async=false; generator=false

### testing/web-platform/tests/html/canvas/offscreen/conformance-requirements/2d.conformance.requirements.missingargs.worker.js

Blob: `f249fcb881a831f085a6443af502130e35e395e6`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-135; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @21-21; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-26; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-27; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-40; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @47-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-48; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-49; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-52; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-53; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-54; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-55; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-56; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-57; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-58; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @59-59; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @60-60; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-61; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-63; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-64; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @65-65; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @67-67; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @68-68; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-69; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @70-70; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-71; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-72; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @73-73; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-74; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-75; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-76; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-77; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @78-78; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-79; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @80-80; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @81-81; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-82; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-83; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @84-84; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @85-85; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-86; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @87-87; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-88; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-89; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-92; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-93; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-96; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-97; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @98-98; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @101-101; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @102-102; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @103-103; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @104-104; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-105; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-106; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @107-107; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @110-110; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-111; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @116-116; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-117; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-120; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @121-121; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @122-122; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @123-123; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-127; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @128-128; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @129-129; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @132-132; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-133; FunctionExpression; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [95c5101d-274c-4955-be22-73affe3514be.md](95c5101d-274c-4955-be22-73affe3514be.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `8830693ba8774f05a1f94d3f3e29d90c63312f65028064fe9749de36a28f51e7`.
