<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["security/sandbox/mac/SandboxPolicyHWInference.h", "security/sandbox/mac/SandboxPolicyPGO.h", "security/sandbox/mac/SandboxPolicyRDD.h", "security/sandbox/mac/SandboxPolicySocket.h", "security/sandbox/mac/SandboxPolicyUtility.h", "security/sandbox/win/SandboxInitialization.cpp", "security/sandbox/win/SandboxInitialization.h", "security/sandbox/win/gtest/TestConfigHelpers.cpp", "security/sandbox/win/src/sandboxbroker/ConfigHelpers.cpp", "security/sandbox/win/src/sandboxbroker/ConfigHelpers.h", "security/sandbox/win/src/sandboxbroker/sandboxBroker.cpp", "security/sandbox/win/src/sandboxbroker/sandboxBroker.h", "security/sandbox/win/src/sandboxtarget/TargetGeckoServicesImpl.cpp", "security/sandbox/win/src/sandboxtarget/TargetGeckoServicesImpl.h", "security/sandbox/win/src/sandboxtarget/sandboxTarget.cpp", "security/sandbox/win/src/sandboxtarget/sandboxTarget.h"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/security native and TypeScript syntax map 232

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### security/sandbox/mac/SandboxPolicyHWInference.h

Blob: `db90e7bbc8553a22e13eec070700b51c64e553bf`. Grammar: cpp. Status: syntax-clean.


### security/sandbox/mac/SandboxPolicyPGO.h

Blob: `29b01ba1351e9c558df5c9fd8af89e077b4517d5`. Grammar: cpp. Status: syntax-clean.


### security/sandbox/mac/SandboxPolicyRDD.h

Blob: `99a17344a501e015e92ba956546f0e012918dcc4`. Grammar: cpp. Status: syntax-clean.


### security/sandbox/mac/SandboxPolicySocket.h

Blob: `ea1eb587a0c3e6149ed1ba349e9442210f70f348`. Grammar: cpp. Status: syntax-clean.


### security/sandbox/mac/SandboxPolicyUtility.h

Blob: `bcac56bca5a3d925643afb1f3c7199a942d6fb76`. Grammar: cpp. Status: syntax-clean.


### security/sandbox/win/SandboxInitialization.cpp

Blob: `32b4d048cd575f15ef25bcde05a7d3b1412bfaa9`. Grammar: cpp. Status: contains-errors.

- include "SandboxInitialization.h" @5
- include "base/memory/ref_counted.h" @7
- include "mozilla/DebugOnly.h" @8
- include "mozilla/WindowsProcessMitigations.h" @9
- include "nsWindowsDllInterceptor.h" @10
- include "sandbox/win/src/process_mitigations.h" @11
- include "sandbox/win/src/sandbox_factory.h" @12
- function_definition ThreadLocalStorageIsInitialized @17-20
- function_definition patched_CloseHandle @32-41
- function_definition patched_DuplicateHandle @43-59
- function_definition patched_ApiSetQueryApiSetPresence @69-79
- function_definition EnableHandleCloseMonitoring @84-99
- function_definition EnableApiQueryInterception @108-118
- function_definition ShouldDisableHandleVerifier @120-129
- function_definition InitializeHandleVerifier @131-137
- function_definition InitializeTargetServices @139-156
- function_definition GetInitializedTargetServices @158-163
- function_definition LowerSandbox @165-165
- class_specifier BrokerServicesDelegateImpl @167-189
- function_definition ParallelLaunchPostTaskAndReplyWithResult @170-178
- function_definition BeforeTargetProcessCreateOnCreationThread @180-181
- function_definition AfterTargetProcessCreateOnCreationThread @183-184
- function_definition OnCreateThreadActionCreateFailure @186-186
- function_definition OnCreateThreadActionDuplicateFailure @188-188
- function_definition InitializeBrokerServices @191-219
- function_definition GetInitializedBrokerServices @221-226
- function_definition ApplyParentProcessMitigations @228-234

### security/sandbox/win/SandboxInitialization.h

Blob: `55f46a139ea638e54359b17549ed9a2e8bc0c528`. Grammar: cpp. Status: syntax-clean.

- class_specifier BrokerServices @9-9
- class_specifier TargetServices @10-10

### security/sandbox/win/gtest/TestConfigHelpers.cpp

Blob: `bb7279a27c9a18df0b8533311b6e345d96cdf7b9`. Grammar: cpp. Status: contains-errors.

- include <windows.h> @5
- include <string> @7
- include "gmock/gmock.h" @9
- include "gtest/gtest.h" @10
- include "nsLiteralString.h" @11
- include "nsWindowsHelpers.h" @12
- include "sandbox/win/src/app_container.h" @13
- include "sandbox/win/src/policy_engine_opcodes.h" @14
- include "sandbox/win/src/sandbox.h" @15
- include "../src/sandboxbroker/ConfigHelpers.h" @18
- class_specifier MockConfig @47-95
- function_definition SetUpPathsInKey @105-113
- class_specifier UserFontConfigHelperTest @115-151
- function_definition UserFontConfigHelperTest @118-125
- function_definition ~UserFontConfigHelperTest @127-132
- function_definition SetUpPaths @134-136
- function_definition CreateHelperAndCallAddRules @138-144
- function_definition TEST_F @153-159
- function_definition TEST_F @161-169
- function_definition TEST_F @171-178
- function_definition TEST_F @180-190
- function_definition TEST_F @192-209
- function_definition TEST_F @211-229
- function_definition TEST_F @231-256
- function_definition TEST_F @258-271
- function_definition TEST_F @273-285
- function_definition TEST_F @287-295
- function_definition TEST_F @297-307
- function_definition TEST_F @309-315
- function_definition TEST_F @317-329
- function_definition TEST_F @331-345
- function_definition TEST_F @347-362
- function_definition RuleSize @364-367
- function_definition MakeLongFontPath @369-393
- function_definition TEST_F @395-412
- function_definition TEST_F @414-433

### security/sandbox/win/src/sandboxbroker/ConfigHelpers.cpp

Blob: `967d7517c795bb4014e52e376454540e7a5ccdff`. Grammar: cpp. Status: syntax-clean.

- include "ConfigHelpers.h" @5
- include <windows.h> @7
- include "mozilla/Logging.h" @9
- include "mozilla/UniquePtrExtensions.h" @10
- include "mozilla/Vector.h" @11
- include "nsExceptionHandler.h" @12
- include "nsStringFwd.h" @13
- include "nsUnicharUtils.h" @14
- include "nsWindowsHelpers.h" @15
- include "sandbox/win/src/policy_engine_opcodes.h" @16
- function_definition ContainsSandboxWildcard @29-36
- function_definition SizeTrackingConfig @40-54
- function_definition AllowFileAccess @56-98
- function_definition UserFontConfigHelper @100-114
- function_definition ~UserFontConfigHelper @116-120
- function_definition AddRulesForKey @122-237
- function_definition AddRules @239-320

### security/sandbox/win/src/sandboxbroker/ConfigHelpers.h

Blob: `95cf39bfa8119fb0367f6a4bbdc67001a32eba0e`. Grammar: cpp. Status: contains-errors.

- include <minwindef.h> @8
- include "mozilla/Attributes.h" @10
- include "nsStringFwd.h" @11
- include "sandbox/win/src/sandbox_policy.h" @12
- class_specifier TargetPolicy @15-15
- class_specifier SizeTrackingConfig @21-32
- function_definition class @34-52
- function_definition UserFontConfigHelper @44-44

### security/sandbox/win/src/sandboxbroker/sandboxBroker.cpp

Blob: `74c0e5486b855849ca9298ae08ab0f32d0d61cb6`. Grammar: cpp. Status: syntax-clean.

- include "sandboxBroker.h" @7
- include <aclapi.h> @9
- include <sddl.h> @10
- include <shlobj.h> @11
- include <string> @13
- include "ConfigHelpers.h" @15
- include "GfxDriverInfo.h" @16
- include "WinUtils.h" @17
- include "base/win/sid.h" @18
- include "base/win/windows_version.h" @19
- include "mozilla/Assertions.h" @20
- include "mozilla/ClearOnShutdown.h" @21
- include "mozilla/Components.h" @22
- include "mozilla/ImportDir.h" @23
- include "mozilla/Logging.h" @24
- include "mozilla/NSPRLogModulesParser.h" @25
- include "mozilla/Omnijar.h" @26
- include "mozilla/Preferences.h" @27
- include "mozilla/SHA1.h" @28
- include "mozilla/SandboxSettings.h" @29
- include "mozilla/StaticPrefs_media.h" @30
- include "mozilla/StaticPrefs_security.h" @31
- include "mozilla/StaticPtr.h" @32
- include "mozilla/UniquePtr.h" @33
- include "mozilla/WinDllServices.h" @34
- include "mozilla/WindowsVersion.h" @35
- include "mozilla/glean/SecuritySandboxMetrics.h" @36
- include "mozilla/ipc/LaunchError.h" @37
- include "mozilla/ipc/UtilityProcessSandboxing.h" @38
- include "nsAppDirectoryServiceDefs.h" @39
- include "nsCOMPtr.h" @40
- include "nsDirectoryServiceDefs.h" @41
- include "nsIFile.h" @42
- include "nsIGfxInfo.h" @43
- include "nsIProperties.h" @44
- include "nsIXULRuntime.h" @45
- include "nsServiceManagerUtils.h" @46
- include "nsString.h" @47
- include "nsTArray.h" @48
- include "nsTHashtable.h" @49
- include "sandbox/win/src/app_container.h" @50
- include "sandbox/win/src/sandbox.h" @51
- include "sandbox/win/src/security_level.h" @52
- function_definition AddWin32kLockdownConfig @100-120
- function_definition CacheAndStandardizeDir @122-131
- function_definition Initialize @134-160
- function_definition CacheDirectoryServiceDir @162-178
- function_definition AddCachedDirRule @181-202
- function_definition EnsureWindowsDirCached @204-235
- function_definition AddCachedWindowsDirRule @238-281
- function_definition GeckoDependentInitialize @284-307
- function_definition SandboxBroker @309-316
- function_definition AddMozLogRulesToConfig @320-368
- function_definition AddDeveloperRepoDirToConfig @370-398
- function_definition AddLLVMProfilePathDirectoryToPolicy @403-410
- function_definition EnsureAppLockerAccess @415-442
- function_definition LaunchApp @444-638
- function_definition (anonymous) @645-661
- function_definition AllowProxyLoadFromBinDir @663-670
- function_definition AddCigToConfig @672-724
- function_definition DynamicCodeFlagForSystemMediaLibraries @734-749
- function_definition GetProcessUserSidString @751-773
- function_definition HexEncode @777-788
- function_definition EnsureLpacPermsissionsOnDir @794-877
- function_definition IsLowPrivilegedAppContainerSupported @879-883
- function_definition AddAndConfigureAppContainerProfile @890-958
- function_definition AddShaderCachesToPolicy @961-1012
- function_definition SetSecurityLevelForContentProcess @1014-1333
- function_definition SetSecurityLevelForGPUProcess @1335-1428
- function_definition SetSecurityLevelForRDDProcess @1436-1506
- function_definition SetSecurityLevelForSocketProcess @1508-1579
- struct_specifier UtilitySandboxProps @1582-1620
- struct_specifier GenericUtilitySandboxProps @1622-1622
- struct_specifier UtilityAudioDecodingWmfSandboxProps @1624-1637
- function_definition UtilityAudioDecodingWmfSandboxProps @1625-1636
- struct_specifier UtilityMfMediaEngineCdmSandboxProps @1640-1688
- function_definition UtilityMfMediaEngineCdmSandboxProps @1641-1687
- struct_specifier WindowsUtilitySandboxProps @1691-1705
- function_definition WindowsUtilitySandboxProps @1692-1704
- function_definition LogUtilitySandboxProps @1722-1769
- function_definition BuildUtilitySandbox @1771-1847
- function_definition SetSecurityLevelForUtilityProcess @1849-1894
- function_definition SetSecurityLevelForGMPlugin @1896-2045
- function_definition AllowReadFile @2048-2061
- function_definition AddHandleToShare @2063-2065
- function_definition IsWin32kLockedDown @2067-2070
- function_definition ApplyLoggingConfig @2072-2080
- function_definition ~SandboxBroker @2082-2082

### security/sandbox/win/src/sandboxbroker/sandboxBroker.h

Blob: `9643dfe01cc78433ef5a54d38f9149b5c7f380aa`. Grammar: cpp. Status: syntax-clean.

- include <stdint.h> @8
- include <windows.h> @9
- include "mozilla/Result.h" @11
- include "mozilla/ipc/EnvironmentMap.h" @12
- include "mozilla/ipc/LaunchError.h" @13
- include "mozilla/ipc/UtilityProcessSandboxing.h" @14
- include "nsCOMPtr.h" @15
- include "nsISupportsImpl.h" @16
- include "nsXULAppAPI.h" @17
- class_specifier BrokerServices @20-20
- class_specifier TargetPolicy @21-21
- enum_specifier GMPSandboxKind @26-26
- class_specifier SandboxBroker @28-80

### security/sandbox/win/src/sandboxtarget/TargetGeckoServicesImpl.cpp

Blob: `3402e2ccb2dabc40db3c784f3565028d3bb8a063`. Grammar: cpp. Status: syntax-clean.

- include "TargetGeckoServicesImpl.h" @5
- include "mozilla/Logging.h" @7
- include "mozilla/ProfilerMarkers.h" @8
- include "mozilla/sandboxing/TargetGeckoServices.h" @9
- include "nsString.h" @10
- struct_specifier SandboxSyscall @18-31
- function_definition MarkIntervalStart @37-40
- function_definition MarkIntervalEnd @42-46
- function_definition MarkSyscallBrokeringIntervalEnd @48-73
- function_definition InitTargetGeckoServices @75-85

### security/sandbox/win/src/sandboxtarget/TargetGeckoServicesImpl.h

Blob: `a06436cfc4dfeed9f64c71b16b2b516d8c969268`. Grammar: cpp. Status: syntax-clean.

- include "mozilla/sandboxing/TargetGeckoServices.h" @8

### security/sandbox/win/src/sandboxtarget/sandboxTarget.cpp

Blob: `2575763624320b2d3023e24cd4a6f596b4941995`. Grammar: cpp. Status: syntax-clean.

- include "sandboxTarget.h" @5
- include "mozilla/CpuInfo.h" @7
- include "mozilla/SandboxSettings.h" @8
- include "mozilla/WindowsStackWalkInitialization.h" @9
- include "sandbox/win/src/sandbox.h" @10
- function_definition Instance @17-20
- function_definition StartSandbox @22-33
- function_definition LowerContentSandbox @35-45
- function_definition NotifyStartObservers @47-57

### security/sandbox/win/src/sandboxtarget/sandboxTarget.h

Blob: `092c3b5b1355dc10c5fcfed407946bcfe86107ec`. Grammar: cpp. Status: syntax-clean.

- include <windows.h> @8
- include <functional> @10
- include <list> @11
- include <utility> @12
- include "mozilla/Assertions.h" @14
- class_specifier TargetServices @17-17
- class_specifier SandboxTarget @22-70
- function_definition SetTargetServices @36-42
- function_definition IsSandboxed @44-44
- function_definition RegisterSandboxStartCallback @47-49
- function_definition SandboxTarget @63-63

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
