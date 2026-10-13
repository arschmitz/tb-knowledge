<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["dom"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["93718bce0bb14f2e440f1e0bc261229acffc720b7be489483a0097e05dfc3fd8"],"sourceAt":"2026-10-13T04:14:46.642314+00:00","correctionOf":"notes/60125c24-f1af-494b-a8ca-38eb76f470c1.md"}} -->
# firefox/dom structural source map 112

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`dom/media/driftcontrol/plot.py` | `b628fd253b4522b4c95f0862856335f145d65ec9` | 5614 bytes | source | UTF-8 | mode 100755
Declarations: main@32
Dependencies: bokeh.io@26; bokeh.layouts@27; bokeh.models@28; bokeh.plotting@29

`dom/media/eme/CDMCaps.cpp` | `cd1c9704143b2c1999001bfa378b342eee0ccc32` | 3546 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; IsUsableStatus@20; CDMCaps::IsKeyUsable@26; CDMCaps::RemoveKeysForSession@100
Dependencies: mozilla/CDMCaps.h@5; SamplesWaitingForKey.h@7; mozilla/EMEUtils.h@8; nsThreadUtils.h@9

`dom/media/eme/CDMCaps.h` | `cd8fdc75b3993d86ec4f2f22e60e882a76a601ac` | 2477 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; CDMCaps@19; KeyStatus@28; mId@31; mStatus@35; WaitForKeys@64; mKeyId@66
Dependencies: SamplesWaitingForKey.h@8; mozilla/Monitor.h@9; mozilla/dom/BindingDeclarations.h@10; mozilla/dom/MediaKeyStatusMapBinding.h@11; nsString.h@12; nsTArray.h@13

`dom/media/eme/CDMProxy.h` | `30e66d07755c263cf4615796662cda5ab6513a5e` | 11231 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; ErrorResult@17; MediaRawData@18; ChromiumCDMProxy@19; RemoteCDMProxy@20; WMFCDMProxy@22; eme@25; DecryptStatus@26; DecryptResult@36; mStatus@38; MozPromise@43; CDMKeyInfo@46; mKeyId@49; mKeyId@53; CDMKeyInfo@57; int64_t@72; CDMProxy@78; dom@80; class@149; class@154; Capabilites@235; AsChromiumCDMProxy@250; AsWMFCDMProxy@253; AsRemoteCDMProxy@256; IsHardwareDecryptionSupported@258; mMainThread@269; MainThreadOnlyRawPtr@277; MainThreadOnlyRawPtr@279; IsNull@283; Clear@288
Dependencies: mozilla/CDMCaps.h@8; mozilla/DataMutex.h@9; mozilla/MozPromise.h@10; mozilla/dom/MediaKeyMessageEvent.h@11; mozilla/dom/MediaKeySessionBinding.h@12; mozilla/dom/MediaKeys.h@13; nsIThread.h@14

`dom/media/eme/DecryptorProxyCallback.h` | `acf5676c3467aa938943f18212b962e52419f750` | 1949 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ErrorResult@13; DecryptorProxyCallback@16
Dependencies: mozilla/CDMProxy.h@8; mozilla/dom/MediaKeyMessageEventBinding.h@9; mozilla/dom/MediaKeyStatusMapBinding.h@10

`dom/media/eme/DetailedPromise.cpp` | `589013f09160de3369c51ac9079f649134e233f6` | 1915 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; Promise@15; DetailedPromise::MaybeReject@32
Dependencies: DetailedPromise.h@5; VideoUtils.h@7; mozilla/dom/DOMException.h@8; nsPrintfCString.h@9

`dom/media/eme/DetailedPromise.h` | `cc4154bc811389c13825af44b3fcef3a8a005af3` | 3074 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; DetailedPromise@18; MaybeResolve@25; MaybeRejectWithTypeError@54; MaybeRejectWithTypeError@61; MaybeRejectWithRangeError@68; MaybeRejectWithRangeError@75; eStatus@84
Dependencies: EMEUtils.h@8; mozilla/dom/Promise.h@9; mozilla/dom/DOMExceptionNames.inc@47

`dom/media/eme/EMEOriginID.h` | `7daf95e9b652180d964cfee4422be1940140ff49` | 1647 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12
Dependencies: mozilla/StaticPrefs_media.h@8; mozilla/media/MediaChild.h@9; nsIPrincipal.h@10

`dom/media/eme/EMEUtils.cpp` | `e6515f6fc9f24206d418e2f22a76e0d0fc79fd58` | 8913 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@22; GetEMELog@24; GetEMEVerboseLog@29; IsClearkeyKeySystem@40; IsWidevineKeySystem@48; IsMediaFoundationCDMPlaybackEnabled@53; IsPlayReadyEnabled@59; IsPlayReadyKeySystemAndSupported@64; IsWidevineHardwareDecryptionEnabled@73; IsWidevineExperimentKeySystemAndSupported@78; IsWMFClearKeySystemAndSupported@86; KeySystemToProxyName@97; IsHardwareDecryptionSupported@138; DoesKeySystemSupportClearLead@199; DoesKeySystemSupportHardwareDecryption@228; GetOrigin@257
Dependencies: mozilla/EMEUtils.h@5; KeySystemConfig.h@7; MediaData.h@8; jsfriendapi.h@9; mozilla/StaticPrefs_media.h@10; mozilla/dom/BufferSourceBinding.h@11; mozilla/dom/Document.h@12; mozilla/dom/KeySystemNames.h@13; mozilla/dom/UnionTypes.h@14; nsContentUtils.h@15; nsIScriptObjectPrincipal.h@16; mozilla/PMFCDM.h@19

`dom/media/eme/EMEUtils.h` | `9ce524297f33db5e5e5d20b1a7e8a77a86db61e6` | 3396 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; class@17; MFCDMCapabilitiesIPDL@19; KeySystemConfig@21; dom@23; Document@24; CDMType@78
Dependencies: mozilla/Logging.h@8; mozilla/dom/BufferSourceBindingFwd.h@9; mozilla/dom/MediaKeyStatusMapBinding.h@10; mozilla/dom/MediaKeySystemAccessBinding.h@11; nsString.h@12; nsTArray.h@13

`dom/media/eme/KeySystemConfig.cpp` | `1865f67728d9286090ec9d1c747a9190909a3aaf` | 13576 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@28; KeySystemConfig::Supports@31; gfx::gfxVars::WidevineSupport@35; IsWMFClearKeySystemAndSupported@67; media::MCSInfo::SupportsHardwareDecode@165; IsWidevineExperimentKeySystemAndSupported@218; KeySystemConfig::GetGMPKeySystemConfigs@252; KeySystemConfig::GetDebugInfo@299
Dependencies: KeySystemConfig.h@5; EMEUtils.h@7; GMPUtils.h@8; KeySystemNames.h@9; mozilla/StaticPrefs_media.h@10; mozilla/dom/ChromeUtilsBinding.h@11; mozilla/dom/Promise.h@12; nsPrintfCString.h@13; PDMFactory.h@16; WMFDecoderModule.h@17; MediaCodecsSupport.h@20; mozilla/gfx/gfxVars.h@21; mediafoundation/WMFCDMImpl.h@25

`dom/media/eme/KeySystemConfig.h` | `d9ea68a6ad51f25fc5fc78a0f7049a72f4d312c5` | 10035 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; KeySystemConfigRequest@17; KeySystemConfig@19; ContainerSupport@57; ContainerSupport@60; IsSupported@75; GetDebugInfo@112; ContainsDecryptedOnlyCodec@158; ContainsDecryptedAndDecodedCodec@163; std::any_of@171; class@187; KeySystemConfig@197; KeySystemConfigRequest@247; mIsPrivateBrowsing@253
Dependencies: MediaData.h@8; mozilla/MozPromise.h@9; mozilla/dom/MediaKeySystemAccessBinding.h@10; mozilla/dom/MediaKeysBinding.h@11; nsString.h@12; nsTArray.h@13

`dom/media/eme/KeySystemNames.h` | `e43333cb385db6ed5ce816845996cde7d7399465` | 2223 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16

`dom/media/eme/MediaEncryptedEvent.cpp` | `1ecdc5fc23ee6f3a3706ce59fb0532d3ce8c3cfa` | 3728 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; Event@38; MediaEncryptedEvent::~MediaEncryptedEvent@42; MediaEncryptedEvent::GetInitDataType@89
Dependencies: MediaEncryptedEvent.h@5; js/ArrayBuffer.h@7; jsfriendapi.h@8; mozilla/HoldDropJSObjects.h@9; mozilla/dom/MediaEncryptedEventBinding.h@10; mozilla/dom/MediaKeys.h@11; nsContentUtils.h@12; nsINode.h@13

`dom/media/eme/MediaEncryptedEvent.h` | `c0a3a6c1f0196ad88d1f12bdaa747621bb3ac815` | 1824 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; MediaKeyNeededEventInit@19; MediaEncryptedEvent@21
Dependencies: cstdint@8; js/RootingAPI.h@10; mozilla/AlreadyAddRefed.h@11; mozilla/dom/Event.h@12; nsCycleCollectionParticipant.h@13; nsISupports.h@14; nsStringFwd.h@15; nsTArray.h@16

`dom/media/eme/MediaKeyError.cpp` | `72d7f397a2882d378e368c2f748d5f7309b5e0c1` | 882 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; Event@13; MediaKeyError::SystemCode@19
Dependencies: MediaKeyError.h@5; mozilla/dom/MediaKeyErrorBinding.h@7; nsContentUtils.h@8

`dom/media/eme/MediaKeyError.h` | `c5eeb40d836fdc88105caa0f553d7e20f621c424` | 755 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; MediaKeyError@14
Dependencies: js/TypeDecls.h@8; mozilla/dom/Event.h@9; nsWrapperCache.h@10

`dom/media/eme/MediaKeyMessageEvent.cpp` | `740922965f8c225952945759c8f43998b616398b` | 3586 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; mMessageType@42; MediaKeyMessageEvent::~MediaKeyMessageEvent@46; MediaKeyMessageEvent::AsMediaKeyMessageEvent@48
Dependencies: mozilla/dom/MediaKeyMessageEvent.h@5; js/ArrayBuffer.h@7; js/RootingAPI.h@8; jsfriendapi.h@9; mozilla/HoldDropJSObjects.h@10; mozilla/dom/MediaKeyMessageEventBinding.h@11; mozilla/dom/MediaKeys.h@12; mozilla/dom/Nullable.h@13; mozilla/dom/PrimitiveConversions.h@14; mozilla/dom/TypedArray.h@15; nsContentUtils.h@16

`dom/media/eme/MediaKeyMessageEvent.h` | `4c8fe3079ab1a7d459c02efa9676fee902145c2e` | 1896 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; ErrorResult@17; dom@19; MediaKeyMessageEventInit@21; MediaKeyMessageEvent@23; MessageType@49
Dependencies: js/TypeDecls.h@8; mozilla/dom/Event.h@9; mozilla/dom/MediaKeyMessageEventBinding.h@10; mozilla/dom/TypedArray.h@11; nsCOMPtr.h@12; nsCycleCollectionParticipant.h@13; nsWrapperCache.h@14

`dom/media/eme/MediaKeySession.cpp` | `73f2bb84c0abba54b265fd39131a894b4d28510b` | 24648 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; MediaKeySession::SetSessionId@77; MediaKeySession::~MediaKeySession@88; MediaKeySession::GetError@93; MediaKeySession::GetSessionId@95; MediaKeySession::Expiration@106; MediaKeySession::Closed@108; MediaKeySession::UpdateKeyStatusMap@110; MediaKeySession::KeyStatuses@138; MediaKeySession::Close@466; MediaKeySession::OnClosed@512; MediaKeySession::IsClosed@527; MediaKeySession::Remove@529; MediaKeySession::DispatchKeyError@585; MediaKeySession::DispatchKeyStatusesChange@595; MediaKeySession::Token@607; MediaKeySession::SetExpiration@620; MediaKeySession::GetOnkeystatuseschange@627; MediaKeySession::SetOnkeystatuseschange@631; MediaKeySession::GetOnmessage@635; MediaKeySession::SetOnmessage@639; ToString@643
Dependencies: mozilla/dom/MediaKeySession.h@5; ctime@7; utility@8; GMPUtils.h@10; mozilla/AsyncEventDispatcher.h@11; mozilla/CDMProxy.h@12; mozilla/EMEUtils.h@13; mozilla/Encoding.h@14; mozilla/dom/HTMLMediaElement.h@15; mozilla/dom/KeyIdsInitDataBinding.h@16; mozilla/dom/MediaEncryptedEvent.h@17; mozilla/dom/MediaKeyError.h@18; mozilla/dom/MediaKeyMessageEvent.h@19; mozilla/dom/MediaKeyStatusMap.h@20; mozilla/dom/MediaKeySystemAccess.h@21; nsCycleCollectionParticipant.h@22; nsPrintfCString.h@23; psshparser/PsshParser.h@24

`dom/media/eme/MediaKeySession.h` | `0bd11900f10358f6e673f104696a0ac50d7e2a73` | 4610 bytes | source | UTF-8 | mode 100644
Declarations: JSContext@20; mozilla@22; ErrorResult@23; dom@25; MediaKeySession@26; dom@30; ArrayBufferViewOrArrayBuffer@32; MediaKeyError@33; MediaKeyStatusMap@34; MediaKeySession@38; IsCallable@110
Dependencies: DecoderDoctorLogger.h@8; mozilla/DOMEventTargetHelper.h@9; mozilla/DetailedPromise.h@10; mozilla/Mutex.h@11; mozilla/dom/MediaKeyMessageEventBinding.h@12; mozilla/dom/MediaKeySessionBinding.h@13; mozilla/dom/MediaKeysBinding.h@14; mozilla/dom/Promise.h@15; mozilla/dom/TypedArray.h@16; nsCOMPtr.h@17; nsCycleCollectionParticipant.h@18

`dom/media/eme/MediaKeyStatusMap.cpp` | `59e14050bb6862f79a9b4d8bed827a1b0425b4d1` | 3304 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; mParent@25; MediaKeyStatusMap::GetParentObject@34; MediaKeyStatusMap::Has@66; MediaKeyStatusMap::GetIterableLength@70; MediaKeyStatusMap::GetKeyIDAsHexString@80; MediaKeyStatusMap::GetValueAtIndex@85; MediaKeyStatusMap::Size@90; MediaKeyStatusMap::Update@92
Dependencies: mozilla/dom/MediaKeyStatusMap.h@5; GMPUtils.h@7; mozilla/EMEUtils.h@8; mozilla/dom/BufferSourceBinding.h@9; mozilla/dom/ToJSValue.h@10; mozilla/dom/UnionTypes.h@11; nsPIDOMWindow.h@12

`dom/media/eme/MediaKeyStatusMap.h` | `fc48ee2f7e51d74e698b73cd85520a7efae28593` | 2792 bytes | source | UTF-8 | mode 100644
Declarations: nsPIDOMWindowInner@15; mozilla@17; ErrorResult@18; dom@20; MediaKeyStatusMap@25; KeyStatus@57; mKeyId@59
Dependencies: mozilla/CDMCaps.h@8; mozilla/dom/BufferSourceBindingFwd.h@9; mozilla/dom/MediaKeyStatusMapBinding.h@10; mozilla/dom/TypedArray.h@11; nsCycleCollectionParticipant.h@12; nsWrapperCache.h@13

`dom/media/eme/MediaKeySystemAccess.cpp` | `e77fb05131cef6724939a7eead195c0035016598` | 52280 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@39; mParent@61; MediaKeySystemAccess::GetParentObject@73; MediaKeySystemAccess::GetKeySystem@77; class@92; IsWidevineExperimentKeySystemAndSupported@111; KeySystemConfig::Supports@182; IsMFCDMAllowedByOrigin@261; Filer@266; CodecType@430; IsWidevineKeySystem@468; IsPersistentSessionType@507; GetMajorType@520; GetCodecType@530; IsParameterUnrecognized@558; IsPersistentSessionType@1012; IsPersistentSessionType@1036; EME_LOG@1215; ToCString@1224; ToCString@1231; ToCString@1238; ToCString@1254; ToCString@1266; ToCString@1279
Dependencies: mozilla/dom/MediaKeySystemAccess.h@5; DecoderDoctorDiagnostics.h@7; DecoderTraits.h@8; MP4Decoder.h@9; MediaContainerType.h@10; WebMDecoder.h@11; mozilla/ClearOnShutdown.h@12; mozilla/EMEUtils.h@13; mozilla/Preferences.h@14; mozilla/Services.h@15; mozilla/StaticPrefs_media.h@16; mozilla/dom/Document.h@17; mozilla/dom/KeySystemNames.h@18; mozilla/dom/MediaKeySession.h@19; mozilla/dom/MediaKeySystemAccessBinding.h@20; mozilla/dom/MediaKeySystemAccessManager.h@21; mozilla/dom/MediaSource.h@22; mozilla/dom/PContent.h@23; nsDOMString.h@24; nsIObserverService.h@25; nsMimeTypes.h@26; nsReadableUtils.h@27; nsServiceManagerUtils.h@28; nsUnicharUtils.h@29; PDMFactory.h@32; WMFDecoderModule.h@33; mozilla/gfx/gfxVars.h@36; nsIWindowsMediaFoundationCDMOriginsListService.h@42

`dom/media/eme/MediaKeySystemAccess.h` | `dac6d17a9f465c5c9bf3042ba1858298f8ebeb1f` | 2716 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; DecoderDoctorDiagnostics@18; ErrorResult@19; dom@21; IPCOriginStatusEntry@23; MediaKeySystemAccessRequest@24; MediaKeySystemAccess@26
Dependencies: js/TypeDecls.h@8; mozilla/KeySystemConfig.h@9; mozilla/dom/MediaKeySystemAccessBinding.h@10; mozilla/dom/MediaKeysRequestStatusBinding.h@11; mozilla/dom/Promise.h@12; nsCycleCollectionParticipant.h@13; nsWrapperCache.h@14

`dom/media/eme/MediaKeySystemAccessManager.cpp` | `aaa3ff25b64f1f51f8f70f980f30d8b649f9cdc1` | 29492 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; MediaKeySystemAccessRequest@31; MediaKeySystemAccessManager::PendingRequest::~PendingRequest@35; MediaKeySystemAccessManager::PendingRequest::CancelTimer@39; RejectPromiseWithInvalidAccessError@47; RejectPromiseWithNotSupportedError@54; RejectPromiseWithInvalidAccessError@75; RejectPromiseWithNotSupportedError@80; RejectPromiseWithTypeError@85; mWindow@139; MediaKeySystemAccessManager::~MediaKeySystemAccessManager@143; MediaKeySystemAccessManager::GetName@671; MediaKeySystemAccessManager::EnsureObserversAdded@676; MediaKeySystemAccessManager::Shutdown@692
Dependencies: MediaKeySystemAccessManager.h@5; DecoderDoctorDiagnostics.h@7; MediaKeySystemAccessPermissionRequest.h@8; VideoUtils.h@9; mozilla/DetailedPromise.h@10; mozilla/EMEUtils.h@11; mozilla/Preferences.h@12; mozilla/Services.h@13; mozilla/StaticPrefs_media.h@14; mozilla/dom/BrowserChild.h@15; mozilla/dom/Document.h@16; mozilla/dom/KeySystemNames.h@17; nsComponentManagerUtils.h@18; nsContentUtils.h@19; nsIObserverService.h@20; nsIScriptError.h@21; nsPrintfCString.h@22; nsServiceManagerUtils.h@23; nsTHashMap.h@24

`dom/media/eme/MediaKeySystemAccessManager.h` | `1a8c499b98b1ea4cdec371becf1c0bb80cbb95ef` | 11310 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; DetailedPromise@18; TestGMPVideoDecoder@19; MediaKeySystemAccessRequest@89; mKeySystem@93; MediaKeySystemAccessManager@102; PendingRequest@129; class@130; PendingRequestWithMozPromise@164; PendingRequest@168
Dependencies: DecoderDoctorDiagnostics.h@8; mozilla/MozPromise.h@9; mozilla/dom/MediaKeySystemAccess.h@10; nsCycleCollectionParticipant.h@11; nsIObserver.h@12; nsISupportsImpl.h@13; nsITimer.h@14

`dom/media/eme/MediaKeySystemAccessPermissionRequest.cpp` | `586f1b22d048b5b82d29edbb6cb99baa82c0d1d4` | 3020 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@9; MediaKeySystemAccessPermissionRequest::Create@19; MediaKeySystemAccessPermissionRequest::GetPromise@53; MediaKeySystemAccessPermissionRequest::Start@57; MediaKeySystemAccessPermissionRequest::Allow@76; MediaKeySystemAccessPermissionRequest::Cancel@83
Dependencies: MediaKeySystemAccessPermissionRequest.h@5; nsGlobalWindowInner.h@7

`dom/media/eme/MediaKeySystemAccessPermissionRequest.h` | `70504f227d85d53f72153f88721bac122175c115` | 3046 bytes | source | UTF-8 | mode 100644
Declarations: nsGlobalWindowInner@11; mozilla@13; MediaKeySystemAccessPermissionRequest@35
Dependencies: mozilla/MozPromise.h@8; nsContentPermissionHelper.h@9

`dom/media/eme/MediaKeys.cpp` | `6b7f543956123fae511ea221bcf2b974ce6060a1` | 31382 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@41; mConfig@79; MediaKeys::~MediaKeys@84; MediaKeys::ConnectInnerWindow@129; MediaKeys::DisconnectInnerWindow@138; MediaKeys::OnInnerWindowDestroy@150; MediaKeys::Terminated@166; MediaKeys::Shutdown@189; MediaKeys::GetParentObject@216; MediaKeys::GetKeySystem@223; MediaKeys::StorePromise@265; MediaKeys::RetrievePromise@297; MediaKeys::OnSessionIdReady@358; MediaKeys::ResolvePromise@380; MediaKeysGMPCrashHelper@417; mMediaKeys@420; MediaKeys::CreateCDMProxy@435; IsWMFClearKeySystemAndSupported@461; MediaKeys::Init@474; MediaKeys::OnCDMCreated@625; MediaKeys::OnSessionLoaded@703; MediaKeys::OnSessionClosed@710; MediaKeys::IsBoundToMediaElement@733; MediaKeys::Bind@738; MediaKeys::Unbind@749; MediaKeys::CheckIsElementCapturePossible@754; MediaKeys::GetSessionsInfo@805; MediaKeys::GetMediaKeySystemConfigurationString@868
Dependencies: mozilla/dom/MediaKeys.h@5; ChromiumCDMProxy.h@7; GMPCrashHelper.h@8; mozilla/EMEUtils.h@9; mozilla/JSONStringWriteFuncs.h@10; mozilla/dom/DOMException.h@11; mozilla/dom/Document.h@12; mozilla/dom/HTMLMediaElement.h@13; mozilla/dom/MediaKeyError.h@14; mozilla/dom/MediaKeyMessageEvent.h@15; mozilla/dom/MediaKeySession.h@16; mozilla/dom/MediaKeySessionBinding.h@17; mozilla/dom/MediaKeyStatusMap.h@18; mozilla/dom/MediaKeySystemAccess.h@19; mozilla/dom/MediaKeysBinding.h@20; mozilla/dom/UnionTypes.h@21; mozilla/dom/WindowContext.h@22; mozilla/dom/WindowGlobalChild.h@23; nsContentTypeParser.h@24; nsContentUtils.h@25; nsIScriptObjectPrincipal.h@26; nsPrintfCString.h@27; nsServiceManagerUtils.h@28; AndroidDecoderModule.h@31; mozilla/MediaDrmCDMProxy.h@32; mozilla/RemoteCDMProxy.h@33; mozilla/RemoteMediaManagerChild.h@34; mozilla/StaticPrefs_media.h@35; mozilla/WMFCDMProxy.h@38

`dom/media/eme/MediaKeys.h` | `e07ea9d2549161bd4a6fb8739bca887b3405fdac` | 9166 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@23; CDMProxy@25; dom@27; MediaKeys@28; dom@32; ArrayBufferViewOrArrayBuffer@34; MediaKeySession@35; MediaKeysPolicy@36; HTMLMediaElement@37; nsRefPtrHashtable@39; nsRefPtrHashtable@40; nsRefPtrHashtable@41; nsTHashMap@43; uint32_t@44; MediaKeys@48; GetCDMProxy@112; GetPrincipal@114; ResolvePromiseWithResult@160
Dependencies: DecoderDoctorLogger.h@8; mozilla/DetailedPromise.h@9; mozilla/RefPtr.h@10; mozilla/WeakPtr.h@11; mozilla/dom/MediaKeyStatusMapBinding.h@12; mozilla/dom/MediaKeySystemAccessBinding.h@13; mozilla/dom/MediaKeysBinding.h@14; mozilla/dom/Promise.h@15; nsCOMPtr.h@16; nsCycleCollectionParticipant.h@17; nsIObserver.h@18; nsRefPtrHashtable.h@19; nsTHashMap.h@20; nsWrapperCache.h@21

`dom/media/eme/clearkey/BigEndian.h` | `9c59bb4a2fd91dda54f5bf16e6cdfad43210a4f2` | 1930 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@22; BigEndian@24; readUint32@26; readUint16@32; readUint64@37; writeUint64@44
Dependencies: stdint.h@20

`dom/media/eme/clearkey/ClearKeyBase64.cpp` | `4923ebbd1a65a4f3c4f10f198de2d5cb09d8ec16` | 2505 bytes | source | UTF-8 | mode 100644
Declarations: Decode6Bit@26; DecodeBase64@53
Dependencies: ClearKeyBase64.h@17

`dom/media/eme/clearkey/ClearKeyBase64.h` | `46f529a0d6d8960a7bc60e1333d1703e300f5b96` | 898 bytes | source | UTF-8 | mode 100644
Dependencies: stdint.h@20; string@22; vector@23

`dom/media/eme/clearkey/ClearKeyDecryptionManager.cpp` | `eaea6bf09b6a3eba0cf82d7cb6e131efce6827ac` | 10202 bytes | source | UTF-8 | mode 100644
Declarations: AllZero@31; ClearKeyDecryptor@36; HasKey@41; ClearKeyDecryptionManager::Get@58; ClearKeyDecryptionManager::ClearKeyDecryptionManager@65; ClearKeyDecryptionManager::~ClearKeyDecryptionManager@69; ClearKeyDecryptionManager::HasSeenKeyId@80; ClearKeyDecryptionManager::HasKeyForKeyId@94; ClearKeyDecryptionManager::InitKey@105; ClearKeyDecryptionManager::ExpectKeyId@115; ClearKeyDecryptionManager::ReleaseKeyId@124; ClearKeyDecryptor::ClearKeyDecryptor@155; ClearKeyDecryptor::~ClearKeyDecryptor@157; ClearKeyDecryptor::InitKey@165
Dependencies: ClearKeyDecryptionManager.h@17; assert.h@19; string.h@20; algorithm@22; vector@23; mozilla/CheckedInt.h@25; mozilla/Span.h@26; psshparser/PsshParser.h@27

`dom/media/eme/clearkey/ClearKeyDecryptionManager.h` | `47e8a84abbc9d7b4b5b74da7f5056fdf8860860f` | 3322 bytes | source | UTF-8 | mode 100644
Declarations: ClearKeyDecryptor@30; CryptoMetaData@32; CryptoMetaData@36; Init@40; IsValid@59; NumSubsamples@64; ClearKeyDecryptionManager@78
Dependencies: stddef.h@22; map@24; ClearKeyUtils.h@26; RefCounted.h@27; content_decryption_module.h@28

`dom/media/eme/clearkey/ClearKeyPersistence.cpp` | `822ba5e48d571c76f491619a51379220e6f42d43` | 4431 bytes | source | UTF-8 | mode 100644
Declarations: ClearKeyPersistence::WriteIndex@73; ClearKeyPersistence::ClearKeyPersistence@98; ClearKeyPersistence::IsLoaded@112; ClearKeyPersistence::GetNewSessionId@116; ClearKeyPersistence::IsPersistentSessionId@141; ClearKeyPersistence::PersistentSessionRemoved@145
Dependencies: ClearKeyPersistence.h@17; assert.h@19; stdint.h@20; sstream@22; ClearKeySessionManager.h@24; ClearKeyStorage.h@25; ClearKeyUtils.h@26; RefCounted.h@27

`dom/media/eme/clearkey/ClearKeyPersistence.h` | `eb7a1798eb785cfb2e29e96655312af5b329e14a` | 1771 bytes | source | UTF-8 | mode 100644
Declarations: ClearKeySessionManager@30; PersistentKeyState@33; ClearKeyPersistence@35
Dependencies: functional@23; set@24; string@25; RefCounted.h@27; content_decryption_module.h@28

`dom/media/eme/clearkey/ClearKeySession.cpp` | `c59e7ea4ab549178c91fb3a5f9d44f7dba23f0e1` | 2329 bytes | source | UTF-8 | mode 100644
Declarations: mSessionId@32; ClearKeySession::~ClearKeySession@36; ClearKeySession::Type@68; ClearKeySession::AddKeyId@70
Dependencies: ClearKeySession.h@17; assert.h@19; BigEndian.h@21; ClearKeyDecryptionManager.h@22; ClearKeyStorage.h@23; ClearKeyUtils.h@24; psshparser/PsshParser.h@25

`dom/media/eme/clearkey/ClearKeySession.h` | `56e185d0b967302de7b9cf5c179c968b369d9fa1` | 1497 bytes | source | UTF-8 | mode 100644
Declarations: ClearKeySession@29
Dependencies: string@23; vector@24; ClearKeyUtils.h@26; content_decryption_module.h@27

`dom/media/eme/clearkey/ClearKeySessionManager.cpp` | `794597084f627423a68ef84891d88fb9610d9872` | 24905 bytes | source | UTF-8 | mode 100644
Declarations: mDecryptionManager@38; ClearKeySessionManager::~ClearKeySessionManager@46; ClearKeySessionManager::DecryptingComplete@571; ClearKeySessionManager::QueryOutputProtectionStatusIfNeeded@617; ClearKeySessionManager::QueryOutputProtectionStatusFromHost@669; ClearKeySessionManager::NotifyOutputProtectionStatus@681
Dependencies: ClearKeySessionManager.h@17; assert.h@19; stdint.h@20; stdio.h@21; string.h@22; ClearKeyDecryptionManager.h@24; ClearKeyPersistence.h@25; ClearKeyStorage.h@26; ClearKeyUtils.h@27; content_decryption_module.h@28; psshparser/PsshParser.h@29

`dom/media/eme/clearkey/ClearKeySessionManager.h` | `0e5ca030a61237f5f429abb0ff709b14422a34df` | 5499 bytes | source | UTF-8 | mode 100644
Declarations: ClearKeySessionManager@38
Dependencies: functional@23; map@24; optional@25; queue@26; set@27; string@28; ClearKeyDecryptionManager.h@30; ClearKeyPersistence.h@31; ClearKeySession.h@32; ClearKeyUtils.h@33; RefCounted.h@34; content_decryption_module.h@35; mozilla/TimeStamp.h@36

`dom/media/eme/clearkey/ClearKeyStorage.cpp` | `002ae35b1e3fd89d038a6124e4bdbcfc9fd08509` | 5805 bytes | source | UTF-8 | mode 100644
Declarations: WriteRecordClient@34; mData@73; Do@75; Done@81; ReadRecordClient@115; mOnFailure@153; Do@155
Dependencies: ClearKeyStorage.h@17; assert.h@19; vector@23; ClearKeyUtils.h@25; content_decryption_module.h@26

