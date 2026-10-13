<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["devtools/client/inspector/test/browser_inspector_navigation.js","devtools/client/inspector/test/browser_inspector_open_on_neterror.js","devtools/client/inspector/test/browser_inspector_pane-toggle-01.js","devtools/client/inspector/test/browser_inspector_pane-toggle-02.js","devtools/client/inspector/test/browser_inspector_pane-toggle-03.js","devtools/client/inspector/test/browser_inspector_pane-toggle-04.js","devtools/client/inspector/test/browser_inspector_pane-toggle-05.js","devtools/client/inspector/test/browser_inspector_pane-toggle-layout-invariant.js","devtools/client/inspector/test/browser_inspector_pane_state_restore.js","devtools/client/inspector/test/browser_inspector_picker-no-page-events.js","devtools/client/inspector/test/browser_inspector_picker-page-reload.js","devtools/client/inspector/test/browser_inspector_picker-reset-reference.js","devtools/client/inspector/test/browser_inspector_picker-shift-key.js","devtools/client/inspector/test/browser_inspector_picker-stop-on-eyedropper.js","devtools/client/inspector/test/browser_inspector_picker-stop-on-tool-change.js","devtools/client/inspector/test/browser_inspector_picker-useragent-widget.js","devtools/client/inspector/test/browser_inspector_picker_video_widget.js","devtools/client/inspector/test/browser_inspector_portrait_mode.js","devtools/client/inspector/test/browser_inspector_pseudoclass-lock.js","devtools/client/inspector/test/browser_inspector_pseudoclass-menu.js","devtools/client/inspector/test/browser_inspector_reload-01.js","devtools/client/inspector/test/browser_inspector_reload-02.js","devtools/client/inspector/test/browser_inspector_reload_iframe.js","devtools/client/inspector/test/browser_inspector_reload_invalid_iframe.js","devtools/client/inspector/test/browser_inspector_reload_missing-iframe-node.js","devtools/client/inspector/test/browser_inspector_reload_nested_iframe.js","devtools/client/inspector/test/browser_inspector_reload_shadow_dom.js","devtools/client/inspector/test/browser_inspector_reload_xul.js","devtools/client/inspector/test/browser_inspector_remove-iframe-during-load.js","devtools/client/inspector/test/browser_inspector_select-last-selected.js","devtools/client/inspector/test/browser_inspector_sidebarstate.js","devtools/client/inspector/test/browser_inspector_split-orientation.js","devtools/client/inspector/test/browser_inspector_startup.js","devtools/client/inspector/test/browser_inspector_switch-to-inspector-on-pick.js","devtools/client/inspector/test/browser_inspector_textbox-menu.js","devtools/client/inspector/test/browser_inspector_textbox-menu_reopen_toolbox.js","devtools/client/inspector/test/browser_inspector_use-in-console-conflict.js","devtools/client/inspector/test/head.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-04.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-05.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-06.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-07.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-08.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-by-type.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cancel.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-comments.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssgrid_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssgrid_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_04.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_05.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_06-scale.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_06-translate.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_07.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_iframe_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_offset-path.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_percent.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-csstransform_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-csstransform_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-custom-element.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-embed.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-clipboard.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-csp.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-events.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-frames.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-image.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-keyboard-shortcut.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-label.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-show-hide.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-xul.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-zoom.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_04.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_05.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_06.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_07.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_hide_on_interaction.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_iframe.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-iframes_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-iframes_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-inline.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_04.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_separate-window.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure-keybinding.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_04.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-options.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-preview.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reduced-motion-message.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reduced-motion.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reload.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_03.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-selector_01.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-selector_02.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-svg-document.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-viewport-size.js","devtools/client/inspector/test/highlighter/browser_inspector_highlighter-zoom.js","devtools/client/inspector/test/highlighter/head.js","devtools/client/inspector/test/search/browser_inspector_search-01.js","devtools/client/inspector/test/search/browser_inspector_search-02.js","devtools/client/inspector/test/search/browser_inspector_search-03.js","devtools/client/inspector/test/search/browser_inspector_search-04.js","devtools/client/inspector/test/search/browser_inspector_search-05.js","devtools/client/inspector/test/search/browser_inspector_search-06.js","devtools/client/inspector/test/search/browser_inspector_search-07.js","devtools/client/inspector/test/search/browser_inspector_search-08.js","devtools/client/inspector/test/search/browser_inspector_search-09.js","devtools/client/inspector/test/search/browser_inspector_search-10.js","devtools/client/inspector/test/search/browser_inspector_search-clear.js","devtools/client/inspector/test/search/browser_inspector_search-filter_context-menu.js","devtools/client/inspector/test/search/browser_inspector_search-label.js","devtools/client/inspector/test/search/browser_inspector_search-navigation.js","devtools/client/inspector/test/search/browser_inspector_search-reserved.js","devtools/client/inspector/test/search/browser_inspector_search-selection.js","devtools/client/inspector/test/search/browser_inspector_search-sidebar.js","devtools/client/inspector/test/search/browser_inspector_search-suggests-ids-and-classes.js","devtools/client/inspector/test/search/browser_inspector_search-suggests-pseudo.js","devtools/client/inspector/test/search/browser_inspector_search_keyboard_shortcut_conflict.js","devtools/client/inspector/test/search/browser_inspector_search_keyboard_trap.js","devtools/client/inspector/test/search/head.js","devtools/client/inspector/test/shared-head.js","devtools/client/inspector/test/sjs_slow-loading-image.sjs","devtools/client/inspector/toolsidebar.js","devtools/client/jsonview/.eslintrc.mjs","devtools/client/jsonview/Converter.sys.mjs","devtools/client/jsonview/Sniffer.sys.mjs","devtools/client/jsonview/components/Headers.mjs","devtools/client/jsonview/components/HeadersPanel.mjs","devtools/client/jsonview/components/HeadersToolbar.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/devtools JavaScript function map 118

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### devtools/client/inspector/test/browser_inspector_navigation.js

Blob: `68f1edc4ca16032b491959b60fa4fdf5f07fe608`. Role: test-path,source. Parse: module.

- (anonymous) @22-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @56-88; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @83-83; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_open_on_neterror.js

Blob: `b294add285c0dcc4873123e7e9448ac151a1d710`. Role: test-path,source. Parse: module.

- (anonymous) @11-44; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-01.js

Blob: `e5335c3e931abf60a368d451a6b8c609c137c98a`. Role: test-path,source. Parse: module.

- (anonymous) @9-36; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-02.js

Blob: `132f0feb7f7d6e67682c971f742afd756663549f`. Role: test-path,source. Parse: module.

- (anonymous) @9-85; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-03.js

Blob: `1522781832efebd1c93e9bc9c970c9329f8d745b`. Role: test-path,source. Parse: module.

- (anonymous) @12-60; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-04.js

Blob: `024fca816b5a00312638452e5b1e9d35aa033768`. Role: test-path,source. Parse: module.

- (anonymous) @9-55; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-05.js

Blob: `3033e76cc1de54f6440bd34ec0794dd062b8caba`. Role: test-path,source. Parse: module.

- (anonymous) @10-43; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-68; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @71-93; FunctionExpression; parameters=0; async=true; generator=false
- toggleSidebar @95-106; ArrowFunctionExpression; parameters=1; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane-toggle-layout-invariant.js

Blob: `1abc7db9759fff5c54b7fe93f7e97631d7319a45`. Role: test-path,source. Parse: module.

- getInvariantRect @11-16; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @12-15; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-32; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_pane_state_restore.js

Blob: `4842efaae43f37d15b1724d1c3a232761d6ff27d`. Role: test-path,source. Parse: module.

- (anonymous) @17-75; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-no-page-events.js

Blob: `5b30aa30c6237ea2e4f6adbbef780f9e97ba3350`. Role: test-path,source. Parse: module.

- triggerPageEvents @31-71; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @35-69; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @43-45; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @51-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @72-98; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-page-reload.js

Blob: `aad50c16e71d2031c108cb96b03e6e92381765bd`. Role: test-path,source. Parse: module.

- waitForIframeLoad @17-36; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @21-23; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @25-35; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @32-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-94; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-reset-reference.js

Blob: `2a9bc39ca6050218e0a3e2f3c7e9a7df2a356065`. Role: test-path,source. Parse: module.

- (anonymous) @13-69; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-shift-key.js

Blob: `163f86edee5a60c1fe2534adbbb066afc8f3906c`. Role: test-path,source. Parse: module.

- (anonymous) @26-143; FunctionExpression; parameters=0; async=true; generator=false
- clickElement @145-153; FunctionDeclaration; parameters=1; async=true; generator=false
- checkElementSelected @155-162; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-stop-on-eyedropper.js

Blob: `bed9e2e82c86db5a15dc8989bb3cc084d40a50e0`. Role: test-path,source. Parse: module.

- (anonymous) @13-46; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_picker-stop-on-tool-change.js

Blob: `e8a5796f49278ba19b61313c521b55a1f6ed532d`. Role: test-path,source. Parse: module.

- (anonymous) @13-27; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_picker-useragent-widget.js

Blob: `11b45e8dca3f8082db6f92995290c0bf415fea97`. Role: test-path,source. Parse: module.

- (anonymous) @16-20; FunctionExpression; parameters=0; async=true; generator=false
- runUserAgentWidgetPickerTest @22-54; FunctionDeclaration; parameters=1; async=true; generator=false
- getShadowHost @65-74; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_picker_video_widget.js

Blob: `0d71988f4cdc6258891257839d81d40bdc96da95`. Role: test-path,source. Parse: module.

- (anonymous) @12-52; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @27-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_portrait_mode.js

Blob: `0d7f2b25fd989ca60d2a1a99253e158083024d15`. Role: test-path,source. Parse: module.

- (anonymous) @10-53; FunctionExpression; parameters=0; async=true; generator=false
- waitForClassMutation @64-77; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @65-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @66-74; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_pseudoclass-lock.js

Blob: `27ff3243a6bb8cc67332ffadcc0af183c756d93a`. Role: test-path,source. Parse: module.

- (anonymous) @21-89; FunctionExpression; parameters=0; async=true; generator=false
- togglePseudoClass @91-106; FunctionDeclaration; parameters=1; async=true; generator=false
- testNavigate @108-130; FunctionDeclaration; parameters=1; async=true; generator=false
- assertPseudoAddedToNode @132-179; FunctionDeclaration; parameters=4; async=true; generator=false
- assertPseudoRemovedFromNode @181-193; FunctionDeclaration; parameters=2; async=true; generator=false
- assertPseudoRemovedFromView @195-218; FunctionDeclaration; parameters=4; async=true; generator=false
- hasPseudoClassLock @227-236; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @231-234; ArrowFunctionExpression; parameters=2; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_pseudoclass-menu.js

Blob: `5ee349aac3a8da6268dfc11709a4ad04b75421b8`. Role: test-path,source. Parse: module.

- (anonymous) @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-75; FunctionExpression; parameters=0; async=true; generator=false
- applyAndVerifyPseudoLock @77-97; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @91-94; ArrowFunctionExpression; parameters=2; async=false; generator=false
- testMenuItems @99-117; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @102-102; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testElementSpecificItems @119-138; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @125-125; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_reload-01.js

Blob: `7adf53ceb33194fac584cbfbcd93cc15b42759dd`. Role: test-path,source. Parse: module.

- (anonymous) @13-30; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_reload-02.js

Blob: `da27805f21c86db0ea10d064c42a3ab1b4e008e9`. Role: test-path,source. Parse: module.

- (anonymous) @25-47; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_reload_iframe.js

Blob: `d3cba528a44c2d6d53e55e26ca1cfe6fdc7469d0`. Role: test-path,source. Parse: module.

- getTestURI @13-26; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @28-84; FunctionExpression; parameters=0; async=true; generator=false
- hasPromiseResolved @86-95; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-93; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_reload_invalid_iframe.js

Blob: `fba10332f95236326d0f815a982876c0ffe58e3b`. Role: test-path,source. Parse: module.

- (anonymous) @12-63; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @16-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-35; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_reload_missing-iframe-node.js

Blob: `d69e061d720e18ce62a985bc35a3003a10207060`. Role: test-path,source. Parse: module.

- (anonymous) @13-58; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-34; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @21-31; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_reload_nested_iframe.js

Blob: `e4617f20ec1d6f8a658c55c4f8db559041c6f4a6`. Role: test-path,source. Parse: module.

- (anonymous) @21-50; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_reload_shadow_dom.js

Blob: `1bcdeb9ff6859787a8c96b3fbfec1e61a66b210f`. Role: test-path,source. Parse: module.

- (anonymous) @36-61; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_reload_xul.js

Blob: `dbbe906a092c514020fc707d61135a31ec628513`. Role: test-path,source. Parse: module.

- (anonymous) @10-13; FunctionExpression; parameters=0; async=true; generator=false
- testToolboxInitialization @15-34; FunctionDeclaration; parameters=3; async=true; generator=false
- testMarkupView @36-48; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_remove-iframe-during-load.js

Blob: `c11957424d755f7f6f5ab8cf33d41fa4df946775`. Role: test-path,source. Parse: module.

- (anonymous) @10-73; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-30; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-48; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-63; FunctionExpression; parameters=0; async=true; generator=false
- contentPageHasNode @75-83; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @79-81; FunctionExpression; parameters=1; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_select-last-selected.js

Blob: `fe56ff5ae7ca77b5ebddd5090b7e22bfe56b1b46`. Role: test-path,source. Parse: module.

- (anonymous) @56-75; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_sidebarstate.js

Blob: `b42874a377bcf2ef5809b58b043df7432ce20afa`. Role: test-path,source. Parse: module.

- (anonymous) @9-64; FunctionExpression; parameters=0; async=true; generator=false
- checkTelemetryResults @66-75; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_split-orientation.js

Blob: `beeb46034458cb47aa0914564783adde063ea290`. Role: test-path,source. Parse: module.

- (anonymous) @12-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openSplitOrientationMenu @87-106; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @94-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForSplitOrientationMenuToClose @108-116; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @110-115; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_startup.js

Blob: `55f4f5301f2a056d508dbc405fd8e121f3e92453`. Role: test-path,source. Parse: module.

- onPageResourceRequest @13-21; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @14-20; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-19; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @36-74; FunctionExpression; parameters=0; async=true; generator=false
- waitForLinkedBrowserEvent @76-78; FunctionDeclaration; parameters=2; async=false; generator=false
- contentReadyState @80-84; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @81-83; FunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_switch-to-inspector-on-pick.js

Blob: `d67a9219f40c688b5949f3d2d17a36002a6a5f73`. Role: test-path,source. Parse: module.

- (anonymous) @11-24; FunctionExpression; parameters=0; async=true; generator=false
- openToolbox @26-29; FunctionDeclaration; parameters=1; async=true; generator=false
- startPickerAndAssertSwitchToInspector @31-39; FunctionDeclaration; parameters=1; async=true; generator=false
- checkResults @41-61; FunctionDeclaration; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_textbox-menu.js

Blob: `c5063007eecd69c0bc2cf4345afdc12d5c628328`. Role: test-path,source. Parse: module.

- (anonymous) @8-78; FunctionExpression; parameters=0; async=true; generator=false
- checkTextBox @80-101; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/inspector/test/browser_inspector_textbox-menu_reopen_toolbox.js

Blob: `ea9025a5aa6044b09c01527f48eb72f8f6e1ef7f`. Role: test-path,source. Parse: module.

- (anonymous) @8-22; FunctionExpression; parameters=0; async=true; generator=false
- checkContextMenuOnSearchbox @24-51; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/browser_inspector_use-in-console-conflict.js

Blob: `8c19a564949ff1d27a6da0bdd3f356198e5b708a`. Role: test-path,source. Parse: module.

- (anonymous) @15-51; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getConsoleResults @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/head.js

Blob: `16dcd346b89b7ed6aaab73298cfe41a420da7f35`. Role: test-path,source. Parse: module.

- (anonymous) @24-38; FunctionExpression; parameters=0; async=false; generator=false
- startPicker @46-57; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @53-55; FunctionExpression; parameters=0; async=true; generator=false
- stopPickerWithEscapeKey @64-68; FunctionExpression; parameters=1; async=true; generator=false
- startEyeDropper @75-79; FunctionExpression; parameters=1; async=true; generator=false
- pickElement @95-108; FunctionDeclaration; parameters=4; async=false; generator=false
- hoverElement @132-177; FunctionDeclaration; parameters=5; async=true; generator=false
- getBrowsingContextForNestedFrame @190-212; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @204-207; FunctionExpression; parameters=1; async=false; generator=false
- selectAndHighlightNode @224-233; FunctionDeclaration; parameters=2; async=true; generator=false
- focusNode @243-250; FunctionDeclaration; parameters=2; async=true; generator=false
- clearCurrentNodeSelection @259-264; FunctionDeclaration; parameters=1; async=false; generator=false
- clickOnInspectMenuItem @272-295; FunctionExpression; parameters=1; async=true; generator=false
- getFrameDocument @307-313; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @312-312; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getShadowRoot @325-331; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @330-330; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getNodeFrontInShadowDom @345-358; FunctionExpression; parameters=3; async=true; generator=false
- focusSearchBoxUsingShortcut @360-374; FunctionExpression; parameters=2; async=true; generator=false
- getContainerForNodeFront @385-387; FunctionDeclaration; parameters=2; async=false; generator=false
- getContainerForSelector @399-415; FunctionExpression; parameters=3; async=true; generator=false
- hoverContainer @427-443; FunctionExpression; parameters=2; async=true; generator=false
- clickContainer @454-472; FunctionExpression; parameters=2; async=true; generator=false
- mouseLeaveMarkupView @481-496; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @493-495; ArrowFunctionExpression; parameters=1; async=false; generator=false
- fireCopyEvent @501-505; FunctionDeclaration; parameters=1; async=false; generator=false
- undoChange @516-526; FunctionDeclaration; parameters=1; async=false; generator=false
- redoChange @537-547; FunctionDeclaration; parameters=1; async=false; generator=false
- getNodeFrontForSelector @553-562; FunctionDeclaration; parameters=2; async=true; generator=false
- poll @574-585; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @581-581; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getHighlighterHelperFor @598-745; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @599-745; FunctionExpression; parameters=1; async=true; generator=false
- prefix @612-614; FunctionExpression; parameters=1; async=false; generator=false
- highlightedNode @616-627; FunctionExpression; parameters=0; async=false; generator=false
- getComputedStyle @622-625; FunctionExpression; parameters=1; async=true; generator=false
- actorID @629-635; FunctionExpression; parameters=0; async=false; generator=false
- show @637-647; FunctionExpression; parameters=3; async=true; generator=false
- hide @649-651; FunctionExpression; parameters=0; async=true; generator=false
- isElementHidden @653-661; FunctionExpression; parameters=1; async=true; generator=false
- getElementTextContent @663-668; FunctionExpression; parameters=1; async=true; generator=false
- getElementAttribute @670-676; FunctionExpression; parameters=2; async=true; generator=false
- waitForElementAttributeSet @678-687; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @679-686; FunctionExpression; parameters=0; async=true; generator=false
- waitForElementAttributeRemoved @689-698; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @690-697; FunctionExpression; parameters=0; async=true; generator=false
- synthesizeMouse @700-715; FunctionExpression; parameters=1; async=true; generator=false
- get @729-736; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @730-736; FunctionExpression; parameters=3; async=true; generator=false
- finalize @740-743; FunctionExpression; parameters=0; async=true; generator=false
- getHighlighterTestHelpers @754-799; FunctionDeclaration; parameters=1; async=false; generator=false
- _waitForHighlighterTypeEvent @766-777; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @767-776; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _handler @768-773; FunctionDeclaration; parameters=1; async=false; generator=false
- getActiveHighlighter @780-782; FunctionExpression; parameters=1; async=false; generator=false
- getNodeForActiveHighlighter @783-785; FunctionExpression; parameters=1; async=false; generator=false
- waitForHighlighterTypeShown @786-788; FunctionExpression; parameters=1; async=false; generator=false
- waitForHighlighterTypeHidden @789-791; FunctionExpression; parameters=1; async=false; generator=false
- waitForHighlighterTypeRestored @792-794; FunctionExpression; parameters=1; async=false; generator=false
- waitForHighlighterTypeDiscarded @795-797; FunctionExpression; parameters=1; async=false; generator=false
- waitForStyleEditor @812-854; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @815-853; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @816-852; ArrowFunctionExpression; parameters=0; async=false; generator=false
- gotEditor @822-843; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @833-836; ArrowFunctionExpression; parameters=1; async=false; generator=false
- containsFocus @863-872; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForTab @880-887; FunctionExpression; parameters=0; async=true; generator=false
- synthesizeKeys @897-901; FunctionDeclaration; parameters=2; async=false; generator=false
- focusAndSendKey @911-914; FunctionDeclaration; parameters=2; async=false; generator=false
- assertTooltipShownOnHover @927-944; FunctionDeclaration; parameters=2; async=true; generator=false
- assertShowPreviewTooltip @957-979; FunctionDeclaration; parameters=2; async=true; generator=false
- assertTooltipHiddenOnMouseOut @990-1004; FunctionDeclaration; parameters=2; async=true; generator=false
- assertTooltipHiddenOnEscape @1014-1020; FunctionDeclaration; parameters=2; async=true; generator=false
- assertVariableTooltipForProperty @1053-1188; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @1072-1079; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getDisplayedNodeTextContent @1198-1211; FunctionDeclaration; parameters=2; async=true; generator=false
- toggleShapesHighlighter @1229-1265; FunctionDeclaration; parameters=5; async=true; generator=false
- toggleContainerByClick @1280-1295; FunctionDeclaration; parameters=3; async=true; generator=false
- simulateColorPickerChange @1305-1313; FunctionDeclaration; parameters=2; async=true; generator=false
- assertMarkupViewAsTree @1337-1347; FunctionDeclaration; parameters=3; async=true; generator=false
- _checkMarkupViewNode @1349-1388; FunctionDeclaration; parameters=3; async=true; generator=false
- _parseMarkupViewTree @1404-1440; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1410-1410; ArrowFunctionExpression; parameters=1; async=false; generator=false
- assertContainerSlotted @1445-1451; FunctionDeclaration; parameters=1; async=false; generator=false
- assertContainerHasText @1457-1463; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForMutation @1465-1467; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForNMutations @1469-1482; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @1472-1481; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onMutation @1473-1480; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1474-1474; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkEyeDropperColorAt @1494-1508; FunctionDeclaration; parameters=5; async=true; generator=false
- deleteNodeWithContextMenu @1519-1546; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @1525-1525; ArrowFunctionExpression; parameters=1; async=false; generator=false
- reflowContentPage @1554-1561; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1555-1560; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1556-1559; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAllAdjustedQuadsForContentPageElement @1570-1607; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @1588-1605; ArrowFunctionExpression; parameters=2; async=false; generator=false
- isNodeCorrectlyHighlighted @1616-1640; FunctionDeclaration; parameters=2; async=true; generator=false
- getAreaRect @1650-1693; FunctionDeclaration; parameters=1; async=true; generator=false
- checkMarkupSearchSuggestions @1707-1744; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @1738-1738; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://devtools/shared/loader/Loader.sys.mjs @1589; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-01.js

Blob: `2cdf530073f43e2d71acf0fc72c5ddb75d9504d6`. Role: test-path,source. Parse: module.

- (anonymous) @9-43; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-02.js

Blob: `c57f1bd0174107261f4ee9f20d82a8006e22d8bb`. Role: test-path,source. Parse: module.

- (anonymous) @11-225; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @151-158; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @153-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @221-224; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getHighlighterInfobarText @227-237; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @228-236; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @231-234; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-03.js

Blob: `711f5da8c5b07c826a5cb7a22bf4c39c34e4fe22`. Role: test-path,source. Parse: module.

- (anonymous) @35-123; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @97-98; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-04.js

Blob: `8d42b3f15c6f45407523304a9a18cbc823d1183d`. Role: test-path,source. Parse: module.

- (anonymous) @31-54; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-05.js

Blob: `4c4fd4781cc895c1c53532a3c469e7c8058e1d75`. Role: test-path,source. Parse: module.

- (anonymous) @28-35; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @31-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-72; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-06.js

Blob: `a68a8fa73615b4eb4b138b67154b78c296a7c988`. Role: test-path,source. Parse: module.

- (anonymous) @12-31; FunctionExpression; parameters=0; async=true; generator=false
- getPageYOffset @33-39; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-07.js

Blob: `cb8c11cdd0df6d0b8b0057959a675eea29fd97fe`. Role: test-path,source. Parse: module.

- debuggerIsPaused @12-14; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForPaused @16-30; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @17-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @23-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-90; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-08.js

Blob: `dc8acfd3a1ba568cfb0ae28d9e5cc5a1c50f3bb2`. Role: test-path,source. Parse: module.

- (anonymous) @9-66; FunctionExpression; parameters=0; async=true; generator=false
- getActiveHighlighter @16-18; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_01.js

Blob: `f0daf4bbe809d638ec9f90092d61c83fbc1c0fb5`. Role: test-path,source. Parse: module.

- (anonymous) @8-36; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_02.js

Blob: `bebc87f593f12b4db3d8ab340d2e93bdc1f56f28`. Role: test-path,source. Parse: module.

- (anonymous) @9-45; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide-config_03.js

Blob: `e90bd87ad02fa4ce0bd17adf94fb411c763c7768`. Role: test-path,source. Parse: module.

- (anonymous) @13-79; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @63-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _handler @64-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module chrome://remote/content/shared/AppInfo.sys.mjs @7; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-autohide.js

Blob: `4d658e77ad14de9ff8d1cf414a0d417cbd08c2bd`. Role: test-path,source. Parse: module.

- (anonymous) @9-77; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @41-43; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-by-type.js

Blob: `5b19d5fb9b9f804447b73b9b42631589795d181c`. Role: test-path,source. Parse: module.

- (anonymous) @16-22; FunctionExpression; parameters=0; async=true; generator=false
- manyInstancesOfCustomHighlighters @24-57; FunctionDeclaration; parameters=1; async=true; generator=false
- showHideMethodsAreAvailable @59-70; FunctionDeclaration; parameters=1; async=true; generator=false
- unknownHighlighterTypeShouldntBeAccepted @72-75; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @12; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cancel.js

Blob: `4502870863c5be8467c34831b2b3fae51fc0e3f3`. Role: test-path,source. Parse: module.

- (anonymous) @42-80; FunctionExpression; parameters=0; async=true; generator=false
- cancelPickerByShortcut @83-88; FunctionDeclaration; parameters=3; async=true; generator=false
- isSelectedMarkupNodeInView @90-94; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-comments.js

Blob: `e599ef41246c0ad947bfef1f7812179410edf808`. Role: test-path,source. Parse: module.

- (anonymous) @11-118; FunctionExpression; parameters=0; async=true; generator=false
- hoverContainer @50-65; FunctionDeclaration; parameters=1; async=false; generator=false
- hoverElement @67-71; FunctionDeclaration; parameters=1; async=true; generator=false
- hoverComment @73-81; FunctionDeclaration; parameters=0; async=false; generator=false
- hoverTextNode @83-92; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @85-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- assertHighlighterShownOn @94-99; FunctionDeclaration; parameters=1; async=true; generator=false
- assertHighlighterShownOnTextNode @101-112; FunctionDeclaration; parameters=2; async=true; generator=false
- assertHighlighterHidden @114-117; FunctionDeclaration; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssgrid_01.js

Blob: `ec75e3997be1d0a42287b19a892c4550ef43d72c`. Role: test-path,source. Parse: module.

- (anonymous) @44-55; FunctionExpression; parameters=0; async=true; generator=false
- isHiddenByDefault @57-66; FunctionDeclaration; parameters=2; async=true; generator=false
- isVisibleWhenShown @68-94; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @39; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssgrid_02.js

Blob: `b58fa13437b876719479a5c81d22c9102ac270a8`. Role: test-path,source. Parse: module.

- (anonymous) @25-54; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @20; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_01.js

Blob: `fa093a4a5cb8b3d460419b77c9e05448900994f4`. Role: test-path,source. Parse: module.

- (anonymous) @34-44; FunctionExpression; parameters=0; async=true; generator=false
- getShapeHidden @46-56; FunctionDeclaration; parameters=2; async=true; generator=false
- isHiddenByDefault @58-72; FunctionDeclaration; parameters=2; async=true; generator=false
- isVisibleWhenShown @74-97; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_02.js

Blob: `615ba39f648125e3e877ef0b758a0159d6171fba`. Role: test-path,source. Parse: module.

- (anonymous) @15-27; FunctionExpression; parameters=0; async=true; generator=false
- polygonHasCorrectAttrs @29-48; FunctionDeclaration; parameters=3; async=true; generator=false
- circleHasCorrectAttrs @50-85; FunctionDeclaration; parameters=3; async=true; generator=false
- ellipseHasCorrectAttrs @87-122; FunctionDeclaration; parameters=3; async=true; generator=false
- insetHasCorrectAttrs @124-159; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_03.js

Blob: `6ee772bfc5b645f6c599e47224ca3e5112109bea`. Role: test-path,source. Parse: module.

- (anonymous) @17-27; FunctionExpression; parameters=0; async=true; generator=false
- testZoomSize @29-61; FunctionDeclaration; parameters=2; async=true; generator=false
- testGeometryBox @63-94; FunctionDeclaration; parameters=1; async=true; generator=false
- testStrokeBox @96-119; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @11; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_04.js

Blob: `586ed32628d83e8e5c2bf9d3e65d8959b0de8335`. Role: test-path,source. Parse: module.

- testPolygon @15-23; FunctionExpression; parameters=0; async=true; generator=false
- testCircle @25-32; FunctionExpression; parameters=0; async=true; generator=false
- testEllipse @34-40; FunctionExpression; parameters=0; async=true; generator=false
- testInset @42-48; FunctionExpression; parameters=0; async=true; generator=false
- taskSetup @50-64; FunctionDeclaration; parameters=0; async=true; generator=false
- getComputedPropertyValue @66-71; FunctionDeclaration; parameters=3; async=true; generator=false
- setup @73-78; FunctionDeclaration; parameters=1; async=true; generator=false
- teardown @80-84; FunctionDeclaration; parameters=1; async=true; generator=false
- testPolygonMovePoint @86-128; FunctionDeclaration; parameters=1; async=true; generator=false
- testPolygonAddPoint @130-195; FunctionDeclaration; parameters=1; async=true; generator=false
- testPolygonRemovePoint @197-253; FunctionDeclaration; parameters=1; async=true; generator=false
- testCircleMoveCenter @255-309; FunctionDeclaration; parameters=1; async=true; generator=false
- testCircleWithoutPosition @311-400; FunctionDeclaration; parameters=1; async=true; generator=false
- testEllipseMoveRadius @402-484; FunctionDeclaration; parameters=1; async=true; generator=false
- testInsetMoveEdges @486-593; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_05.js

Blob: `dc856011eab1df1a01a06277c81ebb47a138d30b`. Role: test-path,source. Parse: module.

- (anonymous) @14-30; FunctionExpression; parameters=0; async=true; generator=false
- setup @32-37; FunctionDeclaration; parameters=1; async=true; generator=false
- teardown @39-43; FunctionDeclaration; parameters=1; async=true; generator=false
- highlightFromRuleView @48-107; FunctionDeclaration; parameters=1; async=true; generator=false
- highlightFromHighlighter @113-161; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @9; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_06-scale.js

Blob: `7c0a42e34f79356eacdf9fbaf283f925eb42007a`. Role: test-path,source. Parse: module.

- (anonymous) @16-31; FunctionExpression; parameters=0; async=true; generator=false
- setup @33-37; FunctionDeclaration; parameters=1; async=true; generator=false
- teardown @39-43; FunctionDeclaration; parameters=1; async=true; generator=false
- testScale @45-153; FunctionDeclaration; parameters=1; async=true; generator=false
- getBoundingBoxInPx @155-190; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @175-179; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_06-translate.js

Blob: `13db6e2a53c266c5ee7d5db2d19d1d37e3a32d45`. Role: test-path,source. Parse: module.

- (anonymous) @16-31; FunctionExpression; parameters=0; async=true; generator=false
- setup @33-37; FunctionDeclaration; parameters=1; async=true; generator=false
- teardown @39-43; FunctionDeclaration; parameters=1; async=true; generator=false
- testTranslate @45-93; FunctionDeclaration; parameters=1; async=true; generator=false
- getBoundingBoxInPx @95-130; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @115-119; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_07.js

Blob: `7205583785e69a189a86a8a9ae378ead5634b527`. Role: test-path,source. Parse: module.

- (anonymous) @16-31; FunctionExpression; parameters=0; async=true; generator=false
- setup @33-37; FunctionDeclaration; parameters=1; async=true; generator=false
- teardown @39-43; FunctionDeclaration; parameters=1; async=true; generator=false
- testOneDimScale @45-146; FunctionDeclaration; parameters=1; async=true; generator=false
- getBoundingBoxInPx @148-183; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @168-172; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_iframe_01.js

Blob: `d84c0871f9c2c952139e77c6e799cad002e24abd`. Role: test-path,source. Parse: module.

- (anonymous) @15-24; FunctionExpression; parameters=0; async=true; generator=false
- testPolygonIframeMovePoint @26-90; FunctionDeclaration; parameters=1; async=true; generator=false
- getClipPathPoint @92-97; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_offset-path.js

Blob: `1736e8eb4a8f413a39667a36480eeb45ec25a2d4`. Role: test-path,source. Parse: module.

- (anonymous) @43-196; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @125-127; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @146-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getShapeHighlighterRect @198-205; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @38; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-cssshape_percent.js

Blob: `72d7acfe4f8a90e3dc3a5f938e8b4c021ab4538c`. Role: test-path,source. Parse: module.

- (anonymous) @16-25; FunctionExpression; parameters=0; async=true; generator=false
- insetHasCorrectAttrs @27-115; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @43-46; ArrowFunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @53-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- floatEq @120-122; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @11; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-csstransform_01.js

Blob: `948064d97b1d852896a0e800e937de2ce2192ec1`. Role: test-path,source. Parse: module.

- (anonymous) @26-46; FunctionExpression; parameters=0; async=true; generator=false
- isHiddenByDefault @48-57; FunctionDeclaration; parameters=2; async=true; generator=false
- has2PolygonsAnd4Lines @59-84; FunctionDeclaration; parameters=2; async=true; generator=false
- isNotShownForUntransformed @86-102; FunctionDeclaration; parameters=3; async=true; generator=false
- isNotShownForInline @104-120; FunctionDeclaration; parameters=3; async=true; generator=false
- isVisibleWhenShown @122-148; FunctionDeclaration; parameters=3; async=true; generator=false
- linesLinkThePolygons @150-231; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @22; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-csstransform_02.js

Blob: `d56b0ebde07a89edd3a66b7b072cb500b8e98c78`. Role: test-path,source. Parse: module.

- (anonymous) @27-70; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-52; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @23; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-custom-element.js

Blob: `8d2450556545676303f6f719a1e025af3656272d`. Role: test-path,source. Parse: module.

- (anonymous) @10-30; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-embed.js

Blob: `5da6d0ac08cba066ea2c2a3526fd709b4bc84baf`. Role: test-path,source. Parse: module.

- (anonymous) @11-24; FunctionExpression; parameters=0; async=true; generator=false
- getEmbeddedBody @26-32; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-clipboard.js

Blob: `37f0015aada2231037c9bfa6a26b1546d50d985a`. Role: test-path,source. Parse: module.

- (anonymous) @16-66; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @8; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-csp.js

Blob: `e8b7074de285c6f43faf0e9f968378d21bc2eeb4`. Role: test-path,source. Parse: module.

- (anonymous) @10-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @34-37; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-events.js

Blob: `deb1b763c33b5e20dcde227501c53f0adb701071`. Role: test-path,source. Parse: module.

- x @66-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- x @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- x @79-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- y @88-88; ArrowFunctionExpression; parameters=2; async=false; generator=false
- y @91-91; ArrowFunctionExpression; parameters=2; async=false; generator=false
- y @101-101; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @107-123; FunctionExpression; parameters=0; async=true; generator=false
- respondsToMoveEvents @125-163; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @133-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkPosition @165-172; FunctionDeclaration; parameters=2; async=true; generator=false
- respondsToReturnAndEscape @174-187; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @8; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-frames.js

Blob: `9b3b2545db7206660a60ea333b4d33480637c29e`. Role: test-path,source. Parse: module.

- (anonymous) @39-93; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkColorAt @53-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @89-92; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-image.js

Blob: `eb38767bf8fe2b451b1412b486f509d5a04dd377`. Role: test-path,source. Parse: module.

- (anonymous) @11-18; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-keyboard-shortcut.js

Blob: `2f37100113f3329b853f5684a9e4e43aedfa2d84`. Role: test-path,source. Parse: module.

- (anonymous) @7-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-36; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-label.js

Blob: `8f0a2f502782e3fb12fac26bed1d441ce5e7f603`. Role: test-path,source. Parse: module.

- getCoordinates @29-31; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @36-38; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @43-45; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @50-52; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @57-59; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @64-66; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getCoordinates @71-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getCoordinates @78-80; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @85-130; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @98-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkLabelPositionAttributes @132-142; FunctionDeclaration; parameters=2; async=true; generator=false
- hasAttribute @144-147; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @10; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-show-hide.js

Blob: `e2a6a0bcbbb6eb073bd43b02ab3d023d6a0a04db`. Role: test-path,source. Parse: module.

- (anonymous) @8-41; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-39; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-xul.js

Blob: `15d380aa7c77d8e853888920ddfc73f6bcb3ba0f`. Role: test-path,source. Parse: module.

- (anonymous) @13-70; FunctionExpression; parameters=0; async=true; generator=false
- isDisabled @72-74; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-eyedropper-zoom.js

Blob: `31bbe63d46881399725ab65213eb92ddfcc76b1e`. Role: test-path,source. Parse: module.

- (anonymous) @31-88; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkColorAt @48-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @83-86; ArrowFunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_01.js

Blob: `a90b7ed42b7c591b33333ea073c1c26602b3b463`. Role: test-path,source. Parse: module.

- (anonymous) @31-45; FunctionExpression; parameters=0; async=true; generator=false
- hasArrowsAndLabelsAndHandlers @47-60; FunctionDeclaration; parameters=1; async=true; generator=false
- isHiddenForNonPositionedNonSizedElement @62-77; FunctionDeclaration; parameters=1; async=true; generator=false
- sideArrowsAreDisplayedForPositionedNode @79-98; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @23; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_02.js

Blob: `1fd5fbec9fe11653f2a32db7d82653091bb21109`. Role: test-path,source. Parse: module.

- (anonymous) @84-96; FunctionExpression; parameters=0; async=true; generator=false
- positionLabelsAreCorrect @98-128; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @40; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_03.js

Blob: `8ba3c9b802865dcdf2c0d7caff8d5aa08a693c1a`. Role: test-path,source. Parse: module.

- (anonymous) @20-38; FunctionExpression; parameters=0; async=true; generator=false
- checkArrowsLabelsAndHandlers @40-75; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @14; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_04.js

Blob: `ad61bd85ff016c38581d047b94874ee1904a0398`. Role: test-path,source. Parse: module.

- (anonymous) @26-55; FunctionExpression; parameters=0; async=true; generator=false
- checkArrowsAndHandlers @57-65; FunctionDeclaration; parameters=3; async=true; generator=false
- checkArrowAndHandler @67-106; FunctionDeclaration; parameters=3; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @14; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_05.js

Blob: `ff80546240ccc6e8c2c16fec028710e8a482475f`. Role: test-path,source. Parse: module.

- (anonymous) @88-104; FunctionExpression; parameters=0; async=true; generator=false
- testNode @106-125; FunctionDeclaration; parameters=2; async=true; generator=false
- isOffsetParentVisible @127-129; FunctionDeclaration; parameters=1; async=true; generator=false
- isCurrentNodeVisible @131-133; FunctionDeclaration; parameters=1; async=true; generator=false
- hasVisibleArrowsAndHandlers @135-143; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @14; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_06.js

Blob: `10b0115ccf0bebc87ceb95e59beafc496e998bc1`. Role: test-path,source. Parse: module.

- (anonymous) @66-84; FunctionExpression; parameters=0; async=true; generator=false
- executeTest @86-93; FunctionDeclaration; parameters=3; async=true; generator=false
- areElementAndHighlighterMovedCorrectly @95-125; FunctionDeclaration; parameters=3; async=true; generator=false
- isHandlerPositionUpdated @127-137; FunctionDeclaration; parameters=5; async=true; generator=false
- areElementSideValuesCorrect @139-162; FunctionDeclaration; parameters=4; async=true; generator=false
- getHandlerCoords @164-169; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @12; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_07.js

Blob: `ca4bb42041c1c855e206c382d170d5ba2048800e`. Role: test-path,source. Parse: module.

- (anonymous) @28-41; FunctionExpression; parameters=0; async=true; generator=false
- executeTest @43-60; FunctionDeclaration; parameters=4; async=true; generator=false
- checkOffsetParentSame @64-108; FunctionDeclaration; parameters=3; async=true; generator=false
- checkArrowStartingPos @112-138; FunctionDeclaration; parameters=3; async=true; generator=false
- splitPointsIntoCoordinates @141-149; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @12; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_hide_on_interaction.js

Blob: `4b44561b61d4a1b6c9cbef1341011744ccd679d3`. Role: test-path,source. Parse: module.

- (anonymous) @12-72; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @20-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOnceHighlighterShown @74-76; FunctionDeclaration; parameters=1; async=false; generator=false
- getOnceHighlighterHidden @78-80; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-geometry_iframe.js

Blob: `a5f7b22a0064747439d05303c0b89f3fde080357`. Role: test-path,source. Parse: module.

- (anonymous) @21-48; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_01.js

Blob: `264257ae274c6341a6d052f19335b10fd9f48ce2`. Role: test-path,source. Parse: module.

- (anonymous) @13-33; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_02.js

Blob: `7c295407edf02be64c26d05f1c7099a06f146feb`. Role: test-path,source. Parse: module.

- (anonymous) @12-43; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-hover_03.js

Blob: `0cd7461bea1c2ffa85f643b8bb3a702971dcf44f`. Role: test-path,source. Parse: module.

- (anonymous) @13-60; FunctionExpression; parameters=0; async=true; generator=false
- isHighlighting @22-25; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForHighlighterShown @27-32; FunctionDeclaration; parameters=0; async=true; generator=false
- waitForInspectorUpdated @34-36; FunctionDeclaration; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-iframes_01.js

Blob: `c39431b4dc74572f807495953b1b0190b398f54e`. Role: test-path,source. Parse: module.

- (anonymous) @27-86; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-iframes_02.js

Blob: `bb1943f33525c5350a21ecca999f48d6d0d8e2ad`. Role: test-path,source. Parse: module.

- (anonymous) @15-51; FunctionExpression; parameters=0; async=true; generator=false
- switchToFrameContext @59-78; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-inline.js

Blob: `0432b84a2d356152c100044caaea6779ad505182`. Role: test-path,source. Parse: module.

- (anonymous) @24-93; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_01.js

Blob: `7e5a09ded38f6dcc23527b3468928c9f0e2bac73`. Role: test-path,source. Parse: module.

- (anonymous) @11-71; FunctionExpression; parameters=0; async=true; generator=false
- doKeyHover @61-70; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_02.js

Blob: `cb8f995699838a3c491ad40f8e16f5305d7689cd`. Role: test-path,source. Parse: module.

- (anonymous) @11-64; FunctionExpression; parameters=0; async=true; generator=false
- doKeyHover @55-63; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_03.js

Blob: `86a427c6e758d85e3aea459e932daf7af3414180`. Role: test-path,source. Parse: module.

- (anonymous) @12-69; FunctionExpression; parameters=0; async=true; generator=false
- doKeyPick @54-62; FunctionDeclaration; parameters=2; async=false; generator=false
- doKeyStop @64-68; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_04.js

Blob: `5351ae32de8c78eb33d1d63578bacd5a7a1b246c`. Role: test-path,source. Parse: module.

- (anonymous) @11-39; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-keybinding_separate-window.js

Blob: `80984bf96e954aca3cbd631365ba3ff78f445e0a`. Role: test-path,source. Parse: module.

- (anonymous) @31-99; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @94-94; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertStatuses @101-116; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @103-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForFocusChanged @118-120; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure-keybinding.js

Blob: `66f250ab18f08178e8101de09c7febb462431f01`. Role: test-path,source. Parse: module.

- (anonymous) @22-123; FunctionExpression; parameters=0; async=true; generator=false
- canMoveAreaViaKeybindings @125-149; FunctionDeclaration; parameters=4; async=true; generator=false
- canResizeAreaViaKeybindings @151-178; FunctionDeclaration; parameters=4; async=true; generator=false
- handlerIsHighlighted @180-186; FunctionDeclaration; parameters=1; async=true; generator=false
- handlerShouldBeHighlighted @188-190; FunctionDeclaration; parameters=1; async=true; generator=false
- handlerShouldNotBeHighlighted @192-197; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @14; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_01.js

Blob: `d09863ec60b5615bc096119e66679c7b54c77a3b`. Role: test-path,source. Parse: module.

- (anonymous) @25-39; FunctionExpression; parameters=0; async=true; generator=false
- isHiddenByDefault @41-52; FunctionDeclaration; parameters=1; async=true; generator=false
- areLabelsHiddenByDefaultWhenShows @54-67; FunctionDeclaration; parameters=1; async=true; generator=false
- areLabelsProperlyDisplayedWhenMouseMoved @69-95; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @17; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_02.js

Blob: `25026ea26853c58a9456f9da225bd7d7e877e0a5`. Role: test-path,source. Parse: module.

- (anonymous) @30-48; FunctionExpression; parameters=0; async=true; generator=false
- hasNoLabelsWhenStarts @50-74; FunctionDeclaration; parameters=1; async=true; generator=false
- hasSizeLabelWhenMoved @76-100; FunctionDeclaration; parameters=1; async=true; generator=false
- hasSizeLabelAndGuidesWhenStops @102-127; FunctionDeclaration; parameters=1; async=true; generator=false
- hasCorrectSizeLabelValue @129-141; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @17; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_03.js

Blob: `ac396f81497b7fd5be1b8a79825ae3d51d2c25a1`. Role: test-path,source. Parse: module.

- top @22-24; FunctionExpression; parameters=1; async=false; generator=false
- topright @25-27; FunctionExpression; parameters=1; async=false; generator=false
- right @28-30; FunctionExpression; parameters=2; async=false; generator=false
- bottomright @31-33; FunctionExpression; parameters=2; async=false; generator=false
- bottom @34-36; FunctionExpression; parameters=2; async=false; generator=false
- bottomleft @37-39; FunctionExpression; parameters=2; async=false; generator=false
- left @40-42; FunctionExpression; parameters=2; async=false; generator=false
- topleft @43-45; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-66; FunctionExpression; parameters=0; async=true; generator=false
- areHandlersHiddenByDefault @68-77; FunctionDeclaration; parameters=1; async=true; generator=false
- areHandlersHiddenOnAreaCreation @79-88; FunctionDeclaration; parameters=1; async=true; generator=false
- areHandlersCorrectlyShownAfterAreaCreation @90-109; FunctionDeclaration; parameters=1; async=true; generator=false
- getHandlerCoords @111-117; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @11; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-measure_04.js

Blob: `d515d6893e7c84e5dd33d11089cb6e1b84524eb3`. Role: test-path,source. Parse: module.

- top @24-26; FunctionExpression; parameters=1; async=false; generator=false
- topright @27-29; FunctionExpression; parameters=1; async=false; generator=false
- right @30-32; FunctionExpression; parameters=2; async=false; generator=false
- bottomright @33-35; FunctionExpression; parameters=2; async=false; generator=false
- bottom @36-38; FunctionExpression; parameters=2; async=false; generator=false
- bottomleft @39-41; FunctionExpression; parameters=2; async=false; generator=false
- left @42-44; FunctionExpression; parameters=2; async=false; generator=false
- topleft @45-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-72; FunctionExpression; parameters=0; async=true; generator=false
- canResizeAreaViaHandlers @74-158; FunctionDeclaration; parameters=1; async=true; generator=false
- getHandlerCoords @160-166; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @11; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-options.js

Blob: `b7ad10013b21c71933bc9134c39234aef25ee08b`. Role: test-path,source. Parse: module.

- checkHighlighter @25-45; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @50-56; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @61-69; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @74-80; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @85-97; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @102-114; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @119-153; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @158-192; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @197-213; FunctionExpression; parameters=1; async=true; generator=false
- checkHighlighter @218-234; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @238-262; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-preview.js

Blob: `256f57c521943eb4e097eb5eeb731d8a994aa086`. Role: test-path,source. Parse: module.

- (anonymous) @14-41; FunctionExpression; parameters=0; async=true; generator=false
- clickElement @43-49; FunctionDeclaration; parameters=3; async=true; generator=false
- checkElementSelected @51-58; FunctionDeclaration; parameters=2; async=true; generator=false
- checkPickerMode @60-72; FunctionDeclaration; parameters=2; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reduced-motion-message.js

Blob: `2d134392d35f4633a967976f2614ce229a02a939`. Role: test-path,source. Parse: module.

- testMessageHiddenWhenPrefersReducedMotionDisabled @11-25; FunctionExpression; parameters=0; async=true; generator=false
- testMessageHiddenWhenAlreadyDismissed @27-42; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-98; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-77; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @85-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getSimpleHighlightersMessage @100-104; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reduced-motion.js

Blob: `43ce3296986bd4fcebf724e5f96c3f962a39925a`. Role: test-path,source. Parse: module.

- (anonymous) @13-88; FunctionExpression; parameters=0; async=true; generator=false
- getElementComputedStyle @29-36; ArrowFunctionExpression; parameters=2; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-reload.js

Blob: `ac3dac4e2cf16cd128db0b872f74405bb21c3464`. Role: test-path,source. Parse: module.

- (anonymous) @11-36; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_01.js

Blob: `2453c543e4ac06f9bbc6f89ac4ea6941ea166a2a`. Role: test-path,source. Parse: module.

- (anonymous) @28-41; FunctionExpression; parameters=0; async=true; generator=false
- isHiddenByDefault @43-52; FunctionDeclaration; parameters=3; async=true; generator=false
- isVisibleAfterShow @54-67; FunctionDeclaration; parameters=3; async=true; generator=false
- isHiddenAfterHide @69-79; FunctionDeclaration; parameters=3; async=true; generator=false
- hasRightLabelsContent @81-110; FunctionDeclaration; parameters=3; async=true; generator=false
- isRulerHidden @112-119; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @24; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_02.js

Blob: `67751122f600f091fa79fb7d237a55e4a8416911`. Role: test-path,source. Parse: module.

- (anonymous) @20-35; FunctionExpression; parameters=0; async=true; generator=false
- isUpdatedAfterScroll @37-204; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @82-91; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @83-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @86-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @146-155; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @147-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @150-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://devtools/shared/highlighters.mjs @16; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-rulers_03.js

Blob: `329bc4bb5422dd6f2c707aa5f9e4f98c5a9de257`. Role: test-path,source. Parse: module.

- (anonymous) @21-35; FunctionExpression; parameters=0; async=true; generator=false
- isVisibleAfterShow @37-53; FunctionDeclaration; parameters=3; async=true; generator=false
- isHiddenAfterHide @55-68; FunctionDeclaration; parameters=3; async=true; generator=false
- hasRightLabelsContent @70-97; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @74-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-96; ArrowFunctionExpression; parameters=0; async=true; generator=false
- resizeInspector @99-108; FunctionDeclaration; parameters=1; async=true; generator=false
- isViewportInfobarHidden @110-117; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @15; ChromeUtils-import-literal
- Module resource://devtools/shared/loader/Loader.sys.mjs @75; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-selector_01.js

Blob: `13e79d18855ad79b12c8ee7d2cb7a05ceb764f53`. Role: test-path,source. Parse: module.

- (anonymous) @54-83; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @50; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-selector_02.js

Blob: `cbd6a06f03adc4980b6ab9819fea9982ccc04f6c`. Role: test-path,source. Parse: module.

- (anonymous) @47-88; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @43; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-svg-document.js

Blob: `331d0b3dfb4048e6aa993c96ea9ce04019f5ed88`. Role: test-path,source. Parse: module.

- (anonymous) @13-53; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @30-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getInfoBarEl @31-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-viewport-size.js

Blob: `e7bdd0159a67cfdf42a99c05e9b0f6fe90ccd40d`. Role: test-path,source. Parse: module.

- (anonymous) @20-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @70-76; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @83-89; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @101-107; ArrowFunctionExpression; parameters=0; async=true; generator=false
- isInfobarVisible @121-139; FunctionDeclaration; parameters=3; async=true; generator=false
- hasRightLabelsContent @141-169; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @143-168; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @148-156; ArrowFunctionExpression; parameters=0; async=false; generator=false
- resizeInspector @171-177; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForVisible @179-188; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @180-186; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForHidden @190-198; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @191-197; ArrowFunctionExpression; parameters=0; async=true; generator=false
- isViewportInfobarHidden @200-207; FunctionDeclaration; parameters=2; async=true; generator=false
- isRulersHighlighterHidden @209-219; FunctionDeclaration; parameters=2; async=true; generator=false
- Module resource://devtools/shared/highlighters.mjs @14; ChromeUtils-import-literal
- Module resource://devtools/shared/loader/Loader.sys.mjs @149; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/browser_inspector_highlighter-zoom.js

Blob: `dc6a24b2fb7289412aa39ffcec29551e8201bb99`. Role: test-path,source. Parse: module.

- expectedStyle @17-22; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @24-74; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @52-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getElementsNodeStyle @76-82; FunctionDeclaration; parameters=1; async=true; generator=false
- Module resource://devtools/shared/loader/Loader.sys.mjs @53; ChromeUtils-import-literal

### devtools/client/inspector/test/highlighter/head.js

Blob: `1937e80cdfb3e67026428d9da4c66300cf03c3bf`. Role: test-path,source. Parse: module.


### devtools/client/inspector/test/search/browser_inspector_search-01.js

Blob: `3d56252f25cda60a53207072b42421d2546db037`. Role: test-path,source. Parse: module.

- (anonymous) @60-110; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-02.js

Blob: `9746ef0c81678896ae54cb657c6c54d5d0209156`. Role: test-path,source. Parse: module.

- (anonymous) @139-142; FunctionExpression; parameters=0; async=true; generator=false
- testEscape @144-168; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-03.js

Blob: `ad09ebcd5e418eca8dc2dd63ecd3ccddb676d942`. Role: test-path,source. Parse: module.

- (anonymous) @209-212; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @214-302; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-04.js

Blob: `ff4c789b24c90970e4a2ee444b929e60e18e323b`. Role: test-path,source. Parse: module.

- (anonymous) @73-111; FunctionExpression; parameters=0; async=true; generator=false
- formatSuggestions @113-115; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @114-114; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-05.js

Blob: `a5e4cb99abf46d351e865dd31c2f4d9fd93bcf98`. Role: test-path,source. Parse: module.

- (anonymous) @10-64; FunctionExpression; parameters=0; async=true; generator=false
- checkCorrectButton @66-83; FunctionExpression; parameters=2; async=true; generator=false
- getSelectedNodeFrontInfo @93-107; FunctionDeclaration; parameters=1; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-06.js

Blob: `96dab6dd2b8d33cb69faca9c5aa3230c1f719b88`. Role: test-path,source. Parse: module.

- (anonymous) @12-70; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-27; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- synthesizeKeys @72-87; FunctionDeclaration; parameters=2; async=true; generator=false
- assertHasResult @89-97; FunctionDeclaration; parameters=2; async=false; generator=false
- mutatePage @99-103; FunctionDeclaration; parameters=2; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-07.js

Blob: `e112fca9448de4cc1e724e6adcc9e84bd33b9b1b`. Role: test-path,source. Parse: module.

- (anonymous) @26-60; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-08.js

Blob: `64c62d8b1acd7ac2a1df56b343fd0b6122ce4a87`. Role: test-path,source. Parse: module.

- (anonymous) @41-75; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-09.js

Blob: `f61d1c92130dc5ec49b25448d34b34020cadaf9c`. Role: test-path,source. Parse: module.

- (anonymous) @49-112; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-10.js

Blob: `2912c9588b775c42169755da8eab6d9e4a4030e2`. Role: test-path,source. Parse: module.

- (anonymous) @24-51; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-clear.js

Blob: `56078d035b99ae67c2e8626640dcd68022007d59`. Role: test-path,source. Parse: module.

- (anonymous) @26-88; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-filter_context-menu.js

Blob: `e8392b1425cff379ef6081afd73926d56a63c35f`. Role: test-path,source. Parse: module.

- (anonymous) @10-109; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-label.js

Blob: `037d5bb8da4bb8f6a9be97ebe864fb164fb9aea4`. Role: test-path,source. Parse: module.

- (anonymous) @11-38; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-navigation.js

Blob: `cb74c8ced0cad5cac5f3809c44caf2cc632e6671`. Role: test-path,source. Parse: module.

- (anonymous) @61-76; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-reserved.js

Blob: `a4acc469bcb0a36477ccacba1084b48d542c0363`. Role: test-path,source. Parse: module.

- (anonymous) @95-133; FunctionExpression; parameters=0; async=true; generator=false
- formatSuggestions @135-137; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @136-136; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-selection.js

Blob: `bdc65945af4ebf4b5efb65912d6962d4aef05d55`. Role: test-path,source. Parse: module.

- (anonymous) @9-65; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @18-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-24; ArrowFunctionExpression; parameters=1; async=false; generator=false
- sendKeyAndCheck @67-83; FunctionExpression; parameters=5; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-sidebar.js

Blob: `9a802e8e01b226242b8923f5d897b59eaa5b248d`. Role: test-path,source. Parse: module.

- (anonymous) @8-49; FunctionExpression; parameters=0; async=true; generator=false
- pressCtrlF @51-53; FunctionDeclaration; parameters=0; async=false; generator=false
- moveFocusInRuleView @55-62; FunctionDeclaration; parameters=1; async=false; generator=false
- clickInComputedView @64-67; FunctionDeclaration; parameters=1; async=false; generator=false
- isInInspectorSearchBox @69-75; FunctionDeclaration; parameters=1; async=false; generator=false
- isInRuleViewSearchBox @77-83; FunctionDeclaration; parameters=1; async=false; generator=false
- isInComputedViewSearchBox @85-91; FunctionDeclaration; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-suggests-ids-and-classes.js

Blob: `80dc500089d4cc7ecac9cc65d76a20b57716c27e`. Role: test-path,source. Parse: module.

- (anonymous) @44-90; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search-suggests-pseudo.js

Blob: `1691ec110856390635aa36f558e08fd9fd70bc34`. Role: test-path,source. Parse: module.

- (anonymous) @9-164; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @115-115; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @125-125; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @132-132; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/search/browser_inspector_search_keyboard_shortcut_conflict.js

Blob: `696010fea42d58288e427e908d75e4c85b04eb9f`. Role: test-path,source. Parse: module.

- (anonymous) @10-59; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/browser_inspector_search_keyboard_trap.js

Blob: `b3f4fcdb3d441e07ce0884c4f9b61b160444ecc7`. Role: test-path,source. Parse: module.

- (anonymous) @73-95; FunctionExpression; parameters=0; async=true; generator=false

### devtools/client/inspector/test/search/head.js

Blob: `1937e80cdfb3e67026428d9da4c66300cf03c3bf`. Role: test-path,source. Parse: module.


### devtools/client/inspector/test/shared-head.js

Blob: `e229249e52f8c5922ff8232143482d802b92497e`. Role: test-path,source. Parse: module.

- openInspector @28-41; FunctionExpression; parameters=1; async=true; generator=false
- openInspectorSidebarTab @56-81; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openRuleView @94-113; FunctionDeclaration; parameters=1; async=true; generator=false
- openComputedView @122-133; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @123-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openChangesView @142-151; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @143-150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openLayoutView @160-172; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @161-171; ArrowFunctionExpression; parameters=1; async=false; generator=false
- selectRuleView @181-183; FunctionDeclaration; parameters=1; async=false; generator=false
- selectComputedView @192-195; FunctionDeclaration; parameters=1; async=true; generator=false
- selectChangesView @204-207; FunctionDeclaration; parameters=1; async=true; generator=false
- selectLayoutView @215-218; FunctionDeclaration; parameters=1; async=true; generator=false
- getNodeFront @229-234; FunctionDeclaration; parameters=2; async=false; generator=false
- selectNode @250-271; FunctionExpression; parameters=4; async=true; generator=false
- waitForChildrenUpdated @282-289; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @284-288; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @285-287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForMultipleChildrenUpdates @294-305; FunctionDeclaration; parameters=1; async=true; generator=false
- expandContainer @311-314; FunctionDeclaration; parameters=2; async=true; generator=false
- getNodeFrontInFrames @329-371; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @366-366; ArrowFunctionExpression; parameters=1; async=false; generator=false
- selectNodeInFrames @393-402; FunctionDeclaration; parameters=4; async=true; generator=false
- manualDebounce @413-433; FunctionDeclaration; parameters=0; async=false; generator=false
- debounce @416-425; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @417-424; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @418-418; ArrowFunctionExpression; parameters=1; async=false; generator=false
- debounce.flush @427-430; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @428-428; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRulePropertyValue @444-471; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @448-469; ArrowFunctionExpression; parameters=3; async=false; generator=false
- getComputedStyleProperty @483-494; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @487-492; ArrowFunctionExpression; parameters=3; async=false; generator=false
- waitForComputedStyleProperty @509-528; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @518-526; ArrowFunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @520-525; ArrowFunctionExpression; parameters=0; async=false; generator=false
- focusEditableField @536-581; FunctionExpression; parameters=5; async=true; generator=false
- getRuleViewRule @597-614; FunctionDeclaration; parameters=3; async=false; generator=false
- getRuleViewProperty @633-640; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @635-636; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _syncGetRuleViewProperty @642-658; FunctionDeclaration; parameters=3; async=false; generator=false
- getRuleViewPropertyValue @672-675; FunctionDeclaration; parameters=3; async=false; generator=false
- getRuleViewSelector @687-692; FunctionDeclaration; parameters=2; async=false; generator=false
- getRuleViewLinkByIndex @704-707; FunctionDeclaration; parameters=2; async=false; generator=false
- getRuleViewLinkTextByIndex @718-720; FunctionDeclaration; parameters=2; async=false; generator=false
- focusNewRuleViewProperty @730-747; FunctionExpression; parameters=1; async=true; generator=false
- createNewRuleViewProperty @762-777; FunctionExpression; parameters=2; async=true; generator=false
- setSearchFilter @789-800; FunctionExpression; parameters=2; async=true; generator=false
- buildContextMenuItems @806-818; FunctionDeclaration; parameters=1; async=false; generator=false
- addItem @809-814; FunctionExpression; parameters=1; async=false; generator=false
- openStyleContextMenuAndGetAllItems @827-830; FunctionDeclaration; parameters=2; async=false; generator=false
- openContextMenuAndGetAllItems @839-842; FunctionDeclaration; parameters=2; async=false; generator=false
- waitUntilVisitedState @852-878; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @853-877; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @857-874; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasMatchingElementInContentPage @886-894; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @890-892; FunctionExpression; parameters=1; async=false; generator=false
- getNumberOfMatchingElementsInContentPage @902-910; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @906-908; FunctionExpression; parameters=1; async=false; generator=false
- getContentPageElementProperty @919-927; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @923-925; FunctionExpression; parameters=2; async=false; generator=false
- setContentPageElementProperty @937-946; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @941-944; FunctionExpression; parameters=3; async=false; generator=false
- getContentPageElementAttributes @954-966; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @958-964; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @960-963; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getContentPageElementAttribute @975-983; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @979-981; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setContentPageElementAttribute @992-1002; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @996-1000; ArrowFunctionExpression; parameters=3; async=false; generator=false
- removeContentPageElementAttribute @1010-1018; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @1014-1016; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getRuleViewRuleEditorAt @1035-1039; FunctionDeclaration; parameters=2; async=false; generator=false
- getTextProperty @1054-1068; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @1057-1059; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setProperty @1086-1185; FunctionDeclaration; parameters=4; async=true; generator=false
- onStartSet @1108-1108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onChanged @1112-1112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1131-1131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getMarkupViewSearchInput @1193-1195; FunctionDeclaration; parameters=1; async=false; generator=false
- searchInMarkupView @1202-1223; FunctionDeclaration; parameters=2; async=true; generator=false
- assertDisplayedRulesCount @1228-1235; FunctionDeclaration; parameters=3; async=true; generator=false
- showCustomizableSelectPicker @1245-1257; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @1247-1255; ArrowFunctionExpression; parameters=1; async=false; generator=false

### devtools/client/inspector/test/sjs_slow-loading-image.sjs

Blob: `c4b12d7c60e1cda0c586471b97ad7489a33fb6bf`. Role: test-path,data-or-other. Parse: module.

- handleRequest @5-33; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @12-12; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-29; ArrowFunctionExpression; parameters=0; async=false; generator=false

### devtools/client/inspector/toolsidebar.js

Blob: `021b821b2f6021695bc81778163982f6c2886212`. Role: source. Parse: module.

- constructor @10-29; FunctionExpression; parameters=3; async=false; generator=false
- React @44-46; FunctionExpression; parameters=0; async=false; generator=false
- ReactDOM @48-50; FunctionExpression; parameters=0; async=false; generator=false
- browserRequire @52-54; FunctionExpression; parameters=0; async=false; generator=false
- InspectorTabPanel @56-58; FunctionExpression; parameters=0; async=false; generator=false
- TabBar @60-62; FunctionExpression; parameters=0; async=false; generator=false
- render @66-76; FunctionExpression; parameters=0; async=false; generator=false
- addAllQueuedTabs @81-83; FunctionExpression; parameters=0; async=false; generator=false
- addTab @94-97; FunctionExpression; parameters=5; async=false; generator=false
- addExistingTab @108-117; FunctionExpression; parameters=4; async=false; generator=false
- queueTab @128-131; FunctionExpression; parameters=5; async=false; generator=false
- queueExistingTab @142-151; FunctionExpression; parameters=4; async=false; generator=false
- removeTab @160-164; FunctionExpression; parameters=1; async=false; generator=false
- toggleTab @172-174; FunctionExpression; parameters=2; async=false; generator=false
- select @182-184; FunctionExpression; parameters=1; async=false; generator=false
- getCurrentTabID @189-191; FunctionExpression; parameters=0; async=false; generator=false
- getTabPanel @199-205; FunctionExpression; parameters=1; async=false; generator=false
- handleSelectionChange @210-224; FunctionExpression; parameters=1; async=false; generator=false
- updateTelemetryOnChange @234-253; FunctionExpression; parameters=2; async=false; generator=false
- getTelemetryPanelNameOrOther @264-280; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @268-270; ArrowFunctionExpression; parameters=1; async=false; generator=false
- show @288-297; FunctionExpression; parameters=1; async=false; generator=false
- hide @302-306; FunctionExpression; parameters=0; async=false; generator=false
- destroy @311-331; FunctionExpression; parameters=0; async=false; generator=false
- Class ToolSidebar @9-332

### devtools/client/jsonview/.eslintrc.mjs

Blob: `ccb3dec226efa9ecb299e1ec63853f66712be9fe`. Role: source. Parse: module.


### devtools/client/jsonview/Converter.sys.mjs

Blob: `560f82440a8d6ae934c6bfe412892b29efdee359`. Role: source. Parse: module.

- Converter @8-17; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://devtools/shared/loader/Loader.sys.mjs @9; ChromeUtils-import-literal

### devtools/client/jsonview/Sniffer.sys.mjs

Blob: `2ea89a71b2a36f57f7a7faec69e82e79c0f31cb2`. Role: source. Parse: module.

- getContentDisposition @19-26; FunctionDeclaration; parameters=1; async=false; generator=false
- getMIMETypeFromContent @38-77; FunctionExpression; parameters=1; async=false; generator=false
- Class Sniffer @37-78
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/jsonl-mime-types.mjs @6; ImportDeclaration

### devtools/client/jsonview/components/Headers.mjs

Blob: `91d9a908d9455b552b986c772f67d184676b3683`. Role: source. Parse: module.

- propTypes @22-26; FunctionExpression; parameters=0; async=false; generator=false
- constructor @28-31; FunctionExpression; parameters=1; async=false; generator=false
- render @33-61; FunctionExpression; parameters=0; async=false; generator=false
- propTypes @69-78; FunctionExpression; parameters=0; async=false; generator=false
- constructor @80-86; FunctionExpression; parameters=1; async=false; generator=false
- render @88-110; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-93; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @96-107; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class HeaderList @68-111
- Class Headers @21-62
- Module resource://devtools/client/shared/vendor/react.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @11; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @12; ImportDeclaration

### devtools/client/jsonview/components/HeadersPanel.mjs

Blob: `cfb874be6524c5beee2615cdf8cda0a8b59269c0`. Role: source. Parse: module.

- propTypes @26-31; FunctionExpression; parameters=0; async=false; generator=false
- constructor @33-39; FunctionExpression; parameters=1; async=false; generator=false
- render @41-49; FunctionExpression; parameters=0; async=false; generator=false
- Class HeadersPanel @25-50
- Module resource://devtools/client/shared/vendor/react.mjs @7; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @8; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-dom-factories.mjs @9; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @10; ImportDeclaration
- Module resource://devtools/client/jsonview/components/Headers.mjs @12; ImportDeclaration
- Module resource://devtools/client/jsonview/components/HeadersToolbar.mjs @15; ImportDeclaration

### devtools/client/jsonview/components/HeadersToolbar.mjs

Blob: `39b95bd5ff439144662592d6363b6cf1634ae96d`. Role: source. Parse: module.

- propTypes @18-22; FunctionExpression; parameters=0; async=false; generator=false
- constructor @24-27; FunctionExpression; parameters=1; async=false; generator=false
- onCopy @31-33; FunctionExpression; parameters=0; async=false; generator=false
- render @35-43; FunctionExpression; parameters=0; async=false; generator=false
- Class HeadersToolbar @17-44
- Module resource://devtools/client/shared/vendor/react.mjs @5; ImportDeclaration
- Module resource://devtools/client/shared/vendor/react-prop-types.mjs @6; ImportDeclaration
- Module resource://devtools/client/shared/react-utils.mjs @7; ImportDeclaration
- Module resource://devtools/client/jsonview/components/reps/Toolbar.mjs @9; ImportDeclaration

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
