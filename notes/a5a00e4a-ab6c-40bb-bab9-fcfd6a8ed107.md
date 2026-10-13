<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:17:22.071Z","paths":["chat/protocols/matrix/lib/matrix-sdk/crypto/index.js","chat/protocols/matrix/lib/matrix-sdk/crypto/key_passphrase.js","chat/protocols/matrix/lib/matrix-sdk/crypto/keybackup.js","chat/protocols/matrix/lib/matrix-sdk/crypto/olmlib.js","chat/protocols/matrix/lib/matrix-sdk/crypto/recoverykey.js","chat/protocols/matrix/lib/matrix-sdk/crypto/store/base.js","chat/protocols/matrix/lib/matrix-sdk/crypto/store/indexeddb-crypto-store-backend.js","chat/protocols/matrix/lib/matrix-sdk/crypto/store/indexeddb-crypto-store.js","chat/protocols/matrix/lib/matrix-sdk/crypto/store/localStorage-crypto-store.js","chat/protocols/matrix/lib/matrix-sdk/crypto/store/memory-crypto-store.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/Base.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/Error.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/IllegalMethod.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/QRCode.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/SAS.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/SASDecimal.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/Channel.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/InRoomChannel.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/ToDeviceChannel.js","chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/VerificationRequest.js","chat/protocols/matrix/lib/matrix-sdk/digest.js","chat/protocols/matrix/lib/matrix-sdk/embedded.js","chat/protocols/matrix/lib/matrix-sdk/errors.js","chat/protocols/matrix/lib/matrix-sdk/event-mapper.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/ExtensibleEvent.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/InvalidEventError.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/MessageEvent.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollEndEvent.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollResponseEvent.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollStartEvent.js","chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/utilities.js","chat/protocols/matrix/lib/matrix-sdk/feature.js","chat/protocols/matrix/lib/matrix-sdk/filter-component.js","chat/protocols/matrix/lib/matrix-sdk/filter.js","chat/protocols/matrix/lib/matrix-sdk/http-api/errors.js","chat/protocols/matrix/lib/matrix-sdk/http-api/fetch.js","chat/protocols/matrix/lib/matrix-sdk/http-api/index.js","chat/protocols/matrix/lib/matrix-sdk/http-api/interface.js","chat/protocols/matrix/lib/matrix-sdk/http-api/method.js","chat/protocols/matrix/lib/matrix-sdk/http-api/prefix.js","chat/protocols/matrix/lib/matrix-sdk/http-api/utils.js","chat/protocols/matrix/lib/matrix-sdk/index.js","chat/protocols/matrix/lib/matrix-sdk/indexeddb-helpers.js","chat/protocols/matrix/lib/matrix-sdk/indexeddb-worker.js","chat/protocols/matrix/lib/matrix-sdk/interactive-auth.js","chat/protocols/matrix/lib/matrix-sdk/logger.js","chat/protocols/matrix/lib/matrix-sdk/matrix.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/CallMembership.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/LivekitFocus.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/MatrixRTCSession.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/MatrixRTCSessionManager.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/focus.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/index.js","chat/protocols/matrix/lib/matrix-sdk/matrixrtc/types.js","chat/protocols/matrix/lib/matrix-sdk/models/MSC3089Branch.js","chat/protocols/matrix/lib/matrix-sdk/models/MSC3089TreeSpace.js","chat/protocols/matrix/lib/matrix-sdk/models/ToDeviceMessage.js","chat/protocols/matrix/lib/matrix-sdk/models/beacon.js","chat/protocols/matrix/lib/matrix-sdk/models/compare-event-ordering.js","chat/protocols/matrix/lib/matrix-sdk/models/device.js","chat/protocols/matrix/lib/matrix-sdk/models/event-context.js","chat/protocols/matrix/lib/matrix-sdk/models/event-status.js"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-study-20261013"}} -->
# thunderbird/chat JavaScript function map 11

Revision: `87d0159c7149a43253964c2cb6917939557dc799`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### chat/protocols/matrix/lib/matrix-sdk/crypto/index.js

Blob: `3f62f1d6a7caa45f9fda2c2b85324044d7fce072`. Role: source. Parse: module.

- _getRequireWildcardCache @53-53; FunctionDeclaration; parameters=1; async=false; generator=false
- _getRequireWildcardCache @53-53; FunctionExpression; parameters=1; async=false; generator=false
- _interopRequireWildcard @54-54; FunctionDeclaration; parameters=2; async=false; generator=false
- _interopRequireDefault @55-55; FunctionDeclaration; parameters=1; async=false; generator=false
- ownKeys @56-56; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @56-56; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @57-57; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @57-57; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @57-57; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @58-58; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @59-59; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @60-60; FunctionDeclaration; parameters=2; async=false; generator=false
- isCryptoAvailable @99-101; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @123-142; FunctionExpression; parameters=1; async=false; generator=false
- getOlmVersion @147-149; FunctionExpression; parameters=0; async=false; generator=false
- constructor @171-402; FunctionExpression; parameters=6; async=false; generator=false
- (anonymous) @226-226; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @226-226; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @237-273; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @274-280; ArrowFunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @281-310; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @303-305; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @321-332; ArrowFunctionExpression; parameters=5; async=false; generator=false
- createRequest @327-330; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @352-377; ArrowFunctionExpression; parameters=0; async=true; generator=false
- cryptoCallbacks.getCrossSigningKey @398-400; ArrowFunctionExpression; parameters=1; async=true; generator=false
- init @412-463; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @447-455; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @448-454; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setDeviceIsolationMode @468-470; FunctionExpression; parameters=1; async=false; generator=false
- getVersion @474-477; FunctionExpression; parameters=0; async=false; generator=false
- getTrustCrossSignedDevices @488-490; FunctionExpression; parameters=0; async=false; generator=false
- getCryptoTrustCrossSignedDevices @495-497; FunctionExpression; parameters=0; async=false; generator=false
- setTrustCrossSignedDevices @504-519; FunctionExpression; parameters=1; async=false; generator=false
- setCryptoTrustCrossSignedDevices @524-526; FunctionExpression; parameters=1; async=false; generator=false
- createRecoveryKeyFromPassphrase @538-567; FunctionExpression; parameters=1; async=true; generator=false
- userHasCrossSigningKeys @577-580; FunctionExpression; parameters=1; async=true; generator=false
- isCrossSigningReady @596-600; FunctionExpression; parameters=0; async=true; generator=false
- isSecretStorageReady @617-622; FunctionExpression; parameters=0; async=true; generator=false
- getCrossSigningStatus @627-643; FunctionExpression; parameters=0; async=true; generator=false
- bootstrapCrossSigning @656-736; FunctionExpression; parameters=1; async=true; generator=false
- resetCrossSigning @666-685; ArrowFunctionExpression; parameters=0; async=true; generator=false
- bootstrapSecretStorage @758-962; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @759-759; ArrowFunctionExpression; parameters=0; async=true; generator=false
- createSSSS @774-784; ArrowFunctionExpression; parameters=1; async=true; generator=false
- ensureCanCheckPassphrase @785-804; ArrowFunctionExpression; parameters=2; async=true; generator=false
- signKeyBackupWithCrossSigning @805-818; ArrowFunctionExpression; parameters=1; async=true; generator=false
- resetKeyBackup @967-990; FunctionExpression; parameters=0; async=true; generator=false
- deleteKeyBackupVersion @995-997; FunctionExpression; parameters=1; async=true; generator=false
- addSecretStorageKey @1002-1004; FunctionExpression; parameters=3; async=false; generator=false
- hasSecretStorageKey @1009-1011; FunctionExpression; parameters=1; async=false; generator=false
- getSecretStorageKey @1016-1018; FunctionExpression; parameters=1; async=false; generator=false
- storeSecret @1023-1025; FunctionExpression; parameters=3; async=false; generator=false
- getSecret @1030-1032; FunctionExpression; parameters=1; async=false; generator=false
- isSecretStored @1037-1039; FunctionExpression; parameters=1; async=false; generator=false
- requestSecret @1040-1045; FunctionExpression; parameters=2; async=false; generator=false
- getDefaultSecretStorageKeyId @1050-1052; FunctionExpression; parameters=0; async=false; generator=false
- setDefaultSecretStorageKeyId @1057-1059; FunctionExpression; parameters=1; async=false; generator=false
- checkSecretStorageKey @1064-1066; FunctionExpression; parameters=2; async=false; generator=false
- checkSecretStoragePrivateKey @1077-1087; FunctionExpression; parameters=2; async=false; generator=false
- getSessionBackupPrivateKey @1093-1112; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1094-1098; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1095-1097; ArrowFunctionExpression; parameters=1; async=false; generator=false
- storeSessionBackupPrivateKey @1119-1129; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1126-1128; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getActiveSessionBackupVersion @1136-1141; FunctionExpression; parameters=0; async=true; generator=false
- isKeyBackupTrusted @1148-1151; FunctionExpression; parameters=1; async=true; generator=false
- checkKeyBackupAndEnable @1158-1165; FunctionExpression; parameters=0; async=true; generator=false
- checkCrossSigningPrivateKey @1176-1186; FunctionExpression; parameters=2; async=false; generator=false
- afterCrossSigningLocalKeyChange @1194-1262; FunctionExpression; parameters=0; async=true; generator=false
- upload @1201-1225; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1208-1222; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1222-1224; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkForDeviceVerificationUpgrade @1271-1285; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1280-1280; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkForValidDeviceSignature @1295-1309; FunctionExpression; parameters=3; async=true; generator=false
- getCrossSigningKeyId @1319-1321; FunctionExpression; parameters=1; async=false; generator=false
- getCrossSigningId @1324-1326; FunctionExpression; parameters=1; async=false; generator=false
- getStoredCrossSigningForUser @1335-1337; FunctionExpression; parameters=1; async=false; generator=false
- checkUserTrust @1346-1352; FunctionExpression; parameters=1; async=false; generator=false
- getUserVerificationStatus @1357-1359; FunctionExpression; parameters=1; async=true; generator=false
- pinCurrentUserIdentity @1364-1366; FunctionExpression; parameters=1; async=true; generator=false
- getDeviceVerificationStatus @1374-1380; FunctionExpression; parameters=2; async=true; generator=false
- checkDeviceTrust @1385-1388; FunctionExpression; parameters=2; async=false; generator=false
- checkDeviceInfoTrust @1398-1409; FunctionExpression; parameters=2; async=false; generator=false
- checkIfOwnDeviceCrossSigned @1419-1424; FunctionExpression; parameters=1; async=false; generator=false
- checkOwnCrossSigningTrust @1429-1565; FunctionExpression; parameters=1; async=true; generator=false
- upload @1528-1550; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1534-1547; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1547-1549; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getBackupDecryptor @1570-1587; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1574-1576; ArrowFunctionExpression; parameters=0; async=true; generator=false
- importBackedUpRoomKeys @1592-1595; FunctionExpression; parameters=3; async=false; generator=false
- storeTrustedSelfKeys @1602-1611; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1608-1610; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkDeviceVerifications @1619-1643; FunctionExpression; parameters=1; async=true; generator=false
- enableLazyLoading @1647-1649; FunctionExpression; parameters=0; async=false; generator=false
- registerEventHandlers @1658-1663; FunctionExpression; parameters=1; async=false; generator=false
- start @1668-1670; FunctionExpression; parameters=0; async=false; generator=false
- stop @1673-1678; FunctionExpression; parameters=0; async=false; generator=false
- getDeviceEd25519Key @1687-1689; FunctionExpression; parameters=0; async=false; generator=false
- getDeviceCurve25519Key @1698-1700; FunctionExpression; parameters=0; async=false; generator=false
- getOwnDeviceKeys @1705-1716; FunctionExpression; parameters=0; async=true; generator=false
- setGlobalBlacklistUnverifiedDevices @1727-1729; FunctionExpression; parameters=1; async=false; generator=false
- getGlobalBlacklistUnverifiedDevices @1736-1738; FunctionExpression; parameters=0; async=false; generator=false
- uploadDeviceKeys @1744-1756; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1751-1755; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getNeedsNewFallback @1757-1759; FunctionExpression; parameters=0; async=false; generator=false
- maybeUploadOneTimeKeys @1762-1864; FunctionExpression; parameters=0; async=false; generator=false
- uploadLoop @1802-1838; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @1840-1850; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @1847-1849; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1850-1856; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1856-1858; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1858-1863; ArrowFunctionExpression; parameters=0; async=false; generator=false
- uploadOneTimeKeys @1867-1911; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @1904-1907; ArrowFunctionExpression; parameters=0; async=false; generator=false
- downloadKeys @1921-1923; FunctionExpression; parameters=2; async=false; generator=false
- getStoredDevicesForUser @1933-1935; FunctionExpression; parameters=1; async=false; generator=false
- getUserDeviceInfo @1946-1977; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @1957-1957; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1967-1974; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @1970-1970; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getStoredDevice @1986-1988; FunctionExpression; parameters=2; async=false; generator=false
- saveDeviceList @2002-2004; FunctionExpression; parameters=1; async=false; generator=false
- setDeviceVerified @2011-2013; FunctionExpression; parameters=3; async=true; generator=false
- crossSignDevice @2020-2022; FunctionExpression; parameters=1; async=true; generator=false
- setDeviceVerification @2046-2186; FunctionExpression; parameters=6; async=true; generator=false
- upload @2073-2095; ArrowFunctionExpression; parameters=1; async=true; generator=false
- upload @2155-2176; ArrowFunctionExpression; parameters=1; async=true; generator=false
- findVerificationRequestDMInProgress @2187-2189; FunctionExpression; parameters=2; async=false; generator=false
- getVerificationRequestsToDeviceInProgress @2190-2192; FunctionExpression; parameters=1; async=false; generator=false
- requestVerificationDM @2193-2200; FunctionExpression; parameters=2; async=false; generator=false
- requestVerification @2203-2213; FunctionExpression; parameters=2; async=false; generator=false
- requestOwnUserVerification @2214-2216; FunctionExpression; parameters=0; async=false; generator=false
- requestDeviceVerification @2217-2219; FunctionExpression; parameters=2; async=false; generator=false
- requestVerificationWithChannel @2220-2236; FunctionExpression; parameters=3; async=true; generator=false
- beginKeyVerification @2237-2254; FunctionExpression; parameters=4; async=false; generator=false
- legacyDeviceVerification @2255-2269; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @2267-2267; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getOlmSessionsForUser @2283-2295; FunctionExpression; parameters=1; async=true; generator=false
- getEventSenderDeviceInfo @2302-2341; FunctionExpression; parameters=1; async=false; generator=false
- getEventEncryptionInfo @2359-2400; FunctionExpression; parameters=1; async=false; generator=false
- getEncryptionInfoForEvent @2405-2467; FunctionExpression; parameters=1; async=true; generator=false
- forceDiscardSession @2477-2485; FunctionExpression; parameters=1; async=false; generator=false
- setRoomEncryption @2502-2511; FunctionExpression; parameters=3; async=true; generator=false
- setRoomEncryptionImpl @2526-2605; FunctionExpression; parameters=2; async=true; generator=false
- onState @2595-2602; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2598-2600; ArrowFunctionExpression; parameters=1; async=false; generator=false
- trackRoomDevices @2615-2621; FunctionExpression; parameters=1; async=false; generator=false
- trackRoomDevicesImpl @2633-2655; FunctionExpression; parameters=1; async=false; generator=false
- trackMembers @2635-2645; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2642-2644; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2649-2652; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ensureOlmSessionsForUsers @2668-2689; FunctionExpression; parameters=2; async=false; generator=false
- exportRoomKeys @2696-2708; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @2698-2706; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2699-2705; ArrowFunctionExpression; parameters=1; async=false; generator=false
- exportRoomKeysAsJson @2716-2718; FunctionExpression; parameters=0; async=true; generator=false
- importRoomKeys @2726-2755; FunctionExpression; parameters=2; async=false; generator=false
- updateProgress @2730-2737; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @2738-2754; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2748-2753; ArrowFunctionExpression; parameters=0; async=false; generator=false
- importRoomKeysAsJson @2766-2768; FunctionExpression; parameters=2; async=true; generator=false
- countSessionsNeedingBackup @2774-2776; FunctionExpression; parameters=0; async=false; generator=false
- prepareToEncrypt @2784-2789; FunctionExpression; parameters=1; async=false; generator=false
- encryptEvent @2801-2836; FunctionExpression; parameters=2; async=true; generator=false
- decryptEvent @2846-2878; FunctionExpression; parameters=1; async=true; generator=false
- processDeviceLists @2886-2896; FunctionExpression; parameters=1; async=true; generator=false
- requestRoomKey @2906-2915; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @2907-2911; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @2911-2914; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cancelRoomKeyRequest @2922-2926; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @2923-2925; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cancelAndResendAllOutgoingKeyRequests @2932-2934; FunctionExpression; parameters=0; async=true; generator=false
- onCryptoEvent @2942-2945; FunctionExpression; parameters=2; async=true; generator=false
- onSyncWillProcess @2952-2965; FunctionExpression; parameters=1; async=true; generator=false
- onSyncCompleted @2975-2999; FunctionExpression; parameters=1; async=true; generator=false
- evalDeviceListChanges @3008-3025; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3010-3012; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3019-3023; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getTrackedE2eUsers @3033-3042; FunctionExpression; parameters=0; async=true; generator=false
- getTrackedE2eRooms @3050-3065; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @3051-3064; ArrowFunctionExpression; parameters=1; async=false; generator=false
- encryptAndSendToDevices @3079-3092; FunctionExpression; parameters=2; async=true; generator=false
- prepareToDeviceBatch @3093-3131; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @3098-3116; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3122-3129; ArrowFunctionExpression; parameters=1; async=false; generator=false
- encryptToDeviceMessages @3136-3162; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @3137-3139; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3142-3160; ArrowFunctionExpression; parameters=1; async=false; generator=false
- preprocessToDeviceMessages @3163-3173; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @3166-3172; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateOneTimeKeyCount @3181-3187; FunctionExpression; parameters=1; async=false; generator=false
- processKeyCounts @3188-3200; FunctionExpression; parameters=2; async=false; generator=false
- onRoomKeyEvent @3207-3220; FunctionExpression; parameters=1; async=false; generator=false
- onRoomKeyWithheldEvent @3228-3248; FunctionExpression; parameters=1; async=false; generator=false
- onKeyVerificationMessage @3256-3274; FunctionExpression; parameters=1; async=false; generator=false
- createRequest @3260-3272; ArrowFunctionExpression; parameters=1; async=false; generator=false
- handleVerificationEvent @3275-3324; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @3281-3290; ArrowFunctionExpression; parameters=2; async=false; generator=false
- statusListener @3283-3287; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onToDeviceBadEncrypted @3332-3414; FunctionExpression; parameters=1; async=true; generator=false
- retryDecryption @3342-3347; ArrowFunctionExpression; parameters=0; async=false; generator=false
- onRoomMembership @3424-3454; FunctionExpression; parameters=3; async=false; generator=false
- onRoomKeyRequestEvent @3462-3474; FunctionExpression; parameters=1; async=false; generator=false
- processReceivedRoomKeyRequests @3482-3511; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @3504-3504; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @3505-3505; ArrowFunctionExpression; parameters=1; async=false; generator=false
- processReceivedRoomKeyRequest @3517-3584; FunctionExpression; parameters=1; async=true; generator=false
- req.share @3573-3575; ArrowFunctionExpression; parameters=0; async=false; generator=false
- processReceivedRoomKeyRequestCancellation @3590-3597; FunctionExpression; parameters=1; async=true; generator=false
- getRoomDecryptor @3614-3643; FunctionExpression; parameters=2; async=false; generator=false
- getRoomDecryptors @3652-3660; FunctionExpression; parameters=1; async=false; generator=false
- signObject @3667-3677; FunctionExpression; parameters=1; async=true; generator=false
- isRoomEncrypted @3683-3685; FunctionExpression; parameters=1; async=false; generator=false
- isEncryptionEnabledInRoom @3690-3692; FunctionExpression; parameters=1; async=true; generator=false
- getRoomEncryption @3698-3700; FunctionExpression; parameters=1; async=false; generator=false
- isDehydrationSupported @3706-3708; FunctionExpression; parameters=0; async=true; generator=false
- startDehydration @3713-3715; FunctionExpression; parameters=1; async=true; generator=false
- fixBackupKey @3731-3737; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @3735-3735; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @3743-3765; FunctionExpression; parameters=1; async=false; generator=false
- ?.share @3762-3764; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @3773-3784; FunctionExpression; parameters=1; async=false; generator=false
- Class IncomingRoomKeyRequestCancellation @3772-3785
- Class IncomingRoomKeyRequest @3742-3766
- Class Crypto @143-3716