`dom/media/eme/clearkey/ClearKeyStorage.h` | `fcba02a5dba8360054bb58a21c14315bcb453d12` | 1509 bytes | source | UTF-8 | mode 100644
Dependencies: stdint.h@20; functional@22; string@23; vector@24; ClearKeySessionManager.h@26

`dom/media/eme/clearkey/ClearKeyUtils.cpp` | `383143cac52062d1522ad95c41fe9daf0576a934` | 17286 bytes | source | UTF-8 | mode 100644
Declarations: DeleteHelper@46; operator@47; operator@48; operator@49; MaybeDeleteHelper@53; operator@54; CK_Log@62; PrintableAsString@85; EncodeBase64Web@236; ParserContext@308; PeekSymbol@313; GetNextSymbol@323; SkipString@331; SkipObject@350; SkipArray@374; SkipLiteral@397; SkipToken@408; GetNextLabel@425; ParseKeyObject@444; ParseKeys@490; ParseKeyIds@561; ClearKeyUtils::IsValidSessionId@643; ClearKeyUtils::ToHexString@657
Dependencies: ClearKeyUtils.h@17; assert.h@19; ctype.h@20; memory.h@21; stdarg.h@22; stdint.h@23; stdio.h@24; stdlib.h@25; algorithm@27; cctype@28; memory@29; sstream@30; vector@31; BigEndian.h@33; ClearKeyBase64.h@34; mozilla/Sprintf.h@35; pk11pub.h@36; prerror.h@37; psshparser/PsshParser.h@38; secmodt.h@39

`dom/media/eme/clearkey/ClearKeyUtils.h` | `7999701aaa5af41bc532fe8097b2e32a813bcb32` | 3585 bytes | source | UTF-8 | mode 100644
Declarations: std@48; std@49; KeyIdPair@62; ClearKeyUtils@67; Contains@97; Assign@102
Dependencies: assert.h@20; stddef.h@22; stdint.h@23; string@25; vector@26; content_decryption_module.h@28; mozilla/Span.h@29; pk11pub.h@30

`dom/media/eme/clearkey/RefCounted.h` | `de31af11c4a4691bd88cf61e31a838eb2d886ee5` | 1792 bytes | source | UTF-8 | mode 100644
Declarations: RefCounted@28; AddRef@30; Release@32; RefCounted@41; RefPtr@47; RefPtr@49; RefPtr@51; RefPtr@52; Get@60; Set@68
Dependencies: assert.h@20; stdint.h@21; atomic@23; ClearKeyUtils.h@25

`dom/media/eme/clearkey/gtest/TestClearKeyUtils.cpp` | `17f445c82fd6582d232dc280b42f15a8aeda0609` | 2414 bytes | test-path,source | UTF-8 | mode 100644
Declarations: B64Test@12; TEST@66
Dependencies: stdint.h@5; ../ClearKeyBase64.cpp@7; gtest/gtest.h@8

`dom/media/eme/clearkey/gtest/moz.build` | `1e0db870b7176030d1b775e725741252f5974c83` | 314 bytes | test-path,build-registration | UTF-8 | mode 100644

`dom/media/eme/clearkey/moz.build` | `c36dcf8985f6c0e43bf1976db7080de01bb63e17` | 782 bytes | build-registration | UTF-8 | mode 100644

`dom/media/eme/mediadrm/MediaDrmCDMCallbackProxy.cpp` | `a53e0bfdcfbf096203d7cc112e408caeada69b7e` | 4332 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; mProxy@18; MediaDrmCDMCallbackProxy::ResolvePromise@34; MediaDrmCDMCallbackProxy::SessionClosed@62
Dependencies: MediaDrmCDMCallbackProxy.h@5; MainThreadUtils.h@7; MediaDrmCDMProxy.h@8; mozilla/EMEUtils.h@9; mozilla/dom/MediaKeySession.h@10; mozilla/dom/MediaKeys.h@11; nsServiceManagerUtils.h@12; nsString.h@13

`dom/media/eme/mediadrm/MediaDrmCDMCallbackProxy.h` | `d0d4e7bd9ee5d1f15e49b961a6524ef08ec0ea80` | 2212 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; CDMProxy@12; ErrorResult@13; MediaDrmCDMProxy@14; MediaDrmCDMCallbackProxy@19
Dependencies: mozilla/CDMProxy.h@8; mozilla/DecryptorProxyCallback.h@9

`dom/media/eme/mediadrm/MediaDrmCDMProxy.cpp` | `db0fc3cf3b3a9c1f5e8985430d7eb4eeb175796c` | 16103 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; mShutdownCalled@32; MediaDrmCDMProxy::~MediaDrmCDMProxy@37; EME_LOG@45; MediaDrmCDMProxy::QueryOutputProtectionStatus@175; MediaDrmCDMProxy::Shutdown@187; MediaDrmCDMProxy::Terminated@201; MediaDrmCDMProxy::Decrypt@286; MediaDrmCDMProxy::ResolvePromise@316; MediaDrmCDMProxy::OnKeyStatusesChange@351; MediaDrmCDMProxy::IsOnOwnerThread@374; MediaDrmCDMProxy::OnCDMCreated@384; MediaDrmCDMProxy::md_Init@402; MediaDrmCDMProxy::md_CreateSession@415; MediaDrmCDMProxy::md_UpdateSession@447; MediaDrmCDMProxy::md_CloseSession@458; MediaDrmCDMProxy::md_Shutdown@469
Dependencies: mozilla/MediaDrmCDMProxy.h@5; MediaDrmCDMCallbackProxy.h@7; mozilla/EMEOriginID.h@8; mozilla/dom/MediaKeySession.h@9

`dom/media/eme/mediadrm/MediaDrmCDMProxy.h` | `3b7127e6ff94c87f4ca36040f6785112e9a8bf26` | 6458 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@20; MediaDrmCDMCallbackProxy@22; MediaDrmCDMProxy@23; CreateSessionData@117; UpdateSessionData@125; SessionOpData@131; RejectPromiseTask@136; mReason@144
Dependencies: jni.h@8; MediaCodec.h@10; mozilla/CDMCaps.h@11; mozilla/CDMProxy.h@12; mozilla/MediaDrmProxySupport.h@13; mozilla/UniquePtr.h@14; mozilla/dom/MediaKeySession.h@15; mozilla/dom/MediaKeys.h@16; mozilla/jni/Types.h@17; nsString.h@18

`dom/media/eme/mediadrm/MediaDrmProvisioning.sys.mjs` | `f9e86894886d7edff05e491a064cb7549d13a3b3` | 778 bytes | source | UTF-8 | mode 100644
Declarations: MediaDrmProvisioning@5; provision@13

`dom/media/eme/mediadrm/MediaDrmProvisioningHelper.cpp` | `f652aaf33c28b7ad2e1030ae42aea47bcc76e31a` | 3363 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; mResolver@22; MediaDrmProvisioningHelper::~MediaDrmProvisioningHelper@24; MediaDrmProvisioningHelper::Provision@30
Dependencies: MediaDrmProvisioningHelper.h@5; nsComponentManagerUtils.h@7; nsIMediaDrmProvisioning.h@8

`dom/media/eme/mediadrm/MediaDrmProvisioningHelper.h` | `563138d182409a05e25d0fe20806cb44aa689f98` | 2064 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; MediaDrmProvisioningHelper@22; MaybeResolve@44
Dependencies: mozilla/PRemoteCDMChild.h@8; mozilla/dom/PromiseNativeHandler.h@9; nsISerialEventTarget.h@10

`dom/media/eme/mediadrm/MediaDrmProxySupport.cpp` | `06d7ff7d941006d47382484b9d3e7166d65b3185` | 10725 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; GetMDRMNLog@15; MediaDrmJavaCallbacksSupport@20; java@24; mDecryptorProxyCallback@32; MediaDrmKeyStatusToMediaKeyStatus@135; mKeySystem@194; MediaDrmProxySupport::~MediaDrmProxySupport@210; MediaDrmProxySupport::Shutdown@263
Dependencies: MediaDrmProxySupport.h@5; MediaCodec.h@7; MediaDrmCDMCallbackProxy.h@8; mozilla/EMEUtils.h@9; mozilla/java/MediaDrmProxyNatives.h@10; mozilla/java/SessionKeyInfoWrappers.h@11

`dom/media/eme/mediadrm/MediaDrmProxySupport.h` | `ce0770e57a987139ad427f067fe0554aea8bea27` | 2027 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; MediaDrmSessionType@16; MediaDrmCDMCallbackProxy@29; MediaDrmProxySupport@31
Dependencies: mozilla/DecryptorProxyCallback.h@8; mozilla/Logging.h@9; mozilla/UniquePtr.h@10; mozilla/java/MediaDrmProxyWrappers.h@11; nsString.h@12

`dom/media/eme/mediadrm/MediaDrmRemoteCDMParent.cpp` | `23c6914e78cf38747de8c7c4f573d48f2954cd93` | 33138 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; MediaDrmRemoteCDMParent::InitializeStatics@19; mMutex@143; MediaDrmRemoteCDMParent::~MediaDrmRemoteCDMParent@153; MediaDrmRemoteCDMParent::ActorDestroy@159; MediaDrmRemoteCDMParent::Destroy@164; MediaDrmRemoteCDMParent::EnsureHasAMediaCrypto@308; MediaDrmRemoteCDMParent::EnsureProvisioned@358; MediaDrmCrypto::~MediaDrmCrypto@903; MediaDrmCryptoInfo::~MediaDrmCryptoInfo@905
Dependencies: MediaDrmRemoteCDMParent.h@5; limits@7; mozilla/CheckedInt.h@9; mozilla/EMEUtils.h@10; mozilla/RemoteMediaManagerParent.h@11

`dom/media/eme/mediadrm/MediaDrmRemoteCDMParent.h` | `462edfff549ca05f0668cb7632f150cf9a829ce5` | 5471 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; MediaDrmCrypto@20; GetNdkCrypto@27; MediaDrmCrypto@30; MediaDrmCryptoInfo@37; GetNdkCryptoInfo@44; mCryptoInfo@48; MediaDrmRemoteCDMParent@55; GetCrypto@62; HasCrypto@67; SessionEntry@151
Dependencies: map@8; media/NdkMediaCodec.h@10; media/NdkMediaCrypto.h@11; media/NdkMediaDrm.h@12; media/NdkMediaError.h@13; mozilla/Mutex.h@14; mozilla/RemoteCDMParent.h@15; mozilla/StaticPtr.h@16

`dom/media/eme/mediadrm/components.conf` | `6ff00a98dc70199abc302122c24f8dbd06a158bd` | 492 bytes | build-registration | UTF-8 | mode 100644

`dom/media/eme/mediadrm/moz.build` | `52fe35f4d3619f67221c6591f06a77687fc05e2e` | 880 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@39

`dom/media/eme/mediadrm/nsIMediaDrmProvisioning.idl` | `c9767fc18bd9c4857550f15f4eaadf8beb26a6b3` | 409 bytes | source | UTF-8 | mode 100644
Declarations: nsIMediaDrmProvisioning@8
Dependencies: nsISupports.idl@5

`dom/media/eme/mediafoundation/WMFCDMImpl.cpp` | `06cc3895e0890a34b3ea5c1e6ffa61835308e099` | 5082 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; WMFCDMCapabilites::~WMFCDMCapabilites@122
Dependencies: WMFCDMImpl.h@5; mozilla/AppShutdown.h@7; mozilla/ClearOnShutdown.h@8; mozilla/ScopeExit.h@9; mozilla/dom/KeySystemNames.h@10; mozilla/dom/MediaKeySession.h@11

`dom/media/eme/mediafoundation/WMFCDMImpl.h` | `3a8ab304dfa8abc599b3f434cc97852634763e4b` | 4784 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; WMFCDMProxyCallback@19; WMFCDMImpl@29; WMFCDMImpl@33; InitParams@36; Id@95; WMFCDMCapabilites@117
Dependencies: MediaData.h@8; mozilla/Assertions.h@9; mozilla/EMEUtils.h@10; mozilla/KeySystemConfig.h@11; mozilla/MFCDMChild.h@12; mozilla/media/MediaUtils.h@13; nsString.h@14; nsThreadUtils.h@15

`dom/media/eme/mediafoundation/WMFCDMProxy.cpp` | `9d41dfc9ea64105433dd9a491ca65c83897dcf06` | 17250 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; mConfig@59; NS_NewNamedThread@73; WMFCDMProxy::ResolvePromise@141; WMFCDMProxy::Shutdown@314; WMFCDMProxy::Terminated@325; WMFCDMProxy::OnKeyStatusesChange@347; WMFCDMProxy::IsHardwareDecryptionSupported@431; WMFCDMProxy::GetCDMProxyId@435
Dependencies: WMFCDMProxy.h@5; MediaData.h@7; WMFCDMImpl.h@8; WMFCDMProxyCallback.h@9; mozilla/EMEUtils.h@10; mozilla/WMFCDMProxyCallback.h@11; mozilla/WindowsVersion.h@12; mozilla/dom/MediaKeySession.h@13; mozilla/dom/MediaKeySystemAccessBinding.h@14; mozilla/dom/MediaKeysBinding.h@15

`dom/media/eme/mediafoundation/WMFCDMProxy.h` | `737b837df00f3c9b902f30fd9db0c976288a77d6` | 5159 bytes | source | UTF-8 | mode 100644
Declarations: dom@18; MediaKeySystemMediaCapability@19; mozilla@22; WMFCDMProxyCallback@24; WMFCDMProxy@26; ResolvePromiseWithResult@120
Dependencies: mozilla/CDMCaps.h@8; mozilla/CDMProxy.h@9; mozilla/MozPromise.h@10; mozilla/RefPtr.h@11; mozilla/WMFCDMImpl.h@12; mozilla/dom/BindingDeclarations.h@13; mozilla/dom/MediaKeySession.h@14; mozilla/dom/MediaKeys.h@15; nsString.h@16

`dom/media/eme/mediafoundation/WMFCDMProxyCallback.cpp` | `b832fe813db8b68ff9d81c2478e348113b8558ec` | 3640 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; WMFCDMProxyCallback::WMFCDMProxyCallback@22; WMFCDMProxyCallback::~WMFCDMProxyCallback@27; WMFCDMProxyCallback::OnSessionMessage@29; WMFCDMProxyCallback::OnRemoteProcessCrashed@87; WMFCDMProxyCallback::Shutdown@96
Dependencies: WMFCDMProxyCallback.h@5; GMPUtils.h@7; mozilla/EMEUtils.h@8; mozilla/WMFCDMProxy.h@9

`dom/media/eme/mediafoundation/WMFCDMProxyCallback.h` | `32d50c638d5d57def0da3c7fa160293902630bfc` | 1225 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; WMFCDMProxy@13; WMFCDMProxyCallback@17
Dependencies: mozilla/PMFCDM.h@8; nsThreadUtils.h@9

`dom/media/eme/mediafoundation/moz.build` | `52e602298bbbe42b3feb2310e5d11f699b6e486e` | 467 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@17

`dom/media/eme/metrics.yaml` | `0e6914c44256ac05caf3243f61ed0cbcccc42bab` | 1930 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/eme/moz.build` | `1b390d08a1814cdeddafb14cb5db87999a3c6df6` | 1382 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@53

`dom/media/encoder/ContainerWriter.h` | `6ab33ee3e2bb2bd3a630cdc96f50802bed0d52e7` | 2548 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ContainerWriter@16; ContainerWriter@18; IsWritingComplete@52
Dependencies: EncodedFrame.h@8; TrackMetadataBase.h@9; nsTArray.h@10

`dom/media/encoder/EncodedFrame.h` | `2be4b4978dace358949e4bbd19436a00b822f093` | 2127 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; EncodedFrame@16; FrameType@19; mFrameData@34; GetEndTime@52
Dependencies: TimeUnits.h@8; VideoUtils.h@9; mozilla/media/MediaUtils.h@10; nsISupportsImpl.h@11

`dom/media/encoder/MediaEncoder.cpp` | `9eddf89257aca05a37a06093be1c8a1b2d49380c` | 37756 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@43; BlobStorer@49; Promise@70; MediaEncoder@76; mShutdownPromise@86; MediaEncoder@171; mShutdownPromise@179; MediaEncoder@353; mEncoderThread@356; Forget@358; mError@426; MediaEncoder::RegisterListeners@437; MediaEncoder::~MediaEncoder@462; MediaEncoder::EnsureGraphTrackFrom@470; MediaEncoder::Suspend@479; MediaEncoder::Resume@500; MediaEncoder::ConnectAudioNode@521; MediaEncoder::ConnectMediaStreamTrack@558; MediaEncoder::RemoveMediaStreamTrack@601; MediaEncoder::MaybeShutdown@741; MediaEncoder::Shutdown@763; MediaEncoder::Stop@811; MediaEncoder::Cancel@821; MediaEncoder::HasError@840; MediaEncoder::SetError@845; MediaEncoder::MaybeCreateMutableBlobStorage@872; MediaEncoder::OnEncodedAudioPushed@880; MediaEncoder::OnEncodedVideoPushed@886; MediaEncoder::MaybeExtractOrGatherBlob@892; MediaEncoder::Extract@932; MediaEncoder::DisconnectTracks@1000; MediaEncoder::IsWebMEncoderEnabled@1026; MediaEncoder::UpdateInitialized@1030; MediaEncoder::UpdateStarted@1076
Dependencies: MediaEncoder.h@5; algorithm@7; AudioNodeEngine.h@9; AudioNodeTrack.h@10; DriftCompensation.h@11; MediaDecoder.h@12; MediaTrackGraph.h@13; MediaTrackListener.h@14; Muxer.h@15; OggWriter.h@16; OpusTrackEncoder.h@17; TimeUnits.h@18; Tracing.h@19; VP8TrackEncoder.h@20; WebMWriter.h@21; mozilla/Logging.h@22; mozilla/Preferences.h@23; mozilla/ProfilerLabels.h@24; mozilla/StaticPrefs_media.h@25; mozilla/StaticPtr.h@26; mozilla/TaskQueue.h@27; mozilla/dom/AudioNode.h@28; mozilla/dom/AudioStreamTrack.h@29; mozilla/dom/Blob.h@30; mozilla/dom/BlobImpl.h@31; mozilla/dom/MediaStreamTrack.h@32; mozilla/dom/MutableBlobStorage.h@33; mozilla/dom/VideoStreamTrack.h@34; mozilla/gfx/Point.h@35; nsMimeTypes.h@36; nsThreadUtils.h@37

`dom/media/encoder/MediaEncoder.h` | `b5975efd57a6867316530fe59b6ae8084aa59b72` | 14409 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; DriftCompensator@21; Muxer@22; Runnable@23; TaskQueue@24; dom@26; AudioNode@27; AudioStreamTrack@28; BlobImpl@29; MediaStreamTrack@30; MutableBlobStorage@31; VideoStreamTrack@32; DriftCompensator@35; MediaEncoder@101; AudioTrackListener@103; VideoTrackListener@104; EncoderListener@105; AssertShutdownCalled@179; StartedEvent@223; ErrorEvent@226; ShutdownEvent@228; DataAvailableEvent@231; GetEncodeTimeStamp@390
Dependencies: ContainerWriter.h@8; CubebUtils.h@9; MediaQueue.h@10; MediaTrackGraph.h@11; MediaTrackListener.h@12; TrackEncoder.h@13; mozilla/MemoryReporting.h@14; mozilla/MozPromise.h@15; mozilla/UniquePtr.h@16; nsIMemoryReporter.h@17

`dom/media/encoder/Muxer.cpp` | `730dcff10d71ebf9dd640afa9779f65329c862d9` | 6558 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@9; mWriter@19; Muxer::Disconnect@21; Muxer::IsFinished@28; Muxer::GetData@67; Muxer::Mux@112
Dependencies: Muxer.h@5; ContainerWriter.h@7

`dom/media/encoder/Muxer.h` | `d56a93b9b5083a5cd16c03efa88a7c9e99175fb1` | 2504 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; ContainerWriter@13; EncodedFrame@14; TrackMetadataBase@15; Muxer@20; NeedsMetadata@36
Dependencies: MediaQueue.h@8; mozilla/media/MediaUtils.h@9

`dom/media/encoder/OpusTrackEncoder.cpp` | `7ee125710b4e83b15b8e9318e141047f110f3e80` | 16314 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; SerializeToBuffer@47; IsSampleRateSupported@114; mNumOutputFrames@136; OpusTrackEncoder::~OpusTrackEncoder@138; OpusTrackEncoder::Init@148; OpusTrackEncoder::GetLookahead@202; OpusTrackEncoder::NumInputFramesPerPacket@206; OpusTrackEncoder::NumOutputFramesPerPacket@210; OpusTrackEncoder::NeedsResampler@214; OpusTrackEncoder::GetMetadata@221; OpusTrackEncoder::Encode@250
Dependencies: OpusTrackEncoder.h@4; opus/opus.h@6; VideoUtils.h@8; mozilla/CheckedInt.h@9; mozilla/ProfilerLabels.h@10; nsString.h@11

`dom/media/encoder/OpusTrackEncoder.h` | `2306dfa64ce4f42257f2a5e23adf41b4f37bc313` | 3137 bytes | source | UTF-8 | mode 100644
Declarations: OpusEncoder@14; mozilla@16; OpusMetadata@19; OpusTrackEncoder@30
Dependencies: speex/speex_resampler.h@8; stdint.h@9; TimeUnits.h@11; TrackEncoder.h@12

`dom/media/encoder/TrackEncoder.cpp` | `3b3b20f5ae9ccc43a50cd552d386e94290012ed8` | 26996 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; mEncodedDataQueue@44; TrackEncoder::IsInitialized@46; TrackEncoder::IsStarted@51; TrackEncoder::IsEncodingComplete@56; TrackEncoder::SetInitialized@61; TrackEncoder::SetStarted@75; TrackEncoder::OnError@89; TrackEncoder::RegisterListener@99; TrackEncoder::UnregisterListener@105; TrackEncoder::SetWorkerThread@110; AudioTrackEncoder::Suspend@114; AudioTrackEncoder::Resume@127; AudioTrackEncoder::AppendAudioSegment@140; AudioTrackEncoder::Cancel@235; AudioTrackEncoder::NotifyEndOfStream@245; mEnabled@331; VideoTrackEncoder::Suspend@335; VideoTrackEncoder::Resume@351; VideoTrackEncoder::Disable@381; VideoTrackEncoder::Enable@409; VideoTrackEncoder::AppendVideoSegment@437; VideoTrackEncoder::Cancel@559; VideoTrackEncoder::NotifyEndOfStream@571; VideoTrackEncoder::SetStartOffset@640; VideoTrackEncoder::AdvanceCurrentTime@649
Dependencies: TrackEncoder.h@5; AudioChannelFormat.h@7; DriftCompensation.h@8; MediaTrackGraph.h@9; MediaTrackListener.h@10; VideoUtils.h@11; mozilla/AbstractThread.h@12; mozilla/Logging.h@13; mozilla/ProfilerLabels.h@14; mozilla/RollingMean.h@15

`dom/media/encoder/TrackEncoder.h` | `52b5aaeac940fc4c286de192af9b23cb7576d21d` | 15151 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; AbstractThread@17; DriftCompensator@18; TrackEncoder@19; TrackEncoderListener@21; TrackEncoder@54; EncodedDataQueue@79; AudioTrackEncoder@188; mAudioBitrate@195; NumInputFramesPerPacket@288; class@321; VideoTrackEncoder@326; SecondsToMediaTime@387
Dependencies: AudioSegment.h@8; EncodedFrame.h@9; MediaQueue.h@10; MediaTrackGraph.h@11; TrackMetadataBase.h@12; VideoSegment.h@13

`dom/media/encoder/TrackMetadataBase.h` | `5c6d9c43dd9268c1f428db195164407b1f264438` | 2416 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; TrackMetadataBase@14; MetadataKind@17; AudioTrackMetadata@36; VideoTrackMetadata@53
Dependencies: nsCOMPtr.h@8; nsTArray.h@9

`dom/media/encoder/VP8TrackEncoder.cpp` | `3a5961e00331e2ffe9180910de9779acd18cd3f5` | 26473 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@22; VP8TrackEncoder::~VP8TrackEncoder@160; VP8TrackEncoder::Destroy@165; VP8TrackEncoder::SetMaxKeyFrameDistance@189; VP8TrackEncoder::GetMetadata@368; VP8TrackEncoder::Encode@495; VP8TrackEncoder::PrepareRawFrame@661
Dependencies: VP8TrackEncoder.h@5; vpx/vp8cx.h@7; vpx/vpx_encoder.h@8; DriftCompensation.h@10; ImageConversion.h@11; VideoSegment.h@12; VideoUtils.h@13; WebMWriter.h@14; mozilla/ProfilerLabels.h@15; mozilla/dom/ImageBitmapBinding.h@16; mozilla/dom/ImageUtils.h@17; mozilla/gfx/2D.h@18; mozilla/media/MediaUtils.h@19; prsystem.h@20

`dom/media/encoder/VP8TrackEncoder.h` | `36a62725b9ad71c2d108fdbc8356bca4251c901b` | 5714 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; struct@16; struct@17; struct@18; VP8Metadata@20; VP8TrackEncoder@27; EncodeOperation@28
Dependencies: vpx/vpx_codec.h@8; TimeUnits.h@10; TrackEncoder.h@11; mozilla/RollingMean.h@12

`dom/media/encoder/moz.build` | `ccd92cdac132893e92a62c9f46f2e81c791fa975` | 1108 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@34

`dom/media/fake-cdm/cdm-fake.cpp` | `4f3836a51b3e16be7eb56bffe05b01f09c9a5c0f` | 2431 bytes | source | UTF-8 | mode 100644
Declarations: INITIALIZE_CDM_MODULE@43; VerifyCdmHost_0@59
Dependencies: cdm-test-decryptor.h@36; content_decryption_module.h@37; content_decryption_module_ext.h@38

`dom/media/fake-cdm/cdm-test-decryptor.cpp` | `a5db8e632b95ef0c118a7ef077e0b709d38f23ad` | 14702 bytes | source | UTF-8 | mode 100644
Declarations: TestManager@21; BeginTest@26; EndTest@39; Error@61; Finish@63; FakeDecryptor::FakeDecryptor@69; FakeDecryptor::Message@74; Tokenize@82; WriteRecordSuccessTask@92; mId@95; operator@97; WriteRecordFailureTask@103; mMessage@108; operator@110; TestEmptyContinuation@123; mTestmanager@126; TruncateContinuation@142; mID@146; VerifyAndFinishContinuation@169; mTestID@176; VerifyAndOverwriteContinuation@195; mTestID@205; OpenedSecondTimeContinuation@233; mTestmanager@237; OpenedFirstTimeContinuation@254; mID@258; FakeDecryptor::TestStorage@335; ReportWritten@345; mRecordId@348; operator@349; ReportReadStatusContinuation@357; mRecordId@360; ReportReadRecordContinuation@377; mRecordId@380
Dependencies: cdm-test-decryptor.h@5; istream@7; iterator@8; mutex@9; set@10; sstream@11; string@12; vector@13; cdm-test-output-protection.h@15; cdm-test-storage.h@16; mozilla/Assertions.h@17

`dom/media/fake-cdm/cdm-test-decryptor.h` | `d2db845116234a9beb555fe6ba4f5396e5475fd6` | 3605 bytes | source | UTF-8 | mode 100644
Declarations: FakeDecryptor@12
Dependencies: string@8; content_decryption_module.h@10

`dom/media/fake-cdm/cdm-test-output-protection.h` | `05f05b820a710343c842769a30a23d8064a331ee` | 3971 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@21; HRESULT@24; RunOutputProtectionAPITests@92; TestOuputProtectionAPIs@125
Dependencies: d3d9.h@9; stdio.h@10; windows.h@11; string@13; vector@14; opmapi.h@16; cdm-test-decryptor.h@19

`dom/media/fake-cdm/cdm-test-storage.cpp` | `8175ad8fe68170fac87fda196a5a0f84307bae1c` | 6294 bytes | source | UTF-8 | mode 100644
Declarations: WriteRecordClient@11; mOnSuccess@16; Do@34; Done@41; ReadRecordClient@85; mOnReadComplete@89; Do@107; OpenRecordClient@146; mOpenComplete@149; Do@158; Done@165
Dependencies: cdm-test-storage.h@5; vector@7

`dom/media/fake-cdm/cdm-test-storage.h` | `2cd4fede7bd07671c73afc6afc5d6b1240f056a1` | 1569 bytes | source | UTF-8 | mode 100644
Declarations: ReadContinuation@17; OpenContinuation@37
Dependencies: cstdint@8; functional@9; string@10; content_decryption_module.h@12

`dom/media/fake-cdm/manifest.json` | `96823bac098e051ffd9021e4eb3447c8b8e1996f` | 196 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/fake-cdm/moz.build` | `4b2c84a306237f3ce850d8ea906d9da7574ead55` | 776 bytes | build-registration | UTF-8 | mode 100644

`dom/media/flac/FlacDecoder.cpp` | `34b00e3d7d72883de0d3a8060edebd97d7ec6109` | 1120 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; FlacDecoder::IsEnabled@13; FlacDecoder::IsSupportedType@16
Dependencies: FlacDecoder.h@5; MediaContainerType.h@7; mozilla/StaticPrefs_media.h@8

`dom/media/flac/FlacDecoder.h` | `c227acc73ca93a429235a04e58fea22ddd7c8f91` | 793 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; MediaContainerType@13; TrackInfo@14; FlacDecoder@16
Dependencies: mozilla/UniquePtr.h@8; nsTArray.h@9

`dom/media/flac/FlacDemuxer.cpp` | `498242a2c4fc0d5aef405a67fb9cc8deb2a817d5` | 35167 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@22; flac@23; FrameHeader@28; Size@32; IsValid@34; Index@37; Parse@43; Frame@218; FindNext@224; FindNext@260; Offset@307; SetEndOffset@311; SetEndTime@313; ResetStartTimeIfNeeded@319; Size@330; Time@332; Duration@340; IsValid@351; EOS@353; SetRate@355; SetBitDepth@357; SetInvalid@359; Reset@362; SetOffset@365; FrameParser@380; EndFrameSession@389; FindNextFrame@395; IsHeaderBlock@428; HeaderBlockLength@433; DecodeHeaderBlock@437; HasFullMetadata@441; Info@443; GetTags@446; GetNextFrame@449; CheckFrameData@468; FlacDemuxer::FlacDemuxer@557; FlacDemuxer::InitInternal@561; FlacDemuxer::Init@569; FlacDemuxer::GetNumberTracks@581; FlacDemuxer::IsSeekable@594; mSource@600; FlacTrackDemuxer::Init@607; FlacTrackDemuxer::GetInfo@663; FlacTrackDemuxer::IsSeekable@693; FlacTrackDemuxer::FastSeek@709; FlacTrackDemuxer::ScanUntil@802; FlacTrackDemuxer::Reset@869; FlacTrackDemuxer::SkipToNextRandomAccessPoint@882; FlacTrackDemuxer::GetResourceOffset@888; FlacTrackDemuxer::GetBuffered@890; FlacTrackDemuxer::AverageFrameLength@980; FlacTrackDemuxer::Duration@989; FlacTrackDemuxer::TimeAtEnd@993; FlacDemuxer::FlacSniffer@1035
Dependencies: FlacDemuxer.h@5; BitReader.h@7; FlacFrameParser.h@8; TimeUnits.h@9; VideoUtils.h@10; mozilla/EndianUtils.h@11; mozilla/Maybe.h@12; prenv.h@13

