<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_connection_state.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_network_runtimes.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_connect.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_refresh.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_select.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_status.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_unavailable_runtime.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_unplugged_device.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_favicons.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_navigate.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_zombietab.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_targets_sorted.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_basic.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_connection_attempt.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_inspect.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_navigate.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_actions.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_connected_details.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates_multi.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates_network.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox_runtime_info.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox_worker_inspection.js","devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_workers_remote_runtime.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_connect.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_extension.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_profiler.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_serviceworker.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_tabs.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_console.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_debugger.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_inspector.js","devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_netmonitor.js","devtools/client/aboutdebugging/test/browser/head.js","devtools/client/aboutdebugging/test/browser/helper-adb.js","devtools/client/aboutdebugging/test/browser/helper-addons.js","devtools/client/aboutdebugging/test/browser/helper-backward-compat.js","devtools/client/aboutdebugging/test/browser/helper-collapsibilities.js","devtools/client/aboutdebugging/test/browser/helper-mocks.js","devtools/client/aboutdebugging/test/browser/helper-real-usb.js","devtools/client/aboutdebugging/test/browser/helper-serviceworker.js","devtools/client/aboutdebugging/test/browser/mocks/helper-adb-mock.js","devtools/client/aboutdebugging/test/browser/mocks/helper-client-wrapper-mock.js","devtools/client/aboutdebugging/test/browser/mocks/helper-runtime-client-factory-mock.js","devtools/client/aboutdebugging/test/browser/resources/backward-compat/debugger.js","devtools/client/aboutdebugging/test/browser/resources/backward-compat/sw.js","devtools/client/aboutdebugging/test/browser/resources/script_aboutdebugging_devtoolstoolbox_breakpoint.js","devtools/client/aboutdebugging/test/browser/resources/service-workers/controlled-sw.worker.js","devtools/client/aboutdebugging/test/browser/resources/service-workers/empty-sw.worker.js","devtools/client/aboutdebugging/test/browser/resources/service-workers/fetch-sw.worker.js","devtools/client/aboutdebugging/test/browser/resources/service-workers/push-sw.worker.js","devtools/client/aboutdebugging/test/browser/resources/test-temporary-extension/script.js","devtools/client/aboutdebugging/test/node/babel.config.js","devtools/client/aboutdebugging/test/node/components/shared-message.test.js","devtools/client/aboutdebugging/test/node/jest.config.js","devtools/client/aboutdebugging/test/node/setup.js","devtools/client/aboutdebugging/test/xpcshell/test_extensions_path.js","devtools/client/aboutdebugging/test/xpcshell/test_runtime_default_preferences.js","devtools/client/aboutdebugging/test/xpcshell/xpcshell-head.js","devtools/client/accessibility/accessibility-proxy.js","devtools/client/accessibility/accessibility-view.js","devtools/client/accessibility/actions/accessibles.js","devtools/client/accessibility/actions/audit.js","devtools/client/accessibility/actions/details.js","devtools/client/accessibility/actions/simulation.js","devtools/client/accessibility/actions/ui.js","devtools/client/accessibility/components/AccessibilityPrefs.js","devtools/client/accessibility/components/AccessibilityRow.js","devtools/client/accessibility/components/AccessibilityRowValue.js","devtools/client/accessibility/components/AccessibilityTree.js","devtools/client/accessibility/components/AccessibilityTreeFilter.js","devtools/client/accessibility/components/Accessible.js","devtools/client/accessibility/components/AuditController.js","devtools/client/accessibility/components/AuditFilter.js","devtools/client/accessibility/components/AuditProgressOverlay.js","devtools/client/accessibility/components/Badge.js","devtools/client/accessibility/components/Badges.js","devtools/client/accessibility/components/Check.js","devtools/client/accessibility/components/Checks.js","devtools/client/accessibility/components/ColorContrastAccessibility.js","devtools/client/accessibility/components/ContrastBadge.js","devtools/client/accessibility/components/Description.js","devtools/client/accessibility/components/DisplayTabbingOrder.js","devtools/client/accessibility/components/KeyboardBadge.js","devtools/client/accessibility/components/KeyboardCheck.js","devtools/client/accessibility/components/LearnMoreLink.js","devtools/client/accessibility/components/MainFrame.js","devtools/client/accessibility/components/RightSidebar.js","devtools/client/accessibility/components/SimulationMenuButton.js","devtools/client/accessibility/components/TextLabelBadge.js","devtools/client/accessibility/components/TextLabelCheck.js","devtools/client/accessibility/components/Toolbar.js","devtools/client/accessibility/constants.js","devtools/client/accessibility/main.js","devtools/client/accessibility/panel.js","devtools/client/accessibility/picker.js","devtools/client/accessibility/provider.js","devtools/client/accessibility/reducers/accessibles.js","devtools/client/accessibility/reducers/audit.js","devtools/client/accessibility/reducers/details.js","devtools/client/accessibility/reducers/index.js","devtools/client/accessibility/reducers/simulation.js","devtools/client/accessibility/reducers/ui.js","devtools/client/accessibility/test/browser/browser_accessibility.js","devtools/client/accessibility/test/browser/browser_accessibility_context_menu_browser.js","devtools/client/accessibility/test/browser/browser_accessibility_context_menu_inspector.js","devtools/client/accessibility/test/browser/browser_accessibility_fission_switch_target.js","devtools/client/accessibility/test/browser/browser_accessibility_mutations.js","devtools/client/accessibility/test/browser/browser_accessibility_panel_audit_hidden_iframe.js","devtools/client/accessibility/test/browser/browser_accessibility_panel_audit_oop.js","devtools/client/accessibility/test/browser/browser_accessibility_panel_toolbar_checks.js","devtools/client/accessibility/test/browser/browser_accessibility_panel_toolbar_pref_scroll.js","devtools/client/accessibility/test/browser/browser_accessibility_print_to_json.js","devtools/client/accessibility/test/browser/browser_accessibility_relation_navigation.js","devtools/client/accessibility/test/browser/browser_accessibility_reload.js","devtools/client/accessibility/test/browser/browser_accessibility_sidebar.js","devtools/client/accessibility/test/browser/browser_accessibility_sidebar_checks.js","devtools/client/accessibility/test/browser/browser_accessibility_sidebar_dom_nodes.js","devtools/client/accessibility/test/browser/browser_accessibility_simulation.js","devtools/client/accessibility/test/browser/browser_accessibility_tabbing_order_highlighter.js","devtools/client/accessibility/test/browser/browser_accessibility_tabbing_order_highlighter_iframe_picker.js","devtools/client/accessibility/test/browser/browser_accessibility_tree.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_audit.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_all.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_long.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_reset.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_toolbar.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_contrast.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_iframe_picker.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_navigation.js","devtools/client/accessibility/test/browser/browser_accessibility_tree_navigation_oop.js","devtools/client/accessibility/test/browser/head.js","devtools/client/accessibility/test/chrome/contrast.snapshots.js","devtools/client/accessibility/test/chrome/head.js","devtools/client/accessibility/test/node/babel.config.js","devtools/client/accessibility/test/node/components/accessibility-prefs.test.js","devtools/client/accessibility/test/node/components/accessibility-tree-filter.test.js","devtools/client/accessibility/test/node/components/audit-controller.test.js","devtools/client/accessibility/test/node/components/audit-filter.test.js","devtools/client/accessibility/test/node/components/audit-progress-overlay.test.js","devtools/client/accessibility/test/node/components/badge.test.js","devtools/client/accessibility/test/node/components/badges.test.js","devtools/client/accessibility/test/node/components/check.test.js","devtools/client/accessibility/test/node/components/contrast-badge.test.js","devtools/client/accessibility/test/node/components/display-tabbing-order.test.js","devtools/client/accessibility/test/node/components/keyboard-badge.test.js","devtools/client/accessibility/test/node/components/keyboard-check.test.js","devtools/client/accessibility/test/node/components/text-label-badge.test.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/devtools JavaScript function map 86

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_connection_state.js

Blob: `757f59689188b3531fbaab86e6ebff8e895bd30e`. Role: test-path,source. Parse: module.

- (anonymous) @18-102; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @42-44; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @58-61; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @66-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-174; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @133-136; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @140-141; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @164-164; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupPreferences @176-192; FunctionDeclaration; parameters=0; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_network_runtimes.js

Blob: `5af8a7613739ddc3ca67da4048bd3b82024ecfaa`. Role: test-path,source. Parse: module.

- (anonymous) @12-39; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime.js

Blob: `b63b7ae08ec0b2a290ffb0d0b7ea9d740c04c61e`. Role: test-path,source. Parse: module.

- (anonymous) @11-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_connect.js

Blob: `f4978b0495d8df0bf774c769a1b211e51b13e80c`. Role: test-path,source. Parse: module.

- (anonymous) @14-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_refresh.js

Blob: `b94c57a35a9a4a333006e49ae17ef0fdc8e6c756`. Role: test-path,source. Parse: module.

- (anonymous) @14-50; FunctionExpression; parameters=0; async=true; generator=false
- mocks.adbMock.adb.updateRuntimes @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-40; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_runtime_select.js

Blob: `66ca219bf34b58fff0d8045ab5b639a12d6ab931`. Role: test-path,source. Parse: module.

- (anonymous) @10-44; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_status.js

Blob: `e67cde31bb7c7c4cb3e9c726a07801331961d1a1`. Role: test-path,source. Parse: module.

- (anonymous) @14-50; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-47; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_unavailable_runtime.js

Blob: `e073939b6d78fae31f27bba59a1ee417266648bc`. Role: test-path,source. Parse: module.

- (anonymous) @15-65; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-57; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_sidebar_usb_unplugged_device.js

Blob: `5074538a944c58b289ea8f7819d6051638d9ab88`. Role: test-path,source. Parse: module.

- (anonymous) @18-69; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_favicons.js

Blob: `def5c71314ecb228fa6a426fdc6054711cf12ec6`. Role: test-path,source. Parse: module.

- (anonymous) @24-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/ImageTestUtils.sys.mjs @6; ChromeUtils-import-literal

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_navigate.js

Blob: `45355203e330ba651d04f7f34069d3056f460a08`. Role: test-path,source. Parse: module.

- (anonymous) @14-31; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_tab_zombietab.js

Blob: `1243d3374dd0505afe566544b3b66fd8d9f8ac1b`. Role: test-path,source. Parse: module.