### chat/protocols/matrix/lib/matrix-sdk/crypto/key_passphrase.js

Blob: `c29eccec8e539628ef2e239bf4747f7b6960567d`. Role: source. Parse: module.

- get @8-10; FunctionExpression; parameters=0; async=false; generator=false
- get @14-16; FunctionExpression; parameters=0; async=false; generator=false
- keyFromPassphrase @43-51; FunctionDeclaration; parameters=1; async=true; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/keybackup.js

Blob: `430afc16cdfa1c471b1b89abcb059363dd193d64`. Role: source. Parse: module.


### chat/protocols/matrix/lib/matrix-sdk/crypto/olmlib.js

Blob: `ed88d7539eb0d850095921dc968e8218d76fa132`. Role: source. Parse: module.

- _interopRequireDefault @18-18; FunctionDeclaration; parameters=1; async=false; generator=false
- ownKeys @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @21-21; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @22-22; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @23-23; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @40-45; FunctionExpression; parameters=1; async=false; generator=false
- encryptMessageForDevice @72-112; FunctionDeclaration; parameters=7; async=true; generator=false
- getExistingOlmSessions @126-151; FunctionDeclaration; parameters=3; async=true; generator=false
- (anonymous) @128-128; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @130-130; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @136-146; ArrowFunctionExpression; parameters=0; async=true; generator=false
- ensureOlmSessionsForDevices @173-318; FunctionDeclaration; parameters=7; async=true; generator=false
- (anonymous) @199-204; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @200-203; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @303-307; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @307-310; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _verifyKeyAndStartSession @319-337; FunctionDeclaration; parameters=4; async=true; generator=false
- verifySignature @354-371; FunctionDeclaration; parameters=5; async=true; generator=false
- pkSign @383-406; FunctionDeclaration; parameters=4; async=false; generator=false
- pkVerify @414-432; FunctionDeclaration; parameters=3; async=false; generator=false
- isOlmEncrypted @437-447; FunctionDeclaration; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/recoverykey.js

Blob: `fe7a7c3e7610af96ee2c3aa4ea9dec74d16e8924`. Role: source. Parse: module.

- (anonymous) @7-16; FunctionExpression; parameters=1; async=false; generator=false
- get @12-14; FunctionExpression; parameters=0; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/store/base.js

Blob: `d2ab265d52032e3e674cedcd21d35cf6cbc7fcb9`. Role: source. Parse: module.

- (anonymous) @55-63; FunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/store/indexeddb-crypto-store-backend.js

Blob: `d0a2064502a70e14f30b0225bb9b99c791cc5fe1`. Role: source. Parse: module.

