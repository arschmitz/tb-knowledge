<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["toolkit/mozapps/extensions/content/components/mlmodel-list-intro.mjs","toolkit/mozapps/extensions/content/components/native-theme-colors-checkbox.mjs","toolkit/mozapps/extensions/content/components/plugin-options.mjs","toolkit/mozapps/extensions/content/components/proxy-context-menu.mjs","toolkit/mozapps/extensions/content/components/recommended-addon-card.mjs","toolkit/mozapps/extensions/content/components/recommended-addon-list.mjs","toolkit/mozapps/extensions/content/components/recommended-extensions-footer.mjs","toolkit/mozapps/extensions/content/components/recommended-extensions-section.mjs","toolkit/mozapps/extensions/content/components/recommended-footer.mjs","toolkit/mozapps/extensions/content/components/recommended-section.mjs","toolkit/mozapps/extensions/content/components/recommended-themes-footer.mjs","toolkit/mozapps/extensions/content/components/recommended-themes-section.mjs","toolkit/mozapps/extensions/content/components/search-addons.mjs","toolkit/mozapps/extensions/content/components/smartwindow-themes-notice.mjs","toolkit/mozapps/extensions/content/components/taar-notice.mjs","toolkit/mozapps/extensions/content/components/theme-preview.mjs","toolkit/mozapps/extensions/content/components/update-release-notes.mjs","toolkit/mozapps/extensions/content/view-controller.mjs","toolkit/mozapps/extensions/internal/AboutAddonsTestUtils.sys.mjs","toolkit/mozapps/extensions/internal/AddonRepository.sys.mjs","toolkit/mozapps/extensions/internal/AddonSettings.sys.mjs","toolkit/mozapps/extensions/internal/AddonTestUtils.sys.mjs","toolkit/mozapps/extensions/internal/AddonUpdateChecker.sys.mjs","toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs","toolkit/mozapps/extensions/internal/ModelHubProvider.sys.mjs","toolkit/mozapps/extensions/internal/ProductAddonChecker.sys.mjs","toolkit/mozapps/extensions/internal/SitePermsAddonProvider.sys.mjs","toolkit/mozapps/extensions/internal/ThemesBundledLocalization.sys.mjs","toolkit/mozapps/extensions/internal/XPIDatabase.sys.mjs","toolkit/mozapps/extensions/internal/XPIExports.sys.mjs","toolkit/mozapps/extensions/internal/XPIInstall.sys.mjs","toolkit/mozapps/extensions/internal/XPIProvider.sys.mjs","toolkit/mozapps/extensions/internal/crypto-utils.sys.mjs","toolkit/mozapps/extensions/internal/siteperms-addon-utils.sys.mjs","toolkit/mozapps/extensions/test/browser/.eslintrc.mjs","toolkit/mozapps/extensions/test/browser/browser_AMBrowserExtensionsImport.js","toolkit/mozapps/extensions/test/browser/browser_about_debugging_link.js","toolkit/mozapps/extensions/test/browser/browser_addon_list_reordering.js","toolkit/mozapps/extensions/test/browser/browser_amo_abuse_report.js","toolkit/mozapps/extensions/test/browser/browser_bug572561.js","toolkit/mozapps/extensions/test/browser/browser_checkAddonCompatibility.js","toolkit/mozapps/extensions/test/browser/browser_dragdrop.js","toolkit/mozapps/extensions/test/browser/browser_file_xpi_no_process_switch.js","toolkit/mozapps/extensions/test/browser/browser_globalwarnings.js","toolkit/mozapps/extensions/test/browser/browser_gmpProvider.js","toolkit/mozapps/extensions/test/browser/browser_history_navigation.js","toolkit/mozapps/extensions/test/browser/browser_html_a11y_no_horizontal_overflow.js","toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions.js","toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_file_access.js","toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_policy_blocked.js","toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_userScripts.js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/toolkit JavaScript function map 1361

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### toolkit/mozapps/extensions/content/components/mlmodel-list-intro.mjs

Blob: `95474cb0f25259624110804372e527620a49add8`. Role: source. Parse: module.

- render @9-11; FunctionExpression; parameters=0; async=false; generator=false
- template @13-30; FunctionExpression; parameters=0; async=false; generator=false
- Class MLModelListIntro @8-31
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @6; ImportDeclaration

### toolkit/mozapps/extensions/content/components/native-theme-colors-checkbox.mjs

Blob: `d4cf2db49880066388f7fd426f590f392c0dc0ff`. Role: source. Parse: module.

- shouldShowNativeThemeCheckbox @20-26; FunctionDeclaration; parameters=1; async=false; generator=false
- observe @42-42; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @48-51; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @53-58; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @60-63; FunctionExpression; parameters=0; async=false; generator=false
- willUpdate @65-73; FunctionExpression; parameters=1; async=false; generator=false
- startObserving @75-82; FunctionExpression; parameters=0; async=false; generator=false
- stopObserving @84-90; FunctionExpression; parameters=0; async=false; generator=false
- updateFromPref @92-94; FunctionExpression; parameters=0; async=false; generator=false
- onChange @96-104; FunctionExpression; parameters=1; async=false; generator=false
- render @106-121; FunctionExpression; parameters=0; async=false; generator=false
- Class NativeThemeColorsCheckbox @35-122
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @6; ImportDeclaration
- Module ../aboutaddons-utils.mjs @7; ImportDeclaration
- Module resource://gre/modules/AppConstants.sys.mjs @9; ChromeUtils-import-literal

### toolkit/mozapps/extensions/content/components/plugin-options.mjs

Blob: `a8cc315ad369393fa559dd328db1989772aa0629`. Role: source. Parse: module.

- markup @10-37; FunctionExpression; parameters=0; async=false; generator=false
- setElementState @39-52; FunctionExpression; parameters=3; async=false; generator=false
- Class PluginOptions @9-53
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration
- Module ./addon-options.mjs @7; ImportDeclaration

### toolkit/mozapps/extensions/content/components/proxy-context-menu.mjs

Blob: `3609450bee85e65181127fd8bc3dd7ad125f8068`. Role: source. Parse: module.

- openPopupAtScreen @7-12; FunctionExpression; parameters=1; async=false; generator=false
- Class ProxyContextMenu @6-13

### toolkit/mozapps/extensions/content/components/recommended-addon-card.mjs

Blob: `26fc15e0709e4676649fffafa935ecba82c7539c`. Role: source. Parse: module.

- markup @19-36; FunctionExpression; parameters=0; async=false; generator=false
- connectCallback @37-39; FunctionExpression; parameters=0; async=false; generator=false
- disconnectCallback @40-42; FunctionExpression; parameters=0; async=false; generator=false
- render @43-45; FunctionExpression; parameters=0; async=false; generator=false
- markup @52-64; FunctionExpression; parameters=0; async=false; generator=false
- connectCallback @65-67; FunctionExpression; parameters=0; async=false; generator=false
- disconnectCallback @68-70; FunctionExpression; parameters=0; async=false; generator=false
- render @71-73; FunctionExpression; parameters=0; async=false; generator=false
- setDiscoAddon @99-138; FunctionExpression; parameters=1; async=false; generator=false
- setCardContent @147-176; FunctionExpression; parameters=2; async=false; generator=false
- setCardDescription @178-201; FunctionExpression; parameters=2; async=false; generator=false
- registerButtons @203-212; FunctionExpression; parameters=2; async=false; generator=false
- handleEvent @214-224; FunctionExpression; parameters=1; async=false; generator=false
- installDiscoAddon @226-245; FunctionExpression; parameters=0; async=true; generator=false
- setAddon @251-257; FunctionExpression; parameters=1; async=false; generator=false
- Class RecommendedAddonCard @94-258
- Class RecommendedAddonDescription @51-74
- Class RecommendedAddonName @18-46
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration
- Module ../view-controller.mjs @9; ImportDeclaration
- Module ./addon-card.mjs @10; ImportDeclaration
- Module resource://gre/modules/AddonManager.sys.mjs @12; ChromeUtils-import-literal

### toolkit/mozapps/extensions/content/components/recommended-addon-list.mjs

Blob: `2d048bf6c8d53213cb8dd41ad3d3a954733d5a6b`. Role: source. Parse: module.

- connectedCallback @15-21; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @23-25; FunctionExpression; parameters=0; async=false; generator=false
- type @27-29; FunctionExpression; parameters=0; async=false; generator=false
- type @39-41; FunctionExpression; parameters=1; async=false; generator=false
- hideInstalled @43-45; FunctionExpression; parameters=0; async=false; generator=false
- hideInstalled @56-58; FunctionExpression; parameters=1; async=false; generator=false
- getCardById @60-67; FunctionExpression; parameters=1; async=false; generator=false
- setAddonForCard @69-79; FunctionExpression; parameters=2; async=false; generator=false
- preferClientId @85-87; FunctionExpression; parameters=0; async=false; generator=false
- updateCardsWithAddonManager @89-101; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @91-91; ArrowFunctionExpression; parameters=1; async=false; generator=false
- loadCardsIfNeeded @103-109; FunctionExpression; parameters=0; async=true; generator=false
- _loadCards @111-130; FunctionExpression; parameters=0; async=true; generator=false
- onInstalled @136-141; FunctionExpression; parameters=1; async=false; generator=false
- onUninstalled @143-148; FunctionExpression; parameters=1; async=false; generator=false
- Class RecommendedAddonList @14-149
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration
- Module resource://gre/modules/AddonManager.sys.mjs @10; ChromeUtils-import-literal

### toolkit/mozapps/extensions/content/components/recommended-extensions-footer.mjs

Blob: `0ef05a9515638e1a4e66592a9a06ee7b127ddec7`. Role: source. Parse: module.

- markup @8-39; FunctionExpression; parameters=0; async=false; generator=false
- Class RecommendedExtensionsFooter @7-40
- Module ./recommended-footer.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/recommended-extensions-section.mjs

Blob: `83942c7ee72d1982acdff9a9c7ebd471303d49a3`. Role: source. Parse: module.

- markup @14-29; FunctionExpression; parameters=0; async=false; generator=false
- Class RecommendedExtensionsSection @13-30
- Module ./recommended-section.mjs @5; ImportDeclaration
- Module ./recommended-extensions-footer.mjs @10; ImportDeclaration

### toolkit/mozapps/extensions/content/components/recommended-footer.mjs

Blob: `ffe88d72270915730e4d48e89cd1cc061ef00d5e`. Role: source. Parse: module.

- markup @10-41; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @43-50; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @52-65; FunctionExpression; parameters=1; async=false; generator=false
- Class RecommendedFooter @9-66
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/recommended-section.mjs

Blob: `4250c40ff4d83f9aa30ec61bf23540ce4108eed7`. Role: source. Parse: module.

- connectedCallback @22-26; FunctionExpression; parameters=0; async=false; generator=false
- list @28-30; FunctionExpression; parameters=0; async=false; generator=false
- footer @32-34; FunctionExpression; parameters=0; async=false; generator=false
- render @36-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @43-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class RecommendedSection @21-47
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/recommended-themes-footer.mjs

Blob: `826d39d7b39d81b1433ef4505b50097e815aa856`. Role: source. Parse: module.

- markup @11-38; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @40-53; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @55-68; FunctionExpression; parameters=1; async=false; generator=false
- Class RecommendedThemesFooter @10-69
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/recommended-themes-section.mjs

Blob: `f4e59027fa7f3b441e48e751f13663bec4a0dc1d`. Role: source. Parse: module.

- markup @14-28; FunctionExpression; parameters=0; async=false; generator=false
- Class RecommendedThemesSection @13-29
- Module ./recommended-section.mjs @5; ImportDeclaration
- Module ./recommended-themes-footer.mjs @10; ImportDeclaration

### toolkit/mozapps/extensions/content/components/search-addons.mjs

Blob: `8a4ae723c60b1e823a53622fd8dbb142db87898a`. Role: source. Parse: module.

- connectedCallback @13-33; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @35-38; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @40-47; FunctionExpression; parameters=1; async=false; generator=false
- value @49-51; FunctionExpression; parameters=0; async=false; generator=false
- searchAddons @53-66; FunctionExpression; parameters=1; async=false; generator=false
- Class SearchAddons @12-67
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/smartwindow-themes-notice.mjs

Blob: `7fc8dfd86ede1a37749572fcc9981b041e664898`. Role: source. Parse: module.

- markup @13-24; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @26-38; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @40-51; FunctionExpression; parameters=0; async=false; generator=false
- render @53-64; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @66-70; FunctionExpression; parameters=1; async=false; generator=false
- observe @72-85; FunctionExpression; parameters=3; async=false; generator=false
- Class SmartWindowThemesNotice @10-86
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/taar-notice.mjs

Blob: `f314668b3ffa0044ad160e09c2a5494383341e3b`. Role: source. Parse: module.

- markup @10-28; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @30-40; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @42-46; FunctionExpression; parameters=1; async=false; generator=false
- Class TaarMessageBar @9-47
- Module ../aboutaddons-utils.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/content/components/theme-preview.mjs

Blob: `03e1f3e382dd621500102ac7b98a913cf163e121`. Role: source. Parse: module.

- onColorSchemeChange @32-32; ArrowFunctionExpression; parameters=0; async=false; generator=false
- createRenderRoot @34-36; FunctionExpression; parameters=0; async=false; generator=false
- connectedCallback @38-45; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @47-53; FunctionExpression; parameters=0; async=false; generator=false
- render @55-89; FunctionExpression; parameters=0; async=false; generator=false
- getExtraThemesListManager @91-115; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @111-114; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class ThemePreview @24-116
- Module chrome://global/content/vendor/lit.all.mjs @5; ImportDeclaration
- Module chrome://global/content/lit-utils.mjs @10; ImportDeclaration
- Module ../aboutaddons-utils.mjs @11; ImportDeclaration
- Module ./aboutaddons-themes-picker.mjs @16; ImportDeclaration

### toolkit/mozapps/extensions/content/components/update-release-notes.mjs

Blob: `da3411a31cad3d0bda3161c76e4cda4ce8639edc`. Role: source. Parse: module.

- connectedCallback @9-11; FunctionExpression; parameters=0; async=false; generator=false
- disconnectedCallback @13-15; FunctionExpression; parameters=0; async=false; generator=false
- handleEvent @17-25; FunctionExpression; parameters=1; async=false; generator=false
- loadForUri @27-58; FunctionExpression; parameters=1; async=true; generator=false
- setMessage @60-65; FunctionExpression; parameters=1; async=false; generator=false
- setLoadingMessage @67-69; FunctionExpression; parameters=0; async=false; generator=false
- setErrorMessage @71-73; FunctionExpression; parameters=0; async=false; generator=false
- Class UpdateReleaseNotes @8-74
- Module ../aboutaddons-utils.mjs @6; ImportDeclaration

### toolkit/mozapps/extensions/content/view-controller.mjs

Blob: `f294952066aec967c5b4f2e741051b9c18fd1a2d`. Role: source. Parse: module.

- loadView @9-14; FunctionDeclaration; parameters=1; async=false; generator=false
- defaultViewId @19-24; FunctionExpression; parameters=0; async=false; generator=false
- initialize @29-35; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @37-48; FunctionExpression; parameters=1; async=false; generator=false
- observe @50-55; FunctionExpression; parameters=2; async=false; generator=false
- notifyEMLoaded @57-60; FunctionExpression; parameters=0; async=false; generator=false
- notifyEMUpdateCheckFinished @62-65; FunctionExpression; parameters=0; async=false; generator=false
- defineView @67-74; FunctionExpression; parameters=2; async=false; generator=false
- parseViewId @76-80; FunctionExpression; parameters=1; async=false; generator=false
- loadView @82-102; FunctionExpression; parameters=2; async=false; generator=false
- renderState @104-164; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @139-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @140-153; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @141-152; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @144-148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- resetState @166-168; FunctionExpression; parameters=0; async=false; generator=false
- Module ./aboutaddons-utils.mjs @5; ImportDeclaration
- Module chrome://global/content/ScrollOffsets.mjs @6; ImportDeclaration

### toolkit/mozapps/extensions/internal/AboutAddonsTestUtils.sys.mjs

Blob: `583fd9d8f6c51d3448de719ccbcb9cf1f9a7d7fb`. Role: source. Parse: module.

- assertIsAboutAddonsWindow @10-19; FunctionDeclaration; parameters=2; async=false; generator=false
- assertIsAboutAddonsSidebarButton @21-35; FunctionDeclaration; parameters=1; async=false; generator=false
- getCategoriesBox @37-44; FunctionDeclaration; parameters=1; async=false; generator=false
- getAddonCard @47-50; FunctionExpression; parameters=2; async=false; generator=false
- getAddonCardMoreOptionsButton @52-69; FunctionExpression; parameters=2; async=false; generator=false
- getPageOptionsButton @71-80; FunctionExpression; parameters=1; async=false; generator=false
- getSidebarSelectedViewId @84-86; FunctionExpression; parameters=1; async=false; generator=false
- getSidebarSelectedCategory @88-90; FunctionExpression; parameters=1; async=false; generator=false
- getAllCategoryButtons @92-97; FunctionExpression; parameters=1; async=false; generator=false
- getCategoryButton @99-104; FunctionExpression; parameters=2; async=false; generator=false
- getCategoryBadgeCount @106-110; FunctionExpression; parameters=1; async=false; generator=false
- isCategoryButtonSelected @112-120; FunctionExpression; parameters=2; async=false; generator=false
- isCategoryVisible @122-129; FunctionExpression; parameters=2; async=false; generator=false
- clickCategoryButton @131-142; FunctionExpression; parameters=2; async=false; generator=false
- waitForCategoriesUpdate @151-159; FunctionExpression; parameters=1; async=true; generator=false
- Module resource://testing-common/Assert.sys.mjs @4; ImportDeclaration
- Module resource://testing-common/BrowserTestUtils.sys.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/internal/AddonRepository.sys.mjs

Blob: `60cf5c0499b686cb71e8f793ab386ea72a5d4048`. Role: source. Parse: module.

- (anonymous) @20-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- BLANK_DB @70-75; FunctionExpression; parameters=0; async=false; generator=false
- convertHTMLToPlainText @85-105; FunctionDeclaration; parameters=1; async=false; generator=false
- getAddonsToCache @107-142; FunctionDeclaration; parameters=1; async=true; generator=false
- AddonSearchResult @144-148; FunctionDeclaration; parameters=1; async=false; generator=false
- iconURL @199-201; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @268-303; FunctionExpression; parameters=0; async=false; generator=false
- homepageURL @322-325; FunctionExpression; parameters=0; async=false; generator=false
- appIsShuttingDown @327-329; FunctionExpression; parameters=0; async=false; generator=false
- getSearchURL @339-344; FunctionExpression; parameters=1; async=false; generator=false
- cacheEnabled @349-351; FunctionExpression; parameters=0; async=false; generator=false
- shutdown @358-360; FunctionExpression; parameters=0; async=false; generator=false
- metadataAge @362-366; FunctionExpression; parameters=0; async=false; generator=false
- isMetadataStale @368-374; FunctionExpression; parameters=0; async=false; generator=false
- getCachedAddonByID @387-408; FunctionExpression; parameters=2; async=true; generator=false
- _clearCache @415-419; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @416-417; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _createServiceRequest @426-428; FunctionExpression; parameters=0; async=false; generator=false
- _fetchPaged @450-503; FunctionExpression; parameters=3; async=false; generator=false
- fetchNextPage @454-500; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @455-499; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @472-474; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @475-477; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @478-496; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAddonsByIDs @512-531; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @513-518; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @523-527; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @525-525; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @527-527; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getMappedAddons @555-591; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @562-575; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @566-573; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @575-575; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cacheAddons @601-626; FunctionExpression; parameters=1; async=true; generator=false
- _getAllInstalledAddons @633-635; FunctionExpression; parameters=0; async=false; generator=false
- backgroundUpdateCheck @651-704; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @652-697; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @669-669; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateIfLocaleChanged @707-727; FunctionExpression; parameters=0; async=false; generator=false
- _parseAddon @736-821; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @779-780; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @789-803; ArrowFunctionExpression; parameters=1; async=false; generator=false
- safeSize @790-791; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _formatURLPref @824-838; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @831-835; FunctionExpression; parameters=2; async=false; generator=false
- flush @840-842; FunctionExpression; parameters=0; async=false; generator=false
- getAvailableLangpacks @844-880; FunctionExpression; parameters=0; async=true; generator=false
- jsonFile @895-900; FunctionExpression; parameters=0; async=false; generator=false
- openConnection @907-966; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @909-962; ArrowFunctionExpression; parameters=0; async=true; generator=false
- shutdown @978-991; FunctionExpression; parameters=1; async=false; generator=false
- delete @1001-1022; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1011-1011; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1012-1016; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1018-1018; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _saveNow @1024-1033; FunctionExpression; parameters=0; async=true; generator=false
- save @1035-1051; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1038-1038; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1045-1045; ArrowFunctionExpression; parameters=0; async=false; generator=false
- flush @1060-1072; FunctionExpression; parameters=0; async=false; generator=false
- getAddon @1081-1083; FunctionExpression; parameters=1; async=false; generator=false
- repopulate @1092-1101; FunctionExpression; parameters=1; async=false; generator=false
- update @1109-1113; FunctionExpression; parameters=1; async=true; generator=false
- _update @1121-1127; FunctionExpression; parameters=1; async=false; generator=false
- _parseAddon @1137-1242; FunctionExpression; parameters=1; async=false; generator=false
- _makeDeveloper @1252-1256; FunctionExpression; parameters=1; async=false; generator=false
- _makeScreenshot @1266-1283; FunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/Log.sys.mjs @77; ImportDeclaration

### toolkit/mozapps/extensions/internal/AddonSettings.sys.mjs

Blob: `09bb0adc97170edb414d8da91c61ec2232aa64c6`. Role: source. Parse: module.

- makeConstant @23-30; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/AppConstants.sys.mjs @6; ImportDeclaration
- Module resource://gre/modules/AddonManager.sys.mjs @8; ImportDeclaration

### toolkit/mozapps/extensions/internal/AddonTestUtils.sys.mjs

Blob: `ea3150718351797f5627317a7d53f16a7721363b`. Role: source. Parse: module.

- isRegExp @68-70; FunctionDeclaration; parameters=1; async=false; generator=false
- constructor @73-76; FunctionExpression; parameters=1; async=false; generator=false
- addBlocker @78-80; FunctionExpression; parameters=3; async=false; generator=false
- trigger @82-101; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @84-97; ArrowFunctionExpression; parameters=1; async=true; generator=false
- constructor @117-161; FunctionExpression; parameters=1; async=false; generator=false
- hasItem @163-185; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @170-184; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasTheme @187-189; FunctionExpression; parameters=2; async=false; generator=false
- hasExtension @191-193; FunctionExpression; parameters=2; async=false; generator=false
- resetXPIExports @205-232; FunctionDeclaration; parameters=1; async=false; generator=false
- maybeInit @247-251; FunctionExpression; parameters=1; async=false; generator=false
- init @253-393; FunctionExpression; parameters=2; async=false; generator=false
- pathShouldntExist @324-330; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @332-392; ArrowFunctionExpression; parameters=0; async=false; generator=false
- initMochitest @395-424; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @412-423; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @414-416; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getXPIExports @426-430; FunctionExpression; parameters=0; async=false; generator=false
- getWeakSignatureInstallPrefName @432-434; FunctionExpression; parameters=0; async=false; generator=false
- setWeakSignatureInstallAllowed @436-453; FunctionExpression; parameters=1; async=false; generator=false
- cleanup @439-448; ArrowFunctionExpression; parameters=0; async=false; generator=false
- iterDirectory @463-480; FunctionExpression; parameters=1; async=false; generator=true
- createHttpServer @499-502; FunctionExpression; parameters=1; async=false; generator=false
- registerJSON @504-506; FunctionExpression; parameters=1; async=false; generator=false
- info @508-512; FunctionExpression; parameters=1; async=false; generator=false
- cleanupTempXPIs @514-541; FunctionExpression; parameters=0; async=false; generator=false
- createAppInfo @543-552; FunctionExpression; parameters=4; async=false; generator=false
- updateAppInfo @554-570; FunctionExpression; parameters=1; async=false; generator=false
- getManifestURI @572-594; FunctionExpression; parameters=1; async=false; generator=false
- getIDFromExtension @596-598; FunctionExpression; parameters=1; async=false; generator=false
- getIDFromManifest @600-613; FunctionExpression; parameters=1; async=true; generator=false
- overrideCertDB @617-735; FunctionExpression; parameters=0; async=false; generator=false
- verifyCert @623-687; ArrowFunctionExpression; parameters=4; async=true; generator=false
- init @692-704; FunctionExpression; parameters=0; async=false; generator=false
- openSignedAppFileAsync @706-723; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @711-721; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @713-719; ArrowFunctionExpression; parameters=1; async=false; generator=false
- loadBlocklistData @751-764; FunctionExpression; parameters=2; async=true; generator=false
- loadBlocklistRawData @774-815; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @806-806; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseStartupManager @831-905; FunctionExpression; parameters=1; async=true; generator=false
- XPIExports.XPIInternal.BootstrapScope.prototype._beforeCallBootstrapMethod @863-873; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @896-896; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseShutdownManager @907-988; FunctionExpression; parameters=1; async=true; generator=false
- promiseRestartManager @999-1002; FunctionExpression; parameters=1; async=true; generator=false
- notifyEarlyStartup @1010-1012; FunctionExpression; parameters=0; async=false; generator=false
- notifyLateStartup @1021-1023; FunctionExpression; parameters=0; async=false; generator=false
- loadAddonsList @1025-1035; FunctionExpression; parameters=1; async=true; generator=false
- writeFilesToZip @1048-1083; FunctionExpression; parameters=3; async=false; generator=false
- promiseWriteFilesToZip @1085-1091; FunctionExpression; parameters=3; async=true; generator=false
- promiseWriteFilesToDir @1093-1121; FunctionExpression; parameters=2; async=true; generator=false
- promiseWriteFilesToExtension @1123-1133; FunctionExpression; parameters=4; async=false; generator=false
- allocTempXPIFile @1137-1145; FunctionExpression; parameters=0; async=false; generator=false
- createTempXPIFile @1155-1159; FunctionExpression; parameters=1; async=false; generator=false
- createTempWebExtensionFile @1170-1174; FunctionExpression; parameters=1; async=false; generator=false
- promiseInstallXPI @1184-1186; FunctionExpression; parameters=1; async=false; generator=false
- promiseWriteProxyFileToDir @1200-1206; FunctionExpression; parameters=3; async=false; generator=false
- manuallyInstall @1226-1274; FunctionExpression; parameters=4; async=true; generator=false
- manuallyUninstall @1288-1298; FunctionExpression; parameters=3; async=false; generator=false
- getFileForAddon @1315-1323; FunctionExpression; parameters=3; async=false; generator=false
- setExtensionModifiedTime @1334-1341; FunctionExpression; parameters=2; async=false; generator=false
- promiseSetExtensionModifiedTime @1343-1363; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1355-1355; ArrowFunctionExpression; parameters=1; async=false; generator=false
- registerDirectory @1365-1388; FunctionExpression; parameters=2; async=false; generator=false
- getFile @1367-1373; FunctionExpression; parameters=2; async=false; generator=false
- promiseAddonEvent @1406-1420; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1407-1419; ArrowFunctionExpression; parameters=1; async=false; generator=false
- event @1409-1415; FunctionExpression; parameters=1; async=false; generator=false
- promiseInstallEvent @1422-1436; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1423-1435; ArrowFunctionExpression; parameters=1; async=false; generator=false
- event @1425-1431; FunctionExpression; parameters=1; async=false; generator=false
- promiseManagerEvent @1438-1452; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1439-1451; ArrowFunctionExpression; parameters=1; async=false; generator=false
- event @1441-1447; FunctionExpression; parameters=1; async=false; generator=false
- promiseCompleteInstall @1463-1489; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1465-1485; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallEnded @1472-1479; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1485-1488; ArrowFunctionExpression; parameters=0; async=false; generator=false
- promiseInstallFile @1505-1531; FunctionExpression; parameters=3; async=true; generator=false
- promiseInstallAllFiles @1544-1550; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1546-1547; ArrowFunctionExpression; parameters=1; async=false; generator=false
- promiseCompleteAllInstalls @1552-1554; FunctionExpression; parameters=1; async=false; generator=false
- promiseFindAddonUpdates @1575-1633; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1583-1632; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onNoCompatibilityUpdateAvailable @1587-1593; FunctionExpression; parameters=1; async=false; generator=false
- onCompatibilityUpdateAvailable @1595-1601; FunctionExpression; parameters=1; async=false; generator=false
- onNoUpdateAvailable @1603-1609; FunctionExpression; parameters=1; async=false; generator=false
- onUpdateAvailable @1611-1617; FunctionExpression; parameters=2; async=false; generator=false
- onUpdateFinished @1619-1627; FunctionExpression; parameters=2; async=false; generator=false
- promiseConsoleOutput @1649-1676; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1654-1663; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @1655-1662; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkMessages @1711-1761; FunctionExpression; parameters=2; async=false; generator=false
- msgMatches @1715-1726; FunctionDeclaration; parameters=2; async=false; generator=false
- validateOptionFormat @1728-1736; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1743-1743; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkInstallInfo @1775-1799; FunctionExpression; parameters=3; async=false; generator=false
- promiseWebExtensionStartup @1810-1819; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1811-1818; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @1812-1817; FunctionExpression; parameters=2; async=false; generator=false
- waitForSearchProviderStartup @1834-1864; FunctionExpression; parameters=2; async=true; generator=false
- initializeURLPreloader @1870-1872; FunctionExpression; parameters=0; async=false; generator=false
- overrideBuiltIns @1880-1896; FunctionExpression; parameters=1; async=true; generator=false
- assertSitePermissionInstallSteps @1914-1933; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1923-1923; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAMGleanEvents @1940-1958; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1947-1947; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1949-1950; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1950-1950; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1954-1954; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1957-1957; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class AddonsList @116-194
- Class MockBarrier @72-102
- Module resource://gre/modules/AddonManager.sys.mjs @10; ImportDeclaration
- Module resource://gre/modules/AsyncShutdown.sys.mjs @15; ImportDeclaration
- Module resource://gre/modules/FileUtils.sys.mjs @16; ImportDeclaration
- Module resource://gre/modules/NetUtil.sys.mjs @17; ImportDeclaration
- Module resource://gre/modules/XPCOMUtils.sys.mjs @18; ImportDeclaration
- Module resource://gre/modules/EventEmitter.sys.mjs @19; ImportDeclaration
- Module resource://gre/modules/addons/XPIExports.sys.mjs @427; ChromeUtils-import-literal
- Module resource://gre/modules/Blocklist.sys.mjs @775; ChromeUtils-import-literal
- Module resource://gre/modules/addons/XPIExports.sys.mjs @857; ChromeUtils-import-literal
- Module resource://gre/modules/addons/XPIExports.sys.mjs @920; ChromeUtils-import-literal
- Module resource://gre/modules/addons/XPIExports.sys.mjs @1027; ChromeUtils-import-literal

### toolkit/mozapps/extensions/internal/AddonUpdateChecker.sys.mjs

Blob: `5b7b10a7641c57e1f5206fb57030c8c2afb60971`. Role: source. Parse: module.

- sanitizeUpdateURL @50-79; FunctionDeclaration; parameters=4; async=false; generator=false
- parseJSONManifest @93-243; FunctionDeclaration; parameters=3; async=false; generator=false
- array @95-95; ArrowFunctionExpression; parameters=1; async=false; generator=false
- object @96-96; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getProperty @99-115; FunctionDeclaration; parameters=4; async=false; generator=false
- getRequiredProperty @117-125; FunctionDeclaration; parameters=3; async=false; generator=false
- UpdateParser @256-281; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @274-274; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @275-275; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @276-276; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onLoad @292-356; FunctionExpression; parameters=0; async=false; generator=false
- onTimeout @361-366; FunctionExpression; parameters=0; async=false; generator=false
- onError @371-397; FunctionExpression; parameters=0; async=false; generator=false
- notifyError @402-410; FunctionExpression; parameters=1; async=false; generator=false
- cancel @415-424; FunctionExpression; parameters=0; async=false; generator=false
- matchesVersions @442-470; FunctionDeclaration; parameters=5; async=false; generator=false
- getCompatibilityUpdate @494-533; FunctionExpression; parameters=7; async=false; generator=false
- getNewestCompatibleUpdate @552-626; FunctionExpression; parameters=6; async=true; generator=false
- checkForUpdates @640-642; FunctionExpression; parameters=3; async=false; generator=false
- Module resource://gre/modules/Log.sys.mjs @24; ImportDeclaration

### toolkit/mozapps/extensions/internal/GMPProvider.sys.mjs

Blob: `e0844cef4dafdeef74a0e34de11c9934ad5aa60f`. Role: source. Parse: module.

- (anonymous) @81-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @83-86; ArrowFunctionExpression; parameters=0; async=false; generator=false
- configureLogging @98-122; FunctionDeclaration; parameters=0; async=false; generator=false
- GMPWrapper @128-149; FunctionDeclaration; parameters=2; async=false; generator=false
- gmpPath @162-164; FunctionExpression; parameters=1; async=false; generator=false
- gmpPath @165-174; FunctionExpression; parameters=0; async=false; generator=false
- id @176-178; FunctionExpression; parameters=0; async=false; generator=false
- libName @179-181; FunctionExpression; parameters=0; async=false; generator=false
- type @182-184; FunctionExpression; parameters=0; async=false; generator=false
- isGMPlugin @185-187; FunctionExpression; parameters=0; async=false; generator=false
- name @188-190; FunctionExpression; parameters=0; async=false; generator=false
- creator @191-193; FunctionExpression; parameters=0; async=false; generator=false
- homepageURL @194-196; FunctionExpression; parameters=0; async=false; generator=false
- description @198-200; FunctionExpression; parameters=0; async=false; generator=false
- fullDescription @201-203; FunctionExpression; parameters=0; async=false; generator=false
- getFullDescription @205-235; FunctionExpression; parameters=1; async=false; generator=false
- version @237-243; FunctionExpression; parameters=0; async=false; generator=false
- isActive @245-251; FunctionExpression; parameters=0; async=false; generator=false
- appDisabled @252-261; FunctionExpression; parameters=0; async=false; generator=false
- userDisabled @263-269; FunctionExpression; parameters=0; async=false; generator=false
- userDisabled @270-276; FunctionExpression; parameters=1; async=false; generator=false
- enable @278-280; FunctionExpression; parameters=0; async=true; generator=false
- disable @281-283; FunctionExpression; parameters=0; async=true; generator=false
- blocklistState @285-287; FunctionExpression; parameters=0; async=false; generator=false
- size @288-290; FunctionExpression; parameters=0; async=false; generator=false
- scope @291-293; FunctionExpression; parameters=0; async=false; generator=false
- pendingOperations @294-296; FunctionExpression; parameters=0; async=false; generator=false
- operationsRequiringRestart @298-300; FunctionExpression; parameters=0; async=false; generator=false
- permissions @302-311; FunctionExpression; parameters=0; async=false; generator=false
- updateDate @313-321; FunctionExpression; parameters=0; async=false; generator=false
- isCompatible @323-325; FunctionExpression; parameters=0; async=false; generator=false
- isPlatformCompatible @327-329; FunctionExpression; parameters=0; async=false; generator=false
- providesUpdatesSecurely @331-333; FunctionExpression; parameters=0; async=false; generator=false
- foreignInstall @335-337; FunctionExpression; parameters=0; async=false; generator=false
- installTelemetryInfo @339-341; FunctionExpression; parameters=0; async=false; generator=false
- isCompatibleWith @343-345; FunctionExpression; parameters=0; async=false; generator=false
- applyBackgroundUpdates @347-359; FunctionExpression; parameters=0; async=false; generator=false
- applyBackgroundUpdates @361-369; FunctionExpression; parameters=1; async=false; generator=false
- findUpdates @380-458; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @426-455; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @431-431; ArrowFunctionExpression; parameters=1; async=false; generator=false
- pluginLibraries @460-466; FunctionExpression; parameters=0; async=false; generator=false
- pluginFullpath @467-477; FunctionExpression; parameters=0; async=false; generator=false
- isInstalled @479-481; FunctionExpression; parameters=0; async=false; generator=false
- _handleEnabledChanged @483-513; FunctionExpression; parameters=0; async=false; generator=false
- onPrefEMEGlobalEnabledChanged @515-549; FunctionExpression; parameters=0; async=false; generator=false
- checkForUpdates @557-574; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @565-573; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @570-570; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onPrefEnabledChanged @576-580; FunctionExpression; parameters=0; async=false; generator=false
- onPrefVersionChanged @582-618; FunctionExpression; parameters=0; async=false; generator=false
- observe @620-639; FunctionExpression; parameters=3; async=false; generator=false
- uninstallPlugin @641-654; FunctionExpression; parameters=0; async=false; generator=false
- shutdown @656-670; FunctionExpression; parameters=0; async=false; generator=false
- _arePluginFilesOnDisk @672-695; FunctionExpression; parameters=0; async=false; generator=false
- fileExists @673-678; FunctionExpression; parameters=2; async=false; generator=false
- validate @697-728; FunctionExpression; parameters=0; async=false; generator=false
- name @732-734; FunctionExpression; parameters=0; async=false; generator=false
- startup @738-813; FunctionExpression; parameters=0; async=false; generator=false
- shutdown @815-839; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @819-836; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getAddonByID @841-851; FunctionExpression; parameters=1; async=true; generator=false
- getAddonsByTypes @853-863; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @859-859; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @860-860; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isEnabled @865-867; FunctionExpression; parameters=0; async=false; generator=false
- buildPluginList @869-885; FunctionExpression; parameters=0; async=false; generator=false
- ensureProperCDMInstallState @887-896; FunctionExpression; parameters=0; async=false; generator=false
- observe @898-905; FunctionExpression; parameters=2; async=false; generator=false
- addObserver @907-909; FunctionExpression; parameters=0; async=false; generator=false
- overrideGmpService @925-933; FunctionExpression; parameters=2; async=true; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/AppConstants.sys.mjs @7; ImportDeclaration
- Module resource://gre/modules/GMPUtils.sys.mjs @19; ImportDeclaration

### toolkit/mozapps/extensions/internal/ModelHubProvider.sys.mjs

Blob: `e070a0c044a9693951776a1672033d17d6896c4c`. Role: source. Parse: module.

- (anonymous) @24-24; ArrowFunctionExpression; parameters=3; async=false; generator=false
- constructor @42-53; FunctionExpression; parameters=1; async=false; generator=false
- uninstall @55-63; FunctionExpression; parameters=0; async=true; generator=false
- usedByFirefoxFeatures @65-67; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @66-66; ArrowFunctionExpression; parameters=1; async=false; generator=false
- usedByAddonIds @69-73; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @71-71; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @72-72; ArrowFunctionExpression; parameters=1; async=false; generator=false
- name @75-81; FunctionExpression; parameters=0; async=false; generator=false
- modelHomepageURL @83-92; FunctionExpression; parameters=0; async=false; generator=false
- isActive @94-96; FunctionExpression; parameters=0; async=false; generator=false
- isCompatible @98-100; FunctionExpression; parameters=0; async=false; generator=false
- permissions @102-104; FunctionExpression; parameters=0; async=false; generator=false
- type @106-108; FunctionExpression; parameters=0; async=false; generator=false
- iconURL @111-116; FunctionExpression; parameters=0; async=false; generator=false
- name @123-125; FunctionExpression; parameters=0; async=false; generator=false
- getAddonsByTypes @127-138; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @134-135; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAddonByID @140-145; FunctionExpression; parameters=1; async=true; generator=false
- observe @147-154; FunctionExpression; parameters=3; async=false; generator=false
- shutdown @156-162; FunctionExpression; parameters=0; async=false; generator=false
- init @164-172; FunctionExpression; parameters=0; async=false; generator=false
- onUninstalled @174-180; FunctionExpression; parameters=1; async=true; generator=false
- clearAddonCache @182-184; FunctionExpression; parameters=0; async=false; generator=false
- getWrapperIdForModel @186-191; FunctionExpression; parameters=1; async=false; generator=false
- refreshAddonCache @193-231; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @214-214; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class ModelHubAddonWrapper @30-117
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/internal/ProductAddonChecker.sys.mjs

Blob: `b774662595881d614b6fe7f38476745494e0b2ad`. Role: source. Parse: module.

- getRequestStatus @42-62; FunctionDeclaration; parameters=1; async=false; generator=false
- conservativeFetch @74-109; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @75-108; FunctionExpression; parameters=2; async=false; generator=false
- request.onerror @79-83; ArrowFunctionExpression; parameters=0; async=false; generator=false
- request.ontimeout @84-88; ArrowFunctionExpression; parameters=0; async=false; generator=false
- request.onabort @89-93; ArrowFunctionExpression; parameters=0; async=false; generator=false
- request.onload @94-101; ArrowFunctionExpression; parameters=0; async=false; generator=false
- verifyGmpContentSignature @128-217; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @148-148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @149-157; ArrowFunctionExpression; parameters=1; async=false; generator=false
- downloadXMLWithRequest @230-308; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @231-307; ArrowFunctionExpression; parameters=2; async=false; generator=false
- fail @258-281; ArrowFunctionExpression; parameters=1; async=false; generator=false
- success @283-298; ArrowFunctionExpression; parameters=1; async=false; generator=false
- downloadXML @327-342; FunctionDeclaration; parameters=4; async=true; generator=false
- parseXML @353-404; FunctionDeclaration; parameters=1; async=false; generator=false
- downloadFile @417-472; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @418-471; ArrowFunctionExpression; parameters=2; async=false; generator=false
- sr.onload @421-437; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @427-436; FunctionExpression; parameters=0; async=true; generator=false
- fail @439-455; ArrowFunctionExpression; parameters=1; async=false; generator=false
- downloadAndVerifyFile @474-492; FunctionDeclaration; parameters=3; async=true; generator=false
- verifyFile @505-528; FunctionExpression; parameters=2; async=true; generator=false
- getProductAddonList @560-572; FunctionExpression; parameters=4; async=false; generator=false
- downloadAddon @586-599; FunctionExpression; parameters=2; async=true; generator=false
- overrideServiceRequest @611-621; FunctionExpression; parameters=2; async=true; generator=false
- lazy.ServiceRequest @613-615; FunctionExpression; parameters=0; async=false; generator=false
- Module resource://gre/modules/Log.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/CertUtils.sys.mjs @6; ImportDeclaration

### toolkit/mozapps/extensions/internal/SitePermsAddonProvider.sys.mjs

Blob: `5903dd80d13dbbee77c409a675bba4ceff222b71`. Role: source. Parse: module.

- (anonymous) @25-25; ArrowFunctionExpression; parameters=0; async=false; generator=false
- generateSalt @46-55; FunctionDeclaration; parameters=0; async=false; generator=false
- getSalt @57-62; FunctionDeclaration; parameters=0; async=false; generator=false
- constructor @83-98; FunctionExpression; parameters=2; async=false; generator=false
- isUninstalled @100-102; FunctionExpression; parameters=0; async=false; generator=false
- sitePermissions @109-111; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @110-110; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handlePermissionChange @121-139; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @128-132; ArrowFunctionExpression; parameters=1; async=false; generator=false
- type @141-143; FunctionExpression; parameters=0; async=false; generator=false
- name @145-149; FunctionExpression; parameters=0; async=false; generator=false
- creator @151-153; FunctionExpression; parameters=0; async=false; generator=false
- homepageURL @155-157; FunctionExpression; parameters=0; async=false; generator=false
- description @159-161; FunctionExpression; parameters=0; async=false; generator=false
- fullDescription @163-165; FunctionExpression; parameters=0; async=false; generator=false
- version @167-171; FunctionExpression; parameters=0; async=false; generator=false
- updateDate @172-174; FunctionExpression; parameters=0; async=false; generator=false
- isActive @176-178; FunctionExpression; parameters=0; async=false; generator=false
- appDisabled @180-182; FunctionExpression; parameters=0; async=false; generator=false
- userDisabled @184-186; FunctionExpression; parameters=0; async=false; generator=false
- userDisabled @187-187; FunctionExpression; parameters=1; async=false; generator=false
- size @189-191; FunctionExpression; parameters=0; async=false; generator=false
- updateBlocklistState @193-193; FunctionExpression; parameters=0; async=true; generator=false
- blocklistState @195-197; FunctionExpression; parameters=0; async=false; generator=false
- scope @199-201; FunctionExpression; parameters=0; async=false; generator=false
- pendingOperations @203-205; FunctionExpression; parameters=0; async=false; generator=false
- operationsRequiringRestart @207-209; FunctionExpression; parameters=0; async=false; generator=false
- permissions @211-214; FunctionExpression; parameters=0; async=false; generator=false
- signedState @216-219; FunctionExpression; parameters=0; async=false; generator=false
- enable @221-221; FunctionExpression; parameters=0; async=true; generator=false
- disable @223-223; FunctionExpression; parameters=0; async=true; generator=false
- uninstall @230-258; FunctionExpression; parameters=0; async=true; generator=false
- isCompatible @260-262; FunctionExpression; parameters=0; async=false; generator=false
- isPlatformCompatible @264-266; FunctionExpression; parameters=0; async=false; generator=false
- providesUpdatesSecurely @268-270; FunctionExpression; parameters=0; async=false; generator=false
- foreignInstall @272-274; FunctionExpression; parameters=0; async=false; generator=false
- installTelemetryInfo @276-278; FunctionExpression; parameters=0; async=false; generator=false
- isCompatibleWith @280-282; FunctionExpression; parameters=0; async=false; generator=false
- constructor @294-304; FunctionExpression; parameters=2; async=false; generator=false
- existingAddon @306-308; FunctionExpression; parameters=0; async=false; generator=false
- uninstall @310-328; FunctionExpression; parameters=0; async=false; generator=false
- validInstallOrigins @330-334; FunctionExpression; parameters=0; async=false; generator=false
- constructor @353-362; FunctionExpression; parameters=2; async=false; generator=false
- installTelemetryInfo @364-366; FunctionExpression; parameters=0; async=false; generator=false
- checkPrompt @368-399; FunctionExpression; parameters=0; async=true; generator=false
- install @401-423; FunctionExpression; parameters=0; async=false; generator=false
- cancel @425-435; FunctionExpression; parameters=0; async=false; generator=false
- addListener @446-448; FunctionExpression; parameters=1; async=false; generator=false
- removeListener @455-457; FunctionExpression; parameters=1; async=false; generator=false
- callInstallListeners @464-475; FunctionExpression; parameters=1; async=false; generator=false
- name @479-481; FunctionExpression; parameters=0; async=false; generator=false
- handlePermissionChange @491-546; FunctionExpression; parameters=2; async=false; generator=false
- lazyInit @554-567; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @556-564; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shutdown @569-575; FunctionExpression; parameters=0; async=false; generator=false
- getAddonByID @583-595; FunctionExpression; parameters=1; async=true; generator=false
- getAddonsByTypes @605-616; FunctionExpression; parameters=1; async=true; generator=false
- getSitePermsAddonInstallForWebpage @625-627; FunctionExpression; parameters=2; async=false; generator=false
- isEnabled @629-631; FunctionExpression; parameters=0; async=false; generator=false
- observe @633-658; FunctionExpression; parameters=3; async=false; generator=false
- addFirstContentProcessObserver @660-662; FunctionExpression; parameters=0; async=false; generator=false
- Class SitePermsAddonInstall @341-476
- Class SitePermsAddonInstalling @285-335
- Class SitePermsAddonWrapper @64-283
- Module resource://gre/modules/addons/crypto-utils.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/addons/siteperms-addon-utils.sys.mjs @6; ImportDeclaration
- Module resource://gre/modules/XPCOMUtils.sys.mjs @14; ImportDeclaration

### toolkit/mozapps/extensions/internal/ThemesBundledLocalization.sys.mjs

Blob: `33aea9bc587416d83bccbeb6af7d931da2a76bc4`. Role: source. Parse: module.

- l10n @12-17; ArrowFunctionExpression; parameters=0; async=false; generator=false
- themeIdPrefix @82-84; FunctionDeclaration; parameters=1; async=false; generator=false
- hasThemeIdBundledLocalization @94-96; FunctionDeclaration; parameters=1; async=false; generator=false
- getL10nIdForThemeProp @106-119; FunctionDeclaration; parameters=2; async=false; generator=false
- getL10nThemeString @125-143; FunctionDeclaration; parameters=2; async=false; generator=false
- Module resource://gre/modules/AppConstants.sys.mjs @5; ImportDeclaration
- Module resource://gre/modules/XPCOMUtils.sys.mjs @6; ImportDeclaration

### toolkit/mozapps/extensions/internal/XPIDatabase.sys.mjs

Blob: `1e15dba8105182e776da2ee360065ddb94df8dc0`. Role: source. Parse: module.

- promiseIdleSlice @175-179; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @176-178; ArrowFunctionExpression; parameters=1; async=false; generator=false
- idleForEach @197-205; FunctionDeclaration; parameters=3; async=true; generator=false
- getRepositoryAddon @215-222; FunctionDeclaration; parameters=1; async=true; generator=false
- copyProperties @237-247; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @241-245; FunctionExpression; parameters=1; async=false; generator=false
- addonFor @251-251; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @260-309; FunctionExpression; parameters=1; async=false; generator=false
- sourceBundle @311-313; FunctionExpression; parameters=0; async=false; generator=false
- sourceBundle @315-323; FunctionExpression; parameters=1; async=false; generator=false
- wrapper @325-330; FunctionExpression; parameters=0; async=false; generator=false
- resolvedRootURI @332-336; FunctionExpression; parameters=0; async=false; generator=false
- validInstallOrigins @349-377; FunctionExpression; parameters=1; async=false; generator=false
- addedToDatabase @379-382; FunctionExpression; parameters=0; async=false; generator=false
- isWebExtension @384-386; FunctionExpression; parameters=0; async=false; generator=false
- selectedLocale @388-437; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @399-399; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @431-432; ArrowFunctionExpression; parameters=1; async=false; generator=false
- providesUpdatesSecurely @439-441; FunctionExpression; parameters=0; async=false; generator=false
- isCorrectlySigned @443-477; FunctionExpression; parameters=0; async=false; generator=false
- isCompatible @479-481; FunctionExpression; parameters=0; async=false; generator=false
- isPrivileged @483-489; FunctionExpression; parameters=0; async=false; generator=false
- hidden @491-499; FunctionExpression; parameters=0; async=false; generator=false
- hidden @501-503; FunctionExpression; parameters=1; async=false; generator=false
- disabled @505-512; FunctionExpression; parameters=0; async=false; generator=false
- isPlatformCompatible @514-558; FunctionExpression; parameters=0; async=false; generator=false
- isCompatibleWith @560-598; FunctionExpression; parameters=2; async=false; generator=false
- matchingTargetApplication @600-611; FunctionExpression; parameters=0; async=false; generator=false
- updateBlocklistAttentionDismissed @613-620; FunctionExpression; parameters=1; async=false; generator=false
- findBlocklistEntry @622-624; FunctionExpression; parameters=0; async=true; generator=false
- updateBlocklistState @626-691; FunctionExpression; parameters=1; async=true; generator=false
- recordAddonBlockChangeTelemetry @693-695; FunctionExpression; parameters=1; async=false; generator=false
- setUserDisabled @697-725; FunctionExpression; parameters=2; async=true; generator=false
- applyCompatibilityUpdate @727-755; FunctionExpression; parameters=2; async=false; generator=false
- toJSON @757-761; FunctionExpression; parameters=0; async=false; generator=false
- importMetadata @771-782; FunctionExpression; parameters=1; async=false; generator=false
- permissions @784-868; FunctionExpression; parameters=0; async=false; generator=false
- propagateDisabledState @870-877; FunctionExpression; parameters=1; async=false; generator=false
- constructor @891-893; FunctionExpression; parameters=1; async=false; generator=false
- __AddonInternal__ @895-897; FunctionExpression; parameters=0; async=false; generator=false
- quarantineIgnoredByApp @899-901; FunctionExpression; parameters=0; async=false; generator=false
- quarantineIgnoredByUser @903-909; FunctionExpression; parameters=0; async=false; generator=false
- quarantineIgnoredByUser @911-913; FunctionExpression; parameters=1; async=false; generator=false
- canChangeQuarantineIgnored @915-924; FunctionExpression; parameters=0; async=false; generator=false
- previousActiveThemeID @926-931; FunctionExpression; parameters=0; async=false; generator=false
- seen @933-935; FunctionExpression; parameters=0; async=false; generator=false
- markAsSeen @937-940; FunctionExpression; parameters=0; async=false; generator=false
- installTelemetryInfo @942-955; FunctionExpression; parameters=0; async=false; generator=false
- temporarilyInstalled @957-959; FunctionExpression; parameters=0; async=false; generator=false
- aboutURL @961-963; FunctionExpression; parameters=0; async=false; generator=false
- optionsURL @965-988; FunctionExpression; parameters=0; async=false; generator=false
- optionsType @990-1008; FunctionExpression; parameters=0; async=false; generator=false
- optionsBrowserStyle @1010-1013; FunctionExpression; parameters=0; async=false; generator=false
- incognito @1015-1017; FunctionExpression; parameters=0; async=false; generator=false
- getBlocklistURL @1019-1021; FunctionExpression; parameters=0; async=true; generator=false
- iconURL @1023-1025; FunctionExpression; parameters=0; async=false; generator=false
- icons @1027-1052; FunctionExpression; parameters=0; async=false; generator=false
- screenshots @1054-1070; FunctionExpression; parameters=0; async=false; generator=false
- recommendationStates @1072-1085; FunctionExpression; parameters=0; async=false; generator=false
- isRecommended @1091-1093; FunctionExpression; parameters=0; async=false; generator=false
- canBypassThirdParyInstallPrompt @1095-1104; FunctionExpression; parameters=0; async=false; generator=false
- isApplyBackgroundUpdatesControlledByPolicies @1106-1110; FunctionExpression; parameters=0; async=false; generator=false
- applyBackgroundUpdates @1112-1122; FunctionExpression; parameters=0; async=false; generator=false
- applyBackgroundUpdates @1123-1148; FunctionExpression; parameters=1; async=false; generator=false
- syncGUID @1150-1161; FunctionExpression; parameters=1; async=false; generator=false
- install @1163-1169; FunctionExpression; parameters=0; async=false; generator=false
- updateInstall @1171-1174; FunctionExpression; parameters=0; async=false; generator=false
- pendingUpgrade @1176-1179; FunctionExpression; parameters=0; async=false; generator=false
- scope @1181-1188; FunctionExpression; parameters=0; async=false; generator=false
- locationName @1190-1193; FunctionExpression; parameters=0; async=false; generator=false
- pendingOperations @1195-1227; FunctionExpression; parameters=0; async=false; generator=false
- operationsRequiringRestart @1229-1231; FunctionExpression; parameters=0; async=false; generator=false
- isDebuggable @1233-1235; FunctionExpression; parameters=0; async=false; generator=false
- permissions @1237-1239; FunctionExpression; parameters=0; async=false; generator=false
- isActive @1241-1250; FunctionExpression; parameters=0; async=false; generator=false
- startupPromise @1252-1263; FunctionExpression; parameters=0; async=false; generator=false
- blocklistAttentionDismissed @1265-1268; FunctionExpression; parameters=0; async=false; generator=false
- blocklistAttentionDismissed @1270-1273; FunctionExpression; parameters=1; async=false; generator=false
- updateBlocklistState @1275-1277; FunctionExpression; parameters=1; async=false; generator=false
- userDisabled @1279-1282; FunctionExpression; parameters=0; async=false; generator=false
- embedderDisabled @1292-1298; FunctionExpression; parameters=0; async=false; generator=false
- setEmbedderDisabled @1314-1333; FunctionExpression; parameters=1; async=true; generator=false
- enable @1335-1338; FunctionExpression; parameters=1; async=false; generator=false
- disable @1340-1343; FunctionExpression; parameters=1; async=false; generator=false
- setSoftDisabled @1345-1370; FunctionExpression; parameters=1; async=true; generator=false
- isPrivileged @1372-1374; FunctionExpression; parameters=0; async=false; generator=false
- hidden @1376-1378; FunctionExpression; parameters=0; async=false; generator=false
- isSystem @1380-1383; FunctionExpression; parameters=0; async=false; generator=false
- isBuiltin @1385-1387; FunctionExpression; parameters=0; async=false; generator=false
- isSyncable @1391-1394; FunctionExpression; parameters=0; async=false; generator=false
- userPermissions @1400-1402; FunctionExpression; parameters=0; async=false; generator=false
- optionalPermissions @1404-1406; FunctionExpression; parameters=0; async=false; generator=false
- requestedPermissions @1412-1414; FunctionExpression; parameters=0; async=false; generator=false
- installPermissions @1419-1438; FunctionExpression; parameters=0; async=false; generator=false
- optionalOriginsNormalized @1440-1461; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1451-1451; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1452-1455; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasDataCollectionPermissions @1463-1468; FunctionExpression; parameters=0; async=false; generator=false
- isCompatibleWith @1470-1472; FunctionExpression; parameters=2; async=false; generator=false
- uninstall @1474-1477; FunctionExpression; parameters=1; async=true; generator=false
- cancelUninstall @1479-1482; FunctionExpression; parameters=0; async=false; generator=false
- findUpdates @1484-1492; FunctionExpression; parameters=4; async=false; generator=false
- cancelUpdate @1495-1502; FunctionExpression; parameters=0; async=false; generator=false
- reload @1511-1525; FunctionExpression; parameters=0; async=true; generator=false
- getResourceURI @1538-1548; FunctionExpression; parameters=1; async=false; generator=false
- chooseValue @1551-1564; FunctionDeclaration; parameters=3; async=false; generator=false
- defineAddonWrapperProperty @1566-1571; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1596-1601; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1597-1600; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1612-1621; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1613-1620; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1623-1629; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1624-1628; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1631-1638; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1640-1662; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1641-1661; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1664-1713; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1665-1712; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1715-1733; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1716-1732; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1726-1728; FunctionExpression; parameters=1; async=false; generator=false
- _findAddon @1750-1757; FunctionDeclaration; parameters=2; async=false; generator=false
- _filterDB @1770-1772; FunctionDeclaration; parameters=2; async=false; generator=false
- lastError @1801-1809; FunctionExpression; parameters=0; async=false; generator=false
- _saveNow @1811-1841; FunctionExpression; parameters=0; async=true; generator=false
- saveChanges @1846-1868; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1862-1862; ArrowFunctionExpression; parameters=0; async=false; generator=false
- finalize @1870-1877; FunctionExpression; parameters=0; async=true; generator=false
- toJSON @1885-1898; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1894-1894; ArrowFunctionExpression; parameters=1; async=false; generator=false
- syncLoadDB @1910-1922; FunctionExpression; parameters=1; async=false; generator=false
- _recordStartupError @1924-1927; FunctionExpression; parameters=1; async=false; generator=false
- parseDB @1937-2028; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1975-2004; ArrowFunctionExpression; parameters=1; async=false; generator=false
- maybeIdleDispatch @2030-2034; FunctionExpression; parameters=0; async=true; generator=false
- asyncLoadDB @2049-2102; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2072-2097; ArrowFunctionExpression; parameters=0; async=true; generator=false
- timeRebuildDatabase @2104-2113; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2105-2112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- rebuildDatabase @2123-2148; FunctionExpression; parameters=1; async=false; generator=false
- shutdown @2156-2189; FunctionExpression; parameters=0; async=true; generator=false
- verifySignatures @2194-2275; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2196-2196; ArrowFunctionExpression; parameters=0; async=false; generator=false
- importPermissions @2281-2286; FunctionExpression; parameters=0; async=false; generator=false
- addonChanged @2297-2336; FunctionExpression; parameters=2; async=true; generator=false
- getAddonList @2351-2363; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @2356-2356; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddon @2373-2379; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2375-2375; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2376-2378; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddonInLocation @2391-2395; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2392-2393; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddonsInLocation @2404-2406; FunctionExpression; parameters=1; async=false; generator=false
- getAddonsInLocations @2415-2419; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2416-2417; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getVisibleAddonForID @2428-2430; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2429-2429; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getVisibleAddons @2439-2443; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2441-2441; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddonsByType @2452-2466; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2465-2465; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getVisibleAddonsWithPendingOperations @2475-2482; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2477-2480; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shouldShowBlocklistAttention @2484-2486; FunctionExpression; parameters=0; async=false; generator=false
- shouldShowBlocklistAttentionForAddon @2488-2498; FunctionExpression; parameters=1; async=false; generator=false
- clearBlocklistAttentionAddonIdsSet @2500-2502; FunctionExpression; parameters=0; async=false; generator=false
- maybeUpdateBlocklistAttentionAddonIdsSet @2504-2520; FunctionExpression; parameters=1; async=false; generator=false
- removeFromBlocklistAttentionAddonIdsSet @2522-2528; FunctionExpression; parameters=1; async=false; generator=false
- getBlocklistAttentionInfo @2530-2571; FunctionExpression; parameters=0; async=true; generator=false
- addonFilter @2532-2534; ArrowFunctionExpression; parameters=1; async=false; generator=false
- shouldShow @2545-2547; FunctionExpression; parameters=0; async=false; generator=false
- hasSoftBlocked @2548-2554; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2550-2552; ArrowFunctionExpression; parameters=1; async=false; generator=false
- hasHardBlocked @2555-2560; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2557-2558; ArrowFunctionExpression; parameters=1; async=false; generator=false
- extensionsCount @2561-2563; FunctionExpression; parameters=0; async=false; generator=false
- addons @2564-2566; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2565-2565; ArrowFunctionExpression; parameters=1; async=false; generator=false
- dismiss @2567-2569; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2568-2568; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddons @2581-2586; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2585-2585; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAddonByID @2595-2598; FunctionExpression; parameters=1; async=true; generator=false
- getAddonBySyncGUID @2607-2610; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @2608-2608; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getAddonsByTypes @2619-2622; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @2621-2621; ArrowFunctionExpression; parameters=1; async=false; generator=false
- mustSign @2631-2641; FunctionExpression; parameters=1; async=false; generator=false
- isDisabledLegacy @2650-2663; FunctionExpression; parameters=1; async=false; generator=false
- isUsableAddon @2673-2775; FunctionExpression; parameters=1; async=false; generator=false
- isActive @2727-2730; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2732-2732; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addToDatabase @2787-2797; FunctionExpression; parameters=2; async=false; generator=false
- updateAddonMetadata @2812-2824; FunctionExpression; parameters=3; async=false; generator=false
- removeAddonMetadata @2832-2836; FunctionExpression; parameters=1; async=false; generator=false
- updateXPIStates @2838-2844; FunctionExpression; parameters=1; async=false; generator=false
- makeAddonVisible @2853-2867; FunctionExpression; parameters=1; async=false; generator=false
- makeAddonLocationVisible @2880-2902; FunctionExpression; parameters=2; async=false; generator=false
- setAddonProperties @2912-2917; FunctionExpression; parameters=2; async=false; generator=false
- setAddonSyncGUID @2929-2947; FunctionExpression; parameters=2; async=false; generator=false
- excludeSyncGUID @2931-2933; FunctionDeclaration; parameters=1; async=false; generator=false
- updateAddonActive @2957-2964; FunctionExpression; parameters=2; async=false; generator=false
- updateActiveAddons @2969-2981; FunctionExpression; parameters=0; async=false; generator=false
- updateAddonDisabledState @3010-3141; FunctionExpression; parameters=2; async=true; generator=false
- updateAddonAppDisabledStates @3146-3150; FunctionExpression; parameters=0; async=false; generator=false
- updateAddonRepositoryData @3155-3173; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @3162-3170; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3163-3170; ArrowFunctionExpression; parameters=1; async=false; generator=false
- recordAddonTelemetry @3181-3187; FunctionExpression; parameters=1; async=false; generator=false
- flattenByID @3205-3225; FunctionExpression; parameters=2; async=false; generator=false
- getVisibleAddons @3234-3256; FunctionExpression; parameters=1; async=false; generator=false
- addMetadata @3278-3395; FunctionExpression; parameters=4; async=false; generator=false
- removeMetadata @3404-3410; FunctionExpression; parameters=1; async=false; generator=false
- updateMetadata @3428-3478; FunctionExpression; parameters=4; async=false; generator=false
- updatePath @3493-3503; FunctionExpression; parameters=3; async=false; generator=false
- updateCompatibility @3522-3612; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @3605-3605; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isAppBundledLocation @3624-3630; FunctionExpression; parameters=1; async=false; generator=false
- isSystemAddonLocation @3640-3645; FunctionExpression; parameters=1; async=false; generator=false
- updateExistingAddon @3667-3720; FunctionExpression; parameters=5; async=false; generator=false
- processFileChanges @3747-3954; FunctionExpression; parameters=5; async=false; generator=false
- findManifest @3754-3756; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @3758-3758; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3759-3759; ArrowFunctionExpression; parameters=0; async=false; generator=false
- hideAddonCb @3847-3849; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @3877-3877; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3921-3949; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @3930-3945; ArrowFunctionExpression; parameters=1; async=true; generator=false
- applyStartupChange @3969-4040; FunctionExpression; parameters=3; async=false; generator=false
- Class AddonWrapper @890-1549
- Class AddonInternal @259-878
- Module resource://gre/modules/XPCOMUtils.sys.mjs @13; ImportDeclaration
- Module resource://gre/modules/addons/XPIExports.sys.mjs @15; ImportDeclaration
- Module resource://gre/modules/Log.sys.mjs @54; ImportDeclaration

### toolkit/mozapps/extensions/internal/XPIExports.sys.mjs

Blob: `63aac4a150d81ca7339e37216c3bd2706a996e9c`. Role: source. Parse: module.


### toolkit/mozapps/extensions/internal/XPIInstall.sys.mjs

Blob: `5585794fc03a1a676271dda7fa2242a1de0d37d2`. Role: source. Parse: module.

- (anonymous) @44-48; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @105-114; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getFile @126-143; FunctionDeclaration; parameters=2; async=false; generator=false
- flushJarCache @151-156; FunctionDeclaration; parameters=1; async=false; generator=false
- getJarURI @193-201; FunctionDeclaration; parameters=2; async=false; generator=false
- get @206-211; FunctionExpression; parameters=1; async=false; generator=false
- constructor @213-217; FunctionExpression; parameters=2; async=false; generator=false
- close @219-219; FunctionExpression; parameters=0; async=false; generator=false
- readString @221-224; FunctionExpression; parameters=1; async=true; generator=false
- verifySignedState @226-251; FunctionExpression; parameters=3; async=true; generator=false
- flushCache @253-253; FunctionExpression; parameters=0; async=false; generator=false
- constructor @257-259; FunctionExpression; parameters=1; async=false; generator=false
- hasResource @261-263; FunctionExpression; parameters=1; async=false; generator=false
- iterDirectory @265-277; FunctionExpression; parameters=2; async=true; generator=false
- iterFiles @279-295; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @280-294; ArrowFunctionExpression; parameters=1; async=true; generator=false
- readBinary @297-299; FunctionExpression; parameters=1; async=false; generator=false
- verifySignedStateForRoot @301-303; FunctionExpression; parameters=0; async=true; generator=false
- constructor @307-311; FunctionExpression; parameters=1; async=false; generator=false
- close @313-317; FunctionExpression; parameters=0; async=false; generator=false
- hasResource @319-321; FunctionExpression; parameters=1; async=true; generator=false
- iterFiles @323-331; FunctionExpression; parameters=1; async=true; generator=false
- readBinary @333-336; FunctionExpression; parameters=1; async=true; generator=false
- verifySignedStateForRoot @338-369; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @339-368; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openSignedAppFileFinished @341-361; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @358-358; ArrowFunctionExpression; parameters=1; async=false; generator=false
- flushCache @371-373; FunctionExpression; parameters=0; async=false; generator=false
- builtinPackage @384-404; FunctionDeclaration; parameters=1; async=false; generator=false
- verifySignedState @389-394; FunctionExpression; parameters=0; async=false; generator=false
- hasResource @395-402; FunctionExpression; parameters=1; async=true; generator=false
- newVersionReason @416-420; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForAllPromises @424-439; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @425-438; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @429-433; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @430-433; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @435-436; ArrowFunctionExpression; parameters=1; async=false; generator=false
- loadManifestFromWebManifest @453-610; FunctionDeclaration; parameters=2; async=true; generator=false
- checkPrivileged @459-470; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @495-495; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getLocale @549-586; FunctionDeclaration; parameters=1; async=false; generator=false
- readRecommendationStates @612-651; FunctionDeclaration; parameters=2; async=true; generator=false
- defineSyncGUID @653-667; FunctionDeclaration; parameters=1; async=false; generator=false
- get @656-659; ArrowFunctionExpression; parameters=0; async=false; generator=false
- set @660-663; ArrowFunctionExpression; parameters=1; async=false; generator=false
- generateTemporaryInstallID @670-682; FunctionDeclaration; parameters=1; async=false; generator=false
- loadManifest @684-763; FunctionExpression; parameters=3; async=true; generator=false
- loadManifestFromFile @780-788; FunctionExpression; parameters=3; async=true; generator=false
- syncLoadManifest @794-818; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @805-816; ArrowFunctionExpression; parameters=0; async=true; generator=false
- getTemporaryFile @828-834; FunctionDeclaration; parameters=0; async=false; generator=false
- getHashForFile @836-845; FunctionDeclaration; parameters=2; async=false; generator=false
- getSignedStatus @864-902; FunctionDeclaration; parameters=3; async=false; generator=false
- shouldVerifySignedState @904-921; FunctionDeclaration; parameters=2; async=false; generator=false
- verifyBundleSignedState @937-957; FunctionExpression; parameters=2; async=true; generator=false
- escapeAddonURI @975-1003; FunctionDeclaration; parameters=4; async=false; generator=false
- addonMap @1013-1015; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1014-1014; ArrowFunctionExpression; parameters=1; async=false; generator=false
- removeAsync @1017-1019; FunctionDeclaration; parameters=1; async=true; generator=false
- recursiveRemove @1027-1071; FunctionDeclaration; parameters=1; async=false; generator=false
- setFilePermissions @1081-1093; FunctionDeclaration; parameters=2; async=false; generator=false
- writeStringToFile @1103-1120; FunctionDeclaration; parameters=2; async=false; generator=false
- SafeInstallOperation @1132-1134; FunctionDeclaration; parameters=0; async=false; generator=false
- _installFile @1139-1166; FunctionExpression; parameters=3; async=false; generator=false
- moveUnder @1178-1185; FunctionExpression; parameters=2; async=false; generator=false
- moveTo @1196-1206; FunctionExpression; parameters=2; async=false; generator=false
- copy @1218-1225; FunctionExpression; parameters=2; async=false; generator=false
- rollback @1232-1250; FunctionExpression; parameters=0; async=false; generator=false
- constructor @1300-1371; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @1315-1315; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1320-1322; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1325-1325; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _cleanup @1377-1393; FunctionExpression; parameters=0; async=false; generator=false
- install @1405-1428; FunctionExpression; parameters=0; async=false; generator=false
- continuePostponedInstall @1430-1439; FunctionExpression; parameters=0; async=false; generator=false
- onShutdown @1445-1451; FunctionExpression; parameters=0; async=false; generator=false
- cancel @1461-1505; FunctionExpression; parameters=0; async=false; generator=false
- addListener @1514-1522; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1516-1518; FunctionExpression; parameters=1; async=false; generator=false
- removeListener @1530-1534; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1531-1533; FunctionExpression; parameters=1; async=false; generator=false
- removeTemporaryFile @1539-1563; FunctionExpression; parameters=0; async=false; generator=false
- _setFileHash @1565-1575; FunctionExpression; parameters=1; async=false; generator=false
- updatePersistedMetadata @1580-1590; FunctionExpression; parameters=0; async=false; generator=false
- loadManifest @1600-1799; FunctionExpression; parameters=1; async=true; generator=false
- getIcon @1801-1815; FunctionExpression; parameters=1; async=false; generator=false
- checkPrompt @1824-1867; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1825-1866; ArrowFunctionExpression; parameters=0; async=true; generator=false
- checkForBlockers @1875-1891; FunctionExpression; parameters=0; async=false; generator=false
- resumeFn @1882-1884; ArrowFunctionExpression; parameters=0; async=false; generator=false
- startInstall @1896-2082; FunctionExpression; parameters=0; async=true; generator=false
- install @1970-2038; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2040-2058; ArrowFunctionExpression; parameters=0; async=true; generator=false
- stageInstall @2097-2136; FunctionExpression; parameters=3; async=true; generator=false
- unstageInstall @2144-2154; FunctionExpression; parameters=1; async=true; generator=false
- backupStagedInstall @2162-2184; FunctionExpression; parameters=0; async=false; generator=false
- restoreStagedInstall @2193-2205; FunctionExpression; parameters=0; async=false; generator=false
- deleteBackupStagedInstall @2214-2223; FunctionExpression; parameters=0; async=false; generator=false
- postpone @2233-2284; FunctionExpression; parameters=2; async=true; generator=false
- install @2264-2277; ArrowFunctionExpression; parameters=0; async=false; generator=false
- _callInstallListeners @2286-2309; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2293-2293; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2299-2299; ArrowFunctionExpression; parameters=0; async=false; generator=false
- init @2316-2433; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2405-2429; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onUpdateFinished @2409-2425; ArrowFunctionExpression; parameters=2; async=false; generator=false
- install @2435-2446; FunctionExpression; parameters=0; async=false; generator=false
- constructor @2488-2507; FunctionExpression; parameters=3; async=false; generator=false
- install @2509-2530; FunctionExpression; parameters=0; async=false; generator=false
- cancel @2532-2542; FunctionExpression; parameters=0; async=false; generator=false
- observe @2544-2549; FunctionExpression; parameters=3; async=false; generator=false
- startDownload @2554-2583; FunctionExpression; parameters=0; async=false; generator=false
- openChannel @2585-2649; FunctionExpression; parameters=0; async=false; generator=false
- onDataAvailable @2656-2662; FunctionExpression; parameters=4; async=false; generator=false
- asyncOnChannelRedirect @2670-2700; FunctionExpression; parameters=4; async=false; generator=false
- onStartRequest @2707-2744; FunctionExpression; parameters=1; async=false; generator=false
- onStopRequest @2751-2840; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @2809-2823; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onUpdateFinished @2818-2818; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2824-2827; ArrowFunctionExpression; parameters=1; async=false; generator=false
- downloadFailed @2850-2872; FunctionExpression; parameters=2; async=false; generator=false
- downloadCompleted @2877-2930; FunctionExpression; parameters=0; async=true; generator=false
- getInterface @2932-2954; FunctionExpression; parameters=1; async=false; generator=false
- createUpdate @2969-3003; FunctionDeclaration; parameters=4; async=false; generator=false
- (anonymous) @2972-3002; FunctionExpression; parameters=0; async=true; generator=false
- installFor @3007-3007; ArrowFunctionExpression; parameters=1; async=false; generator=false
- AddonInstallWrapper @3019-3022; FunctionDeclaration; parameters=1; async=false; generator=false
- __AddonInstallInternal__ @3025-3027; FunctionExpression; parameters=0; async=false; generator=false
- error @3029-3031; FunctionExpression; parameters=0; async=false; generator=false
- error @3033-3035; FunctionExpression; parameters=1; async=false; generator=false
- type @3037-3039; FunctionExpression; parameters=0; async=false; generator=false
- iconURL @3041-3043; FunctionExpression; parameters=0; async=false; generator=false
- existingAddon @3045-3048; FunctionExpression; parameters=0; async=false; generator=false
- addon @3050-3053; FunctionExpression; parameters=0; async=false; generator=false
- addonHasPreviousConsent @3055-3057; FunctionExpression; parameters=0; async=false; generator=false
- sourceURI @3059-3061; FunctionExpression; parameters=0; async=false; generator=false
- promptHandler @3063-3065; FunctionExpression; parameters=1; async=false; generator=false
- promptHandler @3067-3069; FunctionExpression; parameters=0; async=false; generator=false
- installTelemetryInfo @3071-3073; FunctionExpression; parameters=0; async=false; generator=false
- isUserRequestedUpdate @3075-3077; FunctionExpression; parameters=0; async=false; generator=false
- downloadStartedAt @3079-3081; FunctionExpression; parameters=0; async=false; generator=false
- hashedAddonId @3083-3091; FunctionExpression; parameters=0; async=false; generator=false
- install @3093-3095; FunctionExpression; parameters=0; async=false; generator=false
- postpone @3097-3099; FunctionExpression; parameters=2; async=false; generator=false
- cancel @3101-3103; FunctionExpression; parameters=0; async=false; generator=false
- continuePostponedInstall @3105-3107; FunctionExpression; parameters=0; async=false; generator=false
- addListener @3109-3111; FunctionExpression; parameters=1; async=false; generator=false
- removeListener @3113-3115; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3127-3134; FunctionExpression; parameters=1; async=false; generator=false
- get @3129-3131; FunctionExpression; parameters=0; async=false; generator=false
- UpdateChecker @3153-3216; FunctionExpression; parameters=5; async=false; generator=false
- callListener @3234-3244; FunctionExpression; parameters=2; async=false; generator=false
- onUpdateCheckComplete @3252-3372; FunctionExpression; parameters=1; async=true; generator=false
- sendUpdateAvailableMessages @3313-3328; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @3362-3364; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onUpdateCheckError @3380-3386; FunctionExpression; parameters=1; async=false; generator=false
- cancel @3391-3398; FunctionExpression; parameters=0; async=false; generator=false
- createLocalInstall @3414-3429; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @3424-3424; ArrowFunctionExpression; parameters=0; async=false; generator=false
- uninstallAddonFromLocation @3441-3460; FunctionDeclaration; parameters=2; async=true; generator=false
- constructor @3463-3468; FunctionExpression; parameters=1; async=false; generator=false
- name @3470-3472; FunctionExpression; parameters=0; async=false; generator=false
- dir @3474-3476; FunctionExpression; parameters=0; async=false; generator=false
- dir @3477-3480; FunctionExpression; parameters=1; async=false; generator=false
- getStagingDir @3488-3490; FunctionExpression; parameters=0; async=false; generator=false
- requestStagingDir @3492-3510; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3506-3509; ArrowFunctionExpression; parameters=1; async=false; generator=false
- releaseStagingDir @3512-3521; FunctionExpression; parameters=0; async=false; generator=false
- cleanStagingDir @3531-3561; FunctionExpression; parameters=1; async=false; generator=false
- getTrashDir @3571-3590; FunctionExpression; parameters=0; async=false; generator=false
- installAddon @3613-3676; FunctionExpression; parameters=1; async=false; generator=false
- moveOldAddon @3618-3631; ArrowFunctionExpression; parameters=1; async=false; generator=false
- uninstallAddon @3685-3734; FunctionExpression; parameters=1; async=false; generator=false
- constructor @3738-3743; FunctionExpression; parameters=1; async=false; generator=false
- _addonSet @3745-3747; FunctionExpression; parameters=0; async=false; generator=false
- _addonSet @3748-3750; FunctionExpression; parameters=1; async=false; generator=false
- _saveAddonSet @3758-3763; FunctionExpression; parameters=1; async=false; generator=false
- _loadAddonSet @3765-3767; FunctionExpression; parameters=0; async=false; generator=false
- getStagingDir @3776-3787; FunctionExpression; parameters=0; async=false; generator=false
- requestStagingDir @3789-3795; FunctionExpression; parameters=0; async=false; generator=false
- isValidAddon @3797-3806; FunctionExpression; parameters=1; async=false; generator=false
- getInvalidAddonIds @3819-3845; FunctionExpression; parameters=1; async=false; generator=false
- updateAddonSetOnAppVersionChanged @3847-3887; FunctionExpression; parameters=1; async=true; generator=false
- systemUpdateIsBuiltInUpgrade @3864-3870; ArrowFunctionExpression; parameters=2; async=false; generator=false
- resetAddonSet @3892-3914; FunctionExpression; parameters=0; async=true; generator=false
- cleanDirectories @3921-3945; FunctionExpression; parameters=0; async=true; generator=false
- installAddonSet @3953-4071; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3960-3960; ArrowFunctionExpression; parameters=1; async=false; generator=false
- installAddon @4006-4010; FunctionDeclaration; parameters=1; async=true; generator=false
- postponeAddon @4012-4027; FunctionDeclaration; parameters=1; async=true; generator=false
- resumeFn @4019-4024; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @4043-4044; ArrowFunctionExpression; parameters=1; async=false; generator=false
- resumeAddonSet @4079-4097; FunctionExpression; parameters=1; async=true; generator=false
- resumeAddon @4080-4084; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @4086-4087; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getTrashDir @4107-4126; FunctionExpression; parameters=0; async=false; generator=false
- installAddon @4138-4170; FunctionExpression; parameters=1; async=false; generator=false
- uninstallAddon @4173-4173; FunctionExpression; parameters=0; async=false; generator=false
- findAddonUpdates @4177-4199; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @4178-4198; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onUpdateAvailable @4182-4184; FunctionExpression; parameters=2; async=false; generator=false
- onUpdateFinished @4186-4192; FunctionExpression; parameters=2; async=false; generator=false
- _ensurePersistentStagedLangpack @4204-4241; FunctionExpression; parameters=0; async=false; generator=false
- restoreStagedIfNeeded @4216-4221; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallStarted @4223-4229; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallCancelled @4230-4232; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallFailed @4233-4235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallEnded @4236-4238; ArrowFunctionExpression; parameters=1; async=false; generator=false
- stageLangpackInstall @4243-4280; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4244-4279; ArrowFunctionExpression; parameters=2; async=false; generator=false
- onDownloadEnded @4246-4255; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallFailed @4256-4259; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallEnded @4260-4265; ArrowFunctionExpression; parameters=1; async=false; generator=false
- onInstallPostponed @4266-4274; ArrowFunctionExpression; parameters=1; async=false; generator=false
- stageLangpackUpdates @4282-4300; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @4293-4293; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4294-4296; ArrowFunctionExpression; parameters=1; async=false; generator=false
- stageLangpacksForAppUpdate @4315-4317; FunctionExpression; parameters=2; async=false; generator=false
- doing @4322-4324; FunctionExpression; parameters=1; async=false; generator=false
- done @4326-4333; FunctionExpression; parameters=1; async=false; generator=false
- cancelAll @4335-4345; FunctionExpression; parameters=0; async=false; generator=false
- installDistributionAddon @4357-4419; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @4413-4415; ArrowFunctionExpression; parameters=1; async=false; generator=false
- installStagedAddon @4434-4485; FunctionExpression; parameters=3; async=true; generator=false
- updateSystemAddons @4487-4650; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @4515-4515; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4525-4525; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setMatches @4528-4545; ArrowFunctionExpression; parameters=2; async=false; generator=false
- downloadAddon @4574-4607; FunctionDeclaration; parameters=1; async=true; generator=false
- validateAddon @4612-4632; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4636-4636; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4648-4648; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isInstallEnabled @4658-4661; FunctionExpression; parameters=0; async=false; generator=false
- isDirectRequestWhitelisted @4670-4673; FunctionExpression; parameters=0; async=false; generator=false
- isFileRequestWhitelisted @4682-4685; FunctionExpression; parameters=0; async=false; generator=false
- isWeakSignatureInstallAllowed @4687-4689; FunctionExpression; parameters=0; async=false; generator=false
- getWeakSignatureInstallPrefName @4691-4693; FunctionExpression; parameters=0; async=false; generator=false
- isInstallAllowed @4703-4754; FunctionExpression; parameters=1; async=false; generator=false
- getInstallForURL @4789-4811; FunctionExpression; parameters=2; async=true; generator=false
- getInstallForFile @4825-4841; FunctionExpression; parameters=3; async=true; generator=false
- getInstallsByTypes @4851-4860; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4854-4856; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @4859-4859; ArrowFunctionExpression; parameters=1; async=false; generator=false
- installTemporaryAddon @4875-4891; FunctionExpression; parameters=1; async=true; generator=false
- installBuiltinAddon @4903-4946; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @4938-4938; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _activateAddon @4962-5044; FunctionExpression; parameters=2; async=true; generator=false
- install @4985-5002; ArrowFunctionExpression; parameters=0; async=false; generator=false
- uninstallAddon @5059-5185; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @5127-5127; ArrowFunctionExpression; parameters=1; async=false; generator=false
- uninstall @5140-5161; ArrowFunctionExpression; parameters=0; async=false; generator=false
- cancelUninstallAddon @5193-5228; FunctionExpression; parameters=1; async=false; generator=false
- Class SystemAddonInstaller @3737-4174
- Class DirectoryInstaller @3462-3735
- Class (anonymous) @2449-2955
- Class (anonymous) @2312-2447
- Class AddonInstall @1260-2310
- Class XPIPackage @306-374
- Class DirPackage @256-304
- Class Package @205-254
- Module resource://gre/modules/XPCOMUtils.sys.mjs @16; ImportDeclaration
- Module resource://gre/modules/addons/XPIExports.sys.mjs @18; ImportDeclaration
- Module resource://gre/modules/addons/crypto-utils.sys.mjs @19; ImportDeclaration
- Module resource://gre/modules/AppConstants.sys.mjs @24; ImportDeclaration
- Module resource://gre/modules/AddonManager.sys.mjs @25; ImportDeclaration
- Module resource://gre/modules/ExtensionParent.sys.mjs @45; ChromeUtils-import-literal
- Module resource://gre/modules/Log.sys.mjs @180; ImportDeclaration
- Module resource://gre/modules/addons/AddonUpdateChecker.sys.mjs @3164; ChromeUtils-import-literal

### toolkit/mozapps/extensions/internal/XPIProvider.sys.mjs

Blob: `f448b259154df4966831efa7df1659346a5dab1c`. Role: source. Parse: module.

- get @162-165; FunctionExpression; parameters=0; async=false; generator=false
- encoded @168-179; FunctionDeclaration; parameters=2; async=false; generator=false
- awaitPromise @223-247; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @228-231; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @232-235; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @240-240; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getFile @259-276; FunctionDeclaration; parameters=2; async=false; generator=false
- isXPI @291-297; FunctionDeclaration; parameters=2; async=false; generator=false
- getExpectedID @308-315; FunctionDeclaration; parameters=1; async=false; generator=false
- canRunInSafeMode @325-338; FunctionDeclaration; parameters=1; async=false; generator=false
- getURIForResourceInFile @354-365; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @358-358; ArrowFunctionExpression; parameters=1; async=false; generator=false
- buildJarURI @377-381; FunctionDeclaration; parameters=2; async=false; generator=false
- maybeResolveURI @383-388; FunctionDeclaration; parameters=1; async=false; generator=false
- iterDirectory @398-415; FunctionDeclaration; parameters=1; async=false; generator=true
- migrateAddonLoader @425-462; FunctionDeclaration; parameters=1; async=false; generator=false
- constructor @488-533; FunctionExpression; parameters=4; async=false; generator=false
- mtime @536-538; FunctionExpression; parameters=0; async=false; generator=false
- active @539-541; FunctionExpression; parameters=0; async=false; generator=false
- path @547-549; FunctionExpression; parameters=0; async=false; generator=false
- path @550-552; FunctionExpression; parameters=1; async=false; generator=false
- relativePath @559-568; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @576-599; FunctionExpression; parameters=0; async=false; generator=false
- isWebExtension @601-603; FunctionExpression; parameters=0; async=false; generator=false
- isPrivileged @605-611; FunctionExpression; parameters=0; async=false; generator=false
- getModTime @621-637; FunctionExpression; parameters=1; async=false; generator=false
- getTelemetryKey @645-647; FunctionExpression; parameters=0; async=false; generator=false
- resolvedRootURI @649-651; FunctionExpression; parameters=0; async=false; generator=false
- syncWithDB @665-703; FunctionExpression; parameters=2; async=false; generator=false
- constructor @720-740; FunctionExpression; parameters=4; async=false; generator=false
- hasPrecedence @742-745; FunctionExpression; parameters=1; async=false; generator=false
- installer @747-752; FunctionExpression; parameters=0; async=false; generator=false
- makeInstaller @754-756; FunctionExpression; parameters=0; async=false; generator=false
- restore @758-794; FunctionExpression; parameters=1; async=false; generator=false
- toJSON @802-820; FunctionExpression; parameters=0; async=false; generator=false
- hasStaged @822-827; FunctionExpression; parameters=0; async=false; generator=false
- _addState @829-833; FunctionExpression; parameters=3; async=false; generator=false
- addAddon @841-853; FunctionExpression; parameters=1; async=false; generator=false
- removeAddon @861-866; FunctionExpression; parameters=1; async=false; generator=false
- addFile @877-884; FunctionExpression; parameters=2; async=false; generator=false
- stageAddon @898-901; FunctionExpression; parameters=2; async=false; generator=false
- unstageAddon @909-914; FunctionExpression; parameters=1; async=false; generator=false
- getStagedAddons @916-920; FunctionExpression; parameters=0; async=false; generator=true
- isLinkedAddon @930-935; FunctionExpression; parameters=1; async=false; generator=false
- isTemporary @937-939; FunctionExpression; parameters=0; async=false; generator=false
- isSystem @941-943; FunctionExpression; parameters=0; async=false; generator=false
- isBuiltin @945-947; FunctionExpression; parameters=0; async=false; generator=false
- hidden @949-951; FunctionExpression; parameters=0; async=false; generator=false
- enumerable @956-958; FunctionExpression; parameters=0; async=false; generator=false
- constructor @966-969; FunctionExpression; parameters=1; async=false; generator=false
- makeInstaller @971-978; FunctionExpression; parameters=0; async=false; generator=false
- installAddon @975-975; FunctionExpression; parameters=0; async=false; generator=false
- uninstallAddon @976-976; FunctionExpression; parameters=0; async=false; generator=false
- toJSON @980-982; FunctionExpression; parameters=0; async=false; generator=false
- isTemporary @984-986; FunctionExpression; parameters=0; async=false; generator=false
- enumerable @988-990; FunctionExpression; parameters=0; async=false; generator=false
- constructor @999-1002; FunctionExpression; parameters=0; async=false; generator=false
- makeInstaller @1007-1012; FunctionExpression; parameters=0; async=false; generator=false
- installAddon @1009-1009; FunctionExpression; parameters=0; async=false; generator=false
- uninstallAddon @1010-1010; FunctionExpression; parameters=0; async=false; generator=false
- hidden @1014-1016; FunctionExpression; parameters=0; async=false; generator=false
- isBuiltin @1018-1020; FunctionExpression; parameters=0; async=false; generator=false
- enumerable @1022-1024; FunctionExpression; parameters=0; async=false; generator=false
- isLinkedAddon @1028-1030; FunctionExpression; parameters=0; async=false; generator=false
- constructor @1038-1045; FunctionExpression; parameters=0; async=false; generator=false
- makeInstaller @1050-1055; FunctionExpression; parameters=0; async=false; generator=false
- installAddon @1052-1052; FunctionExpression; parameters=0; async=false; generator=false
- uninstallAddon @1053-1053; FunctionExpression; parameters=0; async=false; generator=false
- readAddons @1063-1078; FunctionExpression; parameters=0; async=false; generator=false
- hidden @1080-1082; FunctionExpression; parameters=0; async=false; generator=false
- isBuiltin @1084-1086; FunctionExpression; parameters=0; async=false; generator=false
- isSystem @1088-1090; FunctionExpression; parameters=0; async=false; generator=false
- enumerable @1092-1094; FunctionExpression; parameters=0; async=false; generator=false
- isLinkedAddon @1098-1100; FunctionExpression; parameters=0; async=false; generator=false
- constructor @1127-1131; FunctionExpression; parameters=5; async=false; generator=false
- makeInstaller @1133-1138; FunctionExpression; parameters=0; async=false; generator=false
- _readLinkFile @1150-1203; FunctionExpression; parameters=1; async=false; generator=false
- readAddons @1211-1252; FunctionExpression; parameters=0; async=false; generator=false
- isSystem @1254-1256; FunctionExpression; parameters=0; async=false; generator=false
- constructor @1277-1316; FunctionExpression; parameters=4; async=false; generator=false
- makeInstaller @1318-1323; FunctionExpression; parameters=0; async=false; generator=false
- _loadAddonSet @1330-1344; FunctionExpression; parameters=0; async=false; generator=false
- readAddons @1346-1362; FunctionExpression; parameters=0; async=false; generator=false
- isActive @1369-1371; FunctionExpression; parameters=0; async=false; generator=false
- isSystem @1373-1375; FunctionExpression; parameters=0; async=false; generator=false
- isBuiltin @1377-1379; FunctionExpression; parameters=0; async=false; generator=false
- constructor @1397-1402; FunctionExpression; parameters=3; async=false; generator=false
- _appKeyPath @1407-1417; FunctionExpression; parameters=0; async=false; generator=false
- readAddons @1426-1459; FunctionExpression; parameters=0; async=false; generator=false
- size @1479-1485; FunctionExpression; parameters=0; async=false; generator=false
- loadExtensionState @1492-1517; FunctionExpression; parameters=0; async=false; generator=false
- scanForChanges @1530-1742; FunctionExpression; parameters=1; async=false; generator=false
- getMissingIds @1579-1581; ArrowFunctionExpression; parameters=1; async=false; generator=false
- locations @1744-1746; FunctionExpression; parameters=0; async=false; generator=false
- addLocation @1754-1759; FunctionExpression; parameters=2; async=false; generator=false
- getLocation @1770-1772; FunctionExpression; parameters=1; async=false; generator=false
- getAddon @1786-1789; FunctionExpression; parameters=2; async=false; generator=false
- findAddon @1803-1815; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1803-1803; ArrowFunctionExpression; parameters=0; async=false; generator=false
- enabledAddons @1820-1828; FunctionExpression; parameters=0; async=false; generator=true
- addAddon @1836-1838; FunctionExpression; parameters=1; async=false; generator=false
- save @1843-1884; FunctionExpression; parameters=0; async=false; generator=false
- saveFailureHandler @1851-1877; FunctionExpression; parameters=1; async=false; generator=false
- toJSON @1886-1894; FunctionExpression; parameters=0; async=false; generator=false
- removeAddon @1904-1911; FunctionExpression; parameters=2; async=false; generator=false
- disableAddon @1919-1925; FunctionExpression; parameters=1; async=false; generator=false
- constructor @1937-1946; FunctionExpression; parameters=1; async=false; generator=false
- get @1957-1963; FunctionExpression; parameters=1; async=false; generator=false
- file @1965-1967; FunctionExpression; parameters=0; async=false; generator=false
- runInSafeMode @1969-1973; FunctionExpression; parameters=0; async=false; generator=false
- fetchState @1982-1987; FunctionExpression; parameters=0; async=false; generator=false
- callBootstrapMethod @2002-2104; FunctionExpression; parameters=3; async=true; generator=false
- _beforeCallBootstrapMethod @2107-2107; FunctionExpression; parameters=0; async=false; generator=false
- loadBootstrapScope @2117-2160; FunctionExpression; parameters=1; async=false; generator=false
- unloadBootstrapScope @2166-2173; FunctionExpression; parameters=0; async=false; generator=false
- startup @2187-2211; FunctionExpression; parameters=2; async=true; generator=false
- shutdown @2222-2226; FunctionExpression; parameters=2; async=true; generator=false
- _shutdown @2228-2231; FunctionExpression; parameters=2; async=true; generator=false
- disable @2242-2253; FunctionExpression; parameters=0; async=true; generator=false
- install @2270-2272; FunctionExpression; parameters=3; async=false; generator=false
- _install @2274-2286; FunctionExpression; parameters=4; async=true; generator=false
- uninstall @2302-2304; FunctionExpression; parameters=2; async=false; generator=false
- _uninstall @2306-2318; FunctionExpression; parameters=3; async=true; generator=false
- update @2341-2392; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @2396-2398; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2400-2402; ArrowFunctionExpression; parameters=1; async=false; generator=false
- name @2405-2407; FunctionExpression; parameters=0; async=false; generator=false
- registerProvider @2433-2435; FunctionExpression; parameters=0; async=false; generator=false
- isDBLoaded @2439-2447; FunctionExpression; parameters=0; async=false; generator=false
- addonIsActive @2457-2460; FunctionExpression; parameters=1; async=false; generator=false
- sortBootstrappedAddons @2473-2508; FunctionExpression; parameters=0; async=false; generator=false
- compare @2474-2479; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @2483-2483; ArrowFunctionExpression; parameters=2; async=false; generator=false
- add @2493-2503; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2507-2507; ArrowFunctionExpression; parameters=1; async=false; generator=false
- addTelemetry @2513-2518; FunctionExpression; parameters=2; async=false; generator=false
- setupInstallLocations @2520-2651; FunctionExpression; parameters=1; async=false; generator=false
- DirectoryLoc @2521-2528; FunctionDeclaration; parameters=6; async=false; generator=false
- SystemLoc @2530-2537; FunctionDeclaration; parameters=4; async=false; generator=false
- RegistryLoc @2539-2543; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @2548-2548; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2578-2578; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2583-2583; ArrowFunctionExpression; parameters=0; async=false; generator=false
- registerBuiltinDictionaries @2657-2668; FunctionExpression; parameters=0; async=false; generator=false
- unregisterDictionaries @2679-2697; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2695-2695; ArrowFunctionExpression; parameters=1; async=false; generator=false
- startup @2715-3016; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2874-2926; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2906-2906; ArrowFunctionExpression; parameters=1; async=false; generator=false
- fetchState @2927-2927; ArrowFunctionExpression; parameters=0; async=false; generator=false
- observer @2931-2936; FunctionExpression; parameters=0; async=false; generator=false
- observer @2965-2978; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @3007-3009; ArrowFunctionExpression; parameters=0; async=false; generator=false
- shutdown @3024-3052; FunctionExpression; parameters=0; async=true; generator=false
- cleanupTemporaryAddons @3054-3087; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3061-3061; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cleanup @3063-3066; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3070-3076; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addAddonsToCrashReporter @3092-3107; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3098-3098; ArrowFunctionExpression; parameters=1; async=false; generator=false
- processPendingFileChanges @3119-3181; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3143-3148; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3149-3157; ArrowFunctionExpression; parameters=1; async=false; generator=false
- installDistributionAddons @3197-3281; FunctionExpression; parameters=2; async=false; generator=false
- maybeInstallBuiltinAddon @3296-3310; FunctionExpression; parameters=3; async=true; generator=false
- getDependentAddons @3312-3316; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3313-3314; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkForChanges @3335-3430; FunctionExpression; parameters=3; async=false; generator=false
- getNewSideloads @3439-3455; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @3446-3446; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3450-3453; ArrowFunctionExpression; parameters=1; async=false; generator=false
- supportsMimetype @3466-3468; FunctionExpression; parameters=1; async=false; generator=false
- isTemporaryInstallID @3471-3473; FunctionExpression; parameters=1; async=false; generator=false
- setStartupData @3486-3490; FunctionExpression; parameters=2; async=false; generator=false
- persistStartupData @3499-3509; FunctionExpression; parameters=2; async=false; generator=false
- getAddonIDByInstanceID @3511-3526; FunctionExpression; parameters=1; async=false; generator=false
- getAddonsByTypes @3528-3533; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3529-3529; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getActiveAddons @3542-3570; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3547-3547; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getBuiltinAddonVersion @3572-3578; FunctionExpression; parameters=1; async=false; generator=false
- shouldShowBlocklistAttention @3580-3582; FunctionExpression; parameters=0; async=false; generator=false
- getBlocklistAttentionInfo @3584-3586; FunctionExpression; parameters=0; async=false; generator=false
- observe @3593-3623; FunctionExpression; parameters=3; async=false; generator=false
- uninstallSystemProfileAddon @3625-3628; FunctionExpression; parameters=1; async=false; generator=false
- _updateDatabase @3630-3641; FunctionExpression; parameters=1; async=true; generator=false
- XPIProvider.meth @3655-3657; FunctionExpression; parameters=0; async=false; generator=false
- XPIProvider.meth @3667-3669; FunctionExpression; parameters=0; async=false; generator=false
- overrideAsyncShutdown @3701-3703; FunctionExpression; parameters=1; async=false; generator=false
- Class BootstrapScope @1936-2393
- Class WinRegLocation @1388-1460
- Class SystemAddonLocation @1263-1380
- Class DirectoryLocation @1109-1257
- Class _SystemBuiltInLocation @1037-1101
- Class _BuiltInLocation @998-1031
- Class TemporaryLocation @961-991
- Class XPIStateLocation @719-959
- Class XPIState @487-704
- Module resource://gre/modules/XPCOMUtils.sys.mjs @16; ImportDeclaration
- Module resource://gre/modules/addons/XPIExports.sys.mjs @18; ImportDeclaration
- Module resource://gre/modules/AddonManager.sys.mjs @19; ImportDeclaration
- Module resource://gre/modules/AppConstants.sys.mjs @23; ImportDeclaration
- Module resource://gre/modules/Log.sys.mjs @206; ImportDeclaration

### toolkit/mozapps/extensions/internal/crypto-utils.sys.mjs

Blob: `9ef096df0f5213015c1d5d9abc160e33305a1b83`. Role: source. Parse: module.

- hasStrongSignature @13-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @15-15; ArrowFunctionExpression; parameters=1; async=false; generator=false
- computeHashAsString @19-24; FunctionDeclaration; parameters=2; async=false; generator=false
- computeSha256HashAsString @34-36; FunctionDeclaration; parameters=1; async=false; generator=false
- computeSha1HashAsString @46-48; FunctionDeclaration; parameters=1; async=false; generator=false
- getHashStringForCrypto @57-65; FunctionDeclaration; parameters=1; async=false; generator=false
- toHexString @59-59; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @63-63; ArrowFunctionExpression; parameters=1; async=false; generator=false

### toolkit/mozapps/extensions/internal/siteperms-addon-utils.sys.mjs

Blob: `8bc17c3808fbc1cea112cd80810ee33d4f4b6ba4`. Role: source. Parse: module.

- (anonymous) @60-60; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isGatedPermissionType @67-69; FunctionDeclaration; parameters=1; async=false; generator=false
- isKnownPublicSuffix @75-86; FunctionDeclaration; parameters=1; async=false; generator=false
- addGatedPermissionTypesForXpcShellTests @94-100; FunctionDeclaration; parameters=1; async=false; generator=false
- isPrincipalInSitePermissionsBlocklist @106-108; FunctionDeclaration; parameters=1; async=false; generator=false
- getSitePermsInstallPromptStringIds @116-118; FunctionDeclaration; parameters=1; async=false; generator=false
- getSitePermsPermissionsPromptStringIds @126-128; FunctionDeclaration; parameters=1; async=false; generator=false
- getSitePermsShortDescriptionStringId @137-139; FunctionDeclaration; parameters=1; async=false; generator=false
- Module resource://gre/modules/XPCOMUtils.sys.mjs @5; ImportDeclaration

### toolkit/mozapps/extensions/test/browser/.eslintrc.mjs

Blob: `55697c63e6b2b41584592dbe22c18763cc650d66`. Role: test-path,source. Parse: module.

- Module globals @5; ImportDeclaration

### toolkit/mozapps/extensions/test/browser/browser_AMBrowserExtensionsImport.js

Blob: `d4a2f13fa65542d5f13c0cff4180d5f538e69d16`. Role: test-path,source. Parse: module.

- mockAddonRepository @44-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getMappedAddons @46-52; FunctionExpression; parameters=0; async=true; generator=false
- assertWarningShown @60-97; ArrowFunctionExpression; parameters=3; async=true; generator=false
- setup @99-119; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @115-118; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_aboutaddons_global_message @121-232; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @212-216; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @215-215; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://gre/modules/AddonManager.sys.mjs @5; ChromeUtils-import-literal
- Module resource://testing-common/AddonTestUtils.sys.mjs @9; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_about_debugging_link.js

Blob: `f3dfd9d50be50dbde640f8a0632d007736ebe78f`. Role: test-path,source. Parse: module.

- waitForDispatch @13-23; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @14-22; ArrowFunctionExpression; parameters=1; async=false; generator=false
- predicate @17-17; ArrowFunctionExpression; parameters=1; async=false; generator=false
- run @18-20; ArrowFunctionExpression; parameters=3; async=false; generator=false
- waitForRequestsToSettle @29-60; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @40-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @42-45; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForRequestsSuccess @62-68; FunctionDeclaration; parameters=1; async=false; generator=false
- testAboutDebugging @70-126; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @97-97; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @112-112; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Module resource://testing-common/PromiseTestUtils.sys.mjs @6; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_addon_list_reordering.js

Blob: `d0f443ec19ee59c9665f85111eadb1259e01468a`. Role: test-path,source. Parse: module.

- assertInSection @12-20; FunctionDeclaration; parameters=3; async=false; generator=false
- waitForAnimationFrame @22-24; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @23-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- clickEnableToggle @26-40; FunctionDeclaration; parameters=1; async=true; generator=false
- mouseOver @42-47; FunctionDeclaration; parameters=1; async=false; generator=false
- mouseOutOfList @49-51; FunctionDeclaration; parameters=1; async=false; generator=false
- pressKey @53-56; FunctionDeclaration; parameters=2; async=false; generator=false
- waitForTransitionEnd @58-67; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @60-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-64; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-75; FunctionExpression; parameters=0; async=true; generator=false
- testReordering @77-206; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @85-92; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @95-95; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @205-205; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @6; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_amo_abuse_report.js

Blob: `c38ef4993fa1527b3fa0f52e61a85769247d5308`. Role: test-path,source. Parse: module.

- (anonymous) @8-20; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_opens_amo_form_in_a_tab @22-48; FunctionExpression; parameters=0; async=true; generator=false
- test_report_button_shown_on_dictionary_addons @50-57; FunctionExpression; parameters=0; async=true; generator=false
- test_report_action_hidden_on_langpack_addons @59-66; FunctionExpression; parameters=0; async=true; generator=false
- test_report_action_hidden_on_system_addons @68-75; FunctionExpression; parameters=0; async=true; generator=false
- test_report_action_hidden_on_builtin_addons @77-85; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_bug572561.js

Blob: `531998f8e5d0ba5c0510b9ca450528eeb9c80d77`. Role: test-path,source. Parse: module.

- onInstallStarted @19-22; FunctionExpression; parameters=0; async=true; generator=false
- onInstallEnded @24-28; FunctionExpression; parameters=0; async=true; generator=false
- onInstallCancelled @30-35; FunctionExpression; parameters=0; async=true; generator=false
- onInstallFailed @37-40; FunctionExpression; parameters=0; async=false; generator=false
- test @43-51; FunctionDeclaration; parameters=0; async=true; generator=false
- end_test @53-56; FunctionDeclaration; parameters=0; async=true; generator=false
- check_hidden @58-64; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @67-73; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @77-82; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @85-87; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @91-98; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_checkAddonCompatibility.js

Blob: `9cea5b50452e55ea3963efea5cad167e0181b117`. Role: test-path,source. Parse: module.

- test @7-36; FunctionDeclaration; parameters=0; async=true; generator=false
- compareTypeName @17-19; FunctionExpression; parameters=2; async=false; generator=false

### toolkit/mozapps/extensions/test/browser/browser_dragdrop.js

Blob: `b0301df5811e49e7f69eb497f1e46d3698a8578e`. Role: test-path,source. Parse: module.

- checkInstallConfirmation @16-71; FunctionDeclaration; parameters=1; async=true; generator=false
- observe @19-40; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-55; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getDragOverTarget @73-75; FunctionDeclaration; parameters=1; async=false; generator=false
- getDropTarget @77-79; FunctionDeclaration; parameters=1; async=false; generator=false
- withTestPage @81-90; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @84-88; ArrowFunctionExpression; parameters=1; async=true; generator=false
- initDragSession @92-125; FunctionDeclaration; parameters=2; async=false; generator=false
- simulateDragAndDrop @127-164; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @149-149; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_drop_url @167-180; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @169-178; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_drop_file @183-196; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @185-194; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_drop_multiple_urls @199-215; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @200-214; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_drop_multiple_files @218-234; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @219-233; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_drop_file_and_url @237-253; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @238-252; ArrowFunctionExpression; parameters=1; async=true; generator=false
- test_drop_incompat_file @257-270; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @258-269; ArrowFunctionExpression; parameters=1; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_file_xpi_no_process_switch.js

Blob: `dbf4b6eddc0302ac75a16679d53357d8949ea8ff`. Role: test-path,source. Parse: module.

- promiseInstallNotification @6-29; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @7-28; ArrowFunctionExpression; parameters=1; async=false; generator=false
- popupshown @8-25; FunctionDeclaration; parameters=1; async=false; generator=false
- CheckBrowserInPid @31-35; FunctionDeclaration; parameters=3; async=false; generator=false
- (anonymous) @32-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- testOpenedAndDraggedXPI @37-110; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @39-41; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @113-119; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_globalwarnings.js

Blob: `17f9b44684a2c82195c4f9992e6fa4282d174f52`. Role: test-path,source. Parse: module.

- loadDetail @7-17; FunctionDeclaration; parameters=2; async=true; generator=false
- checkMessageShown @19-53; FunctionDeclaration; parameters=4; async=false; generator=false
- checkNoMessages @55-65; FunctionDeclaration; parameters=1; async=false; generator=false
- clickMessageAction @67-71; FunctionDeclaration; parameters=1; async=false; generator=false
- checkCompatibility @73-114; FunctionExpression; parameters=0; async=true; generator=false
- checkSecurity @116-160; FunctionExpression; parameters=0; async=true; generator=false
- checkSafeMode @162-196; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_gmpProvider.js

Blob: `f70899c7e9635c3321a9fec73beb9c5bd7ab4b1c`. Role: test-path,source. Parse: module.

- checkForAddons @34-37; ArrowFunctionExpression; parameters=0; async=false; generator=false
- installAddon @39-43; ArrowFunctionExpression; parameters=1; async=false; generator=false
- openDetailsView @46-58; FunctionDeclaration; parameters=2; async=false; generator=false
- initializeState @60-95; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @64-79; FunctionExpression; parameters=0; async=true; generator=false
- testNotInstalledDisabled @97-123; FunctionExpression; parameters=0; async=true; generator=false
- testNotInstalledDisabledDetails @125-150; FunctionExpression; parameters=0; async=true; generator=false
- testNotInstalled @152-183; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @160-164; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testNotInstalledDetails @185-206; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @195-199; ArrowFunctionExpression; parameters=0; async=false; generator=false
- testInstalled @208-240; FunctionExpression; parameters=0; async=true; generator=false
- testInstalledDetails @242-260; FunctionExpression; parameters=0; async=true; generator=false
- testInstalledGlobalEmeDisabled @262-277; FunctionExpression; parameters=0; async=true; generator=false
- testPreferencesButton @279-325; FunctionExpression; parameters=0; async=true; generator=false
- testUpdateButton @327-358; FunctionExpression; parameters=0; async=true; generator=false
- testEmeSupport @360-409; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://gre/modules/GMPInstallManager.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/GMPUtils.sys.mjs @11; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_history_navigation.js

Blob: `7581595227df6695aacfadb38a921097688aeebb`. Role: test-path,source. Parse: module.

- go_back @47-49; FunctionDeclaration; parameters=0; async=false; generator=false
- go_back_key @54-56; FunctionDeclaration; parameters=0; async=false; generator=false
- go_forward_key @58-60; FunctionDeclaration; parameters=0; async=false; generator=false
- go_forward @62-64; FunctionDeclaration; parameters=0; async=false; generator=false
- check_state @66-69; FunctionDeclaration; parameters=2; async=false; generator=false
- is_in_list @71-84; FunctionDeclaration; parameters=4; async=false; generator=false
- is_in_detail @86-100; FunctionDeclaration; parameters=4; async=false; generator=false
- is_in_discovery @102-109; FunctionDeclaration; parameters=3; async=false; generator=false
- expand_addon_element @111-117; FunctionDeclaration; parameters=2; async=true; generator=false
- wait_for_page_load @119-121; FunctionDeclaration; parameters=1; async=false; generator=false
- test_navigate_history @125-168; FunctionExpression; parameters=0; async=true; generator=false
- test_navigate_between_webpage_and_aboutaddons @171-235; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @228-228; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_keyboard_history_navigation @239-293; FunctionExpression; parameters=0; async=true; generator=false
- test_single_history_entry @296-318; FunctionExpression; parameters=0; async=true; generator=false
- test_new_history_entry_while_opened @322-346; FunctionExpression; parameters=0; async=true; generator=false
- test_navigate_back_from_website @350-417; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @364-412; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @365-412; FunctionExpression; parameters=0; async=false; generator=false
- listener @371-411; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @383-383; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @384-410; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @387-409; FunctionExpression; parameters=0; async=false; generator=false
- listener @395-407; FunctionExpression; parameters=1; async=true; generator=false
- test_refresh_listview_donot_add_history_entries @420-455; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @432-452; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @434-451; FunctionExpression; parameters=1; async=true; generator=false
- test_refresh_detailview_donot_add_history_entries @458-492; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @469-489; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @471-488; FunctionExpression; parameters=1; async=true; generator=false
- test_history_on_detailview_extension_removed @496-526; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @517-517; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_open_last_view @529-540; FunctionExpression; parameters=0; async=true; generator=false
- test_discopane_first_history_entry @543-564; FunctionExpression; parameters=0; async=true; generator=false
- test_discopane_second_history_entry @567-597; FunctionExpression; parameters=0; async=true; generator=false
- test_initialSelectedView_on_aboutaddons_reload @599-618; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @15; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_html_a11y_no_horizontal_overflow.js

Blob: `ba1c33384b8f20aaa77935ec5ab9d038e3a53577`. Role: test-path,source. Parse: module.

- checkNoElementOverflow @11-24; FunctionDeclaration; parameters=4; async=false; generator=false
- extraCheck @31-32; ArrowFunctionExpression; parameters=2; async=false; generator=false
- setZoom @36-42; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @39-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- waitForReflow @44-48; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @45-47; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @46-46; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkNoHorizontalOverflow @50-57; FunctionDeclaration; parameters=2; async=false; generator=false
- test_no_horizontal_overflow_when_zoomed @59-79; FunctionExpression; parameters=0; async=true; generator=false

### toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions.js

Blob: `ce8b42105ca14ad4720a7288068e40a5e7999d55`. Role: test-path,source. Parse: module.

- assertVisibleSections @24-38; ArrowFunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @29-29; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @30-30; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @34-34; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyLearnMoreLink @40-46; ArrowFunctionExpression; parameters=2; async=false; generator=false
- background @48-69; FunctionDeclaration; parameters=0; async=true; generator=false
- (anonymous) @49-60; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @61-63; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @65-68; ArrowFunctionExpression; parameters=1; async=true; generator=false
- getExtensions @71-225; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @204-213; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @206-212; FunctionExpression; parameters=2; async=false; generator=false
- waitForPermissionChange @227-240; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @228-239; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listener @230-237; ArrowFunctionExpression; parameters=2; async=false; generator=false
- runTest @242-524; FunctionDeclaration; parameters=1; async=true; generator=false
- testTogglePermissionButton @355-408; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @360-360; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @405-407; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testExternalPermissionChange @412-450; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @447-449; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testOtherPermissionChange @454-473; FunctionDeclaration; parameters=2; async=true; generator=false
- testPermissionsView @526-641; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @643-652; ArrowFunctionExpression; parameters=0; async=true; generator=false
- testPermissionsView_MV2 @654-656; FunctionExpression; parameters=0; async=true; generator=false
- testPermissionsView_MV3_noInstallPrompt @658-667; FunctionExpression; parameters=0; async=true; generator=false
- testPermissionsView_MV3 @669-678; FunctionExpression; parameters=0; async=true; generator=false
- testPermissionsViewStates @680-751; FunctionExpression; parameters=0; async=true; generator=false
- install_addon @711-715; FunctionDeclaration; parameters=1; async=true; generator=false
- wait_for_addon_item_updated @717-719; FunctionDeclaration; parameters=1; async=false; generator=false
- testTempOrigins @753-824; FunctionExpression; parameters=0; async=true; generator=false
- background @769-775; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @770-774; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @771-773; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkExpected @778-787; FunctionDeclaration; parameters=2; async=true; generator=false
- testAllUrlsNotGrantedUnconditionally_MV3 @826-858; FunctionExpression; parameters=0; async=true; generator=false
- background @839-842; FunctionExpression; parameters=0; async=true; generator=false
- test_OneOfMany_AllSites_toggle @860-943; FunctionExpression; parameters=0; async=true; generator=false
- testOverrideLocalization @945-1035; FunctionExpression; parameters=0; async=true; generator=false
- mockCleanup @974-982; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mockCleanup @976-976; ArrowFunctionExpression; parameters=0; async=false; generator=false
- test_data_collection @1037-1620; FunctionExpression; parameters=0; async=true; generator=false
- verifyUI @1042-1060; FunctionExpression; parameters=1; async=true; generator=false
- getFluentId @1049-1049; ArrowFunctionExpression; parameters=1; async=false; generator=false
- verifyUI @1067-1119; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1126-1143; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1150-1201; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1209-1276; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1285-1340; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1348-1397; FunctionExpression; parameters=1; async=true; generator=false
- verifyUI @1407-1494; FunctionExpression; parameters=1; async=true; generator=false
- togglePerms @1495-1545; FunctionExpression; parameters=2; async=true; generator=false
- test_data_collection_and_disabled_extension @1622-1692; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @1; ChromeUtils-import-literal
- Module resource://gre/modules/Extension.sys.mjs @4; ChromeUtils-import-literal
- Module resource://gre/modules/ExtensionPermissions.sys.mjs @7; ChromeUtils-import-literal
- Module resource://gre/modules/ExtensionPermissionMessages.sys.mjs @11; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_file_access.js

Blob: `429cf23847689e3bccce659f1c463d3d96b95258`. Role: test-path,source. Parse: module.

- getAddonCardWithPermsSection @15-32; FunctionDeclaration; parameters=2; async=true; generator=false
- getFileToggle @34-38; FunctionDeclaration; parameters=1; async=false; generator=false
- verifyToggleFilePermission @40-71; FunctionDeclaration; parameters=2; async=true; generator=false
- (anonymous) @52-55; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @65-68; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @73-77; ArrowFunctionExpression; parameters=0; async=true; generator=false
- test_without_any_file_permissions @79-97; FunctionExpression; parameters=0; async=true; generator=false
- do_test_all_urls_permission @99-134; FunctionDeclaration; parameters=1; async=true; generator=false
- test_all_urls_permission_mv2 @136-138; FunctionExpression; parameters=0; async=true; generator=false
- test_all_urls_permission_mv3 @140-142; FunctionExpression; parameters=0; async=true; generator=false
- test_with_file_in_content_scripts_matches @144-166; FunctionDeclaration; parameters=1; async=true; generator=false
- test_with_file_in_content_scripts_matches_mv2 @168-170; FunctionExpression; parameters=0; async=true; generator=false
- test_with_file_in_content_scripts_matches_mv3 @172-174; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @6; ChromeUtils-import-literal
- Module resource://gre/modules/ExtensionPermissions.sys.mjs @9; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_policy_blocked.js

Blob: `9d3f2903411f36b6fa91f0bf39fe414b650cce25`. Role: test-path,source. Parse: module.

- loadPolicyExtension @15-28; FunctionDeclaration; parameters=2; async=true; generator=false
- openOptionalPermissionToggles @32-57; FunctionDeclaration; parameters=1; async=true; generator=false
- cleanup @59-63; FunctionDeclaration; parameters=2; async=true; generator=false
- verifyBlockedToggleUI @65-89; FunctionDeclaration; parameters=2; async=true; generator=false
- test_blocked_permission_toggle_global @91-97; FunctionExpression; parameters=0; async=true; generator=false
- test_blocked_permission_toggle_per_id @99-106; FunctionExpression; parameters=0; async=true; generator=false
- test_allowed_permission_toggle_is_not_disabled @108-144; FunctionExpression; parameters=0; async=true; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @6; ChromeUtils-import-literal
- Module resource://testing-common/EnterprisePolicyTesting.sys.mjs @9; ChromeUtils-import-literal

### toolkit/mozapps/extensions/test/browser/browser_html_detail_permissions_userScripts.js

Blob: `3e57c88cfd2395df6d3ea18051a54c110f0843c4`. Role: test-path,source. Parse: module.

- (anonymous) @14-18; ArrowFunctionExpression; parameters=0; async=true; generator=false
- loadUserScriptsExtension @20-49; FunctionDeclaration; parameters=1; async=false; generator=false
- background @28-47; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-37; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @38-46; ArrowFunctionExpression; parameters=1; async=false; generator=false
- loadPermissionsView @51-65; FunctionDeclaration; parameters=1; async=true; generator=false
- test_userScripts_permission_warning @67-146; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @80-81; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Module resource://testing-common/AddonTestUtils.sys.mjs @5; ChromeUtils-import-literal
- Module resource://gre/modules/ExtensionPermissionMessages.sys.mjs @8; ChromeUtils-import-literal

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