`dom/media/flac/FlacDemuxer.h` | `0124c4bbe62b574c00b8d8a2f6af089ae2e1b763` | 3473 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; flac@12; Frame@13; FrameParser@14; FlacTrackDemuxer@16; FlacDemuxer@21; FlacTrackDemuxer@42
Dependencies: MediaDataDemuxer.h@8; MediaResource.h@9

`dom/media/flac/FlacFrameParser.cpp` | `6619b7816cbcad6998726e5740f0f917de72bb08` | 7441 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; mPacketCount@40; FlacFrameParser::HeaderBlockLength@44; FlacFrameParser::GetTags@224
Dependencies: FlacFrameParser.h@5; BufferReader.h@7; OggCodecState.h@8; OpusParser.h@9; VideoUtils.h@10; mozilla/EndianUtils.h@11; mozilla/Try.h@12; nsTArray.h@13

`dom/media/flac/FlacFrameParser.h` | `0a9b32449caf70c3d0e4a67d34edbc0b3fd8aa3d` | 2231 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; OpusParser@24; FlacFrameParser@30; HasFullMetadata@43
Dependencies: MediaDecoder.h@8; MediaInfo.h@9; MediaResource.h@10; mozilla/Maybe.h@11; mozilla/Result.h@12

`dom/media/flac/moz.build` | `c6e76fab03092b1417dce35b0346013fefc0096f` | 537 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /tools/fuzzing/libfuzzer-config.mozbuild@22

`dom/media/fuzz/FuzzMedia.cpp` | `5fcaceb284e5fd0cbea891e1635a511a81d321e4` | 13573 bytes | source | UTF-8 | mode 100644
Declarations: Benchmark@26; BenchmarkPlayback@28; Benchmark@66; Parameters@70; mTimeout@74; mTimeout@81; MozPromise@89; FuzzRunner@109; FuzzRunner@111; Run@113; SpinEventLoopUntil@126; mPlaybackState@138; Benchmark::~Benchmark@142; Benchmark::Run@144; Benchmark::Dispose@155; Benchmark::Init@161; mDrained@179; BenchmarkPlayback::DemuxSamples@181; BenchmarkPlayback::DemuxNextSample@203; BenchmarkPlayback::InitDecoder@234; BenchmarkPlayback::FinalizeShutdown@261; BenchmarkPlayback::GlobalShutdown@279; Thread@299; BenchmarkPlayback::Output@310; BenchmarkPlayback::Error@333; BenchmarkPlayback::InputExhausted@342
Dependencies: ADTSDemuxer.h@5; BufferMediaResource.h@6; FlacDemuxer.h@7; FuzzingInterface.h@8; MP3Demuxer.h@9; MP4Demuxer.h@10; MediaDataDecoderProxy.h@11; OggDemuxer.h@12; PDMFactory.h@13; PlatformDecoderModule.h@14; QueueObject.h@15; WaveDemuxer.h@16; WebMDemuxer.h@17; mozilla/AbstractThread.h@18; mozilla/SpinEventLoopUntil.h@19; mozilla/TaskQueue.h@20; mozilla/gfx/gfxVars.h@21; systemservices/MediaUtils.h@22

`dom/media/fuzz/moz.build` | `f6fe73da6d45ee85b11c990e596a914e1cf1e527` | 655 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@11; /tools/fuzzing/libfuzzer-config.mozbuild@27