- _defineProperty @12-12; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @14-14; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @41-51; FunctionExpression; parameters=1; async=false; generator=false
- db.onversionchange @47-50; ArrowFunctionExpression; parameters=0; async=false; generator=false
- containsData @52-54; FunctionExpression; parameters=0; async=true; generator=false
- startup @55-59; FunctionExpression; parameters=0; async=true; generator=false
- deleteAllData @60-62; FunctionExpression; parameters=0; async=true; generator=false
- getMigrationState @69-79; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @71-77; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getReq.onsuccess @74-76; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setMigrationState @86-91; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @87-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getOrAddOutgoingRoomKeyRequest @102-127; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-126; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @109-125; ArrowFunctionExpression; parameters=1; async=false; generator=false
- txn.oncomplete @120-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOutgoingRoomKeyRequest @138-146; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @139-145; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @142-144; ArrowFunctionExpression; parameters=1; async=false; generator=false
- _getOutgoingRoomKeyRequest @160-181; FunctionExpression; parameters=3; async=false; generator=false
- cursorReq.onsuccess @164-180; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOutgoingRoomKeyRequestByState @193-229; FunctionExpression; parameters=1; async=false; generator=false
- onsuccess @205-222; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @228-228; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAllOutgoingRoomKeyRequestsByState @235-244; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @236-243; ArrowFunctionExpression; parameters=2; async=false; generator=false
- request.onsuccess @241-241; ArrowFunctionExpression; parameters=0; async=false; generator=false
- request.onerror @242-242; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOutgoingRoomKeyRequestsByTarget @245-274; FunctionExpression; parameters=3; async=false; generator=false
- onsuccess @248-267; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @252-252; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @273-273; ArrowFunctionExpression; parameters=0; async=false; generator=false
- updateOutgoingRoomKeyRequest @288-308; FunctionExpression; parameters=3; async=false; generator=false
- onsuccess @290-303; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @307-307; ArrowFunctionExpression; parameters=0; async=false; generator=false
- deleteOutgoingRoomKeyRequest @319-335; FunctionExpression; parameters=2; async=false; generator=false
- cursorReq.onsuccess @322-333; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getAccount @339-349; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @342-348; FunctionExpression; parameters=0; async=false; generator=false
- storeAccount @350-353; FunctionExpression; parameters=2; async=false; generator=false
- getCrossSigningKeys @354-364; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @357-363; FunctionExpression; parameters=0; async=false; generator=false
- getSecretStorePrivateKey @365-375; FunctionExpression; parameters=3; async=false; generator=false
- getReq.onsuccess @368-374; FunctionExpression; parameters=0; async=false; generator=false
- storeCrossSigningKeys @376-379; FunctionExpression; parameters=2; async=false; generator=false
- storeSecretStorePrivateKey @380-383; FunctionExpression; parameters=3; async=false; generator=false
- countEndToEndSessions @387-397; FunctionExpression; parameters=2; async=false; generator=false
- countReq.onsuccess @390-396; FunctionExpression; parameters=0; async=false; generator=false
- getEndToEndSessions @398-419; FunctionExpression; parameters=3; async=false; generator=false
- getReq.onsuccess @403-418; FunctionExpression; parameters=0; async=false; generator=false
- getEndToEndSession @420-437; FunctionExpression; parameters=4; async=false; generator=false
- getReq.onsuccess @423-436; FunctionExpression; parameters=0; async=false; generator=false
- getAllEndToEndSessions @438-454; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @441-453; FunctionExpression; parameters=0; async=false; generator=false
- storeEndToEndSession @455-463; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndSessionProblem @464-474; FunctionExpression; parameters=3; async=true; generator=false
- getEndToEndSessionProblem @475-507; FunctionExpression; parameters=2; async=true; generator=false
- req.onsuccess @481-504; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @487-489; ArrowFunctionExpression; parameters=2; async=false; generator=false
- filterOutNotifiedErrorDevices @510-534; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @514-532; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @515-531; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getReq.onsuccess @521-530; FunctionExpression; parameters=0; async=false; generator=false
- getEndToEndSessionsBatch @541-565; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @543-559; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getReq.onsuccess @546-558; FunctionExpression; parameters=0; async=false; generator=false
- deleteEndToEndSessionsBatch @574-591; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @575-590; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @583-585; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getEndToEndInboundGroupSession @595-630; FunctionExpression; parameters=4; async=false; generator=false
- getReq.onsuccess @600-613; FunctionExpression; parameters=0; async=false; generator=false
- withheldGetReq.onsuccess @616-629; FunctionExpression; parameters=0; async=false; generator=false
- getAllEndToEndInboundGroupSessions @631-655; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @634-654; FunctionExpression; parameters=0; async=false; generator=false
- addEndToEndInboundGroupSession @656-674; FunctionExpression; parameters=4; async=false; generator=false
- addReq.onerror @663-673; ArrowFunctionExpression; parameters=1; async=false; generator=false
- storeEndToEndInboundGroupSession @675-682; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSessionWithheld @683-690; FunctionExpression; parameters=4; async=false; generator=false
- countEndToEndInboundGroupSessions @699-709; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @701-707; ArrowFunctionExpression; parameters=1; async=false; generator=false
- countReq.onsuccess @704-706; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getEndToEndInboundGroupSessionsBatch @716-749; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @718-743; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getReq.onsuccess @722-742; FunctionExpression; parameters=0; async=false; generator=false
- backupGetReq.onsuccess @727-737; ArrowFunctionExpression; parameters=0; async=false; generator=false
- deleteEndToEndInboundGroupSessionsBatch @758-775; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @759-774; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @767-769; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getEndToEndDeviceData @776-786; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @779-785; FunctionExpression; parameters=0; async=false; generator=false
- storeEndToEndDeviceData @787-790; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndRoom @791-794; FunctionExpression; parameters=3; async=false; generator=false
- getEndToEndRooms @795-812; FunctionExpression; parameters=2; async=false; generator=false
- getReq.onsuccess @799-811; FunctionExpression; parameters=0; async=false; generator=false
- getSessionsNeedingBackup @816-844; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @817-843; ArrowFunctionExpression; parameters=2; async=false; generator=false
- txn.oncomplete @821-823; FunctionExpression; parameters=0; async=false; generator=false
- getReq.onsuccess @827-842; FunctionExpression; parameters=0; async=false; generator=false
- sessionGetReq.onsuccess @831-837; FunctionExpression; parameters=0; async=false; generator=false
- countSessionsNeedingBackup @845-855; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @850-854; ArrowFunctionExpression; parameters=2; async=false; generator=false
- req.onsuccess @853-853; ArrowFunctionExpression; parameters=0; async=false; generator=false
- unmarkSessionsNeedingBackup @856-868; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @861-867; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @862-866; ArrowFunctionExpression; parameters=2; async=false; generator=false
- markSessionsNeedingBackup @869-884; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @874-883; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @875-882; ArrowFunctionExpression; parameters=2; async=false; generator=false
- addSharedHistoryInboundGroupSession @885-903; FunctionExpression; parameters=4; async=false; generator=false
- req.onsuccess @891-902; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getSharedHistoryInboundGroupSessions @904-921; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @910-920; ArrowFunctionExpression; parameters=2; async=false; generator=false
- req.onsuccess @911-918; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addParkedSharedHistory @922-940; FunctionExpression; parameters=3; async=false; generator=false
- req.onsuccess @928-939; ArrowFunctionExpression; parameters=0; async=false; generator=false
- takeParkedSharedHistory @941-959; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @946-958; ArrowFunctionExpression; parameters=2; async=false; generator=false
- cursorReq.onsuccess @947-956; ArrowFunctionExpression; parameters=0; async=false; generator=false
- doTxn @960-984; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @973-976; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @976-979; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @981-983; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @987-989; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @989-991; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @991-996; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @996-1000; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1000-1002; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1002-1004; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1004-1008; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1008-1012; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1012-1020; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1020-1024; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @1024-1028; ArrowFunctionExpression; parameters=1; async=false; generator=false
- upgradeDatabase @1032-1037; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @1034-1036; ArrowFunctionExpression; parameters=2; async=false; generator=false
- createDatabase @1038-1047; FunctionDeclaration; parameters=1; async=false; generator=false
- abortWithException @1052-1063; FunctionDeclaration; parameters=2; async=false; generator=false
- promiseifyTxn @1064-1089; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @1065-1088; ArrowFunctionExpression; parameters=2; async=false; generator=false
- txn.oncomplete @1066-1071; ArrowFunctionExpression; parameters=0; async=false; generator=false
- txn.onerror @1072-1079; ArrowFunctionExpression; parameters=1; async=false; generator=false
- txn.onabort @1080-1087; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class Backend @38-985

### chat/protocols/matrix/lib/matrix-sdk/crypto/store/indexeddb-crypto-store.js

Blob: `a1da9bcad71e9bcbaa510db8c67eb9bad83e6010`. Role: source. Parse: module.

- _getRequireWildcardCache @14-14; FunctionDeclaration; parameters=1; async=false; generator=false
- _getRequireWildcardCache @14-14; FunctionExpression; parameters=1; async=false; generator=false
- _interopRequireWildcard @15-15; FunctionDeclaration; parameters=2; async=false; generator=false
- _defineProperty @16-16; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @17-17; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- exists @42-44; FunctionExpression; parameters=2; async=false; generator=false
- existsAndIsNotMigrated @50-87; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @51-86; ArrowFunctionExpression; parameters=2; async=false; generator=false
- openDBRequest.onupgradeneeded @54-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openDBRequest.onblocked @59-59; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openDBRequest.onsuccess @60-84; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getReq.onsuccess @75-78; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getReq.onerror @79-81; ArrowFunctionExpression; parameters=0; async=false; generator=false
- openDBRequest.onerror @85-85; ArrowFunctionExpression; parameters=0; async=false; generator=false
- constructor @94-99; FunctionExpression; parameters=2; async=false; generator=false
- containsData @108-110; FunctionExpression; parameters=0; async=true; generator=false
- startup @121-175; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @125-149; ArrowFunctionExpression; parameters=2; async=false; generator=false
- req.onupgradeneeded @132-136; ArrowFunctionExpression; parameters=1; async=false; generator=false
- req.onblocked @137-139; ArrowFunctionExpression; parameters=0; async=false; generator=false
- req.onerror @140-143; ArrowFunctionExpression; parameters=1; async=false; generator=false
- req.onsuccess @144-148; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @149-156; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @153-155; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @154-154; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @155-155; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @156-170; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @170-173; ArrowFunctionExpression; parameters=1; async=false; generator=false
- deleteAllData @182-207; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @183-201; ArrowFunctionExpression; parameters=2; async=false; generator=false
- req.onblocked @190-192; ArrowFunctionExpression; parameters=0; async=false; generator=false
- req.onerror @193-196; ArrowFunctionExpression; parameters=1; async=false; generator=false
- req.onsuccess @197-200; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @201-206; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getMigrationState @216-218; FunctionExpression; parameters=0; async=false; generator=false
- setMigrationState @227-229; FunctionExpression; parameters=1; async=false; generator=false
- getOrAddOutgoingRoomKeyRequest @240-242; FunctionExpression; parameters=1; async=false; generator=false
- getOutgoingRoomKeyRequest @253-255; FunctionExpression; parameters=1; async=false; generator=false
- getOutgoingRoomKeyRequestByState @267-269; FunctionExpression; parameters=1; async=false; generator=false
- getAllOutgoingRoomKeyRequestsByState @277-279; FunctionExpression; parameters=1; async=false; generator=false
- getOutgoingRoomKeyRequestsByTarget @291-293; FunctionExpression; parameters=3; async=false; generator=false
- updateOutgoingRoomKeyRequest @307-309; FunctionExpression; parameters=3; async=false; generator=false
- deleteOutgoingRoomKeyRequest @320-322; FunctionExpression; parameters=2; async=false; generator=false
- getAccount @333-335; FunctionExpression; parameters=2; async=false; generator=false
- storeAccount @344-346; FunctionExpression; parameters=2; async=false; generator=false
- getCrossSigningKeys @356-358; FunctionExpression; parameters=2; async=false; generator=false
- getSecretStorePrivateKey @365-367; FunctionExpression; parameters=3; async=false; generator=false
- storeCrossSigningKeys @375-377; FunctionExpression; parameters=2; async=false; generator=false
- storeSecretStorePrivateKey @386-388; FunctionExpression; parameters=3; async=false; generator=false
- countEndToEndSessions @397-399; FunctionExpression; parameters=2; async=false; generator=false
- getEndToEndSession @413-415; FunctionExpression; parameters=4; async=false; generator=false
- getEndToEndSessions @428-430; FunctionExpression; parameters=3; async=false; generator=false
- getAllEndToEndSessions @439-441; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndSession @450-452; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndSessionProblem @453-455; FunctionExpression; parameters=3; async=false; generator=false
- getEndToEndSessionProblem @456-458; FunctionExpression; parameters=2; async=false; generator=false
- filterOutNotifiedErrorDevices @459-461; FunctionExpression; parameters=1; async=false; generator=false
- countEndToEndInboundGroupSessions @470-472; FunctionExpression; parameters=0; async=false; generator=false
- getEndToEndSessionsBatch @481-483; FunctionExpression; parameters=0; async=false; generator=false
- deleteEndToEndSessionsBatch @492-494; FunctionExpression; parameters=1; async=false; generator=false
- getEndToEndInboundGroupSession @507-509; FunctionExpression; parameters=4; async=false; generator=false
- getAllEndToEndInboundGroupSessions @518-520; FunctionExpression; parameters=2; async=false; generator=false
- addEndToEndInboundGroupSession @531-533; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSession @544-546; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSessionWithheld @547-549; FunctionExpression; parameters=4; async=false; generator=false
- getEndToEndInboundGroupSessionsBatch @558-560; FunctionExpression; parameters=0; async=false; generator=false
- deleteEndToEndInboundGroupSessionsBatch @569-571; FunctionExpression; parameters=1; async=false; generator=false
- storeEndToEndDeviceData @584-586; FunctionExpression; parameters=2; async=false; generator=false
- getEndToEndDeviceData @595-597; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndRoom @607-609; FunctionExpression; parameters=3; async=false; generator=false
- getEndToEndRooms @616-618; FunctionExpression; parameters=2; async=false; generator=false
- getSessionsNeedingBackup @628-630; FunctionExpression; parameters=1; async=false; generator=false
- countSessionsNeedingBackup @637-639; FunctionExpression; parameters=1; async=false; generator=false
- unmarkSessionsNeedingBackup @647-649; FunctionExpression; parameters=2; async=false; generator=false
- markSessionsNeedingBackup @657-659; FunctionExpression; parameters=2; async=false; generator=false
- addSharedHistoryInboundGroupSession @668-670; FunctionExpression; parameters=4; async=false; generator=false
- getSharedHistoryInboundGroupSessions @678-680; FunctionExpression; parameters=2; async=false; generator=false
- addParkedSharedHistory @685-687; FunctionExpression; parameters=3; async=false; generator=false
- takeParkedSharedHistory @692-694; FunctionExpression; parameters=2; async=false; generator=false
- doTxn @718-720; FunctionExpression; parameters=4; async=false; generator=false
- Class IndexedDBCryptoStore @41-721

### chat/protocols/matrix/lib/matrix-sdk/crypto/store/localStorage-crypto-store.js

Blob: `d92952cc877686a82e96469873bb1cdef9b3df2e`. Role: source. Parse: module.

- keyEndToEndSessions @45-47; FunctionDeclaration; parameters=1; async=false; generator=false
- keyEndToEndSessionProblems @48-50; FunctionDeclaration; parameters=1; async=false; generator=false
- keyEndToEndInboundGroupSession @51-53; FunctionDeclaration; parameters=2; async=false; generator=false
- keyEndToEndInboundGroupSessionWithheld @54-56; FunctionDeclaration; parameters=2; async=false; generator=false
- keyEndToEndRoomsPrefix @57-59; FunctionDeclaration; parameters=1; async=false; generator=false
- exists @61-69; FunctionExpression; parameters=1; async=false; generator=false
- constructor @70-73; FunctionExpression; parameters=1; async=false; generator=false
- containsData @82-84; FunctionExpression; parameters=0; async=true; generator=false
- getMigrationState @93-95; FunctionExpression; parameters=0; async=true; generator=false
- setMigrationState @104-106; FunctionExpression; parameters=1; async=true; generator=false
- countEndToEndSessions @110-120; FunctionExpression; parameters=2; async=false; generator=false
- _getEndToEndSessions @123-138; FunctionExpression; parameters=1; async=false; generator=false
- getEndToEndSession @139-142; FunctionExpression; parameters=4; async=false; generator=false
- getEndToEndSessions @143-145; FunctionExpression; parameters=3; async=false; generator=false
- getAllEndToEndSessions @146-155; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndSession @156-160; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndSessionProblem @161-173; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @169-171; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getEndToEndSessionProblem @174-193; FunctionExpression; parameters=2; async=true; generator=false
- filterOutNotifiedErrorDevices @194-216; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndSessionsBatch @225-245; FunctionExpression; parameters=0; async=true; generator=false
- deleteEndToEndSessionsBatch @254-268; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndInboundGroupSession @272-274; FunctionExpression; parameters=4; async=false; generator=false
- getAllEndToEndInboundGroupSessions @275-292; FunctionExpression; parameters=2; async=false; generator=false
- addEndToEndInboundGroupSession @293-298; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSession @299-301; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSessionWithheld @302-304; FunctionExpression; parameters=4; async=false; generator=false
- countEndToEndInboundGroupSessions @313-322; FunctionExpression; parameters=0; async=true; generator=false
- getEndToEndInboundGroupSessionsBatch @331-362; FunctionExpression; parameters=0; async=true; generator=false
- deleteEndToEndInboundGroupSessionsBatch @371-379; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndDeviceData @380-382; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndDeviceData @383-385; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndRoom @386-388; FunctionExpression; parameters=3; async=false; generator=false
- getEndToEndRooms @389-400; FunctionExpression; parameters=2; async=false; generator=false
- getSessionsNeedingBackup @401-422; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @409-415; ArrowFunctionExpression; parameters=1; async=false; generator=false
- countSessionsNeedingBackup @423-426; FunctionExpression; parameters=0; async=false; generator=false
- unmarkSessionsNeedingBackup @427-434; FunctionExpression; parameters=1; async=false; generator=false
- markSessionsNeedingBackup @435-442; FunctionExpression; parameters=1; async=false; generator=false
- deleteAllData @449-452; FunctionExpression; parameters=0; async=false; generator=false
- getAccount @456-459; FunctionExpression; parameters=2; async=false; generator=false
- storeAccount @460-462; FunctionExpression; parameters=2; async=false; generator=false
- getCrossSigningKeys @463-466; FunctionExpression; parameters=2; async=false; generator=false
- getSecretStorePrivateKey @467-470; FunctionExpression; parameters=3; async=false; generator=false
- storeCrossSigningKeys @471-473; FunctionExpression; parameters=2; async=false; generator=false
- storeSecretStorePrivateKey @474-476; FunctionExpression; parameters=3; async=false; generator=false
- doTxn @477-479; FunctionExpression; parameters=3; async=false; generator=false
- getJsonItem @482-492; FunctionDeclaration; parameters=2; async=false; generator=false
- setJsonItem @493-495; FunctionDeclaration; parameters=3; async=false; generator=false
- Class LocalStorageCryptoStore @60-480

