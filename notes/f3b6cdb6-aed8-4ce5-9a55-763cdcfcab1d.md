<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["servo/components/style/values/specified/image.rs", "servo/components/style/values/specified/intersection_observer.rs", "servo/components/style/values/specified/length.rs", "servo/components/style/values/specified/list.rs", "servo/components/style/values/specified/mod.rs", "servo/components/style/values/specified/motion.rs", "servo/components/style/values/specified/number.rs", "servo/components/style/values/specified/outline.rs", "servo/components/style/values/specified/page.rs", "servo/components/style/values/specified/param.rs", "servo/components/style/values/specified/percentage.rs", "servo/components/style/values/specified/position.rs", "servo/components/style/values/specified/random.rs", "servo/components/style/values/specified/ratio.rs", "servo/components/style/values/specified/rect.rs", "servo/components/style/values/specified/resolution.rs", "servo/components/style/values/specified/source_size_list.rs", "servo/components/style/values/specified/svg.rs", "servo/components/style/values/specified/svg_path.rs", "servo/components/style/values/specified/table.rs", "servo/components/style/values/specified/text.rs", "servo/components/style/values/specified/time.rs", "servo/components/style/values/specified/transform.rs", "servo/components/style/values/specified/tree_counting.rs", "servo/components/style/values/specified/ui.rs", "servo/components/style/values/specified/url.rs", "servo/components/style/values/tagged_numeric.rs", "servo/components/style_derive/animate.rs", "servo/components/style_derive/cg.rs", "servo/components/style_derive/compute_squared_distance.rs", "servo/components/style_derive/lib.rs", "servo/components/style_derive/parse.rs", "servo/components/style_derive/specified_value_info.rs", "servo/components/style_derive/to_animated_value.rs", "servo/components/style_derive/to_animated_zero.rs", "servo/components/style_derive/to_computed_value.rs", "servo/components/style_derive/to_css.rs", "servo/components/style_derive/to_resolved_value.rs", "servo/components/style_derive/to_typed.rs", "servo/components/style_traits/arc_slice.rs", "servo/components/style_traits/dom.rs", "servo/components/style_traits/lib.rs", "servo/components/style_traits/owned_array.rs", "servo/components/style_traits/owned_slice.rs", "servo/components/style_traits/owned_str.rs", "servo/components/style_traits/specified_value_info.rs", "servo/components/style_traits/values.rs", "servo/components/to_shmem/lib.rs", "servo/components/to_shmem_derive/lib.rs", "servo/components/to_shmem_derive/to_shmem.rs", "servo/components/to_shmem_derive/util.rs", "servo/ports/geckolib/error_reporter.rs", "servo/ports/geckolib/glue.rs", "servo/ports/geckolib/lib.rs", "servo/ports/geckolib/stylesheet_loader.rs", "servo/ports/geckolib/tests/lib.rs", "servo/ports/geckolib/tests/piecewise_linear.rs", "servo/tests/unit/malloc_size_of/lib.rs", "servo/tests/unit/style/animated_properties.rs", "servo/tests/unit/style/attr.rs", "servo/tests/unit/style/custom_properties.rs", "servo/tests/unit/style/lib.rs", "servo/tests/unit/style/logical_geometry.rs", "servo/tests/unit/style/media_queries.rs", "servo/tests/unit/style/parsing/animation.rs", "servo/tests/unit/style/parsing/background.rs", "servo/tests/unit/style/parsing/border.rs", "servo/tests/unit/style/parsing/box_.rs", "servo/tests/unit/style/parsing/column.rs", "servo/tests/unit/style/parsing/effects.rs", "servo/tests/unit/style/parsing/image.rs", "servo/tests/unit/style/parsing/inherited_text.rs", "servo/tests/unit/style/parsing/mod.rs", "servo/tests/unit/style/parsing/outline.rs", "servo/tests/unit/style/parsing/position.rs", "servo/tests/unit/style/parsing/selectors.rs", "servo/tests/unit/style/parsing/supports.rs", "servo/tests/unit/style/parsing/text_overflow.rs", "servo/tests/unit/style/parsing/transition_duration.rs", "servo/tests/unit/style/parsing/transition_timing_function.rs", "servo/tests/unit/style/properties/mod.rs", "servo/tests/unit/style/properties/scaffolding.rs", "servo/tests/unit/style/properties/serialization.rs", "servo/tests/unit/style/rule_tree/bench.rs", "servo/tests/unit/style/rule_tree/mod.rs", "servo/tests/unit/style/size_of.rs", "servo/tests/unit/style/str.rs", "servo/tests/unit/style/stylesheets.rs", "servo/tests/unit/style/stylist.rs"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/servo native and TypeScript syntax map 236

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### servo/components/style/values/specified/image.rs

Blob: `b358f427647da7efde8cc11d2a96da6de28299a1`. Grammar: rust. Status: syntax-clean.

- function_item to_typed @44-56
- function_item has_modern_syntax @92-107
- function_item default_color_interpolation_method @110-124
- function_item cross_fade_enabled @126-128
- function_item collect_completion_keywords @133-152
- function_item collect_completion_keywords @160-164
- function_item collect_completion_keywords @170-172
- enum_item LineDirection @179-188
- function_item parse @203-205
- function_item parse_with_cors_mode @209-260
- function_item for_cascade @267-270
- function_item parse_element @274-279
- function_item parse_with_cors_anonymous @283-293
- function_item parse_forbid_none @296-301
- function_item parse_only_url @304-314
- function_item parse_args @319-329
- function_item parse_percentage @333-343
- function_item parse @346-364
- function_item parse @368-385
- function_item parse @389-411
- function_item parse_type @415-418
- function_item parse @420-468
- function_item parse @472-544
- enum_item Shape @473-477
- function_item parse_webkit_gradient_argument @548-715
- enum_item Component @558-562
- function_item line_direction_from_points @564-583
- function_item parse @586-601
- function_item from @605-618
- function_item from @622-634
- function_item partial_cmp @638-649
- function_item parse_webkit_gradient_stops @717-802
- function_item parse_stops @805-815
- function_item parse_linear @819-868
- function_item parse_radial @871-939
- function_item parse_conic @942-1004
- function_item points_downwards @1008-1021
- function_item to_css @1023-1050
- function_item parse @1054-1096
- function_item parse @1100-1204
- function_item parse_with_compat_mode @1208-1222
- function_item parse_comma_separated @1226-1276
- function_item parse @1280-1289
- function_item parse_args @1294-1312
- enum_item ImageRendering @1334-1353
- enum_item ImageDecoding @1375-1380

### servo/components/style/values/specified/intersection_observer.rs

Blob: `036c402b819048ccdcc04961d12a19b4889abc87`. Grammar: rust. Status: syntax-clean.

- function_item parse_pixel_or_percent @17-37
- struct_item IntersectionObserverMargin @46-46
- function_item parse @49-59
- function_item to_css @67-79

### servo/components/style/values/specified/length.rs

Blob: `4d547730affed9d8b4e009b2207c0fef9b7e0080`. Grammar: rust. Status: syntax-clean.

- enum_item LengthUnit @69-125
- function_item from_str @130-132
- function_item from_str_with_flags @136-199
- function_item as_str @203-256
- function_item is_absolute @260-265
- function_item is_font_relative @269-285
- function_item is_viewport_percentage @289-317
- function_item is_container_relative @321-326
- function_item sort_key @330-380
- enum_item FontBaseSize @385-390
- enum_item LineHeightBase @394-399
- function_item resolve @403-414
- enum_item ViewportVariant @418-427
- enum_item ViewportUnit @431-444
- struct_item NoCalcLength @451-454
- function_item new @484-486
- function_item length_unit @490-492
- function_item unitless_value @496-498
- function_item unit @502-504
- function_item canonical_unit @507-513
- function_item to @516-529
- function_item is_negative @532-534
- function_item is_zero @537-539
- function_item is_infinite @542-544
- function_item is_nan @547-549
- function_item should_zoom_text @555-557
- function_item sort_key @561-563
- function_item parse_dimension_with_flags @566-574
- function_item parse_dimension_with_context @577-583
- function_item try_op @585-597
- function_item map @599-605
- function_item to_computed_pixel_length_without_context @609-611
- function_item to_computed_pixel_length_with_font_metrics @617-642
- function_item from_px @646-648
- function_item to_px_if_absolute @652-664
- function_item from_em @668-670
- function_item from_servo_character_width @674-676
- function_item font_relative_to_computed_value @680-689
- function_item reference_font_size_and_length @691-892
- function_item query_font_metrics @697-704
- function_item ex_size @706-718
- function_item ch_size @720-735
- function_item cap_size @737-745
- function_item ic_size @747-759
- function_item viewport_percentage_to_computed_value @896-953
- function_item container_relative_to_computed_value @957-985
- function_item servo_character_width_to_computed_value @988-999
- function_item to_computed_value_with_base_size @1002-1031
- function_item to_computed_value @1038-1044
- function_item from_computed_value @1047-1049
- function_item to_css @1053-1063
- function_item to_typed @1067-1077
- function_item partial_cmp @1083-1092
- function_item zero @1096-1098
- function_item is_zero @1100-1102
- struct_item Length @1112-1112
- function_item to_css @1115-1123
- function_item to_typed @1127-1132
- function_item from @1139-1141
- function_item new @1147-1149
- function_item new_calc @1153-1155
- function_item is_calc @1159-1161
- function_item parse_internal @1164-1203
- function_item parse_non_negative @1207-1212
- function_item parse_non_negative_quirky @1216-1227
- function_item from_px @1231-1233
- function_item to_computed_pixel_length_without_context @1236-1243
- function_item to_computed_pixel_length_with_font_metrics @1247-1258
- function_item parse @1262-1264
- function_item to_computed_value @1271-1287
- function_item from_computed_value @1290-1292
- function_item zero @1296-1298
- function_item is_zero @1300-1307
- function_item parse_quirky @1312-1318
- function_item parse @1326-1328
- function_item from @1333-1335
- function_item from @1340-1342
- function_item from_px @1348-1350
- function_item parse_quirky @1354-1364
- enum_item LengthPercentage @1373-1377
- function_item from @1380-1387
- function_item from @1392-1394
- function_item from @1399-1401
- function_item parse @1406-1408
- function_item zero_percent @1414-1416
- function_item hundred_percent @1420-1422
- function_item parse_internal @1424-1471
- function_item parse_quirky @1476-1488
- function_item parse_quirky_with_anchor_size_function @1493-1505
- function_item parse_quirky_with_anchor_functions @1510-1522
- function_item parse_non_negative_with_anchor_size @1526-1538
- function_item parse_non_negative @1545-1550
- function_item parse_non_negative_quirky @1554-1566
- function_item compute_without_context @1572-1584
- function_item zero @1588-1590
- function_item is_zero @1592-1598
- function_item is_zero_no_percent @1602-1607
- trait_item EqualsPercentage @1611-1615
- function_signature_item equals_percentage @1614-1614
- function_item equals_percentage @1618-1623
- function_item zero_percent @1632-1634
- function_item parse_quirky @1639-1647
- function_item zero_percent @1657-1661
- function_item parse_quirky @1666-1674
- function_item from @1686-1688
- function_item parse @1693-1695
- function_item zero_percent @1701-1703
- function_item parse_quirky @1708-1714
- function_item parse_non_negative_with_anchor_size @1719-1726
- function_item parse_quirky @1740-1748
- function_item parse @1761-1763
- function_item is_webkit_fill_available_enabled_in_width_and_height @1787-1789
- function_item is_webkit_fill_available_enabled_in_all_size_properties @1791-1797
- function_item is_stretch_enabled @1799-1801
- function_item is_fit_content_function_enabled @1803-1805
- enum_item ParseAnchorFunctions @1823-1826
- function_item parse_quirky @1830-1843
- function_item parse_size_for_flex_basis_width @1846-1857
- function_item parse_quirky_internal @1863-1895
- function_item parse_size_for_width_or_height_quirky @1902-1915
- function_item parse_size_for_width_or_height @1922-1934
- function_item zero_percent @1938-1940
- function_item parse @1947-1949
- function_item parse_quirky @1954-1985
- function_item parse_quirky @1998-2021
- function_item parse @2025-2027

### servo/components/style/values/specified/list.rs

Blob: `50305be32d603f8c53355ba5ba73566386e5a612`. Grammar: rust. Status: syntax-clean.

- struct_item ListStyleType @29-29
- function_item disc @34-36
- function_item none @40-42
- function_item is_name @46-48
- function_item from_gecko_keyword @55-74
- function_item is_bullet @78-80
- function_item parse @84-87
- struct_item QuotePair @103-109
- struct_item QuoteList @125-129
- enum_item Quotes @147-152
- function_item parse @155-189
- enum_item ListStylePosition @214-217

### servo/components/style/values/specified/mod.rs

Blob: `326196930927b1e444dcb6ab76eb7c2f4774916c`. Grammar: rust. Status: syntax-clean.

- mod_item align @141-141
- mod_item angle @142-142
- mod_item animation @143-143
- mod_item background @144-144
- mod_item basic_shape @145-145
- mod_item border @146-146
- mod_item box_ @148-148
- mod_item calc @149-149
- mod_item color @150-150
- mod_item column @151-151
- mod_item corner_shape @152-152
- mod_item counters @153-153
- mod_item easing @154-154
- mod_item effects @155-155
- mod_item flex @156-156
- mod_item font @157-157
- mod_item frequency @158-158
- mod_item grid @159-159
- mod_item image @160-160
- mod_item intersection_observer @161-161
- mod_item length @162-162
- mod_item list @163-163
- mod_item motion @164-164
- mod_item number @165-165
- mod_item outline @166-166
- mod_item page @167-167
- mod_item param @168-168
- mod_item percentage @169-169
- mod_item position @170-170
- mod_item random @171-171
- mod_item ratio @172-172
- mod_item rect @173-173
- mod_item resolution @174-174
- mod_item source_size_list @175-175
- mod_item svg @176-176
- mod_item svg_path @177-177
- mod_item table @178-178
- mod_item text @179-179
- mod_item time @180-180
- mod_item transform @181-181
- mod_item tree_counting @182-182
- mod_item ui @183-183
- mod_item url @184-184
- enum_item AngleOrPercentage @190-193
- function_item parse_internal @196-206
- function_item parse_with_unitless @210-215
- function_item parse @219-221
- enum_item NumberOrPercentage @232-235
- function_item parse_with_clamping_mode @238-256
- function_item parse_non_negative @259-264
- function_item to_percentage @267-272
- function_item to_number @275-280
- function_item as_percentage @283-288
- function_item into_simplified_number @292-297
- function_item to_computed_value_without_context @300-309
- function_item parse @313-315
- function_item hundred_percent @324-326
- function_item new_number @330-332
- function_item parse @336-340
- struct_item Opacity @345-345
- function_item parse @351-355
- function_item to_computed_value @362-371
- function_item from_computed_value @374-378
- function_item parse @404-406
- function_item parse_quirky @411-451
- function_item parse_argument @418-424
- function_item parse_quirky @459-469
- enum_item AllowQuirks @474-481
- function_item allowed @485-491
- enum_item ParsedNamespace @496-501
- function_item parse @506-515
- function_item default @519-521
- function_item parse_namespace @525-548

### servo/components/style/values/specified/motion.rs

Blob: `db8a19f78b40362b33f6ff1f24bc468800938d87`. Grammar: rust. Status: syntax-clean.

- enum_item CoordBox @58-65
- function_item is_default @70-72
- function_item parse @76-79
- function_item parse_function_arguments @84-139
- function_item parse @143-160
- function_item parse @164-199
- enum_item OffsetRotateDirection @207-215
- function_item is_none @220-222
- function_item direction_specified_and_angle_is_zero @226-228
- struct_item OffsetRotate @235-246
- function_item auto @251-256
- function_item is_auto @260-262
- function_item parse @266-283
- function_item to_computed_value @290-303
- function_item from_computed_value @306-315

### servo/components/style/values/specified/number.rs

Blob: `99f07bd787b41c5190d6ef3991e6b5c2803d4e8b`. Grammar: rust. Status: syntax-clean.

- function_item parse_number_with_clamping_mode @29-52
- function_item parse_integer_with_clamping_mode @55-78
- struct_item NoCalcNumber @83-83
- function_item new @88-90
- function_item value @94-96
- function_item get @100-102
- function_item unit @105-107
- function_item canonical_unit @110-112
- function_item to @115-120
- function_item eq @124-126
- function_item partial_cmp @130-132
- function_item to_css @136-141
- function_item to_computed_value @147-149
- function_item from_computed_value @151-153
- struct_item Number @160-160
- function_item to_css @163-171
- function_item to_typed @175-180
- function_item parse @184-191
- function_item partial_cmp @195-197
- function_item new @203-205
- function_item new_calc @209-211
- function_item to_percentage @214-224
- function_item get @230-235
- function_item resolve @239-244
- function_item as_calc @248-253
- function_item parse_non_negative @256-266
- function_item parse_at_least_one @269-279
- function_item clamp_to_one @283-290
- function_item to_computed_value @297-311
- function_item from_computed_value @314-316
- function_item is_parallel_to @320-331
- function_item zero @338-340
- function_item is_zero @344-346
- function_item parse @353-361
- function_item one @366-368
- function_item is_one @372-374
- function_item new @379-381
- function_item get @385-387
- function_item as_calc @391-393
- function_item parse @401-403
- function_item parse @410-418
- struct_item Integer @428-428
- function_item zero @432-434
- function_item is_zero @438-440
- function_item one @445-447
- function_item is_one @451-453
- function_item eq @457-459
- function_item new @464-466
- function_item get @471-476
- function_item resolve @480-488
- function_item ensure_clamping_mode @491-503
- function_item parse @507-514
- function_item parse_non_negative @519-529
- function_item parse_positive @532-542
- function_item to_css @546-554
- function_item to_typed @558-563
- function_item to_computed_value @570-585
- function_item from_computed_value @588-590
- function_item parse @600-602

### servo/components/style/values/specified/outline.rs

Blob: `9796a3c7707fe9bb0bb55a782f009c66779b20b7`. Grammar: rust. Status: syntax-clean.

- enum_item OutlineStyle @32-37
- function_item none @42-44
- function_item none_or_hidden @48-53
- function_item parse @57-68

### servo/components/style/values/specified/page.rs

Blob: `b872ee50e89d0182ea02044e244f65b96fd25d98`. Grammar: rust. Status: syntax-clean.

- function_item parse @22-46
- enum_item PageName @65-70
- function_item parse @73-79
- function_item auto @85-87
- function_item is_auto @91-93

### servo/components/style/values/specified/param.rs

Blob: `4191154d2799c392db44f90b98c09a12be52fd89`. Grammar: rust. Status: syntax-clean.

- struct_item LinkParamValue @30-30
- struct_item LinkParam @44-49
- struct_item LinkParameters @70-75
- function_item none @79-81
- function_item parse @85-104
- function_item to_css @108-120

### servo/components/style/values/specified/percentage.rs

Blob: `c5fd4efc0bb102aae5f6640b2ba9d8dc2e83d1ca`. Grammar: rust. Status: syntax-clean.

- struct_item NoCalcPercentage @39-39
- function_item to_css @44-49
- function_item to_typed @53-55
- function_item new @60-62
- function_item zero @66-68
- function_item hundred @72-74
- function_item get @78-80
- function_item unit @83-85
- function_item canonical_unit @88-90
- function_item to @94-99
- function_item to_computed_value @105-107
- function_item from_computed_value @109-111
- struct_item Percentage @116-116
- function_item to_css @119-127
- function_item to_typed @131-136
- function_item new @141-143
- function_item new_calc @147-149
- function_item zero @153-155
- function_item hundred @159-161
- function_item is_calc @165-167
- function_item get @173-178
- function_item resolve @184-189
- function_item to_number @192-202
- function_item to_length_percentage @205-210
- function_item reverse @215-234
- function_item parse_with_clamping_mode @237-255
- function_item parse_non_negative @258-263
- function_item parse_zero_to_a_hundred @267-272
- function_item clamp_to_hundred @276-283
- function_item parse @288-290
- function_item to_computed_value @297-314
- function_item from_computed_value @317-319
- trait_item ToPercentage @325-333
- function_item is_calc @327-329
- function_signature_item to_percentage @332-332
- function_item is_calc @336-338
- function_item to_percentage @340-342
- function_item parse @350-352
- function_item compute @359-364

### servo/components/style/values/specified/position.rs

Blob: `d11837f210916382aeb69ab53386aec40fbbbd86`. Grammar: rust. Status: syntax-clean.

- enum_item PositionComponent @56-63
- enum_item HorizontalPositionKeyword @83-86
- enum_item VerticalPositionKeyword @106-109
- function_item parse @112-118
- function_item parse_three_value_quirky @123-202
- function_item center @206-208
- function_item is_three_value_syntax @212-214
- function_item to_css @218-240
- function_item parse @244-246
- function_item parse_quirky @251-272
- function_item is_center @276-286
- function_item zero @291-293
- function_item component_count @296-307
- function_item to_computed_value @313-328
- function_item from_computed_value @330-332
- function_item initial_specified_value @337-339
- struct_item AnchorNameIdent @359-364
- function_item none @368-370
- function_item parse @374-386
- function_item is_tree_scoped @390-392
- function_item none @400-402
- struct_item ScopedNameList @422-427
- function_item none @431-433
- function_item is_none @436-438
- function_item all @441-448
- function_item parse @452-468
- function_item is_tree_scoped @472-474
- function_item none @483-485
- function_item is_none @488-490
- enum_item PositionAnchorKeyword @509-518
- function_item is_tree_scoped @521-526
- function_item normal @534-536
- enum_item PositionTryFallbacksTryTacticKeyword @556-567
- struct_item PositionTryFallbacksTryTactic @587-589
- function_item parse @592-609
- function_item is_empty @615-617
- function_item iter @621-623
- struct_item DashedIdentAndOrTryTactic @640-645
- function_item parse @648-675
- enum_item PositionTryFallbacksItem @693-699
- struct_item PositionTryFallbacksList @718-722
- function_item is_tree_scoped @725-727
- function_item none @733-735
- function_item is_none @738-740
- function_item parse @744-756
- function_item none @764-766
- enum_item PositionTryOrder @787-799
- function_item normal @804-806
- function_item is_normal @809-811
- struct_item PositionVisibility @833-833
- function_item default @848-850
- function_item always @856-858
- enum_item PositionAreaType @865-880
- enum_item PositionAreaAxis @891-903
- function_item is_physical @907-909
- function_item is_flow_relative_direction @912-914
- function_item is_canonically_first @917-919
- function_item flip @922-927
- function_item to_logical @929-950
- enum_item PositionAreaTrack @957-970
- function_item flip @973-981
- function_item start @983-985
- enum_item PositionAreaKeyword @1019-1101
- function_item none @1106-1108
- function_item is_none @1111-1113
- function_item self_wm @1116-1118
- function_item axis @1121-1123
- function_item with_axis @1126-1128
- function_item with_inferred_axis @1131-1137
- function_item track @1140-1148
- function_item group_type @1150-1173
- function_item to_physical @1175-1223
- function_item flip_track @1225-1231
- function_item to_self_alignment @1240-1271
- struct_item PositionArea @1290-1296
- function_item none @1301-1306
- function_item is_none @1310-1312
- function_item parse_except_none @1315-1320
- function_item get_type @1323-1342
- function_item parse_internal @1344-1398
- function_item canonicalize_order @1400-1415
- function_item make_missing_second_explicit @1417-1430
- function_item to_physical @1433-1451
- function_item flip_logical_axis @1453-1459
- function_item flip_start @1461-1464
- function_item with_tactic @1467-1497
- function_item parse @1501-1503
- trait_item Side @1507-1513
- function_signature_item start @1509-1509
- function_signature_item is_start @1512-1512
- function_item start @1517-1519
- function_item is_start @1522-1524
- function_item start @1529-1531
- function_item is_start @1534-1536
- struct_item GridAutoFlow @1561-1561
- function_item validate_and_simplify @1575-1585
- function_item to_css @1589-1607
- function_item flex_wrap_balance_enabled @1612-1614
- struct_item FlexWrap @1641-1641
- function_item validate_and_simplify @1657-1669
- struct_item TemplateAreas @1685-1698
- struct_item TemplateAreasParser @1702-1708
- function_item try_parse_string @1712-1717
- function_item parse_string @1720-1802
- function_item finish @1805-1814
- function_item parse_internal @1818-1822
- function_item parse @1826-1829
- struct_item TemplateAreasArc @1845-1845
- function_item parse @1848-1851
- struct_item UnsignedRange @1867-1872
- struct_item NamedArea @1887-1894
- struct_item TemplateAreasTokenizer @1898-1898
- function_item next @1903-1919
- function_item is_name_code_point @1922-1929
- enum_item GridTemplateAreas @1951-1956
- function_item none @1961-1963
- function_item parse @1973-1994
- function_item from_mapped_ratio @1999-2009
- function_item parse_quirky @2019-2036
- function_item parse_as_anchor_function_fallback @2038-2048
- function_item parse_anchor_functions_quirky @2050-2070
- function_item parse @2074-2076
- function_item parse @2083-2110
- enum_item FlexDirection @2135-2140
- enum_item BoxSizing @2164-2167
- enum_item ObjectFit @2191-2197

### servo/components/style/values/specified/random.rs

Blob: `40d26145e6954d1f470c91891e5b9e78633ca3a8`. Grammar: rust. Status: syntax-clean.

- struct_item RandomUaIdent @29-29
- function_item ua_prefixed @32-51
- function_item from_property @54-56
- function_item from_property_and_index @61-65
- function_item empty @68-70
- function_item is_empty @73-75
- function_item parse @79-101
- struct_item RandomCacheKey @109-117
- function_item parse @120-163
- function_item to_css @167-182
- enum_item RandomKey @193-200
- function_item auto @205-220
- function_item parse @224-243
- function_item to_computed_value @249-254
- function_item from_computed_value @256-258
- function_item to_css @262-273

### servo/components/style/values/specified/ratio.rs

Blob: `a17fcf14d686abcb51cba89109b0b0ec122cea2b`. Grammar: rust. Status: syntax-clean.

- function_item parse @20-28

### servo/components/style/values/specified/rect.rs

Blob: `e0c5214743219c8638e1e4f7896b1bb9c3e6f9f1`. Grammar: rust. Status: syntax-clean.

- function_item to_typed @21-27

### servo/components/style/values/specified/resolution.rs

Blob: `d8afebee7a3d07d963a1bfebbf2ecf6b58e69cea`. Grammar: rust. Status: syntax-clean.

- enum_item ResolutionUnit @23-32
- function_item from_str @37-45
- function_item as_str @49-56
- struct_item NoCalcResolution @62-65
- function_item new @70-72
- function_item from_dppx @76-78
- function_item from_x @82-84
- function_item dppx @87-92
- function_item dpi @95-101
- function_item resolution_unit @105-107
- function_item parse_dimension @110-113
- function_item to_css @117-127
- struct_item Resolution @136-136
- function_item to_css @139-147
- function_item new @155-157
- function_item new_calc @161-163
- function_item from_dppx @167-169
- function_item from_x @173-175
- function_item is_calc @179-181
- function_item parse_dimension @184-186
- function_item to_computed_value @193-208
- function_item from_computed_value @211-213
- function_item parse @217-236

### servo/components/style/values/specified/source_size_list.rs

Blob: `6c35d59b6e6b8c1320dfd123865f56b6676ebefc`. Grammar: rust. Status: syntax-clean.

- struct_item SourceSize @24-27
- function_item parse @30-34
- struct_item SourceSizeList @41-44
- function_item empty @48-53
- function_item evaluate @56-79
- enum_item SourceSizeOrLength @82-85
- function_item parse @88-95
- function_item parse @102-134

### servo/components/style/values/specified/svg.rs

Blob: `68f595cbd2df127283f61ec568c6cc329b585d17`. Grammar: rust. Status: syntax-clean.

- function_item is_context_value_enabled @35-37
- function_item parse @63-78
- enum_item PaintOrder @87-96
- struct_item SVGPaintOrder @131-131
- function_item normal @135-137
- function_item order_at @140-148
- function_item parse @152-205
- function_item to_css @209-234
- struct_item ContextPropertyBits @252-252
- struct_item MozContextProperties @282-288
- function_item parse @291-335
- enum_item DProperty @361-368
- function_item none @373-375
- function_item parse @379-389
- struct_item VectorEffect @411-411
- function_item none @424-426
- enum_item TextAnchor @451-455
- enum_item ShapeRendering @479-484
- enum_item StrokeLinecap @508-512
- enum_item StrokeLinejoin @536-540
- enum_item MaskType @564-567
- enum_item MaskMode @591-595
- enum_item MaskComposite @619-624
- enum_item ColorInterpolation @648-652

### servo/components/style/values/specified/svg_path.rs

Blob: `fdcc8949edcff708dc6657bfb3666048095daa0f`. Grammar: rust. Status: syntax-clean.

- enum_item AllowEmpty @29-32
- struct_item SVGPathData @51-55
- function_item commands @60-62
- function_item normalize @66-75
- function_item parse @89-96
- function_item parse_bytes @103-117
- function_item to_css @120-135
- function_item to_css @140-145
- function_item parse @149-154
- function_item animate @158-171
- function_item compute_squared_distance @175-182
- struct_item PathTraversalState @198-203
- function_item normalize @212-403
- function_item to_css_for_svg @406-485
- function_item add @494-499
- function_item sub @505-510
- function_item mul @516-521
- function_item mul @527-529
- function_item div @535-540
- function_item to_abs @545-557
- function_item to_abs @562-568
- function_item to_abs @573-602
- function_item from @607-615
- function_item from @620-633
- function_item from @638-640
- function_item from @645-650
- function_item from @655-659
- function_item to_css @663-670
- struct_item PathParser @674-677
- function_item new @712-724
- function_item parse_subpath @727-764
- function_item parse_moveto @767-794
- function_item parse_closepath @797-800
- function_item parse_line_abs @803-805
- function_item parse_line_rel @808-810
- function_item parse_h_line_abs @813-815
- function_item parse_h_line_rel @818-820
- function_item parse_v_line_abs @823-825
- function_item parse_v_line_rel @828-830
- function_item parse_curve_abs @833-837
- function_item parse_curve_rel @840-844
- function_item parse_smooth_curve_abs @847-851
- function_item parse_smooth_curve_rel @854-858
- function_item parse_quadratic_bezier_curve_abs @861-865
- function_item parse_quadratic_bezier_curve_rel @868-872
- function_item parse_smooth_quadratic_bezier_curve_abs @875-877
- function_item parse_smooth_quadratic_bezier_curve_rel @880-882
- function_item parse_elliptical_arc_abs @885-894
- function_item parse_elliptical_arc_rel @897-906
- function_item arc_flag_parsers @909-925
- function_item parse_coord @929-934
- function_item parse_command_end_abs @937-942
- function_item parse_command_end_rel @945-950
- function_item parse_control_point_abs @953-961
- function_item parse_control_point_rel @964-972
- function_item parse_axis_end_abs @975-980
- function_item parse_axis_end_rel @983-988
- function_item parse_arc_radii @991-997
- function_item parse_number @1006-1088
- function_item skip_wsp @1092-1101
- function_item skip_comma_wsp @1105-1116

### servo/components/style/values/specified/table.rs

Blob: `31d9c7caa5571d9e6b54f20540cdb9ce2d7e0466`. Grammar: rust. Status: syntax-clean.

- enum_item CaptionSide @35-38
- enum_item BorderCollapse @62-65
- enum_item EmptyCells @89-92
- enum_item TableLayout @116-119

### servo/components/style/values/specified/text.rs

Blob: `234fcd5bde8bf5e2a274314bcc40f47a7a666761`. Grammar: rust. Status: syntax-clean.

- enum_item Spacing @33-38
- function_item parse @41-49
- struct_item LetterSpacing @56-56
- function_item to_computed_value @61-67
- function_item from_computed_value @69-76
- struct_item WordSpacing @83-83
- function_item to_computed_value @88-93
- function_item from_computed_value @95-99
- enum_item HyphenateCharacter @118-123
- function_item parse @129-144
- function_item parse @148-160
- enum_item TextOverflowSide @178-185
- struct_item TextOverflow @209-216
- function_item parse @219-236
- function_item get_initial_value @241-247
- function_item to_css @251-264
- struct_item TextDecorationLine @296-296
- function_item default @329-331
- function_item none @337-339
- enum_item TextTransformCase @357-368
- struct_item TextTransform @396-396
- function_item none @424-426
- function_item is_none @430-432
- function_item validate_mixed_flags @434-438
- function_item case @441-450
- enum_item TextAlignLast @473-481
- enum_item TextAlignKeyword @503-516
- enum_item TextAlign @533-553
- function_item to_computed_value @559-597
- function_item from_computed_value @600-602
- function_item fill_mode_is_default_and_shape_exists @605-610
- enum_item TextEmphasisStyle @618-629
- enum_item TextEmphasisFillMode @646-651
- function_item is_filled @656-658
- enum_item TextEmphasisShapeKeyword @677-688
- function_item to_computed_value @694-727
- function_item from_computed_value @730-741
- function_item parse @745-776
- struct_item TextEmphasisPosition @803-803
- function_item validate_and_simplify @820-833
- enum_item WordBreak @854-864
- enum_item TextJustify @884-892
- enum_item MozControlCharacterVisibility @912-915
- function_item default @919-925
- enum_item LineBreak @946-952
- enum_item OverflowWrap @972-976
- function_item parse @985-1023
- enum_item TextDecorationSkipInk @1048-1052
- function_item auto @1060-1062
- function_item is_auto @1066-1068
- function_item auto @1077-1079
- function_item is_auto @1083-1085
- function_item parse_inset_endpoint @1088-1097
- function_item parse @1100-1110
- struct_item TextUnderlinePosition @1137-1137
- function_item validate_mixed_flags @1154-1164
- function_item to_css @1168-1196
- enum_item RubyPosition @1214-1219
- function_item parse @1222-1247
- function_item to_css @1251-1261
- function_item collect_completion_keywords @1265-1267
- struct_item TextAutospace @1306-1306
- enum_item TextEdgeKeyword @1368-1381
- function_item is_valid_for_over @1384-1393
- function_item is_valid_for_under @1395-1403
- struct_item TextEdge @1430-1435
- function_item parse @1438-1470
- function_item to_css @1474-1492
- enum_item TextBoxEdge @1515-1520
- struct_item TextBoxTrim @1543-1543
- function_item none @1560-1562
- enum_item Hyphens @1587-1591
- enum_item TextSizeAdjust @1615-1618
- enum_item RubyAlign @1642-1647
- enum_item TextCombineUpright @1671-1674
- enum_item TextRendering @1698-1703
- enum_item TextSecurity @1727-1732
- enum_item TextWrapMode @1756-1759
- enum_item TextWrapStyle @1783-1787
- enum_item UnicodeBidi @1811-1818
- enum_item TextDecorationStyle @1842-1852
- enum_item WhiteSpaceCollapse @1879-1888

### servo/components/style/values/specified/time.rs

Blob: `5525842f5ddb87d62aa6d7f1110751e733cafd0d`. Grammar: rust. Status: syntax-clean.

- enum_item TimeUnit @27-32
- function_item from_str @37-43
- function_item as_str @47-52
- struct_item NoCalcTime @58-61
- function_item new @66-68
- function_item from_seconds @72-74
- function_item seconds @78-83
- function_item time_unit @87-89
- function_item unit @93-95
- function_item unitless_value @99-101
- function_item canonical_unit @104-106
- function_item to @109-116
- function_item parse_dimension @119-122
- function_item to_css @126-136
- function_item to_computed_value @142-144
- function_item from_computed_value @146-148
- function_item to_typed @152-163
- struct_item Time @170-170
- function_item to_css @173-181
- function_item to_typed @185-190
- function_item new @198-200
- function_item new_calc @204-206
- function_item from_seconds @210-212
- function_item is_calc @216-218
- function_item parse_with_clamping_mode @220-254
- function_item parse_non_negative @257-262
- function_item zero @267-269
- function_item is_zero @272-278
- function_item to_computed_value @284-302
- function_item from_computed_value @304-306
- function_item parse @310-312

### servo/components/style/values/specified/transform.rs

Blob: `34b308b9ae9699b33513ca147b767d7fd5745fd3`. Grammar: rust. Status: syntax-clean.

- function_item all_transform_boxes_are_enabled @41-43
- function_item all_transform_boxes_are_enabled @46-48
- enum_item TransformBox @74-82
- function_item initial_value @87-93
- function_item zero_zero @96-102
- enum_item AllowUnitlessPerspective @109-112
- function_item parse_legacy @119-124
- function_item parse_internal @130-349
- function_item parse @353-355
- enum_item OriginComponent @360-367
- function_item parse @370-420
- function_item to_computed_value @429-440
- function_item from_computed_value @442-444
- function_item zero @449-451
- function_item parse @458-497
- function_item parse @504-530
- struct_item ScaleFactor @535-535
- function_item one @538-540
- function_item parse @547-551
- function_item to_computed_value @557-559
- function_item from_computed_value @561-565
- function_item to_f32 @569-574
- function_item to_f64 @576-578
- function_item parse @585-598

### servo/components/style/values/specified/tree_counting.rs

Blob: `e863b1cff51eabc2b886b2f01347ff651f033a30`. Grammar: rust. Status: syntax-clean.

- enum_item TreeCountingFunction @15-22
- function_item to_computed_value @26-31

### servo/components/style/values/specified/ui.rs

Blob: `064adf8f4b5ca034532bd3f1bc6eebe2dfd38312`. Grammar: rust. Status: syntax-clean.

- function_item parse @27-40
- function_item parse @44-64
- function_item collect_completion_keywords @70-72
- struct_item BoolInteger @89-89
- function_item zero @94-96
- function_item parse @100-107
- function_item to_css @111-116
- function_item parse @123-131
- enum_item UserSelect @154-163
- enum_item CursorKind @186-227
- enum_item MozTheme @247-252
- enum_item PointerEvents @274-293
- enum_item Inert @315-318
- enum_item UserFocus @340-344
- enum_item ImeMode @368-374
- enum_item ScrollbarWidth @398-402
- enum_item WindowDragging @426-430
- enum_item WindowShadow @454-457
- enum_item FieldSizing @481-484

### servo/components/style/values/specified/url.rs

Blob: `80b68c300608ada691710bb1575a3d652d29b81d`. Grammar: rust. Status: syntax-clean.


### servo/components/style/values/tagged_numeric.rs

Blob: `f7297d4028feeb1a9f5e040eeba16ca31ee61574`. Grammar: rust. Status: syntax-clean.

- struct_item BoxedVariant @20-24
- struct_item BoxedVariant @29-32
- function_item clone @36-38
- struct_item TagVariant @47-49
- struct_item InlineVariant @54-58
- struct_item NumericUnion @71-71
- function_item is_inline @78-80
- function_item is_boxed @83-85
- function_item boxed_ptr @88-100
- function_item unpack_mut @103-111
- function_item unpack @114-122
- function_item extract @125-135
- function_item inline @138-146
- function_item boxed @149-171
- function_item drop @175-179
- function_item clone @183-188
- function_item size_of @192-197
- function_item to_shmem @201-212
- function_item fmt @218-220
- function_item eq @224-226
- enum_item Unpacked @231-236
- enum_item Extracted @240-245
- enum_item UnpackedMut @248-253

### servo/components/style_derive/animate.rs

Blob: `c87fae295520124fe3274c6d61ba16da7257fe47`. Grammar: rust. Status: syntax-clean.

- function_item derive @12-67
- function_item derive_variant_arm @69-116
- struct_item AnimationInputAttrs @120-122
- struct_item AnimationVariantAttrs @126-131
- struct_item AnimationFieldAttrs @135-138

### servo/components/style_derive/cg.rs

Blob: `1add5f3b538e32082dc50803ef6568beb20572b5`. Grammar: rust. Status: syntax-clean.

- function_item propagate_clauses_to_output_type @35-80
- function_item add_predicate @82-87
- function_item fmap_match @89-94
- function_item fmap2_match @96-129
- function_item fmap_trait_output @131-163
- function_item map_type_params @165-236
- function_item map_type_params_in_path @238-283
- function_item path_to_ident @285-299
- function_item parse_field_attrs @301-309
- function_item parse_input_attrs @311-319
- function_item parse_variant_attrs_from_ast @321-332
- function_item parse_variant_attrs @334-342
- function_item ref_pattern @344-354
- function_item value @356-366
- function_item to_css_identifier @372-390
- function_item to_scream_case @393-395
- function_item split_camel_segment @398-409

### servo/components/style_derive/compute_squared_distance.rs

Blob: `a4c46322dd9553e1461824de93d96b19cf1b056a`. Grammar: rust. Status: syntax-clean.

- function_item derive @11-68
- function_item derive_variant_arm @70-122
- struct_item DistanceFieldAttrs @126-128

### servo/components/style_derive/lib.rs

Blob: `7efa429c99247eae8d9636da53209d271a376787`. Grammar: rust. Status: syntax-clean.

- mod_item animate @19-19
- mod_item cg @20-20
- mod_item compute_squared_distance @21-21
- mod_item parse @22-22
- mod_item specified_value_info @23-23
- mod_item to_animated_value @24-24
- mod_item to_animated_zero @25-25
- mod_item to_computed_value @26-26
- mod_item to_css @27-27
- mod_item to_resolved_value @28-28
- mod_item to_typed @29-29
- function_item derive_animate @32-35
- function_item derive_compute_squared_distance @38-41
- function_item derive_to_animated_value @44-47
- function_item derive_parse @50-53
- function_item derive_to_animated_zero @56-59
- function_item derive_to_computed_value @62-65
- function_item derive_to_resolved_value @68-71
- function_item derive_to_css @74-77
- function_item derive_specified_value_info @80-83
- function_item derive_to_typed @86-89

### servo/components/style_derive/parse.rs

Blob: `ef0a527ca22c9a6de45b6e772b1932d2338ad6de`. Grammar: rust. Status: syntax-clean.

- struct_item ParseVariantAttrs @14-18
- struct_item ParseFieldAttrs @22-24
- function_item parse_bitflags @26-88
- function_item parse_non_keyword_variant @90-169
- function_item derive @171-327

### servo/components/style_derive/specified_value_info.rs

Blob: `c3351fbf99a2a6844afe131cd329d7def5728b37`. Grammar: rust. Status: syntax-clean.

- function_item derive @12-135
- function_item derive_struct_fields @139-174
- struct_item ValueInfoInputAttrs @178-181
- struct_item ValueInfoVariantAttrs @185-189
- struct_item ValueInfoFieldAttrs @193-196

### servo/components/style_derive/to_animated_value.rs

Blob: `5bcbfeae3cf80cb2c2a3b33cef975c407108ecea`. Grammar: rust. Status: syntax-clean.

- function_item derive @11-42

### servo/components/style_derive/to_animated_zero.rs

Blob: `4cc98f38d520c8a9eaefe455b3bf4aaa87975315`. Grammar: rust. Status: syntax-clean.

- function_item derive @10-63

### servo/components/style_derive/to_computed_value.rs

Blob: `0faa0de20a32f03cb348a9c9b99b72a3ef07d15c`. Grammar: rust. Status: syntax-clean.

- function_item derive_to_value @11-159
- function_item derive @161-193
- struct_item ToValueAttrs @196-199
- struct_item ComputedValueAttrs @203-206

### servo/components/style_derive/to_css.rs

Blob: `d565ec1fa7b7e8102baa5b3dc4306016b8cfe9ae`. Grammar: rust. Status: syntax-clean.

- function_item derive_bitflags @12-78
- function_item derive @80-148
- function_item derive_variant_arm @150-184
- function_item derive_variant_fields_expr @186-248
- function_item derive_single_field_expr @250-313
- struct_item CssBitflagAttrs @317-327
- function_item names @331-339
- function_item single_flags @341-343
- function_item mixed_flags @345-347
- struct_item CssInputAttrs @352-359
- struct_item CssVariantAttrs @363-371
- struct_item CssFieldAttrs @375-383

### servo/components/style_derive/to_resolved_value.rs

Blob: `9cea28f7ca50957d6f734f3b6a256bca72578e24`. Grammar: rust. Status: syntax-clean.

- function_item derive @11-45
- struct_item ResolvedValueAttrs @49-52

### servo/components/style_derive/to_typed.rs

Blob: `b1d275a23131078bd0ebf26699764190e50ce07b`. Grammar: rust. Status: syntax-clean.

- function_item derive @103-213
- function_item derive_bitflags @226-301
- function_item derive_variant_arm @320-377
- function_item derive_variant_fields_expr @395-457
- function_item derive_single_field_expr @476-588
- function_item field_generic_arguments @607-635
- struct_item TypedInputAttrs @639-666
- struct_item TypedVariantAttrs @670-703
- struct_item TypedFieldAttrs @707-720

### servo/components/style_traits/arc_slice.rs

Blob: `f8dcf9ff590f0c18f06223da82f92fc1bb5577b6`. Grammar: rust. Status: syntax-clean.

- struct_item ArcSlice @33-33
- function_item deref @39-42
- function_item clone @46-48
- function_item default @57-68
- function_item serialize @72-77
- function_item deserialize @81-87
- function_item from_iter @95-100
- function_item from_iter_leaked @106-110
- function_item forget @115-119
- function_item leaked_empty_ptr @124-129
- function_item is_unique @132-134
- function_item unconditional_size_of @139-145
- function_item hash @149-151
- struct_item ForgottenArcSlicePtr @159-159

### servo/components/style_traits/dom.rs

Blob: `18f42113dc684d0e343def6d145f4d0270cf6c08`. Grammar: rust. Status: syntax-clean.

- struct_item OpaqueNode @17-17
- function_item id @22-24

### servo/components/style_traits/lib.rs

Blob: `e621de27056bbfed4ef253c61b47e17d37e75ace`. Grammar: rust. Status: syntax-clean.

- enum_item DevicePixel @31-31
- struct_item PinchZoomFactor @35-35
- function_item new @39-41
- function_item get @44-46
- enum_item CSSPixel @59-59
- mod_item arc_slice @67-67
- mod_item dom @68-68
- mod_item specified_value_info @69-69
- mod_item values @71-71
- mod_item owned_array @72-72
- mod_item owned_slice @73-73
- mod_item owned_str @74-74
- enum_item StyleParseErrorKind @87-142
- function_item from @145-147
- enum_item PropertySyntaxParseError @152-178
- enum_item PropertyInheritsParseError @182-191
- function_item allows_unitless_lengths @223-225
- function_item allows_all_numeric_values @229-231
- function_item allows_computational_dependence @235-237
- function_item allows_unitless_zero_lengths @241-243
- trait_item SpeculativePainter @248-255
- function_signature_item speculatively_draw_a_paint_image @250-254

### servo/components/style_traits/owned_array.rs

Blob: `ffd9e89eed4f2d1f6af002e0e58429459953584c`. Grammar: rust. Status: syntax-clean.

- struct_item OwnedArray @48-51
- function_item drop @55-59
- function_item clone @67-69
- function_item fmt @73-75
- function_item eq @79-81
- function_item into_box @89-93
- function_item into_array @97-99
- function_item deref @106-108
- function_item deref_mut @113-115
- function_item from @120-122
- function_item from @127-133
- function_item shallow_size_of @137-139
- function_item size_of @143-145
- function_item to_shmem @149-156

### servo/components/style_traits/owned_slice.rs

Blob: `84c45cd844b06ebaee80d0c280611369306291d2`. Grammar: rust. Status: syntax-clean.

- struct_item OwnedSlice @35-39
- function_item default @43-49
- function_item drop @54-58
- function_item clone @66-68
- function_item fmt @72-74
- function_item eq @78-80
- function_item into_box @88-90
- function_item into_vec @94-98
- function_item from_slice @102-107
- function_item into_iter @115-117
- function_item deref @124-126
- function_item deref_mut @131-133
- function_item from @138-147
- function_item from @152-154
- function_item shallow_size_of @158-160
- function_item size_of @164-166
- function_item to_shmem @170-175
- function_item from_iter @180-182
- function_item serialize @186-191
- function_item deserialize @195-201
- function_item hash @205-207

### servo/components/style_traits/owned_str.rs

Blob: `3537fbf393bc4085582923432158364e9a0bc100`. Grammar: rust. Status: syntax-clean.

- struct_item OwnedStr @17-17
- function_item fmt @20-22
- function_item deref @29-31
- function_item deref_mut @36-38
- function_item into_box @44-46
- function_item into_string @50-52
- function_item from @57-59
- function_item from @64-66
- function_item from @71-73
- function_item from @78-80

### servo/components/style_traits/specified_value_info.rs

Blob: `89ded9a74ce57a6d5182981b9d84c0ffd3078c8e`. Grammar: rust. Status: syntax-clean.

- mod_item CssType @21-28
- trait_item SpecifiedValueInfo @64-79
- function_item collect_completion_keywords @78-78
- function_item collect_completion_keywords @100-102
- function_item collect_completion_keywords @107-109
- function_item collect_completion_keywords @138-141

### servo/components/style_traits/values.rs

Blob: `7bb5a11704705dda2e2355e0b3b846fc798b468d`. Grammar: rust. Status: syntax-clean.

- trait_item ToCss @79-104
- function_signature_item to_css @81-83
- function_item to_css_string @89-93
- function_item to_css_cssstring @99-103
- function_item to_css @110-115
- function_item to_css @120-125
- function_item to_css @130-135
- function_item to_css @140-145
- function_item to_css @153-158
- function_item to_css @163-168
- struct_item CssWriter @175-178
- function_item new @186-191
- function_item write_str @199-211
- function_item write_char @214-222
- struct_item SequenceWriter @249-252
- function_item has_written @259-262
- function_item new @266-272
- function_item write_item @276-326
- function_item before @283-295
- function_item after @296-320
- function_item item @335-340
- function_item raw_item @347-349
- struct_item Comma @355-355
- struct_item Space @360-360
- struct_item CommaWithSpace @366-366
- trait_item Separator @369-384
- function_signature_item separator @371-371
- function_signature_item parse @381-383
- function_item separator @387-389
- function_item parse @391-396
- function_item separator @400-402
- function_item parse @404-418
- function_item separator @422-424
- function_item parse @426-445
- trait_item OneOrMoreSeparated @450-453
- function_item to_css @463-474
- function_item to_css @481-486
- function_item to_css @493-498
- function_item to_css @502-508
- mod_item specified @534-590
- enum_item AllowedNumericType @552-562
- function_item is_ok @567-577
- function_item clamp @581-588

### servo/components/to_shmem/lib.rs

Blob: `1506d8cb5218058ef91a351e285f28f8e69b0ab1`. Grammar: rust. Status: syntax-clean.

- struct_item SharedMemoryBuilder @38-52
- function_item padding_needed_for @56-58
- function_item padded_size @61-63
- function_item new @71-79
- function_item len @83-85
- function_item is_empty @89-91
- function_item write @100-115
- function_item alloc_value @121-123
- function_item alloc_array @129-138
- function_item alloc @144-162
- trait_item ToShmem @166-180
- function_signature_item to_shmem @179-179
- function_item to_shmem @217-219
- function_item to_shmem @223-228
- function_item to_shmem @232-237
- function_item to_shmem @241-245
- function_item to_shmem @249-263
- function_item to_shmem_slice_ptr @272-291
- function_item to_shmem_slice @299-308
- function_item to_shmem @311-316
- function_item to_shmem @320-332
- function_item to_shmem @336-350
- function_item to_shmem @354-366
- function_item to_shmem @370-376
- function_item to_shmem @383-390
- function_item to_shmem @394-401
- function_item to_shmem @406-423
- function_item to_shmem @432-443
- function_item to_shmem @447-475
- function_item to_shmem @479-512
- function_item to_shmem @517-569
- function_item to_shmem @574-595
- function_item to_shmem @600-609
- function_item to_shmem @613-616
- function_item to_shmem @627-632

### servo/components/to_shmem_derive/lib.rs

Blob: `0b1a3f028f80d690f9c2a38de2ab1cd6f5598786`. Grammar: rust. Status: syntax-clean.

- mod_item to_shmem @9-9
- mod_item util @10-10
- function_item derive_to_shmem @13-16

### servo/components/to_shmem_derive/to_shmem.rs

Blob: `3d38e568b8efa61e7dd755141fbbeba45d3f48f5`. Grammar: rust. Status: syntax-clean.

- function_item derive @12-68
- struct_item ShmemInputAttrs @72-74
- struct_item ShmemFieldAttrs @78-80

### servo/components/to_shmem_derive/util.rs

Blob: `df7335493184635354635005b9543e846c62b311`. Grammar: rust. Status: syntax-clean.

- function_item parse_input_attrs @11-19
- function_item parse_field_attrs @21-29
- function_item add_predicate @31-36
- function_item fmap2_match @38-71
- function_item value @73-80

### servo/ports/geckolib/error_reporter.rs

Blob: `8b7bceaab4ff9bd9d4679c5c73012ab2fd718415`. Grammar: rust. Status: syntax-clean.

- struct_item ErrorReporter @27-30
- function_item new @35-57
- enum_item Action @61-65
- trait_item ErrorHelpers @67-72
- function_signature_item error_data @68-68
- function_signature_item error_params @69-69
- function_signature_item selectors @70-70
- function_signature_item to_gecko_message @71-71
- struct_item ErrorParams @75-78
- function_item needs_escape @80-83
- function_item snippet_of @87-101
- function_item extract_error_params @105-118
- function_item error_data @121-152
- function_item error_params @154-159
- function_item selectors @161-166
- function_item to_gecko_message @168-383
- function_item report @387-433
- function_item report_error @437-444

### servo/ports/geckolib/glue.rs

Blob: `d10c163b81a23566fb07de299c9e97b5aa5976ee`. Grammar: rust. Status: syntax-clean.

- trait_item ClosureHelper @173-175
- function_signature_item invoke @174-174
- function_item invoke @184-192
- function_item Servo_Initialize @208-228
- function_item Servo_Shutdown @231-238
- function_item dummy_url_data @241-243
- function_item dummy_chrome_url_data @246-250
- function_item is_main_thread @253-255
- function_item is_dom_worker_thread @258-260
- function_item is_in_servo_traversal @268-270
- function_item create_shared_context @272-288
- function_item traverse_subtree @290-325
- function_item Servo_TraverseSubtree @332-409
- function_item Servo_MaybeGCRuleTree @414-417
- function_item Servo_AnimationValues_Interpolate @420-430
- function_item Servo_AnimationValues_IsInterpolable @433-438
- function_item Servo_AnimationValues_Add @441-450
- function_item Servo_AnimationValues_Accumulate @453-463
- function_item Servo_AnimationValues_GetZeroValue @466-474
- function_item Servo_AnimationValues_ComputeDistance @477-484
- function_item composite_endpoint @491-510
- function_item accumulate_endpoint @514-535
- function_item compose_animation_segment @541-620
- function_item Servo_ComposeAnimationSegment @623-641
- function_item Servo_AnimationCompose @644-709
- function_item Servo_AnimationValue_Serialize @734-750
- function_item Servo_AnimationValue_Dump @754-756
- function_item Servo_AnimationValue_GetColor @759-768
- function_item Servo_AnimationValue_IsCurrentColor @771-779
- function_item Servo_AnimationValue_GetOpacity @782-788
- function_item Servo_AnimationValue_Opacity @791-793
- function_item Servo_AnimationValue_Color @796-813
- function_item Servo_AnimationValue_GetScale @816-823
- function_item Servo_AnimationValue_GetTranslate @826-833
- function_item Servo_AnimationValue_GetRotate @836-843
- function_item Servo_AnimationValue_GetTransform @846-853
- function_item Servo_AnimationValue_GetOffsetPath @856-867
- function_item Servo_AnimationValue_GetOffsetDistance @870-877
- function_item Servo_AnimationValue_GetOffsetRotate @880-887
- function_item Servo_AnimationValue_GetOffsetAnchor @890-897
- function_item Servo_AnimationValue_GetOffsetPosition @900-907
- function_item Servo_AnimationValue_IsOffsetPathUrl @910-918
- function_item Servo_AnimationValue_Rotate @921-925
- function_item Servo_AnimationValue_Translate @928-932
- function_item Servo_AnimationValue_Scale @935-937
- function_item Servo_AnimationValue_Transform @940-944
- function_item Servo_AnimationValue_OffsetPath @947-951
- function_item Servo_AnimationValue_OffsetDistance @954-958
- function_item Servo_AnimationValue_OffsetRotate @961-965
- function_item Servo_AnimationValue_OffsetAnchor @968-972
- function_item Servo_AnimationValue_OffsetPosition @975-979
- function_item Servo_AnimationValue_DeepEqual @982-987
- function_item Servo_AnimationValue_Uncompute @990-1003
- function_item resolve_rules_for_element_with_context @1066-1093
- function_item Servo_AnimationValueMap_Create @1096-1098
- function_item Servo_AnimationValueMap_Drop @1101-1105
- function_item Servo_AnimationValueMap_GetValue @1108-1119
- function_item Servo_StyleSet_GetBaseComputedValuesForElement @1122-1167
- struct_item ShouldTransitionResult @1171-1174
- function_item is_transitionable @1177-1192
- function_item Servo_ComputedValues_ShouldTransition @1197-1290
- function_item Servo_ComputedValues_TransitionValueMatches @1293-1310
- function_item Servo_ComputedValues_ExtractAnimationValue @1313-1325
- function_item Servo_ResolveLogicalProperty @1328-1338
- function_item Servo_Property_LookupEnabledForAllContent @1341-1348
- function_item Servo_Property_GetName @1351-1367
- function_item Servo_Property_IsShorthand @1386-1392
- function_item Servo_Property_IsInherited @1395-1417
- function_item Servo_Property_SupportsType @1420-1427
- function_item Servo_Property_GetCSSValuesForProperty @1430-1449
- function_item Servo_Property_GetCSSWideKeywords @1452-1456
- function_item Servo_Property_IsAnimatable @1459-1461
- function_item Servo_Property_ResolveAlias @1464-1471
- function_item Servo_Property_IsDiscreteAnimatable @1474-1479
- function_item Servo_Element_ClearData @1482-1484
- function_item Servo_Element_SizeOfExcludingThisAndCVs @1487-1506
- function_item Servo_Element_GetMaybeOutOfDateStyle @1509-1518
- function_item Servo_Element_GetMaybeOutOfDatePseudoStyle @1521-1534
- function_item borrow_assert_main_thread @1541-1546
- function_item borrow_assert_main_thread @1549-1551
- function_item Servo_Element_IsDisplayNone @1554-1560
- function_item Servo_Element_IsDisplayContents @1563-1569
- function_item Servo_Element_IsPrimaryStyleReusedViaRuleNode @1572-1579
- function_item check_element_and_eager_pseudos @1581-1606
- function_item Servo_Element_ReferencesAttribute @1609-1621
- function_item Servo_Element_UsesTreeCountingFunction @1624-1630
- function_item Servo_StyleSheet_Empty @1633-1648
- function_item Servo_StyleSheet_FromUTF8Bytes @1654-1714
- function_item Servo_StyleSheet_FromUTF8BytesAsync @1717-1748
- function_item Servo_ShutdownThreadPool @1751-1754
- function_item Servo_ThreadPool_GetThreadHandles @1757-1761
- function_item Servo_StyleSheet_FromSharedData @1764-1775
- function_item Servo_StyleSet_AppendStyleSheet @1778-1788
- function_item Servo_AuthorStyles_Create @1791-1793
- function_item Servo_AuthorStyles_Drop @1796-1800
- function_item Servo_AuthorStyles_AppendStyleSheet @1803-1811
- function_item Servo_AuthorStyles_InsertStyleSheetBefore @1814-1826
- function_item Servo_AuthorStyles_RemoveStyleSheet @1829-1841
- function_item Servo_AuthorStyles_ForceDirty @1844-1846
- function_item Servo_AuthorStyles_IsDirty @1849-1851
- function_item Servo_DeclarationBlock_SizeOfIncludingThis @1854-1877
- function_item Servo_AuthorStyles_SizeOfIncludingThis @1880-1899
- function_item Servo_StyleSet_MediumFeaturesChanged @1902-1955
- function_item Servo_StyleSet_InsertStyleSheetBefore @1958-1973
- function_item Servo_StyleSet_RemoveStyleSheet @1976-1986
- function_item Servo_StyleSet_GetSheetAt @1989-1998
- function_item Servo_StyleSet_GetSheetCount @2001-2007
- function_item Servo_StyleSet_FlushStyleSheets @2010-2061
- function_item Servo_StyleSet_NoteStyleSheetsChanged @2064-2071
- function_item Servo_StyleSet_SetAuthorStyleDisabled @2074-2085
- function_item Servo_StyleSet_UsesFontMetrics @2088-2091
- function_item Servo_StyleSet_UsesRootFontMetrics @2094-2097
- function_item Servo_StyleSheet_HasRules @2100-2104
- function_item Servo_StyleSheet_UseCounters @2107-2109
- function_item Servo_StyleSheet_GetRules @2112-2114
- function_item Servo_StyleSheet_Clone @2117-2127
- function_item Servo_StyleSheet_SizeOfIncludingThis @2130-2145
- function_item Servo_StyleSheet_GetOrigin @2148-2150
- function_item Servo_StyleSheet_GetSourceMapURL @2153-2160
- function_item Servo_StyleSheet_GetSourceURL @2163-2170
- function_item with_maybe_worker_shared_lock @2172-2178
- function_item read_locked_arc @2180-2188
- function_item read_locked_arc_worker @2190-2198
- function_item read_locked_arc_unchecked @2201-2207
- function_item read_locked_arc_unchecked @2210-2216
- function_item write_locked_arc @2218-2226
- function_item write_locked_arc_worker @2228-2236
- function_item Servo_CssRules_GetRuleCount @2239-2241
- function_item Servo_CssRules_GetRuleTypeAt @2244-2249
- function_item Servo_CssRules_ListTypes @2252-2256
- function_item Servo_CssRules_InsertRule @2259-2309
- function_item Servo_CssRules_DeleteRule @2312-2319
- trait_item MaybeLocked @2321-2323
- function_signature_item maybe_locked_read @2322-2322
- function_item maybe_locked_read @2326-2328
- function_item maybe_locked_read @2332-2334
- function_item Servo_StyleRule_EnsureRules @2457-2476
- function_item Servo_NestedDeclarationsRule_GetStyle @2654-2660
- function_item Servo_NestedDeclarationsRule_SetStyle @2663-2670
- function_item Servo_DeclarationBlock_IsImmutable @2673-2685
- function_item Servo_DeclarationBlock_SetImmutable @2688-2698
- function_item Servo_StyleRule_GetStyle @2701-2705
- function_item Servo_StyleRule_SetStyle @2708-2715
- function_item Servo_StyleRule_GetSelectorText @2718-2720
- function_item desugared_selector_list @2722-2731
- function_item Servo_StyleRule_GetSelectorList @2734-2738
- function_item Servo_StyleRule_GetSelectorDataAtIndex @2741-2757
- function_item Servo_StyleRule_GetSelectorCount @2760-2762
- struct_item DesugaredScopeData @2764-2767
- function_item desugared_selector_list_with_scope @2769-2852
- function_item desugared_scope_rule @2778-2819
- struct_item ScopeRuleData @2856-2863
- function_item selector_matches_element @2865-2953
- function_item Servo_StyleRule_SelectorMatchesElement @2956-2978
- function_item Servo_StyleRule_GetScopeRootFor @2981-3009
- function_item Servo_StyleRule_SetSelectorText @3014-3048
- function_item Servo_SelectorList_Closest @3051-3060
- function_item Servo_SelectorList_Matches @3063-3072
- function_item Servo_SelectorList_QueryFirst @3075-3099
- function_item Servo_SelectorList_QueryAll @3102-3137
- function_item Servo_SelectorList_QueryAllWithScope @3140-3208
- function_item Servo_ImportRule_GetHref @3211-3215
- function_item Servo_ImportRule_GetLayerName @3218-3225
- function_item Servo_ImportRule_GetSupportsText @3228-3239
- function_item Servo_ImportRule_GetSheet @3242-3248
- function_item Servo_ImportRule_SetSheet @3251-3258
- function_item Servo_Keyframe_GetKeyText @3261-3268
- function_item Servo_Keyframe_SetKeyText @3271-3281
- function_item Servo_Keyframe_GetStyle @3284-3290
- function_item Servo_Keyframe_SetStyle @3293-3300
- function_item Servo_KeyframesRule_GetName @3303-3305
- function_item Servo_KeyframesRule_SetName @3308-3315
- function_item Servo_KeyframesRule_GetCount @3318-3320
- function_item Servo_KeyframesRule_GetKeyframeAt @3323-3336
- function_item Servo_KeyframesRule_FindRule @3339-3350
- function_item Servo_KeyframesRule_AppendRule @3353-3370
- function_item Servo_KeyframesRule_DeleteRule @3373-3377
- function_item Servo_MediaRule_GetMedia @3380-3382
- function_item Servo_CustomMediaRule_GetCondition @3386-3399
- function_item Servo_NamespaceRule_GetPrefix @3402-3406
- function_item Servo_NamespaceRule_GetURI @3409-3411
- function_item Servo_MarginRule_GetStyle @3414-3416
- function_item Servo_MarginRule_GetName @3419-3421
- function_item Servo_CustomMediaRule_GetName @3424-3426
- function_item Servo_PageRule_GetStyle @3429-3431
- function_item Servo_PageRule_SetStyle @3434-3441
- function_item Servo_PageRule_GetSelectorText @3444-3448
- function_item Servo_PageRule_SetSelectorText @3451-3490
- function_item Servo_PropertyRule_GetName @3493-3495
- function_item Servo_PropertyRule_GetSyntax @3498-3509
- function_item Servo_PropertyRule_GetInherits @3512-3514
- function_item Servo_PropertyRule_GetInitialValue @3517-3526
- function_item Servo_SupportsRule_GetConditionText @3529-3534
- function_item Servo_ContainerRule_GetConditionText @3537-3542
- function_item Servo_ContainerRule_GetConditionsLength @3545-3547
- function_item Servo_ContainerRule_GetContainerName @3550-3561
- function_item Servo_ContainerRule_GetContainerQuery @3564-3574
- function_item Servo_ContainerRule_QueryContainerFor @3577-3588
- function_item Servo_ContainerRule_QueryConditionMatchesElement @3591-3627
- function_item Servo_DocumentRule_GetConditionText @3630-3635
- function_item Servo_FontFeatureValuesRule_GetFontFamily @3638-3645
- function_item Servo_FontFeatureValuesRule_GetValueText @3648-3653
- function_item Servo_FontPaletteValuesRule_GetName @3656-3661
- function_item Servo_FontPaletteValuesRule_GetFontFamily @3664-3673
- function_item Servo_FontPaletteValuesRule_GetBasePalette @3676-3683
- function_item Servo_FontPaletteValuesRule_GetOverrideColors @3686-3695
- function_item Servo_FontFaceRule_CreateEmpty @3698-3706
- function_item Servo_FontFaceRule_Clone @3709-3714
- function_item Servo_FontFaceRule_Equals @3717-3727
- function_item Servo_FontFaceRule_GetSourceLocation @3730-3742
- function_item Servo_FontFaceRule_Length @3745-3747
- function_item Servo_FontFaceRule_IndexGetter @3750-3764
- function_item Servo_FontFaceRule_GetDeclCssText @3767-3776
- function_item Servo_FontFaceRule_GetFontWeight @3791-3807
- function_item Servo_FontFaceRule_GetFontWidth @3810-3826
- function_item Servo_FontFaceRule_GetFontStyle @3829-3845
- function_item Servo_FontFaceRule_GetFontDisplay @3848-3853
- function_item Servo_FontFaceRule_GetFontLanguageOverride @3856-3861
- function_item Servo_FontFaceRule_GetAscentOverride @3866-3882
- function_item Servo_FontFaceRule_GetDescentOverride @3887-3903
- function_item Servo_FontFaceRule_GetLineGapOverride @3908-3924
- function_item Servo_FontFaceRule_GetSizeAdjust @3927-3943
- function_item Servo_FontFaceRule_GetFamilyName @3946-3957
- function_item Servo_FontFaceRule_GetUnicodeRanges @3960-3977
- function_item Servo_FontFaceRule_GetSources @3980-4017
- function_item Servo_FontFaceRule_GetVariationSettings @4020-4037
- function_item Servo_FontFaceRule_GetFeatureSettings @4040-4057
- function_item Servo_FontFaceRule_GetDescriptorCssText @4060-4068
- function_item Servo_FontFaceRule_SetDescriptor @4071-4102
- function_item Servo_FontFaceRule_ResetDescriptor @4105-4112
- function_item Servo_CounterStyleRule_GetName @4115-4119
- function_item Servo_CounterStyleRule_SetName @4122-4134
- function_item Servo_CounterStyleRule_GetGeneration @4137-4141
- function_item symbol_to_string @4143-4148
- function_item Servo_CounterStyleRule_GetPad @4152-4167
- function_item get_symbol @4169-4176
- function_item Servo_CounterStyleRule_GetPrefix @4179-4186
- function_item Servo_CounterStyleRule_GetSuffix @4189-4196
- function_item Servo_CounterStyleRule_GetNegative @4199-4216
- enum_item IsOrdinalInRange @4219-4224
- function_item Servo_CounterStyleRule_IsInRange @4227-4266
- function_item Servo_CounterStyleRule_GetSymbols @4269-4281
- struct_item AdditiveSymbol @4284-4287
- function_item Servo_CounterStyleRule_GetAdditiveSymbols @4290-4308
- enum_item CounterSpeakAs @4311-4318
- function_item Servo_CounterStyleRule_GetSpeakAs @4321-4339
- enum_item CounterSystem @4342-4350
- function_item Servo_CounterStyleRule_GetSystem @4353-4368
- function_item Servo_CounterStyleRule_GetExtended @4371-4383
- function_item Servo_CounterStyleRule_GetFixedFirstValue @4386-4401
- function_item Servo_CounterStyleRule_GetFallback @4404-4413
- function_item Servo_CounterStyleRule_GetDescriptorCssText @4415-4423
- function_item Servo_CounterStyleRule_SetDescriptor @4426-4452
- function_item Servo_PositionTryRule_GetName @4455-4462
- function_item Servo_PositionTryRule_GetStyle @4465-4469
- function_item Servo_PositionTryRule_SetStyle @4472-4479
- function_item Servo_ComputedValues_GetForPageContent @4482-4525
- function_item Servo_ComputedValues_GetForPositionTry @4528-4543
- function_item Servo_ComputedValues_GetForAnonymousBox @4546-4570
- function_item get_functional_pseudo_parameter_atom @4572-4582
- function_item Servo_ResolvePseudoStyle @4585-4661
- function_item debug_atom_array @4663-4675
- function_item Servo_ComputedValues_ResolveXULTreePseudoStyle @4678-4723
- function_item Servo_SetExplicitStyle @4726-4734
- function_item get_pseudo_style @4736-4828
- function_item Servo_ComputedValues_Inherit @4831-4855
- function_item Servo_ComputedValues_SpecifiesAnimationsOrTransitions @4858-4866
- enum_item MatchingDeclarationBlockOrigin @4869-4878
- struct_item MatchingDeclarationBlock @4881-4884
- function_item Servo_ComputedValues_GetMatchingDeclarations @4887-4932
- function_item dump_properties_and_rules @4949-4957
- function_item dump_rules @4960-4971
- function_item Servo_ComputedValues_EqualForCachedAnonymousContentStyle @4975-5014
- function_item Servo_ComputedValues_DumpMatchedRules @5018-5020
- function_item Servo_ComputedValues_BlockifiedDisplay @5023-5030
- function_item Servo_StyleSet_Init @5033-5041
- function_item Servo_StyleSet_Drop @5044-5046
- function_item Servo_StyleSet_RebuildCachedData @5049-5053
- function_item Servo_StyleSet_CompatModeChanged @5056-5060
- function_item parse_property_into @5062-5092
- function_item parse_property @5094-5126
- function_item Servo_ParseProperty @5129-5151
- function_item Servo_ParseLengthPercentageForAbsoluteLengths @5176-5191
- function_item Servo_ParseViewTimelineInset @5194-5221
- function_item Servo_ParseEasing @5224-5236
- function_item Servo_ParseKeyframeSelector @5239-5269
- function_item Servo_ParseTimelineRangeName @5272-5284
- function_item Servo_SerializeEasing @5287-5289
- function_item Servo_SerializeTimelineRangeName @5292-5297
- function_item Servo_GetProperties_Overriding_Animation @5300-5334
- function_item Servo_MatrixTransform_Operate @5337-5363
- function_item Servo_ParseStyleAttribute @5366-5385
- function_item Servo_PseudoStyleType_EnabledForAllContent @5388-5390
- function_item Servo_ParsePseudoElement @5393-5427
- function_item Servo_DeclarationBlock_CreateEmpty @5430-5438
- function_item Servo_DeclarationBlock_Clear @5441-5445
- function_item Servo_DeclarationBlock_Clone @5448-5459
- function_item Servo_DeclarationBlock_Equals @5462-5469
- function_item Servo_DeclarationBlock_GetCssText @5472-5479
- function_item Servo_DeclarationBlock_SerializeOneValue @5482-5501
- function_item Servo_SerializeFontValueForCanvas @5504-5512
- function_item Servo_DeclarationBlock_Count @5515-5519
- function_item Servo_DeclarationBlock_GetAt @5522-5558
- function_item get_property_value @5570-5583
- function_item Servo_DeclarationBlock_GetPropertyValue @5586-5593
- function_item Servo_DeclarationBlock_GetPropertyValueByNonCustomId @5596-5608
- function_item Servo_DeclarationBlock_GetPropertyValueById @5611-5623
- function_item Servo_DeclarationBlock_GetPropertyIsImportant @5626-5634
- struct_item UnsupportedValue @5643-5643
- function_item from @5646-5648
- enum_item PropertyTypedValueList @5665-5678
- function_item Servo_DeclarationBlock_GetPropertyTypedValueList @5681-5706
- function_item set_property_to_declarations @5709-5729
- function_item set_property @5731-5775
- function_item Servo_DeclarationBlock_SanitizeForCanvas @5778-5799
- function_item Servo_DeclarationBlock_SetProperty @5802-5826
- function_item Servo_DeclarationBlock_SetPropertyToAnimationValue @5829-5847
- function_item Servo_DeclarationBlock_SetPropertyById @5850-5874
- function_item Servo_DeclarationBlock_SetPropertyTypedValue @5877-5917
- function_item remove_property @5919-5939
- function_item Servo_DeclarationBlock_RemoveProperty @5942-5952
- function_item Servo_DeclarationBlock_RemovePropertyById @5955-5963
- function_item Servo_DeclarationBlock_Parse @5966-5983
- function_item Servo_NumericDeclaration_Parse @5986-6008
- function_item Servo_NumericDeclaration_Drop @6011-6013
- enum_item NumericValueResult @6024-6035
- function_item Servo_NumericDeclaration_GetValue @6038-6046
- function_item Servo_NumericType_Create @6049-6059
- function_item Servo_NumericType_Invert @6062-6064
- function_item add_numeric_types @6066-6077
- function_item Servo_NumericType_AddTypes @6080-6085
- function_item Servo_NumericType_AddTypesFromValues @6088-6093
- function_item Servo_NumericType_MultiplyTypes @6096-6107
- function_item Servo_SumValue_Create @6110-6117
- function_item Servo_SumValue_Drop @6120-6122
- function_item Servo_SumValue_ToUnit @6133-6144
- function_item Servo_SumValue_ToUnits @6155-6169
- function_item Servo_ImageValue_ToCss @6172-6174
- function_item Servo_MediaList_Create @6177-6180
- function_item Servo_MediaList_DeepClone @6183-6188
- function_item Servo_MediaList_Matches @6191-6203
- function_item Servo_DeclarationBlock_HasCSSWideKeyword @6206-6214
- function_item Servo_MediaList_GetText @6217-6221
- function_item Servo_MediaList_SetText @6224-6259
- function_item Servo_MediaList_IsViewportDependent @6262-6264
- function_item Servo_MediaList_GetLength @6267-6269
- function_item Servo_MediaList_GetMediumAt @6272-6285
- function_item Servo_MediaList_AppendMedium @6288-6305
- function_item Servo_MediaList_DeleteMedium @6308-6328
- function_item Servo_MediaList_SizeOfIncludingThis @6331-6354
- function_item Servo_DeclarationBlock_HasProperty @6379-6390
- function_item Servo_DeclarationBlock_HasLonghandProperty @6393-6406
- function_item Servo_DeclarationBlock_SetIdentStringValue @6409-6424
- function_item Servo_DeclarationBlock_SetKeywordValue @6428-6503
- function_item get_from_computed @6443-6449
- function_item Servo_DeclarationBlock_SetIntValue @6506-6521
- function_item Servo_DeclarationBlock_SetMathDepthValue @6524-6541
- function_item Servo_DeclarationBlock_SetCounterResetListItem @6544-6560
- function_item Servo_DeclarationBlock_SetCounterSetListItem @6563-6578
- function_item Servo_DeclarationBlock_SetPixelValue @6581-6638
- function_item Servo_DeclarationBlock_SetLengthValue @6641-6697
- function_item Servo_DeclarationBlock_SetTransform @6700-6724
- function_item Servo_DeclarationBlock_SetBackdropFilter @6727-6752
- function_item Servo_DeclarationBlock_SetColorScheme @6755-6774
- function_item Servo_DeclarationBlock_SetPathValue @6777-6793
- function_item Servo_CreatePathDataFromCommands @6796-6804
- function_item Servo_SVGPathData_Add @6807-6824
- function_item Servo_SVGPathData_Parse @6827-6834
- function_item Servo_SVGPathData_NormalizeAndReduce @6837-6843
- function_item Servo_SVGPathData_ToString @6846-6849
- function_item Servo_SVGPathData_Interpolate @6852-6880
- function_item Servo_DeclarationBlock_SetPercentValue @6883-6919
- function_item Servo_DeclarationBlock_SetAutoValue @6922-6944
- function_item Servo_DeclarationBlock_SetCurrentColor @6947-6966
- function_item Servo_DeclarationBlock_SetColorValue @6969-6993
- function_item Servo_DeclarationBlock_SetFontFamily @6996-7025
- function_item Servo_DeclarationBlock_SetBackgroundImage @7028-7057
- function_item Servo_DeclarationBlock_SetTextDecorationColorOverride @7060-7071
- function_item Servo_DeclarationBlock_SetAspectRatio @7074-7087
- function_item Servo_CSSSupports2 @7090-7106
- enum_item CssSupportsUrlContext @7110-7113
- struct_item CssSupportsParams @7117-7121
- function_item Servo_CSSSupports @7124-7164
- function_item Servo_CSSSupportsForImport @7167-7188
- function_item Servo_NoteExplicitHints @7191-7197
- function_item Servo_TakeChangeHint @7200-7223
- function_item Servo_ResolveStyle @7226-7240
- function_item Servo_ResolveStyleLazily @7243-7356
- function_item Servo_ReparentStyle @7359-7395
- function_item simulate_compute_values_failure @7398-7402
- function_item simulate_compute_values_failure @7405-7407
- function_item create_context_for_animation @7409-7433
- struct_item PropertyAndIndex @7435-7438
- struct_item PrioritizedPropertyIter @7440-7444
- function_item new @7447-7469
- function_item reset @7471-7473
- function_item next @7479-7485
- function_item Servo_GetComputedKeyframeValues @7489-7629
- function_item Servo_GetAnimationValues @7632-7670
- function_item Servo_AnimationValue_GetPropertyId @7673-7678
- function_item Servo_AnimationValue_Compute @7681-7733
- function_item Servo_ParseAnimationRangeStart @7741-7754
- function_item Servo_ParseAnimationRangeEnd @7757-7770
- function_item Servo_AssertTreeIsClean @7773-7798
- function_item assert_subtree_is_clean @7782-7795
- function_item Servo_IsWorkerThread @7801-7803
- function_item property_value_pair_for @7805-7812
- function_item remove_duplicated_property_value_entry @7814-7842
- function_item Servo_StyleSet_GetKeyframesForName @7845-8040
- function_item Servo_StyleSet_GetFontFaceRules @8043-8063
- function_item Servo_StyleSet_GetCounterStyleRule @8070-8083
- function_item Servo_StyleSet_GetLastViewTransitionRule @8086-8091
- function_item Servo_StyleSet_BuildFontFeatureValueSet @8094-8118
- function_item Servo_StyleSet_BuildFontPaletteValueSet @8121-8145
- function_item Servo_StyleSet_ResolveForDeclarations @8148-8169
- function_item Servo_StyleSet_AddSizeOfExcludingThis @8172-8186
- function_item Servo_UACache_AddSizeOf @8189-8201
- function_item Servo_StyleSet_MightHaveAttributeDependency @8204-8219
- function_item Servo_StyleSet_MightHaveAttributeDependencyInContainer @8222-8238
- function_item Servo_StyleSet_MightHaveNthOfIDDependency @8241-8259
- function_item Servo_StyleSet_MightHaveNthOfClassDependency @8262-8276
- function_item Servo_StyleSet_MightHaveNthOfAttributeDependency @8279-8294
- function_item on_siblings_invalidated @8296-8304
- function_item restyle_for_nth_of @8306-8331
- function_item invalidate_siblings_of @8311-8322
- function_item relative_selector_invalidated_at @8333-8348
- function_item add_relative_selector_attribute_dependency @8350-8368
- function_item inherit_relative_selector_search_direction @8370-8387
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorIDDependency @8390-8432
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorClassDependency @8435-8475
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorAttributeDependency @8478-8513
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorStateDependency @8516-8555
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorCustomStateDependency @8558-8590
- function_item invalidate_relative_selector_prev_sibling_side_effect @8592-8611
- function_item invalidate_relative_selector_next_sibling_side_effect @8613-8632
- function_item invalidate_relative_selector_ts_dependency @8634-8671
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorEmptyDependency @8674-8683
- enum_item RelativeSelectorNthEdgeInvalidateFor @8687-8690
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorNthEdgeDependency @8693-8706
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorNthDependencyFromSibling @8709-8730
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorForInsertion @8733-8812
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorForAppend @8815-8854
- function_item Servo_StyleSet_MaybeInvalidateRelativeSelectorForRemoval @8857-8927
- function_item Servo_StyleSet_HasStateDependency @8930-8942
- function_item Servo_StyleSet_HasNthOfCustomStateDependency @8945-8956
- function_item Servo_StyleSet_HasNthOfStateDependency @8959-8971
- function_item Servo_StyleSet_RestyleSiblingsForNthOf @8974-8978
- function_item Servo_StyleSet_HasDocumentStateDependency @8981-8989
- function_item computed_or_resolved_value @8991-9014
- function_item Servo_GetComputedValue @9017-9024
- function_item Servo_GetResolvedValue @9027-9048
- function_item Servo_ComputedValues_GetPropertyTypedValueList @9051-9129
- function_item Servo_GetCustomPropertyValue @9132-9165
- function_item Servo_GetCustomPropertiesCount @9168-9173
- function_item Servo_ComputedValues_HasCustomProperty @9176-9185
- function_item Servo_GetCustomPropertyNameAt @9188-9199
- function_item Servo_CssUrl_IsLocalRef @9202-9204
- function_item relative_selector_dependencies_for_id @9206-9230
- function_item relative_selector_dependencies_for_class @9232-9250
- function_item relative_selector_dependencies_for_custom_state @9252-9271
- function_item process_relative_selector_invalidations @9273-9347
- function_item Servo_ProcessInvalidations @9350-9409
- function_item Servo_HasPendingRestyleAncestor @9412-9460
- function_item Servo_SelectorList_Parse @9463-9482
- function_item Servo_SelectorList_Drop @9485-9487
- function_item Servo_IsValidCSSColor @9490-9504
- function_item Servo_IsValidCSSImage @9507-9523
- struct_item ComputeColorResult @9525-9528
- function_item compute_color @9530-9586
- function_item Servo_ComputeColor @9589-9608
- function_item Servo_AbsoluteColor_ToCss @9611-9613
- function_item Servo_ColorTo @9616-9680
- function_item Servo_ResolveColor @9683-9688
- function_item Servo_ResolveCalcLengthPercentage @9691-9696
- enum_item CalcAnchorPositioningFunctionResolution @9701-9709
- function_item Servo_ResolveAnchorFunctionsInCalcPercentage @9712-9730
- function_item Servo_ConvertColorSpace @9733-9738
- function_item Servo_GamutMapColorUsingBinarySearchMINDE @9741-9746
- function_item Servo_GamutMapColorUsingRaytrace @9749-9754
- function_item Servo_IntersectionObserverMargin_Parse @9757-9787
- function_item Servo_IntersectionObserverMargin_ToString @9790-9796
- function_item Servo_ParseTransformIntoMatrix @9799-9833
- function_item Servo_ParseFilters @9836-9892
- function_item Servo_ParseFontShorthandForMatching @9895-10012
- function_item Servo_SourceSizeList_Parse @10015-10034
- function_item Servo_SourceSizeList_Evaluate @10037-10051
- function_item Servo_SourceSizeList_Drop @10054-10056
- function_item Servo_InvalidateStyleForDocStateChanges @10059-10103
- function_item Servo_PseudoClass_GetStates @10106-10114
- function_item Servo_UseCounters_Create @10117-10119
- function_item Servo_UseCounters_Drop @10122-10124
- function_item Servo_UseCounters_Merge @10127-10132
- function_item Servo_IsPropertyIdRecordedInUseCounter @10135-10141
- function_item Servo_IsUnknownPropertyRecordedInUseCounter @10144-10149
- function_item Servo_IsCustomUseCounterRecorded @10152-10157
- function_item Servo_IsCssPropertyRecordedInUseCounter @10160-10187
- function_item Servo_SharedMemoryBuilder_Create @10190-10195
- function_item Servo_SharedMemoryBuilder_AddStylesheet @10198-10216
- function_item Servo_SharedMemoryBuilder_GetLength @10219-10223
- function_item Servo_SharedMemoryBuilder_Drop @10226-10228
- function_item Servo_StyleArcSlice_EmptyPtr @10231-10233
- function_item Servo_LoadData_GetLazy @10236-10240
- function_item Servo_LengthPercentage_ToCss @10243-10248
- function_item Servo_FontStyle_ToCss @10251-10253
- function_item Servo_FontWeight_ToCss @10256-10258
- function_item Servo_FontWidth_ToCss @10261-10263
- function_item Servo_FontWidth_SerializeKeyword @10266-10273
- function_item Servo_CursorKind_Parse @10276-10287
- function_item Servo_FontFamily_Generic @10290-10292
- function_item Servo_FontFamily_ForSystemFont @10295-10297
- function_item Servo_FontFamilyList_WithNames @10300-10307
- function_item Servo_FamilyName_Serialize @10310-10312
- function_item Servo_GenericFontFamily_Parse @10315-10330
- function_item Servo_ColorScheme_Parse @10333-10355
- function_item Servo_LayerBlockRule_GetName @10358-10362
- function_item Servo_ScopeRule_GetStart @10365-10371
- function_item Servo_ScopeRule_GetEnd @10374-10380
- function_item Servo_LayerStatementRule_GetNameCount @10383-10385
- function_item Servo_LayerStatementRule_GetNameAt @10388-10396
- function_item Servo_ViewTransitionRule_GetNavigationDescriptor @10399-10403
- function_item Servo_ViewTransitionRule_GetNavigation @10406-10413
- function_item Servo_ViewTransitionRule_GetTypes @10416-10423
- function_item Servo_InvalidateForViewportUnits @10426-10458
- function_item Servo_InterpolateColor @10461-10477
- function_item Servo_EasingFunctionAt @10480-10486
- function_item parse_no_context @10488-10506
- function_item Servo_ParseLengthWithoutStyleContext @10513-10533
- function_item Servo_SlowRgbToColorName @10536-10550
- function_item Servo_SlowRgbToNearestColorName @10553-10587
- function_item Servo_ColorNameToRgb @10590-10598
- function_item Servo_RegisterCustomProperty @10602-10618
- struct_item PropDef @10621-10632
- function_item new @10636-10666
- function_item Servo_GetRegisteredCustomProperties @10670-10699
- function_item Servo_GetRegisteredCustomProperty @10702-10729
- function_item Servo_Value_Matches_Syntax @10732-10772
- struct_item SelectorWarningData @10775-10780
- function_item Servo_GetSelectorWarnings @10783-10794
- function_item Servo_GetRuleBodyText @10797-10834
- function_item Servo_ReplaceBlockRuleBodyTextInStylesheetText @10837-10887
- function_item get_byte_index_from_line_and_column @10890-10934
- struct_item CSSToken @10937-10949
- function_item Servo_CSSParser_create @10952-10956
- function_item Servo_CSSParser_destroy @10959-10961
- function_item Servo_CSSParser_GetCurrentLine @10964-10966
- function_item Servo_CSSParser_GetCurrentColumn @10969-10971
- function_item Servo_CSSParser_NextToken @10974-11125
- enum_item AnchorPositioningFunctionResolution @11129-11136
- function_item resolve_anchor_function @11138-11153
- function_item resolve_inset_fallback @11155-11190
- function_item Servo_ResolveAnchorFunction @11193-11200
- trait_item AnchorSizeFallbackResolver @11202-11208
- function_signature_item resolve_fallback @11203-11207
- function_item resolve_fallback @11211-11246
- function_item resolve_fallback @11250-11276
- function_item resolve_fallback @11280-11315
- function_item resolve_fallback @11319-11356
- function_item do_resolve_anchor_size @11359-11380
- function_item Servo_ResolveAnchorSizeFunctionForInset @11383-11394
- function_item offset_params_from_base_params @11396-11408
- function_item Servo_ResolveAnchorSizeFunctionForMargin @11411-11422
- function_item Servo_ResolveAnchorSizeFunctionForSize @11425-11436
- function_item Servo_ResolveAnchorSizeFunctionForMaxSize @11439-11450
- function_item Servo_PhysicalizePositionArea @11453-11459
- function_item Servo_ResolvePositionAreaSelfAlignment @11463-11488
- function_item Servo_GetShadowRootForScoped @11491-11499
- function_item compute_arbritrary_substitution_functions @11501-11570
- struct_item ContextForSubstitution @11572-11578
- function_item new @11581-11599
- function_item computed_context @11601-11620
- function_item dummy_author_style_rule_context @11623-11635
- function_item Servo_GetSubstitutedValue @11638-11663
- function_item Servo_GetComputationStepsSupportedCSSFunctions @11666-11678
- function_item Servo_GetComputationSteps @11681-11841
- function_item Servo_TextTransform_Case @11844-11846

### servo/ports/geckolib/lib.rs

Blob: `ffccfbc33334960f0a95d403c064890b55e5a5c0`. Grammar: rust. Status: syntax-clean.

- mod_item error_reporter @14-14
- mod_item glue @16-16
- mod_item stylesheet_loader @17-17
- function_item je_malloc_usable_size @21-23

### servo/ports/geckolib/stylesheet_loader.rs

Blob: `880c70e3748ae13240286585ebfed3b7a9f9a8cb`. Grammar: rust. Status: syntax-clean.

- struct_item StylesheetLoader @26-31
- function_item new @34-41
- function_item request_stylesheet @45-86
- struct_item AsyncStylesheetParser @89-96
- function_item new @99-115
- function_item parse @117-138
- function_item request_stylesheet @142-181

### servo/ports/geckolib/tests/lib.rs

Blob: `f27c2fe353d70276043e769f8eca04d5f1836725`. Grammar: rust. Status: syntax-clean.

- mod_item piecewise_linear @17-17

### servo/ports/geckolib/tests/piecewise_linear.rs

Blob: `728c76638af14f3c1b37c371fce523967eaa7e16`. Grammar: rust. Status: syntax-clean.

- function_item get_linear_keyword_equivalent @8-10
- function_item linear_keyword_equivalent_in_bound @12-17
- function_item linear_keyword_equivalent_out_of_bounds @20-24
- function_item get_const_function @26-30
- function_item const_function @35-40
- function_item const_function_out_of_bounds @43-47
- function_item implied_input_spacing @50-67
- function_item interpolation @70-84
- function_item implied_multiple_input_spacing @87-107
- function_item nonzero_edge_values @110-120
- function_item out_of_bounds_extrapolate @123-134
- function_item out_of_bounds_flat @137-150
- function_item flat_region @153-165
- function_item step @168-181
- function_item step_multiple_conflicting @184-198
- function_item always_monotonic @201-214
- function_item always_monotonic_flat @217-230
- function_item always_monotonic_flat_backwards @233-246
- function_item input_out_of_bounds @249-261
- function_item invalid_builder_input @264-285
- function_item input_domain_not_complete @288-298
- function_item input_second_negative @301-327
- function_item input_second_last_above_1 @330-345

### servo/tests/unit/malloc_size_of/lib.rs

Blob: `1280d0a8f2120471dc2340f414b78ffe1412a146`. Grammar: rust. Status: syntax-clean.

- function_item imports_ok @21-21
- mod_item does_not_impl_malloc_size_of @23-63
- function_item servo_arc @36-36
- function_item std_arc @49-49
- function_item rc @62-62
- mod_item does_not_impl_malloc_shallow_size_of @65-105
- function_item servo_arc @78-78
- function_item std_arc @91-91
- function_item rc @104-104

### servo/tests/unit/style/animated_properties.rs

Blob: `05b74de16c569e176db627057ea3e3e1c54c4425`. Grammar: rust. Status: syntax-clean.

- function_item interpolate_rgba @10-17
- function_item test_rgba_color_interepolation_preserves_transparent @21-26
- function_item test_rgba_color_interepolation_alpha @29-34
- function_item test_rgba_color_interepolation_out_of_range_1 @37-48
- function_item test_rgba_color_interepolation_out_of_range_2 @51-60
- function_item test_rgba_color_interepolation_out_of_range_clamped_1 @63-72
- function_item test_rgba_color_interepolation_out_of_range_clamped_2 @75-84
- function_item test_transform_interpolation_on_translate @88-138
- function_item test_transform_interpolation_on_scale @141-149
- function_item test_transform_interpolation_on_rotate @152-177
- function_item test_transform_interpolation_on_skew @180-199
- function_item test_transform_interpolation_on_mismatched_lists @202-225

### servo/tests/unit/style/attr.rs

Blob: `fd22b96d0f4aa5333e848095e0453c5cc9b5538b`. Grammar: rust. Status: syntax-clean.

- function_item test_length_calc @10-19
- function_item test_parse_double @22-28
- function_item test_parse_double_negative_prefix @31-37
- function_item test_parse_double_positive_prefix @40-46
- function_item test_from_limited_i32_should_be_default_when_less_than_0 @49-55
- function_item test_from_limited_i32_should_parse_a_uint_when_value_is_0_or_greater @58-63
- function_item test_from_limited_i32_should_keep_parsed_value_when_not_an_int @66-73
- function_item test_parse_length @76-94
- function_item check @77-80

### servo/tests/unit/style/custom_properties.rs

Blob: `e8d04e8e547498d859114a4a3823825b92e76d4a`. Grammar: rust. Status: syntax-clean.

- function_item cascade @13-36
- function_item cascade_custom_simple @39-48

### servo/tests/unit/style/lib.rs

Blob: `31a9d60285767d5298acb6f60a31dc8f495bba06`. Grammar: rust. Status: syntax-clean.

- mod_item animated_properties @26-26
- mod_item attr @27-27
- mod_item custom_properties @28-28
- mod_item logical_geometry @29-29
- mod_item parsing @30-30
- mod_item properties @31-31
- mod_item rule_tree @32-32
- mod_item size_of @33-33
- mod_item str @34-34
- mod_item stylesheets @35-35
- mod_item stylist @36-36

### servo/tests/unit/style/logical_geometry.rs

Blob: `e5c6605421fcd3b6d3d900b4ecea2097c8dfda74`. Grammar: rust. Status: syntax-clean.

- function_item modes @9-35
- function_item test_size_round_trip @38-46
- function_item test_point_round_trip @49-58
- function_item test_margin_round_trip @61-71
- function_item test_rect_round_trip @74-81

### servo/tests/unit/style/media_queries.rs

Blob: `27bc1208fff95660ce8737ae6d3cece0f6844dad`. Grammar: rust. Status: syntax-clean.

- function_item test_media_rule @19-52
- function_item media_query_test @54-72
- function_item test_mq_empty @75-79
- function_item test_mq_screen @82-115
- function_item test_mq_print @118-151
- function_item test_mq_unknown @154-187
- function_item test_mq_all @190-214
- function_item test_mq_or @217-236
- function_item test_mq_default_expressions @239-267
- function_item test_mq_expressions @270-338
- function_item test_to_css @341-347
- function_item test_mq_multiple_expressions @350-399
- function_item test_mq_malformed_expressions @402-422
- function_item check_malformed_expr @403-410
- function_item test_matching_simple @425-442
- function_item test_matching_width @445-557
- function_item test_matching_invalid @560-578

### servo/tests/unit/style/parsing/animation.rs

Blob: `257e45540b33b46202d656f5fe3160e968cb2db4`. Grammar: rust. Status: syntax-clean.

- function_item test_animation_iteration @14-21

### servo/tests/unit/style/parsing/background.rs

Blob: `d37deb8c8e9fb765984c14dc45d14f0a1d584952`. Grammar: rust. Status: syntax-clean.

- function_item background_shorthand_should_parse_all_available_properties_when_specified @16-56
- function_item background_shorthand_should_parse_when_some_fields_set @59-111
- function_item background_shorthand_should_parse_comma_separated_declarations @114-163
- function_item background_shorthand_should_parse_position_and_size_correctly @166-196
- function_item background_shorthand_should_parse_origin_and_clip_correctly @199-232

### servo/tests/unit/style/parsing/border.rs

Blob: `a2f3bf40686bd7597f7caff172aff822b56e45f8`. Grammar: rust. Status: syntax-clean.

- function_item test_border_radius @73-111
- function_item border_image_shorthand_should_parse_when_all_properties_specified @114-123
- function_item border_image_shorthand_should_parse_without_width @126-135
- function_item border_image_shorthand_should_parse_without_outset @138-147
- function_item border_image_shorthand_should_parse_without_width_or_outset @150-159
- function_item border_image_shorthand_should_parse_with_just_source @162-170
- function_item border_image_outset_should_error_on_negative_length @173-176
- function_item border_image_outset_should_error_on_negative_number @179-182
- function_item border_image_outset_should_return_number_on_plain_zero @185-188
- function_item border_image_outset_should_return_length_on_length_zero @191-194
- function_item test_border_style @197-210
- function_item test_border_spacing @213-219

### servo/tests/unit/style/parsing/box_.rs

Blob: `cec950c3cd7983f9d950d0506c43432c1f5d6413`. Grammar: rust. Status: syntax-clean.

- function_item test_transform_translate @9-15
- function_item test_unexhausted_transform @18-22

### servo/tests/unit/style/parsing/column.rs

Blob: `6e0e86182af191e3b6c94939d32b9c1bdb00c8a1`. Grammar: rust. Status: syntax-clean.

- function_item test_column_width @9-18
- function_item test_column_gap @21-30

### servo/tests/unit/style/parsing/effects.rs

Blob: `1b377aca547f92108b04faedd7bee081e4f82b85`. Grammar: rust. Status: syntax-clean.

- function_item test_clip @10-39
- function_item test_effects_parser_exhaustion @42-48
- function_item test_parse_factor @51-91
- function_item blur_radius_should_not_accept_negavite_values @94-99

### servo/tests/unit/style/parsing/image.rs

Blob: `33ccb88cb0c0242d3841695dca70168678703fe6`. Grammar: rust. Status: syntax-clean.

- function_item test_linear_gradient @10-31
- function_item test_radial_gradient @34-154

### servo/tests/unit/style/parsing/inherited_text.rs

Blob: `90ec16f7b0a3cfed4daaec3de1396068461a9446`. Grammar: rust. Status: syntax-clean.

- function_item negative_letter_spacing_should_parse_properly @9-18
- function_item negative_word_spacing_should_parse_properly @21-30
- function_item line_height_should_return_number_on_plain_zero @33-38
- function_item line_height_should_return_length_on_length_zero @41-46

### servo/tests/unit/style/parsing/mod.rs

Blob: `e9a6197c90292505a33ce0605d573cbbbfbfedb2`. Grammar: rust. Status: syntax-clean.

- function_item parse @13-19
- function_item parse_input @21-36
- function_item parse_entirely @38-44
- function_item parse_entirely_input @46-54
- mod_item animation @130-130
- mod_item background @131-131
- mod_item border @132-132
- mod_item box_ @133-133
- mod_item column @134-134
- mod_item effects @135-135
- mod_item image @136-136
- mod_item inherited_text @137-137
- mod_item outline @138-138
- mod_item position @139-139
- mod_item selectors @140-140
- mod_item supports @141-141
- mod_item text_overflow @142-142
- mod_item transition_duration @143-143
- mod_item transition_timing_function @144-144

### servo/tests/unit/style/parsing/outline.rs

Blob: `6d909d9bc5edabe26d33bc90bda3ef5a94159675`. Grammar: rust. Status: syntax-clean.

- function_item test_outline_style @9-26

### servo/tests/unit/style/parsing/position.rs

Blob: `ce73c7a0d2dba34ed1b1d757d7756594cd4aa0bf`. Grammar: rust. Status: syntax-clean.

- function_item test_position @11-75
- function_item test_horizontal_position @78-110
- function_item test_vertical_position @113-145

### servo/tests/unit/style/parsing/selectors.rs

Blob: `0f6e2e7a43b2467e26cf491135a5d1e3b661e804`. Grammar: rust. Status: syntax-clean.

- function_item parse_selector @11-20
- function_item test_selectors @23-33

### servo/tests/unit/style/parsing/supports.rs

Blob: `6cba7195a70cec40af8fd87acb3a0c57877d21dc`. Grammar: rust. Status: syntax-clean.

- function_item test_supports_condition @10-19

### servo/tests/unit/style/parsing/text_overflow.rs

Blob: `505e6ffb8cdf933920ef25c5a00e4d0783910e1c`. Grammar: rust. Status: syntax-clean.

- function_item test_text_overflow @9-20
- function_item test_text_overflow_parser_exhaustion @23-30

### servo/tests/unit/style/parsing/transition_duration.rs

Blob: `c771a58944cc29e1b84d2b8faf99f4fbba6796a3`. Grammar: rust. Status: syntax-clean.

- function_item test_positive_transition_duration @9-12
- function_item test_negative_transition_duration @15-17

### servo/tests/unit/style/parsing/transition_timing_function.rs

Blob: `4ea3fc45dce483f23a46d2a68b8cf0b9db4e6939`. Grammar: rust. Status: syntax-clean.

- function_item test_cubic_bezier @10-50
- function_item test_steps @53-68

### servo/tests/unit/style/properties/mod.rs

Blob: `750a1b5765cef68e84f83d77a4875a115b70a651`. Grammar: rust. Status: syntax-clean.

- function_item parse @11-17
- function_item parse_input @19-34
- mod_item scaffolding @68-68
- mod_item serialization @69-69

### servo/tests/unit/style/properties/scaffolding.rs

Blob: `a4cffcb6ffafc6c2d5c1bd3627522944acd80d7f`. Grammar: rust. Status: syntax-clean.

- function_item properties_list_json @12-44
- function_item find_python @47-71
- function_item find_python @74-87

### servo/tests/unit/style/properties/serialization.rs

Blob: `3b65434c9af83be9db22de82902e9176253618a9`. Grammar: rust. Status: syntax-clean.

- trait_item ToCssString @18-20
- function_signature_item to_css_string @19-19
- function_item to_css_string @23-27
- function_item property_declaration_block_should_serialize_correctly @31-73
- mod_item shorthand_serialization @75-776
- function_item shorthand_properties_to_string @78-82
- mod_item four_sides_shorthands @84-330
- function_item all_equal_properties_should_serialize_to_one_value @90-101
- function_item equal_vertical_and_equal_horizontal_properties_should_serialize_to_two_value @104-117
- function_item different_vertical_and_equal_horizontal_properties_should_serialize_to_three_values @120-134
- function_item different_properties_should_serialize_to_four_values @137-152
- function_item different_longhands_should_serialize_to_long_form @155-185
- function_item same_longhands_should_serialize_correctly @188-217
- function_item padding_should_serialize_correctly @220-234
- function_item border_width_should_serialize_correctly @237-253
- function_item border_width_with_keywords_should_serialize_correctly @256-271
- function_item border_color_should_serialize_correctly @274-292
- function_item border_style_should_serialize_correctly @295-307
- function_item border_radius_should_serialize_correctly @312-329
- mod_item border_shorthands @332-486
- function_item border_top_and_color @336-361
- function_item border_color_and_top @364-390
- function_item directional_border_should_show_all_properties_when_values_are_set @396-409
- function_item get_border_property_values @411-417
- function_item border_top_should_serialize_correctly @420-429
- function_item border_right_should_serialize_correctly @432-441
- function_item border_bottom_should_serialize_correctly @444-453
- function_item border_left_should_serialize_correctly @456-465
- function_item border_should_serialize_correctly @468-485
- mod_item background @488-617
- function_item background_should_serialize_all_available_properties_when_specified @492-514
- function_item background_should_combine_origin_and_clip_properties_when_equal @517-539
- function_item serialize_multiple_backgrounds @542-565
- function_item serialize_multiple_backgrounds_unequal_property_lists @568-593
- function_item background_position_should_be_a_valid_form_its_longhands @596-616
- mod_item quotes @619-628
- function_item should_serialize_none_correctly @623-627
- mod_item animation @630-722
- function_item serialize_single_animation @634-654
- function_item serialize_multiple_animations @657-678
- function_item serialize_multiple_animations_unequal_property_lists @681-703
- function_item serialize_multiple_without_all_properties_returns_longhand @706-721
- mod_item keywords @724-745
- function_item css_wide_keywords_should_be_parsed @727-734
- function_item non_keyword_custom_property_should_be_unparsed @737-744
- mod_item effects @747-775
- function_item box_shadow_should_serialize_correctly @753-774

### servo/tests/unit/style/rule_tree/bench.rs

Blob: `ab507f3bdab52bc5fcd8a236019b2851ffbebe33`. Grammar: rust. Status: syntax-clean.

- struct_item ErrorringErrorReporter @19-19
- function_item report_error @21-29
- struct_item AutoGCRuleTree @32-32
- function_item new @35-37
- function_item drop @41-49
- function_item parse_rules @52-80
- function_item test_insertion @82-84
- function_item test_insertion_style_attribute @86-102
- function_item bench_insertion_basic @105-122
- function_item bench_insertion_basic_per_element @125-140
- function_item bench_expensive_insertion @143-168
- function_item bench_insertion_basic_parallel @171-199
- function_item bench_expensive_insertion_parallel @202-239

### servo/tests/unit/style/rule_tree/mod.rs

Blob: `6370d2640c9c79f438c9e65fe5be3a86ccaffbc0`. Grammar: rust. Status: syntax-clean.

- mod_item bench @5-5

### servo/tests/unit/style/size_of.rs

Blob: `1fee6997e08808fb5ba4cfcf9b32704bb9643dcf`. Grammar: rust. Status: syntax-clean.


### servo/tests/unit/style/str.rs

Blob: `9445ce167cc586d878060fdc8c3bd078a9cfcf86`. Grammar: rust. Status: syntax-clean.

- function_item split_html_space_chars_whitespace @8-15
- function_item test_str_join_empty @18-23
- function_item test_str_join_one @26-31
- function_item test_str_join_many @34-39
- function_item test_starts_with_ignore_ascii_case_basic @42-45
- function_item test_starts_with_ignore_ascii_case_char_boundary @48-50

### servo/tests/unit/style/stylesheets.rs

Blob: `535238edaa33cafa0580ea3a512f127cbbbde6e7`. Grammar: rust. Status: syntax-clean.

- function_item block_from @35-44
- function_item test_parse_stylesheet @47-343
- struct_item CSSError @346-351
- struct_item TestingErrorReporter @353-355
- function_item new @358-362
- function_item assert_messages_contain @364-388
- function_item report_error @392-399
- function_item test_report_error_stylesheet @403-470
- function_item test_no_report_unrecognized_vendor_properties @473-503
- function_item test_source_map_url @506-533
- function_item test_source_url @536-560

### servo/tests/unit/style/stylist.rs

Blob: `aefc89c666bf382f7eeda4ce501c1c3686ebbb7a`. Grammar: rust. Status: syntax-clean.

- function_item get_mock_rules @25-62
- function_item parse_selectors @64-76
- function_item test_revalidation_selectors @79-169
- function_item test_rule_ordering_same_specificity @172-180
- function_item test_insert @183-214
- function_item mock_stylist @216-223
- function_item test_stylist_device_accessors @226-232
- function_item test_stylist_rule_tree_accessors @235-240

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