`dom/media/gmp-plugin-openh264/fakeopenh264.info` | `814a96be320359152e90ca15793143c292724983` | 116 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp-plugin-openh264/gmp-fake-openh264.cpp` | `e16817a3a6bf9d971f155661cd687122491be9d8` | 14829 bytes | source | UTF-8 | mode 100644
Declarations: FakeVideoEncoder@78; FakeVideoDecoder@79; EncodedFrame@84; SPSNalu@85; PPSNalu@89; IDRNalu@93; SelfDestruct@110; SelfDestruct@112; FakeVideoEncoder@123; FakeVideoEncoder@125; AveragePlane@278; FakeVideoDecoder@296; host_@299
Dependencies: assert.h@36; stdint.h@37; cstring@39; iostream@40; gmp-platform.h@42; gmp-video-decode.h@43; gmp-video-encode.h@44; gmp-video-frame-encoded.h@45; gmp-video-frame-i420.h@46; gmp-video-host.h@47; mozilla/PodOperations.h@48

`dom/media/gmp-plugin-openh264/moz.build` | `b06663b5a3d57200643cf055703436dd839411ef` | 554 bytes | build-registration | UTF-8 | mode 100644

`dom/media/gmp/CDMStorageIdProvider.cpp` | `a3e1cdc8d8609c2a27098fe9a9ba4604f9ea65c6` | 1977 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; CDMStorageIdProvider::ComputeStorageId@19
Dependencies: CDMStorageIdProvider.h@5; GMPLog.h@7; mozilla/IntegerPrintfMacros.h@8; nsCOMPtr.h@9; nsICryptoHash.h@10; rlz/lib/machine_id.h@13

`dom/media/gmp/CDMStorageIdProvider.h` | `4e941c6c27b5c09750acce23f6b1e1bc398695fa` | 1273 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; CDMStorageIdProvider@18
Dependencies: nsString.h@14

`dom/media/gmp/ChromiumCDMAdapter.cpp` | `3afba39c6a92dcfe2ef2afc5d2592e51d80729af` | 10480 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@37; ChromiumCDMAdapter::SetAdaptee@51; ChromiumCdmHost@53; ChromiumCdmHostCompat@62; TakeToCDMHostFile@72; ChromiumCDMAdapter::GMPInit@79; ChromiumCDMAdapter::GMPShutdown@173; DWORD@200; GetDosDeviceNames@231; GetDeviceMapping@258; InitializeHooks@267; mPath@285; HostFile::~HostFile@287; mPath@300; HostFile::HostFile@309; HostFile::TakePlatformFile@315
Dependencies: ChromiumCDMAdapter.h@5; utility@7; GMPLog.h@9; WidevineUtils.h@10; content_decryption_module.h@11; content_decryption_module_ext.h@12; gmp-api/gmp-entrypoints.h@13; gmp-api/gmp-video-codec.h@14; mozilla/HelperMacros.h@15; mozilla/PodOperations.h@16; mozilla/dom/KeySystemNames.h@17; strsafe.h@20; windows.h@21; unordered_map@23; vector@24; WinUtils.h@26; nsWindowsDllInterceptor.h@27; fcntl.h@29; sys/stat.h@30; sys/types.h@31; unistd.h@32

`dom/media/gmp/ChromiumCDMAdapter.h` | `5f9886a20e364fcaf308e7022d94b0d6ab009e10` | 2073 bytes | source | UTF-8 | mode 100644
Declarations: GMPPlatformAPI@17; mozilla@19; nsString@22; nsCString@24; HostFile@27; HostFileData@41; mBinary@43; mBinary@46; ChromiumCDMAdapter@54
Dependencies: utility@8; GMPLoader.h@10; GMPUtils.h@11; content_decryption_module_ext.h@12; nsString.h@13; nsTArray.h@14; prlink.h@15

`dom/media/gmp/ChromiumCDMCallback.h` | `4d5a7f176f8bd132628bc23f5ade81c6ab8da412` | 1884 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; ErrorResult@14; ChromiumCDMCallback@17
Dependencies: mozilla/CDMProxy.h@8; mozilla/dom/MediaKeyMessageEventBinding.h@9; mozilla/dom/MediaKeyStatusMapBinding.h@10; mozilla/gmp/GMPTypes.h@11

`dom/media/gmp/ChromiumCDMCallbackProxy.cpp` | `fbd80bdfbac1b5c33b397f4cfd27574adb622119` | 6646 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ChromiumCDMCallbackProxy::ResolvePromise@39; ToDOMMediaKeyStatus@82; ChromiumCDMCallbackProxy::SessionClosed@138; ChromiumCDMCallbackProxy::QueryOutputProtectionStatus@145; ChromiumCDMCallbackProxy::Terminated@150; ChromiumCDMCallbackProxy::Shutdown@155
Dependencies: ChromiumCDMCallbackProxy.h@5; type_traits@7; ChromiumCDMProxy.h@9; content_decryption_module.h@10

`dom/media/gmp/ChromiumCDMCallbackProxy.h` | `c47e878f013e0f4400220e511fc17d010e5f0868` | 2021 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ChromiumCDMCallbackProxy@14; mProxy@18
Dependencies: ChromiumCDMCallback.h@8; ChromiumCDMProxy.h@9; nsThreadUtils.h@10

`dom/media/gmp/ChromiumCDMChild.cpp` | `b5b00e4e3176580f2f17b431cfc85b120c7a0554` | 35393 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@23; mPlugin@26; ChromiumCDMChild::ClampException@31; ChromiumCDMChild::ClampKeyStatus@50; ChromiumCDMChild::TimerExpired@69; CDMShmemBuffer@81; mProtocol@84; CDMShmemBuffer@92; ExtractShmem@127; ToString@144; StringJoin@145; ChromiumCDMChild::Allocate@150; ChromiumCDMChild::SetTimer@186; NewGMPTask@192; ChromiumCDMChild::GetCurrentWallTime@196; ChromiumCDMChild::CallMethod@201; ChromiumCDMChild::OnResolvePromise@271; ChromiumCDMChild::QueryOutputProtectionStatus@371; ChromiumCDMChild::OnInitialized@378; ChromiumCDMChild::CreateFileIO@387; ChromiumCDMChild::RequestStorageId@396; ChromiumCDMChild::~ChromiumCDMChild@422; ChromiumCDMChild::IsOnMessageLoopThread@426; ChromiumCDMChild::ActorDestroy@430; ChromiumCDMChild::PurgeShmems@442; ChromiumCDMChild::RecvPurgeShmems@449; ChromiumCDMChild::HasShmemOfSize@647; ChromiumCDMChild::RecvDeinitializeVideoDecoder@764; ChromiumCDMChild::RecvResetVideoDecoder@776; ChromiumCDMChild::ReturnOutput@857; ChromiumCDMChild::RecvDrain@891; ChromiumCDMChild::RecvDestroy@912; ChromiumCDMChild::RecvGiveBuffer@923; ChromiumCDMChild::GiveBuffer@930
Dependencies: ChromiumCDMChild.h@5; type_traits@7; CDMStorageIdProvider.h@9; GMPContentChild.h@10; GMPLog.h@11; GMPMessageUtils.h@12; GMPPlatform.h@13; GMPUtils.h@14; WidevineFileIO.h@15; WidevineUtils.h@16; WidevineVideoFrame.h@17; base/time.h@18; mozilla/ScopeExit.h@19; nsPrintfCString.h@20; nsReadableUtils.h@21

`dom/media/gmp/ChromiumCDMChild.h` | `0406a2cb92870f52b0296b45723e7f5c12223926` | 6896 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; GMPContentChild@15; ChromiumCDMChild@17; SimpleMap@135; MozPromise@147
Dependencies: SimpleMap.h@8; WidevineVideoFrame.h@9; content_decryption_module.h@10; mozilla/gmp/PChromiumCDMChild.h@11

`dom/media/gmp/ChromiumCDMCompat.h` | `ae7fce0e41d64b1c5d2130df7a2be7c80e92bb81` | 4938 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; ChromiumCDMCompat@12; mCDM@15
Dependencies: content_decryption_module.h@8

`dom/media/gmp/ChromiumCDMParent.cpp` | `7607a11a0e3581f78886abd2bb51b6c4964319a5` | 52441 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; NS_ConvertUTF16toUTF8@161; ChromiumCDMParent::SendBufferToCDM@371; ChromiumCDMParent::Decrypt@385; ChromiumCDMParent::Recv__delete__@418; ChromiumCDMParent::ResolvePromise@486; ChromiumCDMParent::RejectPromiseShutdown@525; ChromiumCDMParent::RecvOnQueryOutputProtectionStatus@626; ToDecryptStatus@662; ChromiumCDMParent::RecvIncreaseShmemPoolSize@747; ChromiumCDMParent::PurgeShmems@773; ChromiumCDMParent::EnsureSufficientShmems@792; ChromiumCDMParent::ReorderAndReturnOutput@931; ChromiumCDMParent::RecvDecodeFailed@1101; ChromiumCDMParent::RecvShutdown@1126; ChromiumCDMParent::ActorDestroy@1133; ChromiumCDMParent::DecryptAndDecodeFrame@1241; ChromiumCDMParent::FlushVideoDecoder@1277; ChromiumCDMParent::RecvResetVideoDecoderComplete@1299; ChromiumCDMParent::Drain@1310; ChromiumCDMParent::RecvDrainComplete@1327; ChromiumCDMParent::ShutdownVideoDecoder@1342; ChromiumCDMParent::Shutdown@1367
Dependencies: ChromiumCDMParent.h@5; AnnexB.h@7; ChromiumCDMCallback.h@8; ChromiumCDMCallbackProxy.h@9; ChromiumCDMProxy.h@10; GMPContentChild.h@11; GMPContentParent.h@12; GMPLog.h@13; GMPService.h@14; GMPUtils.h@15; H264.h@16; VideoUtils.h@17; content_decryption_module.h@18; mozilla/ScopeExit.h@19; mozilla/StaticPrefs_media.h@20; mozilla/dom/MediaKeyMessageEventBinding.h@21; mozilla/gmp/GMPTypes.h@22

`dom/media/gmp/ChromiumCDMParent.h` | `8ee22bc67cba0b94550687db244a3703a8d8499e` | 9819 bytes | source | UTF-8 | mode 100644
Declarations: ChromiumCDMCallback@21; mozilla@23; ErrorResult@25; MediaRawData@26; ChromiumCDMProxy@27; gmp@29; GMPContentParent@31; ChromiumCDMParent@38; MozPromise@43; PluginId@51
Dependencies: DecryptJob.h@8; GMPCrashHelper.h@9; GMPCrashHelperHolder.h@10; GMPMessageUtils.h@11; ImageContainer.h@12; PlatformDecoderModule.h@13; ReorderQueue.h@14; mozilla/Maybe.h@15; mozilla/RefPtr.h@16; mozilla/Span.h@17; mozilla/gmp/PChromiumCDMParent.h@18; nsTHashMap.h@19

`dom/media/gmp/ChromiumCDMProxy.cpp` | `513c170ae352b211bc305f2acf4ca58ade251d61` | 24239 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; mGMPThread@30; ChromiumCDMProxy::~ChromiumCDMProxy@34; ChromiumCDMProxy::OnCDMCreated@146; ChromiumCDMProxy::ShutdownCDMIfExists@167; ChromiumCDMProxy::IsOnOwnerThread@191; ToCDMInitDataType@208; ChromiumCDMProxy::QueryOutputProtectionStatus@342; StaticPrefs::media_widevine_hdcp_protection_mask@397; ChromiumCDMProxy::Shutdown@407; ChromiumCDMProxy::ResolvePromise@464; ChromiumCDMProxy::OnKeyStatusesChange@530; ChromiumCDMProxy::Decrypt@601; ChromiumCDMProxy::Terminated@632; ChromiumCDMProxy::GetCDMParent@638
Dependencies: ChromiumCDMProxy.h@5; ChromiumCDMCallbackProxy.h@7; GMPService.h@8; GMPUtils.h@9; MediaResult.h@10; content_decryption_module.h@11; mozilla/StaticPrefs_media.h@12; mozilla/dom/MediaKeySession.h@13; mozilla/dom/MediaKeysBinding.h@14; nsPrintfCString.h@15

`dom/media/gmp/ChromiumCDMProxy.h` | `bf39c76151c7bc141a0ef56548ee48371153e369` | 4802 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ErrorResult@14; MediaRawData@15; DecryptJob@16; ChromiumCDMCallbackProxy@17; ChromiumCDMProxy@18
Dependencies: ChromiumCDMParent.h@8; mozilla/AbstractThread.h@9; mozilla/CDMProxy.h@10

`dom/media/gmp/DecryptJob.cpp` | `5ad1479227134211ce08347027674677e67c29c8` | 1611 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@9; mId@14; DecryptJob::Ensure@16; DecryptJob::PostResult@20
Dependencies: DecryptJob.h@5; mozilla/Atomics.h@7

`dom/media/gmp/DecryptJob.h` | `994e6496da051d035f6eb9f3ac1a6b235e26ae15` | 805 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; DecryptJob@13
Dependencies: mozilla/CDMProxy.h@8; mozilla/Span.h@9

`dom/media/gmp/GMPCallbackBase.h` | `7c8ac52b1fc9a685dcb8f2fb3ec4ed34b530cb6c` | 698 bytes | source | UTF-8 | mode 100644
Declarations: GMPCallbackBase@10
Dependencies: nsISupportsImpl.h@8

`dom/media/gmp/GMPChild.cpp` | `bbe722074b37c4caea62b988b66611543d3575f0` | 25706 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@63; gmp@64; mGMPMessageLoop@74; GMPChild::~GMPChild@80; GMPChild::Shutdown@142; GMPChild::RecvPreloadLibs@165; GMPChild::GetUTF8LibPath@245; GMPChild::GetPluginName@317; CloneFile@344; GetParentFile@350; NS_SUCCEEDED@444; GMPChild::MakeCDMHostVerificationPaths@461; ToCString@509; StringJoin@510; GMPChild::RecvStartPlugin@515; GMPChild::GMPMessageLoop@572; GMPChild::ActorDestroy@574; GMPChild::ProcessingError@616; GMPChild::GetGMPTimers@636; GMPChild::GetGMPStorage@647; GMPChild::RecvCrashPluginNow@658; GMPChild::RecvCloseActive@663; GMPChild::GMPContentChildActorDestroy@694; GMPChild::RecvPreferenceUpdate@712; GMPChild::RecvShutdown@717; GMPChild::RecvUnblockUntrustedModulesThread@780; mozilla::services::GetObserverService@782
Dependencies: GMPChild.h@5; algorithm@7; ChildProfilerController.h@9; ChromiumCDMAdapter.h@10; GeckoProfiler.h@11; base/command_line.h@12; base/task.h@13; dlfcn.h@15; mozilla/Sandbox.h@17; GMPContentChild.h@20; GMPLoader.h@21; GMPLog.h@22; GMPPlatform.h@23; GMPProcessChild.h@24; GMPProcessParent.h@25; GMPUtils.h@26; GMPVideoDecoderChild.h@27; GMPVideoEncoderChild.h@28; GMPVideoHost.h@29; gmp-video-decode.h@30; gmp-video-encode.h@31; mozilla/BackgroundHangMonitor.h@32; mozilla/FOGIPC.h@33; mozilla/TextUtils.h@34; mozilla/glean/GleanTestsTestMetrics.h@35; mozilla/ipc/CrashReporterClient.h@36; mozilla/ipc/Endpoint.h@37; mozilla/ipc/ProcessChild.h@38; nsDebugImpl.h@39; nsExceptionHandler.h@40; nsIFile.h@41; nsIXULRuntime.h@42; nsReadableUtils.h@43; nsThreadManager.h@44; nsXPCOM.h@45; nsXPCOMPrivate.h@46; nsXULAppAPI.h@47; prio.h@48; stdlib.h@50; WinUtils.h@52; mozilla/Services.h@53; mozilla/StaticPrefs_dom.h@54; mozilla/WinDllServices.h@55; nsIObserverService.h@56; unistd.h@58

`dom/media/gmp/GMPChild.h` | `29420c99389b41b876e49463070e5aae2d770263` | 3246 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; ChildProfilerController@17; gmp@19; GMPContentChild@21; GMPChild@23
Dependencies: GMPLoader.h@8; GMPStorageChild.h@9; GMPTimerChild.h@10; gmp-entrypoints.h@11; mozilla/gmp/PGMPChild.h@12; prlink.h@13

`dom/media/gmp/GMPContentChild.cpp` | `df07129a978dec331c46e6db43b9e67fd293a5ae` | 4303 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; GMPContentChild::GMPMessageLoop@17; GMPContentChild::ActorDestroy@32; GMPContentChild::ProcessingError@36; GMPContentChild::AllocPGMPVideoDecoderChild@41; GMPContentChild::AllocPGMPVideoEncoderChild@46; GMPContentChild::CloseActive@112; GMPContentChild::IsUsed@132
Dependencies: GMPContentChild.h@5; ChromiumCDMChild.h@7; ChromiumCDMCompat.h@8; GMPChild.h@9; GMPUtils.h@10; GMPVideoDecoderChild.h@11; GMPVideoEncoderChild.h@12; base/task.h@13

`dom/media/gmp/GMPContentChild.h` | `17a227714e3e25650661c3a6531b288bdc4baebb` | 2027 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; GMPChild@16; GMPContentChild@22; GMPContentChild@28
Dependencies: mozilla/gmp/PGMPContentChild.h@8; mozilla/SandboxTestingChild.h@11

`dom/media/gmp/GMPContentParent.cpp` | `243b065c16afe9e7c5ace1582cd92a020aabc45d` | 7513 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; mParent@24; GMPContentParent::~GMPContentParent@34; GMPContentParent::ActorDestroy@44; GMPContentParent::ChromiumCDMDestroyed@51; GMPContentParent::VideoDecoderDestroyed@60; GMPContentParent::VideoEncoderDestroyed@70; GMPContentParent::AddCloseBlocker@80; GMPContentParent::RemoveCloseBlocker@88; GMPContentParent::CloseIfUnused@98; GMPContentParent::GMPEventTarget@125; GMPContentParent::GetGMPVideoDecoder@166; GMPContentParent::GetGMPVideoEncoder@184; GMPContentParentCloseBlocker::Destroy@202
Dependencies: GMPContentParent.h@5; ChromiumCDMParent.h@7; GMPLog.h@8; GMPParent.h@9; GMPServiceChild.h@10; GMPVideoDecoderParent.h@11; GMPVideoEncoderParent.h@12; base/task.h@13; mozIGeckoMediaPluginService.h@14; mozilla/Logging.h@15

`dom/media/gmp/GMPContentParent.h` | `254ebe1e7745360db5bbdfd3e32f0d0e6fa6c907` | 3218 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; GMPContentParentCloseBlocker@14; GMPParent@15; GMPVideoDecoderParent@16; GMPVideoEncoderParent@17; ChromiumCDMParent@18; GMPContentParent@24; SetDisplayName@46; SetPluginId@50; GetPluginId@51; SetPluginType@52; GetPluginType@53; Close@68; GMPContentParentCloseBlocker@81; mParent@86
Dependencies: GMPNativeTypes.h@8; mozilla/gmp/PGMPContentParent.h@9; nsISupportsImpl.h@10

`dom/media/gmp/GMPCrashHelper.h` | `2de7cb4cd9eb2830e98d1df481c8c0071e780913` | 1081 bytes | source | UTF-8 | mode 100644
Declarations: nsPIDOMWindowInner@11; mozilla@13; GMPCrashHelper@20
Dependencies: MainThreadUtils.h@8; nsISupportsImpl.h@9

`dom/media/gmp/GMPCrashHelperHolder.cpp` | `a6d03396eeffbd33706691f17700719bb382b58b` | 888 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; GMPCrashHelperHolder::SetCrashHelper@14; GMPCrashHelperHolder::GetCrashHelper@18; GMPCrashHelperHolder::MaybeDisconnect@20
Dependencies: GMPCrashHelperHolder.h@5; GMPService.h@7; mozilla/RefPtr.h@8; mozilla/ipc/ProtocolUtils.h@9; nsPIDOMWindow.h@10

`dom/media/gmp/GMPCrashHelperHolder.h` | `3d2c55cf818f5b35d65b38abd04bc237f06dbd10` | 2713 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; GMPCrashHelperHolder@48
Dependencies: GMPCrashHelper.h@8; mozilla/RefPtr.h@9

`dom/media/gmp/GMPDiskStorage.cpp` | `c33f8d36a7378713c5c9dee2d9fa99b7791d7785` | 15048 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; GMPDiskStorage@76; mNodeId@79; Init@95; NS_FAILED@108; OpenFileMode@342; RemoveStorageFile@423; Record@436; mFilename@438
Dependencies: GMPLog.h@5; GMPParent.h@6; gmp-storage.h@7; mozilla/EndianUtils.h@8; nsAppDirectoryServiceDefs.h@9; nsClassHashtable.h@10; nsDirectoryServiceDefs.h@11; nsDirectoryServiceUtils.h@12; nsHashKeys.h@13; nsServiceManagerUtils.h@14; plhash.h@15; prio.h@16

`dom/media/gmp/GMPLoader.cpp` | `17d0bbddb21c239b97ceab5479f93c3d2a46b789` | 9652 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@27; PassThroughGMPAdapter@28; IsAppLockerPolicyPresent@85; EnsureAppLockerCacheIsWarm@108; SrpIoctlBuffer@117; mozilla::Span@148; GMPLoader::Shutdown@240; WinSandboxStarter@247; LinuxSandboxStarter@264; Make@271; MakeSandboxStarter@288; GMPLoader::GMPLoader@298; GMPLoader::CanSandbox@300
Dependencies: GMPLoader.h@5; GMPLog.h@7; gmp-entrypoints.h@8; nsExceptionHandler.h@9; prenv.h@10; prerror.h@11; prlink.h@12; mozilla/sandboxTarget.h@14; nsWindowsHelpers.h@15; mozilla/Sandbox.h@18; mozilla/SandboxInfo.h@19; mozilla/SandboxProfilerObserver.h@20; windows.h@24

`dom/media/gmp/GMPLoader.h` | `5de4de8c47b7d1f6a72d4c7fcdd222011de3f712` | 2609 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; SandboxStarter@21; GMPAdapter@28; GMPLoader@49
Dependencies: stdint.h@8; gmp-entrypoints.h@10; mozilla/UniquePtr.h@11; nsString.h@12; prlink.h@13; mozilla/Sandbox.h@16

`dom/media/gmp/GMPLog.h` | `e6be9f0d8a388bdd81bb0d741bd6aed7a1425125` | 1049 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12
Dependencies: content_decryption_module.h@8; gmp-video-codec.h@9; mozilla/Logging.h@10

`dom/media/gmp/GMPMemoryStorage.cpp` | `0cdd9d73db60a7d2f35e87e2bf76bce926469f3a` | 2542 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@9; GMPMemoryStorage@15; GMPMemoryStorage@17; Record@74
Dependencies: GMPLog.h@5; GMPStorage.h@6; nsClassHashtable.h@7

`dom/media/gmp/GMPMessageUtils.h` | `1b32bc443a5ff867c534fec149b9f6137561ca12` | 10370 bytes | source | UTF-8 | mode 100644
Declarations: IPC@16; ParamTraits@19; ParamTraits@24; ParamTraits@28; ParamTraits@33; ParamTraits@39; ParamTraits@44; ParamTraits@49; ParamTraits@54; ParamTraits@59; ParamTraits@64; ParamTraits@69; MOZ_ENUM_SERIALIZER_ALLOW_SENTINEL_UPPER_BOUND@74; ParamTraits@79; ParamTraits@84; ParamTraits@90; ParamTraits@96; ParamTraits@102; ParamTraits@108; ParamTraits@114; CDMVideoFormatValidator@120; IsLegalValue@123; ParamTraits@143; ParamTraits@150; ParamTraits@157; ParamTraits@164; ParamTraits@171; ParamTraits@179; GMPVideoCodec@180; Write@182; Read@212
Dependencies: GMPNativeTypes.h@8; GMPSanitizedExports.h@9; gmp-video-codec.h@10; gmp-video-frame-encoded.h@11; ipc/EnumSerializer.h@12; ipc/IPCMessageUtilsSpecializations.h@13; mozilla/Attributes.h@14

`dom/media/gmp/GMPNativeTypes.h` | `1b0da3d2a6498f1c4812e4cdc31db6a7f0d2bd89` | 366 bytes | source | UTF-8 | mode 100644
Declarations: class@8

`dom/media/gmp/GMPParent.cpp` | `fdf156562dcee9df832addb66976658c0c76ad17` | 49081 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@58; mGMPEventTarget@83; GMPParent::~GMPParent@88; GMPParent::CloneFrom@94; GMPParent::InitForClearkey@169; GMPParent::Crash@308; NotifyGMPProcessLoadedTask@314; mGMPParent@320; ipc::shared_memory::UsingPosixShm@329; GMPParent::LoadProcess@367; NS_WARN_IF@384; GMPParent::OnPreferenceChange@472; GMPParent::RecvPGMPContentChildDestroyed@483; GMPParent::RecvFOGData@491; ModulesTrustRunnable@501; mRunAtNormalPriority@510; GMPParent::CloseIfUnused@541; GMPParent::CloseActive@562; GMPParent::MarkForDeletion@579; GMPParent::IsMarkedForDeletion@584; GMPParent::Shutdown@586; NotifyGMPShutdownTask@616; Runnable@619; GMPParent::ChildTerminated@633; GMPParent::DeleteProcess@653; java::GeckoProcessManager::Selector::GlobalRef@726; GMPParent::State@739; GMPParent::GMPEventTarget@741; GMPParent::EnsureProcessLoaded@787; GMPParent::AddCrashAnnotations@803; GMPParent::GetCrashID@817; GMPParent::ActorDestroy@842; GMPParent::AllocPGMPStorageParent@882; GMPParent::AllocPGMPTimerParent@890; GMPParent::ReadGMPMetaData@904; ApplyGlibcWorkaround@931; ApplyOleaut32@945; GMPParent::ReadGMPInfoFile@997; GMPParent::ReadChromiumManifestFile@1105; GMPParent::CanBeSharedCrossNodeIds@1282; GMPParent::CanBeUsedFrom@1291; GMPParent::SetNodeId@1295; GMPParent::UpdatePluginType@1300; GMPParent::GetPluginId@1322; GMPParent::ResolveGetContentParentPromises@1324; GMPParent::OpenPGMPContent@1335; GMPParent::RejectGetContentParentPromises@1362; GMPParent::ForgetGMPContentParent@1401; GMPParent::EnsureProcessLoaded@1406; GMPParent::IncrementGMPContentChildCount@1414; GMPParent::GetPluginBaseName@1416; GMPParent::PreTranslateBins@1419; GMPParent::PreTranslateBinsWorker@1429
Dependencies: GMPParent.h@5; CDMStorageIdProvider.h@7; ChromiumCDMAdapter.h@8; GMPContentParent.h@9; GMPLog.h@10; GMPTimerParent.h@11; GeckoProfiler.h@12; MediaResult.h@13; mozIGeckoMediaPluginService.h@14; mozilla/Casting.h@15; mozilla/FOGIPC.h@16; mozilla/dom/KeySystemNames.h@17; mozilla/dom/WidevineCDMManifestBinding.h@18; mozilla/ipc/Endpoint.h@19; mozilla/ipc/GeckoChildProcessHost.h@20; mozilla/SandboxInfo.h@22; mozilla/ipc/SharedMemoryHandle.h@23; ProfilerParent.h@25; mozilla/SSE.h@26; mozilla/Services.h@27; mozilla/StaticPrefs_media.h@28; mozilla/SyncRunnable.h@29; mozilla/Telemetry.h@30; mozilla/glean/IpcMetrics.h@31; nsComponentManagerUtils.h@32; nsIObserverService.h@33; nsIRunnable.h@34; nsIWritablePropertyBag2.h@35; nsPrintfCString.h@36; nsThreadUtils.h@37; runnable_utils.h@38; PDMFactory.h@40; WMFDecoderModule.h@41; mozilla/FileUtilsWin.h@42; mozilla/WinDllServices.h@43; mozilla/java/GeckoProcessManagerWrappers.h@46; mozilla/java/GeckoProcessTypeWrappers.h@47; base/process_util.h@50; nsMacUtilsImpl.h@51

`dom/media/gmp/GMPParent.h` | `43c5af336e0c4d9c3174e6dce077152a4bfe10a4` | 8234 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; GMPCapability@28; mAPITags@33; GMPCapability@34; class@47; GMPContentParent@55; GMPParent@57; GetPluginType@121; GetDirectory@132; IsUsed@182
Dependencies: GMPNativeTypes.h@8; GMPProcessParent.h@9; GMPServiceParent.h@10; GMPStorageParent.h@11; GMPTimerParent.h@12; GMPVideoDecoderParent.h@13; GMPVideoEncoderParent.h@14; mozilla/Atomics.h@15; mozilla/MozPromise.h@16; mozilla/gmp/PGMPParent.h@17; mozilla/ipc/CrashReporterHelper.h@18; nsCOMPtr.h@19; nsIFile.h@20; nsISupports.h@21; nsString.h@22; nsTArray.h@23; nscore.h@24

`dom/media/gmp/GMPPlatform.cpp` | `fdee0b2e243c4e9e6a617935f35d06bdaf308ba9` | 8309 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; GMPRunnable@40; mCancelOnShutdown@45; GMPSyncRunnable@63; Runnable@66; WaitUntilDone@70; GMPThreadImpl@99; CreateThread@113; RunOnMainThread@129; SyncRunOnMainThread@142; MOZ_CAPABILITY@156; CreateMutex@170; SetTimerOnMainThread@195; GetClock@204; InitPlatformAPI@212; AddPluginObject@227; RemovePluginObject@232; ShutdownPlatformAPI@237; SendFOGData@246; GMPThreadImpl::GMPThreadImpl@263; GMPThreadImpl::~GMPThreadImpl@265; GMPThreadImpl::Post@271; GMPThreadImpl::Join@287; GMPMutexImpl::GMPMutexImpl@297; GMPMutexImpl::~GMPMutexImpl@299; GMPMutexImpl::Destroy@301; GMPMutexImpl::Acquire@304; GMPMutexImpl::Release@306; NewGMPTask@309; Task@310; mFunction@313
Dependencies: GMPPlatform.h@5; GMPChild.h@7; GMPStorageChild.h@8; GMPTimerChild.h@9; base/task.h@10; base/thread.h@11; base/time.h@12; mozilla/Atomics.h@13; mozilla/Monitor.h@14; mozilla/Mutex.h@15; mozilla/ReentrantMonitor.h@16; mozilla/StaticMutex.h@17; nsThreadUtils.h@18; mozilla/UntrustedModulesProcessor.h@21; ctime@24

`dom/media/gmp/GMPPlatform.h` | `7f45236d0f32d9ab396cc173c010bb474bff08aa` | 1214 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; ipc@14; ByteBuf@15; gmp@18; GMPChild@20; class@24
Dependencies: gmp-platform.h@8; mozilla/RefPtr.h@9; mozilla/gmp/PGMPChild.h@10

`dom/media/gmp/GMPProcessChild.cpp` | `971ddc265c0d482b1e3f62532778a1e89e443be9` | 1629 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; GMPProcessChild::InitStatics@16; GMPProcessChild::Init@27; GMPProcessChild::CleanUp@48
Dependencies: GMPProcessChild.h@5; base/command_line.h@7; base/string_util.h@8; mozilla/GeckoArgs.h@9

`dom/media/gmp/GMPProcessChild.h` | `b047b9624bb41269079bea795e74343c651ece9f` | 1010 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; GMPLoader@13; GMPProcessChild@15; mozilla@17; UseNativeEventProcessing@24; UseXPCOM@25
Dependencies: GMPChild.h@8; mozilla/ipc/ProcessChild.h@9

`dom/media/gmp/GMPProcessParent.cpp` | `e9d36cf3923b1ad7974ee9843cde4f1335b426bb` | 12208 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@40; GMPProcessParent::InitStaticMainThread@52; GMPProcessParent::~GMPProcessParent@83; GMPProcessParent::Launch@85; PrefSerializerRunnable@86; mMonitor@90; GMPProcessParent::Delete@251; GMPProcessParent::DoDelete@257; GMPProcessParent::IsMacSandboxLaunchEnabled@268; GMPProcessParent::SetRequiresWindowServer@272; GMPProcessParent::FillMacSandboxInfo@276
Dependencies: GMPProcessParent.h@5; GMPUtils.h@7; nsIRunnable.h@8; WinUtils.h@10; string@12; GMPLog.h@14; base/process_util.h@15; base/string_util.h@16; mozilla/GeckoArgs.h@17; mozilla/StaticPrefs_media.h@18; mozilla/ipc/ProcessChild.h@19; mozilla/ipc/ProcessUtils.h@20; mozilla/java/GeckoProcessManagerWrappers.h@22; nsFmtString.h@24; mozilla/Omnijar.h@27; mozilla/Preferences.h@28; mozilla/Sandbox.h@29; mozilla/SandboxSettings.h@30; nsMacUtilsImpl.h@31

`dom/media/gmp/GMPProcessParent.h` | `03c0ea661d27b5e95bd8905b6f6d4b8c6db94a4a` | 3669 bytes | source | UTF-8 | mode 100644
Declarations: nsIRunnable@15; mozilla@17; GMPProcessParent@19; UseXPCOM@31; GetMacSandboxType@52
Dependencies: base/basictypes.h@8; base/file_path.h@9; base/thread.h@10; mozilla/ipc/GeckoChildProcessHost.h@11; mozilla/media/MediaUtils.h@12; nsIFile.h@13

`dom/media/gmp/GMPSanitizedExports.h` | `9b2d89ebe1a22ecb5a5bc64fb660a2bcd402a317` | 802 bytes | source | UTF-8 | mode 100644
Dependencies: content_decryption_module.h@18

`dom/media/gmp/GMPService.cpp` | `80e9b16c86449471724e3b8244d02ee8eb12e99c` | 18060 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@40; GetGMPLog@42; GetGMPLibraryLog@47; GetGMPLibraryLogLevel@52; gmp@75; GMPServiceCreateHelper@79; GetOrCreate@83; GMPServiceCreateHelper@102; GetOrCreateOnMainThread@106; GeckoMediaPluginService::GetGeckoMediaPluginService@153; mXPCOMWillShutdown@165; NS_SUCCEEDED@174; GeckoMediaPluginService::Init@233; MozPromiseHolder@262; GeckoMediaPluginService::GetContentParentForTest@308; GeckoMediaPluginService::ShutdownGMPThread@364; GeckoMediaPluginService::GetThread@398; GeckoMediaPluginService::GetThreadLocked@408; GeckoMediaPluginService::GetGMPThread@434; GeckoMediaPluginService::DisconnectCrashHelper@536
Dependencies: GMPService.h@5; ChromiumCDMParent.h@7; GMPLog.h@8; GMPParent.h@9; GMPProcessParent.h@10; GMPServiceChild.h@11; GMPServiceParent.h@12; GMPVideoDecoderParent.h@13; mozilla/AppShutdown.h@14; mozilla/ClearOnShutdown.h@15; mozilla/EventDispatcher.h@16; mozilla/dom/Document.h@17; mozilla/dom/PluginCrashedEvent.h@18; mozilla/ipc/GeckoChildProcessHost.h@19; nsThreadUtils.h@20; mozilla/SandboxInfo.h@22; VideoUtils.h@24; mozilla/Services.h@25; mozilla/SyncRunnable.h@26; nsAppDirectoryServiceDefs.h@27; nsComponentManagerUtils.h@28; nsDirectoryServiceDefs.h@29; nsDirectoryServiceUtils.h@30; nsGlobalWindowInner.h@31; nsHashKeys.h@32; nsIObserverService.h@33; nsIXULAppInfo.h@34; nsNativeCharsetUtils.h@35; nsXPCOMPrivate.h@36; prio.h@37; runnable_utils.h@38

`dom/media/gmp/GMPService.h` | `1518d36addcee1a6651830417e6b55dded76abcc` | 4296 bytes | source | UTF-8 | mode 100644
Declarations: nsIAsyncShutdownClient@21; nsIRunnable@22; nsISerialEventTarget@23; nsIThread@24; already_AddRefed@27; mozilla@29; GMPCrashHelper@31; MediaResult@32; gmp@38; GeckoMediaPluginService@46; XPCOMWillShutdownReceived@84; AssertOnGMPThread@90
Dependencies: GMPContentParent.h@8; GMPCrashHelper.h@9; gmp-video-codec.h@10; mozIGeckoMediaPluginService.h@11; mozilla/Atomics.h@12; mozilla/MozPromise.h@13; mozilla/gmp/GMPTypes.h@14; nsCOMPtr.h@15; nsClassHashtable.h@16; nsIObserver.h@17; nsString.h@18; nsTArray.h@19

`dom/media/gmp/GMPServiceChild.cpp` | `f7c5130f35a1ee15fcafc280181e7570e3e8316b` | 23560 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@26; GeckoMediaPluginServiceChild::GetSingleton@34; GeckoMediaPluginServiceChild::Init@48; GeckoMediaPluginServiceChild::~GeckoMediaPluginServiceChild@68; mozilla@213; mozilla@214; GMPCapabilityAndVersion@216; mName@218; ToString@229; GMPCapabilitiesToString@255; GeckoMediaPluginServiceChild::BeginShutdown@292; GeckoMediaPluginServiceChild::GetServiceChild@408; GeckoMediaPluginServiceChild::AddShutdownBlocker@475; GeckoMediaPluginServiceChild::RemoveShutdownBlocker@503; GeckoMediaPluginServiceChild::RemoveShutdownBlockerIfNeeded@512; GMPServiceChild::HasAlreadyBridgedTo@557; OpenPGMPServiceChild@572; mEndpoint@578; GMPServiceChild::Create@600; GMPServiceChild::RecvBeginShutdown@621; GMPServiceChild::HaveContentParents@631
Dependencies: GMPServiceChild.h@5; GMPLog.h@7; GMPParent.h@8; base/task.h@9; mozIGeckoMediaPluginChromeService.h@10; mozilla/ClearOnShutdown.h@11; mozilla/SchedulerGroup.h@12; mozilla/StaticMutex.h@13; mozilla/StaticPtr.h@14; mozilla/SyncRunnable.h@15; mozilla/dom/ContentChild.h@16; mozilla/ipc/Endpoint.h@17; nsCOMPtr.h@18; nsComponentManagerUtils.h@19; nsFmtString.h@20; nsIObserverService.h@21; nsReadableUtils.h@22; nsXPCOMPrivate.h@23; runnable_utils.h@24

`dom/media/gmp/GMPServiceChild.h` | `3464c886297d09071c6fdb686edc26abeba6a809` | 6797 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; GMPContentParent@19; GMPContentParentCloseBlocker@20; GMPServiceChild@21; GeckoMediaPluginServiceChild@23; MozPromise@68; GMPServiceChild@137; mService@144; Service@163
Dependencies: GMPService.h@8; MediaResult.h@9; base/process.h@10; mozilla/MozPromise.h@11; mozilla/dom/PContent.h@12; mozilla/gmp/PGMPServiceChild.h@13; mozilla/media/MediaUtils.h@14; nsRefPtrHashtable.h@15

`dom/media/gmp/GMPServiceParent.cpp` | `5c49c28804764c0b55c0531c9306e1a6182a72cc` | 71834 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@61; GeckoMediaPluginServiceParent::GetSingleton@71; mLoadPluginsFromDiskComplete@94; GeckoMediaPluginServiceParent::~GeckoMediaPluginServiceParent@98; GeckoMediaPluginServiceParent::Init@102; GMPPlatformString@174; GeckoMediaPluginServiceParent::InitStorage@204; GeckoMediaPluginServiceParent::EnsureInitialized@396; GeckoMediaPluginServiceParent::NotifySyncShutdownComplete@485; GeckoMediaPluginServiceParent::IsShuttingDown@490; GeckoMediaPluginServiceParent::UnloadPlugins@495; GeckoMediaPluginServiceParent::CrashPlugins@534; GeckoMediaPluginServiceParent::LoadFromEnvironment@544; NS_CopyNativeToUnicode@589; NotifyObserversTask@619; Runnable@622; GeckoMediaPluginServiceParent::PathRunnable::Run@641; mozilla@661; mozilla@662; mozilla@663; GeckoMediaPluginServiceParent::SendUnblockUntrustedModulesThread@799; GeckoMediaPluginServiceParent::TestTriggerMetrics@821; GeckoMediaPluginServiceParent::AddPluginDirectory@901; GeckoMediaPluginServiceParent::EnsurePluginsOnDiskScanned@980; GeckoMediaPluginServiceParent::CreateGMPParent@1119; Dummy@1276; GeckoMediaPluginServiceParent::GetStorageDir@1328; ReadSalt@1399; ExtractHostName@1591; MatchBaseDomain@1639; NodeFilter@1689; NodeFilter@1690; operator@1691; OriginFilter@1781; mSite@1784; BaseDomainFilter@1803; mBaseDomain@1805; MTimeFilter@1822; MTimeFilter@1823; IsModifiedAfter@1826; IsNodeIdValid@1925; GeckoMediaPluginServiceParent::ClearTemporaryStorage@1948; GeckoMediaPluginServiceParent::ClearStorage@1956; NS_FAILED@1973; mService@1997; GMPServiceParent::~GMPServiceParent@2008; GMPServiceParent::BeginShutdown@2013; OpenPGMPServiceParent@2118; mResult@2126; GMPServiceParent::Create@2140
Dependencies: GMPServiceParent.h@5; GMPDecoderModule.h@7; GMPLog.h@8; GMPParent.h@9; GMPVideoDecoderParent.h@10; base/task.h@11; mozilla/ClearOnShutdown.h@12; mozilla/Logging.h@13; mozilla/Preferences.h@14; mozilla/SchedulerGroup.h@15; mozilla/dom/ContentParent.h@16; mozilla/ipc/Endpoint.h@17; mozilla/ipc/GeckoChildProcessHost.h@18; nsFmtString.h@19; nsThreadUtils.h@20; mozilla/SandboxInfo.h@22; VideoUtils.h@24; mozilla/AppShutdown.h@25; mozilla/Services.h@26; mozilla/SpinEventLoopUntil.h@27; mozilla/StaticPrefs_media.h@28; mozilla/SyncRunnable.h@29; mozilla/UntrustedModulesData.h@31; nsAppDirectoryServiceDefs.h@33; nsComponentManagerUtils.h@34; nsDirectoryServiceDefs.h@35; nsDirectoryServiceUtils.h@36; nsHashKeys.h@37; nsIFile.h@38; nsIObserverService.h@39; nsIXULRuntime.h@40; nsNativeCharsetUtils.h@41; nsNetUtil.h@42; nsXPCOMPrivate.h@43; prio.h@44; runnable_utils.h@45; mozilla/dom/MediaKeys.h@48; mozilla/MFCDMParent.h@52; media/NdkMediaCrypto.h@56; media/NdkMediaDrm.h@57; mozilla/gfx/gfxVars.h@58

`dom/media/gmp/GMPServiceParent.h` | `390ef75c4e4cee813722a2345cdd67f283862f1f` | 11155 bytes | source | UTF-8 | mode 100644
Declarations: already_AddRefed@24; mozilla@28; OriginAttributesPattern@29; gmp@31; GMPParent@33; GMPServiceParent@34; GeckoMediaPluginServiceParent@36; Observer@105; DirectoryFilter@131; PathRunnable@174; EOperation@176; mDefer@188; MainThreadOnly@203; MainThreadOnly@205; GMPServiceParent@260
Dependencies: GMPService.h@8; GMPStorage.h@9; mozIGeckoMediaPluginChromeService.h@10; mozilla/MozPromise.h@11; mozilla/dom/ContentParent.h@12; mozilla/gmp/PGMPParent.h@13; mozilla/gmp/PGMPServiceParent.h@14; mozilla/media/MediaUtils.h@15; nsClassHashtable.h@16; nsIAsyncShutdown.h@17; nsNetUtil.h@18; nsRefPtrHashtable.h@19; nsTHashMap.h@20; nsThreadUtils.h@21

`dom/media/gmp/GMPSharedMemManager.cpp` | `c5e4e772bab5c08e1276cf93167f3b3fbb5ce9cf` | 2539 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@9; GMPSharedMemManager::~GMPSharedMemManager@11; GMPSharedMemManager::MgrPurgeShmems@83
Dependencies: GMPSharedMemManager.h@5; mozilla/ipc/SharedMemoryMapping.h@7

`dom/media/gmp/GMPSharedMemManager.h` | `62b871f1da7662ca67e5e5e9e19ba89abeae62e4` | 1380 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; GMPVideoi420FrameImpl@13; class@15; GMPSharedMemManager@17; MgrAllocShmem@28; MgrDecodedFrameDestroyed@31
Dependencies: mozilla/ipc/Shmem.h@8; nsTArray.h@9

`dom/media/gmp/GMPStorage.h` | `118e19dd2d02a3bac24e659869c47b73dfc3af16` | 1302 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; GMPStorage@16
Dependencies: gmp-storage.h@8; mozilla/AlreadyAddRefed.h@9; nsISupportsImpl.h@10; nsString.h@11; nsTArray.h@12

`dom/media/gmp/GMPStorageChild.cpp` | `125519623052613bdf343d55b1122da22d6334eb` | 8641 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@24; ToArray@26; mName@34; GMPRecordImpl::GetOwner@36; GMPRecordImpl::Open@41; GMPRecordImpl::OpenComplete@50; GMPRecordImpl::Read@60; GMPRecordImpl::Write@80; GMPRecordImpl::WriteComplete@89; GMPRecordImpl::Close@99; GMPRecordImpl::DestroyOwner@121; GMPStorageChild::GMPStorageChild@126; GMPStorageChild::HasRecord@157; GMPStorageChild::Open@172; GMPStorageChild::Read@189; GMPStorageChild::Close@228; GMPStorageChild::RecvShutdown@268; GMPStorageChild::ActorDestroy@277
Dependencies: GMPStorageChild.h@5; GMPChild.h@7; base/task.h@8; gmp-storage.h@9

`dom/media/gmp/GMPStorageChild.h` | `81faa20924f827f58a0424dd37e36be119aa3051` | 3053 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; GMPChild@18; GMPStorageChild@19; GMPRecordImpl@21; GMPStorageChild@52
Dependencies: gmp-platform.h@8; gmp-storage.h@9; mozilla/Mutex.h@10; mozilla/RecursiveMutex.h@11; mozilla/gmp/PGMPStorageChild.h@12; nsRefPtrHashtable.h@13; nsTHashtable.h@14

`dom/media/gmp/GMPStorageParent.cpp` | `1565224c8fcdc7015d58c9f52f800bace0ee78c8` | 6184 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; gmp@24; mNodeId@28; GMPStorageParent::Init@30; NS_FAILED@44; LOGD@136; GMPStorageParent::ActorDestroy@182; GMPStorageParent::Shutdown@188
Dependencies: GMPStorageParent.h@5; GMPParent.h@7; gmp-storage.h@8

`dom/media/gmp/GMPStorageParent.h` | `b80822999c8e7757eba3a519c7590cd7018d5783` | 1369 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; GMPStorageParent@14
Dependencies: GMPParent.h@8; GMPStorage.h@9; mozilla/gmp/PGMPStorageParent.h@10

`dom/media/gmp/GMPTimerChild.cpp` | `ef92b8ed2cc1e363162ff3479953ee2131990fb3` | 1514 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; mTimerCount@15; GMPTimerChild::~GMPTimerChild@19; GMPTimerChild::SetTimer@23
Dependencies: GMPTimerChild.h@5; GMPChild.h@7; GMPPlatform.h@8

`dom/media/gmp/GMPTimerChild.h` | `c23b476bcd55468672f6c179c4a29838f5e9c0eb` | 1005 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; GMPChild@17; GMPTimerChild@19
Dependencies: gmp-errors.h@8; gmp-platform.h@9; mozilla/Monitor.h@10; mozilla/gmp/PGMPTimerChild.h@11; nsHashKeys.h@12; nsTHashMap.h@13

`dom/media/gmp/GMPTimerParent.cpp` | `cd784a990dd7c06cf24307b91c230abcd96abda7` | 2560 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; gmp@21; mGMPEventTarget@24; GMPTimerParent::Shutdown@54; GMPTimerParent::ActorDestroy@69; GMPTimerParent::GMPTimerExpired@77; GMPTimerParent::TimerExpired@86
Dependencies: GMPTimerParent.h@5; memory@7; GMPLog.h@9; nsComponentManagerUtils.h@10

`dom/media/gmp/GMPTimerParent.h` | `328fb452d674535b276500cd11881bf3798e331f` | 1436 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; GMPTimerParent@16; Context@35; Context@36
Dependencies: mozilla/Monitor.h@8; mozilla/gmp/PGMPTimerParent.h@9; nsCOMPtr.h@10; nsITimer.h@11; nsTHashSet.h@12

`dom/media/gmp/GMPTypes.ipdlh` | `0ae59469f196dcd384d3e7a77e911f3c11af2ddd` | 3293 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; gmp@15; NodeIdParts@25; GMPVideoEncodedFrameData@44; GMPPlaneData@56; GMPVideoi420FrameData@62; CDMInputBuffer@73; CDMVideoDecoderConfig@86; CDMKeyInformation@96; CDMVideoPlane@102; CDMVideoFrame@107

`dom/media/gmp/GMPUtils.cpp` | `87f34a65b0ec0aa3c32a79235dcdcc1c9e5aca39` | 11599 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@24; ToHexString@36; ToHexString@50; FileExists@54; mMode@60; DirectoryEnumerator::Next@64; ReadIntoString@119; GMPInfoFileParser::Init@129; GMPInfoFileParser::Contains@166; GMPInfoFileParser::Get@172; HaveGMPFor@183; IsOnGMPThread@197; LogToConsole@208; GetGMPThread@219; Align16@227; I420FrameBufferSizePadded@232; SizeNumBytes@242; constexpr@277; constexpr@299; AdjustOpenH264NALUSequence@345; ToMediaResult@359
Dependencies: GMPUtils.h@5; bit@7; GMPLog.h@9; GMPService.h@10; VideoLimits.h@11; gmp-video-frame-encoded.h@12; mozIGeckoMediaPluginService.h@13; mozilla/Base64.h@14; mozilla/EndianUtils.h@15; nsCOMPtr.h@16; nsCRTGlue.h@17; nsDirectoryServiceDefs.h@18; nsIConsoleService.h@19; nsIFile.h@20; nsLiteralString.h@21; prio.h@22

`dom/media/gmp/GMPUtils.h` | `ca25619bf3b2611f6d45d9e984d840794320ea7d` | 2587 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoEncodedFrame@21; nsIFile@22; nsIDirectoryEnumerator@23; mozilla@25; DestroyPolicy@28; operator@29; DirectoryEnumerator@45; Mode@47; GMPInfoFileParser@61
Dependencies: MediaResult.h@8; gmp-errors.h@9; gmp-video-codec.h@10; mozilla/AbstractThread.h@11; mozilla/UniquePtr.h@12; nsCOMPtr.h@13; nsClassHashtable.h@14; nsStringFwd.h@15; nsTArray.h@16

`dom/media/gmp/GMPVideoDecoderChild.cpp` | `7fc72ff521e4991b080b8c23353b7b93ea4041c0` | 7361 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@16; mPlugin@19; GMPVideoDecoderChild::~GMPVideoDecoderChild@23; GMPVideoDecoderChild::MgrIsOnOwningThread@34; GMPVideoDecoderChild::Init@38; GMPVideoDecoderChild::Decoded@45; GMPVideoDecoderChild::ReceivedDecodedFrame@90; GMPVideoDecoderChild::InputDataExhausted@100; GMPVideoDecoderChild::DrainComplete@110; GMPVideoDecoderChild::ResetComplete@132; GMPVideoDecoderChild::Error@154; GMPVideoDecoderChild::RecvReset@210; GMPVideoDecoderChild::RecvDrain@228; GMPVideoDecoderChild::ActorDestroy@246
Dependencies: GMPVideoDecoderChild.h@5; GMPContentChild.h@7; GMPPlatform.h@8; GMPVideoEncodedFrameImpl.h@9; GMPVideoi420FrameImpl.h@10; mozilla/StaticPrefs_media.h@11; nsProxyRelease.h@12; nsThreadUtils.h@13; runnable_utils.h@14

`dom/media/gmp/GMPVideoDecoderChild.h` | `9e4ee1cb092b3f650ff7b22552202e4818807ba7` | 2591 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; GMPContentChild@17; GMPVideoDecoderChild@19
Dependencies: GMPSharedMemManager.h@8; GMPVideoHost.h@9; gmp-video-decode.h@10; mozilla/gmp/GMPTypes.h@11; mozilla/gmp/PGMPVideoDecoderChild.h@12; nsString.h@13

`dom/media/gmp/GMPVideoDecoderParent.cpp` | `5c1a9d9d69af2dc0d7db04e42b254463d62907e3` | 13553 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; mFrameCount@40; GMPVideoDecoderParent::MgrIsOnOwningThread@46; GMPVideoDecoderParent::Close@51; GMPVideoDecoderParent::Reset@153; GMPVideoDecoderParent::CancelResetCompleteTimeout@188; GMPVideoDecoderParent::Drain@195; GMPVideoDecoderParent::GetDisplayName@216; GMPVideoDecoderParent::Shutdown@226; GMPVideoDecoderParent::ActorDestroy@255; GMPVideoDecoderParent::RecvInputDataExhausted@364; GMPVideoDecoderParent::RecvDrainComplete@375; GMPVideoDecoderParent::RecvResetComplete@393; GMPVideoDecoderParent::RecvError@409; GMPVideoDecoderParent::RecvShutdown@425; GMPVideoDecoderParent::UnblockResetAndDrain@432
Dependencies: GMPVideoDecoderParent.h@5; GMPContentParent.h@7; GMPLog.h@8; GMPMessageUtils.h@9; GMPUtils.h@10; GMPVideoEncodedFrameImpl.h@11; GMPVideoi420FrameImpl.h@12; mozilla/gmp/GMPTypes.h@13; nsAutoRef.h@14; nsPrintfCString.h@15; nsThreadUtils.h@16

`dom/media/gmp/GMPVideoDecoderParent.h` | `02a4795d628fc4f65eefcc7c00bcdf0d4464c426` | 3915 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; GMPContentParent@21; GMPVideoDecoderParent@23
Dependencies: GMPCrashHelperHolder.h@8; GMPMessageUtils.h@9; GMPSharedMemManager.h@10; GMPUtils.h@11; GMPVideoDecoderProxy.h@12; GMPVideoHost.h@13; VideoUtils.h@14; gmp-video-decode.h@15; mozilla/RefPtr.h@16; mozilla/gmp/PGMPVideoDecoderParent.h@17

`dom/media/gmp/GMPVideoDecoderProxy.h` | `0fec3a1648bb651bc48028c61702f600ecdad390` | 2035 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoDecoderCallbackProxy@16; GMPVideoDecoderProxy@33
Dependencies: GMPCallbackBase.h@8; GMPNativeTypes.h@9; GMPUtils.h@10; gmp-video-decode.h@11; gmp-video-frame-encoded.h@12; gmp-video-frame-i420.h@13; nsTArray.h@14

`dom/media/gmp/GMPVideoEncodedFrameImpl.cpp` | `2ebe788b728fa9d498d7d32bde3c0d2d2a986d9f` | 9051 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; mBufferType@26; mBufferType@43; mBufferType@60; GMPVideoEncodedFrameImpl::~GMPVideoEncodedFrameImpl@64; GMPVideoEncodedFrameImpl::GetFrameFormat@76; GMPVideoEncodedFrameImpl::DestroyBuffer@137; GMPVideoEncodedFrameImpl::CreateEmptyFrame@145; GMPVideoEncodedFrameImpl::CopyFrame@161; GMPVideoEncodedFrameImpl::SetEncodedWidth@185; GMPVideoEncodedFrameImpl::EncodedWidth@189; GMPVideoEncodedFrameImpl::SetEncodedHeight@191; GMPVideoEncodedFrameImpl::EncodedHeight@195; GMPVideoEncodedFrameImpl::SetTimeStamp@197; GMPVideoEncodedFrameImpl::TimeStamp@201; GMPVideoEncodedFrameImpl::SetDuration@203; GMPVideoEncodedFrameImpl::Duration@207; GMPVideoEncodedFrameImpl::SetFrameType@209; GMPVideoEncodedFrameImpl::FrameType@213; GMPVideoEncodedFrameImpl::SetAllocatedSize@215; GMPVideoEncodedFrameImpl::AllocatedSize@241; GMPVideoEncodedFrameImpl::SetSize@248; GMPVideoEncodedFrameImpl::Size@250; GMPVideoEncodedFrameImpl::SetCompleteFrame@252; GMPVideoEncodedFrameImpl::CompleteFrame@256; GMPVideoEncodedFrameImpl::Buffer@268; GMPVideoEncodedFrameImpl::Destroy@278; GMPVideoEncodedFrameImpl::BufferType@280; GMPVideoEncodedFrameImpl::SetBufferType@284; GMPVideoEncodedFrameImpl::SetTemporalLayerId@288; GMPVideoEncodedFrameImpl::GetTemporalLayerId@292
Dependencies: GMPVideoEncodedFrameImpl.h@5; GMPSharedMemManager.h@7; GMPVideoHost.h@8; mozilla/gmp/GMPTypes.h@9; nsProxyRelease.h@10; nsThreadUtils.h@11; nsXULAppAPI.h@12

`dom/media/gmp/GMPVideoEncodedFrameImpl.h` | `c39f847c2fd8a56151271e2840a3ec7d38b62f86` | 4675 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@39; CryptoSample@40; gmp@42; GMPVideoHostImpl@44; GMPVideoEncodedFrameData@45; GMPVideoEncodedFrameImpl@47
Dependencies: gmp-errors.h@33; gmp-video-frame-encoded.h@34; gmp-video-frame.h@35; mozilla/ipc/Shmem.h@36; nsTArray.h@37

`dom/media/gmp/GMPVideoEncoderChild.cpp` | `5647b9bcf4291ef27f59fac465ad2090240debf2` | 6566 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; mPlugin@16; GMPVideoEncoderChild::~GMPVideoEncoderChild@20; GMPVideoEncoderChild::MgrIsOnOwningThread@31; GMPVideoEncoderChild::Init@35; GMPVideoEncoderChild::Error@93; GMPVideoEncoderChild::ActorDestroy@193
Dependencies: GMPVideoEncoderChild.h@5; GMPContentChild.h@7; GMPPlatform.h@8; GMPVideoEncodedFrameImpl.h@9; mozilla/StaticPrefs_media.h@10; runnable_utils.h@11

`dom/media/gmp/GMPVideoEncoderChild.h` | `222bb6c280ea57794a3de28b3ad6adb5c08ba3e4` | 2926 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; GMPContentChild@17; GMPVideoEncoderChild@19
Dependencies: GMPSharedMemManager.h@8; GMPVideoHost.h@9; GMPVideoi420FrameImpl.h@10; gmp-video-encode.h@11; mozilla/gmp/PGMPVideoEncoderChild.h@12; nsString.h@13

`dom/media/gmp/GMPVideoEncoderParent.cpp` | `d32029938f15b457e3a4739dbccfa0a38892654f` | 8318 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; mPluginId@42; GMPVideoEncoderParent::MgrIsOnOwningThread@46; GMPVideoEncoderParent::Close@51; GMPVideoEncoderParent::SetPeriodicKeyFrames@168; GMPVideoEncoderParent::Shutdown@185; GMPVideoEncoderParent::ActorDestroy@207; GMPVideoEncoderParent::RecvError@270; GMPVideoEncoderParent::RecvShutdown@278
Dependencies: GMPVideoEncoderParent.h@5; GMPContentParent.h@7; GMPCrashHelper.h@8; GMPLog.h@9; GMPMessageUtils.h@10; GMPVideoEncodedFrameImpl.h@11; GMPVideoi420FrameImpl.h@12; mozilla/gmp/GMPTypes.h@13; nsAutoRef.h@14; nsThread.h@15; nsThreadUtils.h@16; runnable_utils.h@17

`dom/media/gmp/GMPVideoEncoderParent.h` | `5376f6dd3f04a37f0743023309e1b00a98c6f3b6` | 3369 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; GMPVideoEncoderParent@21
Dependencies: GMPContentParent.h@8; GMPCrashHelperHolder.h@9; GMPMessageUtils.h@10; GMPSharedMemManager.h@11; GMPUtils.h@12; GMPVideoEncoderProxy.h@13; GMPVideoHost.h@14; gmp-video-encode.h@15; mozilla/RefPtr.h@16; mozilla/gmp/PGMPVideoEncoderParent.h@17

`dom/media/gmp/GMPVideoEncoderProxy.h` | `413cf0ae5eb5c9053b5c3b23600fb3589f8d0c6f` | 2309 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoEncoderCallbackProxy@15; GMPVideoEncoderProxy@35
Dependencies: GMPCallbackBase.h@8; GMPUtils.h@9; gmp-video-encode.h@10; gmp-video-frame-encoded.h@11; gmp-video-frame-i420.h@12; nsTArray.h@13

`dom/media/gmp/GMPVideoHost.cpp` | `ddb4464337440bf25b15cfb91e2f19c23eff55e4` | 1282 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; GMPVideoHostImpl::CreatePlane@40
Dependencies: GMPVideoHost.h@5; GMPSharedMemManager.h@7; GMPVideoEncodedFrameImpl.h@8; GMPVideoPlaneImpl.h@9; GMPVideoi420FrameImpl.h@10; mozilla/Assertions.h@11

`dom/media/gmp/GMPVideoHost.h` | `f803e6673a209dc8d6a5dd4257781b8411ebd531` | 912 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; GMPVideoEncodedFrameImpl@16; GMPVideoi420FrameImpl@17; GMPVideoHostImpl@19
Dependencies: GMPSharedMemManager.h@8; gmp-video-frame.h@9; gmp-video-host.h@10; gmp-video-plane.h@11; nsTArray.h@12

`dom/media/gmp/GMPVideoPlaneImpl.cpp` | `4681fa1663f1cbcae1b2279dedebed9ec784bd57` | 3050 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; mStride@19; GMPPlaneImpl::MaybeResize@32; GMPPlaneImpl::Copy@57; GMPPlaneImpl::Swap@92; GMPPlaneImpl::AllocatedSize@100; GMPPlaneImpl::ResetSize@104; GMPPlaneImpl::IsZeroSize@106; GMPPlaneImpl::Stride@108; GMPPlaneImpl::Buffer@116; GMPPlaneImpl::Destroy@123
Dependencies: GMPVideoPlaneImpl.h@5; algorithm@7; GMPSharedMemManager.h@9; GMPVideoHost.h@10; mozilla/gmp/GMPTypes.h@11

`dom/media/gmp/GMPVideoPlaneImpl.h` | `235dba43496167856883589e9a90f8a7dd435b71` | 1405 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; GMPPlaneData@13; GMPPlaneImpl@15
Dependencies: gmp-video-plane.h@8; nsTArray.h@9

`dom/media/gmp/GMPVideoi420FrameImpl.cpp` | `3dff703c85e6d661685907af82d5b1a5ba9244ed` | 17509 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@17; mStride@23; mDuration@53; mDuration@71; mDuration@89; GMPVideoi420FrameImpl::~GMPVideoi420FrameImpl@93; GMPVideoi420FrameImpl::InitFrameData@110; GMPVideoi420FrameImpl::GetFrameFormat@149; GMPVideoi420FrameImpl::Destroy@153; GMPVideoi420FrameImpl::MaybeResize@318; GMPVideoi420FrameImpl::CopyFrame@420; GMPVideoi420FrameImpl::SwapFrame@447; GMPVideoi420FrameImpl::Buffer@461; GMPVideoi420FrameImpl::Buffer@481; GMPVideoi420FrameImpl::AllocatedSize@499; GMPVideoi420FrameImpl::AllocatedSize@506; GMPVideoi420FrameImpl::Stride@513; GMPVideoi420FrameImpl::SetWidth@520; GMPVideoi420FrameImpl::SetHeight@529; GMPVideoi420FrameImpl::Width@538; GMPVideoi420FrameImpl::Height@540; GMPVideoi420FrameImpl::SetTimestamp@542; GMPVideoi420FrameImpl::Timestamp@546; GMPVideoi420FrameImpl::SetUpdatedTimestamp@548; GMPVideoi420FrameImpl::UpdatedTimestamp@552; GMPVideoi420FrameImpl::SetDuration@556; GMPVideoi420FrameImpl::Duration@560; GMPVideoi420FrameImpl::IsZeroSize@562; GMPVideoi420FrameImpl::ResetSize@566
Dependencies: GMPVideoi420FrameImpl.h@5; algorithm@7; GMPSharedMemManager.h@9; GMPVideoHost.h@10; mozilla/CheckedInt.h@11; mozilla/gmp/GMPTypes.h@12; nsProxyRelease.h@13; nsThreadUtils.h@14; nsXULAppAPI.h@15

`dom/media/gmp/GMPVideoi420FrameImpl.h` | `bfbf375d1f6ec715a3dfcf64214da6bc60222347` | 4401 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; GMPPlaneData@15; GMPVideoi420FrameData@16; GMPVideoHostImpl@17; class@19; GMPVideoi420FrameImpl@24; GMPFramePlane@84
Dependencies: gmp-video-frame-i420.h@8; mozilla/Maybe.h@9; mozilla/ipc/Shmem.h@10; nsTArray.h@11

`dom/media/gmp/PChromiumCDM.ipdl` | `c6db95a88fbb5e70bd55d8ad8af1222614278103` | 4230 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@19; gmp@20

`dom/media/gmp/PGMP.ipdl` | `f7814b31b7319072b2a0cb3999288e0ce507280f` | 3094 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@23; gmp@24

`dom/media/gmp/PGMPContent.ipdl` | `d1f631a30fcf3baeed7cb9b4b2c5003fd40b9ab8` | 1019 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; gmp@16

`dom/media/gmp/PGMPService.ipdl` | `d19313e97ce19cefa21c5a9baad3de352844c92d` | 1166 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; gmp@13; GMPLaunchResult@15

`dom/media/gmp/PGMPStorage.ipdl` | `d5a4c98980bb3ded8a93c9fa851c83cc53bd5bb2` | 935 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; gmp@13

`dom/media/gmp/PGMPTimer.ipdl` | `c1d683c0e9efbdd732b9d66050a86422b50ef3b1` | 633 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@10; gmp@11

`dom/media/gmp/PGMPVideoDecoder.ipdl` | `0b959e056e0bec45e4a8380cb6d37ec947cf6487` | 1502 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; gmp@15

`dom/media/gmp/PGMPVideoEncoder.ipdl` | `a89b8f3871c6feea70b8d7cbc09d14065f5b1a5b` | 1700 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; gmp@16

`dom/media/gmp/README.txt` | `189cf3b302db45e2442aa22dea1129afce7d8800` | 135 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp/gmp-api/gmp-entrypoints.h` | `62511a55c1d5e58ca977eba4638e6b85e9a7f697` | 3207 bytes | source | UTF-8 | mode 100644
Declarations: GMPErr@48; GMPErr@64; void@70
Dependencies: gmp-errors.h@36; gmp-platform.h@37