### chat/protocols/matrix/lib/matrix-sdk/crypto/store/memory-crypto-store.js

Blob: `f1378da53c0cba870bb44955a5d1a762c178ed99`. Role: source. Parse: module.

- ownKeys @10-10; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @11-11; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @11-11; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @11-11; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @12-12; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @14-14; FunctionDeclaration; parameters=2; async=false; generator=false
- encodeSessionKey @29-31; FunctionDeclaration; parameters=2; async=false; generator=false
- decodeSessionKey @32-40; FunctionDeclaration; parameters=1; async=false; generator=false
- constructor @47-64; FunctionExpression; parameters=0; async=false; generator=false
- containsData @74-77; FunctionExpression; parameters=0; async=true; generator=false
- startup @86-89; FunctionExpression; parameters=0; async=true; generator=false
- deleteAllData @96-98; FunctionExpression; parameters=0; async=false; generator=false
- getMigrationState @107-109; FunctionExpression; parameters=0; async=true; generator=false
- setMigrationState @118-120; FunctionExpression; parameters=1; async=true; generator=false
- getOrAddOutgoingRoomKeyRequest @131-148; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @133-147; ArrowFunctionExpression; parameters=0; async=false; generator=false
- getOutgoingRoomKeyRequest @159-161; FunctionExpression; parameters=1; async=false; generator=false
- _getOutgoingRoomKeyRequest @174-181; FunctionExpression; parameters=1; async=false; generator=false
- getOutgoingRoomKeyRequestByState @192-201; FunctionExpression; parameters=1; async=false; generator=false
- getAllOutgoingRoomKeyRequestsByState @207-209; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @208-208; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getOutgoingRoomKeyRequestsByTarget @210-220; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @214-214; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateOutgoingRoomKeyRequest @234-247; FunctionExpression; parameters=3; async=false; generator=false
- deleteOutgoingRoomKeyRequest @258-272; FunctionExpression; parameters=2; async=false; generator=false
- getAccount @276-278; FunctionExpression; parameters=2; async=false; generator=false
- storeAccount @279-281; FunctionExpression; parameters=2; async=false; generator=false
- getCrossSigningKeys @282-284; FunctionExpression; parameters=2; async=false; generator=false
- getSecretStorePrivateKey @285-288; FunctionExpression; parameters=3; async=false; generator=false
- storeCrossSigningKeys @289-291; FunctionExpression; parameters=2; async=false; generator=false
- storeSecretStorePrivateKey @292-294; FunctionExpression; parameters=3; async=false; generator=false
- countEndToEndSessions @298-304; FunctionExpression; parameters=2; async=false; generator=false
- getEndToEndSession @305-308; FunctionExpression; parameters=4; async=false; generator=false
- getEndToEndSessions @309-311; FunctionExpression; parameters=3; async=false; generator=false
- getAllEndToEndSessions @312-321; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @313-320; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @314-319; ArrowFunctionExpression; parameters=1; async=false; generator=false
- storeEndToEndSession @322-329; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndSessionProblem @330-340; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @337-339; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getEndToEndSessionProblem @341-359; FunctionExpression; parameters=2; async=true; generator=false
- filterOutNotifiedErrorDevices @360-381; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndSessionsBatch @390-407; FunctionExpression; parameters=0; async=true; generator=false
- deleteEndToEndSessionsBatch @416-428; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndInboundGroupSession @432-435; FunctionExpression; parameters=4; async=false; generator=false
- getAllEndToEndInboundGroupSessions @436-443; FunctionExpression; parameters=2; async=false; generator=false
- addEndToEndInboundGroupSession @444-449; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSession @450-453; FunctionExpression; parameters=4; async=false; generator=false
- storeEndToEndInboundGroupSessionWithheld @454-457; FunctionExpression; parameters=4; async=false; generator=false
- countEndToEndInboundGroupSessions @466-468; FunctionExpression; parameters=0; async=true; generator=false
- getEndToEndInboundGroupSessionsBatch @477-495; FunctionExpression; parameters=0; async=true; generator=false
- deleteEndToEndInboundGroupSessionsBatch @504-512; FunctionExpression; parameters=1; async=true; generator=false
- getEndToEndDeviceData @516-518; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndDeviceData @519-521; FunctionExpression; parameters=2; async=false; generator=false
- storeEndToEndRoom @525-527; FunctionExpression; parameters=3; async=false; generator=false
- getEndToEndRooms @528-530; FunctionExpression; parameters=2; async=false; generator=false
- getSessionsNeedingBackup @531-544; FunctionExpression; parameters=1; async=false; generator=false
- countSessionsNeedingBackup @545-547; FunctionExpression; parameters=0; async=false; generator=false
- unmarkSessionsNeedingBackup @548-554; FunctionExpression; parameters=1; async=false; generator=false
- markSessionsNeedingBackup @555-561; FunctionExpression; parameters=1; async=false; generator=false
- addSharedHistoryInboundGroupSession @562-566; FunctionExpression; parameters=3; async=false; generator=false
- getSharedHistoryInboundGroupSessions @567-569; FunctionExpression; parameters=1; async=false; generator=false
- addParkedSharedHistory @570-574; FunctionExpression; parameters=2; async=false; generator=false
- takeParkedSharedHistory @575-579; FunctionExpression; parameters=1; async=false; generator=false
- doTxn @583-585; FunctionExpression; parameters=3; async=false; generator=false
- Class MemoryCryptoStore @46-586

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/Base.js

Blob: `491318cca5f36bc385cd84abb65ae35ac2709d37`. Role: source. Parse: module.

- _defineProperty @15-15; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @16-16; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @17-17; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @37-40; FunctionExpression; parameters=1; async=false; generator=false
- constructor @79-98; FunctionExpression; parameters=6; async=false; generator=false
- initiatedByMe @99-109; FunctionExpression; parameters=0; async=false; generator=false
- hasBeenCancelled @110-112; FunctionExpression; parameters=0; async=false; generator=false
- resetTimer @113-124; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @118-123; ArrowFunctionExpression; parameters=0; async=false; generator=false
- endTimer @125-130; FunctionExpression; parameters=0; async=false; generator=false
- send @131-133; FunctionExpression; parameters=2; async=false; generator=false
- waitForEvent @134-147; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @143-146; ArrowFunctionExpression; parameters=2; async=false; generator=false
- canSwitchStartEvent @148-150; FunctionExpression; parameters=1; async=false; generator=false
- switchStartEvent @151-164; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @165-203; FunctionExpression; parameters=1; async=false; generator=false
- done @204-211; FunctionExpression; parameters=0; async=true; generator=false
- cancel @212-258; FunctionExpression; parameters=1; async=false; generator=false
- verify @266-292; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @268-279; ArrowFunctionExpression; parameters=2; async=false; generator=false
- ?.resolve @269-273; ArrowFunctionExpression; parameters=1; async=false; generator=false
- ?.reject @274-278; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @283-289; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @289-289; ArrowFunctionExpression; parameters=0; async=false; generator=false
- verifyKeys @293-340; FunctionExpression; parameters=3; async=true; generator=false
- events @341-343; FunctionExpression; parameters=0; async=false; generator=false
- getShowSasCallbacks @351-353; FunctionExpression; parameters=0; async=false; generator=false
- getReciprocateQrCodeCallbacks @361-363; FunctionExpression; parameters=0; async=false; generator=false
- Class VerificationBase @53-364
- Class SwitchStartEventError @36-41

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/Error.js

Blob: `b96ccd4afb7f0bfe129f22dcea698df90b39cde9`. Role: source. Parse: module.

- newVerificationError @32-41; FunctionDeclaration; parameters=3; async=false; generator=false
- errorFactory @42-46; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @43-45; FunctionExpression; parameters=1; async=false; generator=false
- errorFromEvent @77-94; FunctionDeclaration; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/IllegalMethod.js

Blob: `46911b9b0b6e40718b41c0a45df4c986ae6fecc1`. Role: source. Parse: module.

- _defineProperty @8-8; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @9-9; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @10-10; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @29-34; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @31-33; ArrowFunctionExpression; parameters=0; async=true; generator=false
- factory @35-37; FunctionExpression; parameters=6; async=false; generator=false
- NAME @40-44; FunctionExpression; parameters=0; async=false; generator=false
- Class IllegalMethod @28-45

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/QRCode.js

Blob: `39f7a0382db8c05050fbe550bf6d83b7392f8f20`. Role: source. Parse: module.

- _defineProperty @13-13; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @14-14; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @15-15; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @42-111; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @45-110; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @59-65; ArrowFunctionExpression; parameters=2; async=false; generator=false
- cancel @62-62; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @92-109; ArrowFunctionExpression; parameters=3; async=false; generator=false
- factory @112-114; FunctionExpression; parameters=6; async=false; generator=false
- NAME @117-119; FunctionExpression; parameters=0; async=false; generator=false
- getReciprocateQrCodeCallbacks @120-122; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-132; FunctionExpression; parameters=1; async=false; generator=false
- constructor @134-147; FunctionExpression; parameters=6; async=false; generator=false
- create @148-167; FunctionExpression; parameters=2; async=true; generator=false
- encodedSharedSecret @172-174; FunctionExpression; parameters=0; async=false; generator=false
- getBuffer @175-177; FunctionExpression; parameters=0; async=false; generator=false
- generateSharedSecret @178-182; FunctionExpression; parameters=0; async=false; generator=false
- getOtherDeviceKey @183-191; FunctionExpression; parameters=2; async=true; generator=false
- determineMode @192-206; FunctionExpression; parameters=2; async=false; generator=false
- generateQrData @207-238; FunctionExpression; parameters=7; async=false; generator=false
- generateBuffer @239-271; FunctionExpression; parameters=1; async=false; generator=false
- appendByte @242-245; ArrowFunctionExpression; parameters=1; async=false; generator=false
- appendInt @246-250; ArrowFunctionExpression; parameters=1; async=false; generator=false
- appendStr @251-255; ArrowFunctionExpression; parameters=3; async=false; generator=false
- appendEncBase64 @256-260; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class QRCodeData @133-272
- Class ReciprocateQRCode @41-123

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/SAS.js

Blob: `5ac28a248883a3657a9b3013e0b68abf5a92e0ae`. Role: source. Parse: module.

- _interopRequireDefault @15-15; FunctionDeclaration; parameters=1; async=false; generator=false
- _defineProperty @16-16; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @17-17; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- generateEmojiSas @176-181; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @180-180; ArrowFunctionExpression; parameters=1; async=false; generator=false
- generateSas @186-195; FunctionDeclaration; parameters=2; async=false; generator=false
- calculateMAC @202-208; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @203-207; FunctionExpression; parameters=2; async=false; generator=false
- curve25519-hkdf-sha256 @211-216; FunctionExpression; parameters=3; async=false; generator=false
- curve25519 @217-222; FunctionExpression; parameters=3; async=false; generator=false
- intersection @236-238; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @237-237; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @247-278; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @253-277; ArrowFunctionExpression; parameters=0; async=true; generator=false
- NAME @280-282; FunctionExpression; parameters=0; async=false; generator=false
- events @283-285; FunctionExpression; parameters=0; async=false; generator=false
- canSwitchStartEvent @286-292; FunctionExpression; parameters=1; async=false; generator=false
- sendStart @293-305; FunctionExpression; parameters=0; async=true; generator=false
- verifyAndCheckMAC @306-333; FunctionExpression; parameters=4; async=true; generator=false
- (anonymous) @308-323; ArrowFunctionExpression; parameters=2; async=false; generator=false
- confirm @311-318; ArrowFunctionExpression; parameters=0; async=true; generator=false
- cancel @319-319; ArrowFunctionExpression; parameters=0; async=false; generator=false
- mismatch @320-320; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @324-330; ArrowFunctionExpression; parameters=1; async=false; generator=false
- doSendVerification @334-387; FunctionExpression; parameters=0; async=true; generator=false
- doRespondVerification @388-429; FunctionExpression; parameters=0; async=true; generator=false
- sendMAC @430-448; FunctionExpression; parameters=2; async=false; generator=false
- checkMAC @449-459; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @454-458; ArrowFunctionExpression; parameters=3; async=false; generator=false
- getShowSasCallbacks @460-462; FunctionExpression; parameters=0; async=false; generator=false
- Class SAS @246-463

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/SASDecimal.js

Blob: `7cd8fb2505add12ff3d0581fe39131234c20cd14`. Role: source. Parse: module.

- generateDecimalSas @29-39; FunctionDeclaration; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/Channel.js

