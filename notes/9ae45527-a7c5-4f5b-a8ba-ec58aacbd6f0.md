<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:18:44.114924+00:00","paths":["testing"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["54f7b99d26a1b07a6077e5c9a7455010e881ef20d2c81f9d44dddd5f11afbaab"],"sourceAt":"2026-10-13T04:18:44.114924+00:00","correctionOf":"notes/84994754-8468-4e64-a39d-66919533b006.md"}} -->
# firefox/testing Python and build syntax map 108

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Python AST parser; no source was executed. Functions and classes have source ranges. Imports are written names, not resolved modules. Build entries list assignments with literal string lists and registration calls. Conditions are not evaluated; listed files are not necessarily built or shipped. Dynamic expressions and included build files need separate analysis. Failed parses remain listed.

### testing/web-platform/tests/webdriver/tests/bidi/network/set_extra_headers/headers_name_standard_tentative.py

Blob: `9466f802857514698a2ef7fff6bef4de9ed60346`. Parse: parsed.

- import pytest @5
- async-function test_set_standard_headers @41-55

### testing/web-platform/tests/webdriver/tests/bidi/network/set_extra_headers/invalid.py

Blob: `a81b6cde56d15ce9ff3fe5eed9997f090c4a1290`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @3
- from tests.bidi import get_invalid_cases @4
- from webdriver.bidi.undefined import UNDEFINED @5
- async-function test_params_contexts_invalid_type @18-24
- async-function test_params_contexts_empty_list @27-31
- async-function test_params_contexts_entry_invalid_type @35-40
- async-function test_params_contexts_entry_invalid_value @43-49
- async-function test_params_contexts_iframe @52-69
- async-function test_params_user_contexts_invalid_type @73-79
- async-function test_params_user_contexts_empty_list @82-87
- async-function test_params_user_contexts_entry_invalid_type @91-97
- async-function test_params_user_contexts_entry_invalid_value @101-107
- async-function test_params_contexts_and_user_contexts @110-117
- async-function test_params_headers_missing @120-123
- async-function test_params_headers_invalid_type @127-130
- async-function test_params_headers_header_invalid_type @134-137
- async-function test_params_headers_header_name_invalid_type @141-146
- async-function test_params_headers_header_name_invalid_value @154-159
- async-function test_params_headers_header_value_invalid_type @163-169
- async-function test_params_headers_header_value_invalid_value @181-187

### testing/web-platform/tests/webdriver/tests/bidi/network/set_extra_headers/user_contexts.py

Blob: `df7289ad2fc69b30d480540cf939831d59e4d270`. Parse: parsed.

- import pytest @5
- from tests.bidi.network.set_extra_headers import SOME_HEADER_NAME,USER_CONTEXT_HEADER,USER_CONTEXT_VALUE,GLOBAL_HEADER,GLOBAL_VALUE @7
- from tests.bidi.network.set_extra_headers.conftest import prepare_context @9
- async-function test_isolation @14-51
- async-function test_frame @56-75
- async-function test_overrides_global @78-106

### testing/web-platform/tests/webdriver/tests/bidi/script/__init__.py

Blob: `15b599ad932c29a5833a2439c35e8f2f99e87087`. Parse: parsed.

- from __future__ import annotations @1
- from typing import Any,Callable,Mapping @2
- from webdriver.bidi.modules.script import ContextTarget @3
- from .. import any_int,any_string,recursive_compare @5
- function specific_error_response @8-20
- function any_stack_trace @23-28
- function any_stack_frame @31-44
- async-function create_sandbox @208-226

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/add_preload_script.py

Blob: `f608b99024e810216c31f1d87dad12970ead6938`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_add_preload_script @9-57
- async-function test_add_same_preload_script_twice @60-65
- async-function test_script_order @68-100
- async-function test_script_order.on_event @80-83
- async-function test_add_preload_script_in_iframe @103-133
- async-function test_add_preload_script_with_error @136-157
- async-function test_page_script_can_access_preload_script_properties @160-180
- async-function test_add_preload_script_order_with_different_configuration @194-244
- async-function test_add_preload_script_order_with_different_configuration.add_preload_script_of_type @198-217

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/arguments.py

Blob: `8dc98bce316d25c7e5410d0f58d8626340740b0e`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- from ... import any_string,recursive_compare @4
- async-function test_channel @62-92
- async-function test_channel_with_multiple_arguments @95-119
- async-function test_mutation_observer @122-179
- async-function test_two_channels @182-237
- async-function test_two_channels.on_event @193-194

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/contexts.py

Blob: `1cc9310f27952ce2582b953e5e6417041fafff24`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_top_context_with_iframes @9-46
- async-function test_page_script_context_isolation @50-85
- async-function test_identical_contexts @88-110

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/execution_order_tentative.py

Blob: `bce240d08e2c439e20511e457280382cc8969b6e`. Parse: parsed.

- import asyncio @1
- import pytest @2
- from webdriver.bidi.modules.script import ContextTarget @4
- async-function test_preload_script_properties_available_immediately @21-100

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/invalid.py

Blob: `dd59895a5683728521c525e8e9153633d8faab1d`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- async-function test_params_function_declaration_invalid_type @8-14
- async-function test_params_arguments_invalid_type @18-23
- async-function test_params_arguments_entry_invalid_type @27-32
- async-function test_params_arguments_entry_invalid_value @35-40
- async-function test_params_arguments_channel_value_invalid_type @44-49
- async-function test_params_arguments_channel_id_invalid_type @53-58
- async-function test_params_arguments_channel_ownership_invalid_type @62-75
- async-function test_params_arguments_channel_ownership_invalid_value @78-88
- async-function test_params_arguments_channel_serialization_options_invalid_type @92-107
- async-function test_params_arguments_channel_max_dom_depth_invalid_type @111-126
- async-function test_params_arguments_channel_max_dom_depth_invalid_value @129-142
- async-function test_params_arguments_channel_max_object_depth_invalid_type @146-161
- async-function test_params_arguments_channel_max_object_depth_invalid_value @164-177
- async-function test_params_arguments_channel_include_shadow_tree_invalid_type @181-198
- async-function test_params_arguments_channel_include_shadow_tree_invalid_value @201-214
- async-function test_params_contexts_invalid_type @218-222
- async-function test_params_contexts_empty_list @225-229
- async-function test_params_contexts_context_invalid_type @233-237
- async-function test_params_contexts_context_invalid_value @241-245
- async-function test_params_contexts_context_non_top_level @248-266
- async-function test_params_sandbox_invalid_type @270-274
- async-function test_params_user_contexts_invalid_type @278-282
- async-function test_params_user_contexts_empty_list @285-289
- async-function test_params_user_contexts_entry_invalid_type @293-297
- async-function test_params_user_contexts_entry_invalid_value @301-305
- async-function test_params_user_context_and_contexts @308-314

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/sandbox.py

