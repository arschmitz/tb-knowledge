<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["toolkit/components/passwordmgr/test/browser/browser_doorhanger_username_edits.js","toolkit/components/passwordmgr/test/browser/browser_doorhanger_window_open.js","toolkit/components/passwordmgr/test/browser/browser_entry_point_telemetry.js","toolkit/components/passwordmgr/test/browser/browser_exceptions_dialog.js","toolkit/components/passwordmgr/test/browser/browser_fileURIOrigin.js","toolkit/components/passwordmgr/test/browser/browser_focus_before_first_DOMContentLoaded.js","toolkit/components/passwordmgr/test/browser/browser_form_history_fallback.js","toolkit/components/passwordmgr/test/browser/browser_formless_submit_chrome.js","toolkit/components/passwordmgr/test/browser/browser_glean_pwmgr_form_autofill_result.js","toolkit/components/passwordmgr/test/browser/browser_insecurePasswordConsoleWarning.js","toolkit/components/passwordmgr/test/browser/browser_isProbablyASignUpForm.js","toolkit/components/passwordmgr/test/browser/browser_localip_frame.js","toolkit/components/passwordmgr/test/browser/browser_login_storage_migrator.js","toolkit/components/passwordmgr/test/browser/browser_message_onFormSubmit.js","toolkit/components/passwordmgr/test/browser/browser_openPasswordManager.js","toolkit/components/passwordmgr/test/browser/browser_preselect_login.js","toolkit/components/passwordmgr/test/browser/browser_primary_password_reauth.js","toolkit/components/passwordmgr/test/browser/browser_private_window.js","toolkit/components/passwordmgr/test/browser/browser_proxyAuth_prompt.js","toolkit/components/passwordmgr/test/browser/browser_relay_signup_flow.js","toolkit/components/passwordmgr/test/browser/browser_relay_signup_flow_showToAllBrowsers.js","toolkit/components/passwordmgr/test/browser/browser_relay_telemetry.js","toolkit/components/passwordmgr/test/browser/browser_relay_use.js","toolkit/components/passwordmgr/test/browser/browser_relay_utils.js","toolkit/components/passwordmgr/test/browser/browser_rust_storage_primary_password.js","toolkit/components/passwordmgr/test/browser/browser_telemetry_SignUpFormRuleset.js","toolkit/components/passwordmgr/test/browser/browser_test_changeContentInputValue.js","toolkit/components/passwordmgr/test/browser/browser_username_only_form_telemetry.js","toolkit/components/passwordmgr/test/browser/browser_username_select_dialog.js","toolkit/components/passwordmgr/test/browser/file_focus_before_DOMContentLoaded.sjs","toolkit/components/passwordmgr/test/browser/head.js","toolkit/components/passwordmgr/test/browser/slow_css.sjs","toolkit/components/passwordmgr/test/formsubmit.sjs","toolkit/components/passwordmgr/test/mochitest/.eslintrc.mjs","toolkit/components/passwordmgr/test/mochitest/auth2/authenticate.sjs","toolkit/components/passwordmgr/test/mochitest/chrome_timeout.js","toolkit/components/passwordmgr/test/mochitest/pwmgr_common.js","toolkit/components/passwordmgr/test/mochitest/pwmgr_common_parent.js","toolkit/components/passwordmgr/test/mochitest/slow_image.sjs","toolkit/components/passwordmgr/test/unit/head.js","toolkit/components/passwordmgr/test/unit/test_BreachAlertStore.js","toolkit/components/passwordmgr/test/unit/test_BreachAlertsData.js","toolkit/components/passwordmgr/test/unit/test_CSVParser.js","toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_doAutocompleteSearch.js","toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_getGeneratedPassword.js","toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_onPasswordEditedOrGenerated.js","toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_searchAndDedupeLogins.js","toolkit/components/passwordmgr/test/unit/test_LoginManagerPrompter_getUsernameSuggestions.js","toolkit/components/passwordmgr/test/unit/test_LoginStorageMigrator.js","toolkit/components/passwordmgr/test/unit/test_LoginStorageMigrator_nimbus.js","toolkit/components/passwordmgr/test/unit/test_OSCrypto_win.js","toolkit/components/passwordmgr/test/unit/test_PasswordGenerator.js","toolkit/components/passwordmgr/test/unit/test_PasswordRulesManager_generatePassword.js","toolkit/components/passwordmgr/test/unit/test_context_menu.js","toolkit/components/passwordmgr/test/unit/test_crypto_SDR_primary_password.js","toolkit/components/passwordmgr/test/unit/test_dedupeLogins.js","toolkit/components/passwordmgr/test/unit/test_disabled_hosts.js","toolkit/components/passwordmgr/test/unit/test_displayOrigin.js","toolkit/components/passwordmgr/test/unit/test_doLoginsMatch.js","toolkit/components/passwordmgr/test/unit/test_findRelatedRealms.js","toolkit/components/passwordmgr/test/unit/test_getFormFields.js","toolkit/components/passwordmgr/test/unit/test_getPasswordFields.js","toolkit/components/passwordmgr/test/unit/test_getPasswordOrigin.js","toolkit/components/passwordmgr/test/unit/test_getUserNameAndPasswordFields.js","toolkit/components/passwordmgr/test/unit/test_getUsernameFieldFromUsernameOnlyForm.js","toolkit/components/passwordmgr/test/unit/test_isInferredLoginForm.js","toolkit/components/passwordmgr/test/unit/test_isInferredUsernameField.js","toolkit/components/passwordmgr/test/unit/test_isOriginMatching.js","toolkit/components/passwordmgr/test/unit/test_isProbablyANewPasswordField.js","toolkit/components/passwordmgr/test/unit/test_isUsernameFieldType.js","toolkit/components/passwordmgr/test/unit/test_legacy_empty_formActionOrigin.js","toolkit/components/passwordmgr/test/unit/test_legacy_validation.js","toolkit/components/passwordmgr/test/unit/test_login_autocomplete_result.js","toolkit/components/passwordmgr/test/unit/test_loginsBackup.js","toolkit/components/passwordmgr/test/unit/test_logins_change.js","toolkit/components/passwordmgr/test/unit/test_logins_decrypt_failure.js","toolkit/components/passwordmgr/test/unit/test_logins_metainfo.js","toolkit/components/passwordmgr/test/unit/test_logins_search.js","toolkit/components/passwordmgr/test/unit/test_maybeImportLogin.js","toolkit/components/passwordmgr/test/unit/test_module_LoginCSVImport.js","toolkit/components/passwordmgr/test/unit/test_module_LoginExport.js","toolkit/components/passwordmgr/test/unit/test_module_LoginManager.js","toolkit/components/passwordmgr/test/unit/test_module_LoginStore.js","toolkit/components/passwordmgr/test/unit/test_notifications.js","toolkit/components/passwordmgr/test/unit/test_recipes_add.js","toolkit/components/passwordmgr/test/unit/test_recipes_content.js","toolkit/components/passwordmgr/test/unit/test_reencrypt.js","toolkit/components/passwordmgr/test/unit/test_remote_recipes.js","toolkit/components/passwordmgr/test/unit/test_search_schemeUpgrades.js","toolkit/components/passwordmgr/test/unit/test_shadowHTTPLogins.js","toolkit/components/passwordmgr/test/unit/test_storage.js","toolkit/components/passwordmgr/test/unit/test_storage_rust_shutdown.js","toolkit/components/passwordmgr/test/unit/test_telemetry.js","toolkit/components/passwordmgr/test/unit/test_vulnerable_passwords.js","toolkit/components/pdfjs/PdfJsDefaultPrefs.js","toolkit/components/pdfjs/PdfJsOverridePrefs.js","toolkit/components/pdfjs/content/GeckoViewPdfJsChild.sys.mjs","toolkit/components/pdfjs/content/GeckoViewPdfJsParent.sys.mjs","toolkit/components/pdfjs/content/PdfEmbedFallbackParent.sys.mjs","toolkit/components/pdfjs/content/PdfEmbedFallbackStreamConverter.sys.mjs","toolkit/components/pdfjs/content/PdfJs.sys.mjs","toolkit/components/pdfjs/content/PdfJsAIFeature.sys.mjs","toolkit/components/pdfjs/content/PdfJsChild.sys.mjs","toolkit/components/pdfjs/content/PdfJsContextMenu.sys.mjs","toolkit/components/pdfjs/content/PdfJsFeaturesNotification.sys.mjs","toolkit/components/pdfjs/content/PdfJsNetwork.sys.mjs","toolkit/components/pdfjs/content/PdfJsParent.sys.mjs","toolkit/components/pdfjs/content/PdfJsPrint.sys.mjs","toolkit/components/pdfjs/content/PdfJsTelemetry.sys.mjs","toolkit/components/pdfjs/content/PdfJsVersion.sys.mjs","toolkit/components/pdfjs/content/PdfSandbox.sys.mjs"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/toolkit JavaScript function map 1329

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### toolkit/components/passwordmgr/test/browser/browser_doorhanger_username_edits.js

Blob: `589db80a1973f2bbe0cc54faff3676e0cf616177`. Role: test-path,source. Parse: module.

- test_edit_username @9-184; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @89-181; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @123-123; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @125-127; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @157-157; ArrowFunctionExpression; parameters=2; async=false; generator=false
- initForm @186-196; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @190-194; FunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_doorhanger_window_open.js

Blob: `514994b63d7c767e9a65d074373844f6edeb733f`. Role: test-path,source. Parse: module.

- withTestTabUntilStorageChange @29-55; FunctionDeclaration; parameters=2; async=false; generator=false
- storageChangedObserved @30-36; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @47-53; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @57-59; FunctionExpression; parameters=0; async=true; generator=false
- test_saveChromeHiddenAutoClose @61-98; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @70-82; FunctionExpression; parameters=0; async=true; generator=false
- test_changeChromeHiddenAutoClose @100-145; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @103-122; FunctionExpression; parameters=0; async=true; generator=false
- test_saveChromeVisibleSameWindow @147-178; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @154-161; FunctionExpression; parameters=0; async=true; generator=false
- test_changeChromeVisibleSameWindow @180-217; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @186-193; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_entry_point_telemetry.js

Blob: `d0be77e5bfdef46ad6c169820620854dee7d212c`. Role: test-path,source. Parse: module.

- (anonymous) @3-5; FunctionExpression; parameters=0; async=true; generator=false
- mainMenu_entryPoint @7-58; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @14-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openingFunc @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- pageInfo_entryPoint @60-100; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-98; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openingFunc @83-84; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_exceptions_dialog.js

Blob: `5ec0231f292d5af7139d6b8fc7bcb6419dd40ee2`. Role: test-path,source. Parse: module.

- openExceptionsDialog @5-19; FunctionDeclaration; parameters=0; async=false; generator=false
- countDisabledHosts @21-23; FunctionDeclaration; parameters=1; async=false; generator=false
- promiseStorageChanged @25-34; FunctionDeclaration; parameters=1; async=false; generator=false
- observer @26-31; FunctionDeclaration; parameters=2; async=false; generator=false
- test_disable @36-48; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @41-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_enable @50-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @55-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_block_button_with_enter_key @64-142; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @71-71; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_fileURIOrigin.js

Blob: `ae8c8607928432cfd412cc7ea68a5c85d0cef150`. Role: test-path,source. Parse: module.

- getDataFromNextSubmitMessage @6-14; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @7-13; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @8-12; ArrowFunctionExpression; parameters=2; async=false; generator=false
- testCrossOriginFormUsesCorrectOrigin @16-51; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-40; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @33-39; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_focus_before_first_DOMContentLoaded.js

Blob: `06a9e31cb0e0e57f8ee672bf335c991d60f8cad0`. Role: test-path,source. Parse: module.

- (anonymous) @8-34; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_autocompleteFromUsername @36-114; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @54-56; ArrowFunctionExpression; parameters=0; async=true; generator=false
- checkInitialValues @63-78; FunctionExpression; parameters=0; async=false; generator=false
- checkFill @104-111; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_form_history_fallback.js

Blob: `b10bd6c5fe183cfe1b44ff04c9996a95c42377a2`. Role: test-path,source. Parse: module.

- cleanup @9-13; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @15-17; FunctionExpression; parameters=0; async=true; generator=false
- test_username_not_saved_in_form_history_when_password_manager_enabled @20-54; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @30-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_username_saved_in_form_history_when_password_manager_disabled @58-74; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/FormHistoryTestUtils.sys.mjs @1; ChromeUtils-import-literal
- Module resource://gre/modules/FormHistory.sys.mjs @4; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_formless_submit_chrome.js

Blob: `ae86ea78fc34d18cfb4dfb74b8882bd7351a211b`. Role: test-path,source. Parse: module.

- fillTestPage @7-26; FunctionDeclaration; parameters=3; async=true; generator=false
- withTestPage @28-48; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @35-46; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @42-42; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @50-52; FunctionExpression; parameters=0; async=true; generator=false
- test_urlbar_new_URL @54-72; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @55-71; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_urlbar_fragment_enter @74-82; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @75-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_backButton_forwardButton @84-133; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @85-132; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @115-115; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @122-124; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_reloadButton @135-152; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @136-151; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @145-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_back_keyboard_shortcut @154-180; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @155-179; ArrowFunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_glean_pwmgr_form_autofill_result.js

Blob: `e825a505483541d9c49ea0869bc6efb7156628d2`. Role: test-path,source. Parse: module.

- (anonymous) @120-122; ArrowFunctionExpression; parameters=0; async=true; generator=false
- verifyAutofillResults @124-180; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @155-171; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_autofill_results @182-186; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManagerChild.sys.mjs @10; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_insecurePasswordConsoleWarning.js

Blob: `5116bc9235683d3d84480e142d98f5dba313f76a`. Role: test-path,source. Parse: module.

- testInsecurePasswordWarning @14-131; FunctionExpression; parameters=0; async=true; generator=false
- messageHandler @21-40; FunctionDeclaration; parameters=1; async=false; generator=false
- findWarningPattern @22-26; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @23-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-44; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-111; ArrowFunctionExpression; parameters=1; async=false; generator=false
- warningPatternHandler @87-110; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @118-124; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_isProbablyASignUpForm.js

Blob: `cc8bc63e7a5cee9f2eac6961d3889af73d10c207`. Role: test-path,source. Parse: module.

- (anonymous) @5-52; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @11-50; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @12-49; ArrowFunctionExpression; parameters=0; async=true; generator=false
- assertSignUpForm @18-29; FunctionDeclaration; parameters=4; async=false; generator=false
- Module resource://gre/modules/FormScenarios.sys.mjs @14; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_localip_frame.js

Blob: `4c3957c857499a505649af8f01f7a5a60fd41bcc`. Role: test-path,source. Parse: module.

- (anonymous) @3-22; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_warningForLocalIP @24-91; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @57-64; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @58-63; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @84-84; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_login_storage_migrator.js

Blob: `6f7889d49b4a68b90cd01f4a523e81686f2a091e`. Role: test-path,source. Parse: module.

- cleanup @44-62; FunctionDeclaration; parameters=0; async=true; generator=false
- migrate @64-66; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @68-78; FunctionExpression; parameters=0; async=true; generator=false
- report_result_under_rust_backend @82-86; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_moves_logins_to_rust @88-119; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_is_idempotent @121-143; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_quarantines_real_duplicate @145-183; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @172-172; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @173-174; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_migration_moves_vulnerable_passwords @185-205; FunctionExpression; parameters=0; async=true; generator=false
- test_restore_counts_a_login_deleted_in_rust @210-249; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @228-228; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @235-235; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_storage_operation_time_telemetry @253-279; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @269-269; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://passwordmgr/passwordstorage.sys.mjs @14; ChromeUtils-import-literal
- Module resource://gre/modules/storage-rust.sys.mjs @17; ChromeUtils-import-literal
- Module resource://gre/modules/LoginStorageMigrator.sys.mjs @20; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_message_onFormSubmit.js

Blob: `1940d6407397969e339e4ad252bae392bdb825c6`. Role: test-path,source. Parse: module.

- waitForFormSubmissionDetected @6-16; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @7-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- observer @8-14; FunctionExpression; parameters=3; async=false; generator=false
- test_login_save_disable @18-47; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @30-45; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @38-41; FunctionExpression; parameters=0; async=true; generator=false
- test_login_save_enable @49-82; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @61-80; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @73-76; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_openPasswordManager.js

Blob: `af5d70e259e401e07e990cbe01850c2fef72f9d6`. Role: test-path,source. Parse: module.

- test_noFilter @5-15; FunctionExpression; parameters=0; async=true; generator=false
- openingFunc @6-7; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @12-14; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_filter @17-35; FunctionExpression; parameters=0; async=true; generator=false
- openingFunc @20-24; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @32-34; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_management_noFilter @37-43; FunctionExpression; parameters=0; async=true; generator=false
- test_management_filter @45-58; FunctionExpression; parameters=0; async=true; generator=false
- test_url_when_opening_password_manager_without_a_filterString @61-90; FunctionExpression; parameters=0; async=true; generator=false
- openingFunc @63-67; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @78-78; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_url_when_opening_password_manager_with_a_filterString @94-123; FunctionExpression; parameters=0; async=true; generator=false
- openingFunc @96-100; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-111; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_url_when_opening_password_manager_without_filterString_or_entryPoint @127-160; FunctionExpression; parameters=0; async=true; generator=false
- openingFunc @129-133; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @148-148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://testing-common/Sinon.sys.mjs @1; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_preselect_login.js

Blob: `1a9d7fa7bb70393f05d7f0676c190c81657e1a1f`. Role: test-path,source. Parse: module.

- waitForAppMenu @26-42; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isExpectedLoginItemSelected @44-60; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @48-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-70; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_about_logins_defaults_to_first_item @72-91; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @78-89; FunctionExpression; parameters=1; async=true; generator=false
- test_gear_icon_opens_about_logins_with_preselected_login @94-151; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @100-149; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @121-121; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @134-134; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_edit_button_keyboard_opens_about_logins_with_preselected_login @155-213; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @162-210; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @178-178; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @184-184; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @195-195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_edit_button_subfocus_cleared_by_navigation @216-266; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @222-264; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @235-235; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @241-241; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @247-247; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @253-253; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @259-259; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_edit_button_subfocus_announced_to_a11y @268-317; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @274-315; FunctionExpression; parameters=1; async=true; generator=false
- window.A11yUtils.announce @286-289; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @295-295; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @301-301; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @307-307; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_edit_button_hidden_for_pointer_selection @319-406; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @325-404; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @347-350; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @358-358; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @386-386; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_password_menu_opens_about_logins_with_preselected_login @409-441; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @415-439; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @424-424; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_new_login_url_has_correct_hash @444-476; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @450-474; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @451-473; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @461-464; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_no_logins_empty_url_hash @478-505; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @485-503; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @494-494; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_primary_password_reauth.js

Blob: `396c2c8f0c57dac64fe72f16df566591e005f664`. Role: test-path,source. Parse: module.

- test_single_prompt_when_storage_races_reauth @13-68; FunctionExpression; parameters=0; async=true; generator=false
- observer @31-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-43; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_declined_write_reports_abort @74-126; FunctionExpression; parameters=0; async=true; generator=false
- observer @82-88; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @90-93; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @112-112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @113-113; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_private_window.js

Blob: `04a7bda5dc3ad1dea8b8cc2f5d720a384f112d82`. Role: test-path,source. Parse: module.

- focusWindow @3-18; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @7-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-12; FunctionExpression; parameters=0; async=false; generator=false
- getDialogDoc @20-55; FunctionDeclaration; parameters=0; async=false; generator=false
- waitForAuthPrompt @57-63; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @58-60; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAuthPrompt @65-71; FunctionDeclaration; parameters=0; async=false; generator=false
- loadAccessRestrictedURL @73-86; FunctionDeclaration; parameters=4; async=true; generator=false
- test_setup @113-117; FunctionExpression; parameters=0; async=true; generator=false
- test_normal_popup_notification_1 @119-162; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @127-160; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @155-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_private_popup_notification_2 @164-241; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @185-234; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @213-213; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_private_popup_notification_no_capture_pref_2b @243-305; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @263-298; FunctionExpression; parameters=1; async=true; generator=false
- test_normal_popup_notification_3 @307-365; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @327-352; FunctionExpression; parameters=1; async=true; generator=false
- test_private_popup_notification_3b @367-426; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @387-413; FunctionExpression; parameters=1; async=true; generator=false
- test_normal_new_password_4 @428-489; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @447-474; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @469-469; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_private_new_password_5 @491-559; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @517-544; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @539-539; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_normal_with_login_6 @561-603; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @573-601; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @595-595; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_normal_autofilled_7 @605-647; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @622-645; FunctionExpression; parameters=1; async=true; generator=false
- test_private_not_autofilled_8 @649-677; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @666-675; FunctionExpression; parameters=1; async=true; generator=false
- test_normal_autofilled_10 @721-759; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @740-757; FunctionExpression; parameters=1; async=true; generator=false
- test_normal_http_basic_auth @761-820; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @774-818; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @782-791; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @813-813; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_private_http_basic_auth @822-876; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @843-874; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @869-869; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_private_http_basic_auth_no_capture_pref @878-933; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @898-931; FunctionExpression; parameters=1; async=true; generator=false
- test_cleanup @935-938; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_proxyAuth_prompt.js

Blob: `f6fef84b818f0ec343b8d6f92483008ba7fe3bfc`. Role: test-path,source. Parse: module.

- initProxy @9-60; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @10-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onProxyAvailable @16-42; FunctionExpression; parameters=4; async=false; generator=false
- onStartRequest @18-20; FunctionExpression; parameters=1; async=false; generator=false
- onStopRequest @21-21; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @62-64; FunctionExpression; parameters=0; async=true; generator=false
- getAuthPromptCallback @75-86; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @77-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onAuthAvailable @81-83; FunctionExpression; parameters=2; async=false; generator=false
- testProxyAuthPromptMerge @93-179; FunctionExpression; parameters=0; async=true; generator=false
- Class ProxyChannelListener @17-22

### toolkit/components/passwordmgr/test/browser/browser_relay_signup_flow.js

Blob: `822d83eaca0b4cad29e5726d2c207f3caea203ad`. Role: test-path,source. Parse: module.

- test_default_does_not_display_Relay_to_unauthenticated_browser @9-26; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-24; FunctionExpression; parameters=1; async=true; generator=false
- test_default_displays_Relay_to_signed_in_browser @29-52; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @38-47; FunctionExpression; parameters=1; async=true; generator=false
- test_site_not_on_allowList_still_shows_Relay_to_browser_that_already_enabled @55-79; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @66-75; FunctionExpression; parameters=1; async=true; generator=false
- test_authenticated_browser_use_email_mask_calls_fxa_and_relay_functions @83-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @94-115; FunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_relay_signup_flow_showToAllBrowsers.js

Blob: `03c9883ed2f16590e2ae775d44d9e9d8c9d4acf4`. Role: test-path,source. Parse: module.

- (anonymous) @8-12; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @14-21; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_showToAllBrowsers_displays_Relay_autocomplete_item_to_unauthenticated_browser @24-43; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-40; FunctionExpression; parameters=1; async=true; generator=false
- test_site_not_on_allowList_doesnt_show_Relay @46-67; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @55-64; FunctionExpression; parameters=1; async=true; generator=false
- test_showToAllBrowsers_open_ACPopup_twice_calls_RemoteSettings_once @70-112; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @77-86; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @95-104; FunctionExpression; parameters=1; async=true; generator=false
- test_showToAllBrowsers_click_on_Relay_opens_optin_prompt @116-151; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @123-148; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @146-146; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_dismiss_Relay_optin_shows_Relay_again_later @154-182; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @161-179; FunctionExpression; parameters=1; async=true; generator=false
- clickThruMoreActionsToDisableRelay @184-199; FunctionDeclaration; parameters=1; async=true; generator=false
- test_disable_Relay_optin_does_not_show_Relay_again_later @202-229; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @209-223; FunctionExpression; parameters=1; async=true; generator=false
- test_disable_Relay_optin_can_reenable_via_preferences @233-297; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @241-255; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @264-276; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @268-273; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @284-293; FunctionExpression; parameters=1; async=true; generator=false
- test_unauthenticated_browser_use_email_mask_opens_fxa_signin @301-396; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @317-320; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @341-385; FunctionExpression; parameters=1; async=true; generator=false
- isSigninUrl @353-368; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @388-390; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/browser_relay_telemetry.js

Blob: `389ba2d22eb8201894c1867154ca7059b4a5c698`. Role: test-path,source. Parse: module.

- collectRelayTelemeryEvent @8-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=3; async=false; generator=false
- waitForEvents @19-29; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @21-23; ArrowFunctionExpression; parameters=0; async=false; generator=false
- assertEvents @31-48; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @36-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openRelayAC @50-69; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @62-62; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @74-87; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @80-84; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_pref_toggle @89-114; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @96-112; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_popup_option_optin_enabled @116-185; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @125-182; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @167-173; FunctionExpression; parameters=0; async=true; generator=false
- test_popup_option_optin_postponed @187-224; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @195-221; FunctionExpression; parameters=1; async=true; generator=false
- test_popup_option_optin_disabled @226-262; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @234-259; FunctionExpression; parameters=1; async=true; generator=false
- test_popup_option_fillusername @264-290; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @273-286; FunctionExpression; parameters=1; async=true; generator=false
- test_fillusername_free_tier_limit @292-351; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @302-348; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @340-347; FunctionExpression; parameters=0; async=true; generator=false
- test_fillusername_error @353-394; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @363-391; FunctionExpression; parameters=1; async=true; generator=false
- test_auth_token_error @396-447; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @406-443; FunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_relay_use.js

Blob: `e5a20d9fc9a0f5e8acad905fd381fe0264ab27bc`. Role: test-path,source. Parse: module.

- test_site_on_denyList_does_not_show_Relay_to_signed_in_browser @9-36; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @22-31; FunctionExpression; parameters=1; async=true; generator=false
- test_domain_allow_denylist_across_scenarios @39-155; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @120-120; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @123-123; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @138-148; FunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_relay_utils.js

Blob: `c1a31aa4acff47756de468da40820259391174ac`. Role: test-path,source. Parse: module.

- POST @46-49; ArrowFunctionExpression; parameters=2; async=false; generator=false
- GET @50-52; ArrowFunctionExpression; parameters=2; async=false; generator=false
- default @57-59; ArrowFunctionExpression; parameters=2; async=false; generator=false
- default @64-67; ArrowFunctionExpression; parameters=2; async=false; generator=false
- simpleRouter @71-79; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @71-79; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setupServerScenario @80-82; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setUpMockRelayServer @84-101; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @96-100; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=1; async=false; generator=false
- stubRemoteSettingsAllowList @103-115; FunctionDeclaration; parameters=1; async=true; generator=false
- stubRemoteSettingsDenyList @117-129; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @131-140; FunctionExpression; parameters=0; async=true; generator=false
- stubFxAccountsToSimulateSignedIn @142-154; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @152-152; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getRelayItemFromACPopup @156-164; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @158-161; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @160-160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- waitForElementById @166-172; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @170-170; ArrowFunctionExpression; parameters=0; async=false; generator=false
- clickRelayItemAndWaitForPopup @174-184; FunctionDeclaration; parameters=1; async=true; generator=false
- clickButtonAndWaitForPopupToClose @186-194; FunctionDeclaration; parameters=1; async=true; generator=false
- setupRelayScenario @196-201; ArrowFunctionExpression; parameters=1; async=true; generator=false
- Module resource://testing-common/httpd.sys.mjs @3; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @6; ChromeUtils-import-literal
- Module resource://gre/modules/FxAccounts.sys.mjs @9; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_rust_storage_primary_password.js

Blob: `94c1c6d7e94e012f9dd26361384343b3985046d3`. Role: test-path,source. Parse: module.

- answerPrimaryPasswordDialogs @27-44; FunctionDeclaration; parameters=1; async=false; generator=false
- observer @29-38; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @40-43; ArrowFunctionExpression; parameters=0; async=false; generator=false
- rustPromptEvents @46-50; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-69; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-68; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_wrong_password_then_success @71-94; FunctionExpression; parameters=0; async=true; generator=false
- test_cancel @96-115; FunctionExpression; parameters=0; async=true; generator=false
- test_count_does_not_prompt @117-132; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/storage-rust.sys.mjs @12; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/browser_telemetry_SignUpFormRuleset.js

Blob: `23d177adb62d9ef0b5f2732d8d0a58ae290a9081`. Role: test-path,source. Parse: module.

- countEntries @11-15; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @13-13; ArrowFunctionExpression; parameters=2; async=false; generator=false
- countEntriesOfChildHistogram @21-34; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @23-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @36-38; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @40-50; ArrowFunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_test_changeContentInputValue.js

Blob: `74ae53778862bd628518dd60dd78cf82ee106b5e`. Role: test-path,source. Parse: module.

- (anonymous) @41-43; FunctionExpression; parameters=0; async=true; generator=false
- testStringChange @48-112; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @71-110; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @82-102; FunctionExpression; parameters=1; async=true; generator=false
- verifyKeyListener @85-99; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @95-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkForm @114-130; FunctionDeclaration; parameters=2; async=true; generator=false
- contentCheckForm @118-128; FunctionExpression; parameters=1; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_username_only_form_telemetry.js

Blob: `37238069b181198ce0c592c9e6cd512da19561bd`. Role: test-path,source. Parse: module.

- setupForms @8-57; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @23-53; FunctionExpression; parameters=1; async=true; generator=false
- addForm @25-43; FunctionDeclaration; parameters=1; async=false; generator=false
- checkChildHistogram @59-71; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @61-69; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @73-85; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @83-83; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_oneUsernameOnlyForm @87-101; FunctionExpression; parameters=0; async=true; generator=false
- test_multipleUsernameOnlyForms @103-117; FunctionExpression; parameters=0; async=true; generator=false
- test_multipleDocument @119-150; FunctionExpression; parameters=0; async=true; generator=false
- test_tooManyUsernameOnlyForms @152-166; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/browser/browser_username_select_dialog.js

Blob: `0bb67bea648f27ebe98dc29c7275a4b451680514`. Role: test-path,source. Parse: module.

- getSelectDialogDoc @7-32; FunctionDeclaration; parameters=0; async=false; generator=false
- test_changeUPLoginOnPUpdateForm_accept @58-125; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @67-67; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @72-100; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @87-93; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @97-99; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_changeUPLoginOnPUpdateForm_cancel @127-184; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @137-165; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @152-158; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @162-164; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/browser/file_focus_before_DOMContentLoaded.sjs

Blob: `234bcc70d82a5ef5a27b37b578c7e8e614eed724`. Role: test-path,data-or-other. Parse: module.

- handleRequest @13-32; FunctionDeclaration; parameters=2; async=false; generator=false
- finishOutput @28-31; FunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/Timer.sys.mjs @9; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/head.js

Blob: `30d41388bc6524fe6dbebc7eb65ed6c66bca596e`. Role: test-path,source. Parse: module.

- common_initialize @14-29; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @25-27; FunctionExpression; parameters=0; async=true; generator=false
- cleanup_checkNotificationsFromClosedTabs @34-40; FunctionExpression; parameters=0; async=false; generator=false
- cleanup_removeAllLoginsAndResetRecipes @43-62; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyLogins @72-125; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @74-74; ArrowFunctionExpression; parameters=2; async=false; generator=false
- submitFormAndGetResults @136-186; FunctionDeclaration; parameters=4; async=true; generator=false
- contentSubmitForm @142-170; FunctionDeclaration; parameters=1; async=true; generator=false
- getFormSubmitResponseResult @196-227; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @203-205; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @210-224; ArrowFunctionExpression; parameters=2; async=false; generator=false
- testSubmittingLoginForm @238-261; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @248-259; FunctionExpression; parameters=1; async=true; generator=false
- testSubmittingLoginFormHTTP @271-277; FunctionDeclaration; parameters=3; async=false; generator=false
- checkOnlyLoginWasUsedTwice @279-311; FunctionDeclaration; parameters=1; async=true; generator=false
- clearHttpAuths @313-318; FunctionDeclaration; parameters=0; async=false; generator=false
- getCaptureDoorhanger @338-371; FunctionDeclaration; parameters=3; async=false; generator=false
- getCaptureDoorhangerThatMayOpen @373-388; FunctionDeclaration; parameters=3; async=true; generator=false
- waitForDoorhanger @390-409; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @392-402; ArrowFunctionExpression; parameters=0; async=false; generator=false
- hideDoorhangerPopup @411-421; FunctionDeclaration; parameters=0; async=true; generator=false
- getDoorhangerButton @423-435; FunctionDeclaration; parameters=2; async=false; generator=false
- clickDoorhangerButton @444-462; FunctionDeclaration; parameters=2; async=true; generator=false
- cleanupDoorhanger @464-474; FunctionDeclaration; parameters=1; async=true; generator=false
- cleanupPasswordNotifications @476-483; FunctionDeclaration; parameters=1; async=true; generator=false
- clearMessageCache @485-495; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @486-494; ArrowFunctionExpression; parameters=0; async=true; generator=false
- checkDoorhangerUsernamePassword @503-518; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @506-513; ArrowFunctionExpression; parameters=0; async=false; generator=false
- updateDoorhangerInputValues @531-574; FunctionDeclaration; parameters=2; async=true; generator=false
- setInputValue @544-555; FunctionDeclaration; parameters=2; async=true; generator=false
- selectDoorhangerUsername @582-584; FunctionDeclaration; parameters=1; async=true; generator=false
- _selectDoorhanger @586-633; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @604-604; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @614-614; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @616-618; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openPasswordManager @637-668; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @641-641; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @649-660; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @656-656; ArrowFunctionExpression; parameters=0; async=false; generator=false
- close @664-666; FunctionExpression; parameters=0; async=false; generator=false
- openACPopup @672-696; FunctionDeclaration; parameters=4; async=true; generator=false
- openAutocomplete @688-690; FunctionExpression; parameters=1; async=false; generator=false
- closePopup @698-706; FunctionDeclaration; parameters=1; async=true; generator=false
- fillGeneratedPasswordFromOpenACPopup @708-746; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @716-719; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForInput @726-733; FunctionExpression; parameters=1; async=true; generator=false
- openPasswordContextMenu @756-816; FunctionDeclaration; parameters=5; async=true; generator=false
- listenForTestNotification @834-870; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @844-869; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @845-868; ArrowFunctionExpression; parameters=2; async=false; generator=false
- doFillGeneratedPasswordContextMenuItem @875-908; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @899-901; ArrowFunctionExpression; parameters=1; async=false; generator=false
- changeContentFormValues @911-921; FunctionDeclaration; parameters=3; async=true; generator=false
- changeContentInputValue @923-984; FunctionDeclaration; parameters=4; async=true; generator=false
- (anonymous) @932-934; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @946-980; FunctionExpression; parameters=1; async=true; generator=false
- verifyConfirmationHint @986-1026; FunctionDeclaration; parameters=4; async=true; generator=false
- Module resource://testing-common/LoginTestUtils.sys.mjs @3; ChromeUtils-import-literal
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @7; ChromeUtils-import-literal
- Module resource://testing-common/PromptTestUtils.sys.mjs @10; ChromeUtils-import-literal
- Module resource://testing-common/WrapPrivileged.sys.mjs @143; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerChild.sys.mjs @487; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/browser/slow_css.sjs

Blob: `b74c057bccfeccd99d7f2d40d4693a84f37090bd`. Role: test-path,data-or-other. Parse: module.

- handleRequest @1-15; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @8-11; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/formsubmit.sjs

Blob: `f519234d36408df63fc38781800865fa89ed42e3`. Role: test-path,data-or-other. Parse: module.

- handleRequest @1-8; FunctionDeclaration; parameters=2; async=false; generator=false
- reallyHandleRequest @10-37; FunctionDeclaration; parameters=2; async=false; generator=false

### toolkit/components/passwordmgr/test/mochitest/.eslintrc.mjs

Blob: `afa40d3dd603d3f59cb72875b9a69ea5481f51e0`. Role: test-path,source. Parse: module.


### toolkit/components/passwordmgr/test/mochitest/auth2/authenticate.sjs

Blob: `bc11bb29f8815453774a82d0ffd9bcd9c863baac`. Role: test-path,data-or-other. Parse: module.

- handleRequest @1-8; FunctionDeclaration; parameters=2; async=false; generator=false
- reallyHandleRequest @10-216; FunctionDeclaration; parameters=2; async=false; generator=false

### toolkit/components/passwordmgr/test/mochitest/chrome_timeout.js

Blob: `854a1e5d9a7b458705b75a3196ae7b4a51d3402b`. Role: test-path,source. Parse: module.

- (anonymous) @2-10; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4-6; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/components/passwordmgr/test/mochitest/pwmgr_common.js

Blob: `ea5125ad89a6d6671a3f52e854b3207aba6a2f91`. Role: test-path,source. Parse: module.

- (anonymous) @14-16; ArrowFunctionExpression; parameters=3; async=false; generator=false
- recreateTree @32-35; FunctionDeclaration; parameters=1; async=false; generator=false
- _checkArrayValues @37-46; FunctionDeclaration; parameters=3; async=false; generator=false
- checkAutoCompleteResults @52-81; FunctionDeclaration; parameters=4; async=false; generator=false
- untilAutocompletePopupClosed @88-93; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @89-92; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getIframeBrowsingContext @95-98; FunctionDeclaration; parameters=2; async=false; generator=false
- setUserInputValues @104-127; FunctionDeclaration; parameters=3; async=false; generator=false
- getSubmitMessage @133-153; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @135-152; ArrowFunctionExpression; parameters=1; async=false; generator=false
- processed @138-150; FunctionExpression; parameters=1; async=false; generator=false
- getPasswordEditedMessage @158-173; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @160-172; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @163-170; FunctionExpression; parameters=1; async=false; generator=false
- createLoginForm @199-299; FunctionDeclaration; parameters=1; async=false; generator=false
- form.onsubmit @228-228; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkLoginForm @306-323; FunctionDeclaration; parameters=4; async=false; generator=false
- ensureCondition @331-359; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @336-358; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @339-357; FunctionExpression; parameters=0; async=true; generator=false
- ensureLoginFormStaysFilledWith @373-385; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @379-384; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkLoginFormInFrame @387-421; FunctionDeclaration; parameters=5; async=false; generator=false
- (anonymous) @397-419; ArrowFunctionExpression; parameters=4; async=false; generator=false
- checkUnmodifiedFormInFrame @423-443; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @424-442; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkLoginFormInFrameWithElementValues @455-533; FunctionDeclaration; parameters=3; async=true; generator=false
- checkFormWithElementValues @463-531; FunctionExpression; parameters=2; async=false; generator=false
- checkForm @542-590; FunctionDeclaration; parameters=4; async=false; generator=false
- checkUnmodifiedForm @598-616; FunctionDeclaration; parameters=1; async=false; generator=false
- registerRunTests @625-676; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @626-675; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onDOMContentLoaded @627-662; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @640-657; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @653-656; ArrowFunctionExpression; parameters=0; async=false; generator=false
- enablePrimaryPassword @678-680; FunctionDeclaration; parameters=0; async=true; generator=false
- disablePrimaryPassword @682-684; FunctionDeclaration; parameters=0; async=true; generator=false
- setPrimaryPassword @686-701; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @687-698; ArrowFunctionExpression; parameters=1; async=false; generator=false
- primaryPasswordSet @690-696; FunctionExpression; parameters=0; async=false; generator=false
- isLoggedIn @703-705; FunctionDeclaration; parameters=0; async=false; generator=false
- logoutPrimaryPassword @707-714; FunctionDeclaration; parameters=0; async=false; generator=false
- parent_logoutPrimaryPassword @708-713; FunctionExpression; parameters=0; async=false; generator=false
- promiseFormsProcessedInSameProcess @720-736; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @722-735; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onProcessedForm @723-733; FunctionDeclaration; parameters=3; async=false; generator=false
- promiseFormsProcessed @742-762; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @745-761; ArrowFunctionExpression; parameters=1; async=false; generator=false
- formProcessed @748-759; FunctionExpression; parameters=0; async=false; generator=false
- loadFormIntoWindow @764-798; FunctionDeclaration; parameters=5; async=true; generator=false
- (anonymous) @768-768; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @782-793; FunctionExpression; parameters=2; async=false; generator=false
- getTelemetryEvents @800-807; FunctionDeclaration; parameters=1; async=true; generator=false
- loadRecipes @809-812; FunctionDeclaration; parameters=1; async=false; generator=false
- resetRecipes @814-817; FunctionDeclaration; parameters=0; async=false; generator=false
- promiseStorageChanged @819-827; FunctionDeclaration; parameters=1; async=true; generator=false
- promisePromptShown @829-832; FunctionDeclaration; parameters=1; async=true; generator=false
- runInParent @842-848; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @844-846; ArrowFunctionExpression; parameters=0; async=false; generator=false
- manageLoginsInParent @853-898; FunctionDeclaration; parameters=0; async=false; generator=false
- addLoginsInParentInner @854-897; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @856-858; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @860-881; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @863-879; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @883-896; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @890-890; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addLoginsInParent @906-910; FunctionDeclaration; parameters=1; async=true; generator=false
- setStoredLoginsAsync @919-924; FunctionDeclaration; parameters=1; async=true; generator=false
- setStoredLoginsDuringTest @934-943; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @939-942; ArrowFunctionExpression; parameters=0; async=true; generator=false
- setStoredLoginsDuringTask @952-961; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @957-960; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getLogins @966-969; FunctionDeclaration; parameters=0; async=false; generator=false
- setFormAndWaitForFieldFilled @986-997; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @991-996; ArrowFunctionExpression; parameters=0; async=false; generator=false
- runChecksAfterCommonInit @1004-1015; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @1023-1068; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cleanupParent @1028-1067; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1038-1039; ArrowFunctionExpression; parameters=1; async=false; generator=false
- loginToVanillaObject @1074-1085; FunctionDeclaration; parameters=1; async=false; generator=false
- get @1095-1115; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1096-1114; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1098-1107; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setContentForTask @1128-1141; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1132-1132; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setPreferencesForTask @1149-1154; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @1153-1153; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1160-1166; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1168-1170; ArrowFunctionExpression; parameters=0; async=false; generator=false
- formAutofillResult @1180-1199; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @1186-1198; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1189-1195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/LoginManagerParent.sys.mjs @1030; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/mochitest/pwmgr_common_parent.js

Blob: `1e6e75b8915f98fd9e591bf39ea3f2f05f1cf2f8`. Role: test-path,source. Parse: module.

- (anonymous) @23-25; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @31-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- commonInit @39-80; FunctionDeclaration; parameters=1; async=true; generator=false
- dumpLogins @82-88; FunctionDeclaration; parameters=0; async=true; generator=false
- dumpLogin @90-107; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @109-126; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @110-125; ArrowFunctionExpression; parameters=1; async=false; generator=false
- storageChanged @111-122; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @128-139; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @129-138; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promptShown @130-134; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @141-143; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @149-151; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @154-158; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @160-163; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @165-195; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @181-192; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @197-218; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @199-205; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @215-215; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @220-223; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @225-235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @227-229; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @231-233; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @237-245; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @247-249; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @8; ChromeUtils-import-literal
- Module resource://gre/modules/LoginHelper.sys.mjs @11; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerParent.sys.mjs @14; ChromeUtils-import-literal
- Module resource://testing-common/LoginTestUtils.sys.mjs @17; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/mochitest/slow_image.sjs

Blob: `b955e43f5d193b6c36af18f55b0bb332f731a7e8`. Role: test-path,data-or-other. Parse: module.

- handleRequest @11-25; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @18-21; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/head.js

Blob: `8c2dc53f66c6ba2a4650821f2acae1d4d3812937`. Role: test-path,source. Parse: module.

- run_test @54-57; FunctionDeclaration; parameters=0; async=false; generator=false
- getTempFile @65-67; FunctionDeclaration; parameters=1; async=false; generator=false
- initNewParent @70-72; FunctionExpression; parameters=0; async=false; generator=false
- test_common_initialize @77-95; FunctionExpression; parameters=0; async=true; generator=false
- test_common_prefs @97-99; FunctionExpression; parameters=0; async=true; generator=false
- formLikeEqual @105-134; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @9; ChromeUtils-import-literal
- Module resource://gre/modules/XPCOMUtils.sys.mjs @12; ChromeUtils-import-literal
- Module resource://gre/modules/LoginRecipes.sys.mjs @15; ChromeUtils-import-literal
- Module resource://gre/modules/LoginHelper.sys.mjs @18; ChromeUtils-import-literal
- Module resource://testing-common/FileTestUtils.sys.mjs @21; ChromeUtils-import-literal
- Module resource://testing-common/LoginTestUtils.sys.mjs @24; ChromeUtils-import-literal
- Module resource://testing-common/MockDocument.sys.mjs @27; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_BreachAlertStore.js

Blob: `01bf909bd602fd63e5f2ec663e01ba5da39db00a`. Role: test-path,source. Parse: module.

- (anonymous) @12-16; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_set_and_get @18-32; FunctionExpression; parameters=0; async=true; generator=false
- test_get_unknown_id_returns_empty @34-37; FunctionExpression; parameters=0; async=true; generator=false
- test_clear_specific @39-53; FunctionExpression; parameters=0; async=true; generator=false
- test_clear_all @55-68; FunctionExpression; parameters=0; async=true; generator=false
- test_singleton @70-73; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/BreachAlertStore.sys.mjs @6; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_BreachAlertsData.js

Blob: `1adede268e1e71d33cc0d62e2599c2a94e764864`. Role: test-path,source. Parse: module.

- (anonymous) @29-36; FunctionExpression; parameters=0; async=true; generator=false
- test_getBreachData @38-51; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @48-48; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_getBreachForSite @53-74; FunctionExpression; parameters=0; async=true; generator=false
- test_getAllBreaches @76-90; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://services-settings/remote-settings.sys.mjs @7; ChromeUtils-import-literal
- Module moz-src:///toolkit/components/passwordmgr/BreachAlertsData.sys.mjs @10; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_CSVParser.js

Blob: `d680d8daf251c71211b30e460b1ce2bd263cf349`. Role: test-path,source. Parse: module.

- parseCSVStringAndValidateResult @225-248; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @229-229; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_csv_parsing_results @250-254; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @251-253; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/CSV.sys.mjs @6; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_doAutocompleteSearch.js

Blob: `2e182a70642140c251b2ca4fd56abba1fe7c96a3`. Role: test-path,source. Parse: module.

- (anonymous) @25-45; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @34-44; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_generated_noLogins @47-119; FunctionExpression; parameters=0; async=true; generator=false
- test_generated_emptyUsernameSavedLogin @121-148; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerParent.sys.mjs @10; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_getGeneratedPassword.js

Blob: `1493bbd32ed2b312868108cb7e81c4a455753081`. Role: test-path,source. Parse: module.

- simulateNavigationInTheFrame @14-30; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @19-29; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_getGeneratedPassword @32-183; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @68-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_getGeneratedPassword_containerTab_cacheCleared_on_username_added @194-254; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @212-220; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerParent.sys.mjs @10; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_onPasswordEditedOrGenerated.js

Blob: `438616b3d13397a63f695d76c3ef43e8f2fa3a6f`. Role: test-path,source. Parse: module.

- stubPrompter @27-62; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @30-35; ArrowFunctionExpression; parameters=0; async=false; generator=false
- resetPrompterHistory @47-51; FunctionDeclaration; parameters=0; async=false; generator=false
- restorePrompter @52-54; FunctionDeclaration; parameters=0; async=false; generator=false
- stubGeneratedPasswordForBrowsingContextId @64-134; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @77-103; ArrowFunctionExpression; parameters=0; async=false; generator=false
- embedderElement @86-98; FunctionExpression; parameters=0; async=false; generator=false
- top @99-101; FunctionExpression; parameters=0; async=false; generator=false
- checkEditTelemetryRecorded @136-162; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @150-153; ArrowFunctionExpression; parameters=1; async=false; generator=false
- startTestConditions @164-182; FunctionDeclaration; parameters=1; async=true; generator=false
- assertLoginProperties @187-197; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @199-207; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword @209-338; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @218-218; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @267-267; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @303-303; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_onPasswordEditedOrGenerated_editToEmpty_generatedPassword @341-426; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @350-350; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_addUsernameBeforeAutoSaveEdit @429-598; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @443-449; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @453-453; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_editUsernameOfFilledSavedLogin @600-730; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @613-619; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword_withDisabledLogin @733-768; FunctionExpression; parameters=0; async=true; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword_withSavedEmptyUsername @772-855; FunctionExpression; parameters=0; async=true; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword_withSavedEmptyUsernameAndUsernameValue @859-972; FunctionExpression; parameters=0; async=true; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword_withEmptyUsernameDifferentFormActionOrigin @976-1035; FunctionExpression; parameters=0; async=true; generator=false
- test_onPasswordEditedOrGenerated_generatedPassword_withSavedUsername @1039-1096; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/Sinon.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerParent.sys.mjs @10; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerPrompter.sys.mjs @13; ChromeUtils-import-literal
- Module resource://testing-common/TestUtils.sys.mjs @17; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginManagerParent_searchAndDedupeLogins.js

Blob: `25ec1cf735341fc5093407b2fa262a0943dec14a`. Role: test-path,source. Parse: module.

- setup @53-56; FunctionExpression; parameters=0; async=false; generator=false
- test_searchAndDedupeLogins_acceptDifferentSubdomains @58-183; FunctionExpression; parameters=0; async=true; generator=false
- test_searchAndDedupeLogins_scheme_order_independent_of_insertion_order @190-212; FunctionExpression; parameters=0; async=true; generator=false
- test_reject_duplicates @215-237; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManagerParent.sys.mjs @7; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginManagerPrompter_getUsernameSuggestions.js

Blob: `e31e39f1594b1290cabb9751bcbe97c2985fb03c`. Role: test-path,source. Parse: module.

- _setPrefs @106-111; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @108-110; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _saveLogins @113-134; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @114-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _compare @136-159; FunctionDeclaration; parameters=2; async=false; generator=false
- _test @161-184; FunctionDeclaration; parameters=1; async=true; generator=false
- test_LoginManagerPrompter_getUsernameSuggestions @186-191; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManagerPrompter.sys.mjs @1; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginStorageMigrator.js

Blob: `c24c13bfb40382b6e907fe9f74acf2cb2b2af61c`. Role: test-path,source. Parse: module.

- restoreTarget @43-45; FunctionDeclaration; parameters=0; async=false; generator=false
- resetState @52-63; FunctionDeclaration; parameters=0; async=false; generator=false
- makeJsonStorage @65-108; FunctionDeclaration; parameters=1; async=false; generator=false
- decryptedPotentiallyVulnerablePasswords @75-77; FunctionExpression; parameters=0; async=false; generator=false
- getAllLogins @78-81; FunctionExpression; parameters=1; async=true; generator=false
- loginIsDeletedAsync @84-86; FunctionExpression; parameters=1; async=true; generator=false
- searchLoginsAsync @87-94; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @88-93; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addLoginsAsync @97-103; FunctionExpression; parameters=2; async=true; generator=false
- modifyLoginAsync @104-106; FunctionExpression; parameters=2; async=true; generator=false
- makeRustStorage @113-167; FunctionDeclaration; parameters=1; async=false; generator=false
- countLoginsAsync @124-126; FunctionExpression; parameters=0; async=true; generator=false
- getAllLogins @127-130; FunctionExpression; parameters=1; async=true; generator=false
- removeAllLoginsAsync @135-142; FunctionExpression; parameters=0; async=true; generator=false
- clearAllPotentiallyVulnerablePasswords @143-145; FunctionExpression; parameters=0; async=true; generator=false
- addLoginsWithResultsAsync @146-158; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @151-151; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @152-156; ArrowFunctionExpression; parameters=2; async=false; generator=false
- addPotentiallyVulnerablePasswords @159-165; FunctionExpression; parameters=1; async=true; generator=false
- mockPrimaryPasswordPrompt @171-189; FunctionDeclaration; parameters=1; async=false; generator=false
- promptPassword @173-178; FunctionExpression; parameters=3; async=false; generator=false
- getNewPrompter @182-182; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @191-194; FunctionExpression; parameters=0; async=false; generator=false
- test_jsonPrimary_returns_json_without_migrating @200-211; FunctionExpression; parameters=0; async=true; generator=false
- test_rustPrimary_returns_rust_without_migrating @213-225; FunctionExpression; parameters=0; async=true; generator=false
- test_revertPending_deactivates_rust @227-243; FunctionExpression; parameters=0; async=true; generator=false
- loginWithMeta @247-261; FunctionDeclaration; parameters=1; async=false; generator=false
- test_revert_restores_added_and_changed_logins @263-328; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @288-289; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @293-293; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_restore_keeps_the_newer_json_password @330-365; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @354-355; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_matches_a_recreated_login_by_name @367-407; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @393-394; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_leaves_a_deleted_login_deleted @409-430; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @420-421; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_counts_the_logins_it_would_delete @434-466; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @448-449; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_is_skipped_for_an_empty_rust_store @468-487; FunctionExpression; parameters=0; async=true; generator=false
- test_restore_keeps_the_rust_store_on_a_login_error @489-521; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @498-498; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_runs_while_sync_is_configured @526-543; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @536-537; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restored_logins_are_marked_for_upload @547-567; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @557-557; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_stops_once_the_attempts_are_spent @569-586; FunctionExpression; parameters=0; async=true; generator=false
- test_spent_attempts_do_not_block_a_raised_target @590-611; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @603-603; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_can_be_turned_off_by_pref @613-624; FunctionExpression; parameters=0; async=true; generator=false
- test_restore_refuses_an_implausibly_large_store @626-656; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @638-638; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_waits_for_the_primary_password @658-705; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @668-668; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @683-683; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @689-691; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_restore_runs_only_once @707-728; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @715-716; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_raising_the_target_runs_the_restore_again @733-766; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @742-742; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @751-752; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @762-762; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_activating_rust_clears_the_restore_state @768-790; FunctionExpression; parameters=0; async=true; generator=false
- test_exceedMigrationBudget_falls_back_to_json @792-810; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_completes_and_reports_status @816-851; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_sorts_by_timePasswordChanged_desc @853-876; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_quarantines_duplicates @882-914; FunctionExpression; parameters=0; async=true; generator=false
- addResults @894-897; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @896-896; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @897-897; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_migration_partial_failure_records_login_error @916-945; FunctionExpression; parameters=0; async=true; generator=false
- addResults @923-926; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @926-926; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_migration_fatal_aborts_and_increments_attempts @951-982; FunctionExpression; parameters=0; async=true; generator=false
- test_migration_retries_then_completes @984-999; FunctionExpression; parameters=0; async=true; generator=false
- test_primaryPassword_prompt_accepted_migrates @1005-1035; FunctionExpression; parameters=0; async=true; generator=false
- test_primaryPassword_prompt_canceled_defers @1037-1077; FunctionExpression; parameters=0; async=true; generator=false
- test_primaryPassword_unlocked_migrates @1079-1104; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginStorageMigrator.sys.mjs @16; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @19; ChromeUtils-import-literal
- Module resource://testing-common/MockRegistrar.sys.mjs @22; ChromeUtils-import-literal
- Module resource://testing-common/TestUtils.sys.mjs @25; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_LoginStorageMigrator_nimbus.js

Blob: `582a206af7f179a4306e0dbdae57798ec8658157`. Role: test-path,source. Parse: module.

- (anonymous) @28-38; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @32-37; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_enrollment_sets_and_restores_pref @40-69; FunctionExpression; parameters=0; async=true; generator=false
- test_exceeded_budget_unenrolls_and_keeps_disabled @71-98; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://nimbus/ExperimentAPI.sys.mjs @6; ChromeUtils-import-literal
- Module resource://testing-common/NimbusTestUtils.sys.mjs @9; ChromeUtils-import-literal
- Module resource://gre/modules/LoginStorageMigrator.sys.mjs @12; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_OSCrypto_win.js

Blob: `9545f5ea02e31550adafa368847700f61da942f7`. Role: test-path,source. Parse: module.

- test_getIELoginHash @17-47; FunctionExpression; parameters=0; async=false; generator=false
- test_decryptData_encryptData @49-116; FunctionExpression; parameters=0; async=false; generator=false
- encryptDecrypt @50-57; FunctionDeclaration; parameters=2; async=false; generator=false
- test_decryptDataOutput @118-138; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-137; ArrowFunctionExpression; parameters=2; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_PasswordGenerator.js

Blob: `88e014c1bc2e64109b1350f61846d63517a5f907`. Role: test-path,source. Parse: module.

- test_shuffleString @7-11; FunctionExpression; parameters=0; async=true; generator=false
- test_randomUInt8Index @13-23; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_generatePassword_classes @25-53; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_length @55-74; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_defaultLength @76-84; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_immutableDefaultRequiredClasses @87-121; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/shared/PasswordGenerator.sys.mjs @3; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_PasswordRulesManager_generatePassword.js

Blob: `19e39bc05aef7d689dcbaada82745801491c33b1`. Role: test-path,source. Parse: module.

- getRulesForRecord @29-38; FunctionDeclaration; parameters=2; async=false; generator=false
- test_verify_password_rules @40-114; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_many_rules @123-153; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_all_characters_allowed @155-189; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_required_special_character @191-223; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_with_arbitrary_required_characters @226-287; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_subdomain_rule @291-373; FunctionExpression; parameters=0; async=true; generator=false
- test_generatePassword_idn_rule @377-400; FunctionExpression; parameters=0; async=true; generator=false
- test_improved_password_rules_telemetry @402-441; FunctionExpression; parameters=0; async=true; generator=false
- checkCharacters @443-453; FunctionDeclaration; parameters=2; async=false; generator=false
- checkConsecutiveCharacters @455-478; FunctionDeclaration; parameters=2; async=false; generator=false
- findMaximumRepeating @456-472; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyPassword @480-552; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://gre/modules/shared/PasswordGenerator.sys.mjs @6; ChromeUtils-import-literal
- Module resource://gre/modules/PasswordRulesManager.sys.mjs @9; ChromeUtils-import-literal
- Module resource://gre/modules/shared/PasswordRulesParser.sys.mjs @12; ChromeUtils-import-literal
- Module resource://services-settings/remote-settings.sys.mjs @15; ChromeUtils-import-literal
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @18; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_context_menu.js

Blob: `53753baa02aeceeb7e7b89eb2bd8fbae5d9ba670`. Role: test-path,source. Parse: module.

- (anonymous) @56-60; FunctionExpression; parameters=0; async=false; generator=false
- test_initialize @65-67; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginBothHTTPAndHTTPSDeduped @69-79; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginOnlyHTTPS_noUsername @81-95; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginOnlyHTTP @97-107; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginDedupeSchemeUpgrade @111-124; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginSchemeDowngrade @126-140; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginNotShadowedSchemeUpgrade @142-160; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginShadowedSchemeDowngrade @162-176; FunctionExpression; parameters=0; async=true; generator=false
- test_sameDomainDifferentPort_onDefault @180-193; FunctionExpression; parameters=0; async=true; generator=false
- test_sameDomainDifferentPort_onNonDefault @195-209; FunctionExpression; parameters=0; async=true; generator=false
- test_sameOriginOnlyHTTPAuth @213-223; FunctionExpression; parameters=0; async=true; generator=false
- formLogin @227-236; FunctionDeclaration; parameters=1; async=false; generator=false
- authLogin @238-247; FunctionDeclaration; parameters=1; async=false; generator=false
- runTestcase @252-283; FunctionDeclaration; parameters=1; async=true; generator=false
- createLoginsFragment @288-314; FunctionDeclaration; parameters=2; async=true; generator=false
- checkLoginItems @316-346; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://gre/modules/LoginManagerContextMenu.sys.mjs @7; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_crypto_SDR_primary_password.js

Blob: `e3bffb198be038eb9fa93d46bbb6d0e4311b08b2`. Role: test-path,source. Parse: module.

- promptPassword @27-34; FunctionExpression; parameters=3; async=false; generator=false
- getNewPrompter @41-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- promptEvents @47-51; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- lockToken @59-64; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @66-88; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @83-87; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_encrypt_success @90-101; FunctionExpression; parameters=0; async=true; generator=false
- test_decrypt_cancel @103-118; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @107-107; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_decrypt_many_success @120-135; FunctionExpression; parameters=0; async=true; generator=false
- test_no_prompt_while_unlocked @137-146; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/MockRegistrar.sys.mjs @11; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_dedupeLogins.js

Blob: `6015ead2410dc1cf1fce622ca1f929442da396d7`. Role: test-path,source. Parse: module.

- test_dedupeLogins @81-158; FunctionExpression; parameters=0; async=false; generator=false
- test_dedupeLogins_resolveBy @160-372; FunctionExpression; parameters=0; async=true; generator=false
- test_dedupeLogins_preferredOriginMissing @374-411; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @404-406; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_disabled_hosts.js

Blob: `affc512b05fa8d4d6de1ab6a969cb962e3d0bd39`. Role: test-path,source. Parse: module.

- test_setLoginSavingEnabled_getAllDisabledHosts @15-51; FunctionExpression; parameters=0; async=false; generator=false
- test_setLoginSavingEnabled_getLoginSavingEnabled @56-78; FunctionExpression; parameters=0; async=false; generator=false
- test_setLoginSavingEnabled_invalid_characters @83-95; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @86-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_rememberSignons @100-155; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @114-115; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_storage_setLoginSavingEnabled_nonascii_IDN_is_supported @161-188; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_setLoginSavingEnabled_nonascii_IDN_not_supported @195-222; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_displayOrigin.js

Blob: `a42f066b3e0ba2641dccc1b624cd85c66f3dd0cd`. Role: test-path,source. Parse: module.

- test_displayOrigin @10-43; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_doLoginsMatch.js

Blob: `fb38f08cf7c6967380244d278e050419359108c6`. Role: test-path,source. Parse: module.

- test_formActionOrigin_ignoreSchemes @5-57; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_findRelatedRealms.js

Blob: `b79a0ab4c4672e7ab8e158dcb27000a3a7e16bc4`. Role: test-path,source. Parse: module.

- test_related_domain_matching @15-49; FunctionExpression; parameters=0; async=true; generator=false
- test_newly_synced_collection @51-104; FunctionExpression; parameters=0; async=true; generator=false
- test_no_related_domains @106-120; FunctionExpression; parameters=0; async=true; generator=false
- test_unrelated_subdomains @122-156; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginRelatedRealms.sys.mjs @6; ChromeUtils-import-literal
- Module resource://services-settings/remote-settings.sys.mjs @9; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_getFormFields.js

Blob: `5868c03f8ecfb444c643947bfdde3e2535a8bd81`. Role: test-path,source. Parse: module.

- beforeGetFunction @61-69; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @452-462; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _setPrefs @464-469; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @466-468; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @476-549; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @478-548; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @522-527; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _generateDocStateFromTestCase @552-572; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @562-569; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/shared/LoginFormFactory.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerChild.sys.mjs @11; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_getPasswordFields.js

Blob: `3bad4ed660443f04ba6c160dd72c8fe7ea68aca6`. Role: test-path,source. Parse: module.

- beforeGetFunction @156-158; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @170-258; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @172-257; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @286-307; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @288-306; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/shared/LoginFormFactory.sys.mjs @8; ChromeUtils-import-literal
- Module resource://gre/modules/LoginManagerChild.sys.mjs @11; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_getPasswordOrigin.js

Blob: `95a7313c1d8f0f1f8ff3a870081ba28f10e7b919`. Role: test-path,source. Parse: module.


### toolkit/components/passwordmgr/test/unit/test_getUserNameAndPasswordFields.js

Blob: `8b3136d7bcbc371009c2efd934aef97978987eaf`. Role: test-path,source. Parse: module.

- _setPrefs @119-124; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @121-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @131-186; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @133-185; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManagerChild.sys.mjs @7; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_getUsernameFieldFromUsernameOnlyForm.js

Blob: `8ca7c772a35a497fd9343777b45e8fd3ed815489`. Role: test-path,source. Parse: module.

- _setPrefs @145-150; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @147-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @159-190; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @161-189; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManagerChild.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/FormLikeFactory.sys.mjs @11; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_isInferredLoginForm.js

Blob: `4ee3f00147218f0e8e6a36aa896526ebd4bc0041`. Role: test-path,source. Parse: module.

- update @51-53; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @58-60; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @65-67; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @72-74; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @82-104; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-103; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_isInferredUsernameField.js

Blob: `612864326cc47be08f0bb8c070d26b5cd6253114`. Role: test-path,source. Parse: module.

- update @89-91; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @105-107; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @134-136; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @141-143; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @148-150; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @155-157; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @162-164; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @169-171; ArrowFunctionExpression; parameters=2; async=false; generator=false
- update @176-178; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @192-228; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @193-227; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_isOriginMatching.js

Blob: `02547609ecf253980879a42f854603bb5dfe23a2`. Role: test-path,source. Parse: module.

- test_isOriginMatching @7-177; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_isProbablyANewPasswordField.js

Blob: `0206e68b05f79d95d52d5135af114474d578d4d6`. Role: test-path,source. Parse: module.

- makeDocumentVisibleToFathom @15-28; FunctionDeclaration; parameters=1; async=false; generator=false
- getComputedStyle @17-22; FunctionExpression; parameters=0; async=false; generator=false
- labelledByDocument @30-42; FunctionDeclaration; parameters=0; async=false; generator=false
- test_returns_false_when_pref_disabled @130-159; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @164-191; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @165-190; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManager.shared.sys.mjs @7; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_isUsernameFieldType.js

Blob: `57238964a7a774849b62863f416cc81f8c604091`. Role: test-path,source. Parse: module.

- (anonymous) @146-160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @147-159; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_legacy_empty_formActionOrigin.js

Blob: `0d0fde09e4a49f1ee5c96e8e76a2cfd04a1e00ad`. Role: test-path,source. Parse: module.

- test_addLogin_wildcard @51-72; FunctionExpression; parameters=0; async=true; generator=false
- test_search_all_wildcard @79-106; FunctionExpression; parameters=0; async=true; generator=false
- test_searchLogins_wildcard @112-122; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_legacy_validation.js

Blob: `7fb6c9807d730489ff3bcb5adac7c448343e2866`. Role: test-path,source. Parse: module.

- test_addLogin_invalid_characters_legacy @19-78; FunctionExpression; parameters=0; async=true; generator=false
- test_setLoginSavingEnabled_invalid_characters_legacy @83-94; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_login_autocomplete_result.js

Blob: `668cff02af1ee8a9d3a94381988f1c0bfc47dbe8`. Role: test-path,source. Parse: module.

- (anonymous) @85-89; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_all_patterns @91-746; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @677-745; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @703-732; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @736-736; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @741-741; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_external_autocomplete_items @748-812; FunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/LoginAutoComplete.sys.mjs @1; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_loginsBackup.js

Blob: `afe8ee8112d763504425875c99b9e693bd6fc5fc`. Role: test-path,source. Parse: module.

- test_logins_store_missing_or_corrupt_with_backup @64-218; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @189-191; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @215-217; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/TestUtils.sys.mjs @13; ChromeUtils-import-literal
- Module resource://testing-common/TelemetryTestUtils.sys.mjs @16; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_logins_change.js

Blob: `fd6baf6149bd6d09df390d1a7e5b887d049af714`. Role: test-path,source. Parse: module.

- checkLoginInvalid @26-62; FunctionDeclaration; parameters=2; async=true; generator=false
- compareAttributes @79-85; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @84-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_addLogin_removeLogin @92-111; FunctionExpression; parameters=0; async=true; generator=false
- add_login_works_with_empty_array @113-116; FunctionExpression; parameters=0; async=true; generator=false
- duplicated_logins_are_not_added @118-126; FunctionExpression; parameters=0; async=true; generator=false
- logins_containing_nul_in_username_are_not_added @128-133; FunctionExpression; parameters=0; async=true; generator=false
- logins_containing_nul_in_password_are_not_added @135-140; FunctionExpression; parameters=0; async=true; generator=false
- return_value_includes_plaintext_username_and_password @143-149; FunctionExpression; parameters=0; async=true; generator=false
- event_data_includes_plaintext_username_and_password @152-178; FunctionExpression; parameters=0; async=true; generator=false
- observe @159-172; FunctionExpression; parameters=3; async=false; generator=false
- test_invalid_httpRealm_formActionOrigin @189-220; FunctionExpression; parameters=0; async=true; generator=false
- test_missing_properties @225-250; FunctionExpression; parameters=0; async=true; generator=false
- test_invalid_characters @255-269; FunctionExpression; parameters=0; async=true; generator=false
- test_removeLogin_nonexisting @274-283; FunctionExpression; parameters=0; async=true; generator=false
- test_removeLogin_requiresMatchingCredentials @289-312; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_requiresMatchingCredentials @318-333; FunctionExpression; parameters=0; async=true; generator=false
- test_removeLogin_normalizedOrigin @340-349; FunctionExpression; parameters=0; async=true; generator=false
- test_removeAllUserFacingLogins @354-362; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_nsILoginInfo @367-421; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @413-413; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_modifyLogin_nsIProperyBag @426-507; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @499-499; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_deduplicate_logins @512-555; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @547-550; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @549-549; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_deduplicate_keeps_most_recent @560-597; FunctionExpression; parameters=0; async=false; generator=false
- test_addLogin_badDates @602-665; FunctionExpression; parameters=0; async=true; generator=false
- test_addLogins_badDates @670-707; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_logins_decrypt_failure.js

Blob: `863a73dd7f8c418bdf7b3b9094aef2dbed13a9ea`. Role: test-path,source. Parse: module.

- resetPrimaryPassword @24-29; FunctionDeclaration; parameters=0; async=true; generator=false
- test_logins_decrypt_failure @36-103; FunctionExpression; parameters=0; async=true; generator=false
- test_add_logins_with_decrypt_failure @108-166; FunctionExpression; parameters=0; async=true; generator=false
- test_sync_metadata_with_decrypt_failure @169-187; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_logins_metainfo.js

Blob: `0024f13dc370c2eb32d977cc0bc75a75d0aebac5`. Role: test-path,source. Parse: module.

- retrieveOriginMatching @24-28; FunctionDeclaration; parameters=1; async=true; generator=false
- assertMetaInfoEqual @34-50; FunctionDeclaration; parameters=2; async=false; generator=false
- test_initialize @72-87; FunctionExpression; parameters=0; async=false; generator=false
- test_addLogin_metainfo @93-128; FunctionExpression; parameters=0; async=true; generator=false
- test_addLogin_metainfo_duplicate_json @134-147; FunctionExpression; parameters=0; async=true; generator=false
- test_addLogin_metainfo_duplicate_rust @153-164; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_nsILoginInfo_metainfo_ignored @170-181; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_nsIProperyBag_metainfo @187-218; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_nsIProperyBag_metainfo_json @224-280; FunctionExpression; parameters=0; async=true; generator=false
- test_modifyLogin_nsIProperyBag_metainfo_duplicate @286-297; FunctionExpression; parameters=0; async=true; generator=false
- test_searchLogins_metainfo @302-327; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_metainfo @333-349; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_logins_search.js

Blob: `bd146125ce7e034d4c4e25a4e4f8e5e96ed0a9ae`. Role: test-path,source. Parse: module.

- buildExpectedLogins @20-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @21-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkSearchLogins @38-46; FunctionDeclaration; parameters=2; async=true; generator=false
- checkAllSearches @61-85; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @92-94; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_search_all_basic @99-169; FunctionExpression; parameters=0; async=true; generator=false
- test_searchLogins @174-189; FunctionExpression; parameters=0; async=true; generator=false
- test_searchLogins_invalid @194-199; FunctionExpression; parameters=0; async=true; generator=false
- test_search_all_full_case_sensitive @205-219; FunctionExpression; parameters=0; async=false; generator=false
- test_search_all_empty @225-234; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_maybeImportLogin.js

Blob: `e21343d47e37b0f5fdb5ed49e70a6e31606e3c2c`. Role: test-path,source. Parse: module.

- maybeImportLogins @13-16; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_invalid_logins @18-55; FunctionExpression; parameters=0; async=true; generator=false
- test_new_logins @57-112; FunctionExpression; parameters=0; async=true; generator=false
- test_duplicate_logins @114-154; FunctionExpression; parameters=0; async=true; generator=false
- test_different_passwords @156-233; FunctionExpression; parameters=0; async=true; generator=false
- test_different_usernames_without_guid @235-276; FunctionExpression; parameters=0; async=true; generator=false
- test_different_usernames_with_guid @278-326; FunctionExpression; parameters=0; async=true; generator=false
- test_different_targets @328-398; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_module_LoginCSVImport.js

Blob: `7219bfebebd6236111e6d3227517495a29a46139`. Role: test-path,source. Parse: module.

- setupCsv @41-50; FunctionDeclaration; parameters=2; async=true; generator=false
- checkMetaInfo @52-62; FunctionDeclaration; parameters=3; async=false; generator=false
- checkLoginNewlyCreated @64-70; FunctionDeclaration; parameters=1; async=false; generator=false
- assertImportCategoryTelemetry @78-84; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @86-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_import_tsv @93-125; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @123-123; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_tsv_with_missing_columns @130-149; FunctionExpression; parameters=0; async=true; generator=false
- test_import_lacking_username_column @155-171; FunctionExpression; parameters=0; async=true; generator=false
- test_import_with_duplicate_fields @176-195; FunctionExpression; parameters=0; async=true; generator=false
- test_import_with_duplicate_columns @200-216; FunctionExpression; parameters=0; async=true; generator=false
- test_import_minimal_with_mixed_naming @223-249; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @244-247; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_firefox_various_latest @255-270; FunctionExpression; parameters=0; async=true; generator=false
- test_import_from_firefox_auth @275-303; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @301-301; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_firefox_auth_with_quotes @308-335; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @333-333; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_firefox_auth_some_quoted_fields @340-367; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @365-365; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_firefox_form_empty_formActionOrigin @372-399; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @397-397; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_firefox_form_with_formActionOrigin @404-431; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @429-429; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_bitwarden_csv @437-465; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @460-463; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_chrome_csv @471-498; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @493-496; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_login_without_username @503-530; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @525-528; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_from_keepassxc_csv @536-563; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @558-561; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_summary_contains_added_login @568-577; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_modified_login_without_guid @582-623; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @621-621; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_summary_modified_login_with_guid @628-667; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @665-665; ArrowFunctionExpression; parameters=2; async=false; generator=false
- test_import_summary_contains_unchanged_login @672-689; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_contains_missing_fields_errors @694-723; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_with_bad_format @728-741; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_with_non_csv_file @746-761; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_with_url_user_multiple_values @766-787; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_with_duplicated_guid_values @792-808; FunctionExpression; parameters=0; async=true; generator=false
- test_import_summary_with_different_time_changed @813-842; FunctionExpression; parameters=0; async=true; generator=false
- test_import_duplicate_logins_as_one @847-872; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginCSVImport.sys.mjs @11; ChromeUtils-import-literal
- Module resource://gre/modules/LoginExport.sys.mjs @14; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_module_LoginExport.js

Blob: `91f7a99563aee54b232c6c7dba5223fa9664631b`. Role: test-path,source. Parse: module.

- exportAsCSVInTmpFile @22-29; FunctionDeclaration; parameters=0; async=true; generator=false
- exportFormLogin @45-51; FunctionDeclaration; parameters=1; async=false; generator=false
- exportAuthLogin @53-59; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @61-67; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-66; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_buildCSVRow @69-86; FunctionExpression; parameters=0; async=true; generator=false
- test_no_new_properties_to_export @88-120; FunctionExpression; parameters=0; async=true; generator=false
- test_export_one_form_login @122-138; FunctionExpression; parameters=0; async=true; generator=false
- test_export_one_auth_login @140-156; FunctionExpression; parameters=0; async=true; generator=false
- test_export_escapes_values @158-171; FunctionExpression; parameters=0; async=true; generator=false
- test_export_multiple_rows @173-223; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginExport.sys.mjs @11; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @14; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_module_LoginManager.js

Blob: `2d43e308084035739b106a858711bb362eadbf47`. Role: test-path,source. Parse: module.

- test_ensureCurrentSyncID @21-43; FunctionExpression; parameters=0; async=true; generator=false
- test_sync_getters_before_storage_init @50-74; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/LoginManager.sys.mjs @17; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_module_LoginStore.js

Blob: `3a2ed039a9834640dd0c75377e2f50b62c0b9cf9`. Role: test-path,source. Parse: module.

- test_save_reload @25-64; FunctionExpression; parameters=0; async=true; generator=false
- test_load_empty @69-79; FunctionExpression; parameters=0; async=true; generator=false
- test_save_empty @84-92; FunctionExpression; parameters=0; async=true; generator=false
- test_load_string_predefined @98-142; FunctionExpression; parameters=0; async=true; generator=false
- test_load_string_malformed @147-164; FunctionExpression; parameters=0; async=true; generator=false
- test_load_string_malformed_sync @170-187; FunctionExpression; parameters=0; async=true; generator=false
- test_load_bad_dates @192-340; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_notifications.js

Blob: `ed51aebbf088dced187e37be2fc965aeebe6e220`. Role: test-path,source. Parse: module.

- observe @14-52; FunctionExpression; parameters=3; async=false; generator=false
- test_notifications @55-195; FunctionExpression; parameters=0; async=true; generator=false
- test_notifications_gated_by_isActive @197-248; FunctionExpression; parameters=0; async=true; generator=false
- observer @229-233; ArrowFunctionExpression; parameters=3; async=false; generator=false
- Module resource://gre/modules/LoginManager.sys.mjs @198; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_recipes_add.js

Blob: `253556232e6e6586fd814c3eeb9b49dcae56a118`. Role: test-path,source. Parse: module.

- test_init @10-30; FunctionExpression; parameters=0; async=true; generator=false
- test_get_missing_host @32-40; FunctionExpression; parameters=0; async=true; generator=false
- test_add_get_simple_host @42-68; FunctionExpression; parameters=0; async=true; generator=false
- test_add_get_non_standard_port_host @70-91; FunctionExpression; parameters=0; async=true; generator=false
- test_add_multiple_hosts @93-136; FunctionExpression; parameters=0; async=true; generator=false
- test_add_pathRegex @138-165; FunctionExpression; parameters=0; async=true; generator=false
- test_add_selectors @167-200; FunctionExpression; parameters=0; async=true; generator=false
- test_add_missing_prop @204-211; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @207-207; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_unknown_prop @213-223; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @216-219; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_invalid_hosts @225-235; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @228-231; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_empty_host_array @237-247; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @240-243; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_pathRegex_non_regexp @249-260; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @252-256; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_usernameSelector_non_string @262-273; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @265-269; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_add_passwordSelector_non_string @275-286; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @278-282; ArrowFunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_recipes_content.js

Blob: `673bb508511a4490d3ec780ff09983c1a5ecd98a`. Role: test-path,source. Parse: module.

- test_getFieldOverrides @10-53; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_reencrypt.js

Blob: `3d1c70cd7d20a8c2e9aa006bd681cda519f7ef29`. Role: test-path,source. Parse: module.

- (anonymous) @14-23; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @15-18; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_before_reencrypt @25-30; FunctionExpression; parameters=0; async=true; generator=false
- test_reencrypt_same_mechanism @32-39; FunctionExpression; parameters=0; async=true; generator=false
- test_reencrypt_new_mechanism @41-50; FunctionExpression; parameters=0; async=true; generator=false
- test_reencrypt_mixed_mechanism @52-71; FunctionExpression; parameters=0; async=true; generator=false
- test_reencrypt_race @73-91; FunctionExpression; parameters=0; async=true; generator=false
- test_reencrypt_no_logins_present @93-102; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_remote_recipes.js

Blob: `ae5106c42b3854fa8a19e190debbacad1253b44a`. Role: test-path,source. Parse: module.

- test_init_remote_recipe @17-59; FunctionExpression; parameters=0; async=true; generator=false
- test_add_recipe_sync @61-95; FunctionExpression; parameters=0; async=true; generator=false
- test_remove_recipe_sync @97-124; FunctionExpression; parameters=0; async=true; generator=false
- test_malformed_recipes_in_db @126-164; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://services-settings/remote-settings.sys.mjs @11; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_search_schemeUpgrades.js

Blob: `b2d0b66c9aa9764bf7ef5e77cd97f6d36edb770f`. Role: test-path,source. Parse: module.

- buildExpectedLogins @17-31; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @18-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @19-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkSearch @45-53; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @58-60; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_search_schemeUpgrades_origin @65-94; FunctionExpression; parameters=0; async=true; generator=false
- test_search_schemeUpgrades_formActionOrigin @99-127; FunctionExpression; parameters=0; async=true; generator=false
- test_search_schemeUpgrades_origin_formActionOrigin @129-191; FunctionExpression; parameters=0; async=true; generator=false
- test_http_to_https @196-215; FunctionExpression; parameters=0; async=true; generator=false
- test_search_schemeUpgrades_downgrade @220-239; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_shadowHTTPLogins.js

Blob: `86a9a08ac3959fe9ffff5c0d7b4c7980c875aaed`. Role: test-path,source. Parse: module.

- test_shadowHTTPLogins @30-82; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_storage.js

Blob: `9bd1d2489ad74d87b7ce592b2dee05906221e8fa`. Role: test-path,source. Parse: module.

- reloadAndCheckLoginsGen @19-23; FunctionDeclaration; parameters=1; async=true; generator=false
- test_storage_addLogin_nonascii @30-54; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_addLogin_newlines @59-66; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_addLogin_dot @75-83; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_addLogin_http_realm_parentheses @90-103; FunctionExpression; parameters=0; async=true; generator=false
- test_storage_addLogin_parentheses @112-121; FunctionExpression; parameters=0; async=true; generator=false
- test_listInvalidOrigins @128-136; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/passwordmgr/test/unit/test_storage_rust_shutdown.js

Blob: `8e2829f47f16779505887848fe8c019fb3957b27`. Role: test-path,source. Parse: module.

- makeFakeInstance @34-41; FunctionDeclaration; parameters=1; async=false; generator=false
- test_register_blocker_when_phase_open @43-78; FunctionExpression; parameters=0; async=true; generator=false
- test_finalize_immediately_when_phase_closed @80-100; FunctionExpression; parameters=0; async=true; generator=false
- test_blocker_waits_for_initialization @102-125; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @105-105; ArrowFunctionExpression; parameters=1; async=false; generator=false
- test_blocker_finalizes_after_failed_initialization @127-140; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/storage-rust.sys.mjs @24; ChromeUtils-import-literal
- Module resource://testing-common/Sinon.sys.mjs @27; ChromeUtils-import-literal
- Module resource://testing-common/TestUtils.sys.mjs @30; ChromeUtils-import-literal

### toolkit/components/passwordmgr/test/unit/test_telemetry.js

Blob: `7ec4c9345a72059ee0a5840beecd4f3e07d1164d`. Role: test-path,source. Parse: module.

- daysBeforeMs @22-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @77-94; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_logins_count @99-105; FunctionExpression; parameters=0; async=false; generator=false
- test_settings_statistics @110-125; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @112-114; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/passwordmgr/test/unit/test_vulnerable_passwords.js

Blob: `135f8c7762343439c275cc5ecbc9830e904474c5`. Role: test-path,source. Parse: module.

- (anonymous) @6-8; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_vulnerable_password_methods @10-46; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/components/pdfjs/PdfJsDefaultPrefs.js

Blob: `c131247b002047fdf149b9918f699b77593b959d`. Role: source. Parse: failed.

Failure: Unexpected token #include


### toolkit/components/pdfjs/PdfJsOverridePrefs.js

Blob: `c1e9b3348555a2318c6d4340a504101bafd7824d`. Role: source. Parse: failed.

Failure: Unexpected token #if


### toolkit/components/pdfjs/content/GeckoViewPdfJsChild.sys.mjs

Blob: `5c794626a6f1758695384b8ce8561c9621a07f7d`. Role: source. Parse: module.

- init @19-21; FunctionExpression; parameters=1; async=false; generator=false
- dispatchEvent @23-27; FunctionExpression; parameters=2; async=false; generator=false
- receiveMessage @29-42; FunctionExpression; parameters=1; async=false; generator=false
- Class GeckoViewPdfJsChild @18-43
- Module resource://gre/modules/GeckoViewActorChild.sys.mjs @16; ImportDeclaration

### toolkit/components/pdfjs/content/GeckoViewPdfJsParent.sys.mjs

Blob: `3aacc7f742275eb0acdab843d601753c3b3f3fcd`. Role: source. Parse: module.

- constructor @32-34; FunctionExpression; parameters=1; async=false; generator=false
- cleanup @36-39; FunctionExpression; parameters=0; async=false; generator=false
- onEvent @41-90; FunctionExpression; parameters=3; async=false; generator=false
- getFindType @92-129; FunctionExpression; parameters=1; async=false; generator=false
- updateMatchesCount @131-165; FunctionExpression; parameters=2; async=false; generator=false
- constructor @175-178; FunctionExpression; parameters=2; async=false; generator=false
- cleanup @180-182; FunctionExpression; parameters=0; async=false; generator=false
- onEvent @184-202; FunctionExpression; parameters=3; async=false; generator=false
- save @204-240; FunctionExpression; parameters=1; async=true; generator=false
- constructor @246-248; FunctionExpression; parameters=1; async=false; generator=false
- onEvent @250-265; FunctionExpression; parameters=3; async=false; generator=false
- receiveMessage @275-300; FunctionExpression; parameters=1; async=false; generator=false
- didDestroy @302-329; FunctionExpression; parameters=0; async=false; generator=false
- addEventListener @331-357; FunctionExpression; parameters=1; async=false; generator=false
- updateMatchesCount @359-361; FunctionExpression; parameters=1; async=false; generator=false
- updateControlState @363-365; FunctionExpression; parameters=1; async=false; generator=false
- save @367-369; FunctionExpression; parameters=1; async=false; generator=false
- getExperimentFeature @371-382; FunctionExpression; parameters=0; async=true; generator=false
- recordExposure @384-393; FunctionExpression; parameters=0; async=true; generator=false
- reportTelemetry @395-397; FunctionExpression; parameters=1; async=false; generator=false
- printToPDF @399-406; FunctionExpression; parameters=1; async=false; generator=false
- Class GeckoViewPdfJsParent @268-407
- Class SignatureHandler @243-266
- Class FileSaver @168-241
- Class FindHandler @25-166
- Module resource://gre/modules/GeckoViewActorParent.sys.mjs @16; ImportDeclaration

### toolkit/components/pdfjs/content/PdfEmbedFallbackParent.sys.mjs

Blob: `2088c7f03a0a2c4faf3de482d8b16813fae5a59a`. Role: source. Parse: module.

- getEmbeddingPage @32-42; FunctionDeclaration; parameters=1; async=false; generator=false
- receiveMessage @48-66; FunctionExpression; parameters=1; async=false; generator=false
- Class PdfEmbedFallbackParent @47-67

### toolkit/components/pdfjs/content/PdfEmbedFallbackStreamConverter.sys.mjs

Blob: `c6e3bf519bc1339d9347d99412d13858ad8f3c8b`. Role: source. Parse: module.

- getDOMWindow @26-32; FunctionDeclaration; parameters=2; async=false; generator=false
- openPdf @46-52; FunctionDeclaration; parameters=2; async=false; generator=false
- convert @69-71; FunctionExpression; parameters=0; async=false; generator=false
- asyncConvertData @73-79; FunctionExpression; parameters=4; async=false; generator=false
- getConvertedType @81-101; FunctionExpression; parameters=2; async=false; generator=false
- onStartRequest @103-127; FunctionExpression; parameters=1; async=false; generator=false
- onDataAvailable @129-140; FunctionExpression; parameters=4; async=false; generator=false
- onStopRequest @142-146; FunctionExpression; parameters=0; async=false; generator=false
- serveFallback @163-260; FunctionExpression; parameters=2; async=false; generator=false
- stopDownloadingPdf @174-178; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onStartRequest @184-186; FunctionExpression; parameters=0; async=false; generator=false
- onDataAvailable @187-189; FunctionExpression; parameters=4; async=false; generator=false
- onStopRequest @190-251; FunctionExpression; parameters=2; async=false; generator=false
- stopWhenFallbackIsDone @223-227; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @233-241; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @236-240; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class PdfEmbedFallbackStreamConverter @59-261
- Module resource://gre/modules/pdfjs.sys.mjs @16; ImportDeclaration

### toolkit/components/pdfjs/content/PdfJs.sys.mjs

Blob: `8e864cc686faa1f378d95b31113712b81f75003c`. Role: source. Parse: module.

- getFileExtensions @46-48; FunctionExpression; parameters=0; async=false; generator=false
- extensionExists @52-54; FunctionExpression; parameters=1; async=false; generator=false
- init @65-75; FunctionExpression; parameters=1; async=false; generator=false
- initPrefs @77-91; FunctionExpression; parameters=0; async=false; generator=false
- uninit @93-98; FunctionExpression; parameters=0; async=false; generator=false
- migrate @100-115; FunctionExpression; parameters=0; async=false; generator=false
- _becomeHandler @117-150; FunctionExpression; parameters=0; async=false; generator=false
- _unbecomeHandler @152-169; FunctionExpression; parameters=0; async=false; generator=false
- _isDefault @177-199; FunctionExpression; parameters=1; async=false; generator=false
- checkIsDefault @201-207; FunctionExpression; parameters=1; async=false; generator=false
- cachedIsDefault @209-211; FunctionExpression; parameters=0; async=false; generator=false
- observe @214-216; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @224-224; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @24; ImportDeclaration

### toolkit/components/pdfjs/content/PdfJsAIFeature.sys.mjs

Blob: `5ba2cd51b11884e9ce4253bd8db2d828533c4dea`. Role: source. Parse: module.

- engineId @31-33; FunctionExpression; parameters=0; async=false; generator=false
- id @40-42; FunctionExpression; parameters=0; async=false; generator=false
- hasDistinctEnabledState @50-55; FunctionExpression; parameters=0; async=false; generator=false
- canRunOnDevice @62-65; FunctionExpression; parameters=0; async=false; generator=false
- enable @72-79; FunctionExpression; parameters=0; async=true; generator=false
- block @86-91; FunctionExpression; parameters=0; async=true; generator=false
- makeAvailable @98-105; FunctionExpression; parameters=0; async=true; generator=false
- uninstall @112-118; FunctionExpression; parameters=0; async=true; generator=false
- isEnabled @125-132; FunctionExpression; parameters=0; async=false; generator=false
- isAllowed @140-142; FunctionExpression; parameters=0; async=false; generator=false
- isBlocked @149-154; FunctionExpression; parameters=0; async=false; generator=false
- isManagedByPolicy @162-164; FunctionExpression; parameters=0; async=false; generator=false
- Class PdfJsGuessAltTextFeature @25-165
- Module chrome://global/content/ml/AIFeature.sys.mjs @16; ImportDeclaration
- Module chrome://global/content/ml/EngineProcess.sys.mjs @17; ImportDeclaration

### toolkit/components/pdfjs/content/PdfJsChild.sys.mjs

Blob: `646834dd20eaf19a2f6dc76dc30d38c0a465e49f`. Role: source. Parse: module.

- init @17-21; FunctionExpression; parameters=1; async=false; generator=false
- dispatchEvent @23-29; FunctionExpression; parameters=2; async=false; generator=false
- receiveMessage @31-49; FunctionExpression; parameters=1; async=false; generator=false
- Class PdfJsChild @16-50

### toolkit/components/pdfjs/content/PdfJsContextMenu.sys.mjs

Blob: `47fd7eebbd05675c3c0a313523c255502b51c103`. Role: source. Parse: module.

- constructor @38-44; FunctionExpression; parameters=2; async=false; generator=false
- initItems @46-145; FunctionExpression; parameters=0; async=false; generator=false
- cmd @147-171; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @169-169; ArrowFunctionExpression; parameters=2; async=false; generator=false
- Class PdfJsContextMenu @27-172
- Module resource://gre/modules/XPCOMUtils.sys.mjs @18; ImportDeclaration

### toolkit/components/pdfjs/content/PdfJsFeaturesNotification.sys.mjs

Blob: `d5c0ab8893b8730db02ef40c0e36af0fc5464b65`. Role: source. Parse: module.

- impressionLimit @16-21; FunctionExpression; parameters=0; async=false; generator=false
- isEligible @24-28; FunctionExpression; parameters=0; async=false; generator=false
- recordImpression @31-36; FunctionExpression; parameters=0; async=false; generator=false
- isConsumed @44-48; FunctionExpression; parameters=0; async=false; generator=false
- consume @51-53; FunctionExpression; parameters=0; async=false; generator=false

### toolkit/components/pdfjs/content/PdfJsNetwork.sys.mjs

Blob: `a36f889539c9b88994eddfc2373a556b28da13c8`. Role: source. Parse: module.

- getTypedArray @16-22; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @21-21; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @28-41; FunctionExpression; parameters=2; async=false; generator=false
- NetworkManager_getXhr @35-37; FunctionExpression; parameters=0; async=false; generator=false
- requestRange @43-52; FunctionExpression; parameters=3; async=false; generator=false
- request @54-97; FunctionExpression; parameters=1; async=false; generator=false
- xhr.onerror @82-84; FunctionExpression; parameters=0; async=false; generator=false
- onProgress @99-110; FunctionExpression; parameters=2; async=false; generator=false
- onStateChange @112-180; FunctionExpression; parameters=1; async=false; generator=false
- abortAllRequests @182-186; FunctionExpression; parameters=0; async=false; generator=false
- abortRequest @188-192; FunctionExpression; parameters=1; async=false; generator=false
- Class NetworkManager @27-193

### toolkit/components/pdfjs/content/PdfJsParent.sys.mjs

Blob: `db56c56c9c8bda73fd79c67b69bd95c1cdc60094`. Role: source. Parse: module.

- isBytes @75-75; ArrowFunctionExpression; parameters=1; async=false; generator=false
- validateVerifyPdfSignatureArgs @88-97; FunctionDeclaration; parameters=1; async=false; generator=false
- filterCertsForView @110-123; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @116-120; ArrowFunctionExpression; parameters=1; async=false; generator=false
- validateMLGuessRequest @138-161; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @145-145; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @181-196; FunctionExpression; parameters=0; async=false; generator=false
- didDestroy @198-207; FunctionExpression; parameters=0; async=false; generator=false
- receiveMessage @209-255; FunctionExpression; parameters=1; async=false; generator=false
- _openAboutPdfFeatures @257-268; FunctionExpression; parameters=0; async=false; generator=false
- _claimFeaturesNotification @270-276; FunctionExpression; parameters=0; async=false; generator=false
- _viewPdfCertificate @278-309; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @292-292; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _verifyPdfSignature @311-346; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @330-334; ArrowFunctionExpression; parameters=1; async=false; generator=false
- nsresultName @348-360; FunctionExpression; parameters=1; async=false; generator=false
- flattenCertificate @362-387; FunctionExpression; parameters=1; async=false; generator=false
- browser @393-395; FunctionExpression; parameters=0; async=false; generator=false
- getTextContent @402-411; FunctionExpression; parameters=0; async=false; generator=false
- openDatabase @413-419; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @414-418; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _handleSignature @421-432; FunctionExpression; parameters=1; async=true; generator=false
- getSignatures @434-474; FunctionExpression; parameters=0; async=true; generator=false
- observe @438-453; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @467-467; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createSignature @476-499; FunctionExpression; parameters=1; async=true; generator=false
- deleteSignature @501-517; FunctionExpression; parameters=1; async=true; generator=false
- _updatedPreference @519-543; FunctionExpression; parameters=0; async=false; generator=false
- _setPreferences @545-576; FunctionExpression; parameters=1; async=false; generator=false
- _recordExposure @578-580; FunctionExpression; parameters=0; async=false; generator=false
- _reportTelemetry @582-584; FunctionExpression; parameters=1; async=false; generator=false
- _mlGuess @586-617; FunctionExpression; parameters=1; async=true; generator=false
- _loadAIEngine @619-732; FunctionExpression; parameters=1; async=true; generator=false
- timeoutCallback @644-667; ArrowFunctionExpression; parameters=0; async=false; generator=false
- progressCallback @670-725; FunctionExpression; parameters=1; async=false; generator=false
- _mlDelete @734-759; FunctionExpression; parameters=1; async=true; generator=false
- createAIEngine @761-776; FunctionExpression; parameters=2; async=true; generator=false
- _saveURL @778-801; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @794-799; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _updateControlState @803-851; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @808-850; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _reportText @858-870; FunctionExpression; parameters=1; async=false; generator=false
- _updateMatchesCount @872-885; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @877-884; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _requestMatchesCount @887-901; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @903-958; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @918-920; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _addEventListener @960-969; FunctionExpression; parameters=0; async=false; generator=false
- _hookupEventListeners @976-992; FunctionExpression; parameters=1; async=false; generator=false
- _removeEventListener @994-1017; FunctionExpression; parameters=0; async=false; generator=false
- Class PdfJsParent @163-1018
- Module resource://gre/modules/XPCOMUtils.sys.mjs @16; ImportDeclaration
- Module resource://pdf.js/PdfJsTelemetry.sys.mjs @17; ImportDeclaration
- Module resource://gre/modules/FinderSound.sys.mjs @18; ImportDeclaration

### toolkit/components/pdfjs/content/PdfJsPrint.sys.mjs

Blob: `d9f8d410053e55a4a59793dcbeb9a3a03864a6b8`. Role: source. Parse: module.

- doesViewerOwnTarget @30-48; FunctionDeclaration; parameters=2; async=false; generator=false
- hasPDFHeaderAndEOF @51-69; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @64-64; ArrowFunctionExpression; parameters=2; async=false; generator=false
- printToPDF @84-175; FunctionExpression; parameters=4; async=true; generator=false

### toolkit/components/pdfjs/content/PdfJsTelemetry.sys.mjs

Blob: `ec84a1944f6d2e425056282c7ce8e5a056534993`. Role: source. Parse: module.

- onViewerIsUsed @17-19; FunctionExpression; parameters=0; async=false; generator=false
- fixKeys @23-33; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- report @35-71; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @49-49; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onTimeToView @73-75; FunctionExpression; parameters=1; async=false; generator=false
- onEditing @77-194; FunctionExpression; parameters=1; async=false; generator=false
- onImage @196-270; FunctionExpression; parameters=1; async=false; generator=false
- onSignature @272-298; FunctionExpression; parameters=1; async=false; generator=false
- onButtons @300-302; FunctionExpression; parameters=1; async=false; generator=false
- onGeckoview @304-306; FunctionExpression; parameters=1; async=false; generator=false
- onComment @308-310; FunctionExpression; parameters=1; async=false; generator=false
- onCommentSidebar @312-314; FunctionExpression; parameters=1; async=false; generator=false
- onPageOrganization @316-319; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @317-317; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class PdfJsTelemetry @22-320
- Class PdfJsTelemetryContent @16-20

### toolkit/components/pdfjs/content/PdfJsVersion.sys.mjs

Blob: `dc3d6220ad87a0edfaaec5e9cd223976808a6b18`. Role: source. Parse: module.


### toolkit/components/pdfjs/content/PdfSandbox.sys.mjs

Blob: `02f8120227aa7832fdc47fdbf5f1fb0e86b72713`. Role: source. Parse: module.

- constructor @19-22; FunctionExpression; parameters=2; async=false; generator=false
- exportValueToSandbox @23-25; FunctionExpression; parameters=1; async=false; generator=false
- importValueFromSandbox @27-29; FunctionExpression; parameters=1; async=false; generator=false
- createErrorForSandbox @31-33; FunctionExpression; parameters=1; async=false; generator=false
- constructor @37-74; FunctionExpression; parameters=2; async=false; generator=false
- dispatchEvent @76-78; FunctionExpression; parameters=1; async=false; generator=false
- destroy @80-87; FunctionExpression; parameters=0; async=false; generator=false
- Class PdfSandbox @36-88
- Class SandboxSupport @18-34
- Module resource://pdf.js/build/pdf.sandbox.external.sys.mjs @16; ImportDeclaration

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
