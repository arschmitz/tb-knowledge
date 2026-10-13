<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["mobile"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["98ce839b4b01243a83e64c9e51f0bdfbd9c64dc3d91080051f5ca0954f2acc67"],"sourceAt":"2026-10-13T04:14:46.642314+00:00","correctionOf":"notes/bcacb335-d717-4b28-b858-f2520b4d3ce0.md"}} -->
# firefox/mobile structural source map 423

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/middleware/AdsTelemetryMiddlewareTest.kt` | `1cebd5aed57807f8e77334c36079dbfde1d24d5f` | 4931 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AdsTelemetryMiddlewareTest@27; setup@33

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/middleware/SearchMiddlewareTest.kt` | `d64ed826fb0865ae6e6a8eb55cf26f1149f38dfd` | 76894 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchMiddlewareTest@41; setUp@47; tearDown@52; runTest@815; runTest@862; runTest@898; runTest@1139; runTest@1222; runTest@1237; runTest@1282; runTest@1668; wait@1835

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/region/RegionManagerTest.kt` | `ad65214bad3918ff180461280fa05a57f9cc2ff7` | 5308 bytes | test-path,source | UTF-8 | mode 100644
Declarations: RegionManagerTest@17; FakeLocationService@138

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/region/RegionMiddlewareTest.kt` | `ac533661fb4268962db2562708f8fd5215eea968` | 7771 bytes | test-path,source | UTF-8 | mode 100644
Declarations: RegionMiddlewareTest@27; setUp@35; runTest@49; runTest@80; runTest@139

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/BundledSearchEnginesStorageTest.kt` | `e6dcb175ec76ebb9720eda9b977708887f9990c4` | 39428 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BundledSearchEnginesStorageTest@21; assertContainsSearchEngine@162; assertContainsNotSearchEngine@171

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/CustomSearchEngineStorageTest.kt` | `2dcbe3dd9b9b672e520a3b2de2b46ecf993a3712` | 4415 bytes | test-path,source | UTF-8 | mode 100644
Declarations: CustomSearchEngineStorageTest@19

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/ParseSearchPluginsTest.kt` | `7567f422d9306d90cc27cfb28bc5db9dd16c9864` | 4070 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ParseSearchPluginsTest@22; parserNoSearchExtraParams@26; parserWithSearchExtraParams@47

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/SearchEngineReaderTest.kt` | `d596e69e1ea36d0799c9b3d481bf658d56ecea99` | 20952 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchEngineReaderTest@35; setUp@43; assertThrows@263; assertThrows@276

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/SearchEngineSelectorRepositoryTest.kt` | `99405025cae2ae300179aacdef3c6e6407af94f8` | 7701 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchEngineSelectorRepositoryTest@35; setUp@45

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/storage/SearchEngineWriterTest.kt` | `9fbc2d4ef4d8b6519e2fc7ff1bafcc636fd3cf37` | 9598 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchEngineWriterTest@34

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/suggestions/ParserTest.kt` | `911312af89170354b7a625a274d9a65c0586596f` | 16612 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ParserTest@13

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/suggestions/SearchSuggestionClientTest.kt` | `71434e2309ba10131d43a8f99d1394d6c6f5270d` | 5222 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchSuggestionClientTest@20

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/BaseSearchTelemetryTest.kt` | `d9f0c0aea89e406f9e919e95f9c3bfe40c91379c` | 7343 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BaseSearchTelemetryTest@30; setup@85; processMessage@97

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/SearchProviderModelTest.kt` | `1ff125a7c85b6c8a00af47fe9bedf7c78e2318df` | 1516 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SearchProviderModelTest@10

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/SerpTelemetryRepositoryTest.kt` | `a940e6160ace30be96d5977575cc0531f46db87d` | 5008 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SerpTelemetryRepositoryTest@29; setup@59

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/UtilsKtTest.kt` | `4da94b4ed4bacbdb6ceb8540723bbdbb9f0bf87d` | 890 bytes | test-path,source | UTF-8 | mode 100644
Declarations: UtilsKtTest@14

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/ads/AdsTelemetryTest.kt` | `2521afd7130bd1819a2a00dd7e3ca1fd83cf446a` | 11348 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AdsTelemetryTest@42; setUp@107; process@133; process@150; process@168; process@202; process@232; process@251

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/telemetry/incontent/InContentTelemetryTest.kt` | `0fb5c5b8ce8b33492c282613c1ee1ffdc8878848` | 22642 bytes | test-path,source | UTF-8 | mode 100644
Declarations: InContentTelemetryTest@40; setup@137; process@182; process@205; process@226; process@248; process@270; process@292; process@314; process@336; process@358; process@380; process@402; process@424; process@446; process@468; process@490; process@512

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/trendingsearches/TrendingSearchClientTest.kt` | `b2ef44c056b6089c8e468a59e31d389db7d1b875` | 3405 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TrendingSearchClientTest@17

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/widget/AppSearchWidgetProviderTest.kt` | `4e897390323ccca1b850163729c3d3fdadb62825` | 5030 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AppSearchWidgetProviderTest@16; testGetLayoutSize@21; testGetLargeLayout@43; testGetMediumLayout@55; testGetSmallLayout@67; testGetExtraSmall2Layout@79; testGetExtraSmall1Layout@97; testGetText@115

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/widget/BaseVoiceSearchActivityExtendedForTests.kt` | `de42091f0b2043d5e0ebb420eff70766c017cae3` | 663 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BaseVoiceSearchActivityExtendedForTests@10; onSpeechRecognitionStarted@16; onSpeechRecognitionEnded@18; addMenuProvider@20

`mobile/android/android-components/components/feature/search/src/test/java/mozilla/components/feature/search/widget/BaseVoiceSearchActivityTest.kt` | `ed5228bde9a831258c5a735eaa7d4b80fb51cdb2` | 4943 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BaseVoiceSearchActivityTest@34; setup@41; allowVoiceIntentToResolveActivity@50

`mobile/android/android-components/components/feature/search/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/search/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/README.md` | `315ee5443c3610bf5869c625db02fbdc750698a3` | 887 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/build.gradle` | `2b9689b25016bd08770f58f4d81fefdea367d818` | 1112 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/src/main/java/mozilla/components/feature/serviceworker/ServiceWorkerSupport.kt` | `f2eaa3f08352943be2dad4e2e45d2ac3e2334522` | 2109 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/src/test/java/mozilla/components/feature/serviceworker/ServiceWorkerSupportTest.kt` | `89b023fc706e9ae5e6da2c655063eccfe6b5ebde` | 2634 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ServiceWorkerSupportTest@25