Blob: `3aa3c70d424054656791a034eaa80903f1db5639`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import recursive_compare @5
- async-function test_add_preload_script_to_sandbox @10-42
- async-function test_remove_properties_set_by_preload_script @45-72
- async-function test_arguments @75-111

### testing/web-platform/tests/webdriver/tests/bidi/script/add_preload_script/user_contexts.py

Blob: `db798d83f4f316e5bab3e81a5586228f83f0fab2`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_add_preload_script_to_user_context @8-55
- async-function test_add_preload_script_to_default_user_context @58-105
- async-function test_add_preload_script_to_multiple_user_contexts @108-142
- async-function test_identical_user_contexts @145-166

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/arguments.py

Blob: `622d0d2e863e140cd4cd53d304406726fd949cbf`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- from ... import recursive_compare @4
- from .. import PRIMITIVE_VALUES @5
- async-function test_default_arguments @10-17
- async-function test_primitive_value @21-38
- async-function test_local_value @84-100

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/await_promise.py

Blob: `cbdaeae6d98c053653e118f5e4ea29b97a885c74`. Parse: parsed.

- import pytest @1
- from ... import recursive_compare @3
- from webdriver.bidi.modules.script import ContextTarget @4
- async-function test_await_promise_delayed @10-29
- async-function test_await_promise_async_arrow @33-46

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/channel.py

Blob: `b29a8c59d37feab60b275ac32bb00e6001c2ed33`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- from ... import any_string,recursive_compare @4
- async-function test_channel @63-88
- async-function test_channel_with_multiple_arguments @91-117
- async-function test_two_channels @120-177
- async-function test_two_channels.on_event @131-132
- async-function test_channel_and_nonchannel_arguments @180-214

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/csp_tentative.py

Blob: `b4c92e4f2a1f6b3923265bf69c29339232958b0e`. Parse: parsed.

- import pytest @1
- import asyncio @2
- from webdriver.bidi.modules.script import ContextTarget @4
- from .. import CSP_EXPRESSIONS @6
- async-function test_default_src_unsafe_inline @16-31

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/exception_details.py

Blob: `06c4488492cf162a250703cd4508fc024b642ae5`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @2
- from ... import any_int,any_string,recursive_compare @4
- from .. import any_stack_trace,PRIMITIVE_VALUES,REMOTE_VALUES @5
- async-function test_exception_details @11-33
- async-function test_invalid_function @36-55
- async-function test_rejected_promise @59-84

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/exception_details_await_promise.py

Blob: `f3c75f8b689038141fc24014a0a1f44b7f6830ac`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @2
- from ... import any_int,any_string,recursive_compare @4
- from .. import any_stack_trace,PRIMITIVE_VALUES,REMOTE_VALUES @5
- async-function test_exception_details @11-33

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/function_declaration.py

Blob: `460880706e17e0e2efc205a25548afab359e7d05`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_arrow_function @8-15

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/internal_id.py

Blob: `95e4f5798b8b6a6a17143c4eb7509f277caa7caf`. Parse: parsed.

- import pytest @1
- from ... import recursive_compare,any_string @3
- async-function test_remote_values_with_internal_id @25-53
- async-function test_different_remote_values_have_unique_internal_ids @56-67

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/invalid.py

Blob: `ccd5bcfa439e5bf661715fb31fc9ccb00fe5c09b`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget,SerializationOptions @4
- async-function test_params_target_invalid_type @14-18
- async-function test_params_context_invalid_type @22-28
- async-function test_params_sandbox_invalid_type @32-38
- async-function test_params_context_unknown @41-47
- async-function test_params_realm_invalid_type @51-57
- async-function test_params_realm_unknown @60-66
- async-function test_params_function_declaration_invalid_type @70-78
- async-function test_params_this_invalid_type @82-89
- async-function test_params_arguments_invalid_type @93-100
- async-function test_params_arguments_entry_invalid_type @104-111
- async-function test_params_arguments_channel_value_invalid_type @115-124
- async-function test_params_arguments_channel_id_invalid_type @128-137
- async-function test_params_arguments_channel_ownership_invalid_type @141-150
- async-function test_params_arguments_channel_ownership_invalid_value @153-162
- async-function test_params_arguments_channel_serialization_options_invalid_type @166-183
- async-function test_params_arguments_channel_max_dom_depth_invalid_type @187-204
- async-function test_params_arguments_channel_max_dom_depth_invalid_value @207-224
- async-function test_params_arguments_channel_max_object_depth_invalid_type @228-245
- async-function test_params_arguments_channel_max_object_depth_invalid_value @248-265
- async-function test_params_arguments_channel_include_shadow_tree_invalid_type @269-288
- async-function test_params_arguments_channel_include_shadow_tree_invalid_value @291-308
- async-function test_params_arguments_handle_invalid_type @312-323
- async-function test_params_arguments_handle_unknown_value @326-337
- async-function test_params_arguments_sharedId_invalid_type @341-352
- async-function test_params_await_promise_invalid_type @356-364
- async-function test_params_result_ownership_invalid_value @368-377
- async-function test_params_serialization_options_invalid_type @381-390
- async-function test_params_max_dom_depth_invalid_type @394-403
- async-function test_params_max_dom_depth_invalid_value @406-413
- async-function test_params_max_object_depth_invalid_type @417-428
- async-function test_params_max_object_depth_invalid_value @431-438
- async-function test_params_include_shadow_tree_invalid_type @442-453
- async-function test_params_include_shadow_tree_invalid_value @456-463
- async-function test_params_user_activation_invalid_type @467-476

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/primitive_values.py

Blob: `16453e9d0bde3028c9e506a82f5c4f684dc2ff10`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from .. import PRIMITIVE_VALUES @4
- async-function test_primitive_values @11-23

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/realm.py

Blob: `01e148b2a1a4a12fa1206596fc20555cedb71cf4`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import RealmTarget @3
- from ... import recursive_compare @4
- async-function test_target_realm @9-28
- async-function test_different_target_realm @31-71

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/remote_reference.py

