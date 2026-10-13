<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["gfx/skia/skia/src/sksl/ir/SkSLType.h", "gfx/skia/skia/src/sksl/ir/SkSLTypeReference.cpp", "gfx/skia/skia/src/sksl/ir/SkSLTypeReference.h", "gfx/skia/skia/src/sksl/ir/SkSLVarDeclarations.cpp", "gfx/skia/skia/src/sksl/ir/SkSLVarDeclarations.h", "gfx/skia/skia/src/sksl/ir/SkSLVariable.cpp", "gfx/skia/skia/src/sksl/ir/SkSLVariable.h", "gfx/skia/skia/src/sksl/ir/SkSLVariableReference.cpp", "gfx/skia/skia/src/sksl/ir/SkSLVariableReference.h", "gfx/skia/skia/src/sksl/lex/DFA.h", "gfx/skia/skia/src/sksl/lex/DFAState.h", "gfx/skia/skia/src/sksl/lex/LexUtil.h", "gfx/skia/skia/src/sksl/lex/Main.cpp", "gfx/skia/skia/src/sksl/lex/NFA.cpp", "gfx/skia/skia/src/sksl/lex/NFA.h", "gfx/skia/skia/src/sksl/lex/NFAState.h", "gfx/skia/skia/src/sksl/lex/NFAtoDFA.h", "gfx/skia/skia/src/sksl/lex/RegexNode.cpp", "gfx/skia/skia/src/sksl/lex/RegexNode.h", "gfx/skia/skia/src/sksl/lex/RegexParser.cpp", "gfx/skia/skia/src/sksl/lex/RegexParser.h", "gfx/skia/skia/src/sksl/lex/TransitionTable.cpp", "gfx/skia/skia/src/sksl/lex/TransitionTable.h", "gfx/skia/skia/src/sksl/spirv.h", "gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePlayer.cpp", "gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePlayer.h", "gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePriv.cpp", "gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePriv.h", "gfx/skia/skia/src/sksl/tracing/SkSLTraceHook.cpp", "gfx/skia/skia/src/sksl/tracing/SkSLTraceHook.h", "gfx/skia/skia/src/sksl/transform/SkSLAddConstToVarModifiers.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadFunctions.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadGlobalVariables.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadLocalVariables.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateEmptyStatements.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateUnnecessaryBraces.cpp", "gfx/skia/skia/src/sksl/transform/SkSLEliminateUnreachableCode.cpp", "gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinFunctions.cpp", "gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinStructs.cpp", "gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinVariables.cpp", "gfx/skia/skia/src/sksl/transform/SkSLHoistSwitchVarDeclarationsAtTopLevel.cpp", "gfx/skia/skia/src/sksl/transform/SkSLProgramWriter.h", "gfx/skia/skia/src/sksl/transform/SkSLRenamePrivateSymbols.cpp", "gfx/skia/skia/src/sksl/transform/SkSLReplaceConstVarsWithLiterals.cpp", "gfx/skia/skia/src/sksl/transform/SkSLReplaceSplatCastsWithSwizzles.cpp", "gfx/skia/skia/src/sksl/transform/SkSLRewriteIndexedSwizzle.cpp", "gfx/skia/skia/src/sksl/transform/SkSLTransform.cpp", "gfx/skia/skia/src/sksl/transform/SkSLTransform.h", "gfx/skia/skia/src/text/GlyphRun.cpp", "gfx/skia/skia/src/text/GlyphRun.h", "gfx/skia/skia/src/text/SlugFromBuffer.cpp", "gfx/skia/skia/src/text/StrikeForGPU.cpp", "gfx/skia/skia/src/text/StrikeForGPU.h", "gfx/skia/skia/src/text/gpu/DistanceFieldAdjustTable.cpp", "gfx/skia/skia/src/text/gpu/DistanceFieldAdjustTable.h", "gfx/skia/skia/src/text/gpu/GlyphUtils.h", "gfx/skia/skia/src/text/gpu/GlyphVector.cpp", "gfx/skia/skia/src/text/gpu/GlyphVector.h", "gfx/skia/skia/src/text/gpu/SDFMaskFilter.cpp", "gfx/skia/skia/src/text/gpu/SDFMaskFilter.h", "gfx/skia/skia/src/text/gpu/SkChromeRemoteGlyphCache.cpp", "gfx/skia/skia/src/text/gpu/Slug.cpp", "gfx/skia/skia/src/text/gpu/SlugImpl.cpp", "gfx/skia/skia/src/text/gpu/SlugImpl.h", "gfx/skia/skia/src/text/gpu/StrikeCache.cpp", "gfx/skia/skia/src/text/gpu/StrikeCache.h", "gfx/skia/skia/src/text/gpu/SubRunAllocator.cpp", "gfx/skia/skia/src/text/gpu/SubRunAllocator.h", "gfx/skia/skia/src/text/gpu/SubRunContainer.cpp", "gfx/skia/skia/src/text/gpu/SubRunContainer.h", "gfx/skia/skia/src/text/gpu/SubRunControl.cpp", "gfx/skia/skia/src/text/gpu/SubRunControl.h", "gfx/skia/skia/src/text/gpu/TextBlob.cpp", "gfx/skia/skia/src/text/gpu/TextBlob.h", "gfx/skia/skia/src/text/gpu/TextBlobRedrawCoordinator.cpp", "gfx/skia/skia/src/text/gpu/TextBlobRedrawCoordinator.h", "gfx/skia/skia/src/text/gpu/VertexFiller.cpp", "gfx/skia/skia/src/text/gpu/VertexFiller.h", "gfx/skia/skia/src/utils/SkBitSet.h", "gfx/skia/skia/src/utils/SkCallableTraits.h", "gfx/skia/skia/src/utils/SkCamera.cpp", "gfx/skia/skia/src/utils/SkCanvasStack.cpp", "gfx/skia/skia/src/utils/SkCanvasStack.h", "gfx/skia/skia/src/utils/SkCanvasStateUtils.cpp", "gfx/skia/skia/src/utils/SkCharToGlyphCache.cpp", "gfx/skia/skia/src/utils/SkCharToGlyphCache.h", "gfx/skia/skia/src/utils/SkClipStackUtils.cpp", "gfx/skia/skia/src/utils/SkClipStackUtils.h", "gfx/skia/skia/src/utils/SkCustomTypeface.cpp", "gfx/skia/skia/src/utils/SkDashPath.cpp", "gfx/skia/skia/src/utils/SkDashPathPriv.h", "gfx/skia/skia/src/utils/SkEventTracer.cpp", "gfx/skia/skia/src/utils/SkFloatToDecimal.cpp", "gfx/skia/skia/src/utils/SkFloatToDecimal.h", "gfx/skia/skia/src/utils/SkFloatUtils.h", "gfx/skia/skia/src/utils/SkGetExecutablePath.h", "gfx/skia/skia/src/utils/SkGetExecutablePath_linux.cpp", "gfx/skia/skia/src/utils/SkGetExecutablePath_mac.cpp", "gfx/skia/skia/src/utils/SkGetExecutablePath_win.cpp", "gfx/skia/skia/src/utils/SkJSONWriter.cpp", "gfx/skia/skia/src/utils/SkJSONWriter.h", "gfx/skia/skia/src/utils/SkMatrix22.cpp", "gfx/skia/skia/src/utils/SkMatrix22.h", "gfx/skia/skia/src/utils/SkMultiPictureDocument.cpp", "gfx/skia/skia/src/utils/SkMultiPictureDocumentPriv.h", "gfx/skia/skia/src/utils/SkNWayCanvas.cpp", "gfx/skia/skia/src/utils/SkNullCanvas.cpp", "gfx/skia/skia/src/utils/SkOSPath.cpp", "gfx/skia/skia/src/utils/SkOSPath.h", "gfx/skia/skia/src/utils/SkOrderedFontMgr.cpp", "gfx/skia/skia/src/utils/SkPaintFilterCanvas.cpp", "gfx/skia/skia/src/utils/SkParse.cpp", "gfx/skia/skia/src/utils/SkParseColor.cpp", "gfx/skia/skia/src/utils/SkParsePath.cpp", "gfx/skia/skia/src/utils/SkPatchUtils.cpp", "gfx/skia/skia/src/utils/SkPatchUtils.h", "gfx/skia/skia/src/utils/SkPolyUtils.cpp", "gfx/skia/skia/src/utils/SkPolyUtils.h", "gfx/skia/skia/src/utils/SkShaderUtils.cpp", "gfx/skia/skia/src/utils/SkShaderUtils.h", "gfx/skia/skia/src/utils/SkShadowTessellator.cpp", "gfx/skia/skia/src/utils/SkShadowTessellator.h", "gfx/skia/skia/src/utils/SkShadowUtils.cpp", "gfx/skia/skia/src/utils/SkTextUtils.cpp", "gfx/skia/skia/src/utils/mac/SkCGBase.h", "gfx/skia/skia/src/utils/mac/SkCGGeometry.h", "gfx/skia/skia/src/utils/mac/SkCTFont.cpp", "gfx/skia/skia/src/utils/mac/SkCTFont.h", "gfx/skia/skia/src/utils/mac/SkCTFontCreateExactCopy.cpp", "gfx/skia/skia/src/utils/mac/SkCTFontCreateExactCopy.h", "gfx/skia/skia/src/utils/mac/SkCreateCGImageRef.cpp", "gfx/skia/skia/src/utils/mac/SkUniqueCFRef.h", "gfx/skia/skia/src/utils/win/SkAutoCoInitialize.cpp", "gfx/skia/skia/src/utils/win/SkAutoCoInitialize.h", "gfx/skia/skia/src/utils/win/SkDWrite.cpp", "gfx/skia/skia/src/utils/win/SkDWrite.h", "gfx/skia/skia/src/utils/win/SkDWriteFontFileStream.cpp", "gfx/skia/skia/src/utils/win/SkDWriteFontFileStream.h", "gfx/skia/skia/src/utils/win/SkDWriteGeometrySink.cpp", "gfx/skia/skia/src/utils/win/SkDWriteGeometrySink.h", "gfx/skia/skia/src/utils/win/SkDWriteNTDDI_VERSION.h", "gfx/skia/skia/src/utils/win/SkHRESULT.cpp", "gfx/skia/skia/src/utils/win/SkHRESULT.h", "gfx/skia/skia/src/utils/win/SkIStream.cpp", "gfx/skia/skia/src/utils/win/SkIStream.h", "gfx/skia/skia/src/utils/win/SkObjBase.h", "gfx/skia/skia/src/utils/win/SkTScopedComPtr.h", "gfx/src/AAStroke.h", "gfx/src/AppUnits.h", "gfx/src/ArrayView.h"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/gfx native and TypeScript syntax map 89

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### gfx/skia/skia/src/sksl/ir/SkSLType.h

Blob: `9ab4feff76b272861ad1b3970d9b58027bb51662`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @11
- include "include/core/SkTypes.h" @12
- include "include/private/base/SkTArray.h" @13
- include "src/sksl/SkSLDefines.h" @14
- include "src/sksl/SkSLPosition.h" @15
- include "src/sksl/ir/SkSLIRNode.h" @16
- include "src/sksl/ir/SkSLLayout.h" @17
- include "src/sksl/ir/SkSLModifierFlags.h" @18
- include "src/sksl/ir/SkSLSymbol.h" @19
- include "src/sksl/spirv.h" @20
- include <cmath> @22
- include <cstddef> @23
- include <cstdint> @24
- include <cstring> @25
- include <memory> @26
- include <string> @27
- include <string_view> @28
- include <tuple> @29
- include <compare> @34
- class_specifier Context @39-39
- class_specifier Expression @40-40
- class_specifier SymbolTable @41-41
- class_specifier Type @42-42
- struct_specifier CoercionCost @44-75
- function_definition Free @45-45
- function_definition Normal @46-46
- function_definition Narrowing @47-47
- function_definition Impossible @48-48
- function_definition isPossible @50-52
- function_definition operator+ @55-60
- function_definition operator< @62-65
- function_definition operator<= @67-70
- struct_specifier Field @80-95
- function_definition Field @81-86
- class_specifier Type @100-679
- enum_specifier TypeKind @107-126
- enum_specifier NumberKind @128-134
- enum_specifier TextureAccess @136-141
- function_definition Type @143-143
- function_definition is @211-213
- function_definition (anonymous) @216-219
- function_definition (anonymous) @222-225
- function_definition isBuiltin @236-238
- function_definition displayName @240-242
- function_definition description @244-246
- function_definition isAllowedInES2 @252-254
- function_definition isAllowedInUniform @263-267
- function_definition (anonymous) @270-272
- function_definition matches @275-277
- function_definition abbreviatedName @282-284
- function_definition typeKind @289-291
- function_definition numberKind @296-298
- function_definition isBoolean @303-305
- function_definition isNumber @310-319
- function_definition isFloat @324-326
- function_definition isSigned @331-333
- function_definition isUnsigned @338-340
- function_definition isInteger @345-353
- function_definition isOpaque @359-372
- function_definition isStorageTexture @377-379
- function_definition priority @385-388
- function_definition canCoerceTo @394-396
- function_definition (anonymous) @410-412
- function_definition (anonymous) @417-419
- function_definition (anonymous) @425-428
- function_definition columns @435-438
- function_definition rows @444-447
- function_definition minimumValue @450-453
- function_definition maximumValue @455-458
- function_definition slotCount @463-465
- function_definition (anonymous) @471-473
- function_definition fields @475-477
- function_definition coercibleTypes @482-485
- function_definition dimensions @487-490
- function_definition isDepth @492-495
- function_definition isArrayedTexture @497-500
- function_definition isVoid @502-504
- function_definition isGeneric @506-508
- function_definition isSampler @510-512
- function_definition isAtomic @514-516
- function_definition isScalar @518-520
- function_definition isLiteral @522-524
- function_definition (anonymous) @526-528
- function_definition isVector @530-532
- function_definition isMatrix @534-536
- function_definition isArray @538-540
- function_definition isUnsizedArray @542-544
- function_definition isStruct @546-548
- function_definition isInterfaceBlock @550-552
- function_definition isEffectChild @556-560
- function_definition isMultisampled @562-565
- function_definition textureAccess @567-570
- function_definition hasPrecision @572-574
- function_definition highPrecision @576-578
- function_definition bitWidth @580-582
- function_definition isOrContainsArray @584-586
- function_definition isOrContainsUnsizedArray @588-590
- function_definition isOrContainsAtomic @592-594
- function_definition isOrContainsBool @596-598
- function_definition Type @649-654
- function_definition isInRootSymbolTable @665-667
- function_definition structNestingDepth @670-672

### gfx/skia/skia/src/sksl/ir/SkSLTypeReference.cpp

Blob: `662671a9028851fd9d47ceba266cae0ca9e65af8`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/ir/SkSLTypeReference.h" @8
- include "include/core/SkTypes.h" @10
- include "src/sksl/SkSLErrorReporter.h" @11
- include "src/sksl/SkSLProgramSettings.h" @12
- function_definition VerifyType @16-28
- function_definition Convert @30-35
- function_definition Make @37-42

### gfx/skia/skia/src/sksl/ir/SkSLTypeReference.h

Blob: `4055634a0f145ff3541125c19271af9851f03b74`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLBuiltinTypes.h" @11
- include "src/sksl/SkSLContext.h" @12
- include "src/sksl/SkSLPosition.h" @13
- include "src/sksl/ir/SkSLExpression.h" @14
- include "src/sksl/ir/SkSLIRNode.h" @15
- include "src/sksl/ir/SkSLType.h" @16
- include <cstdint> @18
- include <memory> @19
- include <string> @20
- enum_specifier OperatorPrecedence @24-24
- class_specifier TypeReference @30-71
- function_definition TypeReference @34-35
- function_definition (anonymous) @51-53
- function_definition description @55-57
- function_definition clone @59-61
- function_definition TypeReference @64-66

### gfx/skia/skia/src/sksl/ir/SkSLVarDeclarations.cpp

Blob: `1959a00e9a82b66e9a58f124476358e18981685d`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/ir/SkSLVarDeclarations.h" @8
- include "include/core/SkSpan.h" @10
- include "include/private/base/SkTo.h" @11
- include "src/base/SkEnumBitMask.h" @12
- include "src/sksl/SkSLAnalysis.h" @13
- include "src/sksl/SkSLBuiltinTypes.h" @14
- include "src/sksl/SkSLCompiler.h" @15
- include "src/sksl/SkSLContext.h" @16
- include "src/sksl/SkSLErrorReporter.h" @17
- include "src/sksl/SkSLPosition.h" @18
- include "src/sksl/SkSLProgramKind.h" @19
- include "src/sksl/SkSLProgramSettings.h" @20
- include "src/sksl/SkSLString.h" @21
- include "src/sksl/ir/SkSLLayout.h" @22
- include "src/sksl/ir/SkSLModifierFlags.h" @23
- include "src/sksl/ir/SkSLModifiers.h" @24
- include "src/sksl/ir/SkSLSymbolTable.h" @25
- include "src/sksl/ir/SkSLType.h" @26
- include <string_view> @28
- function_definition check_valid_uniform_type @33-78
- function_definition description @82-94
- function_definition ErrorCheck @96-293
- function_definition ErrorCheckAndCoerce @295-367
- function_definition Convert @369-393
- function_definition Convert @395-433
- function_definition Make @435-466

### gfx/skia/skia/src/sksl/ir/SkSLVarDeclarations.h

Blob: `a9cc40569d6a66f5645942343fce61b861745882`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "src/sksl/ir/SkSLExpression.h" @12
- include "src/sksl/ir/SkSLIRNode.h" @13
- include "src/sksl/ir/SkSLModifierFlags.h" @14
- include "src/sksl/ir/SkSLProgramElement.h" @15
- include "src/sksl/ir/SkSLStatement.h" @16
- include "src/sksl/ir/SkSLVariable.h" @17
- include <memory> @19
- include <string> @20
- include <string_view> @21
- include <utility> @22
- class_specifier Context @26-26
- struct_specifier Layout @27-27
- struct_specifier Modifiers @28-28
- class_specifier Position @29-29
- class_specifier Type @30-30
- class_specifier VarDeclaration @37-128
- function_definition VarDeclaration @41-49
- function_definition ~VarDeclaration @51-56
- function_definition (anonymous) @90-92
- function_definition var @94-96
- function_definition detachDeadVariable @98-100
- function_definition arraySize @102-104
- function_definition (anonymous) @106-108
- function_definition (anonymous) @110-112
- class_specifier GlobalVarDeclaration @134-169
- function_definition GlobalVarDeclaration @138-143
- function_definition (anonymous) @145-147
- function_definition (anonymous) @149-151
- function_definition (anonymous) @153-155
- function_definition (anonymous) @157-159
- function_definition description @161-163

### gfx/skia/skia/src/sksl/ir/SkSLVariable.cpp

Blob: `19edf4bed32a21f3757118976c1c1ecf39d44fb9`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/ir/SkSLVariable.h" @8
- include "src/base/SkEnumBitMask.h" @10
- include "src/base/SkStringView.h" @11
- include "src/sksl/SkSLCompiler.h" @12
- include "src/sksl/SkSLContext.h" @13
- include "src/sksl/SkSLErrorReporter.h" @14
- include "src/sksl/SkSLIntrinsicList.h" @15
- include "src/sksl/SkSLMangler.h" @16
- include "src/sksl/SkSLProgramSettings.h" @17
- include "src/sksl/ir/SkSLExpression.h" @18
- include "src/sksl/ir/SkSLIRNode.h" @19
- include "src/sksl/ir/SkSLInterfaceBlock.h" @20
- include "src/sksl/ir/SkSLLayout.h" @21
- include "src/sksl/ir/SkSLSymbolTable.h" @22
- include "src/sksl/ir/SkSLVarDeclarations.h" @23
- include <utility> @25
- function_definition ~Variable @31-36
- function_definition ~ExtendedVariable @38-43
- function_definition initialValue @45-48
- function_definition varDeclaration @50-59
- function_definition globalVarDeclaration @61-70
- function_definition setVarDeclaration @72-77
- function_definition setGlobalVarDeclaration @79-82
- function_definition (anonymous) @84-86
- function_definition mangledName @88-90
- function_definition Convert @92-144
- function_definition Make @146-179
- function_definition MakeScratchVariable @181-220

### gfx/skia/skia/src/sksl/ir/SkSLVariable.h

Blob: `31113e969a3e077070d34192b1b1aed895539afe`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "src/sksl/SkSLPosition.h" @12
- include "src/sksl/ir/SkSLIRNode.h" @13
- include "src/sksl/ir/SkSLLayout.h" @14
- include "src/sksl/ir/SkSLModifierFlags.h" @15
- include "src/sksl/ir/SkSLStatement.h" @16
- include "src/sksl/ir/SkSLSymbol.h" @17
- include "src/sksl/ir/SkSLType.h" @18
- include <cstdint> @20
- include <memory> @21
- include <string> @22
- include <string_view> @23
- include <utility> @24
- class_specifier Context @28-28
- class_specifier Expression @29-29
- class_specifier GlobalVarDeclaration @30-30
- class_specifier InterfaceBlock @31-31
- class_specifier Mangler @32-32
- class_specifier SymbolTable @33-33
- class_specifier VarDeclaration @34-34
- enum_specifier VariableStorage @36-41
- class_specifier Variable @48-147
- function_definition Variable @54-60
- struct_specifier ScratchVariable @79-82
- function_definition modifierFlags @89-91
- function_definition modifiersPosition @95-97
- function_definition isBuiltin @99-101
- function_definition storage @103-105
- function_definition detachDeadVarDeclaration @117-120
- function_definition interfaceBlock @125-125
- function_definition setInterfaceBlock @127-127
- function_definition detachDeadInterfaceBlock @129-129
- function_definition mangledName @132-132
- function_definition description @134-137
- class_specifier ExtendedVariable @158-195
- function_definition ExtendedVariable @160-165
- function_definition interfaceBlock @169-171
- function_definition (anonymous) @173-175
- function_definition setInterfaceBlock @177-180
- function_definition detachDeadInterfaceBlock @182-185

### gfx/skia/skia/src/sksl/ir/SkSLVariableReference.cpp

Blob: `3a53e3dded64d6412768c4ced982e98f7ae6c61f`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/ir/SkSLVariableReference.h" @8
- include "src/sksl/ir/SkSLVariable.h" @10
- function_definition VariableReference @14-19
- function_definition description @21-23
- function_definition setRefKind @25-27
- function_definition setVariable @29-31

### gfx/skia/skia/src/sksl/ir/SkSLVariableReference.h

Blob: `a61e333866b44519c2105cb364344d238d7b6148`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "src/sksl/SkSLPosition.h" @12
- include "src/sksl/ir/SkSLExpression.h" @13
- include "src/sksl/ir/SkSLIRNode.h" @14
- include <cstdint> @16
- include <memory> @17
- include <string> @18
- class_specifier Variable @22-22
- enum_specifier OperatorPrecedence @23-23
- enum_specifier VariableRefKind @25-32
- class_specifier VariableReference @41-83
- function_definition Make @51-56
- function_definition VariableReference @58-58
- function_definition (anonymous) @59-59
- function_definition variable @61-63
- function_definition refKind @65-67
- function_definition clone @72-74

### gfx/skia/skia/src/sksl/lex/DFA.h

Blob: `61c3f698b629d5f380f7b61e7d989c7a918fefe1`. Grammar: cpp. Status: syntax-clean.

- include <string> @11
- include <vector> @12
- struct_specifier DFA @17-35
- function_definition DFA @18-22

### gfx/skia/skia/src/sksl/lex/DFAState.h

Blob: `24e208310288c61fbb5bb21ad94b553b97e6b947`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/LexUtil.h" @11
- include <vector> @13
- include <string> @14
- struct_specifier DFAState @16-61
- struct_specifier Label @17-44
- function_definition Label @20-21
- function_definition operator== @23-25
- function_definition operator!= @27-29
- function_definition description @32-42
- function_definition DFAState @46-48
- function_definition DFAState @50-52
- function_definition DFAState @54-54
- struct_specifier hash<DFAState::Label> @64-72
- function_definition operator() @65-71

### gfx/skia/skia/src/sksl/lex/LexUtil.h

Blob: `69b4d6f5d5718e50c71ed384554896db9c39c944`. Grammar: cpp. Status: syntax-clean.

- include <cstdlib> @11

### gfx/skia/skia/src/sksl/lex/Main.cpp

Blob: `e094a77ab6aa4897ca59c528b7376c3f3347c455`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/DFA.h" @8
- include "src/sksl/lex/LexUtil.h" @9
- include "src/sksl/lex/NFA.h" @10
- include "src/sksl/lex/NFAtoDFA.h" @11
- include "src/sksl/lex/RegexNode.h" @12
- include "src/sksl/lex/RegexParser.h" @13
- include "src/sksl/lex/TransitionTable.h" @14
- include <stdio.h> @16
- include <stdlib.h> @17
- include <algorithm> @18
- include <sstream> @19
- include <string> @20
- include <vector> @21
- function_definition writeH @41-102
- function_definition writeCPP @104-184
- function_definition process @186-226
- function_definition main @228-235

### gfx/skia/skia/src/sksl/lex/NFA.cpp

Blob: `1ad9fd3312a267a705f3b263f6a8d59a1ddcfa21`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/NFA.h" @8
- include "src/sksl/lex/LexUtil.h" @10
- include <string> @11
- function_definition match @13-44

### gfx/skia/skia/src/sksl/lex/NFA.h

Blob: `414b6a7fbfeb44d3b5c81f81ef1e68f06003f091`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/NFAState.h" @11
- include "src/sksl/lex/RegexNode.h" @12
- include <string> @14
- include <utility> @15
- include <vector> @16
- struct_specifier NFA @22-56
- function_definition addRegex @27-34
- function_definition addState @39-42

### gfx/skia/skia/src/sksl/lex/NFAState.h

Blob: `e451b3368cc30a3de65452f259b9ffdb4a8bc22d`. Grammar: cpp. Status: syntax-clean.

- include <string> @11
- include <vector> @12
- include "src/sksl/lex/LexUtil.h" @14
- struct_specifier NFAState @16-150
- enum_specifier Kind @17-31
- function_definition NFAState @33-35
- function_definition NFAState @37-40
- function_definition NFAState @42-44
- function_definition NFAState @46-53
- function_definition NFAState @55-58
- function_definition accept @60-80
- function_definition description @83-137

### gfx/skia/skia/src/sksl/lex/NFAtoDFA.h

Blob: `624ab25344ee6cb6bb198ecb0d3ed9039cea0c02`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/DFA.h" @10
- include "src/sksl/lex/DFAState.h" @11
- include "src/sksl/lex/NFA.h" @12
- include "src/sksl/lex/NFAState.h" @13
- include <algorithm> @15
- include <climits> @16
- include <memory> @17
- include <unordered_map> @18
- include <set> @19
- include <vector> @20
- class_specifier NFAtoDFA @32-167
- function_definition NFAtoDFA @37-38
- function_definition convert @43-60
- function_definition getState @66-74
- function_definition add @76-90
- function_definition addTransition @92-101
- function_definition scanState @103-132
- function_definition computeMappings @137-160

### gfx/skia/skia/src/sksl/lex/RegexNode.cpp

Blob: `69b04d4185a9c455e87117d03eb40f42fc4d43f2`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/RegexNode.h" @8
- include "src/sksl/lex/LexUtil.h" @10
- include "src/sksl/lex/NFA.h" @11
- include "src/sksl/lex/NFAState.h" @12
- include <string> @14
- function_definition createStates @16-87
- function_definition description @90-122

### gfx/skia/skia/src/sksl/lex/RegexNode.h

Blob: `c9ca89e5b56fdf3f2ccfa570c89e50c47fefca99`. Grammar: cpp. Status: syntax-clean.

- include <string> @11
- include <utility> @12
- include <vector> @13
- struct_specifier NFA @15-15
- struct_specifier RegexNode @20-77
- enum_specifier Kind @21-31
- function_definition RegexNode @33-34
- function_definition RegexNode @36-39
- function_definition RegexNode @41-48
- function_definition RegexNode @50-53
- function_definition RegexNode @55-59

### gfx/skia/skia/src/sksl/lex/RegexParser.cpp

Blob: `87721b825c0035faa372458fa67b155801e72bd6`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/RegexParser.h" @8
- include "src/sksl/lex/LexUtil.h" @10
- include <stdio.h> @12
- include <stdlib.h> @13
- include <utility> @14
- include <vector> @15
- function_definition parse @17-25
- function_definition peek @27-32
- function_definition expect @34-40
- function_definition pop @42-46
- function_definition term @48-55
- function_definition quantifiedTerm @57-65
- function_definition sequence @67-82
- function_definition escapeSequence @84-92
- function_definition literal @94-105
- function_definition dot @107-110
- function_definition group @112-116
- function_definition setItem @118-134
- function_definition set @136-164
- function_definition regex @166-183

### gfx/skia/skia/src/sksl/lex/RegexParser.h

Blob: `9a1697c96c1e5b1e3090e87fd8bb450a55829473`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/RegexNode.h" @11
- include <stack> @13
- include <string> @14
- class_specifier RegexParser @21-87

### gfx/skia/skia/src/sksl/lex/TransitionTable.cpp

Blob: `3d352fbf6e040a5ef751758b987c0a10c04bd2e9`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/lex/DFA.h" @8
- include "src/sksl/lex/TransitionTable.h" @9
- include <array> @11
- include <algorithm> @12
- include <cassert> @13
- include <cmath> @14
- include <unordered_map> @15
- include <unordered_set> @16
- include <utility> @17
- include <vector> @18
- enum_specifier IndexType @34-37
- struct_specifier IndexEntry @38-41
- struct_specifier CompactEntry @42-45
- struct_specifier FullEntry @46-48
- function_definition add_compact_entry @52-86
- function_definition add_full_entry @88-105
- function_definition WriteTransitionTable @109-241

### gfx/skia/skia/src/sksl/lex/TransitionTable.h

Blob: `08b0a4e83b480969cb801852ce8c841a58dd22cd`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @11
- include <fstream> @12
- struct_specifier DFA @14-14

### gfx/skia/skia/src/sksl/spirv.h

Blob: `22821ed862adcf952af7b7b0acf1cf41e761ff9a`. Grammar: cpp. Status: syntax-clean.

- enum_specifier SpvSourceLanguage_ @62-68
- enum_specifier SpvExecutionModel_ @70-78
- enum_specifier SpvAddressingModel_ @80-84
- enum_specifier SpvMemoryModel_ @86-90
- enum_specifier SpvExecutionMode_ @92-124
- enum_specifier SpvStorageClass_ @126-139
- enum_specifier SpvDim_ @141-149
- enum_specifier SpvSamplerAddressingMode_ @151-157
- enum_specifier SpvSamplerFilterMode_ @159-162
- enum_specifier SpvImageFormat_ @164-205
- enum_specifier SpvImageChannelOrder_ @207-227
- enum_specifier SpvImageChannelDataType_ @229-247
- enum_specifier SpvImageOperandsShift_ @249-258
- enum_specifier SpvImageOperandsMask_ @260-270
- enum_specifier SpvFPFastMathModeShift_ @272-278
- enum_specifier SpvFPFastMathModeMask_ @280-287
- enum_specifier SpvFPRoundingMode_ @289-294
- enum_specifier SpvLinkageType_ @296-299
- enum_specifier SpvAccessQualifier_ @301-305
- enum_specifier SpvFunctionParameterAttribute_ @307-316
- enum_specifier SpvDecoration_ @318-362
- enum_specifier SpvBuiltIn_ @364-406
- enum_specifier SpvSelectionControlShift_ @408-411
- enum_specifier SpvSelectionControlMask_ @413-417
- enum_specifier SpvLoopControlShift_ @419-422
- enum_specifier SpvLoopControlMask_ @424-428
- enum_specifier SpvFunctionControlShift_ @430-435
- enum_specifier SpvFunctionControlMask_ @437-443
- enum_specifier SpvMemorySemanticsShift_ @445-456
- enum_specifier SpvMemorySemanticsMask_ @458-470
- enum_specifier SpvMemoryAccessShift_ @472-476
- enum_specifier SpvMemoryAccessMask_ @478-483
- enum_specifier SpvScope_ @485-491
- enum_specifier SpvGroupOperation_ @493-497
- enum_specifier SpvKernelEnqueueFlags_ @499-503
- enum_specifier SpvKernelProfilingInfoShift_ @505-507
- enum_specifier SpvKernelProfilingInfoMask_ @509-512
- enum_specifier SpvCapability_ @514-571
- enum_specifier SpvOp_ @573-868

### gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePlayer.cpp

Blob: `325a9bd49ecafea06b6a4b57f72832c7e8f71dcc`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/tracing/SkSLDebugTracePlayer.h" @8
- include "src/sksl/tracing/SkSLDebugTracePriv.h" @10
- include <limits.h> @12
- include <algorithm> @13
- include <utility> @14
- function_definition reset @18-47
- function_definition step @49-56
- function_definition stepOver @58-69
- function_definition stepOut @71-82
- function_definition run @84-93
- function_definition tidyState @95-103
- function_definition traceHasCompleted @105-107
- function_definition getCurrentLine @109-112
- function_definition getCurrentLineInStackFrame @114-121
- function_definition atBreakpoint @123-125
- function_definition setBreakpoints @127-129
- function_definition addBreakpoint @131-133
- function_definition removeBreakpoint @135-137
- function_definition getCallStack @139-147
- function_definition getStackDepth @149-152
- function_definition getVariablesForDisplayMask @154-168
- function_definition getLocalVariables @170-180
- function_definition getGlobalVariables @182-187
- function_definition updateVariableWriteTime @189-210
- function_definition execute @212-283

### gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePlayer.h

Blob: `c43e19dfb5b2b1ccb2ba82b02aa5e7307646504d`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/tracing/SkSLDebugTracePriv.h" @10
- include "include/core/SkRefCnt.h" @12
- include "include/core/SkTypes.h" @13
- include "src/utils/SkBitSet.h" @14
- include <cstddef> @16
- include <cstdint> @17
- include <optional> @18
- include <unordered_map> @19
- include <unordered_set> @20
- include <vector> @21
- class_specifier SkSLDebugTracePlayer @28-136
- function_definition (anonymous) @56-56
- function_definition cursor @65-65
- function_definition (anonymous) @84-84
- struct_specifier VariableData @87-91
- struct_specifier StackFrame @113-117
- struct_specifier Slot @118-123

### gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePriv.cpp

Blob: `7f1ba6c01040d49b31161d070dfb0a8b055da0fd`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/tracing/SkSLDebugTracePriv.h" @7
- include "include/core/SkStream.h" @9
- include "include/core/SkTypes.h" @10
- include "src/sksl/ir/SkSLType.h" @11
- include <cstdio> @13
- include <cstring> @14
- include <sstream> @15
- include <string> @16
- function_definition getSlotComponentSuffix @20-38
- function_definition interpretValueBits @40-60
- function_definition slotValueToString @62-75
- function_definition getSlotValue @77-79
- function_definition setTraceCoord @81-83
- function_definition setSource @85-92
- function_definition dump @94-191

### gfx/skia/skia/src/sksl/tracing/SkSLDebugTracePriv.h

Blob: `d5fe9ff95c55395cf4f3bf9382c82c61e59abc82`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPoint.h" @11
- include "include/sksl/SkSLDebugTrace.h" @12
- include "src/sksl/SkSLPosition.h" @13
- include "src/sksl/ir/SkSLType.h" @14
- include "src/sksl/tracing/SkSLTraceHook.h" @15
- include <cstdint> @17
- include <memory> @18
- include <string> @19
- include <vector> @20
- class_specifier SkWStream @22-22
- struct_specifier TraceInfo @26-36
- enum_specifier Op @27-33
- struct_specifier SlotDebugInfo @38-54
- struct_specifier FunctionDebugInfo @56-59
- class_specifier DebugTracePriv @61-107

### gfx/skia/skia/src/sksl/tracing/SkSLTraceHook.cpp

Blob: `0c1201043156b6725b10108ffc44cbffa5586cd0`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/tracing/SkSLDebugTracePriv.h" @8
- include "src/sksl/tracing/SkSLTraceHook.h" @9
- function_definition Make @13-17
- function_definition line @19-21
- function_definition var @22-24
- function_definition enter @25-27
- function_definition exit @28-30
- function_definition scope @31-33

### gfx/skia/skia/src/sksl/tracing/SkSLTraceHook.h

Blob: `404e1be22953cc744a161a13cb5fa52b7ddfae61`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @11
- include <memory> @12
- include <vector> @13
- struct_specifier TraceInfo @17-17
- class_specifier TraceHook @19-27
- function_definition ~TraceHook @21-21
- class_specifier Tracer @29-41

### gfx/skia/skia/src/sksl/transform/SkSLAddConstToVarModifiers.cpp

Blob: `97b8cc46130ceca32dff020052f8369aac0b5ede`. Grammar: cpp. Status: syntax-clean.

- include "src/base/SkEnumBitMask.h" @8
- include "src/sksl/SkSLAnalysis.h" @9
- include "src/sksl/analysis/SkSLProgramUsage.h" @10
- include "src/sksl/ir/SkSLModifierFlags.h" @11
- include "src/sksl/ir/SkSLVariable.h" @12
- include "src/sksl/transform/SkSLTransform.h" @13
- class_specifier Expression @17-17
- function_definition AddConstToVarModifiers @19-38

### gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadFunctions.cpp

Blob: `ec8c9ea367f77b1afeafdb9dc5c5180853cf7a7c`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLContext.h" @8
- include "src/sksl/SkSLModule.h" @9
- include "src/sksl/SkSLProgramSettings.h" @10
- include "src/sksl/analysis/SkSLProgramUsage.h" @11
- include "src/sksl/ir/SkSLFunctionDeclaration.h" @12
- include "src/sksl/ir/SkSLFunctionDefinition.h" @13
- include "src/sksl/ir/SkSLProgram.h" @14
- include "src/sksl/ir/SkSLProgramElement.h" @15
- include "src/sksl/transform/SkSLTransform.h" @16
- include <algorithm> @18
- include <cstddef> @19
- include <memory> @20
- include <vector> @21
- function_definition dead_function_predicate @25-36
- function_definition EliminateDeadFunctions @38-61
- function_definition EliminateDeadFunctions @63-77

### gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadGlobalVariables.cpp

Blob: `59c7455811209985693585779009e1b3aca09779`. Grammar: cpp. Status: syntax-clean.

- include "src/base/SkStringView.h" @8
- include "src/sksl/SkSLContext.h" @9
- include "src/sksl/SkSLModule.h" @10
- include "src/sksl/SkSLProgramSettings.h" @11
- include "src/sksl/analysis/SkSLProgramUsage.h" @12
- include "src/sksl/ir/SkSLProgram.h" @13
- include "src/sksl/ir/SkSLProgramElement.h" @14
- include "src/sksl/ir/SkSLVarDeclarations.h" @15
- include "src/sksl/ir/SkSLVariable.h" @16
- include "src/sksl/transform/SkSLTransform.h" @17
- include <algorithm> @19
- include <cstddef> @20
- include <memory> @21
- include <vector> @22
- function_definition is_dead_variable @26-43
- function_definition EliminateDeadGlobalVariables @45-63
- function_definition EliminateDeadGlobalVariables @65-88

### gfx/skia/skia/src/sksl/transform/SkSLEliminateDeadLocalVariables.cpp

Blob: `6e2bbdc96f1fdec4cd69cb6d9ad2cf8996950bc4`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @8
- include "include/core/SkTypes.h" @9
- include "src/core/SkTHash.h" @10
- include "src/sksl/SkSLAnalysis.h" @11
- include "src/sksl/SkSLModule.h" @12
- include "src/sksl/SkSLProgramSettings.h" @13
- include "src/sksl/analysis/SkSLProgramUsage.h" @14
- include "src/sksl/ir/SkSLBinaryExpression.h" @15
- include "src/sksl/ir/SkSLExpression.h" @16
- include "src/sksl/ir/SkSLExpressionStatement.h" @17
- include "src/sksl/ir/SkSLFunctionDefinition.h" @18
- include "src/sksl/ir/SkSLNop.h" @19
- include "src/sksl/ir/SkSLProgram.h" @20
- include "src/sksl/ir/SkSLProgramElement.h" @21
- include "src/sksl/ir/SkSLStatement.h" @22
- include "src/sksl/ir/SkSLVarDeclarations.h" @23
- include "src/sksl/ir/SkSLVariable.h" @24
- include "src/sksl/ir/SkSLVariableReference.h" @25
- include "src/sksl/transform/SkSLProgramWriter.h" @26
- include "src/sksl/transform/SkSLTransform.h" @27
- include <memory> @29
- include <utility> @30
- include <vector> @31
- class_specifier Context @37-37
- function_definition eliminate_dead_local_variables @39-156
- class_specifier DeadLocalVariableEliminator @42-138
- function_definition DeadLocalVariableEliminator @44-46
- function_definition visitExpressionPtr @50-76
- function_definition visitStatementPtr @78-125
- function_definition CanEliminate @127-129
- function_definition EliminateDeadLocalVariables @158-162
- function_definition EliminateDeadLocalVariables @164-170

### gfx/skia/skia/src/sksl/transform/SkSLEliminateEmptyStatements.cpp

Blob: `2fe72db77d1af542145a8f4ed8b8726860ce1eaa`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @8
- include "src/sksl/SkSLDefines.h" @9
- include "src/sksl/SkSLModule.h" @10
- include "src/sksl/ir/SkSLBlock.h" @11
- include "src/sksl/ir/SkSLFunctionDefinition.h" @12
- include "src/sksl/ir/SkSLProgramElement.h" @13
- include "src/sksl/ir/SkSLStatement.h" @14
- include "src/sksl/transform/SkSLProgramWriter.h" @15
- include "src/sksl/transform/SkSLTransform.h" @16
- include <algorithm> @18
- include <iterator> @19
- include <memory> @20
- include <vector> @21
- class_specifier Expression @25-25
- function_definition eliminate_empty_statements @27-61
- class_specifier EmptyStatementEliminator @28-53
- function_definition visitExpressionPtr @30-33
- function_definition visitStatementPtr @35-50
- function_definition EliminateEmptyStatements @63-65

### gfx/skia/skia/src/sksl/transform/SkSLEliminateUnnecessaryBraces.cpp

Blob: `34a8975807878a58779d811ee820e1d1b72e677a`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLDefines.h" @8
- include "src/sksl/SkSLModule.h" @9
- include "src/sksl/SkSLPosition.h" @10
- include "src/sksl/ir/SkSLBlock.h" @11
- include "src/sksl/ir/SkSLDoStatement.h" @12
- include "src/sksl/ir/SkSLExpression.h" @13
- include "src/sksl/ir/SkSLForStatement.h" @14
- include "src/sksl/ir/SkSLFunctionDefinition.h" @15
- include "src/sksl/ir/SkSLIRNode.h" @16
- include "src/sksl/ir/SkSLIfStatement.h" @17
- include "src/sksl/ir/SkSLNop.h" @18
- include "src/sksl/ir/SkSLProgramElement.h" @19
- include "src/sksl/ir/SkSLStatement.h" @20
- include "src/sksl/transform/SkSLProgramWriter.h" @21
- include "src/sksl/transform/SkSLTransform.h" @22
- include <memory> @24
- include <utility> @25
- include <vector> @26
- class_specifier Context @30-30
- function_definition EliminateUnnecessaryBraces @32-186
- class_specifier UnnecessaryBraceEliminator @33-98
- function_definition visitExpressionPtr @35-38
- function_definition visitStatementPtr @40-67
- function_definition EliminateBracesFrom @69-95
- class_specifier RequiredBraceWriter @100-171
- function_definition RequiredBraceWriter @102-102
- function_definition visitExpressionPtr @104-107
- function_definition visitStatementPtr @109-167

### gfx/skia/skia/src/sksl/transform/SkSLEliminateUnreachableCode.cpp

Blob: `6e31ad1ba50fecc16cec497a3c28633924320ca3`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @8
- include "include/core/SkTypes.h" @9
- include "include/private/base/SkTArray.h" @10
- include "src/sksl/SkSLDefines.h" @11
- include "src/sksl/SkSLModule.h" @12
- include "src/sksl/analysis/SkSLProgramUsage.h" @13
- include "src/sksl/ir/SkSLFunctionDefinition.h" @14
- include "src/sksl/ir/SkSLIRNode.h" @15
- include "src/sksl/ir/SkSLIfStatement.h" @16
- include "src/sksl/ir/SkSLNop.h" @17
- include "src/sksl/ir/SkSLProgram.h" @18
- include "src/sksl/ir/SkSLProgramElement.h" @19
- include "src/sksl/ir/SkSLStatement.h" @20
- include "src/sksl/ir/SkSLSwitchCase.h" @21
- include "src/sksl/ir/SkSLSwitchStatement.h" @22
- include "src/sksl/transform/SkSLProgramWriter.h" @23
- include "src/sksl/transform/SkSLTransform.h" @24
- include <memory> @26
- include <vector> @27
- class_specifier Expression @33-33
- function_definition eliminate_unreachable_code @35-206
- class_specifier UnreachableCodeEliminator @37-198
- function_definition UnreachableCodeEliminator @39-42
- function_definition visitExpressionPtr @44-47
- function_definition visitStatementPtr @49-191
- function_definition EliminateUnreachableCode @208-210
- function_definition EliminateUnreachableCode @212-214

### gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinFunctions.cpp

Blob: `72b720d79ddf58796f1c2cd7362a7f9d6aa5445e`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "src/core/SkTHash.h" @9
- include "src/sksl/SkSLContext.h" @10
- include "src/sksl/SkSLIntrinsicList.h" @11
- include "src/sksl/SkSLProgramSettings.h" @12
- include "src/sksl/analysis/SkSLProgramUsage.h" @13
- include "src/sksl/ir/SkSLFunctionDeclaration.h" @14
- include "src/sksl/ir/SkSLFunctionDefinition.h" @15
- include "src/sksl/ir/SkSLProgram.h" @16
- include "src/sksl/ir/SkSLSymbol.h" @17
- include "src/sksl/transform/SkSLTransform.h" @18
- include <algorithm> @20
- include <cstddef> @21
- include <memory> @22
- include <string> @23
- include <string_view> @24
- include <vector> @25
- class_specifier ProgramElement @29-29
- function_definition FindAndDeclareBuiltinFunctions @31-97

### gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinStructs.cpp

Blob: `362be7dadc50291dd94c7f299f8b0963c95feafd`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "src/core/SkTHash.h" @9
- include "src/sksl/SkSLContext.h" @10
- include "src/sksl/SkSLModule.h" @11
- include "src/sksl/analysis/SkSLProgramUsage.h" @12
- include "src/sksl/ir/SkSLProgram.h" @13
- include "src/sksl/ir/SkSLProgramElement.h" @14
- include "src/sksl/ir/SkSLStructDefinition.h" @15
- include "src/sksl/ir/SkSLSymbol.h" @16
- include "src/sksl/ir/SkSLType.h" @17
- include "src/sksl/transform/SkSLTransform.h" @18
- include <memory> @20
- include <type_traits> @21
- include <vector> @22
- function_definition contains_builtin_struct @28-36
- function_definition get_struct_definitions_from_module @38-59
- function_definition FindAndDeclareBuiltinStructs @61-76

### gfx/skia/skia/src/sksl/transform/SkSLFindAndDeclareBuiltinVariables.cpp

Blob: `94c26393e4435556faa1a154bab44b96b0f94264`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @8
- include "include/core/SkTypes.h" @9
- include "src/core/SkTHash.h" @10
- include "src/sksl/SkSLBuiltinTypes.h" @11
- include "src/sksl/SkSLCompiler.h" @12
- include "src/sksl/SkSLContext.h" @13
- include "src/sksl/SkSLProgramSettings.h" @14
- include "src/sksl/analysis/SkSLProgramUsage.h" @15
- include "src/sksl/ir/SkSLFunctionDeclaration.h" @16
- include "src/sksl/ir/SkSLFunctionDefinition.h" @17
- include "src/sksl/ir/SkSLIRNode.h" @18
- include "src/sksl/ir/SkSLInterfaceBlock.h" @19
- include "src/sksl/ir/SkSLLayout.h" @20
- include "src/sksl/ir/SkSLProgram.h" @21
- include "src/sksl/ir/SkSLProgramElement.h" @22
- include "src/sksl/ir/SkSLSymbol.h" @23
- include "src/sksl/ir/SkSLSymbolTable.h" @24
- include "src/sksl/ir/SkSLType.h" @25
- include "src/sksl/ir/SkSLVarDeclarations.h" @26
- include "src/sksl/ir/SkSLVariable.h" @27
- include "src/sksl/transform/SkSLTransform.h" @28
- include <algorithm> @30
- include <memory> @31
- include <string_view> @32
- include <vector> @33
- class_specifier BuiltinVariableScanner @39-123
- function_definition BuiltinVariableScanner @41-43
- function_definition addDeclaringElement @45-51
- function_definition addDeclaringElement @53-69
- function_definition addImplicitFragColorWrite @71-87
- function_definition GlobalVarBuiltinName @89-91
- function_definition InterfaceBlockName @93-95
- function_definition sortNewElements @97-118
- function_definition FindAndDeclareBuiltinVariables @127-184

### gfx/skia/skia/src/sksl/transform/SkSLHoistSwitchVarDeclarationsAtTopLevel.cpp

Blob: `8f8a71140e3a1231fcdaf2e8e5e17648326f07d3`. Grammar: cpp. Status: syntax-clean.

- include "include/private/base/SkAssert.h" @8
- include "include/private/base/SkTArray.h" @9
- include "src/sksl/SkSLAnalysis.h" @10
- include "src/sksl/SkSLDefines.h" @11
- include "src/sksl/SkSLPosition.h" @12
- include "src/sksl/ir/SkSLBlock.h" @13
- include "src/sksl/ir/SkSLExpression.h" @14
- include "src/sksl/ir/SkSLIRHelpers.h" @15
- include "src/sksl/ir/SkSLIRNode.h" @16
- include "src/sksl/ir/SkSLModifierFlags.h" @17
- include "src/sksl/ir/SkSLNop.h" @18
- include "src/sksl/ir/SkSLStatement.h" @19
- include "src/sksl/ir/SkSLSymbolTable.h" @20
- include "src/sksl/ir/SkSLVarDeclarations.h" @21
- include "src/sksl/ir/SkSLVariable.h" @22
- include "src/sksl/transform/SkSLProgramWriter.h" @23
- include "src/sksl/transform/SkSLTransform.h" @24
- include <memory> @26
- include <utility> @27
- class_specifier Context @33-33
- function_definition HoistSwitchVarDeclarationsAtTopLevel @35-137
- struct_specifier HoistSwitchVarDeclsVisitor @39-78
- function_definition HoistSwitchVarDeclsVisitor @40-40
- function_definition visitExpressionPtr @42-45
- function_definition visitStatementPtr @47-72
- struct_specifier AssignmentHelper @106-112
- function_definition makeAssignmentStmt @109-111

### gfx/skia/skia/src/sksl/transform/SkSLProgramWriter.h

Blob: `6e5988aa927293f2248e3ec7228181a6af3e56e1`. Grammar: cpp. Status: contains-errors.

- include "src/sksl/analysis/SkSLProgramVisitor.h" @11
- struct_specifier ProgramWriterTypes @15-22
- class_specifier ProgramWriter @26-36
- function_definition visitExpressionPtr @30-32
- function_definition visitStatementPtr @33-35

### gfx/skia/skia/src/sksl/transform/SkSLRenamePrivateSymbols.cpp

Blob: `905291c06e51d7bac5bebcd3ff5d4def6b994c62`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @8
- include "include/core/SkTypes.h" @9
- include "src/base/SkEnumBitMask.h" @10
- include "src/base/SkStringView.h" @11
- include "src/sksl/SkSLAnalysis.h" @12
- include "src/sksl/SkSLModule.h" @13
- include "src/sksl/SkSLProgramSettings.h" @14
- include "src/sksl/ir/SkSLFunctionDeclaration.h" @15
- include "src/sksl/ir/SkSLFunctionDefinition.h" @16
- include "src/sksl/ir/SkSLFunctionPrototype.h" @17
- include "src/sksl/ir/SkSLIRNode.h" @18
- include "src/sksl/ir/SkSLModifierFlags.h" @19
- include "src/sksl/ir/SkSLProgramElement.h" @20
- include "src/sksl/ir/SkSLStatement.h" @21
- include "src/sksl/ir/SkSLSymbol.h" @22
- include "src/sksl/ir/SkSLSymbolTable.h" @23
- include "src/sksl/ir/SkSLVarDeclarations.h" @24
- include "src/sksl/ir/SkSLVariable.h" @25
- include "src/sksl/transform/SkSLProgramWriter.h" @26
- include "src/sksl/transform/SkSLTransform.h" @27
- include <cstdint> @29
- include <memory> @30
- include <string> @31
- include <string_view> @32
- include <utility> @33
- include <vector> @34
- class_specifier Context @38-38
- class_specifier ProgramUsage @39-39
- enum_specifier ProgramKind @40-40
- function_definition strip_export_flag @42-56
- function_definition RenamePrivateSymbols @58-242
- class_specifier SymbolRenamer @62-224
- function_definition SymbolRenamer @64-71
- function_definition FindShortNameForSymbol @73-103
- function_definition minifyVariableName @105-132
- function_definition minifyFunctionName @134-149
- function_definition functionNameCanBeMinifiedSafely @151-160
- function_definition minifyFunction @162-175
- function_definition minifyPrototype @177-190
- function_definition visitProgramElement @192-205
- function_definition visitStatementPtr @207-217

### gfx/skia/skia/src/sksl/transform/SkSLReplaceConstVarsWithLiterals.cpp

Blob: `db11919d13c4445452e5781bc350c46e3fe6de28`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "src/core/SkTHash.h" @9
- include "src/sksl/SkSLConstantFolder.h" @10
- include "src/sksl/SkSLModule.h" @11
- include "src/sksl/analysis/SkSLProgramUsage.h" @12
- include "src/sksl/ir/SkSLExpression.h" @13
- include "src/sksl/ir/SkSLFunctionDefinition.h" @14
- include "src/sksl/ir/SkSLModifierFlags.h" @15
- include "src/sksl/ir/SkSLProgramElement.h" @16
- include "src/sksl/ir/SkSLVariable.h" @17
- include "src/sksl/ir/SkSLVariableReference.h" @18
- include "src/sksl/transform/SkSLProgramWriter.h" @19
- include "src/sksl/transform/SkSLTransform.h" @20
- include <cstddef> @22
- include <memory> @23
- include <string> @24
- include <string_view> @25
- include <vector> @26
- function_definition ReplaceConstVarsWithLiterals @32-103
- class_specifier ConstVarReplacer @33-62
- function_definition ConstVarReplacer @35-35
- function_definition visitExpressionPtr @39-56

### gfx/skia/skia/src/sksl/transform/SkSLReplaceSplatCastsWithSwizzles.cpp

Blob: `06aa0e49c8ce11e99e477343fcf88e9b957c8984`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLModule.h" @8
- include "src/sksl/ir/SkSLConstructorSplat.h" @9
- include "src/sksl/ir/SkSLExpression.h" @10
- include "src/sksl/ir/SkSLFunctionDefinition.h" @11
- include "src/sksl/ir/SkSLLiteral.h" @12
- include "src/sksl/ir/SkSLProgramElement.h" @13
- include "src/sksl/ir/SkSLSwizzle.h" @14
- include "src/sksl/ir/SkSLType.h" @15
- include "src/sksl/transform/SkSLProgramWriter.h" @16
- include "src/sksl/transform/SkSLTransform.h" @17
- include <memory> @19
- include <utility> @20
- include <vector> @21
- class_specifier Context @25-25
- function_definition ReplaceSplatCastsWithSwizzles @27-64
- class_specifier SwizzleWriter @28-56
- function_definition SwizzleWriter @30-30
- function_definition visitExpressionPtr @32-51

### gfx/skia/skia/src/sksl/transform/SkSLRewriteIndexedSwizzle.cpp

Blob: `5e413bbd68dd20c285bcbef639124b279aad8846`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLBuiltinTypes.h" @8
- include "src/sksl/SkSLContext.h" @9
- include "src/sksl/ir/SkSLConstructorCompound.h" @10
- include "src/sksl/ir/SkSLExpression.h" @11
- include "src/sksl/ir/SkSLIndexExpression.h" @12
- include "src/sksl/ir/SkSLSwizzle.h" @13
- include "src/sksl/ir/SkSLType.h" @14
- include "src/sksl/transform/SkSLTransform.h" @15
- include <memory> @17
- include <utility> @18
- function_definition RewriteIndexedSwizzle @22-49

### gfx/skia/skia/src/sksl/transform/SkSLTransform.cpp

Blob: `770b683edefee645adc1c3cbf2b06e095c37004c`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/transform/SkSLTransform.h" @8

### gfx/skia/skia/src/sksl/transform/SkSLTransform.h

Blob: `b9769fc8b1d577397fb562839e4ed75444feb770`. Grammar: cpp. Status: syntax-clean.

- include "src/sksl/SkSLDefines.h" @11
- include "src/sksl/ir/SkSLModifierFlags.h" @12
- include <cstdint> @14
- include <memory> @15
- class_specifier Block @19-19
- class_specifier Context @20-20
- class_specifier Expression @21-21
- class_specifier IndexExpression @22-22
- class_specifier Position @23-23
- class_specifier ProgramUsage @24-24
- class_specifier SymbolTable @25-25
- class_specifier Variable @26-26
- enum_specifier ProgramKind @27-27
- struct_specifier Module @28-28
- struct_specifier Program @29-29

### gfx/skia/skia/src/text/GlyphRun.cpp

Blob: `36d538d419cfec2932cbffcab5fd516de76caf71`. Grammar: cpp. Status: syntax-clean.

- include "src/text/GlyphRun.h" @8
- include "include/core/SkFont.h" @10
- include "include/core/SkMatrix.h" @11
- include "include/core/SkRSXform.h" @12
- include "include/core/SkScalar.h" @13
- include "include/private/base/SkTLogic.h" @14
- include "src/core/SkFontPriv.h" @15
- include "src/core/SkGlyph.h" @16
- include "src/core/SkStrikeSpec.h" @17
- include "src/core/SkTextBlobPriv.h" @18
- include <cstring> @20
- class_specifier SkPaint @22-22
- function_definition GlyphRun @26-36
- function_definition GlyphRun @38-42
- function_definition GlyphRunList @45-54
- function_definition GlyphRunList @56-64
- function_definition uniqueID @66-69
- function_definition anyRunsLCD @71-78
- function_definition temporaryShuntBlobNotifyAddedToCache @80-85
- function_definition makeBlob @87-115
- function_definition glyphrun_source_bounds @118-185
- function_definition makeGlyphRunList @187-192
- function_definition draw_text_positions @194-207
- function_definition (anonymous) @209-229
- function_definition (anonymous) @231-289
- function_definition convertRSXForm @291-303
- function_definition initialize @305-318
- function_definition prepareBuffers @320-332
- function_definition textToGlyphIDs @334-348
- function_definition makeGlyphRun @350-368
- function_definition (anonymous) @370-374

### gfx/skia/skia/src/text/GlyphRun.h

Blob: `ee9166a30681ccce6c7d37833bbd9c44b05dacba`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkFont.h" @11
- include "include/core/SkFontTypes.h" @12
- include "include/core/SkPoint.h" @13
- include "include/core/SkRect.h" @14
- include "include/core/SkRefCnt.h" @15
- include "include/core/SkSpan.h" @16
- include "include/core/SkTextBlob.h" @17
- include "include/core/SkTypes.h" @18
- include "include/private/base/SkTemplates.h" @19
- include "src/base/SkZip.h" @20
- include <algorithm> @22
- include <cstddef> @23
- include <cstdint> @24
- include <iterator> @25
- include <optional> @26
- include <tuple> @27
- include <vector> @28
- class_specifier SkPaint @30-30
- struct_specifier SkRSXform @31-31
- class_specifier GlyphRunBuilder @34-34
- class_specifier GlyphRun @36-67
- function_definition runSize @47-47
- function_definition positions @48-48
- function_definition glyphsIDs @49-49
- function_definition source @50-50
- function_definition (anonymous) @51-51
- function_definition clusters @52-52
- function_definition text @53-53
- function_definition scaledRotations @54-54
- class_specifier GlyphRunList @69-135
- function_definition canCache @88-88
- function_definition runCount @89-89
- function_definition totalGlyphCount @90-96
- function_definition maxGlyphRunSize @97-103
- function_definition hasRSXForm @105-110
- function_definition origin @114-114
- function_definition sourceBounds @115-115
- function_definition sourceBoundsWithOrigin @116-116
- function_definition blob @117-117
- function_definition builder @118-118
- function_definition begin @120-120
- function_definition end @121-121
- function_definition begin @122-122
- function_definition end @123-123
- function_definition size @124-124
- function_definition empty @125-125
- function_definition operator [] @126-126
- class_specifier GlyphRunBuilder @137-182
- function_definition empty @150-150

### gfx/skia/skia/src/text/SlugFromBuffer.cpp

Blob: `15b2779ffb2ed6c251e900f935eb6d6bf35ded58`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkRefCnt.h" @8
- include "include/core/SkSerialProcs.h" @9
- include "include/private/base/SkAssert.h" @10
- include "include/private/chromium/Slug.h" @11
- include "src/core/SkReadBuffer.h" @12
- include <atomic> @14
- include <cstdint> @15
- function_definition MakeFromBuffer @22-29
- function_definition NextUniqueID @31-34

### gfx/skia/skia/src/text/StrikeForGPU.cpp

Blob: `67f1a9227fa93ced11806ed5dd8466b3bf8c129e`. Grammar: cpp. Status: syntax-clean.

- include "src/text/StrikeForGPU.h" @8
- include "src/core/SkDescriptor.h" @10
- include "src/core/SkStrike.h" @11
- include "src/core/SkStrikeCache.h" @12
- include "src/core/SkStrikeSpec.h" @13
- include <memory> @15
- include <utility> @16
- function_definition SkStrikePromise @20-20
- function_definition SkStrikePromise @22-23
- function_definition SkStrikePromise @24-25
- function_definition strike @27-35
- function_definition resetStrike @37-39
- function_definition (anonymous) @41-47
- function_definition flatten @49-51
- function_definition StrikeMutationMonitor @54-57
- function_definition ~StrikeMutationMonitor @59-61

### gfx/skia/skia/src/text/StrikeForGPU.h

Blob: `809d8f189f392f0b158800312105648f75640438`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPath.h" @11
- include "include/core/SkRefCnt.h" @12
- include "include/core/SkTypes.h" @13
- include "src/core/SkGlyph.h" @14
- include <memory> @16
- include <optional> @17
- include <variant> @18
- class_specifier SkDescriptor @20-20
- class_specifier SkDrawable @21-21
- class_specifier SkReadBuffer @22-22
- class_specifier SkStrike @23-23
- class_specifier SkStrikeCache @24-24
- class_specifier SkStrikeClient @25-25
- class_specifier SkStrikeSpec @26-26
- class_specifier SkWriteBuffer @27-27
- class_specifier SkStrikePromise @39-67
- function_definition SkStrikePromise @41-41
- function_definition SkStrikePromise @42-42
- function_definition (anonymous) @43-43
- class_specifier StrikeForGPU @70-94
- function_definition IDOrPath @98-98
- function_definition IDOrPath @99-99
- function_definition ~IDOrPath @102-102
- class_specifier StrikeMutationMonitor @114-121
- class_specifier StrikeForGPUCacheInterface @124-128
- function_definition ~StrikeForGPUCacheInterface @126-126

### gfx/skia/skia/src/text/gpu/DistanceFieldAdjustTable.cpp

Blob: `6f395745726273a377fc5b04c845b83ed8fae4bd`. Grammar: cpp. Status: contains-errors.

- include "src/text/gpu/DistanceFieldAdjustTable.h" @8
- include "include/core/SkTypes.h" @10
- include "include/private/base/SkDebug.h" @11
- include "include/private/base/SkTemplates.h" @12
- include "src/base/SkNoDestructor.h" @13
- include "src/core/SkScalerContext.h" @14
- include <cstddef> @16
- include <cstdint> @17
- function_definition build_distance_adjust_table @25-105
- function_definition Get @107-110
- function_definition DistanceFieldAdjustTable @112-115

### gfx/skia/skia/src/text/gpu/DistanceFieldAdjustTable.h

Blob: `c39fb339a97179d2fb554ca240ea3e60848b9d0d`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkScalar.h" @11
- class_specifier SkNoDestructor @13-13
- class_specifier DistanceFieldAdjustTable @18-41
- function_definition ~DistanceFieldAdjustTable @22-25
- function_definition getAdjustment @27-30

### gfx/skia/skia/src/text/gpu/GlyphUtils.h

Blob: `112e00359a2acc9fcdf20a2b5ac865fc4320a56b`. Grammar: cpp. Status: syntax-clean.

- include "src/core/SkMask.h" @11
- include "src/gpu/MaskFormat.h" @12
- function_definition FormatFromSkGlyph @21-37

### gfx/skia/skia/src/text/gpu/GlyphVector.cpp

Blob: `7040436d16af70d7417bc679e3ccb7215a649805`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/GlyphVector.h" @8
- include "include/private/base/SkAssert.h" @10
- include "include/private/base/SkTo.h" @11
- include "src/core/SkGlyph.h" @12
- include "src/core/SkReadBuffer.h" @13
- include "src/core/SkStrike.h" @14
- include "src/core/SkStrikeCache.h" @15
- include "src/core/SkWriteBuffer.h" @16
- include "src/text/StrikeForGPU.h" @17
- include "src/text/gpu/SubRunAllocator.h" @18
- include <climits> @20
- include <optional> @21
- include <utility> @22
- class_specifier SkStrikeClient @24-24
- function_definition GlyphVector @28-31
- function_definition GlyphVector @33-39
- function_definition ~GlyphVector @41-46
- function_definition Make @48-59
- function_definition MakeFromBuffer @61-93
- function_definition flatten @95-111

### gfx/skia/skia/src/text/gpu/GlyphVector.h

Blob: `35432127f90c19cb1ffba87a0f180bf89ccedb46`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @11
- include "src/core/SkGlyph.h" @12
- include "src/core/SkStrike.h" @13
- include "src/gpu/MaskFormat.h" @14
- include "src/text/gpu/StrikeCache.h" @15
- include <cstddef> @17
- include <cstdint> @18
- include <functional> @19
- include <optional> @20
- class_specifier SkReadBuffer @22-22
- class_specifier SkStrikeClient @23-23
- class_specifier SkWriteBuffer @24-24
- class_specifier SubRunAllocator @27-27
- class_specifier StrikeCache @28-28
- class_specifier GlyphVector @105-219
- function_definition Size @119-122
- function_definition GlyphVector @129-129
- function_definition (anonymous) @130-130
- function_definition (anonymous) @131-131
- function_definition glyphCount @139-139
- function_definition unflattenSize @148-148
- function_definition hasBackendData @150-153
- function_definition (anonymous) @155-158
- function_definition (anonymous) @160-163
- function_definition accessBackendGlyphs @165-169
- function_definition initBackendData @172-202

### gfx/skia/skia/src/text/gpu/SDFMaskFilter.cpp

Blob: `0870d36a74c84d74181606296452dafe1e746f97`. Grammar: cpp. Status: contains-errors.

- include "src/text/gpu/SDFMaskFilter.h" @8
- include "include/core/SkFlattenable.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkRect.h" @12
- include "src/core/SkDistanceFieldGen.h" @13
- include "src/core/SkMask.h" @14
- include "src/core/SkMaskFilterBase.h" @15
- class_specifier SkMatrix @17-17
- class_specifier SkReadBuffer @18-18
- class_specifier SDFMaskFilterImpl @24-39
- function_definition type @34-34
- function_definition SDFMaskFilterImpl @43-43
- function_definition getFormat @45-47
- function_definition filterMask @49-85
- function_definition computeFastBounds @87-91
- function_definition CreateProc @93-95
- function_definition Make @99-101

### gfx/skia/skia/src/text/gpu/SDFMaskFilter.h

Blob: `47b78943f7956078dc402bbbbdc511f9cec1ee8a`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "include/core/SkMaskFilter.h" @15
- include "include/core/SkRefCnt.h" @16
- class_specifier SDFMaskFilter @24-27

### gfx/skia/skia/src/text/gpu/SkChromeRemoteGlyphCache.cpp

Blob: `caf2869d3a19db6d94c7c2a25d25d84167f4581e`. Grammar: cpp. Status: syntax-clean.

- include "include/private/chromium/SkChromeRemoteGlyphCache.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkColorSpace.h" @11
- include "include/core/SkData.h" @12
- include "include/core/SkDrawable.h" @13
- include "include/core/SkFontMetrics.h" @14
- include "include/core/SkImageInfo.h" @15
- include "include/core/SkMatrix.h" @16
- include "include/core/SkPicture.h" @17
- include "include/core/SkRect.h" @18
- include "include/core/SkSize.h" @19
- include "include/core/SkString.h" @20
- include "include/core/SkSurfaceProps.h" @21
- include "include/core/SkTypeface.h" @22
- include "include/private/base/SkAssert.h" @23
- include "include/private/base/SkDebug.h" @24
- include "include/private/base/SkPoint_impl.h" @25
- include "include/private/base/SkTFitsIn.h" @26
- include "include/private/base/SkTo.h" @27
- include "include/private/chromium/Slug.h" @28
- include "src/base/SkArenaAlloc.h" @29
- include "src/core/SkDescriptor.h" @30
- include "src/core/SkDevice.h" @31
- include "src/core/SkFontMetricsPriv.h" @32
- include "src/core/SkGlyph.h" @33
- include "src/core/SkReadBuffer.h" @34
- include "src/core/SkScalerContext.h" @35
- include "src/core/SkStrike.h" @36
- include "src/core/SkStrikeCache.h" @37
- include "src/core/SkStrikeSpec.h" @38
- include "src/core/SkTHash.h" @39
- include "src/core/SkTraceEvent.h" @40
- include "src/core/SkTypeface_remote.h" @41
- include "src/core/SkWriteBuffer.h" @42
- include "src/text/GlyphRun.h" @43
- include "src/text/StrikeForGPU.h" @44
- include "src/text/gpu/SubRunAllocator.h" @45
- include "src/text/gpu/SubRunContainer.h" @46
- include "src/text/gpu/SubRunControl.h" @47
- include "src/text/gpu/TextBlob.h" @48
- include <cstring> @50
- include <memory> @51
- include <optional> @52
- include <unordered_map> @53
- include <utility> @54
- class_specifier SkPaint @56-56
- struct_specifier StrikeSpec @66-72
- function_definition StrikeSpec @67-67
- function_definition StrikeSpec @68-69
- class_specifier RemoteStrike @75-154
- function_definition ~RemoteStrike @81-81
- function_definition lock @83-83
- function_definition unlock @84-84
- function_definition prepareForImage @86-90
- function_definition prepareForPath @91-95
- function_definition prepareForDrawable @96-100
- function_definition discardableHandleId @104-104
- function_definition (anonymous) @106-108
- function_definition (anonymous) @112-114
- function_definition hasPendingGlyphs @118-120
- function_definition RemoteStrike @156-168
- function_definition writePendingGlyphs @170-211
- function_definition ensureScalerContext @213-217
- function_definition resetScalerContext @219-222
- function_definition setStrikeSpec @224-226
- function_definition digestFor @228-261
- function_definition strikePromise @263-265
- class_specifier SkStrikeServerImpl @269-310
- struct_specifier MapOps @290-297
- function_definition operator() @291-293
- function_definition operator() @294-296
- function_definition SkStrikeServerImpl @312-315
- function_definition setMaxEntriesInDescriptorMapForTesting @317-319
- function_definition remoteStrikeMapSizeForTesting @320-322
- function_definition writeStrikeData @324-368
- function_definition findOrCreateScopedStrike @370-373
- function_definition checkForDeletedEntries @375-390
- function_definition getOrCreateCache @392-448
- class_specifier GlyphTrackingDevice @451-516
- function_definition GlyphTrackingDevice @453-460
- function_definition createDevice @462-471
- function_definition strikeDeviceInfo @473-475
- function_definition onDrawGlyphRunList @478-497
- function_definition convertGlyphRunListToSlug @499-511
- function_definition SkStrikeServer @519-520
- function_definition ~SkStrikeServer @522-522
- function_definition makeAnalysisCanvas @524-559
- function_definition writeStrikeData @561-563
- function_definition impl @565-565
- function_definition setMaxEntriesInDescriptorMapForTesting @567-569
- function_definition remoteStrikeMapSizeForTesting @570-572
- class_specifier DiscardableStrikePinner @575-588
- function_definition DiscardableStrikePinner @577-579
- function_definition ~DiscardableStrikePinner @581-581
- function_definition canDelete @582-582
- function_definition assertValid @583-583
- class_specifier SkStrikeClientImpl @591-620
- class_specifier PictureBackedGlyphDrawable @602-612
- function_definition PictureBackedGlyphDrawable @604-604
- function_definition onGetBounds @607-607
- function_definition onApproximateBytesUsed @608-610
- function_definition onDraw @611-611
- function_definition SkStrikeClientImpl @622-629
- function_definition readStrikeData @631-746
- function_definition translateTypefaceID @748-771
- function_definition retrieveTypefaceUsingServerID @773-776
- function_definition addTypeface @778-791
- function_definition SkStrikeClient @794-797
- function_definition ~SkStrikeClient @799-799
- function_definition readStrikeData @801-803
- function_definition retrieveTypefaceUsingServerIDForTest @805-808
- function_definition translateTypefaceID @810-812
- function_definition deserializeSlugForTest @814-817

### gfx/skia/skia/src/text/gpu/Slug.cpp

Blob: `c872dbbc13a3559d7143dfa89f4872001db03852`. Grammar: cpp. Status: syntax-clean.

- include "include/private/chromium/Slug.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkSerialProcs.h" @12
- include "src/core/SkReadBuffer.h" @13
- include "src/core/SkWriteBuffer.h" @14
- class_specifier SkData @16-16
- function_definition ConvertBlob @20-23
- function_definition serialize @25-29
- function_definition serialize @31-40
- function_definition Deserialize @42-48
- function_definition draw @50-52

### gfx/skia/skia/src/text/gpu/SlugImpl.cpp

Blob: `2895fac678eaf38da769a183bead6abad91e6be9`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/SlugImpl.h" @8
- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkRect.h" @12
- include "include/core/SkSerialProcs.h" @13
- include "include/private/base/SkAssert.h" @14
- include "include/private/chromium/Slug.h" @15
- include "src/core/SkDevice.h" @16
- include "src/core/SkReadBuffer.h" @17
- include "src/core/SkWriteBuffer.h" @18
- include "src/text/GlyphRun.h" @19
- include "src/text/gpu/SubRunAllocator.h" @20
- include "src/text/gpu/SubRunContainer.h" @21
- include <memory> @23
- include <utility> @24
- class_specifier SkStrikeClient @26-26
- function_definition SlugImpl @30-37
- function_definition doFlatten @39-44
- function_definition MakeFromBuffer @46-67
- function_definition position_matrix @69-72
- function_definition Make @74-104
- function_definition AddDeserialProcs @106-113

### gfx/skia/skia/src/text/gpu/SlugImpl.h

Blob: `c5aa85f88e3c193f247fa87feda5e24572049f8b`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPoint.h" @10
- include "include/core/SkRect.h" @11
- include "include/core/SkRefCnt.h" @12
- include "include/private/base/SkAssert.h" @13
- include "include/private/chromium/Slug.h" @14
- include "src/text/gpu/SubRunAllocator.h" @15
- include "src/text/gpu/SubRunContainer.h" @16
- include <cstddef> @18
- class_specifier SkMatrix @20-20
- class_specifier SkPaint @21-21
- class_specifier SkReadBuffer @22-22
- class_specifier SkStrikeClient @23-23
- class_specifier SkWriteBuffer @24-24
- struct_specifier SkStrikeDeviceInfo @25-25
- class_specifier GlyphRunList @28-28
- class_specifier StrikeForGPUCacheInterface @29-29
- class_specifier SlugImpl @34-72
- function_definition ~SlugImpl @40-40
- function_definition sourceBounds @51-51
- function_definition sourceBoundsWithOrigin @52-52
- function_definition (anonymous) @54-54
- function_definition origin @55-55
- function_definition (anonymous) @57-57
- function_definition operator delete @61-61
- function_definition operator new @62-62
- function_definition operator new @63-63

### gfx/skia/skia/src/text/gpu/StrikeCache.cpp

Blob: `c06cd57dfb1c96dcaba5671744f77bf3551ce658`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/StrikeCache.h" @7
- include "include/private/base/SkAssert.h" @9
- include "include/private/base/SkDebug.h" @10
- include "include/private/chromium/SkChromeRemoteGlyphCache.h" @11
- include "src/base/SkArenaAlloc.h" @12
- include "src/core/SkGlyph.h" @13
- include "src/core/SkReadBuffer.h" @14
- include "src/core/SkStrikeCache.h" @15
- include "src/core/SkStrikeSpec.h" @16
- include "src/core/SkTraceEvent.h" @17
- include "src/text/StrikeForGPU.h" @18
- include <algorithm> @20
- include <optional> @21
- include <utility> @22
- class_specifier SkStrike @24-24
- function_definition addMemoryUsed @28-33
- function_definition ~StrikeCache @35-37
- function_definition freeAll @39-41
- function_definition internalPurge @43-95
- function_definition internalAttachToHead @97-116
- function_definition internalRemoveStrike @118-137
- function_definition validate @139-161
- function_definition (anonymous) @163-165
- function_definition HashTraits::Hash @167-169
- function_definition MakeFromBuffer @174-196

### gfx/skia/skia/src/text/gpu/StrikeCache.h

Blob: `68d9d6fe409b9a9d813c9c3f07f709a215400733`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkRefCnt.h" @11
- include "src/base/SkArenaAlloc.h" @12
- include "src/core/SkDescriptor.h" @13
- include "src/core/SkStrikeSpec.h" @14
- include "src/core/SkTHash.h" @15
- include <cstddef> @17
- include <cstdint> @18
- struct_specifier SkPackedGlyphID @20-20
- class_specifier StrikeCache @34-34
- class_specifier TextStrikeBase @40-72
- function_definition ~TextStrikeBase @42-42
- function_definition (anonymous) @44-44
- function_definition (anonymous) @45-45
- function_definition memoryUsed @47-47
- function_definition TextStrikeBase @50-51
- class_specifier StrikeCache @76-112
- struct_specifier HashTraits @99-102
- function_definition Find @114-118
- function_definition Add @120-124

### gfx/skia/skia/src/text/gpu/SubRunAllocator.cpp

Blob: `d5e51be0eac1724c3a81f9f6e9cce244d1db147d`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/SubRunAllocator.h" @8
- include "include/private/base/SkMath.h" @10
- include "include/private/base/SkTFitsIn.h" @11
- include <cstddef> @13
- include <memory> @14
- include <new> @15
- function_definition BagOfBytes @20-31
- function_definition BagOfBytes @33-34
- function_definition ~BagOfBytes @36-43
- function_definition Block::Block @45-47
- function_definition alignedBytes @49-55
- function_definition setupBytesAndCapacity @57-63
- function_definition needMoreBytes @65-80
- function_definition SubRunAllocator @83-87
- function_definition SubRunAllocator @89-90
- function_definition alignedBytes @92-94

### gfx/skia/skia/src/text/gpu/SubRunAllocator.h

Blob: `192b41b244dc131b9614ecf9a31453d60bfac799`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @11
- include "include/private/base/SkAssert.h" @12
- include "include/private/base/SkMath.h" @13
- include "include/private/base/SkTLogic.h" @14
- include "include/private/base/SkTemplates.h" @15
- include "include/private/base/SkTo.h" @16
- include "src/base/SkArenaAlloc.h" @17
- include <algorithm> @19
- include <array> @20
- include <climits> @21
- include <cstddef> @22
- include <cstdint> @23
- include <cstring> @24
- include <limits> @25
- include <memory> @26
- include <new> @27
- include <tuple> @28
- include <utility> @29
- class_specifier BagOfBytes @34-186
- function_definition BagOfBytes @56-56
- function_definition (anonymous) @57-57
- function_definition BagOfBytes @58-61
- function_definition (anonymous) @62-66
- function_definition PlatformMinimumSizeWithOverhead @72-75
- function_definition MinimumSizeWithOverhead @77-113
- function_definition WillCountFit @120-123
- function_definition allocateBytesFor @127-132
- function_definition allocateBytesFor @134-136
- function_definition AlignUp @141-143
- struct_specifier Block @148-153
- function_definition allocateBytes @157-167
- class_specifier SubRunInitializer @189-204
- function_definition SubRunInitializer @191-191
- function_definition ~SubRunInitializer @192-194
- function_definition initialize @196-200
- class_specifier SubRunAllocator @211-329
- struct_specifier Destroyer @213-216
- function_definition operator() @215-215
- struct_specifier ArrayDestroyer @218-224
- function_definition operator() @221-223
- function_definition SubRunAllocator @231-231
- function_definition (anonymous) @232-232
- function_definition SubRunAllocator @233-233
- function_definition (anonymous) @234-234
- function_definition AllocateClassMemoryAndArena @237-250
- function_definition makePOD @252-256
- function_definition makeUnique @259-263
- function_definition makePODArray @265-269
- function_definition makePODSpan @272-281
- function_definition makePODArray @284-292
- function_definition makeUniqueArray @295-302
- function_definition makeUniqueArray @305-312
- function_definition makeUniqueArray @315-323
- class_specifier STSubRunAllocator @337-344
- function_definition STSubRunAllocator @342-343

### gfx/skia/skia/src/text/gpu/SubRunContainer.cpp

Blob: `c59ff2f4be392fb2e845002cb4aa95a850e9e60a`. Grammar: cpp. Status: contains-errors.

- include "src/text/gpu/SubRunContainer.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkDrawable.h" @11
- include "include/core/SkFont.h" @12
- include "include/core/SkMaskFilter.h" @13
- include "include/core/SkMatrix.h" @14
- include "include/core/SkPaint.h" @15
- include "include/core/SkPath.h" @16
- include "include/core/SkPathEffect.h" @17
- include "include/core/SkRect.h" @18
- include "include/core/SkScalar.h" @19
- include "include/core/SkStrokeRec.h" @20
- include "include/core/SkSurfaceProps.h" @21
- include "include/core/SkTypes.h" @22
- include "include/effects/SkDashPathEffect.h" @23
- include "include/private/base/SkFloatingPoint.h" @24
- include "include/private/base/SkOnce.h" @25
- include "include/private/base/SkTArray.h" @26
- include "include/private/base/SkTLogic.h" @27
- include "include/private/base/SkTo.h" @28
- include "src/base/SkZip.h" @29
- include "src/core/SkDevice.h" @30
- include "src/core/SkDistanceFieldGen.h" @31
- include "src/core/SkEnumerate.h" @32
- include "src/core/SkFontPriv.h" @33
- include "src/core/SkGlyph.h" @34
- include "src/core/SkMask.h" @35
- include "src/core/SkMaskFilterBase.h" @36
- include "src/core/SkMatrixPriv.h" @37
- include "src/core/SkPathEffectBase.h" @38
- include "src/core/SkReadBuffer.h" @39
- include "src/core/SkScalerContext.h" @40
- include "src/core/SkStrike.h" @41
- include "src/core/SkStrikeCache.h" @42
- include "src/core/SkStrikeSpec.h" @43
- include "src/core/SkWriteBuffer.h" @44
- include "src/gpu/MaskFormat.h" @45
- include "src/text/GlyphRun.h" @46
- include "src/text/StrikeForGPU.h" @47
- include "src/text/gpu/GlyphUtils.h" @48
- include "src/text/gpu/SDFMaskFilter.h" @49
- include "src/text/gpu/StrikeCache.h" @50
- include "src/text/gpu/SubRunControl.h" @51
- include <algorithm> @53
- include <climits> @54
- include <cstdint> @55
- include <new> @56
- include <optional> @57
- include <vector> @58
- enum_specifier SubRun::SubRunStreamTag @76-86
- function_definition get_packedIDs @96-98
- function_definition get_glyphIDs @100-102
- function_definition get_positions @105-107
- class_specifier PathOpSubmitter @113-168
- function_definition PathOpSubmitter @115-115
- function_definition PathOpSubmitter @116-116
- function_definition (anonymous) @117-117
- function_definition PathOpSubmitter @118-125
- function_definition (anonymous) @126-130
- function_definition unflattenSize @170-172
- function_definition flatten @174-183
- function_definition MakeFromBuffer @185-217
- function_definition PathOpSubmitter @219-231
- function_definition ~PathOpSubmitter @233-240
- function_definition Make @242-257
- function_definition submitDraws @259-320
- class_specifier PathSubRun @323-361
- function_definition PathSubRun @325-325
- function_definition Make @327-335
- function_definition draw @337-343
- function_definition canReuse @347-349
- function_definition testingOnly_atlasSubRun @350-350
- function_definition subRunStreamTag @356-356
- function_definition unflattenSize @363-365
- function_definition doFlatten @367-369
- function_definition MakeFromBuffer @371-377
- class_specifier DrawableOpSubmitter @381-429
- function_definition DrawableOpSubmitter @383-383
- function_definition DrawableOpSubmitter @384-384
- function_definition (anonymous) @385-385
- function_definition DrawableOpSubmitter @386-390
- function_definition (anonymous) @391-395
- function_definition Make @401-412
- function_definition unflattenSize @431-433
- function_definition flatten @435-443
- function_definition MakeFromBuffer @445-475
- function_definition DrawableOpSubmitter @477-487
- function_definition submitDraws @489-525
- class_specifier DrawableSubRun @528-568
- function_definition DrawableSubRun @530-531
- function_definition Make @533-542
- function_definition draw @548-554
- function_definition subRunStreamTag @563-563
- function_definition unflattenSize @570-572
- function_definition doFlatten @574-576
- function_definition MakeFromBuffer @578-584
- function_definition canReuse @586-588
- function_definition testingOnly_atlasSubRun @590-592
- class_specifier DirectMaskSubRun @595-686
- function_definition DirectMaskSubRun @597-598
- function_definition Make @600-617
- function_definition MakeFromBuffer @619-634
- function_definition draw @636-646
- function_definition unflattenSize @648-652
- function_definition glyphSrcPadding @654-654
- function_definition deviceRectAndNeedsTransform @656-661
- function_definition glyphParams @663-666
- function_definition canReuse @668-671
- function_definition testingOnly_atlasSubRun @673-675
- function_definition subRunStreamTag @678-680
- function_definition doFlatten @682-685
- class_specifier TransformedMaskSubRun @689-785
- function_definition TransformedMaskSubRun @691-693
- function_definition Make @695-715
- function_definition MakeFromBuffer @717-731
- function_definition unflattenSize @733-737
- function_definition canReuse @739-743
- function_definition testingOnly_atlasSubRun @745-745
- function_definition glyphSrcPadding @747-747
- function_definition draw @749-759
- function_definition deviceRectAndNeedsTransform @761-765
- function_definition glyphParams @767-770
- function_definition subRunStreamTag @773-775
- function_definition doFlatten @777-781
- function_definition has_some_antialiasing @789-793
- class_specifier SDFTSubRun @797-915
- function_definition SDFTSubRun @799-809
- function_definition Make @811-843
- function_definition MakeFromBuffer @845-866
- function_definition unflattenSize @868-872
- function_definition canReuse @874-876
- function_definition testingOnly_atlasSubRun @878-878
- function_definition glyphSrcPadding @880-880
- function_definition draw @882-889
- function_definition deviceRectAndNeedsTransform @891-895
- function_definition glyphParams @897-899
- function_definition subRunStreamTag @902-902
- function_definition doFlatten @903-909
- function_definition add_multi_mask_format @922-945
- function_definition ~SubRun @949-949
- function_definition flatten @950-953
- function_definition MakeFromBuffer @955-979
- function_definition SubRunContainer @982-983
- function_definition flattenAllocSizeHint @985-991
- function_definition AllocSizeHintFromBuffer @993-1002
- function_definition flattenRuns @1004-1014
- function_definition MakeFromBufferInAlloc @1016-1034
- function_definition EstimateAllocSize @1036-1046
- function_definition find_maximum_glyph_dimension @1048-1057
- function_definition prepare_for_SDFT_drawing @1060-1101
- function_definition prepare_for_direct_mask_drawing @1104-1153
- function_definition prepare_for_mask_drawing @1155-1194
- function_definition prepare_for_path_drawing @1196-1222
- function_definition prepare_for_drawable_drawing @1224-1250
- function_definition make_sdft_strike_spec @1253-1290
- function_definition MakeInAlloc @1293-1591
- function_definition draw @1593-1601
- function_definition canReuse @1603-1610
- function_definition MakePointsFromBuffer @1613-1626

### gfx/skia/skia/src/text/gpu/SubRunContainer.h

Blob: `90e8fd3dfbda0fd60868677e53180d5a4b5fdad9`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkMatrix.h" @11
- include "include/core/SkRect.h" @12
- include "include/core/SkRefCnt.h" @13
- include "include/core/SkSpan.h" @14
- include "include/private/base/SkPoint_impl.h" @15
- include "include/private/base/SkTLogic.h" @16
- include "src/core/SkColorData.h" @17
- include "src/text/gpu/GlyphVector.h" @18
- include "src/text/gpu/SubRunAllocator.h" @19
- include "src/text/gpu/VertexFiller.h" @20
- include <cstddef> @22
- include <functional> @23
- include <iterator> @24
- include <memory> @25
- include <tuple> @26
- include <utility> @27
- class_specifier SkCanvas @29-29
- class_specifier SkPaint @30-30
- class_specifier SkReadBuffer @31-31
- class_specifier SkStrikeClient @32-32
- class_specifier SkWriteBuffer @33-33
- struct_specifier SkStrikeDeviceInfo @34-34
- class_specifier GlyphRunList @37-37
- class_specifier StrikeForGPUCacheInterface @38-38
- enum_specifier MaskFormat @42-42
- class_specifier GlyphVector @46-46
- class_specifier StrikeCache @47-47
- struct_specifier RendererData @49-53
- class_specifier AtlasSubRun @55-55
- class_specifier SubRun @65-65
- class_specifier SubRun @67-99
- enum_specifier SubRunStreamTag @92-92
- class_specifier AtlasSubRun @115-147
- function_definition AtlasSubRun @117-118
- function_definition ~AtlasSubRun @120-120
- function_definition glyphCount @122-122
- function_definition maskFormat @123-123
- function_definition instanceFlags @125-125
- struct_specifier GlyphParams @130-134
- function_definition (anonymous) @137-137
- function_definition (anonymous) @139-139
- class_specifier SubRunList @150-185
- class_specifier Iterator @152-168
- function_definition Iterator @159-159
- function_definition (anonymous) @160-160
- function_definition operator++ @161-161
- function_definition operator== @162-162
- function_definition operator!= @163-163
- function_definition operator* @164-164
- function_definition append @170-174
- function_definition isEmpty @175-175
- function_definition begin @176-176
- function_definition end @177-177
- function_definition begin @178-178
- function_definition end @179-179
- function_definition (anonymous) @180-180
- class_specifier SubRunContainer @188-188
- class_specifier SubRunContainer @190-234
- function_definition SubRunContainer @193-193
- function_definition SubRunContainer @194-194
- function_definition (anonymous) @195-195
- function_definition SubRunContainer @198-198
- function_definition (anonymous) @199-199
- enum_specifier SubRunCreationBehavior @209-209
- function_definition (anonymous) @226-226
- function_definition isEmpty @227-227

### gfx/skia/skia/src/text/gpu/SubRunControl.cpp

Blob: `d92108883a988a746b95dd0fc4d65801b1aede22`. Grammar: cpp. Status: contains-errors.

- include "src/text/gpu/SubRunControl.h" @8
- include "include/core/SkFont.h" @10
- include "include/core/SkFontTypes.h" @11
- include "include/core/SkMatrix.h" @12
- include "include/core/SkPaint.h" @13
- include "include/core/SkScalar.h" @14
- include "src/core/SkFontPriv.h" @15
- include "src/core/SkGlyph.h" @16
- include "src/core/SkReadBuffer.h" @17
- include "src/core/SkWriteBuffer.h" @18
- include <tuple> @20
- struct_specifier SkPoint @22-22
- function_definition MinSDFTRange @37-42
- function_definition SubRunControl @44-54
- function_definition isDirect @57-68
- function_definition isSDFT @71-82
- function_definition getSDFFont @84-117
- function_definition matrixInRange @138-141
- function_definition flatten @143-146
- function_definition MakeFromBuffer @148-152

### gfx/skia/skia/src/text/gpu/SubRunControl.h

Blob: `3a984669a69c3419cafd0ce047423ff9382c4c79`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkScalar.h" @11
- include "include/core/SkTypes.h" @12
- include <tuple> @14
- class_specifier SkFont @16-16
- class_specifier SkMatrix @17-17
- class_specifier SkPaint @18-18
- class_specifier SkReadBuffer @19-19
- class_specifier SkWriteBuffer @20-20
- struct_specifier SkPoint @21-21
- class_specifier SDFTMatrixRange @28-38
- function_definition SDFTMatrixRange @30-30
- class_specifier SubRunControl @41-81
- function_definition maxSize @55-55
- function_definition SubRunControl @57-57
- function_definition forcePathAA @62-62

### gfx/skia/skia/src/text/gpu/TextBlob.cpp

Blob: `143210b65c548439676ef6337a79b0156d9debba`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/TextBlob.h" @8
- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkRect.h" @12
- include "include/core/SkScalar.h" @13
- include "include/private/base/SkAssert.h" @14
- include "include/private/base/SkCPUTypes.h" @15
- include "src/core/SkColorData.h" @16
- include "src/core/SkDevice.h" @17
- include "src/core/SkFontPriv.h" @18
- include "src/core/SkMaskFilterBase.h" @19
- include "src/core/SkPaintPriv.h" @20
- include "src/core/SkScalerContext.h" @21
- include "src/text/GlyphRun.h" @22
- include "src/text/gpu/SlugImpl.h" @23
- include "src/text/gpu/SubRunAllocator.h" @24
- include "src/text/gpu/SubRunContainer.h" @25
- include "src/text/gpu/SubRunControl.h" @26
- include <memory> @28
- include <utility> @29
- class_specifier SkMaskFilter @31-31
- function_definition can_use_direct @39-52
- function_definition compute_canonical_color @55-78
- function_definition Key::Make @84-150
- function_definition Key::operator== @152-185
- function_definition operator delete @188-188
- function_definition operator new @189-189
- function_definition operator new @190-190
- function_definition ~TextBlob @192-192
- function_definition Make @194-213
- function_definition addKey @215-217
- function_definition canReuse @219-235
- function_definition (anonymous) @237-237
- function_definition draw @239-244
- function_definition TextBlob @246-253
- function_definition MakeSlug @255-261

### gfx/skia/skia/src/text/gpu/TextBlob.h

Blob: `c0d1ac8fe0cb0d8e32e9e6ce8d8eeb99b401ae09`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkColor.h" @11
- include "include/core/SkMatrix.h" @12
- include "include/core/SkPaint.h" @13
- include "include/core/SkRefCnt.h" @14
- include "include/core/SkScalar.h" @15
- include "include/core/SkSurfaceProps.h" @16
- include "include/private/base/SkTo.h" @17
- include "src/base/SkTInternalLList.h" @18
- include "src/core/SkMaskFilterBase.h" @19
- include "src/text/gpu/SubRunAllocator.h" @20
- include "src/text/gpu/SubRunContainer.h" @21
- include <cstddef> @23
- include <cstdint> @24
- include <tuple> @25
- class_specifier SkCanvas @27-27
- struct_specifier SkPoint @28-28
- struct_specifier SkStrikeDeviceInfo @29-29
- class_specifier GlyphRunList @32-32
- class_specifier StrikeForGPUCacheInterface @33-33
- class_specifier Slug @37-37
- class_specifier TextBlob @54-134
- struct_specifier Key @58-82
- function_definition (anonymous) @106-106
- function_definition size @113-113

### gfx/skia/skia/src/text/gpu/TextBlobRedrawCoordinator.cpp

Blob: `1d4d3e3b2b66fc0351cebb209d41ca17e0fb3e98`. Grammar: cpp. Status: contains-errors.

- include "src/text/gpu/TextBlobRedrawCoordinator.h" @8
- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkTypes.h" @12
- include "src/core/SkDevice.h" @13
- include "src/core/SkStrikeCache.h" @14
- include "src/text/GlyphRun.h" @15
- include <utility> @17
- class_specifier SkCanvas @19-19
- class_specifier SkPaint @20-20
- function_definition SkShouldPostMessageToBus @29-32
- function_definition TextBlobRedrawCoordinator @34-37
- function_definition drawGlyphRunList @39-49
- function_definition findOrCreateBlob @51-84
- function_definition post_purge_blob_message @86-90
- function_definition addOrReturnExisting @92-98
- function_definition find @100-114
- function_definition remove @116-119
- function_definition internalRemove @121-136
- function_definition freeAll @138-143
- function_definition purgeStaleBlobs @145-148
- function_definition internalPurgeStaleBlobs @150-170
- function_definition usedBytes @172-175
- function_definition isOverBudget @177-180
- function_definition internalCheckPurge @182-204
- function_definition internalAdd @206-223
- function_definition BlobIDCacheEntry::BlobIDCacheEntry @225-225
- function_definition BlobIDCacheEntry::BlobIDCacheEntry @227-227
- function_definition BlobIDCacheEntry::GetKey @229-232
- function_definition BlobIDCacheEntry::addBlob @234-240
- function_definition BlobIDCacheEntry::removeBlob @242-250
- function_definition BlobIDCacheEntry::find @252-256
- function_definition BlobIDCacheEntry::findBlobIndex @258-265

### gfx/skia/skia/src/text/gpu/TextBlobRedrawCoordinator.h

Blob: `860ab3600100fa62d19dc87c170fde1b9db99dd5`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkRefCnt.h" @11
- include "include/private/base/SkTArray.h" @12
- include "include/private/base/SkThreadAnnotations.h" @13
- include "src/base/SkSpinlock.h" @14
- include "src/base/SkTInternalLList.h" @15
- include "src/core/SkMessageBus.h" @16
- include "src/core/SkTHash.h" @17
- include "src/text/gpu/SubRunContainer.h" @18
- include "src/text/gpu/TextBlob.h" @19
- include <cstddef> @21
- include <cstdint> @22
- class_specifier GrTextBlobTestingPeer @24-24
- class_specifier SkCanvas @25-25
- class_specifier SkMatrix @26-26
- class_specifier SkPaint @27-27
- struct_specifier SkStrikeDeviceInfo @28-28
- class_specifier GlyphRunList @30-30
- class_specifier TextBlobRedrawCoordinator @41-125
- struct_specifier PurgeBlobMessage @54-60
- function_definition PurgeBlobMessage @55-56
- struct_specifier BlobIDCacheEntry @72-90

### gfx/skia/skia/src/text/gpu/VertexFiller.cpp

Blob: `f9cd3f87da7644e4cf84aadb9703d7360a179b8d`. Grammar: cpp. Status: syntax-clean.

- include "src/text/gpu/VertexFiller.h" @8
- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkRect.h" @12
- include "include/core/SkScalar.h" @13
- include "include/core/SkTypes.h" @14
- include "src/core/SkReadBuffer.h" @15
- include "src/core/SkWriteBuffer.h" @16
- include "src/gpu/MaskFormat.h" @17
- include "src/text/gpu/SubRunAllocator.h" @18
- include "src/text/gpu/SubRunContainer.h" @19
- include <optional> @21
- function_definition VertexFiller @27-36
- function_definition Make @38-47
- function_definition MakeFromBuffer @49-70
- function_definition flatten @72-78
- function_definition viewDifference @80-85
- function_definition CanUseDirect @90-105
- function_definition isLCD @107-107
- function_definition deviceRectAndCheckTransform @112-129
- function_definition boundsAndDeviceMatrix @131-163

### gfx/skia/skia/src/text/gpu/VertexFiller.h

Blob: `d2e8a6f768025e272db7abf036a4faa60c7dd922`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkRect.h" @12
- include "include/core/SkScalar.h" @13
- include "include/core/SkSpan.h" @14
- include "include/core/SkTypes.h" @15
- include "include/private/base/SkTLogic.h" @16
- include "src/base/SkVx.h" @17
- include "src/core/SkColorData.h" @18
- include <cstddef> @20
- include <optional> @21
- include <tuple> @22
- class_specifier SkReadBuffer @24-24
- class_specifier SkWriteBuffer @25-25
- enum_specifier MaskFormat @28-28
- class_specifier SubRunAllocator @32-32
- enum_specifier FillerType @34-37
- class_specifier VertexFiller @49-104
- function_definition unflattenSize @67-67
- function_definition maskFormat @79-79
- function_definition count @83-83
- function_definition topLefts @85-85
- function_definition canDrawDirect @87-87
- function_definition canUseDirect @89-91

### gfx/skia/skia/src/utils/SkBitSet.h

Blob: `24291ead843f06cfb8e296276e4292145c835125`. Grammar: cpp. Status: contains-errors.

- include "include/private/base/SkMalloc.h" @11
- include "include/private/base/SkTemplates.h" @12
- include "src/base/SkMathPriv.h" @13
- include <climits> @15
- include <cstring> @16
- include <limits> @17
- include <memory> @18
- include <optional> @19
- class_specifier SkBitSet @21-158
- function_definition SkBitSet @23-25
- function_definition SkBitSet @27-27
- function_definition (anonymous) @28-28
- function_definition SkBitSet @29-29
- function_definition (anonymous) @30-37
- function_definition ~SkBitSet @38-38
- function_definition operator== @41-47
- function_definition operator!= @49-51
- function_definition set @54-57
- function_definition set @60-64
- function_definition reset @67-70
- function_definition reset @73-77
- function_definition test @79-82
- function_definition size @84-86
- function_definition forEachSetIndex @90-103
- function_definition findFirst @108-119
- function_definition findFirstUnset @122-136
- function_definition chunkFor @147-149
- function_definition ChunkMaskFor @151-153
- function_definition NumChunksFor @155-157

### gfx/skia/skia/src/utils/SkCallableTraits.h

Blob: `e30159d5e465004891d256e757be79944d54eb0c`. Grammar: cpp. Status: contains-errors.

- include <type_traits> @11
- include <tuple> @12
- struct_specifier sk_base_callable_traits @14-21
- struct_specifier argument @17-20
- struct_specifier SkCallableTraits @50-50
- struct_specifier SkCallableTraits<R T::*> @78-78

### gfx/skia/skia/src/utils/SkCamera.cpp

Blob: `f514524953f77a4f82a4cda611dbc3df688b6f35`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkCamera.h" @8
- function_definition SkScalarDotDiv @10-20
- function_definition SkPatch3D @24-26
- function_definition reset @28-32
- function_definition transform @34-42
- function_definition dotWith @44-50
- function_definition SkCamera3D @54-56
- function_definition reset @58-66
- function_definition update @68-70
- function_definition doUpdate @72-111
- function_definition patchToMatrix @113-148
- function_definition Sk3DView @152-154
- function_definition ~Sk3DView @156-163
- function_definition save @165-170
- function_definition restore @172-177
- function_definition setCameraLocation @180-187
- function_definition getCameraLocationX @189-191
- function_definition getCameraLocationY @193-195
- function_definition getCameraLocationZ @197-199
- function_definition translate @202-204
- function_definition rotateX @206-208
- function_definition rotateY @210-212
- function_definition rotateZ @214-216
- function_definition dotWithNormal @218-222
- function_definition getMatrix @224-230
- include "include/core/SkCanvas.h" @232
- function_definition applyToCanvas @234-239

### gfx/skia/skia/src/utils/SkCanvasStack.cpp

Blob: `ea3918b8bcb42cbe032293f0c52d1e5b0cf93ce3`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkCanvasStack.h" @8
- include "include/core/SkRect.h" @10
- include "include/core/SkScalar.h" @11
- include "include/core/SkShader.h" @12
- include "include/private/base/SkTDArray.h" @13
- include <utility> @14
- class_specifier SkPath @16-16
- class_specifier SkRRect @17-17
- function_definition SkCanvasStack @19-20
- function_definition ~SkCanvasStack @22-24
- function_definition pushCanvas @26-52
- function_definition removeAll @54-57
- function_definition clipToZOrderedBounds @64-69
- function_definition didSetM44 @78-85
- function_definition onClipRect @87-90
- function_definition onClipRRect @92-95
- function_definition onClipPath @97-100
- function_definition onClipShader @102-105
- function_definition onClipRegion @107-117

### gfx/skia/skia/src/utils/SkCanvasStack.h

Blob: `c27827931c6f714ca911527be323b977b809ef2e`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkCanvas.h" @11
- include "include/core/SkM44.h" @12
- include "include/core/SkPoint.h" @13
- include "include/core/SkRefCnt.h" @14
- include "include/core/SkRegion.h" @15
- include "include/core/SkTypes.h" @16
- include "include/private/base/SkTArray.h" @17
- include "include/private/base/SkTypeTraits.h" @18
- include "include/utils/SkNWayCanvas.h" @19
- include <memory> @21
- include <type_traits> @22
- class_specifier SkPath @24-24
- class_specifier SkRRect @25-25
- class_specifier SkShader @26-26
- enum_specifier SkClipOp @27-27
- struct_specifier SkRect @28-28
- class_specifier SkCanvasStack @36-80
- function_definition addCanvas @50-50
- function_definition removeCanvas @51-51
- struct_specifier CanvasData @65-75

### gfx/skia/skia/src/utils/SkCanvasStateUtils.cpp

Blob: `f028bb3f721b7eabb01a42a11e28d9fc183539e1`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkCanvasStateUtils.h" @8
- include "include/core/SkAlphaType.h" @10
- include "include/core/SkBitmap.h" @11
- include "include/core/SkCanvas.h" @12
- include "include/core/SkColorType.h" @13
- include "include/core/SkImageInfo.h" @14
- include "include/core/SkMatrix.h" @15
- include "include/core/SkPixmap.h" @16
- include "include/core/SkPoint.h" @17
- include "include/core/SkRect.h" @18
- include "include/core/SkSize.h" @19
- include "include/private/base/SkMalloc.h" @20
- include "src/core/SkDevice.h" @21
- include "src/core/SkWriter32.h" @22
- include "src/utils/SkCanvasStack.h" @23
- include <cstddef> @25
- include <cstdint> @26
- include <utility> @27
- enum_specifier RasterConfigs @42-46
- enum_specifier CanvasBackends @49-54
- struct_specifier ClipRect @57-59
- struct_specifier SkMCState @61-66
- struct_specifier SkCanvasLayerState @70-88
- struct_specifier raster @79-83
- struct_specifier gpu @84-86
- class_specifier SkCanvasState @90-110
- function_definition SkCanvasState @92-98
- class_specifier SkCanvasState_v1 @112-149
- function_definition SkCanvasState_v1 @116-122
- function_definition ~SkCanvasState_v1 @124-140
- function_definition setup_MC_state @153-176
- function_definition CaptureCanvasState @178-239
- function_definition setup_canvas_from_MC_state @243-268
- function_definition make_canvas_from_canvas_layer @270-297
- function_definition MakeFromCanvasState @299-328
- function_definition ReleaseCanvasState @332-338

### gfx/skia/skia/src/utils/SkCharToGlyphCache.cpp

Blob: `b96c06618348c8d1153073d1699899ca210d5933`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkCharToGlyphCache.h" @8
- function_definition SkCharToGlyphCache @10-12
- function_definition ~SkCharToGlyphCache @14-14
- function_definition reset @16-27
- function_definition find_simple @38-49
- function_definition find_with_slope @51-93
- function_definition findGlyphIndex @95-107
- function_definition insertCharAndGlyph @109-129

### gfx/skia/skia/src/utils/SkCharToGlyphCache.h

Blob: `0171faa65aab4ac130754b10294b9ed865ea8499`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "include/private/base/SkTDArray.h" @12
- include "include/private/base/SkTo.h" @13
- class_specifier SkCharToGlyphCache @15-61
- function_definition count @21-23
- function_definition addCharAndGlyph @48-55

### gfx/skia/skia/src/utils/SkClipStackUtils.cpp

Blob: `37f899d3a8065e3ab0e93e144187ab7931f3ea40`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkClipStackUtils.h" @8
- include "include/core/SkPath.h" @10
- include "include/core/SkPathTypes.h" @11
- include "include/pathops/SkPathOps.h" @12
- include "src/core/SkClipStack.h" @13
- enum_specifier SkClipOp @15-15
- function_definition SkClipStack_AsPath @17-45

### gfx/skia/skia/src/utils/SkClipStackUtils.h

Blob: `191918f921a65cc4f08ac684c4e9b3e6a53ae912`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- class_specifier SkClipStack @13-13
- class_specifier SkPath @14-14

### gfx/skia/skia/src/utils/SkCustomTypeface.cpp

Blob: `4ed4aa63f69964731c65a4bbf133abdf9f3159f3`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkCustomTypeface.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkColor.h" @11
- include "include/core/SkData.h" @12
- include "include/core/SkDrawable.h" @13
- include "include/core/SkFontArguments.h" @14
- include "include/core/SkFontMetrics.h" @15
- include "include/core/SkFontParameters.h" @16
- include "include/core/SkFontStyle.h" @17
- include "include/core/SkFontTypes.h" @18
- include "include/core/SkMatrix.h" @19
- include "include/core/SkPaint.h" @20
- include "include/core/SkPath.h" @21
- include "include/core/SkPathBuilder.h" @22
- include "include/core/SkPoint.h" @23
- include "include/core/SkRect.h" @24
- include "include/core/SkRefCnt.h" @25
- include "include/core/SkScalar.h" @26
- include "include/core/SkSerialProcs.h" @27
- include "include/core/SkSpan.h" @28
- include "include/core/SkStream.h" @29
- include "include/core/SkString.h" @30
- include "include/core/SkTypeface.h" @31
- include "include/core/SkTypes.h" @32
- include "include/private/base/SkAlign.h" @33
- include "include/private/base/SkFixed.h" @34
- include "include/private/base/SkMalloc.h" @35
- include "include/private/base/SkTo.h" @36
- include "src/core/SkAdvancedTypefaceMetrics.h" @37
- include "src/core/SkFontDescriptor.h" @38
- include "src/core/SkGlyph.h" @39
- include "src/core/SkMask.h" @40
- include "src/core/SkScalerContext.h" @41
- include "src/core/SkStreamPriv.h" @42
- include <algorithm> @44
- include <cstdint> @45
- include <cstring> @46
- include <memory> @47
- include <optional> @48
- include <utility> @49
- include <vector> @50
- class_specifier SkArenaAlloc @52-52
- class_specifier SkDescriptor @53-53
- function_definition scale_fontmetrics @59-86
- class_specifier SkUserTypeface @88-148
- function_definition SkUserTypeface @93-98
- function_definition onOpenExistingStream @121-121
- function_definition onMakeClone @123-125
- function_definition onCountGlyphs @126-126
- function_definition onGetUPEM @127-127
- function_definition onComputeBounds @128-131
- function_definition getPostScriptGlyphNames @135-135
- function_definition onGlyphMaskNeedsCurrentColor @136-136
- function_definition onGetVariationDesignPosition @137-138
- function_definition onGetVariationDesignParameters @139-141
- function_definition onGetTableTags @142-142
- function_definition onGetTableData @143-143
- function_definition glyphCount @145-147
- function_definition SkCustomTypefaceBuilder @150-152
- function_definition setMetrics @154-156
- function_definition setFontStyle @158-160
- function_definition (anonymous) @162-168
- function_definition setGlyph @170-175
- function_definition setGlyph @177-184
- function_definition detach @186-204
- function_definition onFilterRec @208-211
- function_definition getGlyphToUnicodeMap @213-218
- function_definition onGetAdvancedMetrics @220-222
- function_definition onGetFontDescriptor @224-227
- function_definition onCharsToGlyphs @229-236
- function_definition onGetFamilyName @238-240
- function_definition onGetPostScriptName @242-244
- function_definition onCreateFamilyNameIterator @246-248
- class_specifier SkUserScalerContext @252-369
- function_definition SkUserScalerContext @254-259
- function_definition userTF @261-263
- function_definition generateMetrics @266-293
- function_definition generateImage @295-315
- function_definition generatePath @317-323
- function_definition generateDrawable @325-360
- class_specifier DrawableMatrixWrapper @326-353
- function_definition DrawableMatrixWrapper @328-331
- function_definition onGetBounds @333-335
- function_definition onApproximateBytesUsed @337-339
- function_definition onDraw @341-349
- function_definition generateFontMetrics @362-365
- function_definition onCreateScalerContext @371-375
- enum_specifier GlyphType @384-384
- function_definition onOpenStream @386-422
- class_specifier AutoRestorePosition @424-440
- function_definition AutoRestorePosition @428-430
- function_definition ~AutoRestorePosition @432-436
- function_definition markDone @439-439
- function_definition Deserialize @442-517
- function_definition MakeFromStream @519-522

### gfx/skia/skia/src/utils/SkDashPath.cpp

Blob: `a0c717822a56192beb16afb73092b586dce6fedc`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkDashPathPriv.h" @8
- include "include/core/SkPaint.h" @10
- include "include/core/SkPath.h" @11
- include "include/core/SkPathBuilder.h" @12
- include "include/core/SkPathMeasure.h" @13
- include "include/core/SkPoint.h" @14
- include "include/core/SkRect.h" @15
- include "include/core/SkScalar.h" @16
- include "include/core/SkSpan.h" @17
- include "include/core/SkStrokeRec.h" @18
- include "include/core/SkTypes.h" @19
- include "include/private/base/SkAlign.h" @20
- include "include/private/base/SkFloatingPoint.h" @21
- include "include/private/base/SkTo.h" @22
- include "src/core/SkPathEffectBase.h" @23
- include "src/core/SkPointPriv.h" @24
- include <algorithm> @26
- include <cmath> @27
- include <cstddef> @28
- include <cstdint> @29
- function_definition is_even @31-33
- function_definition find_first_interval @35-52
- function_definition CalcDashParameters @54-90
- function_definition outset_for_stroke @92-101
- function_definition adjust_zero_length_line @108-111
- function_definition clip_line @113-167
- function_definition cull_path @172-233
- class_specifier SpecialLineRec @235-306
- function_definition init @237-278
- function_definition addSegment @280-299
- function_definition InternalFilter @309-458
- function_definition FilterDashPath @460-472
- function_definition ValidDashPath @474-487

### gfx/skia/skia/src/utils/SkDashPathPriv.h

Blob: `4768d11c57fdf6fdc36722975eede736caa9ecdc`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPathEffect.h" @11
- include "include/core/SkSpan.h" @12
- include "src/core/SkPathEffectBase.h" @13
- enum_specifier StrokeRecApplication @38-41

### gfx/skia/skia/src/utils/SkEventTracer.cpp

Blob: `ee8730e411479a0102da7c059b2fa3fcbe01e5ab`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkEventTracer.h" @8
- include "include/private/base/SkMacros.h" @10
- include <stdlib.h> @12
- include <atomic> @13
- class_specifier SkDefaultEventTracer @15-44
- function_definition addTraceEvent @16-25
- function_definition updateTraceEventDuration @27-30
- function_definition getCategoryGroupEnabled @32-35
- function_definition getCategoryGroupName @36-40
- function_definition newTracingSection @43-43
- function_definition SetInstance @49-65
- function_definition GetInstance @67-73

### gfx/skia/skia/src/utils/SkFloatToDecimal.cpp

Blob: `ef890427f8bb82a6b65ac4dd0b0d89f1208934ea`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkFloatToDecimal.h" @8
- include "include/core/SkTypes.h" @10
- include <cfloat> @12
- include <cmath> @13
- include <limits.h> @16
- function_definition pow_by_squaring @20-33
- function_definition pow10 @36-62
- function_definition SkFloatToDecimal @73-187

### gfx/skia/skia/src/utils/SkFloatToDecimal.h

Blob: `9ea5968a62d1a58c79581c7be47bb7504c39a0b5`. Grammar: cpp. Status: syntax-clean.


### gfx/skia/skia/src/utils/SkFloatUtils.h

Blob: `172449c14ae8bd5e34791b91b71901479bb8931f`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include <limits.h> @12
- include <float.h> @13
- class_specifier SkTypeWithSize @16-20
- class_specifier SkTypeWithSize<32> @23-26
- class_specifier SkTypeWithSize<64> @29-32
- struct_specifier SkNumericLimits @35-37
- struct_specifier SkNumericLimits<double> @40-42
- struct_specifier SkNumericLimits<float> @45-47
- class_specifier SkFloatingPoint @55-171
- function_definition SkFloatingPoint @90-90
- function_definition exponent_bits @93-93
- function_definition fraction_bits @96-96
- function_definition is_nan @99-104
- function_definition AlmostEquals @113-121
- function_definition SignAndMagnitudeToBiased @149-157
- function_definition DistanceBetweenSignAndMagnitudeNumbers @163-168

### gfx/skia/skia/src/utils/SkGetExecutablePath.h

Blob: `ccf4c49fe5115321643c5576e5724e8d87cd981d`. Grammar: cpp. Status: syntax-clean.

- include <string> @11

### gfx/skia/skia/src/utils/SkGetExecutablePath_linux.cpp

Blob: `a83fb2c3766f4d91fa6c784e7c7ba04c2157413f`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkGetExecutablePath.h" @8
- include <linux/limits.h> @10
- include <sys/types.h> @11
- include <unistd.h> @12
- include <cstddef> @13
- function_definition SkGetExecutablePath @17-26

### gfx/skia/skia/src/utils/SkGetExecutablePath_mac.cpp

Blob: `14c73beb54551f25ec549389c4498b9d74f4da10`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkGetExecutablePath.h" @8
- include <mach-o/dyld.h> @10
- function_definition SkGetExecutablePath @12-21

### gfx/skia/skia/src/utils/SkGetExecutablePath_win.cpp

Blob: `71fbf882934144bd8d873199a43da0fd0aa19ea1`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkGetExecutablePath.h" @8
- include <windows.h> @10
- function_definition SkGetExecutablePath @12-16

### gfx/skia/skia/src/utils/SkJSONWriter.cpp

Blob: `25a70eb2789384f18ee369dc1aef8ddccf9ad527`. Grammar: cpp. Status: contains-errors.

- include "src/utils/SkJSONWriter.h" @8
- include <inttypes.h> @10
- include <stdarg.h> @11
- include <stdio.h> @12
- function_definition appendS64 @14-17
- function_definition appendU64 @19-22
- function_definition appendHexU64 @24-27
- function_definition appendf @29-42

### gfx/skia/skia/src/utils/SkJSONWriter.h

Blob: `3dd7932e2158a18136dd4682f3ceaa8f4cd1f8d1`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkStream.h" @11
- include "include/core/SkString.h" @12
- include "include/core/SkTypes.h" @13
- include "include/private/base/SkNoncopyable.h" @14
- include "include/private/base/SkTArray.h" @15
- include "src/base/SkUTF.h" @16
- include <cstring> @18
- include <cstdint> @19
- include <string> @20
- include <type_traits> @21
- class_specifier SkJSONWriter @38-417
- enum_specifier Mode @40-52
- function_definition SkJSONWriter @57-66
- function_definition ~SkJSONWriter @68-73
- function_definition flush @78-83
- function_definition appendName @90-104
- function_definition beginObject @114-121
- function_definition endObject @126-136
- function_definition beginArray @146-153
- function_definition endArray @158-168
- function_definition appendString @176-211
- function_definition appendString @212-214
- function_definition appendString @217-219
- function_definition appendNString @220-223
- function_definition appendCString @224-226
- function_definition appendPointer @228-228
- function_definition appendBool @229-236
- function_definition appendS32 @237-237
- function_definition appendU32 @239-239
- function_definition appendFloat @241-241
- function_definition appendDouble @242-242
- function_definition appendFloatDigits @243-246
- function_definition appendDoubleDigits @247-250
- function_definition appendHexU32 @251-251
- function_definition appendString @254-257
- function_definition appendString @258-261
- function_definition appendString @264-267
- function_definition appendNString @268-272
- function_definition appendCString @273-276
- function_definition appendFloatDigits @297-300
- function_definition appendDoubleDigits @301-304
- enum_specifier (anonymous) @307-312
- enum_specifier Scope @314-318
- enum_specifier State @320-328
- function_definition beginValue @332-350
- function_definition separator @352-363
- function_definition write @365-377
- function_definition scope @379-382
- function_definition multiline @384-387
- function_definition popScope @389-406

### gfx/skia/skia/src/utils/SkMatrix22.cpp

Blob: `25f3d60358fbcc83aa3a049eb6a2b35a82ad68af`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkMatrix22.h" @8
- include "include/core/SkMatrix.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkScalar.h" @12
- function_definition SkComputeGivensRotation @14-41

### gfx/skia/skia/src/utils/SkMatrix22.h

Blob: `c8bcd5f6bdbc437edb251e5e24d3eb4e2c2f1851`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPoint.h" @11
- class_specifier SkMatrix @13-13

### gfx/skia/skia/src/utils/SkMultiPictureDocument.cpp

Blob: `72377d0eb62ca7bfa12cd2d18dd8116eb3b8a5cb`. Grammar: cpp. Status: syntax-clean.

- include "include/docs/SkMultiPictureDocument.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkData.h" @11
- include "include/core/SkDocument.h" @12
- include "include/core/SkPicture.h" @13
- include "include/core/SkPictureRecorder.h" @14
- include "include/core/SkRect.h" @15
- include "include/core/SkScalar.h" @16
- include "include/core/SkSerialProcs.h" @17
- include "include/core/SkStream.h" @18
- include "include/private/base/SkDebug.h" @19
- include "include/private/base/SkTArray.h" @20
- include "include/private/base/SkTo.h" @21
- include "include/utils/SkNWayCanvas.h" @22
- include "src/utils/SkMultiPictureDocumentPriv.h" @23
- include <algorithm> @25
- include <climits> @26
- include <cstdint> @27
- include <cstring> @28
- include <functional> @29
- include <utility> @30
- function_definition join @57-63
- struct_specifier MultiPictureDocument @65-118
- function_definition MultiPictureDocument @72-77
- function_definition ~MultiPictureDocument @79-79
- function_definition onBeginPage @81-84
- function_definition onEndPage @85-92
- function_definition onClose @93-113
- function_definition onAbort @114-117
- struct_specifier PagerCanvas @120-147
- function_definition PagerCanvas @125-128
- function_definition nextCanvas @129-134
- function_definition onDrawAnnotation @135-146
- function_definition Make @152-156
- function_definition ReadPageCount @158-179
- function_definition ReadPageSizes @181-205
- function_definition Read @207-234

### gfx/skia/skia/src/utils/SkMultiPictureDocumentPriv.h

Blob: `5f64fd2f947866a8ffacbac80611b2629e9bbd96`. Grammar: cpp. Status: syntax-clean.

- include "include/docs/SkMultiPictureDocument.h" @11

### gfx/skia/skia/src/utils/SkNWayCanvas.cpp

Blob: `f979eb16c7739a284df83112909702d279372da6`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkNWayCanvas.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkColor.h" @11
- include "include/core/SkMatrix.h" @12
- include "include/core/SkPoint.h" @13
- include "include/core/SkRSXform.h" @14
- include "include/core/SkRect.h" @15
- include "include/core/SkRefCnt.h" @16
- include "include/core/SkScalar.h" @17
- include "include/core/SkShader.h" @18
- include "include/core/SkTypes.h" @19
- include "include/private/base/SkTDArray.h" @20
- include "include/utils/SkNoDrawCanvas.h" @21
- include "src/core/SkCanvasPriv.h" @22
- include <algorithm> @24
- include <iterator> @25
- include <utility> @26
- class_specifier GlyphRunList @29-29
- class_specifier SkData @32-32
- class_specifier SkDrawable @33-33
- class_specifier SkImage @34-34
- class_specifier SkPaint @35-35
- class_specifier SkPath @36-36
- class_specifier SkPicture @37-37
- class_specifier SkRRect @38-38
- class_specifier SkRegion @39-39
- class_specifier SkTextBlob @40-40
- class_specifier SkVertices @41-41
- enum_specifier SkBlendMode @42-42
- enum_specifier SkClipOp @43-43
- struct_specifier SkDrawShadowRec @44-44
- function_definition SkNWayCanvas @46-46
- function_definition ~SkNWayCanvas @48-50
- function_definition addCanvas @52-62
- function_definition removeCanvas @64-69
- function_definition removeAll @71-73
- class_specifier SkNWayCanvas::Iter @78-97
- function_definition Iter @80-82
- function_definition next @83-89
- function_definition operator-> @90-90
- function_definition get @91-91
- function_definition willSave @99-106
- function_definition getSaveLayerStrategy @108-117
- function_definition onDoSaveBehind @119-126
- function_definition willRestore @128-134
- function_definition didConcat44 @136-141
- function_definition didSetM44 @143-148
- function_definition didTranslate @150-155
- function_definition didScale @157-162
- function_definition onClipRect @164-170
- function_definition onClipRRect @172-178
- function_definition onClipPath @180-186
- function_definition onClipShader @188-194
- function_definition onClipRegion @196-202
- function_definition onResetClip @204-210
- function_definition onDrawPaint @212-217
- function_definition onDrawBehind @219-224
- function_definition onDrawPoints @226-232
- function_definition onDrawRect @234-239
- function_definition onDrawRegion @241-246
- function_definition onDrawOval @248-253
- function_definition onDrawArc @255-261
- function_definition onDrawRRect @263-268
- function_definition onDrawDRRect @270-275
- function_definition onDrawPath @277-282
- function_definition onDrawImage2 @284-290
- function_definition onDrawImageRect2 @292-299
- function_definition onDrawImageLattice2 @301-308
- function_definition onDrawAtlas2 @310-322
- function_definition onDrawGlyphRunList @324-330
- function_definition onDrawTextBlob @332-338
- function_definition onDrawSlug @340-345
- function_definition onDrawPicture @347-353
- function_definition onDrawDrawable @355-360
- function_definition onDrawVerticesObject @362-368
- function_definition onDrawPatch @370-377
- function_definition onDrawShadowRec @379-384
- function_definition onDrawAnnotation @386-391
- function_definition onDrawEdgeAAQuad @393-399
- function_definition onDrawEdgeAAImageSet2 @401-410

### gfx/skia/skia/src/utils/SkNullCanvas.cpp

Blob: `3179282156fc82b2a878790b8daa5a2998235505`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkNullCanvas.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/utils/SkNWayCanvas.h" @11
- function_definition SkMakeNullCanvas @13-17

### gfx/skia/skia/src/utils/SkOSPath.cpp

Blob: `f960d1fde48be990f39798c66910312167873147`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkOSPath.h" @8
- include "include/core/SkTypes.h" @10
- include <string.h> @12
- function_definition Join @14-21
- function_definition Basename @23-34
- function_definition Dirname @36-49

### gfx/skia/skia/src/utils/SkOSPath.h

Blob: `783e985fd64f6f621cd3bb8b59e8836360b7597b`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkString.h" @11
- class_specifier SkOSPath @16-53

### gfx/skia/skia/src/utils/SkOrderedFontMgr.cpp

Blob: `fba9dd810b384c8158987d3d616c0ebef26546f8`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkOrderedFontMgr.h" @8
- include "include/core/SkData.h" @10
- include "include/core/SkFontStyle.h" @11
- include "include/core/SkStream.h" @12
- include "include/core/SkTypeface.h" @13
- include <utility> @15
- class_specifier SkString @17-17
- struct_specifier SkFontArguments @18-18
- function_definition SkOrderedFontMgr @20-20
- function_definition ~SkOrderedFontMgr @21-21
- function_definition append @23-25
- function_definition onCountFamilies @27-33
- function_definition onGetFamilyName @35-43
- function_definition onCreateStyleSet @45-54
- function_definition onMatchFamily @56-64
- function_definition onMatchFamilyStyle @66-74
- function_definition onMatchFamilyStyleCharacter @76-87
- function_definition onLegacyMakeTypeface @89-96
- function_definition onMakeFromData @100-102
- function_definition onMakeFromStreamIndex @104-107
- function_definition onMakeFromStreamArgs @109-112
- function_definition onMakeFromFile @114-116

### gfx/skia/skia/src/utils/SkPaintFilterCanvas.cpp

Blob: `022976a01dfe4332224066d0b516a9b8095d45b5`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkPaintFilterCanvas.h" @8
- include "include/core/SkBlendMode.h" @10
- include "include/core/SkMatrix.h" @11
- include "include/core/SkPaint.h" @12
- include "include/core/SkPixmap.h" @13
- include "include/core/SkPoint.h" @14
- include "include/core/SkRSXform.h" @15
- include "include/core/SkRect.h" @16
- include "include/core/SkSurface.h" @17
- include "include/core/SkSurfaceProps.h" @18
- include <optional> @20
- class_specifier SkData @22-22
- class_specifier SkDrawable @23-23
- class_specifier SkImage @24-24
- class_specifier SkPath @25-25
- class_specifier SkPicture @26-26
- class_specifier SkRRect @27-27
- class_specifier SkRegion @28-28
- class_specifier SkTextBlob @29-29
- class_specifier SkVertices @30-30
- struct_specifier SkDrawShadowRec @31-31
- class_specifier SkPaintFilterCanvas::AutoPaintFilter @33-50
- function_definition AutoPaintFilter @35-38
- function_definition AutoPaintFilter @40-41
- function_definition (anonymous) @43-43
- function_definition shouldDraw @45-45
- function_definition SkPaintFilterCanvas @52-61
- function_definition onDrawPaint @63-68
- function_definition onDrawBehind @70-75
- function_definition onDrawPoints @77-83
- function_definition onDrawRect @85-90
- function_definition onDrawRRect @92-97
- function_definition onDrawDRRect @99-105
- function_definition onDrawRegion @107-112
- function_definition onDrawOval @114-119
- function_definition onDrawArc @121-127
- function_definition onDrawPath @129-134
- function_definition onDrawImage2 @136-142
- function_definition onDrawImageRect2 @144-151
- function_definition onDrawImageLattice2 @153-160
- function_definition onDrawVerticesObject @162-168
- function_definition onDrawPatch @170-177
- function_definition onDrawPicture @179-199
- function_definition onDrawDrawable @201-209
- function_definition onDrawGlyphRunList @211-217
- function_definition onDrawTextBlob @219-225
- function_definition onDrawAtlas2 @227-236
- function_definition onDrawAnnotation @238-240
- function_definition onDrawShadowRec @242-244
- function_definition onDrawEdgeAAQuad @246-256
- function_definition onDrawEdgeAAImageSet2 @258-269
- function_definition onNewSurface @271-274
- function_definition onPeekPixels @276-278
- function_definition onAccessTopLayerPixels @280-291
- function_definition onImageInfo @293-295
- function_definition onGetProps @297-302

### gfx/skia/skia/src/utils/SkParse.cpp

Blob: `ae59e93ec2fa307dba7a5b8a7af3fd447f2f9fbd`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkScalar.h" @8
- include "include/core/SkTypes.h" @9
- include "include/private/base/SkTo.h" @10
- include "include/utils/SkParse.h" @11
- include <cstdint> @13
- include <cstdlib> @14
- include <cstring> @15
- include <limits> @16
- include <string> @17
- function_definition is_between @19-22
- function_definition is_ws @24-27
- function_definition is_digit @29-32
- function_definition is_sep @34-37
- function_definition to_hex @39-49
- function_definition is_hex @51-54
- function_definition skip_ws @56-62
- function_definition skip_sep @64-70
- function_definition Count @72-91
- function_definition Count @93-112
- function_definition FindHex @114-141
- function_definition FindS32 @143-175
- function_definition FindScalar @177-190
- function_definition FindScalars @192-211
- function_definition lookup_str @213-219
- function_definition FindBool @221-237
- function_definition FindList @239-263

### gfx/skia/skia/src/utils/SkParseColor.cpp

Blob: `ae6a412fdf0df147e9d762bf58bff576fed791ec`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkParse.h" @7
- include "include/core/SkColor.h" @9
- include "include/core/SkTypes.h" @10
- include <algorithm> @12
- include <cstddef> @13
- include <cstdint> @14
- include <cstring> @15
- include <iterator> @16
- struct_specifier ColorRec @161-163
- function_definition FindNamedColor @306-324
- function_definition nib2byte @343-347
- function_definition FindColor @349-388

### gfx/skia/skia/src/utils/SkParsePath.cpp

Blob: `dc38257ceb7100d04876a5d72da4feee7f6e2d74`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPath.h" @8
- include "include/core/SkPathBuilder.h" @9
- include "include/core/SkPathTypes.h" @10
- include "include/core/SkPoint.h" @11
- include "include/core/SkScalar.h" @12
- include "include/core/SkStream.h" @13
- include "include/core/SkString.h" @14
- include "include/core/SkTypes.h" @15
- include "include/utils/SkParse.h" @16
- include "include/utils/SkParsePath.h" @17
- include "src/core/SkGeometry.h" @18
- include <cstdio> @20
- function_definition is_between @22-24
- function_definition is_ws @26-28
- function_definition is_digit @30-32
- function_definition is_sep @34-36
- function_definition is_lower @38-40
- function_definition to_upper @42-44
- function_definition skip_ws @46-51
- function_definition skip_sep @53-60
- function_definition find_points @64-74
- function_definition find_scalar @78-89
- function_definition find_flag @95-105
- function_definition FromSVGString @107-241
- function_definition ToSVGString @245-306

### gfx/skia/skia/src/utils/SkPatchUtils.cpp

Blob: `2e4f9f2fb021faace813e893fed428139ae6e407`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkPatchUtils.h" @8
- include "include/core/SkAlphaType.h" @10
- include "include/core/SkColorSpace.h" @11
- include "include/core/SkColorType.h" @12
- include "include/core/SkImageInfo.h" @13
- include "include/core/SkMatrix.h" @14
- include "include/core/SkPoint.h" @15
- include "include/core/SkScalar.h" @16
- include "include/core/SkSize.h" @17
- include "include/core/SkTypes.h" @18
- include "include/core/SkVertices.h" @19
- include "include/private/base/SkFloatingPoint.h" @20
- include "include/private/base/SkMath.h" @21
- include "include/private/base/SkTPin.h" @22
- include "include/private/base/SkTo.h" @23
- include "src/base/SkArenaAlloc.h" @24
- include "src/base/SkVx.h" @25
- include "src/core/SkColorData.h" @26
- include "src/core/SkColorSpacePriv.h" @27
- include "src/core/SkConvertPixels.h" @28
- include "src/core/SkGeometry.h" @29
- include <algorithm> @31
- include <cstdint> @32
- include <cstring> @33
- enum_specifier CubicCtrlPts @36-56
- enum_specifier Corner @59-64
- class_specifier FwDCubicEvaluator @84-143
- function_definition FwDCubicEvaluator @92-97
- function_definition restart @102-114
- function_definition done @119-121
- function_definition next @126-133
- function_definition getCtrlPoints @135-137
- function_definition approx_arc_length @154-163
- function_definition bilerp @165-170
- function_definition bilerp @172-180
- function_definition GetLevelOfDetail @182-210
- function_definition GetTopCubic @212-217
- function_definition GetBottomCubic @219-224
- function_definition GetLeftCubic @226-231
- function_definition GetRightCubic @233-238
- function_definition skcolor_to_float @240-246
- function_definition float_to_skcolor @248-254
- function_definition MakeVertices @256-390

### gfx/skia/skia/src/utils/SkPatchUtils.h

Blob: `bed0deab7e60f4f54ff4cfaa1945cf9c17079d7b`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkColor.h" @11
- include "include/core/SkRefCnt.h" @12
- class_specifier SkColorSpace @14-14
- class_specifier SkMatrix @15-15
- class_specifier SkVertices @16-16
- struct_specifier SkISize @17-17
- struct_specifier SkPoint @18-18
- class_specifier SkPatchUtils @20-58
- enum_specifier (anonymous) @24-28

### gfx/skia/skia/src/utils/SkPolyUtils.cpp

Blob: `fa93cfccfc4ff74ef51b1f76b443071016c0c94e`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkPolyUtils.h" @8
- include "include/core/SkRect.h" @10
- include "include/core/SkTypes.h" @11
- include "include/private/base/SkDebug.h" @12
- include "include/private/base/SkFloatingPoint.h" @13
- include "include/private/base/SkMalloc.h" @14
- include "include/private/base/SkTArray.h" @15
- include "include/private/base/SkTDArray.h" @16
- include "include/private/base/SkTemplates.h" @17
- include "src/base/SkTDPQueue.h" @18
- include "src/base/SkTInternalLList.h" @19
- include "src/base/SkVx.h" @20
- include "src/core/SkPointPriv.h" @21
- include "src/core/SkRectPriv.h" @22
- include <algorithm> @24
- include <cstdint> @25
- include <limits> @26
- include <new> @27
- struct_specifier OffsetSegment @36-39
- function_definition compute_side @46-54
- function_definition SkGetPolygonWinding @57-75
- function_definition compute_offset_vector @78-88
- function_definition outside_interval @91-94
- function_definition zero_length @97-99
- function_definition compute_intersection @106-194
- function_definition SkIsConvexPolygon @196-250
- struct_specifier OffsetEdge @252-313
- function_definition init @261-266
- function_definition checkIntersection @269-282
- function_definition computeCrossingDistance @287-311
- function_definition remove_node @315-322
- function_definition SkInsetConvexPolygon @338-485
- function_definition SkComputeRadialSteps @490-522
- function_definition left @527-529
- function_definition right @532-534
- struct_specifier Vertex @536-547
- function_definition Left @537-539
- enum_specifier VertexFlags @549-552
- struct_specifier ActiveEdge @554-695
- function_definition ActiveEdge @555-555
- function_definition ActiveEdge @556-565
- function_definition aboveIfLeft @570-621
- function_definition above @624-632
- function_definition intersect @634-671
- function_definition intersect @673-675
- function_definition lessThan @677-682
- function_definition equals @684-686
- class_specifier ActiveEdgeList @697-1084
- function_definition ActiveEdgeList @699-703
- function_definition ~ActiveEdgeList @704-707
- function_definition insert @709-824
- function_definition replace @827-884
- function_definition remove @886-995
- function_definition allocate @999-1006
- function_definition IsRed @1011-1013
- function_definition SingleRotation @1015-1025
- function_definition DoubleRotation @1027-1031
- function_definition VerifyTree @1034-1078
- function_definition SkIsSimplePolygon @1092-1173
- function_definition setup_offset_edge @1178-1184
- function_definition is_reflex_vertex @1186-1193
- function_definition SkOffsetSimplePolygon @1195-1468
- struct_specifier TriangulationVertex @1472-1482
- enum_specifier VertexType @1475-1475
- function_definition compute_triangle_bounds @1484-1493
- function_definition point_in_triangle @1497-1520
- class_specifier ReflexHash @1523-1614
- function_definition init @1525-1553
- function_definition add @1555-1559
- function_definition remove @1561-1565
- function_definition checkTriangle @1567-1597
- function_definition hash @1600-1605
- function_definition reclassify_vertex @1617-1630
- function_definition SkTriangulateSimplePolygon @1632-1771

### gfx/skia/skia/src/utils/SkPolyUtils.h

Blob: `f00ec26cd7c4cd320c9e2725825e01c45a166d13`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkPoint.h" @11
- include "include/core/SkScalar.h" @12
- include <cstdint> @14
- struct_specifier SkRect @17-17
- class_specifier SkTDArray @18-18

### gfx/skia/skia/src/utils/SkShaderUtils.cpp

Blob: `4efa5cfa27ada19142f6d71f4e74cb09ca46977a`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkShaderUtils.h" @8
- include "include/core/SkString.h" @10
- include "include/private/base/SkTArray.h" @11
- include "src/core/SkStringUtils.h" @12
- include "src/sksl/SkSLProgramSettings.h" @13
- include "src/sksl/SkSLString.h" @14
- include <cstddef> @16
- include <iomanip> @17
- include <sstream> @18
- class_specifier GLSLPrettyPrint @24-242
- function_definition GLSLPrettyPrint @26-26
- function_definition prettify @28-141
- function_definition appendChar @144-148
- function_definition hasToken @152-164
- function_definition parseUntilNewline @166-177
- function_definition parseUntil @182-201
- function_definition tabString @204-210
- function_definition newline @214-219
- function_definition undoNewlineAfter @223-230
- function_definition PrettyPrint @244-247
- function_definition VisitLineByLine @249-256
- function_definition SpirvAsHexStream @258-275
- function_definition BuildShaderErrorMessage @277-285
- function_definition PrintShaderBanner @287-295

### gfx/skia/skia/src/utils/SkShaderUtils.h

Blob: `14259fac96b9adf4b20c50d1e4db76d87f948fab`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkSpan.h" @11
- include "include/private/base/SkDebug.h" @12
- include <cstdint> @14
- include <functional> @15
- include <string> @16
- enum_specifier ProgramKind @18-18
- function_definition PrintLineByLine @28-32

### gfx/skia/skia/src/utils/SkShadowTessellator.cpp

Blob: `7bdd7f1cadadcb93e95e2d0c944ab9b8c9e24efb`. Grammar: cpp. Status: syntax-clean.

- include "src/utils/SkShadowTessellator.h" @9
- include "include/core/SkColor.h" @11
- include "include/core/SkMatrix.h" @12
- include "include/core/SkPath.h" @13
- include "include/core/SkPoint.h" @14
- include "include/core/SkPoint3.h" @15
- include "include/core/SkRect.h" @16
- include "include/core/SkTypes.h" @17
- include "include/core/SkVertices.h" @18
- include "include/private/base/SkFloatingPoint.h" @19
- include "include/private/base/SkTDArray.h" @20
- include "include/private/base/SkTemplates.h" @21
- include "src/core/SkColorData.h" @22
- include "src/core/SkDrawShadowInfo.h" @23
- include "src/core/SkGeometry.h" @24
- include "src/core/SkPointPriv.h" @25
- include "src/core/SkRectPriv.h" @26
- include "src/utils/SkPolyUtils.h" @27
- include <algorithm> @29
- include <cstdint> @30
- include "src/gpu/ganesh/geometry/GrPathUtils.h" @34
- class_specifier SkBaseShadowTessellator @44-143
- function_definition ~SkBaseShadowTessellator @47-47
- function_definition releaseVertices @49-56
- function_definition vertexCount @63-63
- function_definition indexCount @64-64
- function_definition heightFunc @103-105
- function_definition compute_normal @145-157
- function_definition duplicate_pt @159-165
- function_definition perp_dot @167-171
- function_definition SkBaseShadowTessellator @173-193
- function_definition accumulateCentroid @195-216
- function_definition checkConvexity @218-236
- function_definition finishPathPolygon @238-261
- function_definition computeConvexShadow @263-383
- function_definition computeClipVectorsAndTestCentroid @385-412
- function_definition addEdge @414-472
- function_definition clipUmbraPoint @474-504
- function_definition addInnerPoint @506-536
- function_definition getClosestUmbraIndex @538-566
- function_definition computeConcaveShadow @568-605
- function_definition stitchConcaveRings @607-738
- function_definition sanitize_point @751-754
- function_definition handleLine @756-781
- function_definition handleLine @783-787
- function_definition handleQuad @789-812
- function_definition handleQuad @814-817
- function_definition handleCubic @819-838
- function_definition handleConic @840-858
- function_definition addArc @860-887
- function_definition appendTriangle @889-895
- function_definition appendQuad @897-908
- class_specifier SkAmbientShadowTessellator @912-921
- function_definition SkAmbientShadowTessellator @923-956
- function_definition spancpy @958-963
- function_definition computePathPolygon @965-1006
- class_specifier SkSpotShadowTessellator @1010-1022
- function_definition SkSpotShadowTessellator @1024-1071
- function_definition computeClipAndPathPolygons @1073-1157
- function_definition addToClip @1159-1163
- function_definition MakeAmbient @1167-1174
- function_definition MakeSpot @1176-1188

### gfx/skia/skia/src/utils/SkShadowTessellator.h

Blob: `9a6323a168ba1322e380767d050fe7c3b8184404`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkRefCnt.h" @13
- include "include/core/SkScalar.h" @14
- include <functional> @16
- class_specifier SkMatrix @18-18
- class_specifier SkPath @19-19
- class_specifier SkVertices @20-20
- struct_specifier SkPoint3 @21-21

### gfx/skia/skia/src/utils/SkShadowUtils.cpp

Blob: `982c9c167dc145f451ec18bd28a1dfd52f81e7f6`. Grammar: cpp. Status: contains-errors.

- include "include/utils/SkShadowUtils.h" @8
- include "include/core/SkBlendMode.h" @10
- include "include/core/SkBlender.h" @11
- include "include/core/SkBlurTypes.h" @12
- include "include/core/SkCanvas.h" @13
- include "include/core/SkColorFilter.h" @14
- include "include/core/SkM44.h" @15
- include "include/core/SkMaskFilter.h" @16
- include "include/core/SkMatrix.h" @17
- include "include/core/SkPaint.h" @18
- include "include/core/SkPath.h" @19
- include "include/core/SkPoint.h" @20
- include "include/core/SkPoint3.h" @21
- include "include/core/SkRect.h" @22
- include "include/core/SkRefCnt.h" @23
- include "include/core/SkVertices.h" @24
- include "include/private/SkIDChangeListener.h" @25
- include "include/private/base/SkFloatingPoint.h" @26
- include "include/private/base/SkTPin.h" @27
- include "include/private/base/SkTemplates.h" @28
- include "include/private/base/SkTo.h" @29
- include "src/base/SkRandom.h" @30
- include "src/core/SkBlurMask.h" @31
- include "src/core/SkColorFilterPriv.h" @32
- include "src/core/SkDevice.h" @33
- include "src/core/SkDrawShadowInfo.h" @34
- include "src/core/SkPathPriv.h" @35
- include "src/core/SkResourceCache.h" @36
- include "src/core/SkVerticesPriv.h" @37
- include "src/utils/SkShadowTessellator.h" @40
- include "src/gpu/ganesh/GrStyle.h" @44
- include "src/gpu/ganesh/geometry/GrStyledShape.h" @45
- include <algorithm> @48
- include <cstring> @49
- include <functional> @50
- include <memory> @51
- include <new> @52
- include <utility> @53
- class_specifier SkRRect @57-57
- function_definition resource_cache_shared_id @64-66
- struct_specifier AmbientVerticesFactory @69-94
- function_definition isCompatible @74-80
- function_definition makeVertices @82-93
- struct_specifier SpotVerticesFactory @97-175
- enum_specifier OccluderType @98-110
- function_definition isCompatible @119-145
- function_definition makeVertices @147-174
- class_specifier CachedTessellations @183-268
- function_definition size @185-185
- function_definition find @187-190
- function_definition add @192-195
- function_definition find @197-200
- function_definition add @202-205
- class_specifier Set @209-264
- function_definition size @211-211
- function_definition find @213-232
- function_definition add @234-252
- struct_specifier Entry @255-259
- class_specifier CachedTessellationsRec @274-302
- function_definition CachedTessellationsRec @276-281
- function_definition (anonymous) @283-285
- function_definition bytesUsed @287-287
- function_definition getCategory @289-289
- function_definition refTessellations @291-291
- function_definition find @294-297
- struct_specifier FindContext @311-325
- function_definition FindContext @312-313
- function_definition FindVisitor @333-345
- function_definition (anonymous) @353-355
- function_definition (anonymous) @357-357
- function_definition (anonymous) @358-358
- function_definition keyBytes @361-364
- function_definition writeKey @365-367
- function_definition isRRect @368-368
- function_definition keyBytes @370-370
- function_definition writeKey @371-371
- function_definition isRRect @372-372
- class_specifier ShadowInvalidator @387-409
- function_definition ShadowInvalidator @389-392
- function_definition (anonymous) @395-397
- function_definition FindVisitor @400-402
- function_definition changed @404-406
- function_definition draw_shadow @416-479
- function_definition tilted @482-484
- function_definition SkShadowUtils @487-540
- function_definition fill_shadow_rec @542-565
- function_definition SkShadowUtils @568-579
- function_definition SkShadowUtils @581-593
- function_definition validate_rec @597-600
- function_definition SkDevice @602-861

### gfx/skia/skia/src/utils/SkTextUtils.cpp

Blob: `8a47a9e4d3af9fca053240b86d668edb655303c7`. Grammar: cpp. Status: syntax-clean.

- include "include/utils/SkTextUtils.h" @8
- include "include/core/SkCanvas.h" @10
- include "include/core/SkFont.h" @11
- include "include/core/SkMatrix.h" @12
- include "include/core/SkPath.h" @13
- include "include/core/SkPathBuilder.h" @14
- include "include/core/SkPoint.h" @15
- include "include/core/SkScalar.h" @16
- include "include/core/SkTextBlob.h" @17
- include "include/private/base/SkTemplates.h" @18
- include "src/core/SkFontPriv.h" @19
- class_specifier SkPaint @23-23
- function_definition Draw @25-37
- function_definition GetPath @39-60
- struct_specifier Rec @45-48

### gfx/skia/skia/src/utils/mac/SkCGBase.h

Blob: `430e49b078429d98e0a7307d0c2a014059c5be0a`. Grammar: cpp. Status: syntax-clean.

- include "include/private/base/SkFeatures.h" @11
- include "include/core/SkScalar.h" @15
- include <CoreGraphics/CoreGraphics.h> @22
- function_definition SkScalarToCGFloat @27-29
- function_definition SkScalarFromCGFloat @31-33
- function_definition SkFloatFromCGFloat @35-37

### gfx/skia/skia/src/utils/mac/SkCGGeometry.h

Blob: `41fdec8323833262f8673a0df902c02693d231d1`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include <CoreGraphics/CoreGraphics.h> @19
- function_definition SkCGRectIsEmpty @27-29
- function_definition SkCGRectGetMinX @31-33
- function_definition SkCGRectGetMaxX @35-37
- function_definition SkCGRectGetMinY @39-41
- function_definition SkCGRectGetMaxY @43-45
- function_definition SkCGRectGetWidth @47-49

### gfx/skia/skia/src/utils/mac/SkCTFont.cpp

Blob: `5de88964641e4d8a188e87b5cdb4cbb078144b52`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "include/core/SkData.h" @12
- include "include/core/SkRefCnt.h" @13
- include "include/private/base/SkOnce.h" @14
- include "src/sfnt/SkOTTable_OS_2.h" @15
- include "src/sfnt/SkSFNTHeader.h" @16
- include "src/utils/mac/SkCTFont.h" @17
- include "src/utils/mac/SkUniqueCFRef.h" @18
- include <CoreText/CoreText.h> @25
- include <CoreText/CTFontManager.h> @26
- include <CoreGraphics/CoreGraphics.h> @27
- include <CoreFoundation/CoreFoundation.h> @28
- include <dlfcn.h> @31
- function_definition SkCTFontGetSmoothBehavior @218-276
- function_definition (anonymous) @278-321
- function_definition (anonymous) @323-434

### gfx/skia/skia/src/utils/mac/SkCTFont.h

Blob: `ef18938b2bee9b13f4ef15c98be1b50ba2b4b372`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include <CoreGraphics/CoreGraphics.h> @19
- enum_specifier SkCTFontSmoothBehavior @22-26

### gfx/skia/skia/src/utils/mac/SkCTFontCreateExactCopy.cpp

Blob: `d99f9a9700e359bd8e4708bdbbb042c9a62c0439`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @8
- include "src/utils/mac/SkCTFontCreateExactCopy.h" @11
- include "src/ports/SkTypeface_mac_ct.h" @13
- include "src/utils/mac/SkUniqueCFRef.h" @14
- include "nsCocoaFeatures.h" @17
- function_definition add_opsz_attr @29-35
- function_definition add_notrak_attr @38-44
- function_definition SkCTFontCreateExactCopy @46-59

### gfx/skia/skia/src/utils/mac/SkCTFontCreateExactCopy.h

Blob: `f39b15da383bb6cbc208ae03f6de6d6e8952c65a`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include <CoreGraphics/CoreGraphics.h> @19
- include <CoreText/CoreText.h> @20
- include "src/utils/mac/SkUniqueCFRef.h" @23
- struct_specifier OpszVariation @25-25

### gfx/skia/skia/src/utils/mac/SkCreateCGImageRef.cpp

Blob: `c7d91d8889d646bbd5affd07a574f6fd8ee0db0f`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @8
- include "include/core/SkBitmap.h" @11
- include "include/core/SkColorSpace.h" @12
- include "include/core/SkData.h" @13
- include "include/encode/SkICC.h" @14
- include "include/private/base/SkMacros.h" @15
- include "include/private/base/SkTo.h" @16
- include "include/utils/mac/SkCGUtils.h" @17
- include "src/core/SkColorData.h" @18
- include "src/utils/mac/SkUniqueCFRef.h" @19
- include <climits> @21
- include <memory> @22
- function_definition compute_cgalpha_info_rgba @24-33
- function_definition compute_cgalpha_info_bgra @35-44
- function_definition compute_cgalpha_info_4444 @45-52
- function_definition get_bitmap_info @54-87
- function_definition prepare_for_image_ref @89-105
- function_definition SkCreateCGImageRefWithColorspace @107-110
- function_definition SkCreateCGImageRef @112-145
- function_definition SkCGDrawBitmap @147-161
- function_definition SkCreateCGContext @165-186
- function_definition SkCopyPixelsFromCGImage @188-219
- function_definition SkCreateBitmapFromCGImage @221-253
- function_definition SkMakeImageFromCGImage @255-263
- function_definition SkCreateCGDataProvider @265-281
- function_definition SkMakeColorSpaceFromCGColorSpace @283-305
- function_definition SkCreateCGColorSpace @307-341

### gfx/skia/skia/src/utils/mac/SkUniqueCFRef.h

Blob: `750b9ae3322761ce98a921d70117c636a0d4ba46`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "include/private/base/SkTemplates.h" @14
- include <CoreFoundation/CoreFoundation.h> @16
- include <memory> @17
- include <type_traits> @18

### gfx/skia/skia/src/utils/win/SkAutoCoInitialize.cpp

Blob: `5b0f3f97457079fdc3758da7e94812eace186136`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "src/utils/win/SkAutoCoInitialize.h" @11
- include <objbase.h> @13
- include <winerror.h> @14
- function_definition SkAutoCoInitialize @16-20
- function_definition ~SkAutoCoInitialize @22-26
- function_definition succeeded @28-30

### gfx/skia/skia/src/utils/win/SkAutoCoInitialize.h

Blob: `e090315b1928a59f496012216950f1bdefe5993b`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "include/private/base/SkNoncopyable.h" @15
- include "src/base/SkLeanWindows.h" @16
- class_specifier SkAutoCoInitialize @22-29

### gfx/skia/skia/src/utils/win/SkDWrite.cpp

Blob: `b159e14d6ccbb5a023280b964328177ee68a2005`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @7
- include "include/core/SkString.h" @10
- include "include/private/base/SkOnce.h" @11
- include "src/utils/win/SkDWrite.h" @12
- include "src/utils/win/SkHRESULT.h" @13
- include <dwrite.h> @15
- function_definition release_dwrite_factory @24-28
- function_definition create_dwrite_factory @30-57
- function_definition sk_get_dwrite_factory @60-64
- function_definition sk_cstring_to_wchar @70-82
- function_definition sk_wchar_to_skstring @85-102
- function_definition sk_get_locale_string @107-127
- function_definition SkGetGetUserDefaultLocaleNameProc @129-141

### gfx/skia/skia/src/utils/win/SkDWrite.h

Blob: `4c447c2a7d533c9644d0bda1a28730b5ce3141ee`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkFontStyle.h" @11
- include "include/private/base/SkTemplates.h" @12
- include <dwrite.h> @14
- include <winsdkver.h> @15
- class_specifier SkString @17-17
- class_specifier AutoDWriteTable @50-70
- function_definition AutoDWriteTable @52-56
- function_definition ~AutoDWriteTable @57-61
- class_specifier AutoTDWriteTable @71-78
- function_definition AutoTDWriteTable @74-74
- function_definition get @76-76
- function_definition operator-> @77-77
- struct_specifier DWriteStyle @83-97
- function_definition DWriteStyle @84-93

### gfx/skia/skia/src/utils/win/SkDWriteFontFileStream.cpp

Blob: `e574cf135137605c583a92b17cb42ec8460e0d84`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @7
- include "include/core/SkTypes.h" @10
- include "include/private/base/SkTFitsIn.h" @11
- include "include/private/base/SkTemplates.h" @12
- include "src/utils/win/SkDWriteFontFileStream.h" @13
- include "src/utils/win/SkHRESULT.h" @14
- include "src/utils/win/SkTScopedComPtr.h" @15
- include <dwrite.h> @17
- function_definition SkDWriteFontFileStream @24-29
- function_definition ~SkDWriteFontFileStream @31-35
- function_definition read @37-80
- function_definition isAtEnd @82-84
- function_definition rewind @86-89
- function_definition onDuplicate @91-93
- function_definition getPosition @95-97
- function_definition seek @99-103
- function_definition move @105-107
- function_definition onFork @109-113
- function_definition getLength @115-122
- function_definition getMemoryBase @124-134
- function_definition Create @139-147
- function_definition SkDWriteFontFileStreamWrapper @149-151
- function_definition QueryInterface @153-162
- function_definition AddRef @164-166
- function_definition Release @168-174
- function_definition ReadFileFragment @176-219
- function_definition ReleaseFileFragment @221-223
- function_definition GetFileSize @225-228
- function_definition GetLastWriteTime @230-234

### gfx/skia/skia/src/utils/win/SkDWriteFontFileStream.h

Blob: `71ef04c16562f70d18595a7f166dd377ab9f7b25`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @11
- include "include/core/SkStream.h" @13
- include "include/private/base/SkMutex.h" @14
- include "src/utils/win/SkObjBase.h" @15
- include "src/utils/win/SkTScopedComPtr.h" @16
- include <dwrite.h> @18
- class_specifier SkDWriteFontFileStream @24-53
- function_definition duplicate @38-40
- function_definition fork @41-43
- class_specifier SkDWriteFontFileStreamWrapper @59-87
- function_definition ~SkDWriteFontFileStreamWrapper @82-82

### gfx/skia/skia/src/utils/win/SkDWriteGeometrySink.cpp

Blob: `6f8126e38527611e88ba225c4b1ab624d48c62b8`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @8
- include "include/core/SkPathBuilder.h" @11
- include "src/utils/SkFloatUtils.h" @12
- include "src/utils/win/SkDWriteGeometrySink.h" @13
- include "src/utils/win/SkObjBase.h" @14
- include <dwrite.h> @16
- include <d2d1.h> @17
- function_definition SkDWriteGeometrySink @19-20
- function_definition ~SkDWriteGeometrySink @22-22
- function_definition QueryInterface @24-36
- function_definition AddRef @38-40
- function_definition Release @42-48
- function_definition SetFillMode @50-62
- function_definition SetSegmentFlags @64-68
- function_definition BeginFigure @70-76
- function_definition AddLines @78-85
- function_definition approximately_equal @87-90
- struct_specifier Cubic @92-95
- function_definition check_quadratic @97-114
- function_definition AddBeziers @116-138
- function_definition EndFigure @140-144
- function_definition Close @146-148
- function_definition Create @150-153

### gfx/skia/skia/src/utils/win/SkDWriteGeometrySink.h

Blob: `84d68ba6002e658620f859e1006be8dbd42fbd36`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkPathBuilder.h" @11
- include "src/utils/win/SkObjBase.h" @12
- include <dwrite.h> @14
- include <d2d1.h> @15
- class_specifier SkDWriteGeometrySink @17-54
- function_definition goingTo @24-30
- function_definition currentIsNot @32-34

### gfx/skia/skia/src/utils/win/SkDWriteNTDDI_VERSION.h

Blob: `c4d611f2707670a67a2dce8c95c858f21bba2fdf`. Grammar: cpp. Status: syntax-clean.


### gfx/skia/skia/src/utils/win/SkHRESULT.cpp

Blob: `bc5ac08adcb47225fd46cb55070ddfda31a13a49`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @8
- include "src/utils/win/SkHRESULT.h" @11
- function_definition SkTraceHR @13-38

### gfx/skia/skia/src/utils/win/SkHRESULT.h

Blob: `fbf312c771f8fc18c7bab368a4fbf9df88c38c90`. Grammar: cpp. Status: syntax-clean.

- include "include/core/SkTypes.h" @11
- include "src/base/SkLeanWindows.h" @14

### gfx/skia/skia/src/utils/win/SkIStream.cpp

Blob: `93b483bf783563a54c4334f9459f4365582e7474`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @8
- include "include/core/SkStream.h" @11
- include "src/utils/win/SkIStream.h" @12
- function_definition SkBaseIStream @17-17
- function_definition ~SkBaseIStream @18-18
- function_definition QueryInterface @20-35
- function_definition AddRef @37-39
- function_definition Release @41-47
- function_definition Read @50-51
- function_definition Write @53-54
- function_definition SetSize @57-58
- function_definition CopyTo @60-61
- function_definition Commit @63-64
- function_definition Revert @66-67
- function_definition LockRegion @69-70
- function_definition UnlockRegion @72-73
- function_definition Clone @75-76
- function_definition Seek @78-81
- function_definition Stat @83-84
- function_definition SkIStream @90-96
- function_definition ~SkIStream @98-98
- function_definition CreateFromSkStream @100-106
- function_definition Read @109-113
- function_definition Write @115-117
- function_definition Seek @120-172
- function_definition Stat @174-184
- function_definition SkWIStream @190-193
- function_definition ~SkWIStream @195-199
- function_definition CreateFromSkWStream @201-204
- function_definition Write @207-217
- function_definition Commit @220-223
- function_definition Stat @225-235

### gfx/skia/skia/src/utils/win/SkIStream.h

Blob: `37d9b022839bd44f35500f2273fe58369616a7a4`. Grammar: cpp. Status: contains-errors.

- include "include/core/SkTypes.h" @13
- include "src/base/SkLeanWindows.h" @17
- include "src/utils/win/SkObjBase.h" @18
- include <ole2.h> @19
- class_specifier SkStream @21-21
- class_specifier SkWStream @22-22
- class_specifier SkBaseIStream @28-58
- class_specifier SkIStream @63-80
- class_specifier SkWIStream @85-98

### gfx/skia/skia/src/utils/win/SkObjBase.h

Blob: `be314eb22da6056c715eded9d64f7788c6b2de50`. Grammar: cpp. Status: syntax-clean.

- include "src/base/SkLeanWindows.h" @11
- include <objbase.h> @12

### gfx/skia/skia/src/utils/win/SkTScopedComPtr.h

Blob: `f638ca868ed514e9ccd10fa02f5b344df2b48a06`. Grammar: cpp. Status: syntax-clean.

- include "src/base/SkLeanWindows.h" @11
- include "src/utils/win/SkObjBase.h" @12
- function_definition SkRefComPtr @16-19
- function_definition SkSafeRefComPtr @21-26
- class_specifier SkTScopedComPtr @29-83
- function_definition SkTScopedComPtr @34-34
- function_definition SkTScopedComPtr @35-35
- function_definition SkTScopedComPtr @36-36
- function_definition SkTScopedComPtr @37-37
- function_definition SkTScopedComPtr @38-38
- function_definition ~SkTScopedComPtr @40-40
- function_definition (anonymous) @42-45
- function_definition (anonymous) @46-46
- function_definition (anonymous) @47-47
- function_definition (anonymous) @49-49
- function_definition (anonymous) @51-51
- function_definition operator-> @53-53
- function_definition operator& @61-61
- function_definition get @63-63
- function_definition reset @65-70
- function_definition swap @72-76
- function_definition release @78-82

### gfx/src/AAStroke.h

Blob: `31f7658eaa7ab3d65a06c76aa0d08c2b4add9e7d`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- enum_specifier LineCap @12-12
- enum_specifier LineJoin @13-13
- struct_specifier StrokeStyle @14-19
- struct_specifier Stroker @20-20
- struct_specifier OutputVertex @21-25
- struct_specifier VertexBuffer @26-29

### gfx/src/AppUnits.h

Blob: `050720e63b3237268c96e049bd2a35c9b677d1d0`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @8
- function_definition AppUnitsPerCSSPixel @11-11
- function_definition AppUnitsPerCSSInch @12-14

### gfx/src/ArrayView.h

Blob: `3f663dcc9a1d9f119125bf9dc74230f7c4ae15e8`. Grammar: cpp. Status: contains-errors.

- include "nsTArray.h" @8
- class_specifier ArrayView @18-31
- function_definition ArrayView @22-23
- function_definition (anonymous) @24-24
- function_definition Length @25-25
- function_definition Data @26-26

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
