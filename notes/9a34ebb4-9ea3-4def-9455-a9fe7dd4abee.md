<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["netwerk/protocol/http/HttpChannelChild.h", "netwerk/protocol/http/HttpChannelParent.cpp", "netwerk/protocol/http/HttpChannelParent.h", "netwerk/protocol/http/HttpConnectionBase.cpp", "netwerk/protocol/http/HttpConnectionBase.h", "netwerk/protocol/http/HttpConnectionMgrChild.cpp", "netwerk/protocol/http/HttpConnectionMgrChild.h", "netwerk/protocol/http/HttpConnectionMgrParent.cpp", "netwerk/protocol/http/HttpConnectionMgrParent.h", "netwerk/protocol/http/HttpConnectionMgrShell.h", "netwerk/protocol/http/HttpConnectionUDP.cpp", "netwerk/protocol/http/HttpConnectionUDP.h", "netwerk/protocol/http/HttpInfo.cpp", "netwerk/protocol/http/HttpInfo.h", "netwerk/protocol/http/HttpLog.h", "netwerk/protocol/http/HttpTrafficAnalyzer.cpp", "netwerk/protocol/http/HttpTrafficAnalyzer.h", "netwerk/protocol/http/HttpTransactionChild.cpp", "netwerk/protocol/http/HttpTransactionChild.h", "netwerk/protocol/http/HttpTransactionParent.cpp", "netwerk/protocol/http/HttpTransactionParent.h", "netwerk/protocol/http/HttpTransactionShell.h", "netwerk/protocol/http/HttpWinUtils.cpp", "netwerk/protocol/http/HttpWinUtils.h", "netwerk/protocol/http/InterceptedHttpChannel.cpp", "netwerk/protocol/http/InterceptedHttpChannel.h", "netwerk/protocol/http/MicrosoftEntraSSOUtils.h", "netwerk/protocol/http/MockHttpAuth.cpp", "netwerk/protocol/http/MockHttpAuth.h", "netwerk/protocol/http/NetworkMarker.cpp", "netwerk/protocol/http/NetworkMarker.h", "netwerk/protocol/http/NullHttpChannel.cpp", "netwerk/protocol/http/NullHttpChannel.h", "netwerk/protocol/http/NullHttpTransaction.cpp", "netwerk/protocol/http/NullHttpTransaction.h", "netwerk/protocol/http/ObliviousHttpChannel.cpp", "netwerk/protocol/http/ObliviousHttpChannel.h", "netwerk/protocol/http/ObliviousHttpService.cpp", "netwerk/protocol/http/ObliviousHttpService.h", "netwerk/protocol/http/OpaqueResponseUtils.cpp", "netwerk/protocol/http/OpaqueResponseUtils.h", "netwerk/protocol/http/PHttpChannelParams.h", "netwerk/protocol/http/ParentChannelListener.cpp", "netwerk/protocol/http/ParentChannelListener.h", "netwerk/protocol/http/PendingTransactionInfo.cpp", "netwerk/protocol/http/PendingTransactionInfo.h", "netwerk/protocol/http/PendingTransactionQueue.cpp", "netwerk/protocol/http/PendingTransactionQueue.h", "netwerk/protocol/http/QuicSocketControl.cpp", "netwerk/protocol/http/QuicSocketControl.h", "netwerk/protocol/http/ReplacedHttpResponse.cpp", "netwerk/protocol/http/ReplacedHttpResponse.h", "netwerk/protocol/http/SpeculativeTransaction.cpp", "netwerk/protocol/http/SpeculativeTransaction.h", "netwerk/protocol/http/TLSTransportLayer.cpp", "netwerk/protocol/http/TLSTransportLayer.h", "netwerk/protocol/http/TRRServiceChannel.cpp", "netwerk/protocol/http/TRRServiceChannel.h", "netwerk/protocol/http/TimingStruct.h", "netwerk/protocol/http/TlsHandshaker.cpp", "netwerk/protocol/http/TlsHandshaker.h", "netwerk/protocol/http/WebTransportCertificateVerifier.cpp", "netwerk/protocol/http/WebTransportCertificateVerifier.h", "netwerk/protocol/http/WebTransportFlowControl.cpp", "netwerk/protocol/http/WebTransportFlowControl.h", "netwerk/protocol/http/WebTransportSessionBase.cpp", "netwerk/protocol/http/WebTransportSessionBase.h", "netwerk/protocol/http/WebTransportStreamBase.cpp", "netwerk/protocol/http/WebTransportStreamBase.h", "netwerk/protocol/http/ZeroRttHandle.cpp", "netwerk/protocol/http/ZeroRttHandle.h", "netwerk/protocol/http/binary_http/src/binary_http.h", "netwerk/protocol/http/binary_http/src/lib.rs", "netwerk/protocol/http/happy_eyeballs_glue/HappyEyeballs.cpp", "netwerk/protocol/http/happy_eyeballs_glue/HappyEyeballs.h", "netwerk/protocol/http/happy_eyeballs_glue/src/lib.rs", "netwerk/protocol/http/happy_eyeballs_glue/src/metrics.rs", "netwerk/protocol/http/happy_eyeballs_glue/src/profiler.rs", "netwerk/protocol/http/nsAHttpConnection.cpp", "netwerk/protocol/http/nsAHttpConnection.h", "netwerk/protocol/http/nsAHttpTransaction.h", "netwerk/protocol/http/nsCORSListenerProxy.cpp", "netwerk/protocol/http/nsCORSListenerProxy.h", "netwerk/protocol/http/nsHttp.cpp", "netwerk/protocol/http/nsHttp.h", "netwerk/protocol/http/nsHttpActivityDistributor.cpp", "netwerk/protocol/http/nsHttpActivityDistributor.h", "netwerk/protocol/http/nsHttpAuthCache.cpp", "netwerk/protocol/http/nsHttpAuthCache.h", "netwerk/protocol/http/nsHttpAuthManager.cpp", "netwerk/protocol/http/nsHttpAuthManager.h", "netwerk/protocol/http/nsHttpBasicAuth.cpp", "netwerk/protocol/http/nsHttpBasicAuth.h", "netwerk/protocol/http/nsHttpChannel.cpp", "netwerk/protocol/http/nsHttpChannel.h", "netwerk/protocol/http/nsHttpChannelAuthProvider.cpp", "netwerk/protocol/http/nsHttpChannelAuthProvider.h", "netwerk/protocol/http/nsHttpChunkedDecoder.cpp", "netwerk/protocol/http/nsHttpChunkedDecoder.h", "netwerk/protocol/http/nsHttpConnection.cpp", "netwerk/protocol/http/nsHttpConnection.h", "netwerk/protocol/http/nsHttpConnectionInfo.cpp", "netwerk/protocol/http/nsHttpConnectionInfo.h"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/netwerk native and TypeScript syntax map 196

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### netwerk/protocol/http/HttpChannelChild.h

Blob: `3ace414ad15ee19afa1dbf3828b53375cd2cee0c`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Mutex.h" @8
- include "mozilla/StaticPrefsBase.h" @9
- include "mozilla/extensions/StreamFilterParent.h" @10
- include "mozilla/net/ChannelEventQueue.h" @11
- include "mozilla/net/DNS.h" @12
- include "mozilla/net/HttpBaseChannel.h" @13
- include "mozilla/net/NeckoTargetHolder.h" @14
- include "mozilla/net/PHttpChannelChild.h" @15
- include "nsIAsyncVerifyRedirectCallback.h" @16
- include "nsICacheEntry.h" @17
- include "nsICacheInfoChannel.h" @18
- include "nsIChildChannel.h" @19
- include "nsIHttpChannelChild.h" @20
- include "nsIInterfaceRequestor.h" @21
- include "nsIInterfaceRequestorUtils.h" @22
- include "nsIMultiPartChannel.h" @23
- include "nsIProgressEventSink.h" @24
- include "nsIProxiedChannel.h" @25
- include "nsIResumableChannel.h" @26
- include "nsIStreamListener.h" @27
- include "nsIThreadRetargetableRequest.h" @28
- class_specifier nsIEventTarget @30-30
- class_specifier nsIInterceptedBodyCallback @31-31
- class_specifier nsISerialEventTarget @32-32
- class_specifier nsITransportSecurityInfo @33-33
- class_specifier nsInputStreamPump @34-34
- class_specifier HttpBackgroundChannelChild @41-41
- class_specifier HttpChannelChild @43-485
- function_definition GetDecompressDictionary @82-86
- function_definition SetDecompressDictionary @87-90
- function_definition SetResponseOverride @107-110
- function_definition SetResponseStatus @112-115
- function_definition GetCallStack @143-145
- function_definition AsyncCall @180-188
- enum_specifier BckChildQueueStatus @374-381
- function_definition RemoteChannelExists @438-438
- function_definition IsSuspended @491-491

### netwerk/protocol/http/HttpChannelParent.cpp

Blob: `783eec56d58e5c20878a3f65c6ea2b74a8ee0835`. Grammar: cpp. Status: contains-errors.

- include "mozilla/net/HttpChannelParent.h" @6
- include "ErrorList.h" @8
- include "HttpBackgroundChannelParent.h" @9
- include "HttpLog.h" @10
- include "ParentChannelListener.h" @11
- include "SerializedLoadContext.h" @12
- include "mozilla/BasePrincipal.h" @13
- include "mozilla/Components.h" @14
- include "mozilla/ConsoleReportCollector.h" @15
- include "mozilla/InputStreamLengthHelper.h" @16
- include "mozilla/IntegerPrintfMacros.h" @17
- include "mozilla/LoadInfo.h" @18
- include "mozilla/ProfilerLabels.h" @19
- include "mozilla/ProfilerMarkers.h" @20
- include "mozilla/StaticPrefs_network.h" @21
- include "mozilla/StoragePrincipalHelper.h" @22
- include "mozilla/dom/BrowserParent.h" @23
- include "mozilla/dom/BrowsingContext.h" @24
- include "mozilla/dom/ContentParent.h" @25
- include "mozilla/dom/ContentProcessManager.h" @26
- include "mozilla/dom/Document.h" @27
- include "mozilla/dom/Element.h" @28
- include "mozilla/dom/ServiceWorkerUtils.h" @29
- include "mozilla/dom/WindowGlobalParent.h" @30
- include "mozilla/ipc/BackgroundUtils.h" @31
- include "mozilla/ipc/IPCStreamUtils.h" @32
- include "mozilla/ipc/InputStreamUtils.h" @33
- include "mozilla/ipc/URIUtils.h" @34
- include "mozilla/net/BackgroundChannelRegistrar.h" @35
- include "mozilla/net/CacheEntryWriteHandleParent.h" @36
- include "mozilla/net/ChannelEventQueue.h" @37
- include "mozilla/net/CookieServiceParent.h" @38
- include "mozilla/net/EarlyHintRegistrar.h" @39
- include "mozilla/net/ExecuteIfOnMainThreadEventTarget.h" @40
- include "mozilla/net/NeckoParent.h" @41
- include "mozilla/net/RedirectChannelRegistrar.h" @42
- include "nsCORSListenerProxy.h" @43
- include "nsDebug.h" @44
- include "nsHttpHandler.h" @45
- include "nsIAuthPrompt.h" @46
- include "nsIAuthPrompt2.h" @47
- include "nsICacheInfoChannel.h" @48
- include "nsIClassOfService.h" @49
- include "nsIIPCSerializableInputStream.h" @50
- include "nsIMultiPartChannel.h" @51
- include "nsIPrompt.h" @52
- include "nsIPromptFactory.h" @53
- include "nsISecureBrowserUI.h" @54
- include "nsISerializable.h" @55
- include "nsISupportsPriority.h" @56
- include "nsIViewSourceChannel.h" @57
- include "nsIWindowWatcher.h" @58
- include "nsNetCID.h" @59
- include "nsNetUtil.h" @60
- include "nsQueryObject.h" @61
- include "nsSerializationHelper.h" @62
- include "nsStreamUtils.h" @63
- include "nsStringStream.h" @64
- include "nsThreadUtils.h" @65
- struct_specifier ChannelMarker @71-94
- function_definition StreamJSONMarkerData @86-93
- function_definition HttpChannelParent @104-133
- function_definition ~HttpChannelParent @135-145
- function_definition ActorDestroy @147-153
- function_definition Init @155-189
- function_definition TryInvokeAsyncOpen @191-211
- function_definition GetContentParentId @213-215
- function_definition OnBackgroundParentReady @217-227
- function_definition OnBackgroundParentDestroyed @229-246
- function_definition CleanupBackgroundChannel @248-292
- function_definition OtherPid @294-299
- function_definition HttpChannelParent::GetInterface @320-363
- function_definition AsyncOpenFailed @369-381
- function_definition InvokeAsyncOpen @383-397
- function_definition InvokeEarlyHintPreloader @399-419
- function_definition DoAsyncOpen @421-674
- function_definition WaitForBgParent @676-696
- function_definition ConnectChannel @698-755
- function_definition RecvSetPriority @757-772
- function_definition RecvSetClassOfService @774-780
- function_definition RecvSuspend @782-789
- function_definition RecvResume @791-798
- function_definition RecvCancel @800-847
- function_definition RecvRedirect2Verify @849-996
- function_definition ContinueVerification @999-1042
- function_definition ContinueRedirect2Verify @1044-1064
- function_definition RecvDocumentChannelCleanup @1066-1074
- function_definition RecvRemoveCorsPreflightCacheEntry @1076-1090
- function_definition GetTimingAttributes @1096-1147
- function_definition OnStartRequest @1149-1402
- function_definition OnStopRequest @1404-1492
- function_definition OnAfterLastPart @1498-1517
- function_definition OnDataAvailable @1523-1586
- function_definition GetEventTargetForBgParentWait @1594-1601
- function_definition NeedFlowControl @1603-1628
- function_definition RecvBytesRead @1630-1649
- function_definition RecvOpenOriginalCacheInputStream @1651-1667
- function_definition OnProgress @1673-1705
- function_definition OnStatus @1707-1739
- function_definition SetParentListener @1745-1756
- function_definition SetClassifierMatchedInfo @1758-1767
- function_definition SetClassifierMatchedTrackingInfo @1769-1778
- function_definition NotifyClassificationFlags @1780-1792
- function_definition Delete @1794-1799
- function_definition GetRemoteType @1801-1810
- function_definition IsRedirectDueToAuthRetry @1812-1814
- function_definition StartRedirect @1820-1975
- function_definition CompleteRedirect @1977-2000
- function_definition RecordAltDataPrincipal @2007-2024
- function_definition CacheEntryWriteHandleParent @2026-2028
- function_definition OpenAlternativeOutputStream @2030-2045
- function_definition AllocCacheEntryWriteHandle @2047-2049
- function_definition OpenAlternativeOutputStream @2051-2066
- function_definition SecurityInfo @2068-2075
- function_definition DoSendDeleteSelf @2077-2084
- function_definition RecvDeletingChannel @2086-2094
- function_definition ReportSecurityMessage @2100-2107
- function_definition ReadyToVerify @2113-2122
- function_definition DoSendSetPriority @2124-2128
- function_definition DoSendReportLNAToConsole @2130-2138
- function_definition LogBlockedCORSRequest @2140-2149
- function_definition LogMimeTypeMismatch @2151-2161
- function_definition AsyncOnChannelRedirect @2167-2177
- function_definition OnRedirectResult @2183-2248
- function_definition OverrideReferrerInfoDuringBeginConnect @2250-2256
- function_definition AttachStreamFilter @2258-2275
- function_definition DetachStreamFilters @2277-2289
- function_definition SetHttpChannelFromEarlyHintPreloader @2291-2300
- function_definition SetCookieChanges @2302-2318

### netwerk/protocol/http/HttpChannelParent.h

Blob: `d1e62b01abaa4a1384300cf3755f5e2f97d423ad`. Grammar: cpp. Status: contains-errors.

- include "HttpBaseChannel.h" @8
- include "mozilla/MozPromise.h" @9
- include "mozilla/dom/ipc/IdType.h" @10
- include "mozilla/net/NeckoCommon.h" @11
- include "mozilla/net/NeckoParent.h" @12
- include "mozilla/net/PHttpChannelParent.h" @13
- include "nsHttp.h" @14
- include "nsHttpChannel.h" @15
- include "nsIChannelEventSink.h" @16
- include "nsIMultiPartChannel.h" @17
- include "nsIParentRedirectingChannel.h" @18
- include "nsIProgressEventSink.h" @19
- include "nsIRedirectResultListener.h" @20
- include "nsIURI.h" @21
- class_specifier nsICacheEntry @23-23
- class_specifier BrowserParent @31-31
- class_specifier HttpBackgroundChannelParent @36-36
- class_specifier ParentChannelListener @37-37
- class_specifier ChannelEventQueue @38-38
- class_specifier CacheEntryWriteHandleParent @39-39
- class_specifier HttpChannelParent @41-334
- function_definition SetApplyConversion @74-78

### netwerk/protocol/http/HttpConnectionBase.cpp

Blob: `47c1e77a8e38aa27b1c142cc8b01df1029b043f8`. Grammar: cpp. Status: syntax-clean.

- include "HttpLog.h" @6
- include "ConnectionEntry.h" @18
- include "HttpConnectionBase.h" @19
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @20
- include "nsHttpHandler.h" @21
- include "nsHttpTransaction.h" @22
- include "nsIClassOfService.h" @23
- include "nsIOService.h" @24
- include "nsISocketTransport.h" @25
- include "xpcpublic.h" @26
- function_definition HttpConnectionBase @35-37
- function_definition BootstrapTimings @39-41
- function_definition SetDnsBootstrapTimings @43-47
- function_definition SetConnectBootstrapTimings @49-62
- function_definition HandOffConnectPhase @64-89
- function_definition SetSecurityCallbacks @91-100
- function_definition SetTrafficCategory @102-109
- function_definition ChangeConnectionState @111-121
- function_definition RecordConnectionCloseTelemetry @123-125
- function_definition RecordConnectionAddressType @127-154
- function_definition ChangeState @156-160
- function_definition CheckTunnelIsNeeded @162-188
- function_definition SetOwner @190-192
- function_definition OwnerEntry @194-196

### netwerk/protocol/http/HttpConnectionBase.h

Blob: `e3fa965df6408c821520202ad388970a40cb8750`. Grammar: cpp. Status: contains-errors.

- include "ARefBase.h" @8
- include "HttpTrafficAnalyzer.h" @9
- include "TimingStruct.h" @10
- include "mozilla/Mutex.h" @11
- include "mozilla/WeakPtr.h" @12
- include "mozilla/net/DNS.h" @13
- include "nsAHttpTransaction.h" @14
- include "nsCOMPtr.h" @15
- include "nsHttpConnectionInfo.h" @16
- include "nsHttpResponseHead.h" @17
- include "nsIAsyncInputStream.h" @18
- include "nsIAsyncOutputStream.h" @19
- include "nsIInterfaceRequestor.h" @20
- include "nsITimer.h" @21
- include "nsProxyRelease.h" @22
- include "prinrval.h" @23
- class_specifier nsISocketTransport @25-25
- class_specifier nsITLSSocketControl @26-26
- class_specifier ConnectionEntry @31-31
- class_specifier nsHttpHandler @32-32
- class_specifier ASpdySession @33-33
- class_specifier WebTransportSessionBase @34-34
- enum_specifier ConnectionState @36-43
- enum_specifier ConnectionExperienceState @45-50
- class_specifier HttpConnectionBase @65-264
- function_definition ConnectionInfo @86-86
- function_definition GetWebTransportSession @100-103
- function_definition UsingSpdy @105-105
- function_definition UsingHttp3 @106-106
- function_definition SetTransactionCaps @108-108
- function_definition IsExperienced @114-114
- function_definition NoClientCertAuth @122-122
- function_definition GetExtendedCONNECTSupport @125-127
- function_definition GetConnectionInfo @129-131
- function_definition GetCallbacks @143-146
- function_definition InitCallbacks @148-152
- function_definition Rtt @170-170
- function_definition Transport @173-173
- function_definition CloseReason @184-184
- function_definition SetCloseReason @185-189
- function_definition IsProxyConnectInProgress @194-194
- function_definition (anonymous) @200-202
- function_definition SetIsRacing @207-207
- function_definition IsRacing @208-208
- function_definition SetDontExclude @209-209
- enum_specifier HttpConnectionState @251-255
- function_definition TunnelSetupInProgress @257-257
- function_definition SetTunnelSetupDone @258-258
- function_definition SetupProxyConnectStream @259-259

### netwerk/protocol/http/HttpConnectionMgrChild.cpp

Blob: `c83a6ac2ad3a80615d20f3775d73aaf8ff9fb8bb`. Grammar: cpp. Status: contains-errors.

- include "HttpConnectionMgrChild.h" @6
- include "AltSvcTransactionChild.h" @8
- include "EventTokenBucket.h" @9
- include "HttpLog.h" @10
- include "HttpTransactionChild.h" @11
- include "mozilla/net/WebSocketConnectionChild.h" @12
- include "nsHttpConnectionInfo.h" @13
- include "nsHttpConnectionMgr.h" @14
- include "nsHttpHandler.h" @15
- include "nsISpeculativeConnect.h" @16
- function_definition HttpConnectionMgrChild @20-23
- function_definition ~HttpConnectionMgrChild @25-27
- function_definition ActorDestroy @29-31
- function_definition RecvDoShiftReloadConnectionCleanupWithConnInfo @33-47
- function_definition RecvUpdateCurrentBrowserId @49-53
- function_definition ToRealHttpTransaction @55-61
- function_definition RecvAddTransaction @63-67
- function_definition RecvAddTransactionWithStickyConn @69-77
- function_definition RecvRescheduleTransaction @79-84
- function_definition RecvUpdateClassOfServiceOnTransaction @86-92
- function_definition RecvCancelTransaction @94-98
- class_specifier SpeculativeConnectionOverrider @102-118
- function_definition SpeculativeConnectionOverrider @110-112
- function_definition ~SpeculativeConnectionOverrider @115-115
- function_definition GetInterface @123-129
- function_definition GetIgnoreIdle @131-135
- function_definition GetParallelSpeculativeConnectLimit @137-142
- function_definition GetAllow1918 @144-148
- function_definition RecvSpeculativeConnect @152-170
- function_definition RecvStartWebSocketConnection @172-181

### netwerk/protocol/http/HttpConnectionMgrChild.h

Blob: `f61675ec13b51157fde0ac7ef6fc6e027b881f03`. Grammar: cpp. Status: contains-errors.

- include "mozilla/RefPtr.h" @8
- include "mozilla/net/PHttpConnectionMgrChild.h" @9
- class_specifier nsHttpConnectionMgr @13-13
- class_specifier HttpConnectionMgrChild @15-47

### netwerk/protocol/http/HttpConnectionMgrParent.cpp

Blob: `bed055802d108f3cef7a0c59d28400b667697409`. Grammar: cpp. Status: contains-errors.

- include "HttpConnectionMgrParent.h" @6
- include "AltSvcTransactionParent.h" @8
- include "HttpLog.h" @9
- include "mozilla/net/HttpTransactionParent.h" @10
- include "mozilla/net/WebSocketConnectionParent.h" @11
- include "nsHttpConnectionInfo.h" @12
- include "nsIHttpChannelInternal.h" @13
- include "nsIInterfaceRequestor.h" @14
- include "nsIInterfaceRequestorUtils.h" @15
- include "nsIOService.h" @16
- include "nsISpeculativeConnect.h" @17
- include "nsQueryObject.h" @18
- function_definition AddHttpUpgradeListenerToMap @28-34
- function_definition RemoveHttpUpgradeListenerFromMap @37-40
- function_definition GetAndRemoveHttpUpgradeListener @43-47
- function_definition Init @51-61
- function_definition Shutdown @63-75
- function_definition UpdateRequestTokenBucket @77-82
- function_definition DoShiftReloadConnectionCleanup @84-88
- function_definition DoShiftReloadConnectionCleanupWithConnInfo @90-312
- function_definition (anonymous) @100-102
- function_definition PruneDeadConnections @107-111
- function_definition AbortAndCloseAllConnections @113-116
- function_definition UpdateParam @118-123
- function_definition PrintDiagnostics @125-128
- function_definition UpdateCurrentBrowserId @130-135
- function_definition AddTransaction @137-148
- function_definition AddTransactionWithStickyConn @150-163
- function_definition RescheduleTransaction @165-176
- function_definition UpdateClassOfServiceOnTransaction @178-188
- function_definition CancelTransaction @190-201
- function_definition ReclaimConnection @203-206
- function_definition ProcessPendingQ @208-211
- function_definition ProcessPendingQ @213-216
- function_definition GetSocketThreadTarget @218-221
- function_definition SpeculativeConnect @223-256
- function_definition VerifyTraffic @258-262
- function_definition ExcludeHttp2 @264-266
- function_definition ExcludeHttp3 @268-270
- function_definition ClearConnectionHistory @272-276
- function_definition CompleteUpgrade @278-302
- function_definition AsHttpConnectionMgr @304-306
- function_definition AsHttpConnectionMgrParent @308-310

### netwerk/protocol/http/HttpConnectionMgrParent.h

Blob: `c264f8864e487ab720bbee4f77942008ab747e42`. Grammar: cpp. Status: contains-errors.

- include "HttpConnectionMgrShell.h" @8
- include "mozilla/StaticMutex.h" @9
- include "mozilla/net/PHttpConnectionMgrParent.h" @10
- class_specifier HttpConnectionMgrParent @16-38
- function_definition HttpConnectionMgrParent @22-22
- function_definition ~HttpConnectionMgrParent @31-31

### netwerk/protocol/http/HttpConnectionMgrShell.h

Blob: `0644ac2a5f632433b9edb99ed0b0d18c6c82a763`. Grammar: cpp. Status: contains-errors.

- include "nsISupports.h" @8
- class_specifier nsIEventTarget @10-10
- class_specifier nsIHttpUpgradeListener @11-11
- class_specifier nsIInterfaceRequestor @12-12
- class_specifier ARefBase @16-16
- class_specifier EventTokenBucket @17-17
- class_specifier HttpTransactionShell @18-18
- class_specifier nsHttpConnectionInfo @19-19
- class_specifier HttpConnectionBase @20-20
- class_specifier nsHttpConnectionMgr @21-21
- class_specifier HttpConnectionMgrParent @22-22
- class_specifier SpeculativeTransaction @23-23
- class_specifier ClassOfService @24-24
- class_specifier HttpConnectionMgrShell @34-167
- enum_specifier nsParamName @38-52

### netwerk/protocol/http/HttpConnectionUDP.cpp

Blob: `db77675dde60519f368e358f524da8fa0344d666`. Grammar: cpp. Status: contains-errors.

- include "HttpLog.h" @6
- include "ASpdySession.h" @18
- include "ConnectionHandle.h" @19
- include "Http3Session.h" @20
- include "HttpConnectionUDP.h" @21
- include "mozilla/StaticPrefs_network.h" @22
- include "mozilla/glean/NetwerkMetrics.h" @23
- include "nsComponentManagerUtils.h" @24
- include "nsHttpConnectionMgr.h" @25
- include "nsHttpHandler.h" @26
- include "nsHttpTransaction.h" @27
- include "nsIDNSRecord.h" @28
- include "nsIHttpChannelInternal.h" @29
- include "nsINetAddr.h" @30
- include "nsISocketProvider.h" @31
- include "nsNetAddr.h" @32
- include "nsSocketTransportService2.h" @33
- include "nsStringStream.h" @34
- include "nsThreadUtils.h" @35
- class_specifier ConnectUDPTransaction @44-132
- function_definition ConnectUDPTransaction @48-52
- function_definition SetConnection @54-54
- function_definition Connection @55-55
- function_definition GetSecurityCallbacks @56-58
- function_definition OnTransportStatus @59-62
- function_definition IsDone @63-63
- function_definition Status @64-64
- function_definition Caps @65-65
- function_definition ReadRequestSegment @67-73
- function_definition ReadSegments @75-88
- function_definition WriteSegments @89-100
- function_definition Close @101-106
- function_definition ConnectionInfo @107-109
- function_definition SetProxyConnectFailed @110-112
- function_definition RequestHead @113-115
- function_definition Http1xTransactionCount @116-116
- function_definition TakeSubTransactions @117-120
- function_definition ~ConnectUDPTransaction @123-125
- class_specifier Http3ConnectTransaction @143-181
- function_definition Http3ConnectTransaction @145-150
- function_definition Caps @152-152
- function_definition ConnectionInfo @153-153
- function_definition OnTransportStatus @155-156
- function_definition ReadSegments @158-163
- function_definition WriteSegments @164-169
- function_definition Close @171-171
- function_definition RequestHead @172-172
- function_definition ~Http3ConnectTransaction @175-177
- function_definition HttpConnectionUDP @187-189
- function_definition ~HttpConnectionUDP @191-203
- function_definition RekeyAfterHttp3OnlyHandOff @205-226
- function_definition Init @228-282
- function_definition InitWithSocket @284-300
- function_definition InitCommon @302-402
- function_definition Activate @405-534
- function_definition OnConnected @536-580
- function_definition CreateProxyConnectStream @582-624
- function_definition CreateTunnelStream @626-665
- function_definition Close @667-709
- function_definition DontReuse @711-718
- function_definition TestJoinConnection @720-727
- function_definition JoinConnection @729-736
- function_definition CanReuse @738-755
- function_definition IsConnectedAndUnusable @757-764
- function_definition CanDirectlyActivate @766-775
- function_definition OnHeadersAvailable @781-821
- function_definition HandleTunnelResponse @823-864
- function_definition ResetTransaction @866-909
- function_definition IsReused @911-911
- function_definition TakeTransport @913-917
- function_definition GetTLSSocketControl @919-930
- function_definition PushBack @932-936
- class_specifier HttpConnectionUDPForceIO @938-966
- function_definition HttpConnectionUDPForceIO @943-946
- function_definition Run @948-959
- function_definition ~HttpConnectionUDPForceIO @962-962
- function_definition GetPriority @971-980
- function_definition ResumeSend @982-998
- function_definition ResumeRecv @1000-1000
- function_definition ForceSendIO @1002-1008
- function_definition MaybeForceSendIO @1010-1028
- function_definition ForceRecv @1031-1036
- function_definition ForceSend @1039-1044
- function_definition Version @1046-1046
- function_definition LastWriteTime @1048-1050
- function_definition CloseTransaction @1056-1115
- function_definition OnQuicTimeoutExpired @1117-1130
- function_definition NotifyDataRead @1147-1149
- function_definition NotifyDataWrite @1151-1153
- function_definition RecvData @1156-1172
- function_definition SendData @1175-1191
- function_definition GetInterface @1198-1214
- function_definition SetEvent @1216-1235
- function_definition LastTransactionExpectedNoContent @1237-1239
- function_definition SetLastTransactionExpectedNoContent @1241-1243
- function_definition IsPersistent @1245-1245
- function_definition Transaction @1247-1247
- function_definition BytesWritten @1249-1254
- function_definition OnPacketReceived @1256-1259
- function_definition OnStopListening @1261-1267
- function_definition GetSelfAddr @1269-1274
- function_definition GetPeerAddr @1276-1281
- function_definition ResolvedByTRR @1283-1283
- function_definition EffectiveTRRMode @1285-1287
- function_definition TRRSkipReason @1289-1289
- function_definition GetStats @1291-1296
- function_definition SetDontExclude @1298-1302

### netwerk/protocol/http/HttpConnectionUDP.h

Blob: `b401912ab9a59e2046ff2ebacc6e69509da58edc`. Grammar: cpp. Status: contains-errors.

- include "ARefBase.h" @8
- include "Http3Session.h" @9
- include "HttpConnectionBase.h" @10
- include "HttpTrafficAnalyzer.h" @11
- include "TimingStruct.h" @12
- include "mozilla/Mutex.h" @13
- include "nsAHttpTransaction.h" @14
- include "nsCOMPtr.h" @15
- include "nsHttpConnectionInfo.h" @16
- include "nsHttpResponseHead.h" @17
- include "nsIAsyncInputStream.h" @18
- include "nsIAsyncOutputStream.h" @19
- include "nsIInterfaceRequestor.h" @20
- include "nsISupportsPriority.h" @21
- include "nsITimer.h" @22
- include "nsProxyRelease.h" @23
- include "prinrval.h" @24
- class_specifier nsIDNSRecord @26-26
- class_specifier nsISocketTransport @27-27
- class_specifier nsITLSSocketControl @28-28
- class_specifier nsHttpHandler @33-33
- class_specifier ASpdySession @34-34
- class_specifier HttpConnectionUDP @47-169
- function_definition UsingHttp3 @77-77
- function_definition GetEchConfigUsed @88-88

### netwerk/protocol/http/HttpInfo.cpp

Blob: `f9d4f22679f1862a4b1c64b04eebbd18acbd1724`. Grammar: cpp. Status: syntax-clean.

- include "HttpInfo.h" @6
- include "HttpLog.h" @8
- include "nsHttpConnectionMgr.h" @9
- include "nsHttpHandler.h" @10
- function_definition net::HttpInfo::GetHttpConnectionData @12-17
- function_definition net::HttpInfo::GetHttp3ConnectionStatsData @19-24

### netwerk/protocol/http/HttpInfo.h

Blob: `2d50481fc915a8c2d01ac988bb12c3f3bff97655`. Grammar: cpp. Status: syntax-clean.

- include "nsTArrayForwardDeclare.h" @8
- struct_specifier HttpRetParams @13-13
- struct_specifier Http3ConnectionStatsParams @14-14
- class_specifier HttpInfo @16-22

### netwerk/protocol/http/HttpLog.h

Blob: `ed5571944d20f6a40eabdf6003bb75a680856d8d`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/net/NeckoChild.h" @18

### netwerk/protocol/http/HttpTrafficAnalyzer.cpp

Blob: `bffc2b7a8e67d7fec7c7621fea36ea7735aa6aad`. Grammar: cpp. Status: contains-errors.

- include "HttpTrafficAnalyzer.h" @5
- include "HttpLog.h" @7
- include "mozilla/StaticPrefs_network.h" @8
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @9
- include "nsSocketTransportService2.h" @10
- function_definition CreateTrafficCategory @64-170
- function_definition IncrementHttpTransaction @172-183
- function_definition IncrementHttpConnection @185-195
- function_definition IncrementHttpConnection @197-236
- function_definition AccumulateHttpTransferredSize @241-257

### netwerk/protocol/http/HttpTrafficAnalyzer.h

Blob: `4dce608b30eff33c4deb0a26834c1d859e2a2cdf`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @8
- include "nsTArrayForwardDeclare.h" @10
- enum_specifier HttpTrafficCategory @111-112
- class_specifier HttpTrafficAnalyzer @116-140
- enum_specifier ClassOfService @118-122
- enum_specifier TrackingClassification @124-129

### netwerk/protocol/http/HttpTransactionChild.cpp

Blob: `110766cd56ceb99dc2e6d773e1eaa1359a941771`. Grammar: cpp. Status: contains-errors.

- include "HttpTransactionChild.h" @6
- include "HttpLog.h" @8
- include "OpaqueResponseUtils.h" @9
- include "mozilla/ScopeExit.h" @10
- include "mozilla/StaticPrefs_network.h" @11
- include "mozilla/ipc/IPCStreamUtils.h" @12
- include "mozilla/net/BackgroundDataBridgeParent.h" @13
- include "mozilla/net/ChannelEventQueue.h" @14
- include "mozilla/net/InputChannelThrottleQueueChild.h" @15
- include "mozilla/net/SocketProcessChild.h" @16
- include "nsHttpHandler.h" @17
- include "nsHttpResponseHead.h" @18
- include "nsHttpTransaction.h" @19
- include "nsIRequestContext.h" @20
- include "nsISocketTransport.h" @21
- include "nsITransportSecurityInfo.h" @22
- include "nsInputStreamPump.h" @23
- include "nsNetUtil.h" @24
- include "nsProxyInfo.h" @25
- include "nsProxyRelease.h" @26
- include "nsQueryObject.h" @27
- include "nsSerializationHelper.h" @28
- function_definition HttpTransactionChild @40-42
- function_definition ~HttpTransactionChild @44-46
- function_definition CreateRequestContext @48-63
- function_definition InitInternal @65-105
- function_definition RecvCancelPump @107-112
- function_definition CancelInternal @114-122
- function_definition RecvSuspendPump @124-131
- function_definition RecvResumePump @133-140
- function_definition RecvInit @142-185
- function_definition RecvSetDNSWasRefreshed @187-193
- function_definition RecvDontReuseConnection @195-201
- function_definition RecvSetH2WSConnRefTaken @203-209
- function_definition ActorDestroy @211-215
- function_definition GetHttpTransaction @217-219
- function_definition OnDataAvailable @225-308
- function_definition ToTimingStructArgs @310-323
- function_definition GetDataForSniffer @329-333
- function_definition CanSendODAToContentProcessDirectly @335-383
- function_definition OnStartRequest @385-501
- function_definition GetTimingAttributes @503-524
- function_definition OnStopRequest @526-582
- function_definition OnTransportStatus @588-629
- function_definition SetThrottleQueue @635-638
- function_definition GetThrottleQueue @640-646
- function_definition CheckListenerChain @651-655
- function_definition OnDataFinished @657-658
- function_definition EarlyHint @660-669

### netwerk/protocol/http/HttpTransactionChild.h

Blob: `fb962625ab14e8def8e1b17e0d263d3fa69217ed`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "mozilla/net/HttpTrafficAnalyzer.h" @9
- include "mozilla/net/NeckoChannelParams.h" @10
- include "mozilla/net/PHttpTransactionChild.h" @11
- include "nsHttpRequestHead.h" @12
- include "nsIEarlyHintObserver.h" @13
- include "nsIRequest.h" @14
- include "nsIStreamListener.h" @15
- include "nsIThreadRetargetableStreamListener.h" @16
- include "nsIThrottledInputChannel.h" @17
- include "nsITransport.h" @18
- class_specifier nsInputStreamPump @20-20
- class_specifier BackgroundDataBridgeParent @24-24
- class_specifier InputChannelThrottleQueueChild @25-25
- class_specifier nsHttpConnectionInfo @26-26
- class_specifier nsHttpTransaction @27-27
- class_specifier nsProxyInfo @28-28
- class_specifier HttpTransactionChild @34-122
- function_definition ToSupports @126-128

### netwerk/protocol/http/HttpTransactionParent.cpp

Blob: `612a4391e117cf1c840d7af3302c364c36c58bab`. Grammar: cpp. Status: contains-errors.

- include "HttpTransactionParent.h" @6
- include "HttpLog.h" @8
- include "HttpTrafficAnalyzer.h" @9
- include "mozilla/ipc/IPCStreamUtils.h" @10
- include "mozilla/net/ChannelEventQueue.h" @11
- include "mozilla/net/InputChannelThrottleQueueParent.h" @12
- include "mozilla/net/SocketProcessParent.h" @13
- include "nsHttpHandler.h" @14
- include "nsIRequestContext.h" @15
- include "nsIThreadRetargetableStreamListener.h" @16
- include "nsITransportSecurityInfo.h" @17
- include "nsNetUtil.h" @18
- include "nsProxyRelease.h" @19
- include "nsQueryObject.h" @20
- include "nsSerializationHelper.h" @21
- include "nsStreamUtils.h" @22
- include "nsStringStream.h" @23
- function_definition Release @35-73
- function_definition HttpTransactionParent @79-83
- function_definition ~HttpTransactionParent @85-88
- function_definition Init @95-169
- function_definition AsyncRead @171-178
- function_definition TakeResponseHeadAndConnInfo @180-193
- function_definition TakeResponseTrailers @195-201
- function_definition SetSniffedTypeToChannel @203-209
- function_definition GetDeliveryTarget @211-221
- function_definition GetODATarget @223-234
- function_definition RetargetDeliveryTo @236-270
- function_definition SetDNSWasRefreshed @272-275
- function_definition GetNetworkAddresses @277-287
- function_definition GetTargetIPAddressSpace @289-291
- function_definition HasStickyConnection @293-295
- function_definition GetDomainLookupStart @297-299
- function_definition GetDomainLookupEnd @301-303
- function_definition GetConnectStart @305-307
- function_definition GetTcpConnectEnd @309-311
- function_definition GetSecureConnectionStart @313-315
- function_definition GetConnectEnd @317-319
- function_definition GetRequestStart @321-323
- function_definition GetResponseStart @325-327
- function_definition GetFirstInterimResponseStart @329-331
- function_definition GetFinalResponseHeadersStart @333-335
- function_definition GetResponseEnd @337-339
- function_definition Timings @341-341
- function_definition ResponseIsComplete @343-343
- function_definition GetTransferSize @345-345
- function_definition GetRequestSize @347-347
- function_definition IsHttp3Used @349-349
- function_definition DataSentToChildProcess @351-353
- function_definition SecurityInfo @355-358
- function_definition ProxyConnectFailed @360-360
- function_definition TakeRestartedState @362-366
- function_definition HTTPSSVCReceivedStage @368-370
- function_definition DontReuseConnection @372-375
- function_definition SetH2WSConnRefTaken @377-380
- function_definition SetSecurityCallbacks @382-386
- function_definition SetDomainLookupStart @388-392
- function_definition SetDomainLookupEnd @393-397
- function_definition AsHttpTransaction @399-401
- function_definition AsHttpTransactionParent @403-405
- function_definition GetProxyConnectResponseCode @407-410
- function_definition GetProxyConnectResponseHead @412-415
- function_definition Http2Disabled @417-419
- function_definition Http3Disabled @421-423
- function_definition GetConnInfo @425-429
- function_definition GetNeckoTarget @431-434
- function_definition RecvOnStartRequest @436-469
- function_definition (anonymous) @459-467
- function_definition TimingStructArgsToTimingsStruct @471-488
- function_definition DoOnStartRequest @490-554
- function_definition RecvOnTransportStatus @556-570
- function_definition RecvOnDataAvailable @572-597
- function_definition DoOnDataAvailable @599-624
- function_definition CancelOnMainThread @627-644
- function_definition RecvOnStopRequest @646-674
- function_definition DoOnStopRequest @676-713
- function_definition RecvOnInitFailed @715-722
- function_definition RecvEarlyHint @724-739
- function_definition GetName @745-749
- function_definition IsPending @751-755
- function_definition GetStatus @757-761
- function_definition SetCanceledReason @763-766
- function_definition GetCanceledReason @768-770
- function_definition CancelWithReason @772-775
- function_definition Cancel @777-809
- function_definition DoNotifyListener @811-828
- function_definition ContinueDoNotifyListener @830-842
- function_definition Suspend @844-854
- function_definition Resume @856-883
- function_definition GetLoadGroup @885-889
- function_definition SetLoadGroup @891-895
- function_definition GetLoadFlags @897-901
- function_definition SetLoadFlags @903-907
- function_definition GetTRRMode @909-913
- function_definition SetTRRMode @915-919
- function_definition ActorDestroy @921-932
- function_definition HandleAsyncAbort @934-948
- function_definition GetSupportsHTTP3 @950-950
- function_definition SetIsForWebTransport @952-954
- function_definition GetPendingTime @956-958

### netwerk/protocol/http/HttpTransactionParent.h

Blob: `20f2c6f636477b479598d48188d298d32d93a21c`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "mozilla/Mutex.h" @9
- include "mozilla/net/HttpTransactionShell.h" @10
- include "mozilla/net/NeckoChannelParams.h" @11
- include "mozilla/net/PHttpTransactionParent.h" @12
- include "nsCOMPtr.h" @13
- include "nsHttp.h" @14
- include "nsIRequest.h" @15
- include "nsIThreadRetargetableRequest.h" @16
- include "nsITransport.h" @17
- include "nsITransportSecurityInfo.h" @18
- class_specifier ChannelEventQueue @22-22
- class_specifier nsHttpConnectionInfo @23-23
- class_specifier HttpTransactionParent @30-188
- function_definition SetRequestBodyIsStreaming @43-45
- function_definition SetRedirectTimestamp @88-91
- function_definition GetOnStartRequestStartTime @93-95
- function_definition GetDataAvailableStartTime @96-98
- function_definition GetOnStopRequestStartTime @99-101

### netwerk/protocol/http/HttpTransactionShell.h

Blob: `bf6a8498c5308f5a4eb412ef5c3d83060d17454d`. Grammar: cpp. Status: contains-errors.

- include <functional> @8
- include "TimingStruct.h" @10
- include "mozilla/RefPtr.h" @11
- include "mozilla/UniquePtr.h" @12
- include "nsHttpRequestHead.h" @13
- include "nsIClassOfService.h" @14
- include "nsIEarlyHintObserver.h" @15
- include "nsILoadInfo.h" @16
- include "nsISupports.h" @17
- include "nsITRRSkipReason.h" @18
- include "nsITransportSecurityInfo.h" @19
- include "nsInputStreamPump.h" @20
- class_specifier nsIEventTraget @22-22
- class_specifier nsIInputStream @23-23
- class_specifier nsIInterfaceRequestor @24-24
- class_specifier nsIRequest @25-25
- class_specifier nsIRequestContext @26-26
- class_specifier nsITransportEventSink @27-27
- enum_specifier HttpTrafficCategory @31-31
- class_specifier HttpTransactionParent @32-32
- class_specifier nsHttpConnectionInfo @33-33
- class_specifier nsHttpHeaderArray @34-34
- class_specifier nsHttpRequestHead @35-35
- class_specifier nsHttpTransaction @36-36
- class_specifier ProxyConnectResponseHead @37-37
- class_specifier TransactionObserverResult @38-38
- enum_specifier LNAPermission @41-45
- struct_specifier LNAPerms @47-50
- class_specifier HttpTransactionShell @60-193
- function_definition GetOnStartRequestStartTime @188-188
- function_definition GetDataAvailableStartTime @189-189
- function_definition GetOnStopRequestStartTime @190-190
- function_definition SetIsTRRTransaction @192-192

### netwerk/protocol/http/HttpWinUtils.cpp

Blob: `9cc8bf47c1cd47fe84f91d2d8b3e7ddc5b273a4e`. Grammar: cpp. Status: syntax-clean.

- include "HttpWinUtils.h" @5
- include <proofofpossessioncookieinfo.h> @7
- include "mozilla/ClearOnShutdown.h" @9
- include "nsHttpChannel.h" @10
- include "nsIURI.h" @11
- function_definition AddWindowsSSO @19-118

### netwerk/protocol/http/HttpWinUtils.h

Blob: `389c93276be094d65004c752586635677e595928`. Grammar: cpp. Status: syntax-clean.

- class_specifier nsHttpChannel @11-11

### netwerk/protocol/http/InterceptedHttpChannel.cpp

Blob: `be9bd1b1ff260317cdab5ab3bad5ecb62376b217`. Grammar: cpp. Status: contains-errors.

- include "InterceptedHttpChannel.h" @5
- include <memory> @7
- include "NetworkMarker.h" @9
- include "mozilla/Logging.h" @10
- include "mozilla/SchedulerGroup.h" @11
- include "mozilla/ScopeExit.h" @12
- include "mozilla/dom/ChannelInfo.h" @13
- include "mozilla/dom/PerformanceStorage.h" @14
- include "mozilla/glean/DomServiceworkersMetrics.h" @15
- include "nsContentSecurityManager.h" @16
- include "nsEscape.h" @17
- include "nsHttpChannel.h" @18
- include "nsIHttpHeaderVisitor.h" @19
- include "nsIRedirectResultListener.h" @20
- include "nsQueryObject.h" @21
- include "nsStreamUtils.h" @22
- include "nsStringStream.h" @23
- function_definition InterceptedHttpChannel @38-55
- function_definition ReleaseListeners @57-71
- function_definition SetupReplacementChannel @73-100
- function_definition AsyncOpenInternal @102-191
- function_definition ShouldRedirect @193-197
- function_definition FollowSyntheticRedirect @199-260
- function_definition RedirectForResponseURL @262-328
- function_definition StartPump @330-373
- function_definition OpenRedirectChannel @375-401
- function_definition MaybeCallStatusAndProgress @403-460
- function_definition MaybeCallBodyCallback @462-467
- function_definition CreateForInterception @470-480
- function_definition CreateForSynthesis @483-502
- function_definition SetCanceledReason @504-507
- function_definition GetCanceledReason @509-511
- function_definition CancelWithReason @513-517
- function_definition Cancel @519-569
- function_definition Suspend @571-579
- function_definition Resume @581-589
- function_definition GetSecurityInfo @591-597
- function_definition AsyncOpen @599-622
- function_definition LogBlockedCORSRequest @624-630
- function_definition LogMimeTypeMismatch @632-638
- function_definition GetIsAuthChannel @640-643
- function_definition SetPriority @645-649
- function_definition SetClassFlags @651-655
- function_definition ClearClassFlags @657-661
- function_definition AddClassFlags @663-667
- function_definition SetClassOfService @669-673
- function_definition SetIncremental @675-679
- function_definition ResumeAt @681-690
- function_definition DoNotifyListenerCleanup @692-695
- function_definition DoAsyncAbort @697-699
- function_definition InterceptedHttpChannel::ResetInterception @703-839
- class_specifier ResetInterceptionHeaderVisitor @703-732
- function_definition ~ResetInterceptionHeaderVisitor @706-706
- function_definition VisitHeader @708-719
- function_definition ResetInterceptionHeaderVisitor @722-725
- function_definition SynthesizeStatus @841-861
- function_definition SynthesizeHeader @863-879
- function_definition StartSynthesizedResponse @881-966
- function_definition FinishSynthesizedResponse @968-977
- function_definition CancelInterception @979-982
- function_definition GetChannel @984-989
- function_definition GetSecureUpgradedChannelURI @991-997
- function_definition SetChannelInfo @999-1003
- function_definition GetInternalContentPolicyType @1005-1012
- function_definition GetConsoleReportCollector @1014-1020
- function_definition SetFetchHandlerStart @1022-1026
- function_definition SetFetchHandlerFinish @1028-1032
- function_definition SetRemoteWorkerLaunchStart @1034-1040
- function_definition SetRemoteWorkerLaunchEnd @1042-1048
- function_definition SetLaunchServiceWorkerStart @1050-1054
- function_definition GetLaunchServiceWorkerStart @1056-1061
- function_definition SetLaunchServiceWorkerEnd @1063-1067
- function_definition GetLaunchServiceWorkerEnd @1069-1074
- function_definition GetDispatchFetchEventStart @1076-1081
- function_definition GetDispatchFetchEventEnd @1083-1088
- function_definition GetHandleFetchEventStart @1090-1095
- function_definition GetHandleFetchEventEnd @1097-1102
- function_definition GetIsReset @1104-1108
- function_definition SetReleaseHandle @1110-1114
- function_definition OnRedirectVerifyCallback @1116-1145
- function_definition OnStartRequest @1147-1197
- function_definition OnStopRequest @1199-1263
- function_definition OnDataAvailable @1265-1287
- function_definition OnDataFinished @1289-1301
- function_definition RetargetDeliveryTo @1303-1321
- function_definition GetDeliveryTarget @1323-1330
- function_definition CheckListenerChain @1332-1342
- function_definition IsFromCache @1352-1359
- function_definition HasCacheEntry @1361-1368
- function_definition GetCacheEntryId @1370-1376
- function_definition GetCacheTokenFetchCount @1378-1386
- function_definition GetCacheTokenExpirationTime @1388-1396
- function_definition SetAllowStaleCacheContent @1398-1406
- function_definition GetAllowStaleCacheContent @1408-1416
- function_definition SetForceValidateCacheContent @1418-1433
- function_definition GetForceValidateCacheContent @1434-1448
- function_definition GetPreferCacheLoadOverBypass @1450-1458
- function_definition SetPreferCacheLoadOverBypass @1460-1468
- function_definition PreferAlternativeDataType @1470-1478
- function_definition (anonymous) @1480-1483
- function_definition GetAlternativeDataType @1485-1491
- function_definition GetCacheEntryWriteHandle @1493-1500
- function_definition OpenAlternativeOutputStream @1502-1511
- function_definition GetOriginalInputStream @1513-1520
- function_definition GetAlternativeDataInputStream @1522-1529
- function_definition GetCacheKey @1531-1537
- function_definition SetCacheKey @1539-1545
- function_definition GetCacheDisposition @1547-1553
- function_definition InterceptionTimeStamps::InterceptionTimeStamps @1556-1558
- function_definition InterceptionTimeStamps::Init @1560-1576
- function_definition InterceptionTimeStamps::RecordTime @1578-1616
- function_definition InterceptionTimeStamps::RecordTime @1618-1625
- function_definition InterceptionTimeStamps::RecordTimeInternal @1627-1665
- function_definition InterceptionTimeStamps::GenKeysWithStatus @1667-1701
- function_definition InterceptionTimeStamps::SaveTimeStamps @1703-1742

### netwerk/protocol/http/InterceptedHttpChannel.h

Blob: `ab440756a6745ce3c4785f211db32173c6bd27c5`. Grammar: cpp. Status: contains-errors.

- include "HttpBaseChannel.h" @8
- include "nsIAsyncVerifyRedirectCallback.h" @9
- include "nsICacheInfoChannel.h" @10
- include "nsIInputStream.h" @11
- include "nsINetworkInterceptController.h" @12
- include "nsIThreadRetargetableRequest.h" @13
- include "nsIThreadRetargetableStreamListener.h" @14
- include "nsInputStreamPump.h" @15
- class_specifier InterceptedHttpChannel @50-331
- class_specifier InterceptionTimeStamps @104-183
- enum_specifier Status @107-117
- function_definition ~InterceptionTimeStamps @120-120
- enum_specifier Stage @161-166
- function_definition ~InterceptedHttpChannel @190-190
- function_definition SetEarlyHintObserver @286-289
- function_definition SetWebTransportSessionEventListener @291-294
- function_definition SetResponseOverride @296-299
- function_definition SetResponseStatus @301-304
- function_definition GetDecompressDictionary @322-326
- function_definition SetDecompressDictionary @327-330

### netwerk/protocol/http/MicrosoftEntraSSOUtils.h

Blob: `f092fe745ca43975ecde7093832bac8cf43082f9`. Grammar: cpp. Status: syntax-clean.

- include "ErrorList.h" @8
- include "nsHttpChannel.h" @9
- class_specifier nsHttpChannel @14-14
- class_specifier MicrosoftEntraSSOUtils @15-15

### netwerk/protocol/http/MockHttpAuth.cpp

Blob: `8657a7e7fa6592e019090e22f47fc06857bdb61f`. Grammar: cpp. Status: contains-errors.

- include "MockHttpAuth.h" @6
- include "HttpLog.h" @8
- function_definition ChallengeReceived @14-20
- function_definition GenerateCredentialsAsync @22-29
- function_definition GenerateCredentials @31-38
- function_definition GetAuthFlags @40-43

### netwerk/protocol/http/MockHttpAuth.h

Blob: `6121852b3189ad469c4e3d7de95964ef91c48b3e`. Grammar: cpp. Status: contains-errors.

- include "nsCOMPtr.h" @8
- include "nsIHttpAuthenticator.h" @9
- class_specifier MockHttpAuth @14-28
- function_definition MockHttpAuth @19-19
- function_definition Create @21-24
- function_definition ~MockHttpAuth @27-27

### netwerk/protocol/http/NetworkMarker.cpp

Blob: `88c8dd82673cf1f16f6fb2bd1a94702917c257dd`. Grammar: cpp. Status: syntax-clean.

- include "NetworkMarker.h" @5
- include "HttpBaseChannel.h" @7
- include "mozilla/ErrorNames.h" @8
- include "mozilla/Perfetto.h" @9
- include "nsHttpHandler.h" @10
- include "nsIChannelEventSink.h" @11
- include "nsIClassOfService.h" @12
- struct_specifier NetworkMarker @15-237
- function_definition StreamJSONMarkerData @20-131
- function_definition GetNetworkState @133-147
- function_definition GetCacheState @149-168
- function_definition getRedirectType @170-183
- function_definition GetClassOfService @186-236
- function_definition EmitPerfettoTrackEvent @244-401
- function_definition profiler_add_network_marker @407-463

### netwerk/protocol/http/NetworkMarker.h

Blob: `5fe902b1a3b163052772d739fb9521cb7079ba8d`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/ProfilerMarkers.h" @8
- include "nsHttp.h" @9
- include "nsICacheInfoChannel.h" @10
- include "nsIClassOfService.h" @11
- struct_specifier TimingStruct @16-16
- enum_specifier NetworkLoadType @18-23

### netwerk/protocol/http/NullHttpChannel.cpp

Blob: `e47aa31985771603e3c6dec21aacc2bcd1928763`. Grammar: cpp. Status: contains-errors.

- include "NullHttpChannel.h" @5
- include "nsContentSecurityManager.h" @7
- include "nsContentUtils.h" @8
- include "nsIScriptSecurityManager.h" @9
- include "nsIStreamListener.h" @10
- function_definition NullHttpChannel @18-22
- function_definition NullHttpChannel @24-44
- function_definition Init @46-52
- function_definition GetChannelId @58-61
- function_definition SetChannelId @63-66
- function_definition GetTopLevelContentWindowId @68-71
- function_definition SetTopLevelContentWindowId @73-76
- function_definition GetBrowserId @78-79
- function_definition SetBrowserId @81-82
- function_definition GetTransferSize @84-87
- function_definition GetRequestSize @89-92
- function_definition GetDecodedBodySize @94-97
- function_definition GetRequestMethod @99-102
- function_definition SetRequestMethod @104-107
- function_definition GetReferrerInfo @109-112
- function_definition SetReferrerInfo @114-117
- function_definition SetReferrerInfoWithoutClone @119-122
- function_definition GetRequestHeader @124-129
- function_definition SetRequestHeader @131-135
- function_definition SetNewReferrerInfo @137-142
- function_definition SetEmptyRequestHeader @144-147
- function_definition VisitRequestHeaders @149-152
- function_definition VisitNonDefaultRequestHeaders @154-157
- function_definition GetAllowSTS @159-162
- function_definition SetAllowSTS @164-167
- function_definition GetRedirectionLimit @169-172
- function_definition SetRedirectionLimit @174-177
- function_definition GetResponseStatus @179-182
- function_definition GetResponseStatusText @184-187
- function_definition GetRequestSucceeded @189-192
- function_definition GetResponseHeader @194-199
- function_definition SetResponseHeader @201-205
- function_definition VisitResponseHeaders @207-210
- function_definition GetOriginalResponseHeader @212-216
- function_definition VisitOriginalResponseHeaders @218-221
- function_definition ShouldStripRequestBodyHeader @223-227
- function_definition IsNoStoreResponse @229-232
- function_definition IsNoCacheResponse @234-237
- function_definition RedirectTo @239-242
- function_definition UpgradeToSecure @244-245
- function_definition GetRequestObserversCalled @247-250
- function_definition SetRequestObserversCalled @252-255
- function_definition GetRequestContextID @257-260
- function_definition SetRequestContextID @262-265
- function_definition GetProtocolVersion @267-270
- function_definition GetEncodedBodySize @272-275
- function_definition GetIsUserAgentHeaderOutdated @277-280
- function_definition SetIsUserAgentHeaderOutdated @282-285
- function_definition SetSource @287-288
- function_definition GetOriginalURI @294-298
- function_definition SetOriginalURI @300-304
- function_definition GetURI @306-310
- function_definition GetOwner @312-315
- function_definition SetOwner @317-320
- function_definition GetNotificationCallbacks @322-326
- function_definition SetNotificationCallbacks @328-332
- function_definition GetSecurityInfo @334-337
- function_definition GetContentType @339-342
- function_definition SetContentType @344-347
- function_definition GetContentCharset @349-352
- function_definition SetContentCharset @354-357
- function_definition GetContentLength @359-362
- function_definition SetContentLength @364-367
- function_definition Open @369-377
- function_definition AsyncOpen @379-386
- function_definition GetContentDisposition @388-391
- function_definition SetContentDisposition @393-396
- function_definition GetContentDispositionFilename @398-402
- function_definition SetContentDispositionFilename @404-408
- function_definition GetContentDispositionHeader @410-414
- function_definition GetLoadInfo @416-419
- function_definition SetLoadInfo @421-424
- function_definition GetParentProcessChannelHandle @426-430
- function_definition SetParentProcessChannelHandle @432-436
- function_definition GetName @442-443
- function_definition IsPending @445-446
- function_definition GetStatus @448-451
- function_definition SetCanceledReason @453-455
- function_definition GetCanceledReason @457-459
- function_definition CancelWithReason @461-464
- function_definition Cancel @466-467
- function_definition GetCanceled @469-472
- function_definition Suspend @474-475
- function_definition Resume @477-478
- function_definition GetLoadGroup @480-483
- function_definition SetLoadGroup @485-488
- function_definition GetLoadFlags @490-493
- function_definition GetTRRMode @495-498
- function_definition SetTRRMode @500-503
- function_definition SetLoadFlags @505-508
- function_definition GetIsDocument @510-513
- function_definition GetRedirectCount @519-522
- function_definition SetRedirectCount @524-527
- function_definition GetInternalRedirectCount @529-532
- function_definition SetInternalRedirectCount @534-537
- function_definition GetChannelCreation @539-543
- function_definition SetChannelCreation @545-552
- function_definition GetAsyncOpen @554-558
- function_definition SetAsyncOpen @560-565
- function_definition GetLaunchServiceWorkerStart @567-572
- function_definition SetLaunchServiceWorkerStart @574-577
- function_definition GetLaunchServiceWorkerEnd @579-584
- function_definition SetLaunchServiceWorkerEnd @586-589
- function_definition GetDispatchFetchEventStart @591-596
- function_definition SetDispatchFetchEventStart @598-601
- function_definition GetDispatchFetchEventEnd @603-608
- function_definition SetDispatchFetchEventEnd @610-613
- function_definition GetHandleFetchEventStart @615-620
- function_definition SetHandleFetchEventStart @622-625
- function_definition GetHandleFetchEventEnd @627-632
- function_definition SetHandleFetchEventEnd @634-637
- function_definition GetDomainLookupStart @639-643
- function_definition GetDomainLookupEnd @645-649
- function_definition GetConnectStart @651-655
- function_definition GetTcpConnectEnd @657-661
- function_definition GetSecureConnectionStart @663-668
- function_definition GetConnectEnd @670-674
- function_definition GetRequestStart @676-680
- function_definition GetResponseStart @682-686
- function_definition GetFirstInterimResponseStart @688-693
- function_definition GetFinalResponseHeadersStart @695-700
- function_definition GetResponseEnd @702-706
- function_definition GetRedirectStart @708-712
- function_definition SetRedirectStart @714-717
- function_definition GetRedirectEnd @719-723
- function_definition SetRedirectEnd @725-728
- function_definition GetInitiatorType @730-734
- function_definition SetInitiatorType @736-740
- function_definition GetAllRedirectsSameOrigin @742-746
- function_definition SetAllRedirectsSameOrigin @748-751
- function_definition GetAllRedirectsSameOriginIgnoringInternal @753-759
- function_definition SetAllRedirectsSameOriginIgnoringInternal @761-765
- function_definition GetAllRedirectsPassTimingAllowCheck @767-772
- function_definition SetAllRedirectsPassTimingAllowCheck @774-778
- function_definition BodyInfoAccessAllowedCheck @780-785
- function_definition TimingAllowCheck @787-791
- function_definition GetCacheReadStart @793-797
- function_definition GetCacheReadEnd @799-803
- function_definition GetTransactionPending @805-809
- function_definition GetIsMainDocumentChannel @811-815
- function_definition SetIsMainDocumentChannel @817-820
- function_definition LogBlockedCORSRequest @822-827
- function_definition LogMimeTypeMismatch @829-834
- function_definition SetReportResourceTiming @836-839
- function_definition GetReportResourceTiming @841-844
- function_definition GetServerTiming @846-849
- function_definition GetNativeServerTiming @851-855
- function_definition SetClassicScriptHintCharset @857-860
- function_definition GetClassicScriptHintCharset @862-865
- function_definition SetDocumentCharacterSet @867-870
- function_definition GetDocumentCharacterSet @872-875
- function_definition SetRenderBlocking @877-880
- function_definition GetRenderBlocking @882-885
- function_definition GetDecompressDictionary @887-892
- function_definition SetDecompressDictionary @894-898

### netwerk/protocol/http/NullHttpChannel.h

Blob: `4c8d1d67ba95ca1ad54f3e30212fd7509460fbd8`. Grammar: cpp. Status: contains-errors.

- include "mozilla/TimeStamp.h" @8
- include "nsCOMPtr.h" @9
- include "nsIHttpChannel.h" @10
- include "nsINullChannel.h" @11
- include "nsITimedChannel.h" @12
- include "nsIURI.h" @13
- include "nsString.h" @14
- include "prtime.h" @15
- class_specifier nsProxyInfo @20-20
- class_specifier NullHttpChannel @22-60
- function_definition ~NullHttpChannel @45-45

### netwerk/protocol/http/NullHttpTransaction.cpp

Blob: `973bb796c7615dab94a45d9a6e51f033111e2da1`. Grammar: cpp. Status: contains-errors.

- include "NullHttpTransaction.h" @6
- include "HttpLog.h" @8
- include "mozilla/Components.h" @9
- include "mozilla/net/NeckoChannelParams.h" @10
- include "nsAHttpConnection.h" @11
- include "nsHttp.h" @12
- include "nsHttpHandler.h" @13
- include "nsHttpRequestHead.h" @14
- include "nsIHttpActivityObserver.h" @15
- include "nsNetUtil.h" @16
- include "nsQueryObject.h" @17
- function_definition NullHttpTransaction @25-59
- function_definition ~NullHttpTransaction @61-64
- function_definition Claim @66-72
- function_definition Unclaim @74-74
- function_definition SetConnection @76-78
- function_definition Connection @80-82
- function_definition GetSecurityCallbacks @84-87
- function_definition OnTransportStatus @89-128
- function_definition IsDone @130-130
- function_definition Status @132-132
- function_definition Caps @134-134
- function_definition ReadSegments @136-142
- function_definition WriteSegments @144-149
- function_definition Http1xTransactionCount @151-151
- function_definition RequestHead @153-187
- function_definition TakeSubTransactions @189-192
- function_definition SetProxyConnectFailed @194-194
- function_definition Close @196-209
- function_definition ConnectionInfo @211-213

### netwerk/protocol/http/NullHttpTransaction.h

Blob: `77a6a882e95367956ada1a81f20e4b64c870cbf0`. Grammar: cpp. Status: contains-errors.

- include "TimingStruct.h" @8
- include "nsAHttpTransaction.h" @9
- class_specifier nsIHttpActivityObserver @16-16
- class_specifier nsAHttpConnection @21-21
- class_specifier nsHttpConnectionInfo @22-22
- class_specifier nsHttpRequestHead @23-23
- class_specifier NullHttpTransaction @29-81
- function_definition IsNullTransaction @43-43
- function_definition QueryNullTransaction @44-44
- function_definition ResponseTimeoutEnabled @45-45
- function_definition ResponseTimeout @46-46
- function_definition BrowserId @52-52
- function_definition Timings @54-54
- function_definition GetTcpConnectEnd @56-56
- function_definition GetSecureConnectionStart @57-59

### netwerk/protocol/http/ObliviousHttpChannel.cpp

Blob: `c00ae1e6d3bd0569b4cb4312a4c34904ce02ed80`. Grammar: cpp. Status: contains-errors.

- include "ObliviousHttpChannel.h" @6
- include "BinaryHttpRequest.h" @8
- include "HttpLog.h" @9
- include "nsIHttpHeaderVisitor.h" @10
- include "nsStringStream.h" @11
- function_definition ObliviousHttpChannel @20-32
- function_definition ~ObliviousHttpChannel @34-36
- function_definition GetTopLevelContentWindowId @42-45
- function_definition SetTopLevelContentWindowId @47-50
- function_definition GetBrowserId @52-55
- function_definition SetBrowserId @57-60
- function_definition GetTransferSize @62-65
- function_definition GetRequestSize @67-70
- function_definition GetDecodedBodySize @72-75
- function_definition GetRequestMethod @77-81
- function_definition SetRequestMethod @83-87
- function_definition GetReferrerInfo @89-92
- function_definition SetReferrerInfo @94-97
- function_definition SetReferrerInfoWithoutClone @99-103
- function_definition GetRequestHeader @105-115
- function_definition SetRequestHeader @117-135
- function_definition SetNewReferrerInfo @137-142
- function_definition SetEmptyRequestHeader @144-147
- function_definition VisitRequestHeaders @149-158
- function_definition VisitNonDefaultRequestHeaders @160-164
- function_definition GetAllowSTS @166-169
- function_definition SetAllowSTS @171-174
- function_definition GetRedirectionLimit @176-179
- function_definition SetRedirectionLimit @181-184
- function_definition GetResponseStatus @186-198
- function_definition GetResponseStatusText @200-205
- function_definition GetRequestSucceeded @207-216
- function_definition GetIsMainDocumentChannel @218-221
- function_definition SetIsMainDocumentChannel @223-226
- function_definition GetResponseHeader @228-253
- function_definition SetResponseHeader @255-261
- function_definition VisitResponseHeaders @263-287
- function_definition GetOriginalResponseHeader @289-293
- function_definition VisitOriginalResponseHeaders @295-303
- function_definition ShouldStripRequestBodyHeader @305-313
- function_definition IsNoStoreResponse @315-320
- function_definition IsNoCacheResponse @322-327
- function_definition RedirectTo @329-333
- function_definition UpgradeToSecure @335-340
- function_definition GetRequestObserversCalled @342-345
- function_definition SetRequestObserversCalled @347-350
- function_definition GetRequestContextID @352-355
- function_definition SetRequestContextID @357-360
- function_definition GetIsUserAgentHeaderOutdated @362-365
- function_definition SetIsUserAgentHeaderOutdated @367-370
- function_definition GetProtocolVersion @372-375
- function_definition GetEncodedBodySize @377-382
- function_definition LogBlockedCORSRequest @384-389
- function_definition LogMimeTypeMismatch @391-397
- function_definition SetSource @399-403
- function_definition SetConnectionInfo @405-409
- function_definition DoDiagnosticAssertWhenOnStopNotCalledOnDestroy @411-415
- function_definition DisableAltDataCache @417-421
- function_definition SetAltDataForChild @423-427
- function_definition SetCorsPreflightParameters @429-436
- function_definition GetOriginalURI @442-445
- function_definition SetOriginalURI @447-450
- function_definition GetURI @452-456
- function_definition GetOwner @458-461
- function_definition SetOwner @463-466
- function_definition GetNotificationCallbacks @468-472
- function_definition SetNotificationCallbacks @474-478
- function_definition GetSecurityInfo @480-484
- function_definition GetContentType @486-489
- function_definition SetContentType @491-495
- function_definition GetContentCharset @497-500
- function_definition SetContentCharset @502-505
- function_definition GetContentLength @507-510
- function_definition SetContentLength @512-515
- function_definition Open @517-521
- function_definition AsyncOpen @523-610
- function_definition GetCanceled @612-615
- function_definition GetContentDisposition @617-620
- function_definition SetContentDisposition @622-625
- function_definition GetContentDispositionFilename @627-632
- function_definition SetContentDispositionFilename @634-639
- function_definition GetContentDispositionHeader @641-645
- function_definition GetLoadInfo @647-650
- function_definition SetLoadInfo @652-655
- function_definition GetParentProcessChannelHandle @657-661
- function_definition SetParentProcessChannelHandle @663-667
- function_definition GetIsDocument @669-672
- function_definition OnDataAvailable @678-704
- function_definition OnStartRequest @710-715
- function_definition ProcessOnStopRequest @717-743
- function_definition EmitOnDataAvailable @745-769
- function_definition OnStopRequest @771-793
- function_definition GetRelayChannel @799-806
- function_definition ExplicitSetUploadStream @812-849
- function_definition CloneUploadStream @851-856
- function_definition SetClassicScriptHintCharset @858-861
- function_definition GetClassicScriptHintCharset @863-866
- function_definition SetDocumentCharacterSet @868-871
- function_definition GetDocumentCharacterSet @873-876
- function_definition GetDecompressDictionary @878-882
- function_definition SetDecompressDictionary @884-887

### netwerk/protocol/http/ObliviousHttpChannel.h

Blob: `967c23b22352275eb71e5b2350834bc5cc63f68c`. Grammar: cpp. Status: contains-errors.

- include "nsIBinaryHttp.h" @8
- include "nsIHttpChannel.h" @9
- include "nsIHttpChannelInternal.h" @10
- include "nsIObliviousHttp.h" @11
- include "nsIObliviousHttpChannel.h" @12
- include "nsIStreamListener.h" @13
- include "nsITimedChannel.h" @14
- include "nsIUploadChannel2.h" @15
- include "nsTHashMap.h" @16
- class_specifier ObliviousHttpChannel @20-65

### netwerk/protocol/http/ObliviousHttpService.cpp

Blob: `f5ffbb3636e547af16bd42bb4c222551f5b9cdfa`. Grammar: cpp. Status: contains-errors.

- include "ObliviousHttpService.h" @5
- include "DNSUtils.h" @7
- include "ObliviousHttpChannel.h" @8
- include "mozilla/Base64.h" @9
- include "mozilla/StaticPrefs_network.h" @10
- include "nsIObserverService.h" @11
- include "nsIPrefService.h" @12
- include "nsNetUtil.h" @13
- include "nsPrintfCString.h" @14
- function_definition ObliviousHttpService @21-37
- function_definition Init @44-47
- function_definition FetchConfig @49-55
- function_definition FetchConfigInternal @57-125
- function_definition ReadPrefs @127-148
- function_definition NewChannel @152-170
- function_definition GetTRRSettings @172-179
- function_definition ClearTRRConfig @181-186
- function_definition Observe @190-213
- function_definition OnStreamComplete @217-241

### netwerk/protocol/http/ObliviousHttpService.h

Blob: `86cd31cfd156834af19cfd586ede458580c8eac5`. Grammar: cpp. Status: contains-errors.

- include "mozilla/DataMutex.h" @8
- include "nsCOMPtr.h" @9
- include "nsIObliviousHttp.h" @10
- include "nsIObserver.h" @11
- include "nsIStreamLoader.h" @12
- class_specifier ObliviousHttpConfig @16-20
- class_specifier ObliviousHttpService @22-41
- function_definition ~ObliviousHttpService @35-35

### netwerk/protocol/http/OpaqueResponseUtils.cpp

Blob: `1144e766980d4b2a4a2d1ab3a0f65ba166cf38ab`. Grammar: cpp. Status: contains-errors.

- include "mozilla/net/OpaqueResponseUtils.h" @5
- include "ErrorList.h" @7
- include "HttpBaseChannel.h" @8
- include "mozilla/StaticPrefs_browser.h" @9
- include "mozilla/dom/Document.h" @10
- include "mozilla/dom/JSValidatorParent.h" @11
- include "nsContentUtils.h" @12
- include "nsHttpResponseHead.h" @13
- include "nsISupports.h" @14
- include "nsMimeTypes.h" @15
- include "nsStreamUtils.h" @16
- include "nsStringStream.h" @17
- include "nsThreadUtils.h" @18
- function_definition IsOpaqueSafeListedMIMEType @28-36
- enum_specifier OpaqueResponseMediaException @40-40
- function_definition ConfiguredMediaExceptionsStrategy @42-51
- function_definition IsOpaqueSafeListedSpecBreakingMIMEType @53-90
- function_definition IsOpaqueBlockListedMIMEType @92-100
- function_definition IsOpaqueBlockListedNeverSniffedMIMEType @102-146
- function_definition GetOpaqueResponseBlockedReason @148-180
- function_definition GetOpaqueResponseBlockedReason @182-194
- function_definition ParseContentRangeHeaderString @196-240
- function_definition IsFirstPartialResponse @242-255
- function_definition GetORBLog @257-257
- function_definition OpaqueResponseFilter @259-262
- function_definition OnStartRequest @264-280
- function_definition OnDataAvailable @282-292
- function_definition OnStopRequest @294-301
- function_definition OpaqueResponseBlocker @305-326
- function_definition OnStartRequest @328-350
- function_definition OnStopRequest @352-376
- function_definition OnDataAvailable @378-411
- function_definition EnsureOpaqueResponseIsAllowedAfterSniff @413-459
- function_definition EnsureOpaqueResponseIsAllowedAfterJavaScriptValidation @461-472
- function_definition RecordTelemetry @474-511
- function_definition ValidateJavaScript @520-589
- function_definition IsSniffing @591-593
- function_definition AllowResponse @595-599
- function_definition BlockResponse @601-610
- function_definition FilterResponse @612-622
- function_definition ResolveAndProcessData @624-660
- function_definition MaybeRunOnStopRequest @662-667

### netwerk/protocol/http/OpaqueResponseUtils.h

Blob: `3965b5d8ca3dadf37f074923b77044b0e93a6a74`. Grammar: cpp. Status: contains-errors.

- include "ipc/EnumSerializer.h" @8
- include "mozilla/Logging.h" @9
- include "mozilla/TimeStamp.h" @10
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @11
- include "nsCOMPtr.h" @12
- include "nsIContentPolicy.h" @13
- include "nsIEncodedChannel.h" @14
- include "nsIHttpChannel.h" @15
- include "nsIStreamListener.h" @16
- include "nsMimeTypes.h" @17
- include "nsString.h" @18
- include "nsTArray.h" @19
- include "nsUnknownDecoder.h" @20
- class_specifier nsIContentSniffer @22-22
- class_specifier JSValidatorParent @25-25
- class_specifier Shmem @29-29
- class_specifier HttpBaseChannel @34-34
- class_specifier nsHttpResponseHead @35-35
- enum_specifier OpaqueResponseBlockedReason @37-44
- enum_specifier OpaqueResponse @48-48
- class_specifier OpaqueResponseFilter @67-79
- function_definition ~OpaqueResponseFilter @76-76
- class_specifier OpaqueResponseBlocker @81-135
- enum_specifier State @82-82
- enum_specifier ValidatorResult @108-108
- function_definition ~OpaqueResponseBlocker @111-111
- class_specifier nsCompressedAudioVideoImageDetector @137-187
- function_definition nsCompressedAudioVideoImageDetector @141-144
- function_definition DetermineContentType @147-186
- struct_specifier ParamTraits<mozilla::net::OpaqueResponseBlocker::ValidatorResult> @192-196

### netwerk/protocol/http/PHttpChannelParams.h

Blob: `8b1d983ed7256d02e95c72203f508dcf034d2ffa`. Grammar: cpp. Status: contains-errors.

- include "base/basictypes.h" @9
- include "ipc/EnumSerializer.h" @10
- include "ipc/IPCMessageUtils.h" @11
- include "ipc/IPCMessageUtilsSpecializations.h" @12
- include "nsHttp.h" @13
- include "nsHttpHeaderArray.h" @14
- include "nsHttpRequestHead.h" @15
- include "nsHttpResponseHead.h" @16
- struct_specifier RequestHeaderTuple @21-31
- function_definition operator== @27-30
- struct_specifier HttpVersionValidator @35-46
- function_definition IsLegalValue @38-45
- struct_specifier ParamTraits<mozilla::net::HttpVersion> @57-59
- struct_specifier ParamTraits<mozilla::net::nsHttpRequestHead::ParsedMethodType> @62-66
- struct_specifier ParamTraits<mozilla::net::nsHttpAtom> @69-87
- function_definition Write @72-77
- function_definition Read @79-86
- struct_specifier ParamTraits<mozilla::net::nsHttpHeaderArray::nsEntry> @90-179
- function_definition Write @93-127
- function_definition Read @129-178
- struct_specifier ParamTraits<mozilla::net::nsHttpHeaderArray> @182-196
- function_definition Write @185-189
- function_definition Read @191-195
- struct_specifier ParamTraits<mozilla::net::nsHttpRequestHead> @199-233
- function_definition Write @202-214
- function_definition Read @216-232
- struct_specifier ParamTraits<mozilla::net::nsHttpResponseHead> @238-292
- function_definition Write @241-263
- function_definition Read @265-291

### netwerk/protocol/http/ParentChannelListener.cpp

Blob: `decb1a7d6c47012f97e0d9e87bf7ed79fa5770c3`. Grammar: cpp. Status: contains-errors.

- include "ParentChannelListener.h" @6
- include "Element.h" @8
- include "HttpLog.h" @9
- include "mozilla/Components.h" @10
- include "mozilla/SchedulerGroup.h" @11
- include "mozilla/dom/CanonicalBrowsingContext.h" @12
- include "mozilla/dom/ContentParent.h" @13
- include "mozilla/dom/Document.h" @14
- include "mozilla/dom/LoadURIOptionsBinding.h" @15
- include "mozilla/dom/ServiceWorkerInterceptController.h" @16
- include "mozilla/dom/ServiceWorkerUtils.h" @17
- include "mozilla/net/HttpChannelParent.h" @18
- include "mozilla/net/RedirectChannelRegistrar.h" @19
- include "nsIAuthPrompt.h" @20
- include "nsIAuthPrompt2.h" @21
- include "nsIHttpHeaderVisitor.h" @22
- include "nsILoginManagerAuthPrompter.h" @23
- include "nsIPrompt.h" @24
- include "nsIPromptFactory.h" @25
- include "nsISecureBrowserUI.h" @26
- include "nsIThreadRetargetableStreamListener.h" @27
- include "nsIWebNavigation.h" @28
- include "nsIWindowWatcher.h" @29
- include "nsQueryObject.h" @30
- function_definition ParentChannelListener @37-45
- function_definition ~ParentChannelListener @47-49
- function_definition ParentChannelListener::OnStartRequest @67-88
- function_definition OnStopRequest @90-104
- function_definition OnDataAvailable @110-119
- function_definition OnDataFinished @121-133
- function_definition OnAfterLastPart @139-149
- function_definition GetInterface @155-204
- function_definition SetListenerAfterRedirect @206-209
- function_definition ShouldPrepareForIntercept @215-227
- function_definition ChannelIntercepted @229-238
- function_definition GetAuthPrompt @244-273
- function_definition CheckListenerChain @279-290

### netwerk/protocol/http/ParentChannelListener.h

Blob: `8b1dbcdccb4662023289335e874a6eb1b64183d3`. Grammar: cpp. Status: contains-errors.

- include "mozilla/dom/CanonicalBrowsingContext.h" @8
- include "nsIAuthPromptProvider.h" @9
- include "nsIInterfaceRequestor.h" @10
- include "nsIMultiPartChannel.h" @11
- include "nsINetworkInterceptController.h" @12
- include "nsIStreamListener.h" @13
- include "nsIThreadRetargetableStreamListener.h" @14
- class_specifier ParentChannelListener @22-68
- function_definition GetBrowsingContext @46-48
- function_definition ToSupports @70-72

### netwerk/protocol/http/PendingTransactionInfo.cpp

Blob: `cd2fca31b098fe29b89276df2acb42e717229264`. Grammar: cpp. Status: syntax-clean.

- include "PendingTransactionInfo.h" @6
- include "HttpLog.h" @8
- include "NullHttpTransaction.h" @9
- function_definition ~PendingTransactionInfo @20-44
- function_definition IsAlreadyClaimedInitializingConn @46-97
- function_definition ForgetConnectionAttemptAndActiveConn @99-105
- function_definition RememberConnectionAttempt @107-111
- function_definition TryClaimingActiveConn @113-128

### netwerk/protocol/http/PendingTransactionInfo.h

Blob: `e459e08041fbbb5d81290a0e65c532d40fe0d306`. Grammar: cpp. Status: contains-errors.

- include "DnsAndConnectSocket.h" @8
- class_specifier PendingTransactionInfo @13-46
- function_definition PendingTransactionInfo @15-16
- function_definition Transaction @38-38
- class_specifier PendingComparator @48-54
- function_definition Equals @50-53

### netwerk/protocol/http/PendingTransactionQueue.cpp

Blob: `0ba4e2ad80b475e6d4b07e31e2afd7ec325156bf`. Grammar: cpp. Status: contains-errors.

- include "HttpLog.h" @6
- include "PendingTransactionQueue.h" @14
- include "mozilla/ChaosMode.h" @15
- include "mozilla/StaticPrefs_network.h" @16
- include "nsHttpHandler.h" @17
- function_definition TabIdForQueuing @22-26
- function_definition TransactionComparator @31-47
- function_definition InsertTransactionNormal @49-66
- function_definition InsertTransactionSorted @68-107
- function_definition InsertTransaction @109-127
- function_definition GetTransactionPendingQHelper @129-140
- function_definition AppendPendingUrgentStartQ @142-146
- function_definition AppendPendingQForFocusedWindow @148-173
- function_definition AppendPendingQForNonFocusedWindows @175-210
- function_definition ReschedTransaction @212-223
- function_definition RemoveEmptyPendingQ @225-231
- function_definition ComputePendingQueueLength @234-240
- function_definition OnPendingTransactionRemovedFromTable @243-246
- function_definition PendingQueueLengthForWindow @248-252
- function_definition PrintPendingQ @254-266
- function_definition Compact @268-273
- function_definition CancelAllTransactions @275-296

### netwerk/protocol/http/PendingTransactionQueue.h

Blob: `0864963736209362dead14d611d76c468482b0b0`. Grammar: cpp. Status: syntax-clean.

- include "PendingTransactionInfo.h" @8
- include "nsClassHashtable.h" @9
- include "nsHttpTransaction.h" @10
- class_specifier PendingTransactionQueue @15-115
- function_definition PendingTransactionQueue @17-17
- function_definition PendingQueueLength @53-56
- function_definition PendingQueueIsEmpty @60-63
- function_definition UrgentStartQueueLength @74-76
- function_definition UrgentStartQueueIsEmpty @80-82
- function_definition ~PendingTransactionQueue @90-90

### netwerk/protocol/http/QuicSocketControl.cpp

Blob: `0867e93cf9899c18f898d0ad77c0bc1cd7ba47ab`. Grammar: cpp. Status: syntax-clean.

- include "QuicSocketControl.h" @6
- include "Http3Session.h" @8
- include "SharedCertVerifier.h" @9
- include "nsISocketProvider.h" @10
- include "nsIWebProgressListener.h" @11
- include "nsNSSComponent.h" @12
- include "nsSocketTransportService2.h" @13
- include "nsThreadUtils.h" @14
- include "ssl.h" @15
- include "sslt.h" @16
- function_definition QuicSocketControl @21-30
- function_definition SetCertVerificationResult @32-41
- function_definition GetSSLVersionOffered @43-48
- function_definition CallAuthenticated @50-56
- function_definition HandshakeCompleted @58-73
- function_definition SetNegotiatedNPN @75-79
- function_definition SetInfo @81-95
- function_definition GetEchConfig @97-102
- function_definition SetEchConfig @104-113
- function_definition GetRetryEchConfig @115-120
- function_definition SetRetryEchConfig @122-125
- function_definition IsBuiltCertChainRootBuiltInRoot @127-129

### netwerk/protocol/http/QuicSocketControl.h

Blob: `98ca47be50dd675021a44358769a34a0c9ba8c64`. Grammar: cpp. Status: syntax-clean.

- include "CommonSocketControl.h" @9
- include "nsIWeakReferenceUtils.h" @10
- class_specifier Http3Session @15-15
- class_specifier QuicSocketControl @21-58
- function_definition ~QuicSocketControl @51-51

### netwerk/protocol/http/ReplacedHttpResponse.cpp

Blob: `77d78f0112e17f38a3b408bc449e143128f8d0ec`. Grammar: cpp. Status: contains-errors.

- include "ReplacedHttpResponse.h" @5
- function_definition Init @11-12
- function_definition GetResponseStatus @14-18
- function_definition SetResponseStatus @20-24
- function_definition GetResponseStatusText @26-30
- function_definition SetResponseStatusText @32-37
- function_definition GetResponseBody @39-43
- function_definition SetResponseBody @45-49
- function_definition SetResponseHeader @51-59
- function_definition VisitResponseHeaders @61-67

### netwerk/protocol/http/ReplacedHttpResponse.h

Blob: `88de706013aa816725442cc921f3002f4ceab288`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "nsHttpHeaderArray.h" @9
- include "nsIReplacedHttpResponse.h" @10
- include "nsString.h" @11
- class_specifier ReplacedHttpResponse @18-31
- function_definition ~ReplacedHttpResponse @24-24

### netwerk/protocol/http/SpeculativeTransaction.cpp

Blob: `0eba016dd1b5950e6edca069a2d70857b14c7bad`. Grammar: cpp. Status: contains-errors.

- include "SpeculativeTransaction.h" @6
- include "HTTPSRecordResolver.h" @8
- include "HttpLog.h" @9
- include "nsHttpConnectionMgr.h" @10
- include "nsHttpHandler.h" @11
- include "nsICachingChannel.h" @12
- function_definition SpeculativeTransaction @17-22
- function_definition ~SpeculativeTransaction @24-24
- function_definition CreateWithNewConnInfo @26-34
- function_definition FetchHTTPSRR @36-50
- function_definition OnHTTPSRRAvailable @52-71
- function_definition ReadSegments @73-79
- function_definition Close @81-98
- function_definition InvokeCallback @100-106

### netwerk/protocol/http/SpeculativeTransaction.h

Blob: `bfb7b5dd85735b6b328d322f8d24c68b47c55639`. Grammar: cpp. Status: syntax-clean.

- include "NullHttpTransaction.h" @8
- include "mozilla/Maybe.h" @9
- class_specifier HTTPSRecordResolver @14-14
- class_specifier SpeculativeTransaction @16-59
- function_definition SetParallelSpeculativeConnectLimit @32-34
- function_definition SetIgnoreIdle @35-35
- function_definition SetAllow1918 @36-36
- function_definition (anonymous) @38-40
- function_definition (anonymous) @41-41
- function_definition (anonymous) @42-42
- class_specifier FallbackTransaction @61-73
- function_definition FallbackTransaction @63-67
- function_definition IsForFallback @69-69
- function_definition ~FallbackTransaction @72-72

### netwerk/protocol/http/TLSTransportLayer.cpp

Blob: `67a27ab0551a2999fad921c321844884e4fdc143`. Grammar: cpp. Status: contains-errors.

- include "TLSTransportLayer.h" @6
- include "HttpLog.h" @8
- include "nsISocketProvider.h" @9
- include "nsITLSSocketControl.h" @10
- include "nsQueryObject.h" @11
- include "nsSocketProviderService.h" @12
- include "nsSocketTransport2.h" @13
- function_definition InputStreamWrapper::AddRef @25-25
- function_definition InputStreamWrapper::Release @28-30
- function_definition InputStreamWrapper::InputStreamWrapper @32-34
- function_definition InputStreamWrapper::Close @36-40
- function_definition InputStreamWrapper::Available @42-46
- function_definition InputStreamWrapper::StreamStatus @48-52
- function_definition InputStreamWrapper::ReadDirectly @54-59
- function_definition InputStreamWrapper::Read @61-111
- function_definition InputStreamWrapper::ReadSegments @113-121
- function_definition InputStreamWrapper::IsNonBlocking @123-126
- function_definition InputStreamWrapper::CloseWithStatus @128-136
- function_definition InputStreamWrapper::AsyncWait @138-175
- function_definition OutputStreamWrapper::AddRef @185-187
- function_definition OutputStreamWrapper::Release @190-192
- function_definition OutputStreamWrapper::OutputStreamWrapper @194-196
- function_definition OutputStreamWrapper::Close @198-202
- function_definition OutputStreamWrapper::Flush @204-208
- function_definition OutputStreamWrapper::StreamStatus @210-214
- function_definition OutputStreamWrapper::WriteDirectly @216-223
- function_definition OutputStreamWrapper::Write @225-268
- function_definition OutputStreamWrapper::WriteSegments @270-276
- function_definition OutputStreamWrapper::WriteFromSegments @279-284
- function_definition OutputStreamWrapper::WriteFrom @286-291
- function_definition OutputStreamWrapper::IsNonBlocking @293-296
- function_definition OutputStreamWrapper::CloseWithStatus @298-304
- function_definition OutputStreamWrapper::AsyncWait @306-334
- function_definition DispatchRelease @344-355
- function_definition Release @359-377
- function_definition ~TLSTransportLayer @400-408
- function_definition Init @410-454
- function_definition MaybeWakeWaiter @459-477
- function_definition OnInputStreamReady @479-486
- function_definition OnOutputStreamReady @488-496
- function_definition SetKeepaliveEnabled @498-504
- function_definition SetKeepaliveVals @506-514
- function_definition GetSecurityCallbacks @516-523
- function_definition SetSecurityCallbacks @525-533
- function_definition OpenInputStream @535-540
- function_definition OpenOutputStream @542-547
- function_definition Close @549-590
- function_definition SetEventSink @592-599
- function_definition Bind @601-607
- function_definition GetEchConfigUsed @609-615
- function_definition SetEchConfig @617-623
- function_definition ResolvedByTRR @625-631
- function_definition GetEffectiveTRRMode @633-639
- function_definition GetTrrSkipReason @641-647
- function_definition GetTlsSocketControl @689-697
- function_definition GetOriginAttributes @699-705
- function_definition SetOriginAttributes @707-713
- function_definition GetScriptableOriginAttributes @715-723
- function_definition SetScriptableOriginAttributes @725-733
- function_definition GetHost @735-741
- function_definition GetTimeout @743-749
- function_definition SetTimeout @751-757
- function_definition SetReuseAddrPort @759-765
- function_definition SetLinger @767-773
- function_definition GetQoSBits @775-781
- function_definition SetQoSBits @783-789
- function_definition GetRetryDnsIfPossible @791-797
- function_definition GetStatus @799-805
- function_definition OutputInternal @807-823
- function_definition InputInternal @825-839
- function_definition GetPeerName @841-849
- function_definition GetSocketOption @851-858
- function_definition SetSocketOption @860-863
- function_definition Close @865-865
- function_definition Write @867-871
- function_definition Send @873-876
- function_definition Read @878-881
- function_definition Recv @883-886
- function_definition Poll @888-906
- function_definition HasDataToRecv @908-917

### netwerk/protocol/http/TLSTransportLayer.h

Blob: `87e6b9e7fad16a066a1c0bc4dc9441d4adcd14c5`. Grammar: cpp. Status: contains-errors.

- include "nsIAsyncInputStream.h" @8
- include "nsIAsyncOutputStream.h" @9
- include "nsIInterfaceRequestor.h" @10
- include "nsISocketTransport.h" @11
- include "nsSocketTransportService2.h" @12
- include "prio.h" @13
- class_specifier TLSTransportLayer @43-163
- function_definition GetInputStreamWrapper @59-62
- function_definition GetOutputStreamWrapper @63-66
- function_definition ReleaseOwner @70-70
- class_specifier InputStreamWrapper @73-98
- function_definition Status @83-83
- function_definition SetStatus @84-84
- function_definition ~InputStreamWrapper @88-88
- class_specifier OutputStreamWrapper @100-125
- function_definition Status @111-111
- function_definition SetStatus @112-112
- function_definition ~OutputStreamWrapper @116-116
- function_definition Transport @130-130
- function_definition ToSupports @167-169

### netwerk/protocol/http/TRRServiceChannel.cpp

Blob: `376ae9120226120b8a0f7c2335b9207e2b985a97`. Grammar: cpp. Status: contains-errors.

- include "TRRServiceChannel.h" @5
- include "AltServiceChild.h" @7
- include "HttpLog.h" @8
- include "ProxyConfigLookup.h" @9
- include "ReferrerInfo.h" @10
- include "TRR.h" @11
- include "TRRLoadInfo.h" @12
- include "TRRService.h" @13
- include "mozilla/ScopeExit.h" @14
- include "mozilla/StaticPrefs_network.h" @15
- include "mozilla/glean/NetwerkMetrics.h" @16
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @17
- include "nsDNSPrefetch.h" @18
- include "nsEscape.h" @19
- include "nsHttpConnectionMgr.h" @20
- include "nsHttpHeaderArray.h" @21
- include "nsHttpTransaction.h" @22
- include "nsICachingChannel.h" @23
- include "nsICancelable.h" @24
- include "nsIOService.h" @25
- include "nsIProtocolProxyService2.h" @26
- include "nsISeekableStream.h" @27
- include "nsSocketTransportService2.h" @28
- include "nsThreadUtils.h" @29
- include "nsURLHelper.h" @30
- function_definition DispatchRelease @39-50
- function_definition Release @53-71
- function_definition TRRServiceChannel @91-96
- function_definition ~TRRServiceChannel @98-100
- function_definition SetCanceledReason @102-104
- function_definition GetCanceledReason @106-108
- function_definition CancelWithReason @110-114
- function_definition Cancel @116-152
- function_definition CancelNetworkRequest @154-162
- function_definition Suspend @164-173
- function_definition Resume @175-184
- function_definition GetSecurityInfo @186-191
- function_definition AsyncOpen @193-238
- function_definition MaybeResolveProxyAndBeginConnect @240-262
- function_definition ResolveProxy @264-310
- function_definition OnProxyAvailable @312-364
- function_definition BeginConnect @366-527
- function_definition ContinueOnBeforeConnect @529-572
- function_definition Connect @574-588
- function_definition SetupTransaction @590-719
- struct_specifier LNAPerms @700-700
- function_definition MaybeStartDNSPrefetch @721-748
- function_definition OnTransportStatus @750-754
- function_definition CallOnStartRequest @756-848
- function_definition AfterApplyContentConversions @850-884
- function_definition ProcessAltService @886-964
- function_definition OnStartRequest @966-1038
- function_definition SyncProcessRedirection @1040-1120
- function_definition SetupReplacementChannel @1122-1165
- function_definition OnDataAvailable @1167-1184
- function_definition TelemetryReport @1186-1275
- function_definition OnStopRequest @1277-1312
- function_definition OnLookupComplete @1314-1348
- function_definition LogBlockedCORSRequest @1350-1355
- function_definition LogMimeTypeMismatch @1357-1362
- function_definition GetIsAuthChannel @1364-1367
- function_definition SetNotificationCallbacks @1369-1373
- function_definition SetPriority @1375-1378
- function_definition OnClassOfServiceUpdated @1380-1388
- function_definition SetClassFlags @1390-1398
- function_definition SetIncremental @1400-1408
- function_definition SetClassOfService @1410-1418
- function_definition AddClassFlags @1420-1428
- function_definition ClearClassFlags @1430-1438
- function_definition ResumeAt @1440-1443
- function_definition DoAsyncAbort @1445-1447
- function_definition GetProxyInfo @1449-1457
- function_definition GetHttpProxyConnectResponseCode @1459-1465
- function_definition GetHttpProxyResponseHeader @1467-1470
- function_definition GetLoadFlags @1472-1475
- function_definition SetLoadFlags @1477-1486
- function_definition GetURI @1488-1491
- function_definition GetNotificationCallbacks @1493-1497
- function_definition GetLoadGroup @1499-1502
- function_definition GetRequestMethod @1504-1507
- function_definition DoNotifyListener @1509-1543
- function_definition DoNotifyListenerCleanup @1545-1545
- function_definition GetDomainLookupStart @1547-1555
- function_definition GetDomainLookupEnd @1557-1565
- function_definition GetConnectStart @1567-1575
- function_definition GetTcpConnectEnd @1577-1585
- function_definition GetSecureConnectionStart @1587-1595
- function_definition GetConnectEnd @1597-1605
- function_definition GetRequestStart @1607-1615
- function_definition GetResponseStart @1617-1625
- function_definition GetResponseEnd @1627-1635
- function_definition SetLoadGroup @1637-1639
- function_definition TimingAllowCheck @1641-1646
- function_definition SameOriginWithOriginalUri @1648-1648

### netwerk/protocol/http/TRRServiceChannel.h

Blob: `aa0b54b404eb93341406f6af1cb2f6cd2c245cf7`. Grammar: cpp. Status: contains-errors.

- include "HttpBaseChannel.h" @8
- include "mozilla/DataMutex.h" @9
- include "nsIDNSListener.h" @10
- include "nsIProtocolProxyCallback.h" @11
- include "nsIProxiedChannel.h" @12
- include "nsIStreamListener.h" @13
- include "nsITransport.h" @14
- include "nsWeakReference.h" @15
- class_specifier nsDNSPrefetch @17-17
- class_specifier HttpTransactionShell @21-21
- class_specifier nsHttpHandler @22-22
- class_specifier TRRServiceChannel @30-175
- function_definition GetDecompressDictionary @77-81
- function_definition SetDecompressDictionary @82-85
- function_definition SetEarlyHintObserver @96-98
- function_definition SetWebTransportSessionEventListener @99-102
- function_definition SetResponseOverride @104-107
- function_definition SetResponseStatus @109-112
- function_definition IsIsolated @141-141
- function_definition ShouldTaintReplacementChannelOrigin @156-159

### netwerk/protocol/http/TimingStruct.h

Blob: `55e3171003665e796a7a6953fd17f0e206148f67`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/TimeStamp.h" @8
- include "nsString.h" @9
- struct_specifier TimingStruct @14-27
- struct_specifier ResourceTimingStruct @29-41

### netwerk/protocol/http/TlsHandshaker.cpp

Blob: `14fe3c54ec8dacedfeb92ba2a1a8698849091403`. Grammar: cpp. Status: contains-errors.

- include "TlsHandshaker.h" @6
- include "HttpLog.h" @8
- include "mozilla/StaticPrefs_network.h" @9
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @10
- include "nsHttpConnection.h" @11
- include "nsHttpConnectionInfo.h" @12
- include "nsHttpHandler.h" @13
- include "nsITLSSocketControl.h" @14
- function_definition TlsHandshaker @24-28
- function_definition ~TlsHandshaker @30-30
- function_definition NotifyClose @32-36
- function_definition CertVerificationDone @38-45
- function_definition ClientAuthCertificateRequested @47-55
- function_definition ClientAuthCertificateSelected @57-65
- function_definition HandshakeDone @67-85
- function_definition SetupSSL @87-121
- function_definition InitSSLParams @123-162
- function_definition SetupNPNList @168-197
- function_definition EnsureNPNComplete @200-240
- function_definition EarlyDataDone @242-250
- function_definition FinishNPNSetup @252-264
- function_definition Check0RttEnabled @266-338
- function_definition ReportSecureConnectionStart @340-361
- function_definition EarlyDataTelemetry @364-406

### netwerk/protocol/http/TlsHandshaker.h

Blob: `6a533ec5dfb9289313cdf35ffdcb1477440bbe84`. Grammar: cpp. Status: contains-errors.

- include "nsITlsHandshakeListener.h" @8
- include "nsString.h" @9
- class_specifier nsISocketTransport @11-11
- class_specifier nsITLSSocketControl @12-12
- class_specifier nsHttpConnection @16-16
- class_specifier nsHttpConnectionInfo @17-17
- class_specifier TlsHandshaker @19-93
- function_definition EarlyDataAvailable @35-38
- function_definition EarlyDataWasAvailable @39-42
- function_definition EarlyDataUsed @43-43
- function_definition EarlyDataCanNotBeUsed @44-46
- function_definition NPNComplete @54-54
- function_definition SetupSSLCalled @55-55
- function_definition TlsHandshakeComplitionPending @56-58
- function_definition (anonymous) @59-59
- function_definition SetNPNComplete @60-60
- enum_specifier EarlyData @79-86

### netwerk/protocol/http/WebTransportCertificateVerifier.cpp

Blob: `d305c98637dc67e86ea21dcc1355af0f600f62b2`. Grammar: cpp. Status: syntax-clean.

- include "WebTransportCertificateVerifier.h" @5
- include "ScopedNSSTypes.h" @7
- include "hasht.h" @8
- include "nss/mozpkix/pkixcheck.h" @9
- include "nss/mozpkix/pkixutil.h" @10
- class_specifier ServerCertHashesTrustDomain @14-79
- function_definition ServerCertHashesTrustDomain @16-16
- function_definition FindIssuer @81-87
- function_definition GetCertTrust @89-97
- function_definition CheckSignatureDigestAlgorithm @99-106
- function_definition CheckRSAPublicKeyModulusSizeInBits @108-117
- function_definition VerifyRSAPKCS1SignedData @119-125
- function_definition VerifyRSAPSSSignedData @127-133
- function_definition CheckECDSACurveIsAcceptable @135-139
- function_definition VerifyECDSASignedData @141-147
- function_definition DigestBuf @149-155
- function_definition CheckValidityIsAcceptable @157-164
- function_definition CheckRevocation @166-175
- function_definition IsChainValid @177-183
- function_definition NoteAuxiliaryExtension @185-189
- function_definition AuthCertificateWithServerCertificateHashes @197-264

### netwerk/protocol/http/WebTransportCertificateVerifier.h

Blob: `5cfd75ec826925cf3b49c709f8ce199d22fe365e`. Grammar: cpp. Status: syntax-clean.

- include "nsIWebTransport.h" @8
- include "nsTArray.h" @9
- include "nss/mozpkix/pkixtypes.h" @10

### netwerk/protocol/http/WebTransportFlowControl.cpp

Blob: `4c6febe3c2c48973b02e34b771c8b87de5629003`. Grammar: cpp. Status: syntax-clean.

- include "WebTransportFlowControl.h" @5
- function_definition CreateStreamsBlockedCapsule @9-22
- function_definition CreateStreamDataBlockedCapsule @24-36
- function_definition CreateSessionDataBlockedCapsule @38-50
- function_definition CreateMaxStreamsCapsule @52-64
- function_definition CreateMaxStreamDataCapsule @66-78
- function_definition CreateMaxDataCapsule @80-91

### netwerk/protocol/http/WebTransportFlowControl.h

Blob: `621384aaa443eacc2c00663d977b80a8d8c86e2f`. Grammar: cpp. Status: syntax-clean.

- include "Capsule.h" @8
- include "CapsuleEncoder.h" @9
- include "WebTransportStreamBase.h" @10
- include "mozilla/Assertions.h" @11
- include "mozilla/Maybe.h" @12
- include "mozilla/Result.h" @13
- include "mozilla/net/neqo_glue_ffi_generated.h" @14
- class_specifier SenderFlowControlBase @21-69
- function_definition SenderFlowControlBase @23-23
- function_definition Update @25-33
- function_definition Consume @35-38
- function_definition Available @40-40
- function_definition Used @42-42
- function_definition Blocked @44-49
- function_definition BlockedNeeded @55-60
- function_definition BlockedSent @62-62
- class_specifier SenderFlowControlStreamType @72-81
- function_definition SenderFlowControlStreamType @74-75
- class_specifier SenderFlowControlStreamId @84-93
- function_definition SenderFlowControlStreamId @86-87
- class_specifier SenderFlowControlSession @96-102
- function_definition SenderFlowControlSession @98-99
- class_specifier LocalStreamLimits @104-148
- function_definition LocalStreamLimits @106-108
- function_definition TakeStreamId @110-124
- function_definition (anonymous) @126-134
- function_definition (anonymous) @136-143
- class_specifier ReceiverFlowControlBase @150-194
- function_definition ReceiverFlowControlBase @152-153
- function_definition Retire @155-163
- function_definition SendFlowControlUpdate @165-169
- function_definition CapsuleNeeded @171-171
- function_definition NextLimit @172-172
- function_definition MaxActive @173-173
- function_definition SetMaxActive @175-178
- function_definition Retired @180-180
- function_definition Consumed @181-181
- function_definition CapsuleSent @183-186
- class_specifier ReceiverFlowControlStreamId @196-228
- function_definition ReceiverFlowControlStreamId @198-199
- function_definition SetConsumed @203-215
- function_definition AddRetired @217-224
- class_specifier ReceiverFlowControlSession @230-255
- function_definition ReceiverFlowControlSession @232-233
- function_definition Consume @238-245
- function_definition AddRetired @247-254
- class_specifier ReceiverFlowControlStreamType @257-276
- function_definition ReceiverFlowControlStreamType @259-261
- function_definition CheckAllowed @265-265
- function_definition AddRetired @267-272
- class_specifier RemoteStreamLimit @278-315
- function_definition RemoteStreamLimit @280-285
- function_definition IsAllowed @287-290
- function_definition IsNewStream @292-298
- function_definition TakeStreamId @300-305
- function_definition (anonymous) @307-307
- function_definition (anonymous) @308-310
- class_specifier RemoteStreamLimits @317-334
- function_definition RemoteStreamLimits @319-321
- function_definition (anonymous) @323-325
- function_definition (anonymous) @327-329

### netwerk/protocol/http/WebTransportSessionBase.cpp

Blob: `88c8ae932c385be326a1622e87e0b58af8114bb4`. Grammar: cpp. Status: contains-errors.

- include "WebTransportSessionBase.h" @5
- include "nsIWebTransport.h" @7
- function_definition GetRawStats @13-17
- function_definition SetWebTransportSessionEventListener @19-23
- function_definition GetListener @25-29
- function_definition TakeListener @31-35

### netwerk/protocol/http/WebTransportSessionBase.h

Blob: `f1e4a0219a4cc6066d432ab497814ae98271d08a`. Grammar: cpp. Status: contains-errors.

- include <functional> @8
- include "mozilla/Mutex.h" @10
- include "mozilla/dom/PWebTransport.h" @11
- include "nsISupportsImpl.h" @12
- include "nsIWebTransport.h" @13
- include "nsTArray.h" @14
- class_specifier WebTransportSessionEventListener @16-16
- class_specifier WebTransportStreamBase @20-20
- class_specifier Http3WebTransportSession @21-21
- class_specifier WebTransportSessionStatsWrapper @27-42
- function_definition WebTransportSessionStatsWrapper @32-34
- function_definition ~WebTransportSessionStatsWrapper @39-39
- class_specifier WebTransportSessionBase @44-85
- function_definition WebTransportSessionBase @46-48
- function_definition StartReading @70-70
- function_definition GetHttp3WebTransportSession @72-74
- function_definition ~WebTransportSessionBase @77-77

### netwerk/protocol/http/WebTransportStreamBase.cpp

Blob: `ccc0e893c865641e104465222c50a571081597a0`. Grammar: cpp. Status: syntax-clean.

- include "WebTransportStreamBase.h" @5
- include "nsIOService.h" @7
- include "nsIPipe.h" @8
- include "nsSocketTransportService2.h" @9
- function_definition WebTransportStreamBase @13-17
- function_definition ~WebTransportStreamBase @19-19
- function_definition InitOutputPipe @21-42
- function_definition InitInputPipe @44-59
- function_definition GetWriterAndReader @61-74

### netwerk/protocol/http/WebTransportStreamBase.h

Blob: `6d508612138757ca71ec22b7976b371c1a8af268`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "mozilla/Mutex.h" @9
- include "mozilla/net/neqo_glue_ffi_generated.h" @10
- include "nsCOMPtr.h" @11
- include "nsIAsyncInputStream.h" @12
- include "nsIAsyncOutputStream.h" @13
- include "nsISupportsImpl.h" @14
- class_specifier nsIWebTransportSendStreamStats @16-16
- class_specifier nsIWebTransportReceiveStreamStats @17-17
- class_specifier StreamId @27-56
- function_definition StreamId @29-29
- function_definition IsBiDi @31-31
- function_definition IsUni @33-33
- function_definition StreamType @35-38
- function_definition IsClientInitiated @40-40
- function_definition IsServerInitiated @42-42
- function_definition Next @44-44
- function_definition Index @46-46
- function_definition operator== @48-48
- function_definition From @50-50
- function_definition (anonymous) @52-52
- class_specifier SenderFlowControlBase @58-58
- class_specifier ReceiverFlowControlBase @59-59
- class_specifier WebTransportStreamBase @61-128
- function_definition StreamType @71-71
- function_definition SenderFc @89-89
- function_definition ReceiverFc @90-90
- enum_specifier StreamRole @101-104
- enum_specifier SendStreamState @106-111
- enum_specifier RecvStreamState @113-113
- function_definition ToSupports @132-134

### netwerk/protocol/http/ZeroRttHandle.cpp

Blob: `3420542b939271a7c9e9d84460b344e84da5a280`. Grammar: cpp. Status: contains-errors.

- include "ZeroRttHandle.h" @7
- include "HappyEyeballsConnectionAttempt.h" @9
- include "HappyEyeballsTransaction.h" @10
- include "HttpConnectionBase.h" @11
- include "HttpLog.h" @12
- include "mozilla/StaticPrefs_network.h" @13
- include "nsAHttpTransaction.h" @14
- include "nsHttpRequestHead.h" @15
- include "nsHttpTransaction.h" @16
- include "nsIInputStream.h" @17
- include "nsISeekableStream.h" @18
- include "nsSocketTransportService2.h" @19
- include "nsWeakReference.h" @20
- function_definition ZeroRttHandle @30-33
- function_definition ~ZeroRttHandle @35-35
- function_definition IsUsableRealTxn @37-39
- function_definition ResolveRealTxn @44-51
- function_definition Do0RTT @53-110
- function_definition ZeroRttForwardReadSegment @114-120
- function_definition ReadSegments @122-177
- function_definition Finish0RTT @179-312
- function_definition ShouldDisqualify @314-317
- function_definition Cleanup @319-325
- function_definition Transition @327-356
- function_definition RealTxn @358-360

### netwerk/protocol/http/ZeroRttHandle.h

Blob: `f967ab88d045ac26491dd1da879da288f85d8cd9`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Maybe.h" @9
- include "nsISupportsImpl.h" @10
- include "nsIWeakReferenceUtils.h" @11
- include "nscore.h" @12
- class_specifier HappyEyeballsConnectionAttempt @16-16
- class_specifier HappyEyeballsTransaction @17-17
- class_specifier nsAHttpSegmentReader @18-18
- class_specifier nsHttpTransaction @19-19
- class_specifier ZeroRttHandle @53-172
- function_definition AnyStarted @95-95
- function_definition HadWinner @101-101
- function_definition SetAnyStartedForTesting @113-113
- enum_specifier State @134-138

### netwerk/protocol/http/binary_http/src/binary_http.h

Blob: `dc69584fb5e674c5581db43a069fa8c156c83d61`. Grammar: cpp. Status: syntax-clean.

- include "nsISupportsUtils.h" @9

### netwerk/protocol/http/binary_http/src/lib.rs

Blob: `b729a24e115775e549345ecb34f19de65fb60143`. Grammar: rust. Status: syntax-clean.

- enum_item HeaderComponent @20-23
- function_item extract_header_components @26-38
- struct_item BinaryHttpRequest @41-48
- function_item get_method @52-54
- function_item get_scheme @57-59
- function_item get_authority @62-64
- function_item get_path @67-69
- function_item get_content @72-74
- function_item get_header_names @77-82
- function_item get_header_values @85-90
- struct_item BinaryHttpResponse @94-98
- function_item get_status @102-104
- function_item get_content @107-109
- function_item get_header_names @112-117
- function_item get_header_values @120-125
- struct_item BinaryHttp @129-129
- function_item encode_request @133-166
- function_item decode_response @169-190
- function_item decode_request @193-229
- function_item encode_response @232-255
- function_item binary_http_constructor @259-265

### netwerk/protocol/http/happy_eyeballs_glue/HappyEyeballs.cpp

Blob: `0fa559f9bbaf6886df875eea10f532567a32cbf1`. Grammar: cpp. Status: syntax-clean.

- include "HappyEyeballs.h" @5
- function_definition Init @11-19

### netwerk/protocol/http/happy_eyeballs_glue/HappyEyeballs.h

Blob: `ee7d959f1b9dad32497ba0bb6b4baa553b1f0891`. Grammar: cpp. Status: syntax-clean.

- include <cstdint> @8
- include "mozilla/net/happy_eyeballs_glue.h" @10
- include "nsError.h" @11
- include "nsTArray.h" @12
- class_specifier HappyEyeballs @17-30
- function_definition HappyEyeballs @19-19
- function_definition ~HappyEyeballs @20-20
- function_definition AddRef @28-28
- function_definition Release @29-29

### netwerk/protocol/http/happy_eyeballs_glue/src/lib.rs

Blob: `c02ca3f640944cc00c82caf860890b94b7be6227`. Grammar: rust. Status: syntax-clean.

- mod_item metrics @7-7
- mod_item profiler @8-8
- enum_item IpPreference @20-25
- function_item from @28-35
- struct_item HttpVersions @43-47
- function_item from @50-56
- function_item happy_eyeballs_create @60-147
- function_item happy_eyeballs_process_dns_response_a @150-168
- function_item happy_eyeballs_process_dns_response_aaaa @171-189
- function_item happy_eyeballs_process_dns_response_https @192-210
- function_item happy_eyeballs_process_connection_result @213-224
- function_item happy_eyeballs_process_ech_retry @227-243
- function_item happy_eyeballs_process_output @246-273
- struct_item HappyEyeballs @276-281
- function_item process_dns_response_a @284-309
- function_item process_dns_response_aaaa @311-336
- function_item process_dns_response_https @338-410
- function_item process_connection_result @412-432
- function_item process_ech_retry @434-446
- function_item process_output @448-530
- struct_item AltSvc @534-540
- enum_item DnsRecordType @543-547
- enum_item HttpVersion @551-555
- enum_item ConnectionAttemptHttpVersions @558-563
- function_item from @566-572
- function_item from @576-582
- function_item from @586-592
- function_item from @596-603
- function_item from @607-614
- function_item from @618-624
- function_item from @628-633
- struct_item ServiceInfo @637-645
- enum_item IpAddr @648-651
- function_item from @654-659
- enum_item FailureReason @663-666
- enum_item Output @669-696
- function_item happy_eyeballs_release @699-709
- function_item happy_eyeballs_addref @712-719
- function_item addref @723-725
- function_item release @726-728

### netwerk/protocol/http/happy_eyeballs_glue/src/metrics.rs

Blob: `08594cb56126ac72d5cbcbe9028039f1839ceca3`. Grammar: rust. Status: syntax-clean.

- struct_item DnsInfo @11-14
- struct_item ConnInfo @16-18
- enum_item Outcome @20-23
- struct_item Metrics @25-46
- function_item new @49-71
- function_item dns_query_started @73-85
- function_item dns_response @87-111
- function_item dns_response_https @113-132
- function_item connection_attempt_started @134-149
- function_item connection_cancelled @151-155
- function_item connection_succeeded @157-164
- function_item failed @166-170
- function_item drop @174-241
- function_item dns_record_type_label @244-250

### netwerk/protocol/http/happy_eyeballs_glue/src/profiler.rs

Blob: `eaca41a61f74e3eae08b572a290e32cf08ac4992`. Grammar: rust. Status: syntax-clean.

- enum_item Outcome @19-23
- function_item as_str @26-32
- enum_item IpVersion @36-39
- function_item as_str @42-47
- function_item from @51-56
- struct_item DnsMarker @60-71
- function_item marker_type_name @74-76
- function_item marker_type_display @78-89
- function_item stream_json_marker_data @91-101
- struct_item ConnectionMarker @105-113
- function_item marker_type_name @116-118
- function_item marker_type_display @120-131
- function_item stream_json_marker_data @133-143
- struct_item LifetimeMarker @147-154
- function_item marker_type_name @157-159
- function_item marker_type_display @161-171
- function_item stream_json_marker_data @173-182
- struct_item DnsInfo @185-189
- struct_item ConnInfo @191-197
- struct_item Profiler @199-209
- function_item new @212-280
- function_item set_flow_id @282-284
- function_item dns_query_started @286-303
- function_item dns_response @305-332
- function_item dns_response_https @334-390
- function_item connection_attempt_started @392-413
- function_item connection_cancelled @415-417
- function_item connection_result @419-426
- function_item emit_connection_marker @428-449
- function_item drop @453-514

### netwerk/protocol/http/nsAHttpConnection.cpp

Blob: `14d812a165d9e7b1c6d18c9fd2bd48aced0ef9be`. Grammar: cpp. Status: contains-errors.

- include "nsAHttpConnection.h" @5
- include "mozilla/Components.h" @7
- include "nsSocketTransportService2.h" @8
- include "nsThreadUtils.h" @9
- function_definition Release @15-27
- function_definition ~nsAHttpConnection @31-31
- class_specifier DeleteAHttpConnection @33-45
- function_definition DeleteAHttpConnection @35-36
- function_definition Run @38-41
- function_definition DeleteSelfOnSocketThread @47-58

### netwerk/protocol/http/nsAHttpConnection.h

Blob: `df20acfc7acec581face2579b0a70f266416f0b2`. Grammar: cpp. Status: contains-errors.

- include "HttpTrafficAnalyzer.h" @8
- include "WebTransportSessionBase.h" @9
- include "mozilla/net/DNS.h" @10
- include "nsAHttpTransaction.h" @11
- include "nsHttp.h" @12
- include "nsIRequest.h" @13
- include "nsISupports.h" @14
- class_specifier nsIAsyncInputStream @16-16
- class_specifier nsIAsyncOutputStream @17-17
- class_specifier nsISocketTransport @18-18
- class_specifier nsITLSSocketControl @19-19
- class_specifier nsHttpConnectionInfo @24-24
- class_specifier HttpConnectionBase @25-25
- class_specifier nsHttpRequestHead @26-26
- class_specifier nsHttpResponseHead @27-27
- class_specifier nsAHttpConnection @37-181
- function_definition TransactionHasDataToWrite @78-80
- function_definition TransactionHasDataToRecv @84-86
- function_definition GetConnectionInfo @204-210
- function_definition GetTLSSocketControl @211-217
- function_definition ResumeSend @218-221
- function_definition ResumeRecv @222-225
- function_definition ForceSend @226-229
- function_definition ForceRecv @230-233
- function_definition Transport @234-237
- function_definition Version @238-241
- function_definition IsProxyConnectInProgress @242-244
- function_definition LastTransactionExpectedNoContent @245-248
- function_definition SetLastTransactionExpectedNoContent @249-251
- function_definition BytesWritten @252-254
- function_definition SetSecurityCallbacks @255-257
- function_definition SetTrafficCategory @258-260
- function_definition GetSelfAddr @261-264
- function_definition GetPeerAddr @265-268
- function_definition ResolvedByTRR @269-271
- function_definition EffectiveTRRMode @272-275
- function_definition TRRSkipReason @276-279
- function_definition GetEchConfigUsed @280-282
- function_definition SetCloseReason @283-285

### netwerk/protocol/http/nsAHttpTransaction.h

Blob: `000c037036a13353a74dafae48a4bb316e8cb55d`. Grammar: cpp. Status: contains-errors.

- include "nsILoadInfo.h" @8
- include "nsIRequest.h" @9
- include "nsITRRSkipReason.h" @10
- include "nsTArray.h" @11
- include "nsWeakReference.h" @12
- class_specifier nsIDNSHTTPSSVCRecord @22-22
- class_specifier nsIInterfaceRequestor @23-23
- class_specifier nsIRequestContext @24-24
- class_specifier nsISVCBRecord @25-25
- class_specifier nsITLSSocketControl @26-26
- class_specifier nsITransport @27-27
- class_specifier nsAHttpConnection @32-32
- class_specifier nsAHttpSegmentReader @33-33
- class_specifier nsAHttpSegmentWriter @34-34
- class_specifier nsHttpTransaction @35-35
- class_specifier nsHttpRequestHead @36-36
- class_specifier nsHttpResponseHead @37-37
- class_specifier ProxyConnectResponseHead @38-38
- class_specifier nsHttpConnectionInfo @39-39
- class_specifier NullHttpTransaction @40-40
- enum_specifier ExtendedCONNECTSupport @42-42
- class_specifier nsAHttpTransaction @57-263
- function_definition OnActivated @67-67
- function_definition ReadSegmentsAgain @99-104
- function_definition WriteSegmentsAgain @105-109
- function_definition Cancel @115-115
- function_definition IsNullTransaction @153-153
- function_definition QueryNullTransaction @154-154
- function_definition QueryHttpTransaction @159-159
- function_definition RequestContext @162-162
- function_definition GetTransactionTLSSocketControl @177-180
- function_definition DisableSpdy @182-182
- function_definition DisableHttp2ForProxy @184-184
- function_definition DisableHttp3 @185-185
- function_definition MakeNonSticky @186-186
- function_definition MakeRestartable @187-187
- function_definition ReuseConnectionOnRestartOK @188-188
- function_definition SetIsHttp2Websocket @189-189
- function_definition IsHttp2Websocket @190-190
- function_definition AllowedToConnectToIpAddressSpace @193-196
- function_definition DoNotRemoveAltSvc @204-204
- function_definition DoNotResetIPFamilyPreference @208-208
- function_definition Do0RTT @215-217
- function_definition OnPSKResumptionAccepted @222-222
- function_definition Finish0RTT @234-236
- function_definition BrowserId @238-241
- function_definition OnProxyConnectComplete @243-244
- function_definition OnClientAuthCertificateRequested @248-248
- function_definition OnClientAuthCertificateSelected @249-249
- function_definition FetchHTTPSRR @251-251
- function_definition OnHTTPSRRAvailable @252-256
- function_definition IsForWebTransport @257-257
- function_definition IsResettingForTunnelConn @258-258
- function_definition SetResettingForTunnelConn @259-259
- function_definition InvokeCallback @261-261
- function_definition IsForFallback @262-262
- class_specifier nsAHttpSegmentReader @290-313
- function_definition CommitToSegmentSize @309-312
- class_specifier nsAHttpSegmentWriter @323-328

### netwerk/protocol/http/nsCORSListenerProxy.cpp

Blob: `bf817d772b43f73092249c7915db550e9dfa1867`. Grammar: cpp. Status: contains-errors.

- include "nsCORSListenerProxy.h" @5
- include <algorithm> @7
- include "HttpChannelChild.h" @9
- include "mozilla/Assertions.h" @10
- include "mozilla/BasePrincipal.h" @11
- include "mozilla/Components.h" @12
- include "mozilla/ExpandedPrincipal.h" @13
- include "mozilla/LinkedList.h" @14
- include "mozilla/LoadInfo.h" @15
- include "mozilla/NullPrincipal.h" @16
- include "mozilla/Preferences.h" @17
- include "mozilla/StaticPrefs_content.h" @18
- include "mozilla/StaticPrefs_dom.h" @19
- include "mozilla/StaticPrefs_network.h" @20
- include "mozilla/StoragePrincipalHelper.h" @21
- include "mozilla/dom/ReferrerInfo.h" @22
- include "mozilla/dom/RequestBinding.h" @23
- include "mozilla/dom/nsHTTPSOnlyUtils.h" @24
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @25
- include "nsAsyncRedirectVerifyHelper.h" @26
- include "nsCharSeparatedTokenizer.h" @27
- include "nsClassHashtable.h" @28
- include "nsComponentManagerUtils.h" @29
- include "nsContentUtils.h" @30
- include "nsError.h" @31
- include "nsHashKeys.h" @32
- include "nsHttpChannel.h" @33
- include "nsIAsyncVerifyRedirectCallback.h" @34
- include "nsICORSPreflightCache.h" @35
- include "nsIChannel.h" @36
- include "nsIChannelEventSink.h" @37
- include "nsIConsoleService.h" @38
- include "nsICorsPreflightCallback.h" @39
- include "nsIDNSRecord.h" @40
- include "nsIDNSService.h" @41
- include "nsIHttpChannel.h" @42
- include "nsIHttpChannelInternal.h" @43
- include "nsIHttpHeaderVisitor.h" @44
- include "nsIInterfaceRequestorUtils.h" @45
- include "nsILoadContext.h" @46
- include "nsILoadGroup.h" @47
- include "nsINetworkInterceptController.h" @48
- include "nsIScriptError.h" @49
- include "nsISupportsImpl.h" @50
- include "nsIThreadRetargetableStreamListener.h" @51
- include "nsMimeTypes.h" @52
- include "nsNetUtil.h" @53
- include "nsQueryObject.h" @54
- include "nsServiceManagerUtils.h" @55
- include "nsStreamUtils.h" @56
- include "nsString.h" @57
- include "nsStringStream.h" @58
- include "nsWhitespaceTokenizer.h" @59
- struct_specifier CORSCacheEntry @64-64
- function_definition GetStatusCodeAsString @70-77
- function_definition LogBlockedRequest @79-157
- class_specifier nsPreflightCache @162-187
- struct_specifier TokenTime @167-170
- function_definition ~nsPreflightCache @182-182
- struct_specifier CORSCacheEntry @189-223
- function_definition CORSCacheEntry @193-201
- function_definition ~CORSCacheEntry @220-220
- function_definition GetEntries @227-240
- function_definition ClearEntry @242-256
- function_definition EnsurePreflightCache @261-267
- function_definition PurgePrivateBrowsingEntries @269-278
- function_definition GetKey @282-286
- function_definition GetURI @288-292
- function_definition GetOriginAttributes @294-301
- function_definition (anonymous) @303-303
- function_definition GetPrincipal @305-309
- function_definition GetPrivateBrowsing @311-315
- function_definition GetWithCredentials @317-321
- function_definition PurgeExpired @323-338
- function_definition CheckDNSCache @340-389
- function_definition CheckRequest @391-428
- struct_specifier CheckToken @403-408
- function_definition Equals @404-407
- struct_specifier CheckHeaderToken @415-420
- function_definition Equals @416-419
- function_definition GetEntry @430-500
- function_definition RemoveEntries @502-522
- function_definition Clear @524-527
- function_definition GetCORSPreflightSingleton @537-545
- function_definition Shutdown @548-548
- function_definition ClearCache @551-556
- function_definition ClearPrivateBrowsingCache @559-564
- function_definition GetOriginHeaderPrincipal @574-583
- function_definition nsCORSListenerProxy @585-598
- function_definition Init @600-622
- function_definition OnStartRequest @624-677
- class_specifier CheckOriginHeader @680-702
- function_definition CheckOriginHeader @682-684
- function_definition VisitHeader @686-696
- function_definition ~CheckOriginHeader @701-701
- function_definition CheckRequestApproved @707-836
- function_definition OnStopRequest @838-850
- function_definition OnDataAvailable @852-871
- function_definition OnDataFinished @873-890
- function_definition SetInterceptController @892-895
- function_definition GetInterface @897-917
- function_definition AsyncOnChannelRedirect @919-1036
- function_definition CheckListenerChain @1038-1052
- function_definition CheckInsecureUpgradePreventsCORS @1063-1098
- function_definition UpdateChannel @1100-1259
- function_definition CheckPreflightNeeded @1261-1333
- class_specifier nsCORSPreflightListener @1340-1375
- function_definition nsCORSPreflightListener @1344-1354
- function_definition ~nsCORSPreflightListener @1365-1365
- function_definition AddResultToCache @1381-1491
- function_definition OnStartRequest @1493-1515
- function_definition OnStopRequest @1517-1521
- function_definition OnDataAvailable @1525-1532
- function_definition AsyncOnChannelRedirect @1534-1551
- function_definition CheckPreflightRequestApproved @1553-1685
- function_definition GetInterface @1687-1696
- function_definition RemoveFromCorsPreflightCache @1698-1706
- function_definition StartCORSPreflight @1709-1877
- function_definition LogBlockedCORSRequest @1880-1926

### netwerk/protocol/http/nsCORSListenerProxy.h

Blob: `4fdad610c11c64728ac6dad981c6195eab55ecb4`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "mozilla/Mutex.h" @9
- include "nsCOMPtr.h" @10
- include "nsICORSPreflightCache.h" @11
- include "nsIChannelEventSink.h" @12
- include "nsIInterfaceRequestor.h" @13
- include "nsIStreamListener.h" @14
- include "nsIThreadRetargetableStreamListener.h" @15
- include "nsIURI.h" @16
- include "nsString.h" @17
- include "nsTArray.h" @18
- class_specifier nsIHttpChannel @20-20
- class_specifier nsIURI @21-21
- class_specifier nsIPrincipal @22-22
- class_specifier nsINetworkInterceptController @23-23
- class_specifier nsICorsPreflightCallback @24-24
- class_specifier HttpChannelParent @28-28
- class_specifier nsHttpChannel @29-29
- enum_specifier DataURIHandling @33-33
- enum_specifier UpdateType @35-39
- class_specifier nsCORSListenerProxy @41-129
- function_definition ~nsCORSListenerProxy @90-90

### netwerk/protocol/http/nsHttp.cpp

Blob: `7c3ad3e2dc60fd966760d003e15f31f8af468ad0`. Grammar: cpp. Status: contains-errors.

- include "nsHttp.h" @6
- include <errno.h> @8
- include <string.h> @9
- include <functional> @11
- include "CacheControlParser.h" @13
- include "HttpLog.h" @14
- include "PLDHashTable.h" @15
- include "mozilla/DataMutex.h" @16
- include "mozilla/OriginAttributes.h" @17
- include "mozilla/Preferences.h" @18
- include "mozilla/StaticPrefs_network.h" @19
- include "nsCRT.h" @20
- include "nsContentUtils.h" @21
- include "nsHttpHandler.h" @22
- include "nsHttpRequestHead.h" @23
- include "nsHttpResponseHead.h" @24
- include "nsICacheEntry.h" @25
- include "nsIRequest.h" @26
- include "nsIStandardURL.h" @27
- include "nsJSUtils.h" @28
- include "nsLiteralString.h" @29
- include "nsStandardURL.h" @30
- include "sslerr.h" @31
- enum_specifier (anonymous) @44-47
- function_definition CreateAtomTable @61-82
- function_definition CreateAtomTable @84-88
- function_definition DestroyAtomTable @90-95
- function_definition ResolveAtom @98-130
- function_definition IsValidToken @167-176
- function_definition GetProtocolVersion @178-195
- function_definition TrimHTTPWhitespace @198-205
- function_definition IsReasonableHeaderValue @208-221
- function_definition FindToken @223-242
- function_definition ParseInt64 @244-265
- function_definition IsPermanentRedirect @267-269
- function_definition ValidationRequired @271-417
- function_definition GetHttpResponseHeadFromCacheEntry @419-450
- function_definition CheckPartial @452-473
- function_definition DetermineFramingAndImmutability @475-486
- function_definition IsBeforeLastActiveTabLoadOptimization @488-491
- function_definition ConvertRequestHeadToString @493-528
- function_definition NotifyActiveTabLoadOptimization @530-534
- function_definition GetLastActiveTabLoadOptimizationHit @536-539
- function_definition SetLastActiveTabLoadOptimizationHit @541-545
- function_definition localEnsureBuffer @550-566
- function_definition EnsureBuffer @568-571
- function_definition EnsureBuffer @573-576
- function_definition IsTokenSymbol @578-583
- function_definition ParsedHeaderPair @585-602
- function_definition RemoveQuotedStringEscapes @604-614
- function_definition Tokenize @616-667
- function_definition ParsedHeaderValueList @669-681
- function_definition ParseNameAndValue @683-778
- function_definition ParsedHeaderValueListList @780-791
- function_definition CallingScriptLocationString @793-808
- function_definition LogCallingScriptLocation @810-813
- function_definition LogCallingScriptLocation @815-825
- function_definition LogHeaders @827-843
- function_definition HttpProxyResponseToErrorCode @845-981
- function_definition IsAlpnSupported @983-1001
- function_definition PossibleZeroRTTRetryError @1007-1014
- function_definition MakeOriginURL @1016-1021
- function_definition MakeOriginURL @1023-1031
- function_definition CreatePushHashKey @1033-1064
- function_definition GetNSResultFromWebTransportError @1066-1069
- function_definition GetWebTransportErrorFromNSResult @1071-1079
- function_definition WebTransportErrorToHttp3Error @1081-1083
- function_definition Http3ErrorToWebTransportError @1085-1100
- function_definition ToCloseReason @1102-1144
- function_definition DisallowHTTPSRR @1146-1150
- function_definition HttpVersionToTelemetryLabel @1153-1167
- function_definition GetProxyDNSStrategyHelper @1169-1182

### netwerk/protocol/http/nsHttp.h

Blob: `b0a41456bed55d3a2ceb1e84bed11f23d5efb5c4`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @8
- include "NSSErrorsService.h" @10
- include "mozilla/OriginAttributes.h" @11
- include "mozilla/TimeStamp.h" @12
- include "mozilla/UniquePtr.h" @13
- include "nsError.h" @14
- include "nsIHttpChannelInternal.h" @15
- include "nsString.h" @16
- include "nsTArray.h" @17
- include "prtime.h" @18
- class_specifier nsICacheEntry @20-20
- class_specifier nsHttpResponseHead @25-25
- class_specifier nsHttpRequestHead @26-26
- class_specifier CacheControlParser @27-27
- enum_specifier HttpVersion @29-36
- enum_specifier SpdyVersion @38-38
- enum_specifier SupportedAlpnRank @40-45
- enum_specifier ConnectionCloseReason @49-72
- function_definition IsHttp3 @76-78
- struct_specifier nsHttpAtom @202-202
- struct_specifier nsHttpAtomLiteral @203-203
- function_definition IsValidToken @216-218
- function_definition ParseInt64 @248-251
- function_definition SendDataInChunks @298-318
- struct_specifier nsHttpAtomLiteral @322-322
- struct_specifier nsHttpAtom @323-347
- function_definition nsHttpAtom @324-324
- function_definition nsHttpAtom @325-325
- function_definition (anonymous) @327-327
- function_definition get @329-334
- function_definition (anonymous) @336-336
- function_definition operator= @338-338
- function_definition nsHttpAtom @342-342
- struct_specifier nsHttpAtomLiteral @349-360
- function_definition get @350-350
- function_definition (anonymous) @351-351
- function_definition nsHttpAtomLiteral @354-354
- function_definition (anonymous) @356-356
- function_definition operator== @362-365
- function_definition operator!= @366-369
- function_definition operator== @371-373
- function_definition operator!= @374-376
- function_definition operator== @378-380
- function_definition operator!= @381-383
- function_definition operator== @385-387
- function_definition operator!= @388-390
- include "nsHttpAtomList.inc" @402
- function_definition PRTimeToSeconds @410-412
- class_specifier ParsedHeaderPair @430-453
- function_definition ParsedHeaderPair @435-443
- class_specifier ParsedHeaderValueList @455-462
- class_specifier ParsedHeaderValueListList @464-478
- function_definition AllowedErrorForTransactionRetry @493-502

### netwerk/protocol/http/nsHttpActivityDistributor.cpp

Blob: `f0be1ad93395090062e94b455a6edc6a6be8876b`. Grammar: cpp. Status: contains-errors.

- include "nsHttpActivityDistributor.h" @6
- include "HttpLog.h" @8
- include "NullHttpChannel.h" @9
- include "mozilla/net/SocketProcessChild.h" @10
- include "mozilla/net/SocketProcessParent.h" @11
- include "nsCOMPtr.h" @12
- include "nsHttpHandler.h" @13
- include "nsIOService.h" @14
- include "nsNetUtil.h" @15
- include "nsQueryObject.h" @16
- include "nsThreadUtils.h" @17
- function_definition ObserveActivity @28-49
- function_definition ObserveConnectionActivity @51-70
- function_definition ObserveActivityWithArgs @72-95
- function_definition Activated @155-155
- function_definition ObserveProxyResponseEnabled @157-159
- function_definition ObserveConnectionEnabled @161-163
- function_definition GetIsActive @165-176
- function_definition SetIsActive @178-183
- function_definition AddObserver @185-219
- function_definition RemoveObserver @221-250
- function_definition GetObserveProxyResponse @252-259
- function_definition SetObserveProxyResponse @261-280
- function_definition GetObserveConnection @282-288
- function_definition SetObserveConnection @290-309

### netwerk/protocol/http/nsHttpActivityDistributor.h

Blob: `3eb52366b65fe0e095ba37b615a747f40426157c`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Atomics.h" @8
- include "mozilla/Mutex.h" @9
- include "nsIHttpActivityObserver.h" @10
- include "nsProxyRelease.h" @11
- include "nsTArray.h" @12
- class_specifier nsHttpActivityDistributor @17-35
- function_definition nsHttpActivityDistributor @23-25
- function_definition ~nsHttpActivityDistributor @28-28

### netwerk/protocol/http/nsHttpAuthCache.cpp

Blob: `37c88a92d5d5b3f681342bf8b7dc9d06ad1c934b`. Grammar: cpp. Status: contains-errors.

- include "nsHttpAuthCache.h" @6
- include <algorithm> @8
- include "HttpLog.h" @10
- include "mozilla/DebugOnly.h" @11
- include "mozilla/Services.h" @12
- include "nsCRT.h" @13
- include "nsIObserverService.h" @14
- include "nsNetUtil.h" @15
- include "nsString.h" @16
- function_definition GetAuthKey @21-32
- function_definition GetEntries @40-51
- function_definition ClearEntry @53-71
- function_definition nsHttpAuthCache @73-75
- function_definition Init @80-86
- function_definition ~nsHttpAuthCache @88-93
- function_definition GetAuthEntryForPath @95-111
- function_definition GetAuthEntryForDomain @113-131
- function_definition SetAuthEntry @133-161
- function_definition ClearAuthEntry @163-171
- function_definition ClearAll @173-176
- function_definition LookupAuthNode @182-193
- function_definition Observe @195-206
- function_definition ClearOriginData @208-229
- function_definition CollectKeys @231-233
- function_definition Clear @239-243
- function_definition Equals @245-249
- function_definition GetDomain @253-257
- function_definition GetUser @259-263
- function_definition GetPassword @265-269
- function_definition GetRealm @276-280
- function_definition GetCreds @282-286
- function_definition GetChallenge @288-292
- function_definition GetDomain @294-298
- function_definition GetUser @300-304
- function_definition GetPassword @306-310
- function_definition GetIdentity @312-318
- function_definition AddPath @320-329
- function_definition Set @331-356
- function_definition nsHttpAuthNode @362-364
- function_definition ~nsHttpAuthNode @366-370
- function_definition LookupEntryByPath @372-392
- function_definition LookupEntryItrByRealm @394-399
- function_definition LookupEntryByRealm @401-408
- function_definition SetAuthEntry @410-431
- function_definition ClearAuthEntry @433-438

### netwerk/protocol/http/nsHttpAuthCache.h

Blob: `2cd7c6b4bbc2da27e38e5c846b6587449c06280e`. Grammar: cpp. Status: contains-errors.

- include "nsCOMPtr.h" @8
- include "nsClassHashtable.h" @9
- include "nsError.h" @10
- include "nsHashKeys.h" @11
- include "nsIHttpAuthCache.h" @12
- include "nsIObserver.h" @13
- include "nsStringFwd.h" @14
- include "nsTArray.h" @15
- include "nsWeakReference.h" @16
- class_specifier OriginAttributesPattern @20-20
- class_specifier nsHttpAuthIdentity @28-51
- function_definition nsHttpAuthIdentity @30-30
- function_definition nsHttpAuthIdentity @31-33
- function_definition ~nsHttpAuthIdentity @34-34
- function_definition (anonymous) @36-36
- function_definition (anonymous) @37-37
- function_definition (anonymous) @38-38
- function_definition IsEmpty @43-45
- class_specifier AuthIdentity @54-64
- function_definition AuthIdentity @59-59
- function_definition ~AuthIdentity @62-62
- class_specifier nsHttpAuthEntry @70-117
- function_definition nsHttpAuthEntry @75-81
- function_definition (anonymous) @83-83
- function_definition (anonymous) @84-84
- function_definition (anonymous) @85-85
- function_definition (anonymous) @86-86
- function_definition (anonymous) @87-87
- function_definition (anonymous) @88-88
- function_definition (anonymous) @90-90
- function_definition ~nsHttpAuthEntry @97-97
- class_specifier nsHttpAuthNode @123-157
- function_definition EntryCount @149-149
- class_specifier nsHttpAuthCache @164-231

### netwerk/protocol/http/nsHttpAuthManager.cpp

Blob: `6eee83bec85f009dd04f86a84c69e94ca2e5fd5c`. Grammar: cpp. Status: contains-errors.

- include "nsHttpAuthManager.h" @6
- include "HttpLog.h" @8
- include "nsHttpHandler.h" @9
- include "nsIPrincipal.h" @10
- include "nsNetUtil.h" @11
- function_definition GetHttpAuthCacheSingleton @19-25
- function_definition Init @27-49
- function_definition GetAuthIdentity @51-82
- function_definition SetAuthIdentity @84-105
- function_definition ClearAll @107-112

### netwerk/protocol/http/nsHttpAuthManager.h

Blob: `1a61b118cc7fbb10508a2be94a5b4ed9a775c0e1`. Grammar: cpp. Status: contains-errors.

- include "nsIHttpAuthManager.h" @8
- class_specifier nsIHttpAuthCache @10-10
- class_specifier nsHttpAuthCache @15-15
- class_specifier nsHttpAuthManager @17-32
- function_definition nsHttpAuthManager @24-24
- function_definition ~nsHttpAuthManager @28-28

### netwerk/protocol/http/nsHttpBasicAuth.cpp

Blob: `1e45341c6a93d27660264cc71bae59afaf159072`. Grammar: cpp. Status: contains-errors.

- include "nsHttpBasicAuth.h" @6
- include "HttpLog.h" @8
- include "mozilla/Base64.h" @9
- include "mozilla/ClearOnShutdown.h" @10
- include "nsCRT.h" @11
- include "nsString.h" @12
- function_definition GetOrCreate @19-30
- function_definition ChallengeReceived @42-52
- function_definition GenerateCredentialsAsync @53-61
- function_definition GenerateCredentials @63-91
- function_definition GetAuthFlags @93-97

### netwerk/protocol/http/nsHttpBasicAuth.h

Blob: `a5900834cfeabf711b51fb2e3944882c21158c54`. Grammar: cpp. Status: contains-errors.

- include "mozilla/StaticPtr.h" @8
- include "nsIHttpAuthenticator.h" @9
- class_specifier nsHttpBasicAuth @19-32
- function_definition nsHttpBasicAuth @24-24
- function_definition ~nsHttpBasicAuth @29-29

### netwerk/protocol/http/nsHttpChannel.cpp

Blob: `67e517994f5f4656d89a904a75905e970eb639ca`. Grammar: cpp. Status: contains-errors.

- include "nsHttpChannel.h" @6
- include <inttypes.h> @8
- include "AlternateServices.h" @10
- include "CacheControlParser.h" @11
- include "CacheStorageService.h" @12
- include "CookieService.h" @13
- include "HttpChannelParent.h" @14
- include "HttpLog.h" @15
- include "HttpTrafficAnalyzer.h" @16
- include "HttpTransactionParent.h" @17
- include "InterceptedHttpChannel.h" @18
- include "LNAPermissionRequest.h" @19
- include "LoadContextInfo.h" @20
- include "NetworkMarker.h" @21
- include "ThirdPartyUtil.h" @22
- include "mozilla/AntiTrackingRedirectHeuristic.h" @23
- include "mozilla/AntiTrackingUtils.h" @24
- include "mozilla/Attributes.h" @25
- include "mozilla/BasePrincipal.h" @26
- include "mozilla/Components.h" @27
- include "mozilla/ContentBlockingAllowList.h" @28
- include "mozilla/DebugOnly.h" @29
- include "mozilla/FlowMarkers.h" @30
- include "mozilla/LoadInfo.h" @31
- include "mozilla/NullPrincipal.h" @32
- include "mozilla/PerfStats.h" @33
- include "mozilla/ProfilerDumpOrCrash.h" @34
- include "mozilla/ProfilerLabels.h" @35
- include "mozilla/ScopeExit.h" @36
- include "mozilla/Services.h" @37
- include "mozilla/Sprintf.h" @38
- include "mozilla/StaticPrefs_dom.h" @39
- include "mozilla/StaticPrefs_network.h" @40
- include "mozilla/StaticPrefs_privacy.h" @41
- include "mozilla/StaticPrefs_security.h" @42
- include "mozilla/StoragePrincipalHelper.h" @43
- include "mozilla/Telemetry.h" @44
- include "mozilla/TimeStamp.h" @45
- include "mozilla/ToString.h" @46
- include "mozilla/dom/ClientInfo.h" @47
- include "mozilla/dom/Document.h" @48
- include "mozilla/dom/NavigatorLogin.h" @49
- include "mozilla/dom/PerformanceStorage.h" @50
- include "mozilla/dom/PolicyContainer.h" @51
- include "mozilla/dom/ReferrerInfo.h" @52
- include "mozilla/dom/SecFetch.h" @53
- include "mozilla/dom/ServiceWorkerUtils.h" @54
- include "mozilla/dom/WindowGlobalParent.h" @55
- include "mozilla/dom/nsCSPContext.h" @56
- include "mozilla/dom/nsHTTPSOnlyStreamListener.h" @57
- include "mozilla/dom/nsHTTPSOnlyUtils.h" @58
- include "mozilla/extensions/StreamFilterParent.h" @59
- include "mozilla/glean/AntitrackingMetrics.h" @60
- include "mozilla/glean/DomSecurityMetrics.h" @61
- include "mozilla/glean/NetwerkMetrics.h" @62
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @63
- include "mozilla/net/AsyncUrlChannelClassifier.h" @64
- include "mozilla/net/CaptivePortalService.h" @65
- include "mozilla/net/ChannelClassifierUtils.h" @66
- include "mozilla/net/CookieJarSettings.h" @67
- include "mozilla/net/CookieServiceParent.h" @68
- include "mozilla/net/NeckoChannelParams.h" @69
- include "mozilla/net/NoVarySearchUtils.h" @70
- include "mozilla/net/OpaqueResponseUtils.h" @71
- include "mozilla/net/SFVService.h" @72
- include "mozilla/net/SocketProcessParent.h" @73
- include "mozilla/net/TRRService.h" @74
- include "mozilla/net/URLPatternGlue.h" @75
- include "mozilla/net/urlpattern_glue.h" @76
- include "netCore.h" @77
- include "nsCOMPtr.h" @78
- include "nsCORSListenerProxy.h" @79
- include "nsCRT.h" @80
- include "nsChannelClassifier.h" @81
- include "nsCharSeparatedTokenizer.h" @82
- include "nsComponentManagerUtils.h" @83
- include "nsContentSecurityManager.h" @84
- include "nsContentSecurityUtils.h" @85
- include "nsContentUtils.h" @86
- include "nsDNSPrefetch.h" @87
- include "nsError.h" @88
- include "nsEscape.h" @89
- include "nsHttp.h" @90
- include "nsHttpChannelAuthProvider.h" @91
- include "nsHttpConnectionMgr.h" @92
- include "nsHttpHandler.h" @93
- include "nsHttpTransaction.h" @94
- include "nsICacheEntry.h" @95
- include "nsICacheStorage.h" @96
- include "nsICacheStorageService.h" @97
- include "nsICancelable.h" @98
- include "nsIClassOfService.h" @99
- include "nsICompressConvStats.h" @100
- include "nsIConsoleService.h" @101
- include "nsICookieNotification.h" @102
- include "nsICryptoHash.h" @103
- include "nsIDNSRecord.h" @104
- include "nsIEffectiveTLDService.h" @105
- include "nsIHttpChannelInternal.h" @106
- include "nsIHttpHeaderVisitor.h" @107
- include "nsINetworkErrorLogging.h" @108
- include "nsINetworkInterceptController.h" @109
- include "nsINetworkLinkService.h" @110
- include "nsIOService.h" @111
- include "nsIPrincipal.h" @112
- include "nsIPrompt.h" @113
- include "nsIProtocolProxyService2.h" @114
- include "nsIRedirectResultListener.h" @115
- include "nsIScriptError.h" @116
- include "nsIScriptSecurityManager.h" @117
- include "nsISeekableStream.h" @118
- include "nsISiteIntegrityService.h" @119
- include "nsISiteSecurityService.h" @120
- include "nsISocketProvider.h" @121
- include "nsISocketTransport.h" @122
- include "nsIStreamConverter.h" @123
- include "nsIStreamConverterService.h" @124
- include "nsIStreamListenerTee.h" @125
- include "nsIStreamTransportService.h" @126
- include "nsIStringBundle.h" @127
- include "nsISystemInfo.h" @128
- include "nsITransportSecurityInfo.h" @129
- include "nsIURIMutator.h" @130
- include "nsIURLQueryStringStripper.h" @131
- include "nsIWebProgressListener.h" @132
- include "nsIWebTransport.h" @133
- include "nsInputStreamPump.h" @134
- include "nsMimeTypes.h" @135
- include "nsMixedContentBlocker.h" @136
- include "nsNetCID.h" @137
- include "nsNetUtil.h" @138
- include "nsPrintfCString.h" @139
- include "nsQueryObject.h" @140
- include "nsStreamUtils.h" @141
- include "nsString.h" @142
- include "nsStringStream.h" @143
- include "nsThreadUtils.h" @144
- include "nsURLHelper.h" @145
- include "nsUnknownDecoder.h" @146
- include "prnetdb.h" @147
- include "sslt.h" @148
- include "HttpWinUtils.h" @150
- include "MicrosoftEntraSSOUtils.h" @153
- include "mozilla/StaticPrefs_fuzzing.h" @156
- include "mozilla/dom/ReportDeliver.h" @159
- include "mozilla/dom/ReportingHeader.h" @160
- enum_specifier ChannelDisposition @183-194
- function_definition CacheDispositionToTelemetryLabel @196-214
- function_definition AccumulateCacheHitTelemetry @216-248
- function_definition Hash @252-269
- class_specifier CookieVisitor @271-289
- function_definition CookieVisitor @273-281
- function_definition ~CookieVisitor @283-283
- function_definition (anonymous) @285-285
- class_specifier CookieObserver @291-308
- function_definition StealChanges @299-301
- function_definition CookieObserver @304-304
- function_definition ~CookieObserver @305-305
- function_definition Create @313-331
- function_definition Observe @333-375
- function_definition MaybeInitializeCookieProcessingGuard @377-411
- function_definition WillRedirect @417-420
- function_definition AutoRedirectVetoNotifier @425-433
- class_specifier MOZ_STACK_CLASS @425-425
- function_definition ~AutoRedirectVetoNotifier @437-437
- function_definition RedirectSucceeded @438-438
- function_definition ReportRedirectResult @447-472
- function_definition nsHttpChannel @478-483
- function_definition ~nsHttpChannel @485-513
- function_definition Init @515-523
- function_definition AddSecurityMessage @525-532
- function_definition LogBlockedCORSRequest @534-543
- function_definition LogMimeTypeMismatch @545-555
- function_definition AddStorageAccessHeadersToRequest @561-597
- function_definition StorageAccessReloadedChannel @599-601
- function_definition PrimeSuspendAfterExamineResponse @603-605
- function_definition CancelSuspendOrResumeAfterExamineResponse @607-615
- function_definition MaybeSuspendAfterExamineResponse @617-626
- function_definition PrepareToConnect @628-826
- function_definition ContinuePrepareToConnect @828-834
- function_definition HandleContinueCancellingByURLClassifier @836-856
- function_definition SetPriorityHeader @858-883
- function_definition OnBeforeConnect @885-1017
- function_definition canUseHTTPSRRonNetwork @1026-1070
- function_definition MaybeUseHTTPSRRForUpgrade @1072-1170
- function_definition ContinueOnBeforeConnect @1172-1286
- function_definition AddResponseHeadersToResponseHead @1288-1301
- class_specifier MOZ_STACK_CLASS @1288-1288
- function_definition AddRef @1306-1308
- function_definition Release @1310-1312
- function_definition ~AddResponseHeadersToResponseHead @1314-1316
- function_definition HandleOverrideResponse @1326-1412
- function_definition Connect @1414-1495
- function_definition ConnectOnTailUnblock @1497-1541
- function_definition ContinueConnect @1543-1617
- function_definition DoConnect @1619-1653
- function_definition DoConnectActual @1655-1669
- function_definition DispatchTransaction @1671-1708
- function_definition SpeculativeConnect @1710-1751
- function_definition DoNotifyListenerCleanup @1753-1756
- function_definition ReleaseListeners @1758-1770
- function_definition DoAsyncAbort @1772-1774
- function_definition HandleAsyncRedirect @1776-1809
- function_definition ContinueHandleAsyncRedirect @1811-1843
- function_definition HandleAsyncNotModified @1845-1866
- function_definition SetupChannelForTransaction @1868-2054
- function_definition UpdateLocalNetworkAccessPermissions @2058-2162
- function_definition InitTransaction @2164-2260
- function_definition CreateTrafficCategory @2262-2309
- function_definition SetCachedContentType @2311-2338
- function_definition ShouldSniffMisconfiguredType @2340-2384
- function_definition CallOnStartRequest @2386-2722
- function_definition GetHttpProxyConnectResponseCode @2724-2735
- function_definition GetHttpProxyResponseHeader @2737-2744
- function_definition ProcessFailedProxyConnect @2746-2778
- function_definition GetSTSConsoleErrorTag @2780-2808
- function_definition ProcessHSTSHeader @2813-2864
- function_definition ProcessWAICTHeader @2867-2931
- function_definition ProcessSecurityHeaders @2940-2975
- function_definition IsHTTPS @2977-2977
- function_definition ProcessSSLInformation @2979-3013
- function_definition ProcessAltService @3015-3088
- function_definition ProcessResponse @3090-3215
- function_definition AsyncContinueProcessResponse @3217-3228
- function_definition ContinueProcessResponse1 @3230-3338
- function_definition ContinueProcessResponse2 @3340-3377
- function_definition ContinueProcessResponse3 @3379-3603
- function_definition ContinueProcessResponseAfterPartialContent @3605-3614
- function_definition ContinueProcessResponseAfterNotModified @3616-3657
- function_definition ReportHttpResponseVersion @3659-3667
- function_definition UpdateCacheDisposition @3669-3691
- function_definition ContinueProcessResponse4 @3694-3742
- function_definition ProcessNormal @3744-3748
- function_definition ContinueProcessNormal @3750-3873
- function_definition ContinueProcessNormal2 @3875-3925
- function_definition ContinueProcessNormal3 @3927-4017
- function_definition PromptTempRedirect @4019-4047
- function_definition SetHTTPSSVCRecord @4085-4091
- function_definition HandleAsyncRedirectChannelToHttps @4093-4114
- function_definition StartRedirectChannelToHttps @4116-4126
- function_definition HandleAsyncAPIRedirect @4128-4154
- function_definition HandleAsyncRedirectToUnstrippedURI @4156-4188
- function_definition RedirectToNewChannelForAuthRetry @4189-4298
- function_definition StartRedirectChannelToURI @4300-4303
- function_definition StartRedirectChannelToURI @4305-4358
- function_definition ContinueAsyncRedirectChannelToURI @4360-4390
- function_definition OpenRedirectChannel @4392-4419
- function_definition AsyncDoReplaceWithProxy @4421-4449
- function_definition ResolveProxy @4451-4473
- function_definition ResponseWouldVary @4475-4555
- function_definition RemoveFromVary @4558-4588
- function_definition HandleAsyncAbort @4593-4595
- function_definition IsResumable @4601-4614
- function_definition MaybeSetupByteRangeRequest @4616-4634
- function_definition SetupByteRangeRequest @4636-4665
- function_definition UntieByteRangeRequest @4667-4673
- function_definition ProcessPartialContent @4675-4779
- function_definition OnDoneReadingPartialCacheEntry @4781-4823
- function_definition ShouldBypassProcessNotModified @4829-4843
- function_definition MaybeGenerateNELReport @4845-4914
- function_definition ProcessNotModified @4916-4997
- function_definition IsSubRangeRequest @5001-5017
- function_definition OpenCacheEntry @5019-5036
- function_definition OpenCacheEntryInternal @5038-5149
- function_definition NoteCacheEntryKeyMatch @5157-5185
- function_definition GetCacheStorage @5191-5210
- function_definition MaybeReplaceNoVarySearchAliasEntry @5218-5248
- function_definition CheckPartial @5250-5255
- function_definition UntieValidationRequest @5257-5266
- function_definition OnCacheEntryCheck @5268-5680
- function_definition OnCacheEntryAvailable @5682-5723
- function_definition OnCacheEntryAvailableInternal @5725-5752
- function_definition OnNormalCacheEntryAvailable @5754-5792
- function_definition GenerateCacheKey @5795-5799
- function_definition AssembleCacheKey @5802-5827
- function_definition DoUpdateExpirationTime @5829-5878
- function_definition UpdateExpirationTime @5889-5896
- function_definition OpenCacheInputStream @5898-6095
- function_definition ReadFromCache @6099-6175
- function_definition CloseCacheEntry @6177-6263
- function_definition OnOpaqueResponseAllowed @6265-6272
- function_definition InitCacheEntry @6279-6345
- function_definition UpdateInhibitPersistentCachingFlag @6347-6367
- function_definition DoAddCacheEntryHeaders @6369-6400
- function_definition AddCacheEntryHeaders @6402-6406
- function_definition UpdateCacheEntryHeaders @6408-6520
- function_definition ParseDictionary @6522-6595
- function_definition GetAuthType @6597-6606
- function_definition StoreAuthorizationMetaData @6608-6620
- function_definition FinalizeCacheEntry @6626-6642
- function_definition InstallCacheListener @6644-6646
- function_definition DoInstallCacheListener @6657-6825
- function_definition SetupReplacementChannel @6831-6954
- function_definition AsyncProcessRedirection @6956-7095
- function_definition ContinueProcessRedirectionAfterFallback @7097-7168
- function_definition ContinueProcessRedirection @7170-7199
- function_definition OnAuthAvailable @7205-7225
- function_definition OnAuthCancelled @7227-7265
- function_definition CloseStickyConnection @7267-7294
- function_definition ConnectionRestartable @7296-7301
- function_definition DispatchRelease @7308-7319
- function_definition Release @7322-7330
- function_definition SetCanceledReason @7367-7369
- function_definition GetCanceledReason @7371-7373
- function_definition CancelWithReason @7375-7378
- function_definition Cancel @7380-7424
- function_definition CancelByURLClassifier @7426-7478
- function_definition ContinueCancellingByURLClassifier @7480-7500
- function_definition CancelInternal @7502-7647
- function_definition CancelNetworkRequest @7649-7660
- function_definition Suspend @7662-7703
- function_definition StaticSuspend @7706-7706
- function_definition Resume @7708-7829
- function_definition GetSecurityInfo @7835-7840
- function_definition AsyncOpen @7847-7985
- function_definition AsyncOpenFinal @7987-8049
- function_definition MaybeResolveProxyAndBeginConnect @8051-8085
- function_definition AsyncOpenOnTailUnblock @8087-8091
- function_definition GetOrCreateChannelClassifier @8093-8103
- function_definition ComputeProxyDNSStrategy @8105-8116
- function_definition GetProxyDNSStrategy @8118-8124
- function_definition BeginConnect @8130-12923
- function_definition MaybeStartDNSPrefetch @8527-8597
- function_definition GetEncodedBodySize @8599-8609
- function_definition GetDecompressDictionary @8611-8615
- function_definition SetDecompressDictionary @8617-8631
- function_definition GetIsAuthChannel @8637-8641
- function_definition SetChannelIsForDownload @8643-8652
- function_definition ProcessId @8654-8664
- function_definition AttachStreamFilter @8666-8701
- function_definition GetNavigationStartTimeStamp @8703-8709
- function_definition SetNavigationStartTimeStamp @8711-8716
- function_definition SetPriority @8722-8750
- function_definition OnClassOfServiceUpdated @8756-8769
- function_definition SetClassFlags @8771-8779
- function_definition AddClassFlags @8781-8789
- function_definition ClearClassFlags @8791-8799
- function_definition SetClassOfService @8801-8809
- function_definition SetIncremental @8811-8819
- function_definition OnProxyAvailable @8825-8905
- function_definition GetProxyInfo @8911-8919
- function_definition GetDomainLookupStart @8925-8933
- function_definition GetDomainLookupEnd @8935-8943
- function_definition GetConnectStart @8945-8953
- function_definition GetTcpConnectEnd @8955-8963
- function_definition GetSecureConnectionStart @8965-8973
- function_definition GetConnectEnd @8975-8983
- function_definition GetRequestStart @8985-8993
- function_definition GetResponseStart @8995-9003
- function_definition GetFirstInterimResponseStart @9005-9013
- function_definition GetFinalResponseHeadersStart @9015-9023
- function_definition GetResponseEnd @9025-9033
- function_definition GetTransactionPending @9035-9043
- function_definition GetIsSSL @9049-9055
- function_definition GetProxyMethodIsConnect @9057-9061
- function_definition GetServerResponseHeader @9063-9067
- function_definition GetProxyChallenges @9069-9073
- function_definition GetWWWChallenges @9075-9079
- function_definition SetProxyCredentials @9081-9084
- function_definition SetWWWCredentials @9086-9097
- function_definition GetLoadFlags @9104-9107
- function_definition GetURI @9109-9110
- function_definition GetNotificationCallbacks @9112-9115
- function_definition GetLoadGroup @9117-9120
- function_definition GetRequestMethod @9122-9125
- function_definition RecordOnStartTelemetry @9131-9194
- enum_specifier HttpOnStartState @9149-9153
- function_definition hasConnectivity @9196-9212
- function_definition GetFallbackURI @9214-9231
- function_definition IsInternalSystemLoad @9236-9244
- function_definition GetEssentialDomainCategory @9247-9267
- function_definition ReportLNAAccessToConsole @9272-9309
- function_definition ProcessLNAActions @9311-9375
- function_definition UpdateCurrentIpAddressSpace @9377-9414
- function_definition OnStartRequest @9416-9629
- function_definition MaybeUpdateDocumentIPAddressSpaceFromCache @9631-9663
- function_definition OnPermissionPromptResult @9665-9733
- function_definition ContinueOnStartRequest1 @9735-9769
- function_definition ContinueOnStartRequest2 @9771-9796
- function_definition ContinueOnStartRequest3 @9798-9807
- function_definition ReportHTTPSRRTelemetry @9809-9830
- function_definition RecordHttpChanDispositionGlean @9832-9884
- enum_specifier HttpChannelDispositionUpgrade @9886-9892
- function_definition HttpChanDispositionToTelemetryLabel @9894-9911
- function_definition LogConsoleError @9913-9935
- function_definition RecordHTTPSUpgradeTelemetry @9937-10059
- function_definition RecordIPAddressSpaceTelemetry @10061-10092
- function_definition RecordLNATelemetry @10094-10232
- function_definition OnStopRequest @10234-10457
- function_definition ContinueOnStopRequestAfterAuthRetry @10459-10536
- function_definition ContinueOnStopRequest @10538-10825
- class_specifier OnTransportStatusAsyncEvent @10831-10858
- function_definition OnTransportStatusAsyncEvent @10833-10842
- function_definition Run @10844-10851
- function_definition OnDataAvailable @10860-10991
- function_definition RetargetDeliveryTo @10997-11048
- function_definition GetDeliveryTarget @11050-11061
- function_definition CheckListenerChain @11067-11077
- function_definition OnDataFinished @11079-11089
- function_definition OnTransportStatus @11095-11170
- function_definition IsFromCache @11176-11185
- function_definition HasCacheEntry @11187-11191
- function_definition GetCacheEntryId @11193-11200
- function_definition GetCacheTokenFetchCount @11202-11212
- function_definition GetCacheTokenExpirationTime @11214-11220
- function_definition SetAllowStaleCacheContent @11222-11228
- function_definition GetAllowStaleCacheContent @11229-11234
- function_definition SetForceValidateCacheContent @11236-11242
- function_definition GetForceValidateCacheContent @11243-11248
- function_definition SetPreferCacheLoadOverBypass @11250-11254
- function_definition GetPreferCacheLoadOverBypass @11255-11260
- function_definition PreferAlternativeDataType @11262-11270
- function_definition FUZZING @11272-11275
- function_definition GetAlternativeDataType @11277-11285
- class_specifier CacheEntryWriteHandle @11287-11301
- function_definition ~CacheEntryWriteHandle @11288-11288
- function_definition CacheEntryWriteHandle @11294-11297
- function_definition OpenAlternativeOutputStream @11310-11320
- function_definition GetCacheEntryWriteHandle @11322-11334
- function_definition OpenAlternativeOutputStream @11336-11355
- function_definition GetOriginalInputStream @11357-11371
- function_definition GetAlternativeDataInputStream @11373-11387
- function_definition GetCacheToken @11393-11398
- function_definition SetCacheToken @11400-11403
- function_definition GetCacheKey @11405-11413
- function_definition SetCacheKey @11415-11423
- function_definition GetCacheOnlyMetadata @11425-11430
- function_definition SetCacheOnlyMetadata @11432-11445
- function_definition GetPin @11447-11452
- function_definition SetPin @11454-11462
- function_definition ForceCacheEntryValidFor @11464-11484
- function_definition ResumeAt @11490-11498
- function_definition DoAuthRetry @11500-11536
- function_definition ContinueDoAuthRetry @11538-11584
- function_definition WaitForRedirectCallback @11590-11612
- function_definition OnRedirectVerifyCallback @11614-11668
- function_definition PushRedirectAsyncFunc @11670-11672
- function_definition PopRedirectAsyncFunc @11674-11679
- function_definition OnLookupComplete @11685-11715
- function_definition OnHTTPSRRAvailable @11717-11753
- function_definition CreateNewURI @11760-11766
- function_definition MaybeInvalidateCacheEntryForSubsequentGet @11768-11804
- function_definition InvalidateCacheEntryForLocation @11806-11815
- function_definition DoInvalidateCacheEntry @11817-11850
- function_definition AsyncOnExamineCachedResponse @11852-11854
- function_definition UpdateAggregateCallbacks @11856-11865
- function_definition SetLoadGroup @11867-11876
- function_definition SetNotificationCallbacks @11878-11887
- function_definition AwaitingCacheCallbacks @11889-11891
- function_definition IsRedirectStatus @11894-11898
- function_definition SetCouldBeSynthesized @11900-11903
- function_definition OnPreflightSucceeded @11905-11912
- function_definition OnPreflightFailed @11914-11923
- function_definition CallOrWaitForResume @11925-11940
- function_definition HasNullRequestOrigin @11944-11970
- function_definition SetOriginHeader @11975-12099
- function_definition SetDoNotTrack @12101-12111
- function_definition SetGlobalPrivacyControl @12113-12123
- function_definition ReportSystemChannelTelemetry @12125-12250
- function_definition TriggerNetwork @12252-12283
- function_definition OnSuspendTimeout @12285-12299
- function_definition TimerCallback::TimerCallback @12301-12302
- function_definition TimerCallback::GetName @12306-12310
- function_definition TimerCallback::Notify @12312-12323
- function_definition MaybeStartCacheWaitTimer @12325-12341
- function_definition CancelCacheWaitTimer @12343-12348
- function_definition OnCacheWaitTimeout @12350-12384
- function_definition EligibleForTailing @12386-12407
- function_definition WaitingForTailUnblock @12409-12440
- function_definition OnTailUnblock @12448-12472
- function_definition SetWarningReporter @12474-12478
- function_definition GetWarningReporter @12480-12484
- function_definition DisableIsOpaqueResponseAllowedAfterSniffCheck @12497-12549
- function_definition RedirectToInterceptedChannel @12553-12631
- class_specifier CopyNonDefaultHeaderVisitor @12553-12577
- function_definition ~CopyNonDefaultHeaderVisitor @12556-12556
- function_definition VisitHeader @12558-12564
- function_definition CopyNonDefaultHeaderVisitor @12567-12570
- function_definition ReEvaluateReferrerAfterTrackingStatusIsKnown @12633-12672
- class_specifier BackgroundRevalidatingListener @12678-12690
- function_definition OnStartRequest @12692-12695
- function_definition OnDataAvailable @12697-12704
- function_definition OnStopRequest @12706-12718
- function_definition GetInterface @12720-12727
- function_definition AsyncOnChannelRedirect @12731-12738
- function_definition PerformBackgroundCacheRevalidation @12746-12763
- function_definition PerformBackgroundCacheRevalidationNow @12765-12840
- function_definition SetEarlyHintObserver @12842-12846
- function_definition EarlyHint @12848-12861
- function_definition SetResponseOverride @12863-12875
- function_definition SetResponseStatus @12877-12892
- function_definition SetWebTransportSessionEventListener @12894-12898
- function_definition GetWebTransportSessionEventListener @12900-12905
- function_definition GetLastTransportStatus @12907-12911
- function_definition GetCacheDisposition @12913-12920

### netwerk/protocol/http/nsHttpChannel.h

Blob: `cb5da1a630eb49624078262917d34146c6367444`. Grammar: cpp. Status: contains-errors.

- include "AlternateServices.h" @8
- include "AutoClose.h" @9
- include "HttpBaseChannel.h" @10
- include "HttpTransactionShell.h" @11
- include "TimingStruct.h" @12
- include "mozilla/AtomicBitfields.h" @13
- include "mozilla/Atomics.h" @14
- include "mozilla/Mutex.h" @15
- include "mozilla/extensions/PStreamFilterParent.h" @16
- include "mozilla/net/DocumentLoadListener.h" @17
- include "nsHttpResponseHead.h" @18
- include "nsIAsyncVerifyRedirectCallback.h" @19
- include "nsICacheEntry.h" @20
- include "nsICacheEntryOpenCallback.h" @21
- include "nsICacheStorage.h" @22
- include "nsICachingChannel.h" @23
- include "nsICorsPreflightCallback.h" @24
- include "nsIDNSListener.h" @25
- include "nsIEarlyHintObserver.h" @26
- include "nsIHttpAuthenticableChannel.h" @27
- include "nsIProtocolProxyCallback.h" @28
- include "nsIReplacedHttpResponse.h" @29
- include "nsIRequestContext.h" @30
- include "nsIStreamListener.h" @31
- include "nsIThreadRetargetableRequest.h" @32
- include "nsIThreadRetargetableStreamListener.h" @33
- include "nsITransport.h" @34
- include "nsITransportSecurityInfo.h" @35
- include "nsTArray.h" @36
- include "nsWeakReference.h" @37
- class_specifier nsDNSPrefetch @39-39
- class_specifier nsICancelable @40-40
- class_specifier nsIDNSRecord @41-41
- class_specifier nsIDNSHTTPSSVCRecord @42-42
- class_specifier nsIHttpChannelAuthProvider @43-43
- class_specifier nsInputStreamPump @44-44
- class_specifier nsITransportSecurityInfo @45-45
- class_specifier nsChannelClassifier @50-50
- class_specifier HttpChannelSecurityWarningReporter @51-51
- class_specifier nsHttpChannel @63-975
- function_definition DataSentToChildProcess @220-220
- enum_specifier SnifferType @222-222
- function_definition GetRequestTime @228-228
- function_definition (anonymous) @229-229
- function_definition GetSnifferCategoryType @249-251
- class_specifier AutoCacheWaitFlags @254-276
- function_definition AutoCacheWaitFlags @256-260
- function_definition Keep @262-265
- function_definition ~AutoCacheWaitFlags @267-271
- function_definition IsReadingFromCache @283-283
- function_definition HostPartIsTheSame @525-530
- function_definition DoNotRender3xxBody @532-536
- function_definition IsAuthRedirectedChannel @576-576
- function_definition CachedContentIsValid @781-783
- class_specifier TimerCallback @830-842
- function_definition ~TimerCallback @839-839
- enum_specifier ResponseSource @845-849
- enum_specifier EssentialDomainCategory @930-937
- function_definition ToSupports @980-982

### netwerk/protocol/http/nsHttpChannelAuthProvider.cpp

Blob: `cacd523a510a19680a3f93e9ee767824015479cd`. Grammar: cpp. Status: contains-errors.

- include "nsHttpChannelAuthProvider.h" @6
- include "HttpLog.h" @8
- include "MockHttpAuth.h" @9
- include "mozilla/BasePrincipal.h" @10
- include "mozilla/Components.h" @11
- include "mozilla/StoragePrincipalHelper.h" @12
- include "mozilla/Tokenizer.h" @13
- include "netCore.h" @14
- include "nsAuthInformationHolder.h" @15
- include "nsCRT.h" @16
- include "nsContentUtils.h" @17
- include "nsEscape.h" @18
- include "nsHttp.h" @19
- include "nsHttpBasicAuth.h" @20
- include "nsHttpDigestAuth.h" @21
- include "nsHttpHandler.h" @22
- include "nsIAuthPrompt2.h" @23
- include "nsIAuthPromptProvider.h" @24
- include "nsIHttpAuthenticableChannel.h" @25
- include "nsIHttpAuthenticator.h" @26
- include "nsIHttpChannelInternal.h" @27
- include "nsIInterfaceRequestor.h" @28
- include "nsIInterfaceRequestorUtils.h" @29
- include "nsIPromptService.h" @30
- include "nsIStringBundle.h" @31
- include "nsIURI.h" @32
- include "nsNetUtil.h" @33
- include "nsHttpNegotiateAuth.h" @35
- include "mozilla/StaticPrefs_network.h" @37
- include "mozilla/StaticPrefs_prompts.h" @38
- include "nsHttpNTLMAuth.h" @39
- include "nsIProxiedChannel.h" @40
- include "nsIProxyInfo.h" @41
- include "nsIURL.h" @42
- include "nsServiceManagerUtils.h" @43
- function_definition GetOriginAttributesSuffix @54-63
- function_definition nsHttpChannelAuthProvider @65-71
- function_definition ~nsHttpChannelAuthProvider @73-76
- function_definition Init @78-118
- function_definition ProcessAuthentication @120-185
- function_definition AddAuthorizationHeaders @187-241
- function_definition Cancel @243-257
- function_definition Disconnect @259-277
- function_definition GetAuthPrompt @280-298
- function_definition GenCredsAndSetEntry @301-346
- function_definition UpdateCache @348-392
- function_definition ClearProxyIdent @394-399
- function_definition PrepareForAuthentication @401-443
- function_definition ChallengeParser @445-450
- class_specifier MOZ_STACK_CLASS @445-445
- function_definition GetNext @452-511
- enum_specifier ChallengeRank @514-520
- function_definition Rank @522-544
- function_definition GetCredentials @546-713
- struct_specifier AuthChallenge @551-561
- function_definition operator= @556-560
- function_definition GetAuthorizationMembers @715-745
- function_definition GetCredentialsForChallenge @747-973
- function_definition BlockPrompt @975-1070
- function_definition GetAuthType @1072-1077
- function_definition GetAuthenticator @1079-1116
- function_definition ParseUserDomain @1119-1126
- function_definition GetIdentityFromURI @1128-1165
- function_definition ParseRealm @1167-1256
- class_specifier nsHTTPAuthInformation @1258-1265
- function_definition nsHTTPAuthInformation @1260-1262
- function_definition SetToHttpAuthIdentity @1267-1270
- function_definition PromptForIdentity @1272-1361
- function_definition OnAuthAvailable @1363-1426
- function_definition OnAuthCancelled @1428-1495
- function_definition OnCredsGenerated @1497-1552
- function_definition ContinueOnAuthAvailable @1554-1573
- function_definition SetAuthorizationHeader @1575-1676
- function_definition GetCurrentPath @1678-1687

### netwerk/protocol/http/nsHttpChannelAuthProvider.h

Blob: `943e7f2efc35a615af2d31c986e9f570978a6bbe`. Grammar: cpp. Status: contains-errors.

- include "nsCOMPtr.h" @8
- include "nsHttpAuthCache.h" @9
- include "nsIAuthPromptCallback.h" @10
- include "nsICancelable.h" @11
- include "nsIHttpAuthenticatorCallback.h" @12
- include "nsIHttpChannelAuthProvider.h" @13
- include "nsProxyInfo.h" @14
- include "nsString.h" @15
- class_specifier nsIHttpAuthenticableChannel @17-17
- class_specifier nsIHttpAuthenticator @18-18
- class_specifier nsIURI @19-19
- class_specifier nsHttpHandler @24-24
- struct_specifier nsHttpAtom @25-25
- class_specifier nsHttpChannelAuthProvider @27-176
- function_definition (anonymous) @42-44
- function_definition ProxyPort @46-46
- function_definition (anonymous) @48-48
- function_definition Port @49-49
- function_definition UsingSSL @50-50
- function_definition UsingHttpProxy @52-54

### netwerk/protocol/http/nsHttpChunkedDecoder.cpp

Blob: `9b8a632f70c5320c3d5ccd1e491612703ae9791b`. Grammar: cpp. Status: syntax-clean.

- include "nsHttpChunkedDecoder.h" @6
- include <errno.h> @8
- include <string.h> @9
- include <algorithm> @11
- include "HttpLog.h" @13
- function_definition HandleChunkedContent @22-78
- function_definition ParseChunkRemaining @84-173

### netwerk/protocol/http/nsHttpChunkedDecoder.h

Blob: `c260d2b5f31a6c59ae3c0fbcd344da728c879f81`. Grammar: cpp. Status: syntax-clean.

- include "nsError.h" @8
- include "nsHttpHeaderArray.h" @9
- include "nsString.h" @10
- class_specifier nsHttpChunkedDecoder @15-44
- function_definition nsHttpChunkedDecoder @17-17
- function_definition ~nsHttpChunkedDecoder @18-18
- function_definition ReachedEOF @20-20
- function_definition Trailers @27-27
- function_definition TakeTrailers @29-29
- function_definition GetChunkRemaining @32-32

### netwerk/protocol/http/nsHttpConnection.cpp

Blob: `075f0892a987fec46c8d2cd8739571b62a49a6c2`. Grammar: cpp. Status: contains-errors.

- include "HttpLog.h" @6
- include "ASpdySession.h" @14
- include "NSSErrorsService.h" @15
- include "TLSTransportLayer.h" @16
- include "mozilla/ChaosMode.h" @17
- include "mozilla/StaticPrefs_network.h" @18
- include "mozilla/glean/NetwerkMetrics.h" @19
- include "mozilla/glean/NetwerkProtocolHttpMetrics.h" @20
- include "mozpkix/pkixnss.h" @21
- include "nsCRT.h" @22
- include "nsHttpConnection.h" @23
- include "nsHttpConnectionMgr.h" @24
- include "nsHttpHandler.h" @25
- include "nsHttpRequestHead.h" @26
- include "nsHttpResponseHead.h" @27
- include "nsIClassOfService.h" @28
- include "nsIOService.h" @29
- include "nsISocketTransport.h" @30
- include "nsISupportsPriority.h" @31
- include "nsITLSSocketControl.h" @32
- include "nsITransportSecurityInfo.h" @33
- include "nsPreloadedStream.h" @34
- include "nsProxyRelease.h" @35
- include "nsQueryObject.h" @36
- include "nsSocketTransport2.h" @37
- include "nsSocketTransportService2.h" @38
- include "nsStringStream.h" @39
- include "nsThreadUtils.h" @40
- include "sslerr.h" @41
- include "sslt.h" @42
- function_definition nsHttpConnection @54-63
- function_definition ~nsHttpConnection @65-115
- function_definition Init @117-154
- function_definition TryTakeSubTransactions @156-183
- function_definition ResetTransaction @185-201
- function_definition MoveTransactionsToSpdy @203-270
- function_definition Start0RTTSpdy @272-305
- function_definition StartSpdy @307-421
- function_definition OnClientAuthCertificateRequested @423-427
- function_definition OnClientAuthCertificateSelected @429-433
- function_definition PostProcessNPNSetup @435-525
- function_definition Reset0RttForSpdy @527-535
- function_definition Activate @538-705
- function_definition AddTransaction @707-760
- function_definition SwapTransaction @762-774
- function_definition CreateTunnelStream @776-803
- function_definition Close @805-892
- function_definition MarkAsDontReuse @894-900
- function_definition DontReuse @902-913
- function_definition TestJoinConnection @915-922
- function_definition JoinConnection @924-931
- function_definition CanReuse @933-958
- function_definition CanReuseLikely @960-978
- function_definition CanDirectlyActivate @980-987
- function_definition CanDirectlyActivateReason @989-995
- function_definition IdleTime @997-1000
- function_definition TimeToLive @1004-1020
- function_definition IsAlive @1022-1034
- function_definition SetUrgentStartPreferred @1036-1044
- function_definition OnHeadersAvailable @1050-1162
- function_definition HandleTunnelResponse @1164-1227
- function_definition HandleWebSocketResponse @1229-1270
- function_definition IsReused @1272-1280
- function_definition SetIsReusedAfter @1282-1285
- function_definition TakeTransport @1287-1334
- function_definition ReadTimeoutTick @1336-1394
- function_definition UpdateTCPKeepalive @1396-1418
- function_definition GetTLSSocketControl @1420-1437
- function_definition PushBack @1439-1449
- class_specifier HttpConnectionForceIO @1451-1481
- function_definition HttpConnectionForceIO @1453-1454
- function_definition Run @1459-1474
- function_definition ~HttpConnectionForceIO @1477-1477
- function_definition GetPriority @1486-1496
- function_definition ResumeSend @1498-1509
- function_definition ResumeRecv @1511-1544
- function_definition ForceSendIO @1546-1552
- function_definition MaybeForceSendIO @1554-1572
- function_definition ForceRecv @1575-1580
- function_definition ForceSend @1583-1588
- function_definition BeginIdleMonitoring @1590-1600
- function_definition EndIdleMonitoring @1602-1612
- function_definition Version @1614-1619
- function_definition LastWriteTime @1621-1621
- function_definition CloseTransaction @1627-1677
- function_definition CheckCanWrite0RTTData @1679-1706
- function_definition OnReadSegment @1708-1748
- function_definition OnSocketWritable @1750-1900
- function_definition OnWriteSegment @1902-1929
- function_definition OnSocketReadable @1931-2020
- function_definition SetupSecondaryTLS @2022-2046
- function_definition SetInTunnel @2048-2051
- function_definition MakeConnectString @2054-2119
- function_definition StartShortLivedTCPKeepalives @2121-2192
- function_definition StartLongLivedTCPKeepalives @2194-2236
- function_definition DisableTCPKeepalives @2238-2257
- function_definition nsHttpConnection::OnInputStreamReady @2274-2321
- function_definition OnOutputStreamReady @2327-2345
- function_definition OnTransportStatus @2351-2356
- function_definition GetInterface @2363-2379
- function_definition CheckForTraffic @2381-2403
- function_definition SetEvent @2405-2434
- function_definition NoClientCertAuth @2436-2448
- function_definition GetExtendedCONNECTSupport @2450-2461
- function_definition LastTransactionExpectedNoContent @2463-2465
- function_definition SetLastTransactionExpectedNoContent @2467-2469
- function_definition IsPersistent @2471-2471
- function_definition Transaction @2473-2473
- function_definition GetSelfAddr @2475-2480
- function_definition GetPeerAddr @2482-2487
- function_definition ResolvedByTRR @2489-2495
- function_definition EffectiveTRRMode @2497-2503
- function_definition TRRSkipReason @2505-2511
- function_definition GetEchConfigUsed @2513-2519
- function_definition HandshakeDoneInternal @2521-2680
- function_definition SetTunnelSetupDone @2701-2707
- function_definition SetupProxyConnectStream @2709-2724
- function_definition ReadFromStream @2726-2732
- function_definition SendConnectRequest @2734-2740
- function_definition GetWebTransportSession @2742-2753

### netwerk/protocol/http/nsHttpConnection.h

Blob: `5b017b4eba7b5c92a5efcdc436290ded96e12e39`. Grammar: cpp. Status: contains-errors.

- include <functional> @8
- include "ARefBase.h" @10
- include "HttpConnectionBase.h" @11
- include "HttpTrafficAnalyzer.h" @12
- include "TimingStruct.h" @13
- include "TlsHandshaker.h" @14
- include "mozilla/Mutex.h" @15
- include "nsAHttpTransaction.h" @16
- include "nsCOMPtr.h" @17
- include "nsHttpConnectionInfo.h" @18
- include "nsHttpResponseHead.h" @19
- include "nsIAsyncInputStream.h" @20
- include "nsIAsyncOutputStream.h" @21
- include "nsIInterfaceRequestor.h" @22
- include "nsILoadInfo.h" @23
- include "nsISocketTransport.h" @24
- include "nsISupportsPriority.h" @25
- include "nsITimer.h" @26
- include "nsITlsHandshakeListener.h" @27
- include "nsProxyRelease.h" @28
- include "prinrval.h" @29
- class_specifier nsISocketTransport @31-31
- class_specifier nsITLSSocketControl @32-32
- class_specifier nsHttpHandler @37-37
- class_specifier ASpdySession @38-38
- class_specifier nsHttpConnection @51-405
- function_definition IsKeepAlive @90-93
- function_definition NeedSpdyTunnel @106-109
- function_definition ForcePlainText @114-114
- function_definition IsUrgentStartPreferred @116-118
- function_definition MaxBytesRead @123-123
- function_definition GetLastHttpResponseVersion @124-124
- function_definition HandshakeError @126-126
- function_definition (anonymous) @135-135
- function_definition UsingSpdy @147-147
- function_definition GetSpdyVersion @148-148
- function_definition EverUsedSpdy @149-149
- function_definition UsingHttp3 @150-150
- function_definition ReportedNPN @154-154
- function_definition ContentBytesWritten @170-170
- function_definition NoTraffic @182-185
- function_definition BytesWritten @194-194
- function_definition Transport @196-196
- function_definition IsForWebSocket @204-204
- enum_specifier TCPKeepaliveConfig @239-243
- function_definition TransactionCaps @277-277

### netwerk/protocol/http/nsHttpConnectionInfo.cpp

Blob: `cf3ccd7190b78cc52da56dfb1e98308a36920f64`. Grammar: cpp. Status: syntax-clean.

- include "HttpLog.h" @6
- include "mozilla/HashFunctions.h" @14
- include "mozilla/net/DNS.h" @15
- include "mozilla/net/NeckoChannelParams.h" @16
- include "nsComponentManagerUtils.h" @17
- include "nsHttpConnectionInfo.h" @18
- include "nsHttpHandler.h" @19
- include "nsICryptoHash.h" @20
- include "nsIDNSByTypeRecord.h" @21
- include "nsIProtocolProxyService.h" @22
- include "nsNetCID.h" @23
- include "nsProxyInfo.h" @24
- include "prnetdb.h" @25
- function_definition SHA256 @27-40
- function_definition nsHttpConnectionInfo @45-53
- function_definition nsHttpConnectionInfo @55-71
- function_definition GenerateNewWebTransportId @74-80
- function_definition Init @82-130
- function_definition BuildHashKey @132-295
- function_definition RebuildHashKey @297-320
- function_definition SetOriginServer @322-330
- function_definition Clone @335-370
- function_definition CloneAndAdoptHTTPSSVCRecord @372-434
- function_definition CloneAndAdoptPortAndAlpn @436-482
- function_definition SerializeHttpConnectionInfo @485-521
- function_definition DeserializeHttpConnectionInfoCloneArgs @525-570
- function_definition CloneAsDirectRoute @572-605
- function_definition CreateConnectUDPFallbackConnInfo @607-617
- function_definition CreateWildCard @619-638
- function_definition SetTRRMode @640-645
- function_definition SetIPv4Disabled @647-652
- function_definition SetIPv6Disabled @654-659
- function_definition SetHttp3Policy @661-666
- function_definition SetWebTransport @668-673
- function_definition SetWebTransportId @675-680
- function_definition SetTlsFlags @682-689
- function_definition UsingProxy @691-694
- function_definition HostIsLocalIPLiteral @696-704
- function_definition BuildOriginFrameHashKey @707-719

### netwerk/protocol/http/nsHttpConnectionInfo.h

Blob: `2c272acae938cd0b1cf0218a0dba16b36890f78b`. Grammar: cpp. Status: contains-errors.

- include "ARefBase.h" @8
- include "mozilla/AlreadyAddRefed.h" @9
- include "mozilla/BasePrincipal.h" @10
- include "mozilla/Logging.h" @11
- include "mozilla/net/happy_eyeballs_glue.h" @12
- include "nsCOMPtr.h" @13
- include "nsHttp.h" @14
- include "nsIRequest.h" @15
- include "nsProxyInfo.h" @16
- include "nsStringFwd.h" @17
- class_specifier nsISVCBRecord @32-32
- class_specifier HttpConnectionInfoCloneArgs @38-38
- class_specifier nsHttpTransaction @39-39
- class_specifier nsHttpConnectionInfoMutator @40-40
- struct_specifier CoalescingKey @42-45
- enum_specifier Http3Policy @51-65
- class_specifier nsHttpConnectionInfo @67-487
- function_definition ~nsHttpConnectionInfo @97-100
- enum_specifier HashKeyIndex @107-120
- function_definition UnderlyingIndex @121-123
- function_definition (anonymous) @126-126
- function_definition (anonymous) @128-128
- function_definition Origin @129-129
- function_definition OriginPort @130-130
- function_definition (anonymous) @132-132
- function_definition RoutedHost @133-133
- function_definition RoutedPort @134-134
- function_definition IsWildCard @152-152
- function_definition ProxyHost @158-160
- function_definition ProxyPort @161-161
- function_definition ProxyType @162-164
- function_definition ProxyUsername @165-167
- function_definition ProxyPassword @168-170
- function_definition ProxyFlag @171-177
- function_definition (anonymous) @179-181
- function_definition (anonymous) @182-184
- function_definition Equals @193-195
- function_definition Username @197-197
- function_definition ProxyInfo @198-198
- function_definition DefaultPort @199-201
- function_definition GetAnonymous @202-204
- function_definition AnonymousInvertedHashKey @205-209
- function_definition GetPrivate @210-212
- function_definition GetInsecureScheme @213-215
- function_definition GetNoSpdy @216-216
- function_definition GetBeConservative @217-219
- function_definition GetAnonymousAllowClientCert @220-222
- function_definition GetFallbackConnection @223-225
- function_definition GetHappyEyeballsEnabled @226-228
- function_definition GetTlsFlags @230-230
- function_definition GetIsTrrServiceChannel @231-231
- function_definition GetTRRMode @232-232
- function_definition GetIPv4Disabled @233-233
- function_definition GetIPv6Disabled @234-234
- function_definition GetHttp3Policy @236-236
- function_definition GetHttp3Disabled @237-239
- function_definition GetHttp3Only @240-240
- function_definition GetWebTransport @242-242
- function_definition GetWebTransportId @243-243
- function_definition (anonymous) @245-245
- function_definition (anonymous) @246-246
- function_definition (anonymous) @247-247
- function_definition (anonymous) @249-251
- function_definition UsingHttpProxy @257-257
- function_definition UsingOnlyHttpProxy @260-260
- function_definition UsingHttpsProxy @263-263
- function_definition EndToEndSSL @266-266
- function_definition FirstHopSSL @270-270
- function_definition UsingConnect @274-274
- function_definition GetLessThanTls13 @279-279
- function_definition IsHttp3 @280-280
- function_definition IsHttp3ProxyConnection @281-281
- function_definition HasIPHintAddress @282-282
- function_definition (anonymous) @284-284
- function_definition SetAnonymous @293-295
- function_definition SetPrivate @296-298
- function_definition SetInsecureScheme @299-301
- function_definition SetNoSpdy @302-308
- function_definition SetBeConservative @309-311
- function_definition SetAnonymousAllowClientCert @312-314
- function_definition SetFallbackConnection @315-317
- function_definition SetHappyEyeballsEnabled @318-324
- function_definition SetIsTrrServiceChannel @326-328
- function_definition SetLessThanTls13 @335-337
- function_definition SetHasIPHintAddress @338-338
- function_definition SetEchConfig @339-339
- function_definition GetHashCharAt @346-348
- function_definition SetHashCharAt @349-351
- function_definition nsHttpConnectionInfoMutator @398-405
- class_specifier MOZ_STACK_CLASS @398-398
- function_definition (anonymous) @406-409
- function_definition (anonymous) @410-413
- function_definition (anonymous) @414-417
- function_definition (anonymous) @418-421
- function_definition (anonymous) @422-425
- function_definition (anonymous) @426-429
- function_definition (anonymous) @430-433
- function_definition (anonymous) @434-437
- function_definition (anonymous) @438-441
- function_definition (anonymous) @442-445
- function_definition (anonymous) @446-449
- function_definition (anonymous) @450-453
- function_definition (anonymous) @454-457
- function_definition (anonymous) @458-461
- function_definition (anonymous) @462-465
- function_definition (anonymous) @466-469
- function_definition (anonymous) @470-473
- function_definition (anonymous) @474-477
- function_definition Finalize @479-479
- function_definition nsHttpConnectionInfoMutator @482-484
- function_definition Mutate @489-491

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