Blob: `a0430f49d24f73d80db96066562185f14c0e46d1`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @3
- from ... import any_string,recursive_compare @5
- async-function test_remote_reference_argument @97-117
- async-function test_remote_reference_deserialization @145-164
- async-function test_remote_reference_node_argument @192-212
- async-function test_remote_reference_node_cdata @215-235
- async-function test_remote_reference_sharedId_precedence_over_handle @238-262
- async-function test_remote_reference_dom_collection @305-334

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/remote_values.py

Blob: `32b4b87e850cc8c444c2edabe27b0612aefbea98`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @3
- from ... import recursive_compare @4
- from .. import REMOTE_VALUES @5
- async-function test_remote_values @15-27
- async-function test_remote_value_promise @31-41
- async-function test_window_context_top_level @45-63
- async-function test_window_context_iframe_window @69-99
- async-function test_window_context_iframe_content_window @105-136
- async-function test_window_context_same_id_after_navigation @142-175

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/result_node.py

Blob: `b6cd9bfdd94215096ad32cccddd0acae443bf9e1`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @2
- from ... import any_string,recursive_compare @4
- async-function test_element_node @135-149
- async-function test_attribute_node @191-204
- async-function test_text_node @228-241
- async-function test_cdata_node @265-278
- async-function test_processing_instruction_node @302-317
- async-function test_comment_node @341-354
- async-function test_document_node @395-409
- async-function test_doctype_node @432-445
- async-function test_document_fragment_node @484-498
- async-function test_node_embedded_within @629-642
- async-function test_node_within_dom_collection @691-709
- async-function test_custom_element_with_shadow_root @713-749

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/result_ownership.py

Blob: `f30facb73a8ae264e0f1b4777169966fc9a8f305`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @3
- from ... import assert_handle @4
- async-function test_throw_exception @11-19
- async-function test_invalid_script @24-32
- async-function test_rejected_promise @37-45
- async-function test_return_value @51-58

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/sandbox.py

Blob: `7c466b0b1f7b8840f0b67dcaf22bb24bd212996a`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget,ScriptEvaluateResultException @3
- from ... import any_int,any_string,recursive_compare @5
- from .. import any_stack_trace @6
- async-function test_sandbox @11-48
- async-function test_sandbox_with_empty_name @51-73
- async-function test_switch_sandboxes @76-101
- async-function test_sandbox_with_side_effects @104-125
- async-function test_sandbox_returns_same_node @128-141
- async-function test_arguments @144-163
- async-function test_arguments_uses_same_node_in_sandbox @166-180
- async-function test_exception_details @184-208
- async-function test_target_realm @211-232

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/serialization_options.py

Blob: `68c8cf9c1cb50bdd0ba5fe4ea0edf6391601ecd8`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @2
- from webdriver.bidi.undefined import UNDEFINED @3
- from ... import any_string,recursive_compare @5
- async-function test_include_shadow_tree_for_custom_element @159-186
- async-function test_include_shadow_tree_for_shadow_root @272-298
- async-function test_max_dom_depth @432-446
- async-function test_max_dom_depth_null @449-520
- async-function test_max_object_depth @559-567

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/strict_mode.py

Blob: `a1a8f4c079f72cf196ec29c78bb7207e1df84003`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @3
- from ... import recursive_compare @4
- from .. import specific_error_response @5
- async-function test_strict_mode @10-41

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/target.py

Blob: `d6550d67d5e7e696c41f6d16836822a0cc8e9a0d`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import recursive_compare @7
- async-function test_target_context_and_realm @12-33

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/this.py

Blob: `de91bc395bae1ae8b64b3093000dfd8e5668d7c9`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import any_string,recursive_compare @5
- async-function test_this @10-27
- async-function test_default_this @30-38
- async-function test_remote_value_deserialization @66-85
- async-function test_channel @121-147

### testing/web-platform/tests/webdriver/tests/bidi/script/call_function/user_activation.py

Blob: `cbf9c8ad4e74617639f9687ad83b97e485ed3d2e`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_userActivation @9-23
- async-function test_userActivation_copy @27-46

### testing/web-platform/tests/webdriver/tests/bidi/script/conftest.py

Blob: `dfb97e86a2cc84ff38eedf889bd578d65681ecfc`. Parse: parsed.

- import pytest @1
- import pytest_asyncio @2
- from typing import Any,List,Mapping,Optional @3
- from webdriver.bidi.modules.script import ContextTarget,OwnershipModel,SerializationOptions @5
- function call_function @9-35
- async-function call_function.call_function @10-33
- async-function default_realm @39-41
- function evaluate @45-67
- async-function evaluate.evaluate @46-65
- async-function setup_csp_tentative_test @71-110

### testing/web-platform/tests/webdriver/tests/bidi/script/disown/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/disown/handles.py

Blob: `1dfa318cd1871e2e5ebdcd13bd2e3c6c26ae02b5`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @3
- from webdriver.bidi.modules.script import ContextTarget @5
- from ... import assert_handle @7
- async-function test_basic_handle @12-31
- async-function test_multiple_handles_for_different_objects @34-88
- async-function test_multiple_handles_for_same_object @91-143
- async-function test_unknown_handle @146-173

### testing/web-platform/tests/webdriver/tests/bidi/script/disown/invalid.py

Blob: `f9849f3e3961f9347f6f7c0e14ba3f3e6444aff3`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget @4
- async-function test_params_target_invalid_type @10-14
- async-function test_params_context_invalid_type @18-22
- async-function test_params_sandbox_invalid_type @26-30
- async-function test_params_context_unknown @33-37
- async-function test_params_realm_invalid_type @41-45
- async-function test_params_realm_unknown @48-52
- async-function test_params_handles_invalid_type @56-60
- async-function test_params_handles_invalid_handle_type @64-68

### testing/web-platform/tests/webdriver/tests/bidi/script/disown/target.py

Blob: `f01dcb3b717d9f3ed2586f019da09758e17c999a`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @3
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget @5
- from ... import assert_handle @7
- async-function test_realm @12-33
- async-function test_sandbox @36-95
- async-function test_context_and_realm @98-136

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/await_promise.py