`dom/media/gmp/gmp-api/gmp-errors.h` | `a0cf09fd45e5b0c7121b1208ee6c29e71d4f2b3d` | 2150 bytes | source | UTF-8 | mode 100644
Declarations: enum@35

`dom/media/gmp/gmp-api/gmp-platform.h` | `dc0162717b3eff665d42ca21b79d8eb930f66dd3` | 3773 bytes | source | UTF-8 | mode 100644
Declarations: GMPTask@42; GMPThread@49; GMPMutex@58; int64_t@68; GMPErr@70; GMPErr@71; GMPErr@72; GMPErr@73; GMPErr@76; GMPErr@82; GMPErr@84; GMPPlatformAPI@86
Dependencies: stdint.h@35; gmp-errors.h@37; gmp-storage.h@38

`dom/media/gmp/gmp-api/gmp-storage.h` | `2a0bd149759377bbeca9d1fb7ddbe9ee62ad28e6` | 4701 bytes | source | UTF-8 | mode 100644
Declarations: GMPRecord@43; GMPRecordClient@73
Dependencies: stdint.h@20; gmp-errors.h@22

`dom/media/gmp/gmp-api/gmp-video-codec.h` | `d8befaa8f9751c0fcd43ca736979fb2593b12040` | 9044 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoCodecComplexity@42; GMPVP8ResilienceMode@50; GMPVideoCodecVP8@63; GMPVideoCodecH264AVCC@78; GMPVideoCodecH264@100; GMPVideoCodecH264AVCC@102; GMPVideoCodecType@106; GMPSimulcastStream@119; GMPVideoCodecMode@129; GMPLogLevel@137; GMPProfile@148; GMPLevel@162; GMPRateControlMode@183; GMPSliceMode@193; GMPApiVersion@201; GMPVideoCodec@216; GMPBufferType@259; GMPCodecSpecificInfoGeneric@268; GMPCodecSpecificInfoH264@272; GMPCodecSpecificInfoVP8@278; GMPCodecSpecificInfo@301
Dependencies: stddef.h@36; stdint.h@37

`dom/media/gmp/gmp-api/gmp-video-decode.h` | `c214f1a350875759f4486a759bb3c52d48160e39` | 5197 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoDecoderCallback@44; GMPVideoDecoder@74
Dependencies: stdint.h@36; gmp-errors.h@38; gmp-video-codec.h@39; gmp-video-frame-encoded.h@40; gmp-video-frame-i420.h@41

`dom/media/gmp/gmp-api/gmp-video-encode.h` | `c4288618408344b800415787a936341754f373f2` | 5485 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoEncoderCallback@44; GMPVideoEncoder@66
Dependencies: stdint.h@36; gmp-errors.h@38; gmp-video-codec.h@39; gmp-video-frame-encoded.h@40; gmp-video-frame-i420.h@41

`dom/media/gmp/gmp-api/gmp-video-frame-encoded.h` | `fcea5bd63a767797c7b6781b74436641bac2d2bd` | 4045 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoFrameType@41; GMPVideoEncodedFrame@59
Dependencies: stdint.h@36; gmp-video-codec.h@38; gmp-video-frame.h@39

`dom/media/gmp/gmp-api/gmp-video-frame-i420.h` | `1340efe78583eb4e96829392343c77152c6f12d8` | 5511 bytes | source | UTF-8 | mode 100644
Declarations: GMPPlaneType@42; GMPVideoi420Frame@58
Dependencies: stdint.h@36; gmp-errors.h@38; gmp-video-frame.h@39; gmp-video-plane.h@40

`dom/media/gmp/gmp-api/gmp-video-frame.h` | `adf01a8b778a3ec6fa18aa5f8eaa60411b55ba74` | 1955 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoFrameFormat@38; GMPVideoFrame@40
Dependencies: gmp-video-plane.h@36

`dom/media/gmp/gmp-api/gmp-video-host.h` | `91ebae504396a7e29f7629953a9fc01740c52a52` | 2217 bytes | source | UTF-8 | mode 100644
Declarations: GMPVideoHost@42
Dependencies: gmp-errors.h@36; gmp-video-codec.h@37; gmp-video-frame-encoded.h@38; gmp-video-frame-i420.h@39

`dom/media/gmp/gmp-api/gmp-video-plane.h` | `fb129d2941a8b5bae3180c13b3cf0718bf232825` | 3593 bytes | source | UTF-8 | mode 100644
Declarations: GMPPlane@49
Dependencies: stdint.h@36; gmp-errors.h@38

`dom/media/gmp/moz.build` | `8b8f052454c604d9068c5e9afd1b32fa0592bd77` | 3834 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@128

`dom/media/gmp/mozIGeckoMediaPluginChromeService.idl` | `16d36c27e3cacd719f378c06b69346bf5f19c717` | 1781 bytes | source | UTF-8 | mode 100644
Declarations: mozIGeckoMediaPluginChromeService@9
Dependencies: nsISupports.idl@5; nsIFile.idl@6

`dom/media/gmp/mozIGeckoMediaPluginService.idl` | `d9b99e0b4291b52de90e4c00d32c815d8c19ce1e` | 4575 bytes | source | UTF-8 | mode 100644
Declarations: nsIFile@8; GMPDecryptorProxy@14; GMPVideoDecoderProxy@15; GMPVideoEncoderProxy@16; GMPVideoHost@17; mozilla@19; GMPCrashHelper@20; GMPGetterCallback@24; GMPGetterCallback@27; GMPVideoGetterCallback@32; GMPVideoGetterCallback@35; GMPGetterCallback@39; GMPVideoGetterCallback@40; GMPVideoGetterCallback@41; GetNodeIdCallback@42; mozIGeckoMediaPluginService@60
Dependencies: nsISupports.idl@5; nsIThread.idl@6; mozilla/UniquePtr.h@11; nsTArray.h@12; nsString.h@13

`dom/media/gmp/rlz/OWNERS` | `66f24ebb372977e698dacef4b52dd9bc77e575e0` | 70 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp/rlz/README.mozilla` | `4408737a5e7a5fbe020492ede1fa43b3ae950d73` | 261 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp/rlz/lib/assert.h` | `767c2163b30df075f57018100a644ff5bc6a81b4` | 360 bytes | source | UTF-8 | mode 100644
Dependencies: assert.h@8

`dom/media/gmp/rlz/lib/crc8.cc` | `fe02eabf1b897535ff2c416f332080d78653687e` | 2905 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@49
Dependencies: rlz/lib/crc8.h@5

`dom/media/gmp/rlz/lib/crc8.h` | `6c3c84859bfc589aac679d7cf67579822a506cc4` | 664 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@10; Crc8@12

`dom/media/gmp/rlz/lib/machine_id.cc` | `dd41e52001124725c67b3697d7807fdce7d13125` | 3015 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@18; GetMachineId@20; testing@44
Dependencies: rlz/lib/machine_id.h@5; stddef.h@7; rlz/lib/assert.h@9; rlz/lib/crc8.h@10; rlz/lib/string_utils.h@11; mozilla/SHA1.h@16

`dom/media/gmp/rlz/lib/machine_id.h` | `5fa343efa3554845fc6f286bd43ab5442997e9d0` | 1194 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@11; testing@25
Dependencies: string@8; vector@9

`dom/media/gmp/rlz/lib/string_utils.cc` | `6da732382368e7c8e6a15ce6a13c87d67b361299` | 893 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@9
Dependencies: rlz/lib/string_utils.h@7

`dom/media/gmp/rlz/lib/string_utils.h` | `500133ade1f4821d30fff4b05247a91bd369cbf1` | 510 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@12
Dependencies: string@10

`dom/media/gmp/rlz/mac/lib/machine_id_mac.cc` | `8c0bae22e8f7109c32967e874493269dc7e67308` | 9961 bytes | source | UTF-8 | mode 100644
Declarations: base@24; ScopedCFTypeRef@28; T@30; object_@33; T@47; release@53; mac@63; ScopedIOObject@68; IOT@70; object_@73; reset@84; IOT@90; SysCFStringRefToUTF8@175; rlz_lib@183; FindEthernetInterfaces@190; GetMacAddress@252; CopySerialNumber@262; GetRawMachineId@284
Dependencies: CoreFoundation/CoreFoundation.h@5; IOKit/IOKitLib.h@6; IOKit/network/IOEthernetController.h@7; IOKit/network/IOEthernetInterface.h@8; IOKit/network/IONetworkInterface.h@9; stddef.h@10; stdint.h@11; vector@13; string@14

`dom/media/gmp/rlz/moz.build` | `235b7e6346e266db0efd6301d9674e6ebab138ab` | 807 bytes | build-registration | UTF-8 | mode 100644

`dom/media/gmp/rlz/win/lib/machine_id_win.cc` | `5f4b3557310aa22f052f445dcfceb64f3329cf14` | 4095 bytes | source | UTF-8 | mode 100644
Declarations: rlz_lib@16; GetSystemVolumeSerialNumber@20; GetComputerSid@44; ConvertSidToBytes@73; GetRawMachineId@112
Dependencies: windows.h@5; sddl.h@6; memory@8; string@9; vector@10; mozilla/ArrayUtils.h@12; rlz/lib/assert.h@14

`dom/media/gmp/widevine-adapter/OWNERS` | `f09af4551058344f999ad1f9b65ae066c77ad21e` | 42 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp/widevine-adapter/README.md` | `18dc49f8e6cb8eda0d0e6c345362db5208d4a4c3` | 1689 bytes | documentation | UTF-8 | mode 100644

`dom/media/gmp/widevine-adapter/WidevineFileIO.cpp` | `41237a2bc2a948d32fe6cf6bace86f0bbd27bc62` | 3301 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; WidevineFileIO::Open@16; WidevineFileIO::Read@40; WidevineFileIO::Write@51; WidevineFileIO::DestroyRecord@61; WidevineFileIO::Close@68; GMPToWidevineFileStatus@74; WidevineFileIO::OpenComplete@85; WidevineFileIO::WriteComplete@98
Dependencies: WidevineFileIO.h@5; GMPLog.h@7; WidevineUtils.h@8; gmp-api/gmp-platform.h@9

`dom/media/gmp/widevine-adapter/WidevineFileIO.h` | `356897d7f7cd6c1c5a21b9d1ae2ad7dcd6ce8de8` | 1134 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@13; WidevineFileIO@15; WidevineFileIO@17
Dependencies: string@8; content_decryption_module.h@10; gmp-api/gmp-storage.h@11

`dom/media/gmp/widevine-adapter/WidevineUtils.cpp` | `0b02decd8d1b588fb307a4add099bea2a7490c07` | 1589 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; WidevineBuffer::WidevineBuffer@14; WidevineBuffer::~WidevineBuffer@19; WidevineBuffer::Destroy@23; WidevineBuffer::Capacity@25; WidevineBuffer::Data@27; WidevineBuffer::SetSize@29; WidevineBuffer::Size@31; WidevineBuffer::ExtractBuffer@33; mBuffer@39; WidevineDecryptedBlock::~WidevineDecryptedBlock@41; WidevineDecryptedBlock::SetDecryptedBuffer@48; WidevineDecryptedBlock::DecryptedBuffer@52; WidevineDecryptedBlock::SetTimestamp@54; WidevineDecryptedBlock::Timestamp@58
Dependencies: WidevineUtils.h@5; stdint.h@7; GMPLog.h@9; gmp-api/gmp-errors.h@10

`dom/media/gmp/widevine-adapter/WidevineUtils.h` | `53784d5ac1f8e7b6f84d184090987bf81f3f69b0` | 2756 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; gmp@32; CDMShmemBuffer@33; WidevineBuffer@35; CDMBuffer@39; AsArrayBuffer@41; AsShmemBuffer@42; WidevineBuffer@45; WidevineDecryptedBlock@69
Dependencies: content_decryption_module.h@8; mozilla/Logging.h@9; nsISupportsImpl.h@10; nsTArray.h@11; stddef.h@12

`dom/media/gmp/widevine-adapter/WidevineVideoFrame.cpp` | `a6e49610a6f284ba1de7b149ec2d9e451b8272ff` | 4775 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; mTimestamp@18; mTimestamp@30; WidevineVideoFrame::~WidevineVideoFrame@40; WidevineVideoFrame::SetFormat@47; WidevineVideoFrame::Format@53; WidevineVideoFrame::SetSize@55; WidevineVideoFrame::Size@62; WidevineVideoFrame::SetFrameBuffer@64; WidevineVideoFrame::FrameBuffer@71; WidevineVideoFrame::PlaneOffset@80; WidevineVideoFrame::SetStride@84; WidevineVideoFrame::Stride@90; WidevineVideoFrame::SetTimestamp@94; WidevineVideoFrame::Timestamp@100
Dependencies: WidevineVideoFrame.h@5; GMPLog.h@7; WidevineUtils.h@8; mozilla/CheckedInt.h@9; mozilla/IntegerPrintfMacros.h@10

`dom/media/gmp/widevine-adapter/WidevineVideoFrame.h` | `b5f444542f05445fe20e8ee612ea7ecd01535dd4` | 1475 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; WidevineVideoFrame@13
Dependencies: content_decryption_module.h@8; stddef.h@9

`dom/media/gmp/widevine-adapter/content_decryption_module.h` | `4fa6f8fc707f28119a7cbb7d710e8350a91a5736` | 82905 bytes | source | UTF-8 | mode 100644
Declarations: void@51; cdm@70; Exception@85; class@94; Pattern@103; class@109; ColorSpace@121; double@134; SubsampleEntry@157; InputBuffer_2@169; AudioCodec@194; AudioDecoderConfig_2@197; AudioFormat@214; VideoFormat@227; Size@248; VideoCodec@254; VideoCodecProfile@263; VideoDecoderConfig_2@287; VideoDecoderConfig_3@307; StreamType@326; PlatformChallengeResponse@332; KeyStatus@350; class@366; KeyInformation@381; KeyInformation_2@392; OutputProtectionMethods@402; OutputLinkTypes@409; QueryResult@422; InitDataType@427; SessionType@432; MessageType@440; HdcpVersion@448; Policy@462; CDM_CLASS_API@468; Buffer@479; CDM_CLASS_API@488; DecryptedBlock@499; CDM_CLASS_API@512; VideoFrame@534; CDM_CLASS_API@540; VideoFrame_2@552; CDM_CLASS_API@567; AudioFrames@579; CDM_CLASS_API@592; FileIO@625; CDM_CLASS_API@633; class@635; FileIOClient@661; MetricName@673; CDM_CLASS_API@688; CDM_CLASS_API@689; CDM_CLASS_API@690; CDM_CLASS_API@698; Host_10@702; ContentDecryptionModule_10@908; CDM_CLASS_API@918; Host_11@922; ContentDecryptionModule_11@1132; CDM_CLASS_API@1144; Host_12@1148; ContentDecryptionModule_12@1358; CDM_CLASS_API@1362; Host_10@1494; CDM_CLASS_API@1498; Host_11@1635; CDM_CLASS_API@1639; Host_12@1776
Dependencies: cstdint@8; type_traits@9; content_decryption_module_export.h@11; mozilla/DefineEnum.h@13

`dom/media/gmp/widevine-adapter/content_decryption_module_export.h` | `932708deba3149ea6160849d113a06e4201c8114` | 1364 bytes | source | UTF-8 | mode 100644

`dom/media/gmp/widevine-adapter/content_decryption_module_ext.h` | `53b16238febde4b3a7c04f7cf09eabeacda4b769` | 1779 bytes | source | UTF-8 | mode 100644
Declarations: cdm@16; wchar_t@19; HANDLE@20; char@23; int@24; HostFile@28; file_path@32
Dependencies: cstdint@8; windows.h@11; content_decryption_module_export.h@14

`dom/media/gmp/widevine-adapter/enum.patch` | `c4cd12661027a764e1162830f2f5405cea269b95` | 1114 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gmp/widevine-adapter/moz.build` | `0fc3fa560b586de1c2dcc1763bc59bff11e87cf6` | 622 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@26

