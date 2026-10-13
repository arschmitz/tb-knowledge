<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["mfbt/Algorithm.h", "mfbt/Alignment.h", "mfbt/AllocPolicy.h", "mfbt/AlreadyAddRefed.h", "mfbt/Array.h", "mfbt/ArrayUtils.h", "mfbt/Assertions.cpp", "mfbt/Assertions.h", "mfbt/AtomicBitfields.h", "mfbt/Atomics.h", "mfbt/Attributes.h", "mfbt/BinarySearch.h", "mfbt/BitSet.h", "mfbt/BloomFilter.h", "mfbt/BoundedMPSCQueue.h", "mfbt/Buffer.h", "mfbt/BufferList.h", "mfbt/Casting.h", "mfbt/ChaosMode.cpp", "mfbt/ChaosMode.h", "mfbt/Char16.h", "mfbt/CheckedArithmetic.h", "mfbt/CheckedInt.h", "mfbt/CompactPair.h", "mfbt/Compiler.h", "mfbt/CumulativeAverage.h", "mfbt/DbgMacro.h", "mfbt/DebugOnly.h", "mfbt/DefineEnum.h", "mfbt/DoublyLinkedList.h", "mfbt/EndianUtils.h", "mfbt/EnumSet.h", "mfbt/EnumTypeTraits.h", "mfbt/EnumeratedArray.h", "mfbt/EnumeratedRange.h", "mfbt/FStream.h", "mfbt/FastBernoulliTrial.h", "mfbt/FloatingPoint.cpp", "mfbt/FloatingPoint.h", "mfbt/FunctionRef.h", "mfbt/FunctionTypeTraits.h", "mfbt/Fuzzing.h", "mfbt/HashFunctions.h", "mfbt/HashTable.h", "mfbt/HelperMacros.h", "mfbt/InitializedOnce.h", "mfbt/IntegerRange.h", "mfbt/IntegerTypeTraits.h", "mfbt/JSONWriter.h", "mfbt/JsRust.h", "mfbt/Latin1.h", "mfbt/Likely.h", "mfbt/LinkedList.h", "mfbt/Literals.h", "mfbt/MacroArgs.h", "mfbt/MacroForEach.h", "mfbt/MathAlgorithms.h", "mfbt/Maybe.h", "mfbt/MaybeFmt.h", "mfbt/MaybeOneOf.h", "mfbt/MaybeStorageBase.h", "mfbt/MemoryChecking.h", "mfbt/MemoryReporting.h", "mfbt/MoveOnlyFunction.h", "mfbt/MruCache.h", "mfbt/NeverDestroyed.h", "mfbt/NonDereferenceable.h", "mfbt/NotNull.h", "mfbt/Opaque.h", "mfbt/OperatorNewExtensions.h", "mfbt/PairHash.h", "mfbt/Path.h", "mfbt/PodOperations.h", "mfbt/Poison.cpp", "mfbt/Poison.h", "mfbt/RandomNum.cpp", "mfbt/RandomNum.h", "mfbt/Range.h", "mfbt/RangedArray.h", "mfbt/RangedPtr.h", "mfbt/ReentrancyGuard.h", "mfbt/RefCountType.h", "mfbt/RefCounted.cpp", "mfbt/RefCounted.h", "mfbt/RefPtr.h", "mfbt/Result.h", "mfbt/ResultExtensions.h", "mfbt/ResultVariant.h", "mfbt/ReverseIterator.h", "mfbt/RollingMean.h", "mfbt/SEH.h", "mfbt/SHA1.cpp", "mfbt/SHA1.h", "mfbt/SPSCQueue.h", "mfbt/Saturate.h", "mfbt/ScopeExit.h", "mfbt/SegmentedVector.h", "mfbt/SharedLibrary.h", "mfbt/SmallPointerArray.h", "mfbt/Span.h", "mfbt/SplayTree.h", "mfbt/StaticAnalysisFunctions.h", "mfbt/StringBuffer.h", "mfbt/TaggedAnonymousMemory.cpp", "mfbt/TaggedAnonymousMemory.h", "mfbt/Tainting.h", "mfbt/TextUtils.h", "mfbt/ThreadLocal.h", "mfbt/ThreadSafeWeakPtr.h", "mfbt/ThreadSafety.h", "mfbt/TiedFields.h", "mfbt/ToString.h", "mfbt/Try.h", "mfbt/TypedEnumBits.h", "mfbt/Types.h", "mfbt/UniquePtr.h", "mfbt/UniquePtrExtensions.cpp", "mfbt/UniquePtrExtensions.h", "mfbt/UsingEnum.h", "mfbt/Utf16.h", "mfbt/Utf8.cpp", "mfbt/Utf8.h", "mfbt/Variant.h", "mfbt/Vector.h", "mfbt/WasiAtomic.h", "mfbt/WeakPtr.h", "mfbt/WindowsVersion.h", "mfbt/WrappingOperations.h", "mfbt/XorShift128PlusRNG.h", "mfbt/double-conversion/double-conversion/bignum-dtoa.cc", "mfbt/double-conversion/double-conversion/bignum-dtoa.h", "mfbt/double-conversion/double-conversion/bignum.cc", "mfbt/double-conversion/double-conversion/bignum.h", "mfbt/double-conversion/double-conversion/cached-powers.cc", "mfbt/double-conversion/double-conversion/cached-powers.h", "mfbt/double-conversion/double-conversion/diy-fp.h", "mfbt/double-conversion/double-conversion/double-conversion.h", "mfbt/double-conversion/double-conversion/double-to-string.cc", "mfbt/double-conversion/double-conversion/double-to-string.h", "mfbt/double-conversion/double-conversion/fast-dtoa.cc", "mfbt/double-conversion/double-conversion/fast-dtoa.h", "mfbt/double-conversion/double-conversion/fixed-dtoa.cc", "mfbt/double-conversion/double-conversion/fixed-dtoa.h", "mfbt/double-conversion/double-conversion/ieee.h", "mfbt/double-conversion/double-conversion/string-to-double.cc", "mfbt/double-conversion/double-conversion/string-to-double.h", "mfbt/double-conversion/double-conversion/strtod.cc", "mfbt/double-conversion/double-conversion/strtod.h", "mfbt/double-conversion/double-conversion/utils.h", "mfbt/fallible.h"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/mfbt native and TypeScript syntax map 179

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### mfbt/Algorithm.h

Blob: `b364b11f7fbbd1a37090fd3c5195489c21fe373d`. Grammar: cpp. Status: syntax-clean.

- include <iterator> @10
- include <type_traits> @11
- include "mozilla/Result.h" @13
- struct_specifier TransformTraits @23-28
- function_definition TransformIfAbortOnErr @39-58
- function_definition TransformIfAbortOnErr @62-68
- function_definition TransformAbortOnErr @83-89
- function_definition TransformAbortOnErr @92-98

### mfbt/Alignment.h

Blob: `d88e796af4c1ab6a59e33f779cfcfffc199eb38d`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @10
- include <cstdint> @11
- include "mozilla/Attributes.h" @13
- struct_specifier AlignedElem @22-22
- function_definition AlignedStorage2 @25-43
- struct_specifier MOZ_INHERIT_TYPE_ANNOTATIONS_FROM_TEMPLATE_ARGS @25-25
- function_definition addr @31-31
- function_definition addr @32-32
- function_definition bytes @34-34
- function_definition bytes @35-35
- function_definition AlignedStorage2 @37-37
- function_definition AlignedStorage2 @41-41

### mfbt/AllocPolicy.h

Blob: `5ab6186876a44e598afd907fa8faca5b39b75226`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @13
- include <cstdlib> @14
- include "mozilla/Assertions.h" @16
- include "mozilla/CheckedArithmetic.h" @17
- include "mozilla/Likely.h" @18
- class_specifier MallocAllocPolicy @74-120
- function_definition maybe_pod_malloc @77-82
- function_definition maybe_pod_calloc @85-87
- function_definition maybe_pod_realloc @90-95
- function_definition pod_malloc @98-100
- function_definition pod_calloc @103-105
- function_definition pod_realloc @108-110
- function_definition free_ @113-115
- function_definition reportAllocOverflow @117-117
- function_definition checkSimulatedOOM @119-119
- class_specifier NeverAllocPolicy @129-169
- function_definition maybe_pod_malloc @132-134
- function_definition maybe_pod_calloc @137-139
- function_definition maybe_pod_realloc @142-144
- function_definition pod_malloc @147-149
- function_definition pod_calloc @152-154
- function_definition pod_realloc @157-159
- function_definition free_ @162-164
- function_definition reportAllocOverflow @166-166
- function_definition checkSimulatedOOM @168-168

### mfbt/AlreadyAddRefed.h

Blob: `3e97197bc71ba569cfdff86186d782882cdb0049`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @10
- include "mozilla/Assertions.h" @12
- struct_specifier unused_t @17-17
- function_definition already_AddRefed @46-177
- function_definition already_AddRefed @47-47
- function_definition already_AddRefed @53-53
- function_definition already_AddRefed @57-57
- function_definition (anonymous) @104-108
- function_definition take @140-144
- function_definition leak @152-152
- function_definition downcast @169-173

### mfbt/Array.h

Blob: `c0dc8fcc0543f1570be23f41094c42dc448c53e4`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @10
- include <iterator> @11
- include <ostream> @12
- include <utility> @13
- include "mozilla/Assertions.h" @15
- include "mozilla/Attributes.h" @16
- include "mozilla/Likely.h" @17
- function_definition Array @22-86
- class_specifier MOZ_GSL_OWNER @22-22
- function_definition Array @29-29
- function_definition (anonymous) @39-44
- function_definition (anonymous) @46-51
- function_definition begin @61-61
- function_definition begin @62-62
- function_definition cbegin @63-63
- function_definition end @64-64
- function_definition end @65-65
- function_definition cend @66-66
- function_definition size @69-69
- function_definition data @72-72
- function_definition data @73-73
- function_definition rbegin @76-76
- function_definition rbegin @77-79
- function_definition crbegin @80-80
- function_definition rend @81-81
- function_definition rend @82-84
- function_definition crend @85-85
- class_specifier Array<T, 0> @89-96
- function_definition (anonymous) @91-91
- function_definition (anonymous) @93-95
- function_definition (anonymous) @101-103

### mfbt/ArrayUtils.h

Blob: `eea60fd181ac957db20fd9690c6bb4e9e47bcf16`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @12
- include <stdint.h> @13
- include "mozilla/Assertions.h" @15
- include "mozilla/Attributes.h" @16
- include <algorithm> @19
- include <type_traits> @20
- function_definition PointerRangeSize @37-40
- function_definition ArrayEqual @47-49
- function_definition ArrayEqual @52-54
- struct_specifier AlignedChecker @59-64
- function_definition test @60-63
- struct_specifier AlignedChecker<AlignType, Pointee,
                      std::enable_if_t<std::is_void_v<AlignType>>> @67-70
- function_definition test @69-69
- function_definition IsInRange @88-97
- function_definition IsInRange @105-108

### mfbt/Assertions.cpp

Blob: `a354a460cc8c14b482897f449337c250c9a71627`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Assertions.h" @5
- include <stdarg.h> @7
- include "mozilla/Atomics.h" @9
- include "mozilla/Sprintf.h" @10
- function_definition MOZ_CrashPrintf @29-44
- function_definition detail::InvalidArrayIndex_CRASH @46-52

### mfbt/Assertions.h

Blob: `b26a32f2e36cbdbb8fdf5d63426aea34484b69f4`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @12
- include <process.h> @26
- include <unistd.h> @29
- include "mozilla/Attributes.h" @36
- include "mozilla/Fuzzing.h" @37
- include "mozilla/Likely.h" @38
- include "mozilla/MacroArgs.h" @39
- include "mozilla/StaticAnalysisFunctions.h" @40
- include "mozilla/Types.h" @41
- include "mozilla/StackWalk.h" @43
- function_definition AnnotateMozCrashReason @57-66
- include <stddef.h> @74
- include <stdio.h> @75
- include <stdlib.h> @76
- include <android/log.h> @91
- function_definition MOZ_ReportAssertionFailurePrintFrame @97-100
- function_definition MOZ_CrashPrintFrame @101-103
- function_definition MOZ_StripRelativeComponents @115-128
- function_definition MOZ_PRETEND_NORETURN_FOR_STATIC_ANALYSIS @139-167
- function_definition MOZ_PRETEND_NORETURN_FOR_STATIC_ANALYSIS @169-196
- function_definition MOZ_NoReturn @234-239
- function_definition MOZ_CrashSequence @259-291
- function_definition MOZ_Crash @390-403
- include <type_traits> @489
- struct_specifier AssertionConditionType @494-510
- function_definition MakeCompilerAssumeUnreachableFakeValue @806-808

### mfbt/AtomicBitfields.h

Blob: `de7dce8d09d76ac8a9e8796d3b90ef3c31c447cb`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @8
- include <type_traits> @9
- include "mozilla/Assertions.h" @11
- include "mozilla/MacroArgs.h" @12
- include "mozilla/MacroForEach.h" @13
- include "mozilla/WasiAtomic.h" @16
- include <atomic> @18

### mfbt/Atomics.h

Blob: `68371049351c192c811fbd19e8f2d0aa6261653f`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @17
- include "mozilla/WasiAtomic.h" @20
- include <atomic> @22
- include <cstddef> @25
- include <cstdint> @26
- include <type_traits> @27
- include <emmintrin.h> @31
- include <sanitizer/tsan_interface.h> @35
- enum_specifier MemoryOrdering @70-152
- struct_specifier AtomicOrderConstraints @161-161
- struct_specifier AtomicOrderConstraints<Relaxed> @164-170
- struct_specifier AtomicOrderConstraints<ReleaseAcquire> @173-179
- struct_specifier AtomicOrderConstraints<SequentiallyConsistent> @182-188
- struct_specifier IntrinsicBase @191-194
- struct_specifier IntrinsicMemoryOps @197-218
- function_definition load @200-202
- function_definition store @204-206
- function_definition exchange @208-210
- function_definition compareExchange @212-217
- struct_specifier IntrinsicAddSub @221-231
- function_definition add @224-226
- function_definition sub @228-230
- struct_specifier IntrinsicAddSub<T*, Order> @234-244
- function_definition add @237-239
- function_definition sub @241-243
- struct_specifier IntrinsicIncDec @247-257
- function_definition inc @250-252
- function_definition dec @254-256
- struct_specifier MOZ_EMPTY_BASES @260-260
- function_definition or_ @264-266
- function_definition xor_ @268-270
- function_definition and_ @272-274
- struct_specifier MOZ_EMPTY_BASES @278-278
- struct_specifier ToStorageTypeArgument @283-285
- function_definition convert @284-284
- class_specifier AtomicBase @288-334
- function_definition AtomicBase @298-298
- function_definition AtomicBase @299-300
- function_definition operator= @307-310
- function_definition AtomicBase @312-312
- function_definition exchange @318-318
- function_definition compareExchange @331-333
- class_specifier AtomicBaseIncDec @337-353
- function_definition AtomicBaseIncDec @341-341
- function_definition AtomicBaseIncDec @342-342
- function_definition AtomicBaseIncDec @346-346
- function_definition (anonymous) @348-348
- function_definition operator++ @349-349
- function_definition operator-- @350-350
- function_definition operator++ @351-351
- function_definition operator-- @352-352
- class_specifier Atomic @376-376
- class_specifier Atomic<
    T, Order,
    std::enable_if_t<std::is_integral_v<T> && !std::is_same_v<T, bool>>> @387-420
- function_definition Atomic @394-394
- function_definition Atomic @395-395
- function_definition Atomic @399-399
- function_definition operator+= @401-403
- function_definition operator-= @405-407
- function_definition operator|= @409-411
- function_definition operator^= @413-415
- function_definition operator&= @417-419
- class_specifier Atomic<T*, Order> @431-449
- function_definition Atomic @435-435
- function_definition Atomic @436-436
- function_definition Atomic @440-440
- function_definition operator+= @442-444
- function_definition operator-= @446-448
- class_specifier Atomic<T, Order, std::enable_if_t<std::is_enum_v<T>>> @457-470
- function_definition Atomic @462-462
- function_definition Atomic @463-463
- function_definition (anonymous) @465-465
- function_definition Atomic @469-469
- class_specifier Atomic<bool, Order> @489-510
- function_definition Atomic @493-493
- function_definition Atomic @494-494
- function_definition Atomic @496-496
- function_definition bool @499-501
- function_definition operator= @503-503
- function_definition exchange @505-505
- function_definition compareExchange @507-509
- class_specifier Atomic<double, Order> @516-530
- function_definition Atomic @520-520
- function_definition Atomic @521-521
- function_definition Atomic @523-523
- function_definition (anonymous) @525-527
- function_definition operator= @529-529
- function_definition cpu_pause @535-546
- function_definition AtomicRefCountDecrement @561-577

### mfbt/Attributes.h

Blob: `7665dc6b547395dcaa0e877ff672cf1105bc146c`. Grammar: cpp. Status: contains-errors.

- include <version> @11

### mfbt/BinarySearch.h

Blob: `870be6e6af7c4a695406d53a8eed141a7995925d`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @8
- include <type_traits> @9
- include <utility> @10
- include "mozilla/Assertions.h" @12
- function_definition BinarySearchIf @68-98
- class_specifier BinarySearchDefaultComparator @103-122
- function_definition BinarySearchDefaultComparator @105-105
- function_definition operator() @108-118
- function_definition BinarySearch @127-132
- function_definition LowerBound @169-194
- function_definition UpperBound @197-222
- function_definition EqualRange @225-251

### mfbt/BitSet.h

Blob: `4904b80aa2a6e4ffb2bd30c78ae63fbea430bc69`. Grammar: cpp. Status: contains-errors.

- include <bit> @8
- include <cstddef> @9
- include <cstdint> @10
- include <type_traits> @11
- include "fmt/format.h" @13
- include "mozilla/Array.h" @14
- include "mozilla/MathAlgorithms.h" @15
- include "mozilla/Span.h" @16
- enum_specifier MemoryOrdering @20-20
- class_specifier Atomic @22-22
- struct_specifier UnwrapMaybeAtomic @27-29
- struct_specifier UnwrapMaybeAtomic<mozilla::Atomic<T, Order, Enable>> @31-33
- class_specifier BitSet @49-258
- function_definition ResetPaddingBits @67-71
- class_specifier Reference @74-95
- function_definition Reference @76-77
- function_definition (anonymous) @79-88
- function_definition bool @90-90
- function_definition BitSet @97-97
- function_definition BitSet @99-99
- function_definition (anonymous) @101-106
- function_definition BitSet @108-112
- function_definition size @114-114
- function_definition test @116-119
- function_definition IsEmpty @121-128
- function_definition (anonymous) @130-130
- function_definition operator[] @132-132
- function_definition operator[] @134-137
- function_definition operator| @139-143
- function_definition (anonymous) @145-150
- function_definition operator~ @152-156
- function_definition (anonymous) @158-163
- function_definition operator& @165-169
- function_definition operator== @171-171
- function_definition Count @173-181
- function_definition ResetAll @184-188
- function_definition SetAll @191-196
- function_definition Flip @198-204
- function_definition FindFirst @207-207
- function_definition FindNext @211-229
- function_definition FindLast @231-231
- function_definition FindPrev @235-253
- function_definition Storage @255-255
- function_definition Storage @257-257
- struct_specifier fmt::formatter<mozilla::BitSet<N, StorageType>> @263-337
- function_definition parse @266-268
- function_definition format @274-336

### mfbt/BloomFilter.h

Blob: `686cf03f199227a4d8d3d7d7d0cebf3d54272c28`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @15
- include <cstring> @16
- include "mozilla/Attributes.h" @18
- include "mozilla/Likely.h" @19
- class_specifier BitBloomFilter @52-170
- function_definition BitBloomFilter @102-109
- function_definition hash1 @141-141
- function_definition hash2 @142-147
- function_definition getSlot @149-154
- function_definition setSlot @156-161
- function_definition getFirstSlot @163-163
- function_definition getSecondSlot @164-164
- function_definition setFirstSlot @166-166
- function_definition setSecondSlot @167-167
- function_definition clear @173-175
- function_definition add @178-181
- function_definition add @184-187
- function_definition mightContain @190-194
- function_definition mightContain @197-201
- class_specifier CountingBloomFilter @216-279
- function_definition CountingBloomFilter @218-222
- function_definition hash1 @261-261
- function_definition hash2 @262-264
- function_definition (anonymous) @266-266
- function_definition (anonymous) @267-267
- function_definition (anonymous) @269-271
- function_definition (anonymous) @272-274
- function_definition full @276-276
- function_definition clear @282-284
- function_definition add @287-296
- function_definition add @299-302
- function_definition remove @305-316
- function_definition remove @319-323
- function_definition mightContain @326-330
- function_definition mightContain @333-337

### mfbt/BoundedMPSCQueue.h

Blob: `bea700cad1a6fe2bdb6b7d5699857208f48eec8d`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @18
- include <atomic> @19
- include <cinttypes> @20
- include <cstddef> @21
- include <cstdint> @22
- include <memory> @23
- include <optional> @24
- include "mozilla/Assertions.h" @26
- class_specifier MPSCRingBufferBase @51-328
- function_definition MPSCRingBufferBase @55-77
- function_definition Send @92-100
- function_definition Recv @115-125
- function_definition Capacity @127-127
- function_definition Get @170-172
- function_definition Set @174-178
- function_definition MarkSlot @199-248
- function_definition UnmarkSlot @263-297
- function_definition StorageCapacity @302-304

### mfbt/Buffer.h

Blob: `35fa127a132d02537194821c372ead44723c5f0e`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @8
- include <iterator> @9
- include <utility> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/Maybe.h" @13
- include "mozilla/Span.h" @14
- include "mozilla/UniquePtr.h" @15
- include "mozilla/UniquePtrExtensions.h" @16
- class_specifier Buffer @30-194
- function_definition Buffer @36-36
- function_definition (anonymous) @37-37
- function_definition Buffer @43-43
- function_definition Buffer @51-52
- function_definition Buffer @58-61
- function_definition (anonymous) @67-72
- function_definition Buffer @80-84
- function_definition CopyFrom @91-102
- function_definition Buffer @113-114
- function_definition Alloc @124-130
- function_definition AllocForOverwrite @140-146
- function_definition AsSpan @148-148
- function_definition AsWritableSpan @149-149
- function_definition (anonymous) @150-150
- function_definition (anonymous) @151-151
- function_definition Elements @157-157
- function_definition Length @158-158
- function_definition (anonymous) @160-163
- function_definition (anonymous) @165-168
- function_definition begin @176-176
- function_definition begin @177-177
- function_definition cbegin @178-178
- function_definition end @179-179
- function_definition end @180-180
- function_definition cend @181-181
- function_definition rbegin @184-184
- function_definition rbegin @185-187
- function_definition crbegin @188-188
- function_definition rend @189-189
- function_definition rend @190-192
- function_definition crend @193-193

### mfbt/BufferList.h

Blob: `eb0b37043d49d3a6960166c3b9170a874d0bb3f1`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @8
- include <cstdint> @9
- include <cstring> @10
- include <utility> @11
- include "mozilla/Assertions.h" @13
- include "mozilla/MemoryReporting.h" @14
- include "mozilla/Vector.h" @15
- include <type_traits> @17
- class_specifier InfallibleAllocPolicy @26-26
- class_specifier BufferList @31-437
- struct_specifier Segment @34-50
- function_definition Segment @39-40
- function_definition Segment @42-42
- function_definition (anonymous) @43-43
- function_definition Segment @45-45
- function_definition (anonymous) @46-46
- function_definition Start @48-48
- function_definition End @49-49
- function_definition BufferList @70-88
- function_definition BufferList @90-90
- function_definition BufferList @92-99
- function_definition (anonymous) @101-101
- function_definition (anonymous) @103-112
- function_definition ~BufferList @114-114
- function_definition Init @118-124
- function_definition CopyFrom @126-146
- function_definition Size @149-149
- function_definition SizeOfExcludingThis @151-157
- function_definition isStorageConsistent @160-160
- function_definition Clear @163-174
- class_specifier IterImpl @178-321
- function_definition IterImpl @191-196
- function_definition Data @200-203
- function_definition operator== @205-207
- function_definition operator!= @208-208
- function_definition HasRoomFor @212-214
- function_definition RemainingInSegment @218-221
- function_definition HasBytesAvailable @225-227
- function_definition TotalBytesAvailable @231-233
- function_definition Advance @239-256
- function_definition AdvanceAcrossSegments @261-307
- function_definition Done @310-310
- function_definition AbsoluteOffset @313-313
- function_definition IsIn @316-320
- function_definition Start @324-327
- function_definition Start @328-328
- function_definition Iter @330-330
- function_definition RangeLength @369-372
- function_definition WriteBytesZeroCopy @375-393
- function_definition BufferList @403-404
- function_definition AllocateSegment @406-421
- function_definition AssertConsistentSize @423-431
- function_definition WriteBytes @440-457
- function_definition AllocateBytes @460-487
- function_definition ReadBytes @490-508
- function_definition Borrow @512-534
- function_definition MoveFallible @538-561
- function_definition Truncate @564-607

### mfbt/Casting.h

Blob: `53f7ab18cd300deb661f2a1614afedf32c2c9b44`. Grammar: cpp. Status: contains-errors.

- include <cmath> @10
- include <cstdint> @11
- include <limits> @12
- include <type_traits> @13
- include "mozilla/Assertions.h" @15
- include <cstring> @18
- include <cstdio> @22
- include "fmt/format.h" @24
- function_definition BitwiseCast @51-72
- function_definition BitwiseCast @75-79
- function_definition safe_integer @84-87
- function_definition safe_integer_unsigned @90-93
- function_definition TypeToString @99-101
- function_definition DiagnosticMessage @137-156
- function_definition IsInBounds @160-220
- function_definition AssertedCast @232-243
- function_definition ReleaseAssertedCast @253-257
- function_definition SaturatingCast @264-311
- class_specifier LazyAssertedCastT @316-326
- function_definition LazyAssertedCastT @320-320
- function_definition (anonymous) @323-325
- function_definition LazyAssertedCast @335-337

### mfbt/ChaosMode.cpp

Blob: `39d574d19c315cba40c0590164d61ec83a6e9044`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/ChaosMode.h" @5

### mfbt/ChaosMode.h

Blob: `3385e570aed68256ee95304250ec15b0fce1663c`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @8
- include "mozilla/Assertions.h" @10
- include "mozilla/Atomics.h" @11
- enum_specifier ChaosFeature @15-34
- class_specifier ChaosMode @46-89
- function_definition SetChaosFeature @48-50
- function_definition isActive @52-55
- function_definition enterChaosMode @62-62
- function_definition leaveChaosMode @67-70
- function_definition randomUint32LessThan @76-79
- function_definition randomInt32InRange @85-88

### mfbt/Char16.h

Blob: `92ed110891efe8627ac9b32a8051cb78d38bbef1`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @20
- include <cstdint> @21
- include "mozilla/Attributes.h" @23
- class_specifier char16ptr_t @35-117
- function_definition char16ptr_t @42-42
- function_definition char16ptr_t @43-44
- function_definition char16ptr_t @47-47
- function_definition (anonymous) @49-49
- function_definition (anonymous) @50-52
- function_definition (anonymous) @54-56
- function_definition (anonymous) @58-58
- function_definition (anonymous) @59-59
- function_definition (anonymous) @61-61
- function_definition (anonymous) @62-64
- function_definition (anonymous) @65-65
- function_definition (anonymous) @66-68
- function_definition (anonymous) @69-71
- function_definition (anonymous) @72-74
- function_definition (anonymous) @81-83
- function_definition (anonymous) @84-86
- function_definition (anonymous) @87-90
- function_definition (anonymous) @91-91
- function_definition operator[] @94-94
- function_definition operator== @95-95
- function_definition operator== @96-96
- function_definition operator!= @97-97
- function_definition operator+ @98-98
- function_definition operator+ @99-101
- function_definition operator+ @102-104
- function_definition operator+ @105-107
- function_definition operator+ @108-110
- function_definition operator+ @111-113
- function_definition operator- @114-116
- function_definition operator- @119-121

### mfbt/CheckedArithmetic.h

Blob: `04fa8bac41b785fe3fd6ee202086499bc8df52d1`. Grammar: cpp. Status: syntax-clean.

- function_definition SafeAdd @13-15
- function_definition SafeSub @18-20
- function_definition SafeMul @23-25

### mfbt/CheckedInt.h

Blob: `aab11b327402e70f84af56471d6e9119c501dd05`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @10
- include <limits> @11
- include <type_traits> @12
- include <utility> @13
- include "mozilla/Assertions.h" @15
- include "mozilla/Attributes.h" @16
- include "mozilla/CheckedArithmetic.h" @17
- class_specifier CheckedInt @22-22
- struct_specifier IsSupportedPass2 @38-40
- struct_specifier IsSupported @43-45
- struct_specifier IsSupported<int8_t> @48-50
- struct_specifier IsSupported<uint8_t> @53-55
- struct_specifier IsSupported<int16_t> @58-60
- struct_specifier IsSupported<uint16_t> @63-65
- struct_specifier IsSupported<int32_t> @68-70
- struct_specifier IsSupported<uint32_t> @73-75
- struct_specifier IsSupported<int64_t> @78-80
- struct_specifier IsSupported<uint64_t> @83-85
- struct_specifier IsSupportedPass2<signed char> @88-90
- struct_specifier IsSupportedPass2<unsigned char> @93-95
- struct_specifier IsSupportedPass2<short> @98-100
- struct_specifier IsSupportedPass2<unsigned short> @103-105
- struct_specifier IsSupportedPass2<int> @108-110
- struct_specifier IsSupportedPass2<unsigned int> @113-115
- struct_specifier IsSupportedPass2<long> @118-120
- struct_specifier IsSupportedPass2<unsigned long> @123-125
- struct_specifier IsSupportedPass2<long long> @128-130
- struct_specifier IsSupportedPass2<unsigned long long> @133-135
- function_definition IsDivValid @144-149
- function_definition IsModValid @152-155
- struct_specifier NegateImpl @158-158
- struct_specifier NegateImpl<T, false> @161-168
- function_definition negate @162-167
- struct_specifier NegateImpl<T, true> @171-183
- function_definition negate @172-182
- function_definition CheckedInt @259-299
- class_specifier CheckedInt @259-295
- function_definition CheckedInt @265-271
- function_definition CheckedInt @302-303
- function_definition toChecked @309-313
- function_definition CheckedInt @316-320
- function_definition value @323-328
- function_definition isValid @335-335
- function_definition operator- @372-374
- function_definition operator== @394-396
- function_definition (anonymous) @399-402
- function_definition operator++ @405-409
- function_definition (anonymous) @412-415
- function_definition operator-- @418-422
- function_definition (anonymous) @515-519
- function_definition OP @521-523
- function_definition OP @525-527

### mfbt/CompactPair.h

Blob: `36118f7e5ba04c479ccd8facde2cc65962256b07`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @10
- include <tuple> @11
- include <type_traits> @12
- include <utility> @13
- include "mozilla/Attributes.h" @15
- class_specifier CompactPair @28-66
- function_definition CompactPair @33-35
- function_definition CompactPair @39-42
- function_definition CompactPair @45-46
- function_definition CompactPair @47-47
- function_definition CompactPair @48-48
- function_definition (anonymous) @50-50
- function_definition (anonymous) @51-51
- function_definition operator== @53-53
- function_definition (anonymous) @55-55
- function_definition (anonymous) @56-56
- function_definition (anonymous) @57-57
- function_definition (anonymous) @58-58
- function_definition swap @61-65
- function_definition MakeCompactPair @77-81
- function_definition swap @88-90

### mfbt/Compiler.h

Blob: `0a8bb76c015d6416ae6930405a624ecc7bea844c`. Grammar: cpp. Status: syntax-clean.


### mfbt/CumulativeAverage.h

Blob: `ffbb484382dab6fbfacb94b7db80db3ef5d31bab`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @10
- include <limits> @12
- include <type_traits> @13
- include "mozilla/Assertions.h" @15
- class_specifier CumulativeAverage @26-66
- function_definition insert @35-47
- function_definition mean @49-52
- function_definition empty @54-54
- function_definition count @56-56
- function_definition reset @58-61

### mfbt/DbgMacro.h

Blob: `cd8a807da4cf9c6f21e0df8ca0fe29fe13fd9563`. Grammar: cpp. Status: syntax-clean.

- include <fmt/format.h> @10
- include <cstdio> @12
- include <sstream> @13
- include "mozilla/MacroForEach.h" @15
- include "mozilla/Span.h" @16
- class_specifier nsTSubstring @19-19
- include <android/log.h> @22
- struct_specifier supports_os @31-31
- struct_specifier supports_os<T, std::void_t<decltype(std::declval<std::ostream&>()
                                           << std::declval<T&>())>> @34-36
- function_definition (anonymous) @47-58
- function_definition (anonymous) @64-71
- function_definition (anonymous) @77-88
- function_definition (anonymous) @95-105
- function_definition (anonymous) @111-113

### mfbt/DebugOnly.h

Blob: `2d17aae17c79c3e134fd696cc154aaa47a798c1a`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @13
- include <utility> @16
- function_definition DebugOnly @41-98
- class_specifier MOZ_STACK_CLASS @41-41
- function_definition DebugOnly @46-46
- function_definition value @47-47
- function_definition value @48-48
- function_definition DebugOnly @49-49
- function_definition DEBUG @50-53
- function_definition DEBUG @54-57
- function_definition operator++ @59-59
- function_definition operator-- @60-60
- function_definition operator& @66-66
- function_definition DEBUG @68-68
- function_definition DEBUG @69-69
- function_definition DEBUG @71-71
- function_definition DEBUG @72-72
- function_definition DEBUG @74-74
- function_definition DebugOnly @77-77
- function_definition DebugOnly @78-78
- function_definition DebugOnly @79-79
- function_definition (anonymous) @80-80
- function_definition DebugOnly @81-81
- function_definition (anonymous) @82-82
- function_definition operator++ @83-83
- function_definition operator-- @84-84
- function_definition (anonymous) @85-85
- function_definition (anonymous) @86-86
- function_definition (anonymous) @87-87
- function_definition (anonymous) @88-88
- function_definition (anonymous) @89-89
- function_definition ~DebugOnly @97-97

### mfbt/DefineEnum.h

Blob: `331fbcdf9046286907c740855e547fc90da1a35e`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @10
- include <ostream> @12
- include "mozilla/MacroArgs.h" @14
- include "mozilla/MacroForEach.h" @15

### mfbt/DoublyLinkedList.h

Blob: `fee0b387e5629ed14e74ab5b921e9ad0d0305662`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @10
- include <iterator> @11
- include <type_traits> @12
- include "mozilla/Assertions.h" @14
- class_specifier DoublyLinkedListElement @71-80
- function_definition DoublyLinkedListElement @79-79
- struct_specifier GetDoublyLinkedListElement @94-102
- function_definition (anonymous) @98-100
- function_definition (anonymous) @101-101
- class_specifier DoublyLinkedList @111-434
- function_definition isStateValid @119-119
- function_definition ElementNotInList @121-130
- function_definition DoublyLinkedList @133-133
- class_specifier Iterator @135-176
- function_definition Iterator @145-145
- function_definition Iterator @146-146
- function_definition (anonymous) @148-148
- function_definition operator-> @149-149
- function_definition (anonymous) @151-154
- function_definition operator++ @156-160
- function_definition (anonymous) @162-165
- function_definition operator-- @167-171
- function_definition operator== @173-173
- function_definition (anonymous) @175-175
- function_definition begin @178-178
- function_definition begin @179-179
- function_definition cbegin @180-180
- function_definition end @182-182
- function_definition end @183-183
- function_definition cend @184-184
- function_definition isEmpty @189-192
- function_definition isSingle @194-197
- function_definition pushFront @203-218
- function_definition popFront @224-244
- function_definition pushBack @250-266
- function_definition popBack @272-292
- function_definition insertBefore @297-316
- function_definition remove @321-344
- function_definition find @350-350
- function_definition find @356-359
- function_definition contains @365-365
- function_definition contains @371-371
- function_definition ElementProbablyInList @379-384
- function_definition ElementIsLinkedWell @390-416
- function_definition ListIsWellFormed @421-433
- class_specifier SafeDoublyLinkedList @446-637
- class_specifier SafeIterator @462-548
- function_definition SafeIterator @475-475
- function_definition SafeIterator @476-477
- function_definition SafeIterator @479-488
- function_definition ~SafeIterator @489-497
- function_definition (anonymous) @499-505
- function_definition operator-> @507-507
- function_definition operator-> @508-508
- function_definition operator* @509-509
- function_definition operator* @510-510
- function_definition current @512-512
- function_definition current @513-513
- function_definition (anonymous) @515-515
- function_definition operator== @516-518
- function_definition operator!= @519-521
- function_definition (anonymous) @523-523
- function_definition setNext @546-546
- function_definition setCurrent @547-547
- function_definition SafeDoublyLinkedList @555-555
- function_definition isEmpty @557-557
- function_definition contains @558-565
- function_definition begin @567-567
- function_definition begin @568-568
- function_definition cbegin @569-569
- function_definition end @571-571
- function_definition end @572-572
- function_definition cend @573-573
- function_definition pushFront @575-575
- function_definition pushBack @577-586
- function_definition popFront @588-599
- function_definition popBack @601-614
- function_definition remove @616-632

### mfbt/EndianUtils.h

Blob: `c9ec3830b37ca480c81d8f0db9bda3a602983522`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @67
- include <string.h> @68
- include <bit> @70
- include "mozilla/Assertions.h" @72
- include "mozilla/DebugOnly.h" @73
- function_definition byteswap @80-88
- class_specifier EndianUtils @92-184
- function_definition assertNoOverlap @97-104
- function_definition assertAligned @107-109
- function_definition maybeSwap @117-122
- function_definition maybeSwapInPlace @129-138
- function_definition copyAndSwapTo @145-160
- function_definition copyAndSwapFrom @167-183
- class_specifier Endian @187-442
- function_definition Endian @189-189
- function_definition Endian @190-190
- function_definition operator= @191-191
- function_definition readUint16 @195-197
- function_definition readUint32 @200-202
- function_definition readUint64 @205-207
- function_definition readUintptr @210-212
- function_definition readInt16 @215-217
- function_definition readInt32 @220-222
- function_definition readInt64 @225-227
- function_definition readIntptr @230-232
- function_definition writeUint16 @235-235
- function_definition writeUint32 @238-238
- function_definition writeUint64 @241-241
- function_definition writeUintptr @244-246
- function_definition writeInt16 @249-249
- function_definition writeInt32 @252-252
- function_definition writeInt64 @255-255
- function_definition writeIntptr @258-258
- function_definition swapToLittleEndian @268-270
- function_definition copyAndSwapToLittleEndian @280-283
- function_definition swapToLittleEndianInPlace @289-291
- function_definition swapToBigEndian @297-299
- function_definition copyAndSwapToBigEndian @309-312
- function_definition swapToBigEndianInPlace @318-320
- function_definition swapToNetworkOrder @328-330
- function_definition copyAndSwapToNetworkOrder @333-336
- function_definition swapToNetworkOrderInPlace @339-341
- function_definition swapFromLittleEndian @347-349
- function_definition copyAndSwapFromLittleEndian @359-362
- function_definition swapFromLittleEndianInPlace @368-370
- function_definition swapFromBigEndian @376-378
- function_definition copyAndSwapFromBigEndian @388-391
- function_definition swapFromBigEndianInPlace @397-399
- function_definition swapFromNetworkOrder @406-408
- function_definition copyAndSwapFromNetworkOrder @411-414
- function_definition swapFromNetworkOrderInPlace @417-419
- function_definition read @427-431
- function_definition write @438-441
- class_specifier EndianReadWrite @445-466
- class_specifier LittleEndian @470-471
- class_specifier BigEndian @473-473
- class_specifier NativeEndian @477-511

### mfbt/EnumSet.h

Blob: `80157c56b5098ddcca619058e4a6939ad48a5a07`. Grammar: cpp. Status: contains-errors.

- include <bit> @10
- include <initializer_list> @11
- include <type_traits> @12
- include "mozilla/Assertions.h" @14
- include "mozilla/Attributes.h" @15
- include <cstdint> @17
- class_specifier EnumSet @29-347
- function_definition EnumSet @34-34
- function_definition EnumSet @36-36
- function_definition EnumSet @38-39
- function_definition EnumSet @41-42
- function_definition EnumSet @44-46
- function_definition EnumSet @48-52
- function_definition EnumSet @54-54
- function_definition EnumSet @57-57
- function_definition DEBUG @59-63
- function_definition operator+= @69-72
- function_definition operator+ @77-81
- function_definition operator+= @86-89
- function_definition operator+ @94-98
- function_definition operator-= @103-106
- function_definition operator- @111-115
- function_definition operator-= @120-123
- function_definition operator- @128-132
- function_definition clear @137-140
- function_definition operator&= @145-148
- function_definition operator& @153-157
- function_definition operator== @163-165
- function_definition operator== @167-167
- function_definition operator== @173-175
- function_definition operator!= @180-180
- function_definition contains @185-185
- function_definition contains @190-192
- function_definition size @197-203
- function_definition isEmpty @205-211
- function_definition serialize @213-213
- function_definition deserialize @215-218
- class_specifier ConstIterator @220-289
- function_definition checkVersion @227-230
- function_definition ConstIterator @233-241
- function_definition ConstIterator @243-249
- function_definition ConstIterator @251-258
- function_definition ~ConstIterator @260-260
- function_definition operator== @262-266
- function_definition operator!= @268-270
- function_definition operator* @272-278
- function_definition (anonymous) @280-288
- function_definition begin @291-291
- function_definition end @293-293
- function_definition BitFor @296-299
- function_definition BitAt @301-310
- function_definition HasBitFor @312-315
- function_definition HasBitAt @317-324
- function_definition IncVersion @326-330
- function_definition MaxBits @332-338

### mfbt/EnumTypeTraits.h

Blob: `3bf22185767d62660518cbcbc421fadfdba8f03a`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @10
- include <type_traits> @11
- struct_specifier EnumFitsWithinHelper @19-19
- struct_specifier EnumFitsWithinHelper<EnumSize, true, StorageSize, true> @23-24
- struct_specifier EnumFitsWithinHelper<EnumSize, true, StorageSize, false> @28-29
- struct_specifier EnumFitsWithinHelper<EnumSize, false, StorageSize, true> @33-34
- struct_specifier EnumFitsWithinHelper<EnumSize, false, StorageSize, false> @38-39
- struct_specifier EnumTypeFitsWithin @53-59
- function_definition UnderlyingValue @81-84
- struct_specifier MinContiguousEnumValue @116-116
- struct_specifier MaxContiguousEnumValue @119-119
- struct_specifier MaxEnumValue @122-122
- struct_specifier ContiguousEnumValues @127-130
- struct_specifier ContiguousEnumSize @135-139

### mfbt/EnumeratedArray.h

Blob: `8060b81b46bddee92b07885ca4f1a2f545cfb356`. Grammar: cpp. Status: contains-errors.

- include <utility> @10
- include "EnumTypeTraits.h" @12
- include "mozilla/Array.h" @13
- class_specifier EnumeratedArray @46-93
- function_definition EnumeratedArray @56-56
- function_definition (anonymous) @62-64
- function_definition (anonymous) @66-68
- function_definition begin @76-76
- function_definition begin @77-77
- function_definition cbegin @78-78
- function_definition end @79-79
- function_definition end @80-80
- function_definition cend @81-81
- function_definition size @84-84
- function_definition rbegin @87-87
- function_definition rbegin @88-88
- function_definition crbegin @89-89
- function_definition rend @90-90
- function_definition rend @91-91
- function_definition crend @92-92

### mfbt/EnumeratedRange.h

Blob: `080921a8387a54046d2f03d66aee94949a50b3e1`. Grammar: cpp. Status: syntax-clean.

- include <type_traits> @21
- include "mozilla/Assertions.h" @23
- include "mozilla/ReverseIterator.h" @24
- include <limits> @27
- class_specifier EnumeratedIterator @35-80
- function_definition EnumeratedIterator @40-41
- function_definition EnumeratedIterator @44-45
- function_definition operator* @47-47
- function_definition (anonymous) @51-54
- function_definition (anonymous) @55-58
- function_definition operator++ @59-63
- function_definition operator-- @64-68
- function_definition operator== @72-72
- function_definition operator< @73-73
- function_definition operator<= @74-74
- function_definition operator> @75-75
- function_definition operator>= @76-76
- class_specifier EnumeratedRange @83-106
- function_definition EnumeratedRange @91-92
- function_definition begin @94-94
- function_definition cbegin @95-95
- function_definition end @96-96
- function_definition cend @97-97
- function_definition rbegin @98-98
- function_definition crbegin @99-99
- function_definition rend @100-100
- function_definition crend @101-101
- function_definition MakeEnumeratedRange @120-124
- function_definition MakeEnumeratedRange @129-131
- function_definition MakeInclusiveEnumeratedRange @142-150
- function_definition MakeInclusiveEnumeratedRange @153-155

### mfbt/FStream.h

Blob: `714fcb77065fea410b76acac4aaedb9035f5b1ce`. Grammar: cpp. Status: syntax-clean.

- include <fcntl.h> @16
- include <ext/stdio_filebuf.h> @18
- include <istream> @19
- include <ostream> @20
- include "mozilla/UniquePtr.h" @22
- include "mozilla/Char16.h" @25
- include <fstream> @27
- class_specifier IFStream @35-47
- function_definition rdbuf @39-39
- function_definition is_open @41-41
- function_definition close @43-43
- function_definition IFStream @49-52
- function_definition open @54-64
- class_specifier OFStream @66-78
- function_definition rdbuf @70-70
- function_definition is_open @72-72
- function_definition close @74-74
- function_definition OFStream @80-83
- function_definition open @85-98
- class_specifier IFStream @101-109
- function_definition IFStream @103-104
- function_definition open @106-108
- class_specifier OFStream @111-119
- function_definition OFStream @113-114
- function_definition open @116-118

### mfbt/FastBernoulliTrial.h

Blob: `944fe2c681935826e2cf984712dce73e30c4e599`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @8
- include <cmath> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/XorShift128PlusRNG.h" @13
- class_specifier FastBernoulliTrial @88-376
- function_definition FastBernoulliTrial @178-184
- function_definition trial @191-198
- function_definition trial @216-223
- function_definition setRandomState @225-227
- function_definition setProbability @229-288
- function_definition chooseSkipCount @316-375

### mfbt/FloatingPoint.cpp

Blob: `cf7f64d32c912ad2fdde445ad1bc7cafefd84052`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/FloatingPoint.h" @7
- include <cfloat> @9
- include <cmath> @10
- function_definition IsFloat32Representable @14-38

### mfbt/FloatingPoint.h

Blob: `dc0ddd69737c59262bd2a4307638076e557cc80a`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @10
- include <bit> @11
- include <cstdint> @12
- include <limits> @13
- include <type_traits> @14
- include "mozilla/Assertions.h" @16
- include "mozilla/Attributes.h" @17
- include "mozilla/Casting.h" @18
- include "mozilla/MathAlgorithms.h" @19
- include "mozilla/MemoryChecking.h" @20
- include "mozilla/Types.h" @21
- struct_specifier FloatingPointTrait @47-47
- struct_specifier FloatingPointTrait<float> @50-56
- struct_specifier FloatingPointTrait<double> @59-65
- struct_specifier FloatingPoint @94-151
- function_definition IsNegative @158-161
- function_definition IsNegativeZero @165-171
- function_definition IsPositiveZero @175-181
- function_definition ToZeroIfNonfinite @188-190
- function_definition ExponentComponent @199-210
- function_definition PositiveInfinity @214-216
- function_definition NegativeInfinity @220-222
- struct_specifier InfinityBits @228-234
- struct_specifier SpecificNaNBits @241-252
- struct_specifier SpecificFloatingPointBits @259-271
- function_definition SpecificNaN @290-301
- function_definition SpecificNaN @304-309
- function_definition MinNumberValue @313-315
- function_definition MaxNumberValue @319-321
- function_definition NumberEqualsSignedInteger @326-394
- function_definition NumberIsSignedInteger @397-414
- function_definition NumberIsInt32 @427-429
- function_definition NumberIsInt64 @440-442
- function_definition NumberEqualsInt32 @453-455
- function_definition NumberEqualsInt64 @466-468
- function_definition UnspecifiedNaN @475-484
- function_definition NumbersAreIdentical @492-498
- function_definition NumbersAreBitwiseIdentical @504-507
- function_definition EqualOrBothNaN @514-519
- function_definition NaNSafeMin @526-531
- function_definition NaNSafeMax @538-543
- struct_specifier FuzzyEqualsEpsilon @548-548
- struct_specifier FuzzyEqualsEpsilon<float> @551-554
- function_definition value @553-553
- struct_specifier FuzzyEqualsEpsilon<double> @557-560
- function_definition value @559-559
- function_definition FuzzyEqualsAdditive @577-581
- function_definition FuzzyEqualsMultiplicative @596-602

### mfbt/FunctionRef.h

Blob: `ad54bbf20e076cee58a687c84c668d25a44bd7b6`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @14
- include <type_traits> @15
- include <utility> @16
- include "mozilla/OperatorNewExtensions.h" @18
- struct_specifier MatchingFunctionPointerTag @46-46
- struct_specifier MatchingFunctorTag @47-47
- struct_specifier InvalidFunctorTag @48-48
- struct_specifier GetCallableTag @53-72
- struct_specifier GetCallableTag<std::nullptr_t, Ret, Params...> @77-77
- class_specifier MOZ_TEMPORARY_CLASS @96-96
- function_definition FunctionRef @99-213
- class_specifier MOZ_TEMPORARY_CLASS @99-99
- function_definition CallFunctionPointer @134-138
- function_definition FunctionRef @141-145
- function_definition FunctionRef @158-158
- function_definition operator() @207-209
- function_definition (anonymous) @212-212

### mfbt/FunctionTypeTraits.h

Blob: `d5b250de6c2a3530a63f0b12a470fd34a1d7c6f6`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @8
- struct_specifier FunctionTypeTraits @36-36
- struct_specifier FunctionTypeTraits<T&> @40-40
- struct_specifier FunctionTypeTraits<T&&> @42-42
- struct_specifier FunctionTypeTraits<T*> @44-44
- struct_specifier FunctionTypeTraits @48-48
- struct_specifier SafePackElement @52-52
- struct_specifier SafePackElement<N> @55-57
- struct_specifier SafePackElement<0, A, As...> @60-62
- struct_specifier SafePackElement<N, A, As...> @65-65
- struct_specifier FunctionTypeTraits<R(As...)> @74-79
- struct_specifier FunctionTypeTraits<R (C::*)(As...)> @83-83
- struct_specifier FunctionTypeTraits<R (C::*)(As...) const> @87-88
- struct_specifier FunctionTypeTraits<R NS_STDCALL(As...)> @93-94
- struct_specifier FunctionTypeTraits<R (NS_STDCALL C::*)(As...)> @98-99
- struct_specifier FunctionTypeTraits<R (NS_STDCALL C::*)(As...) const> @103-104

### mfbt/Fuzzing.h

Blob: `45e3478d727d1be569efc73814558629c3daf834`. Grammar: cpp. Status: syntax-clean.

- include <stdbool.h> @12
- include "mozilla/fuzzing/NyxWrapper.h" @17
- include "mozilla/ScopeExit.h" @20
- include "mozilla/fuzzing/Nyx.h" @21

### mfbt/HashFunctions.h

Blob: `b10a1fdcd0c01e102b449a9a78127b23effd866c`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @48
- include <cstring> @49
- include <type_traits> @50
- include "mozilla/Attributes.h" @52
- include "mozilla/EndianUtils.h" @53
- include "mozilla/MathAlgorithms.h" @54
- include "mozilla/Types.h" @55
- include "mozilla/WrappingOperations.h" @56
- function_definition ScrambleHashCode @81-98
- function_definition RotateLeft5 @102-105
- function_definition AddU32ToHash @107-151
- function_definition AddUintNToHash @160-162
- function_definition AddUintNToHash @165-169
- function_definition AddToHash @183-189
- function_definition AddToHash @192-201
- function_definition AddToHash @208-210
- function_definition AddToHash @213-218
- function_definition AddToHash @221-223
- function_definition HashGeneric @233-235
- function_definition HashBytes @244-270
- function_definition HashBytes @272-276
- function_definition HashString @278-280
- function_definition HashString @283-285
- function_definition HashString @287-290
- class_specifier UTF16Hasher @301-339
- function_definition UTF16Hasher @307-308
- function_definition Add @310-324
- function_definition Finish @326-338
- function_definition HashString @343-353
- function_definition HashString @358-361
- function_definition HashString @364-366
- function_definition HashLatin1AsUTF16 @370-377
- class_specifier HashCodeScrambler @407-475
- struct_specifier SipHasher @408-408
- function_definition HashCodeScrambler @414-415
- function_definition scramble @421-424
- function_definition offsetOfMK0 @426-428
- function_definition offsetOfMK1 @430-432
- struct_specifier SipHasher @435-474
- function_definition SipHasher @436-442
- function_definition sipHash @444-454
- function_definition sipRound @456-471

### mfbt/HashTable.h

Blob: `72c33ee15a5dabec2bbaa25f1b2b5df55718d063`. Grammar: cpp. Status: contains-errors.

- include <bit> @75
- include <type_traits> @76
- include <utility> @77
- include "mozilla/AllocPolicy.h" @79
- include "mozilla/Assertions.h" @80
- include "mozilla/Attributes.h" @81
- include "mozilla/Casting.h" @82
- include "mozilla/HashFunctions.h" @83
- include "mozilla/MathAlgorithms.h" @84
- include "mozilla/Maybe.h" @85
- include "mozilla/MemoryChecking.h" @86
- include "mozilla/MemoryReporting.h" @87
- include "mozilla/Opaque.h" @88
- include "mozilla/OperatorNewExtensions.h" @89
- include "mozilla/ReentrancyGuard.h" @90
- include "mozilla/UniquePtr.h" @91
- include "mozilla/WrappingOperations.h" @92
- struct_specifier DefaultHasher @97-97
- class_specifier HashMapEntry @100-100
- class_specifier HashTableEntry @105-105
- class_specifier HashTable @108-108
- function_definition HashMap @141-449
- class_specifier MOZ_STANDALONE_DEBUG @141-141
- struct_specifier MapHashPolicy @146-156
- function_definition (anonymous) @150-150
- function_definition setKey @153-155
- function_definition HashMap @167-169
- function_definition HashMap @171-171
- function_definition HashMap @174-174
- function_definition swap @178-178
- function_definition generation @183-183
- function_definition empty @186-186
- function_definition count @189-189
- function_definition capacity @193-193
- function_definition shallowSizeOfExcludingThis @198-200
- function_definition shallowSizeOfIncludingThis @201-204
- function_definition compact @208-208
- function_definition reserve @213-213
- function_definition HashMap @216-216
- function_definition has @222-224
- function_definition lookup @237-239
- function_definition readonlyThreadsafeLookup @243-245
- function_definition put @252-255
- function_definition put @258-267
- function_definition putNew @272-275
- function_definition putNew @278-282
- function_definition putNewInfallible @299-302
- function_definition lookupForAdd @337-339
- function_definition add @343-346
- function_definition relookupOrAdd @350-354
- function_definition remove @359-363
- function_definition remove @367-367
- function_definition clear @370-370
- function_definition clearAndCompact @373-373
- function_definition rekeyIfMoved @379-383
- function_definition rekeyAs @387-394
- function_definition iter @406-406
- function_definition modIter @419-419
- function_definition (anonymous) @424-424
- function_definition (anonymous) @425-425
- function_definition traceOwnedAllocs @434-436
- function_definition offsetOfHashShift @440-442
- function_definition offsetOfTable @443-445
- function_definition offsetOfEntryCount @446-448
- class_specifier HashSet @468-759
- struct_specifier SetHashPolicy @471-481
- function_definition (anonymous) @475-475
- function_definition setKey @478-480
- function_definition HashSet @492-494
- function_definition HashSet @496-496
- function_definition HashSet @499-499
- function_definition (anonymous) @500-500
- function_definition HashSet @503-503
- function_definition (anonymous) @504-504
- function_definition swap @507-507
- function_definition generation @512-512
- function_definition empty @515-515
- function_definition count @518-518
- function_definition capacity @522-522
- function_definition shallowSizeOfExcludingThis @527-529
- function_definition shallowSizeOfIncludingThis @530-533
- function_definition compact @537-537
- function_definition reserve @542-542
- function_definition has @547-549
- function_definition lookup @561-563
- function_definition readonlyThreadsafeLookup @567-569
- function_definition put @575-578
- function_definition putNew @583-585
- function_definition putNew @589-591
- function_definition putNewInfallible @608-610
- function_definition lookupForAdd @645-647
- function_definition add @651-653
- function_definition relookupOrAdd @657-660
- function_definition remove @665-669
- function_definition remove @673-673
- function_definition clear @676-676
- function_definition clearAndCompact @679-679
- function_definition rekeyIfMoved @685-689
- function_definition rekeyAs @693-700
- function_definition replaceKey @707-713
- function_definition replaceKey @714-716
- function_definition iter @728-728
- function_definition modIter @741-741
- function_definition (anonymous) @746-746
- function_definition (anonymous) @747-747
- function_definition traceOwnedAllocs @756-758
- struct_specifier PointerHasher @798-810
- function_definition hash @803-803
- function_definition match @805-807
- function_definition rekey @809-809
- struct_specifier DefaultHasher @814-830
- function_definition hash @817-822
- function_definition match @824-827
- function_definition rekey @829-829
- struct_specifier DefaultHasher<T, std::enable_if_t<std::is_enum_v<T>>> @834-846
- function_definition hash @838-838
- function_definition match @840-843
- function_definition rekey @845-845
- struct_specifier DefaultHasher<T*> @850-850
- struct_specifier DefaultHasher<UniquePtr<T, D>> @854-868
- function_definition hash @859-861
- function_definition match @863-865
- function_definition rekey @867-867
- struct_specifier DefaultHasher<double> @872-888
- function_definition hash @876-883
- function_definition match @885-887
- struct_specifier DefaultHasher<float> @892-907
- function_definition hash @896-902
- function_definition match @904-906
- struct_specifier CStringHasher @910-921
- function_definition hash @914-916
- function_definition match @918-920
- struct_specifier FallibleHashMethods @937-959
- function_definition maybeGetHash @946-949
- function_definition ensureHash @955-958
- function_definition MaybeGetHash @962-965
- function_definition EnsureHash @968-971
- class_specifier HashMapEntry @983-1020
- function_definition HashMapEntry @996-998
- function_definition HashMapEntry @1000-1000
- function_definition (anonymous) @1001-1001
- function_definition (anonymous) @1006-1006
- function_definition (anonymous) @1010-1010
- function_definition (anonymous) @1012-1012
- function_definition (anonymous) @1013-1013
- function_definition offsetOfKey @1015-1015
- function_definition offsetOfValue @1016-1016
- function_definition HashMapEntry @1018-1018
- function_definition operator= @1019-1019
- class_specifier HashTable @1029-1029
- class_specifier EntrySlot @1032-1032
- class_specifier HashTableEntry @1035-1160
- function_definition rawValuePtr @1119-1119
- function_definition isLiveHash @1121-1121
- function_definition valuePtr @1123-1123
- function_definition destroyStoredT @1125-1129
- function_definition HashTableEntry @1132-1132
- function_definition ~HashTableEntry @1134-1134
- function_definition HashTableEntry @1136-1136
- function_definition operator= @1137-1137
- function_definition destroy @1139-1139
- function_definition swap @1141-1155
- function_definition (anonymous) @1157-1157
- function_definition (anonymous) @1159-1159
- class_specifier EntrySlot @1165-1255
- function_definition EntrySlot @1176-1177
- function_definition isLiveHash @1180-1180
- function_definition EntrySlot @1182-1182
- function_definition EntrySlot @1183-1183
- function_definition (anonymous) @1185-1185
- function_definition (anonymous) @1186-1186
- function_definition operator== @1188-1188
- function_definition operator< @1190-1190
- function_definition (anonymous) @1192-1196
- function_definition destroy @1198-1198
- function_definition swap @1200-1203
- function_definition (anonymous) @1205-1205
- function_definition (anonymous) @1207-1207
- function_definition isFree @1209-1209
- function_definition clearLive @1211-1215
- function_definition clear @1217-1223
- function_definition isRemoved @1225-1225
- function_definition removeLive @1227-1231
- function_definition isLive @1233-1233
- function_definition setCollision @1235-1238
- function_definition unsetCollision @1239-1239
- function_definition hasCollision @1240-1240
- function_definition matchHash @1241-1243
- function_definition getKeyHash @1244-1244
- function_definition setLive @1247-1252
- function_definition toEntry @1254-1254
- function_definition AllocPolicy @1258-1560
- class_specifier MOZ_STANDALONE_DEBUG @1258-1258
- function_definition forEachSlot @1270-1278
- class_specifier Ptr @1284-1367
- function_definition Ptr @1294-1302
- function_definition Ptr @1305-1313
- function_definition isValid @1315-1315
- function_definition Ptr @1318-1326
- function_definition found @1328-1336
- function_definition (anonymous) @1338-1338
- function_definition operator== @1340-1343
- function_definition operator!= @1345-1350
- function_definition (anonymous) @1352-1358
- function_definition operator-> @1360-1366
- class_specifier AddPtr @1370-1406
- function_definition AddPtr @1378-1386
- function_definition AddPtr @1391-1400
- function_definition isLive @1402-1402
- function_definition AddPtr @1405-1405
- class_specifier Iterator @1411-1470
- function_definition moveToNextLiveEntry @1412-1416
- function_definition Iterator @1421-1435
- function_definition done @1447-1451
- function_definition (anonymous) @1453-1459
- function_definition next @1461-1469
- class_specifier ModIterator @1477-1496
- function_definition ModIterator @1485-1486
- function_definition remove @1507-1514
- function_definition (anonymous) @1516-1522
- function_definition rekey @1528-1540
- function_definition rekey @1542-1542
- function_definition ~ModIterator @1550-1559
- function_definition HashTable @1563-1563
- function_definition (anonymous) @1564-1572
- function_definition swap @1574-1586
- function_definition (anonymous) @1588-1588
- function_definition (anonymous) @1589-1589
- function_definition traceOwnedAllocs @1592-1596
- function_definition hashShift @1649-1651
- function_definition gen @1652-1654
- function_definition HashTable @1657-1657
- function_definition setHashShift @1667-1670
- function_definition bestCapacity @1672-1694
- function_definition hashShiftForLength @1696-1705
- function_definition isLiveHash @1707-1707
- function_definition prepareHash @1709-1717
- enum_specifier FailureBehavior @1719-1719
- struct_specifier FakeSlot @1723-1725
- function_definition createTable @1727-1745
- function_definition destroyTable @1747-1755
- function_definition freeTable @1757-1761
- function_definition HashTable @1778-1779
- function_definition ~HashTable @1781-1785
- struct_specifier DoubleHash @1790-1793
- function_definition hash2 @1795-1800
- function_definition applyDoubleHash @1802-1805
- function_definition match @1807-1809
- enum_specifier LookupReason @1811-1811
- function_definition slotForIndex @1813-1817
- function_definition lookup @1822-1868
- function_definition findNonLiveSlot @1873-1901
- enum_specifier RebuildStatus @1903-1903
- function_definition changeTableSize @1905-1947
- function_definition rehashIfOverloaded @1949-1970
- function_definition infallibleRehashIfOverloaded @1972-1976
- function_definition remove @1978-1991
- function_definition shrinkIfUnderloaded @1993-2003
- function_definition rehashTableInPlace @2010-2043
- function_definition putNewInfallibleInternal @2048-2063
- function_definition compact @2081-2094
- function_definition shrinkToBestCapacity @2096-2101
- function_definition clearAndCompact @2103-2106
- function_definition reserve @2108-2126
- function_definition iter @2128-2128
- function_definition modIter @2130-2130
- function_definition empty @2132-2132
- function_definition count @2134-2134
- function_definition rawCapacity @2136-2136
- function_definition capacity @2138-2138
- function_definition generation @2140-2140
- function_definition shallowSizeOfExcludingThis @2142-2144
- function_definition shallowSizeOfIncludingThis @2146-2148
- function_definition readonlyThreadsafeLookup @2150-2162
- function_definition lookup @2164-2167
- function_definition lookupForAdd @2169-2187
- function_definition add @2190-2248
- function_definition putNewInfallible @2253-2258
- function_definition putNew @2263-2279
- function_definition relookupOrAdd @2284-2308
- function_definition remove @2310-2317
- function_definition rekeyWithoutRehash @2320-2330
- function_definition rekeyAndMaybeRehash @2333-2336
- function_definition offsetOfHashShift @2338-2352
- function_definition offsetOfTable @2353-2353
- function_definition offsetOfEntryCount @2354-2356

### mfbt/HelperMacros.h

Blob: `9a2cd428bda99d5bb5be0f7d846abdfb7ea6e7f2`. Grammar: cpp. Status: syntax-clean.


### mfbt/InitializedOnce.h

Blob: `fcf19b79cee339e7865ac4f1985b31a6183945ba`. Grammar: cpp. Status: contains-errors.

- include <type_traits> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/Maybe.h" @13
- enum_specifier InitWhen @19-19
- enum_specifier DestroyWhen @20-20
- struct_specifier AllowAnyValue @24-26
- function_definition Check @25-25
- struct_specifier ConvertsToTrue @29-33
- function_definition Check @30-32
- class_specifier InitializedOnce @46-143
- function_definition InitializedOnce @62-62
- function_definition InitializedOnce @68-72
- function_definition InitializedOnce @74-74
- function_definition InitializedOnce @75-80
- function_definition (anonymous) @81-81
- function_definition (anonymous) @82-93
- function_definition init @97-102
- function_definition (anonymous) @104-104
- function_definition isSome @105-105
- function_definition isNothing @106-106
- function_definition (anonymous) @108-108
- function_definition operator-> @109-109
- function_definition (anonymous) @111-111
- function_definition destroy @115-118
- function_definition maybeDestroy @122-127
- function_definition release @131-136
- class_specifier LazyInitializer @147-165
- function_definition LazyInitializer @149-151
- function_definition (anonymous) @154-157
- function_definition LazyInitializer @159-159
- function_definition (anonymous) @160-160
- function_definition do_Init @244-247

### mfbt/IntegerRange.h

Blob: `82c317cd2ae22922b441c3a83fa2c881850f8451`. Grammar: cpp. Status: syntax-clean.

- include <iterator> @10
- include <type_traits> @11
- include "mozilla/Assertions.h" @13
- include "mozilla/ReverseIterator.h" @14
- class_specifier IntegerIterator @21-79
- function_definition IntegerIterator @36-36
- function_definition IntegerIterator @39-40
- function_definition operator* @46-46
- function_definition (anonymous) @50-53
- function_definition (anonymous) @54-57
- function_definition operator++ @58-62
- function_definition operator-- @63-67
- function_definition operator== @71-71
- function_definition operator< @72-72
- function_definition operator<= @73-73
- function_definition operator> @74-74
- function_definition operator>= @75-75
- class_specifier IntegerRange @82-107
- function_definition IntegerRange @90-90
- function_definition IntegerRange @93-93
- function_definition begin @95-95
- function_definition cbegin @96-96
- function_definition end @97-97
- function_definition cend @98-98
- function_definition rbegin @99-99
- function_definition crbegin @100-100
- function_definition rend @101-101
- function_definition crend @102-102
- function_definition IntegerRange @112-118
- function_definition IntegerRange @121-128

### mfbt/IntegerTypeTraits.h

Blob: `4ca687f9002c6d6e1cf9356572e7258857d6ba1a`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include <type_traits> @11
- struct_specifier StdintTypeForSizeAndSignedness @23-23
- struct_specifier StdintTypeForSizeAndSignedness<1, true> @26-28
- struct_specifier StdintTypeForSizeAndSignedness<1, false> @31-33
- struct_specifier StdintTypeForSizeAndSignedness<2, true> @36-38
- struct_specifier StdintTypeForSizeAndSignedness<2, false> @41-43
- struct_specifier StdintTypeForSizeAndSignedness<4, true> @46-48
- struct_specifier StdintTypeForSizeAndSignedness<4, false> @51-53
- struct_specifier StdintTypeForSizeAndSignedness<8, true> @56-58
- struct_specifier StdintTypeForSizeAndSignedness<8, false> @61-63
- struct_specifier UnsignedStdintTypeForSize @68-69
- struct_specifier SignedStdintTypeForSize @72-73
- struct_specifier PositionOfSignBit @76-81

### mfbt/JSONWriter.h

Blob: `207869b3b5368b1981ac47ab1e1fe5037de2a7ed`. Grammar: cpp. Status: contains-errors.

- include <utility> @93
- include "double-conversion/double-conversion.h" @95
- include "mozilla/Assertions.h" @96
- include "mozilla/Span.h" @97
- include "mozilla/Sprintf.h" @98
- include "mozilla/UniquePtr.h" @99
- include "mozilla/Vector.h" @100
- class_specifier JSONWriteFunc @107-111
- function_definition ~JSONWriteFunc @110-110
- class_specifier JSONWriter @113-567
- class_specifier EscapedString @127-243
- function_definition CheckInvariants @134-138
- function_definition hexDigitToAsciiChar @140-143
- function_definition EscapedString @146-238
- function_definition EscapedString @240-240
- function_definition (anonymous) @242-242
- enum_specifier CollectionStyle @254-257
- function_definition Indent @285-289
- function_definition Separator @294-304
- function_definition PropertyNameAndColon @306-313
- function_definition Scalar @315-323
- function_definition QuotedScalar @325-335
- function_definition NewVectorEntries @337-344
- function_definition StartCollection @346-357
- function_definition EndCollection @360-370
- function_definition JSONWriter @373-377
- function_definition JSONWriter @379-390
- function_definition (anonymous) @394-394
- function_definition Start @403-405
- function_definition End @408-413
- function_definition NullProperty @416-418
- function_definition NullProperty @421-425
- function_definition NullElement @428-428
- function_definition BoolProperty @431-433
- function_definition BoolProperty @436-440
- function_definition BoolElement @443-443
- function_definition IntProperty @446-451
- function_definition IntProperty @454-458
- function_definition IntElement @461-461
- function_definition DoubleProperty @464-473
- function_definition DoubleProperty @476-480
- function_definition DoubleElement @483-483
- function_definition StringProperty @486-489
- function_definition StringProperty @492-496
- function_definition StringProperty @499-503
- function_definition StringProperty @506-510
- function_definition StringElement @513-515
- function_definition StringElement @518-522
- function_definition StartArrayProperty @525-528
- function_definition StartArrayProperty @531-536
- function_definition StartArrayElement @539-541
- function_definition EndArray @544-544
- function_definition StartObjectProperty @547-550
- function_definition StartObjectProperty @553-558
- function_definition StartObjectElement @561-563
- function_definition EndObject @566-566

### mfbt/JsRust.h

Blob: `e2f4f73896d28ff2f958a0f3bfe97576ebe1b817`. Grammar: cpp. Status: syntax-clean.


### mfbt/Latin1.h

Blob: `5bab8199583d764b234e45738bb3985f0cccd24d`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @15
- include <type_traits> @16
- include "mozilla/JsRust.h" @18
- include "encoding_rs_mem.h" @21
- include "mozilla/Span.h" @22
- class_specifier MakeUnsignedChar @36-39
- class_specifier MakeUnsignedChar<char16_t> @42-45
- class_specifier MakeUnsignedChar<char32_t> @48-51
- function_definition IsNonAsciiLatin1 @60-64
- function_definition IsUtf16Latin1 @74-90
- function_definition IsUtf8Latin1 @101-103
- function_definition UnsafeIsValidUtf8Latin1 @112-114
- function_definition Utf8Latin1UpTo @126-128
- function_definition UnsafeValidUtf8Lati1UpTo @138-140
- function_definition LossyConvertUtf16toLatin1 @150-172
- function_definition LossyConvertUtf8toLatin1 @184-188
- function_definition ConvertLatin1toUtf8 @198-202
- function_definition ConvertLatin1toUtf8Partial @223-230
- function_definition ConvertLatin1toUtf16 @238-257

### mfbt/Likely.h

Blob: `12b52925caed9a46915cef7e2bc84dacb77cc45b`. Grammar: cpp. Status: syntax-clean.


### mfbt/LinkedList.h

Blob: `3829d11d26ebec8e0f1b61c95ddd30922d75ba6e`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @65
- include <iterator> @66
- include <utility> @67
- include "mozilla/Assertions.h" @69
- include "mozilla/MemoryReporting.h" @70
- include "mozilla/RefPtr.h" @71
- class_specifier LinkedListElement @78-78
- struct_specifier LinkedListElementTraits @88-106
- function_definition enterList @99-99
- function_definition exitList @100-100
- function_definition cleanElement @105-105
- struct_specifier LinkedListElementTraits<RefPtr<T>> @109-122
- function_definition enterList @115-117
- function_definition exitList @118-120
- function_definition cleanElement @121-121
- class_specifier LinkedList @127-127
- class_specifier LinkedListElement @130-406
- function_definition LinkedListElement @177-178
- function_definition LinkedListElement @184-187
- function_definition (anonymous) @189-195
- function_definition ~LinkedListElement @197-201
- function_definition (anonymous) @203-203
- function_definition LinkedListElement @204-204
- function_definition getNext @210-210
- function_definition getNext @211-211
- function_definition getPrevious @217-217
- function_definition getPrevious @218-218
- function_definition setNext @224-227
- function_definition setPrevious @234-237
- function_definition remove @243-252
- function_definition removeAndGetNext @260-264
- function_definition removeAndGetPrevious @272-276
- function_definition removeFrom @282-285
- function_definition isInList @290-293
- enum_specifier NodeKind @299-299
- function_definition LinkedListElement @301-302
- function_definition asT @308-308
- function_definition asT @309-311
- function_definition setNextUnsafe @317-327
- function_definition setPreviousUnsafe @333-343
- function_definition transferBeforeUnsafe @348-365
- function_definition adjustLinkForMove @371-405
- class_specifier LinkedList @409-721
- class_specifier IteratorImpl @426-457
- function_definition IteratorImpl @438-440
- function_definition operator* @442-442
- function_definition (anonymous) @444-448
- function_definition (anonymous) @450-454
- function_definition operator== @456-456
- function_definition LinkedList @460-461
- function_definition LinkedList @463-463
- function_definition (anonymous) @465-470
- function_definition ~LinkedList @472-482
- function_definition (anonymous) @484-484
- function_definition LinkedList @485-485
- function_definition begin @493-493
- function_definition begin @494-494
- function_definition cbegin @495-495
- function_definition end @496-496
- function_definition end @497-497
- function_definition cend @498-498
- function_definition rbegin @500-500
- function_definition rbegin @501-503
- function_definition crbegin @504-504
- function_definition rend @505-505
- function_definition rend @506-508
- function_definition crend @509-509
- function_definition insertFront @514-517
- function_definition insertBack @522-522
- function_definition extendBack @527-533
- function_definition splice @538-566
- function_definition getFirst @571-571
- function_definition getFirst @572-572
- function_definition getLast @577-577
- function_definition getLast @578-578
- function_definition popFirst @584-590
- function_definition popLast @596-602
- function_definition isEmpty @607-607
- function_definition contains @612-614
- function_definition clear @622-625
- function_definition length @630-630
- function_definition sizeOfExcludingThis @638-646
- function_definition sizeOfIncludingThis @651-653
- function_definition debugAssertIsSane @659-706
- function_definition assertContains @711-720
- function_definition RangeSizeEstimate @724-726
- function_definition ImplCycleCollectionUnlink @729-731
- function_definition ImplCycleCollectionTraverse @734-746
- class_specifier AutoCleanLinkedList @749-766
- function_definition AutoCleanLinkedList @755-755
- function_definition AutoCleanLinkedList @756-756
- function_definition ~AutoCleanLinkedList @757-757
- function_definition (anonymous) @759-759
- function_definition clear @761-765

### mfbt/Literals.h

Blob: `b8de980ae707085d52c97434747edae9d6ffda27`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @10
- function_definition operator""_KiB @17-19
- function_definition operator""_KiB @21-23
- function_definition operator""_MiB @25-27
- function_definition operator""_MiB @29-31
- function_definition operator""_percent @33-35

### mfbt/MacroArgs.h

Blob: `550e1d7d480131c7e9458ad270705d4119315fd5`. Grammar: cpp. Status: syntax-clean.


### mfbt/MacroForEach.h

Blob: `08c0aea171b0d1d37182e52aecb7e168206e167a`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/MacroArgs.h" @14

### mfbt/MathAlgorithms.h

Blob: `f354b0a05ee23c448ded286a0c051b50115c277a`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @10
- include <bit> @11
- include <climits> @12
- include <cmath> @13
- include <cstdint> @14
- include <type_traits> @15
- include "mozilla/Assertions.h" @17
- struct_specifier AbsReturnType @24-24
- struct_specifier AbsReturnType<
    T, std::enable_if_t<std::is_integral_v<T> && std::is_signed_v<T>>> @27-30
- struct_specifier AbsReturnType<T, std::enable_if_t<std::is_floating_point_v<T>>> @33-35
- function_definition Abs @40-43
- function_definition Abs @46-48
- function_definition Abs @51-53
- function_definition Abs @56-58
- function_definition CeilingLog2 @70-76
- function_definition CeilingLog2Size @79-81
- function_definition FindMostSignificantBit @88-93
- function_definition FloorLog2 @104-106
- function_definition FloorLog2Size @109-111
- function_definition RoundUpPow2 @117-121
- function_definition RotateLeft @127-132
- function_definition RotateRight @138-143
- function_definition GCD @148-190

### mfbt/Maybe.h

Blob: `934a10e5dee73380a1cb6cfd44d612ecc434d993`. Grammar: cpp. Status: contains-errors.

- include <functional> @10
- include <new> @11
- include <ostream> @12
- include <type_traits> @13
- include <utility> @14
- include "mozilla/Assertions.h" @16
- include "mozilla/Attributes.h" @17
- include "mozilla/MaybeStorageBase.h" @18
- include "mozilla/MemoryChecking.h" @19
- include "mozilla/OperatorNewExtensions.h" @20
- include "mozilla/Poison.h" @21
- include "mozilla/ThreadSafety.h" @22
- class_specifier nsCycleCollectionTraversalCallback @24-24
- struct_specifier Nothing @33-33
- function_definition operator== @35-35
- class_specifier Maybe @38-38
- function_definition WritePoisonAtOffset @52-55
- struct_specifier InlinePoisoner @58-63
- function_definition poison @59-62
- struct_specifier InlinePoisoner<N, N> @66-70
- function_definition poison @67-69
- struct_specifier OutOfLinePoisoner @76-80
- function_definition poison @77-79
- function_definition PoisonObject @83-88
- struct_specifier MaybePoisoner @91-102
- function_definition poison @94-101
- class_specifier Maybe_CopyMove_Enabler @109-109
- class_specifier MOZ_TRIVIAL_ABI @147-147
- function_definition Maybe_CopyMove_Enabler @151-151
- function_definition Maybe_CopyMove_Enabler @153-155
- function_definition (anonymous) @156-159
- class_specifier MOZ_TRIVIAL_ABI @166-166
- function_definition Maybe_CopyMove_Enabler @170-170
- function_definition Maybe_CopyMove_Enabler @172-174
- function_definition (anonymous) @175-178
- class_specifier Maybe_CopyMove_Enabler<T, false, true, true> @185-1193
- function_definition Maybe_CopyMove_Enabler @187-187
- class_specifier Maybe_CopyMove_Enabler<T, false, false, true> @197-890
- function_definition Maybe_CopyMove_Enabler @199-199
- function_definition Maybe_CopyMove_Enabler @201-201
- function_definition (anonymous) @202-202
- class_specifier Maybe_CopyMove_Enabler<T, false, true, false> @210-309
- function_definition Maybe_CopyMove_Enabler @212-212
- function_definition Maybe_CopyMove_Enabler @215-215
- function_definition (anonymous) @216-216
- class_specifier Maybe_CopyMove_Enabler<T, TriviallyDestructibleAndCopyable, false,
                             false> @223-232
- function_definition Maybe_CopyMove_Enabler @226-226
- function_definition Maybe_CopyMove_Enabler @228-228
- function_definition (anonymous) @229-229
- function_definition Maybe_CopyMove_Enabler @230-230
- function_definition (anonymous) @231-231
- struct_specifier MaybeStorage @240-240
- struct_specifier MaybeStorage<T, false> @243-272
- function_definition MaybeStorage @247-247
- function_definition MaybeStorage @248-249
- function_definition MaybeStorage @250-251
- function_definition MaybeStorage @254-256
- function_definition MaybeStorage @262-262
- function_definition (anonymous) @263-263
- function_definition MaybeStorage @264-264
- function_definition (anonymous) @265-265
- function_definition ~MaybeStorage @267-271
- struct_specifier MaybeStorage<T, true> @279-295
- function_definition MaybeStorage @285-285
- function_definition MaybeStorage @286-287
- function_definition MaybeStorage @288-289
- function_definition MaybeStorage @292-294
- struct_specifier IsMaybeImpl @301-301
- struct_specifier IsMaybeImpl<Maybe<T>> @304-304
- class_specifier MOZ_INHERIT_TYPE_ANNOTATIONS_FROM_TEMPLATE_ARGS @366-366
- struct_specifier SomeGuard @375-375
- function_definition Maybe @378-379
- function_definition poisonData @384-384
- function_definition Maybe @389-389
- function_definition Maybe @391-391
- function_definition Maybe @394-395
- function_definition Maybe @403-407
- function_definition Maybe @411-411
- function_definition Maybe @419-424
- function_definition Maybe @427-427
- function_definition (anonymous) @431-442
- function_definition (anonymous) @450-463
- function_definition (anonymous) @469-472
- function_definition (anonymous) @475-475
- function_definition isSome @476-476
- function_definition isNothing @477-477
- function_definition extract @490-495
- function_definition take @501-501
- function_definition valueOr @515-520
- function_definition valueOrFrom @527-532
- function_definition ptrOr @543-548
- function_definition ptrOr @550-555
- function_definition ptrOrFrom @562-567
- function_definition ptrOrFrom @570-575
- function_definition (anonymous) @590-595
- function_definition (anonymous) @597-603
- function_definition (anonymous) @610-615
- function_definition (anonymous) @618-623
- function_definition (anonymous) @633-638
- function_definition (anonymous) @641-646
- function_definition (anonymous) @649-654
- function_definition (anonymous) @657-662
- function_definition map @670-675
- function_definition map @678-683
- function_definition map @686-691
- function_definition map @694-699
- function_definition andThen @709-717
- function_definition andThen @720-728
- function_definition andThen @731-739
- function_definition andThen @742-750
- function_definition orElse @757-765
- function_definition orElse @768-776
- function_definition orElse @779-787
- function_definition orElse @790-798
- struct_specifier Iterator @803-833
- function_definition Iterator @811-811
- function_definition Iterator @812-812
- function_definition operator* @814-814
- function_definition operator-> @816-816
- function_definition (anonymous) @818-821
- function_definition operator++ @823-827
- function_definition operator<=> @829-829
- function_definition begin @839-839
- function_definition begin @840-842
- function_definition cbegin @843-843
- function_definition end @845-845
- function_definition end @846-846
- function_definition cend @847-847
- function_definition reset @850-864
- function_definition emplace @874-879
- function_definition (anonymous) @881-889
- class_specifier Maybe<T&> @893-967
- function_definition Maybe @895-895
- function_definition Maybe @896-896
- function_definition emplace @898-898
- function_definition (anonymous) @901-901
- function_definition isSome @902-902
- function_definition isNothing @903-903
- function_definition (anonymous) @905-908
- function_definition operator-> @910-910
- function_definition (anonymous) @911-911
- function_definition reset @918-918
- function_definition (anonymous) @921-926
- function_definition map @929-935
- function_definition andThen @938-946
- function_definition orElse @949-957
- function_definition refEquals @959-961
- function_definition refEquals @963-963
- function_definition value @970-973
- function_definition value @976-979
- function_definition value @982-985
- function_definition ptr @988-991
- function_definition ptr @994-997
- function_definition operator-> @1000-1003
- function_definition operator-> @1006-1009
- function_definition (anonymous) @1012-1015
- function_definition (anonymous) @1018-1021
- function_definition (anonymous) @1024-1027
- function_definition (anonymous) @1030-1033
- function_definition (anonymous) @1036-1039
- function_definition (anonymous) @1042-1045
- function_definition (anonymous) @1048-1051
- function_definition (anonymous) @1054-1057
- function_definition emplace @1061-1065
- function_definition Some @1078-1080
- function_definition SomeRef @1083-1087
- function_definition ToMaybeRef @1090-1092
- function_definition ToMaybe @1095-1100
- function_definition operator== @1108-1116
- function_definition operator!= @1119-1121
- function_definition operator== @1128-1130
- function_definition operator!= @1133-1135
- function_definition operator== @1138-1140
- function_definition operator!= @1143-1145
- function_definition operator< @1152-1160
- function_definition operator> @1163-1165
- function_definition operator<= @1168-1170
- function_definition operator>= @1173-1175
- function_definition ImplCycleCollectionTraverse @1178-1184
- function_definition ImplCycleCollectionUnlink @1187-1191

### mfbt/MaybeFmt.h

Blob: `b515f358e055c16a9bdd2c216253ded089b05453`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Maybe.h" @8
- include <fmt/base.h> @10
- struct_specifier fmt::formatter<mozilla::Maybe<T>, Char> @13-31
- function_definition parse @19-21
- function_definition format @24-30

### mfbt/MaybeOneOf.h

Blob: `474feb65214cf38b10fa235bd8deb37664bda609`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @13
- include <algorithm> @15
- include <new> @16
- include <utility> @17
- include "mozilla/Assertions.h" @19
- include "mozilla/OperatorNewExtensions.h" @20
- function_definition MaybeOneOf @40-150
- class_specifier MOZ_NON_PARAM @40-40
- function_definition data @48-48
- function_definition data @49-49
- enum_specifier State @51-51
- struct_specifier Type2State @53-53
- function_definition (anonymous) @56-59
- function_definition (anonymous) @62-65
- function_definition ~MaybeOneOf @69-69
- function_definition MaybeOneOf @71-82
- function_definition (anonymous) @84-89
- function_definition empty @91-91
- function_definition constructed @94-96
- function_definition construct @99-103
- function_definition (anonymous) @106-108
- function_definition (anonymous) @111-113
- function_definition destroy @115-123
- function_definition destroyIfConstructed @125-129
- function_definition mapNonEmpty @132-138
- function_definition mapNonEmpty @140-146
- function_definition MaybeOneOf @148-148
- struct_specifier MaybeOneOf<T1, T2>::Type2State<T1, Ignored> @154-157
- struct_specifier MaybeOneOf<T1, T2>::Type2State<T2, Ignored> @161-164

### mfbt/MaybeStorageBase.h

Blob: `dc4a9bbad62d7d01da94c78317518536328b3bb2`. Grammar: cpp. Status: syntax-clean.

- include <type_traits> @11
- include <utility> @12
- struct_specifier MaybeStorageBase @24-24
- struct_specifier MaybeStorageBase<T, false> @27-57
- function_definition Union @32-32
- function_definition Union @33-33
- function_definition Union @36-36
- function_definition Union @38-39
- function_definition ~Union @41-41
- function_definition MaybeStorageBase @48-48
- function_definition MaybeStorageBase @49-49
- function_definition MaybeStorageBase @50-50
- function_definition MaybeStorageBase @52-53
- function_definition addr @55-55
- function_definition addr @56-56
- struct_specifier MaybeStorageBase<T, true> @60-87
- function_definition Union @65-65
- function_definition Union @66-66
- function_definition Union @67-67
- function_definition Union @69-70
- function_definition MaybeStorageBase @77-77
- function_definition MaybeStorageBase @78-78
- function_definition MaybeStorageBase @79-79
- function_definition MaybeStorageBase @82-83
- function_definition addr @85-85
- function_definition addr @86-86

### mfbt/MemoryChecking.h

Blob: `b18f475c2ac37ca10330f2f3fe51c376acb06661`. Grammar: cpp. Status: contains-errors.

- include "valgrind/memcheck.h" @25
- include <stddef.h> @33
- include "mozilla/Types.h" @35
- include <stddef.h> @70
- include "mozilla/Types.h" @72

### mfbt/MemoryReporting.h

Blob: `7079e4b9c768d15c84eed9268adec8a8f78015e0`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @10

### mfbt/MoveOnlyFunction.h

Blob: `25dac4432ec74abab876992b0e4a2ae34445f07c`. Grammar: cpp. Status: syntax-clean.

- include "function2/function2.hpp" @12

### mfbt/MruCache.h

Blob: `912bc41a1d8b679d3887ea45437e88db45915236`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @8
- include <type_traits> @9
- include <utility> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/Attributes.h" @13
- include "mozilla/HashFunctions.h" @14
- include "mozilla/MathAlgorithms.h" @15
- class_specifier MruCache @62-180
- function_definition MruCache @75-75
- function_definition MruCache @76-76
- function_definition MruCache @77-77
- function_definition IsEmpty @81-86
- function_definition Put @92-94
- function_definition Remove @97-97
- function_definition Clear @100-104
- class_specifier Entry @116-145
- function_definition Entry @118-120
- function_definition (anonymous) @122-122
- function_definition (anonymous) @124-127
- function_definition Set @130-133
- function_definition Remove @135-140
- function_definition Lookup @150-171
- function_definition SetIndex @177-177

### mfbt/NeverDestroyed.h

Blob: `bb160b630c414fafcc39cc59f976ce5d676af2c0`. Grammar: cpp. Status: contains-errors.

- include <new> @8
- include <type_traits> @9
- include <utility> @10
- include "mozilla/Attributes.h" @12
- function_definition NeverDestroyed @28-61
- class_specifier MOZ_STATIC_LOCAL_CLASS @28-28
- function_definition NeverDestroyed @39-41
- function_definition (anonymous) @43-43
- function_definition (anonymous) @44-44
- function_definition operator-> @46-46
- function_definition operator-> @47-47
- function_definition get @49-49
- function_definition get @50-50
- function_definition NeverDestroyed @53-53

### mfbt/NonDereferenceable.h

Blob: `ee0a1be0a6caf90b6bee3e29561a04c73c214d27`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @10
- include "mozilla/Attributes.h" @12
- class_specifier NonDereferenceable @48-117
- function_definition NonDereferenceable @51-51
- function_definition NonDereferenceable @54-55
- function_definition (anonymous) @56-57
- function_definition NonDereferenceable @68-68
- function_definition (anonymous) @69-73
- function_definition mPtr @77-78
- function_definition (anonymous) @80-83
- function_definition (anonymous) @87-95
- function_definition (anonymous) @99-99
- function_definition operator-> @100-100
- function_definition (anonymous) @104-104
- function_definition value @107-108

### mfbt/NotNull.h

Blob: `cfe75c7d7ab82c75a502ad5dc6349b2c283b880a`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @63
- include <type_traits> @64
- include <utility> @65
- include "mozilla/Assertions.h" @67
- struct_specifier CopyablePtr @73-82
- function_definition CopyablePtr @78-78
- function_definition CopyablePtr @81-81
- class_specifier MovingNotNull @86-86
- class_specifier NotNull @122-200
- function_definition NotNull @136-141
- function_definition NotNull @145-145
- function_definition (anonymous) @163-163
- function_definition (anonymous) @166-166
- function_definition (anonymous) @174-176
- function_definition operator-> @187-189
- function_definition operator* @190-192
- function_definition NotNull @198-198
- function_definition (anonymous) @199-199
- function_definition NotNull @218-218
- function_definition NotNull @222-222

### mfbt/Opaque.h

Blob: `c9eacd23f1a8bf01a107f08c470f712b94a376f4`. Grammar: cpp. Status: syntax-clean.

- include <type_traits> @10
- class_specifier Opaque @20-31
- function_definition Opaque @27-27
- function_definition Opaque @28-28
- function_definition operator== @30-30

### mfbt/OperatorNewExtensions.h

Blob: `c0235842662c1b9cdeed0cb02d54de867620ad5e`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Assertions.h" @10
- enum_specifier NotNullTag @15-17
- function_definition operator new @43-46

### mfbt/PairHash.h

Blob: `5e0668e02c81c563adf3affade0dd00d1381fd50`. Grammar: cpp. Status: syntax-clean.

- include <utility> @10
- include "mozilla/CompactPair.h" @12
- include "mozilla/HashFunctions.h" @13
- function_definition HashPair @24-27
- function_definition HashCompactPair @30-33
- struct_specifier PairHasher @39-50
- function_definition hash @43-43
- function_definition match @45-47
- function_definition rekey @49-49
- struct_specifier CompactPairHasher @56-69
- function_definition hash @60-62
- function_definition match @64-66
- function_definition rekey @68-68

### mfbt/Path.h

Blob: `dd20ce2a4a8f92672bf92e0fe6424b44a59d8a11`. Grammar: cpp. Status: syntax-clean.

- class_specifier Path @17-24

### mfbt/PodOperations.h

Blob: `f57a9019db86ddccf3721b42ff65b50d347e4e29`. Grammar: cpp. Status: contains-errors.

- include <cstring> @16
- include <limits> @17
- include <type_traits> @18
- include "mozilla/Assertions.h" @20
- include "mozilla/Attributes.h" @21
- class_specifier Array @26-26
- class_specifier NotNull @29-29
- function_definition PodZero @33-37
- function_definition PodZero @41-56
- function_definition PodZero @60-62
- function_definition PodArrayZero @78-83
- function_definition PodArrayZero @86-91
- function_definition PodCopy @98-129
- function_definition PodCopy @132-149
- function_definition PodArrayCopy @156-158
- function_definition PodMove @167-173

### mfbt/Poison.cpp

Blob: `b46c57ff055bedc038bb7cefc5237131784af1c8`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Poison.h" @10
- include "mozilla/Assertions.h" @12
- include <windows.h> @14
- include <unistd.h> @16
- include <sys/mman.h> @18
- function_definition ReserveRegion @38-40
- function_definition ReleaseRegion @42-44
- function_definition ProbeRegion @46-55
- function_definition GetDesiredRegionSize @57-61
- function_definition ReserveRegion @66-70
- function_definition ReleaseRegion @72-72
- function_definition ProbeRegion @74-78
- function_definition GetDesiredRegionSize @80-83
- function_definition ReserveRegion @91-93
- function_definition ReleaseRegion @95-95
- function_definition ProbeRegion @97-102
- function_definition GetDesiredRegionSize @104-104
- include "mozilla/TaggedAnonymousMemory.h" @108
- function_definition ReserveRegion @110-114
- function_definition ReleaseRegion @116-118
- function_definition GetDesiredRegionSize @132-132
- function_definition ReservePoisonArea @141-182
- function_definition GetPoisonValue @184-189

### mfbt/Poison.h

Blob: `341f8387fc8e999caeabc942b7e8d3c6f12347c1`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @13
- include <string.h> @14
- include "mozilla/Assertions.h" @16
- include "mozilla/Types.h" @17
- function_definition mozPoisonValue @26-26
- function_definition mozWritePoison @33-41
- class_specifier CorruptionCanaryForStatics @57-75
- function_definition CorruptionCanaryForStatics @59-59
- function_definition ~CorruptionCanaryForStatics @62-62
- function_definition Check @64-68
- class_specifier CorruptionCanary @93-101
- function_definition CorruptionCanary @95-95
- function_definition ~CorruptionCanary @97-100

### mfbt/RandomNum.cpp

Blob: `c5e1d9b454ef90bf1881e60c423559dba4b2d705`. Grammar: cpp. Status: contains-errors.

- include "mozilla/RandomNum.h" @5
- include <fcntl.h> @8
- include <unistd.h> @9
- include "minwindef.h" @13
- include "mozilla/DynamicallyLinkedFunctionPtr.h" @14
- include <linux/random.h> @24
- include <sys/syscall.h> @25
- include <sgidefs.h> @42
- function_definition GenerateRandomBytesFromOS @75-120
- function_definition RandomUint64 @122-129
- function_definition RandomUint64OrDie @131-135

### mfbt/RandomNum.h

Blob: `aaa89c70a8fa3c95f2b567f6afe43e73d13d5cf4`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Maybe.h" @10
- include "mozilla/Types.h" @11

### mfbt/Range.h

Blob: `90538a09125bd9fb0bc9da9293f0e1515a368afb`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @8
- include <type_traits> @10
- include "mozilla/RangedPtr.h" @12
- include "mozilla/Span.h" @13
- class_specifier Range @19-71
- function_definition Range @29-29
- function_definition Range @30-39
- function_definition Range @40-46
- function_definition begin @50-60
- function_definition end @61-61
- function_definition length @62-62
- function_definition (anonymous) @64-64
- function_definition (anonymous) @66-66
- function_definition (anonymous) @68-68
- function_definition (anonymous) @70-70

### mfbt/RangedArray.h

Blob: `acc2ff78b162c52f7edc1aae24cf91176911b466`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Array.h" @16
- class_specifier RangedArray @21-60
- function_definition length @27-27
- function_definition minIndex @28-28
- function_definition (anonymous) @30-33
- function_definition (anonymous) @35-38
- function_definition begin @46-46
- function_definition begin @47-47
- function_definition cbegin @48-48
- function_definition end @49-49
- function_definition end @50-50
- function_definition cend @51-51
- function_definition rbegin @54-54
- function_definition rbegin @55-55
- function_definition crbegin @56-56
- function_definition rend @57-57
- function_definition rend @58-58
- function_definition crend @59-59

### mfbt/RangedPtr.h

Blob: `23d9fbb9e64e14232ffcb0d0a5032e4b242c39a0`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @13
- include <cstdint> @14
- include "mozilla/ArrayUtils.h" @16
- include "mozilla/Assertions.h" @17
- include "mozilla/Attributes.h" @18
- function_definition checkSanity @53-56
- function_definition create @59-65
- function_definition asUintptr @67-67
- function_definition RangedPtr @82-86
- function_definition RangedPtr @88-88
- function_definition RangedPtr @91-91
- function_definition (anonymous) @95-100
- function_definition (anonymous) @105-110
- function_definition get @112-112
- function_definition (anonymous) @114-114
- function_definition checkIdenticalRange @116-119
- function_definition ReinterpretCast @122-129
- function_definition (anonymous) @141-146
- function_definition operator+ @148-152
- function_definition operator- @154-158
- function_definition (anonymous) @165-168
- function_definition (anonymous) @171-177
- function_definition (anonymous) @179-179
- function_definition operator++ @181-185
- function_definition (anonymous) @187-187
- function_definition operator-- @189-193
- function_definition (anonymous) @195-198
- function_definition (anonymous) @200-203
- function_definition (anonymous) @205-209
- function_definition (anonymous) @211-215
- function_definition operator-> @217-221
- function_definition operator== @224-226
- function_definition operator!= @228-230
- function_definition operator== @233-235
- function_definition operator!= @237-239
- function_definition operator== @241-241
- function_definition operator!= @242-242
- function_definition operator< @245-247
- function_definition operator<= @249-251
- function_definition operator> @254-256
- function_definition operator>= @258-260
- function_definition operator- @262-265
- function_definition RangedPtr @267-267

### mfbt/ReentrancyGuard.h

Blob: `2d7d0097fdfe0a88ca81e86d734ea6e58ce8100c`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @10
- include "mozilla/Assertions.h" @12
- class_specifier MOZ_RAII @18-18
- class_specifier T @24-24
- function_definition ReentrancyGuard @29-36
- function_definition ~ReentrancyGuard @38-38
- function_definition ~ReentrancyGuard @42-42
- function_definition ReentrancyGuard @45-45

### mfbt/RefCountType.h

Blob: `9cbcb46bf101a917e7c53904dd689507e71c2b0a`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @8

### mfbt/RefCounted.cpp

Blob: `f8174ff769d0ed67adf9298356d1dce6a3e577a6`. Grammar: cpp. Status: contains-errors.

- include "mozilla/RefCounted.h" @5
- function_definition SetLeakCheckingFunctions @15-31

### mfbt/RefCounted.h

Blob: `d9c265078284d584c5543942fcdb6b62f54754cd`. Grammar: cpp. Status: contains-errors.

- include <type_traits> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/Atomics.h" @13
- include "mozilla/Attributes.h" @14
- include "mozilla/RefCountType.h" @15
- class_specifier RefCountLogger @69-126
- function_definition logAddRef @75-87
- function_definition ReleaseLogger @98-125
- class_specifier MOZ_STACK_CLASS @98-98
- function_definition mPointer @99-107
- class_specifier T @100-100
- function_definition logRelease @109-119
- enum_specifier RefCountAtomicity @129-129
- class_specifier RC @132-152
- function_definition RC @134-134
- function_definition RC @136-136
- function_definition (anonymous) @137-137
- function_definition RC @138-138
- function_definition (anonymous) @139-139
- function_definition operator++ @141-141
- function_definition operator-- @142-142
- function_definition operator= @145-145
- function_definition (anonymous) @148-148
- class_specifier RC<T, AtomicRefCount> @155-214
- function_definition RC @157-157
- function_definition RC @159-159
- function_definition (anonymous) @160-160
- function_definition RC @161-161
- function_definition (anonymous) @162-162
- function_definition operator++ @164-174
- function_definition operator-- @176-176
- function_definition operator= @181-183
- function_definition (anonymous) @186-190
- function_definition IncrementIfNonzero @192-210
- class_specifier RefCounted @217-267
- function_definition RefCounted @219-219
- function_definition ~RefCounted @221-221
- function_definition AddRef @226-231
- function_definition Release @233-251
- function_definition ref @257-257
- function_definition deref @258-258
- function_definition refCount @259-259
- function_definition hasOneRef @260-263
- class_specifier RefCounted @289-295
- function_definition ~RefCounted @291-294
- class_specifier AtomicRefCounted @307-314
- function_definition ~AtomicRefCounted @310-313

### mfbt/RefPtr.h

Blob: `d70858b2655de040852b3794aea17d313d4d4451`. Grammar: cpp. Status: contains-errors.

- include <fmt/ostream.h> @8
- include <type_traits> @10
- include "mozilla/AlreadyAddRefed.h" @12
- include "mozilla/Assertions.h" @13
- include "mozilla/Attributes.h" @14
- include "mozilla/DbgMacro.h" @15
- class_specifier nsQueryReferent @21-21
- class_specifier nsCOMPtr_helper @22-22
- class_specifier nsISupports @23-23
- class_specifier MovingNotNull @27-27
- class_specifier NotNull @29-29
- class_specifier OwningNonNull @31-31
- class_specifier StaticLocalRefPtr @33-33
- class_specifier StaticRefPtr @35-35
- struct_specifier RefPtrTraits @47-50
- function_definition AddRef @48-48
- function_definition Release @49-49
- function_definition MOZ_NULL_AFTER_MOVE @55-60
- class_specifier MOZ_IS_REFPTR @55-55
- function_definition assign_assuming_AddRef @64-70
- function_definition ~RefPtr @78-82
- function_definition RefPtr @86-89
- function_definition RefPtr @91-98
- function_definition RefPtr @100-102
- function_definition mRawPtr @106-110
- function_definition mozilla_RefPtr_h @179-182
- function_definition mozilla_RefPtr_h @184-189
- function_definition (anonymous) @192-197
- function_definition mozilla_RefPtr_h @199-204
- function_definition (anonymous) @207-212
- function_definition (anonymous) @215-220
- function_definition (anonymous) @227-230
- function_definition (anonymous) @234-239
- function_definition (anonymous) @243-249
- function_definition swap @265-271
- function_definition swap @273-279
- function_definition forget @281-288
- function_definition forget @291-300
- function_definition forget @302-306
- function_definition get @308-315
- function_definition mozilla_RefPtr_h @317-328
- function_definition mozilla_RefPtr_h @338-338
- function_definition operator! @339-339
- function_definition MOZ_NO_ADDREF_RELEASE_ON_RETURN @341-345
- class_specifier Proxy @348-360
- function_definition Proxy @354-355
- function_definition operator() @357-359
- function_definition operator->* @363-367
- function_definition get_address @369-374
- function_definition get_address @376-381
- function_definition StartAssignment @390-393
- function_definition AddRef @408-408
- function_definition Release @409-409
- struct_specifier ConstRemovingRefPtrTraits<const U> @412-419
- function_definition AddRef @413-415
- function_definition Release @416-418
- class_specifier nsCycleCollectionTraversalCallback @422-422
- function_definition ImplCycleCollectionUnlink @428-430
- function_definition ImplCycleCollectionTraverse @433-437
- function_definition address_of @440-442
- function_definition address_of @445-447
- class_specifier RefPtrGetterAddRefs @450-485
- function_definition RefPtrGetterAddRefs @470-473
- function_definition (anonymous) @475-477
- function_definition (anonymous) @479-479
- function_definition (anonymous) @481-481
- function_definition getter_AddRefs @488-495
- function_definition operator== @500-502
- function_definition operator!= @505-507
- function_definition operator== @512-514
- function_definition operator== @517-519
- function_definition operator!= @522-524
- function_definition operator!= @527-529
- function_definition operator== @532-534
- function_definition operator== @537-539
- function_definition operator!= @542-544
- function_definition operator!= @547-549
- function_definition operator== @554-556
- function_definition operator== @559-561
- function_definition operator!= @564-566
- function_definition operator!= @569-571
- function_definition (anonymous) @576-578
- struct_specifier fmt::formatter<RefPtr<T>> @581-581
- function_definition do_AddRef @586-589
- function_definition do_AddRef @592-595
- function_definition MakeAndAddRef @608-611
- function_definition MakeRefPtr @621-624

### mfbt/Result.h

Blob: `013ad5aee9321520248a65adf6e336a105a6e281`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @10
- include <cstdint> @11
- include <cstring> @12
- include <type_traits> @13
- include "mozilla/Assertions.h" @15
- include "mozilla/Attributes.h" @16
- include "mozilla/CompactPair.h" @17
- include "mozilla/MaybeStorageBase.h" @18
- struct_specifier Ok @27-27
- struct_specifier ErrorPropagationTag @36-36
- class_specifier GenericErrorResult @39-39
- class_specifier Result @41-41
- enum_specifier PackingStrategy @45-51
- struct_specifier UnusedZero @54-54
- class_specifier ResultImplementation @57-57
- struct_specifier EmptyWrapper @60-67
- function_definition EmptyWrapper @61-61
- function_definition EmptyWrapper @62-62
- function_definition EmptyWrapper @63-63
- function_definition addr @65-65
- function_definition addr @66-66
- class_specifier ResultImplementationNullIsOkBase @80-156
- function_definition ResultImplementationNullIsOkBase @95-96
- function_definition ResultImplementationNullIsOkBase @97-98
- function_definition ResultImplementationNullIsOkBase @100-104
- function_definition ResultImplementationNullIsOkBase @105-109
- function_definition ResultImplementationNullIsOkBase @111-120
- function_definition (anonymous) @121-135
- function_definition isOk @137-137
- function_definition (anonymous) @139-139
- function_definition unwrap @140-140
- function_definition updateAfterTracing @141-147
- function_definition inspectErr @149-151
- function_definition unwrapErr @152-152
- function_definition updateErrorAfterTracing @153-155
- class_specifier ResultImplementationNullIsOk @160-160
- class_specifier ResultImplementationNullIsOk<V, E, true> @163-168
- class_specifier ResultImplementationNullIsOk<V, E, false> @171-186
- function_definition ResultImplementationNullIsOk @177-177
- function_definition (anonymous) @178-179
- function_definition ~ResultImplementationNullIsOk @181-185
- class_specifier ResultImplementation<V, E, PackingStrategy::ZeroIsEmptyError> @193-222
- function_definition ResultImplementation @203-203
- function_definition ResultImplementation @204-204
- function_definition isOk @206-206
- function_definition inspect @208-208
- function_definition unwrap @209-209
- function_definition inspectErr @211-211
- function_definition unwrapErr @212-212
- function_definition updateAfterTracing @214-217
- function_definition updateErrorAfterTracing @218-221
- class_specifier ResultImplementation<V, E, PackingStrategy::NullIsOk> @230-235
- class_specifier ResultImplementation<V, E, PackingStrategy::LowBitTagIsError> @250-317
- function_definition ResultImplementation @274-281
- function_definition ResultImplementation @282-290
- function_definition isOk @292-292
- function_definition inspect @294-298
- function_definition unwrap @299-299
- function_definition inspectErr @301-306
- function_definition unwrapErr @307-307
- function_definition updateAfterTracing @309-312
- function_definition updateErrorAfterTracing @313-316
- struct_specifier IsPackableVariant @321-343
- struct_specifier VEbool @322-329
- function_definition VEbool @323-323
- function_definition VEbool @324-325
- struct_specifier EVbool @330-337
- function_definition EVbool @331-331
- function_definition EVbool @332-333
- class_specifier ResultImplementation<V, E, PackingStrategy::PackedVariant> @350-379
- function_definition ResultImplementation @357-357
- function_definition ResultImplementation @358-359
- function_definition isOk @361-361
- function_definition (anonymous) @363-363
- function_definition unwrap @364-364
- function_definition (anonymous) @366-366
- function_definition unwrapErr @367-367
- function_definition updateAfterTracing @369-373
- function_definition updateErrorAfterTracing @374-378
- struct_specifier UnusedZero @386-388
- struct_specifier UnusedZeroEnum @401-416
- function_definition Inspect @407-409
- function_definition Unwrap @410-412
- function_definition Store @413-415
- struct_specifier HasFreeLSB @423-425
- struct_specifier HasFreeLSB<void*> @429-431
- struct_specifier HasFreeLSB<T*> @437-439
- struct_specifier SelectResultImpl @444-458
- struct_specifier IsResult @461-461
- struct_specifier IsResult<Result<V, E>> @464-464
- function_definition ToResult @469-472
- function_definition Result @538-540
- function_definition Result @543-545
- function_definition Result @549-552
- function_definition Result @555-557
- function_definition Result @558-560
- function_definition (anonymous) @569-582
- function_definition Result @595-595
- function_definition Result @596-596
- function_definition isOk @601-601
- function_definition isErr @604-604
- function_definition unwrap @608-611
- function_definition unwrapOr @617-619
- function_definition unwrapErr @622-625
- function_definition updateAfterTracing @629-631
- function_definition updateErrorAfterTracing @635-637
- function_definition inspect @640-647
- function_definition inspectErr @650-658
- function_definition propagateErr @670-673
- function_definition map @704-707
- function_definition mapErr @737-741
- function_definition orElse @799-801
- function_definition andThen @833-835
- function_definition operator== @837-840
- function_definition operator!= @842-844
- class_specifier GenericErrorResult @854-872
- function_definition GenericErrorResult @861-862
- function_definition GenericErrorResult @864-865
- function_definition GenericErrorResult @867-868
- function_definition GenericErrorResult @870-871
- function_definition Err @875-877

### mfbt/ResultExtensions.h

Blob: `c7c25438880ba5756282cdc2be877d8978f071c6`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Assertions.h" @11
- include "mozilla/dom/quota/RemoveParen.h" @12
- include "nscore.h" @13
- include "prtypes.h" @14
- struct_specifier ErrorPropagationTag @18-18
- class_specifier GenericErrorResult<nsresult> @23-38
- function_definition GenericErrorResult @30-32
- function_definition GenericErrorResult @34-35
- function_definition (anonymous) @37-37
- include "mozilla/Result.h" @46
- struct_specifier ResultTypeTraits @51-51
- struct_specifier ResultTypeTraits<nsresult> @54-56
- function_definition From @55-55
- function_definition ToResult @59-64
- function_definition ToResult @67-72
- function_definition ResultRefAsParam @76-78
- function_definition ToResultInvokeInternal @82-99
- struct_specifier outparam_as_pointer @102-102
- struct_specifier outparam_as_pointer<T*> @105-107
- struct_specifier outparam_as_reference @110-110
- struct_specifier outparam_as_reference<T*> @113-115
- function_definition ToResultInvokeSelector @135-140
- function_definition ToResultInvokeSelector @143-148
- function_definition ToResultInvoke @170-173
- struct_specifier tag @177-179
- struct_specifier select_last @182-184
- struct_specifier select_last<> @190-192
- function_definition ToResultInvokeMemberInternal @196-210
- function_definition ToResultInvokeMember @231-236
- function_definition ToResultInvokeMember @241-246
- function_definition ToResultInvokeMember @250-253
- function_definition ToResultInvokeMember @257-261
- function_definition ToResultInvokeMember @267-270
- function_definition ToResultInvokeMember @276-280
- function_definition ToResultInvokeMember @286-291
- function_definition ToResultInvokeMember @296-302
- function_definition ToResultInvokeMember @306-310
- function_definition ToResultInvokeMember @314-318
- function_definition ToResultInvokeMember @324-328
- function_definition ToResultInvokeMember @334-338

### mfbt/ResultVariant.h

Blob: `c3d25084d31398b3ff808be10774b22adf049751`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Result.h" @10
- include "mozilla/Variant.h" @11
- class_specifier ResultImplementation<V, E, PackingStrategy::Variant> @16-54
- function_definition ResultImplementation @22-22
- function_definition ResultImplementation @23-23
- function_definition (anonymous) @24-24
- function_definition (anonymous) @25-25
- function_definition ResultImplementation @27-27
- function_definition ResultImplementation @28-28
- function_definition ResultImplementation @30-31
- function_definition ResultImplementation @33-33
- function_definition ResultImplementation @34-35
- function_definition isOk @37-37
- function_definition unwrap @42-42
- function_definition (anonymous) @43-43
- function_definition unwrapErr @45-45
- function_definition (anonymous) @46-46
- function_definition updateAfterTracing @48-50
- function_definition updateErrorAfterTracing @51-53

### mfbt/ReverseIterator.h

Blob: `4cc35a49673e9690c899d3fa5fa50d99183d328f`. Grammar: cpp. Status: syntax-clean.

- include <utility> @12
- class_specifier ReverseIterator @21-88
- function_definition ReverseIterator @29-29
- function_definition operator* @34-37
- function_definition operator- @40-42
- function_definition (anonymous) @46-49
- function_definition (anonymous) @50-53
- function_definition operator++ @54-58
- function_definition operator-- @59-63
- function_definition operator== @91-94
- function_definition operator!= @97-100
- function_definition operator< @103-106
- function_definition operator<= @109-112
- function_definition operator> @115-118
- function_definition operator>= @121-124
- class_specifier IteratorRange @130-151
- function_definition IteratorRange @137-138
- function_definition begin @140-140
- function_definition cbegin @141-141
- function_definition end @142-142
- function_definition cend @143-143
- function_definition rbegin @144-144
- function_definition crbegin @145-145
- function_definition rend @146-146
- function_definition crend @147-147
- function_definition Reversed @156-159
- function_definition Reversed @162-165

### mfbt/RollingMean.h

Blob: `20c4df0b8f48c4279de7950b734b1ebbbc60c093`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @10
- include <type_traits> @12
- include "mozilla/Assertions.h" @14
- include "mozilla/Vector.h" @15
- class_specifier RollingMean @29-88
- function_definition RollingMean @41-44
- function_definition (anonymous) @46-46
- function_definition insert @51-66
- function_definition mean @71-74
- function_definition empty @76-76
- function_definition clear @81-85
- function_definition maxValues @87-87

### mfbt/SEH.h

Blob: `170eb095ee7c6c2ae2be79d4d1b72fc05d19ec79`. Grammar: cpp. Status: syntax-clean.


### mfbt/SHA1.cpp

Blob: `b6e6472093e1d3f9caa95daeb7b088c8d30dde21`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/SHA1.h" @5
- include <string.h> @7
- include "mozilla/Assertions.h" @9
- include "mozilla/EndianUtils.h" @10
- function_definition SHA_ROTL @15-18
- function_definition SHA1Sum @29-36
- function_definition update @77-116
- function_definition finish @121-150
- function_definition shaCompress @199-404

### mfbt/SHA1.h

Blob: `fca7998260adc4df9a4d7ed150502376765144cf`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @10
- include <stdint.h> @11
- include "mozilla/Types.h" @13
- class_specifier SHA1Sum @35-55

### mfbt/SPSCQueue.h

Blob: `2493aa3feafe3ac9f54576d45dbe1158255daee2`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @10
- include <atomic> @11
- include <cstddef> @12
- include <limits> @13
- include <memory> @14
- include <type_traits> @15
- include "mozilla/Assertions.h" @17
- include "mozilla/PodOperations.h" @18
- include <thread> @20
- struct_specifier MemoryOperations @27-40
- struct_specifier MemoryOperations<T, true> @43-50
- function_definition ConstructDefault @44-46
- function_definition MoveOrCopy @47-49
- struct_specifier MemoryOperations<T, false> @53-62
- function_definition ConstructDefault @54-58
- function_definition MoveOrCopy @59-61
- class_specifier SPSCRingBufferBase @94-408
- function_definition SPSCRingBufferBase @104-115
- function_definition EnqueueDefault @124-126
- function_definition Enqueue @136-136
- function_definition Enqueue @148-182
- function_definition Dequeue @194-221
- function_definition AvailableRead @232-235
- function_definition AvailableWrite @246-249
- function_definition Capacity @257-257
- function_definition ResetConsumerThreadId @265-274
- function_definition ResetProducerThreadId @282-291
- function_definition IsEmpty @302-304
- function_definition IsFull @316-318
- function_definition StorageCapacity @327-327
- function_definition AvailableReadInternal @336-342
- function_definition AvailableWriteInternal @351-359
- function_definition IncrementIndex @370-374
- function_definition AssertCorrectThread @385-391

### mfbt/Saturate.h

Blob: `c2bbd79f495764aeae232bf98bfc4f4407f9af58`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @10
- include <limits> @12
- include <type_traits> @13
- include <utility> @14
- include "mozilla/Attributes.h" @16
- include "mozilla/CheckedArithmetic.h" @17
- class_specifier SaturateOp @39-106
- function_definition SaturateOp @41-47
- function_definition SaturateOp @48-48
- function_definition SaturateOp @49-49
- function_definition (anonymous) @50-50
- function_definition (anonymous) @51-51
- function_definition operator+ @55-55
- function_definition operator- @57-57
- function_definition (anonymous) @60-67
- function_definition (anonymous) @69-76
- function_definition (anonymous) @80-83
- function_definition operator++ @85-90
- function_definition (anonymous) @92-95
- function_definition operator-- @97-102
- class_specifier Saturate @113-212
- function_definition Saturate @115-115
- function_definition Saturate @116-116
- function_definition Saturate @118-120
- function_definition Saturate @122-122
- function_definition (anonymous) @124-124
- function_definition operator== @128-128
- function_definition operator== @130-130
- function_definition operator!= @131-131
- function_definition (anonymous) @135-135
- function_definition (anonymous) @137-140
- function_definition operator+ @144-147
- function_definition operator+ @149-152
- function_definition operator- @154-157
- function_definition operator- @159-162
- function_definition (anonymous) @166-169
- function_definition (anonymous) @171-174
- function_definition (anonymous) @176-179
- function_definition (anonymous) @181-184
- function_definition (anonymous) @188-192
- function_definition operator++ @194-197
- function_definition (anonymous) @199-203
- function_definition operator-- @205-208
- function_definition operator== @230-232
- function_definition operator!= @235-237

### mfbt/ScopeExit.h

Blob: `c12150b76fb027fa9689a915d8063469969dff41`. Grammar: cpp. Status: contains-errors.

- include <utility> @81
- include "mozilla/Attributes.h" @83
- function_definition ScopeExit @88-113
- class_specifier MOZ_STACK_CLASS @88-88
- function_definition ScopeExit @96-100
- function_definition ~ScopeExit @102-106
- function_definition release @108-108
- function_definition ScopeExit @110-110
- function_definition MakeScopeExit @117-120

### mfbt/SegmentedVector.h

Blob: `a81dd3a849e2db73dd756211c74d03f4a809640a`. Grammar: cpp. Status: contains-errors.

- include <new> @21
- include <utility> @22
- include "mozilla/AllocPolicy.h" @24
- include "mozilla/Attributes.h" @25
- include "mozilla/LinkedList.h" @26
- include "mozilla/MemoryReporting.h" @27
- include "mozilla/OperatorNewExtensions.h" @28
- include "mozilla/Likely.h" @31
- include "mozilla/mozalloc_oom.h" @32
- class_specifier SegmentedVector @55-350
- struct_specifier SegmentImpl @57-107
- function_definition RawData @68-68
- function_definition SegmentImpl @71-71
- function_definition ~SegmentImpl @73-77
- function_definition Length @79-79
- function_definition Elems @81-81
- function_definition (anonymous) @83-86
- function_definition (anonymous) @88-91
- function_definition Append @94-100
- function_definition PopLast @102-106
- function_definition SegmentedVector @125-133
- function_definition SegmentedVector @135-136
- function_definition (anonymous) @137-143
- function_definition ~SegmentedVector @145-145
- function_definition IsEmpty @147-147
- function_definition Length @151-158
- function_definition Append @163-175
- function_definition InfallibleAppend @180-190
- function_definition Clear @192-198
- function_definition (anonymous) @200-204
- function_definition (anonymous) @206-210
- function_definition PopLast @212-221
- function_definition PopLastN @225-267
- class_specifier IterImpl @280-330
- function_definition IterImpl @286-291
- function_definition Done @294-298
- function_definition (anonymous) @300-303
- function_definition (anonymous) @305-308
- function_definition Next @310-317
- function_definition Prev @319-329
- function_definition Iter @332-332
- function_definition IterFromLast @333-333
- function_definition SizeOfExcludingThis @339-341
- function_definition SizeOfIncludingThis @344-346

### mfbt/SharedLibrary.h

Blob: `fa6a703914d46813fb45ced4aed764462946f1cc`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Char16.h" @12
- include "prlink.h" @13
- function_definition LoadLibraryWithFlags @27-39

### mfbt/SmallPointerArray.h

Blob: `a949f167f041cfec19d143ec5b8b797b5ec3367a`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @10
- include <cstddef> @11
- include <new> @12
- include <vector> @13
- include "mozilla/Assertions.h" @15
- include "mozilla/PodOperations.h" @16
- class_specifier SmallPointerArray @36-270
- function_definition SmallPointerArray @44-49
- function_definition ~SmallPointerArray @51-55
- function_definition SmallPointerArray @57-61
- function_definition (anonymous) @63-66
- function_definition Clear @68-77
- function_definition AppendElement @79-110
- function_definition RemoveElement @112-148
- function_definition Contains @150-165
- function_definition Length @167-177
- function_definition IsEmpty @179-179
- function_definition ElementAt @181-190
- function_definition operator[] @192-192
- function_definition begin @198-198
- function_definition begin @199-199
- function_definition cbegin @200-200
- function_definition end @201-201
- function_definition end @202-202
- function_definition cend @203-203
- function_definition beginInternal @206-224
- function_definition (anonymous) @228-228
- function_definition (anonymous) @230-233
- function_definition maybeVector @235-240

### mfbt/Span.h

Blob: `560deaa8641f73b070f98df975c0c63b1535d857`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @25
- include <array> @26
- include <cstddef> @27
- include <cstdint> @28
- include <iterator> @29
- include <limits> @30
- include <string> @31
- include <type_traits> @32
- include <utility> @33
- include "mozilla/Assertions.h" @35
- include "mozilla/Attributes.h" @36
- include "mozilla/Casting.h" @37
- include "mozilla/UniquePtr.h" @38
- class_specifier Array @43-43
- class_specifier EnumeratedArray @46-46
- function_definition narrow_cast @52-54
- class_specifier Span @66-66
- struct_specifier is_span_oracle @72-72
- struct_specifier is_span_oracle<mozilla::Span<ElementType, Extent>> @75-75
- struct_specifier is_span @78-78
- struct_specifier is_std_array_oracle @81-81
- struct_specifier is_std_array_oracle<std::array<ElementType, Extent>> @84-84
- struct_specifier is_std_array @87-87
- struct_specifier is_allowed_extent_conversion @90-93
- struct_specifier is_allowed_element_type_conversion @96-98
- struct_specifier SpanKnownBounds @100-100
- class_specifier span_iterator @103-250
- function_definition span_iterator @118-118
- function_definition span_iterator @120-124
- function_definition span_iterator @131-133
- function_definition (anonymous) @143-144
- function_definition operator* @146-149
- function_definition operator-> @151-154
- function_definition (anonymous) @156-159
- function_definition operator++ @161-165
- function_definition (anonymous) @167-170
- function_definition operator-- @172-176
- function_definition operator+ @178-181
- function_definition (anonymous) @183-188
- function_definition operator- @190-193
- function_definition (anonymous) @195-195
- function_definition operator- @197-200
- function_definition operator[] @202-204
- function_definition operator== @206-214
- function_definition operator!= @216-219
- function_definition operator< @221-225
- function_definition operator<= @227-230
- function_definition operator> @232-235
- function_definition operator>= @237-240
- function_definition swap @242-245
- function_definition operator+ @253-257
- class_specifier extent_type @260-281
- function_definition extent_type @266-266
- function_definition extent_type @269-274
- function_definition extent_type @276-278
- function_definition size @280-280
- class_specifier extent_type<dynamic_extent> @284-297
- function_definition extent_type @289-289
- function_definition extent_type @291-291
- function_definition size @293-293
- function_definition Span @369-883
- class_specifier MOZ_GSL_POINTER @369-369
- function_definition Span @400-400
- function_definition Span @405-405
- function_definition Span @410-411
- function_definition Span @416-418
- function_definition Span @424-429
- function_definition Span @435-439
- function_definition Span @463-463
- function_definition Span @525-528
- function_definition Span @598-598
- function_definition Span @603-603
- function_definition ~Span @631-631
- function_definition First @641-644
- function_definition Last @650-654
- function_definition Subspan @660-665
- function_definition First @670-673
- function_definition Last @678-682
- function_definition Subspan @687-694
- function_definition From @699-701
- function_definition To @706-708
- function_definition subspan @711-714
- function_definition from @716-716
- function_definition to @718-718
- function_definition FromTo @724-728
- function_definition Length @734-734
- function_definition size @739-739
- function_definition LengthBytes @744-744
- function_definition size_bytes @749-751
- function_definition IsEmpty @756-756
- function_definition empty @762-762
- function_definition operator[] @765-768
- function_definition at @773-773
- function_definition operator() @775-777
- function_definition Elements @784-784
- function_definition data @791-791
- function_definition begin @794-796
- function_definition end @797-799
- function_definition cbegin @801-803
- function_definition cend @804-806
- function_definition rbegin @808-808
- function_definition rend @809-809
- function_definition crbegin @811-813
- function_definition crend @814-816
- function_definition SplitAt @819-825
- function_definition SplitAt @827-832
- function_definition AsConst @834-836
- function_definition IndexOf @840-848
- function_definition Contains @852-854
- function_definition ExtentType @856-880
- class_specifier ExtentType @860-860
- class_specifier OtherExtentType @863-863
- function_definition data @876-876
- function_definition operator== @913-917
- function_definition operator!= @920-923
- function_definition operator< @926-930
- function_definition operator<= @933-936
- function_definition operator> @939-942
- function_definition operator>= @945-948
- struct_specifier calculate_byte_size @957-961
- struct_specifier calculate_byte_size<ElementType, dynamic_extent> @964-965
- function_definition AsBytes @973-977
- function_definition AsWritableBytes @984-987
- function_definition AsChars @992-994
- function_definition AsWritableChars @999-1001
- function_definition MakeStringSpan @1007-1013
- function_definition MakeStringSpan @1019-1025

### mfbt/SplayTree.h

Blob: `1f1662d5b6767bc8a82fa7794f7f0c27ef97d079`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Assertions.h" @13
- class_specifier SplayTree @18-18
- class_specifier SplayTreeNode @21-32
- function_definition SplayTreeNode @26-26
- class_specifier SplayTree @45-280
- function_definition SplayTree @49-49
- function_definition SplayTree @51-51
- function_definition operator= @52-52
- function_definition empty @54-54
- function_definition find @56-64
- function_definition insert @66-77
- function_definition remove @81-139
- function_definition removeMin @141-149
- function_definition checkCoherency @152-152
- function_definition lookup @159-176
- function_definition finishInsertion @178-187
- function_definition splay @194-216
- function_definition rotate @218-253
- function_definition checkCoherency @255-279
- function_definition findOrInsert @283-298

### mfbt/StaticAnalysisFunctions.h

Blob: `0e11a84b3c388e6a92bce593a7c787b9deb09f37`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @17
- include "mozilla/Attributes.h" @21
- function_definition MOZ_KnownLive @34-36
- function_definition (anonymous) @42-44
- function_definition MOZ_AssertAssignmentTest @55-58

### mfbt/StringBuffer.h

Blob: `dd4aff5333ebdebba1c28c40dcfa2a24f39f69e8`. Grammar: cpp. Status: contains-errors.

- include <atomic> @8
- include <cstring> @9
- include "mozilla/AlreadyAddRefed.h" @11
- include "mozilla/Assertions.h" @12
- include "mozilla/CheckedInt.h" @13
- include "mozilla/Maybe.h" @14
- include "mozilla/MemoryReporting.h" @15
- include "mozilla/RefCounted.h" @16
- include "mozmemory.h" @17
- class_specifier StringBuffer @30-311
- function_definition Alloc @55-68
- function_definition ConstructInPlace @81-90
- function_definition IsValidLength @97-101
- function_definition Create @109-112
- function_definition Create @113-116
- function_definition Create @117-120
- function_definition Realloc @133-161
- function_definition AddRef @163-174
- function_definition Release @176-191
- function_definition FromData @198-200
- function_definition Data @205-207
- function_definition StorageSize @214-214
- function_definition AllocationSize @220-222
- function_definition IsReadonly @232-262
- function_definition HasMultipleReferences @267-267
- function_definition RefCount @274-276
- function_definition SizeOfIncludingThisIfUnshared @282-284
- function_definition SizeOfIncludingThisEvenIfShared @295-297
- function_definition DoCreate @301-310

### mfbt/TaggedAnonymousMemory.cpp

Blob: `d4af84c0f0244021c90875073a4c4f333147b4bb`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/TaggedAnonymousMemory.h" @7
- include <stdint.h> @9
- include <sys/mman.h> @10
- include <sys/prctl.h> @11
- include <sys/syscall.h> @12
- include <sys/types.h> @13
- include <unistd.h> @14
- include "mozilla/Assertions.h" @16
- function_definition TagAnonymousMemoryAligned @31-36
- function_definition GetPageMask @41-51
- function_definition MozTagAnonymousMemory @55-69
- function_definition MozTaggedAnonymousMmap @71-80

### mfbt/TaggedAnonymousMemory.h

Blob: `4b684efb6b66c14cc99672234a2fc6b6c1a273b1`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @35
- include <sys/mman.h> @37
- include <sys/types.h> @38
- include "mozilla/Types.h" @41
- function_definition MozTagAnonymousMemory @62-63
- function_definition MozTaggedAnonymousMmap @65-74

### mfbt/Tainting.h

Blob: `f3c67af62b4c325ba11dc3ec4d038027ec587b10`. Grammar: cpp. Status: syntax-clean.

- include <utility> @12
- include "mozilla/MacroArgs.h" @14
- struct_specifier ParamTraits @18-18
- class_specifier Tainted @24-24
- class_specifier Tainted @55-70
- function_definition Tainted @60-60
- function_definition Tainted @64-64
- function_definition (anonymous) @66-66
- function_definition (anonymous) @67-67

### mfbt/TextUtils.h

Blob: `7c7234093a9ff5ba57dcee3392d1a31647c4969d`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @10
- include "mozilla/Assertions.h" @12
- include "mozilla/Latin1.h" @13
- include "mozilla/Span.h" @14
- function_definition IsAscii @35-35
- function_definition IsAscii @38-40
- function_definition IsAscii @43-45
- function_definition IsAscii @48-50
- function_definition IsAscii @53-53
- function_definition IsAscii @56-56
- function_definition IsAscii @64-87
- function_definition IsAscii @95-120
- function_definition IsAsciiNullTerminated @127-134
- function_definition AsciiValidUpTo @141-144
- function_definition Utf16ValidUpTo @150-152
- function_definition EnsureUtf16ValiditySpan @161-163
- function_definition ConvertAsciitoUtf16 @171-175
- function_definition IsAsciiWhitespace @186-190
- function_definition IsAsciiLowercaseAlpha @199-203
- function_definition IsAsciiUppercaseAlpha @212-216
- function_definition IsAsciiAlpha @225-227
- function_definition IsAsciiDigit @236-240
- function_definition IsAsciiHexDigit @248-253
- function_definition IsAsciiAlphanumeric @262-264
- function_definition AsciiAlphanumericToNumber @271-286

### mfbt/ThreadLocal.h

Blob: `0671adb9b40b0d7b2938034a1fc3580a70ecc5e3`. Grammar: cpp. Status: syntax-clean.

- include <pthread.h> @11
- include <cstdint> @14
- include <type_traits> @15
- include "mozilla/Assertions.h" @17
- struct_specifier Helper @76-78
- struct_specifier Helper<S*> @81-83
- class_specifier ThreadLocalKeyStorage @98-119
- function_definition ThreadLocalKeyStorage @100-100
- function_definition initialized @102-102
- function_definition init @104-104
- function_definition get @106-109
- function_definition set @111-115
- class_specifier ThreadLocalKeyStorage @124-142
- function_definition ThreadLocalKeyStorage @126-126
- function_definition initialized @128-128
- function_definition init @130-130
- function_definition get @132-132
- function_definition set @134-137
- class_specifier ThreadLocalKeyStorage @145-167
- function_definition ThreadLocalKeyStorage @147-147
- function_definition initialized @149-149
- function_definition init @151-151
- function_definition get @153-156
- function_definition set @158-162
- class_specifier ThreadLocalNativeStorage @171-188
- function_definition initialized @175-175
- function_definition init @177-177
- function_definition get @179-179
- function_definition set @181-184
- class_specifier ThreadLocal @191-204
- function_definition infallibleInit @195-197
- function_definition init @207-219
- function_definition get @222-225
- function_definition set @228-234

### mfbt/ThreadSafeWeakPtr.h

Blob: `38dea893ac1df8b2894b315220620a2842093db4`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Assertions.h" @56
- include "mozilla/HashFunctions.h" @57
- include "mozilla/RefCountType.h" @58
- include "mozilla/RefCounted.h" @59
- include "mozilla/RefPtr.h" @60
- class_specifier ThreadSafeWeakPtr @65-65
- class_specifier SupportsThreadSafeWeakPtr @68-68
- class_specifier SupportsThreadSafeWeakPtrBase @72-72
- class_specifier ThreadSafeWeakReference @77-104
- function_definition ThreadSafeWeakReference @80-81
- function_definition typeName @84-84
- function_definition typeSize @85-85
- class_specifier SupportsThreadSafeWeakPtr @140-200
- function_definition SupportsThreadSafeWeakPtr @147-150
- function_definition AddRef @154-160
- function_definition Release @162-181
- function_definition ref @186-186
- function_definition deref @187-187
- function_definition refCount @188-188
- function_definition hasOneRef @189-189
- function_definition getThreadSafeWeakReference @195-197
- class_specifier ThreadSafeWeakPtr @204-297
- function_definition ThreadSafeWeakPtr @208-208
- function_definition (anonymous) @210-210
- function_definition ThreadSafeWeakPtr @211-211
- function_definition (anonymous) @213-213
- function_definition ThreadSafeWeakPtr @214-214
- function_definition ThreadSafeWeakPtr @220-221
- function_definition (anonymous) @223-226
- function_definition (anonymous) @228-231
- function_definition ThreadSafeWeakPtr @233-233
- function_definition IsNull @239-239
- function_definition IsDead @245-245
- function_definition operator== @247-247
- function_definition operator== @249-251
- function_definition operator== @253-256
- function_definition operator== @258-263
- function_definition operator!= @266-268
- function_definition Hash @270-270
- function_definition (anonymous) @273-273
- function_definition getRefPtr @277-291
- function_definition do_AddRef @302-306

### mfbt/ThreadSafety.h

Blob: `3e051ff1dd5473bea300b74764b1803d15fb94c4`. Grammar: cpp. Status: syntax-clean.


### mfbt/TiedFields.h

Blob: `fa3a834e2889d6bf5e75ff5681365b681aa0eb9a`. Grammar: cpp. Status: syntax-clean.

- include <array> @8
- include <cstddef> @9
- include <tuple> @10
- function_definition TiedFields @25-27
- function_definition TiedFields @30-36
- struct_specifier SizeofTupleArgs @39-39
- struct_specifier SizeofTupleArgs<std::tuple<Args...>> @44-45
- function_definition AreAllBytesTiedFields @63-68
- struct_specifier FieldDebugInfoT @76-80
- function_definition IsTightlyPacked @77-79
- struct_specifier TightlyPackedFieldEndOffsetT @83-108
- function_definition Fn @88-107
- struct_specifier TightlyPackedFieldEndOffsetT<StructT, TupleOfFields, 0> @111-116
- function_definition Fn @112-115
- struct_specifier TightlyPackedFieldEndOffsetT<StructT, TupleOfFields, size_t(-1)> @118-124
- function_definition Fn @119-123
- function_definition AssertTiedFieldsAreExhaustive @127-139
- struct_specifier PaddingField @151-166
- function_definition PaddingField @156-156
- function_definition operator== @158-160
- function_definition operator< @161-163
- function_definition MutTiedFields @165-165

### mfbt/ToString.h

Blob: `9579da2e4d692e8bc958e66bd6189f0235af958a`. Grammar: cpp. Status: syntax-clean.

- include <sstream> @10
- include <string> @11
- function_definition ToString @20-24

### mfbt/Try.h

Blob: `b135d51e291509f23e00a7e65bfc344e1dbc8588`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Likely.h" @8
- include "mozilla/Result.h" @9

### mfbt/TypedEnumBits.h

Blob: `a5c3aa433be54a9c2dc1b785e00d6c0c3a0a56e8`. Grammar: cpp. Status: contains-errors.

- include "mozilla/IntegerTypeTraits.h" @12
- class_specifier CastableTypedEnumResult @41-56
- function_definition CastableTypedEnumResult @46-46
- function_definition (anonymous) @48-48
- function_definition (anonymous) @51-53
- function_definition operator! @55-55
- function_definition (anonymous) @89-91

### mfbt/Types.h

Blob: `cb64e3562bbd747a0d6b225144e69163cd312c6b`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @16

### mfbt/UniquePtr.h

Blob: `debd49752261ab5f98e585d04869d4850ceac8f5`. Grammar: cpp. Status: contains-errors.

- include <memory> @10
- include <utility> @11
- include "mozilla/Attributes.h" @13
- struct_specifier UniqueSelector @30-32
- struct_specifier UniqueSelector<T[]> @35-37
- struct_specifier UniqueSelector<T[N]> @40-42
- function_definition MakeUnique @101-103
- function_definition WrapUnique @119-121
- function_definition TempPtrToSetterT @181-197
- class_specifier MOZ_TEMPORARY_CLASS @181-181
- function_definition (anonymous) @190-190
- function_definition ~TempPtrToSetterT @192-196
- function_definition TempPtrToSetter @202-204
- function_definition operator== @213-215
- function_definition operator== @218-220
- function_definition operator!= @223-225
- function_definition operator!= @228-230

### mfbt/UniquePtrExtensions.cpp

Blob: `e0772fef1c3593d12d5660f710e633b52132b7d6`. Grammar: cpp. Status: syntax-clean.

- include "UniquePtrExtensions.h" @5
- include "mozilla/Assertions.h" @7
- include "mozilla/DebugOnly.h" @8
- include <windows.h> @11
- include <errno.h> @13
- include <fcntl.h> @14
- include <unistd.h> @15
- function_definition operator() @21-31
- function_definition SetCloseOnExec @36-46
- function_definition DuplicateFileHandle @50-72

### mfbt/UniquePtrExtensions.h

Blob: `0d66fda54ddacb759b97748c2ac21efcdc5c2121`. Grammar: cpp. Status: contains-errors.

- include <cstdlib> @10
- include <type_traits> @11
- include "mozilla/Attributes.h" @13
- include "mozilla/Types.h" @14
- include "mozilla/UniquePtr.h" @15
- include "mozilla/fallible.h" @16
- include <cstdint> @19
- include <mach/mach.h> @22
- include "mozilla/Assertions.h" @24
- include "mozilla/DebugOnly.h" @25
- include "mozilla/Assertions.h" @28
- function_definition MakeUniqueFallible @38-41
- function_definition MakeUniqueFallible @44-48
- function_definition MakeUniqueForOverwrite @61-63
- function_definition MakeUniqueForOverwrite @66-70
- function_definition MakeUniqueForOverwriteFallible @77-80
- function_definition MakeUniqueForOverwriteFallible @83-87
- struct_specifier FreePolicy @96-98
- function_definition operator() @97-97
- struct_specifier FileHandleHelper @110-164
- function_definition FileHandleHelper @111-115
- function_definition FileHandleHelper @117-117
- function_definition FileHandleHelper @119-120
- function_definition IsValid @122-134
- function_definition operator!= @136-136
- function_definition (anonymous) @138-138
- function_definition XP_WIN @144-146
- function_definition operator== @152-152
- struct_specifier FileHandleDeleter @166-170
- struct_specifier MachPortHelper @173-187
- function_definition MachPortHelper @174-174
- function_definition MachPortHelper @176-176
- function_definition MachPortHelper @178-178
- function_definition operator!= @180-180
- function_definition (anonymous) @182-182
- function_definition (anonymous) @183-183
- struct_specifier MachSendRightDeleter @189-197
- function_definition operator() @192-196
- struct_specifier MachReceiveRightDeleter @199-207
- function_definition operator() @202-206
- struct_specifier MachPortSetDeleter @209-217
- function_definition operator() @212-216
- function_definition DuplicateFileHandle @234-236
- function_definition SetCloseOnExec @242-244
- function_definition FileHandleIsValid @247-249
- function_definition FileHandleIsValid @250-252
- function_definition RetainMachSendRight @266-273
- struct_specifier PointerType @279-281
- struct_specifier PointerType<T, D,
                   std::void_t<typename std::remove_reference_t<D>::pointer>> @284-287
- struct_specifier ReceiverType @290-290
- struct_specifier ReceiverType<
    T, D, std::void_t<typename std::remove_reference_t<D>::receiver>> @293-296
- function_definition UniquePtrGetterTransfers @299-322
- class_specifier MOZ_TEMPORARY_CLASS @299-299
- function_definition UniquePtrGetterTransfers @304-305
- function_definition ~UniquePtrGetterTransfers @306-306
- function_definition (anonymous) @308-308
- function_definition (anonymous) @309-309
- function_definition (anonymous) @315-317
- function_definition getter_Transfers @333-335

### mfbt/UsingEnum.h

Blob: `d82cbc0bce73f52903c68b81a7ce09788c054576`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/MacroForEach.h" @8

### mfbt/Utf16.h

Blob: `75140f686f61ad96a8a19134e80711bf27ff9ae0`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/Assertions.h" @10
- include "mozilla/Likely.h" @11
- function_definition IsInBMP @28-28
- function_definition IsHighSurrogate @31-33
- function_definition IsLowSurrogate @36-38
- function_definition IsSurrogate @41-43
- function_definition IsSurrogatePair @46-48
- function_definition IsValidCodePoint @52-54
- function_definition HighSurrogate @57-62
- function_definition LowSurrogate @65-69
- function_definition SurrogateToUCS4 @72-77
- function_definition DecodeOneUtf16CodePoint @90-121

### mfbt/Utf8.cpp

Blob: `9b293047296ad9c9e1071ad3c0b01d48bdc82602`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Utf8.h" @7
- include <stddef.h> @9
- include "mozilla/HashFunctions.h" @11
- include "mozilla/Maybe.h" @12
- include "mozilla/TextUtils.h" @13
- include "mozilla/Types.h" @14
- include "mozilla/Utf16.h" @15
- function_definition IsValidUtf8 @20-42
- function_definition HashUTF8AsUTF16 @46-72

### mfbt/Utf8.h

Blob: `bf6f83b4025271f5033465c7eee946e68686e789`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Casting.h" @13
- include "mozilla/Likely.h" @14
- include "mozilla/Maybe.h" @15
- include "mozilla/Span.h" @16
- include "mozilla/TextUtils.h" @17
- include <limits.h> @19
- include <stddef.h> @20
- include <stdint.h> @21
- include "mozilla/Types.h" @23
- include <limits> @26
- function_definition Utf8Unit @166-166
- function_definition Utf8Unit @168-168
- function_definition Utf8Unit @170-175
- function_definition Utf8Unit @177-178
- function_definition operator== @180-182
- function_definition operator!= @184-186
- function_definition toChar @189-193
- function_definition toUnsignedChar @196-199
- function_definition toUint8 @202-205
- function_definition Utf8AsUnsignedChars @222-242
- function_definition IsAscii @245-247
- function_definition IsUtf8 @255-276
- function_definition Utf8ValidUpTo @286-289
- function_definition ConvertUtf16toUtf8 @299-303
- function_definition ConvertUtf16toUtf8Partial @324-331
- function_definition ConvertUtf8toUtf16 @345-349
- function_definition UnsafeConvertValidUtf8toUtf16 @359-363
- function_definition ConvertUtf8toUtf16WithoutReplacement @379-387
- function_definition IsTrailingUnit @395-397
- function_definition DecodeOneUtf8CodePointInline @432-507
- function_definition DecodeOneUtf8CodePoint @516-524
- function_definition DecodeOneUtf8CodePointInline @534-577
- function_definition DecodeOneUtf8CodePoint @584-588
- function_definition LossyDecodeOneUtf8CodePoint @595-614

### mfbt/Variant.h

Blob: `871b6b7b3c2520a2a1e6079205922b45daa5a924`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @10
- include <algorithm> @12
- include <new> @13
- include <type_traits> @14
- include <utility> @15
- include "mozilla/Assertions.h" @17
- include "mozilla/HashFunctions.h" @18
- include "mozilla/OperatorNewExtensions.h" @19
- struct_specifier ParamTraits @23-23
- class_specifier Variant @29-29
- struct_specifier type_pack_element @45-47
- struct_specifier NthImpl @55-55
- struct_specifier NthImpl<0, T, Ts...> @58-60
- struct_specifier NthImpl<N, T, Ts...> @63-65
- struct_specifier SelectVariantTypeHelper @73-73
- struct_specifier SelectVariantTypeHelper<T> @76-78
- struct_specifier SelectVariantTypeHelper<T, T, Variants...> @81-85
- struct_specifier SelectVariantTypeHelper<T, const T, Variants...> @88-92
- struct_specifier SelectVariantTypeHelper<T, const T&, Variants...> @95-99
- struct_specifier SelectVariantTypeHelper<T, T&&, Variants...> @102-106
- struct_specifier SelectVariantTypeHelper<T, Head, Variants...> @109-110
- struct_specifier SelectVariantType @121-123
- struct_specifier VariantTag @128-139
- struct_specifier TagHelper @147-147
- struct_specifier TagHelper<Tag, N, T, U, Next, false> @151-153
- function_definition tag @152-152
- struct_specifier TagHelper<Tag, N, T, U, Next, true> @157-159
- function_definition tag @158-158
- struct_specifier VariantImplementation @168-168
- struct_specifier VariantImplementation<Tag, N, T> @172-224
- function_definition tag @174-177
- function_definition copyConstruct @180-182
- function_definition moveConstruct @185-187
- function_definition destroy @190-192
- function_definition equal @195-197
- function_definition match @200-210
- function_definition matchN @213-223
- struct_specifier VariantImplementation<Tag, N, T, Ts...> @228-341
- function_definition tag @233-235
- function_definition copyConstruct @238-244
- function_definition moveConstruct @248-254
- function_definition destroy @257-263
- function_definition equal @266-273
- function_definition match @276-301
- function_definition matchN @304-340
- struct_specifier AsVariantTemporary @350-370
- function_definition AsVariantTemporary @353-353
- function_definition AsVariantTemporary @357-357
- function_definition AsVariantTemporary @359-360
- function_definition AsVariantTemporary @362-363
- function_definition AsVariantTemporary @365-365
- function_definition operator= @366-366
- function_definition operator= @367-367
- struct_specifier VariantType @376-378
- struct_specifier VariantIndex @382-384
- function_definition MOZ_NON_PARAM @599-934
- class_specifier MOZ_INHERIT_TYPE_ANNOTATIONS_FROM_TEMPLATE_ARGS @599-599
- function_definition ptr @620-620
- function_definition ptr @622-622
- function_definition Variant @633-638
- function_definition tag @647-650
- function_definition tag @660-663
- function_definition tag @671-679
- function_definition Variant @682-684
- function_definition Variant @687-689
- function_definition (anonymous) @692-697
- function_definition (anonymous) @700-705
- function_definition (anonymous) @709-716
- function_definition ~Variant @718-718
- function_definition (anonymous) @721-726
- function_definition (anonymous) @729-735
- function_definition is @739-744
- function_definition is @747-751
- function_definition operator== @757-759
- function_definition operator!= @766-766
- function_definition (anonymous) @772-778
- function_definition (anonymous) @781-786
- function_definition (anonymous) @790-795
- function_definition (anonymous) @798-803
- function_definition (anonymous) @807-813
- function_definition (anonymous) @816-821
- function_definition (anonymous) @825-830
- function_definition (anonymous) @833-838
- function_definition extract @847-853
- function_definition extract @856-861
- function_definition match @867-869
- function_definition match @872-875
- function_definition match @879-881
- function_definition match @884-887
- function_definition match @891-893
- function_definition match @896-899
- function_definition match @903-905
- function_definition match @908-911
- function_definition addTagToHash @918-920
- function_definition matchN @922-933
- function_definition AsVariant @950-952

### mfbt/Vector.h

Blob: `abb44b380b450b999646d309d1872fd7b5bc7fd1`. Grammar: cpp. Status: contains-errors.

- include <new> @10
- include <type_traits> @11
- include <utility> @12
- include "mozilla/AllocPolicy.h" @14
- include "mozilla/ArrayUtils.h" @15
- include "mozilla/Assertions.h" @16
- include "mozilla/Attributes.h" @17
- include "mozilla/CheckedArithmetic.h" @18
- include "mozilla/Likely.h" @19
- include "mozilla/MathAlgorithms.h" @20
- include "mozilla/MemoryReporting.h" @21
- include "mozilla/OperatorNewExtensions.h" @22
- include "mozilla/PodOperations.h" @23
- include "mozilla/ReentrancyGuard.h" @24
- include "mozilla/Span.h" @25
- class_specifier Vector @30-30
- function_definition CapacityHasExcessSpace @40-43
- function_definition GrowEltsByDoubling @65-121
- function_definition ComputeGrowth @125-127
- function_definition ComputeGrowth @132-140
- struct_specifier VectorImpl @147-235
- function_definition new_ @153-155
- function_definition destroy @158-163
- function_definition initialize @166-171
- function_definition copyConstruct @178-184
- function_definition moveConstruct @191-196
- function_definition copyConstructN @203-207
- function_definition growTo @215-234
- struct_specifier VectorImpl<T, N, AP, true> @243-311
- function_definition new_ @246-253
- function_definition destroy @255-255
- function_definition initialize @257-270
- function_definition copyConstruct @273-283
- function_definition moveConstruct @286-289
- function_definition copyConstructN @291-295
- function_definition growTo @297-310
- struct_specifier VectorTesting @315-315
- function_definition MOZ_GSL_OWNER @339-959
- class_specifier MOZ_NON_PARAM @339-339
- struct_specifier ComputeCapacity @376-379
- struct_specifier ComputeCapacity<0, Dummy> @382-384
- struct_specifier CapacityAndReserved @423-441
- function_definition CapacityAndReserved @424-431
- function_definition CapacityAndReserved @432-432
- struct_specifier CRAndStorage @451-463
- function_definition CRAndStorage @452-453
- function_definition CRAndStorage @454-454
- function_definition data @460-460
- function_definition storage @462-462
- struct_specifier CRAndStorage<0, Dummy> @466-479
- function_definition CRAndStorage @467-468
- function_definition CRAndStorage @469-469
- function_definition storage @471-478
- function_definition usingInlineStorage @494-496
- function_definition inlineStorage @498-498
- function_definition beginNoCheck @500-500
- function_definition endNoCheck @502-502
- function_definition endNoCheck @504-504
- function_definition reserved @514-518
- function_definition Vector @539-540
- function_definition Vector @546-546
- function_definition (anonymous) @551-551
- function_definition (anonymous) @553-553
- enum_specifier (anonymous) @555-555
- function_definition length @557-557
- function_definition empty @559-559
- function_definition capacity @561-561
- function_definition isStorageConsistent @574-576
- function_definition begin @579-582
- function_definition begin @584-587
- function_definition end @589-592
- function_definition end @594-597
- function_definition (anonymous) @599-605
- function_definition (anonymous) @607-613
- function_definition (anonymous) @615-621
- function_definition (anonymous) @623-629
- function_definition (anonymous) @631-635
- function_definition (anonymous) @637-637
- class_specifier Range @639-662
- function_definition Range @643-645
- function_definition empty @648-648
- function_definition remain @649-649
- function_definition (anonymous) @650-653
- function_definition popFront @654-657
- function_definition popCopyFront @658-661
- class_specifier ConstRange @664-687
- function_definition ConstRange @668-670
- function_definition empty @673-673
- function_definition remain @674-674
- function_definition (anonymous) @675-678
- function_definition popFront @679-682
- function_definition popCopyFront @683-686
- function_definition all @689-689
- function_definition all @690-690
- function_definition emplaceBack @790-794
- function_definition infallibleAppend @814-816
- function_definition infallibleAppendN @817-817
- function_definition infallibleAppend @819-821
- function_definition infallibleAppend @823-825
- function_definition infallibleEmplaceBack @827-830
- function_definition traceOwnedAllocs @954-958
- function_definition (anonymous) @1024-1029
- function_definition ~Vector @1032-1038
- function_definition reverse @1041-1049
- function_definition convertToHeapStorage @1057-1076
- function_definition growStorageBy @1079-1103
- function_definition initCapacity @1106-1122
- function_definition initLengthUninitialized @1125-1131
- function_definition maybeCheckSimulatedOOM @1134-1146
- function_definition reserve @1149-1166
- function_definition shrinkBy @1169-1174
- function_definition shrinkTo @1177-1180
- function_definition growBy @1183-1202
- function_definition growByUninitialized @1205-1221
- function_definition infallibleGrowByUninitialized @1224-1228
- function_definition resize @1231-1238
- function_definition resizeUninitialized @1241-1249
- function_definition clear @1252-1256
- function_definition clearAndFree @1259-1271
- function_definition shrinkStorageToFit @1274-1322
- function_definition canAppendWithoutRealloc @1325-1327
- function_definition internalAppendAll @1331-1334
- function_definition internalAppend @1338-1343
- function_definition appendN @1346-1362
- function_definition internalAppendN @1365-1371
- function_definition insert @1375-1396
- function_definition erase @1399-1407
- function_definition erase @1410-1418
- function_definition eraseIf @1422-1432
- function_definition eraseIfEqual @1436-1438
- function_definition internalEnsureCapacity @1441-1456
- function_definition append @1460-1469
- function_definition internalAppend @1473-1479
- function_definition moveAppend @1483-1491
- function_definition internalMoveAppend @1495-1501
- function_definition append @1505-1521
- function_definition appendAll @1525-1528
- function_definition appendAll @1532-1544
- function_definition append @1548-1551
- function_definition popBack @1554-1561
- function_definition popCopy @1564-1568
- function_definition extractRawBuffer @1571-1586
- function_definition extractOrCopyRawBuffer @1589-1610
- function_definition replaceRawBuffer @1613-1644
- function_definition replaceRawBuffer @1647-1649
- function_definition sizeOfExcludingThis @1652-1655
- function_definition sizeOfIncludingThis @1658-1661
- function_definition swap @1664-1686

### mfbt/WasiAtomic.h

Blob: `740a0f5c231d17cce88f73c6ce6c99033724d0c5`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @8
- include <atomic> @12
- include <cstdint> @15
- enum_specifier memory_order @21-28
- struct_specifier atomic @38-123
- function_definition atomic @42-42
- function_definition atomic @43-43
- function_definition atomic @45-45
- function_definition (anonymous) @46-46
- function_definition (anonymous) @47-47
- function_definition ~atomic @48-48
- function_definition load @50-52
- function_definition store @54-57
- function_definition operator= @59-59
- function_definition exchange @61-66
- function_definition compare_exchange_weak @68-72
- function_definition compare_exchange_weak @74-79
- function_definition compare_exchange_strong @81-85
- function_definition compare_exchange_strong @87-92
- function_definition fetch_add @94-98
- function_definition fetch_sub @100-104
- function_definition fetch_or @106-110
- function_definition fetch_xor @112-116
- function_definition fetch_and @118-122
- struct_specifier atomic<T*> @126-188
- function_definition atomic @132-132
- function_definition atomic @133-133
- function_definition atomic @134-134
- function_definition (anonymous) @135-135
- function_definition (anonymous) @136-136
- function_definition load @138-140
- function_definition store @142-145
- function_definition operator= @147-147
- function_definition exchange @149-154
- function_definition compare_exchange_weak @156-160
- function_definition compare_exchange_weak @162-167
- function_definition compare_exchange_strong @169-173
- function_definition fetch_add @175-180
- function_definition fetch_sub @182-187

### mfbt/WeakPtr.h

Blob: `6867a68db7b37970abf308cefc4389b179bcda9d`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Attributes.h" @74
- include "mozilla/RefCounted.h" @75
- include "mozilla/RefPtr.h" @76
- include <functional> @78
- include "mozilla/Assertions.h" @81
- include "nsISupportsImpl.h" @83
- include "nsProxyRelease.h" @85
- include "mozilla/Maybe.h" @91
- enum_specifier WeakPtrDestructorBehavior @157-162
- class_specifier WeakPtr @168-168
- class_specifier SupportsWeakPtr @169-169
- class_specifier WeakReference @175-206
- function_definition WeakReference @177-180
- function_definition get @182-185
- function_definition typeName @188-188
- function_definition typeSize @189-189
- function_definition AssertThreadSafety @193-193
- function_definition detach @199-202
- class_specifier SupportsWeakPtr @210-237
- function_definition ~SupportsWeakPtr @214-214
- function_definition DetachWeakPtr @217-221
- function_definition SelfReferencingWeakReference @224-231
- class_specifier WeakPtr @240-333
- function_definition (anonymous) @244-253
- function_definition WeakPtr @255-258
- function_definition (anonymous) @260-266
- function_definition (anonymous) @268-279
- function_definition WeakPtr @281-289
- function_definition WeakPtr @291-291
- function_definition WeakPtr @293-293
- function_definition (anonymous) @295-295
- function_definition get @296-296
- function_definition (anonymous) @297-297
- function_definition (anonymous) @298-298
- function_definition MOZ_NO_ADDREF_RELEASE_ON_RETURN @299-299
- struct_specifier StableOrdering @306-313
- function_definition Equals @307-309
- function_definition LessThan @310-312
- function_definition ~WeakPtr @316-324
- function_definition WeakPtr @330-330

### mfbt/WindowsVersion.h

Blob: `28c5e782c4b6bc0cbe8686e5da84c7e81ddfdde6`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @8
- include <windows.h> @9
- include "mozilla/Atomics.h" @11
- include "mozilla/Attributes.h" @12
- function_definition IsWindows10BuildOrLater @16-51
- function_definition IsWin10AnniversaryUpdateOrLater @53-55
- function_definition IsWin10CreatorsUpdateOrLater @57-59
- function_definition IsWin10FallCreatorsUpdateOrLater @61-63
- function_definition IsWin10Sep2018UpdateOrLater @65-67
- function_definition IsWin11OrLater @69-71
- function_definition IsWin1122H2OrLater @73-75

### mfbt/WrappingOperations.h

Blob: `2205864e23878e5856fbc9885a65df663084fa8f`. Grammar: cpp. Status: contains-errors.

- include <limits.h> @26
- include <type_traits> @28
- include "mozilla/Attributes.h" @30
- struct_specifier WrapToSignedHelper @37-84
- function_definition compute @56-83
- function_definition WrapToSigned @96-99
- function_definition ToResult @104-108
- struct_specifier WrappingAddHelper @111-120
- function_definition compute @116-119
- function_definition WrappingAdd @152-154
- struct_specifier WrappingSubtractHelper @159-168
- function_definition compute @164-167
- function_definition WrappingSubtract @198-200
- struct_specifier WrappingMultiplyHelper @205-217
- function_definition compute @210-216
- function_definition WrappingMultiply @256-258

### mfbt/XorShift128PlusRNG.h

Blob: `78c271d4b210d4b2874b0904b7baf2407e7fca2b`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Assertions.h" @10
- include "mozilla/Attributes.h" @11
- include "mozilla/FloatingPoint.h" @12
- class_specifier XorShift128PlusRNG @40-113
- function_definition XorShift128PlusRNG @53-55
- function_definition next @60-74
- function_definition nextDouble @82-94
- function_definition setState @101-105
- function_definition offsetOfState0 @107-109
- function_definition offsetOfState1 @110-112

### mfbt/double-conversion/double-conversion/bignum-dtoa.cc

Blob: `1d44b87589726586f15477dad536e52d69ca0e57`. Grammar: cpp. Status: syntax-clean.

- include <cmath> @28
- include "bignum-dtoa.h" @30
- include "bignum.h" @32
- include "ieee.h" @33
- function_definition NormalizedExponent @37-44
- function_definition BignumDtoa @89-169
- function_definition GenerateShortestDigits @185-274
- function_definition GenerateCountedDigits @283-323
- function_definition BignumToFixed @331-372
- function_definition EstimatePower @390-418
- function_definition InitialScaledStartValuesPositiveExponent @422-451
- function_definition InitialScaledStartValuesNegativeExponentPositivePower @455-485
- function_definition InitialScaledStartValuesNegativeExponentNegativePower @489-532
- function_definition InitialScaledStartValues @573-603
- function_definition FixupMultiply10 @617-644

### mfbt/double-conversion/double-conversion/bignum-dtoa.h

Blob: `34b961992d672c1713bc19dde430939d28dffb53`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31
- enum_specifier BignumDtoaMode @35-48

### mfbt/double-conversion/double-conversion/bignum.cc

Blob: `c1476cca77bc8dc4001f3c6872f85e8873ccda01`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @28
- include <cstring> @29
- include "bignum.h" @31
- include "utils.h" @32
- function_definition (anonymous) @36-39
- function_definition (anonymous) @42-45
- function_definition AssignUInt16 @49-56
- function_definition AssignUInt64 @59-66
- function_definition AssignBignum @69-75
- function_definition ReadUInt64 @78-88
- function_definition AssignDecimalString @91-109
- function_definition HexCharValue @112-121
- function_definition AssignHexString @126-147
- function_definition AddUInt64 @150-157
- function_definition AddBignum @160-203
- function_definition RawBigit @185-185
- function_definition SubtractBignum @206-230
- function_definition ShiftLeft @233-241
- function_definition MultiplyByUInt32 @244-270
- function_definition MultiplyByUInt64 @273-302
- function_definition MultiplyByPowerOfTen @305-346
- function_definition Square @349-418
- function_definition AssignPowerUInt16 @421-492
- function_definition DivideModuloIntBignum @496-559
- function_definition SizeInHexChars @563-571
- function_definition HexCharOfValue @574-580
- function_definition ToHexString @583-624
- function_definition BigitOrZero @627-635
- function_definition Compare @638-661
- function_definition PlusCompare @664-706
- function_definition Clamp @709-717
- function_definition Align @720-742
- function_definition RawBigit @734-734
- function_definition BigitsShiftLeft @745-758
- function_definition SubtractTimes @761-788

### mfbt/double-conversion/double-conversion/bignum.h

Blob: `14d1ca86fc7fdefbcd394585026165225de71a14`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31
- class_specifier Bignum @35-148
- function_definition Bignum @42-42
- function_definition Times10 @63-63
- function_definition Equal @77-79
- function_definition LessEqual @80-82
- function_definition Less @83-85
- function_definition PlusEqual @89-91
- function_definition PlusLessEqual @93-95
- function_definition PlusLess @97-99
- function_definition EnsureCapacity @114-118
- function_definition IsClamped @121-123
- function_definition Zero @124-127
- function_definition BigitLength @133-133

### mfbt/double-conversion/double-conversion/cached-powers.cc

Blob: `56bdfc9d6361119c668bbe2734c72de18a26f588`. Grammar: cpp. Status: contains-errors.

- include <climits> @28
- include <cmath> @29
- include <cstdarg> @30
- include "utils.h" @32
- include "cached-powers.h" @34
- struct_specifier CachedPower @40-44
- function_definition GetCachedPowerForBinaryExponentRange @139-156
- function_definition GetCachedPowerForDecimalExponent @159-171

### mfbt/double-conversion/double-conversion/cached-powers.h

Blob: `f38c26d201fad654612c81bca05f71feafc16111`. Grammar: cpp. Status: syntax-clean.

- include "diy-fp.h" @31

### mfbt/double-conversion/double-conversion/diy-fp.h

Blob: `a2200c4ded0cddd173eab631223b58bfa0447a0e`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31
- class_specifier DiyFp @41-133
- function_definition DiyFp @45-45
- function_definition DiyFp @46-46
- function_definition Subtract @52-56
- function_definition Minus @61-65
- function_definition Multiply @68-87
- function_definition Times @90-94
- function_definition Normalize @96-114
- function_definition Normalize @116-120
- function_definition f @122-122
- function_definition e @123-123
- function_definition set_f @125-125
- function_definition set_e @126-126

### mfbt/double-conversion/double-conversion/double-conversion.h

Blob: `6e8884d84ca56dbfd05964e463dd7999364b3b35`. Grammar: cpp. Status: syntax-clean.

- include "string-to-double.h" @31
- include "double-to-string.h" @32

### mfbt/double-conversion/double-conversion/double-to-string.cc

Blob: `dbb0c7d97ba9e1954ca32eb9274f6b6d7518bdf0`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @28
- include <climits> @29
- include <cmath> @30
- include "double-to-string.h" @32
- include "bignum-dtoa.h" @34
- include "fast-dtoa.h" @35
- include "fixed-dtoa.h" @36
- include "ieee.h" @37
- include "utils.h" @38
- function_definition (anonymous) @42-51
- function_definition HandleSpecialValues @54-72
- function_definition CreateExponentialRepresentation @75-123
- function_definition CreateDecimalRepresentation @126-171
- function_definition ToShortestIeeeNumber @174-209
- function_definition ToFixed @212-242
- function_definition ToExponential @245-297
- function_definition ToPrecision @300-366
- function_definition DtoaToBignumDtoaMode @369-380
- function_definition DoubleToAscii @383-448

### mfbt/double-conversion/double-conversion/double-to-string.h

Blob: `226b95aa44a372b69cc6d0a3f268432322daa9c1`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Types.h" @31
- include "utils.h" @32
- class_specifier DoubleToStringConverter @36-494
- enum_specifier Flags @76-85
- function_definition DoubleToStringConverter @166-190
- function_definition ToShortest @249-251
- function_definition ToShortestSingle @260-262
- enum_specifier DtoaMode @392-405

### mfbt/double-conversion/double-conversion/fast-dtoa.cc

Blob: `d7a23984df2de338354fd7c7b3896f8e5fe63613`. Grammar: cpp. Status: syntax-clean.

- include "fast-dtoa.h" @28
- include "cached-powers.h" @30
- include "diy-fp.h" @31
- include "ieee.h" @32
- function_definition RoundWeed @61-166
- function_definition RoundWeedCounted @181-223
- function_definition BiggestPowerTen @240-256
- function_definition DigitGen @300-396
- function_definition DigitGenCounted @428-505
- function_definition Grisu3 @519-583
- function_definition Grisu3Counted @591-632
- function_definition FastDtoa @635-663

### mfbt/double-conversion/double-conversion/fast-dtoa.h

Blob: `5f1e8eee5e56e7c496c84dc0a5bf9dad0b97fc9f`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31
- enum_specifier FastDtoaMode @35-45

### mfbt/double-conversion/double-conversion/fixed-dtoa.cc

Blob: `e739b19804cdc219376fc9e85f825d2e6af41ab7`. Grammar: cpp. Status: syntax-clean.

- include <cmath> @28
- include "fixed-dtoa.h" @30
- include "ieee.h" @31
- class_specifier UInt128 @37-114
- function_definition UInt128 @39-39
- function_definition UInt128 @40-40
- function_definition Multiply @42-57
- function_definition Shift @59-78
- function_definition DivModPowerOf2 @82-95
- function_definition IsZero @97-99
- function_definition BitAt @101-107
- function_definition FillDigits32FixedLength @120-127
- function_definition FillDigits32 @130-150
- function_definition FillDigits64FixedLength @153-165
- function_definition FillDigits64 @168-186
- function_definition RoundUp @189-216
- function_definition FillFractionals @230-287
- function_definition TrimZeros @292-307
- function_definition FastFixedDtoa @310-403

### mfbt/double-conversion/double-conversion/fixed-dtoa.h

Blob: `3bdd08e21f59d5fece37eb14a6f510f464c3f2ba`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31

### mfbt/double-conversion/double-conversion/ieee.h

Blob: `9203f4d558e0cea52007cc5809a715042451e8f9`. Grammar: cpp. Status: syntax-clean.

- include "diy-fp.h" @31
- function_definition double_to_uint64 @36-36
- function_definition uint64_to_double @37-37
- function_definition float_to_uint32 @38-38
- function_definition uint32_to_float @39-39
- class_specifier Double @42-284
- function_definition Double @54-54
- function_definition Double @55-55
- function_definition Double @56-56
- function_definition Double @57-58
- function_definition AsDiyFp @62-66
- function_definition AsNormalizedDiyFp @69-83
- function_definition AsUint64 @86-88
- function_definition NextDouble @91-102
- function_definition PreviousDouble @104-112
- function_definition Exponent @114-121
- function_definition Significand @123-131
- function_definition IsDenormal @134-137
- function_definition IsSpecial @141-144
- function_definition IsNan @146-150
- function_definition IsQuietNan @152-158
- function_definition IsSignalingNan @160-166
- function_definition IsInfinite @169-173
- function_definition Sign @175-178
- function_definition UpperBoundary @182-185
- function_definition NormalizedBoundaries @191-205
- function_definition LowerBoundaryIsCloser @207-218
- function_definition value @220-220
- function_definition SignificandSizeForOrderOfMagnitude @228-234
- function_definition Infinity @236-238
- function_definition NaN @240-242
- function_definition DiyFpToUint64 @256-281
- class_specifier Single @286-443
- function_definition Single @296-296
- function_definition Single @297-297
- function_definition Single @298-298
- function_definition AsDiyFp @302-306
- function_definition AsUint32 @309-311
- function_definition Exponent @313-320
- function_definition Significand @322-330
- function_definition IsDenormal @333-336
- function_definition IsSpecial @340-343
- function_definition IsNan @345-349
- function_definition IsQuietNan @351-357
- function_definition IsSignalingNan @359-365
- function_definition IsInfinite @368-372
- function_definition Sign @374-377
- function_definition NormalizedBoundaries @383-397
- function_definition UpperBoundary @401-404
- function_definition LowerBoundaryIsCloser @406-417
- function_definition value @419-419
- function_definition Infinity @421-423
- function_definition NaN @425-427

### mfbt/double-conversion/double-conversion/string-to-double.cc

Blob: `6cc6ce0bc48d603b7b9dbac827b7c67276e6005e`. Grammar: cpp. Status: contains-errors.

- include <climits> @28
- include <locale> @29
- include <cmath> @30
- include "string-to-double.h" @32
- include "ieee.h" @34
- include "strtod.h" @35
- include "utils.h" @36
- function_definition CodeUnit @57-59
- function_definition CodeUnit @61-63
- function_definition ToLower @65-70
- function_definition Pass @72-74
- function_definition ConsumeSubStringImpl @77-92
- function_definition ConsumeSubString @97-106
- function_definition ConsumeFirstCharacter @110-116
- function_definition isWhitespace @140-151
- function_definition AdvanceToNonspace @156-162
- function_definition isDigit @165-169
- function_definition SignedZero @172-174
- function_definition IsDecimalDigitForRadix @185-187
- function_definition IsDecimalDigitForRadix @190-192
- function_definition IsCharacterDigitForRadix @201-203
- function_definition Advance @207-223
- function_definition IsHexFloatString @233-272
- function_definition RadixStringToIeee @280-478
- function_definition StringToIeee @481-824
- function_definition StringToDouble @827-832
- function_definition StringToDouble @835-840
- function_definition StringToFloat @843-849
- function_definition StringToFloat @852-858
- function_definition StringTo<double> @862-867
- function_definition StringTo<float> @871-876
- function_definition StringTo<double> @880-885
- function_definition StringTo<float> @889-894

### mfbt/double-conversion/double-conversion/string-to-double.h

Blob: `24972da26d9bdb43d63afcf571612fcbd7e6152f`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Types.h" @31
- include "utils.h" @32
- class_specifier StringToDoubleConverter @36-235
- enum_specifier Flags @40-51
- function_definition StringToDoubleConverter @168-180

### mfbt/double-conversion/double-conversion/strtod.cc

Blob: `21d8438941fa608ef0d5d5040daa688ca118020b`. Grammar: cpp. Status: contains-errors.

- include <climits> @28
- include <cstdarg> @29
- include "bignum.h" @31
- include "cached-powers.h" @32
- include "ieee.h" @33
- include "strtod.h" @34
- function_definition TrimLeadingZeros @95-102
- function_definition CutToMaxSignificantDigits @104-119
- function_definition ClampExponent @128-133
- function_definition TrimAndCut @140-158
- function_definition ReadUint64 @166-177
- function_definition ReadDiyFp @184-202
- function_definition DoubleStrtod @205-257
- function_definition AdjustmentPowerOfTen @262-279
- function_definition DiyFpStrtod @285-392
- function_definition CompareBufferWithDiyFp @403-429
- function_definition ComputeGuess @434-458
- function_definition IsDigit @461-463
- function_definition IsNonZeroDigit @465-467
- function_definition AssertTrimmedDigits @474-481
- function_definition StrtodTrimmed @484-504
- function_definition Strtod @506-513
- function_definition SanitizedDoubletof @515-537
- function_definition Strtof @539-547
- function_definition StrtofTrimmed @549-624

### mfbt/double-conversion/double-conversion/strtod.h

Blob: `77221fb9d5388f4fc869cdc40b345165c2a86872`. Grammar: cpp. Status: syntax-clean.

- include "utils.h" @31
- function_definition TrimTrailingZeros @53-60

### mfbt/double-conversion/double-conversion/utils.h

Blob: `629ac2b9a5e95f5162a5f4e77a6b29316b2b5a9c`. Grammar: cpp. Status: contains-errors.

- include <cstdlib> @34
- include <cstring> @35
- include "mozilla/Assertions.h" @44
- function_definition abort_noreturn @76-76
- include <stdint.h> @189
- function_definition StrLength @244-248
- class_specifier Vector @252-295
- function_definition Vector @254-254
- function_definition Vector @255-257
- function_definition SubVector @261-266
- function_definition length @269-269
- function_definition is_empty @272-272
- function_definition start @275-275
- function_definition (anonymous) @278-281
- function_definition (anonymous) @283-283
- function_definition (anonymous) @285-285
- function_definition pop_back @287-290
- class_specifier StringBuilder @301-371
- function_definition StringBuilder @303-304
- function_definition ~StringBuilder @306-306
- function_definition size @308-308
- function_definition position @311-314
- function_definition Reset @317-317
- function_definition AddCharacter @322-326
- function_definition AddString @330-332
- function_definition AddSubstring @336-341
- function_definition AddPadding @346-350
- function_definition Finalize @353-362
- function_definition is_finalized @368-368
- function_definition BitCast @398-412
- function_definition BitCast @415-417

### mfbt/fallible.h

Blob: `543564502a30831b399cada8d50351eb32087004`. Grammar: cpp. Status: syntax-clean.

- include <new> @55

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