Blob: `45c3fc2aeacc2449929f8a0e106f51328e0f68e1`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @3
- from ... import any_int,any_string,recursive_compare @5
- from .. import any_stack_trace,PRIMITIVE_VALUES @6
- async-function test_await_promise_delayed @11-22
- async-function test_await_promise_rejected @25-45
- async-function test_await_promise_resolved @48-55
- async-function test_await_resolve_array @58-73
- async-function test_await_resolve_date @76-86
- async-function test_await_resolve_map @89-116
- async-function test_await_resolve_primitive @120-129
- async-function test_await_resolve_regexp @132-145
- async-function test_await_resolve_set @148-173
- async-function test_no_await_promise_rejected @176-183
- async-function test_no_await_promise_resolved @186-193

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/csp_tentative.py

Blob: `f5a374ec39527b70d0f3c4bf225128890ccb04f4`. Parse: parsed.

- import pytest @1
- import asyncio @2
- from webdriver.bidi.modules.script import ContextTarget @4
- from .. import CSP_EXPRESSIONS @6
- async-function test_default_src_unsafe_inline @16-30

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/evaluate.py

Blob: `fb20ed174e3b5abf1cdce4eaf062f3ee33cb851c`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget @2
- from ... import recursive_compare @4
- async-function test_evaluate @9-17
- async-function test_interact_with_dom @20-28
- async-function test_target_realm @31-50
- async-function test_different_target_realm @53-93

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/exception_details.py

Blob: `2eb9d27a3d489f0405e2d1039d882bd0e5b47888`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @2
- from ... import any_int,any_string,recursive_compare @4
- from .. import any_stack_trace,PRIMITIVE_VALUES,REMOTE_VALUES @5
- async-function test_exception_details @11-32
- async-function test_invalid_script @35-54
- async-function test_rejected_promise @58-83

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/exception_details_await_promise.py

Blob: `119c9a4ef4f15ad4bbd8ac1685c486f14d2e2b47`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @2
- from ... import any_int,any_string,recursive_compare @4
- from .. import any_stack_trace,PRIMITIVE_VALUES,REMOTE_VALUES @5
- async-function test_exception_details_await_promise @11-33

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/internal_id.py

Blob: `e8654fa8a8646577c5cb9fa23a6fc59619c0a8e5`. Parse: parsed.

- import pytest @1
- from ... import recursive_compare,any_string @3
- async-function test_remote_values_with_internal_id @25-51
- async-function test_different_remote_values_have_unique_internal_ids @54-65
- async-function test_nested_remote_values_have_same_internal_ids @68-82

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/invalid.py

Blob: `f27720a204e5ae78e12fcfa6be883750b9767337`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget,SerializationOptions @4
- async-function test_params_target_invalid_type @10-15
- async-function test_params_context_invalid_type @19-24
- async-function test_params_sandbox_invalid_type @28-33
- async-function test_params_context_unknown @36-41
- async-function test_params_realm_invalid_type @45-50
- async-function test_params_realm_unknown @53-58
- async-function test_params_expression_invalid_type @62-67
- async-function test_params_await_promise_invalid_type @71-76
- async-function test_params_result_ownership_invalid_value @80-86
- async-function test_params_serialization_options_invalid_type @90-96
- async-function test_params_max_dom_depth_invalid_type @100-106
- async-function test_params_max_dom_depth_invalid_value @109-115
- async-function test_params_max_object_depth_invalid_type @119-125
- async-function test_params_max_object_depth_invalid_value @128-134
- async-function test_params_include_shadow_tree_invalid_type @138-144
- async-function test_params_include_shadow_tree_invalid_value @147-154
- async-function test_params_user_activation_invalid_type @158-164

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/primitive_values.py

Blob: `96aa9687b65515fbe2bc0e7aa290e47be71b6f2f`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- from .. import PRIMITIVE_VALUES @3
- async-function test_primitive_values @9-17

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/remote_values.py

Blob: `fd5210e66d8b412edc796bd019e1912557056974`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @2
- from ... import recursive_compare @3
- from .. import REMOTE_VALUES @4
- async-function test_remote_values @10-18
- async-function test_window_context_top_level @22-36
- async-function test_window_context_iframe_window @42-68
- async-function test_window_context_iframe_content_window @74-101
- async-function test_window_context_same_id_after_navigation @107-142

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/result_node.py

Blob: `55bb92265540b760a690391694b1c3b861b62ce6`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @2
- from ... import any_string,recursive_compare @4
- async-function test_element_node @135-147
- async-function test_attribute_node @189-200
- async-function test_text_node @224-235
- async-function test_cdata_node @259-272
- async-function test_processing_instruction_node @296-311
- async-function test_comment_node @335-346
- async-function test_document_node @387-399
- async-function test_doctype_node @422-433
- async-function test_document_fragment_node @472-486
- async-function test_node_embedded_within @611-624
- async-function test_node_within_dom_collection @673-691
- async-function test_custom_element_with_shadow_root @695-731

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/result_ownership.py

Blob: `6659cdd6a2f48048af625e505dec00f4af82dee8`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @3
- from ... import assert_handle @4
- async-function test_throw_exception @11-19
- async-function test_invalid_script @24-32
- async-function test_rejected_promise @37-45
- async-function test_return_value @51-58

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/sandbox.py

Blob: `47620c0c4a627b28d19241958ea32f19d3293820`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget,ScriptEvaluateResultException @3
- from ... import any_int,any_string,recursive_compare @5
- from .. import any_stack_trace @6
- async-function test_sandbox @11-48
- async-function test_sandbox_with_empty_name @51-73
- async-function test_switch_sandboxes @76-101
- async-function test_sandbox_with_side_effects @104-125
- async-function test_sandbox_returns_same_node @128-141
- async-function test_exception_details @145-170
- async-function test_target_realm @173-194

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/serialization_options.py

Blob: `00e1703dc41a8c8c1abdf974a812481b9f8978b8`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,SerializationOptions @2
- from ... import any_string,recursive_compare @4
- async-function test_include_shadow_tree_for_custom_element @158-185
- async-function test_include_shadow_tree_for_shadow_root @271-297
- async-function test_max_dom_depth @431-444
- async-function test_max_dom_depth_null @447-522
- async-function test_max_object_depth @561-569

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/strict_mode.py

Blob: `a20857d4eacd20b727d30b0782a894b6efe0936d`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget,ScriptEvaluateResultException @3
- from ... import recursive_compare @4
- from .. import specific_error_response @5
- async-function test_strict_mode @10-35

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/target.py

Blob: `e67a5dd81f7cc06f14dd68e1160bdae419d7c49b`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import recursive_compare @7
- async-function test_target_context_and_realm @12-33

