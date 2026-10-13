<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["dom"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["14b7546512cd7c45752bef238c09f378bb4cb9bad76f1ab5e8c4ea6b890fca9b"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/8ed4754b-230f-450c-932d-bd7e1af871c2.md"}} -->
# firefox/dom native and TypeScript syntax map 20

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### dom/canvas/WebGLContext.h

Blob: `5b4f1abe5ac6abbd1240f984296d3002360c3f7a`. Grammar: cpp. Status: contains-errors.

- include <bitset> @8
- include <memory> @9
- include "Colorspaces.h" @11
- include "GLContextTypes.h" @12
- include "GLDefs.h" @13
- include "GLScreenBuffer.h" @14
- include "ScopedGLHelpers.h" @15
- include "SurfaceTypes.h" @16
- include "TexUnpackBlob.h" @17
- include "js/ScalarType.h" @18
- include "mozilla/Atomics.h" @19
- include "mozilla/EnumeratedArray.h" @20
- include "mozilla/Mutex.h" @21
- include "mozilla/StaticMutex.h" @22
- include "mozilla/StaticPrefs_webgl.h" @23
- include "mozilla/WeakPtr.h" @24
- include "mozilla/dom/BindingDeclarations.h" @25
- include "mozilla/dom/HTMLCanvasElement.h" @26
- include "mozilla/dom/Nullable.h" @27
- include "mozilla/dom/TypedArray.h" @28
- include "mozilla/dom/ipc/IdType.h" @29
- include "mozilla/gfx/2D.h" @30
- include "nsICanvasRenderingContextInternal.h" @31
- include "nsTArray.h" @32
- include "CacheInvalidator.h" @35
- include "WebGLContextLossHandler.h" @36
- include "WebGLExtensions.h" @37
- include "WebGLObjectModel.h" @38
- include "WebGLStrongTypes.h" @39
- include "WebGLTypes.h" @40
- include <list> @43
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @45
- include "mozilla/dom/WebGLRenderingContextBinding.h" @46
- class_specifier nsIDocShell @48-48
- class_specifier HostWebGLContext @61-61
- class_specifier ScopedCopyTexImageSource @62-62
- class_specifier ScopedDrawCallWrapper @63-63
- class_specifier ScopedResolveTexturesForDraw @64-64
- class_specifier WebGLBuffer @65-65
- class_specifier WebGLExtensionBase @66-66
- class_specifier WebGLFramebuffer @67-67
- class_specifier WebGLProgram @68-68
- class_specifier WebGLQuery @69-69
- class_specifier WebGLRenderbuffer @70-70
- class_specifier WebGLSampler @71-71
- class_specifier WebGLShader @72-72
- class_specifier WebGLSync @73-73
- class_specifier WebGLTexture @74-74
- class_specifier WebGLTransformFeedback @75-75
- class_specifier WebGLVertexArray @76-76
- class_specifier WebGL2Context @77-77
- class_specifier Document @80-80
- class_specifier Element @81-81
- class_specifier ImageData @82-82
- class_specifier OwningHTMLCanvasElementOrOffscreenCanvas @83-83
- struct_specifier WebGLContextAttributes @84-84
- class_specifier SourceSurface @88-88
- class_specifier VRLayerChild @89-89
- class_specifier GLScreenBuffer @93-93
- class_specifier MozFramebuffer @94-94
- class_specifier SharedSurface @95-95
- class_specifier Sampler @96-96
- class_specifier Texture @97-97
- class_specifier CompositableHost @101-101
- class_specifier RemoteTextureOwnerClient @102-102
- class_specifier SharedSurfacesHolder @103-103
- class_specifier SurfaceDescriptor @104-104
- class_specifier AvailabilityRunnable @108-108
- struct_specifier CachedDrawFetchLimits @109-109
- struct_specifier FbAttachInfo @110-110
- struct_specifier FormatInfo @111-111
- class_specifier FormatUsageAuthority @112-112
- struct_specifier FormatUsageInfo @113-113
- struct_specifier ImageInfo @114-114
- struct_specifier LinkedProgramInfo @115-115
- struct_specifier SamplerUniformInfo @116-116
- struct_specifier SamplingState @117-117
- class_specifier ScopedPrepForResourceClear @118-118
- class_specifier ShaderValidator @119-119
- class_specifier TexUnpackBlob @120-120
- struct_specifier UniformInfo @121-121
- struct_specifier UniformBlockInfo @122-122
- struct_specifier VertAttribPointerDesc @123-123
- class_specifier AvailabilityRunnable @134-144
- class_specifier WebGLContext @150-1330
- enum_specifier (anonymous) @188-199
- class_specifier LruPosition @202-220
- function_definition ~LruPosition @214-214
- function_definition LruPosition @216-216
- function_definition LruPosition @217-217
- function_definition (anonymous) @218-218
- function_definition (anonymous) @219-219
- class_specifier FuncScope @285-285
- function_definition (anonymous) @346-346
- class_specifier FuncScope @349-358
- function_definition GenerateErrorImpl @360-362
- function_definition GenerateError @365-367
- function_definition GenerateError @370-392
- function_definition ErrorInvalidEnum @395-397
- function_definition ErrorInvalidOperation @399-401
- function_definition ErrorInvalidValue @403-405
- function_definition ErrorInvalidFramebufferOperation @407-410
- function_definition ErrorOutOfMemory @412-414
- function_definition ErrorImplementationBug @417-427
- function_definition GL @450-450
- function_definition IsPremultAlpha @452-452
- function_definition IsPreservingDrawingBuffer @454-456
- function_definition SetDrawingBufferColorSpace @517-519
- function_definition SetUnpackColorSpace @521-523
- function_definition IsContextLost @545-551
- function_definition ValidateBufferForNonTf @718-723
- struct_specifier ScissorRect @765-772
- function_definition OnDataAllocCall @780-780
- function_definition GLMaxDrawBuffers @921-921
- function_definition MaxValidDrawBuffers @923-929
- function_definition LastColorAttachmentEnum @931-933
- function_definition (anonymous) @935-935
- function_definition (anonymous) @941-941
- function_definition MaxVertexAttribs @942-942
- function_definition GLMaxTextureUnits @943-943
- function_definition IsExtensionEnabled @961-963
- function_definition IsWebGL2 @973-973
- function_definition AsWebGL2 @975-975
- struct_specifier FailureReason @977-986
- function_definition FailureReason @981-981
- function_definition FailureReason @984-985
- function_definition HasDrawBuffers @1048-1051
- function_definition ValidateNonNegative @1067-1073
- function_definition ValidateNonNull @1076-1083
- function_definition (anonymous) @1137-1137
- function_definition ShouldGenerateWarnings @1199-1199
- function_definition ShouldGeneratePerfWarnings @1201-1203
- struct_specifier GetDefaultFBForReadDesc @1275-1277
- function_definition GetDefaultFBForRead @1279-1281
- function_definition GenerateWarning @1290-1292
- function_definition GeneratePerfWarning @1295-1299
- function_definition RoundUpToMultipleOf @1335-1337
- class_specifier ScopedFBRebinder @1339-1346
- function_definition ScopedFBRebinder @1344-1344
- function_definition IsBufferTargetLazilyBound @1350-1352
- class_specifier ScopedLazyBind @1356-1375
- function_definition ScopedLazyBind @1362-1368
- function_definition ~ScopedLazyBind @1370-1374
- class_specifier ScopedDrawCallWrapper @1388-1394
- class_specifier ScopedPrepForResourceClear @1398-1404
- struct_specifier IndexedName @1406-1409

### dom/canvas/WebGLContextBuffers.cpp

Blob: `3adc569ba2fdd9f19e7f7ecadda0687c2c7df7c4`. Grammar: cpp. Status: syntax-clean.

- include "ClientWebGLContext.h" @5
- include "GLContext.h" @6
- include "WebGLBuffer.h" @7
- include "WebGLContext.h" @8
- include "WebGLTransformFeedback.h" @9
- include "WebGLVertexArray.h" @10
- function_definition ValidateBufferSlot @14-61
- function_definition ValidateBufferSelection @63-92
- function_definition ValidateIndexedBufferSlot @94-125
- function_definition BindBuffer @129-149
- function_definition ValidateIndexedBufferBinding @153-171
- function_definition BindBufferRange @173-231
- function_definition BufferData @235-245
- function_definition UninitializedBufferData_SizeOnly @247-257
- function_definition BufferSubData @261-271
- function_definition CreateBuffer @275-283

### dom/canvas/WebGLContextDraw.cpp

Blob: `11188f9cd56f080a792188d0046ef03e6d6b02e8`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include <memory> @6
- include "GLContext.h" @8
- include "MozFramebuffer.h" @9
- include "WebGLBuffer.h" @10
- include "WebGLContext.h" @11
- include "WebGLFormats.h" @12
- include "WebGLFramebuffer.h" @13
- include "WebGLProgram.h" @14
- include "WebGLRenderbuffer.h" @15
- include "WebGLShader.h" @16
- include "WebGLTexture.h" @17
- include "WebGLTransformFeedback.h" @18
- include "WebGLVertexArray.h" @19
- include "mozilla/CheckedInt.h" @20
- include "mozilla/ProfilerLabels.h" @21
- include "mozilla/ScopeExit.h" @22
- include "mozilla/StaticPrefs_webgl.h" @23
- include "nsPrintfCString.h" @24
- class_specifier ScopedResolveTexturesForDraw @33-45
- struct_specifier TexRebindRequest @34-37
- function_definition ValidateNoSamplingFeedback @47-73
- function_definition ScopedResolveTexturesForDraw @75-205
- struct_specifier SamplerByTexUnit @80-83
- function_definition ~ScopedResolveTexturesForDraw @207-218
- function_definition ValidateStencilParamsForDrawCall @222-256
- function_definition GenErrorIllegalUse @260-277
- function_definition ValidateBufferForNonTf @279-302
- function_definition ValidateBuffersForTf @304-329
- function_definition ValidateBuffersForTf @331-376
- function_definition FindFirstOne @381-388
- function_definition ValidateDraw @390-582
- function_definition UsedVertsForTFDraw @586-604
- class_specifier ScopedDrawWithTransformFeedback @606-665
- function_definition ScopedDrawWithTransformFeedback @613-651
- function_definition Advance @653-664
- function_definition HasInstancedDrawing @667-670
- function_definition DrawArraysInstanced @674-847
- function_definition DrawElements_check @851-928
- function_definition HandleDrawElementsErrors @930-947
- function_definition DrawElementsInstanced @949-1082
- function_definition Draw_cleanup @1086-1120
- function_definition WhatDoesVertexAttrib0Need @1122-1157
- function_definition DoFakeVertexAttrib0 @1159-1314

### dom/canvas/WebGLContextExtensions.cpp

Blob: `4ea3bf4a610bb5595203fd1a636c8057a312ec32`. Grammar: cpp. Status: contains-errors.

- include "ClientWebGLExtensions.h" @5
- include "GLContext.h" @6
- include "WebGLContext.h" @7
- include "WebGLExtensions.h" @8
- include "mozilla/EnumeratedRange.h" @9
- include "mozilla/StaticPrefs_webgl.h" @10
- include "mozilla/dom/BindingDeclarations.h" @11
- include "mozilla/dom/ToJSValue.h" @12
- include "nsString.h" @13
- function_definition GetExtensionName @17-72
- function_definition GetExtension @77-114
- function_definition GetExtension @116-245
- function_definition IsExtensionSupported @250-403
- function_definition IsExtensionExplicit @405-407
- function_definition WarnIfImplicit @409-417
- function_definition RequestExtension @419-596

### dom/canvas/WebGLContextFramebufferOperations.cpp

Blob: `2c4bc437eca9180ef76118c22cddc277c6083e6a`. Grammar: cpp. Status: syntax-clean.

- include "GLContext.h" @5
- include "GLScreenBuffer.h" @6
- include "WebGLContext.h" @7
- include "WebGLFormats.h" @8
- include "WebGLFramebuffer.h" @9
- include "WebGLRenderbuffer.h" @10
- include "WebGLTexture.h" @11
- function_definition Clear @15-59
- function_definition GLClampFloat @61-67
- function_definition ClearColor @69-106
- function_definition ClearDepth @108-114
- function_definition ClearStencil @116-122
- function_definition ColorMask @124-151
- function_definition DepthMask @153-159
- function_definition DrawBuffers @161-196
- function_definition StencilMaskSeparate @198-218

### dom/canvas/WebGLContextGL.cpp

Blob: `1ed0831953e9f39fb2c2e8380326e512e4dd28ae`. Grammar: cpp. Status: syntax-clean.

- include <fmt/format.h> @5
- include <algorithm> @7
- include "CanvasUtils.h" @9
- include "GLContext.h" @10
- include "MozFramebuffer.h" @11
- include "WebGL2Context.h" @12
- include "WebGLBuffer.h" @13
- include "WebGLContext.h" @14
- include "WebGLFormats.h" @15
- include "WebGLFramebuffer.h" @16
- include "WebGLProgram.h" @17
- include "WebGLQuery.h" @18
- include "WebGLRenderbuffer.h" @19
- include "WebGLShader.h" @20
- include "WebGLTexelConversions.h" @21
- include "WebGLTexture.h" @22
- include "WebGLValidateStrings.h" @23
- include "WebGLVertexArray.h" @24
- include "gfxContext.h" @25
- include "gfxPlatform.h" @26
- include "gfxUtils.h" @27
- include "jsfriendapi.h" @28
- include "mozilla/RefPtr.h" @29
- include "mozilla/StaticPrefs_webgl.h" @30
- include "mozilla/dom/BindingUtils.h" @31
- include "mozilla/dom/ImageData.h" @32
- include "mozilla/dom/WebGLRenderingContextBinding.h" @33
- include "nsContentUtils.h" @34
- include "nsDebug.h" @35
- include "nsError.h" @36
- include "nsLayoutUtils.h" @37
- include "nsReadableUtils.h" @38
- include "nsString.h" @39
- function_definition ActiveTexture @50-64
- function_definition AttachShader @66-74
- function_definition BindAttribLocation @76-82
- function_definition BindFramebuffer @84-114
- function_definition BlendEquationSeparate @116-140
- function_definition ValidateBlendFuncEnum @142-166
- function_definition ValidateBlendFuncEnums @168-191
- function_definition BlendFuncSeparate @193-221
- function_definition CheckFramebufferStatus @223-247
- function_definition CreateProgram @249-254
- function_definition CreateShader @256-266
- function_definition CullFace @268-275
- function_definition DetachShader @277-285
- function_definition ValidateComparisonEnum @287-303
- function_definition DepthFunc @305-312
- function_definition DepthRange @314-323
- function_definition FramebufferAttach @327-369
- function_definition FrontFace @373-386
- function_definition GetBufferParameter @388-412
- function_definition GetFramebufferAttachmentParameter @414-544
- function_definition GetRenderbufferParameter @546-576
- function_definition CreateTexture @578-586
- function_definition GetError @588-625
- function_definition GetUniform @627-699
- function_definition Hint @701-740
- function_definition LinkProgram @744-765
- function_definition SetPixelUnpack @767-850
- function_definition DoReadPixelsAndConvert @852-900
- function_definition ReadPixelsInto @902-914
- function_definition ReadPixelsPbo @916-963
- function_definition DefaultReadPixelPI @965-990
- function_definition ArePossiblePackEnums @992-1015
- function_definition ValidImplementationColorReadPI @1017-1052
- function_definition format_as @1054-1056
- function_definition ValidateReadPixelsFormatAndType @1058-1114
- function_definition ReadPixelsImpl @1116-1255
- function_definition RenderbufferStorageMultisample @1257-1266
- function_definition Scissor @1268-1279
- function_definition StencilFuncSeparate @1281-1308
- function_definition StencilOpSeparate @1310-1321
- function_definition UniformData @1326-1411
- function_definition UseProgram @1415-1433
- function_definition ValidateProgram @1435-1440
- function_definition CreateFramebuffer @1442-1450
- function_definition CreateOpaqueFramebuffer @1452-1468
- function_definition CreateRenderbuffer @1470-1475
- function_definition Viewport @1477-1496
- function_definition CompileShader @1498-1503
- function_definition ShaderSource @1505-1511
- function_definition BlendColor @1513-1518
- function_definition Flush @1520-1525
- function_definition Finish @1527-1535
- function_definition LineWidth @1537-1555
- function_definition PolygonOffset @1557-1562
- function_definition PolygonOffsetClampEXT @1564-1573
- function_definition ProvokingVertex @1575-1582
- function_definition SampleCoverage @1584-1589
- function_definition ClipControlEXT @1591-1606

### dom/canvas/WebGLContextLossHandler.cpp

Blob: `a8fdd670db60aad04437deedf598f8a81b7f66de`. Grammar: cpp. Status: syntax-clean.

- include "WebGLContextLossHandler.h" @5
- include "WebGLContext.h" @7
- include "base/message_loop.h" @8
- function_definition WebGLContextLossHandler @12-22
- function_definition ~WebGLContextLossHandler @24-24
- function_definition RunTimer @28-36
- function_definition ClearTimer @38-38

### dom/canvas/WebGLContextLossHandler.h

Blob: `21cf82f1ae0991ffdab03d0d2eb423239860071d`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Atomics.h" @8
- include "mozilla/RefPtr.h" @9
- include "mozilla/WeakPtr.h" @10
- include "nsThreadUtils.h" @11
- class_specifier WebGLContext @14-14
- class_specifier WebGLContextLossHandler @16-27

### dom/canvas/WebGLContextState.cpp

Blob: `e137847721a29f2ee01d3013a713f8dcfdacb3a1`. Grammar: cpp. Status: syntax-clean.

- include "GLContext.h" @5
- include "GLScreenBuffer.h" @6
- include "MozFramebuffer.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLContext.h" @9
- include "WebGLFormats.h" @10
- include "WebGLFramebuffer.h" @11
- include "WebGLProgram.h" @12
- include "WebGLRenderbuffer.h" @13
- include "WebGLShader.h" @14
- include "WebGLTexture.h" @15
- include "WebGLVertexArray.h" @16
- include "mozilla/Maybe.h" @17
- include "mozilla/Preferences.h" @18
- include "nsString.h" @19
- function_definition SetEnabled @23-78
- function_definition GetStencilBits @80-99
- function_definition GetParameter @101-449
- function_definition GetStateTrackingSlot @451-466

### dom/canvas/WebGLContextTextures.cpp

Blob: `5af70c40dfdaa7dc40b5b2abf5adb0837c1f3821`. Grammar: cpp. Status: syntax-clean.

- include "CanvasUtils.h" @5
- include "GLContext.h" @6
- include "WebGLBuffer.h" @7
- include "WebGLContext.h" @8
- include "WebGLExtensions.h" @9
- include "WebGLFramebuffer.h" @10
- include "WebGLProgram.h" @11
- include "WebGLRenderbuffer.h" @12
- include "WebGLShader.h" @13
- include "WebGLTexelConversions.h" @14
- include "WebGLTexture.h" @15
- include "WebGLValidateStrings.h" @16
- include "WebGLVertexArray.h" @17
- include "gfxContext.h" @18
- include "gfxPlatform.h" @19
- include "gfxUtils.h" @20
- include "jsfriendapi.h" @21
- include "mozilla/dom/BindingUtils.h" @22
- include "mozilla/dom/ImageData.h" @23
- include "nsContentUtils.h" @24
- include "nsDebug.h" @25
- include "nsError.h" @26
- include "nsLayoutUtils.h" @27
- include "nsReadableUtils.h" @28
- include "nsString.h" @29
- function_definition IsTexParamValid @34-49
- function_definition BindTexture @54-95
- function_definition GenerateMipmap @97-103
- function_definition GetTexParameter @105-115
- function_definition TexParameter_base @117-124
- function_definition GetActiveTex @129-157
- function_definition TexStorage @159-168
- function_definition TexImage @170-193
- function_definition CompressedTexImage @195-215
- function_definition CopyTexImage @217-231

### dom/canvas/WebGLContextUtils.cpp

Blob: `d0a9536c00b3a5df380c4d6072adcc2500ef4b0c`. Grammar: cpp. Status: contains-errors.

- include "GLContext.h" @5
- include "HostWebGLContext.h" @6
- include "WebGLBuffer.h" @7
- include "WebGLContext.h" @8
- include "WebGLExtensions.h" @9
- include "WebGLFramebuffer.h" @10
- include "WebGLProgram.h" @11
- include "WebGLTexture.h" @12
- include "WebGLVertexArray.h" @13
- include "js/Warnings.h" @14
- include "jsapi.h" @15
- include "mozilla/Preferences.h" @16
- include "mozilla/Sprintf.h" @17
- include "mozilla/dom/ScriptSettings.h" @18
- include "mozilla/gfx/Logging.h" @19
- include "nsPrintfCString.h" @20
- include "nsServiceManagerUtils.h" @21
- function_definition GetEnumName @26-358
- function_definition EnumName @361-369
- function_definition EnumString @371-379
- function_definition ErrorInvalidEnumArg @381-385
- function_definition ErrorInvalidEnumInfo @387-398
- function_definition IsCacheCorrect @402-410
- function_definition AssertUintParamCorrect @412-420
- function_definition AssertMaskedUintParamCorrect @422-435
- function_definition AssertUintParamCorrect @437-437
- function_definition AssertCachedBindings @440-472
- function_definition AssertCachedGlobalState @474-525

### dom/canvas/WebGLContextValidate.cpp

Blob: `e9e68eed87b2901dcc2c755c7e01c8bde2433f85`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include "CanvasUtils.h" @7
- include "GLContext.h" @8
- include "GLSLANG/ShaderLang.h" @9
- include "WebGLBuffer.h" @10
- include "WebGLContext.h" @11
- include "WebGLFormats.h" @12
- include "WebGLFramebuffer.h" @13
- include "WebGLProgram.h" @14
- include "WebGLRenderbuffer.h" @15
- include "WebGLSampler.h" @16
- include "WebGLShader.h" @17
- include "WebGLTexture.h" @18
- include "WebGLValidateStrings.h" @19
- include "WebGLVertexArray.h" @20
- include "gfxEnv.h" @21
- include "jsfriendapi.h" @22
- include "mozilla/Preferences.h" @23
- include "mozilla/StaticPrefs_webgl.h" @24
- include "nsPrintfCString.h" @25
- function_definition RestrictCap @74-81
- function_definition ValidateBlendEquationEnum @87-109
- function_definition ValidateBlendFuncEnumsCompatibility @111-132
- function_definition ValidateStencilOpEnum @134-150
- function_definition ValidateFaceEnum @152-163
- function_definition ValidateAttribArraySetter @165-175
- function_definition MakeLimits @179-261
- function_definition InitAndValidateGL @263-601
- function_definition ValidateFramebufferTarget @603-625

### dom/canvas/WebGLContextVertexArray.cpp

Blob: `6774a979bd8e2bbee9fa00426ae5c7b272d9972a`. Grammar: cpp. Status: syntax-clean.

- include "GLContext.h" @5
- include "WebGLBuffer.h" @6
- include "WebGLContext.h" @7
- include "WebGLVertexArray.h" @8
- function_definition BindVertexArray @12-29
- function_definition CreateVertexArray @31-36

### dom/canvas/WebGLContextVertices.cpp

Blob: `64553deaba68635a58116f2dd4b9fa1fa9d4019d`. Grammar: cpp. Status: syntax-clean.

- include <bit> @5
- include <limits> @6
- include "GLContext.h" @8
- include "WebGLBuffer.h" @9
- include "WebGLContext.h" @10
- include "WebGLFramebuffer.h" @11
- include "WebGLProgram.h" @12
- include "WebGLRenderbuffer.h" @13
- include "WebGLShader.h" @14
- include "WebGLTexture.h" @15
- include "WebGLTypes.h" @16
- include "WebGLVertexArray.h" @17
- include "mozilla/ResultVariant.h" @18
- function_definition ValidateAttribIndex @22-42
- function_definition VertexAttrib4T @46-81
- function_definition EnableVertexAttribArray @85-95
- function_definition DisableVertexAttribArray @97-109
- function_definition GetVertexAttrib @111-139
- function_definition CheckVertexAttribPointer @143-257
- function_definition DoVertexAttribPointer @259-270
- function_definition VertexAttribPointer @272-293
- function_definition VertexAttribDivisor @297-306

### dom/canvas/WebGLExtensions.cpp

Blob: `b288f665ddd42bb437411ba482ddb69f1a95fd86`. Grammar: cpp. Status: syntax-clean.

- include "WebGLExtensions.h" @5
- include "GLContext.h" @7
- include "WebGLContext.h" @8
- include "WebGLFormats.h" @9
- include "mozilla/Casting.h" @10
- include "mozilla/ScopeExit.h" @11
- include "mozilla/StaticPrefs_webgl.h" @12
- include "mozilla/dom/WebGLRenderingContextBinding.h" @13
- function_definition TestShaderCompile @17-49
- function_definition WebGLExtensionBlendMinMax @53-56
- function_definition IsSupported @58-62
- function_definition WebGLExtensionColorBufferFloat @66-72
- function_definition SetRenderable @74-91
- function_definition OnSetExplicit @93-95
- function_definition IsSupported @97-103
- function_definition WebGLExtensionColorBufferHalfFloat @107-113
- function_definition SetRenderable @115-135
- function_definition OnSetExplicit @137-139
- function_definition IsSupported @141-148
- function_definition WebGLExtensionCompressedTextureASTC @152-200
- function_definition IsSupported @202-207
- function_definition WebGLExtensionCompressedTextureBPTC @211-233
- function_definition IsSupported @235-238
- function_definition WebGLExtensionCompressedTextureES3 @242-284
- function_definition WebGLExtensionCompressedTextureETC1 @288-306
- function_definition WebGLExtensionCompressedTexturePVRTC @310-331
- function_definition WebGLExtensionCompressedTextureRGTC @335-357
- function_definition IsSupported @359-362
- function_definition WebGLExtensionCompressedTextureS3TC @366-387
- function_definition IsSupported @389-401
- function_definition WebGLExtensionCompressedTextureS3TC_SRGB @405-426
- function_definition IsSupported @428-439
- function_definition WebGLExtensionDepthClamp @443-446
- function_definition WebGLExtensionDepthTexture @450-474
- function_definition IsSupported @476-485
- function_definition WebGLExtensionDisjointTimerQuery @489-493
- function_definition IsSupported @495-504
- function_definition WebGLExtensionDrawBuffers @508-511
- function_definition IsSupported @513-539
- function_definition WebGLExtensionExplicitPresent @543-553
- function_definition IsSupported @555-558
- function_definition WebGLExtensionEXTColorBufferFloat @562-589
- function_definition IsSupported @592-597
- function_definition WebGLExtensionFBORenderMipmap @601-605
- function_definition IsSupported @607-615
- function_definition WebGLExtensionFloatBlend @619-622
- function_definition IsSupported @624-633
- function_definition WebGLExtensionFragDepth @637-640
- function_definition IsSupported @642-668
- function_definition WebGLExtensionPolygonOffsetClamp @672-676
- function_definition IsSupported @678-681
- function_definition WebGLExtensionClipControl @683-686
- function_definition IsSupported @688-690
- function_definition WebGLExtensionInstancedArrays @694-698
- function_definition IsSupported @700-706
- function_definition WebGLExtensionMultiview @710-713
- function_definition IsSupported @715-720
- function_definition WebGLExtensionShaderTextureLod @724-728
- function_definition IsSupported @730-755
- function_definition WebGLExtensionSRGB @759-795
- function_definition IsSupported @797-801
- function_definition WebGLExtensionTextureFloat @805-902
- function_definition IsSupported @904-915
- function_definition WebGLExtensionTextureFloatLinear @919-936
- function_definition WebGLExtensionTextureHalfFloat @940-1039
- function_definition IsSupported @1041-1055
- function_definition WebGLExtensionTextureHalfFloatLinear @1059-1071
- function_definition IsSupported @1075-1078
- function_definition WebGLExtensionTextureNorm16 @1080-1126

### dom/canvas/WebGLExtensions.h

Blob: `06695f4959909c74dde10b3f0c9cb8f3a13c3f2d`. Grammar: cpp. Status: syntax-clean.

- include "WebGLObjectModel.h" @8
- include "WebGLTypes.h" @9
- include "nsString.h" @10
- include "nsTArray.h" @11
- include "nsWrapperCache.h" @12
- class_specifier ErrorResult @15-15
- struct_specifier Nullable @19-19
- class_specifier Sequence @21-21
- struct_specifier FormatRenderableState @25-25
- class_specifier FormatUsageAuthority @26-26
- class_specifier WebGLContext @29-29
- class_specifier WebGLQuery @30-30
- class_specifier WebGLShader @31-31
- class_specifier WebGLTexture @32-32
- class_specifier WebGLVertexArray @33-33
- class_specifier WebGLExtensionBase @35-58
- function_definition WebGLExtensionBase @43-43
- function_definition ~WebGLExtensionBase @46-46
- function_definition OnSetExplicit @49-49
- function_definition SetExplicit @52-55
- function_definition IsExplicit @57-57
- class_specifier WebGLExtensionCompressedTextureASTC @62-66
- class_specifier WebGLExtensionCompressedTextureBPTC @68-72
- class_specifier WebGLExtensionCompressedTextureES3 @74-77
- class_specifier WebGLExtensionCompressedTextureETC1 @79-82
- class_specifier WebGLExtensionCompressedTexturePVRTC @84-87
- class_specifier WebGLExtensionCompressedTextureRGTC @89-93
- class_specifier WebGLExtensionCompressedTextureS3TC @95-99
- class_specifier WebGLExtensionCompressedTextureS3TC_SRGB @101-105
- class_specifier WebGLExtensionDebugRendererInfo @107-111
- function_definition WebGLExtensionDebugRendererInfo @109-110
- class_specifier WebGLExtensionDebugShaders @113-117
- function_definition WebGLExtensionDebugShaders @115-116
- class_specifier WebGLExtensionDepthClamp @119-122
- class_specifier WebGLExtensionDepthTexture @124-128
- class_specifier WebGLExtensionDrawBuffersIndexed @130-134
- function_definition WebGLExtensionDrawBuffersIndexed @132-133
- class_specifier WebGLExtensionElementIndexUint @136-140
- function_definition WebGLExtensionElementIndexUint @138-139
- class_specifier WebGLExtensionExplicitPresent @142-146
- class_specifier WebGLExtensionEXTColorBufferFloat @148-152
- class_specifier WebGLExtensionFBORenderMipmap @154-158
- class_specifier WebGLExtensionFloatBlend @160-164
- class_specifier WebGLExtensionFragDepth @166-170
- class_specifier WebGLExtensionLoseContext @172-176
- function_definition WebGLExtensionLoseContext @174-175
- class_specifier WebGLExtensionMultiview @178-182
- class_specifier WebGLExtensionProvokingVertex @184-188
- function_definition WebGLExtensionProvokingVertex @186-187
- class_specifier WebGLExtensionPolygonOffsetClamp @190-194
- class_specifier WebGLExtensionClipControl @196-200
- class_specifier WebGLExtensionSRGB @202-206
- class_specifier WebGLExtensionStandardDerivatives @208-212
- function_definition WebGLExtensionStandardDerivatives @210-211
- class_specifier WebGLExtensionShaderTextureLod @214-218
- class_specifier WebGLExtensionTextureFilterAnisotropic @220-224
- function_definition WebGLExtensionTextureFilterAnisotropic @222-223
- class_specifier WebGLExtensionTextureFloat @226-232
- class_specifier WebGLExtensionTextureFloatLinear @234-237
- class_specifier WebGLExtensionTextureHalfFloat @239-245
- class_specifier WebGLExtensionTextureHalfFloatLinear @247-250
- class_specifier WebGLExtensionTextureMirrorClampToEdge @252-256
- function_definition WebGLExtensionTextureMirrorClampToEdge @254-255
- class_specifier WebGLExtensionTextureNorm16 @258-262
- class_specifier WebGLExtensionColorBufferFloat @264-271
- class_specifier WebGLExtensionColorBufferHalfFloat @273-280
- class_specifier WebGLExtensionDrawBuffers @282-286
- class_specifier WebGLExtensionVertexArray @288-292
- function_definition WebGLExtensionVertexArray @290-291
- class_specifier WebGLExtensionInstancedArrays @294-298
- class_specifier WebGLExtensionBlendMinMax @300-304
- class_specifier WebGLExtensionDisjointTimerQuery @306-310
- class_specifier WebGLExtensionMOZDebug @312-316
- function_definition WebGLExtensionMOZDebug @314-315

### dom/canvas/WebGLFormats.cpp

Blob: `2911f5a5e2493b19b29027da249b2cca4530d825`. Grammar: cpp. Status: contains-errors.

- include "WebGLFormats.h" @5
- include "GLContext.h" @7
- include "GLDefs.h" @8
- include "mozilla/StaticMutex.h" @9
- include "mozilla/gfx/Logging.h" @10
- function_definition ToString @14-28
- function_definition ToBaseType @30-43
- function_definition ToString @45-55
- function_definition AlwaysInsert @60-65
- function_definition FindOrNull @68-73
- function_definition GetFormatInfo_NoLock @82-85
- function_definition MakeCompressedFormatInfo @89-99
- function_definition MakeFormatInfo @103-182
- function_definition AddFormatInfo @184-186
- function_definition InitFormatInfo @188-475
- function_definition EnsureInitFormatTables @481-491
- function_definition GetFormat @498-503
- function_definition GetCopyDecayFormat @507-512
- function_definition For @514-594
- function_definition IsUnpackValid @606-613
- function_definition ResolveMaxSamples @615-630
- function_definition AddSimpleUnsized @634-644
- function_definition AddLegacyFormats_LA8 @653-692
- function_definition AddUnsizedFormats @694-708
- function_definition SetRenderable @710-725
- function_definition CreateForWebGL1 @727-798
- function_definition CreateForWebGL2 @800-1033
- function_definition AddTexUnpack @1037-1052
- function_definition Contains @1054-1056
- function_definition IsInternalFormatEnumValid @1058-1061
- function_definition AreUnpackEnumsValid @1063-1067
- function_definition AllowRBFormat @1071-1084
- function_definition AllowSizedTexFormat @1086-1098
- function_definition AllowUnsizedTexFormat @1100-1111
- function_definition GetRBUsage @1113-1116
- function_definition GetSizedTexUsage @1118-1121
- function_definition GetUnsizedTexUsage @1123-1126
- function_definition EditUsage @1128-1145
- function_definition GetUsage @1147-1153

### dom/canvas/WebGLFormats.h

Blob: `2228852ce4b3110b439d138c83b7513588e24ed0`. Grammar: cpp. Status: syntax-clean.

- include <map> @8
- include <memory> @9
- include <set> @10
- include "WebGLTypes.h" @12
- enum_specifier EffectiveFormat @18-201
- enum_specifier UnsizedFormat @203-214
- enum_specifier ComponentType @217-223
- enum_specifier TextureBaseType @226-230
- enum_specifier CompressionFamily @234-242
- struct_specifier CompressedFormatInfo @246-252
- struct_specifier FormatInfo @254-283
- function_definition IsColorFormat @279-282
- struct_specifier PackingInfoInfo @287-297
- function_definition BytesPerPixel @294-296
- function_definition BytesPerPixel @301-309
- struct_specifier FormatRenderableState @317-339
- enum_specifier RenderableState @319-323
- function_definition Explicit @329-331
- function_definition Implicit @333-335
- function_definition IsRenderable @337-337
- function_definition IsExplicit @338-338
- struct_specifier FormatUsageInfo @341-395
- function_definition FormatUsageInfo @367-371
- function_definition IsRenderable @373-373
- function_definition IsExplicitlyRenderable @376-376
- function_definition GetExtensionID @377-380
- function_definition MaxSamples @389-394
- class_specifier FormatUsageAuthority @397-436
- function_definition FormatUsageAuthority @415-415

### dom/canvas/WebGLFramebuffer.cpp

Blob: `fb299ad7f53b28640bed1cbdb2b7997a103a2390`. Grammar: cpp. Status: syntax-clean.

- include "WebGLFramebuffer.h" @5
- include <algorithm> @8
- include "GLBlitHelper.h" @10
- include "GLContext.h" @11
- include "GLScreenBuffer.h" @12
- include "MozFramebuffer.h" @13
- include "WebGLContext.h" @14
- include "WebGLExtensions.h" @15
- include "WebGLFormats.h" @16
- include "WebGLRenderbuffer.h" @17
- include "WebGLTexture.h" @18
- include "mozilla/IntegerRange.h" @19
- include "mozilla/dom/WebGLRenderingContextBinding.h" @20
- include "nsPrintfCString.h" @21
- function_definition ShouldDeferAttachment @25-37
- function_definition WebGLFBAttachPoint @39-39
- function_definition WebGLFBAttachPoint @40-40
- function_definition WebGLFBAttachPoint @42-45
- function_definition ~WebGLFBAttachPoint @47-50
- function_definition Clear @52-52
- function_definition Set @54-66
- function_definition GetImageInfo @68-79
- function_definition IsComplete @81-208
- function_definition DoAttachment @210-262
- function_definition GetParameter @264-475
- function_definition WebGLFramebuffer @481-505
- function_definition WebGLFramebuffer @507-522
- function_definition ~WebGLFramebuffer @524-541
- function_definition GetColorAttachPoint @545-557
- function_definition GetAttachPoint @559-574
- function_definition DetachTexture @576-583
- function_definition DetachRenderbuffer @585-592
- function_definition HasDuplicateAttachments @597-610
- function_definition HasDefinedAttachments @612-618
- function_definition HasIncompleteAttachments @620-630
- function_definition AllImageRectsMatch @632-659
- function_definition AllImageSamplesMatch @661-685
- function_definition PrecheckFramebufferStatus @687-736
- function_definition ValidateAndInitAttachments @741-751
- function_definition ValidateClearBufferType @753-786
- function_definition ValidateForColorRead @788-819
- function_definition DoDeferredAttachments @824-844
- function_definition ResolveAttachmentData @846-972
- function_definition CompletenessInfo::~CompletenessInfo @974-985
- function_definition CheckFramebufferStatus @990-1075
- function_definition RefreshDrawBuffers @1079-1099
- function_definition RefreshReadBuffer @1101-1116
- function_definition DrawBuffers @1120-1170
- function_definition ReadBuffer @1172-1191
- function_definition FramebufferAttach @1195-1220
- function_definition GetAttachmentParameter @1222-1252
- function_definition GetBackbufferFormats @1256-1279
- function_definition BlitFramebuffer @1282-1706

### dom/canvas/WebGLFramebuffer.h

Blob: `516b9db7065679196708065f9cd8c60df84f56e5`. Grammar: cpp. Status: contains-errors.

- include <bitset> @8
- include <vector> @9
- include "GLScreenBuffer.h" @11
- include "WebGLObjectModel.h" @12
- include "WebGLStrongTypes.h" @13
- include "WebGLTexture.h" @14
- include "WebGLTypes.h" @15
- include "mozilla/WeakPtr.h" @16
- class_specifier WebGLFramebuffer @20-20
- class_specifier WebGLRenderbuffer @21-21
- class_specifier WebGLTexture @22-22
- class_specifier PlacementArray @25-25
- class_specifier GLContext @28-28
- class_specifier MozFramebuffer @29-29
- struct_specifier FbAttachInfo @33-40
- class_specifier WebGLFBAttachPoint @43-134
- function_definition HasAttachment @69-71
- function_definition Texture @77-77
- function_definition Renderbuffer @78-78
- function_definition ColorAttachmentId @80-84
- function_definition Layer @86-86
- function_definition ZLayerCount @87-87
- function_definition MipLevel @88-88
- function_definition (anonymous) @89-89
- function_definition IsEquivalentForFeedback @102-109
- struct_specifier Ordered @113-133
- function_definition Ordered @116-116
- function_definition operator< @118-132
- class_specifier WebGLFramebuffer @136-280
- struct_specifier CompletenessInfo @171-198
- function_definition CompletenessInfo @184-184
- function_definition CompletenessInfo @185-185
- function_definition CompletenessInfo @186-186
- function_definition CompletenessInfo @187-195
- function_definition (anonymous) @253-253
- function_definition (anonymous) @254-254
- function_definition GetCompletenessInfo @259-259
- function_definition IsCheckFramebufferStatusComplete @264-266

### dom/canvas/WebGLInternalFormatsTable.h

Blob: `46b88aeeabb378caa173d5c12fced53ae9737237`. Grammar: cpp. Status: contains-errors.


### dom/canvas/WebGLIpdl.h

Blob: `828873c513f5d2cbf94421af6566deeeca360ed0`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTypes.h" @8
- include "gfxTypes.h" @9
- include "ipc/EnumSerializer.h" @10
- include "ipc/IPCMessageUtils.h" @11
- include "mozilla/GfxMessageUtils.h" @12
- include "mozilla/dom/BindingIPCUtils.h" @13
- include "mozilla/ipc/Shmem.h" @14
- include "mozilla/layers/LayersSurfaces.h" @15
- class_specifier RaiiShmem @23-111
- function_definition Alloc @29-34
- function_definition AllocUnsafe @36-41
- function_definition RaiiShmem @45-45
- function_definition RaiiShmem @47-60
- function_definition reset @62-71
- function_definition ~RaiiShmem @73-73
- function_definition RaiiShmem @77-77
- function_definition (anonymous) @78-83
- function_definition IsShmem @87-87
- function_definition (anonymous) @89-89
- function_definition (anonymous) @93-96
- function_definition ByteRange @98-103
- function_definition Extract @105-110
- struct_specifier ParamTraits<mozilla::webgl::FrontBufferSnapshotIpc> @121-135
- function_definition Write @124-128
- function_definition Read @130-134
- struct_specifier ParamTraits<mozilla::webgl::ReadPixelsResultIpc> @140-154
- function_definition Write @143-147
- function_definition Read @149-153
- struct_specifier ParamTraits<mozilla::webgl::TexUnpackBlobDesc> @159-184
- function_definition Write @162-174
- function_definition Read @176-183
- struct_specifier ParamTraits<mozilla::webgl::Padded<U, PaddedSize>> @189-199
- function_definition Write @192-194
- function_definition Read @196-198
- struct_specifier ParamTraits<mozilla::webgl::AttribBaseType> @204-208
- struct_specifier ParamTraits<mozilla::webgl::ContextLossReason> @211-215
- struct_specifier ParamTraits<gfxAlphaType> @218-220
- struct_specifier ParamTraits<mozilla::dom::WebGLPowerPreference> @223-225
- struct_specifier ParamTraits<mozilla::dom::PredefinedColorSpace> @228-230
- struct_specifier ParamTraits<mozilla::webgl::OptionalRenderableFormatBits> @233-236
- struct_specifier ParamTraits<mozilla::webgl::InitContextDesc> @242-243
- struct_specifier ParamTraits<mozilla::WebGLContextOptions> @246-247
- struct_specifier ParamTraits<mozilla::webgl::OpaqueFramebufferOptions> @250-252
- struct_specifier ParamTraits<mozilla::webgl::ShaderPrecisionFormat> @255-256
- struct_specifier ParamTraits<mozilla::gl::GLVendor> @261-265
- struct_specifier ParamTraits<mozilla::webgl::EnumMask<U>> @268-269
- struct_specifier ParamTraits<mozilla::webgl::InitContextResult> @272-273
- struct_specifier ParamTraits<mozilla::webgl::Limits> @276-277
- struct_specifier ParamTraits<mozilla::webgl::PixelPackingState> @280-281
- struct_specifier ParamTraits<mozilla::webgl::PixelUnpackStateWebgl> @283-284
- struct_specifier ParamTraits<mozilla::avec2<U>> @343-344
- struct_specifier ParamTraits<mozilla::avec3<U>> @349-350

### dom/canvas/WebGLMemoryTracker.cpp

Blob: `5e5eed971fe0378f14ce3e1706b8ddad38cd4f0f`. Grammar: cpp. Status: contains-errors.

- include "WebGLMemoryTracker.h" @5
- include "HostWebGLContext.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLRenderbuffer.h" @9
- include "WebGLShader.h" @10
- include "WebGLTexture.h" @11
- function_definition EnsureRegistered @18-24
- function_definition CollectReports @26-148

### dom/canvas/WebGLMemoryTracker.h

Blob: `bcaa186ff373afd21c7e6a4580fb5677aa647ce1`. Grammar: cpp. Status: contains-errors.

- include "nsIMemoryReporter.h" @8
- class_specifier WebGLMemoryTracker @12-21
- function_definition ~WebGLMemoryTracker @20-20

### dom/canvas/WebGLMethodDispatcher.h

Blob: `f4683baedd93bdd1e57b561bca68e8e5b60fda67`. Grammar: cpp. Status: contains-errors.

- include "HostWebGLContext.h" @8
- include "TexUnpackBlob.h" @9
- include "WebGLQueueParamTraits.h" @10
- class_specifier WebGLMethodDispatcher @15-16

### dom/canvas/WebGLObjectModel.h

Blob: `c02dd8dd0cda00401530dc79f4e98dceeb893a3d`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTypes.h" @8
- include "mozilla/WeakPtr.h" @9
- class_specifier WebGLContext @13-13
- class_specifier WebGLContextBoundObject @20-28
- class_specifier WebGLRectangleObject @34-69
- function_definition WebGLRectangleObject @36-36
- function_definition WebGLRectangleObject @38-39
- function_definition Width @41-41
- function_definition width @42-42
- function_definition Height @44-44
- function_definition height @45-45
- function_definition setDimensions @47-50
- function_definition setDimensions @52-60
- function_definition HasSameDimensionsAs @62-64

### dom/canvas/WebGLParent.cpp

Blob: `712e9d5ad1014fe86b6688fff91990f33c1ee5c9`. Grammar: cpp. Status: syntax-clean.

- include "WebGLParent.h" @5
- include "HostWebGLContext.h" @7
- include "ImageContainer.h" @8
- include "WebGLChild.h" @9
- include "WebGLMethodDispatcher.h" @10
- include "mozilla/layers/SharedSurfacesParent.h" @11
- include "mozilla/layers/TextureClientSharedSurface.h" @12
- function_definition RecvInitialize @16-25
- function_definition WebGLParent @27-29
- function_definition ~WebGLParent @31-31
- function_definition RecvDispatchCommands @37-96
- function_definition RecvTexImage @98-109
- function_definition Recv__delete__ @113-116
- function_definition ActorDestroy @118-118
- function_definition RecvWaitForTxn @120-127
- function_definition RecvGetFrontBufferSnapshot @131-134
- function_definition GetFrontBufferSnapshot @136-173
- function_definition RecvGetBufferSubData @175-201
- function_definition RecvReadPixels @203-233
- function_definition RecvReadPixelsAsync @235-266
- function_definition RecvCheckFramebufferStatus @270-278
- function_definition RecvClientWaitSync @280-288
- function_definition RecvCreateOpaqueFramebuffer @290-299
- function_definition RecvDrawingBufferSize @301-308
- function_definition RecvFinish @310-317
- function_definition RecvGetBufferParameter @319-327
- function_definition RecvGetCompileResult @329-337
- function_definition RecvGetError @339-346
- function_definition RecvGetFragDataLocation @348-357
- function_definition RecvGetFramebufferAttachmentParameter @359-367
- function_definition RecvGetFrontBuffer @369-377
- function_definition RecvGetIndexedParameter @379-387
- function_definition RecvGetInternalformatParameter @389-398
- function_definition RecvGetLinkResult @400-408
- function_definition RecvGetNumber @410-417
- function_definition RecvGetQueryParameter @419-427
- function_definition RecvGetRenderbufferParameter @429-437
- function_definition RecvGetSamplerParameter @439-447
- function_definition RecvGetString @449-457
- function_definition RecvGetTexParameter @459-467
- function_definition RecvGetUniform @469-477
- function_definition RecvGetVertexAttrib @479-487
- function_definition RecvOnMemoryPressure @489-496
- function_definition RecvValidateProgram @498-505

### dom/canvas/WebGLParent.h

Blob: `16c786ef211261c6c96be816a48e1d48e0bb2617`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/GfxMessageUtils.h" @8
- include "mozilla/WeakPtr.h" @9
- include "mozilla/dom/PWebGLParent.h" @10
- include "mozilla/dom/ipc/IdType.h" @11
- class_specifier HostWebGLContext @15-15
- class_specifier WebGLChild @16-16
- class_specifier SharedSurfacesHolder @19-19
- class_specifier SharedSurfaceTextureClient @20-20
- class_specifier SurfaceDescriptor @21-21
- class_specifier WebGLParent @26-131
- function_definition RecvPing @41-44
- function_definition RecvSyncPing @46-46
- function_definition GetHostWebGLContext @114-114

### dom/canvas/WebGLProgram.cpp

Blob: `39a20304195b204fb8d51aea1e3139b265735e31`. Grammar: cpp. Status: syntax-clean.

- include "WebGLProgram.h" @5
- include "GLContext.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLContext.h" @9
- include "WebGLFormats.h" @10
- include "WebGLShader.h" @11
- include "WebGLShaderValidator.h" @12
- include "WebGLTransformFeedback.h" @13
- include "WebGLValidateStrings.h" @14
- include "WebGLVertexArray.h" @15
- include "mozilla/CheckedInt.h" @16
- include "mozilla/RefPtr.h" @17
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @18
- include "mozilla/dom/WebGLRenderingContextBinding.h" @19
- include "mozilla/gfx/Logging.h" @20
- include "nsPrintfCString.h" @21
- function_definition IsShadowSampler @25-34
- function_definition SamplerBaseType @36-62
- function_definition FragOutputBaseType @66-94
- function_definition UniformAs1fv @100-103
- function_definition UniformAs2fv @104-107
- function_definition UniformAs3fv @108-111
- function_definition UniformAs4fv @112-115
- function_definition UniformAs1iv @117-120
- function_definition UniformAs2iv @121-124
- function_definition UniformAs3iv @125-128
- function_definition UniformAs4iv @129-132
- function_definition UniformAs1uiv @134-137
- function_definition UniformAs2uiv @138-141
- function_definition UniformAs3uiv @142-145
- function_definition UniformAs4uiv @146-149
- function_definition UniformAsMatrix2x2fv @151-155
- function_definition UniformAsMatrix2x3fv @156-160
- function_definition UniformAsMatrix2x4fv @161-165
- function_definition UniformAsMatrix3x2fv @167-171
- function_definition UniformAsMatrix3x3fv @172-176
- function_definition UniformAsMatrix3x4fv @177-181
- function_definition UniformAsMatrix4x2fv @183-187
- function_definition UniformAsMatrix4x3fv @188-192
- function_definition UniformAsMatrix4x4fv @193-197
- function_definition EndsWith @201-205
- function_definition ActiveUniformValidationInfo::Make @207-329
- function_definition QueryProgramInfo @337-519
- function_definition LinkedProgramInfo::LinkedProgramInfo @523-526
- function_definition LinkedProgramInfo::~LinkedProgramInfo @528-528
- function_definition ToAttribBaseType @530-584
- function_definition ToString @586-598
- function_definition ToString @600-610
- function_definition LinkedProgramInfo::GetDrawFetchLimits @614-706
- function_definition WebGLProgram @711-715
- function_definition ~WebGLProgram @717-725
- function_definition AttachShader @730-745
- function_definition BindAttribLocation @747-775
- function_definition DetachShader @777-794
- function_definition UniformBlockBinding @796-825
- function_definition ValidateForLink @827-871
- function_definition LinkProgram @873-955
- function_definition NumUsedLocationsByElemType @957-979
- function_definition ElemTypeComponents @981-1044
- function_definition ValidateAfterTentativeLink @1046-1135
- function_definition UseProgram @1137-1154
- function_definition ValidateProgram @1156-1174
- function_definition LinkAndUpdate @1178-1204
- function_definition TransformFeedbackVaryings @1206-1238

### dom/canvas/WebGLProgram.h

Blob: `51126fa240511893d9bed98cab3770f1bac5fe68`. Grammar: cpp. Status: contains-errors.

- include <bitset> @8
- include <map> @9
- include <memory> @10
- include <vector> @11
- include "CacheInvalidator.h" @13
- include "WebGLObjectModel.h" @14
- include "WebGLTypes.h" @15
- include "mozilla/RefPtr.h" @16
- include "mozilla/Vector.h" @17
- include "mozilla/WeakPtr.h" @18
- class_specifier ErrorResult @21-21
- class_specifier WebGLContext @22-22
- class_specifier WebGLProgram @23-23
- class_specifier WebGLShader @24-24
- struct_specifier Nullable @28-28
- class_specifier OwningUnsignedLongOrUint32ArrayOrBoolean @29-29
- class_specifier Sequence @31-31
- enum_specifier TextureBaseType @36-36
- struct_specifier UniformBlockInfo @38-41
- struct_specifier FragOutputInfo @43-48
- struct_specifier CachedDrawFetchLimits @50-60
- function_definition CachedDrawFetchLimits @55-55
- function_definition CachedDrawFetchLimits @56-56
- function_definition CachedDrawFetchLimits @57-57
- function_definition (anonymous) @59-59
- struct_specifier ActiveUniformValidationInfo @67-74
- struct_specifier SamplerUniformInfo @76-82
- struct_specifier LocationInfo @84-98
- function_definition PrettyName @89-97
- struct_specifier LinkedProgramInfo @102-145
- class_specifier WebGLProgram @149-209
- function_definition IsLinked @176-176
- function_definition LinkInfo @178-180
- function_definition (anonymous) @182-182
- function_definition (anonymous) @183-183
- function_definition (anonymous) @185-185

### dom/canvas/WebGLQuery.cpp

Blob: `3f4206a7181004dc0a0a8b5081a02f53651ba5ca`. Grammar: cpp. Status: syntax-clean.

- include "WebGLQuery.h" @5
- include "GLContext.h" @7
- include "WebGLContext.h" @8
- include "mozilla/StaticPrefs_webgl.h" @9
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @10
- include "nsContentUtils.h" @11
- function_definition GenQuery @17-21
- function_definition WebGLQuery @23-27
- function_definition ~WebGLQuery @29-32
- function_definition TargetForDriver @36-52
- function_definition BeginQuery @54-65
- function_definition EndQuery @67-78
- function_definition GetQueryParameter @80-140
- function_definition QueryCounter @142-154

### dom/canvas/WebGLQuery.h

Blob: `b1fc299831c601dab19490b8dc1ab03b12321720`. Grammar: cpp. Status: contains-errors.

- include "WebGLObjectModel.h" @8
- include "nsThreadUtils.h" @9
- class_specifier AvailabilityRunnable @13-13
- class_specifier WebGLQuery @16-49
- function_definition Target @32-32
- function_definition IsActive @33-33

### dom/canvas/WebGLQueueParamTraits.h

Blob: `b92a6779ecb46a2368fedbf438ba53737d5c99d0`. Grammar: cpp. Status: contains-errors.

- include "QueueParamTraits.h" @8
- include "TexUnpackBlob.h" @9
- include "WebGLTypes.h" @10
- include "ipc/EnumSerializer.h" @11
- struct_specifier QueueParamTraits @16-16
- function_definition TiedFields @40-42
- struct_specifier QueueParamTraits<avec2<T>> @53-53
- struct_specifier QueueParamTraits<avec3<T>> @56-56
- struct_specifier QueueParamTraits<AttribBaseType> @62-64
- struct_specifier ProvokingVertexValidator @66-77
- function_definition IsLegalValue @69-76
- struct_specifier QueueParamTraits<ProvokingVertex> @80-81
- struct_specifier QueueParamTraits<Span<T>> @87-116
- function_definition Write @89-98
- function_definition Read @101-115
- struct_specifier QueueParamTraits<webgl::ContextLossReason> @119-122
- struct_specifier QueueParamTraits<Result<V, E>> @125-157
- function_definition Write @129-139
- function_definition Read @142-156
- struct_specifier QueueParamTraits<std::string> @160-184
- function_definition Write @164-171
- function_definition Read @174-183
- struct_specifier QueueParamTraits<std::vector<U>> @187-215
- function_definition Write @191-200
- function_definition Read @203-214
- struct_specifier QueueParamTraits<WebGLExtensionID> @218-221
- struct_specifier QueueParamTraits<CompileResult> @224-242
- function_definition Write @228-233
- function_definition Read @236-241
- struct_specifier QueueParamTraits<mozilla::layers::TextureType> @245-248
- struct_specifier QueueParamTraits<mozilla::gfx::SurfaceFormat> @251-254
- struct_specifier QueueParamTraits<gfxAlphaType> @257-259
- struct_specifier QueueParamTraits<dom::WebGLPowerPreference> @269-270
- struct_specifier QueueParamTraits<dom::PredefinedColorSpace> @272-273

### dom/canvas/WebGLRenderbuffer.cpp

Blob: `3f7d3e9ef874998cd64e3a2d1f748766c633375e`. Grammar: cpp. Status: syntax-clean.

- include "WebGLRenderbuffer.h" @5
- include "GLContext.h" @7
- include "ScopedGLHelpers.h" @8
- include "WebGLContext.h" @9
- include "WebGLFormats.h" @10
- include "WebGLStrongTypes.h" @11
- include "WebGLTexture.h" @12
- include "mozilla/dom/WebGLRenderingContextBinding.h" @13
- function_definition DepthFormatForDepthStencilEmu @17-23
- function_definition DoCreateRenderbuffer @25-29
- function_definition EmulatePackedDepthStencil @31-33
- function_definition WebGLRenderbuffer @35-45
- function_definition ~WebGLRenderbuffer @47-56
- function_definition DoRenderbufferStorageMaybeMultisample @58-105
- function_definition DoRenderbufferStorage @107-144
- function_definition Truncate @146-149
- function_definition RenderbufferStorage @151-192
- function_definition DoFramebufferRenderbuffer @194-211
- function_definition GetRenderbufferParameter @213-254

### dom/canvas/WebGLRenderbuffer.h

Blob: `63110bc0bc82416a4dd023c5a3d14dfd8fd6aa62`. Grammar: cpp. Status: contains-errors.

- include "CacheInvalidator.h" @8
- include "WebGLObjectModel.h" @9
- include "WebGLStrongTypes.h" @10
- include "WebGLTexture.h" @11
- struct_specifier FormatUsageInfo @15-15
- class_specifier WebGLRenderbuffer @18-55
- function_definition (anonymous) @37-37
- function_definition MemoryUsage @44-44

### dom/canvas/WebGLSampler.cpp

Blob: `b5f7ca762614fa39073346b89df87626e83f5167`. Grammar: cpp. Status: syntax-clean.

- include "WebGLSampler.h" @5
- include "GLContext.h" @7
- include "WebGLContext.h" @8
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @9
- function_definition WebGLSampler @13-18
- function_definition ~WebGLSampler @20-23
- function_definition ValidateSamplerParameterParams @25-129
- function_definition SamplerParameter @131-172

### dom/canvas/WebGLSampler.h

Blob: `cd69b1ea14bd1684f8772e19fcd31369297e8aa8`. Grammar: cpp. Status: contains-errors.

- include "WebGLObjectModel.h" @8
- include "WebGLStrongTypes.h" @9
- include "WebGLTexture.h" @10
- class_specifier WebGLSampler @14-33
- function_definition (anonymous) @32-32

### dom/canvas/WebGLShader.cpp

Blob: `2969307257181915e675a4d1b23a40282b619e48`. Grammar: cpp. Status: syntax-clean.

- include "WebGLShader.h" @5
- include "GLContext.h" @7
- include "GLSLANG/ShaderLang.h" @8
- include "WebGLContext.h" @9
- include "WebGLObjectModel.h" @10
- include "WebGLShaderValidator.h" @11
- include "WebGLValidateStrings.h" @12
- include "mozilla/MemoryReporting.h" @13
- include "mozilla/dom/WebGLRenderingContextBinding.h" @14
- include "nsPrintfCString.h" @15
- include "nsString.h" @16
- include "prenv.h" @17
- function_definition PrintLongString @21-37
- function_definition GetCompilationStatusAndLog @39-56
- function_definition WebGLShader @60-65
- function_definition ~WebGLShader @67-70
- function_definition ShaderSource @72-74
- function_definition CompileShader @76-119
- function_definition CalcNumSamplerUniforms @123-132
- function_definition NumAttributes @134-136
- function_definition BindAttribLocation @138-146
- function_definition MapTransformFeedbackVaryings @148-169
- function_definition SizeOfIncludingThis @174-178

### dom/canvas/WebGLShader.h

Blob: `2fbffc4442274b679c8849643341b445b6060d08`. Grammar: cpp. Status: contains-errors.

- include <memory> @8
- include <string> @9
- include <vector> @10
- include "GLDefs.h" @12
- include "WebGLObjectModel.h" @13
- include "mozilla/MemoryReporting.h" @14
- class_specifier ShaderValidatorResults @19-19
- class_specifier WebGLShader @22-69
- function_definition (anonymous) @43-43
- function_definition (anonymous) @44-44
- function_definition IsCompiled @45-45

### dom/canvas/WebGLShaderValidator.cpp

Blob: `dca28d797ca1dd44b0eec5b7747739051e62c5b0`. Grammar: cpp. Status: syntax-clean.

- include "WebGLShaderValidator.h" @5
- include <algorithm> @7
- include <string> @8
- include <vector> @9
- include "GLContext.h" @11
- include "MurmurHash3.h" @12
- include "WebGLContext.h" @13
- include "mozilla/Preferences.h" @14
- include "mozilla/StaticPrefs_webgl.h" @15
- include "mozilla/gfx/Logging.h" @16
- include "nsPrintfCString.h" @17
- function_definition IdentifierHashFunc @22-28
- function_definition ChooseValidatorCompileOptions @30-81
- function_definition ShaderOutput @87-117
- function_definition CreateShaderValidator @119-254
- function_definition Create @261-271
- function_definition ~ShaderValidator @273-273
- function_definition StartsWith @275-278
- function_definition Split @280-295
- function_definition ValidateAndTranslate @297-360
- function_definition CanLinkTo @362-514
- function_definition SizeOfIncludingThis @516-544

### dom/canvas/WebGLShaderValidator.h

Blob: `1f16b1042ebf1759056be5cecc1aae85faca9546`. Grammar: cpp. Status: syntax-clean.

- include <memory> @8
- include <string> @9
- include <unordered_map> @10
- include "GLDefs.h" @12
- include "GLSLANG/ShaderLang.h" @13
- include "nsString.h" @14
- class_specifier ShaderValidatorResults @18-42
- class_specifier ShaderValidator @44-71
- function_definition ShaderValidator @60-64

### dom/canvas/WebGLStrongTypes.h

Blob: `9aabec9db9abcd00f68c02d57015464d0563362e`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @8
- include <array> @9
- include "GLDefs.h" @11
- include "mozilla/Assertions.h" @12
- include "mozilla/Attributes.h" @13
- class_specifier StrongGLenum @101-162
- function_definition AssertOnceThatEnumValuesAreSorted @107-119
- function_definition StrongGLenum @122-124
- function_definition StrongGLenum @126-129
- function_definition get @131-134
- function_definition operator== @136-138
- function_definition operator!= @140-142
- function_definition operator<= @144-146
- function_definition operator>= @148-150
- function_definition (anonymous) @152-152
- function_definition IsValueLegal @154-161
- function_definition operator== @165-167
- function_definition operator!= @170-172
- function_definition operator== @175-177
- function_definition operator!= @180-182

### dom/canvas/WebGLSync.cpp

Blob: `2827d4cd43f8767f981843a40d38de672c3fd30c`. Grammar: cpp. Status: syntax-clean.

- include "WebGLSync.h" @5
- include "GLContext.h" @7
- include "WebGLContext.h" @8
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @9
- function_definition WebGLSync @13-18
- function_definition ~WebGLSync @20-24
- function_definition ClientWaitSync @26-60

### dom/canvas/WebGLSync.h

Blob: `158f4651cba712ee758e861475b6ec8208d96a8c`. Grammar: cpp. Status: contains-errors.

- include "WebGLObjectModel.h" @8
- class_specifier AvailabilityRunnable @12-12
- struct_specifier Task @14-17
- function_definition ~Task @15-15
- struct_specifier FnTask @20-26
- function_definition FnTask @23-23
- function_definition operator() @25-25
- enum_specifier ClientWaitSyncResult @29-34
- class_specifier WebGLSync @36-65
- function_definition OnCompleteTaskAdd @55-59
- function_definition IsKnownComplete @61-61

### dom/canvas/WebGLTexelConversions.cpp

Blob: `3166f5b321b1047fb8ff57f9feab2e6565f363f9`. Grammar: cpp. Status: contains-errors.

- include "WebGLTexelConversions.h" @5
- include "GLBlitHelper.h" @7
- include "WebGLContext.h" @8
- class_specifier WebGLImageConverter @28-435
- function_definition NumElementsPerTexelForFormat @42-79
- function_definition run @93-260
- function_definition run @265-280
- function_definition run @284-300
- function_definition run @303-323
- function_definition run @326-372
- function_definition run @375-421
- function_definition WebGLImageConverter @423-432
- function_definition Success @434-434
- function_definition ConvertImage @439-511

### dom/canvas/WebGLTexelConversions.h

Blob: `efbe8397ac87f59a4e2bccaff7c9194d39ab4380`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @35
- include "WebGLTypes.h" @37
- include "mozilla/Attributes.h" @38
- include "mozilla/Casting.h" @39
- enum_specifier OriginPos @44-44
- function_definition packToFloat16 @70-108
- function_definition unpackFromFloat16 @110-161
- function_definition packToFloat11 @166-223
- function_definition packToFloat10 @225-282
- function_definition unpackFromFloat11 @284-298
- function_definition unpackFromFloat10 @300-314
- enum_specifier WebGLTexelPremultiplicationOp @316-320
- struct_specifier IsFloatFormat @325-331
- struct_specifier IsHalfFloatFormat @334-339
- struct_specifier Is16bppFormat @342-346
- struct_specifier DataTypeForFormat @351-353
- struct_specifier DataTypeForFormat<Format, true, false, false> @356-358
- struct_specifier DataTypeForFormat<Format, false, true, false> @361-363
- struct_specifier DataTypeForFormat<Format, false, false, true> @366-368
- struct_specifier DataTypeForFormat<WebGLTexelFormat::RGB11F11F10F, true, false, false> @371-373
- struct_specifier IntermediateFormat @376-381
- function_definition TexelBytesForFormat @383-422
- function_definition HasAlpha @424-434
- function_definition HasColor @436-454
- function_definition unpack @465-472
- function_definition unpack @477-483
- function_definition unpack @486-492
- function_definition unpack @495-501
- function_definition unpack @504-510
- function_definition unpack @513-519
- function_definition unpack @522-528
- function_definition unpack @533-539
- function_definition unpack @542-548
- function_definition unpack @551-557
- function_definition unpack @560-566
- function_definition unpack @569-575
- function_definition unpack @578-584
- function_definition unpack @589-599
- function_definition unpack @602-608
- function_definition unpack @611-617
- function_definition unpack @620-626
- function_definition unpack @629-636
- function_definition unpack @641-652
- function_definition unpack @655-665
- function_definition unpack @668-674
- function_definition unpack @677-683
- function_definition unpack @686-692
- function_definition unpack @697-703
- function_definition unpack @706-712
- function_definition unpack @715-721
- function_definition pack @730-733
- function_definition pack @738-742
- function_definition pack @745-749
- function_definition pack @752-756
- function_definition pack @759-763
- function_definition pack @766-771
- function_definition pack @774-779
- function_definition pack @782-786
- function_definition pack @789-793
- function_definition pack @796-800
- function_definition pack @803-807
- function_definition pack @810-816
- function_definition pack @819-825
- function_definition pack @828-832
- function_definition pack @835-841
- function_definition pack @844-851
- function_definition pack @854-858
- function_definition pack @861-866
- function_definition pack @869-874
- function_definition pack @879-884
- function_definition pack @887-894
- function_definition pack @898-905
- function_definition pack @908-913
- function_definition pack @916-923
- function_definition pack @926-934
- function_definition pack @937-942
- function_definition pack @945-951
- function_definition pack @954-960
- function_definition pack @963-968
- function_definition pack @971-979
- function_definition pack @983-991
- function_definition pack @994-999
- function_definition pack @1002-1009
- function_definition pack @1012-1020
- function_definition pack @1023-1028
- function_definition pack @1031-1037
- function_definition pack @1040-1046
- function_definition pack @1051-1056
- function_definition pack @1059-1069
- function_definition pack @1073-1083
- function_definition pack @1086-1092
- function_definition pack @1095-1105
- function_definition pack @1108-1118
- function_definition pack @1121-1126
- function_definition pack @1129-1136
- function_definition pack @1139-1147
- function_definition pack @1150-1156
- function_definition pack @1159-1167
- function_definition pack @1170-1179
- function_definition pack @1182-1188
- function_definition pack @1191-1198
- function_definition pack @1201-1208
- function_definition pack @1213-1218
- function_definition pack @1221-1231
- function_definition pack @1235-1245
- function_definition pack @1248-1253
- function_definition pack @1256-1266
- function_definition pack @1270-1280
- function_definition pack @1283-1290
- function_definition pack @1293-1304
- function_definition pack @1308-1319
- function_definition pack @1322-1329
- function_definition pack @1332-1343
- function_definition pack @1347-1358
- function_definition pack @1361-1368
- function_definition pack @1371-1380
- function_definition pack @1383-1393
- function_definition pack @1396-1403
- function_definition pack @1406-1414
- function_definition pack @1417-1425
- function_definition convertType @1430-1438
- function_definition convertType @1441-1447
- function_definition convertType @1450-1456
- function_definition convertType @1459-1465
- function_definition convertType @1468-1475
- function_definition convertType @1478-1485
- function_definition convertType @1488-1494
- function_definition convertType @1497-1503
- function_definition convertType @1506-1513

### dom/canvas/WebGLTexture.cpp

Blob: `f9001d3d56f18545d2536ad613f63bfe371ca186`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTexture.h" @5
- include <algorithm> @7
- include <bit> @8
- include "GLContext.h" @10
- include "ScopedGLHelpers.h" @11
- include "WebGLContext.h" @12
- include "WebGLFormats.h" @13
- include "WebGLFramebuffer.h" @14
- include "WebGLSampler.h" @15
- include "WebGLTexelConversions.h" @16
- include "mozilla/IntegerRange.h" @17
- include "mozilla/MathAlgorithms.h" @18
- include "mozilla/ScopeExit.h" @19
- include "mozilla/dom/WebGLRenderingContextBinding.h" @20
- include "mozilla/gfx/Logging.h" @21
- function_definition MemoryUsage @28-39
- function_definition NextMip @41-65
- function_definition WebGLTexture @71-79
- function_definition ~WebGLTexture @81-89
- function_definition MemoryUsage @91-97
- function_definition PopulateMipChain @101-123
- function_definition IsMipAndCubeComplete @129-178
- function_definition CalcCompletenessInfo @180-262
- function_definition CalcSampleableInfo @264-394
- function_definition GetSampleableInfo @396-411
- function_definition Es3_q @415-430
- function_definition SetSwizzle @434-448
- function_definition RefreshSwizzle @450-460
- function_definition EnsureImageDataInitialized @462-474
- function_definition ClearDepthTexture @476-536
- function_definition ZeroTextureData @538-661
- function_definition ClampLevelBaseAndMax @663-688
- function_definition BindTexture @693-724
- function_definition ClampMipmapLevelForDriver @726-729
- function_definition GenerateMipmap @731-843
- function_definition GetTexParameter @845-887
- function_definition TexParameter @892-1104
- function_definition Truncate @1106-1111

### dom/canvas/WebGLTexture.h

Blob: `c33915e767b0e9c3362b25901ed2f7cfc54b4718`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @8
- include <vector> @9
- include "CacheInvalidator.h" @11
- include "WebGLObjectModel.h" @12
- include "WebGLStrongTypes.h" @13
- include "WebGLTypes.h" @14
- include "mozilla/Assertions.h" @15
- include "mozilla/dom/TypedArray.h" @16
- class_specifier ErrorResult @19-19
- class_specifier WebGLContext @20-20
- class_specifier WebGLFramebuffer @21-21
- class_specifier WebGLSampler @22-22
- struct_specifier FloatOrInt @23-23
- struct_specifier TexImageSource @24-24
- class_specifier Element @27-27
- class_specifier HTMLVideoElement @28-28
- class_specifier ImageData @29-29
- class_specifier ArrayBufferViewOrSharedArrayBufferView @30-30
- class_specifier Image @34-34
- struct_specifier DriverUnpackInfo @38-38
- struct_specifier FormatUsageInfo @39-39
- struct_specifier PackingInfo @40-40
- class_specifier TexUnpackBlob @41-41
- struct_specifier SamplingState @49-60
- struct_specifier ImageInfo @62-86
- function_definition IsDefined @76-83
- class_specifier WebGLTexture @90-314
- enum_specifier MipmapLevelState @119-123
- struct_specifier CompletenessInfo @134-140
- function_definition (anonymous) @155-155
- function_definition (anonymous) @156-156
- function_definition Es3_level_base @159-165
- function_definition Es3_level_max @166-173
- function_definition (anonymous) @180-180
- function_definition Target @194-194
- function_definition SizeOfExcludingThis @200-203
- function_definition SizeOfIncludingThis @204-206
- function_definition FaceForTarget @261-276
- function_definition (anonymous) @279-284
- function_definition (anonymous) @286-288
- function_definition (anonymous) @290-293
- function_definition (anonymous) @295-297
- function_definition (anonymous) @299-303
- function_definition IsCubeMap @313-313
- function_definition TexImageTargetForTargetAndFace @316-329

### dom/canvas/WebGLTextureUpload.cpp

Blob: `a00bc4407b12ef68108c992902d8d4b053caed23`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTextureUpload.h" @5
- include <algorithm> @7
- include <bit> @8
- include "CanvasUtils.h" @10
- include "ClientWebGLContext.h" @11
- include "GLBlitHelper.h" @12
- include "GLContext.h" @13
- include "ScopedGLHelpers.h" @14
- include "TexUnpackBlob.h" @15
- include "WebGLBuffer.h" @16
- include "WebGLContext.h" @17
- include "WebGLFormats.h" @18
- include "WebGLFramebuffer.h" @19
- include "WebGLTexelConversions.h" @20
- include "WebGLTexture.h" @21
- include "mozilla/MathAlgorithms.h" @22
- include "mozilla/ScopeExit.h" @23
- include "mozilla/StaticPrefs_webgl.h" @24
- include "mozilla/dom/HTMLCanvasElement.h" @25
- include "mozilla/dom/HTMLVideoElement.h" @26
- include "mozilla/dom/ImageBitmap.h" @27
- include "mozilla/dom/ImageData.h" @28
- include "mozilla/dom/OffscreenCanvas.h" @29
- include "mozilla/gfx/2D.h" @30
- include "mozilla/gfx/Logging.h" @31
- include "mozilla/layers/SharedSurfacesChild.h" @32
- include "nsLayoutUtils.h" @33
- function_definition FromImageBitmap @47-88
- function_definition FromOffscreenCanvas @90-105
- function_definition FromVideoFrame @107-114
- function_definition FromDomElem @116-140
- function_definition FromSurfaceFromElementResult @142-241
- function_definition ValidateTexImage @248-260
- function_definition ValidateTexImageSpecification @263-363
- function_definition ValidateTexImageSelection @366-395
- function_definition ValidateCompressedTexUnpack @397-429
- function_definition DoChannelsMatchForCopyTexImage @431-484
- class_specifier UploadInitMemTracker @490-587
- enum_specifier UploadMem @495-504
- function_definition UploadInitState @506-520
- function_definition UploadInitMemTracker @523-527
- function_definition EnsureImageDataZeroedBeforePartialUpload @530-551
- function_definition ExpectsFullUpload @555-555
- function_definition ClearSliceUninitAfterFullUpload @559-586
- function_definition DoTexStorage @593-617
- function_definition IsTarget3D @619-637
- function_definition DoTexImage @639-656
- function_definition DoTexSubImage @658-675
- function_definition DoCompressedTexImage @677-696
- function_definition DoCompressedTexSubImage @698-717
- function_definition DoCopyTexSubImage @719-735
- function_definition ValidateCompressedTexImageRestrictions @741-793
- function_definition ValidateFormatAndSize @795-853
- function_definition TexStorage @855-963
- function_definition TexImage @969-1161
- function_definition IsSubImageBlockAligned @1166-1184
- function_definition CompressedTexImage @1187-1385
- function_definition ValidateCopyTexImageFormats @1390-1416
- class_specifier ScopedCopyTexImageSource @1420-1431
- function_definition ScopedCopyTexImageSource @1433-1556
- function_definition ToGLHandle @1559-1561
- function_definition ~ScopedCopyTexImageSource @1563-1581
- function_definition GetUnsizedFormatForCopy @1585-1615
- function_definition ValidateCopyDestUsage @1617-1691
- function_definition ValidateCopyTexImageForFeedback @1693-1717
- function_definition DoCopyTexOrSubImage @1719-1845
- function_definition CopyTexImage @1848-1946

### dom/canvas/WebGLTextureUpload.h

Blob: `37fdc622e8887dfe96bc65cfd4b41fcb0fc90d7d`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTypes.h" @8
- struct_specifier SurfaceFromElementResult @11-11
- class_specifier Element @14-14
- class_specifier OffscreenCanvas @15-15

### dom/canvas/WebGLTransformFeedback.cpp

Blob: `1c3712e984fce080a735822f62e64c2ef9cc0f90`. Grammar: cpp. Status: syntax-clean.

- include "WebGLTransformFeedback.h" @5
- include "GLContext.h" @7
- include "WebGL2Context.h" @8
- include "WebGLBuffer.h" @9
- include "WebGLProgram.h" @10
- include "mozilla/IntegerRange.h" @11
- include "mozilla/dom/WebGL2RenderingContextBinding.h" @12
- function_definition WebGLTransformFeedback @16-21
- function_definition ~WebGLTransformFeedback @23-28
- function_definition PrepareTransformFeedback @34-88
- function_definition BeginTransformFeedback @90-126
- function_definition EndTransformFeedback @128-156
- function_definition PauseTransformFeedback @158-172
- function_definition ResumeTransformFeedback @174-197

### dom/canvas/WebGLTransformFeedback.h

Blob: `593513589c595b8ebef8f074e6d4e56de7c4d8f0`. Grammar: cpp. Status: contains-errors.

- include "WebGLObjectModel.h" @8
- include "WebGLTypes.h" @9
- struct_specifier CachedDrawFetchLimits @13-13
- class_specifier WebGLTransformFeedback @16-59
- function_definition IsActiveAndNotPaused @52-52

### dom/canvas/WebGLTypes.h

Blob: `9b3ac0a44e2adcae51be7637cae13fa86b1dd5dd`. Grammar: cpp. Status: contains-errors.

- include <limits> @8
- include <string> @9
- include <string_view> @10
- include <tuple> @11
- include <type_traits> @12
- include <unordered_map> @13
- include <vector> @14
- include "GLContextTypes.h" @16
- include "GLDefs.h" @17
- include "ImageContainer.h" @18
- include "gfxTypes.h" @19
- include "mozilla/Casting.h" @20
- include "mozilla/CheckedInt.h" @21
- include "mozilla/DefineEnum.h" @22
- include "mozilla/Range.h" @23
- include "mozilla/RefCounted.h" @24
- include "mozilla/Result.h" @25
- include "mozilla/ResultVariant.h" @26
- include "mozilla/Span.h" @27
- include "mozilla/TiedFields.h" @28
- include "mozilla/TypedEnumBits.h" @29
- include "mozilla/WeakPtr.h" @30
- include "mozilla/dom/WebGLRenderingContextBinding.h" @31
- include "mozilla/gfx/2D.h" @32
- include "mozilla/gfx/BuildConstants.h" @33
- include "mozilla/gfx/Logging.h" @34
- include "mozilla/gfx/Point.h" @35
- include "mozilla/gfx/Rect.h" @36
- include "mozilla/ipc/Shmem.h" @37
- include "mozilla/layers/LayersSurfaces.h" @38
- include "nsString.h" @39
- include "nsTArray.h" @40
- class_specifier GLContext @52-52
- class_specifier ForbidNarrowing @60-75
- function_definition mVal @65-72
- function_definition (anonymous) @74-74
- function_definition malloc @77-79
- function_definition calloc @81-84
- function_definition AutoAssertCast @90-92
- struct_specifier QueueParamTraits @99-99
- class_specifier TexUnpackBytes @100-100
- class_specifier TexUnpackSurface @101-101
- class_specifier ClientWebGLContext @104-104
- class_specifier WebGLTexture @105-105
- class_specifier WebGLBuffer @106-106
- class_specifier WebGLFramebuffer @107-107
- class_specifier WebGLProgram @108-108
- class_specifier WebGLQuery @109-109
- class_specifier WebGLRenderbuffer @110-110
- class_specifier WebGLSampler @111-111
- class_specifier WebGLShader @112-112
- class_specifier WebGLSync @113-113
- class_specifier WebGLTexture @114-114
- class_specifier WebGLTransformFeedback @115-115
- class_specifier WebGLVertexArray @116-116
- class_specifier VRefCounted @120-128
- function_definition ~VRefCounted @122-122
- enum_specifier WebGLVertexAttrib0Status @138-144
- enum_specifier WebGLTexelFormat @154-194
- enum_specifier WebGLTexImageFunc @196-203
- enum_specifier WebGLTexDimensions @205-205
- enum_specifier WebGLExtensionID @208-252
- class_specifier UniqueBuffer @254-291
- function_definition Take @259-263
- function_definition UniqueBuffer @265-265
- function_definition ~UniqueBuffer @267-267
- function_definition UniqueBuffer @269-269
- function_definition (anonymous) @271-276
- function_definition (anonymous) @278-278
- function_definition get @280-280
- function_definition reset @282-290
- struct_specifier FormatUsageInfo @294-294
- struct_specifier SampleableInfo @298-305
- function_definition IsComplete @304-304
- enum_specifier UniformBaseType @315-319
- enum_specifier BufferKind @324-328
- struct_specifier FloatOrInt @334-346
- function_definition FloatOrInt @341-341
- function_definition FloatOrInt @343-343
- function_definition MutTiedFields @345-345
- struct_specifier WebGLContextOptions @350-397
- function_definition MutTiedFields @367-385
- function_definition WebGLContextOptions @390-390
- function_definition operator== @393-395
- function_definition operator!= @396-396
- function_definition ToColorSpace2 @401-409
- struct_specifier avec2 @416-467
- function_definition MutTiedFields @422-422
- function_definition From @425-430
- function_definition From @433-435
- function_definition FromSize @437-439
- function_definition avec2 @441-441
- function_definition avec2 @442-442
- function_definition operator== @444-444
- function_definition (anonymous) @452-461
- function_definition StaticCast @464-466
- function_definition MinExtents @470-472
- function_definition MaxExtents @475-477
- struct_specifier avec3 @482-509
- function_definition MutTiedFields @489-489
- function_definition From @492-498
- function_definition From @501-503
- function_definition avec3 @505-505
- function_definition avec3 @506-506
- function_definition operator== @508-508
- function_definition AsVec @516-516
- struct_specifier PackingInfo @522-545
- function_definition MutTiedFields @526-526
- function_definition operator< @529-531
- function_definition operator== @532-534
- function_definition operator!= @535-537
- function_definition (anonymous) @540-544
- struct_specifier DriverUnpackInfo @548-568
- function_definition ToPacking @555-555
- function_definition Fields @558-560
- function_definition operator== @562-564
- function_definition operator!= @565-567
- class_specifier EnumMask @573-605
- struct_specifier BitRef @578-592
- function_definition (anonymous) @582-582
- function_definition (anonymous) @584-591
- function_definition Mask @594-596
- function_definition operator[] @599-599
- function_definition operator[] @600-600
- function_definition MutTiedFields @604-604
- enum_specifier ContextLossReason @611-615
- struct_specifier InitContextDesc @619-631
- function_definition MutTiedFields @627-630
- struct_specifier Limits @638-676
- function_definition MutTiedFields @664-675
- struct_specifier PaddedBase @681-687
- struct_specifier PaddedBase<T, 0> @690-693
- struct_specifier Padded @697-711
- function_definition (anonymous) @701-701
- function_definition (anonymous) @702-702
- function_definition (anonymous) @704-704
- function_definition (anonymous) @705-705
- function_definition (anonymous) @707-707
- function_definition (anonymous) @708-708
- function_definition operator-> @709-709
- function_definition operator-> @710-710
- enum_specifier OptionalRenderableFormatBits @715-718
- struct_specifier TupleStdHash @729-738
- function_definition operator() @730-737
- struct_specifier ShaderPrecisionFormat @740-751
- function_definition MutTiedFields @748-750
- struct_specifier InitContextResult @755-773
- function_definition MutTiedFields @769-772
- struct_specifier ErrorInfo @777-780
- enum_specifier LossStatus @784-790
- struct_specifier CompileResult @794-799
- struct_specifier OpaqueFramebufferOptions @803-813
- function_definition MutTiedFields @810-812
- struct_specifier SwapChainOptions @817-830
- function_definition MutTiedFields @826-829
- struct_specifier ActiveInfo @834-838
- struct_specifier ActiveAttribInfo @840-843
- struct_specifier ActiveUniformInfo @845-853
- struct_specifier ActiveUniformBlockInfo @855-862
- struct_specifier LinkActiveInfo @864-869
- struct_specifier LinkResult @871-880
- function_definition LinkResult @872-872
- function_definition ~LinkResult @873-873
- struct_specifier TypedQuad @885-891
- function_definition MutTiedFields @890-890
- struct_specifier GetUniformData @894-897
- struct_specifier FrontBufferSnapshotIpc @899-903
- struct_specifier ReadPixelsResult @905-908
- struct_specifier ReadPixelsResultIpc @910-912
- struct_specifier VertAttribPointerDesc @914-926
- function_definition MutTiedFields @922-925
- struct_specifier VertAttribPointerCalculated @928-932
- function_definition ShmemRange @937-939
- function_definition MaybeFind @944-949
- function_definition Find @952-958
- function_definition MaybeAs @963-967
- function_definition IsTexMipmapFilter @971-980
- function_definition IsTexImageTarget @982-996
- function_definition ImageToTexTarget @998-1012
- function_definition IsTexTarget3D @1014-1023
- class_specifier Element @1028-1028
- class_specifier ImageBitmap @1029-1029
- class_specifier ImageData @1030-1030
- class_specifier OffscreenCanvas @1031-1031
- class_specifier VideoFrame @1032-1032
- struct_specifier TexImageSource @1035-1051
- struct_specifier DeriveNotEq @1056-1061
- function_definition operator!= @1057-1060
- struct_specifier PixelPackingState @1063-1088
- function_definition MutTiedFields @1071-1074
- function_definition operator== @1077-1079
- function_definition AssertDefaultUnpack @1081-1083
- struct_specifier PixelUnpackStateWebgl @1090-1103
- function_definition MutTiedFields @1098-1102
- struct_specifier ExplicitPixelPackingState @1105-1132
- struct_specifier Metrics @1106-1123
- struct_specifier ReadPixelsDesc @1134-1141
- function_definition MutTiedFields @1140-1140
- struct_specifier TexUnpackBlobDesc @1147-1174
- function_definition ExplicitUnpacking @1166-1171
- function_definition MakeRange @1182-1184
- function_definition MakeRange @1187-1189
- function_definition AlignmentOffset @1196-1202
- function_definition ByteSize @1205-1207
- function_definition ToString @1227-1229
- function_definition Memcpy @1231-1239
- function_definition Memcpy @1242-1245
- function_definition Memcpy @1247-1250
- function_definition Memcpy @1253-1257
- function_definition StartsWith @1261-1264
- enum_specifier ProvokingVertex @1282-1285
- struct_specifier BufferAndIndex @1289-1292
- struct_specifier IndexedBufferBinding @1296-1305
- function_definition PrintfStdString @1310-1314
- function_definition ToChars @1316-1319
- struct_specifier ReinterpretToSpan @1322-1328
- function_definition From @1324-1327
- function_definition Join @1332-1351
- function_definition ToStringWithCommas @1353-1362
- function_definition to_array_impl @1370-1373
- function_definition to_array_impl @1376-1379
- function_definition to_array @1383-1385
- function_definition to_array @1388-1390

### dom/canvas/WebGLValidateStrings.cpp

Blob: `1d2a0bcbcd91552df880409619a5b10bd0bbccd8`. Grammar: cpp. Status: syntax-clean.

- include "WebGLValidateStrings.h" @5
- include <regex> @7
- include "WebGLTypes.h" @9
- include "nsPrintfCString.h" @10
- function_definition CommentsToSpaces @28-85
- function_definition IsValidGLSLChar @89-132
- function_definition IsValidForPreprocOrGlsl @134-143
- function_definition CrushGlslToAscii @149-158
- function_definition CheckGLSLVariableName @160-188

### dom/canvas/WebGLValidateStrings.h

Blob: `51dce5d857ff18e7d251e805569982a2c1d7ef14`. Grammar: cpp. Status: syntax-clean.

- include <string> @30
- include "WebGLTypes.h" @32
- include "mozilla/Maybe.h" @33

### dom/canvas/WebGLVertexArray.cpp

Blob: `58d7af9313a9ac2c11e7af02244d645e04627eb9`. Grammar: cpp. Status: syntax-clean.

- include "WebGLVertexArray.h" @5
- include "GLContext.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLContext.h" @9
- include "WebGLVertexArrayFake.h" @10
- include "WebGLVertexArrayGL.h" @11
- include "mozilla/dom/WebGLRenderingContextBinding.h" @12
- function_definition Create @16-21
- function_definition WebGLVertexArray @23-30
- function_definition ~WebGLVertexArray @32-32
- function_definition GetVertexAttrib @34-67
- function_definition AttribPointer @69-84

### dom/canvas/WebGLVertexArray.h

Blob: `ce4594915ff7a35941e3172559dc66618686240d`. Grammar: cpp. Status: contains-errors.

- include <array> @8
- include <bitset> @9
- include "CacheInvalidator.h" @11
- include "WebGLObjectModel.h" @12
- include "WebGLStrongTypes.h" @13
- include "mozilla/IntegerRange.h" @14
- class_specifier WebGLBuffer @18-18
- class_specifier WebGLVertexArrayFake @19-19
- struct_specifier LinkedProgramInfo @22-22
- struct_specifier VertAttribLayoutData @24-32
- struct_specifier VertAttribBindingData @34-37
- class_specifier WebGLVertexArray @44-110
- function_definition SetAttribIsArray @74-79
- function_definition AttribDivisor @81-84
- function_definition (anonymous) @90-92
- function_definition (anonymous) @93-95
- function_definition GetAttribIsArrayWithNullBuffer @97-106

### dom/canvas/WebGLVertexArrayFake.cpp

Blob: `6347253db0763df3e23f1e3214d49f2e486e6f99`. Grammar: cpp. Status: syntax-clean.

- include "WebGLVertexArrayFake.h" @5
- include "GLContext.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLContext.h" @9
- function_definition BindBuffer @13-16
- function_definition WebGLVertexArrayFake @18-19
- function_definition DoVertexAttrib @21-52
- function_definition BindVertexArray @54-69

### dom/canvas/WebGLVertexArrayFake.h

Blob: `cf07de01ee9e76e2a2103c5ce71138e5a378f20f`. Grammar: cpp. Status: syntax-clean.

- include "WebGLVertexArray.h" @8
- class_specifier WebGLVertexArrayFake @12-18
- function_definition ~WebGLVertexArrayFake @15-15

### dom/canvas/WebGLVertexArrayGL.cpp

Blob: `a9a14577481c25705763dd8deb4dd66f4c0129c0`. Grammar: cpp. Status: syntax-clean.

- include "WebGLVertexArrayGL.h" @5
- include "GLContext.h" @7
- include "WebGLBuffer.h" @8
- include "WebGLContext.h" @9
- function_definition WebGLVertexArrayGL @13-18
- function_definition ~WebGLVertexArrayGL @20-23
- function_definition BindVertexArray @25-28

### dom/canvas/WebGLVertexArrayGL.h

Blob: `083e99b3e58d1dd2c4c1310e9ecf365f9478e7e7`. Grammar: cpp. Status: syntax-clean.

- include "WebGLVertexArray.h" @8
- class_specifier WebGLVertexArrayGL @12-20

### dom/canvas/XRWebGLLayer.cpp

Blob: `5fa6362aeaff3bc5114f96974597e150d4101c95`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/XRWebGLLayer.h" @5
- include "ClientWebGLContext.h" @7
- include "GLContext.h" @8
- include "MozFramebuffer.h" @9
- include "ScopedGLHelpers.h" @10
- include "VRDisplayClient.h" @11
- include "WebGLFramebuffer.h" @12
- include "mozilla/StaticPrefs_dom.h" @13
- include "mozilla/StaticPrefs_webgl.h" @14
- include "mozilla/dom/WebGLRenderingContextBinding.h" @15
- include "mozilla/dom/XRSession.h" @16
- include "mozilla/dom/XRView.h" @17
- include "mozilla/dom/XRViewport.h" @18
- include "nsContentUtils.h" @19
- include "nsIScriptError.h" @20
- function_definition XRWebGLLayer @32-45
- function_definition ~XRWebGLLayer @47-47
- function_definition DeleteFramebuffer @49-54
- function_definition Constructor @57-161
- function_definition WrapObject @163-166
- function_definition GetParentObject @168-168
- function_definition Antialias @170-175
- function_definition Depth @177-182
- function_definition Stencil @184-189
- function_definition Alpha @191-197
- function_definition IgnoreDepthValues @199-199
- function_definition GetFramebuffer @201-203
- function_definition FramebufferWidth @205-210
- function_definition FramebufferHeight @212-217
- function_definition GetViewport @219-235
- function_definition GetNativeFramebufferScaleFactor @238-250
- function_definition StartAnimationFrame @252-256
- function_definition EndAnimationFrame @258-262
- function_definition GetCanvas @264-264
- function_definition SessionEnded @266-266

### dom/canvas/XRWebGLLayer.h

Blob: `26ca91a7e56acec0ef7932d44642d0c4219e179e`. Grammar: cpp. Status: contains-errors.

- include "WebGLTypes.h" @8
- include "gfxVR.h" @9
- include "mozilla/DOMEventTargetHelper.h" @10
- include "mozilla/dom/WebXRBinding.h" @11
- include "mozilla/dom/XRSession.h" @12
- include "nsICanvasRenderingContextInternal.h" @13
- class_specifier WebGLFramebufferJS @16-16
- class_specifier ClientWebGLContext @17-17
- class_specifier XRSession @19-19
- class_specifier XRView @20-20
- class_specifier XRViewport @21-21
- class_specifier WebGLRenderingContextOrWebGL2RenderingContext @22-22
- struct_specifier XRWebGLLayerInit @23-23
- class_specifier XRWebGLLayer @24-81

### dom/canvas/gtest/TestOffscreenCanvas.cpp

Blob: `99e1056df3e6e8ce4c2ba7eee2a9a44d7b7a1c59`. Grammar: cpp. Status: syntax-clean.

- include "OffscreenCanvasDisplayHelper.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/dom/CanvasRenderingContextHelper.h" @7
- include "mozilla/dom/WorkerRef.h" @8
- function_definition TEST @15-34

### dom/canvas/gtest/TestSanitizeRenderer.cpp

Blob: `e10bcb8eb560d867457589e301d4583614dd3efc`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @5
- function_definition TEST @11-18
- function_definition TEST @20-28
- function_definition TEST @30-37
- function_definition TEST @39-46
- function_definition TEST @48-54
- function_definition TEST @56-62
- function_definition TEST @64-71
- function_definition TEST @73-80
- function_definition TEST @82-88
- function_definition TEST @89-95
- function_definition TEST @97-103
- function_definition TEST @105-111
- function_definition TEST @113-119
- function_definition TEST @123-132
- function_definition TEST @134-144
- function_definition TEST @146-156
- function_definition TEST @158-168
- function_definition TEST @170-176
- function_definition TEST @178-188
- function_definition TEST @190-197
- function_definition TEST @199-206
- function_definition TEST @208-217
- function_definition TEST @219-225
- function_definition TEST @227-233
- function_definition TEST @235-241
- function_definition TEST @243-249
- function_definition TEST @251-257
- function_definition TEST @259-269
- function_definition TEST @270-276
- function_definition TEST @283-289
- function_definition TEST @291-297
- function_definition TEST @299-305
- function_definition TEST @307-313
- function_definition TEST @315-325

### dom/canvas/gtest/TestWebGLTextureUploadInit.cpp

Blob: `8de2fcee7ffeafca0acb9cf0c5d676af62c90d0a`. Grammar: cpp. Status: contains-errors.

- include <vector> @5
- include "WebGLContext.h" @7
- include "WebGLTexture.h" @8
- include "WebGLTypes.h" @9
- include "gfxPlatform.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gfx/2D.h" @12
- function_definition DXT5ByteCount @28-33
- class_specifier UnmappableSourceSurface @38-53
- function_definition UnmappableSourceSurface @42-42
- function_definition GetSize @44-44
- function_definition GetFormat @45-47
- function_definition GetData @48-48
- function_definition Stride @49-49
- class_specifier WebGLTextureUploadInit @62-148
- function_definition SetUp @67-83
- function_definition ExpectNoError @85-87
- function_definition ExpectError @89-91
- function_definition EnableS3TC @93-100
- function_definition BindAndAllocUninitialized @102-109
- function_definition BindAndAllocUninitializedCompressed @113-116
- function_definition TexSubImageFromBytes @118-129
- function_definition TexSubImageFromUnmappableSurface @131-140
- function_definition CompressedSubImageFromBytes @142-147
- function_definition TEST_F @150-172
- function_definition TEST_F @174-189
- function_definition TEST_F @191-207
- function_definition TEST_F @209-227
- function_definition TEST_F @229-254
- function_definition TEST_F @256-273
- function_definition TEST_F @275-292
- function_definition TEST_F @294-311
- function_definition TEST_F @313-333
- function_definition TEST_F @335-355

### dom/canvas/nsICanvasRenderingContextInternal.cpp

Blob: `0d9af09793e3a197c10ca8531313bd1460f5ed96`. Grammar: cpp. Status: contains-errors.

- include "nsICanvasRenderingContextInternal.h" @5
- include "mozilla/ErrorResult.h" @7
- include "mozilla/PresShell.h" @8
- include "mozilla/dom/CanvasUtils.h" @9
- include "mozilla/dom/Document.h" @10
- include "mozilla/dom/Event.h" @11
- include "mozilla/dom/WorkerCommon.h" @12
- include "mozilla/dom/WorkerPrivate.h" @13
- include "mozilla/dom/WorkerRunnable.h" @14
- include "mozilla/gfx/DrawTargetRecording.h" @15
- include "nsContentUtils.h" @16
- include "nsPIDOMWindow.h" @17
- include "nsRFPService.h" @18
- include "nsRefreshDriver.h" @19
- include "nsThreadUtils.h" @20
- function_definition nsICanvasRenderingContextInternal @25-26
- function_definition ~nsICanvasRenderingContextInternal @28-29
- function_definition GetPresShell @31-36
- function_definition GetParentObject @38-49
- class_specifier RecordCanvasUsageRunnable @51-91
- function_definition RecordCanvasUsageRunnable @54-61
- function_definition MainThreadRun @64-87
- function_definition RecordCanvasUsage @93-132
- function_definition PrincipalOrNull @134-145
- function_definition GetCookieJarSettings @147-174
- function_definition RemovePostRefreshObserver @176-181
- function_definition AddPostRefreshObserverIfNecessary @183-190
- function_definition DoSecurityCheck @192-201
- function_definition ShouldResistFingerprinting @203-213
- function_definition DispatchEvent @215-237
- function_definition GetOptimizedSnapshot @239-261

### dom/canvas/nsICanvasRenderingContextInternal.h

Blob: `6e066b1c21593c03a95ed0997f6298d55d674708`. Grammar: cpp. Status: contains-errors.

- include "gfxRect.h" @8
- include "mozilla/EventForwards.h" @9
- include "mozilla/Maybe.h" @10
- include "mozilla/NotNull.h" @11
- include "mozilla/RefPtr.h" @12
- include "mozilla/StateWatching.h" @13
- include "mozilla/UniquePtr.h" @14
- include "mozilla/WeakPtr.h" @15
- include "mozilla/dom/HTMLCanvasElement.h" @16
- include "mozilla/dom/OffscreenCanvas.h" @17
- include "mozilla/gfx/2D.h" @18
- include "mozilla/layers/LayersSurfaces.h" @19
- include "nsIDocShell.h" @20
- include "nsIInputStream.h" @21
- include "nsISupports.h" @22
- include "nsRefreshObservers.h" @23
- class_specifier nsICookieJarSettings @28-28
- class_specifier nsIDocShell @29-29
- class_specifier nsIPrincipal @30-30
- class_specifier nsRefreshDriver @31-31
- class_specifier nsDisplayListBuilder @34-34
- class_specifier ClientWebGLContext @35-35
- class_specifier PresShell @36-36
- class_specifier WebGLFramebufferJS @37-37
- class_specifier IProtocol @39-39
- class_specifier CanvasRenderer @42-42
- class_specifier CompositableForwarder @43-43
- class_specifier FwdTransactionTracker @44-44
- class_specifier Layer @45-45
- class_specifier Image @46-46
- class_specifier LayerManager @47-47
- class_specifier LayerTransactionChild @48-48
- class_specifier PersistentBufferProvider @49-49
- class_specifier WebRenderCanvasData @50-50
- class_specifier DrawTarget @53-53
- class_specifier SourceSurface @54-54
- enum_specifier FrameCaptureState @58-58
- class_specifier nsICanvasRenderingContextInternal @60-250
- function_definition SetCanvasElement @73-77
- function_definition SetOffscreenCanvas @91-93
- function_definition Initialize @104-104
- function_definition SupportsSnapshotExternalCanvas @142-144
- function_definition SyncSnapshot @146-146
- function_definition GetFrontBufferSnapshot @148-150
- function_definition SupportAsyncSnapshot @152-152
- function_definition GetSurfaceSnapshotAsync @154-157
- function_definition GetAsImage @174-176
- function_definition UpdateWebRenderCanvasData @178-182
- function_definition InitializeCanvasRenderer @184-187
- function_definition SetContextOptions @202-205
- function_definition OnMemoryPressure @207-207
- function_definition OnBeforePaintTransaction @209-209
- function_definition OnDidPaintTransaction @210-210
- function_definition OnWindowDestroy @212-212
- function_definition GetBufferProvider @214-216
- function_definition GetFrontBuffer @218-221
- function_definition PresentFrontBuffer @223-226
- function_definition UseCompositableForwarder @228-231

### dom/clients/api/Client.cpp

Blob: `830071b8fb8771b9f8ad6915223f451ca7e066aa`. Grammar: cpp. Status: contains-errors.

- include "Client.h" @5
- include "ClientDOMUtil.h" @7
- include "mozilla/dom/ClientHandle.h" @8
- include "mozilla/dom/ClientIPCTypes.h" @9
- include "mozilla/dom/ClientManager.h" @10
- include "mozilla/dom/ClientState.h" @11
- include "mozilla/dom/DOMMozPromiseRequestHolder.h" @12
- include "mozilla/dom/MessagePortBinding.h" @13
- include "mozilla/dom/Promise.h" @14
- include "mozilla/dom/WorkerScope.h" @15
- include "nsIDUtils.h" @16
- include "nsIGlobalObject.h" @17
- function_definition EnsureHandle @30-38
- function_definition Client @40-43
- function_definition CreationTime @45-45
- function_definition LastFocusTime @47-52
- function_definition GetStorageAccess @54-57
- function_definition WrapObject @59-65
- function_definition GetParentObject @67-67
- function_definition GetUrl @69-71
- function_definition GetId @73-75
- function_definition Type @77-77
- function_definition GetFrameType @79-79
- function_definition PostMessage @81-105
- function_definition PostMessage @107-111
- function_definition GetVisibilityState @113-115
- function_definition Focused @117-119
- function_definition Focus @121-165
- function_definition Navigate @167-202

### dom/clients/api/Client.h

Blob: `fea814d79d720640e23abf8aca1ad3e8f1622b6b`. Grammar: cpp. Status: contains-errors.

- include "X11UndefineNone.h" @7
- include "mozilla/StorageAccess.h" @8
- include "mozilla/dom/ClientBinding.h" @9
- include "nsCOMPtr.h" @10
- include "nsContentUtils.h" @11
- include "nsISupports.h" @12
- include "nsWrapperCache.h" @13
- class_specifier nsIGlobalObject @15-15
- class_specifier ErrorResult @19-19
- class_specifier ClientHandle @23-23
- class_specifier ClientInfoAndState @24-24
- class_specifier Promise @25-25
- class_specifier Sequence @27-27
- struct_specifier StructuredSerializeOptions @28-28
- class_specifier Client @30-82
- function_definition ~Client @35-35

### dom/clients/api/ClientDOMUtil.h

Blob: `5f5b1cad220933e6db2fae71a3fec3dafe87f8c4`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/dom/ClientIPCTypes.h" @7
- include "mozilla/dom/ClientOpPromise.h" @8
- include "mozilla/dom/DOMMozPromiseRequestHolder.h" @9
- include "mozilla/dom/WorkerPrivate.h" @10
- class_specifier nsIGlobalObject @12-12
- function_definition StartClientManagerOp @20-42

### dom/clients/api/Clients.cpp

Blob: `8a27b27f363bdc4e1e45e701d6b50e9250225b6c`. Grammar: cpp. Status: contains-errors.

- include "Clients.h" @5
- include "Client.h" @7
- include "ClientDOMUtil.h" @8
- include "mozilla/SchedulerGroup.h" @9
- include "mozilla/StaticPrefs_privacy.h" @10
- include "mozilla/dom/ClientIPCTypes.h" @11
- include "mozilla/dom/ClientManager.h" @12
- include "mozilla/dom/ClientsBinding.h" @13
- include "mozilla/dom/Promise.h" @14
- include "mozilla/dom/ServiceWorkerDescriptor.h" @15
- include "mozilla/dom/ServiceWorkerManager.h" @16
- include "mozilla/dom/ServiceWorkerUtils.h" @17
- include "mozilla/dom/WorkerScope.h" @18
- include "mozilla/ipc/BackgroundUtils.h" @19
- include "nsIGlobalObject.h" @20
- include "nsReadableUtils.h" @21
- include "nsString.h" @22
- function_definition mGlobal @36-40
- function_definition WrapObject @42-45
- function_definition GetParentObject @47-47
- function_definition Get @49-113
- class_specifier MatchAllComparator @117-143
- function_definition LessThan @119-137
- function_definition Equals @139-142
- function_definition MatchAll @147-197
- function_definition OpenWindow @199-253
- function_definition Claim @255-287

### dom/clients/api/Clients.h

Blob: `d24a8093031db0f8029afcaafddde8065d194fc6`. Grammar: cpp. Status: contains-errors.

- include "nsCOMPtr.h" @7
- include "nsISupports.h" @8
- include "nsWrapperCache.h" @9
- class_specifier nsIGlobalObject @11-11
- class_specifier ErrorResult @15-15
- struct_specifier ClientQueryOptions @19-19
- class_specifier Promise @20-20
- class_specifier Clients @22-48
- function_definition ~Clients @25-25

### dom/clients/manager/ClientChannelHelper.cpp

Blob: `def48e59d469e04131dcbdae3fa0e540d280afb4`. Grammar: cpp. Status: contains-errors.

- include "ClientChannelHelper.h" @5
- include "ClientManager.h" @7
- include "ClientSource.h" @8
- include "MainThreadUtils.h" @9
- include "mozilla/AntiTrackingUtils.h" @10
- include "mozilla/StoragePrincipalHelper.h" @11
- include "mozilla/dom/ClientsBinding.h" @12
- include "mozilla/dom/ServiceWorkerDescriptor.h" @13
- include "mozilla/ipc/BackgroundUtils.h" @14
- include "nsContentUtils.h" @15
- include "nsIAsyncVerifyRedirectCallback.h" @16
- include "nsIChannel.h" @17
- include "nsIChannelEventSink.h" @18
- include "nsIHttpChannelInternal.h" @19
- include "nsIInterfaceRequestor.h" @20
- include "nsIInterfaceRequestorUtils.h" @21
- class_specifier ClientChannelHelper @36-201
- function_definition ~ClientChannelHelper @42-42
- function_definition GetInterface @44-57
- function_definition CreateClient @59-61
- function_definition AsyncOnChannelRedirect @63-180
- function_definition ClientChannelHelper @183-185
- function_definition CreateClientForPrincipal @187-200
- class_specifier ClientChannelHelperParent @206-257
- function_definition ~ClientChannelHelperParent @207-213
- function_definition CreateClient @215-217
- function_definition SetFutureSourceInfo @219-231
- function_definition CreateClientForPrincipal @239-253
- function_definition ClientChannelHelperParent @254-256
- class_specifier ClientChannelHelperChild @259-287
- function_definition ~ClientChannelHelperChild @260-260
- function_definition AsyncOnChannelRedirect @262-281
- function_definition ClientChannelHelperChild @284-286
- function_definition AddClientChannelHelperInternal @292-368
- function_definition AddClientChannelHelper @370-377
- function_definition AddClientChannelHelperInParent @379-385
- function_definition AddClientChannelHelperInChild @387-405
- function_definition CreateReservedSourceIfNeeded @407-418

### dom/clients/manager/ClientChannelHelper.h

Blob: `d2f441ffcb29bd1f517aeace92dc7dea44675216`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Maybe.h" @7
- include "nsError.h" @8
- class_specifier nsIChannel @10-10
- class_specifier nsISerialEventTarget @11-11
- class_specifier ClientInfo @15-15

### dom/clients/manager/ClientHandle.cpp

Blob: `98a182530a42bd32e8a0cc5a0e4b9b7987b9b8cb`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandle.h" @5
- include "ClientHandleChild.h" @7
- include "ClientHandleOpChild.h" @8
- include "ClientManager.h" @9
- include "ClientPrincipalUtils.h" @10
- include "ClientState.h" @11
- include "mozilla/dom/PClientManagerChild.h" @12
- include "mozilla/dom/ServiceWorkerDescriptor.h" @13
- include "mozilla/dom/ipc/StructuredCloneData.h" @14
- function_definition ~ClientHandle @20-20
- function_definition Shutdown @22-31
- function_definition StartOp @33-58
- function_definition OnShutdownThing @60-66
- function_definition ClientHandle @68-77
- function_definition Activate @79-93
- function_definition ExecutionReady @95-97
- function_definition (anonymous) @99-99
- function_definition Control @101-121
- function_definition Focus @123-138
- function_definition PostMessage @140-165
- function_definition OnDetach @167-178
- function_definition EvictFromBFCache @180-185

### dom/clients/manager/ClientHandle.h

Blob: `fe467443b9262674c1eac33149a81f4df1168633`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/MozPromise.h" @7
- include "mozilla/dom/ClientInfo.h" @8
- include "mozilla/dom/ClientOpPromise.h" @9
- include "mozilla/dom/ClientThing.h" @10
- class_specifier ClientManager @18-18
- class_specifier ClientHandleChild @19-19
- class_specifier ClientOpConstructorArgs @20-20
- class_specifier PClientManagerChild @21-21
- class_specifier ServiceWorkerDescriptor @22-22
- enum_specifier CallerType @23-23
- class_specifier StructuredCloneData @26-26
- class_specifier ClientHandle @35-107

### dom/clients/manager/ClientHandleChild.cpp

Blob: `4fb73796105a6c67bb271a6dc0b749eb9b9fc3bc`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandleChild.h" @5
- include "ClientHandle.h" @7
- include "ClientHandleOpChild.h" @8
- include "mozilla/dom/ClientIPCTypes.h" @9
- function_definition RecvExecutionReady @15-21
- function_definition ActorDestroy @23-31
- function_definition AllocPClientHandleOpChild @33-37
- function_definition DeallocPClientHandleOpChild @39-43
- function_definition ClientHandleChild @45-46
- function_definition SetOwner @48-52
- function_definition RevokeOwner @54-58
- function_definition MaybeStartTeardown @60-66

### dom/clients/manager/ClientHandleChild.h

Blob: `eb3e4a904b855973b514b8ba025b0c6193231dbc`. Grammar: cpp. Status: contains-errors.

- include "ClientThing.h" @7
- include "mozilla/dom/PClientHandleChild.h" @8
- class_specifier ClientHandle @12-12
- class_specifier ClientInfo @13-13
- class_specifier ClientThing @16-16
- class_specifier ClientHandleChild @18-45
- function_definition ~ClientHandleChild @22-22

### dom/clients/manager/ClientHandleOpChild.cpp

Blob: `9fffe93f71a5c2678525562be265cf2763889e3f`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandleOpChild.h" @5
- include "ClientHandle.h" @7
- function_definition ActorDestroy @11-16
- function_definition Recv__delete__ @18-28
- function_definition ClientHandleOpChild @30-40

### dom/clients/manager/ClientHandleOpChild.h

Blob: `e0668ddc5b370904f1b0c8f808afc2f33105f860`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/dom/ClientOpPromise.h" @7
- include "mozilla/dom/PClientHandleOpChild.h" @8
- class_specifier ClientHandle @12-12
- class_specifier ClientHandleOpChild @14-32
- function_definition ~ClientHandleOpChild @31-31

### dom/clients/manager/ClientHandleOpParent.cpp

Blob: `fad5f033c1ec91124b3ebc4feda17481c1d5cb16`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandleOpParent.h" @5
- include "ClientHandleParent.h" @7
- include "ClientSourceParent.h" @8
- include "ClientValidation.h" @9
- include "mozilla/dom/PClientManagerParent.h" @10
- include "mozilla/dom/ipc/StructuredCloneData.h" @11
- include "mozilla/ipc/BackgroundParent.h" @12
- function_definition GetSource @19-22
- function_definition ActorDestroy @24-27
- function_definition Init @29-90

### dom/clients/manager/ClientHandleOpParent.h

Blob: `32700dfd6afb72e274053cb18c5ff668342641d4`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandleParent.h" @7
- include "ClientOpPromise.h" @8
- include "mozilla/dom/PClientHandleOpParent.h" @9
- class_specifier ClientSourceParent @13-13
- class_specifier ClientHandleOpParent @15-29
- function_definition ClientHandleOpParent @25-25
- function_definition ~ClientHandleOpParent @26-26

### dom/clients/manager/ClientHandleParent.cpp

Blob: `e8624cf7e19dde6f2c395566bb67a9b38ce2d27a`. Grammar: cpp. Status: syntax-clean.

- include "ClientHandleParent.h" @5
- include "ClientHandleOpParent.h" @7
- include "ClientManagerService.h" @8
- include "ClientPrincipalUtils.h" @9
- include "ClientSourceParent.h" @10
- include "ClientValidation.h" @11
- include "mozilla/dom/ClientIPCTypes.h" @12
- include "mozilla/dom/ContentParent.h" @13
- include "mozilla/dom/PClientManagerParent.h" @14
- include "mozilla/ipc/BackgroundParent.h" @15
- function_definition RecvTeardown @22-25
- function_definition ActorDestroy @27-40
- function_definition AllocPClientHandleOpParent @42-45
- function_definition DeallocPClientHandleOpParent @47-51
- function_definition RecvPClientHandleOpConstructor @53-58
- function_definition ClientHandleParent @60-61
- function_definition ~ClientHandleParent @63-63
- function_definition Init @65-94
- function_definition GetSource @96-96
- function_definition EnsureSource @98-104
- function_definition FoundSource @106-123

### dom/clients/manager/ClientHandleParent.h

Blob: `c4896d370c7a3bf0d577d3dc6fb0068249cf199d`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/PClientHandleParent.h" @7
- class_specifier ClientManagerService @11-11
- class_specifier ClientSourceParent @12-12
- class_specifier ClientHandleParent @17-60

### dom/clients/manager/ClientIPCUtils.h

Blob: `f82367cd92ee778fc2df46a4f9c5dd377aa10c11`. Grammar: cpp. Status: syntax-clean.

- include "X11UndefineNone.h" @7
- include "ipc/EnumSerializer.h" @8
- include "mozilla/StorageAccess.h" @9
- include "mozilla/dom/BindingIPCUtils.h" @10
- include "mozilla/dom/ClientBinding.h" @11
- include "mozilla/dom/ClientsBinding.h" @12
- include "mozilla/dom/DocumentBinding.h" @13
- struct_specifier ParamTraits<mozilla::dom::ClientType> @17-18
- struct_specifier ParamTraits<mozilla::dom::FrameType> @21-22
- struct_specifier ParamTraits<mozilla::dom::VisibilityState> @25-27
- struct_specifier ParamTraits<mozilla::StorageAccess> @30-34

### dom/clients/manager/ClientInfo.cpp

Blob: `864c56dd20fc6c7c87e085f7c33a7d6a5cbc65ee`. Grammar: cpp. Status: contains-errors.

- include "ClientInfo.h" @5
- include "mozilla/dom/ClientIPCTypes.h" @7
- include "mozilla/ipc/BackgroundUtils.h" @8
- function_definition ClientInfo @15-22
- function_definition ClientInfo @24-25
- function_definition ClientInfo @27-27
- function_definition (anonymous) @29-33
- function_definition ClientInfo @35-36
- function_definition (anonymous) @38-42
- function_definition ~ClientInfo @44-44
- function_definition operator== @46-48
- function_definition operator!= @50-52
- function_definition (anonymous) @54-54
- function_definition SetAgentClusterId @56-60
- function_definition (anonymous) @62-64
- function_definition Type @66-66
- function_definition (anonymous) @68-70
- function_definition (anonymous) @72-74
- function_definition (anonymous) @76-76
- function_definition SetURL @78-78
- function_definition FrameType @80-80
- function_definition SetFrameType @82-84
- function_definition (anonymous) @86-86
- function_definition IsPrivateBrowsing @88-106
- function_definition GetPrincipal @108-110
- function_definition (anonymous) @112-115
- function_definition SetPolicyContainerArgs @117-120
- function_definition (anonymous) @122-124
- function_definition SetPreloadCspInfo @126-129

### dom/clients/manager/ClientInfo.h

Blob: `892c021627b873bec0689604644a536970d88782`. Grammar: cpp. Status: syntax-clean.

- include "X11UndefineNone.h" @8
- include "mozilla/Maybe.h" @9
- include "mozilla/TimeStamp.h" @10
- include "mozilla/UniquePtr.h" @11
- include "nsCOMPtr.h" @12
- include "nsString.h" @13
- class_specifier nsIPrincipal @15-15
- struct_specifier nsID @16-16
- class_specifier CSPInfo @21-21
- class_specifier PolicyContainerArgs @22-22
- class_specifier PrincipalInfo @23-23
- class_specifier IPCClientInfo @28-28
- enum_specifier FrameType @29-29
- enum_specifier ClientType @30-30
- class_specifier ClientInfo @35-114

### dom/clients/manager/ClientManager.cpp

Blob: `4748b4dca16a17a613bd18754b0b91d531114bdf`. Grammar: cpp. Status: contains-errors.

- include "ClientManager.h" @5
- include "ClientHandle.h" @7
- include "ClientManagerChild.h" @8
- include "ClientManagerOpChild.h" @9
- include "ClientSource.h" @10
- include "mozilla/ClearOnShutdown.h" @11
- include "mozilla/StaticPrefs_dom.h" @12
- include "mozilla/dom/WorkerPrivate.h" @13
- include "mozilla/ipc/BackgroundChild.h" @14
- include "mozilla/ipc/PBackgroundChild.h" @15
- include "prthread.h" @16
- function_definition ClientManager @45-68
- function_definition Shutdown @90-98
- function_definition CreateSourceInternal @100-134
- function_definition CreateSourceInternal @136-154
- function_definition CreateHandleInternal @156-172
- function_definition StartOp @174-201
- function_definition GetOrCreateForCurrentThread @204-234
- function_definition GetWorkerPrivate @236-240
- function_definition ExpectOrForgetFutureSource @243-264
- function_definition ExpectFutureSource @266-270
- function_definition ForgetFutureSource @272-276
- function_definition Startup @279-398
- function_definition CreateSource @301-315
- function_definition CreateSource @318-323
- function_definition CreateSourceFromInfo @326-330
- function_definition CreateInfo @332-352
- function_definition CreateHandle @355-359
- function_definition MatchAll @362-366
- function_definition Claim @369-373
- function_definition GetInfoAndState @376-381
- function_definition Navigate @384-388
- function_definition OpenWindow @391-396

### dom/clients/manager/ClientManager.h

Blob: `aa8b055cb4a0c94f5d07a9ea244ed27a2d150a7a`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/ClientOpPromise.h" @7
- include "mozilla/dom/ClientThing.h" @8
- include "mozilla/dom/PClientManagerChild.h" @9
- class_specifier nsIPrincipal @11-11
- class_specifier PBackgroundChild @15-15
- class_specifier PrincipalInfo @16-16
- class_specifier ClientClaimArgs @20-20
- class_specifier ClientGetInfoAndStateArgs @21-21
- class_specifier ClientHandle @22-22
- class_specifier ClientInfo @23-23
- class_specifier ClientManagerChild @24-24
- class_specifier ClientMatchAllArgs @25-25
- class_specifier ClientNavigateArgs @26-26
- class_specifier ClientOpConstructorArgs @27-27
- class_specifier ClientOpenWindowArgs @28-28
- class_specifier ClientSource @29-29
- enum_specifier ClientType @30-30
- class_specifier WorkerPrivate @31-31
- class_specifier ClientManager @38-144

### dom/clients/manager/ClientManagerActors.cpp

Blob: `143d8d292c80a5ae2eabd81737700f25e0a221b5`. Grammar: cpp. Status: syntax-clean.

- include "ClientManagerChild.h" @5
- include "ClientManagerParent.h" @6
- function_definition AllocClientManagerParent @10-12
- function_definition InitClientManagerParent @14-17

### dom/clients/manager/ClientManagerActors.h

Blob: `34585ce25947603e38542c9bc36e9bc4a57bd6d7`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/AlreadyAddRefed.h" @7
- class_specifier PClientManagerParent @12-12

### dom/clients/manager/ClientManagerChild.cpp

Blob: `5e24d94a8dc30ed32717e8e789e1073c0d2c2ab0`. Grammar: cpp. Status: syntax-clean.

- include "ClientManagerChild.h" @5
- include "ClientHandleChild.h" @7
- include "ClientManagerOpChild.h" @8
- include "ClientNavigateOpChild.h" @9
- include "ClientSourceChild.h" @10
- include "mozilla/dom/WorkerCommon.h" @11
- include "mozilla/dom/WorkerRef.h" @12
- function_definition ActorDestroy @16-26
- function_definition AllocPClientManagerOpChild @28-33
- function_definition DeallocPClientManagerOpChild @35-39
- function_definition AllocPClientNavigateOpChild @41-44
- function_definition DeallocPClientNavigateOpChild @46-50
- function_definition RecvPClientNavigateOpConstructor @52-59
- function_definition Create @62-82
- function_definition ClientManagerChild @84-85
- function_definition ~ClientManagerChild @87-87
- function_definition SetOwner @89-93
- function_definition RevokeOwner @95-99
- function_definition MaybeStartTeardown @101-107
- function_definition GetWorkerPrivate @109-114

### dom/clients/manager/ClientManagerChild.h

Blob: `2bd78adc12f255a954bcda82855b8709cd8e196e`. Grammar: cpp. Status: contains-errors.

- include "ClientThing.h" @7
- include "mozilla/dom/PClientManagerChild.h" @8
- class_specifier IPCWorkerRef @12-12
- class_specifier WorkerPrivate @13-13
- class_specifier ClientManagerChild @15-54

### dom/clients/manager/ClientManagerOpChild.cpp

Blob: `d3dcee4fc4426da8e41f72e67b45e0bf398bc3ae`. Grammar: cpp. Status: syntax-clean.

- include "ClientManagerOpChild.h" @5
- include "mozilla/dom/ClientManager.h" @7
- include "mozilla/ipc/ProtocolUtils.h" @8
- function_definition ActorDestroy @12-20
- function_definition Recv__delete__ @22-34
- function_definition ClientManagerOpChild @36-42
- function_definition ~ClientManagerOpChild @44-46

### dom/clients/manager/ClientManagerOpChild.h

Blob: `e914dc8963aa8a7b134635b026cc62ec97bedc65`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/MozPromise.h" @7
- include "mozilla/dom/ClientOpPromise.h" @8
- include "mozilla/dom/PClientManagerOpChild.h" @9
- class_specifier ClientManager @13-13
- class_specifier ClientManagerOpChild @15-31

### dom/clients/manager/ClientManagerOpParent.cpp

Blob: `242c393ac67220d635bd58e517eb5eee40670273`. Grammar: cpp. Status: contains-errors.

- include "ClientManagerOpParent.h" @5
- include "ClientManagerService.h" @7
- include "ClientValidation.h" @8
- include "mozilla/dom/ContentParent.h" @9
- include "mozilla/dom/PClientManagerParent.h" @10
- include "mozilla/dom/RemoteType.h" @11
- include "mozilla/ipc/BackgroundParent.h" @12
- function_definition DoServiceOp @20-42
- function_definition ActorDestroy @44-46
- function_definition ClientManagerOpParent @48-51
- function_definition Init @53-95

### dom/clients/manager/ClientManagerOpParent.h

Blob: `4f2859e6b601cb632bdfc332b5b8c653f12b2080`. Grammar: cpp. Status: syntax-clean.

- include "ClientOpPromise.h" @7
- include "mozilla/dom/PClientManagerOpParent.h" @8
- class_specifier ClientManagerService @12-12
- class_specifier ThreadsafeContentParentHandle @13-13
- class_specifier ClientManagerOpParent @15-34
- function_definition ~ClientManagerOpParent @29-29

### dom/clients/manager/ClientManagerParent.cpp

Blob: `7eb2a26f0c8ae78522e00966cd3c12c9f0ab853c`. Grammar: cpp. Status: syntax-clean.

- include "ClientManagerParent.h" @5
- include "ClientHandleParent.h" @7
- include "ClientManagerOpParent.h" @8
- include "ClientManagerService.h" @9
- include "ClientSourceParent.h" @10
- include "ClientValidation.h" @11
- include "mozilla/dom/ContentParent.h" @12
- include "mozilla/dom/PClientNavigateOpParent.h" @13
- include "mozilla/ipc/BackgroundParent.h" @14
- function_definition RecvTeardown @21-24
- function_definition ActorDestroy @26-28
- function_definition AllocPClientHandleParent @30-34
- function_definition RecvPClientHandleConstructor @36-40
- function_definition AllocPClientManagerOpParent @42-45
- function_definition DeallocPClientManagerOpParent @47-51
- function_definition RecvPClientManagerOpConstructor @53-59
- function_definition AllocPClientNavigateOpParent @61-66
- function_definition DeallocPClientNavigateOpParent @68-72
- function_definition AllocPClientSourceParent @74-81
- function_definition RecvPClientSourceConstructor @83-93
- function_definition ClientManagerParent @95-96
- function_definition ~ClientManagerParent @98-98
- function_definition Init @100-100
- function_definition RecvExpectFutureClientSource @102-114
- function_definition RecvForgetFutureClientSource @116-127

### dom/clients/manager/ClientManagerParent.h

Blob: `c02f13c65363c5581e6244c716b33562db863f2d`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/PClientManagerParent.h" @7
- class_specifier ClientManagerService @11-11
- class_specifier ClientManagerParent @13-62

### dom/clients/manager/ClientManagerService.cpp

Blob: `9e3cf49cd7df271182a1651804c0d590dbbd28c7`. Grammar: cpp. Status: contains-errors.

- include "ClientManagerService.h" @5
- include "ClientHandleParent.h" @7
- include "ClientManagerParent.h" @8
- include "ClientNavigateOpParent.h" @9
- include "ClientOpenWindowUtils.h" @10
- include "ClientPrincipalUtils.h" @11
- include "ClientSourceParent.h" @12
- include "jsfriendapi.h" @13
- include "mozilla/ClearOnShutdown.h" @14
- include "mozilla/Components.h" @15
- include "mozilla/MozPromise.h" @16
- include "mozilla/SchedulerGroup.h" @17
- include "mozilla/ScopeExit.h" @18
- include "mozilla/dom/ContentParent.h" @19
- include "mozilla/dom/ServiceWorkerManager.h" @20
- include "mozilla/dom/ServiceWorkerUtils.h" @21
- include "mozilla/ipc/BackgroundParent.h" @22
- include "mozilla/ipc/PBackgroundSharedTypes.h" @23
- include "nsIAsyncShutdown.h" @24
- include "nsIXULRuntime.h" @25
- include "nsProxyRelease.h" @26
- class_specifier ClientShutdownBlocker @38-109
- function_definition ~ClientShutdownBlocker @41-41
- function_definition ClientShutdownBlocker @44-47
- function_definition GetName @49-54
- function_definition BlockShutdown @56-61
- function_definition GetState @63-64
- function_definition OnShutdown @73-107
- function_definition ClientManagerService @115-140
- function_definition ~ClientManagerService @142-149
- function_definition Shutdown @151-180
- function_definition MaybeUnwrapAsExistingSource @182-191
- function_definition FindExistingSource @193-210
- function_definition GetOrCreateInstance @213-223
- function_definition GetInstance @226-235
- function_definition IsNullPrincipalInfo @239-241
- function_definition AreBothNullPrincipals @243-247
- function_definition AddSource @251-293
- function_definition RemoveSource @295-304
- function_definition ExpectFutureSource @306-324
- function_definition ForgetFutureSource @326-358
- function_definition FindSource @360-385
- function_definition AddManager @387-397
- function_definition RemoveManager @399-404
- function_definition Navigate @406-453
- class_specifier PromiseListHolder @457-520
- function_definition ProcessSuccess @463-466
- function_definition ProcessCompletion @468-472
- function_definition ~PromiseListHolder @474-474
- function_definition PromiseListHolder @477-479
- function_definition GetResultPromise @481-488
- function_definition AddPromise @490-511
- function_definition MaybeFinish @513-517
- function_definition MatchAll @524-572
- function_definition ClaimOnMainThread @576-615
- function_definition Claim @619-671
- function_definition GetInfoAndState @673-706
- function_definition OpenWindow @708-716
- function_definition HasWindow @718-741

### dom/clients/manager/ClientManagerService.h

Blob: `704709eff1a101ba24d5447342331c7881e95ef1`. Grammar: cpp. Status: contains-errors.

- include "ClientHandleParent.h" @7
- include "ClientOpPromise.h" @8
- include "mozilla/AlreadyAddRefed.h" @9
- include "mozilla/Assertions.h" @10
- include "mozilla/MozPromise.h" @11
- include "mozilla/RefPtr.h" @12
- include "mozilla/Variant.h" @13
- include "mozilla/dom/ClientIPCTypes.h" @14
- include "mozilla/dom/ipc/IdType.h" @15
- include "nsHashKeys.h" @16
- include "nsISupports.h" @17
- include "nsTArray.h" @18
- include "nsTHashMap.h" @19
- struct_specifier nsID @21-21
- class_specifier PrincipalInfo @27-27
- class_specifier ClientManagerParent @33-33
- class_specifier ClientSourceParent @34-34
- class_specifier ClientHandleParent @35-35
- class_specifier ThreadsafeContentParentHandle @36-36
- class_specifier ClientManagerService @41-158
- class_specifier FutureClientSourceParent @48-78
- function_definition (anonymous) @52-54
- function_definition Promise @56-58
- function_definition ResolvePromiseIfExists @60-62
- function_definition RejectPromiseIfExists @64-67
- function_definition SetAsAssociated @69-69
- function_definition IsAssociated @71-71

### dom/clients/manager/ClientNavigateOpChild.cpp

Blob: `1e7cb16c021c3d72f0050b23a17aabc528b1c7ee`. Grammar: cpp. Status: contains-errors.

- include "ClientNavigateOpChild.h" @5
- include "ClientSource.h" @7
- include "ClientSourceChild.h" @8
- include "ClientState.h" @9
- include "ReferrerInfo.h" @10
- include "mozilla/dom/Document.h" @11
- include "mozilla/dom/PolicyContainer.h" @12
- include "nsDocShellLoadState.h" @13
- include "nsIDocShell.h" @14
- include "nsIWebNavigation.h" @15
- include "nsIWebProgress.h" @16
- include "nsIWebProgressListener.h" @17
- include "nsNetUtil.h" @18
- include "nsPIDOMWindow.h" @19
- include "nsPIDOMWindowInlines.h" @20
- include "nsURLHelper.h" @21
- class_specifier NavigateLoadListener @27-146
- function_definition ~NavigateLoadListener @33-33
- function_definition NavigateLoadListener @36-42
- function_definition OnStateChange @44-106
- function_definition OnProgressChange @108-115
- function_definition OnLocationChange @117-122
- function_definition OnStatusChange @124-129
- function_definition OnSecurityChange @131-136
- function_definition OnContentBlockingEvent @138-143
- function_definition DoNavigate @153-318
- function_definition ActorDestroy @320-322
- function_definition Init @324-352

### dom/clients/manager/ClientNavigateOpChild.h

Blob: `a374439cd95f3c1891ba7ba052305d87abd40967`. Grammar: cpp. Status: contains-errors.

- include "ClientOpPromise.h" @7
- include "mozilla/dom/PClientNavigateOpChild.h" @8
- class_specifier ClientNavigateOpChild @12-31
- function_definition ClientNavigateOpChild @25-25
- function_definition ~ClientNavigateOpChild @26-26

### dom/clients/manager/ClientNavigateOpParent.cpp

Blob: `1167831359fc90e42b5b4f345673123dc5404e56`. Grammar: cpp. Status: syntax-clean.

- include "ClientNavigateOpParent.h" @5
- function_definition ActorDestroy @11-18
- function_definition Recv__delete__ @20-31
- function_definition ClientNavigateOpParent @33-38
- function_definition ~ClientNavigateOpParent @40-42

### dom/clients/manager/ClientNavigateOpParent.h

Blob: `c5f5cf17011794cdeb3a86aa131ef525dbcc768d`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/dom/ClientOpPromise.h" @7
- include "mozilla/dom/PClientNavigateOpParent.h" @8
- class_specifier ClientNavigateOpParent @12-26

### dom/clients/manager/ClientOpPromise.h

Blob: `53934d8ce846810a300579dc3fa8afd7f781ef3a`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/MozPromise.h" @7
- class_specifier CopyableErrorResult @10-10
- class_specifier ClientOpResult @14-14
- class_specifier ClientState @15-15

### dom/clients/manager/ClientOpenWindowUtils.cpp

Blob: `5979ef1d958aad1afa60117956a44bf8bbc2c458`. Grammar: cpp. Status: contains-errors.

- include "ClientOpenWindowUtils.h" @5
- include "ClientInfo.h" @7
- include "ClientManager.h" @8
- include "ClientState.h" @9
- include "mozilla/NullPrincipal.h" @10
- include "mozilla/dom/BrowserParent.h" @11
- include "mozilla/dom/BrowsingContext.h" @12
- include "mozilla/dom/CanonicalBrowsingContext.h" @13
- include "mozilla/dom/ContentParent.h" @14
- include "mozilla/dom/PolicyContainer.h" @15
- include "mozilla/dom/WindowGlobalParent.h" @16
- include "mozilla/dom/nsCSPContext.h" @17
- include "nsContentUtils.h" @18
- include "nsDocShell.h" @19
- include "nsDocShellLoadState.h" @20
- include "nsFocusManager.h" @21
- include "nsGlobalWindowOuter.h" @22
- include "nsIBrowser.h" @23
- include "nsIBrowserDOMWindow.h" @24
- include "nsIDocShell.h" @25
- include "nsIDocShellTreeOwner.h" @26
- include "nsIMutableArray.h" @27
- include "nsISupportsPrimitives.h" @28
- include "nsIURI.h" @29
- include "nsIWebProgress.h" @30
- include "nsIWebProgressListener.h" @31
- include "nsIWindowMediator.h" @32
- include "nsIWindowWatcher.h" @33
- include "nsIXPConnect.h" @34
- include "nsNetUtil.h" @35
- include "nsOpenWindowInfo.h" @36
- include "nsPIDOMWindow.h" @37
- include "nsPIWindowWatcher.h" @38
- include "nsPrintfCString.h" @39
- include "nsWindowWatcher.h" @40
- include "mozilla/dom/Promise-inl.h" @43
- include "nsIGeckoViewServiceWorker.h" @44
- include "nsImportModule.h" @45
- function_definition OnStateChange @52-144
- class_specifier WebProgressListener @52-65
- function_definition OnProgressChange @146-153
- function_definition OnLocationChange @155-160
- function_definition OnStatusChange @162-167
- function_definition OnSecurityChange @169-174
- function_definition OnContentBlockingEvent @176-181
- struct_specifier ClientOpenWindowArgsParsed @201-207
- function_definition OpenNewWindow @211-266
- function_definition OpenWindow @272-323
- function_definition WaitForLoad @326-389
- function_definition GeckoViewOpenWindow @392-438
- function_definition ClientOpenWindow @443-553

### dom/clients/manager/ClientOpenWindowUtils.h

Blob: `ab4f8ff9908d9a9d328716d342f93ecc8842c78b`. Grammar: cpp. Status: contains-errors.

- include "ClientOpPromise.h" @7
- include "mozilla/dom/ClientIPCTypes.h" @8
- class_specifier ThreadsafeContentParentHandle @12-12

### dom/clients/manager/ClientPrincipalUtils.cpp

Blob: `a3c56d6eacb191acdb168b5f36f34144652c588a`. Grammar: cpp. Status: syntax-clean.

- include "ClientPrincipalUtils.h" @5
- include "mozilla/ipc/PBackgroundSharedTypes.h" @7
- function_definition ClientMatchPrincipalInfo @14-44

### dom/clients/manager/ClientPrincipalUtils.h

Blob: `1c8afde3ac53a6f837aba5c3d2df8ea2c416ea57`. Grammar: cpp. Status: syntax-clean.

- class_specifier PrincipalInfo @10-10

### dom/clients/manager/ClientSource.cpp

Blob: `cd99a976e04afcd1b4a3945b6470e3ff992199b6`. Grammar: cpp. Status: syntax-clean.

- include "ClientSource.h" @5
- include "ClientManager.h" @7
- include "ClientManagerChild.h" @8
- include "ClientPrincipalUtils.h" @9
- include "ClientSourceChild.h" @10
- include "ClientState.h" @11
- include "ClientValidation.h" @12
- include "mozilla/SchedulerGroup.h" @13
- include "mozilla/StaticPrefs_privacy.h" @14
- include "mozilla/StorageAccess.h" @15
- include "mozilla/Try.h" @16
- include "mozilla/dom/BlobURLProtocolHandler.h" @17
- include "mozilla/dom/ClientIPCTypes.h" @18
- include "mozilla/dom/ContentChild.h" @19
- include "mozilla/dom/DOMMozPromiseRequestHolder.h" @20
- include "mozilla/dom/JSExecutionManager.h" @21
- include "mozilla/dom/MessageEvent.h" @22
- include "mozilla/dom/MessageEventBinding.h" @23
- include "mozilla/dom/Navigator.h" @24
- include "mozilla/dom/PolicyContainer.h" @25
- include "mozilla/dom/ServiceWorker.h" @26
- include "mozilla/dom/ServiceWorkerContainer.h" @27
- include "mozilla/dom/ServiceWorkerManager.h" @28
- include "mozilla/dom/ServiceWorkerUtils.h" @29
- include "mozilla/dom/WorkerRef.h" @30
- include "mozilla/dom/WorkerScope.h" @31
- include "mozilla/dom/ipc/StructuredCloneData.h" @32
- include "mozilla/ipc/BackgroundUtils.h" @33
- include "nsContentUtils.h" @34
- include "nsFocusManager.h" @35
- include "nsIContentSecurityPolicy.h" @36
- include "nsIDocShell.h" @37
- include "nsPIDOMWindow.h" @38
- function_definition Shutdown @48-57
- function_definition ExecutionReady @59-75
- function_definition SnapshotWindowState @77-103
- function_definition GetWorkerPrivate @105-111
- function_definition GetDocShell @113-119
- function_definition GetGlobal @121-139
- function_definition MaybeCreateInitialDocument @143-158
- function_definition ClientSource @160-171
- function_definition Activate @173-203
- function_definition ~ClientSource @205-205
- function_definition GetInnerWindow @207-213
- function_definition WorkerExecutionReady @215-246
- function_definition WindowExecutionReady @248-315
- function_definition DocShellExecutionReady @317-352
- function_definition Freeze @354-356
- function_definition Thaw @358-360
- function_definition EvictFromBFCache @362-368
- function_definition EvictFromBFCacheOp @370-373
- function_definition (anonymous) @375-375
- function_definition WorkerSyncPing @377-393
- function_definition SetController @395-442
- function_definition Control @444-487
- function_definition InheritController @489-504
- function_definition (anonymous) @506-508
- function_definition NoteDOMContentLoaded @510-513
- function_definition Focus @515-590
- function_definition PostMessage @592-613
- function_definition GetInfoAndState @615-626
- function_definition SnapshotState @628-646
- function_definition EventTarget @648-648
- function_definition SetPolicyContainer @650-661
- function_definition SetPreloadCsp @663-675
- function_definition SetPolicyContainerArgs @677-681
- function_definition (anonymous) @683-687
- function_definition Traverse @689-698
- function_definition NoteCalledRegisterForServiceWorkerScope @700-706
- function_definition CalledRegisterForServiceWorkerScope @708-711
- function_definition GetPrincipal @713-727

### dom/clients/manager/ClientSource.h

Blob: `e9d044b61065dac8d0f2307ddd5b1dcd46038b90`. Grammar: cpp. Status: contains-errors.

- include "mozilla/ResultVariant.h" @7
- include "mozilla/Variant.h" @8
- include "mozilla/dom/ClientInfo.h" @9
- include "mozilla/dom/ClientOpPromise.h" @10
- include "mozilla/dom/ClientThing.h" @11
- include "mozilla/dom/ServiceWorkerDescriptor.h" @12
- class_specifier nsIContentSecurityPolicy @18-18
- class_specifier nsIPolicyContainer @19-19
- class_specifier nsIDocShell @20-20
- class_specifier nsIGlobalObject @21-21
- class_specifier nsISerialEventTarget @22-22
- class_specifier nsPIDOMWindowInner @23-23
- class_specifier ErrorResult @26-26
- class_specifier ClientControlledArgs @30-30
- class_specifier ClientFocusArgs @31-31
- class_specifier ClientGetInfoAndStateArgs @32-32
- class_specifier ClientManager @33-33
- class_specifier ClientPostMessageArgs @34-34
- class_specifier ClientSourceChild @35-35
- class_specifier ClientSourceConstructorArgs @36-36
- class_specifier ClientSourceExecutionReadyArgs @37-37
- class_specifier ClientState @38-38
- class_specifier ClientWindowState @39-39
- class_specifier PClientManagerChild @40-40
- class_specifier WorkerPrivate @41-41
- class_specifier ClientSource @49-177
- function_definition SetAgentClusterId @165-167
- function_definition ImplCycleCollectionUnlink @179-181
- function_definition ImplCycleCollectionTraverse @183-189

### dom/clients/manager/ClientSourceChild.cpp

Blob: `93966a9e2e133c449fbd3b1bad08ced2813eaa85`. Grammar: cpp. Status: syntax-clean.

- include "ClientSourceChild.h" @5
- include "ClientSource.h" @7
- include "ClientSourceOpChild.h" @8
- include "mozilla/dom/ClientIPCTypes.h" @9
- function_definition ActorDestroy @15-23
- function_definition AllocPClientSourceOpChild @25-28
- function_definition DeallocPClientSourceOpChild @30-34
- function_definition RecvPClientSourceOpConstructor @36-41
- function_definition RecvEvictFromBFCache @43-49
- function_definition ClientSourceChild @51-52
- function_definition SetOwner @54-58
- function_definition RevokeOwner @60-64
- function_definition GetSource @66-66
- function_definition MaybeStartTeardown @68-74

### dom/clients/manager/ClientSourceChild.h

Blob: `03759f9c7272f3f2223cce72ac3fe4397b2c4f21`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/PClientSourceChild.h" @7
- class_specifier ClientSource @11-11
- class_specifier ClientSourceConstructorArgs @12-12
- class_specifier ClientThing @14-14
- class_specifier ClientSourceChild @16-48
- function_definition ~ClientSourceChild @20-20

### dom/clients/manager/ClientSourceOpChild.cpp

Blob: `640fea58b533259f67b389f992393d15c415320e`. Grammar: cpp. Status: contains-errors.

- include "ClientSourceOpChild.h" @5
- include "ClientSource.h" @7
- include "ClientSourceChild.h" @8
- include "mozilla/Assertions.h" @9
- function_definition GetSource @13-16
- function_definition DoSourceOp @19-68
- function_definition ActorDestroy @70-72
- function_definition Init @74-113
- function_definition ScheduleDeletion @115-123
- function_definition ~ClientSourceOpChild @125-127
- function_definition Cleanup @129-131

### dom/clients/manager/ClientSourceOpChild.h

Blob: `67d585dec523ef2e893dc0238d0c67635f41712b`. Grammar: cpp. Status: syntax-clean.

- include "ClientOpPromise.h" @7
- include "mozilla/dom/FlippedOnce.h" @8
- include "mozilla/dom/PClientSourceOpChild.h" @9
- class_specifier ClientSource @13-13
- class_specifier ClientSourceOpChild @15-39

### dom/clients/manager/ClientSourceOpParent.cpp

Blob: `46d096aaf9a4a89150642860e7abfa8f43a5d739`. Grammar: cpp. Status: syntax-clean.

- include "ClientSourceOpParent.h" @5
- include "ClientSourceParent.h" @7
- function_definition ActorDestroy @13-20
- function_definition Recv__delete__ @22-43
- function_definition ClientSourceOpParent @45-49
- function_definition ~ClientSourceOpParent @51-53

### dom/clients/manager/ClientSourceOpParent.h

Blob: `0efed1b22458d26380f19535ae0c3fccbd1c028e`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/dom/ClientOpPromise.h" @7
- include "mozilla/dom/PClientSourceOpParent.h" @8
- class_specifier ClientSourceOpParent @12-29
- function_definition (anonymous) @26-26

### dom/clients/manager/ClientSourceParent.cpp

Blob: `a87ebb08df51aca36a2be351ec788741542404b8`. Grammar: cpp. Status: syntax-clean.

- include "ClientSourceParent.h" @5
- include "ClientHandleParent.h" @7
- include "ClientManagerService.h" @8
- include "ClientPrincipalUtils.h" @9
- include "ClientSourceOpParent.h" @10
- include "ClientValidation.h" @11
- include "mozilla/SchedulerGroup.h" @12
- include "mozilla/dom/ClientIPCTypes.h" @13
- include "mozilla/dom/ContentParent.h" @14
- include "mozilla/dom/PClientManagerParent.h" @15
- include "mozilla/dom/ServiceWorkerManager.h" @16
- include "mozilla/dom/ServiceWorkerUtils.h" @17
- include "mozilla/ipc/BackgroundParent.h" @18
- function_definition RecvWorkerSyncPing @27-32
- function_definition RecvTeardown @34-37
- function_definition RecvExecutionReady @39-59
- function_definition RecvFreeze @61-71
- function_definition RecvThaw @73-82
- function_definition RecvInheritController @84-112
- function_definition RecvNoteDOMContentLoaded @114-129
- function_definition ActorDestroy @131-141
- function_definition AllocPClientSourceOpParent @143-148
- function_definition DeallocPClientSourceOpParent @150-154
- function_definition ClientSourceParent @156-165
- function_definition ~ClientSourceParent @167-171
- function_definition Init @173-193
- function_definition (anonymous) @195-195
- function_definition IsFrozen @197-197
- function_definition ExecutionReady @199-199
- function_definition ExecutionReadyPromise @201-206
- function_definition (anonymous) @208-211
- function_definition ClearController @213-213
- function_definition AttachHandle @215-219
- function_definition DetachHandle @221-225
- function_definition StartOp @227-249

### dom/clients/manager/ClientSourceParent.h

Blob: `e01592096a5b48925beb5df8169cf92d6c051dbd`. Grammar: cpp. Status: contains-errors.

- include "ClientInfo.h" @7
- include "ClientOpPromise.h" @8
- include "mozilla/MozPromise.h" @9
- include "mozilla/dom/PClientSourceParent.h" @10
- include "mozilla/dom/ServiceWorkerDescriptor.h" @11
- include "mozilla/dom/ipc/IdType.h" @12
- class_specifier ClientHandleParent @16-16
- class_specifier ClientManagerService @17-17
- class_specifier ThreadsafeContentParentHandle @18-18
- class_specifier ClientSourceParent @20-87
- function_definition IsOwnedByProcess @77-80

### dom/clients/manager/ClientState.cpp

Blob: `2552ca4ba74f59d8b67dcb95e2d4a42aeffbb0d4`. Grammar: cpp. Status: contains-errors.

- include "ClientState.h" @5
- include "mozilla/dom/ClientIPCTypes.h" @7
- function_definition ClientWindowState @11-16
- function_definition ClientWindowState @18-19
- function_definition ClientWindowState @21-23
- function_definition ClientWindowState @25-26
- function_definition (anonymous) @28-33
- function_definition (anonymous) @35-39
- function_definition VisibilityState @41-43
- function_definition (anonymous) @45-47
- function_definition Focused @49-49
- function_definition GetStorageAccess @51-53
- function_definition (anonymous) @55-55
- function_definition ClientWorkerState @57-58
- function_definition ClientWorkerState @60-61
- function_definition ClientWorkerState @63-64
- function_definition ClientWorkerState @66-68
- function_definition (anonymous) @70-75
- function_definition (anonymous) @77-81
- function_definition GetStorageAccess @83-85
- function_definition (anonymous) @87-87
- function_definition ClientState @89-89
- function_definition ClientState @91-93
- function_definition ClientState @95-97
- function_definition ClientState @99-101
- function_definition ClientState @103-105
- function_definition ClientState @107-108
- function_definition (anonymous) @110-113
- function_definition ~ClientState @115-115
- function_definition FromIPC @118-127
- function_definition IsWindowState @129-131
- function_definition (anonymous) @133-135
- function_definition IsWorkerState @137-139
- function_definition (anonymous) @141-143
- function_definition GetStorageAccess @145-151
- function_definition ToIPC @153-159

### dom/clients/manager/ClientState.h

Blob: `2aa4f5ab5b415c3dd6078f4acfdd4799b394d31c`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Maybe.h" @8
- include "mozilla/TimeStamp.h" @9
- include "mozilla/UniquePtr.h" @10
- include "mozilla/Variant.h" @11
- include "nsContentUtils.h" @12
- enum_specifier StorageAccess @18-18
- enum_specifier VisibilityState @27-27
- class_specifier IPCClientState @29-29
- class_specifier IPCClientWindowState @30-30
- class_specifier IPCClientWorkerState @31-31
- class_specifier ClientWindowState @36-64
- function_definition ~ClientWindowState @53-53
- class_specifier ClientWorkerState @72-92
- function_definition ~ClientWorkerState @87-87
- class_specifier ClientState @97-130
- function_definition ClientState @108-108
- function_definition (anonymous) @111-111

### dom/clients/manager/ClientThing.h

Blob: `f6a9f9076456e5f18261a901022cd020e4703398`. Grammar: cpp. Status: contains-errors.

- include "nsTArray.h" @7
- class_specifier ClientThing @15-132
- function_definition ClientThing @29-38
- function_definition ~ClientThing @40-47
- function_definition AssertIsValid @49-52
- function_definition GetActor @55-58
- function_definition IsShutdown @61-64
- function_definition MaybeExecute @68-77
- function_definition ActivateThing @83-90
- function_definition ShutdownThing @93-109
- function_definition OnShutdownThing @112-114
- function_definition RevokeActor @118-131

### dom/clients/manager/ClientValidation.cpp

Blob: `2e8fd8006a1377c9371af2da3d1fd306c51a4df6`. Grammar: cpp. Status: syntax-clean.

- include "ClientValidation.h" @5
- include "mozilla/StaticPrefs_security.h" @7
- include "mozilla/dom/ClientIPCTypes.h" @8
- include "mozilla/dom/LoadedOriginSet.h" @9
- include "mozilla/dom/ProcessIsolation.h" @10
- include "mozilla/dom/RemoteType.h" @11
- include "mozilla/ipc/PBackgroundSharedTypes.h" @12
- include "mozilla/net/MozURL.h" @13
- function_definition ClientIsValidPrincipalInfo @21-40
- function_definition IsValidClientOpConstructorArgs @42-92
- function_definition ClientIsValidCreationURL @94-170

### dom/clients/manager/ClientValidation.h

Blob: `cc29c05a3a18c1ead0679378feecb40498c3cf91`. Grammar: cpp. Status: syntax-clean.

- include "nsStringFwd.h" @7
- class_specifier PrincipalInfo @12-12
- class_specifier ClientOpConstructorArgs @17-17
- class_specifier LoadedOriginSet @18-18

### dom/closewatcher/CloseWatcher.cpp

Blob: `26973f0d9eabaf9efce94f6009fa15d988fa167f`. Grammar: cpp. Status: contains-errors.

- include "CloseWatcher.h" @5
- include "mozilla/RefPtr.h" @7
- include "mozilla/dom/CloseWatcherBinding.h" @8
- include "mozilla/dom/CloseWatcherManager.h" @9
- include "mozilla/dom/Event.h" @10
- include "mozilla/dom/EventBinding.h" @11
- include "mozilla/dom/ToJSValue.h" @12
- include "mozilla/dom/WindowContext.h" @13
- include "nsGlobalWindowInner.h" @14
- function_definition Constructor @20-45
- function_definition WrapObject @47-50
- function_definition RequestToClose @53-95
- function_definition Close @98-115
- function_definition AddToWindowsCloseWatcherManager @117-122
- function_definition Destroy @124-129
- function_definition IsActive @131-140
- function_definition RunAbortAlgorithm @142-142

### dom/closewatcher/CloseWatcher.h

Blob: `be8b66f266700e40389a1a50d402b54af64dde7e`. Grammar: cpp. Status: contains-errors.

- include "mozilla/DOMEventTargetHelper.h" @8
- include "mozilla/dom/CloseWatcherBinding.h" @9
- include "mozilla/dom/DebuggerNotificationBinding.h" @10
- class_specifier CloseWatcher @14-72
- function_definition GetParentObject @16-18
- function_definition GetDebuggerNotificationType @20-23
- function_definition CloseWatcher @35-36
- function_definition RequestClose @40-40
- function_definition SetEnabled @57-57
- function_definition DisconnectFromOwner @59-62
- function_definition ~CloseWatcher @65-65

### dom/closewatcher/CloseWatcherManager.cpp

Blob: `91e616948661028ddf4966325ae36b3831e414f7`. Grammar: cpp. Status: contains-errors.

- include "CloseWatcherManager.h" @5
- include "CloseWatcher.h" @7
- function_definition NotifyUserInteraction @17-25
- function_definition CanGrow @27-29
- function_definition ProcessCloseRequest @32-50
- function_definition Add @54-65
- function_definition Remove @68-78
- function_definition Contains @80-87

### dom/closewatcher/CloseWatcherManager.h

Blob: `29b4b4cb22e08aa370b23926b863583a63c4b675`. Grammar: cpp. Status: contains-errors.

- include "nsCycleCollectionParticipant.h" @8
- include "nsISupportsImpl.h" @9
- include "nsTObserverArray.h" @10
- class_specifier CloseWatcher @14-14
- class_specifier CloseWatcherManager @19-46
- function_definition CloseWatcherManager @21-21
- function_definition IsEmpty @38-38
- function_definition ~CloseWatcherManager @41-41

### dom/commandhandler/ControllerCommand.h

Blob: `ae09cce4a24f26cc8b29ee618cbf7f35f5cdfb71`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @8
- include "nsISupportsImpl.h" @9
- include "nsStringFwd.h" @10
- class_specifier nsISupports @11-11
- class_specifier nsICommandParams @12-12
- class_specifier ControllerCommand @16-54
- function_definition ~ControllerCommand @53-53

### dom/commandhandler/nsBaseCommandController.cpp

Blob: `2413c20c33a295624a9bbdfbaf676cca1e66b330`. Grammar: cpp. Status: syntax-clean.

- include "nsBaseCommandController.h" @5
- include "mozilla/ControllerCommand.h" @7
- include "nsControllerCommandTable.h" @8
- include "nsIWeakReferenceUtils.h" @9
- include "nsString.h" @10
- function_definition nsBaseCommandController @15-17
- function_definition ~nsBaseCommandController @19-19
- function_definition IsCommandEnabled @25-34
- function_definition SupportsCommand @36-43
- function_definition DoCommand @45-57
- function_definition DoCommandWithParams @59-72
- function_definition GetCommandStateWithParams @74-86
- function_definition OnEvent @88-92
- function_definition GetSupportedCommands @94-99
- function_definition CreateWindowController @101-105
- function_definition CreateEditorController @107-111
- function_definition CreateEditingController @113-117
- function_definition CreateHTMLEditorController @119-123
- function_definition CreateHTMLEditorDocStateController @125-129

### dom/commandhandler/nsBaseCommandController.h

Blob: `a9e981e52c36833c5c62e5c4ec8ed84fb4d24c69`. Grammar: cpp. Status: contains-errors.

- include "nsIController.h" @8
- include "nsIWeakReferenceUtils.h" @9
- class_specifier nsControllerCommandTable @14-14
- class_specifier nsBaseCommandController @18-46
- function_definition SetContext @22-24
- function_definition ToSupports @48-50

### dom/commandhandler/nsCommandManager.cpp

Blob: `3dd9837c74fd4272f7bfa3c52db3e15d4d2f584c`. Grammar: cpp. Status: contains-errors.

- include "nsCommandManager.h" @5
- include "nsCOMArray.h" @7
- include "nsContentUtils.h" @8
- include "nsIController.h" @9
- include "nsIControllers.h" @10
- include "nsIObserver.h" @11
- include "nsPIDOMWindow.h" @12
- include "nsPIWindowRoot.h" @13
- include "nsServiceManagerUtils.h" @14
- include "nsString.h" @15
- function_definition nsCommandManager @17-20
- function_definition ~nsCommandManager @22-22
- function_definition CommandStatusChanged @49-63
- function_definition AddCommandObserver @69-89
- function_definition RemoveCommandObserver @91-106
- function_definition IsCommandSupported @108-119
- function_definition IsCommandEnabled @121-132
- function_definition IsCommandEnabled @134-146
- function_definition GetCommandState @148-169
- function_definition DoCommand @171-190
- function_definition GetControllerForCommand @192-234

### dom/commandhandler/nsCommandManager.h

Blob: `4b377093a087b888914d47de26433c3294f5b1f2`. Grammar: cpp. Status: contains-errors.

- include "nsClassHashtable.h" @8
- include "nsCycleCollectionParticipant.h" @9
- include "nsICommandManager.h" @10
- include "nsString.h" @11
- include "nsWeakReference.h" @12
- class_specifier nsIController @14-14
- class_specifier nsCOMArray @16-16
- class_specifier nsCommandManager @18-56
- function_definition nsCommandManager @23-23
- function_definition AsCommandManager @58-60
- function_definition AsCommandManager @62-64

### dom/commandhandler/nsCommandParams.cpp

Blob: `644dab5d838dd6e42bac816d32d1e846c1c11ce7`. Grammar: cpp. Status: contains-errors.

- include "nsCommandParams.h" @5
- include <new> @7
- include "nsCRT.h" @9
- include "nscore.h" @10
- function_definition nsCommandParams @16-16
- function_definition ~nsCommandParams @18-18
- function_definition GetValueType @20-47
- function_definition GetBooleanValue @49-56
- function_definition GetBool @58-60
- function_definition GetLongValue @62-69
- function_definition GetInt @71-73
- function_definition GetDoubleValue @75-82
- function_definition GetDouble @84-86
- function_definition GetStringValue @88-91
- function_definition GetString @93-98
- function_definition GetCStringValue @100-103
- function_definition GetCString @105-110
- function_definition GetISupportsValue @112-124
- function_definition GetISupports @126-130
- function_definition SetBooleanValue @132-135
- function_definition SetBool @137-140
- function_definition SetLongValue @142-145
- function_definition SetInt @147-150
- function_definition SetDoubleValue @152-155
- function_definition SetDouble @157-160
- function_definition SetStringValue @162-165
- function_definition SetString @167-172
- function_definition SetCStringValue @174-177
- function_definition SetCString @179-184
- function_definition SetISupportsValue @186-189
- function_definition SetISupports @191-195
- function_definition RemoveValue @197-201

### dom/commandhandler/nsCommandParams.h

Blob: `0cb9b5fd218d38558a39d7297557f8888e416a76`. Grammar: cpp. Status: contains-errors.

- include "mozilla/ErrorResult.h" @8
- include "nsCOMPtr.h" @9
- include "nsICommandParams.h" @10
- include "nsString.h" @11
- include "nsTHashMap.h" @12
- class_specifier nsCommandParams @14-74
- function_definition GetBool @25-28
- function_definition GetInt @30-33
- function_definition GetDouble @35-38
- function_definition GetISupports @43-46
- function_definition GenericGet @59-68
- function_definition AsCommandParams @76-78
- function_definition AsCommandParams @80-82

### dom/commandhandler/nsControllerCommandTable.cpp

Blob: `94e595140695c3aa1ba3835fa5fe36071fd6f658`. Grammar: cpp. Status: syntax-clean.

- include "nsControllerCommandTable.h" @5
- include "mozilla/ClearOnShutdown.h" @7
- include "mozilla/ControllerCommand.h" @8
- include "mozilla/EditorController.h" @9
- include "mozilla/HTMLEditorController.h" @10
- include "mozilla/StaticPtr.h" @11
- include "nsGlobalWindowCommands.h" @12
- include "nsString.h" @13
- function_definition RegisterCommand @17-21
- function_definition UnregisterCommand @23-27
- function_definition FindCommandHandler @29-32
- function_definition IsCommandEnabled @34-44
- function_definition GetSupportedCommands @46-49
- function_definition EnsureCommandTableWithCommands @53-63
- function_definition EditorCommandTable @66-70
- function_definition EditingCommandTable @73-77
- function_definition HTMLEditorCommandTable @80-84
- function_definition HTMLEditorDocStateCommandTable @87-92
- function_definition WindowCommandTable @95-99

### dom/commandhandler/nsControllerCommandTable.h

Blob: `a1320e392e94f94523f474223e774a88e058ff47`. Grammar: cpp. Status: syntax-clean.

- include "nsHashKeys.h" @8
- include "nsISupportsImpl.h" @9
- include "nsRefPtrHashtable.h" @10
- class_specifier ControllerCommand @13-13
- class_specifier nsICommandParams @16-16
- class_specifier nsControllerCommandTable @18-50
- function_definition nsControllerCommandTable @20-20
- function_definition SupportsCommand @34-36
- function_definition MakeImmutable @37-37
- function_definition ~nsControllerCommandTable @41-41

### dom/compression/BaseAlgorithms.cpp

Blob: `d5fe06684d682534f643c42f8733bd8c34a6101a`. Grammar: cpp. Status: contains-errors.

- include "BaseAlgorithms.h" @5
- include "mozilla/dom/BufferSourceBinding.h" @7
- include "mozilla/dom/BufferSourceBindingFwd.h" @8
- include "mozilla/dom/TransformStreamDefaultController.h" @9
- include "mozilla/dom/UnionTypes.h" @10
- function_definition TransformCallbackImpl @18-43
- function_definition FlushCallbackImpl @49-62
- function_definition Enqueue @64-75
- function_definition TransformCallbackImpl @81-120
- function_definition FlushCallbackImpl @126-150
- function_definition Enqueue @152-163

### dom/compression/BaseAlgorithms.h

Blob: `1deb2b1190d52fd134b613d6b2b66fb00e8cd6e7`. Grammar: cpp. Status: contains-errors.

- include "js/TypeDecls.h" @8
- include "mozilla/dom/TransformerCallbackHelpers.h" @9
- enum_specifier Flush @16-16
- class_specifier CompressionStreamAlgorithms @18-55
- function_definition ~CompressionStreamAlgorithms @40-40
- class_specifier DecompressionStreamAlgorithms @57-102
- function_definition ~DecompressionStreamAlgorithms @79-79

### dom/compression/CompressionStream.cpp

Blob: `5894c7d456f5c666b7afca9ebd8ec0c19af6ec4e`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/CompressionStream.h" @5
- include "FormatBrotli.h" @7
- include "FormatZlib.h" @8
- include "js/TypeDecls.h" @9
- include "mozilla/dom/CompressionStreamBinding.h" @10
- include "mozilla/dom/ReadableStream.h" @11
- include "mozilla/dom/TextDecoderStream.h" @12
- include "mozilla/dom/TransformStream.h" @13
- include "mozilla/dom/WritableStream.h" @14
- function_definition CreateCompressionStreamAlgorithms @28-45
- function_definition CompressionStream @47-49
- function_definition ~CompressionStream @51-51
- function_definition WrapObject @53-56
- function_definition Constructor @59-92
- function_definition Readable @94-96
- function_definition Writable @98-100

### dom/compression/CompressionStream.h

Blob: `6e02c366f4e9492eb036061e7aa9432563d79cd5`. Grammar: cpp. Status: contains-errors.

- include "js/TypeDecls.h" @8
- include "mozilla/Attributes.h" @9
- include "mozilla/ErrorResult.h" @10
- include "mozilla/dom/BindingDeclarations.h" @11
- include "nsCycleCollectionParticipant.h" @12
- include "nsWrapperCache.h" @13
- class_specifier ReadableStream @17-17
- class_specifier WritableStream @18-18
- class_specifier TransformStream @19-19
- enum_specifier CompressionFormat @21-21
- class_specifier CompressionStream @23-53
- function_definition GetParentObject @35-35

### dom/compression/DecompressionStream.cpp

Blob: `e5d05a7aecfbca5cbde4e60d5fa1e6067e132ec5`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/DecompressionStream.h" @5
- include "BaseAlgorithms.h" @7
- include "FormatBrotli.h" @8
- include "FormatZlib.h" @9
- include "FormatZstd.h" @10
- include "js/TypeDecls.h" @11
- include "mozilla/StaticPrefs_dom.h" @12
- include "mozilla/dom/CompressionStreamBinding.h" @13
- include "mozilla/dom/DecompressionStreamBinding.h" @14
- include "mozilla/dom/ReadableStream.h" @15
- include "mozilla/dom/TextDecoderStream.h" @16
- include "mozilla/dom/TransformStream.h" @17
- include "mozilla/dom/UnionTypes.h" @18
- include "mozilla/dom/WritableStream.h" @19
- function_definition CreateDecompressionStreamAlgorithms @28-47
- function_definition ~DecompressionStream @61-61
- function_definition WrapObject @63-66
- function_definition Constructor @69-107
- function_definition Readable @109-111
- function_definition Writable @113-115

### dom/compression/DecompressionStream.h

Blob: `38185b486cc5ecef8ca5b977f112766cac03d70f`. Grammar: cpp. Status: contains-errors.

- include "js/TypeDecls.h" @8
- include "mozilla/Attributes.h" @9
- include "mozilla/ErrorResult.h" @10
- include "mozilla/dom/BindingDeclarations.h" @11
- include "nsCycleCollectionParticipant.h" @12
- include "nsWrapperCache.h" @13
- class_specifier ReadableStream @17-17
- class_specifier WritableStream @18-18
- class_specifier TransformStream @19-19
- enum_specifier CompressionFormat @21-21
- class_specifier DecompressionStream @23-53
- function_definition GetParentObject @35-35

### dom/compression/FormatBrotli.cpp

Blob: `86f33ce31143e859e464aff0e4e191c626e64844`. Grammar: cpp. Status: contains-errors.

- include "FormatBrotli.h" @5
- include <memory> @7
- include "BaseAlgorithms.h" @9
- include "brotli/decode.h" @10
- include "brotli/encode.h" @11
- include "mozilla/dom/TransformStreamDefaultController.h" @12
- function_definition intoBrotliOp @34-47
- function_definition Create @49-55
- function_definition Init @57-64
- function_definition Compress @71-114
- function_definition BrotliDeleter::operator() @116-119
- function_definition Create @121-127
- function_definition Init @129-143
- function_definition Decompress @150-208
- function_definition BrotliDeleter::operator() @210-213

### dom/compression/FormatBrotli.h

Blob: `c91489e8573f44feceac13cc90d572c025a552c9`. Grammar: cpp. Status: contains-errors.

- include "BaseAlgorithms.h" @8
- struct_specifier BrotliDecoderStateStruct @10-10
- struct_specifier BrotliEncoderStateStruct @11-11
- class_specifier BrotliCompressionStreamAlgorithms @18-46
- function_definition BrotliCompressionStreamAlgorithms @28-28
- function_definition ~BrotliCompressionStreamAlgorithms @39-39
- struct_specifier BrotliDeleter @41-43
- class_specifier BrotliDecompressionStreamAlgorithms @48-79
- function_definition BrotliDecompressionStreamAlgorithms @59-59
- function_definition ~BrotliDecompressionStreamAlgorithms @72-72
- struct_specifier BrotliDeleter @74-76

### dom/compression/FormatZlib.cpp

Blob: `a05765e4b27ac551b84f422bc1efa2337b69a413`. Grammar: cpp. Status: contains-errors.

- include "FormatZlib.h" @5
- include "BaseAlgorithms.h" @7
- include "mozilla/dom/CompressionStreamBinding.h" @8
- include "mozilla/dom/TransformStreamDefaultController.h" @9
- function_definition intoZLibFlush @31-44
- function_definition ZLibWindowBits @48-69
- function_definition Create @71-77
- function_definition Init @79-89
- function_definition Compress @94-171
- function_definition ~ZLibCompressionStreamAlgorithms @173-175
- function_definition Create @177-183
- function_definition Init @185-193
- function_definition Decompress @200-307
- function_definition ~ZLibDecompressionStreamAlgorithms @309-311

### dom/compression/FormatZlib.h

Blob: `03f8a3c964ba73d80457e9e59868c384984cc4b5`. Grammar: cpp. Status: contains-errors.

- include "BaseAlgorithms.h" @8
- include "mozilla/dom/TransformerCallbackHelpers.h" @9
- include "zlib.h" @10
- enum_specifier CompressionFormat @16-16
- class_specifier ZLibCompressionStreamAlgorithms @21-45
- function_definition ZLibCompressionStreamAlgorithms @31-31
- class_specifier ZLibDecompressionStreamAlgorithms @47-73
- function_definition ZLibDecompressionStreamAlgorithms @57-57

### dom/compression/FormatZstd.cpp

Blob: `bd33994e297f2b885521fde710077b8023a93bf5`. Grammar: cpp. Status: contains-errors.

- include "FormatZstd.h" @5
- include "BaseAlgorithms.h" @7
- include "mozilla/dom/TransformStreamDefaultController.h" @8
- include "zstd/zstd.h" @9
- function_definition Create @22-28
- function_definition Init @30-42
- function_definition Decompress @49-100
- function_definition ~ZstdDecompressionStreamAlgorithms @102-107

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [8ed4754b-230f-450c-932d-bd7e1af871c2.md](8ed4754b-230f-450c-932d-bd7e1af871c2.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `14b7546512cd7c45752bef238c09f378bb4cb9bad76f1ab5e8c4ea6b890fca9b`.