- (anonymous) @19-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-94; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkInspectButton @96-103; FunctionDeclaration; parameters=3; async=false; generator=false
- getInspectButton @105-108; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_targets_sorted.js

Blob: `4fc9bb87c0a79afd7342dba3b488e26da2ab0049`. Role: test-path,source. Parse: module.

- (anonymous) @7-111; FunctionExpression; parameters=0; async=true; generator=false
- thisFirefoxClient.listAddons @10-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- thisFirefoxClient.listWorkers @19-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- thisFirefoxClient.listTabs @39-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- retrieveFavicon @44-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- retrieveFavicon @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- retrieveFavicon @56-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- findTargetIndex @63-66; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- assertTargetOrder @68-83; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_basic.js

Blob: `a28143592fa44ac644404f7ae238c53ff709ae14`. Role: test-path,source. Parse: module.

- (anonymous) @9-36; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_connection_attempt.js

Blob: `6b93292bb9c009c372d452fd974072be777e55fd`. Role: test-path,source. Parse: module.

- testSuccessfulConnectionAttempt @21-52; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testFailedConnectionAttempt @54-89; FunctionExpression; parameters=0; async=true; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @57-59; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @71-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @78-83; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testPendingConnectionAttempt @91-157; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @107-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @110-113; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @123-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @128-128; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @139-144; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testCancelledConnectionAttempt @159-202; FunctionExpression; parameters=0; async=true; generator=false
- mocks.runtimeClientFactoryMock.createClientForRuntime @171-173; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @172-172; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-184; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @190-195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setupConnectionAttemptTest @205-237; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @224-224; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeUsbRuntime @239-247; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @243-245; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_inspect.js

Blob: `815ba7fc6a9b68cbda3199c1eabc0907ae078638`. Role: test-path,source. Parse: module.

- (anonymous) @11-63; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_navigate.js

Blob: `02e8abdb7bd51f9d40a4cf9b2b03e3348186f94d`. Role: test-path,source. Parse: module.

- (anonymous) @10-37; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkSelectPageEvent @39-52; FunctionDeclaration; parameters=2; async=false; generator=false
- navigateToUSBRuntime @54-64; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @63-63; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_actions.js

Blob: `07e211f1e9fa84d8371bcca066af519d874cff09`. Role: test-path,source. Parse: module.

- testUsbRuntimeUpdates @14-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-61; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-82; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_connected_details.js

Blob: `bda9c0463959a0e09d31c4e86b2027a29f9dc518`. Role: test-path,source. Parse: module.

- (anonymous) @17-62; FunctionExpression; parameters=0; async=true; generator=false
- usbClient.getDeviceDescription @25-30; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates.js

Blob: `3125bb2974d6bccb0cd2bacc586ec866b71dfb59`. Role: test-path,source. Parse: module.

- assertExtras @41-45; FunctionDeclaration; parameters=2; async=false; generator=false
- testUsbRuntimeUpdates @53-168; FunctionExpression; parameters=0; async=true; generator=false
- addUsbRuntime @170-180; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @179-179; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeUsbRuntime @182-190; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @186-188; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates_multi.js

Blob: `23c37cd7e0696379834a807b08b0844341a4adcf`. Role: test-path,source. Parse: module.

- assertExtras @41-45; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @51-134; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @75-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @78-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @104-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-111; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_telemetry_runtime_updates_network.js

Blob: `af3faa09773daed3ce5e07818da8322a7959be03`. Role: test-path,source. Parse: module.

- assertExtras @15-19; FunctionDeclaration; parameters=2; async=false; generator=false
- testNetworkRuntimeUpdates @24-113; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @89-89; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addNetworkRuntime @115-122; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox.js

Blob: `3d68732bc2c3f4c86126194085b92cd96c96cdb2`. Role: test-path,source. Parse: module.

- testThisFirefoxWithLocalTab @19-29; FunctionExpression; parameters=0; async=true; generator=false
- testThisFirefoxWithoutLocalTab @35-48; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testThisFirefoxKeepDiscardedTab @53-68; FunctionExpression; parameters=0; async=true; generator=false
- testThisFirefoxWithXpinstallDisabled @73-89; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkThisFirefoxTargetPanes @91-124; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @95-96; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @114-114; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox_runtime_info.js

Blob: `2475994fed406ec17024a014193716b26b144423`. Role: test-path,source. Parse: module.

- (anonymous) @11-54; FunctionExpression; parameters=0; async=true; generator=false
- runtimeClientFactoryMock.createClientForRuntime @16-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_thisfirefox_worker_inspection.js

Blob: `4d02c73b1b3c79cef3159519a8736506ad6a3d0d`. Role: test-path,source. Parse: module.

- (anonymous) @6-68; FunctionExpression; parameters=0; async=true; generator=false
- thisFirefoxClient.listWorkers @14-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getWorker @20-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- runtimeClientFactoryMock.createClientForRuntime @26-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_aboutdebugging_workers_remote_runtime.js

Blob: `7f2e594dc1477437722c56baf85acf15dc390c73`. Role: test-path,source. Parse: module.

- (anonymous) @37-83; FunctionExpression; parameters=0; async=true; generator=false
- testWorkerOnMockedRemoteClient @88-160; FunctionDeclaration; parameters=4; async=true; generator=false
- remoteClient.listWorkers @115-115; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-120; ArrowFunctionExpression; parameters=0; async=false; generator=false
- remoteClient.listWorkers @129-129; ArrowFunctionExpression; parameters=0; async=false; generator=false
- retrieveFavicon @139-139; ArrowFunctionExpression; parameters=0; async=false; generator=false
- remoteClient.listTabs @144-144; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @146-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @159-159; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_connect.js

Blob: `3ea1369f1a4850d9ff5803c71b7bb39f7679e993`. Role: test-path,source. Parse: module.

- (anonymous) @15-42; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_extension.js

Blob: `32c3dda2a5643575acdefbe385adfff52a6c58ce`. Role: test-path,source. Parse: module.

- (anonymous) @18-77; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_profiler.js

Blob: `c6ecc68d0513b8601db8a47659ea92494ace2f8d`. Role: test-path,source. Parse: module.

- (anonymous) @27-77; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openProfilerDialog @83-95; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_serviceworker.js

Blob: `951128bd5fb49ec55a53967210c6d63e475cb5b7`. Role: test-path,source. Parse: module.

- (anonymous) @20-49; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_tabs.js

Blob: `0516fcb3ed70fa39772a1a4bd8cdaaf70199aec0`. Role: test-path,source. Parse: module.

- (anonymous) @16-52; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_console.js

Blob: `b941bc28982ecb19c6b7e9b216c8d3c504493612`. Role: test-path,source. Parse: module.

- (anonymous) @16-42; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_debugger.js

Blob: `1f51b6c0054ad3f44877bc5c1628100b21e85d81`. Role: test-path,source. Parse: module.

- (anonymous) @26-69; FunctionExpression; parameters=1; async=true; generator=false
- getMarkedLine @79-88; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @82-82; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_inspector.js

Blob: `e0d4a068da8f3475444cbfa9ad4dd491469e920e`. Role: test-path,source. Parse: module.

- (anonymous) @16-69; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @63-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectNodeOnRemoteTarget @75-86; FunctionDeclaration; parameters=2; async=true; generator=false
- getComputedProperties @93-100; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @95-98; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/browser_backward_compat_toolbox_netmonitor.js

Blob: `c96c505e5daccaff371689207977741f11fe9623`. Role: test-path,source. Parse: module.

- (anonymous) @14-42; FunctionExpression; parameters=1; async=true; generator=false
- getRequests @25-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/head.js

Blob: `4d2fd1c199a46d319213b38ebe40107a85009797`. Role: test-path,source. Parse: module.

- (anonymous) @21-39; FunctionExpression; parameters=0; async=true; generator=false
- openAboutDebugging @41-67; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openAboutDevtoolsToolbox @69-159; FunctionDeclaration; parameters=5; async=true; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @114-121; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-137; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @140-143; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @148-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- closeAboutDevtoolsToolbox @161-197; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @188-188; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @193-193; ArrowFunctionExpression; parameters=0; async=false; generator=false
- closeWebExtAboutDevtoolsToolbox @199-208; FunctionDeclaration; parameters=2; async=true; generator=false
- reloadAboutDebugging @210-226; FunctionDeclaration; parameters=1; async=true; generator=false
- waitForRequestsSuccess @231-237; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForAboutDebuggingRequests @243-273; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @254-259; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @255-258; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectThisFirefoxPage @278-293; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @287-287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectConnectPage @298-304; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @303-303; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectSidebarItemPage @306-312; FunctionDeclaration; parameters=2; async=false; generator=false
- getDebugTargetPane @314-332; FunctionDeclaration; parameters=2; async=false; generator=false
- sanitizeTitle @316-318; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findDebugTargetByText @334-337; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @336-336; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getSidebarItems @339-341; FunctionDeclaration; parameters=1; async=false; generator=false
- findSidebarItemByText @343-348; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @345-347; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findSidebarItemLinkByText @350-355; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @352-354; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isSidebarItemSelected @357-362; FunctionDeclaration; parameters=1; async=false; generator=false
- connectToRuntime @364-377; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @366-366; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @376-376; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForRuntimePage @379-384; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @380-383; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectRuntime @386-397; FunctionDeclaration; parameters=3; async=true; generator=false
- getToolbox @399-401; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @400-400; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openProfilerDialog @407-420; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @408-410; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getThisFirefoxString @426-432; FunctionDeclaration; parameters=1; async=false; generator=false
- waitUntilUsbDeviceIsUnplugged @434-443; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @436-442; ArrowFunctionExpression; parameters=0; async=false; generator=false
- updateSelectedTab @458-478; FunctionDeclaration; parameters=3; async=true; generator=false
- synthesizeUrlKeyInput @490-508; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @494-494; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @500-500; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clickOnAddonWidget @517-534; FunctionDeclaration; parameters=1; async=false; generator=false
- createAddonData @537-555; FunctionDeclaration; parameters=1; async=false; generator=false
- connectToLocalFirefox @557-579; FunctionDeclaration; parameters=1; async=true; generator=false
- disconnect @570-576; ArrowFunctionExpression; parameters=1; async=false; generator=false
- disconnectFromLocalFirefox @582-592; FunctionDeclaration; parameters=1; async=true; generator=false
- assertDebugTargetCollapsed @595-610; FunctionDeclaration; parameters=2; async=true; generator=false
- assertDebugTargetExpanded @613-629; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/helper-adb.js

