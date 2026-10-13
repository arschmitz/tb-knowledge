<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:22:06.018534+00:00","paths":["third_party"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-study-20261013","portableCopies":["e69d471aef24b9683427503b6560875bb8351e5cb49dad9c49a26dc5f2ef016d"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/a6147e01-6373-499a-ac0f-7c0d2a73a7eb.md"}} -->
# thunderbird/third_party native and TypeScript syntax map 56

Revision: `87d0159c7149a43253964c2cb6917939557dc799`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/debug_output.h

Blob: `8a5eedc21f0cb80254897e22b8608af33343a86d`. Grammar: cpp. Status: contains-errors.

- include <stdio.h> @30
- include <stdarg.h> @31
- include "glheader.h" @32
- include "menums.h" @33
- struct_specifier gl_context @40-40
- struct_specifier gl_context @43-43
- struct_specifier gl_context @46-46
- struct_specifier gl_context @52-52
- struct_specifier gl_context @55-55
- struct_specifier gl_context @58-58
- struct_specifier gl_context @61-61
- enum_specifier mesa_debug_source @61-61
- enum_specifier mesa_debug_type @62-62
- enum_specifier mesa_debug_severity @63-63
- struct_specifier gl_debug_state @66-66
- enum_specifier mesa_debug_source @67-67
- enum_specifier mesa_debug_type @68-68
- enum_specifier mesa_debug_severity @70-70

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/draw.h

Blob: `212e70a3fd494517e9d9d597fa22eb52c054beb2`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @34
- include "main/glheader.h" @35
- struct_specifier gl_context @41-41
- struct_specifier _mesa_prim @43-65
- struct_specifier _mesa_index_buffer @71-77
- struct_specifier gl_buffer_object @75-75
- struct_specifier gl_context @81-81
- struct_specifier _glapi_table @82-82

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/enums.h

Blob: `0e18cd407e9dbd955f82b9d4a4361b8d86a3c235`. Grammar: cpp. Status: contains-errors.


### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/errors.h

Blob: `17fe380f26aff3bc57110c29b32c427a529b863b`. Grammar: cpp. Status: contains-errors.

- include <stdio.h> @39
- include <stdarg.h> @40
- include "glheader.h" @41
- include "menums.h" @42
- struct_specifier gl_context @49-49
- struct_specifier gl_context @52-52
- struct_specifier gl_context @55-55
- struct_specifier gl_context @58-58
- struct_specifier gl_context @64-64
- struct_specifier gl_context @73-73
- struct_specifier gl_context @77-77
- enum_specifier mesa_debug_source @79-79
- enum_specifier mesa_debug_type @80-80
- enum_specifier mesa_debug_severity @81-81
- struct_specifier gl_context @86-86
- enum_specifier mesa_debug_source @88-88
- enum_specifier mesa_debug_type @89-89
- enum_specifier mesa_debug_severity @90-90
- struct_specifier gl_context @94-94
- enum_specifier mesa_debug_source @96-96
- enum_specifier mesa_debug_type @97-97
- enum_specifier mesa_debug_severity @98-98

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/extensions.h

Blob: `303929baabc9d84cd174b781533be482f477581f`. Grammar: cpp. Status: contains-errors.

- include "mtypes.h" @39
- struct_specifier gl_context @45-45
- struct_specifier gl_extensions @46-46
- struct_specifier gl_context @48-48
- struct_specifier gl_extensions @52-52
- struct_specifier gl_context @54-54
- struct_specifier gl_context @56-56
- struct_specifier gl_context @59-59
- struct_specifier gl_context @62-62
- struct_specifier mesa_extension @68-84
- struct_specifier mesa_extension @86-86
- include "extensions_table.h" @92
- include "extensions_table.h" @106
- struct_specifier gl_extensions @118-118
- struct_specifier gl_extensions @119-119

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/extensions_table.c

Blob: `6241705de13e198227179626c68faa1d1f74019d`. Grammar: c. Status: contains-errors.

- include "main/extensions.h" @26
- struct_specifier mesa_extension @37-37

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/extensions_table.h

Blob: `18d5f8073bfc9c3888e4b6f3f41b192bbfca202b`. Grammar: cpp. Status: contains-errors.


### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/formats.h

Blob: `f0e58b327e6b9d38c38a6cbc1d47a7f56f774f12`. Grammar: cpp. Status: contains-errors.

- include <GL/gl.h> @36
- include <stdbool.h> @37
- include <stdint.h> @38
- include "gallium/include/pipe/p_format.h" @39
- include "util/u_endian.h" @40
- enum_specifier mesa_format_layout @65-78
- enum_specifier (anonymous) @84-92
- enum_specifier mesa_array_format_datatype @103-112
- enum_specifier mesa_array_format_base_format @114-118
- enum_specifier (anonymous) @123-137
- function_definition _mesa_array_format_is_signed @156-160
- function_definition _mesa_array_format_is_float @162-166
- function_definition _mesa_array_format_is_normalized @168-172
- function_definition _mesa_array_format_get_base_format @174-179
- enum_specifier mesa_array_format_base_format @174-174
- enum_specifier mesa_array_format_base_format @177-177
- function_definition _mesa_array_format_get_datatype @181-186
- enum_specifier mesa_array_format_datatype @181-181
- enum_specifier mesa_array_format_datatype @184-184
- function_definition _mesa_array_format_datatype_get_size @188-192
- enum_specifier mesa_array_format_datatype @189-189
- function_definition _mesa_array_format_get_type_size @194-198
- function_definition _mesa_array_format_get_num_channels @200-204
- function_definition _mesa_array_format_get_swizzle @206-213
- function_definition _mesa_array_format_set_swizzle @215-228
- function_definition _mesa_format_is_mesa_array_format @234-238
- enum_specifier pipe_format @244-244
- enum_specifier mesa_format_layout @642-642

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/glheader.h

Blob: `59ca1cbadfca51a9aec571b5867019042d0d0272`. Grammar: cpp. Status: contains-errors.

- include "GL/gl.h" @37
- include "GL/glext.h" @38

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/glthread.h

Blob: `a50b2f87ceb4e3d97021e6b02386106591e1345e`. Grammar: cpp. Status: contains-errors.

- include <inttypes.h> @46
- include <stdbool.h> @47
- include "util/u_queue.h" @48
- include "GL/gl.h" @49
- include "compiler/shader_enums.h" @50
- struct_specifier gl_context @52-52
- struct_specifier _mesa_HashTable @53-53
- struct_specifier glthread_vao @55-60
- struct_specifier glthread_batch @63-81
- struct_specifier util_queue_fence @66-66
- struct_specifier gl_context @69-69
- struct_specifier glthread_state @83-116
- struct_specifier util_queue @86-86
- struct_specifier util_queue_monitoring @89-89
- struct_specifier glthread_batch @95-95
- struct_specifier glthread_batch @98-98
- struct_specifier _mesa_HashTable @107-107
- struct_specifier glthread_vao @108-108
- struct_specifier glthread_vao @109-109
- struct_specifier glthread_vao @110-110
- struct_specifier gl_context @118-118
- struct_specifier gl_context @119-119
- struct_specifier gl_context @121-121
- struct_specifier gl_context @122-122
- struct_specifier gl_context @123-123
- struct_specifier gl_context @124-124
- struct_specifier gl_context @125-125
- struct_specifier gl_context @127-127
- struct_specifier gl_context @129-129
- struct_specifier gl_context @132-132
- struct_specifier gl_context @133-133
- struct_specifier gl_context @135-135
- struct_specifier gl_context @137-137
- struct_specifier gl_context @139-139

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/hash.h

Blob: `0a3996a7d00694a067f9ce54e7dac0adb23c14d1`. Grammar: cpp. Status: syntax-clean.

- include <stdbool.h> @35
- include <stdint.h> @36
- include "glheader.h" @37
- include "c11/threads.h" @39
- function_definition uint_key_compare @73-77
- function_definition uint_hash @79-83
- function_definition uint_key_hash @85-89
- function_definition uint_key @91-95
- struct_specifier _mesa_HashTable @101-108
- struct_specifier hash_table @102-102
- struct_specifier _mesa_HashTable @110-110
- struct_specifier _mesa_HashTable @112-112
- struct_specifier _mesa_HashTable @114-114
- struct_specifier _mesa_HashTable @116-116
- struct_specifier _mesa_HashTable @118-118
- function_definition _mesa_HashLockMutex @129-134
- struct_specifier _mesa_HashTable @130-130
- function_definition _mesa_HashUnlockMutex @142-147
- struct_specifier _mesa_HashTable @143-143
- struct_specifier _mesa_HashTable @149-149
- struct_specifier _mesa_HashTable @151-151
- struct_specifier _mesa_HashTable @154-154
- struct_specifier _mesa_HashTable @157-157
- struct_specifier _mesa_HashTable @162-162
- struct_specifier _mesa_HashTable @167-167
- struct_specifier _mesa_HashTable @171-171
- struct_specifier _mesa_HashTable @173-173
- struct_specifier _mesa_HashTable @176-176

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/macros.h

Blob: `caa310fd021c85f458ce7990eedc884486276a82`. Grammar: cpp. Status: syntax-clean.

- include "util/macros.h" @34
- include "util/u_math.h" @35
- include "util/rounding.h" @36
- include "util/compiler.h" @37
- include "main/glheader.h" @38
- include "mesa_private.h" @39
- function_definition UINT_AS_UNION @178-183
- function_definition INT_AS_UNION @185-190
- function_definition FLOAT_AS_UNION @192-197
- function_definition DOUBLE_AS_UINT64 @199-207
- function_definition UINT64_AS_DOUBLE @209-217
- function_definition U_FIXED @228-233
- function_definition S_FIXED @240-244
- function_definition TEST_EQ_4UBV @274-282
- function_definition COPY_4UBV @295-304
- function_definition COPY_CLEAN_4V_TYPE_AS_UNION @634-657
- function_definition LINTERP @662-666
- function_definition INTERP_3F @668-674
- function_definition INTERP_4F @676-683
- function_definition minify @689-693
- function_definition CROSS3 @697-703
- function_definition DOT2 @707-711
- function_definition DOT3 @713-717
- function_definition DOT4 @719-723
- function_definition LEN_SQUARED_3FV @726-730
- function_definition LEN_SQUARED_2FV @732-736
- function_definition LEN_3FV @739-743
- function_definition LEN_2FV @745-749
- function_definition NORMALIZE_3FV @753-763
- function_definition DIFFERENT_SIGNS @767-778

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/menums.h

Blob: `79c14da5ea0062a10e0e5404396ff879e96a8dca`. Grammar: cpp. Status: syntax-clean.

- include "util/macros.h" @35
- enum_specifier gl_api @43-50
- enum_specifier gl_texture_index @57-72
- enum_specifier PACKED @93-93
- enum_specifier gl_buffer_index @115-138
- enum_specifier gl_map_buffer_index @140-145
- enum_specifier mesa_debug_source @153-162
- enum_specifier mesa_debug_type @164-176
- enum_specifier mesa_debug_severity @178-185

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/mesa_private.h

Blob: `229a746a8099f7cb235dedf6de1f3306d40ba95b`. Grammar: cpp. Status: contains-errors.

- include "glheader.h" @34

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/mtypes.h

Blob: `4f1e8e52ab05346b4bd7d54384da746d19252c77`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @37
- include <stdbool.h> @38
- include "c11/threads.h" @39
- include "main/glheader.h" @41
- include "main/glthread.h" @42
- include "main/menums.h" @43
- include "main/config.h" @44
- include "glapi/glapi.h" @45
- include "math/m_matrix.h" @46
- include "compiler/shader_enums.h" @47
- include "compiler/shader_info.h" @48
- include "main/formats.h" @49
- include "compiler/glsl/list.h" @50
- include "util/simple_mtx.h" @51
- include "util/u_dynarray.h" @52
- struct_specifier _mesa_HashTable @67-67
- struct_specifier gl_attrib_node @68-68
- struct_specifier gl_list_extensions @69-69
- struct_specifier gl_meta_state @70-70
- struct_specifier gl_program_cache @71-71
- struct_specifier gl_texture_object @72-72
- struct_specifier gl_debug_state @73-73
- struct_specifier gl_context @74-74
- struct_specifier st_context @75-75
- struct_specifier gl_uniform_storage @76-76
- struct_specifier prog_instruction @77-77
- struct_specifier gl_program_parameter_list @78-78
- struct_specifier gl_shader_spirv_data @79-79
- struct_specifier set @80-80
- struct_specifier shader_includes @81-81
- struct_specifier vbo_context @82-82
- function_definition _mesa_varying_slot_in_fs @94-113
- struct_specifier gl_config @163-217
- struct_specifier gl_material @280-283
- struct_specifier gl_light @300-331
- struct_specifier gl_lightmodel @337-344
- struct_specifier gl_accum_attrib @350-353
- struct_specifier gl_colorbuffer_attrib @371-454
- struct_specifier Blend @405-418
- enum_specifier gl_advanced_blend_mode @431-431
- enum_specifier gl_logicop_mode @444-444
- struct_specifier gl_vertex_format @460-470
- enum_specifier pipe_format @464-464
- struct_specifier gl_current_attrib @476-497
- struct_specifier gl_depthbuffer_attrib @503-511
- struct_specifier gl_eval_attrib @517-554
- enum_specifier gl_fog_mode @560-566
- struct_specifier gl_fog_attrib @572-587
- struct_specifier gl_hint_attrib @595-606
- struct_specifier gl_light_attrib @612-647
- struct_specifier gl_light @614-614
- struct_specifier gl_lightmodel @615-615
- struct_specifier gl_material @621-621
- struct_specifier gl_line_attrib @653-660
- struct_specifier gl_list_attrib @666-669
- struct_specifier gl_multisample_attrib @675-695
- struct_specifier gl_pixelmap @701-705
- struct_specifier gl_pixelmaps @711-723
- struct_specifier gl_pixelmap @713-713
- struct_specifier gl_pixelmap @714-714
- struct_specifier gl_pixelmap @715-715
- struct_specifier gl_pixelmap @716-716
- struct_specifier gl_pixelmap @717-717
- struct_specifier gl_pixelmap @718-718
- struct_specifier gl_pixelmap @719-719
- struct_specifier gl_pixelmap @720-720
- struct_specifier gl_pixelmap @721-721
- struct_specifier gl_pixelmap @722-722
- struct_specifier gl_pixel_attrib @729-755
- struct_specifier gl_point_attrib @761-773
- struct_specifier gl_polygon_attrib @779-794
- struct_specifier gl_scissor_rect @800-804
- struct_specifier gl_scissor_attrib @807-814
- struct_specifier gl_scissor_rect @810-810
- struct_specifier gl_scissor_rect @813-813
- struct_specifier gl_stencil_attrib @833-847
- struct_specifier gl_texture_image @873-905
- struct_specifier gl_texture_object @897-897
- enum_specifier gl_face_index @911-920
- struct_specifier gl_sampler_object @927-952
- struct_specifier util_dynarray @951-951
- struct_specifier gl_texture_object @959-1024
- struct_specifier gl_sampler_object @968-968
- struct_specifier gl_buffer_object @1012-1012
- struct_specifier gl_texture_image @1019-1019
- struct_specifier util_dynarray @1022-1022
- struct_specifier util_dynarray @1023-1023
- struct_specifier gl_tex_env_combine_state @1034-1048
- enum_specifier gl_tex_env_mode @1052-1069
- enum_specifier gl_tex_env_source @1073-1089
- enum_specifier gl_tex_env_operand @1093-1099
- struct_specifier gl_tex_env_argument @1103-1112
- struct_specifier gl_tex_env_combine_packed @1118-1129
- struct_specifier gl_tex_env_argument @1127-1127
- struct_specifier gl_tex_env_argument @1128-1128
- struct_specifier gl_texgen @1175-1181
- struct_specifier gl_texture_unit @1187-1202
- struct_specifier gl_sampler_object @1195-1195
- struct_specifier gl_texture_object @1198-1198
- struct_specifier gl_texture_object @1201-1201
- struct_specifier gl_fixedfunc_texture_unit @1209-1243
- struct_specifier gl_texgen @1217-1217
- struct_specifier gl_texgen @1218-1218
- struct_specifier gl_texgen @1219-1219
- struct_specifier gl_texgen @1220-1220
- struct_specifier gl_tex_env_combine_state @1227-1227
- struct_specifier gl_tex_env_combine_state @1233-1233
- struct_specifier gl_tex_env_combine_packed @1236-1236
- struct_specifier gl_tex_env_combine_state @1242-1242
- struct_specifier gl_texture_attrib @1249-1281
- struct_specifier gl_texture_object @1251-1251
- struct_specifier gl_buffer_object @1254-1254
- struct_specifier gl_texture_unit @1279-1279
- struct_specifier gl_fixedfunc_texture_unit @1280-1280
- struct_specifier gl_transform_attrib @1294-1308
- struct_specifier gl_viewport_attrib @1314-1322
- struct_specifier gl_buffer_mapping @1328-1334
- enum_specifier gl_buffer_usage @1340-1351
- struct_specifier gl_buffer_object @1357-1386
- struct_specifier gl_buffer_mapping @1376-1376
- struct_specifier hash_table @1380-1380
- struct_specifier gl_pixelstore_attrib @1392-1408
- struct_specifier gl_buffer_object @1407-1407
- enum_specifier gl_attribute_map_mode @1417-1423
- struct_specifier gl_array_attributes @1439-1477
- struct_specifier gl_vertex_format @1446-1446
- struct_specifier gl_vertex_buffer_binding @1485-1521
- struct_specifier gl_buffer_object @1490-1490
- struct_specifier gl_vertex_array_object @1528-1584
- struct_specifier gl_array_attributes @1550-1550
- struct_specifier gl_vertex_buffer_binding @1553-1553
- struct_specifier gl_buffer_object @1583-1583
- struct_specifier gl_array_attrib @1590-1653
- struct_specifier gl_vertex_array_object @1593-1593
- struct_specifier gl_vertex_array_object @1596-1596
- struct_specifier gl_vertex_array_object @1599-1599
- struct_specifier gl_vertex_array_object @1602-1602
- struct_specifier _mesa_HashTable @1605-1605
- struct_specifier gl_buffer_object @1626-1626
- struct_specifier gl_vertex_array_object @1634-1634
- struct_specifier gl_vertex_array_object @1648-1648
- struct_specifier gl_feedback @1659-1666
- struct_specifier gl_selection @1672-1683
- struct_specifier gl_1d_map @1689-1694
- struct_specifier gl_2d_map @1700-1707
- struct_specifier gl_evaluators @1713-1744
- struct_specifier gl_1d_map @1719-1719
- struct_specifier gl_1d_map @1720-1720
- struct_specifier gl_1d_map @1721-1721
- struct_specifier gl_1d_map @1722-1722
- struct_specifier gl_1d_map @1723-1723
- struct_specifier gl_1d_map @1724-1724
- struct_specifier gl_1d_map @1725-1725
- struct_specifier gl_1d_map @1726-1726
- struct_specifier gl_1d_map @1727-1727
- struct_specifier gl_2d_map @1734-1734
- struct_specifier gl_2d_map @1735-1735
- struct_specifier gl_2d_map @1736-1736
- struct_specifier gl_2d_map @1737-1737
- struct_specifier gl_2d_map @1738-1738
- struct_specifier gl_2d_map @1739-1739
- struct_specifier gl_2d_map @1740-1740
- struct_specifier gl_2d_map @1741-1741
- struct_specifier gl_2d_map @1742-1742
- struct_specifier gl_transform_feedback_varying_info @1747-1754
- struct_specifier gl_transform_feedback_output @1760-1776
- struct_specifier gl_transform_feedback_buffer @1779-1796
- struct_specifier gl_transform_feedback_info @1800-1817
- struct_specifier gl_transform_feedback_output @1807-1807
- struct_specifier gl_transform_feedback_varying_info @1813-1813
- struct_specifier gl_transform_feedback_buffer @1816-1816
- struct_specifier gl_transform_feedback_object @1823-1872
- struct_specifier gl_program @1851-1851
- struct_specifier gl_buffer_object @1855-1855
- struct_specifier gl_transform_feedback_state @1878-1893
- struct_specifier gl_buffer_object @1883-1883
- struct_specifier _mesa_HashTable @1886-1886
- struct_specifier gl_transform_feedback_object @1889-1889
- struct_specifier gl_transform_feedback_object @1892-1892
- struct_specifier gl_perf_monitor_object @1899-1928
- struct_specifier gl_perf_monitor_counter @1939-1955
- struct_specifier gl_perf_monitor_group @1958-1972
- struct_specifier gl_perf_monitor_counter @1970-1970
- struct_specifier gl_perf_query_object @1983-1989
- struct_specifier gl_perf_monitor_state @1995-2003
- struct_specifier gl_perf_monitor_group @1998-1998
- struct_specifier _mesa_HashTable @2002-2002
- struct_specifier gl_perf_query_state @2009-2012
- struct_specifier _mesa_HashTable @2011-2011
- struct_specifier gl_bindless_sampler @2018-2031
- struct_specifier gl_bindless_image @2037-2052
- enum_specifier gl_vertex_processing_mode @2060-2065
- struct_specifier gl_program @2071-2270
- struct_specifier shader_info @2074-2074
- struct_specifier nir_shader @2086-2086
- struct_specifier gl_program_parameter_list @2124-2124
- struct_specifier (anonymous) @2133-2269
- struct_specifier sh @2135-2221
- struct_specifier gl_shader_program_data @2137-2137
- struct_specifier gl_active_atomic_buffer @2139-2139
- struct_specifier gl_transform_feedback_info @2142-2142
- struct_specifier gl_uniform_storage @2155-2155
- struct_specifier gl_subroutine_function @2162-2162
- struct_specifier gl_uniform_block @2184-2184
- struct_specifier gl_uniform_block @2185-2185
- struct_specifier gl_bindless_sampler @2203-2203
- struct_specifier gl_bindless_image @2211-2211
- struct_specifier fs @2214-2219
- struct_specifier arb @2224-2268
- struct_specifier prog_instruction @2225-2225
- struct_specifier gl_program_state @2276-2280
- struct_specifier gl_vertex_program_state @2286-2322
- struct_specifier gl_program @2294-2294
- struct_specifier gl_program @2300-2300
- struct_specifier gl_program @2305-2305
- struct_specifier gl_program_cache @2308-2308
- struct_specifier gl_tess_ctrl_program_state @2327-2335
- struct_specifier gl_program @2330-2330
- struct_specifier gl_tess_eval_program_state @2340-2344
- struct_specifier gl_program @2343-2343
- struct_specifier gl_geometry_program_state @2349-2356
- struct_specifier gl_program @2355-2355
- struct_specifier gl_fragment_program_state @2361-2383
- struct_specifier gl_program @2367-2367
- struct_specifier gl_program @2374-2374
- struct_specifier gl_program @2379-2379
- struct_specifier gl_program_cache @2382-2382
- struct_specifier gl_compute_program_state @2389-2395
- struct_specifier gl_program @2394-2394
- struct_specifier atifs_instruction @2402-2402
- struct_specifier atifs_setupinst @2403-2403
- struct_specifier ati_fragment_shader @2408-2433
- struct_specifier atifs_instruction @2412-2412
- struct_specifier atifs_setupinst @2413-2413
- struct_specifier gl_program @2432-2432
- struct_specifier gl_ati_fragment_shader_state @2438-2444
- struct_specifier ati_fragment_shader @2443-2443
- struct_specifier gl_subroutine_function @2449-2455
- struct_specifier glsl_type @2454-2454
- struct_specifier gl_shader_info @2460-2541
- struct_specifier TessCtrl @2465-2471
- struct_specifier TessEval @2476-2493
- enum_specifier gl_tess_spacing @2483-2483
- struct_specifier Geom @2498-2516
- struct_specifier Comp @2522-2540
- enum_specifier gl_derivative_group @2539-2539
- struct_specifier gl_linked_shader @2546-2592
- struct_specifier gl_program @2554-2554
- struct_specifier exec_list @2580-2580
- struct_specifier exec_list @2581-2581
- struct_specifier exec_list @2582-2582
- struct_specifier glsl_symbol_table @2583-2583
- struct_specifier gl_shader_spirv_data @2591-2591
- enum_specifier gl_compile_status @2600-2605
- struct_specifier gl_shader @2610-2693
- enum_specifier gl_compile_status @2625-2625
- struct_specifier exec_list @2643-2643
- struct_specifier glsl_symbol_table @2644-2644
- struct_specifier gl_shader_info @2689-2689
- struct_specifier gl_shader_spirv_data @2692-2692
- struct_specifier gl_uniform_buffer_variable @2696-2715
- struct_specifier glsl_type @2712-2712
- struct_specifier gl_uniform_block @2718-2765
- struct_specifier gl_uniform_buffer_variable @2724-2724
- enum_specifier glsl_interface_packing @2763-2763
- struct_specifier gl_active_atomic_buffer @2771-2785
- struct_specifier gl_shader_variable @2791-2884
- struct_specifier glsl_type @2796-2796
- struct_specifier glsl_type @2801-2801
- struct_specifier glsl_type @2807-2807
- struct_specifier gl_program_resource @2889-2894
- enum_specifier gl_link_status @2900-2905
- struct_specifier gl_shader_program_data @2910-2967
- struct_specifier gl_uniform_storage @2919-2919
- struct_specifier gl_uniform_block @2924-2924
- struct_specifier gl_uniform_block @2925-2925
- struct_specifier gl_active_atomic_buffer @2927-2927
- struct_specifier hash_table_u64 @2946-2946
- struct_specifier gl_program_resource @2951-2951
- enum_specifier gl_link_status @2954-2954
- struct_specifier gl_shader_program @2973-3112
- struct_specifier gl_shader @2998-2998
- struct_specifier string_to_uint_map @3007-3007
- struct_specifier string_to_uint_map @3016-3016
- struct_specifier string_to_uint_map @3017-3017
- struct_specifier TransformFeedback @3026-3032
- struct_specifier gl_program @3034-3034
- enum_specifier gl_frag_depth_layout @3037-3037
- struct_specifier Geom @3043-3048
- struct_specifier Comp @3054-3059
- struct_specifier gl_shader_program_data @3062-3062
- struct_specifier gl_uniform_storage @3070-3070
- struct_specifier exec_list @3077-3077
- struct_specifier string_to_uint_map @3092-3092
- struct_specifier gl_linked_shader @3105-3105
- struct_specifier gl_pipeline_object @3131-3163
- struct_specifier gl_program @3147-3147
- struct_specifier gl_shader_program @3149-3149
- struct_specifier gl_shader_program @3156-3156
- struct_specifier gl_pipeline_shader_state @3168-3178
- struct_specifier gl_pipeline_object @3171-3171
- struct_specifier gl_pipeline_object @3174-3174
- struct_specifier _mesa_HashTable @3177-3177
- struct_specifier gl_shader_compiler_options @3183-3238
- struct_specifier nir_shader_compiler_options @3237-3237
- struct_specifier gl_query_object @3244-3254
- struct_specifier gl_query_state @3260-3284
- struct_specifier _mesa_HashTable @3262-3262
- struct_specifier gl_query_object @3263-3263
- struct_specifier gl_query_object @3264-3264
- struct_specifier gl_query_object @3267-3267
- struct_specifier gl_query_object @3270-3270
- struct_specifier gl_query_object @3271-3271
- struct_specifier gl_query_object @3274-3274
- struct_specifier gl_query_object @3275-3275
- struct_specifier gl_query_object @3278-3278
- struct_specifier gl_query_object @3281-3281
- struct_specifier gl_sync_object @3288-3299
- struct_specifier gl_shared_state @3305-3395
- struct_specifier _mesa_HashTable @3309-3309
- struct_specifier _mesa_HashTable @3310-3310
- struct_specifier _mesa_HashTable @3311-3311
- struct_specifier gl_texture_object @3314-3314
- struct_specifier gl_texture_object @3317-3317
- struct_specifier _mesa_HashTable @3334-3334
- struct_specifier gl_program @3335-3335
- struct_specifier gl_program @3336-3336
- struct_specifier _mesa_HashTable @3340-3340
- struct_specifier ati_fragment_shader @3341-3341
- struct_specifier _mesa_HashTable @3343-3343
- struct_specifier _mesa_HashTable @3346-3346
- struct_specifier _mesa_HashTable @3349-3349
- struct_specifier _mesa_HashTable @3350-3350
- struct_specifier set @3353-3353
- struct_specifier _mesa_HashTable @3356-3356
- struct_specifier hash_table_u64 @3359-3359
- struct_specifier hash_table_u64 @3360-3360
- struct_specifier shader_includes @3364-3364
- struct_specifier _mesa_HashTable @3382-3382
- struct_specifier _mesa_HashTable @3385-3385
- struct_specifier gl_renderbuffer @3404-3447
- struct_specifier gl_texture_image @3437-3437
- struct_specifier gl_context @3440-3440
- struct_specifier gl_renderbuffer @3440-3440
- struct_specifier gl_context @3443-3443
- struct_specifier gl_renderbuffer @3444-3444
- struct_specifier gl_renderbuffer_attachment @3454-3476
- struct_specifier gl_renderbuffer @3463-3463
- struct_specifier gl_texture_object @3469-3469
- struct_specifier gl_framebuffer @3484-3605
- struct_specifier gl_config @3505-3505
- struct_specifier DefaultGeometry @3518-3525
- struct_specifier gl_renderbuffer_attachment @3580-3580
- struct_specifier gl_renderbuffer @3597-3597
- struct_specifier gl_renderbuffer @3598-3598
- struct_specifier gl_framebuffer @3604-3604
- struct_specifier gl_precision @3611-3616
- struct_specifier gl_program_constants @3622-3688
- struct_specifier gl_precision @3672-3672
- struct_specifier gl_precision @3673-3673
- struct_specifier gl_constants @3694-4178
- struct_specifier ViewportBounds @3730-3733
- struct_specifier gl_program_constants @3736-3736
- struct_specifier QueryCounterBits @3740-3757
- struct_specifier SupportedMultisampleModes @4067-4071
- struct_specifier gl_shader_compiler_options @4109-4109
- struct_specifier spirv_supported_capabilities @4169-4169
- struct_specifier spirv_supported_extensions @4172-4172
- struct_specifier gl_extensions @4185-4447
- struct_specifier gl_matrix_stack @4453-4461
- include "dd.h" @4544
- struct_specifier gl_display_list @4554-4561
- struct_specifier gl_dlist_state @4567-4588
- struct_specifier gl_display_list @4569-4569
- struct_specifier Current @4582-4587
- struct_specifier gl_driver_flags @4597-4735
- struct_specifier gl_buffer_binding @4737-4749
- struct_specifier gl_buffer_object @4739-4739
- struct_specifier gl_image_unit @4754-4802
- struct_specifier gl_texture_object @4759-4759
- struct_specifier gl_subroutine_index_binding @4807-4811
- struct_specifier gl_texture_handle_object @4813-4818
- struct_specifier gl_texture_object @4815-4815
- struct_specifier gl_sampler_object @4816-4816
- struct_specifier gl_image_handle_object @4820-4824
- struct_specifier gl_image_unit @4822-4822
- struct_specifier gl_memory_object @4826-4831
- struct_specifier gl_semaphore_object @4833-4836
- struct_specifier gl_context @4846-5223
- struct_specifier gl_shared_state @4849-4849
- struct_specifier _glapi_table @4859-4859
- struct_specifier _glapi_table @4863-4863
- struct_specifier _glapi_table @4865-4865
- struct_specifier _glapi_table @4871-4871
- struct_specifier _glapi_table @4875-4875
- struct_specifier _glapi_table @4881-4881
- struct_specifier _glapi_table @4887-4887
- struct_specifier _glapi_table @4893-4893
- struct_specifier glthread_state @4897-4897
- struct_specifier gl_config @4899-4899
- struct_specifier gl_framebuffer @4900-4900
- struct_specifier gl_framebuffer @4901-4901
- struct_specifier gl_framebuffer @4902-4902
- struct_specifier gl_framebuffer @4903-4903
- struct_specifier dd_function_table @4908-4908
- struct_specifier gl_constants @4911-4911
- struct_specifier gl_matrix_stack @4915-4915
- struct_specifier gl_matrix_stack @4916-4916
- struct_specifier gl_matrix_stack @4917-4917
- struct_specifier gl_matrix_stack @4918-4918
- struct_specifier gl_matrix_stack @4919-4919
- struct_specifier gl_dlist_state @4926-4926
- struct_specifier gl_extensions @4932-4932
- struct_specifier gl_attrib_node @4941-4941
- struct_specifier gl_accum_attrib @4950-4950
- struct_specifier gl_colorbuffer_attrib @4951-4951
- struct_specifier gl_current_attrib @4952-4952
- struct_specifier gl_depthbuffer_attrib @4953-4953
- struct_specifier gl_eval_attrib @4954-4954
- struct_specifier gl_fog_attrib @4955-4955
- struct_specifier gl_hint_attrib @4956-4956
- struct_specifier gl_light_attrib @4957-4957
- struct_specifier gl_line_attrib @4958-4958
- struct_specifier gl_list_attrib @4959-4959
- struct_specifier gl_multisample_attrib @4960-4960
- struct_specifier gl_pixel_attrib @4961-4961
- struct_specifier gl_point_attrib @4962-4962
- struct_specifier gl_polygon_attrib @4963-4963
- struct_specifier gl_scissor_attrib @4965-4965
- struct_specifier gl_stencil_attrib @4966-4966
- struct_specifier gl_texture_attrib @4967-4967
- struct_specifier gl_transform_attrib @4968-4968
- struct_specifier gl_viewport_attrib @4969-4969
- struct_specifier gl_attrib_node @4976-4976
- struct_specifier gl_array_attrib @4981-4981
- struct_specifier gl_pixelstore_attrib @4982-4982
- struct_specifier gl_pixelstore_attrib @4983-4983
- struct_specifier gl_pixelstore_attrib @4984-4984
- struct_specifier gl_pixelmaps @4989-4989
- struct_specifier gl_evaluators @4991-4991
- struct_specifier gl_feedback @4992-4992
- struct_specifier gl_selection @4993-4993
- struct_specifier gl_program_state @4995-4995
- struct_specifier gl_vertex_program_state @4996-4996
- struct_specifier gl_fragment_program_state @4997-4997
- struct_specifier gl_geometry_program_state @4998-4998
- struct_specifier gl_compute_program_state @4999-4999
- struct_specifier gl_tess_ctrl_program_state @5000-5000
- struct_specifier gl_tess_eval_program_state @5001-5001
- struct_specifier gl_ati_fragment_shader_state @5002-5002
- struct_specifier gl_pipeline_shader_state @5004-5004
- struct_specifier gl_pipeline_object @5005-5005
- struct_specifier gl_pipeline_object @5024-5024
- struct_specifier nir_shader @5029-5029
- struct_specifier gl_query_state @5031-5031
- struct_specifier gl_transform_feedback_state @5033-5033
- struct_specifier gl_perf_monitor_state @5035-5035
- struct_specifier gl_perf_query_state @5036-5036
- struct_specifier gl_buffer_object @5038-5038
- struct_specifier gl_buffer_object @5039-5039
- struct_specifier gl_buffer_object @5040-5040
- struct_specifier gl_buffer_object @5042-5042
- struct_specifier gl_buffer_object @5043-5043
- struct_specifier gl_buffer_object @5045-5045
- struct_specifier gl_buffer_object @5051-5051
- struct_specifier gl_buffer_object @5057-5057
- struct_specifier gl_buffer_binding @5065-5065
- struct_specifier gl_buffer_binding @5074-5074
- struct_specifier gl_buffer_object @5081-5081
- struct_specifier gl_buffer_object @5087-5087
- struct_specifier gl_buffer_binding @5092-5092
- struct_specifier gl_image_unit @5098-5098
- struct_specifier gl_subroutine_index_binding @5100-5100
- struct_specifier gl_meta_state @5103-5103
- struct_specifier gl_renderbuffer @5106-5106
- struct_specifier gl_debug_state @5118-5118
- struct_specifier gl_driver_flags @5124-5124
- struct_specifier gl_list_extensions @5141-5141
- struct_specifier vbo_context @5185-5185
- struct_specifier st_context @5186-5186
- struct_specifier set @5195-5195
- struct_specifier disk_cache @5212-5212
- struct_specifier hash_table_u64 @5218-5218
- struct_specifier hash_table_u64 @5219-5219
- struct_specifier gl_memory_info @5228-5236
- enum_specifier _verbose @5248-5264
- enum_specifier _debug @5268-5275

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/shaderobj.h

Blob: `3f105d64d21b4692bf7908119ef8606462761249`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @30
- include "compiler/shader_enums.h" @31
- include "program/ir_to_mesa.h" @32
- include "util/macros.h" @33
- struct_specifier gl_shader_program_data @40-40
- struct_specifier gl_linked_shader @41-41
- struct_specifier dd_function_table @42-42
- struct_specifier gl_pipeline_object @43-43
- struct_specifier gl_context @50-50
- struct_specifier gl_context @53-53
- struct_specifier gl_context @57-57
- struct_specifier gl_shader @57-57
- struct_specifier gl_shader @58-58
- struct_specifier gl_shader @60-60
- struct_specifier gl_context @61-61
- struct_specifier gl_shader @63-63
- struct_specifier gl_context @64-64
- struct_specifier gl_context @69-69
- struct_specifier gl_shader_program @70-70
- struct_specifier gl_shader_program @71-71
- struct_specifier gl_context @74-74
- struct_specifier gl_shader_program_data @75-75
- struct_specifier gl_shader_program_data @76-76
- function_definition _mesa_reference_shader_program @78-85
- struct_specifier gl_context @79-79
- struct_specifier gl_shader_program @80-80
- struct_specifier gl_shader_program @81-81
- struct_specifier gl_shader @87-87
- struct_specifier gl_context @91-91
- struct_specifier gl_shader @91-91
- struct_specifier gl_context @94-94
- struct_specifier gl_linked_shader @95-95
- struct_specifier gl_shader_program @97-97
- struct_specifier gl_context @98-98
- struct_specifier gl_shader_program @100-100
- struct_specifier gl_context @101-101
- struct_specifier gl_shader_program @104-104
- struct_specifier gl_shader_program_data @107-107
- struct_specifier gl_context @111-111
- struct_specifier gl_shader_program @112-112
- struct_specifier gl_context @115-115
- struct_specifier gl_shader_program @116-116
- struct_specifier gl_context @119-119
- struct_specifier gl_shader_program @120-120
- struct_specifier dd_function_table @124-124
- function_definition _mesa_shader_enum_to_shader_stage @126-145
- function_definition _mesa_shader_stage_to_subroutine_prefix @149-168
- function_definition _mesa_shader_stage_from_subroutine_uniform @170-188
- function_definition _mesa_shader_stage_from_subroutine @190-208
- function_definition _mesa_shader_stage_to_subroutine @210-233
- function_definition _mesa_shader_stage_to_subroutine_uniform @235-256
- struct_specifier gl_pipeline_object @259-259

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/uniforms.h

Blob: `819cf90ba41eb0c4483d66281bf282d7b884df69`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @29
- include "compiler/glsl_types.h" @30
- include "compiler/glsl/ir_uniform.h" @31
- include "program/prog_parameter.h" @32
- struct_specifier gl_program @39-39
- struct_specifier _glapi_table @40-40
- struct_specifier gl_context @459-459
- struct_specifier gl_shader_program @459-459
- enum_specifier glsl_base_type @460-460
- struct_specifier gl_context @465-465
- struct_specifier gl_shader_program @465-465
- enum_specifier glsl_base_type @466-466
- struct_specifier gl_context @470-470
- struct_specifier gl_shader_program @470-470
- struct_specifier gl_context @473-473
- enum_specifier glsl_base_type @474-474
- struct_specifier gl_uniform_storage @478-478
- enum_specifier gl_uniform_driver_format @481-481
- struct_specifier gl_uniform_storage @485-485
- struct_specifier gl_uniform_storage @488-488
- struct_specifier gl_shader_program @493-493
- struct_specifier gl_program @494-494
- struct_specifier gl_shader_program @497-497
- struct_specifier gl_pipeline_object @500-500
- struct_specifier gl_context @503-503
- struct_specifier gl_uniform_storage @504-504
- struct_specifier gl_builtin_uniform_element @506-510
- struct_specifier gl_builtin_uniform_desc @512-516
- struct_specifier gl_builtin_uniform_element @514-514

### third_party/rust/glslopt/glsl-optimizer/src/mesa/main/version.h

Blob: `4469509c08efb01048e0802acb95c32abe05fd3c`. Grammar: cpp. Status: syntax-clean.

- include <stdbool.h> @30
- include "glheader.h" @31
- include "menums.h" @32
- struct_specifier gl_context @34-34
- struct_specifier gl_constants @35-35
- struct_specifier gl_extensions @36-36
- struct_specifier gl_extensions @39-39
- struct_specifier gl_constants @40-40
- struct_specifier gl_context @43-43
- struct_specifier gl_constants @46-46
- struct_specifier gl_context @50-50
- struct_specifier gl_constants @53-53
- struct_specifier gl_context @56-56
- struct_specifier gl_context @59-59
- struct_specifier gl_context @62-62

### third_party/rust/glslopt/glsl-optimizer/src/mesa/math/m_matrix.h

Blob: `c34d9e3022f7e9044ec8fc46e027278beed00576`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @35
- enum_specifier GLmatrixtype @62-70
- struct_specifier GLmatrix @75-82
- enum_specifier GLmatrixtype @81-81

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/dummy_errors.c

Blob: `d69f54d1d054f79b43ae27e9806ad2cf7caea4fe`. Grammar: c. Status: syntax-clean.

- include <stdio.h> @23
- include "main/errors.h" @24
- function_definition _mesa_error_no_memory @26-30

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/ir_to_mesa.h

Blob: `33eb801bae834286fd3f052628d0d75173e8e311`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @27
- struct_specifier gl_context @33-33
- struct_specifier gl_program @34-34
- struct_specifier gl_shader @35-35
- struct_specifier gl_shader_program @36-36
- struct_specifier gl_linked_shader @37-37
- struct_specifier gl_program_parameter_list @38-38
- struct_specifier gl_context @40-40
- struct_specifier gl_shader_program @40-40
- struct_specifier gl_context @41-41
- struct_specifier gl_shader_program @41-41
- struct_specifier gl_context @44-44
- struct_specifier gl_shader_program @45-45
- struct_specifier gl_linked_shader @47-47
- struct_specifier gl_program_parameter_list @48-48
- struct_specifier gl_context @51-51
- struct_specifier gl_shader_program @52-52
- struct_specifier gl_program @53-53

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/prog_instruction.h

Blob: `328566a10f1e4d03877266c993908c0ab9a1e088`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @41
- enum_specifier prog_opcode @111-175
- struct_specifier prog_src_register @188-203
- struct_specifier prog_dst_register @209-215
- struct_specifier prog_instruction @221-257
- enum_specifier prog_opcode @223-223
- struct_specifier prog_src_register @224-224
- struct_specifier prog_dst_register @225-225
- struct_specifier gl_program @264-264
- struct_specifier prog_instruction @267-267
- struct_specifier prog_instruction @269-269
- struct_specifier prog_instruction @270-270
- struct_specifier prog_instruction @271-271
- enum_specifier prog_opcode @274-274
- enum_specifier prog_opcode @277-277
- enum_specifier prog_opcode @280-280
- struct_specifier prog_instruction @283-283
- enum_specifier prog_opcode @286-286

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/prog_parameter.h

Blob: `1fb0c5b7d1fbe920f0828558097cf69ee9827899`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @34
- include <stdint.h> @35
- include "prog_statevars.h" @36
- include <string.h> @38
- enum_specifier gl_register_file @54-74
- struct_specifier gl_program_parameter @93-128
- struct_specifier gl_program_parameter_list @134-144
- struct_specifier gl_program_parameter @139-139
- struct_specifier gl_program_parameter_list @147-147
- struct_specifier gl_program_parameter_list @150-150
- struct_specifier gl_program_parameter_list @154-154
- struct_specifier gl_program_parameter_list @157-157
- struct_specifier gl_program_parameter_list @161-161
- struct_specifier gl_program_parameter_list @169-169
- function_definition _mesa_add_unnamed_constant @173-180
- struct_specifier gl_program_parameter_list @174-174
- struct_specifier gl_program_parameter_list @183-183
- struct_specifier gl_program_parameter_list @188-188
- function_definition _mesa_lookup_parameter_index @192-207
- struct_specifier gl_program_parameter_list @193-193
- function_definition _mesa_gl_datatype_is_64bit @209-238

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/prog_statevars.h

Blob: `de457d1a7f42b9edf05c0933f28dd6f9e2835c7c`. Grammar: cpp. Status: contains-errors.

- include "main/glheader.h" @29
- include "compiler/shader_enums.h" @30
- struct_specifier gl_context @38-38
- struct_specifier gl_program_parameter_list @39-39
- enum_specifier gl_state_index_ @51-135
- struct_specifier gl_context @139-139
- struct_specifier gl_program_parameter_list @140-140

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/program.h

Blob: `7de6804047a22e48c761e2ac0e371f0bd5f6ddb3`. Grammar: cpp. Status: contains-errors.

- include "prog_parameter.h" @43
- struct_specifier gl_program @50-50
- struct_specifier gl_context @54-54
- struct_specifier gl_context @57-57
- struct_specifier gl_context @60-60
- struct_specifier gl_context @63-63
- struct_specifier gl_program @65-65
- struct_specifier gl_program @66-66
- struct_specifier gl_program @69-69
- struct_specifier gl_context @70-70
- struct_specifier gl_context @74-74
- struct_specifier gl_program @74-74
- struct_specifier gl_program @76-76
- struct_specifier gl_context @77-77
- struct_specifier gl_context @80-80
- struct_specifier gl_program @81-81
- struct_specifier gl_program @82-82
- function_definition _mesa_reference_program @84-91
- struct_specifier gl_context @85-85
- struct_specifier gl_program @86-86
- struct_specifier gl_program @87-87
- struct_specifier gl_program @94-94
- struct_specifier gl_program @97-97
- struct_specifier gl_program @101-101
- struct_specifier gl_context @110-110
- struct_specifier gl_program @111-111
- function_definition _mesa_program_enum_to_shader_stage @113-135
- function_definition _mesa_shader_stage_to_program @138-158
- struct_specifier gl_program @162-162

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/symbol_table.c

Blob: `f86588b76bda6b99f3f7f6b2219f03abac04cf11`. Grammar: c. Status: syntax-clean.

- include "main/errors.h" @25
- include "symbol_table.h" @26
- include "util/hash_table.h" @27
- include "util/u_string.h" @28
- struct_specifier symbol @30-57
- struct_specifier symbol @40-40
- struct_specifier symbol @48-48
- struct_specifier scope_level @63-69
- struct_specifier scope_level @65-65
- struct_specifier symbol @68-68
- struct_specifier _mesa_symbol_table @75-84
- struct_specifier hash_table @77-77
- struct_specifier scope_level @80-80
- function_definition _mesa_symbol_table_pop_scope @86-115
- struct_specifier _mesa_symbol_table @87-87
- struct_specifier scope_level @89-89
- struct_specifier symbol @90-90
- struct_specifier symbol @98-98
- struct_specifier hash_entry @99-99
- function_definition _mesa_symbol_table_push_scope @118-130
- struct_specifier _mesa_symbol_table @119-119
- struct_specifier scope_level @121-121
- function_definition find_symbol @133-138
- struct_specifier symbol @133-133
- struct_specifier _mesa_symbol_table @134-134
- struct_specifier hash_entry @136-136
- struct_specifier symbol @137-137
- function_definition _mesa_symbol_table_symbol_scope @149-161
- struct_specifier _mesa_symbol_table @150-150
- struct_specifier symbol @153-153
- function_definition _mesa_symbol_table_find_symbol @164-173
- struct_specifier _mesa_symbol_table @165-165
- struct_specifier symbol @168-168
- function_definition _mesa_symbol_table_add_symbol @176-214
- struct_specifier _mesa_symbol_table @177-177
- struct_specifier symbol @180-180
- struct_specifier symbol @181-181
- function_definition _mesa_symbol_table_replace_symbol @216-229
- struct_specifier _mesa_symbol_table @217-217
- struct_specifier symbol @221-221
- function_definition _mesa_symbol_table_add_global_symbol @231-285
- struct_specifier _mesa_symbol_table @232-232
- struct_specifier scope_level @235-235
- struct_specifier symbol @236-236
- struct_specifier symbol @237-237
- function_definition _mesa_symbol_table_ctor @289-302
- struct_specifier _mesa_symbol_table @289-289
- struct_specifier _mesa_symbol_table @292-292
- function_definition _mesa_symbol_table_dtor @305-314
- struct_specifier _mesa_symbol_table @306-306

### third_party/rust/glslopt/glsl-optimizer/src/mesa/program/symbol_table.h

Blob: `6db2164fc21af09e083d1ab4e25035be267a39cd`. Grammar: cpp. Status: contains-errors.

- struct_specifier _mesa_symbol_table @30-30
- struct_specifier _mesa_symbol_table @32-32
- struct_specifier _mesa_symbol_table @34-34
- struct_specifier _mesa_symbol_table @36-36
- struct_specifier _mesa_symbol_table @39-39
- struct_specifier _mesa_symbol_table @44-44
- struct_specifier _mesa_symbol_table @48-48
- struct_specifier _mesa_symbol_table @51-51
- struct_specifier _mesa_symbol_table @54-54
- struct_specifier _mesa_symbol_table @56-56

### third_party/rust/glslopt/glsl-optimizer/src/mesa/vbo/vbo.h

Blob: `bd99e2465141e25c33df20080308e12b2e888402`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @34
- include "main/glheader.h" @35
- include "main/draw.h" @36
- struct_specifier gl_context @42-42
- struct_specifier gl_context @45-45
- struct_specifier gl_context @48-48
- struct_specifier gl_context @51-51
- struct_specifier gl_context @54-54
- struct_specifier gl_context @57-57
- struct_specifier _glapi_table @58-58
- struct_specifier gl_context @61-61
- struct_specifier _glapi_table @62-62
- struct_specifier gl_context @65-65
- struct_specifier gl_context @68-68
- struct_specifier gl_context @71-71
- struct_specifier gl_context @75-75
- struct_specifier gl_context @78-78
- struct_specifier gl_context @81-81
- struct_specifier gl_display_list @81-81
- struct_specifier gl_context @84-84
- struct_specifier gl_buffer_object @88-88
- struct_specifier gl_context @97-97
- struct_specifier _mesa_prim @97-97
- struct_specifier _mesa_index_buffer @98-98
- struct_specifier gl_context @102-102
- struct_specifier _mesa_prim @103-103
- struct_specifier _mesa_index_buffer @105-105
- struct_specifier gl_buffer_object @107-107
- struct_specifier gl_array_attributes @111-111
- struct_specifier gl_context @112-112
- struct_specifier gl_vertex_buffer_binding @115-115
- struct_specifier gl_context @116-116

### third_party/rust/glslopt/glsl-optimizer/src/util/bitscan.h

Blob: `760d4a527eb711ba4834308ba10ec55eeb6d746c`. Grammar: cpp. Status: contains-errors.

- include <assert.h> @32
- include <stdint.h> @33
- include <stdbool.h> @34
- include <string.h> @35
- include <intrin.h> @38
- include <popcntintrin.h> @42
- include "c99_compat.h" @45
- function_definition ffs @59-67
- function_definition ffsll @76-84
- function_definition u_bit_scan @99-105
- function_definition u_bit_scan64 @107-113
- function_definition util_is_power_of_two_or_zero @120-124
- function_definition util_is_power_of_two_or_zero64 @131-135
- function_definition util_is_power_of_two_nonzero @142-159
- function_definition u_bit_scan_consecutive_range @173-185
- function_definition u_bit_scan_consecutive_range64 @187-199
- function_definition util_last_bit @207-226
- function_definition util_last_bit64 @233-252
- function_definition util_last_bit_signed @259-266
- function_definition u_bit_consecutive @271-278
- function_definition u_bit_consecutive64 @280-287
- function_definition util_bitcount @292-310
- function_definition util_bitcount64 @312-320

### third_party/rust/glslopt/glsl-optimizer/src/util/bitset.h

Blob: `0fdfe205f39e93ed525ae8f74bebd5310bce06dc`. Grammar: cpp. Status: syntax-clean.

- include "util/bitscan.h" @34
- include "util/macros.h" @35
- function_definition __bitset_ffs @85-96
- function_definition __bitset_next_set @100-130

### third_party/rust/glslopt/glsl-optimizer/src/util/blob.c

Blob: `db192146ac1f2c707c73c9127d84ee35a2fb5f3a`. Grammar: c. Status: contains-errors.

- include <string.h> @24
- include "blob.h" @26
- include "u_math.h" @27
- include <valgrind.h> @30
- include <memcheck.h> @31
- function_definition grow_to_fit @43-77
- struct_specifier blob @44-44
- function_definition align_blob @85-100
- struct_specifier blob @86-86
- function_definition align_blob_reader @102-106
- struct_specifier blob_reader @103-103
- function_definition blob_init @108-116
- struct_specifier blob @109-109
- function_definition blob_init_fixed @118-126
- struct_specifier blob @119-119
- function_definition blob_finish_get_buffer @128-137
- struct_specifier blob @129-129
- function_definition blob_overwrite_bytes @139-155
- struct_specifier blob @140-140
- function_definition blob_write_bytes @157-170
- struct_specifier blob @158-158
- function_definition blob_reserve_bytes @172-184
- struct_specifier blob @173-173
- function_definition blob_reserve_uint32 @186-191
- struct_specifier blob @187-187
- function_definition blob_reserve_intptr @193-198
- struct_specifier blob @194-194
- function_definition blob_overwrite_uint8 @217-224
- struct_specifier blob @218-218
- function_definition blob_overwrite_uint32 @226-233
- struct_specifier blob @227-227
- function_definition blob_overwrite_intptr @235-242
- struct_specifier blob @236-236
- function_definition blob_write_string @244-248
- struct_specifier blob @245-245
- function_definition blob_reader_init @250-257
- struct_specifier blob_reader @251-251
- function_definition ensure_can_read @263-275
- struct_specifier blob_reader @264-264
- function_definition blob_read_bytes @277-290
- struct_specifier blob_reader @278-278
- function_definition blob_copy_bytes @292-302
- struct_specifier blob_reader @293-293
- function_definition blob_skip_bytes @304-309
- struct_specifier blob_reader @305-305
- function_definition blob_read_string @336-368
- struct_specifier blob_reader @337-337

### third_party/rust/glslopt/glsl-optimizer/src/util/blob.h

Blob: `e1e156eb43fa1e40f9dc34d20a80f826f48c42f5`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @27
- include <stddef.h> @28
- include <stdint.h> @29
- include <stdlib.h> @30
- struct_specifier blob @49-70
- struct_specifier blob_reader @80-85
- struct_specifier blob @91-91
- struct_specifier blob @105-105
- function_definition blob_finish @113-118
- struct_specifier blob @114-114
- struct_specifier blob @121-121
- struct_specifier blob @129-129
- struct_specifier blob @142-142
- struct_specifier blob @150-150
- struct_specifier blob @158-158
- struct_specifier blob @173-173
- struct_specifier blob @184-184
- struct_specifier blob @197-197
- struct_specifier blob @212-212
- struct_specifier blob @225-225
- struct_specifier blob @247-247
- struct_specifier blob @262-262
- struct_specifier blob @275-275
- struct_specifier blob @290-290
- struct_specifier blob @300-300
- struct_specifier blob_reader @314-314
- struct_specifier blob_reader @327-327
- struct_specifier blob_reader @334-334
- struct_specifier blob_reader @340-340
- struct_specifier blob_reader @349-349
- struct_specifier blob_reader @361-361
- struct_specifier blob_reader @373-373
- struct_specifier blob_reader @385-385
- struct_specifier blob_reader @397-397
- struct_specifier blob_reader @412-412

### third_party/rust/glslopt/glsl-optimizer/src/util/compiler.h

Blob: `43a06b43139da8fe35d94fd70863784b0ed5f6ac`. Grammar: cpp. Status: syntax-clean.

- include <assert.h> @37
- include "util/macros.h" @39
- include "c99_compat.h" @41
- include <byteswap.h> @52
- include <CoreFoundation/CFByteOrder.h> @55
- include <sys/types.h> @58
- include <sys/endian.h> @61

### third_party/rust/glslopt/glsl-optimizer/src/util/crc32.c

Blob: `425046ab5fd02aa25dd24bedf886edb5076e7b24`. Grammar: c. Status: syntax-clean.

- include <zlib.h> @37
- include "crc32.h" @39
- function_definition util_hash_crc32 @114-134

### third_party/rust/glslopt/glsl-optimizer/src/util/crc32.h

Blob: `b6a21f4170535a8bc4000f09da927dc10b3219c5`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @38
- include <stdint.h> @39

### third_party/rust/glslopt/glsl-optimizer/src/util/debug.c

Blob: `89ae61310746455ecb037a6a0dda837eb320c223`. Grammar: c. Status: syntax-clean.

- include <errno.h> @24
- include <string.h> @25
- include "debug.h" @26
- include "u_string.h" @27
- function_definition parse_debug_string @29-54
- struct_specifier debug_control @31-31
- function_definition comma_separated_list_contains @56-68
- function_definition env_var_as_boolean @75-95
- function_definition env_var_as_unsigned @100-114

### third_party/rust/glslopt/glsl-optimizer/src/util/debug.h

Blob: `bbcc19755458872b395c24c098f7333011c8590c`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @27
- include <stdbool.h> @28
- struct_specifier debug_control @34-37
- struct_specifier debug_control @41-41

### third_party/rust/glslopt/glsl-optimizer/src/util/detect_os.h

Blob: `6506948e0359086c71a4480021602dd73ce81763`. Grammar: cpp. Status: syntax-clean.


### third_party/rust/glslopt/glsl-optimizer/src/util/disk_cache.c

Blob: `a92d621927a857f262e15ea100db65a513b755f2`. Grammar: c. Status: contains-errors.

- include <ctype.h> @26
- include <ftw.h> @27
- include <string.h> @28
- include <stdlib.h> @29
- include <stdio.h> @30
- include <sys/file.h> @31
- include <sys/types.h> @32
- include <sys/stat.h> @33
- include <sys/mman.h> @34
- include <unistd.h> @35
- include <fcntl.h> @36
- include <pwd.h> @37
- include <errno.h> @38
- include <dirent.h> @39
- include <inttypes.h> @40
- include "zlib.h" @41
- include "zstd.h" @44
- include "util/crc32.h" @47
- include "util/debug.h" @48
- include "util/rand_xor.h" @49
- include "util/u_atomic.h" @50
- include "util/u_queue.h" @51
- include "util/mesa-sha1.h" @52
- include "util/ralloc.h" @53
- include "util/compiler.h" @54
- include "disk_cache.h" @56
- struct_specifier disk_cache @84-114
- struct_specifier util_queue @90-90
- struct_specifier disk_cache_put_job @116-130
- struct_specifier util_queue_fence @117-117
- struct_specifier disk_cache @119-119
- struct_specifier cache_item_metadata @129-129
- function_definition mkdir_if_needed @137-163
- struct_specifier stat @140-140
- function_definition concatenate_and_mkdir @175-190
- struct_specifier stat @179-179
- function_definition disk_cache_create @198-443
- struct_specifier disk_cache @198-198
- struct_specifier disk_cache @203-203
- struct_specifier stat @207-207
- struct_specifier passwd @265-265
- function_definition disk_cache_destroy @445-455
- struct_specifier disk_cache @446-446
- function_definition disk_cache_wait_for_idle @457-461
- struct_specifier disk_cache @458-458
- function_definition get_cache_file @468-483
- struct_specifier disk_cache @469-469
- function_definition make_cache_file_directory @490-502
- struct_specifier disk_cache @491-491
- function_definition choose_lru_file_matching @512-563
- struct_specifier stat @515-515
- struct_specifier dirent @519-519
- struct_specifier stat @533-533
- function_definition is_regular_non_tmp_file @568-579
- struct_specifier stat @569-569
- function_definition unlink_lru_file_from_directory @582-601
- struct_specifier stat @585-585
- function_definition is_two_character_sub_directory @606-641
- struct_specifier stat @607-607
- struct_specifier dirent @629-629
- function_definition evict_lru_item @643-685
- struct_specifier disk_cache @644-644
- function_definition disk_cache_remove @687-707
- struct_specifier disk_cache @688-688
- struct_specifier stat @690-690
- function_definition read_all @709-722
- function_definition write_all @724-737
- function_definition deflate_and_write_to_disk @749-835
- function_definition create_put_job @837-880
- struct_specifier disk_cache_put_job @837-837
- struct_specifier disk_cache @838-838
- struct_specifier cache_item_metadata @840-840
- struct_specifier disk_cache_put_job @842-842
- struct_specifier disk_cache_put_job @842-842
- struct_specifier disk_cache_put_job @843-843
- function_definition destroy_put_job @882-891
- struct_specifier disk_cache_put_job @886-886
- struct_specifier disk_cache_put_job @886-886
- struct_specifier cache_entry_file_data @893-896
- function_definition cache_put @898-1064
- struct_specifier disk_cache_put_job @906-906
- struct_specifier disk_cache_put_job @906-906
- struct_specifier flock @948-948
- struct_specifier cache_entry_file_data @1018-1018
- struct_specifier stat @1045-1045
- function_definition disk_cache_put @1066-1087
- struct_specifier disk_cache @1067-1067
- struct_specifier cache_item_metadata @1069-1069
- struct_specifier disk_cache_put_job @1079-1079
- function_definition inflate_cache_data @1092-1131
- function_definition disk_cache_get @1133-1274
- struct_specifier disk_cache @1134-1134
- struct_specifier stat @1137-1137
- struct_specifier cache_entry_file_data @1227-1227
- function_definition disk_cache_put_key @1276-1294
- struct_specifier disk_cache @1277-1277
- function_definition disk_cache_has_key @1303-1321
- struct_specifier disk_cache @1304-1304
- function_definition disk_cache_compute_key @1323-1334
- struct_specifier disk_cache @1324-1324
- struct_specifier mesa_sha1 @1327-1327
- function_definition disk_cache_set_callbacks @1336-1342
- struct_specifier disk_cache @1337-1337

### third_party/rust/glslopt/glsl-optimizer/src/util/disk_cache.h

Blob: `09b316e6e8d0600e35c224dcea923d7b5d4bf1e3`. Grammar: cpp. Status: contains-errors.

- include <dlfcn.h> @28
- include <stdio.h> @29
- include "util/build_id.h" @30
- include <assert.h> @32
- include <stdint.h> @33
- include <stdbool.h> @34
- include <sys/stat.h> @35
- include "util/mesa-sha1.h" @36
- struct_specifier cache_item_metadata @64-75
- struct_specifier disk_cache @77-77
- function_definition disk_cache_format_hex_id @79-92
- function_definition disk_cache_get_function_timestamp @95-116
- struct_specifier stat @99-99
- function_definition disk_cache_get_function_identifier @118-134
- struct_specifier mesa_sha1 @119-119
- struct_specifier build_id_note @124-124
- struct_specifier disk_cache @167-167
- struct_specifier disk_cache @175-175
- struct_specifier disk_cache @181-181
- struct_specifier disk_cache @187-187
- struct_specifier disk_cache @199-199
- struct_specifier cache_item_metadata @201-201
- struct_specifier disk_cache @217-217
- struct_specifier disk_cache @229-229
- struct_specifier disk_cache @242-242
- struct_specifier disk_cache @248-248
- struct_specifier disk_cache @252-252
- function_definition disk_cache_create @257-262
- struct_specifier disk_cache @257-257
- function_definition disk_cache_destroy @264-267
- struct_specifier disk_cache @265-265
- function_definition disk_cache_put @269-275
- struct_specifier disk_cache @270-270
- struct_specifier cache_item_metadata @272-272
- function_definition disk_cache_remove @277-281
- struct_specifier disk_cache @278-278
- function_definition disk_cache_get @283-287
- struct_specifier disk_cache @284-284
- function_definition disk_cache_put_key @289-293
- struct_specifier disk_cache @290-290
- function_definition disk_cache_has_key @295-299
- struct_specifier disk_cache @296-296
- function_definition disk_cache_compute_key @301-306
- struct_specifier disk_cache @302-302
- function_definition disk_cache_set_callbacks @308-313
- struct_specifier disk_cache @309-309

### third_party/rust/glslopt/glsl-optimizer/src/util/fast_urem_by_const.h

Blob: `beb253d2291e0dfb70dd08db80affacf1b91ac66`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @24
- function_definition _mul32by64_hi @47-64
- function_definition util_fast_urem32 @66-73

### third_party/rust/glslopt/glsl-optimizer/src/util/fnv1a.h

Blob: `0f92d0b0e405f9ebd6b161ce9e05c5ec6b6c3257`. Grammar: cpp. Status: syntax-clean.

- enum_specifier _FNV1A_H @31-33
- function_definition _mesa_fnv32_1a_accumulate_block @44-56

### third_party/rust/glslopt/glsl-optimizer/src/util/format/u_format.h

Blob: `1b6f0b882893a316bbcdf01fbc1196a41a1decf4`. Grammar: cpp. Status: contains-errors.

- include "pipe/p_format.h" @33
- include "pipe/p_defines.h" @34
- include "util/u_debug.h" @35
- struct_specifier pipe_screen @38-38
- enum_specifier util_format_layout @52-101
- struct_specifier util_format_block @104-117
- enum_specifier util_format_type @120-126
- enum_specifier util_format_colorspace @129-134
- struct_specifier util_format_channel_description @137-144
- struct_specifier util_format_description @147-425
- enum_specifier pipe_format @149-149
- struct_specifier util_format_block @161-161
- enum_specifier util_format_layout @163-163
- struct_specifier util_format_channel_description @226-226
- enum_specifier util_format_colorspace @242-242
- struct_specifier util_format_description @428-428
- enum_specifier pipe_format @429-429
- function_definition util_format_name @436-447
- enum_specifier pipe_format @437-437
- struct_specifier util_format_description @439-439
- function_definition util_format_short_name @449-460
- enum_specifier pipe_format @450-450
- struct_specifier util_format_description @452-452
- function_definition util_format_is_plain @465-475
- enum_specifier pipe_format @466-466
- struct_specifier util_format_description @468-468
- function_definition util_format_is_compressed @477-500
- enum_specifier pipe_format @478-478
- struct_specifier util_format_description @480-480
- function_definition util_format_is_s3tc @502-513
- enum_specifier pipe_format @503-503
- struct_specifier util_format_description @505-505
- function_definition util_format_is_etc @515-526
- enum_specifier pipe_format @516-516
- struct_specifier util_format_description @518-518
- function_definition util_format_is_srgb @528-533
- enum_specifier pipe_format @529-529
- struct_specifier util_format_description @531-531
- function_definition util_format_has_depth @535-540
- struct_specifier util_format_description @536-536
- function_definition util_format_has_stencil @542-547
- struct_specifier util_format_description @543-543
- function_definition util_format_is_depth_or_stencil @549-561
- enum_specifier pipe_format @550-550
- struct_specifier util_format_description @552-552
- function_definition util_format_is_depth_and_stencil @563-575
- enum_specifier pipe_format @564-564
- struct_specifier util_format_description @566-566
- function_definition util_format_get_depth_only @580-596
- enum_specifier pipe_format @580-580
- enum_specifier pipe_format @581-581
- function_definition util_format_is_yuv @598-609
- enum_specifier pipe_format @599-599
- struct_specifier util_format_description @601-601
- function_definition util_get_depth_format_type @614-624
- struct_specifier util_format_description @615-615
- struct_specifier util_format_description @634-634
- function_definition util_format_get_mask @641-663
- enum_specifier pipe_format @642-642
- struct_specifier util_format_description @644-644
- function_definition util_format_colormask @671-694
- struct_specifier util_format_description @672-672
- function_definition util_format_colormask_full @703-707
- struct_specifier util_format_description @704-704
- enum_specifier pipe_format @711-711
- enum_specifier pipe_format @715-715
- enum_specifier pipe_format @719-719
- enum_specifier pipe_format @722-722
- enum_specifier pipe_format @725-725
- enum_specifier pipe_format @729-729
- enum_specifier pipe_format @732-732
- enum_specifier pipe_format @735-735
- enum_specifier pipe_format @738-738
- enum_specifier pipe_format @741-741
- enum_specifier pipe_format @744-744
- enum_specifier pipe_format @747-747
- enum_specifier pipe_format @750-750
- struct_specifier util_format_description @758-758
- struct_specifier util_format_description @759-759
- function_definition util_format_is_rgba8_variant @768-790
- struct_specifier util_format_description @769-769
- function_definition util_format_get_blocksizebits @795-806
- enum_specifier pipe_format @796-796
- struct_specifier util_format_description @798-798
- function_definition util_format_get_blocksize @811-824
- enum_specifier pipe_format @812-812
- function_definition util_format_get_blockwidth @826-837
- enum_specifier pipe_format @827-827
- struct_specifier util_format_description @829-829
- function_definition util_format_get_blockheight @839-850
- enum_specifier pipe_format @840-840
- struct_specifier util_format_description @842-842
- function_definition util_format_get_blockdepth @852-863
- enum_specifier pipe_format @853-853
- struct_specifier util_format_description @855-855
- function_definition util_format_get_nblocksx @865-871
- enum_specifier pipe_format @866-866
- function_definition util_format_get_nblocksy @873-879
- enum_specifier pipe_format @874-874
- function_definition util_format_get_nblocksz @881-887
- enum_specifier pipe_format @882-882
- function_definition util_format_get_nblocks @889-896
- enum_specifier pipe_format @890-890
- function_definition util_format_get_stride @898-903
- enum_specifier pipe_format @899-899
- function_definition util_format_get_2d_size @905-911
- enum_specifier pipe_format @906-906
- function_definition util_format_get_component_bits @913-954
- enum_specifier pipe_format @914-914
- enum_specifier util_format_colorspace @915-915
- struct_specifier util_format_description @918-918
- enum_specifier util_format_colorspace @919-919
- function_definition util_format_srgb @960-1065
- enum_specifier pipe_format @960-960
- enum_specifier pipe_format @961-961
- function_definition util_format_linear @1071-1172
- enum_specifier pipe_format @1071-1071
- enum_specifier pipe_format @1072-1072
- function_definition util_format_stencil_only @1178-1201
- enum_specifier pipe_format @1178-1178
- enum_specifier pipe_format @1179-1179
- function_definition util_format_intensity_to_red @1207-1239
- enum_specifier pipe_format @1207-1207
- enum_specifier pipe_format @1208-1208
- function_definition util_format_luminance_to_red @1245-1317
- enum_specifier pipe_format @1245-1245
- enum_specifier pipe_format @1246-1246
- function_definition util_format_get_num_planes @1319-1330
- enum_specifier pipe_format @1320-1320
- function_definition util_format_get_plane_format @1332-1350
- enum_specifier pipe_format @1332-1332
- enum_specifier pipe_format @1333-1333
- function_definition util_format_get_plane_width @1352-1368
- enum_specifier pipe_format @1353-1353
- function_definition util_format_get_plane_height @1370-1386
- enum_specifier pipe_format @1371-1371
- struct_specifier pipe_screen @1388-1388
- enum_specifier pipe_format @1389-1389
- enum_specifier pipe_texture_target @1390-1390
- function_definition util_format_get_nr_components @1399-1404
- enum_specifier pipe_format @1400-1400
- struct_specifier util_format_description @1402-1402
- function_definition util_format_get_first_non_void_channel @1410-1424
- enum_specifier pipe_format @1411-1411
- struct_specifier util_format_description @1413-1413
- function_definition util_format_is_unorm8 @1431-1440
- struct_specifier util_format_description @1432-1432
- function_definition util_format_unpack_z_float @1442-1449
- enum_specifier pipe_format @1443-1443
- struct_specifier util_format_description @1446-1446
- function_definition util_format_unpack_z_32unorm @1451-1458
- enum_specifier pipe_format @1452-1452
- struct_specifier util_format_description @1455-1455
- function_definition util_format_unpack_s_8uint @1460-1467
- enum_specifier pipe_format @1461-1461
- struct_specifier util_format_description @1464-1464
- function_definition util_format_unpack_rgba_float @1469-1476
- enum_specifier pipe_format @1470-1470
- struct_specifier util_format_description @1473-1473
- function_definition util_format_unpack_rgba @1482-1494
- enum_specifier pipe_format @1483-1483
- struct_specifier util_format_description @1486-1486
- function_definition util_format_pack_z_float @1496-1503
- enum_specifier pipe_format @1497-1497
- struct_specifier util_format_description @1500-1500
- function_definition util_format_pack_z_32unorm @1505-1512
- enum_specifier pipe_format @1506-1506
- struct_specifier util_format_description @1509-1509
- function_definition util_format_pack_s_8uint @1514-1521
- enum_specifier pipe_format @1515-1515
- struct_specifier util_format_description @1518-1518
- function_definition util_format_pack_rgba @1528-1540
- enum_specifier pipe_format @1529-1529
- struct_specifier util_format_description @1532-1532
- enum_specifier pipe_format @1547-1547
- enum_specifier pipe_format @1553-1553
- enum_specifier pipe_format @1559-1559
- enum_specifier pipe_format @1565-1565
- enum_specifier pipe_format @1571-1571
- enum_specifier pipe_format @1577-1577
- enum_specifier pipe_format @1583-1583
- enum_specifier pipe_format @1589-1589
- struct_specifier util_format_description @1599-1599
- enum_specifier pipe_format @1602-1602
- enum_specifier pipe_format @1605-1605
- enum_specifier pipe_format @1611-1611
- enum_specifier pipe_format @1616-1616
- enum_specifier pipe_format @1651-1651
- enum_specifier pipe_format @1652-1652
- enum_specifier pipe_format @1656-1656

### third_party/rust/glslopt/glsl-optimizer/src/util/futex.h

Blob: `4d712e2ef2dea91fee9de9b9a125f8e21f2ea38c`. Grammar: cpp. Status: syntax-clean.

- include <limits.h> @30
- include <stdint.h> @31
- include <unistd.h> @32
- include <linux/futex.h> @33
- include <sys/syscall.h> @34
- include <sys/time.h> @35
- function_definition sys_futex @37-40
- struct_specifier timespec @37-37
- function_definition futex_wake @42-45
- function_definition futex_wait @47-53
- struct_specifier timespec @47-47
- include <assert.h> @58
- include <errno.h> @59
- include <fcntl.h> @60
- include <sys/types.h> @61
- include <sys/umtx.h> @62
- include <sys/time.h> @63
- function_definition futex_wake @65-69
- function_definition futex_wait @71-88
- struct_specifier timespec @71-71
- struct_specifier _umtx_time @74-74
- include <sys/time.h> @93
- include <sys/futex.h> @94
- function_definition futex_wake @96-99
- function_definition futex_wait @101-107
- struct_specifier timespec @101-101
- struct_specifier timespec @103-103

### third_party/rust/glslopt/glsl-optimizer/src/util/half_float.c

Blob: `aae690a56a6fad2e03636517397305f9713af537`. Grammar: c. Status: contains-errors.

- include <math.h> @28
- include <assert.h> @29
- include "half_float.h" @30
- include "util/u_half.h" @31
- include "rounding.h" @32
- include "softfloat.h" @33
- include "macros.h" @34
- function_definition _mesa_float_to_half @56-129
- function_definition _mesa_float_to_float16_rtz @131-135
- function_definition _mesa_half_to_float @142-146
- function_definition _mesa_half_to_unorm8 @152-172
- function_definition _mesa_uint16_div_64k_to_half @178-213

### third_party/rust/glslopt/glsl-optimizer/src/util/half_float.h

Blob: `27ffaf6ca330fb4ce4c9a32cfddfc26d394f556e`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @29
- include <stdint.h> @30
- function_definition _mesa_float_to_float16_rtne @52-56
- function_definition _mesa_half_is_negative @58-62
- struct_specifier float16_t @71-78
- function_definition float16_t @73-73
- function_definition float16_t @74-74
- function_definition float16_t @75-75
- function_definition one @76-76
- function_definition zero @77-77

### third_party/rust/glslopt/glsl-optimizer/src/util/hash_table.c

Blob: `0b0077cc7f3e6efddeac9db48d86419569fac2c5`. Grammar: c. Status: contains-errors.

- include <stdlib.h> @43
- include <string.h> @44
- include <assert.h> @45
- include "hash_table.h" @47
- include "ralloc.h" @48
- include "macros.h" @49
- include "u_memory.h" @50
- include "fast_urem_by_const.h" @51
- include "util/u_memory.h" @52
- include "xxhash.h" @55
- function_definition uint_key @70-74
- struct_specifier hash_sizes @83-86
- function_definition key_pointer_is_reserved @124-128
- struct_specifier hash_table @125-125
- function_definition entry_is_free @130-134
- struct_specifier hash_entry @131-131
- function_definition entry_is_deleted @136-140
- struct_specifier hash_table @137-137
- struct_specifier hash_entry @137-137
- function_definition entry_is_present @142-146
- struct_specifier hash_table @143-143
- struct_specifier hash_entry @143-143
- function_definition _mesa_hash_table_init @148-169
- struct_specifier hash_table @149-149
- function_definition _mesa_hash_table_create @171-192
- struct_specifier hash_table @171-171
- struct_specifier hash_table @177-177
- function_definition _mesa_hash_table_clone @194-214
- struct_specifier hash_table @194-194
- struct_specifier hash_table @195-195
- struct_specifier hash_table @197-197
- struct_specifier hash_table @203-203
- struct_specifier hash_entry @211-211
- function_definition _mesa_hash_table_destroy @222-235
- struct_specifier hash_table @223-223
- struct_specifier hash_entry @224-224
- function_definition _mesa_hash_table_clear @243-261
- struct_specifier hash_table @244-244
- struct_specifier hash_entry @245-245
- struct_specifier hash_entry @247-247
- function_definition _mesa_hash_table_set_deleted_key @273-277
- struct_specifier hash_table @274-274
- function_definition hash_table_search @279-307
- struct_specifier hash_entry @279-279
- struct_specifier hash_table @280-280
- struct_specifier hash_entry @291-291
- function_definition _mesa_hash_table_search @315-320
- struct_specifier hash_entry @315-315
- struct_specifier hash_table @316-316
- function_definition _mesa_hash_table_search_pre_hashed @322-328
- struct_specifier hash_entry @322-322
- struct_specifier hash_table @323-323
- struct_specifier hash_entry @330-330
- struct_specifier hash_table @331-331
- function_definition hash_table_insert_rehash @334-357
- struct_specifier hash_table @335-335
- struct_specifier hash_entry @344-344
- function_definition _mesa_hash_table_rehash @359-392
- struct_specifier hash_table @360-360
- struct_specifier hash_table @362-362
- struct_specifier hash_entry @363-363
- function_definition hash_table_insert @394-462
- struct_specifier hash_entry @394-394
- struct_specifier hash_table @395-395
- struct_specifier hash_entry @398-398
- struct_specifier hash_entry @414-414
- function_definition _mesa_hash_table_insert @470-475
- struct_specifier hash_entry @470-470
- struct_specifier hash_table @471-471
- function_definition _mesa_hash_table_insert_pre_hashed @477-483
- struct_specifier hash_entry @477-477
- struct_specifier hash_table @478-478
- function_definition _mesa_hash_table_remove @491-501
- struct_specifier hash_table @492-492
- struct_specifier hash_entry @493-493
- function_definition _mesa_hash_table_remove_key @506-510
- struct_specifier hash_table @506-506
- function_definition _mesa_hash_table_next_entry @518-534
- struct_specifier hash_entry @518-518
- struct_specifier hash_table @519-519
- struct_specifier hash_entry @520-520
- function_definition _mesa_hash_table_random_entry @544-569
- struct_specifier hash_entry @544-544
- struct_specifier hash_table @545-545
- struct_specifier hash_entry @546-546
- struct_specifier hash_entry @548-548
- function_definition _mesa_hash_data @572-576
- function_definition _mesa_hash_int @578-582
- function_definition _mesa_hash_uint @584-588
- function_definition _mesa_hash_u32 @590-594
- function_definition _mesa_hash_string @597-609
- function_definition _mesa_hash_pointer @611-616
- function_definition _mesa_key_int_equal @618-622
- function_definition _mesa_key_uint_equal @624-629
- function_definition _mesa_key_u32_equal @631-635
- function_definition _mesa_key_string_equal @641-645
- function_definition _mesa_key_pointer_equal @647-651
- function_definition _mesa_pointer_hash_table_create @656-661
- struct_specifier hash_table @656-656
- struct_specifier hash_key_u64 @669-671
- function_definition key_u64_hash @673-677
- struct_specifier hash_key_u64 @676-676
- function_definition key_u64_equals @679-686
- struct_specifier hash_key_u64 @682-682
- struct_specifier hash_key_u64 @683-683
- function_definition _mesa_hash_table_u64_create @690-712
- struct_specifier hash_table_u64 @690-690
- struct_specifier hash_table_u64 @694-694
- function_definition _mesa_hash_table_u64_clear @714-762
- struct_specifier hash_table_u64 @715-715
- struct_specifier hash_entry @716-716
- struct_specifier hash_table @723-723
- struct_specifier hash_entry @724-724
- struct_specifier hash_key_u64 @730-730
- struct_specifier hash_table @743-743
- struct_specifier hash_entry @744-744
- struct_specifier hash_key_u64 @750-750
- function_definition _mesa_hash_table_u64_destroy @764-774
- struct_specifier hash_table_u64 @765-765
- struct_specifier hash_entry @766-766
- function_definition _mesa_hash_table_u64_insert @776-801
- struct_specifier hash_table_u64 @777-777
- struct_specifier hash_key_u64 @793-793
- function_definition hash_table_u64_search @803-812
- struct_specifier hash_entry @803-803
- struct_specifier hash_table_u64 @804-804
- struct_specifier hash_key_u64 @809-809
- function_definition _mesa_hash_table_u64_search @814-830
- struct_specifier hash_table_u64 @815-815
- struct_specifier hash_entry @817-817
- function_definition _mesa_hash_table_u64_remove @832-859
- struct_specifier hash_table_u64 @833-833
- struct_specifier hash_entry @835-835
- struct_specifier hash_key @854-854
- struct_specifier hash_key @854-854

### third_party/rust/glslopt/glsl-optimizer/src/util/hash_table.h

Blob: `b1eb9d4e217d743d850e0eb3c6fb5f2f0f23f426`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @31
- include <inttypes.h> @32
- include <stdbool.h> @33
- include "c99_compat.h" @34
- include "fnv1a.h" @35
- include "macros.h" @36
- struct_specifier hash_entry @42-46
- struct_specifier hash_table @48-61
- struct_specifier hash_entry @49-49
- struct_specifier hash_table @63-63
- struct_specifier hash_table @70-70
- struct_specifier hash_table @76-76
- struct_specifier hash_table @77-77
- struct_specifier hash_table @78-78
- struct_specifier hash_entry @79-79
- struct_specifier hash_table @80-80
- struct_specifier hash_entry @81-81
- struct_specifier hash_table @82-82
- function_definition _mesa_hash_table_num_entries @85-88
- struct_specifier hash_table @85-85
- struct_specifier hash_entry @90-90
- struct_specifier hash_table @91-91
- struct_specifier hash_entry @92-92
- struct_specifier hash_table @93-93
- struct_specifier hash_entry @95-95
- struct_specifier hash_table @96-96
- struct_specifier hash_entry @97-97
- struct_specifier hash_table @98-98
- struct_specifier hash_table @100-100
- struct_specifier hash_entry @101-101
- struct_specifier hash_table @102-102
- struct_specifier hash_entry @105-105
- struct_specifier hash_table @105-105
- struct_specifier hash_entry @106-106
- struct_specifier hash_entry @107-107
- struct_specifier hash_table @108-108
- struct_specifier hash_entry @109-109
- struct_specifier hash_table @125-125
- function_definition hash_table_call_foreach @138-147
- struct_specifier hash_table @139-139
- struct_specifier hash_table_u64 @152-156
- struct_specifier hash_table @153-153
- struct_specifier hash_table_u64 @158-158
- struct_specifier hash_table_u64 @162-162
- struct_specifier hash_entry @163-163
- struct_specifier hash_table_u64 @166-166
- struct_specifier hash_table_u64 @170-170
- struct_specifier hash_table_u64 @173-173
- struct_specifier hash_table_u64 @176-176
- struct_specifier hash_entry @177-177

### third_party/rust/glslopt/glsl-optimizer/src/util/list.h

Blob: `8a18c4b0d8d8b99f500359082a5d1906b2d1a95b`. Grammar: cpp. Status: syntax-clean.

- include <stdbool.h> @41
- include <stddef.h> @42
- include <assert.h> @43
- include "c99_compat.h" @44
- struct_specifier list_head @52-56
- struct_specifier list_head @54-54
- struct_specifier list_head @55-55
- function_definition list_inithead @58-62
- struct_specifier list_head @58-58
- function_definition list_add @64-70
- struct_specifier list_head @64-64
- struct_specifier list_head @64-64
- function_definition list_addtail @72-78
- struct_specifier list_head @72-72
- struct_specifier list_head @72-72
- struct_specifier list_head @80-80
- function_definition list_replace @82-92
- struct_specifier list_head @82-82
- struct_specifier list_head @82-82
- function_definition list_del @94-99
- struct_specifier list_head @94-94
- function_definition list_delinit @101-107
- struct_specifier list_head @101-101
- function_definition list_is_empty @109-112
- struct_specifier list_head @109-109
- function_definition list_is_singular @117-120
- struct_specifier list_head @117-117
- function_definition list_length @122-129
- struct_specifier list_head @122-122
- struct_specifier list_head @124-124
- function_definition list_splice @131-140
- struct_specifier list_head @131-131
- struct_specifier list_head @131-131
- function_definition list_splicetail @142-151
- struct_specifier list_head @142-142
- struct_specifier list_head @142-142
- function_definition list_validate @153-159
- struct_specifier list_head @153-153
- struct_specifier list_head @155-155

### third_party/rust/glslopt/glsl-optimizer/src/util/macros.h

Blob: `e4dfd67c8cc26ace3b749067d3479147018ad3e4`. Grammar: cpp. Status: contains-errors.

- include <assert.h> @27
- include "c99_compat.h" @29
- include "c11_compat.h" @30
- enum_specifier pipe_debug_type @350-359

### third_party/rust/glslopt/glsl-optimizer/src/util/mesa-sha1.c

Blob: `fa9284627b19e11e185c65b4b5b843bc80b9927d`. Grammar: c. Status: syntax-clean.

- include "sha1/sha1.h" @27
- include "mesa-sha1.h" @28
- function_definition _mesa_sha1_compute @30-38
- struct_specifier mesa_sha1 @33-33
- function_definition _mesa_sha1_format @40-51

### third_party/rust/glslopt/glsl-optimizer/src/util/mesa-sha1.h

Blob: `bde50ba1eb4f5c97528d13314318178a5282d620`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @26
- include "c99_compat.h" @27
- include "sha1/sha1.h" @28
- function_definition _mesa_sha1_init @36-40
- struct_specifier mesa_sha1 @37-37
- function_definition _mesa_sha1_update @42-46
- struct_specifier mesa_sha1 @43-43
- function_definition _mesa_sha1_final @48-52
- struct_specifier mesa_sha1 @49-49

### third_party/rust/glslopt/glsl-optimizer/src/util/mesa-sha1_test.c

Blob: `9b3b477c7f291e1857457deb5ee4b034b7eb8cc5`. Grammar: c. Status: syntax-clean.

- include <stdio.h> @24
- include <stdbool.h> @25
- include <string.h> @26
- include "macros.h" @28
- include "mesa-sha1.h" @29
- function_definition main @33-65
- struct_specifier test_data @35-38

### third_party/rust/glslopt/glsl-optimizer/src/util/os_memory.h

Blob: `b191cf205840803cf20f4ed5eccb4feb9ab8d925`. Grammar: cpp. Status: contains-errors.

- include "os_memory_stdc.h" @70

### third_party/rust/glslopt/glsl-optimizer/src/util/os_memory_aligned.h

Blob: `08f12062a7fc4816deddd627d535d5a1dc93da6a`. Grammar: cpp. Status: syntax-clean.

- function_definition add_overflow_size_t @43-48
- function_definition os_malloc_aligned @53-61
- function_definition os_malloc_aligned @70-96
- function_definition os_free_aligned @102-110
- function_definition os_realloc_aligned @117-128

### third_party/rust/glslopt/glsl-optimizer/src/util/os_memory_stdc.h

Blob: `bda5715998fbe347aa647166e91acfbd040b8639`. Grammar: cpp. Status: syntax-clean.

- include <stdlib.h> @38
- include <malloc.h> @50
- include "os_memory_aligned.h" @58

### third_party/rust/glslopt/glsl-optimizer/src/util/os_misc.c

Blob: `e6894731b635b754e028b4ac49b2da8769607a0c`. Grammar: c. Status: syntax-clean.

- include "os_misc.h" @29
- include <stdarg.h> @31
- include <windows.h> @39
- include <stdio.h> @40
- include <stdlib.h> @41
- include <stdio.h> @45
- include <stdlib.h> @46
- include <unistd.h> @53
- include <log/log.h> @54
- include <unistd.h> @56
- include <sys/sysctl.h> @58
- include <kernel/OS.h> @60
- include <windows.h> @62
- function_definition os_log_message @68-115
- function_definition os_get_option @119-123
- function_definition os_get_total_physical_memory @132-184

### third_party/rust/glslopt/glsl-optimizer/src/util/os_misc.h

Blob: `19c8962d5d8fb3516df5dc1caca889fb6bb46935`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @37
- include <stdbool.h> @38
- include "detect_os.h" @40
- include <signal.h> @44
- include <unistd.h> @45

### third_party/rust/glslopt/glsl-optimizer/src/util/os_time.h

Blob: `049ab118db27cd2a6ea1feab4b1f977b23bc277b`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @38
- include <stdint.h> @39
- function_definition os_time_get @58-62
- function_definition os_time_timeout @77-86

### third_party/rust/glslopt/glsl-optimizer/src/util/ralloc.c

Blob: `7b7b0185584969dbb29df61ea22777bf2f585ccc`. Grammar: c. Status: contains-errors.

- include <assert.h> @24
- include <stdlib.h> @25
- include <stdarg.h> @26
- include <stdio.h> @27
- include <string.h> @28
- include <stdint.h> @29
- include "ralloc.h" @37
- function_definition (anonymous) @62-83
- struct_specifier ralloc_header @73-73
- struct_specifier ralloc_header @76-76
- struct_specifier ralloc_header @79-79
- struct_specifier ralloc_header @80-80
- struct_specifier ralloc_header @85-85
- function_definition get_header @90-97
- function_definition add_child @101-112
- function_definition ralloc_context @114-118
- function_definition ralloc_size @120-150
- function_definition rzalloc_size @152-161
- function_definition resize @164-192
- function_definition reralloc_size @194-202
- function_definition rerzalloc_size @204-217
- function_definition ralloc_array_size @219-226
- function_definition rzalloc_array_size @228-235
- function_definition reralloc_array_size @237-244
- function_definition rerzalloc_array_size @246-254
- function_definition ralloc_free @256-267
- function_definition unlink_block @269-286
- function_definition unsafe_free @288-304
- function_definition ralloc_steal @306-320
- function_definition ralloc_adopt @322-349
- function_definition ralloc_parent @351-361
- function_definition ralloc_set_destructor @363-368
- function_definition ralloc_strdup @370-384
- function_definition ralloc_strndup @386-400
- function_definition cat @403-420
- function_definition ralloc_strcat @423-427
- function_definition ralloc_strncat @429-433
- function_definition ralloc_str_append @435-452
- function_definition ralloc_asprintf @454-463
- function_definition printf_length @465-489
- function_definition ralloc_vasprintf @491-501
- function_definition ralloc_asprintf_append @503-512
- function_definition ralloc_vasprintf_append @514-521
- function_definition ralloc_asprintf_rewrite_tail @523-532
- function_definition ralloc_vasprintf_rewrite_tail @534-560
- function_definition (anonymous) @588-614
- struct_specifier linear_header @599-599
- struct_specifier linear_header @600-600
- struct_specifier linear_size_chunk @616-619
- struct_specifier linear_header @621-621
- struct_specifier linear_size_chunk @622-622
- function_definition create_linear_node @629-652
- function_definition linear_alloc_child @654-687
- function_definition linear_alloc_parent @689-706
- function_definition linear_zalloc_child @708-716
- function_definition linear_zalloc_parent @718-726
- function_definition linear_free_parent @728-745
- function_definition ralloc_steal_linear_parent @747-763
- function_definition ralloc_parent_of_linear_parent @765-771
- function_definition linear_realloc @773-790
- function_definition linear_strdup @796-813
- function_definition linear_asprintf @815-824
- function_definition linear_vasprintf @826-836
- function_definition linear_asprintf_append @838-847
- function_definition linear_vasprintf_append @849-856
- function_definition linear_asprintf_rewrite_tail @858-868
- function_definition linear_vasprintf_rewrite_tail @870-895
- function_definition linear_cat @898-915
- function_definition linear_strcat @917-921

### third_party/rust/glslopt/glsl-optimizer/src/util/ralloc.h

Blob: `e84ba0f8c617e7617036859eb2e0b895679e2067`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @49
- include <stdarg.h> @50
- include <stdbool.h> @51
- include "macros.h" @53

### third_party/rust/glslopt/glsl-optimizer/src/util/rounding.h

Blob: `f897ec7969d02667e0979b4986e64cda0a80cd36`. Grammar: cpp. Status: syntax-clean.

- include <limits.h> @27
- include <math.h> @28
- include <stdint.h> @29
- include <xmmintrin.h> @32
- include <emmintrin.h> @33
- include <smmintrin.h> @37
- function_definition _mesa_roundevenf @59-71
- function_definition _mesa_roundeven @76-88
- function_definition _mesa_lroundevenf @94-108
- function_definition _mesa_lroundeven @115-129
- function_definition _mesa_i64roundevenf @135-145

### third_party/rust/glslopt/glsl-optimizer/src/util/set.c

Blob: `ffe0fe808eadd8d24ec45d16b423b01b66159fdc`. Grammar: c. Status: contains-errors.

- include <stdlib.h> @35
- include <assert.h> @36
- include <string.h> @37
- include "hash_table.h" @39
- include "macros.h" @40
- include "ralloc.h" @41
- include "set.h" @42
- include "fast_urem_by_const.h" @43
- struct_specifier hash_sizes @54-57
- function_definition key_pointer_is_reserved @95-99
- function_definition entry_is_free @101-105
- struct_specifier set_entry @102-102
- function_definition entry_is_deleted @107-111
- struct_specifier set_entry @108-108
- function_definition entry_is_present @113-117
- struct_specifier set_entry @114-114
- function_definition _mesa_set_create @119-149
- struct_specifier set @119-119
- struct_specifier set @125-125
- function_definition _mesa_set_clone @151-171
- struct_specifier set @151-151
- struct_specifier set @152-152
- struct_specifier set @154-154
- struct_specifier set @160-160
- struct_specifier set_entry @168-168
- function_definition _mesa_set_destroy @179-192
- struct_specifier set @180-180
- struct_specifier set_entry @180-180
- function_definition _mesa_set_clear @200-213
- struct_specifier set @201-201
- struct_specifier set_entry @201-201
- function_definition set_search @220-247
- struct_specifier set_entry @220-220
- struct_specifier set @221-221
- struct_specifier set_entry @231-231
- function_definition _mesa_set_search @249-254
- struct_specifier set_entry @249-249
- struct_specifier set @250-250
- function_definition _mesa_set_search_pre_hashed @256-263
- struct_specifier set_entry @256-256
- struct_specifier set @257-257
- function_definition set_add_rehash @265-285
- struct_specifier set @266-266
- struct_specifier set_entry @274-274
- function_definition set_rehash @287-320
- struct_specifier set @288-288
- struct_specifier set @290-290
- struct_specifier set_entry @291-291
- function_definition _mesa_set_resize @322-334
- struct_specifier set @323-323
- function_definition set_search_or_add @343-401
- struct_specifier set_entry @343-343
- struct_specifier set @344-344
- struct_specifier set_entry @346-346
- struct_specifier set_entry @362-362
- function_definition set_add @409-428
- struct_specifier set_entry @409-409
- struct_specifier set @410-410
- struct_specifier set_entry @412-412
- function_definition _mesa_set_add @430-435
- struct_specifier set_entry @430-430
- struct_specifier set @431-431
- function_definition _mesa_set_add_pre_hashed @437-443
- struct_specifier set_entry @437-437
- struct_specifier set @438-438
- function_definition _mesa_set_search_and_add @445-452
- struct_specifier set_entry @445-445
- struct_specifier set @446-446
- function_definition _mesa_set_search_and_add_pre_hashed @454-470
- struct_specifier set_entry @454-454
- struct_specifier set @455-455
- struct_specifier set_entry @460-460
- function_definition _mesa_set_search_or_add @472-477
- struct_specifier set_entry @472-472
- struct_specifier set @473-473
- function_definition _mesa_set_search_or_add_pre_hashed @479-486
- struct_specifier set_entry @479-479
- struct_specifier set @480-480
- function_definition _mesa_set_remove @494-503
- struct_specifier set @495-495
- struct_specifier set_entry @495-495
- function_definition _mesa_set_remove_key @508-512
- struct_specifier set @509-509
- function_definition _mesa_set_next_entry @520-535
- struct_specifier set_entry @520-520
- struct_specifier set @521-521
- struct_specifier set_entry @521-521
- function_definition _mesa_set_random_entry @537-562
- struct_specifier set_entry @537-537
- struct_specifier set @538-538
- struct_specifier set_entry @539-539
- struct_specifier set_entry @541-541
- function_definition _mesa_pointer_set_create @567-572
- struct_specifier set @567-567

### third_party/rust/glslopt/glsl-optimizer/src/util/set.h

Blob: `55857aca7ab4a4f9ac899eb4114af12ae2bef7e8`. Grammar: cpp. Status: contains-errors.

- include <inttypes.h> @31
- include <stdbool.h> @32
- struct_specifier set_entry @38-41
- struct_specifier set @43-56
- struct_specifier set_entry @45-45
- struct_specifier set @58-58
- struct_specifier set @63-63
- struct_specifier set @64-64
- struct_specifier set @67-67
- struct_specifier set_entry @68-68
- struct_specifier set @70-70
- struct_specifier set @72-72
- struct_specifier set_entry @73-73
- struct_specifier set_entry @75-75
- struct_specifier set @76-76
- struct_specifier set_entry @77-77
- struct_specifier set @78-78
- struct_specifier set_entry @80-80
- struct_specifier set @81-81
- struct_specifier set_entry @82-82
- struct_specifier set @83-83
- struct_specifier set_entry @86-86
- struct_specifier set @87-87
- struct_specifier set_entry @88-88
- struct_specifier set @89-89
- struct_specifier set_entry @92-92
- struct_specifier set @93-93
- struct_specifier set_entry @94-94
- struct_specifier set @95-95
- struct_specifier set @99-99
- struct_specifier set_entry @99-99
- struct_specifier set @101-101
- struct_specifier set_entry @103-103
- struct_specifier set @104-104
- struct_specifier set_entry @104-104
- struct_specifier set_entry @106-106
- struct_specifier set @107-107
- struct_specifier set_entry @108-108
- struct_specifier set @110-110

### third_party/rust/glslopt/glsl-optimizer/src/util/sha1/sha1.c

Blob: `4fe2aa723c5846d9edf96221dc52160a7b841a00`. Grammar: c. Status: syntax-clean.

- include <stdint.h> @17
- include <string.h> @18
- include "u_endian.h" @19
- include "sha1.h" @20
- function_definition SHA1Transform @54-101
- function_definition SHA1Init @107-118
- function_definition SHA1Update @124-141
- function_definition SHA1Pad @147-161
- function_definition SHA1Final @163-174

### third_party/rust/glslopt/glsl-optimizer/src/util/sha1/sha1.h

Blob: `029a0ae87f1b4c02abf60bef93b85681694b4aec`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @12
- include <stdint.h> @13
- struct_specifier _SHA1_CTX @23-27

### third_party/rust/glslopt/glsl-optimizer/src/util/simple_mtx.h

Blob: `e332816b98981e7ed4adf541d056a25be2c1d59b`. Grammar: cpp. Status: contains-errors.

- include "util/futex.h" @27
- include "util/macros.h" @28
- include "c11/threads.h" @30
- struct_specifier simple_mtx_t @58-60
- function_definition simple_mtx_init @66-72
- function_definition simple_mtx_destroy @74-80
- function_definition simple_mtx_lock @82-99
- function_definition simple_mtx_unlock @101-114
- function_definition simple_mtx_init @122-126
- function_definition simple_mtx_destroy @128-132
- function_definition simple_mtx_lock @134-138
- function_definition simple_mtx_unlock @140-144

### third_party/rust/glslopt/glsl-optimizer/src/util/softfloat.c

Blob: `591128efd474e9e0bb114e56428c5a3988f6b2ce`. Grammar: c. Status: syntax-clean.

- include "rounding.h" @46
- include "bitscan.h" @47
- include "softfloat.h" @48
- function_definition _mesa_short_shift_right_jam64 @100-104
- function_definition _mesa_shift_right_jam64 @117-122
- function_definition _mesa_shift_right_jam32 @135-140
- function_definition _mesa_roundtozero_f64 @145-169
- function_definition _mesa_round_f32 @174-202
- function_definition _mesa_roundtozero_f16 @207-226
- function_definition _mesa_short_shift_left_m @239-257
- function_definition _mesa_shift_left_m @271-304
- function_definition _mesa_short_shift_right_m @317-335
- function_definition _mesa_short_shift_right_jam_m @350-371
- function_definition _mesa_shift_right_jam_m @388-437
- function_definition _mesa_double_add_rtz @449-531
- function_definition _mesa_count_leading_zeros64 @537-541
- function_definition _mesa_count_leading_zeros32 @547-551
- function_definition _mesa_norm_round_pack_f64 @553-567
- function_definition _mesa_neg_x_m @577-596
- function_definition _mesa_add_m @608-628
- function_definition _mesa_sub_m @640-659
- function_definition _mesa_double_sub_rtz @670-762
- function_definition _mesa_norm_subnormal_mantissa_f64 @764-772
- function_definition _mesa_norm_subnormal_mantissa_f32 @774-782
- function_definition _mesa_softfloat_mul_f64_to_f128_m @792-814
- function_definition _mesa_double_mul_rtz @825-918
- function_definition _mesa_double_fma_rtz @931-1183
- function_definition _mesa_float_fma_rtz @1196-1374
- function_definition _mesa_double_to_f32 @1383-1429
- function_definition _mesa_float_to_half_rtz @1437-1475

### third_party/rust/glslopt/glsl-optimizer/src/util/softfloat.h

Blob: `4e48c6548b9232245f366d4ccd2847a4c01703b0`. Grammar: cpp. Status: contains-errors.

- include <stdbool.h> @46
- include <stdint.h> @47

### third_party/rust/glslopt/glsl-optimizer/src/util/string_buffer.c

Blob: `31ebe3cb7e04d4761f467aac6926a489b51b0772`. Grammar: c. Status: contains-errors.

- include "string_buffer.h" @25
- function_definition ensure_capacity @27-44
- struct_specifier _mesa_string_buffer @28-28
- function_definition _mesa_string_buffer_create @46-67
- struct_specifier _mesa_string_buffer @46-46
- struct_specifier _mesa_string_buffer @49-49
- function_definition _mesa_string_buffer_append_all @69-86
- struct_specifier _mesa_string_buffer @70-70
- function_definition _mesa_string_buffer_append_len @88-105
- struct_specifier _mesa_string_buffer @89-89
- function_definition _mesa_string_buffer_vprintf @107-136
- struct_specifier _mesa_string_buffer @108-108
- function_definition _mesa_string_buffer_printf @138-148
- struct_specifier _mesa_string_buffer @139-139

### third_party/rust/glslopt/glsl-optimizer/src/util/string_buffer.h

Blob: `eaaf5f33dfd2854905b95fc82ad3780dbb869bb2`. Grammar: cpp. Status: contains-errors.

- include "ralloc.h" @27
- include "u_string.h" @28
- include <stdbool.h> @29
- include <stdint.h> @30
- include <stdio.h> @31
- include <string.h> @32
- struct_specifier _mesa_string_buffer @38-42
- struct_specifier _mesa_string_buffer @44-44
- function_definition _mesa_string_buffer_destroy @47-51
- struct_specifier _mesa_string_buffer @48-48
- struct_specifier _mesa_string_buffer @54-54
- struct_specifier _mesa_string_buffer @57-57
- function_definition _mesa_string_buffer_append_char @60-64
- struct_specifier _mesa_string_buffer @61-61
- function_definition _mesa_string_buffer_append @66-70
- struct_specifier _mesa_string_buffer @67-67
- function_definition _mesa_string_buffer_clear @72-77
- struct_specifier _mesa_string_buffer @73-73
- function_definition _mesa_string_buffer_crimp_to_fit @79-90
- struct_specifier _mesa_string_buffer @80-80
- struct_specifier _mesa_string_buffer @93-93
- struct_specifier _mesa_string_buffer @97-97

### third_party/rust/glslopt/glsl-optimizer/src/util/strndup.h

Blob: `dcaa429dbe81b1b0fdb6d537972d93f41e73695e`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @29
- include <string.h> @30
- function_definition strndup @36-52

### third_party/rust/glslopt/glsl-optimizer/src/util/strtod.c

Blob: `de695d64b4742400eb00bff16608119b547781f5`. Grammar: c. Status: syntax-clean.

- include <stdlib.h> @27
- include <locale.h> @30
- include <xlocale.h> @32
- include "strtod.h" @37
- function_definition _mesa_locale_init @40-46
- function_definition _mesa_locale_fini @48-54
- function_definition _mesa_strtod @60-68
- function_definition _mesa_strtof @75-85

### third_party/rust/glslopt/glsl-optimizer/src/util/strtod.h

Blob: `60e15cfa0ebc1eb4453a7d63f77e9d5257ee44a3`. Grammar: cpp. Status: contains-errors.


### third_party/rust/glslopt/glsl-optimizer/src/util/u_atomic.h

Blob: `db56835e9d4f9ba6ed219770849ed1375e624b83`. Grammar: cpp. Status: syntax-clean.

- include "no_extern_c.h" @9
- include <stdbool.h> @14
- include <stdint.h> @15
- include <windows.h> @114
- include <intrin.h> @115
- include <assert.h> @116
- include <atomic.h> @171
- include <assert.h> @172
- function_definition p_atomic_xchg_32 @240-249
- function_definition p_atomic_xchg_64 @251-260

### third_party/rust/glslopt/glsl-optimizer/src/util/u_debug.c

Blob: `e1c8265965fd3d9e9f470e947a781fea1cb9b009`. Grammar: c. Status: contains-errors.

- include "pipe/p_config.h" @30
- include "util/u_debug.h" @32
- include "pipe/p_format.h" @33
- include "pipe/p_state.h" @34
- include "util/u_string.h" @35
- include "util/u_math.h" @36
- include <inttypes.h> @37
- include <stdio.h> @39
- include <limits.h> @40
- include <ctype.h> @41
- include <windows.h> @44
- include <stdlib.h> @45
- function_definition _debug_vprintf @49-65
- function_definition _pipe_debug_message @68-79
- struct_specifier pipe_debug_callback @69-69
- enum_specifier pipe_debug_type @71-71
- function_definition debug_disable_error_message_boxes @82-105
- function_definition debug_print_blob @109-121
- function_definition debug_get_option_should_print @125-141
- function_definition debug_get_option @144-158
- function_definition debug_get_bool_option @161-191
- function_definition debug_get_num_option @194-217
- function_definition str_has_option @220-262
- function_definition debug_get_flags_option @265-307
- struct_specifier debug_named_value @267-267
- struct_specifier debug_named_value @272-272
- function_definition _debug_assert_fail @310-317
- function_definition debug_dump_enum @320-334
- struct_specifier debug_named_value @321-321
- function_definition debug_dump_enum_noprefix @337-358
- struct_specifier debug_named_value @338-338
- function_definition debug_dump_flags @361-398
- struct_specifier debug_named_value @362-362
- function_definition debug_funclog_enter @406-420
- function_definition debug_funclog_exit @422-429
- function_definition debug_funclog_enter_exit @431-439

### third_party/rust/glslopt/glsl-optimizer/src/util/u_debug.h

Blob: `a9e44bf24e2073a15fb282eaa27454ed19acfcae`. Grammar: cpp. Status: contains-errors.

- include <stdarg.h> @41
- include <string.h> @42
- include "util/os_misc.h" @43
- include "util/detect_os.h" @44
- include "util/macros.h" @45
- include <OS.h> @49
- function_definition _debug_printf @66-73
- function_definition debug_printf @89-100
- struct_specifier pipe_debug_callback @274-274
- struct_specifier pipe_debug_callback @278-278
- enum_specifier pipe_debug_type @280-280
- struct_specifier debug_named_value @287-292
- struct_specifier debug_named_value @323-323
- struct_specifier debug_named_value @327-327
- struct_specifier debug_named_value @336-336
- struct_specifier debug_named_value @400-400

### third_party/rust/glslopt/glsl-optimizer/src/util/u_dynarray.h

Blob: `000feaa834939e9baa958dc4240d2d67c28f4fcd`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @30
- include <string.h> @31
- include <limits.h> @32
- include "ralloc.h" @33
- struct_specifier util_dynarray @45-51
- function_definition util_dynarray_init @53-58
- struct_specifier util_dynarray @54-54
- function_definition util_dynarray_fini @60-71
- struct_specifier util_dynarray @61-61
- function_definition util_dynarray_clear @73-77
- struct_specifier util_dynarray @74-74
- function_definition util_dynarray_ensure_cap @81-101
- struct_specifier util_dynarray @82-82
- function_definition util_dynarray_resize_bytes @104-118
- struct_specifier util_dynarray @105-105
- function_definition util_dynarray_clone @120-127
- struct_specifier util_dynarray @121-121
- struct_specifier util_dynarray @122-122
- function_definition util_dynarray_grow_bytes @129-146
- struct_specifier util_dynarray @130-130
- function_definition util_dynarray_trim @148-169
- struct_specifier util_dynarray @149-149

### third_party/rust/glslopt/glsl-optimizer/src/util/u_endian.h

Blob: `6bbae3c444c322b7f16fbb6eef2c586f86aecb0c`. Grammar: cpp. Status: syntax-clean.

- include <endian.h> @31
- include <machine/endian.h> @42
- include <sys/isa_defs.h> @53
- include <sys/types.h> @65
- include <machine/endian.h> @66

### third_party/rust/glslopt/glsl-optimizer/src/util/u_math.c

Blob: `9a8a9ecbbdeeb824f859cd0e686ce9a1608d93c4`. Grammar: c. Status: syntax-clean.

- include "pipe/p_config.h" @30
- include "util/u_math.h" @31
- include "util/u_cpu_detect.h" @32
- include <xmmintrin.h> @35
- function_definition init_pow2_table @48-54
- function_definition init_log2_table @61-67
- function_definition util_init_math @73-82
- function_definition util_fpstate_get @89-101
- function_definition util_fpstate_set_denorms_to_zero @109-124
- function_definition util_fpstate_set @131-139

### third_party/rust/glslopt/glsl-optimizer/src/util/u_math.h

Blob: `42d9e348ec85ab3c3766d5ff1163c5410928dd25`. Grammar: cpp. Status: contains-errors.

- include <assert.h> @41
- include <float.h> @42
- include <math.h> @43
- include <stdarg.h> @44
- include "bitscan.h" @46
- include "u_endian.h" @47
- function_definition util_get_float32_exponent @90-98
- function_definition util_fast_exp2 @110-135
- function_definition util_fast_exp @141-146
- function_definition util_fast_log2 @158-168
- function_definition util_fast_pow @174-178
- function_definition util_ifloor @184-213
- function_definition util_iround @219-239
- function_definition util_is_approx @245-249
- function_definition util_is_inf_or_nan @264-270
- function_definition util_is_nan @273-279
- function_definition util_inf_sign @282-292
- function_definition util_is_double_inf_or_nan @298-304
- function_definition util_is_double_nan @307-313
- function_definition util_double_inf_sign @316-326
- function_definition util_is_half_inf_or_nan @332-336
- function_definition util_is_half_nan @339-343
- function_definition util_half_inf_sign @346-354
- function_definition fui @360-366
- function_definition uif @368-374
- function_definition ubyte_to_float @380-384
- function_definition float_to_ubyte @390-406
- function_definition ushort_to_float @411-415
- function_definition float_to_ushort @421-437
- function_definition byte_to_float_tex @439-443
- function_definition float_to_byte_tex @445-449
- function_definition util_logbase2 @454-468
- function_definition util_logbase2_64 @470-485
- function_definition util_logbase2_ceil @491-498
- function_definition util_logbase2_ceil64 @500-507
- function_definition util_next_power_of_two @512-538
- function_definition util_next_power_of_two64 @540-567
- function_definition util_bitreverse @574-583
- function_definition util_bswap32 @606-617
- function_definition util_bswap64 @622-631
- function_definition util_bswap16 @637-642
- function_definition util_memcpy_cpu_to_le32 @644-660
- function_definition ALIGN @690-695
- function_definition ALIGN_NPOT @700-705
- function_definition ROUND_DOWN_TO @718-723
- function_definition align @728-732
- function_definition align64 @734-738
- function_definition util_align_npot @743-749
- function_definition u_minify @751-755
- function_definition util_unsigned_fixed @784-788
- function_definition util_signed_fixed @790-794
- function_definition util_is_vbo_upload_ratio_too_large @811-821

### third_party/rust/glslopt/glsl-optimizer/src/util/u_memory.h

Blob: `4cdccb66aaf4b8770b9b7144330fe971ff3f9f72`. Grammar: cpp. Status: contains-errors.

- include "util/u_debug.h" @37
- include "util/os_memory.h" @38
- function_definition align_calloc @65-72
- function_definition mem_dup @77-84

### third_party/rust/glslopt/glsl-optimizer/src/util/u_queue.h

Blob: `5943df4fcbbf00976af01f9bf1ab7851fada32b4`. Grammar: cpp. Status: contains-errors.

- include <string.h> @36
- include "util/futex.h" @38
- include "util/list.h" @39
- include "util/macros.h" @40
- include "util/os_time.h" @41
- include "util/u_atomic.h" @42
- include "util/u_thread.h" @43
- struct_specifier util_queue_fence @63-70
- function_definition util_queue_fence_init @72-76
- struct_specifier util_queue_fence @73-73
- function_definition util_queue_fence_destroy @78-83
- struct_specifier util_queue_fence @79-79
- function_definition util_queue_fence_signal @85-94
- struct_specifier util_queue_fence @86-86
- function_definition util_queue_fence_reset @102-111
- struct_specifier util_queue_fence @103-103
- function_definition util_queue_fence_is_signalled @113-117
- struct_specifier util_queue_fence @114-114
- struct_specifier util_queue_fence @124-128
- struct_specifier util_queue_fence @130-130
- struct_specifier util_queue_fence @131-131
- struct_specifier util_queue_fence @132-132
- function_definition util_queue_fence_reset @140-145
- struct_specifier util_queue_fence @141-141
- function_definition util_queue_fence_is_signalled @147-151
- struct_specifier util_queue_fence @148-148
- struct_specifier util_queue_fence @155-155
- function_definition util_queue_fence_wait @157-162
- struct_specifier util_queue_fence @158-158
- struct_specifier util_queue_fence @165-165
- function_definition util_queue_fence_wait_timeout @177-190
- struct_specifier util_queue_fence @178-178
- struct_specifier util_queue_job @194-200
- struct_specifier util_queue_fence @197-197
- struct_specifier util_queue @203-221
- struct_specifier util_queue_job @217-217
- struct_specifier list_head @220-220
- struct_specifier util_queue @223-223
- struct_specifier util_queue @228-228
- struct_specifier util_queue @231-231
- struct_specifier util_queue_fence @233-233
- struct_specifier util_queue @237-237
- struct_specifier util_queue_fence @238-238
- struct_specifier util_queue @240-240
- struct_specifier util_queue @247-247
- struct_specifier util_queue @249-249
- function_definition util_queue_is_initialized @253-257
- struct_specifier util_queue @254-254
- struct_specifier util_queue_monitoring @262-271
- struct_specifier util_queue @265-265

### third_party/rust/glslopt/glsl-optimizer/src/util/u_string.h

Blob: `88df2cceda66681d02e6b8c2f9752bce7f845080`. Grammar: cpp. Status: contains-errors.

- include <stdio.h> @39
- include <stdlib.h> @41
- include <stddef.h> @42
- include <stdarg.h> @43
- include <string.h> @44
- include "util/macros.h" @46
- function_definition util_strchrnul @56-62
- function_definition util_sprintf @71-77
- function_definition util_vasprintf @80-99
- function_definition util_asprintf @102-111

### third_party/rust/glslopt/glsl-optimizer/src/util/u_thread.h

Blob: `b91d05e4cfd2aefa28cdb8e8aef9d25cdebbaec4`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @30
- include <stdbool.h> @31
- include "c11/threads.h" @33
- include "detect_os.h" @34
- include <signal.h> @37
- include <pthread_np.h> @39
- include <OS.h> @44
- function_definition u_thread_create @55-75
- function_definition u_thread_setname @77-95
- function_definition util_pin_thread_to_L3 @107-118
- function_definition util_get_L3_for_pinned_thread @127-152
- function_definition u_thread_get_time_nano @159-172
- struct_specifier timespec @163-163
- function_definition u_thread_is_self @174-180
- function_definition util_barrier_init @190-193
- function_definition util_barrier_destroy @195-198
- function_definition util_barrier_wait @200-203
- struct_specifier util_barrier @208-214
- function_definition util_barrier_init @216-223
- function_definition util_barrier_destroy @225-230
- function_definition util_barrier_wait @232-252

### third_party/rust/glslopt/glsl-optimizer/src/util/xxhash.h

Blob: `c0c8f44b600b1ae08ac15d4feca50fea5b72f10d`. Grammar: cpp. Status: contains-errors.

- include <stddef.h> @170
- enum_specifier XXH_errorcode @171-171
- include <stdint.h> @180
- include <limits.h> @183
- struct_specifier XXH32_state_s @225-225
- struct_specifier XXH32_canonical_t @251-251
- include <stdint.h> @263
- struct_specifier XXH64_state_s @278-278
- struct_specifier XXH64_canonical_t @288-288
- struct_specifier XXH32_state_s @312-322
- struct_specifier XXH64_state_s @327-337
- include <stdlib.h> @431
- function_definition XXH_malloc @432-432
- function_definition XXH_free @433-433
- include <string.h> @435
- function_definition XXH_memcpy @436-436
- include <limits.h> @438
- include <assert.h> @476
- include <stdint.h> @492
- function_definition XXH_read32 @505-505
- function_definition XXH_read32 @512-512
- function_definition XXH_read32 @519-524
- enum_specifier XXH_endianess @530-530
- function_definition XXH_isLittleEndian @542-546
- function_definition XXH_swap32 @580-586
- enum_specifier XXH_alignment @593-593
- function_definition XXH_readLE32 @595-598
- function_definition XXH_readBE32 @600-603
- function_definition XXH_readLE32_align @605-613
- function_definition XXH_versionNumber @619-619
- function_definition XXH32_round @631-681
- function_definition XXH32_avalanche @684-692
- function_definition XXH32_finalize @696-763
- function_definition XXH32_endian_align @765-801
- function_definition XXH32_hash_t @804-822
- function_definition * XXH32_createState(void) @828-831
- function_definition XXH32_freeState @832-836
- function_definition XXH32_copyState @838-841
- function_definition XXH32_reset @843-854
- function_definition XXH32_update @857-918
- function_definition XXH32_digest @921-937
- function_definition XXH32_canonicalFromHash @948-953
- function_definition XXH32_hashFromCanonical @955-958
- function_definition XXH_read64 @1001-1001
- function_definition XXH_read64 @1008-1008
- function_definition XXH_read64 @1016-1021
- function_definition XXH_swap64 @1030-1040
- function_definition XXH_readLE64 @1043-1046
- function_definition XXH_readBE64 @1048-1051
- function_definition XXH_readLE64_align @1053-1060
- function_definition XXH64_round @1071-1077
- function_definition XXH64_mergeRound @1079-1085
- function_definition XXH64_avalanche @1087-1095
- function_definition XXH64_finalize @1100-1221
- function_definition XXH64_endian_align @1223-1263
- function_definition XXH64_hash_t @1266-1285
- function_definition * XXH64_createState(void) @1289-1292
- function_definition XXH64_freeState @1293-1297
- function_definition XXH64_copyState @1299-1302
- function_definition XXH64_reset @1304-1315
- function_definition XXH64_update @1317-1375
- function_definition XXH64_digest @1378-1400
- function_definition XXH64_canonicalFromHash @1405-1410
- function_definition XXH64_hashFromCanonical @1412-1415

### third_party/rust/glslopt/src/bindings.rs

Blob: `f4e5bebd08babb4c5d9b0ed3139787c27529ee39`. Grammar: rust. Status: syntax-clean.

- struct_item glslopt_shader @5-7
- struct_item glslopt_ctx @10-12
- function_signature_item glslopt_initialize @41-41
- function_signature_item glslopt_cleanup @44-44
- function_signature_item glslopt_set_max_unroll_iterations @47-50
- function_signature_item glslopt_optimize @53-58
- function_signature_item glslopt_get_status @61-61
- function_signature_item glslopt_get_output @64-64
- function_signature_item glslopt_get_raw_output @67-67
- function_signature_item glslopt_get_log @70-70
- function_signature_item glslopt_shader_delete @73-73
- function_signature_item glslopt_shader_get_input_count @76-76
- function_signature_item glslopt_shader_get_input_desc @79-89
- function_signature_item glslopt_shader_get_uniform_count @92-92
- function_signature_item glslopt_shader_get_uniform_total_size @95-97
- function_signature_item glslopt_shader_get_uniform_desc @100-110
- function_signature_item glslopt_shader_get_texture_count @113-113
- function_signature_item glslopt_shader_get_texture_desc @116-126
- function_signature_item glslopt_shader_get_stats @129-134

### third_party/rust/glslopt/src/lib.rs

Blob: `e06ec1a4c6496e58b46a66cc4784975f222ba368`. Grammar: rust. Status: syntax-clean.

- mod_item bindings @7-7
- enum_item ShaderType @9-12
- enum_item Target @14-19
- struct_item Context @21-23
- function_item new @26-39
- function_item optimize @41-53
- function_item drop @57-61
- struct_item Shader @64-66
- function_item get_status @69-71
- function_item get_output @73-82
- function_item get_log @84-93
- function_item drop @97-101

### third_party/rust/glslopt/wrapper.hpp

Blob: `5491b3d8a6e4322ba1e009ad1b3481a7b674cb83`. Grammar: cpp. Status: syntax-clean.

- include "glsl-optimizer/src/compiler/glsl/glsl_optimizer.h" @1

### third_party/rust/goblin/src/archive/mod.rs

Blob: `0ff633c45b653cb45485ae67f6fbd012ef9cc3b7`. Grammar: rust. Status: syntax-clean.

- struct_item MemberHeader @44-59
- struct_item Header @62-65
- function_item name @70-74
- function_item size @75-88
- struct_item Member @93-104
- function_item parse @110-155
- function_item size @159-161
- function_item bsd_filename_length @164-177
- function_item extended_name @180-188
- function_item raw_name @192-194
- struct_item Index @201-208
- function_item parse_sysv_index @220-239
- function_item parse_bsd_symdef @242-315
- function_item parse_windows_linker_member @324-359
- struct_item NameIndex @366-368
- function_item parse @371-379
- function_item get @381-407
- enum_item IndexType @413-423
- struct_item Archive @429-437
- function_item parse @440-536
- function_item get @541-547
- function_item get_at @550-552
- function_item len @555-557
- function_item extract @560-570
- function_item summarize @573-587
- function_item members @595-597
- function_item member_of_symbol @600-606
- mod_item tests @610-637
- function_item test_member_bsd_filename_length @614-636

### third_party/rust/goblin/src/elf/compression_header.rs

Blob: `1dd7aa13626448112941fe85ff7d42ee556740f9`. Grammar: rust. Status: syntax-clean.

- mod_item compression_header32 @88-121
- struct_item CompressionHeader @95-102
- mod_item compression_header64 @123-158
- struct_item CompressionHeader @130-138

### third_party/rust/goblin/src/elf/constants_header.rs

Blob: `9b19c84c2c246723b52317165f32740a903a070b`. Grammar: rust. Status: syntax-clean.

- function_item machine_to_str @382-563

### third_party/rust/goblin/src/elf/constants_relocation.rs

Blob: `0604a7c483935672789a6e6e171a935324779869`. Grammar: rust. Status: syntax-clean.

- function_item r_to_str @909-1417

### third_party/rust/goblin/src/elf/dynamic.rs

Blob: `ab7c407076d87dc211b017cc5e63914801bef2d5`. Grammar: rust. Status: syntax-clean.

- function_item tag_to_str @163-214
- function_item df_tag_to_str @228-237
- function_item df_1_tag_to_str @292-323
- mod_item dyn32 @781-793
- mod_item dyn64 @795-807

### third_party/rust/goblin/src/elf/gnu_hash.rs

Blob: `8b73182f41cb272797de75e96fa7e9def23a43ef`. Grammar: rust. Status: syntax-clean.

- function_item hash @26-31
- mod_item tests @34-44
- function_item test_hash @37-43

### third_party/rust/goblin/src/elf/header.rs

Blob: `2c05e8ffc6fc98f117c427a27c1737bb521b5eea`. Grammar: rust. Status: syntax-clean.

- function_item class_to_str @173-180
- function_item et_to_str @184-194
- mod_item header32 @610-619
- mod_item header64 @621-630

### third_party/rust/goblin/src/elf/mod.rs

Blob: `70c49146ffda7bfa8d498ffaad374a48af66450d`. Grammar: rust. Status: syntax-clean.

- mod_item gnu_hash @41-41
- mod_item compression_header @46-46
- mod_item header @47-47
- mod_item program_header @48-48
- mod_item section_header @49-49
- mod_item sym @51-51
- mod_item dynamic @52-52
- mod_item reloc @54-54
- mod_item note @55-55
- mod_item symver @57-57
- mod_item tests @503-571
- function_item parse_crt1_64bit @507-532
- function_item parse_crt1_32bit @535-560
- function_item no_use_statement_conflict @565-570
- function_item f @569-569

### third_party/rust/goblin/src/elf/note.rs

Blob: `2e2864d25f69833551d376a77fe2fc81ab9a9206`. Grammar: rust. Status: syntax-clean.

- struct_item Nhdr32 @65-72
- struct_item Nhdr64 @82-89

### third_party/rust/goblin/src/elf/program_header.rs

Blob: `80d499ca683bb80ef90555e7e02cfb965f3b5e28`. Grammar: rust. Status: syntax-clean.

- function_item pt_to_str @61-85
- mod_item program_header32 @364-396
- struct_item ProgramHeader @371-388
- mod_item program_header64 @398-430
- struct_item ProgramHeader @405-422

### third_party/rust/goblin/src/elf/reloc.rs

Blob: `0fcf977e55af2b1ac8610ef1b61b39cbcf28fcf4`. Grammar: rust. Status: syntax-clean.

- mod_item reloc32 @219-244
- function_item r_sym @229-231
- function_item r_type @234-236
- function_item r_info @239-241
- mod_item reloc64 @246-270
- function_item r_sym @255-257
- function_item r_type @260-262
- function_item r_info @265-267

### third_party/rust/goblin/src/elf/section_header.rs

Blob: `bc8f6e4d1f64705ed94ac5710890c4375572474b`. Grammar: rust. Status: syntax-clean.

- function_item sht_to_str @208-246
- function_item shf_to_str @248-265
- mod_item section_header32 @347-355
- mod_item section_header64 @357-366

### third_party/rust/goblin/src/elf/sym.rs

Blob: `823ee6846b8eb6ba6f20c28468ebbf80107400ff`. Grammar: rust. Status: syntax-clean.

- function_item st_bind @75-77
- function_item st_type @83-85
- function_item st_visibility @91-93
- function_item is_import @97-100
- function_item get_type @104-106
- function_item bind_to_str @110-119
- function_item type_to_str @123-136
- function_item visibility_to_str @140-151
- mod_item sym32 @270-298
- struct_item Sym @277-290
- mod_item sym64 @300-328
- struct_item Sym @307-320
- struct_item Sym @341-348
- function_item size @352-354
- function_item is_import @357-360
- function_item is_function @363-365
- function_item st_bind @370-372
- function_item st_type @377-379
- function_item st_visibility @384-386
- function_item parse @389-399
- function_item fmt @403-426
- function_item size_with @431-436

### third_party/rust/goblin/src/elf/symver.rs

Blob: `0dd55e3d255cfa9e6a874020488138241fdd54ae`. Grammar: rust. Status: syntax-clean.

- struct_item ElfVersym @101-103
- struct_item ElfVerdef @110-118
- struct_item ElfVerdaux @125-128
- struct_item ElfVerneed @135-141
- struct_item ElfVernaux @148-154
- struct_item VersymSection @162-165
- function_item parse @168-185
- function_item iter @189-191
- function_item is_empty @195-197
- function_item len @201-205
- function_item get_at @209-217
- function_item into_iter @224-230
- struct_item VersymIter @234-238
- function_item next @243-258
- function_item size_hint @261-264
- struct_item Versym @275-277
- function_item is_local @283-285
- function_item is_global @290-292
- function_item is_hidden @296-298
- function_item version @302-304
- function_item from @308-310
- struct_item VerdefSection @320-325
- function_item parse @328-349
- function_item iter @353-355
- function_item into_iter @363-371
- struct_item VerdefIter @375-381
- function_item next @386-441
- function_item size_hint @444-447
- struct_item Verdef @458-476
- function_item iter @481-483
- function_item into_iter @490-498
- struct_item VerdauxIter @502-508
- function_item next @513-543
- function_item size_hint @546-549
- struct_item Verdaux @560-565
- struct_item VerneedSection @574-578
- function_item parse @582-603
- function_item iter @607-609
- function_item into_iter @617-625
- struct_item VerneedIter @629-635
- function_item next @640-691
- function_item size_hint @694-697
- struct_item Verneed @708-723
- function_item iter @728-730
- function_item into_iter @738-746
- struct_item VernauxIter @750-756
- function_item next @761-799
- function_item size_hint @802-805
- struct_item Vernaux @816-829
- mod_item test @832-880
- function_item check_size @838-844
- function_item check_versym @847-879

### third_party/rust/goblin/src/error.rs

Blob: `0ec4e1e0c95a636a2c68348f1f109fe06b5a5150`. Grammar: rust. Status: syntax-clean.

- enum_item Error @14-26
- function_item source @30-36
- function_item from @41-43
- function_item from @47-49
- function_item from @53-55
- function_item fmt @59-68

### third_party/rust/goblin/src/lib.rs

Blob: `e811de1ea5dcb0d9280e2fb6a05294be209395b0`. Grammar: rust. Status: syntax-clean.

- mod_item error @112-112
- mod_item strtab @114-114
- mod_item container @117-206
- enum_item Container @122-125
- function_item is_big @129-131
- function_item default @144-146
- struct_item Ctx @151-154
- function_item is_big @158-160
- function_item is_little_endian @162-164
- function_item new @166-168
- function_item size @170-176
- function_item from @180-185
- function_item from @189-194
- function_item default @199-204
- function_item take_hint_bytes @211-215
- struct_item HintData @219-222
- enum_item Hint @227-236
- mod_item elf @333-333
- mod_item elf32 @337-350
- mod_item gnu_hash @346-349
- mod_item elf64 @354-367
- mod_item gnu_hash @363-366
- mod_item mach @370-370
- mod_item pe @373-373
- mod_item archive @376-376
- mod_item tests @379-396

### third_party/rust/goblin/src/mach/bind_opcodes.rs

Blob: `970ab10af138bc2b5556a776ca604e2b1775b35b`. Grammar: rust. Status: syntax-clean.

- function_item opcode_to_str @41-60

### third_party/rust/goblin/src/mach/constants.rs

Blob: `8ae17851c8c3cece55712ffc7ceb993b9982c328`. Grammar: rust. Status: syntax-clean.

- mod_item cputype @200-458
- function_item get_arch_from_flag @388-400
- mod_item tests @461-483
- function_item test_basic_mapping @463-482

### third_party/rust/goblin/src/mach/exports.rs

Blob: `2ce4f89e0dff1f6077ca86c2de4b077228bba1c2`. Grammar: rust. Status: syntax-clean.

- enum_item SymbolKind @30-35
- function_item new @38-45
- function_item to_str @46-53
- enum_item ExportInfo @58-74
- function_item parse @78-143
- struct_item Export @148-157
- function_item new @161-172
- struct_item ExportTrie @176-179
- function_item walk_nodes @183-193
- function_item walk_branches @196-222
- function_item walk_trie @224-266
- function_item new_impl @268-285
- function_item exports @288-294
- function_item new @297-303
- function_item new_from_linkedit_data_command @306-311
- function_item fmt @315-323
- mod_item tests @327-381
- function_item export_trie @330-347
- function_item export_trie_linkedit_data @350-369
- function_item invalid_range @372-380

### third_party/rust/goblin/src/mach/fat.rs

Blob: `33d945748afc9cfe5acc1baf42c805da8eecd5ba`. Grammar: rust. Status: syntax-clean.

- struct_item FatHeader @20-25
- function_item fmt @30-35
- function_item from_bytes @40-45
- function_item from_fd @49-53
- function_item parse @56-58
- struct_item FatArch @64-73
- function_item fmt @78-86
- function_item slice @91-105
- function_item cputype @108-110
- function_item cpusubtype @113-115
- function_item cpu_caps @118-120
- function_item is_64 @123-125
- function_item parse @128-131

### third_party/rust/goblin/src/mach/header.rs

Blob: `df8731f111c66848bbf804bac84239681695e062`. Grammar: rust. Status: syntax-clean.

- function_item flag_to_str @80-110
- function_item filetype_to_str @145-161
- struct_item Header32 @166-181
- function_item from_bytes @189-191
- function_item size @192-194
- struct_item Header64 @200-216
- function_item from_bytes @224-226
- function_item size @227-229
- struct_item Header @235-248
- function_item fmt @251-262
- function_item from @266-277
- function_item from @281-291
- function_item from @295-306
- function_item from @310-321
- function_item new @325-329
- function_item cputype @331-333
- function_item cpusubtype @335-337
- function_item cpu_caps @339-341
- function_item size_with @345-350
- function_item size_with @354-359
- function_item try_from_ctx @364-385
- function_item try_into_ctx @390-400
- function_item into_ctx @404-406
- mod_item tests @410-438
- function_item test_parse_armv7_header @415-427
- function_item sizeof_header32 @430-432
- function_item sizeof_header64 @435-437

### third_party/rust/goblin/src/mach/imports.rs

Blob: `3c31329a96625570edebc937aad95deb1dd7780d`. Grammar: rust. Status: syntax-clean.

- struct_item BindInformation @20-30
- function_item new @33-40
- function_item is_weak @41-43
- function_item default @47-59
- struct_item Import @64-83
- function_item new @87-112
- struct_item BindInterpreter @118-122
- function_item fmt @125-140
- function_item new @145-157
- function_item imports @159-169
- function_item run @170-307

### third_party/rust/goblin/src/mach/load_command.rs

Blob: `305c3b823f0f7713e5bc1d2d8682240bfc9ae209`. Grammar: rust. Status: syntax-clean.

- struct_item LoadCommandHeader @17-20
- function_item fmt @23-30
- struct_item Section32 @41-64
- struct_item Section64 @71-96
- struct_item SegmentCommand32 @102-114
- function_item name @119-121
- struct_item SegmentCommand64 @126-138
- function_item name @143-145
- struct_item Fvmlib @153-160
- struct_item FvmlibCommand @171-178
- struct_item Dylib @203-212
- struct_item DylibCommand @218-225
- struct_item SubFrameworkCommand @239-246
- struct_item SubClientCommand @259-266
- struct_item SubUmbrellaCommand @283-290
- struct_item SubLibraryCommand @309-316
- struct_item PreboundDylibCommand @329-341
- struct_item DylinkerCommand @348-352
- struct_item ThreadCommand @382-396
- function_item instruction_pointer @399-498
- function_item try_from_ctx @503-547
- function_item clone @551-553
- function_item fmt @557-565
- struct_item RoutinesCommand32 @576-591
- struct_item RoutinesCommand64 @596-611
- struct_item SymtabCommand @615-622
- function_item default @625-634
- function_item new @638-640
- struct_item DysymtabCommand @685-724
- function_item default @727-750
- function_item new @754-756
- struct_item DylibTableOfContents @765-770
- struct_item DylibModule @776-805
- struct_item DylibModule64 @811-842
- struct_item DylibReference @852-857
- struct_item TwolevelHintsCommand @863-872
- struct_item TwolevelHint @890-895
- struct_item PrebindCksumCommand @908-915
- struct_item UuidCommand @921-928
- struct_item RpathCommand @936-943
- struct_item LinkeditDataCommand @951-961
- struct_item EncryptionInfoCommand32 @969-980
- struct_item EncryptionInfoCommand64 @988-1001
- enum_item Platform @1009-1014
- function_item try_from @1019-1032
- struct_item VersionMinCommand @1040-1048
- function_item new @1051-1058
- function_item platform @1060-1066
- struct_item DyldInfoCommand @1073-1098
- struct_item LinkerOptionCommand @1105-1111
- struct_item SymsegCommand @1124-1133
- struct_item IdentCommand @1143-1148
- struct_item FvmfileCommand @1158-1167
- struct_item EntryPointCommand @1177-1184
- struct_item BuildVersionCommand @1193-1205
- struct_item BuildToolVersion @1210-1215
- struct_item FilesetEntryCommand @1221-1233
- struct_item SourceVersionCommand @1239-1245
- struct_item DataInCodeEntry @1252-1259
- struct_item NoteCommand @1265-1275
- function_item cmd_to_str @1353-1411
- enum_item CommandVariant @1421-1477
- function_item try_from_ctx @1481-1712
- function_item cmdsize @1716-1776
- function_item cmd @1777-1836
- struct_item LoadCommand @1841-1846
- function_item parse @1850-1859

### third_party/rust/goblin/src/mach/mod.rs

Blob: `6355e7af070cc5ac2b2fa96727667b11ce1a77df`. Grammar: rust. Status: syntax-clean.

- mod_item bind_opcodes @13-13
- mod_item constants @14-14
- mod_item exports @15-15
- mod_item fat @16-16
- mod_item header @17-17
- mod_item imports @18-18
- mod_item load_command @19-19
- mod_item relocation @20-20
- mod_item segment @21-21
- mod_item symbols @22-22
- function_item peek @27-29
- function_item parse_magic_and_ctx @32-53
- struct_item MachO @56-83
- function_item fmt @86-101
- function_item is_object_file @106-108
- function_item symbols @110-116
- function_item relocations @118-132
- function_item exports @134-140
- function_item imports @142-148
- function_item parse @150-152
- function_item parse_lossy @155-157
- function_item parse_impl @160-313
- struct_item MultiArch @317-321
- struct_item FatArchIterator @324-329
- enum_item SingleArch @335-338
- function_item next @342-354
- struct_item SingleArchIterator @358-363
- function_item peek_bytes @365-392
- function_item extract_multi_entry @394-412
- function_item next @416-431
- function_item into_iter @437-444
- function_item new @449-456
- function_item iter_arches @458-465
- function_item arches @467-477
- function_item get @479-490
- function_item find @492-502
- function_item find_cputype @504-512
- function_item fmt @516-521
- enum_item Mach @527-532
- function_item parse @536-538
- function_item parse_lossy @541-543
- function_item parse_impl @546-564
- mod_item test @568-628
- function_item parse_multi_arch_of_macho_binaries @572-598
- function_item parse_multi_arch_of_archives @601-627

### third_party/rust/goblin/src/mach/relocation.rs

Blob: `8e39fb749f6fb1fd02903d04909708cfb8d13579`. Grammar: rust. Status: syntax-clean.

- struct_item RelocationInfo @32-38
- function_item r_symbolnum @45-47
- function_item r_pcrel @50-52
- function_item r_length @55-57
- function_item r_extern @60-62
- function_item r_type @65-67
- function_item is_extern @70-72
- function_item is_pic @75-77
- function_item to_str @79-81
- function_item fmt @88-98
- function_item reloc_to_str @168-222

### third_party/rust/goblin/src/mach/segment.rs

Blob: `6fab7866ff1c05f30a4e2cb0998625b3255cecc3`. Grammar: rust. Status: syntax-clean.

- struct_item RelocationIterator @21-27
- function_item next @31-41
- struct_item Section @46-65
- function_item name @69-71
- function_item segname @73-75
- function_item iter_relocations @77-95
- function_item from @99-114
- function_item from @118-132
- function_item fmt @136-148
- function_item from @152-164
- function_item from @168-180
- function_item try_from_ctx @185-196
- function_item size_with @200-205
- function_item try_into_ctx @210-217
- function_item into_ctx @221-223
- struct_item SectionIterator @226-232
- function_item len @237-239
- function_item next @244-283
- function_item into_iter @289-297
- struct_item Segment @301-317
- function_item from @320-334
- function_item from @338-352
- function_item fmt @356-380
- function_item size_with @384-389
- function_item try_into_ctx @394-406
- function_item into_ctx @410-412
- function_item segment_data @416-423
- function_item new @428-450
- function_item name @452-454
- function_item sections @456-462
- function_item from_32 @464-471
- function_item from_32_lossy @474-481
- function_item from_32_impl @483-515
- function_item from_64 @518-525
- function_item from_64_lossy @528-535
- function_item from_64_impl @537-565
- struct_item Segments @570-572
- function_item deref @576-578
- function_item deref_mut @582-584
- function_item into_iter @590-592
- function_item new @597-601
- function_item sections @604-606

### third_party/rust/goblin/src/mach/symbols.rs

Blob: `adfc4d665bb41a11af97178f678571acc5af3aa5`. Grammar: rust. Status: syntax-clean.

- function_item n_type_to_str @128-137
- struct_item Nlist32 @141-152
- function_item fmt @157-165
- struct_item Nlist64 @170-181
- function_item fmt @186-194
- struct_item Nlist @198-209
- function_item get_type @213-215
- function_item type_str @217-219
- function_item is_global @221-223
- function_item is_weak @225-227
- function_item is_undefined @229-231
- function_item is_stab @233-235
- function_item size_with @239-244
- function_item from @248-256
- function_item from @260-268
- function_item from @272-280
- function_item from @284-292
- function_item try_from_ctx @297-306
- function_item try_into_ctx @311-321
- function_item into_ctx @325-327
- struct_item SymbolsCtx @331-335
- function_item try_from_ctx @342-357
- struct_item SymbolIterator @361-368
- function_item next @372-385
- struct_item Symbols @389-396
- function_item into_iter @401-403
- function_item new @410-424
- function_item parse @425-443
- function_item iter @445-454
- function_item get @457-463
- function_item fmt @467-487

### third_party/rust/goblin/src/pe/authenticode.rs

Blob: `1af46d6939c0eaf8ff64882c4cf5dca740039b20`. Grammar: rust. Status: syntax-clean.

- function_item authenticode_ranges @21-27
- struct_item ExcludedSections @33-38
- function_item new @41-53
- struct_item ExcludedSectionsIter @56-60
- enum_item IterState @63-80
- function_item default @83-85
- function_item next @91-276

### third_party/rust/goblin/src/pe/certificate_table.rs

Blob: `be45ce48dcef18a532e6d393d1ea655c3a3530d9`. Grammar: rust. Status: syntax-clean.

- enum_item AttributeCertificateRevision @16-21
- function_item try_from @26-40
- enum_item AttributeCertificateType @45-54
- function_item try_from @59-77
- struct_item AttributeCertificateHeader @81-86
- struct_item AttributeCertificate @90-95
- function_item parse @98-130
- function_item try_into_ctx @137-150
- function_item enumerate_certificates @155-188

### third_party/rust/goblin/src/pe/characteristic.rs

Blob: `801ffcc133f83bf749b631bd424dcebb0b7488ff`. Grammar: rust. Status: syntax-clean.

- function_item is_dll @133-135
- function_item is_exe @138-140

### third_party/rust/goblin/src/pe/data_directories.rs

Blob: `e65db5953d7a5a40796454c45359616509675c0f`. Grammar: rust. Status: syntax-clean.

- struct_item DataDirectory @9-12
- function_item parse @18-20
- enum_item DataDirectoryType @24-40
- function_item try_from @44-67
- struct_item DataDirectories @71-73
- function_item try_into_ctx @78-89
- function_item parse @102-120
- function_item dirs @138-152

### third_party/rust/goblin/src/pe/debug.rs

Blob: `89e6d21a6013daedba1d754cdd806bcf47fce414`. Grammar: rust. Status: syntax-clean.

- struct_item DebugData @10-14
- function_item parse @17-30
- function_item parse_with_opts @32-51
- function_item guid @54-56
- struct_item ImageDebugDirectory @62-71
- function_item parse @84-97
- function_item parse_with_opts @99-115
- struct_item CodeviewPDB70DebugInfo @126-131
- function_item parse @134-136
- function_item parse_with_opts @138-189
- struct_item CodeviewPDB20DebugInfo @195-201
- function_item parse @204-206
- function_item parse_with_opts @208-260

### third_party/rust/goblin/src/pe/dll_characteristic.rs

Blob: `b63d01d5dff59ebd524448701473a77603792d17`. Grammar: rust. Status: syntax-clean.


### third_party/rust/goblin/src/pe/exception.rs

Blob: `e4440c16dcea35a075ae09f60139ebf273db1728`. Grammar: rust. Status: syntax-clean.

- struct_item RuntimeFunction @104-111
- function_item fmt @114-123
- struct_item RuntimeFunctionIterator @128-130
- function_item next @135-150
- function_item size_hint @152-155
- struct_item Register @166-166
- function_item xmm @169-171
- function_item name @174-211
- enum_item StackFrameOffset @216-228
- function_item with_ctx @231-236
- function_item fmt @240-242
- enum_item UnwindOperation @250-315
- struct_item UnwindOpContext @319-329
- struct_item UnwindCode @333-345
- function_item try_from_ctx @350-441
- struct_item UnwindCodeIterator @449-453
- function_item next @458-464
- function_item size_hint @466-471
- enum_item UnwindHandler @479-484
- struct_item UnwindInfo @498-535
- function_item parse @539-610
- function_item unwind_codes @617-626
- function_item fmt @630-642
- function_item into_iter @650-652
- struct_item ExceptionData @656-661
- function_item parse @665-678
- function_item parse_with_opts @681-712
- function_item len @715-717
- function_item is_empty @720-722
- function_item functions @731-735
- function_item get_function @738-740
- function_item find_function @744-778
- function_item get_unwind_info @781-787
- function_item get_unwind_info_with_opts @790-808
- function_item get_function_by_rva @811-817
- function_item get_function_by_rva_with_opts @819-834
- function_item get_function_by_offset @837-842
- function_item fmt @846-853
- function_item into_iter @861-863
- mod_item tests @867-1058
- function_item test_size_of_runtime_function @871-876
- function_item test_iter_unwind_codes @1033-1057

### third_party/rust/goblin/src/pe/export.rs

Blob: `f892c75276530f8f90f196eb353585e7ee9a23b9`. Grammar: rust. Status: syntax-clean.

- struct_item ExportDirectoryTable @15-27
- function_item parse @32-35
- enum_item ExportAddressTableEntry @39-42
- struct_item ExportData @60-66
- function_item parse @69-82
- function_item parse_with_opts @84-207
- enum_item Reexport @212-215
- function_item try_from_ctx @220-262
- function_item parse @266-268
- struct_item Export @273-279
- struct_item ExportCtx @282-290
- function_item try_from_ctx @295-367
- function_item parse @371-384
- function_item parse_with_opts @386-417
- mod_item tests @421-533
- function_item size_export_directory_table @498-503
- function_item parse_export_table @506-513
- function_item parse_export_directory @516-532

### third_party/rust/goblin/src/pe/header.rs

Blob: `d1b4f36a4fa3d5ce92fd773378078d3a049b2176`. Grammar: rust. Status: syntax-clean.

- struct_item DosHeader @36-291
- function_item parse @299-381
- struct_item DosStub @394-394
- function_item default @396-405
- struct_item CoffHeader @423-502
- function_item parse @705-707
- function_item sections @713-736
- function_item symbols @739-747
- function_item strings @750-767
- struct_item Header @777-791
- function_item parse_impl @794-813
- function_item parse @816-826
- function_item parse_without_dos @829-832
- function_item try_into_ctx @838-848
- struct_item TeHeader @859-881
- function_item parse @890-895
- function_item sections @898-919
- function_item fixup_header @922-950
- function_item fixup_section @953-989
- function_item machine_to_str @994-1030
- mod_item tests @1033-1094
- function_item crss_header @1086-1093

### third_party/rust/goblin/src/pe/import.rs

Blob: `0284fc3276f0ebaf505d63baa50e6d2fb5fc69a5`. Grammar: rust. Status: syntax-clean.

- trait_item Bitfield @21-34
- function_signature_item is_ordinal @29-29
- function_signature_item to_ordinal @30-30
- function_signature_item to_rva @31-31
- function_signature_item size_of @32-32
- function_signature_item is_zero @33-33
- function_item is_ordinal @37-39
- function_item to_ordinal @40-42
- function_item to_rva @43-45
- function_item size_of @46-48
- function_item is_zero @49-51
- function_item is_ordinal @55-57
- function_item to_ordinal @58-60
- function_item to_rva @61-63
- function_item size_of @64-66
- function_item is_zero @67-69
- struct_item HintNameTableEntry @73-76
- function_item parse @79-84
- enum_item SyntheticImportLookupTableEntry @88-91
- function_item parse @96-109
- function_item parse_with_opts @111-155
- struct_item ImportDirectoryEntry @163-169
- function_item is_null @174-180
- struct_item SyntheticImportDirectoryEntry @184-192
- function_item parse @195-208
- function_item parse_with_opts @210-295
- struct_item ImportData @300-302
- function_item parse @305-318
- function_item parse_with_opts @320-362
- struct_item Import @367-374
- function_item parse @377-416

### third_party/rust/goblin/src/pe/mod.rs

Blob: `3c8c3c3e462335c70559bfd5950d5451688d3831`. Grammar: rust. Status: syntax-clean.

- mod_item authenticode @13-13
- mod_item certificate_table @14-14
- mod_item characteristic @15-15
- mod_item data_directories @16-16
- mod_item debug @17-17
- mod_item dll_characteristic @18-18
- mod_item exception @19-19
- mod_item export @20-20
- mod_item header @21-21
- mod_item import @22-22
- mod_item optional_header @23-23
- mod_item options @24-24
- mod_item relocation @25-25
- mod_item section_table @26-26
- mod_item subsystem @27-27
- mod_item symbol @28-28
- mod_item tls @29-29
- mod_item utils @30-30
- struct_item PE @43-81
- function_item parse @85-87
- function_item parse_with_opts @90-309
- function_item write_sections @311-390
- function_item write_certificates @392-414
- function_item try_into_ctx @420-495
- struct_item TE @508-518
- function_item parse @523-560
- function_item fixup_debug_data @563-587
- struct_item Coff @592-603
- function_item parse @607-622
- mod_item tests @626-771
- function_item string_table_excludes_length @737-742
- function_item symbol_name_excludes_length @745-756
- function_item invalid_dos_header @759-763
- function_item invalid_pe_header @766-770

### third_party/rust/goblin/src/pe/optional_header.rs

Blob: `e3fba43f7083c03de2ccc06541e5f77cfd0f417d`. Grammar: rust. Status: syntax-clean.

- struct_item StandardFields32 @19-38
- struct_item StandardFields64 @51-68
- struct_item StandardFields @93-131
- function_item from @134-146
- function_item from @150-162
- function_item from @166-178
- function_item from @182-193
- struct_item WindowsFields32 @209-252
- struct_item WindowsFields64 @270-402
- function_item from @436-460
- function_item try_from @466-490
- struct_item OptionalHeader @552-559
- function_item container @572-578
- function_item try_from_ctx @583-612
- function_item try_into_ctx @618-634
- mod_item tests @638-668
- function_item sizeof_standards32 @641-646
- function_item sizeof_windows32 @648-653
- function_item sizeof_standards64 @655-660
- function_item sizeof_windows64 @662-667

### third_party/rust/goblin/src/pe/options.rs

Blob: `4461a4c7bd1f7a6cdd8d21c4064ada526c3ac846`. Grammar: rust. Status: syntax-clean.

- struct_item ParseOptions @3-11
- function_item default @15-20

### third_party/rust/goblin/src/pe/relocation.rs

Blob: `ab8398ce73b4af5073a24c43f2ffa9ea308aa64b`. Grammar: rust. Status: syntax-clean.

- struct_item Relocation @82-98
- struct_item Relocations @102-105
- function_item parse @111-117
- function_item next @122-132

### third_party/rust/goblin/src/pe/section_table.rs

Blob: `f49c2b689ccc8224025bd8e98ab2f86f00467ad3`. Grammar: rust. Status: syntax-clean.

- struct_item SectionTable @10-22
- function_item base64_decode_string_entry @29-55
- function_item parse @58-82
- function_item data @84-108
- function_item name_offset @110-131
- function_item set_name_offset @134-180
- function_item name @182-187
- function_item relocations @189-193
- function_item overlaps_with @196-202
- function_item size_with @206-208
- function_item try_into_ctx @213-226
- function_item into_ctx @230-232
- mod_item tests @293-316
- function_item set_name_offset @297-315

### third_party/rust/goblin/src/pe/subsystem.rs

Blob: `a611591ae56417ad813d76dd59cba6773b622a66`. Grammar: rust. Status: syntax-clean.


### third_party/rust/goblin/src/pe/symbol.rs

Blob: `e5aba25beca7f6f7b91906059d8ee76b243ce56a`. Grammar: rust. Status: syntax-clean.

- struct_item Symbol @168-196
- function_item parse @203-213
- function_item name @219-227
- function_item name_offset @232-244
- function_item set_name_offset @247-250
- function_item base_type @255-257
- function_item derived_type @262-264
- function_item is_function_definition @269-273
- function_item is_weak_external @278-280
- function_item is_file @285-287
- function_item is_section_definition @292-294
- struct_item AuxFunctionDefinition @300-317
- struct_item AuxBeginAndEndFunction @322-337
- struct_item AuxWeakExternal @351-358
- struct_item AuxSectionDefinition @391-412
- struct_item SymbolTable @416-418
- function_item parse @424-427
- function_item size @430-432
- function_item get @438-441
- function_item aux_function_definition @444-447
- function_item aux_begin_and_end_function @450-453
- function_item aux_weak_external @456-459
- function_item aux_file @462-468
- function_item aux_section_definition @471-474
- function_item iter @479-484
- function_item try_into_ctx @490-492
- function_item fmt @496-500
- struct_item SymbolIterator @507-510
- function_item next @514-524

### third_party/rust/goblin/src/pe/tls.rs

Blob: `2369bb0e6f113942982787f602719a835d142eeb`. Grammar: rust. Status: syntax-clean.

- struct_item ImageTlsDirectory @13-32
- struct_item TlsData @36-45
- function_item parse @48-61
- function_item parse_with_opts @63-114
- function_item parse @118-133
- function_item parse_with_opts @135-246

### third_party/rust/goblin/src/pe/utils.rs

Blob: `d4d01726bf0f007dcc705f857df60f76b8095898`. Grammar: rust. Status: syntax-clean.

- function_item is_in_range @14-16
- function_item aligned_pointer_to_raw_data @20-23
- function_item section_read_size @26-72
- function_item round_size @27-30
- function_item rva2offset @74-77
- function_item is_in_section @79-86
- function_item find_offset @88-121
- function_item find_offset_or @123-132
- function_item try_name @134-148
- function_item get_data @150-166
- function_item get_data_with_opts @168-183
- function_item pad @185-198

### third_party/rust/goblin/src/strtab.rs

Blob: `e8ab18ed21775a53510d4f363cf6f330fe1b8272`. Grammar: rust. Status: syntax-clean.

- struct_item Strtab @16-21
- function_item get_str @24-26
- function_item new @33-35
- function_item len @38-40
- function_item from_slice_unparsed @45-52
- function_item get_unsafe @57-63
- function_item parse @69-88
- function_item new_preparsed @93-95
- function_item to_vec @118-131
- function_item get_at @137-151
- function_item from_raw @157-159
- function_item get @166-172
- function_item fmt @176-181
- function_item default @185-192
- function_item index @200-205
- function_item as_vec_no_final_null @209-214
- function_item as_vec_no_first_null_no_final_null @217-222
- function_item to_vec_final_null @225-230
- function_item to_vec_newline_delim @233-238
- function_item parse_utf8 @241-255
- function_item get_at_utf8 @258-269

### third_party/rust/gpu-allocator/examples/d3d12-buffer-winrs.rs

Blob: `b5f5354cd960a57fb9a36b2cd699342c956cf5e1`. Grammar: rust. Status: syntax-clean.

- function_item create_d3d12_device @30-80
- function_item main @82-240

### third_party/rust/gpu-allocator/examples/metal-buffer.rs

Blob: `1d30bbe73fa627a9a6efbc1e4955d80934ab96d4`. Grammar: rust. Status: syntax-clean.

- function_item main @9-147

### third_party/rust/gpu-allocator/examples/vulkan-buffer.rs

Blob: `dcf0b9ca26f1c33599119a38092af0a2be9d1839`. Grammar: rust. Status: syntax-clean.

- function_item main @10-198

### third_party/rust/gpu-allocator/src/allocator/dedicated_block_allocator/mod.rs

Blob: `02bb13df8e9e0cf14cd1d40143d1df8dc3f2c81c`. Grammar: rust. Status: syntax-clean.

- mod_item visualizer @15-15
- struct_item DedicatedBlockAllocator @21-28
- function_item new @31-39
- function_item allocate @44-73
- function_item free @75-82
- function_item rename_allocation @84-95
- function_item report_memory_leaks @97-135
- function_item report_allocations @137-148
- function_item allocated @150-152
- function_item supports_general_allocations @154-156

### third_party/rust/gpu-allocator/src/allocator/dedicated_block_allocator/visualizer.rs

Blob: `a2cd4d205822a3a7b45078425cb6554d4ea2e740`. Grammar: rust. Status: syntax-clean.

- function_item draw_base_info @5-7

### third_party/rust/gpu-allocator/src/allocator/free_list_allocator/mod.rs

Blob: `db969d683301bc7312ab9abe99666f1d3a2a1b92`. Grammar: rust. Status: syntax-clean.

- mod_item visualizer @19-19
- function_item align_down @26-28
- function_item align_up @30-32
- struct_item MemoryChunk @35-46
- struct_item FreeListAllocator @49-55
- function_item is_on_same_page @58-65
- function_item has_granularity_conflict @68-74
- function_item new @77-109
- function_item get_new_chunk_id @112-123
- function_item remove_id_from_free_list @125-127
- function_item merge_free_chunks @129-162
- function_item allocate @167-304
- function_item free @306-342
- function_item rename_allocation @344-367
- function_item report_memory_leaks @369-417
- function_item report_allocations @419-434
- function_item allocated @436-438
- function_item supports_general_allocations @440-442

### third_party/rust/gpu-allocator/src/allocator/free_list_allocator/visualizer.rs

Blob: `5c7783105770ee7b418dd72f59a14c4d1fff8355`. Grammar: rust. Status: syntax-clean.

- function_item supports_visualization @7-9
- function_item draw_base_info @11-15
- function_item draw_visualization @17-24

### third_party/rust/gpu-allocator/src/allocator/mod.rs

Blob: `523ebcbd5f41e9947a33faa54bd283eea53c4a1a`. Grammar: rust. Status: syntax-clean.

- mod_item dedicated_block_allocator @12-12
- mod_item free_list_allocator @15-15
- enum_item AllocationType @20-24
- function_item as_str @28-34
- struct_item AllocationReport @39-48
- struct_item MemoryBlockReport @52-58
- struct_item AllocatorReport @62-71
- function_item fmt @74-81
- function_item fmt @85-105
- trait_item SubAllocatorBase @109-109
- trait_item SubAllocatorBase @111-111
- trait_item SubAllocator @113-153
- function_signature_item allocate @114-122
- function_signature_item free @124-124
- function_signature_item rename_allocation @126-130
- function_signature_item report_memory_leaks @132-137
- function_signature_item report_allocations @139-139
- function_signature_item supports_general_allocations @144-144
- function_signature_item allocated @146-146
- function_item is_empty @150-152
- function_item fmt_bytes @155-169

### third_party/rust/gpu-allocator/src/d3d12/mod.rs

Blob: `9cb9a0ff09b3204f081b4c31b1f08c987deffda8`. Grammar: rust. Status: syntax-clean.

- mod_item visualizer @22-22
- enum_item ResourceCategory @37-41
- enum_item ResourceStateOrBarrierLayout @44-47
- struct_item ResourceCreateDesc @50-59
- enum_item HeapCategory @62-67
- function_item from @70-76
- function_item from @80-91
- struct_item AllocationCreateDesc @95-111
- function_item from_d3d12_resource_desc @116-135
- enum_item ID3D12DeviceVersion @139-148
- function_item deref @153-159
- struct_item AllocatorCreateDesc @163-167
- enum_item ResourceType @169-181
- struct_item Resource @184-191
- function_item resource @194-196
- function_item drop @200-204
- struct_item CommittedAllocationStatistics @208-211
- struct_item Allocation @214-223
- function_item chunk_id @226-228
- function_item heap @241-243
- function_item offset @247-249
- function_item size @252-254
- function_item is_null @256-258
- struct_item MemoryBlock @262-266
- function_item new @268-315
- struct_item MemoryType @319-327
- function_item allocate @330-471
- function_item free @474-502
- struct_item Allocator @505-510
- function_item device @513-515
- function_item new @517-618
- function_item allocate @620-669
- function_item free @671-689
- function_item rename_allocation @691-708
- function_item report_memory_leaks @710-720
- function_item d3d12_resource_desc_1 @722-737
- function_item resource_allocation_info @739-780
- function_item create_resource @784-993
- function_item free_resource @996-1017
- function_item generate_report @1019-1044
- function_item capacity @1047-1057
- function_item fmt @1061-1063
- function_item drop @1067-1078

### third_party/rust/gpu-allocator/src/d3d12/visualizer.rs

Blob: `c1cd37a204f615672e8b60d4c4de0fbae21626e0`. Grammar: rust. Status: syntax-clean.

- struct_item AllocatorVisualizerBlockWindow @11-15
- function_item new @18-24
- struct_item AllocatorVisualizer @27-31
- function_item format_heap_type @33-43
- function_item format_cpu_page_property @45-54
- function_item format_memory_pool @56-64
- function_item new @67-73
- function_item set_color_scheme @75-77
- function_item render_memory_block_ui @79-166
- function_item render_memory_block_window @168-177
- function_item render_memory_block_visualization_windows @179-224
- function_item render_breakdown_ui @226-237
- function_item render_breakdown_window @239-248

### third_party/rust/gpu-allocator/src/lib.rs

Blob: `0906aabfd23e7c3f1d58b3efdeed438ab9efb83e`. Grammar: rust. Status: syntax-clean.

- mod_item result @227-227
- mod_item allocator @230-230
- mod_item visualizer @235-235
- mod_item vulkan @238-238
- mod_item d3d12 @241-241
- mod_item metal @244-244
- enum_item MemoryLocation @247-257
- struct_item AllocatorDebugSettings @261-278
- function_item default @281-292
- struct_item AllocationSizes @340-363
- function_item new @371-381
- function_item with_max_device_memblock_size @384-389
- function_item with_max_host_memblock_size @392-397
- function_item adjust_memblock_size @399-416
- function_item get_memblock_size @424-436
- function_item default @440-448

### third_party/rust/gpu-allocator/src/metal/mod.rs

Blob: `13972204ca6beb6688ce5c6d9b2fed7a484e7eb9`. Grammar: rust. Status: syntax-clean.

- mod_item visualizer @18-18
- function_item memory_location_to_metal @30-37
- struct_item Allocation @40-48
- function_item heap @63-65
- function_item size @68-70
- function_item offset @76-78
- function_item name @80-82
- function_item is_null @84-86
- struct_item AllocationCreateDesc @90-97
- function_item buffer @100-116
- function_item texture @118-136
- function_item acceleration_structure_with_size @138-154
- struct_item Allocator @157-163
- function_item fmt @166-168
- struct_item AllocatorCreateDesc @172-179
- struct_item CommittedAllocationStatistics @182-185
- struct_item MemoryBlock @188-192
- function_item new @195-223
- struct_item MemoryType @227-235
- function_item allocate @238-387
- function_item free @389-421
- function_item new @425-486
- function_item allocate @488-533
- function_item free @535-551
- function_item heaps @554-562
- function_item generate_report @564-589
- function_item capacity @592-602
- function_item residency_set @625-629

### third_party/rust/gpu-allocator/src/metal/visualizer.rs

Blob: `26b3c13563805dcc59bf93afa23de6fc1102df10`. Grammar: rust. Status: syntax-clean.

- struct_item AllocatorVisualizerBlockWindow @9-13
- function_item new @15-21
- struct_item AllocatorVisualizer @24-28
- function_item new @31-37
- function_item set_color_scheme @39-41
- function_item render_memory_block_ui @43-109
- function_item render_memory_block_window @111-120
- function_item render_memory_block_visualization_windows @122-167
- function_item render_breakdown_ui @169-180
- function_item render_breakdown_window @182-191

### third_party/rust/gpu-allocator/src/result.rs

Blob: `50bfff3333716943b1a256c655acbeefef42ad0a`. Grammar: rust. Status: syntax-clean.

- enum_item AllocationError @6-25

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [a6147e01-6373-499a-ac0f-7c0d2a73a7eb.md](a6147e01-6373-499a-ac0f-7c0d2a73a7eb.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `e69d471aef24b9683427503b6560875bb8351e5cb49dad9c49a26dc5f2ef016d`.