Blob: `430afc16cdfa1c471b1b89abcb059363dd193d64`. Role: source. Parse: module.


### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/InRoomChannel.js

Blob: `d3826f93f34d6182bdcc8a5db4e0c580d4d104d2`. Role: source. Parse: module.

- _defineProperty @10-10; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @11-11; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @12-12; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @42-47; FunctionExpression; parameters=3; async=false; generator=false
- receiveStartFromOtherDevices @48-50; FunctionExpression; parameters=0; async=false; generator=false
- transactionId @53-55; FunctionExpression; parameters=0; async=false; generator=false
- getOtherPartyUserId @56-70; FunctionExpression; parameters=2; async=false; generator=false
- getTimestamp @76-78; FunctionExpression; parameters=1; async=false; generator=false
- canCreateRequest @85-87; FunctionExpression; parameters=1; async=false; generator=false
- canCreateRequest @88-90; FunctionExpression; parameters=1; async=false; generator=false
- getTransactionId @97-106; FunctionExpression; parameters=1; async=false; generator=false
- validateEvent @117-140; FunctionExpression; parameters=2; async=false; generator=false
- getEventType @149-167; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @176-218; FunctionExpression; parameters=3; async=true; generator=false
- completedContentFromEvent @228-234; FunctionExpression; parameters=1; async=false; generator=false
- completeContent @245-266; FunctionExpression; parameters=2; async=false; generator=false
- send @274-277; FunctionExpression; parameters=2; async=false; generator=false
- sendCompleted @284-293; FunctionExpression; parameters=2; async=true; generator=false
- constructor @297-299; FunctionExpression; parameters=0; async=false; generator=false
- getRequest @300-304; FunctionExpression; parameters=1; async=false; generator=false
- getRequestByChannel @305-307; FunctionExpression; parameters=1; async=false; generator=false
- getRequestByTxnId @308-313; FunctionExpression; parameters=2; async=false; generator=false
- setRequest @314-316; FunctionExpression; parameters=2; async=false; generator=false
- setRequestByChannel @317-319; FunctionExpression; parameters=2; async=false; generator=false
- doSetRequest @320-327; FunctionExpression; parameters=3; async=false; generator=false
- removeRequest @328-337; FunctionExpression; parameters=1; async=false; generator=false
- findRequestInProgress @338-347; FunctionExpression; parameters=2; async=false; generator=false
- Class InRoomRequests @296-348
- Class InRoomChannel @36-294

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/ToDeviceChannel.js

Blob: `520a0d2a70c0c39ed934b328d569a1981404a93e`. Role: source. Parse: module.

- _defineProperty @12-12; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @14-14; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @36-43; FunctionExpression; parameters=5; async=false; generator=false
- isToDevices @44-55; FunctionExpression; parameters=1; async=false; generator=false
- getEventType @56-58; FunctionExpression; parameters=1; async=false; generator=false
- getTransactionId @65-68; FunctionExpression; parameters=1; async=false; generator=false
- canCreateRequest @75-77; FunctionExpression; parameters=1; async=false; generator=false
- canCreateRequest @78-80; FunctionExpression; parameters=1; async=false; generator=false
- validateEvent @91-119; FunctionExpression; parameters=2; async=false; generator=false
- getTimestamp @125-128; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @137-173; FunctionExpression; parameters=3; async=true; generator=false
- (anonymous) @164-164; ArrowFunctionExpression; parameters=1; async=false; generator=false
- completedContentFromEvent @180-182; FunctionExpression; parameters=1; async=false; generator=false
- completeContent @193-206; FunctionExpression; parameters=2; async=false; generator=false
- send @214-221; FunctionExpression; parameters=2; async=false; generator=false
- sendCompleted @228-244; FunctionExpression; parameters=2; async=true; generator=false
- sendToDevices @245-253; FunctionExpression; parameters=3; async=true; generator=false
- makeTransactionId @259-261; FunctionExpression; parameters=0; async=false; generator=false
- constructor @265-267; FunctionExpression; parameters=0; async=false; generator=false
- getRequest @268-270; FunctionExpression; parameters=1; async=false; generator=false
- getRequestByChannel @271-273; FunctionExpression; parameters=1; async=false; generator=false
- getRequestBySenderAndTxnId @274-279; FunctionExpression; parameters=2; async=false; generator=false
- setRequest @280-282; FunctionExpression; parameters=2; async=false; generator=false
- setRequestByChannel @283-285; FunctionExpression; parameters=2; async=false; generator=false
- setRequestBySenderAndTxnId @286-293; FunctionExpression; parameters=3; async=false; generator=false
- removeRequest @294-303; FunctionExpression; parameters=1; async=false; generator=false
- findRequestInProgress @304-313; FunctionExpression; parameters=2; async=false; generator=false
- getRequestsInProgress @314-320; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @317-317; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class ToDeviceRequests @264-321
- Class ToDeviceChannel @34-262

### chat/protocols/matrix/lib/matrix-sdk/crypto/verification/request/VerificationRequest.js

Blob: `e3dddb76aba082dd6772095a16e4db86c73fcfcc`. Role: source. Parse: module.

- get @9-11; FunctionExpression; parameters=0; async=false; generator=false
- get @16-18; FunctionExpression; parameters=0; async=false; generator=false
- _defineProperty @26-26; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @27-27; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @28-28; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @77-122; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @103-119; ArrowFunctionExpression; parameters=0; async=true; generator=false
- validateEvent @132-157; FunctionExpression; parameters=3; async=false; generator=false
- transactionId @164-166; FunctionExpression; parameters=0; async=false; generator=false
- roomId @171-173; FunctionExpression; parameters=0; async=false; generator=false
- invalid @174-176; FunctionExpression; parameters=0; async=false; generator=false
- requested @179-181; FunctionExpression; parameters=0; async=false; generator=false
- cancelled @184-186; FunctionExpression; parameters=0; async=false; generator=false
- ready @189-191; FunctionExpression; parameters=0; async=false; generator=false
- started @194-196; FunctionExpression; parameters=0; async=false; generator=false
- done @199-201; FunctionExpression; parameters=0; async=false; generator=false
- methods @204-206; FunctionExpression; parameters=0; async=false; generator=false
- chosenMethod @209-211; FunctionExpression; parameters=0; async=false; generator=false
- calculateEventTimeout @212-219; FunctionExpression; parameters=1; async=false; generator=false
- timeout @222-228; FunctionExpression; parameters=0; async=false; generator=false
- requestEvent @234-236; FunctionExpression; parameters=0; async=false; generator=false
- phase @239-241; FunctionExpression; parameters=0; async=false; generator=false
- verifier @244-246; FunctionExpression; parameters=0; async=false; generator=false
- canAccept @247-249; FunctionExpression; parameters=0; async=false; generator=false
- accepting @250-252; FunctionExpression; parameters=0; async=false; generator=false
- declining @253-255; FunctionExpression; parameters=0; async=false; generator=false
- pending @258-260; FunctionExpression; parameters=0; async=false; generator=false
- qrCodeData @266-268; FunctionExpression; parameters=0; async=false; generator=false
- getQRCodeBytes @277-279; FunctionExpression; parameters=0; async=false; generator=false
- generateQRCode @287-289; FunctionExpression; parameters=0; async=true; generator=false
- otherPartySupportsMethod @298-326; FunctionExpression; parameters=2; async=false; generator=false
- initiatedByMe @332-352; FunctionExpression; parameters=0; async=false; generator=false
- requestingUserId @355-361; FunctionExpression; parameters=0; async=false; generator=false
- receivingUserId @364-370; FunctionExpression; parameters=0; async=false; generator=false
- otherUserId @373-375; FunctionExpression; parameters=0; async=false; generator=false
- otherDeviceId @378-380; FunctionExpression; parameters=0; async=false; generator=false
- isSelfVerification @381-383; FunctionExpression; parameters=0; async=false; generator=false
- cancellingUserId @389-399; FunctionExpression; parameters=0; async=false; generator=false
- cancellationCode @404-407; FunctionExpression; parameters=0; async=false; generator=false
- observeOnly @408-410; FunctionExpression; parameters=0; async=false; generator=false
- targetDevice @419-427; FunctionExpression; parameters=0; async=false; generator=false
- beginKeyVerification @436-454; FunctionExpression; parameters=2; async=false; generator=false
- startVerification @455-460; FunctionExpression; parameters=1; async=true; generator=false
- scanQRCode @461-463; FunctionExpression; parameters=1; async=false; generator=false
- sendRequest @469-476; FunctionExpression; parameters=0; async=true; generator=false
- cancel @485-502; FunctionExpression; parameters=1; async=true; generator=false
- accept @508-517; FunctionExpression; parameters=0; async=true; generator=false
- waitFor @526-546; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @527-545; ArrowFunctionExpression; parameters=2; async=false; generator=false
- check @528-541; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setPhase @547-552; FunctionExpression; parameters=2; async=false; generator=false
- getEventByEither @553-555; FunctionExpression; parameters=1; async=false; generator=false
- getEventBy @556-562; FunctionExpression; parameters=2; async=false; generator=false
- calculatePhaseTransitions @563-623; FunctionExpression; parameters=0; async=false; generator=false
- phase @567-567; ArrowFunctionExpression; parameters=0; async=false; generator=false
- transitionToPhase @624-662; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @633-633; ArrowFunctionExpression; parameters=1; async=false; generator=false
- applyPhaseTransitions @663-673; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @665-665; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isWinningStartRace @674-706; FunctionExpression; parameters=1; async=false; generator=false
- hasEventId @707-719; FunctionExpression; parameters=1; async=false; generator=false
- handleEvent @731-798; FunctionExpression; parameters=5; async=true; generator=false
- (anonymous) @778-778; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setupTimeout @799-811; FunctionExpression; parameters=1; async=false; generator=false
- cancelOnError @812-836; FunctionExpression; parameters=2; async=true; generator=false
- adjustObserveOnly @837-845; FunctionExpression; parameters=2; async=false; generator=false
- addEvent @846-864; FunctionExpression; parameters=3; async=false; generator=false
- createVerifier @865-879; FunctionExpression; parameters=3; async=false; generator=false
- wasSentByOwnUser @880-882; FunctionExpression; parameters=1; async=false; generator=false
- wasSentByOwnDevice @885-894; FunctionExpression; parameters=1; async=false; generator=false
- onVerifierCancelled @895-902; FunctionExpression; parameters=0; async=false; generator=false
- onVerifierFinished @903-911; FunctionExpression; parameters=0; async=false; generator=false
- getEventFromOtherParty @912-914; FunctionExpression; parameters=1; async=false; generator=false
- Class VerificationRequest @76-915

### chat/protocols/matrix/lib/matrix-sdk/digest.js

Blob: `6836bb2f9d2f9d3a3f41b61ad9f9d8aaf03fd68f`. Role: source. Parse: module.

- sha256 @31-38; FunctionDeclaration; parameters=1; async=true; generator=false

### chat/protocols/matrix/lib/matrix-sdk/embedded.js

Blob: `b1368b5f294d953438deff7c04bb18a1dd3bab3a`. Role: source. Parse: module.

- ownKeys @16-16; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @16-16; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @17-17; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @17-17; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @18-18; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @19-19; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @20-20; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @51-141; FunctionExpression; parameters=5; async=false; generator=false
- (anonymous) @60-79; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @80-92; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @93-93; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @99-99; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @100-100; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @104-104; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @109-109; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @111-114; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @115-118; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @119-119; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @120-120; ArrowFunctionExpression; parameters=1; async=false; generator=false
- startClient @142-191; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @167-178; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @172-172; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @174-177; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @180-182; ArrowFunctionExpression; parameters=0; async=false; generator=false
- stopClient @192-197; FunctionExpression; parameters=0; async=false; generator=false
- joinRoom @198-201; FunctionExpression; parameters=1; async=true; generator=false
- encryptAndSendEvent @202-227; FunctionExpression; parameters=3; async=true; generator=false
- sendStateEvent @228-236; FunctionExpression; parameters=4; async=true; generator=false
- _unstable_sendDelayedStateEvent @242-248; FunctionExpression; parameters=5; async=true; generator=false
- validateSendDelayedEventResponse @249-256; FunctionExpression; parameters=1; async=false; generator=false
- _unstable_updateDelayedEvent @262-267; FunctionExpression; parameters=2; async=true; generator=false
- sendToDevice @268-271; FunctionExpression; parameters=2; async=true; generator=false
- getOpenIdToken @272-282; FunctionExpression; parameters=0; async=true; generator=false
- queueToDevice @283-297; FunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @288-288; ArrowFunctionExpression; parameters=0; async=false; generator=false
- encryptAndSendToDevices @298-310; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @300-300; ArrowFunctionExpression; parameters=0; async=false; generator=false
- checkTurnServers @314-316; FunctionExpression; parameters=0; async=true; generator=false
- getSyncState @319-321; FunctionExpression; parameters=0; async=false; generator=false
- setSyncState @322-326; FunctionExpression; parameters=1; async=false; generator=false
- ack @327-329; FunctionExpression; parameters=1; async=true; generator=false
- watchTurnServers @330-351; FunctionExpression; parameters=0; async=true; generator=false
- onClientStopped @332-334; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class RoomWidgetClient @40-352

### chat/protocols/matrix/lib/matrix-sdk/errors.js

Blob: `60a35699e5e0ecece41db9ad039f30dafea4f5ad`. Role: source. Parse: module.

- _defineProperty @7-7; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @8-8; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @25-28; FunctionExpression; parameters=1; async=false; generator=false
- constructor @30-35; FunctionExpression; parameters=1; async=false; generator=false
- constructor @40-43; FunctionExpression; parameters=2; async=false; generator=false
- constructor @56-58; FunctionExpression; parameters=0; async=false; generator=false
- Class ClientStoppedError @55-59
- Class KeySignatureUploadError @39-44
- Class InvalidCryptoStoreError @29-36

