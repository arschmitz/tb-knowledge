<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["dom/media/gmp/GMPService.h", "dom/media/gmp/GMPServiceChild.cpp", "dom/media/gmp/GMPServiceChild.h", "dom/media/gmp/GMPServiceParent.cpp", "dom/media/gmp/GMPServiceParent.h", "dom/media/gmp/GMPSharedMemManager.cpp", "dom/media/gmp/GMPSharedMemManager.h", "dom/media/gmp/GMPStorage.h", "dom/media/gmp/GMPStorageChild.cpp", "dom/media/gmp/GMPStorageChild.h", "dom/media/gmp/GMPStorageParent.cpp", "dom/media/gmp/GMPStorageParent.h", "dom/media/gmp/GMPTimerChild.cpp", "dom/media/gmp/GMPTimerChild.h", "dom/media/gmp/GMPTimerParent.cpp", "dom/media/gmp/GMPTimerParent.h", "dom/media/gmp/GMPUtils.cpp", "dom/media/gmp/GMPUtils.h", "dom/media/gmp/GMPVideoDecoderChild.cpp", "dom/media/gmp/GMPVideoDecoderChild.h", "dom/media/gmp/GMPVideoDecoderParent.cpp", "dom/media/gmp/GMPVideoDecoderParent.h", "dom/media/gmp/GMPVideoDecoderProxy.h", "dom/media/gmp/GMPVideoEncodedFrameImpl.cpp", "dom/media/gmp/GMPVideoEncodedFrameImpl.h", "dom/media/gmp/GMPVideoEncoderChild.cpp", "dom/media/gmp/GMPVideoEncoderChild.h", "dom/media/gmp/GMPVideoEncoderParent.cpp", "dom/media/gmp/GMPVideoEncoderParent.h", "dom/media/gmp/GMPVideoEncoderProxy.h", "dom/media/gmp/GMPVideoHost.cpp", "dom/media/gmp/GMPVideoHost.h", "dom/media/gmp/GMPVideoPlaneImpl.cpp", "dom/media/gmp/GMPVideoPlaneImpl.h", "dom/media/gmp/GMPVideoi420FrameImpl.cpp", "dom/media/gmp/GMPVideoi420FrameImpl.h", "dom/media/gmp/gmp-api/gmp-entrypoints.h", "dom/media/gmp/gmp-api/gmp-errors.h", "dom/media/gmp/gmp-api/gmp-platform.h", "dom/media/gmp/gmp-api/gmp-storage.h", "dom/media/gmp/gmp-api/gmp-video-codec.h", "dom/media/gmp/gmp-api/gmp-video-decode.h", "dom/media/gmp/gmp-api/gmp-video-encode.h", "dom/media/gmp/gmp-api/gmp-video-frame-encoded.h", "dom/media/gmp/gmp-api/gmp-video-frame-i420.h", "dom/media/gmp/gmp-api/gmp-video-frame.h", "dom/media/gmp/gmp-api/gmp-video-host.h", "dom/media/gmp/gmp-api/gmp-video-plane.h", "dom/media/gmp/rlz/lib/assert.h", "dom/media/gmp/rlz/lib/crc8.cc", "dom/media/gmp/rlz/lib/crc8.h", "dom/media/gmp/rlz/lib/machine_id.cc", "dom/media/gmp/rlz/lib/machine_id.h", "dom/media/gmp/rlz/lib/string_utils.cc", "dom/media/gmp/rlz/lib/string_utils.h", "dom/media/gmp/rlz/mac/lib/machine_id_mac.cc", "dom/media/gmp/rlz/win/lib/machine_id_win.cc", "dom/media/gmp/widevine-adapter/WidevineFileIO.cpp", "dom/media/gmp/widevine-adapter/WidevineFileIO.h", "dom/media/gmp/widevine-adapter/WidevineUtils.cpp", "dom/media/gmp/widevine-adapter/WidevineUtils.h", "dom/media/gmp/widevine-adapter/WidevineVideoFrame.cpp", "dom/media/gmp/widevine-adapter/WidevineVideoFrame.h", "dom/media/gmp/widevine-adapter/content_decryption_module.h", "dom/media/gmp/widevine-adapter/content_decryption_module_export.h", "dom/media/gmp/widevine-adapter/content_decryption_module_ext.h", "dom/media/gtest/GMPTestMonitor.h", "dom/media/gtest/MediaSinkTestUtils.h", "dom/media/gtest/MockDecoderModule.h", "dom/media/gtest/MockGraphInterface.h", "dom/media/gtest/MockMediaDataDemuxer.h", "dom/media/gtest/MockMediaDecoderOwner.h", "dom/media/gtest/MockMediaResource.cpp", "dom/media/gtest/MockMediaResource.h", "dom/media/gtest/TestADTSDemuxer.cpp", "dom/media/gtest/TestAOMDecoder.cpp", "dom/media/gtest/TestAV1FmtpParser.cpp", "dom/media/gtest/TestAVSync.cpp", "dom/media/gtest/TestAppleVTColorSpace.cpp", "dom/media/gtest/TestAsyncLogger.cpp", "dom/media/gtest/TestAudioBuffer.cpp", "dom/media/gtest/TestAudioBufferAddWithScale.cpp", "dom/media/gtest/TestAudioBuffers.cpp", "dom/media/gtest/TestAudioCallbackDriver.cpp", "dom/media/gtest/TestAudioClock.cpp", "dom/media/gtest/TestAudioCompactor.cpp", "dom/media/gtest/TestAudioConfig.cpp", "dom/media/gtest/TestAudioConverter.cpp", "dom/media/gtest/TestAudioData.cpp", "dom/media/gtest/TestAudioDecoderInputTrack.cpp", "dom/media/gtest/TestAudioDeviceEnumerator.cpp", "dom/media/gtest/TestAudioInputProcessing.cpp", "dom/media/gtest/TestAudioInputSource.cpp", "dom/media/gtest/TestAudioMixer.cpp", "dom/media/gtest/TestAudioPacketizer.cpp", "dom/media/gtest/TestAudioRingBuffer.cpp", "dom/media/gtest/TestAudioSampleFormat.cpp", "dom/media/gtest/TestAudioSegment.cpp", "dom/media/gtest/TestAudioSinkWrapper.cpp", "dom/media/gtest/TestAudioStream.cpp", "dom/media/gtest/TestAudioTrackEncoder.cpp", "dom/media/gtest/TestAudioTrackGraph.cpp", "dom/media/gtest/TestBitWriter.cpp", "dom/media/gtest/TestBlankVideoDataCreator.cpp", "dom/media/gtest/TestBufferMediaResource.cpp", "dom/media/gtest/TestBufferReader.cpp", "dom/media/gtest/TestCDMStorage.cpp", "dom/media/gtest/TestCamerasParent.cpp", "dom/media/gtest/TestCubebInputStream.cpp", "dom/media/gtest/TestDataMutex.cpp", "dom/media/gtest/TestDecodedStream.cpp", "dom/media/gtest/TestDeviceInputTrack.cpp", "dom/media/gtest/TestDriftCompensation.cpp", "dom/media/gtest/TestFFmpegDecodeStats.cpp", "dom/media/gtest/TestGMPCrossOrigin.cpp", "dom/media/gtest/TestGMPPluginScan.cpp", "dom/media/gtest/TestGMPRemoveAndDelete.cpp", "dom/media/gtest/TestGMPUtils.cpp", "dom/media/gtest/TestGMPVideoEncodedFrame.cpp", "dom/media/gtest/TestGMPVideoi420Frame.cpp", "dom/media/gtest/TestGroupId.cpp", "dom/media/gtest/TestH264FmtpParser.cpp", "dom/media/gtest/TestHDRUtils.cpp", "dom/media/gtest/TestImageConversion.cpp", "dom/media/gtest/TestIntervalSet.cpp", "dom/media/gtest/TestMP3Demuxer.cpp", "dom/media/gtest/TestMP4Demuxer.cpp", "dom/media/gtest/TestMediaCapabilities.cpp", "dom/media/gtest/TestMediaCodecsSupport.cpp", "dom/media/gtest/TestMediaDataDecoder.cpp", "dom/media/gtest/TestMediaDataEncoder.cpp", "dom/media/gtest/TestMediaEventSource.cpp", "dom/media/gtest/TestMediaFormatReader.cpp", "dom/media/gtest/TestMediaInfo.cpp", "dom/media/gtest/TestMediaMIMETypes.cpp", "dom/media/gtest/TestMediaQueue.cpp", "dom/media/gtest/TestMediaSpan.cpp", "dom/media/gtest/TestMediaUtils.cpp", "dom/media/gtest/TestMuxer.cpp", "dom/media/gtest/TestOfflineClockDriver.cpp", "dom/media/gtest/TestOggWriter.cpp", "dom/media/gtest/TestOpusParser.cpp", "dom/media/gtest/TestPDMFactorySupport.cpp", "dom/media/gtest/TestPacer.cpp", "dom/media/gtest/TestQuantizableBuffer.cpp", "dom/media/gtest/TestRTCStatsTimestampMaker.cpp", "dom/media/gtest/TestRemoteImageHolder.cpp", "dom/media/gtest/TestRust.cpp", "dom/media/gtest/TestSimpleMap.cpp", "dom/media/gtest/TestSpeechModelMapping.cpp"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/dom native and TypeScript syntax map 32

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### dom/media/gmp/GMPService.h

Blob: `1518d36addcee1a6651830417e6b55dded76abcc`. Grammar: cpp. Status: contains-errors.

- include "GMPContentParent.h" @8
- include "GMPCrashHelper.h" @9
- include "gmp-video-codec.h" @10
- include "mozIGeckoMediaPluginService.h" @11
- include "mozilla/Atomics.h" @12
- include "mozilla/MozPromise.h" @13
- include "mozilla/gmp/GMPTypes.h" @14
- include "nsCOMPtr.h" @15
- include "nsClassHashtable.h" @16
- include "nsIObserver.h" @17
- include "nsString.h" @18
- include "nsTArray.h" @19
- class_specifier nsIAsyncShutdownClient @21-21
- class_specifier nsIRunnable @22-22
- class_specifier nsISerialEventTarget @23-23
- class_specifier nsIThread @24-24
- struct_specifier already_AddRefed @27-27
- class_specifier GMPCrashHelper @31-31
- class_specifier MediaResult @32-32
- class_specifier GeckoMediaPluginService @46-125
- function_definition XPCOMWillShutdownReceived @84-84
- function_definition AssertOnGMPThread @90-95

### dom/media/gmp/GMPServiceChild.cpp

Blob: `f7c5130f35a1ee15fcafc280181e7570e3e8316b`. Grammar: cpp. Status: contains-errors.

- include "GMPServiceChild.h" @5
- include "GMPLog.h" @7
- include "GMPParent.h" @8
- include "base/task.h" @9
- include "mozIGeckoMediaPluginChromeService.h" @10
- include "mozilla/ClearOnShutdown.h" @11
- include "mozilla/SchedulerGroup.h" @12
- include "mozilla/StaticMutex.h" @13
- include "mozilla/StaticPtr.h" @14
- include "mozilla/SyncRunnable.h" @15
- include "mozilla/dom/ContentChild.h" @16
- include "mozilla/ipc/Endpoint.h" @17
- include "nsCOMPtr.h" @18
- include "nsComponentManagerUtils.h" @19
- include "nsFmtString.h" @20
- include "nsIObserverService.h" @21
- include "nsReadableUtils.h" @22
- include "nsXPCOMPrivate.h" @23
- include "runnable_utils.h" @24
- function_definition GetSingleton @33-46
- function_definition Init @48-63
- function_definition ~GeckoMediaPluginServiceChild @68-70
- function_definition GetContentParent @72-211
- struct_specifier GMPCapabilityAndVersion @216-250
- function_definition GMPCapabilityAndVersion @217-227
- function_definition ToString @229-245
- function_definition GMPCapabilitiesToString @255-260
- function_definition UpdateGMPCapabilities @263-290
- function_definition BeginShutdown @292-313
- function_definition HasPluginForAPI @315-335
- function_definition FindPluginDirectoryForAPI @337-342
- function_definition GetNodeId @344-377
- function_definition Observe @379-405
- function_definition GetServiceChild @407-436
- function_definition SetServiceChild @438-452
- function_definition RemoveGMPContentParent @454-473
- function_definition AddShutdownBlocker @475-501
- function_definition RemoveShutdownBlocker @503-510
- function_definition RemoveShutdownBlockerIfNeeded @512-530
- function_definition GetBridgedGMPContentParent @532-544
- function_definition RemoveGMPContentParent @546-555
- function_definition HasAlreadyBridgedTo @557-559
- function_definition GetAndBlockAlreadyBridgedTo @561-570
- class_specifier OpenPGMPServiceChild @572-597
- function_definition OpenPGMPServiceChild @574-578
- function_definition Run @580-592
- function_definition Create @600-619
- function_definition RecvBeginShutdown @621-629
- function_definition HaveContentParents @631-633

### dom/media/gmp/GMPServiceChild.h

Blob: `3464c886297d09071c6fdb686edc26abeba6a809`. Grammar: cpp. Status: contains-errors.

- include "GMPService.h" @8
- include "MediaResult.h" @9
- include "base/process.h" @10
- include "mozilla/MozPromise.h" @11
- include "mozilla/dom/PContent.h" @12
- include "mozilla/gmp/PGMPServiceChild.h" @13
- include "mozilla/media/MediaUtils.h" @14
- include "nsRefPtrHashtable.h" @15
- class_specifier GMPContentParent @19-19
- class_specifier GMPContentParentCloseBlocker @20-20
- class_specifier GMPServiceChild @21-21
- class_specifier GeckoMediaPluginServiceChild @23-131
- function_definition InitializePlugins @55-57
- class_specifier GMPServiceChild @137-173
- function_definition GMPServiceChild @143-144
- function_definition Service @163-163
- function_definition ~GMPServiceChild @166-166

### dom/media/gmp/GMPServiceParent.cpp

Blob: `5c49c28804764c0b55c0531c9306e1a6182a72cc`. Grammar: cpp. Status: contains-errors.

- include "GMPServiceParent.h" @5
- include "GMPDecoderModule.h" @7
- include "GMPLog.h" @8
- include "GMPParent.h" @9
- include "GMPVideoDecoderParent.h" @10
- include "base/task.h" @11
- include "mozilla/ClearOnShutdown.h" @12
- include "mozilla/Logging.h" @13
- include "mozilla/Preferences.h" @14
- include "mozilla/SchedulerGroup.h" @15
- include "mozilla/dom/ContentParent.h" @16
- include "mozilla/ipc/Endpoint.h" @17
- include "mozilla/ipc/GeckoChildProcessHost.h" @18
- include "nsFmtString.h" @19
- include "nsThreadUtils.h" @20
- include "mozilla/SandboxInfo.h" @22
- include "VideoUtils.h" @24
- include "mozilla/AppShutdown.h" @25
- include "mozilla/Services.h" @26
- include "mozilla/SpinEventLoopUntil.h" @27
- include "mozilla/StaticPrefs_media.h" @28
- include "mozilla/SyncRunnable.h" @29
- include "mozilla/UntrustedModulesData.h" @31
- include "nsAppDirectoryServiceDefs.h" @33
- include "nsComponentManagerUtils.h" @34
- include "nsDirectoryServiceDefs.h" @35
- include "nsDirectoryServiceUtils.h" @36
- include "nsHashKeys.h" @37
- include "nsIFile.h" @38
- include "nsIObserverService.h" @39
- include "nsIXULRuntime.h" @40
- include "nsNativeCharsetUtils.h" @41
- include "nsNetUtil.h" @42
- include "nsXPCOMPrivate.h" @43
- include "prio.h" @44
- include "runnable_utils.h" @45
- include "mozilla/dom/MediaKeys.h" @48
- include "mozilla/MFCDMParent.h" @52
- include "media/NdkMediaCrypto.h" @56
- include "media/NdkMediaDrm.h" @57
- include "mozilla/gfx/gfxVars.h" @58
- function_definition GetSingleton @70-83
- function_definition GeckoMediaPluginServiceParent @89-96
- function_definition ~GeckoMediaPluginServiceParent @98-100
- function_definition Init @102-157
- function_definition CloneAndAppend @159-172
- function_definition GMPPlatformString @174-202
- function_definition InitStorage @204-238
- function_definition Observe @240-383
- function_definition OnPreferenceChanged @385-393
- function_definition EnsureInitialized @395-404
- function_definition GetContentParent @406-457
- function_definition InitializePlugins @459-483
- function_definition NotifySyncShutdownComplete @485-488
- function_definition IsShuttingDown @490-493
- function_definition UnloadPlugins @495-532
- function_definition CrashPlugins @534-542
- function_definition LoadFromEnvironment @544-617
- class_specifier NotifyObserversTask @619-638
- function_definition NotifyObserversTask @621-622
- function_definition Run @623-632
- function_definition ~NotifyObserversTask @635-635
- function_definition PathRunnable::Run @640-647
- function_definition UpdateContentProcessGMPCapabilities @649-719
- function_definition SendFlushFOGData @721-757
- function_definition SendGetUntrustedModulesData @760-797
- function_definition SendUnblockUntrustedModulesThread @799-817
- function_definition TestTriggerMetrics @820-862
- function_definition AsyncAddPluginDirectory @864-898
- function_definition AddPluginDirectory @900-906
- function_definition RemovePluginDirectory @908-914
- function_definition RemoveAndDeletePluginDirectory @916-923
- function_definition HasPluginForAPI @925-947
- function_definition FindPluginDirectoryForAPI @949-978
- function_definition EnsurePluginsOnDiskScanned @980-1048
- function_definition FindPluginForAPIFrom @1050-1065
- function_definition SelectPluginForAPI @1067-1117
- function_definition CreateGMPParent @1119-1133
- function_definition ClonePlugin @1135-1148
- function_definition AddOnGMPThread @1150-1203
- function_definition RemoveOnGMPThread @1205-1273
- function_definition Dummy @1276-1279
- function_definition PluginTerminated @1281-1297
- function_definition ReAddOnGMPThread @1299-1325
- function_definition GetStorageDir @1327-1333
- function_definition WriteToFile @1335-1361
- function_definition ReadFromFile @1363-1397
- function_definition ReadSalt @1399-1401
- function_definition GetMemoryStorageFor @1403-1407
- function_definition IsPersistentStorageAllowed @1409-1420
- function_definition GetNodeId @1422-1566
- function_definition GetNodeId @1568-1576
- function_definition GetNodeId @1578-1589
- function_definition ExtractHostName @1591-1609
- function_definition MatchOrigin @1617-1637
- function_definition MatchBaseDomain @1639-1662
- function_definition KillPlugins @1665-1687
- struct_specifier NodeFilter @1689-1697
- function_definition NodeFilter @1690-1690
- function_definition operator() @1691-1693
- function_definition ClearNodeIdAndPlugin @1699-1714
- function_definition ClearNodeIdAndPlugin @1716-1773
- function_definition ForgetThisSiteOnGMPThread @1775-1795
- struct_specifier OriginFilter @1781-1792
- function_definition OriginFilter @1782-1784
- function_definition operator() @1785-1787
- function_definition ForgetThisBaseDomainOnGMPThread @1797-1815
- struct_specifier BaseDomainFilter @1803-1812
- function_definition BaseDomainFilter @1804-1805
- function_definition operator() @1806-1808
- function_definition ClearRecentHistoryOnGMPThread @1817-1880
- struct_specifier MTimeFilter @1822-1873
- function_definition MTimeFilter @1823-1823
- function_definition IsModifiedAfter @1826-1839
- function_definition operator() @1842-1869
- function_definition ForgetThisSite @1882-1894
- function_definition ForgetThisSiteNative @1896-1905
- function_definition ForgetThisBaseDomain @1907-1913
- function_definition ForgetThisBaseDomainNative @1915-1923
- function_definition IsNodeIdValid @1925-1927
- function_definition ServiceUserCreated @1930-1937
- function_definition ServiceUserDestroyed @1939-1946
- function_definition ClearTemporaryStorage @1948-1954
- function_definition ClearStorage @1956-1983
- function_definition GetById @1985-1994
- function_definition GMPServiceParent @1996-2006
- function_definition ~GMPServiceParent @2008-2011
- function_definition BeginShutdown @2013-2016
- function_definition RecvLaunchGMP @2018-2102
- function_definition RecvGetGMPNodeId @2104-2116
- class_specifier OpenPGMPServiceParent @2118-2137
- function_definition OpenPGMPServiceParent @2120-2126
- function_definition Run @2128-2131
- function_definition Create @2140-2171

### dom/media/gmp/GMPServiceParent.h

Blob: `390ef75c4e4cee813722a2345cdd67f283862f1f`. Grammar: cpp. Status: contains-errors.

- include "GMPService.h" @8
- include "GMPStorage.h" @9
- include "mozIGeckoMediaPluginChromeService.h" @10
- include "mozilla/MozPromise.h" @11
- include "mozilla/dom/ContentParent.h" @12
- include "mozilla/gmp/PGMPParent.h" @13
- include "mozilla/gmp/PGMPServiceParent.h" @14
- include "mozilla/media/MediaUtils.h" @15
- include "nsClassHashtable.h" @16
- include "nsIAsyncShutdown.h" @17
- include "nsNetUtil.h" @18
- include "nsRefPtrHashtable.h" @19
- include "nsTHashMap.h" @20
- include "nsThreadUtils.h" @21
- struct_specifier already_AddRefed @24-24
- class_specifier OriginAttributesPattern @29-29
- class_specifier GMPParent @33-33
- class_specifier GMPServiceParent @34-34
- class_specifier GeckoMediaPluginServiceParent @36-246
- class_specifier Observer @105-105
- struct_specifier DirectoryFilter @131-134
- function_definition ~DirectoryFilter @133-133
- class_specifier PathRunnable @174-197
- enum_specifier EOperation @176-179
- function_definition PathRunnable @181-188
- class_specifier MainThreadOnly @203-213
- function_definition MainThreadOnly @205-205
- function_definition (anonymous) @206-209
- class_specifier GMPServiceParent @260-305

### dom/media/gmp/GMPSharedMemManager.cpp

Blob: `c5e4e772bab5c08e1276cf93167f3b3fbb5ce9cf`. Grammar: cpp. Status: syntax-clean.

- include "GMPSharedMemManager.h" @5
- include "mozilla/ipc/SharedMemoryMapping.h" @7
- function_definition ~GMPSharedMemManager @11-17
- function_definition PurgeSmallerShmem @19-32
- function_definition MgrTakeShmem @34-45
- function_definition MgrTakeShmem @47-60
- function_definition MgrGiveShmem @62-81
- function_definition MgrPurgeShmems @83-96

### dom/media/gmp/GMPSharedMemManager.h

Blob: `62b871f1da7662ca67e5e5e9e19ba89abeae62e4`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/ipc/Shmem.h" @8
- include "nsTArray.h" @9
- class_specifier GMPVideoi420FrameImpl @13-13
- enum_specifier GMPSharedMemClass @15-15
- class_specifier GMPSharedMemManager @17-44
- function_definition GMPSharedMemManager @19-19
- function_definition MgrAllocShmem @28-28
- function_definition MgrDecodedFrameDestroyed @31-31

### dom/media/gmp/GMPStorage.h

Blob: `118e19dd2d02a3bac24e659869c47b73dfc3af16`. Grammar: cpp. Status: contains-errors.

- include "gmp-storage.h" @8
- include "mozilla/AlreadyAddRefed.h" @9
- include "nsISupportsImpl.h" @10
- include "nsString.h" @11
- include "nsTArray.h" @12
- class_specifier GMPStorage @16-30
- function_definition ~GMPStorage @29-29

### dom/media/gmp/GMPStorageChild.cpp

Blob: `125519623052613bdf343d55b1122da22d6334eb`. Grammar: cpp. Status: syntax-clean.

- include "GMPStorageChild.h" @5
- include "GMPChild.h" @7
- include "base/task.h" @8
- include "gmp-storage.h" @9
- function_definition ToArray @26-30
- function_definition GMPRecordImpl @32-34
- function_definition GetOwner @36-39
- function_definition Open @41-48
- function_definition OpenComplete @50-58
- function_definition Read @60-67
- function_definition ReadComplete @69-78
- function_definition Write @80-87
- function_definition WriteComplete @89-97
- function_definition Close @99-119
- function_definition DestroyOwner @121-124
- function_definition GMPStorageChild @126-128
- function_definition CreateRecord @130-155
- function_definition HasRecord @157-159
- function_definition GetRecord @161-170
- function_definition Open @172-187
- function_definition Read @189-204
- function_definition Write @206-226
- function_definition Close @228-241
- function_definition RecvOpenComplete @243-249
- function_definition RecvReadComplete @251-258
- function_definition RecvWriteComplete @260-266
- function_definition RecvShutdown @268-275
- function_definition ActorDestroy @277-290

### dom/media/gmp/GMPStorageChild.h

Blob: `81faa20924f827f58a0424dd37e36be119aa3051`. Grammar: cpp. Status: contains-errors.

- include "gmp-platform.h" @8
- include "gmp-storage.h" @9
- include "mozilla/Mutex.h" @10
- include "mozilla/RecursiveMutex.h" @11
- include "mozilla/gmp/PGMPStorageChild.h" @12
- include "nsRefPtrHashtable.h" @13
- include "nsTHashtable.h" @14
- class_specifier GMPChild @18-18
- class_specifier GMPStorageChild @19-19
- class_specifier GMPRecordImpl @21-50
- function_definition (anonymous) @36-36
- function_definition ~GMPRecordImpl @45-45
- class_specifier GMPStorageChild @52-97
- function_definition ~GMPStorageChild @79-79

### dom/media/gmp/GMPStorageParent.cpp

Blob: `1565224c8fcdc7015d58c9f52f800bace0ee78c8`. Grammar: cpp. Status: syntax-clean.

- include "GMPStorageParent.h" @5
- include "GMPParent.h" @7
- include "gmp-storage.h" @8
- function_definition GMPStorageParent @26-28
- function_definition Init @30-60
- function_definition RecvOpen @62-104
- function_definition RecvRead @106-132
- function_definition RecvWrite @134-166
- function_definition RecvClose @168-180
- function_definition ActorDestroy @182-186
- function_definition Shutdown @188-198

### dom/media/gmp/GMPStorageParent.h

Blob: `b80822999c8e7757eba3a519c7590cd7018d5783`. Grammar: cpp. Status: contains-errors.

- include "GMPParent.h" @8
- include "GMPStorage.h" @9
- include "mozilla/gmp/PGMPStorageParent.h" @10
- class_specifier GMPStorageParent @14-41
- function_definition ~GMPStorageParent @33-33

### dom/media/gmp/GMPTimerChild.cpp

Blob: `ef92b8ed2cc1e363162ff3479953ee2131990fb3`. Grammar: cpp. Status: syntax-clean.

- include "GMPTimerChild.h" @5
- include "GMPChild.h" @7
- include "GMPPlatform.h" @8
- function_definition GMPTimerChild @14-17
- function_definition ~GMPTimerChild @19-21
- function_definition SetTimer @23-45
- function_definition RecvTimerExpired @47-57

### dom/media/gmp/GMPTimerChild.h

Blob: `c23b476bcd55468672f6c179c4a29838f5e9c0eb`. Grammar: cpp. Status: contains-errors.

- include "gmp-errors.h" @8
- include "gmp-platform.h" @9
- include "mozilla/Monitor.h" @10
- include "mozilla/gmp/PGMPTimerChild.h" @11
- include "nsHashKeys.h" @12
- include "nsTHashMap.h" @13
- class_specifier GMPChild @17-17
- class_specifier GMPTimerChild @19-40

### dom/media/gmp/GMPTimerParent.cpp

Blob: `cd784a990dd7c06cf24307b91c230abcd96abda7`. Grammar: cpp. Status: syntax-clean.

- include "GMPTimerParent.h" @5
- include <memory> @7
- include "GMPLog.h" @9
- include "nsComponentManagerUtils.h" @10
- function_definition GMPTimerParent @23-24
- function_definition RecvSetTimer @26-52
- function_definition Shutdown @54-67
- function_definition ActorDestroy @69-74
- function_definition GMPTimerExpired @77-84
- function_definition TimerExpired @86-100

### dom/media/gmp/GMPTimerParent.h

Blob: `328fb452d674535b276500cd11881bf3798e331f`. Grammar: cpp. Status: contains-errors.

- include "mozilla/Monitor.h" @8
- include "mozilla/gmp/PGMPTimerParent.h" @9
- include "nsCOMPtr.h" @10
- include "nsITimer.h" @11
- include "nsTHashSet.h" @12
- class_specifier GMPTimerParent @16-51
- function_definition ~GMPTimerParent @31-31
- struct_specifier Context @35-42
- function_definition Context @36-36

### dom/media/gmp/GMPUtils.cpp

Blob: `87f34a65b0ec0aa3c32a79235dcdcc1c9e5aca39`. Grammar: cpp. Status: syntax-clean.

- include "GMPUtils.h" @5
- include <bit> @7
- include "GMPLog.h" @9
- include "GMPService.h" @10
- include "VideoLimits.h" @11
- include "gmp-video-frame-encoded.h" @12
- include "mozIGeckoMediaPluginService.h" @13
- include "mozilla/Base64.h" @14
- include "mozilla/EndianUtils.h" @15
- include "nsCOMPtr.h" @16
- include "nsCRTGlue.h" @17
- include "nsDirectoryServiceDefs.h" @18
- include "nsIConsoleService.h" @19
- include "nsIFile.h" @20
- include "nsLiteralString.h" @21
- include "prio.h" @22
- function_definition SplitAt @26-34
- function_definition ToHexString @36-48
- function_definition ToHexString @50-52
- function_definition FileExists @54-57
- function_definition DirectoryEnumerator @59-62
- function_definition Next @64-91
- function_definition ReadIntoArray @93-117
- function_definition ReadIntoString @119-127
- function_definition Init @129-164
- function_definition Contains @166-170
- function_definition Get @172-181
- function_definition HaveGMPFor @183-195
- function_definition IsOnGMPThread @197-206
- function_definition LogToConsole @208-217
- function_definition GetGMPThread @219-225
- function_definition Align16 @227-230
- function_definition I420FrameBufferSizePadded @232-240
- function_definition SizeNumBytes @242-257
- function_definition AdjustOpenH264NALUSequence @259-343
- function_definition AdjustOpenH264NALUSequence @345-357
- function_definition ToMediaResult @359-372

### dom/media/gmp/GMPUtils.h

Blob: `ca25619bf3b2611f6d45d9e984d840794320ea7d`. Grammar: cpp. Status: syntax-clean.

- include "MediaResult.h" @8
- include "gmp-errors.h" @9
- include "gmp-video-codec.h" @10
- include "mozilla/AbstractThread.h" @11
- include "mozilla/UniquePtr.h" @12
- include "nsCOMPtr.h" @13
- include "nsClassHashtable.h" @14
- include "nsStringFwd.h" @15
- include "nsTArray.h" @16
- class_specifier GMPVideoEncodedFrame @21-21
- class_specifier nsIFile @22-22
- class_specifier nsIDirectoryEnumerator @23-23
- struct_specifier DestroyPolicy @28-30
- function_definition operator() @29-29
- class_specifier DirectoryEnumerator @45-59
- enum_specifier Mode @47-50
- class_specifier GMPInfoFileParser @61-69

### dom/media/gmp/GMPVideoDecoderChild.cpp

Blob: `7fc72ff521e4991b080b8c23353b7b93ea4041c0`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoDecoderChild.h" @5
- include "GMPContentChild.h" @7
- include "GMPPlatform.h" @8
- include "GMPVideoEncodedFrameImpl.h" @9
- include "GMPVideoi420FrameImpl.h" @10
- include "mozilla/StaticPrefs_media.h" @11
- include "nsProxyRelease.h" @12
- include "nsThreadUtils.h" @13
- include "runnable_utils.h" @14
- function_definition GMPVideoDecoderChild @18-21
- function_definition ~GMPVideoDecoderChild @23-32
- function_definition MgrIsOnOwningThread @34-36
- function_definition Init @38-43
- function_definition Decoded @45-77
- function_definition ReceivedDecodedReferenceFrame @79-88
- function_definition ReceivedDecodedFrame @90-98
- function_definition InputDataExhausted @100-108
- function_definition DrainComplete @110-130
- function_definition ResetComplete @132-152
- function_definition Error @154-162
- function_definition RecvInitDecode @164-176
- function_definition RecvGiveShmem @178-182
- function_definition RecvDecode @184-208
- function_definition RecvReset @210-226
- function_definition RecvDrain @228-244
- function_definition ActorDestroy @246-252

### dom/media/gmp/GMPVideoDecoderChild.h

Blob: `9e4ee1cb092b3f650ff7b22552202e4818807ba7`. Grammar: cpp. Status: syntax-clean.

- include "GMPSharedMemManager.h" @8
- include "GMPVideoHost.h" @9
- include "gmp-video-decode.h" @10
- include "mozilla/gmp/GMPTypes.h" @11
- include "mozilla/gmp/PGMPVideoDecoderChild.h" @12
- include "nsString.h" @13
- class_specifier GMPContentChild @17-17
- class_specifier GMPVideoDecoderChild @19-71
- function_definition MgrCanSend @43-43
- function_definition MgrDeallocShmem @45-49

### dom/media/gmp/GMPVideoDecoderParent.cpp

Blob: `5c1a9d9d69af2dc0d7db04e42b254463d62907e3`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoDecoderParent.h" @5
- include "GMPContentParent.h" @7
- include "GMPLog.h" @8
- include "GMPMessageUtils.h" @9
- include "GMPUtils.h" @10
- include "GMPVideoEncodedFrameImpl.h" @11
- include "GMPVideoi420FrameImpl.h" @12
- include "mozilla/gmp/GMPTypes.h" @13
- include "nsAutoRef.h" @14
- include "nsPrintfCString.h" @15
- include "nsThreadUtils.h" @16
- function_definition GMPVideoDecoderParent @30-42
- function_definition ~GMPVideoDecoderParent @44-44
- function_definition MgrIsOnOwningThread @46-48
- function_definition Close @51-69
- function_definition InitDecode @71-100
- function_definition Decode @102-151
- function_definition Reset @153-186
- function_definition CancelResetCompleteTimeout @188-193
- function_definition Drain @195-214
- function_definition GetDisplayName @216-223
- function_definition Shutdown @226-252
- function_definition ActorDestroy @255-280
- function_definition HandleDecoded @282-312
- function_definition RecvReturnShmem @314-318
- function_definition RecvDecodedShmem @320-330
- function_definition RecvDecodedData @332-343
- function_definition RecvReceivedDecodedReferenceFrame @345-353
- function_definition RecvReceivedDecodedFrame @355-362
- function_definition RecvInputDataExhausted @364-373
- function_definition RecvDrainComplete @375-391
- function_definition RecvResetComplete @393-407
- function_definition RecvError @409-423
- function_definition RecvShutdown @425-430
- function_definition UnblockResetAndDrain @432-452

### dom/media/gmp/GMPVideoDecoderParent.h

Blob: `02a4795d628fc4f65eefcc7c00bcdf0d4464c426`. Grammar: cpp. Status: contains-errors.

- include "GMPCrashHelperHolder.h" @8
- include "GMPMessageUtils.h" @9
- include "GMPSharedMemManager.h" @10
- include "GMPUtils.h" @11
- include "GMPVideoDecoderProxy.h" @12
- include "GMPVideoHost.h" @13
- include "VideoUtils.h" @14
- include "gmp-video-decode.h" @15
- include "mozilla/RefPtr.h" @16
- include "mozilla/gmp/PGMPVideoDecoderParent.h" @17
- class_specifier GMPContentParent @21-21
- class_specifier GMPVideoDecoderParent @23-109
- function_definition GetPluginId @50-50
- function_definition GetPluginType @51-51
- function_definition MgrAllocShmem @55-57
- function_definition MgrDeallocShmem @59-63
- function_definition MgrCanSend @66-66

### dom/media/gmp/GMPVideoDecoderProxy.h

Blob: `0fec3a1648bb651bc48028c61702f600ecdad390`. Grammar: cpp. Status: syntax-clean.

- include "GMPCallbackBase.h" @8
- include "GMPNativeTypes.h" @9
- include "GMPUtils.h" @10
- include "gmp-video-decode.h" @11
- include "gmp-video-frame-encoded.h" @12
- include "gmp-video-frame-i420.h" @13
- include "nsTArray.h" @14
- class_specifier GMPVideoDecoderCallbackProxy @16-20
- function_definition ~GMPVideoDecoderCallbackProxy @19-19
- class_specifier GMPVideoDecoderProxy @33-53

### dom/media/gmp/GMPVideoEncodedFrameImpl.cpp

Blob: `2ebe788b728fa9d498d7d32bde3c0d2d2a986d9f`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoEncodedFrameImpl.h" @5
- include "GMPSharedMemManager.h" @7
- include "GMPVideoHost.h" @8
- include "mozilla/gmp/GMPTypes.h" @9
- include "nsProxyRelease.h" @10
- include "nsThreadUtils.h" @11
- include "nsXULAppAPI.h" @12
- function_definition GMPVideoEncodedFrameImpl @16-28
- function_definition GMPVideoEncodedFrameImpl @30-45
- function_definition GMPVideoEncodedFrameImpl @47-62
- function_definition ~GMPVideoEncodedFrameImpl @64-74
- function_definition GetFrameFormat @76-78
- function_definition CheckFrameData @81-94
- function_definition RelinquishFrameData @96-107
- function_definition RelinquishFrameData @109-124
- function_definition RelinquishFrameData @126-135
- function_definition DestroyBuffer @137-143
- function_definition CreateEmptyFrame @145-159
- function_definition CopyFrame @161-183
- function_definition SetEncodedWidth @185-187
- function_definition EncodedWidth @189-189
- function_definition SetEncodedHeight @191-193
- function_definition EncodedHeight @195-195
- function_definition SetTimeStamp @197-199
- function_definition TimeStamp @201-201
- function_definition SetDuration @203-205
- function_definition Duration @207-207
- function_definition SetFrameType @209-211
- function_definition FrameType @213-213
- function_definition SetAllocatedSize @215-239
- function_definition AllocatedSize @241-246
- function_definition SetSize @248-248
- function_definition Size @250-250
- function_definition SetCompleteFrame @252-254
- function_definition CompleteFrame @256-256
- function_definition Buffer @258-266
- function_definition Buffer @268-276
- function_definition Destroy @278-278
- function_definition BufferType @280-282
- function_definition SetBufferType @284-286
- function_definition SetTemporalLayerId @288-290
- function_definition GetTemporalLayerId @292-294

### dom/media/gmp/GMPVideoEncodedFrameImpl.h

Blob: `c39f847c2fd8a56151271e2840a3ec7d38b62f86`. Grammar: cpp. Status: syntax-clean.

- include "gmp-errors.h" @33
- include "gmp-video-frame-encoded.h" @34
- include "gmp-video-frame.h" @35
- include "mozilla/ipc/Shmem.h" @36
- include "nsTArray.h" @37
- class_specifier CryptoSample @40-40
- class_specifier GMPVideoHostImpl @44-44
- class_specifier GMPVideoEncodedFrameData @45-45
- class_specifier GMPVideoEncodedFrameImpl @47-118

### dom/media/gmp/GMPVideoEncoderChild.cpp

Blob: `5647b9bcf4291ef27f59fac465ad2090240debf2`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoEncoderChild.h" @5
- include "GMPContentChild.h" @7
- include "GMPPlatform.h" @8
- include "GMPVideoEncodedFrameImpl.h" @9
- include "mozilla/StaticPrefs_media.h" @10
- include "runnable_utils.h" @11
- function_definition GMPVideoEncoderChild @15-18
- function_definition ~GMPVideoEncoderChild @20-29
- function_definition MgrIsOnOwningThread @31-33
- function_definition Init @35-40
- function_definition Encoded @42-76
- function_definition MgrDecodedFrameDestroyed @78-91
- function_definition Error @93-101
- function_definition RecvInitEncode @103-117
- function_definition RecvGiveShmem @119-123
- function_definition RecvEncode @125-152
- function_definition RecvSetChannelParameters @154-165
- function_definition RecvSetRates @167-178
- function_definition RecvSetPeriodicKeyFrames @180-191
- function_definition ActorDestroy @193-199

### dom/media/gmp/GMPVideoEncoderChild.h

Blob: `222bb6c280ea57794a3de28b3ad6adb5c08ba3e4`. Grammar: cpp. Status: syntax-clean.

- include "GMPSharedMemManager.h" @8
- include "GMPVideoHost.h" @9
- include "GMPVideoi420FrameImpl.h" @10
- include "gmp-video-encode.h" @11
- include "mozilla/gmp/PGMPVideoEncoderChild.h" @12
- include "nsString.h" @13
- class_specifier GMPContentChild @17-17
- class_specifier GMPVideoEncoderChild @19-74
- function_definition MgrDeallocShmem @40-44
- function_definition MgrCanSend @48-48

### dom/media/gmp/GMPVideoEncoderParent.cpp

Blob: `d32029938f15b457e3a4739dbccfa0a38892654f`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoEncoderParent.h" @5
- include "GMPContentParent.h" @7
- include "GMPCrashHelper.h" @8
- include "GMPLog.h" @9
- include "GMPMessageUtils.h" @10
- include "GMPVideoEncodedFrameImpl.h" @11
- include "GMPVideoi420FrameImpl.h" @12
- include "mozilla/gmp/GMPTypes.h" @13
- include "nsAutoRef.h" @14
- include "nsThread.h" @15
- include "nsThreadUtils.h" @16
- include "runnable_utils.h" @17
- function_definition GMPVideoEncoderParent @36-44
- function_definition MgrIsOnOwningThread @46-48
- function_definition Close @51-64
- function_definition InitEncode @66-93
- function_definition Encode @95-132
- function_definition SetChannelParameters @134-149
- function_definition SetRates @151-166
- function_definition SetPeriodicKeyFrames @168-182
- function_definition Shutdown @185-204
- function_definition ActorDestroy @207-225
- function_definition RecvReturnShmem @227-231
- function_definition RecvEncodedShmem @233-246
- function_definition RecvEncodedData @248-260
- function_definition RecvDroppedFrame @262-268
- function_definition RecvError @270-276
- function_definition RecvShutdown @278-281

### dom/media/gmp/GMPVideoEncoderParent.h

Blob: `5376f6dd3f04a37f0743023309e1b00a98c6f3b6`. Grammar: cpp. Status: contains-errors.

- include "GMPContentParent.h" @8
- include "GMPCrashHelperHolder.h" @9
- include "GMPMessageUtils.h" @10
- include "GMPSharedMemManager.h" @11
- include "GMPUtils.h" @12
- include "GMPVideoEncoderProxy.h" @13
- include "GMPVideoHost.h" @14
- include "gmp-video-encode.h" @15
- include "mozilla/RefPtr.h" @16
- include "mozilla/gmp/PGMPVideoEncoderParent.h" @17
- class_specifier GMPVideoEncoderParent @21-89
- function_definition GetPluginId @48-48
- function_definition MgrAllocShmem @51-53
- function_definition MgrDeallocShmem @55-59
- function_definition MgrCanSend @62-62
- function_definition ~GMPVideoEncoderParent @66-66

### dom/media/gmp/GMPVideoEncoderProxy.h

Blob: `413cf0ae5eb5c9053b5c3b23600fb3589f8d0c6f`. Grammar: cpp. Status: syntax-clean.

- include "GMPCallbackBase.h" @8
- include "GMPUtils.h" @9
- include "gmp-video-encode.h" @10
- include "gmp-video-frame-encoded.h" @11
- include "gmp-video-frame-i420.h" @12
- include "nsTArray.h" @13
- class_specifier GMPVideoEncoderCallbackProxy @15-22
- function_definition ~GMPVideoEncoderCallbackProxy @17-17
- class_specifier GMPVideoEncoderProxy @35-53

### dom/media/gmp/GMPVideoHost.cpp

Blob: `ddb4464337440bf25b15cfb91e2f19c23eff55e4`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoHost.h" @5
- include "GMPSharedMemManager.h" @7
- include "GMPVideoEncodedFrameImpl.h" @8
- include "GMPVideoPlaneImpl.h" @9
- include "GMPVideoi420FrameImpl.h" @10
- include "mozilla/Assertions.h" @11
- function_definition GMPVideoHostImpl @15-15
- function_definition ~GMPVideoHostImpl @17-17
- function_definition CreateFrame @19-38
- function_definition CreatePlane @40-51

### dom/media/gmp/GMPVideoHost.h

Blob: `f803e6673a209dc8d6a5dd4257781b8411ebd531`. Grammar: cpp. Status: contains-errors.

- include "GMPSharedMemManager.h" @8
- include "gmp-video-frame.h" @9
- include "gmp-video-host.h" @10
- include "gmp-video-plane.h" @11
- include "nsTArray.h" @12
- class_specifier GMPVideoEncodedFrameImpl @16-16
- class_specifier GMPVideoi420FrameImpl @17-17
- class_specifier GMPVideoHostImpl @19-31

### dom/media/gmp/GMPVideoPlaneImpl.cpp

Blob: `4681fa1663f1cbcae1b2279dedebed9ec784bd57`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoPlaneImpl.h" @5
- include <algorithm> @7
- include "GMPSharedMemManager.h" @9
- include "GMPVideoHost.h" @10
- include "mozilla/gmp/GMPTypes.h" @11
- function_definition GMPPlaneImpl @15-21
- function_definition InitPlaneData @23-30
- function_definition MaybeResize @32-38
- function_definition CreateEmptyPlane @40-55
- function_definition Copy @57-73
- function_definition Copy @75-90
- function_definition Swap @92-98
- function_definition AllocatedSize @100-102
- function_definition ResetSize @104-104
- function_definition IsZeroSize @106-106
- function_definition Stride @108-108
- function_definition Buffer @110-115
- function_definition Buffer @116-121
- function_definition Destroy @123-123

### dom/media/gmp/GMPVideoPlaneImpl.h

Blob: `235dba43496167856883589e9a90f8a7dd435b71`. Grammar: cpp. Status: syntax-clean.

- include "gmp-video-plane.h" @8
- include "nsTArray.h" @9
- class_specifier GMPPlaneData @13-13
- class_specifier GMPPlaneImpl @15-44
- function_definition GMPPlaneImpl @17-17
- function_definition ~GMPPlaneImpl @20-20

### dom/media/gmp/GMPVideoi420FrameImpl.cpp

Blob: `3dff703c85e6d661685907af82d5b1a5ba9244ed`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoi420FrameImpl.h" @5
- include <algorithm> @7
- include "GMPSharedMemManager.h" @9
- include "GMPVideoHost.h" @10
- include "mozilla/CheckedInt.h" @11
- include "mozilla/gmp/GMPTypes.h" @12
- include "nsProxyRelease.h" @13
- include "nsThreadUtils.h" @14
- include "nsXULAppAPI.h" @15
- function_definition GMPFramePlane::GMPFramePlane @19-23
- function_definition GMPFramePlane::InitPlaneData @25-30
- function_definition GMPFramePlane::Copy @32-43
- function_definition GMPVideoi420FrameImpl @45-55
- function_definition GMPVideoi420FrameImpl @57-73
- function_definition GMPVideoi420FrameImpl @75-91
- function_definition ~GMPVideoi420FrameImpl @93-108
- function_definition InitFrameData @110-119
- function_definition InitFrameData @121-136
- function_definition InitFrameData @138-147
- function_definition GetFrameFormat @149-151
- function_definition Destroy @153-153
- function_definition CheckFrameData @156-242
- function_definition CheckDimensions @244-270
- function_definition CheckDimensions @272-286
- function_definition GetPlane @288-301
- function_definition GetPlane @303-316
- function_definition MaybeResize @318-347
- function_definition CreateEmptyFrame @349-387
- function_definition CreateFrame @389-418
- function_definition CopyFrame @420-445
- function_definition SwapFrame @447-459
- function_definition Buffer @461-469
- function_definition Buffer @471-479
- function_definition Buffer @481-488
- function_definition Buffer @490-497
- function_definition AllocatedSize @499-504
- function_definition AllocatedSize @506-511
- function_definition Stride @513-518
- function_definition SetWidth @520-527
- function_definition SetHeight @529-536
- function_definition Width @538-538
- function_definition Height @540-540
- function_definition SetTimestamp @542-544
- function_definition Timestamp @546-546
- function_definition SetUpdatedTimestamp @548-550
- function_definition UpdatedTimestamp @552-554
- function_definition SetDuration @556-558
- function_definition Duration @560-560
- function_definition IsZeroSize @562-564
- function_definition ResetSize @566-570

### dom/media/gmp/GMPVideoi420FrameImpl.h

Blob: `bfbf375d1f6ec715a3dfcf64214da6bc60222347`. Grammar: cpp. Status: syntax-clean.

- include "gmp-video-frame-i420.h" @8
- include "mozilla/Maybe.h" @9
- include "mozilla/ipc/Shmem.h" @10
- include "nsTArray.h" @11
- class_specifier GMPPlaneData @15-15
- class_specifier GMPVideoi420FrameData @16-16
- class_specifier GMPVideoHostImpl @17-17
- enum_specifier HostReportPolicy @19-22
- class_specifier GMPVideoi420FrameImpl @24-120
- struct_specifier GMPFramePlane @84-94
- function_definition GMPFramePlane @86-86

### dom/media/gmp/gmp-api/gmp-entrypoints.h

Blob: `62511a55c1d5e58ca977eba4638e6b85e9a7f697`. Grammar: cpp. Status: syntax-clean.

- include "gmp-errors.h" @36
- include "gmp-platform.h" @37

### dom/media/gmp/gmp-api/gmp-errors.h

Blob: `a0cf09fd45e5b0c7121b1208ee6c29e71d4f2b3d`. Grammar: cpp. Status: syntax-clean.

- enum_specifier GMPErr @35-53

### dom/media/gmp/gmp-api/gmp-platform.h

Blob: `dc0162717b3eff665d42ca21b79d8eb930f66dd3`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @35
- include "gmp-errors.h" @37
- include "gmp-storage.h" @38
- class_specifier GMPTask @42-47
- function_definition ~GMPTask @45-45
- class_specifier GMPThread @49-54
- function_definition ~GMPThread @51-51
- class_specifier GMPMutex @58-64
- function_definition ~GMPMutex @60-60
- struct_specifier GMPPlatformAPI @86-100

### dom/media/gmp/gmp-api/gmp-storage.h

Blob: `2a0bd149759377bbeca9d1fb7ddbe9ee62ad28e6`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @20
- include "gmp-errors.h" @22
- class_specifier GMPRecord @43-69
- function_definition ~GMPRecord @68-68
- class_specifier GMPRecordClient @73-109
- function_definition ~GMPRecordClient @108-108

### dom/media/gmp/gmp-api/gmp-video-codec.h

Blob: `d8befaa8f9751c0fcd43ca736979fb2593b12040`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @36
- include <stdint.h> @37
- enum_specifier GMP_VIDEO_CODEC_h_ @39-39
- enum_specifier GMP_VIDEO_CODEC_h_ @40-40
- enum_specifier GMPVideoCodecComplexity @42-48
- enum_specifier GMPVP8ResilienceMode @50-60
- struct_specifier GMPVideoCodecVP8 @63-72
- struct_specifier GMPVideoCodecH264AVCC @78-95
- struct_specifier GMPVideoCodecH264 @100-104
- struct_specifier GMPVideoCodecH264AVCC @102-102
- enum_specifier GMPVideoCodecType @106-115
- struct_specifier GMPSimulcastStream @119-127
- enum_specifier GMPVideoCodecMode @129-135
- enum_specifier GMPLogLevel @137-146
- enum_specifier GMPProfile @148-160
- enum_specifier GMPLevel @162-181
- enum_specifier GMPRateControlMode @183-191
- enum_specifier GMPSliceMode @193-199
- enum_specifier GMPApiVersion @201-214
- struct_specifier GMPVideoCodec @216-253
- enum_specifier GMPBufferType @259-266
- struct_specifier GMPCodecSpecificInfoGeneric @268-270
- struct_specifier GMPCodecSpecificInfoH264 @272-274
- struct_specifier GMPCodecSpecificInfoVP8 @278-290
- struct_specifier GMPCodecSpecificInfo @301-305

### dom/media/gmp/gmp-api/gmp-video-decode.h

Blob: `c214f1a350875759f4486a759bb3c52d48160e39`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @36
- include "gmp-errors.h" @38
- include "gmp-video-codec.h" @39
- include "gmp-video-frame-encoded.h" @40
- include "gmp-video-frame-i420.h" @41
- class_specifier GMPVideoDecoderCallback @44-63
- function_definition ~GMPVideoDecoderCallback @46-46
- class_specifier GMPVideoDecoder @74-123
- function_definition ~GMPVideoDecoder @76-76

### dom/media/gmp/gmp-api/gmp-video-encode.h

Blob: `c4288618408344b800415787a936341754f373f2`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @36
- include "gmp-errors.h" @38
- include "gmp-video-codec.h" @39
- include "gmp-video-frame-encoded.h" @40
- include "gmp-video-frame-i420.h" @41
- class_specifier GMPVideoEncoderCallback @44-55
- function_definition ~GMPVideoEncoderCallback @46-46
- class_specifier GMPVideoEncoder @66-129
- function_definition ~GMPVideoEncoder @68-68

### dom/media/gmp/gmp-api/gmp-video-frame-encoded.h

Blob: `fcea5bd63a767797c7b6781b74436641bac2d2bd`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @36
- include "gmp-video-codec.h" @38
- include "gmp-video-frame.h" @39
- enum_specifier GMPVideoFrameType @41-48
- class_specifier GMPVideoEncodedFrame @59-92

### dom/media/gmp/gmp-api/gmp-video-frame-i420.h

Blob: `1340efe78583eb4e96829392343c77152c6f12d8`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @36
- include "gmp-errors.h" @38
- include "gmp-video-frame.h" @39
- include "gmp-video-plane.h" @40
- enum_specifier GMPPlaneType @42-47
- class_specifier GMPVideoi420Frame @58-139

### dom/media/gmp/gmp-api/gmp-video-frame.h

Blob: `adf01a8b778a3ec6fa18aa5f8eaa60411b55ba74`. Grammar: cpp. Status: syntax-clean.

- include "gmp-video-plane.h" @36
- enum_specifier GMPVideoFrameFormat @38-38
- class_specifier GMPVideoFrame @40-45

### dom/media/gmp/gmp-api/gmp-video-host.h

Blob: `91ebae504396a7e29f7629953a9fc01740c52a52`. Grammar: cpp. Status: syntax-clean.

- include "gmp-errors.h" @36
- include "gmp-video-codec.h" @37
- include "gmp-video-frame-encoded.h" @38
- include "gmp-video-frame-i420.h" @39
- class_specifier GMPVideoHost @42-50

### dom/media/gmp/gmp-api/gmp-video-plane.h

Blob: `fb129d2941a8b5bae3180c13b3cf0718bf232825`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @36
- include "gmp-errors.h" @38
- class_specifier GMPPlane @49-92

### dom/media/gmp/rlz/lib/assert.h

Blob: `767c2163b30df075f57018100a644ff5bc6a81b4`. Grammar: cpp. Status: syntax-clean.

- include <assert.h> @8

### dom/media/gmp/rlz/lib/crc8.cc

Blob: `fe02eabf1b897535ff2c416f332080d78653687e`. Grammar: cpp. Status: syntax-clean.

- include "rlz/lib/crc8.h" @5
- function_definition Generate @51-70
- function_definition Verify @72-88

### dom/media/gmp/rlz/lib/crc8.h

Blob: `6c3c84859bfc589aac679d7cf67579822a506cc4`. Grammar: cpp. Status: syntax-clean.

- class_specifier Crc8 @12-21

### dom/media/gmp/rlz/lib/machine_id.cc

Blob: `dd41e52001124725c67b3697d7807fdce7d13125`. Grammar: cpp. Status: syntax-clean.

- include "rlz/lib/machine_id.h" @5
- include <stddef.h> @7
- include "rlz/lib/assert.h" @9
- include "rlz/lib/crc8.h" @10
- include "rlz/lib/string_utils.h" @11
- include "mozilla/SHA1.h" @16
- function_definition GetMachineId @20-42
- function_definition GetMachineIdImpl @46-89

### dom/media/gmp/rlz/lib/machine_id.h

Blob: `5fa343efa3554845fc6f286bd43ab5442997e9d0`. Grammar: cpp. Status: syntax-clean.

- include <string> @8
- include <vector> @9

### dom/media/gmp/rlz/lib/string_utils.cc

Blob: `6da732382368e7c8e6a15ce6a13c87d67b361299`. Grammar: cpp. Status: syntax-clean.

- include "rlz/lib/string_utils.h" @7
- function_definition BytesToString @11-32

### dom/media/gmp/rlz/lib/string_utils.h

Blob: `500133ade1f4821d30fff4b05247a91bd369cbf1`. Grammar: cpp. Status: syntax-clean.

- include <string> @10

### dom/media/gmp/rlz/mac/lib/machine_id_mac.cc

Blob: `8c0bae22e8f7109c32967e874493269dc7e67308`. Grammar: cpp. Status: syntax-clean.

- include <CoreFoundation/CoreFoundation.h> @5
- include <IOKit/IOKitLib.h> @6
- include <IOKit/network/IOEthernetController.h> @7
- include <IOKit/network/IOEthernetInterface.h> @8
- include <IOKit/network/IONetworkInterface.h> @9
- include <stddef.h> @10
- include <stdint.h> @11
- include <vector> @13
- include <string> @14
- class_specifier ScopedCFTypeRef @28-61
- function_definition ScopedCFTypeRef @32-34
- function_definition ScopedCFTypeRef @36-36
- function_definition ScopedCFTypeRef @37-37
- function_definition ~ScopedCFTypeRef @39-42
- function_definition (anonymous) @44-44
- function_definition (anonymous) @45-45
- function_definition (anonymous) @47-49
- function_definition release @53-57
- class_specifier ScopedIOObject @68-96
- function_definition ScopedIOObject @72-74
- function_definition ~ScopedIOObject @76-79
- function_definition ScopedIOObject @81-81
- function_definition operator= @82-82
- function_definition reset @84-88
- function_definition (anonymous) @90-92
- function_definition CFCast @103-112
- function_definition CFCast @115-124
- function_definition CFStringToSTLStringWithEncodingT @132-173
- function_definition SysCFStringRefToUTF8 @175-179
- function_definition FindEthernetInterfaces @190-213
- function_definition GetMACAddressFromIterator @215-250
- function_definition GetMacAddress @252-260
- function_definition CopySerialNumber @262-280
- function_definition GetRawMachineId @284-320

### dom/media/gmp/rlz/win/lib/machine_id_win.cc

Blob: `5f4b3557310aa22f052f445dcfceb64f3329cf14`. Grammar: cpp. Status: syntax-clean.

- include <windows.h> @5
- include <sddl.h> @6
- include <memory> @8
- include <string> @9
- include <vector> @10
- include "mozilla/ArrayUtils.h" @12
- include "rlz/lib/assert.h" @14
- function_definition GetSystemVolumeSerialNumber @20-42
- function_definition GetComputerSid @44-71
- function_definition ConvertSidToBytes @73-108
- function_definition GetRawMachineId @112-134

### dom/media/gmp/widevine-adapter/WidevineFileIO.cpp

Blob: `41237a2bc2a948d32fe6cf6bace86f0bbd27bc62`. Grammar: cpp. Status: syntax-clean.

- include "WidevineFileIO.h" @5
- include "GMPLog.h" @7
- include "WidevineUtils.h" @8
- include "gmp-api/gmp-platform.h" @9
- function_definition Open @16-38
- function_definition Read @40-49
- function_definition Write @51-59
- function_definition DestroyRecord @61-66
- function_definition Close @68-72
- function_definition GMPToWidevineFileStatus @74-83
- function_definition OpenComplete @85-89
- function_definition ReadComplete @91-96
- function_definition WriteComplete @98-102

### dom/media/gmp/widevine-adapter/WidevineFileIO.h

Blob: `356897d7f7cd6c1c5a21b9d1ae2ad7dcd6ce8de8`. Grammar: cpp. Status: syntax-clean.

- include <string> @8
- include "content_decryption_module.h" @10
- include "gmp-api/gmp-storage.h" @11
- class_specifier WidevineFileIO @15-37
- function_definition WidevineFileIO @17-17

### dom/media/gmp/widevine-adapter/WidevineUtils.cpp

Blob: `0b02decd8d1b588fb307a4add099bea2a7490c07`. Grammar: cpp. Status: syntax-clean.

- include "WidevineUtils.h" @5
- include <stdint.h> @7
- include "GMPLog.h" @9
- include "gmp-api/gmp-errors.h" @10
- function_definition WidevineBuffer @14-17
- function_definition ~WidevineBuffer @19-21
- function_definition Destroy @23-23
- function_definition Capacity @25-25
- function_definition Data @27-27
- function_definition SetSize @29-29
- function_definition Size @31-31
- function_definition ExtractBuffer @33-36
- function_definition WidevineDecryptedBlock @38-39
- function_definition ~WidevineDecryptedBlock @41-46
- function_definition SetDecryptedBuffer @48-50
- function_definition DecryptedBuffer @52-52
- function_definition SetTimestamp @54-56
- function_definition Timestamp @58-58

### dom/media/gmp/widevine-adapter/WidevineUtils.h

Blob: `53784d5ac1f8e7b6f84d184090987bf81f3f69b0`. Grammar: cpp. Status: syntax-clean.

- include "content_decryption_module.h" @8
- include "mozilla/Logging.h" @9
- include "nsISupportsImpl.h" @10
- include "nsTArray.h" @11
- include "stddef.h" @12
- class_specifier CDMShmemBuffer @33-33
- class_specifier WidevineBuffer @35-35
- class_specifier CDMBuffer @39-43
- function_definition AsArrayBuffer @41-41
- function_definition AsShmemBuffer @42-42
- class_specifier WidevineBuffer @45-67
- function_definition WidevineBuffer @50-50
- function_definition operator= @51-51
- function_definition AsArrayBuffer @63-63
- class_specifier WidevineDecryptedBlock @69-81

### dom/media/gmp/widevine-adapter/WidevineVideoFrame.cpp

Blob: `a6e49610a6f284ba1de7b149ec2d9e451b8272ff`. Grammar: cpp. Status: syntax-clean.

- include "WidevineVideoFrame.h" @5
- include "GMPLog.h" @7
- include "WidevineUtils.h" @8
- include "mozilla/CheckedInt.h" @9
- include "mozilla/IntegerPrintfMacros.h" @10
- function_definition WidevineVideoFrame @14-24
- function_definition WidevineVideoFrame @26-38
- function_definition ~WidevineVideoFrame @40-45
- function_definition SetFormat @47-51
- function_definition Format @53-53
- function_definition SetSize @55-60
- function_definition Size @62-62
- function_definition SetFrameBuffer @64-69
- function_definition FrameBuffer @71-71
- function_definition SetPlaneOffset @73-78
- function_definition PlaneOffset @80-82
- function_definition SetStride @84-88
- function_definition Stride @90-92
- function_definition SetTimestamp @94-98
- function_definition Timestamp @100-100
- function_definition InitToBlack @102-142

### dom/media/gmp/widevine-adapter/WidevineVideoFrame.h

Blob: `b5f444542f05445fe20e8ee612ea7ecd01535dd4`. Grammar: cpp. Status: syntax-clean.

- include "content_decryption_module.h" @8
- include "stddef.h" @9
- class_specifier WidevineVideoFrame @13-47

### dom/media/gmp/widevine-adapter/content_decryption_module.h

Blob: `4fa6f8fc707f28119a7cbb7d710e8350a91a5736`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @8
- include <type_traits> @9
- include "content_decryption_module_export.h" @11
- include "mozilla/DefineEnum.h" @13
- enum_specifier Exception @85-90
- enum_specifier EncryptionScheme @94-98
- struct_specifier Pattern @103-106
- enum_specifier ColorRange @109-114
- struct_specifier ColorSpace @121-126
- struct_specifier SubsampleEntry @157-160
- struct_specifier InputBuffer_2 @169-191
- struct_specifier SubsampleEntry @183-183
- enum_specifier AudioCodec @194-194
- struct_specifier AudioDecoderConfig_2 @197-210
- enum_specifier AudioFormat @214-222
- enum_specifier VideoFormat @227-245
- struct_specifier Size @248-251
- enum_specifier VideoCodec @254-260
- enum_specifier VideoCodecProfile @263-280
- struct_specifier VideoDecoderConfig_2 @287-304
- struct_specifier VideoDecoderConfig_3 @307-323
- enum_specifier StreamType @326-326
- struct_specifier PlatformChallengeResponse @332-345
- enum_specifier KeyStatus @350-358
- enum_specifier KeyStatus_2 @366-375
- struct_specifier KeyInformation @381-386
- struct_specifier KeyInformation_2 @392-397
- enum_specifier OutputProtectionMethods @402-405
- enum_specifier OutputLinkTypes @409-418
- enum_specifier QueryResult @422-422
- enum_specifier InitDataType @427-427
- enum_specifier SessionType @432-435
- enum_specifier MessageType @440-445
- enum_specifier HdcpVersion @448-459
- struct_specifier Policy @462-464
- function_definition Buffer @468-485
- class_specifier CDM_CLASS_API @468-468
- function_definition ~Buffer @480-480
- function_definition DecryptedBlock @488-501
- class_specifier CDM_CLASS_API @488-488
- function_definition ~DecryptedBlock @500-500
- function_definition VideoFrame @512-536
- class_specifier CDM_CLASS_API @512-512
- function_definition ~VideoFrame @535-535
- function_definition VideoFrame_2 @540-554
- class_specifier CDM_CLASS_API @540-540
- function_definition ~VideoFrame_2 @553-553
- function_definition AudioFrames @567-581
- class_specifier CDM_CLASS_API @567-567
- function_definition ~AudioFrames @580-580
- function_definition FileIO @592-627
- class_specifier CDM_CLASS_API @592-592
- function_definition ~FileIO @626-626
- function_definition FileIOClient @633-663
- class_specifier CDM_CLASS_API @633-633
- enum_specifier Status @635-635
- function_definition ~FileIOClient @662-662
- enum_specifier MetricName @673-685
- class_specifier CDM_CLASS_API @688-688
- class_specifier CDM_CLASS_API @689-689
- class_specifier CDM_CLASS_API @690-690
- function_definition ContentDecryptionModule_10 @698-910
- class_specifier CDM_CLASS_API @698-698
- function_definition ~ContentDecryptionModule_10 @909-909
- function_definition ContentDecryptionModule_11 @918-1134
- class_specifier CDM_CLASS_API @918-918
- function_definition ~ContentDecryptionModule_11 @1133-1133
- function_definition ContentDecryptionModule_12 @1144-1360
- class_specifier CDM_CLASS_API @1144-1144
- function_definition ~ContentDecryptionModule_12 @1359-1359
- function_definition Host_10 @1362-1496
- class_specifier CDM_CLASS_API @1362-1362
- function_definition ~Host_10 @1495-1495
- function_definition Host_11 @1498-1637
- class_specifier CDM_CLASS_API @1498-1498
- function_definition ~Host_11 @1636-1636
- function_definition Host_12 @1639-1778
- class_specifier CDM_CLASS_API @1639-1639
- function_definition ~Host_12 @1777-1777

### dom/media/gmp/widevine-adapter/content_decryption_module_export.h

Blob: `932708deba3149ea6160849d113a06e4201c8114`. Grammar: cpp. Status: syntax-clean.


### dom/media/gmp/widevine-adapter/content_decryption_module_ext.h

Blob: `53b16238febde4b3a7c04f7cf09eabeacda4b769`. Grammar: cpp. Status: contains-errors.

- include <cstdint> @8
- include <windows.h> @11
- include "content_decryption_module_export.h" @14
- struct_specifier HostFile @28-40
- function_definition HostFile @29-32

### dom/media/gtest/GMPTestMonitor.h

Blob: `5c4a321e835e44806375598bd6fcb8e671e01cd6`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/SchedulerGroup.h" @7
- include "mozilla/SpinEventLoopUntil.h" @8
- include "nsThreadUtils.h" @9
- class_specifier GMPTestMonitor @11-36
- function_definition GMPTestMonitor @13-13
- function_definition AwaitFinished @15-20
- function_definition MarkFinished @23-26
- function_definition SetFinished @29-32

### dom/media/gtest/MediaSinkTestUtils.h

Blob: `9ef332d044f00683b7d8b66f0876a5fcd3eabcb4`. Grammar: cpp. Status: contains-errors.

- include <utility> @8
- include "AudioSink.h" @10
- include "AudioSinkWrapper.h" @11
- include "ImageContainer.h" @12
- include "MediaData.h" @13
- include "MediaInfo.h" @14
- include "MediaQueue.h" @15
- include "VideoFrameContainer.h" @16
- include "gtest/gtest.h" @17
- include "nsThreadUtils.h" @18
- function_definition MakeAudioSinkWrapper @45-55
- function_definition MakeSinkTestVideoFrameContainer @57-70
- function_definition MakeSinkTest1x1Image @74-84

### dom/media/gtest/MockDecoderModule.h

Blob: `c1190a7895e35cf539cf49290076ad85e4dbde90`. Grammar: cpp. Status: contains-errors.

- include "BlankDecoderModule.h" @8
- include "DummyMediaDataDecoder.h" @9
- include "PlatformDecoderModule.h" @10
- include "gmock/gmock.h" @11
- enum_specifier HardwareAcceleration @15-15
- class_specifier MockVideoDataDecoder @17-40
- function_definition MockVideoDataDecoder @19-31
- function_definition SetLatencyFrameCount @36-36
- function_definition ~MockVideoDataDecoder @39-39
- class_specifier HardwareCapableMockDecoder @44-59
- function_definition HardwareCapableMockDecoder @46-50
- function_definition IsHardwareAccelerated @52-54
- function_definition ~HardwareCapableMockDecoder @57-57
- class_specifier MockDecoderModule @61-83
- function_definition MockDecoderModule @63-66
- function_definition Name @79-79
- function_definition ~MockDecoderModule @82-82

### dom/media/gtest/MockGraphInterface.h

Blob: `1a1d20be0eb40c505190c2c7c1a14e5ddab06619`. Grammar: cpp. Status: contains-errors.

- include <tuple> @8
- include "GraphDriver.h" @10
- include "gmock/gmock.h" @11
- class_specifier MockGraphInterface @15-96
- function_definition MockGraphInterface @17-18
- function_definition OneIteration @32-60
- function_definition SetEnsureNextIteration @61-61
- function_definition IterationCount @63-63
- function_definition StateComputedTime @65-65
- function_definition SetCurrentDriver @66-66
- function_definition StopIterating @68-68
- function_definition SwitchTo @70-77
- function_definition (anonymous) @80-82
- function_definition ~MockGraphInterface @95-95

### dom/media/gtest/MockMediaDataDemuxer.h

Blob: `57a255c27f151a783ea15a4781476709071142f1`. Grammar: cpp. Status: contains-errors.

- include "MediaContainerType.h" @8
- include "MediaDecoderOwner.h" @9
- include "MediaMIMETypes.h" @10
- include "VideoUtils.h" @11
- include "gmock/gmock.h" @12
- class_specifier MockMediaDataDemuxer @16-33
- function_definition MockMediaDataDemuxer @18-22
- function_definition ~MockMediaDataDemuxer @32-32
- class_specifier MockMediaTrackDemuxer @35-68
- function_definition MockMediaTrackDemuxer @39-49
- function_definition GetSamples @56-59
- function_definition ~MockMediaTrackDemuxer @67-67

### dom/media/gtest/MockMediaDecoderOwner.h

Blob: `f885328ae1edbb9c18704bdf29defba493885e92`. Grammar: cpp. Status: contains-errors.

- include "MediaDecoderOwner.h" @8
- include "gmock/gmock.h" @9
- class_specifier MockMediaDecoderOwner @13-52

### dom/media/gtest/MockMediaResource.cpp

Blob: `9a391e32b409f37a796f117d80fa0115aca8c43b`. Grammar: cpp. Status: syntax-clean.

- include "MockMediaResource.h" @5
- include <sys/stat.h> @7
- include <sys/types.h> @8
- function_definition MockMediaResource @12-13
- function_definition Open @15-22
- function_definition ~MockMediaResource @24-28
- function_definition ReadAt @30-48
- function_definition GetLength @50-56
- function_definition MockClearBufferedRanges @58-58
- function_definition MockAddBufferedRange @60-62
- function_definition GetNextCachedData @64-75
- function_definition GetCachedDataEnd @77-84
- function_definition GetCachedRanges @86-89

### dom/media/gtest/MockMediaResource.h

Blob: `f69cd115884f20cb41c31fc4c297434f9158273a`. Grammar: cpp. Status: syntax-clean.

- include "MediaResource.h" @8
- include "mozilla/Atomics.h" @9
- include "nsTArray.h" @10
- class_specifier MockMediaResource @16-52
- function_definition ShouldCacheReads @23-23
- function_definition Pin @24-24
- function_definition Unpin @25-25
- function_definition IsDataCachedToEndOfResource @29-29
- function_definition ReadFromCache @30-36

### dom/media/gtest/TestADTSDemuxer.cpp

Blob: `2eee29833802dd31dedffe3669e4d70b6e48689b`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include <climits> @7
- include "ADTSDemuxer.h" @9
- include "MockMediaResource.h" @10
- class_specifier MockADTSMediaResource @12-12
- class_specifier MockADTSMediaResource @20-29
- function_definition MockADTSMediaResource @24-25
- function_definition ~MockADTSMediaResource @28-28
- function_definition TEST @33-48

### dom/media/gtest/TestAOMDecoder.cpp

Blob: `6512e1dc51ed3183c0c656d3f261670b380baaa7`. Grammar: cpp. Status: syntax-clean.

- include "AOMDecoder.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/gfx/Types.h" @7
- include "nsTArray.h" @8
- function_definition AppendU16BE @19-22
- function_definition AppendU32BE @24-29
- function_definition BuildMetadataOBU @33-54
- function_definition BuildMDCVPayload @56-75
- function_definition BuildCLLPayload @77-83
- function_definition TEST @85-108
- function_definition TEST @110-123
- function_definition TEST @125-142
- function_definition TEST @144-153
- function_definition TEST @155-166
- function_definition TEST @168-178
- function_definition TEST @180-193

### dom/media/gtest/TestAV1FmtpParser.cpp

Blob: `0209617b38b484eee4593e4e27d6c07a226f60a8`. Grammar: cpp. Status: syntax-clean.

- include "MediaMIMETypes.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/media/webrtc/AV1FmtpParser.h" @7
- function_definition Parse @11-18
- function_definition TEST @20-29
- function_definition TEST @31-36
- function_definition TEST @38-43
- function_definition TEST @45-50
- function_definition TEST @52-57
- function_definition TEST @59-64
- function_definition TEST @66-72
- function_definition TEST @74-80
- function_definition TEST @82-88
- function_definition TEST @90-95
- function_definition TEST @97-102
- function_definition TEST @104-109
- function_definition TEST @111-123
- function_definition TEST @125-130
- function_definition TEST @132-137
- function_definition TEST @139-144
- function_definition TEST @146-151
- function_definition TEST @153-158
- function_definition TEST @160-169
- function_definition TEST @171-180
- function_definition TEST @182-186
- function_definition TEST @188-192
- function_definition TEST @194-198
- function_definition TEST @200-206
- function_definition TEST @208-212
- function_definition TEST @214-218
- function_definition TEST @220-223
- function_definition TEST @225-228
- function_definition TEST @230-238
- function_definition TEST @240-243
- function_definition TEST @245-248
- function_definition TEST @250-253

### dom/media/gtest/TestAVSync.cpp

Blob: `17ff81bb8df518d8bcdbbc4da5b48b0bd30f04ef`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include <cmath> @6
- include <tuple> @7
- include "AudioGenerator.h" @9
- include "AudioSampleFormat.h" @10
- include "CubebUtils.h" @11
- include "FrameStatistics.h" @12
- include "MediaData.h" @13
- include "MediaSinkTestUtils.h" @14
- include "MockCubeb.h" @15
- include "MockMediaDecoderOwner.h" @16
- include "TimeUnits.h" @17
- include "VideoSink.h" @18
- include "gtest/gtest.h" @19
- include "mozilla/Maybe.h" @20
- include "mozilla/SpinEventLoopUntil.h" @21
- include "mozilla/gtest/ScopedPrefSetter.h" @22
- include "nsThreadUtils.h" @23
- include "prthread.h" @24
- class_specifier AVSyncTest @62-454
- function_definition SetUp @64-70
- function_definition TearDown @75-90
- class_specifier ScopedCubebContext @99-105
- function_definition ScopedCubebContext @101-103
- function_definition ~ScopedCubebContext @104-104
- function_definition CreateSink @108-135
- function_definition ProcessPending @140-140
- enum_specifier ExpectedAudioStream @143-143
- function_definition Start @145-160
- function_definition SeekStop @162-168
- function_definition PushAudio @191-210
- function_definition PushVideoFrame @212-218
- function_definition PushVideoFrames @220-228
- function_definition VideoFrameDuration @234-236
- function_definition PushSteadyContent @240-244
- function_definition DriveCallback @247-270
- function_definition AdvanceClock @278-282
- function_definition WaitForRenderedSchedule @287-318
- function_definition ExpectScheduleMatchesClock @353-390
- function_definition ExpectCadenceMatchesRate @397-423
- function_definition ExpectCorrectClockAndCadence @425-428
- function_definition TEST_F @457-464
- function_definition TEST_F @467-482
- function_definition TEST_F @488-510
- function_definition TEST_F @517-526
- function_definition TEST_F @532-549
- function_definition TEST_F @554-569
- function_definition TEST_F @572-587
- function_definition TEST_F @591-606
- function_definition TEST_F @609-618
- class_specifier AVSyncRateTest @624-625
- function_definition TEST_P @627-639
- class_specifier AVSyncFrameRateTest @647-648
- function_definition TEST_P @650-662
- class_specifier AVSyncCallbackSizeTest @670-671
- function_definition TEST_P @673-684
- class_specifier AVSyncSeekTest @692-766
- function_definition RunSeekResume @694-713
- function_definition RenderedAudio @719-721
- function_definition ExpectDrainingAdvancesClock @724-733
- function_definition RunClockFollowsRenderedAudio @737-765
- function_definition TEST_F @768-772
- function_definition TEST_F @774-778
- function_definition TEST_F @780-784
- function_definition TEST_F @786-790

### dom/media/gtest/TestAppleVTColorSpace.cpp

Blob: `2143b5a6a2a93eff04451c152f0abee14878c776`. Grammar: cpp. Status: contains-errors.

- include <CoreGraphics/CGColorSpace.h> @5
- include <CoreVideo/CVPixelBuffer.h> @6
- include "AppleVTColorSpace.h" @8
- include "MP4Demuxer.h" @9
- include "MacIOSurfaceImage.h" @10
- include "MockMediaResource.h" @11
- include "PDMFactory.h" @12
- include "VideoUtils.h" @13
- include "gfxPlatform.h" @14
- include "gtest/gtest.h" @15
- include "mozilla/ScopeExit.h" @16
- include "mozilla/SharedThreadPool.h" @17
- include "mozilla/UniquePtr.h" @18
- include "mozilla/gfx/MacIOSurface.h" @19
- include "mozilla/gtest/ScopedPrefSetter.h" @20
- include "mozilla/gtest/WaitFor.h" @21
- function_definition DecodeFirstFrameViaVideoToolbox @28-118
- function_definition TEST @123-132
- function_definition TEST @134-143
- function_definition AttachesColorSpace @150-171
- function_definition TEST @177-181
- function_definition TEST @185-191
- function_definition TEST @197-234
- function_definition TEST @238-246
- function_definition TEST @249-262

### dom/media/gtest/TestAsyncLogger.cpp

Blob: `8998dec56b1191c4828cc16c30cb734f0ced3be9`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include <string> @7
- include "AsyncLogger.h" @9
- function_definition TEST @13-31
- function_definition TEST @33-53
- function_definition TEST @55-76

### dom/media/gtest/TestAudioBuffer.cpp

Blob: `af7e9c527d27288a862007fab2c72cc5ef1e8d01`. Grammar: cpp. Status: syntax-clean.

- include "MediaData.h" @5
- include "gtest/gtest.h" @6
- function_definition FillSine @13-25
- function_definition TEST @27-45

### dom/media/gtest/TestAudioBufferAddWithScale.cpp

Blob: `037461898d9b22c3688100823c980282b1763b0a`. Grammar: cpp. Status: syntax-clean.

- include <cstring> @5
- include "AudioNodeEngine.h" @7
- include "gtest/gtest.h" @8
- function_definition ReferenceAddWithScale @42-48
- function_definition ExpectBitIdentical @52-67
- function_definition FillSignal @72-76
- function_definition TEST @83-105
- function_definition TEST @109-128
- function_definition TEST @136-160
- function_definition TEST @164-185

### dom/media/gtest/TestAudioBuffers.cpp

Blob: `a72b23435b8742ecfee7bd98966abbc3c1b28560`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @5
- include <vector> @7
- include "AudioBufferUtils.h" @9
- include "gtest/gtest.h" @10
- function_definition test_for_number_of_channels @14-62
- function_definition TEST @64-69

### dom/media/gtest/TestAudioCallbackDriver.cpp

Blob: `08ca0865f7a46df6231102a30ab8209419b54c29`. Grammar: cpp. Status: contains-errors.

- include "CubebUtils.h" @5
- include "MediaTrackGraphImpl.h" @6
- include "MockCubeb.h" @7
- include "MockGraphInterface.h" @8
- include "gtest/gtest.h" @9
- include "mozilla/Attributes.h" @10
- include "mozilla/SyncRunnable.h" @11
- include "mozilla/gtest/WaitFor.h" @12
- include "nsTArray.h" @13
- function_definition TestSlowStart @58-168
- function_definition TEST @170-175
- function_definition AutoSetter @179-191
- class_specifier MOZ_STACK_CLASS @179-179
- function_definition ~AutoSetter @187-190
- function_definition TestInputProcessingOnStart @504-566
- function_definition TEST @568-607

### dom/media/gtest/TestAudioClock.cpp

Blob: `9598b2c4829b54f5a9fff35658bbf2e9cb6795e9`. Grammar: cpp. Status: syntax-clean.

- include "AudioStream.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @23-43
- function_definition TEST @48-66
- function_definition TEST @78-127
- function_definition TEST @136-155
- function_definition TEST @166-183
- function_definition TEST @194-218
- function_definition TEST @229-254
- function_definition TEST @266-287

### dom/media/gtest/TestAudioCompactor.cpp

Blob: `64279d8812815c0ad02d3f90426d24e942822ce1`. Grammar: cpp. Status: syntax-clean.

- include "AudioCompactor.h" @4
- include "gtest/gtest.h" @5
- include "nsDeque.h" @6
- include "nsIMemoryReporter.h" @7
- class_specifier MemoryFunctor @14-24
- function_definition MemoryFunctor @16-16
- function_definition operator() @19-21
- class_specifier TestCopy @26-47
- function_definition TestCopy @28-33
- function_definition operator() @35-40
- function_definition TestAudioCompactor @49-74
- function_definition TEST @76-79
- function_definition TEST @81-84
- function_definition TEST @86-89
- function_definition TEST @91-94
- function_definition TEST @96-137

### dom/media/gtest/TestAudioConfig.cpp

Blob: `78914cc0c68fc5ea911334f6a77a932862395b90`. Grammar: cpp. Status: syntax-clean.

- include "AudioConfig.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @12-19

### dom/media/gtest/TestAudioConverter.cpp

Blob: `377c2b653a2abd0b57fe395a9882bf064a959bc6`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include <limits> @7
- include "AudioConverter.h" @9
- function_definition TEST @13-28

### dom/media/gtest/TestAudioData.cpp

Blob: `5c46b66366e853f15a2bc49cb75b20e1caf5fa44`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include "MediaData.h" @7
- include "TimeUnits.h" @8
- function_definition TEST @20-38
- function_definition TEST @42-55

### dom/media/gtest/TestAudioDecoderInputTrack.cpp

Blob: `09b9efd1ce55b4c29c4d7180d535a5c1bf330782`. Grammar: cpp. Status: syntax-clean.

- include <utility> @5
- include "AudioDecoderInputTrack.h" @7
- include "GraphDriver.h" @8
- include "MediaInfo.h" @9
- include "MediaTrackGraphImpl.h" @10
- include "VideoUtils.h" @11
- include "gmock/gmock.h" @12
- include "gtest/gtest.h" @13
- include "mozilla/ScopeExit.h" @14
- include "mozilla/gtest/WaitFor.h" @15
- include "nsThreadUtils.h" @16
- class_specifier MockTestGraph @29-69
- function_definition MockTestGraph @31-34
- function_definition Init @36-43
- function_definition ~MockTestGraph @49-49
- class_specifier MockDriver @51-68
- function_definition MockDriver @54-57
- function_definition ~MockDriver @67-67
- function_definition CreateAudioDataFromInfo @71-75
- function_definition CreateTrack @77-84
- class_specifier TestAudioDecoderInputTrack @86-140
- function_definition SetUp @88-96
- function_definition TearDown @98-105
- function_definition CreateAudioData @107-109
- function_definition GetTrackSegment @111-111
- function_definition ExpectSegmentNonSilence @113-123
- function_definition ExpectSegmentSilence @125-135
- function_definition TEST_F @142-185
- function_definition TEST_F @187-246
- function_definition TEST_F @248-264
- function_definition TEST_F @266-304
- function_definition TEST_F @306-333
- function_definition TEST_F @335-370
- function_definition TEST_F @372-391
- function_definition TEST_F @393-427
- function_definition TEST @432-462

### dom/media/gtest/TestAudioDeviceEnumerator.cpp

Blob: `67f7591db9d66edeec8a2892bc909207e95eea8b`. Grammar: cpp. Status: contains-errors.

- include "AudioDeviceInfo.h" @5
- include "CubebDeviceEnumerator.h" @6
- include "MockCubeb.h" @7
- include "gmock/gmock.h" @8
- include "gtest/gtest-printers.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/media/MediaUtils.h" @11
- include "nsTArray.h" @12
- enum_specifier DeviceOperation @36-36
- function_definition TestEnumeration @38-90
- function_definition TEST @93-128
- function_definition TEST @130-191
- function_definition TEST @194-221
- function_definition TEST @224-240
- function_definition TEST @242-285
- function_definition TEST @287-326
- function_definition TEST @328-385
- function_definition TEST @387-435

### dom/media/gtest/TestAudioInputProcessing.cpp

Blob: `d57d873bd7eca8333fcc9823b9c74065b2236355`. Grammar: cpp. Status: syntax-clean.

- include "AudioGenerator.h" @5
- include "MediaEngineWebRTCAudio.h" @6
- include "MediaTrackGraphImpl.h" @7
- include "PrincipalHandle.h" @8
- include "gmock/gmock.h" @9
- include "gtest/gtest.h" @10
- include "libwebrtcglue/SystemTime.h" @11
- include "libwebrtcglue/WebrtcEnvironmentWrapper.h" @12
- include "mozilla/NullPrincipal.h" @13
- include "nsContentUtils.h" @14
- include "nsTArray.h" @15
- class_specifier MockGraph @25-65
- function_definition MockGraph @27-30
- function_definition Init @32-49
- function_definition ForceOutputDeviceForAEC @51-53
- function_definition ForceDefaultOutputDevice @55-57
- function_definition UpdateEnumeratorDefaultDeviceTracking @59-59
- function_definition ~MockGraph @64-64
- function_definition TEST @71-240
- function_definition TEST @242-357
- function_definition TEST @359-451
- function_definition TEST @453-473
- function_definition TEST @475-495
- function_definition operator== @498-504
- function_definition (anonymous) @506-528
- function_definition TEST @531-732
- function_definition TEST @734-830

### dom/media/gtest/TestAudioInputSource.cpp

Blob: `e0d477b9615400d380436595a3eeaca9f3063339`. Grammar: cpp. Status: syntax-clean.

- include "AudioInputSource.h" @5
- include "MockCubeb.h" @6
- include "gmock/gmock.h" @7
- include "gtest/gtest.h" @8
- include "mozilla/Result.h" @9
- include "mozilla/gtest/WaitFor.h" @10
- include "nsContentUtils.h" @11
- class_specifier MockAudioEventListener @26-36
- function_definition ~MockAudioEventListener @35-35
- function_definition TEST @38-105
- function_definition TEST @107-188
- function_definition TEST @190-238
- function_definition TEST @240-286
- function_definition TEST @288-365

### dom/media/gtest/TestAudioMixer.cpp

Blob: `c98086061a31def8599cd781ab516372c206af07`. Grammar: cpp. Status: syntax-clean.

- include "AudioMixer.h" @5
- include "gtest/gtest.h" @6
- struct_specifier MixerConsumer @13-31
- function_definition MixerCallback @16-30
- function_definition GetLowValue @42-44
- function_definition GetLowValue @47-49
- function_definition GetHighValue @52-54
- function_definition GetHighValue @57-59
- function_definition FillBuffer @61-67
- function_definition TEST @69-174

### dom/media/gtest/TestAudioPacketizer.cpp

Blob: `e9ae8db4ebb05ab3b2f678a5f7b5fc6b6aaf55b3`. Grammar: cpp. Status: syntax-clean.

- include <math.h> @5
- include <stdint.h> @6
- include <memory> @8
- include "../AudioPacketizer.h" @10
- include "../TimedPacketizer.h" @11
- include "gtest/gtest.h" @12
- class_specifier AutoBuffer @17-25
- function_definition AutoBuffer @19-19
- function_definition ~AutoBuffer @20-20
- function_definition Get @21-21
- function_definition Sequence @27-33
- function_definition IsSequence @35-41
- function_definition Zero @43-48
- function_definition sine @50-50
- function_definition TEST @52-164
- function_definition TEST @166-195

### dom/media/gtest/TestAudioRingBuffer.cpp

Blob: `497f9f02213cb86f18bf3402757b1410487776e0`. Grammar: cpp. Status: syntax-clean.

- include "AudioRingBuffer.h" @5
- include "gmock/gmock.h" @6
- include "gtest/gtest.h" @7
- include "mozilla/PodOperations.h" @8
- function_definition TEST @13-89
- function_definition TEST @91-167
- function_definition TEST @169-271
- function_definition TEST @273-375
- function_definition TEST @377-425
- function_definition TEST @427-475
- function_definition TEST @477-612
- function_definition TEST @614-749
- function_definition TEST @751-791
- function_definition TEST @793-833
- function_definition TEST @835-857
- function_definition TEST @859-883
- function_definition TEST @885-911
- function_definition TEST @913-952
- function_definition TEST @954-993
- function_definition TEST @995-1018
- function_definition TEST @1020-1043
- function_definition TEST @1045-1068
- function_definition TEST @1070-1093
- function_definition TEST @1095-1115
- function_definition TEST @1117-1137
- function_definition TEST @1139-1174
- function_definition TEST @1176-1211
- function_definition TEST @1213-1248
- function_definition TEST @1250-1285
- function_definition TEST @1287-1311

### dom/media/gtest/TestAudioSampleFormat.cpp

Blob: `eccade374a6c947e9f2bb09c577eb29ce9ecc52c`. Grammar: cpp. Status: syntax-clean.

- include <type_traits> @6
- include "AudioSampleFormat.h" @8
- include "gtest/gtest.h" @9
- function_definition LowestSample @14-20
- function_definition HighestSample @25-31
- function_definition HighestSampleExpected @36-55
- function_definition TestSampleTypePair @58-66
- function_definition TestSampleType24bits @69-90
- function_definition TEST @92-116

### dom/media/gtest/TestAudioSegment.cpp

Blob: `953463b9c79864c356b75a1d454bfbdff070d29a`. Grammar: cpp. Status: contains-errors.

- include "AudioGenerator.h" @5
- include "AudioSegment.h" @6
- include "gtest/gtest.h" @7
- function_definition GetLowValue @25-27
- function_definition GetLowValue @30-32
- function_definition GetHighValue @35-37
- function_definition GetHighValue @40-42
- function_definition GetSilentValue @45-47
- function_definition GetSilentValue @50-52
- function_definition GetPlanarChannelArray @57-66
- function_definition DeletePlanarChannelsArray @69-74
- function_definition GetPlanarArray @77-86
- function_definition DeletePlanarArray @89-94
- function_definition GetInterleavedChannelArray @99-107
- function_definition DeleteInterleavedChannelArray @110-112
- function_definition FuzzyEqual @114-114
- function_definition TestInterleaveAndConvert @117-138
- function_definition TestDeinterleaveAndConvert @141-161
- function_definition SilentChannel @166-168
- function_definition TestUpmixStereo @171-194
- function_definition TestDownmixStereo @197-226
- function_definition TEST @228-242
- function_definition fillChunk @245-264
- function_definition TEST @266-275
- function_definition TEST @277-301
- function_definition TEST @303-337
- function_definition TEST @339-353
- function_definition TEST @355-361
- function_definition TEST @363-374
- function_definition TEST @376-443
- function_definition TEST @445-467

### dom/media/gtest/TestAudioSinkWrapper.cpp

Blob: `c0fd5a47de2188ede0eb3019d192bef8b6ebd34b`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include "AudioSampleFormat.h" @7
- include "AudioSink.h" @8
- include "AudioSinkWrapper.h" @9
- include "CubebUtils.h" @10
- include "MediaData.h" @11
- include "MediaSinkTestUtils.h" @12
- include "MockCubeb.h" @13
- include "TimeUnits.h" @14
- include "gmock/gmock.h" @15
- include "gtest/gtest-printers.h" @16
- include "gtest/gtest.h" @17
- include "mozilla/Preferences.h" @18
- include "mozilla/SpinEventLoopUntil.h" @19
- include "mozilla/SyncRunnable.h" @20
- include "mozilla/gtest/WaitFor.h" @21
- include "nsThreadManager.h" @22
- include "nsThreadUtils.h" @23
- function_definition TEST @29-91
- function_definition TEST @95-138
- function_definition TEST @146-211
- enum_specifier ReuseStream @214-214
- class_specifier AudioSinkWrapperReuseTest @221-600
- function_definition SetUp @223-226
- function_definition TearDown @229-238
- function_definition CreateWrapper @240-255
- function_definition ProcessPending @257-257
- function_definition Start @260-264
- function_definition SeekStop @268-272
- function_definition OutputLatencyFrames @285-285
- function_definition PushAudio @306-315
- function_definition DriveCallback @322-332
- function_definition TakeRecorded @337-339
- function_definition DrainRecordedOutput @346-357
- function_definition ResumeWithData @359-364
- function_definition SeekAndSupplyPostSeekAudio @368-372
- function_definition PlayAudioFromStart @374-383
- function_definition PlayPreSeekThenSeek @390-400
- function_definition SamplesMatchingNum @402-406
- function_definition AudibleSamplesNum @408-411
- function_definition ExpectClockNotAhead @416-424
- function_definition ExpectClockHeldAt @428-434
- function_definition PlayFromZeroToSteadyState @441-459
- function_definition SeekAndResumeAt @462-478
- function_definition ExpectClockHoldsAtTargetWhileSilent @485-501
- function_definition ExpectClockFollowsAudioOncePlaying @507-554
- function_definition StartMutedSeekResume @558-563
- function_definition AdvanceMutedSystemClockPastTarget @567-574
- function_definition ExpectUnmuteDoesNotRegressClock @579-583
- function_definition TEST_F @602-608
- function_definition TEST_F @610-625
- function_definition TEST_F @627-639
- function_definition TEST_F @641-653
- function_definition RunReuseAcrossSeek @658-683
- function_definition TEST_F @685-687
- function_definition TEST_F @689-691
- function_definition TEST_F @695-710
- function_definition TEST_F @716-739
- function_definition TEST_F @746-797
- function_definition TEST_F @804-850
- function_definition TEST_F @856-885
- function_definition TEST_F @892-909
- function_definition TEST_F @914-933
- function_definition TEST_F @939-977
- function_definition TEST_F @982-997
- function_definition TEST_F @1002-1016
- function_definition TEST_F @1026-1047
- function_definition RunSeekResumeClockFollowsAudible @1057-1068
- function_definition TEST_F @1070-1073
- function_definition TEST_F @1075-1078
- function_definition TEST_F @1083-1109
- function_definition RunMutedSeekResumeThenUnmuteDoesNotRegress @1122-1128
- function_definition TEST_F @1130-1133
- function_definition TEST_F @1135-1138

### dom/media/gtest/TestAudioStream.cpp

Blob: `45731500f0a10a812a23f9bea209cec9a5a59dae`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include "AudioStream.h" @7
- include "CubebUtils.h" @8
- include "MockCubeb.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/gtest/WaitFor.h" @11
- class_specifier TestDataSource @17-52
- function_definition TestDataSource @19-20
- function_definition AppendFrames @22-27
- function_definition PendingFrames @29-31
- function_definition PopFrames @33-44
- function_definition Ended @46-46
- function_definition TEST @56-110

### dom/media/gtest/TestAudioTrackEncoder.cpp

Blob: `20f1959b5930ce159f77b7898578a9d9be6979f8`. Grammar: cpp. Status: syntax-clean.

- include "AudioGenerator.h" @5
- include "AudioSampleFormat.h" @6
- include "OpusTrackEncoder.h" @7
- include "gtest/gtest.h" @8
- class_specifier TestOpusTrackEncoder @12-27
- function_definition TestOpusTrackEncoder @14-16
- function_definition TestOpusRawCreation @19-26
- function_definition TestOpusInit @29-33
- function_definition TEST @35-64
- function_definition TEST @66-155
- function_definition TestOpusResampler @157-161
- function_definition TEST @163-177
- function_definition TEST @179-193
- function_definition TEST @195-223
- function_definition TEST @225-252
- function_definition TestSampleRate @254-280
- function_definition TEST @282-296

### dom/media/gtest/TestAudioTrackGraph.cpp

Blob: `c4049f9386a3c21dde15fa8b19f31348648740f6`. Grammar: cpp. Status: contains-errors.

- include "CrossGraphPort.h" @5
- include "DeviceInputTrack.h" @6
- include "MediaTrackGraphImpl.h" @7
- include "StaticComponents.h" @8
- include "VideoUtils.h" @9
- include "gmock/gmock.h" @10
- include "gtest/gtest-printers.h" @11
- include "gtest/gtest.h" @12
- include "MediaEngineWebRTCAudio.h" @14
- include "MockCubeb.h" @16
- include "WavDumper.h" @17
- include "mozilla/Components.h" @18
- include "mozilla/CycleCollectedJSContext.h" @19
- include "mozilla/GenericFactory.h" @20
- include "mozilla/Preferences.h" @21
- include "mozilla/SpinEventLoopUntil.h" @22
- include "mozilla/StateMirroring.h" @23
- include "mozilla/gtest/MozHelpers.h" @24
- include "mozilla/gtest/WaitFor.h" @25
- include "mozilla/ipc/IOThread.h" @26
- include "nsComponentManager.h" @27
- include "nsITargetShutdownTask.h" @28
- include "nsIThreadInternal.h" @29
- include "nsXPCOMPrivate.h" @30
- struct_specifier StartInputProcessing @74-84
- function_definition StartInputProcessing @78-82
- function_definition Run @83-83
- struct_specifier StopInputProcessing @86-93
- function_definition StopInputProcessing @89-91
- function_definition Run @92-92
- function_definition QueueApplySettings @95-107
- function_definition QueueExpectIsPassThrough @109-115
- class_specifier GoFaster @118-125
- function_definition GoFaster @122-123
- function_definition Run @124-124
- struct_specifier StartNonNativeInput @127-137
- function_definition StartNonNativeInput @131-135
- function_definition Run @136-136
- struct_specifier StopNonNativeInput @139-145
- function_definition StopNonNativeInput @142-143
- function_definition Run @144-144
- class_specifier OnFallbackListener @149-165
- function_definition OnFallbackListener @154-154
- function_definition Reset @156-156
- function_definition OnFallback @157-157
- function_definition NotifyOutput @159-164
- class_specifier MockAudioDataListener @167-186
- function_definition ~MockAudioDataListener @169-169
- function_definition MockAudioDataListener @172-172
- class_specifier MockProcessedMediaTrack @188-217
- function_definition MockProcessedMediaTrack @190-208
- function_definition NumberOfChannels @216-216
- function_definition TEST_WithTailDispatch @235-282
- function_definition TEST_WithTailDispatch @284-310
- function_definition TEST_WithTailDispatch @312-347
- function_definition TEST_WithTailDispatch @349-388
- function_definition TEST_WithTailDispatch @390-404
- function_definition TEST_WithTailDispatch @406-434
- function_definition TEST_WithTailDispatch @436-603
- struct_specifier DeviceInfo @468-471
- struct_specifier DeviceQueryMessage @475-493
- function_definition DeviceQueryMessage @479-483
- function_definition Run @484-492
- function_definition TEST_WithTailDispatch @605-674
- class_specifier TestDeviceInputConsumerTrack @676-717
- function_definition Create @678-684
- function_definition Destroy @686-690
- function_definition ProcessInput @692-703
- function_definition NumberOfChannels @705-712
- function_definition TestDeviceInputConsumerTrack @715-716
- function_definition TEST_WithTailDispatch @719-802
- class_specifier TestAudioDataListener @728-745
- function_definition TestAudioDataListener @730-741
- function_definition ~TestAudioDataListener @744-744
- function_definition TEST_WithTailDispatch @819-1055
- class_specifier TestAudioDataListener @833-859
- function_definition TestAudioDataListener @835-842
- function_definition SetInputChannelCount @844-855
- function_definition ~TestAudioDataListener @858-858
- function_definition TEST_WithTailDispatch @1061-1243
- class_specifier TestAudioDataListener @1062-1074
- function_definition TestAudioDataListener @1064-1070
- function_definition ~TestAudioDataListener @1073-1073
- function_definition TEST_WithTailDispatch @1246-1308
- function_definition TEST_WithTailDispatch @1310-1398
- function_definition TEST_WithTailDispatch @1400-1572
- function_definition rmsf32 @1576-1589
- function_definition TEST_WithTailDispatch @1591-1721
- function_definition TEST_WithTailDispatch @1723-1837
- function_definition TEST_WithTailDispatch @1848-2082
- function_definition TEST_WithTailDispatch @2084-2141
- function_definition TEST_WithTailDispatch @2143-2206
- function_definition TEST_WithTailDispatch @2208-2272
- function_definition TEST_WithTailDispatch @2278-2459
- function_definition TestCrossGraphPort @2461-2665
- function_definition TEST_WithTailDispatch @2667-2683
- function_definition TEST_WithTailDispatch @2685-2697
- function_definition TEST_WithTailDispatch @2699-2801
- function_definition TEST_WithTailDispatch @2804-2905
- function_definition TEST_WithTailDispatch @2908-3124
- function_definition TEST_WithTailDispatch @3126-3382
- function_definition TEST_WithTailDispatch @3384-3453
- function_definition TEST_WithTailDispatch @3455-3568
- class_specifier TrackDestroyShutdownFactory @3570-3593
- function_definition ~TrackDestroyShutdownFactory @3571-3571
- function_definition TrackDestroyShutdownFactory @3576-3577
- function_definition CreateInstance @3579-3588
- function_definition TEST_WithTailDispatch @3597-3663
- function_definition TEST @3665-3892
- class_specifier TestRunnable @3895-3923
- function_definition Run @3905-3908
- function_definition OnDiscard @3910-3912
- function_definition ~TestRunnable @3915-3917
- function_definition TEST @3933-4146
- class_specifier MicroTaskDispatcher @4154-4169
- function_definition MicroTaskDispatcher @4156-4158
- function_definition Run @4160-4163
- function_definition TEST @4176-4282
- class_specifier TestShutdownTask @4285-4306
- function_definition TargetShutdown @4293-4299
- function_definition ~TestShutdownTask @4302-4302
- function_definition TEST @4311-4403
- class_specifier IPCTestRunnable @4411-4427
- function_definition IPCTestRunnable @4413-4416
- function_definition OnDiscard @4418-4421
- function_definition ~IPCTestRunnable @4424-4424
- function_definition TEST @4430-4522
- function_definition TEST @4524-4635

### dom/media/gtest/TestBitWriter.cpp

Blob: `9afc1cd85ac0652e3eeeef970612d06e449ce4aa`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @5
- include "BitReader.h" @7
- include "BitWriter.h" @8
- include "gtest/gtest.h" @9
- function_definition TEST @13-57
- function_definition TEST @59-76

### dom/media/gtest/TestBlankVideoDataCreator.cpp

Blob: `b7d99e3aa08e170d91cf28a896bed2bd96405509`. Grammar: cpp. Status: syntax-clean.

- include "BlankDecoderModule.h" @5
- include "ImageContainer.h" @6
- include "gtest/gtest.h" @7
- function_definition TEST @11-19
- function_definition TEST @21-29

### dom/media/gtest/TestBufferMediaResource.cpp

Blob: `5fbbc265e37cdb0288ecce00450565fbe3a6b17b`. Grammar: cpp. Status: syntax-clean.

- include "BufferMediaResource.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/RefPtr.h" @7
- function_definition TEST @11-20
- function_definition TEST @22-31
- function_definition TEST @33-46
- function_definition TEST @48-57
- function_definition TEST @59-68
- function_definition TEST @70-83

### dom/media/gtest/TestBufferReader.cpp

Blob: `7fe8690d6d7ca715e555bda50d283cd0326a1464`. Grammar: cpp. Status: syntax-clean.

- include "BufferReader.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @10-37
- function_definition TEST @39-52

### dom/media/gtest/TestCDMStorage.cpp

Blob: `1962dd844a6e09470b8b50cb4907f135b6129fde`. Grammar: cpp. Status: contains-errors.

- include "ChromiumCDMCallback.h" @5
- include "ChromiumCDMParent.h" @6
- include "GMPServiceParent.h" @7
- include "GMPTestMonitor.h" @8
- include "MediaResult.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/RefPtr.h" @11
- include "mozilla/SchedulerGroup.h" @12
- include "mozilla/SpinEventLoopUntil.h" @13
- include "mozilla/gtest/MozAssertions.h" @14
- include "nsCRTGlue.h" @15
- include "nsDirectoryServiceDefs.h" @16
- include "nsDirectoryServiceUtils.h" @17
- include "nsIFile.h" @18
- include "nsNSSComponent.h" @19
- include "nsThreadUtils.h" @20
- function_definition GetGMPThread @25-31
- function_definition EnumerateDir @37-49
- function_definition EnumerateCDMStorageDir @56-81
- class_specifier GMPShutdownObserver @83-125
- function_definition GMPShutdownObserver @85-90
- function_definition Run @92-104
- function_definition Observe @106-118
- function_definition ~GMPShutdownObserver @121-121
- class_specifier NotifyObserversTask @129-143
- function_definition NotifyObserversTask @131-132
- function_definition Run @133-141
- class_specifier ClearCDMStorageTask @145-187
- function_definition ClearCDMStorageTask @147-149
- function_definition Run @151-168
- function_definition Observe @170-180
- function_definition ~ClearCDMStorageTask @183-183
- function_definition ClearCDMStorage @191-196
- function_definition SimulatePBModeExit @198-205
- class_specifier TestGetNodeIdCallback @207-220
- function_definition TestGetNodeIdCallback @209-210
- function_definition Done @212-215
- function_definition GetNodeIdParts @222-239
- function_definition GetNodeId @241-271
- function_definition IsCDMStorageIsEmpty @273-285
- function_definition AssertIsOnGMPThread @287-298
- class_specifier CDMStorageTest @300-1201
- function_definition DoTest @303-309
- function_definition CDMStorageTest @311-311
- function_definition Update @313-317
- function_definition TestGetNodeId @319-358
- function_definition TestGetNodeId_Continuation @360-371
- function_definition CreateDecryptor @373-379
- function_definition CreateDecryptor @381-387
- function_definition CreateDecryptor @389-422
- function_definition TestBasicStorage @424-440
- function_definition TestForgetThisSite @448-460
- function_definition TestForgetThisSite_AnotherSite @462-473
- struct_specifier NodeInfo @475-482
- function_definition NodeInfo @476-478
- class_specifier NodeIdCollector @484-498
- function_definition NodeIdCollector @486-486
- function_definition operator() @487-494
- function_definition TestForgetThisSite_CollectSiteInfo @500-511
- function_definition TestForgetThisSite_Forget @513-530
- class_specifier NodeIdVerifier @532-560
- function_definition NodeIdVerifier @534-536
- function_definition operator() @537-550
- function_definition ~NodeIdVerifier @551-555
- class_specifier StorageVerifier @562-582
- function_definition StorageVerifier @564-565
- function_definition operator() @566-573
- function_definition ~StorageVerifier @574-578
- function_definition TestForgetThisSite_Verify @584-591
- function_definition TestForgetThisBaseDomain @599-611
- function_definition TestForgetThisBaseDomain_SecondSite @613-624
- function_definition TestForgetThisBaseDomain_ThirdSite @626-638
- struct_specifier BaseDomainNodeInfo @640-646
- function_definition BaseDomainNodeInfo @641-642
- class_specifier BaseDomainNodeIdCollector @648-663
- function_definition BaseDomainNodeIdCollector @650-651
- function_definition operator() @652-659
- function_definition TestForgetThisBaseDomain_CollectSiteInfo @665-674
- function_definition TestForgetThisBaseDomain_Forget @676-696
- class_specifier BaseDomainNodeIdVerifier @698-725
- function_definition BaseDomainNodeIdVerifier @700-702
- function_definition operator() @703-715
- function_definition ~BaseDomainNodeIdVerifier @716-720
- class_specifier BaseDomainStorageVerifier @727-749
- function_definition BaseDomainStorageVerifier @729-730
- function_definition operator() @731-739
- function_definition ~BaseDomainStorageVerifier @740-745
- function_definition TestForgetThisBaseDomain_Verify @751-760
- function_definition TestClearRecentHistory1 @769-781
- function_definition TestClearRecentHistory2 @790-802
- function_definition TestClearRecentHistory3 @811-823
- class_specifier MaxMTimeFinder @825-840
- function_definition MaxMTimeFinder @827-827
- function_definition operator() @828-835
- function_definition GetResult @836-836
- function_definition TestClearRecentHistory1_Clear @842-852
- function_definition TestClearRecentHistory2_Clear @854-864
- function_definition TestClearRecentHistory3_Clear @866-876
- class_specifier FileCounter @878-886
- function_definition FileCounter @880-880
- function_definition operator() @881-881
- function_definition GetCount @882-882
- function_definition TestClearRecentHistory_CheckEmpty @888-903
- function_definition TestClearRecentHistory_CheckNonEmpty @905-921
- function_definition TestCrossOriginStorage @923-945
- function_definition TestCrossOriginStorage_RecordStoredContinuation @947-959
- function_definition TestPBStorage @961-976
- function_definition TestPBStorage_RecordStoredContinuation @978-989
- function_definition TestPBStorage_RecordRetrievedContinuation @991-1001
- function_definition TestOutputProtection @1004-1013
- function_definition TestLongRecordNames @1016-1068
- function_definition Expect @1070-1074
- function_definition AwaitFinished @1076-1080
- function_definition ShutdownThen @1082-1093
- function_definition Shutdown @1095-1101
- function_definition Dummy @1103-1103
- function_definition SetFinished @1105-1111
- function_definition SessionMessage @1113-1129
- function_definition Terminated @1131-1136
- function_definition ~CDMStorageTest @1139-1139
- struct_specifier ExpectedMessage @1141-1147
- function_definition ExpectedMessage @1142-1144
- class_specifier CallbackProxy @1156-1198
- function_definition CallbackProxy @1158-1158
- function_definition SetSessionId @1160-1161
- function_definition ResolveLoadSessionPromise @1163-1164
- function_definition ResolvePromiseWithKeyStatus @1166-1167
- function_definition ResolvePromise @1169-1169
- function_definition RejectPromise @1171-1172
- function_definition SessionMessage @1174-1178
- function_definition SessionKeysChange @1180-1182
- function_definition ExpirationChange @1184-1185
- function_definition SessionClosed @1187-1187
- function_definition QueryOutputProtectionStatus @1189-1189
- function_definition Terminated @1191-1191
- function_definition Shutdown @1193-1193
- function_definition CreateTestDirectory @1203-1217
- function_definition TestMatchBaseDomain_MatchOrigin @1219-1233
- function_definition TestMatchBaseDomain_MatchTLD @1235-1249
- function_definition TestMatchBaseDomain_NoMatch @1251-1265
- function_definition TEST @1267-1270
- function_definition TEST @1272-1275
- function_definition TEST @1277-1280
- function_definition TEST @1282-1286
- function_definition TEST @1288-1292
- function_definition TEST @1294-1298
- function_definition TEST @1300-1304
- function_definition TEST @1306-1310
- function_definition TEST @1312-1316
- function_definition TEST @1318-1322
- function_definition TEST @1324-1328
- function_definition TEST @1330-1334
- function_definition TEST @1336-1340
- function_definition TEST @1343-1347

### dom/media/gtest/TestCamerasParent.cpp

Blob: `60a7c3a898f69f3ff242ed0d6e3acd06f10f1897`. Grammar: cpp. Status: contains-errors.

- include <memory> @5
- include "CamerasParent.h" @7
- include "VideoEngine.h" @8
- include "api/video/i420_buffer.h" @9
- include "fake_video_capture/device_info_empty.h" @10
- include "fake_video_capture/device_info_fake.h" @11
- include "gmock/gmock.h" @12
- include "gtest/gtest.h" @13
- include "mozilla/SyncRunnable.h" @14
- include "mozilla/gtest/WaitFor.h" @15
- include "mozilla/ipc/BackgroundParent.h" @16
- include "video_engine/video_capture_factory.h" @17
- function_definition RunOnBackgroundThread @33-38
- function_definition WaitForBackgroundThread @40-42
- class_specifier MockCamerasParent @44-66
- function_definition MockCamerasParent @46-46
- function_definition Create @49-59
- class_specifier MockVideoCapturer @68-95
- function_definition MockVideoCapturer @86-94
- class_specifier MockVideoCaptureFactory @98-126
- function_definition MockVideoCaptureFactory @105-122
- class_specifier TestableCamerasParent @128-150
- function_definition TestableCamerasParent @130-130
- function_definition Create @133-143
- struct_specifier TestCamerasParent @152-170
- function_definition SetUpTestSuite @155-161
- function_definition SetUp @163-163
- function_definition TearDown @165-169
- function_definition TEST_F @172-172
- function_definition TEST_F @174-228
- struct_specifier TestAggregateCapturerWithDeviceInfo @231-290
- function_definition SetUp @255-276
- function_definition TearDown @278-289
- function_definition TEST_F @297-299
- function_definition TEST_F @301-305
- function_definition TEST_F @307-318
- function_definition TEST_F @320-342
- function_definition TEST_F @344-360
- function_definition TEST_F @362-388
- function_definition TEST_F @390-445
- function_definition TEST_F @447-460
- function_definition TEST @462-477

### dom/media/gtest/TestCubebInputStream.cpp

Blob: `3c00a33dc5ec34b34c35125d27bdfa0921b22744`. Grammar: cpp. Status: syntax-clean.

- include "CubebInputStream.h" @5
- include "MockCubeb.h" @6
- include "gmock/gmock.h" @7
- include "gtest/gtest.h" @8
- include "mozilla/gtest/WaitFor.h" @9
- class_specifier MockListener @18-27
- function_definition ~MockListener @26-26
- function_definition TEST @29-84
- function_definition TEST @86-131
- function_definition TEST @133-184

### dom/media/gtest/TestDataMutex.cpp

Blob: `02f5785a060f0fc3cc722a992b8aa8e76dd08f27`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @5
- include "mozilla/DataMutex.h" @6
- include "nsTArray.h" @7
- struct_specifier A @11-14
- function_definition Set @12-12
- function_definition TEST @16-45

### dom/media/gtest/TestDecodedStream.cpp

Blob: `1d8a4be97372813b6557f27dabd2dbe5f1ae264a`. Grammar: cpp. Status: syntax-clean.

- include "BlankDecoderModule.h" @5
- include "DecodedStream.h" @6
- include "MediaData.h" @7
- include "MediaQueue.h" @8
- include "MediaSinkTestUtils.h" @9
- include "MediaTrackGraphImpl.h" @10
- include "MediaTrackListener.h" @11
- include "MockCubeb.h" @12
- include "gtest/gtest.h" @13
- include "mozilla/SyncRunnable.h" @14
- include "mozilla/gtest/WaitFor.h" @15
- include "nsJSEnvironment.h" @16
- enum_specifier MediaType @22-22
- function_definition CreateOutputTracks @25-37
- function_definition CreateMediaInfo @40-50
- class_specifier OnFallbackListener @52-68
- function_definition OnFallbackListener @57-57
- function_definition Reset @59-59
- function_definition OnFallback @60-60
- function_definition NotifyOutput @62-67
- class_specifier TestDecodedStream @71-205
- function_definition TestDecodedStream @85-91
- function_definition SetUp @93-140
- function_definition TearDown @142-202
- function_definition CreateMediaInfo @204-204
- function_definition TEST_F @211-217

### dom/media/gtest/TestDeviceInputTrack.cpp

Blob: `7b683ee9e7205c450d2d8b383c4110d0c042f386`. Grammar: cpp. Status: syntax-clean.

- include "AudioGenerator.h" @5
- include "DeviceInputTrack.h" @6
- include "MediaTrackGraphImpl.h" @7
- include "MockCubeb.h" @8
- include "gmock/gmock.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/StaticPrefs_media.h" @11
- include "mozilla/gtest/WaitFor.h" @12
- include "nsContentUtils.h" @13
- class_specifier MockGraphImpl @24-64
- function_definition MockGraphImpl @26-29
- function_definition Init @31-38
- function_definition ~MockGraphImpl @44-44
- class_specifier MockDriver @46-63
- function_definition MockDriver @49-52
- function_definition ~MockDriver @62-62
- class_specifier TestDeviceInputTrack @66-80
- function_definition TestDeviceInputTrack @68-68
- function_definition SetUp @70-73
- function_definition TearDown @75-75
- function_definition TEST_F @82-176
- class_specifier TestDeviceInputConsumerTrack @83-114
- function_definition Create @85-91
- function_definition Destroy @93-97
- function_definition NumberOfChannels @102-109
- function_definition TestDeviceInputConsumerTrack @112-113
- class_specifier TestAudioDataListener @116-153
- function_definition TestAudioDataListener @118-119
- function_definition RequestedInputChannelCount @121-125
- function_definition RequestedInputProcessingParams @126-129
- function_definition IsVoiceInput @130-132
- function_definition DeviceChanged @133-133
- function_definition NotifySetRequestedInputProcessingParams @135-139
- function_definition NotifySetRequestedInputProcessingParamsResult @140-144
- function_definition ~TestAudioDataListener @147-147
- function_definition TEST_F @178-234
- class_specifier MockEventListener @236-246
- function_definition ~MockEventListener @245-245
- function_definition TEST_F @248-349
- function_definition TEST_F @351-444
- function_definition TEST_F @446-501
- function_definition TEST_F @503-560

### dom/media/gtest/TestDriftCompensation.cpp

Blob: `8f04ec4c6418a92fda99cbe1547d7c918cf646ab`. Grammar: cpp. Status: syntax-clean.

- include "DriftCompensation.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/SpinEventLoopUntil.h" @7
- class_specifier DriftCompensatorTest @11-41
- function_definition DriftCompensatorTest @17-32
- function_definition Past @35-37
- function_definition Future @40-40
- function_definition TEST_F @43-45
- function_definition TEST_F @47-55
- function_definition TEST_F @57-65
- function_definition TEST_F @67-74
- function_definition TEST_F @76-84

### dom/media/gtest/TestFFmpegDecodeStats.cpp

Blob: `325d7277d772895f3e36d7991839095d6f790fed`. Grammar: cpp. Status: syntax-clean.

- include <chrono> @7
- include <thread> @8
- include "FFmpegDecodeStats.h" @10
- include "gtest/gtest.h" @11
- function_definition InsertSlowFrame @26-30
- function_definition InsertFastFrame @32-35
- function_definition TEST @37-41
- function_definition TEST @43-52
- function_definition TEST @54-61
- function_definition TEST @63-77
- function_definition TEST @79-88

### dom/media/gtest/TestGMPCrossOrigin.cpp

Blob: `f8a14396df8ee7c5ba728cd06f36e69f81f2f2d0`. Grammar: cpp. Status: contains-errors.

- include "GMPServiceParent.h" @5
- include "GMPTestMonitor.h" @6
- include "GMPVideoDecoderProxy.h" @7
- include "GMPVideoEncoderProxy.h" @8
- include "gtest/gtest.h" @9
- include "mozilla/StaticPtr.h" @10
- include "mozilla/gtest/MozAssertions.h" @11
- include "nsAppDirectoryServiceDefs.h" @12
- include "nsThreadUtils.h" @13
- struct_specifier GMPTestRunner @18-33
- function_definition GMPTestRunner @21-21
- function_definition ~GMPTestRunner @32-32
- class_specifier RunTestGMPVideoCodec @39-73
- function_definition Done @41-48
- function_definition Run @50-53
- function_definition RunTestGMPVideoCodec @59-60
- function_definition Get @62-70
- function_definition RunTestGMPTestCodec1 @82-84
- function_definition RunTestGMPTestCodec2 @86-88
- function_definition RunTestGMPTestCodec3 @90-92
- class_specifier RunTestGMPCrossOrigin @95-153
- function_definition Done @97-107
- function_definition Run @109-118
- function_definition RunTestGMPCrossOrigin @121-126
- class_specifier Step2 @128-148
- function_definition Step2 @130-132
- function_definition Done @133-143
- function_definition RunTestGMPCrossOrigin1 @160-162
- function_definition RunTestGMPCrossOrigin2 @164-166
- function_definition RunTestGMPCrossOrigin3 @168-170
- function_definition RunTestGMPCrossOrigin4 @172-174
- function_definition DoTest @176-188
- function_definition TEST @190-196
- function_definition TEST @198-205

### dom/media/gtest/TestGMPPluginScan.cpp

Blob: `55cea40296299360af745f89807057701ff46d5f`. Grammar: cpp. Status: syntax-clean.

- include "GMPUtils.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/MozPromise.h" @7
- include "mozilla/gtest/WaitFor.h" @8
- include "nsString.h" @9
- include "nsTArray.h" @10
- include "nsThreadUtils.h" @11
- function_definition ExpectPluginsFromEnvironment @22-33
- function_definition TEST @35-38
- function_definition TEST @40-57

### dom/media/gtest/TestGMPRemoveAndDelete.cpp

Blob: `fe5b29cb397f4aab90a5db8be341ba56d191c0f6`. Grammar: cpp. Status: contains-errors.

- include "GMPService.h" @5
- include "GMPServiceParent.h" @6
- include "GMPTestMonitor.h" @7
- include "GMPUtils.h" @8
- include "GMPVideoDecoderProxy.h" @9
- include "gmp-api/gmp-video-host.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/Services.h" @12
- include "mozilla/StaticPtr.h" @13
- include "nsDirectoryServiceDefs.h" @14
- include "nsIObserverService.h" @15
- class_specifier GMPRemoveTest @28-100
- function_definition ReceivedDecodedReferenceFrame @68-69
- function_definition ReceivedDecodedFrame @70-70
- function_definition InputDataExhausted @71-71
- function_definition DrainComplete @72-72
- function_definition ResetComplete @73-73
- function_definition TEST @105-112
- function_definition TEST @117-124
- function_definition TEST @132-151
- function_definition TEST @157-179
- function_definition GetService @185-193
- function_definition GetServiceParent @195-203
- function_definition GMPRemoveTest @207-208
- function_definition ~GMPRemoveTest @210-215
- function_definition Setup @217-241
- function_definition CreateVideoDecoder @243-281
- function_definition gmp_GetVideoDecoder @283-315
- class_specifier Callback @290-306
- function_definition Callback @292-294
- function_definition Done @295-300
- function_definition CloseVideoDecoder @317-325
- function_definition DeletePluginDirectory @327-329
- function_definition Decode @331-339
- function_definition gmp_Decode @341-388
- struct_specifier EncodedFrame @344-364
- struct_specifier SPSNalu @345-348
- struct_specifier PPSNalu @349-352
- struct_specifier IDRNalu @353-363
- function_definition Wait @390-390
- function_definition IsTerminated @392-392
- function_definition Observe @395-408
- function_definition Decoded @411-415
- function_definition Error @418-421
- function_definition Terminated @424-430
- function_definition GeneratePlugin @432-470

### dom/media/gtest/TestGMPUtils.cpp

Blob: `fedd53632599c170d730aea26d65b2d7716fc350`. Grammar: cpp. Status: syntax-clean.

- include <string> @5
- include "GMPUtils.h" @7
- include "gtest/gtest.h" @8
- include "nsString.h" @9
- function_definition TestSplitAt @13-25
- function_definition TEST @27-53
- function_definition TEST @55-80
- struct_specifier Test @57-60

### dom/media/gtest/TestGMPVideoEncodedFrame.cpp

Blob: `35c798e7f7595fed795169c7e91d6978a9d04b5a`. Grammar: cpp. Status: syntax-clean.

- include "GMPVideoEncodedFrameImpl.h" @5
- include "GMPVideoHost.h" @6
- include "gtest/gtest.h" @7
- include "mozilla/gmp/GMPTypes.h" @8
- function_definition TemporalIdAndSize @13-19
- function_definition CheckFrameData @21-24
- function_definition TEST @28-35
- function_definition TEST @38-44
- function_definition TEST @47-52
- function_definition TEST @55-60
- function_definition TEST @63-68

### dom/media/gtest/TestGMPVideoi420Frame.cpp

Blob: `77223747282c920c787aed1ba9f007dc9b64326d`. Grammar: cpp. Status: syntax-clean.

- include <climits> @6
- include "GMPVideoi420FrameImpl.h" @8
- include "gtest/gtest.h" @9
- include "mozilla/gmp/GMPTypes.h" @10
- struct_specifier PlaneData @14-18
- struct_specifier FrameWithBuffer @20-23
- function_definition CalculateBufferSize @25-42
- function_definition MakeFrameData @44-66
- function_definition MakeValidI420Frame @68-82
- function_definition TEST @84-92
- function_definition TEST @94-102
- function_definition TEST @104-112
- function_definition TEST @114-119
- function_definition TEST @121-127
- function_definition TEST @129-135
- function_definition TEST @137-145

### dom/media/gtest/TestGroupId.cpp

Blob: `19cf4f6db8a86e5248cc791d3cb555e674869238`. Grammar: cpp. Status: syntax-clean.

- include "AudioDeviceInfo.h" @5
- include "MediaManager.h" @6
- include "gmock/gmock.h" @7
- include "gtest/gtest-printers.h" @8
- include "gtest/gtest.h" @9
- include "nsTArray.h" @10
- include "webrtc/MediaEngineFake.h" @11
- function_definition PrintTo @16-19
- function_definition PrintTo @20-22
- function_definition MakeAudioDeviceInfo @24-32
- function_definition MakeCameraDevice @34-39
- function_definition MakeMicDevice @41-47
- function_definition MakeSpeakerDevice @49-55
- function_definition TEST @60-77
- function_definition TEST @82-98
- function_definition TEST @102-120
- function_definition TEST @125-152
- function_definition TEST @158-179
- function_definition TEST @184-215
- function_definition TEST @220-238
- function_definition TEST @243-261
- function_definition TEST @266-280
- function_definition TEST @285-299

### dom/media/gtest/TestH264FmtpParser.cpp

Blob: `9694ed8cdb9f08658ce3ede824430eea9d7a6f04`. Grammar: cpp. Status: syntax-clean.

- include "MediaMIMETypes.h" @5
- include "api/rtp_parameters.h" @6
- include "gtest/gtest.h" @7
- include "mozilla/media/webrtc/H264FmtpParser.h" @8
- function_definition Parse @12-19
- function_definition TEST @21-28
- function_definition TEST @30-40
- function_definition TEST @42-49
- function_definition TEST @51-58
- function_definition TEST @60-67
- function_definition TEST @69-77
- function_definition TEST @79-88
- function_definition TEST @90-98
- function_definition TEST @100-108
- function_definition TEST @110-117
- function_definition TEST @119-124
- function_definition TEST @126-131
- function_definition TEST @133-138
- function_definition TEST @140-146
- function_definition TEST @148-154
- function_definition TEST @156-163
- function_definition TEST @165-170
- function_definition TEST @172-179
- function_definition TEST @181-188
- function_definition TEST @190-197
- function_definition TEST @199-211
- function_definition TEST @213-220
- function_definition TEST @222-231
- function_definition TEST @233-241
- function_definition TEST @243-249
- function_definition TEST @251-259
- function_definition TEST @261-266

### dom/media/gtest/TestHDRUtils.cpp

Blob: `83fa04a0a74b6e43c6af8fa421af8d0911eefab4`. Grammar: cpp. Status: syntax-clean.

- include "HDRUtils.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/gfx/Types.h" @7
- function_definition MakeBT2020_1000nit @15-24
- function_definition TEST @28-52
- function_definition TEST @55-77
- function_definition TEST @80-91
- function_definition TEST @94-104
- function_definition TEST @106-118
- function_definition TEST @120-130
- function_definition TEST @132-142

### dom/media/gtest/TestImageConversion.cpp

Blob: `8b81f5384ca85ebb2c415ad11d24d2259411b3ca`. Grammar: cpp. Status: syntax-clean.

- include <iterator> @5
- include "ImageContainer.h" @7
- include "ImageConversion.h" @8
- include "SourceSurfaceRawData.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/CheckedInt.h" @11
- include "mozilla/RefPtr.h" @12
- include "mozilla/UniquePtr.h" @13
- include "mozilla/dom/ImageBitmapBinding.h" @14
- include "mozilla/dom/ImageUtils.h" @15
- struct_specifier YCbCrValue @45-49
- struct_specifier RGBValue @53-58
- function_definition ChromaDivisor @69-79
- class_specifier TestPlanarYCbCrImage @85-195
- function_definition TestPlanarYCbCrImage @87-90
- function_definition TestPlanarYCbCrImage @92-146
- function_definition Fill @149-176
- function_definition CopyData @178-180
- function_definition SizeOfExcludingThis @181-181
- function_definition IsInterleaved @184-187
- function_definition GenerateI420 @202-206
- function_definition CreateSolidSurfaceImage @208-263
- function_definition CreateSurfaceImage @265-274
- function_definition TEST @276-295
- function_definition TEST @297-385
- function_definition TEST @397-415
- function_definition TEST @422-449
- function_definition TEST @451-468
- function_definition TEST @473-530
- function_definition TEST @540-573
- function_definition TEST @575-602
- struct_specifier RGBSample @608-611
- struct_specifier RGBToYUVExpectation @620-625
- function_definition CheckI420Conversion @670-696
- function_definition CheckNV12Conversion @698-719
- function_definition TEST @724-753
- function_definition TEST @755-784
- function_definition ForEachRedSourceImage @789-808
- function_definition TEST @812-822
- function_definition TEST @826-843
- function_definition TEST @847-871
- function_definition TEST @875-900
- function_definition TEST @903-912
- function_definition TEST @914-955
- function_definition TEST @960-996

### dom/media/gtest/TestIntervalSet.cpp

Blob: `c54e08faebb48d346717137230cfd0a2f0ff7d7c`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include <type_traits> @6
- include <vector> @7
- include "Intervals.h" @9
- include "TimeUnits.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/ErrorResult.h" @12
- include "mozilla/dom/TimeRanges.h" @13
- function_definition CreateByteInterval @21-24
- function_definition CreateByteIntervalSet @26-31
- function_definition TEST @33-61
- function_definition CreateTimeInterval @63-71
- function_definition CreateTimeIntervals @73-77
- function_definition TEST @79-113
- function_definition TEST @115-119
- function_definition TEST @121-136
- function_definition TEST @138-153
- function_definition TEST @155-166
- function_definition TEST @168-196
- function_definition Compare @199-209
- function_definition GeneratePermutations @211-242
- function_definition TEST @244-258
- function_definition TEST @260-274
- function_definition TEST @276-288
- function_definition TEST @290-307
- function_definition Duplicate @309-312
- function_definition TEST @314-347
- function_definition TEST @349-359
- function_definition TEST @361-372
- function_definition TEST @374-388
- function_definition TEST @390-413
- function_definition TEST @415-423
- function_definition TEST @425-450
- function_definition TEST @452-477
- function_definition TEST @479-493
- function_definition TEST @495-529
- function_definition TEST @531-537
- function_definition TEST @539-569
- function_definition CheckTimeRanges @571-583
- function_definition TEST @585-602
- function_definition TEST @604-658
- class_specifier Foo @661-689
- function_definition Foo @663-663
- function_definition Foo @665-665
- function_definition operator+ @667-673
- function_definition operator- @674-680
- function_definition operator< @681-681
- function_definition operator== @682-682
- function_definition operator<= @683-683
- function_definition TEST @691-703
- function_definition TEST @705-718
- function_definition TEST @720-819

### dom/media/gtest/TestMP3Demuxer.cpp

Blob: `4755a998db7a267c41252332f8eb0e38a82afb3a`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include <climits> @7
- include <vector> @8
- include "MP3Demuxer.h" @10
- include "MockMediaResource.h" @11
- class_specifier MockMP3MediaResource @13-13
- class_specifier MockMP3StreamMediaResource @14-14
- class_specifier MockMP3MediaResource @24-33
- function_definition MockMP3MediaResource @28-29
- function_definition ~MockMP3MediaResource @32-32
- class_specifier MockMP3StreamMediaResource @36-47
- function_definition MockMP3StreamMediaResource @40-41
- function_definition GetLength @43-43
- function_definition ~MockMP3StreamMediaResource @46-46
- struct_specifier MP3Resource @49-89
- enum_specifier HeaderType @50-50
- struct_specifier Duration @51-61
- function_definition Duration @55-56
- function_definition Tolerance @57-60
- class_specifier MP3DemuxerTest @91-438
- function_definition SetUp @93-435
- function_definition TEST_F @440-453
- function_definition TEST_F @455-472
- function_definition TEST_F @474-535
- function_definition TEST_F @537-589
- function_definition TEST_F @591-630
- function_definition TEST_F @634-651

### dom/media/gtest/TestMP4Demuxer.cpp

Blob: `f644f47c5ccff265833b82bc735a41ad29aa260b`. Grammar: cpp. Status: syntax-clean.

- include "AOMDecoder.h" @5
- include "BufferMediaResource.h" @6
- include "DecoderData.h" @7
- include "H265.h" @8
- include "MP4Demuxer.h" @9
- include "MediaDataDemuxer.h" @10
- include "MockMediaResource.h" @11
- include "VideoUtils.h" @12
- include "gtest/gtest.h" @13
- include "mozilla/MozPromise.h" @14
- include "mozilla/SharedThreadPool.h" @15
- include "mozilla/TaskQueue.h" @16
- include "mozilla/gtest/MozAssertions.h" @17
- include "mp4parse.h" @18
- class_specifier MP4DemuxerBinding @29-157
- function_definition MP4DemuxerBinding @44-51
- function_definition MP4DemuxerBinding @53-58
- function_definition RunTestAndWait @61-66
- function_definition CheckTrackKeyFrame @68-107
- function_definition CheckTrackSamples @109-146
- function_definition DispatchTask @150-154
- function_definition ~MP4DemuxerBinding @156-156
- function_definition TEST @159-178
- function_definition ToCryptoString @180-200
- function_definition TEST @202-346
- function_definition TEST @348-561
- function_definition TEST @563-591
- function_definition TEST @599-643
- function_definition TEST @660-697
- function_definition TEST @699-707
- function_definition TEST @709-717
- function_definition TEST @719-727
- function_definition ReadFileToBuffer @729-749
- function_definition PatchMdhdTimescales @752-777
- function_definition TEST @783-804
- function_definition TEST @811-841
- function_definition MakeTrackInfo @844-851
- function_definition MakeVideoInfo @853-862
- function_definition TEST @864-938
- function_definition TEST @940-992
- function_definition TEST @994-1021
- function_definition TEST @1023-1045
- function_definition TEST @1047-1060
- function_definition MakeSampleInfo @1064-1078
- function_definition TEST @1081-1092
- function_definition TEST @1095-1106
- function_definition TEST @1109-1120
- function_definition TEST @1123-1134
- function_definition TEST @1137-1148
- function_definition TEST @1151-1162
- function_definition TEST @1165-1176

### dom/media/gtest/TestMediaCapabilities.cpp

Blob: `a06a7c60d53c0bc2fbdd7ea2c5c3d4f713d9f21a`. Grammar: cpp. Status: syntax-clean.

- include "MediaCapabilities.h" @5
- include "MediaInfo.h" @6
- include "MockDecoderModule.h" @7
- include "PDMFactory.h" @8
- include "VPXDecoder.h" @9
- include "VideoUtils.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gtest/WaitFor.h" @12
- function_definition TEST @18-44
- function_definition TEST @46-72
- function_definition TEST @74-100

### dom/media/gtest/TestMediaCodecsSupport.cpp

Blob: `8ba277320a449bcd7875fcd77a9234f63ac9fe7e`. Grammar: cpp. Status: syntax-clean.

- include "MediaCodecsSupport.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @11-33
- function_definition TEST @40-74
- function_definition TEST @82-130
- function_definition TEST @136-175
- function_definition TEST @180-219
- function_definition TEST @223-249

### dom/media/gtest/TestMediaDataDecoder.cpp

Blob: `61879d9468d572e45fbc257658be56af07f4fb43`. Grammar: cpp. Status: syntax-clean.

- include <type_traits> @5
- include "H264.h" @7
- include "ImageContainer.h" @8
- include "MP4Demuxer.h" @9
- include "MockMediaResource.h" @10
- include "PDMFactory.h" @11
- include "VideoUtils.h" @12
- include "gfxPlatform.h" @13
- include "gtest/gtest.h" @14
- include "mozilla/ScopeExit.h" @15
- include "mozilla/SharedThreadPool.h" @16
- include "mozilla/UniquePtr.h" @17
- include "mozilla/gtest/ScopedPrefSetter.h" @18
- include "mozilla/gtest/WaitFor.h" @19
- class_specifier PropertyTest @26-55
- function_definition SetUpTestSuite @28-41
- function_definition TearDownTestSuite @43-48
- function_definition CheckEquals @62-90
- function_definition CheckAndroid @98-113
- function_definition DecodeFirstAV1FrameViaFFVPX @116-193
- function_definition GetPlanarData @195-200
- function_definition TEST @202-214
- function_definition TEST @216-227
- function_definition CheckApple @230-239
- function_definition TEST_P @250-259
- function_definition TEST_P @263-265

### dom/media/gtest/TestMediaDataEncoder.cpp

Blob: `9b05f1b331a20e2ddd4ece5f33abe6bff021371c`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @5
- include "AOMDecoder.h" @7
- include "AnnexB.h" @8
- include "BufferReader.h" @9
- include "H264.h" @10
- include "ImageContainer.h" @11
- include "MediaData.h" @12
- include "PEMFactory.h" @13
- include "TimeUnits.h" @14
- include "VPXDecoder.h" @15
- include "VideoUtils.h" @16
- include "gtest/gtest.h" @17
- include "mozilla/AbstractThread.h" @18
- include "mozilla/Preferences.h" @19
- include "mozilla/SpinEventLoopUntil.h" @20
- include "mozilla/gtest/ScopedPrefSetter.h" @21
- include "mozilla/gtest/WaitFor.h" @22
- include "mozilla/media/MediaUtils.h" @23
- class_specifier MediaDataEncoderTest @97-215
- function_definition SetUp @99-103
- function_definition TearDown @105-109
- struct_specifier FrameSource @112-209
- function_definition GetSize @119-119
- function_definition Init @121-138
- function_definition Deinit @140-144
- function_definition GetFrame @146-167
- function_definition DrawChessboard @169-193
- function_definition Draw @195-208
- function_definition CreateVideoEncoder @217-241
- function_definition EnsureInit @243-249
- function_definition WaitForShutdown @251-266
- function_definition Drain @268-281
- struct_specifier EncodeResult @283-286
- function_definition EncodeWithInputStats @287-303
- function_definition Encode @305-310
- function_definition EncodeBatchWithInputStats @312-340
- function_definition GetKeyFrameCount @343-351
- function_definition GetNALUSize @353-356
- function_definition IsValidAVCC @358-385
- function_definition CheckH264EncodeOutput @393-434
- function_definition CreateH264Encoder @436-447
- function_definition TEST_F @449-455
- function_definition TEST_F @457-471
- function_definition H264EncodesTest @473-521
- function_definition TEST_F @523-525
- function_definition TEST_F @527-529
- function_definition TEST_F @531-533
- function_definition TEST_F @535-537
- function_definition TEST_F @539-542
- function_definition TEST_F @544-547
- function_definition TEST_F @549-552
- function_definition TEST_F @554-557
- function_definition TEST_F @570-577
- function_definition TEST_F @582-589
- function_definition H264EncodeBatchTest @591-620
- function_definition TEST_F @622-624
- function_definition TEST_F @626-628
- function_definition TEST_F @630-632
- function_definition TEST_F @634-636
- function_definition TEST_F @638-641
- function_definition TEST_F @643-646
- function_definition TEST_F @648-651
- function_definition TEST_F @653-656
- function_definition H264EncodeAfterDrainTest @659-683
- function_definition TEST_F @685-688
- function_definition TEST_F @690-693
- function_definition TEST_F @695-697
- function_definition TEST_F @699-702
- function_definition H264InterleavedEncodeAndDrainTest @704-733
- function_definition TEST_F @735-738
- function_definition TEST_F @740-743
- function_definition TEST_F @745-748
- function_definition TEST_F @750-753
- function_definition TEST_F @756-768
- function_definition TEST_F @770-790
- function_definition TEST_F @793-823
- function_definition CreateNV12Frame @827-855
- function_definition TEST_F @857-882
- function_definition TEST_F @888-898
- function_definition CreateVP8Encoder @902-912
- function_definition CreateVP9Encoder @914-924
- function_definition TEST_F @926-932
- function_definition TEST_F @934-949
- function_definition TEST_F @951-984
- function_definition TEST_F @986-998
- function_definition TEST_F @1001-1034
- function_definition TEST_F @1036-1067
- function_definition TEST_F @1069-1100
- function_definition TEST_F @1103-1109
- function_definition TEST_F @1111-1126
- function_definition TEST_F @1128-1159
- function_definition TEST_F @1161-1173
- function_definition TEST_F @1176-1209
- function_definition TEST_F @1211-1246
- function_definition TEST_F @1248-1283
- function_definition CreateAudioEncoder @1287-1309
- function_definition TEST_F @1311-1340
- function_definition TEST_F @1342-1414
- function_definition CreateAV1Encoder @1416-1426
- struct_specifier AV1ColorTestData @1428-1436
- function_definition SetFrameColor @1459-1465
- function_definition AV1ColorFormat @1467-1473
- function_definition ExpectAV1Color @1475-1485
- function_definition EncodeAV1ColorFrame @1487-1496
- function_definition TEST_F @1498-1514
- function_definition TEST_F @1516-1532
- function_definition GetAV1FrameTemporalId @1534-1545
- function_definition TEST_F @1547-1578
- function_definition TEST_F @1580-1615
- function_definition TEST_F @1617-1662

### dom/media/gtest/TestMediaEventSource.cpp

Blob: `3efa4b7282c07474fa1764ae5a42f621d1bda174`. Grammar: cpp. Status: contains-errors.

- include <memory> @5
- include "MediaEventSource.h" @7
- include "VideoUtils.h" @8
- include "gmock/gmock-matchers.h" @9
- include "gmock/gmock.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/SharedThreadPool.h" @12
- include "mozilla/TaskQueue.h" @13
- include "mozilla/UniquePtr.h" @14
- function_definition TEST @29-55
- function_definition TEST @57-84
- function_definition TEST @89-117
- function_definition TEST @119-146
- function_definition TEST @152-163
- function_definition TEST @168-201
- struct_specifier Foo @184-187
- function_definition Foo @185-185
- function_definition OnNotify @186-186
- function_definition TEST @206-237
- function_definition TEST @239-274
- struct_specifier Foo @250-255
- function_definition OnNotify1 @251-251
- function_definition OnNotify2 @252-252
- function_definition OnNotify3 @253-253
- function_definition OnNotify4 @254-254
- struct_specifier SomeEvent @276-283
- function_definition SomeEvent @277-277
- function_definition SomeEvent @280-280
- function_definition SomeEvent @281-281
- function_definition TEST @288-320
- struct_specifier Foo @301-303
- function_definition OnNotify @302-302
- function_definition TEST @322-371
- struct_specifier Foo1 @341-343
- function_definition OnNotify @342-342
- struct_specifier Foo2 @346-348
- function_definition OnNotify @347-347
- function_definition TEST @373-404
- struct_specifier Foo @386-388
- function_definition OnNotify @387-387
- function_definition TEST @406-449
- struct_specifier Foo @423-426
- function_definition OnNotify @424-424
- function_definition OnNotify2 @425-425
- function_definition TEST @451-499
- struct_specifier Foo1 @466-468
- function_definition OnNotify @467-467
- struct_specifier Foo2 @473-475
- function_definition OnNotify @474-474
- function_definition TEST @501-534
- struct_specifier Foo @513-515
- function_definition OnNotify @514-514
- function_definition TEST @539-564
- function_definition TEST @566-589
- function_definition TEST @591-611
- struct_specifier RefCounter @613-620
- function_definition RefCounter @615-615
- function_definition ~RefCounter @619-619
- function_definition TEST @626-651
- function_definition TEST @656-681
- struct_specifier DestroyChecker @684-695
- function_definition DestroyChecker @685-687
- function_definition ~DestroyChecker @688-691
- class_specifier ClassForDestroyCheck @697-707
- function_definition ClassForDestroyCheck @700-701
- function_definition RefCountNums @703-703
- function_definition ~ClassForDestroyCheck @706-706
- function_definition TEST @709-739
- function_definition TEST @741-756
- function_definition TEST @758-795

### dom/media/gtest/TestMediaFormatReader.cpp

Blob: `bd40f51e591716fa41f19b56e57f369362d7cfd4`. Grammar: cpp. Status: contains-errors.

- include <initializer_list> @5
- include "ImageContainer.h" @7
- include "MediaFormatReader.h" @8
- include "MockDecoderModule.h" @9
- include "MockMediaDataDemuxer.h" @10
- include "MockMediaDecoderOwner.h" @11
- include "PDMFactory.h" @12
- include "ReaderProxy.h" @13
- include "TimeUnits.h" @14
- include "VideoFrameContainer.h" @15
- include "gtest/gtest.h" @16
- include "mozilla/Atomics.h" @17
- include "mozilla/Preferences.h" @18
- include "mozilla/SpinEventLoopUntil.h" @19
- include "mozilla/gfx/gfxVars.h" @20
- include "mozilla/gtest/MozAssertions.h" @21
- include "mozilla/gtest/WaitFor.h" @22
- include "nsQueryObject.h" @23
- function_definition MakeRawSample @45-53
- function_definition ResolveOneSample @55-59
- class_specifier TestMediaFormatReader @63-265
- function_definition SetUp @65-68
- function_definition SetUpReaderDependencies @70-100
- function_definition TearDown @102-102
- function_definition SetVideoMediaTime @104-113
- function_definition AddAudioTrack @115-126
- function_definition InitReader @128-147
- function_definition FinishShutdown @149-155
- function_definition WaitForReaderOperations @159-176
- function_definition ExpectDecoderWithFailingPrimingDrain @180-203
- function_definition ExpectDemuxReachingInternalSeekPriming @212-236
- function_definition ReachInternalSeekPriming @240-248
- function_definition TEST_F @271-281
- function_definition TEST_F @283-308
- function_definition TEST_F @310-347
- function_definition TEST_F @349-368
- function_definition TEST_F @370-405
- function_definition TEST_F @407-428
- function_definition TEST_F @430-456
- function_definition TEST_F @458-486
- function_definition TEST_F @488-592
- function_definition TEST_F @597-642
- class_specifier RecreateOnNthDecodeDecoder @644-664
- function_definition RecreateOnNthDecodeDecoder @646-650
- function_definition Decode @652-658
- function_definition ~RecreateOnNthDecodeDecoder @661-661
- class_specifier VideoRateTest @666-836
- enum_specifier SampleType @668-668
- function_definition ExpectedRate @673-682
- struct_specifier SampleSpec @684-690
- function_definition SetUp @692-700
- function_definition TearDown @702-702
- function_definition ShutdownReader @704-711
- function_definition AddSample @713-716
- function_definition AddSample @718-723
- function_definition AddSampleAt @725-732
- function_definition AddSampleWithoutTrackInfo @734-736
- function_definition RecreateFirstDecoderOnDecode @738-741
- function_definition InitReader @743-793
- function_definition ReadFrame @795-797
- function_definition ReadToEnd @799-811
- function_definition SetNullDecode @813-816
- function_definition SeekToStart @818-821
- function_definition VideoRate @823-827
- function_definition TEST_F @838-855
- function_definition TEST_F @857-879
- function_definition TEST_F @881-896
- function_definition TEST_F @898-919
- function_definition TEST_F @921-953
- function_definition TEST_F @955-989
- function_definition TEST_F @991-1013
- function_definition TEST_F @1015-1032
- function_definition TEST_F @1034-1058
- function_definition TEST_F @1060-1091
- function_definition TEST_F @1093-1127
- class_specifier TestMFRCryptoSampleSizeCheck @1132-1202
- function_definition TestMFRCryptoSampleSizeCheck @1146-1151
- function_definition SetUp @1153-1170
- function_definition TearDown @1172-1178
- function_definition InitReader @1180-1201
- function_definition MakeCryptoSamplesHolder @1208-1221
- function_definition TEST_F @1227-1244
- function_definition TEST_F @1248-1263
- function_definition TEST_F @1267-1281

### dom/media/gtest/TestMediaInfo.cpp

Blob: `01c840fb7f9e481682ad82fb925f906f2647f25b`. Grammar: cpp. Status: syntax-clean.

- include "MediaInfo.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @10-35

### dom/media/gtest/TestMediaMIMETypes.cpp

Blob: `bdb28ca40bba4758f004e1a5ee4ab44f23e4ddad`. Grammar: cpp. Status: syntax-clean.

- include "MediaMIMETypes.h" @5
- include "gtest/gtest.h" @6
- function_definition TEST @10-27
- struct_specifier tests @12-15
- function_definition TEST @29-39
- function_definition TEST @41-80
- struct_specifier tests @43-50
- function_definition TEST @82-179
- function_definition TEST @181-191
- function_definition TEST @193-318
- struct_specifier tests @196-204

### dom/media/gtest/TestMediaQueue.cpp

Blob: `7176de069f3965064f2b32627d2e88a2bbe348b7`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include "MediaData.h" @7
- include "MediaQueue.h" @8
- include "nsISupportsImpl.h" @9
- function_definition CreateDataRawPtr @14-31
- function_definition CreateData @33-36
- function_definition TEST @42-82
- function_definition TEST @84-116
- function_definition TEST @118-125
- function_definition TEST @127-144
- function_definition TEST @146-158
- function_definition TEST @160-177
- function_definition TEST @179-211
- function_definition TEST @213-268
- function_definition TEST @270-287
- function_definition TEST @289-302

### dom/media/gtest/TestMediaSpan.cpp

Blob: `9dc9f9dda5813950958813db594ace9a3aaa7ed5`. Grammar: cpp. Status: syntax-clean.

- include <gtest/gtest.h> @5
- include <stdint.h> @6
- include "MediaSpan.h" @8
- function_definition makeBuffer @12-18
- function_definition IsRangeAt @20-32
- function_definition IsRange @34-36
- function_definition TEST @38-60
- function_definition TEST @62-86
- function_definition TEST @88-107

### dom/media/gtest/TestMediaUtils.cpp

Blob: `d2e9a706d72bc6e61b6b5e51c22cc739ff14b4b9`. Grammar: cpp. Status: syntax-clean.

- include "MediaUtils.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/AppShutdown.h" @7
- include "mozilla/SyncRunnable.h" @8
- include "mozilla/gtest/MozHelpers.h" @9
- include "gfxPlatformMac.h" @12
- function_definition DoCreateTicketBeforeAppShutdownOnMain @27-78
- function_definition DoCreateTicketAfterAppShutdownOnMain @80-99
- function_definition DoCreateTicketBeforeAppShutdownOffMain @101-161
- function_definition DoCreateTicketAfterAppShutdownOffMain @163-190
- function_definition DoTwoTicketsWithSameNameBothBlockShutdown @192-233
- function_definition TEST @235-239
- function_definition TEST @241-245
- function_definition TEST @247-251
- function_definition TEST @253-257
- function_definition TEST @259-263

### dom/media/gtest/TestMuxer.cpp

Blob: `87644edf44efd06c5cbc5d9fdf15cbb4777612ae`. Grammar: cpp. Status: syntax-clean.

- include "ContainerWriter.h" @5
- include "EncodedFrame.h" @6
- include "Muxer.h" @7
- include "OpusTrackEncoder.h" @8
- include "WebMWriter.h" @9
- include "gmock/gmock.h" @10
- include "gtest/gtest.h" @11
- function_definition CreateOpusMetadata @20-36
- function_definition CreateVP8Metadata @38-46
- function_definition CreateFrame @48-64
- class_specifier MockContainerWriter @66-75
- function_definition TEST @77-113
- function_definition TEST @115-157
- function_definition TEST @159-209

### dom/media/gtest/TestOfflineClockDriver.cpp

Blob: `9446f629d5e95f6427e364aabd19ac6c3370ac2b`. Grammar: cpp. Status: contains-errors.

- include "MockGraphInterface.h" @5
- include "gtest/gtest.h" @6
- include "mozilla/gtest/WaitFor.h" @7

### dom/media/gtest/TestOggWriter.cpp

Blob: `ecdef323f169e30733fe472c40c2a08371912892`. Grammar: cpp. Status: syntax-clean.

- include "OggWriter.h" @5
- include "OpusTrackEncoder.h" @6
- include "gtest/gtest.h" @7
- function_definition TEST @12-61

### dom/media/gtest/TestOpusParser.cpp

Blob: `ffa6806bed27d1d701abe534bc77fa34563f7d04`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include "OpusParser.h" @7
- include "gtest/gtest.h" @8
- function_definition TEST @12-24

### dom/media/gtest/TestPDMFactorySupport.cpp

Blob: `76ca7b18628de6cc532d611a91df1808f8fecf1c`. Grammar: cpp. Status: syntax-clean.

- include "PDMFactorySupport.h" @5
- include "VideoUtils.h" @6
- include "gtest/gtest.h" @7
- include "mozilla/Preferences.h" @8
- include "mozilla/SpinEventLoopUntil.h" @9
- include "mozilla/TaskQueue.h" @10
- include "mozilla/gfx/gfxVars.h" @11
- include "mozilla/gtest/WaitFor.h" @12
- function_definition TEST @18-26
- function_definition TEST @30-44
- function_definition TEST @49-67
- function_definition TEST @72-103
- function_definition TEST @107-117
- function_definition TEST @123-133
- function_definition TEST @143-182
- function_definition TEST @186-203

### dom/media/gtest/TestPacer.cpp

Blob: `8796d6fc5b500724c60c7cd8099ba98bb905b041`. Grammar: cpp. Status: contains-errors.

- include <thread> @5
- include "Pacer.h" @7
- include "VideoUtils.h" @8
- include "gmock/gmock-matchers.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/gtest/WaitFor.h" @11
- class_specifier PacerTest @16-55
- function_definition PacerTest @18-23
- function_definition EnqueueSoon @29-35
- function_definition TearDown @37-40
- function_definition Interval @42-42
- function_definition SetInterval @44-48
- class_specifier PacerTestInt @57-63
- function_definition PacerTestInt @59-60
- function_definition TearDown @62-62
- class_specifier PacerTestIntLongDuplication @65-68
- function_definition PacerTestIntLongDuplication @67-67
- class_specifier PacerTestIntTenMsDuplication @70-74
- function_definition PacerTestIntTenMsDuplication @72-73
- class_specifier PacerTestIntInfDuplication @76-79
- function_definition PacerTestIntInfDuplication @78-78
- function_definition TEST_F @93-102
- function_definition TEST_F @104-113
- function_definition TEST_F @115-138
- function_definition TEST_F @140-159
- function_definition TEST_F @161-188
- function_definition TEST_F @190-217
- function_definition TEST_F @219-273

### dom/media/gtest/TestQuantizableBuffer.cpp

Blob: `87c41ab36133d893ba497f569d38781d9f284cc1`. Grammar: cpp. Status: contains-errors.

- include <limits> @5
- include "ImageContainer.h" @7
- include "MediaData.h" @8
- include "VideoUtils.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/DefineEnum.h" @11
- include "mozilla/UniquePtr.h" @12
- class_specifier QuantizableBufferTest @18-113
- struct_specifier TestBuffer @25-109
- function_definition TestBuffer @26-103
- function_definition TEST_P @124-136
- function_definition TEST_P @138-165
- function_definition TEST_P @167-173

### dom/media/gtest/TestRTCStatsTimestampMaker.cpp

Blob: `f3cb33b5bd70f2bd6e456e0396e2b303217bc6d1`. Grammar: cpp. Status: syntax-clean.

- include <cmath> @5
- include "gtest/gtest.h" @7
- include "jsapi/RTCStatsReport.h" @8
- include "libwebrtcglue/SystemTime.h" @9
- include "mozilla/dom/PerformanceService.h" @10
- function_definition TEST @19-34
- function_definition TEST @36-53
- function_definition TEST @55-67
- function_definition TEST @69-82
- function_definition TEST @84-100
- function_definition TEST @102-116

### dom/media/gtest/TestRemoteImageHolder.cpp

Blob: `8c8046723b295ef1b935824858bc952d3ea2d9bc`. Grammar: cpp. Status: contains-errors.

- include "GPUVideoImage.h" @6
- include "ImageContainer.h" @7
- include "gtest/gtest.h" @8
- include "mozilla/RemoteImageHolder.h" @9
- include "mozilla/gfx/Types.h" @10
- include "mozilla/ipc/Shmem.h" @11
- include "mozilla/layers/BufferTexture.h" @12
- include "mozilla/layers/ImageDataSerializer.h" @13
- include "mozilla/layers/LayersSurfaces.h" @14
- class_specifier TestGPUVideoSurfaceManager @21-58
- struct_specifier ColorMetadata @23-29
- function_definition Readback @33-36
- function_definition TransferToImage @38-49
- function_definition DeallocateSurfaceDescriptor @51-51
- function_definition OnSetCurrent @52-52
- function_definition ~TestGPUVideoSurfaceManager @57-57
- function_definition MakeInvalidDescriptor @60-66
- function_definition MakeValidDescriptor @68-74
- function_definition MakeHDRMetadataDescriptor @76-83
- function_definition MakeColorMetadataDescriptor @85-91
- function_definition MakeOversizedDisplayDescriptor @94-100
- function_definition MakeInvalidChromaDimensionsDescriptor @103-109
- function_definition TEST @111-121
- function_definition TEST @123-133
- function_definition TEST @135-162
- function_definition TEST @164-203
- function_definition TEST @205-230
- function_definition TEST @232-261
- function_definition TEST @263-283
- function_definition TEST @285-321
- function_definition TEST @323-359

### dom/media/gtest/TestRust.cpp

Blob: `5050e80dfa19f0d0317a5cd94191f8346d5239c5`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @1
- include "gtest/gtest.h" @3
- function_definition TEST @7-11

### dom/media/gtest/TestSimpleMap.cpp

Blob: `da06c6a7fb0202f0c46d0f787bf7e1fb93ff7d72`. Grammar: cpp. Status: syntax-clean.

- include "SimpleMap.h" @5
- include "gtest/gtest.h" @6
- include "nsString.h" @7
- function_definition TEST @11-25
- function_definition TEST @27-55
- function_definition TEST @57-65
- function_definition TEST @67-86
- function_definition TEST @88-105
- function_definition TEST @107-121

### dom/media/gtest/TestSpeechModelMapping.cpp

Blob: `fd8b065fbb6c49b31f02b5f8cfe737b5086e28a8`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @5
- include "mozilla/dom/SpeechRecognitionModelMapping.h" @6
- function_definition TEST @10-31
- struct_specifier TestCase @12-16
- function_definition TEST @33-38
- function_definition TEST @40-45

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