### testing/web-platform/tests/webdriver/tests/bidi/script/evaluate/user_activation.py

Blob: `38d68b87476220b91ee8adc2118757fd5f571983`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_userActivation @9-23
- async-function test_userActivation_copy @27-45

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/context.py

Blob: `5ddddc5912ef5bebd4350af0a95ff30db2baeff7`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import recursive_compare @5
- async-function test_context @10-71

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/get_realms.py

Blob: `9777ef4977d2585c1befc04091f4cd7f517cc915`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import any_string,recursive_compare @5
- async-function test_payload_types @15-27
- async-function test_realm_is_consistent_when_calling_twice @30-35
- async-function test_realm_is_different_after_reload @38-48
- async-function test_multiple_top_level_contexts @52-86
- async-function test_iframes @89-147
- async-function test_origin @150-181
- async-function test_dedicated_worker @184-231
- async-function test_dedicated_worker.on_event @195-197
- async-function test_dedicated_worker_with_context @234-270
- async-function test_dedicated_worker_with_context.on_event @247-249

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/invalid.py

Blob: `c15378a6e0d097c3912bc5744c7acc5f994f37f8`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- async-function test_params_context_invalid_type @8-10
- async-function test_params_context_invalid_value @13-15
- async-function test_params_type_invalid_type @19-21
- async-function test_params_type_invalid_value @24-26

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/sandbox.py

Blob: `cf2157035cd10fe16e0a4bb4896afe3b6616de4f`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import recursive_compare @5
- async-function test_sandbox @13-53
- async-function test_origin @56-101
- async-function test_type @104-145
- async-function test_multiple_top_level_contexts @149-237

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/type.py

Blob: `f4c07a0c9102828441b6b7880da5309cb07153ea`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- from ... import any_string,recursive_compare @5
- async-function test_type @14-35
- async-function test_dedicated_worker @38-80
- async-function test_dedicated_worker.on_event @49-51
- async-function test_shared_worker @83-124
- async-function test_shared_worker.on_event @94-96
- async-function test_service_worker @127-177
- async-function test_service_worker.on_event @138-140

### testing/web-platform/tests/webdriver/tests/bidi/script/get_realms/user_context_tentative.py

Blob: `cda2f6c2e02ba9f912f5ced61b5dedbefb90156c`. Parse: parsed.

- import pytest @1
- async-function test_user_context @7-22

### testing/web-platform/tests/webdriver/tests/bidi/script/message/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/message/message.py

Blob: `347f6856965740b83d30ea531875e5802dc1030a`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- from webdriver.error import TimeoutException @3
- async-function test_unsubscribe @11-32
- async-function test_unsubscribe.on_event @17-18
- async-function test_subscribe @35-56
- async-function test_subscribe_to_one_context @59-99
- async-function test_subscribe_to_one_context.on_event @70-71

### testing/web-platform/tests/webdriver/tests/bidi/script/message/user_context_tentative.py

Blob: `26ee06ce19ec1013076c098f31f133ac155dfbe3`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- async-function test_user_context @10-37

### testing/web-platform/tests/webdriver/tests/bidi/script/realm_created/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/realm_created/realm_created.py

Blob: `d3a0cbdd73be637cfbb34af7951c6bb244965cde`. Parse: parsed.

- import pytest @3
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget @4
- from webdriver.error import TimeoutException @8
- from ... import any_string,recursive_compare @10
- from .. import create_sandbox @11
- async-function test_unsubscribe @19-35
- async-function test_unsubscribe.on_event @25-26
- async-function test_create_context @39-58
- async-function test_create_context.on_event @44-45
- async-function test_navigate @61-80
- async-function test_navigate.on_event @66-67
- async-function test_reload @83-106
- async-function test_reload.on_event @92-93
- async-function test_sandbox @110-134
- async-function test_iframe @138-162
- async-function test_iframe.on_event @143-144
- async-function test_subscribe_to_one_context @165-199
- async-function test_subscribe_to_one_context.on_event @177-178
- async-function test_script_when_realm_is_created @203-232
- async-function test_dedicated_worker @235-277
- async-function test_dedicated_worker.on_event @246-248
- async-function test_shared_worker @280-320
- async-function test_shared_worker.on_event @291-293
- async-function test_service_worker @323-372
- async-function test_service_worker.on_event @334-336
- async-function test_existing_realm @376-398
- async-function test_dedicated_worker_subscribe_to_one_context @401-467
- async-function test_dedicated_worker_subscribe_to_one_context.on_event @420-422
- async-function test_dedicated_worker_subscribe_to_user_context @470-540
- async-function test_dedicated_worker_subscribe_to_user_context.on_event @490-492

### testing/web-platform/tests/webdriver/tests/bidi/script/realm_created/user_context_tentative.py

Blob: `6288ed7ad3318caf4e85b752e27bf858e758305a`. Parse: parsed.

- import pytest @1
- async-function test_user_context @9-32
- async-function test_user_context.on_event @20-21

### testing/web-platform/tests/webdriver/tests/bidi/script/realm_created/window_open.py

Blob: `a68872c0fd37fbf1e9a6a254c9b32831df010d2a`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @2
- async-function test_window_open @12-43
- async-function test_window_open.on_event @19-20
- async-function test_event_order @47-81
- async-function test_event_order.on_event @54-55

### testing/web-platform/tests/webdriver/tests/bidi/script/realm_destroyed/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/realm_destroyed/realm_destroyed.py

Blob: `a3cc879e6ea9d888605cf5787d335d7bb6a3f856`. Parse: parsed.