### chat/protocols/matrix/lib/matrix-sdk/event-mapper.js

Blob: `b8084e11c287603b101186476055942181d9cc60`. Role: source. Parse: module.

- ownKeys @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9-9; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @10-10; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @11-11; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @12-12; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @13-13; FunctionDeclaration; parameters=2; async=false; generator=false
- eventMapperFor @28-86; FunctionDeclaration; parameters=2; async=false; generator=false
- mapper @31-84; FunctionDeclaration; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/ExtensibleEvent.js

Blob: `c3578ffc357320b6c46e3b3a180055d11dfa383b`. Role: source. Parse: module.

- constructor @27-29; FunctionExpression; parameters=1; async=false; generator=false
- wireContent @34-36; FunctionExpression; parameters=0; async=false; generator=false
- Class ExtensibleEvent @26-62

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/InvalidEventError.js

Blob: `2136849a23f35cb3acaaf625ca2a389cf0982b2f`. Role: source. Parse: module.

- constructor @27-29; FunctionExpression; parameters=1; async=false; generator=false
- Class InvalidEventError @26-30

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/MessageEvent.js

Blob: `48361727b02b544190e732a0d37c9597973bd539`. Role: source. Parse: module.

- ownKeys @11-11; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @11-11; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @12-12; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @13-13; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @14-14; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @15-15; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @44-90; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @68-68; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @69-69; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isEquivalentTo @91-93; FunctionExpression; parameters=1; async=false; generator=false
- serializeMMessageOnly @94-109; FunctionExpression; parameters=0; async=false; generator=false
- serialize @110-120; FunctionExpression; parameters=0; async=false; generator=false
- from @128-136; FunctionExpression; parameters=2; async=false; generator=false
- Class MessageEvent @37-137

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollEndEvent.js

Blob: `71b25bfedff4bec781ac36793acf0c4ef313f86d`. Role: source. Parse: module.

- ownKeys @12-12; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @14-14; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @15-15; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @16-16; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @40-56; FunctionExpression; parameters=1; async=false; generator=false
- isEquivalentTo @57-59; FunctionExpression; parameters=1; async=false; generator=false
- serialize @60-71; FunctionExpression; parameters=0; async=false; generator=false
- from @79-91; FunctionExpression; parameters=2; async=false; generator=false
- Class PollEndEvent @34-92

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollResponseEvent.js

Blob: `3f18b8ae1628f5fbf46f5c91e0ea72e0912b9ddb`. Role: source. Parse: module.

- _defineProperty @11-11; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @12-12; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @13-13; FunctionDeclaration; parameters=2; async=false; generator=false
- answerIds @36-38; FunctionExpression; parameters=0; async=false; generator=false
- spoiled @47-49; FunctionExpression; parameters=0; async=false; generator=false
- constructor @58-69; FunctionExpression; parameters=1; async=false; generator=false
- validateAgainst @76-99; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @84-84; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @90-90; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isEquivalentTo @100-102; FunctionExpression; parameters=1; async=false; generator=false
- serialize @103-116; FunctionExpression; parameters=0; async=false; generator=false
- from @125-138; FunctionExpression; parameters=2; async=false; generator=false
- Class PollResponseEvent @31-139

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/PollStartEvent.js

Blob: `2d8f77c285843da2a2c8b0e0eb02a22ae0192c4f`. Role: source. Parse: module.

- ownKeys @13-13; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @14-14; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @14-14; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @14-14; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @15-15; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @16-16; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @17-17; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @38-49; FunctionExpression; parameters=1; async=false; generator=false
- serialize @50-57; FunctionExpression; parameters=0; async=false; generator=false
- from @65-73; FunctionExpression; parameters=2; async=false; generator=false
- constructor @86-138; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @130-133; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isEquivalentTo @139-141; FunctionExpression; parameters=1; async=false; generator=false
- serialize @142-155; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @150-150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @152-152; ArrowFunctionExpression; parameters=2; async=false; generator=false
- from @165-184; FunctionExpression; parameters=4; async=false; generator=false
- (anonymous) @177-180; ArrowFunctionExpression; parameters=1; async=false; generator=false
- makeId @188-190; FunctionDeclaration; parameters=0; async=false; generator=false
- (anonymous) @189-189; ArrowFunctionExpression; parameters=0; async=false; generator=false
- Class PollStartEvent @80-185
- Class PollAnswerSubevent @37-74

### chat/protocols/matrix/lib/matrix-sdk/extensible_events_v1/utilities.js

Blob: `62e02febd7063dc648daa6eeed5111a437e7ac3b`. Role: source. Parse: module.

- isProvided @29-31; FunctionDeclaration; parameters=1; async=false; generator=false
- isOptionalAString @38-40; FunctionDeclaration; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/feature.js

Blob: `4a0f45b1265c18f98579c2825b887bcbc9c35e2f`. Role: source. Parse: module.

- (anonymous) @23-28; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @29-38; FunctionExpression; parameters=1; async=false; generator=false
- buildFeatureSupportMap @65-81; FunctionDeclaration; parameters=1; async=true; generator=false
- (anonymous) @69-71; ArrowFunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/filter-component.js

Blob: `a28fa07e0c28b0205b452d21ab262820b464cf75`. Role: source. Parse: module.

- matchesWildcard @31-38; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @53-56; FunctionExpression; parameters=2; async=false; generator=false
- check @63-76; FunctionExpression; parameters=1; async=false; generator=false
- toJSON @81-93; FunctionExpression; parameters=0; async=false; generator=false
- checkFields @105-146; FunctionExpression; parameters=6; async=false; generator=false
- rooms @107-109; FunctionExpression; parameters=1; async=false; generator=false
- senders @110-112; FunctionExpression; parameters=1; async=false; generator=false
- types @113-115; FunctionExpression; parameters=1; async=false; generator=false
- arrayMatchesFilter @147-151; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @148-150; ArrowFunctionExpression; parameters=1; async=false; generator=false
- filter @158-160; FunctionExpression; parameters=1; async=false; generator=false
- limit @167-169; FunctionExpression; parameters=0; async=false; generator=false
- Class FilterComponent @52-170

### chat/protocols/matrix/lib/matrix-sdk/filter.js

Blob: `c76e22560e605e1776fa8b533154a1ce27d78321`. Role: source. Parse: module.

- ownKeys @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9-9; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @10-10; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @11-11; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @12-12; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @13-13; FunctionDeclaration; parameters=2; async=false; generator=false
- setProp @30-40; FunctionDeclaration; parameters=3; async=false; generator=false
- fromJson @50-54; FunctionExpression; parameters=3; async=false; generator=false
- constructor @60-66; FunctionExpression; parameters=2; async=false; generator=false
- getFilterId @72-74; FunctionExpression; parameters=0; async=false; generator=false
- getDefinition @80-82; FunctionExpression; parameters=0; async=false; generator=false
- setDefinition @88-150; FunctionExpression; parameters=1; async=false; generator=false
- getRoomTimelineFilterComponent @156-158; FunctionExpression; parameters=0; async=false; generator=false
- filterRoomTimeline @166-174; FunctionExpression; parameters=1; async=false; generator=false
- setTimelineLimit @180-182; FunctionExpression; parameters=1; async=false; generator=false
- setUnreadThreadNotifications @187-195; FunctionExpression; parameters=1; async=false; generator=false
- setLazyLoadMembers @196-198; FunctionExpression; parameters=1; async=false; generator=false
- setIncludeLeaveRooms @205-207; FunctionExpression; parameters=1; async=false; generator=false
- Class Filter @46-208

### chat/protocols/matrix/lib/matrix-sdk/http-api/errors.js

Blob: `6478c28afe238d53f1be7de78aeb593da51c34f3`. Role: source. Parse: module.

- _defineProperty @7-7; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @8-8; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @33-36; FunctionExpression; parameters=2; async=false; generator=false
- constructor @46-65; FunctionExpression; parameters=4; async=false; generator=false
- constructor @76-78; FunctionExpression; parameters=2; async=false; generator=false
- name @79-81; FunctionExpression; parameters=0; async=false; generator=false
- Class ConnectionError @75-82
- Class MatrixError @39-66
- Class HTTPError @32-37

### chat/protocols/matrix/lib/matrix-sdk/http-api/fetch.js

Blob: `979ebc8b96b630df56b73c5f13da48c17981b20d`. Role: source. Parse: module.

- ownKeys @12-12; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @12-12; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @13-13; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @14-14; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @15-15; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @16-16; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @34-41; FunctionExpression; parameters=2; async=false; generator=false
- abort @42-45; FunctionExpression; parameters=0; async=false; generator=false
- fetch @46-51; FunctionExpression; parameters=2; async=false; generator=false
- setIdBaseUrl @57-59; FunctionExpression; parameters=1; async=false; generator=false
- idServerRequest @60-80; FunctionExpression; parameters=5; async=false; generator=false
- authedRequest @109-151; FunctionExpression; parameters=5; async=true; generator=false
- tryRefreshToken @158-175; FunctionExpression; parameters=0; async=true; generator=false
- request @203-206; FunctionExpression; parameters=5; async=false; generator=false
- requestOtherUrl @222-291; FunctionExpression; parameters=4; async=true; generator=false
- sanitizeUrlForLogs @292-312; FunctionExpression; parameters=1; async=false; generator=false
- getUrl @321-329; FunctionExpression; parameters=4; async=false; generator=false
- Class FetchHttpApi @33-330

### chat/protocols/matrix/lib/matrix-sdk/http-api/index.js

Blob: `7b41a9436bfc30b7e518648620bbeca914da26d3`. Role: source. Parse: module.

- (anonymous) @12-22; FunctionExpression; parameters=1; async=false; generator=false
- get @18-20; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @26-36; FunctionExpression; parameters=1; async=false; generator=false
- get @32-34; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @38-48; FunctionExpression; parameters=1; async=false; generator=false
- get @44-46; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @50-60; FunctionExpression; parameters=1; async=false; generator=false
- get @56-58; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @62-72; FunctionExpression; parameters=1; async=false; generator=false
- get @68-70; FunctionExpression; parameters=0; async=false; generator=false
- _getRequireWildcardCache @73-73; FunctionDeclaration; parameters=1; async=false; generator=false
- _getRequireWildcardCache @73-73; FunctionExpression; parameters=1; async=false; generator=false
- _interopRequireWildcard @74-74; FunctionDeclaration; parameters=2; async=false; generator=false
- _defineProperty @75-75; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @76-76; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @77-77; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @93-96; FunctionExpression; parameters=1; async=false; generator=false
- uploadContent @110-211; FunctionExpression; parameters=2; async=false; generator=false
- timeoutFn @125-128; FunctionExpression; parameters=0; async=false; generator=false
- xhr.onreadystatechange @132-157; FunctionExpression; parameters=0; async=false; generator=false
- xhr.upload.onprogress @158-167; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @181-183; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @196-198; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @202-204; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @203-203; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @205-208; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @206-206; ArrowFunctionExpression; parameters=1; async=false; generator=false
- cancelUpload @212-219; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @213-213; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getCurrentUploads @220-222; FunctionExpression; parameters=0; async=false; generator=false
- getContentUri @229-237; FunctionExpression; parameters=0; async=false; generator=false
- Class MatrixHttpApi @92-238

### chat/protocols/matrix/lib/matrix-sdk/http-api/interface.js

Blob: `2d155bce087ac140d8fcf376c680250bf5c434e2`. Role: source. Parse: module.

- (anonymous) @33-37; FunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/http-api/method.js

Blob: `4725d87f2823abbd82b6867b933be731e607f7b3`. Role: source. Parse: module.

- (anonymous) @22-31; FunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/http-api/prefix.js

Blob: `f85ed3c368a426a1e969d6a8d0fc3f596641e22b`. Role: source. Parse: module.

- (anonymous) @22-27; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @28-31; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @32-36; FunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/http-api/utils.js

Blob: `56a582928a5c65e924a3c712497402c039825bc4`. Role: source. Parse: module.

- timeoutSignal @32-38; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @34-36; ArrowFunctionExpression; parameters=0; async=false; generator=false
- anySignal @39-61; FunctionDeclaration; parameters=1; async=false; generator=false
- cleanup @41-45; FunctionDeclaration; parameters=0; async=false; generator=false
- onAbort @46-49; FunctionDeclaration; parameters=0; async=false; generator=false
- parseErrorResponse @73-87; FunctionDeclaration; parameters=2; async=false; generator=false
- isXhr @88-90; FunctionDeclaration; parameters=1; async=false; generator=false
- getResponseContentType @101-114; FunctionDeclaration; parameters=1; async=false; generator=false
- retryNetworkOperation @123-144; FunctionDeclaration; parameters=2; async=true; generator=false
- calculateRetryBackoff @157-185; FunctionDeclaration; parameters=3; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/index.js

Blob: `690474dcc1f35d75898e3b4a940d799961409a78`. Role: source. Parse: module.

- (anonymous) @9-19; FunctionExpression; parameters=1; async=false; generator=false
- get @15-17; FunctionExpression; parameters=0; async=false; generator=false
- _getRequireWildcardCache @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- _getRequireWildcardCache @20-20; FunctionExpression; parameters=1; async=false; generator=false
- _interopRequireWildcard @21-21; FunctionDeclaration; parameters=2; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/indexeddb-helpers.js

Blob: `1fa33bee4e74daa3709dbe97e83c5d54c919f52d`. Role: source. Parse: module.

- exists @31-56; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @32-55; ArrowFunctionExpression; parameters=2; async=false; generator=false
- req.onupgradeneeded @35-39; ArrowFunctionExpression; parameters=0; async=false; generator=false
- req.onblocked @40-40; ArrowFunctionExpression; parameters=0; async=false; generator=false
- req.onsuccess @41-53; ArrowFunctionExpression; parameters=0; async=false; generator=false
- req.onerror @54-54; ArrowFunctionExpression; parameters=0; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/indexeddb-worker.js