Blob: `f5e6adfc6b23eefe555f46a4b7e8e859c53e7e50`. Role: test-path,source. Parse: module.

- checkAdbNotRunning @8-20; FunctionDeclaration; parameters=0; async=true; generator=false
- waitForAdbStart @24-37; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @32-36; ArrowFunctionExpression; parameters=0; async=true; generator=false
- stopAdbProcess @42-58; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @53-57; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/helper-addons.js

Blob: `d5c860e3a3f931190f01e2dae7edaa5bab37996f`. Role: test-path,source. Parse: module.

- _getSupportsFile @8-15; FunctionDeclaration; parameters=1; async=false; generator=false
- enableExtensionDebugging @17-20; FunctionDeclaration; parameters=0; async=true; generator=false
- installRegularExtension @26-43; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @30-42; ArrowFunctionExpression; parameters=2; async=false; generator=false
- installTemporaryExtension @50-75; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @59-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @60-67; FunctionExpression; parameters=2; async=false; generator=false
- createTemporaryXPI @78-104; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @102-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- updateTemporaryXPI @113-129; FunctionDeclaration; parameters=2; async=false; generator=false
- installTemporaryExtensionFromXPI @137-148; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @146-146; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeTemporaryExtension @151-164; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @154-157; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @163-163; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeExtension @167-176; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @175-175; ArrowFunctionExpression; parameters=0; async=false; generator=false
- prepareMockFilePicker @179-187; FunctionDeclaration; parameters=1; async=false; generator=false
- promiseBackgroundContextEvent @190-203; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @195-202; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @196-201; FunctionExpression; parameters=2; async=false; generator=false
- promiseBackgroundContextLoaded @205-207; FunctionDeclaration; parameters=1; async=false; generator=false
- promiseBackgroundContextUnloaded @210-212; FunctionDeclaration; parameters=1; async=false; generator=false
- assertBackgroundStatus @215-229; FunctionDeclaration; parameters=2; async=true; generator=false
- getBackgroundStatusElement @220-221; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @223-226; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getExtensionInstance @232-237; FunctionDeclaration; parameters=1; async=false; generator=false
- triggerExtensionEventPageIdleTimeout @240-242; FunctionDeclaration; parameters=1; async=true; generator=false
- wakeupExtensionEventPage @245-247; FunctionDeclaration; parameters=1; async=true; generator=false
- promiseTerminateBackgroundScriptIgnored @250-255; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @252-254; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseBackgroundStatusUpdate @258-263; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://gre/modules/Extension.sys.mjs @51; ChromeUtils-import-literal
- Module resource://testing-common/ExtensionTestCommon.sys.mjs @79; ChromeUtils-import-literal
- Module resource://gre/modules/Extension.sys.mjs @191; ChromeUtils-import-literal

### devtools/client/aboutdebugging/test/browser/helper-backward-compat.js

Blob: `58deae41b8b8d64b6c42189c0b3824eaae6b51fc`. Role: test-path,source. Parse: module.

- getCompatConfig @37-46; FunctionDeclaration; parameters=0; async=true; generator=false
- addCompatTask @57-76; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @58-75; FunctionExpression; parameters=0; async=true; generator=false
- openAboutDebuggingWithCompatServer @90-97; FunctionDeclaration; parameters=2; async=true; generator=false
- runDevToolsServerCommand @111-124; FunctionDeclaration; parameters=3; async=true; generator=false
- openDevToolsServerTab @131-136; FunctionDeclaration; parameters=2; async=true; generator=false
- closeDevToolsServerTab @142-144; FunctionDeclaration; parameters=2; async=true; generator=false
- getCompatFixtureUrl @150-152; FunctionDeclaration; parameters=1; async=false; generator=false
- openCompatToolbox @168-192; FunctionDeclaration; parameters=2; async=true; generator=false
- closeCompatToolbox @198-203; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/aboutdebugging/test/browser/helper-collapsibilities.js

Blob: `e47915fbe234f372e88a243ff5ee751851af8429`. Role: test-path,source. Parse: module.

- prepareCollapsibilitiesTest @34-39; FunctionDeclaration; parameters=0; async=false; generator=false
- toggleCollapsibility @42-51; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-58; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/helper-mocks.js

Blob: `5d47a37bd0aec41ae8b081bc3b455571124e5ff3`. Role: test-path,source. Parse: module.

- constructor @32-78; FunctionExpression; parameters=0; async=false; generator=false
- ?.adbMock.adb.getRuntimes @38-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.adbMock.adb.getDevices @41-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ?.adbMock.adb.updateRuntimes @49-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.adbMock.adb.isProcessStarted @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.runtimeClientFactoryMock.createClientForRuntime @65-67; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- thisFirefoxClient @80-82; FunctionExpression; parameters=0; async=false; generator=false
- enableMocks @84-88; FunctionExpression; parameters=0; async=false; generator=false
- disableMocks @90-98; FunctionExpression; parameters=0; async=false; generator=false
- createNetworkRuntime @100-118; FunctionExpression; parameters=2; async=false; generator=false
- mockNetworkClient.getDeviceDescription @108-114; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeNetworkRuntime @120-127; FunctionExpression; parameters=1; async=false; generator=false
- emitUSBUpdate @129-131; FunctionExpression; parameters=0; async=false; generator=false
- createUSBRuntime @152-192; FunctionExpression; parameters=2; async=false; generator=false
- mockUsbClient.getDeviceDescription @169-176; ArrowFunctionExpression; parameters=0; async=true; generator=false
- mockUsbClient.getDeviceDescription @180-186; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeUSBRuntime @194-197; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @195-195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addDevice @199-204; FunctionExpression; parameters=2; async=false; generator=false
- removeDevice @206-210; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @207-209; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeRuntime @212-218; FunctionExpression; parameters=1; async=false; generator=false
- silenceWorkerUpdates @222-241; FunctionExpression; parameters=0; async=false; generator=false
- WorkersListener @229-234; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addListener @231-231; ArrowFunctionExpression; parameters=0; async=false; generator=false
- removeListener @232-232; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @238-240; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createLocalClientWrapper @244-258; FunctionDeclaration; parameters=0; async=true; generator=false
- setupThisFirefoxMock @263-280; FunctionDeclaration; parameters=0; async=false; generator=false
- runtimeClientFactoryMock.createClientForRuntime @266-271; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @275-277; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class Mocks @31-219

### devtools/client/aboutdebugging/test/browser/helper-real-usb.js

Blob: `dd6c8c263d82fc3e1a2e300a0f1880b106ab933a`. Role: test-path,source. Parse: module.

- getExpectedRuntime @9-12; FunctionDeclaration; parameters=0; async=true; generator=false
- getExpectedRuntimeAll @15-23; FunctionDeclaration; parameters=0; async=true; generator=false
- isAvailable @26-28; FunctionDeclaration; parameters=0; async=false; generator=false
- openAboutDebuggingWithADB @31-49; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _getExpectedRuntimesPath @52-54; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/helper-serviceworker.js

Blob: `316c1ded369e0684f42a1a7caf875c8b1c276537`. Role: test-path,source. Parse: module.

- enableServiceWorkerDebugging @11-21; FunctionDeclaration; parameters=0; async=true; generator=false
- onServiceWorkerMessage @32-51; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @37-49; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-46; FunctionExpression; parameters=1; async=false; generator=false
- _waitForServiceWorkerStatus @54-62; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @55-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForServiceWorkerStopped @65-67; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForServiceWorkerRunning @70-72; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForServiceWorkerRegistering @75-77; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForRegistration @80-88; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @83-86; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @84-86; FunctionExpression; parameters=0; async=true; generator=false
- unregisterServiceWorker @99-110; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @100-109; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/mocks/helper-adb-mock.js

Blob: `f427fb7270ddb60f0edc2df5163a094031003ae3`. Role: test-path,source. Parse: module.

- enableAdbMock @17-22; FunctionDeclaration; parameters=1; async=false; generator=false
- disableAdbMock @28-33; FunctionDeclaration; parameters=0; async=false; generator=false
- createAdbMock @40-71; FunctionDeclaration; parameters=0; async=false; generator=false
- adbMock.registerListener @42-44; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.getRuntimes @46-48; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.getDevices @50-52; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.updateRuntimes @54-56; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.unregisterListener @58-60; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.once @62-64; FunctionExpression; parameters=0; async=false; generator=false
- adbMock.isProcessStarted @66-68; FunctionExpression; parameters=0; async=false; generator=false
- addObserverMock @83-99; FunctionDeclaration; parameters=1; async=false; generator=false
- adbMock.registerListener @88-91; FunctionExpression; parameters=1; async=false; generator=false
- createAdbProcessMock @102-117; FunctionDeclaration; parameters=0; async=false; generator=false
- mock.start @110-114; ArrowFunctionExpression; parameters=0; async=true; generator=false
- enableAdbProcessMock @120-128; FunctionDeclaration; parameters=1; async=false; generator=false
- disableAdbProcessMock @131-136; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/mocks/helper-client-wrapper-mock.js

Blob: `5748904bffe206df08938a0de7ca614f95a8f68b`. Role: test-path,source. Parse: module.

- createClientMock @24-113; FunctionDeclaration; parameters=0; async=false; generator=false
- once @36-38; ArrowFunctionExpression; parameters=2; async=false; generator=false
- on @39-41; ArrowFunctionExpression; parameters=2; async=false; generator=false
- off @42-44; ArrowFunctionExpression; parameters=2; async=false; generator=false
- once @46-48; ArrowFunctionExpression; parameters=2; async=false; generator=false
- on @49-51; ArrowFunctionExpression; parameters=2; async=false; generator=false
- off @52-54; ArrowFunctionExpression; parameters=2; async=false; generator=false
- close @57-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isClosed @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- connect @61-61; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getDeviceDescription @63-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getPreference @65-73; FunctionExpression; parameters=1; async=false; generator=false
- createRootResourceCommand @75-80; ArrowFunctionExpression; parameters=0; async=false; generator=false
- watchResources @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- unwatchResources @78-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- listAddons @82-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- listProcesses @84-84; ArrowFunctionExpression; parameters=0; async=false; generator=false
- listTabs @86-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- listWorkers @88-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getMainProcess @94-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getFront @96-96; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setPreference @98-100; FunctionExpression; parameters=2; async=false; generator=false
- getPerformancePanelUrl @101-101; ArrowFunctionExpression; parameters=0; async=false; generator=false
- loadPerformanceProfiler @102-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkVersionCompatibility @104-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createThisFirefoxClientMock @116-137; FunctionDeclaration; parameters=0; async=false; generator=false
- retrieveFavicon @126-126; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mockThisFirefoxClient.listTabs @133-133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mockThisFirefoxClient.getDeviceDescription @134-134; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/mocks/helper-runtime-client-factory-mock.js