`dom/media/gmp/widevine-adapter/moz.yaml` | `0f11763d7a5d3ba7758183179a6d7495399f6bf7` | 1068 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/gtest/Cargo.toml` | `f0b20dc2dd56bf602b0b0bd7bec847a93a2437e2` | 159 bytes | test-path,build-registration | UTF-8 | mode 100644

`dom/media/gtest/GMPTestMonitor.h` | `5c4a321e835e44806375598bd6fcb8e671e01cd6` | 1018 bytes | test-path,source | UTF-8 | mode 100644
Declarations: GMPTestMonitor@11; GMPTestMonitor@13; AwaitFinished@15; MarkFinished@23; SetFinished@29
Dependencies: mozilla/SchedulerGroup.h@7; mozilla/SpinEventLoopUntil.h@8; nsThreadUtils.h@9

`dom/media/gtest/MediaSinkTestUtils.h` | `9ef332d044f00683b7d8b66f0876a5fcd3eabcb4` | 3741 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@40
Dependencies: utility@8; AudioSink.h@10; AudioSinkWrapper.h@11; ImageContainer.h@12; MediaData.h@13; MediaInfo.h@14; MediaQueue.h@15; VideoFrameContainer.h@16; gtest/gtest.h@17; nsThreadUtils.h@18

`dom/media/gtest/MockDecoderModule.h` | `c1190a7895e35cf539cf49290076ad85e4dbde90` | 3053 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@13; class@15; MockVideoDataDecoder@17; ON_CALL@27; SetLatencyFrameCount@36; HardwareCapableMockDecoder@44; mHardwareAcceleration@50; MockDecoderModule@61; MockDecoderModule@63
Dependencies: BlankDecoderModule.h@8; DummyMediaDataDecoder.h@9; PlatformDecoderModule.h@10; gmock/gmock.h@11

`dom/media/gtest/MockGraphInterface.h` | `1a1d20be0eb40c505190c2c7c1a14e5ddab06619` | 3814 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@13; MockGraphInterface@15; mSampleRate@18; SetEnsureNextIteration@61; IterationCount@63; StateComputedTime@65; SetCurrentDriver@66; StopIterating@68; FramesIteratedEvent@80
Dependencies: tuple@8; GraphDriver.h@10; gmock/gmock.h@11

`dom/media/gtest/MockMediaDataDemuxer.h` | `57a255c27f151a783ea15a4781476709071142f1` | 2666 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@14; MockMediaDataDemuxer@16; MockMediaDataDemuxer@18; ON_CALL@19; MockMediaTrackDemuxer@35; MockMediaTrackDemuxer@39; ON_CALL@40
Dependencies: MediaContainerType.h@8; MediaDecoderOwner.h@9; MediaMIMETypes.h@10; VideoUtils.h@11; gmock/gmock.h@12

`dom/media/gtest/MockMediaDecoderOwner.h` | `f885328ae1edbb9c18704bdf29defba493885e92` | 2507 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@11; MockMediaDecoderOwner@13
Dependencies: MediaDecoderOwner.h@8; gmock/gmock.h@9

`dom/media/gtest/MockMediaResource.cpp` | `9a391e32b409f37a796f117d80fa0115aca8c43b` | 2252 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@10; mFileHandle@13; MockMediaResource::Open@15; MockMediaResource::~MockMediaResource@24; MockMediaResource::GetLength@50; MockMediaResource::MockClearBufferedRanges@58; MockMediaResource::MockAddBufferedRange@60; MockMediaResource::GetNextCachedData@64; MockMediaResource::GetCachedDataEnd@77; MockMediaResource::GetCachedRanges@86
Dependencies: MockMediaResource.h@5; sys/stat.h@7; sys/types.h@8

`dom/media/gtest/MockMediaResource.h` | `f69cd115884f20cb41c31fc4c297434f9158273a` | 1769 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@12; MockMediaResource@16
Dependencies: MediaResource.h@8; mozilla/Atomics.h@9; nsTArray.h@10

`dom/media/gtest/TestADTSDemuxer.cpp` | `2eee29833802dd31dedffe3669e4d70b6e48689b` | 1459 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockADTSMediaResource@12; mozilla@13; MockADTSMediaResource@20; MockMediaResource@25; TEST@33
Dependencies: gtest/gtest.h@5; climits@7; ADTSDemuxer.h@9; MockMediaResource.h@10

`dom/media/gtest/TestAOMDecoder.cpp` | `6512e1dc51ed3183c0c656d3f261670b380baaa7` | 7602 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AppendU16BE@19; AppendU32BE@24; BuildMDCVPayload@56; BuildCLLPayload@77; TEST@85; TEST@110; TEST@125; TEST@144; TEST@155; TEST@168; TEST@180
Dependencies: AOMDecoder.h@5; gtest/gtest.h@6; mozilla/gfx/Types.h@7; nsTArray.h@8

`dom/media/gtest/TestAV1FmtpParser.cpp` | `0209617b38b484eee4593e4e27d6c07a226f60a8` | 7072 bytes | test-path,source | UTF-8 | mode 100644
Declarations: Parse@11; TEST@20; TEST@31; TEST@38; TEST@45; TEST@52; TEST@59; TEST@66; TEST@74; TEST@82; TEST@90; TEST@97; TEST@104; TEST@111; TEST@125; TEST@132; TEST@139; TEST@146; TEST@153; TEST@160; TEST@171; TEST@182; TEST@188; TEST@194; TEST@200; TEST@208; TEST@214; TEST@220; TEST@225; TEST@230; TEST@240; TEST@245; TEST@250
Dependencies: MediaMIMETypes.h@5; gtest/gtest.h@6; mozilla/media/webrtc/AV1FmtpParser.h@7

`dom/media/gtest/TestAVSync.cpp` | `17ff81bb8df518d8bcdbbc4da5b48b0bd30f04ef` | 31863 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AVSyncTest@62; ScopedCubebContext@99; ScopedCubebContext@101; ProcessPending@140; class@143; SeekStop@162; PushAudio@191; PushVideoFrame@212; VideoFrameDuration@234; PushSteadyContent@240; DriveCallback@247; AdvanceClock@278; WaitForRenderedSchedule@287; ExpectScheduleMatchesClock@353; ExpectCadenceMatchesRate@397; ExpectCorrectClockAndCadence@425; TEST_F@457; TEST_F@467; TEST_F@488; TEST_F@517; TEST_F@532; TEST_F@554; TEST_F@572; TEST_F@591; TEST_F@609; AVSyncRateTest@624; TEST_P@627; AVSyncFrameRateTest@647; TEST_P@650; AVSyncCallbackSizeTest@670; TEST_P@673; AVSyncSeekTest@692; RunSeekResume@694; RenderedAudio@719; RunClockFollowsRenderedAudio@737; TEST_F@768; TEST_F@774; TEST_F@780; TEST_F@786
Dependencies: algorithm@5; cmath@6; tuple@7; AudioGenerator.h@9; AudioSampleFormat.h@10; CubebUtils.h@11; FrameStatistics.h@12; MediaData.h@13; MediaSinkTestUtils.h@14; MockCubeb.h@15; MockMediaDecoderOwner.h@16; TimeUnits.h@17; VideoSink.h@18; gtest/gtest.h@19; mozilla/Maybe.h@20; mozilla/SpinEventLoopUntil.h@21; mozilla/gtest/ScopedPrefSetter.h@22; nsThreadUtils.h@23; prthread.h@24

`dom/media/gtest/TestAppleVTColorSpace.cpp` | `2143b5a6a2a93eff04451c152f0abee14878c776` | 10463 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@123; TEST@134; TEST@177; TEST@185; TEST@197; TEST@238; TEST@249
Dependencies: CoreGraphics/CGColorSpace.h@5; CoreVideo/CVPixelBuffer.h@6; AppleVTColorSpace.h@8; MP4Demuxer.h@9; MacIOSurfaceImage.h@10; MockMediaResource.h@11; PDMFactory.h@12; VideoUtils.h@13; gfxPlatform.h@14; gtest/gtest.h@15; mozilla/ScopeExit.h@16; mozilla/SharedThreadPool.h@17; mozilla/UniquePtr.h@18; mozilla/gfx/MacIOSurface.h@19; mozilla/gtest/ScopedPrefSetter.h@20; mozilla/gtest/WaitFor.h@21

`dom/media/gtest/TestAsyncLogger.cpp` | `8998dec56b1191c4828cc16c30cb734f0ced3be9` | 2256 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@11; TEST@13; TEST@33; TEST@55
Dependencies: gtest/gtest.h@5; string@7; AsyncLogger.h@9

`dom/media/gtest/TestAudioBuffer.cpp` | `af7e9c527d27288a862007fab2c72cc5ef1e8d01` | 1515 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FillSine@13; TEST@27
Dependencies: MediaData.h@5; gtest/gtest.h@6

`dom/media/gtest/TestAudioBufferAddWithScale.cpp` | `037461898d9b22c3688100823c980282b1763b0a` | 7100 bytes | test-path,source | UTF-8 | mode 100644
Declarations: FillSignal@72; TEST@83; TEST@109; TEST@136; TEST@164
Dependencies: cstring@5; AudioNodeEngine.h@7; gtest/gtest.h@8

`dom/media/gtest/TestAudioBuffers.cpp` | `a72b23435b8742ecfee7bd98966abbc3c1b28560` | 2016 bytes | test-path,source | UTF-8 | mode 100644
Declarations: test_for_number_of_channels@14; TEST@64
Dependencies: stdint.h@5; vector@7; AudioBufferUtils.h@9; gtest/gtest.h@10

`dom/media/gtest/TestAudioCallbackDriver.cpp` | `08ca0865f7a46df6231102a30ab8209419b54c29` | 29623 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@15; WaitUntil@123; TEST@170; MOZ_STACK_CLASS@179; mVal@186; TEST@568
Dependencies: CubebUtils.h@5; MediaTrackGraphImpl.h@6; MockCubeb.h@7; MockGraphInterface.h@8; gtest/gtest.h@9; mozilla/Attributes.h@10; mozilla/SyncRunnable.h@11; mozilla/gtest/WaitFor.h@12; nsTArray.h@13

`dom/media/gtest/TestAudioClock.cpp` | `9598b2c4829b54f5a9fff35658bbf2e9cb6795e9` | 12326 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@23; TEST@48; TEST@78; TEST@136; TEST@166; TEST@194; TEST@229; TEST@266
Dependencies: AudioStream.h@5; gtest/gtest.h@6

`dom/media/gtest/TestAudioCompactor.cpp` | `64279d8812815c0ad02d3f90426d24e942822ce1` | 3694 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MemoryFunctor@14; MemoryFunctor@16; TestCopy@26; mFrameCount@33; operator@35; TestAudioCompactor@49; TEST@76; TEST@81; TEST@86; TEST@91; TEST@96
Dependencies: AudioCompactor.h@4; gtest/gtest.h@5; nsDeque.h@6; nsIMemoryReporter.h@7

`dom/media/gtest/TestAudioConfig.cpp` | `78914cc0c68fc5ea911334f6a77a932862395b90` | 748 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@12
Dependencies: AudioConfig.h@5; gtest/gtest.h@6

`dom/media/gtest/TestAudioConverter.cpp` | `377c2b653a2abd0b57fe395a9882bf064a959bc6` | 890 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@13
Dependencies: gtest/gtest.h@5; limits@7; AudioConverter.h@9

`dom/media/gtest/TestAudioData.cpp` | `5c46b66366e853f15a2bc49cb75b20e1caf5fa44` | 2320 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@20; TEST@42
Dependencies: gtest/gtest.h@5; MediaData.h@7; TimeUnits.h@8

`dom/media/gtest/TestAudioDecoderInputTrack.cpp` | `09b9efd1ce55b4c29c4d7180d535a5c1bf330782` | 17609 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockTestGraph@29; MediaTrackGraphImpl@32; Init@36; MockDriver@51; MockDriver@54; CreateAudioDataFromInfo@71; TestAudioDecoderInputTrack@86; CreateAudioData@107; GetTrackSegment@111; TEST_F@142; TEST_F@187; TEST_F@248; TEST_F@266; TEST_F@306; TEST_F@335; TEST_F@372; TEST_F@393; TEST@432
Dependencies: utility@5; AudioDecoderInputTrack.h@7; GraphDriver.h@8; MediaInfo.h@9; MediaTrackGraphImpl.h@10; VideoUtils.h@11; gmock/gmock.h@12; gtest/gtest.h@13; mozilla/ScopeExit.h@14; mozilla/gtest/WaitFor.h@15; nsThreadUtils.h@16

`dom/media/gtest/TestAudioDeviceEnumerator.cpp` | `67f7591db9d66edeec8a2892bc909207e95eea8b` | 16702 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MATCHER@21; MATCHER@27; DeviceOperation@36; TEST@93; TEST@130; TEST@194; TEST@224; TEST@242; TEST@287; TEST@328; TEST@387
Dependencies: AudioDeviceInfo.h@5; CubebDeviceEnumerator.h@6; MockCubeb.h@7; gmock/gmock.h@8; gtest/gtest-printers.h@9; gtest/gtest.h@10; mozilla/media/MediaUtils.h@11; nsTArray.h@12

`dom/media/gtest/TestAudioInputProcessing.cpp` | `d57d873bd7eca8333fcc9823b9c74065b2236355` | 31462 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockGraph@25; MediaTrackGraphImpl@28; Init@32; ForceOutputDeviceForAEC@51; ForceDefaultOutputDevice@55; TEST@71; TEST@242; TEST@359; TEST@453; TEST@475; webrtc@497; TEST@531; TEST@734
Dependencies: AudioGenerator.h@5; MediaEngineWebRTCAudio.h@6; MediaTrackGraphImpl.h@7; PrincipalHandle.h@8; gmock/gmock.h@9; gtest/gtest.h@10; libwebrtcglue/SystemTime.h@11; libwebrtcglue/WebrtcEnvironmentWrapper.h@12; mozilla/NullPrincipal.h@13; nsContentUtils.h@14; nsTArray.h@15

`dom/media/gtest/TestAudioInputSource.cpp` | `e0d477b9615400d380436595a3eeaca9f3063339` | 12876 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockAudioEventListener@26; TEST@38; TEST@107; TEST@190; TEST@240; TEST@288
Dependencies: AudioInputSource.h@5; MockCubeb.h@6; gmock/gmock.h@7; gtest/gtest.h@8; mozilla/Result.h@9; mozilla/gtest/WaitFor.h@10; nsContentUtils.h@11

`dom/media/gtest/TestAudioMixer.cpp` | `c98086061a31def8599cd781ab516372c206af07` | 5963 bytes | test-path,source | UTF-8 | mode 100644
Declarations: audio_mixer@11; MixerConsumer@13; MixerCallback@16; TEST@69
Dependencies: AudioMixer.h@5; gtest/gtest.h@6

`dom/media/gtest/TestAudioPacketizer.cpp` | `e9ae8db4ebb05ab3b2f678a5f7b5fc6b6aaf55b3` | 6998 bytes | test-path,source | UTF-8 | mode 100644
Declarations: AutoBuffer@17; AutoBuffer@19; Get@21; Sequence@27; IsSequence@35; Zero@43; sine@50; TEST@52; TEST@166
Dependencies: math.h@5; stdint.h@6; memory@8; ../AudioPacketizer.h@10; ../TimedPacketizer.h@11; gtest/gtest.h@12

`dom/media/gtest/TestAudioRingBuffer.cpp` | `497f9f02213cb86f18bf3402757b1410487776e0` | 40103 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@13; TEST@91; TEST@169; TEST@273; TEST@377; TEST@427; TEST@477; TEST@614; TEST@751; TEST@793; TEST@835; TEST@859; TEST@885; TEST@913; TEST@954; TEST@995; TEST@1020; TEST@1045; TEST@1070; TEST@1095; TEST@1117; TEST@1139; TEST@1176; TEST@1213; TEST@1250; TEST@1287
Dependencies: AudioRingBuffer.h@5; gmock/gmock.h@6; gtest/gtest.h@7; mozilla/PodOperations.h@8

`dom/media/gtest/TestAudioSampleFormat.cpp` | `eccade374a6c947e9f2bb09c577eb29ce9ecc52c` | 4118 bytes | test-path,source | UTF-8 | mode 100644
Declarations: constexpr@15; constexpr@26; constexpr@50; TestSampleTypePair@58; TestSampleType24bits@69; constexpr@78; TEST@92
Dependencies: type_traits@6; AudioSampleFormat.h@8; gtest/gtest.h@9

`dom/media/gtest/TestAudioSegment.cpp` | `953463b9c79864c356b75a1d454bfbdff070d29a` | 12430 bytes | test-path,source | UTF-8 | mode 100644
Declarations: audio_segment@11; GetSilentValue@45; GetSilentValue@50; DeletePlanarChannelsArray@69; GetPlanarArray@77; DeletePlanarArray@89; DeleteInterleavedChannelArray@110; FuzzyEqual@114; TestInterleaveAndConvert@117; TestDeinterleaveAndConvert@141; SilentChannel@166; TestUpmixStereo@171; TestDownmixStereo@197; TEST@228; fillChunk@245; TEST@266; TEST@277; TEST@303; TEST@339; TEST@355; TEST@363; TEST@376; TEST@445
Dependencies: AudioGenerator.h@5; AudioSegment.h@6; gtest/gtest.h@7

`dom/media/gtest/TestAudioSinkWrapper.cpp` | `c0fd5a47de2188ede0eb3019d192bef8b6ebd34b` | 50708 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@29; TEST@95; TEST@146; class@214; AudioSinkWrapperReuseTest@221; ProcessPending@257; SeekStop@268; OutputLatencyFrames@285; DriveCallback@322; TakeRecorded@337; DrainRecordedOutput@346; AudibleSamplesNum@408; PlayFromZeroToSteadyState@441; SeekAndResumeAt@462; ExpectClockFollowsAudioOncePlaying@507; StartMutedSeekResume@558; ExpectUnmuteDoesNotRegressClock@579; TEST_F@602; TEST_F@610; TEST_F@627; TEST_F@641; AudioSinkWrapperReuseTest::RunReuseAcrossSeek@658; TEST_F@685; TEST_F@689; TEST_F@695; TEST_F@716; TEST_F@746; TEST_F@804; TEST_F@892; TEST_F@914; TEST_F@939; TEST_F@982; TEST_F@1002; TEST_F@1026; TEST_F@1070; TEST_F@1075; TEST_F@1083; AudioSinkWrapperReuseTest::RunMutedSeekResumeThenUnmuteDoesNotRegress@1122; TEST_F@1130; TEST_F@1135
Dependencies: algorithm@5; AudioSampleFormat.h@7; AudioSink.h@8; AudioSinkWrapper.h@9; CubebUtils.h@10; MediaData.h@11; MediaSinkTestUtils.h@12; MockCubeb.h@13; TimeUnits.h@14; gmock/gmock.h@15; gtest/gtest-printers.h@16; gtest/gtest.h@17; mozilla/Preferences.h@18; mozilla/SpinEventLoopUntil.h@19; mozilla/SyncRunnable.h@20; mozilla/gtest/WaitFor.h@21; nsThreadManager.h@22; nsThreadUtils.h@23

`dom/media/gtest/TestAudioStream.cpp` | `45731500f0a10a812a23f9bea209cec9a5a59dae` | 3647 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TestDataSource@17; mChannelCount@20; AppendFrames@22; PendingFrames@29; TEST@56
Dependencies: algorithm@5; AudioStream.h@7; CubebUtils.h@8; MockCubeb.h@9; gtest/gtest.h@10; mozilla/gtest/WaitFor.h@11

`dom/media/gtest/TestAudioTrackEncoder.cpp` | `20f1959b5930ce159f77b7898578a9d9be6979f8` | 10284 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TestOpusTrackEncoder@12; OpusTrackEncoder@16; TestOpusRawCreation@19; TestOpusInit@29; TEST@35; TEST@66; TestOpusResampler@157; TEST@163; TEST@179; TEST@195; TEST@225; TestSampleRate@254; TEST@282
Dependencies: AudioGenerator.h@5; AudioSampleFormat.h@6; OpusTrackEncoder.h@7; gtest/gtest.h@8

`dom/media/gtest/TestAudioTrackGraph.cpp` | `c4049f9386a3c21dde15fa8b19f31348648740f6` | 191432 bytes | test-path,source | UTF-8 | mode 100644
Declarations: StartInputProcessing@74; mInputProcessing@82; StopInputProcessing@86; ControlMessage@91; GoFaster@118; ControlMessage@123; StartNonNativeInput@127; mInputSource@135; StopNonNativeInput@139; ControlMessage@143; OnFallbackListener@149; OnFallbackListener@154; Reset@156; OnFallback@157; MockAudioDataListener@167; MockProcessedMediaTrack@188; ProcessedMediaTrack@191; TEST_WithTailDispatch@235; TEST_WithTailDispatch@284; TEST_WithTailDispatch@312; NS_GetCurrentThread@378; TEST_WithTailDispatch@390; TEST_WithTailDispatch@406; TEST_WithTailDispatch@436; DeviceInfo@468; DeviceQueryMessage@475; mHolder@483; TEST_WithTailDispatch@605; TestDeviceInputConsumerTrack@676; Create@678; Destroy@686; DeviceInputConsumerTrack@716; TEST_WithTailDispatch@719; TestAudioDataListener@728; TestAudioDataListener@730; TestAudioDataListener@833; TestAudioDataListener@835; TEST_WithTailDispatch@1061; TestAudioDataListener@1062; TestAudioDataListener@1064; TEST_WithTailDispatch@1246; TEST_WithTailDispatch@1310; WaitUntil@1360; TEST_WithTailDispatch@1400; rmsf32@1576; TEST_WithTailDispatch@1591; TEST_WithTailDispatch@1723; WaitUntil@2175; WaitUntil@2193; WaitUntil@2241; WaitUntil@2259; TEST_WithTailDispatch@2278; TEST_WithTailDispatch@2667; TEST_WithTailDispatch@2685; TEST_WithTailDispatch@2699; WaitUntil@2746; TEST_WithTailDispatch@2804; TEST_WithTailDispatch@2908; TEST_WithTailDispatch@3384; TEST_WithTailDispatch@3455; TrackDestroyShutdownFactory@3570; mShutdownSvc@3577; TEST_WithTailDispatch@3597; TEST@3665; TestRunnable@3895; mCheckpoint@3904; TEST@3933; MicroTaskDispatcher@4154; mGraph@4158; TEST@4176; TestShutdownTask@4285; mGraph@4291; TEST@4311; IPCTestRunnable@4411; mGraph@4416; TEST@4430; TEST@4524
Dependencies: CrossGraphPort.h@5; DeviceInputTrack.h@6; MediaTrackGraphImpl.h@7; StaticComponents.h@8; VideoUtils.h@9; gmock/gmock.h@10; gtest/gtest-printers.h@11; gtest/gtest.h@12; MediaEngineWebRTCAudio.h@14; MockCubeb.h@16; WavDumper.h@17; mozilla/Components.h@18; mozilla/CycleCollectedJSContext.h@19; mozilla/GenericFactory.h@20; mozilla/Preferences.h@21; mozilla/SpinEventLoopUntil.h@22; mozilla/StateMirroring.h@23; mozilla/gtest/MozHelpers.h@24; mozilla/gtest/WaitFor.h@25; mozilla/ipc/IOThread.h@26; nsComponentManager.h@27; nsITargetShutdownTask.h@28; nsIThreadInternal.h@29; nsXPCOMPrivate.h@30

`dom/media/gtest/TestBitWriter.cpp` | `9afc1cd85ac0652e3eeeef970612d06e449ce4aa` | 2066 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@13; TEST@59
Dependencies: stdint.h@5; BitReader.h@7; BitWriter.h@8; gtest/gtest.h@9

`dom/media/gtest/TestBlankVideoDataCreator.cpp` | `b7d99e3aa08e170d91cf28a896bed2bd96405509` | 922 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@11; TEST@21
Dependencies: BlankDecoderModule.h@5; ImageContainer.h@6; gtest/gtest.h@7

`dom/media/gtest/TestBufferMediaResource.cpp` | `5fbbc265e37cdb0288ecce00450565fbe3a6b17b` | 2441 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@11; TEST@22; TEST@33; TEST@48; TEST@59; TEST@70
Dependencies: BufferMediaResource.h@5; gtest/gtest.h@6; mozilla/RefPtr.h@7

`dom/media/gtest/TestBufferReader.cpp` | `7fe8690d6d7ca715e555bda50d283cd0326a1464` | 1597 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@10; TEST@39
Dependencies: BufferReader.h@5; gtest/gtest.h@6

`dom/media/gtest/TestCDMStorage.cpp` | `1962dd844a6e09470b8b50cb4907f135b6129fde` | 46396 bytes | test-path,source | UTF-8 | mode 100644
Declarations: GetGMPThread@25; EnumerateDir@37; EnumerateCDMStorageDir@56; GMPShutdownObserver@83; mNodeId@90; NotifyObserversTask@129; mozilla::Runnable@132; ClearCDMStorageTask@145; mContinuation@149; SimulatePBModeExit@198; TestGetNodeIdCallback@207; mNodeId@210; Done@212; IsCDMStorageIsEmpty@273; AssertIsOnGMPThread@287; CDMStorageTest@300; DoTest@303; CDMStorageTest@311; Update@313; TestGetNodeId@319; TestGetNodeId_Continuation@360; TestBasicStorage@424; TestForgetThisSite@448; TestForgetThisSite_AnotherSite@462; NodeInfo@475; siteToForget@478; NodeIdCollector@484; NodeIdCollector@486; operator@487; TestForgetThisSite_CollectSiteInfo@500; TestForgetThisSite_Forget@513; NodeIdVerifier@532; mExpectedRemainingNodeIds@536; operator@537; StorageVerifier@562; mExpectedRemainingNodeIds@565; operator@566; TestForgetThisSite_Verify@584; TestForgetThisBaseDomain@599; TestForgetThisBaseDomain_SecondSite@613; TestForgetThisBaseDomain_ThirdSite@626; BaseDomainNodeInfo@640; baseDomainToForget@642; BaseDomainNodeIdCollector@648; mNodeInfo@651; operator@652; TestForgetThisBaseDomain_CollectSiteInfo@665; BaseDomainNodeIdVerifier@698; mExpectedRemainingNodeIds@702; operator@703; BaseDomainStorageVerifier@727; mExpectedRemainingNodeIds@730; operator@731; TestClearRecentHistory1@769; TestClearRecentHistory2@790; TestClearRecentHistory3@811; MaxMTimeFinder@825; MaxMTimeFinder@827; operator@828; GetResult@836; TestClearRecentHistory1_Clear@842; TestClearRecentHistory2_Clear@854; TestClearRecentHistory3_Clear@866; FileCounter@878; FileCounter@880; operator@881; GetCount@882; TestClearRecentHistory_CheckEmpty@888; TestClearRecentHistory_CheckNonEmpty@905; TestCrossOriginStorage@923; TestCrossOriginStorage_RecordStoredContinuation@947; TestPBStorage@961; TestPBStorage_RecordStoredContinuation@978; TestPBStorage_RecordRetrievedContinuation@991; TestOutputProtection@1004; TestLongRecordNames@1016; AwaitFinished@1076; ShutdownThen@1082; Shutdown@1095; Dummy@1103; SetFinished@1105; Terminated@1131; ExpectedMessage@1141; mMessage@1144; CallbackProxy@1156; CallbackProxy@1158; CreateTestDirectory@1203; TestMatchBaseDomain_MatchOrigin@1219; TestMatchBaseDomain_MatchTLD@1235; TestMatchBaseDomain_NoMatch@1251; TEST@1267; TEST@1272; TEST@1277; TEST@1282; TEST@1288; TEST@1294; TEST@1300; TEST@1306; TEST@1312; TEST@1318; TEST@1324; TEST@1330; TEST@1336; TEST@1343
Dependencies: ChromiumCDMCallback.h@5; ChromiumCDMParent.h@6; GMPServiceParent.h@7; GMPTestMonitor.h@8; MediaResult.h@9; gtest/gtest.h@10; mozilla/RefPtr.h@11; mozilla/SchedulerGroup.h@12; mozilla/SpinEventLoopUntil.h@13; mozilla/gtest/MozAssertions.h@14; nsCRTGlue.h@15; nsDirectoryServiceDefs.h@16; nsDirectoryServiceUtils.h@17; nsIFile.h@18; nsNSSComponent.h@19; nsThreadUtils.h@20

`dom/media/gtest/TestCamerasParent.cpp` | `60a7c3a898f69f3ff242ed0d6e3acd06f10f1897` | 18284 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@32; RunOnBackgroundThread@33; WaitForBackgroundThread@40; MockCamerasParent@44; Create@49; MockVideoCapturer@68; MockVideoCapturer@86; MockVideoCaptureFactory@98; MockVideoCaptureFactory@105; TestableCamerasParent@128; Create@133; TestCamerasParent@152; SetUpTestSuite@155; TEST_F@172; TEST_F@174; TestAggregateCapturerWithDeviceInfo@231; TEST_F@297; TEST_F@301; TEST_F@307; TEST_F@320; TEST_F@344; TEST_F@362; TEST_F@390; TEST_F@447; TEST@462
Dependencies: memory@5; CamerasParent.h@7; VideoEngine.h@8; api/video/i420_buffer.h@9; fake_video_capture/device_info_empty.h@10; fake_video_capture/device_info_fake.h@11; gmock/gmock.h@12; gtest/gtest.h@13; mozilla/SyncRunnable.h@14; mozilla/gtest/WaitFor.h@15; mozilla/ipc/BackgroundParent.h@16; video_engine/video_capture_factory.h@17

`dom/media/gtest/TestCubebInputStream.cpp` | `3c00a33dc5ec34b34c35125d27bdfa0921b22744` | 6031 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockListener@18; TEST@29; TEST@86; TEST@133
Dependencies: CubebInputStream.h@5; MockCubeb.h@6; gmock/gmock.h@7; gtest/gtest.h@8; mozilla/gtest/WaitFor.h@9

`dom/media/gtest/TestDataMutex.cpp` | `02f5785a060f0fc3cc722a992b8aa8e76dd08f27` | 1006 bytes | test-path,source | UTF-8 | mode 100644
Declarations: A@11; Set@12; TEST@16
Dependencies: gtest/gtest.h@5; mozilla/DataMutex.h@6; nsTArray.h@7

`dom/media/gtest/TestDecodedStream.cpp` | `1d8a4be97372813b6557f27dabd2dbe5f1ae264a` | 7824 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@21; MediaType@22; constexpr@28; constexpr@32; CreateMediaInfo@40; constexpr@43; constexpr@46; OnFallbackListener@52; OnFallbackListener@57; Reset@59; OnFallback@60; TestDecodedStream@71; CreateMediaInfo@204; TEST_F@211
Dependencies: BlankDecoderModule.h@5; DecodedStream.h@6; MediaData.h@7; MediaQueue.h@8; MediaSinkTestUtils.h@9; MediaTrackGraphImpl.h@10; MediaTrackListener.h@11; MockCubeb.h@12; gtest/gtest.h@13; mozilla/SyncRunnable.h@14; mozilla/gtest/WaitFor.h@15; nsJSEnvironment.h@16

`dom/media/gtest/TestDeviceInputTrack.cpp` | `7b683ee9e7205c450d2d8b383c4110d0c042f386` | 19798 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockGraphImpl@24; MediaTrackGraphImpl@27; Init@31; MockDriver@46; MockDriver@49; TestDeviceInputTrack@66; TestDeviceInputTrack@68; TEST_F@82; TestDeviceInputConsumerTrack@83; Create@85; Destroy@93; DeviceInputConsumerTrack@113; TestAudioDataListener@116; mChannelCount@119; TEST_F@178; MockEventListener@236; TEST_F@248; TEST_F@351; TEST_F@446; TEST_F@503
Dependencies: AudioGenerator.h@5; DeviceInputTrack.h@6; MediaTrackGraphImpl.h@7; MockCubeb.h@8; gmock/gmock.h@9; gtest/gtest.h@10; mozilla/StaticPrefs_media.h@11; mozilla/gtest/WaitFor.h@12; nsContentUtils.h@13

`dom/media/gtest/TestDriftCompensation.cpp` | `8f04ec4c6418a92fda99cbe1547d7c918cf646ab` | 3503 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DriftCompensatorTest@11; Past@35; Future@40; TEST_F@43; TEST_F@47; TEST_F@57; TEST_F@67; TEST_F@76
Dependencies: DriftCompensation.h@5; gtest/gtest.h@6; mozilla/SpinEventLoopUntil.h@7

`dom/media/gtest/TestFFmpegDecodeStats.cpp` | `325d7277d772895f3e36d7991839095d6f790fed` | 2889 bytes | test-path,source | UTF-8 | mode 100644
Declarations: InsertSlowFrame@26; InsertFastFrame@32; TEST@37; TEST@43; TEST@54; TEST@63; TEST@79
Dependencies: chrono@7; thread@8; FFmpegDecodeStats.h@10; gtest/gtest.h@11

`dom/media/gtest/TestGMPCrossOrigin.cpp` | `f8a14396df8ee7c5ba728cd06f36e69f81f2f2d0` | 6847 bytes | test-path,source | UTF-8 | mode 100644
Declarations: GMPTestRunner@18; RunTestGMPVideoCodec@39; Run@50; T@56; Base@57; mMonitor@60; Get@62; RunTestGMPVideoCodec@75; RunTestGMPVideoCodec@78; GMPTestRunner::RunTestGMPTestCodec1@82; GMPTestRunner::RunTestGMPTestCodec2@86; GMPTestRunner::RunTestGMPTestCodec3@90; RunTestGMPCrossOrigin@95; mShouldBeEqual@126; Step2@128; Base@132; RunTestGMPCrossOrigin@155; RunTestGMPCrossOrigin@157; GMPTestRunner::RunTestGMPCrossOrigin1@160; GMPTestRunner::RunTestGMPCrossOrigin2@164; GMPTestRunner::RunTestGMPCrossOrigin3@168; GMPTestRunner::RunTestGMPCrossOrigin4@172; void@177; TEST@190; TEST@198
Dependencies: GMPServiceParent.h@5; GMPTestMonitor.h@6; GMPVideoDecoderProxy.h@7; GMPVideoEncoderProxy.h@8; gtest/gtest.h@9; mozilla/StaticPtr.h@10; mozilla/gtest/MozAssertions.h@11; nsAppDirectoryServiceDefs.h@12; nsThreadUtils.h@13

`dom/media/gtest/TestGMPPluginScan.cpp` | `55cea40296299360af745f89807057701ff46d5f` | 2386 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@13; ExpectPluginsFromEnvironment@22; TEST@35
Dependencies: GMPUtils.h@5; gtest/gtest.h@6; mozilla/MozPromise.h@7; mozilla/gtest/WaitFor.h@8; nsString.h@9; nsTArray.h@10; nsThreadUtils.h@11

`dom/media/gtest/TestGMPRemoveAndDelete.cpp` | `fe5b29cb397f4aab90a5db8be341ba56d191c0f6` | 13704 bytes | test-path,source | UTF-8 | mode 100644
Declarations: GMPRemoveTest@28; TEST@105; TEST@117; TEST@132; TEST@157; GetService@185; GetServiceParent@195; mIsTerminated@208; GMPRemoveTest::~GMPRemoveTest@210; GMPRemoveTest::Setup@217; GMPRemoveTest::CreateVideoDecoder@243; Callback@290; mMonitor@294; std::move@312; GMPRemoveTest::CloseVideoDecoder@317; GMPRemoveTest::DeletePluginDirectory@327; GMPRemoveTest::Decode@331; GMPRemoveTest::gmp_Decode@341; EncodedFrame@344; SPSNalu@345; PPSNalu@349; IDRNalu@353; GMPRemoveTest::Wait@390; GMPRemoveTest::IsTerminated@392; GMPRemoveTest::Decoded@411; GMPRemoveTest::Error@418; GMPRemoveTest::Terminated@424; GMPRemoveTest::GeneratePlugin@432
Dependencies: GMPService.h@5; GMPServiceParent.h@6; GMPTestMonitor.h@7; GMPUtils.h@8; GMPVideoDecoderProxy.h@9; gmp-api/gmp-video-host.h@10; gtest/gtest.h@11; mozilla/Services.h@12; mozilla/StaticPtr.h@13; nsDirectoryServiceDefs.h@14; nsIObserverService.h@15

`dom/media/gtest/TestGMPUtils.cpp` | `fedd53632599c170d730aea26d65b2d7716fc350` | 2320 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@27; TEST@55; Test@57
Dependencies: string@5; GMPUtils.h@7; gtest/gtest.h@8; nsString.h@9

`dom/media/gtest/TestGMPVideoEncodedFrame.cpp` | `35c798e7f7595fed795169c7e91d6978a9d04b5a` | 2623 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@28; TEST@55; TEST@63
Dependencies: GMPVideoEncodedFrameImpl.h@5; GMPVideoHost.h@6; gtest/gtest.h@7; mozilla/gmp/GMPTypes.h@8

`dom/media/gtest/TestGMPVideoi420Frame.cpp` | `77223747282c920c787aed1ba9f007dc9b64326d` | 4545 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PlaneData@14; FrameWithBuffer@20; MakeValidI420Frame@68; TEST@84; TEST@94; TEST@104; TEST@114; TEST@121; TEST@129; TEST@137
Dependencies: climits@6; GMPVideoi420FrameImpl.h@8; gtest/gtest.h@9; mozilla/gmp/GMPTypes.h@10

`dom/media/gtest/TestGroupId.cpp` | `19cf4f6db8a86e5248cc791d3cb555e674869238` | 11483 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PrintTo@16; PrintTo@20; TEST@60; TEST@82; TEST@102; TEST@125; TEST@158; TEST@184; TEST@220; TEST@243; TEST@266; TEST@285
Dependencies: AudioDeviceInfo.h@5; MediaManager.h@6; gmock/gmock.h@7; gtest/gtest-printers.h@8; gtest/gtest.h@9; nsTArray.h@10; webrtc/MediaEngineFake.h@11

`dom/media/gtest/TestH264FmtpParser.cpp` | `9694ed8cdb9f08658ce3ede824430eea9d7a6f04` | 9463 bytes | test-path,source | UTF-8 | mode 100644
Declarations: Parse@12; TEST@21; TEST@30; TEST@42; TEST@51; TEST@60; TEST@69; TEST@79; TEST@90; TEST@100; TEST@110; TEST@119; TEST@126; TEST@133; TEST@140; TEST@148; TEST@156; TEST@165; TEST@172; TEST@181; TEST@190; TEST@199; TEST@213; TEST@222; TEST@233; TEST@243; TEST@251; TEST@261
Dependencies: MediaMIMETypes.h@5; api/rtp_parameters.h@6; gtest/gtest.h@7; mozilla/media/webrtc/H264FmtpParser.h@8

`dom/media/gtest/TestHDRUtils.cpp` | `83fa04a0a74b6e43c6af8fa421af8d0911eefab4` | 4394 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MakeBT2020_1000nit@15; TEST@28; TEST@55; TEST@80; TEST@94; TEST@106; TEST@120; TEST@132
Dependencies: HDRUtils.h@5; gtest/gtest.h@6; mozilla/gfx/Types.h@7

`dom/media/gtest/TestImageConversion.cpp` | `8b81f5384ca85ebb2c415ad11d24d2259411b3ca` | 38041 bytes | test-path,source | UTF-8 | mode 100644
Declarations: YCbCrValue@45; RGBValue@53; ChromaDivisor@69; TestPlanarYCbCrImage@85; mFormat@95; Fill@149; SizeOfExcludingThis@181; IsInterleaved@184; GenerateI420@202; TEST@276; TEST@297; TEST@397; TEST@422; TEST@451; TEST@473; TEST@540; TEST@575; RGBSample@608; RGBToYUVExpectation@620; TEST@724; TEST@755; ForEachRedSourceImage@789; TEST@812; ForEachRedSourceImage@815; TEST@826; ForEachRedSourceImage@829; TEST@847; TEST@875; TEST@903; TEST@914; TEST@960
Dependencies: iterator@5; ImageContainer.h@7; ImageConversion.h@8; SourceSurfaceRawData.h@9; gtest/gtest.h@10; mozilla/CheckedInt.h@11; mozilla/RefPtr.h@12; mozilla/UniquePtr.h@13; mozilla/dom/ImageBitmapBinding.h@14; mozilla/dom/ImageUtils.h@15

`dom/media/gtest/TestIntervalSet.cpp` | `c54e08faebb48d346717137230cfd0a2f0ff7d7c` | 23377 bytes | test-path,source | UTF-8 | mode 100644
Declarations: media@17; media@18; media@19; CreateByteInterval@21; TEST@33; CreateTimeInterval@63; CreateTimeIntervals@73; TEST@79; TEST@115; TEST@121; TEST@138; TEST@155; TEST@168; TEST@244; TEST@260; TEST@276; TEST@290; Duplicate@309; TEST@314; TEST@349; TEST@361; TEST@374; TEST@390; TEST@415; TEST@425; TEST@452; TEST@479; TEST@495; TEST@531; TEST@539; TEST@585; TEST@604; Foo@661; Foo@663; Foo@665; TEST@691; TEST@705; TEST@720
Dependencies: algorithm@5; type_traits@6; vector@7; Intervals.h@9; TimeUnits.h@10; gtest/gtest.h@11; mozilla/ErrorResult.h@12; mozilla/dom/TimeRanges.h@13

`dom/media/gtest/TestMP3Demuxer.cpp` | `4755a998db7a267c41252332f8eb0e38a82afb3a` | 22603 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockMP3MediaResource@13; MockMP3StreamMediaResource@14; mozilla@15; MockMP3MediaResource@24; MockMediaResource@29; MockMP3StreamMediaResource@36; MockMP3MediaResource@41; MP3Resource@49; class@50; Duration@51; mMicroseconds@56; Tolerance@57; MP3DemuxerTest@91; TEST_F@440; TEST_F@455; TEST_F@474; TEST_F@537; TEST_F@591; mozilla@632; TEST_F@634
Dependencies: gtest/gtest.h@5; climits@7; vector@8; MP3Demuxer.h@10; MockMediaResource.h@11

`dom/media/gtest/TestMP4Demuxer.cpp` | `f644f47c5ccff265833b82bc735a41ad29aa260b` | 45619 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MP4DemuxerBinding@29; mIndex@49; mIndex@58; RunTestAndWait@61; CheckTrackKeyFrame@68; DispatchTask@90; CheckTrackSamples@109; DispatchTask@117; DispatchTask@150; TEST@159; ToCryptoString@180; TEST@202; TEST@348; TEST@563; TEST@599; TEST@660; TEST@699; TEST@709; TEST@719; ReadFileToBuffer@729; TEST@783; TEST@811; MakeTrackInfo@844; TEST@864; TEST@940; TEST@994; TEST@1023; TEST@1047; TEST@1081; TEST@1095; TEST@1109; TEST@1123; TEST@1137; TEST@1151; TEST@1165
Dependencies: AOMDecoder.h@5; BufferMediaResource.h@6; DecoderData.h@7; H265.h@8; MP4Demuxer.h@9; MediaDataDemuxer.h@10; MockMediaResource.h@11; VideoUtils.h@12; gtest/gtest.h@13; mozilla/MozPromise.h@14; mozilla/SharedThreadPool.h@15; mozilla/TaskQueue.h@16; mozilla/gtest/MozAssertions.h@17; mp4parse.h@18

`dom/media/gtest/TestMediaCapabilities.cpp` | `a06a7c60d53c0bc2fbdd7ea2c5c3d4f713d9f21a` | 3609 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@18; TEST@46; TEST@74
Dependencies: MediaCapabilities.h@5; MediaInfo.h@6; MockDecoderModule.h@7; PDMFactory.h@8; VPXDecoder.h@9; VideoUtils.h@10; gtest/gtest.h@11; mozilla/gtest/WaitFor.h@12

`dom/media/gtest/TestMediaCodecsSupport.cpp` | `8ba277320a449bcd7875fcd77a9234f63ac9fe7e` | 9997 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@11; TEST@40; TEST@82; TEST@136; TEST@180; TEST@223
Dependencies: MediaCodecsSupport.h@5; gtest/gtest.h@6

`dom/media/gtest/TestMediaDataDecoder.cpp` | `61879d9468d572e45fbc257658be56af07f4fb43` | 9515 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PropertyTest@26; SetUpTestSuite@28; TearDownTestSuite@43; std::to_string@81; CheckAndroid@98; TEST@202; TEST@216; CheckApple@230; TEST_P@250; TEST_P@263
Dependencies: type_traits@5; H264.h@7; ImageContainer.h@8; MP4Demuxer.h@9; MockMediaResource.h@10; PDMFactory.h@11; VideoUtils.h@12; gfxPlatform.h@13; gtest/gtest.h@14; mozilla/ScopeExit.h@15; mozilla/SharedThreadPool.h@16; mozilla/UniquePtr.h@17; mozilla/gtest/ScopedPrefSetter.h@18; mozilla/gtest/WaitFor.h@19

`dom/media/gtest/TestMediaDataEncoder.cpp` | `9b05f1b331a20e2ddd4ece5f33abe6bff021371c` | 62941 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MediaDataEncoderTest@97; FrameSource@112; GetSize@119; Init@121; Deinit@140; GetFrame@146; Draw@195; EnsureInit@243; WaitForShutdown@251; EncodeResult@283; GetKeyFrameCount@343; AsVariant@443; TEST_F@449; RUN_IF_SUPPORTED@450; TEST_F@457; RUN_IF_SUPPORTED@458; RUN_IF_SUPPORTED@482; TEST_F@523; TEST_F@527; TEST_F@531; TEST_F@535; TEST_F@539; TEST_F@544; TEST_F@549; TEST_F@554; TEST_F@570; TEST_F@582; RUN_IF_SUPPORTED@599; TEST_F@622; TEST_F@626; TEST_F@630; TEST_F@634; TEST_F@638; TEST_F@643; TEST_F@648; TEST_F@653; RUN_IF_SUPPORTED@667; TEST_F@685; TEST_F@690; TEST_F@695; TEST_F@699; RUN_IF_SUPPORTED@712; TEST_F@735; TEST_F@740; TEST_F@745; TEST_F@750; TEST_F@756; RUN_IF_SUPPORTED@757; TEST_F@770; RUN_IF_SUPPORTED@771; TEST_F@793; RUN_IF_SUPPORTED@794; CreateNV12Frame@827; TEST_F@857; RUN_IF_SUPPORTED@858; TEST_F@888; RUN_IF_SUPPORTED@890; TEST_F@926; RUN_IF_SUPPORTED@927; TEST_F@934; RUN_IF_SUPPORTED@935; TEST_F@951; RUN_IF_SUPPORTED@952; TEST_F@986; RUN_IF_SUPPORTED@987; TEST_F@1001; RUN_IF_SUPPORTED@1002; TEST_F@1036; RUN_IF_SUPPORTED@1037; TEST_F@1069; RUN_IF_SUPPORTED@1070; TEST_F@1103; RUN_IF_SUPPORTED@1104; TEST_F@1111; RUN_IF_SUPPORTED@1112; TEST_F@1128; RUN_IF_SUPPORTED@1129; TEST_F@1161; RUN_IF_SUPPORTED@1162; TEST_F@1176; RUN_IF_SUPPORTED@1177; TEST_F@1211; RUN_IF_SUPPORTED@1212; TEST_F@1248; RUN_IF_SUPPORTED@1249; EncoderConfig::CodecSpecific@1291; TEST_F@1311; TEST_F@1342; AV1ColorTestData@1428; TEST_F@1498; RUN_IF_SUPPORTED@1499; TEST_F@1516; RUN_IF_SUPPORTED@1517; GetAV1FrameTemporalId@1534; TEST_F@1547; RUN_IF_SUPPORTED@1548; TEST_F@1580; RUN_IF_SUPPORTED@1581; TEST_F@1617; RUN_IF_SUPPORTED@1618
Dependencies: algorithm@5; AOMDecoder.h@7; AnnexB.h@8; BufferReader.h@9; H264.h@10; ImageContainer.h@11; MediaData.h@12; PEMFactory.h@13; TimeUnits.h@14; VPXDecoder.h@15; VideoUtils.h@16; gtest/gtest.h@17; mozilla/AbstractThread.h@18; mozilla/Preferences.h@19; mozilla/SpinEventLoopUntil.h@20; mozilla/gtest/ScopedPrefSetter.h@21; mozilla/gtest/WaitFor.h@22; mozilla/media/MediaUtils.h@23

`dom/media/gtest/TestMediaEventSource.cpp` | `3efa4b7282c07474fa1764ae5a42f621d1bda174` | 24616 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@29; TEST@57; TEST@89; TEST@119; TEST@152; TEST@168; Foo@184; Foo@185; OnNotify@186; TEST@206; TEST@239; Foo@250; OnNotify1@251; OnNotify2@252; OnNotify3@253; SomeEvent@276; SomeEvent@277; SomeEvent@280; SomeEvent@281; TEST@288; Foo@301; OnNotify@302; TEST@322; Foo1@341; OnNotify@342; Foo2@346; OnNotify@347; TEST@373; Foo@386; OnNotify@387; TEST@406; Foo@423; OnNotify@424; OnNotify2@425; TEST@451; Foo1@466; OnNotify@467; Foo2@473; OnNotify@474; TEST@501; Foo@513; OnNotify@514; TEST@539; TEST@566; TEST@591; RefCounter@613; RefCounter@615; TEST@626; TEST@656; DestroyChecker@684; DestroyChecker@685; ClassForDestroyCheck@697; DestroyChecker@701; RefCountNums@703; TEST@709; TEST@741; TEST@758
Dependencies: memory@5; MediaEventSource.h@7; VideoUtils.h@8; gmock/gmock-matchers.h@9; gmock/gmock.h@10; gtest/gtest.h@11; mozilla/SharedThreadPool.h@12; mozilla/TaskQueue.h@13; mozilla/UniquePtr.h@14

`dom/media/gtest/TestMediaFormatReader.cpp` | `bd40f51e591716fa41f19b56e57f369362d7cfd4` | 52208 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ResolveOneSample@55; TestMediaFormatReader@63; SetUpReaderDependencies@70; SetVideoMediaTime@104; ON_CALL@105; AddAudioTrack@115; ON_CALL@117; InitReader@128; FinishShutdown@149; WaitForReaderOperations@159; ExpectDecoderWithFailingPrimingDrain@180; ExpectDemuxReachingInternalSeekPriming@212; EXPECT_CALL@223; ReachInternalSeekPriming@240; TEST_F@271; EXPECT_CALL@274; TEST_F@283; EXPECT_CALL@286; ON_CALL@290; TEST_F@310; EXPECT_CALL@315; EXPECT_CALL@320; EXPECT_CALL@324; TEST_F@349; EXPECT_CALL@352; TEST_F@370; TEST_F@407; EXPECT_CALL@410; TEST_F@430; EXPECT_CALL@435; EXPECT_CALL@439; TEST_F@458; ON_CALL@463; ON_CALL@467; TEST_F@488; EXPECT_CALL@524; EXPECT_CALL@528; EXPECT_CALL@536; EXPECT_CALL@540; EXPECT_CALL@546; TEST_F@597; RecreateOnNthDecodeDecoder@644; MockVideoDataDecoder@648; VideoRateTest@666; class@668; ExpectedRate@673; SampleSpec@684; ON_CALL@697; ShutdownReader@704; AddSampleWithoutTrackInfo@734; RecreateFirstDecoderOnDecode@738; InitReader@743; ReadFrame@795; ReadToEnd@799; SetNullDecode@813; SeekToStart@818; VideoRate@823; TEST_F@838; TEST_F@857; TEST_F@881; TEST_F@898; TEST_F@921; TEST_F@955; TEST_F@991; EXPECT_CALL@999; TEST_F@1015; TEST_F@1034; EXPECT_CALL@1042; TEST_F@1060; TEST_F@1093; TestMFRCryptoSampleSizeCheck@1132; mOwner@1151; InitReader@1180; TEST_F@1227; ON_CALL@1230; TEST_F@1248; ON_CALL@1250; TEST_F@1267; ON_CALL@1269
Dependencies: initializer_list@5; ImageContainer.h@7; MediaFormatReader.h@8; MockDecoderModule.h@9; MockMediaDataDemuxer.h@10; MockMediaDecoderOwner.h@11; PDMFactory.h@12; ReaderProxy.h@13; TimeUnits.h@14; VideoFrameContainer.h@15; gtest/gtest.h@16; mozilla/Atomics.h@17; mozilla/Preferences.h@18; mozilla/SpinEventLoopUntil.h@19; mozilla/gfx/gfxVars.h@20; mozilla/gtest/MozAssertions.h@21; mozilla/gtest/WaitFor.h@22; nsQueryObject.h@23

`dom/media/gtest/TestMediaInfo.cpp` | `01c840fb7f9e481682ad82fb925f906f2647f25b` | 1294 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@10
Dependencies: MediaInfo.h@5; gtest/gtest.h@6

`dom/media/gtest/TestMediaMIMETypes.cpp` | `bdb28ca40bba4758f004e1a5ee4ab44f23e4ddad` | 13105 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@10; TEST@29; TEST@41; TEST@82; TEST@181; TEST@193
Dependencies: MediaMIMETypes.h@5; gtest/gtest.h@6

`dom/media/gtest/TestMediaQueue.cpp` | `7176de069f3965064f2b32627d2e88a2bbe348b7` | 9659 bytes | test-path,source | UTF-8 | mode 100644
Declarations: CreateData@33; TEST@42; TEST@84; TEST@118; TEST@127; TEST@146; TEST@160; TEST@179; TEST@213; TEST@270; TEST@289
Dependencies: gtest/gtest.h@5; MediaData.h@7; MediaQueue.h@8; nsISupportsImpl.h@9

`dom/media/gtest/TestMediaSpan.cpp` | `9dc9f9dda5813950958813db594ace9a3aaa7ed5` | 3005 bytes | test-path,source | UTF-8 | mode 100644
Declarations: makeBuffer@12; IsRange@34; TEST@38; TEST@62; TEST@88
Dependencies: gtest/gtest.h@5; stdint.h@6; MediaSpan.h@8

`dom/media/gtest/TestMediaUtils.cpp` | `d2e9a706d72bc6e61b6b5e51c22cc739ff14b4b9` | 8496 bytes | test-path,source | UTF-8 | mode 100644
Declarations: DoCreateTicketBeforeAppShutdownOnMain@27; DoCreateTicketAfterAppShutdownOnMain@80; DoCreateTicketBeforeAppShutdownOffMain@101; DoCreateTicketAfterAppShutdownOffMain@163; DoTwoTicketsWithSameNameBothBlockShutdown@192; TEST@235; TEST@241; TEST@247; TEST@253; TEST@259
Dependencies: MediaUtils.h@5; gtest/gtest.h@6; mozilla/AppShutdown.h@7; mozilla/SyncRunnable.h@8; mozilla/gtest/MozHelpers.h@9; gfxPlatformMac.h@12

`dom/media/gtest/TestMuxer.cpp` | `87644edf44efd06c5cbc5d9fdf15cbb4777612ae` | 7763 bytes | test-path,source | UTF-8 | mode 100644
Declarations: MockContainerWriter@66; TEST@77; TEST@115; TEST@159
Dependencies: ContainerWriter.h@5; EncodedFrame.h@6; Muxer.h@7; OpusTrackEncoder.h@8; WebMWriter.h@9; gmock/gmock.h@10; gtest/gtest.h@11

`dom/media/gtest/TestOfflineClockDriver.cpp` | `9446f629d5e95f6427e364aabd19ac6c3370ac2b` | 1841 bytes | test-path,source | UTF-8 | mode 100644
Dependencies: MockGraphInterface.h@5; gtest/gtest.h@6; mozilla/gtest/WaitFor.h@7

`dom/media/gtest/TestOggWriter.cpp` | `ecdef323f169e30733fe472c40c2a08371912892` | 2030 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@12
Dependencies: OggWriter.h@5; OpusTrackEncoder.h@6; gtest/gtest.h@7

`dom/media/gtest/TestOpusParser.cpp` | `ffa6806bed27d1d701abe534bc77fa34563f7d04` | 886 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@12
Dependencies: algorithm@5; OpusParser.h@7; gtest/gtest.h@8

`dom/media/gtest/TestPDMFactorySupport.cpp` | `76ca7b18628de6cc532d611a91df1808f8fecf1c` | 7434 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@18; TEST@30; TEST@49; TEST@72; TEST@107; TEST@123; TEST@143; InvokeAsync@155; TEST@186
Dependencies: PDMFactorySupport.h@5; VideoUtils.h@6; gtest/gtest.h@7; mozilla/Preferences.h@8; mozilla/SpinEventLoopUntil.h@9; mozilla/TaskQueue.h@10; mozilla/gfx/gfxVars.h@11; mozilla/gtest/WaitFor.h@12

`dom/media/gtest/TestPacer.cpp` | `8796d6fc5b500724c60c7cd8099ba98bb905b041` | 8089 bytes | test-path,source | UTF-8 | mode 100644
Declarations: PacerTest@16; mInterval@23; EnqueueSoon@29; TearDown@37; Interval@42; SetInterval@44; PacerTestInt@57; PacerTestIntLongDuplication@65; PacerTestIntLongDuplication@67; PacerTestIntTenMsDuplication@70; PacerTestInt@73; PacerTestIntInfDuplication@76; PacerTestIntInfDuplication@78; TEST_F@93; TEST_F@104; TEST_F@115; TEST_F@140; TEST_F@161; TEST_F@190; TEST_F@219; WaitUntil@241
Dependencies: thread@5; Pacer.h@7; VideoUtils.h@8; gmock/gmock-matchers.h@9; gtest/gtest.h@10; mozilla/gtest/WaitFor.h@11

`dom/media/gtest/TestQuantizableBuffer.cpp` | `87c41ab36133d893ba497f569d38781d9f284cc1` | 7516 bytes | test-path,source | UTF-8 | mode 100644
Declarations: QuantizableBufferTest@18; TestBuffer@25; TEST_P@124; TEST_P@138; TEST_P@167
Dependencies: limits@5; ImageContainer.h@7; MediaData.h@8; VideoUtils.h@9; gtest/gtest.h@10; mozilla/DefineEnum.h@11; mozilla/UniquePtr.h@12

`dom/media/gtest/TestRTCStatsTimestampMaker.cpp` | `f3cb33b5bd70f2bd6e456e0396e2b303217bc6d1` | 4361 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@19; TEST@36; TEST@55; TEST@69; TEST@84; TEST@102
Dependencies: cmath@5; gtest/gtest.h@7; jsapi/RTCStatsReport.h@8; libwebrtcglue/SystemTime.h@9; mozilla/dom/PerformanceService.h@10

`dom/media/gtest/TestRemoteImageHolder.cpp` | `8c8046723b295ef1b935824858bc952d3ea2d9bc` | 13519 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TestGPUVideoSurfaceManager@21; ColorMetadata@23; MakeInvalidDescriptor@60; MakeValidDescriptor@68; MakeColorMetadataDescriptor@85; MakeOversizedDisplayDescriptor@94; MakeInvalidChromaDimensionsDescriptor@103; TEST@111; TEST@123; TEST@135; TEST@164; TEST@205; TEST@232; TEST@263; TEST@285; TEST@323
Dependencies: GPUVideoImage.h@6; ImageContainer.h@7; gtest/gtest.h@8; mozilla/RemoteImageHolder.h@9; mozilla/gfx/Types.h@10; mozilla/ipc/Shmem.h@11; mozilla/layers/BufferTexture.h@12; mozilla/layers/ImageDataSerializer.h@13; mozilla/layers/LayersSurfaces.h@14

`dom/media/gtest/TestRust.cpp` | `5050e80dfa19f0d0317a5cd94191f8346d5239c5` | 211 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@7
Dependencies: stdint.h@1; gtest/gtest.h@3

`dom/media/gtest/TestSimpleMap.cpp` | `da06c6a7fb0202f0c46d0f787bf7e1fb93ff7d72` | 2922 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@9; TEST@11; TEST@27; TEST@57; TEST@67; TEST@88; TEST@107
Dependencies: SimpleMap.h@5; gtest/gtest.h@6; nsString.h@7

`dom/media/gtest/TestSpeechModelMapping.cpp` | `fd8b065fbb6c49b31f02b5f8cfe737b5086e28a8` | 1525 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@10; TestCase@12; TEST@33; TEST@40
Dependencies: gtest/gtest.h@5; mozilla/dom/SpeechRecognitionModelMapping.h@6

`dom/media/gtest/TestTelemetryProbesReporter.cpp` | `003230720f36958732c93f5417efcc625f986ad3` | 1017 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@11
Dependencies: TelemetryProbesReporter.h@5; gtest/gtest.h@6; nsError.h@7

`dom/media/gtest/TestTimeUnit.cpp` | `d7631172fff123dfffbb850b0e70c629b04d6a4a` | 9600 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@12; TEST@67; TEST@91; TEST@122; TEST@225; TEST@273; TEST@296
Dependencies: TimeUnits.h@5; gtest/gtest.h@6

`dom/media/gtest/TestUnboundedMPSCQueue.cpp` | `106cb39c3f8d0d5011ff9268ca5e28ba98c2d0fa` | 14753 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@19; MoveOnlyValue@21; MoveOnlyValue@22; MoveOnlyValue@28; CountedType@42; CountedType@43; CountedType@45; CountedType@51; PushValue@71; TEST@79; TEST@87; TEST@98; TEST@115; TEST@135; TEST@153; TEST@186; TEST@200; TEST@217; TEST@236; TEST@255; TEST@268; TEST@282; UnboundedMPSCQueueMTTest@292; TEST_P@299; TEST_P@339; NS_NewRunnableFunction@357; TEST_P@394; TEST@439; TEST@480
Dependencies: gtest/gtest.h@5; algorithm@7; cstdint@8; string@9; vector@10; UnboundedMPSCQueue.h@12; mozilla/Atomics.h@13; mozilla/TaskQueue.h@14; mozilla/UniquePtr.h@15; nsThreadManager.h@16; nsThreadUtils.h@17

`dom/media/gtest/TestVPXDecoding.cpp` | `848691cfcca41f63c2be994ebcbd96d98231402f` | 2749 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ReadVPXFile@13; TestFileData@62; TEST@71
Dependencies: stdio.h@5; VPXDecoder.h@7; gtest/gtest.h@8; nsTArray.h@9

`dom/media/gtest/TestVideoData.cpp` | `afc3a7013ac89f7e5db5912fe2afd70984f2b807` | 12908 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TestHDRTransferFunctionPropagation@42; TEST@89; TEST@94; TEST@100; TEST@125; TEST@219; NoCopyPlanarYCbCrImage@287; NoCopyPlanarYCbCrImage@289; SizeOfExcludingThis@294; TEST@299; TEST@323
Dependencies: ImageContainer.h@5; MediaData.h@6; MediaInfo.h@7; MediaResult.h@8; gtest/gtest.h@9; mozilla/AutoRestore.h@10; mozilla/ResultVariant.h@11; mozilla/gfx/Types.h@12; nsIWidget.h@13; nsTArray.h@14

`dom/media/gtest/TestVideoFrameContainer.cpp` | `189d939df391c80a3a0f55ee9b3e5f29cd9a16b0` | 2377 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@20
Dependencies: ImageContainer.h@5; MockMediaDecoderOwner.h@6; TimeUnits.h@7; VideoFrameContainer.h@8; gmock/gmock.h@9; gtest/gtest.h@10; nsContentUtils.h@11

`dom/media/gtest/TestVideoFrameConverter.cpp` | `949fe40038480c620bfdf78afe54b292c7069233` | 30402 bytes | test-path,source | UTF-8 | mode 100644
Declarations: VideoFrameConverterTest@21; FrameListener@23; mSource@28; SetWants@42; DebugVideoFrameConverter@57; VideoFrameConverterTest@73; mListener@82; CalcMultiplesInMillis@124; TEST_F@175; TEST_F@190; TEST_F@207; TEST_F@224; TEST_F@252; TEST_F@283; TEST_F@359; TEST_F@382; TEST_F@420; TEST_F@463; TEST_F@513; TEST_F@543; TEST_F@578; TEST_F@647; TEST_F@696
Dependencies: array@5; iterator@6; thread@7; MediaEventSource.h@9; VideoFrameConverter.h@10; VideoUtils.h@11; YUVBufferGenerator.h@12; gmock/gmock-matchers.h@13; gtest/gtest.h@14; mozilla/gtest/WaitFor.h@15; rtc_base/ref_counted_object.h@16

`dom/media/gtest/TestVideoSegment.cpp` | `3367759a4d586c786daaa824d25b4d81656339d1` | 3977 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@10; Image@11; TEST@14; TEST@30; TEST@46
Dependencies: VideoSegment.h@5; gtest/gtest.h@6

`dom/media/gtest/TestVideoSink.cpp` | `421eda31a6ec268891bff89e9c8b0daac96275d5` | 11152 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@23; TestVideoSinkPause@165; PushVideoFrame@219; PlayUntil@231; TEST_F@259; TEST_F@266
Dependencies: AudioDeviceInfo.h@5; AudioSink.h@6; AudioSinkWrapper.h@7; ImageContainer.h@8; MediaSinkTestUtils.h@9; MockCubeb.h@10; MockMediaDecoderOwner.h@11; TimeUnits.h@12; VideoFrameContainer.h@13; VideoSink.h@14; gtest/gtest.h@15; mozilla/gtest/WaitFor.h@16

`dom/media/gtest/TestVideoTrackEncoder.cpp` | `d21e8db9e18bfbbb46353bce847401739d55934e` | 59233 bytes | test-path,source | UTF-8 | mode 100644
Declarations: InitParam@29; MockDriftCompensator@35; DriftCompensator@38; TestVP8TrackEncoder@46; DriftCompensator@53; TestInit@57; SumDurations@103; TEST@111; TEST@127; TEST@147; TEST@169; TEST@193; FrameSpec@226; TEST@269; TEST@305; TEST@338; TEST@373; TEST@408; TEST@450; TEST@493; TEST@542; TEST@604; TEST@654; TEST@682; TEST@734; TEST@783; TEST@813; TEST@845; TEST@876; TEST@908; TEST@965; TEST@1033; TEST@1080; TEST@1128; TEST@1171; TEST@1220; TEST@1270; TEST@1347; TEST@1418; TEST@1469; TEST@1517; TEST@1610
Dependencies: algorithm@5; DriftCompensation.h@7; MediaTrackGraph.h@8; MediaTrackListener.h@9; TimeUnits.h@10; VP8TrackEncoder.h@11; WebMWriter.h@12; YUVBufferGenerator.h@13; gmock/gmock.h@14; gtest/gtest.h@15; prtime.h@16

`dom/media/gtest/TestVideoUtils.cpp` | `6fffa32d1db14af13a54f53f4b3d30e1fef39a20` | 5595 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@12; TEST@32; TEST@48; TEST@99
Dependencies: VideoUtils.h@5; gtest/gtest.h@6; nsMimeTypes.h@7; nsString.h@8

`dom/media/gtest/TestWMFDeadlock.cpp` | `ba1db5b5110de15997ca91f1c60faa6088aebded` | 4105 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@27; TEST@32; mscom::EnsureMTA@63; mscom::EnsureMTA@92
Dependencies: atomic@18; EncoderConfig.h@20; MediaCodecsSupport.h@21; WMF.h@22; gtest/gtest.h@23; mozilla/mscom/EnsureMTA.h@24; nsThreadUtils.h@25

`dom/media/gtest/TestWebMBuffered.cpp` | `98b814931033ba6c30bc76d63c0a5605b3c0abae` | 9973 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@17; TEST@36; ReadFile@53; TEST@74; TEST@96; TEST@132; TEST@146; TEST@160; TEST@176; TEST@192; TEST@208; TEST@222; InitEndOffsetOf@237; TEST@246; TEST@257; TEST@272; TEST@284; TEST@298
Dependencies: stdio.h@5; WebMBufferedParser.h@7; gtest/gtest.h@8; nsTArray.h@9

`dom/media/gtest/TestWebMDemuxer.cpp` | `39b070b7486eec3346c074c639417f336a1f3f0b` | 20296 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@21; InvokeAsync@32; TEST@84; InvokeAsync@112; TEST@195; InvokeAsync@205; TEST@254; InvokeAsync@264; TEST@309; InvokeAsync@319; TEST@369; InvokeAsync@389
Dependencies: H265.h@5; MatroskaDemuxer.h@6; MediaDataDemuxer.h@7; MockMediaResource.h@8; VideoUtils.h@9; WebMDemuxer.h@10; gtest/gtest-spi.h@11; gtest/gtest.h@12; mozilla/MozPromise.h@13; mozilla/SharedThreadPool.h@14; mozilla/TaskQueue.h@15; mozilla/gfx/Types.h@16

`dom/media/gtest/TestWebMWriter.cpp` | `79687c04a9c11b1f00d93503868fb6d8f203575f` | 20778 bytes | test-path,source | UTF-8 | mode 100644
Declarations: WebMOpusTrackEncoder@16; OpusTrackEncoder@19; TestOpusCreation@20; WebMVP8TrackEncoder@29; Init@38; TestWebMWriter@68; HaveValidCluster@101; TEST@112; TEST@145; TEST@183; WebMioData@233; webm_read@238; webm_seek@258; webm_tell@292; TEST@298; Flatten@368; CountClusters@379; DemuxedPacket@390; ExpectedTimestampNs@398; DemuxWebM@405; TEST@444; TEST@476; TEST@516; TEST@566
Dependencies: DriftCompensation.h@5; OpusTrackEncoder.h@6; VP8TrackEncoder.h@7; WebMWriter.h@8; gtest/gtest.h@9; mozilla/CheckedInt.h@10; mozilla/MathAlgorithms.h@11; nestegg/nestegg.h@12

`dom/media/gtest/TestWebRTCCodecInfo.cpp` | `084bf7abda98afbd1a9db965fde3aa9c71e7208e` | 16167 bytes | test-path,source | UTF-8 | mode 100644
Declarations: WebRTCCodecInfoTest@74; TestAudioDecodeEncodeSWHW@155; TEST_F@170; TEST_F@186; TEST_F@218; TEST_F@246; TEST_F@255; TEST_F@261; TEST_F@270; TEST_F@291; TEST_F@304; TEST_F@322; TEST_F@344; TEST_F@367; TEST_F@387
Dependencies: EncoderConfig.h@7; MediaMIMETypes.h@8; PlatformDecoderModule.h@9; VideoUtils.h@10; gtest/gtest.h@11; mozilla/Preferences.h@12; mozilla/SpinEventLoopUntil.h@13; mozilla/gfx/gfxVars.h@14; mozilla/gtest/ScopedPrefSetter.h@15; mozilla/media/webrtc/CodecInfo.h@16; nsThreadUtils.h@17

`dom/media/gtest/TestWebrtcCodecFactory.cpp` | `0d98ea1c354e160877dbd852885caab30f1d440b` | 6416 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@18; class@20; TestWebrtcVideoDecoderFactory@22; dom::RTCStatsTimestampMaker::Create@31; TestWebrtcVideoEncoderFactory@57; dom::RTCStatsTimestampMaker::Create@65; DoTestRacyGmpPluginForwards@97; EventType@106; constexpr@133; TEST_F@156; TEST_F@160
Dependencies: MediaMIMETypes.h@5; PlatformDecoderModule.h@6; WebrtcEnvironmentWrapper.h@7; WebrtcGmpVideoCodec.h@8; WebrtcVideoCodecFactory.h@9; gmock/gmock.h@10; gtest/gtest.h@11; mozilla/gtest/WaitFor.h@12

`dom/media/gtest/TestWebrtcGmpCodec.cpp` | `0fde9f82e3c769200d19a6964f3618610c0c9dbb` | 15791 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@21; TestWebrtcGmpVideoEncoder@23; InitEncodeAndWait@65; WaitForGmpThread@72; MockEncodedImageCallback@79; CreateBlackFrame@86; TEST_F@92; TEST_F@94; TEST_F@96; TEST_F@128; TEST_F@187; TEST_F@250; TEST@310; TEST@323; TEST@357; TEST@366; TEST@379; TEST@393; TEST@405
Dependencies: WebrtcGmpVideoCodec.h@5; api/video/i420_buffer.h@6; gmock/gmock.h@7; gtest/gtest.h@8; media/base/media_constants.h@9; mozilla/gtest/WaitFor.h@10

`dom/media/gtest/TestWebrtcTaskQueueWrapper.cpp` | `089a5fe3fba56f7a804c6bed187bc4c81eb8bb5c` | 2042 bytes | test-path,source | UTF-8 | mode 100644
Declarations: mozilla@14; MakeTestWebrtcTaskQueueWrapper@16; TEST@22; TEST@41
Dependencies: WebrtcTaskQueueWrapper.h@5; gmock/gmock.h@6; gtest/gtest.h@7; mozilla/TaskQueue.h@8; nsThreadUtils.h@9

`dom/media/gtest/TestYUVBufferGenerator.cpp` | `4ee8df01635a6c1fd0a952f934c1c12f4654af29` | 7851 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@25; TEST@109; TEST@179
Dependencies: limits@5; ImageContainer.h@7; YUVBufferGenerator.h@8; gtest/gtest.h@9; mozilla/RefPtr.h@10

`dom/media/gtest/YUVBufferGenerator.cpp` | `5c6775943149c703c6c72b0bae2feb6710f18287` | 5967 bytes | test-path,source | UTF-8 | mode 100644
Declarations: YUVBufferGenerator::GetSize@76; YUVBufferGenerator::FillI420SourceBuffer@80; YUVBufferGenerator::GenerateI420Image@98; YUVBufferGenerator::GenerateNV12Image@137; YUVBufferGenerator::GenerateNV21Image@173
Dependencies: YUVBufferGenerator.h@5; VideoUtils.h@7; mozilla/CheckedInt.h@8

`dom/media/gtest/YUVBufferGenerator.h` | `d28545c11bb5519e8d2f3c46f9e2393336dcaf7d` | 2333 bytes | test-path,source | UTF-8 | mode 100644
Declarations: YUVBufferGenerator@18; ChannelColor@20; class@26
Dependencies: cstddef@8; cstdint@9; ImageContainer.h@11; Point.h@12; Rect.h@13; mozilla/AlreadyAddRefed.h@14; nsTArray.h@15

`dom/media/gtest/av1-color-metadata.mp4` | `2458b572c6d137e3451dd9cb2d00510b306f4366` | 868 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/dash_dashinit.mp4` | `d19068f36de613d822c3cebaeffd3ef5601f183e` | 80388 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/generate_color_metadata_video.py` | `acbcccf6c35584cb1395ecde0a6d8ea2c09fe9ce` | 2905 bytes | test-path,source | UTF-8 | mode 100755
Declarations: encoder_option@24; parse_args@31; main@53
Dependencies: pathlib@21

`dom/media/gtest/hello.rs` | `af1308eee6c0bfd19a3be7f8745043faa7a73d41` | 168 bytes | test-path,source | UTF-8 | mode 100644

`dom/media/gtest/id3v2header.mp3` | `2f5585d02ea15a35478deb6bb8d6072c6a92b191` | 191302 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/moz.build` | `979f9521e7140b4caba2cd5c1339438c6ae6853c` | 6778 bytes | test-path,build-registration | UTF-8 | mode 100644
Dependencies: /dom/media/webrtc/third_party_build/webrtc.mozbuild@5; /ipc/chromium/chromium-config.mozbuild@207