- import asyncio @5
- import pytest @6
- from webdriver.bidi.error import BidiException @7
- from webdriver.bidi.modules.script import ContextTarget,RealmTarget @8
- from webdriver.error import TimeoutException @9
- from ..realm_created.realm_created import REALM_CREATED_EVENT @11
- from .. import create_sandbox @12
- async-function test_unsubscribe @20-36
- async-function test_unsubscribe.on_event @27-28
- async-function test_close_context @40-52
- async-function test_navigate @55-70
- async-function test_reload_context @73-86
- async-function test_sandbox @90-111
- async-function test_sandbox.on_event @96-97
- async-function test_subscribe_after_sandbox_creation @114-136
- async-function test_subscribe_after_sandbox_creation.on_event @124-126
- async-function test_iframe @140-164
- async-function test_iframe_destroy_parent @167-198
- async-function test_iframe_destroy_parent.on_event @181-182
- async-function test_subscribe_to_one_context @201-239
- async-function test_subscribe_to_one_context.on_event @216-217
- async-function test_dedicated_worker @242-292
- async-function test_dedicated_worker.on_realm_created_event @254-256
- async-function test_dedicated_worker.on_realm_destroyed_event @258-260
- async-function test_shared_worker @295-347
- async-function test_shared_worker.on_realm_created_event @307-309
- async-function test_shared_worker.on_realm_destroyed_event @311-313
- async-function test_dedicated_worker_subscribe_to_one_context @350-453
- async-function test_dedicated_worker_subscribe_to_one_context.on_realm_created_event @380-382
- async-function test_dedicated_worker_subscribe_to_one_context.on_realm_destroyed_event @386-388
- async-function test_dedicated_worker_subscribe_to_user_context @456-562
- async-function test_dedicated_worker_subscribe_to_user_context.on_realm_created_event @489-491
- async-function test_dedicated_worker_subscribe_to_user_context.on_realm_destroyed_event @495-497

### testing/web-platform/tests/webdriver/tests/bidi/script/remove_preload_script/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/script/remove_preload_script/invalid.py

Blob: `f32c5f57cac33c3b367e4b61a7d85def0c08321a`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- async-function test_params_script_invalid_type @8-10
- async-function test_params_script_invalid_value @13-15

### testing/web-platform/tests/webdriver/tests/bidi/script/remove_preload_script/remove_preload_script.py

Blob: `5d37bfcc36e6dfecbc0a7fcb952424e957272732`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.script import ContextTarget @4
- async-function test_remove_preload_script @10-34
- async-function test_remove_preload_script_twice @37-46
- async-function test_remove_one_of_preload_scripts @49-79
- async-function test_remove_script_set_up_for_one_context @82-118
- async-function test_remove_script_set_up_for_user_context @121-171

### testing/web-platform/tests/webdriver/tests/bidi/script/remove_preload_script/sandbox.py

Blob: `72a31219b6fac1641231e05f1850778fd224bba3`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.script import ContextTarget @3
- async-function test_remove_preload_script_from_sandbox @8-43

### testing/web-platform/tests/webdriver/tests/bidi/session/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/session/capabilities/unhandled_prompt_behavior/file/accept.py

Blob: `cc1197a53f93a83251c6acb633570702fe48edd9`. Parse: parsed.

- import pytest @2
- async-function test_string_accept @8-9
- async-function test_string_accept_and_notify @13-14
- async-function test_default_accept @18-19
- async-function test_file_accept @24-25

### testing/web-platform/tests/webdriver/tests/bidi/session/capabilities/unhandled_prompt_behavior/file/dismiss.py

Blob: `91367a33a42d0dda11d32987a254f5386fe7a9da`. Parse: parsed.

- import pytest @2
- async-function test_string_dismiss @8-9
- async-function test_string_dismiss_and_notify @13-14
- async-function test_default_dismiss @18-19
- async-function test_file_dismiss @24-25

### testing/web-platform/tests/webdriver/tests/bidi/session/capabilities/unhandled_prompt_behavior/file/ignore.py

Blob: `9d9951dd3352ad973825aa5ded332ea4b316fc46`. Parse: parsed.

- import pytest @2
- async-function test_no_capabilities @7-8
- async-function test_string_ignore @12-13
- async-function test_default_ignore @17-18
- async-function test_file_ignore @23-24

### testing/web-platform/tests/webdriver/tests/bidi/session/status/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/session/status/status.py

Blob: `26222f9adb097c43d45d8a2bac6d21c9129ec81b`. Parse: parsed.

- import pytest @1
- async-function test_bidi_session_status @8-11

### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/contexts.py

Blob: `9eb67b390c1625ad57e36d06045f47399a1ac681`. Parse: parsed.

- import pytest @1
- from ... import create_console_api_message,recursive_compare @3
- async-function test_subscribe_to_one_context @12-44
- async-function test_subscribe_to_one_context.on_event @21-22
- async-function test_subscribe_to_one_context_twice @47-77
- async-function test_subscribe_to_one_context_twice.on_event @57-58
- async-function test_subscribe_to_one_context_and_then_to_all @80-151
- async-function test_subscribe_to_one_context_and_then_to_all.on_event @89-90
- async-function test_subscribe_to_all_context_and_then_to_one_again @154-178
- async-function test_subscribe_to_all_context_and_then_to_one_again.on_event @165-166
- async-function test_subscribe_to_top_context_with_iframes @181-225
- async-function test_subscribe_to_top_context_with_iframes.on_event @204-205
- async-function test_subscribe_to_child_context @228-272
- async-function test_subscribe_to_child_context.on_event @251-252

### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/events.py

Blob: `19d6b226477904f53635e68eb9f157c04e446eba`. Parse: parsed.

- import pytest @1
- async-function test_subscribe_to_module @10-43
- async-function test_subscribe_to_module.on_event @18-19
- async-function test_subscribe_to_one_event_and_then_to_module @46-93
- async-function test_subscribe_to_one_event_and_then_to_module.on_event @56-57
- async-function test_subscribe_to_module_and_then_to_one_event_again @96-142
- async-function test_subscribe_to_module_and_then_to_one_event_again.on_event @106-107

### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/invalid.py

Blob: `01b86d0e6e480bf4dad45aa7f0b69af40417704f`. Parse: parsed.

- import asyncio @1
- import pytest @3
- from webdriver.bidi.error import InvalidArgumentException,NoSuchFrameException,NoSuchUserContextException @5
- from ... import create_console_api_message @7
- async-function test_params_empty @12-14
- async-function test_params_events_invalid_type @18-20
- async-function test_params_events_empty @23-25
- async-function test_params_events_value_invalid_type @29-31
- async-function test_params_events_value_invalid_event_name @35-37
- async-function test_params_events_value_valid_and_invalid_event_names @40-64
- async-function test_params_events_value_valid_and_invalid_event_names.on_event @52-53
- async-function test_params_contexts_invalid_type @68-70
- async-function test_params_contexts_empty @73-75
- async-function test_params_contexts_value_invalid_type @79-81
- async-function test_params_contexts_value_invalid_value @84-86
- async-function test_params_contexts_valid_and_invalid_value @89-113
- async-function test_params_contexts_valid_and_invalid_value.on_event @101-102
- async-function test_subscribe_to_closed_tab @116-122
- async-function test_params_user_context_invalid_type @126-128
- async-function test_params_user_context_empty @131-133
- async-function test_params_user_context_value_invalid_type @137-139
- async-function test_params_user_context_value_invalid_value @142-144
- async-function test_params_user_context_and_contexts @147-149
- async-function test_subscribe_to_closed_user_context @152-158

### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/subscription_id.py

Blob: `d0e869e52d7e2c9dac1e2b3aacf3fb7ab6ddbfb8`. Parse: parsed.

- import pytest @1
- import uuid @2
- async-function test_subscribe_subscription_id @7-10
- async-function test_subscribe_twice @13-17

### testing/web-platform/tests/webdriver/tests/bidi/session/subscribe/user_contexts.py

Blob: `ae2f574eca5a696b3b3646dae784743c0d18f695`. Parse: parsed.

- import pytest @1
- from ... import create_console_api_message,recursive_compare @3
- async-function test_subscribe_one_user_context @8-34
- async-function test_subscribe_default_user_context @37-63
- async-function test_subscribe_multiple_user_contexts @66-85
- async-function test_buffered_event @88-115
- async-function test_subscribe_to_user_context_and_then_globally @118-189
- async-function test_subscribe_to_user_context_and_then_to_browsing_context @192-264
- async-function test_subscribe_globally_and_then_to_user_context @267-308
- async-function test_subscribe_to_browsing_context_and_then_to_user_context @311-373

### testing/web-platform/tests/webdriver/tests/bidi/session/unsubscribe/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/session/unsubscribe/events.py

Blob: `f8072b544e9e9308073bbb808f6ec1c7a9734bcd`. Parse: parsed.

- import pytest @1
- from webdriver.error import TimeoutException @2
- async-function test_unsubscribe_from_module @11-36
- async-function test_unsubscribe_from_module.on_event @18-19
- async-function test_subscribe_to_module_unsubscribe_from_one_event @39-76
- async-function test_subscribe_to_module_unsubscribe_from_one_event.on_event @51-52

### testing/web-platform/tests/webdriver/tests/bidi/session/unsubscribe/invalid.py

Blob: `5024086fc234c4c856354f3d0e75526ffff679df`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.error import InvalidArgumentException @3
- from ... import create_console_api_message @5
- async-function test_params_empty @10-12
- async-function test_params_events_invalid_type @16-18
- async-function test_params_events_empty @21-23
- async-function test_params_events_value_invalid_type @27-29
- async-function test_params_events_value_invalid_event_name @33-35
- async-function test_params_events_value_valid_and_invalid_event_name @38-67
- async-function test_params_events_value_valid_and_invalid_event_name.on_event @55-56
- async-function test_unsubscribe_from_one_event_and_then_from_module @70-84
- async-function test_params_unsubscribe_globally_without_subscription @87-89
- async-function test_params_unsubscribe_globally_with_individual_subscription @92-100
- async-function test_params_subscriptions_invalid_type @104-106
- async-function test_params_subscriptions_entry_invalid_type @110-112
- async-function test_params_subscriptions_invalid_value @116-118
- async-function test_unsubscribe_with_subscription_id_twice @121-128

### testing/web-platform/tests/webdriver/tests/bidi/session/unsubscribe/subscriptions.py

Blob: `6fea9f4dac034bd9bc6641c802b7d1f5ff73b072`. Parse: parsed.

- import pytest @1
- from ... import create_console_api_message,recursive_compare @3
- async-function test_unsubscribe_with_subscription_id @8-22
- async-function test_unsubscribe_with_multiple_subscription_ids @25-62
- async-function test_unsubscribe_with_multiple_subscription_ids.on_event @42-43
- async-function test_unsubscribe_from_one_of_the_context @65-96
- async-function test_unsubscribe_from_closed_context @99-109
- async-function test_subscribe_twice_to_context_and_unsubscribe_once @112-139
- async-function test_subscribe_twice_to_globally_and_unsubscribe_once @142-165
- async-function test_unsubscribe_partially_from_one_event @168-215
- async-function test_unsubscribe_partially_from_one_event.on_domContentLoaded_event @180-181
- async-function test_unsubscribe_partially_from_one_event.on_load_event @183-184
- async-function test_unsubscribe_with_event_and_subscriptions @218-249
- async-function test_unsubscribe_with_event_and_subscriptions.on_event @230-231
- async-function test_unsubscribe_globally_with_one_context_subscription @252-283
- async-function test_unsubscribe_from_one_context_with_global_subscription @286-317
- async-function test_unsubscribe_globally_with_user_context_subscription @320-356
- async-function test_unsubscribe_globally_with_user_context_and_context_subscription @359-401
- async-function test_unsubscribe_from_user_context_with_global_subscription @404-442
- async-function test_unsubscribe_from_user_context @445-466
- async-function test_unsubscribe_from_user_context_twice @469-504
- async-function test_unsubscribe_from_user_context_with_context_subscription @507-547
- async-function test_unsubscribe_from_context_with_user_context_subscription @550-590

### testing/web-platform/tests/webdriver/tests/bidi/storage/__init__.py

Blob: `52770d76d0e65a43fb6cc8882839e6223116c9af`. Parse: parsed.

- from datetime import datetime,timedelta,timezone @1
- from typing import Optional @2
- from webdriver.bidi.modules.network import NetworkBytesValue,NetworkStringValue @3
- from webdriver.bidi.modules.storage import PartialCookie,PartitionDescriptor,BrowsingContextPartitionDescriptor @4
- from .. import any_int,recursive_compare @5
- async-function assert_cookie_is_not_set @11-17
- async-function assert_cookie_is_set @20-52
- function create_cookie @55-76
- function generate_expiry_date @79-84
- function format_expiry_string @87-90
- async-function get_default_partition_key @93-98
- async-function assert_partition_key @101-106

### testing/web-platform/tests/webdriver/tests/bidi/storage/delete_cookies/__init__.py

Blob: `4b73b0bcedf401f9af495d853e943501f81cce7e`. Parse: parsed.

- async-function assert_cookies_are_not_present @1-3

### testing/web-platform/tests/webdriver/tests/bidi/storage/delete_cookies/filter.py