Blob: `23ff8039079a09ae023f4f170c5acde7f5637c42`. Role: test-path,source. Parse: module.

- enableRuntimeClientFactoryMock @14-26; FunctionDeclaration; parameters=1; async=false; generator=false
- mockRuntimeDefaultPreferences @29-49; FunctionExpression; parameters=0; async=false; generator=false
- setDefaultPreferencesIfNeeded @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- disableRuntimeClientFactoryMock @54-61; FunctionDeclaration; parameters=0; async=false; generator=false
- createRuntimeClientFactoryMock @68-75; FunctionDeclaration; parameters=0; async=false; generator=false
- RuntimeClientFactoryMock.createClientForRuntime @70-72; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/backward-compat/debugger.js

Blob: `a4146eb0639b206199a6611fe75b188cc2adfd64`. Role: test-path,source. Parse: module.

- clickMe @10-14; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/backward-compat/sw.js

Blob: `648b7b40692b760461e7b981dc5a6a0bd2189739`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/browser/resources/script_aboutdebugging_devtoolstoolbox_breakpoint.js

Blob: `99401016e455e1708b537512866d0bdccf4c75a9`. Role: test-path,source. Parse: module.

- window.testMethod @8-12; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/service-workers/controlled-sw.worker.js

Blob: `128b9d715529b79a96cc24d89ed59e2d866e9a3c`. Role: test-path,source. Parse: module.

- waitUntil @7-16; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @11-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @20-29; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-36; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/service-workers/empty-sw.worker.js

Blob: `1e7226402c291a8efcc1945957f3f87e147f24cc`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/browser/resources/service-workers/fetch-sw.worker.js

Blob: `8e71e3b10881839290dd6733c1486e06333c0136`. Role: test-path,source. Parse: module.

- self.onfetch @4-6; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/service-workers/push-sw.worker.js

Blob: `3b17457370e48852b0a0ad26945e7d1d6188f28f`. Role: test-path,source. Parse: module.

- postMessage @10-16; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @11-15; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-14; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @24-30; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-28; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-35; FunctionExpression; parameters=1; async=false; generator=false

### devtools/client/aboutdebugging/test/browser/resources/test-temporary-extension/script.js

Blob: `7341583aba56295aa275562b2a012893d15600a3`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/node/babel.config.js

Blob: `f4910810ba3fc39efcc863ba70b841b0da0206dc`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/node/components/shared-message.test.js

Blob: `21a3f44c589bfdd5d13aff631765cd59de71c43f`. Role: test-path,source. Parse: module.

- (anonymous) @22-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @45-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @57-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-68; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/aboutdebugging/test/node/jest.config.js

Blob: `45479fefa8aa274cc60fdd68cb23a6eedb449ebc`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/node/setup.js

Blob: `570e4462ae815927a6bb219e70f98f3f7748c378`. Role: test-path,source. Parse: module.


### devtools/client/aboutdebugging/test/xpcshell/test_extensions_path.js

Blob: `1ec9f0d7c25a609efbad2c561c7e0a87d2198280`. Role: test-path,source. Parse: module.

- testParseFileUri @9-27; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/aboutdebugging/test/xpcshell/test_runtime_default_preferences.js

Blob: `465e11a43bb5aac4555da981cdd13c9ac195d867`. Role: test-path,source. Parse: module.

- test_with_traits @36-68; FunctionExpression; parameters=0; async=true; generator=false
- getTraits @40-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_without_traits_no_error @70-116; FunctionExpression; parameters=0; async=true; generator=false
- getTraits @76-80; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_without_traits_with_error @118-193; FunctionExpression; parameters=0; async=true; generator=false
- getTraits @123-127; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @136-140; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @142-146; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createClientWrapper @195-203; FunctionDeclaration; parameters=1; async=false; generator=false
- getFront @197-199; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/Sinon.sys.mjs @3; ChromeUtils-import-literal

### devtools/client/aboutdebugging/test/xpcshell/xpcshell-head.js

Blob: `733c0400da4ad1efe3a657deb334776046142676`. Role: test-path,source. Parse: module.

- Module resource://devtools/shared/loader/Loader.sys.mjs @8; ChromeUtils-import-literal

### devtools/client/accessibility/accessibility-proxy.js

Blob: `6ce0bacb9074cc9fc8c35a7dcbb7cc0dbb525f99`. Role: source. Parse: module.

- constructor @31-71; FunctionExpression; parameters=2; async=false; generator=false
- enabled @73-75; FunctionExpression; parameters=0; async=false; generator=false
- canBeEnabled @80-82; FunctionExpression; parameters=0; async=false; generator=false
- currentTarget @84-86; FunctionExpression; parameters=0; async=false; generator=false
- audit @100-140; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @114-125; ArrowFunctionExpression; parameters=1; async=true; generator=false
- toggleDisplayTabbingOrder @142-164; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @159-160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- enableAccessibility @166-174; FunctionExpression; parameters=0; async=true; generator=false
- getAccessibilityTreeRoot @183-185; FunctionExpression; parameters=0; async=false; generator=false
- withAllAccessibilityFronts @194-211; FunctionExpression; parameters=1; async=true; generator=false
- withAllAccessibilityWalkerFronts @221-225; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @222-223; ArrowFunctionExpression; parameters=1; async=true; generator=false
- unhighlightBeforeCalling @231-246; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @232-245; ArrowFunctionExpression; parameters=1; async=true; generator=false
- pick @254-277; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @256-275; ArrowFunctionExpression; parameters=1; async=true; generator=false
- cancelPick @282-300; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @285-298; ArrowFunctionExpression; parameters=1; async=true; generator=false
- resetAccessiblity @302-306; FunctionExpression; parameters=0; async=true; generator=false
- startListening @308-315; FunctionExpression; parameters=2; async=false; generator=false
- stopListening @317-324; FunctionExpression; parameters=2; async=false; generator=false
- startListeningForAccessibilityEvents @326-335; FunctionExpression; parameters=1; async=false; generator=false
- stopListeningForAccessibilityEvents @337-346; FunctionExpression; parameters=1; async=false; generator=false
- startListeningForLifecycleEvents @348-350; FunctionExpression; parameters=1; async=false; generator=false
- stopListeningForLifecycleEvents @352-354; FunctionExpression; parameters=1; async=false; generator=false
- startListeningForParentLifecycleEvents @356-361; FunctionExpression; parameters=1; async=false; generator=false
- stopListeningForParentLifecycleEvents @363-368; FunctionExpression; parameters=1; async=false; generator=false
- highlightAccessible @370-389; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @382-388; ArrowFunctionExpression; parameters=1; async=false; generator=false
- unhighlightAccessible @391-408; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @401-407; ArrowFunctionExpression; parameters=1; async=false; generator=false
- initialize @410-429; FunctionExpression; parameters=0; async=true; generator=false
- supports @431-435; FunctionExpression; parameters=0; async=false; generator=false
- destroy @437-453; FunctionExpression; parameters=0; async=false; generator=false
- getEvents @455-459; FunctionExpression; parameters=1; async=false; generator=false
- registerEvent @461-468; FunctionExpression; parameters=3; async=false; generator=false
- unregisterEvent @470-489; FunctionExpression; parameters=3; async=false; generator=false
- onAccessibilityFrontAvailable @491-497; FunctionExpression; parameters=1; async=false; generator=false
- onAccessibilityFrontDestroyed @499-505; FunctionExpression; parameters=1; async=false; generator=false
- onAccessibleWalkerFrontAvailable @507-516; FunctionExpression; parameters=1; async=false; generator=false
- onAccessibleWalkerFrontDestroyed @518-527; FunctionExpression; parameters=1; async=false; generator=false
- onTargetAvailable @529-542; FunctionExpression; parameters=1; async=true; generator=false
- onTargetDestroyed @544-550; FunctionExpression; parameters=1; async=true; generator=false
- onTargetSelected @552-587; FunctionExpression; parameters=1; async=true; generator=false
- ?.simulate @557-557; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @562-562; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityProxy @25-588

### devtools/client/accessibility/accessibility-view.js

Blob: `620975590805c065400f881f96dee40c195ad686`. Role: source. Parse: module.

- constructor @54-61; FunctionExpression; parameters=1; async=false; generator=false
- initialize @124-177; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @172-174; ArrowFunctionExpression; parameters=0; async=false; generator=false
- destroy @179-182; FunctionExpression; parameters=0; async=false; generator=false
- selectAccessible @184-187; FunctionExpression; parameters=1; async=true; generator=false
- highlightAccessible @189-192; FunctionExpression; parameters=1; async=true; generator=false
- selectNodeAccessible @194-253; FunctionExpression; parameters=1; async=true; generator=false
- onMessage @260-267; FunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityView @53-268

### devtools/client/accessibility/actions/accessibles.js

Blob: `0462a25d4917d6ed4f44076e31486015d16833be`. Role: source. Parse: module.

- exports.fetchChildren @19-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-26; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.select @29-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-44; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.highlight @49-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.unhighlight @69-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @70-71; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/actions/audit.js

Blob: `7d91299eea42e33ae47af5b42c599629b5dc2dd2`. Role: source. Parse: module.

- exports.filterToggle @16-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-18; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.auditing @21-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.audit @28-36; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @29-36; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-36; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/actions/details.js

Blob: `2e0d38fd327c86a37c90bfc133724e73f1403ca0`. Role: source. Parse: module.

- exports.updateDetails @16-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-39; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/actions/simulation.js

Blob: `98d69d62f3c104372396a0a264e5cde9b4aaea23`. Role: source. Parse: module.

- exports.simulate @12-16; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @13-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @16-16; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/actions/ui.js

Blob: `d4af5ba8fbb81b9e4ae4eef4481173f4c748ce55`. Role: source. Parse: module.

- exports.reset @20-29; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @21-29; ArrowFunctionExpression; parameters=1; async=true; generator=false
- exports.updateCanBeDisabled @35-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @36-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.updateCanBeEnabled @43-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @44-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.updatePref @48-52; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @49-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exports.enable @58-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @59-66; ArrowFunctionExpression; parameters=1; async=true; generator=false
- exports.updateDisplayTabbingOrder @69-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @70-77; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/components/AccessibilityPrefs.js