Blob: `1ea6d36c9b73b0f1361979f26bf281b4b2080cef`. Role: source. Parse: module.

- get @8-10; FunctionExpression; parameters=0; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/interactive-auth.js

Blob: `fc3a3b663b87f82791f354d83642659187c4818d`. Role: source. Parse: module.

- _defineProperty @10-10; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @11-11; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @12-12; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @37-49; FunctionExpression; parameters=1; async=false; generator=false
- constructor @65-72; FunctionExpression; parameters=3; async=false; generator=false
- constructor @101-157; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @124-142; ArrowFunctionExpression; parameters=0; async=true; generator=false
- attemptAuth @166-187; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @180-182; ArrowFunctionExpression; parameters=0; async=false; generator=false
- poll @194-221; FunctionExpression; parameters=0; async=true; generator=false
- getSessionId @228-230; FunctionExpression; parameters=0; async=false; generator=false
- getClientSecret @238-240; FunctionExpression; parameters=0; async=false; generator=false
- getStageParams @248-250; FunctionExpression; parameters=1; async=false; generator=false
- getChosenFlow @251-253; FunctionExpression; parameters=0; async=false; generator=false
- submitAuthDict @267-307; FunctionExpression; parameters=2; async=true; generator=false
- getEmailSid @315-317; FunctionExpression; parameters=0; async=false; generator=false
- setEmailSid @327-329; FunctionExpression; parameters=1; async=false; generator=false
- doRequest @341-407; FunctionExpression; parameters=2; async=true; generator=false
- startNextAuthStage @415-437; FunctionExpression; parameters=0; async=false; generator=false
- chooseStage @446-454; FunctionExpression; parameters=0; async=false; generator=false
- scoreFlow @458-465; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @462-462; ArrowFunctionExpression; parameters=1; async=false; generator=false
- chooseFlow @482-512; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @491-491; ArrowFunctionExpression; parameters=2; async=false; generator=false
- firstUncompletedStage @520-523; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @522-522; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class InteractiveAuth @100-524
- Class NoAuthFlowFoundError @64-73

### chat/protocols/matrix/lib/matrix-sdk/logger.js

Blob: `efdacad28b91306893cd066d5b914a1af3b7ac6f`. Role: source. Parse: module.

- _interopRequireDefault @8-8; FunctionDeclaration; parameters=1; async=false; generator=false
- _defineProperty @9-9; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @10-10; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @11-11; FunctionDeclaration; parameters=2; async=false; generator=false
- _loglevel.default.methodFactory @44-60; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @45-59; FunctionExpression; parameters=1; async=false; generator=false
- extendLogger @69-75; FunctionDeclaration; parameters=1; async=false; generator=false
- prefixedLogger.withPrefix @71-74; FunctionExpression; parameters=1; async=false; generator=false
- getPrefixedLogger @76-85; FunctionDeclaration; parameters=1; async=false; generator=false
- constructor @106-110; FunctionExpression; parameters=2; async=false; generator=false
- trace @111-113; FunctionExpression; parameters=1; async=false; generator=false
- debug @114-116; FunctionExpression; parameters=1; async=false; generator=false
- info @117-119; FunctionExpression; parameters=1; async=false; generator=false
- warn @120-122; FunctionExpression; parameters=1; async=false; generator=false
- error @123-125; FunctionExpression; parameters=1; async=false; generator=false
- Class LogSpan @105-126

### chat/protocols/matrix/lib/matrix-sdk/matrix.js

Blob: `609faa27fe753e09fcb77c14f64fa6cdccb8daff`. Role: source. Parse: module.

- get @38-40; FunctionExpression; parameters=0; async=false; generator=false
- get @44-46; FunctionExpression; parameters=0; async=false; generator=false
- get @51-53; FunctionExpression; parameters=0; async=false; generator=false
- get @57-59; FunctionExpression; parameters=0; async=false; generator=false
- get @63-65; FunctionExpression; parameters=0; async=false; generator=false
- get @69-71; FunctionExpression; parameters=0; async=false; generator=false
- get @75-77; FunctionExpression; parameters=0; async=false; generator=false
- get @81-83; FunctionExpression; parameters=0; async=false; generator=false
- get @87-89; FunctionExpression; parameters=0; async=false; generator=false
- get @93-95; FunctionExpression; parameters=0; async=false; generator=false
- get @99-101; FunctionExpression; parameters=0; async=false; generator=false
- get @105-107; FunctionExpression; parameters=0; async=false; generator=false
- get @111-113; FunctionExpression; parameters=0; async=false; generator=false
- get @117-119; FunctionExpression; parameters=0; async=false; generator=false
- get @123-125; FunctionExpression; parameters=0; async=false; generator=false
- get @129-131; FunctionExpression; parameters=0; async=false; generator=false
- get @136-138; FunctionExpression; parameters=0; async=false; generator=false
- get @142-144; FunctionExpression; parameters=0; async=false; generator=false
- get @148-150; FunctionExpression; parameters=0; async=false; generator=false
- get @154-156; FunctionExpression; parameters=0; async=false; generator=false
- get @160-162; FunctionExpression; parameters=0; async=false; generator=false
- get @167-169; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @174-184; FunctionExpression; parameters=1; async=false; generator=false
- get @180-182; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @186-196; FunctionExpression; parameters=1; async=false; generator=false
- get @192-194; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @198-208; FunctionExpression; parameters=1; async=false; generator=false
- get @204-206; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @210-220; FunctionExpression; parameters=1; async=false; generator=false
- get @216-218; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @222-232; FunctionExpression; parameters=1; async=false; generator=false
- get @228-230; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @234-244; FunctionExpression; parameters=1; async=false; generator=false
- get @240-242; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @246-256; FunctionExpression; parameters=1; async=false; generator=false
- get @252-254; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @258-268; FunctionExpression; parameters=1; async=false; generator=false
- get @264-266; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @270-280; FunctionExpression; parameters=1; async=false; generator=false
- get @276-278; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @282-292; FunctionExpression; parameters=1; async=false; generator=false
- get @288-290; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @294-304; FunctionExpression; parameters=1; async=false; generator=false
- get @300-302; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @306-316; FunctionExpression; parameters=1; async=false; generator=false
- get @312-314; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @318-328; FunctionExpression; parameters=1; async=false; generator=false
- get @324-326; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @330-340; FunctionExpression; parameters=1; async=false; generator=false
- get @336-338; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @342-352; FunctionExpression; parameters=1; async=false; generator=false
- get @348-350; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @354-364; FunctionExpression; parameters=1; async=false; generator=false
- get @360-362; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @366-376; FunctionExpression; parameters=1; async=false; generator=false
- get @372-374; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @378-388; FunctionExpression; parameters=1; async=false; generator=false
- get @384-386; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @390-400; FunctionExpression; parameters=1; async=false; generator=false
- get @396-398; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @402-412; FunctionExpression; parameters=1; async=false; generator=false
- get @408-410; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @414-424; FunctionExpression; parameters=1; async=false; generator=false
- get @420-422; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @426-436; FunctionExpression; parameters=1; async=false; generator=false
- get @432-434; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @438-448; FunctionExpression; parameters=1; async=false; generator=false
- get @444-446; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @450-460; FunctionExpression; parameters=1; async=false; generator=false
- get @456-458; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @462-472; FunctionExpression; parameters=1; async=false; generator=false
- get @468-470; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @474-484; FunctionExpression; parameters=1; async=false; generator=false
- get @480-482; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @486-496; FunctionExpression; parameters=1; async=false; generator=false
- get @492-494; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @498-508; FunctionExpression; parameters=1; async=false; generator=false
- get @504-506; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @510-520; FunctionExpression; parameters=1; async=false; generator=false
- get @516-518; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @522-532; FunctionExpression; parameters=1; async=false; generator=false
- get @528-530; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @534-544; FunctionExpression; parameters=1; async=false; generator=false
- get @540-542; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @546-556; FunctionExpression; parameters=1; async=false; generator=false
- get @552-554; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @558-568; FunctionExpression; parameters=1; async=false; generator=false
- get @564-566; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @570-580; FunctionExpression; parameters=1; async=false; generator=false
- get @576-578; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @582-592; FunctionExpression; parameters=1; async=false; generator=false
- get @588-590; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @594-604; FunctionExpression; parameters=1; async=false; generator=false
- get @600-602; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @606-616; FunctionExpression; parameters=1; async=false; generator=false
- get @612-614; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @618-628; FunctionExpression; parameters=1; async=false; generator=false
- get @624-626; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @630-640; FunctionExpression; parameters=1; async=false; generator=false
- get @636-638; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @642-652; FunctionExpression; parameters=1; async=false; generator=false
- get @648-650; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @654-664; FunctionExpression; parameters=1; async=false; generator=false
- get @660-662; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @666-676; FunctionExpression; parameters=1; async=false; generator=false
- get @672-674; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @678-688; FunctionExpression; parameters=1; async=false; generator=false
- get @684-686; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @690-700; FunctionExpression; parameters=1; async=false; generator=false
- get @696-698; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @702-712; FunctionExpression; parameters=1; async=false; generator=false
- get @708-710; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @714-724; FunctionExpression; parameters=1; async=false; generator=false
- get @720-722; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @726-736; FunctionExpression; parameters=1; async=false; generator=false
- get @732-734; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @738-748; FunctionExpression; parameters=1; async=false; generator=false
- get @744-746; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @750-760; FunctionExpression; parameters=1; async=false; generator=false
- get @756-758; FunctionExpression; parameters=0; async=false; generator=false
- _getRequireWildcardCache @777-777; FunctionDeclaration; parameters=1; async=false; generator=false
- _getRequireWildcardCache @777-777; FunctionExpression; parameters=1; async=false; generator=false
- _interopRequireWildcard @778-778; FunctionDeclaration; parameters=2; async=false; generator=false
- cryptoStoreFactory @799-799; ArrowFunctionExpression; parameters=0; async=false; generator=false
- setCryptoStoreFactory @806-808; FunctionDeclaration; parameters=1; async=false; generator=false
- amendClientOpts @809-816; FunctionDeclaration; parameters=1; async=false; generator=false
- createClient @828-830; FunctionDeclaration; parameters=1; async=false; generator=false
- createRoomWidgetClient @846-848; FunctionDeclaration; parameters=5; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/CallMembership.js

Blob: `f73972a0c9a73a87c0fb857f890fd3c032628cbf`. Role: source. Parse: module.

- _defineProperty @9-9; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @10-10; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @11-11; FunctionDeclaration; parameters=2; async=false; generator=false
- isSessionMembershipData @32-32; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkSessionsMembershipData @34-47; ArrowFunctionExpression; parameters=2; async=false; generator=false
- isLegacyCallMembershipData @51-51; ArrowFunctionExpression; parameters=1; async=false; generator=false
- checkCallMembershipDataLegacy @53-77; ArrowFunctionExpression; parameters=2; async=false; generator=false
- equal @79-81; FunctionExpression; parameters=2; async=false; generator=false
- constructor @82-92; FunctionExpression; parameters=2; async=false; generator=false
- sender @93-95; FunctionExpression; parameters=0; async=false; generator=false
- eventId @96-98; FunctionExpression; parameters=0; async=false; generator=false
- callId @99-101; FunctionExpression; parameters=0; async=false; generator=false
- deviceId @102-104; FunctionExpression; parameters=0; async=false; generator=false
- application @105-107; FunctionExpression; parameters=0; async=false; generator=false
- scope @108-110; FunctionExpression; parameters=0; async=false; generator=false
- membershipID @111-117; FunctionExpression; parameters=0; async=false; generator=false
- createdTs @118-120; FunctionExpression; parameters=0; async=false; generator=false
- getAbsoluteExpiry @126-136; FunctionExpression; parameters=0; async=false; generator=false
- getLocalExpiry @143-156; FunctionExpression; parameters=0; async=false; generator=false
- getMsUntilExpiry @161-171; FunctionExpression; parameters=0; async=false; generator=false
- isExpired @176-181; FunctionExpression; parameters=0; async=false; generator=false
- getPreferredFoci @182-189; FunctionExpression; parameters=0; async=false; generator=false
- getFocusSelection @190-199; FunctionExpression; parameters=0; async=false; generator=false
- Class CallMembership @78-200

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/LivekitFocus.js

Blob: `928a1e33cb66e88f83baaace2684ce051a214396`. Role: source. Parse: module.

- isLivekitFocusConfig @23-23; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isLivekitFocus @25-25; ArrowFunctionExpression; parameters=1; async=false; generator=false
- isLivekitFocusActive @27-27; ArrowFunctionExpression; parameters=1; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/MatrixRTCSession.js

Blob: `af8efc06797771c11595eac899693d2241f1c655`. Role: source. Parse: module.

