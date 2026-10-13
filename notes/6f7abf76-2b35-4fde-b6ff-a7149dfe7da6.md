<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["third_party"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["655c5dbe3b65db7f1f96b42334eef6854e0f13934a110606506c42c8f420e1b8"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/f1ac82ff-e59b-496a-bef9-99b50460436d.md"}} -->
# firefox/third_party native and TypeScript syntax map 336

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span.h

Blob: `f26e38e4eeac2804d4de53052fdbcb6214dba7bb`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include "opentelemetry/common/attribute_value.h" @8
- include "opentelemetry/common/key_value_iterable_view.h" @9
- include "opentelemetry/nostd/span.h" @10
- include "opentelemetry/nostd/string_view.h" @11
- include "opentelemetry/nostd/type_traits.h" @12
- include "opentelemetry/trace/span_context.h" @13
- include "opentelemetry/trace/span_context_kv_iterable.h" @14
- include "opentelemetry/trace/span_context_kv_iterable_view.h" @15
- include "opentelemetry/trace/span_metadata.h" @16
- include "opentelemetry/version.h" @18
- function_definition namespace @20-258
- class_specifier Tracer @24-24
- class_specifier Span @54-256
- function_definition Span @59-59
- function_definition ~Span @62-62
- function_definition Span @65-65
- function_definition Span @66-66
- function_definition (anonymous) @67-67
- function_definition (anonymous) @68-68
- function_definition AddEvent @92-96
- function_definition AddEvent @100-105
- function_definition AddEvent @109-112
- function_definition AddEvent @114-122
- function_definition AddEvent @124-131
- function_definition AddLink @163-167
- function_definition AddLink @176-189
- function_definition AddLinks @199-203
- function_definition AddLinks @212-229

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_context.h

Blob: `54ce38c021b4183efae80d1de97d97a99a388fbd`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @6
- include <utility> @8
- include "opentelemetry/nostd/shared_ptr.h" @10
- include "opentelemetry/trace/span_id.h" @11
- include "opentelemetry/trace/trace_flags.h" @12
- include "opentelemetry/trace/trace_id.h" @13
- include "opentelemetry/trace/trace_state.h" @14
- include "opentelemetry/version.h" @15
- function_definition namespace @17-93
- class_specifier SpanContext @24-92
- function_definition SpanContext @34-40
- function_definition SpanContext @42-52
- function_definition IsValid @55-55
- function_definition (anonymous) @58-58
- function_definition (anonymous) @61-61
- function_definition (anonymous) @64-64
- function_definition (anonymous) @67-67
- function_definition operator== @74-78
- function_definition IsRemote @80-80
- function_definition GetInvalid @82-82
- function_definition IsSampled @84-84

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_context_kv_iterable.h

Blob: `0cd92bd6ea1a73b97fcd9a2b840b29faaf6c74c9`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/common/attribute_value.h" @6
- include "opentelemetry/common/key_value_iterable_view.h" @7
- include "opentelemetry/nostd/function_ref.h" @8
- include "opentelemetry/trace/span_context.h" @9
- include "opentelemetry/version.h" @10
- function_definition namespace @12-58
- class_specifier SpanContextKeyValueIterable @18-41
- function_definition SpanContextKeyValueIterable @21-21
- function_definition ~SpanContextKeyValueIterable @22-22
- function_definition SpanContextKeyValueIterable @23-23
- function_definition (anonymous) @24-24
- function_definition SpanContextKeyValueIterable @25-25
- function_definition (anonymous) @26-26
- class_specifier NullSpanContext @46-56
- function_definition ForEachKeyValue @49-53
- function_definition size @55-55

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_context_kv_iterable_view.h

Blob: `cd014a23fbf524dd4aec62af8bd1697186db6648`. Grammar: cpp. Status: contains-errors.

- include <iterator> @6
- include <type_traits> @7
- include <utility> @8
- include "opentelemetry/common/key_value_iterable_view.h" @10
- include "opentelemetry/nostd/function_ref.h" @11
- include "opentelemetry/nostd/span.h" @12
- include "opentelemetry/nostd/string_view.h" @13
- include "opentelemetry/nostd/utility.h" @14
- include "opentelemetry/trace/span_context.h" @15
- include "opentelemetry/trace/span_context_kv_iterable.h" @16
- include "opentelemetry/version.h" @17
- function_definition namespace @19-119
- function_definition take_span_context_kv @27-29
- function_definition take_span_context_kv @32-33
- function_definition take_span_context_kv @35-38
- struct_specifier is_span_context_kv_iterable @49-53
- class_specifier SpanContextKeyValueIterableView @57-118
- function_definition SpanContextKeyValueIterableView @63-63
- function_definition ForEachKeyValue @65-78
- function_definition size @80-80
- function_definition do_callback @85-95
- function_definition do_callback @99-105
- function_definition do_callback @107-117

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_id.h

Blob: `6537f77fc7227f9ff0301208587c25e93bcf9d02`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include <cstring> @7
- include "opentelemetry/nostd/span.h" @9
- include "opentelemetry/version.h" @10
- function_definition namespace @12-66
- class_specifier SpanId @16-64
- function_definition SpanId @23-23
- function_definition SpanId @26-26
- function_definition ToLowerBase16 @29-37
- function_definition Id @40-43
- function_definition operator== @45-45
- function_definition operator!= @47-47
- function_definition IsValid @50-54
- function_definition CopyBytesTo @57-60

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_metadata.h

Blob: `a138026bdb4fbf28d1b9eb855f4c173d075f8637`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/common/timestamp.h" @6
- include "opentelemetry/version.h" @7
- include <cstdint> @10
- enum_specifier SpanKind @18-18
- enum_specifier SpanKind @20-28
- enum_specifier StatusCode @36-36
- enum_specifier StatusCode @38-44
- struct_specifier EndSpanOptions @50-54

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/span_startoptions.h

Blob: `8a2165b0f06af566a4b3d1d602a4a2edd022304d`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/common/timestamp.h" @6
- include "opentelemetry/context/context.h" @7
- include "opentelemetry/nostd/variant.h" @8
- include "opentelemetry/trace/span_context.h" @9
- include "opentelemetry/trace/span_metadata.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-70
- struct_specifier StartSpanOptions @21-68

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/trace_flags.h

Blob: `f4c7bc6a447d44a546ba5c5f6889ceec0951df04`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include "opentelemetry/nostd/span.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-65
- class_specifier TraceFlags @18-63
- function_definition TraceFlags @36-36
- function_definition TraceFlags @38-38
- function_definition IsSampled @40-40
- function_definition IsRandom @42-42
- function_definition ToLowerBase16 @45-50
- function_definition flags @52-52
- function_definition operator== @54-54
- function_definition operator!= @56-56
- function_definition CopyBytesTo @59-59

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/trace_id.h

Blob: `533037123e4e6463913923853d57ae4bd544eeba`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include <cstring> @7
- include "opentelemetry/nostd/span.h" @9
- include "opentelemetry/version.h" @10
- function_definition namespace @12-71
- class_specifier TraceId @19-69
- function_definition TraceId @26-26
- function_definition TraceId @29-32
- function_definition ToLowerBase16 @35-43
- function_definition Id @46-49
- function_definition operator== @51-54
- function_definition operator!= @56-56
- function_definition IsValid @59-59
- function_definition CopyBytesTo @62-65

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/trace_state.h

Blob: `5cab875852ca84139ea88517c14c4dc68a8bf655`. Grammar: cpp. Status: contains-errors.

- include <ctype.h> @6
- include <cstddef> @7
- include <string> @8
- include <vector> @9
- include "opentelemetry/common/kv_properties.h" @11
- include "opentelemetry/nostd/function_ref.h" @12
- include "opentelemetry/nostd/shared_ptr.h" @13
- include "opentelemetry/nostd/string_view.h" @14
- include "opentelemetry/nostd/unique_ptr.h" @15
- include "opentelemetry/version.h" @16
- include <regex> @19
- function_definition namespace @22-332
- function_definition TraceState @34-330
- class_specifier OPENTELEMETRY_EXPORT @34-34
- function_definition shared_ptr<TraceState> GetDefault @43-47
- function_definition FromHeader @55-87
- function_definition ToHeader @92-112
- function_definition Get @118-126
- function_definition Set @138-164
- function_definition Delete @172-193
- function_definition Empty @196-196
- function_definition GetAllEntries @200-204
- function_definition IsValidKey @212-219
- function_definition IsValidValue @225-232
- function_definition TraceState @236-236
- function_definition TrimString @238-249
- function_definition IsValidKeyRegEx @252-268
- function_definition IsValidValueRegEx @270-288
- function_definition IsValidKeyNonRegEx @290-305
- function_definition IsValidValueNonRegEx @307-322
- function_definition IsLowerCaseAlphaOrDigit @325-325

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/tracer.h

Blob: `3684f332460284565c33c383d7a0958b21f3f833`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include "opentelemetry/context/context.h" @8
- include "opentelemetry/nostd/shared_ptr.h" @9
- include "opentelemetry/nostd/string_view.h" @10
- include "opentelemetry/trace/context.h" @11
- include "opentelemetry/trace/default_span.h" @12
- include "opentelemetry/trace/scope.h" @13
- include "opentelemetry/trace/span.h" @14
- include "opentelemetry/trace/span_context_kv_iterable_view.h" @15
- include "opentelemetry/trace/span_startoptions.h" @16
- include "opentelemetry/version.h" @17
- function_definition namespace @19-245
- class_specifier Tracer @28-244
- function_definition Tracer @31-31
- function_definition ~Tracer @32-32
- function_definition Tracer @33-33
- function_definition (anonymous) @34-34
- function_definition Tracer @35-35
- function_definition (anonymous) @36-36
- function_definition StartSpan @54-58
- function_definition StartSpan @62-67
- function_definition StartSpan @69-74
- function_definition StartSpan @80-87
- function_definition StartSpan @89-96
- function_definition StartSpan @100-115
- function_definition StartSpan @119-129
- function_definition StartSpan @131-148
- function_definition WithActiveSpan @156-156
- function_definition GetCurrentSpan @163-166
- function_definition Enabled @177-177
- function_definition ForceFlush @192-196
- function_definition Close @205-209
- function_definition UpdateEnabled @230-233

### third_party/opentelemetry-cpp/api/include/opentelemetry/trace/tracer_provider.h

Blob: `222b77f6bd0541ec0cb188e94475454f2401b2f9`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/common/key_value_iterable.h" @6
- include "opentelemetry/common/key_value_iterable_view.h" @7
- include "opentelemetry/nostd/shared_ptr.h" @8
- include "opentelemetry/nostd/string_view.h" @9
- include "opentelemetry/version.h" @10
- function_definition namespace @12-131
- class_specifier Tracer @16-16
- function_definition TracerProvider @21-130
- class_specifier OPENTELEMETRY_EXPORT @21-21
- function_definition ~TracerProvider @25-25
- function_definition TracerProvider @26-26
- function_definition TracerProvider @28-28
- function_definition GetTracer @58-63
- function_definition GetTracer @75-92
- function_definition GetTracer @106-116

### third_party/opentelemetry-cpp/api/include/opentelemetry/version.h

Blob: `48908afe8866f03bc4af21dabc15c2c98cad76eb`. Grammar: cpp. Status: syntax-clean.

- include "opentelemetry/common/macros.h" @6
- include "opentelemetry/detail/preprocessor.h" @7

### third_party/opentelemetry-cpp/exporters/memory/include/opentelemetry/exporters/memory/in_memory_data.h

Blob: `26acba4b63f0daf1e28e93503c4adf297c1e0a57`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/common/circular_buffer.h" @6
- include <vector> @8
- function_definition namespace @10-61
- class_specifier InMemoryData @19-59
- function_definition InMemoryData @25-25
- function_definition Add @30-30
- function_definition Get @37-55

### third_party/opentelemetry-cpp/exporters/memory/include/opentelemetry/exporters/memory/in_memory_span_data.h

Blob: `6eaae0663cc9e671d2308d044fb813ebbea711c5`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @6
- include <memory> @7
- include <vector> @8
- include "opentelemetry/exporters/memory/in_memory_data.h" @10
- include "opentelemetry/sdk/trace/span_data.h" @11
- include "opentelemetry/version.h" @12
- function_definition namespace @14-32
- class_specifier InMemorySpanData @19-30
- function_definition InMemorySpanData @25-27
- function_definition GetSpans @29-29

### third_party/opentelemetry-cpp/exporters/memory/include/opentelemetry/exporters/memory/in_memory_span_exporter.h

Blob: `21192170d43bf9f1468356bc8df7fbf5f878dff9`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @6
- include <atomic> @7
- include <chrono> @8
- include <memory> @9
- include <ostream> @10
- include <utility> @11
- include "opentelemetry/exporters/memory/in_memory_span_data.h" @13
- include "opentelemetry/nostd/span.h" @14
- include "opentelemetry/sdk/common/exporter_utils.h" @15
- include "opentelemetry/sdk/common/global_log_handler.h" @16
- include "opentelemetry/sdk/trace/exporter.h" @17
- include "opentelemetry/sdk/trace/recordable.h" @18
- include "opentelemetry/sdk/trace/span_data.h" @19
- include "opentelemetry/version.h" @20
- function_definition namespace @22-103
- class_specifier InMemorySpanExporter @33-101
- function_definition InMemorySpanExporter @39-41
- function_definition MakeRecordable @46-49
- function_definition Export @56-76
- function_definition ForceFlush @78-78
- function_definition Shutdown @86-90
- function_definition GetData @95-95
- function_definition isShutdown @100-100

### third_party/opentelemetry-cpp/exporters/memory/include/opentelemetry/exporters/memory/in_memory_span_exporter_factory.h

Blob: `549ff13c71d89ee385f50701b8fcac01c4a56b19`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @6
- include <memory> @7
- include "opentelemetry/exporters/memory/in_memory_span_data.h" @9
- include "opentelemetry/sdk/trace/exporter.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-45
- class_specifier InMemorySpanExporterFactory @22-42

### third_party/opentelemetry-cpp/exporters/memory/src/in_memory_span_exporter_factory.cc

Blob: `ff5bab92533ebe7e25d768ff718d5f201a3f0558`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/exporters/memory/in_memory_span_exporter_factory.h" @4
- include "opentelemetry/exporters/memory/in_memory_span_data.h" @5
- include "opentelemetry/exporters/memory/in_memory_span_exporter.h" @6
- include "opentelemetry/sdk/trace/exporter.h" @7
- function_definition namespace @9-32
- function_definition Create @15-19
- function_definition Create @21-29

### third_party/opentelemetry-cpp/exporters/otlp/include/opentelemetry/exporters/otlp/otlp_populate_attribute_utils.h

Blob: `fe4f5ac0e0b7410f684ab58fd625fec8f4fd82a8`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @6
- include <limits> @7
- include <string> @8
- include "opentelemetry/common/attribute_value.h" @10
- include "opentelemetry/nostd/string_view.h" @11
- include "opentelemetry/sdk/common/attribute_utils.h" @12
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @13
- include "opentelemetry/sdk/resource/resource.h" @14
- include "opentelemetry/version.h" @15
- class_specifier AnyValue @26-26
- class_specifier KeyValue @27-27
- class_specifier InstrumentationScope @28-28
- class_specifier Resource @36-36
- function_definition namespace @43-120
- class_specifier OtlpPopulateAttributeUtils @51-117
- function_definition Utf8SafePrefixLength @113-116

### third_party/opentelemetry-cpp/exporters/otlp/include/opentelemetry/exporters/otlp/otlp_recordable.h

Blob: `d4c30483f8e787787b60a6260f6bbd449aaad9f0`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <cstdint> @7
- include <limits> @8
- include <string> @9
- include "opentelemetry/exporters/otlp/protobuf_include_prefix.h" @12
- include "opentelemetry/proto/common/v1/common.pb.h" @13
- include "opentelemetry/proto/resource/v1/resource.pb.h" @14
- include "opentelemetry/proto/trace/v1/trace.pb.h" @15
- include "opentelemetry/exporters/otlp/protobuf_include_suffix.h" @16
- include "opentelemetry/common/attribute_value.h" @19
- include "opentelemetry/common/key_value_iterable.h" @20
- include "opentelemetry/common/timestamp.h" @21
- include "opentelemetry/nostd/string_view.h" @22
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @23
- include "opentelemetry/sdk/resource/resource.h" @24
- include "opentelemetry/sdk/trace/recordable.h" @25
- include "opentelemetry/sdk/trace/span_limits.h" @26
- include "opentelemetry/trace/span_context.h" @27
- include "opentelemetry/trace/span_id.h" @28
- include "opentelemetry/trace/span_metadata.h" @29
- include "opentelemetry/trace/trace_flags.h" @30
- include "opentelemetry/version.h" @31
- function_definition namespace @33-127
- class_specifier OtlpRecordable @38-125
- function_definition OtlpRecordable @48-60
- function_definition (anonymous) @62-62
- function_definition (anonymous) @63-63

### third_party/opentelemetry-cpp/exporters/otlp/include/opentelemetry/exporters/otlp/otlp_recordable_utils.h

Blob: `94be2933aab859ae29e6f7bf5869c32e82dc359d`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include "opentelemetry/nostd/span.h" @8
- include "opentelemetry/sdk/trace/recordable.h" @9
- include "opentelemetry/version.h" @10
- class_specifier ExportLogsServiceRequest @23-23
- class_specifier ExportTraceServiceRequest @30-30
- function_definition namespace @38-54
- class_specifier OtlpRecordableUtils @46-52

### third_party/opentelemetry-cpp/exporters/otlp/include/opentelemetry/exporters/otlp/protobuf_include_prefix.h

Blob: `ce2d4ce041dfef434636e0dce5cbfed2ad516cdd`. Grammar: cpp. Status: syntax-clean.


### third_party/opentelemetry-cpp/exporters/otlp/include/opentelemetry/exporters/otlp/protobuf_include_suffix.h

Blob: `547eb3f3356f54252e20e8443883fae460b90e85`. Grammar: cpp. Status: syntax-clean.


### third_party/opentelemetry-cpp/exporters/otlp/src/otlp_populate_attribute_utils.cc

Blob: `943121e5706adbaf8abc4c093f34ff638737e0b7`. Grammar: cpp. Status: contains-errors.

- include <utf8_validity.h> @5
- include <stdint.h> @8
- include <algorithm> @9
- include <cstring> @10
- include <limits> @11
- include <string> @12
- include <utility> @13
- include <vector> @14
- include "opentelemetry/common/attribute_value.h" @16
- include "opentelemetry/exporters/otlp/otlp_populate_attribute_utils.h" @17
- include "opentelemetry/nostd/span.h" @18
- include "opentelemetry/nostd/string_view.h" @19
- include "opentelemetry/nostd/variant.h" @20
- include "opentelemetry/sdk/common/attribute_utils.h" @21
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @22
- include "opentelemetry/sdk/resource/resource.h" @23
- include "opentelemetry/version.h" @24
- include "opentelemetry/exporters/otlp/protobuf_include_prefix.h" @27
- include "opentelemetry/proto/common/v1/common.pb.h" @28
- include "opentelemetry/proto/resource/v1/resource.pb.h" @29
- include "opentelemetry/exporters/otlp/protobuf_include_suffix.h" @30
- function_definition namespace @33-459
- function_definition SetUint64Value @50-60
- function_definition PopulateAnyValue @63-227
- function_definition PopulateAnyValue @229-373
- function_definition PopulateAttribute @375-395
- function_definition PopulateAttribute @398-418
- function_definition PopulateAttribute @420-434
- function_definition PopulateAttribute @436-446
- function_definition Utf8SafePrefixLength @451-456

### third_party/opentelemetry-cpp/exporters/otlp/src/otlp_recordable.cc

Blob: `017fc5190521429c08425c1bf91f5d9e06b99d5b`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @4
- include <chrono> @5
- include <cstdint> @6
- include <string> @7
- include "opentelemetry/common/attribute_value.h" @9
- include "opentelemetry/common/key_value_iterable.h" @10
- include "opentelemetry/common/timestamp.h" @11
- include "opentelemetry/exporters/otlp/otlp_populate_attribute_utils.h" @12
- include "opentelemetry/exporters/otlp/otlp_recordable.h" @13
- include "opentelemetry/nostd/function_ref.h" @14
- include "opentelemetry/nostd/span.h" @15
- include "opentelemetry/nostd/string_view.h" @16
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @17
- include "opentelemetry/sdk/resource/resource.h" @18
- include "opentelemetry/sdk/trace/span_limits.h" @19
- include "opentelemetry/trace/span_context.h" @20
- include "opentelemetry/trace/span_id.h" @21
- include "opentelemetry/trace/span_metadata.h" @22
- include "opentelemetry/trace/trace_flags.h" @23
- include "opentelemetry/trace/trace_id.h" @24
- include "opentelemetry/trace/trace_state.h" @25
- include "opentelemetry/version.h" @26
- include "opentelemetry/exporters/otlp/protobuf_include_prefix.h" @29
- include "opentelemetry/proto/common/v1/common.pb.h" @30
- include "opentelemetry/proto/resource/v1/resource.pb.h" @31
- include "opentelemetry/proto/trace/v1/trace.pb.h" @32
- include "opentelemetry/exporters/otlp/protobuf_include_suffix.h" @33
- function_definition namespace @36-278
- function_definition SetIdentity @42-55
- function_definition ProtoResource @57-66
- function_definition GetResource @68-71
- function_definition GetResourceSchemaURL @73-82
- function_definition GetInstrumentationScope @84-88
- function_definition GetInstrumentationLibrarySchemaURL @90-99
- function_definition GetProtoInstrumentationScope @101-112
- function_definition SetResource @114-117
- function_definition SetSpanLimits @119-132
- function_definition SetAttribute @134-146
- function_definition AddEvent @148-173
- function_definition AddLink @175-200
- function_definition SetStatus @202-209
- function_definition SetName @211-214
- function_definition SetTraceFlags @216-221
- function_definition SetSpanKind @223-257
- function_definition SetStartTime @259-262
- function_definition SetDuration @264-268
- function_definition SetInstrumentationScope @270-275

### third_party/opentelemetry-cpp/exporters/otlp/src/otlp_recordable_utils.cc

Blob: `120238b97152c0e2257918a5ee582daf7464293f`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @4
- include <memory> @5
- include <unordered_map> @6
- include "opentelemetry/exporters/otlp/otlp_populate_attribute_utils.h" @8
- include "opentelemetry/exporters/otlp/otlp_recordable.h" @9
- include "opentelemetry/exporters/otlp/otlp_recordable_utils.h" @10
- include "opentelemetry/nostd/span.h" @11
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @12
- include "opentelemetry/sdk/resource/resource.h" @13
- include "opentelemetry/sdk/trace/recordable.h" @14
- include "opentelemetry/version.h" @15
- include "opentelemetry/exporters/otlp/protobuf_include_prefix.h" @18
- include "opentelemetry/proto/collector/trace/v1/trace_service.pb.h" @19
- include "opentelemetry/proto/common/v1/common.pb.h" @20
- include "opentelemetry/proto/resource/v1/resource.pb.h" @21
- include "opentelemetry/proto/trace/v1/trace.pb.h" @22
- include "opentelemetry/exporters/otlp/protobuf_include_suffix.h" @23
- function_definition namespace @26-135
- struct_specifier InstrumentationScopePointerHasher @34-46
- function_definition operator() @36-45
- struct_specifier InstrumentationScopePointerEqual @48-66
- function_definition operator() @50-65
- function_definition PopulateRequest @69-132
- struct_specifier ResourceSpansEntry @82-86

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/atomic_shared_ptr.h

Blob: `39c0ce91cce235eb9fab6c26dca48390f15f5498`. Grammar: cpp. Status: contains-errors.

- include <atomic> @6
- include <memory> @7
- include <mutex> @8
- include "opentelemetry/version.h" @10
- function_definition namespace @12-62
- class_specifier AtomicSharedPtr @25-45
- function_definition AtomicSharedPtr @28-28
- function_definition store @30-34
- function_definition load @36-40
- class_specifier AtomicSharedPtr @48-59
- function_definition AtomicSharedPtr @51-51
- function_definition store @53-53
- function_definition load @55-55

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/atomic_unique_ptr.h

Blob: `01b1266330b5da67cf4521cdea4d7bfdf961a52f`. Grammar: cpp. Status: contains-errors.

- include <atomic> @6
- include <memory> @7
- include <utility> @8
- include "opentelemetry/version.h" @10
- function_definition namespace @12-91
- class_specifier AtomicUniquePtr @22-89
- function_definition AtomicUniquePtr @25-25
- function_definition AtomicUniquePtr @26-26
- function_definition AtomicUniquePtr @27-27
- function_definition (anonymous) @28-28
- function_definition (anonymous) @29-29
- function_definition AtomicUniquePtr @31-32
- function_definition ~AtomicUniquePtr @34-34
- function_definition (anonymous) @36-36
- function_definition operator-> @38-38
- function_definition Get @43-43
- function_definition IsNull @48-48
- function_definition SwapIfNull @55-66
- function_definition Swap @72-72
- function_definition Reset @78-85

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/attribute_utils.h

Blob: `8b83b363b060086f87446b2c7c493d65a808ee7a`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @6
- include <cstddef> @7
- include <cstdint> @8
- include <initializer_list> @9
- include <limits> @10
- include <map> @11
- include <string> @12
- include <unordered_map> @13
- include <utility> @14
- include <vector> @15
- include "opentelemetry/common/attribute_value.h" @17
- include "opentelemetry/common/key_value_iterable.h" @18
- include "opentelemetry/nostd/span.h" @19
- include "opentelemetry/nostd/string_view.h" @20
- include "opentelemetry/nostd/variant.h" @21
- include "opentelemetry/version.h" @22
- include <new> @25
- enum_specifier OwnedAttributeType @59-76
- function_definition Utf8SafePrefixLength @95-142
- struct_specifier AttributeConverter @157-227
- function_definition AttributeConverter @159-159
- function_definition AttributeConverter @164-164
- function_definition operator() @166-166
- function_definition operator() @167-167
- function_definition operator() @168-168
- function_definition operator() @169-169
- function_definition operator() @170-170
- function_definition operator() @171-171
- function_definition operator() @172-177
- function_definition operator() @178-185
- function_definition operator() @186-192
- function_definition operator() @193-198
- function_definition operator() @199-199
- function_definition operator() @200-200
- function_definition operator() @201-201
- function_definition operator() @202-202
- function_definition operator() @203-203
- function_definition operator() @204-204
- function_definition operator() @205-217
- function_definition convertSpan @220-223
- struct_specifier AttributeEqualToVisitor @234-281
- function_definition operator() @238-241
- function_definition operator() @245-248
- function_definition operator() @251-254
- function_definition operator() @257-260
- function_definition operator() @263-271
- function_definition operator() @275-280
- function_definition AttributeInsertOrAssign @292-303
- function_definition catch @327-331
- function_definition catch @332-335
- class_specifier AttributeMap @342-432
- function_definition AttributeMap @346-346
- function_definition AttributeMap @349-352
- function_definition AttributeMap @355-361
- function_definition AttributeMap @364-373
- function_definition ConstructFrom @375-382
- function_definition (anonymous) @385-388
- function_definition SetAttribute @391-403
- function_definition EqualTo @406-431
- class_specifier OrderedAttributeMap @437-484
- function_definition OrderedAttributeMap @441-441
- function_definition OrderedAttributeMap @444-452
- function_definition OrderedAttributeMap @455-464
- function_definition (anonymous) @467-470
- function_definition SetAttribute @473-483

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/attributemap_hash.h

Blob: `1ef97f5a3ccb7b6326fc839b09eac5ac56473683`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @6
- include <functional> @7
- include <string> @8
- include <utility> @9
- include <vector> @10
- include "opentelemetry/nostd/variant.h" @12
- include "opentelemetry/sdk/common/attribute_utils.h" @13
- include "opentelemetry/version.h" @14
- function_definition namespace @16-80
- function_definition GetHash @23-29
- function_definition GetHash @32-38
- function_definition GetHash @43-47
- struct_specifier GetHashForAttributeValueVisitor @49-58
- function_definition GetHashForAttributeValueVisitor @51-51
- function_definition operator() @53-56
- function_definition GetHashForAttributeMap @61-70
- function_definition GetHash @73-77

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/base64.h

Blob: `918eaaf14ae8ad9871db4b5cbcde29bfdaffc986`. Grammar: cpp. Status: contains-errors.

- include <string> @6
- include "opentelemetry/nostd/string_view.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-34

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/circular_buffer.h

Blob: `94ebb1f8cae3669b7fcf7754624b754bb0c31dd7`. Grammar: cpp. Status: contains-errors.

- include <atomic> @6
- include <cassert> @7
- include <cstddef> @8
- include <cstdint> @9
- include <functional> @10
- include <memory> @11
- include <utility> @12
- include "opentelemetry/nostd/span.h" @14
- include "opentelemetry/sdk/common/atomic_unique_ptr.h" @15
- include "opentelemetry/sdk/common/circular_buffer_range.h" @16
- include "opentelemetry/version.h" @17
- function_definition namespace @19-195
- class_specifier CircularBuffer @29-193
- function_definition CircularBuffer @32-34
- function_definition Peek @41-44
- function_definition Consume @57-64
- function_definition Consume @72-80
- function_definition Add @87-120
- function_definition Add @122-126
- function_definition Clear @133-133
- function_definition max_size @138-138
- function_definition empty @143-143
- function_definition size @151-157
- function_definition consumption_count @162-162
- function_definition production_count @167-167
- function_definition PeekImpl @175-192

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/circular_buffer_range.h

Blob: `5e16c3d41042961fbc7c238a09acb1d55c788877`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @6
- include <cassert> @7
- include <type_traits> @8
- include "opentelemetry/nostd/span.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-91
- class_specifier CircularBufferRange @22-89
- function_definition CircularBufferRange @25-25
- function_definition CircularBufferRange @27-27
- function_definition CircularBufferRange @29-31
- function_definition (anonymous) @33-33
- function_definition ForEach @41-59
- function_definition size @64-64
- function_definition empty @69-69
- function_definition Take @76-84

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/custom_hash_equality.h

Blob: `3d45c30c2d0250aced24e25f3d487f0c24f68fae`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @6
- include <cstring> @7
- include <string> @8
- include "opentelemetry/nostd/string_view.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-156
- struct_specifier FnvPrime @31-31
- struct_specifier FnvPrime<Ty, 4> @35-38
- struct_specifier FnvPrime<Ty, 8> @42-45
- struct_specifier FnvOffset @49-49
- struct_specifier FnvOffset<Ty, 4> @53-59
- function_definition Fix @58-58
- struct_specifier FnvOffset<Ty, 8> @63-70
- function_definition Fix @69-69
- function_definition Fnv1a @82-94
- struct_specifier StringViewHash @101-118
- function_definition operator() @109-112
- function_definition operator() @114-117
- struct_specifier StringViewEqual @120-136
- function_definition operator() @129-135
- function_definition find_heterogeneous @145-154

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/disabled.h

Blob: `ab181865d32b21af8bd269f316586c26f9354250`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/version.h" @6
- function_definition namespace @8-17

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/empty_attributes.h

Blob: `f5e10c12e6505c430ffe1c2a902dee0ee1b3abf9`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @6
- include <array> @7
- include <string> @8
- include <utility> @9
- include "opentelemetry/common/key_value_iterable_view.h" @11
- include "opentelemetry/version.h" @12
- function_definition namespace @14-26

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/env_variables.h

Blob: `7bf28e2c1cd165325f3670fd6e0bc19700867363`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <cstdint> @7
- include <string> @8
- include "opentelemetry/version.h" @10
- function_definition namespace @12-72
- function_definition setenv @60-63
- function_definition unsetenv @65-68

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/exporter_utils.h

Blob: `c25ff89bae078ed8bedb5ac9d87f6750dbcaa5e6`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include "opentelemetry/version.h" @8
- function_definition namespace @10-35
- enum_specifier ExportResult @18-32

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/common/global_log_handler.h

Blob: `2fd3bfe43a7868babc8296d957c244450fffa00c`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include <sstream> @7
- include <string> @8
- include "opentelemetry/nostd/shared_ptr.h" @10
- include "opentelemetry/sdk/common/attribute_utils.h" @11
- include "opentelemetry/version.h" @12
- function_definition namespace @24-133
- enum_specifier LogLevel @32-39
- function_definition LevelToString @41-57
- class_specifier LogHandler @59-74
- function_definition LogHandler @62-62
- function_definition LogHandler @64-64
- function_definition LogHandler @65-65
- function_definition (anonymous) @66-66
- function_definition (anonymous) @67-67
- class_specifier DefaultLogHandler @76-84
- class_specifier NoopLogHandler @86-94
- class_specifier GlobalLogHandler @99-129

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/instrumentationscope/instrumentation_scope.h

Blob: `9ede6945300da13fba65970443cd7744accc9c04`. Grammar: cpp. Status: contains-errors.

- include <string> @6
- include <type_traits> @7
- include "opentelemetry/common/key_value_iterable_view.h" @9
- include "opentelemetry/nostd/string_view.h" @10
- include "opentelemetry/nostd/type_traits.h" @11
- include "opentelemetry/nostd/unique_ptr.h" @12
- include "opentelemetry/nostd/variant.h" @13
- include "opentelemetry/sdk/common/attribute_utils.h" @14
- include "opentelemetry/version.h" @15
- function_definition namespace @17-184
- class_specifier InstrumentationScope @26-181
- function_definition InstrumentationScope @29-29
- function_definition InstrumentationScope @30-30
- function_definition (anonymous) @31-31
- function_definition (anonymous) @32-32
- function_definition ~InstrumentationScope @33-33
- function_definition Create @43-51
- function_definition Create @61-69
- function_definition Create @83-99
- function_definition HashCode @101-101
- function_definition operator== @108-112
- function_definition equal @124-145
- function_definition (anonymous) @147-147
- function_definition (anonymous) @148-148
- function_definition (anonymous) @149-149
- function_definition (anonymous) @150-150
- function_definition SetAttribute @152-157
- function_definition InstrumentationScope @160-172

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/instrumentationscope/scope_configurator.h

Blob: `7b073217419d1e47f3325d98619d9ae17ffd1179`. Grammar: cpp. Status: contains-errors.

- include <functional> @5
- include <utility> @6
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-148
- class_specifier ScopeConfigurator @21-146
- class_specifier Builder @27-125
- function_definition Builder @37-38
- function_definition (anonymous) @52-57
- function_definition (anonymous) @67-75
- function_definition Build @82-105
- struct_specifier Condition @113-121
- function_definition Condition @118-120
- function_definition ComputeConfig @134-137
- function_definition ScopeConfigurator @141-143

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/resource/resource.h

Blob: `2e462122f533c9efe0a7fd2a59f984879a27a41e`. Grammar: cpp. Status: contains-errors.

- include <string> @6
- include "opentelemetry/sdk/common/attribute_utils.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-82
- class_specifier Resource @19-79
- function_definition Resource @28-28
- function_definition Resource @29-29
- function_definition (anonymous) @30-30
- function_definition (anonymous) @31-31
- function_definition ~Resource @33-33

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/resource/resource_detector.h

Blob: `b707cfd4762b862cab2ba50130e9b9755aaac653`. Grammar: cpp. Status: contains-errors.

- include <string> @6
- include "opentelemetry/sdk/resource/resource.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-50
- class_specifier ResourceDetector @20-37
- function_definition ResourceDetector @23-23
- function_definition ResourceDetector @25-25
- function_definition ResourceDetector @26-26
- function_definition (anonymous) @27-27
- function_definition (anonymous) @28-28
- function_definition ~ResourceDetector @30-30
- class_specifier OTELResourceDetector @43-47

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/exporter.h

Blob: `ffd3785b871e3e4acf63a6d04a51937dd9d40570`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <memory> @7
- include "opentelemetry/nostd/span.h" @9
- include "opentelemetry/sdk/common/exporter_utils.h" @10
- include "opentelemetry/sdk/trace/recordable.h" @11
- include "opentelemetry/version.h" @12
- function_definition namespace @14-73
- function_definition SpanExporter @24-71
- class_specifier OPENTELEMETRY_EXPORT @24-24
- function_definition SpanExporter @29-29
- function_definition SpanExporter @30-30

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/id_generator.h

Blob: `28c80fc067482c4b6cb66e57985e94b8a25e86e4`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/trace/span_id.h" @6
- include "opentelemetry/trace/trace_id.h" @7
- include "opentelemetry/version.h" @8
- function_definition namespace @10-45
- class_specifier IdGenerator @17-42
- function_definition IdGenerator @20-20
- function_definition IdGenerator @22-22
- function_definition IdGenerator @23-23
- function_definition (anonymous) @24-24
- function_definition (anonymous) @25-25
- function_definition ~IdGenerator @27-27
- function_definition IsRandom @35-35

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/multi_recordable.h

Blob: `84c4e6be81754fe0838a0ee0b1176418ab4af04c`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @6
- include <map> @7
- include <memory> @8
- include "opentelemetry/common/timestamp.h" @10
- include "opentelemetry/sdk/trace/processor.h" @11
- include "opentelemetry/sdk/trace/recordable.h" @12
- include "opentelemetry/version.h" @13
- function_definition namespace @15-69
- class_specifier MultiRecordable @21-67

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/multi_span_processor.h

Blob: `7b0172dc8e3baefea2bd10c0827fa53ae3d003e1`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <memory> @7
- include <mutex> @8
- include <vector> @9
- include "opentelemetry/sdk/trace/multi_recordable.h" @11
- include "opentelemetry/sdk/trace/processor.h" @12
- include "opentelemetry/version.h" @13
- function_definition namespace @15-199
- struct_specifier MultiSpanProcessorOptions @22-23
- class_specifier MultiSpanProcessor @31-197
- function_definition MultiSpanProcessor @34-40
- function_definition MultiSpanProcessor @42-42
- function_definition MultiSpanProcessor @43-43
- function_definition (anonymous) @44-44
- function_definition (anonymous) @45-45
- function_definition AddProcessor @47-64
- function_definition MakeRecordable @66-78
- function_definition OnStart @80-95
- function_definition OnEnd @97-112
- function_definition ForceFlush @114-126
- function_definition Shutdown @128-132
- function_definition ~MultiSpanProcessor @134-138
- function_definition InternalShutdown @141-153
- struct_specifier ProcessorNode @156-165
- function_definition ProcessorNode @160-164
- function_definition Cleanup @167-192

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/processor.h

Blob: `5c4a6a2d54cfb7e4331a064676e49ce4d83eb7f0`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <memory> @7
- include "opentelemetry/version.h" @9
- function_definition namespace @11-15
- class_specifier SpanContext @14-14
- class_specifier Recordable @21-21
- function_definition SpanProcessor @29-82
- class_specifier OPENTELEMETRY_EXPORT @29-29
- function_definition SpanProcessor @34-34
- function_definition SpanProcessor @35-35
- function_definition ~SpanProcessor @39-39

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/provider.h

Blob: `98d3ca3a08e8b0af9c982fd0ee9326630336f461`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/nostd/shared_ptr.h" @6
- include "opentelemetry/trace/tracer_provider.h" @7
- include "opentelemetry/version.h" @8
- function_definition namespace @10-30
- function_definition Provider @19-27
- class_specifier OPENTELEMETRY_EXPORT @19-19

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/random_id_generator.h

Blob: `01e460563d07a24dec1b8d054e39b343feedb6a0`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/trace/id_generator.h" @6
- include "opentelemetry/trace/span_id.h" @7
- include "opentelemetry/trace/trace_id.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-28
- class_specifier RandomIdGenerator @17-25
- function_definition RandomIdGenerator @20-20

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/random_id_generator_factory.h

Blob: `a1915d3136f5320b80a96e89de78c5f87f20b1b3`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include "opentelemetry/sdk/trace/id_generator.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-30
- class_specifier RandomIdGeneratorFactory @20-27

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/recordable.h

Blob: `e12d069f808fff971a26aa3396d04f8ccfa5e4ec`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include "opentelemetry/common/attribute_value.h" @8
- include "opentelemetry/common/timestamp.h" @9
- include "opentelemetry/nostd/string_view.h" @10
- include "opentelemetry/sdk/common/empty_attributes.h" @11
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @12
- include "opentelemetry/sdk/trace/span_limits.h" @13
- include "opentelemetry/trace/span_context.h" @14
- include "opentelemetry/trace/span_id.h" @15
- include "opentelemetry/trace/span_metadata.h" @16
- include "opentelemetry/version.h" @17
- function_definition namespace @21-25
- class_specifier KeyValueIterable @24-24
- class_specifier Resource @31-31
- class_specifier SpanData @38-38
- class_specifier Recordable @45-200
- function_definition Recordable @48-48
- function_definition Recordable @50-50
- function_definition Recordable @51-51
- function_definition (anonymous) @52-52
- function_definition (anonymous) @53-53
- function_definition ~Recordable @55-55
- function_definition AddEvent @87-91
- function_definition AddEvent @98-101
- function_definition AddEvent @108-113
- function_definition AddLink @127-130
- function_definition SetTraceFlags @149-149
- function_definition SetSpanLimits @179-179
- function_definition (anonymous) @187-187

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/sampler.h

Blob: `888a44383b59148c6b63415c6b34c5766c53c279`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @6
- include <map> @7
- include <memory> @8
- include <string> @9
- include "opentelemetry/common/attribute_value.h" @11
- include "opentelemetry/nostd/shared_ptr.h" @12
- include "opentelemetry/nostd/string_view.h" @13
- include "opentelemetry/trace/span_metadata.h" @14
- include "opentelemetry/trace/trace_id.h" @15
- include "opentelemetry/version.h" @16
- function_definition namespace @18-22
- class_specifier KeyValueIterable @21-21
- class_specifier SpanContext @26-26
- class_specifier SpanContextKeyValueIterable @27-27
- class_specifier TraceState @28-28
- enum_specifier Decision @38-47
- struct_specifier SamplingResult @53-66
- function_definition IsRecording @61-64
- function_definition IsSampled @65-65
- class_specifier Sampler @72-113
- function_definition Sampler @75-75
- function_definition Sampler @77-77
- function_definition Sampler @78-78
- function_definition (anonymous) @79-79
- function_definition (anonymous) @80-80
- function_definition ~Sampler @82-82

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/samplers/always_on.h

Blob: `6b983008c7edaa8ba1f8ef97c3b3f0b6b3e5d052`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/nostd/string_view.h" @6
- include "opentelemetry/sdk/trace/sampler.h" @7
- include "opentelemetry/trace/span_context.h" @8
- include "opentelemetry/trace/span_metadata.h" @9
- include "opentelemetry/trace/trace_id.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-17
- class_specifier KeyValueIterable @16-16
- class_specifier SpanContextKeyValueIterable @21-21
- class_specifier AlwaysOnSampler @31-59
- function_definition ShouldSample @37-53
- function_definition GetDescription @58-58

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/samplers/always_on_factory.h

Blob: `80b38f8456ab653737c6c7be36db36b387e3f7f0`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include "opentelemetry/sdk/trace/sampler.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-30
- class_specifier AlwaysOnSamplerFactory @20-27

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/simple_processor.h

Blob: `19394e11c01d988a6e8a57cfb59941f2015fe0c5`. Grammar: cpp. Status: contains-errors.

- include <atomic> @6
- include <chrono> @7
- include <memory> @8
- include <mutex> @9
- include <utility> @10
- include "opentelemetry/common/spin_lock_mutex.h" @12
- include "opentelemetry/nostd/span.h" @13
- include "opentelemetry/sdk/common/exporter_utils.h" @14
- include "opentelemetry/sdk/trace/exporter.h" @15
- include "opentelemetry/sdk/trace/processor.h" @16
- include "opentelemetry/sdk/trace/recordable.h" @17
- include "opentelemetry/trace/span_context.h" @18
- include "opentelemetry/version.h" @19
- function_definition namespace @21-114
- class_specifier SimpleSpanProcessor @35-112
- function_definition SimpleSpanProcessor @42-44
- function_definition SimpleSpanProcessor @46-46
- function_definition SimpleSpanProcessor @47-47
- function_definition (anonymous) @48-48
- function_definition (anonymous) @49-49
- function_definition MakeRecordable @51-54
- function_definition OnStart @56-58
- function_definition OnEnd @60-70
- function_definition ForceFlush @72-81
- function_definition Shutdown @83-87
- function_definition ~SimpleSpanProcessor @89-89
- function_definition InternalShutdown @92-101

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/simple_processor_factory.h

Blob: `2ae40c2f7bdd60f8339a575687979f26d97ddab6`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include "opentelemetry/sdk/trace/exporter.h" @8
- include "opentelemetry/sdk/trace/processor.h" @9
- include "opentelemetry/version.h" @10
- function_definition namespace @12-31
- function_definition SimpleSpanProcessorFactory @21-28
- class_specifier OPENTELEMETRY_EXPORT @21-21

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/span_data.h

Blob: `e5869d8fc6618c89d5b36c03b71523c7870193ff`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <limits> @7
- include <map> @8
- include <memory> @9
- include <string> @10
- include <unordered_map> @11
- include <utility> @12
- include <vector> @13
- include "opentelemetry/common/attribute_value.h" @15
- include "opentelemetry/common/key_value_iterable.h" @16
- include "opentelemetry/common/key_value_iterable_view.h" @17
- include "opentelemetry/common/timestamp.h" @18
- include "opentelemetry/nostd/string_view.h" @19
- include "opentelemetry/sdk/common/attribute_utils.h" @20
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @21
- include "opentelemetry/sdk/resource/resource.h" @22
- include "opentelemetry/sdk/trace/recordable.h" @23
- include "opentelemetry/sdk/trace/span_limits.h" @24
- include "opentelemetry/trace/span_context.h" @25
- include "opentelemetry/trace/span_id.h" @26
- include "opentelemetry/trace/span_metadata.h" @27
- include "opentelemetry/trace/trace_flags.h" @28
- include "opentelemetry/trace/trace_id.h" @29
- include "opentelemetry/version.h" @30
- function_definition namespace @32-292
- class_specifier SpanDataEvent @40-80
- function_definition GetName @54-54
- function_definition GetTimestamp @60-60
- function_definition GetDroppedAttributesCount @73-73
- class_specifier SpanDataLink @85-118
- function_definition (anonymous) @105-105
- function_definition GetDroppedAttributesCount @112-112
- class_specifier SpanData @123-290
- function_definition SpanData @126-126
- function_definition GetTraceId @131-131
- function_definition GetSpanId @137-137
- function_definition (anonymous) @143-143
- function_definition GetParentSpanId @149-149
- function_definition GetName @155-155
- function_definition GetFlags @161-161
- function_definition GetSpanKind @167-167
- function_definition GetStatus @173-173
- function_definition GetDescription @179-179
- function_definition (anonymous) @194-197
- function_definition GetStartTime @203-203
- function_definition GetDuration @209-209
- function_definition (anonymous) @222-222
- function_definition (anonymous) @228-228
- function_definition GetDroppedAttributesCount @265-265
- function_definition GetDroppedEventsCount @267-267
- function_definition GetDroppedLinksCount @269-269

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/span_limits.h

Blob: `3f2db6e3cc29233b065cca011cb749eb22cb5180`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @6
- include <cstdint> @7
- include <limits> @8
- include "opentelemetry/version.h" @10
- function_definition namespace @12-67
- struct_specifier SpanLimits @22-64
- function_definition NoLimits @53-63

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer.h

Blob: `601cfc1b7c2b5693fc13da6dc1ec81a2c1602b59`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @6
- include <atomic> @8
- include <mutex> @9
- include "opentelemetry/common/key_value_iterable.h" @10
- include "opentelemetry/nostd/shared_ptr.h" @11
- include "opentelemetry/nostd/string_view.h" @12
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @13
- include "opentelemetry/sdk/resource/resource.h" @14
- include "opentelemetry/sdk/trace/id_generator.h" @15
- include "opentelemetry/sdk/trace/processor.h" @16
- include "opentelemetry/sdk/trace/sampler.h" @17
- include "opentelemetry/sdk/trace/span_limits.h" @18
- include "opentelemetry/sdk/trace/tracer_config.h" @19
- include "opentelemetry/sdk/trace/tracer_context.h" @20
- include "opentelemetry/trace/noop.h" @21
- include "opentelemetry/trace/span.h" @22
- include "opentelemetry/trace/span_context_kv_iterable.h" @23
- include "opentelemetry/trace/span_startoptions.h" @24
- include "opentelemetry/trace/tracer.h" @25
- include "opentelemetry/version.h" @26
- function_definition namespace @28-146
- class_specifier Tracer @36-144
- function_definition ForceFlush @57-61
- function_definition Close @70-74
- function_definition (anonymous) @85-85
- function_definition (anonymous) @88-88
- function_definition (anonymous) @91-91
- function_definition (anonymous) @94-97
- function_definition (anonymous) @100-103
- function_definition (anonymous) @106-106
- function_definition (anonymous) @109-109
- function_definition Enabled @113-113
- function_definition UpdateEnabled @117-120

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer_config.h

Blob: `9f67687dc8e32912dff92cc323279769c0ee9ee3`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/version.h" @6
- function_definition namespace @8-56
- function_definition TracerConfig @19-54
- class_specifier OPENTELEMETRY_EXPORT @19-19

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer_context.h

Blob: `f94972b8fe905f58e60dad1a9348e75659ded77e`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <memory> @7
- include <vector> @8
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @10
- include "opentelemetry/sdk/resource/resource.h" @11
- include "opentelemetry/sdk/trace/id_generator.h" @12
- include "opentelemetry/sdk/trace/processor.h" @13
- include "opentelemetry/sdk/trace/random_id_generator.h" @14
- include "opentelemetry/sdk/trace/sampler.h" @15
- include "opentelemetry/sdk/trace/samplers/always_on.h" @16
- include "opentelemetry/sdk/trace/span_limits.h" @17
- include "opentelemetry/sdk/trace/tracer_config.h" @18
- include "opentelemetry/version.h" @19
- function_definition namespace @21-144
- class_specifier TracerContext @40-141
- function_definition TracerContext @57-57
- function_definition TracerContext @58-58
- function_definition (anonymous) @59-59
- function_definition (anonymous) @60-60
- function_definition ~TracerContext @62-62

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer_context_factory.h

Blob: `0279bee93af342fcdfd8f8d8b9f617cd8a9519f0`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include <vector> @7
- include "opentelemetry/sdk/resource/resource.h" @9
- include "opentelemetry/sdk/trace/id_generator.h" @10
- include "opentelemetry/sdk/trace/processor.h" @11
- include "opentelemetry/sdk/trace/sampler.h" @12
- include "opentelemetry/sdk/trace/tracer_context.h" @13
- include "opentelemetry/version.h" @14
- function_definition namespace @16-70
- function_definition TracerContextFactory @25-67
- class_specifier OPENTELEMETRY_EXPORT @25-25

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer_provider.h

Blob: `5b9986a4c3ad97517fed85abd8563a6b9a0b3af1`. Grammar: cpp. Status: contains-errors.

- include <chrono> @6
- include <mutex> @7
- include <vector> @8
- include "opentelemetry/nostd/shared_ptr.h" @10
- include "opentelemetry/nostd/string_view.h" @11
- include "opentelemetry/sdk/resource/resource.h" @12
- include "opentelemetry/sdk/trace/id_generator.h" @13
- include "opentelemetry/sdk/trace/processor.h" @14
- include "opentelemetry/sdk/trace/random_id_generator.h" @15
- include "opentelemetry/sdk/trace/sampler.h" @16
- include "opentelemetry/sdk/trace/samplers/always_on.h" @17
- include "opentelemetry/sdk/trace/span_limits.h" @18
- include "opentelemetry/sdk/trace/tracer.h" @19
- include "opentelemetry/sdk/trace/tracer_context.h" @20
- include "opentelemetry/trace/tracer.h" @21
- include "opentelemetry/trace/tracer_provider.h" @22
- include "opentelemetry/version.h" @23
- function_definition namespace @25-160
- function_definition trace::TracerProvider @31-158
- class_specifier OPENTELEMETRY_EXPORT @31-31
- function_definition TracerProvider @79-81
- function_definition TracerProvider @82-82

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/trace/tracer_provider_factory.h

Blob: `81e0e36f01597f8efdf92a20753151975ac8ee21`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include <vector> @7
- include "opentelemetry/sdk/resource/resource.h" @9
- include "opentelemetry/sdk/trace/id_generator.h" @10
- include "opentelemetry/sdk/trace/processor.h" @11
- include "opentelemetry/sdk/trace/sampler.h" @12
- include "opentelemetry/sdk/trace/span_limits.h" @13
- include "opentelemetry/sdk/trace/tracer_context.h" @14
- include "opentelemetry/sdk/trace/tracer_provider.h" @15
- include "opentelemetry/trace/tracer_provider.h" @16
- include "opentelemetry/version.h" @17
- function_definition namespace @19-109
- function_definition TracerProviderFactory @29-106
- class_specifier OPENTELEMETRY_EXPORT @29-29

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk/version/version.h

Blob: `5924fa4b740164d8a8971c325e46ac479d377a67`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/version.h" @8
- function_definition namespace @10-24

### third_party/opentelemetry-cpp/sdk/include/opentelemetry/sdk_config.h

Blob: `afe78f1d80bab126166d0a7b95c91e3640abd10e`. Grammar: cpp. Status: syntax-clean.

- include "opentelemetry/sdk/common/global_log_handler.h" @6

### third_party/opentelemetry-cpp/sdk/src/common/base64.cc

Blob: `ce4e2f67222fc34dbed16c86e16da0c82803b612`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/common/base64.h" @4
- include <gsl/gsl> @7
- include <assert.h> @9
- include <cstring> @11
- include <limits> @12
- function_definition namespace @14-337
- function_definition Base64EscapeInternal @39-128
- function_definition Base64EscapeInternal @130-158
- function_definition Base64UnescapeInternal @160-280
- function_definition Base64Escape @289-298
- function_definition string Base64Escape @300-306
- function_definition Base64Unescape @308-334

### third_party/opentelemetry-cpp/sdk/src/common/disabled.cc

Blob: `b49eb922a1c61e2ee1c400aa9a50352b8990d5d2`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/common/disabled.h" @4
- include "opentelemetry/sdk/common/env_variables.h" @5
- include "opentelemetry/version.h" @6
- function_definition namespace @8-30
- function_definition GetSdkDisabled @14-27

### third_party/opentelemetry-cpp/sdk/src/common/empty_attributes.cc

Blob: `a1ccde5ffe863ace814d40de1fb92748a8a404ea`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @4
- include <array> @5
- include <string> @6
- include <utility> @7
- include "opentelemetry/common/key_value_iterable_view.h" @9
- include "opentelemetry/nostd/utility.h" @10
- include "opentelemetry/sdk/common/empty_attributes.h" @11
- include "opentelemetry/version.h" @12
- function_definition namespace @14-29
- function_definition (anonymous) @18-27

### third_party/opentelemetry-cpp/sdk/src/common/env_variables.cc

Blob: `75ceaf7822a5c8b39cbda1caa6c4c88be045ff53`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/common/env_variables.h" @4
- include <string.h> @7
- include <strings.h> @10
- include <cctype> @13
- include <cerrno> @14
- include <cstdlib> @15
- include <limits> @16
- include <ostream> @17
- include "opentelemetry/nostd/string_view.h" @19
- include "opentelemetry/sdk/common/global_log_handler.h" @20
- include "opentelemetry/version.h" @21
- function_definition namespace @23-284
- function_definition GetRawEnvironmentVariable @29-60
- function_definition GetBoolEnvironmentVariable @62-88
- function_definition GetTimeoutFromString @90-172
- function_definition GetDurationEnvironmentVariable @174-194
- function_definition GetStringEnvironmentVariable @196-204
- function_definition GetUintEnvironmentVariable @206-243
- function_definition GetFloatEnvironmentVariable @245-281

### third_party/opentelemetry-cpp/sdk/src/common/fast_random_number_generator.h

Blob: `66c9c06b63e8aa7d7a805a62d76d206cb5e1a191`. Grammar: cpp. Status: contains-errors.

- include <array> @6
- include <cstdint> @7
- include <limits> @8
- include "opentelemetry/version.h" @10
- function_definition namespace @12-81
- class_specifier FastRandomNumberGenerator @35-79
- function_definition FastRandomNumberGenerator @40-40
- function_definition FastRandomNumberGenerator @43-46
- function_definition operator() @48-62
- function_definition seed @67-71
- function_definition uint64_t @73-73
- function_definition uint64_t @75-75

### third_party/opentelemetry-cpp/sdk/src/common/global_log_handler.cc

Blob: `bd30262ba714ca756863da87345773a555065b78`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/common/global_log_handler.h" @4
- include <iostream> @6
- function_definition namespace @8-131
- struct_specifier GlobalLogHandlerData @18-34
- function_definition GlobalLogHandlerData @23-23
- function_definition ~GlobalLogHandlerData @24-24
- function_definition GlobalLogHandlerData @26-26
- function_definition GlobalLogHandlerData @27-27
- function_definition (anonymous) @29-29
- function_definition (anonymous) @30-30
- function_definition (anonymous) @38-42
- function_definition ~LogHandler @46-46
- function_definition Handle @48-81
- function_definition Handle @83-88
- function_definition GetLogHandler @90-98
- function_definition OPENTELEMETRY_UNLIKELY_CONDITION @92-95
- function_definition SetLogHandler @100-108
- function_definition OPENTELEMETRY_UNLIKELY_CONDITION @102-105
- function_definition GetLogLevel @110-118
- function_definition OPENTELEMETRY_UNLIKELY_CONDITION @112-115
- function_definition SetLogLevel @120-127
- function_definition OPENTELEMETRY_UNLIKELY_CONDITION @122-125

### third_party/opentelemetry-cpp/sdk/src/common/platform/fork.h

Blob: `b1a0e9d7798d99181cc0cc97914d9b2a3bf385b7`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/version.h" @6
- function_definition namespace @8-23

### third_party/opentelemetry-cpp/sdk/src/common/platform/fork_unix.cc

Blob: `41926bbfe7dbb576a3c1e4219ffa8f1a77fe560a`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/version.h" @4
- include "src/common/platform/fork.h" @5
- include <pthread.h> @7
- function_definition namespace @9-22
- function_definition AtFork @16-19

### third_party/opentelemetry-cpp/sdk/src/common/platform/fork_windows.cc

Blob: `9d9f2bf7916bc677e605df59684a8f02979c5025`. Grammar: cpp. Status: contains-errors.

- include "src/common/platform/fork.h" @4
- function_definition namespace @6-22
- function_definition AtFork @13-19

### third_party/opentelemetry-cpp/sdk/src/common/random.cc

Blob: `9b696dea656ac22ffa00a321e46e3367ae0432f2`. Grammar: cpp. Status: contains-errors.

- include "src/common/random.h" @5
- include "src/common/platform/fork.h" @6
- include <atomic> @8
- include <cstring> @9
- include <random> @10
- function_definition namespace @12-86
- class_specifier TlsRandomNumberGenerator @24-51
- function_definition TlsRandomNumberGenerator @27-34
- function_definition (anonymous) @36-36
- function_definition OnFork @43-43
- function_definition Seed @45-50
- function_definition (anonymous) @57-61
- function_definition GenerateRandom64 @63-66
- function_definition GenerateRandomBuffer @68-84

### third_party/opentelemetry-cpp/sdk/src/common/random.h

Blob: `28adbaf41c20a99e50cc7a106c041cf11b87bfb5`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @6
- include "opentelemetry/nostd/span.h" @8
- include "opentelemetry/version.h" @9
- include "src/common/fast_random_number_generator.h" @10
- function_definition namespace @12-42
- class_specifier Random @21-40

### third_party/opentelemetry-cpp/sdk/src/common/wildcard_match.h

Blob: `5a729944711419da96a13d74de784e318a486921`. Grammar: cpp. Status: contains-errors.

- include <cstddef> @6
- include <string> @7
- include "opentelemetry/version.h" @9
- function_definition namespace @11-62
- function_definition WildcardMatch @21-59

### third_party/opentelemetry-cpp/sdk/src/resource/resource.cc

Blob: `95b41498f8df9a5b5e6037b0ab9622972a3f9718`. Grammar: cpp. Status: contains-errors.

- include <string> @4
- include <unordered_map> @5
- include <utility> @6
- include "opentelemetry/nostd/variant.h" @8
- include "opentelemetry/sdk/resource/resource.h" @9
- include "opentelemetry/sdk/resource/resource_detector.h" @10
- include "opentelemetry/sdk/version/version.h" @11
- include "opentelemetry/semconv/incubating/process_attributes.h" @12
- include "opentelemetry/semconv/service_attributes.h" @13
- include "opentelemetry/semconv/telemetry_attributes.h" @14
- include "opentelemetry/version.h" @15
- function_definition namespace @17-88
- function_definition Resource @23-23
- function_definition Resource @25-27
- function_definition Resource @29-31
- function_definition Merge @33-39
- function_definition Create @41-59
- function_definition (anonymous) @61-65
- function_definition (anonymous) @67-75
- function_definition (anonymous) @77-80
- function_definition (anonymous) @82-85

### third_party/opentelemetry-cpp/sdk/src/resource/resource_detector.cc

Blob: `c96283a613fe9a1e98555a2e1d4bf9c180da8e41`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/resource/resource_detector.h" @4
- include "opentelemetry/nostd/variant.h" @5
- include "opentelemetry/sdk/common/env_variables.h" @6
- include "opentelemetry/sdk/resource/resource.h" @7
- include "opentelemetry/semconv/service_attributes.h" @8
- include "opentelemetry/version.h" @9
- include <stddef.h> @11
- include <sstream> @12
- include <string> @13
- function_definition namespace @15-71
- function_definition Create @24-28
- function_definition Detect @30-68

### third_party/opentelemetry-cpp/sdk/src/trace/exporter.cc

Blob: `5984583ba53ba065a188368b969d0c4512881ae2`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/trace/exporter.h" @4
- function_definition namespace @6-22
- function_definition SpanExporter @12-12
- function_definition ~SpanExporter @14-14
- function_definition ForceFlush @16-19

### third_party/opentelemetry-cpp/sdk/src/trace/multi_recordable.cc

Blob: `37959a8e1f666460ff0dab9f60ff95f7b7e8789d`. Grammar: cpp. Status: contains-errors.

- include <chrono> @4
- include <cstddef> @5
- include <map> @6
- include <memory> @7
- include <utility> @8
- include "opentelemetry/common/attribute_value.h" @10
- include "opentelemetry/common/timestamp.h" @11
- include "opentelemetry/nostd/string_view.h" @12
- include "opentelemetry/sdk/trace/multi_recordable.h" @13
- include "opentelemetry/sdk/trace/processor.h" @14
- include "opentelemetry/sdk/trace/recordable.h" @15
- include "opentelemetry/trace/span_id.h" @16
- include "opentelemetry/trace/trace_flags.h" @17
- include "opentelemetry/version.h" @18
- function_definition namespace @20-175
- function_definition MakeKey @26-29
- function_definition AddRecordable @31-35
- function_definition (anonymous) @37-48
- function_definition ReleaseRecordable @50-61
- function_definition SetIdentity @63-70
- function_definition SetSpanLimits @72-78
- function_definition SetAttribute @80-87
- function_definition AddEvent @89-97
- function_definition AddLink @99-106
- function_definition SetStatus @108-115
- function_definition SetName @117-123
- function_definition SetTraceFlags @125-131
- function_definition SetSpanKind @133-139
- function_definition SetResource @141-147
- function_definition SetStartTime @149-155
- function_definition SetDuration @157-163
- function_definition SetInstrumentationScope @165-172

### third_party/opentelemetry-cpp/sdk/src/trace/provider.cc

Blob: `ff27c409611ee9fd7a7a43bc1860e01a2574b59d`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/trace/provider.h" @4
- include "opentelemetry/nostd/shared_ptr.h" @5
- include "opentelemetry/sdk/common/disabled.h" @6
- include "opentelemetry/sdk/trace/provider.h" @7
- include "opentelemetry/trace/tracer_provider.h" @8
- include "opentelemetry/version.h" @9
- function_definition namespace @11-29
- function_definition SetTracerProvider @17-26

### third_party/opentelemetry-cpp/sdk/src/trace/random_id_generator.cc

Blob: `f09fa81141e40276134cd0e4dcab7ac3d096bd64`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @4
- include "opentelemetry/nostd/span.h" @6
- include "opentelemetry/sdk/trace/random_id_generator.h" @7
- include "opentelemetry/trace/span_id.h" @8
- include "opentelemetry/trace/trace_id.h" @9
- include "opentelemetry/version.h" @10
- include "src/common/random.h" @11
- function_definition namespace @13-34
- function_definition GenerateSpanId @20-25
- function_definition GenerateTraceId @27-32

### third_party/opentelemetry-cpp/sdk/src/trace/random_id_generator_factory.cc

Blob: `9bf0818664b8f2c6adfd1811bda97a9ac5709960`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/trace/random_id_generator_factory.h" @4
- include "opentelemetry/sdk/trace/random_id_generator.h" @5
- include "opentelemetry/version.h" @6
- function_definition namespace @8-21
- function_definition Create @14-18

### third_party/opentelemetry-cpp/sdk/src/trace/samplers/always_on_factory.cc

Blob: `a803596b9c0f172642841ae49d0b529fd40e9a13`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/trace/samplers/always_on_factory.h" @4
- include "opentelemetry/sdk/trace/samplers/always_on.h" @5
- include "opentelemetry/version.h" @6
- function_definition namespace @8-21
- function_definition Create @14-18

### third_party/opentelemetry-cpp/sdk/src/trace/simple_processor_factory.cc

Blob: `7e567d22cfc2b49f26367431657ea352ca61b856`. Grammar: cpp. Status: contains-errors.

- include <memory> @4
- include <utility> @5
- include "opentelemetry/sdk/trace/exporter.h" @7
- include "opentelemetry/sdk/trace/processor.h" @8
- include "opentelemetry/sdk/trace/simple_processor.h" @9
- include "opentelemetry/sdk/trace/simple_processor_factory.h" @10
- include "opentelemetry/version.h" @11
- function_definition namespace @13-26
- function_definition Create @18-23

### third_party/opentelemetry-cpp/sdk/src/trace/span.cc

Blob: `1233e3361df1d36c92236da620bbc2ca230d22fd`. Grammar: cpp. Status: contains-errors.

- include <chrono> @4
- include <utility> @5
- include "opentelemetry/nostd/function_ref.h" @7
- include "opentelemetry/sdk/trace/processor.h" @8
- include "opentelemetry/sdk/trace/recordable.h" @9
- include "opentelemetry/trace/span_id.h" @10
- include "opentelemetry/trace/span_metadata.h" @11
- include "opentelemetry/trace/trace_flags.h" @12
- include "opentelemetry/version.h" @13
- include "src/trace/span.h" @14
- function_definition namespace @16-232
- function_definition NowOr @28-38
- function_definition NowOr @40-50
- function_definition Span @53-94
- function_definition ~Span @96-99
- function_definition SetAttribute @101-110
- function_definition AddEvent @112-120
- function_definition AddEvent @122-130
- function_definition AddEvent @132-140
- function_definition AddEvent @142-152
- function_definition AddLink @155-165
- function_definition AddLinks @167-180
- function_definition SetStatus @183-191
- function_definition UpdateName @193-201
- function_definition End @203-224
- function_definition IsRecording @226-230

### third_party/opentelemetry-cpp/sdk/src/trace/span.h

Blob: `2a5614821daac57b53fc5e900865e84b07122d63`. Grammar: cpp. Status: contains-errors.

- include <memory> @6
- include <mutex> @7
- include "opentelemetry/common/attribute_value.h" @9
- include "opentelemetry/common/key_value_iterable.h" @10
- include "opentelemetry/common/timestamp.h" @11
- include "opentelemetry/nostd/string_view.h" @12
- include "opentelemetry/sdk/trace/recordable.h" @13
- include "opentelemetry/sdk/trace/tracer.h" @14
- include "opentelemetry/trace/span.h" @15
- include "opentelemetry/trace/span_context.h" @16
- include "opentelemetry/trace/span_context_kv_iterable.h" @17
- include "opentelemetry/trace/span_startoptions.h" @18
- include "opentelemetry/version.h" @19
- function_definition namespace @21-90
- class_specifier Span @26-88
- function_definition Span @37-37
- function_definition Span @38-38
- function_definition (anonymous) @39-39
- function_definition (anonymous) @40-40
- function_definition GetContext @76-79

### third_party/opentelemetry-cpp/sdk/src/trace/span_data.cc

Blob: `e4d42fae4f302d8ccc21ae627c1b5339070b0500`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @4
- include <chrono> @5
- include <cstddef> @6
- include <cstdint> @7
- include <memory> @8
- include <string> @9
- include <unordered_map> @10
- include <utility> @11
- include <vector> @12
- include "opentelemetry/common/attribute_value.h" @14
- include "opentelemetry/common/key_value_iterable.h" @15
- include "opentelemetry/common/timestamp.h" @16
- include "opentelemetry/nostd/function_ref.h" @17
- include "opentelemetry/nostd/string_view.h" @18
- include "opentelemetry/nostd/variant.h" @19
- include "opentelemetry/sdk/common/attribute_utils.h" @20
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @21
- include "opentelemetry/sdk/resource/resource.h" @22
- include "opentelemetry/sdk/trace/span_data.h" @23
- include "opentelemetry/sdk/trace/span_limits.h" @24
- include "opentelemetry/trace/span_context.h" @25
- include "opentelemetry/trace/span_id.h" @26
- include "opentelemetry/trace/trace_flags.h" @27
- include "opentelemetry/version.h" @28
- function_definition namespace @30-250
- function_definition SetAttributeImpl @39-66
- function_definition CreateAttributeMap @70-90
- function_definition SpanDataEvent @94-103
- function_definition (anonymous) @105-109
- function_definition SpanDataLink @111-119
- function_definition (anonymous) @121-125
- function_definition (anonymous) @127-137
- function_definition (anonymous) @139-152
- function_definition (anonymous) @154-158
- function_definition SetIdentity @160-165
- function_definition SetAttribute @167-175
- function_definition AddEvent @177-188
- function_definition AddLink @190-200
- function_definition SetSpanLimits @202-205
- function_definition SetStatus @207-212
- function_definition SetName @214-217
- function_definition SetTraceFlags @219-222
- function_definition SetSpanKind @224-227
- function_definition SetResource @229-232
- function_definition SetStartTime @234-237
- function_definition SetDuration @239-242
- function_definition SetInstrumentationScope @244-247

### third_party/opentelemetry-cpp/sdk/src/trace/tracer.cc

Blob: `b0f0e593e86fdaf767fff4c2857ff9fbaf9a2e53`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @4
- include <chrono> @5
- include <map> @6
- include <mutex> @7
- include <new> @8
- include <utility> @9
- include "opentelemetry/context/context.h" @11
- include "opentelemetry/nostd/shared_ptr.h" @12
- include "opentelemetry/nostd/string_view.h" @13
- include "opentelemetry/nostd/variant.h" @14
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @15
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @16
- include "opentelemetry/sdk/trace/id_generator.h" @17
- include "opentelemetry/sdk/trace/sampler.h" @18
- include "opentelemetry/sdk/trace/tracer.h" @19
- include "opentelemetry/sdk/trace/tracer_config.h" @20
- include "opentelemetry/sdk/trace/tracer_context.h" @21
- include "opentelemetry/trace/context.h" @22
- include "opentelemetry/trace/noop.h" @23
- include "opentelemetry/trace/span.h" @24
- include "opentelemetry/trace/span_context.h" @25
- include "opentelemetry/trace/span_id.h" @26
- include "opentelemetry/trace/span_startoptions.h" @27
- include "opentelemetry/trace/trace_flags.h" @28
- include "opentelemetry/trace/trace_id.h" @29
- include "opentelemetry/trace/trace_state.h" @30
- include "opentelemetry/version.h" @31
- include "src/trace/span.h" @33
- function_definition namespace @35-211
- function_definition Tracer @40-47
- function_definition StartSpan @49-178
- function_definition ForceFlushWithMicroseconds @180-187
- function_definition CloseWithMicroseconds @189-198
- function_definition UpdateTracerConfig @200-208

### third_party/opentelemetry-cpp/sdk/src/trace/tracer_config.cc

Blob: `26f0b21fecfec7dcb87a6f5578fff5593e395734`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/trace/tracer_config.h" @4
- function_definition namespace @6-40
- function_definition TracerConfig::Disabled @12-16
- function_definition TracerConfig::Enabled @18-21
- function_definition TracerConfig::Default @23-27
- function_definition IsEnabled @29-32
- function_definition operator== @34-37

### third_party/opentelemetry-cpp/sdk/src/trace/tracer_context.cc

Blob: `43bdabc93b300c613749d35de2c1c26e08fd0162`. Grammar: cpp. Status: contains-errors.

- include <chrono> @4
- include <memory> @5
- include <utility> @6
- include <vector> @7
- include "opentelemetry/sdk/common/global_log_handler.h" @9
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @10
- include "opentelemetry/sdk/resource/resource.h" @11
- include "opentelemetry/sdk/trace/id_generator.h" @12
- include "opentelemetry/sdk/trace/multi_span_processor.h" @13
- include "opentelemetry/sdk/trace/processor.h" @14
- include "opentelemetry/sdk/trace/sampler.h" @15
- include "opentelemetry/sdk/trace/span_limits.h" @16
- include "opentelemetry/sdk/trace/tracer_config.h" @17
- include "opentelemetry/sdk/trace/tracer_context.h" @18
- include "opentelemetry/version.h" @19
- function_definition namespace @21-104
- function_definition TracerContext @28-41
- function_definition (anonymous) @43-46
- function_definition (anonymous) @48-51
- function_definition (anonymous) @53-57
- function_definition (anonymous) @59-62
- function_definition (anonymous) @64-67
- function_definition AddProcessor @69-73
- function_definition SetTracerConfigurator @75-86
- function_definition (anonymous) @88-91
- function_definition ForceFlush @93-96
- function_definition Shutdown @98-101

### third_party/opentelemetry-cpp/sdk/src/trace/tracer_context_factory.cc

Blob: `9472dc041f44aad93c7ff353b74ab16561ef4309`. Grammar: cpp. Status: contains-errors.

- include <memory> @4
- include <utility> @5
- include <vector> @6
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @8
- include "opentelemetry/sdk/resource/resource.h" @9
- include "opentelemetry/sdk/trace/id_generator.h" @10
- include "opentelemetry/sdk/trace/processor.h" @11
- include "opentelemetry/sdk/trace/random_id_generator_factory.h" @12
- include "opentelemetry/sdk/trace/sampler.h" @13
- include "opentelemetry/sdk/trace/samplers/always_on_factory.h" @14
- include "opentelemetry/sdk/trace/tracer_config.h" @15
- include "opentelemetry/sdk/trace/tracer_context.h" @16
- include "opentelemetry/sdk/trace/tracer_context_factory.h" @17
- include "opentelemetry/version.h" @18
- function_definition namespace @20-78
- function_definition Create @26-31
- function_definition Create @33-39
- function_definition Create @41-48
- function_definition Create @50-62
- function_definition Create @64-75

### third_party/opentelemetry-cpp/sdk/src/trace/tracer_provider.cc

Blob: `47d3bb98b9a03b93ca1a086fed769fa4e97e124b`. Grammar: cpp. Status: contains-errors.

- include <chrono> @4
- include <mutex> @5
- include <utility> @6
- include <vector> @7
- include "opentelemetry/common/key_value_iterable.h" @9
- include "opentelemetry/nostd/shared_ptr.h" @10
- include "opentelemetry/nostd/string_view.h" @11
- include "opentelemetry/sdk/common/global_log_handler.h" @12
- include "opentelemetry/sdk/instrumentationscope/instrumentation_scope.h" @13
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @14
- include "opentelemetry/sdk/resource/resource.h" @15
- include "opentelemetry/sdk/trace/id_generator.h" @16
- include "opentelemetry/sdk/trace/processor.h" @17
- include "opentelemetry/sdk/trace/sampler.h" @18
- include "opentelemetry/sdk/trace/span_limits.h" @19
- include "opentelemetry/sdk/trace/tracer.h" @20
- include "opentelemetry/sdk/trace/tracer_config.h" @21
- include "opentelemetry/sdk/trace/tracer_context.h" @22
- include "opentelemetry/sdk/trace/tracer_provider.h" @23
- include "opentelemetry/version.h" @24
- function_definition namespace @26-183
- function_definition TracerProvider @34-38
- function_definition TracerProvider @40-53
- function_definition TracerProvider @55-68
- function_definition ~TracerProvider @70-79
- function_definition GetTracer @88-126
- function_definition AddProcessor @128-131
- function_definition UpdateTracerConfigurator @133-161
- function_definition (anonymous) @163-166
- function_definition (anonymous) @168-171
- function_definition Shutdown @173-176
- function_definition ForceFlush @178-181

### third_party/opentelemetry-cpp/sdk/src/trace/tracer_provider_factory.cc

Blob: `06f792c6598b07079c54b7549b87bfab2fba5290`. Grammar: cpp. Status: contains-errors.

- include <memory> @4
- include <utility> @5
- include <vector> @6
- include "opentelemetry/sdk/instrumentationscope/scope_configurator.h" @8
- include "opentelemetry/sdk/resource/resource.h" @9
- include "opentelemetry/sdk/trace/id_generator.h" @10
- include "opentelemetry/sdk/trace/processor.h" @11
- include "opentelemetry/sdk/trace/random_id_generator_factory.h" @12
- include "opentelemetry/sdk/trace/sampler.h" @13
- include "opentelemetry/sdk/trace/samplers/always_on_factory.h" @14
- include "opentelemetry/sdk/trace/span_limits.h" @15
- include "opentelemetry/sdk/trace/tracer_config.h" @16
- include "opentelemetry/sdk/trace/tracer_context.h" @17
- include "opentelemetry/sdk/trace/tracer_provider.h" @18
- include "opentelemetry/sdk/trace/tracer_provider_factory.h" @19
- include "opentelemetry/version.h" @20
- function_definition namespace @22-165
- function_definition Create @28-33
- function_definition Create @35-41
- function_definition Create @43-50
- function_definition Create @52-64
- function_definition Create @66-75
- function_definition Create @77-90
- function_definition Create @92-97
- function_definition Create @99-105
- function_definition Create @107-114
- function_definition Create @116-128
- function_definition Create @130-139
- function_definition Create @141-154
- function_definition Create @156-162

### third_party/opentelemetry-cpp/sdk/src/version/version.cc

Blob: `7504c6c2f2b130d2a41b8f7eb862cdeaf127d2a3`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/sdk/version/version.h" @7
- function_definition namespace @9-28

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry.proto.collector.trace.v1.rs

Blob: `bf778b143faaeb1c29a7ecbda1b1d7fa22872c79`. Grammar: rust. Status: syntax-clean.

- struct_item ExportTraceServiceRequest @3-13
- struct_item ExportTraceServiceResponse @15-33
- struct_item ExportTracePartialSuccess @35-51

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry.proto.common.v1.rs

Blob: `61c059a7b5ae4d9ffd080021fdc02d6d8e84d6c5`. Grammar: rust. Status: syntax-clean.

- struct_item AnyValue @6-11
- mod_item any_value @13-33
- enum_item Value @17-32
- struct_item ArrayValue @37-41
- struct_item KeyValueList @48-55
- struct_item KeyValue @59-64
- struct_item InstrumentationScope @68-81
- struct_item EntityRef @87-116

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry.proto.resource.v1.rs

Blob: `50099d127afe026f2768e3ec8c4168431718baf0`. Grammar: rust. Status: syntax-clean.

- struct_item Resource @4-31

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry.proto.trace.v1.rs

Blob: `61cb737943e5e902d3f594a5a277b22a7c5cda15`. Grammar: rust. Status: syntax-clean.

- struct_item TracesData @13-21
- struct_item ResourceSpans @24-40
- struct_item ScopeSpans @43-59
- struct_item Span @64-193
- mod_item span @195-350
- struct_item Event @199-228
- struct_item Link @234-285
- enum_item SpanKind @300-321
- function_item as_str_name @327-336
- function_item from_str_name @338-348
- struct_item Status @354-361
- mod_item status @363-409
- enum_item StatusCode @378-386
- function_item as_str_name @392-398
- function_item from_str_name @400-407
- enum_item SpanFlags @426-437
- function_item as_str_name @443-450
- function_item from_str_name @452-460

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/collector/trace/v1/trace_service.pb.cc

Blob: `4b83586e7dbae76cbd5a2064b11e0bcd50c84854`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/proto/collector/trace/v1/trace_service.pb.h" @6
- include <algorithm> @8
- include <type_traits> @9
- include "google/protobuf/io/coded_stream.h" @10
- include "google/protobuf/generated_message_tctable_impl.h" @11
- include "google/protobuf/internal_visibility.h" @12
- include "google/protobuf/extension_set.h" @13
- include "google/protobuf/generated_message_util.h" @14
- include "google/protobuf/wire_format_lite.h" @15
- include "google/protobuf/io/zero_copy_stream_impl_lite.h" @16
- include "google/protobuf/port_def.inc" @20
- class_specifier ExportTracePartialSuccess::_Internal @30-35
- function_definition InternalGenerateParseTable_ @37-79
- function_definition Impl_::Impl_ @82-88
- function_definition ExportTracePartialSuccess @91-99
- function_definition ExportTracePartialSuccess::PlacementNew_ @100-104
- function_definition InternalNewImpl_ @105-107
- function_definition InternalGenerateClassData_ @108-132
- function_definition _default @137-137
- function_definition _default @142-142
- function_definition _table @143-147
- function_definition ~ExportTracePartialSuccessGlobalsTypeInternal @148-148
- function_definition (anonymous) @166-174
- function_definition ExportTracePartialSuccess_get_class_data @167-173
- class_specifier ExportTraceServiceResponse::_Internal @176-181
- function_definition ExportTraceServiceResponse @183-222
- function_definition Impl_::Impl_ @225-228
- function_definition ExportTraceServiceResponse @231-239
- function_definition PlacementNew_ @240-244
- function_definition ExportTraceServiceResponse @245-247
- function_definition ExportTraceServiceResponse @248-272
- function_definition _default @277-277
- function_definition _default @282-282
- function_definition _table @283-287
- function_definition ~ExportTraceServiceResponseGlobalsTypeInternal @288-288
- function_definition (anonymous) @306-314
- function_definition ExportTraceServiceResponse_get_class_data @307-313
- class_specifier ExportTraceServiceRequest::_Internal @316-321
- function_definition ExportTraceServiceRequest @323-362
- function_definition Impl_::Impl_ @365-372
- function_definition ExportTraceServiceRequest @375-383
- function_definition PlacementNew_ @384-388
- function_definition ExportTraceServiceRequest @389-391
- function_definition ExportTraceServiceRequest @392-416
- function_definition _default @421-421
- function_definition _default @426-426
- function_definition _table @427-431
- function_definition ~ExportTraceServiceRequestGlobalsTypeInternal @432-432
- function_definition (anonymous) @450-458
- function_definition ExportTraceServiceRequest_get_class_data @451-457
- function_definition clear_resource_spans @472-476
- function_definition Super_ @481-485
- function_definition Super_ @506-515
- function_definition SharedCtor @525-527
- function_definition ~ExportTraceServiceRequest @528-531
- function_definition SharedDtor @532-540
- function_definition GetClassData @549-551
- function_definition GetClassData @554-556
- function_definition Clear @564-576
- function_definition ExportTraceServiceRequest::_InternalSerialize @584-616
- function_definition ByteSizeLong @622-646
- function_definition MergeImpl @648-670
- function_definition CopyFrom @672-677
- function_definition Super_ @693-697
- function_definition Super_ @711-724
- function_definition Impl_::Impl_ @725-728
- function_definition SharedCtor @730-733
- function_definition ~ExportTraceServiceResponse @734-737
- function_definition SharedDtor @738-747
- function_definition GetClassData @756-758
- function_definition GetClassData @761-763
- function_definition Clear @771-784
- function_definition ExportTraceServiceResponse::_InternalSerialize @792-819
- function_definition ByteSizeLong @825-846
- function_definition MergeImpl @848-873
- function_definition CopyFrom @875-880
- function_definition Super_ @896-900
- function_definition Super_ @915-925
- function_definition error_message_ @926-929
- function_definition SharedCtor @931-934
- function_definition ~ExportTracePartialSuccess @935-938
- function_definition SharedDtor @939-948
- function_definition GetClassData @957-959
- function_definition GetClassData @962-964
- function_definition Clear @972-985
- function_definition ExportTracePartialSuccess::_InternalSerialize @993-1032
- function_definition ByteSizeLong @1035-1124
- function_definition ByteSizeLong @1038-1069
- function_definition MergeImpl @1071-1103
- function_definition CopyFrom @1105-1110
- include "google/protobuf/port_undef.inc" @1134

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/collector/trace/v1/trace_service.pb.h

Blob: `010c6c78f7a77208716ec516a626e97e2ca1fbe4`. Grammar: cpp. Status: contains-errors.

- include <limits> @9
- include <string> @10
- include <type_traits> @11
- include <utility> @12
- include "google/protobuf/runtime_version.h" @15
- include "google/protobuf/io/coded_stream.h" @21
- include "google/protobuf/arena.h" @22
- include "google/protobuf/arenastring.h" @23
- include "google/protobuf/generated_message_tctable_decl.h" @24
- include "google/protobuf/generated_message_util.h" @25
- include "google/protobuf/metadata_lite.h" @26
- include "google/protobuf/message_lite.h" @27
- include "google/protobuf/repeated_field.h" @28
- include "google/protobuf/extension_set.h" @29
- include "opentelemetry/proto/trace/v1/trace.pb.h" @30
- include "google/protobuf/port_def.inc" @34
- struct_specifier TableStruct_opentelemetry_2fproto_2fcollector_2ftrace_2fv1_2ftrace_5fservice_2eproto @39-41
- class_specifier ExportTracePartialSuccess @47-47
- struct_specifier ExportTracePartialSuccessGlobalsTypeInternal @48-48
- class_specifier ExportTraceServiceRequest @55-55
- struct_specifier ExportTraceServiceRequestGlobalsTypeInternal @56-56
- class_specifier ExportTraceServiceResponse @63-63
- struct_specifier ExportTraceServiceResponseGlobalsTypeInternal @64-64
- function_definition google::protobuf::MessageLite @92-203
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @92-92
- function_definition ExportTracePartialSuccess @112-112
- function_definition ExportTracePartialSuccess @113-113
- function_definition (anonymous) @114-117
- function_definition (anonymous) @118-126
- function_definition (anonymous) @128-131
- function_definition mutable_unknown_fields @132-135
- function_definition (anonymous) @137-139
- function_definition swap @141-141
- function_definition MergeFrom @163-163
- function_definition GetCachedSize @194-196
- function_definition ExportTracePartialSuccess @205-211
- enum_specifier (anonymous) @226-229
- class_specifier _Internal @257-257
- struct_specifier Impl_ @276-294
- function_definition google::protobuf::MessageLite @297-408
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @297-297
- function_definition ExportTraceServiceResponse @317-317
- function_definition ExportTraceServiceResponse @318-318
- function_definition (anonymous) @319-322
- function_definition (anonymous) @323-331
- function_definition (anonymous) @333-336
- function_definition mutable_unknown_fields @337-340
- function_definition (anonymous) @342-344
- function_definition swap @346-346
- function_definition MergeFrom @368-368
- function_definition GetCachedSize @399-401
- function_definition ExportTraceServiceResponse @410-416
- enum_specifier (anonymous) @431-433
- class_specifier _Internal @451-451
- struct_specifier Impl_ @470-487
- function_definition google::protobuf::MessageLite @490-601
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @490-490
- function_definition ExportTraceServiceRequest @510-510
- function_definition ExportTraceServiceRequest @511-511
- function_definition (anonymous) @512-515
- function_definition (anonymous) @516-524
- function_definition (anonymous) @526-529
- function_definition mutable_unknown_fields @530-533
- function_definition (anonymous) @535-537
- function_definition swap @539-539
- function_definition MergeFrom @561-561
- function_definition GetCachedSize @592-594
- function_definition ExportTraceServiceRequest @603-609
- enum_specifier (anonymous) @624-626
- class_specifier _Internal @649-649
- struct_specifier Impl_ @668-685
- function_definition _internal_resource_spans_size @704-706
- function_definition resource_spans_size @707-709
- function_definition (anonymous) @710-714
- function_definition ExportTraceServiceRequest::mutable_resource_spans @715-719
- function_definition ExportTraceServiceRequest::add_resource_spans @720-729
- function_definition (anonymous) @730-734
- function_definition ExportTraceServiceRequest::mutable_resource_spans @735-741
- function_definition (anonymous) @742-746
- function_definition ExportTraceServiceRequest::_internal_mutable_resource_spans @747-751
- function_definition has_partial_success @758-762
- function_definition clear_partial_success @763-767
- function_definition (anonymous) @768-772
- function_definition (anonymous) @773-776
- function_definition unsafe_arena_set_allocated_partial_success @777-790
- function_definition ExportTraceServiceResponse::release_partial_success @791-809
- function_definition ExportTraceServiceResponse::unsafe_arena_release_partial_success @810-818
- function_definition ExportTraceServiceResponse::_internal_mutable_partial_success @819-826
- function_definition ExportTraceServiceResponse::mutable_partial_success @827-833
- function_definition set_allocated_partial_success @834-853
- function_definition clear_rejected_spans @860-864
- function_definition rejected_spans @865-868
- function_definition set_rejected_spans @869-873
- function_definition _internal_rejected_spans @874-877
- function_definition _internal_set_rejected_spans @878-881
- function_definition clear_error_message @884-888
- function_definition (anonymous) @889-893
- function_definition set_error_message @895-900
- function_definition ExportTracePartialSuccess::mutable_error_message @901-907
- function_definition (anonymous) @908-911
- function_definition _internal_set_error_message @912-915
- function_definition ExportTracePartialSuccess::_internal_mutable_error_message @916-919
- function_definition ExportTracePartialSuccess::release_error_message @920-932
- function_definition set_allocated_error_message @933-945
- include "google/protobuf/port_undef.inc" @961

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/common/v1/common.pb.cc

Blob: `327327d98a17c89cb87f9d98b76158b1d95ac8f3`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/proto/common/v1/common.pb.h" @6
- include <algorithm> @8
- include <type_traits> @9
- include "google/protobuf/io/coded_stream.h" @10
- include "google/protobuf/generated_message_tctable_impl.h" @11
- include "google/protobuf/internal_visibility.h" @12
- include "google/protobuf/extension_set.h" @13
- include "google/protobuf/generated_message_util.h" @14
- include "google/protobuf/wire_format_lite.h" @15
- include "google/protobuf/io/zero_copy_stream_impl_lite.h" @16
- include "google/protobuf/port_def.inc" @20
- class_specifier EntityRef::_Internal @29-34
- function_definition InternalGenerateParseTable_ @36-93
- function_definition Impl_::Impl_ @96-114
- function_definition EntityRef @117-125
- function_definition PlacementNew_ @126-130
- function_definition InternalNewImpl_ @131-133
- function_definition InternalGenerateClassData_ @134-158
- function_definition _default @163-163
- function_definition _default @168-168
- function_definition _table @169-173
- function_definition ~EntityRefGlobalsTypeInternal @174-174
- function_definition (anonymous) @192-200
- function_definition EntityRef_get_class_data @193-199
- class_specifier AnyValue::_Internal @202-206
- function_definition AnyValue @208-270
- function_definition Impl_::Impl_ @273-277
- function_definition AnyValue @280-288
- function_definition PlacementNew_ @289-293
- function_definition AnyValue @294-296
- function_definition AnyValue @297-321
- function_definition _default @326-326
- function_definition _default @331-331
- function_definition _table @332-336
- function_definition ~AnyValueGlobalsTypeInternal @337-337
- function_definition (anonymous) @355-363
- function_definition AnyValue_get_class_data @356-362
- class_specifier ArrayValue::_Internal @365-370
- function_definition ArrayValue @372-411
- function_definition Impl_::Impl_ @414-421
- function_definition ArrayValue @424-432
- function_definition PlacementNew_ @433-437
- function_definition ArrayValue @438-440
- function_definition ArrayValue @441-465
- function_definition _default @470-470
- function_definition _default @475-475
- function_definition _table @476-480
- function_definition ~ArrayValueGlobalsTypeInternal @481-481
- function_definition (anonymous) @499-507
- function_definition ArrayValue_get_class_data @500-506
- class_specifier KeyValue::_Internal @509-514
- function_definition KeyValue @516-564
- function_definition Impl_::Impl_ @567-573
- function_definition KeyValue @576-584
- function_definition PlacementNew_ @585-589
- function_definition KeyValue @590-592
- function_definition KeyValue @593-617
- function_definition _default @622-622
- function_definition _default @627-627
- function_definition _table @628-632
- function_definition ~KeyValueGlobalsTypeInternal @633-633
- function_definition (anonymous) @651-659
- function_definition KeyValue_get_class_data @652-658
- class_specifier KeyValueList::_Internal @661-666
- function_definition KeyValueList @668-707
- function_definition Impl_::Impl_ @710-717
- function_definition KeyValueList @720-728
- function_definition PlacementNew_ @729-733
- function_definition KeyValueList @734-736
- function_definition KeyValueList @737-761
- function_definition _default @766-766
- function_definition _default @771-771
- function_definition _table @772-776
- function_definition ~KeyValueListGlobalsTypeInternal @777-777
- function_definition (anonymous) @795-803
- function_definition KeyValueList_get_class_data @796-802
- class_specifier InstrumentationScope::_Internal @805-810
- function_definition InstrumentationScope @812-873
- function_definition Impl_::Impl_ @876-890
- function_definition InstrumentationScope @893-901
- function_definition PlacementNew_ @902-906
- function_definition InstrumentationScope @907-909
- function_definition InstrumentationScope @910-934
- function_definition _default @939-939
- function_definition _default @944-944
- function_definition _table @945-949
- function_definition ~InstrumentationScopeGlobalsTypeInternal @950-950
- function_definition (anonymous) @968-976
- function_definition InstrumentationScope_get_class_data @969-975
- function_definition set_allocated_array_value @988-1000
- function_definition set_allocated_kvlist_value @1001-1013
- function_definition Super_ @1018-1022
- function_definition Super_ @1037-1071
- function_definition SharedCtor @1078-1080
- function_definition ~AnyValue @1081-1084
- function_definition SharedDtor @1085-1096
- function_definition clear_value @1098-1147
- function_definition GetClassData @1157-1159
- function_definition GetClassData @1162-1164
- function_definition Clear @1172-1180
- function_definition AnyValue::_InternalSerialize @1188-1253
- function_definition ByteSizeLong @1259-1317
- function_definition MergeImpl @1319-1392
- function_definition CopyFrom @1394-1399
- function_definition Super_ @1415-1419
- function_definition Super_ @1440-1449
- function_definition SharedCtor @1459-1461
- function_definition ~ArrayValue @1462-1465
- function_definition SharedDtor @1466-1474
- function_definition GetClassData @1483-1485
- function_definition GetClassData @1488-1490
- function_definition Clear @1498-1510
- function_definition ArrayValue::_InternalSerialize @1518-1550
- function_definition ByteSizeLong @1556-1580
- function_definition MergeImpl @1582-1604
- function_definition CopyFrom @1606-1611
- function_definition Super_ @1627-1631
- function_definition Super_ @1652-1661
- function_definition SharedCtor @1671-1673
- function_definition ~KeyValueList @1674-1677
- function_definition SharedDtor @1678-1686
- function_definition GetClassData @1695-1697
- function_definition GetClassData @1700-1702
- function_definition Clear @1710-1722
- function_definition KeyValueList::_InternalSerialize @1730-1762
- function_definition ByteSizeLong @1768-1792
- function_definition MergeImpl @1794-1816
- function_definition CopyFrom @1818-1823
- function_definition Super_ @1839-1843
- function_definition Super_ @1858-1871
- function_definition key_ @1872-1875
- function_definition SharedCtor @1877-1880
- function_definition ~KeyValue @1881-1884
- function_definition SharedDtor @1885-1895
- function_definition GetClassData @1904-1906
- function_definition GetClassData @1909-1911
- function_definition Clear @1919-1937
- function_definition KeyValue::_InternalSerialize @1945-1982
- function_definition ByteSizeLong @1988-2017
- function_definition MergeImpl @2019-2055
- function_definition CopyFrom @2057-2062
- function_definition Super_ @2081-2085
- function_definition Super_ @2108-2118
- function_definition SharedCtor @2130-2133
- function_definition ~InstrumentationScope @2134-2137
- function_definition SharedDtor @2138-2148
- function_definition GetClassData @2157-2159
- function_definition GetClassData @2162-2164
- function_definition Clear @2172-2193
- function_definition InstrumentationScope::_InternalSerialize @2201-2262
- function_definition ByteSizeLong @2268-2313
- function_definition MergeImpl @2315-2362
- function_definition CopyFrom @2364-2369
- function_definition Super_ @2390-2394
- function_definition Super_ @2424-2433
- function_definition SharedCtor @2450-2452
- function_definition ~EntityRef @2453-2456
- function_definition SharedDtor @2457-2467
- function_definition GetClassData @2476-2478
- function_definition GetClassData @2481-2483
- function_definition Clear @2491-2514
- function_definition EntityRef::_InternalSerialize @2522-2582
- function_definition ByteSizeLong @2585-2709
- function_definition ByteSizeLong @2588-2637
- function_definition MergeImpl @2639-2686
- function_definition CopyFrom @2688-2693
- include "google/protobuf/port_undef.inc" @2718

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/common/v1/common.pb.h

Blob: `dbc7d727eb93a925913496dc571a7fa69192321e`. Grammar: cpp. Status: contains-errors.

- include <limits> @9
- include <string> @10
- include <type_traits> @11
- include <utility> @12
- include "google/protobuf/runtime_version.h" @15
- include "google/protobuf/io/coded_stream.h" @21
- include "google/protobuf/arena.h" @22
- include "google/protobuf/arenastring.h" @23
- include "google/protobuf/generated_message_tctable_decl.h" @24
- include "google/protobuf/generated_message_util.h" @25
- include "google/protobuf/metadata_lite.h" @26
- include "google/protobuf/message_lite.h" @27
- include "google/protobuf/repeated_field.h" @28
- include "google/protobuf/extension_set.h" @29
- include "google/protobuf/port_def.inc" @33
- struct_specifier TableStruct_opentelemetry_2fproto_2fcommon_2fv1_2fcommon_2eproto @38-40
- class_specifier AnyValue @45-45
- struct_specifier AnyValueGlobalsTypeInternal @46-46
- class_specifier ArrayValue @53-53
- struct_specifier ArrayValueGlobalsTypeInternal @54-54
- class_specifier EntityRef @61-61
- struct_specifier EntityRefGlobalsTypeInternal @62-62
- class_specifier InstrumentationScope @69-69
- struct_specifier InstrumentationScopeGlobalsTypeInternal @70-70
- class_specifier KeyValue @77-77
- struct_specifier KeyValueGlobalsTypeInternal @78-78
- class_specifier KeyValueList @85-85
- struct_specifier KeyValueListGlobalsTypeInternal @86-86
- function_definition google::protobuf::MessageLite @112-223
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @112-112
- function_definition EntityRef @132-132
- function_definition EntityRef @133-133
- function_definition (anonymous) @134-137
- function_definition (anonymous) @138-146
- function_definition (anonymous) @148-151
- function_definition mutable_unknown_fields @152-155
- function_definition (anonymous) @157-159
- function_definition swap @161-161
- function_definition MergeFrom @183-183
- function_definition GetCachedSize @214-216
- function_definition EntityRef @225-231
- enum_specifier (anonymous) @246-251
- class_specifier _Internal @336-336
- struct_specifier Impl_ @355-375
- function_definition google::protobuf::MessageLite @378-499
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @378-378
- function_definition AnyValue @398-398
- function_definition AnyValue @399-399
- function_definition (anonymous) @400-403
- function_definition (anonymous) @404-412
- function_definition (anonymous) @414-417
- function_definition mutable_unknown_fields @418-421
- function_definition (anonymous) @423-425
- enum_specifier ValueCase @426-435
- function_definition swap @437-437
- function_definition MergeFrom @459-459
- function_definition GetCachedSize @490-492
- function_definition AnyValue @501-507
- enum_specifier (anonymous) @522-530
- class_specifier _Internal @638-638
- struct_specifier Impl_ @666-693
- function_definition ValueUnion @677-677
- function_definition google::protobuf::MessageLite @696-807
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @696-696
- function_definition ArrayValue @716-716
- function_definition ArrayValue @717-717
- function_definition (anonymous) @718-721
- function_definition (anonymous) @722-730
- function_definition (anonymous) @732-735
- function_definition mutable_unknown_fields @736-739
- function_definition (anonymous) @741-743
- function_definition swap @745-745
- function_definition MergeFrom @767-767
- function_definition GetCachedSize @798-800
- function_definition ArrayValue @809-815
- enum_specifier (anonymous) @830-832
- class_specifier _Internal @855-855
- struct_specifier Impl_ @874-891
- function_definition google::protobuf::MessageLite @894-1005
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @894-894
- function_definition KeyValue @914-914
- function_definition KeyValue @915-915
- function_definition (anonymous) @916-919
- function_definition (anonymous) @920-928
- function_definition (anonymous) @930-933
- function_definition mutable_unknown_fields @934-937
- function_definition (anonymous) @939-941
- function_definition swap @943-943
- function_definition MergeFrom @965-965
- function_definition GetCachedSize @996-998
- function_definition KeyValue @1007-1013
- enum_specifier (anonymous) @1028-1031
- class_specifier _Internal @1064-1064
- struct_specifier Impl_ @1083-1101
- function_definition google::protobuf::MessageLite @1104-1215
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @1104-1104
- function_definition KeyValueList @1124-1124
- function_definition KeyValueList @1125-1125
- function_definition (anonymous) @1126-1129
- function_definition (anonymous) @1130-1138
- function_definition (anonymous) @1140-1143
- function_definition mutable_unknown_fields @1144-1147
- function_definition (anonymous) @1149-1151
- function_definition swap @1153-1153
- function_definition MergeFrom @1175-1175
- function_definition GetCachedSize @1206-1208
- function_definition KeyValueList @1217-1223
- enum_specifier (anonymous) @1238-1240
- class_specifier _Internal @1263-1263
- struct_specifier Impl_ @1282-1299
- function_definition google::protobuf::MessageLite @1302-1413
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @1302-1302
- function_definition InstrumentationScope @1322-1322
- function_definition InstrumentationScope @1323-1323
- function_definition (anonymous) @1324-1327
- function_definition (anonymous) @1328-1336
- function_definition (anonymous) @1338-1341
- function_definition mutable_unknown_fields @1342-1345
- function_definition (anonymous) @1347-1349
- function_definition swap @1351-1351
- function_definition MergeFrom @1373-1373
- function_definition GetCachedSize @1404-1406
- function_definition InstrumentationScope @1415-1421
- enum_specifier (anonymous) @1436-1441
- class_specifier _Internal @1504-1504
- struct_specifier Impl_ @1523-1543
- function_definition has_string_value @1562-1564
- function_definition set_has_string_value @1565-1567
- function_definition clear_string_value @1568-1574
- function_definition (anonymous) @1575-1579
- function_definition set_string_value @1581-1591
- function_definition mutable_string_value @1592-1603
- function_definition (anonymous) @1604-1610
- function_definition _internal_set_string_value @1611-1614
- function_definition _internal_mutable_string_value @1615-1618
- function_definition release_string_value @1619-1627
- function_definition set_allocated_string_value @1628-1638
- function_definition has_bool_value @1641-1643
- function_definition set_has_bool_value @1644-1646
- function_definition clear_bool_value @1647-1653
- function_definition bool_value @1654-1657
- function_definition set_bool_value @1658-1665
- function_definition _internal_bool_value @1666-1671
- function_definition has_int_value @1674-1676
- function_definition set_has_int_value @1677-1679
- function_definition clear_int_value @1680-1686
- function_definition int_value @1687-1690
- function_definition set_int_value @1691-1698
- function_definition _internal_int_value @1699-1704
- function_definition has_double_value @1707-1709
- function_definition set_has_double_value @1710-1712
- function_definition clear_double_value @1713-1719
- function_definition double_value @1720-1723
- function_definition set_double_value @1724-1731
- function_definition _internal_double_value @1732-1737
- function_definition has_array_value @1740-1742
- function_definition _internal_has_array_value @1743-1745
- function_definition set_has_array_value @1746-1748
- function_definition clear_array_value @1749-1761
- function_definition release_array_value @1762-1775
- function_definition (anonymous) @1776-1779
- function_definition (anonymous) @1780-1783
- function_definition unsafe_arena_release_array_value @1784-1794
- function_definition unsafe_arena_set_allocated_array_value @1795-1806
- function_definition _internal_mutable_array_value @1807-1814
- function_definition mutable_array_value @1815-1820
- function_definition has_kvlist_value @1823-1825
- function_definition _internal_has_kvlist_value @1826-1828
- function_definition set_has_kvlist_value @1829-1831
- function_definition clear_kvlist_value @1832-1844
- function_definition release_kvlist_value @1845-1858
- function_definition (anonymous) @1859-1862
- function_definition (anonymous) @1863-1866
- function_definition unsafe_arena_release_kvlist_value @1867-1877
- function_definition unsafe_arena_set_allocated_kvlist_value @1878-1889
- function_definition _internal_mutable_kvlist_value @1890-1897
- function_definition mutable_kvlist_value @1898-1903
- function_definition has_bytes_value @1906-1908
- function_definition set_has_bytes_value @1909-1911
- function_definition clear_bytes_value @1912-1918
- function_definition (anonymous) @1919-1923
- function_definition set_bytes_value @1925-1935
- function_definition mutable_bytes_value @1936-1947
- function_definition (anonymous) @1948-1954
- function_definition _internal_set_bytes_value @1955-1958
- function_definition _internal_mutable_bytes_value @1959-1962
- function_definition release_bytes_value @1963-1971
- function_definition set_allocated_bytes_value @1972-1982
- function_definition has_value @1984-1986
- function_definition clear_has_value @1987-1989
- function_definition value_case @1990-1992
- function_definition _internal_values_size @1998-2000
- function_definition values_size @2001-2003
- function_definition clear_values @2004-2008
- function_definition (anonymous) @2009-2013
- function_definition mutable_values @2014-2018
- function_definition add_values @2019-2028
- function_definition (anonymous) @2029-2033
- function_definition mutable_values @2034-2040
- function_definition (anonymous) @2041-2045
- function_definition _internal_mutable_values @2046-2050
- function_definition _internal_values_size @2057-2059
- function_definition values_size @2060-2062
- function_definition clear_values @2063-2067
- function_definition (anonymous) @2068-2072
- function_definition KeyValueList::mutable_values @2073-2077
- function_definition KeyValueList::add_values @2078-2087
- function_definition (anonymous) @2088-2092
- function_definition KeyValueList::mutable_values @2093-2099
- function_definition (anonymous) @2100-2104
- function_definition KeyValueList::_internal_mutable_values @2105-2109
- function_definition clear_key @2116-2120
- function_definition (anonymous) @2121-2125
- function_definition set_key @2127-2132
- function_definition mutable_key @2133-2139
- function_definition (anonymous) @2140-2143
- function_definition _internal_set_key @2144-2147
- function_definition _internal_mutable_key @2148-2151
- function_definition release_key @2152-2164
- function_definition set_allocated_key @2165-2177
- function_definition has_value @2180-2184
- function_definition clear_value @2185-2189
- function_definition (anonymous) @2190-2194
- function_definition (anonymous) @2195-2198
- function_definition unsafe_arena_set_allocated_value @2199-2212
- function_definition release_value @2213-2231
- function_definition unsafe_arena_release_value @2232-2240
- function_definition _internal_mutable_value @2241-2248
- function_definition mutable_value @2249-2255
- function_definition set_allocated_value @2256-2275
- function_definition clear_name @2282-2286
- function_definition (anonymous) @2287-2291
- function_definition set_name @2293-2298
- function_definition InstrumentationScope::mutable_name @2299-2305
- function_definition (anonymous) @2306-2309
- function_definition _internal_set_name @2310-2313
- function_definition InstrumentationScope::_internal_mutable_name @2314-2317
- function_definition InstrumentationScope::release_name @2318-2330
- function_definition set_allocated_name @2331-2343
- function_definition clear_version @2346-2350
- function_definition (anonymous) @2351-2355
- function_definition set_version @2357-2362
- function_definition InstrumentationScope::mutable_version @2363-2369
- function_definition (anonymous) @2370-2373
- function_definition _internal_set_version @2374-2377
- function_definition InstrumentationScope::_internal_mutable_version @2378-2381
- function_definition InstrumentationScope::release_version @2382-2394
- function_definition set_allocated_version @2395-2407
- function_definition _internal_attributes_size @2410-2412
- function_definition attributes_size @2413-2415
- function_definition clear_attributes @2416-2420
- function_definition (anonymous) @2421-2425
- function_definition InstrumentationScope::mutable_attributes @2426-2430
- function_definition InstrumentationScope::add_attributes @2431-2440
- function_definition (anonymous) @2441-2445
- function_definition InstrumentationScope::mutable_attributes @2446-2452
- function_definition (anonymous) @2453-2457
- function_definition InstrumentationScope::_internal_mutable_attributes @2458-2462
- function_definition clear_dropped_attributes_count @2465-2469
- function_definition dropped_attributes_count @2470-2473
- function_definition set_dropped_attributes_count @2474-2478
- function_definition _internal_dropped_attributes_count @2479-2482
- function_definition _internal_set_dropped_attributes_count @2483-2486
- function_definition clear_schema_url @2493-2497
- function_definition (anonymous) @2498-2502
- function_definition set_schema_url @2504-2509
- function_definition mutable_schema_url @2510-2516
- function_definition (anonymous) @2517-2520
- function_definition _internal_set_schema_url @2521-2524
- function_definition _internal_mutable_schema_url @2525-2528
- function_definition release_schema_url @2529-2541
- function_definition set_allocated_schema_url @2542-2554
- function_definition clear_type @2557-2561
- function_definition (anonymous) @2562-2566
- function_definition set_type @2568-2573
- function_definition mutable_type @2574-2580
- function_definition (anonymous) @2581-2584
- function_definition _internal_set_type @2585-2588
- function_definition _internal_mutable_type @2589-2592
- function_definition release_type @2593-2605
- function_definition set_allocated_type @2606-2618
- function_definition _internal_id_keys_size @2621-2623
- function_definition id_keys_size @2624-2626
- function_definition clear_id_keys @2627-2631
- function_definition add_id_keys @2632-2641
- function_definition (anonymous) @2642-2646
- function_definition mutable_id_keys @2647-2651
- function_definition set_id_keys @2653-2658
- function_definition add_id_keys @2660-2668
- function_definition (anonymous) @2669-2673
- function_definition mutable_id_keys @2674-2680
- function_definition (anonymous) @2681-2685
- function_definition _internal_mutable_id_keys @2686-2690
- function_definition _internal_description_keys_size @2693-2695
- function_definition description_keys_size @2696-2698
- function_definition clear_description_keys @2699-2703
- function_definition add_description_keys @2704-2713
- function_definition (anonymous) @2714-2718
- function_definition mutable_description_keys @2719-2723
- function_definition set_description_keys @2725-2730
- function_definition add_description_keys @2732-2740
- function_definition (anonymous) @2741-2745
- function_definition mutable_description_keys @2746-2752
- function_definition (anonymous) @2753-2757
- function_definition _internal_mutable_description_keys @2758-2762
- include "google/protobuf/port_undef.inc" @2777

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/resource/v1/resource.pb.cc

Blob: `7b803e9647fb2a50319d21b8cb3eb7948401c7ae`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/proto/resource/v1/resource.pb.h" @6
- include <algorithm> @8
- include <type_traits> @9
- include "google/protobuf/io/coded_stream.h" @10
- include "google/protobuf/generated_message_tctable_impl.h" @11
- include "google/protobuf/internal_visibility.h" @12
- include "google/protobuf/extension_set.h" @13
- include "google/protobuf/generated_message_util.h" @14
- include "google/protobuf/wire_format_lite.h" @15
- include "google/protobuf/io/zero_copy_stream_impl_lite.h" @16
- include "google/protobuf/port_def.inc" @20
- class_specifier Resource::_Internal @29-34
- function_definition InternalGenerateParseTable_ @36-93
- function_definition Impl_::Impl_ @96-109
- function_definition Resource @112-120
- function_definition PlacementNew_ @121-125
- function_definition InternalNewImpl_ @126-128
- function_definition InternalGenerateClassData_ @129-153
- function_definition _default @158-158
- function_definition _default @163-163
- function_definition _table @164-168
- function_definition ~ResourceGlobalsTypeInternal @169-169
- function_definition (anonymous) @187-195
- function_definition Resource_get_class_data @188-194
- function_definition clear_attributes @207-211
- function_definition clear_entity_refs @212-216
- function_definition Super_ @221-225
- function_definition Super_ @253-263
- function_definition SharedCtor @278-281
- function_definition ~Resource @282-285
- function_definition SharedDtor @286-294
- function_definition GetClassData @303-305
- function_definition GetClassData @308-310
- function_definition Clear @318-336
- function_definition Resource::_InternalSerialize @344-397
- function_definition ByteSizeLong @400-497
- function_definition ByteSizeLong @403-441
- function_definition MergeImpl @443-477
- function_definition CopyFrom @479-484
- include "google/protobuf/port_undef.inc" @506

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/resource/v1/resource.pb.h

Blob: `e2ecd857a09386cb3d33e3fffcdee9592ade67ed`. Grammar: cpp. Status: contains-errors.

- include <limits> @9
- include <string> @10
- include <type_traits> @11
- include <utility> @12
- include "google/protobuf/runtime_version.h" @15
- include "google/protobuf/io/coded_stream.h" @21
- include "google/protobuf/arena.h" @22
- include "google/protobuf/arenastring.h" @23
- include "google/protobuf/generated_message_tctable_decl.h" @24
- include "google/protobuf/generated_message_util.h" @25
- include "google/protobuf/metadata_lite.h" @26
- include "google/protobuf/message_lite.h" @27
- include "google/protobuf/repeated_field.h" @28
- include "google/protobuf/extension_set.h" @29
- include "opentelemetry/proto/common/v1/common.pb.h" @30
- include "google/protobuf/port_def.inc" @34
- struct_specifier TableStruct_opentelemetry_2fproto_2fresource_2fv1_2fresource_2eproto @39-41
- class_specifier Resource @46-46
- struct_specifier ResourceGlobalsTypeInternal @47-47
- function_definition google::protobuf::MessageLite @73-184
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @73-73
- function_definition Resource @93-93
- function_definition Resource @94-94
- function_definition (anonymous) @95-98
- function_definition (anonymous) @99-107
- function_definition (anonymous) @109-112
- function_definition mutable_unknown_fields @113-116
- function_definition (anonymous) @118-120
- function_definition swap @122-122
- function_definition MergeFrom @144-144
- function_definition GetCachedSize @175-177
- function_definition Resource @186-192
- enum_specifier (anonymous) @207-211
- class_specifier _Internal @264-264
- struct_specifier Impl_ @283-302
- function_definition _internal_attributes_size @321-323
- function_definition attributes_size @324-326
- function_definition (anonymous) @327-331
- function_definition mutable_attributes @332-336
- function_definition add_attributes @337-346
- function_definition (anonymous) @347-351
- function_definition mutable_attributes @352-358
- function_definition (anonymous) @359-363
- function_definition _internal_mutable_attributes @364-368
- function_definition clear_dropped_attributes_count @371-375
- function_definition dropped_attributes_count @376-379
- function_definition set_dropped_attributes_count @380-384
- function_definition _internal_dropped_attributes_count @385-388
- function_definition _internal_set_dropped_attributes_count @389-392
- function_definition _internal_entity_refs_size @395-397
- function_definition entity_refs_size @398-400
- function_definition (anonymous) @401-405
- function_definition mutable_entity_refs @406-410
- function_definition add_entity_refs @411-420
- function_definition (anonymous) @421-425
- function_definition mutable_entity_refs @426-432
- function_definition (anonymous) @433-437
- function_definition _internal_mutable_entity_refs @438-442
- include "google/protobuf/port_undef.inc" @457

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/trace/v1/trace.pb.cc

Blob: `a4218aa52dd047742f0b81c246c5e2ed1189b945`. Grammar: cpp. Status: contains-errors.

- include "opentelemetry/proto/trace/v1/trace.pb.h" @6
- include <algorithm> @8
- include <type_traits> @9
- include "google/protobuf/io/coded_stream.h" @10
- include "google/protobuf/generated_message_tctable_impl.h" @11
- include "google/protobuf/internal_visibility.h" @12
- include "google/protobuf/extension_set.h" @13
- include "google/protobuf/generated_message_util.h" @14
- include "google/protobuf/wire_format_lite.h" @15
- include "google/protobuf/io/zero_copy_stream_impl_lite.h" @16
- include "google/protobuf/port_def.inc" @20
- class_specifier Status::_Internal @29-34
- function_definition InternalGenerateParseTable_ @36-78
- function_definition Impl_::Impl_ @81-87
- function_definition Status @90-98
- function_definition PlacementNew_ @99-103
- function_definition InternalNewImpl_ @104-106
- function_definition InternalGenerateClassData_ @107-131
- function_definition _default @136-136
- function_definition _default @141-141
- function_definition _table @142-146
- function_definition ~StatusGlobalsTypeInternal @147-147
- function_definition (anonymous) @165-173
- function_definition Status_get_class_data @166-172
- class_specifier Span_Link::_Internal @175-180
- function_definition Span_Link @182-256
- function_definition Impl_::Impl_ @259-277
- function_definition Span_Link @280-288
- function_definition PlacementNew_ @289-293
- function_definition Span_Link @294-296
- function_definition Span_Link @297-321
- function_definition _default @326-326
- function_definition _default @331-331
- function_definition _table @332-336
- function_definition ~Span_LinkGlobalsTypeInternal @337-337
- function_definition (anonymous) @355-363
- function_definition Span_Link_get_class_data @356-362
- class_specifier Span_Event::_Internal @365-370
- function_definition Span_Event @372-432
- function_definition Impl_::Impl_ @435-447
- function_definition Span_Event @450-458
- function_definition PlacementNew_ @459-463
- function_definition Span_Event @464-466
- function_definition Span_Event @467-491
- function_definition _default @496-496
- function_definition _default @501-501
- function_definition _table @502-506
- function_definition ~Span_EventGlobalsTypeInternal @507-507
- function_definition (anonymous) @525-533
- function_definition Span_Event_get_class_data @526-532
- class_specifier Span::_Internal @535-540
- function_definition Span @542-690
- function_definition Impl_::Impl_ @693-733
- function_definition Span @736-744
- function_definition PlacementNew_ @745-749
- function_definition Span @750-752
- function_definition Span @753-777
- function_definition _default @782-782
- function_definition _default @787-787
- function_definition _table @788-792
- function_definition ~SpanGlobalsTypeInternal @793-793
- function_definition (anonymous) @811-819
- function_definition Span_get_class_data @812-818
- class_specifier ScopeSpans::_Internal @821-826
- function_definition ScopeSpans @828-888
- function_definition Impl_::Impl_ @891-902
- function_definition ScopeSpans @905-913
- function_definition PlacementNew_ @914-918
- function_definition ScopeSpans @919-921
- function_definition ScopeSpans @922-946
- function_definition _default @951-951
- function_definition _default @956-956
- function_definition _table @957-961
- function_definition ~ScopeSpansGlobalsTypeInternal @962-962
- function_definition (anonymous) @980-988
- function_definition ScopeSpans_get_class_data @981-987
- class_specifier ResourceSpans::_Internal @990-995
- function_definition ResourceSpans @997-1057
- function_definition Impl_::Impl_ @1060-1071
- function_definition ResourceSpans @1074-1082
- function_definition PlacementNew_ @1083-1087
- function_definition ResourceSpans @1088-1090
- function_definition ResourceSpans @1091-1115
- function_definition _default @1120-1120
- function_definition _default @1125-1125
- function_definition _table @1126-1130
- function_definition ~ResourceSpansGlobalsTypeInternal @1131-1131
- function_definition (anonymous) @1149-1157
- function_definition ResourceSpans_get_class_data @1150-1156
- class_specifier TracesData::_Internal @1159-1164
- function_definition TracesData @1166-1205
- function_definition Impl_::Impl_ @1208-1215
- function_definition TracesData @1218-1226
- function_definition PlacementNew_ @1227-1231
- function_definition TracesData @1232-1234
- function_definition TracesData @1235-1259
- function_definition _default @1264-1264
- function_definition _default @1269-1269
- function_definition _table @1270-1274
- function_definition ~TracesDataGlobalsTypeInternal @1275-1275
- function_definition (anonymous) @1293-1301
- function_definition TracesData_get_class_data @1294-1300
- function_definition Span_SpanKind_Parse @1340-1349
- function_definition (anonymous) @1353-1363
- function_definition Status_StatusCode_Parse @1384-1393
- function_definition (anonymous) @1397-1407
- function_definition SpanFlags_Parse @1431-1440
- function_definition (anonymous) @1444-1454
- function_definition Super_ @1461-1465
- function_definition Super_ @1486-1495
- function_definition SharedCtor @1505-1507
- function_definition ~TracesData @1508-1511
- function_definition SharedDtor @1512-1520
- function_definition GetClassData @1529-1531
- function_definition GetClassData @1534-1536
- function_definition Clear @1544-1556
- function_definition TracesData::_InternalSerialize @1564-1596
- function_definition ByteSizeLong @1602-1626
- function_definition MergeImpl @1628-1650
- function_definition CopyFrom @1652-1657
- function_definition clear_resource @1669-1673
- function_definition Super_ @1678-1682
- function_definition Super_ @1704-1717
- function_definition SharedCtor @1728-1731
- function_definition ~ResourceSpans @1732-1735
- function_definition SharedDtor @1736-1746
- function_definition GetClassData @1755-1757
- function_definition GetClassData @1760-1762
- function_definition Clear @1770-1791
- function_definition ResourceSpans::_InternalSerialize @1799-1848
- function_definition ByteSizeLong @1854-1890
- function_definition MergeImpl @1892-1933
- function_definition CopyFrom @1935-1940
- function_definition clear_scope @1956-1960
- function_definition Super_ @1965-1969
- function_definition Super_ @1991-2004
- function_definition SharedCtor @2015-2018
- function_definition ~ScopeSpans @2019-2022
- function_definition SharedDtor @2023-2033
- function_definition GetClassData @2042-2044
- function_definition GetClassData @2047-2049
- function_definition Clear @2057-2078
- function_definition ScopeSpans::_InternalSerialize @2086-2135
- function_definition ByteSizeLong @2141-2177
- function_definition MergeImpl @2179-2220
- function_definition CopyFrom @2222-2227
- function_definition clear_attributes @2243-2247
- function_definition Super_ @2252-2256
- function_definition Super_ @2278-2294
- function_definition SharedCtor @2305-2313
- function_definition ~Span_Event @2314-2317
- function_definition SharedDtor @2318-2327
- function_definition GetClassData @2336-2338
- function_definition GetClassData @2341-2343
- function_definition Clear @2351-2375
- function_definition Span_Event::_InternalSerialize @2383-2443
- function_definition ByteSizeLong @2449-2493
- function_definition MergeImpl @2495-2538
- function_definition CopyFrom @2540-2545
- function_definition clear_attributes @2566-2570
- function_definition Super_ @2575-2579
- function_definition Super_ @2603-2619
- function_definition SharedCtor @2632-2640
- function_definition ~Span_Link @2641-2644
- function_definition SharedDtor @2645-2656
- function_definition GetClassData @2665-2667
- function_definition GetClassData @2670-2672
- function_definition Clear @2680-2710
- function_definition Span_Link::_InternalSerialize @2718-2794
- function_definition ByteSizeLong @2800-2858
- function_definition MergeImpl @2860-2921
- function_definition CopyFrom @2923-2928
- function_definition clear_attributes @2951-2955
- function_definition Super_ @2960-2964
- function_definition Super_ @3004-3024
- function_definition SharedCtor @3049-3057
- function_definition ~Span @3058-3061
- function_definition SharedDtor @3062-3076
- function_definition GetClassData @3085-3087
- function_definition GetClassData @3090-3092
- function_definition Clear @3100-3146
- function_definition Span::_InternalSerialize @3154-3324
- function_definition ByteSizeLong @3330-3456
- function_definition MergeImpl @3458-3582
- function_definition CopyFrom @3584-3589
- function_definition Super_ @3620-3624
- function_definition Super_ @3639-3649
- function_definition message_ @3650-3653
- function_definition SharedCtor @3655-3658
- function_definition ~Status @3659-3662
- function_definition SharedDtor @3663-3672
- function_definition GetClassData @3681-3683
- function_definition GetClassData @3686-3688
- function_definition Clear @3696-3709
- function_definition Status::_InternalSerialize @3717-3756
- function_definition ByteSizeLong @3759-3848
- function_definition ByteSizeLong @3762-3793
- function_definition MergeImpl @3795-3827
- function_definition CopyFrom @3829-3834
- include "google/protobuf/port_undef.inc" @3857

### third_party/opentelemetry-cpp/third_party/opentelemetry-proto/opentelemetry/proto/trace/v1/trace.pb.h

Blob: `dad24332cb49e5ec85c174aa60fdaccff7081894`. Grammar: cpp. Status: contains-errors.

- include <limits> @9
- include <string> @10
- include <type_traits> @11
- include <utility> @12
- include "google/protobuf/runtime_version.h" @15
- include "google/protobuf/io/coded_stream.h" @21
- include "google/protobuf/arena.h" @22
- include "google/protobuf/arenastring.h" @23
- include "google/protobuf/generated_message_tctable_decl.h" @24
- include "google/protobuf/generated_message_util.h" @25
- include "google/protobuf/metadata_lite.h" @26
- include "google/protobuf/message_lite.h" @27
- include "google/protobuf/repeated_field.h" @28
- include "google/protobuf/extension_set.h" @29
- include "google/protobuf/generated_enum_util.h" @30
- include "opentelemetry/proto/common/v1/common.pb.h" @31
- include "opentelemetry/proto/resource/v1/resource.pb.h" @32
- include "google/protobuf/port_def.inc" @36
- struct_specifier TableStruct_opentelemetry_2fproto_2ftrace_2fv1_2ftrace_2eproto @41-43
- enum_specifier SpanFlags @48-48
- enum_specifier Span_SpanKind @50-50
- enum_specifier Status_StatusCode @52-52
- class_specifier ResourceSpans @54-54
- struct_specifier ResourceSpansGlobalsTypeInternal @55-55
- class_specifier ScopeSpans @62-62
- struct_specifier ScopeSpansGlobalsTypeInternal @63-63
- class_specifier Span @70-70
- struct_specifier SpanGlobalsTypeInternal @71-71
- class_specifier Span_Event @78-78
- struct_specifier Span_EventGlobalsTypeInternal @79-79
- class_specifier Span_Link @86-86
- struct_specifier Span_LinkGlobalsTypeInternal @87-87
- class_specifier Status @94-94
- struct_specifier StatusGlobalsTypeInternal @95-95
- class_specifier TracesData @102-102
- struct_specifier TracesDataGlobalsTypeInternal @103-103
- enum_specifier Span_SpanKind @132-143
- function_definition Span_SpanKind_IsValid @150-152
- function_definition (anonymous) @156-161
- enum_specifier Status_StatusCode @164-172
- function_definition Status_StatusCode_IsValid @179-181
- function_definition (anonymous) @185-190
- enum_specifier SpanFlags @193-202
- function_definition SpanFlags_IsValid @209-211
- function_definition (anonymous) @215-220
- function_definition google::protobuf::MessageLite @231-342
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @231-231
- function_definition Status @251-251
- function_definition Status @252-252
- function_definition (anonymous) @253-256
- function_definition (anonymous) @257-265
- function_definition (anonymous) @267-270
- function_definition mutable_unknown_fields @271-274
- function_definition (anonymous) @276-278
- function_definition swap @280-280
- function_definition MergeFrom @302-302
- function_definition GetCachedSize @333-335
- function_definition Status @344-350
- function_definition StatusCode_IsValid @367-369
- function_definition (anonymous) @374-376
- function_definition StatusCode_Parse @377-380
- enum_specifier (anonymous) @383-386
- class_specifier _Internal @414-414
- struct_specifier Impl_ @433-451
- function_definition google::protobuf::MessageLite @454-565
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @454-454
- function_definition Span_Link @474-474
- function_definition Span_Link @475-475
- function_definition (anonymous) @476-479
- function_definition (anonymous) @480-488
- function_definition (anonymous) @490-493
- function_definition mutable_unknown_fields @494-497
- function_definition (anonymous) @499-501
- function_definition swap @503-503
- function_definition MergeFrom @525-525
- function_definition GetCachedSize @556-558
- function_definition Span_Link @567-573
- enum_specifier (anonymous) @588-595
- class_specifier _Internal @683-683
- struct_specifier Impl_ @702-724
- function_definition google::protobuf::MessageLite @727-838
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @727-727
- function_definition Span_Event @747-747
- function_definition Span_Event @748-748
- function_definition (anonymous) @749-752
- function_definition (anonymous) @753-761
- function_definition (anonymous) @763-766
- function_definition mutable_unknown_fields @767-770
- function_definition (anonymous) @772-774
- function_definition swap @776-776
- function_definition MergeFrom @798-798
- function_definition GetCachedSize @829-831
- function_definition Span_Event @840-846
- enum_specifier (anonymous) @861-866
- class_specifier _Internal @924-924
- struct_specifier Impl_ @943-963
- function_definition google::protobuf::MessageLite @966-1077
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @966-966
- function_definition Span @986-986
- function_definition Span @987-987
- function_definition (anonymous) @988-991
- function_definition (anonymous) @992-1000
- function_definition (anonymous) @1002-1005
- function_definition mutable_unknown_fields @1006-1009
- function_definition (anonymous) @1011-1013
- function_definition swap @1015-1015
- function_definition MergeFrom @1037-1037
- function_definition GetCachedSize @1068-1070
- function_definition Span @1079-1085
- function_definition SpanKind_IsValid @1107-1109
- function_definition (anonymous) @1114-1116
- function_definition SpanKind_Parse @1117-1120
- enum_specifier (anonymous) @1123-1140
- class_specifier _Internal @1363-1363
- struct_specifier Impl_ @1382-1414
- function_definition google::protobuf::MessageLite @1417-1528
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @1417-1417
- function_definition ScopeSpans @1437-1437
- function_definition ScopeSpans @1438-1438
- function_definition (anonymous) @1439-1442
- function_definition (anonymous) @1443-1451
- function_definition (anonymous) @1453-1456
- function_definition mutable_unknown_fields @1457-1460
- function_definition (anonymous) @1462-1464
- function_definition swap @1466-1466
- function_definition MergeFrom @1488-1488
- function_definition GetCachedSize @1519-1521
- function_definition ScopeSpans @1530-1536
- enum_specifier (anonymous) @1551-1555
- class_specifier _Internal @1608-1608
- struct_specifier Impl_ @1627-1646
- function_definition google::protobuf::MessageLite @1649-1760
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @1649-1649
- function_definition ResourceSpans @1669-1669
- function_definition ResourceSpans @1670-1670
- function_definition (anonymous) @1671-1674
- function_definition (anonymous) @1675-1683
- function_definition (anonymous) @1685-1688
- function_definition mutable_unknown_fields @1689-1692
- function_definition (anonymous) @1694-1696
- function_definition swap @1698-1698
- function_definition MergeFrom @1720-1720
- function_definition GetCachedSize @1751-1753
- function_definition ResourceSpans @1762-1768
- enum_specifier (anonymous) @1783-1787
- class_specifier _Internal @1840-1840
- struct_specifier Impl_ @1859-1878
- function_definition google::protobuf::MessageLite @1881-1992
- class_specifier PROTOBUF_FUTURE_ADD_EARLY_WARN_UNUSED @1881-1881
- function_definition TracesData @1901-1901
- function_definition TracesData @1902-1902
- function_definition (anonymous) @1903-1906
- function_definition (anonymous) @1907-1915
- function_definition (anonymous) @1917-1920
- function_definition mutable_unknown_fields @1921-1924
- function_definition (anonymous) @1926-1928
- function_definition swap @1930-1930
- function_definition MergeFrom @1952-1952
- function_definition GetCachedSize @1983-1985
- function_definition TracesData @1994-2000
- enum_specifier (anonymous) @2015-2017
- class_specifier _Internal @2040-2040
- struct_specifier Impl_ @2059-2076
- function_definition _internal_resource_spans_size @2095-2097
- function_definition resource_spans_size @2098-2100
- function_definition clear_resource_spans @2101-2105
- function_definition (anonymous) @2106-2110
- function_definition mutable_resource_spans @2111-2115
- function_definition add_resource_spans @2116-2125
- function_definition (anonymous) @2126-2130
- function_definition mutable_resource_spans @2131-2137
- function_definition (anonymous) @2138-2142
- function_definition _internal_mutable_resource_spans @2143-2147
- function_definition has_resource @2154-2158
- function_definition (anonymous) @2159-2163
- function_definition (anonymous) @2164-2167
- function_definition unsafe_arena_set_allocated_resource @2168-2181
- function_definition ResourceSpans::release_resource @2182-2200
- function_definition ResourceSpans::unsafe_arena_release_resource @2201-2209
- function_definition ResourceSpans::_internal_mutable_resource @2210-2217
- function_definition ResourceSpans::mutable_resource @2218-2224
- function_definition set_allocated_resource @2225-2244
- function_definition _internal_scope_spans_size @2247-2249
- function_definition scope_spans_size @2250-2252
- function_definition clear_scope_spans @2253-2257
- function_definition (anonymous) @2258-2262
- function_definition ResourceSpans::mutable_scope_spans @2263-2267
- function_definition ResourceSpans::add_scope_spans @2268-2277
- function_definition (anonymous) @2278-2282
- function_definition ResourceSpans::mutable_scope_spans @2283-2289
- function_definition (anonymous) @2290-2294
- function_definition ResourceSpans::_internal_mutable_scope_spans @2295-2299
- function_definition clear_schema_url @2302-2306
- function_definition (anonymous) @2307-2311
- function_definition set_schema_url @2313-2318
- function_definition ResourceSpans::mutable_schema_url @2319-2325
- function_definition (anonymous) @2326-2329
- function_definition _internal_set_schema_url @2330-2333
- function_definition ResourceSpans::_internal_mutable_schema_url @2334-2337
- function_definition ResourceSpans::release_schema_url @2338-2350
- function_definition set_allocated_schema_url @2351-2363
- function_definition has_scope @2370-2374
- function_definition (anonymous) @2375-2379
- function_definition (anonymous) @2380-2383
- function_definition unsafe_arena_set_allocated_scope @2384-2397
- function_definition release_scope @2398-2416
- function_definition unsafe_arena_release_scope @2417-2425
- function_definition _internal_mutable_scope @2426-2433
- function_definition mutable_scope @2434-2440
- function_definition set_allocated_scope @2441-2460
- function_definition _internal_spans_size @2463-2465
- function_definition spans_size @2466-2468
- function_definition clear_spans @2469-2473
- function_definition (anonymous) @2474-2478
- function_definition mutable_spans @2479-2483
- function_definition add_spans @2484-2493
- function_definition (anonymous) @2494-2498
- function_definition mutable_spans @2499-2505
- function_definition (anonymous) @2506-2510
- function_definition _internal_mutable_spans @2511-2515
- function_definition clear_schema_url @2518-2522
- function_definition (anonymous) @2523-2527
- function_definition set_schema_url @2529-2534
- function_definition mutable_schema_url @2535-2541
- function_definition (anonymous) @2542-2545
- function_definition _internal_set_schema_url @2546-2549
- function_definition _internal_mutable_schema_url @2550-2553
- function_definition release_schema_url @2554-2566
- function_definition set_allocated_schema_url @2567-2579
- function_definition clear_time_unix_nano @2586-2590
- function_definition time_unix_nano @2591-2594
- function_definition set_time_unix_nano @2595-2599
- function_definition _internal_time_unix_nano @2600-2603
- function_definition _internal_set_time_unix_nano @2604-2607
- function_definition clear_name @2610-2614
- function_definition (anonymous) @2615-2619
- function_definition set_name @2621-2626
- function_definition mutable_name @2627-2633
- function_definition (anonymous) @2634-2637
- function_definition _internal_set_name @2638-2641
- function_definition _internal_mutable_name @2642-2645
- function_definition release_name @2646-2658
- function_definition set_allocated_name @2659-2671
- function_definition _internal_attributes_size @2674-2676
- function_definition attributes_size @2677-2679
- function_definition (anonymous) @2680-2684
- function_definition mutable_attributes @2685-2689
- function_definition add_attributes @2690-2699
- function_definition (anonymous) @2700-2704
- function_definition mutable_attributes @2705-2711
- function_definition (anonymous) @2712-2716
- function_definition _internal_mutable_attributes @2717-2721
- function_definition clear_dropped_attributes_count @2724-2728
- function_definition dropped_attributes_count @2729-2732
- function_definition set_dropped_attributes_count @2733-2737
- function_definition _internal_dropped_attributes_count @2738-2741
- function_definition _internal_set_dropped_attributes_count @2742-2745
- function_definition clear_trace_id @2752-2756
- function_definition (anonymous) @2757-2761
- function_definition set_trace_id @2763-2768
- function_definition mutable_trace_id @2769-2775
- function_definition (anonymous) @2776-2779
- function_definition _internal_set_trace_id @2780-2783
- function_definition _internal_mutable_trace_id @2784-2787
- function_definition release_trace_id @2788-2800
- function_definition set_allocated_trace_id @2801-2813
- function_definition clear_span_id @2816-2820
- function_definition (anonymous) @2821-2825
- function_definition set_span_id @2827-2832
- function_definition mutable_span_id @2833-2839
- function_definition (anonymous) @2840-2843
- function_definition _internal_set_span_id @2844-2847
- function_definition _internal_mutable_span_id @2848-2851
- function_definition release_span_id @2852-2864
- function_definition set_allocated_span_id @2865-2877
- function_definition clear_trace_state @2880-2884
- function_definition (anonymous) @2885-2889
- function_definition set_trace_state @2891-2896
- function_definition mutable_trace_state @2897-2903
- function_definition (anonymous) @2904-2907
- function_definition _internal_set_trace_state @2908-2911
- function_definition _internal_mutable_trace_state @2912-2915
- function_definition release_trace_state @2916-2928
- function_definition set_allocated_trace_state @2929-2941
- function_definition _internal_attributes_size @2944-2946
- function_definition attributes_size @2947-2949
- function_definition (anonymous) @2950-2954
- function_definition mutable_attributes @2955-2959
- function_definition add_attributes @2960-2969
- function_definition (anonymous) @2970-2974
- function_definition mutable_attributes @2975-2981
- function_definition (anonymous) @2982-2986
- function_definition _internal_mutable_attributes @2987-2991
- function_definition clear_dropped_attributes_count @2994-2998
- function_definition dropped_attributes_count @2999-3002
- function_definition set_dropped_attributes_count @3003-3007
- function_definition _internal_dropped_attributes_count @3008-3011
- function_definition _internal_set_dropped_attributes_count @3012-3015
- function_definition clear_flags @3018-3022
- function_definition flags @3023-3026
- function_definition set_flags @3027-3031
- function_definition _internal_flags @3032-3035
- function_definition _internal_set_flags @3036-3039
- function_definition clear_trace_id @3046-3050
- function_definition (anonymous) @3051-3055
- function_definition set_trace_id @3057-3062
- function_definition mutable_trace_id @3063-3069
- function_definition (anonymous) @3070-3073
- function_definition _internal_set_trace_id @3074-3077
- function_definition _internal_mutable_trace_id @3078-3081
- function_definition release_trace_id @3082-3094
- function_definition set_allocated_trace_id @3095-3107
- function_definition clear_span_id @3110-3114
- function_definition (anonymous) @3115-3119
- function_definition set_span_id @3121-3126
- function_definition mutable_span_id @3127-3133
- function_definition (anonymous) @3134-3137
- function_definition _internal_set_span_id @3138-3141
- function_definition _internal_mutable_span_id @3142-3145
- function_definition release_span_id @3146-3158
- function_definition set_allocated_span_id @3159-3171
- function_definition clear_trace_state @3174-3178
- function_definition (anonymous) @3179-3183
- function_definition set_trace_state @3185-3190
- function_definition mutable_trace_state @3191-3197
- function_definition (anonymous) @3198-3201
- function_definition _internal_set_trace_state @3202-3205
- function_definition _internal_mutable_trace_state @3206-3209
- function_definition release_trace_state @3210-3222
- function_definition set_allocated_trace_state @3223-3235
- function_definition clear_parent_span_id @3238-3242
- function_definition (anonymous) @3243-3247
- function_definition set_parent_span_id @3249-3254
- function_definition mutable_parent_span_id @3255-3261
- function_definition (anonymous) @3262-3265
- function_definition _internal_set_parent_span_id @3266-3269
- function_definition _internal_mutable_parent_span_id @3270-3273
- function_definition release_parent_span_id @3274-3286
- function_definition set_allocated_parent_span_id @3287-3299
- function_definition clear_flags @3302-3306
- function_definition flags @3307-3310
- function_definition set_flags @3311-3315
- function_definition _internal_flags @3316-3319
- function_definition _internal_set_flags @3320-3323
- function_definition clear_name @3326-3330
- function_definition (anonymous) @3331-3335
- function_definition set_name @3337-3342
- function_definition mutable_name @3343-3349
- function_definition (anonymous) @3350-3353
- function_definition _internal_set_name @3354-3357
- function_definition _internal_mutable_name @3358-3361
- function_definition release_name @3362-3374
- function_definition set_allocated_name @3375-3387
- function_definition clear_kind @3390-3394
- function_definition kind @3395-3398
- function_definition set_kind @3399-3403
- function_definition _internal_kind @3404-3407
- function_definition _internal_set_kind @3408-3411
- function_definition clear_start_time_unix_nano @3414-3418
- function_definition start_time_unix_nano @3419-3422
- function_definition set_start_time_unix_nano @3423-3427
- function_definition _internal_start_time_unix_nano @3428-3431
- function_definition _internal_set_start_time_unix_nano @3432-3435
- function_definition clear_end_time_unix_nano @3438-3442
- function_definition end_time_unix_nano @3443-3446
- function_definition set_end_time_unix_nano @3447-3451
- function_definition _internal_end_time_unix_nano @3452-3455
- function_definition _internal_set_end_time_unix_nano @3456-3459
- function_definition _internal_attributes_size @3462-3464
- function_definition attributes_size @3465-3467
- function_definition (anonymous) @3468-3472
- function_definition mutable_attributes @3473-3477
- function_definition add_attributes @3478-3487
- function_definition (anonymous) @3488-3492
- function_definition mutable_attributes @3493-3499
- function_definition (anonymous) @3500-3504
- function_definition _internal_mutable_attributes @3505-3509
- function_definition clear_dropped_attributes_count @3512-3516
- function_definition dropped_attributes_count @3517-3520
- function_definition set_dropped_attributes_count @3521-3525
- function_definition _internal_dropped_attributes_count @3526-3529
- function_definition _internal_set_dropped_attributes_count @3530-3533
- function_definition _internal_events_size @3536-3538
- function_definition events_size @3539-3541
- function_definition clear_events @3542-3546
- function_definition (anonymous) @3547-3551
- function_definition mutable_events @3552-3556
- function_definition add_events @3557-3566
- function_definition (anonymous) @3567-3571
- function_definition mutable_events @3572-3578
- function_definition (anonymous) @3579-3583
- function_definition _internal_mutable_events @3584-3588
- function_definition clear_dropped_events_count @3591-3595
- function_definition dropped_events_count @3596-3599
- function_definition set_dropped_events_count @3600-3604
- function_definition _internal_dropped_events_count @3605-3608
- function_definition _internal_set_dropped_events_count @3609-3612
- function_definition _internal_links_size @3615-3617
- function_definition links_size @3618-3620
- function_definition clear_links @3621-3625
- function_definition (anonymous) @3626-3630
- function_definition mutable_links @3631-3635
- function_definition add_links @3636-3645
- function_definition (anonymous) @3646-3650
- function_definition mutable_links @3651-3657
- function_definition (anonymous) @3658-3662
- function_definition _internal_mutable_links @3663-3667
- function_definition clear_dropped_links_count @3670-3674
- function_definition dropped_links_count @3675-3678
- function_definition set_dropped_links_count @3679-3683
- function_definition _internal_dropped_links_count @3684-3687
- function_definition _internal_set_dropped_links_count @3688-3691
- function_definition has_status @3694-3698
- function_definition clear_status @3699-3703
- function_definition (anonymous) @3704-3708
- function_definition (anonymous) @3709-3712
- function_definition unsafe_arena_set_allocated_status @3713-3726
- function_definition release_status @3727-3745
- function_definition unsafe_arena_release_status @3746-3754
- function_definition _internal_mutable_status @3755-3762
- function_definition mutable_status @3763-3769
- function_definition set_allocated_status @3770-3789
- function_definition clear_message @3796-3800
- function_definition (anonymous) @3801-3805
- function_definition set_message @3807-3812
- function_definition mutable_message @3813-3819
- function_definition (anonymous) @3820-3823
- function_definition _internal_set_message @3824-3827
- function_definition _internal_mutable_message @3828-3831
- function_definition release_message @3832-3844
- function_definition set_allocated_message @3845-3857
- function_definition clear_code @3860-3864
- function_definition code @3865-3868
- function_definition set_code @3869-3873
- function_definition _internal_code @3874-3877
- function_definition _internal_set_code @3878-3881
- struct_specifier is_proto_enum<::opentelemetry::proto::trace::v1::Span_SpanKind> @3898-3898
- struct_specifier internal::LiteEnumFuncs<::opentelemetry::proto::trace::v1::Span_SpanKind> @3900-3904
- struct_specifier is_proto_enum<::opentelemetry::proto::trace::v1::Status_StatusCode> @3906-3906
- struct_specifier internal::LiteEnumFuncs<::opentelemetry::proto::trace::v1::Status_StatusCode> @3908-3912
- struct_specifier is_proto_enum<::opentelemetry::proto::trace::v1::SpanFlags> @3914-3914
- struct_specifier internal::LiteEnumFuncs<::opentelemetry::proto::trace::v1::SpanFlags> @3916-3920
- include "google/protobuf/port_undef.inc" @3927

### third_party/parakeet.cpp/include/parakeet.h

Blob: `f74f2862563dda3702fff79a5cd0f94e757a288d`. Grammar: cpp. Status: contains-errors.

- include <string> @24
- enum_specifier Decoder @32-32

### third_party/parakeet.cpp/include/parakeet_capi.h

Blob: `24cd23a029a270974a65a6ca5fe2075e963d5d8b`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @4
- struct_specifier parakeet_ctx @18-18
- struct_specifier parakeet_stream @190-190
- struct_specifier parakeet_stream_event @241-246
- struct_specifier parakeet_stream_word @281-286

### third_party/parakeet.cpp/moz-overrides.h

Blob: `9247caa2e14375ad3a72c2964ffb1610cf74038e`. Grammar: cpp. Status: syntax-clean.

- include <cstdlib> @6
- function_definition abort_with_suppression @19-21

### third_party/parakeet.cpp/src/audio_io.cpp

Blob: `ed1eea1efeeb04feec854f16f1dbde4989547ba7`. Grammar: cpp. Status: syntax-clean.

- include "audio_io.hpp" @1
- include "common.hpp" @2
- include <cmath> @3
- function_definition resample_linear @7-21
- function_definition load_audio_16k_mono @23-28

### third_party/parakeet.cpp/src/audio_io.hpp

Blob: `47d38789c268175c7dc95b4f35afa8d2601de473`. Grammar: cpp. Status: syntax-clean.

- include <string> @2
- include <vector> @3
- include <cstdint> @4
- struct_specifier Audio @6-9

### third_party/parakeet.cpp/src/backend.cpp

Blob: `40055f9811c1c2dde2e89c209e12765d28e577cd`. Grammar: cpp. Status: syntax-clean.

- include "backend.hpp" @1
- include "common.hpp" @2
- include "ggml_graph.hpp" @3
- include "model_loader.hpp" @4
- include "ggml.h" @6
- include "ggml-alloc.h" @7
- include "ggml-backend.h" @8
- include "ggml-cpu.h" @9
- include <cassert> @11
- include <cctype> @12
- include <cstdlib> @13
- include <cstring> @14
- include <string> @15
- include <vector> @16
- function_definition last_graph_alloc_bytes @23-23
- struct_specifier PendingInput @35-39
- struct_specifier PendingCapture @44-47
- struct_specifier Backend::Impl @50-62
- function_definition Backend @71-146
- function_definition ~Backend @148-158
- function_definition set_n_threads @160-168
- function_definition handle @170-172
- function_definition register_input @174-176
- function_definition register_capture @178-180
- function_definition compute @182-328
- struct_specifier ggml_init_params @191-191
- struct_specifier ggml_context @197-197
- struct_specifier ggml_tensor @209-209
- struct_specifier ggml_cgraph @224-224
- enum_specifier ggml_status @302-302
- function_definition add_graph_input @330-335
- function_definition graph_input_tensor @337-343
- function_definition capture_graph_output @345-349
- function_definition ensure_weights_realized @351-359
- function_definition clone_weight @361-373
- function_definition clone_weight_opt @375-379
- function_definition weight_to_host_f32 @381-388

### third_party/parakeet.cpp/src/backend.hpp

Blob: `d534ec984cfce605523ffc33357213486557b2e4`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @2
- include <functional> @3
- include <string> @4
- include <vector> @5
- struct_specifier ggml_context @7-7
- struct_specifier ggml_tensor @8-8
- struct_specifier ggml_backend @9-9
- struct_specifier ggml_backend @10-10
- class_specifier ModelLoader @14-14
- class_specifier Backend @39-98
- function_definition Backend @46-46
- function_definition (anonymous) @47-47
- function_definition n_threads @52-52
- function_definition device_name @56-56
- struct_specifier Impl @94-94

### third_party/parakeet.cpp/src/common.cpp

Blob: `7a1adb1edf2fb56e863875452561b08d364bfae4`. Grammar: cpp. Status: syntax-clean.

- include "common.hpp" @1

### third_party/parakeet.cpp/src/common.hpp

Blob: `b6449164f91a1ccc52ce432892852e8c7ad85da3`. Grammar: cpp. Status: syntax-clean.

- include <cstdio> @2

### third_party/parakeet.cpp/src/conformer.cpp

Blob: `0622f05420c88f1a73dd827087a4cd9cb4d633d7`. Grammar: cpp. Status: syntax-clean.

- include "conformer.hpp" @1
- include "relpos_attention.hpp" @2
- include "ggml_graph.hpp" @3
- include "backend.hpp" @4
- include "ggml.h" @5
- include <cassert> @6
- include <cmath> @7
- include <cstring> @8
- include <string> @9
- include <vector> @10
- function_definition clone_weight @20-23
- function_definition clone_weight_opt @24-27
- function_definition build_conv_module @38-164
- function_definition build_conv_module @172-269
- function_definition ConformerLayer @271-283
- function_definition build_graph_batched @285-358
- function_definition build_graph @364-434
- function_definition forward @436-442
- function_definition forward_with_conv @444-526
- function_definition conv_module_forward @528-551

### third_party/parakeet.cpp/src/conformer.hpp

Blob: `5fafc0b50d01ce578589757af49c0f27f8109282`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include "graph_builder.hpp" @3
- include <string> @4
- include <vector> @5
- struct_specifier ggml_context @7-7
- struct_specifier ggml_tensor @8-8
- class_specifier ConformerLayer @45-110

### third_party/parakeet.cpp/src/ctc_decoder.cpp

Blob: `5e1fe386c56c2280207b6b9f6ef1a944953d4e88`. Grammar: cpp. Status: syntax-clean.

- include "ctc_decoder.hpp" @1
- include "ggml_graph.hpp" @2
- include "backend.hpp" @3
- include "ggml.h" @4
- include <cassert> @5
- include <cstring> @6
- include <stdexcept> @7
- include <string> @8
- include "moz-overrides.h" @9
- function_definition ctc_head_tensor @19-27
- function_definition CTCDecoder @30-33
- function_definition forward @35-117

### third_party/parakeet.cpp/src/ctc_decoder.hpp

Blob: `33db996ac39cfa09d948c2849c17277a09f10562`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <vector> @3
- class_specifier CTCDecoder @19-32

### third_party/parakeet.cpp/src/decode_common.hpp

Blob: `5bae7e07eadfbe3b0570c473a2ec37df3f7fab27`. Grammar: cpp. Status: syntax-clean.

- include <cmath> @2
- function_definition decode_argmax @5-9
- function_definition decode_max_prob_conf @12-20

### third_party/parakeet.cpp/src/decode_types.hpp

Blob: `4e0df71bcdc7d4c7ed82d9027de99e5c855a1d83`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @2
- struct_specifier TokenInfo @27-32

### third_party/parakeet.cpp/src/encoder.cpp

Blob: `0f77caa0d94d13c924ae532b78a8c50848b431af`. Grammar: cpp. Status: syntax-clean.

- include "encoder.hpp" @1
- include "subsampling.hpp" @2
- include "conformer.hpp" @3
- include "pos_enc.hpp" @4
- include "ggml_graph.hpp" @5
- include "backend.hpp" @6
- include "graph_builder.hpp" @7
- include "ggml.h" @8
- include <cassert> @9
- include <cmath> @10
- include <cstdlib> @11
- include <vector> @12
- function_definition local_attn_window @24-35
- function_definition Encoder @37-43
- function_definition forward @45-50
- function_definition forward_capture @52-123
- function_definition forward_batch @125-199
- function_definition run_post_subsampling_batch @201-255
- function_definition forward_batch_tiled @257-283

### third_party/parakeet.cpp/src/encoder.hpp

Blob: `f9a5ae8271e62b118b12b886455e6f1ad8741582`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <vector> @3
- struct_specifier MelBatch @17-23
- class_specifier Encoder @25-85

### third_party/parakeet.cpp/src/fft.cpp

Blob: `4571a60831d3238ce7fc1de08a4f3d9a985eeffd`. Grammar: cpp. Status: syntax-clean.

- include "fft.hpp" @1
- include <cassert> @2
- include <cmath> @6
- include <cstdint> @10
- include <vector> @11
- function_definition fft_inplace @17-56
- function_definition rfft @58-79

### third_party/parakeet.cpp/src/fft.hpp

Blob: `6738d9fd14472a0fb4386c4356c877d501e77323`. Grammar: cpp. Status: syntax-clean.

- include <vector> @2

### third_party/parakeet.cpp/src/ggml_graph.cpp

Blob: `f5bf84a416b58391fd54a0b54c0e1edd3bd79382`. Grammar: cpp. Status: syntax-clean.

- include "ggml_graph.hpp" @1
- include "backend.hpp" @2
- include "common.hpp" @3
- include "ggml.h" @4
- include <atomic> @5
- include <memory> @6
- include <mutex> @7
- function_definition set_num_threads @16-16
- function_definition num_threads @17-17
- function_definition (anonymous) @49-67
- function_definition shutdown_backend @69-79
- function_definition run_graph @81-98

### third_party/parakeet.cpp/src/ggml_graph.hpp

Blob: `0b922e03f77dc1fff6a5eae6d0f5cec3d65a092a`. Grammar: cpp. Status: syntax-clean.

- include <functional> @2
- include <vector> @3
- struct_specifier ggml_context @5-5
- struct_specifier ggml_tensor @6-6
- class_specifier Backend @42-42

### third_party/parakeet.cpp/src/graph_builder.hpp

Blob: `9fc48fba03d360464bbb4a3d8046aa4423be934c`. Grammar: cpp. Status: syntax-clean.

- include <cstddef> @2
- include <memory> @3
- include <vector> @4
- class_specifier GraphInputPool @16-30
- function_definition (anonymous) @19-22
- function_definition (anonymous) @24-27

### third_party/parakeet.cpp/src/joint.cpp

Blob: `90cc24edfb4818001c5aa0a985066b0ecefc4f19`. Grammar: cpp. Status: syntax-clean.

- include "joint.hpp" @1
- include "backend.hpp" @2
- include "ggml_graph.hpp" @3
- include "ggml.h" @4
- include <cassert> @5
- include <cstring> @6
- include <vector> @7
- function_definition Joint @11-35
- function_definition precompute_enc_proj @37-63
- function_definition step_logits @65-104
- function_definition step_logits_batch @106-143
- function_definition forward @145-174

### third_party/parakeet.cpp/src/joint.hpp

Blob: `8369cb2235fa6df7aeaf14f2a44a9b78d9198169`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <vector> @3
- class_specifier Joint @29-94
- function_definition joint_hidden @78-78
- function_definition V_plus @81-81
- function_definition vocab_size @82-82
- function_definition num_durations @83-83

### third_party/parakeet.cpp/src/mel.cpp

Blob: `21d2b24b6f569435f34a29aecccd2fea8e3f57e9`. Grammar: cpp. Status: syntax-clean.

- include "mel.hpp" @1
- include "fft.hpp" @2
- include "backend.hpp" @3
- include "ggml.h" @4
- include <cassert> @5
- include <cmath> @6
- include <cstring> @7
- include <algorithm> @8
- include <vector> @9
- function_definition MelKernel @16-61
- function_definition frame_logmel @63-91
- function_definition MelFrontend @93-93
- function_definition compute @95-176
- function_definition StreamingMel @182-191
- function_definition reset @193-201
- function_definition build_frames @207-243
- function_definition feed @245-288
- function_definition finalize @290-306
- function_definition to_feat_major @311-319

### third_party/parakeet.cpp/src/mel.hpp

Blob: `4045557a982294852d6d5d89e9694d507182d1c1`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <cassert> @3
- include <vector> @4
- struct_specifier MelKernel @10-29
- class_specifier MelFrontend @31-38
- class_specifier StreamingMel @64-113
- function_definition incremental_ok @70-70
- function_definition n_mels @72-72

### third_party/parakeet.cpp/src/mel_gpu.cpp

Blob: `6228e6a6482595d790a2db2b5da9ffb56f7dff46`. Grammar: cpp. Status: syntax-clean.

- include "mel_gpu.hpp" @1
- include "backend.hpp" @2
- include "ggml_graph.hpp" @3
- include "ggml.h" @4
- include <cassert> @5
- include <cmath> @9
- include <vector> @13
- function_definition GpuMel @21-38
- function_definition compute @40-168

### third_party/parakeet.cpp/src/mel_gpu.hpp

Blob: `ed4b0cf07262a19b113f8c5ac93d5d4ed9cfbb45`. Grammar: cpp. Status: syntax-clean.

- include "mel.hpp" @2
- include <vector> @3
- class_specifier GpuMel @15-26

### third_party/parakeet.cpp/src/model.cpp

Blob: `672659e3fbc9a4d2a5a7fe6c2052be14361cc3b1`. Grammar: cpp. Status: syntax-clean.

- include "model.hpp" @1
- include "audio_io.hpp" @3
- include "mel.hpp" @4
- include "mel_gpu.hpp" @5
- include "encoder.hpp" @6
- include "subsampling.hpp" @7
- include "ctc_decoder.hpp" @8
- include "search.hpp" @9
- include "tokenizer.hpp" @10
- include "prediction.hpp" @11
- include "joint.hpp" @12
- include "prompt_kernel.hpp" @13
- include "tdt.hpp" @14
- include "rnnt.hpp" @15
- include "transducer_batch.hpp" @16
- include "transcription.hpp" @17
- include "decode_types.hpp" @18
- include "backend.hpp" @19
- include "ggml_graph.hpp" @20
- include <algorithm> @22
- include <cstdlib> @23
- include <stdexcept> @24
- include <vector> @25
- include "moz-overrides.h" @26
- function_definition arch_prefers_tdt @33-38
- function_definition load @41-54
- function_definition load_fd @58-66
- function_definition resolve_prompt_index @74-78
- function_definition maybe_apply_prompt @82-89
- function_definition decode_enc_out @93-121
- function_definition transcribe_16k @123-174
- function_definition safe_mel_window @181-189
- function_definition subsampling_tile_for @195-204
- function_definition build_mel_batch @211-236
- function_definition batch_enc_to_row_major @240-254
- function_definition transcribe_16k_batch @256-308
- function_definition transcribe_pcm_batch @310-321
- function_definition decode_enc_out_with_timestamps @326-367
- function_definition transcribe_16k_with_timestamps @369-425
- function_definition transcribe_16k_batch_with_timestamps @427-486
- function_definition transcribe_pcm_batch_with_timestamps @488-499
- function_definition transcribe_pcm @501-511
- function_definition transcribe_path @513-521
- function_definition transcribe_with_timestamps @523-534
- function_definition transcribe_path_with_timestamps @536-544

### third_party/parakeet.cpp/src/model.hpp

Blob: `e1ea37a0b9386c61f12acda323050d156c394c3c`. Grammar: cpp. Status: syntax-clean.

- include "parakeet.h" @2
- include "model_loader.hpp" @3
- include "transcription.hpp" @4
- include <memory> @6
- include <string> @7
- include <vector> @8
- class_specifier Model @22-125
- function_definition (anonymous) @91-91
- function_definition (anonymous) @95-95
- function_definition weights_bytes @97-97
- function_definition Model @100-100
- function_definition (anonymous) @101-101
- function_definition Model @104-104

### third_party/parakeet.cpp/src/model_loader.cpp

Blob: `3fa2da8bd0837ec52fb2a56d7f938227c6b978e9`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @1
- include "common.hpp" @2
- include "ggml.h" @3
- include "ggml-backend.h" @4
- include "ggml-alloc.h" @5
- include "ggml-cpu.h" @6
- include "gguf.h" @7
- include <cstring> @8
- include <cstdio> @9
- include <vector> @10
- include <utility> @11
- include <stdexcept> @12
- include "moz-overrides.h" @13
- function_definition resolve_index_or_throw @16-27
- function_definition kv_u32 @29-31
- function_definition kv_i32 @32-34
- function_definition kv_i32_arr @35-44
- function_definition kv_str_arr @45-54
- function_definition kv_f32 @55-57
- function_definition kv_bool @58-60
- function_definition kv_str @61-63
- function_definition ~ModelLoader @64-73
- function_definition weights_bytes @75-78
- function_definition realize_weights @80-138
- struct_specifier ggml_init_params @108-108
- function_definition load @139-144
- struct_specifier gguf_init_params @140-140
- function_definition load_fd @149-158
- struct_specifier gguf_init_params @150-150
- function_definition parse_gguf @160-237
- function_definition tensor @238-240

### third_party/parakeet.cpp/src/model_loader.hpp

Blob: `973789c4f9cd78b291b659dea95df0c155cc2201`. Grammar: cpp. Status: syntax-clean.

- include <string> @2
- include <vector> @3
- include <unordered_map> @4
- include <cstdint> @5
- struct_specifier ggml_tensor @6-6
- struct_specifier ggml_context @7-7
- struct_specifier gguf_context @8-8
- struct_specifier ggml_backend_buffer @9-9
- struct_specifier ggml_backend_buffer @10-10
- struct_specifier ggml_backend @11-11
- struct_specifier ggml_backend @12-12
- struct_specifier StreamingCfg @17-26
- struct_specifier PromptCfg @29-46
- function_definition lang_to_index @36-40
- struct_specifier ParakeetConfig @47-74
- class_specifier ModelLoader @75-112
- function_definition ModelLoader @77-77
- function_definition (anonymous) @82-82
- function_definition (anonymous) @83-83
- function_definition ggml_ctx @85-85
- function_definition weights_realized @97-97

### third_party/parakeet.cpp/src/parakeet.cpp

Blob: `bdd93700608acfa3f5ee5c2a6d6245b69487595a`. Grammar: cpp. Status: syntax-clean.

- include "parakeet.h" @1
- include "model.hpp" @2
- include <cstdlib> @4
- include <cstring> @5
- include <stdexcept> @6
- include <string> @7
- function_definition parakeet_version @11-11
- function_definition transcribe @18-25
- function_definition parakeet_transcribe_file @29-44
- function_definition parakeet_free_string @46-46

### third_party/parakeet.cpp/src/parakeet_capi.cpp

Blob: `c528165ee25ca6f1cfb77fe464b12c2fed802010`. Grammar: cpp. Status: syntax-clean.

- include "parakeet_capi.h" @1
- include <cstdio> @2
- include <cstdlib> @3
- include <cstring> @4
- include <exception> @5
- include <memory> @6
- include <new> @7
- include <string> @8
- include <vector> @9
- include "parakeet.h" @10
- include "model.hpp" @11
- include "streaming.hpp" @12
- include "mel.hpp" @13
- include "transcription.hpp" @15
- include "moz-overrides.h" @16
- struct_specifier parakeet_ctx @43-46
- struct_specifier parakeet_stream @68-78
- function_definition append_mel_frames @85-101
- function_definition to_decoder @107-114
- function_definition dup_to_c @118-124
- function_definition append_json_string @129-151
- function_definition append_json_int @154-158
- function_definition append_json_float @162-170
- function_definition transcription_to_json @175-211
- function_definition parakeet_capi_abi_version @215-217
- function_definition parakeet_capi_load @219-232
- function_definition parakeet_capi_weights_bytes @234-237
- function_definition parakeet_capi_load_fd @240-252
- function_definition parakeet_capi_free @254-256
- function_definition parakeet_capi_transcribe_path_lang @258-279
- function_definition parakeet_capi_transcribe_path @281-285
- function_definition parakeet_capi_transcribe_pcm_lang @287-310
- function_definition parakeet_capi_transcribe_pcm @312-318
- function_definition parakeet_capi_transcribe_pcm_batch_lang @320-368
- function_definition parakeet_capi_transcribe_pcm_batch @370-378
- function_definition parakeet_capi_transcribe_path_json @380-405
- function_definition parakeet_capi_transcribe_pcm_batch_json_lang @407-446
- function_definition parakeet_capi_transcribe_pcm_batch_json @448-455
- function_definition feed_available @473-528
- function_definition parakeet_capi_stream_begin_lang @532-558
- function_definition parakeet_capi_stream_has_eou @560-563
- function_definition parakeet_capi_stream_blank_seconds @565-568
- function_definition parakeet_capi_stream_end_utterance @570-584
- function_definition parakeet_capi_stream_begin @586-589
- function_definition parakeet_capi_stream_feed @591-624
- function_definition parakeet_capi_stream_finalize @626-654
- function_definition parakeet_capi_stream_chunk_samples @656-662
- function_definition parakeet_capi_stream_drain_events @664-691
- function_definition parakeet_capi_free_events @693-695
- function_definition parakeet_capi_stream_drain_words @699-730
- function_definition parakeet_capi_free_words @732-738
- function_definition stream_json @749-789
- function_definition stream_frame_sec @792-795
- function_definition parakeet_capi_stream_feed_json @799-829
- function_definition parakeet_capi_stream_finalize_json @831-858
- function_definition parakeet_capi_stream_free @860-862
- function_definition parakeet_capi_free_string @864-866
- function_definition parakeet_capi_last_error @868-871

### third_party/parakeet.cpp/src/pos_enc.cpp

Blob: `860825e23f8bd8132d2d920c85513fca09cb405e`. Grammar: cpp. Status: syntax-clean.

- include "pos_enc.hpp" @1
- include <cmath> @2
- include <cassert> @3
- function_definition rel_pos_encoding @10-34
- function_definition local_rel_pos_encoding @36-59

### third_party/parakeet.cpp/src/pos_enc.hpp

Blob: `c185be99dd443eea2cb2a4ebb6cd9a9329d2a289`. Grammar: cpp. Status: syntax-clean.

- include <vector> @2

### third_party/parakeet.cpp/src/prediction.cpp

Blob: `3ef80662f86d265ca42fdf83c85dff620f44976a`. Grammar: cpp. Status: syntax-clean.

- include "prediction.hpp" @1
- include "backend.hpp" @2
- include "ggml_graph.hpp" @3
- include "ggml.h" @4
- include "ggml-backend.h" @5
- include <cassert> @6
- include <cstring> @7
- include <string> @8
- include <vector> @9
- function_definition PredictionNet @13-19
- function_definition zero_state @24-29
- function_definition step @44-113
- function_definition step_batch @121-197
- function_definition forward @204-222

### third_party/parakeet.cpp/src/prediction.hpp

Blob: `6e5b8ed666105da3ea1428edf8460e1dec24c2be`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <vector> @3
- include <cstdint> @4
- struct_specifier PredState @12-15
- struct_specifier BatchedPredState @19-22
- class_specifier PredictionNet @51-103
- function_definition hidden_size @89-89
- function_definition num_layers @91-91

### third_party/parakeet.cpp/src/prompt_kernel.cpp

Blob: `6d5e476ad0fa174ad1f1e4cf72bd31e95ceceec9`. Grammar: cpp. Status: syntax-clean.

- include "prompt_kernel.hpp" @1
- include "backend.hpp" @2
- include "ggml_graph.hpp" @3
- include "ggml.h" @4
- include <cassert> @5
- include <vector> @6
- function_definition PromptKernel @10-15
- function_definition apply @17-66

### third_party/parakeet.cpp/src/prompt_kernel.hpp

Blob: `14c6bfe2f182d7302b9ec3b8d9c4380d5160ad66`. Grammar: cpp. Status: syntax-clean.

- include "model_loader.hpp" @2
- include <vector> @3
- class_specifier PromptKernel @19-35
- function_definition present @22-22

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [f1ac82ff-e59b-496a-bef9-99b50460436d.md](f1ac82ff-e59b-496a-bef9-99b50460436d.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `655c5dbe3b65db7f1f96b42334eef6854e0f13934a110606506c42c8f420e1b8`.
