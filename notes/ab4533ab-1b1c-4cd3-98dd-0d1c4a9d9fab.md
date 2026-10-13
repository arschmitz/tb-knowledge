<!-- knowledge: {"repository":"thunderbird","at":"2026-10-13T04:22:06.018534+00:00","paths":["third_party"],"source":{"reference":"Git commit 87d0159c7149a43253964c2cb6917939557dc799","revision":"87d0159c7149a43253964c2cb6917939557dc799","status":"provisional","study":"architecture-study-20261013","portableCopies":["9b82c28ff094bb3b4a59502ced522e7015cfa856b2c4aaca06ef5277725d50f2"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/554dea11-c531-4502-aa42-b776ac0d93b6.md"}} -->
# thunderbird/third_party native and TypeScript syntax map 128

Revision: `87d0159c7149a43253964c2cb6917939557dc799`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### third_party/rust/winapi/src/um/winspool.rs

Blob: `c6796caf3472a59e056d605a2a70db39b67ac137`. Grammar: rust. Status: syntax-clean.

- function_signature_item EnumPrintersA @914-922
- function_signature_item EnumPrintersW @923-931
- function_signature_item GetSpoolFileHandle @958-960
- function_signature_item CommitSpoolData @961-965
- function_signature_item CloseSpoolFileHandle @966-969
- function_signature_item OpenPrinterA @970-974
- function_signature_item OpenPrinterW @975-979
- function_signature_item ResetPrinterA @980-983
- function_signature_item ResetPrinterW @984-987
- function_signature_item SetJobA @988-994
- function_signature_item SetJobW @995-1001
- function_signature_item GetJobA @1002-1009
- function_signature_item GetJobW @1010-1017
- function_signature_item EnumJobsA @1018-1027
- function_signature_item EnumJobsW @1028-1037
- function_signature_item AddPrinterA @1038-1042
- function_signature_item AddPrinterW @1043-1047
- function_signature_item DeletePrinter @1048-1050
- function_signature_item SetPrinterA @1051-1056
- function_signature_item SetPrinterW @1057-1062
- function_signature_item GetPrinterA @1063-1069
- function_signature_item GetPrinterW @1070-1076
- function_signature_item AddPrinterDriverA @1077-1081
- function_signature_item AddPrinterDriverW @1082-1086
- function_signature_item AddPrinterDriverExA @1087-1092
- function_signature_item AddPrinterDriverExW @1093-1098
- function_signature_item EnumPrinterDriversA @1099-1107
- function_signature_item EnumPrinterDriversW @1108-1116
- function_signature_item GetPrinterDriverA @1117-1124
- function_signature_item GetPrinterDriverW @1125-1132
- function_signature_item GetPrinterDriverDirectoryA @1133-1140
- function_signature_item GetPrinterDriverDirectoryW @1141-1148
- function_signature_item DeletePrinterDriverA @1149-1153
- function_signature_item DeletePrinterDriverW @1154-1158
- function_signature_item DeletePrinterDriverExA @1159-1165
- function_signature_item DeletePrinterDriverExW @1166-1172
- function_signature_item AddPrintProcessorA @1173-1178
- function_signature_item AddPrintProcessorW @1179-1184
- function_signature_item EnumPrintProcessorsA @1185-1193
- function_signature_item EnumPrintProcessorsW @1194-1202
- function_signature_item GetPrintProcessorDirectoryA @1203-1210
- function_signature_item GetPrintProcessorDirectoryW @1211-1218
- function_signature_item EnumPrintProcessorDatatypesA @1219-1227
- function_signature_item EnumPrintProcessorDatatypesW @1228-1236
- function_signature_item DeletePrintProcessorA @1237-1241
- function_signature_item DeletePrintProcessorW @1242-1246
- function_signature_item StartDocPrinterA @1247-1251
- function_signature_item StartDocPrinterW @1252-1256
- function_signature_item StartPagePrinter @1257-1259
- function_signature_item WritePrinter @1260-1265
- function_signature_item FlushPrinter @1266-1272
- function_signature_item EndPagePrinter @1273-1275
- function_signature_item AbortPrinter @1276-1278
- function_signature_item ReadPrinter @1279-1284
- function_signature_item EndDocPrinter @1285-1287
- function_signature_item AddJobA @1288-1294
- function_signature_item AddJobW @1295-1301
- function_signature_item ScheduleJob @1302-1305
- function_signature_item PrinterProperties @1306-1309
- function_signature_item DocumentPropertiesA @1310-1317
- function_signature_item DocumentPropertiesW @1318-1325
- function_signature_item AdvancedDocumentPropertiesA @1326-1332
- function_signature_item AdvancedDocumentPropertiesW @1333-1339
- function_signature_item ExtDeviceMode @1340-1349
- function_signature_item GetPrinterDataA @1350-1357
- function_signature_item GetPrinterDataW @1358-1365
- function_signature_item GetPrinterDataExA @1366-1374
- function_signature_item GetPrinterDataExW @1375-1383
- function_signature_item EnumPrinterDataA @1384-1394
- function_signature_item EnumPrinterDataW @1395-1405
- function_signature_item EnumPrinterDataExA @1406-1413
- function_signature_item EnumPrinterDataExW @1414-1421
- function_signature_item EnumPrinterKeyA @1422-1428
- function_signature_item EnumPrinterKeyW @1429-1435
- function_signature_item SetPrinterDataA @1436-1442
- function_signature_item SetPrinterDataW @1443-1449
- function_signature_item SetPrinterDataExA @1450-1457
- function_signature_item SetPrinterDataExW @1458-1465
- function_signature_item DeletePrinterDataA @1466-1469
- function_signature_item DeletePrinterDataW @1470-1473
- function_signature_item DeletePrinterDataExA @1474-1478
- function_signature_item DeletePrinterDataExW @1479-1483
- function_signature_item DeletePrinterKeyA @1484-1487
- function_signature_item DeletePrinterKeyW @1488-1491
- function_signature_item WaitForPrinterChange @1688-1691
- function_signature_item FindFirstPrinterChangeNotification @1692-1697
- function_signature_item FindNextPrinterChangeNotification @1698-1703
- function_signature_item FreePrinterNotifyInfo @1704-1706
- function_signature_item FindClosePrinterChangeNotification @1707-1709
- function_signature_item PrinterMessageBoxA @1740-1747
- function_signature_item PrinterMessageBoxW @1748-1755
- function_signature_item ClosePrinter @1764-1766
- function_signature_item AddFormA @1767-1771
- function_signature_item AddFormW @1772-1776
- function_signature_item DeleteFormA @1777-1780
- function_signature_item DeleteFormW @1781-1784
- function_signature_item GetFormA @1785-1792
- function_signature_item GetFormW @1793-1800
- function_signature_item SetFormA @1801-1806
- function_signature_item SetFormW @1807-1812
- function_signature_item EnumFormsA @1813-1820
- function_signature_item EnumFormsW @1821-1828
- function_signature_item EnumMonitorsA @1829-1836
- function_signature_item EnumMonitorsW @1837-1844
- function_signature_item AddMonitorA @1845-1849
- function_signature_item AddMonitorW @1850-1854
- function_signature_item DeleteMonitorA @1855-1859
- function_signature_item DeleteMonitorW @1860-1864
- function_signature_item EnumPortsA @1865-1872
- function_signature_item EnumPortsW @1873-1880
- function_signature_item AddPortA @1881-1885
- function_signature_item AddPortW @1886-1890
- function_signature_item ConfigurePortA @1891-1895
- function_signature_item ConfigurePortW @1896-1900
- function_signature_item DeletePortA @1901-1905
- function_signature_item DeletePortW @1906-1910
- function_signature_item XcvDataW @1911-1920
- function_signature_item GetDefaultPrinterA @1921-1924
- function_signature_item GetDefaultPrinterW @1925-1928
- function_signature_item SetDefaultPrinterA @1929-1931
- function_signature_item SetDefaultPrinterW @1932-1934
- function_signature_item SetPortA @1935-1940
- function_signature_item SetPortW @1941-1945
- function_signature_item AddPrinterConnectionA @1946-1948
- function_signature_item AddPrinterConnectionW @1949-1951
- function_signature_item DeletePrinterConnectionA @1952-1954
- function_signature_item DeletePrinterConnectionW @1955-1957
- function_signature_item ConnectToPrinterDlg @1958-1961
- function_signature_item AddPrintProvidorA @1988-1992
- function_signature_item AddPrintProvidorW @1993-1997
- function_signature_item DeletePrintProvidorA @1998-2002
- function_signature_item DeletePrintProvidorW @2003-2007
- function_signature_item IsValidDevmodeA @2008-2011
- function_signature_item IsValidDevmodeW @2012-2015
- function_signature_item OpenPrinter2A @2149-2154
- function_signature_item OpenPrinter2W @2155-2160
- function_signature_item AddPrinterConnection2A @2177-2182
- function_signature_item AddPrinterConnection2W @2183-2188
- function_signature_item InstallPrinterDriverFromPackageA @2192-2198
- function_signature_item InstallPrinterDriverFromPackageW @2199-2205
- function_signature_item UploadPrinterDriverPackageA @2211-2219
- function_signature_item UploadPrinterDriverPackageW @2220-2228
- function_signature_item GetCorePrinterDriversA @2245-2251
- function_signature_item GetCorePrinterDriversW @2252-2258
- function_signature_item CorePrinterDriverInstalledA @2259-2266
- function_signature_item CorePrinterDriverInstalledW @2267-2274
- function_signature_item GetPrinterDriverPackagePathA @2275-2283
- function_signature_item GetPrinterDriverPackagePathW @2284-2292
- function_signature_item DeletePrinterDriverPackageA @2293-2297
- function_signature_item DeletePrinterDriverPackageW @2298-2302
- function_signature_item ReportJobProcessingProgress @2357-2362
- function_signature_item GetPrinterDriver2A @2363-2371
- function_signature_item GetPrinterDriver2W @2372-2380
- function_signature_item GetPrintExecutionData @2394-2396
- function_signature_item GetJobNamedPropertyValue @2397-2402
- function_signature_item FreePrintPropertyValue @2403-2405
- function_signature_item FreePrintNamedPropertyArray @2406-2409
- function_signature_item SetJobNamedProperty @2410-2414
- function_signature_item DeleteJobNamedProperty @2415-2419
- function_signature_item EnumJobNamedProperties @2420-2425
- function_signature_item GetPrintOutputInfo @2426-2431

### third_party/rust/winapi/src/um/winsvc.rs

Blob: `baa2a8b84275861e2413c828796368248ca56f2c`. Grammar: rust. Status: syntax-clean.

- function_signature_item ChangeServiceConfigA @373-385
- function_signature_item ChangeServiceConfigW @386-398
- function_signature_item ChangeServiceConfig2A @399-403
- function_signature_item ChangeServiceConfig2W @404-408
- function_signature_item CloseServiceHandle @409-411
- function_signature_item ControlService @412-416
- function_signature_item CreateServiceA @417-431
- function_signature_item CreateServiceW @432-446
- function_signature_item DeleteService @447-449
- function_signature_item EnumDependentServicesA @450-457
- function_signature_item EnumDependentServicesW @458-465
- function_signature_item EnumServicesStatusA @466-475
- function_signature_item EnumServicesStatusW @476-485
- function_signature_item EnumServicesStatusExA @486-497
- function_signature_item EnumServicesStatusExW @498-509
- function_signature_item GetServiceKeyNameA @510-515
- function_signature_item GetServiceKeyNameW @516-521
- function_signature_item GetServiceDisplayNameA @522-527
- function_signature_item GetServiceDisplayNameW @528-533
- function_signature_item LockServiceDatabase @534-536
- function_signature_item NotifyBootConfigStatus @537-539
- function_signature_item OpenSCManagerA @540-544
- function_signature_item OpenSCManagerW @545-549
- function_signature_item OpenServiceA @550-554
- function_signature_item OpenServiceW @555-559
- function_signature_item QueryServiceConfigA @560-565
- function_signature_item QueryServiceConfigW @566-571
- function_signature_item QueryServiceConfig2A @572-578
- function_signature_item QueryServiceConfig2W @579-585
- function_signature_item QueryServiceLockStatusA @586-591
- function_signature_item QueryServiceLockStatusW @592-597
- function_signature_item QueryServiceObjectSecurity @598-604
- function_signature_item QueryServiceStatus @605-608
- function_signature_item QueryServiceStatusEx @609-615
- function_signature_item RegisterServiceCtrlHandlerA @616-619
- function_signature_item RegisterServiceCtrlHandlerW @620-623
- function_signature_item RegisterServiceCtrlHandlerExA @624-628
- function_signature_item RegisterServiceCtrlHandlerExW @629-633
- function_signature_item SetServiceObjectSecurity @634-638
- function_signature_item SetServiceStatus @639-642
- function_signature_item StartServiceCtrlDispatcherA @643-645
- function_signature_item StartServiceCtrlDispatcherW @646-648
- function_signature_item StartServiceA @649-653
- function_signature_item StartServiceW @654-658
- function_signature_item UnlockServiceDatabase @659-661
- function_signature_item NotifyServiceStatusChangeA @662-666
- function_signature_item NotifyServiceStatusChangeW @667-671
- function_signature_item ControlServiceExA @672-677
- function_signature_item ControlServiceExW @678-683
- function_signature_item QueryServiceDynamicInformation @684-688
- function_signature_item WaitServiceState @689-694

### third_party/rust/winapi/src/um/wintrust.rs

Blob: `867e12e46aa92491e98038b7da90b19e6ef92c6a`. Grammar: rust. Status: syntax-clean.

- function_signature_item WinVerifyTrust @83-83

### third_party/rust/winapi/src/um/winusb.rs

Blob: `c72e36833a25dbe2fbe986276629872d7e9a3135`. Grammar: rust. Status: syntax-clean.

- function_signature_item WinUsb_Initialize @26-29
- function_signature_item WinUsb_Free @30-32
- function_signature_item WinUsb_GetAssociatedInterface @33-37
- function_signature_item WinUsb_GetDescriptor @38-46
- function_signature_item WinUsb_QueryInterfaceSettings @47-51
- function_signature_item WinUsb_QueryDeviceInformation @52-57
- function_signature_item WinUsb_SetCurrentAlternateSetting @58-61
- function_signature_item WinUsb_GetCurrentAlternateSetting @62-65
- function_signature_item WinUsb_QueryPipe @66-71
- function_signature_item WinUsb_QueryPipeEx @72-77
- function_signature_item WinUsb_SetPipePolicy @78-84
- function_signature_item WinUsb_GetPipePolicy @85-91
- function_signature_item WinUsb_ReadPipe @92-99
- function_signature_item WinUsb_WritePipe @100-107
- function_signature_item WinUsb_ControlTransfer @108-115
- function_signature_item WinUsb_ResetPipe @116-119
- function_signature_item WinUsb_AbortPipe @120-123
- function_signature_item WinUsb_FlushPipe @124-127
- function_signature_item WinUsb_SetPowerPolicy @128-133
- function_signature_item WinUsb_GetPowerPolicy @134-139
- function_signature_item WinUsb_GetOverlappedResult @140-145
- function_signature_item WinUsb_ParseConfigurationDescriptor @146-154
- function_signature_item WinUsb_ParseDescriptors @155-160
- function_signature_item WinUsb_GetCurrentFrameNumber @161-165
- function_signature_item WinUsb_GetAdjustedFrameNumber @166-169
- function_signature_item WinUsb_RegisterIsochBuffer @170-176
- function_signature_item WinUsb_UnregisterIsochBuffer @177-179
- function_signature_item WinUsb_WriteIsochPipe @180-186
- function_signature_item WinUsb_ReadIsochPipe @187-195
- function_signature_item WinUsb_WriteIsochPipeAsap @196-202
- function_signature_item WinUsb_ReadIsochPipeAsap @203-211

### third_party/rust/winapi/src/um/winuser.rs

Blob: `caeb5d95f9f76dc6dcc91f8e6f855379c72e8e97`. Grammar: rust. Status: syntax-clean.

- function_item IS_INTRESOURCE @131-133
- function_item MAKEINTRESOURCEA @135-137
- function_item MAKEINTRESOURCEW @139-141
- function_signature_item wvsprintfA @171-175
- function_signature_item wvsprintfW @176-180
- function_signature_item wsprintfA @183-187
- function_signature_item wsprintfW @188-192
- function_item GET_APPCOMMAND_LPARAM @597-599
- function_item GET_DEVICE_LPARAM @601-603
- function_signature_item LoadKeyboardLayoutA @716-719
- function_signature_item LoadKeyboardLayoutW @720-723
- function_signature_item ActivateKeyboardLayout @724-727
- function_signature_item ToUnicodeEx @728-736
- function_signature_item UnloadKeyboardLayout @737-739
- function_signature_item GetKeyboardLayoutNameA @740-742
- function_signature_item GetKeyboardLayoutNameW @743-745
- function_signature_item GetKeyboardLayoutList @746-749
- function_signature_item GetKeyboardLayout @750-752
- function_signature_item GetMouseMovePointsEx @765-771
- function_signature_item CreateDesktopA @784-791
- function_signature_item CreateDesktopW @792-799
- function_signature_item CreateDesktopExA @800-809
- function_signature_item CreateDesktopExW @810-819
- function_signature_item OpenDesktopA @820-825
- function_signature_item OpenDesktopW @826-831
- function_signature_item OpenInputDesktop @832-836
- function_signature_item EnumDesktopsA @837-841
- function_signature_item EnumDesktopsW @842-846
- function_signature_item EnumDesktopWindows @847-851
- function_signature_item SwitchDesktop @852-854
- function_signature_item SetThreadDesktop @855-857
- function_signature_item CloseDesktop @858-860
- function_signature_item GetThreadDesktop @861-863
- function_signature_item CreateWindowStationA @880-885
- function_signature_item CreateWindowStationW @886-891
- function_signature_item OpenWindowStationA @892-896
- function_signature_item OpenWindowStationW @897-901
- function_signature_item EnumWindowStationsA @902-905
- function_signature_item EnumWindowStationsW @906-909
- function_signature_item CloseWindowStation @910-912
- function_signature_item SetProcessWindowStation @913-915
- function_signature_item GetProcessWindowStation @916-916
- function_signature_item SetUserObjectSecurity @917-921
- function_signature_item GetUserObjectSecurity @922-928
- function_signature_item GetUserObjectInformationA @944-950
- function_signature_item GetUserObjectInformationW @951-957
- function_signature_item SetUserObjectInformationA @958-963
- function_signature_item SetUserObjectInformationW @964-969
- function_signature_item IsHungAppWindow @1036-1038
- function_signature_item DisableProcessWindowsGhosting @1039-1039
- function_item GET_WHEEL_DELTA_WPARAM @1284-1286
- function_item GET_KEYSTATE_WPARAM @1289-1291
- function_item GET_NCHITTEST_WPARAM @1293-1295
- function_item GET_XBUTTON_WPARAM @1297-1299
- function_signature_item RegisterWindowMessageA @1477-1479
- function_signature_item RegisterWindowMessageW @1480-1482
- function_signature_item TrackMouseEvent @1539-1541
- function_signature_item DrawEdge @1649-1654
- function_signature_item DrawFrameControl @1692-1697
- function_signature_item DrawCaption @1707-1712
- function_signature_item DrawAnimatedRects @1717-1722
- function_signature_item GetMessageA @1891-1896
- function_signature_item GetMessageW @1897-1902
- function_signature_item TranslateMessage @1903-1905
- function_signature_item DispatchMessageA @1906-1908
- function_signature_item DispatchMessageW @1909-1911
- function_signature_item SetMessageQueue @1912-1914
- function_signature_item PeekMessageA @1915-1921
- function_signature_item PeekMessageW @1922-1928
- function_signature_item RegisterHotKey @1938-1943
- function_signature_item UnregisterHotKey @1944-1947
- function_signature_item ExitWindowsEx @1971-1974
- function_signature_item SwapMouseButton @1975-1977
- function_signature_item GetMessagePos @1978-1978
- function_signature_item GetMessageTime @1979-1979
- function_signature_item GetMessageExtraInfo @1980-1980
- function_signature_item GetUnpredictedMessagePos @1981-1981
- function_signature_item IsWow64Message @1982-1982
- function_signature_item SetMessageExtraInfo @1983-1985
- function_signature_item SendMessageA @1986-1991
- function_signature_item SendMessageW @1992-1997
- function_signature_item SendMessageTimeoutA @1998-2006
- function_signature_item SendMessageTimeoutW @2007-2015
- function_signature_item SendNotifyMessageA @2016-2021
- function_signature_item SendNotifyMessageW @2022-2027
- function_signature_item SendMessageCallbackA @2028-2035
- function_signature_item SendMessageCallbackW @2036-2043
- function_signature_item BroadcastSystemMessageExA @2053-2060
- function_signature_item BroadcastSystemMessageExW @2061-2068
- function_signature_item BroadcastSystemMessageA @2069-2075
- function_signature_item BroadcastSystemMessageW @2076-2082
- function_signature_item RegisterDeviceNotificationA @2108-2112
- function_signature_item RegisterDeviceNotificationW @2113-2117
- function_signature_item UnregisterDeviceNotification @2118-2120
- function_signature_item RegisterPowerSettingNotification @2125-2129
- function_signature_item UnregisterPowerSettingNotification @2130-2132
- function_signature_item RegisterSuspendResumeNotification @2133-2136
- function_signature_item UnregisterSuspendResumeNotification @2137-2139
- function_signature_item PostMessageA @2140-2145
- function_signature_item PostMessageW @2146-2151
- function_signature_item PostThreadMessageA @2152-2157
- function_signature_item PostThreadMessageW @2158-2163
- function_signature_item AttachThreadInput @2170-2174
- function_signature_item ReplyMessage @2175-2177
- function_signature_item WaitMessage @2178-2178
- function_signature_item WaitForInputIdle @2179-2182
- function_signature_item DefWindowProcA @2183-2188
- function_signature_item DefWindowProcW @2189-2194
- function_signature_item PostQuitMessage @2195-2197
- function_signature_item CallWindowProcA @2198-2204
- function_signature_item CallWindowProcW @2205-2211
- function_signature_item InSendMessage @2212-2212
- function_signature_item InSendMessageEx @2213-2215
- function_signature_item GetDoubleClickTime @2223-2223
- function_signature_item SetDoubleClickTime @2224-2226
- function_signature_item RegisterClassA @2227-2229
- function_signature_item RegisterClassW @2230-2232
- function_signature_item UnregisterClassA @2233-2236
- function_signature_item UnregisterClassW @2237-2240
- function_signature_item GetClassInfoA @2241-2245
- function_signature_item GetClassInfoW @2246-2250
- function_signature_item RegisterClassExA @2251-2253
- function_signature_item RegisterClassExW @2254-2256
- function_signature_item GetClassInfoExA @2257-2261
- function_signature_item GetClassInfoExW @2262-2266
- function_signature_item CreateWindowExA @2274-2287
- function_signature_item CreateWindowExW @2288-2301
- function_signature_item IsWindow @2306-2308
- function_signature_item IsMenu @2309-2311
- function_signature_item IsChild @2312-2315
- function_signature_item DestroyWindow @2316-2318
- function_signature_item ShowWindow @2319-2322
- function_signature_item AnimateWindow @2323-2327
- function_signature_item UpdateLayeredWindow @2328-2338
- function_signature_item UpdateLayeredWindowIndirect @2354-2357
- function_signature_item GetLayeredWindowAttributes @2358-2363
- function_signature_item PrintWindow @2368-2372
- function_signature_item SetLayeredWindowAttributes @2373-2378
- function_signature_item ShowWindowAsync @2387-2390
- function_signature_item FlashWindow @2391-2394
- function_signature_item FlashWindowEx @2405-2407
- function_signature_item ShowOwnedPopups @2416-2419
- function_signature_item OpenIcon @2420-2422
- function_signature_item CloseWindow @2423-2425
- function_signature_item MoveWindow @2426-2433
- function_signature_item SetWindowPos @2434-2442
- function_signature_item GetWindowPlacement @2443-2446
- function_signature_item SetWindowPlacement @2447-2450
- function_signature_item GetWindowDisplayAffinity @2455-2458
- function_signature_item SetWindowDisplayAffinity @2459-2462
- function_signature_item BeginDeferWindowPos @2463-2465
- function_signature_item DeferWindowPos @2466-2475
- function_signature_item EndDeferWindowPos @2476-2478
- function_signature_item IsWindowVisible @2479-2481
- function_signature_item IsIconic @2482-2484
- function_signature_item AnyPopup @2485-2485
- function_signature_item BringWindowToTop @2486-2488
- function_signature_item IsZoomed @2489-2491
- function_signature_item CreateDialogParamA @2541-2547
- function_signature_item CreateDialogParamW @2548-2554
- function_signature_item CreateDialogIndirectParamA @2555-2561
- function_signature_item CreateDialogIndirectParamW @2562-2568
- function_signature_item DialogBoxParamA @2575-2581
- function_signature_item DialogBoxParamW @2582-2588
- function_signature_item DialogBoxIndirectParamA @2589-2595
- function_signature_item DialogBoxIndirectParamW @2596-2602
- function_signature_item EndDialog @2609-2612
- function_signature_item GetDlgItem @2613-2616
- function_signature_item SetDlgItemInt @2617-2622
- function_signature_item GetDlgItemInt @2623-2628
- function_signature_item SetDlgItemTextA @2629-2633
- function_signature_item SetDlgItemTextW @2634-2638
- function_signature_item GetDlgItemTextA @2639-2644
- function_signature_item GetDlgItemTextW @2645-2650
- function_signature_item CheckDlgButton @2651-2655
- function_signature_item CheckRadioButton @2656-2661
- function_signature_item IsDlgButtonChecked @2662-2665
- function_signature_item SendDlgItemMessageA @2666-2672
- function_signature_item SendDlgItemMessageW @2673-2679
- function_signature_item GetNextDlgGroupItem @2680-2684
- function_signature_item GetNextDlgTabItem @2685-2689
- function_signature_item GetDlgCtrlID @2690-2692
- function_signature_item GetDialogBaseUnits @2693-2693
- function_signature_item DefDlgProcA @2694-2699
- function_signature_item DefDlgProcW @2700-2705
- function_signature_item SetDialogControlDpiChangeBehavior @2713-2717
- function_signature_item GetDialogControlDpiChangeBehavior @2718-2720
- function_signature_item SetDialogDpiChangeBehavior @2729-2733
- function_signature_item GetDialogDpiChangeBehavior @2734-2736
- function_signature_item CallMsgFilterA @2737-2740
- function_signature_item CallMsgFilterW @2741-2744
- function_signature_item OpenClipboard @2745-2747
- function_signature_item CloseClipboard @2748-2748
- function_signature_item GetClipboardSequenceNumber @2749-2749
- function_signature_item GetClipboardOwner @2750-2750
- function_signature_item SetClipboardViewer @2751-2753
- function_signature_item GetClipboardViewer @2754-2754
- function_signature_item ChangeClipboardChain @2755-2758
- function_signature_item SetClipboardData @2759-2762
- function_signature_item GetClipboardData @2763-2765
- function_signature_item RegisterClipboardFormatA @2766-2768
- function_signature_item RegisterClipboardFormatW @2769-2771
- function_signature_item CountClipboardFormats @2772-2772
- function_signature_item EnumClipboardFormats @2773-2775
- function_signature_item GetClipboardFormatNameA @2776-2780
- function_signature_item GetClipboardFormatNameW @2781-2785
- function_signature_item EmptyClipboard @2786-2786
- function_signature_item IsClipboardFormatAvailable @2787-2789
- function_signature_item GetPriorityClipboardFormat @2790-2793
- function_signature_item GetOpenClipboardWindow @2794-2794
- function_signature_item AddClipboardFormatListener @2795-2797
- function_signature_item RemoveClipboardFormatListener @2798-2800
- function_signature_item GetUpdatedClipboardFormats @2801-2805
- function_signature_item CharToOemA @2806-2809
- function_signature_item CharToOemW @2810-2813
- function_signature_item OemToCharA @2814-2817
- function_signature_item OemToCharW @2818-2821
- function_signature_item CharToOemBuffA @2822-2826
- function_signature_item CharToOemBuffW @2827-2831
- function_signature_item OemToCharBuffA @2832-2836
- function_signature_item OemToCharBuffW @2837-2841
- function_signature_item CharUpperA @2842-2844
- function_signature_item CharUpperW @2845-2847
- function_signature_item CharUpperBuffA @2848-2851
- function_signature_item CharUpperBuffW @2852-2855
- function_signature_item CharLowerA @2856-2858
- function_signature_item CharLowerW @2859-2861
- function_signature_item CharLowerBuffA @2862-2865
- function_signature_item CharLowerBuffW @2866-2869
- function_signature_item CharNextA @2870-2872
- function_signature_item CharNextW @2873-2875
- function_signature_item CharPrevA @2876-2879
- function_signature_item CharPrevW @2880-2883
- function_signature_item CharNextExA @2884-2888
- function_signature_item CharPrevExA @2889-2894
- function_signature_item IsCharAlphaA @2907-2909
- function_signature_item IsCharAlphaW @2910-2912
- function_signature_item IsCharAlphaNumericA @2913-2915
- function_signature_item IsCharAlphaNumericW @2916-2918
- function_signature_item IsCharUpperA @2919-2921
- function_signature_item IsCharUpperW @2922-2924
- function_signature_item IsCharLowerA @2925-2927
- function_signature_item IsCharLowerW @2928-2930
- function_signature_item SetFocus @2931-2933
- function_signature_item GetActiveWindow @2934-2934
- function_signature_item GetFocus @2935-2935
- function_signature_item GetKBCodePage @2936-2936
- function_signature_item GetKeyState @2937-2939
- function_signature_item GetAsyncKeyState @2940-2942
- function_signature_item GetKeyboardState @2943-2945
- function_signature_item SetKeyboardState @2946-2948
- function_signature_item GetKeyNameTextA @2949-2953
- function_signature_item GetKeyNameTextW @2954-2958
- function_signature_item GetKeyboardType @2959-2961
- function_signature_item ToAscii @2962-2968
- function_signature_item ToAsciiEx @2969-2976
- function_signature_item ToUnicode @2977-2984
- function_signature_item OemKeyScan @2985-2987
- function_signature_item VkKeyScanA @2988-2990
- function_signature_item VkKeyScanW @2991-2993
- function_signature_item VkKeyScanExA @2994-2997
- function_signature_item VkKeyScanExW @2998-3001
- function_signature_item keybd_event @3008-3013
- function_signature_item mouse_event @3030-3036
- function_signature_item SendInput @3080-3084
- function_signature_item GetTouchInputInfo @3114-3119
- function_signature_item CloseTouchInputHandle @3120-3122
- function_signature_item RegisterTouchWindow @3127-3130
- function_signature_item UnregisterTouchWindow @3131-3133
- function_signature_item IsTouchWindow @3134-3137
- function_signature_item InitializeTouchInjection @3263-3266
- function_signature_item InjectTouchInput @3267-3270
- function_signature_item GetPointerType @3303-3306
- function_signature_item GetPointerCursorId @3307-3310
- function_signature_item GetPointerInfo @3311-3314
- function_signature_item GetPointerInfoHistory @3315-3319
- function_signature_item GetPointerFrameInfo @3320-3324
- function_signature_item GetPointerFrameInfoHistory @3325-3330
- function_signature_item GetPointerTouchInfo @3331-3334
- function_signature_item GetPointerTouchInfoHistory @3335-3339
- function_signature_item GetPointerFrameTouchInfo @3340-3344
- function_signature_item GetPointerFrameTouchInfoHistory @3345-3350
- function_signature_item GetPointerPenInfo @3351-3354
- function_signature_item GetPointerPenInfoHistory @3355-3359
- function_signature_item GetPointerFramePenInfo @3360-3364
- function_signature_item GetPointerFramePenInfoHistory @3365-3370
- function_signature_item SkipPointerFrameMessages @3371-3373
- function_signature_item RegisterPointerInputTarget @3374-3377
- function_signature_item UnregisterPointerInputTarget @3378-3381
- function_signature_item RegisterPointerInputTargetEx @3382-3386
- function_signature_item UnregisterPointerInputTargetEx @3387-3390
- function_signature_item CreateSyntheticPointerDevice @3394-3398
- function_signature_item InjectSyntheticPointerInput @3399-3403
- function_signature_item DestroySyntheticPointerDevice @3404-3406
- function_signature_item EnableMouseInPointer @3409-3411
- function_signature_item IsMouseInPointerEnabled @3412-3412
- function_signature_item RegisterTouchHitTestingWindow @3418-3421
- function_signature_item EvaluateProximityToRect @3439-3443
- function_signature_item EvaluateProximityToPolygon @3444-3449
- function_signature_item PackTouchHitTestingProximityEvaluation @3450-3453
- function_signature_item GetWindowFeedbackSetting @3471-3477
- function_signature_item SetWindowFeedbackSetting @3478-3484
- function_signature_item GetPointerInputTransform @3490-3494
- function_signature_item GetLastInputInfo @3502-3504
- function_signature_item MapVirtualKeyA @3505-3508
- function_signature_item MapVirtualKeyW @3509-3512
- function_signature_item MapVirtualKeyExA @3513-3517
- function_signature_item MapVirtualKeyExW @3518-3522
- function_signature_item GetInputState @3530-3530
- function_signature_item GetQueueStatus @3531-3533
- function_signature_item GetCapture @3534-3534
- function_signature_item SetCapture @3535-3537
- function_signature_item ReleaseCapture @3538-3538
- function_signature_item MsgWaitForMultipleObjects @3539-3545
- function_signature_item MsgWaitForMultipleObjectsEx @3546-3552
- function_signature_item SetTimer @3577-3582
- function_signature_item SetCoalescableTimer @3589-3595
- function_signature_item KillTimer @3596-3599
- function_signature_item IsWindowUnicode @3600-3602
- function_signature_item EnableWindow @3603-3606
- function_signature_item IsWindowEnabled @3607-3609
- function_signature_item LoadAcceleratorsA @3610-3613
- function_signature_item LoadAcceleratorsW @3614-3617
- function_signature_item CreateAcceleratorTableA @3618-3621
- function_signature_item CreateAcceleratorTableW @3622-3625
- function_signature_item DestroyAcceleratorTable @3626-3628
- function_signature_item CopyAcceleratorTableA @3629-3633
- function_signature_item CopyAcceleratorTableW @3634-3638
- function_signature_item TranslateAcceleratorA @3639-3643
- function_signature_item TranslateAcceleratorW @3644-3648
- function_signature_item GetSystemMetrics @3752-3754
- function_signature_item GetSystemMetricsForDpi @3755-3758
- function_signature_item LoadMenuA @3759-3762
- function_signature_item LoadMenuW @3763-3766
- function_signature_item LoadMenuIndirectA @3767-3769
- function_signature_item LoadMenuIndirectW @3770-3772
- function_signature_item GetMenu @3773-3775
- function_signature_item SetMenu @3776-3779
- function_signature_item ChangeMenuA @3780-3786
- function_signature_item ChangeMenuW @3787-3793
- function_signature_item HiliteMenuItem @3794-3799
- function_signature_item GetMenuStringA @3800-3806
- function_signature_item GetMenuStringW @3807-3813
- function_signature_item GetMenuState @3814-3818
- function_signature_item DrawMenuBar @3819-3821
- function_signature_item GetSystemMenu @3825-3828
- function_signature_item CreateMenu @3829-3829
- function_signature_item CreatePopupMenu @3830-3830
- function_signature_item DestroyMenu @3831-3833
- function_signature_item CheckMenuItem @3834-3838
- function_signature_item EnableMenuItem @3839-3843
- function_signature_item GetSubMenu @3844-3847
- function_signature_item GetMenuItemID @3848-3851
- function_signature_item GetMenuItemCount @3852-3854
- function_signature_item InsertMenuA @3855-3861
- function_signature_item InsertMenuW @3862-3868
- function_signature_item AppendMenuA @3869-3874
- function_signature_item AppendMenuW @3875-3880
- function_signature_item ModifyMenuA @3881-3887
- function_signature_item ModifyMenuW @3888-3894
- function_signature_item RemoveMenu @3895-3899
- function_signature_item DeleteMenu @3900-3904
- function_signature_item SetMenuItemBitmaps @3905-3911
- function_signature_item GetMenuCheckMarkDimensions @3912-3912
- function_signature_item TrackPopupMenu @3913-3921
- function_signature_item TrackPopupMenuEx @3933-3940
- function_signature_item CalculatePopupWindowPosition @3941-3947
- function_signature_item GetMenuInfo @3973-3976
- function_signature_item SetMenuInfo @3977-3980
- function_signature_item EndMenu @3981-3986
- function_signature_item InsertMenuItemA @4055-4060
- function_signature_item InsertMenuItemW @4061-4066
- function_signature_item GetMenuItemInfoA @4067-4072
- function_signature_item GetMenuItemInfoW @4073-4078
- function_signature_item SetMenuItemInfoA @4079-4084
- function_signature_item SetMenuItemInfoW @4085-4090
- function_signature_item GetMenuDefaultItem @4095-4099
- function_signature_item SetMenuDefaultItem @4100-4104
- function_signature_item GetMenuItemRect @4105-4110
- function_signature_item MenuItemFromPoint @4111-4115
- function_signature_item DragObject @4156-4162
- function_signature_item DragDetect @4163-4166
- function_signature_item DrawIcon @4167-4172
- function_signature_item DrawTextA @4207-4213
- function_signature_item DrawTextW @4214-4220
- function_signature_item DrawTextExA @4221-4228
- function_signature_item DrawTextExW @4229-4236
- function_signature_item GrayStringA @4237-4247
- function_signature_item GrayStringW @4248-4258
- function_signature_item DrawStateA @4273-4284
- function_signature_item DrawStateW @4285-4296
- function_signature_item TabbedTextOutA @4297-4306
- function_signature_item TabbedTextOutW @4307-4316
- function_signature_item GetTabbedTextExtentA @4317-4323
- function_signature_item GetTabbedTextExtentW @4324-4330
- function_signature_item UpdateWindow @4331-4333
- function_signature_item SetActiveWindow @4334-4336
- function_signature_item GetForegroundWindow @4337-4337
- function_signature_item PaintDesktop @4338-4340
- function_signature_item SwitchToThisWindow @4341-4344
- function_signature_item SetForegroundWindow @4345-4347
- function_signature_item AllowSetForegroundWindow @4348-4350
- function_signature_item LockSetForegroundWindow @4354-4356
- function_signature_item WindowFromDC @4361-4363
- function_signature_item GetDC @4364-4366
- function_signature_item GetDCEx @4367-4371
- function_signature_item GetWindowDC @4386-4388
- function_signature_item ReleaseDC @4389-4392
- function_signature_item BeginPaint @4393-4396
- function_signature_item EndPaint @4397-4400
- function_signature_item GetUpdateRect @4401-4405
- function_signature_item GetUpdateRgn @4406-4410
- function_signature_item SetWindowRgn @4411-4415
- function_signature_item GetWindowRgn @4416-4419
- function_signature_item GetWindowRgnBox @4420-4423
- function_signature_item ExcludeUpdateRgn @4424-4427
- function_signature_item InvalidateRect @4428-4432
- function_signature_item ValidateRect @4433-4436
- function_signature_item InvalidateRgn @4437-4441
- function_signature_item ValidateRgn @4442-4445
- function_signature_item RedrawWindow @4446-4451
- function_signature_item LockWindowUpdate @4466-4468
- function_signature_item ScrollWindow @4469-4475
- function_signature_item ScrollDC @4476-4484
- function_signature_item ScrollWindowEx @4485-4494
- function_signature_item SetScrollPos @4501-4506
- function_signature_item GetScrollPos @4507-4510
- function_signature_item SetScrollRange @4511-4517
- function_signature_item GetScrollRange @4518-4523
- function_signature_item ShowScrollBar @4524-4528
- function_signature_item EnableScrollBar @4529-4533
- function_signature_item SetPropA @4544-4548
- function_signature_item SetPropW @4549-4553
- function_signature_item GetPropA @4554-4557
- function_signature_item GetPropW @4558-4561
- function_signature_item RemovePropA @4562-4565
- function_signature_item RemovePropW @4566-4569
- function_signature_item EnumPropsExA @4570-4574
- function_signature_item EnumPropsExW @4575-4579
- function_signature_item EnumPropsA @4580-4583
- function_signature_item EnumPropsW @4584-4587
- function_signature_item SetWindowTextA @4588-4591
- function_signature_item SetWindowTextW @4592-4595
- function_signature_item GetWindowTextA @4596-4600
- function_signature_item GetWindowTextW @4601-4605
- function_signature_item GetWindowTextLengthA @4606-4608
- function_signature_item GetWindowTextLengthW @4609-4611
- function_signature_item GetClientRect @4612-4615
- function_signature_item GetWindowRect @4616-4619
- function_signature_item AdjustWindowRect @4620-4624
- function_signature_item AdjustWindowRectEx @4625-4630
- function_signature_item AdjustWindowRectExForDpi @4631-4637
- function_signature_item SetWindowContextHelpId @4651-4654
- function_signature_item GetWindowContextHelpId @4655-4657
- function_signature_item SetMenuContextHelpId @4658-4661
- function_signature_item GetMenuContextHelpId @4662-4664
- function_signature_item MessageBoxA @4704-4709
- function_signature_item MessageBoxW @4710-4715
- function_signature_item MessageBoxExA @4716-4722
- function_signature_item MessageBoxExW @4723-4729
- function_signature_item MessageBoxIndirectA @4763-4765
- function_signature_item MessageBoxIndirectW @4766-4768
- function_signature_item MessageBeep @4769-4771
- function_signature_item ShowCursor @4772-4774
- function_signature_item SetCursorPos @4775-4778
- function_signature_item SetPhysicalCursorPos @4779-4782
- function_signature_item SetCursor @4783-4785
- function_signature_item GetCursorPos @4786-4788
- function_signature_item GetPhysicalCursorPos @4789-4791
- function_signature_item GetClipCursor @4792-4794
- function_signature_item GetCursor @4795-4795
- function_signature_item CreateCaret @4796-4801
- function_signature_item GetCaretBlinkTime @4802-4802
- function_signature_item SetCaretBlinkTime @4803-4805
- function_signature_item DestroyCaret @4806-4806
- function_signature_item HideCaret @4807-4809
- function_signature_item ShowCaret @4810-4812
- function_signature_item SetCaretPos @4813-4816
- function_signature_item GetCaretPos @4817-4819
- function_signature_item ClientToScreen @4820-4823
- function_signature_item ScreenToClient @4824-4827
- function_signature_item LogicalToPhysicalPoint @4828-4831
- function_signature_item PhysicalToLogicalPoint @4832-4835
- function_signature_item LogicalToPhysicalPointForPerMonitorDPI @4836-4839
- function_signature_item PhysicalToLogicalPointForPerMonitorDPI @4840-4843
- function_signature_item MapWindowPoints @4844-4849
- function_signature_item WindowFromPoint @4850-4852
- function_signature_item WindowFromPhysicalPoint @4853-4855
- function_signature_item ChildWindowFromPoint @4856-4859
- function_signature_item ClipCursor @4860-4862
- function_signature_item ChildWindowFromPointEx @4869-4873
- function_signature_item GetSysColor @4920-4922
- function_signature_item GetSysColorBrush @4923-4925
- function_signature_item SetSysColors @4926-4930
- function_signature_item DrawFocusRect @4931-4934
- function_signature_item FillRect @4935-4939
- function_signature_item FrameRect @4940-4944
- function_signature_item InvertRect @4945-4948
- function_signature_item SetRect @4949-4955
- function_signature_item SetRectEmpty @4956-4958
- function_signature_item CopyRect @4959-4962
- function_signature_item InflateRect @4963-4967
- function_signature_item IntersectRect @4968-4972
- function_signature_item UnionRect @4973-4977
- function_signature_item SubtractRect @4978-4982
- function_signature_item OffsetRect @4983-4987
- function_signature_item IsRectEmpty @4988-4990
- function_signature_item EqualRect @4991-4994
- function_signature_item PtInRect @4995-4998
- function_signature_item GetWindowWord @4999-5002
- function_signature_item SetWindowWord @5003-5007
- function_signature_item GetWindowLongA @5008-5011
- function_signature_item GetWindowLongW @5012-5015
- function_signature_item SetWindowLongA @5016-5020
- function_signature_item SetWindowLongW @5021-5025
- function_signature_item GetWindowLongPtrA @5027-5030
- function_signature_item GetWindowLongPtrW @5032-5035
- function_signature_item SetWindowLongPtrA @5037-5041
- function_signature_item SetWindowLongPtrW @5043-5047
- function_signature_item GetClassWord @5058-5061
- function_signature_item SetClassWord @5062-5066
- function_signature_item GetClassLongA @5067-5070
- function_signature_item GetClassLongW @5071-5074
- function_signature_item SetClassLongA @5075-5079
- function_signature_item SetClassLongW @5080-5084
- function_signature_item GetClassLongPtrA @5086-5089
- function_signature_item GetClassLongPtrW @5091-5094
- function_signature_item SetClassLongPtrA @5096-5100
- function_signature_item SetClassLongPtrW @5102-5106
- function_signature_item GetProcessDefaultLayout @5117-5119
- function_signature_item SetProcessDefaultLayout @5120-5122
- function_signature_item GetDesktopWindow @5123-5123
- function_signature_item GetParent @5124-5126
- function_signature_item SetParent @5127-5130
- function_signature_item EnumChildWindows @5131-5135
- function_signature_item FindWindowA @5136-5139
- function_signature_item FindWindowW @5140-5143
- function_signature_item FindWindowExA @5144-5149
- function_signature_item FindWindowExW @5150-5155
- function_signature_item GetShellWindow @5156-5156
- function_signature_item RegisterShellHookWindow @5157-5159
- function_signature_item DeregisterShellHookWindow @5160-5162
- function_signature_item EnumWindows @5163-5166
- function_signature_item EnumThreadWindows @5167-5171
- function_signature_item GetClassNameA @5175-5179
- function_signature_item GetClassNameW @5180-5184
- function_signature_item GetTopWindow @5185-5187
- function_signature_item GetWindowThreadProcessId @5193-5196
- function_signature_item IsGUIThread @5197-5199
- function_signature_item GetLastActivePopup @5200-5202
- function_signature_item GetWindow @5213-5216
- function_signature_item SetWindowsHookA @5217-5220
- function_signature_item SetWindowsHookW @5221-5224
- function_signature_item UnhookWindowsHook @5225-5228
- function_signature_item SetWindowsHookExA @5229-5234
- function_signature_item SetWindowsHookExW @5235-5240
- function_signature_item UnhookWindowsHookEx @5241-5243
- function_signature_item CallNextHookEx @5244-5249
- function_signature_item CheckMenuRadioItem @5298-5304
- function_signature_item LoadBitmapA @5329-5332
- function_signature_item LoadBitmapW @5333-5336
- function_signature_item LoadCursorA @5337-5340
- function_signature_item LoadCursorW @5341-5344
- function_signature_item LoadCursorFromFileA @5345-5347
- function_signature_item LoadCursorFromFileW @5348-5350
- function_signature_item CreateCursor @5351-5359
- function_signature_item DestroyCursor @5360-5362
- function_signature_item SetSystemCursor @5382-5385
- function_signature_item LoadIconA @5396-5399
- function_signature_item LoadIconW @5400-5403
- function_signature_item CreateIcon @5407-5415
- function_signature_item DestroyIcon @5416-5418
- function_signature_item LookupIconIdFromDirectory @5419-5422
- function_signature_item LookupIconIdFromDirectoryEx @5423-5429
- function_signature_item CreateIconFromResource @5430-5435
- function_signature_item CreateIconFromResourceEx @5436-5444
- function_signature_item LoadImageA @5465-5472
- function_signature_item LoadImageW @5473-5480
- function_signature_item CopyImage @5481-5487
- function_signature_item DrawIconEx @5491-5501
- function_signature_item CreateIconIndirect @5502-5504
- function_signature_item CopyIcon @5505-5507
- function_signature_item GetIconInfo @5508-5511
- function_signature_item IsDialogMessageA @5706-5709
- function_signature_item IsDialogMessageW @5710-5713
- function_signature_item MapDialogRect @5714-5717
- function_signature_item DlgDirListA @5718-5724
- function_signature_item DlgDirListW @5725-5731
- function_signature_item DlgDirSelectExA @5735-5740
- function_signature_item DlgDirSelectExW @5741-5746
- function_signature_item DlgDirListComboBoxA @5747-5753
- function_signature_item DlgDirListComboBoxW @5754-5760
- function_signature_item DlgDirSelectComboBoxExA @5761-5766
- function_signature_item DlgDirSelectComboBoxExW @5767-5772
- function_signature_item SetScrollInfo @5976-5981
- function_signature_item GetScrollInfo @5982-5986
- function_signature_item DefFrameProcA @5994-6000
- function_signature_item DefFrameProcW @6001-6007
- function_signature_item DefMDIChildProcA @6008-6013
- function_signature_item DefMDIChildProcW @6014-6019
- function_signature_item ArrangeIconicWindows @6020-6022
- function_signature_item CreateMDIWindowA @6023-6034
- function_signature_item CreateMDIWindowW @6035-6046
- function_signature_item CascadeWindows @6047-6053
- function_signature_item WinHelpA @6057-6062
- function_signature_item WinHelpW @6063-6068
- function_signature_item ChangeDisplaySettingsA @6381-6384
- function_signature_item ChangeDisplaySettingsW @6385-6388
- function_signature_item ChangeDisplaySettingsExA @6389-6395
- function_signature_item ChangeDisplaySettingsExW @6396-6402
- function_signature_item EnumDisplaySettingsA @6407-6411
- function_signature_item EnumDisplaySettingsW @6412-6416
- function_signature_item EnumDisplaySettingsExA @6417-6422
- function_signature_item EnumDisplaySettingsExW @6423-6428
- function_signature_item EnumDisplayDevicesA @6433-6438
- function_signature_item EnumDisplayDevicesW @6439-6444
- function_signature_item SystemParametersInfoA @6448-6453
- function_signature_item SystemParametersInfoW @6454-6459
- function_signature_item SystemParametersInfoForDpi @6460-6466
- function_signature_item SetLastErrorEx @6470-6473
- function_signature_item InternalGetWindowText @6474-6478
- function_signature_item EndTask @6479-6483
- function_signature_item CancelShutdown @6484-6484
- function_signature_item MonitorFromPoint @6490-6493
- function_signature_item MonitorFromRect @6494-6497
- function_signature_item MonitorFromWindow @6498-6501
- function_signature_item GetMonitorInfoA @6529-6532
- function_signature_item GetMonitorInfoW @6533-6536
- function_signature_item EnumDisplayMonitors @6545-6550
- function_signature_item NotifyWinEvent @6551-6556
- function_signature_item SetWinEventHook @6568-6576
- function_signature_item IsWinEventHookInstalled @6577-6579
- function_signature_item UnhookWinEvent @6586-6588
- function_signature_item GetGUIThreadInfo @6728-6731
- function_signature_item BlockInput @6732-6734
- function_signature_item SetProcessDPIAware @6738-6738
- function_signature_item IsProcessDPIAware @6739-6739
- function_signature_item SetThreadDpiAwarenessContext @6740-6742
- function_signature_item GetThreadDpiAwarenessContext @6743-6743
- function_signature_item GetWindowDpiAwarenessContext @6744-6746
- function_signature_item GetAwarenessFromDpiAwarenessContext @6747-6749
- function_signature_item GetDpiFromDpiAwarenessContext @6750-6752
- function_signature_item AreDpiAwarenessContextsEqual @6753-6756
- function_signature_item IsValidDpiAwarenessContext @6757-6759
- function_signature_item GetDpiForWindow @6760-6762
- function_signature_item GetDpiForSystem @6763-6763
- function_signature_item GetSystemDpiForProcess @6764-6766
- function_signature_item EnableNonClientDpiScaling @6767-6769
- function_signature_item SetProcessDpiAwarenessContext @6770-6772
- function_signature_item SetThreadDpiHostingBehavior @6773-6775
- function_signature_item GetThreadDpiHostingBehavior @6776-6776
- function_signature_item GetWindowDpiHostingBehavior @6777-6779
- function_signature_item GetWindowModuleFileNameA @6780-6784
- function_signature_item GetWindowModuleFileNameW @6785-6789
- function_signature_item GetCursorInfo @6836-6838
- function_signature_item GetWindowInfo @6856-6859
- function_signature_item GetTitleBarInfo @6869-6872
- function_signature_item GetMenuBarInfo @6896-6901
- function_signature_item GetScrollBarInfo @6915-6919
- function_signature_item GetComboBoxInfo @6933-6936
- function_signature_item GetAncestor @6942-6945
- function_signature_item RealChildWindowFromPoint @6946-6949
- function_signature_item RealGetWindowClassA @6950-6954
- function_signature_item RealGetWindowClassW @6955-6959
- function_signature_item GetAltTabInfoA @6975-6981
- function_signature_item GetAltTabInfoW @6982-6988
- function_signature_item GetListBoxInfo @6989-6991
- function_signature_item LockWorkStation @6992-6992
- function_signature_item UserHandleGrantAccess @6993-6997
- function_item GET_RAWINPUT_CODE_WPARAM @7001-7001
- function_signature_item GetRawInputData @7088-7094
- function_signature_item GetRawInputDeviceInfoA @7137-7142
- function_signature_item GetRawInputDeviceInfoW @7143-7148
- function_signature_item GetRawInputBuffer @7149-7153
- function_signature_item RegisterRawInputDevices @7178-7182
- function_signature_item GetRegisteredRawInputDevices @7183-7187
- function_signature_item GetRawInputDeviceList @7195-7199
- function_signature_item DefRawInputProc @7200-7204
- function_signature_item ChangeWindowMessageFilter @7205-7208
- function_signature_item ChangeWindowMessageFilterEx @7216-7221
- function_signature_item ShutdownBlockReasonCreate @7233-7236
- function_signature_item ShutdownBlockReasonQuery @7237-7241
- function_signature_item ShutdownBlockReasonDestroy @7242-7244
- function_signature_item IsImmersiveProcess @7248-7250

### third_party/rust/winapi/src/um/winver.rs

Blob: `5d25c678fbe75e0e386017551ddb4944c5cdfdbf`. Grammar: rust. Status: syntax-clean.

- function_signature_item GetFileVersionInfoSizeA @11-14
- function_signature_item GetFileVersionInfoSizeW @15-18
- function_signature_item GetFileVersionInfoA @19-24
- function_signature_item GetFileVersionInfoW @25-30
- function_signature_item VerQueryValueA @31-36
- function_signature_item VerQueryValueW @37-42
- function_signature_item VerLanguageNameA @43-47
- function_signature_item VerLanguageNameW @48-52

### third_party/rust/winapi/src/um/wlanapi.rs

Blob: `9584509da9f4d7deeed05e056b90da66d3166a7c`. Grammar: rust. Status: syntax-clean.

- function_item WLAN_API_VERSION_MAJOR @38-40
- function_item WLAN_API_VERSION_MINOR @42-44
- function_item WLAN_API_MAKE_VERSION @46-48
- function_signature_item WlanOpenHandle @866-871
- function_signature_item WlanCloseHandle @872-875
- function_signature_item WlanEnumInterfaces @876-880
- function_signature_item WlanSetAutoConfigParameter @881-887
- function_signature_item WlanQueryAutoConfigParameter @888-895
- function_signature_item WlanGetInterfaceCapability @896-901
- function_signature_item WlanSetInterface @902-909
- function_signature_item WlanQueryInterface @910-918
- function_signature_item WlanIhvControl @919-928
- function_signature_item WlanScan @929-935
- function_signature_item WlanGetAvailableNetworkList @936-942
- function_signature_item WlanGetAvailableNetworkList2 @943-949
- function_signature_item WlanGetNetworkBssList @950-958
- function_signature_item WlanConnect @959-964
- function_signature_item WlanConnect2 @965-970
- function_signature_item WlanDisconnect @971-975
- function_signature_item WlanRegisterNotification @976-984
- function_signature_item WlanGetProfile @985-993
- function_signature_item WlanSetProfileEapUserData @994-1003
- function_signature_item WlanSetProfileEapXmlUserData @1004-1011
- function_signature_item WlanSetProfile @1012-1021
- function_signature_item WlanDeleteProfile @1022-1027
- function_signature_item WlanRenameProfile @1028-1034
- function_signature_item WlanGetProfileList @1035-1040
- function_signature_item WlanSetProfileList @1041-1047
- function_signature_item WlanSetProfilePosition @1048-1054
- function_signature_item WlanSetProfileCustomUserData @1055-1062
- function_signature_item WlanGetProfileCustomUserData @1063-1070
- function_signature_item WlanSetFilterList @1071-1076
- function_signature_item WlanGetFilterList @1077-1082
- function_signature_item WlanSetPsdIEDataList @1083-1088
- function_signature_item WlanSaveTemporaryProfile @1089-1097
- function_signature_item WlanDeviceServiceCommand @1098-1108
- function_signature_item WlanGetSupportedDeviceServices @1109-1113
- function_signature_item WlanExtractPsdIEDataList @1114-1121
- function_signature_item WlanReasonCodeToString @1122-1127
- function_signature_item WlanAllocateMemory @1128-1130
- function_signature_item WlanFreeMemory @1131-1133
- function_signature_item WlanSetSecuritySettings @1134-1138
- function_signature_item WlanGetSecuritySettings @1139-1145
- function_signature_item WlanUIEditProfile @1156-1164
- function_signature_item WlanHostedNetworkStartUsing @1210-1214
- function_signature_item WlanHostedNetworkStopUsing @1215-1219
- function_signature_item WlanHostedNetworkForceStart @1220-1224
- function_signature_item WlanHostedNetworkForceStop @1225-1229
- function_signature_item WlanHostedNetworkQueryProperty @1278-1285
- function_signature_item WlanHostedNetworkSetProperty @1286-1293
- function_signature_item WlanHostedNetworkInitSettings @1294-1298
- function_signature_item WlanHostedNetworkRefreshSecuritySettings @1299-1303
- function_signature_item WlanHostedNetworkQueryStatus @1316-1320
- function_signature_item WlanHostedNetworkSetSecondaryKey @1321-1329
- function_signature_item WlanHostedNetworkQuerySecondaryKey @1330-1338
- function_signature_item WlanRegisterVirtualStationNotification @1339-1343
- function_signature_item WFDOpenHandle @1418-1422
- function_signature_item WFDCloseHandle @1423-1425
- function_signature_item WFDStartOpenSession @1435-1441
- function_signature_item WFDCancelOpenSession @1442-1444
- function_signature_item WFDOpenLegacySession @1445-1450
- function_signature_item WFDCloseSession @1451-1453
- function_signature_item WFDUpdateDeviceVisibility @1454-1456

### third_party/rust/winapi/src/um/wlanihv.rs

Blob: `e2fa8fb173a7c77abcb9463f9766fb26005d01fb`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/um/wlanihvtypes.rs

Blob: `d87d7b2393026f3bf9304c2194b00045a06d72ba`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/um/wlclient.rs

Blob: `e8af8011985afabbaf5323c1037e5090236772ac`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/um/wow64apiset.rs

Blob: `90d4b724b962cf5cc6870af2f487dac5ad6cbce8`. Grammar: rust. Status: syntax-clean.

- function_signature_item Wow64DisableWow64FsRedirection @9-11
- function_signature_item Wow64RevertWow64FsRedirection @12-14
- function_signature_item IsWow64Process @15-18
- function_signature_item GetSystemWow64DirectoryA @19-22
- function_signature_item GetSystemWow64DirectoryW @23-26
- function_signature_item IsWow64Process2 @27-31

### third_party/rust/winapi/src/um/wpdmtpextensions.rs

Blob: `7ff0b6dc7f6acd7a3913e4459c839b2757793d8e`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/um/ws2bth.rs

Blob: `7494f9261604590e7c1cb9c5d0124c4c9d031f72`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/um/ws2spi.rs

Blob: `d26128949164b21ca377454b4c1fc9ca5f2a8e0b`. Grammar: rust. Status: syntax-clean.

- function_signature_item WSPStartup @399-405
- function_signature_item WSCEnumProtocols @415-420
- function_signature_item WSCEnumProtocols32 @430-435
- function_signature_item WSCDeinstallProvider @436-439
- function_signature_item WSCDeinstallProvider32 @447-450
- function_signature_item WSCInstallProvider @451-457
- function_signature_item WSCInstallProvider64_32 @468-474
- function_signature_item WSCGetProviderPath @475-480
- function_signature_item WSCGetProviderPath32 @490-495
- function_signature_item WSCUpdateProvider @496-502
- function_signature_item WSCUpdateProvider32 @513-519
- function_signature_item WSCSetProviderInfo @539-546
- function_signature_item WSCGetProviderInfo @547-554
- function_signature_item WSCSetProviderInfo32 @556-563
- function_signature_item WSCGetProviderInfo32 @565-572
- function_signature_item WSCSetApplicationCategory @573-581
- function_signature_item WSCGetApplicationCategory @582-589
- function_signature_item WPUCloseEvent @590-593
- function_signature_item WPUCloseSocketHandle @594-597
- function_signature_item WPUCreateEvent @598-600
- function_signature_item WPUCreateSocketHandle @601-605
- function_signature_item WPUFDIsSet @606-609
- function_signature_item WPUGetProviderPath @610-615
- function_signature_item WPUModifyIFSHandle @616-620
- function_signature_item WPUPostMessage @621-626
- function_signature_item WPUQueryBlockingCallback @627-632
- function_signature_item WPUQuerySocketHandleContext @633-637
- function_signature_item WPUQueueApc @638-643
- function_signature_item WPUResetEvent @644-647
- function_signature_item WPUSetEvent @648-651
- function_signature_item WPUCompleteOverlappedRequest @652-658
- function_signature_item WPUOpenCurrentThread @659-662
- function_signature_item WPUCloseThread @663-666
- function_signature_item WSCEnumNameSpaceProviders32 @668-671
- function_signature_item WSCEnumNameSpaceProvidersEx32 @673-676
- function_signature_item WSCInstallNameSpace @677-683
- function_signature_item WSCInstallNameSpace32 @694-700
- function_signature_item WSCUnInstallNameSpace @701-703
- function_signature_item WSCInstallNameSpaceEx @709-716
- function_signature_item WSCInstallNameSpaceEx32 @718-725
- function_signature_item WSCUnInstallNameSpace32 @727-729
- function_signature_item WSCEnableNSProvider @730-733
- function_signature_item WSCEnableNSProvider32 @741-744
- function_signature_item WSCInstallProviderAndChains64_32 @746-756
- function_signature_item WSCInstallProviderAndChains @758-767
- function_signature_item NSPStartup @835-838
- function_signature_item WSAAdvertiseProvider @898-901
- function_signature_item WSAUnadvertiseProvider @902-904
- function_signature_item WSAProviderCompleteAsyncCall @905-908

### third_party/rust/winapi/src/um/ws2tcpip.rs

Blob: `4867c74a2f9c79548660f3eb6d56bb189d9d987a`. Grammar: rust. Status: syntax-clean.

- function_signature_item getaddrinfo @45-50
- function_signature_item GetAddrInfoW @51-56
- function_signature_item GetAddrInfoExA @76-87
- function_signature_item GetAddrInfoExW @88-99
- function_signature_item GetAddrInfoExCancel @100-102
- function_signature_item GetAddrInfoExOverlappedResult @103-105
- function_signature_item SetAddrInfoExA @138-151
- function_signature_item SetAddrInfoExW @152-165
- function_signature_item freeaddrinfo @196-198
- function_signature_item FreeAddrInfoW @199-201
- function_signature_item FreeAddrInfoEx @210-212
- function_signature_item FreeAddrInfoExW @213-215
- function_signature_item getnameinfo @225-233
- function_signature_item GetNameInfoW @234-242
- function_signature_item inet_pton @263-267
- function_signature_item InetPtonW @268-272
- function_signature_item inet_ntop @273-278
- function_signature_item InetNtopW @279-284
- function_signature_item WSASetSocketSecurity @310-316
- function_signature_item WSAQuerySocketSecurity @317-325
- function_signature_item WSASetSocketPeerTargetName @326-332
- function_signature_item WSADeleteSocketPeerTargetName @333-339
- function_signature_item WSAImpersonateSocketPeer @340-344
- function_signature_item WSARevertImpersonation @345-345

### third_party/rust/winapi/src/um/wtsapi32.rs

Blob: `ddddf35f2e4970ce1a8b3a0c2457695f224d8e52`. Grammar: rust. Status: syntax-clean.

- function_signature_item WTSQueryUserToken @5-5

### third_party/rust/winapi/src/um/xinput.rs

Blob: `b6f110b7e256f5037c4ecf327f0eb216eaf5d44b`. Grammar: rust. Status: syntax-clean.

- function_signature_item XInputGetState @135-138
- function_signature_item XInputSetState @139-142
- function_signature_item XInputGetCapabilities @143-147
- function_signature_item XInputEnable @148-150
- function_signature_item XInputGetAudioDeviceIds @151-157
- function_signature_item XInputGetBatteryInformation @158-162
- function_signature_item XInputGetKeystroke @163-167
- function_signature_item XInputGetDSoundAudioDeviceGuids @168-172

### third_party/rust/winapi/src/vc/excpt.rs

Blob: `a4f4d91e4ab59d58943610834fe93725e2dabf49`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/vc/limits.rs

Blob: `31509adeed3e5c1ff3bc86e40c1bc210b7d7e201`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/vc/mod.rs

Blob: `0c0606bd9e95ce885e2bae68e9044f68db00b998`. Grammar: rust. Status: syntax-clean.

- mod_item excpt @7-7
- mod_item limits @8-8
- mod_item vadefs @9-9
- mod_item vcruntime @10-10

### third_party/rust/winapi/src/vc/vadefs.rs

Blob: `d44cc04db7358ec94e4ee528b17ae80486c7462d`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/vc/vcruntime.rs

Blob: `63c671b36bda6aed2a0275347c3bd163e16d4485`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/winrt/activation.rs

Blob: `dca597bd17dcc52c7bf60babe3f780db10a28694`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/winrt/hstring.rs

Blob: `3eae6e0cb73ddee715d08007e70c7892ec8b6dec`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/winrt/inspectable.rs

Blob: `fb1e433151aadb6aa842df260ab681934655613e`. Grammar: rust. Status: syntax-clean.


### third_party/rust/winapi/src/winrt/mod.rs

Blob: `47e38676f14a8accf4bdbc70c28a92271134e34e`. Grammar: rust. Status: syntax-clean.

- mod_item activation @6-6
- mod_item hstring @7-7
- mod_item inspectable @8-8
- mod_item roapi @9-9
- mod_item robuffer @10-10
- mod_item roerrorapi @11-11
- mod_item winstring @12-12

### third_party/rust/winapi/src/winrt/roapi.rs

Blob: `47b988062c8ec050a944c659010d9a3122691b04`. Grammar: rust. Status: syntax-clean.

- enum_item RO_REGISTRATION_COOKIE__ @17-17
- function_signature_item RoInitialize @24-26
- function_signature_item RoUninitialize @27-27
- function_signature_item RoActivateInstance @28-31
- function_signature_item RoRegisterActivationFactories @32-37
- function_signature_item RoRevokeActivationFactories @38-40
- function_signature_item RoGetActivationFactory @41-45
- function_signature_item RoRegisterForApartmentShutdown @49-53
- function_signature_item RoUnregisterForApartmentShutdown @54-56
- function_signature_item RoGetApartmentIdentifier @57-59

### third_party/rust/winapi/src/winrt/robuffer.rs

Blob: `b0192fbe28e2db4eabaabf35bf2ada7669764f5b`. Grammar: rust. Status: syntax-clean.

- function_signature_item RoGetBufferMarshaler @9-11

### third_party/rust/winapi/src/winrt/roerrorapi.rs

Blob: `aa9f683a51cae735d9214699bf654a3670168dff`. Grammar: rust. Status: syntax-clean.

- function_signature_item RoGetErrorReportingFlags @20-22
- function_signature_item RoSetErrorReportingFlags @23-25
- function_signature_item RoResolveRestrictedErrorInfoReference @26-29
- function_signature_item SetRestrictedErrorInfo @30-32
- function_signature_item GetRestrictedErrorInfo @33-35
- function_signature_item RoOriginateErrorW @36-40
- function_signature_item RoOriginateError @41-44
- function_signature_item RoTransformErrorW @45-50
- function_signature_item RoTransformError @51-55
- function_signature_item RoCaptureErrorContext @56-58
- function_signature_item RoFailFastWithErrorContext @59-61
- function_signature_item RoOriginateLanguageException @62-66
- function_signature_item RoClearError @67-67
- function_signature_item RoReportUnhandledError @68-70
- function_signature_item RoInspectThreadErrorInfo @79-85
- function_signature_item RoInspectCapturedStackBackTrace @86-93
- function_signature_item RoGetMatchingRestrictedErrorInfo @94-97
- function_signature_item RoReportFailedDelegate @98-101
- function_signature_item IsErrorPropagationEnabled @102-102

### third_party/rust/winapi/src/winrt/winstring.rs

Blob: `ecbfcdf2a621d8dcaada8f45d0278f04e45321a7`. Grammar: rust. Status: syntax-clean.

- function_signature_item WindowsCreateString @11-15
- function_signature_item WindowsCreateStringReference @16-21
- function_signature_item WindowsDeleteString @22-24
- function_signature_item WindowsDuplicateString @25-28
- function_signature_item WindowsGetStringLen @29-31
- function_signature_item WindowsGetStringRawBuffer @32-35
- function_signature_item WindowsIsStringEmpty @36-38
- function_signature_item WindowsStringHasEmbeddedNull @39-42
- function_signature_item WindowsCompareStringOrdinal @43-47
- function_signature_item WindowsSubstring @48-52
- function_signature_item WindowsSubstringWithSpecifiedLength @53-58
- function_signature_item WindowsConcatString @59-63
- function_signature_item WindowsReplaceString @64-69
- function_signature_item WindowsTrimStringStart @70-74
- function_signature_item WindowsTrimStringEnd @75-79
- function_signature_item WindowsPreallocateStringBuffer @80-84
- function_signature_item WindowsPromoteStringBuffer @85-88
- function_signature_item WindowsDeleteStringBuffer @89-91
- function_signature_item WindowsInspectString @100-107
- function_signature_item HSTRING_UserSize @108-112
- function_signature_item HSTRING_UserMarshal @113-117
- function_signature_item HSTRING_UserUnmarshal @118-122
- function_signature_item HSTRING_UserFree @123-126
- function_signature_item HSTRING_UserSize64 @128-132
- function_signature_item HSTRING_UserMarshal64 @134-138
- function_signature_item HSTRING_UserUnmarshal64 @140-144
- function_signature_item HSTRING_UserFree64 @146-149

### third_party/rust/windows-collections/src/bindings.rs

Blob: `8aeeb777a319f4305fe68fbb3afbd6eebd2d473e`. Grammar: rust. Status: syntax-clean.

- struct_item IIterable @3-5
- function_item First @27-37
- trait_item IIterable_Impl @42-47
- function_signature_item First @46-46
- function_item new @49-76
- function_item First @50-70
- function_item matches @77-79
- struct_item IIterable_Vtbl @83-93
- function_item into_iter @97-99
- function_item into_iter @104-106
- struct_item IIterator @110-112
- function_item Current @134-144
- function_item HasCurrent @145-155
- function_item MoveNext @156-166
- function_item GetMany @167-182
- trait_item IIterator_Impl @187-198
- function_signature_item Current @191-191
- function_signature_item HasCurrent @192-192
- function_signature_item MoveNext @193-193
- function_signature_item GetMany @194-197
- function_item new @200-298
- function_item Current @201-221
- function_item HasCurrent @222-241
- function_item MoveNext @242-261
- function_item GetMany @262-289
- function_item matches @299-301
- struct_item IIterator_Vtbl @305-325
- function_item next @328-338
- struct_item IKeyValuePair @342-349
- function_item Key @379-389
- function_item Value @390-400
- trait_item IKeyValuePair_Impl @407-414
- function_signature_item Key @412-412
- function_signature_item Value @413-413
- function_item new @418-470
- function_item Key @419-440
- function_item Value @441-462
- function_item matches @471-473
- struct_item IKeyValuePair_Vtbl @477-493
- struct_item IMap @496-503
- function_item Lookup @536-550
- function_item Size @551-561
- function_item HasKey @562-576
- function_item GetView @577-587
- function_item Insert @588-604
- function_item Remove @605-617
- function_item Clear @618-624
- function_item First @625-635
- function_item into_iter @642-644
- function_item into_iter @651-653
- trait_item IMap_Impl @660-676
- function_signature_item Lookup @665-665
- function_signature_item Size @666-666
- function_signature_item HasKey @667-667
- function_signature_item GetView @668-668
- function_signature_item Insert @669-673
- function_signature_item Remove @674-674
- function_signature_item Clear @675-675
- function_item new @680-837
- function_item Lookup @681-703
- function_item Size @704-724
- function_item HasKey @725-746
- function_item GetView @747-768
- function_item Insert @769-795
- function_item Remove @796-810
- function_item Clear @811-824
- function_item matches @838-840
- struct_item IMap_Vtbl @844-878
- struct_item IMapView @881-888
- function_item Lookup @923-937
- function_item Size @938-948
- function_item HasKey @949-963
- function_item Split @964-978
- function_item First @979-989
- function_item into_iter @996-998
- function_item into_iter @1005-1007
- trait_item IMapView_Impl @1014-1027
- function_signature_item Lookup @1019-1019
- function_signature_item Size @1020-1020
- function_signature_item HasKey @1021-1021
- function_signature_item Split @1022-1026
- function_item new @1031-1128
- function_item Lookup @1032-1054
- function_item Size @1055-1075
- function_item HasKey @1076-1097
- function_item Split @1098-1118
- function_item matches @1129-1131
- struct_item IMapView_Vtbl @1135-1159
- struct_item IVector @1162-1164
- function_item GetAt @1191-1202
- function_item Size @1203-1213
- function_item GetView @1214-1224
- function_item IndexOf @1225-1240
- function_item SetAt @1241-1254
- function_item InsertAt @1255-1268
- function_item RemoveAt @1269-1278
- function_item Append @1279-1291
- function_item RemoveAtEnd @1292-1300
- function_item Clear @1301-1307
- function_item GetMany @1308-1325
- function_item ReplaceAll @1326-1339
- function_item First @1340-1350
- function_item into_iter @1355-1357
- function_item into_iter @1362-1364
- trait_item IVector_Impl @1369-1392
- function_signature_item GetAt @1373-1373
- function_signature_item Size @1374-1374
- function_signature_item GetView @1375-1375
- function_signature_item IndexOf @1376-1376
- function_signature_item SetAt @1377-1377
- function_signature_item InsertAt @1378-1378
- function_signature_item RemoveAt @1379-1379
- function_signature_item Append @1380-1380
- function_signature_item RemoveAtEnd @1381-1381
- function_signature_item Clear @1382-1382
- function_signature_item GetMany @1383-1387
- function_signature_item ReplaceAll @1388-1391
- function_item new @1394-1636
- function_item GetAt @1395-1416
- function_item Size @1417-1436
- function_item GetView @1437-1457
- function_item IndexOf @1458-1483
- function_item SetAt @1484-1498
- function_item InsertAt @1499-1513
- function_item RemoveAt @1514-1527
- function_item Append @1528-1541
- function_item RemoveAtEnd @1542-1554
- function_item Clear @1555-1567
- function_item GetMany @1568-1597
- function_item ReplaceAll @1598-1619
- function_item matches @1637-1639
- struct_item IVector_Vtbl @1643-1691
- struct_item IVectorView @1694-1696
- function_item GetAt @1723-1734
- function_item Size @1735-1745
- function_item IndexOf @1746-1761
- function_item GetMany @1762-1779
- function_item First @1780-1790
- function_item into_iter @1795-1797
- function_item into_iter @1802-1804
- trait_item IVectorView_Impl @1809-1821
- function_signature_item GetAt @1813-1813
- function_signature_item Size @1814-1814
- function_signature_item IndexOf @1815-1815
- function_signature_item GetMany @1816-1820
- function_item new @1823-1930
- function_item GetAt @1824-1845
- function_item Size @1846-1865
- function_item IndexOf @1866-1891
- function_item GetMany @1892-1921
- function_item matches @1931-1933
- struct_item IVectorView_Vtbl @1937-1962

### third_party/rust/windows-collections/src/iterable.rs

Blob: `759fd909c154b836f9cdaf4ad7955bf05dc976db`. Grammar: rust. Status: syntax-clean.

- struct_item StockIterable @5-11
- function_item First @18-24
- struct_item StockIterator @28-35
- function_item Current @42-51
- function_item HasCurrent @53-58
- function_item MoveNext @60-70
- function_item GetMany @72-83
- function_item from @91-93

### third_party/rust/windows-collections/src/lib.rs

Blob: `929049305a9194453126d62a6d484c09ee073fb6`. Grammar: rust. Status: syntax-clean.

- mod_item bindings @10-10
- mod_item iterable @17-17
- mod_item map_view @19-19
- mod_item vector_view @21-21

### third_party/rust/windows-collections/src/map_view.rs

Blob: `abc85c83da701e83c95c41b8189a06f57faf264e`. Grammar: rust. Status: syntax-clean.

- struct_item StockMapView @5-13
- function_item First @22-28
- function_item Lookup @38-42
- function_item Size @44-46
- function_item HasKey @48-50
- function_item Split @52-56
- struct_item StockMapViewIterator @60-69
- function_item Current @78-90
- function_item HasCurrent @92-95
- function_item MoveNext @97-101
- function_item GetMany @103-123
- struct_item StockKeyValuePair @127-136
- function_item Key @145-147
- function_item Value @149-151
- function_item from @161-163

### third_party/rust/windows-collections/src/vector_view.rs

Blob: `e5fa389a3c603ab8f91a745d91f26e6e8efdd0fd`. Grammar: rust. Status: syntax-clean.

- struct_item StockVectorView @5-11
- function_item First @18-24
- function_item GetAt @32-39
- function_item Size @41-43
- function_item IndexOf @45-53
- function_item GetMany @55-66
- struct_item StockVectorViewIterator @70-77
- function_item Current @84-92
- function_item HasCurrent @94-97
- function_item MoveNext @99-108
- function_item GetMany @110-120
- function_item from @128-130

### third_party/rust/windows-core/src/agile_reference.rs

Blob: `74609a7a8aa71fc89543c53b2c8abee694bee084`. Grammar: rust. Status: syntax-clean.

- struct_item AgileReference @7-7
- function_item new @11-24
- function_item resolve @27-29
- function_item fmt @36-38

### third_party/rust/windows-core/src/array.rs

Blob: `419fd2d4a3b74d34ead2236592cb8cc7d8b00f1f`. Grammar: rust. Status: syntax-clean.

- struct_item Array @4-7
- function_item default @10-15
- function_item new @20-22
- function_item with_len @25-49
- function_item from_slice @52-59
- function_item from_raw_parts @64-66
- function_item as_slice @69-71
- function_item is_empty @74-76
- function_item len @79-81
- function_item clear @84-106
- function_item set_abi_len @115-117
- function_item into_abi @121-125
- function_item deref @131-138
- function_item deref_mut @142-149
- function_item drop @153-155
- function_item fmt @162-164

### third_party/rust/windows-core/src/as_impl.rs

Blob: `75a8b60b83445322edbcc83418ff8a607d1f164d`. Grammar: rust. Status: syntax-clean.

- trait_item AsImpl @4-20
- function_item as_impl @9-11
- function_signature_item as_impl_ptr @19-19

### third_party/rust/windows-core/src/com_object.rs

Blob: `8fd38c9df6671858f0afee701eeea0c1261a3eda`. Grammar: rust. Status: syntax-clean.

- trait_item ComObjectInner @20-43
- function_signature_item into_object @42-42
- trait_item ComObjectInterface @53-56
- function_signature_item as_interface_ref @55-55
- struct_item ComObject @74-76
- function_item new @80-82
- function_item from_raw @96-98
- function_item get @106-108
- function_item get_box @112-114
- function_item get_mut @125-134
- function_item take @142-149
- function_item cast @157-163
- function_item as_interface @170-175
- function_item to_interface @179-184
- function_item into_interface @190-199
- function_item cast_from @215-221
- function_item default @225-227
- function_item drop @231-235
- function_item clone @240-245
- function_item as_ref @250-252
- function_item deref @259-261
- function_item from @270-272
- function_item hash @277-279
- function_item eq @288-292
- function_item partial_cmp @298-302
- function_item cmp @306-310
- function_item fmt @314-316
- function_item fmt @320-322
- function_item borrow @326-328
- struct_item StaticComObject @355-360
- function_item from_outer @370-372
- function_item get @380-382
- function_item deref @391-393

### third_party/rust/windows-core/src/event.rs

Blob: `3951ef2cf8062947aee6b28b4f0c136c8d23cb20`. Grammar: rust. Status: syntax-clean.

- struct_item Event @9-11
- function_item default @17-19
- function_item new @24-28
- function_item add @31-48
- function_item remove @51-72
- function_item clear @75-80
- function_item call @83-106
- enum_item Delegate @112-115
- function_item new @119-125
- function_item to_token @128-135
- function_item call @138-143

### third_party/rust/windows-core/src/guid.rs

Blob: `fc1ee3253bffa7c77106f842c7faf4bc022e242c`. Grammar: rust. Status: syntax-clean.

- struct_item GUID @7-19
- function_item new @23-32
- function_item zeroed @35-42
- function_item from_values @45-52
- function_item from_u128 @55-62
- function_item to_u128 @65-70
- function_item from_signature @73-97
- function_item fmt @109-125
- function_item try_from @131-152
- function_item from @156-158
- function_item from @162-164
- function_item invalid_guid @167-169
- function_item try_u32 @171-173
- function_item try_u16 @175-179
- function_item try_u8 @181-185
- function_item next @187-206

### third_party/rust/windows-core/src/handles.rs

Blob: `de395e36d05420d33ed829d312846972ee15401c`. Grammar: rust. Status: syntax-clean.

- trait_item Free @5-11
- function_signature_item free @10-10
- struct_item Owned @16-16
- function_item new @24-26
- function_item drop @30-32
- function_item deref @37-39
- function_item deref_mut @43-45

### third_party/rust/windows-core/src/imp/array_proxy.rs

Blob: `9b45ea8b218d86cae6a65dd2f5320e04407f76ea`. Grammar: rust. Status: syntax-clean.

- struct_item ArrayProxy @3-7
- function_item array_proxy @9-15
- function_item drop @18-23
- function_item deref @29-31
- function_item deref_mut @35-37

### third_party/rust/windows-core/src/imp/bindings.rs

Blob: `8a6f710370ea14935db44b73f9283fe8be46c954`. Grammar: rust. Status: syntax-clean.

- struct_item GUID @15-20
- function_item from_u128 @22-29

### third_party/rust/windows-core/src/imp/can_into.rs

Blob: `47ee7838c4be0fbb352fc58feb4eab923938dcf7`. Grammar: rust. Status: syntax-clean.

- trait_item CanInto @1-3

### third_party/rust/windows-core/src/imp/com_bindings.rs

Blob: `052cf5044a049218f96115a714665ad5da3c509a`. Grammar: rust. Status: syntax-clean.

- function_item RoGetAgileReference @2-16
- struct_item AgileReferenceOptions @20-20
- struct_item IAgileObject_Vtbl @33-35
- trait_item IAgileObject_Impl @36-36
- function_item new @38-42
- function_item matches @43-45
- function_item Resolve @55-68
- struct_item IAgileReference_Vtbl @72-79
- trait_item IAgileReference_Impl @80-86
- function_signature_item Resolve @81-85
- function_item new @88-109
- function_item Resolve @89-104
- function_item matches @110-112
- function_item Resolve @122-135
- struct_item IWeakReference_Vtbl @139-146
- trait_item IWeakReference_Impl @147-153
- function_signature_item Resolve @148-152
- function_item new @155-176
- function_item Resolve @156-171
- function_item matches @177-179
- function_item GetWeakReference @189-198
- struct_item IWeakReferenceSource_Vtbl @202-208
- trait_item IWeakReferenceSource_Impl @209-211
- function_signature_item GetWeakReference @210-210
- function_item new @213-237
- function_item GetWeakReference @214-232
- function_item matches @238-240

### third_party/rust/windows-core/src/imp/factory_cache.rs

Blob: `8adcb089fc4646aab2fac8fe4937f345cc5358ae`. Grammar: rust. Status: syntax-clean.

- struct_item FactoryCache @9-13
- function_item new @16-22
- function_item default @26-28
- function_item call @32-65
- function_item load_factory @73-117
- function_item search_path @125-143
- function_item get_activation_factory @145-156
- function_item delay_load @158-179
- mod_item tests @185-214
- function_item dll_search @189-213

### third_party/rust/windows-core/src/imp/generic_factory.rs

Blob: `1f9ddcee5dcbd1eb95979fa82d7b1455c91c1eb8`. Grammar: rust. Status: syntax-clean.

- function_item ActivateInstance @15-25
- struct_item IGenericFactory_Vtbl @29-33

### third_party/rust/windows-core/src/imp/marshaler.rs

Blob: `822cce6505bb8fbc741c2b502a7ae45932c21115`. Grammar: rust. Status: syntax-clean.

- function_item marshaler @9-36
- struct_item Marshaler @39-44
- function_item QueryInterface @61-81
- function_item AddRef @83-88
- function_item Release @90-101
- function_item GetUnmarshalClass @103-125
- function_item GetMarshalSizeMax @127-149
- function_item MarshalInterface @151-173
- function_item UnmarshalInterface @175-191
- function_item ReleaseMarshalData @193-202
- function_item DisconnectObject @204-213
- struct_item IMarshal @218-218
- struct_item IMarshal_Vtbl @226-268

### third_party/rust/windows-core/src/imp/mod.rs

Blob: `f4b84058f44ac1298fcb1aba9fd0f28ee28703f2`. Grammar: rust. Status: syntax-clean.

- mod_item bindings @4-4
- mod_item can_into @5-5
- mod_item com_bindings @6-6
- mod_item ref_count @7-7
- mod_item sha1 @8-8
- mod_item weak_ref_count @9-9

### third_party/rust/windows-core/src/imp/ref_count.rs

Blob: `97e1f2a67062eb5748a8162440dd44a161719204`. Grammar: rust. Status: syntax-clean.

- struct_item RefCount @5-5
- function_item new @9-11
- function_item add_ref @14-16
- function_item release @22-32

### third_party/rust/windows-core/src/imp/sha1.rs

Blob: `98d81cb6005fae8ec060c65ce0113cadebed0cde`. Grammar: rust. Status: syntax-clean.

- function_item sha1 @1-10
- struct_item ConstBuffer @14-17
- function_item default @20-22
- function_item for_class @26-33
- function_item for_interface @35-37
- function_item from_slice @39-42
- function_item new @44-49
- function_item push_slice @51-53
- function_item get @55-57
- function_item len @59-61
- function_item as_slice @63-65
- function_item push_other @67-69
- function_item push @71-75
- function_item push_hex_u8 @77-89
- function_item digit @78-86
- function_item push_hex_u16 @91-94
- function_item push_hex_u32 @96-99
- function_item push_amount @101-109
- function_item push_guid @111-125
- struct_item Blocks @128-131
- function_item process_blocks @133-183
- function_item as_block @139-152
- function_item clone_from_slice_64 @154-166
- function_item process_state @185-278
- function_item digest @280-344
- function_item clone_from_slice_128 @281-293
- function_item clone_slice_128 @295-302
- function_item as_block @304-317
- function_item rol @346-348
- function_item blk @350-353
- function_item r0 @355-371
- function_item r1 @373-390
- function_item r2 @392-409
- function_item r3 @411-428
- function_item r4 @430-447
- struct_item Digest @449-451
- function_item bytes @454-477
- function_item fmt @481-486

### third_party/rust/windows-core/src/imp/weak_ref_count.rs

Blob: `f8fde660c20506b8019236a02f93d0eb4e0b906e`. Grammar: rust. Status: syntax-clean.

- struct_item WeakRefCount @10-10
- function_item new @13-15
- function_item add_ref @17-24
- function_item is_one @27-29
- function_item release @31-49
- function_item query @52-93
- function_item is_weak_ref @96-98
- struct_item TearOff @101-107
- function_item new @111-121
- function_item from_encoding @123-129
- function_item from_strong_ptr @149-151
- function_item from_weak_ptr @153-155
- function_item decode @157-159
- function_item query_interface @161-169
- function_item StrongQueryInterface @171-195
- function_item WeakQueryInterface @197-235
- function_item StrongAddRef @237-244
- function_item WeakAddRef @246-253
- function_item StrongRelease @255-263
- function_item WeakRelease @265-280
- function_item StrongDowngrade @282-296
- function_item WeakUpgrade @298-326

### third_party/rust/windows-core/src/imp/windows.rs

Blob: `d9f44ad3414abeaba09dd7e2fc639cf74fcb7c56`. Grammar: rust. Status: syntax-clean.

- mod_item factory_cache @1-1
- mod_item generic_factory @4-4
- mod_item marshaler @7-7
- mod_item array_proxy @10-10

### third_party/rust/windows-core/src/inspectable.rs

Blob: `adca8a3cf3a2fbc2514a44ac8c46b07518869728`. Grammar: rust. Status: syntax-clean.

- struct_item IInspectable @13-13
- function_item GetRuntimeClassName @20-26
- function_item GetTrustLevel @29-35
- struct_item IInspectable_Vtbl @40-50
- function_item new @64-122
- function_item GetIids @65-81
- function_item GetRuntimeClassName @82-103
- function_item GetTrustLevel @104-115

### third_party/rust/windows-core/src/interface.rs

Blob: `bea4373574fcc109f7165fdc77edd362f17edb9b`. Grammar: rust. Status: syntax-clean.

- trait_item Interface @14-264
- function_item vtable @27-30
- function_item assume_vtable @40-42
- function_item as_raw @46-49
- function_item into_raw @53-58
- function_item from_raw @66-68
- function_item from_raw_borrowed @77-85
- function_item cast @92-114
- function_item cast_to_any @150-164
- function_item is_object @174-184
- function_item cast_object_ref @200-211
- function_item cast_object @228-235
- function_item downgrade @238-241
- function_item query @249-257
- function_item to_ref @261-263
- struct_item InterfaceRef @271-271
- function_item clone @276-278
- function_item fmt @282-284
- function_item from_raw @295-297
- function_item from_interface @304-310
- function_item to_owned @314-316
- function_item from @321-323
- function_item deref @330-332

### third_party/rust/windows-core/src/lib.rs

Blob: `382572708ffbdf0b27179155b4cefec3e7a60628`. Grammar: rust. Status: syntax-clean.

- mod_item imp @23-23
- mod_item as_impl @25-25
- mod_item com_object @26-26
- mod_item guid @27-27
- mod_item inspectable @28-28
- mod_item interface @29-29
- mod_item out_param @30-30
- mod_item out_ref @31-31
- mod_item param @32-32
- mod_item param_value @33-33
- mod_item r#ref @34-34
- mod_item runtime_name @35-35
- mod_item runtime_type @36-36
- mod_item scoped_interface @37-37
- mod_item r#type @38-38
- mod_item unknown @39-39
- mod_item weak @40-40

### third_party/rust/windows-core/src/out_param.rs

Blob: `828746c1f7e17a8ebdf5b0371909fec45455b6f2`. Grammar: rust. Status: syntax-clean.

- trait_item OutParam @8-14
- function_signature_item borrow_mut @13-13
- function_item borrow_mut @20-26
- function_item borrow_mut @33-35
- function_item borrow_mut @42-48
- function_item borrow_mut @55-62

### third_party/rust/windows-core/src/out_ref.rs

Blob: `eb4fd0caf0e39859e2e5be771fdfdb4f8e42c03e`. Grammar: rust. Status: syntax-clean.

- struct_item OutRef @7-7
- function_item is_null @11-13
- function_item write @16-24
- function_item from @28-30
- function_item default @34-36

### third_party/rust/windows-core/src/param.rs

Blob: `5ebf3add08f4ae4d0cbc90258132fa615f7be9a1`. Grammar: rust. Status: syntax-clean.

- trait_item Param @8-14
- function_signature_item param @13-13
- function_item param @20-27
- function_item param @34-36
- function_item param @46-55
- function_item param @62-64
- function_item param @73-75

### third_party/rust/windows-core/src/param_value.rs

Blob: `4500e261e8365c0c2d6697bf7738e74b16f90aa0`. Grammar: rust. Status: syntax-clean.

- enum_item ParamValue @5-8
- function_item abi @12-19
- function_item borrow @21-23

### third_party/rust/windows-core/src/ref.rs

Blob: `8f13e6ae538060aa123d640fbccff95dec851250`. Grammar: rust. Status: syntax-clean.

- struct_item Ref @6-6
- function_item is_null @10-12
- function_item ok @15-18
- function_item as_ref @21-27
- function_item unwrap @35-37
- function_item cloned @40-42
- function_item assume_init_ref @44-46
- function_item default @50-52
- function_item deref @57-59
- function_item from @66-68
- function_item from @75-81
- function_item from @85-87

### third_party/rust/windows-core/src/runtime_name.rs

Blob: `c6af26ae61b0cc92ce027533737e1e5bede15fd8`. Grammar: rust. Status: syntax-clean.

- trait_item RuntimeName @2-5

### third_party/rust/windows-core/src/runtime_type.rs

Blob: `f28ded853ecc62c6ea3c75d3bdf06e5a00818caf`. Grammar: rust. Status: syntax-clean.

- trait_item RuntimeType @4-6

### third_party/rust/windows-core/src/scoped_interface.rs

Blob: `5a701e8ceeffcf03a26d75eecd3819643265f023`. Grammar: rust. Status: syntax-clean.

- struct_item ScopedHeap @7-10
- struct_item ScopedInterface @13-16
- function_item new @19-24
- function_item deref @30-32
- function_item drop @36-40

### third_party/rust/windows-core/src/type.rs

Blob: `a64f191d0a282ed7bea162fcad812113fd218ae1`. Grammar: rust. Status: syntax-clean.

- trait_item TypeKind @4-6
- struct_item InterfaceType @9-9
- struct_item CloneType @12-12
- struct_item CopyType @15-15
- trait_item Type @18-26
- function_signature_item is_null @22-22
- function_signature_item assume_init_ref @23-23
- function_signature_item from_abi @24-24
- function_signature_item from_default @25-25
- function_item is_null @35-37
- function_item assume_init_ref @39-41
- function_item from_abi @43-51
- function_item from_default @53-55
- function_item is_null @65-67
- function_item assume_init_ref @69-71
- function_item from_abi @73-75
- function_item from_default @77-79
- function_item is_null @89-91
- function_item assume_init_ref @93-95
- function_item from_abi @97-99
- function_item from_default @101-103

### third_party/rust/windows-core/src/unknown.rs

Blob: `4dc6aa7157368999e7cee9b578055c90c9fc6182`. Grammar: rust. Status: syntax-clean.

- struct_item IUnknown @12-12
- struct_item IUnknown_Vtbl @16-24
- function_item clone @32-38
- function_item drop @42-46
- function_item eq @50-62
- function_item fmt @68-70
- trait_item IUnknownImpl @78-150
- function_signature_item get_impl @83-83
- function_signature_item get_impl_mut @86-86
- function_signature_item into_inner @89-89
- function_signature_item QueryInterface @97-97
- function_signature_item AddRef @100-100
- function_signature_item Release @111-111
- function_signature_item is_reference_count_one @114-114
- function_signature_item GetTrustLevel @117-117
- function_item as_interface @124-129
- function_item to_interface @133-138
- function_signature_item to_object @147-149
- function_item new @153-185
- function_item QueryInterface @154-163
- function_item AddRef @164-171
- function_item Release @172-179

### third_party/rust/windows-core/src/weak.rs

Blob: `b110ffbbf15ae4e619d6665b7d8e7dcd39ad19a4`. Grammar: rust. Status: syntax-clean.

- struct_item Weak @6-6
- function_item new @10-12
- function_item upgrade @15-19
- function_item downgrade @21-24

### third_party/rust/windows-core/src/windows.rs

Blob: `6f055bbc3dcd7c6bce0ef232f3406dcc2722b8af`. Grammar: rust. Status: syntax-clean.

- mod_item agile_reference @1-1
- mod_item array @4-4
- mod_item event @8-8
- mod_item handles @12-12
- function_item factory @19-21
- function_item param @24-26
- function_item param @30-32
- function_item param @36-38
- function_item param @42-44

### third_party/rust/windows-future/src/async.rs

Blob: `d6a5bf50e1d0349f9b230cfaab120c7e23683dba`. Grammar: rust. Status: syntax-clean.

- trait_item Async @12-65
- function_signature_item set_completed @20-20
- function_signature_item invoke_completed @24-24
- function_signature_item get_results @27-27
- function_signature_item status @30-30
- function_item join @33-44
- function_item when @47-64
- function_item set_completed @71-76
- function_item invoke_completed @79-81
- function_item get_results @83-85
- function_item status @87-89
- function_item set_completed @96-101
- function_item invoke_completed @104-106
- function_item get_results @108-110
- function_item status @112-114
- function_item set_completed @121-128
- function_item invoke_completed @131-133
- function_item get_results @135-137
- function_item status @139-141
- function_item set_completed @148-155
- function_item invoke_completed @158-160
- function_item get_results @162-164
- function_item status @166-168

### third_party/rust/windows-future/src/async_ready.rs

Blob: `e50122abddc72c374369cd8465360b2d6b9eb9e5`. Grammar: rust. Status: syntax-clean.

- struct_item ReadyState @4-7
- function_item new @10-15
- function_item status @17-23
- function_item invoke_completed @27-34
- function_item error_code @38-43
- struct_item ReadyAction @47-47
- struct_item ReadyOperation @50-52
- struct_item ReadyActionWithProgress @55-57
- struct_item ReadyOperationWithProgress @60-63
- function_item Id @66-68
- function_item Status @69-71
- function_item ErrorCode @72-74
- function_item Cancel @75-77
- function_item Close @78-80
- function_item Id @84-86
- function_item Status @87-89
- function_item ErrorCode @90-92
- function_item Cancel @93-95
- function_item Close @96-98
- function_item Id @102-104
- function_item Status @105-107
- function_item ErrorCode @108-110
- function_item Cancel @111-113
- function_item Close @114-116
- function_item Id @120-122
- function_item Status @123-125
- function_item ErrorCode @126-128
- function_item Cancel @129-131
- function_item Close @132-134
- function_item SetCompleted @138-140
- function_item Completed @141-143
- function_item GetResults @144-146
- function_item SetCompleted @150-152
- function_item Completed @153-155
- function_item GetResults @156-158
- function_item SetCompleted @162-164
- function_item Completed @165-167
- function_item GetResults @168-170
- function_item SetProgress @171-173
- function_item Progress @174-176
- function_item SetCompleted @182-187
- function_item Completed @188-190
- function_item GetResults @191-193
- function_item SetProgress @194-196
- function_item Progress @197-199
- function_item ready @204-206
- function_item ready @211-213
- function_item ready @218-220
- function_item ready @225-227

### third_party/rust/windows-future/src/async_spawn.rs

Blob: `cd394cbd77dc77141c9e79ff81dfe735940a7a1d`. Grammar: rust. Status: syntax-clean.

- struct_item State @4-8
- function_item status @11-17
- function_item error_code @19-24
- function_item get_results @26-31
- struct_item SyncState @34-34
- function_item new @37-43
- function_item status @45-47
- function_item error_code @49-51
- function_item get_results @53-55
- function_item set_completed @57-76
- function_item spawn @78-94
- struct_item Action @100-100
- struct_item Operation @103-105
- struct_item ActionWithProgress @108-110
- struct_item OperationWithProgress @113-116
- function_item Id @119-121
- function_item Status @122-124
- function_item ErrorCode @125-127
- function_item Cancel @128-130
- function_item Close @131-133
- function_item Id @137-139
- function_item Status @140-142
- function_item ErrorCode @143-145
- function_item Cancel @146-148
- function_item Close @149-151
- function_item Id @155-157
- function_item Status @158-160
- function_item ErrorCode @161-163
- function_item Cancel @164-166
- function_item Close @167-169
- function_item Id @173-175
- function_item Status @176-178
- function_item ErrorCode @179-181
- function_item Cancel @182-184
- function_item Close @185-187
- function_item SetCompleted @191-193
- function_item Completed @194-196
- function_item GetResults @197-199
- function_item SetCompleted @203-205
- function_item Completed @206-208
- function_item GetResults @209-211
- function_item SetCompleted @215-217
- function_item Completed @218-220
- function_item GetResults @221-223
- function_item SetProgress @224-226
- function_item Progress @227-229
- function_item SetCompleted @235-240
- function_item Completed @241-243
- function_item GetResults @244-246
- function_item SetProgress @247-249
- function_item Progress @250-252
- function_item spawn @257-269
- function_item spawn @274-286
- function_item spawn @291-303
- function_item spawn @308-320

### third_party/rust/windows-future/src/bindings.rs

Blob: `ca60743cdc513eca734347c3ac812dcd80e61af8`. Grammar: rust. Status: syntax-clean.

- function_item new @11-24
- function_item Invoke @25-38
- struct_item AsyncActionCompletedHandler_Vtbl @42-49
- struct_item AsyncActionCompletedHandlerBox @51-57
- function_item QueryInterface @72-103
- function_item AddRef @104-109
- function_item Release @110-119
- function_item Invoke @120-129
- struct_item AsyncActionProgressHandler @133-138
- function_item new @156-172
- function_item Invoke @173-187
- struct_item AsyncActionProgressHandler_Vtbl @191-202
- struct_item AsyncActionProgressHandlerBox @204-218
- function_item QueryInterface @239-271
- function_item AddRef @272-277
- function_item Release @278-287
- function_item Invoke @288-301
- struct_item AsyncActionWithProgressCompletedHandler @305-310
- function_item new @330-346
- function_item Invoke @347-360
- struct_item AsyncActionWithProgressCompletedHandler_Vtbl @364-375
- struct_item AsyncActionWithProgressCompletedHandlerBox @377-391
- function_item QueryInterface @412-430
- function_item AddRef @431-436
- function_item Release @437-446
- function_item Invoke @447-456
- struct_item AsyncOperationCompletedHandler @460-465
- function_item new @483-496
- function_item Invoke @497-510
- struct_item AsyncOperationCompletedHandler_Vtbl @514-525
- struct_item AsyncOperationCompletedHandlerBox @527-538
- function_item QueryInterface @556-588
- function_item AddRef @589-594
- function_item Release @595-604
- function_item Invoke @605-614
- struct_item AsyncOperationProgressHandler @618-625
- function_item new @653-669
- function_item Invoke @670-684
- struct_item AsyncOperationProgressHandler_Vtbl @688-701
- struct_item AsyncOperationProgressHandlerBox @703-719
- function_item QueryInterface @742-760
- function_item AddRef @761-766
- function_item Release @767-776
- function_item Invoke @777-790
- struct_item AsyncOperationWithProgressCompletedHandler @794-801
- function_item new @829-845
- function_item Invoke @846-859
- struct_item AsyncOperationWithProgressCompletedHandler_Vtbl @863-876
- struct_item AsyncOperationWithProgressCompletedHandlerBox @878-894
- function_item QueryInterface @917-935
- function_item AddRef @936-941
- function_item Release @942-951
- function_item Invoke @952-961
- struct_item AsyncStatus @965-965
- function_item SetCompleted @995-1007
- function_item Completed @1008-1018
- function_item GetResults @1019-1027
- function_item Id @1028-1038
- function_item Status @1039-1049
- function_item ErrorCode @1050-1060
- function_item Cancel @1061-1067
- function_item Close @1068-1074
- trait_item IAsyncAction_Impl @1081-1088
- function_signature_item SetCompleted @1082-1085
- function_signature_item Completed @1086-1086
- function_signature_item GetResults @1087-1087
- function_item new @1090-1133
- function_item SetCompleted @1091-1100
- function_item Completed @1101-1117
- function_item GetResults @1118-1126
- function_item matches @1134-1136
- struct_item IAsyncAction_Vtbl @1140-1151
- struct_item IAsyncActionWithProgress @1154-1159
- function_item SetProgress @1190-1202
- function_item Progress @1203-1213
- function_item SetCompleted @1214-1226
- function_item Completed @1227-1239
- function_item GetResults @1240-1248
- function_item Id @1249-1259
- function_item Status @1260-1270
- function_item ErrorCode @1271-1281
- function_item Cancel @1282-1288
- function_item Close @1289-1295
- trait_item IAsyncActionWithProgress_Impl @1310-1326
- function_signature_item SetProgress @1314-1317
- function_signature_item Progress @1318-1318
- function_signature_item SetCompleted @1319-1322
- function_signature_item Completed @1323-1324
- function_signature_item GetResults @1325-1325
- function_item new @1328-1434
- function_item SetProgress @1330-1347
- function_item Progress @1348-1368
- function_item SetCompleted @1369-1386
- function_item Completed @1387-1407
- function_item GetResults @1408-1420
- function_item matches @1435-1437
- struct_item IAsyncActionWithProgress_Vtbl @1441-1464
- function_item Id @1480-1490
- function_item Status @1491-1501
- function_item ErrorCode @1502-1512
- function_item Cancel @1513-1519
- function_item Close @1520-1526
- trait_item IAsyncInfo_Impl @1531-1537
- function_signature_item Id @1532-1532
- function_signature_item Status @1533-1533
- function_signature_item ErrorCode @1534-1534
- function_signature_item Cancel @1535-1535
- function_signature_item Close @1536-1536
- function_item new @1539-1614
- function_item Id @1540-1555
- function_item Status @1556-1571
- function_item ErrorCode @1572-1587
- function_item Cancel @1588-1596
- function_item Close @1597-1605
- function_item matches @1615-1617
- struct_item IAsyncInfo_Vtbl @1621-1634
- struct_item IAsyncOperation @1637-1639
- function_item SetCompleted @1670-1682
- function_item Completed @1683-1693
- function_item GetResults @1694-1704
- function_item Id @1705-1715
- function_item Status @1716-1726
- function_item ErrorCode @1727-1737
- function_item Cancel @1738-1744
- function_item Close @1745-1751
- trait_item IAsyncOperation_Impl @1760-1770
- function_signature_item SetCompleted @1764-1767
- function_signature_item Completed @1768-1768
- function_signature_item GetResults @1769-1769
- function_item new @1772-1840
- function_item SetCompleted @1773-1786
- function_item Completed @1787-1807
- function_item GetResults @1808-1828
- function_item matches @1841-1843
- struct_item IAsyncOperation_Vtbl @1847-1865
- struct_item IAsyncOperationWithProgress @1868-1875
- function_item SetProgress @1924-1936
- function_item Progress @1937-1949
- function_item SetCompleted @1950-1962
- function_item Completed @1963-1975
- function_item GetResults @1976-1986
- function_item Id @1987-1997
- function_item Status @1998-2008
- function_item ErrorCode @2009-2019
- function_item Cancel @2020-2026
- function_item Close @2027-2033
- trait_item IAsyncOperationWithProgress_Impl @2054-2072
- function_signature_item SetProgress @2059-2062
- function_signature_item Progress @2063-2063
- function_signature_item SetCompleted @2064-2067
- function_signature_item Completed @2068-2070
- function_signature_item GetResults @2071-2071
- function_item new @2078-2200
- function_item SetProgress @2082-2100
- function_item Progress @2101-2122
- function_item SetCompleted @2123-2141
- function_item Completed @2142-2163
- function_item GetResults @2164-2185
- function_item matches @2201-2203
- struct_item IAsyncOperationWithProgress_Vtbl @2207-2235

### third_party/rust/windows-future/src/bindings_impl.rs

Blob: `8156f0bd70caa3fb6058b9ae169e4be8518a4cc6`. Grammar: rust. Status: syntax-clean.

- struct_item SECURITY_ATTRIBUTES @10-14
- function_item default @16-18

### third_party/rust/windows-future/src/future.rs

Blob: `bd57857721eb3010d0f666d7bf836425b6902b18`. Grammar: rust. Status: syntax-clean.

- struct_item AsyncFuture @10-24
- function_item new @27-34
- function_item poll @44-80
- function_item into_future @91-93
- function_item into_future @100-102
- function_item into_future @109-111
- function_item into_future @118-120

### third_party/rust/windows-future/src/join.rs

Blob: `3e29c62af96ceb4e7a17b2c8018b9eb15078b1fb`. Grammar: rust. Status: syntax-clean.

- function_item join @5-7
- function_item join @12-14
- function_item join @19-21
- function_item join @26-28

### third_party/rust/windows-future/src/lib.rs

Blob: `c5d764ae69aae9a5c67319c63e99e0e6741df135`. Grammar: rust. Status: syntax-clean.

- mod_item r#async @11-11
- mod_item bindings @12-12
- mod_item bindings_impl @13-13
- mod_item join @14-14
- mod_item waiter @15-15
- mod_item when @16-16
- mod_item async_ready @25-25
- mod_item async_spawn @27-27
- mod_item future @29-29

### third_party/rust/windows-future/src/waiter.rs

Blob: `6c3a9a79333678972b231c38b7027faed7847e5c`. Grammar: rust. Status: syntax-clean.

- struct_item Waiter @3-3
- struct_item WaiterSignaler @4-4
- function_item new @8-17
- function_item signal @26-31
- function_item drop @35-40

### third_party/rust/windows-future/src/when.rs

Blob: `7f231fac4ff428ab98c7e6a2b0720333a2bf41f2`. Grammar: rust. Status: syntax-clean.

- function_item when @5-10
- function_item when @15-20
- function_item when @25-30
- function_item when @35-40

### third_party/rust/windows-implement/src/gen.rs

Blob: `d6a31c11495dfb015d912cd0f737bf9aa3d102cb`. Grammar: rust. Status: syntax-clean.

- function_item gen_all @18-35
- function_item gen_original_impl @40-61
- function_item gen_impl_struct @64-95
- function_item gen_impl_deref @98-114
- function_item gen_impl_impl @131-171
- function_item gen_iunknown_impl @174-243
- function_item gen_impl_com_object_inner @246-275
- function_item gen_query_interface @278-376
- function_item gen_into_outer @380-427
- function_item gen_into_static @431-442
- function_item gen_impl_from @469-512
- function_item gen_impl_com_object_interfaces @519-569
- function_item gen_impl_as_impl @572-600

### third_party/rust/windows-implement/src/lib.rs

Blob: `a883007fcc9bdce4a462d23d962bb8dc37a0778f`. Grammar: rust. Status: syntax-clean.

- mod_item r#gen @9-9
- mod_item tests @13-13
- function_item implement @40-45
- function_item implement_core @47-87
- struct_item ImplementInputs @90-118
- struct_item InterfaceChain @121-130
- struct_item ImplementType @132-138
- function_item to_ident @141-146
- function_item to_vtbl_ident @147-152
- struct_item ImplementAttributes @156-160
- function_item parse @163-174
- function_item parse_implement @178-187
- function_item walk_implement @189-216
- enum_item UseTree2 @219-225
- function_item to_element_type @228-264
- struct_item UsePath2 @267-270
- struct_item UseName2 @272-275
- struct_item UseGroup2 @277-280
- function_item parse @283-353
- function_item convert_implements_to_interface_chains @356-389
- function_item get_interface_ident_suffix @391-406

### third_party/rust/windows-implement/src/tests.rs

Blob: `3f5c3493aa001f2d7c7795fe7a35a6a2cefbc2bf`. Grammar: rust. Status: syntax-clean.

- function_item implement @18-27
- function_item rustfmt @29-67
- function_item simple_type @70-79
- function_item zero_sized_type @82-89
- function_item no_interfaces @92-99
- function_item generic_no_lifetime @102-113
- function_item generic_with_lifetime @116-125
- function_item tuple_type @128-135

### third_party/rust/windows-interface/src/lib.rs

Blob: `9c65736e71433c67fac4cc4e9cc51ac43f4c2d15`. Grammar: rust. Status: syntax-clean.

- function_item interface @35-46
- struct_item Interface @79-85
- function_item gen_tokens @89-121
- function_item gen_implementation @124-160
- function_item get_com_trait @162-187
- function_item gen_vtable @190-361
- function_item gen_conversions @364-395
- function_item parent_type @397-403
- function_item parent_vtable @405-412
- function_item parent_is_iunknown @414-420
- function_item parent_path @422-432
- function_item parent_trait_constraint @435-444
- function_item parse @448-479
- struct_item Guid @491-491
- function_item to_tokens @494-575
- function_item hex_lit @495-497
- function_item ensure_length @499-528
- function_item parse @579-583
- struct_item InterfaceMethod @595-601
- function_item is_result @604-621
- function_item gen_args @624-633
- function_item gen_consume_generics @635-652
- function_item gen_consume_params @654-670
- function_item gen_consume_args @672-689
- function_item parse @693-732
- struct_item InterfaceMethodArg @736-741
- function_item borrow_type @744-761

### third_party/rust/windows-link/src/lib.rs

Blob: `dbecf9f3b5e4fee95ebcb9768608ae19b990797d`. Grammar: rust. Status: syntax-clean.


### third_party/rust/windows-numerics/src/bindings.rs

Blob: `1cbe2600022b6e7d9c2fef9720f500b2fcc83e0a`. Grammar: rust. Status: syntax-clean.

- struct_item Matrix3x2 @3-10
- struct_item Matrix4x4 @21-38
- struct_item Vector2 @47-50
- struct_item Vector3 @61-65
- struct_item Vector4 @76-81

### third_party/rust/windows-numerics/src/lib.rs

Blob: `4aca65e500413b8f941451a0ed12a11963b80000`. Grammar: rust. Status: syntax-clean.

- mod_item bindings @5-5
- mod_item matrix3x2 @8-8
- mod_item matrix4x4 @9-9
- mod_item vector2 @10-10
- mod_item vector3 @11-11
- mod_item vector4 @12-12

### third_party/rust/windows-numerics/src/matrix3x2.rs

Blob: `bd7f18bd44e4bcb1f604637678091362acf59627`. Grammar: rust. Status: syntax-clean.

- function_item identity @4-13
- function_item translation @14-23
- function_item rotation @24-26
- function_item rotation_around @27-34
- function_item scale @35-37
- function_item scale_around @38-47
- function_item skew @48-50
- function_item skew_around @51-58
- function_item impl_add @59-68
- function_item impl_sub @69-78
- function_item impl_mul @79-88
- function_item impl_mul_f32 @89-98
- function_item add @103-105
- function_item add @109-111
- function_item add @115-117
- function_item add @121-123
- function_item sub @127-129
- function_item sub @133-135
- function_item sub @139-141
- function_item sub @145-147
- function_item mul @151-153
- function_item mul @157-159
- function_item mul @163-165
- function_item mul @169-171
- function_item mul @175-177
- function_item mul @181-183

### third_party/rust/windows-numerics/src/matrix4x4.rs

Blob: `0ad311af605e39333f817a13c85bb59931a2df5d`. Grammar: rust. Status: syntax-clean.

- function_item translation @4-23
- function_item rotation_y @24-50
- function_item perspective_projection @51-71
- function_item impl_add @72-91
- function_item impl_sub @92-111
- function_item impl_mul @112-131
- function_item impl_mul_f32 @132-151
- function_item add @156-158
- function_item add @162-164
- function_item add @168-170
- function_item add @174-176
- function_item sub @180-182
- function_item sub @186-188
- function_item sub @192-194
- function_item sub @198-200
- function_item mul @204-206
- function_item mul @210-212
- function_item mul @216-218
- function_item mul @222-224
- function_item mul @228-230
- function_item mul @234-236

### third_party/rust/windows-numerics/src/vector2.rs

Blob: `2d4d8178894ed69c1d5c6ac1c7e929d602c8a78c`. Grammar: rust. Status: syntax-clean.

- function_item new @4-6
- function_item zero @7-9
- function_item one @10-12
- function_item unit_x @13-15
- function_item unit_y @16-18
- function_item dot @19-21
- function_item length_squared @22-24
- function_item length @26-28
- function_item distance @30-32
- function_item distance_squared @33-35
- function_item normalize @37-39
- function_item impl_add @41-46
- function_item impl_sub @47-52
- function_item impl_div @53-58
- function_item impl_div_f32 @59-64
- function_item impl_mul @65-70
- function_item impl_mul_f32 @71-76
- function_item add @81-83
- function_item add @87-89
- function_item add @93-95
- function_item add @99-101
- function_item sub @105-107
- function_item sub @111-113
- function_item sub @117-119
- function_item sub @123-125
- function_item div @129-131
- function_item div @135-137
- function_item div @141-143
- function_item div @147-149
- function_item div @153-155
- function_item div @159-161
- function_item mul @165-167
- function_item mul @171-173
- function_item mul @177-179
- function_item mul @183-185
- function_item mul @189-191
- function_item mul @195-197

### third_party/rust/windows-numerics/src/vector3.rs

Blob: `c42255775f41170f8f0b8f902fa91cd846e1106e`. Grammar: rust. Status: syntax-clean.

- function_item new @4-6
- function_item zero @7-13
- function_item one @14-20
- function_item unit_x @21-27
- function_item unit_y @28-34
- function_item unit_z @35-41
- function_item dot @42-44
- function_item length_squared @45-47
- function_item length @49-51
- function_item distance @53-55
- function_item distance_squared @56-58
- function_item normalize @60-62
- function_item impl_add @64-70
- function_item impl_sub @71-77
- function_item impl_div @78-84
- function_item impl_div_f32 @85-91
- function_item impl_mul @92-98
- function_item impl_mul_f32 @99-105
- function_item add @110-112
- function_item add @116-118
- function_item add @122-124
- function_item add @128-130
- function_item sub @134-136
- function_item sub @140-142
- function_item sub @146-148
- function_item sub @152-154
- function_item div @158-160
- function_item div @164-166
- function_item div @170-172
- function_item div @176-178
- function_item div @182-184
- function_item div @188-190
- function_item mul @194-196
- function_item mul @200-202
- function_item mul @206-208
- function_item mul @212-214
- function_item mul @218-220
- function_item mul @224-226

### third_party/rust/windows-numerics/src/vector4.rs

Blob: `790bd81c045396bee8a1a952c1afdc32033e8ea2`. Grammar: rust. Status: syntax-clean.

- function_item new @4-6
- function_item zero @7-14
- function_item one @15-22
- function_item unit_x @23-30
- function_item unit_y @31-38
- function_item unit_z @39-46
- function_item unit_w @47-54
- function_item dot @55-57
- function_item length_squared @58-60
- function_item length @62-64
- function_item distance @66-68
- function_item distance_squared @69-71
- function_item normalize @73-75
- function_item impl_add @77-84
- function_item impl_sub @85-92
- function_item impl_div @93-100
- function_item impl_div_f32 @101-108
- function_item impl_mul @109-116
- function_item impl_mul_f32 @117-124
- function_item add @129-131
- function_item add @135-137
- function_item add @141-143
- function_item add @147-149
- function_item sub @153-155
- function_item sub @159-161
- function_item sub @165-167
- function_item sub @171-173
- function_item div @177-179
- function_item div @183-185
- function_item div @189-191
- function_item div @195-197
- function_item div @201-203
- function_item div @207-209
- function_item mul @213-215
- function_item mul @219-221
- function_item mul @225-227
- function_item mul @231-233
- function_item mul @237-239
- function_item mul @243-245

### third_party/rust/windows-result/src/bindings.rs

Blob: `696f12a2985c1beadf4906f8e6c28ff7d3712c48`. Grammar: rust. Status: syntax-clean.

- struct_item GUID @23-28
- function_item from_u128 @30-37
- struct_item IErrorInfo_Vtbl @46-53
- struct_item IRestrictedErrorInfo_Vtbl @56-66
- struct_item IUnknown_Vtbl @69-77

### third_party/rust/windows-result/src/bool.rs

Blob: `650df3672b227a6f353c965eeba5a83442af70b6`. Grammar: rust. Status: syntax-clean.

- struct_item BOOL @7-7
- function_item as_bool @12-14
- function_item ok @18-24
- function_item unwrap @29-31
- function_item expect @36-38
- function_item from @42-44
- function_item from @48-50
- function_item from @54-60
- function_item from @64-66
- function_item eq @70-72
- function_item eq @76-78
- function_item not @83-89

### third_party/rust/windows-result/src/bstr.rs

Blob: `86b8c2caafa0ececca3fbea2a2670a143ce4e4f9`. Grammar: rust. Status: syntax-clean.

- struct_item BasicString @5-5
- function_item deref @10-25
- function_item default @29-31
- function_item drop @35-39

### third_party/rust/windows-result/src/com.rs

Blob: `21cacb99d995442f74664a049b19410e75e61d03`. Grammar: rust. Status: syntax-clean.

- struct_item ComPtr @12-12
- function_item as_raw @15-17
- function_item cast @19-28
- function_item eq @32-34
- function_item clone @40-45
- function_item drop @49-53

### third_party/rust/windows-result/src/error.rs

Blob: `ce5331310a5ecd47f6e48ad05c49db84f91f3284`. Grammar: rust. Status: syntax-clean.

- struct_item Error @46-55
- function_item const_nonzero_i32 @64-70
- function_item nonzero_hresult @72-78
- function_item empty @82-87
- function_item new @91-107
- function_item from_hresult @110-115
- function_item from_thread @118-120
- function_item code @123-129
- function_item message @132-139
- function_item as_ptr @143-145
- function_item from @152-156
- function_item from @160-165
- function_item from @170-172
- function_item from @177-182
- function_item from @186-188
- function_item from @192-194
- function_item from @198-200
- function_item fmt @204-210
- function_item fmt @214-221
- function_item hash @225-228
- function_item eq @233-235
- function_item partial_cmp @241-243
- function_item cmp @247-249
- mod_item error_info @255-352
- struct_item ErrorInfo @265-267
- function_item empty @270-272
- function_item from_thread @274-282
- function_item into_thread @284-290
- function_item originate_error @292-297
- function_item message @299-339
- function_item as_ptr @341-347
- mod_item error_info @355-388
- struct_item EmptyErrorInfo @361-361
- function_item empty @366-368
- function_item from_thread @370-372
- function_item into_thread @374-374
- function_item originate_error @377-377
- function_item message @379-381
- function_item as_ptr @384-386

### third_party/rust/windows-result/src/hresult.rs

Blob: `42f833ab73e4629cb20985a9a84e085538215fb5`. Grammar: rust. Status: syntax-clean.

- struct_item HRESULT @7-7
- function_item is_ok @12-14
- function_item is_err @18-20
- function_item unwrap @28-30
- function_item ok @34-40
- function_item map @45-51
- function_item and_then @56-62
- function_item message @65-113
- function_item from_thread @116-126
- function_item from_win32 @129-135
- function_item from_nt @138-144
- function_item from @148-153
- function_item fmt @157-159
- function_item fmt @163-165

### third_party/rust/windows-result/src/lib.rs

Blob: `cdc12164f29dacbe1b21d562e8534881c5603a15`. Grammar: rust. Status: syntax-clean.

- mod_item bindings @17-17
- mod_item com @21-21
- mod_item strings @24-24
- mod_item bstr @29-29
- mod_item error @31-31
- mod_item hresult @34-34
- mod_item bool @37-37

### third_party/rust/windows-result/src/strings.rs

Blob: `ce77f1f717641703a36e646a08179c194b7da156`. Grammar: rust. Status: syntax-clean.

- struct_item HeapString @3-3
- function_item default @6-8
- function_item drop @12-18
- function_item wide_trim_end @21-29

### third_party/rust/windows-strings/src/bindings.rs

Blob: `2e0ad17d1637589f7024e1e2b15b73f43a5a2c03`. Grammar: rust. Status: syntax-clean.


### third_party/rust/windows-strings/src/bstr.rs

Blob: `e2df203bfe76cc22e08b3890d3687d45d7c55c6f`. Grammar: rust. Status: syntax-clean.

- struct_item BSTR @7-7
- function_item new @13-15
- function_item from_wide @18-35
- function_item from_raw @39-41
- function_item into_raw @45-47
- function_item deref @53-68
- function_item clone @72-74
- function_item from @78-81
- function_item from @85-87
- function_item from @91-93
- function_item try_from @99-101
- function_item try_from @107-109
- function_item default @113-115
- function_item fmt @119-125
- function_item fmt @129-131
- function_item eq @135-137
- function_item eq @143-145
- function_item eq @149-151
- function_item eq @155-157
- function_item drop @161-165

### third_party/rust/windows-strings/src/decode.rs

Blob: `7ac03ca886d2c18a3d8b4bc44e100fc17a62de5a`. Grammar: rust. Status: syntax-clean.

- struct_item Decode @2-2
- function_item fmt @9-16
- function_item decode_utf8 @20-58

### third_party/rust/windows-strings/src/hstring.rs

Blob: `ca8a2376d3dd5546c3953dfa8676da78bc5450bb`. Grammar: rust. Status: syntax-clean.

- struct_item HSTRING @7-7
- function_item new @13-15
- function_item from_wide @18-20
- function_item to_string_lossy @23-25
- function_item to_os_string @29-31
- function_item from_wide_iter @35-58
- function_item as_header @60-62
- function_item deref @68-77
- function_item default @81-83
- function_item clone @87-93
- function_item drop @97-107
- function_item fmt @114-120
- function_item fmt @124-126
- function_item from @130-132
- function_item from @136-138
- function_item from @142-144
- function_item from @149-151
- function_item from @156-163
- function_item from @168-170
- function_item from @175-177
- function_item cmp @183-185
- function_item hash @189-191
- function_item partial_cmp @195-197
- function_item eq @201-203
- function_item eq @207-209
- function_item eq @213-215
- function_item eq @219-221
- function_item eq @225-227
- function_item eq @231-233
- function_item eq @237-239
- function_item eq @243-245
- function_item eq @249-251
- function_item eq @255-257
- function_item eq @261-263
- function_item eq @267-269
- function_item eq @273-275
- function_item eq @280-282
- function_item eq @287-289
- function_item eq @294-296
- function_item eq @301-305
- function_item eq @310-312
- function_item eq @317-319
- function_item eq @324-326
- function_item eq @331-333
- function_item eq @338-340
- function_item eq @345-347
- function_item eq @352-354
- function_item eq @359-361
- function_item try_from @367-369
- function_item try_from @375-377
- function_item from @382-384
- function_item from @389-391

### third_party/rust/windows-strings/src/hstring_builder.rs

Blob: `52dc1515d756c13d72fc71ab7b045b58beb03028`. Grammar: rust. Status: syntax-clean.

- struct_item HStringBuilder @7-7
- function_item new @11-19
- function_item trim_end @22-37
- function_item as_bytes_mut @40-48
- function_item as_header @50-52
- function_item as_header_mut @54-56
- function_item from @60-69
- function_item deref @75-81
- function_item deref_mut @85-91
- function_item drop @95-99
- function_item fmt @103-109

### third_party/rust/windows-strings/src/hstring_header.rs

Blob: `39401102db3c695aaf0e5677f33903ce402c18b0`. Grammar: rust. Status: syntax-clean.

- struct_item HStringHeader @6-14
- function_item alloc @17-42
- function_item free @44-52
- function_item duplicate @54-69

### third_party/rust/windows-strings/src/lib.rs

Blob: `4024abfb66f61d1730d0133dbd67804458d3e752`. Grammar: rust. Status: syntax-clean.

- mod_item bstr @9-9
- mod_item hstring @12-12
- mod_item hstring_builder @15-15
- mod_item hstring_header @18-18
- mod_item bindings @21-21
- mod_item decode @23-23
- mod_item ref_count @26-26
- mod_item literals @29-29
- mod_item pcstr @32-32
- mod_item pcwstr @35-35
- mod_item pstr @38-38
- mod_item pwstr @41-41
- function_signature_item strlen @45-45

### third_party/rust/windows-strings/src/literals.rs

Blob: `395f0d073faaa1d6b7c1964f4724524926728137`. Grammar: rust. Status: syntax-clean.

- function_item decode_utf8_char @77-139
- function_item utf16_len @142-150
- mod_item tests @153-165
- function_item test @157-164

### third_party/rust/windows-strings/src/pcstr.rs

Blob: `cd7528542336c4bb2e046db0333be51f96eca5da`. Grammar: rust. Status: syntax-clean.

- struct_item PCSTR @6-6
- function_item from_raw @10-12
- function_item null @15-17
- function_item as_ptr @20-22
- function_item is_null @25-27
- function_item as_bytes @34-39
- function_item to_string @46-48
- function_item display @55-57
- function_item default @61-63

### third_party/rust/windows-strings/src/pcwstr.rs

Blob: `c98d40c840991c144ba1ba6901f2e88438530ab7`. Grammar: rust. Status: syntax-clean.

- struct_item PCWSTR @6-6
- function_item from_raw @10-12
- function_item null @15-17
- function_item as_ptr @20-22
- function_item is_null @25-27
- function_item len @34-39
- function_signature_item wcslen @36-36
- function_item is_empty @46-48
- function_item as_wide @55-57
- function_item to_string @64-66
- function_item to_hstring @73-75
- function_item display @82-84
- function_item default @88-90
- function_item as_ref @94-96

### third_party/rust/windows-strings/src/pstr.rs

Blob: `141d481ba0eb55652b086b0efb3da7c3c0ae8224`. Grammar: rust. Status: syntax-clean.

- struct_item PSTR @6-6
- function_item from_raw @10-12
- function_item null @15-17
- function_item as_ptr @20-22
- function_item is_null @25-27
- function_item as_bytes @34-39
- function_item to_string @46-48
- function_item display @55-57
- function_item default @61-63

### third_party/rust/windows-strings/src/pwstr.rs

Blob: `db4d74ac7b57ec1ad9833a6c73dab48a37aef8b9`. Grammar: rust. Status: syntax-clean.

- struct_item PWSTR @6-6
- function_item from_raw @10-12
- function_item null @15-17
- function_item as_ptr @20-22
- function_item is_null @25-27
- function_item len @34-36
- function_item is_empty @43-45
- function_item as_wide @52-54
- function_item to_string @61-63
- function_item to_hstring @70-72
- function_item display @79-81
- function_item default @85-87

### third_party/rust/windows-strings/src/ref_count.rs

Blob: `c6309f9fc9a2edfb6cb36668205e4259b2d8aed9`. Grammar: rust. Status: syntax-clean.

- struct_item RefCount @5-5
- function_item new @8-10
- function_item add_ref @12-14
- function_item release @16-26

### third_party/rust/windows-sys/src/Windows/Wdk/Devices/Bluetooth/mod.rs

Blob: `7474dcadaa49167be774e1f46e9c868a30ab9824`. Grammar: rust. Status: syntax-clean.


### third_party/rust/windows-sys/src/Windows/Wdk/Devices/HumanInterfaceDevice/mod.rs

Blob: `3aea81279958f7ea8e3ec640372e2e49963aac36`. Grammar: rust. Status: syntax-clean.

- struct_item HID_XFER_PACKET @11-15
- function_item default @17-19
- struct_item VHF_CONFIG @23-44
- function_item default @46-48

### third_party/rust/windows-sys/src/Windows/Wdk/Devices/mod.rs

Blob: `e90977f98bee340aa53760768c2ada8a5dae7cb7`. Grammar: rust. Status: syntax-clean.

- mod_item Bluetooth @2-2
- mod_item HumanInterfaceDevice @4-4

### third_party/rust/windows-sys/src/Windows/Wdk/Foundation/mod.rs

Blob: `f00d889816f375c1fe9cdeef8d3b0ae75a79407e`. Grammar: rust. Status: syntax-clean.

- struct_item ACCESS_STATE @6-23
- function_item default @26-28
- function_item default @39-41
- struct_item DEVICE_OBJECT @46-72
- function_item default @75-77
- function_item default @88-90
- struct_item DEVOBJ_EXTENSION @95-112
- function_item default @115-117
- struct_item DISPATCHER_HEADER @122-126
- function_item default @129-131
- function_item default @147-149
- function_item default @160-162
- struct_item DISPATCHER_HEADER_0_1 @167-172
- struct_item DISPATCHER_HEADER_0_2 @176-181
- function_item default @184-186
- function_item default @197-199
- struct_item DISPATCHER_HEADER_0_2_0_0 @204-206
- function_item default @216-218
- struct_item DISPATCHER_HEADER_0_2_1_0 @223-225
- struct_item DISPATCHER_HEADER_0_3 @229-234
- function_item default @237-239
- function_item default @250-252
- struct_item DISPATCHER_HEADER_0_3_0_0 @257-259
- struct_item DISPATCHER_HEADER_0_4 @263-268
- function_item default @271-273
- function_item default @284-286
- struct_item DISPATCHER_HEADER_0_4_0_0 @291-293
- struct_item DISPATCHER_HEADER_0_5 @297-302
- function_item default @305-307
- function_item default @318-320
- struct_item DISPATCHER_HEADER_0_5_0_0 @325-327
- function_item default @336-338
- struct_item DISPATCHER_HEADER_0_6 @343-348
- struct_item DRIVER_EXTENSION @363-368
- function_item default @371-373
- struct_item DRIVER_OBJECT @383-399
- function_item default @402-404
- struct_item ERESOURCE @419-433
- function_item default @436-438
- function_item default @449-451
- struct_item ERESOURCE_0_0 @456-459
- function_item default @469-471
- struct_item FAST_IO_DISPATCH @488-517
- struct_item FAST_MUTEX @563-569
- function_item default @572-574
- struct_item FILE_OBJECT @579-610
- function_item default @613-615
- struct_item IO_COMPLETION_CONTEXT @621-625
- function_item default @627-629
- struct_item IO_SECURITY_CONTEXT @635-640
- function_item default @643-645
- struct_item IO_STACK_LOCATION @650-660
- function_item default @663-665
- function_item default @713-715
- struct_item IO_STACK_LOCATION_0_2 @720-726
- function_item default @729-731
- struct_item IO_STACK_LOCATION_0_1 @736-742
- function_item default @745-747
- struct_item IO_STACK_LOCATION_0_0 @752-758
- function_item default @761-763
- struct_item IO_STACK_LOCATION_0_26 @768-770
- function_item default @773-775
- struct_item IO_STACK_LOCATION_0_16 @780-785
- function_item default @788-790
- struct_item IO_STACK_LOCATION_0_14 @795-800
- function_item default @803-805
- struct_item IO_STACK_LOCATION_0_27 @810-812
- function_item default @815-817
- struct_item IO_STACK_LOCATION_0_15 @822-826
- function_item default @829-831
- struct_item IO_STACK_LOCATION_0_19 @836-839
- function_item default @842-844
- struct_item IO_STACK_LOCATION_0_7 @849-853
- struct_item IO_STACK_LOCATION_0_6 @857-860
- struct_item IO_STACK_LOCATION_0_38 @864-869
- function_item default @872-874
- struct_item IO_STACK_LOCATION_0_34 @879-881
- function_item default @884-886
- struct_item IO_STACK_LOCATION_0_35 @891-896
- function_item default @899-901
- function_item default @912-914
- struct_item IO_STACK_LOCATION_0_24 @919-921
- struct_item IO_STACK_LOCATION_0_31 @925-928
- struct_item IO_STACK_LOCATION_0_5 @932-937
- function_item default @940-942
- struct_item IO_STACK_LOCATION_0_10 @947-952
- function_item default @955-957
- struct_item IO_STACK_LOCATION_0_8 @962-965
- struct_item IO_STACK_LOCATION_0_30 @969-971
- struct_item IO_STACK_LOCATION_0_25 @975-981
- function_item default @984-986
- struct_item IO_STACK_LOCATION_0_22 @991-996
- function_item default @999-1001
- struct_item IO_STACK_LOCATION_0_17 @1006-1009
- struct_item IO_STACK_LOCATION_0_12 @1013-1016
- struct_item IO_STACK_LOCATION_0_28 @1020-1025
- function_item default @1028-1030
- struct_item IO_STACK_LOCATION_0_3 @1035-1039
- struct_item IO_STACK_LOCATION_0_21 @1043-1045
- function_item default @1048-1050
- struct_item IO_STACK_LOCATION_0_11 @1055-1057
- struct_item IO_STACK_LOCATION_0_9 @1061-1066
- function_item default @1069-1071
- function_item default @1083-1085
- struct_item IO_STACK_LOCATION_0_9_0_0 @1090-1093
- struct_item IO_STACK_LOCATION_0_29 @1097-1099
- struct_item IO_STACK_LOCATION_0_23 @1103-1105
- struct_item IO_STACK_LOCATION_0_18 @1109-1112
- function_item default @1115-1117
- struct_item IO_STACK_LOCATION_0_13 @1122-1125
- struct_item IO_STACK_LOCATION_0_36 @1129-1132
- function_item default @1135-1137
- struct_item IO_STACK_LOCATION_0_32 @1142-1146
- function_item default @1149-1151
- struct_item IO_STACK_LOCATION_0_20 @1156-1159
- function_item default @1162-1164
- struct_item IO_STACK_LOCATION_0_37 @1169-1174
- function_item default @1177-1179
- struct_item IO_STACK_LOCATION_0_33 @1184-1186
- struct_item IO_STACK_LOCATION_0_4 @1190-1194
- struct_item IRP @1198-1220
- function_item default @1223-1225
- function_item default @1236-1238
- function_item default @1250-1252
- function_item default @1263-1265
- struct_item IRP_2_0 @1270-1273
- function_item default @1276-1278
- function_item default @1289-1291
- function_item default @1302-1304
- function_item default @1316-1318
- struct_item IRP_3_0 @1323-1329
- function_item default @1332-1334
- function_item default @1345-1347
- struct_item IRP_3_0_0_0 @1352-1354
- function_item default @1357-1359
- struct_item IRP_3_0_1 @1364-1367
- function_item default @1370-1372
- function_item default @1383-1385
- struct_item KDEVICE_QUEUE @1395-1401
- struct_item KDPC @1405-1414
- function_item default @1417-1419
- function_item default @1430-1432
- struct_item KDPC_0_0 @1437-1441
- struct_item KEVENT @1446-1448
- function_item default @1451-1453
- struct_item KMUTANT @1460-1466
- function_item default @1469-1471
- function_item default @1482-1484
- struct_item KMUTANT_0_0 @1489-1491
- struct_item KQUEUE @1497-1503
- function_item default @1506-1508
- struct_item KWAIT_BLOCK @1518-1526
- function_item default @1529-1531
- function_item default @1543-1545
- struct_item MDL @1568-1577
- function_item default @1579-1581
- struct_item OBJECT_ATTRIBUTES @1608-1615
- function_item default @1618-1620
- struct_item OBJECT_ATTRIBUTES32 @1625-1632
- function_item default @1635-1637
- struct_item OBJECT_ATTRIBUTES64 @1642-1649
- function_item default @1652-1654
- struct_item OBJECT_NAME_INFORMATION @1659-1661
- struct_item OWNER_ENTRY @1664-1667
- function_item default @1669-1671
- function_item default @1680-1682
- struct_item OWNER_ENTRY_0_0 @1686-1688
- struct_item RTL_SPLAY_LINKS @1727-1731
- function_item default @1733-1735
- struct_item SECTION_OBJECT_POINTERS @1739-1743
- function_item default @1745-1747
- struct_item SECURITY_SUBJECT_CONTEXT @1752-1757
- function_item default @1760-1762
- struct_item TARGET_DEVICE_CUSTOM_NOTIFICATION @1775-1782
- function_item default @1785-1787
- struct_item VPB @1792-1802
- function_item default @1805-1807
- struct_item WORK_QUEUE_ITEM @1812-1816
- function_item default @1819-1821

### third_party/rust/windows-sys/src/Windows/Wdk/Graphics/Direct3D/mod.rs

Blob: `482f288aee1882e2035f40ff6bd166c3446bb2c5`. Grammar: rust. Status: syntax-clean.

- struct_item D3DDDIARG_CREATERESOURCE @186-200
- function_item default @202-204
- struct_item D3DDDIARG_CREATERESOURCE2 @208-223
- function_item default @225-227
- struct_item D3DDDICB_DESTROYALLOCATION2FLAGS @231-233
- function_item default @235-237
- function_item default @246-248
- struct_item D3DDDICB_DESTROYALLOCATION2FLAGS_0_0 @252-254
- struct_item D3DDDICB_LOCK2FLAGS @257-259
- function_item default @261-263
- function_item default @272-274
- struct_item D3DDDICB_LOCK2FLAGS_0_0 @278-280
- struct_item D3DDDICB_LOCKFLAGS @283-285
- function_item default @287-289
- function_item default @298-300
- struct_item D3DDDICB_LOCKFLAGS_0_0 @304-306
- struct_item D3DDDICB_SIGNALFLAGS @309-311
- function_item default @313-315
- function_item default @324-326
- struct_item D3DDDICB_SIGNALFLAGS_0_0 @330-332
- struct_item D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE @442-444
- function_item default @446-448
- function_item default @457-459
- struct_item D3DDDIGPUVIRTUALADDRESS_PROTECTION_TYPE_0_0 @463-465
- struct_item D3DDDIRECT @495-500
- struct_item D3DDDI_ALLOCATIONINFO @503-510
- function_item default @512-514
- function_item default @523-525
- struct_item D3DDDI_ALLOCATIONINFO_0_0 @529-531
- struct_item D3DDDI_ALLOCATIONINFO2 @534-544
- function_item default @546-548
- function_item default @557-559
- function_item default @568-570
- function_item default @579-581
- struct_item D3DDDI_ALLOCATIONINFO2_1_0 @585-587
- struct_item D3DDDI_ALLOCATIONLIST @590-593
- function_item default @595-597
- function_item default @606-608
- struct_item D3DDDI_ALLOCATIONLIST_0_0 @612-614
- struct_item D3DDDI_CREATECONTEXTFLAGS @650-652
- function_item default @654-656
- function_item default @665-667
- struct_item D3DDDI_CREATECONTEXTFLAGS_0_0 @671-673
- struct_item D3DDDI_CREATEHWCONTEXTFLAGS @676-678
- function_item default @680-682
- function_item default @691-693
- struct_item D3DDDI_CREATEHWCONTEXTFLAGS_0_0 @697-699
- struct_item D3DDDI_CREATEHWQUEUEFLAGS @702-704
- function_item default @706-708
- function_item default @717-719
- struct_item D3DDDI_CREATEHWQUEUEFLAGS_0_0 @723-725
- struct_item D3DDDI_CREATENATIVEFENCEINFO @728-736
- function_item default @738-740
- struct_item D3DDDI_DESTROYPAGINGQUEUE @744-746
- struct_item D3DDDI_DRIVERESCAPE_CPUEVENTUSAGE @760-765
- function_item default @767-769
- struct_item D3DDDI_DRIVERESCAPE_TRANSLATEALLOCATIONEHANDLE @773-776
- struct_item D3DDDI_DRIVERESCAPE_TRANSLATERESOURCEHANDLE @779-782
- struct_item D3DDDI_DXGI_RGB @785-789
- struct_item D3DDDI_ESCAPEFLAGS @792-794
- function_item default @796-798
- function_item default @807-809
- struct_item D3DDDI_ESCAPEFLAGS_0_0 @813-815
- struct_item D3DDDI_EVICT_FLAGS @818-820
- function_item default @822-824
- function_item default @833-835
- struct_item D3DDDI_EVICT_FLAGS_0_0 @839-841
- struct_item D3DDDI_GAMMA_RAMP_DXGI_1 @859-863
- function_item default @865-867
- struct_item D3DDDI_GAMMA_RAMP_RGB256x3x16 @871-875
- function_item default @877-879
- struct_item D3DDDI_GETRESOURCEPRESENTPRIVATEDRIVERDATA @883-887
- function_item default @889-891
- struct_item D3DDDI_HDR_METADATA_HDR10 @895-904
- function_item default @906-908
- struct_item D3DDDI_HDR_METADATA_HDR10PLUS @912-914
- function_item default @916-918
- struct_item D3DDDI_KERNELOVERLAYINFO @926-932
- function_item default @934-936
- struct_item D3DDDI_MAKERESIDENT @940-948
- function_item default @950-952
- struct_item D3DDDI_MAKERESIDENT_FLAGS @956-958
- function_item default @960-962
- function_item default @971-973
- struct_item D3DDDI_MAKERESIDENT_FLAGS_0_0 @977-979
- struct_item D3DDDI_MAPGPUVIRTUALADDRESS @982-996
- function_item default @998-1000
- struct_item D3DDDI_MULTISAMPLINGMETHOD @1010-1013
- struct_item D3DDDI_NATIVEFENCEMAPPING @1016-1020
- function_item default @1022-1024
- struct_item D3DDDI_OFFER_FLAGS @1028-1030
- function_item default @1032-1034
- function_item default @1043-1045
- struct_item D3DDDI_OFFER_FLAGS_0_0 @1049-1051
- struct_item D3DDDI_OPENALLOCATIONINFO @1060-1064
- function_item default @1066-1068
- struct_item D3DDDI_OPENALLOCATIONINFO2 @1072-1078
- function_item default @1080-1082
- struct_item D3DDDI_PATCHLOCATIONLIST @1098-1105
- function_item default @1107-1109
- function_item default @1118-1120
- struct_item D3DDDI_PATCHLOCATIONLIST_0_0 @1124-1126
- struct_item D3DDDI_QUERYREGISTRY_FLAGS @1134-1136
- function_item default @1138-1140
- function_item default @1149-1151
- struct_item D3DDDI_QUERYREGISTRY_FLAGS_0_0 @1155-1157
- struct_item D3DDDI_QUERYREGISTRY_INFO @1160-1169
- function_item default @1171-1173
- function_item default @1184-1186
- struct_item D3DDDI_RATIONAL @1198-1201
- struct_item D3DDDI_RESERVEGPUVIRTUALADDRESS @1208-1218
- function_item default @1220-1222
- function_item default @1231-1233
- function_item default @1242-1244
- function_item default @1253-1255
- function_item default @1264-1266
- struct_item D3DDDI_RESOURCEFLAGS @1270-1272
- function_item default @1274-1276
- function_item default @1285-1287
- struct_item D3DDDI_RESOURCEFLAGS_0_0 @1291-1293
- struct_item D3DDDI_RESOURCEFLAGS2 @1296-1298
- function_item default @1300-1302
- function_item default @1311-1313
- struct_item D3DDDI_RESOURCEFLAGS2_0_0 @1317-1319
- struct_item D3DDDI_SEGMENTPREFERENCE @1331-1333
- function_item default @1335-1337
- function_item default @1346-1348
- struct_item D3DDDI_SEGMENTPREFERENCE_0_0 @1352-1354
- struct_item D3DDDI_SURFACEINFO @1358-1365
- function_item default @1367-1369
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO @1373-1376
- function_item default @1378-1380
- function_item default @1390-1392
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO_0_2 @1396-1398
- function_item default @1400-1402
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO_0_1 @1406-1409
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO_0_0 @1412-1414
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2 @1417-1422
- function_item default @1424-1426
- function_item default @1440-1442
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_3 @1446-1448
- function_item default @1450-1452
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_2 @1456-1458
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_4 @1461-1467
- function_item default @1469-1471
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_5 @1475-1483
- function_item default @1485-1487
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_6 @1491-1493
- function_item default @1495-1497
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_1 @1501-1504
- struct_item D3DDDI_SYNCHRONIZATIONOBJECTINFO2_0_0 @1507-1509
- struct_item D3DDDI_SYNCHRONIZATIONOBJECT_FLAGS @1512-1514
- function_item default @1516-1518
- function_item default @1527-1529
- struct_item D3DDDI_SYNCHRONIZATIONOBJECT_FLAGS_0_0 @1533-1535
- struct_item D3DDDI_TRIMRESIDENCYSET_FLAGS @1543-1545
- function_item default @1547-1549
- function_item default @1558-1560
- struct_item D3DDDI_TRIMRESIDENCYSET_FLAGS_0_0 @1564-1566
- struct_item D3DDDI_UPDATEALLOCPROPERTY @1569-1577
- function_item default @1579-1581
- function_item default @1590-1592
- struct_item D3DDDI_UPDATEALLOCPROPERTY_0_0 @1596-1598
- struct_item D3DDDI_UPDATEALLOCPROPERTY_FLAGS @1601-1603
- function_item default @1605-1607
- function_item default @1616-1618
- struct_item D3DDDI_UPDATEALLOCPROPERTY_FLAGS_0_0 @1622-1624
- struct_item D3DDDI_UPDATEGPUVIRTUALADDRESS_OPERATION @1630-1633
- function_item default @1635-1637
- function_item default @1648-1650
- struct_item D3DDDI_UPDATEGPUVIRTUALADDRESS_OPERATION_0_3 @1654-1658
- struct_item D3DDDI_UPDATEGPUVIRTUALADDRESS_OPERATION_0_1 @1661-1669
- function_item default @1671-1673
- struct_item D3DDDI_UPDATEGPUVIRTUALADDRESS_OPERATION_0_0 @1677-1683
- struct_item D3DDDI_UPDATEGPUVIRTUALADDRESS_OPERATION_0_2 @1686-1690
- function_item default @1692-1694
- struct_item D3DDDI_WAITFORSYNCHRONIZATIONOBJECTFROMCPU_FLAGS @1706-1708
- function_item default @1710-1712
- function_item default @1721-1723
- struct_item D3DDDI_WAITFORSYNCHRONIZATIONOBJECTFROMCPU_FLAGS_0_0 @1727-1729
- struct_item D3DGPU_PHYSICAL_ADDRESS @1836-1840
- struct_item D3DHAL_CLIPPEDTRIANGLEFAN @1863-1867
- struct_item D3DHAL_CONTEXTDESTROYALLDATA @1871-1874
- struct_item D3DHAL_CONTEXTDESTROYDATA @1877-1880
- struct_item D3DHAL_D3DDX6EXTENDEDCAPS @1884-1907
- struct_item D3DHAL_D3DEXTENDEDCAPS @1910-1942
- struct_item D3DHAL_DP2ADDDIRTYRECT @1945-1948
- struct_item D3DHAL_DP2BLT @1951-1959
- struct_item D3DHAL_DP2CLEAR @1962-1968
- function_item default @1970-1972
- struct_item D3DHAL_DP2COLORFILL @1976-1980
- struct_item D3DHAL_DP2COMMAND @1983-1987
- function_item default @1989-1991
- function_item default @2000-2002
- struct_item D3DHAL_DP2CREATELIGHT @2006-2008
- struct_item D3DHAL_DP2CREATEPIXELSHADER @2011-2014
- struct_item D3DHAL_DP2CREATEVERTEXSHADER @2017-2021
- struct_item D3DHAL_DP2CREATEVERTEXSHADERDECL @2024-2027
- struct_item D3DHAL_DP2CREATEVERTEXSHADERFUNC @2030-2033
- struct_item D3DHAL_DP2DELETEQUERY @2036-2038
- struct_item D3DHAL_DP2DRAWRECTPATCH @2041-2044
- struct_item D3DHAL_DP2DRAWTRIPATCH @2047-2050
- struct_item D3DHAL_DP2EXT @2053-2056
- struct_item D3DHAL_DP2INDEXEDLINELIST @2059-2062
- struct_item D3DHAL_DP2INDEXEDLINESTRIP @2065-2067
- function_item default @2069-2071
- struct_item D3DHAL_DP2INDEXEDTRIANGLEFAN @2075-2077
- function_item default @2079-2081
- struct_item D3DHAL_DP2INDEXEDTRIANGLELIST @2085-2090
- struct_item D3DHAL_DP2INDEXEDTRIANGLELIST2 @2093-2097
- struct_item D3DHAL_DP2INDEXEDTRIANGLESTRIP @2100-2102
- function_item default @2104-2106
- struct_item D3DHAL_DP2ISSUEQUERY @2110-2113
- struct_item D3DHAL_DP2LINELIST @2116-2118
- struct_item D3DHAL_DP2LINESTRIP @2121-2123
- struct_item D3DHAL_DP2PIXELSHADER @2127-2129
- struct_item D3DHAL_DP2POINTS @2132-2135
- struct_item D3DHAL_DP2RESPONSE @2138-2143
- struct_item D3DHAL_DP2RESPONSEQUERY @2146-2149
- struct_item D3DHAL_DP2SETCLIPPLANE @2152-2155
- function_item default @2157-2159
- struct_item D3DHAL_DP2SETCONVOLUTIONKERNELMONO @2163-2167
- struct_item D3DHAL_DP2SETDEPTHSTENCIL @2170-2172
- struct_item D3DHAL_DP2SETINDICES @2175-2178
- struct_item D3DHAL_DP2SETLIGHT @2181-2184
- struct_item D3DHAL_DP2SETPALETTE @2187-2191
- struct_item D3DHAL_DP2SETPIXELSHADERCONST @2194-2197
- struct_item D3DHAL_DP2SETPRIORITY @2200-2203
- struct_item D3DHAL_DP2SETRENDERTARGET @2206-2209
- struct_item D3DHAL_DP2SETRENDERTARGET2 @2212-2215
- struct_item D3DHAL_DP2SETSTREAMSOURCE @2218-2222
- struct_item D3DHAL_DP2SETSTREAMSOURCE2 @2225-2230
- struct_item D3DHAL_DP2SETSTREAMSOURCEFREQ @2233-2236
- struct_item D3DHAL_DP2SETSTREAMSOURCEUM @2239-2242
- struct_item D3DHAL_DP2SETTEXLOD @2245-2248
- struct_item D3DHAL_DP2SETVERTEXSHADERCONST @2251-2254
- struct_item D3DHAL_DP2STARTVERTEX @2257-2259
- struct_item D3DHAL_DP2SURFACEBLT @2262-2270
- struct_item D3DHAL_DP2TEXBLT @2273-2279
- struct_item D3DHAL_DP2TEXTURESTAGESTATE @2282-2286
- struct_item D3DHAL_DP2TRIANGLEFAN @2289-2291
- struct_item D3DHAL_DP2TRIANGLEFAN_IMM @2294-2296
- struct_item D3DHAL_DP2TRIANGLELIST @2299-2301
- struct_item D3DHAL_DP2TRIANGLESTRIP @2304-2306
- struct_item D3DHAL_DP2UPDATEPALETTE @2309-2313
- struct_item D3DHAL_DP2VERTEXSHADER @2316-2318
- struct_item D3DHAL_DP2VIEWPORTINFO @2321-2326
- struct_item D3DHAL_DP2WINFO @2329-2332
- struct_item D3DHAL_DP2ZRANGE @2335-2338
- struct_item D3DHAL_DRAWPRIMCOUNTS @2341-2346
- struct_item D3DHAL_DRAWPRIMITIVESDATA @2349-2355
- function_item default @2357-2359
- struct_item D3DHAL_SCENECAPTUREDATA @2378-2382
- struct_item D3DHAL_TEXTUREDESTROYDATA @2396-2400
- struct_item D3DHAL_TEXTUREGETSURFDATA @2403-2408
- struct_item D3DHAL_TEXTURESWAPDATA @2412-2417
- struct_item D3DHAL_VALIDATETEXTURESTAGESTATEDATA @2423-2429
- struct_item D3DKMDT_2DREGION @2433-2436
- struct_item D3DKMDT_3x4_COLORSPACE_TRANSFORM @2439-2443
- function_item default @2445-2447
- struct_item D3DKMDT_COLORSPACE_TRANSFORM_MATRIX_V2 @2463-2470
- function_item default @2472-2474
- struct_item D3DKMDT_COLOR_COEFF_DYNAMIC_RANGES @2483-2488
- struct_item D3DKMDT_DISPLAYMODE_FLAGS @2498-2501
- struct_item D3DKMDT_FREQUENCY_RANGE @2511-2516
- struct_item D3DKMDT_GAMMA_RAMP @2519-2523
- function_item default @2525-2527
- function_item default @2539-2541
- struct_item D3DKMDT_GDISURFACEDATA @2545-2552
- function_item default @2554-2556
- struct_item D3DKMDT_GDISURFACEFLAGS @2560-2562
- function_item default @2564-2566
- function_item default @2575-2577
- struct_item D3DKMDT_GDISURFACEFLAGS_0_0 @2581-2583
- struct_item D3DKMDT_GRAPHICS_RENDERING_FORMAT @2603-2610
- struct_item D3DKMDT_MONITOR_DESCRIPTOR @2644-2650
- function_item default @2652-2654
- struct_item D3DKMDT_MONITOR_FREQUENCY_RANGE @2659-2664
- function_item default @2666-2668
- function_item default @2677-2679
- struct_item D3DKMDT_MONITOR_SOURCE_MODE @2686-2693
- function_item default @2695-2697
- struct_item D3DKMDT_PALETTEDATA @2728-2733
- struct_item D3DKMDT_PREEMPTION_CAPS @2737-2740
- struct_item D3DKMDT_SHADOWSURFACEDATA @2752-2757
- struct_item D3DKMDT_SHAREDPRIMARYSURFACEDATA @2760-2766
- struct_item D3DKMDT_STAGINGSURFACEDATA @2769-2773
- struct_item D3DKMDT_VIDEO_PRESENT_SOURCE @2785-2788
- struct_item D3DKMDT_VIDEO_PRESENT_TARGET @2791-2797
- struct_item D3DKMDT_VIDEO_SIGNAL_INFO @2800-2808
- function_item default @2810-2812
- function_item default @2821-2823
- struct_item D3DKMDT_VIDEO_SIGNAL_INFO_0_0 @2827-2829
- struct_item D3DKMDT_VIDPN_HW_CAPABILITY @2833-2835
- struct_item D3DKMDT_VIDPN_PRESENT_PATH @2838-2850
- function_item default @2852-2854
- struct_item D3DKMDT_VIDPN_PRESENT_PATH_COPYPROTECTION @2859-2864
- function_item default @2866-2868
- struct_item D3DKMDT_VIDPN_PRESENT_PATH_COPYPROTECTION_SUPPORT @2872-2874
- struct_item D3DKMDT_VIDPN_PRESENT_PATH_ROTATION_SUPPORT @2880-2882
- struct_item D3DKMDT_VIDPN_PRESENT_PATH_SCALING_SUPPORT @2886-2888
- struct_item D3DKMDT_VIDPN_PRESENT_PATH_TRANSFORMATION @2891-2896
- struct_item D3DKMDT_VIDPN_SOURCE_MODE @2899-2903
- function_item default @2905-2907
- function_item default @2916-2918
- struct_item D3DKMDT_VIDPN_TARGET_MODE @2923-2928
- function_item default @2930-2932
- function_item default @2941-2943
- struct_item D3DKMDT_VIDPN_TARGET_MODE_0_0 @2947-2949
- struct_item D3DKMDT_VIRTUALGPUSURFACEDATA @2952-2957
- function_item default @3069-3071
- struct_item D3DKMDT_WIRE_FORMAT_AND_PREFERENCE_0 @3075-3077
- struct_item D3DKMT_ACQUIREKEYEDMUTEX @3080-3085
- function_item default @3087-3089
- struct_item D3DKMT_ACQUIREKEYEDMUTEX2 @3093-3100
- function_item default @3102-3104
- struct_item D3DKMT_ACTIVATE_SPECIFIC_DIAG_ESCAPE @3108-3111
- struct_item D3DKMT_ADAPTERADDRESS @3117-3121
- struct_item D3DKMT_ADAPTERINFO @3124-3129
- struct_item D3DKMT_ADAPTERREGISTRYINFO @3132-3137
- function_item default @3139-3141
- struct_item D3DKMT_ADAPTERTYPE @3145-3147
- function_item default @3149-3151
- function_item default @3160-3162
- struct_item D3DKMT_ADAPTERTYPE_0_0 @3166-3168
- struct_item D3DKMT_ADAPTER_PERFDATA @3171-3182
- struct_item D3DKMT_ADAPTER_PERFDATACAPS @3185-3192
- struct_item D3DKMT_ADAPTER_VERIFIER_OPTION @3195-3199
- function_item default @3201-3203
- function_item default @3212-3214
- function_item default @3226-3228
- struct_item D3DKMT_ADAPTER_VERIFIER_VIDMM_FLAGS_0 @3232-3234
- struct_item D3DKMT_ADAPTER_VERIFIER_VIDMM_TRIM_INTERVAL @3237-3241
- struct_item D3DKMT_ADJUSTFULLSCREENGAMMA @3244-3249
- struct_item D3DKMT_AUXILIARYPRESENTINFO @3256-3259
- struct_item D3DKMT_BDDFALLBACK_CTL @3269-3271
- struct_item D3DKMT_BLOCKLIST_INFO @3274-3277
- function_item default @3279-3281
- struct_item D3DKMT_BLTMODEL_PRESENTHISTORYTOKEN @3285-3290
- struct_item D3DKMT_BRIGHTNESS_INFO @3293-3297
- function_item default @3299-3301
- function_item default @3318-3320
- struct_item D3DKMT_BRIGHTNESS_POSSIBLE_LEVELS @3336-3339
- function_item default @3341-3343
- struct_item D3DKMT_BUDGETCHANGENOTIFICATION @3347-3350
- function_item default @3352-3354
- struct_item D3DKMT_CANCEL_PRESENTS @3358-3366
- function_item default @3368-3370
- struct_item D3DKMT_CANCEL_PRESENTS_FLAGS @3374-3376
- function_item default @3378-3380
- function_item default @3389-3391
- struct_item D3DKMT_CANCEL_PRESENTS_FLAGS_0_0 @3395-3397
- struct_item D3DKMT_CHANGESURFACEPOINTER @3404-3411
- function_item default @3414-3416
- struct_item D3DKMT_CHANGEVIDEOMEMORYRESERVATION @3420-3426
- function_item default @3428-3430
- struct_item D3DKMT_CHECKMONITORPOWERSTATE @3434-3437
- struct_item D3DKMT_CHECKMULTIPLANEOVERLAYSUPPORT @3440-3446
- function_item default @3448-3450
- struct_item D3DKMT_CHECKMULTIPLANEOVERLAYSUPPORT2 @3454-3461
- function_item default @3463-3465
- struct_item D3DKMT_CHECKMULTIPLANEOVERLAYSUPPORT3 @3469-3478
- function_item default @3480-3482
- struct_item D3DKMT_CHECKOCCLUSION @3486-3488
- function_item default @3490-3492
- struct_item D3DKMT_CHECKSHAREDRESOURCEACCESS @3496-3499
- struct_item D3DKMT_CHECKVIDPNEXCLUSIVEOWNERSHIP @3502-3505
- struct_item D3DKMT_CHECK_MULTIPLANE_OVERLAY_PLANE @3508-3513
- struct_item D3DKMT_CHECK_MULTIPLANE_OVERLAY_PLANE2 @3516-3522
- struct_item D3DKMT_CHECK_MULTIPLANE_OVERLAY_PLANE3 @3525-3531
- function_item default @3533-3535
- struct_item D3DKMT_CHECK_MULTIPLANE_OVERLAY_SUPPORT_RETURN_INFO @3539-3541
- function_item default @3543-3545
- function_item default @3554-3556
- struct_item D3DKMT_CHECK_MULTIPLANE_OVERLAY_SUPPORT_RETURN_INFO_0_0 @3560-3562
- struct_item D3DKMT_CLOSEADAPTER @3588-3590
- struct_item D3DKMT_COMPOSITION_PRESENTHISTORYTOKEN @3593-3595
- struct_item D3DKMT_CONFIGURESHAREDRESOURCE @3598-3604
- function_item default @3606-3608
- struct_item D3DKMT_CONNECT_DOORBELL @3612-3615
- function_item default @3617-3619
- struct_item D3DKMT_CONNECT_DOORBELL_FLAGS @3623-3625
- function_item default @3627-3629
- function_item default @3638-3640
- struct_item D3DKMT_CONNECT_DOORBELL_FLAGS_0_0 @3644-3646
- struct_item D3DKMT_CPDRIVERNAME @3649-3651
- function_item default @3653-3655
- struct_item D3DKMT_CREATEALLOCATION @3659-3671
- function_item default @3673-3675
- function_item default @3684-3686
- function_item default @3695-3697
- struct_item D3DKMT_CREATEALLOCATIONFLAGS @3701-3703
- struct_item D3DKMT_CREATECONTEXT @3706-3722
- function_item default @3724-3726
- struct_item D3DKMT_CREATECONTEXTVIRTUAL @3730-3739
- function_item default @3741-3743
- struct_item D3DKMT_CREATEDCFROMMEMORY @3748-3758
- function_item default @3761-3763
- struct_item D3DKMT_CREATEDEVICE @3767-3777
- function_item default @3779-3781
- function_item default @3790-3792
- struct_item D3DKMT_CREATEDEVICEFLAGS @3796-3798
- struct_item D3DKMT_CREATEHWCONTEXT @3801-3809
- function_item default @3811-3813
- struct_item D3DKMT_CREATEHWQUEUE @3817-3826
- function_item default @3828-3830
- struct_item D3DKMT_CREATEKEYEDMUTEX @3834-3838
- struct_item D3DKMT_CREATEKEYEDMUTEX2 @3841-3848
- function_item default @3850-3852
- struct_item D3DKMT_CREATEKEYEDMUTEX2_FLAGS @3856-3858
- function_item default @3860-3862
- function_item default @3871-3873
- struct_item D3DKMT_CREATEKEYEDMUTEX2_FLAGS_0_0 @3877-3879
- struct_item D3DKMT_CREATENATIVEFENCE @3882-3885
- function_item default @3887-3889
- struct_item D3DKMT_CREATEOVERLAY @3893-3898
- struct_item D3DKMT_CREATEPAGINGQUEUE @3901-3908
- function_item default @3910-3912
- struct_item D3DKMT_CREATEPROTECTEDSESSION @3916-3924
- function_item default @3926-3928
- struct_item D3DKMT_CREATESTANDARDALLOCATION @3932-3936
- function_item default @3938-3940
- function_item default @3948-3950
- struct_item D3DKMT_CREATESTANDARDALLOCATIONFLAGS @3954-3956
- function_item default @3958-3960
- function_item default @3969-3971
- struct_item D3DKMT_CREATESTANDARDALLOCATIONFLAGS_0_0 @3975-3977
- struct_item D3DKMT_CREATESYNCFILE @3980-3985
- struct_item D3DKMT_CREATESYNCHRONIZATIONOBJECT @3988-3992
- function_item default @3994-3996
- struct_item D3DKMT_CREATESYNCHRONIZATIONOBJECT2 @4000-4004
- function_item default @4006-4008
- struct_item D3DKMT_CREATE_DOORBELL @4012-4022
- function_item default @4024-4026
- struct_item D3DKMT_CREATE_DOORBELL_FLAGS @4030-4032
- function_item default @4034-4036
- function_item default @4045-4047
- struct_item D3DKMT_CREATE_DOORBELL_FLAGS_0_0 @4051-4053
- struct_item D3DKMT_CREATE_OUTPUTDUPL @4056-4063
- function_item default @4065-4067
- struct_item D3DKMT_CROSSADAPTERRESOURCE_SUPPORT @4071-4073
- struct_item D3DKMT_CURRENTDISPLAYMODE @4083-4086
- struct_item D3DKMT_DEBUG_SNAPSHOT_ESCAPE @4091-4094
- function_item default @4096-4098
- struct_item D3DKMT_DESTROYALLOCATION @4108-4113
- function_item default @4115-4117
- struct_item D3DKMT_DESTROYALLOCATION2 @4121-4127
- function_item default @4129-4131
- struct_item D3DKMT_DESTROYCONTEXT @4135-4137
- struct_item D3DKMT_DESTROYDCFROMMEMORY @4141-4144
- function_item default @4147-4149
- struct_item D3DKMT_DESTROYDEVICE @4153-4155
- struct_item D3DKMT_DESTROYHWCONTEXT @4158-4160
- struct_item D3DKMT_DESTROYHWQUEUE @4163-4165
- struct_item D3DKMT_DESTROYKEYEDMUTEX @4168-4170
- struct_item D3DKMT_DESTROYOVERLAY @4173-4176
- struct_item D3DKMT_DESTROYPROTECTEDSESSION @4179-4181
- struct_item D3DKMT_DESTROYSYNCHRONIZATIONOBJECT @4184-4186
- struct_item D3DKMT_DESTROY_DOORBELL @4189-4191
- struct_item D3DKMT_DESTROY_OUTPUTDUPL @4194-4198
- struct_item D3DKMT_DEVICEPAGEFAULT_STATE @4212-4219
- function_item default @4221-4223
- struct_item D3DKMT_DEVICEPRESENT_QUEUE_STATE @4227-4230
- struct_item D3DKMT_DEVICEPRESENT_STATE @4233-4236
- struct_item D3DKMT_DEVICEPRESENT_STATE_DWM @4239-4242
- struct_item D3DKMT_DEVICERESET_STATE @4245-4247
- function_item default @4249-4251
- function_item default @4260-4262
- struct_item D3DKMT_DEVICERESET_STATE_0_0 @4266-4268
- struct_item D3DKMT_DEVICE_ESCAPE @4281-4284
- function_item default @4286-4288
- function_item default @4296-4298
- struct_item D3DKMT_DEVICE_ESCAPE_0_0 @4302-4305
- struct_item D3DKMT_DEVICE_IDS @4308-4315
- struct_item D3DKMT_DIRECTFLIP_SUPPORT @4318-4320
- struct_item D3DKMT_DIRTYREGIONS @4323-4326
- function_item default @4328-4330
- struct_item D3DKMT_DISPLAYMODE @4334-4344
- struct_item D3DKMT_DISPLAYMODELIST @4347-4351
- function_item default @4353-4355
- struct_item D3DKMT_DISPLAY_CAPS @4359-4361
- function_item default @4363-4365
- function_item default @4374-4376
- struct_item D3DKMT_DISPLAY_CAPS_0_0 @4380-4382
- struct_item D3DKMT_DISPLAY_UMD_FILENAMEINFO @4385-4388
- function_item default @4390-4392
- struct_item D3DKMT_DLIST_DRIVER_NAME @4396-4398
- function_item default @4400-4402
- struct_item D3DKMT_DMM_ESCAPE @4422-4427
- function_item default @4429-4431
- struct_item D3DKMT_DOD_SET_DIRTYRECT_MODE @4435-4437
- struct_item D3DKMT_DRIVERCAPS_EXT @4440-4442
- function_item default @4444-4446
- function_item default @4455-4457
- struct_item D3DKMT_DRIVERCAPS_EXT_0_0 @4461-4463
- struct_item D3DKMT_DRIVER_DESCRIPTION @4467-4469
- function_item default @4471-4473
- struct_item D3DKMT_ENUMADAPTERS @4480-4483
- function_item default @4485-4487
- struct_item D3DKMT_ENUMADAPTERS2 @4491-4494
- function_item default @4496-4498
- struct_item D3DKMT_ENUMADAPTERS3 @4502-4506
- function_item default @4508-4510
- function_item default @4519-4521
- struct_item D3DKMT_ENUMADAPTERS_FILTER_0 @4525-4527
- struct_item D3DKMT_ESCAPE @4530-4538
- function_item default @4540-4542
- struct_item D3DKMT_ESCAPE_VIRTUAL_REFRESH_RATE @4585-4592
- function_item default @4594-4596
- struct_item D3DKMT_EVICT @4618-4624
- function_item default @4626-4628
- struct_item D3DKMT_EVICTION_CRITERIA @4632-4636
- function_item default @4638-4640
- struct_item D3DKMT_EVICTION_CRITERIA_0 @4644-4646
- function_item default @4648-4650
- function_item default @4659-4661
- struct_item D3DKMT_EVICTION_CRITERIA_0_0_0 @4665-4667
- struct_item D3DKMT_FENCE_PRESENTHISTORYTOKEN @4670-4672
- struct_item D3DKMT_FLIPINFOFLAGS @4675-4677
- struct_item D3DKMT_FLIPMANAGER_AUXILIARYPRESENTINFO @4680-4691
- struct_item D3DKMT_FLIPMANAGER_PRESENTHISTORYTOKEN @4694-4698
- function_item default @4700-4702
- function_item default @4711-4713
- struct_item D3DKMT_FLIPMANAGER_PRESENTHISTORYTOKEN_0_0 @4717-4719
- struct_item D3DKMT_FLIPMODEL_PRESENTHISTORYTOKEN @4725-4756
- function_item default @4758-4760
- function_item default @4769-4771
- struct_item D3DKMT_FLIPMODEL_PRESENTHISTORYTOKEN_0_0 @4775-4779
- function_item default @4781-4783
- function_item default @4792-4794
- struct_item D3DKMT_FLIPMODEL_PRESENTHISTORYTOKENFLAGS @4798-4800
- function_item default @4802-4804
- function_item default @4813-4815
- struct_item D3DKMT_FLIPMODEL_PRESENTHISTORYTOKENFLAGS_0_0 @4819-4821
- struct_item D3DKMT_FLIPOVERLAY @4824-4830
- function_item default @4832-4834
- struct_item D3DKMT_FLIPQUEUEINFO @4838-4842
- struct_item D3DKMT_FLUSHHEAPTRANSITIONS @4845-4847
- struct_item D3DKMT_FREEGPUVIRTUALADDRESS @4850-4854
- struct_item D3DKMT_GDIMODEL_PRESENTHISTORYTOKEN @4857-4863
- struct_item D3DKMT_GDIMODEL_SYSMEM_PRESENTHISTORYTOKEN @4866-4870
- struct_item D3DKMT_GETALLOCATIONPRIORITY @4874-4880
- function_item default @4882-4884
- struct_item D3DKMT_GETCONTEXTINPROCESSSCHEDULINGPRIORITY @4888-4891
- struct_item D3DKMT_GETCONTEXTSCHEDULINGPRIORITY @4894-4897
- struct_item D3DKMT_GETDEVICESTATE @4900-4904
- function_item default @4906-4908
- function_item default @4921-4923
- struct_item D3DKMT_GETDISPLAYMODELIST @4927-4932
- function_item default @4934-4936
- struct_item D3DKMT_GETMULTISAMPLEMETHODLIST @4940-4948
- function_item default @4950-4952
- struct_item D3DKMT_GETOVERLAYSTATE @4956-4960
- struct_item D3DKMT_GETPRESENTHISTORY @4963-4969
- function_item default @4971-4973
- struct_item D3DKMT_GETPROCESSDEVICEREMOVALSUPPORT @4978-4982
- function_item default @4984-4986
- struct_item D3DKMT_GETRUNTIMEDATA @4990-4995
- function_item default @4997-4999
- struct_item D3DKMT_GETSCANLINE @5003-5008
- struct_item D3DKMT_GETSHAREDPRIMARYHANDLE @5011-5015
- struct_item D3DKMT_GETSHAREDRESOURCEADAPTERLUID @5018-5022
- function_item default @5024-5026
- struct_item D3DKMT_GETVERTICALBLANKEVENT @5030-5035
- function_item default @5037-5039
- struct_item D3DKMT_GET_DEVICE_VIDPN_OWNERSHIP_INFO @5043-5046
- struct_item D3DKMT_GET_GPUMMU_CAPS @5049-5052
- struct_item D3DKMT_GET_MULTIPLANE_OVERLAY_CAPS @5055-5064
- function_item default @5066-5068
- struct_item D3DKMT_GET_POST_COMPOSITION_CAPS @5072-5077
- struct_item D3DKMT_GET_PTE @5080-5088
- function_item default @5090-5092
- struct_item D3DKMT_GET_SEGMENT_CAPS @5098-5102
- function_item default @5104-5106
- struct_item D3DKMT_GPUMMU_CAPS @5110-5113
- function_item default @5115-5117
- function_item default @5126-5128
- struct_item D3DKMT_GPUMMU_CAPS_0_0 @5132-5134
- struct_item D3DKMT_GPUVERSION @5137-5141
- function_item default @5143-5145
- struct_item D3DKMT_HISTORY_BUFFER_STATUS @5160-5163
- struct_item D3DKMT_HWDRM_SUPPORT @5166-5168
- struct_item D3DKMT_HYBRID_DLIST_DLL_SUPPORT @5171-5173
- struct_item D3DKMT_HYBRID_LIST @5176-5181
- struct_item D3DKMT_INDEPENDENTFLIP_SECONDARY_SUPPORT @5184-5186
- struct_item D3DKMT_INDEPENDENTFLIP_SUPPORT @5189-5191
- struct_item D3DKMT_INVALIDATEACTIVEVIDPN @5194-5198
- function_item default @5200-5202
- struct_item D3DKMT_INVALIDATECACHE @5206-5211
- struct_item D3DKMT_ISBADDRIVERFORHWPROTECTIONDISABLED @5214-5216
- struct_item D3DKMT_KMD_DRIVER_VERSION @5219-5221
- struct_item D3DKMT_LOCK @5224-5233
- function_item default @5235-5237
- struct_item D3DKMT_LOCK2 @5241-5246
- function_item default @5248-5250
- struct_item D3DKMT_MARKDEVICEASERROR @5254-5257
- struct_item D3DKMT_MIRACASTCOMPANIONDRIVERNAME @5272-5274
- function_item default @5276-5278
- struct_item D3DKMT_MIRACAST_CHUNK_DATA @5282-5286
- function_item default @5288-5290
- struct_item D3DKMT_MIRACAST_DISPLAY_DEVICE_CAPS @5309-5313
- struct_item D3DKMT_MIRACAST_DISPLAY_DEVICE_STATUS @5317-5319
- struct_item D3DKMT_MIRACAST_DISPLAY_STOP_SESSIONS @5322-5326
- struct_item D3DKMT_MOVE_RECT @5333-5336
- struct_item D3DKMT_MPO3DDI_SUPPORT @5339-5341
- struct_item D3DKMT_MPOKERNELCAPS_SUPPORT @5344-5346
- struct_item D3DKMT_MULTIPLANEOVERLAY_DECODE_SUPPORT @5350-5352
- struct_item D3DKMT_MULTIPLANEOVERLAY_HUD_SUPPORT @5355-5360
- struct_item D3DKMT_MULTIPLANEOVERLAY_SECONDARY_SUPPORT @5363-5365
- struct_item D3DKMT_MULTIPLANEOVERLAY_STRETCH_SUPPORT @5368-5372
- struct_item D3DKMT_MULTIPLANEOVERLAY_SUPPORT @5375-5377
- struct_item D3DKMT_MULTIPLANE_OVERLAY @5380-5385
- struct_item D3DKMT_MULTIPLANE_OVERLAY2 @5388-5393
- struct_item D3DKMT_MULTIPLANE_OVERLAY3 @5396-5410
- function_item default @5412-5414
- struct_item D3DKMT_MULTIPLANE_OVERLAY_ATTRIBUTES @5418-5434
- function_item default @5436-5438
- struct_item D3DKMT_MULTIPLANE_OVERLAY_ATTRIBUTES2 @5442-5459
- function_item default @5461-5463
- struct_item D3DKMT_MULTIPLANE_OVERLAY_ATTRIBUTES3 @5467-5479
- function_item default @5481-5483
- struct_item D3DKMT_MULTIPLANE_OVERLAY_CAPS @5490-5492
- function_item default @5494-5496
- function_item default @5505-5507
- struct_item D3DKMT_MULTIPLANE_OVERLAY_CAPS_0_0 @5511-5513
- struct_item D3DKMT_MULTIPLANE_OVERLAY_POST_COMPOSITION @5520-5525
- function_item default @5527-5529
- struct_item D3DKMT_MULTIPLANE_OVERLAY_POST_COMPOSITION_FLAGS @5533-5535
- function_item default @5537-5539
- function_item default @5548-5550
- struct_item D3DKMT_MULTIPLANE_OVERLAY_POST_COMPOSITION_FLAGS_0_0 @5554-5556
- struct_item D3DKMT_MULTIPLANE_OVERLAY_POST_COMPOSITION_WITH_SOURCE @5559-5562
- function_item default @5564-5566
- struct_item D3DKMT_MULTISAMPLEMETHOD @5580-5584
- struct_item D3DKMT_NODEMETADATA @5589-5592
- function_item default @5594-5596
- struct_item D3DKMT_NODE_PERFDATA @5600-5610
- struct_item D3DKMT_NOTIFY_WORK_SUBMISSION @5613-5616
- function_item default @5618-5620
- struct_item D3DKMT_NOTIFY_WORK_SUBMISSION_FLAGS @5624-5626
- function_item default @5628-5630
- function_item default @5639-5641
- struct_item D3DKMT_NOTIFY_WORK_SUBMISSION_FLAGS_0_0 @5645-5647
- struct_item D3DKMT_OFFERALLOCATIONS @5650-5657
- function_item default @5659-5661
- struct_item D3DKMT_OFFER_FLAGS @5665-5667
- function_item default @5669-5671
- function_item default @5680-5682
- struct_item D3DKMT_OFFER_FLAGS_0_0 @5686-5688
- struct_item D3DKMT_OPENADAPTERFROMDEVICENAME @5696-5700
- function_item default @5702-5704
- struct_item D3DKMT_OPENADAPTERFROMGDIDISPLAYNAME @5708-5713
- function_item default @5715-5717
- struct_item D3DKMT_OPENADAPTERFROMHDC @5722-5727
- function_item default @5730-5732
- struct_item D3DKMT_OPENADAPTERFROMLUID @5736-5739
- struct_item D3DKMT_OPENGLINFO @5742-5746
- function_item default @5748-5750
- struct_item D3DKMT_OPENKEYEDMUTEX @5754-5757
- struct_item D3DKMT_OPENKEYEDMUTEX2 @5760-5765
- function_item default @5767-5769
- struct_item D3DKMT_OPENKEYEDMUTEXFROMNTHANDLE @5773-5778
- function_item default @5780-5782
- struct_item D3DKMT_OPENNATIVEFENCEFROMNTHANDLE @5786-5793
- function_item default @5795-5797
- struct_item D3DKMT_OPENNTHANDLEFROMNAME @5802-5806
- function_item default @5809-5811
- struct_item D3DKMT_OPENPROTECTEDSESSIONFROMNTHANDLE @5815-5818
- function_item default @5820-5822
- struct_item D3DKMT_OPENRESOURCE @5826-5838
- function_item default @5840-5842
- function_item default @5851-5853
- struct_item D3DKMT_OPENRESOURCEFROMNTHANDLE @5857-5873
- function_item default @5875-5877
- struct_item D3DKMT_OPENSYNCHRONIZATIONOBJECT @5881-5885
- function_item default @5887-5889
- struct_item D3DKMT_OPENSYNCOBJECTFROMNTHANDLE @5893-5896
- function_item default @5898-5900
- struct_item D3DKMT_OPENSYNCOBJECTFROMNTHANDLE2 @5904-5910
- function_item default @5912-5914
- function_item default @5923-5925
- struct_item D3DKMT_OPENSYNCOBJECTFROMNTHANDLE2_0_0 @5929-5933
- function_item default @5935-5937
- struct_item D3DKMT_OPENSYNCOBJECTNTHANDLEFROMNAME @5942-5946
- function_item default @5949-5951
- struct_item D3DKMT_OUTDUPL_POINTER_SHAPE_INFO @5955-5961
- struct_item D3DKMT_OUTPUTDUPLCONTEXTSCOUNT @5968-5971
- struct_item D3DKMT_OUTPUTDUPLCREATIONFLAGS @5974-5976
- function_item default @5978-5980
- function_item default @5989-5991
- struct_item D3DKMT_OUTPUTDUPLCREATIONFLAGS_0_0 @5995-5997
- struct_item D3DKMT_OUTPUTDUPLPRESENT @6000-6009
- function_item default @6011-6013
- struct_item D3DKMT_OUTPUTDUPLPRESENTFLAGS @6017-6019
- function_item default @6021-6023
- function_item default @6032-6034
- struct_item D3DKMT_OUTPUTDUPLPRESENTFLAGS_0_0 @6038-6040
- struct_item D3DKMT_OUTPUTDUPLPRESENTTOHWQUEUE @6043-6051
- function_item default @6053-6055
- struct_item D3DKMT_OUTPUTDUPL_FRAMEINFO @6059-6068
- struct_item D3DKMT_OUTPUTDUPL_GET_FRAMEINFO @6071-6075
- struct_item D3DKMT_OUTPUTDUPL_GET_POINTER_SHAPE_DATA @6078-6085
- function_item default @6087-6089
- struct_item D3DKMT_OUTPUTDUPL_KEYEDMUTEX @6093-6095
- function_item default @6097-6099
- struct_item D3DKMT_OUTPUTDUPL_METADATA @6103-6110
- function_item default @6112-6114
- struct_item D3DKMT_OUTPUTDUPL_POINTER_POSITION @6121-6124
- struct_item D3DKMT_OUTPUTDUPL_RELEASE_FRAME @6127-6131
- struct_item D3DKMT_OUTPUTDUPL_SNAPSHOT @6134-6142
- function_item default @6144-6146
- struct_item D3DKMT_PAGE_TABLE_LEVEL_DESC @6150-6156
- struct_item D3DKMT_PANELFITTER_SUPPORT @6159-6161
- struct_item D3DKMT_PARAVIRTUALIZATION @6164-6166
- struct_item D3DKMT_PHYSICAL_ADAPTER_COUNT @6169-6171
- struct_item D3DKMT_PINDIRECTFLIPRESOURCES @6174-6178
- function_item default @6180-6182
- struct_item D3DKMT_PLANE_SPECIFIC_INPUT_FLAGS @6186-6188
- function_item default @6190-6192
- function_item default @6201-6203
- struct_item D3DKMT_PLANE_SPECIFIC_INPUT_FLAGS_0_0 @6207-6209
- struct_item D3DKMT_PLANE_SPECIFIC_OUTPUT_FLAGS @6212-6214
- function_item default @6216-6218
- function_item default @6227-6229
- struct_item D3DKMT_PLANE_SPECIFIC_OUTPUT_FLAGS_0_0 @6233-6235
- struct_item D3DKMT_POLLDISPLAYCHILDREN @6251-6254
- struct_item D3DKMT_PRESENT @6257-6283
- function_item default @6285-6287
- function_item default @6296-6298
- function_item default @6307-6309
- struct_item D3DKMT_PRESENTFLAGS @6313-6315
- function_item default @6317-6319
- function_item default @6328-6330
- struct_item D3DKMT_PRESENTFLAGS_0_0 @6334-6336
- struct_item D3DKMT_PRESENTHISTORYTOKEN @6339-6344
- function_item default @6346-6348
- function_item default @6364-6366
- struct_item D3DKMT_PRESENT_MULTIPLANE_OVERLAY @6371-6382
- function_item default @6384-6386
- function_item default @6395-6397
- struct_item D3DKMT_PRESENT_MULTIPLANE_OVERLAY2 @6401-6413
- function_item default @6415-6417
- function_item default @6426-6428
- struct_item D3DKMT_PRESENT_MULTIPLANE_OVERLAY3 @6432-6447
- function_item default @6449-6451
- struct_item D3DKMT_PRESENT_MULTIPLANE_OVERLAY_FLAGS @6455-6457
- function_item default @6459-6461
- function_item default @6470-6472
- struct_item D3DKMT_PRESENT_MULTIPLANE_OVERLAY_FLAGS_0_0 @6476-6478
- struct_item D3DKMT_PRESENT_REDIRECTED @6481-6490
- function_item default @6492-6494
- struct_item D3DKMT_PRESENT_REDIRECTED_FLAGS @6498-6500
- function_item default @6502-6504
- function_item default @6513-6515
- struct_item D3DKMT_PRESENT_REDIRECTED_FLAGS_0_0 @6519-6521
- struct_item D3DKMT_PRESENT_RGNS @6524-6529
- function_item default @6531-6533
- struct_item D3DKMT_PRESENT_STATS @6537-6543
- struct_item D3DKMT_PRESENT_STATS_DWM @6546-6553
- struct_item D3DKMT_PRESENT_STATS_DWM2 @6556-6566
- struct_item D3DKMT_PROCESS_VERIFIER_OPTION @6569-6574
- function_item default @6576-6578
- function_item default @6587-6589
- function_item default @6601-6603
- struct_item D3DKMT_PROCESS_VERIFIER_VIDMM_FLAGS_0 @6607-6609
- struct_item D3DKMT_PROCESS_VERIFIER_VIDMM_RESTRICT_BUDGET @6612-6615
- struct_item D3DKMT_QUERYADAPTERINFO @6638-6643
- function_item default @6645-6647
- struct_item D3DKMT_QUERYALLOCATIONRESIDENCY @6651-6657
- function_item default @6659-6661
- struct_item D3DKMT_QUERYCLOCKCALIBRATION @6665-6670
- function_item default @6672-6674
- struct_item D3DKMT_QUERYFSEBLOCK @6678-6683
- function_item default @6685-6687
- function_item default @6696-6698
- struct_item D3DKMT_QUERYFSEBLOCKFLAGS_0 @6702-6704
- struct_item D3DKMT_QUERYPROCESSOFFERINFO @6707-6712
- function_item default @6714-6716
- struct_item D3DKMT_QUERYPROTECTEDSESSIONINFOFROMNTHANDLE @6720-6726
- function_item default @6728-6730
- struct_item D3DKMT_QUERYPROTECTEDSESSIONSTATUS @6734-6737
- struct_item D3DKMT_QUERYREMOTEVIDPNSOURCEFROMGDIDISPLAYNAME @6740-6743
- function_item default @6745-6747
- struct_item D3DKMT_QUERYRESOURCEINFO @6751-6759
- function_item default @6761-6763
- struct_item D3DKMT_QUERYRESOURCEINFOFROMNTHANDLE @6767-6775
- function_item default @6777-6779
- struct_item D3DKMT_QUERYSTATISTICS @6785-6791
- function_item default @6793-6795
- function_item default @6819-6821
- struct_item D3DKMT_QUERYSTATISTICS_ADAPTER_INFORMATION @6827-6846
- function_item default @6848-6850
- struct_item D3DKMT_QUERYSTATISTICS_ADAPTER_INFORMATION_FLAGS @6854-6856
- function_item default @6858-6860
- function_item default @6869-6871
- struct_item D3DKMT_QUERYSTATISTICS_ADAPTER_INFORMATION_FLAGS_0_0 @6875-6877
- struct_item D3DKMT_QUERYSTATISTICS_COMMITMENT_DATA @6882-6885
- function_item default @6887-6889
- struct_item D3DKMT_QUERYSTATISTICS_COUNTER @6893-6896
- struct_item D3DKMT_QUERYSTATISTICS_DMA_BUFFER @6899-6903
- struct_item D3DKMT_QUERYSTATISTICS_DMA_PACKET_TYPE_INFORMATION @6907-6912
- struct_item D3DKMT_QUERYSTATISTICS_MEMORY @6916-6920
- struct_item D3DKMT_QUERYSTATISTICS_MEMORY_USAGE @6923-6929
- struct_item D3DKMT_QUERYSTATISTICS_NODE_INFORMATION @6934-6939
- function_item default @6941-6943
- struct_item D3DKMT_QUERYSTATISTICS_PACKET_INFORMATION @6947-6950
- function_item default @6952-6954
- struct_item D3DKMT_QUERYSTATISTICS_PHYSICAL_ADAPTER_INFORMATION @6959-6963
- struct_item D3DKMT_QUERYSTATISTICS_POLICY @6966-6972
- function_item default @6974-6976
- struct_item D3DKMT_QUERYSTATISTICS_PREEMPTION_INFORMATION @6980-6982
- function_item default @6984-6986
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_ADAPTER_INFORMATION @6993-7003
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_INFORMATION @7006-7011
- function_item default @7013-7015
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_INTERFERENCE_COUNTERS @7020-7022
- function_item default @7024-7026
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_NODE_INFORMATION @7032-7038
- function_item default @7040-7042
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_SEGMENT_GROUP_INFORMATION @7050-7055
- function_item default @7057-7059
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_SEGMENT_INFORMATION @7063-7072
- function_item default @7074-7076
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_SEGMENT_POLICY @7080-7082
- struct_item D3DKMT_QUERYSTATISTICS_PROCESS_VIDPNSOURCE_INFORMATION @7086-7096
- function_item default @7098-7100
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_ADAPTER2 @7104-7106
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_ADAPTER_INFORMATION2 @7109-7111
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_NODE @7114-7116
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_NODE2 @7119-7122
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_PHYSICAL_ADAPTER @7125-7127
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_PROCESS_SEGMENT_GROUP2 @7130-7133
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_SEGMENT @7136-7138
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_SEGMENT2 @7141-7144
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_SEGMENT_GROUP_USAGE @7147-7150
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_SEGMENT_USAGE @7153-7156
- struct_item D3DKMT_QUERYSTATISTICS_QUERY_VIDPNSOURCE @7159-7161
- struct_item D3DKMT_QUERYSTATISTICS_QUEUE_PACKET_TYPE_INFORMATION @7165-7168
- function_item default @7188-7190
- struct_item D3DKMT_QUERYSTATISTICS_SEGMENT_INFORMATION @7197-7208
- function_item default @7210-7212
- struct_item D3DKMT_QUERYSTATISTICS_SEGMENT_INFORMATION_0 @7216-7218
- struct_item D3DKMT_QUERYSTATISTICS_SEGMENT_INFORMATION_1 @7221-7223
- struct_item D3DKMT_QUERYSTATISTICS_SYSTEM_MEMORY @7232-7244
- struct_item D3DKMT_QUERYSTATISTICS_VIDEO_MEMORY @7248-7253
- function_item default @7255-7257
- struct_item D3DKMT_QUERYSTATISTICS_VIDPNSOURCE_INFORMATION @7262-7266
- function_item default @7268-7270
- struct_item D3DKMT_QUERYSTATSTICS_ALLOCATIONS @7274-7282
- struct_item D3DKMT_QUERYSTATSTICS_LOCKS @7285-7293
- struct_item D3DKMT_QUERYSTATSTICS_PAGING_FAULT @7296-7315
- struct_item D3DKMT_QUERYSTATSTICS_PAGING_TRANSFER @7318-7327
- struct_item D3DKMT_QUERYSTATSTICS_PREPRATION @7330-7336
- struct_item D3DKMT_QUERYSTATSTICS_REFERENCE_DMA_BUFFER @7339-7354
- struct_item D3DKMT_QUERYSTATSTICS_RENAMING @7357-7367
- struct_item D3DKMT_QUERYSTATSTICS_SWIZZLING_RANGE @7370-7373
- struct_item D3DKMT_QUERYSTATSTICS_TERMINATIONS @7376-7381
- struct_item D3DKMT_QUERYVIDEOMEMORYINFO @7384-7393
- function_item default @7395-7397
- struct_item D3DKMT_QUERYVIDPNEXCLUSIVEOWNERSHIP @7401-7407
- function_item default @7409-7411
- struct_item D3DKMT_QUERY_ADAPTER_UNIQUE_GUID @7415-7417
- function_item default @7419-7421
- struct_item D3DKMT_QUERY_DEVICE_IDS @7425-7428
- struct_item D3DKMT_QUERY_GPUMMU_CAPS @7431-7434
- function_item default @7436-7438
- struct_item D3DKMT_QUERY_MIRACAST_DRIVER_TYPE @7442-7444
- struct_item D3DKMT_QUERY_PHYSICAL_ADAPTER_PNP_KEY @7447-7452
- function_item default @7454-7456
- struct_item D3DKMT_QUERY_SCANOUT_CAPS @7460-7463
- struct_item D3DKMT_RECLAIMALLOCATIONS @7468-7474
- function_item default @7476-7478
- struct_item D3DKMT_RECLAIMALLOCATIONS2 @7482-7489
- function_item default @7491-7493
- function_item default @7502-7504
- struct_item D3DKMT_REGISTERBUDGETCHANGENOTIFICATION @7508-7513
- function_item default @7515-7517
- struct_item D3DKMT_REGISTERTRIMNOTIFICATION @7521-7527
- function_item default @7529-7531
- struct_item D3DKMT_RELEASEKEYEDMUTEX @7535-7539
- struct_item D3DKMT_RELEASEKEYEDMUTEX2 @7542-7548
- function_item default @7550-7552
- struct_item D3DKMT_RENDER @7556-7576
- function_item default @7578-7580
- function_item default @7589-7591
- struct_item D3DKMT_RENDERFLAGS @7595-7597
- struct_item D3DKMT_REQUEST_MACHINE_CRASH_ESCAPE @7600-7604
- struct_item D3DKMT_SCATTERBLT @7608-7614
- struct_item D3DKMT_SCATTERBLTS @7617-7620
- function_item default @7622-7624
- struct_item D3DKMT_SEGMENTGROUPSIZEINFO @7635-7641
- struct_item D3DKMT_SEGMENTSIZEINFO @7644-7648
- struct_item D3DKMT_SEGMENT_CAPS @7651-7658
- struct_item D3DKMT_SETALLOCATIONPRIORITY @7661-7667
- function_item default @7669-7671
- struct_item D3DKMT_SETCONTEXTINPROCESSSCHEDULINGPRIORITY @7675-7678
- struct_item D3DKMT_SETCONTEXTSCHEDULINGPRIORITY @7681-7684
- struct_item D3DKMT_SETDISPLAYMODE @7688-7695
- struct_item D3DKMT_SETDISPLAYMODE_FLAGS @7698-7701
- struct_item D3DKMT_SETDISPLAYPRIVATEDRIVERFORMAT @7704-7708
- struct_item D3DKMT_SETFSEBLOCK @7711-7716
- function_item default @7718-7720
- function_item default @7729-7731
- struct_item D3DKMT_SETFSEBLOCKFLAGS_0 @7735-7737
- struct_item D3DKMT_SETGAMMARAMP @7740-7746
- function_item default @7748-7750
- function_item default @7759-7761
- struct_item D3DKMT_SETHWPROTECTIONTEARDOWNRECOVERY @7765-7768
- struct_item D3DKMT_SETQUEUEDLIMIT @7771-7775
- function_item default @7777-7779
- function_item default @7788-7790
- struct_item D3DKMT_SETQUEUEDLIMIT_0_0 @7794-7797
- struct_item D3DKMT_SETSTABLEPOWERSTATE @7800-7803
- struct_item D3DKMT_SETSYNCREFRESHCOUNTWAITTARGET @7806-7811
- struct_item D3DKMT_SETVIDPNSOURCEHWPROTECTION @7814-7818
- struct_item D3DKMT_SETVIDPNSOURCEOWNER @7821-7826
- function_item default @7828-7830
- struct_item D3DKMT_SETVIDPNSOURCEOWNER1 @7834-7837
- function_item default @7839-7841
- struct_item D3DKMT_SETVIDPNSOURCEOWNER2 @7845-7848
- function_item default @7850-7852
- struct_item D3DKMT_SET_COLORSPACE_TRANSFORM @7856-7862
- function_item default @7864-7866
- function_item default @7874-7876
- struct_item D3DKMT_SHAREDPRIMARYLOCKNOTIFICATION @7881-7885
- struct_item D3DKMT_SHAREDPRIMARYUNLOCKNOTIFICATION @7888-7891
- struct_item D3DKMT_SHAREOBJECTWITHHOST @7894-7899
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECT @7902-7907
- function_item default @7909-7911
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECT2 @7915-7923
- function_item default @7925-7927
- function_item default @7937-7939
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECT2_0_0 @7943-7945
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECTFROMCPU @7948-7954
- function_item default @7956-7958
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECTFROMGPU @7962-7967
- function_item default @7969-7971
- function_item default @7980-7982
- struct_item D3DKMT_SIGNALSYNCHRONIZATIONOBJECTFROMGPU2 @7986-7993
- function_item default @7995-7997
- function_item default @8008-8010
- struct_item D3DKMT_STANDARDALLOCATION_EXISTINGHEAP @8018-8020
- struct_item D3DKMT_SUBMITCOMMAND @8025-8038
- function_item default @8040-8042
- struct_item D3DKMT_SUBMITCOMMANDFLAGS @8046-8048
- struct_item D3DKMT_SUBMITCOMMANDTOHWQUEUE @8051-8060
- function_item default @8062-8064
- struct_item D3DKMT_SUBMITPRESENTBLTTOHWQUEUE @8068-8072
- function_item default @8074-8076
- struct_item D3DKMT_SUBMITPRESENTTOHWQUEUE @8080-8083
- function_item default @8085-8087
- struct_item D3DKMT_SUBMITSIGNALSYNCOBJECTSTOHWQUEUE @8091-8098
- function_item default @8100-8102
- struct_item D3DKMT_SUBMITWAITFORSYNCOBJECTSTOHWQUEUE @8106-8111
- function_item default @8113-8115
- struct_item D3DKMT_SURFACECOMPLETE_PRESENTHISTORYTOKEN @8119-8121
- struct_item D3DKMT_TDRDBGCTRL_ESCAPE @8139-8142
- function_item default @8144-8146
- function_item default @8154-8156
- struct_item D3DKMT_TRACKEDWORKLOAD_SUPPORT @8160-8164
- struct_item D3DKMT_TRIMNOTIFICATION @8167-8171
- function_item default @8173-8175
- struct_item D3DKMT_TRIMPROCESSCOMMITMENT @8179-8185
- function_item default @8187-8189
- function_item default @8198-8200
- struct_item D3DKMT_TRIMPROCESSCOMMITMENT_FLAGS_0 @8204-8206
- struct_item D3DKMT_UMDFILENAMEINFO @8209-8212
- function_item default @8214-8216
- struct_item D3DKMT_UMD_DRIVER_VERSION @8220-8222
- struct_item D3DKMT_UNLOCK @8225-8229
- function_item default @8231-8233
- struct_item D3DKMT_UNLOCK2 @8237-8240
- struct_item D3DKMT_UNPINDIRECTFLIPRESOURCES @8243-8247
- function_item default @8249-8251
- struct_item D3DKMT_UNREGISTERBUDGETCHANGENOTIFICATION @8255-8257
- function_item default @8259-8261
- struct_item D3DKMT_UNREGISTERTRIMNOTIFICATION @8265-8268
- function_item default @8270-8272
- struct_item D3DKMT_UPDATEGPUVIRTUALADDRESS @8276-8286
- function_item default @8288-8290
- function_item default @8299-8301
- struct_item D3DKMT_UPDATEGPUVIRTUALADDRESS_0_0 @8305-8307
- struct_item D3DKMT_UPDATEOVERLAY @8310-8314
- struct_item D3DKMT_VAD_DESC @8317-8324
- struct_item D3DKMT_VA_RANGE_DESC @8334-8345
- struct_item D3DKMT_VGPUINTERFACEID @8351-8353
- function_item default @8355-8357
- struct_item D3DKMT_VIDMM_ESCAPE @8381-8384
- function_item default @8386-8388
- function_item default @8410-8412
- struct_item D3DKMT_VIDMM_ESCAPE_0_10 @8416-8423
- struct_item D3DKMT_VIDMM_ESCAPE_0_11 @8426-8431
- struct_item D3DKMT_VIDMM_ESCAPE_0_13 @8434-8436
- struct_item D3DKMT_VIDMM_ESCAPE_0_2 @8439-8441
- struct_item D3DKMT_VIDMM_ESCAPE_0_1 @8444-8448
- function_item default @8450-8452
- struct_item D3DKMT_VIDMM_ESCAPE_0_7 @8456-8458
- struct_item D3DKMT_VIDMM_ESCAPE_0_3 @8461-8465
- function_item default @8467-8469
- function_item default @8482-8484
- struct_item D3DKMT_VIDMM_ESCAPE_0_3_0_0 @8488-8490
- struct_item D3DKMT_VIDMM_ESCAPE_0_6 @8493-8495
- function_item default @8497-8499
- struct_item D3DKMT_VIDMM_ESCAPE_0_4 @8503-8506
- struct_item D3DKMT_VIDMM_ESCAPE_0_0 @8509-8511
- function_item default @8513-8515
- function_item default @8524-8526
- struct_item D3DKMT_VIDMM_ESCAPE_0_0_0_0 @8530-8532
- struct_item D3DKMT_VIDMM_ESCAPE_0_8 @8535-8539
- struct_item D3DKMT_VIDMM_ESCAPE_0_5 @8542-8545
- function_item default @8547-8549
- struct_item D3DKMT_VIDMM_ESCAPE_0_12 @8553-8555
- struct_item D3DKMT_VIDMM_ESCAPE_0_9 @8558-8560
- struct_item D3DKMT_VIDPNSOURCEOWNER_FLAGS @8566-8568
- function_item default @8570-8572
- function_item default @8581-8583
- struct_item D3DKMT_VIDPNSOURCEOWNER_FLAGS_0_0 @8587-8589
- struct_item D3DKMT_VIDSCH_ESCAPE @8605-8609
- function_item default @8611-8613
- function_item default @8628-8630
- struct_item D3DKMT_VIDSCH_ESCAPE_0_0 @8634-8637
- function_item default @8639-8641
- function_item default @8649-8651
- struct_item D3DKMT_VIDSCH_ESCAPE_0_1 @8655-8658
- struct_item D3DKMT_VIRTUALADDRESSFLAGS @8661-8663
- struct_item D3DKMT_VIRTUALADDRESSINFO @8666-8668
- struct_item D3DKMT_WAITFORIDLE @8671-8673
- struct_item D3DKMT_WAITFORSYNCHRONIZATIONOBJECT @8676-8680
- function_item default @8682-8684
- struct_item D3DKMT_WAITFORSYNCHRONIZATIONOBJECT2 @8688-8693
- function_item default @8695-8697
- function_item default @8706-8708
- struct_item D3DKMT_WAITFORSYNCHRONIZATIONOBJECT2_0_0 @8712-8714
- struct_item D3DKMT_WAITFORSYNCHRONIZATIONOBJECTFROMCPU @8717-8724
- function_item default @8726-8728
- struct_item D3DKMT_WAITFORSYNCHRONIZATIONOBJECTFROMGPU @8732-8737
- function_item default @8739-8741
- function_item default @8751-8753
- struct_item D3DKMT_WAITFORVERTICALBLANKEVENT @8757-8761
- struct_item D3DKMT_WAITFORVERTICALBLANKEVENT2 @8764-8770
- function_item default @8772-8774
- struct_item D3DKMT_WDDM_1_2_CAPS @8778-8781
- function_item default @8783-8785
- function_item default @8794-8796
- struct_item D3DKMT_WDDM_1_2_CAPS_0_0 @8800-8802
- struct_item D3DKMT_WDDM_1_3_CAPS @8805-8807
- function_item default @8809-8811
- function_item default @8820-8822
- struct_item D3DKMT_WDDM_1_3_CAPS_0_0 @8826-8828
- struct_item D3DKMT_WDDM_2_0_CAPS @8831-8833
- function_item default @8835-8837
- function_item default @8846-8848
- struct_item D3DKMT_WDDM_2_0_CAPS_0_0 @8852-8854
- struct_item D3DKMT_WDDM_2_7_CAPS @8857-8859
- function_item default @8861-8863
- function_item default @8872-8874
- struct_item D3DKMT_WDDM_2_7_CAPS_0_0 @8878-8880
- struct_item D3DKMT_WDDM_2_9_CAPS @8883-8885
- function_item default @8887-8889
- function_item default @8898-8900
- struct_item D3DKMT_WDDM_2_9_CAPS_0_0 @8904-8906
- struct_item D3DKMT_WDDM_3_0_CAPS @8909-8911
- function_item default @8913-8915
- function_item default @8924-8926
- struct_item D3DKMT_WDDM_3_0_CAPS_0_0 @8930-8932
- struct_item D3DKMT_WDDM_3_1_CAPS @8935-8937
- function_item default @8939-8941
- function_item default @8950-8952
- struct_item D3DKMT_WDDM_3_1_CAPS_0_0 @8956-8958
- struct_item D3DKMT_WORKINGSETFLAGS @8961-8963
- struct_item D3DKMT_WORKINGSETINFO @8966-8970
- struct_item D3DKMT_WSAUMDIMAGENAME @8973-8975
- function_item default @8977-8979
- struct_item D3DKMT_XBOX @8984-8986
- struct_item D3DLINEPATTERN @8989-8992
- struct_item D3DNTHAL_CLIPPEDTRIANGLEFAN @9091-9095
- struct_item D3DNTHAL_CONTEXTDESTROYALLDATA @9099-9102
- struct_item D3DNTHAL_CONTEXTDESTROYDATA @9105-9108
- struct_item D3DNTHAL_D3DDX6EXTENDEDCAPS @9112-9135
- struct_item D3DNTHAL_D3DEXTENDEDCAPS @9138-9170
- struct_item D3DNTHAL_DP2ADDDIRTYRECT @9173-9176
- struct_item D3DNTHAL_DP2BLT @9179-9187
- struct_item D3DNTHAL_DP2CLEAR @9190-9196
- function_item default @9198-9200
- struct_item D3DNTHAL_DP2COLORFILL @9204-9208
- struct_item D3DNTHAL_DP2COMMAND @9211-9215
- function_item default @9217-9219
- function_item default @9228-9230
- struct_item D3DNTHAL_DP2CREATELIGHT @9234-9236
- struct_item D3DNTHAL_DP2CREATEPIXELSHADER @9239-9242
- struct_item D3DNTHAL_DP2CREATEVERTEXSHADER @9245-9249
- struct_item D3DNTHAL_DP2CREATEVERTEXSHADERDECL @9252-9255
- struct_item D3DNTHAL_DP2CREATEVERTEXSHADERFUNC @9258-9261
- struct_item D3DNTHAL_DP2DELETEQUERY @9264-9266
- struct_item D3DNTHAL_DP2DRAWRECTPATCH @9269-9272
- struct_item D3DNTHAL_DP2DRAWTRIPATCH @9275-9278
- struct_item D3DNTHAL_DP2EXT @9281-9284
- struct_item D3DNTHAL_DP2INDEXEDLINELIST @9287-9290
- struct_item D3DNTHAL_DP2INDEXEDLINESTRIP @9293-9295
- function_item default @9297-9299
- struct_item D3DNTHAL_DP2INDEXEDTRIANGLEFAN @9303-9305
- function_item default @9307-9309
- struct_item D3DNTHAL_DP2INDEXEDTRIANGLELIST @9313-9318
- struct_item D3DNTHAL_DP2INDEXEDTRIANGLELIST2 @9321-9325
- struct_item D3DNTHAL_DP2INDEXEDTRIANGLESTRIP @9328-9330
- function_item default @9332-9334
- struct_item D3DNTHAL_DP2ISSUEQUERY @9338-9341
- struct_item D3DNTHAL_DP2LINELIST @9344-9346
- struct_item D3DNTHAL_DP2LINESTRIP @9349-9351
- struct_item D3DNTHAL_DP2PIXELSHADER @9355-9357
- struct_item D3DNTHAL_DP2POINTS @9360-9363
- struct_item D3DNTHAL_DP2RESPONSE @9366-9371
- struct_item D3DNTHAL_DP2RESPONSEQUERY @9374-9377
- struct_item D3DNTHAL_DP2SETCLIPPLANE @9380-9383
- function_item default @9385-9387
- struct_item D3DNTHAL_DP2SETCONVOLUTIONKERNELMONO @9391-9395
- struct_item D3DNTHAL_DP2SETDEPTHSTENCIL @9398-9400
- struct_item D3DNTHAL_DP2SETINDICES @9403-9406
- struct_item D3DNTHAL_DP2SETLIGHT @9409-9412
- function_item default @9414-9416
- function_item default @9425-9427
- struct_item D3DNTHAL_DP2SETPALETTE @9431-9435
- struct_item D3DNTHAL_DP2SETPIXELSHADERCONST @9438-9441
- struct_item D3DNTHAL_DP2SETPRIORITY @9444-9447
- struct_item D3DNTHAL_DP2SETRENDERTARGET @9450-9453
- struct_item D3DNTHAL_DP2SETRENDERTARGET2 @9456-9459
- struct_item D3DNTHAL_DP2SETSTREAMSOURCE @9462-9466
- struct_item D3DNTHAL_DP2SETSTREAMSOURCE2 @9469-9474
- struct_item D3DNTHAL_DP2SETSTREAMSOURCEFREQ @9477-9480
- struct_item D3DNTHAL_DP2SETSTREAMSOURCEUM @9483-9486
- struct_item D3DNTHAL_DP2SETTEXLOD @9489-9492
- struct_item D3DNTHAL_DP2SETVERTEXSHADERCONST @9495-9498
- struct_item D3DNTHAL_DP2STARTVERTEX @9501-9503
- struct_item D3DNTHAL_DP2SURFACEBLT @9506-9514
- struct_item D3DNTHAL_DP2TEXBLT @9517-9523
- struct_item D3DNTHAL_DP2TEXTURESTAGESTATE @9526-9530
- struct_item D3DNTHAL_DP2TRIANGLEFAN @9533-9535
- struct_item D3DNTHAL_DP2TRIANGLEFAN_IMM @9538-9540
- struct_item D3DNTHAL_DP2TRIANGLELIST @9543-9545
- struct_item D3DNTHAL_DP2TRIANGLESTRIP @9548-9550
- struct_item D3DNTHAL_DP2UPDATEPALETTE @9553-9557
- struct_item D3DNTHAL_DP2VERTEXSHADER @9560-9562
- struct_item D3DNTHAL_DP2VIEWPORTINFO @9565-9570
- struct_item D3DNTHAL_DP2WINFO @9573-9576
- struct_item D3DNTHAL_DP2ZRANGE @9579-9582
- struct_item D3DNTHAL_SCENECAPTUREDATA @9588-9592
- struct_item D3DNTHAL_TEXTURECREATEDATA @9598-9603
- function_item default @9605-9607
- struct_item D3DNTHAL_TEXTUREDESTROYDATA @9611-9615
- struct_item D3DNTHAL_TEXTUREGETSURFDATA @9618-9623
- function_item default @9625-9627
- struct_item D3DNTHAL_TEXTURESWAPDATA @9631-9636
- struct_item D3DNTHAL_VALIDATETEXTURESTAGESTATEDATA @9642-9648
- struct_item DDNT_DEFERRED_AGP_AWARE_DATA @9857-9859
- struct_item DDNT_DXVERSION @9862-9866
- struct_item DDNT_FREE_DEFERRED_AGP_DATA @9869-9872
- struct_item DDNT_GETADAPTERGROUPDATA @9875-9880
- struct_item DDNT_GETD3DQUERYCOUNTDATA @9883-9886
- struct_item DDNT_GETDDIVERSIONDATA @9889-9893
- struct_item DDNT_GETDRIVERINFO2DATA @9896-9901
- struct_item DDNT_GETEXTENDEDMODECOUNTDATA @9904-9908
- struct_item DDNT_GETFORMATCOUNTDATA @9911-9915
- struct_item DD_DEFERRED_AGP_AWARE_DATA @9918-9920
- struct_item DD_DXVERSION @9923-9927
- struct_item DD_FREE_DEFERRED_AGP_DATA @9930-9933
- struct_item DD_GETADAPTERGROUPDATA @9936-9941
- struct_item DD_GETD3DQUERYCOUNTDATA @9944-9947
- struct_item DD_GETDDIVERSIONDATA @9950-9954
- struct_item DD_GETDRIVERINFO2DATA @9957-9962
- struct_item DD_GETEXTENDEDMODECOUNTDATA @9965-9969
- struct_item DD_GETFORMATCOUNTDATA @9972-9976
- struct_item DISPLAYID_DETAILED_TIMING_TYPE_I @9992-10002
- struct_item DISPLAYID_DETAILED_TIMING_TYPE_I_0 @10005-10007
- struct_item DISPLAYID_DETAILED_TIMING_TYPE_I_1 @10010-10012
- struct_item DISPLAYID_DETAILED_TIMING_TYPE_I_2 @10015-10017
- struct_item DXGKARG_SETPALETTE @10028-10033
- function_item default @10035-10037
- struct_item DXGKMDT_OPM_ACP_AND_CGMSA_SIGNALING @10069-10083
- function_item default @10085-10087
- struct_item DXGKMDT_OPM_ACTUAL_OUTPUT_FORMAT @10096-10105
- struct_item DXGKMDT_OPM_CONFIGURE_PARAMETERS @10135-10141
- function_item default @10143-10145
- struct_item DXGKMDT_OPM_CONNECTED_HDCP_DEVICE_INFORMATION @10150-10158
- function_item default @10160-10162
- struct_item DXGKMDT_OPM_COPP_COMPATIBLE_GET_INFO_PARAMETERS @10187-10193
- function_item default @10195-10197
- struct_item DXGKMDT_OPM_CREATE_VIDEO_OUTPUT_FOR_TARGET_PARAMETERS @10201-10205
- struct_item DXGKMDT_OPM_ENCRYPTED_PARAMETERS @10213-10215
- function_item default @10217-10219
- struct_item DXGKMDT_OPM_GET_INFO_PARAMETERS @10234-10241
- function_item default @10243-10245
- struct_item DXGKMDT_OPM_HDCP_KEY_SELECTION_VECTOR @10256-10258
- function_item default @10260-10262
- struct_item DXGKMDT_OPM_OMAC @10276-10278
- function_item default @10280-10282
- struct_item DXGKMDT_OPM_OUTPUT_ID @10290-10294
- struct_item DXGKMDT_OPM_RANDOM_NUMBER @10326-10328
- function_item default @10330-10332
- struct_item DXGKMDT_OPM_REQUESTED_INFORMATION @10337-10341
- function_item default @10343-10345
- struct_item DXGKMDT_OPM_SET_ACP_AND_CGMSA_SIGNALING_PARAMETERS @10351-10362
- function_item default @10364-10366
- struct_item DXGKMDT_OPM_SET_HDCP_SRM_PARAMETERS @10371-10373
- struct_item DXGKMDT_OPM_SET_PROTECTION_LEVEL_PARAMETERS @10378-10383
- struct_item DXGKMDT_OPM_STANDARD_INFORMATION @10386-10392
- struct_item DXGKVGPU_ESCAPE_HEAD @10425-10428
- struct_item DXGKVGPU_ESCAPE_INITIALIZE @10431-10434
- struct_item DXGKVGPU_ESCAPE_PAUSE @10437-10441
- function_item default @10443-10445
- function_item default @10454-10456
- struct_item DXGKVGPU_ESCAPE_PAUSE_0_0 @10460-10462
- struct_item DXGKVGPU_ESCAPE_POWERTRANSITIONCOMPLETE @10465-10468
- struct_item DXGKVGPU_ESCAPE_READ_PCI_CONFIG @10471-10475
- struct_item DXGKVGPU_ESCAPE_READ_VGPU_TYPE @10478-10480
- struct_item DXGKVGPU_ESCAPE_RELEASE @10483-10485
- struct_item DXGKVGPU_ESCAPE_RESUME @10488-10492
- struct_item DXGKVGPU_ESCAPE_WRITE_PCI_CONFIG @10504-10508
- struct_item DXGK_ADAPTER_PERFDATA @10511-10521
- struct_item DXGK_ADAPTER_PERFDATACAPS @10524-10530
- struct_item DXGK_BACKLIGHT_INFO @10533-10537
- struct_item DXGK_BRIGHTNESS_CAPS @10541-10543
- function_item default @10545-10547
- function_item default @10556-10558
- struct_item DXGK_BRIGHTNESS_CAPS_0_0 @10562-10564
- struct_item DXGK_BRIGHTNESS_GET_NIT_RANGES_OUT @10567-10572
- function_item default @10574-10576
- struct_item DXGK_BRIGHTNESS_GET_OUT @10580-10583
- struct_item DXGK_BRIGHTNESS_NIT_RANGE @10587-10591
- struct_item DXGK_BRIGHTNESS_SENSOR_DATA @10594-10600
- function_item default @10602-10604
- function_item default @10613-10615
- struct_item DXGK_BRIGHTNESS_SENSOR_DATA_0_0 @10619-10621
- struct_item DXGK_BRIGHTNESS_SENSOR_DATA_CHROMATICITY @10624-10627
- struct_item DXGK_BRIGHTNESS_SET_IN @10630-10634
- function_item default @10636-10638
- struct_item DXGK_BRIGHTNESS_STATE @10642-10644
- function_item default @10646-10648
- function_item default @10657-10659
- struct_item DXGK_BRIGHTNESS_STATE_0_0 @10663-10665
- struct_item DXGK_DISPLAY_INFORMATION @10674-10682
- struct_item DXGK_ESCAPE_GPUMMUCAPS @10711-10722
- function_item default @10724-10726
- struct_item DXGK_FAULT_ERROR_CODE @10730-10732
- function_item default @10734-10736
- function_item default @10745-10747
- struct_item DXGK_FAULT_ERROR_CODE_0_0 @10751-10753
- struct_item DXGK_FAULT_ERROR_CODE_0_1 @10756-10758
- struct_item DXGK_GPUCLOCKDATA @10764-10769
- function_item default @10771-10773
- struct_item DXGK_GPUCLOCKDATA_FLAGS @10777-10779
- function_item default @10781-10783
- function_item default @10792-10794
- struct_item DXGK_GPUCLOCKDATA_FLAGS_0_0 @10798-10800
- struct_item DXGK_GPUVERSION @10803-10806
- function_item default @10808-10810
- struct_item DXGK_GRAPHICSPOWER_REGISTER_INPUT_V_1_2 @10815-10822
- function_item default @10825-10827
- struct_item DXGK_GRAPHICSPOWER_REGISTER_OUTPUT @10832-10837
- function_item default @10840-10842
- function_item default @10859-10861
- struct_item DXGK_MIRACAST_CHUNK_ID_0 @10865-10867
- struct_item DXGK_MIRACAST_CHUNK_INFO @10870-10875
- function_item default @10877-10879
- function_item default @10896-10898
- struct_item DXGK_MONITORLINKINFO_CAPABILITIES_0 @10902-10904
- function_item default @10912-10914
- struct_item DXGK_MONITORLINKINFO_USAGEHINTS_0 @10918-10920
- struct_item DXGK_NODEMETADATA @10923-10929
- function_item default @10931-10933
- struct_item DXGK_NODEMETADATA_FLAGS @10937-10939
- function_item default @10941-10943
- function_item default @10952-10954
- struct_item DXGK_NODEMETADATA_FLAGS_0_0 @10958-10960
- struct_item DXGK_NODE_PERFDATA @10963-10971
- struct_item DXGK_PTE @10983-10986
- function_item default @10988-10990
- function_item default @10999-11001
- struct_item DXGK_PTE_0_0 @11005-11007
- function_item default @11015-11017
- struct_item DXGK_TARGETMODE_DETAIL_TIMING @11033-11037
- struct_item GPUP_DRIVER_ESCAPE_INPUT @11046-11048
- struct_item OUTPUTDUPL_CONTEXT_DEBUG_INFO @11189-11196
- function_item default @11198-11200
- struct_item _NT_D3DLINEPATTERN @11432-11435

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [554dea11-c531-4502-aa42-b776ac0d93b6.md](554dea11-c531-4502-aa42-b776ac0d93b6.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `9b82c28ff094bb3b4a59502ced522e7015cfa856b2c4aaca06ef5277725d50f2`.