Blob: `746d7dce9b5d8c3604b6cc320309201d90f4a822`. Role: source. Parse: module.

- (anonymous) @20-24; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-34; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @53-59; FunctionExpression; parameters=0; async=false; generator=false
- togglePref @61-63; FunctionExpression; parameters=1; async=false; generator=false
- onPrefClick @65-67; FunctionExpression; parameters=1; async=false; generator=false
- onLearnMoreClick @69-71; FunctionExpression; parameters=0; async=false; generator=false
- render @73-101; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @104-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityPrefs @52-102

### devtools/client/accessibility/components/AccessibilityRow.js

Blob: `d5314b63c3b384693c5529f8a4a0640d1643baf2`. Role: source. Parse: module.

- shouldComponentUpdate @76-90; FunctionExpression; parameters=1; async=false; generator=false
- propTypes @98-107; FunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @111-129; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @135-158; FunctionExpression; parameters=1; async=false; generator=false
- scrollIntoView @160-169; FunctionExpression; parameters=0; async=false; generator=false
- update @171-182; FunctionExpression; parameters=0; async=false; generator=false
- flashValue @184-202; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @199-201; ArrowFunctionExpression; parameters=0; async=false; generator=false
- scrollNodeIntoViewIfNeeded @214-241; FunctionExpression; parameters=1; async=true; generator=false
- highlight @243-252; FunctionExpression; parameters=3; async=true; generator=false
- unhighlight @254-257; FunctionExpression; parameters=1; async=false; generator=false
- printToJSON @259-268; FunctionExpression; parameters=0; async=true; generator=false
- onContextMenu @270-290; FunctionExpression; parameters=1; async=false; generator=false
- click @283-283; ArrowFunctionExpression; parameters=0; async=false; generator=false
- render @297-313; FunctionExpression; parameters=0; async=false; generator=false
- onContextMenu @301-301; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onMouseOver @302-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onMouseOut @303-303; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @316-320; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityRow @97-314
- Class HighlightableTreeRowClass @75-91
- Module resource://devtools/client/shared/components/tree/TreeRow.mjs @21; ChromeUtils-import-literal
- Module resource://devtools/client/shared/scroll.mjs @69; ChromeUtils-import-literal

### devtools/client/accessibility/components/AccessibilityRowValue.js

Blob: `f6fba9005585f91c8df3536dbf37530ec253a67b`. Role: source. Parse: module.

- propTypes @30-36; FunctionExpression; parameters=0; async=false; generator=false
- render @38-55; FunctionExpression; parameters=0; async=false; generator=false
- Class AccessibilityRowValue @29-56
- Module resource://devtools/client/shared/components/reps/index.mjs @23; ChromeUtils-import-literal

### devtools/client/accessibility/components/AccessibilityTree.js

Blob: `b203faa2b2a33b4ed3a78bbcba7bfeb098a19dee`. Role: source. Parse: module.

- propTypes @56-71; FunctionExpression; parameters=0; async=false; generator=false
- constructor @73-81; FunctionExpression; parameters=1; async=false; generator=false
- UNSAFE_componentWillMount @87-98; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @100-108; FunctionExpression; parameters=1; async=false; generator=false
- componentWillUnmount @113-124; FunctionExpression; parameters=0; async=false; generator=false
- onReorder @134-138; FunctionExpression; parameters=1; async=false; generator=false
- scrollSelectedRowIntoView @140-157; FunctionExpression; parameters=0; async=false; generator=false
- onNameChange @171-182; FunctionExpression; parameters=2; async=false; generator=false
- onTextChange @193-198; FunctionExpression; parameters=1; async=false; generator=false
- renderValue @200-202; FunctionExpression; parameters=1; async=false; generator=false
- render @207-288; FunctionExpression; parameters=0; async=false; generator=false
- renderRow @232-248; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRowClass @240-242; FunctionExpression; parameters=0; async=false; generator=false
- onClickRow @264-275; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @270-270; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onContextMenuTree @276-286; FunctionExpression; parameters=1; async=false; generator=false
- mapStateToProps @291-301; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityTree @55-289
- Module resource://devtools/client/shared/components/tree/TreeView.mjs @19; ChromeUtils-import-literal
- Module resource://devtools/client/shared/components/reps/index.mjs @24; ChromeUtils-import-literal
- Module resource://devtools/client/shared/scroll.mjs @48; ChromeUtils-import-literal

### devtools/client/accessibility/components/AccessibilityTreeFilter.js

Blob: `540bcb5eb94428e32cd539f431cbf261bd36463c`. Role: source. Parse: module.

- (anonymous) @21-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-30; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-35; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @55-64; FunctionExpression; parameters=0; async=false; generator=false
- toggleFilter @66-80; FunctionExpression; parameters=1; async=true; generator=false
- onClick @82-84; FunctionExpression; parameters=1; async=false; generator=false
- render @86-158; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @113-121; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @132-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-133; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mapStateToProps @161-163; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AccessibilityTreeFilter @54-159

### devtools/client/accessibility/components/Accessible.js

Blob: `03920bf24cc98d6bcb9fe4cfe9fc5093a4686c88`. Role: source. Parse: module.

- propTypes @69-76; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @78-94; FunctionExpression; parameters=1; async=false; generator=false
- flashRow @96-106; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @103-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- render @108-110; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @116-130; FunctionExpression; parameters=0; async=false; generator=false
- constructor @132-144; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @146-151; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @153-182; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @172-173; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @178-179; ArrowFunctionExpression; parameters=1; async=false; generator=false
- componentWillUnmount @184-196; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @192-193; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onAccessibleInspected @198-203; FunctionExpression; parameters=0; async=false; generator=false
- update @205-212; FunctionExpression; parameters=0; async=false; generator=false
- setExpanded @214-224; FunctionExpression; parameters=2; async=false; generator=false
- showHighlighter @226-232; FunctionExpression; parameters=1; async=true; generator=false
- hideHighlighter @234-240; FunctionExpression; parameters=0; async=true; generator=false
- showAccessibleHighlighter @242-245; FunctionExpression; parameters=1; async=false; generator=false
- hideAccessibleHighlighter @247-250; FunctionExpression; parameters=1; async=false; generator=false
- selectNode @252-261; FunctionExpression; parameters=2; async=true; generator=false
- selectAccessible @263-277; FunctionExpression; parameters=1; async=true; generator=false
- openLink @279-281; FunctionExpression; parameters=1; async=false; generator=false
- renderItem @283-357; FunctionExpression; parameters=5; async=false; generator=false
- valueProps.onDOMNodeMouseOut @294-294; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueProps.onDOMNodeMouseOver @295-296; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueProps.onInspectIconClick @301-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueProps.onAccessibleMouseOut @306-307; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueProps.onAccessibleMouseOver @308-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- valueProps.onInspectIconClick @313-316; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @337-355; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @345-349; ArrowFunctionExpression; parameters=1; async=false; generator=false
- render @359-398; FunctionExpression; parameters=0; async=false; generator=false
- getRoots @368-368; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getKey @369-369; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getParent @370-370; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getChildren @371-371; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isExpanded @372-372; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onExpand @373-373; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onCollapse @374-374; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onFocus @375-379; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onActivate @380-386; ArrowFunctionExpression; parameters=1; async=false; generator=false
- findAccessibleTarget @408-420; ArrowFunctionExpression; parameters=2; async=false; generator=false
- findByPath @432-444; ArrowFunctionExpression; parameters=2; async=false; generator=false
- isNodeFront @452-452; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isAccessibleFront @460-460; ArrowFunctionExpression; parameters=1; async=false; generator=false
- translateAccessibleFrontToGrip @471-480; ArrowFunctionExpression; parameters=1; async=false; generator=false
- translateNodeFrontToGripWrapper @482-485; ArrowFunctionExpression; parameters=1; async=false; generator=false
- makeItemsForDetails @494-512; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @495-512; ArrowFunctionExpression; parameters=1; async=false; generator=false
- makeParentMap @514-528; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _traverse @517-524; FunctionDeclaration; parameters=1; async=false; generator=false
- mapStateToProps @530-557; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @541-551; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class Accessible @115-399
- Class AccessiblePropertyClass @68-111
- Module resource://devtools/client/shared/components/reps/index.mjs @50; ChromeUtils-import-literal

### devtools/client/accessibility/components/AuditController.js

Blob: `88adbb6bbe906a46179735eeb0e889296e713b5f`. Role: source. Parse: module.

- propTypes @11-16; FunctionExpression; parameters=0; async=false; generator=false
- constructor @18-29; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @31-35; FunctionExpression; parameters=0; async=false; generator=false
- componentDidUpdate @37-39; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @41-44; FunctionExpression; parameters=0; async=false; generator=false
- onAudited @46-55; FunctionExpression; parameters=0; async=false; generator=false
- maybeRequestAudit @57-76; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- render @78-83; FunctionExpression; parameters=0; async=false; generator=false
- Class AuditController @10-84

### devtools/client/accessibility/components/AuditFilter.js

Blob: `4a6d2ce623f4efb31605515fb70afcf51a7e1c9c`. Role: source. Parse: module.

- validateCheck @26-28; FunctionDeclaration; parameters=1; async=false; generator=false
- propTypes @46-52; FunctionExpression; parameters=0; async=false; generator=false
- isVisible @54-56; FunctionExpression; parameters=1; async=false; generator=false
- shouldHide @58-80; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- render @82-84; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @87-89; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AuditFilter @45-85

### devtools/client/accessibility/components/AuditProgressOverlay.js

Blob: `2fdba7541626b6a615e100731c88c5cc13d57e8b`. Role: source. Parse: module.

- TextProgressBar @24-36; FunctionDeclaration; parameters=1; async=false; generator=false
- propTypes @39-45; FunctionExpression; parameters=0; async=false; generator=false
- render @47-85; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @88-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AuditProgressOverlay @38-86

### devtools/client/accessibility/components/Badge.js

Blob: `dfcedf1d0437df4eb3104c191ca1314ecdbe7b6d`. Role: source. Parse: module.

- propTypes @16-23; FunctionExpression; parameters=0; async=false; generator=false
- render @25-37; FunctionExpression; parameters=0; async=false; generator=false
- Class Badge @15-38

