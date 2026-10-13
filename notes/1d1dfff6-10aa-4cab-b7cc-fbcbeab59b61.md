<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["image/imgLoader.h", "image/imgRequest.cpp", "image/imgRequest.h", "image/imgRequestProxy.cpp", "image/imgRequestProxy.h", "image/imgTools.cpp", "image/imgTools.h", "image/remote/RemoteImageProtocolHandler.cpp", "image/remote/RemoteImageProtocolHandler.h", "image/rust/jxl/src/decoder.rs", "image/rust/jxl/src/ffi.rs", "image/rust/jxl/src/lib.rs", "image/rust/jxl/src/runner.rs", "image/test/fuzzing/TestDecoders.cpp", "image/test/gtest/Common.cpp", "image/test/gtest/Common.h", "image/test/gtest/TestADAM7InterpolatingFilter.cpp", "image/test/gtest/TestAnimationFrameBuffer.cpp", "image/test/gtest/TestBlendAnimationFilter.cpp", "image/test/gtest/TestCopyOnWrite.cpp", "image/test/gtest/TestDecodeToSurface.cpp", "image/test/gtest/TestDecoders.cpp", "image/test/gtest/TestDecodersPerf.cpp", "image/test/gtest/TestDeinterlacingFilter.cpp", "image/test/gtest/TestDownscalingFilter.cpp", "image/test/gtest/TestFrameAnimator.cpp", "image/test/gtest/TestHDRPNGEncoder.cpp", "image/test/gtest/TestLoader.cpp", "image/test/gtest/TestMetadata.cpp", "image/test/gtest/TestRemoveFrameRectFilter.cpp", "image/test/gtest/TestSourceBuffer.cpp", "image/test/gtest/TestStreamingLexer.cpp", "image/test/gtest/TestSurfaceCache.cpp", "image/test/gtest/TestSurfacePipeIntegration.cpp", "image/test/gtest/TestSurfaceSink.cpp", "image/test/gtest/TestSwizzleFilter.cpp"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/image native and TypeScript syntax map 98

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### image/imgLoader.h

Blob: `880ca81adbdc2980b1ba7927279ea294b50be736`. Grammar: cpp. Status: contains-errors.

- include "ImageCacheKey.h" @9
- include "imgICache.h" @10
- include "imgILoader.h" @11
- include "imgIRequest.h" @12
- include "imgRequest.h" @13
- include "mozilla/CORSMode.h" @14
- include "mozilla/EnumSet.h" @15
- include "mozilla/Maybe.h" @16
- include "mozilla/Mutex.h" @17
- include "mozilla/UniquePtr.h" @18
- include "mozilla/dom/CacheExpirationTime.h" @19
- include "nsExpirationTracker.h" @20
- include "nsIChannel.h" @21
- include "nsIContentSniffer.h" @22
- include "nsIProgressEventSink.h" @23
- include "nsIThreadRetargetableStreamListener.h" @24
- include "nsRefPtrHashtable.h" @25
- include "nsTHashSet.h" @26
- include "nsWeakReference.h" @27
- include "mozilla/dom/IntegrityPolicyWAICT.h" @29
- include "mozilla/dom/ResourceHasher.h" @30
- class_specifier imgLoader @33-33
- class_specifier imgRequestProxy @34-34
- class_specifier imgINotificationObserver @35-35
- class_specifier nsILoadGroup @36-36
- class_specifier imgCacheExpirationTracker @37-37
- class_specifier imgMemoryReporter @38-38
- class_specifier Document @42-42
- enum_specifier FetchPriority @43-43
- class_specifier imgCacheEntry @47-142
- function_definition imgCacheEntry @54-54
- function_definition GetDataSize @56-56
- function_definition SetDataSize @57-61
- function_definition GetTouchedTime @63-63
- function_definition SetTouchedTime @64-67
- function_definition GetLoadTime @69-69
- function_definition (anonymous) @73-73
- function_definition AccumulateExpiryTime @75-91
- function_definition GetMustValidate @93-93
- function_definition SetMustValidate @94-97
- function_definition GetRequest @99-102
- function_definition Evicted @104-104
- function_definition GetExpirationState @106-106
- function_definition HasNoProxies @108-108
- function_definition ForcePrincipalCheck @110-110
- function_definition HasNotified @112-112
- function_definition SetHasNotified @113-116
- function_definition Loader @118-118
- function_definition SetEvicted @125-125
- class_specifier imgCacheQueue @151-177
- enum_specifier AcceptedMimeTypes @179-182
- class_specifier imgLoader @184-467
- enum_specifier ClearOption @326-330
- function_definition MinimizeCache @333-333
- enum_specifier QueueState @341-341
- function_definition CompareCacheEntries @354-374
- include "nsCOMPtr.h" @473
- include "nsIStreamListener.h" @474
- include "nsIThreadRetargetableStreamListener.h" @475
- class_specifier ProxyListener @477-501
- class_specifier nsProgressNotificationProxy @509-527
- function_definition nsProgressNotificationProxy @513-516
- include "nsCOMArray.h" @533
- class_specifier imgCacheValidator @535-577

### image/imgRequest.cpp

Blob: `c6ea84c7c4f914d9e14ea53dba0c56e62f1f3d15`. Grammar: cpp. Status: contains-errors.

- include "imgRequest.h" @6
- include "DecodePool.h" @8
- include "Image.h" @9
- include "ImageFactory.h" @10
- include "ImageLogging.h" @11
- include "MultipartImage.h" @12
- include "ProgressTracker.h" @13
- include "RasterImage.h" @14
- include "imgIRequest.h" @15
- include "imgLoader.h" @16
- include "imgRequestProxy.h" @17
- include "mozilla/IntegerPrintfMacros.h" @18
- include "mozilla/SizeOfState.h" @19
- include "mozilla/dom/Document.h" @20
- include "nsComponentManagerUtils.h" @21
- include "nsContentUtils.h" @22
- include "nsEscape.h" @23
- include "nsICacheInfoChannel.h" @24
- include "nsIChannel.h" @25
- include "nsIClassOfService.h" @26
- include "nsIHttpChannel.h" @27
- include "nsIInputStream.h" @28
- include "nsIInterfaceRequestorUtils.h" @29
- include "nsIMultiPartChannel.h" @30
- include "nsIProtocolHandler.h" @31
- include "nsIScriptSecurityManager.h" @32
- include "nsISupportsPrimitives.h" @33
- include "nsIThreadRetargetableRequest.h" @34
- include "nsIURL.h" @35
- include "nsMimeTypes.h" @36
- include "nsNetUtil.h" @37
- include "nsProperties.h" @38
- include "prtime.h" @39
- function_definition imgRequest @50-71
- function_definition ~imgRequest @73-81
- function_definition Init @83-147
- function_definition CanReuseWithoutValidation @149-170
- function_definition ClearLoader @172-172
- function_definition GetTriggeringPrincipal @174-177
- function_definition GetProgressTracker @179-192
- function_definition SetCacheEntry @194-194
- function_definition HasCacheEntry @196-196
- function_definition ResetCacheEntry @198-202
- function_definition AddProxy @204-225
- function_definition RemoveProxy @227-278
- function_definition InnerWindowID @280-283
- function_definition SetInnerWindowID @285-288
- function_definition CancelAndAbort @290-302
- class_specifier imgRequestMainThreadCancel @304-323
- function_definition imgRequestMainThreadCancel @306-312
- function_definition Run @314-318
- function_definition Cancel @325-336
- function_definition ContinueCancel @338-349
- class_specifier imgRequestMainThreadEvict @351-367
- function_definition imgRequestMainThreadEvict @353-357
- function_definition Run @359-363
- function_definition EvictFromCache @370-379
- function_definition ContinueEvict @382-386
- function_definition StartDecoding @388-391
- function_definition IsDecodeRequested @393-396
- function_definition GetURI @398-410
- function_definition GetFinalURI @412-424
- function_definition IsChrome @426-426
- function_definition IsData @428-428
- function_definition GetImageErrorCode @430-430
- function_definition RemoveFromCache @432-452
- function_definition HasConsumers @454-457
- function_definition GetImage @459-463
- function_definition GetFileName @465-487
- function_definition Priority @489-496
- function_definition AdjustPriority @498-511
- function_definition AdjustPriorityInternal @513-518
- function_definition BoostPriority @520-556
- function_definition SetIsInCache @558-563
- function_definition UpdateCacheEntrySize @565-574
- function_definition SetCacheValidation @576-609
- function_definition GetMultipart @611-614
- function_definition HadInsecureRedirect @616-619
- function_definition HadCrossOriginRedirects @621-635
- function_definition OnStartRequest @639-738
- function_definition OnStopRequest @740-846
- struct_specifier mimetype_closure @848-850
- function_definition CheckListenerChain @859-862
- function_definition OnDataFinished @864-865
- struct_specifier NewPartResult @869-883
- function_definition NewPartResult @870-874
- function_definition PrepareForNewPart @885-971
- class_specifier FinishPreparingForNewPartRunnable @973-991
- function_definition FinishPreparingForNewPartRunnable @975-981
- function_definition Run @983-986
- function_definition FinishPreparingForNewPart @993-1016
- function_definition ImageAvailable @1018-1018
- function_definition OnDataAvailable @1020-1107
- function_definition SetProperties @1109-1128
- function_definition sniff_mimetype_callback @1130-1144
- function_definition GetInterface @1148-1158
- function_definition AsyncOnChannelRedirect @1161-1190
- function_definition OnRedirectVerifyCallback @1192-1257
- function_definition UpdateShouldReportRenderTimeForLCP @1259-1267

### image/imgRequest.h

Blob: `c20f3ce3f03e9f7a556ee3faa409fb3b14cafd9e`. Grammar: cpp. Status: contains-errors.

- include "ImageCacheKey.h" @9
- include "mozilla/Mutex.h" @10
- include "nsCOMPtr.h" @11
- include "nsError.h" @12
- include "nsIAsyncVerifyRedirectCallback.h" @13
- include "nsIChannelEventSink.h" @14
- include "nsIInterfaceRequestor.h" @15
- include "nsIPrincipal.h" @16
- include "nsIStreamListener.h" @17
- include "nsIThreadRetargetableStreamListener.h" @18
- include "nsProxyRelease.h" @19
- include "nsString.h" @20
- class_specifier imgCacheValidator @22-22
- class_specifier imgLoader @23-23
- class_specifier imgRequestProxy @24-24
- class_specifier imgCacheEntry @25-25
- class_specifier nsIProperties @26-26
- class_specifier nsIRequest @27-27
- class_specifier nsITimedChannel @28-28
- class_specifier nsIURI @29-29
- class_specifier nsIReferrerInfo @30-30
- enum_specifier CORSMode @33-33
- class_specifier Image @35-35
- class_specifier ProgressTracker @36-36
- struct_specifier NewPartResult @40-40
- class_specifier imgRequest @42-310
- function_definition GetCORSMode @111-111
- function_definition GetReferrerInfo @114-114
- function_definition GetPrincipal @129-129
- function_definition (anonymous) @132-132
- function_definition GetMimeType @146-146
- function_definition GetContentLength @148-148
- function_definition GetRequest @163-163
- function_definition GetTimedChannel @165-165
- function_definition GetValidator @171-171
- function_definition SetValidator @172-172
- function_definition LoadId @174-174
- function_definition SetLoadId @175-175
- function_definition Properties @197-197
- function_definition IsDeniedCrossSiteCORSRequest @203-205
- function_definition IsCrossSiteNoCORSRequest @207-207
- function_definition ShouldReportRenderTimeForLCP @209-211

### image/imgRequestProxy.cpp

Blob: `07e3310c4c34fa6113b03ada0136b39c765e90d2`. Grammar: cpp. Status: contains-errors.

- include "imgRequestProxy.h" @6
- include <utility> @8
- include "Image.h" @10
- include "ImageLogging.h" @11
- include "ImageOps.h" @12
- include "ImageTypes.h" @13
- include "imgINotificationObserver.h" @14
- include "imgLoader.h" @15
- include "mozilla/dom/DocGroup.h" @16
- include "mozilla/dom/Document.h" @17
- include "nsCRTGlue.h" @18
- include "nsError.h" @19
- class_specifier ProxyBehaviour @28-37
- function_definition ~ProxyBehaviour @30-30
- class_specifier RequestBehaviour @39-70
- function_definition RequestBehaviour @41-41
- function_definition GetOwner @47-47
- function_definition SetOwner @49-58
- function_definition GetImage @72-78
- function_definition GetProgressTracker @80-88
- function_definition ~imgRequestProxy @121-144
- function_definition Init @146-172
- function_definition ChangeOwner @174-213
- function_definition GetTriggeringPrincipal @215-222
- function_definition MarkValidating @224-227
- function_definition ClearValidating @229-240
- function_definition HasDecodedPixels @242-253
- function_definition DispatchWithTargetIfAvailable @255-260
- function_definition AddToOwner @262-269
- function_definition RemoveFromOwner @271-283
- function_definition AddToLoadGroup @285-297
- function_definition RemoveFromLoadGroup @299-335
- function_definition MoveToBackgroundInLoadGroup @337-367
- function_definition GetName @371-380
- function_definition IsPending @382-383
- function_definition GetStatus @385-388
- function_definition SetCanceledReason @390-392
- function_definition GetCanceledReason @394-396
- function_definition CancelWithReason @398-401
- function_definition SetCancelable @403-406
- function_definition Cancel @408-424
- function_definition DoCancel @426-430
- function_definition CancelAndForgetObserver @432-462
- function_definition StartDecoding @464-482
- function_definition StartDecodingWithResult @484-501
- function_definition RequestDecodeWithResult @503-520
- function_definition GetHasAnimationConsumers @522-526
- function_definition LockImage @528-537
- function_definition UnlockImage @539-550
- function_definition RequestDiscard @552-559
- function_definition IncrementAnimationConsumers @561-570
- function_definition DecrementAnimationConsumers @572-589
- function_definition ClearAnimationConsumers @591-595
- function_definition Suspend @597-598
- function_definition Resume @600-601
- function_definition GetLoadGroup @603-607
- function_definition SetLoadGroup @608-615
- function_definition GetLoadFlags @617-621
- function_definition SetLoadFlags @622-626
- function_definition GetTRRMode @628-631
- function_definition SetTRRMode @633-636
- function_definition GetImage @640-662
- function_definition GetProviderId @664-677
- function_definition GetImageStatus @679-693
- function_definition GetImageErrorCode @695-704
- function_definition GetURI @706-712
- function_definition GetFinalURI @714-720
- function_definition GetNotificationObserver @722-727
- function_definition GetMimeType @729-743
- function_definition GetFileName @745-753
- function_definition NewClonedProxy @755-757
- function_definition Clone @759-767
- function_definition SyncClone @769-774
- function_definition Clone @776-781
- function_definition PerformClone @783-861
- function_definition GetImagePrincipal @863-872
- function_definition GetHadCrossOriginRedirects @874-879
- function_definition GetMultipart @881-889
- function_definition GetCORSMode @891-899
- function_definition GetReferrerInfo @901-910
- function_definition BoostPriority @912-917
- function_definition GetPriority @921-926
- function_definition SetPriority @928-933
- function_definition AdjustPriority @935-943
- function_definition NotificationTypeToString @945-969
- function_definition Notify @971-987
- function_definition OnLoadComplete @989-1042
- function_definition NullOutListener @1044-1058
- function_definition GetStaticRequest @1060-1074
- function_definition GetStaticRequest @1076-1103
- function_definition NotifyListener @1105-1121
- function_definition SyncNotifyListener @1123-1131
- function_definition SetHasImage @1133-1152
- function_definition GetProgressTracker @1154-1156
- function_definition GetImage @1158-1160
- function_definition HasImage @1162-1168
- function_definition HasImage @1170-1170
- function_definition GetOwner @1172-1172
- function_definition GetValidator @1174-1180
- function_definition TimedChannel @1182-1187
- class_specifier StaticBehaviour @1191-1217
- function_definition StaticBehaviour @1193-1193
- function_definition GetImage @1195-1198
- function_definition HasImage @1200-1200
- function_definition GetProgressTracker @1202-1204
- function_definition GetOwner @1206-1206
- function_definition SetOwner @1208-1211
- function_definition imgRequestProxyStatic @1219-1227
- function_definition GetImagePrincipal @1229-1236
- function_definition GetTriggeringPrincipal @1238-1242
- function_definition GetHadCrossOriginRedirects @1244-1249
- function_definition NewClonedProxy @1251-1261

### image/imgRequestProxy.h

Blob: `d1f10d6b40c32fd4c6cb3eb771307f8e57664361`. Grammar: cpp. Status: contains-errors.

- include "IProgressObserver.h" @9
- include "imgIRequest.h" @10
- include "mozilla/PreloaderBase.h" @11
- include "mozilla/TimeStamp.h" @12
- include "mozilla/UniquePtr.h" @13
- include "mozilla/gfx/Rect.h" @14
- include "nsCOMPtr.h" @15
- include "nsIPrincipal.h" @16
- include "nsISupportsPriority.h" @17
- include "nsITimedChannel.h" @18
- include "nsThreadUtils.h" @19
- class_specifier imgINotificationObserver @29-29
- class_specifier imgRequest @30-30
- class_specifier imgStatusNotifyRunnable @31-31
- class_specifier ProxyBehaviour @32-32
- class_specifier Image @36-36
- class_specifier ProgressTracker @37-37
- function_definition HasObserver @78-78
- function_definition NotificationsDeferred @101-103
- function_definition MarkPendingNotify @104-104
- function_definition ClearPendingNotify @105-105
- function_definition IsValidating @106-106
- struct_specifier LCPTimings @129-145
- function_definition AreSet @130-130
- function_definition Reset @132-135
- function_definition Set @140-144
- function_definition (anonymous) @147-147
- function_definition (anonymous) @149-149
- class_specifier imgCancelRunnable @155-155
- class_specifier imgCancelRunnable @158-171
- function_definition imgCancelRunnable @160-161
- function_definition Run @163-166
- function_definition ToSupports @247-249
- class_specifier imgRequestProxyStatic @253-273

### image/imgTools.cpp

Blob: `19b591ecd314f05107dfc81afc65d2b238093ccd`. Grammar: cpp. Status: contains-errors.

- include "imgTools.h" @6
- include "DecodePool.h" @8
- include "IProgressObserver.h" @9
- include "Image.h" @10
- include "ImageFactory.h" @11
- include "Orientation.h" @12
- include "ScriptedNotificationObserver.h" @13
- include "gfxPlatform.h" @14
- include "gfxUtils.h" @15
- include "imgICache.h" @16
- include "imgIContainer.h" @17
- include "imgIEncoder.h" @18
- include "imgIScriptedNotificationObserver.h" @19
- include "imgLoader.h" @20
- include "js/ArrayBuffer.h" @21
- include "js/RootingAPI.h" @22
- include "js/Value.h" @23
- include "mozilla/RefPtr.h" @24
- include "mozilla/dom/Document.h" @25
- include "mozilla/gfx/2D.h" @26
- include "mozilla/gfx/Logging.h" @27
- include "nsCOMPtr.h" @28
- include "nsComponentManagerUtils.h" @29
- include "nsContentUtils.h" @30
- include "nsError.h" @31
- include "nsIStreamListener.h" @32
- include "nsNetUtil.h" @33
- include "nsProxyRelease.h" @34
- include "nsStreamUtils.h" @35
- include "nsStringStream.h" @36
- function_definition sniff_mimetype_callback @45-58
- function_definition OnDataAvailable @60-107
- class_specifier ImageDecoderListener @60-73
- function_definition OnStartRequest @109-110
- function_definition OnStopRequest @112-124
- function_definition Notify @126-131
- function_definition OnLoadComplete @133-140
- function_definition SetHasImage @143-143
- function_definition NotificationsDeferred @144-144
- function_definition MarkPendingNotify @145-145
- function_definition ClearPendingNotify @146-146
- function_definition Run @162-244
- class_specifier ImageDecoderHelper @162-180
- function_definition OnInputStreamReady @246-250
- function_definition OperationCompleted @252-258
- function_definition imgTools @285-285
- function_definition ~imgTools @287-287
- function_definition DecodeImageFromArrayBuffer @289-318
- function_definition DecodeImageFromBuffer @320-357
- function_definition DecodeImageFromChannelAsync @359-372
- function_definition DecodeImageAsync @374-418
- function_definition EncodeImageData @426-454
- function_definition EncodeImageData @456-466
- function_definition EncodeImage @468-492
- function_definition EncodeScaledImage @494-567
- function_definition EncodeCroppedImage @569-632
- function_definition CreateScriptedObserver @634-639
- function_definition GetImgLoaderForDocument @641-645
- function_definition GetImgCacheForDocument @647-653

### image/imgTools.h

Blob: `fdb4bc25840e7e88e68a171824fa3c067f4e08e9`. Grammar: cpp. Status: contains-errors.

- include "imgITools.h" @9
- class_specifier imgTools @21-30

### image/remote/RemoteImageProtocolHandler.cpp

Blob: `7d7e9a8475a5b88b450f67276addcb9394adc004`. Grammar: cpp. Status: syntax-clean.

- include "RemoteImageProtocolHandler.h" @5
- include "ImageRegion.h" @7
- include "gfxContext.h" @8
- include "gfxUtils.h" @9
- include "imgITools.h" @10
- include "mozilla/SVGImageContext.h" @11
- include "mozilla/dom/ContentParent.h" @12
- include "mozilla/dom/ContentProcessManager.h" @13
- include "mozilla/dom/ipc/IdType.h" @14
- include "mozilla/gfx/2D.h" @15
- include "nsContentUtils.h" @16
- include "nsIPipe.h" @17
- include "nsIURI.h" @18
- include "nsMimeTypes.h" @19
- include "nsNetUtil.h" @20
- include "nsStreamUtils.h" @21
- include "nsURLHelper.h" @22
- function_definition GetScheme @36-39
- function_definition AllowPort @41-45
- function_definition GetLaunchingContentParentForDecode @47-64
- function_definition EncodeImage @66-91
- function_definition AsyncReEncodeImage @93-159
- function_definition ParseURI @162-228
- function_definition NewChannel @230-265
- function_definition GetImageSurface @268-346

### image/remote/RemoteImageProtocolHandler.h

Blob: `3d09f1512a6eccc47d5bb96e231a9f8b5fdbeb50`. Grammar: cpp. Status: contains-errors.

- include "mozilla/AlreadyAddRefed.h" @8
- include "mozilla/ClearOnShutdown.h" @9
- include "mozilla/MozPromise.h" @10
- include "mozilla/StaticPtr.h" @11
- include "mozilla/dom/ContentParent.h" @12
- include "nsIProtocolHandler.h" @13
- include "nsThreadUtils.h" @14
- include "nsWeakReference.h" @15
- class_specifier RemoteImageProtocolHandler @19-42
- function_definition GetSingleton @25-32
- function_definition ~RemoteImageProtocolHandler @39-39

### image/rust/jxl/src/decoder.rs

Blob: `b485b4479106e663bca86f927594a42c5232b526`. Grammar: rust. Status: syntax-clean.

- struct_item JxlApiDecoder @14-24
- struct_item BasicInfo @26-33
- enum_item Error @36-39
- function_item from @42-44
- function_item is_gray_profile @47-62
- enum_item BufMode @64-68
- function_item new @71-87
- function_item new_scanner @89-107
- function_item scanned_frames @109-111
- function_item bytes_per_pixel @113-122
- function_item is_gray @124-129
- function_item has_black_channel @131-134
- function_item get_output_icc_profile @136-145
- function_item get_output_cicp @153-183
- function_item flush_pixels @189-228
- function_item get_basic_info @230-252
- function_item set_pixel_format @254-324
- function_item process_data @329-427

### image/rust/jxl/src/ffi.rs

Blob: `d7895c827bd44af1f258c19d734575c0a6605e66`. Grammar: rust. Status: syntax-clean.

- enum_item JxlDecoderStatus @10-14
- struct_item JxlBasicInfo @18-26
- struct_item JxlFrameInfo @30-33
- function_item jxl_decoder_new @39-41
- function_item jxl_decoder_destroy @47-53
- function_item jxl_decoder_process_data @66-120
- function_item jxl_decoder_has_black_channel @125-130
- function_item jxl_decoder_get_basic_info @135-154
- function_item jxl_decoder_get_frame_info @159-172
- function_item jxl_decoder_is_frame_ready @177-184
- function_item jxl_decoder_is_gray @189-194
- function_item jxl_decoder_use_f16 @199-206
- function_item jxl_decoder_get_icc_profile @216-235
- function_item jxl_decoder_get_cicp @250-278
- function_item jxl_decoder_has_more_frames @283-290
- function_item jxl_scanner_new @293-295
- function_item jxl_decoder_get_scanned_frame_count @300-305
- function_item jxl_decoder_get_scanned_frame_info @311-328
- function_item jxl_decoder_flush_pixels @339-366

### image/rust/jxl/src/lib.rs

Blob: `3e2ed12d640e271a1ea348ab189f733a4dc43bde`. Grammar: rust. Status: syntax-clean.

- mod_item decoder @8-8
- mod_item ffi @9-9
- mod_item runner @10-10

### image/rust/jxl/src/runner.rs

Blob: `0833672ce6b89aa0ebaad6b619460938183cb14f`. Grammar: rust. Status: syntax-clean.

- function_signature_item JxlGetDecodePool @64-64
- function_item participant_count @75-82
- function_item pool_thread_limit @86-88
- function_item acquire_pool @90-93
- struct_item State @97-106
- struct_item Shared @108-119
- function_item claim @132-140
- function_item fail @144-149
- function_item take_err @153-155
- function_item drain @159-171
- function_item increase_count @173-175
- function_item release_one @177-187
- struct_item Helper @192-192
- function_item drop @195-197
- struct_item WaitForHelpers @205-205
- function_item drop @208-213
- function_item run_in_parallel @218-282
- struct_item PoolRunner @285-288
- function_item new @293-298
- function_item run @302-317
- function_item num_threads @319-321
- function_item as_dyn @328-330

### image/test/fuzzing/TestDecoders.cpp

Blob: `bdd24f3f8fb0afbc01d63f73eda6b602ace33e0b`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "FuzzingInterfaceStream.h" @6
- include "ImageOps.h" @7
- include "gtest/gtest.h" @8
- include "imgIContainer.h" @9
- include "imgITools.h" @10
- include "mozilla/Preferences.h" @11
- include "mozilla/RefPtr.h" @12
- include "mozilla/gfx/2D.h" @13
- include "nsCOMPtr.h" @14
- include "nsComponentManagerUtils.h" @15
- include "nsIInputStream.h" @16
- include "nsIRunnable.h" @17
- include "nsIThread.h" @18
- include "nsString.h" @19
- include "nsThreadUtils.h" @20
- class_specifier DecodeToSurfaceRunnableFuzzing @36-69
- function_definition DecodeToSurfaceRunnableFuzzing @38-44
- function_definition Run @46-49
- function_definition Go @51-63
- function_definition RunDecodeToSurfaceFuzzing @71-101
- function_definition RunDecodeToSurfaceFuzzingJPEG @103-105
- function_definition RunDecodeToSurfaceFuzzingGIF @107-109
- function_definition RunDecodeToSurfaceFuzzingICO @111-113
- function_definition RunDecodeToSurfaceFuzzingBMP @115-117
- function_definition RunDecodeToSurfaceFuzzingPNG @119-121
- function_definition RunDecodeToSurfaceFuzzingWebP @123-125
- function_definition RunDecodeToSurfaceFuzzingAVIF @127-129
- function_definition RunDecodeToSurfaceFuzzingJXL @132-134
- function_definition FuzzingInitImage @137-151

### image/test/gtest/Common.cpp

Blob: `fef8df498bc0b40db14a515b76c94d7536aabd92`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include <cstdlib> @7
- include "ImageFactory.h" @9
- include "gfxPlatform.h" @10
- include "imgITools.h" @11
- include "mozilla/Preferences.h" @12
- include "mozilla/RefPtr.h" @13
- include "nsComponentManagerUtils.h" @14
- include "nsDirectoryServiceDefs.h" @15
- include "nsIFile.h" @16
- include "nsIInputStream.h" @17
- include "nsIProperties.h" @18
- include "nsNetUtil.h" @19
- include "nsStreamUtils.h" @20
- include "nsString.h" @21
- function_definition AutoInitializeImageLib @32-61
- function_definition SetUp @63-78
- function_definition TearDown @80-80
- function_definition SpinPendingEvents @118-128
- function_definition LoadFile @130-161
- function_definition IsSolidColor @163-168
- function_definition RowsAreSolidColor @170-176
- function_definition RectIsSolidColor @178-227
- function_definition RowHasPixels @229-261
- function_definition CreateTrivialDecoder @267-274
- function_definition AssertCorrectPipelineFinalState @276-284
- function_definition CheckGeneratedImage @286-292
- function_definition CheckGeneratedSurface @294-338
- function_definition CheckWritePixels @340-349
- function_definition CheckTransformedWritePixels @351-398
- function_definition GreenPNGTestCase @404-406
- function_definition GreenGIFTestCase @408-410
- function_definition GreenJPGTestCase @412-415
- function_definition GreenBMPTestCase @417-419
- function_definition GreenICOTestCase @421-426
- function_definition GreenIconTestCase @428-431
- function_definition GreenWebPTestCase @433-435
- function_definition GreenAVIFTestCase @437-439
- function_definition NonzeroReservedAVIFTestCase @441-446
- function_definition MultipleColrAVIFTestCase @448-453
- function_definition Transparent10bit420AVIFTestCase @455-461
- function_definition Transparent10bit422AVIFTestCase @463-469
- function_definition Transparent10bit444AVIFTestCase @471-477
- function_definition Transparent12bit420AVIFTestCase @479-485
- function_definition Transparent12bit422AVIFTestCase @487-493
- function_definition Transparent12bit444AVIFTestCase @495-501
- function_definition Transparent8bit420AVIFTestCase @503-510
- function_definition Transparent8bit422AVIFTestCase @512-519
- function_definition Transparent8bit444AVIFTestCase @521-528
- function_definition Gray8bitLimitedRangeBT601AVIFTestCase @530-535
- function_definition Gray8bitLimitedRangeBT709AVIFTestCase @537-542
- function_definition Gray8bitLimitedRangeBT2020AVIFTestCase @544-549
- function_definition Gray8bitFullRangeBT601AVIFTestCase @551-556
- function_definition Gray8bitFullRangeBT709AVIFTestCase @558-563
- function_definition Gray8bitFullRangeBT2020AVIFTestCase @565-570
- function_definition Gray10bitLimitedRangeBT601AVIFTestCase @572-578
- function_definition Gray10bitLimitedRangeBT709AVIFTestCase @580-586
- function_definition Gray10bitLimitedRangeBT2020AVIFTestCase @588-594
- function_definition Gray10bitFullRangeBT601AVIFTestCase @596-601
- function_definition Gray10bitFullRangeBT709AVIFTestCase @603-608
- function_definition Gray10bitFullRangeBT2020AVIFTestCase @610-615
- function_definition Gray12bitLimitedRangeBT601AVIFTestCase @617-623
- function_definition Gray12bitLimitedRangeBT709AVIFTestCase @625-631
- function_definition Gray12bitLimitedRangeBT2020AVIFTestCase @633-639
- function_definition Gray12bitFullRangeBT601AVIFTestCase @641-646
- function_definition Gray12bitFullRangeBT709AVIFTestCase @648-653
- function_definition Gray12bitFullRangeBT2020AVIFTestCase @655-660
- function_definition Gray8bitLimitedRangeGrayscaleAVIFTestCase @662-667
- function_definition Gray8bitFullRangeGrayscaleAVIFTestCase @669-674
- function_definition Gray10bitLimitedRangeGrayscaleAVIFTestCase @676-682
- function_definition Gray10bitFullRangeGrayscaleAVIFTestCase @684-689
- function_definition Gray12bitLimitedRangeGrayscaleAVIFTestCase @691-697
- function_definition Gray12bitFullRangeGrayscaleAVIFTestCase @699-704
- function_definition StackCheckAVIFTestCase @706-709
- function_definition MultiLayerAVIFTestCase @713-716
- function_definition LargeWebPTestCase @718-721
- function_definition LargeAVIFTestCase @723-726
- function_definition GreenWebPIccSrgbTestCase @728-730
- function_definition GreenFirstFrameAnimatedGIFTestCase @732-735
- function_definition GreenFirstFrameAnimatedPNGTestCase @737-741
- function_definition GreenFirstFrameAnimatedWebPTestCase @743-747
- function_definition GreenFirstFrameAnimatedAVIFTestCase @749-753
- function_definition GreenFirstFrameAnimatedJXLTestCase @756-760
- function_definition LongAnimatedJXLTestCase @762-766
- function_definition BlendAnimatedGIFTestCase @769-772
- function_definition BlendAnimatedPNGTestCase @774-778
- function_definition BlendAnimatedWebPTestCase @780-784
- function_definition BlendAnimatedAVIFTestCase @786-790
- function_definition BlendAnimatedJXLTestCase @793-797
- function_definition CorruptTestCase @800-803
- function_definition CorruptBMPWithTruncatedHeader @805-811
- function_definition CorruptICOWithBadBMPWidthTestCase @813-818
- function_definition CorruptICOWithBadBMPHeightTestCase @820-825
- function_definition CorruptICOWithBadBppTestCase @827-833
- function_definition CorruptAVIFTestCase @835-838
- function_definition TransparentAVIFTestCase @840-845
- function_definition TransparentPNGTestCase @847-852
- function_definition TransparentGIFTestCase @854-859
- function_definition TransparentWebPTestCase @861-866
- function_definition TransparentNoAlphaHeaderWebPTestCase @868-873
- function_definition FirstFramePaddingGIFTestCase @875-878
- function_definition TransparentIfWithinICOBMPTestCase @880-886
- function_definition RLE4BMPTestCase @888-891
- function_definition RLE8BMPTestCase @893-896
- function_definition NoFrameDelayGIFTestCase @898-904
- function_definition ExtraImageSubBlocksAnimatedGIFTestCase @906-912
- function_definition DownscaledPNGTestCase @914-921
- function_definition DownscaledGIFTestCase @923-926
- function_definition DownscaledJPGTestCase @928-931
- function_definition DownscaledBMPTestCase @933-936
- function_definition DownscaledICOTestCase @938-941
- function_definition DownscaledIconTestCase @943-946
- function_definition DownscaledWebPTestCase @948-951
- function_definition DownscaledAVIFTestCase @953-956
- function_definition DownscaledTransparentICOWithANDMaskTestCase @958-965
- function_definition TruncatedSmallGIFTestCase @967-970
- function_definition LargeICOWithBMPTestCase @972-975
- function_definition LargeICOWithPNGTestCase @977-980
- function_definition GreenMultipleSizesICOTestCase @982-985
- function_definition PerfGrayJPGTestCase @987-989
- function_definition PerfCmykJPGTestCase @991-993
- function_definition PerfYCbCrJPGTestCase @995-997
- function_definition PerfRgbPNGTestCase @999-1001
- function_definition PerfRgbAlphaPNGTestCase @1003-1006
- function_definition PerfGrayPNGTestCase @1008-1010
- function_definition PerfGrayAlphaPNGTestCase @1012-1015
- function_definition PerfRgbLosslessWebPTestCase @1017-1020
- function_definition PerfRgbAlphaLosslessWebPTestCase @1022-1025
- function_definition PerfRgbLossyWebPTestCase @1027-1030
- function_definition PerfRgbAlphaLossyWebPTestCase @1032-1035
- function_definition PerfRgbGIFTestCase @1037-1039
- function_definition GreenJXLTestCase @1042-1044
- function_definition ProgressiveJXLTestCase @1046-1048
- function_definition DownscaledJXLTestCase @1050-1053
- function_definition LargeJXLTestCase @1055-1058
- function_definition LargeJXLReferenceWebPTestCase @1065-1068
- function_definition TransparentJXLTestCase @1070-1075
- function_definition CorruptJXLTestCase @1077-1080
- function_definition PerfRgbLosslessJXLTestCase @1082-1085
- function_definition PerfRgbAlphaLosslessJXLTestCase @1087-1090
- function_definition PerfRgbLossyJXLTestCase @1092-1094
- function_definition PerfRgbAlphaLossyJXLTestCase @1096-1099
- function_definition ProgressiveAlphaMultiGroupJXLTestCase @1105-1109
- function_definition ExifResolutionTestCase @1112-1114
- function_definition ExifOrientationDownscaleJPGTestCase @1116-1122
- function_definition TestCaseToDecodedImage @1124-1154

### image/test/gtest/Common.h

Blob: `3a74e6974cc52a2e1867e2d1a3638ac5b3a363b9`. Grammar: cpp. Status: contains-errors.

- include <vector> @8
- include "Decoder.h" @10
- include "SurfaceFlags.h" @11
- include "SurfacePipe.h" @12
- include "SurfacePipeFactory.h" @13
- include "gfxColor.h" @14
- include "gfxPlatform.h" @15
- include "gtest/gtest.h" @16
- include "mozilla/Attributes.h" @17
- include "mozilla/Maybe.h" @18
- include "mozilla/UniquePtr.h" @19
- include "mozilla/gfx/2D.h" @20
- include "mozilla/gtest/MozAssertions.h" @21
- include "nsCOMPtr.h" @22
- class_specifier nsIInputStream @24-24
- struct_specifier BGRAColor @33-100
- function_definition BGRAColor @34-34
- function_definition BGRAColor @36-43
- function_definition Green @45-45
- function_definition Red @46-46
- function_definition Blue @47-47
- function_definition Transparent @48-48
- function_definition FromPixel @50-57
- function_definition DeviceColor @59-70
- function_definition sRGBColor @72-76
- function_definition Premultiply @78-85
- function_definition AsPixel @87-92
- enum_specifier TestCaseFlags @102-110
- struct_specifier ImageTestCase @112-180
- function_definition ImageTestCase @113-123
- function_definition ImageTestCase @125-134
- function_definition WithSurfaceFlags @136-140
- function_definition WithFlags @142-146
- function_definition ChooseColor @148-158
- function_definition Color @160-160
- function_definition Fuzz @162-170
- class_specifier AutoInitializeImageLib @193-196
- class_specifier ImageBenchmarkBase @202-212
- function_definition ImageBenchmarkBase @204-204
- class_specifier ExpectNoResume @260-268
- function_definition Resume @264-264
- function_definition ~ExpectNoResume @267-267
- class_specifier CountResumes @272-285
- function_definition CountResumes @276-276
- function_definition Resume @278-278
- function_definition Count @279-279
- function_definition ~CountResumes @282-282
- function_definition WithFilterPipeline @312-326
- function_definition WithFilterPipeline @329-332
- function_definition AssertConfiguringPipelineFails @343-355
- function_definition DecoderTestHelper @455-467
- class_specifier MOZ_STACK_CLASS @455-455
- function_definition PostIsAnimated @459-461
- function_definition PostFrameStop @463-463

### image/test/gtest/TestADAM7InterpolatingFilter.cpp

Blob: `62b3f10062bd8214c06990b08451fe0161797c60`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include <vector> @6
- include "Common.h" @8
- include "Decoder.h" @9
- include "DecoderFactory.h" @10
- include "SourceBuffer.h" @11
- include "SurfaceFilters.h" @12
- include "SurfacePipe.h" @13
- include "gtest/gtest.h" @14
- include "mozilla/Maybe.h" @15
- include "mozilla/gfx/2D.h" @16
- function_definition WithADAM7InterpolatingFilter @26-33
- function_definition AssertConfiguringADAM7InterpolatingFilterFails @35-42
- function_definition InterpolateByte @44-46
- function_definition InterpolateColors @48-54
- enum_specifier ShouldInterpolate @56-56
- function_definition HorizontallyInterpolatedPixel @58-93
- function_definition (anonymous) @95-120
- function_definition ImportantRowStride @122-129
- function_definition FinalPixelStride @131-138
- function_definition IsImportantRow @140-142
- function_definition ADAM7HorizontallyInterpolatedRow @177-204
- function_definition WriteUninterpolatedPixels @206-227
- function_definition CheckHorizontallyInterpolatedImage @229-251
- function_definition CheckHorizontalInterpolation @253-282
- function_definition ADAM7RowColor @284-295
- function_definition WriteRowColorPixels @297-315
- function_definition CheckVerticallyInterpolatedImage @317-366
- function_definition CheckVerticalInterpolation @368-391
- function_definition CheckInterpolation @393-397
- function_definition CheckADAM7InterpolatingWritePixels @399-428
- function_definition TEST @430-433
- function_definition TEST @435-438
- function_definition TEST @440-443
- function_definition TEST @445-448
- function_definition TEST @450-453
- function_definition TEST @455-458
- function_definition TEST @460-463
- function_definition TEST @465-468
- function_definition TEST @470-473
- function_definition TEST @475-478
- function_definition TEST @480-483
- function_definition TEST @485-502
- function_definition TEST @504-519
- function_definition TEST @521-536
- function_definition TEST @538-547
- function_definition TEST @549-558
- function_definition TEST @560-569
- function_definition TEST @571-577
- function_definition TEST @579-585
- function_definition TEST @587-593
- function_definition TEST @595-599
- function_definition TEST @601-604
- function_definition TEST @606-610
- function_definition TEST @612-616

### image/test/gtest/TestAnimationFrameBuffer.cpp

Blob: `4c7efb7505604c6eaa9d7567aaccf24b1618160b`. Grammar: cpp. Status: syntax-clean.

- include <utility> @5
- include "AnimationFrameBuffer.h" @7
- include "Common.h" @8
- include "gtest/gtest.h" @9
- function_definition CreateEmptyFrame @14-32
- function_definition ReinitForRecycle @34-43
- function_definition PrepareForDiscardingQueue @45-64
- function_definition VerifyDiscardingQueueContents @66-72
- function_definition VerifyInsertInternal @74-91
- function_definition VerifyAdvance @93-116
- function_definition VerifyInsertAndAdvance @118-133
- function_definition VerifyMarkComplete @135-152
- function_definition VerifyInsert @154-162
- function_definition VerifyReset @164-184
- class_specifier ImageAnimationFrameBuffer @186-192
- function_definition ImageAnimationFrameBuffer @188-188
- function_definition TEST_F @194-207
- function_definition TEST_F @209-218
- function_definition TEST_F @220-229
- function_definition TEST_F @231-241
- function_definition TEST_F @243-296
- function_definition TEST_F @298-373
- function_definition TEST_F @375-406
- function_definition TEST_F @408-438
- function_definition TestDiscardingQueueLoop @440-534
- function_definition TEST_F @536-545
- function_definition TEST_F @547-581
- function_definition TestDiscardingQueueReset @583-600
- function_definition TEST_F @602-611
- function_definition TEST_F @613-636
- function_definition TEST_F @638-671
- function_definition TEST_F @673-709
- function_definition TEST_F @711-720
- function_definition TEST_F @722-784
- function_definition TEST_F @786-891

### image/test/gtest/TestBlendAnimationFilter.cpp

Blob: `9d80714dd6776ad72f362e9b6e53996dc7c34daa`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfaceFilters.h" @9
- include "SurfacePipe.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gfx/2D.h" @12
- include "skia/src/core/SkColorPriv.h" @13
- function_definition CreateTrivialBlendingDecoder @19-26
- function_definition WithBlendAnimationFilter @29-55
- function_definition AssertConfiguringBlendAnimationFilterFails @57-68
- function_definition TEST @70-75
- function_definition TEST @77-91
- function_definition TEST @93-109
- function_definition TestWithBlendAnimationFilterClear @111-164
- function_definition TEST @166-169
- function_definition TEST @171-174
- function_definition TEST @176-211
- function_definition TEST @213-254
- function_definition TEST @256-310
- function_definition TEST @312-362
- function_definition TEST @364-428
- function_definition TEST @430-451

### image/test/gtest/TestCopyOnWrite.cpp

Blob: `932739842dde439d4c7497632312672fa9b10e64`. Grammar: cpp. Status: contains-errors.

- include "CopyOnWrite.h" @5
- include "gtest/gtest.h" @6
- struct_specifier ValueStats @11-17
- struct_specifier Value @19-41
- function_definition Value @22-23
- function_definition Value @25-28
- function_definition Go @30-30
- function_definition Go @31-31
- function_definition Serial @33-33
- function_definition ~Value @36-36
- function_definition TEST @43-75
- function_definition TEST @77-123
- function_definition TEST @125-158
- function_definition TEST @160-236

### image/test/gtest/TestDecodeToSurface.cpp

Blob: `4373e8a3f62eeeeb20cb9b2fdeeb116596c675c3`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "ImageOps.h" @6
- include "gtest/gtest.h" @7
- include "imgIContainer.h" @8
- include "mozilla/RefPtr.h" @9
- include "mozilla/gfx/2D.h" @10
- include "nsCOMPtr.h" @11
- include "nsComponentManagerUtils.h" @12
- include "nsIInputStream.h" @13
- include "nsIRunnable.h" @14
- include "nsIThread.h" @15
- include "nsString.h" @16
- include "nsThreadUtils.h" @17
- class_specifier DecodeToSurfaceRunnable @23-77
- function_definition DecodeToSurfaceRunnable @25-33
- function_definition Run @35-38
- function_definition Go @40-70
- function_definition RunDecodeToSurface @79-104
- class_specifier ImageDecodeToSurface @106-109
- function_definition TEST_F @111-111
- function_definition TEST_F @112-112
- function_definition TEST_F @113-113
- function_definition TEST_F @114-114
- function_definition TEST_F @115-115
- function_definition TEST_F @116-116
- function_definition TEST_F @117-117
- function_definition TEST_F @119-119
- function_definition TEST_F @122-124
- function_definition TEST_F @126-128
- function_definition TEST_F @130-132
- function_definition TEST_F @134-136
- function_definition TEST_F @139-141
- function_definition TEST_F @144-154
- function_definition TEST_F @156-189

### image/test/gtest/TestDecoders.cpp

Blob: `06b54f2f101b72409e548bfbe043e372e0d55370`. Grammar: cpp. Status: contains-errors.

- include <algorithm> @5
- include "AnimationSurfaceProvider.h" @7
- include "Common.h" @8
- include "DecodePool.h" @9
- include "Decoder.h" @10
- include "DecoderFactory.h" @11
- include "decoders/nsBMPDecoder.h" @12
- include "gtest/gtest.h" @13
- include "mozilla/Monitor.h" @14
- include "decoders/nsJXLDecoder.h" @16
- include "IDecodingTask.h" @18
- include "ImageFactory.h" @19
- include "ImageOps.h" @20
- include "ProgressTracker.h" @21
- include "SourceBuffer.h" @22
- include "imgIContainer.h" @23
- include "mozilla/Preferences.h" @24
- include "mozilla/RefPtr.h" @25
- include "mozilla/ScopeExit.h" @26
- include "mozilla/gfx/2D.h" @27
- include "nsCOMPtr.h" @28
- include "nsComponentManagerUtils.h" @29
- include "nsIInputStream.h" @30
- include "nsStreamUtils.h" @31
- include "nsString.h" @32
- include "nsThreadUtils.h" @33
- function_definition CheckDecoderState @39-83
- function_definition CheckDecoderResults @85-98
- function_definition WithBadBufferDecode @101-123
- function_definition CheckDecoderBadBuffer @125-129
- class_specifier MonitorAnonymousDecodingTask @135-148
- function_definition ~MonitorAnonymousDecodingTask @145-145
- function_definition MonitorAnonymousDecodingTask @150-153
- function_definition Run @155-177
- function_definition WaitUntilFinished @179-190
- function_definition WithSingleChunkDecode @193-232
- function_definition CheckDecoderSingleChunk @234-240
- function_definition WithDelayedChunkDecode @243-281
- function_definition CheckDecoderDelayedChunk @283-287
- function_definition WithMultiChunkDecode @290-338
- function_definition CheckDecoderMultiChunk @340-345
- function_definition HashDecoderOutput @347-377
- function_definition CheckIncrementalDecodeMatchesOneShot @379-396
- function_definition CheckDownscaleDuringDecode @398-434
- function_definition CheckExifOrientationDownscale @436-464
- function_definition CheckAnimationDecoderResults @466-511
- function_definition WithSingleChunkAnimationDecode @514-569
- function_definition CheckAnimationDecoderSingleChunk @571-577
- function_definition CheckDecoderFrameFirst @579-691
- function_definition CheckDecoderFrameCurrent @693-808
- class_specifier ImageDecoders @810-813
- function_definition TEST_F @854-856
- function_definition TEST_F @858-860
- function_definition TEST_F @862-864
- function_definition TEST_F @866-868
- function_definition TEST_F @870-872
- function_definition TEST_F @874-876
- function_definition TEST_F @878-880
- function_definition TEST_F @882-884
- function_definition TEST_F @886-888
- function_definition TEST_F @891-893
- function_definition TEST_F @896-898
- function_definition TEST_F @900-902
- function_definition TEST_F @904-906
- function_definition TEST_F @908-910
- function_definition TEST_F @912-914
- function_definition TEST_F @916-918
- function_definition TEST_F @920-922
- function_definition TEST_F @924-926
- function_definition TEST_F @928-930
- function_definition TEST_F @932-934
- function_definition TEST_F @936-938
- function_definition TEST_F @940-942
- function_definition TEST_F @944-946
- function_definition TEST_F @948-950
- function_definition TEST_F @952-954
- function_definition TEST_F @956-958
- function_definition TEST_F @960-962
- function_definition TEST_F @964-966
- function_definition TEST_F @968-970
- function_definition TEST_F @972-974
- function_definition TEST_F @976-978
- function_definition TEST_F @980-982
- function_definition TEST_F @984-986
- function_definition TEST_F @988-990
- function_definition TEST_F @992-994
- function_definition TEST_F @996-998
- function_definition TEST_F @1000-1002
- function_definition TEST_F @1004-1006
- function_definition TEST_F @1008-1010
- function_definition TEST_F @1012-1014
- function_definition TEST_F @1016-1018
- function_definition TEST_F @1020-1022
- function_definition TEST_F @1024-1026
- function_definition TEST_F @1028-1030
- function_definition TEST_F @1032-1034
- function_definition TEST_F @1036-1038
- function_definition TEST_F @1043-1045
- function_definition TEST_F @1047-1049
- function_definition TEST_F @1052-1054
- function_definition TEST_F @1060-1069
- function_definition TEST_F @1078-1082
- function_definition DecodeLargeJXL @1088-1102
- function_definition ExpectSurfacesSimilar @1110-1159
- function_definition ExpectSurfacesIdentical @1161-1165
- function_definition TEST_F @1168-1215
- function_definition TEST_F @1218-1269
- function_definition TEST_F @1272-1274
- function_definition TEST_F @1276-1278
- function_definition TEST_F @1280-1282
- function_definition TEST_F @1284-1286
- function_definition TEST_F @1288-1290
- function_definition TEST_F @1292-1294
- function_definition TEST_F @1296-1298
- function_definition TEST_F @1300-1302
- function_definition TEST_F @1304-1306
- function_definition TEST_F @1308-1310
- function_definition TEST_F @1312-1314
- function_definition TEST_F @1316-1318
- function_definition TEST_F @1321-1323
- function_definition TEST_F @1325-1327
- function_definition TEST_F @1329-1331
- function_definition TEST_F @1333-1335
- function_definition TEST_F @1338-1340
- function_definition TEST_F @1342-1344
- function_definition TEST_F @1346-1348
- function_definition TEST_F @1350-1352
- function_definition TEST_F @1354-1356
- function_definition TEST_F @1358-1360
- function_definition TEST_F @1362-1364
- function_definition TEST_F @1366-1368
- function_definition TEST_F @1370-1372
- function_definition TEST_F @1379-1381
- function_definition TEST_F @1384-1386
- function_definition TEST_F @1388-1390
- function_definition TEST_F @1392-1394
- function_definition TEST_F @1396-1398
- function_definition TEST_F @1400-1402
- function_definition TEST_F @1404-1406
- function_definition TEST_F @1408-1410
- function_definition TEST_F @1412-1414
- function_definition TEST_F @1417-1419
- function_definition TEST_F @1421-1423
- function_definition TEST_F @1425-1427
- function_definition TEST_F @1429-1431
- function_definition TEST_F @1433-1435
- function_definition TEST_F @1437-1491
- function_definition TEST_F @1495-1497
- function_definition TEST_F @1499-1501
- function_definition TEST_F @1503-1505
- function_definition TEST_F @1507-1509
- function_definition TEST_F @1511-1513
- function_definition TEST_F @1515-1517
- function_definition TEST_F @1519-1521
- function_definition TEST_F @1523-1525
- function_definition TEST_F @1527-1529
- function_definition TEST_F @1531-1533
- function_definition TEST_F @1535-1537
- function_definition TEST_F @1539-1541
- function_definition TEST_F @1543-1545
- function_definition TEST_F @1547-1549
- function_definition TEST_F @1551-1553
- function_definition TEST_F @1555-1598
- function_definition TEST_F @1600-1602
- function_definition TEST_F @1604-1606
- function_definition TEST_F @1608-1610
- function_definition TEST_F @1612-1614
- function_definition TEST_F @1616-1618
- function_definition TEST_F @1620-1695
- function_definition TEST_F @1697-1700
- function_definition TEST_F @1702-1749

### image/test/gtest/TestDecodersPerf.cpp

Blob: `8de782778f004b62ac92354bde1d5d436a19d8b0`. Grammar: cpp. Status: contains-errors.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "IDecodingTask.h" @8
- include "ProgressTracker.h" @9
- include "SourceBuffer.h" @10
- include "gtest/MozGTestBench.h" @11
- include "gtest/gtest.h" @12
- include "mozilla/Preferences.h" @13
- include "mozilla/RefPtr.h" @14
- function_definition CheckDecoderState @22-61
- function_definition WithSingleChunkDecode @64-84
- function_definition CheckDecode @86-92
- function_definition CheckDownscaleDuringDecode @94-101
- function_definition CheckDownscaleDct @166-177

### image/test/gtest/TestDeinterlacingFilter.cpp

Blob: `0cac6b0fc09efdeab975a3a100c0011cbbf8518a`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfaceFilters.h" @9
- include "SurfacePipe.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gfx/2D.h" @12
- function_definition WithDeinterlacingFilter @19-28
- function_definition AssertConfiguringDeinterlacingFilterFails @30-37
- class_specifier ImageDeinterlacingFilter @39-42
- function_definition TEST_F @44-52
- function_definition TEST_F @54-62
- function_definition TEST_F @64-72
- function_definition TEST_F @74-82
- function_definition TEST_F @84-92
- function_definition TEST_F @94-102
- function_definition TEST_F @104-206
- function_definition TEST_F @208-278
- function_definition TEST_F @280-339
- function_definition TEST_F @341-390
- function_definition TEST_F @392-415
- function_definition WriteRowAndCheckInterlacerOutput @417-454
- function_definition TEST_F @456-536
- function_definition TEST_F @538-619
- function_definition TEST_F @621-624
- function_definition TEST_F @626-629

### image/test/gtest/TestDownscalingFilter.cpp

Blob: `dee880e1aca0f98823df52d1844098be86664996`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfaceFilters.h" @9
- include "SurfacePipe.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gfx/2D.h" @12
- function_definition WithDownscalingFilter @19-28
- function_definition AssertConfiguringDownscalingFilterFails @30-38
- function_definition TEST @40-48
- function_definition TEST @50-58
- function_definition TEST @60-68
- function_definition TEST @70-78
- function_definition TEST @80-88
- function_definition TEST @90-98
- function_definition TEST @100-108
- function_definition TEST @110-114
- function_definition TEST @116-120
- function_definition TEST @122-126
- function_definition TEST @128-132
- function_definition TEST @134-138
- function_definition TEST @140-144
- function_definition TEST @146-186
- function_definition TEST @188-228

### image/test/gtest/TestFrameAnimator.cpp

Blob: `e1ea382c2db2749a4022d71dfe833062713cd6b3`. Grammar: cpp. Status: syntax-clean.

- include "AnimationSurfaceProvider.h" @5
- include "Common.h" @6
- include "Decoder.h" @7
- include "ImageFactory.h" @8
- include "RasterImage.h" @9
- include "gtest/gtest.h" @10
- include "nsIInputStream.h" @11
- function_definition CheckFrameAnimatorBlendResults @17-46
- function_definition WithFrameAnimatorDecode @49-100
- function_definition CheckFrameAnimatorBlend @102-107
- class_specifier ImageFrameAnimator @109-112
- function_definition TEST_F @114-116
- function_definition TEST_F @118-120
- function_definition TEST_F @122-124
- function_definition TEST_F @126-128
- function_definition TEST_F @131-133

### image/test/gtest/TestHDRPNGEncoder.cpp

Blob: `b3cfd8315a693f31b13942f054afc1afaafecfb4`. Grammar: cpp. Status: syntax-clean.

- include <cmath> @5
- include "Common.h" @7
- include "Decoder.h" @8
- include "DecoderFactory.h" @9
- include "IDecodingTask.h" @10
- include "SourceBuffer.h" @11
- include "gtest/gtest.h" @12
- include "imgIEncoder.h" @13
- include "mozilla/gfx/2D.h" @14
- include "nsCOMPtr.h" @15
- include "nsComponentManagerUtils.h" @16
- include "nsStreamUtils.h" @17
- include "nsString.h" @18
- function_definition StrideForFormat @27-32
- struct_specifier ColorRGB @44-46
- function_definition Scale @55-57
- function_definition FillU16Row @59-67
- function_definition FillU16TestPixels @69-74
- function_definition FillU10TestPixels @76-81
- function_definition FillU12TestPixels @83-88
- function_definition PackR10G10B10A2 @90-94
- function_definition FillR10G10B10A2Row @96-103
- function_definition FillR10G10B10A2TestPixels @105-110
- function_definition FracToF16 @119-123
- function_definition FillF16Row @125-133
- function_definition FillF16TestPixels @135-140
- function_definition EncodeHDRPNG @143-169
- function_definition DecodePNG @172-202
- function_definition MakeExpectedRow @206-216
- function_definition VerifyPixels @218-232
- function_definition TEST @234-250
- function_definition TEST @252-268
- function_definition TEST @270-286
- function_definition TEST @288-304
- function_definition TEST @306-322

### image/test/gtest/TestLoader.cpp

Blob: `db4aa5a0d251c9874c51731f359e8b8d4b0a10ea`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "gtest/gtest.h" @6
- include "imgLoader.h" @7
- include "nsMimeTypes.h" @8
- include "nsString.h" @9
- function_definition CheckMimeType @14-25
- class_specifier ImageLoader @27-30
- function_definition TEST_F @32-35
- function_definition TEST_F @37-40
- function_definition TEST_F @42-45
- function_definition TEST_F @47-50
- function_definition TEST_F @52-55
- function_definition TEST_F @57-60
- function_definition TEST_F @62-65
- function_definition TEST_F @67-75
- function_definition TEST_F @77-85
- function_definition TEST_F @88-91
- function_definition TEST_F @93-99
- function_definition TEST_F @102-110
- function_definition TEST_F @112-115

### image/test/gtest/TestMetadata.cpp

Blob: `a0ef1487905d0386d6e0ee635abef4a18e8b5ee2`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "IDecodingTask.h" @8
- include "ImageFactory.h" @9
- include "ProgressTracker.h" @10
- include "SourceBuffer.h" @11
- include "decoders/nsBMPDecoder.h" @12
- include "gtest/gtest.h" @13
- include "imgIContainer.h" @14
- include "mozilla/RefPtr.h" @15
- include "mozilla/gfx/2D.h" @16
- include "nsCOMPtr.h" @17
- include "nsComponentManagerUtils.h" @18
- include "nsIInputStream.h" @19
- include "nsStreamUtils.h" @20
- include "nsString.h" @21
- include "nsThreadUtils.h" @22
- enum_specifier BMPWithinICO @28-28
- function_definition CheckMetadataFrameCount @30-124
- function_definition CheckMetadataCommon @126-216
- function_definition CheckMetadata @218-247
- class_specifier ImageDecoderMetadata @249-252
- function_definition TEST_F @254-256
- function_definition TEST_F @258-258
- function_definition TEST_F @259-261
- function_definition TEST_F @262-262
- function_definition TEST_F @263-265
- function_definition TEST_F @266-266
- function_definition TEST_F @267-267
- function_definition TEST_F @268-268
- function_definition TEST_F @269-269
- function_definition TEST_F @270-270
- function_definition TEST_F @271-271
- function_definition TEST_F @273-275
- function_definition TEST_F @278-278
- function_definition TEST_F @279-281
- function_definition TEST_F @284-286
- function_definition TEST_F @288-290
- function_definition TEST_F @292-294
- function_definition TEST_F @296-298
- function_definition TEST_F @301-303
- function_definition TEST_F @305-307
- function_definition TEST_F @310-312
- function_definition TEST_F @314-317
- function_definition TEST_F @319-322
- function_definition TEST_F @324-324
- function_definition TEST_F @325-325
- function_definition TEST_F @327-327
- function_definition TEST_F @329-334
- function_definition TEST_F @336-407

### image/test/gtest/TestRemoveFrameRectFilter.cpp

Blob: `72031ced02a0511ba55af09cc093cd6a72e54845`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfaceFilters.h" @9
- include "SurfacePipe.h" @10
- include "gtest/gtest.h" @11
- include "mozilla/gfx/2D.h" @12
- function_definition WithRemoveFrameRectFilter @19-27
- function_definition AssertConfiguringRemoveFrameRectFilterFails @29-37
- function_definition TEST @39-49
- function_definition TEST @51-62
- function_definition TEST @64-75
- function_definition TEST @77-88
- function_definition TEST @90-101
- function_definition TEST @103-114
- function_definition TEST @116-130
- function_definition TEST @132-146
- function_definition TEST @148-162
- function_definition TEST @164-178
- function_definition TEST @180-194
- function_definition TEST @196-208
- function_definition TEST @210-221
- function_definition TEST @223-234
- function_definition TEST @236-247
- function_definition TEST @249-261
- function_definition TEST @263-278
- function_definition TEST @280-285
- function_definition TEST @287-293
- function_definition TEST @295-300
- function_definition TEST @302-308

### image/test/gtest/TestSourceBuffer.cpp

Blob: `e2a6e09855a6f9f92242deb8156a07a91aee40d0`. Grammar: cpp. Status: syntax-clean.

- include <algorithm> @5
- include <cstdint> @6
- include <utility> @7
- include "Common.h" @9
- include "SourceBuffer.h" @10
- include "SurfaceCache.h" @11
- include "gtest/gtest.h" @12
- include "nsIInputStream.h" @13
- function_definition ExpectChunkAndByteCount @20-24
- function_definition ExpectRemainingBytes @26-35
- function_definition GenerateByte @37-40
- function_definition GenerateData @42-46
- function_definition GenerateData @48-50
- function_definition CheckData @52-56
- enum_specifier AdvanceMode @58-58
- class_specifier ImageSourceBuffer @60-173
- function_definition ImageSourceBuffer @62-68
- function_definition CheckedAppendToBuffer @71-73
- function_definition CheckedAppendToBufferLastByteForLength @75-78
- function_definition CheckedAppendToBufferInChunks @80-92
- function_definition CheckedCompleteBuffer @94-97
- function_definition CheckedCompleteBuffer @99-103
- function_definition CheckedAdvanceIteratorStateOnly @105-119
- function_definition CheckedAdvanceIteratorStateOnly @121-124
- function_definition CheckedAdvanceIterator @126-140
- function_definition CheckedAdvanceIterator @142-144
- function_definition CheckIteratorMustWait @146-150
- function_definition CheckIteratorIsComplete @152-161
- function_definition CheckIteratorIsComplete @163-166
- function_definition TEST_F @175-190
- function_definition TEST_F @192-203
- function_definition TEST_F @205-218
- function_definition TEST_F @220-233
- function_definition TEST_F @235-247
- function_definition TEST_F @249-264
- function_definition TEST_F @266-286
- function_definition TEST_F @288-308
- function_definition TEST_F @310-330
- function_definition TEST_F @332-350
- function_definition TEST_F @352-374
- function_definition TEST_F @376-392
- function_definition TEST_F @394-417
- function_definition TEST_F @419-455
- function_definition TEST_F @457-473
- function_definition TEST_F @475-500
- function_definition TEST_F @502-541
- function_definition TEST_F @543-586
- function_definition TEST_F @588-627
- function_definition TEST_F @629-681
- function_definition TEST_F @683-696
- function_definition TEST_F @698-708
- function_definition TEST_F @710-719
- function_definition TEST_F @721-751
- function_definition TEST_F @753-762
- function_definition TEST_F @764-773
- function_definition TEST_F @775-788
- function_definition TEST_F @790-805
- function_definition TEST_F @807-822
- function_definition TEST_F @824-845
- function_definition TEST_F @847-851
- function_definition TEST_F @853-878
- function_definition TEST_F @880-895
- function_definition TEST_F @897-931

### image/test/gtest/TestStreamingLexer.cpp

Blob: `a37be93b6af201c1b67cc6d80cae9bfd2790ae3c`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "StreamingLexer.h" @6
- include "gtest/gtest.h" @7
- include "mozilla/Vector.h" @8
- enum_specifier TestState @13-20
- function_definition CheckLexedData @22-29
- function_definition DoLex @31-50
- function_definition DoLexWithUnbuffered @52-73
- function_definition DoLexWithUnbufferedTerminate @75-87
- function_definition DoLexWithYield @89-104
- function_definition DoLexWithTerminateAfterYield @106-118
- function_definition DoLexWithZeroLengthStates @120-136
- function_definition DoLexWithZeroLengthStatesAtEnd @138-154
- function_definition DoLexWithZeroLengthYield @156-172
- function_definition DoLexWithZeroLengthStatesUnbuffered @174-192
- function_definition DoLexWithZeroLengthStatesAfterUnbuffered @194-212
- class_specifier ImageStreamingLexer @214-260
- function_definition ImageStreamingLexer @220-226
- function_definition CheckTruncatedState @229-251
- function_definition TEST_F @262-270
- function_definition TEST_F @272-286
- function_definition TEST_F @288-299
- function_definition TEST_F @301-310
- function_definition TEST_F @312-327
- function_definition TEST_F @329-341
- function_definition TEST_F @343-360
- function_definition TEST_F @362-385
- function_definition TEST_F @387-405
- function_definition TEST_F @407-487
- function_definition TEST_F @489-506
- function_definition TEST_F @508-531
- function_definition TEST_F @533-563
- function_definition TEST_F @565-579
- function_definition TEST_F @581-595
- function_definition TEST_F @597-619
- function_definition TEST_F @621-636
- function_definition TEST_F @638-652
- function_definition TEST_F @654-748
- function_definition TEST_F @750-773
- function_definition TEST_F @775-798
- function_definition TEST_F @800-823
- function_definition TEST_F @825-851
- function_definition TEST_F @853-863
- function_definition TEST_F @865-872
- function_definition TEST_F @874-881
- function_definition TEST_F @883-893
- function_definition TEST_F @895-905
- function_definition TEST_F @907-916
- function_definition TEST_F @918-934

### image/test/gtest/TestSurfaceCache.cpp

Blob: `cc8985bd0c9e858415cabed1eb899b6b380e2dcd`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "ImageFactory.h" @6
- include "ProgressTracker.h" @7
- include "gtest/gtest.h" @8
- include "imgIContainer.h" @9
- include "mozilla/RefPtr.h" @10
- include "mozilla/StaticPrefs_image.h" @11
- include "mozilla/gfx/2D.h" @12
- include "nsIInputStream.h" @13
- include "nsString.h" @14
- class_specifier ImageSurfaceCache @20-23
- function_definition TEST_F @25-157

### image/test/gtest/TestSurfacePipeIntegration.cpp

Blob: `61afcc7c2c3dfdd3e0c3dd4743839100df5b74c5`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfacePipe.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/gfx/2D.h" @11
- class_specifier TestSurfacePipeFactory @20-34
- function_definition SimpleSurfacePipe @22-25
- function_definition SurfacePipeFromPipeline @28-30
- function_definition TestSurfacePipeFactory @33-33
- function_definition CheckSurfacePipeMethodResults @39-78
- class_specifier ImageSurfacePipeIntegration @80-83
- function_definition TEST_F @85-182
- function_definition TEST_F @184-198
- function_definition TEST_F @200-253
- function_definition TEST_F @255-285
- function_definition TEST_F @287-308
- function_definition TEST_F @310-330
- function_definition TEST_F @332-346

### image/test/gtest/TestSurfaceSink.cpp

Blob: `11313ef787c896ce7090c52f58ffcde0ac0e4f0a`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SourceBuffer.h" @8
- include "SurfacePipe.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/gfx/2D.h" @11
- enum_specifier Orient @17-17
- function_definition InitializeRowBuffer @19-32
- function_definition WithSurfaceSink @35-44
- function_definition ResetForNextPass @46-51
- function_definition DoCheckIterativeWrite @54-72
- function_definition CheckIterativeWrite @75-82
- function_definition TEST @84-100
- function_definition TEST @102-108
- function_definition TEST @110-141
- function_definition TEST @143-218
- function_definition TEST @220-279
- function_definition TEST @281-354
- function_definition TEST @356-371
- function_definition TEST @373-389
- function_definition TEST @391-423
- function_definition TEST @425-461
- function_definition TEST @463-480
- function_definition TEST @482-552
- function_definition TEST @554-576
- function_definition TEST @578-624
- function_definition TEST @626-720
- function_definition TEST @722-773
- function_definition TEST @775-898
- function_definition TEST @900-979

### image/test/gtest/TestSwizzleFilter.cpp

Blob: `823281005f748c339e7cb413174d854ddb03e681`. Grammar: cpp. Status: syntax-clean.

- include "Common.h" @5
- include "Decoder.h" @6
- include "DecoderFactory.h" @7
- include "SurfaceFilters.h" @8
- include "SurfacePipe.h" @9
- include "gtest/gtest.h" @10
- include "mozilla/gfx/2D.h" @11
- function_definition WithSwizzleFilter @18-28
- function_definition TEST @30-38
- function_definition TEST @40-50
- function_definition TEST @52-61
- function_definition TEST @63-72
- function_definition TEST @74-83
- function_definition TEST @85-94
- function_definition TEST @96-105
- function_definition TEST @107-117

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