`mobile/android/android-components/components/feature/serviceworker/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/serviceworker/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/README.md` | `785420bfa55bbcb95b8b19f2c38cbb0ca162add3` | 3324 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/build.gradle` | `1363778c49bce6d6b259c6f938564c2321d491b1` | 1480 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/CoordinateScrollingFeature.kt` | `7f5c1293fa71fc2e82a57e08e256c1000d89cf82` | 2848 bytes | source | UTF-8 | mode 100644
Declarations: CoordinateScrollingFeature@32; start@42; stop@53; onLoadingStateChanged@57

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/FullScreenFeature.kt` | `f1786ee1684ea24d6204a4d5a02572c17005ee39` | 4680 bytes | source | UTF-8 | mode 100644
Declarations: start@37; stop@48; onChange@52

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/HistoryDelegate.kt` | `9378b704f4c6857c70f6e5773ac95fa65e780419` | 2393 bytes | source | UTF-8 | mode 100644
Declarations: HistoryDelegate@14

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/PictureInPictureFeature.kt` | `49fa99c1fcfbcc2ff1db29631e98ab50fb10ee84` | 3451 bytes | source | UTF-8 | mode 100644
Declarations: PictureInPictureFeature@27; onPictureInPictureModeChanged@73

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/ScreenOrientationFeature.kt` | `c454179ce7c2ad6e38835c463fd685fb091fc6ce` | 1963 bytes | source | UTF-8 | mode 100644
Declarations: ScreenOrientationFeature@16; start@21; stop@25; onOrientationUnlock@43

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/SessionFeature.kt` | `017b800a752e2de7deb726acac889e4cdf2d4e47` | 3303 bytes | source | UTF-8 | mode 100644
Declarations: SessionFeature@17; start@28; stop@79; release@87

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/SessionUseCases.kt` | `3454d73fa49eb04cf90da2ba9837b81aec6378d8` | 18459 bytes | source | UTF-8 | mode 100644
Declarations: SessionUseCases@20; LoadUrlUseCase@28; DefaultLoadUrlUseCase@38; LoadDataUseCase@116; ReloadUrlUseCase@144; StopLoadingUseCase@168; GoBackUseCase@183; GoForwardUseCase@206; GoToHistoryIndexUseCase@230; RequestDesktopSiteUseCase@255; ExitFullScreenUseCase@274; CrashRecoveryUseCase@286; invoke@288; invoke@305; PurgeHistoryUseCase@313; UpdateLastAccessUseCase@329; SaveToPdfUseCase@359; PrintContentUseCase@380; TranslateUseCase@402; TranslateRestoreUseCase@428

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/SettingsUseCases.kt` | `dff6c1ea140a58b6be3de221fbda51f9e6547da1` | 1930 bytes | source | UTF-8 | mode 100644
Declarations: SettingsUseCases@20; UpdateTrackingProtectionUseCase@28

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/SwipeRefreshFeature.kt` | `74364d55d2b9226f169bfecd1345cdee094123bb` | 4648 bytes | source | UTF-8 | mode 100644
Declarations: SwipeRefreshFeature@36; start@52; stop@76; onRefresh@94

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/TrackingProtectionUseCases.kt` | `d51e273c5ee107492185a419767e22345fb0a749` | 10761 bytes | source | UTF-8 | mode 100644
Declarations: TrackingProtectionUseCases@24; AddExceptionUseCase@30; RemoveExceptionUseCase@55; RemoveAllExceptionsUseCase@96; ContainsExceptionUseCase@113; FetchExceptionsUseCase@137; FetchTrackingLogUserCase@151; FetchTrackingEventsUseCase@177; FetchTotalTrackersBlockedUseCase@198; FetchEarliestTrackingDateUseCase@214

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/engine/EngineViewPresenter.kt` | `b11ca994cce56e540f07989ad90b0f4f0de0a53d` | 4297 bytes | source | UTF-8 | mode 100644
Declarations: start@34; stop@53; onTabToRender@59; renderTab@74; stampLastVisibleAt@102

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/middleware/LastAccessMiddleware.kt` | `c882a385455ce6215cd3a3b6ae690cf44b21f1ec` | 3286 bytes | source | UTF-8 | mode 100644
Declarations: LastAccessMiddleware@17; when@27; when@39

`mobile/android/android-components/components/feature/session/src/main/java/mozilla/components/feature/session/middleware/undo/UndoMiddleware.kt` | `5c5b0eb534086063cbcb2c9bbd9cb415b8f3f44e` | 5769 bytes | source | UTF-8 | mode 100644
Declarations: UndoMiddleware@34; when@49

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/CoordinateScrollingFeatureTest.kt` | `073edf5c754ccce50074ea6f3274efdf66536f72` | 3378 bytes | test-path,source | UTF-8 | mode 100644
Declarations: CoordinateScrollingFeatureTest@27; setup@35

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/FullScreenFeatureTest.kt` | `ede0aa4a399d79266dbf9b69ecc3571a49203fd8` | 23315 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FullScreenFeatureTest@27; runTest@33; runTest@57; runTest@88; runTest@133; runTest@172; runTest@219; runTest@288; runTest@366; runTest@418; runTest@470; runTest@506; runTest@528; runTest@562; runTest@611; runTest@646

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/HistoryDelegateTest.kt` | `f9ff5db6d097d236c3242d540ce92c4f120213b3` | 9127 bytes | test-path,source | UTF-8 | mode 100644
Declarations: HistoryDelegateTest@26; TestHistoryStorage@164; cleanup@254; cancelWrites@258; cancelReads@262; cancelReads@266

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/PictureInPictureFeatureTest.kt` | `e4bc45dda39611f838d644de5110719c546669fb` | 13068 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PictureInPictureFeatureTest@42; setUp@48

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/ScreenOrientationFeatureTest.kt` | `b6514d1b758033d1c28011128239c6d413ad32c8` | 3408 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ScreenOrientationFeatureTest@22

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/SessionFeatureTest.kt` | `565e31038cb33cd152fd9bcfa3c2c8a015ec9107` | 20159 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SessionFeatureTest@36; runTest@42; runTest@63; runTest@84; runTest@104; runTest@132; runTest@153; runTest@180; runTest@205; runTest@233; runTest@260; runTest@284; runTest@329; runTest@374; runTest@397; runTest@423; runTest@446; runTest@470; runTest@497

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/SessionUseCasesTest.kt` | `0002e6b150f9429b83f24d1d5dd35dc1638ef487` | 18674 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SessionUseCasesTest@36; setUp@44; loadUrlWithEngineSession@74; loadUrlWithoutEngineSession@134; loadData@173; reload@209; reloadBypassCache@225; goBack@245; goForward@264; goToHistoryIndex@283; requestDesktopSite@301; exitFullscreen@326

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/SettingsUseCasesTest.kt` | `8473c2a945cd4962bccebe08de1168a27af8ce03` | 2853 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SettingsUseCasesTest@21; updateTrackingProtection@23

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/SwipeRefreshFeatureTest.kt` | `40a1a1bf12d578b419229f435792432e06c1eb39` | 6061 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SwipeRefreshFeatureTest@35; setup@44; runTest@81; runTest@94; runTest@107; setVerticalClipping@134; setDynamicToolbarMaxHeight@136; setActivityContext@138; clearSelection@142; render@144; release@146; removeWindowInsetsListener@155

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/TrackingProtectionUseCasesTest.kt` | `df448d2608b3c345b5db19a148bffa9e6045c6d9` | 12440 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TrackingProtectionUseCasesTest@43; setUp@51

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/middleware/LastAccessMiddlewareTest.kt` | `3ef93107aa201ba7f1b509bf1cb4817c3098c75d` | 12165 bytes | test-path,source | UTF-8 | mode 100644
Declarations: LastAccessMiddlewareTest@26

`mobile/android/android-components/components/feature/session/src/test/java/mozilla/components/feature/session/middleware/undo/UndoMiddlewareTest.kt` | `add2f694ae4615d272e84153c0917f439c233b2e` | 12522 bytes | test-path,source | UTF-8 | mode 100644
Declarations: UndoMiddlewareTest@22; runTest@27; runTest@59; runTest@91; runTest@123; runTest@155; runTest@186; runTest@233; withContext@275

`mobile/android/android-components/components/feature/session/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/session/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/README.md` | `6f188d49d930bd8ac7964de5ed279040f52a56c8` | 632 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/build.gradle` | `69adc7ec708e9cb3dfeefbb82a77c5b94c663bc5` | 1991 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/schemas/mozilla.components.feature.share.db.RecentAppsDatabase/1.json` | `6a268772896b912dc2c62ebd648495a47d379eb1` | 1141 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/schemas/mozilla.components.feature.share.db.RecentAppsDatabase/2.json` | `241b612fa965e9b89f20a3d1f08d0fba98b1625e` | 1146 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/src/androidTest/java/mozilla/components/feature/share/RecentAppsDaoTest.kt` | `3f6884af74c1ba7e5d98583a795de89568e53cb0` | 3443 bytes | source | UTF-8 | mode 100644
Declarations: RecentAppsDaoTest@18; setup@24; tearDown@31; testGetTwoMostRecentApps@36; testIncrementSelectedAppCountAndDecayAllOthers@57; testAddNewlyInstalledAppsToOurDatabase@76; testDeleteAnAppFromOurDatabase@96

`mobile/android/android-components/components/feature/share/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/RecentApp.kt` | `4742a6b9c5aeaf32b9c738b6e4b192a0808829ae` | 691 bytes | source | UTF-8 | mode 100644
Declarations: RecentApp@13

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/RecentAppsStorage.kt` | `b6496cf1503820bb13e60a3cecc8581c0c99f597` | 2172 bytes | source | UTF-8 | mode 100644
Declarations: RecentAppsStorage@14; updateRecentApp@26; deleteRecentApp@35; updateDatabaseWithNewApps@52

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/adapter/RecentAppAdapter.kt` | `7d66feed05781fd12c5ea7974da2b75b7e7d982e` | 833 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/db/RecentAppEntity.kt` | `06b1dab258f35eb6ba53df52a9540dcc321913b3` | 726 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/db/RecentAppsDao.kt` | `9596c04c2647a5761a2c0e4a52e71ad80784c314` | 2004 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/share/src/main/java/mozilla/components/feature/share/db/RecentAppsDatabase.kt` | `6625b31b9c87bf6faf9e1c5200951cc5b3f0c6d5` | 2088 bytes | source | UTF-8 | mode 100644
Declarations: migrate@49

`mobile/android/android-components/components/feature/share/src/test/java/mozilla/components/feature/share/RecentAppStorageTest.kt` | `5bdc71e774c76b4c3095a4fc83f30d0162ca778e` | 2546 bytes | test-path,source | UTF-8 | mode 100644
Declarations: RecentAppStorageTest@17; setup@24

`mobile/android/android-components/components/feature/sitepermissions/README.md` | `5eefdb579c7dc32f8a1b780cfc434703e8e92ef5` | 2215 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/build.gradle` | `c75eb0b228fb7941e737b07586b427f21c201a87` | 2859 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/lint-baseline.xml` | `454d25157cb5b69fc9db8f29282302d88e48f1b0` | 543 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/1.json` | `1363bf43de9d9b6e666d581b5044a878ce7039ea` | 2512 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/2.json` | `344aaccc301e4277b74342ea09ebce85756cd46d` | 2295 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/3.json` | `bfc2906dc9e27aa102dd5255b133bdcf3ea7803a` | 2746 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/4.json` | `44e6233c317d883c81a905648898a997a28ce084` | 2980 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/5.json` | `c570ac00375efc59863e4f098c1373fbf16eb22b` | 2980 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/6.json` | `5780fd467f9b5134fa7cee35f89513a42e12e41d` | 2980 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/7.json` | `87a2a06f6a553e4aa27ad25bf7bc27b0b6ca6512` | 2980 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/8.json` | `97a9421bd1a08e66c39d9a028d4fb0027ba95d54` | 3226 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/schemas/mozilla.components.feature.sitepermissions.db.SitePermissionsDatabase/9.json` | `39025c9af3be8d34239bb5d17ef93122d1d59891` | 3607 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/androidTest/java/mozilla/components/feature/sitepermissions/db/OnDeviceSitePermissionsStorageTest.kt` | `1c21c0dff2b18290c8abd3c17e57a6bfeee6126e` | 13271 bytes | source | UTF-8 | mode 100644
Declarations: OnDeviceSitePermissionsStorageTest@29; setUp@44; tearDown@53; migrate1to2@74; migrate2to3@117; migrate3to4@143; migrate4to5@168; migrate5to6@189; migrate6to7@212; migrate8to9@237

`mobile/android/android-components/components/feature/sitepermissions/src/androidTest/java/mozilla/components/feature/sitepermissions/db/SitePermissionsDaoTest.kt` | `c0df3cbeadd418715d429e5a6bd5a5b038cbc344` | 3882 bytes | source | UTF-8 | mode 100644
Declarations: SitePermissionsDaoTest@22; setUp@31; tearDown@37; testInsertingAndReadingSitePermissions@42; testRemoveAllSitePermissions@54; testUpdateAndDeleteSitePermissions@71

`mobile/android/android-components/components/feature/sitepermissions/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/NotificationPermissionDialogFragment.kt` | `c78f85c708401b6c348146da839087fb066451eb` | 4100 bytes | source | UTF-8 | mode 100644
Declarations: NotificationPermissionDialogFragment@24; AcornTheme@43

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/OnDiskSitePermissionsStorage.kt` | `bb93df55e964d2943d4f8fff2145ab0ae756e903` | 8312 bytes | source | UTF-8 | mode 100644
Declarations: OnDiskSitePermissionsStorage@38

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/PermissionDialog.kt` | `b3e9fc117114f0960b56b5905afa9c7baa4eeeef` | 4461 bytes | source | UTF-8 | mode 100644
Declarations: LaunchedEffect@48; PermissionDialogPreview@98; PermissionDialogPrivatePreview@114

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/SitePermissionsDialogFragment.kt` | `c20fa51f7da7874b5f7261762bc0594b3e6b1e21` | 14755 bytes | source | UTF-8 | mode 100644
Declarations: onDismiss@145; onEnterAnimationComplete@150; showSettingsPrompt@260

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/SitePermissionsFacts.kt` | `5457898ad473720f09ba875398215e427c579ab0` | 2217 bytes | source | UTF-8 | mode 100644
Declarations: SitePermissionsFacts@14

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/SitePermissionsFeature.kt` | `27b1513678ef7f1c5e75639729d6d2c56176dd37` | 54991 bytes | source | UTF-8 | mode 100644
Declarations: SitePermissionsFeature@107; start@148; maybeSetUpDefaultLearnMoreUrlProvider@169; stop@271; onPermissionsResult@289; onContentPermissionGranted@397; withContext@526; when@592; when@709; when@802; when@881; get@1108; when@1109; get@1119; when@1122; reattachFragment@1159; when@1196; when@1237

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/SitePermissionsLearnMoreUrlProvider.kt` | `91311168496d5f774d5135599f821b0641550c09` | 1417 bytes | source | UTF-8 | mode 100644
Declarations: SitePermissionsLearnMoreUrlProvider@10; when@28

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/SitePermissionsRules.kt` | `0038eb578fbb2a00ac7116ad9a4eabbd57afd114` | 4874 bytes | source | UTF-8 | mode 100644
Declarations: class@30; when@36; class@44; when@49; when@56; when@71

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/db/SitePermissionsDao.kt` | `ddcb15d738a0256547e44e48d322ce60db046846` | 1244 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/db/SitePermissionsDatabase.kt` | `698d9022c304f5fb492687e05d2b0b5bf2850e93` | 8324 bytes | source | UTF-8 | mode 100644
Declarations: migrate@81; migrate@105; migrate@125; migrate@140; migrate@152; migrate@160; migrate@175; migrate@189