### devtools/client/accessibility/components/Badges.js

Blob: `342cf2f4d166d3d394d1366efd5333e117cf89c1`. Role: source. Parse: module.

- (anonymous) @24-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @30-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getComponentForAuditType @42-50; FunctionDeclaration; parameters=1; async=false; generator=false
- propTypes @53-57; FunctionExpression; parameters=0; async=false; generator=false
- render @59-85; FunctionExpression; parameters=0; async=false; generator=false
- Class Badges @52-86

### devtools/client/accessibility/components/Check.js

Blob: `780c08dfc6bd86e4ec040943e8ff21b827b7ee71`. Role: source. Parse: module.

- Icon @52-59; FunctionDeclaration; parameters=1; async=false; generator=false
- Annotation @70-79; FunctionDeclaration; parameters=1; async=false; generator=false
- propTypes @87-94; FunctionExpression; parameters=0; async=false; generator=false
- render @96-120; FunctionExpression; parameters=0; async=false; generator=false
- Class Check @86-121

### devtools/client/accessibility/components/Checks.js

Blob: `f73500024e11d5386b08fe6d40ecdac3845a27f5`. Role: source. Parse: module.

- EmptyChecks @40-49; FunctionDeclaration; parameters=0; async=false; generator=false
- propTypes @54-59; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-63; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-67; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-71; FunctionExpression; parameters=1; async=false; generator=false
- render @73-105; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @108-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Checks @53-106

### devtools/client/accessibility/components/ColorContrastAccessibility.js

Blob: `81d4bf617c9bbd462a91049534e35a428876bcbe`. Role: source. Parse: module.

- propTypes @33-40; FunctionExpression; parameters=0; async=false; generator=false
- render @42-58; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @68-83; FunctionExpression; parameters=0; async=false; generator=false
- render @85-169; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @177-181; FunctionExpression; parameters=0; async=false; generator=false
- render @183-193; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @199-203; FunctionExpression; parameters=0; async=false; generator=false
- render @205-223; FunctionExpression; parameters=0; async=false; generator=false
- Class ColorContrastCheck @198-224
- Class ContrastAnnotationClass @176-194
- Class ColorContrastAccessibilityClass @67-170
- Class ContrastValueClass @32-59

### devtools/client/accessibility/components/ContrastBadge.js

Blob: `15bf9eee9521056b61f584a4c69fef9f19b422e6`. Role: source. Parse: module.

- (anonymous) @21-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- propTypes @33-38; FunctionExpression; parameters=0; async=false; generator=false
- render @40-52; FunctionExpression; parameters=0; async=false; generator=false
- Class ContrastBadge @32-53

### devtools/client/accessibility/components/Description.js

Blob: `620e53cfeb22c7b5f30cbecb4ea7ca3ff61f0f14`. Role: source. Parse: module.

- Description @32-53; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/accessibility/components/DisplayTabbingOrder.js

Blob: `c3c71859c0f42d2fadfda6424d6f36ff119e1048`. Role: source. Parse: module.

- propTypes @28-33; FunctionExpression; parameters=0; async=false; generator=false
- constructor @35-43; FunctionExpression; parameters=1; async=false; generator=false
- onChange @45-51; FunctionExpression; parameters=0; async=true; generator=false
- render @53-72; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @75-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class DisplayTabbingOrder @27-73

### devtools/client/accessibility/components/KeyboardBadge.js

Blob: `b72b9f6b2297d79de8d1437d61b7a8c5462115f5`. Role: source. Parse: module.

- (anonymous) @24-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- propTypes @35-40; FunctionExpression; parameters=0; async=false; generator=false
- render @42-53; FunctionExpression; parameters=0; async=false; generator=false
- Class KeyboardBadge @34-54

### devtools/client/accessibility/components/KeyboardCheck.js

Blob: `c0cf861766b191cf1fcb5ecc15d9ff9611651ab2`. Role: source. Parse: module.

- code @49-51; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @78-83; FunctionExpression; parameters=0; async=false; generator=false
- render @85-91; FunctionExpression; parameters=0; async=false; generator=false
- getAnnotation @88-88; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class KeyboardCheck @77-92

### devtools/client/accessibility/components/LearnMoreLink.js

Blob: `8e86e1ed6e36b9186a371e1c4113b78ffbc5826e`. Role: source. Parse: module.

- propTypes @25-33; FunctionExpression; parameters=0; async=false; generator=false
- defaultProps @35-42; FunctionExpression; parameters=0; async=false; generator=false
- render @44-62; FunctionExpression; parameters=0; async=false; generator=false
- Class LearnMoreLink @24-63

### devtools/client/accessibility/components/MainFrame.js

Blob: `ea627bd5033105ed0f86e61795171811f7986f49`. Role: source. Parse: module.

- propTypes @63-85; FunctionExpression; parameters=0; async=false; generator=false
- constructor @87-94; FunctionExpression; parameters=1; async=false; generator=false
- componentDidMount @96-109; FunctionExpression; parameters=0; async=false; generator=false
- componentWillUnmount @111-124; FunctionExpression; parameters=0; async=false; generator=false
- resetAccessibility @126-129; FunctionExpression; parameters=0; async=false; generator=false
- onCanBeEnabledChange @131-137; FunctionExpression; parameters=1; async=false; generator=false
- onCanBeDisabledChange @139-141; FunctionExpression; parameters=1; async=false; generator=false
- useLandscapeMode @143-146; FunctionExpression; parameters=0; async=false; generator=false
- onPanelWindowResize @152-156; FunctionExpression; parameters=0; async=false; generator=false
- render @161-231; FunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @234-241; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MainFrame @62-232

### devtools/client/accessibility/components/RightSidebar.js

Blob: `f7120fc356469bd5c71aa6fcf5cb45585c78a22c`. Role: source. Parse: module.

- RightSidebar @28-65; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/accessibility/components/SimulationMenuButton.js

Blob: `af2d90534f2b04e20e36f6d2d4336992aaf0242d`. Role: source. Parse: module.

- (anonymous) @35-39; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-44; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @57-64; FunctionExpression; parameters=0; async=false; generator=false
- constructor @66-70; FunctionExpression; parameters=1; async=false; generator=false
- disableSimulation @72-76; FunctionExpression; parameters=0; async=false; generator=false
- toggleSimulation @78-89; FunctionExpression; parameters=1; async=false; generator=false
- render @91-153; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-96; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @109-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onClick @124-124; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mapStateToProps @156-158; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class SimulationMenuButton @56-154

### devtools/client/accessibility/components/TextLabelBadge.js

Blob: `2bdace5f601926d5dd59fa5dbb27fc761a827b39`. Role: source. Parse: module.

- (anonymous) @24-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- propTypes @36-41; FunctionExpression; parameters=0; async=false; generator=false
- render @43-54; FunctionExpression; parameters=0; async=false; generator=false
- Class TextLabelBadge @35-55

### devtools/client/accessibility/components/TextLabelCheck.js

Blob: `86553b168799424d5535bc30f7d1e8bfae882260`. Role: source. Parse: module.

- code @57-59; FunctionExpression; parameters=0; async=false; generator=false
- div @63-65; FunctionExpression; parameters=0; async=false; generator=false
- span @69-71; FunctionExpression; parameters=0; async=false; generator=false
- code @82-84; FunctionExpression; parameters=0; async=false; generator=false
- code @99-101; FunctionExpression; parameters=0; async=false; generator=false
- code @108-110; FunctionExpression; parameters=0; async=false; generator=false
- span @114-116; FunctionExpression; parameters=0; async=false; generator=false
- code @131-133; FunctionExpression; parameters=0; async=false; generator=false
- span @137-139; FunctionExpression; parameters=0; async=false; generator=false
- code @146-148; FunctionExpression; parameters=0; async=false; generator=false
- code @163-165; FunctionExpression; parameters=0; async=false; generator=false
- span @169-171; FunctionExpression; parameters=0; async=false; generator=false
- code @186-188; FunctionExpression; parameters=0; async=false; generator=false
- span @192-194; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @209-214; FunctionExpression; parameters=0; async=false; generator=false
- render @216-222; FunctionExpression; parameters=0; async=false; generator=false
- getAnnotation @219-219; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class TextLabelCheck @208-223

### devtools/client/accessibility/components/Toolbar.js

Blob: `ad161fd14a0bb2dae31d1b4f154a1fbc19fbaf5c`. Role: source. Parse: module.

- (anonymous) @19-23; FunctionExpression; parameters=0; async=false; generator=false
- Toolbar @32-63; FunctionDeclaration; parameters=1; async=false; generator=false
- mapStateToProps @65-71; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/constants.js

Blob: `0d5d43e7acabe34ea35350df99b8b90b4ad8b0d6`. Role: source. Parse: module.

- Module resource://devtools/shared/mdn.mjs @42; ChromeUtils-import-literal

### devtools/client/accessibility/main.js

Blob: `bbfae3462ae88f05e4f31daafc9a4f2215a332fd`. Role: source. Parse: module.

- Module resource://devtools/shared/loader/browser-loader.sys.mjs @6; ChromeUtils-import-literal

### devtools/client/accessibility/panel.js

Blob: `5c1fa8301bcbca47b029e621be1e5ef696a02636`. Role: source. Parse: module.

- constructor @53-69; FunctionExpression; parameters=3; async=false; generator=false
- open @73-129; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @81-83; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createFluentBundles @135-149; FunctionExpression; parameters=0; async=true; generator=false
- onLifecycleEvent @151-154; FunctionExpression; parameters=0; async=false; generator=false
- onNewAccessibleFrontSelected @156-158; FunctionExpression; parameters=1; async=false; generator=false
- onAccessibilityInspectorUpdated @160-162; FunctionExpression; parameters=0; async=false; generator=false
- forceRefresh @169-179; FunctionExpression; parameters=0; async=true; generator=false
- onPanelVisibilityChange @184-186; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @185-185; ArrowFunctionExpression; parameters=0; async=false; generator=false
- refresh @188-238; FunctionExpression; parameters=0; async=false; generator=false
- updateA11YServiceDurationTimer @240-249; FunctionExpression; parameters=0; async=false; generator=false
- selectAccessible @251-253; FunctionExpression; parameters=1; async=false; generator=false
- selectAccessibleForNode @255-261; FunctionExpression; parameters=2; async=false; generator=false
- highlightAccessible @263-265; FunctionExpression; parameters=1; async=false; generator=false
- postContentMessage @267-275; FunctionExpression; parameters=2; async=false; generator=false
- updatePickerButton @277-279; FunctionExpression; parameters=0; async=false; generator=false
- forceUpdatePickerButton @281-290; FunctionExpression; parameters=0; async=false; generator=false
- togglePicker @292-294; FunctionExpression; parameters=0; async=false; generator=false
- cancelPicker @296-298; FunctionExpression; parameters=0; async=false; generator=false
- stopPicker @300-302; FunctionExpression; parameters=0; async=false; generator=false
- isVisible @307-309; FunctionExpression; parameters=0; async=false; generator=false
- toolbox @311-313; FunctionExpression; parameters=0; async=false; generator=false
- destroy @315-354; FunctionExpression; parameters=0; async=false; generator=false
- Class AccessibilityPanel @45-355

