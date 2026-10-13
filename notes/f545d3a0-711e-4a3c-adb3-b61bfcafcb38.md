<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["third_party"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["b61ee61bf86a6a7887cd5ba408d1e3debb5dc7eb4ac55bd18591cda8bc66d2cd"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/f73792f1-bd90-4483-b56c-86d9854529c0.md"}} -->
# firefox/third_party native and TypeScript syntax map 362

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### third_party/rust/foldhash/src/convenience.rs

Blob: `dd1dd4e2a07bf1fd390540ec01758ddd50c584d6`. Grammar: rust. Status: syntax-clean.

- trait_item HashMapExt @10-16
- function_signature_item new @12-12
- function_signature_item with_capacity @15-15
- function_item new @20-22
- function_item with_capacity @25-27
- function_item new @32-34
- function_item with_capacity @37-39
- trait_item HashSetExt @43-49
- function_signature_item new @45-45
- function_signature_item with_capacity @48-48
- function_item new @53-55
- function_item with_capacity @58-60
- function_item new @65-67
- function_item with_capacity @70-72

### third_party/rust/foldhash/src/fast.rs

Blob: `4307a15858b8437fb737088a6b64429d71bde28d`. Grammar: rust. Status: syntax-clean.

- struct_item FoldHasher @14-19
- function_item with_seed @25-32
- function_item write_num @35-47
- function_item write @52-68
- function_item write_u8 @71-73
- function_item write_u16 @76-78
- function_item write_u32 @81-83
- function_item write_u64 @86-88
- function_item write_u128 @91-95
- function_item write_usize @98-104
- function_item write_str @108-111
- function_item finish @114-122
- struct_item RandomState @127-130
- function_item default @134-139
- function_item build_hasher @146-148
- struct_item SeedableRandomState @157-160
- function_item default @164-166
- function_item random @172-177
- function_item fixed @181-186
- function_item with_seed @191-197
- function_item build_hasher @204-206
- struct_item FixedState @213-215
- function_item with_seed @220-225
- function_item default @230-234
- function_item build_hasher @241-243

### third_party/rust/foldhash/src/lib.rs

Blob: `5ebb5fe27617fdb704fb8d1a23b4742eff4ee871`. Grammar: rust. Status: syntax-clean.

- mod_item fast @118-118
- mod_item quality @119-119
- mod_item seed @120-120
- mod_item convenience @124-124
- function_item folded_multiply @143-206
- function_item rotate_right @209-233
- function_item cold_path @236-236
- function_item hash_bytes_short @240-259
- function_item load @266-271
- function_item hash_bytes_long @279-350

### third_party/rust/foldhash/src/quality.rs

Blob: `2dd43461e6ec92180d608bf38bd367e67fa15752`. Grammar: rust. Status: syntax-clean.

- struct_item FoldHasher @15-17
- function_item with_seed @23-27
- function_item write @32-34
- function_item write_u8 @37-39
- function_item write_u16 @42-44
- function_item write_u32 @47-49
- function_item write_u64 @52-54
- function_item write_u128 @57-59
- function_item write_usize @62-64
- function_item write_str @68-70
- function_item finish @73-75
- struct_item RandomState @80-82
- function_item build_hasher @88-92
- struct_item SeedableRandomState @101-103
- function_item random @108-112
- function_item fixed @116-120
- function_item with_seed @125-135
- function_item build_hasher @142-146
- struct_item FixedState @153-155
- function_item with_seed @160-168
- function_item build_hasher @175-179

### third_party/rust/foldhash/src/seed.rs

Blob: `257c445194ad06eacdd9f605b6707c029631e0f9`. Grammar: rust. Status: syntax-clean.

- function_item gen_per_hasher_seed @22-71
- struct_item SharedSeed @78-80
- function_item global_random @86-88
- function_item global_fixed @93-95
- function_item from_u64 @102-131
- mod_item global @135-259
- function_item generate_global_seed @140-174
- struct_item GlobalSeedStorage @181-184
- struct_item GlobalSeed @205-208
- function_item new @212-219
- function_item init_slow @223-250
- function_item get @253-257
- mod_item global @262-279
- struct_item GlobalSeed @266-266
- function_item new @270-272
- function_item get @275-277

### third_party/rust/font-types/src/bbox.rs

Blob: `d414422b223c1afb46f2d45dee2f74cc21f314c4`. Grammar: rust. Status: syntax-clean.

- struct_item BoundingBox @6-18
- function_item scale @26-33

### third_party/rust/font-types/src/fixed.rs

Blob: `4bc31adc5799ac7b9c6815c100de9a1bf386f010`. Grammar: rust. Status: syntax-clean.

- function_item mul_div @155-182
- function_item mul @189-192
- function_item div @198-212
- function_item mul @219-222
- function_item div @228-242
- function_item from_i32 @363-365
- function_item to_i32 @370-372
- function_item to_f26dot6 @376-378
- function_item to_f2dot14 @388-390
- function_item to_f32 @397-400
- function_item from @404-406
- function_item from_i32 @412-414
- function_item to_i32 @419-421
- function_item to_f32 @428-431
- function_item to_fixed @437-439
- mod_item tests @443-700
- function_item f2dot14_floats @448-456
- function_item roundtrip_f2dot14 @459-464
- function_item round_f2dot14 @467-471
- function_item round_fixed @474-479
- function_item fixed_floats @491-501
- function_item fixed_floats_rounding @507-518
- function_item with_round_intrinsic @508-510
- function_item fixed_to_int @521-526
- function_item fixed_from_int @529-532
- function_item fixed_to_f26dot6 @535-537
- function_item fixed_muldiv @540-549
- function_item fixed_div_neg_overflow @555-560
- function_item fixed_mul_div_neg_overflow @563-568
- function_item fixed_div_min_value @571-580
- function_item f26dot6_muldiv @583-608
- mod_item serde @611-699
- function_item one_is_one_f2dot14 @625-627
- function_item one_is_one_f4dot12 @630-632
- function_item one_is_one_f6dot10 @635-637
- function_item one_is_one_fixed @640-642
- function_item one_is_one_f26dot6 @645-647
- function_item roundtrip_all_f2dot14 @674-676
- function_item roundtrip_all_f4dot12 @679-681
- function_item roundtrip_all_f6dot10 @684-686
- function_item roundtrip_all_fixed @690-692
- function_item roundtrip_all_f26dot6 @696-698

### third_party/rust/font-types/src/fword.rs

Blob: `1f1071a343942c7fb1631cd0808784b1b429b2ce`. Grammar: rust. Status: syntax-clean.

- struct_item FWord @10-10
- struct_item UfWord @17-17
- function_item new @20-22
- function_item to_i16 @24-26
- function_item to_fixed @29-31
- function_item to_be_bytes @34-36
- function_item new @40-42
- function_item to_u16 @44-46
- function_item to_fixed @49-51
- function_item to_be_bytes @54-56
- function_item fmt @60-62
- function_item fmt @66-68
- function_item from @72-74
- function_item from @78-80
- function_item from @84-86
- function_item from @90-92

### third_party/rust/font-types/src/glyph_id.rs

Blob: `aa0bb24d1bae5ca9121b442a96ea85db2890b389`. Grammar: rust. Status: syntax-clean.

- struct_item GlyphId16 @13-13
- function_item new @20-22
- function_item to_u16 @25-27
- function_item to_u32 @30-32
- function_item to_be_bytes @34-36
- function_item default @40-42
- function_item from @46-48
- function_item from @52-54
- function_item fmt @58-60
- function_item from @64-66
- struct_item GlyphId24 @76-76
- function_item new @83-85
- function_item checked_new @88-93
- function_item to_u32 @96-98
- function_item to_be_bytes @100-102
- function_item from_be_bytes @104-106
- function_item default @110-112
- function_item from @116-118
- function_item fmt @122-124
- function_item from @128-130
- struct_item GlyphId @140-140
- function_item new @147-149
- function_item to_u32 @152-154
- function_item default @158-160
- function_item from @164-166
- function_item from @170-172
- function_item fmt @176-178
- function_item from @182-184
- function_item from @188-190
- function_item from @194-196
- function_item eq @200-202
- function_item partial_cmp @206-208
- function_item eq @212-214
- function_item partial_cmp @218-220
- function_item try_from @226-233
- function_item try_from @239-241
- struct_item TryFromGlyphIdError @246-246
- function_item fmt @249-251

### third_party/rust/font-types/src/int24.rs

Blob: `2245d7ec36e87ab210eb87616f882945f2b877c5`. Grammar: rust. Status: syntax-clean.

- struct_item Int24 @6-6
- function_item new @16-23
- function_item checked_new @26-32
- function_item to_i32 @35-37
- function_item to_be_bytes @39-42
- function_item from_be_bytes @44-50
- function_item from @54-56
- function_item fmt @60-62
- mod_item tests @66-138
- function_item constructor @70-75
- function_item to_be_bytes @78-101
- function_item from_be_bytes @104-127
- function_item round_trip @130-137

### third_party/rust/font-types/src/lib.rs

Blob: `02a1b2f1f5622201c0e8a52166d31d9c06dcf684`. Grammar: rust. Status: syntax-clean.

- mod_item bbox @18-18
- mod_item fixed @19-19
- mod_item fword @20-20
- mod_item glyph_id @21-21
- mod_item int24 @22-22
- mod_item longdatetime @23-23
- mod_item matrix @24-24
- mod_item name_id @25-25
- mod_item offset @26-26
- mod_item point @27-27
- mod_item raw @28-28
- mod_item tag @29-29
- mod_item uint24 @30-30
- mod_item version @31-31
- mod_item serde_test @34-34

### third_party/rust/font-types/src/longdatetime.rs

Blob: `654ed7bb3b05fa72be7c679eeeeb6570fe1df05f`. Grammar: rust. Status: syntax-clean.

- struct_item LongDateTime @10-10
- function_item new @14-16
- function_item as_secs @22-24
- function_item to_be_bytes @27-29

### third_party/rust/font-types/src/matrix.rs

Blob: `926ab611ef70125deb4c9338538a968ed32d4682`. Grammar: rust. Status: syntax-clean.

- struct_item Matrix @38-45
- function_item default @48-50
- function_item from_elements @56-65
- function_item elements @69-71
- function_item map @75-77
- function_item transform @92-97
- function_item mul @103-112
- function_item mul_assign @116-118
- function_item mul @124-127
- trait_item MatrixElement @131-134
- mod_item tests @152-184
- function_item mul_matrix_identity_and_known_product @156-170
- function_item transform_points @173-183

### third_party/rust/font-types/src/name_id.rs

Blob: `bd8ef4fd52612bdc3c4b150f2815e33856b8f093`. Grammar: rust. Status: syntax-clean.

- struct_item NameId @22-22
- function_item new @173-175
- function_item predefined @180-183
- function_item to_u16 @187-189
- function_item is_reserved @193-195
- function_item checked_add @201-208
- function_item to_be_bytes @213-215
- function_item default @219-221
- function_item from @225-227
- function_item fmt @231-261
- function_item fmt @265-267

### third_party/rust/font-types/src/offset.rs

Blob: `19cf2eaeaf083d178d6b21bc2d1a34f5d4296f2a`. Grammar: rust. Status: syntax-clean.

- struct_item Nullable @10-10
- trait_item NullValue @13-15
- function_item from_raw @21-23
- function_item to_raw @26-28
- function_item offset @34-36
- function_item is_null @41-43
- function_item eq @48-50
- function_item default @54-56

### third_party/rust/font-types/src/point.rs

Blob: `b10eb3afca0d26da6397975f247139561ac5f876`. Grammar: rust. Status: syntax-clean.

- struct_item Point @8-13
- function_item new @38-40
- function_item broadcast @43-48
- function_item map @52-57
- function_item add @67-72
- function_item add_assign @80-83
- function_item sub @93-98
- function_item sub_assign @106-109
- function_item mul @119-124
- function_item mul @134-139
- function_item mul_assign @147-150
- function_item mul_assign @158-161
- function_item div @171-176
- function_item div @186-191
- function_item div_assign @199-202
- function_item div_assign @210-213
- function_item neg @223-228
- mod_item tests @232-282
- function_item map @237-242
- function_item add @245-250
- function_item sub @253-258
- function_item mul @261-267
- function_item div @270-276
- function_item neg @279-281

### third_party/rust/font-types/src/raw.rs

Blob: `4ab4bc8c4c2995ea063ae9abc1a3ba4414673f0c`. Grammar: rust. Status: syntax-clean.

- trait_item Scalar @9-26
- function_signature_item from_raw @14-14
- function_signature_item to_raw @17-17
- function_item read @23-25
- trait_item FixedSize @29-42
- mod_item sealed @46-69
- trait_item BeByteArray @52-55
- function_signature_item from_slice @54-54
- trait_item BeByteArray @57-62
- function_signature_item from_slice @61-61
- function_item from_slice @65-67
- struct_item BigEndian @75-75
- function_item new @88-90
- function_item from_slice @95-97
- function_item get @101-103
- function_item set @106-108
- function_item be_bytes @111-113
- function_item from @118-120
- function_item default @124-126
- function_item eq @132-134
- function_item partial_cmp @141-143
- function_item cmp @150-152
- function_item fmt @208-210
- function_item fmt @214-216

### third_party/rust/font-types/src/serde_test.rs

Blob: `926946a27ef06174fe81f9977d98031550c53d8e`. Grammar: rust. Status: syntax-clean.

- function_item test_serde @6-39
- struct_item MyTypes @8-20

### third_party/rust/font-types/src/tag.rs

Blob: `8b88289457b5e1c73166599f42bd789ce47d7d24`. Grammar: rust. Status: syntax-clean.

- struct_item Tag @23-23
- function_item new @30-32
- function_item new_checked @43-68
- function_item from_u32 @74-76
- function_item from_be_bytes @85-87
- function_item to_be_bytes @91-93
- function_item into_bytes @96-98
- function_item validate @112-128
- enum_item InvalidTag @137-145
- function_item from_str @150-152
- function_item to_raw @158-160
- function_item from_raw @162-164
- function_item borrow @171-173
- function_item eq @177-179
- function_item eq @183-185
- function_item eq @189-191
- function_item eq @195-197
- function_item as_ref @201-203
- function_item fmt @207-216
- function_item fmt @220-228
- function_item fmt @232-234
- function_item default @239-241
- function_item serialize @251-262
- function_item deserialize @267-290
- struct_item TagStrVisitor @271-271
- function_item expecting @275-277
- function_item visit_str @278-283
- mod_item tests @294-341
- function_item smoke_test @298-316
- function_item validate_test @319-333
- function_item display @337-340
- mod_item serde_tests @344-382
- struct_item TestMe @348-350
- function_item serde_json_good @353-363
- function_item serde_json_bad @367-373
- function_item deser_json_owned @377-381

### third_party/rust/font-types/src/uint24.rs

Blob: `710da41718f8f7988b75f71a0a5648ebd3410e7f`. Grammar: rust. Status: syntax-clean.

- struct_item Uint24 @6-6
- function_item new @16-20
- function_item checked_new @23-29
- function_item to_u32 @32-34
- function_item to_be_bytes @36-39
- function_item from_be_bytes @41-43
- function_item from @47-49
- function_item from @53-55
- struct_item TryFromUint24Error @60-60
- function_item fmt @63-65
- function_item try_from @74-77
- function_item fmt @81-83
- mod_item tests @87-102
- function_item constructor @91-94
- function_item be_bytes @97-101

### third_party/rust/font-types/src/version.rs

Blob: `a0218597ebde4a4306cb27b9fdfb910fc9c91d94`. Grammar: rust. Status: syntax-clean.

- struct_item Version16Dot16 @12-12
- struct_item MajorMinor @26-31
- trait_item Compatible @34-40
- function_signature_item compatible @39-39
- function_item new @63-67
- function_item to_major_minor @70-74
- function_item to_be_bytes @78-80
- function_item new @99-101
- function_item to_be_bytes @105-109
- function_item from_raw @115-119
- function_item to_raw @121-123
- function_item compatible @128-132
- function_item compatible @136-138
- function_item compatible @143-145
- function_item compatible @149-151
- function_item compatible @156-158
- function_item fmt @162-164
- function_item fmt @168-171
- function_item fmt @175-178
- mod_item tests @182-197
- function_item version_smoke_test @185-190
- function_item minor_version_out_of_range_test @194-196

### third_party/rust/foreign-types-macros/src/build.rs

Blob: `b50610f0f32b6252146559b13597ebbd7046838f`. Grammar: rust. Status: syntax-clean.

- function_item ref_name @7-9
- function_item build @11-19
- function_item build_foreign_type @21-43
- function_item build_decls @45-69
- function_item build_oibits @71-77
- function_item build_oibit @79-88
- function_item build_foreign_impls @90-121
- function_item build_drop_impl @123-138
- function_item build_deref_impls @140-166
- function_item build_borrow_impls @168-188
- function_item build_as_ref_impls @190-210
- function_item build_clone_impl @212-231
- function_item build_to_owned_impl @234-256
- function_item build_to_owned_impl @259-261

### third_party/rust/foreign-types-macros/src/lib.rs

Blob: `77c1e99fbcae1003a4af3bd4499ea8b5d6b3e224`. Grammar: rust. Status: syntax-clean.

- mod_item build @8-8
- mod_item parse @9-9
- function_item foreign_type_impl @12-15

### third_party/rust/foreign-types-macros/src/parse.rs

Blob: `ba11dc976c41176adba7b6960049b100914e0a0c`. Grammar: rust. Status: syntax-clean.

- mod_item kw @6-13
- struct_item Input @15-18
- function_item parse @21-29
- struct_item ForeignType @32-42
- function_item parse @45-71
- function_item parse_oibit @74-81
- function_item parse_oibits @83-100
- function_item parse_type @102-112
- function_item parse_phantom_data @114-120
- function_item parse_fn @122-132
- function_item parse_clone @134-140

### third_party/rust/foreign-types-shared/src/lib.rs

Blob: `2f58b53f18a4af6ac65fe9ef5f517aa92d96c988`. Grammar: rust. Status: syntax-clean.

- struct_item Opaque @14-14
- trait_item ForeignType @27-51
- function_signature_item from_ptr @39-39
- function_signature_item as_ptr @42-42
- function_item into_ptr @46-50
- trait_item ForeignTypeRef @61-92
- function_item from_ptr @71-74
- function_item from_ptr_mut @82-85
- function_item as_ptr @89-91

### third_party/rust/foreign-types/src/lib.rs

Blob: `00b3db950b2a943459843a3de673e051c3dc0c2b`. Grammar: rust. Status: syntax-clean.

- mod_item export @206-216

### third_party/rust/foreign-types/tests/test.rs

Blob: `a1df67e7a1de7693a4848ec7e775b2ad071a80b6`. Grammar: rust. Status: syntax-clean.

- mod_item foo_sys @3-8
- enum_item FOO @4-4
- function_item foo_drop @6-6
- function_item foo_clone @7-7

### third_party/rust/form_urlencoded/src/lib.rs

Blob: `639545ae675ed9cd9d97834b9493d8d61b6abf8f`. Grammar: rust. Status: syntax-clean.

- function_item parse @39-41
- struct_item Parse @44-46
- function_item next @51-67
- function_item decode @70-76
- function_item replace_plus @79-93
- function_item into_owned @97-99
- struct_item ParseIntoOwned @103-105
- function_item next @110-114
- function_item byte_serialize @121-123
- struct_item ByteSerialize @127-129
- function_item byte_serialized_unchanged @131-133
- function_item next @138-163
- function_item size_hint @165-171
- struct_item Serializer @176-180
- trait_item Target @182-186
- function_signature_item as_mut_string @183-183
- function_signature_item finish @184-184
- function_item as_mut_string @189-191
- function_item finish @192-194
- function_item as_mut_string @199-201
- function_item finish @202-204
- function_item new @213-215
- function_item for_suffix @222-236
- function_item clear @241-244
- function_item encoding_override @247-250
- function_item append_pair @255-264
- function_item append_key_only @269-277
- function_item extend_pairs @286-307
- function_item extend_keys_only @316-330
- function_item finish @344-349
- function_item append_separator_if_needed @352-356
- function_item string @358-363
- function_item append_pair @365-376
- function_item append_key_only @378-386
- function_item append_encoded @388-390
- function_item encode @392-397
- function_item decode_utf8_lossy @402-428

### third_party/rust/fragile/examples/basic-fragile.rs

Blob: `54e33fd9fc334bbc9e2ec9d399e556f2770362a9`. Grammar: rust. Status: syntax-clean.

- function_item main @5-18

### third_party/rust/fragile/examples/basic-sticky.rs

Blob: `e982b1de83581e8764b555683e321c1eecd5c9dc`. Grammar: rust. Status: syntax-clean.

- function_item main @5-21

### third_party/rust/fragile/src/errors.rs

Blob: `bf3fb4c9ff5784e00635837e86dada2bf5f69623`. Grammar: rust. Status: syntax-clean.

- struct_item InvalidThreadAccess @6-6
- function_item fmt @9-11

### third_party/rust/fragile/src/fragile.rs

Blob: `7ae2c8b406cb5eb58d2a284406b1a9486aeeb77d`. Grammar: rust. Status: syntax-clean.

- struct_item Fragile @19-24
- function_item new @33-38
- function_item is_valid @43-45
- function_item assert_thread @48-52
- function_item into_inner @60-68
- function_item try_into_inner @75-81
- function_item get @89-92
- function_item get_mut @100-103
- function_item try_get @108-114
- function_item try_get_mut @119-125
- function_item drop @129-138
- function_item from @143-145
- function_item clone @150-152
- function_item default @157-159
- function_item eq @164-166
- function_item partial_cmp @173-175
- function_item lt @178-180
- function_item le @183-185
- function_item gt @188-190
- function_item ge @193-195
- function_item cmp @200-202
- function_item fmt @206-208
- function_item fmt @212-228
- struct_item InvalidPlaceholder @216-216
- function_item fmt @218-220
- function_item test_basic @241-252
- function_item test_mut @255-260
- function_item test_access_other_thread @264-272
- function_item test_noop_drop_elsewhere @275-284
- function_item test_panic_on_drop_elsewhere @287-305
- struct_item X @292-292
- function_item drop @294-296
- function_item test_rc_sending @308-326

### third_party/rust/fragile/src/lib.rs

Blob: `16edc9d9121c61a494da09eabe385bca08573798`. Grammar: rust. Status: syntax-clean.

- mod_item errors @99-99
- mod_item fragile @100-100
- mod_item registry @101-101
- mod_item semisticky @102-102
- mod_item sticky @103-103
- mod_item thread_id @104-104
- struct_item StackToken @117-117
- function_item __private_new @122-126

### third_party/rust/fragile/src/registry.rs

Blob: `6bafb9be004a97b05df4d3607e99d16fa726a4d2`. Grammar: rust. Status: syntax-clean.

- struct_item Entry @1-8
- mod_item slab_impl @11-33
- struct_item Registry @16-16
- function_item insert @22-24
- function_item with @26-28
- function_item try_remove @30-32
- mod_item map_impl @36-68
- struct_item Registry @43-43
- function_item next_item_id @49-53
- function_item insert @55-59
- function_item with @61-63
- function_item try_remove @65-67
- function_item drop @77-83

### third_party/rust/fragile/src/semisticky.rs

Blob: `de6b1e7cd0ce828da111794e26a80126d2c2948e`. Grammar: rust. Status: syntax-clean.

- enum_item SemiStickyImpl @10-13
- struct_item SemiSticky @23-25
- function_item new @36-44
- function_item is_valid @49-54
- function_item into_inner @62-67
- function_item try_into_inner @74-83
- function_item get @91-96
- function_item get_mut @104-109
- function_item try_get @114-122
- function_item try_get_mut @127-135
- function_item from @140-142
- function_item clone @147-150
- function_item default @155-157
- function_item eq @162-165
- function_item partial_cmp @172-175
- function_item lt @178-181
- function_item le @184-187
- function_item gt @190-193
- function_item ge @196-199
- function_item cmp @204-207
- function_item fmt @211-214
- function_item fmt @218-235
- struct_item InvalidPlaceholder @223-223
- function_item fmt @225-227
- function_item test_basic @239-252
- function_item test_mut @255-261
- function_item test_access_other_thread @265-274
- function_item test_drop_same_thread @277-290
- struct_item X @281-281
- function_item drop @283-285
- function_item test_noop_drop_elsewhere @293-326
- struct_item X @303-303
- function_item drop @305-307
- function_item test_rc_sending @329-339

### third_party/rust/fragile/src/sticky.rs

Blob: `707ca2148abbae2d4951ff870610cc3896f2a7ab`. Grammar: rust. Status: syntax-clean.

- struct_item Sticky @30-34
- function_item drop @37-48
- function_item new @58-77
- function_item with_value @80-84
- function_item is_valid @90-92
- function_item assert_thread @95-99
- function_item into_inner @107-114
- function_item unsafe_take_value @116-119
- function_item try_into_inner @126-132
- function_item get @140-142
- function_item get_mut @150-152
- function_item try_get @157-166
- function_item try_get_mut @171-180
- function_item from @185-187
- function_item clone @192-195
- function_item default @200-202
- function_item eq @207-210
- function_item partial_cmp @217-220
- function_item lt @223-226
- function_item le @229-232
- function_item gt @235-238
- function_item ge @241-244
- function_item cmp @249-252
- function_item fmt @256-259
- function_item fmt @263-280
- struct_item InvalidPlaceholder @268-268
- function_item fmt @270-272
- function_item test_basic @291-304
- function_item test_mut @307-313
- function_item test_access_other_thread @317-326
- function_item test_drop_same_thread @329-342
- struct_item X @333-333
- function_item drop @335-337
- function_item test_noop_drop_elsewhere @345-378
- struct_item X @355-355
- function_item drop @357-359
- function_item test_rc_sending @381-391
- function_item test_two_stickies @394-410
- struct_item Wat @395-395
- function_item drop @398-400
- function_item test_thread_spawn @413-426

### third_party/rust/fragile/src/thread_id.rs

Blob: `dd67632248918c019e0f2e561dcc6572f9abe2a7`. Grammar: rust. Status: syntax-clean.

- function_item next @4-8
- function_item get @10-13

### third_party/rust/framehop/src/aarch64/arch.rs

Blob: `910d85851d69eef7aa28709fcbaafaf7e394d233`. Grammar: rust. Status: syntax-clean.

- struct_item ArchAarch64 @6-6

### third_party/rust/framehop/src/aarch64/cache.rs

Blob: `4b207eacbcc318e33c32b3c574379c8fc68ddbd7`. Grammar: rust. Status: syntax-clean.

- struct_item CacheAarch64 @5-7
- function_item new @11-13
- function_item new_in @18-20
- function_item stats @23-25
- function_item default @29-31

### third_party/rust/framehop/src/aarch64/dwarf.rs

Blob: `c3ea10aa0fb3a8e884c9321a6f9b5bfda7a50244`. Grammar: rust. Status: syntax-clean.

- function_item get @16-23
- function_item unwind_frame @27-93
- function_item rule_if_uncovered_by_fde @95-97
- function_item register_rule_to_cfa_offset @100-108
- function_item translate_into_unwind_rule @110-195

### third_party/rust/framehop/src/aarch64/instruction_analysis/epilogue.rs

Blob: `b9a82f27f4fce97707f3ad13aa08329e83fb87b8`. Grammar: rust. Status: syntax-clean.

- struct_item EpilogueDetectorAarch64 @3-7
- enum_item EpilogueStepResult @9-15
- enum_item EpilogueResult @18-26
- enum_item UnexpectedInstructionType @29-36
- enum_item EpilogueInstructionType @39-52
- function_item new @55-61
- function_item analyze_slice @63-153
- function_item instruction_adjusts_stack_pointer @155-168
- function_item is_auth_tail_call @170-236
- function_item analyze_instruction @238-312
- function_item step_instruction @314-397
- function_item unwind_rule_from_detected_epilogue @400-433
- mod_item test @436-702
- function_item test_epilogue_1 @440-476
- function_item test_epilogue_with_retab @479-521
- function_item test_epilogue_with_retab_2 @524-553
- function_item test_epilogue_with_regular_tail_call @556-567
- function_item test_epilogue_with_register_tail_call @571-587
- function_item test_epilogue_with_auth_tail_call @590-646
- function_item test_epilogue_with_auth_tail_call_2 @649-701

### third_party/rust/framehop/src/aarch64/instruction_analysis/mod.rs

Blob: `2e006fc0057b8341a7544968b918aded4e5f962f`. Grammar: rust. Status: syntax-clean.

- mod_item epilogue @4-4
- mod_item prologue @5-5
- function_item rule_from_prologue_analysis @11-17
- function_item rule_from_epilogue_analysis @19-24

### third_party/rust/framehop/src/aarch64/instruction_analysis/prologue.rs

Blob: `0e5d4cbf639f5068cf0c038f9959d980a7223b42`. Grammar: rust. Status: syntax-clean.

- struct_item PrologueDetectorAarch64 @3-5
- enum_item PrologueStepResult @8-11
- enum_item PrologueResult @14-17
- enum_item PrologueInstructionType @20-24
- enum_item UnexpectedInstructionType @27-34
- function_item new @37-39
- function_item analyze_slices @41-104
- function_item analyze_prologue_instruction_type @107-148
- function_item reverse_step_instruction @151-202
- function_item unwind_rule_from_detected_prologue @205-222
- mod_item test @225-400
- function_item test_prologue_1 @229-275
- function_item test_prologue_with_pacibsp @278-332
- function_item test_prologue_with_mov_fp_sp @335-362
- function_item test_no_prologue_despite_stack_store @365-399

### third_party/rust/framehop/src/aarch64/macho.rs

Blob: `84deb80ae25c409abf9281c1055549462a6052cd`. Grammar: rust. Status: syntax-clean.

- function_item unwind_frame @9-64
- function_item rule_for_stub_helper @66-95

### third_party/rust/framehop/src/aarch64/mod.rs

Blob: `470f814b4ce8f3bc1919d675c475062ea50e5702`. Grammar: rust. Status: syntax-clean.

- mod_item arch @1-1
- mod_item cache @2-2
- mod_item dwarf @3-3
- mod_item instruction_analysis @4-4
- mod_item macho @6-6
- mod_item pe @8-8
- mod_item unwind_rule @9-9
- mod_item unwinder @10-10
- mod_item unwindregs @11-11

### third_party/rust/framehop/src/aarch64/pe.rs

Blob: `8f9245152515f00255bbabe5d5fd4c855b69badf`. Grammar: rust. Status: syntax-clean.

- function_item unwind_frame @6-18

### third_party/rust/framehop/src/aarch64/unwind_rule.rs

Blob: `0310258686b3f5533e1d44776bcc67a24ef584ce`. Grammar: rust. Status: syntax-clean.

- enum_item UnwindRuleAarch64 @8-46
- function_item rule_for_stub_functions @51-53
- function_item rule_for_function_start @54-56
- function_item fallback_rule @57-59
- function_item exec @61-236
- mod_item test @240-264
- function_item test_basic @244-263

### third_party/rust/framehop/src/aarch64/unwinder.rs

Blob: `e8fafb6808aed39e8fc8fb04727a9a5ba9e74f18`. Grammar: rust. Status: syntax-clean.

- struct_item UnwinderAarch64 @16-16
- function_item default @19-21
- function_item clone @25-27
- function_item new @32-34
- function_item add_module @42-44
- function_item remove_module @46-48
- function_item max_known_code_address @50-52
- function_item unwind_frame @54-65

### third_party/rust/framehop/src/aarch64/unwindregs.rs

Blob: `3d0c11d03a488931c14542b3697cadee3946f3ce`. Grammar: rust. Status: syntax-clean.

- struct_item UnwindRegsAarch64 @12-17
- struct_item PtrAuthMask @35-35
- function_item new_no_strip @40-42
- function_item new_24_40 @51-53
- function_item from_max_known_address @57-59
- function_item strip_ptr_auth @63-65
- function_item new @71-78
- function_item new_with_ptr_auth_mask @82-94
- function_item lr_mask @98-100
- function_item sp @104-106
- function_item set_sp @110-112
- function_item fp @116-118
- function_item set_fp @122-124
- function_item lr @128-130
- function_item set_lr @134-136
- function_item fmt @140-146
- mod_item test @150-182
- function_item test @154-181

### third_party/rust/framehop/src/add_signed.rs

Blob: `9e924d7bbb7a7ad3ea57583d571e151a94cb7d57`. Grammar: rust. Status: syntax-clean.

- function_item wrapping_add_signed @3-5
- function_item checked_add_signed @9-11
- trait_item AddSigned @19-28
- function_signature_item wrapping_add_signed @23-23
- function_signature_item checked_add_signed @27-27
- function_item wrapping_add_signed @33-35
- function_item checked_add_signed @37-44
- function_item wrapping_add_signed @50-52
- function_item checked_add_signed @54-61
- mod_item test @65-99
- function_item test_wrapping @69-82
- function_item test_checked @85-98

### third_party/rust/framehop/src/arch.rs

Blob: `b08c3fd316707eaeb43ed1c76a41f933987f0c3a`. Grammar: rust. Status: syntax-clean.

- trait_item Arch @3-6

### third_party/rust/framehop/src/cache.rs

Blob: `1c7a61f6e102c37323099a3286ffc24cfed553d3`. Grammar: rust. Status: syntax-clean.

- trait_item AllocationPolicy @9-12
- struct_item MustNotAllocateDuringUnwind @21-21
- struct_item StoreOnStack @26-26
- struct_item MayAllocateDuringUnwind @49-49
- struct_item Cache @62-66
- function_item new @69-74
- function_item default @78-80

### third_party/rust/framehop/src/code_address.rs

Blob: `892823608d7e10ce415bb296203ece13de64171e`. Grammar: rust. Status: syntax-clean.

- enum_item FrameAddress @9-20
- function_item from_instruction_pointer @24-26
- function_item from_return_address @30-34
- function_item address @37-42
- function_item address_for_lookup @61-66
- function_item is_return_address @69-74

### third_party/rust/framehop/src/display_utils.rs

Blob: `ccd5004ee3ad1b782072d803c48aa1790109c553`. Grammar: rust. Status: syntax-clean.

- struct_item HexNum @3-3
- function_item fmt @6-8
- struct_item BinNum @11-11
- function_item fmt @14-16

### third_party/rust/framehop/src/dwarf.rs

Blob: `be563dd39be579a9fa7cd21c0ad6f2af3a6a16cf`. Grammar: rust. Status: syntax-clean.

- enum_item DwarfUnwinderError @16-24
- function_item fmt @27-42
- function_item source @47-53
- enum_item ConversionError @57-72
- trait_item DwarfUnwinding @74-90
- function_signature_item unwind_frame @75-87
- function_signature_item rule_if_uncovered_by_fde @89-89
- enum_item UnwindSectionType @92-95
- struct_item DwarfUnwinder @97-110
- function_item new @118-142
- function_item get_fde_offset_for_relative_address @144-151
- function_item unwind_frame_with_fde @153-203
- function_item unwind_info_for_fde @205-227
- function_item base_addresses_for_sections @230-245
- enum_item DwarfCfiIndexError @248-253
- function_item fmt @256-265
- function_item from @269-271
- function_item source @276-281
- struct_item DwarfCfiIndex @286-294
- function_item try_new @297-351
- function_item try_new_eh_frame @353-362
- function_item try_new_debug_frame @364-373
- function_item fde_offset_for_relative_address @375-382
- trait_item DwarfUnwindRegs @385-387
- function_signature_item get @386-386
- function_item eval_cfa_rule @389-405
- function_item eval_expr @407-430
- function_item eval_register_rule @432-475

### third_party/rust/framehop/src/error.rs

Blob: `df58947e680d600bd82616cbdb0e11dff1beae8d`. Grammar: rust. Status: syntax-clean.

- enum_item Error @9-15
- function_item fmt @18-31
- enum_item UnwinderError @38-49
- function_item fmt @52-78
- function_item from @82-84
- function_item from @89-91
- function_item from @96-101
- function_item source @106-115

### third_party/rust/framehop/src/instruction_analysis.rs

Blob: `47c0eeac31430d0d2f590a2f937828ae1f9f7148`. Grammar: rust. Status: syntax-clean.

- trait_item InstructionAnalysis @3-20
- function_signature_item rule_from_prologue_analysis @5-6
- function_signature_item rule_from_epilogue_analysis @9-10
- function_item rule_from_instruction_analysis @13-19

### third_party/rust/framehop/src/lib.rs

Blob: `737235c071570d52fb3f66ddffbae74ea1bef144`. Grammar: rust. Status: syntax-clean.

- mod_item add_signed @118-118
- mod_item arch @119-119
- mod_item cache @120-120
- mod_item code_address @121-121
- mod_item display_utils @122-122
- mod_item dwarf @123-123
- mod_item error @124-124
- mod_item instruction_analysis @125-125
- mod_item macho @127-127
- mod_item pe @129-129
- mod_item rule_cache @130-130
- mod_item unwind_result @131-131
- mod_item unwind_rule @132-132
- mod_item unwinder @133-133
- mod_item aarch64 @136-136
- mod_item x86_64 @138-138

### third_party/rust/framehop/src/macho.rs

Blob: `ef60c6e193c011dd1d7ee484f16b397300ead7b2`. Grammar: rust. Status: syntax-clean.

- enum_item CompactUnwindInfoUnwinderError @8-22
- function_item fmt @25-41
- function_item from @45-47
- function_item from @51-53
- function_item source @58-64
- enum_item CuiUnwindResult @68-71
- trait_item CompactUnwindInfoUnwinding @73-84
- function_signature_item unwind_frame @74-79
- function_signature_item rule_for_stub_helper @81-83
- struct_item TextBytes @87-90
- function_item new @93-98
- struct_item CompactUnwindInfoUnwinder @101-107
- function_item new @110-123
- function_item function_for_address @125-135
- function_item unwind_frame @137-205

### third_party/rust/framehop/src/pe.rs

Blob: `bba6cf19c582979070f4ff13db7f5a0083947dab`. Grammar: rust. Status: syntax-clean.

- enum_item PeUnwinderError @5-11
- function_item fmt @14-32
- struct_item DataAtRvaRange @47-50
- struct_item PeSections @52-57
- function_item unwind_info_memory_at_rva @63-68
- function_item text_memory_at_rva @70-74
- function_item memory_at_rva @77-87
- trait_item PeUnwinding @89-100
- function_signature_item unwind_frame @90-99

### third_party/rust/framehop/src/rule_cache.rs

Blob: `4aeb507c0cca5476af5296f22ddb7811fd02f326`. Grammar: rust. Status: syntax-clean.

- struct_item RuleCache @7-10
- function_item new @13-18
- function_item lookup @20-44
- function_item insert @46-57
- function_item stats @60-62
- enum_item CacheResult @65-68
- struct_item CacheHandle @70-74
- struct_item CacheEntry @82-86
- struct_item CacheStats @90-104
- function_item new @108-110
- function_item total @113-115
- function_item hits @118-120
- function_item misses @123-125
- mod_item tests @129-146
- function_item test_cache_entry_size @136-145

### third_party/rust/framehop/src/unwind_result.rs

Blob: `57f6aae7093384f0e9d0617ea4c96447de6efbf8`. Grammar: rust. Status: syntax-clean.

- enum_item UnwindResult @2-5

### third_party/rust/framehop/src/unwind_rule.rs

Blob: `f2c2e159f8a3e184bf24e400c418747c48c61008`. Grammar: rust. Status: syntax-clean.

- trait_item UnwindRule @3-18
- function_signature_item exec @6-13
- function_signature_item rule_for_stub_functions @15-15
- function_signature_item rule_for_function_start @16-16
- function_signature_item fallback_rule @17-17

### third_party/rust/framehop/src/unwinder.rs

Blob: `c17b71a1b1cb8cc1348443be5197544cc8113501`. Grammar: rust. Status: syntax-clean.

- trait_item Unwinder @30-88
- function_signature_item add_module @48-48
- function_signature_item remove_module @53-53
- function_signature_item max_known_code_address @61-61
- function_signature_item unwind_frame @65-73
- function_item iter_frames @76-87
- struct_item UnwindIterator @108-114
- enum_item UnwindIteratorState @116-120
- function_item new @124-138
- function_item next @151-175
- function_item next @184-186
- function_item next_global_modules_generation @197-199
- struct_item UnwinderInternal @221-228
- function_item default @231-233
- function_item clone @237-244
- function_item new @248-255
- function_item add_module @259-269
- function_item remove_module @271-281
- function_item max_known_code_address @283-285
- function_item find_module_for_address @287-313
- function_item with_cache @315-371
- function_item unwind_frame @373-384
- function_item unwind_frame_impl @386-555
- enum_item ModuleUnwindDataInternal @570-617
- function_item new @620-712
- struct_item TextByteData @733-736
- struct_item Module @751-764
- function_item clone @767-775
- trait_item ModuleSectionInfo @789-813
- function_signature_item base_svma @796-796
- function_signature_item section_svma_range @799-799
- function_signature_item section_data @802-802
- function_item segment_svma_range @805-807
- function_item segment_data @810-812
- struct_item ExplicitModuleSectionInfo @827-883
- function_item base_svma @889-891
- function_item section_svma_range @893-903
- function_item section_data @904-913
- function_item segment_svma_range @914-919
- function_item segment_data @920-925
- function_item new @929-944
- function_item avma_range @946-948
- function_item base_avma @950-952
- function_item name @954-956

### third_party/rust/framehop/src/x86_64/arch.rs

Blob: `3a1e7cc62446fca7a9f01b76ac2b2608e9f9a8d3`. Grammar: rust. Status: syntax-clean.

- struct_item ArchX86_64 @6-6

### third_party/rust/framehop/src/x86_64/cache.rs

Blob: `fa3abdfbe5fbe489d1c3691df0daab6a4d5e835c`. Grammar: rust. Status: syntax-clean.

- struct_item CacheX86_64 @5-7
- function_item new @11-13
- function_item new_in @18-20
- function_item stats @23-25
- function_item default @29-31

### third_party/rust/framehop/src/x86_64/dwarf.rs

Blob: `12fd80ad5495fbe5f5c6a24a9dff5acccb223050`. Grammar: rust. Status: syntax-clean.

- function_item get @14-21
- function_item unwind_frame @25-84
- function_item rule_if_uncovered_by_fde @86-88
- function_item register_rule_to_cfa_offset @91-99
- function_item translate_into_unwind_rule @101-164

### third_party/rust/framehop/src/x86_64/instruction_analysis/epilogue.rs

Blob: `13c8640ce0a4d4640922eabfbe419983b5f5d781`. Grammar: rust. Status: syntax-clean.

- function_item unwind_rule_from_detected_epilogue @3-85

### third_party/rust/framehop/src/x86_64/instruction_analysis/mod.rs

Blob: `146f6603cc8d4bdb483c6b3fe9dc3e403dab88a8`. Grammar: rust. Status: syntax-clean.

- mod_item epilogue @4-4
- mod_item prologue @5-5
- function_item rule_from_prologue_analysis @11-16
- function_item rule_from_epilogue_analysis @18-23

### third_party/rust/framehop/src/x86_64/instruction_analysis/prologue.rs

Blob: `25abeb5c0474be1f5276de2a85641a31bf2ac9de`. Grammar: rust. Status: syntax-clean.

- function_item unwind_rule_from_detected_prologue @3-45
- function_item is_next_instruction_expected_in_prologue @47-82

### third_party/rust/framehop/src/x86_64/macho.rs

Blob: `199aabf6b1863c1772bdfc30b152adb6b79af3a3`. Grammar: rust. Status: syntax-clean.

- function_item unwind_frame @9-136
- function_item rule_for_stub_helper @138-170

### third_party/rust/framehop/src/x86_64/mod.rs

Blob: `aa0ad6e7da0ee1f6686a4b040011a708c8c6275b`. Grammar: rust. Status: syntax-clean.

- mod_item arch @1-1
- mod_item cache @2-2
- mod_item dwarf @3-3
- mod_item instruction_analysis @4-4
- mod_item macho @6-6
- mod_item pe @8-8
- mod_item register_ordering @9-9
- mod_item unwind_rule @10-10
- mod_item unwinder @11-11
- mod_item unwindregs @12-12

### third_party/rust/framehop/src/x86_64/pe.rs

Blob: `2178b4598ef206a66d3ac0e3465e3ed0f1a24c1c`. Grammar: rust. Status: syntax-clean.

- struct_item State @17-20
- function_item read_register @26-28
- function_item read_stack @30-32
- function_item write_register @34-36
- function_item write_xmm_register @38-40
- function_item convert_pe_register @43-62
- function_item from @65-77
- function_item from @81-93
- function_item unwind_frame @97-223

### third_party/rust/framehop/src/x86_64/register_ordering.rs

Blob: `d76733073b3ae3b08dce84adaa3a3428fc36afbb`. Grammar: rust. Status: syntax-clean.

- function_item decode @15-29
- function_item encode @31-50
- mod_item test @53-84
- function_item unhandled_orderings @57-62
- function_item roundtrip_all @65-83

### third_party/rust/framehop/src/x86_64/unwind_rule.rs

Blob: `1c927190ac8f699eca273b05c08e84aad9ff3a28`. Grammar: rust. Status: syntax-clean.

- enum_item UnwindRuleX86_64 @10-42
- enum_item OffsetOrPop @44-48
- function_item for_sequence_of_offset_or_pop @52-86
- function_item rule_for_stub_functions @92-94
- function_item rule_for_function_start @95-97
- function_item fallback_rule @98-100
- function_item exec @102-251
- mod_item test @255-309
- function_item test_basic @259-283
- function_item test_overflow @286-308

### third_party/rust/framehop/src/x86_64/unwinder.rs

Blob: `bb98d6037638ea14a03404eaec066bece8cc344f`. Grammar: rust. Status: syntax-clean.

- struct_item UnwinderX86_64 @18-18
- function_item default @21-23
- function_item clone @27-29
- function_item new @34-36
- function_item add_module @44-46
- function_item remove_module @48-50
- function_item max_known_code_address @52-54
- function_item unwind_frame @56-67

### third_party/rust/framehop/src/x86_64/unwindregs.rs

Blob: `77319ff741762da715522e9fcd37323610567220`. Grammar: rust. Status: syntax-clean.

- struct_item UnwindRegsX86_64 @6-9
- enum_item Reg @13-30
- function_item new @33-41
- function_item get @44-46
- function_item set @48-50
- function_item ip @53-55
- function_item set_ip @57-59
- function_item sp @62-64
- function_item set_sp @66-68
- function_item bp @71-73
- function_item set_bp @75-77
- function_item fmt @81-101

### third_party/rust/freetype/etc/bindings.h

Blob: `34c894bf0df643ac547e2ded022ba02124b72cc0`. Grammar: cpp. Status: syntax-clean.

- include <freetype2/ft2build.h> @1
- include <freetype2/freetype/freetype.h> @2
- include <freetype2/freetype/ftlcdfil.h> @3
- include <freetype2/freetype/tttables.h> @4
- include <freetype2/freetype/ftmodapi.h> @5
- include <freetype2/freetype/ftoutln.h> @6

### third_party/rust/freetype/src/freetype.rs

Blob: `ccf8a2b5fa072db1b1332a6d62b56a23f0c7fb79`. Grammar: rust. Status: syntax-clean.

- struct_item __BindgenUnionField @12-12
- function_item new @15-15
- function_item as_ref @17-17
- function_item as_mut @19-19
- function_item default @23-23
- function_item clone @27-27
- function_item fmt @31-33
- struct_item FT_MemoryRec_ @129-134
- function_item bindgen_test_layout_FT_MemoryRec_ @136-161
- function_item clone @163-163
- struct_item FT_StreamRec_ @185-196
- function_item bindgen_test_layout_FT_StreamRec_ @198-253
- function_item clone @255-255
- struct_item FT_StreamDesc_ @260-264
- function_item bindgen_test_layout_FT_StreamDesc_ @266-281
- function_item clone @283-283
- struct_item FT_Vector_ @300-303
- function_item bindgen_test_layout_FT_Vector_ @305-320
- function_item clone @322-322
- struct_item FT_BBox_ @327-332
- function_item bindgen_test_layout_FT_BBox_ @334-359
- function_item clone @361-361
- enum_item FT_Pixel_Mode_ @366-376
- struct_item FT_Bitmap_ @380-389
- function_item bindgen_test_layout_FT_Bitmap_ @391-436
- function_item clone @438-438
- struct_item FT_Outline_ @443-450
- function_item bindgen_test_layout_FT_Outline_ @452-487
- function_item clone @489-489
- struct_item FT_Outline_Funcs_ @517-524
- function_item bindgen_test_layout_FT_Outline_Funcs_ @526-561
- function_item clone @563-563
- enum_item FT_Glyph_Format_ @568-574
- struct_item FT_RasterRec_ @578-580
- struct_item FT_Span_ @584-588
- function_item bindgen_test_layout_FT_Span_ @590-610
- function_item clone @612-612
- struct_item FT_Raster_Params_ @634-644
- function_item bindgen_test_layout_FT_Raster_Params_ @646-696
- function_item clone @698-698
- struct_item FT_Raster_Funcs_ @727-734
- function_item bindgen_test_layout_FT_Raster_Funcs_ @736-771
- function_item clone @773-773
- struct_item FT_UnitVector_ @798-801
- function_item bindgen_test_layout_FT_UnitVector_ @803-818
- function_item clone @820-820
- struct_item FT_Matrix_ @825-830
- function_item bindgen_test_layout_FT_Matrix_ @832-857
- function_item clone @859-859
- struct_item FT_Data_ @864-867
- function_item bindgen_test_layout_FT_Data_ @869-884
- function_item clone @886-886
- struct_item FT_Generic_ @894-897
- function_item bindgen_test_layout_FT_Generic_ @899-914
- function_item clone @916-916
- struct_item FT_ListNodeRec_ @921-925
- function_item bindgen_test_layout_FT_ListNodeRec_ @927-947
- function_item clone @949-949
- struct_item FT_ListRec_ @954-957
- function_item bindgen_test_layout_FT_ListRec_ @959-974
- function_item clone @976-976
- enum_item _bindgen_ty_1 @1007-1007
- enum_item _bindgen_ty_2 @1191-1284
- struct_item FT_Glyph_Metrics_ @1287-1296
- function_item bindgen_test_layout_FT_Glyph_Metrics_ @1298-1343
- function_item clone @1345-1345
- struct_item FT_Bitmap_Size_ @1350-1356
- function_item bindgen_test_layout_FT_Bitmap_Size_ @1358-1388
- function_item clone @1390-1390
- struct_item FT_LibraryRec_ @1395-1397
- struct_item FT_ModuleRec_ @1401-1403
- struct_item FT_DriverRec_ @1407-1409
- struct_item FT_RendererRec_ @1413-1415
- struct_item FT_FaceRec_ @1419-1451
- function_item bindgen_test_layout_FT_FaceRec_ @1453-1613
- function_item clone @1615-1615
- struct_item FT_SizeRec_ @1620-1625
- function_item bindgen_test_layout_FT_SizeRec_ @1627-1652
- function_item clone @1654-1654
- struct_item FT_GlyphSlotRec_ @1659-1682
- function_item bindgen_test_layout_FT_GlyphSlotRec_ @1684-1799
- function_item clone @1801-1801
- struct_item FT_CharMapRec_ @1806-1811
- function_item bindgen_test_layout_FT_CharMapRec_ @1813-1838
- function_item clone @1840-1840
- enum_item FT_Encoding_ @1855-1870
- struct_item FT_Face_InternalRec_ @1875-1877
- struct_item FT_Size_InternalRec_ @1882-1884
- struct_item FT_Size_Metrics_ @1888-1897
- function_item bindgen_test_layout_FT_Size_Metrics_ @1899-1944
- function_item clone @1946-1946
- struct_item FT_SubGlyphRec_ @1952-1954
- struct_item FT_Slot_InternalRec_ @1958-1960
- function_signature_item FT_Init_FreeType @1964-1964
- function_signature_item FT_Done_FreeType @1967-1967
- struct_item FT_Parameter_ @1971-1974
- function_item bindgen_test_layout_FT_Parameter_ @1976-1991
- function_item clone @1993-1993
- struct_item FT_Open_Args_ @1998-2007
- function_item bindgen_test_layout_FT_Open_Args_ @2009-2054
- function_item clone @2056-2056
- function_signature_item FT_New_Face @2060-2062
- function_signature_item FT_New_Memory_Face @2065-2067
- function_signature_item FT_Open_Face @2070-2071
- function_signature_item FT_Attach_File @2074-2076
- function_signature_item FT_Attach_Stream @2079-2080
- function_signature_item FT_Reference_Face @2083-2083
- function_signature_item FT_Done_Face @2086-2086
- function_signature_item FT_Select_Size @2089-2089
- enum_item FT_Size_Request_Type_ @2093-2100
- struct_item FT_Size_RequestRec_ @2104-2110
- function_item bindgen_test_layout_FT_Size_RequestRec_ @2112-2143
- function_item clone @2145-2145
- function_signature_item FT_Request_Size @2150-2150
- function_signature_item FT_Set_Char_Size @2153-2155
- function_signature_item FT_Set_Pixel_Sizes @2158-2159
- function_signature_item FT_Load_Glyph @2162-2163
- function_signature_item FT_Load_Char @2166-2167
- function_signature_item FT_Set_Transform @2170-2171
- enum_item FT_Render_Mode_ @2175-2182
- function_signature_item FT_Render_Glyph @2185-2186
- enum_item FT_Kerning_Mode_ @2190-2194
- function_signature_item FT_Get_Kerning @2197-2199
- function_signature_item FT_Get_Track_Kerning @2202-2204
- function_signature_item FT_Get_Glyph_Name @2207-2209
- function_signature_item FT_Get_Postscript_Name @2212-2213
- function_signature_item FT_Select_Charmap @2216-2217
- function_signature_item FT_Set_Charmap @2220-2220
- function_signature_item FT_Get_Charmap_Index @2223-2223
- function_signature_item FT_Get_Char_Index @2226-2226
- function_signature_item FT_Get_First_Char @2229-2230
- function_signature_item FT_Get_Next_Char @2233-2234
- function_signature_item FT_Get_Name_Index @2237-2238
- function_signature_item FT_Get_SubGlyph_Info @2241-2244
- function_signature_item FT_Get_FSType_Flags @2247-2247
- function_signature_item FT_Face_GetCharVariantIndex @2250-2251
- function_signature_item FT_Face_GetCharVariantIsDefault @2254-2256
- function_signature_item FT_Face_GetVariantSelectors @2259-2259
- function_signature_item FT_Face_GetVariantsOfChar @2262-2263
- function_signature_item FT_Face_GetCharsOfVariant @2266-2267
- function_signature_item FT_MulDiv @2270-2270
- function_signature_item FT_MulFix @2273-2273
- function_signature_item FT_DivFix @2276-2276
- function_signature_item FT_RoundFix @2279-2279
- function_signature_item FT_CeilFix @2282-2282
- function_signature_item FT_FloorFix @2285-2285
- function_signature_item FT_Vector_Transform @2288-2288
- function_signature_item FT_Library_Version @2291-2292
- function_signature_item FT_Face_CheckTrueTypePatents @2295-2295
- function_signature_item FT_Face_SetUnpatentedHinting @2298-2299
- enum_item FT_LcdFilter_ @2303-2310
- function_signature_item FT_Library_SetLcdFilter @2313-2314
- function_signature_item FT_Library_SetLcdFilterWeights @2317-2320
- enum_item FT_Sfnt_Tag_ @2324-2333
- function_signature_item FT_Get_Sfnt_Table @2336-2337
- function_signature_item FT_Load_Sfnt_Table @2340-2342
- function_signature_item FT_Sfnt_Table_Info @2345-2347
- function_signature_item FT_Get_CMap_Language_ID @2350-2350
- function_signature_item FT_Get_CMap_Format @2353-2353
- struct_item FT_Module_Class_ @2368-2378
- function_item bindgen_test_layout_FT_Module_Class_ @2380-2430
- function_item clone @2432-2432
- function_signature_item FT_Add_Module @2436-2437
- function_signature_item FT_Get_Module @2440-2442
- function_signature_item FT_Remove_Module @2445-2446
- function_signature_item FT_Property_Set @2449-2451
- function_signature_item FT_Property_Get @2454-2456
- function_signature_item FT_Reference_Library @2459-2459
- function_signature_item FT_New_Library @2462-2463
- function_signature_item FT_Done_Library @2466-2466
- function_signature_item FT_Set_Debug_Hook @2472-2473
- function_signature_item FT_Add_Default_Modules @2476-2476
- enum_item FT_TrueTypeEngineType_ @2480-2484
- function_signature_item FT_Get_TrueType_Engine_Type @2487-2488
- function_signature_item FT_Outline_Decompose @2491-2494
- function_signature_item FT_Outline_New @2497-2499
- function_signature_item FT_Outline_New_Internal @2502-2504
- function_signature_item FT_Outline_Done @2507-2508
- function_signature_item FT_Outline_Done_Internal @2511-2512
- function_signature_item FT_Outline_Check @2515-2515
- function_signature_item FT_Outline_Get_CBox @2518-2519
- function_signature_item FT_Outline_Translate @2522-2523
- function_signature_item FT_Outline_Copy @2526-2527
- function_signature_item FT_Outline_Transform @2530-2531
- function_signature_item FT_Outline_Embolden @2534-2535
- function_signature_item FT_Outline_EmboldenXY @2538-2539
- function_signature_item FT_Outline_Reverse @2542-2542
- function_signature_item FT_Outline_Get_Bitmap @2545-2547
- function_signature_item FT_Outline_Render @2550-2551
- enum_item FT_Orientation_ @2559-2563
- function_signature_item FT_Outline_Get_Orientation @2566-2567

### third_party/rust/freetype/src/lib.rs

Blob: `39f65055cdfcf5cc076ed9b577b66b1a175d4c48`. Grammar: rust. Status: syntax-clean.

- function_item succeeded @26-28
- mod_item freetype @31-31
- mod_item tt_os2 @32-32

### third_party/rust/freetype/src/tt_os2.rs

Blob: `22784f99f376272fba7e684a80c95ff165fed0d2`. Grammar: rust. Status: syntax-clean.

- struct_item TT_OS2 @13-61

### third_party/rust/fs-err/build.rs

Blob: `59169ed8b81a1b048884540c6b39d54339701894`. Grammar: rust. Status: syntax-clean.

- function_item main @3-14

### third_party/rust/fs-err/src/dir.rs

Blob: `f89ab2aee1f237af073d3558b344cc9bd478fa49`. Grammar: rust. Status: syntax-clean.

- function_item read_dir @14-21
- struct_item ReadDir @28-31
- function_item next @36-43
- struct_item DirEntry @49-51
- function_item path @57-59
- function_item metadata @64-68
- function_item file_type @73-77
- function_item file_name @82-84
- mod_item unix @88-98
- function_item ino @94-96

### third_party/rust/fs-err/src/errors.rs

Blob: `f2861effd634dcffeee9bd0e09a94899f7569479`. Grammar: rust. Status: syntax-clean.

- enum_item ErrorKind @9-54
- struct_item Error @61-65
- function_item build @68-77
- function_item fmt @81-150
- function_item cause @154-156
- function_item source @159-161
- function_item source @164-166
- enum_item SourceDestErrorKind @170-183
- struct_item SourceDestError @187-192
- function_item build @195-210
- function_item fmt @214-265
- function_item path_facts_source_dest @269-278
- function_item async_path_facts @281-283
- function_item async_path_facts_source_dest @286-288
- function_item path_facts @291-298
- function_item cause @301-303
- function_item source @306-308
- function_item source @311-313

### third_party/rust/fs-err/src/file.rs

Blob: `7e59cbdf9d9812286dc5891434790461de279206`. Grammar: rust. Status: syntax-clean.

- struct_item File @18-21
- function_item open @27-29
- function_item create @32-34
- function_item open @41-50
- function_item create @55-64
- function_item create_new @69-84
- function_item options @89-91
- function_item sync_all @96-100
- function_item sync_data @108-112
- function_item set_len @117-121
- function_item metadata @126-130
- function_item try_clone @137-145
- function_item set_permissions @150-154
- function_item set_times @163-167
- function_item set_modified @172-176
- function_item lock @185-189
- function_item lock_shared @194-198
- function_item try_lock @203-205
- function_item try_lock_shared @210-212
- function_item unlock @217-221
- function_item from_parts @227-235
- function_item into_parts @238-240
- function_item into_file @243-245
- function_item into_path @248-250
- function_item file @253-255
- function_item file_mut @258-260
- function_item path @263-265
- function_item error @268-270
- function_item read @274-278
- function_item read_vectored @280-284
- function_item read @288-292
- function_item read_vectored @294-298
- function_item from @302-304
- function_item seek @308-312
- function_item seek @316-320
- function_item write @324-328
- function_item write_vectored @330-334
- function_item flush @336-340
- function_item write @344-348
- function_item write_vectored @350-354
- function_item flush @356-360
- mod_item unix @364-422
- function_item as_raw_fd @372-374
- function_item into_raw_fd @378-380
- function_item read_at @384-388
- function_item read_exact_at @389-393
- function_item write_at @394-398
- function_item write_all_at @399-403
- mod_item io_safety @407-421
- function_item as_fd @411-413
- function_item from @417-419
- mod_item windows @425-480
- function_item seek_read @435-439
- function_item seek_write @441-445
- function_item as_raw_handle @449-451
- function_item into_raw_handle @459-461
- mod_item io_safety @465-479
- function_item as_handle @469-471
- function_item from @475-477

### third_party/rust/fs-err/src/lib.rs

Blob: `e67509f1d714ada8cf625da9bcff3c11a957e221`. Grammar: rust. Status: syntax-clean.

- mod_item dir @112-112
- mod_item errors @113-113
- mod_item file @114-114
- mod_item open_options @115-115
- mod_item os @116-116
- mod_item path @117-117
- mod_item tokio @120-120
- function_item read @136-143
- function_item read_to_string @148-155
- function_item write @160-166
- function_item copy @172-181
- function_item create_dir @186-192
- function_item create_dir_all @197-203
- function_item remove_dir @208-214
- function_item remove_dir_all @219-225
- function_item remove_file @230-236
- function_item metadata @241-244
- function_item exists @250-253
- function_item canonicalize @259-262
- function_item hard_link @271-277
- function_item read_link @282-285
- function_item rename @290-295
- function_item soft_link @304-311
- function_item symlink_metadata @316-320
- function_item set_permissions @325-329
- function_item initial_buffer_size @331-333
- mod_item private @336-342
- trait_item Sealed @337-337

### third_party/rust/fs-err/src/open_options.rs

Blob: `ea83dc6fd3b2528ae18307346d4cb32c5216ee77`. Grammar: rust. Status: syntax-clean.

- struct_item OpenOptions @7-7
- function_item new @14-16
- function_item read @21-24
- function_item write @29-32
- function_item append @37-40
- function_item truncate @45-48
- function_item create @53-56
- function_item create_new @61-64
- function_item open @69-78
- function_item from_options @84-86
- function_item options @91-93
- function_item options_mut @99-101
- mod_item unix @105-119
- function_item mode @109-112
- function_item custom_flags @114-117
- mod_item windows @122-151
- function_item access_mode @127-130
- function_item share_mode @132-135
- function_item custom_flags @136-139
- function_item attributes @141-144
- function_item security_qos_flags @146-149

### third_party/rust/fs-err/src/os.rs

Blob: `b801e6076340e10cd591ad85b7c42a4c73f4b9a8`. Grammar: rust. Status: syntax-clean.

- mod_item unix @7-7
- mod_item windows @11-11

### third_party/rust/fs-err/src/os/unix.rs

Blob: `929eacf21e067502c067cffec0409a7089c83f01`. Grammar: rust. Status: syntax-clean.

- mod_item fs @2-84
- function_item symlink @15-21
- function_item chown @29-33
- function_item lchown @42-46
- function_item chroot @54-57
- trait_item FileExt @63-72
- function_signature_item read_at @65-65
- function_signature_item read_exact_at @67-67
- function_signature_item write_at @69-69
- function_signature_item write_all_at @71-71
- trait_item OpenOptionsExt @78-83
- function_signature_item mode @80-80
- function_signature_item custom_flags @82-82

### third_party/rust/fs-err/src/os/windows.rs

Blob: `c1cfc0050a4fdd2db570c4166ea06904174ebe0e`. Grammar: rust. Status: syntax-clean.

- mod_item fs @2-60
- function_item symlink_dir @12-18
- function_item symlink_file @25-31
- trait_item FileExt @37-42
- function_signature_item seek_read @39-39
- function_signature_item seek_write @41-41
- trait_item OpenOptionsExt @48-59
- function_signature_item access_mode @50-50
- function_signature_item share_mode @52-52
- function_signature_item custom_flags @54-54
- function_signature_item attributes @56-56
- function_signature_item security_qos_flags @58-58

### third_party/rust/fs-err/src/path.rs

Blob: `cac6111fe4e890be989209afa2136ddf22b8fdc0`. Grammar: rust. Status: syntax-clean.

- trait_item PathExt @14-41
- function_signature_item fs_err_try_exists @19-19
- function_signature_item fs_err_metadata @23-23
- function_signature_item fs_err_symlink_metadata @27-27
- function_signature_item fs_err_canonicalize @32-32
- function_signature_item fs_err_read_link @36-36
- function_signature_item fs_err_read_dir @40-40
- function_item fs_err_try_exists @45-48
- function_item fs_err_metadata @50-52
- function_item fs_err_symlink_metadata @54-56
- function_item fs_err_canonicalize @58-60
- function_item fs_err_read_link @62-64
- function_item fs_err_read_dir @66-68

### third_party/rust/fs-err/src/tokio/dir_builder.rs

Blob: `1d4579087fcbb8c484dca9715c2499b8dcc79d86`. Grammar: rust. Status: syntax-clean.

- struct_item DirBuilder @10-12
- function_item new @27-29
- function_item recursive @36-39
- function_item create @44-50
- function_item mode @58-61

### third_party/rust/fs-err/src/tokio/file.rs

Blob: `00c44532ec91f227978c6cb559715872c10a2d47`. Grammar: rust. Status: syntax-clean.

- struct_item File @21-24
- function_item open @30-36
- function_item create @41-47
- function_item create_new @52-58
- function_item options @63-65
- function_item from_std @70-73
- function_item sync_all @78-83
- function_item sync_data @89-94
- function_item set_len @99-104
- function_item metadata @109-114
- function_item try_clone @121-126
- function_item into_std @132-134
- function_item try_into_std @139-144
- function_item set_permissions @149-154
- function_item from_parts @160-168
- function_item into_parts @171-173
- function_item file @176-178
- function_item file_mut @181-183
- function_item path @186-188
- function_item error @191-193
- function_item from @197-200
- function_item from @204-206
- function_item as_raw_fd @211-213
- function_item as_raw_handle @218-220
- function_item poll_read @224-233
- function_item start_seek @237-241
- function_item poll_complete @243-248
- function_item poll_write @252-261
- function_item poll_flush @263-268
- function_item poll_shutdown @270-275
- function_item poll_write_vectored @277-286
- function_item is_write_vectored @288-290

### third_party/rust/fs-err/src/tokio/mod.rs

Blob: `a9105055eb42e02c84cad1949ce527bc13df6d79`. Grammar: rust. Status: syntax-clean.

- mod_item dir_builder @7-7
- mod_item file @8-8
- mod_item open_options @9-9
- mod_item read_dir @10-10
- function_item canonicalize @22-27
- function_item copy @35-40
- function_item create_dir @46-51
- function_item create_dir_all @58-63
- function_item hard_link @73-78
- function_item metadata @85-90
- function_item try_exists @96-101
- function_item read @107-112
- function_item read_link @118-123
- function_item read_to_string @130-135
- function_item remove_dir @141-146
- function_item remove_dir_all @152-157
- function_item remove_file @163-168
- function_item rename @175-180
- function_item set_permissions @186-191
- function_item symlink_metadata @197-202
- function_item symlink @211-216
- function_item symlink_dir @225-230
- function_item symlink_file @239-246
- function_item write @253-258

### third_party/rust/fs-err/src/tokio/open_options.rs

Blob: `6530d0462773ea1ead96c5b0248e5c452e2d644b`. Grammar: rust. Status: syntax-clean.

- struct_item OpenOptions @12-14
- function_item new @31-35
- function_item read @40-43
- function_item write @48-51
- function_item append @56-59
- function_item truncate @64-67
- function_item create @72-75
- function_item create_new @80-83
- function_item open @88-95
- function_item mode @103-106
- function_item custom_flags @111-114
- function_item from @118-120
- function_item from @124-126

### third_party/rust/fs-err/src/tokio/read_dir.rs

Blob: `c98b5cf1d9fcdb9c612260e58a8871ac685e54a5`. Grammar: rust. Status: syntax-clean.

- function_item read_dir @13-22
- struct_item ReadDir @30-33
- function_item next_entry @39-44
- function_item poll_next_entry @49-54
- struct_item DirEntry @62-64
- function_item path @70-72
- function_item file_name @78-80
- function_item metadata @85-90
- function_item file_type @95-100
- function_item ino @108-110

### third_party/rust/futures-channel/benches/sync_mpsc.rs

Blob: `7c3c3d3a8039bc56661293cbb90b472b87989c44`. Grammar: rust. Status: syntax-clean.

- function_item unbounded_1_tx @20-37
- function_item unbounded_100_tx @41-59
- function_item unbounded_uncontended @62-73
- struct_item TestSender @76-79
- function_item poll_next @85-94
- function_item bounded_1_tx @99-112
- function_item bounded_100_tx @116-135

### third_party/rust/futures-channel/src/lib.rs

Blob: `09d6a1e2de1fc7321add0165547d923264306e18`. Grammar: rust. Status: syntax-clean.

- mod_item lock @32-32
- mod_item mpsc @35-35
- mod_item oneshot @38-38

### third_party/rust/futures-channel/src/lock.rs

Blob: `b328d0f7dd9de9aab9937a12902e970c2eafff63`. Grammar: rust. Status: syntax-clean.

- struct_item Lock @17-20
- struct_item TryLock @24-26
- function_item new @39-41
- function_item try_lock @52-58
- function_item deref @63-67
- function_item deref_mut @71-78
- function_item drop @82-84
- mod_item tests @88-102
- function_item smoke @92-101

### third_party/rust/futures-channel/src/mpsc/mod.rs

Blob: `03a8a53898a15f321d2a687feba76dd9055c6e33`. Grammar: rust. Status: syntax-clean.

- mod_item queue @93-93
- mod_item sink_impl @95-95
- struct_item UnboundedSenderInner @97-100
- struct_item BoundedSenderInner @102-114
- struct_item Sender @123-123
- struct_item UnboundedSender @128-128
- trait_item AssertKinds @131-131
- struct_item Receiver @137-139
- struct_item UnboundedReceiver @144-146
- struct_item SendError @153-155
- struct_item TrySendError @159-162
- enum_item SendErrorKind @165-168
- struct_item TryRecvError @171-173
- function_item fmt @176-182
- function_item is_full @189-194
- function_item is_disconnected @197-202
- function_item fmt @206-208
- function_item fmt @212-218
- function_item is_full @225-227
- function_item is_disconnected @230-232
- function_item into_inner @235-237
- function_item into_send_error @240-242
- function_item fmt @246-248
- function_item fmt @252-254
- struct_item UnboundedInner @259-272
- struct_item BoundedInner @274-293
- struct_item State @297-303
- struct_item SenderTask @320-323
- function_item new @326-328
- function_item notify @330-336
- function_item channel @349-372
- function_item unbounded @384-397
- function_item poll_ready_nb @406-413
- function_item queue_push_and_signal @416-423
- function_item inc_num_messages @426-454
- function_item same_receiver @457-459
- function_item is_connected_to @462-464
- function_item ptr @469-471
- function_item is_closed @474-476
- function_item close_channel @479-486
- function_item try_send @492-500
- function_item do_send_b @504-544
- function_item queue_push_and_signal @547-554
- function_item inc_num_messages @557-585
- function_item park @587-602
- function_item poll_ready @616-623
- function_item same_receiver @626-628
- function_item is_connected_to @631-633
- function_item ptr @638-640
- function_item is_closed @643-645
- function_item close_channel @648-655
- function_item poll_unparked @657-681
- function_item try_send @687-693
- function_item start_send @700-702
- function_item poll_ready @716-719
- function_item is_closed @722-724
- function_item close_channel @727-731
- function_item disconnect @734-736
- function_item same_receiver @739-744
- function_item is_connected_to @747-752
- function_item hash_receiver @755-763
- function_item poll_ready @768-771
- function_item is_closed @774-776
- function_item close_channel @779-783
- function_item disconnect @786-788
- function_item do_send_nb @791-800
- function_item start_send @806-808
- function_item unbounded_send @815-817
- function_item same_receiver @820-825
- function_item is_connected_to @828-833
- function_item hash_receiver @836-844
- function_item len @847-853
- function_item is_empty @856-858
- function_item clone @862-864
- function_item clone @868-870
- function_item clone @874-898
- function_item clone @902-930
- function_item drop @934-941
- function_item drop @945-952
- function_item fmt @956-958
- function_item fmt @962-964
- function_item close @978-988
- function_item try_next @1000-1005
- function_item next_message @1007-1043
- function_item unpark_one @1046-1052
- function_item dec_num_messages @1054-1061
- function_item is_terminated @1068-1070
- function_item poll_next @1076-1094
- function_item size_hint @1096-1102
- function_item drop @1106-1132
- function_item fmt @1136-1144
- function_item close @1152-1156
- function_item try_next @1168-1173
- function_item next_message @1175-1207
- function_item dec_num_messages @1209-1216
- function_item is_terminated @1220-1222
- function_item poll_next @1228-1246
- function_item size_hint @1248-1254
- function_item drop @1258-1284
- function_item fmt @1288-1296
- function_item set_closed @1307-1314
- function_item max_senders @1320-1322
- function_item set_closed @1325-1332
- function_item is_closed @1342-1344
- function_item size_hint @1346-1352
- function_item decode_state @1361-1363
- function_item encode_state @1365-1373

### third_party/rust/futures-channel/src/mpsc/queue.rs

Blob: `78cbdce6ec1ff83a6c22b2f5f55138944b354ec6`. Grammar: rust. Status: syntax-clean.

- enum_item PopResult @53-63
- struct_item Node @65-68
- struct_item Queue @73-76
- function_item new @82-84
- function_item new @90-93
- function_item push @96-102
- function_item pop @116-136
- function_item pop_spin @142-163
- function_item drop @167-176

### third_party/rust/futures-channel/src/mpsc/sink_impl.rs

Blob: `1be20162c2ef1ce5f00f0646d27c73020937be25`. Grammar: rust. Status: syntax-clean.

- function_item poll_ready @9-11
- function_item start_send @13-15
- function_item poll_flush @17-25
- function_item poll_close @27-30
- function_item poll_ready @36-38
- function_item start_send @40-42
- function_item poll_flush @44-46
- function_item poll_close @48-51
- function_item poll_ready @57-59
- function_item start_send @61-63
- function_item poll_flush @65-67
- function_item poll_close @69-72

### third_party/rust/futures-channel/src/oneshot.rs

Blob: `fe5b115a337705528d8f291667631bc11a60977f`. Grammar: rust. Status: syntax-clean.

- struct_item Receiver @19-21
- struct_item Sender @26-28
- struct_item Inner @36-68
- function_item channel @104-109
- function_item new @112-119
- function_item send @121-152
- function_item poll_canceled @154-186
- function_item is_canceled @188-190
- function_item drop_tx @192-227
- function_item close_rx @229-239
- function_item try_recv @241-254
- function_item recv @256-298
- function_item drop_rx @300-328
- function_item send @341-343
- function_item poll_canceled @357-359
- function_item cancellation @366-368
- function_item is_canceled @376-378
- function_item is_connected_to @382-384
- function_item drop @388-390
- function_item fmt @394-396
- struct_item Cancellation @404-406
- function_item poll @411-413
- struct_item Canceled @419-419
- function_item fmt @422-424
- function_item close @438-440
- function_item try_recv @450-452
- function_item poll @458-460
- function_item is_terminated @464-475
- function_item drop @479-481
- function_item fmt @485-487

### third_party/rust/futures-channel/tests/channel.rs

Blob: `5f01a8ef4c1ca1c6494ca7aeeaf290843c336070`. Grammar: rust. Status: syntax-clean.

- function_item sequence @10-23
- function_item send_sequence @25-29
- function_item drop_sender @32-37
- function_item drop_rx @40-45
- function_item drop_order @48-66
- struct_item A @52-52
- function_item drop @55-57

### third_party/rust/futures-channel/tests/mpsc-close.rs

Blob: `2d49936fc12a2ca58c06d9350179ea629d661548`. Grammar: rust. Status: syntax-clean.

- function_item smoke @13-22
- function_item multiple_senders_disconnect @25-69
- function_item multiple_senders_close_channel @72-104
- function_item single_receiver_drop_closes_channel_and_drains @107-146
- function_item stress_try_send_as_receiver_closes @152-277
- struct_item TestRx @165-169
- struct_item TestTask @170-174
- function_item new @177-187
- function_item poll @192-217
- function_item unbounded_try_next_after_none @280-288
- function_item bounded_try_next_after_none @291-299

### third_party/rust/futures-channel/tests/mpsc-size_hint.rs

Blob: `d9cdaa31fa37f832a4e0a2649f8c30b683805249`. Grammar: rust. Status: syntax-clean.

- function_item unbounded_size_hint @5-21
- function_item channel_size_hint @24-40

### third_party/rust/futures-channel/tests/mpsc.rs

Blob: `28d476b05a6ea45881222f1cf7949990476ffb6a`. Grammar: rust. Status: syntax-clean.

- trait_item AssertSend @14-14
- function_item send_recv @19-26
- function_item send_recv_no_buffer @29-62
- function_item send_shared_recv @65-75
- function_item send_recv_threads @78-89
- function_item send_recv_threads_no_capacity @92-104
- function_item recv_close_gets_none @107-122
- function_item tx_close_gets_none @125-133
- function_item stress_shared_unbounded @203-229
- function_item stress_shared_bounded_hard @232-258
- function_item stress_receiver_multi_task_bounded_hard @262-325
- function_item stress_drop_sender @330-345
- function_item list @333-339
- function_item send_one_two_three @347-351
- function_item stress_close_receiver_iter @355-384
- function_item stress_close_receiver @387-393
- function_item stress_poll_ready_sender @395-399
- function_item stress_poll_ready @404-430
- function_item stress @409-424
- function_item try_send_1 @433-453
- function_item try_send_2 @456-480
- function_item try_send_fail @483-499
- function_item try_send_recv @502-513
- function_item same_receiver @516-532
- function_item is_connected_to @535-543
- function_item hash_receiver @546-592
- function_item send_backpressure @595-613
- function_item send_backpressure_multi_senders @616-635
- function_item unbounded_len @640-658

### third_party/rust/futures-channel/tests/oneshot.rs

Blob: `6b48376dc0eddf7190e3bd5c8df1ef09fa1c47c9`. Grammar: rust. Status: syntax-clean.

- function_item smoke_poll @10-23
- function_item cancel_notifies @26-34
- function_item cancel_lots @37-58
- function_item cancel_after_sender_drop_doesnt_notify @61-67
- function_item close @70-81
- function_item close_wakes @84-94
- function_item is_canceled @97-102
- function_item cancel_sends @105-125

### third_party/rust/futures-core/src/future.rs

Blob: `30c0323a6bd47494db431bd52cc37c6c862bb26e`. Grammar: rust. Status: syntax-clean.

- trait_item FusedFuture @37-40
- function_signature_item is_terminated @39-39
- function_item is_terminated @43-45
- function_item is_terminated @53-55
- mod_item private_try_future @58-64
- trait_item Sealed @61-61
- trait_item TryFuture @68-81
- function_signature_item try_poll @80-80
- function_item try_poll @91-93
- mod_item if_alloc @97-113
- function_item is_terminated @102-104
- function_item is_terminated @109-111

### third_party/rust/futures-core/src/lib.rs

Blob: `6ff6b974b15654b2d795499dc2d5b05d7c4d122b`. Grammar: rust. Status: syntax-clean.

- mod_item future @18-18
- mod_item stream @22-22
- mod_item task @27-27

### third_party/rust/futures-core/src/stream.rs

Blob: `dd07d5aa014da22dea2576a9440159a4d40cd134`. Grammar: rust. Status: syntax-clean.

- trait_item Stream @37-108
- function_signature_item poll_next @76-76
- function_item size_hint @105-107
- function_item poll_next @113-115
- function_item size_hint @117-119
- function_item poll_next @129-131
- function_item size_hint @133-135
- trait_item FusedStream @146-149
- function_signature_item is_terminated @148-148
- function_item is_terminated @152-154
- function_item is_terminated @162-164
- mod_item private_try_stream @167-173
- trait_item Sealed @170-170
- trait_item TryStream @177-193
- function_signature_item try_poll_next @189-192
- function_item try_poll_next @202-207
- mod_item if_alloc @211-245
- function_item poll_next @218-220
- function_item size_hint @222-224
- function_item poll_next @231-233
- function_item size_hint @235-237
- function_item is_terminated @241-243

### third_party/rust/futures-core/src/task/__internal/atomic_waker.rs

Blob: `3b82fb7cc8e1165b9c0e084e799a854c9dd9a079`. Grammar: rust. Status: syntax-clean.

- struct_item AtomicWaker @96-99
- function_item new @207-214
- trait_item AssertSync @210-210
- function_item register @266-359
- function_item wake @364-368
- function_item take @378-406
- function_item default @410-412
- function_item fmt @416-418

### third_party/rust/futures-core/src/task/__internal/mod.rs

Blob: `c2487422800b64ab490a02e98d9a77caa0704807`. Grammar: rust. Status: syntax-clean.

- mod_item atomic_waker @2-2

### third_party/rust/futures-core/src/task/mod.rs

Blob: `19e4eaecdd6b8340c079ca20aae459600fa8b8d0`. Grammar: rust. Status: syntax-clean.

- mod_item poll @4-4
- mod_item __internal @7-7

### third_party/rust/futures-core/src/task/poll.rs

Blob: `607e78e060056b0d94725213e17bd0ba7f2a022b`. Grammar: rust. Status: syntax-clean.


### third_party/rust/futures-executor/benches/thread_notify.rs

Blob: `88d0447cf68bf7765e6e6ce128893097598e9965`. Grammar: rust. Status: syntax-clean.

- function_item thread_yield_single_thread_one_wait @12-37
- struct_item Yield @15-17
- function_item poll @22-30
- function_item thread_yield_single_thread_many_wait @40-67
- struct_item Yield @43-45
- function_item poll @50-58
- function_item thread_yield_multi_thread @70-109
- struct_item Yield @78-81
- function_item poll @87-95

### third_party/rust/futures-executor/src/enter.rs

Blob: `cb58c30bb75ecfa6adb4b61d83781f3610f3ed94`. Grammar: rust. Status: syntax-clean.

- struct_item Enter @9-11
- struct_item EnterError @15-17
- function_item fmt @20-22
- function_item fmt @26-28
- function_item enter @55-65
- function_item fmt @68-70
- function_item drop @74-79

### third_party/rust/futures-executor/src/lib.rs

Blob: `b1af87545fc0c7457eb22c4c4658a35c73cd0f34`. Grammar: rust. Status: syntax-clean.

- mod_item local_pool @57-57
- mod_item thread_pool @64-64
- mod_item unpark_mutex @67-67
- mod_item enter @74-74

### third_party/rust/futures-executor/src/local_pool.rs

Blob: `8a9bc2fc90241dae3630faa6f3bd6eb8b8f6e148`. Grammar: rust. Status: syntax-clean.

- struct_item LocalPool @31-34
- struct_item LocalSpawner @39-41
- struct_item ThreadNotify @45-54
- function_item wake_by_ref @64-75
- function_item run_executor @80-103
- function_item woken @106-108
- function_item new @112-114
- function_item spawner @117-119
- function_item run @136-138
- function_item run_until @157-172
- function_item try_run_one @202-226
- function_item run_until_stalled @253-266
- function_item poll_pool @275-292
- function_item drain_incoming @295-300
- function_item default @304-306
- function_item block_on @315-318
- function_item block_on_stream @324-326
- struct_item BlockingStream @330-332
- function_item deref @336-338
- function_item deref_mut @342-344
- function_item into_inner @349-351
- function_item next @357-359
- function_item size_hint @361-363
- function_item spawn_obj @367-374
- function_item status @376-382
- function_item spawn_local_obj @386-393
- function_item status_local @395-401

### third_party/rust/futures-executor/src/thread_pool.rs

Blob: `537100895345ae0f7160f4c768e1a54693110462`. Grammar: rust. Status: syntax-clean.

- struct_item ThreadPool @28-30
- struct_item ThreadPoolBuilder @37-43
- trait_item AssertSendSync @45-45
- struct_item PoolState @48-53
- function_item fmt @56-58
- function_item fmt @62-67
- enum_item Message @70-73
- function_item new @81-83
- function_item builder @90-92
- function_item spawn_obj_ok @98-105
- function_item spawn_ok @124-129
- function_item spawn_obj @133-136
- function_item send @140-142
- function_item work @144-164
- function_item clone @168-171
- function_item drop @175-181
- function_item new @188-196
- function_item pool_size @206-210
- function_item stack_size @215-218
- function_item name_prefix @226-229
- function_item after_start @240-246
- function_item before_stop @256-262
- function_item create @265-290
- function_item default @294-296
- struct_item Task @300-304
- struct_item WakeHandle @306-309
- function_item run @314-341
- function_item fmt @345-347
- function_item wake_by_ref @351-355
- mod_item tests @359-380
- function_item test_drop_after_start @364-379

### third_party/rust/futures-executor/src/unpark_mutex.rs

Blob: `ac5112cfa2ee30a6e108db5d6be38aedb08b63ce`. Grammar: rust. Status: syntax-clean.

- struct_item UnparkMutex @10-16
- function_item new @46-48
- function_item notify @56-91
- function_item start_poll @100-102
- function_item wait @110-125
- function_item complete @134-136

### third_party/rust/futures-executor/tests/local_pool.rs

Blob: `72ce74b7442392a50238947a05f218eb806702aa`. Grammar: rust. Status: syntax-clean.

- struct_item Pending @13-13
- function_item poll @18-20
- function_item pending @23-25
- function_item run_until_single_future @28-40
- function_item run_until_ignores_spawned @43-48
- function_item run_until_executes_spawned @51-64
- function_item run_returns_if_empty @67-71
- function_item run_executes_spawned @74-101
- function_item run_spawn_many @104-127
- function_item try_run_one_returns_if_empty @130-133
- function_item try_run_one_executes_one_ready @136-166
- function_item try_run_one_returns_on_no_progress @169-207
- function_item try_run_one_runs_sub_futures @210-235
- function_item run_until_stalled_returns_if_empty @238-242
- function_item run_until_stalled_returns_multiple_times @245-259
- function_item run_until_stalled_runs_spawned_sub_futures @262-287
- function_item run_until_stalled_executes_all_ready @290-320
- function_item nesting_run @324-339
- function_item nesting_run_run_until_stalled @343-358
- function_item tasks_are_scheduled_fairly @361-404
- struct_item Spin @364-367
- function_item poll @372-393
- function_item park_unpark_independence @409-434
- struct_item SelfWaking @436-438
- function_item poll @443-450
- function_item self_waking_run_until_stalled @458-472
- function_item self_waking_try_run_one @479-496

### third_party/rust/futures-io/src/lib.rs

Blob: `9c2fa056ad763ab9f147b0a1b1e49a053904bf32`. Grammar: rust. Status: syntax-clean.

- mod_item if_std @26-558
- trait_item AsyncRead @47-104
- function_signature_item poll_read @63-67
- function_item poll_read_vectored @91-103
- trait_item AsyncWrite @113-211
- function_signature_item poll_write @132-136
- function_item poll_write_vectored @161-173
- function_signature_item poll_flush @193-193
- function_signature_item poll_close @210-210
- trait_item AsyncSeek @220-245
- function_signature_item poll_seek @240-244
- trait_item AsyncBufRead @254-301
- function_signature_item poll_fill_buf @283-283
- function_signature_item consume @300-300
- function_item poll_read @336-342
- function_item poll_read_vectored @344-350
- function_item poll_write @418-424
- function_item poll_write_vectored @426-432
- function_item poll_flush @434-436
- function_item poll_close @438-440
- function_item poll_seek @500-506
- function_item poll_fill_buf @534-536
- function_item consume @538-540

### third_party/rust/futures-macro/src/executor.rs

Blob: `7f1d0a93f46ee25f245d277f6b521496f2d6ce75`. Grammar: rust. Status: syntax-clean.

- function_item test @5-56

### third_party/rust/futures-macro/src/join.rs

Blob: `0e891b3aad3073aad8a577e7df76c22d2405e24a`. Grammar: rust. Status: syntax-clean.

- struct_item Join @10-12
- function_item parse @15-27
- function_item bind_futures @30-48
- function_item join @51-86
- function_item try_join @89-144

### third_party/rust/futures-macro/src/lib.rs

Blob: `c1b94785e8a6a7486c26f4f69711a5122b349959`. Grammar: rust. Status: syntax-clean.

- mod_item executor @13-13
- mod_item join @14-14
- mod_item select @15-15
- mod_item stream_select @16-16
- function_item join_internal @20-22
- function_item try_join_internal @26-28
- function_item select_internal @32-34
- function_item select_biased_internal @38-40
- function_item test_internal @45-47
- function_item stream_select_internal @51-55

### third_party/rust/futures-macro/src/select.rs

Blob: `ca83a87e4a47048ee6263a6fc6b02c7ff7f20af5`. Grammar: rust. Status: syntax-clean.

- mod_item kw @9-11
- struct_item Select @13-19
- enum_item CaseKind @22-26
- function_item parse @29-87
- function_item declare_result_enum @94-119
- function_item select @122-124
- function_item select_biased @127-129
- function_item select_inner @131-330

### third_party/rust/futures-macro/src/stream_select.rs

Blob: `9927b5307348dc2302060481a2993078df984bc6`. Grammar: rust. Status: syntax-clean.

- function_item stream_select @6-113

### third_party/rust/futures-sink/src/lib.rs

Blob: `52394e8c2af5e38d74c59070ddb4ed73a4d6289a`. Grammar: rust. Status: syntax-clean.

- trait_item Sink @52-117
- function_signature_item poll_ready @68-68
- function_signature_item start_send @89-89
- function_signature_item poll_flush @103-103
- function_signature_item poll_close @116-116
- function_item poll_ready @122-124
- function_item start_send @126-128
- function_item poll_flush @130-132
- function_item poll_close @134-136
- function_item poll_ready @146-148
- function_item start_send @150-152
- function_item poll_flush @154-156
- function_item poll_close @158-160
- mod_item if_alloc @164-240
- function_item poll_ready @171-173
- function_item start_send @175-179
- function_item poll_flush @181-183
- function_item poll_close @185-187
- function_item poll_ready @193-195
- function_item start_send @197-201
- function_item poll_flush @203-205
- function_item poll_close @207-209
- function_item poll_ready @215-220
- function_item start_send @222-224
- function_item poll_flush @226-231
- function_item poll_close @233-238

### third_party/rust/futures-task/src/arc_wake.rs

Blob: `aa6de0fc437781d0c7c82f84cac2d829d1c93806`. Grammar: rust. Status: syntax-clean.

- trait_item ArcWake @20-49
- function_item wake @31-33
- function_signature_item wake_by_ref @48-48

### third_party/rust/futures-task/src/future_obj.rs

Blob: `a611382193206d1e94ac64faa06b21e9e8358120`. Grammar: rust. Status: syntax-clean.

- struct_item LocalFutureObj @16-20
- function_item remove_future_lifetime @29-33
- function_item remove_drop_lifetime @36-40
- function_item new @45-51
- function_item into_future_obj @61-63
- function_item fmt @67-69
- function_item from @74-76
- function_item poll @83-85
- function_item drop @89-91
- struct_item FutureObj @103-103
- function_item new @111-113
- function_item fmt @117-119
- function_item poll @126-128
- trait_item UnsafeFutureObj @141-174
- function_signature_item into_raw @153-153
- function_signature_item drop @173-173
- function_item into_raw @180-182
- function_item drop @184-184
- function_item into_raw @188-190
- function_item drop @192-192
- function_item into_raw @199-201
- function_item drop @203-203
- function_item into_raw @207-209
- function_item drop @211-211
- mod_item if_alloc @215-335
- function_item into_raw @223-225
- function_item drop @227-229
- function_item into_raw @233-235
- function_item drop @237-239
- function_item into_raw @243-245
- function_item drop @247-249
- function_item into_raw @256-259
- function_item drop @261-263
- function_item into_raw @267-270
- function_item drop @272-274
- function_item into_raw @278-281
- function_item drop @283-285
- function_item from @289-291
- function_item from @295-297
- function_item from @301-303
- function_item from @307-309
- function_item from @313-315
- function_item from @319-321
- function_item from @325-327
- function_item from @331-333

### third_party/rust/futures-task/src/lib.rs

Blob: `c119b6b1e46b5844cf3b1a03cee58204d9245845`. Grammar: rust. Status: syntax-clean.

- mod_item spawn @18-18
- mod_item arc_wake @23-23
- mod_item waker @30-30
- mod_item waker_ref @37-37
- mod_item future_obj @42-42
- mod_item noop_waker @45-45

### third_party/rust/futures-task/src/noop_waker.rs

Blob: `f76a8a2e95d8e2502a9a53d910dfba54643b298a`. Grammar: rust. Status: syntax-clean.

- function_item noop_clone @6-8
- function_item noop @10-10
- function_item noop_raw_waker @14-16
- function_item noop_waker @29-32
- function_item noop_waker_ref @45-53
- struct_item SyncRawWaker @46-46
- mod_item tests @56-63
- function_item issue_2091_cross_thread_segfault @59-62

### third_party/rust/futures-task/src/spawn.rs

Blob: `4a9a45a44668d2171e1382efcff85ddd68874897`. Grammar: rust. Status: syntax-clean.

- trait_item Spawn @6-27
- function_signature_item spawn_obj @15-15
- function_item status @24-26
- trait_item LocalSpawn @31-52
- function_signature_item spawn_local_obj @40-40
- function_item status_local @49-51
- struct_item SpawnError @55-57
- function_item fmt @60-62
- function_item fmt @66-68
- function_item shutdown @76-78
- function_item is_shutdown @81-83
- function_item spawn_obj @87-89
- function_item status @91-93
- function_item spawn_obj @97-99
- function_item status @101-103
- function_item spawn_local_obj @107-109
- function_item status_local @111-113
- function_item spawn_local_obj @117-119
- function_item status_local @121-123
- mod_item if_alloc @127-192
- function_item spawn_obj @132-134
- function_item status @136-138
- function_item spawn_local_obj @142-144
- function_item status_local @146-148
- function_item spawn_obj @152-154
- function_item status @156-158
- function_item spawn_local_obj @162-164
- function_item status_local @166-168
- function_item spawn_obj @173-175
- function_item status @177-179
- function_item spawn_local_obj @184-186
- function_item status_local @188-190

### third_party/rust/futures-task/src/waker.rs

Blob: `ce90aa83d9a20122c67a86778a35b825f2f3fb2c`. Grammar: rust. Status: syntax-clean.

- function_item waker_vtable @6-13
- function_item waker @19-26
- function_item increase_refcount @32-37
- function_item clone_arc_raw @41-44
- function_item wake_arc_raw @46-49
- function_item wake_by_ref_arc_raw @52-56
- function_item drop_arc_raw @58-60

### third_party/rust/futures-task/src/waker_ref.rs

Blob: `5957b4d46afc8aea39c087fa9bc5f4e637c888bf`. Grammar: rust. Status: syntax-clean.

- struct_item WakerRef @14-17
- function_item new @22-27
- function_item new_unowned @36-38
- function_item deref @45-47
- function_item waker_ref @55-66

### third_party/rust/futures-util/benches/bilock.rs

Blob: `013f3351e43df521dc5637ec72266bce8b3ab512`. Grammar: rust. Status: syntax-clean.

- function_item contended @13-42
- function_item lock_unlock @45-68

### third_party/rust/futures-util/benches/flatten_unordered.rs

Blob: `517b2816c3ded7b570f5d5d38f9ad81cb9ff071e`. Grammar: rust. Status: syntax-clean.

- function_item oneshot_streams @16-58

### third_party/rust/futures-util/benches/futures_unordered.rs

Blob: `d5fe7a59deff25d4085d6f00297bf9bff4f88df8`. Grammar: rust. Status: syntax-clean.

- function_item oneshots @15-43

### third_party/rust/futures-util/benches/select.rs

Blob: `5410a952997072dab30e910831cc367d591512eb`. Grammar: rust. Status: syntax-clean.

- function_item select_streams @10-35

### third_party/rust/futures-util/src/abortable.rs

Blob: `e1e79e371db6d23213207d3a64149f191be70c7a`. Grammar: rust. Status: syntax-clean.

- function_item new @58-60
- function_item is_aborted @68-70
- struct_item AbortRegistration @77-79
- function_item handle @87-89
- struct_item AbortHandle @94-96
- function_item new_pair @103-108
- struct_item AbortInner @114-117
- struct_item Aborted @121-121
- function_item fmt @124-126
- function_item try_poll @133-160
- function_item poll @169-171
- function_item poll_next @180-182
- function_item abort @192-195
- function_item is_aborted @206-208

### third_party/rust/futures-util/src/async_await/join_mod.rs

Blob: `28f3b232e77e4505bf5d05e4407fa999a84afb6d`. Grammar: rust. Status: syntax-clean.


### third_party/rust/futures-util/src/async_await/mod.rs

Blob: `7e3f12c99fe5d2e89530f6050ddd266270db8f5d`. Grammar: rust. Status: syntax-clean.

- mod_item poll @10-10
- mod_item pending @15-15
- mod_item join_mod @21-21
- mod_item select_mod @28-28
- mod_item stream_select_mod @36-36
- mod_item random @44-44
- function_item assert_unpin @52-52
- function_item assert_fused_future @56-56
- function_item assert_fused_stream @60-60

### third_party/rust/futures-util/src/async_await/pending.rs

Blob: `5d7a431811feff8bc257c22e26c8989c68f4eb81`. Grammar: rust. Status: syntax-clean.

- function_item pending_once @23-25
- struct_item PendingOnce @29-31
- function_item poll @35-42

### third_party/rust/futures-util/src/async_await/poll.rs

Blob: `b62f45a943cc892dd73193caba136af07e90790a`. Grammar: rust. Status: syntax-clean.

- function_item poll @24-26
- struct_item PollOnce @30-32
- function_item poll @36-38

### third_party/rust/futures-util/src/async_await/random.rs

Blob: `2ac2f78a87dd3a2465c781d5c32356553979990d`. Grammar: rust. Status: syntax-clean.

- function_item shuffle @13-17
- function_item gen_index @20-22
- function_item random @27-54
- function_item prng_seed @32-43

### third_party/rust/futures-util/src/async_await/select_mod.rs

Blob: `80c3c7504a9c4606650bc28c35a5485d6497e2d3`. Grammar: rust. Status: syntax-clean.


### third_party/rust/futures-util/src/async_await/stream_select_mod.rs

Blob: `c3e4f0052c38274aa980ad64249070809903c84e`. Grammar: rust. Status: syntax-clean.


### third_party/rust/futures-util/src/compat/compat01as03.rs

Blob: `0de2d53301f36d7d3073e0f58e82963b186961ba`. Grammar: rust. Status: syntax-clean.

- struct_item Compat01As03 @24-26
- function_item new @33-35
- function_item in_notify @37-40
- function_item get_ref @43-45
- function_item get_mut @49-51
- function_item into_inner @55-57
- trait_item Future01CompatExt @61-84
- function_item compat @78-83
- trait_item Stream01CompatExt @88-112
- function_item compat @106-111
- trait_item Sink01CompatExt @118-145
- function_item sink_compat @139-144
- function_item poll_01_to_03 @149-154
- function_item poll @159-161
- function_item poll_next @167-176
- struct_item Compat01As03Sink @184-188
- function_item new @196-198
- function_item in_notify @200-203
- function_item get_ref @206-208
- function_item get_mut @211-213
- function_item into_inner @216-218
- function_item poll_next @228-237
- function_item start_send @247-251
- function_item poll_ready @253-267
- function_item poll_flush @269-287
- function_item poll_close @289-320
- struct_item NotifyWaker @323-323
- struct_item WakerToHandle @327-327
- function_item from @330-334
- function_item notify @338-340
- function_item clone_raw @344-346
- function_item drop_raw @348-351
- mod_item io @356-455
- trait_item AsyncRead01CompatExt @364-389
- function_item compat @383-388
- trait_item AsyncWrite01CompatExt @394-419
- function_item compat @413-418
- function_item poll_read @423-429
- function_item poll_write @433-439
- function_item poll_flush @441-446
- function_item poll_close @448-453

### third_party/rust/futures-util/src/compat/compat03as01.rs

Blob: `3c5bb77b49c9274048a014516268ab9212c1ed57`. Grammar: rust. Status: syntax-clean.

- struct_item Compat @25-27
- struct_item CompatSink @35-38
- function_item new @46-48
- function_item get_ref @52-54
- function_item get_mut @58-60
- function_item into_inner @63-65
- function_item new @71-73
- function_item get_ref @76-78
- function_item get_mut @81-83
- function_item into_inner @86-88
- function_item poll_03_to_01 @91-96
- function_item poll @105-107
- function_item poll @117-123
- function_item start_send @134-139
- function_item poll_complete @141-143
- function_item close @145-147
- struct_item Current @151-151
- function_item new @154-156
- function_item as_waker @158-186
- function_item ptr_to_current @159-161
- function_item current_to_ptr @162-164
- function_item clone @166-175
- function_item drop @176-176
- function_item wake @177-179
- function_item wake_by_ref @190-192
- function_item with_context @195-204
- function_item with_sink_context @207-216
- mod_item io @220-268
- function_item poll_03_to_io @225-231
- function_item read @234-239
- function_item write @245-250
- function_item flush @252-257
- function_item shutdown @261-266

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [f73792f1-bd90-4483-b56c-86d9854529c0.md](f73792f1-bd90-4483-b56c-86d9854529c0.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `b61ee61bf86a6a7887cd5ba408d1e3debb5dc7eb4ac55bd18591cda8bc66d2cd`.