`mobile/android/android-components/components/feature/sitepermissions/src/main/java/mozilla/components/feature/sitepermissions/db/SitePermissionsEntity.kt` | `da38aa7d9f6700fa4624c5d71c21c9aad377c03a` | 3138 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/layout/mozac_site_permissions_prompt.xml` | `2597739adb70787b815c737f1f908d43aa1078a6` | 4987 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ab/strings.xml` | `4b49b46d7f03eb1c6a4e4395eaa76d6c07f03c8d` | 5300 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-am/strings.xml` | `f18c144f40456faf5f17d2f345e763251a9506aa` | 5353 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-an/strings.xml` | `467726a483ea38cf3b7839d0f03b040e2d7b839d` | 4450 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ar/strings.xml` | `4e032c8f6974010343860c1b96aa8b1ba4f9f302` | 7345 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ast/strings.xml` | `4cd73532dd0d85b2dc8637739c4449451871fcdb` | 5103 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-az/strings.xml` | `ee8863f0cf8a89e4a457dee446a0cdb218681e55` | 3531 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-azb/strings.xml` | `b6711f47460f7b2851e87702adeb29588b4d31b2` | 5292 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-be/strings.xml` | `9dbd389e79fb277a20ed2419b0d114b6d624b3c8` | 7550 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-bg/strings.xml` | `639442be65a9272ffa67b9d9fc18f5b09c7ff0d0` | 7479 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-bn/strings.xml` | `83b0effb88b730d5e6aadb530125991140ff4d12` | 4544 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-bqi/strings.xml` | `02c085e21659964e8698a54e17731c9d24d4abb3` | 7211 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-br/strings.xml` | `f57b81dc0f91436a911e673187c3943a81ae9135` | 5029 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-bs/strings.xml` | `fb70ef4de8d39cc7417989289193ea6d953d8050` | 5977 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ca/strings.xml` | `e6b6c4091d3bf5c49a3681963443e2e919fe4973` | 6909 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-cak/strings.xml` | `a8cca497a7c5e16a41011e5aaa914f341fab6266` | 7143 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ceb/strings.xml` | `a402b05191b16fc8d60b75703043cd13c15baa11` | 3791 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ckb/strings.xml` | `b877cba414bd7f0c3bfc4e8aedb9e21643356f91` | 4107 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-co/strings.xml` | `96217f64da1f476b81a1ca809ebd8849c41763a5` | 7014 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-cs/strings.xml` | `e6abeb16f9c20108a5385b6e62c0c85fd82a12c6` | 6982 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-cy/strings.xml` | `ab57b38bfc55ebdc98c4f7f150c05413e580e87a` | 6860 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-da/strings.xml` | `da5911cbdb1c661e4400cdea5cd270fd1bf8ab79` | 6849 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-de/strings.xml` | `dd0734b12a9fc4600d98ce5449b3c973e0d56be6` | 6931 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-dsb/strings.xml` | `b181d72ea99370c73b625aea384bed75a0db6566` | 6878 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-el/strings.xml` | `26b5c958d315b7d450912bf1c2e015bb4798bac8` | 7791 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-en-rCA/strings.xml` | `6742173ea385113c4adae0bc2c7faa9ef57b89ed` | 6695 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-en-rGB/strings.xml` | `145826bad8b6e66d02cc36b18a097ae2516bd31a` | 6696 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-eo/strings.xml` | `41b94427745759fba63d3d98489b4c5302bebebc` | 6786 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-es-rAR/strings.xml` | `de1d3d3fcfea1e0d8288205e95850e8762818a3a` | 6817 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-es-rCL/strings.xml` | `8f57d2c7d47e4736028537520e4216982de95a25` | 6823 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-es-rES/strings.xml` | `02cf68c00821cd128663ea08fac128e01aa7dec2` | 6836 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-es-rMX/strings.xml` | `348f8f2a53830c0a444eaae29a1b5033a0a9f92d` | 6828 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-es/strings.xml` | `02cf68c00821cd128663ea08fac128e01aa7dec2` | 6836 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-et/strings.xml` | `2fe3929005bb0a4e18de3c25f0af5462d0283491` | 5027 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-eu/strings.xml` | `0f710190b09305d6e258e6d2acc845339eea2e3a` | 6907 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-fa/strings.xml` | `5aee3f3b6f833992a3142dc211679f862a1c6391` | 7639 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ff/strings.xml` | `6b97832b8c1d32766bc8097a3e42bd9752542cc1` | 3430 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-fi/strings.xml` | `69a9eb289cf381fe4df4d5a332f6a49c25e579ee` | 6849 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-fr/strings.xml` | `ac12bcfd5ebe1d24419708d0e4f744e128ffdfe0` | 7018 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-fur/strings.xml` | `b24d2ee8b1406f9a49976babee2c9d03fb8599ea` | 6843 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-fy-rNL/strings.xml` | `d3116c9f6dca9458d814e21bc6df99d10a85e6c2` | 6836 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ga-rIE/strings.xml` | `d8102c2e791f5c6e74c1a943ea0efef8ccf4981d` | 3317 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-gd/strings.xml` | `c09d5af84e9e5f78771e7a8ae5d3e93ea723e773` | 7175 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-gl/strings.xml` | `e9d5cd1a1fb00a37b4ac73447d20e60e4b08cd3a` | 6864 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-gn/strings.xml` | `3530a1d21136922ba14cd6f2cb3c20ed6ad3b676` | 6877 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-gu-rIN/strings.xml` | `bd6b1c56096585c2d555f8e671cfed7857382df8` | 3890 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hi-rIN/strings.xml` | `7f6ee27afc46fb05bb4a9720f8c2214ecb2fc0a8` | 8314 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hil/strings.xml` | `9dad2a3bca0f0813f301a9e63eb37e86a4b8e53d` | 475 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hr/strings.xml` | `a02d1391437dac17db9064f6b284d62165122247` | 6867 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hsb/strings.xml` | `f61c942f11ad3de5f7432a24d2363ae6e010afa2` | 6838 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hu/strings.xml` | `73aea28ba578c128a5cba44570bf07c45b62de2e` | 7086 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-hy-rAM/strings.xml` | `4515a2f45bef47893a8382663b7ea8bbb3c8245d` | 7605 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ia/strings.xml` | `3d1fbe825f746fab50150cfa10ac38ae5457cf78` | 6803 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-in/strings.xml` | `677fb82e23028080ea0327ebfcae94907e1e097c` | 6847 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-is/strings.xml` | `57578d3c1c72461fa0ab2e5cbed756c04ec1d22e` | 6830 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-it/strings.xml` | `4b37b5162d6630e86db7fdef7b174a999de850ed` | 6888 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-iw/strings.xml` | `c126c5dc1aa2be52959622e3b64bfecb66c8d322` | 7114 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ja/strings.xml` | `688856b5b99e51f1e845ad94f4fead22db316651` | 7116 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ka/strings.xml` | `e43283925fb2d7906b1ac5a4bf3d4785fd50bc6f` | 8487 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-kaa/strings.xml` | `dedc343c276aae722966bd2d69f8fe3066bf9034` | 5259 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-kab/strings.xml` | `b47c01600b8d273cfcc474a1900cdd00d57056d4` | 5905 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-kk/strings.xml` | `52e0bcba0b18b3e8e3244752d1821cd05607c42c` | 7812 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-km/strings.xml` | `ef72628ba5ca022abb5bd480a97531a78a94a867` | 8359 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-kmr/strings.xml` | `88a955424f5b7ecf2d8cb43d74511ca7e1f38fdc` | 5037 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-kn/strings.xml` | `783a66547e7ff2ea3b427d6a805be4832501b44e` | 3905 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ko/strings.xml` | `bb22f95139e6fc02506a484c3669e886f0c55a09` | 7119 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-lij/strings.xml` | `edf0fb67a543c3e1908880733fc0bcd9a0703cc7` | 3281 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-lo/strings.xml` | `c85176c6e705cc1eea9ea109dd60993f34f501a7` | 8166 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-lt/strings.xml` | `433857a4b6dfe6818435c446cfa226ca88abf8f7` | 4963 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-lv/strings.xml` | `9eb14f59049da8fba72f363198ce91bddebe450b` | 2105 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-meh/strings.xml` | `e5b4099558e8723231d25964fb0fd036ad1c9bc9` | 4670 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ml/strings.xml` | `de51ad64626a8d831f2ded78f1870db251e7a12c` | 7308 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-mr/strings.xml` | `5d32078146d4c8c7b0da9567a6e449cf5ea91f1d` | 3883 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-my/strings.xml` | `ddb41548ecfe780210cf6ebd6fde12613c32bfe5` | 4818 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-nb-rNO/strings.xml` | `6da56ef1903bd68d96a3600e74c1d775b4655aa2` | 6778 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ne-rNP/strings.xml` | `68d843964712bd62b01c7b0f4001fde38fec11bb` | 5996 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-nl/strings.xml` | `9ca2ae2deb2bfd3fd9b35e097961a26091ef906e` | 6851 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-nn-rNO/strings.xml` | `0467a5e4cc382795743ae001ef30e7fb2e772218` | 6754 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-oc/strings.xml` | `72ba9042766f230adaceafc9d0292e79833d38c3` | 6072 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-om/strings.xml` | `41c476889c5d8e890bb6cec72f5f4d8e431224ab` | 6917 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-or/strings.xml` | `3eea732fd5bc9e7fa658f9fc041c3a21f6f15ed9` | 1363 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-pa-rIN/strings.xml` | `22d7f8377fe6f07b13304bef659b932e5b22019c` | 8252 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-pa-rPK/strings.xml` | `04836c92e72c2a7ef0b4afacccdb374b988c25e4` | 5366 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-pl/strings.xml` | `cfcdfd7ff2ad81b8586c37b358ad3f9eefcd1b1c` | 7105 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ps/strings.xml` | `0523accde5403d99e6a3704d57c4e224e843a40a` | 7602 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-pt-rBR/strings.xml` | `ef56d9a10a1283dcf35158735ef2ea30341b91db` | 6819 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-pt-rPT/strings.xml` | `271b07c518a8d643fd0f92eae29314c35f61550b` | 6819 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-rm/strings.xml` | `bc4819b03327586bf9cd784545845a239320c9c6` | 6899 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ro/strings.xml` | `7a69ad72ee8521da902c93ac1960cb8d04378cc6` | 6907 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ru/strings.xml` | `9ce6840acd1413f3312ce8a015c0579b55dd39d1` | 7573 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sat/strings.xml` | `ca4842cadc58b2a38f33daedac09392b5f212002` | 8263 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sc/strings.xml` | `40207946a6579f49f2e591ab1c26c480d9669ff9` | 6988 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-scn/strings.xml` | `9d5e08f793a2cf32613e2d30201a035f54c2d20a` | 5055 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-si/strings.xml` | `901f19799b1e06b7a1636a0dfaa720714cd45076` | 5842 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sk/strings.xml` | `343b9a88ed73a95c75c6a59056599acb76052fd3` | 7053 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-skr/strings.xml` | `185c5b2b60b5cf3b6c43893df5904aa5b1bf8cb7` | 6246 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sl/strings.xml` | `906dafd42f67dc927da21f55fb51871fdbe83f24` | 6745 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sq/strings.xml` | `1de4bc6eddaa8389849a72c1377d4d8d6b785078` | 6899 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sr/strings.xml` | `9e286391148cb0b6463f42c65e6c35b2f38dac83` | 7469 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-su/strings.xml` | `75bbae5ad61a018418094490a75ac168158991a3` | 4932 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-sv-rSE/strings.xml` | `98ab40e91b14aa914917bd4c47b33e540cbc9de1` | 6839 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ta/strings.xml` | `7955ee01ffab2a017f6098cee568b20c1384592f` | 4394 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-te/strings.xml` | `12956a7d823abaa1beb4216bf75d7277e238068a` | 5062 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tg/strings.xml` | `bfbe8017d48133292b0d2d428a6ebaa78adcdda6` | 7978 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-th/strings.xml` | `ac282258d0ad72b7bf0a1f96b04daacea8c78f1a` | 8108 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tl/strings.xml` | `8fcbc4cea65e32288a0e8e7948cbbe336d682de8` | 5070 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tok/strings.xml` | `676de988ec55aad33bd1dfaed0f9d5a7fa5b652c` | 5032 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tr/strings.xml` | `8da3f6addec41fe83ffec2a53e81ba2399865a87` | 6782 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-trs/strings.xml` | `6e8ee3f75c4d47e427bf1b627fa08862dee97579` | 7173 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tt/strings.xml` | `fd0df791f68f58509d00a8b3a2d142c458fb1744` | 5728 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-tzm/strings.xml` | `2c0b988561b140975fad5a1dd4ad9d6266ec4421` | 3006 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ug/strings.xml` | `08f093a4c0d3eb5ad62b42cdcb21fe495297b5c8` | 7608 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-uk/strings.xml` | `6fdeaa66af7c7b1a25538c3b63a7814aca8af5b0` | 7510 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-ur/strings.xml` | `6ea906ee3dc92820c6617a2a9a076510858f0a75` | 4057 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-uz/strings.xml` | `54cbb43402e5f942f05ddf337a186f943c166909` | 5150 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-vec/strings.xml` | `915d53beea5c0b4505591e338a3824ce51a6d33a` | 3285 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-vi/strings.xml` | `0c9d05f92182ff14da2fa43392f36f5035024b4f` | 6994 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-yo/strings.xml` | `f383ad48f187185b3ea76699be94e29ab971f1b3` | 5345 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-yua/strings.xml` | `3853c955dfcdf839ab5972b08030cdc518f5e653` | 3308 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-zh-rCN/strings.xml` | `eb6d467e0a143122b949d27dafa589684e098833` | 6735 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values-zh-rTW/strings.xml` | `2828e28e03b64f8143a49d94b40160b268ebb684` | 6783 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/main/res/values/strings.xml` | `98075dd60993c8b1ee669b7c2ee4cdb514b390f1` | 6858 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/OnDiskSitePermissionsStorageTest.kt` | `c79c818aeb7896a6de2beb8567c162f997cc4964` | 9681 bytes | test-path,source | UTF-8 | mode 100644
Declarations: OnDiskSitePermissionsStorageTest@45; setup@52

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/SitePermissionsDialogFragmentTest.kt` | `658e751d684beb3065864fee681ec3651795e8a1` | 19536 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionsDialogFragmentTest@36; setUp@42; tearDown@47

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/SitePermissionsFactsTest.kt` | `e6016e55494502d1e543e1d7385be0fed5d1a414` | 5184 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionsFactsTest@19

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/SitePermissionsFeatureTest.kt` | `a88f45ea3375de12d67bce7a53190bd9d260c364` | 84699 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionsFeatureTest@97; setup@119; runTest@188; grant@1473; grant@1550; grant@1784; FakeSitePermissionsLearnMoreUrlProvider@1878

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/SitePermissionsRulesTest.kt` | `b7efcaac7f2efa7c8e2bd03fc4cb5e217a1cb6f0` | 10291 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionsRulesTest@35; setup@43

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/SitePermissionsTest.kt` | `aca6b539d4d2d93cf9c13df2d4944e467663d1df` | 4912 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionsTest@25

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/db/SitePermissionEntityTest.kt` | `a50005dcf809ac93f17040d38a39be82e5085d79` | 4257 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SitePermissionEntityTest@15

`mobile/android/android-components/components/feature/sitepermissions/src/test/java/mozilla/components/feature/sitepermissions/db/StatusConverterTest.kt` | `ba524761539d19ce9627516b3480603fdf6fff8a` | 2345 bytes | test-path,source | UTF-8 | mode 100644
Declarations: StatusConverterTest@15

`mobile/android/android-components/components/feature/sitepermissions/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/sitepermissions/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/README.md` | `20dbc6ddc1579bdaafc1542cd0da1b4248187540` | 344 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/build.gradle` | `8aa12849e0e84490358953645e8249278ce9edc9` | 1868 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ErrorReporter.kt` | `72f5590d15f492f4ecc6db0045587d17e23a1260` | 429 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/PageSummaryFeature.kt` | `31ccbbe13a06a687158d46e3c2a4dc66ca71547c` | 1776 bytes | source | UTF-8 | mode 100644
Declarations: PageSummaryFeature@16

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationAction.kt` | `a427c73b4ba91e3661cdc299aa42889cfaf370fe` | 7353 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationMiddleware.kt` | `7b024a0b79b088e544eaf4b604bd4972020a8932` | 6819 bytes | source | UTF-8 | mode 100644
Declarations: SummarizationMiddleware@36; when@51; withTimeout@59; withTimeout@129

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationReducer.kt` | `8e2d7b34404ab16060119608fb948829a1cbb61a` | 4665 bytes | source | UTF-8 | mode 100644
Declarations: when@18; when@34; when@45; when@55; when@60; when@94

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationScreen.kt` | `41b8ddc4c32e8bbb4486d007497b77101a04520c` | 15561 bytes | source | UTF-8 | mode 100644
Declarations: LaunchedEffect@90; CompositionLocalProvider@94; when@167; when@246; when@249; ApplyHaptics@269; LaunchedEffect@271; when@272; DragHandle@340; SummarizationStatePreviewProvider@370

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationSettingsWrapperMiddleware.kt` | `69397008ec6cc9501e3f16969fbdb34c1d5db281` | 2423 bytes | source | UTF-8 | mode 100644
Declarations: SummarizationSettingsWrapperMiddleware@20; when@30

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationState.kt` | `fc374b3935b7c8ebd9332b0c752893f0d2abaca3` | 5837 bytes | source | UTF-8 | mode 100644
Declarations: class@130

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/SummarizationStore.kt` | `92207c56782ba29bdf25203ea99a2350dc1765f4` | 373 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/content/ContentProvider.kt` | `2af4a1357581d331823f2d1fdf4f37503e97fe89` | 3157 bytes | source | UTF-8 | mode 100644
Declarations: PaywalledContentException@25

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/content/PageContentExtractor.kt` | `35002e7dcd26794f93e877bbc1aa60917bba690b` | 609 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/content/PageMetadata.kt` | `b61be6e02b2d5117af29f82ba864f174595994f2` | 754 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ext/Content.kt` | `1ce8215808ce5c97104c6d9b958f240cbb4c4514` | 3989 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ext/Flow.kt` | `f4962b25dacff99b77c602474a3eb6dbffd6547e` | 2017 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ext/LlmProvider.kt` | `9216a748a786e3754348c9998269d7bf01553570` | 1598 bytes | source | UTF-8 | mode 100644
Declarations: when@28

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/fakes/Llm.kt` | `1d25049e6e122367f4c85c02b4f696dee68f93b4` | 3128 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/ShakeSensitivitySlider.kt` | `e6368976f1c6a87519bdfdcf1de9e137d29b20da` | 8726 bytes | source | UTF-8 | mode 100644
Declarations: Column@70; remember@107; remember@143; Thumb@154; Track@175; repeat@197; FilledTrack@208; when@223; when@231; when@238

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizationSettings.kt` | `bb5546359980e2f38bb3d9dc9fcb56ec20879af1` | 9298 bytes | source | UTF-8 | mode 100644
Declarations: SummarizationSettings@27

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsAction.kt` | `7ed617fb4958229e96b54f20898bb43c519c3645` | 1094 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsMiddleware.kt` | `a8b01e004d1d3cf1663df6b9c58ae4e6b2538c72` | 2984 bytes | source | UTF-8 | mode 100644
Declarations: SummarizeSettingsMiddleware@21; when@44

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsReducer.kt` | `728229ac3dd912e0d877547168ebd2852f15b4b4` | 961 bytes | source | UTF-8 | mode 100644
Declarations: when@12

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsScreen.kt` | `90e9e3b9c323b03ac9c0174601ad9525af72177f` | 9807 bytes | source | UTF-8 | mode 100644
Declarations: Column@106; Column@170; CompositionLocalProvider@197; SummarizeSettingsContentPreview@237; Box@242

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsState.kt` | `0f1cfb80f2e67711f597bf0683ef4c84a56292ae` | 1071 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/settings/SummarizeSettingsStore.kt` | `e6a6c600dec4d7b48a24942b0bcc7a5f4d31aac6` | 394 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/ContentTooLongError.kt` | `f1d82ce477940cbf998f6c72186134c5c89ad1b6` | 2549 bytes | source | UTF-8 | mode 100644
Declarations: Column@30

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/DownloadConsent.kt` | `efa0fb2d18c451545a523d62ab58c78780e3b39a` | 4143 bytes | source | UTF-8 | mode 100644
Declarations: Column@53; Column@76; Column@105

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/DownloadError.kt` | `94b30de730d729abcc7e4a0e19123734292917f1` | 4439 bytes | source | UTF-8 | mode 100644
Declarations: Column@51; Column@72; Column@109

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/DownloadProgress.kt` | `84ddc569e5b95073e7bff66ae72be81ac510f8f6` | 4095 bytes | source | UTF-8 | mode 100644
Declarations: Column@54

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/FxaSignInContent.kt` | `b6a555110a08a9a5742a9adc98bad0eccefaf279` | 4729 bytes | source | UTF-8 | mode 100644
Declarations: Column@64; Column@118

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/InfoError.kt` | `4958d32e83b84afb4aac46d3823a36be9c6d6da1` | 3854 bytes | source | UTF-8 | mode 100644
Declarations: Column@43

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/LearnMoreLinkText.kt` | `708f15cb23c73d97b339b40ed3eafa2fa3decbc5` | 1417 bytes | source | UTF-8 | mode 100644
Declarations: PreviewLearnMoreLink@41

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/OffDeviceSummarizationContent.kt` | `97851bc9b5f2e5d3a7ed3b942b0e8715eea00f68` | 5407 bytes | source | UTF-8 | mode 100644
Declarations: Column@60; Column@79; Column@136

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/OnDeviceSummarizationConsent.kt` | `7f28d7e22cb0586dea3eb9aa5bf43026f92c5450` | 4336 bytes | source | UTF-8 | mode 100644
Declarations: Column@54; Column@73; Column@102

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/PaywalledContentError.kt` | `954e9d9851521487ec4adc5233e99dccd9bea783` | 2550 bytes | source | UTF-8 | mode 100644
Declarations: Column@29

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/SummarizedContent.kt` | `6a7d53bee3b1ea77a39f662b7fe9f6c6b4a981f0` | 1859 bytes | source | UTF-8 | mode 100644
Declarations: Column@29; Box@30; SelectionContainer@44

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/SummarizingContent.kt` | `ada2d0735b1b1f469cd1836ff0c9d7917339ad51` | 6675 bytes | source | UTF-8 | mode 100644
Declarations: withStyle@121; SummarizingContentPreview@138; Box@152; Column@153

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/SummaryContentLoaded.kt` | `68f74c42161d8f0bbdfa64b333106038f948eff1` | 9480 bytes | source | UTF-8 | mode 100644
Declarations: Column@63; SummarizedContent@145; SelectionContainer@146; DisclaimerMessage@170

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/gradient/AnimationLayer.kt` | `5c4b35a8351549241042e1781301641b44f2baa5` | 11162 bytes | source | UTF-8 | mode 100644
Declarations: remember@115; GradientAnimationLayer@141; SummaryLoadingGradientPreview@148; Box@161; translate@219; scale@220; rotate@221

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/gradient/BlobPaths.kt` | `dadbb7da0f1181501fcb0c9c8ccb4307e1c299ba` | 1510 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/java/mozilla/components/feature/summarize/ui/gradient/PhaseData.kt` | `6e5b9254bf3831c2f68ba08e0c3acdf488a3016c` | 3315 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ar/strings.xml` | `bea027ada348898ab2b974af31826807ec7268d4` | 8701 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-be/strings.xml` | `30c7ce10ee0697dcfe52698365ef8edc14db665d` | 4316 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-bg/strings.xml` | `f2e0ed6e22a2014ebd91fe0507c26b37b82795ba` | 11951 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-bqi/strings.xml` | `8345dc1b8d8ee007af60abad45b291e4fe9fdde6` | 11535 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ca/strings.xml` | `22be5ab146953ed4adac0af6be157a0a4c574825` | 8363 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-cak/strings.xml` | `4c3548d925d1fd4a2872dcb350d41925b711c3dc` | 11028 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-co/strings.xml` | `3f2cc131d3445862b227e3cd8bec6c4e03ad25d5` | 10815 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-cs/strings.xml` | `1aa29381c85467d4e038dc090332bd49c9481243` | 10791 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-cy/strings.xml` | `e621558c1f2cf2dbca9a99d7d058e59494044e71` | 10591 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-da/strings.xml` | `feee115caaaa765b6605c1fa8492facfdb93d95e` | 10607 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-de/strings.xml` | `a1a93430de9a8e05547a3bf7a0b70772b0ed4663` | 10961 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-dsb/strings.xml` | `e96f84a7d4a1599860abc9599bf2bd55bbe8adef` | 10824 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-el/strings.xml` | `05d427e132b8de693086782e42f0290999d6bb8e` | 11943 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-en-rCA/strings.xml` | `c007b91f3b9fbe26d705757e4efd6530ae0d8cb5` | 10395 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-en-rGB/strings.xml` | `440e36b9cc6c509ba8f07a6b4ce6491982b5b35e` | 10395 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-eo/strings.xml` | `d20235228397c3098f720092adba0f7add4d6230` | 10416 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-es-rAR/strings.xml` | `0eafeb0e1a999078d8b0758fb7b59d8c8ea92b95` | 10704 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-es-rCL/strings.xml` | `4a91ae41f887e10698eeb0584c4c972a2c5d74b9` | 10672 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-es-rES/strings.xml` | `cfb3ecc013158733d238e38c500e9811da7c5d08` | 10690 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-es-rMX/strings.xml` | `ff940c52a52e20cf642f004cf4d1db97fce3ff32` | 10669 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-es/strings.xml` | `cfb3ecc013158733d238e38c500e9811da7c5d08` | 10690 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-eu/strings.xml` | `a2eb3f795b4768adff2e299c2b2ce2548120e428` | 10661 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-fa/strings.xml` | `c150d7404c87e6fdb00cdfc592ccc9c917e8af24` | 11712 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-fi/strings.xml` | `42b9bfde6cabfbdb07f4fa34266bc46e7e6136a7` | 10755 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-fr/strings.xml` | `d604e17a42a26384da35859d3dd5f5cffe333a72` | 10843 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-fur/strings.xml` | `b3cb66d96040c218401c9356477ff8eb2ac080ba` | 8341 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-fy-rNL/strings.xml` | `ebe06af2dc5b8f517946dd469feffc5d66e12945` | 10622 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-gl/strings.xml` | `057437d4f3ee209c3e4fa79350f8358d6f93296c` | 10589 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-gn/strings.xml` | `b36415c82d850c6b2d13eaacaaba4ef0db8371e5` | 10670 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-hi-rIN/strings.xml` | `a8f4ed77bf194b5a30b4afdce98538f0ed1a0134` | 13142 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-hr/strings.xml` | `1df4656c025f5adee64ab0283ea47678a46aff03` | 8973 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-hsb/strings.xml` | `8af0120f337eeca7da2926463abcfe6b797890a2` | 10713 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-hu/strings.xml` | `43b787c2524807b72b99797d89bd7c187d9faca6` | 10838 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-hy-rAM/strings.xml` | `c7b939b00337d8dcc4664d11f511513acf212e0f` | 11892 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ia/strings.xml` | `1b880d82f30f3cbb9e21f821c84bd66af29b2361` | 10567 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-in/strings.xml` | `f05b594162d60ca5c4e69ae114ab5cd09b49698d` | 10631 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-is/strings.xml` | `c32d850d13c77813b6a05f2ca204634770405986` | 10833 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-it/strings.xml` | `88d048e1d27d95983146455eec5a09d99ad14aa4` | 10779 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-iw/strings.xml` | `50fc9c93edb730f6a13d4a56230c6ab7405dced6` | 11190 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ja/strings.xml` | `f124576b36103a0dd7abe9e2dd142aa974c28ab2` | 10922 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ka/strings.xml` | `8b2f6a394370aa09b56462f52d5cbb3cf6fe4b7f` | 12958 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-kk/strings.xml` | `f28bcc1638457b493c584bb696af20a0a0c55377` | 11997 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-km/strings.xml` | `9b330fd3a862b3a5b4efaaa543c1dae39843f148` | 3700 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ko/strings.xml` | `4cdf7d4f5b4ff8dcadbc8cd7726bae263f984bea` | 10805 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-lv/strings.xml` | `8cde3f5e1d86a2b338da11729baf1994e24d3b31` | 3321 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ml/strings.xml` | `5843aa7683143a4ffbf61beaeab0c922080f8f2c` | 5001 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-nb-rNO/strings.xml` | `6809138ad73025d9d2b3b2acea465a422eced8d0` | 10509 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-nl/strings.xml` | `1e1bd45007c781e962b3631b8175c80e4ad58f7b` | 10686 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-nn-rNO/strings.xml` | `1fa37e25ae054d62a83138b68c42c21a869de7dd` | 10551 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-oc/strings.xml` | `ef6bd135895d9e39644294bec2b5ac77dabd9555` | 6159 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-om/strings.xml` | `c22ed76744431b8c6e4a6e1cd8602efcccd0ab5f` | 7483 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-pa-rIN/strings.xml` | `ea7c72e19bf9c2fbb0a69df5a3704b5863e39b5c` | 12437 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-pl/strings.xml` | `c6f7f7efb438d5604e9230ef93cd7f7959c9744d` | 10831 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-pt-rBR/strings.xml` | `57839376f7a278e0c1f729027fc5b666ec27692e` | 10659 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-pt-rPT/strings.xml` | `29ec4db320f303c0913cc276cde9eafd0ad91469` | 10686 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-rm/strings.xml` | `e0dfe94e0e6ed6954371ed4a457e6564510861fc` | 8402 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ro/strings.xml` | `7d1e309afccd5bf3dbc221be1931f9a67a925d01` | 10728 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ru/strings.xml` | `67201a867d9f3167abf00d339ae8f58e53d71d76` | 12075 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sat/strings.xml` | `6c02b26c2dc87d258de69e4d9683054d0c48dd6b` | 12867 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sc/strings.xml` | `e44f3d7d3c4809bb4bc12b5a126bed8c42d8172e` | 9215 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sk/strings.xml` | `46e05a6f457398482bb793e5b639e5cbc02a0fa4` | 10834 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sl/strings.xml` | `180ddcc1a9e77d89e6cf7bf6798050915b491447` | 9001 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sr/strings.xml` | `4cd34c63747108c5c383565d470aec5dc8e74c69` | 11743 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-sv-rSE/strings.xml` | `6943056de8f3ef807459bdfea531fbb367184045` | 10681 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-tg/strings.xml` | `7e77804ba5a007c4be43098386de3b78ca57c179` | 12482 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-th/strings.xml` | `dea251664491a75da725bc7a686c2fe2181dc82f` | 10004 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-tr/strings.xml` | `3565031531e63b2556d29a2e3853e5dee26bdc2f` | 10694 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-trs/strings.xml` | `a4d2fc10b827f2288044c086ba5f3fa8aebe29a0` | 9038 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-ug/strings.xml` | `35acf5304fe40805ef052d5230f6a669479d3766` | 11814 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-uk/strings.xml` | `287511c57e3a5b91b916f31bf76e37bd6ceab30e` | 11964 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-vi/strings.xml` | `57c326b17445cc58c4fd4326acb40e1c4d624655` | 11079 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-zh-rCN/strings.xml` | `9bab86e7158c8a4cdcfb6b9a0878b0f3b51d6b12` | 10460 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values-zh-rTW/strings.xml` | `cd6749d27fc19cd0624d4dcf8a78cd6a4e0c123e` | 10486 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values/static_strings.xml` | `e4adf208cde6dccfa40865317acc1d31984e646b` | 656 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/main/res/values/strings.xml` | `3f84cffd0cfd79f4ad5899d593cb4184cd1d8e9d` | 10683 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/PageSummaryFeatureTest.kt` | `fc4ee5c57f571a4a41e196d7da8ca1ccaa537a57` | 1697 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PageSummaryFeatureTest@15

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/SummarizationStoreTest.kt` | `6824cfe1c855dc1dee6e75ec75910825eb4c9b08` | 59242 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FakeAttestationFailure@57; FakeAuthenticationRequired@59; SummarizationStoreTest@61; setUp@69

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/content/ContentProviderTest.kt` | `d6f7de74721f690fe1ddbaec37c57c2106c27a88` | 2067 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ContentProviderTest@12

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/ext/FlowTest.kt` | `049ab3e5c0e551d5b8ea5d3b8b5e29b8c441855c` | 3344 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FlowTest@21

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/settings/PageSummariesSettingsMiddlewareTest.kt` | `491a66f61d245c37cfc7f7553ee87207f570fe29` | 5958 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PageSummariesSettingsMiddlewareTest@19

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/settings/PageSummariesSettingsReducerTest.kt` | `e31f7e8cc1e42cfca107cb2a50d991e520d7d55c` | 3855 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PageSummariesSettingsReducerTest@11

`mobile/android/android-components/components/feature/summarize/src/test/java/mozilla/components/feature/summarize/settings/SummarizationSettingsTest.kt` | `12b44551bd4e416bf352f146347744b1190e341a` | 2360 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SummarizationSettingsTest@15

`mobile/android/android-components/components/feature/syncedtabs/README.md` | `433b7a96de85216fb6043175733fd23a04a31b9a` | 1249 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/build.gradle` | `52ad716538549d8c157529dcec5b6319822e268b` | 1666 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/ClientTabPair.kt` | `aee4f9e6d7ab8dd88a3e22d90d57b5175db1a341` | 578 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/SyncedTabsAutocompleteProvider.kt` | `54e53501e4bacdd8fe59945a5578cc0f5c77410e` | 2046 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsAutocompleteProvider@28

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/SyncedTabsFeature.kt` | `80201fedd27522ef86819a08f518da8e5bd7364e` | 3224 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsFeature@39; start@72; stop@77

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/SyncedTabsStorageSuggestionProvider.kt` | `33dd6eea6c2241c3910ca4a9387492072887ccee` | 3746 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsStorageSuggestionProvider@24; when@66

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/commands/GlobalSyncedTabsCommandsProvider.kt` | `85b90e027b7f2285b5431602be72bcc286739696` | 1011 bytes | source | UTF-8 | mode 100644
Declarations: initialize@19; requireNotNull@24

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/commands/SyncedTabsCommands.kt` | `2fae9ad529c37b207f019ed33137f464d9f58e71` | 2503 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsCommands@21

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/commands/SyncedTabsCommandsFlushScheduler.kt` | `dc78d9c377548459382fa43c0698a108a7bf4d82` | 2460 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsCommandsFlushScheduler@27; requestFlush@33; cancelFlush@43

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/commands/SyncedTabsCommandsFlushWorker.kt` | `2fd4a9888a7478027eb3aff7291f45e4d756ed2f` | 1187 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsCommandsFlushWorker@18; when@22

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/controller/DefaultController.kt` | `732650c7cf3ab43ab79cd81b315a75ff9ddc3b79` | 2646 bytes | source | UTF-8 | mode 100644
Declarations: refreshSyncedTabs@32; withContext@38; withContext@49; syncAccount@56

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/controller/SyncedTabsController.kt` | `1aa7ed82c36b520165efc84cc398c31e073bb0b8` | 1170 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsController@15

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/ext/SyncedTabsStorage.kt` | `9085b5c2e00a7a2837c1f692189ef6931e26df6b` | 1537 bytes | source | UTF-8 | mode 100644
Declarations: getSyncedDeviceTabs@23

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/facts/SyncedTabsFacts.kt` | `54d0cb088f462537e5e37f0b7ab170d7f97ea6a6` | 1195 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsFacts@13

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/interactor/DefaultInteractor.kt` | `a7826ff55990c5f7d52ad936de78eaed3c8dead9` | 924 bytes | source | UTF-8 | mode 100644
Declarations: start@17; stop@21; onTabClicked@25; onRefresh@29

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/interactor/SyncedTabsInteractor.kt` | `042cd2c1564e9c7e4c34d127d981e6c6a3b9840e` | 788 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsInteractor@13

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/presenter/DefaultPresenter.kt` | `cbe3ff080afb6a19c8c9b126caf5403eef8957fe` | 6063 bytes | source | UTF-8 | mode 100644
Declarations: start@52; stop@92; onLoggedOut@112; onAuthenticated@116; onAuthenticationProblems@122; refresh@138; onIdle@153; onError@161; onStarted@165

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/presenter/SyncedTabsPresenter.kt` | `3f714651e6f3ecaa21fc0e3def47772d272f895a` | 907 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsPresenter@16

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/storage/SyncedTabsProvider.kt` | `fce57bfda41e5349fef8e699e4321922f870fdc5` | 572 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsProvider@10

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/storage/SyncedTabsStorage.kt` | `ad4a6ee40e7ed2bb8e124c9886e7fcde8edc24a0` | 4877 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsStorage@40; start@52; stop@80