### devtools/client/accessibility/picker.js

Blob: `19d6b6cf5c31e69fe561e8a3a978c16242790759`. Role: source. Parse: module.

- constructor @12-23; FunctionExpression; parameters=1; async=false; generator=false
- toolbox @25-27; FunctionExpression; parameters=0; async=false; generator=false
- accessibilityProxy @29-31; FunctionExpression; parameters=0; async=false; generator=false
- pickerButton @33-35; FunctionExpression; parameters=0; async=false; generator=false
- _telemetry @37-39; FunctionExpression; parameters=0; async=false; generator=false
- release @41-43; FunctionExpression; parameters=0; async=false; generator=false
- emit @45-47; FunctionExpression; parameters=2; async=false; generator=false
- select @55-57; FunctionExpression; parameters=1; async=false; generator=false
- highlight @65-67; FunctionExpression; parameters=1; async=false; generator=false
- getStr @69-71; FunctionExpression; parameters=1; async=false; generator=false
- updateButton @77-84; FunctionExpression; parameters=0; async=false; generator=false
- onPickerAccessibleHovered @92-97; FunctionExpression; parameters=1; async=false; generator=false
- onPickerAccessiblePicked @105-110; FunctionExpression; parameters=1; async=false; generator=false
- onPickerAccessiblePreviewed @118-122; FunctionExpression; parameters=1; async=false; generator=false
- onPickerAccessibleCanceled @127-130; FunctionExpression; parameters=0; async=false; generator=false
- cancel @135-137; FunctionExpression; parameters=0; async=true; generator=false
- stop @142-153; FunctionExpression; parameters=0; async=true; generator=false
- start @161-179; FunctionExpression; parameters=1; async=true; generator=false
- toggle @187-193; FunctionExpression; parameters=1; async=false; generator=false
- Class Picker @11-194

### devtools/client/accessibility/provider.js

Blob: `ede15b239eff77e8282c7842cc0a2d524804236a`. Role: source. Parse: module.

- constructor @20-24; FunctionExpression; parameters=3; async=false; generator=false
- getChildren @33-44; FunctionExpression; parameters=1; async=false; generator=false
- hasChildren @52-54; FunctionExpression; parameters=1; async=false; generator=false
- getValue @64-66; FunctionExpression; parameters=1; async=false; generator=false
- getLabel @75-83; FunctionExpression; parameters=1; async=false; generator=false
- getKey @92-94; FunctionExpression; parameters=1; async=false; generator=false
- getType @103-105; FunctionExpression; parameters=1; async=false; generator=false
- getLevel @120-122; FunctionExpression; parameters=2; async=false; generator=false
- Class Provider @19-123

### devtools/client/accessibility/reducers/accessibles.js

Blob: `ca2b496d12068d807bdf143af48108192546cf9f`. Role: source. Parse: module.

- getInitialState @17-19; FunctionDeclaration; parameters=0; async=false; generator=false
- accessibles @24-38; FunctionDeclaration; parameters=2; async=false; generator=false
- getActorID @40-42; FunctionDeclaration; parameters=1; async=false; generator=false
- cleanupChild @52-64; FunctionDeclaration; parameters=2; async=false; generator=false
- staleChildren @75-82; FunctionDeclaration; parameters=2; async=false; generator=false
- updateChildrenCache @84-104; FunctionDeclaration; parameters=3; async=false; generator=false
- updateAncestry @106-112; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @107-108; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onReceiveChildren @122-136; FunctionDeclaration; parameters=2; async=false; generator=false
- onReceiveAncestry @138-146; FunctionDeclaration; parameters=2; async=false; generator=false
- onAudit @148-159; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @156-156; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/reducers/audit.js

Blob: `1e0461a95979d4275c5e1f1257d503534a8b7450`. Role: source. Parse: module.

- getInitialState @23-34; FunctionDeclaration; parameters=0; async=false; generator=false
- allActiveFilters @39-46; FunctionDeclaration; parameters=0; async=false; generator=false
- audit @48-110; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/reducers/details.js

Blob: `b20a06a44ccbb0f281912473f437f9999f5a0dca`. Role: source. Parse: module.

- getInitialState @14-16; FunctionDeclaration; parameters=0; async=false; generator=false
- details @21-30; FunctionDeclaration; parameters=2; async=false; generator=false
- onUpdateDetails @39-59; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @55-57; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/reducers/index.js

Blob: `d9ca8467ff1c4b56fb28c5b8652ac35001cb8052`. Role: source. Parse: module.


### devtools/client/accessibility/reducers/simulation.js

Blob: `d0cc2b2540304a4a8e38c890e1ae75891508ba63`. Role: source. Parse: module.

- getInitialState @17-25; FunctionDeclaration; parameters=0; async=false; generator=false
- simulation @27-51; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @42-44; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/reducers/ui.js

Blob: `c28de00d90c1d014cdf0a2bb9d6ccbd5204e2525`. Role: source. Parse: module.

- getInitialState @30-45; FunctionDeclaration; parameters=0; async=false; generator=false
- ui @50-77; FunctionDeclaration; parameters=2; async=false; generator=false
- onUpdateDetails @79-87; FunctionDeclaration; parameters=1; async=false; generator=false
- onUnhighlight @89-91; FunctionDeclaration; parameters=1; async=false; generator=false
- updateExpandedNodes @93-102; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @95-99; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onAudit @104-119; FunctionDeclaration; parameters=2; async=false; generator=false
- onHighlight @121-129; FunctionDeclaration; parameters=2; async=false; generator=false
- onSelect @131-141; FunctionDeclaration; parameters=2; async=false; generator=false
- onCanBeDisabledChange @150-152; FunctionDeclaration; parameters=2; async=false; generator=false
- onCanBeEnabledChange @161-163; FunctionDeclaration; parameters=2; async=false; generator=false
- onPrefChange @172-177; FunctionDeclaration; parameters=2; async=false; generator=false
- onReset @186-196; FunctionDeclaration; parameters=2; async=false; generator=false
- onToggle @206-213; FunctionDeclaration; parameters=3; async=false; generator=false
- onUpdateDisplayTabbingOrder @215-222; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://devtools/client/shared/components/tree/TreeView.mjs @23; ChromeUtils-import-literal

### devtools/client/accessibility/test/browser/browser_accessibility.js

Blob: `b87c67fd51c2f1c42aa1486c85f872af0bad23c0`. Role: test-path,source. Parse: module.

- (anonymous) @19-55; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkStartingWithDisabledAccessibilityService @57-92; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkTree @94-105; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_context_menu_browser.js

Blob: `0491b29eb406e521429dd9dac5133ae5cdd4d642`. Role: test-path,source. Parse: module.

- (anonymous) @11-73; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_context_menu_inspector.js

Blob: `03273a30c2d996e6570ace60c97348c899bcc297`. Role: test-path,source. Parse: module.

- openContextMenuForNode @13-28; FunctionDeclaration; parameters=2; async=true; generator=false
- checkShowA11YPropertiesNode @30-39; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkAccessibleObjectSelection @41-73; FunctionDeclaration; parameters=3; async=true; generator=false
- testShowAccessibilityPropertiesContextMenu @78-103; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_fission_switch_target.js

Blob: `9da56a0b1b5d653047ce5a9d4eacc674b0244f92`. Role: test-path,source. Parse: module.

- (anonymous) @42-58; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_mutations.js

Blob: `480369184217024c9cf8e446c2f93502abfeaaac`. Role: test-path,source. Parse: module.

- removeRow @77-100; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @78-99; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @84-94; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @87-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-96; ArrowFunctionExpression; parameters=0; async=false; generator=false
- rename @102-116; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @103-115; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @109-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setup @130-134; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @157-157; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @167-173; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @196-196; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_panel_audit_hidden_iframe.js

Blob: `1e7d0e26c205c0454ceb50941bf337b8b6b36374`. Role: test-path,source. Parse: module.

- setup @46-48; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_panel_audit_oop.js

Blob: `c37dab6ddc9ad505d1489f9ef2a5c83b5fe2bf82`. Role: test-path,source. Parse: module.

- setup @45-47; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @67-69; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_panel_toolbar_checks.js

Blob: `b7d541853b515c703f6233b421ae96be1c1f51d0`. Role: test-path,source. Parse: module.

- setup @34-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @43-45; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @52-54; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @61-63; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @70-72; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @79-81; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @88-90; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @97-99; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_panel_toolbar_pref_scroll.js

Blob: `9f8434f695751e20a042b04cff84909afb71c9fb`. Role: test-path,source. Parse: module.

- setup @41-43; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @53-55; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_print_to_json.js

Blob: `bd7ae57b32348f313ba9ee28960ef62373ed31e6`. Role: test-path,source. Parse: module.

- getMenuItems @8-15; FunctionDeclaration; parameters=1; async=false; generator=false
- newTabSelected @17-26; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @20-22; ArrowFunctionExpression; parameters=0; async=false; generator=false
- parseSnapshotFromTabURI @28-32; FunctionDeclaration; parameters=1; async=false; generator=false
- checkJSONSnapshotForRow @34-60; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @201-256; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_relation_navigation.js

Blob: `4c92091d47740c19bb956e388122f31cdc668a9c`. Role: test-path,source. Parse: module.

- setup @65-65; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @85-85; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @108-146; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_reload.js

Blob: `460b828f129e3c6ad3aefe6f21f0c26193dbaa57`. Role: test-path,source. Parse: module.

- setup @37-37; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @61-65; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @81-84; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_sidebar.js

Blob: `75566c0d1903f4327eee5e4c76254267bbb3902f`. Role: test-path,source. Parse: module.

- setup @52-55; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @53-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setup @70-76; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @71-76; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_sidebar_checks.js