Blob: `0eac3238bd1b9f65420f4f8fe007f5e1cdfbacbf`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.network import NetworkBase64Value,NetworkStringValue @2
- from webdriver.bidi.modules.storage import CookieFilter @3
- from . import assert_cookies_are_not_present @5
- from .. import assert_cookie_is_set,assert_partition_key,create_cookie,format_expiry_string,generate_expiry_date @6
- async-function test_filter @25-68
- async-function test_filter_domain @71-117
- async-function test_filter_expiry @127-197
- async-function test_filter_name @200-241
- async-function test_filter_same_site @254-311
- async-function test_filter_secure @318-375
- async-function test_filter_path @386-442
- async-function test_filter_http_only @449-511

### testing/web-platform/tests/webdriver/tests/bidi/storage/delete_cookies/invalid.py

Blob: `ba9c5a5da0ab510473afef3e860eedf71d7676a7`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.network import NetworkBase64Value,NetworkStringValue @4
- from webdriver.bidi.modules.storage import BrowsingContextPartitionDescriptor,CookieFilter,StorageKeyPartitionDescriptor @5
- async-function test_params_filter_invalid_type @15-17
- async-function test_params_filter_domain_invalid_type @21-23
- async-function test_params_filter_expiry_invalid_type @27-29
- async-function test_params_filter_http_only_invalid_type @33-35
- async-function test_params_filter_name_invalid_type @39-41
- async-function test_params_filter_path_invalid_type @45-47
- async-function test_params_filter_same_site_invalid_type @51-53
- async-function test_params_filter_same_site_invalid_value @57-59
- async-function test_params_filter_secure_invalid_type @63-65
- async-function test_params_filter_size_invalid_type @69-71
- async-function test_params_filter_value_invalid_type @75-77
- async-function test_params_filter_value_type_invalid_type @81-85
- async-function test_params_filter_value_type_invalid_value @88-92
- async-function test_params_filter_value_base64_type_invalid_type @96-100
- async-function test_params_filter_value_string_type_invalid_type @104-108
- async-function test_params_partition_invalid_type @112-114
- async-function test_params_partition_type_invalid_type @118-120
- async-function test_params_partition_type_invalid_value @123-125
- async-function test_params_partition_context_invalid_type @129-133
- async-function test_partition_invalid_context @136-140
- async-function test_params_partition_source_origin_invalid_type @144-148
- async-function test_params_partition_user_context_invalid_type @152-156
- async-function test_params_partition_user_context_invalid_value @159-163

### testing/web-platform/tests/webdriver/tests/bidi/storage/delete_cookies/partition.py

Blob: `b1b2d4a5dd1c9eb1aea13c6ff813c0abd0abfeab`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.network import NetworkStringValue @3
- from webdriver.bidi.modules.storage import BrowsingContextPartitionDescriptor,PartialCookie,StorageKeyPartitionDescriptor @4
- from . import assert_cookies_are_not_present @10
- from .. import assert_cookie_is_set,create_cookie,assert_partition_key @11
- async-function test_default_partition @21-67
- async-function test_partition_context @75-106
- async-function test_partition_context_iframe @110-136
- async-function test_partition_source_origin @146-212
- async-function test_partition_user_context @220-304

### testing/web-platform/tests/webdriver/tests/bidi/storage/get_cookies/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### testing/web-platform/tests/webdriver/tests/bidi/storage/get_cookies/filter.py

Blob: `c0e4673918ddc0e7ed1b413ec6dbc5fac1cf4804`. Parse: parsed.

- import pytest @1
- from webdriver.bidi.modules.network import NetworkBase64Value,NetworkStringValue @2
- from webdriver.bidi.modules.storage import CookieFilter @3
- from .. import assert_partition_key,create_cookie,format_expiry_string,generate_expiry_date @5
- from ... import recursive_compare @6
- async-function test_filter @19-69
- async-function test_filter_domain @72-134
- async-function test_filter_expiry @144-227
- async-function test_filter_name @230-263
- async-function test_filter_same_site @279-342
- async-function test_filter_secure @349-412
- async-function test_filter_path @423-491
- async-function test_filter_http_only @498-570

### testing/web-platform/tests/webdriver/tests/bidi/storage/get_cookies/invalid.py

Blob: `93d0da2ac472a7b406138198c70f9264033403ed`. Parse: parsed.

- import pytest @1
- import webdriver.bidi.error @2
- from webdriver.bidi.modules.network import NetworkBase64Value,NetworkStringValue @3
- from webdriver.bidi.modules.storage import BrowsingContextPartitionDescriptor,CookieFilter,StorageKeyPartitionDescriptor @4
- async-function test_params_filter_invalid_type @14-16
- async-function test_params_filter_domain_invalid_type @20-22
- async-function test_params_filter_expiry_invalid_type @26-28
- async-function test_params_filter_http_only_invalid_type @32-34
- async-function test_params_filter_name_invalid_type @38-40
- async-function test_params_filter_path_invalid_type @44-46
- async-function test_params_filter_same_site_invalid_type @50-52
- async-function test_params_filter_same_site_invalid_value @56-58
- async-function test_params_filter_secure_invalid_type @62-64
- async-function test_params_filter_size_invalid_type @68-70
- async-function test_params_filter_value_invalid_type @74-76
- async-function test_params_filter_value_type_invalid_type @80-84
- async-function test_params_filter_value_type_invalid_value @87-91
- async-function test_params_filter_value_base64_type_invalid_type @95-99
- async-function test_params_filter_value_string_type_invalid_type @103-107
- async-function test_params_partition_invalid_type @111-113
- async-function test_params_partition_type_invalid_type @117-119
- async-function test_params_partition_type_invalid_value @122-124
- async-function test_params_partition_context_invalid_type @128-132
- async-function test_partition_invalid_context @135-139
- async-function test_params_partition_source_origin_invalid_type @143-147
- async-function test_params_partition_user_context_invalid_type @151-155
- async-function test_params_partition_user_context_invalid_value @158-162

## Validation and limits

The parser checked syntax only. This pass cannot prove runtime contracts, ownership, selected build settings, executed branches, or design reasons. Build files use a Python-based domain-specific language; parsing them as Python does not validate the build system. Byte decoding uses UTF-8; special encoding declarations and intentionally invalid fixtures may fail.

## Retrieval correction

This copy preserves the source map in [84994754-8468-4e64-a39d-66919533b006.md](84994754-8468-4e64-a39d-66919533b006.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `54f7b99d26a1b07a6077e5c9a7455010e881ef20d2c81f9d44dddd5f11afbaab`.
