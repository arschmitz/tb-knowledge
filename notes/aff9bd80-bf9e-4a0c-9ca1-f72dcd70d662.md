<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["browser/components/firefoxview/tests/browser/browser_history_firefoxview.js","browser/components/firefoxview/tests/browser/browser_opentabs_cards.js","browser/components/firefoxview/tests/browser/browser_opentabs_changes.js","browser/components/firefoxview/tests/browser/browser_opentabs_firefoxview.js","browser/components/firefoxview/tests/browser/browser_opentabs_more.js","browser/components/firefoxview/tests/browser/browser_opentabs_pinned_tabs.js","browser/components/firefoxview/tests/browser/browser_opentabs_recency.js","browser/components/firefoxview/tests/browser/browser_opentabs_search.js","browser/components/firefoxview/tests/browser/browser_opentabs_tab_favicons.js","browser/components/firefoxview/tests/browser/browser_opentabs_tab_indicators.js","browser/components/firefoxview/tests/browser/browser_recentlyclosed_firefoxview.js","browser/components/firefoxview/tests/browser/browser_reload_firefoxview.js","browser/components/firefoxview/tests/browser/browser_syncedtabs_errors_firefoxview.js","browser/components/firefoxview/tests/browser/browser_syncedtabs_firefoxview.js","browser/components/firefoxview/tests/browser/browser_tab_close_last_tab.js","browser/components/firefoxview/tests/browser/browser_tab_list_keyboard_navigation.js","browser/components/firefoxview/tests/browser/browser_tab_on_close_warning.js","browser/components/firefoxview/tests/browser/head.js","browser/components/firefoxview/viewpage.mjs","browser/components/genai/GenAI.sys.mjs","browser/components/genai/GenAIChild.sys.mjs","browser/components/genai/GenAIParent.sys.mjs","browser/components/genai/LinkPreview.sys.mjs","browser/components/genai/LinkPreviewChild.sys.mjs","browser/components/genai/LinkPreviewModel.sys.mjs","browser/components/genai/LinkPreviewParent.sys.mjs","browser/components/genai/PageAssist.sys.mjs","browser/components/genai/PageAssistChild.sys.mjs","browser/components/genai/PageAssistParent.sys.mjs","browser/components/genai/chat.js","browser/components/genai/content/chatbot-promo.mjs","browser/components/genai/content/chatbot-promo.stories.mjs","browser/components/genai/content/link-preview-card-onboarding.mjs","browser/components/genai/content/link-preview-card.mjs","browser/components/genai/content/model-optin.mjs","browser/components/genai/content/page-assist.mjs","browser/components/genai/tests/browser/browser_chat_contextmenu.js","browser/components/genai/tests/browser/browser_chat_nimbus.js","browser/components/genai/tests/browser/browser_chat_page.js","browser/components/genai/tests/browser/browser_chat_promo.js","browser/components/genai/tests/browser/browser_chat_prompt.js","browser/components/genai/tests/browser/browser_chat_request.js","browser/components/genai/tests/browser/browser_chat_shortcuts.js","browser/components/genai/tests/browser/browser_chat_sidebar.js","browser/components/genai/tests/browser/browser_chat_sidebar_permissions.js","browser/components/genai/tests/browser/browser_chat_telemetry.js","browser/components/genai/tests/browser/browser_genai_actors.js","browser/components/genai/tests/browser/browser_genai_init.js","browser/components/genai/tests/browser/browser_link_preview.js","browser/components/genai/tests/browser/browser_link_preview_aifeature_lifecycle.js","browser/components/genai/tests/browser/browser_link_preview_nimbus.js","browser/components/genai/tests/browser/browser_link_preview_optin.js","browser/components/genai/tests/browser/browser_link_preview_perf.js","browser/components/genai/tests/browser/browser_link_preview_telemetry.js","browser/components/genai/tests/browser/browser_page_assist_actors.js","browser/components/genai/tests/browser/browser_page_assist_sidebar.js","browser/components/genai/tests/browser/head.js","browser/components/genai/tests/xpcshell/test_contextual_prompts.js","browser/components/genai/tests/xpcshell/test_link_preview_text.js","browser/components/genai/tests/xpcshell/test_page_assist.js","browser/components/genai/tests/xpcshell/test_provider_id.js","browser/components/genai/tests/xpcshell/test_show_chat_entrypoint.js","browser/components/installerprefs/InstallerPrefs.sys.mjs","browser/components/installerprefs/test/unit/head.js","browser/components/installerprefs/test/unit/test_empty_prefs_list.js","browser/components/installerprefs/test/unit/test_invalid_name.js","browser/components/installerprefs/test/unit/test_nonbool_pref.js","browser/components/installerprefs/test/unit/test_pref_change.js","browser/components/installerprefs/test/unit/test_pref_values.js","browser/components/ipprotection/IPPL10nHelper.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/browser JavaScript function map 36

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### browser/components/firefoxview/tests/browser/browser_history_firefoxview.js

Blob: `1629f6c18a85246137bd0e45977d1c86d8b4a9ba`. Role: test-path,source. Parse: module.

- isElInViewport @62-72; FunctionDeclaration; parameters=1; async=false; generator=false
- historyComponentReady @74-84; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addHistoryItems @86-107; FunctionDeclaration; parameters=1; async=true; generator=false
- createHistoryEntries @109-119; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @115-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @121-126; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @122-125; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_list_ordering @128-227; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @132-226; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @138-138; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @151-153; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @159-159; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @185-185; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @201-201; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @212-212; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_empty_states @229-331; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @231-330; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @239-239; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @261-261; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-282; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @293-293; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @302-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @317-317; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_observers_removed_when_view_is_hidden @333-386; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @340-385; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @346-346; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @351-351; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @365-365; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @376-376; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @380-380; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_show_all_history_telemetry @388-420; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @392-419; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @413-413; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_search_history @422-500; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @426-499; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @433-433; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @445-449; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @451-454; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @459-462; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @470-472; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @479-482; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @495-497; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_search_ignores_stale_queries @502-562; FunctionExpression; parameters=0; async=true; generator=false
- executeCached @511-517; ArrowFunctionExpression; parameters=2; async=true; generator=false
- interrupt @518-518; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @524-559; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @531-531; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @539-539; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @551-554; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_persist_collapse_card_after_view_change @564-603; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @567-602; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @573-573; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_forget_about_this_site_option @605-688; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @613-687; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @618-618; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @623-623; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @628-628; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @641-641; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @645-645; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @680-680; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/PlacesTestUtils.sys.mjs @4; ChromeUtils-import-literal
- Module resource://gre/modules/ProfileAge.sys.mjs @12; ChromeUtils-import-literal

### browser/components/firefoxview/tests/browser/browser_opentabs_cards.js

Blob: `974d4499e211abc02f36a2885e5c0cc65893ebc8`. Role: test-path,source. Parse: module.

- (anonymous) @11-16; FunctionExpression; parameters=0; async=true; generator=false
- cleanup @18-39; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkTabLists @50-62; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- open_tab_same_window @64-179; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-85; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @89-105; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @108-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @112-127; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @130-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @134-176; ArrowFunctionExpression; parameters=1; async=true; generator=false
- open_tab_new_window @181-266; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @191-235; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @240-262; ArrowFunctionExpression; parameters=1; async=true; generator=false
- open_tab_new_private_window @268-282; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @271-280; ArrowFunctionExpression; parameters=1; async=true; generator=false
- open_tab_new_window_sort_by_recency @284-322; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @295-320; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @311-315; ArrowFunctionExpression; parameters=0; async=true; generator=false
- styling_for_multiple_windows @324-401; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @326-338; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @351-371; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @358-360; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @385-399; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @392-394; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_changes.js

Blob: `9163f59fdda37f0e27aad2d9194f0a5b73c5de97`. Role: test-path,source. Parse: module.

- tabUrl @14-16; FunctionDeclaration; parameters=1; async=false; generator=false
- getWindowId @18-20; FunctionDeclaration; parameters=1; async=false; generator=false
- setup @22-103; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @90-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cleanup @96-101; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_TabChanges @105-191; FunctionExpression; parameters=0; async=true; generator=false
- test_TabRecencyChange @193-410; FunctionExpression; parameters=0; async=true; generator=false
- test_tabNavigations @412-494; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @438-440; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @471-473; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tabsFromPrivateWindows @496-540; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @512-512; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @522-522; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/OpenTabs.sys.mjs @1; ChromeUtils-import-literal

### browser/components/firefoxview/tests/browser/browser_opentabs_firefoxview.js

Blob: `01f1230d0c0a603cc67d3ef68d3b8887b431c291`. Role: test-path,source. Parse: module.

- getVisibleTabURLs @26-28; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @27-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getTabRowURLs @30-32; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @31-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitUntilRowsMatch @34-70; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @44-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-68; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getContextMenuPanelListForCard @72-86; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openContextMenuForItem @88-108; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @91-100; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @94-94; ArrowFunctionExpression; parameters=1; async=false; generator=false
- moreMenuSetup @110-143; FunctionDeclaration; parameters=1; async=true; generator=false
- test_close_open_tab @145-179; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @146-178; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_more_menus @181-306; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @182-305; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_send_device_submenu @308-394; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @323-323; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @325-393; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_submenu_text @396-459; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @427-427; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @429-458; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_fxa_disabled_submenu_text @461-509; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @478-478; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @480-508; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_signed_out_submenu_text @511-567; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @528-528; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @530-566; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_signed_in_sync_disabled_submenu_text @570-626; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @583-583; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @584-584; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @586-625; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_single_device_submenu_text @629-694; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @642-642; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @643-643; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @645-693; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_send_mobile_unverified_account_text @696-758; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @701-701; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @702-702; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @704-757; ArrowFunctionExpression; parameters=0; async=true; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_more.js

Blob: `566e58de84e1b4dfee3903927b8eb2796b1fbea2`. Role: test-path,source. Parse: module.

- (anonymous) @10-13; FunctionExpression; parameters=0; async=false; generator=false
- cleanup @15-36; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggle_show_more_link @38-151; FunctionExpression; parameters=0; async=true; generator=false
- tabEntry @39-41; ArrowFunctionExpression; parameters=1; async=false; generator=false
- tab @69-72; ArrowFunctionExpression; parameters=1; async=false; generator=false
- enter @74-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @81-149; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @89-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-106; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @114-114; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @132-132; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=0; async=true; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_pinned_tabs.js

Blob: `8f644b4b8fe98d7a1898bb0ce11cd6ddaea207b6`. Role: test-path,source. Parse: module.

- cleanup @10-15; FunctionDeclaration; parameters=0; async=false; generator=false
- arrowDown @17-21; ArrowFunctionExpression; parameters=1; async=true; generator=false
- arrowUp @22-26; ArrowFunctionExpression; parameters=1; async=true; generator=false
- arrowRight @27-31; ArrowFunctionExpression; parameters=1; async=true; generator=false
- arrowLeft @32-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_pin_unpin_open_tab @38-149; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @39-147; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-89; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @118-118; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_indicator_pinned_tabs_with_keyboard @151-301; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @155-299; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @162-162; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @189-193; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @221-221; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @226-226; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_mute_unmute_pinned_tab @303-375; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @304-373; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @311-311; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @344-344; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @370-370; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_mute_unmute_with_context_menu @377-476; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @378-474; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @385-385; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @403-403; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @428-428; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @439-439; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @471-471; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_recency.js

Blob: `c037744bf4ec4bd8e3f2e0b7e8f9fe6a2d83a981`. Role: test-path,source. Parse: module.

- (anonymous) @20-22; FunctionExpression; parameters=0; async=true; generator=false
- cleanup @24-27; FunctionDeclaration; parameters=0; async=true; generator=false
- tabUrl @29-31; FunctionDeclaration; parameters=1; async=false; generator=false
- minimizeWindow @33-45; FunctionDeclaration; parameters=1; async=true; generator=false
- getAllSelectedTabURLs @47-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @48-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- restoreWindow @53-107; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @90-99; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @92-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- prepareOpenWindowsAndTabs @109-160; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @112-121; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @113-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @125-127; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @154-155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @155-155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @157-157; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getRecentOpenTabsComponent @162-166; FunctionDeclaration; parameters=1; async=false; generator=false
- checkRecentTabList @168-180; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @175-175; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @177-177; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_single_window_tabs @182-216; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @191-208; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @211-214; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_multiple_window_tabs @218-357; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @266-296; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @299-303; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @319-341; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @350-354; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_windows_activation @359-402; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @382-385; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @394-400; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_minimize_restore_windows @404-511; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @437-456; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @481-508; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @491-491; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/ObjectUtils.sys.mjs @10; ChromeUtils-import-literal

### browser/components/firefoxview/tests/browser/browser_opentabs_search.js

Blob: `fa96ab4510565b5ab7a347a816db8e7d6f09b544`. Role: test-path,source. Parse: module.

- (anonymous) @8-11; FunctionExpression; parameters=0; async=false; generator=false
- cleanup @13-23; FunctionDeclaration; parameters=0; async=true; generator=false
- search_open_tabs @25-86; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @33-82; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-52; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @79-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- search_open_tabs_recent_browsing @88-133; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @97-130; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @118-127; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_tab_favicons.js

Blob: `58560421b922a6388f224f098fb490288e56c1bf`. Role: test-path,source. Parse: module.

- waitForFavicon @15-28; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @16-27; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onLinkIconAvailable @18-24; FunctionExpression; parameters=3; async=false; generator=false
- getFaviconBackgroundImage @30-34; FunctionDeclaration; parameters=1; async=false; generator=false
- test_normal_favicon @36-84; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-83; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @51-51; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @67-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-71; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_svg_favicon @86-156; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-153; ArrowFunctionExpression; parameters=1; async=true; generator=false
- cspListener @95-97; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @129-129; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-133; ArrowFunctionExpression; parameters=1; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_opentabs_tab_indicators.js

Blob: `0dfc910bfd05be6e762c83180e4b041a7bc393e2`. Role: test-path,source. Parse: module.

- test_notification_dot_indicator @12-58; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-57; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @43-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @44-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_container_indicator @60-120; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @62-119; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @83-84; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @89-89; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @98-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_sound_playing_muted_indicator @122-228; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @124-227; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @151-151; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @157-161; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @158-161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @190-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @204-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @217-217; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_bookmark_indicator @230-294; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @232-291; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @238-238; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @248-248; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @256-256; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @264-264; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @269-269; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @281-281; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @288-288; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_recentlyclosed_firefoxview.js

Blob: `a063134615bb0b7246786c198394ab6893dcd4d9`. Role: test-path,source. Parse: module.

- restore_tab @30-38; FunctionDeclaration; parameters=3; async=true; generator=false
- dismiss_tab @40-43; FunctionDeclaration; parameters=1; async=true; generator=false
- tabTestCleanup @45-57; FunctionDeclaration; parameters=0; async=true; generator=false
- prepareSingleClosedTab @59-70; FunctionDeclaration; parameters=0; async=true; generator=false
- prepareClosedTabs @72-148; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @150-155; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @151-154; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_initial_closed_tab @160-177; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @161-176; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_list_ordering @183-204; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @185-202; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @198-198; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_list_updates @209-276; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @212-274; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @218-218; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @248-248; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @252-252; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @270-270; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_restore_tab @282-328; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @286-326; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @292-292; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_restore_tab_from_deleted_group @330-361; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @343-359; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_dismiss_tab @367-434; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @371-432; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @401-401; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @428-428; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_empty_states @436-500; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @449-499; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @459-459; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @481-481; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_observers_removed_when_view_is_hidden @502-534; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @507-533; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @529-529; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_search @536-581; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @538-579; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @551-551; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @559-559; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @568-568; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @576-576; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_search_recent_browsing @583-621; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @589-620; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @603-605; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @616-616; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_reload_firefoxview.js

Blob: `5e6771d2ab59d4ba50d7f97d3f67a6c687a45550`. Role: test-path,source. Parse: module.

- test_reload_firefoxview @11-40; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-39; ArrowFunctionExpression; parameters=1; async=true; generator=false

### browser/components/firefoxview/tests/browser/browser_syncedtabs_errors_firefoxview.js

Blob: `656c33813d86c84394377414957b01b873a0f437`. Role: test-path,source. Parse: module.

- setupWithDesktopDevices @41-61; FunctionDeclaration; parameters=1; async=true; generator=false
- tearDown @63-67; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @69-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @80-84; FunctionExpression; parameters=0; async=true; generator=false
- test_network_offline @87-139; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @90-137; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @108-110; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sync_error @141-166; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @143-164; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @157-159; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sync_admin_disabled @169-212; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @171-176; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @180-208; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @204-206; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sync_disabled_by_policy @214-245; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @218-243; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_sync_error_signed_out @247-276; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @250-274; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @263-266; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sync_disconnected_error @278-332; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @284-330; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @299-302; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_password_change_disconnect_error @334-368; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @341-366; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @355-358; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_multiple_errors @370-419; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @372-417; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @389-392; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @410-412; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/LoginTestUtils.sys.mjs @4; ChromeUtils-import-literal

### browser/components/firefoxview/tests/browser/browser_syncedtabs_firefoxview.js

Blob: `cd155371172d2f37e7c5bd21e69a8e621f733d01`. Role: test-path,source. Parse: module.

- (anonymous) @4-21; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @5-8; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @13-15; FunctionExpression; parameters=0; async=true; generator=false
- promiseTabListsUpdated @23-28; FunctionDeclaration; parameters=1; async=true; generator=false
- test_unconfigured_initial_state @30-68; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-66; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_loading_state @70-121; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @89-119; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_signed_in @123-214; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @137-212; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @146-146; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-165; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_synced_tabs @216-258; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @237-255; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @246-246; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_error_for_two_desktop @260-299; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @280-297; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @289-289; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_empty_state @301-356; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @327-354; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @336-336; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tabs @358-428; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @365-370; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @371-373; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @375-426; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @387-387; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @405-407; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_empty_desktop_same_name @430-473; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @450-471; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @459-459; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_empty_desktop_same_name_three @475-528; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @501-526; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @510-510; ArrowFunctionExpression; parameters=0; async=false; generator=false
- search_synced_tabs @530-714; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @537-542; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @543-545; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @547-711; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @556-556; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @562-568; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @586-586; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @590-593; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @597-599; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @603-604; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @615-615; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @619-625; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @635-637; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @641-643; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @652-652; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @656-659; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @662-667; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @669-670; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @680-680; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @684-690; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @700-702; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @706-708; ArrowFunctionExpression; parameters=0; async=false; generator=false
- search_synced_tabs_recent_browsing @716-841; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @728-736; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @759-838; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @776-776; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @783-783; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @793-793; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @800-802; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @816-816; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @821-821; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @827-828; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @834-834; ArrowFunctionExpression; parameters=0; async=false; generator=false
- view_all_synced_tabs_recent_browsing @843-932; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @855-863; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @886-930; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @897-897; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @918-918; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_mobile_connected @934-975; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @954-972; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @968-968; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_tablet_connected @977-1018; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @997-1015; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1011-1011; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_tab_sync_enabled @1020-1091; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1039-1089; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1051-1051; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1059-1059; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1063-1063; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1076-1076; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1080-1080; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/firefox-view-synced-tabs-error-handler.sys.mjs @82; ChromeUtils-import-literal

### browser/components/firefoxview/tests/browser/browser_tab_close_last_tab.js

Blob: `e7aed1c429d139a3c609f77c3675f765e92446a7`. Role: test-path,source. Parse: module.

- closing_last_tab_should_not_switch_to_fx_view @8-43; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/firefoxview/tests/browser/browser_tab_list_keyboard_navigation.js

Blob: `2e84f89f50498a14c089c5bba39351ae2a63cd1b`. Role: test-path,source. Parse: module.

- test_open_tab_row_navigation @4-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @5-59; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_focus_moves_after_unmute @64-164; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-161; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @122-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @154-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_tab_row_with_sound_navigation @166-266; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @176-263; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @190-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_tab_row_with_sound_mute_and_unmute @268-334; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @278-331; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @285-285; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @292-292; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @322-322; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @328-328; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/firefoxview/tests/browser/browser_tab_on_close_warning.js

Blob: `a63a55163a1751a45b0202b88b929ca3c0eff826`. Role: test-path,source. Parse: module.

- constructor @7-10; FunctionExpression; parameters=0; async=false; generator=false
- cleanup @11-13; FunctionExpression; parameters=0; async=false; generator=false
- observe @14-20; FunctionExpression; parameters=2; async=false; generator=false
- on_close_warning_should_not_show_for_firefox_view_tab @24-38; FunctionExpression; parameters=0; async=true; generator=false
- on_close_warning_should_not_show_for_firefox_view_tab_non_macos @42-59; FunctionExpression; parameters=0; async=true; generator=false
- Class DialogObserver @6-21

### browser/components/firefoxview/tests/browser/head.js

Blob: `822a9d2897d5cd130a5d9f2bd4c4df763ae8d0be`. Role: test-path,source. Parse: module.

- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testVisibility @120-135; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForElementVisible @137-156; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @150-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForVisibleSetupStep @158-188; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @170-172; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupSyncFxAMocks @193-213; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @200-200; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @201-210; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupRecentDeviceListMocks @215-245; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @217-231; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @242-242; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getMockTabData @247-249; FunctionDeclaration; parameters=1; async=false; generator=false
- setupListState @251-279; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @274-276; ArrowFunctionExpression; parameters=0; async=false; generator=false
- touchLastTabFetch @281-288; FunctionDeclaration; parameters=0; async=true; generator=false
- setupMocks @291-328; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @299-299; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @300-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @314-314; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @323-323; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @324-326; ArrowFunctionExpression; parameters=0; async=false; generator=false
- tearDown @330-333; FunctionDeclaration; parameters=1; async=true; generator=false
- open_then_close @343-345; FunctionDeclaration; parameters=2; async=true; generator=false
- clearHistory @351-353; FunctionDeclaration; parameters=0; async=false; generator=false
- cleanup_tab_pickup @359-362; FunctionDeclaration; parameters=0; async=false; generator=false
- isFirefoxViewTabSelected @364-366; FunctionDeclaration; parameters=1; async=false; generator=false
- promiseAllButPrimaryWindowClosed @368-376; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @378-382; ArrowFunctionExpression; parameters=0; async=false; generator=false
- navigateToViewAndWait @384-410; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @389-391; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @395-395; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @401-409; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @403-403; ArrowFunctionExpression; parameters=1; async=false; generator=false
- switchToFxViewTab @420-423; FunctionDeclaration; parameters=1; async=true; generator=false
- isElInViewport @425-435; FunctionDeclaration; parameters=1; async=false; generator=false
- clickFirefoxViewButton @439-445; FunctionDeclaration; parameters=1; async=true; generator=false
- setSortOption @447-453; FunctionDeclaration; parameters=2; async=false; generator=false
- navigateToOpenTabs @458-463; FunctionDeclaration; parameters=1; async=true; generator=false
- getOpenTabsCards @465-467; FunctionDeclaration; parameters=1; async=false; generator=false
- getOpenTabsComponent @469-471; FunctionDeclaration; parameters=1; async=false; generator=false
- getTabRowsForCard @473-479; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @475-475; ArrowFunctionExpression; parameters=0; async=false; generator=false
- click_recently_closed_tab_item @481-507; FunctionDeclaration; parameters=2; async=true; generator=false
- waitForRecentlyClosedTabsList @509-525; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @514-516; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @521-523; ArrowFunctionExpression; parameters=0; async=false; generator=false
- add_new_tab @527-537; FunctionDeclaration; parameters=1; async=true; generator=false
- isActiveElement @539-541; FunctionDeclaration; parameters=1; async=false; generator=false
- cleanupTabs @543-547; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://testing-common/FirefoxViewTestUtils.sys.mjs @15; ChromeUtils-import-literal
- Module resource:///modules/asrouter/ASRouter.sys.mjs @21; ChromeUtils-import-literal
- Module resource://services-sync/UIState.sys.mjs @24; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @27; ChromeUtils-import-literal
- Module resource:///modules/asrouter/FeatureCalloutMessages.sys.mjs @30; ChromeUtils-import-literal
- Module resource:///modules/OpenTabs.sys.mjs @33; ChromeUtils-import-literal
- Module resource://testing-common/SessionStoreTestUtils.sys.mjs @40; ChromeUtils-import-literal

### browser/components/firefoxview/viewpage.mjs

Blob: `36f416b0c7f1efb1fc49078deeb0842b2d2cfa5e`. Role: source. Parse: module.

- properties @33-38; FunctionExpression; parameters=0; async=false; generator=false
- constructor @39-43; FunctionExpression; parameters=0; async=false; generator=false
- ownerViewPage @45-47; FunctionExpression; parameters=0; async=false; generator=false
- isVisible @49-54; FunctionExpression; parameters=0; async=false; generator=false
- viewVisibleCallback @59-59; FunctionExpression; parameters=0; async=false; generator=false
- viewHiddenCallback @64-64; FunctionExpression; parameters=0; async=false; generator=false
- getWindow @66-68; FunctionExpression; parameters=0; async=false; generator=false
- isSelectedBrowserTab @70-73; FunctionExpression; parameters=0; async=false; generator=false
- copyLink @75-78; FunctionExpression; parameters=1; async=false; generator=false
- openInNewWindow @80-85; FunctionExpression; parameters=1; async=false; generator=false
- openInNewPrivateWindow @87-92; FunctionExpression; parameters=1; async=false; generator=false
- recordContextMenuTelemetry @94-99; FunctionExpression; parameters=3; async=false; generator=false
- shouldUpdate @101-103; FunctionExpression; parameters=1; async=false; generator=false
- properties @114-119; FunctionExpression; parameters=0; async=false; generator=false
- constructor @121-127; FunctionExpression; parameters=0; async=false; generator=false
- recentBrowsingElement @129-131; FunctionExpression; parameters=0; async=false; generator=false
- onResize @133-140; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @135-135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onTabSelect @142-156; FunctionExpression; parameters=1; async=false; generator=false
- connectedCallback @158-160; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @162-166; FunctionExpression; parameters=0; async=false; generator=false
- updateAllVirtualLists @168-194; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @173-184; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @176-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @188-192; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggleVisibilityInCardContainer @196-230; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @205-210; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @213-228; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @219-219; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @224-226; ArrowFunctionExpression; parameters=1; async=false; generator=false
- enter @232-240; FunctionExpression; parameters=0; async=false; generator=false
- exit @242-251; FunctionExpression; parameters=0; async=false; generator=false
- Class ViewPage @113-252
- Class ViewPageContent @32-104
- Module chrome://global/content/lit-utils.mjs @5; ImportDeclaration
- Module chrome://browser/content/firefoxview/card-container.mjs @8; ImportDeclaration
- Module chrome://browser/content/firefoxview/fxview-empty-state.mjs @10; ImportDeclaration
- Module chrome://browser/content/firefoxview/fxview-tab-list.mjs @12; ImportDeclaration

### browser/components/genai/GenAI.sys.mjs

Blob: `9a3f5fde05f66b8e04ac1c139d8cf5b7ddff705a`. Role: source. Parse: module.

- (anonymous) @31-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-43; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @85-85; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @99-99; ArrowFunctionExpression; parameters=3; async=false; generator=false
- currentChatProviderInfo @282-287; FunctionExpression; parameters=0; async=false; generator=false
- canOfferChatbot @297-303; FunctionExpression; parameters=0; async=false; generator=false
- canShowChatEntrypoint @308-310; FunctionExpression; parameters=0; async=false; generator=false
- canShowAIAction @315-317; FunctionExpression; parameters=0; async=false; generator=false
- canShowSelectionMenu @322-331; FunctionExpression; parameters=0; async=false; generator=false
- init @336-416; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @357-392; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setPref @380-384; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @401-406; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getProviderId @424-427; FunctionExpression; parameters=1; async=false; generator=false
- addAskChatItems @439-463; FunctionExpression; parameters=5; async=true; generator=false
- (anonymous) @454-460; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @456-459; ArrowFunctionExpression; parameters=0; async=false; generator=false
- initializeSelectionShortcutPanel @474-744; FunctionExpression; parameters=2; async=false; generator=false
- truncateSelection @502-514; ArrowFunctionExpression; parameters=1; async=false; generator=false
- panel.setSearchButtonLabel @516-540; ArrowFunctionExpression; parameters=2; async=false; generator=false
- panel.hide @546-549; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @553-555; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @556-559; ArrowFunctionExpression; parameters=0; async=false; generator=false
- roundDownToNearestHundred @563-565; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createMessageBarWarning @576-599; ArrowFunctionExpression; parameters=1; async=false; generator=false
- buildPopup @602-714; ArrowFunctionExpression; parameters=0; async=true; generator=false
- addItem @618-625; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @631-638; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @659-659; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @660-665; ArrowFunctionExpression; parameters=1; async=false; generator=false
- resetHeight @679-682; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @695-700; ArrowFunctionExpression; parameters=0; async=false; generator=false
- hasMouseoverOnPopup @717-732; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @737-743; ArrowFunctionExpression; parameters=0; async=true; generator=false
- handleShortcutsMessage @760-846; FunctionExpression; parameters=3; async=false; generator=false
- isContextTooLong @853-860; FunctionExpression; parameters=1; async=false; generator=false
- createWarningEl @869-883; FunctionExpression; parameters=3; async=false; generator=false
- isSmartWindow @891-896; FunctionExpression; parameters=1; async=false; generator=false
- isSupportedContext @906-917; FunctionExpression; parameters=1; async=false; generator=false
- canShowAskChat @926-957; FunctionExpression; parameters=4; async=false; generator=false
- buildAskChatContext @967-977; FunctionExpression; parameters=2; async=true; generator=false
- buildAskChatMenu @985-1109; FunctionExpression; parameters=2; async=true; generator=false
- addItem @1025-1028; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1032-1049; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1051-1056; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1075-1081; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1096-1108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- buildTabMenu @1119-1137; FunctionExpression; parameters=2; async=true; generator=false
- showItem @1126-1133; ArrowFunctionExpression; parameters=2; async=false; generator=false
- buildTabSummarizeItem @1149-1205; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1166-1173; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1197-1203; ArrowFunctionExpression; parameters=0; async=false; generator=false
- showItem @1213-1215; FunctionExpression; parameters=2; async=false; generator=false
- getContextualPrompts @1223-1279; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1227-1250; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1253-1253; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1254-1255; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1255-1255; ArrowFunctionExpression; parameters=1; async=false; generator=false
- estimateSelectionLimit @1289-1293; FunctionExpression; parameters=1; async=false; generator=false
- prepareChatPromptPrefix @1298-1329; FunctionExpression; parameters=0; async=true; generator=false
- buildChatPrompt @1339-1396; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1348-1386; ArrowFunctionExpression; parameters=3; async=false; generator=false
- getPageUrl @1405-1419; FunctionExpression; parameters=1; async=false; generator=false
- addPageContext @1429-1433; FunctionExpression; parameters=2; async=false; generator=false
- summarizeCurrentPage @1441-1457; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1450-1454; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setupAutoSubmit @1466-1542; FunctionExpression; parameters=3; async=false; generator=false
- sendAutoSubmit @1467-1481; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onStateChange @1485-1502; FunctionExpression; parameters=3; async=true; generator=false
- onLocationChange @1519-1533; FunctionExpression; parameters=4; async=true; generator=false
- handleAskChat @1550-1676; FunctionExpression; parameters=2; async=true; generator=false
- id @1678-1680; FunctionExpression; parameters=0; async=false; generator=false
- hasDistinctEnabledState @1682-1686; FunctionExpression; parameters=0; async=false; generator=false
- isBlocked @1688-1690; FunctionExpression; parameters=0; async=false; generator=false
- isEnabled @1692-1694; FunctionExpression; parameters=0; async=false; generator=false
- isAllowed @1696-1698; FunctionExpression; parameters=0; async=false; generator=false
- canRunOnDevice @1700-1703; FunctionExpression; parameters=0; async=false; generator=false
- isManagedByPolicy @1705-1711; FunctionExpression; parameters=0; async=false; generator=false
- makeAvailable @1713-1720; FunctionExpression; parameters=0; async=true; generator=false
- enable @1722-1727; FunctionExpression; parameters=0; async=true; generator=false
- block @1729-1733; FunctionExpression; parameters=0; async=true; generator=false
- onChatEnabledChange @1743-1754; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1745-1752; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChatProviderChange @1761-1775; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1772-1774; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChatShortcutsChange @1782-1792; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1784-1790; ArrowFunctionExpression; parameters=1; async=false; generator=false
- reorderChatProviders @1797-1822; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1805-1805; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1809-1817; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1820-1820; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1821-1821; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateIgnoredInputs @1827-1832; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @1830-1830; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @7; ImportDeclaration
- Module resource://gre/modules/XPCOMUtils.sys.mjs @8; ImportDeclaration
- Module chrome://global/content/ml/AIFeature.sys.mjs @9; ImportDeclaration

### browser/components/genai/GenAIChild.sys.mjs

Blob: `ff3ebf13c8780de43eee685f78e8aa9a8a92bad5`. Role: source. Parse: module.

- registerHideEvents @38-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeHideEvents @48-57; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @52-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleEvent @59-148; FunctionExpression; parameters=1; async=false; generator=false
- sendHide @60-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getSelectionInfo @155-182; FunctionExpression; parameters=0; async=false; generator=false
- receiveMessage @191-198; FunctionExpression; parameters=1; async=true; generator=false
- findTextareaEl @207-219; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @216-216; ArrowFunctionExpression; parameters=1; async=false; generator=false
- autoSubmitClick @226-297; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @234-235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @250-250; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @274-290; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @295-295; ArrowFunctionExpression; parameters=0; async=false; generator=false
- didDestroy @299-301; FunctionExpression; parameters=0; async=false; generator=false
- Class GenAIChild @26-302
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration

### browser/components/genai/GenAIParent.sys.mjs

Blob: `78ffcdac008ad9329cc8c10310e98c3535b2edb7`. Role: source. Parse: module.

- receiveMessage @14-20; FunctionExpression; parameters=1; async=false; generator=false
- Class GenAIParent @13-21

### browser/components/genai/LinkPreview.sys.mjs

Blob: `deaead5da0781ec3fe74cfdc3d37d6db38290858`. Role: source. Parse: module.

- (anonymous) @25-26; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @99-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @111-111; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @129-129; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @136-136; ArrowFunctionExpression; parameters=3; async=false; generator=false
- id @156-158; FunctionExpression; parameters=0; async=false; generator=false
- hasDistinctEnabledState @160-165; FunctionExpression; parameters=0; async=false; generator=false
- enable @167-170; FunctionExpression; parameters=0; async=true; generator=false
- block @172-183; FunctionExpression; parameters=0; async=true; generator=false
- makeAvailable @185-217; FunctionExpression; parameters=0; async=true; generator=false
- isEnabled @219-230; FunctionExpression; parameters=0; async=false; generator=false
- isAllowed @232-234; FunctionExpression; parameters=0; async=false; generator=false
- canRunOnDevice @236-239; FunctionExpression; parameters=0; async=false; generator=false
- isBlocked @241-243; FunctionExpression; parameters=0; async=false; generator=false
- isManagedByPolicy @245-250; FunctionExpression; parameters=0; async=false; generator=false
- _getTabContextValue @261-268; FunctionExpression; parameters=1; async=false; generator=false
- canShowKeyPoints @270-277; FunctionExpression; parameters=0; async=false; generator=false
- canShowLegacy @279-281; FunctionExpression; parameters=0; async=false; generator=false
- canShowPreferences @283-286; FunctionExpression; parameters=0; async=false; generator=false
- showOnboarding @288-290; FunctionExpression; parameters=0; async=false; generator=false
- shouldShowContextMenu @292-306; FunctionExpression; parameters=1; async=false; generator=false
- onShiftPrefChange @313-316; FunctionExpression; parameters=1; async=false; generator=false
- onShiftAltPrefChange @323-329; FunctionExpression; parameters=1; async=false; generator=false
- onLongPressPrefChange @336-342; FunctionExpression; parameters=1; async=false; generator=false
- onEnabledPref @350-368; FunctionExpression; parameters=1; async=false; generator=false
- updateCardProperty @376-388; FunctionExpression; parameters=2; async=false; generator=false
- onOptinPref @396-406; FunctionExpression; parameters=1; async=false; generator=false
- onCollapsedPref @414-426; FunctionExpression; parameters=1; async=false; generator=false
- handleNimbusPrefs @431-481; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @459-480; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setPref @469-475; ArrowFunctionExpression; parameters=1; async=false; generator=false
- init @488-521; FunctionExpression; parameters=1; async=false; generator=false
- teardown @529-541; FunctionExpression; parameters=1; async=false; generator=false
- _addEventListeners @548-553; FunctionExpression; parameters=1; async=false; generator=false
- _removeEventListeners @560-568; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @576-593; FunctionExpression; parameters=1; async=false; generator=false
- _onKeyEvent @600-624; FunctionExpression; parameters=1; async=false; generator=false
- _onLinkPreview @633-651; FunctionExpression; parameters=1; async=false; generator=false
- _maybeOnboard @653-683; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @675-682; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderOnboardingPanel @692-735; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @721-727; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @729-731; ArrowFunctionExpression; parameters=0; async=false; generator=false
- initOrResetPreviewPanel @745-799; FunctionExpression; parameters=2; async=false; generator=false
- openPopup @772-777; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @782-795; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _onPressEvent @806-847; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @832-835; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.cancelLongPress @838-843; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _isRegionSupported @854-861; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @857-857; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _isLocaleSupported @868-875; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @871-871; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @874-874; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _isDisabledByPolicy @882-886; FunctionExpression; parameters=0; async=false; generator=false
- createOGCard @899-942; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @904-907; ArrowFunctionExpression; parameters=0; async=false; generator=false
- updateProgress @914-923; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @919-919; ArrowFunctionExpression; parameters=0; async=false; generator=false
- generateKeyPoints @950-1034; FunctionExpression; parameters=2; async=true; generator=false
- addKeyPoint @961-961; FunctionExpression; parameters=0; async=false; generator=false
- onDownload @991-998; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onError @999-1013; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onText @1014-1019; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _handleKeyPointsGenerationEvent @1044-1050; FunctionExpression; parameters=1; async=false; generator=false
- renderLinkPreviewPanel @1059-1157; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @1127-1134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1136-1143; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1145-1150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _maybeLinkPreview @1166-1181; FunctionExpression; parameters=1; async=false; generator=false
- handleContextMenuClick @1190-1193; FunctionExpression; parameters=2; async=true; generator=false
- _updateShortcutMetric @1201-1213; FunctionExpression; parameters=0; async=false; generator=false
- uninstallModel @1224-1238; FunctionExpression; parameters=0; async=true; generator=false
- Module chrome://global/content/ml/AIFeature.sys.mjs @6; ImportDeclaration
- Module resource://gre/modules/XPCOMUtils.sys.mjs @7; ImportDeclaration

### browser/components/genai/LinkPreviewChild.sys.mjs

Blob: `b81f09eec612421a783e3cb526909e1390e8a148`. Role: source. Parse: module.

- receiveMessage @29-35; FunctionExpression; parameters=1; async=true; generator=false
- fetchHTML @44-134; FunctionExpression; parameters=1; async=false; generator=false
- onDataAvailable @76-83; ArrowFunctionExpression; parameters=4; async=false; generator=false
- onStartRequest @84-108; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onStopRequest @109-131; ArrowFunctionExpression; parameters=2; async=false; generator=false
- sniffCharset @147-204; FunctionExpression; parameters=2; async=false; generator=false
- normalizeAndValidateEncodingLabel @212-224; FunctionExpression; parameters=1; async=false; generator=false
- fetchPageData @232-265; FunctionExpression; parameters=1; async=true; generator=false
- extractNormalizedMetadata @278-303; FunctionExpression; parameters=2; async=false; generator=false
- extractUrlComponents @311-332; FunctionExpression; parameters=1; async=false; generator=false
- parseMetaTagsFromDoc @341-374; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @357-366; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getArticleDataFromDoc @382-425; FunctionExpression; parameters=1; async=true; generator=false
- Class LinkPreviewChild @20-426

### browser/components/genai/LinkPreviewModel.sys.mjs

Blob: `55441406dd7dbee166df3f64616df8a12535db6e`. Role: source. Parse: module.

- sha256Hex @71-77; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @75-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- runSmokeTest @95-137; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @198-203; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @221-226; ArrowFunctionExpression; parameters=1; async=false; generator=false
- id @237-239; FunctionExpression; parameters=0; async=false; generator=false
- engineId @241-243; FunctionExpression; parameters=0; async=false; generator=false
- getBlockTokenList @250-252; FunctionExpression; parameters=0; async=false; generator=false
- getSentences @259-397; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @378-385; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @391-391; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @394-395; ArrowFunctionExpression; parameters=1; async=false; generator=false
- preprocessText @406-441; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @415-429; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @423-423; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @433-436; ArrowFunctionExpression; parameters=1; async=false; generator=false
- createEngine @451-453; FunctionExpression; parameters=3; async=true; generator=false
- generateTextAI @465-589; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @474-479; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @532-539; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @637-643; FunctionExpression; parameters=1; async=false; generator=false
- initialize @653-673; FunctionExpression; parameters=1; async=true; generator=false
- put @685-730; FunctionExpression; parameters=1; async=false; generator=false
- flush @738-740; FunctionExpression; parameters=0; async=false; generator=false
- Class SentencePostProcessor @599-741
- Module resource://gre/modules/XPCOMUtils.sys.mjs @6; ImportDeclaration

### browser/components/genai/LinkPreviewParent.sys.mjs

Blob: `88ba844c635e691ad6385e15826ec452d33e7e1b`. Role: source. Parse: module.

- fetchPageData @9-11; FunctionExpression; parameters=1; async=true; generator=false
- Class LinkPreviewParent @8-12

### browser/components/genai/PageAssist.sys.mjs

Blob: `5b58d90213748e97a82b96c036e289bce0628070`. Role: source. Parse: module.

- fetchAiResponse @25-39; FunctionExpression; parameters=2; async=true; generator=false

### browser/components/genai/PageAssistChild.sys.mjs

Blob: `5b4d83d383cf3d6b5b9ef0aec6c34665c71a9083`. Role: source. Parse: module.

- receiveMessage @15-23; FunctionExpression; parameters=1; async=true; generator=false
- getPageData @37-68; FunctionExpression; parameters=0; async=true; generator=false
- Class PageAssistChild @14-69

### browser/components/genai/PageAssistParent.sys.mjs

Blob: `2d921a71eb71052f64bb57d398fcaf4b5781b7e2`. Role: source. Parse: module.

- fetchPageData @21-23; FunctionExpression; parameters=0; async=true; generator=false
- Class PageAssistParent @8-24

### browser/components/genai/chat.js

Blob: `4ecfb821003054875ed7ba9af3b7d2b45d0c21b8`. Role: source. Parse: module.

- (anonymous) @107-108; ArrowFunctionExpression; parameters=0; async=false; generator=false
- closeSidebar @113-121; FunctionDeclaration; parameters=0; async=false; generator=false
- openLink @123-127; FunctionDeclaration; parameters=1; async=false; generator=false
- request @129-139; FunctionDeclaration; parameters=1; async=false; generator=false
- renderChat @141-151; FunctionDeclaration; parameters=0; async=false; generator=false
- renderProviders @153-209; FunctionDeclaration; parameters=0; async=true; generator=false
- addOption @163-168; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @171-179; ArrowFunctionExpression; parameters=2; async=false; generator=false
- renderMore @211-292; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @213-291; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @222-224; ArrowFunctionExpression; parameters=0; async=false; generator=false
- reload @239-241; FunctionExpression; parameters=0; async=false; generator=false
- show_shortcuts @247-249; FunctionExpression; parameters=0; async=false; generator=false
- hide_shortcuts @255-257; FunctionExpression; parameters=0; async=false; generator=false
- about @264-266; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @268-287; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @274-280; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleChange @294-317; FunctionDeclaration; parameters=1; async=false; generator=false
- updateSummarizeButton @321-325; FunctionDeclaration; parameters=0; async=false; generator=false
- onLocationChange @328-332; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @336-374; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @337-373; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @343-348; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @351-359; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @376-385; ArrowFunctionExpression; parameters=0; async=false; generator=false
- showOnboarding @392-587; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @419-423; ArrowFunctionExpression; parameters=2; async=false; generator=false
- AWEvaluateScreenTargeting @427-429; FunctionExpression; parameters=1; async=false; generator=false
- AWFinish @430-448; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @445-447; ArrowFunctionExpression; parameters=1; async=false; generator=false
- AWGetFeatureConfig @449-469; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @453-458; ArrowFunctionExpression; parameters=1; async=false; generator=false
- AWGetInstalledAddons @470-470; FunctionExpression; parameters=0; async=false; generator=false
- AWGetSelectedTheme @471-476; FunctionExpression; parameters=0; async=false; generator=false
- AWSendEventTelemetry @477-512; FunctionExpression; parameters=1; async=false; generator=false
- AWSendToParent @513-585; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @543-551; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleLink @565-571; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @590-592; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @594-595; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @13; ChromeUtils-import-literal

### browser/components/genai/content/chatbot-promo.mjs

Blob: `62dd01ba515020c05a4be7ded7ec32662b4b25ff`. Role: source. Parse: module.

- onVisibilityChange @38-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @40-43; FunctionExpression; parameters=0; async=false; generator=false
- updated @45-59; FunctionExpression; parameters=1; async=false; generator=false
- disconnectedCallback @61-67; FunctionExpression; parameters=0; async=false; generator=false
- maybeFireImpression @69-83; FunctionExpression; parameters=0; async=false; generator=false
- dispatch @85-89; FunctionExpression; parameters=1; async=false; generator=false
- handlePrimary @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleClose @93-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- render @95-131; FunctionExpression; parameters=0; async=false; generator=false
- Class ChatbotPromo @32-132
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @6; ImportDeclaration
- Module chrome://global/content/elements/moz-promo.mjs @8; ImportDeclaration
- Module resource:///modules/asrouter/SidebarChatBotPromo.sys.mjs @18; ChromeUtils-import-literal

### browser/components/genai/content/chatbot-promo.stories.mjs

Blob: `4867a05329536064c0852e89e5e4deb29fa950dc`. Role: source. Parse: module.

- Template @29-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @48-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://browser/content/genai/content/chatbot-promo.mjs @7; ImportDeclaration

### browser/components/genai/content/link-preview-card-onboarding.mjs

Blob: `64befe6af09beec4fd99ce19d19fb8f1ef987ab5`. Role: source. Parse: module.

- properties @19-23; FunctionExpression; parameters=0; async=false; generator=false
- constructor @25-28; FunctionExpression; parameters=0; async=false; generator=false
- handleTryLinkPreview @35-37; FunctionExpression; parameters=1; async=false; generator=false
- handleCloseOnboarding @44-46; FunctionExpression; parameters=1; async=false; generator=false
- render @53-94; FunctionExpression; parameters=0; async=false; generator=false
- Class LinkPreviewCardOnboarding @18-95
- Module chrome://global/content/vendor/lit.all.mjs @7; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @8; ImportDeclaration

### browser/components/genai/content/link-preview-card.mjs

Blob: `0469e94e30ea9cfcba7c21347f16e44012583805`. Role: source. Parse: module.

- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @63-74; FunctionExpression; parameters=0; async=false; generator=false
- handleSettingsClick @84-92; FunctionExpression; parameters=1; async=false; generator=false
- addKeyPoint @94-97; FunctionExpression; parameters=1; async=false; generator=false
- handleLink @104-127; FunctionExpression; parameters=1; async=false; generator=false
- handleRetry @134-138; FunctionExpression; parameters=1; async=false; generator=false
- toggleKeyPoints @145-160; FunctionExpression; parameters=1; async=false; generator=false
- updated @162-177; FunctionExpression; parameters=1; async=false; generator=false
- errorMessageL10nId @184-191; FunctionExpression; parameters=0; async=false; generator=false
- renderErrorGenerationCard @198-225; FunctionExpression; parameters=0; async=false; generator=false
- renderOptInPlaceholderCard @233-272; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @259-264; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderNormalGenerationCard @280-360; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @308-308; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @322-331; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderModelOptIn @369-382; FunctionExpression; parameters=0; async=false; generator=false
- renderModalFirstTime @390-405; FunctionExpression; parameters=0; async=false; generator=false
- _handleOptinConfirm @412-416; FunctionExpression; parameters=0; async=false; generator=false
- _handleCancelDownload @421-423; FunctionExpression; parameters=0; async=false; generator=false
- _handleOptinDeny @430-435; FunctionExpression; parameters=0; async=false; generator=false
- renderKeyPointsSection @443-463; FunctionExpression; parameters=1; async=false; generator=false
- render @470-589; FunctionExpression; parameters=0; async=false; generator=false
- Class LinkPreviewCard @46-590
- Module chrome://global/content/vendor/lit.all.mjs @7; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @12; ImportDeclaration
- Module chrome://browser/content/genai/content/model-optin.mjs @32; ChromeUtils-import-literal

### browser/components/genai/content/model-optin.mjs

Blob: `a44a7c788a221b976ecabf0ef37ff33a67c3da13`. Role: source. Parse: module.

- constructor @42-51; FunctionExpression; parameters=0; async=false; generator=false
- dispatch @53-57; FunctionExpression; parameters=1; async=false; generator=false
- handleConfirmClick @59-61; FunctionExpression; parameters=0; async=false; generator=false
- handleDenyClick @63-66; FunctionExpression; parameters=0; async=false; generator=false
- handleCancelDownloadClick @68-72; FunctionExpression; parameters=0; async=false; generator=false
- handleMessageLinkClick @74-80; FunctionExpression; parameters=1; async=false; generator=false
- handleFooterLinkClick @82-88; FunctionExpression; parameters=1; async=false; generator=false
- render @90-182; FunctionExpression; parameters=0; async=false; generator=false
- Class ModelOptin @14-183
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @6; ImportDeclaration

### browser/components/genai/content/page-assist.mjs

Blob: `b03ddf77300d43aa91b167148ab645b48ed878ab`. Role: source. Parse: module.

- inputTemplate @27-48; FunctionExpression; parameters=0; async=false; generator=false
- constructor @71-80; FunctionExpression; parameters=0; async=false; generator=false
- _browserWin @82-84; FunctionExpression; parameters=0; async=false; generator=false
- _gBrowser @85-87; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @89-98; FunctionExpression; parameters=0; async=false; generator=false
- ?._onUnload @93-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @100-112; FunctionExpression; parameters=0; async=false; generator=false
- _setupFinder @114-141; FunctionExpression; parameters=0; async=false; generator=false
- _cleanup @143-168; FunctionExpression; parameters=0; async=false; generator=false
- _attachReaderModeListener @170-188; FunctionExpression; parameters=0; async=false; generator=false
- receiveMessage @172-181; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _initURLChange @193-218; FunctionExpression; parameters=0; async=false; generator=false
- ?._onTabSelect @199-203; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onLocationChange @207-212; ArrowFunctionExpression; parameters=2; async=false; generator=false
- _fetchPageData @233-246; FunctionExpression; parameters=0; async=true; generator=false
- _clearFinder @248-256; FunctionExpression; parameters=0; async=false; generator=false
- _handlePromptInput @258-281; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onMatchesCountResult @283-287; FunctionExpression; parameters=1; async=false; generator=false
- onHighlightFinished @290-292; FunctionExpression; parameters=0; async=false; generator=false
- onFindResult @295-306; FunctionExpression; parameters=1; async=false; generator=false
- _handleSubmit @308-319; ArrowFunctionExpression; parameters=0; async=true; generator=false
- render @321-373; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @361-364; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class PageAssist @55-374
- Class PageAssistInput @22-49
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @6; ImportDeclaration
- Module chrome://browser/content/sidebar/sidebar-panel-header.mjs @9; ImportDeclaration
- Module chrome://global/content/elements/moz-input-text.mjs @17; ImportDeclaration

### browser/components/genai/tests/browser/browser_chat_contextmenu.js

Blob: `b754f9e1a3ae6b68d7f6ee560c8846dc958dd995`. Role: test-path,source. Parse: module.

- openContextMenu @5-16; FunctionDeclaration; parameters=1; async=true; generator=false
- hideContextMenu @18-23; FunctionDeclaration; parameters=1; async=true; generator=false
- waitMenuState @25-29; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @26-28; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @31-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_hidden_menu @38-60; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @43-57; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_menu_enabled @65-84; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @69-83; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_remove_option @89-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @91-118; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_hidden_in_popup @125-143; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @126-142; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @128-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_visible_in_smart_window @149-215; FunctionExpression; parameters=0; async=true; generator=false
- hasAttribute @162-162; ArrowFunctionExpression; parameters=1; async=false; generator=false
- buildMenu @164-182; ArrowFunctionExpression; parameters=2; async=true; generator=false
- showItem @175-177; ArrowFunctionExpression; parameters=2; async=false; generator=false
- hasAttribute @190-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_smart_window_sidebar_ask_chat @220-275; FunctionExpression; parameters=0; async=true; generator=false
- hasAttribute @244-244; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_open_tab @280-301; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @288-300; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @291-292; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_sidebar @306-342; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @315-324; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_custom_prompt @347-377; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @356-368; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @157; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @225; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @228; ChromeUtils-import-literal
- Module moz-src:///browser/components/aiwindow/ui/modules/AIWindowUI.sys.mjs @231; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_nimbus.js

Blob: `37b07d922fa57836306c349b7b43fcaa6e29fb3a`. Role: test-path,source. Parse: module.

- test_nimbus_user_prefs @11-82; FunctionExpression; parameters=0; async=true; generator=false
- test_nimbus_default_prefs @87-113; FunctionExpression; parameters=0; async=true; generator=false
- test_nimbus_rollout_experiment @118-165; FunctionExpression; parameters=0; async=true; generator=false
- test_nimbus_minimum_version @170-211; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/NimbusTestUtils.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_page.js

Blob: `9a36dad98ef0ffc0501c84b6803e393739125367`. Role: test-path,source. Parse: module.

- (anonymous) @15-18; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openContextMenu @21-59; FunctionDeclaration; parameters=1; async=true; generator=false
- hideContextMenu @61-66; FunctionDeclaration; parameters=1; async=true; generator=false
- runContextMenuTest @68-99; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @84-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertContextMenuStubResult @101-110; FunctionDeclaration; parameters=1; async=false; generator=false
- test_page_and_tab_menu_prompt @118-167; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @134-163; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_summarize_page_button_is_disabled_in_menu @173-188; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @174-187; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @177-180; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_page_menu_no_chatbot @193-265; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @198-264; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @201-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_menu_has_label_and_separator @271-320; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @285-288; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @309-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_menu_page_feature_with_provider_or_menu @325-409; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @343-345; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @371-373; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @399-401; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_menu_no_chatbot @415-459; FunctionExpression; parameters=0; async=true; generator=false
- test_toggle_new_badge @464-500; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @491-491; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_click_summarize_button @505-529; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @516-519; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_summarize_button_disabled_without_url @534-564; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @547-560; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_provider_less_summarization @569-605; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @577-604; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @582-582; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @592-592; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @598-598; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_menu_on_unloaded @607-646; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @634-637; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @636-636; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_promo.js

Blob: `39ed6742ce986c667b4e32c56459eb7898b7a020`. Role: test-path,source. Parse: module.

- stubMessage @53-72; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @56-66; ArrowFunctionExpression; parameters=1; async=true; generator=false
- fireTrigger @74-80; FunctionDeclaration; parameters=1; async=false; generator=false
- getSidebarDoc @82-84; FunctionDeclaration; parameters=1; async=false; generator=false
- getPromo @86-94; FunctionDeclaration; parameters=1; async=false; generator=false
- isPromoShowing @96-99; FunctionDeclaration; parameters=1; async=false; generator=false
- waitForPromo @109-115; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openChatSidebar @117-124; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @120-120; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @126-138; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @135-137; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @140-298; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @143-147; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-152; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @154-218; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @155-175; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @177-201; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @186-186; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-217; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @220-278; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @223-229; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @231-253; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @255-277; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @280-297; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @283-296; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @293-293; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/Sinon.sys.mjs @6; ChromeUtils-import-literal
- Module resource:///modules/asrouter/ASRouter.sys.mjs @9; ChromeUtils-import-literal
- Module resource://messaging-system/lib/SpecialMessageActions.sys.mjs @12; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_prompt.js

Blob: `723eb5ec5507308ce09a463c87a5ea7f37210ae9`. Role: test-path,source. Parse: module.

- (anonymous) @8-13; FunctionExpression; parameters=0; async=true; generator=false
- test_basic_prompt @18-39; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_placeholders @44-75; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_placeholder_options @80-96; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_prefix @101-123; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_prefix_localization @128-144; FunctionExpression; parameters=0; async=true; generator=false
- test_estimate_limit @149-169; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_limit @174-189; FunctionExpression; parameters=0; async=true; generator=false
- getLength @175-175; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_chat_request_sanitizes_and_truncates_tabTitle @194-238; FunctionExpression; parameters=0; async=true; generator=false
- test_page_prompt_uses_page_URL @243-268; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @251-251; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_custom_page_prompt_includes_a_URL @270-298; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @286-286; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_get_page_url_is_valid @303-334; FunctionExpression; parameters=0; async=false; generator=false
- getPageUrl @304-305; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_request.js

Blob: `020c0fa0d9221dd6acd48cc28a533d824c260dd1`. Role: test-path,source. Parse: module.

- test_chat_header @17-50; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_chat_query_param @55-81; FunctionExpression; parameters=0; async=true; generator=false
- test_chat_default_query @86-106; FunctionExpression; parameters=0; async=true; generator=false
- test_chat_no_query_when_auto_submit @112-138; FunctionExpression; parameters=0; async=true; generator=false
- test_chat_auto_submit @143-193; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @161-171; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @163-163; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @173-181; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @174-180; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-190; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/httpd.sys.mjs @7; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @10; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_shortcuts.js

Blob: `a5c80c502c7c2d8ac965c3268da39bd0dc704d38`. Role: test-path,source. Parse: module.

- test_no_shortcuts @20-37; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @24-36; ArrowFunctionExpression; parameters=1; async=true; generator=false
- selectAllAndMouseUp @39-51; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @41-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- showSelectionMenu @53-63; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_show_menu_without_provider @69-96; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @80-87; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_selection_menu_position_with_rtl_app_locale @98-155; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @109-148; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @111-111; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @116-117; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-117; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @131-131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_menu_when_chatbot_blocked @161-191; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @171-186; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @175-175; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_menu_in_unsupported_context @197-224; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @206-219; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @210-210; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_smart_window_ask_chat @229-324; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @258-260; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @259-259; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @273-273; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @287-287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_smart_window_ask_chat_ignores_classic_toggle @330-376; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @350-352; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @351-351; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @365-365; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_ai_action_dropdown @382-506; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @391-503; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @393-394; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @394-394; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @406-406; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @448-448; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @461-461; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @487-487; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @497-497; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_selection_menu_events @512-561; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @522-558; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_show_shortcuts @566-716; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @576-715; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @578-580; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @579-579; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @589-594; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @695-695; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_show_shortcuts_second_tab @721-762; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @731-760; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @733-735; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @734-734; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @744-749; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_show_warning_label @767-854; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @774-852; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @776-778; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @777-777; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_plain_clicks @859-901; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @870-896; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @877-877; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_input_selection @906-953; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @926-949; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @927-931; ArrowFunctionExpression; parameters=0; async=false; generator=false
- showCalls @938-939; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @939-939; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @940-940; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_panel_actions_layout @955-1061; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @963-1058; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @966-968; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @967-967; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @979-979; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @985-985; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1011-1011; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_panel_opens_without_search_service @1063-1105; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1074-1074; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1078-1102; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1093-1093; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_ime_composition_hides_panel @1110-1166; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1118-1163; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1121-1123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1122-1122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1134-1134; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1142-1152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1155-1155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal
- Module moz-src:///browser/components/aiwindow/ui/modules/AIWindowUI.sys.mjs @10; ChromeUtils-import-literal
- Module moz-src:///toolkit/components/search/SearchService.sys.mjs @13; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_sidebar.js

Blob: `0538f44457c63f1a6b2b029dafa8db41f044fe57`. Role: test-path,source. Parse: module.

- (anonymous) @15-17; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_sidebar_render @22-64; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_providers @69-94; FunctionExpression; parameters=0; async=true; generator=false
- countVisible @70-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @75-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_sidebar_onboarding @99-185; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @105-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @128-128; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @132-133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @147-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-165; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_switch_from_chat_onboarding @187-234; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @204-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @217-217; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @219-220; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_custom_onboarding @239-280; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @261-262; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_menu @285-347; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @300-301; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_no_history @352-358; FunctionExpression; parameters=0; async=true; generator=false
- test_keyboard_shortcut @363-406; FunctionExpression; parameters=0; async=true; generator=false
- test_pip_actor_not_chat_sidebar @411-437; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @412-436; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @419-424; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @427-430; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_browser_focus @442-450; FunctionExpression; parameters=0; async=true; generator=false
- test_webext_content_script_in_chat_sidebar @455-486; FunctionExpression; parameters=0; async=true; generator=false
- test_tab_modal_prompt_in_chat_sidebar @493-574; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @505-510; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @514-517; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @557-559; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @562-562; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @562-562; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @569-569; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://testing-common/Sinon.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_chat_sidebar_permissions.js

Blob: `b89534bc7d15f4a57b489b6525ad82e5a4f21b40`. Role: test-path,source. Parse: module.

- openSidebar @14-42; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @20-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @37-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- loadTestPageInTab @44-47; FunctionDeclaration; parameters=1; async=true; generator=false
- clickRequestMic @49-53; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @50-52; ArrowFunctionExpression; parameters=0; async=true; generator=false
- resetPermissions @55-59; FunctionDeclaration; parameters=0; async=false; generator=false
- getSidebarPermissions @61-64; FunctionDeclaration; parameters=1; async=false; generator=false
- dismissPopupNotification @66-78; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @80-89; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @91-111; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_sidebar_granted_perm_skip_popup @113-144; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_shows_popup_and_blocked_permission_ui @146-176; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @166-172; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @170-170; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_open_sidebar_requests @182-218; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @203-203; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sidebar_open_tab_requests @224-266; FunctionExpression; parameters=0; async=true; generator=false
- test_cross_window_between_sidebar_and_sidebar_popup @273-307; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @301-301; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_cross_window_between_tab_and_sidebar_popup @314-362; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @347-347; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_provider_change_cancels_notification @367-391; FunctionExpression; parameters=0; async=true; generator=false
- test_hide_sidebar_cancels_notification @396-415; FunctionExpression; parameters=0; async=true; generator=false
- test_sharing_state_updates_ui @420-463; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @452-452; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @460-460; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/genai/tests/browser/browser_chat_telemetry.js

Blob: `34dd75972f127c841c9a7f00a4612d6a7c718b74`. Role: test-path,source. Parse: module.

- (anonymous) @11-13; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_default_telemetry @18-91; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_telemetry_change @96-133; FunctionExpression; parameters=0; async=true; generator=false
- test_summarize_telemetry @138-167; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @147-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_genai_actors.js

Blob: `5dc982c03fc84bc43e77fefe05a500b1d09ee747`. Role: test-path,source. Parse: module.

- test_got_actor @7-17; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @11-16; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_actor_disabled @22-39; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-37; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @33-33; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/genai/tests/browser/browser_genai_init.js

Blob: `b72c89f27e7fae74405c4715de2937096e0c7786`. Role: test-path,source. Parse: module.

- test_chat_autoopen @14-24; FunctionExpression; parameters=0; async=true; generator=false
- test_chat_autoclose @29-37; FunctionExpression; parameters=0; async=true; generator=false
- test_chat_no_open @42-51; FunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview.js

Blob: `66980d76742b51a4684ebfd8e8d24f633a1ba4d9`. Role: test-path,source. Parse: module.

- (anonymous) @30-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_skip_generate_if_non_eng @45-104; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-65; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_with_shift_alt_key_event @116-180; FunctionExpression; parameters=0; async=true; generator=false
- test_link_preview_with_long_press @185-242; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @229-229; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_with_typing @247-308; FunctionExpression; parameters=0; async=true; generator=false
- test_link_preview_no_trigger @313-355; FunctionExpression; parameters=0; async=true; generator=false
- test_no_event_triggered_when_disabled_with_alt_key @366-391; FunctionExpression; parameters=0; async=true; generator=false
- test_fetch_page_data @396-439; FunctionExpression; parameters=0; async=true; generator=false
- test_fetch_shift_jis @444-460; FunctionExpression; parameters=0; async=true; generator=false
- test_fetch_errors @465-498; FunctionExpression; parameters=0; async=true; generator=false
- test_link_preview_panel_shown @503-605; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @512-516; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @524-525; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_reader_mode_blocked_domains @610-663; FunctionExpression; parameters=0; async=true; generator=false
- fetchHTML @615-621; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @625-629; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_skip_keypoints_generation_if_url_not_readable @668-707; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @685-686; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_key_points_in_disallowed_region @722-763; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @740-741; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_key_points_on_unsupported_hardware @770-818; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @775-775; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @789-790; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_error_rendered @824-914; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @837-838; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @871-872; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @885-886; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @903-904; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_settings_icon_rendered @919-975; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @935-935; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @944-947; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_toggle_expand_collapse @981-1065; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @998-999; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_key_points_in_unsupported_locale @1070-1108; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1089-1090; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_key_points_in_supported_locale @1113-1155; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1132-1133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @4; ChromeUtils-import-literal
- Module chrome://global/content/ml/Utils.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/Region.sys.mjs @10; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/LinkPreviewModel.sys.mjs @13; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/LinkPreviewChild.sys.mjs @17; ChromeUtils-import-literal
- Module resource://gre/modules/Readerable.sys.mjs @21; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @25; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview_aifeature_lifecycle.js

Blob: `c9af178f3af6ab581e95df84ee5f156bdcaea2ac`. Role: test-path,source. Parse: module.

- test_aifeature_id @21-23; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_enable @28-55; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_disable @60-109; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_reset @114-179; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_isEnabled @184-220; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_isAllowed @225-251; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_isAllowed_unsupported_region @256-282; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_isAllowed_unsupported_locale @287-313; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_canRunOnDevice_unsupported @319-342; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @330-330; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_aifeature_isAllowed_policy_disabled @347-381; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_isBlocked @386-407; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_disable_enable_workflow @412-445; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_disable_calls_uninstall @450-470; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_reset_calls_uninstall @475-495; FunctionExpression; parameters=0; async=true; generator=false
- test_pref_change_no_uninstall @500-521; FunctionExpression; parameters=0; async=true; generator=false
- test_aifeature_sequential_enable_disable @526-551; FunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @4; ChromeUtils-import-literal
- Module chrome://global/content/ml/Utils.sys.mjs @7; ChromeUtils-import-literal
- Module chrome://global/content/ml/EngineProcess.sys.mjs @10; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @14; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview_nimbus.js

Blob: `fb6ad7886a171f7c5f7daca9b65d7e5e6b107815`. Role: test-path,source. Parse: module.

- test_nimbus_user_prefs @14-81; FunctionExpression; parameters=0; async=true; generator=false
- test_nimbus_default_prefs @86-112; FunctionExpression; parameters=0; async=true; generator=false
- test_nimbus_rollout_experiment @117-156; FunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @4; ChromeUtils-import-literal
- Module resource://testing-common/NimbusTestUtils.sys.mjs @7; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview_optin.js

Blob: `ec82f2cde765b4697a371bb2595c9034002ebe44`. Role: test-path,source. Parse: module.

- (anonymous) @18-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_pref_updates_existing_cards @27-67; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_keypoints_when_optin_false @75-108; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @91-92; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_keypoints_when_collapsed_true @117-154; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @134-135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_generate_keypoints_when_opted_in @162-228; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @174-178; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @186-187; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_keypoints_when_opted_in_but_collapsed @236-273; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @253-254; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_model_optin_deny_action @281-362; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @298-299; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @325-330; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_model_optin_confirm_action @370-455; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @387-388; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @414-419; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @441-441; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_optin_or_keypoints_in_disallowed_region @465-509; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @485-486; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_locked_preference @515-560; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @534-535; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_optin_or_keypoints_in_unsupported_locale @569-614; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @589-590; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @4; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/LinkPreviewModel.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/Region.sys.mjs @10; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @13; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview_perf.js

Blob: `3849f40ba8fadcbae273614f58048af1d8713b28`. Role: test-path,source. Parse: module.

- (anonymous) @145-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setupLinkPreview @149-161; FunctionDeclaration; parameters=0; async=true; generator=false
- generateKeyPointsOnce @165-226; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @179-179; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- card.addKeyPoint @191-194; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @198-198; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_keypoints_perf @228-241; FunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @15; ChromeUtils-import-literal
- Module resource://testing-common/MLPerfTestUtils.sys.mjs @18; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_link_preview_telemetry.js

Blob: `ff2039d5a9e77a885103f9af6fea9be7bb127efb`. Role: test-path,source. Parse: module.

- clearOverlink @22-25; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForPanelOpen @27-32; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @28-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_default_telemetry @34-65; FunctionExpression; parameters=0; async=true; generator=false
- test_link_preview_ai_consent_continue_ui_interaction @70-144; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @109-114; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_link_preview_ai_consent_cancel_ui_interaction @149-223; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @188-193; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_toggle_expand_collapse_telemetry @231-309; FunctionExpression; parameters=0; async=true; generator=false
- test_link_preview_ai_consent_toggle_collapse_to_cancel_ui_interaction @317-394; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @355-360; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_pref_changed_event_telemetry @400-443; FunctionExpression; parameters=0; async=true; generator=false
- assertTelemetryEvents @403-423; FunctionDeclaration; parameters=3; async=false; generator=false
- test_shortcut_metric_updates @445-554; FunctionExpression; parameters=0; async=true; generator=false
- assertShortcutMetric @452-459; FunctionDeclaration; parameters=2; async=false; generator=false
- Module moz-src:///browser/components/genai/LinkPreview.sys.mjs @4; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/LinkPreviewModel.sys.mjs @9; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @13; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_page_assist_actors.js

Blob: `f79849208adcc1b6617092e719c25781a83f4bca`. Role: test-path,source. Parse: module.

- getPageAssistParentActor @32-34; FunctionDeclaration; parameters=1; async=false; generator=false
- assertCommonPageData @36-44; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @49-53; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForReaderFlag @56-61; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @58-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- loadAndAwaitReader @64-68; FunctionDeclaration; parameters=3; async=true; generator=false
- openPageAssistSidebar @75-86; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @82-82; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_page_assist_child_fetch_data @91-110; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-109; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_page_assist_sidebar_integration @115-189; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @120-186; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @126-126; ArrowFunctionExpression; parameters=0; async=false; generator=false
- PageAssist.fetchAiResponse @142-149; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @157-157; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @172-172; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @179-179; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_page_assist_actor_messages @194-203; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @197-202; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_page_assist_non_readable_page @208-229; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @211-228; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_page_assist_component_fetch_data @234-273; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @239-270; ArrowFunctionExpression; parameters=0; async=true; generator=false
- sideBarEl._fetchPageData @254-254; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @259-259; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_page_assist_is_readerable @278-306; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @280-289; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @282-282; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @293-305; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @295-297; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_page_assist_url_change_detection @311-351; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @316-348; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @321-322; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @326-326; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @338-339; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @343-343; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/PageAssist.sys.mjs @138; ChromeUtils-import-literal

### browser/components/genai/tests/browser/browser_page_assist_sidebar.js

Blob: `92120b52dd4d43e5af7184139104782aae80d0d3`. Role: test-path,source. Parse: module.

- test_sidebar_render @10-20; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/genai/tests/browser/head.js

Blob: `8e9069f84d6809ed551c2a9fa338a9c42855ae47`. Role: test-path,source. Parse: module.

- (anonymous) @4-10; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/SidebarTestUtils.sys.mjs @5; ChromeUtils-import-literal

### browser/components/genai/tests/xpcshell/test_contextual_prompts.js

Blob: `cbdeac762a4bfd052377d6d477e3e0c2693d2f7d`. Role: test-path,source. Parse: module.

- (anonymous) @8-9; ArrowFunctionExpression; parameters=0; async=false; generator=false
- promptCount @13-15; FunctionDeclaration; parameters=1; async=true; generator=false
- test_prompt_prefs @20-35; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_context @40-58; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_l10n @63-79; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/xpcshell/test_link_preview_text.js

Blob: `5f5b25efa8c99aa267e5815fe9116344aee107c2`. Role: test-path,source. Parse: module.

- test_text_processing @26-92; FunctionExpression; parameters=0; async=false; generator=false
- test_text_processing_prefs @97-150; FunctionExpression; parameters=0; async=false; generator=false
- test_sentence_post_processor @155-188; FunctionExpression; parameters=0; async=false; generator=false
- test_generateAI_with_blocklist @193-320; FunctionExpression; parameters=0; async=true; generator=false
- runWithGenerator @196-203; FunctionExpression; parameters=0; async=true; generator=true
- terminate @205-205; FunctionExpression; parameters=0; async=false; generator=false
- onText @230-232; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onText @250-252; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onText @286-288; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onText @305-307; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_sentence_post_processor_limits @325-358; FunctionExpression; parameters=0; async=false; generator=false
- test_smoke_test_skipped_when_generation_abandoned @367-449; FunctionExpression; parameters=0; async=true; generator=false
- mockEngine @371-389; FunctionDeclaration; parameters=1; async=false; generator=false
- runWithGenerator @380-385; FunctionExpression; parameters=0; async=true; generator=true
- terminate @386-386; FunctionExpression; parameters=0; async=false; generator=false
- Module moz-src:///browser/components/genai/LinkPreviewModel.sys.mjs @4; ChromeUtils-import-literal
- Module moz-src:///browser/components/genai/LinkPreviewModel.sys.mjs @7; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @11; ChromeUtils-import-literal
- Module chrome://global/content/ml/Utils.sys.mjs @15; ChromeUtils-import-literal

### browser/components/genai/tests/xpcshell/test_page_assist.js

Blob: `6e266d7c5d18bf0520ef047ed1a75c6c25b53217`. Role: test-path,source. Parse: module.

- test_fetchAiResponse_no_page_data @11-18; FunctionExpression; parameters=0; async=true; generator=false
- test_fetchAiResponse_valid_page_data @23-39; FunctionExpression; parameters=0; async=true; generator=false
- Module moz-src:///browser/components/genai/PageAssist.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/xpcshell/test_provider_id.js

Blob: `ded11fd82f69fa510dcfd64bbd2b6bbe099758f3`. Role: test-path,source. Parse: module.

- (anonymous) @8-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_provider_id @16-35; FunctionExpression; parameters=0; async=true; generator=false
- test_hide_providers @40-48; FunctionExpression; parameters=0; async=true; generator=false
- test_providers_order @53-67; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @60-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal

### browser/components/genai/tests/xpcshell/test_show_chat_entrypoint.js

Blob: `8c5f0ee89794780ae83457151a03a401305f86b5`. Role: test-path,source. Parse: module.

- (anonymous) @8-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_chat_aifeature_states @20-94; FunctionExpression; parameters=0; async=true; generator=false
- test_show_chat @99-133; FunctionExpression; parameters=0; async=true; generator=false
- test_show_selection_menu @138-178; FunctionExpression; parameters=0; async=true; generator=false
- test_supported_context @183-208; FunctionExpression; parameters=0; async=true; generator=false
- fakeBrowser @184-191; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/genai/GenAI.sys.mjs @4; ChromeUtils-import-literal

### browser/components/installerprefs/InstallerPrefs.sys.mjs

Blob: `dd76d44f354b23efd523728d1ddb594cf1cce82c`. Role: source. Parse: module.

- InstallerPrefs @39-54; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @45-53; FunctionExpression; parameters=0; async=false; generator=false
- observe @62-88; FunctionExpression; parameters=3; async=false; generator=false
- _registerPrefListeners @90-92; FunctionExpression; parameters=0; async=false; generator=false
- _cleanRegistryKey @94-101; FunctionExpression; parameters=1; async=false; generator=false
- _reflectPrefsToRegistry @103-108; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @105-106; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _reflectOnePrefToRegistry @110-127; FunctionExpression; parameters=2; async=false; generator=false
- _openRegKey @129-139; FunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @34; ImportDeclaration

### browser/components/installerprefs/test/unit/head.js

Blob: `a10966dafdaa87a2b786947f5920377f43fdf7c3`. Role: test-path,source. Parse: module.

- startModule @15-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getRegistryKey @26-36; FunctionDeclaration; parameters=0; async=false; generator=false
- verifyReflectedPrefs @38-81; FunctionDeclaration; parameters=1; async=false; generator=false
- cleanupReflectedPrefs @83-136; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @85-85; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @5; ChromeUtils-import-literal
- Module moz-src:///browser/components/installerprefs/InstallerPrefs.sys.mjs @9; ChromeUtils-import-literal

### browser/components/installerprefs/test/unit/test_empty_prefs_list.js

Blob: `074d7824ba6cc3f694eb7d6e54ff19e4bfc76b11`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=0; async=false; generator=false

### browser/components/installerprefs/test/unit/test_invalid_name.js

Blob: `4fbccba8e363ff0aa04f5857e7f91f869f039f33`. Role: test-path,source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=0; async=false; generator=false

### browser/components/installerprefs/test/unit/test_nonbool_pref.js

Blob: `cbe9979f65ace159f58eb449e16a6d138414ea4b`. Role: test-path,source. Parse: module.

- (anonymous) @9-18; FunctionExpression; parameters=0; async=false; generator=false

### browser/components/installerprefs/test/unit/test_pref_change.js

Blob: `f42b8b65503506f01ce3ba2af52c797f315aade4`. Role: test-path,source. Parse: module.

- (anonymous) @9-25; FunctionExpression; parameters=0; async=false; generator=false

### browser/components/installerprefs/test/unit/test_pref_values.js

Blob: `b1154f8bc486504792df64c19f364d016d0049ab`. Role: test-path,source. Parse: module.

- (anonymous) @9-18; FunctionExpression; parameters=0; async=false; generator=false

### browser/components/ipprotection/IPPL10nHelper.sys.mjs

Blob: `fc6670193f7ecd9128ca8c17f38a4e0e5a218d10`. Role: source. Parse: module.

- init @33-38; FunctionExpression; parameters=0; async=false; generator=false
- initOnStartupCompleted @40-40; FunctionExpression; parameters=0; async=false; generator=false
- uninit @42-47; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @49-57; FunctionExpression; parameters=0; async=false; generator=false
- hidesFeature @59-79; FunctionExpression; parameters=0; async=false; generator=false
- Class IPPL10nHelperSingleton @32-80
- Module resource://gre/modules/AppConstants.sys.mjs @5; ImportDeclaration

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