`mobile/android/android-components/components/feature/syncedtabs/src/main/java/mozilla/components/feature/syncedtabs/view/SyncedTabsView.kt` | `f1807aa9362faf7794490b9f9893c4f8386d9ac0` | 2186 bytes | source | UTF-8 | mode 100644
Declarations: SyncedTabsView@12; Listener@31; class@41

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/SyncedTabsAutocompleteProviderKtTest.kt` | `acf84c8f7d609a0b124dfe480334d0642d2186c4` | 2958 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsAutocompleteProviderKtTest@22

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/SyncedTabsFeatureTest.kt` | `17aab9696b167c0467621911883ddbbc9c62390d` | 1885 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsFeatureTest@19; start@44; stop@52

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/SyncedTabsStorageSuggestionProviderTest.kt` | `d2979c442e645237ed62f0a4f25b536919857c41` | 4140 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsStorageSuggestionProviderTest@21; setup@28

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/commands/CloseTabsCommandSenderTest.kt` | `6a944a4ce79838838750e1f312729dc120c7c450` | 4639 bytes | test-path,source | UTF-8 | mode 100644
Declarations: CloseTabsCommandSenderTest@27; setUp@60

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/commands/SyncedTabsCommandsFlushSchedulerTest.kt` | `ec54eba2d5f959b157101af63f766f89f633d7e7` | 4291 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsCommandsFlushSchedulerTest@30; setUp@35; tearDown@46

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/commands/SyncedTabsCommandsFlushWorkerTest.kt` | `ce4c503c2afec7b7fd1cf5997e95ad28a8ae5111` | 2086 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsCommandsFlushWorkerTest@23; setUp@27

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/controller/DefaultControllerTest.kt` | `f4628328e4fb2d794d4c84786537259a6275e388` | 6493 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DefaultControllerTest@26; runTest@34; runTest@54; runTest@83; runTest@112; runTest@145

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/ext/SyncedTabsStorageKtTest.kt` | `6998a1de83fe76b042c338e1b0ad42d0b4fbe447` | 2978 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsStorageKtTest@17

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/facts/SyncedTabsFactsTest.kt` | `5db872acc03fa58e03a44298c50dce4a87518489` | 1003 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsFactsTest@13

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/helper/SyncedTabsProvider.kt` | `262440f675c4ffee284a4c1c6d517982fea9cc8e` | 2542 bytes | test-path,source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/interactor/DefaultInteractorTest.kt` | `7d1ba51bce5b4d5263210cbaa248b23ef2bbb259` | 2700 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DefaultInteractorTest@18; TestSyncedTabsView@101; onError@104; displaySyncedTabs@106

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/presenter/DefaultPresenterTest.kt` | `b851e81d5c5230352c8a805f9d138b278782e8e2` | 10746 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DefaultPresenterTest@29