Blob: `f9c0abe8dc1eaab3b72962608bb01a5332634071`. Role: test-path,source. Parse: module.

- setup @34-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @43-47; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @62-65; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_sidebar_dom_nodes.js

Blob: `d7629162890dee30f35c8ffef86d534e0d5dc107`. Role: test-path,source. Parse: module.

- (anonymous) @29-95; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getPropertyItem @98-106; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @101-101; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getPropertyValue @108-111; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_simulation.js

Blob: `5473e31f6fd30cb546b891b89dd0ed0875c4e8e3`. Role: test-path,source. Parse: module.

- setup @48-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @61-63; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @74-76; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @87-91; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @102-104; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tabbing_order_highlighter.js

Blob: `60f8122eae0f0a03802b825271a28b86742c4b83`. Role: test-path,source. Parse: module.

- (anonymous) @19-120; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @92-92; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tabbing_order_highlighter_iframe_picker.js

Blob: `ffa125680401505bda131d1dfad1f3bd1a60eccb`. Role: test-path,source. Parse: module.

- (anonymous) @16-157; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @80-80; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @103-103; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree.js

Blob: `7e0070e603ba43629951c768ab8794bc29f43503`. Role: test-path,source. Parse: module.

- setup @40-40; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @60-60; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_audit.js

Blob: `e2dd61051caf9a390e610b00326cdaabe2c2351e`. Role: test-path,source. Parse: module.

- setup @35-38; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @67-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @90-92; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_all.js

Blob: `cfcaf4fa5676aa0604c1777c2225c6a55ee5093d`. Role: test-path,source. Parse: module.

- (anonymous) @11-30; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_long.js

Blob: `b89789ef49414549a66a6bb92425044ebcca56c7`. Role: test-path,source. Parse: module.

- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @67-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @76-79; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @86-88; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_reset.js

Blob: `aed1ac87a01aa878bb8b7360ba5092ee6b3ba596`. Role: test-path,source. Parse: module.

- setup @47-49; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @68-70; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_audit_toolbar.js

Blob: `da4d962eade31d33cfc2ce13b37c585f49e802a8`. Role: test-path,source. Parse: module.

- setup @48-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @70-72; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_contrast.js

Blob: `8b316b9bfbfd9e888b3fa3c0f48fa312c9f51e20`. Role: test-path,source. Parse: module.

- setup @30-33; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_iframe_picker.js

Blob: `dc146a32d5c3ffe8c17f9102e019c0a5eb7e8801`. Role: test-path,source. Parse: module.

- (anonymous) @37-108; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkTree @110-121; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_navigation.js

Blob: `254a4230141401b538386c658d6c39803360daab`. Role: test-path,source. Parse: module.

- setup @61-61; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @81-81; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @116-116; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @133-133; ArrowFunctionExpression; parameters=1; async=true; generator=false
- setup @163-163; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/accessibility/test/browser/browser_accessibility_tree_navigation_oop.js

Blob: `f661e016a1686c0dcd887514e215b071eb814c95`. Role: test-path,source. Parse: module.

- setup @53-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @70-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setup @102-102; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/accessibility/test/browser/head.js

Blob: `ee59804029daeb4fb350688a3244ee0985aba5b7`. Role: test-path,source. Parse: module.

- waitForAccessibilityShutdown @43-72; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @44-71; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observe @50-60; ArrowFunctionExpression; parameters=3; async=false; generator=false
- shutdownAccessibility @77-80; FunctionDeclaration; parameters=1; async=true; generator=false
- addTestTab @96-128; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @113-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isLinuxOpt @133-144; FunctionDeclaration; parameters=0; async=false; generator=false
- initAccessibilityPanel @154-166; FunctionDeclaration; parameters=1; async=true; generator=false
- compareBadges @177-183; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @181-181; ArrowFunctionExpression; parameters=2; async=false; generator=false
- closestScrolledParent @191-201; FunctionDeclaration; parameters=1; async=false; generator=false
- isVisible @213-223; FunctionDeclaration; parameters=1; async=false; generator=false
- checkSelected @237-247; FunctionDeclaration; parameters=2; async=false; generator=false
- checkLevel @260-266; FunctionDeclaration; parameters=2; async=false; generator=false
- checkTreeState @274-295; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @276-292; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-291; ArrowFunctionExpression; parameters=2; async=false; generator=false
- relationsMatch @306-328; FunctionDeclaration; parameters=2; async=false; generator=false
- parseNumReplacer @341-347; FunctionDeclaration; parameters=2; async=false; generator=false
- checkAuditState @356-378; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @358-377; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkSidebarState @387-414; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @389-413; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkToolbarPrefsState @428-452; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @432-438; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @434-436; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @440-449; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkToolbarState @462-477; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @465-472; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @469-471; ArrowFunctionExpression; parameters=2; async=false; generator=false
- checkSimulationState @489-534; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @494-497; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @510-519; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @525-525; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @530-530; ArrowFunctionExpression; parameters=1; async=false; generator=false
- focusAccessibleProperties @543-552; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @548-548; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectProperty @561-591; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @567-588; ArrowFunctionExpression; parameters=0; async=false; generator=false
- selectRow @599-611; FunctionDeclaration; parameters=2; async=false; generator=false
- toggleRow @619-640; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @635-637; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleMenuItem @654-687; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @671-672; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @684-684; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openSimulationMenu @697-705; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @700-703; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleSimulationOption @715-732; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @724-725; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @730-730; ArrowFunctionExpression; parameters=0; async=false; generator=false
- findAccessibleFor @734-748; FunctionDeclaration; parameters=2; async=true; generator=false
- selectAccessibleForNode @750-757; FunctionDeclaration; parameters=2; async=true; generator=false
- runA11yPanelTests @786-826; FunctionDeclaration; parameters=2; async=true; generator=false
- buildURL @835-852; FunctionDeclaration; parameters=2; async=false; generator=false
- addA11yPanelTestsTask @870-872; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @871-871; ArrowFunctionExpression; parameters=1; async=false; generator=false
- closeTabToolboxAccessibility @883-891; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @890-890; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addA11YPanelTask @902-912; FunctionDeclaration; parameters=4; async=false; generator=false
- a11YPanelTask @903-911; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @134; ChromeUtils-import-literal

### devtools/client/accessibility/test/chrome/contrast.snapshots.js

Blob: `f5eeb5fbb9606439bad2bb98ea583b07884d3195`. Role: test-path,source. Parse: module.


### devtools/client/accessibility/test/chrome/head.js

Blob: `2bd03d53c616a29bc639adda28a04ec89f57a879`. Role: test-path,source. Parse: module.

- window.on @22-22; FunctionExpression; parameters=0; async=false; generator=false
- window.off @23-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://devtools/shared/loader/Loader.sys.mjs @8; ChromeUtils-import-literal
- Module resource://devtools/shared/loader/browser-loader.sys.mjs @11; ChromeUtils-import-literal

### devtools/client/accessibility/test/node/babel.config.js

Blob: `9d227f4c4d83d36a1c10bca240294e4097aeeb31`. Role: test-path,source. Parse: module.


### devtools/client/accessibility/test/node/components/accessibility-prefs.test.js

Blob: `c4990ac33938ac4353349316ace5498dde383cff`. Role: test-path,source. Parse: module.

- checkTogglePrefCheckbox @29-34; FunctionDeclaration; parameters=2; async=false; generator=false
- getMenuItems @36-45; FunctionDeclaration; parameters=2; async=false; generator=false
- checkPrefsState @47-59; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @61-107; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @96-106; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/accessibility-tree-filter.test.js

Blob: `56f09b3d62ef975691f8343b3f0ffe6cd344b6ef`. Role: test-path,source. Parse: module.

- checkToggleFilterCheckbox @34-39; FunctionDeclaration; parameters=2; async=false; generator=false
- getMenuItems @41-50; FunctionDeclaration; parameters=2; async=false; generator=false
- checkFiltersState @52-61; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @63-437; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @100-127; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @129-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-179; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @181-198; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @200-227; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @229-240; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @242-436; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/audit-controller.test.js

Blob: `d84817d68e37e563ebaab2e94430c2ca229e5346`. Role: test-path,source. Parse: module.

- (anonymous) @22-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @53-70; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-90; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/audit-filter.test.js

Blob: `f72ed2f2c3084e8de227ffa1af534083594c20de`. Role: test-path,source. Parse: module.

- (anonymous) @32-153; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @54-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-120; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @122-152; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/audit-progress-overlay.test.js

Blob: `71a6bf54d88756f296c372ec14cb604831374eef`. Role: test-path,source. Parse: module.

- testTextProgressBar @33-53; FunctionDeclaration; parameters=2; async=false; generator=false
- testProgress @55-61; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @63-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-74; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @76-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @84-134; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-147; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/badge.test.js

Blob: `b95ac4478f80f72c8e7a242f29a4fc7496a5a3b5`. Role: test-path,source. Parse: module.

- (anonymous) @21-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-41; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/badges.test.js

Blob: `a7b86e0e92f7afe45dee01574d69b11ea90043bb`. Role: test-path,source. Parse: module.

- (anonymous) @29-114; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @95-113; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/check.test.js

Blob: `7bb3f2c0d9dc185d92454e1c2b182ec405a92b60`. Role: test-path,source. Parse: module.

- (anonymous) @31-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-49; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/contrast-badge.test.js

Blob: `a9ad66cb60c02ba9fe474ac60ea74fa298b0cb9b`. Role: test-path,source. Parse: module.

- (anonymous) @28-96; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @37-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-95; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/display-tabbing-order.test.js

Blob: `e21638423b4954bdcdc06e2c3d4c3f24aa71a9b8`. Role: test-path,source. Parse: module.

- testCheckbox @27-46; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @48-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-90; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/keyboard-badge.test.js

Blob: `6dc3de3818da7799a9c43f9d0e92f86d60abc893`. Role: test-path,source. Parse: module.

- testBadge @27-37; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @39-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-72; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/keyboard-check.test.js

Blob: `33fd3c9e3518c0451a1418b441fe8c9557ef377e`. Role: test-path,source. Parse: module.

- (anonymous) @31-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-45; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/accessibility/test/node/components/text-label-badge.test.js

Blob: `42c46c7871706d90191dc1097b1389ba5b7bf902`. Role: test-path,source. Parse: module.

- testBadge @27-37; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @39-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @74-85; ArrowFunctionExpression; parameters=0; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
