<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["caps/BasePrincipal.cpp", "caps/BasePrincipal.h", "caps/ContentPrincipal.cpp", "caps/ContentPrincipal.h", "caps/ContentPrincipalJSONHandler.h", "caps/DomainPolicy.cpp", "caps/DomainPolicy.h", "caps/ExpandedPrincipal.cpp", "caps/ExpandedPrincipal.h", "caps/ExpandedPrincipalJSONHandler.h", "caps/NullPrincipal.cpp", "caps/NullPrincipal.h", "caps/NullPrincipalJSONHandler.h", "caps/OriginAttributes.cpp", "caps/OriginAttributes.h", "caps/OriginAttributesHashKey.h", "caps/PrincipalHashKey.h", "caps/PrincipalJSONHandler.h", "caps/SharedJSONHandler.h", "caps/SubsumedPrincipalJSONHandler.h", "caps/SystemPrincipal.cpp", "caps/SystemPrincipal.h", "caps/nsJSPrincipals.cpp", "caps/nsJSPrincipals.h", "caps/nsScriptSecurityManager.cpp", "caps/nsScriptSecurityManager.h", "caps/tests/gtest/TestBackgroundThreadPrincipal.cpp", "caps/tests/gtest/TestNullPrincipalPrecursor.cpp", "caps/tests/gtest/TestOriginAttributes.cpp", "caps/tests/gtest/TestPrincipalAttributes.cpp", "caps/tests/gtest/TestPrincipalHash.cpp", "caps/tests/gtest/TestPrincipalSerialization.cpp", "caps/tests/gtest/TestRedirectChainURITruncation.cpp", "caps/tests/gtest/TestScriptSecurityManager.cpp"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/caps native and TypeScript syntax map 7

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### caps/BasePrincipal.cpp

Blob: `dde6854a48d1b7ff690e13bf9966e9f5d8c9f581`. Grammar: cpp. Status: contains-errors.

- include "mozilla/BasePrincipal.h" @5
- include "ContentPrincipalJSONHandler.h" @7
- include "ExpandedPrincipal.h" @8
- include "ExpandedPrincipalJSONHandler.h" @9
- include "NullPrincipalJSONHandler.h" @10
- include "PrincipalJSONHandler.h" @11
- include "SubsumedPrincipalJSONHandler.h" @12
- include "ThirdPartyUtil.h" @13
- include "js/JSON.h" @14
- include "mozilla/Components.h" @15
- include "mozilla/ContentPrincipal.h" @16
- include "mozilla/ExtensionPolicyService.h" @17
- include "mozilla/JSONStringWriteFuncs.h" @18
- include "mozilla/JSONWriter.h" @19
- include "mozilla/NullPrincipal.h" @20
- include "mozilla/PermissionManager.h" @21
- include "mozilla/StaticPrefs_permissions.h" @22
- include "mozilla/StorageAccess.h" @23
- include "mozilla/dom/BlobURLProtocolHandler.h" @24
- include "mozilla/dom/ChromeUtils.h" @25
- include "mozilla/dom/ReferrerInfo.h" @26
- include "mozilla/dom/StorageUtils.h" @27
- include "mozilla/dom/ToJSValue.h" @28
- include "mozilla/dom/nsMixedContentBlocker.h" @29
- include "nsAboutProtocolUtils.h" @30
- include "nsContentUtils.h" @31
- include "nsDocShell.h" @32
- include "nsIEffectiveTLDService.h" @33
- include "nsIOService.h" @34
- include "nsIURIFixup.h" @35
- include "nsIURIMutator.h" @36
- include "nsIURIWithSpecialOrigin.h" @37
- include "nsIURL.h" @38
- include "nsMixedContentBlocker.h" @39
- include "nsNetUtil.h" @40
- include "nsPIDOMWindow.h" @41
- include "nsScriptSecurityManager.h" @42
- include "nsSerializationHelper.h" @43
- include "nsServiceManagerUtils.h" @44
- include "prnetdb.h" @45
- function_definition BasePrincipal @49-56
- function_definition BasePrincipal @58-64
- function_definition ~BasePrincipal @66-66
- function_definition GetOrigin @68-78
- function_definition GetWebExposedOriginSerialization @80-89
- function_definition GetHostPort @91-100
- function_definition GetHost @102-111
- function_definition GetOriginNoSuffix @113-117
- function_definition GetSiteOrigin @119-129
- function_definition GetSiteOriginNoSuffix @131-134
- function_definition ProcessInnerResult @137-145
- function_definition startObject @148-167
- function_definition propertyName @170-223
- function_definition endObject @226-269
- function_definition startArray @272-282
- function_definition endArray @285-295
- function_definition stringValue @298-308
- class_specifier ContainerPrincipalJSONHandler<PrincipalJSONHandlerTypes> @310-310
- class_specifier ContainerPrincipalJSONHandler<SubsumedPrincipalJSONHandlerTypes> @311-311
- function_definition FromJSON @331-347
- function_definition ToJSON @352-364
- function_definition ToJSON @366-377
- function_definition WriteJSONProperties @379-389
- function_definition WriteJSONInnerProperties @391-393
- function_definition FastSubsumesIgnoringFPD @395-406
- function_definition Subsumes @408-423
- function_definition Equals @425-432
- function_definition EqualsForPermission @434-553
- function_definition EqualsConsideringDomain @555-562
- function_definition EqualsURI @564-573
- function_definition Subsumes @575-582
- function_definition SubsumesConsideringDomain @584-591
- function_definition SubsumesConsideringDomainIgnoringFPD @593-601
- function_definition CheckMayLoad @603-606
- function_definition CheckMayLoadWithReporting @608-615
- function_definition CheckMayLoadHelper @617-679
- function_definition IsThirdPartyURI @681-697
- function_definition IsThirdPartyPrincipal @699-708
- function_definition IsThirdPartyChannel @710-723
- function_definition IsSameOrigin @725-737
- function_definition IsL10nAllowed @739-786
- function_definition GetPrefLightCacheKey @788-823
- function_definition HasFirstpartyStorageAccess @825-853
- function_definition GetIsNullPrincipal @855-859
- function_definition GetIsContentPrincipal @861-865
- function_definition GetIsExpandedPrincipal @867-871
- function_definition GetAsciiSpec @873-882
- function_definition GetSpec @884-893
- function_definition GetAsciiHost @895-904
- function_definition GetExposablePrePath @906-917
- function_definition GetExposableSpec @919-935
- function_definition GetPrePath @937-946
- function_definition GetFilePath @948-957
- function_definition GetIsSystemPrincipal @959-963
- function_definition GetIsAddonPrincipal @965-969
- function_definition GetIsAddonOrExpandedAddonPrincipal @971-975
- function_definition GetIsOnion @977-992
- function_definition GetIsIpAddress @994-1017
- function_definition GetIsLocalIpAddress @1019-1037
- function_definition GetScheme @1039-1050
- function_definition SchemeIs @1052-1062
- function_definition IsURIInPrefList @1064-1081
- function_definition IsURIInList @1083-1095
- function_definition IsContentAccessibleAboutURI @1097-1113
- function_definition GetIsOriginPotentiallyTrustworthy @1115-1128
- function_definition GetIsLoopbackHost @1130-1143
- function_definition GetIsSecureContextAllowlistedHost @1145-1167
- function_definition GetAboutModuleFlags @1169-1188
- function_definition GetOriginAttributes @1190-1197
- function_definition GetOriginSuffix @1199-1204
- function_definition GetUserContextId @1206-1210
- function_definition GetPrivateBrowsingId @1212-1216
- function_definition GetIsInPrivateBrowsing @1218-1222
- function_definition GetAddonPolicy @1224-1230
- function_definition GetContentScriptAddonPolicy @1232-1237
- function_definition AddonPolicy @1239-1243
- function_definition AddonPolicyCore @1245-1250
- function_definition AddonHasPermission @1252-1257
- function_definition PrincipalToInherit @1259-1264
- function_definition OverridesCSP @1266-1279
- function_definition CreateContentPrincipal @1281-1310
- function_definition CreateContentPrincipal @1312-1350
- function_definition CreateContentPrincipal @1352-1373
- function_definition CloneForcingOriginAttributes @1375-1392
- function_definition ContentScriptAddonPolicy @1394-1399
- function_definition ContentScriptAddonPolicyCore @1401-1416
- function_definition AddonAllowsLoad @1418-1427
- function_definition GetLocalStorageQuotaKey @1429-1477
- function_definition GetNextSubDomainPrincipal @1479-1526
- function_definition GetStorageOriginKey @1528-1576
- function_definition GetIsScriptAllowedByPolicy @1578-1592
- function_definition Equals @1594-1598
- function_definition CreateReferrerInfo @1600-1614
- function_definition GetPrecursorPrincipal @1616-1620
- function_definition WriteJSONProperty @1641-1645
- function_definition GetHashValue @1649-1653

### caps/BasePrincipal.h

Blob: `2d9e54ef3296d15b7ce814d90ff89750b508157b`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @8
- include "ErrorList.h" @10
- include "js/TypeDecls.h" @11
- include "mozilla/AlreadyAddRefed.h" @12
- include "mozilla/Assertions.h" @13
- include "mozilla/OriginAttributes.h" @14
- include "mozilla/RefPtr.h" @15
- include "nsAtom.h" @16
- include "nsIObjectOutputStream.h" @17
- include "nsIPrincipal.h" @18
- include "nsJSPrincipals.h" @19
- include "nsStringFwd.h" @20
- include "nscore.h" @21
- class_specifier ExpandedPrincipal @23-23
- class_specifier mozIDOMWindow @24-24
- class_specifier nsIChannel @25-25
- class_specifier nsIReferrerInfo @26-26
- class_specifier nsISupports @27-27
- class_specifier nsIURI @28-28
- class_specifier JSONWriter @32-32
- enum_specifier ReferrerPolicy @35-35
- class_specifier WebExtensionPolicy @39-39
- class_specifier WebExtensionPolicyCore @40-40
- class_specifier BasePrincipal @43-43
- class_specifier SiteIdentifier @51-71
- function_definition Init @53-56
- function_definition IsInitialized @58-58
- function_definition GetPrincipal @65-68
- class_specifier BasePrincipal @80-387
- enum_specifier PrincipalKind @84-90
- function_definition Is @102-104
- function_definition As @107-110
- enum_specifier DocumentDomainConsideration @112-115
- function_definition IsContentPrincipal @209-209
- function_definition Cast @211-213
- function_definition (anonymous) @215-217
- function_definition Cast @219-221
- function_definition (anonymous) @223-225
- function_definition (anonymous) @242-244
- function_definition UserContextId @247-247
- function_definition PrivateBrowsingId @248-250
- function_definition Kind @252-252
- function_definition GetOriginNoSuffixHash @293-293
- function_definition GetOriginSuffixHash @294-294
- function_definition SetHasExplicitDomain @323-323
- function_definition GetHasExplicitDomain @324-324
- struct_specifier KeyValT @329-335
- class_specifier Deserializer @340-348
- function_definition ~Deserializer @346-346
- function_definition (anonymous) @364-367
- function_definition WriteJSONProperty @369-371
- function_definition FastEquals @389-412
- function_definition FastEqualsConsideringDomain @414-436
- function_definition FastSubsumes @438-448
- function_definition FastSubsumesConsideringDomain @450-461
- function_definition FastSubsumesIgnoringFPD @463-465
- function_definition FastSubsumesConsideringDomainIgnoringFPD @467-470
- function_definition IsSystemPrincipal @472-474
- function_definition IsSystemPrincipal @478-480

### caps/ContentPrincipal.cpp

Blob: `40e20360e7a6dd7c8379ab5f041fff4a281ddc02`. Grammar: cpp. Status: contains-errors.

- include "ContentPrincipal.h" @5
- include "ContentPrincipalJSONHandler.h" @7
- include "js/JSON.h" @8
- include "js/RealmIterators.h" @9
- include "js/Wrapper.h" @10
- include "mozIThirdPartyUtil.h" @11
- include "mozilla/ClearOnShutdown.h" @12
- include "mozilla/ExtensionPolicyService.h" @13
- include "mozilla/Preferences.h" @14
- include "mozilla/dom/BlobURLProtocolHandler.h" @15
- include "mozilla/dom/ScriptSettings.h" @16
- include "nsAboutProtocolUtils.h" @17
- include "nsContentUtils.h" @18
- include "nsError.h" @19
- include "nsIClassInfoImpl.h" @20
- include "nsIContentSecurityPolicy.h" @21
- include "nsIEffectiveTLDService.h" @22
- include "nsIObjectInputStream.h" @23
- include "nsIObjectOutputStream.h" @24
- include "nsIProtocolHandler.h" @25
- include "nsIStandardURL.h" @26
- include "nsIURI.h" @27
- include "nsIURIMutator.h" @28
- include "nsIURIWithSpecialOrigin.h" @29
- include "nsIURL.h" @30
- include "nsJSPrincipals.h" @31
- include "nsNetCID.h" @32
- include "nsReadableUtils.h" @33
- include "nsScriptSecurityManager.h" @34
- include "nsSerializationHelper.h" @35
- include "nsString.h" @36
- include "nscore.h" @37
- include "pratom.h" @38
- function_definition ContentPrincipal @46-70
- function_definition ContentPrincipal @72-77
- function_definition ~ContentPrincipal @79-79
- function_definition GetScriptLocation @81-83
- function_definition GenerateOriginNoSuffixFromURI @86-204
- function_definition SubsumesInternal @206-247
- function_definition GetURI @249-253
- function_definition MayLoadInternal @255-293
- function_definition GetDomain @295-305
- function_definition SetDomain @307-333
- function_definition GetSpecialBaseDomain @335-388
- function_definition GetBaseDomain @390-409
- function_definition GetSiteOriginNoSuffix @411-472
- function_definition GetSiteIdentifier @474-487
- function_definition AddonPolicyCore @489-504
- function_definition GetAddonId @506-514
- function_definition Deserializer::Read @516-573
- function_definition WriteJSONInnerProperties @575-612
- function_definition startObject @614-626
- function_definition propertyName @628-667
- function_definition endObject @669-697
- function_definition stringValue @699-757

### caps/ContentPrincipal.h

Blob: `3ad1e95a4d73e24062f2e700cf9026d87b8c0f20`. Grammar: cpp. Status: contains-errors.

- include "mozilla/BasePrincipal.h" @8
- include "mozilla/Mutex.h" @9
- include "mozilla/extensions/WebExtensionPolicy.h" @10
- include "nsCOMPtr.h" @11
- include "nsJSPrincipals.h" @12
- include "nsNetUtil.h" @13
- include "nsScriptSecurityManager.h" @14
- include "nsTArray.h" @15
- class_specifier JSONWriter @19-19
- class_specifier ContentPrincipal @21-83
- function_definition IsContentPrincipal @30-30
- function_definition Kind @37-37
- enum_specifier SerializableKeys @51-56
- class_specifier Deserializer @65-68

### caps/ContentPrincipalJSONHandler.h

Blob: `bd769c2a1e72f418b8684d763e3612261ec3faa2`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include "ContentPrincipal.h" @11
- include "OriginAttributes.h" @12
- include "SharedJSONHandler.h" @13
- include "js/TypeDecls.h" @14
- include "mozilla/RefPtr.h" @15
- include "nsCOMPtr.h" @16
- include "nsDebug.h" @17
- include "nsIURI.h" @18
- class_specifier ContentPrincipalJSONHandler @24-85
- enum_specifier State @25-47
- function_definition ContentPrincipalJSONHandler @50-50
- function_definition ~ContentPrincipalJSONHandler @51-51
- function_definition startArray @60-64
- function_definition endArray @65-69
- function_definition HasAccepted @74-74
- function_definition SetErrorState @77-77

### caps/DomainPolicy.cpp

Blob: `b2de4baa69364958b7a66682eb82265a581f2362`. Grammar: cpp. Status: contains-errors.

- include "DomainPolicy.h" @5
- include "mozilla/dom/ContentParent.h" @7
- include "mozilla/ipc/URIUtils.h" @8
- include "nsIURIMutator.h" @9
- include "nsScriptSecurityManager.h" @10
- function_definition BroadcastDomainSetChange @19-35
- function_definition DomainPolicy @37-45
- function_definition ~DomainPolicy @47-52
- function_definition GetBlocklist @54-59
- function_definition GetSuperBlocklist @61-66
- function_definition GetAllowlist @68-73
- function_definition GetSuperAllowlist @75-80
- function_definition Deactivate @82-107
- function_definition CloneDomainPolicy @109-115
- function_definition CopyURIs @117-125
- function_definition ApplyClone @127-132
- function_definition GetCanonicalClone @134-141
- function_definition Add @145-155
- function_definition Remove @157-167
- function_definition Clear @169-177
- function_definition Contains @179-186
- function_definition ContainsSuperDomain @188-214
- function_definition CloneSet @216-218

### caps/DomainPolicy.h

Blob: `9a79c15903f7c1a063d662aee53c891272625b1a`. Grammar: cpp. Status: contains-errors.

- include "nsIDomainPolicy.h" @8
- include "nsTHashSet.h" @9
- include "nsURIHashKey.h" @10
- enum_specifier DomainSetChangeType @14-20
- enum_specifier DomainSetType @22-28
- class_specifier DomainSet @30-43
- function_definition DomainSet @35-35
- function_definition ~DomainSet @40-40
- class_specifier DomainPolicy @45-58

### caps/ExpandedPrincipal.cpp

Blob: `b8c211f6dbfac60578d99226a0cd13eefd1b15ae`. Grammar: cpp. Status: contains-errors.

- include "ExpandedPrincipal.h" @5
- include "ExpandedPrincipalJSONHandler.h" @7
- include "SubsumedPrincipalJSONHandler.h" @8
- include "js/JSON.h" @9
- include "mozilla/Base64.h" @10
- include "mozilla/JSONWriter.h" @11
- include "mozilla/extensions/WebExtensionPolicy.h" @12
- include "nsCharSeparatedTokenizer.h" @13
- include "nsIClassInfoImpl.h" @14
- include "nsIObjectInputStream.h" @15
- include "nsReadableUtils.h" @16
- function_definition ExpandedPrincipal @26-30
- function_definition ~ExpandedPrincipal @32-32
- function_definition Create @34-57
- function_definition GetDomain @59-63
- function_definition SetDomain @65-66
- function_definition SubsumesInternal @68-96
- function_definition MayLoadInternal @98-106
- function_definition GetURI @108-112
- function_definition (anonymous) @114-116
- function_definition GetBaseDomain @118-121
- function_definition GetAddonId @123-127
- function_definition AddonHasPermission @129-136
- function_definition AddonAllowsLoad @138-146
- function_definition SetCsp @148-152
- function_definition GetCsp @154-159
- function_definition PrincipalToInherit @161-176
- function_definition GetScriptLocation @178-194
- function_definition Deserializer::Read @204-242
- function_definition GetSiteIdentifier @244-262
- function_definition WriteJSONInnerProperties @264-286
- function_definition ProcessSubsumedResult @288-295
- function_definition startObject @297-320
- function_definition propertyName @322-362
- function_definition endObject @364-391
- function_definition startArray @393-405
- function_definition endArray @407-420
- function_definition stringValue @422-469
- function_definition IsThirdPartyURI @471-490

### caps/ExpandedPrincipal.h

Blob: `82fbd20a9864d78e7c901da59cbe48b4e7c9e316`. Grammar: cpp. Status: contains-errors.

- include "mozilla/BasePrincipal.h" @8
- include "nsCOMPtr.h" @9
- include "nsJSPrincipals.h" @10
- include "nsNetUtil.h" @11
- include "nsProxyRelease.h" @12
- include "nsTArray.h" @13
- class_specifier nsIContentSecurityPolicy @15-15
- class_specifier JSONWriter @18-18
- class_specifier ExpandedPrincipal @21-90
- function_definition Kind @28-28
- function_definition AddRef @32-34
- function_definition Release @35-37
- enum_specifier SerializableKeys @62-62
- class_specifier Deserializer @69-72

### caps/ExpandedPrincipalJSONHandler.h

Blob: `745231216427957b2472a121ef391c13feb55522`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include "ExpandedPrincipal.h" @11
- include "OriginAttributes.h" @12
- include "SharedJSONHandler.h" @13
- include "SubsumedPrincipalJSONHandler.h" @14
- include "js/TypeDecls.h" @15
- include "mozilla/Maybe.h" @16
- include "mozilla/RefPtr.h" @17
- include "nsCOMPtr.h" @18
- include "nsDebug.h" @19
- include "nsIPrincipal.h" @20
- include "nsTArray.h" @21
- class_specifier ExpandedPrincipalJSONHandler @60-121
- enum_specifier State @61-88
- function_definition ExpandedPrincipalJSONHandler @91-91
- function_definition ~ExpandedPrincipalJSONHandler @92-92
- function_definition HasAccepted @107-107
- function_definition SetErrorState @110-110

### caps/NullPrincipal.cpp

Blob: `a9a429e463e75f19cc8cc25a24e0a033993018e1`. Grammar: cpp. Status: contains-errors.

- include "NullPrincipal.h" @11
- include "ContentPrincipal.h" @13
- include "DefaultURI.h" @14
- include "NullPrincipalJSONHandler.h" @15
- include "js/JSON.h" @16
- include "mozilla/StaticPrefs_network.h" @17
- include "mozilla/dom/BlobURLProtocolHandler.h" @18
- include "nsDocShell.h" @19
- include "nsError.h" @20
- include "nsEscape.h" @21
- include "nsIClassInfoImpl.h" @22
- include "nsIObjectInputStream.h" @23
- include "nsNetCID.h" @24
- include "nsScriptSecurityManager.h" @25
- include "nsSimpleURI.h" @26
- include "pratom.h" @27
- function_definition NullPrincipal @35-38
- function_definition CreateWithInheritedAttributes @41-46
- function_definition Create @49-65
- function_definition CreateWithoutOriginAttributes @68-70
- function_definition EscapePrecursorQuery @72-80
- function_definition UnescapePrecursorQuery @82-88
- function_definition CreateURI @90-146
- function_definition GetScriptLocation @148-150
- function_definition GetURI @156-161
- function_definition GetIsOriginPotentiallyTrustworthy @162-166
- function_definition GetDomain @168-173
- function_definition SetDomain @175-180
- function_definition MayLoadInternal @182-193
- function_definition GetBaseDomain @195-199
- function_definition GetAddonId @201-205
- function_definition Deserializer::Read @210-232
- function_definition WriteJSONInnerProperties @234-247
- function_definition GetPrecursorPrincipal @249-291
- function_definition startObject @293-305
- function_definition propertyName @307-343
- function_definition endObject @345-362
- function_definition stringValue @364-395

### caps/NullPrincipal.h

Blob: `bf0e6a5c4cb7dfc43801ca9628029a0a034d5313`. Grammar: cpp. Status: syntax-clean.

- include "gtest/MozGtestFriend.h" @14
- include "mozilla/BasePrincipal.h" @15
- include "nsCOMPtr.h" @16
- include "nsIPrincipal.h" @17
- include "nsJSPrincipals.h" @18
- class_specifier nsIDocShell @20-20
- class_specifier nsIURI @21-21
- class_specifier JSONWriter @30-30
- class_specifier NullPrincipal @32-116
- function_definition Kind @34-34
- function_definition GetSiteIdentifier @75-78
- enum_specifier SerializableKeys @83-83
- class_specifier Deserializer @90-93
- function_definition ~NullPrincipal @99-99
- function_definition SubsumesInternal @101-105

### caps/NullPrincipalJSONHandler.h

Blob: `b69b6db1b2fd42787092265de70e4716b455d137`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include "NullPrincipal.h" @11
- include "OriginAttributes.h" @12
- include "SharedJSONHandler.h" @13
- include "js/TypeDecls.h" @14
- include "mozilla/Assertions.h" @15
- include "mozilla/RefPtr.h" @16
- include "nsCOMPtr.h" @17
- include "nsDebug.h" @18
- include "nsIURI.h" @19
- class_specifier NullPrincipalJSONHandler @25-82
- enum_specifier State @26-45
- function_definition NullPrincipalJSONHandler @48-48
- function_definition ~NullPrincipalJSONHandler @49-49
- function_definition startArray @58-62
- function_definition endArray @63-67
- function_definition HasAccepted @72-72
- function_definition SetErrorState @75-75

### caps/OriginAttributes.cpp

Blob: `3209b352548ee42171050f78498e5bd93093c42b`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/OriginAttributes.h" @5
- include "mozilla/Assertions.h" @7
- include "mozilla/Preferences.h" @8
- include "mozilla/dom/BlobURLProtocolHandler.h" @9
- include "mozilla/dom/quota/QuotaManager.h" @10
- include "nsCharSeparatedTokenizer.h" @11
- include "nsIEffectiveTLDService.h" @12
- include "nsIURI.h" @13
- include "nsNetCID.h" @14
- include "nsNetUtil.h" @15
- include "nsString.h" @16
- include "nsURLHelper.h" @17
- function_definition MakeTopLevelInfo @24-46
- function_definition PopulateTopLevelInfoFromURI @48-177
- function_definition SetFirstPartyDomain @179-185
- function_definition SetFirstPartyDomain @187-190
- function_definition SetFirstPartyDomain @192-201
- function_definition SetPartitionKey @203-210
- function_definition SetPartitionKey @212-214
- function_definition SetPartitionKey @216-218
- function_definition CreateSuffix @221-289
- function_definition CreateSuffixAtom @291-295
- function_definition CreateAnonymizedSuffix @297-309
- function_definition PopulateFromSuffix @311-397
- function_definition PopulateFromOrigin @399-412
- function_definition SyncAttributesWithPrivateBrowsing @414-417
- function_definition IsPrivateBrowsing @420-428
- function_definition ParsePartitionKey @431-515
- function_definition ExtractSiteFromPartitionKey @518-534

### caps/OriginAttributes.h

Blob: `36905c9dfd20f893649d70838a75c79a7c8177a4`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/HashFunctions.h" @8
- include "mozilla/StaticPrefs_privacy.h" @9
- include "mozilla/dom/OriginAttributesBinding.h" @10
- include "nsIScriptSecurityManager.h" @11
- class_specifier OriginAttributes @15-187
- function_definition OriginAttributes @17-17
- function_definition OriginAttributes @19-20
- enum_specifier (anonymous) @33-42
- function_definition StripAttributes @44-65
- function_definition EqualsIgnoring @67-90
- function_definition operator== @92-94
- function_definition operator!= @96-98
- function_definition EqualsIgnoringFPD @100-104
- function_definition EqualsIgnoringPartitionKey @106-109
- function_definition IsPrivateBrowsing @111-114
- function_definition Hash @117-125
- function_definition IsFirstPartyEnabled @150-152
- function_definition IsRestrictOpenerAccessForFPI @157-162
- function_definition IsBlockPostMessageForFPI @166-169
- class_specifier OriginAttributesPattern @189-328
- function_definition OriginAttributesPattern @197-197
- function_definition OriginAttributesPattern @199-201
- function_definition Matches @204-270
- function_definition Overlaps @272-327

### caps/OriginAttributesHashKey.h

Blob: `9dcd0c3872ee5797c17b634f31c2da4a5429df67`. Grammar: cpp. Status: contains-errors.

- include "OriginAttributes.h" @8
- include "PLDHashTable.h" @9
- class_specifier OriginAttributesHashKey @13-44
- function_definition OriginAttributesHashKey @19-22
- function_definition OriginAttributesHashKey @23-26
- function_definition GetKey @30-30
- function_definition KeyEquals @32-34
- function_definition KeyToPointer @36-36
- function_definition HashKey @38-38
- enum_specifier (anonymous) @40-40

### caps/PrincipalHashKey.h

Blob: `aeae701d26703dc3e60b9d3880411acc190e76bb`. Grammar: cpp. Status: contains-errors.

- include "BasePrincipal.h" @8
- include "PLDHashTable.h" @9
- include "nsCOMPtr.h" @10
- include "nsHashKeys.h" @11
- class_specifier PrincipalHashKey @15-50
- function_definition PrincipalHashKey @20-24
- function_definition PrincipalHashKey @25-28
- function_definition GetKey @32-32
- function_definition KeyEquals @34-37
- function_definition KeyToPointer @39-41
- function_definition HashKey @42-44
- enum_specifier (anonymous) @46-46

### caps/PrincipalJSONHandler.h

Blob: `302e76662450f8a96b6de8d86801fa49a8d6db09`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include "BasePrincipal.h" @11
- include "ContentPrincipalJSONHandler.h" @12
- include "ExpandedPrincipalJSONHandler.h" @13
- include "NullPrincipalJSONHandler.h" @14
- include "SharedJSONHandler.h" @15
- include "js/JSON.h" @16
- include "js/TypeDecls.h" @17
- include "mozilla/AlreadyAddRefed.h" @18
- include "mozilla/RefPtr.h" @19
- include "mozilla/Variant.h" @20
- include "nsDebug.h" @21
- include "nsPrintfCString.h" @22
- class_specifier PrincipalJSONHandlerTypes @26-59
- enum_specifier State @28-52
- class_specifier PrincipalJSONHandler @88-108
- function_definition PrincipalJSONHandler @94-94
- function_definition ~PrincipalJSONHandler @95-95
- function_definition error @97-102
- function_definition Get @104-104
- function_definition SetErrorState @107-107

### caps/SharedJSONHandler.h

Blob: `febdcee1d5d1b0dd4a6f703b3d8c89fa447cb6bf`. Grammar: cpp. Status: syntax-clean.

- include "BasePrincipal.h" @8
- include "js/JSON.h" @9
- include "mozilla/RefPtr.h" @10
- class_specifier PrincipalJSONHandlerShared @15-63
- function_definition propertyName @23-27
- function_definition stringValue @29-33
- function_definition numberValue @35-39
- function_definition booleanValue @41-45
- function_definition nullValue @47-51
- function_definition error @53-55
- class_specifier ContainerPrincipalJSONHandler @70-107
- function_definition CallOnInner @96-101

### caps/SubsumedPrincipalJSONHandler.h

Blob: `dd7f59caff12021ed809b774fb9a182c4129ad2f`. Grammar: cpp. Status: syntax-clean.

- include <stddef.h> @8
- include <stdint.h> @9
- include "BasePrincipal.h" @11
- include "ContentPrincipalJSONHandler.h" @12
- include "NullPrincipalJSONHandler.h" @13
- include "SharedJSONHandler.h" @14
- include "js/TypeDecls.h" @15
- include "mozilla/RefPtr.h" @16
- include "mozilla/Variant.h" @17
- include "nsDebug.h" @18
- class_specifier SubsumedPrincipalJSONHandlerTypes @22-56
- enum_specifier State @24-50
- class_specifier SubsumedPrincipalJSONHandler @74-87
- function_definition SubsumedPrincipalJSONHandler @80-80
- function_definition ~SubsumedPrincipalJSONHandler @81-81
- function_definition HasAccepted @83-83
- function_definition SetErrorState @86-86

### caps/SystemPrincipal.cpp

Blob: `f4a54b806d7f3b1b66f46b893ef9b07cc1792daf`. Grammar: cpp. Status: contains-errors.

- include "SystemPrincipal.h" @7
- include "mozilla/ClearOnShutdown.h" @9
- include "nsCOMPtr.h" @10
- include "nsCRT.h" @11
- include "nsIClassInfoImpl.h" @12
- include "nsReadableUtils.h" @13
- include "nsString.h" @14
- include "nscore.h" @15
- include "pratom.h" @16
- function_definition SystemPrincipal @28-30
- function_definition Get @36-39
- function_definition Init @41-50
- function_definition Shutdown @52-57
- function_definition GetScriptLocation @59-62
- function_definition GetURI @68-72
- function_definition GetIsOriginPotentiallyTrustworthy @74-78
- function_definition GetDomain @80-84
- function_definition SetDomain @86-87
- function_definition GetBaseDomain @89-93
- function_definition GetAddonId @95-99
- function_definition Read @105-109
- function_definition Write @111-116

### caps/SystemPrincipal.h

Blob: `2e243bbf82329bfbe603b5c41dfb75ff667c2e29`. Grammar: cpp. Status: contains-errors.

- include "mozilla/BasePrincipal.h" @10
- include "nsIPrincipal.h" @11
- include "nsJSPrincipals.h" @12
- class_specifier nsScriptSecurityManager @18-18
- class_specifier SystemPrincipal @22-67
- function_definition Kind @28-28
- function_definition AddRef @30-32
- function_definition Release @33-35
- function_definition GetSiteIdentifier @48-51
- function_definition ~SystemPrincipal @56-56
- function_definition SubsumesInternal @61-64
- function_definition MayLoadInternal @66-66

### caps/nsJSPrincipals.cpp

Blob: `946b436702506efd042fef404440cc29eec87de2`. Grammar: cpp. Status: contains-errors.

- include "nsJSPrincipals.h" @5
- include "mozilla/BasePrincipal.h" @7
- include "mozilla/StaticPtr.h" @8
- include "mozilla/dom/StructuredCloneTags.h" @9
- include "mozilla/ipc/BackgroundUtils.h" @10
- include "mozilla/ipc/PBackgroundSharedTypes.h" @11
- include "nsCOMPtr.h" @12
- include "nsIPrincipal.h" @13
- include "nsString.h" @14
- include "xpcpublic.h" @15
- function_definition AddRef @22-27
- function_definition Release @30-39
- function_definition Subsume @42-47
- function_definition Destroy @50-71
- function_definition dump @76-88
- function_definition ReadPrincipals @93-110
- function_definition ReadPrincipalInfo @112-188
- function_definition ReadPrincipalInfo @190-256
- function_definition ReadPrincipalInfo @259-266
- function_definition ReadKnownPrincipalType @269-293
- function_definition WritePrincipalInfo @295-318
- function_definition WritePrincipalInfo @321-352
- function_definition write @354-362
- function_definition isSystemPrincipal @364-367
- function_definition isAddonPrincipal @369-372

### caps/nsJSPrincipals.h

Blob: `d4069f0ac3cd716ebd2491a2c95fe8dc3a6c8876`. Grammar: cpp. Status: contains-errors.

- include "js/Principals.h" @9
- include "nsIPrincipal.h" @10
- struct_specifier JSContext @12-12
- struct_specifier JSStructuredCloneReader @13-13
- struct_specifier JSStructuredCloneWriter @14-14
- class_specifier PrincipalInfo @18-18
- class_specifier nsJSPrincipals @22-80
- function_definition get @53-57
- function_definition get @58-62
- function_definition nsJSPrincipals @67-70
- function_definition ~nsJSPrincipals @79-79

### caps/nsScriptSecurityManager.cpp

Blob: `ddeb7ec7d138394043d3516502143fae7bbf16c2`. Grammar: cpp. Status: contains-errors.

- include "nsScriptSecurityManager.h" @5
- include <stdint.h> @7
- include "DomainPolicy.h" @9
- include "ExpandedPrincipal.h" @10
- include "SystemPrincipal.h" @11
- include "XPCWrapper.h" @12
- include "js/ColumnNumber.h" @13
- include "js/GCVector.h" @14
- include "js/Value.h" @15
- include "mozilla/BasePrincipal.h" @16
- include "mozilla/ClearOnShutdown.h" @17
- include "mozilla/Components.h" @18
- include "mozilla/ContentPrincipal.h" @19
- include "mozilla/ExtensionPolicyService.h" @20
- include "mozilla/NullPrincipal.h" @21
- include "mozilla/Preferences.h" @22
- include "mozilla/SourceLocation.h" @23
- include "mozilla/StaticPrefs_extensions.h" @24
- include "mozilla/StaticPrefs_security.h" @25
- include "mozilla/StaticPtr.h" @26
- include "mozilla/StoragePrincipalHelper.h" @27
- include "mozilla/dom/BindingUtils.h" @28
- include "mozilla/dom/ContentChild.h" @29
- include "mozilla/dom/ContentParent.h" @30
- include "mozilla/dom/Exceptions.h" @31
- include "mozilla/dom/PolicyContainer.h" @32
- include "mozilla/dom/ScriptSettings.h" @33
- include "mozilla/dom/TrustedTypeUtils.h" @34
- include "mozilla/dom/WorkerCommon.h" @35
- include "mozilla/dom/WorkerPrivate.h" @36
- include "mozilla/dom/nsCSPContext.h" @37
- include "nsAboutProtocolUtils.h" @38
- include "nsCRT.h" @39
- include "nsCRTGlue.h" @40
- include "nsContentSecurityUtils.h" @41
- include "nsContentUtils.h" @42
- include "nsDOMCID.h" @43
- include "nsDOMJSUtils.h" @44
- include "nsDirectoryServiceDefs.h" @45
- include "nsDocShell.h" @46
- include "nsError.h" @47
- include "nsGlobalWindowInner.h" @48
- include "nsIChromeRegistry.h" @49
- include "nsIClassInfo.h" @50
- include "nsIConsoleService.h" @51
- include "nsIContent.h" @52
- include "nsIContentSecurityPolicy.h" @53
- include "nsIDocShell.h" @54
- include "nsIEffectiveTLDService.h" @55
- include "nsILoadContext.h" @56
- include "nsILoadInfo.h" @57
- include "nsINestedURI.h" @58
- include "nsIOService.h" @59
- include "nsIResProtocolHandler.h" @60
- include "nsIScriptContext.h" @61
- include "nsIScriptError.h" @62
- include "nsIScriptGlobalObject.h" @63
- include "nsIScriptObjectPrincipal.h" @64
- include "nsIStringBundle.h" @65
- include "nsIURIFixup.h" @66
- include "nsIURIMutator.h" @67
- include "nsJSPrincipals.h" @68
- include "nsJSUtils.h" @69
- include "nsNetUtil.h" @70
- include "nsPIDOMWindow.h" @71
- include "nsPIDOMWindowInlines.h" @72
- include "nsString.h" @73
- include "nsTextFormatter.h" @74
- include "nspr.h" @75
- include "xpcpublic.h" @76
- class_specifier BundleHelper @89-140
- function_definition GetOrCreate @93-107
- function_definition Shutdown @109-112
- function_definition ~BundleHelper @115-115
- function_definition GetOrCreateInternal @117-134
- class_specifier nsAutoInPrincipalDomainOriginSetter @151-156
- function_definition nsAutoInPrincipalDomainOriginSetter @153-153
- function_definition ~nsAutoInPrincipalDomainOriginSetter @154-154
- function_definition GetOriginFromURI @159-192
- function_definition GetPrincipalDomainOrigin @194-205
- function_definition SetPendingExceptionASCII @207-209
- function_definition SetPendingException @211-214
- function_definition SecurityCompareURIs @217-221
- function_definition IsHttpOrHttpsAndCrossOrigin @223-233
- function_definition GetChannelResultPrincipal @244-249
- function_definition GetChannelResultPrincipalIfNotSandboxed @251-255
- function_definition GetChannelResultStoragePrincipal @257-277
- function_definition GetChannelResultPrincipals @279-300
- function_definition GetChannelResultPrincipal @302-386
- function_definition GetChannelURIPrincipal @399-441
- function_definition ContentSecurityPolicyPermitsJSAction @458-576
- function_definition JSPrincipalsSubsume @579-582
- function_definition CheckSameOriginURI @584-599
- function_definition CheckLoadURIFromScript @601-623
- function_definition DenyAccessIfURIHasFlags @631-643
- function_definition EqualOrSubdomain @645-669
- function_definition CheckLoadURIWithPrincipal @671-952
- function_definition CheckLoadURIFlags @963-1134
- function_definition ReportError @1136-1177
- function_definition ReportError @1179-1197
- function_definition CheckLoadURIStrWithPrincipal @1199-1251
- function_definition CheckLoadURIWithPrincipalFromJS @1253-1283
- function_definition CheckLoadURIStrWithPrincipalFromJS @1285-1293
- function_definition InFileURIAllowlist @1295-1309
- function_definition GetSystemPrincipal @1313-1318
- function_definition CreateContentPrincipal @1320-1332
- function_definition CreateContentPrincipalFromOrigin @1334-1349
- function_definition PrincipalToJSON @1351-1366
- function_definition JSONToPrincipal @1368-1383
- function_definition CreateNullPrincipal @1385-1396
- function_definition GetLoadContextContentPrincipal @1398-1409
- function_definition GetDocShellContentPrincipal @1411-1418
- function_definition PrincipalWithOA @1420-1446
- function_definition CanCreateWrapper @1448-1500
- function_definition CanCreateInstance @1502-1515
- function_definition CanGetService @1517-1530
- function_definition nsScriptSecurityManager @1543-1549
- function_definition Init @1551-1564
- function_definition InitJSCallbacks @1566-1581
- function_definition ClearJSCallbacks @1584-1587
- function_definition ~nsScriptSecurityManager @1591-1601
- function_definition Shutdown @1603-1607
- function_definition GetScriptSecurityManager @1609-1611
- function_definition InitStatics @1614-1623
- function_definition SystemPrincipalSingletonConstructor @1628-1634
- struct_specifier IsWhitespace @1636-1638
- function_definition Test @1637-1637
- struct_specifier IsWhitespaceOrComma @1639-1643
- function_definition Test @1640-1642
- function_definition SkipPast @1646-1651
- function_definition SkipUntil @1654-1659
- function_definition ScriptSecurityPrefChanged @1662-1666
- function_definition ScriptSecurityPrefChanged @1668-1676
- function_definition AddSitesToFileURIAllowlist @1678-1711
- function_definition InitPrefs @1713-1727
- function_definition GetDomainPolicyActive @1729-1733
- function_definition ActivateDomainPolicy @1735-1742
- function_definition ActivateDomainPolicyInternal @1744-1756
- function_definition DeactivateDomainPolicy @1760-1762
- function_definition CloneDomainPolicy @1764-1771
- function_definition PolicyAllowsScript @1773-1811
- function_definition (anonymous) @1813-1854

### caps/nsScriptSecurityManager.h

Blob: `025938b4843356a83a05dc6557a2a45fd3817f33`. Grammar: cpp. Status: contains-errors.

- include <stdint.h> @8
- include "js/TypeDecls.h" @10
- include "mozilla/Maybe.h" @11
- include "nsCOMPtr.h" @12
- include "nsIPrincipal.h" @13
- include "nsIScriptSecurityManager.h" @14
- include "nsServiceManagerUtils.h" @15
- include "nsStringFwd.h" @16
- class_specifier nsIIOService @18-18
- class_specifier nsIStringBundle @19-19
- class_specifier OriginAttributes @22-22
- class_specifier SystemPrincipal @23-23
- enum_specifier RuntimeCode @27-27
- enum_specifier CompilationType @28-28
- class_specifier nsScriptSecurityManager @37-136
- function_definition GetStrictFileOriginPolicy @77-77

### caps/tests/gtest/TestBackgroundThreadPrincipal.cpp

Blob: `fbafb2897e5d05eb6c241144e486fed5badf050e`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "mozilla/BasePrincipal.h" @5
- include "mozilla/ContentPrincipal.h" @6
- include "mozilla/NullPrincipal.h" @7
- include "mozilla/gtest/MozAssertions.h" @8
- include "mozilla/ipc/BackgroundUtils.h" @9
- include "mozilla/ipc/PBackgroundSharedTypes.h" @10
- include "nsIEventTarget.h" @11
- include "nsISerialEventTarget.h" @12
- include "nsIURIMutator.h" @13
- include "nsNetUtil.h" @14
- include "nsPrintfCString.h" @15
- include "nsThreadUtils.h" @16
- function_definition RunOnBackgroundThread @21-29
- function_definition TEST @31-49
- function_definition TEST @51-65
- function_definition TEST @67-92

### caps/tests/gtest/TestNullPrincipalPrecursor.cpp

Blob: `f3103c1a9d9083a0b5d32ba8c8746a1c2fb12d9d`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "mozilla/NullPrincipal.h" @5
- include "mozilla/gtest/MozAssertions.h" @6
- include "nsIURI.h" @7
- include "nsIURIMutator.h" @8
- include "nsPrintfCString.h" @9
- function_definition TEST @13-55

### caps/tests/gtest/TestOriginAttributes.cpp

Blob: `bf2b619902592b968099cba25d72d4b3ac21762e`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "mozilla/BasePrincipal.h" @5
- include "mozilla/NullPrincipal.h" @6
- include "mozilla/Preferences.h" @7
- include "nsNetUtil.h" @8
- function_definition TestSuffix @21-30
- function_definition TestFPD @32-40
- function_definition TEST @42-46
- function_definition TEST @48-60
- function_definition TEST @62-79
- function_definition TEST @85-117
- function_definition TEST @119-154
- function_definition TEST @156-191

### caps/tests/gtest/TestPrincipalAttributes.cpp

Blob: `9ed1f3199b674deb310ea7a68623aaaee687d8f3`. Grammar: cpp. Status: contains-errors.

- include "gtest/gtest.h" @4
- include "mozilla/BasePrincipal.h" @5
- include "nsScriptSecurityManager.h" @6
- class_specifier PrincipalAttributesParam @10-14
- class_specifier PrincipalAttributesTest @16-17
- function_definition TEST_P @19-30

### caps/tests/gtest/TestPrincipalHash.cpp

Blob: `1e57453367cbc4c03a82526d161c1475df3ad9f1`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "mozilla/gtest/MozAssertions.h" @5
- include "nsIPrincipal.h" @6
- include "nsNetUtil.h" @7
- include "nsScriptSecurityManager.h" @8
- function_definition TEST @10-28

### caps/tests/gtest/TestPrincipalSerialization.cpp

Blob: `48cda59107404065f05606769a72869229ad58a5`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "mozilla/Base64.h" @5
- include "mozilla/BasePrincipal.h" @6
- include "mozilla/ContentPrincipal.h" @7
- include "mozilla/ExpandedPrincipal.h" @8
- include "mozilla/NullPrincipal.h" @9
- include "mozilla/SystemPrincipal.h" @10
- function_definition TEST @22-47
- function_definition TEST @51-69
- function_definition TEST @73-129
- function_definition TEST @131-192

### caps/tests/gtest/TestRedirectChainURITruncation.cpp

Blob: `ccad5ee9243e64c17ca827dbe561be80bc76ba79`. Grammar: cpp. Status: contains-errors.

- include "gtest/gtest.h" @4
- include "mozilla/BasePrincipal.h" @5
- include "mozilla/ContentPrincipal.h" @6
- include "mozilla/ExpandedPrincipal.h" @7
- include "mozilla/LoadInfo.h" @8
- include "mozilla/NullPrincipal.h" @9
- include "mozilla/SystemPrincipal.h" @10
- include "nsContentUtils.h" @11
- function_definition checkPrincipalTruncation @15-79
- function_definition checkPrincipalTruncation @81-84
- function_definition TEST @86-157
- function_definition TEST @159-183
- function_definition TEST @185-191
- function_definition TEST @193-229

### caps/tests/gtest/TestScriptSecurityManager.cpp

Blob: `b3ac29da4b7d4b26de8a58d4681295066bada108`. Grammar: cpp. Status: syntax-clean.

- include "gtest/gtest.h" @4
- include "nsCOMPtr.h" @5
- include "nsIURI.h" @6
- include "nsNetUtil.h" @7
- include "nsScriptSecurityManager.h" @8
- function_definition TEST @12-47

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