- ownKeys @19-19; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @19-19; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @20-20; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @20-20; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @21-21; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @22-22; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @23-23; FunctionDeclaration; parameters=2; async=false; generator=false
- getParticipantId @52-52; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getParticipantIdFromMembership @53-53; ArrowFunctionExpression; parameters=1; async=false; generator=false
- keysEqual @54-57; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @56-56; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @58-63; FunctionExpression; parameters=1; async=false; generator=false
- callId @75-77; FunctionExpression; parameters=0; async=false; generator=false
- callMembershipsForRoom @81-136; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @131-131; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @133-133; ArrowFunctionExpression; parameters=1; async=false; generator=false
- roomSessionForRoom @141-144; FunctionExpression; parameters=2; async=false; generator=false
- constructor @145-396; FunctionExpression; parameters=3; async=false; generator=false
- (anonymous) @208-259; ArrowFunctionExpression; parameters=1; async=true; generator=false
- (anonymous) @267-310; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @311-311; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @317-357; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @321-321; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @327-327; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @328-328; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @332-332; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @333-333; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @349-349; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @349-349; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @358-373; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @374-382; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @383-391; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isJoined @402-404; FunctionExpression; parameters=0; async=false; generator=false
- stop @409-421; FunctionExpression; parameters=0; async=true; generator=false
- joinRoomSession @437-457; FunctionExpression; parameters=3; async=false; generator=false
- leaveRoomSession @469-506; FunctionExpression; parameters=1; async=true; generator=false
- getActiveFocus @507-520; FunctionExpression; parameters=0; async=false; generator=false
- reemitEncryptionKeys @526-532; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @527-531; ArrowFunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @528-530; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getKeysForParticipant @543-545; FunctionExpression; parameters=2; async=false; generator=false
- getKeysForParticipantInternal @546-548; FunctionExpression; parameters=2; async=false; generator=false
- (anonymous) @547-547; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getEncryptionKeys @556-559; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @558-558; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @558-558; ArrowFunctionExpression; parameters=1; async=false; generator=false
- getNewEncryptionKeyIndex @560-567; FunctionExpression; parameters=0; async=false; generator=false
- setEncryptionKey @583-621; FunctionExpression; parameters=6; async=false; generator=false
- (anonymous) @606-613; ArrowFunctionExpression; parameters=0; async=false; generator=false
- makeNewSenderKey @629-639; FunctionExpression; parameters=1; async=false; generator=false
- requestSendCurrentKey @645-655; FunctionExpression; parameters=0; async=false; generator=false
- setExpiryTimer @659-676; FunctionExpression; parameters=0; async=false; generator=false
- getOldestMembership @677-679; FunctionExpression; parameters=0; async=false; generator=false
- getFocusInUse @680-685; FunctionExpression; parameters=0; async=false; generator=false
- storeLastMembershipFingerprints @686-688; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @687-687; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @687-687; ArrowFunctionExpression; parameters=1; async=false; generator=false
- makeMyMembershipLegacy @694-717; FunctionExpression; parameters=2; async=false; generator=false
- makeMyMembership @721-733; FunctionExpression; parameters=1; async=false; generator=false
- membershipEventNeedsUpdate @738-753; FunctionExpression; parameters=2; async=false; generator=false
- makeNewMembership @754-760; FunctionExpression; parameters=1; async=false; generator=false
- makeNewLegacyMemberships @765-796; FunctionExpression; parameters=4; async=false; generator=false
- filterExpired @766-774; ArrowFunctionExpression; parameters=1; async=false; generator=false
- transformMemberships @775-781; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @784-784; ArrowFunctionExpression; parameters=1; async=false; generator=false
- updateCallMembershipEvent @797-902; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @816-816; ArrowFunctionExpression; parameters=1; async=false; generator=false
- prepareDelayedDisconnection @847-860; ArrowFunctionExpression; parameters=0; async=true; generator=false
- scheduleDelayDisconnection @903-905; FunctionExpression; parameters=0; async=false; generator=false
- stateEventsContainOngoingLegacySession @906-926; FunctionExpression; parameters=1; async=false; generator=false
- makeMembershipStateKey @927-934; FunctionExpression; parameters=2; async=false; generator=false
- Class MatrixRTCSession @68-935

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/MatrixRTCSessionManager.js

Blob: `8a183e9ec7dce51d5f1d30981ee1096759716096`. Role: source. Parse: module.

- _defineProperty @14-14; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @15-15; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @16-16; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @32-36; FunctionExpression; parameters=1; async=false; generator=false
- constructor @42-68; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @52-54; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-57; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @58-67; ArrowFunctionExpression; parameters=2; async=false; generator=false
- start @69-81; FunctionExpression; parameters=0; async=false; generator=false
- stop @82-90; FunctionExpression; parameters=0; async=false; generator=false
- getActiveRoomSession @96-98; FunctionExpression; parameters=1; async=false; generator=false
- getRoomSession @104-109; FunctionExpression; parameters=1; async=false; generator=false
- consumeCallEncryptionEvent @110-131; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @116-116; ArrowFunctionExpression; parameters=0; async=false; generator=false
- refreshRoom @132-143; FunctionExpression; parameters=1; async=false; generator=false
- Class MatrixRTCSessionManager @41-144

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/focus.js

Blob: `430afc16cdfa1c471b1b89abcb059363dd193d64`. Role: source. Parse: module.


### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/index.js

Blob: `57ea271306e1825bb9ea6f92628ee4ff6343a333`. Role: source. Parse: module.

- (anonymous) @7-16; FunctionExpression; parameters=1; async=false; generator=false
- get @12-14; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @18-27; FunctionExpression; parameters=1; async=false; generator=false
- get @23-25; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @29-38; FunctionExpression; parameters=1; async=false; generator=false
- get @34-36; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @40-49; FunctionExpression; parameters=1; async=false; generator=false
- get @45-47; FunctionExpression; parameters=0; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/matrixrtc/types.js

Blob: `430afc16cdfa1c471b1b89abcb059363dd193d64`. Role: source. Parse: module.


### chat/protocols/matrix/lib/matrix-sdk/models/MSC3089Branch.js

Blob: `808e19d2e23861e0746f6e6fe3891663565e5cc6`. Role: source. Parse: module.

- ownKeys @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @9-9; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @10-10; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @10-10; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @11-11; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @12-12; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @13-13; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @34-38; FunctionExpression; parameters=3; async=false; generator=false
- id @43-49; FunctionExpression; parameters=0; async=false; generator=false
- isActive @54-56; FunctionExpression; parameters=0; async=false; generator=false
- version @61-63; FunctionExpression; parameters=0; async=false; generator=false
- roomId @64-66; FunctionExpression; parameters=0; async=false; generator=false
- delete @72-77; FunctionExpression; parameters=0; async=true; generator=false
- getName @83-85; FunctionExpression; parameters=0; async=false; generator=false
- setName @92-96; FunctionExpression; parameters=1; async=true; generator=false
- isLocked @102-104; FunctionExpression; parameters=0; async=false; generator=false
- setLocked @111-115; FunctionExpression; parameters=1; async=true; generator=false
- getFileInfo @121-132; FunctionExpression; parameters=0; async=true; generator=false
- getFileEvent @138-153; FunctionExpression; parameters=0; async=true; generator=false
- createNewVersion @163-184; FunctionExpression; parameters=4; async=true; generator=false
- getVersionHistory @191-221; FunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @209-209; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MSC3089Branch @33-222

### chat/protocols/matrix/lib/matrix-sdk/models/MSC3089TreeSpace.js

Blob: `bd63f163951d500ce2b025ff3dd6d3b909a03ccd`. Role: source. Parse: module.

- _interopRequireDefault @13-13; FunctionDeclaration; parameters=1; async=false; generator=false
- ownKeys @14-14; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @14-14; FunctionExpression; parameters=1; async=false; generator=false
- _objectSpread @15-15; FunctionDeclaration; parameters=1; async=false; generator=false
- (anonymous) @15-15; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @15-15; FunctionExpression; parameters=1; async=false; generator=false
- _defineProperty @16-16; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @17-17; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @18-18; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @66-71; FunctionExpression; parameters=1; async=false; generator=false
- constructor @78-84; FunctionExpression; parameters=2; async=false; generator=false
- id @89-91; FunctionExpression; parameters=0; async=false; generator=false
- isTopLevel @96-102; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @101-101; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setName @109-113; FunctionExpression; parameters=1; async=true; generator=false
- invite @123-129; FunctionExpression; parameters=2; async=true; generator=false
- (anonymous) @126-126; ArrowFunctionExpression; parameters=1; async=false; generator=false
- retryInvite @130-140; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @131-139; ArrowFunctionExpression; parameters=0; async=true; generator=false
- (anonymous) @132-138; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setPermissions @150-173; FunctionExpression; parameters=2; async=true; generator=false
- getPermissions @182-193; FunctionExpression; parameters=1; async=false; generator=false
- createDirectory @200-209; FunctionExpression; parameters=1; async=true; generator=false
- getDirectories @215-230; FunctionExpression; parameters=0; async=false; generator=false
- getDirectory @238-240; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @239-239; ArrowFunctionExpression; parameters=1; async=false; generator=false
- delete @246-264; FunctionExpression; parameters=0; async=true; generator=false
- getOrderedChildren @265-294; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @266-269; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @269-269; ArrowFunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @270-292; ArrowFunctionExpression; parameters=2; async=false; generator=false
- getParentRoom @295-307; FunctionExpression; parameters=0; async=false; generator=false
- getOrder @314-320; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @319-319; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setOrder @330-424; FunctionExpression; parameters=1; async=true; generator=false
- createFile @435-463; FunctionExpression; parameters=4; async=true; generator=false
- getFile @470-473; FunctionExpression; parameters=1; async=false; generator=false
- listFiles @479-481; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @480-480; ArrowFunctionExpression; parameters=1; async=false; generator=false
- listAllFiles @487-490; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @489-489; ArrowFunctionExpression; parameters=1; async=false; generator=false
- Class MSC3089TreeSpace @77-491

### chat/protocols/matrix/lib/matrix-sdk/models/ToDeviceMessage.js

Blob: `430afc16cdfa1c471b1b89abcb059363dd193d64`. Role: source. Parse: module.


### chat/protocols/matrix/lib/matrix-sdk/models/beacon.js

Blob: `1dbf6aef101e5cf8bf21b445ea443f1a5472f5dc`. Role: source. Parse: module.

- _defineProperty @10-10; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @11-11; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @12-12; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @27-34; FunctionExpression; parameters=1; async=false; generator=false
- isTimestampInDuration @35-35; ArrowFunctionExpression; parameters=3; async=false; generator=false
- getBeaconInfoIdentifier @40-40; ArrowFunctionExpression; parameters=1; async=false; generator=false
- constructor @45-61; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @55-58; ArrowFunctionExpression; parameters=0; async=false; generator=false
- isLive @62-64; FunctionExpression; parameters=0; async=false; generator=false
- identifier @65-67; FunctionExpression; parameters=0; async=false; generator=false
- beaconInfoId @68-70; FunctionExpression; parameters=0; async=false; generator=false
- beaconInfoOwner @71-73; FunctionExpression; parameters=0; async=false; generator=false
- beaconInfoEventType @74-76; FunctionExpression; parameters=0; async=false; generator=false
- beaconInfo @77-79; FunctionExpression; parameters=0; async=false; generator=false
- latestLocationState @80-82; FunctionExpression; parameters=0; async=false; generator=false
- latestLocationEvent @83-85; FunctionExpression; parameters=0; async=false; generator=false
- update @86-98; FunctionExpression; parameters=1; async=false; generator=false
- destroy @99-105; FunctionExpression; parameters=0; async=false; generator=false
- monitorLiveness @111-131; FunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @120-122; ArrowFunctionExpression; parameters=0; async=false; generator=false
- (anonymous) @127-129; ArrowFunctionExpression; parameters=0; async=false; generator=false
- addLocations @137-160; FunctionExpression; parameters=1; async=false; generator=false
- (anonymous) @142-154; ArrowFunctionExpression; parameters=1; async=false; generator=false
- setBeaconInfo @161-164; FunctionExpression; parameters=1; async=false; generator=false
- checkLiveness @165-178; FunctionExpression; parameters=0; async=false; generator=false
- Class Beacon @44-179

### chat/protocols/matrix/lib/matrix-sdk/models/compare-event-ordering.js

Blob: `72ede678a46679640d995117054bcae0fd276299`. Role: source. Parse: module.

- compareEventOrdering @45-64; FunctionDeclaration; parameters=3; async=false; generator=false
- compareEventsInMainTimeline @65-94; FunctionDeclaration; parameters=5; async=false; generator=false
- compareEventsInThreads @95-106; FunctionDeclaration; parameters=4; async=false; generator=false
- guessOrderBasedOnTimestamp @114-124; FunctionDeclaration; parameters=2; async=false; generator=false

### chat/protocols/matrix/lib/matrix-sdk/models/device.js

Blob: `ef0c1bc66f26b03e58eb844962f295dcd65e78af`. Role: source. Parse: module.

- _defineProperty @7-7; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @8-8; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @9-9; FunctionDeclaration; parameters=2; async=false; generator=false
- (anonymous) @26-31; FunctionExpression; parameters=1; async=false; generator=false
- constructor @37-62; FunctionExpression; parameters=1; async=false; generator=false
- getFingerprint @69-71; FunctionExpression; parameters=0; async=false; generator=false
- getIdentityKey @78-80; FunctionExpression; parameters=0; async=false; generator=false
- Class Device @36-81

### chat/protocols/matrix/lib/matrix-sdk/models/event-context.js

Blob: `344de0ab2aee5ebf74e749183d39da4d6de5c7da`. Role: source. Parse: module.

- _defineProperty @8-8; FunctionDeclaration; parameters=3; async=false; generator=false
- _toPropertyKey @9-9; FunctionDeclaration; parameters=1; async=false; generator=false
- _toPrimitive @10-10; FunctionDeclaration; parameters=2; async=false; generator=false
- constructor @38-47; FunctionExpression; parameters=1; async=false; generator=false
- getEvent @56-58; FunctionExpression; parameters=0; async=false; generator=false
- getTimeline @65-67; FunctionExpression; parameters=0; async=false; generator=false
- getOurEventIndex @72-74; FunctionExpression; parameters=0; async=false; generator=false
- getPaginateToken @81-83; FunctionExpression; parameters=1; async=false; generator=false
- setPaginateToken @94-96; FunctionExpression; parameters=2; async=false; generator=false
- addEvents @104-114; FunctionExpression; parameters=2; async=false; generator=false
- Class EventContext @25-115

### chat/protocols/matrix/lib/matrix-sdk/models/event-status.js

Blob: `9101a335a8d48ec06372cd48789fcaf8888870fd`. Role: source. Parse: module.

- (anonymous) @26-34; FunctionExpression; parameters=1; async=false; generator=false

## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.