`dom/media/gtest/mp4_demuxer/TestInterval.cpp` | `c3f62785c9e0e8b26cd620db4adbd1cb38384de5` | 2008 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TEST@10; TEST@16; TEST@25; TEST@38; TEST@69
Dependencies: MP4Interval.h@5; gtest/gtest.h@6

`dom/media/gtest/mp4_demuxer/TestMP4.cpp` | `40145955c0e40814e5acb38e35a9616e96621546` | 3646 bytes | test-path,source | UTF-8 | mode 100644
Declarations: error_reader@15; read_vector@19; read_vector::read_vector@27; read_vector::read_vector@34; vector_reader@38; TEST@57; TEST@109; stat@116
Dependencies: stdint.h@5; stdio.h@6; string.h@7; algorithm@9; vector@10; gtest/gtest.h@12; mp4parse.h@13

`dom/media/gtest/mp4_demuxer/TestParser.cpp` | `557bfea49fcab1bf608f305bd7ece6cb1627bcae` | 54648 bytes | test-path,source | UTF-8 | mode 100644
Declarations: TestStream@17; mozilla@18; TestStream@26; mHighestSuccessfulEndOffset@30; TEST@71; TEST@98; ReadTestFile@119; TestFileData@156; TEST@260; TEST@386; TEST@423; TEST@472; TEST@523; TEST@579; TEST@637; TEST@674; TEST@718; TEST@742; TEST@768; TEST@877; TEST@909; MP4MetadataTelemetryFixture@934; TEST_F@936; TEST@1155; TEST@1187; TEST@1203
Dependencies: BufferStream.h@5; MP4Metadata.h@6; MediaData.h@7; MoofParser.h@8; SampleIterator.h@9; TelemetryFixture.h@10; TelemetryTestHelpers.h@11; gtest/gtest.h@12; js/Conversions.h@13; mozilla/Preferences.h@14; mozilla/gtest/MozAssertions.h@15