`mobile/android/android-components/components/feature/syncedtabs/src/test/java/mozilla/components/feature/syncedtabs/storage/SyncedTabsStorageTest.kt` | `87cd114d4ac0be8d2b08e069fb847db2a44328a8` | 21462 bytes | test-path,source | UTF-8 | mode 100644
Declarations: SyncedTabsStorageTest@41; setup@48; runTest@78; runTest@124; runTest@168; runTest@223; runTest@311; runTest@377; runTest@430; runTest@480

`mobile/android/android-components/components/feature/syncedtabs/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/syncedtabs/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/README.md` | `cef17fbcbcfe6d8de837cdaee010a5beb737a72f` | 655 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/build.gradle` | `b92fd0ce997744ed881a74b63ba3f53ce3ecf2ea` | 2584 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/schemas/mozilla.components.feature.tab.collections.db.TabCollectionDatabase/1.json` | `e125b8a11f431602bd63c44b084744d239174bdf` | 3636 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/androidTest/java/mozilla/components/feature/tab/collections/TabCollectionStorageTest.kt` | `8b4cba40114d003fb73550bb97172593cce6b031` | 15905 bytes | source | UTF-8 | mode 100644
Declarations: TabCollectionStorageTest@30; setUp@38; tearDown@49; testCreatingCollections@56; testAddingTabsToExistingCollection@83; testRemovingTabsFromCollection@114; testRenamingCollection@140; testRemovingCollection@155; testCreatingCollectionAndRestoringState@175; testRemovingAllCollections@393; FakeEngine@423; FakeEngineSessionState@453; writeTo@454; matches@461

`mobile/android/android-components/components/feature/tab-collections/src/androidTest/java/mozilla/components/feature/tab/collections/db/TabCollectionDaoTest.kt` | `6aac12e76d473667da2c88a9e51544177f5e43d3` | 5946 bytes | source | UTF-8 | mode 100644
Declarations: TabCollectionDaoTest@21; setUp@32; tearDown@39; testInsertingAndReadingCollections@45; testUpdatingCollections@64; testRemovingCollections@88; testCountingTabCollections@142

`mobile/android/android-components/components/feature/tab-collections/src/androidTest/java/mozilla/components/feature/tab/collections/db/TabDaoTest.kt` | `4a489ee40affbacc0c851dc329eba2769503f801` | 4048 bytes | source | UTF-8 | mode 100644
Declarations: TabDaoTest@18; setUp@28; testAddingTabsToCollection@36; testRemovingTabFromCollection@78; tearDown@121

`mobile/android/android-components/components/feature/tab-collections/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/Tab.kt` | `b2f7512130979d627c53790d7c104c73b2e69e02` | 1141 bytes | source | UTF-8 | mode 100644
Declarations: Tab@12

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/TabCollection.kt` | `4e5c1ca9789b50e1e62ec5cd2349d480280cacad` | 1794 bytes | source | UTF-8 | mode 100644
Declarations: TabCollection@12

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/TabCollectionStorage.kt` | `b58f2bde2a566baa9d7da7f7563b77a76755bed6` | 6117 bytes | source | UTF-8 | mode 100644
Declarations: TabCollectionStorage@23; removeTabFromCollection@78; renameCollection@117; removeCollection@127; removeAllCollections@138

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/adapter/TabAdapter.kt` | `a447d8a9beb38a45e1bbddb73937d5bf117a5653` | 1390 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/adapter/TabCollectionAdapter.kt` | `e8c6d97b92c7f65683d0fcaba5a591d9cf0830e6` | 2395 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabCollectionDao.kt` | `33ab595fd910e13f9f3096467928dbf975ac9ddc` | 1734 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabCollectionDatabase.kt` | `4c2d4db8af75352e1397194bc7190a354ac20b84` | 1230 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabCollectionEntity.kt` | `40a1b9bc88f43528305c6b6d2f3d1ca7f21dd8c2` | 803 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabCollectionWithTabs.kt` | `06d451ca910af28a012d7307e4b8811c955b637c` | 649 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabDao.kt` | `0ca6a5c91d38d13c02d6e3acb12fbb19e53e65d6` | 526 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/db/TabEntity.kt` | `565fbd6611b4968a153ceea3f281be8d16295029` | 1658 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/main/java/mozilla/components/feature/tab/collections/ext/TabsUseCases.kt` | `1fe29056e3e8c726a17d8c8f4f7e98d438c0bb04` | 2701 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/test/java/mozilla/components/feature/tab/collections/ext/TabsUseCasesKtTest.kt` | `7b7f11cd503b3b3262e02c68260ae8c910bd0fe4` | 4903 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TabsUseCasesKtTest@28; setup@40

`mobile/android/android-components/components/feature/tab-collections/src/test/resources/mockito-extensions/org.mockito.plugins.MockMaker` | `cf1c399ea81e3cf7da759acdf4af7504dfa87cfb` | 96 bytes | test-path,data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tab-collections/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/README.md` | `640b6c88bec381ee3d6b9c45b2c6bbe72fe453bc` | 1980 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/build.gradle` | `61cf898546c86dc12d20bd4383879e58eba1d050` | 1007 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/java/mozilla/components/feature/tabdata/coordinator/TabDataCoordinator.kt` | `a3fdbd1734d3e33b6c03de42da63ec7c7cd38c70` | 8907 bytes | source | UTF-8 | mode 100644
Declarations: TabDataCoordinator@45; DefaultTabDataCoordinator@67; initialize@94; withContext@97

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/java/mozilla/components/feature/tabdata/coordinator/data/Tab.kt` | `64d60d9ad327c2ce67acff8f4383bf0212768028` | 972 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/java/mozilla/components/feature/tabdata/coordinator/data/TabGroup.kt` | `d58a18c7781ed724c2288df21b60a86b32e1994d` | 877 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/java/mozilla/components/feature/tabdata/coordinator/data/TabsSnapshot.kt` | `5dc1daef3f7746c6a43d82eeb62a05f4bd5e648a` | 1563 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabdata-coordinator/src/main/java/mozilla/components/feature/tabdata/coordinator/repository/TabRepository.kt` | `6db494d099bff50f7a00236b3a2245261eaa18d4` | 1083 bytes | source | UTF-8 | mode 100644
Declarations: TabRepository@11

