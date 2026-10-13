<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["servo"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["1ba5a7080a7d590f130fd2b3acbd7e759cebed378b3111c962a7e620b09ea28a"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/4b277d57-7417-4571-bd02-cec162a55282.md"}} -->
# firefox/servo native and TypeScript syntax map 234

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### servo/components/malloc_size_of/lib.rs

Blob: `33fccaf372321ef4c826a13ed10bddb8176947ae`. Grammar: rust. Status: syntax-clean.

- struct_item MallocSizeOfOps @63-77
- function_item new @80-90
- function_item is_empty @94-103
- function_item malloc_size_of @111-117
- function_item has_malloc_enclosing_size_of @120-122
- function_item malloc_enclosing_size_of @129-132
- function_item have_seen_ptr @135-141
- trait_item MallocSizeOf @146-150
- function_signature_item size_of @149-149
- trait_item MallocShallowSizeOf @153-159
- function_signature_item shallow_size_of @158-158
- trait_item MallocUnconditionalSizeOf @164-168
- function_signature_item unconditional_size_of @167-167
- trait_item MallocUnconditionalShallowSizeOf @171-174
- function_signature_item unconditional_shallow_size_of @173-173
- trait_item MallocConditionalSizeOf @179-184
- function_signature_item conditional_size_of @183-183
- trait_item MallocConditionalShallowSizeOf @187-190
- function_signature_item conditional_shallow_size_of @189-189
- function_item size_of @193-195
- function_item size_of @199-202
- function_item shallow_size_of @206-208
- function_item size_of @212-214
- function_item size_of @218-220
- function_item size_of @228-230
- function_item size_of @239-241
- function_item size_of @251-253
- function_item size_of @257-263
- function_item size_of @267-272
- function_item size_of @276-278
- function_item size_of @282-284
- function_item size_of @288-292
- function_item size_of @299-304
- function_item size_of @308-314
- function_item shallow_size_of @318-320
- function_item size_of @324-330
- function_item shallow_size_of @334-347
- function_item size_of @351-357
- function_item shallow_size_of @361-367
- function_item size_of @375-381
- function_item shallow_size_of @385-396
- function_item size_of @400-406
- function_item shallow_size_of @495-503
- function_item size_of @511-518
- function_item size_of @523-525
- function_item size_of @536-538
- function_item unconditional_shallow_size_of @542-544
- function_item unconditional_size_of @548-550
- function_item conditional_shallow_size_of @554-560
- function_item conditional_size_of @564-570
- function_item size_of @580-582
- function_item size_of @586-592
- function_item size_of @596-598
- function_item size_of @602-604
- function_item size_of @608-610
- function_item size_of @614-616
- function_item size_of @620-625
- function_item size_of @629-631
- function_item size_of @635-642
- function_item size_of @646-663
- function_item size_of @667-669
- function_item size_of @673-676
- function_item unconditional_size_of @685-697
- function_item unconditional_size_of @706-718
- function_item unconditional_size_of @727-763
- function_item size_of @769-771
- function_item size_of @775-777
- function_item size_of @782-784
- function_item size_of @789-791
- struct_item Measurable @849-849
- function_item deref @854-856
- function_item deref_mut @860-862
- function_item size_of @866-868

### servo/components/selectors/attr.rs

Blob: `2a80f939c9f975cee6d9793bcf1a4bae980ce2d1`. Grammar: rust. Status: syntax-clean.

- struct_item AttrSelectorWithOptionalNamespace @15-23
- function_item namespace @26-31
- enum_item NamespaceConstraint @36-41
- enum_item ParsedAttrSelectorOperation @45-52
- enum_item AttrSelectorOperation @55-62
- function_item eval_str @65-77
- enum_item AttrSelectorOperator @82-89
- function_item to_css @92-106
- function_item eval_str @110-140
- enum_item ParsedCaseSensitivity @148-157
- enum_item CaseSensitivity @160-163
- function_item eq @166-171
- function_item contains @173-195

### servo/components/selectors/bloom.rs

Blob: `5299e1840acf5f99d72e66ee22fb982873936e44`. Grammar: rust. Status: syntax-clean.

- struct_item CountingBloomFilter @68-73
- function_item new @81-83
- function_item clear @86-88
- function_item is_zeroed @93-95
- function_item is_zeroed @98-100
- function_item insert_hash @104-107
- function_item remove_hash @111-114
- function_item might_contain_hash @120-122
- function_item fmt @129-137
- trait_item BloomStorage @140-174
- function_signature_item slot_is_empty @141-141
- function_signature_item adjust_slot @142-142
- function_signature_item is_zeroed @143-143
- function_item first_slot_is_empty @146-148
- function_item second_slot_is_empty @151-153
- function_item adjust_first_slot @156-158
- function_item adjust_second_slot @161-163
- function_item first_slot_index @166-168
- function_item second_slot_index @171-173
- struct_item BloomStorageU8 @177-179
- function_item adjust_slot @183-193
- function_item slot_is_empty @196-198
- function_item is_zeroed @201-203
- function_item default @207-211
- function_item clone @215-219
- struct_item BloomStorageBool @223-225
- function_item adjust_slot @229-244
- function_item slot_is_empty @247-250
- function_item is_zeroed @253-255
- function_item default @259-263
- function_item clone @267-271
- function_item hash1 @275-277
- function_item hash2 @280-282
- function_item create_and_insert_some_stuff @285-339
- function_item hash_as_str @290-296
- mod_item bench @343-422
- struct_item HashGenerator @348-348
- function_item next @351-362
- function_item create_insert_1000_remove_100_lookup_100 @366-381
- function_item might_contain_10 @384-392
- function_item clear @395-398
- function_item insert_10 @401-409
- function_item remove_10 @412-421

### servo/components/selectors/builder.rs

Blob: `bbcd0d239890269a4459f702f9340740637c4104`. Grammar: rust. Status: syntax-clean.

- struct_item SelectorBuilder @48-55
- function_item push @58-60
- function_item push_simple_selector @66-69
- function_item push_combinator @74-78
- function_item reverse_last_compound @80-83
- function_item has_combinators @87-89
- function_item build @93-100
- function_item build_with_specificity_and_flags @105-150
- function_item default @155-160
- struct_item ExactChain @165-165
- function_item len @172-174
- function_item next @185-187
- function_item size_hint @189-192
- struct_item SelectorFlags @198-198
- function_item fmt @212-218
- function_item forbidden_for_nesting @228-230
- struct_item SpecificityAndFlags @235-241
- struct_item Specificity @246-250
- function_item single_class_like @255-261
- function_item from @266-273
- function_item from @278-282
- function_item specificity_and_flags @285-425
- function_item component_specificity @292-409
- function_item selector_list_specificity_and_flags @428-448
- function_item relative_selector_list_specificity_and_flags @450-455

### servo/components/selectors/context.rs

Blob: `4dffd8fe45ae5812f13e14692368ba98d91c8640`. Grammar: rust. Status: syntax-clean.

- enum_item MatchingMode @18-34
- enum_item VisitedHandlingMode @38-51
- function_item matches_visited @55-61
- function_item matches_unvisited @64-70
- enum_item NeedsSelectorFlags @76-79
- enum_item MatchingForInvalidation @83-87
- function_item is_for_invalidation @91-93
- enum_item QuirksMode @100-107
- function_item classes_and_ids_case_sensitivity @111-116
- struct_item SelectorCaches @121-128
- struct_item MatchingContext @133-194
- function_item new @201-219
- function_item new_for_revalidation @222-240
- function_item new_for_visited @243-262
- function_item new_internal @265-295
- function_item nth_index_cache @299-308
- function_item is_nested @312-314
- function_item in_negation @318-320
- function_item quirks_mode @324-326
- function_item matching_mode @330-332
- function_item needs_selector_flags @336-338
- function_item matching_for_invalidation @342-344
- function_item matching_for_revalidation @348-350
- function_item matching_for_invalidation_comparison @354-360
- function_item for_invalidation_comparison @364-377
- function_item classes_and_ids_case_sensitivity @381-383
- function_item nest @387-395
- function_item nest_for_negation @400-409
- function_item visited_handling @412-414
- function_item with_featureless @418-427
- function_item featureless @433-435
- function_item with_visited_handling_mode @439-452
- function_item with_shadow_host @457-467
- function_item shadow_host @472-474
- function_item nest_for_relative_selector @479-491
- function_item nest_for_scope @495-504
- function_item nest_for_scope_condition @509-520
- function_item relative_selector_anchor @524-526

### servo/components/selectors/kleene_value.rs

Blob: `22dbc54121df33e3ec8817a8342fd75ef948fdab`. Grammar: rust. Status: syntax-clean.

- enum_item KleeneValue @9-16
- function_item from @19-21
- function_item to_bool @27-33
- function_item any @39-41
- function_item any_false @47-49
- function_item any_value @52-72
- function_item not @78-84
- function_item bitand @91-99
- function_item bitor @106-114
- function_item bitor_assign @118-120
- function_item bitand_assign @124-126

### servo/components/selectors/lib.rs

Blob: `88f2307622c57f0708cc193c8ca081739065eebb`. Grammar: rust. Status: syntax-clean.

- mod_item attr @8-8
- mod_item bloom @9-9
- mod_item builder @10-10
- mod_item context @11-11
- mod_item kleene_value @12-12
- mod_item matching @13-13
- mod_item nth_index_cache @14-14
- mod_item parser @15-15
- mod_item relative_selector @16-16
- mod_item sink @17-17
- mod_item subtree_filter @18-18
- mod_item tree @19-19
- mod_item visitor @20-20

### servo/components/selectors/matching.rs

Blob: `0a2601d99ed1a2316ee00d4249d9cebbc917e085`. Grammar: rust. Status: syntax-clean.

- function_item for_self @96-102
- function_item for_parent @105-112
- struct_item LocalMatchingContext @116-120
- function_item matches_selector_list @123-141
- function_item selector_may_match @146-170
- enum_item SelectorMatchingResult @229-235
- function_item from @239-247
- function_item matches_selector @259-279
- function_item matches_selector_kleene @283-310
- enum_item CompoundSelectorMatchingResult @314-322
- function_item complex_selector_early_reject_by_local_name @324-331
- function_item early_reject_by_local_name @335-353
- function_item matches_compound_selector_from @362-439
- function_item matches_complex_selector @443-488
- function_item matches_complex_selector_list @491-500
- function_item matches_relative_selector @502-586
- function_item relative_selector_match_early @588-616
- function_item match_relative_selectors @618-647
- function_item do_match_relative_selectors @650-695
- function_item matches_relative_selector_subtree @697-723
- function_item hover_and_active_quirk_applies @728-751
- enum_item SubjectOrPseudoElement @755-758
- function_item host_for_part @760-776
- function_item assigned_slot @778-793
- struct_item NextElement @795-798
- function_item new @802-807
- function_item next_element_for_combinator @811-841
- function_item matches_complex_selector_internal @843-991
- function_item matches_local_name @994-1000
- function_item matches_part @1002-1046
- function_item matches_host @1048-1072
- function_item matches_slotted @1074-1088
- function_item matches_rare_attribute_selector @1090-1121
- function_item compound_matches_featureless_host @1126-1182
- function_item matches_compound_selector @1186-1216
- function_item matches_simple_selector @1219-1354
- function_item select_name @1357-1367
- function_item to_unconditional_case_sensitivity @1370-1387
- function_item matches_generic_nth_child @1389-1515
- function_item nth_child_index @1518-1602

### servo/components/selectors/nth_index_cache.rs

Blob: `21951130109d288b14f106505d8b2d6ced302796`. Grammar: rust. Status: syntax-clean.

- struct_item NthIndexCache @16-23
- function_item get @27-52
- struct_item SelectorListCacheKey @56-56
- function_item new @61-63
- struct_item NthIndexOfSelectorsCaches @68-68
- function_item lookup @73-80
- struct_item NthIndexCacheInner @85-85
- function_item lookup @89-91
- function_item insert @94-96
- function_item is_empty @99-101

### servo/components/selectors/parser.rs

Blob: `cac3c1d0b8c9598fb4ce917f698617fb35010c2f`. Grammar: rust. Status: syntax-clean.

- trait_item PseudoElement @35-76
- function_item accepts_state_pseudo_classes @38-40
- function_item valid_after_slotted @43-45
- function_item valid_after_before_or_after @48-50
- function_item parses_as_element_backed @54-56
- function_item is_before_or_after @61-63
- function_item specificity_count @66-68
- function_item is_in_pseudo_element_tree @73-75
- trait_item NonTSPseudoClass @79-95
- function_signature_item is_active_or_hover @81-81
- function_signature_item is_user_action_state @86-86
- function_item visit @88-94
- function_item to_ascii_lowercase @99-107
- function_item allows_slotted @164-166
- function_item allows_part @169-171
- function_item allows_non_functional_pseudo_classes @174-176
- function_item allows_tree_structural_pseudo_classes @179-181
- function_item allows_combinators @184-186
- function_item allows_only_child_pseudo_class_only @189-191
- enum_item SelectorParseErrorKind @197-218
- trait_item Parser @273-373
- function_item parse_slotted @278-280
- function_item parse_part @283-285
- function_item parse_nth_child_of @288-290
- function_item parse_is_and_where @293-295
- function_item parse_has @298-300
- function_item parse_parent_selector @303-305
- function_item is_is_alias @308-310
- function_item parse_host @313-315
- function_item allow_forgiving_selectors @318-320
- function_item parse_non_ts_pseudo_class @324-331
- function_item parse_non_ts_functional_pseudo_class @333-342
- function_item parse_pseudo_element @344-351
- function_item parse_functional_pseudo_element @353-361
- function_item default_namespace @363-365
- function_item namespace_for_prefix @367-372
- struct_item SelectorList @380-383
- function_item mark_as_intentionally_leaked @387-394
- function_item from_one @396-407
- function_item from_iter @410-419
- function_item slice @422-431
- function_item len @435-440
- function_item thin_arc_heap_ptr @443-448
- struct_item SelectorKey @454-454
- function_item new @458-460
- enum_item ForgivingParsing @465-473
- enum_item ParseRelative @477-488
- function_item scope @492-494
- function_item implicit_scope @496-498
- function_item parse @504-519
- function_item parse_disallow_pseudo @522-537
- function_item parse_forgiving @539-554
- function_item parse_with_state @557-589
- function_item replace_parent_selector @592-598
- function_item from_vec @602-604
- function_item parse_inner_compound_selector @608-623
- struct_item AncestorHashes @641-643
- function_item collect_selector_hashes @645-734
- function_item collect_ancestor_hashes @736-774
- function_item new @777-796
- function_item fourth_hash @799-803
- function_item namespace_empty_string @807-810
- enum_item MatchesFeaturelessHost @817-824
- function_item may_match @829-831
- struct_item Selector @852-854
- function_item mark_as_intentionally_leaked @858-860
- function_item scope @862-870
- function_item implicit_scope @873-881
- function_item specificity @884-886
- function_item flags @889-891
- function_item has_pseudo_element @894-896
- function_item has_parent_selector @899-901
- function_item has_scope_selector @904-906
- function_item is_slotted @909-911
- function_item is_part @914-916
- function_item parts @919-941
- function_item pseudo_element @944-957
- function_item pseudo_elements @960-983
- function_item is_universal @989-999
- function_item matches_featureless_host @1004-1035
- function_item iter @1041-1046
- function_item iter_skip_relative_selector_anchor @1050-1070
- function_item iter_from @1075-1081
- function_item combinator_at_match_order @1086-1094
- function_item iter_raw_match_order @1099-1101
- function_item combinator_at_parse_order @1106-1114
- function_item iter_raw_parse_order_from @1120-1125
- function_item from_vec @1129-1144
- function_item into_data @1147-1149
- function_item replace_parent_selector @1151-1365
- function_item replace_parent_on_selector_list @1161-1192
- function_item replace_parent_on_relative_selector_list @1194-1233
- function_item replace_parent_on_selector @1235-1246
- function_item len @1370-1372
- function_item thin_arc_heap_ptr @1375-1377
- function_item visit @1397-1421
- function_item parse @1425-1435
- function_item new_invalid @1437-1478
- function_item check_for_parent @1438-1461
- function_item is_rightmost @1481-1489
- struct_item SelectorIter @1493-1496
- function_item next_sequence @1502-1504
- function_item skip_until_ancestor @1508-1515
- function_item matches_for_stateless_pseudo_element @1518-1526
- function_item matches_for_stateless_pseudo_element_internal @1529-1542
- function_item selector_length @1546-1548
- function_item next @1555-1567
- function_item fmt @1571-1577
- struct_item CombinatorIter @1581-1581
- function_item new @1583-1587
- function_item consume_non_combinators @1589-1591
- function_item next @1596-1600
- struct_item AncestorIter @1604-1604
- function_item next @1607-1618
- enum_item Combinator @1623-1641
- function_item is_pseudo_element @1646-1648
- function_item is_sibling @1652-1654
- function_item is_ancestor @1659-1661
- enum_item NthType @1668-1675
- function_item is_only @1678-1680
- function_item is_of_type @1682-1684
- function_item is_from_end @1686-1688
- struct_item AnPlusB @1695-1695
- function_item matches_index @1699-1708
- function_item to_css @1715-1731
- struct_item NthSelectorData @1740-1744
- function_item only @1749-1759
- function_item first @1763-1773
- function_item last @1777-1787
- function_item is_simple_edge @1791-1796
- function_item write_start @1800-1813
- function_item write_affine @1816-1818
- struct_item NthOfSelectorData @1827-1829
- function_item new @1834-1839
- function_item nth_data @1843-1845
- function_item selectors @1849-1851
- enum_item RelativeSelectorMatchHint @1857-1870
- function_item new @1874-1916
- function_item is_descendant_direction @1919-1921
- function_item is_next_sibling @1924-1926
- function_item is_subtree @1929-1934
- struct_item RelativeSelectorCombinatorCount @1939-1943
- function_item new @1947-1972
- function_item get_match_hint @1975-1981
- struct_item RelativeSelector @1988-1994
- function_item for_relative_selector @2006-2025
- function_item from_selector_list @2029-2063
- enum_item Component @2073-2178
- function_item is_combinator @2183-2185
- function_item is_host @2189-2191
- function_item as_combinator @2194-2199
- function_item matches_for_stateless_pseudo_element @2204-2220
- function_item visit @2222-2305
- function_item has_indexed_selector_in_subject @2310-2328
- struct_item LocalName @2334-2338
- function_item fmt @2341-2350
- function_item fmt @2354-2356
- function_item fmt @2359-2361
- function_item fmt @2364-2366
- function_item serialize_selector_list @2369-2384
- function_item to_css @2387-2392
- function_item to_css @2396-2537
- function_item to_css_internal @2541-2563
- function_item to_css_relative @2565-2570
- function_item to_css @2574-2579
- function_item to_css @2583-2714
- function_item to_css @2718-2751
- function_item to_css @2755-2760
- function_item parse_selector @2767-2842
- function_item try_parse_combinator @2844-2870
- function_item parse_type_selector @2875-2942
- enum_item SimpleSelectorParseResult @2945-2950
- enum_item QNamePrefix @2954-2961
- function_item parse_qualified_name @2968-3052
- function_item parse_attribute_selector @3054-3176
- enum_item AttributeFlags @3180-3187
- function_item is_ascii_case_insensitive_html_attribute @3199-3249
- function_item to_case_sensitivity @3252-3268
- function_item parse_attribute_flags @3271-3292
- function_item parse_negation @3296-3316
- function_item parse_compound_selector @3324-3422
- function_item parse_is_where @3424-3450
- function_item parse_has @3452-3482
- function_item parse_functional_pseudo_class @3484-3527
- function_item parse_nth_pseudo_class @3529-3571
- function_item is_css2_pseudo_element @3576-3582
- function_item parse_one_simple_selector @3589-3728
- function_item parse_simple_pseudo_class @3730-3782
- mod_item tests @3786-4912
- enum_item PseudoClass @3795-3799
- enum_item PseudoElement @3802-3808
- function_item accepts_state_pseudo_classes @3811-3813
- function_item valid_after_slotted @3815-3817
- function_item valid_after_before_or_after @3819-3821
- function_item is_before_or_after @3823-3825
- function_item parses_as_element_backed @3827-3829
- function_item is_active_or_hover @3834-3836
- function_item is_user_action_state @3839-3841
- function_item to_css @3845-3858
- function_item to_css @3862-3877
- struct_item DummySelectorImpl @3881-3881
- struct_item DummyParser @3884-3887
- function_item default_with_namespace @3890-3895
- struct_item DummyAttrValue @3912-3912
- function_item to_css @3915-3924
- function_item from @3928-3930
- struct_item DummyAtom @3934-3934
- function_item to_css @3937-3942
- function_item from @3946-3948
- function_item from @3952-3954
- function_item precomputed_hash @3958-3960
- function_item parse_slotted @3967-3969
- function_item parse_nth_child_of @3971-3973
- function_item parse_is_and_where @3975-3977
- function_item parse_has @3979-3981
- function_item parse_parent_selector @3983-3985
- function_item parse_part @3987-3989
- function_item parse_host @3991-3993
- function_item parse_non_ts_pseudo_class @3995-4004
- function_item parse_non_ts_functional_pseudo_class @4006-4022
- function_item parse_pseudo_element @4024-4035
- function_item parse_functional_pseudo_element @4037-4049
- function_item default_namespace @4051-4053
- function_item namespace_for_prefix @4055-4057
- function_item parse @4060-4062
- function_item parse_relative @4064-4069
- function_item parse_expected @4071-4076
- function_item parse_relative_expected @4078-4084
- function_item parse_ns @4086-4091
- function_item parse_ns_relative @4093-4099
- function_item parse_ns_expected @4101-4107
- function_item parse_ns_relative_expected @4109-4129
- function_item specificity @4131-4133
- function_item test_ancestor_hashes_in_subject_position @4136-4194
- function_item ancestor_hash_count @4137-4149
- function_item test_empty @4197-4204
- function_item test_parsing @4210-4682
- function_item parent_selector @4685-4724
- function_item test_pseudo_iter @4727-4748
- function_item test_pseudo_before_marker @4751-4771
- function_item test_pseudo_duplicate_before_after_or_marker @4774-4778
- function_item test_pseudo_on_element_backed_pseudo @4781-4801
- function_item test_universal @4804-4812
- function_item test_empty_pseudo_iter @4815-4828
- function_item test_parse_implicit_scope @4831-4885
- struct_item TestVisitor @4887-4889
- function_item visit_simple_selector @4894-4899
- function_item visitor @4903-4911

### servo/components/selectors/relative_selector/cache.rs

Blob: `062a2ca40f4f388361f78eaf2d7559b91bc8e8ef`. Grammar: rust. Status: syntax-clean.

- enum_item RelativeSelectorCachedMatch @24-29
- function_item matched @33-35
- struct_item Key @39-42
- function_item new @45-53
- struct_item RelativeSelectorCache @58-60
- function_item add @64-71
- function_item lookup @74-80

### servo/components/selectors/relative_selector/filter.rs

Blob: `6bcbbaa1e3e9bb41098dec40124685a7560c3085`. Grammar: rust. Status: syntax-clean.

- enum_item Entry @14-22
- enum_item TraversalKind @25-28
- function_item add_to_filter @30-42
- struct_item Key @45-45
- struct_item RelativeSelectorFilterMap @49-51
- function_item fast_reject @53-82
- function_item get_filter @85-107
- function_item fast_reject @114-156

### servo/components/selectors/relative_selector/mod.rs

Blob: `6dd39f7327e6b6e4a0b2eb6e9383bb9ee5d2ab95`. Grammar: rust. Status: syntax-clean.

- mod_item cache @5-5
- mod_item filter @6-6

### servo/components/selectors/sink.rs

Blob: `dcdd7ff259dd5d6dc435a671a66ec97d11d09e1f`. Grammar: rust. Status: syntax-clean.

- trait_item Push @16-19
- function_signature_item push @18-18
- function_item push @22-24
- function_item push @28-30

### servo/components/selectors/subtree_filter.rs

Blob: `535d1f4cdc9a5ff77c992189a041cabe639b50a8`. Grammar: rust. Status: syntax-clean.

- function_item hash_for_subtree_filter @27-32

### servo/components/selectors/tree.rs

Blob: `9aab6db51f364ce28c06eff6937986ce4e3b605a`. Grammar: rust. Status: syntax-clean.

- struct_item OpaqueElement @17-17
- function_item new @26-28
- function_item from_ptr @31-33
- function_item to_ptr @37-39
- trait_item Element @42-194
- function_signature_item opaque @46-46
- function_signature_item parent_element @48-48
- function_signature_item parent_node_is_shadow_root @51-51
- function_signature_item containing_shadow_host @54-54
- function_item pseudo_element_originating_element @60-63
- function_signature_item is_pseudo_element @66-66
- function_signature_item prev_sibling_element @69-69
- function_signature_item next_sibling_element @72-72
- function_signature_item first_element_child @75-75
- function_signature_item is_html_element_in_html_document @77-77
- function_signature_item has_local_name @79-79
- function_signature_item has_namespace @82-82
- function_signature_item is_same_type @85-85
- function_signature_item attr_matches @87-92
- function_item has_attr_in_no_namespace @94-103
- function_signature_item match_non_ts_pseudo_class @105-109
- function_signature_item match_pseudo_element @111-115
- function_signature_item apply_selector_flags @120-120
- function_signature_item is_link @123-123
- function_signature_item is_html_slot_element @126-126
- function_item assigned_slot @131-133
- function_signature_item has_id @135-139
- function_signature_item has_class @141-145
- function_signature_item has_custom_state @147-147
- function_signature_item imported_part @151-154
- function_signature_item is_part @156-156
- function_signature_item is_empty @162-162
- function_signature_item is_root @169-169
- function_item ignores_nth_child_selectors @173-175
- function_signature_item add_element_unique_hashes @179-179
- function_item subtree_filter @185-187
- function_item subtree_may_have_hashes @191-193

### servo/components/selectors/visitor.rs

Blob: `e4286c55532cae89bc7bf8c0a9575e225106aa4a`. Grammar: rust. Status: syntax-clean.

- trait_item SelectorVisitor @17-70
- function_item visit_attribute_selector @24-31
- function_item visit_simple_selector @34-36
- function_item visit_relative_selector_list @42-44
- function_item visit_selector_list @50-61
- function_item visit_complex_selector @67-69
- function_item from_component @92-100
- function_item in_negation @103-105
- function_item in_is @108-110
- function_item in_where @113-115
- function_item in_nth_of @119-121
- function_item in_has @124-126
- function_item relevant_to_nth_of_dependencies @129-136

### servo/components/servo_arc/lib.rs

Blob: `b6382fe3ad4c51d79662fe49720ea114fd1f1a07`. Grammar: rust. Status: syntax-clean.

- struct_item Arc @68-71
- struct_item UniqueArc @99-99
- function_item new @104-106
- function_item new_uninit @110-131
- function_item shareable @135-137
- function_item assume_init @147-152
- function_item deref @157-159
- function_item deref_mut @163-166
- struct_item ArcInner @179-192
- function_item data_offset @198-203
- function_item new @208-238
- function_item new_leaked @242-246
- function_item into_raw @252-256
- function_item from_raw @265-273
- function_item from_raw_addrefed @281-285
- function_item new_static @295-317
- function_item borrow_arc @324-326
- function_item heap_ptr @332-338
- function_item inner @343-350
- function_item record_drop @353-358
- function_item mark_as_intentionally_leaked @370-373
- function_item drop_slow @378-390
- function_item ptr_eq @395-397
- function_item ptr @399-401
- function_item raw_ptr @404-406
- function_signature_item NS_LogCtor @411-415
- function_signature_item NS_LogDtor @416-420
- function_item clone @425-465
- function_item deref @472-474
- function_item make_mut @492-506
- function_item get_mut @512-521
- function_item is_static @525-529
- function_item is_unique @534-539
- function_item drop @544-582
- function_item eq @586-588
- function_item partial_cmp @592-594
- function_item lt @596-598
- function_item le @600-602
- function_item gt @604-606
- function_item ge @608-610
- function_item cmp @613-615
- function_item fmt @620-622
- function_item fmt @626-628
- function_item fmt @632-634
- function_item default @638-640
- function_item hash @644-646
- function_item from @651-653
- function_item borrow @658-660
- function_item as_ref @665-667
- function_item deserialize @675-680
- function_item serialize @685-690
- struct_item HeaderSlice @700-709
- function_item eq @712-714
- function_item drop @718-726
- function_item fmt @730-735
- function_item slice @741-743
- function_item data @746-748
- function_item data_mut @751-753
- function_item slice_mut @757-759
- function_item len @763-765
- function_item is_empty @769-771
- function_item from_header_and_iter_alloc @787-870
- function_item from_header_and_iter_with_size @875-886
- function_item from_header_and_iter @891-897
- function_item from_header_and_iter @914-919
- function_item from_header_and_iter_with_size @922-929
- function_item header_mut @932-935
- function_item data_mut @938-941
- struct_item ArcBorrow @959-959
- function_item clone @964-966
- function_item clone_arc @972-977
- function_item from_ref @985-987
- function_item ptr_eq @992-994
- function_item with_arc @999-1012
- function_item get @1017-1019
- function_item deref @1026-1028
- struct_item ArcUnion @1040-1044
- function_item eq @1050-1057
- enum_item ArcUnionBorrow @1064-1067
- function_item new @1070-1076
- function_item ptr_eq @1080-1082
- function_item ptr @1085-1087
- function_item borrow @1091-1101
- function_item from_first @1104-1108
- function_item from_second @1111-1115
- function_item is_first @1118-1120
- function_item is_second @1123-1125
- function_item as_first @1128-1133
- function_item as_second @1136-1141
- function_item clone @1145-1150
- function_item drop @1154-1163
- function_item fmt @1167-1169
- mod_item tests @1173-1226
- struct_item Canary @1181-1181
- function_item drop @1184-1188
- function_item empty_thin @1192-1196
- function_item thin_assert_padding @1199-1212
- struct_item Padded @1202-1204
- function_item slices_and_thin @1215-1225

### servo/components/style/applicable_declarations.rs

Blob: `6d82f086691449fa9a573d91b720e7ccf9edb449`. Grammar: rust. Status: syntax-clean.

- struct_item CascadePriority @38-42
- function_item partial_cmp @51-53
- function_item cmp @57-81
- enum_item RevertKind @86-93
- function_item new @97-107
- function_item flags @111-113
- function_item set_flags @117-119
- function_item layer_order @123-125
- function_item cascade_level @129-131
- function_item allows_when_reverted @137-147
- function_item unimportant @150-156
- function_item important @159-165
- function_item same_tree_author_normal_at_root_layer @168-174
- struct_item ScopeProximity @181-181
- function_item partial_cmp @185-187
- function_item cmp @191-194
- function_item new @203-208
- function_item infinity @211-213
- function_item get @216-218
- struct_item ApplicableDeclarationBlock @227-240
- function_item from_declarations @246-260
- function_item new @264-280
- function_item source_order @284-286
- function_item level @290-292
- function_item layer_order @296-298
- function_item scope_proximity @302-304
- function_item for_rule_tree @309-311
- function_item sort_key @315-322

### servo/components/style/author_styles.rs

Blob: `59869458ed30ef66c2d90fe82a4ccffa95838a5d`. Grammar: rust. Status: syntax-clean.

- struct_item GenericAuthorStyles @21-31
- function_item default @42-44
- function_item new @53-58
- function_item flush @62-82

### servo/components/style/bezier.rs

Blob: `1a9e06022a07ebab2db07678ca2b239a411c3fcd`. Grammar: rust. Status: syntax-clean.

- struct_item Bezier @16-23
- function_item calculate_bezier_output @33-81
- function_item new @84-99
- function_item sample_curve_x @102-105
- function_item sample_curve_y @108-110
- function_item sample_curve_derivative_x @113-115
- function_item solve_curve_x @118-157
- function_item solve @162-164
- trait_item ApproxEq @167-169
- function_signature_item approx_eq @168-168
- function_item approx_eq @173-175

### servo/components/style/bloom.rs

Blob: `c75f5a67f22b08cb695d764f4ce43fabb235a90d`. Grammar: rust. Status: syntax-clean.

- struct_item StyleBloom @63-76
- struct_item PushedElement @88-94
- function_item new @97-102
- function_item is_attr_name_excluded_from_filter @110-112
- function_item each_relevant_element_hash @115-134
- function_item drop @137-140
- function_item default @144-146
- function_item new @159-170
- function_item filter @173-175
- function_item push @179-184
- function_item push_internal @188-196
- function_item pop @200-220
- function_item matching_depth @225-227
- function_item clear @230-242
- function_item rebuild @245-257
- function_item assert_complete @263-276
- function_item current_parent @282-284
- function_item insert_parents_recovering @294-402
- trait_item AtomExt @405-407
- function_signature_item get_hash32 @406-406
- function_item get_hash32 @411-414
- function_item get_hash32 @419-421
- function_item get_hash32 @426-428

### servo/components/style/build.rs

Blob: `f119e9f1bc8ecb08fa38b4dc794085da0e938511`. Grammar: rust. Status: syntax-clean.

- mod_item build_gecko @12-12
- mod_item build_gecko @15-17
- function_item generate @16-16
- function_item generate_properties @43-67
- function_item main @69-85

### servo/components/style/build_gecko.rs

Blob: `5ff3e497f8dc5c5d58d40e56a4d0e774e2403349`. Grammar: rust. Status: syntax-clean.

- function_item read_config @26-39
- function_item get_modified_time @72-74
- function_item update_last_modified @76-80
- function_item search_include @82-91
- function_item add_headers_recursively @93-107
- function_item add_include @109-118
- trait_item BuilderExt @120-123
- function_signature_item get_initial_builder @121-121
- function_signature_item include @122-122
- function_item get_initial_builder @126-155
- function_item include @156-158
- struct_item Fixup @161-164
- function_item write_binding_file @166-198
- struct_item BuilderWithConfig @200-204
- function_item new @206-212
- function_item handle_list @214-230
- function_item handle_items @231-236
- function_item handle_str_items @237-242
- function_item handle_table_items @243-248
- function_item handle_common @249-260
- function_item get_builder @262-269
- function_item generate_structs @272-315
- function_item setup_logging @317-366
- struct_item BuildLogger @318-321
- function_item enabled @324-326
- function_item log @328-343
- function_item flush @345-349
- function_item generate_pseudo_elements @368-381
- function_item generate @383-393

### servo/components/style/color/color_function.rs

Blob: `ec33eb435e93631ec2260dd0079e1f2166260572`. Grammar: rust. Status: syntax-clean.

- enum_item ColorFunction @25-96
- function_item has_origin_color @100-102
- function_item to_computed_color @109-128
- function_item map_origin_color @133-174
- function_item origin_color @177-189
- function_item to_computed_value @192-276
- function_item to_absolute_color @280-456
- function_item resolve @311-317
- function_item resolve_to_absolute @459-474
- function_item to_css @478-587

### servo/components/style/color/component.rs

Blob: `beb28753046c62e4bf5ef92d85c8730e19b1b0bf`. Grammar: rust. Status: syntax-clean.

- enum_item ColorComponent @26-37
- function_item is_none @42-44
- trait_item ColorComponentType @49-65
- function_signature_item from_value @54-54
- function_signature_item is_valid_type @57-57
- function_signature_item try_from_token @60-60
- function_signature_item try_from_leaf @64-64
- function_item parse @69-104
- function_item to_computed_value @112-156
- function_item resolve @162-172
- function_item to_css @176-197
- function_item to_animated_value @203-205
- function_item from_animated_value @207-209

### servo/components/style/color/convert.rs

Blob: `53787f06a232e7a3e508a0c75f89d031939918e4`. Grammar: rust. Status: syntax-clean.

- function_item normalize_hue @23-25
- function_item rgb_to_hue_min_max @30-49
- function_item hsl_to_rgb @54-86
- function_item hue_to_rgb @55-67
- function_item rgb_to_hsl @90-109
- function_item hwb_to_rgb @114-128
- function_item rgb_to_hwb @133-142
- function_item epsilon_for_range @146-148
- function_item orthogonal_to_polar @154-173
- function_item polar_to_orthogonal @179-192
- function_item transform @195-198
- function_item xyz_d65_to_xyz_d50 @200-211
- function_item xyz_d50_to_xyz_d65 @213-224
- enum_item WhitePoint @227-232
- function_item values @236-244
- function_item convert_white_point @247-253
- trait_item ColorSpaceConversion @266-285
- function_signature_item to_linear_light @272-272
- function_signature_item to_xyz @276-276
- function_signature_item from_xyz @280-280
- function_signature_item to_gamma_encoded @284-284
- function_item to_xyz @289-296
- function_item from_xyz @300-315
- struct_item Srgb @319-319
- function_item to_linear_light @344-354
- function_item to_xyz @356-358
- function_item from_xyz @360-362
- function_item to_gamma_encoded @364-374
- struct_item Hsl @378-378
- function_item to_linear_light @383-385
- function_item to_xyz @388-390
- function_item from_xyz @393-395
- function_item to_gamma_encoded @397-399
- struct_item Hwb @403-403
- function_item to_linear_light @408-410
- function_item to_xyz @413-415
- function_item from_xyz @418-420
- function_item to_gamma_encoded @422-424
- struct_item SrgbLinear @429-429
- function_item to_linear_light @434-437
- function_item to_xyz @439-441
- function_item from_xyz @443-445
- function_item to_gamma_encoded @447-450
- struct_item DisplayP3 @455-455
- function_item to_linear_light @480-482
- function_item to_xyz @484-486
- function_item from_xyz @488-490
- function_item to_gamma_encoded @492-494
- struct_item DisplayP3Linear @498-498
- function_item to_linear_light @502-504
- function_item to_xyz @506-508
- function_item from_xyz @510-512
- function_item to_gamma_encoded @514-516
- struct_item A98Rgb @521-521
- function_item to_linear_light @547-549
- function_item to_xyz @551-553
- function_item from_xyz @555-557
- function_item to_gamma_encoded @560-562
- struct_item ProphotoRgb @567-567
- function_item to_linear_light @592-604
- function_item to_xyz @606-608
- function_item from_xyz @610-612
- function_item to_gamma_encoded @614-625
- struct_item Rec2020 @630-630
- function_item to_linear_light @660-670
- function_item to_xyz @672-674
- function_item from_xyz @676-678
- function_item to_gamma_encoded @680-690
- struct_item XyzD50 @695-695
- function_item to_linear_light @700-702
- function_item to_xyz @704-706
- function_item from_xyz @708-710
- function_item to_gamma_encoded @712-714
- struct_item XyzD65 @719-719
- function_item to_linear_light @724-726
- function_item to_xyz @728-730
- function_item from_xyz @732-734
- function_item to_gamma_encoded @736-738
- struct_item Lab @743-743
- function_item to_linear_light @753-756
- function_item to_xyz @762-791
- function_item from_xyz @797-814
- function_item to_gamma_encoded @816-819
- struct_item Lch @824-824
- function_item to_linear_light @829-832
- function_item to_xyz @834-840
- function_item from_xyz @842-848
- function_item to_gamma_encoded @850-853
- struct_item Oklab @858-858
- function_item to_linear_light @901-904
- function_item to_xyz @906-910
- function_item from_xyz @912-916
- function_item to_gamma_encoded @918-921
- struct_item Oklch @926-926
- function_item to_linear_light @931-934
- function_item to_xyz @936-942
- function_item from_xyz @944-950
- function_item to_gamma_encoded @952-955

### servo/components/style/color/gamut.rs

Blob: `a4c66eb77e0414825b16407bff7053f19d3662f5`. Grammar: rust. Status: syntax-clean.

- mod_item raytrace @13-13
- function_item gamut_map_binary_search @18-155
- function_item clip @160-164
- function_item clip_to_dest_space @170-172
- function_item in_gamut @175-200
- function_item in_gamut_for_dest_space @206-212
- function_item delta_eok @217-225

### servo/components/style/color/gamut/raytrace.rs

Blob: `82671ca2c6acb54060572227bbe0e72cb139a4d7`. Grammar: rust. Status: syntax-clean.

- function_item gamut_map_raytrace @13-161
- function_item cast_ray @167-262

### servo/components/style/color/mix.rs

Blob: `aede32e87294fd00c2c68671c88b3aeff5d4f9a5`. Grammar: rust. Status: syntax-clean.

- enum_item HueInterpolationMethod @34-45
- struct_item ColorInterpolationMethod @61-66
- function_item srgb @70-75
- function_item oklab @79-84
- function_item is_default @87-89
- function_item best_interpolation_between @93-102
- function_item default @106-108
- function_item parse @112-130
- function_item to_css @134-146
- struct_item ColorMixItem @150-155
- function_item new @160-162
- function_item mix_many @166-266
- enum_item ComponentMixOutcome @271-280
- function_item from_colors @283-297
- function_item carry_forward_analogous_missing_components @304-367
- function_item mix_with_weights @371-405
- function_item convert_for_mix @407-411
- function_item interpolate_premultiplied_component @413-422
- function_item normalize_hue @426-428
- function_item adjust_hue @430-490
- function_item interpolate_hue @492-501
- struct_item InterpolatedAlpha @503-512
- function_item interpolate_alpha @514-558
- function_item interpolate_premultiplied @560-645

### servo/components/style/color/mod.rs

Blob: `b43c7ab914a7ccfcc128bc426f7ed47d82fb6742`. Grammar: rust. Status: syntax-clean.

- mod_item convert @8-8
- mod_item color_function @10-10
- mod_item component @11-11
- mod_item gamut @12-12
- mod_item mix @13-13
- mod_item parsing @14-14
- mod_item to_css @15-15
- struct_item ColorComponents @32-32
- function_item map @37-39
- function_item to_array @43-45
- function_item add @51-53
- function_item sub @59-61
- function_item mul @67-69
- function_item div @75-77
- enum_item ColorSpace @100-157
- function_item is_rectangular @162-164
- function_item is_polar @168-170
- function_item is_rgb_or_xyz_like @174-187
- function_item hue_index @192-202
- function_item get_linear_color_space @209-220
- struct_item ColorFlags @227-227
- struct_item AbsoluteColor @251-260
- function_item eq @264-290
- struct_item ComponentDetails @318-321
- function_item from @324-329
- function_item from @333-338
- function_item from @342-354
- function_item from @358-370
- function_item new @400-451
- function_item with_alpha @454-463
- function_item into_srgb_legacy @469-481
- function_item srgb_legacy @484-488
- function_item raw_components @492-494
- function_item is_legacy_syntax @498-505
- function_item is_transparent @509-511
- function_item c0 @515-521
- function_item c1 @525-531
- function_item c2 @535-541
- function_item alpha @545-551
- function_item get_component_by_channel_keyword @554-622
- function_item to_color_space @625-714
- function_item from_nscolor @717-720
- function_item from_nscolor_should_be_in_legacy_syntax @724-728
- function_item from @731-743

### servo/components/style/color/parsing.rs

Blob: `541f894b8a1c04273a27330036539fa18f49f05c`. Grammar: rust. Status: syntax-clean.

- struct_item ChannelKeyword @40-40
- function_item rgb @75-77
- function_item hsl @81-83
- function_item hwb @87-89
- function_item lab @93-95
- function_item lch @99-101
- function_item xyz @105-107
- function_item from_ident @110-127
- function_item parse @131-134
- function_item to_css @138-164
- function_item parse_color_keyword @173-184
- function_item parse_color_with @188-216
- function_item parse_color_function @220-246
- function_item parse_origin_color @249-263
- function_item parse_rgb @266-309
- function_item parse_hsl @315-355
- function_item parse_hwb @361-384
- function_item parse_lab_like @395-413
- function_item parse_lch_like @424-448
- function_item parse_color_with_color_space @452-487
- function_item parse_relative_alpha @491-502
- enum_item NumberOrPercentageComponent @507-513
- function_item to_number @518-523
- function_item from_value @527-529
- function_item is_valid_type @531-534
- function_item try_from_token @536-544
- function_item try_from_leaf @546-552
- enum_item NumberOrAngleComponent @558-564
- function_item degrees @569-574
- function_item from_value @578-580
- function_item is_valid_type @582-585
- function_item try_from_token @587-600
- function_item try_from_leaf @602-608
- function_item from_value @613-615
- function_item is_valid_type @617-619
- function_item try_from_token @621-627
- function_item try_from_leaf @629-635
- function_item parse_number_or_angle @639-652
- function_item parse_percentage @655-673
- function_item parse_number @676-695
- function_item parse_number_or_percentage @698-711
- function_item parse_legacy_alpha @713-723
- function_item parse_modern_alpha @725-736
- function_item could_be_number @741-753
- function_item could_be_percentage @757-769

### servo/components/style/color/to_css.rs

Blob: `0e6f7c3ae6486307153f0bc20f108cb45280e8b0`. Grammar: rust. Status: syntax-clean.

- struct_item ModernComponent @18-18
- function_item to_css @21-41
- function_item to_css @45-56
- function_item to_css @60-71
- function_item to_css @75-181
- function_item write_author_preferred_value @190-312

### servo/components/style/context.rs

Blob: `bdb52bf81541206680bcb0d56ae977cd7364901c`. Grammar: rust. Status: syntax-clean.

- struct_item StyleSystemOptions @54-62
- function_item get_env_bool @65-71
- function_item get_env_usize @76-82
- function_item default @100-109
- function_item default @112-119
- struct_item SharedStyleContext @126-159
- function_item viewport_size @163-165
- function_item device_pixel_ratio @168-170
- function_item quirks_mode @173-175
- struct_item CascadeInputs @186-202
- function_item new_from_style @206-213
- struct_item EagerPseudoCascadeInputs @219-219
- function_item clone @224-234
- function_item new_from_style @239-247
- function_item into_array @250-252
- struct_item ElementCascadeInputs @263-268
- function_item new_from_element_data @273-279
- struct_item PerThreadTraversalStatistics @286-298
- struct_item TraversalStatistics @303-322
- function_item fmt @327-374
- function_item new @381-408
- enum_item SequentialTask @441-460
- function_item execute @464-478
- function_item update_animations @483-494
- struct_item SequentialTaskList @498-500
- function_item deref @508-510
- function_item deref_mut @517-519
- function_item drop @526-531
- struct_item StackLimitChecker @536-538
- function_item new @544-548
- function_item limit_exceeded @552-587
- function_item get_sp @592-595
- struct_item TreeCountingCaches @604-609
- function_item get_or_compute @614-632
- struct_item ThreadLocalStyleContext @640-666
- function_item default @669-671
- function_item new @676-690
- struct_item StyleContext @695-700
- trait_item RegisteredSpeculativePainter @704-709
- function_signature_item name @706-706
- function_signature_item properties @708-708
- trait_item RegisteredSpeculativePainters @713-716
- function_signature_item get @715-715

### servo/components/style/counter_style/mod.rs

Blob: `eaf4fe764477cd2337d2574edbc7add5602a0f52`. Grammar: rust. Status: syntax-clean.

- enum_item SymbolsType @48-54
- enum_item CounterStyle @64-80
- function_item is_symbolic @83-85
- function_item disc @89-91
- function_item decimal @94-96
- function_item is_bullet @100-111
- function_item is_name @114-119
- function_item parse @135-177
- function_item collect_completion_keywords @181-193
- function_item parse_counter_style_name @196-199
- function_item counter_style_name_from_ident @202-223
- function_item is_valid_name_definition @225-232
- function_item parse_counter_style_name_definition @235-243
- struct_item CounterStyleRule @247-253
- function_item parse_counter_style_body @256-317
- function_item to_css @320-326
- function_item empty @332-339
- function_item descriptors @343-345
- function_item set_descriptor @348-393
- function_item check_system @397-399
- function_item check_symbols @401-409
- function_item name @412-414
- function_item set_name @418-421
- function_item generation @424-426
- function_item resolved_system @430-435
- enum_item System @440-458
- function_item parse @461-477
- function_item to_css @481-504
- enum_item Symbol @512-520
- function_item parse @523-529
- function_item is_allowed_in_symbols @534-540
- struct_item Negative @545-545
- function_item parse @548-553
- struct_item CounterRange @558-563
- struct_item CounterRanges @570-570
- enum_item CounterBound @574-579
- function_item parse @582-606
- function_item parse_bound @609-615
- struct_item Pad @619-619
- function_item parse @622-632
- struct_item Fallback @637-637
- function_item parse @640-642
- struct_item Symbols @650-654
- function_item parse @657-666
- struct_item AdditiveSymbols @672-672
- function_item parse @675-688
- struct_item AdditiveTuple @693-698
- function_item parse @705-710
- enum_item SpeakAs @715-728
- function_item parse @731-753

### servo/components/style/counter_style/predefined.rs

Blob: `7243e3b3f32e7300ad283a633c1893322659fa55`. Grammar: rust. Status: syntax-clean.


### servo/components/style/custom_properties.rs

Blob: `bc80bac6e38d28ac50d8c3fb92d178e3ee26c6c0`. Grammar: rust. Status: syntax-clean.

- struct_item CssEnvironment @48-48
- struct_item EnvironmentVariable @52-55
- function_item get_safearea_inset_top @66-68
- function_item get_safearea_inset_bottom @70-72
- function_item get_safearea_inset_left @74-76
- function_item get_safearea_inset_right @78-80
- function_item get_content_preferred_color_scheme @83-98
- function_item get_content_preferred_color_scheme @101-104
- function_item get_scrollbar_inline_size @106-108
- function_item get_hairline @110-115
- function_item eval_gtk_csd_titlebar_radius @152-157
- function_item get @200-231
- function_item with_name @241-243
- function_item with_name @246-248
- function_item from @253-255
- function_item from @258-260
- function_item parse_name @266-272
- struct_item VariableValue @279-296
- function_item compute_variable_value @301-319
- function_item eq @323-325
- function_item to_css @331-336
- function_item to_typed @340-344
- function_item reify_variable_value @347-356
- function_item reify_variable_value_range @364-431
- struct_item ComputedCustomProperties @437-443
- function_item is_empty @447-449
- function_item property_at @452-458
- function_item insert @462-469
- function_item remove @473-475
- function_item shrink_to_fit @478-481
- function_item map_mut @483-489
- function_item get @492-502
- function_item get_for_cssom @506-510
- struct_item ReferenceFlags @522-522
- function_item for_each_non_custom @553-583
- function_item from_unit @585-613
- enum_item SingleNonCustomReference @620-624
- function_item to_prioritary_id @628-634
- struct_item NonCustomReferenceMap @638-638
- function_item default @641-643
- function_item index @649-651
- function_item index_mut @655-657
- enum_item SubstitutionFunctionKind @662-669
- struct_item ComputedSubstitutionFunctions @675-680
- function_item new @686-694
- function_item insert_var @697-704
- function_item insert_attr @707-709
- function_item remove_var @712-714
- function_item remove_attr @717-719
- function_item get_var @722-728
- function_item get_attr @731-733
- enum_item AttributeType @737-743
- struct_item AttributeData @747-750
- struct_item AttrTaintedRange @754-759
- function_item new @764-767
- struct_item AttrTaint @775-775
- function_item should_disallow_urls_in_range @781-785
- function_item is_empty @789-791
- function_item new_fully_tainted @794-798
- function_item push @801-803
- struct_item VariableFallback @808-817
- struct_item SubstitutionFunctionReference @821-834
- function_item is_attr_with_type @838-841
- struct_item References @847-855
- function_item has_references @858-860
- function_item non_custom_references @862-868
- function_item empty @872-881
- function_item new @885-899
- function_item push @901-946
- function_item parse @949-990
- function_item is_attr_tainted @993-995
- function_item integer @998-1007
- function_item ident @1010-1012
- function_item pixels @1015-1028
- function_item int_ms @1031-1041
- function_item int_pixels @1044-1054
- function_item from_token @1056-1069
- function_item css_text @1072-1074
- function_item has_references @1078-1080
- function_item collect_attribute_references @1083-1098
- function_item parse_declaration_value @1102-1118
- function_item parse_declaration_value_block @1121-1370
- function_item parse_attr_type @1374-1395
- function_item get_attr_value_for_cycle_resolution @1399-1416
- function_item handle_invalid_at_computed_value_time @1419-1458
- function_item substitute_references_if_needed_and_apply @1461-1593
- struct_item Substitution @1596-1601
- function_item from_value @1604-1611
- function_item into_value @1613-1649
- function_item new @1651-1663
- struct_item SubstitutionResult @1668-1673
- function_item compute_value @1675-1696
- function_item remove_and_insert_initial_value @1699-1709
- function_item do_substitute_chunk @1711-1799
- function_item quoted_css_string @1801-1805
- function_item substitute_one_reference @1807-1993
- function_item substitute_internal @1996-2022
- function_item substitute @2025-2049

### servo/components/style/custom_properties_map.rs

Blob: `efe4509302162eb62cd743aad814996c1e960017`. Grammar: rust. Status: syntax-clean.

- struct_item CustomPropertiesMap @18-18
- function_item default @21-23
- struct_item Inner @40-48
- struct_item Iter @54-58
- function_item next @63-83
- function_item can_deduplicate_values @87-101
- function_item eq @104-135
- function_item iter @139-145
- function_item is_empty @147-149
- function_item len @151-153
- function_item get @155-160
- function_item insert @162-167
- function_item should_expand_chain @170-176
- function_item is_empty @181-183
- function_item len @186-188
- function_item get_index @191-197
- function_item get @200-202
- function_item do_insert @204-225
- function_item insert @228-230
- function_item remove @233-235
- function_item shrink_to_fit @238-242
- function_item iter @245-247

### servo/components/style/data.rs

Blob: `6d657c511a38fff96a6678abddfe1bd8ac88ae59`. Grammar: rust. Status: syntax-clean.

- struct_item EagerPseudoStyles @61-61
- struct_item EagerPseudoArray @64-64
- function_item deref @69-71
- function_item deref_mut @75-77
- function_item clone @83-89
- function_item fmt @95-108
- function_item is_empty @117-119
- function_item as_optional_array @122-127
- function_item as_array @131-133
- function_item get @136-141
- function_item set @144-150
- struct_item ElementStyles @156-161
- enum_item ViewportUnitUsage @168-177
- function_item get_primary @181-183
- function_item primary @186-188
- function_item is_display_none @191-193
- function_item viewport_unit_usage @196-226
- function_item usage_from_flags @197-205
- function_item uses_tree_counting_function @229-255
- function_item uses_element_scoped_random @258-274
- function_item size_of_excluding_cvs @277-285
- function_item fmt @292-299
- struct_item ElementData @308-322
- struct_item ElementDataWrapper @326-331
- struct_item ElementDataMut @335-339
- struct_item ElementDataRef @343-347
- function_item borrow @352-360
- function_item borrow_mut @364-372
- function_item deref @378-380
- function_item deref @386-388
- function_item deref_mut @392-394
- enum_item RestyleKind @402-412
- function_item needs_to_match_self @414-434
- function_item needs_to_recascade_self @436-455
- function_item invalidate_style_if_needed @461-501
- function_item has_styles @505-507
- function_item share_styles @510-515
- function_item share_primary_style @518-527
- function_item clone_style_with_flags @531-541
- function_item set_styles @544-550
- function_item restyle_kind @554-588
- function_item restyle_kind_for_animation @591-624
- function_item clear_restyle_state @631-634
- function_item clear_restyle_flags_and_damage @638-641
- function_item set_restyled @645-649
- function_item is_restyle @653-655
- function_item set_traversed_without_styling @658-661
- function_item contains_restyle_data @665-667
- function_item safe_for_cousin_sharing @687-704
- function_item size_of_excluding_cvs @708-714

### servo/components/style/device/gecko.rs

Blob: `875cafbf88a0d87488f5f0f49c6e10a2b843194a`. Grammar: rust. Status: syntax-clean.

- struct_item ExtraDeviceData @37-41
- function_item new @48-75
- function_item calc_line_height @80-98
- function_item animation_name_may_be_referenced @102-111
- function_item quirks_mode @114-116
- function_item base_size_for_generic @119-121
- function_item scrollbar_inline_size @124-131
- function_item query_font_metrics @134-180
- function_item document @184-186
- function_item document_random_seed @191-193
- function_item pres_context @197-206
- function_item pref_sheet_prefs @210-212
- function_item reset_computed_values @215-217
- function_item rebuild_cached_data @220-229
- function_item reset @235-237
- function_item is_print_preview @240-246
- function_item media_type @249-263
- function_item page_size_minus_default_margin @268-275
- function_item au_viewport_size @278-290
- function_item au_viewport_size_for_viewport_unit_resolution @294-347
- function_item visited_styles_enabled @350-352
- function_item app_units_per_device_pixel @355-360
- function_item app_units_per_device_pixel_at_unit_full_zoom @363-368
- function_item device_pixel_ratio_ignoring_full_zoom @371-374
- function_item device_pixel_ratio @377-390
- function_item forced_colors @394-397
- function_item system_nscolor @400-406
- function_item is_dark_color_scheme @409-411
- function_item default_background_color @417-421
- function_item default_color @426-430
- function_item text_zoom @434-440
- function_item safe_area_insets @443-456
- function_item is_supported_mime_type @459-463
- function_item chrome_rules_enabled_for_document @470-472
- function_item link_parameters @477-479
- function_item fmt @483-492

### servo/components/style/device/mod.rs

Blob: `6e3873b3a570d55a8cbe94b45519fc04d3d19af2`. Grammar: rust. Status: syntax-clean.

- mod_item gecko @25-25
- mod_item servo @27-27
- struct_item Device @42-91
- function_item environment @96-98
- function_item default_computed_values @102-104
- function_item default_computed_values_arc @107-109
- function_item set_root_style @113-115
- function_item root_font_size @118-121
- function_item set_root_font_size @124-126
- function_item root_line_height @129-134
- function_item set_root_line_height @137-140
- function_item root_font_metrics_ex @143-148
- function_item set_root_font_metrics_ex @151-155
- function_item root_font_metrics_cap @158-163
- function_item set_root_font_metrics_cap @166-170
- function_item root_font_metrics_ch @173-178
- function_item set_root_font_metrics_ch @181-185
- function_item root_font_metrics_ic @188-193
- function_item set_root_font_metrics_ic @196-200
- function_item ensure_root_font_metrics_updated @202-208
- function_item update_root_font_metrics @212-252
- function_item used_root_font_size @255-257
- function_item used_root_line_height @260-262
- function_item used_root_font_metrics @265-267
- function_item used_viewport_size @270-272
- function_item used_dynamic_viewport_size @275-277
- function_item used_font_metrics @280-282
- function_item body_text_color @285-287
- function_item set_body_text_color @292-294
- function_item zoom_text @298-300
- function_item unzoom_text @304-306

### servo/components/style/device/servo.rs

Blob: `de7170b49345e5ccc87e2c14872c0a16fad0b985`. Grammar: rust. Status: syntax-clean.

- trait_item FontMetricsProvider @43-54
- function_signature_item query_font_metrics @45-51
- function_signature_item base_size_for_generic @53-53
- struct_item ExtraDeviceData @57-81
- function_item new @85-127
- function_item calc_line_height @132-145
- function_item quirks_mode @148-150
- function_item document_random_seed @155-158
- function_item base_size_for_generic @161-165
- function_item animation_name_may_be_referenced @168-171
- function_item viewport_size @174-176
- function_item set_viewport_size @183-185
- function_item au_viewport_size @190-195
- function_item au_viewport_size_for_viewport_unit_resolution @198-206
- function_item app_units_per_device_pixel @209-211
- function_item device_pixel_ratio_ignoring_full_zoom @214-216
- function_item device_pixel_ratio @219-221
- function_item set_device_pixel_ratio @228-233
- function_item set_device_size @240-242
- function_item device_size @246-248
- function_item scrollbar_inline_size @251-254
- function_item query_font_metrics @257-271
- function_item set_media_type @278-280
- function_item media_type @283-285
- function_item forced_colors @288-290
- function_item default_background_color @293-295
- function_item default_color @298-300
- function_item set_color_scheme @307-309
- function_item color_scheme @312-314
- function_item set_primary_pointer_capabilities @321-323
- function_item primary_pointer_capabilities @326-328
- function_item set_all_pointer_capabilities @335-337
- function_item all_pointer_capabilities @340-342
- function_item is_dark_color_scheme @344-358
- function_item system_color @360-472
- function_item srgb @365-367
- function_item text_zoom @476-479
- function_item safe_area_insets @482-484
- function_item is_supported_mime_type @487-501
- function_item chrome_rules_enabled_for_document @505-507
- function_item link_parameters @512-514

### servo/components/style/dom.rs

Blob: `27dfb437541d3e40a52d095da1d04b7facd408b4`. Grammar: rust. Status: syntax-clean.

- trait_item NodeInfo @42-47
- function_signature_item is_element @44-44
- function_signature_item is_text_node @46-46
- struct_item LayoutIterator @50-50
- function_item next @59-67
- struct_item DomChildren @71-71
- function_item next @78-82
- struct_item DomDescendants @86-89
- function_item next_skipping_children @97-101
- function_item next @111-115
- trait_item TDocument @119-149
- function_signature_item as_node @124-124
- function_signature_item is_html_document @127-127
- function_signature_item quirks_mode @130-130
- function_item elements_with_id @137-145
- function_signature_item shared_lock @148-148
- trait_item TNode @153-279
- function_signature_item parent_node @164-164
- function_signature_item first_child @167-167
- function_signature_item last_child @170-170
- function_signature_item prev_sibling @173-173
- function_signature_item next_sibling @176-176
- function_signature_item owner_doc @179-179
- function_item dom_children @183-185
- function_signature_item is_in_document @188-188
- function_item dom_descendants @192-197
- function_item next_in_preorder @202-207
- function_item next_in_preorder_skipping_children @214-231
- function_item depth @234-242
- function_signature_item traversal_parent @246-246
- function_item parent_element @249-251
- function_item parent_element_or_host @254-263
- function_signature_item opaque @266-266
- function_signature_item debug_id @269-269
- function_signature_item as_element @272-272
- function_signature_item as_document @275-275
- function_signature_item as_shadow_root @278-278
- struct_item ShowSubtree @283-283
- function_item fmt @285-288
- struct_item ShowSubtreeData @293-293
- function_item fmt @295-298
- struct_item ShowSubtreeDataAndPrimaryValues @304-304
- function_item fmt @307-310
- function_item fmt_with_data @313-326
- function_item fmt_with_data_and_primary_values @329-343
- function_item fmt_subtree @345-361
- trait_item TShadowRoot @364-406
- function_signature_item as_node @369-369
- function_signature_item host @372-372
- function_signature_item style_data @375-377
- function_item parts @380-385
- function_item elements_with_id @392-400
- function_item implicit_scope_for_sheet @403-405
- trait_item TElement @409-985
- function_signature_item as_node @430-430
- function_item owner_doc_matches_for_testing @437-439
- function_item matches_user_and_content_rules @444-446
- function_item traversal_parent @450-452
- function_signature_item traversal_children @455-455
- function_item inheritance_parent @463-465
- function_item each_anonymous_content_child @469-473
- function_signature_item is_html_element @476-476
- function_signature_item is_mathml_element @479-479
- function_signature_item is_svg_element @482-482
- function_item is_xul_element @485-487
- function_item is_html_media_element @490-492
- function_item slotted_nodes @495-497
- function_signature_item style_attribute @500-500
- function_item smil_override @503-505
- function_item animation_declarations @510-519
- function_signature_item animation_rule @522-525
- function_signature_item transition_rule @528-531
- function_signature_item state @534-534
- function_signature_item has_part_attr @537-537
- function_signature_item exports_any_part @540-540
- function_signature_item id @543-543
- function_signature_item each_class @546-548
- function_signature_item each_custom_state @551-553
- function_item each_part @556-560
- function_signature_item each_attr_name @563-565
- function_item each_exported_part @569-573
- function_item may_generate_pseudo @581-595
- function_signature_item has_dirty_descendants @602-602
- function_signature_item has_snapshot @607-607
- function_signature_item handled_snapshot @610-610
- function_signature_item set_handled_snapshot @613-613
- function_item has_current_styles @617-635
- function_signature_item set_dirty_descendants @640-640
- function_signature_item unset_dirty_descendants @645-645
- function_item has_animation_only_dirty_descendants @649-651
- function_item set_animation_only_dirty_descendants @657-657
- function_item unset_animation_only_dirty_descendants @662-662
- function_item clear_descendant_bits @669-673
- function_item is_visited_link @678-680
- function_item implemented_pseudo_element @690-692
- function_signature_item store_children_to_process @696-696
- function_signature_item did_process_child @700-700
- function_signature_item ensure_data @706-706
- function_signature_item clear_data @711-711
- function_signature_item has_data @714-714
- function_signature_item borrow_data @717-717
- function_signature_item mutate_data @720-720
- function_signature_item skip_item_display_fixup @725-725
- function_signature_item may_have_animations @730-730
- function_signature_item update_animations @734-738
- function_signature_item has_animations @743-743
- function_signature_item has_css_animations @748-752
- function_signature_item has_css_transitions @757-761
- function_item has_animation_restyle_hints @764-770
- function_item note_highlight_pseudo_style_invalidated @775-775
- function_signature_item shadow_root @778-778
- function_signature_item containing_shadow @781-781
- function_item ultimate_originating_element @787-795
- function_item each_applicable_non_document_style_rule_data @807-875
- function_signature_item needs_transitions_update @882-886
- function_signature_item lang_attr @890-890
- function_signature_item match_element_lang @897-897
- function_signature_item is_html_document_body_element @901-901
- function_signature_item synthesize_presentational_hints_for_legacy_attributes @905-911
- function_item synthesize_view_transition_dynamic_rules @916-921
- function_signature_item local_name @924-924
- function_signature_item namespace @927-928
- function_signature_item query_container_size @933-936
- function_signature_item has_selector_flags @939-939
- function_signature_item relative_selector_search_direction @942-942
- function_item implicit_scope_for_sheet_in_shadow_root @945-950
- function_item compute_layout_damage @953-955
- function_signature_item get_attr @958-958
- function_item get_tree_counting_result @963-984
- trait_item ElementContext @988-1002
- function_signature_item opaque_element @990-990
- function_signature_item opaque_parent @993-993
- function_signature_item get_attr @996-996
- function_signature_item get_tree_counting_result @1001-1001
- function_item opaque_element @1005-1007
- function_item opaque_parent @1009-1011
- function_item get_attr @1013-1015
- function_item get_tree_counting_result @1017-1019
- struct_item AttributeTracker @1026-1031
- function_item new @1035-1040
- function_item new_dummy @1043-1048
- function_item finalize @1051-1053
- function_item query @1056-1068
- struct_item DummyElementContext @1073-1073
- function_item get_attr @1076-1078
- function_item opaque_element @1080-1082
- function_item opaque_parent @1084-1086
- function_item get_tree_counting_result @1088-1090
- struct_item SendNode @1100-1100
- function_item new @1104-1106
- function_item deref @1110-1112
- struct_item SendElement @1118-1118
- function_item new @1122-1124
- function_item deref @1128-1130

### servo/components/style/dom_apis.rs

Blob: `52ec9bfafe96fa4f0a7008c519d233036fa4dfaf`. Grammar: rust. Status: syntax-clean.

- function_item element_matches @30-51
- function_item element_closest @54-84
- trait_item SelectorQuery @88-100
- function_signature_item should_stop_after_first_match @93-93
- function_signature_item append_element @96-96
- function_signature_item is_empty @99-99
- struct_item QueryAll @106-106
- function_item should_stop_after_first_match @111-113
- function_item append_element @115-117
- function_item is_empty @119-121
- struct_item QueryFirst @125-125
- function_item should_stop_after_first_match @130-132
- function_item append_element @134-138
- function_item is_empty @140-142
- struct_item QuerySelectorProcessor @145-155
- function_item light_tree_only @163-165
- function_item check_outer_dependency @167-173
- function_item collect_invalidations @175-212
- function_item matching_context @214-216
- function_item sibling_traversal_map @218-220
- function_item should_process_descendants @222-228
- function_item invalidated_self @230-232
- function_item invalidated_sibling @234-236
- function_item recursion_limit_exceeded @238-238
- function_item invalidated_descendants @239-239
- enum_item Operation @242-246
- function_item from @250-256
- function_item collect_all_elements @259-293
- function_item connected_element_is_descendant_of @298-332
- function_item fast_connected_elements_with_id @336-361
- function_item collect_elements_with_id @364-402
- function_item get_attr_name @404-424
- function_item get_id @426-446
- function_item query_selector_single_query @449-588
- enum_item SimpleFilter @590-594
- function_item query_selector_fast @605-835
- function_item query_selector_slow @838-854
- enum_item MayUseInvalidation @858-863
- function_item query_selector @866-939

### servo/components/style/driver.rs

Blob: `38ab1ebcb481776fc268543a3e5a6223fa366f5d`. Grammar: rust. Status: syntax-clean.

- function_item should_report_statistics @20-22
- function_item should_report_statistics @25-27
- function_item report_statistics @30-32
- function_item report_statistics @35-47
- function_item with_pool_in_place_scope @49-72
- function_item work_unit_max @75-77
- function_item traverse_dom @88-172

### servo/components/style/error_reporting.rs

Blob: `c2f44307efabaeec5134208d157cb82e27734271`. Grammar: rust. Status: syntax-clean.

- enum_item ContextualParseError @20-61
- function_item fmt @64-197
- function_item parse_error_to_str @65-87
- trait_item ParseErrorReporter @201-212
- function_signature_item report_error @206-211
- struct_item RustLogReporter @221-221
- function_item report_error @225-240
- enum_item SelectorWarningKind @247-254
- function_item from_selector @258-267
- struct_item PerCompoundState @271-278
- function_item new @281-287
- struct_item UnconstrainedRelativeSelectorVisitor @291-293
- function_item new @296-300
- function_item has_warning @302-340
- function_item visit_simple_selector @346-357
- function_item visit_selector_list @359-402
- function_item visit_relative_selector_list @404-419
- struct_item SiblingCombinatorAfterScopeSelectorVisitor @422-425
- function_item new @428-433
- function_item has_warning @434-440
- function_item find_never_matching_scope_selector @442-445
- function_item visit_simple_selector @451-460
- function_item visit_selector_list @462-472
- function_item visit_complex_selector @474-481

### servo/components/style/font_face.rs

Blob: `8d840001709bedac32668e0e2d925707bf597f0d`. Grammar: rust. Status: syntax-clean.

- enum_item Source @31-37
- struct_item SourceList @42-42
- function_item parse @48-64
- enum_item FontFaceSourceFormatKeyword @74-86
- struct_item FontFaceSourceTechFlags @92-92
- function_item parse_one @122-136
- function_item parse @140-154
- function_item to_css @159-191
- struct_item FontFaceRule @196-201
- function_item empty @205-210
- enum_item FontFaceSourceListComponent @221-230
- enum_item FontFaceSourceFormat @235-238
- struct_item UrlSource @246-253
- function_item to_css @256-272
- enum_item FontDisplay @294-300
- struct_item FontWeightRange @333-333
- struct_item ComputedFontWeightRange @343-343
- function_item sort_range @346-348
- function_item compute @352-355
- struct_item FontWidthRange @362-362
- struct_item ComputedFontWidthRange @370-370
- function_item compute @375-388
- function_item compute_width @376-384
- enum_item FontStyleRange @396-399
- struct_item ComputedFontStyleRange @406-406
- function_item parse @409-430
- function_item to_css @434-458
- function_item compute @463-471
- function_item parse_font_face_block @477-497
- function_item parse @500-547
- function_item to_css @552-556

### servo/components/style/font_metrics.rs

Blob: `75018c5677588c45c1caa7d8d840c17838cffcac`. Grammar: rust. Status: syntax-clean.

- struct_item FontMetrics @14-31
- function_item default @34-44
- function_item x_height_or_default @49-59
- function_item zero_advance_measure_or_default @62-86
- function_item cap_height_or_default @89-97
- function_item ic_width_or_default @100-110
- enum_item FontMetricsOrientation @115-124

### servo/components/style/gecko/arc_types.rs

Blob: `a9ceea73e31e9503bf4ea28798652423213e603d`. Grammar: rust. Status: syntax-clean.


### servo/components/style/gecko/conversions.rs

Blob: `f4c994bb1c7f28d0b0e451d81892db424b1a78f1`. Grammar: rust. Status: syntax-clean.

- function_item from @18-25
- function_item from @29-48
- function_item from @52-58

### servo/components/style/gecko/data.rs

Blob: `14bd0ea4c8b6f926211d991a2e791923950ba0d4`. Grammar: rust. Status: syntax-clean.

- struct_item GeckoStyleSheet @30-30
- function_item fmt @43-50
- function_item new @56-62
- function_item from_addrefed @67-70
- function_item hack_is_null @75-77
- function_item raw @80-82
- function_item inner @84-86
- function_item raw_contents @88-91
- function_item drop @95-97
- function_item clone @101-104
- function_item media @108-118
- function_item enabled @123-125
- function_item contents @128-130
- function_item implicit_scope_root @132-156
- struct_item PerDocumentStyleDataImpl @161-170
- struct_item PerDocumentStyleData @175-175
- function_item new @179-188
- function_item borrow @191-193
- function_item borrow_mut @196-198
- function_item flush_stylesheets @203-208
- function_item default_computed_values @211-213
- function_item add_size_of @216-218

### servo/components/style/gecko/media_features.rs

Blob: `199216dbc108836d24780c976f21883c336040da`. Grammar: rust. Status: syntax-clean.

- function_item device_size @20-27
- function_item eval_width @30-32
- function_item eval_device_width @35-37
- function_item eval_height @40-42
- function_item eval_device_height @45-47
- function_item eval_aspect_ratio_for @49-55
- function_item eval_aspect_ratio @58-60
- function_item eval_device_aspect_ratio @63-65
- function_item eval_device_pixel_ratio @68-70
- function_item eval_orientation @73-75
- function_item eval_device_orientation @78-80
- function_item document_picture_in_picture_enabled @82-84
- enum_item DisplayMode @90-97
- function_item eval_display_mode @100-109
- function_item eval_grid @112-116
- function_item eval_transform_3d @119-121
- enum_item Scan @125-128
- function_item eval_scan @131-135
- function_item eval_color @138-140
- function_item eval_color_index @143-146
- function_item eval_monochrome @149-152
- enum_item ColorGamut @159-166
- function_item eval_color_gamut @169-178
- function_item eval_resolution @181-185
- enum_item PrefersReducedMotion @189-192
- enum_item PrefersReducedTransparency @196-199
- enum_item DynamicRange @208-211
- function_item eval_prefers_reduced_motion @214-229
- function_item eval_prefers_reduced_transparency @232-248
- enum_item PrefersContrast @254-263
- function_item eval_prefers_contrast @266-273
- function_item eval_forced_colors @276-282
- enum_item InvertedColors @288-293
- function_item eval_inverted_colors @296-308
- enum_item OverflowBlock @312-316
- function_item eval_overflow_block @319-338
- enum_item OverflowInline @342-345
- function_item eval_overflow_inline @348-360
- enum_item Update @364-368
- function_item eval_update @371-388
- function_item do_eval_prefers_color_scheme @390-402
- function_item eval_prefers_color_scheme @405-407
- function_item eval_content_prefers_color_scheme @409-414
- function_item eval_dynamic_range @417-424
- function_item eval_video_dynamic_range @426-433
- function_item primary_pointer_capabilities @444-448
- function_item all_pointer_capabilities @450-454
- enum_item Pointer @458-462
- function_item eval_pointer_capabilities @464-478
- function_item eval_pointer @481-483
- function_item eval_any_pointer @486-488
- enum_item Hover @492-495
- function_item eval_hover_capabilities @497-511
- function_item eval_hover @514-516
- function_item eval_any_hover @519-521
- function_item eval_moz_is_glyph @523-525
- function_item eval_moz_in_android_pip_mode @527-529
- function_item eval_moz_print_preview @531-537
- function_item eval_moz_is_resource_document @539-541
- enum_item Platform @546-560
- function_item eval_moz_platform @562-569
- enum_item GtkThemeFamily @574-583
- function_item eval_gtk_theme_family @585-591
- enum_item Scripting @597-607
- function_item eval_scripting @610-616
- function_item eval_moz_overlay_scrollbars @618-620
- function_item eval_moz_mac_rtl @622-624
- function_item eval_moz_native_theme @626-631
- function_item get_lnf_int @633-635
- function_item get_lnf_int_as_bool @637-639

### servo/components/style/gecko/mod.rs

Blob: `ac071df12d13ebce479cd8fbdbb2eed53531faf6`. Grammar: rust. Status: syntax-clean.

- mod_item non_ts_pseudo_class_list @8-8
- mod_item arc_types @10-10
- mod_item conversions @11-11
- mod_item data @12-12
- mod_item media_features @13-13
- mod_item pseudo_element @14-14
- mod_item restyle_damage @15-15
- mod_item selector_parser @16-16
- mod_item snapshot @17-17
- mod_item snapshot_helpers @18-18
- mod_item traversal @19-19
- mod_item wrapper @20-20

### servo/components/style/gecko/non_ts_pseudo_class_list.rs

Blob: `0d98e5c1f0cc6f6e72f233b30ec2a9803827b9d8`. Grammar: rust. Status: syntax-clean.


### servo/components/style/gecko/pseudo_element.rs

Blob: `ae60754aaadc9d791062e206436f5237cb63af1b`. Grammar: rust. Status: syntax-clean.

- enum_item Target @78-84
- struct_item PtNameAndClassSelector @102-102
- function_item from_name @110-112
- function_item name @115-118
- function_item classes @121-124
- function_item name_and_classes @127-129
- function_item parse @137-196
- function_item to_css @200-217
- function_item valid_after_slotted @225-228
- function_item valid_after_before_or_after @233-235
- function_item accepts_state_pseudo_classes @238-242
- function_item specificity_count @245-247
- function_item is_in_pseudo_element_tree @250-254
- function_item parses_as_element_backed @256-259
- function_item is_before_or_after @263-265
- function_item is_element_backed @272-275
- function_item cascade_type @284-295
- function_item index @299-301
- function_item discriminant @304-308
- function_item is_unknown_webkit_pseudo_element @312-314
- function_item is_anon_box @318-320
- function_item is_eager @324-326
- function_item has_argument @330-332
- function_item eager_index @336-341
- function_item from_eager_index @345-347
- function_item animations_stored_in_parent @352-357
- function_item is_before @361-363
- function_item is_after @367-369
- function_item is_marker @373-375
- function_item is_selection @379-381
- function_item is_first_letter @385-387
- function_item is_first_line @391-393
- function_item is_lazy @397-399
- function_item highlight_name @402-407
- function_item is_highlight @410-412
- function_item is_target_text @416-418
- function_item is_lazy_painted_highlight_pseudo @424-426
- function_item is_named_view_transition @429-437
- function_item specificity_count @440-459
- function_item supports_user_action_state @462-465
- function_item is_pseudo_enabled_for_url @471-479
- function_item enabled_in_content @482-499
- function_item enabled_in_ua_sheets @502-504
- function_item enabled_in_chrome @507-510
- function_item skip_item_display_fixup @515-519
- function_item is_precomputed @523-525
- function_item should_exist @530-542
- function_item parse_ignore_enabled_state @547-589
- function_item matches_named_view_transition_pseudo_element @592-630

### servo/components/style/gecko/pseudo_element_definition.mako.rs

Blob: `c94230ebe61b5d4413d66310590c4127c927b60f`. Grammar: rust. Status: contains-errors.

- function_item matches @273-288
- function_item to_css @292-325

### servo/components/style/gecko/restyle_damage.rs

Blob: `50fd27c758a4b90afeacaa9107aace3615408959`. Grammar: rust. Status: syntax-clean.

- struct_item GeckoRestyleDamage @17-17
- function_item new @22-24
- function_item as_change_hint @28-30
- function_item empty @34-36
- function_item is_empty @40-42
- function_item compute_style_difference @46-82
- function_item contains @85-87
- function_item reconstruct @91-93
- function_item default @97-99
- function_item bitor @104-106
- function_item bitor_assign @110-112
- function_item bitand @117-119
- function_item not @124-126

### servo/components/style/gecko/selector_parser.rs

Blob: `b677a2a49ecad54e06c82b25c6922bdea746c304`. Grammar: rust. Status: syntax-clean.

- struct_item Lang @43-43
- struct_item CustomState @47-47
- struct_item HeadingSelectorData @52-52
- function_item matches_state @58-73
- function_item to_css @104-165
- function_item parse_non_functional @172-190
- function_item has_any_flag @193-216
- function_item is_enabled_in_content @220-231
- function_item state_flag @234-257
- function_item document_state_flag @260-270
- function_item needs_cache_revalidation @274-292
- function_item is_active_or_hover @297-299
- function_item is_user_action_state @303-308
- struct_item SelectorImpl @313-313
- struct_item ExtraMatchingData @318-329
- function_item should_collect_attr_hash @344-346
- function_item is_pseudo_class_enabled @350-368
- function_item is_pseudo_element_enabled @370-384
- function_item parse_functional_pseudo_element_with_name @388-446
- function_item parse_parent_selector @453-455
- function_item parse_slotted @458-460
- function_item parse_host @463-465
- function_item parse_nth_child_of @468-470
- function_item parse_is_and_where @473-475
- function_item parse_has @478-480
- function_item parse_part @483-485
- function_item is_is_alias @488-490
- function_item allow_forgiving_selectors @493-495
- function_item parse_non_ts_pseudo_class @497-506
- function_item parse_non_ts_functional_pseudo_class @508-559
- function_item parse_pseudo_element @561-578
- function_item parse_functional_pseudo_element @580-593
- function_item default_namespace @595-597
- function_item namespace_for_prefix @599-601
- function_item each_eagerly_cascaded_pseudo_element @608-615

### servo/components/style/gecko/snapshot.rs

Blob: `dedab328e167b7d69b82408e269628725fb52d14`. Grammar: rust. Status: syntax-clean.

- function_item get @40-47
- function_item has_any @52-54
- function_item has_other_pseudo_class_state @59-61
- function_item id_changed @65-67
- function_item class_changed @71-73
- function_item each_attr_changed @77-84
- function_item attr_matches @87-94
- function_item debug_list_attributes @98-105
- function_item state @107-113
- function_item has_attrs @116-118
- function_item id_attr @121-127
- function_item is_part @130-137
- function_item imported_part @140-142
- function_item has_class @145-151
- function_item each_class @154-163
- function_item lang_attr @166-173
- function_item has_custom_states @177-179
- function_item has_custom_state @183-189
- function_item each_custom_state @192-201

### servo/components/style/gecko/snapshot_helpers.rs

Blob: `c02df0e918903cc33a38eb30216a1ce944fa3669`. Grammar: rust. Status: syntax-clean.

- enum_item Class @23-27
- function_item base_type @30-32
- function_item ptr @35-37
- function_item get_class_or_part_from_attr @40-65
- function_item get_id_from_attr @68-74
- function_item is_nodeinfo @78-80
- function_item as_nodeinfo @83-86
- function_item namespace_id @89-94
- function_item name @98-104
- function_item find_attr @109-117
- function_item get_id @121-123
- function_item each_exported_part @126-146
- function_item imported_part @149-159
- function_item atom_array_atoms @162-166
- function_item atom_array_may_contain @169-173
- function_item has_class_or_part @178-203
- function_item each_class_or_part @208-223
- function_item classes_changed @227-247
- function_item attr_matches @251-275
- function_item attr_matches_checked_name @279-334

### servo/components/style/gecko/traversal.rs

Blob: `92aaaba723790dc39225f8d82368d5c5d6831b26`. Grammar: rust. Status: syntax-clean.

- struct_item RecalcStyleOnly @14-16
- function_item new @20-22
- function_item process_preorder @26-38
- function_item process_postorder @40-42
- function_item needs_postorder_traversal @45-47
- function_item shared_context @49-51

### servo/components/style/gecko/wrapper.rs

Blob: `7a6361ee1117e9eb0443fd9f942e7b6cf411a772`. Grammar: rust. Status: syntax-clean.

- function_item elements_with_id @88-106
- function_item static_assert @98-102
- struct_item GeckoDocument @110-110
- function_item as_node @116-118
- function_item is_html_document @121-123
- function_item quirks_mode @126-128
- function_item elements_with_id @131-138
- function_item shared_lock @140-142
- struct_item GeckoShadowRoot @147-147
- function_item fmt @150-153
- function_item eq @158-160
- function_item as_node @167-169
- function_item host @172-174
- function_item style_data @177-183
- function_item elements_with_id @186-193
- function_item parts @196-212
- function_item static_assert @203-209
- function_item implicit_scope_for_sheet @215-221
- struct_item GeckoNode @233-233
- function_item eq @237-239
- function_item fmt @243-261
- function_item is_document @266-270
- function_item is_shadow_root @273-275
- function_item from_content @278-280
- function_item set_flags @283-285
- function_item flags_atomic_for @287-296
- function_item flags_atomic @299-301
- function_item flags @304-306
- function_item may_have_element_children @309-311
- function_item selector_flags_atomic @314-316
- function_item selector_flags @319-321
- function_item set_selector_flags @324-327
- function_item node_info @330-333
- function_item bool_flags @338-340
- function_item bool_flags @344-346
- function_item get_bool_flag @349-351
- function_item is_in_shadow_tree @355-358
- function_item flattened_tree_parent_is_parent @367-390
- function_item flattened_tree_parent @393-413
- function_item contains_non_whitespace_content @416-418
- function_item prev_sibling_element @422-434
- function_item next_sibling_element @438-450
- function_item last_child_element @454-460
- function_item is_element @465-467
- function_item is_text_node @469-473
- function_item parent_node @482-484
- function_item first_child @487-495
- function_item last_child @498-500
- function_item prev_sibling @503-511
- function_item next_sibling @514-522
- function_item owner_doc @525-528
- function_item is_in_document @531-533
- function_item traversal_parent @535-537
- function_item opaque @540-543
- function_item debug_id @545-547
- function_item as_element @550-558
- function_item as_document @561-568
- function_item as_shadow_root @571-579
- enum_item GeckoChildrenIterator @594-600
- function_item drop @603-609
- function_item next @614-632
- struct_item GeckoElement @637-637
- function_item fmt @640-651
- function_item get_data @657-659
- function_item has_any_animation @663-665
- function_item has_attr_impl @669-672
- function_item attrs @675-685
- function_item get_part_attr @688-693
- function_item get_class_attr @696-709
- function_item may_have_anonymous_children @712-715
- function_item flags @718-720
- function_item set_flags @723-725
- function_item unset_flags @728-732
- function_item descendants_need_frames @736-738
- function_item needs_frame @742-744
- function_item dom_slots @748-756
- function_item extended_slots @760-767
- function_item namespace_id @770-772
- function_item has_id @775-778
- function_item state_internal @781-789
- function_item document_state @792-794
- function_item may_have_class @797-800
- function_item has_properties @803-807
- function_item may_have_style_attribute @810-813
- function_item note_explicit_hints @822-852
- function_item is_root_of_native_anonymous_subtree @856-858
- function_item in_native_anonymous_subtree @862-864
- function_item in_ua_widget @868-870
- function_item css_transitions_info @872-887
- function_item needs_transitions_update_per_property @889-924
- function_item slow_selector_flags @927-929
- function_item slow_selector_flags_from_node_selector_flags @933-943
- function_item selector_flags_to_node_flags @948-986
- function_item get_animation_rule @988-1010
- function_item namespace_id_to_atom @1015-1020
- function_item implicit_scope_for_sheet_in_shadow_root @1026-1035
- function_item inheritance_parent @1037-1047
- function_item traversal_children @1049-1068
- function_item is_html_element @1071-1073
- function_item is_mathml_element @1076-1078
- function_item is_svg_element @1081-1083
- function_item is_xul_element @1086-1088
- function_item is_html_media_element @1091-1095
- function_item local_name @1098-1100
- function_item namespace @1103-1105
- function_item query_container_size @1108-1125
- function_item slotted_nodes @1129-1152
- function_item static_assert @1145-1149
- function_item shadow_root @1155-1158
- function_item note_highlight_pseudo_style_invalidated @1160-1165
- function_item containing_shadow @1168-1174
- function_item each_anonymous_content_child @1176-1196
- function_item as_node @1199-1201
- function_item owner_doc_matches_for_testing @1203-1205
- function_item style_attribute @1207-1216
- function_item smil_override @1218-1225
- function_item animation_rule @1227-1232
- function_item transition_rule @1234-1239
- function_item state @1242-1244
- function_item has_part_attr @1247-1250
- function_item exports_any_part @1253-1255
- function_item id @1259-1264
- function_item each_attr_name @1266-1273
- function_item each_class @1275-1285
- function_item each_custom_state @1288-1299
- function_item each_exported_part @1302-1307
- function_item each_part @1309-1319
- function_item has_snapshot @1322-1324
- function_item handled_snapshot @1327-1329
- function_item set_handled_snapshot @1331-1334
- function_item has_dirty_descendants @1337-1339
- function_item set_dirty_descendants @1341-1345
- function_item unset_dirty_descendants @1347-1349
- function_item has_animation_only_dirty_descendants @1352-1354
- function_item set_animation_only_dirty_descendants @1356-1358
- function_item unset_animation_only_dirty_descendants @1360-1362
- function_item clear_descendant_bits @1364-1372
- function_item is_visited_link @1374-1376
- function_item matches_user_and_content_rules @1382-1384
- function_item implemented_pseudo_element @1387-1405
- function_item store_children_to_process @1408-1410
- function_item did_process_child @1412-1414
- function_item ensure_data @1416-1423
- function_item clear_data @1425-1446
- function_item skip_item_display_fixup @1449-1455
- function_item may_have_animations @1458-1471
- function_item update_animations @1475-1499
- function_item has_animations @1502-1504
- function_item has_css_animations @1506-1508
- function_item has_css_transitions @1510-1512
- function_item needs_transitions_update @1524-1564
- function_item has_data @1568-1570
- function_item borrow_data @1573-1575
- function_item mutate_data @1578-1580
- function_item lang_attr @1583-1590
- function_item match_element_lang @1592-1607
- function_item is_html_document_body_element @1609-1619
- function_item synthesize_view_transition_dynamic_rules @1621-1641
- function_item synthesize_presentational_hints_for_legacy_attributes @1643-1761
- function_item static_pres_hint @1657-1661
- function_item to_pres_hint @1663-1669
- function_item pres_hint_from_raw @1675-1682
- function_item has_selector_flags @1763-1766
- function_item relative_selector_search_direction @1768-1780
- function_item get_attr @1782-1797
- function_item eq @1802-1804
- function_item hash @1811-1813
- function_item opaque @1820-1822
- function_item parent_element @1825-1828
- function_item parent_node_is_shadow_root @1831-1835
- function_item containing_shadow_host @1838-1841
- function_item is_pseudo_element @1844-1846
- function_item pseudo_element_originating_element @1849-1863
- function_item assigned_slot @1866-1870
- function_item prev_sibling_element @1873-1882
- function_item next_sibling_element @1885-1894
- function_item first_element_child @1897-1906
- function_item apply_selector_flags @1908-1924
- function_item has_attr_in_no_namespace @1926-1933
- function_item attr_matches @1935-1942
- function_item is_root @1945-1964
- function_item is_empty @1966-1971
- function_item has_local_name @1974-1976
- function_item has_namespace @1979-1981
- function_item is_same_type @1984-1986
- function_item match_non_ts_pseudo_class @1988-2143
- function_item match_pseudo_element @2145-2159
- function_item is_link @2162-2164
- function_item has_id @2167-2178
- function_item is_part @2181-2188
- function_item imported_part @2191-2193
- function_item has_class @2196-2203
- function_item has_custom_state @2206-2217
- function_item is_html_element_in_html_document @2220-2222
- function_item is_html_slot_element @2225-2227
- function_item ignores_nth_child_selectors @2230-2232
- function_item add_element_unique_hashes @2234-2237
- function_item subtree_filter @2240-2242

### servo/components/style/gecko_bindings/mod.rs

Blob: `5fe8233cec7582bc289cd742f86bb0435ddf6f31`. Grammar: rust. Status: syntax-clean.

- mod_item structs @28-30
- mod_item sugar @34-34

### servo/components/style/gecko_bindings/sugar/mod.rs

Blob: `e639abeda09ad31dea0918eb159ec6a41a476b01`. Grammar: rust. Status: syntax-clean.

- mod_item ns_com_ptr @7-7
- mod_item ns_compatibility @8-8
- mod_item ns_style_auto_array @9-9
- mod_item origin_flags @10-10
- mod_item ownership @11-11
- mod_item refptr @12-12

### servo/components/style/gecko_bindings/sugar/ns_com_ptr.rs

Blob: `1c54541bd8055cb683d4945bc3c1ad87d251806d`. Grammar: rust. Status: syntax-clean.

- function_item raw @12-14

### servo/components/style/gecko_bindings/sugar/ns_compatibility.rs

Blob: `f4b81e9f7909ffc203f443d988200770be5b9683`. Grammar: rust. Status: syntax-clean.

- function_item from @12-18

### servo/components/style/gecko_bindings/sugar/ns_style_auto_array.rs

Blob: `57ab01bc81fcb91eee08d2cb276fde61bbf85eb4`. Grammar: rust. Status: syntax-clean.

- function_item index @20-25
- function_item index_mut @29-34
- function_item iter_mut @39-41
- function_item iter @44-46
- function_item len @52-54
- function_item ensure_len @59-66
- function_item ensure_len @71-78
- function_item ensure_len @83-90
- function_item ensure_len @95-102
- function_item into_iter @108-110

### servo/components/style/gecko_bindings/sugar/origin_flags.rs

Blob: `b27060405a43d14959543b1cdb85dc063f1d652e`. Grammar: rust. Status: syntax-clean.

- function_item assert_flags_match @11-19
- function_item from @22-24
- function_item from @28-30

### servo/components/style/gecko_bindings/sugar/ownership.rs

Blob: `b3a6ce44da86fbe0eaf49e4151a661de8c166e50`. Grammar: rust. Status: syntax-clean.

- struct_item Strong @19-22
- function_item from @25-30
- function_item from @34-39
- function_item is_null @45-47
- function_item null @51-56
- function_item deref @61-63
- function_item deref_mut @67-69

### servo/components/style/gecko_bindings/sugar/refptr.rs

Blob: `1c61f34c5ae6b95c6286637b58263d2d8890cdfe`. Grammar: rust. Status: syntax-clean.

- trait_item RefCounted @17-22
- function_signature_item addref @19-19
- function_signature_item release @21-21
- trait_item ThreadSafeRefCounted @25-25
- struct_item RefPtr @29-32
- function_item fmt @35-39
- function_item from_addrefed @46-52
- function_item is_null @55-57
- function_item null @60-65
- function_item new @70-77
- function_item forget @82-89
- function_item get @92-94
- function_item addref @97-103
- function_item release @108-114
- function_item deref @119-122
- function_item to_safe @129-136
- function_item into_safe @139-145
- function_item set @154-161
- function_item clear @167-174
- function_item set_move @181-188
- function_item null @193-198
- function_item from_arc @201-206
- function_item set_arc @209-216
- function_item drop @220-222
- function_item clone @226-232
- function_item eq @236-238
- function_item addref_atom @287-291
- function_item release_atom @294-298

### servo/components/style/gecko_string_cache/mod.rs

Blob: `444cf34c5f2ce145da7bad9800aedfe54820e294`. Grammar: rust. Status: syntax-clean.

- mod_item namespace @49-49
- struct_item Atom @63-63
- function_item serialize @66-72
- struct_item AtomStrVisitor @75-75
- function_item expecting @79-81
- function_item visit_str @83-88
- function_item deserialize @92-97
- struct_item WeakAtom @104-104
- function_item deref @113-123
- function_item precomputed_hash @128-130
- function_item borrow @135-137
- function_item to_owned @144-146
- function_item from @151-153
- function_item to_shmem @157-166
- function_item eq @172-176
- function_item eq @181-183
- function_item new @193-195
- function_item clone @199-201
- function_item get_hash @205-207
- function_item as_slice @211-227
- function_item chars @230-232
- function_item with_str @238-272
- function_item is_static @276-278
- function_item is_ascii_lowercase @282-284
- function_item len @288-290
- function_item is_empty @294-296
- function_item as_ptr @300-303
- function_item to_ascii_lowercase @307-329
- function_item eq_ignore_ascii_case @333-346
- function_item eq_ignore_ascii_case_slow @348-363
- function_item fmt @367-369
- function_item fmt @373-378
- function_item make_handle @382-391
- function_item make_static_handle @394-402
- function_item is_static @406-408
- function_item with @411-419
- function_item from_index_unchecked @424-427
- function_item from_raw @431-437
- function_item from_addrefed @442-445
- function_item into_addrefed @449-453
- function_item hash @457-462
- function_item hash @466-471
- function_item clone @476-484
- function_item drop @489-495
- function_item default @500-502
- function_item fmt @506-508
- function_item fmt @512-514
- function_item from @519-527
- function_item from @532-534
- function_item from @539-541
- function_item from @546-548
- function_item from @553-555

### servo/components/style/gecko_string_cache/namespace.rs

Blob: `75506b678d142dfca51acd77ede040b8989e4d75`. Grammar: rust. Status: syntax-clean.

- struct_item Namespace @41-41
- function_item precomputed_hash @45-47
- struct_item WeakNamespace @52-52
- function_item deref @58-61
- function_item from @65-67
- function_item fmt @71-73
- function_item borrow @78-80
- function_item new @86-88
- function_item clone @93-95

### servo/components/style/global_style_data.rs

Blob: `aa261dbdce3ddf5b0bc3664c8ab3a10881314516`. Grammar: rust. Status: syntax-clean.

- struct_item DummyThreadHandle @31-31
- function_item join @35-37
- struct_item GlobalStyleData @44-50
- struct_item StyleThreadPool @53-62
- function_item thread_name @64-66
- function_item thread_spawn @77-88
- function_item thread_startup @90-98
- function_item thread_shutdown @100-106
- function_item shutdown @110-125
- function_item pool @131-133
- function_item get_thread_handles @136-154
- function_item stylo_threads_pref @158-160
- function_item stylo_threads_pref @163-165

### servo/components/style/invalidation/element/document_state.rs

Blob: `9a2fe3be82388fd90a3a1299ed18ede57af6b990`. Grammar: rust. Status: syntax-clean.

- struct_item InvalidationMatchingData @25-28
- function_item default @32-36
- struct_item DocumentStateInvalidationProcessor @41-47
- function_item new @52-77
- function_item check_outer_dependency @86-92
- function_item collect_invalidations @94-124
- function_item matching_context @126-128
- function_item sibling_traversal_map @130-132
- function_item recursion_limit_exceeded @134-136
- function_item should_process_descendants @138-143
- function_item invalidated_descendants @145-147
- function_item invalidated_self @149-151
- function_item invalidated_sibling @153-155

### servo/components/style/invalidation/element/element_wrapper.rs

Blob: `06046692d91f427b2e76896295b052bdb7e3c2d2`. Grammar: rust. Status: syntax-clean.

- trait_item ElementSnapshot @42-90
- function_signature_item state @44-44
- function_signature_item has_attrs @47-47
- function_item debug_list_attributes @52-54
- function_signature_item id_attr @58-58
- function_signature_item has_class @62-62
- function_signature_item is_part @66-66
- function_signature_item imported_part @69-69
- function_signature_item each_class @73-75
- function_signature_item has_custom_states @78-78
- function_signature_item has_custom_state @81-81
- function_signature_item each_custom_state @84-86
- function_signature_item lang_attr @89-89
- struct_item Snapshots @94-99
- function_item new @103-108
- struct_item ElementWrapper @114-120
- function_item new @127-132
- function_item snapshot @135-152
- function_item state_changes @155-165
- function_item get_lang @170-182
- function_item fmt @189-192
- function_item match_non_ts_pseudo_class @201-288
- function_item apply_selector_flags @290-292
- function_item match_pseudo_element @294-300
- function_item is_link @302-307
- function_item opaque @309-311
- function_item parent_element @313-316
- function_item parent_node_is_shadow_root @318-320
- function_item containing_shadow_host @322-325
- function_item prev_sibling_element @327-330
- function_item next_sibling_element @332-335
- function_item first_element_child @337-340
- function_item is_html_element_in_html_document @343-345
- function_item is_html_slot_element @348-350
- function_item has_local_name @353-358
- function_item has_namespace @361-366
- function_item is_same_type @369-371
- function_item attr_matches @373-385
- function_item has_id @387-394
- function_item is_part @396-401
- function_item imported_part @403-408
- function_item has_class @410-415
- function_item has_custom_state @417-422
- function_item is_empty @424-426
- function_item is_root @428-430
- function_item is_pseudo_element @432-434
- function_item pseudo_element_originating_element @436-440
- function_item assigned_slot @442-446
- function_item add_element_unique_hashes @448-451

### servo/components/style/invalidation/element/invalidation_map.rs

Blob: `c2c1ea51f61265e790084f390bd207baf9b91390`. Grammar: rust. Status: syntax-clean.

- struct_item Dependency @46-77
- function_item selector @80-82
- enum_item NormalDependencyInvalidationKind @87-104
- enum_item RelativeDependencyInvalidationKind @110-123
- enum_item ScopeDependencyInvalidationKind @127-134
- enum_item DependencyInvalidationKind @138-148
- enum_item GeneratedInvalidation @152-157
- function_item get_non_relative_invalidation_kind @161-182
- function_item new @186-198
- function_item for_full_selector_invalidation @207-214
- function_item normal_invalidation_kind @218-223
- function_item relative_invalidation_kind @228-233
- function_item invalidation_kind @236-238
- function_item right_combinator_is_next_sibling @244-253
- function_item dependency_is_relative_with_single_next_sibling @259-266
- struct_item StateDependency @272-277
- function_item selector @280-282
- struct_item DocumentStateDependency @287-298
- struct_item InvalidationMap @318-333
- struct_item TSStateForInvalidation @341-341
- function_item may_be_optimized @362-364
- struct_item TSStateDependency @369-374
- function_item selector @377-379
- struct_item AdditionalRelativeSelectorInvalidationMap @391-402
- function_item default @405-407
- function_item new @412-420
- function_item clear @423-427
- function_item shrink_if_needed @430-433
- function_item default @437-439
- function_item new @444-453
- function_item len @456-475
- function_item clear @478-485
- function_item shrink_if_needed @488-494
- function_item note_selector_for_invalidation @498-549
- struct_item PerCompoundState @551-557
- function_item new @560-565
- struct_item NextDependencyEntry @568-572
- struct_item RelativeSelectorInnerCollectorState @574-577
- struct_item ScopeSelectorCollectorState @578-585
- trait_item Collector @587-619
- function_signature_item dependency @588-588
- function_signature_item id_map @589-589
- function_signature_item class_map @590-590
- function_signature_item state_map @591-591
- function_signature_item attribute_map @592-592
- function_signature_item custom_state_map @593-593
- function_signature_item inner_scope_dependencies @594-594
- function_signature_item this_scope_dependencies @595-595
- function_signature_item update_states @596-596
- function_item type_map @604-606
- function_item ts_state_map @611-613
- function_item any_vec @616-618
- function_item on_attribute @621-631
- function_item on_id_or_class @633-649
- function_item on_scope @651-660
- function_item add_attr_dependency @662-666
- function_item add_custom_state_dependency @668-679
- function_item add_local_name @681-691
- function_item on_pseudo_class @693-713
- function_item add_pseudo_class_dependency @715-731
- function_item visit_all_in_iter_compound @739-751
- struct_item SelectorDependencyCollector @756-792
- function_item next_dependency @794-855
- function_item dependencies_from @807-847
- function_item dependency @858-888
- function_item id_map @890-896
- function_item class_map @898-904
- function_item state_map @906-914
- function_item attribute_map @916-924
- function_item inner_scope_dependencies @926-928
- function_item this_scope_dependencies @930-932
- function_item update_states @934-937
- function_item custom_state_map @939-947
- function_item type_map @949-957
- function_item ts_state_map @959-967
- function_item any_vec @969-977
- function_item visit_whole_selector @981-984
- function_item visit_whole_selector_from @986-1045
- function_item visit_selector_list @1051-1126
- function_item visit_relative_selector_list @1128-1167
- function_item visit_simple_selector @1169-1188
- function_item visit_attribute_selector @1190-1204
- struct_item RelativeSelectorCompoundStateAttributes @1208-1211
- function_item new @1214-1219
- struct_item RelativeSelectorDependencyCollector @1223-1260
- function_item add_non_unique_info @1262-1284
- function_item add_ts_pseudo_class_dependency @1286-1302
- function_item visit_whole_selector @1305-1372
- function_item dependency @1376-1425
- function_item id_map @1427-1429
- function_item class_map @1431-1433
- function_item state_map @1435-1439
- function_item attribute_map @1441-1445
- function_item custom_state_map @1447-1451
- function_item inner_scope_dependencies @1453-1455
- function_item this_scope_dependencies @1457-1459
- function_item update_states @1461-1464
- function_item type_map @1466-1470
- function_item ts_state_map @1472-1476
- function_item any_vec @1478-1482
- enum_item ComponentVisitResult @1485-1491
- function_item on_simple_selector @1494-1534
- function_item visit_selector_list @1539-1591
- function_item visit_relative_selector_list @1593-1599
- function_item visit_simple_selector @1601-1615
- function_item visit_attribute_selector @1617-1629

### servo/components/style/invalidation/element/invalidator.rs

Blob: `3189b4e597ecd5c7b621550e8cb20241f5847a82`. Grammar: rust. Status: syntax-clean.

- struct_item SiblingInfo @22-29
- struct_item SiblingTraversalMap @40-45
- function_item default @51-53
- function_item new @61-69
- function_item next_sibling_for @72-79
- function_item prev_sibling_for @82-89
- trait_item InvalidationProcessor @93-192
- function_item invalidates_on_pseudo_element @100-102
- function_item light_tree_only @107-109
- function_signature_item check_outer_dependency @133-138
- function_signature_item matching_context @141-141
- function_signature_item sibling_traversal_map @144-144
- function_signature_item collect_invalidations @149-155
- function_signature_item should_process_descendants @159-159
- function_signature_item recursion_limit_exceeded @163-163
- function_signature_item invalidated_self @166-166
- function_signature_item invalidated_sibling @170-170
- function_item invalidated_highlight_pseudo @176-176
- function_signature_item invalidated_descendants @179-179
- function_item found_relative_selector_invalidation @184-191
- struct_item DescendantInvalidationLists @196-206
- function_item is_empty @209-213
- struct_item TreeStyleInvalidator @218-228
- enum_item DescendantInvalidationKind @235-242
- enum_item InvalidationKind @249-252
- enum_item InvalidationAddOverride @255-260
- struct_item Invalidation @265-299
- function_item new @303-325
- function_item new_subject_invalidation @332-353
- function_item new_always_effective_for_next_descendant @359-377
- function_item combinator_to_right @382-387
- function_item effective_for_next @391-411
- function_item kind @413-432
- struct_item NegationScopeVisitor @437-442
- function_item new @446-451
- function_item traverse_selector @453-459
- function_item traverse_dependency @466-484
- function_item visit_attribute_selector @490-499
- function_item visit_simple_selector @501-506
- function_item visit_relative_selector_list @508-513
- function_item visit_selector_list @515-529
- function_item visit_complex_selector @531-533
- function_item any_next_has_scope_in_negation @538-548
- function_item fmt @551-566
- struct_item ProcessInvalidationResult @570-576
- struct_item InvalidationResult @579-586
- function_item empty @590-596
- function_item has_invalidated_self @599-601
- function_item has_invalidated_descendants @604-606
- function_item has_invalidated_siblings @609-611
- function_item new @621-632
- function_item invalidate @635-683
- function_item invalidate_siblings @690-733
- function_item invalidate_pseudo_element_or_nac @735-755
- function_item invalidate_child @759-804
- function_item invalidate_nac @806-815
- function_item invalidate_dom_descendants_of @819-842
- function_item invalidate_parts_in_shadow_tree @844-883
- function_item invalidate_parts @885-896
- function_item invalidate_slotted_elements @898-905
- function_item invalidate_slotted_elements_in_slot @907-941
- function_item invalidate_non_slotted_descendants @943-972
- function_item invalidate_descendants @976-1007
- function_item process_sibling_invalidations @1023-1051
- function_item process_descendant_invalidations @1058-1089
- function_item handle_fully_matched @1092-1214
- function_item process_invalidation @1222-1420
- function_item note_scope_dependency_force_at_subject @1433-1470

### servo/components/style/invalidation/element/mod.rs

Blob: `0ddb9f1863def8641911770b9d61cae13bb5adc8`. Grammar: rust. Status: syntax-clean.

- mod_item document_state @7-7
- mod_item element_wrapper @8-8
- mod_item invalidation_map @9-9
- mod_item invalidator @10-10
- mod_item relative_selector @11-11
- mod_item restyle_hints @12-12
- mod_item state_and_attributes @13-13

### servo/components/style/invalidation/element/relative_selector.rs

Blob: `a805aa1d307f375b4d083db10ffd8538c12f2dfb`. Grammar: rust. Status: syntax-clean.

- enum_item DomMutationOperation @40-51
- function_item accept @54-70
- function_item is_side_effect @72-77
- struct_item OptimizationContext @81-85
- function_item can_be_ignored @88-237
- struct_item RelativeSelectorInvalidator @241-256
- struct_item RelativeSelectorInvalidation @258-262
- struct_item AlreadyInvalidatedEntry @268-282
- function_item new @288-295
- function_item update @298-314
- struct_item RelativeSelectorDependencyCollector @318-332
- struct_item ToInvalidate @337-342
- function_item default @345-350
- function_item invalidation_can_collapse @353-427
- function_item new @433-440
- function_item insert_invalidation @442-467
- function_item add_dependency @471-510
- function_item get @513-570
- function_item collect_all_dependencies_for_element @572-714
- function_item is_empty @716-718
- function_item invalidate_relative_selectors_for_this @727-758
- function_item invalidate_relative_selectors_for_dom_mutation @762-828
- function_item invalidate_from_dependencies @831-849
- function_item invalidate_upwards @851-950
- function_item in_search_direction @953-957
- function_item handle_anchor @960-1001
- function_item is_subject @1004-1029
- struct_item RelativeSelectorOuterInvalidationProcessor @1035-1048
- function_item invalidates_on_pseudo_element @1055-1057
- function_item check_outer_dependency @1059-1067
- function_item matching_context @1069-1071
- function_item sibling_traversal_map @1073-1075
- function_item collect_invalidations @1077-1174
- function_item should_process_descendants @1176-1185
- function_item recursion_limit_exceeded @1187-1189
- function_item invalidated_descendants @1191-1193
- function_item invalidated_self @1195-1198
- function_item invalidated_sibling @1200-1203
- struct_item RelativeSelectorInnerInvalidationProcessor @1207-1221
- function_item new @1227-1250
- function_item note_dependency @1252-1301
- function_item take_invalidations @1304-1306
- function_item check_outer_dependency @1314-1332
- function_item matching_context @1334-1336
- function_item collect_invalidations @1338-1355
- function_item should_process_descendants @1357-1359
- function_item recursion_limit_exceeded @1361-1363
- function_item invalidated_self @1366-1366
- function_item invalidated_sibling @1367-1367
- function_item invalidated_descendants @1368-1368
- function_item found_relative_selector_invalidation @1370-1388
- function_item sibling_traversal_map @1390-1392

### servo/components/style/invalidation/element/restyle_hints.rs

Blob: `82e6befc0c10f5c259dc64e4af9471ec584d91a5`. Grammar: rust. Status: syntax-clean.

- function_item restyle_subtree @79-81
- function_item recascade_subtree @86-88
- function_item contains_subtree @93-95
- function_item will_recascade_subtree @99-101
- function_item has_non_animation_invalidations @104-106
- function_item propagate @109-125
- function_item propagate_for_non_animation_restyle @128-156
- function_item replacements @159-161
- function_item for_animations @165-169
- function_item has_animation_hint @174-176
- function_item has_animation_hint_or_recascade @181-187
- function_item has_non_animation_hint @192-194
- function_item has_replacements @199-201
- function_item remove_animation_hints @205-216
- function_item default @220-222

### servo/components/style/invalidation/element/state_and_attributes.rs

Blob: `be39c8448b46b9466e59b0c48a8f65992ca12a17`. Grammar: rust. Status: syntax-clean.

- struct_item Collector @35-54
- struct_item StateAndAttrInvalidationProcessor @58-65
- function_item new @69-93
- function_item check_dependency @98-138
- function_item should_process_descendants @142-144
- function_item propagate_dirty_bit_up_to @147-170
- function_item invalidated_descendants @173-181
- function_item invalidated_self @185-195
- function_item invalidated_sibling @198-220
- function_item invalidates_on_pseudo_element @230-232
- function_item check_outer_dependency @234-251
- function_item matching_context @253-255
- function_item sibling_traversal_map @257-259
- function_item collect_invalidations @261-423
- function_item should_process_descendants @425-434
- function_item recursion_limit_exceeded @436-445
- function_item invalidated_descendants @447-449
- function_item invalidated_self @451-454
- function_item invalidated_sibling @456-459
- function_item invalidated_highlight_pseudo @461-463
- function_item collect_dependencies_in_invalidation_map @471-520
- function_item collect_state_dependencies @522-540
- function_item check_dependency @544-552
- function_item scan_dependency @554-574
- function_item note_dependency @576-668
- function_item dependency_may_be_relevant @672-689
- function_item push_invalidation @692-738
- function_item dependency_may_be_relevant @740-758

### servo/components/style/invalidation/media_queries.rs

Blob: `5ab96a9bb2760174a0f533a610062ce52cceba3c`. Grammar: rust. Status: syntax-clean.

- struct_item MediaListKey @28-28
- function_item from_raw @32-34
- trait_item ToMediaListKey @39-45
- function_item to_media_list_key @42-44
- struct_item EffectiveMediaQueryResults @54-57
- function_item default @60-62
- function_item new @67-71
- function_item clear @74-76
- function_item was_effective @80-85
- function_item saw_effective @88-95
- struct_item PotentiallyEffectiveMediaRules @100-100
- function_item process_import @103-111
- function_item process_media @113-121
- function_item process_document @124-132
- function_item process_supports @135-143

### servo/components/style/invalidation/mod.rs

Blob: `12b0d06853bba2130971e777910f37932e332689`. Grammar: rust. Status: syntax-clean.

- mod_item element @7-7
- mod_item media_queries @8-8
- mod_item stylesheets @9-9
- mod_item viewport_units @10-10

### servo/components/style/invalidation/stylesheets.rs

Blob: `311f0326961d40b95cf3145745e391e951087cd5`. Grammar: rust. Status: syntax-clean.

- enum_item RuleChangeKind @35-47
- enum_item Invalidation @54-64
- function_item is_id @67-69
- function_item is_id_or_class @71-73
- enum_item InvalidationKind @79-83
- function_item bitor_assign @87-89
- function_item is_scope @94-96
- function_item add @99-103
- struct_item StylesheetInvalidationSet @111-117
- function_item new @121-123
- function_item invalidate_fully @126-130
- function_item collect_invalidations_for @134-185
- function_item is_empty @188-192
- function_item invalidation_kind_for @194-248
- function_item process_style @252-282
- function_item process_invalidations_in_subtree @290-360
- function_item scan_component @363-388
- function_item collect_invalidations @404-457
- function_item insert_invalidation @459-501
- function_item insert_atom @465-478
- function_item insert_local_name @480-490
- function_item rule_changed @504-594
- function_item collect_invalidations_for_rule @597-696
- function_item invalidate_position_try @700-746

### servo/components/style/invalidation/viewport_units.rs

Blob: `06faeb14c468e9e053757c31f633a958770491ab`. Grammar: rust. Status: syntax-clean.

- function_item invalidate @14-20
- function_item invalidate_recursively @22-71

### servo/components/style/lib.rs

Blob: `2b9ff6522347fa06d6a3e06f7b07093e482ada7b`. Grammar: rust. Status: syntax-clean.

- mod_item gecko_string_cache @41-41
- mod_item macros @54-54
- mod_item derives @56-65
- mod_item applicable_declarations @67-67
- mod_item author_styles @68-68
- mod_item bezier @69-69
- mod_item bloom @70-70
- mod_item color @71-71
- mod_item computed_value_flags @73-73
- mod_item context @74-74
- mod_item counter_style @75-75
- mod_item custom_properties @76-76
- mod_item custom_properties_map @77-77
- mod_item data @78-78
- mod_item device @79-79
- mod_item dom @80-80
- mod_item dom_apis @81-81
- mod_item driver @82-82
- mod_item error_reporting @83-83
- mod_item font_face @84-84
- mod_item font_metrics @85-85
- mod_item gecko_bindings @88-88
- mod_item global_style_data @89-89
- mod_item invalidation @90-90
- mod_item logical_geometry @92-92
- mod_item matching @93-93
- mod_item media_queries @94-94
- mod_item parallel @95-95
- mod_item parser @96-96
- mod_item piecewise_linear @97-97
- mod_item prefs @98-98
- mod_item properties_and_values @99-99
- mod_item queries @101-101
- mod_item rule_cache @102-102
- mod_item rule_collector @103-103
- mod_item rule_tree @104-104
- mod_item scoped_tls @105-105
- mod_item selector_map @106-106
- mod_item selector_parser @107-107
- mod_item shared_lock @108-108
- mod_item sharing @109-109
- mod_item simple_buckets_map @110-110
- mod_item str @111-111
- mod_item style_adjuster @112-112
- mod_item style_resolver @113-113
- mod_item stylesheet_set @114-114
- mod_item stylesheets @115-115
- mod_item stylist @116-116
- mod_item thread_state @117-117
- mod_item traversal @118-118
- mod_item traversal_flags @119-119
- mod_item typed_om @120-120
- mod_item url @121-121
- mod_item use_counters @122-122
- mod_item values @126-126
- mod_item docs @130-136
- mod_item supported_properties @133-135
- mod_item properties @172-172
- mod_item gecko @176-176
- mod_item servo @181-181
- trait_item CaseSensitivityExt @206-209
- function_signature_item eq_atom @208-208
- function_item eq_atom @213-218
- trait_item Zero @223-229
- function_signature_item zero @225-225
- function_signature_item is_zero @228-228
- function_item zero @235-237
- function_item is_zero @239-241
- trait_item ZeroNoPercent @245-248
- function_signature_item is_zero_no_percent @247-247
- trait_item One @252-258
- function_signature_item one @254-254
- function_signature_item is_one @257-257
- function_item one @264-266
- function_item is_one @268-270
- struct_item AllocErr @281-281
- function_item from @285-287
- function_item from @292-294
- function_item from @299-301
- trait_item ShrinkIfNeeded @311-313
- function_signature_item shrink_if_needed @312-312
- function_item should_shrink @319-322
- function_item shrink_if_needed @329-333
- function_item shrink_if_needed @341-345

### servo/components/style/logical_geometry.rs

Blob: `586b3d8b82df096b712da0ea6c00436e1e66e04b`. Grammar: rust. Status: syntax-clean.

- enum_item BlockFlowDirection @15-19
- enum_item InlineBaseDirection @21-24
- enum_item WritingModeProperty @47-57
- struct_item WritingMode @62-62
- function_item new @133-214
- function_item horizontal_tb @217-219
- function_item is_vertical @222-224
- function_item is_vertical_rl @227-229
- function_item is_horizontal @232-234
- function_item is_vertical_lr @238-240
- function_item is_inline_tb @244-247
- function_item is_bidi_ltr @250-252
- function_item is_sideways @255-257
- function_item is_upright @260-262
- function_item line_left_is_inline_start @271-276
- function_item inline_start_physical_side @279-286
- function_item inline_end_physical_side @289-296
- function_item block_start_physical_side @299-305
- function_item block_end_physical_side @308-314
- function_item flipped_start_side @319-333
- function_item start_start_physical_corner @336-341
- function_item start_end_physical_corner @344-349
- function_item end_start_physical_corner @352-357
- function_item end_end_physical_corner @360-365
- function_item block_flow_direction @368-374
- function_item inline_base_direction @377-383
- function_item is_text_vertical @387-389
- function_item fmt @393-415
- struct_item DebugWritingMode @426-426
- struct_item DebugWritingMode @430-432
- function_item check @437-437
- function_item check_debug @440-440
- function_item new @443-445
- function_item check @451-453
- function_item check_debug @456-458
- function_item new @461-463
- function_item fmt @468-470
- function_item fmt @473-475
- struct_item LogicalSize @480-484
- function_item fmt @487-493
- function_item zero @499-505
- function_item new @510-516
- function_item from_physical @519-525
- function_item width @530-537
- function_item set_width @540-547
- function_item height @550-557
- function_item set_height @560-567
- function_item to_physical @570-577
- function_item convert @580-587
- function_item add @594-602
- function_item sub @609-617
- struct_item LogicalPoint @622-628
- function_item fmt @631-637
- function_item zero @643-649
- function_item new @654-660
- function_item from_physical @665-695
- function_item x @698-711
- function_item set_x @714-729
- function_item y @732-743
- function_item set_y @746-757
- function_item to_physical @760-785
- function_item convert @788-804
- function_item add_point @811-819
- function_item add @826-834
- function_item sub @841-849
- struct_item LogicalMargin @857-863
- function_item fmt @866-882
- function_item zero @887-895
- function_item new @900-914
- function_item from_physical @917-949
- function_item new_all_same @954-956
- function_item top @959-970
- function_item set_top @973-984
- function_item right @987-1000
- function_item set_right @1003-1016
- function_item bottom @1019-1030
- function_item set_bottom @1033-1044
- function_item left @1047-1060
- function_item set_left @1063-1076
- function_item to_physical @1079-1112
- function_item convert @1115-1122
- function_item is_zero @1127-1132
- function_item inline_start_end @1137-1139
- function_item block_start_end @1142-1144
- function_item start_end @1147-1152
- function_item top_bottom @1155-1162
- function_item left_right @1165-1172
- function_item add @1179-1189
- function_item sub @1196-1206
- struct_item LogicalRect @1211-1215
- function_item fmt @1218-1230
- function_item zero @1235-1241
- function_item new @1246-1258
- function_item from_point_size @1261-1273
- function_item from_physical @1278-1315
- function_item inline_end @1318-1320
- function_item block_end @1323-1325
- function_item to_physical @1328-1361
- function_item convert @1364-1380
- function_item translate_by_size @1382-1387
- function_item translate @1389-1400
- function_item union @1405-1424
- function_item add @1431-1449
- function_item sub @1456-1474
- enum_item LogicalAxis @1479-1482
- function_item to_physical @1486-1492
- enum_item LogicalSide @1497-1502
- function_item is_block @1505-1507
- function_item to_physical @1510-1567
- enum_item LogicalCorner @1572-1577
- function_item to_physical @1581-1593
- enum_item PhysicalAxis @1598-1601
- enum_item PhysicalSide @1605-1610
- function_item parallel_to @1614-1616
- function_item orthogonal_to @1619-1621
- function_item opposite_side @1624-1631
- enum_item PhysicalCorner @1636-1641
- function_item from_sides @1644-1676

### servo/components/style/macros.rs

Blob: `8851cb44bdbdb35e9bf6771dbdda7cc633ce7b55`. Grammar: rust. Status: syntax-clean.


### servo/components/style/matching.rs

Blob: `87282696a2dc7ccb060f6d1965a0d9afd14ffde5`. Grammar: rust. Status: syntax-clean.

- struct_item StyleDifference @39-44
- enum_item StyleChange @48-58
- enum_item CascadeVisitedMode @62-69
- trait_item PrivateMatchMethods @71-870
- function_item replace_single_rule_node @72-95
- function_item replace_rules_internal @101-189
- function_item requires_animation_update_for_scroll_self @192-218
- function_item after_change_style @221-234
- function_item needs_animations_update @236-320
- function_item might_need_transitions_update @322-345
- function_item maybe_resolve_starting_style @348-382
- function_item process_transitions @391-437
- function_item process_animations @440-540
- function_item process_animations @543-614
- function_item process_animations_for_pseudo @617-697
- function_item process_animations_for_style @700-788
- function_item accumulate_damage_for @791-869
- function_item need_to_unconditionally_recascade_for_reset_change @873-930
- trait_item MatchMethods @935-1224
- function_item layout_parent @946-965
- function_item line_height_likely_changed @972-997
- function_item finish_restyle @1001-1177
- function_item replace_rules @1183-1203
- function_item compute_style_difference @1208-1223

### servo/components/style/media_queries/media_list.rs

Blob: `03dba14097746a79e2533e9c8c01232d8514dacc`. Grammar: rust. Status: syntax-clean.

- struct_item MediaList @26-30
- function_item parse @40-74
- function_item empty @77-81
- function_item evaluate @84-93
- function_item matches @96-120
- function_item is_empty @123-125
- function_item is_viewport_dependent @128-130
- function_item append_medium @136-150
- function_item delete_medium @156-167

### servo/components/style/media_queries/media_query.rs

Blob: `9cc76d0f763f25183e8fb6a2938a8b281680601c`. Grammar: rust. Status: syntax-clean.

- enum_item Qualifier @21-28
- struct_item MediaType @32-32
- function_item screen @36-38
- function_item print @41-43
- function_item parse @45-56
- struct_item MediaQuery @63-71
- function_item to_css @74-107
- function_item never_matching @113-119
- function_item is_viewport_dependent @122-127
- function_item parse @132-160
- enum_item MediaQueryType @165-170
- function_item parse @173-181
- function_item matches @184-189

### servo/components/style/media_queries/mod.rs

Blob: `823ceca175e775e57a7a06fe5d7ffdd5cf5301b4`. Grammar: rust. Status: syntax-clean.

- mod_item media_list @9-9
- mod_item media_query @10-10

### servo/components/style/parallel.rs

Blob: `fc955efe04da0b17e5876c46fe1ff4660a8ee02c`. Grammar: rust. Status: syntax-clean.

- function_item create_thread_local_context @75-80
- function_item distribute_one_chunk @83-114
- function_item distribute_work @117-145
- function_item style_trees @149-205

### servo/components/style/parser.rs

Blob: `e9045fd20ac2b2b92a6736cdb678c0cae7faad8a`. Grammar: rust. Status: syntax-clean.

- struct_item NestingContext @21-26
- function_item parse_relative_for @29-35
- function_item new @38-44
- function_item new_from_rule @47-54
- function_item save @57-65
- function_item restore @68-70
- struct_item PropertyDeclarationContext @75-82
- function_item set @85-92
- function_item clear @94-97
- function_item property_id @100-102
- function_item current_random_index @105-107
- function_item increment_random_count @112-116
- struct_item ParserContext @120-142
- function_item new @147-170
- function_item with_property_declaration @174-183
- function_item nest_for_rule @186-195
- function_item with_parsing_mode @198-204
- function_item in_page_rule @208-210
- function_item allows_important_declarations @214-219
- function_item has_element_context @223-244
- function_item rule_types @247-249
- function_item error_reporting_enabled @253-255
- function_item log_css_error @258-265
- function_item in_ua_sheet @269-271
- function_item chrome_rules_enabled @275-277
- function_item allows_computational_dependence @281-283
- function_item disallow_urls_in_range @286-289
- trait_item Parse @308-313
- function_signature_item parse @312-312
- function_item parse @320-322
- function_item parse @329-331
- function_item parse @335-337
- function_item parse @341-343

### servo/components/style/piecewise_linear.rs

Blob: `ddb770ca45b97be7083ebd296802cbf811c3017f`. Grammar: rust. Status: syntax-clean.

- struct_item PiecewiseLinearFunctionEntry @33-36
- function_item to_css @39-46
- struct_item PiecewiseLinearFunction @65-70
- function_item interpolate @77-97
- function_item at @101-139
- function_item iter @142-144
- struct_item BuildEntry @149-152
- struct_item PiecewiseLinearFunctionBuilder @156-160
- function_item with_capacity @164-170
- function_item create_entry @172-192
- function_item push @199-201
- function_item build @205-281

### servo/components/style/prefs.rs

Blob: `679b85cde5f9202da1446294a414295912e5b478`. Grammar: rust. Status: syntax-clean.


### servo/components/style/properties/cascade.rs

Blob: `1fe244b1d214d7ecd22cd31daff0d4e2f421d28a`. Grammar: rust. Status: syntax-clean.

- enum_item FirstLineReparenting @55-63
- function_item cascade @79-116
- struct_item DeclarationIterator @118-127
- function_item new @131-150
- function_item update_for_node @152-159
- function_item next @166-193
- function_item cascade_rules @196-234
- enum_item CascadeMode @238-249
- function_item iter_declarations @251-277
- function_item apply_declarations @281-464
- function_item is_base_appearance @473-486
- function_item tweak_when_ignoring_colors @488-614
- function_item alpha_channel @516-522
- struct_item PrioritaryDeclarationPosition @624-628
- function_item default @631-636
- struct_item Declaration @640-644
- struct_item Declarations @648-655
- function_item note_prioritary_property @658-678
- function_item note_declaration @680-694
- struct_item RevertedSet @698-703
- struct_item SeenSubstitutionFunctions @706-711
- struct_item SeenSet @714-717
- function_item find_non_custom_references @720-742
- struct_item KeyframeCustomPropertiesBuilder @752-756
- function_item new @761-773
- function_item cascade @776-784
- function_item build @787-798
- struct_item Cascade @801-813
- function_item new @816-833
- function_item new_for_custom_properties_only @837-850
- function_item substitute_variables_if_needed @852-894
- function_item apply_one_prioritary_property @896-940
- function_item did_apply_prioritary_property @943-1013
- function_item apply_non_prioritary_properties @1015-1065
- function_item recompute_zoom_dependent_inherited_lengths @1068-1079
- function_item apply_one_longhand @1081-1165
- function_item do_apply_declaration @1168-1183
- function_item compute_visited_style_if_needed @1189-1241
- function_item finished_applying_properties @1243-1296
- function_item try_to_use_cached_reset_properties @1298-1344
- function_item recompute_initial_font_family_if_needed @1350-1383
- function_item prioritize_user_fonts_if_needed @1388-1423
- function_item recompute_keyword_font_size_if_needed @1426-1455
- function_item constrain_font_size_if_needed @1460-1478
- function_item unzoom_fonts_if_needed @1484-1503
- function_item recompute_font_size_for_zoom_change @1505-1515
- function_item recompute_math_font_size_if_needed @1522-1652
- function_item scale_factor_for_math_depth_change @1548-1585
- function_item init_custom_properties @1656-1671
- function_item apply_custom_and_prioritary_properties @1678-1713
- function_item ensure_prioritary_property @1716-1735
- function_item cascade_custom_property @1738-1872
- function_item might_have_non_custom_or_attr_dependency @1876-1889
- function_item maybe_note_non_custom_dependency @1893-1945
- function_item value_may_affect_style @1947-2045
- function_item update_attributes_map @2048-2078
- function_item finish_cascade_custom_properties @2082-2122
- function_item substitute_all @2125-2720
- enum_item VarType @2142-2146
- struct_item VarInfo @2150-2159
- struct_item OrderIndexMap @2162-2167
- function_item clear @2170-2173
- struct_item Context @2178-2205
- function_item reset @2208-2214
- function_item map @2216-2218
- function_item map_mut @2220-2222
- function_item handle_loop @2225-2248
- function_item apply_prioritary_property @2255-2267
- function_item visit_value_references @2280-2375
- function_item visit_link @2379-2407
- function_item traverse @2427-2679

### servo/components/style/properties/computed_value_flags.rs

Blob: `2dcded88754efe84c9c26d1c98708a55b6be1474`. Grammar: rust. Status: syntax-clean.

- struct_item ComputedValueFlags @17-17
- function_item default @151-153
- function_item inherited_flags @159-167
- function_item maybe_inherited_flags @171-175
- function_item cascade_input_flags @179-184
- function_item tree_counting_function_flags @188-190
- function_item inherited @196-198
- function_item maybe_inherited @203-205
- function_item for_cascade_inputs @209-211

### servo/components/style/properties/declaration_block.rs

Blob: `c8fed1fa7be9a6cbb730af9d5dbc69b74ddf9d6f`. Grammar: rust. Status: syntax-clean.

- struct_item AnimationDeclarations @57-62
- function_item is_empty @66-68
- enum_item DeclarationUpdate @74-84
- struct_item SourcePropertyDeclarationUpdate @89-93
- enum_item Importance @99-106
- function_item important @110-115
- struct_item PropertyDeclarationIdSet @120-123
- function_item insert @127-138
- function_item contains @141-146
- function_item remove @149-156
- function_item clear @159-162
- function_item is_empty @166-168
- function_item contains_any_reset @171-173
- function_item contains_all_longhands @177-179
- function_item contains_all @183-194
- function_item iter @197-202
- struct_item PropertyDeclarationIdSetIterator @206-209
- function_item next @214-222
- struct_item PropertyDeclarationBlock @227-243
- function_item to_shmem @246-259
- function_item clone @263-270
- function_item eq @274-280
- struct_item DeclarationImportanceIterator @284-286
- function_item default @289-293
- function_item new @298-302
- function_item next @309-320
- function_item size_hint @323-325
- function_item next_back @330-341
- struct_item AnimationValueIterator @345-350
- function_item new @353-365
- function_item next @371-392
- function_item fmt @396-398
- function_item len @404-406
- function_item is_empty @410-412
- function_item new @416-423
- function_item with_one @426-437
- function_item declarations @441-443
- function_item declarations_importance @447-449
- function_item declaration_importance_iter @453-455
- function_item normal_declaration_iter @459-463
- function_item to_animation_value_iter @467-474
- function_item any_important @481-483
- function_item any_normal @490-492
- function_item property_ids @497-499
- function_item contains @503-505
- function_item contains_any_reset @509-511
- function_item get @518-527
- function_item shorthand_to_css @531-571
- function_item property_value_to_css @576-596
- function_item property_priority @599-621
- function_item property_value_to_typed_value_list @626-646
- function_item extend @652-678
- function_item push @685-718
- function_item prepare_for_update @723-821
- function_item update @824-915
- struct_item UpdateOrRemoval @855-859
- function_item first_declaration_to_remove @920-930
- function_item remove_declaration_at @934-938
- function_item clear @942-946
- function_item remove_property @953-982
- function_item single_value_to_css @985-1048
- function_item from_animation_value_map @1051-1067
- function_item has_css_wide_keyword @1071-1080
- function_item to_css @1087-1338
- enum_item AppendableValue @1343-1354
- function_item handle_first_serialization @1357-1367
- function_item append_declaration_value @1370-1381
- function_item append_serialization @1384-1406
- function_item parse_style_attribute @1413-1433
- function_item parse_one_declaration_into @1440-1489
- struct_item PropertyDeclarationParser @1492-1495
- struct_item DeclarationParserState @1501-1515
- function_item first_declaration_start @1519-1521
- function_item has_parsed_declarations @1524-1526
- function_item take_declarations @1529-1531
- function_item parse_value @1534-1579
- function_item report_errors_if_needed @1583-1592
- function_item do_report_css_errors @1595-1611
- function_item did_error @1615-1628
- function_item is_non_mozilla_vendor_identifier @1646-1648
- function_item parse_value @1654-1662
- function_item parse_declarations @1668-1670
- function_item parse_qualified @1672-1674
- function_item alias_of_known_property @1680-1685
- function_item report_one_css_error @1688-1758
- function_item all_properties_in_block @1699-1706
- function_item parse_property_declaration_list @1762-1788

### servo/components/style/properties/gecko.mako.rs

Blob: `e413bb42a58f5503cab2785619bcbb2f86625367`. Grammar: rust. Status: contains-errors.

- struct_item ComputedValues @49-49
- function_item as_gecko_computed_style @53-55
- function_item new @58-84
- function_item default_values @86-100
- function_item to_arc @103-109
- function_item is_pseudo_style @112-114
- function_item pseudo @117-122
- function_item is_first_line_style @125-127
- function_item is_display_property_changed_from_none @130-142
- function_item each_cached_lazy_pseudo @145-161
- function_item drop @166-172
- function_item drop @179-186
- function_item new @191-220
- function_item clone_with_flags @224-242
- function_item into_outer @244-256
- function_item deref @262-264
- function_item deref_mut @269-271
- function_item ineffective_content_property @278-280
- function_item visited_style_ptr @283-285
- function_item visited_style @288-294
- function_item from_computed_value @1281-1283
- function_item resolve_system_font @1291-1299
- struct_item ComputedSystemFont @1302-1304

### servo/components/style/properties/helpers.mako.rs

Blob: `aa2a7d38406d1ba307261bdf63dc707f5eea0232`. Grammar: rust. Status: contains-errors.

- mod_item computed_value @166-168
- function_item get_initial_value @171-171
- function_item get_initial_specified_value @173-190
- function_item parse @183-188
- function_item to_resolved_value @302-310
- function_item from_resolved_value @312-319
- function_item from @326-328
- function_item from @332-334
- function_item to_animated_value @350-354
- function_item from_animated_value @356-360
- function_item to_animated_zero @365-365
- function_item animate @369-377
- function_item compute_squared_distance @380-384
- function_item compute_iter @448-453
- function_item to_computed_value @461-468
- function_item from_computed_value @471-474

### servo/components/style/properties/helpers/animated_properties.mako.rs

Blob: `58cc9111a9147a518d2b8a72975bfeff4c773c63`. Grammar: rust. Status: contains-errors.

- function_item animate @733-754

### servo/components/style/properties/mod.rs

Blob: `c6a88ac2c16613fcbfe35e01257c47a928d50823`. Grammar: rust. Status: syntax-clean.

- mod_item cascade @7-7
- mod_item declaration_block @8-8
- mod_item shorthands @9-9
- mod_item generated @20-22
- enum_item CSSWideKeyword @96-109
- function_item to_str @113-122
- function_item from_ident @125-135
- function_item parse @138-145
- function_item revert_kind @148-155
- struct_item WideKeywordDeclaration @160-165
- function_item to_typed @170-172
- struct_item VariableDeclaration @177-184
- enum_item CustomDeclarationValue @189-196
- struct_item CustomDeclaration @200-207
- function_item fmt @210-220
- struct_item NonCustomPropertyId @228-228
- function_item to_css @232-237
- function_item bit @242-244
- function_item to_noncustomcsspropertyid @249-252
- function_item from_noncustomcsspropertyid @257-264
- function_item unaliased @267-272
- function_item to_property_id @276-278
- function_item as_longhand @282-287
- function_item as_shorthand @291-298
- function_item as_alias @302-310
- function_item longhand_or_shorthand @314-320
- function_item from_longhand @324-326
- function_item from_shorthand @330-332
- function_item from_alias @336-338
- function_item iter @341-343
- function_item from @348-350
- function_item from @355-357
- function_item from @362-364
- enum_item PropertyId @370-375
- function_item to_css @378-389
- function_item longhand_id @395-397
- function_item is_animatable @400-405
- function_item parse_unchecked_for_testing @411-413
- function_item parse_enabled_for_all_content @418-426
- function_item parse @431-437
- function_item parse_ignoring_rule_type @444-450
- function_item from_noncustomcsspropertyid @455-457
- function_item from_gecko_css_property_id @462-473
- function_item is_shorthand @477-479
- function_item as_shorthand @483-491
- function_item non_custom_id @494-499
- function_item non_custom_non_alias_id @503-505
- function_item enabled_for_all_content @510-518
- function_item to_noncustomcsspropertyid_resolving_aliases @525-530
- function_item allowed_in @532-544
- function_item allowed_in_ignoring_rule_type @547-554
- function_item supports_type @558-561
- function_item collect_property_completion_keywords @567-572
- enum_item PropertyIdRef @579-584
- function_item from @587-592
- function_item from @596-598
- function_item from @602-604
- function_item to_css @609-614
- function_item fmt @618-620
- function_item name @626-628
- function_item inherited @632-634
- function_item zoom_dependent @638-640
- function_item ignored_when_document_colors_disabled @645-647
- function_item is_or_is_longhand_of @650-655
- function_item is_longhand_of @658-660
- function_item is_animatable @664-666
- function_item is_discrete_animatable @670-673
- function_item to_noncustomcsspropertyid @678-680
- function_item from_noncustomcsspropertyid @684-688
- function_item is_logical @692-694
- function_item to_css @699-704
- function_item name @710-712
- function_item to_noncustomcsspropertyid @717-719
- function_item from_noncustomcsspropertyid @724-728
- function_item get_shorthand_appendable_value @733-773
- function_item is_legacy_shorthand @777-779
- function_item allows_disabled_subproperties @783-786
- function_item parse_non_custom_property_declaration_value_into @792-867
- function_item with_variables_from_shorthand @870-881
- function_item css_wide_keyword @885-887
- function_item get_css_wide_keyword @891-896
- function_item may_serialize_as_part_of_shorthand @910-920
- function_item is_animatable @923-925
- function_item is_custom @929-931
- function_item parse_into @943-1051
- enum_item OwnedPropertyDeclarationId @1056-1061
- function_item is_logical @1066-1068
- function_item as_borrowed @1072-1077
- function_item from_gecko_css_property_id @1082-1087
- enum_item PropertyDeclarationId @1093-1098
- function_item to_css @1101-1112
- function_item flags @1118-1123
- function_item to_owned @1126-1133
- function_item is_or_is_longhand_of @1137-1147
- function_item is_longhand_of @1151-1156
- function_item name @1159-1168
- function_item as_longhand @1172-1177
- function_item is_logical @1181-1186
- function_item to_physical @1193-1198
- function_item is_animatable @1202-1207
- function_item is_discrete_animatable @1211-1217
- function_item to_noncustomcsspropertyid @1223-1228
- function_item to_gecko_css_property_id @1236-1251
- trait_item IndexedId @1256-1264
- function_signature_item from_index_release_unchecked @1261-1261
- function_signature_item to_index @1263-1263
- function_item from_index_release_unchecked @1270-1273
- function_item to_index @1276-1278
- function_item from_index_release_unchecked @1285-1290
- function_item to_index @1293-1295
- function_item from_index_release_unchecked @1302-1307
- function_item to_index @1310-1312
- struct_item IdSet @1336-1339
- function_item clone @1343-1345
- function_item default @1352-1357
- function_item eq @1362-1364
- function_item fmt @1368-1370
- function_item size_of @1375-1377
- function_item new @1383-1385
- function_item from_storage @1388-1393
- function_item insert @1397-1400
- function_item remove @1404-1407
- function_item contains @1411-1414
- function_item iter @1417-1424
- function_item contains_all @1427-1434
- function_item contains_any @1437-1444
- function_item remove_all @1448-1452
- function_item clear @1456-1458
- function_item is_empty @1462-1464
- function_item contains_any_reset @1471-1473
- struct_item IdSetIterator @1477-1482
- function_item next @1487-1511
- struct_item SourcePropertyDeclaration @1521-1526
- function_item with_one @1538-1542
- function_item drain @1545-1550
- function_item clear @1553-1556
- function_item is_empty @1559-1561
- function_item push @1564-1567
- struct_item SourcePropertyDeclarationDrain @1571-1577
- struct_item UnparsedValue @1581-1586
- function_item to_css @1589-1598
- function_item to_typed @1602-1608
- function_item substitute_variables @1621-1755
- enum_item AllShorthand @1759-1767
- function_item declarations @1772-1777
- struct_item AllShorthandDeclarationIterator @1781-1784
- function_item next @1790-1803
- struct_item NonCustomPropertyIterator @1808-1811
- function_item next @1819-1826
- struct_item TransitionPropertyIterator @1830-1834
- function_item from_style @1838-1844
- struct_item TransitionPropertyIteration @1848-1854
- function_item next @1859-1899

### servo/components/style/properties/properties.mako.rs

Blob: `e0f518b0af568da72e978c04bdc564e2a9f13862`. Grammar: rust. Status: contains-errors.

- struct_item PropertyDeclarationVariantRepr @103-106
- function_item clone @110-178
- struct_item Helper @144-144
- trait_item AssertCopy @145-145
- function_item assert @145-145
- trait_item AssertNotCopy @146-146
- function_item assert @146-146
- function_item do_nothing @491-491

### servo/components/style/properties/shorthands.rs

Blob: `50c7cac832b1656341fc9e2a75c687fca97f73db`. Grammar: rust. Status: syntax-clean.

- function_item serialize_directional_border @60-87
- function_item parse_border @89-121
- mod_item border_block @123-156
- function_item parse_value @127-140
- function_item to_css @143-154
- mod_item border_inline @158-191
- function_item parse_value @162-175
- function_item to_css @178-189
- mod_item border_radius @193-232
- function_item parse_value @201-212
- function_item to_css @215-230
- mod_item corner_shape @234-270
- function_item parse_value @243-254
- function_item to_css @257-268
- mod_item border_image @272-419
- function_item parse_value @281-363
- function_item to_css @366-417
- mod_item border @421-543
- function_item parse_value @431-458
- function_item to_css @461-531
- function_item collect_completion_keywords @539-541
- mod_item container @546-582
- function_item parse_value @552-567
- function_item to_css @570-580
- mod_item vertical_align @584-642
- function_item parse_value @590-619
- function_item to_css @622-640
- mod_item offset @645-741
- function_item parse_value @653-701
- function_item to_css @704-739
- mod_item columns @743-811
- function_item parse_value @749-793
- function_item to_css @796-809
- mod_item column_rule @814-846
- function_item parse_value @821-845
- mod_item text_wrap @849-898
- function_item parse_value @855-876
- function_item to_css @879-896
- mod_item white_space @900-1002
- function_item parse_value @906-950
- function_item parse_special_shorthands @913-924
- function_item to_css @953-988
- function_item collect_completion_keywords @992-1000
- mod_item _webkit_text_stroke @1005-1033
- function_item parse_value @1011-1032
- mod_item list_style @1035-1144
- function_item parse_value @1043-1115
- function_item to_css @1118-1142
- mod_item gap @1146-1180
- function_item parse_value @1152-1165
- function_item to_css @1168-1178
- mod_item marker @1183-1214
- function_item parse_value @1189-1200
- function_item to_css @1203-1212
- mod_item flex_flow @1216-1263
- function_item parse_value @1222-1243
- function_item to_css @1246-1261
- mod_item flex @1265-1328
- function_item parse_flexibility @1272-1281
- function_item parse_value @1283-1327
- mod_item place_content @1330-1374
- function_item parse_value @1336-1359
- function_item to_css @1362-1372
- mod_item place_self @1376-1416
- function_item parse_value @1382-1401
- function_item to_css @1404-1414
- mod_item place_items @1418-1452
- function_item parse_value @1424-1437
- function_item to_css @1440-1450
- mod_item grid_row @1454-1496
- function_item parse_value @1461-1481
- function_item to_css @1484-1494
- mod_item grid_column @1498-1540
- function_item parse_value @1505-1525
- function_item to_css @1528-1538
- mod_item grid_area @1542-1623
- function_item parse_value @1549-1593
- function_item line_with_ident_from @1553-1560
- function_item to_css @1596-1621
- mod_item position_try @1626-1656
- function_item parse_value @1632-1642
- function_item to_css @1645-1654
- mod_item scroll_timeline @1659-1713
- function_item parse_value @1665-1685
- function_item to_css @1688-1711
- mod_item view_timeline @1716-1800
- function_item parse_value @1724-1764
- function_item to_css @1767-1798
- mod_item animation_range @1803-1878
- function_item parse_value @1810-1849
- function_item to_css @1852-1876
- mod_item transition @1880-2068
- function_item parse_value @1890-2010
- struct_item SingleTransition @1894-1900
- function_item parse_one_transition @1902-1973
- function_item to_css @2013-2066
- mod_item outline @2070-2124
- function_item parse_value @2076-2101
- function_item to_css @2104-2122
- mod_item background_position @2126-2182
- function_item parse_value @2134-2157
- function_item to_css @2160-2180
- mod_item background @2184-2433
- function_item parse_value @2200-2332
- function_item to_css @2335-2431
- mod_item font @2435-2748
- function_item parse_value @2452-2552
- function_item count @2518-2520
- enum_item CheckSystemResult @2554-2558
- function_item to_css @2561-2686
- function_item check_system @2690-2727
- function_item collect_completion_keywords @2738-2746
- mod_item font_variant @2750-2900
- function_item parse_value @2762-2833
- function_item to_css @2837-2898
- mod_item font_synthesis @2903-3008
- function_item parse_value @2909-2963
- function_item to_css @2966-2991
- function_item collect_completion_keywords @2997-3006
- mod_item text_box @3011-3077
- function_item parse_value @3017-3052
- function_item to_css @3055-3075
- mod_item text_emphasis @3080-3108
- function_item parse_value @3086-3107
- mod_item text_decoration @3110-3182
- function_item parse_value @3119-3149
- function_item to_css @3153-3180
- mod_item animation @3184-3453
- function_item parse_value @3194-3336
- struct_item SingleAnimation @3198-3207
- function_item parse_one_animation @3209-3291
- function_item to_css @3339-3451
- mod_item mask @3455-3716
- function_item parse_value @3467-3586
- function_item to_css @3589-3714
- mod_item mask_position @3718-3776
- function_item parse_value @3725-3749
- function_item to_css @3752-3774
- mod_item grid_template @3778-4013
- function_item parse_grid_template @3792-3900
- function_item parse_value @3903-3913
- function_item serialize_grid_template @3915-3997
- function_item to_css @4001-4011
- mod_item grid @4015-4175
- function_item parse_value @4025-4097
- function_item parse_auto_flow @4036-4065
- function_item is_grid_template @4100-4104
- function_item to_css @4108-4173

### servo/components/style/properties_and_values/mod.rs

Blob: `5b5e219d595f000f3a73a698a61e18f7e255eb05`. Grammar: rust. Status: syntax-clean.

- mod_item registry @9-9
- mod_item rule @10-10
- mod_item syntax @11-11
- mod_item value @12-12

### servo/components/style/properties_and_values/registry.rs

Blob: `aebdc38b9aede5b28e955ba29e2cc7ba426e7362`. Grammar: rust. Status: syntax-clean.

- struct_item PropertyRegistration @17-28
- struct_item ScriptRegistry @33-35
- function_item get @40-42
- function_item properties @46-48
- function_item register @54-58
- function_item get_all @62-64

### servo/components/style/properties_and_values/rule.rs

Blob: `5d8f34ef2767279ba1308bc7b8e2678a9a7aa39c`. Grammar: rust. Status: syntax-clean.

- function_item parse_property_block @40-139
- enum_item PropertyRegistrationError @143-147
- function_item size_of @151-153
- function_item compute_initial_value @156-184
- function_item validate_initial_value @188-237
- function_item to_css @242-248
- function_item to_shmem @252-256
- struct_item PropertyRuleName @261-261
- function_item to_css @264-267
- enum_item Inherits @272-277
- function_item parse @280-298
- function_item parse @308-315
- function_item unregistered @321-328
- function_item inherits @331-333
- function_item is_universal @336-338

### servo/components/style/properties_and_values/syntax/ascii.rs

Blob: `e1a1b08535b1c47402e2fe7cdc32d2adddbb4e21`. Grammar: rust. Status: syntax-clean.

- function_item trim_ascii_whitespace @6-48
- function_item trim_ascii_whitespace_test @51-60
- function_item test @52-54

### servo/components/style/properties_and_values/syntax/data_type.rs

Blob: `a68a328296f419b6589c0c2a8e6a5cd67bc70c53`. Grammar: rust. Status: syntax-clean.

- struct_item DependentDataTypes @14-14
- enum_item DataType @26-61
- function_item unpremultiply @67-75
- function_item from_str @78-97
- function_item dependent_types @100-118
- function_item to_css @122-145

### servo/components/style/properties_and_values/syntax/mod.rs

Blob: `46290485239655c510ab1c7015aadf48a14de581`. Grammar: rust. Status: syntax-clean.

- mod_item ascii @23-23
- mod_item data_type @24-24
- struct_item Descriptor @28-34
- function_item universal @38-43
- function_item is_universal @47-49
- function_item specified_string @53-55
- function_item from_css_parser @60-102
- function_item try_parse_multiplier @104-115
- function_item try_parse_component_name @117-130
- function_item parse_component_data_type_name @132-138
- function_item from_str @142-182
- function_item dependent_types @185-195
- function_item to_css @199-221
- function_item parse @226-230
- enum_item Multiplier @237-242
- function_item to_css @245-253
- struct_item Component @258-261
- function_item name @266-268
- function_item multiplier @272-274
- function_item unpremultiplied @278-289
- function_item to_css @293-299
- enum_item ComponentName @304-309
- function_item unpremultiply @312-317
- function_item is_pre_multiplied @320-322
- struct_item Parser @325-329
- function_item new @332-338
- function_item peek @340-342
- function_item parse @344-362
- function_item skip_whitespace @364-371
- function_item parse_data_type_name @374-392
- function_item parse_name @394-413
- function_item parse_multiplier @415-423
- function_item parse_component @426-436

### servo/components/style/properties_and_values/value.rs

Blob: `cda68d85be94c5bb9015faa4ff97c850772d6e26`. Grammar: rust. Status: syntax-clean.

- function_item serialization_types @72-93
- enum_item GenericValueComponent @101-151
- struct_item ComponentList @155-160
- function_item animate @163-176
- function_item to_css @180-202
- struct_item Value @209-219
- function_item eq @223-225
- function_item animate @229-236
- function_item new @241-247
- function_item universal @250-259
- function_item serialization_types @267-276
- function_item to_variable_value @279-290
- enum_item ValueInner @297-306
- function_item compute @317-344
- function_item parse @348-386
- function_item to_declared_value @391-410
- function_item as_universal @413-419
- enum_item AllowComputationallyDependent @426-431
- struct_item Parser @435-439
- function_item new @442-452
- function_item parse @454-502
- function_item parse_value @504-527
- function_item parse_component_without_multiplier @529-621
- function_item expect_multiplier_yielded_eof_error @623-631
- function_item expect_multiplier @633-650
- struct_item CustomAnimatedValue @655-661
- function_item animate @664-673
- function_item from_computed @677-685
- function_item from_declaration @687-764
- function_item to_declaration @766-774

### servo/components/style/queries/condition.rs

Blob: `6decdb4d245ae650f38f4849c40cc20d6b83b67e`. Grammar: rust. Status: syntax-clean.

- enum_item Operator @38-41
- enum_item AllowOr @45-48
- enum_item StyleFeatureValue @51-54
- trait_item OperationParser @61-117
- function_item parse_internal @65-102
- function_signature_item parse_in_parens @105-109
- function_signature_item new_not @113-113
- function_signature_item new_operation @116-116
- function_item try_parse_block @119-144
- enum_item StyleQuery @148-159
- function_item to_css @162-194
- function_item maybe_parenthesized @201-212
- function_item enabled @214-216
- function_item parse @218-229
- function_item parse_in_parenthesis_block @231-247
- function_item matches @249-273
- function_item collect_attribute_references @275-285
- function_item parse_in_parens @289-316
- function_item new_not @318-320
- function_item new_operation @322-324
- enum_item StyleFeature @330-335
- function_item parse @338-344
- function_item matches @346-355
- function_item collect_attribute_references @357-362
- struct_item StyleFeaturePlain @367-371
- function_item to_css @374-392
- function_item parse @396-421
- function_item substitute_and_compare @425-468
- function_item matches @470-551
- function_item collect_attribute_references @553-557
- enum_item BoolValue @575-578
- enum_item MozPrefFeatureValue @595-605
- struct_item MozPrefFeature @613-616
- function_item parse @619-635
- function_item matches @638-644
- function_item matches @647-649
- function_item to_css @653-663
- enum_item QueryCondition @668-685
- function_item to_css @688-733
- function_item consume_any_value @737-739
- function_item parse @743-749
- function_item visit @751-770
- function_item cumulative_flags @774-783
- function_item parse_disallow_or @788-794
- function_item parse_in_parenthesis_block @796-818
- function_item matches @825-853
- function_item matches_general @857-933
- function_item collect_attribute_references @936-940
- function_item parse_in_parens @947-995
- function_item new_not @997-999
- function_item new_operation @1001-1003

### servo/components/style/queries/feature.rs

Blob: `089d56111dbcd73918e9f6db873a17245d4fd41f`. Grammar: rust. Status: syntax-clean.

- enum_item Evaluator @37-61
- struct_item FeatureFlags @108-108
- function_item parsing_requirements @132-134
- function_item all_container_axes @137-142
- function_item container_axes @145-147
- enum_item AllowsRanges @153-156
- struct_item QueryFeatureDescription @159-169
- function_item allows_ranges @174-176
- function_item fmt @192-198

### servo/components/style/queries/feature_expression.rs

Blob: `eaf73e798f92e20aef5173d7cf90bbc6c6c76bf3`. Grammar: rust. Status: syntax-clean.

- enum_item FeatureType @38-43
- function_item features @46-58
- function_item find_feature @60-65
- enum_item LegacyRange @70-75
- enum_item Operator @79-90
- function_item to_css @93-104
- function_item is_compatible_with @108-120
- function_item evaluate @122-130
- function_item parse @132-167
- enum_item QueryFeatureExpressionKind @171-187
- function_item evaluate @192-250
- function_item non_ranged_value @253-262
- struct_item QueryFeatureExpression @268-272
- function_item to_css @275-309
- function_item consume_operation_or_colon @312-317
- function_item disabled_by_pref @320-338
- function_item new @341-352
- function_item write_name @354-374
- function_item feature @376-378
- function_item feature_flags @381-383
- function_item parse_feature_name @385-433
- function_item parse_multi_range_syntax @439-495
- function_item parse_in_parenthesis_block @498-567
- function_item matches @570-650
- enum_item QueryExpressionValue @662-694
- function_item to_css @697-727
- function_item parse @729-766
- function_item parse_for_style_range @773-820
- function_item collect_attribute_references @822-826
- enum_item QueryStyleRange @831-851
- function_item to_css @854-888
- function_item parse @899-922
- function_item evaluate @925-991
- function_item resolve_value @994-1083
- function_item resolve_universal @1091-1114
- function_item compare_values @1116-1144
- function_item collect_attribute_references @1148-1170

### servo/components/style/queries/mod.rs

Blob: `5b608ba485262c82cc5e6fa81675dfeba4b9b955`. Grammar: rust. Status: syntax-clean.

- mod_item condition @10-10
- mod_item feature @13-13
- mod_item feature_expression @14-14
- mod_item values @15-15

### servo/components/style/queries/values.rs

Blob: `98b16d76f35eabb6a39739d4b163a2b90ec18fdd`. Grammar: rust. Status: syntax-clean.

- enum_item Orientation @17-20
- function_item eval @24-36
- enum_item PrefersColorScheme @43-46

### servo/components/style/rule_cache.rs

Blob: `b36aadabe32c9b60077fa80facfe766ea2ebe5d8`. Grammar: rust. Status: syntax-clean.

- struct_item RuleCacheConditions @23-29
- function_item set_font_size_dependency @33-36
- function_item set_line_height_dependency @39-42
- function_item set_color_scheme_dependency @45-48
- function_item set_uncacheable @51-53
- function_item set_writing_mode_dependency @56-59
- function_item cacheable @62-64
- struct_item CachedConditions @68-73
- function_item matches @77-120
- struct_item RuleCache @124-127
- function_item default @130-132
- function_item new @137-141
- function_item get_rule_node_for_cache @153-176
- function_item find @182-212
- function_item insert_if_possible @217-265

### servo/components/style/rule_collector.rs

Blob: `586237b3c07b1e704869323441ae2c0bc5a7cf50`. Grammar: rust. Status: syntax-clean.

- function_item containing_shadow_ignoring_svg_use @38-55
- struct_item RuleCollector @62-82
- function_item new @89-120
- function_item in_tree @128-140
- function_item in_shadow_tree @143-145
- function_item collect_stylist_rules @147-173
- function_item collect_user_agent_rules @175-179
- function_item collect_view_transition_dynamic_rules @182-198
- function_item collect_user_rules @200-206
- function_item collect_presentational_hints @212-231
- function_item collect_rules_in_list @234-250
- function_item collect_rules_in_map @253-265
- function_item collect_rules_in_map_with_target @268-285
- function_item is_element_backed_pseudo_element @292-296
- function_item collect_host_and_slotted_rules @299-337
- function_item collect_rules_from_containing_shadow_tree @339-380
- function_item collect_host_rules @383-413
- function_item collect_document_author_rules @415-421
- function_item collect_part_rules_from_outer_trees @423-486
- function_item collect_style_attribute @488-497
- function_item collect_animation_rules @499-531
- function_item collect_all @536-554

### servo/components/style/rule_tree/core.rs

Blob: `479dcfe7b2a4d014e7f82cf73e602331ee173da3`. Grammar: rust. Status: syntax-clean.

- struct_item RuleTree @40-42
- function_item drop @45-47
- function_item size_of @51-66
- struct_item ChildKey @70-70
- function_item default @75-77
- function_item new @82-86
- function_item root @89-91
- function_item gc @94-96
- function_item maybe_gc @99-106
- function_item maybe_dump_stats @109-154
- function_item swap_free_list_and_gc @157-204
- struct_item RuleNode @213-272
- mod_item gecko_leak_checking @276-302
- function_signature_item NS_LogCtor @282-282
- function_signature_item NS_LogDtor @283-283
- function_item log_ctor @288-293
- function_item log_dtor @296-301
- function_item log_new @305-308
- function_item log_drop @311-314
- function_item new @319-337
- function_item root @339-354
- function_item key @356-364
- function_item drop_without_free_list @377-458
- function_item push_on_free_list @463-507
- function_item pretend_to_be_on_free_list @513-517
- function_item as_mut_ptr @519-521
- struct_item WeakRuleNode @524-526
- struct_item StrongRuleNode @529-531
- function_item new @537-547
- function_item from_unsafe_box @549-551
- function_item downgrade @553-559
- function_item parent @562-564
- function_item root_matches @566-571
- function_item ensure_child @573-617
- function_item style_source @622-624
- function_item cascade_priority @628-630
- function_item cascade_level @634-636
- function_item importance @640-642
- function_item has_children_for_testing @646-648
- function_item dump @650-686
- function_item clone @690-699
- function_item drop @704-745
- function_item upgrade @752-766
- function_item fmt @770-772
- function_item eq @777-779
- function_item eq @784-786
- function_item hash @790-795

### servo/components/style/rule_tree/level.rs

Blob: `808e839fef6eccbb9d58528b7eb32de976be762b`. Grammar: rust. Status: syntax-clean.

- struct_item CascadeLevel @52-52
- enum_item CascadeOrigin @97-114
- function_item origin @119-125
- function_item guard @129-134
- function_item cmp @138-163
- function_item partial_cmp @167-169
- function_item new @179-183
- function_item origin @187-191
- function_item important @194-205
- function_item unimportant @208-212
- function_item guard @216-218
- function_item same_tree_author_important @223-225
- function_item same_tree_author_normal @230-232
- function_item is_important @237-239
- function_item importance @244-250
- function_item is_animation @254-261
- function_item is_tree @265-267
- function_item shadow_order @271-275
- function_item author_normal @279-285
- function_item get_shadow_root_for_scoped @288-319
- struct_item ShadowCascadeOrder @330-330
- function_item for_outermost_shadow_tree @340-342
- function_item for_same_tree @346-348
- function_item for_innermost_containing_tree @353-355
- function_item is_in_same_or_containing_tree @359-361
- function_item dec @366-371
- function_item inc @376-381
- function_item neg @387-389

### servo/components/style/rule_tree/map.rs

Blob: `81c4baa6e69e6afa3680399d1dc4bb5056742235`. Grammar: rust. Status: syntax-clean.

- struct_item Map @14-16
- enum_item MapInner @18-22
- struct_item MapIter @24-26
- enum_item MapIterInner @28-31
- enum_item Entry @33-36
- struct_item VacantEntry @38-40
- enum_item VacantEntryInner @42-45
- function_item default @48-52
- function_item into_iter @59-67
- function_item next @73-78
- function_item is_empty @85-91
- function_item len @94-100
- function_item get @102-108
- function_item entry @110-158
- function_item remove @160-171
- function_item insert @175-186
- function_item shallow_size_of @193-201

### servo/components/style/rule_tree/mod.rs

Blob: `804aa29e96eaa62eaa14421715148c1adfac6683`. Grammar: rust. Status: syntax-clean.

- mod_item core @17-17
- mod_item level @18-18
- mod_item map @19-19
- mod_item source @20-20
- mod_item unsafe_box @21-21
- function_item dump @42-45
- function_item dump_stdout @48-51
- function_item insert_ordered_rules_with_important @59-169
- function_item compute_rule_node @173-182
- function_item insert_ordered_rules @186-191
- function_item insert_ordered_rules_from @193-202
- function_item update_rule_at_level @208-292
- function_item has_starting_style @295-301
- function_item remove_transition_rule_if_applicable @304-311
- function_item remove_animation_rules @314-339
- function_item self_and_ancestors @344-348
- function_item has_animation_or_transition_rules @351-357
- function_item get_properties_overriding_animations @364-403
- struct_item SelfAndAncestors @408-410
- function_item next @415-419

### servo/components/style/rule_tree/source.rs

Blob: `463bf531ca29ec3256eeaaaa82793601fdf09bf3`. Grammar: rust. Status: syntax-clean.

- struct_item StyleSource @21-21
- struct_item StyleSourceBorrow @28-28
- function_item eq @35-37
- function_item eq @41-43
- function_item from_declarations @49-51
- function_item to_owned @55-57
- function_item key @60-62
- function_item read @67-72
- function_item key @77-79
- function_item borrow @83-85
- function_item from_declarations @89-91
- function_item dump @93-95
- function_item read @100-102
- function_item get @106-108
- function_item mark_in_rule_tree @112-132

### servo/components/style/rule_tree/unsafe_box.rs

Blob: `bc7a8da186a532f33edacec1b493e828c166bbfd`. Grammar: rust. Status: syntax-clean.

- struct_item UnsafeBox @12-14
- function_item from_box @18-22
- function_item from_raw @29-35
- function_item clone @43-49
- function_item deref_mut @57-59
- function_item drop @67-69
- function_item deref @75-77

### servo/components/style/scoped_tls.rs

Blob: `0b1cd33f2018672669122eb4810fb6555af0eedf`. Grammar: rust. Status: syntax-clean.

- struct_item ScopedTLS @21-24
- function_item new @33-39
- function_item current_thread_index @43-45
- function_item borrow @48-51
- function_item borrow_mut @54-57
- function_item ensure @66-73
- function_item slots @77-79

### servo/components/style/selector_map.rs

Blob: `d5cb851df00da969c2b534f06a90f67712ba2322`. Grammar: rust. Status: syntax-clean.

- struct_item PrecomputedHasher @30-34
- function_item write @67-72
- function_item write_u32 @75-85
- function_item write_u64 @88-97
- function_item finish @100-104
- trait_item SelectorMapEntry @108-113
- function_signature_item selector @110-110
- function_item set_bucket_matches @112-112
- struct_item SelectorMap @143-162
- function_item default @166-168
- function_item new @173-185
- function_item shrink_if_needed @188-194
- function_item clear @197-207
- function_item is_empty @210-212
- function_item len @215-217
- function_item get_all_matching_rules @225-345
- function_item get_matching_rules @348-390
- function_item insert @395-502
- function_item lookup @514-532
- function_item lookup_with_state @535-636
- function_item lookup_with_additional @646-693
- enum_item Bucket @697-712
- function_item specificity @717-728
- function_item more_or_equally_specific_than @731-733
- function_item more_specific_than @736-738
- enum_item BucketMatches @745-752
- function_item specific_bucket_for @754-927
- function_item find_bucket @938-982
- struct_item MaybeCaseInsensitiveHashMap @986-986
- function_item default @990-992
- function_item new @997-999
- function_item shrink_if_needed @1002-1004
- function_item try_get_or_insert_with @1008-1023
- function_item is_empty @1027-1029
- function_item iter @1032-1034
- function_item clear @1037-1039
- function_item get @1042-1051
- function_item test_precomputed_hash_set @1056-1062

### servo/components/style/selector_parser.rs

Blob: `eacb0ed96b59a2985cf843048df94339e315fe4c`. Grammar: rust. Status: syntax-clean.

- struct_item SelectorParser @43-53
- function_item parse_author_origin_no_namespace @60-72
- function_item in_user_agent_stylesheet @75-77
- function_item chrome_rules_enabled @81-83
- enum_item PseudoElementCascadeType @88-111
- struct_item PerPseudoElementMap @115-118
- function_item default @121-126
- function_item fmt @133-148
- function_item get @153-162
- function_item clear @165-168
- function_item set @173-183
- function_item get_or_insert_with @186-200
- function_item iter @203-205
- function_item iter_mut @208-210
- struct_item Direction @217-217
- enum_item HorizontalDirection @221-226
- function_item parse @230-237
- function_item as_horizontal_direction @240-248
- function_item element_state @251-257
- function_item to_css @261-266
- mod_item tests @270-305
- function_item can_build_and_set_arbitrary_index @274-296
- function_item can_iter @299-304

### servo/components/style/servo/animation.rs

Blob: `fbce79f4c227450e87c888cd882ae30482cdb407`. Grammar: rust. Status: syntax-clean.

- struct_item PropertyAnimation @42-54
- function_item property_id @58-61
- function_item timing_function_output @64-73
- function_item calculate_value @76-87
- enum_item AnimationState @92-105
- function_item needs_to_be_ticked @109-111
- enum_item IgnoreTransitions @114-117
- enum_item KeyframesIterationState @124-129
- struct_item IntermediateComputedKeyframe @136-141
- function_item new @144-151
- function_item generate_for_keyframes @155-183
- function_item update_from_step @185-228
- function_item resolve_style @230-270
- struct_item PropertyDeclarationOffsets @274-281
- enum_item AnimationValueOrReference @284-289
- struct_item ComputedKeyframe @293-305
- function_item composite_animation_value @311-324
- struct_item KeyframeOffsetCacheForProperty @332-346
- struct_item KeyframeDataForProperty @348-358
- enum_item Direction @361-364
- function_item relative_to_animation_direction @367-373
- function_item next_relevant_keyframe_for_property_in_direction @381-415
- function_item generate_for_keyframes @418-556
- struct_item Animation @561-602
- function_item is_cancelled_in_new_style @606-617
- function_item iterate_if_necessary @622-633
- function_item iterate_by @638-676
- function_item remaining_iterations @678-683
- function_item current_iteration_end_progress @689-691
- function_item current_iteration_duration @695-697
- function_item iteration_over @701-703
- function_item on_last_iteration @706-708
- function_item has_ended @713-726
- function_item update_from_other @735-839
- function_item get_property_declaration_at_time @843-1013
- function_item fmt @1017-1029
- struct_item Transition @1034-1059
- function_item new @1062-1085
- function_item update_for_possibly_reversed_transition @1087-1155
- function_item has_ended @1160-1162
- function_item calculate_value @1165-1175
- struct_item ElementAnimationSet @1180-1190
- function_item cancel_all_animations @1195-1201
- function_item cancel_active_transitions @1203-1210
- function_item apply_active_animations @1213-1231
- function_item clear_canceled_animations @1234-1239
- function_item is_empty @1243-1245
- function_item needs_animation_ticks @1249-1257
- function_item running_animation_and_transition_count @1260-1270
- function_item has_active_animation @1273-1277
- function_item has_active_transition @1280-1284
- function_item update_animations_for_new_style @1288-1304
- function_item update_transitions_for_new_style @1308-1368
- function_item start_transition_if_applicable @1370-1559
- function_item get_value_map_for_transitions @1564-1596
- function_item get_value_map_for_active_animations @1600-1611
- struct_item AnimationSetKey @1616-1622
- function_item new @1626-1631
- function_item new_for_non_pseudo @1634-1639
- function_item new_for_pseudo @1642-1647
- struct_item DocumentAnimationSet @1652-1656
- function_item has_active_animations @1660-1665
- function_item has_active_transitions @1668-1673
- function_item get_animation_declarations @1677-1691
- function_item get_transition_declarations @1695-1711
- function_item get_all_declarations @1715-1741
- function_item cancel_all_animations_for_key @1744-1748
- function_item start_transitions_if_applicable @1753-1797
- function_item maybe_start_animations @1801-1922

### servo/components/style/servo/attr.rs

Blob: `e94f070fdf4b31e82eb067367a8ddffdb42c9966`. Grammar: rust. Status: syntax-clean.

- enum_item LengthOrPercentageOrAuto @37-41
- enum_item AttrValue @44-85
- function_item from @88-90
- function_item from @94-96
- function_item from @100-102
- function_item from @106-108
- function_item from @112-114
- function_item do_parse_integer @120-141
- function_item parse_integer @145-147
- function_item parse_unsigned_integer @151-153
- function_item parse_double @157-201
- function_item from_serialized_tokenlist @204-215
- function_item from_comma_separated_tokenlist @217-227
- function_item from_u32 @230-238
- function_item from_i32 @240-243
- function_item from_double @246-254
- function_item from_limited_i32 @257-265
- function_item from_limited_u32 @268-276
- function_item from_atomic @278-280
- function_item from_resolved_url @282-285
- function_item from_legacy_color @287-290
- function_item from_dimension @292-295
- function_item from_nonzero_dimension @297-300
- function_item from_shadow_parts @302-305
- function_item from_declaration @307-316
- function_item as_tokens @323-328
- function_item as_atom @335-340
- function_item as_length_percentage @347-352
- function_item as_color @359-364
- function_item as_dimension @371-376
- function_item as_resolved_url @383-388
- function_item as_int @397-403
- function_item as_uint @412-418
- function_item as_uint_px_dimension @429-435
- function_item as_shadow_parts @445-451
- function_item eval_selector @453-458
- function_item deref @464-499
- function_item eq @503-508
- function_item parse_nonzero_length @512-518
- function_item parse_legacy_color @523-646
- function_item hex @626-633
- function_item hex_string @635-645
- function_item parse_length @652-705
- struct_item AttrIdentifier @709-714

### servo/components/style/servo/encoding_support.rs

Blob: `d0b53737ad7c82608a73eeac45d1202d462ecad3`. Grammar: rust. Status: syntax-clean.

- struct_item EncodingRs @17-17
- function_item utf8 @22-24
- function_item is_utf16_be_or_le @26-28
- function_item from_label @30-32
- function_item decode_stylesheet_bytes @35-48
- function_item from_bytes @56-80

### servo/components/style/servo/media_features.rs

Blob: `9e5a77e82a6f877bbf225bb93b6531885c323a27`. Grammar: rust. Status: syntax-clean.

- function_item eval_width @14-16
- function_item eval_height @19-21
- function_item eval_device_width @24-28
- function_item eval_device_height @31-35
- function_item eval_orientation @38-40
- enum_item Scan @44-47
- function_item eval_scan @50-54
- function_item eval_resolution @57-59
- function_item eval_device_pixel_ratio @62-64
- function_item eval_prefers_color_scheme @66-71
- function_item default @88-90
- function_item default @92-94
- enum_item Pointer @99-103
- function_item eval_pointer_capabilities @105-115
- function_item eval_pointer @118-120
- function_item eval_any_pointer @123-125
- enum_item Hover @129-132
- function_item eval_hover_capabilities @134-144
- function_item eval_hover @147-149
- function_item eval_any_hover @152-154
- function_item eval_aspect_ratio @157-160

### servo/components/style/servo/mod.rs

Blob: `173cad72f32234831436d8d19f6370593915975a`. Grammar: rust. Status: syntax-clean.

- mod_item animation @9-9
- mod_item attr @11-11
- mod_item encoding_support @12-12
- mod_item media_features @13-13
- mod_item restyle_damage @14-14
- mod_item selector_parser @15-15
- mod_item shadow_parts @16-16

### servo/components/style/servo/restyle_damage.rs

Blob: `3314954470a48f3bb57a3f9ec602cc6b335f5ed3`. Grammar: rust. Status: syntax-clean.

- function_item compute_style_difference @58-106
- function_item reconstruct @109-113
- function_item default @117-119
- function_item fmt @123-154
- function_item augmented_restyle_damage_rebuild_box @157-164
- function_item augmented_restyle_damage_rebuild_stacking_context @166-172
- function_item compute_damage @174-188
- function_item guarantees_stacking_context @197-202
- function_item has_transform_or_perspective @207-214

### servo/components/style/servo/selector_parser.rs

Blob: `471b96f0f7e44655d0d18414ccbf452d21c012a4`. Grammar: rust. Status: syntax-clean.

- enum_item PseudoElement @39-81
- function_item to_css @87-116
- function_item parses_as_element_backed @120-122
- function_item eager_index @131-134
- function_item index @138-140
- function_item pseudo_none_array @143-145
- function_item from_eager_index @149-155
- function_item is_before_or_after @159-161
- function_item is_unknown_webkit_pseudo_element @165-167
- function_item is_marker @171-173
- function_item is_selection @177-179
- function_item is_before @183-185
- function_item is_after @189-191
- function_item is_first_letter @195-197
- function_item is_first_line @201-203
- function_item is_color_swatch @208-210
- function_item is_eager @214-216
- function_item is_lazy @220-222
- function_item is_anon_box @225-227
- function_item skip_item_display_fixup @232-234
- function_item is_precomputed @238-240
- function_item cascade_type @250-275
- function_item canonical @279-281
- function_item pseudo_info @284-286
- function_item property_restriction @290-300
- function_item should_exist @304-314
- function_item is_highlight @317-319
- function_item has_argument @323-325
- function_item is_target_text @329-331
- function_item is_lazy_painted_highlight_pseudo @337-339
- function_item is_element_backed @344-359
- struct_item CustomState @367-367
- enum_item NonTSPseudoClass @373-412
- function_item is_active_or_hover @416-418
- function_item is_user_action_state @421-426
- function_item visit @428-430
- function_item to_css @434-488
- function_item state_flag @494-534
- function_item document_state_flag @537-539
- function_item needs_cache_revalidation @542-544
- struct_item SelectorImpl @550-550
- struct_item ExtraMatchingData @555-566
- function_item parse_nth_child_of @587-589
- function_item parse_is_and_where @592-594
- function_item parse_has @597-599
- function_item parse_parent_selector @602-604
- function_item parse_part @607-609
- function_item allow_forgiving_selectors @612-614
- function_item parse_non_ts_pseudo_class @616-663
- function_item parse_non_ts_functional_pseudo_class @665-683
- function_item parse_pseudo_element @685-755
- function_item default_namespace @757-759
- function_item namespace_for_prefix @761-763
- function_item parse_host @765-767
- function_item parse_slotted @769-771
- function_item each_eagerly_cascaded_pseudo_element @778-785
- struct_item SnapshotMap @790-790
- function_item new @794-796
- function_item get @799-801
- function_item deref @807-809
- function_item deref_mut @813-815
- struct_item ServoElementSnapshot @820-833
- function_item new @837-839
- function_item id_changed @842-844
- function_item class_changed @847-849
- function_item other_attr_changed @852-854
- function_item get_attr @856-862
- function_item each_attr_changed @866-873
- function_item any_attr_ignore_ns @875-884
- function_item state @888-890
- function_item has_attrs @892-894
- function_item id_attr @896-899
- function_item is_part @901-908
- function_item imported_part @910-912
- function_item has_class @914-921
- function_item each_class @923-932
- function_item lang_attr @934-938
- function_item has_custom_states @942-944
- function_item has_custom_state @948-950
- function_item each_custom_state @953-957
- function_item attr_matches @962-976
- function_item extended_filtering @981-1031

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [4b277d57-7417-4571-bd02-cec162a55282.md](4b277d57-7417-4571-bd02-cec162a55282.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `1ba5a7080a7d590f130fd2b3acbd7e759cebed378b3111c962a7e620b09ea28a`.