`dom/media/gtest/mp4_demuxer/moz.build` | `575dea41ecb6d81f083493ae96899b904a31d9a7` | 2033 bytes | test-path,build-registration | UTF-8 | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1156505.mp4` | `687b06ee1f6cb25aac396154ba82e14932637947` | 296 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1181213.mp4` | `e2326edb4e426d69b889b70dc96183cb853f5277` | 2834 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1181215.mp4` | `7adba3836f74a916c2a9216c9492a95928418c84` | 3086 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1181223.mp4` | `2aa2d5abfd226fa00b34b143d80e5e3a51c4e852` | 2834 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1181719.mp4` | `6846edd6edfc2b4bbbba0fd64a9c7f96a1877a69` | 3095 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1185230.mp4` | `ac5cbdbe85d57dc91f52eff2444ba13c8ac9a5ea` | 3250 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1187067.mp4` | `fdb396eeb30c2906c71236940005493d75770718` | 2835 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1200326.mp4` | `5b8b27d508a4aff7b0cdd0c9f060e32a0025eda7` | 1694 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1204580.mp4` | `4e55b05719230440851fd678096967f6def883d5` | 5833 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1216748.mp4` | `7072f53bec645e38947b1b2322c4f0704d9d31d5` | 296 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1296473.mp4` | `109eb51064d46ffa0ad07714ce4c5bacea706a36` | 5995 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1296532.mp4` | `5a5669bb89951baf1d09e575302210e5a7af8f7f` | 152132 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-harder.mp4` | `7d678b7c66052eb3b5510f67a679388d633b404e` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-i64max.mp4` | `5a3572f88ca3f6d1aa667b4452d852c93c7d64ac` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-i64min.mp4` | `4d3eb366e12487b49df35f4d6ded1ff84d5c563a` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-max-ez.mp4` | `17fbf411ed21060df80cd2752c8fb8a0f6367cd5` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-max-ok.mp4` | `a5e1e4610db5c486cdabaca47dbd749be16da7e3` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-overfl.mp4` | `1ef24e932b19bc5aca8d61f8e97d7d897363e4b3` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-u32max.mp4` | `b1d8b6ce7e6f01801b1715ef821a2ad28eda2383` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065-u64max.mp4` | `419dcba2c10cd739074d8290da2c55fb494e2594` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1301065.mp4` | `543a4fba3e0f72a6170c35c52913d6cfdf613cc7` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1329061.mov` | `4246b8f716b90591aed4e3e1b2a25994f37a9143` | 93681 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1351094.mp4` | `2dfd4c35ce3b6f3d3895e094537d44b4b1ff483a` | 80388 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1388991.mp4` | `deb7aae33a2f6400711768951702380b691c519e` | 288821 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1389299.mp4` | `78dc390a3d74d22c96bf9ee771cc58010dded7c6` | 152132 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1389527.mp4` | `6406fcb8f8b0dc60e1bd9e0a5d0ac4f54ff7eb11` | 92225 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1395244.mp4` | `da43d017ed2e87e9cf739e28ebccd11db29880ae` | 13651 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1410565.mp4` | `ebeaa08354f8fd20db8817d4f454ae3b71339d3d` | 955656 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1513651-2-sample-description-entries.mp4` | `2f8f235a9b4b826547a387fdb4ffc801d317a9b3` | 1100 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1519617-cenc-init-with-track_id-0.mp4` | `e76e9f08943fa793062a6745fb5b46a7ebe12107` | 767 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1519617-track2-trafs-removed.mp4` | `55bd57c7db781031527c36d38609e506169e5f66` | 282228 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1519617-video-has-track_id-0.mp4` | `8cb4dcc212965d1ef20da7f0910d0902d79401d1` | 282024 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_1714125-2-sample-description-entires-with-identical-crypto.mp4` | `4356259e683f888709ba8626e19b4cd57176f9a8` | 1119 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_2004835-overflow-tfdt.mp4` | `cc013058af22d38a56e63d9390bdeac8c3bb39b5` | 764 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_aac_encoder_delay_tfdt.mp4` | `20997e228db1837c3d4adb10187e7f9ef837e820` | 325 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_bad_co64_offset.mp4` | `b6e6ddb8022acc95803ddeb91c08047be1f46c03` | 632 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_bad_fragmented_saio_offset.mp4` | `a87342628c88e59484d33a754f6073c462cd4316` | 751 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/mp4_demuxer/test_case_bad_fragmented_trun_offset.mp4` | `6474819292d5e4bf286415fd2ee52e8a4fbb38d5` | 718 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/negative_duration.mp4` | `de86bf497ca2ca5545bd9ccf0333d4ed6f9f62a7` | 684 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/noise.mp3` | `e76b50350289bfbdbcc3d572f44799dd9fcbc0d5` | 965257 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/noise_vbr.mp3` | `284ebe40bfbf645b53a485f793c90dcd3cc34247` | 583679 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/short-zero-in-moov.mp4` | `577318c8fa8aaf3bc8541844c07d3a5092ea489c` | 13655 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/short-zero-inband.mov` | `9c1864286526a0db4a4ee98bdcb34111539d2625` | 93641 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/small-shot-false-positive.mp3` | `2f1e794051e9dd05955514f15bfca0dda8f917df` | 6845 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/small-shot-partial-xing.mp3` | `99d68e3cbe0cc7d8d1bc84082efbf82d9117af26` | 6825 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/small-shot.mp3` | `f9397a5106be1fe2b5838539096d43e5f0251f8d` | 6825 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test.webm` | `fc9e9912702fc5a7ead9b5e80e54bc042d3613ff` | 1980 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_InvalidElementId.webm` | `74e24d20930f2d4edc592652bf62886b1c8ca05e` | 1122 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_InvalidElementSize.webm` | `420a1452cef1d7630a9e743591f03b79ef2ef9f4` | 1122 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_InvalidLargeEBMLMaxIdLength.webm` | `fc2d9ce88ecb871ea0646118ac642ac1471de7dd` | 1122 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_InvalidLargeElementId.webm` | `ceac160d9d3f279d17ab3ca55925f25e1405150b` | 1129 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_InvalidSmallEBMLMaxIdLength.webm` | `ca38a258c8e7c906ee40f96c127652a3e67ba495` | 1122 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_ValidLargeEBMLMaxIdLength.webm` | `44bca6101e69e17e840595f4d5d6cb44e2a79458` | 1128 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_ValidSmallEBMLMaxSizeLength.webm` | `23fd2b36a620ad1f4e224517f449a15b351e83c6` | 1116 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_av1.mp4` | `311b475dcace6f039f13376f7ba7a9a1445336bd` | 9497 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_case_1224361.vp8.ivf` | `e2fe942f0e66e7ff18b2626ae0250a02e04ef7b7` | 1497 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_case_1224363.vp8.ivf` | `6d2e4e02063b750d7ee9a349acedc517e7e8a83d` | 1388 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_case_1224369.vp8.ivf` | `2f8deb1148b29b4bce415488219c1ea664f9a1bd` | 204 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_hevc_open_gop.mkv` | `21e7e5f1818819885599922a33d924219a725c3a` | 11150 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_hevc_open_gop.mp4` | `bc35076242890bce49357138a3aa8d64126db1b0` | 12131 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/test_vbri.mp3` | `efd74503385c9d8c6afaf59a8923cf67ebd71805` | 16519 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/tos-vp9-hdr-cll.webm` | `e7f72b1ee0197162c2f5399cec5b83c8147bd2bc` | 281 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/gtest/truncated-xing-placeholder.mp3` | `307ac9ee55ef9f8c0f9d113bebe2faaf547b7170` | 110061 bytes | test-path,data-or-other | binary-NUL | mode 100644

`dom/media/hls/HLSDecoder.cpp` | `b1a995fa9e3c7dff24c7a7c7bcbd7ac4e2f8efe0` | 17243 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@40; HLSResourceCallbacksSupport@42; java@47; GeckoHttpChannelListener@78; mResult@85; mMutex@133; HLSResourceCallbacksSupport::Detach@137; HLSResourceCallbacksSupport::NotifyChannelResponse@143; HLSResourceCallbacksSupport::OnDataArrived@168; HLSResourceCallbacksSupport::OnError@183; HLSDecoder::Create@319; HLSDecoder::HLSDecoder@327; HLSDecoder::~HLSDecoder@333; HLSDecoder::IsEnabled@360; HLSDecoder::IsSupportedType@365; HLSDecoder::Load@369; HLSDecoder::AddSizeOfResources@398; HLSDecoder::GetCurrentPrincipal@403; HLSDecoder::HadCrossOriginRedirects@408; HLSDecoder::Play@414; HLSDecoder::Pause@421; HLSDecoder::Suspend@428; HLSDecoder::Resume@434; HLSDecoder::Shutdown@440; HLSDecoder::NotifyDataArrived@456; HLSDecoder::RecordMediaUsage@463; HLSDecoder::UpdateCurrentPrincipal@476
Dependencies: HLSDecoder.h@5; AndroidBridge.h@7; DecoderTraits.h@8; GeckoViewStreamListener.h@9; HLSDemuxer.h@10; HLSUtils.h@11; JavaBuiltins.h@12; JavaExceptions.h@13; MediaContainerType.h@14; MediaDecoderStateMachine.h@15; MediaFormatReader.h@16; MediaShutdownManager.h@17; base/process_util.h@18; mozilla/BasePrincipal.h@19; mozilla/ErrorNames.h@20; mozilla/NullPrincipal.h@21; mozilla/StaticPrefs_media.h@22; mozilla/SyncRunnable.h@23; mozilla/dom/HTMLMediaElement.h@24; mozilla/glean/DomMediaHlsMetrics.h@25; mozilla/java/GeckoAppShellWrappers.h@26; mozilla/java/GeckoHLSResourceWrapperNatives.h@27; mozilla/java/GeckoResultWrappers.h@28; mozilla/java/WebMessageWrappers.h@29; mozilla/java/WebRequestWrappers.h@30; mozilla/widget/WebExecutorSupport.h@31; nsContentUtils.h@32; nsIChannel.h@33; nsIHttpChannel.h@34; nsILoadInfo.h@35; nsMimeTypes.h@36; nsNetUtil.h@37; nsThreadUtils.h@38

`dom/media/hls/HLSDecoder.h` | `012452d7c7f8056b7be3cc3bf4f00d97d08bcff3` | 2536 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@11; HLSResourceCallbacksSupport@13; HLSDecoder@15
Dependencies: MediaDecoder.h@8; mozilla/java/GeckoHLSResourceWrapperWrappers.h@9

`dom/media/hls/HLSDemuxer.cpp` | `c22f1d44603791742f5d543f6d5bbf3d1ffbe173` | 21992 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; TrackInfo@22; getVideoInfoRotation@27; getStereoMode@42; HLSDemuxer@61; java@66; mMutex@73; OnInitialized@77; OnError@95; Detach@114; HLSDemuxer::OnInitialized@143; HLSDemuxer::OnError@158; HLSDemuxer::Init@163; InvokeAsync@165; HLSDemuxer::NotifyDataArrived@171; HLSDemuxer::GetNumberTracks@175; HLSDemuxer::IsSeekable@197; HLSDemuxer::GetCrypto@201; HLSDemuxer::GetNextKeyFrameTime@207; HLSDemuxer::OnTaskQueue@212; HLSDemuxer::~HLSDemuxer@214; mTrackInfo@234; HLSTrackDemuxer::GetInfo@241; HLSTrackDemuxer::UpdateMediaInfo@345; HLSTrackDemuxer::Reset@524; HLSTrackDemuxer::UpdateNextKeyFrameTime@529; HLSTrackDemuxer::GetNextRandomAccessPoint@539; HLSTrackDemuxer::SkipToNextRandomAccessPoint@550; HLSTrackDemuxer::DoSkipToNextRandomAccessPoint@557; TimeUnit::FromMicroseconds@583; HLSTrackDemuxer::GetBuffered@607; HLSTrackDemuxer::BreakCycles@614; HLSTrackDemuxer::~HLSTrackDemuxer@623
Dependencies: HLSDemuxer.h@5; stdint.h@7; algorithm@9; HLSUtils.h@11; MediaCodec.h@12; mozilla/java/GeckoAudioInfoWrappers.h@13; mozilla/java/GeckoHLSDemuxerWrapperNatives.h@14; mozilla/java/GeckoVideoInfoWrappers.h@15; nsPrintfCString.h@16

`dom/media/hls/HLSDemuxer.h` | `a489f4ec7eb8c657bbcb325ed274621b935c6a64` | 4013 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; AbstractThread@20; MediaResult@21; HLSTrackDemuxer@22; HLSDemuxer@27; HLSDemuxerCallbacksSupport@29; GetTaskQueue@49; HLSTrackDemuxer@71; IsTrackValid@98
Dependencies: MediaCodec.h@8; MediaDataDemuxer.h@9; MediaDecoder.h@10; VideoUtils.h@11; mozilla/Maybe.h@12; mozilla/Mutex.h@13; mozilla/TaskQueue.h@14; mozilla/java/GeckoHLSDemuxerWrapperWrappers.h@15; mozilla/java/GeckoHLSSampleWrappers.h@16

`dom/media/hls/HLSUtils.cpp` | `22adb16cd3075c7d3839faaa14a6bb322bf79d62` | 337 bytes | source | UTF-8 | mode 100644
Declarations: GetHLSLog@7
Dependencies: HLSUtils.h@5

`dom/media/hls/HLSUtils.h` | `98dd2930b6a1a6d99e2bd9788b182fc87e574e2e` | 748 bytes | source | UTF-8 | mode 100644
Dependencies: mozilla/Logging.h@8

`dom/media/hls/metrics.yaml` | `1a0a2ac32af17419050c51b1d617594bfcfe276d` | 2086 bytes | data-or-other | UTF-8 | mode 100644

`dom/media/hls/moz.build` | `51c3aa923ddecb70be7eb1425fd4ab3c7a0255cd` | 530 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@18; /tools/fuzzing/libfuzzer-config.mozbuild@23

`dom/media/imagecapture/CaptureTask.cpp` | `bfafd47b945480151074e3aa15698d9520145310` | 5551 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@18; CaptureTask@20; mCaptureTask@23; mPrincipalChanged@38; CaptureTask::AttachTrack@78; CaptureTask::DetachTrack@87; CaptureTask::PrincipalChanged@96; EncodeComplete@108; EncodeComplete@110; CaptureTask::PostTrackEndEvent@169; TrackEndRunnable@176; mozilla::Runnable@179
Dependencies: CaptureTask.h@5; VideoSegment.h@7; gfxUtils.h@8; mozilla/SchedulerGroup.h@9; mozilla/dom/BlobImpl.h@10; mozilla/dom/ImageCapture.h@11; mozilla/dom/ImageCaptureError.h@12; mozilla/dom/ImageEncoder.h@13; mozilla/dom/MediaStreamTrack.h@14; mozilla/dom/VideoStreamTrack.h@15; nsThreadUtils.h@16

`dom/media/imagecapture/CaptureTask.h` | `3f064742fc6f8fc68a3cfb00531b07d7cc097bd2` | 3130 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; dom@14; BlobImpl@15; ImageCapture@16; MediaStreamTrack@17; CaptureTask@30; MediaTrackEventListener@33
Dependencies: MediaTrackGraph.h@8; MediaTrackListener.h@9; PrincipalChangeObserver.h@10

`dom/media/imagecapture/ImageCapture.cpp` | `a5e21c9f11bca2bac4dde62056e1f8cf4c8739be` | 6308 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@20; GetICLog@22; dom@27; DOMEventTargetHelper@39; ImageCapture::~ImageCapture@44; ImageCapture::GetVideoStreamTrack@65; ImageCapture::TakePhotoByMediaEngine@67; TakePhotoCallback@70; mPrincipalChanged@77; ImageCapture::TakePhoto@115; ImageCapture::PostBlobEvent@143; ImageCapture::PostErrorEvent@162; ImageCapture::CheckPrincipal@190
Dependencies: ImageCapture.h@5; CaptureTask.h@7; MediaEngineSource.h@8; mozilla/dom/BlobEvent.h@9; mozilla/dom/DOMException.h@10; mozilla/dom/Document.h@11; mozilla/dom/Event.h@12; mozilla/dom/File.h@13; mozilla/dom/ImageCaptureError.h@14; mozilla/dom/ImageCaptureErrorEvent.h@15; mozilla/dom/ImageCaptureErrorEventBinding.h@16; mozilla/dom/VideoStreamTrack.h@17; nsGlobalWindowInner.h@18

`dom/media/imagecapture/ImageCapture.h` | `bbe4b43fd7cf4c678b88defe3a95ad6cd901ace1` | 2885 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@12; dom@20; Blob@22; MediaStreamTrack@23; VideoStreamTrack@24; ImageCapture@40; GetParentObject@61
Dependencies: mozilla/DOMEventTargetHelper.h@8; mozilla/Logging.h@9; mozilla/dom/ImageCaptureBinding.h@10

`dom/media/imagecapture/moz.build` | `c783fb22bd04210c2396ff6e3f265bb7f717add3` | 431 bytes | build-registration | UTF-8 | mode 100644
Dependencies: /ipc/chromium/chromium-config.mozbuild@12

`dom/media/ipc/MFCDMChild.cpp` | `acc90071da2075bb3d7da8bb130b560121ee7608` | 19854 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@15; mShutdown@77; MFCDMChild::~MFCDMChild@79; MFCDMChild::EnsureRemote@81; MFCDMChild::Shutdown@126; NS_NewRunnableFunction@131; MFCDMChild::AssertSendable@191; MFCDMChild::ActorDestroy@476
Dependencies: MFCDMChild.h@5; RemoteMediaManagerChild.h@7; mozilla/EMEUtils.h@8; mozilla/KeySystemConfig.h@9; mozilla/RefPtr.h@10; mozilla/StaticString.h@11; mozilla/WMFCDMProxyCallback.h@12; nsString.h@13

`dom/media/ipc/MFCDMChild.h` | `503eab4bcde48edc2d5fda2b74b6190e72e68a71` | 5656 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@14; WMFCDMProxyCallback@16; MFCDMChild@22; Id@80; ManagerThread@88; AssertOnManagerThread@89
Dependencies: unordered_map@8; mozilla/Atomics.h@10; mozilla/MozPromise.h@11; mozilla/PMFCDMChild.h@12

`dom/media/ipc/MFCDMParent.cpp` | `0edb544c7cc9621ea33ae91b88ea3c1e1af82c67` | 71813 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@48; GenerateDummySessionId@122; AutoPropVar@134; AutoPropVar@136; Receive@147; Reset@153; InitDataTypeToString@180; RequireClearLead@193; MFCDMParent::IsClearLead@198; getter_AddRefs@302; MapKeySystem@371; IsBeingProfiledOrLogEnabled@386; MFCDMParent::SetWidevineL1Path@392; MFCDMParent::GetCDMById@401; MFCDMParent::Register@407; MFCDMParent::Unregister@414; mCDMAccessLock@433; MFCDMParent::OnHardwareContextReset@464; MFCDMParent::RecreateCDM@498; MFCDMParent::SetupPMPHostApp@527; MFCDMParent::ShutdownCDM@545; MFCDMParent::ActorDestroy@565; MFCDMParent::~MFCDMParent@589; MFCDMParent::GetCDMLibraryName@595; StaticPrefs::media_eme_wmf_use_mock_cdm_for_external_cdms@597; IsWidevineKeySystem@605; MFCDMParent::Shutdown@612; IsWMFClearKeySystemAndSupported@715; IsWidevineKeySystem@718; IsWidevineKeySystem@781; FAILED@895; IsWidevineKeySystem@963; MFCDMParent::GetAllKeySystemsCapabilities@972; SecureLevel@987; IsWidevineExperimentKeySystemAndSupported@1014; FAILED@1092; MFCDMParent::PrewarmHDCP@1608; MFCDMParent::MarkHDCPCondition@1654; MFCDMParent::WaitForHDCPSettleAfterReset@1667; MFCDMParent::ConnectSessionEvents@1682; MFCDMParent::GetSession@1690; MFCDMParent::GetMFCDMProxy@1699; MFCDMService::GetAllKeySystemsCapabilities@1706; MFCDMService::UpdateWidevineL1Path@1780
Dependencies: MFCDMParent.h@5; mfmediaengine.h@7; unknwnbase.h@8; wtypes.h@9; mozilla/Likely.h@11; prinrval.h@13; propkeydef.h@14; propvarutil.h@15; MFCDMProxy.h@17; MFMediaEngineUtils.h@18; RemoteDecodeUtils.h@19; SpecialSystemDirectory.h@20; WMFUtils.h@21; mozilla/DataMutex.h@22; mozilla/EMEUtils.h@23; mozilla/KeySystemConfig.h@24; mozilla/ProfilerMarkers.h@25; mozilla/RandomNum.h@26; mozilla/StaticMutex.h@27; mozilla/StaticPrefs_media.h@28; mozilla/WindowsVersion.h@29; mozilla/dom/KeySystemNames.h@30; mozilla/dom/MediaKeysBinding.h@31; mozilla/dom/Promise.h@32; mozilla/gfx/gfxVars.h@33; mozilla/ipc/UtilityMediaServiceChild.h@34; mozilla/ipc/UtilityProcessManager.h@35; mozilla/ipc/UtilityProcessParent.h@36; nsFmtString.h@37; nsTHashMap.h@38; nsTextFormatter.h@39; sandboxBroker.h@42

`dom/media/ipc/MFCDMParent.h` | `fc2c9a3f35b82a402b6ad39e3d2d3a68c1d8452b` | 10094 bytes | source | UTF-8 | mode 100644
Declarations: mozilla@22; MFCDMProxy@24; MFCDMParent@35; Id@54; ReadinessMonitor@60; IsHardwareDRM@64; class@157; Mutex@192; MFCDMService@244
Dependencies: wrl.h@8; MFCDMExtra.h@10; MFCDMSession.h@11; MFPMPHostWrapper.h@12; MFProtectedPathReadinessMonitor.h@13; RemoteMediaManagerParent.h@14; mozilla/EventTargetAndLockCapability.h@15; mozilla/Maybe.h@16; mozilla/MozPromise.h@17; mozilla/PMFCDMParent.h@18; mozilla/RefPtr.h@19; mozilla/StaticMutex.h@20

`dom/media/ipc/MFCDMSerializers.h` | `f320c544b6cf4ad44acf92f875b1810c29bedd30` | 2060 bytes | source | UTF-8 | mode 100644
Declarations: IPC@15; ParamTraits@18; ParamTraits@25; ParamTraits@32; ParamTraits@38; ParamTraits@43; ParamTraits@48; ParamTraits@52
Dependencies: MediaData.h@8; mozilla/KeySystemConfig.h@9; mozilla/dom/BindingIPCUtils.h@10; mozilla/dom/MediaKeyMessageEventBinding.h@11; mozilla/dom/MediaKeySessionBinding.h@12; mozilla/dom/MediaKeyStatusMapBinding.h@13

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.

## Retrieval correction

This copy preserves the source map in [60125c24-f1af-494b-a8ca-38eb76f470c1.md](60125c24-f1af-494b-a8ca-38eb76f470c1.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `93718bce0bb14f2e440f1e0bc261229acffc720b7be489483a0097e05dfc3fd8`.