`mobile/android/android-components/components/feature/tabdata-coordinator/src/test/java/mozilla/components/feature/tabdata/coordinator/DefaultTabDataCoordinatorTest.kt` | `555162737b3d3aa5fe85d389e5c727bec1248a24` | 21115 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DefaultTabDataCoordinatorTest@26

`mobile/android/android-components/components/feature/tabdata-coordinator/src/test/java/mozilla/components/feature/tabdata/coordinator/fakes/FakeTabRepository.kt` | `ae45734b384c6031e92349549289da1ff83bb608` | 1158 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FakeTabRepository@16

`mobile/android/android-components/components/feature/tabgroups-storage/README.md` | `a085680b261d13b9e45fa185b4df89209aeec818` | 1410 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/build.gradle` | `38a663686c6ee200bd2ffb324cf83bb1f22c0c6a` | 1709 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/schemas/mozilla.components.feature.tabgroups.storage.database.TabGroupDatabase/1.json` | `f48a3949c474f1db351faa560691bbef0dd7be34` | 2266 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/schemas/mozilla.components.feature.tabgroups.storage.database.TabGroupDatabase/2.json` | `82af7749a705ed036d55f4a6e07b3b5575e9f3da` | 2266 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/data/TabGroupData.kt` | `774db637a5bd88764c558117abf9141ae7112696` | 1499 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/data/TabGroupDataTransforms.kt` | `c127e425a9964af1f25e8ecd522b48a13f68f1a3` | 1025 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/StoredTabGroup.kt` | `bd3de9d5be432ecd1ed05a7938fc67a158e4029f` | 1063 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/StoredTabGroupDao.kt` | `089848d58457e344423b078f52a7a8bf8056d9fe` | 2296 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/StoredTabGroupWithAssignments.kt` | `1a8b158cfacdab42e22df2265a976a7a5494e8ec` | 731 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/TabGroupAssignment.kt` | `285be754c79ea63afa892b37dfd52ca75c03e774` | 758 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/TabGroupAssignmentDao.kt` | `7d81b32ce7453bef33595e670aa89b55c5650e54` | 2902 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/TabGroupDatabase.kt` | `ef979a5329f3b217dff254fc547a4aa4420ac8f7` | 1016 bytes | source | UTF-8 | mode 100644
Declarations: migrate@24

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/database/TabGroupOperationsDao.kt` | `24742083b8d5a2b8d8523892d0104f21c627ead2` | 3603 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/main/java/mozilla/components/feature/tabgroups/storage/repository/TabGroupRepository.kt` | `9f421a4d39bf3308d8b8d14af0d7e46ddd226797` | 10032 bytes | source | UTF-8 | mode 100644
Declarations: TabGroupRepository@25; DefaultTabGroupRepository@87; withContext@165

`mobile/android/android-components/components/feature/tabgroups-storage/src/test/java/mozilla/components/feature/tabgroups/storage/data/TabGroupDataTransformsTest.kt` | `21d655a1fb04e914ed72a919ba1b4f74031cd07b` | 2098 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TabGroupDataTransformsTest@11

`mobile/android/android-components/components/feature/tabgroups-storage/src/test/java/mozilla/components/feature/tabgroups/storage/database/TabGroupDatabaseMigrationTest.kt` | `7985e72ead62c8812816ccea11b9d1f89100f46f` | 2057 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TabGroupDatabaseMigrationTest@17; migrate1To2@29

`mobile/android/android-components/components/feature/tabgroups-storage/src/test/java/mozilla/components/feature/tabgroups/storage/repository/DefaultTabGroupRepositoryTest.kt` | `671ff39a866423c1e8577f1c39dc89e5a00b2d8e` | 24154 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DefaultTabGroupRepositoryTest@31; setup@48; teardown@66; List@198; List@208; List@341; List@580; List@581; runTest@598; List@601

`mobile/android/android-components/components/feature/tabgroups-storage/src/test/resources/robolectric.properties` | `3f67ea5ac1bf1ea65d7f53061c18c644b51ee36a` | 7 bytes | test-path,localization-or-properties | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/testFixtures/kotlin/mozilla/components/feature/tabgroups/storage/database/TabGroupDatabaseTestFixtures.kt` | `89491957170f709363ece4fca7806aea9eb3f648` | 760 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabgroups-storage/src/testFixtures/kotlin/mozilla/components/feature/tabgroups/storage/fakes/FakeTabGroupRepository.kt` | `7e9f9d86983f04c2e45967cc5d006758b9dcbcd1` | 5735 bytes | source | UTF-8 | mode 100644
Declarations: FakeTabGroupRepository@14

`mobile/android/android-components/components/feature/tabgroups-storage/src/testFixtures/kotlin/mozilla/components/feature/tabgroups/storage/repository/TabGroupRepositoryTestFixtures.kt` | `091b64f150440e156c3ecfc1cb7fcd09f89ae2eb` | 1000 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/README.md` | `8cc92ed7814506654927a5b79bd7b7e3cb066fd7` | 754 bytes | documentation | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/build.gradle` | `a85e65fb5b2c73e323403a50494a55d1873745de` | 1943 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/lint-baseline.xml` | `355b2f37dc1e93f04bc27439f32ce02414b10760` | 188 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/proguard-rules.pro` | `f1b424510da51fd82143bc74a0a801ae5a1e2fcd` | 751 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/AndroidManifest.xml` | `e16cda1d3446263d2ba0bd8cc1d55772caac5f99` | 225 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/CustomTabsUseCases.kt` | `c4aa9e335cf4c5f7902da4cc348b2c0f3db2154f` | 4664 bytes | source | UTF-8 | mode 100644
Declarations: CustomTabsUseCases@19; AddCustomTabUseCase@24; AddWebAppTabUseCase@54; RemoveCustomTabUseCase@82; MigrateCustomTabUseCase@95

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/LastTabFeature.kt` | `9698f371016090afb215410829b4c6711a109588` | 2029 bytes | source | UTF-8 | mode 100644
Declarations: LastTabFeature@16

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/TabsUseCases.kt` | `4711b9e001ae3cb9ffce1c5806cc113c75b55069` | 25716 bytes | source | UTF-8 | mode 100644
Declarations: TabsUseCases@36; SelectTabUseCase@42; DefaultSelectTabUseCase@47; invoke@49; RemoveTabUseCase@55; DefaultRemoveTabUseCase@84; AddNewTabUseCase@114; RemoveTabsUseCase@224; RemoveAllTabsUseCase@237; RemoveNormalTabsUseCase@249; RemovePrivateTabsUseCase@257; UndoTabRemovalUseCase@265; RestoreUseCase@273; withContext@333; withContext@340; withContext@356; SelectOrAddUseCase@371; DuplicateTabUseCase@446; MoveTabsUseCase@491; MigratePrivateTabUseCase@544; require@556

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/WindowFeature.kt` | `7e54169967dca8f2109b6272b199523c179d821c` | 3307 bytes | source | UTF-8 | mode 100644
Declarations: WindowFeature@20; start@29; when@39; consumeWindowRequest@41; consumeWindowRequest@49; stop@75

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/ext/BrowserState.kt` | `621e3242a10d5f902b4fd6b2f0d503d3fb99c832` | 1291 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/ext/TabSessionState.kt` | `a9df1501e7b821e16083953153d2044aa4942446` | 1088 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/tabstray/Tab.kt` | `05554ad90a2a5c0a832d2833ca4c351e5437aea6` | 1568 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/tabstray/TabList.kt` | `4e2816370091b0d4552092f6630c8df948fc2c46` | 419 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/tabstray/Tabs.kt` | `45058f5918a5bf18629712f19d5a961f975484d4` | 710 bytes | source | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/tabstray/TabsFeature.kt` | `1355ae7417c52263759170bdd2f1265fe136ca03` | 1953 bytes | source | UTF-8 | mode 100644
Declarations: TabsFeature@20; start@35; stop@39; filterTabs@49

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/tabstray/TabsTrayPresenter.kt` | `004aeb7fce70116979061ad89bd9ca951d36a2c2` | 2129 bytes | source | UTF-8 | mode 100644
Declarations: TabsTrayPresenter@25; start@35; stop@39

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/toolbar/TabCounterToolbarButton.kt` | `29750dbf1faf5a3b2b4c2ae166000cf3c40d0ae9` | 5319 bytes | source | UTF-8 | mode 100644
Declarations: onViewAttachedToWindow@80; onViewDetachedFromWindow@85; updateCount@135

