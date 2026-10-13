<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["browser/components/aboutlogins/tests/browser/AboutLoginsTestUtils.sys.mjs","browser/components/aboutlogins/tests/browser/browser_aaa_eventTelemetry_run_first.js","browser/components/aboutlogins/tests/browser/browser_alertDismissedAfterChangingPassword.js","browser/components/aboutlogins/tests/browser/browser_breachAlertLinkTelemetry.js","browser/components/aboutlogins/tests/browser/browser_breachAlertShowingForAddedLogin.js","browser/components/aboutlogins/tests/browser/browser_confirmDeleteDialog.js","browser/components/aboutlogins/tests/browser/browser_contextmenuFillLogins.js","browser/components/aboutlogins/tests/browser/browser_copyToClipboardButton.js","browser/components/aboutlogins/tests/browser/browser_createLogin.js","browser/components/aboutlogins/tests/browser/browser_deleteLogin.js","browser/components/aboutlogins/tests/browser/browser_fxAccounts.js","browser/components/aboutlogins/tests/browser/browser_loginFilter.js","browser/components/aboutlogins/tests/browser/browser_loginItemErrors.js","browser/components/aboutlogins/tests/browser/browser_loginListChanges.js","browser/components/aboutlogins/tests/browser/browser_loginSortOrderRestored.js","browser/components/aboutlogins/tests/browser/browser_noLoginsView.js","browser/components/aboutlogins/tests/browser/browser_openExport.js","browser/components/aboutlogins/tests/browser/browser_openFiltered.js","browser/components/aboutlogins/tests/browser/browser_openImport.js","browser/components/aboutlogins/tests/browser/browser_openImportCSV.js","browser/components/aboutlogins/tests/browser/browser_openPreferences.js","browser/components/aboutlogins/tests/browser/browser_openPreferencesExternal.js","browser/components/aboutlogins/tests/browser/browser_openSite.js","browser/components/aboutlogins/tests/browser/browser_osAuthDialog.js","browser/components/aboutlogins/tests/browser/browser_primaryPassword.js","browser/components/aboutlogins/tests/browser/browser_removeAllDialog.js","browser/components/aboutlogins/tests/browser/browser_sessionRestore.js","browser/components/aboutlogins/tests/browser/browser_tabKeyNav.js","browser/components/aboutlogins/tests/browser/browser_updateLogin.js","browser/components/aboutlogins/tests/browser/browser_vulnerableLoginAddedInSecondaryWindow.js","browser/components/aboutlogins/tests/browser/head.js","browser/components/aboutlogins/tests/chrome/.eslintrc.mjs","browser/components/aboutlogins/tests/chrome/aboutlogins_common.js","browser/components/aboutlogins/tests/unit/head.js","browser/components/aboutlogins/tests/unit/test_getPotentialBreachesByLoginGUID.js","browser/components/aboutwelcome/.eslintrc.mjs","browser/components/aboutwelcome/actors/AboutWelcomeChild.sys.mjs","browser/components/aboutwelcome/actors/AboutWelcomeParent.sys.mjs","browser/components/aboutwelcome/content-src/aboutwelcome.jsx","browser/components/aboutwelcome/content/aboutwelcome.bundle.js","browser/components/aboutwelcome/karma.mc.config.js","browser/components/aboutwelcome/modules/AWToolbarUtils.sys.mjs","browser/components/aboutwelcome/modules/AboutWelcomeDefaults.sys.mjs","browser/components/aboutwelcome/modules/AboutWelcomeTelemetry.sys.mjs","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_animation_play_pause.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_attribution.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_campaign_actions.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_configurable_ui.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_corner_image.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_embedded_browser.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_fxa_signin_flow.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_glean.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_import.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_impression_action.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_layout.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_logo.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_mobile_downloads.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multiselect.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multistage_addonspicker.js","browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multistage_default.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/browser JavaScript function map 13

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### browser/components/aboutlogins/tests/browser/AboutLoginsTestUtils.sys.mjs

Blob: `d064a3b0e3f646d113470ab5a0c7f1594c905427`. Role: test-path,source. Parse: module.

- getCsvImportSuccessDialogData @19-47; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getCsvImportErrorDialogData @56-72; FunctionExpression; parameters=1; async=true; generator=false
- getCsvImportReportData @82-106; FunctionExpression; parameters=1; async=true; generator=false
- Class AboutLoginsTestUtils @9-107

### browser/components/aboutlogins/tests/browser/browser_aaa_eventTelemetry_run_first.js

Blob: `14f8f957a0a5c7e75597cd5df3acde8f5e458e84`. Role: test-path,source. Parse: module.

- (anonymous) @33-55; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-54; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_telemetry_events @57-273; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @58-64; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @67-71; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @79-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @100-104; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @119-125; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @130-136; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @142-146; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-160; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @164-174; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @177-182; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @185-189; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @192-198; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @201-205; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @208-218; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @221-227; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @229-231; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @233-238; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @265-265; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @266-266; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @6; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_alertDismissedAfterChangingPassword.js

Blob: `b2415c8d58719c9da01811d555d7e410b02ab686`. Role: test-path,source. Parse: module.

- (anonymous) @27-42; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-41; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_added_login_shows_breach_warning @44-234; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @49-100; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @61-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @128-232; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @136-136; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @157-162; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @189-191; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @200-200; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @207-212; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_breachAlertLinkTelemetry.js

Blob: `2f96e4a502de19ad0eae9a5df8844f11a1b9adeb`. Role: test-path,source. Parse: module.

- (anonymous) @21-31; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-30; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_breach_alert_link_click_telemetry @33-118; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @39-54; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @64-106; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @70-70; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @98-98; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @4; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_breachAlertShowingForAddedLogin.js

Blob: `3582ccfe545306118a2e95add9c409fe3f490997`. Role: test-path,source. Parse: module.

- (anonymous) @17-26; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @22-25; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_added_login_shows_breach_warning @28-123; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @30-37; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @43-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @58-63; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-121; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @101-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @109-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @112-112; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=1; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_confirmDeleteDialog.js

Blob: `b40b9c2f1a2643faeac24a000382a09aead184e5`. Role: test-path,source. Parse: module.

- (anonymous) @4-12; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test @14-128; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-127; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-120; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_contextmenuFillLogins.js

Blob: `2afb68f0d3eded6717085490113de9676cae599d`. Role: test-path,source. Parse: module.

- (anonymous) @4-16; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @13-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setup @21-30; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @23-29; ArrowFunctionExpression; parameters=0; async=true; generator=false
- setup @37-78; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-65; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @57-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @69-77; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openContextMenuForPasswordInput @87-165; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @96-133; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @114-126; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @117-123; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @155-160; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testContextMenuOnInputField @167-187; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @191-193; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_copyToClipboardButton.js

Blob: `3a2731d5a4411da99d69d1e82b11fdc065fe4d7d`. Role: test-path,source. Parse: module.

- test @4-123; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-121; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @22-40; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @64-77; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-75; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @85-104; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @112-120; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @117-117; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_createLogin.js

Blob: `c0f4fe89dfa58d7d455461b9e03d59ef66f70133`. Role: test-path,source. Parse: module.

- (anonymous) @4-16; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-15; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_create_login @18-331; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @20-39; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @57-57; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @60-149; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @159-159; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @162-232; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @163-167; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @188-192; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @190-190; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @225-225; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @244-251; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @255-283; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @260-260; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @289-320; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @294-304; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @296-296; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @323-330; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_cancel_create_login @333-371; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @335-370; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_cancel_create_login_with_filter_showing_one_login @374-422; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @376-421; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_cancel_create_login_with_logins_filtered_out @425-475; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @427-474; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_create_duplicate_login @477-554; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @484-552; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @511-511; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @515-517; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @542-544; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_deleteLogin.js

Blob: `79409422e5dda6191d99d7e350108f98bd21376d`. Role: test-path,source. Parse: module.

- (anonymous) @4-17; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_show_logins @19-47; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-45; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @29-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_item @49-189; FunctionExpression; parameters=0; async=true; generator=false
- waitForDelete @52-59; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @55-56; ArrowFunctionExpression; parameters=0; async=true; generator=false
- deleteFirstLoginAfterEdit @61-111; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @62-77; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @73-75; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @82-88; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @90-110; ArrowFunctionExpression; parameters=0; async=true; generator=false
- deleteFirstLogin @113-140; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @114-139; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @125-127; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @149-167; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @178-188; ArrowFunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_fxAccounts.js

Blob: `d334476f1cd2145beb982c17e13e8cff4f9e66a3`. Role: test-path,source. Parse: module.

- mockState @13-20; FunctionDeclaration; parameters=1; async=false; generator=false
- UIState.get @14-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-34; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @29-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_logged_out @36-55; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @41-54; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_syncing_enabled @57-103; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @75-99; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @81-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_click_fxaccount @105-129; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://services-sync/UIState.sys.mjs @4; ChromeUtils-import-literal
- Module resource://gre/modules/FxAccounts.sys.mjs @8; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_loginFilter.js

Blob: `beedf6d2f2ed5090638db15fd842b38b29ac5649`. Role: test-path,source. Parse: module.

- (anonymous) @4-12; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- focus_filter_by_ctrl_f @14-61; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @16-60; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getActiveElement @17-25; FunctionDeclaration; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_loginItemErrors.js

Blob: `d99785ad603f9f673409d38ed763e4fe2b5b299e`. Role: test-path,source. Parse: module.

- (anonymous) @4-13; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-12; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_showLoginItemErrors @15-156; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-104; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @62-64; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-79; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @117-150; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @143-145; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_loginListChanges.js

Blob: `3f4bc18de733ce9e051ea0b195ddf1609dee494c`. Role: test-path,source. Parse: module.

- (anonymous) @4-21; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @12-17; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-20; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_added @23-45; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @35-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @37-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_modified @47-71; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-70; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @61-68; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_removed @73-92; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @85-91; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @87-89; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_all_logins_removed @94-153; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @116-134; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @118-124; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @138-152; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @140-142; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_loginSortOrderRestored.js

Blob: `fe2d1f93a4eb63897ee89873111938febd1b7d78`. Role: test-path,source. Parse: module.

- (anonymous) @19-29; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-28; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_sort_order_persisted @31-172; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-76; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @41-74; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @93-120; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @97-118; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @102-102; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @125-125; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @141-170; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @145-168; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @150-153; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_noLoginsView.js

Blob: `c5c384a23c0826ac86979bb64e64c8b09932b933`. Role: test-path,source. Parse: module.

- (anonymous) @4-12; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_logins_class @14-110; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-101; ArrowFunctionExpression; parameters=1; async=true; generator=false
- login_selected_when_login_added_and_in_no_logins_view @113-194; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @114-142; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-192; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @153-155; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_openExport.js

Blob: `9b168b78f4046fa5a674d477d90bf47ee04e3935`. Role: test-path,source. Parse: module.

- (anonymous) @17-47; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @26-33; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForFilePicker @49-57; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @50-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- MockFilePicker.showCallback @51-55; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_export @59-159; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @62-157; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @69-74; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForMenu @71-73; FunctionExpression; parameters=0; async=false; generator=false
- getExportMenuItem @76-81; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @116-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @11; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_openFiltered.js

Blob: `01e823ab8548cd1a95d8b8d01e5b61b4615db3d7`. Role: test-path,source. Parse: module.

- (anonymous) @4-34; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @7-7; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @19-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_query_parameter_filter @36-125; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-124; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @46-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-57; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_query_parameter_filter_no_logins_for_site @127-209; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @132-135; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @145-208; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @147-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_query_parameter_filter_no_login_until_backspace @211-298; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @225-297; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @227-229; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_openImport.js

Blob: `f7b692bf1b2062f596323c795f3c4c7cf785eed6`. Role: test-path,source. Parse: module.

- (anonymous) @8-25; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_import @27-60; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-39; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @33-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getImportItem @41-44; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @4; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_openImportCSV.js

Blob: `c0fd0d49f6c70c5617e1e97bf8e0ca5344b7de44`. Role: test-path,source. Parse: module.

- (anonymous) @15-20; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @16-19; FunctionExpression; parameters=0; async=true; generator=false
- waitForOpenFilePicker @33-44; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- MockFilePicker.showCallback @35-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clickImportFromCsvMenu @57-101; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @64-69; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForMenu @66-68; FunctionExpression; parameters=0; async=false; generator=false
- getImportMenuItem @73-76; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForFilePicker @80-98; FunctionDeclaration; parameters=0; async=true; generator=false
- getCsvImportSuccessDialogData @110-144; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @111-143; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getCsvImportErrorDialogData @153-172; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @154-171; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForImportToComplete @179-187; FunctionExpression; parameters=0; async=true; generator=false
- clickDetailedReport @196-217; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @202-215; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @207-207; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getDetailedReportData @224-253; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @228-250; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getCount @229-234; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @258-262; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @259-261; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_open_import_one_item_from_csv @264-284; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @267-282; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_open_import_all_four_categories @286-329; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @289-327; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_open_import_all_four_detailed_report @331-377; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @334-375; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_open_import_from_csv_with_invalid_file @379-408; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @382-406; ArrowFunctionExpression; parameters=1; async=true; generator=false
- Class CsvImportHelper @25-254
- Module resource://testing-common/FileTestUtils.sys.mjs @5; ChromeUtils-import-literal
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @9; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_openPreferences.js

Blob: `4ee23b5d997e83978636e4212c4dad6d28a0e463`. Role: test-path,source. Parse: module.

- (anonymous) @8-25; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-16; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @22-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_preferences @27-82; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @54-61; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @55-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getPrefsItem @63-66; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @4; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_openPreferencesExternal.js

Blob: `e4290371fb643b09b4fc243903847d25cb83325e`. Role: test-path,source. Parse: module.

- (anonymous) @4-12; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @9-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_feedback @14-65; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @36-41; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @37-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @51-55; ArrowFunctionExpression; parameters=1; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_openSite.js

Blob: `edb9235efbaa8b9159182ab1f8a00060dec821f3`. Role: test-path,source. Parse: module.

- (anonymous) @4-17; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @13-16; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_launch_login_item @19-100; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @27-35; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @54-57; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-74; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @84-84; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @91-99; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-94; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_osAuthDialog.js

Blob: `16c6e96cca364769b68a60f743edd6690dd9c2dd`. Role: test-path,source. Parse: module.

- (anonymous) @22-35; FunctionExpression; parameters=0; async=true; generator=false
- test_os_auth_enabled_with_checkbox @37-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @42-52; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @45-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_os_auth_disabled_with_checkbox @56-74; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-71; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @64-69; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_osAuth_shown_on_edit_login @76-111; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @92-100; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @104-109; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @106-106; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_osAuth_shown_on_reveal_password @113-149; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @129-135; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @138-147; FunctionExpression; parameters=0; async=true; generator=false
- test_os_auth_and_prp @151-243; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @177-184; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @187-202; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @215-222; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @227-238; FunctionExpression; parameters=0; async=true; generator=false
- test_prp_shown_when_os_auth_disabled_and_prp_unlocked @248-303; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @263-266; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @270-277; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @282-286; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @290-298; FunctionExpression; parameters=0; async=true; generator=false
- test_osAuth_shown_on_copy_password @306-335; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @322-328; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @331-333; FunctionExpression; parameters=0; async=true; generator=false
- test_osAuth_not_shown_within_expiration_time @337-381; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @353-359; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @362-379; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @375-375; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_osAuth_shown_after_expiration_timeout @383-427; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @399-405; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @417-423; FunctionExpression; parameters=0; async=true; generator=false
- test_osAuth_shown_on_reload @429-477; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @445-451; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @467-473; FunctionExpression; parameters=0; async=true; generator=false
- test_osAuth_shown_again_on_cancel @479-512; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @492-498; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @501-510; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_primaryPassword.js

Blob: `20248a9e5bca0e46877c9097bae113a558fe132f`. Role: test-path,source. Parse: module.

- waitForLoginCountToReach @4-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8-16; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- promptEvents @20-24; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @26-43; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-42; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test @45-242; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @69-72; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @106-110; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @122-124; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @128-134; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @137-146; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @148-154; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @157-166; FunctionExpression; parameters=0; async=true; generator=false
- createNewToggle @169-195; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @189-191; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @197-221; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @223-239; FunctionExpression; parameters=0; async=true; generator=false
- test_login_item_after_successful_auth @244-275; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @265-271; FunctionExpression; parameters=0; async=true; generator=false
- test_prompt_telemetry @277-355; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @313-313; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @330-333; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @339-342; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @340-340; ArrowFunctionExpression; parameters=1; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_removeAllDialog.js

Blob: `b75992ff542ffe9b3fb11f65e8ae0e3017c5b88a`. Role: test-path,source. Parse: module.

- openRemoveAllDialog @5-23; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @8-12; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @11-11; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getRemoveAllMenuButton @13-16; FunctionDeclaration; parameters=0; async=false; generator=false
- activateLoginItemEdit @25-52; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @27-30; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getLoginItemEditButton @31-34; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @40-50; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @47-47; ArrowFunctionExpression; parameters=0; async=false; generator=false
- activateCreateNewLogin @54-65; FunctionDeclaration; parameters=1; async=true; generator=false
- getCreateNewLoginButton @56-59; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForRemoveAllLogins @67-78; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @68-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observer @69-76; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @80-96; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @90-94; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_remove_all_dialog_l10n @98-170; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @102-169; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @166-166; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_remove_all_dialog_keyboard_navigation @172-240; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @175-210; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @207-207; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @212-221; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @218-218; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @223-239; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @236-236; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_remove_all_dialog_remove_logins @242-395; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @248-318; ArrowFunctionExpression; parameters=0; async=true; generator=false
- activateConfirmCheckbox @319-322; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @330-340; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getDialogRemoveAllButton @341-344; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @351-366; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @354-354; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @358-359; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @363-363; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @368-383; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @384-394; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @391-391; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_edit_mode_resets_on_remove_all_with_login @397-475; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @401-407; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @403-404; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @410-416; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getDialogCancelButton @417-420; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @427-433; ArrowFunctionExpression; parameters=0; async=true; generator=false
- activateConfirmCheckbox @436-439; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @446-456; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getDialogRemoveAllButton @457-460; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @467-473; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_remove_all_when_creating_new_login @477-558; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @483-493; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getDialogCancelButton @494-497; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @503-513; ArrowFunctionExpression; parameters=0; async=true; generator=false
- activateConfirmCheckbox @516-519; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @526-536; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getDialogRemoveAllButton @537-540; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @546-556; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_ensure_icons_are_not_draggable @560-571; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @564-570; ArrowFunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_sessionRestore.js

Blob: `7f6c037bedfe6fc2100a9914ec55eb8cda51ec80`. Role: test-path,source. Parse: module.

- checkLoginDisplayed @6-17; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @7-16; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @9-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @19-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @21-23; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @39-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onLocationChange @41-47; FunctionExpression; parameters=1; async=true; generator=false

### browser/components/aboutlogins/tests/browser/browser_tabKeyNav.js

Blob: `036fc3a10c7f7cabed187c243440599bd93dd91c`. Role: test-path,source. Parse: module.

- (anonymous) @17-27; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @23-26; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_tab_key_nav @29-132; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-131; ArrowFunctionExpression; parameters=0; async=true; generator=false
- selectWithShadowRootIfNeeded @33-40; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @35-38; ArrowFunctionExpression; parameters=2; async=false; generator=false
- tab @68-73; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @70-70; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shiftTab @74-78; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @76-76; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getFocusedElement @83-92; FunctionDeclaration; parameters=0; async=false; generator=false
- getShadowRootFocus @85-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_tab_to_create_button @134-171; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @136-170; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForAnimationFrame @139-141; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @140-140; ArrowFunctionExpression; parameters=1; async=false; generator=false
- tab @143-146; FunctionDeclaration; parameters=0; async=true; generator=false
- getFocusedElement @156-156; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_tab_to_edit_button @173-262; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @179-260; ArrowFunctionExpression; parameters=1; async=true; generator=false
- waitForAnimationFrame @182-184; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=1; async=false; generator=false
- tab @186-189; FunctionDeclaration; parameters=0; async=true; generator=false
- getFocusedElement @202-218; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @225-231; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/browser_updateLogin.js

Blob: `dc20bf0aecc1642ac30035b35a7dcd2202dc7860`. Role: test-path,source. Parse: module.

- (anonymous) @8-21; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @17-20; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_show_logins @23-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-37; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @27-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_login_item @40-425; FunctionExpression; parameters=0; async=true; generator=false
- test_discard_dialog @45-127; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @53-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @99-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @137-159; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @149-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @177-183; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @200-206; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @212-300; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @217-217; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @258-261; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @307-313; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @316-374; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @319-319; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @348-359; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @380-386; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @389-424; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @392-392; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @413-418; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module chrome://browser/content/aboutlogins/aboutLoginsUtils.mjs @4; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/browser/browser_vulnerableLoginAddedInSecondaryWindow.js

Blob: `14b0c36561ff5ef69337cd249c972165ce4f2cf5`. Role: test-path,source. Parse: module.

- (anonymous) @19-49; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @44-48; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_new_login_marked_vulnerable_in_both_windows @51-223; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @53-60; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-132; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @69-71; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @107-109; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @140-140; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @145-170; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @150-150; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @176-198; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @181-187; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-183; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @201-202; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @205-222; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @208-208; ArrowFunctionExpression; parameters=0; async=false; generator=false

### browser/components/aboutlogins/tests/browser/head.js

Blob: `dea60436fdbb7574546aa549921acc70ef390ab1`. Role: test-path,source. Parse: module.

- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addLogin @97-113; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @99-111; ArrowFunctionExpression; parameters=0; async=true; generator=false
- setup_head @117-213; FunctionExpression; parameters=0; async=true; generator=false
- onConsoleMessage @132-205; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @207-212; ArrowFunctionExpression; parameters=0; async=true; generator=false
- waitForMPDialog @221-245; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @227-244; FunctionExpression; parameters=1; async=false; generator=false
- forceAuthTimeoutAndWaitForMPDialog @256-260; FunctionDeclaration; parameters=2; async=false; generator=false
- forceAuthTimeoutAndWaitForOSKeyStoreLogin @270-274; FunctionDeclaration; parameters=1; async=false; generator=false
- Module moz-src:///browser/components/aboutlogins/LoginBreaches.sys.mjs @4; ChromeUtils-import-literal
- Module moz-src:///toolkit/components/passwordmgr/BreachAlertsData.sys.mjs @7; ChromeUtils-import-literal
- Module resource://services-settings/remote-settings.sys.mjs @10; ChromeUtils-import-literal
- Module moz-src:///browser/components/aboutlogins/AboutLoginsParent.sys.mjs @13; ChromeUtils-import-literal
- Module resource://testing-common/OSKeyStoreTestUtils.sys.mjs @16; ChromeUtils-import-literal
- Module resource://gre/modules/OSKeyStore.sys.mjs @20; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @24; ChromeUtils-import-literal
- Module resource://testing-common/PromiseTestUtils.sys.mjs @28; ChromeUtils-import-literal
- Module resource://testing-common/LoginTestUtils.sys.mjs @41; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/chrome/.eslintrc.mjs

Blob: `63ea665f169a3dbb8917f00aa916a86aea87f5f5`. Role: test-path,source. Parse: module.


### browser/components/aboutlogins/tests/chrome/aboutlogins_common.js

Blob: `e33f19f6df08302971841331124f437d437a0be5`. Role: test-path,source. Parse: module.

- asyncElementRendered @11-13; FunctionDeclaration; parameters=0; async=false; generator=false
- importDependencies @21-45; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @34-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clone.onload @35-38; FunctionExpression; parameters=0; async=false; generator=false
- connectRoot @51-51; FunctionExpression; parameters=0; async=false; generator=false
- disconnectRoot @52-52; FunctionExpression; parameters=0; async=false; generator=false
- translateElements @53-55; FunctionExpression; parameters=0; async=false; generator=false
- getAttributes @56-63; FunctionExpression; parameters=1; async=false; generator=false
- setAttributes @64-71; FunctionExpression; parameters=3; async=false; generator=false
- getLoginOrigin @79-81; FunctionExpression; parameters=1; async=false; generator=false
- setFocus @82-84; FunctionExpression; parameters=1; async=false; generator=false
- promptForPrimaryPassword @85-87; FunctionExpression; parameters=3; async=true; generator=false
- doLoginsMatch @88-94; FunctionExpression; parameters=2; async=false; generator=false

### browser/components/aboutlogins/tests/unit/head.js

Blob: `938e06e3c09bc6c738b38242b4e461a1b8ed2731`. Role: test-path,source. Parse: module.

- run_test @19-22; FunctionDeclaration; parameters=0; async=false; generator=false
- Module resource://testing-common/LoginTestUtils.sys.mjs @6; ChromeUtils-import-literal
- Module resource://gre/modules/LoginHelper.sys.mjs @9; ChromeUtils-import-literal

### browser/components/aboutlogins/tests/unit/test_getPotentialBreachesByLoginGUID.js

Blob: `2c28d5bc4cf8d394be4ef9ee43d2d5e8553dc8a6`. Role: test-path,source. Parse: module.

- test_notBreachedLogin @114-126; FunctionExpression; parameters=0; async=true; generator=false
- test_breachedLogin @128-152; FunctionExpression; parameters=0; async=true; generator=false
- test_breachedLoginAfterCrashingUriLogin @154-172; FunctionExpression; parameters=0; async=true; generator=false
- test_notBreachedSubdomain @174-187; FunctionExpression; parameters=0; async=true; generator=false
- test_breachedSubdomain @189-202; FunctionExpression; parameters=0; async=true; generator=false
- test_breachedSiteWithoutPasswords @204-220; FunctionExpression; parameters=0; async=true; generator=false
- test_breachAlertHiddenAfterDismissal @222-252; FunctionExpression; parameters=0; async=true; generator=false
- test_newBreachAfterDismissal @254-269; FunctionExpression; parameters=0; async=true; generator=false
- test_ExceptionsThrownByNonStandardURIsAreCaught @271-285; FunctionExpression; parameters=0; async=true; generator=false
- test_setBreachesFromRemoteSettingsSync @287-334; FunctionExpression; parameters=0; async=true; generator=false
- emitSync @308-313; FunctionDeclaration; parameters=0; async=true; generator=false
- Module resource://services-settings/remote-settings.sys.mjs @7; ChromeUtils-import-literal

### browser/components/aboutwelcome/.eslintrc.mjs

Blob: `2e7e116c95cfc91ff94f2424e1dc870d5311bcf2`. Role: source. Parse: module.

- Module eslint-plugin-import @5; ImportDeclaration
- Module eslint-plugin-jsx-a11y @6; ImportDeclaration
- Module eslint-plugin-react @7; ImportDeclaration
- Module globals @8; ImportDeclaration

### browser/components/aboutwelcome/actors/AboutWelcomeChild.sys.mjs

Blob: `e787093bcdf019811ccc00911f2af227bd492a2a`. Role: source. Parse: module.

- (anonymous) @14-19; ArrowFunctionExpression; parameters=0; async=false; generator=false
- didDestroy @35-37; FunctionExpression; parameters=0; async=false; generator=false
- actorCreated @39-41; FunctionExpression; parameters=0; async=false; generator=false
- sendToPage @48-55; FunctionExpression; parameters=1; async=false; generator=false
- exportFunctions @60-160; FunctionExpression; parameters=0; async=false; generator=false
- wrapPromise @165-169; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @166-167; ArrowFunctionExpression; parameters=2; async=false; generator=false
- sendQueryAndCloneForContent @174-183; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @176-181; ArrowFunctionExpression; parameters=0; async=true; generator=false
- AWSelectTheme @185-189; FunctionExpression; parameters=1; async=false; generator=false
- AWEvaluateScreenTargeting @191-196; FunctionExpression; parameters=1; async=false; generator=false
- AWEvaluateAttributeTargeting @198-202; FunctionExpression; parameters=1; async=false; generator=false
- AWAddScreenImpression @204-208; FunctionExpression; parameters=1; async=false; generator=false
- AWSendImpressionAction @210-212; FunctionExpression; parameters=1; async=false; generator=false
- AWFindBackupsInWellKnownLocations @214-219; FunctionExpression; parameters=1; async=false; generator=false
- getAWContent @224-262; FunctionExpression; parameters=0; async=true; generator=false
- AWGetFeatureConfig @264-266; FunctionExpression; parameters=0; async=false; generator=false
- AWGetFxAMetricsFlowURI @268-270; FunctionExpression; parameters=0; async=false; generator=false
- AWGetSelectedTheme @272-274; FunctionExpression; parameters=0; async=false; generator=false
- AWSendEventTelemetry @281-291; FunctionExpression; parameters=1; async=false; generator=false
- AWSendToParent @300-302; FunctionExpression; parameters=2; async=false; generator=false
- AWWaitForMigrationClose @304-306; FunctionExpression; parameters=0; async=false; generator=false
- setDidSeeFinalScreen @308-318; FunctionExpression; parameters=0; async=false; generator=false
- focusUrlBar @320-324; FunctionExpression; parameters=0; async=false; generator=false
- AWFinish @326-331; FunctionExpression; parameters=0; async=false; generator=false
- AWEnsureAddonInstalled @333-337; FunctionExpression; parameters=1; async=false; generator=false
- AWGetInstalledAddons @339-343; FunctionExpression; parameters=0; async=false; generator=false
- AWEnsureLangPackInstalled @345-389; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @351-387; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addMessageArgsAndUseLangPack @362-381; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @373-376; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @384-385; ArrowFunctionExpression; parameters=0; async=false; generator=false
- AWSetRequestedLocales @391-396; FunctionExpression; parameters=1; async=false; generator=false
- AWNegotiateLangPackForLanguageMismatch @398-403; FunctionExpression; parameters=1; async=false; generator=false
- AWSendToDeviceEmailsSupported @405-409; FunctionExpression; parameters=0; async=false; generator=false
- AWNewScreen @411-413; FunctionExpression; parameters=1; async=false; generator=false
- AWGetUnhandledCampaignAction @415-419; FunctionExpression; parameters=0; async=false; generator=false
- AWWaitForNimbus @421-423; FunctionExpression; parameters=0; async=false; generator=false
- RPMGetFormatURLPref @425-427; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @433-435; FunctionExpression; parameters=1; async=false; generator=false
- Class AboutWelcomeChild @30-436
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://messaging-system/lib/Logger.sys.mjs @15; ChromeUtils-import-literal

### browser/components/aboutwelcome/actors/AboutWelcomeParent.sys.mjs

Blob: `6fedafd6751e111b12d2df8994a175e3c7d798d1`. Role: source. Parse: module.

- (anonymous) @32-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- shouldGateNimbusForAboutWelcome @72-88; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForNimbusForAboutWelcome @96-147; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @112-144; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-117; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @119-134; ArrowFunctionExpression; parameters=0; async=true; generator=false
- constructor @150-170; FunctionExpression; parameters=0; async=false; generator=false
- ?.onWindowClose @160-162; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ?.onTabClose @164-166; ArrowFunctionExpression; parameters=0; async=false; generator=false
- observe @172-178; FunctionExpression; parameters=2; async=false; generator=false
- AWTerminate @181-183; FunctionExpression; parameters=0; async=false; generator=false
- stop @185-196; FunctionExpression; parameters=0; async=false; generator=false
- constructor @200-209; FunctionExpression; parameters=0; async=false; generator=false
- startAboutWelcomeObserver @211-213; FunctionExpression; parameters=0; async=false; generator=false
- doesAppNeedPin @217-222; FunctionExpression; parameters=0; async=true; generator=false
- isDefaultBrowser @224-226; FunctionExpression; parameters=0; async=false; generator=false
- didDestroy @228-242; FunctionExpression; parameters=0; async=false; generator=false
- onContentMessage @251-430; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @275-297; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallEnded @277-282; FunctionExpression; parameters=2; async=false; generator=false
- onInstallCancelled @283-286; FunctionExpression; parameters=0; async=false; generator=false
- onDownloadCancelled @287-290; FunctionExpression; parameters=0; async=false; generator=false
- onInstallFailed @291-294; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @299-300; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @300-300; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @318-318; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @322-322; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @330-330; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @345-355; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observer @350-353; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @351-351; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @354-354; ArrowFunctionExpression; parameters=1; async=false; generator=false
- receiveMessage @436-447; FunctionExpression; parameters=1; async=false; generator=false
- resetNimbusReadyPromiseForTesting @450-452; FunctionDeclaration; parameters=0; async=false; generator=false
- Class AboutWelcomeParent @199-448
- Class AboutWelcomeObserver @149-197
- Module resource://messaging-system/lib/Logger.sys.mjs @33; ChromeUtils-import-literal

### browser/components/aboutwelcome/content-src/aboutwelcome.jsx

Blob: `a1a95ce284dceaab9395fe8aa0030c26aa179c34`. Role: source. Parse: module.

- constructor @11-15; FunctionExpression; parameters=1; async=false; generator=false
- fetchFxAFlowUri @17-19; FunctionExpression; parameters=0; async=true; generator=false
- componentDidMount @21-55; FunctionExpression; parameters=0; async=false; generator=false
- recordImpression @28-39; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- render @57-81; FunctionExpression; parameters=0; async=false; generator=false
- ComputeTelemetryInfo @85-103; FunctionDeclaration; parameters=3; async=false; generator=false
- retrieveRenderContent @105-130; FunctionDeclaration; parameters=0; async=true; generator=false
- mount @132-146; FunctionDeclaration; parameters=0; async=true; generator=false
- Class AboutWelcome @10-82
- Module react @5; ImportDeclaration
- Module react-dom @6; ImportDeclaration
- Module ../../asrouter/content-src/lib/multistage-utils.mjs @7; ImportDeclaration
- Module ../../asrouter/content-src/components/MultiStageAboutWelcome @8; ImportDeclaration

### browser/components/aboutwelcome/content/aboutwelcome.bundle.js

Blob: `750357b241b3177eed00a6d1e2a48dc525bcf18e`. Role: source. Parse: module.

- (anonymous) @7-7319; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @11-16; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @18-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-163; ArrowFunctionExpression; parameters=3; async=false; generator=false
- MultiStageUtils @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleUserAction @45-47; FunctionExpression; parameters=1; async=false; generator=false
- handleImpressionAction @48-62; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @55-61; ArrowFunctionExpression; parameters=1; async=false; generator=false
- sendImpressionTelemetry @63-72; FunctionExpression; parameters=2; async=false; generator=false
- sendActionTelemetry @73-89; FunctionExpression; parameters=4; async=false; generator=false
- sendDismissTelemetry @90-96; FunctionExpression; parameters=3; async=false; generator=false
- fetchFlowParams @97-113; FunctionExpression; parameters=1; async=true; generator=false
- sendEvent @114-121; FunctionExpression; parameters=2; async=false; generator=false
- getLoadingStrategyFor @122-124; FunctionExpression; parameters=1; async=false; generator=false
- handleCampaignAction @125-136; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @126-135; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getValidStyle @137-149; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @143-143; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @145-148; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getTileStyle @150-159; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @165-1112; ArrowFunctionExpression; parameters=3; async=false; generator=false
- CARD_STACK_TRANSITION_OUT_TIME @170-170; ArrowFunctionExpression; parameters=0; async=false; generator=false
- MultiStageAboutWelcome @171-171; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ProgressBar @172-172; ArrowFunctionExpression; parameters=0; async=false; generator=false
- SecondaryCTA @173-173; ArrowFunctionExpression; parameters=0; async=false; generator=false
- StepsIndicator @174-174; ArrowFunctionExpression; parameters=0; async=false; generator=false
- WelcomeScreen @175-175; ArrowFunctionExpression; parameters=0; async=false; generator=false
- MultiStageAboutWelcome @204-579; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @217-288; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @218-287; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @225-225; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @225-225; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @229-229; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @229-229; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @234-234; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @234-234; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @247-251; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @251-253; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @254-256; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @259-278; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @294-300; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @295-299; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @305-309; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @307-307; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @307-307; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleTransition @314-342; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @331-341; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @334-334; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @337-337; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @343-381; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handler @352-363; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @359-362; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @376-376; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @412-412; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleAnimationsPaused @413-413; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @413-413; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @419-425; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @420-424; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @427-441; ArrowFunctionExpression; parameters=0; async=false; generator=false
- refreshActiveThemeId @429-434; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @437-440; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @447-449; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @451-456; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @452-455; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @468-578; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setActiveMultiSelect @473-484; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @474-483; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setScreenMultiSelects @485-496; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @486-495; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setActiveSingleSelectSelection @497-508; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @498-507; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setPinnedSite @509-514; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @510-513; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setTextInput @515-526; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @516-525; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderSingleSecondaryCTAButton @580-658; ArrowFunctionExpression; parameters=1; async=false; generator=false
- computeDisabled @602-623; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @620-620; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shimmedHandleAction @633-638; ArrowFunctionExpression; parameters=1; async=false; generator=false
- SecondaryCTA @659-720; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @669-669; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @671-691; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @672-690; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @698-708; ArrowFunctionExpression; parameters=2; async=false; generator=false
- StepsIndicator @721-732; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ProgressBar @733-751; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @739-743; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @753-756; FunctionExpression; parameters=1; async=false; generator=false
- handleOpenURL @757-797; FunctionExpression; parameters=3; async=false; generator=false
- handleMigrationIfNeeded @798-804; FunctionExpression; parameters=2; async=true; generator=false
- hasMigrate @799-799; ArrowFunctionExpression; parameters=1; async=false; generator=false
- applyThemeIfNeeded @805-812; FunctionExpression; parameters=2; async=false; generator=false
- handlePickerAction @813-826; FunctionExpression; parameters=1; async=false; generator=false
- resolveActionFromContent @827-848; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @840-840; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleAction @849-939; FunctionExpression; parameters=2; async=true; generator=false
- shouldDoBehavior @913-922; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setMultiSelectActions @940-1003; FunctionExpression; parameters=1; async=false; generator=false
- processTile @967-984; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setTextInputActions @1004-1060; FunctionExpression; parameters=1; async=false; generator=false
- truncateToByteSize @1022-1034; ArrowFunctionExpression; parameters=2; async=false; generator=false
- processTile @1035-1049; ArrowFunctionExpression; parameters=2; async=false; generator=false
- render @1061-1109; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1114-1277; ArrowFunctionExpression; parameters=3; async=false; generator=false
- CONFIGURABLE_STYLES @1119-1119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Localized @1120-1120; ArrowFunctionExpression; parameters=0; async=false; generator=false
- pickConfigurableStyles @1121-1121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- resolveImageSrc @1122-1122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- pickConfigurableStyles @1138-1146; FunctionDeclaration; parameters=1; async=false; generator=false
- resolveImageSrc @1151-1157; FunctionDeclaration; parameters=1; async=false; generator=false
- Localized @1197-1275; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1203-1210; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1208-1208; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1279-2755; ArrowFunctionExpression; parameters=3; async=false; generator=false
- MultiStageProtonScreen @1284-1284; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ProtonScreen @1285-1285; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ProtonScreenActionButtons @1286-1286; ArrowFunctionExpression; parameters=0; async=false; generator=false
- screenContentShape @1287-1287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- resolveCornerImagePosition @1337-1344; FunctionDeclaration; parameters=1; async=false; generator=false
- resolveDirectionalImage @1349-1355; FunctionDeclaration; parameters=1; async=false; generator=false
- MultiStageProtonScreen @1356-1523; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1365-1455; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1367-1367; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1372-1379; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1380-1380; ArrowFunctionExpression; parameters=0; async=false; generator=false
- doAdvance @1402-1423; ArrowFunctionExpression; parameters=0; async=false; generator=false
- maybeAdvance @1424-1428; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1429-1432; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1433-1436; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1439-1449; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1450-1454; ArrowFunctionExpression; parameters=0; async=false; generator=false
- useMediaQuery @1466-1475; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1467-1467; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1468-1473; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onChange @1470-1470; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1472-1472; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ProtonScreenActionButtons @1524-1645; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1541-1545; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isPrimaryDisabled @1555-1590; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1575-1575; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1583-1583; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onChange @1632-1634; ArrowFunctionExpression; parameters=0; async=false; generator=false
- componentDidMount @1647-1662; FunctionExpression; parameters=0; async=false; generator=false
- getScreenClassName @1663-1676; FunctionExpression; parameters=5; async=false; generator=false
- renderTitle @1677-1709; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1681-1683; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderPicture @1710-1794; FunctionExpression; parameters=1; async=false; generator=false
- getLoadingStrategy @1726-1733; FunctionDeclaration; parameters=0; async=false; generator=false
- renderNoodles @1795-1807; FunctionExpression; parameters=0; async=false; generator=false
- renderLastCardImage @1808-1828; FunctionExpression; parameters=1; async=false; generator=false
- renderCornerImage @1829-1856; FunctionExpression; parameters=1; async=false; generator=false
- renderLanguageSwitcher @1857-1865; FunctionExpression; parameters=0; async=false; generator=false
- renderDismissButton @1866-1885; FunctionExpression; parameters=0; async=false; generator=false
- renderMoreButton @1886-1892; FunctionExpression; parameters=0; async=false; generator=false
- renderStepsIndicator @1893-1925; FunctionExpression; parameters=0; async=false; generator=false
- hasAnimatedContent @1932-1934; FunctionExpression; parameters=1; async=false; generator=false
- getEffectiveBackground @1935-1943; FunctionExpression; parameters=1; async=false; generator=false
- getEffectiveHeroImageUrl @1944-1949; FunctionExpression; parameters=1; async=false; generator=false
- renderAnimationPlayPauseButton @1950-1963; FunctionExpression; parameters=0; async=false; generator=false
- renderSecondarySection @1964-1986; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1971-1971; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderHeroText @1987-2019; FunctionExpression; parameters=1; async=false; generator=false
- HeroTextWrapper @1995-2004; ArrowFunctionExpression; parameters=1; async=false; generator=false
- renderOrderedContent @2020-2046; FunctionExpression; parameters=1; async=false; generator=false
- renderRTAMOIcon @2047-2057; FunctionExpression; parameters=3; async=false; generator=false
- getCombinedInnerStyles @2058-2066; FunctionExpression; parameters=2; async=false; generator=false
- getActionButtonsPosition @2067-2078; FunctionExpression; parameters=1; async=false; generator=false
- renderActionButtons @2079-2093; FunctionExpression; parameters=2; async=false; generator=false
- render @2096-2208; FunctionExpression; parameters=0; async=false; generator=false
- ref @2159-2161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2220-2220; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2757-4072; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2759-4069; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2759-2864; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2759-2759; FunctionExpression; parameters=0; async=false; generator=false
- r @2759-2759; FunctionDeclaration; parameters=3; async=false; generator=false
- o @2759-2759; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @2759-2759; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2759-2759; FunctionExpression; parameters=1; async=false; generator=false
- printWarning @2769-2769; FunctionExpression; parameters=0; async=false; generator=false
- printWarning @2776-2787; FunctionExpression; parameters=1; async=false; generator=false
- checkPropTypes @2801-2849; FunctionDeclaration; parameters=5; async=false; generator=false
- checkPropTypes.resetWarningCache @2856-2860; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2864-2931; FunctionExpression; parameters=3; async=false; generator=false
- emptyFunction @2876-2876; FunctionDeclaration; parameters=0; async=false; generator=false
- emptyFunctionWithReset @2877-2877; FunctionDeclaration; parameters=0; async=false; generator=false
- module.exports @2880-2929; FunctionExpression; parameters=0; async=false; generator=false
- shim @2881-2893; FunctionDeclaration; parameters=6; async=false; generator=false
- getShim @2895-2897; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2931-3543; FunctionExpression; parameters=3; async=false; generator=false
- printWarning @2948-2948; FunctionExpression; parameters=0; async=false; generator=false
- printWarning @2951-2962; FunctionExpression; parameters=1; async=false; generator=false
- emptyFunctionThatReturnsNull @2965-2967; FunctionDeclaration; parameters=0; async=false; generator=false
- module.exports @2969-3541; FunctionExpression; parameters=2; async=false; generator=false
- getIteratorFn @2988-2993; FunctionDeclaration; parameters=1; async=false; generator=false
- is @3074-3084; FunctionDeclaration; parameters=2; async=false; generator=false
- PropTypeError @3094-3098; FunctionDeclaration; parameters=2; async=false; generator=false
- createChainableTypeChecker @3102-3158; FunctionDeclaration; parameters=1; async=false; generator=false
- checkType @3107-3152; FunctionDeclaration; parameters=7; async=false; generator=false
- createPrimitiveTypeChecker @3160-3178; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3161-3176; FunctionDeclaration; parameters=6; async=false; generator=false
- createAnyTypeChecker @3180-3182; FunctionDeclaration; parameters=0; async=false; generator=false
- createArrayOfTypeChecker @3184-3203; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3185-3201; FunctionDeclaration; parameters=5; async=false; generator=false
- createElementTypeChecker @3205-3215; FunctionDeclaration; parameters=0; async=false; generator=false
- validate @3206-3213; FunctionDeclaration; parameters=5; async=false; generator=false
- createElementTypeTypeChecker @3217-3227; FunctionDeclaration; parameters=0; async=false; generator=false
- validate @3218-3225; FunctionDeclaration; parameters=5; async=false; generator=false
- createInstanceTypeChecker @3229-3239; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3230-3237; FunctionDeclaration; parameters=5; async=false; generator=false
- createEnumTypeChecker @3241-3274; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3256-3272; FunctionDeclaration; parameters=5; async=false; generator=false
- replacer @3264-3270; FunctionExpression; parameters=2; async=false; generator=false
- createObjectOfTypeChecker @3276-3297; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3277-3295; FunctionDeclaration; parameters=5; async=false; generator=false
- createUnionTypeChecker @3299-3332; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3316-3330; FunctionDeclaration; parameters=5; async=false; generator=false
- createNodeChecker @3334-3342; FunctionDeclaration; parameters=0; async=false; generator=false
- validate @3335-3340; FunctionDeclaration; parameters=5; async=false; generator=false
- invalidValidatorError @3344-3349; FunctionDeclaration; parameters=5; async=false; generator=false
- createShapeTypeChecker @3351-3371; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3352-3369; FunctionDeclaration; parameters=5; async=false; generator=false
- createStrictShapeTypeChecker @3373-3403; FunctionDeclaration; parameters=1; async=false; generator=false
- validate @3374-3400; FunctionDeclaration; parameters=5; async=false; generator=false
- isNode @3405-3450; FunctionDeclaration; parameters=1; async=false; generator=false
- isSymbol @3452-3474; FunctionDeclaration; parameters=2; async=false; generator=false
- getPropType @3477-3492; FunctionDeclaration; parameters=1; async=false; generator=false
- getPreciseType @3496-3509; FunctionDeclaration; parameters=1; async=false; generator=false
- getPostfixForTypeWarning @3513-3526; FunctionDeclaration; parameters=1; async=false; generator=false
- getClassName @3529-3534; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @3543-3560; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @3560-3574; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @3574-3577; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @3577-3669; FunctionExpression; parameters=3; async=false; generator=false
- toObject @3590-3596; FunctionDeclaration; parameters=1; async=false; generator=false
- shouldUseNative @3598-3640; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @3618-3620; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3627-3629; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3642-3667; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @3669-3855; FunctionExpression; parameters=3; async=false; generator=false
- defaultSetTimout @3681-3683; FunctionDeclaration; parameters=0; async=false; generator=false
- defaultClearTimeout @3684-3686; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @3687-3706; FunctionExpression; parameters=0; async=false; generator=false
- runTimeout @3707-3731; FunctionDeclaration; parameters=1; async=false; generator=false
- runClearTimeout @3732-3758; FunctionDeclaration; parameters=1; async=false; generator=false
- cleanUpNextTick @3764-3777; FunctionDeclaration; parameters=0; async=false; generator=false
- drainQueue @3779-3801; FunctionDeclaration; parameters=0; async=false; generator=false
- process.nextTick @3803-3814; FunctionExpression; parameters=1; async=false; generator=false
- Item @3817-3820; FunctionDeclaration; parameters=2; async=false; generator=false
- Item.prototype.run @3821-3823; FunctionExpression; parameters=0; async=false; generator=false
- noop @3831-3831; FunctionDeclaration; parameters=0; async=false; generator=false
- process.listeners @3843-3843; FunctionExpression; parameters=1; async=false; generator=false
- process.binding @3845-3847; FunctionExpression; parameters=1; async=false; generator=false
- process.cwd @3849-3849; FunctionExpression; parameters=0; async=false; generator=false
- process.chdir @3850-3852; FunctionExpression; parameters=1; async=false; generator=false
- process.umask @3853-3853; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3855-4040; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @3856-4039; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3856-4039; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3871-4036; FunctionExpression; parameters=0; async=false; generator=false
- isValidElementType @3898-3901; FunctionDeclaration; parameters=1; async=false; generator=false
- typeOf @3903-3943; FunctionDeclaration; parameters=1; async=false; generator=false
- isAsyncMode @3960-3970; FunctionDeclaration; parameters=1; async=false; generator=false
- isConcurrentMode @3971-3973; FunctionDeclaration; parameters=1; async=false; generator=false
- isContextConsumer @3974-3976; FunctionDeclaration; parameters=1; async=false; generator=false
- isContextProvider @3977-3979; FunctionDeclaration; parameters=1; async=false; generator=false
- isElement @3980-3982; FunctionDeclaration; parameters=1; async=false; generator=false
- isForwardRef @3983-3985; FunctionDeclaration; parameters=1; async=false; generator=false
- isFragment @3986-3988; FunctionDeclaration; parameters=1; async=false; generator=false
- isLazy @3989-3991; FunctionDeclaration; parameters=1; async=false; generator=false
- isMemo @3992-3994; FunctionDeclaration; parameters=1; async=false; generator=false
- isPortal @3995-3997; FunctionDeclaration; parameters=1; async=false; generator=false
- isProfiler @3998-4000; FunctionDeclaration; parameters=1; async=false; generator=false
- isStrictMode @4001-4003; FunctionDeclaration; parameters=1; async=false; generator=false
- isSuspense @4004-4006; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4040-4057; FunctionExpression; parameters=3; async=false; generator=false
- A @4052-4052; FunctionDeclaration; parameters=1; async=false; generator=false
- z @4052-4052; FunctionDeclaration; parameters=1; async=false; generator=false
- exports.isLazy @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isFragment @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isForwardRef @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isElement @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isContextProvider @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isContextConsumer @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isAsyncMode @4053-4053; FunctionExpression; parameters=1; async=false; generator=false
- exports.isSuspense @4054-4054; FunctionExpression; parameters=1; async=false; generator=false
- exports.isStrictMode @4054-4054; FunctionExpression; parameters=1; async=false; generator=false
- exports.isProfiler @4054-4054; FunctionExpression; parameters=1; async=false; generator=false
- exports.isPortal @4054-4054; FunctionExpression; parameters=1; async=false; generator=false
- exports.isMemo @4054-4054; FunctionExpression; parameters=1; async=false; generator=false
- exports.isValidElementType @4055-4055; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4057-4068; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @4058-4067; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4058-4067; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4074-4331; ArrowFunctionExpression; parameters=3; async=false; generator=false
- LanguageSwitcher @4079-4079; ArrowFunctionExpression; parameters=0; async=false; generator=false
- useLanguageSwitcher @4080-4080; ArrowFunctionExpression; parameters=0; async=false; generator=false
- useLanguageSwitcher @4099-4199; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @4100-4102; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4108-4116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getNegotiatedLanguage @4121-4151; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4129-4150; ArrowFunctionExpression; parameters=0; async=true; generator=false
- ensureLangPackInstalled @4163-4177; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4169-4173; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4173-4176; ArrowFunctionExpression; parameters=1; async=false; generator=false
- filterScreen @4179-4190; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4186-4186; ArrowFunctionExpression; parameters=1; async=false; generator=false
- LanguageSwitcher @4207-4329; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4218-4231; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4221-4229; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @4293-4300; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @4308-4311; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @4320-4323; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4333-4388; ArrowFunctionExpression; parameters=3; async=false; generator=false
- CTAParagraph @4338-4338; ArrowFunctionExpression; parameters=0; async=false; generator=false
- CTAParagraph @4351-4386; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4359-4362; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onKeyUp @4379-4379; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4390-4428; ArrowFunctionExpression; parameters=3; async=false; generator=false
- HeroImage @4395-4395; ArrowFunctionExpression; parameters=0; async=false; generator=false
- HeroImage @4406-4426; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4430-4468; ArrowFunctionExpression; parameters=3; async=false; generator=false
- OnboardingVideo @4435-4435; ArrowFunctionExpression; parameters=0; async=false; generator=false
- OnboardingVideo @4444-4466; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleVideoAction @4447-4453; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onPlay @4461-4461; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onEnded @4462-4462; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4470-4543; ArrowFunctionExpression; parameters=3; async=false; generator=false
- AdditionalCTA @4475-4475; ArrowFunctionExpression; parameters=0; async=false; generator=false
- AdditionalCTA @4488-4541; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4505-4526; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4523-4523; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4545-4727; ArrowFunctionExpression; parameters=3; async=false; generator=false
- SubmenuButton @4550-4550; ArrowFunctionExpression; parameters=0; async=false; generator=false
- SubmenuButton @4561-4563; ArrowFunctionExpression; parameters=1; async=false; generator=false
- translateMenuitem @4564-4589; FunctionDeclaration; parameters=2; async=false; generator=false
- addMenuitems @4590-4631; FunctionDeclaration; parameters=2; async=false; generator=false
- SubmenuButtonInner @4632-4725; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4650-4661; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4662-4670; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4671-4707; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4689-4694; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4695-4700; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4703-4706; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4729-4872; ArrowFunctionExpression; parameters=3; async=false; generator=false
- LinkParagraph @4734-4734; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderSegment @4745-4825; FunctionDeclaration; parameters=3; async=false; generator=false
- onClick @4766-4769; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onKeyPress @4770-4775; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onClick @4792-4795; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onKeyPress @4811-4815; ArrowFunctionExpression; parameters=1; async=false; generator=false
- LinkParagraph @4826-4870; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4832-4840; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4841-4845; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4851-4851; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @4860-4869; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4874-5262; ArrowFunctionExpression; parameters=3; async=false; generator=false
- ContentTiles @4879-4879; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getTileImpressionContext @4880-4880; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _extends @4902-4902; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @4902-4902; FunctionExpression; parameters=1; async=false; generator=false
- getTileImpressionContext @4934-4943; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @4935-4935; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4941-4941; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ContentTiles @4944-5260; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4959-4982; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4963-4980; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @4969-4976; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4984-5069; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4999-4999; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5004-5004; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onKeyDown @5016-5023; FunctionDeclaration; parameters=1; async=false; generator=false
- onFocusIn @5024-5060; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @5065-5068; ArrowFunctionExpression; parameters=0; async=false; generator=false
- toggleTile @5070-5082; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @5080-5080; ArrowFunctionExpression; parameters=1; async=false; generator=false
- toggleTiles @5083-5086; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5084-5084; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getTileMultiSelects @5087-5089; FunctionDeclaration; parameters=2; async=false; generator=false
- getTileActiveMultiSelect @5090-5092; FunctionDeclaration; parameters=2; async=false; generator=false
- renderContentTile @5093-5233; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onClick @5113-5113; ArrowFunctionExpression; parameters=0; async=false; generator=false
- renderContentTiles @5234-5244; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5240-5240; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @5264-5398; ArrowFunctionExpression; parameters=3; async=false; generator=false
- AddonsPicker @5269-5269; ArrowFunctionExpression; parameters=0; async=false; generator=false
- AddonsPicker @5284-5396; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleInstallClick @5294-5309; FunctionDeclaration; parameters=1; async=false; generator=false
- handleAuthorClick @5310-5319; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @5322-5395; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onClick @5359-5361; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5400-5484; ArrowFunctionExpression; parameters=3; async=false; generator=false
- InstallButton @5405-5405; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Loader @5406-5406; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Loader @5417-5425; ArrowFunctionExpression; parameters=0; async=false; generator=false
- InstallButton @5426-5482; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getDefaultInstallCompleteLabel @5434-5450; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @5451-5453; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onClick @5455-5467; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @5459-5466; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5486-5686; ArrowFunctionExpression; parameters=3; async=false; generator=false
- SingleSelect @5491-5491; ArrowFunctionExpression; parameters=0; async=false; generator=false
- SingleSelect @5512-5684; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlePillSelect @5524-5533; ArrowFunctionExpression; parameters=1; async=false; generator=false
- autoTriggerAllowed @5534-5552; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkAction @5538-5546; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5549-5549; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5556-5571; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5560-5560; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5587-5683; ArrowFunctionExpression; parameters=1; async=false; generator=false
- valOrObj @5608-5608; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleClick @5615-5620; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleKeyDown @5621-5627; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ref @5633-5639; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onKeyDown @5640-5640; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onClick @5660-5660; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5688-5733; ArrowFunctionExpression; parameters=3; async=false; generator=false
- TileButton @5693-5693; ArrowFunctionExpression; parameters=0; async=false; generator=false
- TileButton @5704-5731; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onClick @5714-5721; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @5735-5785; ArrowFunctionExpression; parameters=3; async=false; generator=false
- TileList @5740-5740; ArrowFunctionExpression; parameters=0; async=false; generator=false
- TileList @5753-5783; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5763-5782; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @5787-5846; ArrowFunctionExpression; parameters=3; async=false; generator=false
- CarouselNav @5792-5792; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _extends @5796-5796; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @5796-5796; FunctionExpression; parameters=1; async=false; generator=false
- CarouselNav @5802-5844; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5811-5819; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleChange @5816-5816; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5818-5818; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @5820-5820; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5834-5843; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5848-5909; ArrowFunctionExpression; parameters=3; async=false; generator=false
- MarketplaceButtons @5853-5853; ArrowFunctionExpression; parameters=0; async=false; generator=false
- MobileDownloads @5854-5854; ArrowFunctionExpression; parameters=0; async=false; generator=false
- MarketplaceButtons @5867-5883; ArrowFunctionExpression; parameters=1; async=false; generator=false
- MobileDownloads @5884-5907; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5911-6162; ArrowFunctionExpression; parameters=3; async=false; generator=false
- MultiSelect @5916-5916; ArrowFunctionExpression; parameters=0; async=false; generator=false
- UncheckedNotice @5954-5984; ArrowFunctionExpression; parameters=1; async=false; generator=false
- MultiSelect @5985-6160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @5999-6007; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6001-6005; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6008-6023; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOrderedIds @6009-6021; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @6013-6016; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6016-6018; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6016-6016; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6022-6022; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6022-6022; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6025-6025; ArrowFunctionExpression; parameters=0; async=false; generator=false
- PickerIcon @6026-6039; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleCheckboxContainerInteraction @6044-6066; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6070-6083; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6073-6080; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6088-6091; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6097-6155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ref @6127-6127; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6156-6156; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6164-6238; ArrowFunctionExpression; parameters=3; async=false; generator=false
- TextAreaTile @6169-6169; ArrowFunctionExpression; parameters=0; async=false; generator=false
- TextAreaTile @6181-6236; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6193-6198; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6199-6210; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6211-6218; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6240-6338; ArrowFunctionExpression; parameters=3; async=false; generator=false
- EmbeddedMigrationWizard @6245-6245; ArrowFunctionExpression; parameters=0; async=false; generator=false
- EmbeddedMigrationWizard @6282-6336; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6288-6313; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleBeginMigration @6289-6296; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleClose @6297-6303; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6309-6312; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6340-6374; ArrowFunctionExpression; parameters=3; async=false; generator=false
- EmbeddedThemePicker @6345-6345; ArrowFunctionExpression; parameters=0; async=false; generator=false
- EmbeddedThemePicker @6354-6372; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6358-6367; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6364-6366; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6376-6478; ArrowFunctionExpression; parameters=3; async=false; generator=false
- EmbeddedFxBackupOptIn @6381-6381; ArrowFunctionExpression; parameters=0; async=false; generator=false
- EmbeddedFxBackupOptIn @6390-6476; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6407-6459; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleEnableScheduledBackups @6411-6421; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleAdvanceScreens @6422-6432; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleStateUpdate @6433-6450; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6454-6458; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6480-6654; ArrowFunctionExpression; parameters=3; async=false; generator=false
- ActionChecklist @6485-6485; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ActionChecklistItem @6486-6486; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ActionChecklistProgressBar @6487-6487; ArrowFunctionExpression; parameters=0; async=false; generator=false
- evaluateTargeting @6500-6502; FunctionDeclaration; parameters=1; async=true; generator=false
- ActionChecklistItem @6503-6545; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6509-6514; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setInitialTargetingValue @6510-6512; ArrowFunctionExpression; parameters=0; async=true; generator=false
- onButtonClick @6516-6521; FunctionDeclaration; parameters=1; async=false; generator=false
- ActionChecklistProgressBar @6546-6566; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ActionChecklist @6567-6652; ArrowFunctionExpression; parameters=1; async=false; generator=false
- determineProgressValue @6576-6579; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @6586-6593; ArrowFunctionExpression; parameters=0; async=false; generator=false
- evaluateAllActionsTargeting @6587-6591; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @6588-6588; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @6589-6589; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6597-6599; ArrowFunctionExpression; parameters=0; async=false; generator=false
- handleTileClick @6601-6616; FunctionDeclaration; parameters=1; async=false; generator=false
- handleRemoveChecklistClick @6617-6626; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @6639-6645; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6656-6722; ArrowFunctionExpression; parameters=3; async=false; generator=false
- EmbeddedBrowser @6661-6661; ArrowFunctionExpression; parameters=0; async=false; generator=false
- default @6662-6662; ArrowFunctionExpression; parameters=0; async=false; generator=false
- EmbeddedBrowser @6674-6677; ArrowFunctionExpression; parameters=1; async=false; generator=false
- EmbeddedBrowserInner @6678-6719; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6684-6698; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6693-6693; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6700-6706; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6707-6714; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6710-6712; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6724-6785; ArrowFunctionExpression; parameters=3; async=false; generator=false
- ConfirmationChecklist @6729-6729; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ConfirmationChecklist @6741-6783; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6755-6782; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6787-6863; ArrowFunctionExpression; parameters=3; async=false; generator=false
- EmbeddedBackupRestore @6792-6792; ArrowFunctionExpression; parameters=0; async=false; generator=false
- EmbeddedBackupRestore @6805-6861; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6811-6827; ArrowFunctionExpression; parameters=0; async=false; generator=false
- loadRestore @6812-6814; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @6828-6830; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6831-6840; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6837-6839; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6865-6975; ArrowFunctionExpression; parameters=3; async=false; generator=false
- PinnableSitesList @6870-6870; ArrowFunctionExpression; parameters=0; async=false; generator=false
- PinnableSitesList @6888-6973; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6897-6897; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @6897-6897; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setItemState @6901-6904; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @6901-6904; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlePin @6905-6938; ArrowFunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @6941-6972; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onClick @6967-6967; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @6977-7016; ArrowFunctionExpression; parameters=3; async=false; generator=false
- ContentToggle @6982-6982; ArrowFunctionExpression; parameters=0; async=false; generator=false
- ContentToggle @6993-7014; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7001-7001; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7018-7051; ArrowFunctionExpression; parameters=3; async=false; generator=false
- TextBoxTile @7023-7023; ArrowFunctionExpression; parameters=0; async=false; generator=false
- TextBoxTile @7035-7049; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7053-7097; ArrowFunctionExpression; parameters=3; async=false; generator=false
- BASE_PARAMS @7058-7058; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addUtmParams @7059-7059; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addUtmParams @7080-7094; FunctionDeclaration; parameters=2; async=false; generator=false
- __webpack_require__ @7104-7122; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @7126-7135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- __webpack_require__.n @7128-7134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7130-7130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7131-7131; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @7138-7147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- __webpack_require__.d @7140-7146; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @7150-7152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- __webpack_require__.o @7151-7151; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @7155-7163; ArrowFunctionExpression; parameters=0; async=false; generator=false
- __webpack_require__.r @7157-7162; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7168-7317; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _extends @7177-7177; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @7177-7177; FunctionExpression; parameters=1; async=false; generator=false
- constructor @7187-7193; FunctionExpression; parameters=1; async=false; generator=false
- fetchFxAFlowUri @7194-7198; FunctionExpression; parameters=0; async=true; generator=false
- componentDidMount @7199-7233; FunctionExpression; parameters=0; async=false; generator=false
- recordImpression @7205-7217; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @7224-7224; ArrowFunctionExpression; parameters=0; async=false; generator=false
- render @7234-7258; FunctionExpression; parameters=0; async=false; generator=false
- ComputeTelemetryInfo @7262-7275; FunctionDeclaration; parameters=3; async=false; generator=false
- retrieveRenderContent @7276-7303; FunctionDeclaration; parameters=0; async=true; generator=false
- mount @7304-7314; FunctionDeclaration; parameters=0; async=true; generator=false
- Class AboutWelcome @7186-7259
- Class ProtonScreen @1646-2209
- Class WelcomeScreen @752-1110

### browser/components/aboutwelcome/karma.mc.config.js

Blob: `bb7f6be6eccc46065b5631fbe22c56fa45046cbf`. Role: source. Parse: module.

- module.exports @34-161; FunctionExpression; parameters=1; async=false; generator=false

### browser/components/aboutwelcome/modules/AWToolbarUtils.sys.mjs

Blob: `6128bdb4ffdb8bbe09930c4383c702f33be2fc95`. Role: source. Parse: module.

- maybeAddSetupButton @17-51; FunctionExpression; parameters=0; async=true; generator=false
- onCreated @31-38; FunctionExpression; parameters=1; async=false; generator=false
- onCommand @39-41; FunctionExpression; parameters=1; async=false; generator=false
- onDestroyed @42-48; FunctionExpression; parameters=0; async=false; generator=false
- removeSetupButtonIfOnboardingComplete @53-62; FunctionExpression; parameters=0; async=false; generator=false
- openWelcome @64-73; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @81-83; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration

### browser/components/aboutwelcome/modules/AboutWelcomeDefaults.sys.mjs

Blob: `722291c313bf2e14e09bcc97032c98f354acad49`. Role: source. Parse: module.

- getAddonFromRepository @813-827; FunctionDeclaration; parameters=1; async=true; generator=false
- getAddonInfo @829-858; FunctionDeclaration; parameters=1; async=true; generator=false
- getAttributionContent @860-883; FunctionDeclaration; parameters=0; async=true; generator=false
- getDefaults @886-888; FunctionDeclaration; parameters=0; async=false; generator=false
- getLocalizedUA @896-909; FunctionDeclaration; parameters=1; async=false; generator=false
- prepareMobileDownload @911-928; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @913-913; ArrowFunctionExpression; parameters=1; async=false; generator=false
- prepareContentForReact @930-1008; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @951-953; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @974-976; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @983-983; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addMessageArgs @986-992; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1003-1003; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @12; ChromeUtils-import-literal
- Module resource:///modules/asrouter/MessagingTargetingConstants.sys.mjs @16; ImportDeclaration

### browser/components/aboutwelcome/modules/AboutWelcomeTelemetry.sys.mjs

Blob: `f19a2e977151aa4064c39e7b3ef06ee38df62b03`. Role: source. Parse: module.

- (anonymous) @20-21; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @23-31; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @35-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @46-53; FunctionExpression; parameters=0; async=false; generator=false
- _maybeAttachAttribution @67-73; FunctionExpression; parameters=1; async=false; generator=false
- _createPing @75-85; FunctionExpression; parameters=1; async=true; generator=false
- sendTelemetry @101-108; FunctionExpression; parameters=1; async=true; generator=false
- parseAndSubmitPing @110-170; FunctionExpression; parameters=1; async=false; generator=false
- submitGleanPingForPing @187-316; FunctionExpression; parameters=1; async=false; generator=false
- _snakeToCamelCase @318-322; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @319-321; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class AboutWelcomeTelemetry @45-323
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://messaging-system/lib/Logger.sys.mjs @39; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_animation_play_pause.js

Blob: `d526b872273323e4c894f09daaa0668cbd732cfd`. Role: test-path,source. Parse: module.

- (anonymous) @15-19; FunctionExpression; parameters=0; async=true; generator=false
- clickPlayPauseButton @21-29; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @22-28; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @24-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- expectButtonState @31-46; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @35-44; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @36-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- expectHeroSrc @48-59; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @52-57; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @53-56; ArrowFunctionExpression; parameters=0; async=false; generator=false
- expectSectionBackgroundUrl @61-72; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @65-70; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @66-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_button_without_static_fallback @77-97; FunctionExpression; parameters=0; async=true; generator=false
- test_button_toggles_static_and_animated @103-143; FunctionExpression; parameters=0; async=true; generator=false
- test_starts_paused_with_reduced_motion @150-179; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_attribution.js

Blob: `12f881e9a155dda487ea897fee4f8a7ced4f097e`. Role: test-path,source. Parse: module.

- openRTAMOWithAttribution @71-98; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @92-96; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_screen_content @103-131; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @112-129; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-137; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_rtamo_attribution @139-161; FunctionExpression; parameters=0; async=true; generator=false
- openMultiStageWithUserAgentAttribution @163-182; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @176-180; ArrowFunctionExpression; parameters=0; async=true; generator=false
- onButtonClick @184-197; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @188-195; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @190-190; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_ua_attribution @199-225; FunctionExpression; parameters=0; async=true; generator=false
- test_smart_window_attribution @227-260; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @255-259; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module resource:///modules/asrouter/ASRouter.sys.mjs @3; ChromeUtils-import-literal
- Module resource:///modules/aboutwelcome/AboutWelcomeDefaults.sys.mjs @6; ChromeUtils-import-literal
- Module moz-src:///browser/components/attribution/AttributionCode.sys.mjs @9; ChromeUtils-import-literal
- Module resource://gre/modules/addons/AddonRepository.sys.mjs @12; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_campaign_actions.js

Blob: `43ce653ef091025e31ab015e6fd315a70abd64a6`. Role: test-path,source. Parse: module.

- test_unhandled_campaign_action @35-99; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @90-96; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_campaign_action_honors_default_browser_pref @101-142; FunctionExpression; parameters=0; async=true; generator=false
- Module resource:///modules/asrouter/ASRouter.sys.mjs @3; ChromeUtils-import-literal
- Module moz-src:///browser/components/attribution/AttributionCode.sys.mjs @6; ChromeUtils-import-literal
- Module resource://messaging-system/lib/SpecialMessageActions.sys.mjs @9; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_configurable_ui.js

Blob: `c8e173138d9903aff776e641d425c1142393e0bf`. Role: test-path,source. Parse: module.

- (anonymous) @7-11; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @8-10; FunctionExpression; parameters=0; async=false; generator=false
- test_aboutwelcome_single_select_icon_styles @16-101; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_link_paragraph_inline_image @103-128; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_link_paragraph_segment_action @130-201; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @179-185; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @195-195; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/NimbusTestUtils.sys.mjs @3; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_corner_image.js

Blob: `1a22342b78074df6a4fc181f10a1f7c4daac4f80`. Role: test-path,source. Parse: module.

- makeCornerImageScreen @6-16; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @18-22; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- test_aboutwelcome_corner_image_positions @27-60; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_logical_positions @66-112; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @96-98; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_fallback_position @118-145; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_card_anchored_layouts @151-197; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_entrance_animations @203-232; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_entrance_fallback @238-272; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_entrance_timing @278-316; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_entrance_keeps_style @323-343; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_corner_image_rtl_selection @348-388; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @373-375; ArrowFunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_embedded_browser.js

Blob: `ff5c98ca3277b8e972575ae3b70e10f218ab2be4`. Role: test-path,source. Parse: module.

- test_aboutwelcome_does_not_render_embedded_browser_in_content @24-36; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_fxa_signin_flow.js

Blob: `0ec62e035672a54eb3278f8e3b8c27c57fbc57d9`. Role: test-path,source. Parse: module.

- (anonymous) @16-20; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_sign_success @26-59; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @28-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-56; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @34-38; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_sign_with_service_success @66-107; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-70; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @72-104; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @74-83; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_sign_success_no_autoclose @113-146; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-117; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @119-143; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @121-126; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_aborted @152-167; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @153-166; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @155-159; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_window_aborted @173-191; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @174-190; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @176-183; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_window_success @197-236; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @199-201; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-233; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @205-212; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_window_multiple_tabs_aborted @246-271; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @247-270; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @249-256; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_window_multiple_tabs_success @281-324; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @283-285; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @287-321; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @289-296; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_fxa_signin_flow_entrypoint_utm_params @330-355; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @331-354; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @333-344; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Module resource://services-sync/UIState.sys.mjs @6; ChromeUtils-import-literal
- Module resource://gre/modules/FxAccountsCommon.sys.mjs @10; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_glean.js

Blob: `6468db28bd0e654907c021123b15fd40a60f3611`. Role: test-path,source. Parse: module.

- test_welcome_telemetry @64-147; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @69-71; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @85-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-105; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-144; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource:///modules/aboutwelcome/AboutWelcomeTelemetry.sys.mjs @10; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_import.js

Blob: `82e646127e5cb6c7e89f4705d5464c4b97febfa5`. Role: test-path,source. Parse: module.

- (anonymous) @18-22; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @19-21; FunctionExpression; parameters=0; async=false; generator=false
- test_wait_import_modal @24-75; FunctionExpression; parameters=0; async=true; generator=false
- test_wait_import_spotlight @77-100; FunctionExpression; parameters=0; async=true; generator=false
- Module resource:///modules/asrouter/Spotlight.sys.mjs @79; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_impression_action.js

Blob: `0727686799953300e3818612bd0e51897ea0b34d`. Role: test-path,source. Parse: module.

- makeScreens @14-24; FunctionDeclaration; parameters=2; async=false; generator=false
- clearScreenImpression @26-32; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @27-31; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_allowlisted_impression_action_fires_once @34-103; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-61; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @73-73; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @88-90; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_non_allowlisted_impression_action_rejected @105-144; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @133-133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_multi_action_impression_fires @146-194; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @177-177; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @184-184; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource:///modules/asrouter/ASRouter.sys.mjs @3; ChromeUtils-import-literal
- Module resource://messaging-system/lib/SpecialMessageActions.sys.mjs @6; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_layout.js

Blob: `27831339f685978ec83cc04d4c233183385354bf`. Role: test-path,source. Parse: module.

- (anonymous) @7-11; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @8-10; FunctionExpression; parameters=0; async=false; generator=false
- test_aboutwelcome_with_dimensions @16-32; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_split_position @37-85; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_center_large_position @90-170; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @137-153; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @138-141; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_aboutwelcome_center_large_top_buttons_row @176-213; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_rdm_property @218-237; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_fullscreen_property @242-261; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_narrow_property @266-328; FunctionExpression; parameters=0; async=true; generator=false
- test_secondary_button_top_configuration @333-390; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_fullscreen_split_layout_styles @395-481; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/NimbusTestUtils.sys.mjs @3; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_logo.js

Blob: `ce4691d84ffe8b6f625b6396eb340a4331f94e66`. Role: test-path,source. Parse: module.

- testAboutWelcomeLogoFor @7-62; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @64-68; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-67; FunctionExpression; parameters=0; async=false; generator=false
- test_aboutwelcome_with_customized_logo @73-103; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_with_empty_logo_spacing @108-137; FunctionExpression; parameters=0; async=true; generator=false
- test_title_logo @142-160; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_logo_selection @166-195; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/NimbusTestUtils.sys.mjs @3; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_mobile_downloads.js

Blob: `f7d57db7e2a84773c57b233a618ce17b04e80459`. Role: test-path,source. Parse: module.

- test_aboutwelcome_mobile_downloads_all @29-45; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_mobile_downloads_qr_and_marketplace @52-71; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_mobile_downloads_qr @78-95; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multiselect.js

Blob: `3d13b60c7f66a0de851b88be692ee8b2ba72820e`. Role: test-path,source. Parse: module.

- test_multiselect_unchecked_notices @223-286; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @256-267; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_multiselect_with_item_description @292-318; FunctionExpression; parameters=0; async=true; generator=false
- test_card_multiselect_design @324-379; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @346-378; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_link_style_disclosure @385-534; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @431-475; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @479-499; ArrowFunctionExpression; parameters=0; async=true; generator=false
- edges @480-485; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @503-522; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_picker_multiselect_styles @539-573; FunctionExpression; parameters=0; async=true; generator=false

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multistage_addonspicker.js

Blob: `ed6c0bbb42b48b9ba23d76ff490e7dbba6dbd718`. Role: test-path,source. Parse: module.

- clickVisibleButton @17-36; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @19-35; ArrowFunctionExpression; parameters=1; async=true; generator=false
- getVisibleElement @20-27; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @38-45; FunctionExpression; parameters=0; async=true; generator=false
- test_aboutwelcome_addonspicker @47-313; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @163-165; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @209-211; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @231-233; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @258-260; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @269-269; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @288-290; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource:///actors/AboutWelcomeParent.sys.mjs @3; ChromeUtils-import-literal
- Module resource:///modules/aboutwelcome/AboutWelcomeTelemetry.sys.mjs @7; ChromeUtils-import-literal
- Module resource:///modules/asrouter/ASRouterScreenUtils.sys.mjs @10; ChromeUtils-import-literal
- Module moz-src:///browser/components/migration/InternalTestingProfileMigrator.sys.mjs @13; ChromeUtils-import-literal

### browser/components/aboutwelcome/tests/browser/browser_aboutwelcome_multistage_default.js

Blob: `d67f5b9cbde0c30466257569cc0d36f8472961c7`. Role: test-path,source. Parse: module.

- openAboutWelcome @153-170; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @162-165; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @166-168; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_multistage_aboutwelcome_default @175-295; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @181-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_Multistage_About_Welcome_navigation @300-325; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @304-304; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_AWMultistage_Primary_Action @330-413; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @335-337; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_AWMultistage_Secondary_Open_URL_Action @415-480; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @421-423; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_AWMultistage_Themes @482-555; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @489-491; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @504-511; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @506-506; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_AWMultistage_can_restore_theme @557-627; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @562-562; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @566-569; FunctionExpression; parameters=1; async=false; generator=false
- enable @571-576; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @589-589; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @589-589; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_AWMultistage_Import @629-697; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @649-651; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_updatesPrefOnAWOpen @699-710; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @705-706; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @712-722; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @719-721; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_FxA_metricsFlowURI @724-745; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @727-735; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @730-730; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_send_aboutwelcome_as_page_in_event_telemetry @747-781; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @778-780; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_AMO_untranslated_strings @783-820; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @794-796; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @816-819; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_set_default_pin_untranslated_strings @822-863; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @834-836; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @859-862; ArrowFunctionExpression; parameters=0; async=true; generator=false
- Class FakeAddon @565-577
- Module resource://messaging-system/lib/SpecialMessageActions.sys.mjs @2; ChromeUtils-import-literal
- Module resource://gre/modules/addons/XPIExports.sys.mjs @558; ChromeUtils-import-literal

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