`mobile/android/android-components/components/feature/tabs/src/main/java/mozilla/components/feature/tabs/toolbar/TabsToolbarFeature.kt` | `a15745bd506f43d0a110f1e5ff96c029f9a597d9` | 1798 bytes | source | UTF-8 | mode 100644
Declarations: TabsToolbarFeature@20

`mobile/android/android-components/components/feature/tabs/src/main/res/values-ab/strings.xml` | `e29f29465edbfab19f20700abb82276fb8e305ee` | 491 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-am/strings.xml` | `d99b742826d1e725d84c09442cf37098fd00ac36` | 478 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-an/strings.xml` | `eeaa88fa8ab804e877d5a2f8fb923aab30f59d1b` | 478 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-ar/strings.xml` | `ca1401fa217a8319b4b8a6cc6cd114fb4deeb1d3` | 487 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-ast/strings.xml` | `a41910d5bbfa9a728c5f28980061bd163605bfee` | 480 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-az/strings.xml` | `69062e3958d5cef21716b76f951db7a0b137fb06` | 480 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-azb/strings.xml` | `4f1391ebca14410148693e51ffba3d3aba57ffc2` | 484 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-ban/strings.xml` | `0b6e339ab48d28d7c9fe92f6bdc3331ce293c1c4` | 472 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-be/strings.xml` | `db11e3d5a562e7df7784dba83870e3fb4aea1efc` | 481 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-bg/strings.xml` | `57e695697e83545abb33a54e158d0ba913bd7094` | 483 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-bn/strings.xml` | `6e7cd9853daa7d36a021ea7f84cd68444374a183` | 496 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-bqi/strings.xml` | `9840947cf84d115cf0ed387964cda5b633c98414` | 482 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-br/strings.xml` | `7c98fb40486e73939ec808edd5e2ee975e7576cc` | 479 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-brh/strings.xml` | `9b4c01d72f37f75296e0c4f03912e8f6c25ca970` | 480 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-bs/strings.xml` | `0d09a010b2e3edd44320e7d0970bc174cf1633eb` | 475 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-ca/strings.xml` | `e05d5d09355c73a38ceb29a3ac325763e5e75489` | 478 bytes | data-or-other | UTF-8 | mode 100644

`mobile/android/android-components/components/feature/tabs/src/main/res/values-cak/strings.xml` | `b6af83f86243ce8a62f3930759b346b75d2ac082` | 479 bytes | data-or-other | UTF-8 | mode 100644

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.

## Retrieval correction

This copy preserves the source map in [bcacb335-d717-4b28-b858-f2520b4d3ce0.md](bcacb335-d717-4b28-b858-f2520b4d3ce0.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `98ce839b4b01243a83e64c9e51f0bdfbd9c64dc3d91080051f5ca0954f2acc67`.
