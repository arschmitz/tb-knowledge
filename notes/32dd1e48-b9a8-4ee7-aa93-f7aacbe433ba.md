<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["intl"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["a7d32034dee08052c1867d60ac26a1d9d191baaa4694f6e9beea155f5d3a6ef1"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/e991744b-5751-4d04-9315-e7dbbd02b209.md"}} -->
# firefox/intl native and TypeScript syntax map 103

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### intl/icu/source/i18n/coptccal.cpp

Blob: `797f28872ee090575dec69d48a39ff68ebd963cb`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "gregoimp.h" @14
- include "umutex.h" @15
- include "coptccal.h" @16
- include "cecal.h" @17
- include <float.h> @18
- function_definition CopticCalendar @30-33
- function_definition CopticCalendar @35-38
- function_definition ~CopticCalendar @40-42
- function_definition clone @44-48
- function_definition getType @50-54
- function_definition handleGetExtendedYear @60-71
- function_definition getJDEpochOffset @75-79
- function_definition extendedYearToEra @81-83
- function_definition extendedYearToYear @85-87
- function_definition handleGetLimit @89-96
- function_definition getRelatedYearDifference @98-102

### intl/icu/source/i18n/coptccal.h

Blob: `27ddfb5995a1ad136b2cffa48077f501d6c6c36d`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/calendar.h" @17
- include "cecal.h" @18
- function_definition CECalendar @20-224
- enum_specifier EMonths @33-113
- enum_specifier EEras @115-118

### intl/icu/source/i18n/cpdtrans.cpp

Blob: `99643da07eb91cd3c0de3b4cc0801ca4a7eb2d70`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/unifilt.h" @17
- include "unicode/uniset.h" @18
- include "cpdtrans.h" @19
- include "uvector.h" @20
- include "tridpars.h" @21
- include "cmemory.h" @22
- function_definition CompoundTransliterator @51-58
- function_definition CompoundTransliterator @67-77
- function_definition CompoundTransliterator @79-87
- function_definition CompoundTransliterator @93-103
- function_definition CompoundTransliterator @110-120
- function_definition CompoundTransliterator @122-130
- function_definition init @148-175
- function_definition init @190-234
- function_definition joinIDs @241-251
- function_definition CompoundTransliterator @256-259
- function_definition ~CompoundTransliterator @264-266
- function_definition freeTransliterators @268-277
- function_definition (anonymous) @282-322
- function_definition clone @327-329
- function_definition getCount @335-337
- function_definition (anonymous) @344-346
- function_definition setTransliterators @348-372
- function_definition adoptTransliterators @374-383
- function_definition _smartAppend @388-393
- function_definition (anonymous) @395-438
- function_definition handleGetSourceSet @443-460
- function_definition (anonymous) @465-473
- function_definition handleTransliterate @478-596
- function_definition computeMaximumContextLength @602-611

### intl/icu/source/i18n/cpdtrans.h

Blob: `b01c2df6ac6d3a34a555813bf3f04fd0212a35e3`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @15
- include "unicode/translit.h" @19
- class_specifier TransliteratorRegistry @24-24
- function_definition CompoundTransliterator @40-226
- class_specifier U_I18N_API @40-40

### intl/icu/source/i18n/csdetect.cpp

Blob: `cedc3c06349038aa9da9fbc3c0309e662fce28f2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "unicode/ucsdet.h" @14
- include "csdetect.h" @16
- include "csmatch.h" @17
- include "uenumimp.h" @18
- include "cmemory.h" @20
- include "cstring.h" @21
- include "umutex.h" @22
- include "ucln_in.h" @23
- include "uarrsort.h" @24
- include "inputext.h" @25
- include "csrsbcs.h" @26
- include "csrmbcs.h" @27
- include "csrutf8.h" @28
- include "csrucode.h" @29
- include "csr2022.h" @30
- function_definition UMemory @35-45
- function_definition CSRecognizerInfo @38-39
- function_definition ~CSRecognizerInfo @41-41
- function_definition csdet_cleanup @53-70
- function_definition charsetMatchComparator @72-82
- function_definition initRecognizers @84-139
- function_definition setRecognizers @141-148
- function_definition CharsetDetector @150-180
- function_definition ~CharsetDetector @182-195
- function_definition setText @197-201
- function_definition setStripTagsFlag @203-209
- function_definition getStripTagsFlag @211-214
- function_definition setDeclaredEncoding @216-219
- function_definition getDetectableCount @221-228
- function_definition detect @230-241
- function_definition detectAll @243-279
- function_definition setDetectableCharset @281-319
- function_definition U_CDECL_BEGIN @332-339
- function_definition enumClose @343-350
- function_definition enumCount @352-378
- function_definition enumNext @380-417
- function_definition enumReset @420-423
- function_definition getAllDetectableCharsets @435-464
- function_definition getDetectableCharsets @466-488

### intl/icu/source/i18n/csdetect.h

Blob: `d4bfa75eef25fecbd2da58c342627f337080c38f`. Grammar: cpp. Status: contains-errors.

- include "unicode/uobject.h" @13
- include "unicode/uenum.h" @17
- class_specifier CharsetRecognizer @22-22
- class_specifier CharsetMatch @23-23
- class_specifier CharsetDetector @25-64

### intl/icu/source/i18n/csmatch.cpp

Blob: `35a84c76f2828430f7f12a9ea6bd299882ff43e1`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "unicode/unistr.h" @13
- include "unicode/ucnv.h" @14
- include "csmatch.h" @16
- include "csrecog.h" @18
- include "inputext.h" @19
- function_definition set @29-44
- function_definition getName @46-49
- function_definition getLanguage @51-54
- function_definition getConfidence @56-59
- function_definition getUChars @61-69

### intl/icu/source/i18n/csmatch.h

Blob: `c31da81863785d6615695b8e66f16bfa02a04652`. Grammar: cpp. Status: contains-errors.

- include "unicode/uobject.h" @13
- class_specifier CharsetRecognizer @20-20
- class_specifier CharsetMatch @33-66

### intl/icu/source/i18n/csr2022.cpp

Blob: `9de668a8a07dac28af884247d0f87745abc1cd59`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "cmemory.h" @14
- include "cstring.h" @15
- include "csr2022.h" @17
- include "csmatch.h" @18
- function_definition match_2022 @20-105
- function_definition ~CharsetRecog_2022JP @143-143
- function_definition getName @145-147
- function_definition match @149-156
- function_definition ~CharsetRecog_2022KR @159-159
- function_definition getName @161-163
- function_definition match @165-172
- function_definition ~CharsetRecog_2022CN @174-174
- function_definition getName @176-178
- function_definition match @180-187
- function_definition ~CharsetRecog_2022 @190-192

### intl/icu/source/i18n/csr2022.h

Blob: `4418728f0ec05a2288e5e6943bfa9e8b33874d25`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "csrecog.h" @17
- class_specifier CharsetRecog_2022 @33-58
- function_definition ~CharsetRecog_2022 @37-37
- class_specifier CharsetRecog_2022JP @60-68
- class_specifier CharsetRecog_2022KR @71-79
- class_specifier CharsetRecog_2022CN @81-89

### intl/icu/source/i18n/csrecog.cpp

Blob: `31fce5dd012f523aec270f85065ac2c25701b5c9`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "csrecog.h" @14
- function_definition ~CharsetRecognizer @16-21
- function_definition getLanguage @23-26

### intl/icu/source/i18n/csrecog.h

Blob: `1aa941d5db6d3ed88978c49148d279e83b2c1ec9`. Grammar: cpp. Status: contains-errors.

- include "unicode/uobject.h" @13
- include "inputext.h" @17
- class_specifier CharsetRecognizer @23-52

### intl/icu/source/i18n/csrmbcs.cpp

Blob: `cb78a3433b2a7e616e5bce47ea751bff024b5518`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "cmemory.h" @14
- include "csmatch.h" @15
- include "csrmbcs.h" @16
- include <math.h> @18
- function_definition binarySearch @95-115
- function_definition IteratedChar @117-121
- function_definition nextByte @132-141
- function_definition ~CharsetRecog_mbcs @143-146
- function_definition match_mbcs @148-234
- function_definition ~CharsetRecog_sjis @236-239
- function_definition nextChar @241-267
- function_definition match @269-273
- function_definition getName @275-278
- function_definition getLanguage @280-283
- function_definition ~CharsetRecog_euc @285-288
- function_definition nextChar @290-352
- function_definition ~CharsetRecog_euc_jp @354-357
- function_definition getName @359-362
- function_definition getLanguage @364-367
- function_definition match @369-374
- function_definition ~CharsetRecog_euc_kr @376-379
- function_definition getName @381-384
- function_definition getLanguage @386-389
- function_definition match @391-396
- function_definition ~CharsetRecog_big5 @398-401
- function_definition nextChar @403-431
- function_definition getName @433-436
- function_definition getLanguage @438-441
- function_definition match @443-448
- function_definition ~CharsetRecog_gb_18030 @450-453
- function_definition nextChar @455-507
- function_definition getName @509-512
- function_definition getLanguage @514-517
- function_definition match @519-524

### intl/icu/source/i18n/csrmbcs.h

Blob: `ff7fc4e2a785f092cbd9d715b4fe1e0276bf1d6e`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "csrecog.h" @17
- function_definition UMemory @19-45
- class_specifier CharsetRecog_mbcs @48-92
- class_specifier CharsetRecog_sjis @99-110
- class_specifier CharsetRecog_euc @119-135
- class_specifier CharsetRecog_euc_jp @141-150
- class_specifier CharsetRecog_euc_kr @156-165
- class_specifier CharsetRecog_big5 @172-183
- class_specifier CharsetRecog_gb_18030 @191-202

### intl/icu/source/i18n/csrsbcs.cpp

Blob: `de2ad314b026462ebf4146bcc252f238dd737091`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "cmemory.h" @12
- include "csrsbcs.h" @15
- include "csmatch.h" @16
- function_definition ~NGramParser @32-34
- function_definition search @40-77
- function_definition lookup @79-87
- function_definition addByte @89-93
- function_definition nextByte @95-102
- function_definition parseCharacters @104-121
- function_definition parse @123-143
- function_definition NGramParser_IBM420 @166-169
- function_definition ~NGramParser_IBM420 @171-171
- function_definition isLamAlef @173-183
- function_definition nextByte @192-209
- function_definition parseCharacters @211-241
- function_definition CharsetRecog_sbcs @244-247
- function_definition ~CharsetRecog_sbcs @249-252
- function_definition match_sbcs @254-262
- struct_specifier NGramsPlusLang @707-710
- function_definition ~CharsetRecog_8859_1 @887-890
- function_definition match @892-906
- function_definition getName @908-911
- function_definition ~CharsetRecog_8859_2 @914-917
- function_definition match @919-933
- function_definition getName @935-938
- function_definition ~CharsetRecog_8859_5 @941-944
- function_definition getName @946-949
- function_definition ~CharsetRecog_8859_5_ru @951-954
- function_definition getLanguage @956-959
- function_definition match @961-966
- function_definition ~CharsetRecog_8859_6 @968-971
- function_definition getName @973-976
- function_definition ~CharsetRecog_8859_6_ar @978-981
- function_definition getLanguage @983-986
- function_definition match @988-993
- function_definition ~CharsetRecog_8859_7 @995-998
- function_definition getName @1000-1003
- function_definition ~CharsetRecog_8859_7_el @1005-1008
- function_definition getLanguage @1010-1013
- function_definition match @1015-1021
- function_definition ~CharsetRecog_8859_8 @1023-1026
- function_definition getName @1028-1031
- function_definition ~CharsetRecog_8859_8_I_he @1033-1036
- function_definition getName @1038-1041
- function_definition getLanguage @1043-1046
- function_definition match @1048-1054
- function_definition ~CharsetRecog_8859_8_he @1056-1059
- function_definition getLanguage @1061-1064
- function_definition match @1066-1072
- function_definition ~CharsetRecog_8859_9 @1074-1077
- function_definition getName @1079-1082
- function_definition ~CharsetRecog_8859_9_tr @1084-1087
- function_definition getLanguage @1089-1092
- function_definition match @1094-1100
- function_definition ~CharsetRecog_windows_1256 @1102-1105
- function_definition getName @1107-1110
- function_definition getLanguage @1112-1115
- function_definition match @1117-1122
- function_definition ~CharsetRecog_windows_1251 @1124-1127
- function_definition getName @1129-1132
- function_definition getLanguage @1134-1137
- function_definition match @1139-1144
- function_definition ~CharsetRecog_KOI8_R @1146-1149
- function_definition getName @1151-1154
- function_definition getLanguage @1156-1159
- function_definition match @1161-1166
- function_definition ~CharsetRecog_IBM424_he @1169-1172
- function_definition getLanguage @1174-1177
- function_definition ~CharsetRecog_IBM424_he_rtl @1179-1182
- function_definition getName @1184-1187
- function_definition match @1189-1194
- function_definition ~CharsetRecog_IBM424_he_ltr @1196-1199
- function_definition getName @1201-1204
- function_definition match @1206-1211
- function_definition ~CharsetRecog_IBM420_ar @1213-1216
- function_definition getLanguage @1218-1221
- function_definition match_sbcs @1224-1232
- function_definition ~CharsetRecog_IBM420_ar_rtl @1234-1237
- function_definition getName @1239-1242
- function_definition match @1244-1249
- function_definition ~CharsetRecog_IBM420_ar_ltr @1251-1254
- function_definition getName @1256-1259
- function_definition match @1261-1266

### intl/icu/source/i18n/csrsbcs.h

Blob: `96f982c59bd14bebf38b9fc1485fd399207e56dc`. Grammar: cpp. Status: contains-errors.

- include "unicode/uobject.h" @13
- include "csrecog.h" @17
- function_definition UMemory @19-54
- class_specifier NGramParser_IBM420 @57-68
- class_specifier CharsetRecog_sbcs @72-80
- class_specifier CharsetRecog_8859_1 @82-88
- class_specifier CharsetRecog_8859_2 @90-96
- class_specifier CharsetRecog_8859_5 @98-103
- class_specifier CharsetRecog_8859_6 @105-111
- class_specifier CharsetRecog_8859_7 @113-119
- class_specifier CharsetRecog_8859_8 @121-127
- class_specifier CharsetRecog_8859_9 @129-135
- class_specifier CharsetRecog_8859_5_ru @139-147
- class_specifier CharsetRecog_8859_6_ar @149-157
- class_specifier CharsetRecog_8859_7_el @159-167
- class_specifier CharsetRecog_8859_8_I_he @169-179
- class_specifier CharsetRecog_8859_8_he @181-189
- class_specifier CharsetRecog_8859_9_tr @191-199
- class_specifier CharsetRecog_windows_1256 @201-211
- class_specifier CharsetRecog_windows_1251 @213-223
- class_specifier CharsetRecog_KOI8_R @226-236
- class_specifier CharsetRecog_IBM424_he @239-245
- class_specifier CharsetRecog_IBM424_he_rtl @247-254
- class_specifier CharsetRecog_IBM424_he_ltr @256-262
- class_specifier CharsetRecog_IBM420_ar @264-272
- class_specifier CharsetRecog_IBM420_ar_rtl @274-281
- class_specifier CharsetRecog_IBM420_ar_ltr @283-289

### intl/icu/source/i18n/csrucode.cpp

Blob: `a6e6f83f0f3219b339b562af2669dba59b3f9aa2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "csrucode.h" @14
- include "csmatch.h" @15
- function_definition ~CharsetRecog_Unicode @17-22
- function_definition ~CharsetRecog_UTF_16_BE @24-27
- function_definition getName @29-32
- function_definition adjustConfidence @40-52
- function_definition match @55-78
- function_definition ~CharsetRecog_UTF_16_LE @80-83
- function_definition getName @85-88
- function_definition match @90-116
- function_definition ~CharsetRecog_UTF_32 @118-121
- function_definition match @123-164
- function_definition ~CharsetRecog_UTF_32_BE @166-169
- function_definition getName @171-174
- function_definition getChar @176-180
- function_definition ~CharsetRecog_UTF_32_LE @182-185
- function_definition getName @187-190
- function_definition getChar @192-196

### intl/icu/source/i18n/csrucode.h

Blob: `78e08d22f11d10aacf761d310df82e6669f87d9d`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "csrecog.h" @17
- function_definition CharsetRecognizer @19-42
- class_specifier CharsetRecog_UTF_16_BE @45-54
- class_specifier CharsetRecog_UTF_16_LE @56-65
- class_specifier CharsetRecog_UTF_32 @67-78
- class_specifier CharsetRecog_UTF_32_BE @81-91
- class_specifier CharsetRecog_UTF_32_LE @94-103

### intl/icu/source/i18n/csrutf8.cpp

Blob: `f114f097224a9163e183d4664bd89f499eda9eed`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "csrutf8.h" @14
- include "csmatch.h" @15
- function_definition ~CharsetRecog_UTF8 @17-22
- function_definition getName @24-27
- function_definition match @29-108

### intl/icu/source/i18n/csrutf8.h

Blob: `bcfb38ac951de7c427f81afaca9bb0bc5128da7d`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "csrecog.h" @17
- function_definition CharsetRecognizer @19-39

### intl/icu/source/i18n/curramt.cpp

Blob: `43c3e9c151a279930b3bed7b46faba6a05fe22d1`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/curramt.h" @17
- include "unicode/currunit.h" @18
- function_definition Measure @20-25
- function_definition CurrencyAmount @27-30
- function_definition CurrencyAmount @32-34
- function_definition (anonymous) @36-39
- function_definition clone @41-43
- function_definition ~CurrencyAmount @45-46
- function_definition (anonymous) @48-50

### intl/icu/source/i18n/currfmt.cpp

Blob: `b7dfc09c545e29ac4b125c9b0ada221280fc27a7`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "currfmt.h" @17
- include "unicode/numfmt.h" @18
- include "unicode/curramt.h" @19
- function_definition MeasureFormat @21-26
- function_definition CurrencyFormat @28-31
- function_definition ~CurrencyFormat @33-34
- function_definition clone @36-38
- function_definition (anonymous) @40-46
- function_definition parseObject @48-56

### intl/icu/source/i18n/currfmt.h

Blob: `2a75cae2bb39b10f4be55bdb7564300d54fcab0f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include "unicode/measfmt.h" @20
- class_specifier CurrencyFormat @38-89

### intl/icu/source/i18n/currpinf.cpp

Blob: `6f43ecb2fedfbeca70379ca219ed477a39b35d68`. Grammar: cpp. Status: contains-errors.

- include "unicode/currpinf.h" @10
- include <iostream> @17
- include "unicode/locid.h" @20
- include "unicode/plurrule.h" @21
- include "unicode/strenum.h" @22
- include "unicode/ures.h" @23
- include "unicode/numsys.h" @24
- include "cstring.h" @25
- include "hash.h" @26
- include "uresimp.h" @27
- include "ureslocs.h" @28
- function_definition ValueComparator @41-46
- function_definition CurrencyPluralInfo @65-71
- function_definition CurrencyPluralInfo @73-79
- function_definition CurrencyPluralInfo @81-88
- function_definition (anonymous) @90-137
- function_definition ~CurrencyPluralInfo @139-146
- function_definition operator== @148-164
- function_definition clone @167-177
- function_definition getPluralRules @179-182
- function_definition (anonymous) @184-207
- function_definition (anonymous) @209-212
- function_definition setPluralRules @214-221
- function_definition setCurrencyPluralPattern @223-238
- function_definition setLocale @240-243
- function_definition initialize @245-268
- function_definition setupCurrencyPluralPattern @270-380
- function_definition deleteHash @382-396
- function_definition initHash @398-409
- function_definition copyHash @411-437

### intl/icu/source/i18n/currunit.cpp

Blob: `98f28365cfc8217f95711e456507b6d46cd20bbc`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/currunit.h" @17
- include "unicode/ustring.h" @18
- include "unicode/uchar.h" @19
- include "cstring.h" @20
- include "uinvchar.h" @21
- include "charstr.h" @22
- include "ustr_imp.h" @23
- include "measunit_impl.h" @24
- function_definition CurrencyUnit @26-56
- function_definition CurrencyUnit @58-80
- function_definition CurrencyUnit @82-84
- function_definition CurrencyUnit @86-97
- function_definition CurrencyUnit @99-104
- function_definition (anonymous) @106-113
- function_definition clone @115-117
- function_definition ~CurrencyUnit @119-120

### intl/icu/source/i18n/dangical.cpp

Blob: `2745bf9a0b64fb037b81d01d3cccdec3beec0573`. Grammar: cpp. Status: contains-errors.

- include "chnsecal.h" @13
- include "dangical.h" @14
- include "astro.h" @18
- include "gregoimp.h" @19
- include "uassert.h" @20
- include "ucln_in.h" @21
- include "umutex.h" @22
- include "unicode/rbtz.h" @23
- include "unicode/tzrule.h" @24
- function_definition calendar_dangi_cleanup @35-52
- function_definition DangiCalendar @65-68
- function_definition DangiCalendar @70-73
- function_definition ~DangiCalendar @75-77
- function_definition clone @79-83
- function_definition getType @85-87
- function_definition initAstronomerTimeZone @117-148
- function_definition getAstronomerTimeZone @150-153
- function_definition getSetting @155-160

### intl/icu/source/i18n/dangical.h

Blob: `e993ef39c13f4f3319e49a857b9f89b1cd2acfa6`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include "unicode/calendar.h" @20
- include "unicode/timezone.h" @21
- include "chnsecal.h" @22
- function_definition ChineseCalendar @24-109

### intl/icu/source/i18n/datefmt.cpp

Blob: `de9efc7ca8f9717a9222bf8d85a775d73979caac`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @22
- include "unicode/ures.h" @26
- include "unicode/datefmt.h" @27
- include "unicode/smpdtfmt.h" @28
- include "unicode/dtptngen.h" @29
- include "unicode/udisplaycontext.h" @30
- include "unicode/gregocal.h" @31
- include "reldtfmt.h" @32
- include "sharedobject.h" @33
- include "unifiedcache.h" @34
- include "uarrsort.h" @35
- include "cstring.h" @37
- include "windtfmt.h" @38
- include <stdio.h> @41
- include <typeinfo> @43
- function_definition SharedObject @49-58
- function_definition DateFmtBestPattern @55-56
- function_definition ~DateFmtBestPattern @60-61
- function_definition createObject @64-68
- class_specifier DateFmtBestPatternKey @70-120
- function_definition equals @74-80
- function_definition DateFmtBestPatternKey @82-87
- function_definition DateFmtBestPatternKey @88-90
- function_definition hashCode @92-94
- function_definition operator== @95-97
- function_definition clone @98-100
- function_definition createObject @101-119
- function_definition ~DateFmtBestPatternKey @122-122
- function_definition DateFormat @125-130
- function_definition DateFormat @134-141
- function_definition (anonymous) @145-165
- function_definition ~DateFormat @169-173
- function_definition operator== @177-191
- function_definition (anonymous) @195-226
- function_definition (anonymous) @230-261
- function_definition (anonymous) @266-275
- function_definition (anonymous) @279-303
- function_definition (anonymous) @307-331
- function_definition (anonymous) @335-342
- function_definition parse @346-373
- function_definition parse @377-393
- function_definition parseObject @397-403
- function_definition getBestPattern @447-465
- function_definition getAvailableLocales @568-575
- function_definition adoptCalendar @579-584
- function_definition setCalendar @587-594
- function_definition getCalendar @598-602
- function_definition adoptNumberFormat @606-613
- function_definition setNumberFormat @616-623
- function_definition getNumberFormat @627-631
- function_definition adoptTimeZone @635-641
- function_definition setTimeZone @644-650
- function_definition (anonymous) @654-663
- function_definition setLenient @667-676
- function_definition isLenient @680-691
- function_definition setCalendarLenient @693-699
- function_definition isCalendarLenient @703-711
- function_definition setContext @717-726
- function_definition getContext @732-741
- function_definition (anonymous) @747-758
- function_definition getBooleanAttribute @762-766

### intl/icu/source/i18n/dayperiodrules.cpp

Blob: `ea5e51eb9d519cc45d628157bb9bade93a0ab2d5`. Grammar: cpp. Status: contains-errors.

- include "dayperiodrules.h" @14
- include "unicode/ures.h" @16
- include "charstr.h" @17
- include "cstring.h" @18
- include "ucln_in.h" @19
- include "uhash.h" @20
- include "ulocimp.h" @21
- include "umutex.h" @22
- include "uresimp.h" @23
- function_definition namespace @26-46
- struct_specifier DayPeriodRulesData @30-36
- function_definition DayPeriodRulesData @31-31
- enum_specifier CutoffType @38-44
- struct_specifier DayPeriodRulesDataSink @48-281
- function_definition DayPeriodRulesDataSink @49-51
- function_definition put @54-80
- function_definition processRules @82-131
- function_definition parseSetNum @142-146
- function_definition parseSetNum @148-176
- function_definition addCutoff @178-190
- function_definition setDayPeriodForHoursFromCutoffs @193-226
- function_definition getCutoffTypeFromString @229-241
- function_definition parseHour @244-280
- struct_specifier DayPeriodRulesCountSink @283-297
- function_definition put @286-296
- function_definition ~DayPeriodRulesDataSink @300-300
- function_definition ~DayPeriodRulesCountSink @301-301
- function_definition dayPeriodRulesCleanup @307-313
- function_definition load @317-335
- function_definition getInstance @337-381
- function_definition DayPeriodRules @383-387
- function_definition getMidPointForDayPeriod @389-410
- function_definition getStartHourForDayPeriod @412-437
- function_definition getEndHourForDayPeriod @439-465
- function_definition getDayPeriodFromString @467-495
- function_definition add @497-502
- function_definition allHoursAreSet @504-510

### intl/icu/source/i18n/dayperiodrules.h

Blob: `4bfca762b8079b15ade638bb54dcf1230ec3abb2`. Grammar: cpp. Status: contains-errors.

- include "unicode/locid.h" @17
- include "unicode/unistr.h" @18
- include "unicode/uobject.h" @19
- include "unicode/utypes.h" @20
- include "resource.h" @21
- include "uhash.h" @22
- class_specifier DayPeriodRules @30-85
- enum_specifier DayPeriod @33-47
- function_definition hasMidnight @51-51
- function_definition hasNoon @52-52
- function_definition getDayPeriodForHour @53-53

### intl/icu/source/i18n/dcfmtsym.cpp

Blob: `b82a9587328cb3ae05ea433db8a09ab00736fc9f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @22
- include "unicode/dcfmtsym.h" @26
- include "unicode/ures.h" @27
- include "unicode/decimfmt.h" @28
- include "unicode/ucurr.h" @29
- include "unicode/choicfmt.h" @30
- include "unicode/unistr.h" @31
- include "unicode/numsys.h" @32
- include "unicode/unum.h" @33
- include "unicode/utf16.h" @34
- include "ucurrimp.h" @35
- include "cstring.h" @36
- include "locbased.h" @37
- include "uresimp.h" @38
- include "ureslocs.h" @39
- include "charstr.h" @40
- include "uassert.h" @41
- function_definition DecimalFormatSymbols @101-104
- function_definition DecimalFormatSymbols @109-112
- function_definition DecimalFormatSymbols @114-117
- function_definition DecimalFormatSymbols @119-125
- function_definition createWithLastResortData @127-135
- function_definition ~DecimalFormatSymbols @139-141
- function_definition DecimalFormatSymbols @146-150
- function_definition (anonymous) @155-177
- function_definition operator== @181-210
- struct_specifier DecFmtSymDataSink @223-281
- function_definition DecFmtSymDataSink @232-234
- function_definition put @237-255
- function_definition seenAll @258-265
- function_definition resolveMissingMonetarySeparators @269-280
- struct_specifier CurrencySpacingSink @283-345
- function_definition CurrencySpacingSink @288-289
- function_definition put @292-328
- function_definition resolveMissing @330-344
- function_definition ~DecFmtSymDataSink @348-348
- function_definition ~CurrencySpacingSink @349-349
- function_definition initialize @353-476
- function_definition initialize @478-520
- function_definition setCurrency @522-564
- function_definition getLocale @566-569
- function_definition (anonymous) @571-583
- function_definition setPatternForCurrencySpacing @585-594

### intl/icu/source/i18n/decContext.cpp

Blob: `bdc5f22fe5f7813282aa9c4443e8cdf31a894cb6`. Grammar: cpp. Status: contains-errors.

- include <string.h> @25
- include <stdio.h> @26
- include "decContext.h" @27
- include "decNumberLocal.h" @28
- function_definition * U_EXPORT2 uprv_decContextClearStatus(decContext *context, uInt mask) @47-50
- function_definition *  U_EXPORT2 uprv_decContextDefault(decContext *context, Int kind) @65-120
- function_definition uprv_decContextGetRounding @130-132
- function_definition uprv_decContextGetStatus @142-144
- function_definition * U_EXPORT2 uprv_decContextRestoreStatus(decContext *context,
                                    uInt newstatus, uInt mask) @158-163
- function_definition uprv_decContextSaveStatus @175-177
- function_definition * U_EXPORT2 uprv_decContextSetRounding(decContext *context,
                                  enum rounding newround) @188-192
- enum_specifier rounding @189-189
- function_definition *  U_EXPORT2 uprv_decContextSetStatus(decContext *context, uInt status) @204-209
- function_definition *  U_EXPORT2 uprv_decContextSetStatusFromString(decContext *context,
                                           const char *string) @225-260
- function_definition *  U_EXPORT2 uprv_decContextSetStatusFromStringQuiet(decContext *context,
                                                const char *string) @276-311
- function_definition *  U_EXPORT2 uprv_decContextSetStatusQuiet(decContext *context, uInt status) @322-324
- function_definition uprv_decContextStatusToString @334-358
- function_definition uprv_decContextTestEndian @373-389
- function_definition uprv_decContextTestSavedStatus @402-404
- function_definition uprv_decContextTestStatus @416-418
- function_definition * U_EXPORT2 uprv_decContextZeroStatus(decContext *context) @428-431

### intl/icu/source/i18n/decContext.h

Blob: `48324575e3c6c7904832c769f98d0f0a8285151f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @32
- include "putilimp.h" @33
- include <stdio.h> @63
- include <signal.h> @65
- enum_specifier rounding @79-89
- struct_specifier decContext @92-103
- enum_specifier rounding @96-96
- enum_specifier decClass @117-128
- enum_specifier rounding @261-261

### intl/icu/source/i18n/decNumber.cpp

Blob: `96ad3d7f986aed915f6ec8fd7196a52feda82150`. Grammar: cpp. Status: contains-errors.

- include <stdlib.h> @179
- include <string.h> @181
- include <ctype.h> @182
- include "cmemory.h" @183
- include "decNumber.h" @184
- include "decNumberLocal.h" @185
- include "uassert.h" @186
- function_definition uprv_decNumberFromInt32 @368-379
- function_definition uprv_decNumberFromUInt32 @381-391
- function_definition uprv_decNumberToInt32 @403-437
- function_definition uprv_decNumberToUInt32 @439-466
- function_definition uprv_decNumberToString @482-485
- function_definition uprv_decNumberToEngString @487-490
- function_definition uprv_decNumberFromString @512-742
- function_definition uprv_decNumberAbs @763-780
- function_definition uprv_decNumberAdd @795-804
- function_definition uprv_decNumberAnd @821-875
- function_definition uprv_decNumberCompare @889-895
- function_definition uprv_decNumberCompareSignal @909-915
- function_definition uprv_decNumberCompareTotal @930-936
- function_definition uprv_decNumberCompareTotalMag @951-1002
- function_definition uprv_decNumberDivide @1016-1025
- function_definition uprv_decNumberDivideInteger @1039-1045
- function_definition uprv_decNumberExp @1072-1110
- function_definition uprv_decNumberFMA @1128-1203
- function_definition uprv_decNumberInvert @1219-1262
- function_definition uprv_decNumberLn @1292-1332
- function_definition uprv_decNumberLogB @1358-1381
- function_definition uprv_decNumberLog10 @1418-1552
- function_definition uprv_decNumberMax @1569-1578
- function_definition uprv_decNumberMaxMag @1592-1601
- function_definition uprv_decNumberMin @1615-1624
- function_definition uprv_decNumberMinMag @1638-1647
- function_definition uprv_decNumberMinus @1663-1680
- function_definition uprv_decNumberNextMinus @1693-1716
- function_definition uprv_decNumberNextPlus @1729-1753
- function_definition uprv_decNumberNextToward @1769-1820
- function_definition uprv_decNumberOr @1837-1889
- function_definition uprv_decNumberPlus @1907-1923
- function_definition uprv_decNumberMultiply @1937-1946
- function_definition decExpOp @5265-5535
- function_definition decQuantizeOp @5876-6017
- function_definition decCompareOp @6049-6200
- function_definition decCompare @6214-6259
- function_definition decUnitCompare @6278-6333
- function_definition decUnitAddSub @6382-6619
- function_definition decTrim @6636-6695
- function_definition decReverse @6707-6714
- function_definition decShiftToMost @6729-6770
- function_definition decShiftToLeast @6785-6830
- function_definition decRoundOperand @6851-6872
- function_definition decCopyFit @6887-6892
- function_definition decSetCoeff @6933-7080
- function_definition decApplyRound @7114-7264
- function_definition decFinish @7283-7301
- function_definition ISZERO @7286-7290
- function_definition decFinalize @7318-7378
- function_definition decSetOverflow @7391-7427
- function_definition decSetMaxValue @7437-7452
- function_definition decSetSubnormal @7471-7537
- function_definition ISZERO @7490-7503
- function_definition decCheckMath @7557-7568
- function_definition decGetInt @7585-7660
- function_definition decDecap @7674-7693
- function_definition decBiStr @7710-7717
- function_definition decNaNs @7733-7767
- function_definition decStatus @7784-7794
- function_definition decGetDigits @7809-7844
- function_definition uprv_decNumberShow @7855-7897
- function_definition decDumpAr @7907-7935
- function_definition decCheckOperands @7952-7988
- function_definition decCheckNumber @7998-8089
- function_definition decCheckInexact @8099-8115
- function_definition decMalloc @8135-8150
- function_definition decFree @8164-8182

### intl/icu/source/i18n/decNumber.h

Blob: `4a1eb364e19d323d8cca662322c66f9a5c47b8b7`. Grammar: cpp. Status: contains-errors.

- include "decContext.h" @40
- struct_specifier decNumber @83-90
- enum_specifier decClass @167-167
- enum_specifier decClass @168-168

### intl/icu/source/i18n/decNumberLocal.h

Blob: `1c5a79b7021f0cf61e3918c356fd07220264d9f5`. Grammar: cpp. Status: syntax-clean.

- include <stdlib.h> @32
- include <string.h> @33
- include "decContext.h" @34
- struct_specifier bcdnum @284-290

### intl/icu/source/i18n/decimfmt.cpp

Blob: `0a05cdc8aac37a27ea7b51b05713ea95dbccba74`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include <cmath> @12
- include <cstdlib> @13
- include <stdlib.h> @14
- include "unicode/errorcode.h" @15
- include "unicode/decimfmt.h" @16
- include "number_decimalquantity.h" @17
- include "number_types.h" @18
- include "numparse_impl.h" @19
- include "number_mapper.h" @20
- include "number_patternstring.h" @21
- include "putilimp.h" @22
- include "number_utils.h" @23
- include "number_utypes.h" @24
- function_definition DecimalFormat @46-59
- function_definition DecimalFormat @61-66
- function_definition DecimalFormat @68-74
- function_definition DecimalFormat @76-101
- function_definition DecimalFormat @103-123
- function_definition setParseAllInput @127-131
- function_definition (anonymous) @135-268
- function_definition getAttribute @270-369
- function_definition setGroupingUsed @371-379
- function_definition setParseIntegerOnly @381-389
- function_definition setLenient @391-400
- function_definition DecimalFormat @402-409
- function_definition DecimalFormat @411-427
- function_definition DecimalFormat @429-452
- function_definition (anonymous) @454-478
- function_definition ~DecimalFormat @480-491
- function_definition clone @493-503
- function_definition operator== @505-516
- function_definition (anonymous) @518-534
- function_definition (anonymous) @536-557
- function_definition (anonymous) @559-581
- function_definition (anonymous) @583-585
- function_definition (anonymous) @587-590
- function_definition (anonymous) @592-596
- function_definition (anonymous) @598-614
- function_definition (anonymous) @616-637
- function_definition (anonymous) @639-661
- function_definition (anonymous) @663-682
- function_definition (anonymous) @684-702
- function_definition (anonymous) @704-723
- function_definition parse @725-758
- function_definition parseCurrency @760-796
- function_definition getDecimalFormatSymbols @798-807
- function_definition adoptDecimalFormatSymbols @809-820
- function_definition setDecimalFormatSymbols @822-837
- function_definition getCurrencyPluralInfo @839-844
- function_definition adoptCurrencyPluralInfo @846-855
- function_definition setCurrencyPluralInfo @857-868
- function_definition (anonymous) @870-879
- function_definition setPositivePrefix @881-888
- function_definition (anonymous) @890-899
- function_definition setNegativePrefix @901-908
- function_definition (anonymous) @910-919
- function_definition setPositiveSuffix @921-928
- function_definition (anonymous) @930-939
- function_definition setNegativeSuffix @941-948
- function_definition isSignAlwaysShown @950-956
- function_definition setSignAlwaysShown @958-963
- function_definition getMultiplier @965-981
- function_definition setMultiplier @983-1011
- function_definition getMultiplierScale @1013-1020
- function_definition setMultiplierScale @1022-1027
- function_definition getRoundingIncrement @1029-1036
- function_definition setRoundingIncrement @1038-1043
- function_definition getRoundingMode @1045-1053
- function_definition setRoundingMode @1055-1064
- function_definition getFormatWidth @1066-1073
- function_definition setFormatWidth @1075-1080
- function_definition getPadCharacterString @1082-1089
- function_definition setPadCharacter @1091-1100
- function_definition getPadPosition @1102-1109
- function_definition setPadPosition @1111-1119
- function_definition isScientificNotation @1121-1128
- function_definition setScientificNotation @1130-1140
- function_definition getMinimumExponentDigits @1142-1149
- function_definition setMinimumExponentDigits @1151-1156
- function_definition isExponentSignAlwaysShown @1158-1165
- function_definition setExponentSignAlwaysShown @1167-1172
- function_definition getGroupingSize @1174-1187
- function_definition setGroupingSize @1189-1194
- function_definition getSecondaryGroupingSize @1196-1209
- function_definition setSecondaryGroupingSize @1211-1216
- function_definition getMinimumGroupingDigits @1218-1225
- function_definition setMinimumGroupingDigits @1227-1232
- function_definition isDecimalSeparatorAlwaysShown @1234-1241
- function_definition setDecimalSeparatorAlwaysShown @1243-1248
- function_definition isDecimalPatternMatchRequired @1250-1257
- function_definition setDecimalPatternMatchRequired @1259-1264
- function_definition isParseNoExponent @1266-1273
- function_definition setParseNoExponent @1275-1280
- function_definition isParseCaseSensitive @1282-1289
- function_definition setParseCaseSensitive @1291-1296
- function_definition isFormatFailIfMoreThanMaxDigits @1298-1305
- function_definition setFormatFailIfMoreThanMaxDigits @1307-1312
- function_definition (anonymous) @1314-1342
- function_definition (anonymous) @1344-1354
- function_definition applyPattern @1356-1359
- function_definition applyPattern @1361-1371
- function_definition applyLocalizedPattern @1373-1377
- function_definition applyLocalizedPattern @1379-1390
- function_definition setMaximumIntegerDigits @1392-1402
- function_definition setMinimumIntegerDigits @1404-1414
- function_definition setMaximumFractionDigits @1416-1430
- function_definition setMinimumFractionDigits @1432-1442
- function_definition getMinimumSignificantDigits @1444-1451
- function_definition getMaximumSignificantDigits @1453-1460
- function_definition setMinimumSignificantDigits @1462-1471
- function_definition setMaximumSignificantDigits @1473-1482
- function_definition areSignificantDigitsUsed @1484-1494
- function_definition setSignificantDigitsUsed @1496-1516
- function_definition setCurrency @1518-1538
- function_definition setCurrency @1540-1543
- function_definition setCurrencyUsage @1545-1558
- function_definition getCurrencyUsage @1560-1567
- function_definition formatToDecimalQuantity @1569-1579
- function_definition formatToDecimalQuantity @1581-1594
- function_definition toNumberFormatter @1596-1605
- function_definition touch @1608-1661
- function_definition touchNoError @1663-1666
- function_definition setPropertiesFromPattern @1668-1675
- function_definition getParser @1677-1722
- function_definition getCurrencyParser @1724-1760
- function_definition fieldPositionHelper @1762-1777
- function_definition fieldPositionIteratorHelper @1779-1790
- function_definition setupFastFormat @1795-1865
- function_definition fastFormatDouble @1867-1879
- function_definition fastFormatInt64 @1881-1890
- function_definition doFastFormatInt32 @1892-1917

### intl/icu/source/i18n/displayoptions.cpp

Blob: `8c9dd1c478ac034f6a1c0cebc378954027b2f9fa`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/displayoptions.h" @8
- include "unicode/udisplayoptions.h" @9
- include "cstring.h" @10
- function_definition Builder DisplayOptions::builder @12-14
- function_definition copyToBuilder @16-16
- function_definition DisplayOptions @18-26
- function_definition Builder::Builder @28-37
- function_definition Builder::Builder @39-47
- function_definition U_NAMESPACE_USE @49-75
- function_definition udispopt_getGrammaticalCaseIdentifier @77-84
- function_definition udispopt_fromGrammaticalCaseIdentifier @86-95
- function_definition udispopt_getPluralCategoryIdentifier @111-118
- function_definition udispopt_fromPluralCategoryIdentifier @120-129
- function_definition udispopt_getNounClassIdentifier @147-154
- function_definition udispopt_fromNounClassIdentifier @156-165

### intl/icu/source/i18n/double-conversion-bignum-dtoa.cpp

Blob: `638e9cb0469750c87477d603c6b3e2b3341419ec`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <cmath> @37
- include "double-conversion-bignum-dtoa.h" @41
- include "double-conversion-bignum.h" @43
- include "double-conversion-ieee.h" @44
- function_definition double_conversion @47-655
- function_definition NormalizedExponent @51-58
- function_definition BignumDtoa @103-183
- function_definition GenerateShortestDigits @199-288
- function_definition GenerateCountedDigits @297-332
- function_definition BignumToFixed @340-381
- function_definition EstimatePower @399-427
- function_definition InitialScaledStartValuesPositiveExponent @431-460
- function_definition InitialScaledStartValuesNegativeExponentPositivePower @464-494
- function_definition InitialScaledStartValuesNegativeExponentNegativePower @498-541
- function_definition InitialScaledStartValues @582-612
- function_definition FixupMultiply10 @626-653

### intl/icu/source/i18n/double-conversion-bignum-dtoa.h

Blob: `edc21b0f2e4d5e2bdb75ef6c4738e66f452f70a2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-96
- enum_specifier BignumDtoaMode @49-62

### intl/icu/source/i18n/double-conversion-bignum.cpp

Blob: `d2b701a21d8220a0af03559b9a1c63ddeed6e330`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <algorithm> @37
- include <cstring> @38
- include "double-conversion-bignum.h" @42
- include "double-conversion-utils.h" @43
- function_definition double_conversion @46-811
- function_definition (anonymous) @50-53
- function_definition (anonymous) @56-59
- function_definition BitSize @63-66
- function_definition AssignUInt16 @69-76
- function_definition AssignUInt64 @79-86
- function_definition AssignBignum @89-95
- function_definition ReadUInt64 @98-108
- function_definition AssignDecimalString @111-129
- function_definition HexCharValue @132-141
- function_definition AssignHexString @146-167
- function_definition AddUInt64 @170-177
- function_definition AddBignum @180-223
- function_definition RawBigit @205-205
- function_definition SubtractBignum @226-250
- function_definition ShiftLeft @253-261
- function_definition MultiplyByUInt32 @264-290
- function_definition MultiplyByUInt64 @293-322
- function_definition MultiplyByPowerOfTen @325-366
- function_definition Square @369-438
- function_definition AssignPowerUInt16 @441-512
- function_definition DivideModuloIntBignum @516-579
- function_definition SizeInHexChars @583-591
- function_definition HexCharOfValue @594-600
- function_definition ToHexString @603-644
- function_definition BigitOrZero @647-655
- function_definition Compare @658-681
- function_definition PlusCompare @684-726
- function_definition Clamp @729-737
- function_definition Align @740-762
- function_definition RawBigit @754-754
- function_definition BigitsShiftLeft @765-778
- function_definition SubtractTimes @781-808

### intl/icu/source/i18n/double-conversion-bignum.h

Blob: `bae900a15a742052e9cbca406622d6e31725772b`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-164
- class_specifier Bignum @49-162
- function_definition Bignum @56-56
- function_definition Times10 @77-77
- function_definition Equal @91-93
- function_definition LessEqual @94-96
- function_definition Less @97-99
- function_definition PlusEqual @103-105
- function_definition PlusLessEqual @107-109
- function_definition PlusLess @111-113
- function_definition EnsureCapacity @128-132
- function_definition IsClamped @135-137
- function_definition Zero @138-141
- function_definition BigitLength @147-147

### intl/icu/source/i18n/double-conversion-cached-powers.cpp

Blob: `ad6ea927309903f5e1bc09e6a8ce7c1f9068fc5a`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <climits> @37
- include <cmath> @38
- include <cstdarg> @39
- include "double-conversion-utils.h" @43
- include "double-conversion-cached-powers.h" @45
- function_definition PowersOfTenCache @48-185
- struct_specifier CachedPower @52-56
- function_definition GetCachedPowerForBinaryExponentRange @151-168
- function_definition GetCachedPowerForDecimalExponent @171-183

### intl/icu/source/i18n/double-conversion-cached-powers.h

Blob: `78e70378d9ae2bf4407fc2734d9acd0fdba862a5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-diy-fp.h" @42
- function_definition PowersOfTenCache @45-72

### intl/icu/source/i18n/double-conversion-diy-fp.h

Blob: `5820abedf354051492252dda9dde2743c440eb96`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-149
- class_specifier DiyFp @55-147
- function_definition DiyFp @59-59
- function_definition DiyFp @60-60
- function_definition Subtract @66-70
- function_definition Minus @75-79
- function_definition Multiply @82-101
- function_definition Times @104-108
- function_definition Normalize @110-128
- function_definition Normalize @130-134
- function_definition f @136-136
- function_definition e @137-137
- function_definition set_f @139-139
- function_definition set_e @140-140

### intl/icu/source/i18n/double-conversion-double-to-string.cpp

Blob: `938484bca85189abbf6118b370aaedc524b18593`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <algorithm> @37
- include <climits> @38
- include <cmath> @39
- include "double-conversion-double-to-string.h" @44
- include "double-conversion-bignum-dtoa.h" @46
- include "double-conversion-fast-dtoa.h" @47
- include "double-conversion-ieee.h" @48
- include "double-conversion-utils.h" @49
- function_definition double_conversion @52-465
- function_definition (anonymous) @57-66
- function_definition HandleSpecialValues @69-87
- function_definition CreateExponentialRepresentation @90-138
- function_definition CreateDecimalRepresentation @141-186
- function_definition ToShortestIeeeNumber @189-224
- function_definition ToFixed @227-260
- function_definition ToExponential @263-315
- function_definition ToPrecision @318-384
- function_definition DtoaToBignumDtoaMode @388-399
- function_definition DoubleToAscii @402-463

### intl/icu/source/i18n/double-conversion-double-to-string.h

Blob: `b8cb06a8b2cef5cebd613cf39bc2838a813609da`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-487
- class_specifier DoubleToStringConverter @49-485
- enum_specifier Flags @90-99
- function_definition DoubleToStringConverter @180-204
- function_definition ToShortest @255-257
- function_definition ToShortestSingle @260-262
- enum_specifier DtoaMode @380-393

### intl/icu/source/i18n/double-conversion-fast-dtoa.cpp

Blob: `06e4cf12559da06694958735a7d4e9500d910902`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-fast-dtoa.h" @39
- include "double-conversion-cached-powers.h" @41
- include "double-conversion-diy-fp.h" @42
- include "double-conversion-ieee.h" @43
- function_definition double_conversion @46-679
- function_definition RoundWeed @75-180
- function_definition RoundWeedCounted @195-237
- function_definition BiggestPowerTen @254-270
- function_definition DigitGen @314-410
- function_definition DigitGenCounted @442-519
- function_definition Grisu3 @533-597
- function_definition Grisu3Counted @605-646
- function_definition FastDtoa @649-677

### intl/icu/source/i18n/double-conversion-fast-dtoa.h

Blob: `58a6470052c63c495c4a05627949dc88724b12fc`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-100
- enum_specifier FastDtoaMode @49-59

### intl/icu/source/i18n/double-conversion-ieee.h

Blob: `2940acb16981e856a558553b77b95127b0f420a9`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-diy-fp.h" @42
- function_definition double_conversion @45-459
- function_definition double_to_uint64 @50-50
- function_definition uint64_to_double @51-51
- function_definition float_to_uint32 @52-52
- function_definition uint32_to_float @53-53
- class_specifier Double @56-298
- function_definition Double @68-68
- function_definition Double @69-69
- function_definition Double @70-70
- function_definition Double @71-72
- function_definition AsDiyFp @76-80
- function_definition AsNormalizedDiyFp @83-97
- function_definition AsUint64 @100-102
- function_definition NextDouble @105-116
- function_definition PreviousDouble @118-126
- function_definition Exponent @128-135
- function_definition Significand @137-145
- function_definition IsDenormal @148-151
- function_definition IsSpecial @155-158
- function_definition IsNan @160-164
- function_definition IsQuietNan @166-172
- function_definition IsSignalingNan @174-180
- function_definition IsInfinite @183-187
- function_definition Sign @189-192
- function_definition UpperBoundary @196-199
- function_definition NormalizedBoundaries @205-219
- function_definition LowerBoundaryIsCloser @221-232
- function_definition value @234-234
- function_definition SignificandSizeForOrderOfMagnitude @242-248
- function_definition Infinity @250-252
- function_definition NaN @254-256
- function_definition DiyFpToUint64 @270-295
- class_specifier Single @300-457
- function_definition Single @310-310
- function_definition Single @311-311
- function_definition Single @312-312
- function_definition AsDiyFp @316-320
- function_definition AsUint32 @323-325
- function_definition Exponent @327-334
- function_definition Significand @336-344
- function_definition IsDenormal @347-350
- function_definition IsSpecial @354-357
- function_definition IsNan @359-363
- function_definition IsQuietNan @365-371
- function_definition IsSignalingNan @373-379
- function_definition IsInfinite @382-386
- function_definition Sign @388-391
- function_definition NormalizedBoundaries @397-411
- function_definition UpperBoundary @415-418
- function_definition LowerBoundaryIsCloser @420-431
- function_definition value @433-433
- function_definition Infinity @435-437
- function_definition NaN @439-441

### intl/icu/source/i18n/double-conversion-string-to-double.cpp

Blob: `0a33b91b7c90a4abd9471f76bf19392b787e6d22`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <climits> @39
- include <cmath> @41
- include "double-conversion-string-to-double.h" @45
- include "double-conversion-ieee.h" @47
- include "double-conversion-strtod.h" @48
- include "double-conversion-utils.h" @49
- function_definition ToLower @70-79
- function_definition Pass @81-83
- function_definition ConsumeSubStringImpl @86-99
- function_definition ConsumeSubString @104-113
- function_definition ConsumeFirstCharacter @116-120
- function_definition isWhitespace @144-155
- function_definition AdvanceToNonspace @160-166
- function_definition isDigit @169-173
- function_definition SignedZero @176-178
- function_definition IsDecimalDigitForRadix @189-191
- function_definition IsDecimalDigitForRadix @194-196
- function_definition IsCharacterDigitForRadix @205-207
- function_definition Advance @211-227
- function_definition IsHexFloatString @237-269
- function_definition RadixStringToIeee @277-437
- function_definition StringToIeee @440-767
- function_definition StringToDouble @770-775
- function_definition StringToDouble @778-783
- function_definition StringToFloat @786-792
- function_definition StringToFloat @795-801
- function_definition StringTo<double> @805-810
- function_definition StringTo<float> @814-819
- function_definition StringTo<double> @823-828
- function_definition StringTo<float> @832-837

### intl/icu/source/i18n/double-conversion-string-to-double.h

Blob: `1d4e3dddde9ca62ba913f4ffc051c1d6210ac848`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-250
- class_specifier StringToDoubleConverter @49-248
- enum_specifier Flags @53-64
- function_definition StringToDoubleConverter @181-193

### intl/icu/source/i18n/double-conversion-strtod.cpp

Blob: `eea8203281a26dbaa7fbb1eae51297e0561f8583`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <climits> @37
- include <cstdarg> @38
- include "double-conversion-bignum.h" @42
- include "double-conversion-cached-powers.h" @43
- include "double-conversion-ieee.h" @44
- include "double-conversion-strtod.h" @45
- function_definition double_conversion @48-624
- function_definition TrimLeadingZeros @109-116
- function_definition CutToMaxSignificantDigits @118-133
- function_definition TrimAndCut @140-157
- function_definition ReadUint64 @165-176
- function_definition ReadDiyFp @183-201
- function_definition DoubleStrtod @204-256
- function_definition AdjustmentPowerOfTen @261-278
- function_definition DiyFpStrtod @284-391
- function_definition CompareBufferWithDiyFp @402-428
- function_definition ComputeGuess @433-456
- function_definition IsDigit @459-461
- function_definition IsNonZeroDigit @463-465
- function_definition AssertTrimmedDigits @472-479
- function_definition StrtodTrimmed @482-502
- function_definition Strtod @504-511
- function_definition SanitizedDoubletof @513-535
- function_definition Strtof @537-545
- function_definition StrtofTrimmed @547-622

### intl/icu/source/i18n/double-conversion-strtod.h

Blob: `abfe00a333102ce0006819b2531552068c991404`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include "double-conversion-utils.h" @42
- function_definition double_conversion @45-76
- function_definition TrimTrailingZeros @67-74

### intl/icu/source/i18n/double-conversion-utils.h

Blob: `303668f9317994d42f6d1035315c40282f2cbcdd`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @34
- include <cstdlib> @43
- include <cstring> @44
- include "uassert.h" @54
- function_definition abort_noreturn @84-84
- include <stdint.h> @196
- function_definition double_conversion @250-429
- function_definition StrLength @254-258
- class_specifier Vector @262-305
- function_definition Vector @264-264
- function_definition Vector @265-267
- function_definition SubVector @271-276
- function_definition length @279-279
- function_definition is_empty @282-282
- function_definition start @285-285
- function_definition (anonymous) @288-291
- function_definition (anonymous) @293-293
- function_definition (anonymous) @295-295
- function_definition pop_back @297-300
- class_specifier StringBuilder @311-381
- function_definition StringBuilder @313-314
- function_definition ~StringBuilder @316-316
- function_definition size @318-318
- function_definition position @321-324
- function_definition Reset @327-327
- function_definition AddCharacter @332-336
- function_definition AddString @340-342
- function_definition AddSubstring @346-351
- function_definition AddPadding @356-360
- function_definition Finalize @363-372
- function_definition is_finalized @378-378
- function_definition BitCast @408-422
- function_definition BitCast @425-427

### intl/icu/source/i18n/double-conversion.h

Blob: `eddc38763becdc3547fb3eda47cf92a3943893f1`. Grammar: cpp. Status: syntax-clean.

- include "unicode/utypes.h" @34
- include "double-conversion-string-to-double.h" @42
- include "double-conversion-double-to-string.h" @43

### intl/icu/source/i18n/dt_impl.h

Blob: `a21b68ce1e2cf6c5a551917747d12523146826d4`. Grammar: cpp. Status: syntax-clean.

- include "unicode/unistr.h" @25

### intl/icu/source/i18n/dtfmtsym.cpp

Blob: `ed4cb07a36091c5b1f373d2f1c0a1d409d4926e1`. Grammar: cpp. Status: contains-errors.

- include <utility> @25
- include "unicode/utypes.h" @27
- include "unicode/ustring.h" @30
- include "unicode/localpointer.h" @31
- include "unicode/dtfmtsym.h" @32
- include "unicode/errorcode.h" @33
- include "unicode/smpdtfmt.h" @34
- include "unicode/msgfmt.h" @35
- include "unicode/numsys.h" @36
- include "unicode/tznames.h" @37
- include "cpputils.h" @38
- include "umutex.h" @39
- include "cmemory.h" @40
- include "cstring.h" @41
- include "charstr.h" @42
- include "erarules.h" @43
- include "dt_impl.h" @44
- include "locbased.h" @45
- include "gregoimp.h" @46
- include "hash.h" @47
- include "uassert.h" @48
- include "uresimp.h" @49
- include "ureslocs.h" @50
- include "uvector.h" @51
- include "shareddateformatsymbols.h" @52
- include "unicode/calendar.h" @53
- include "unifiedcache.h" @54
- enum_specifier LastResortSize @176-197
- function_definition ~SharedDateFormatSymbols @199-202
- function_definition createObject @204-225
- function_definition newUnicodeStringArray @271-273
- function_definition DateFormatSymbols @294-299
- function_definition DateFormatSymbols @301-305
- function_definition DateFormatSymbols @308-314
- function_definition DateFormatSymbols @316-320
- function_definition DateFormatSymbols @322-326
- function_definition assignArray @328-362
- function_definition createZoneStrings @369-398
- function_definition copyData @403-483
- function_definition (anonymous) @488-495
- function_definition ~DateFormatSymbols @497-500
- function_definition dispose @502-543
- function_definition disposeZoneStrings @545-564
- function_definition arrayCompare @566-578
- function_definition operator== @580-684
- function_definition getEras @688-693
- function_definition getEraNames @695-700
- function_definition getNarrowEras @702-707
- function_definition getMonths @709-714
- function_definition getShortMonths @716-721
- function_definition getMonths @723-771
- function_definition getWeekdays @773-778
- function_definition getShortWeekdays @780-785
- function_definition getWeekdays @787-840
- function_definition getQuarters @842-890
- function_definition (anonymous) @892-897
- function_definition getAmPmStrings @899-903
- function_definition getAmPmStrings @905-928
- function_definition getLeapMonthPatterns @930-935
- function_definition getYearNames @937-943
- function_definition setYearNames @945-955
- function_definition getZodiacNames @957-963
- function_definition setZodiacNames @965-975
- function_definition setEras @979-990
- function_definition setEraNames @992-1003
- function_definition setNarrowEras @1005-1016
- function_definition setMonths @1018-1029
- function_definition setShortMonths @1031-1042
- function_definition setMonths @1044-1103
- function_definition setWeekdays @1105-1115
- function_definition setShortWeekdays @1117-1128
- function_definition setWeekdays @1130-1201
- function_definition setQuarters @1203-1262
- function_definition setAmPmStrings @1264-1268
- function_definition setAmPmStrings @1270-1299
- function_definition setTimeSeparatorString @1301-1305
- function_definition getZoneStrings @1307-1327
- function_definition initZoneStringsArray @1333-1414
- function_definition setZoneStrings @1416-1427
- function_definition getPatternUChars @1431-1435
- function_definition getPatternCharIndex @1437-1444
- function_definition isNumericField @1474-1481
- function_definition isNumericPatternChar @1483-1486
- function_definition (anonymous) @1490-1495
- function_definition setLocalPatternChars @1499-1503
- struct_specifier CalendarDataSink @1543-1891
- enum_specifier AliasType @1546-1551
- function_definition CalendarDataSink @1578-1585
- function_definition visitAllResources @1589-1591
- function_definition preEnumerate @1594-1598
- function_definition put @1600-1721
- function_definition processResource @1724-1841
- function_definition processAliasFromValue @1844-1885
- function_definition deleteUnicodeStringArray @1888-1890
- function_definition ~CalendarDataSink @1893-1895
- function_definition initField @1900-1917
- function_definition initField @1919-1935
- function_definition initField @1937-1957
- function_definition initEras @1959-2002
- function_definition initLeapMonthPattern @2004-2022
- function_definition (anonymous) @2024-2027
- function_definition (anonymous) @2029-2034
- function_definition (anonymous) @2036-2041
- function_definition (anonymous) @2043-2048
- struct_specifier ContextUsageTypeNameToEnumValue @2050-2053
- function_definition loadDayPeriodStrings @2080-2110
- function_definition initializeData @2113-2642
- function_definition getLocale @2644-2647

### intl/icu/source/i18n/dtitv_impl.h

Blob: `41a6b306c95014d53f7d7214cf012e4b383750c6`. Grammar: cpp. Status: syntax-clean.

- include "unicode/unistr.h" @25

### intl/icu/source/i18n/dtitvfmt.cpp

Blob: `4d29275612947daa72b699b7641759d4aeffd5e0`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @13
- include "unicode/dtitvfmt.h" @15
- include "unicode/calendar.h" @22
- include "unicode/dtptngen.h" @23
- include "unicode/dtitvinf.h" @24
- include "unicode/simpleformatter.h" @25
- include "unicode/udisplaycontext.h" @26
- include "cmemory.h" @27
- include "cstring.h" @28
- include "dtitv_impl.h" @29
- include "mutex.h" @30
- include "uresimp.h" @31
- include "formattedval_impl.h" @32
- include <iostream> @35
- class_specifier FormattedDateIntervalData @70-74
- function_definition FormattedDateIntervalData @72-72
- function_definition ~FormattedDateIntervalData @76-76
- function_definition DateIntervalFormat @139-149
- function_definition DateIntervalFormat @152-164
- function_definition (anonymous) @167-212
- function_definition ~DateIntervalFormat @215-223
- function_definition clone @226-229
- function_definition operator== @232-263
- function_definition (anonymous) @266-284
- function_definition (anonymous) @287-306
- function_definition formatToValue @309-344
- function_definition (anonymous) @347-359
- function_definition formatToValue @362-395
- function_definition (anonymous) @398-414
- function_definition (anonymous) @418-542
- function_definition parseObject @546-553
- function_definition getDateIntervalInfo @558-561
- function_definition setDateIntervalInfo @564-584
- function_definition getDateFormat @588-591
- function_definition adoptTimeZone @594-610
- function_definition setTimeZone @612-626
- function_definition (anonymous) @628-637
- function_definition adoptCalendar @639-659
- function_definition setContext @661-671
- function_definition getContext @673-683
- function_definition DateIntervalFormat @685-716
- function_definition initializePattern @772-981
- function_definition normalizeHourMetacharacters @985-1073
- function_definition getDateTimeSkeleton @1076-1235
- function_definition setSeparateDateTimePtn @1262-1356
- function_definition setFallbackPattern @1360-1373
- function_definition setPatternInfo @1378-1402
- function_definition setIntervalPattern @1404-1409
- function_definition setIntervalPattern @1412-1446
- function_definition setIntervalPattern @1475-1550
- function_definition splitPatternInto2Part @1554-1625
- function_definition fallbackFormatRange @1628-1665
- function_definition (anonymous) @1668-1724
- function_definition fieldExistsInSkeleton @1729-1735
- function_definition adjustFieldWidth @1739-1879
- function_definition findReplaceInPattern @1881-1912
- function_definition concatSingleDate2TimeInterval @1916-1941

### intl/icu/source/i18n/dtitvinf.cpp

Blob: `26dd0a19945deef271e75374482f7ce5fa4f6322`. Grammar: cpp. Status: contains-errors.

- include "unicode/dtitvinf.h" @13
- include <iostream> @23
- include "cmemory.h" @26
- include "cstring.h" @27
- include "unicode/msgfmt.h" @28
- include "unicode/uloc.h" @29
- include "unicode/ures.h" @30
- include "dtitv_impl.h" @31
- include "charstr.h" @32
- include "hash.h" @33
- include "gregoimp.h" @34
- include "uresimp.h" @35
- include "hash.h" @36
- include "gregoimp.h" @37
- include "ulocimp.h" @38
- include "uresimp.h" @39
- function_definition DateIntervalInfo @66-72
- function_definition DateIntervalInfo @76-82
- function_definition setIntervalPattern @86-101
- function_definition setFallbackIntervalPattern @104-123
- function_definition DateIntervalInfo @127-132
- function_definition (anonymous) @136-153
- function_definition clone @156-159
- function_definition ~DateIntervalInfo @162-165
- function_definition operator== @168-179
- function_definition (anonymous) @182-203
- function_definition getDefaultOrder @206-209
- function_definition (anonymous) @212-216
- struct_specifier DateIntervalInfo::DateIntervalSink @231-383
- function_definition DateIntervalSink @239-240
- function_definition put @243-282
- function_definition processSkeletonTable @287-307
- function_definition getCalendarTypeFromPath @312-322
- function_definition validateAndProcessPatternLetter @327-352
- function_definition setIntervalPatternIfAbsent @358-374
- function_definition (anonymous) @376-378
- function_definition resetNextCalendarType @380-382
- function_definition DateIntervalSink::~DateIntervalSink @386-386
- function_definition initializeData @390-483
- function_definition setIntervalPatternInternally @485-509
- function_definition parseSkeleton @513-523
- function_definition stringNumeric @527-537
- function_definition getBestSkeleton @541-667
- function_definition calendarFieldToIntervalIndex @671-713
- function_definition deleteHash @717-731
- function_definition dtitvinfHashTableValueComparator @745-755
- function_definition initHash @757-776
- function_definition copyHash @779-809

### intl/icu/source/i18n/dtptngen.cpp

Blob: `62591588efb211fe6e9decfc4d516b2cb26d78b6`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @14
- include "unicode/datefmt.h" @17
- include "unicode/decimfmt.h" @18
- include "unicode/dtfmtsym.h" @19
- include "unicode/dtptngen.h" @20
- include "unicode/localpointer.h" @21
- include "unicode/simpleformatter.h" @22
- include "unicode/smpdtfmt.h" @23
- include "unicode/udat.h" @24
- include "unicode/udatpg.h" @25
- include "unicode/uniset.h" @26
- include "unicode/uloc.h" @27
- include "unicode/ures.h" @28
- include "unicode/ustring.h" @29
- include "unicode/rep.h" @30
- include "unicode/region.h" @31
- include "cpputils.h" @32
- include "mutex.h" @33
- include "umutex.h" @34
- include "cmemory.h" @35
- include "cstring.h" @36
- include "locbased.h" @37
- include "hash.h" @38
- include "uhash.h" @39
- include "ulocimp.h" @40
- include "uresimp.h" @41
- include "ulocimp.h" @42
- include "dtptngen_impl.h" @43
- include "ucln_in.h" @44
- include "charstr.h" @45
- include "uassert.h" @46
- include "unicode/ustring.h" @59
- include "uarrsort.h" @60
- struct_specifier UResAEntry @62-65
- struct_specifier UResourceBundleAIterator @67-72
- function_definition ures_a_codepointSort @76-83
- function_definition ures_a_open @85-107
- function_definition ures_a_close @109-116
- function_definition ures_a_getNextString @118-129
- function_definition DateTimePatternGenerator @335-348
- function_definition DateTimePatternGenerator @350-366
- function_definition DateTimePatternGenerator @368-383
- function_definition (anonymous) @385-428
- function_definition operator== @431-458
- function_definition operator!= @460-463
- function_definition ~DateTimePatternGenerator @465-472
- function_definition deleteAllowedHourFormats @480-482
- function_definition allowedHourFormatsCleanup @485-488
- enum_specifier AllowedHourFormat @490-503
- function_definition initData @507-529
- struct_specifier AllowedHourFormatsSink @533-615
- function_definition AllowedHourFormatsSink @535-535
- function_definition put @538-596
- function_definition getHourFormatFromUnicodeString @598-614
- function_definition ~AllowedHourFormatsSink @619-619
- function_definition loadAllowedHourFormatsData @621-641
- function_definition getAllowedHourFormatsLangCountry @643-656
- function_definition getAllowedHourFormats @658-738
- function_definition getDefaultHourCycle @740-763
- function_definition getSkeleton @765-773
- function_definition staticGetSkeleton @775-783
- function_definition getBaseSkeleton @785-792
- function_definition staticGetBaseSkeleton @794-802
- function_definition addICUPatterns @804-859
- function_definition hackTimes @861-905
- function_definition getCalendarTypeToUse @909-940
- function_definition consumeShortTimePattern @942-952
- struct_specifier DateTimePatternGenerator::AppendItemFormatsSink @954-981
- function_definition AppendItemFormatsSink @959-959
- function_definition put @962-970
- function_definition fillInMissing @972-980
- struct_specifier DateTimePatternGenerator::AppendItemNamesSink @983-1030
- function_definition AppendItemNamesSink @988-988
- function_definition put @991-1003
- function_definition fillInMissing @1005-1029
- struct_specifier DateTimePatternGenerator::AvailableFormatsSink @1032-1055
- function_definition AvailableFormatsSink @1040-1040
- function_definition put @1043-1054
- function_definition AppendItemFormatsSink::~AppendItemFormatsSink @1058-1058
- function_definition AppendItemNamesSink::~AppendItemNamesSink @1059-1059
- function_definition AvailableFormatsSink::~AvailableFormatsSink @1060-1060
- function_definition addCLDRData @1062-1109
- function_definition initHashtable @1111-1121
- function_definition setAppendItemFormat @1123-1128
- function_definition (anonymous) @1130-1133
- function_definition setAppendItemName @1135-1138
- function_definition (anonymous) @1140-1143
- function_definition setFieldDisplayName @1145-1150
- function_definition getFieldDisplayName @1152-1155
- function_definition (anonymous) @1157-1160
- function_definition getAppendName @1162-1167
- function_definition getBestPattern @1169-1172
- function_definition getBestPattern @1174-1246
- function_definition mapSkeletonMetacharacters @1255-1326
- function_definition replaceFieldTypes @1328-1333
- function_definition replaceFieldTypes @1335-1350
- function_definition setDecimal @1352-1357
- function_definition (anonymous) @1359-1362
- function_definition addCanonicalItems @1364-1375
- function_definition setDateTimeFormat @1377-1383
- function_definition (anonymous) @1385-1389
- function_definition setDateTimeFormat @1391-1405
- function_definition (anonymous) @1407-1418
- function_definition setDateTimeFromCalendar @1422-1492
- function_definition setDecimalSymbols @1494-1502
- function_definition addPattern @1504-1517
- function_definition addPatternWithSkeleton @1519-1528
- function_definition addPatternWithOptionalSkeleton @1540-1600
- function_definition getAppendFormatNumber @1603-1611
- function_definition getFieldAndWidthIndices @1613-1635
- function_definition getBestRaw @1637-1682
- function_definition adjustFieldTypes @1684-1804
- function_definition getBestAppending @1806-1861
- function_definition getTopBitNumber @1863-1878
- function_definition setAvailableFormat @1880-1884
- function_definition isAvailableFormatSet @1886-1889
- function_definition copyHashtable @1891-1915
- function_definition getSkeletons @1917-1930
- function_definition (anonymous) @1932-1947
- function_definition getBaseSkeletons @1949-1962
- function_definition getRedundants @1964-2004
- function_definition isCanonicalItem @2006-2017
- function_definition clone @2020-2023
- function_definition PatternMap @2025-2030
- function_definition copyFrom @2032-2071
- function_definition getHeader @2073-2089
- function_definition ~PatternMap @2091-2098
- function_definition add @2100-2176
- function_definition getPatternFromBasePattern @2179-2196
- function_definition getPatternFromSkeleton @2205-2236
- function_definition equals @2238-2272
- function_definition getDuplicateElem @2276-2308
- function_definition DateTimeMatcher @2310-2311
- function_definition ~DateTimeMatcher @2313-2313
- function_definition DateTimeMatcher @2315-2317
- function_definition (anonymous) @2319-2324
- function_definition set @2327-2331
- function_definition set @2333-2422
- function_definition getBasePattern @2424-2428
- function_definition getPattern @2430-2434
- function_definition getDistance @2436-2462
- function_definition copyFrom @2464-2467
- function_definition copyFrom @2469-2473
- function_definition equals @2475-2479
- function_definition getFieldMask @2481-2491
- function_definition getSkeletonPtr @2493-2496
- function_definition FormatParser @2498-2501
- function_definition ~FormatParser @2504-2505
- function_definition setTokens @2510-2534
- function_definition set @2536-2554
- function_definition getCanonicalIndex @2556-2588
- function_definition isQuoteLiteral @2590-2593
- function_definition getQuoteLiteral @2597-2625
- function_definition isPatternSeparator @2627-2640
- function_definition ~DistanceInfo @2642-2642
- function_definition setTo @2644-2648
- function_definition PatternMapIterator @2650-2655
- function_definition ~PatternMapIterator @2657-2658
- function_definition set @2660-2663
- function_definition getSkeleton @2665-2673
- function_definition hasNext @2675-2705
- function_definition (anonymous) @2707-2739
- function_definition SkeletonFields @2742-2745
- function_definition clear @2747-2750
- function_definition copyFrom @2752-2755
- function_definition clearField @2757-2760
- function_definition getFieldChar @2762-2764
- function_definition getFieldLength @2766-2768
- function_definition populate @2770-2772
- function_definition populate @2774-2777
- function_definition isFieldEmpty @2779-2781
- function_definition (anonymous) @2783-2788
- function_definition (anonymous) @2790-2798
- function_definition getFirstChar @2800-2807
- function_definition PtnSkeleton @2810-2812
- function_definition PtnSkeleton @2814-2816
- function_definition copyFrom @2818-2823
- function_definition clear @2825-2829
- function_definition equals @2831-2836
- function_definition getSkeleton @2838-2849
- function_definition getBaseSkeleton @2851-2862
- function_definition getFirstChar @2864-2867
- function_definition ~PtnSkeleton @2869-2870
- function_definition PtnElem @2872-2875
- function_definition ~PtnElem @2877-2878
- function_definition DTSkeletonEnumeration @2880-2926
- function_definition snext @2928-2934
- function_definition reset @2936-2939
- function_definition count @2941-2944
- function_definition isCanonicalItem @2946-2957
- function_definition ~DTSkeletonEnumeration @2959-2968
- function_definition DTRedundantEnumeration @2970-2971
- function_definition add @2973-2993
- function_definition snext @2995-3001
- function_definition reset @3003-3006
- function_definition count @3008-3011
- function_definition isCanonicalItem @3013-3024
- function_definition ~DTRedundantEnumeration @3026-3035

### intl/icu/source/i18n/dtptngen_impl.h

Blob: `b6eb5f63734ed1b36ca569df984441a685a7a080`. Grammar: cpp. Status: contains-errors.

- include "unicode/udatpg.h" @17
- include "unicode/strenum.h" @19
- include "unicode/unistr.h" @20
- include "uvector.h" @21
- enum_specifier dtStrEnum @107-111
- struct_specifier dtTypeElem @113-119
- class_specifier SkeletonFields @123-143
- function_definition operator== @145-148
- function_definition operator!= @150-152
- class_specifier PtnSkeleton @154-173
- class_specifier PtnElem @175-185
- class_specifier FormatParser @187-211
- function_definition getCanonicalIndex @198-198
- enum_specifier TokenStatus @202-207
- class_specifier DistanceInfo @213-224
- function_definition DistanceInfo @218-218
- function_definition clear @220-220
- function_definition addMissing @222-222
- function_definition addExtra @223-223
- class_specifier DateTimeMatcher @226-244
- class_specifier PatternMap @246-260
- class_specifier PatternMapIterator @262-275
- class_specifier DTSkeletonEnumeration @277-290
- class_specifier DTRedundantEnumeration @292-306

### intl/icu/source/i18n/dtrule.cpp

Blob: `7322cbfdad48f0acf8a0ff8038e7de74fa5be61a`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @10
- include "unicode/utypes.h" @12
- include "unicode/dtrule.h" @16
- function_definition DateTimeRule @22-28
- function_definition DateTimeRule @30-37
- function_definition DateTimeRule @39-53
- function_definition DateTimeRule @55-60
- function_definition ~DateTimeRule @62-63
- function_definition clone @65-68
- function_definition (anonymous) @70-82
- function_definition operator== @84-95
- function_definition operator!= @97-100
- function_definition getDateRuleType @102-105
- function_definition getTimeRuleType @107-110
- function_definition getRuleMonth @112-115
- function_definition getRuleDayOfMonth @117-120
- function_definition getRuleDayOfWeek @122-125
- function_definition getRuleWeekInMonth @127-130
- function_definition getRuleMillisInDay @132-135

### intl/icu/source/i18n/erarules.cpp

Blob: `6f1a379b28424375c3256d0cb7ed3b579f5b7076`. Grammar: cpp. Status: contains-errors.

- include <utility> @4
- include "unicode/utypes.h" @6
- include <stdlib.h> @10
- include "unicode/ucal.h" @11
- include "unicode/ures.h" @12
- include "unicode/ustring.h" @13
- include "unicode/timezone.h" @14
- include "cmemory.h" @15
- include "cstring.h" @16
- include "erarules.h" @17
- include "gregoimp.h" @18
- include "uassert.h" @19
- include "uvectr32.h" @20
- function_definition isSet @38-40
- function_definition isValidRuleStartDate @42-45
- function_definition encodeDate @57-59
- function_definition decodeDate @61-71
- function_definition compareEncodedDateWithYMD @82-104
- function_definition EraRules @106-110
- function_definition ~EraRules @112-113
- function_definition createInstance @115-265
- function_definition getStartDate @267-285
- function_definition getStartYear @287-308
- function_definition getEraCode @310-346
- function_definition initCurrentEra @348-373

### intl/icu/source/i18n/erarules.h

Blob: `f72f73c1c7f5d2c610cc6d4a37875dd8949184b7`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @7
- include "unicode/localpointer.h" @11
- include "unicode/uobject.h" @12
- include "cmemory.h" @13
- function_definition UMemory @15-91
- function_definition getNumberOfEras @29-31
- function_definition getMaxEraCode @37-39
- function_definition getCurrentEraCode @77-79

### intl/icu/source/i18n/esctrn.cpp

Blob: `60f8731101d8fa5078888ea224656a400e03e450`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/utf16.h" @17
- include "esctrn.h" @18
- include "util.h" @19
- function_definition _createEscUnicode @37-40
- function_definition _createEscJava @41-44
- function_definition _createEscC @45-49
- function_definition _createEscXML @50-53
- function_definition _createEscXML10 @54-57
- function_definition _createEscPerl @58-61
- function_definition registerIDs @67-83
- function_definition EscapeTransliterator @89-102
- function_definition EscapeTransliterator @107-116
- function_definition ~EscapeTransliterator @118-120
- function_definition clone @125-127
- function_definition handleTransliterate @132-175

### intl/icu/source/i18n/esctrn.h

Blob: `a4282ea86a2c511a225761936a05e2f23dc2c342`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @15
- include "unicode/translit.h" @19
- function_definition Transliterator @21-138

### intl/icu/source/i18n/ethpccal.cpp

Blob: `a459b578dcfa7cc10c30f0b15e9059419b291c74`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "gregoimp.h" @14
- include "umutex.h" @15
- include "ethpccal.h" @16
- include "cecal.h" @17
- include <float.h> @18
- function_definition EthiopicCalendar @33-37
- function_definition ~EthiopicCalendar @39-41
- function_definition clone @43-47
- function_definition getType @49-53
- function_definition handleGetExtendedYear @59-80
- function_definition getJDEpochOffset @84-88
- function_definition extendedYearToEra @90-92
- function_definition extendedYearToYear @94-96
- function_definition getRelatedYearDifference @98-101
- function_definition EthiopicAmeteAlemCalendar @107-111
- function_definition ~EthiopicAmeteAlemCalendar @113-115
- function_definition clone @117-121
- function_definition getType @127-131
- function_definition handleGetExtendedYear @133-146
- function_definition getJDEpochOffset @148-152
- function_definition extendedYearToEra @154-156
- function_definition extendedYearToYear @158-160
- function_definition handleGetLimit @163-170

### intl/icu/source/i18n/ethpccal.h

Blob: `0912b1377f239ab22cd2fac9d12d326e9345fadb`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/calendar.h" @17
- include "cecal.h" @18
- function_definition CECalendar @20-231
- enum_specifier EMonths @33-98
- enum_specifier EEras @100-103
- function_definition EthiopicCalendar @122-122
- class_specifier EthiopicAmeteAlemCalendar @237-341
- function_definition EthiopicAmeteAlemCalendar @255-255

### intl/icu/source/i18n/fmtable.cpp

Blob: `41fda1fd2ff93dadaf9c74d2e8d95be10decb72d`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @18
- include <cstdlib> @22
- include <math.h> @23
- include "unicode/fmtable.h" @24
- include "unicode/ustring.h" @25
- include "unicode/measure.h" @26
- include "unicode/curramt.h" @27
- include "unicode/uformattable.h" @28
- include "cmemory.h" @29
- include "cstring.h" @30
- include "fixedstring.h" @31
- include "fmtableimp.h" @32
- include "number_decimalquantity.h" @33
- function_definition objectEquals @57-60
- function_definition objectClone @63-66
- function_definition instanceOfMeasure @69-71
- function_definition createArrayCopy @80-87
- function_definition setError @94-98
- function_definition init @104-110
- function_definition Formattable @116-118
- function_definition Formattable @123-128
- function_definition Formattable @133-138
- function_definition Formattable @143-147
- function_definition Formattable @152-157
- function_definition Formattable @162-165
- function_definition Formattable @171-176
- function_definition Formattable @182-187
- function_definition Formattable @189-194
- function_definition Formattable @198-205
- function_definition Formattable @211-216
- function_definition (anonymous) @221-269
- function_definition operator== @273-323
- function_definition ~Formattable @327-330
- function_definition dispose @334-359
- function_definition clone @361-364
- function_definition getType @368-372
- function_definition isNumeric @374-384
- function_definition getLong @387-433
- function_definition getInt64 @442-485
- function_definition getDouble @488-516
- function_definition getObject @518-521
- function_definition setDouble @526-532
- function_definition setLong @537-543
- function_definition setInt64 @548-554
- function_definition setDate @559-565
- function_definition setString @570-576
- function_definition setArray @581-588
- function_definition adoptString @593-599
- function_definition adoptArray @604-611
- function_definition adoptObject @613-618
- function_definition (anonymous) @621-635
- function_definition (anonymous) @638-650
- function_definition (anonymous) @653-665
- function_definition getArray @668-678
- function_definition getBogus @683-687
- function_definition getDecimalNumber @691-705
- function_definition internalGetFixedString @707-748
- function_definition populateDecimalQuantity @750-772
- function_definition adoptDecimalQuantity @775-796
- function_definition setDecimalNumber @800-813
- include <iostream> @821
- include "unicode/datefmt.h" @824
- include "unistrm.h" @825
- class_specifier FormattableStreamer @827-833
- function_definition FormattableStreamer @832-832
- function_definition streamOut @838-884
- function_definition ufmt_open @889-906
- function_definition ufmt_close @908-913
- function_definition ufmt_getType @915-922
- function_definition ufmt_isNumeric @925-929
- function_definition ufmt_getDate @931-936
- function_definition ufmt_getDouble @938-943
- function_definition ufmt_getLong @945-950
- function_definition ufmt_getObject @953-964
- function_definition ufmt_getUChars @966-984
- function_definition ufmt_getArrayLength @986-993
- function_definition * U_EXPORT2
ufmt_getArrayItemByIndex(UFormattable* fmt, int32_t n, UErrorCode *status) @995-1008
- function_definition ufmt_getDecNumChars @1010-1029
- function_definition ufmt_getInt64 @1031-1035

### intl/icu/source/i18n/fmtable_cnv.cpp

Blob: `bc3847b6963e705aadbf5b4f7031cd03d1cf3455`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @18
- include "unicode/fmtable.h" @22
- function_definition Formattable @28-38

### intl/icu/source/i18n/fmtableimp.h

Blob: `2707d6ece2e2ebdbe4d82b97dc93a3753da2635b`. Grammar: cpp. Status: contains-errors.

- include "number_decimalquantity.h" @13

### intl/icu/source/i18n/format.cpp

Blob: `07919d20f61ef44c99b3efa36308060865a1ae0c`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @24
- include "unicode/utypes.h" @26
- function_definition uprv_icuin_lib_dummy @39-42
- include "unicode/format.h" @49
- include "unicode/ures.h" @50
- include "cstring.h" @51
- include "locbased.h" @52
- function_definition ~FieldPosition @62-62
- function_definition clone @64-67
- function_definition Format @72-75
- function_definition ~Format @79-81
- function_definition Format @86-90
- function_definition (anonymous) @95-103
- function_definition (anonymous) @109-119
- function_definition (anonymous) @125-135
- function_definition parseObject @141-153
- function_definition operator== @157-162
- function_definition syntaxError @173-194
- function_definition getLocale @196-199
- function_definition getLocaleID @201-204
- function_definition setLocaleIDs @206-210

### intl/icu/source/i18n/formatted_string_builder.cpp

Blob: `94082dc379f2311068bb2fcd56abde195e1bd73c`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "formatted_string_builder.h" @8
- include "putilimp.h" @9
- include "unicode/ustring.h" @10
- include "unicode/utf16.h" @11
- include "unicode/unum.h" @12
- function_definition uprv_memcpy2 @18-22
- function_definition uprv_memmove2 @26-30
- function_definition FormattedStringBuilder @35-45
- function_definition ~FormattedStringBuilder @47-52
- function_definition FormattedStringBuilder @54-56
- function_definition (anonymous) @58-98
- function_definition length @100-102
- function_definition codePointCount @104-106
- function_definition getFirstCodePoint @108-115
- function_definition getLastCodePoint @117-126
- function_definition codePointAt @128-132
- function_definition codePointBefore @134-140
- function_definition (anonymous) @142-147
- function_definition insertCodePoint @149-167
- function_definition insert @169-180
- function_definition insert @182-195
- function_definition splice @197-222
- function_definition append @224-226
- function_definition insert @228-251
- function_definition writeTerminator @253-261
- function_definition prepareForInsert @263-286
- function_definition prepareForInsertHelper @288-361
- function_definition remove @363-379
- function_definition toUnicodeString @381-383
- function_definition toTempUnicodeString @385-388
- function_definition toDebugString @390-445
- function_definition chars @447-449
- function_definition contentEquals @451-461
- function_definition containsField @463-470

### intl/icu/source/i18n/formatted_string_builder.h

Blob: `2ea7ac4f1b0ad1942fa4c17bed0445d5588a8781`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include <cstdint> @11
- include <type_traits> @12
- include "cstring.h" @14
- include "uassert.h" @15
- include "fphdlimp.h" @16
- function_definition FormattedStringBuilder @35-218
- class_specifier U_I18N_API @35-35
- struct_specifier heap @42-45
- function_definition Field @59-71
- struct_specifier U_I18N_API @59-59
- function_definition Field @62-62
- function_definition charAt @79-83
- function_definition fieldAt @85-89
- function_definition appendChar16 @102-105
- function_definition insertChar16 @108-111
- function_definition appendCodePoint @114-116
- function_definition append @122-124
- function_definition getCharPtr @191-193
- function_definition getCharPtr @195-197
- function_definition getFieldPtr @199-201
- function_definition getFieldPtr @203-205
- function_definition getCapacity @207-209
- function_definition Field::Field @226-231
- function_definition Field::getCategory @243-245
- function_definition Field::getField @247-249
- function_definition Field::isNumeric @251-253
- function_definition Field::isUndefined @255-257
- function_definition Field::operator== @259-261
- function_definition Field::operator!= @263-265

### intl/icu/source/i18n/formattedval_impl.h

Blob: `6b18d25787646688a1de96f21370e9d9d800057c`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @7
- include "unicode/formattedvalue.h" @16
- include "capi_helper.h" @17
- include "fphdlimp.h" @18
- include "util.h" @19
- include "uvectr32.h" @20
- include "formatted_string_builder.h" @21
- enum_specifier UCFPosConstraintType @31-64
- function_definition SpanInfo @121-126
- struct_specifier U_I18N_API @121-121
- class_specifier U_I18N_API_CLASS @137-137
- function_definition FormattedValueStringBuilderImpl @143-143
- function_definition (anonymous) @156-158
- function_definition (anonymous) @159-161
- struct_specifier UFormattedValueImpl @191-191
- struct_specifier UFormattedValueImpl @193-196

### intl/icu/source/i18n/formattedval_iterimpl.cpp

Blob: `ec770e2191d6157e3499ead4e5dab7df00064a26`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "formattedval_impl.h" @12
- include "putilimp.h" @13
- function_definition ~FormattedValueFieldPositionIteratorImpl @24-24
- function_definition toString @26-29
- function_definition toTempString @31-36
- function_definition (anonymous) @38-43
- function_definition nextPosition @45-63
- function_definition getHandler @66-69
- function_definition appendString @71-83
- function_definition addOverlapSpans @86-123
- function_definition sort @126-171

### intl/icu/source/i18n/formattedval_sbimpl.cpp

Blob: `72197cdd8c7abf71b9cf3b3faaac979d589779b2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/ustring.h" @12
- include "formattedval_impl.h" @13
- include "number_types.h" @14
- include "formatted_string_builder.h" @15
- include "number_utils.h" @16
- include "static_unicode_sets.h" @17
- include "unicode/listformatter.h" @18
- function_definition FormattedValueStringBuilderImpl @26-28
- function_definition ~FormattedValueStringBuilderImpl @30-31
- function_definition toString @34-36
- function_definition toTempString @38-40
- function_definition (anonymous) @42-45
- function_definition nextPosition @47-50
- function_definition nextFieldPosition @52-89
- function_definition getAllFieldPositions @91-97
- function_definition resetString @99-102
- function_definition nextPositionImpl @108-292
- function_definition appendSpanInfo @294-305
- function_definition prependSpanInfo @307-321
- function_definition isIntOrGroup @323-326
- function_definition isTrimmable @328-331
- function_definition trimBack @333-338
- function_definition trimFront @340-345

### intl/icu/source/i18n/formattedvalue.cpp

Blob: `f2bfdda6e465f290fac201404bf0c5b1b7662f53`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/formattedvalue.h" @8
- include "formattedval_impl.h" @9
- include "capi_helper.h" @10
- function_definition ConstrainedFieldPosition @12-15
- function_definition ~ConstrainedFieldPosition @17-17
- function_definition reset @19-26
- function_definition constrainCategory @28-31
- function_definition constrainField @33-37
- function_definition setInt64IterationContext @39-41
- function_definition matchesField @43-54
- function_definition setState @56-65
- function_definition ~FormattedValue @68-68
- struct_specifier UConstrainedFieldPositionImpl @75-79
- function_definition * U_EXPORT2
ucfpos_open(UErrorCode* ec) @81-89
- function_definition ucfpos_reset @91-98
- function_definition ucfpos_constrainCategory @100-107
- function_definition ucfpos_constrainField @109-116
- function_definition ucfpos_getCategory @118-125
- function_definition ucfpos_getField @127-134
- function_definition ucfpos_getIndexes @136-144
- function_definition ucfpos_getInt64IterationContext @146-153
- function_definition ucfpos_setInt64IterationContext @155-162
- function_definition ucfpos_matchesField @164-171
- function_definition ucfpos_setState @173-186
- function_definition ucfpos_close @188-193
- function_definition ufmtval_getString @201-220
- function_definition ufmtval_nextPosition @226-237

### intl/icu/source/i18n/fphdlimp.cpp

Blob: `e170dc4b992c8c76f7416be26493425b71886b29`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "fphdlimp.h" @14
- include "uvectr32.h" @15
- function_definition ~FieldPositionHandler @17-23
- function_definition setShift @25-27
- function_definition FieldPositionOnlyHandler @32-34
- function_definition ~FieldPositionOnlyHandler @36-37
- function_definition addAttribute @39-46
- function_definition shiftLast @48-54
- function_definition isRecording @56-59
- function_definition setAcceptFirstOnly @61-63
- function_definition FieldPositionIteratorHandler @68-74
- function_definition FieldPositionIteratorHandler @76-80
- function_definition ~FieldPositionIteratorHandler @82-89
- function_definition addAttribute @91-103
- function_definition shiftLast @105-116
- function_definition isRecording @118-121

### intl/icu/source/i18n/fphdlimp.h

Blob: `9cad36ac86b159f86b5da277b028ff7310b76656`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/fieldpos.h" @17
- include "unicode/fpositer.h" @18
- include "unicode/formattedvalue.h" @19
- function_definition UMemory @21-37
- class_specifier FieldPositionOnlyHandler @42-61
- function_definition FieldPositionIteratorHandler @67-101
- class_specifier U_I18N_API @67-67
- function_definition getError @92-96
- function_definition setCategory @98-100

### intl/icu/source/i18n/fpositer.cpp

Blob: `68f1edcc174a839bc8e97b0ffe73a74f9ff5681b`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/fpositer.h" @17
- include "cmemory.h" @18
- include "uvectr32.h" @19
- function_definition ~FieldPositionIterator @21-27
- function_definition FieldPositionIterator @29-31
- function_definition FieldPositionIterator @33-46
- function_definition operator== @48-59
- function_definition setData @61-91
- function_definition next @93-109

### intl/icu/source/i18n/funcrepl.cpp

Blob: `f093a1e437988e1798b4efadf7f02ace234103f7`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @13
- include "unicode/translit.h" @17
- include "unicode/uniset.h" @18
- include "funcrepl.h" @19
- function_definition FunctionReplacer @34-38
- function_definition FunctionReplacer @43-49
- function_definition ~FunctionReplacer @54-57
- function_definition clone @62-64
- function_definition toReplacer @70-75
- function_definition replace @80-94
- function_definition (anonymous) @99-109
- function_definition addReplacementSetTo @114-117
- function_definition setData @122-124

### intl/icu/source/i18n/funcrepl.h

Blob: `529a10ebbf5377fc1ba3e0e57dc70d847b1cf879`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include "unicode/unifunct.h" @20
- include "unicode/unirepl.h" @21
- class_specifier FunctionReplacer @35-114

### intl/icu/source/i18n/gender.cpp

Blob: `6e9d8d2ac03604e101ff44ba07998e77ba5289df`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @18
- include <utility> @22
- include "unicode/gender.h" @24
- include "unicode/ugender.h" @25
- include "unicode/ures.h" @26
- include "charstr.h" @28
- include "cmemory.h" @29
- include "cstring.h" @30
- include "mutex.h" @31
- include "uassert.h" @32
- include "ucln_in.h" @33
- include "ulocimp.h" @34
- include "umutex.h" @35
- include "uhash.h" @36
- enum_specifier GenderStyle @46-51
- function_definition gender_cleanup @53-63
- function_definition GenderInfo_initCache @65-89
- function_definition GenderInfo @92-93
- function_definition ~GenderInfo @95-96
- function_definition getInstance @98-137
- function_definition loadInstance @139-183
- function_definition getListGender @185-236
- function_definition getNeutralInstance @238-240
- function_definition getMixedNeutralInstance @242-244
- function_definition getMaleTaintsInstance @246-248
- function_definition ugender_getInstance @250-255
- function_definition ugender_getListGender @257-260

### intl/icu/source/i18n/gregocal.cpp

Blob: `3dc3950e274f795cffa4e57274368beac630a4b5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @42
- include <float.h> @43
- include "unicode/gregocal.h" @47
- include "gregoimp.h" @48
- include "umutex.h" @49
- include "uassert.h" @50
- include <stdio.h> @136
- function_definition GregorianCalendar @156-163
- function_definition GregorianCalendar @167-170
- function_definition GregorianCalendar @174-177
- function_definition GregorianCalendar @181-184
- function_definition GregorianCalendar @188-196
- function_definition GregorianCalendar @200-208
- function_definition GregorianCalendar @212-223
- function_definition GregorianCalendar @227-233
- function_definition GregorianCalendar @237-243
- function_definition ~GregorianCalendar @247-249
- function_definition GregorianCalendar @253-259
- function_definition clone @263-266
- function_definition (anonymous) @270-281
- function_definition isEquivalentTo @285-290
- function_definition setGregorianChange @294-339
- function_definition handleComputeFields @341-420
- function_definition getGregorianChange @425-429
- function_definition isLeapYear @433-441
- function_definition handleComputeJulianDay @445-507
- function_definition handleComputeMonthStart @509-562
- function_definition handleGetMonthLength @564-573
- function_definition handleGetYearLength @575-578
- function_definition monthLength @581-586
- function_definition monthLength @590-594
- function_definition yearLength @598-602
- function_definition validateFields @606-645
- function_definition boundsCheck @649-653
- function_definition getEpochDay @657-666
- function_definition computeJulianDayOfYear @679-693
- function_definition millisToJulianDay @750-754
- function_definition julianDayToMillis @758-762
- function_definition aggregateStamp @766-772
- function_definition roll @781-784
- function_definition roll @786-1018
- function_definition getActualMinimum @1030-1033
- function_definition getActualMinimum @1035-1038
- function_definition getActualMinimum @1047-1050
- function_definition handleGetLimit @1062-1064
- function_definition getActualMaximum @1073-1152
- function_definition handleGetExtendedYear @1155-1207
- function_definition handleGetExtendedYearFromWeekFields @1209-1220
- function_definition internalGetEra @1229-1232
- function_definition getType @1234-1239

### intl/icu/source/i18n/gregoimp.cpp

Blob: `5253c9ed0bd0f95a36dde91537b9ffc7e72dc38f`. Grammar: cpp. Status: contains-errors.

- include "gregoimp.h" @14
- include "unicode/ucal.h" @18
- include "uresimp.h" @19
- include "cstring.h" @20
- include "uassert.h" @21
- function_definition floorDivide @23-28
- function_definition floorDivideInt64 @30-33
- function_definition floorDivide @35-42
- function_definition floorDivide @44-57
- function_definition floorDivide @59-94
- function_definition fieldsToDay @107-119
- function_definition dayToFields @121-145
- function_definition dayToYear @147-150
- function_definition dayToYear @152-178
- function_definition timeToFields @180-184
- function_definition timeToFields @186-190
- function_definition timeToFields @192-201
- function_definition timeToYear @203-211
- function_definition dayOfWeek @213-217
- function_definition dayOfWeekInMonth @219-229

### intl/icu/source/i18n/gregoimp.h

Blob: `1b656d64271dac204e82e196ae3532465a4d50e6`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include "unicode/calendar.h" @17
- include "unicode/ures.h" @20
- include "unicode/locid.h" @21
- include "putilimp.h" @22
- function_definition ClockMath @24-114
- class_specifier Grego @167-325
- function_definition floorDivide @327-329
- function_definition isLeapYear @331-334
- function_definition monthLength @336-339
- function_definition previousMonthLength @341-344
- function_definition julianDayToMillis @346-349
- function_definition millisToJulianDay @351-353
- function_definition gregorianShift @355-359
- function_definition defaultCenturyStart @389-393
- function_definition defaultCenturyStartYear @394-398
- function_definition haveDefaultCentury @399-399

### intl/icu/source/i18n/hebrwcal.cpp

Blob: `83f1707990354b30b5a1d59994f7cfc92ad26812`. Grammar: cpp. Status: contains-errors.

- include "hebrwcal.h" @18
- include "cmemory.h" @22
- include "cstring.h" @23
- include "umutex.h" @24
- include <float.h> @25
- include "gregoimp.h" @26
- include "astro.h" @27
- include "uhash.h" @28
- include "ucln_in.h" @29
- function_definition calendar_hebrew_cleanup @145-150
- function_definition Calendar @151-167
- function_definition ~HebrewCalendar @170-171
- function_definition getType @173-175
- function_definition clone @177-179
- function_definition HebrewCalendar @181-182
- function_definition add @219-296
- function_definition add @301-304
- function_definition roll @344-377
- function_definition roll @379-381
- function_definition startOfYear @426-470
- function_definition daysInYear @472-477
- function_definition yearType @485-513
- function_definition isLeapYear @523-527
- function_definition monthsInYear @531-533
- function_definition handleGetLimit @544-546
- function_definition handleGetMonthLength @552-586
- function_definition handleGetYearLength @592-594
- function_definition validateField @596-606
- function_definition handleComputeFields @632-712
- function_definition handleGetExtendedYear @721-729
- function_definition handleComputeMonthStart @735-791
- function_definition inTemporalLeapYear @795-804
- function_definition getTemporalMonthCode @811-817
- function_definition setTemporalMonthCode @819-834
- function_definition internalGetMonth @836-856
- function_definition getRelatedYearDifference @858-861

### intl/icu/source/i18n/hebrwcal.h

Blob: `a959ac307b37579f17b4070ead077c08c8e85753`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @22
- include "unicode/calendar.h" @26
- include "unicode/gregocal.h" @27
- function_definition Calendar @29-421
- enum_specifier Month @91-156

### intl/icu/source/i18n/indiancal.cpp

Blob: `8c8365b0b304a2103d2298e157826c062a22987e`. Grammar: cpp. Status: contains-errors.

- include "indiancal.h" @12
- include <stdlib.h> @13
- include "mutex.h" @16
- include <float.h> @17
- include "gregoimp.h" @18
- include "uhash.h" @19
- include <stdio.h> @23
- include <stdarg.h> @24
- function_definition clone @28-39
- function_definition IndianCalendar @41-44
- function_definition IndianCalendar @46-47
- function_definition ~IndianCalendar @49-51
- function_definition getType @52-54
- function_definition handleGetLimit @88-90
- function_definition isGregorianLeap @95-98
- function_definition handleGetMonthLength @110-124
- function_definition handleGetYearLength @131-134
- function_definition gregorianToJD @142-144
- function_definition IndianToJD @150-187
- function_definition handleComputeMonthStart @194-219
- function_definition handleGetExtendedYear @225-238
- function_definition handleComputeFields @254-296
- function_definition getRelatedYearDifference @302-305

### intl/icu/source/i18n/indiancal.h

Blob: `411abc638afc23f5006b1a05316f2a307bb60a42`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include "unicode/calendar.h" @20
- enum_specifier EEras @77-137

### intl/icu/source/i18n/inputext.cpp

Blob: `4a7712404ca315f12d8780100a4cc4b75347f8fe`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @10
- include "inputext.h" @14
- include "cmemory.h" @16
- include "cstring.h" @17
- include <string.h> @19
- function_definition InputText @28-40
- function_definition ~InputText @42-47
- function_definition setText @49-55
- function_definition setDeclaredEncoding @57-69
- function_definition isSet @71-74
- function_definition MungeInput @82-160

### intl/icu/source/i18n/inputext.h

Blob: `fb92dc06343afa2694dd80ec499603985d1fe310`. Grammar: cpp. Status: contains-errors.

- include "unicode/uobject.h" @22
- function_definition UMemory @26-58

### intl/icu/source/i18n/islamcal.cpp

Blob: `e847ac28c894cca1ba0ef3e14765d5f8edb7666a`. Grammar: cpp. Status: contains-errors.

- include "islamcal.h" @18
- include "umutex.h" @22
- include <float.h> @23
- include "gregoimp.h" @24
- include "astro.h" @25
- include "uhash.h" @26
- include "ucln_in.h" @27
- include "uassert.h" @28
- include <stdio.h> @34
- include <stdarg.h> @35
- function_definition debug_islamcal_loc @36-39
- function_definition debug_islamcal_msg @41-47
- function_definition calendar_islamic_cleanup @59-66
- function_definition getType @194-196
- function_definition clone @198-200
- function_definition IslamicCalendar @202-205
- function_definition ~IslamicCalendar @207-209
- function_definition handleGetLimit @253-255
- function_definition civilLeapYear @301-303
- function_definition yearStart @313-315
- function_definition monthStart @324-337
- function_definition trueMonthStart @359-396
- function_definition moonAge @398-406
- function_definition handleGetMonthLength @420-428
- function_definition yearLength @432-439
- function_definition handleGetYearLength @446-448
- function_definition handleComputeMonthStart @462-485
- function_definition handleGetExtendedYear @494-499
- function_definition handleComputeFields @517-575
- function_definition getEpoc @577-579
- function_definition gregoYearFromIslamicStart @581-596
- function_definition getRelatedYear @598-605
- function_definition setRelatedYear @607-624
- function_definition inTemporalLeapYear @628-636
- function_definition IslamicCivilCalendar @641-644
- function_definition ~IslamicCivilCalendar @646-648
- function_definition getType @650-652
- function_definition clone @654-656
- function_definition yearStart @662-664
- function_definition monthStart @673-679
- function_definition handleGetMonthLength @688-695
- function_definition handleGetYearLength @701-704
- function_definition handleComputeFields @722-764
- function_definition IslamicTBLACalendar @768-771
- function_definition ~IslamicTBLACalendar @773-775
- function_definition getType @777-779
- function_definition clone @781-783
- function_definition getEpoc @785-787
- function_definition IslamicUmalquraCalendar @792-795
- function_definition ~IslamicUmalquraCalendar @797-799
- function_definition getType @801-803
- function_definition clone @805-807
- function_definition yearStart @813-823
- function_definition monthStart @832-844
- function_definition handleGetMonthLength @852-864
- function_definition yearLength @866-878
- function_definition handleGetYearLength @884-886
- function_definition handleComputeFields @904-974
- function_definition IslamicRGSACalendar @978-981
- function_definition ~IslamicRGSACalendar @983-985
- function_definition getType @987-989
- function_definition clone @991-993

### intl/icu/source/i18n/islamcal.h

Blob: `db90255b5b5a4fd483e22813e1bc0b4b4bb05e01`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @21
- include "unicode/calendar.h" @25
- enum_specifier EMonths @92-166
- function_definition IslamicCalendar @188-188
- function_definition IslamicCivilCalendar @354-460
- class_specifier U_I18N_API @354-354
- function_definition IslamicCivilCalendar @371-371
- function_definition IslamicCivilCalendar @469-531
- class_specifier U_I18N_API @469-469
- function_definition IslamicTBLACalendar @486-486
- function_definition IslamicUmalquraCalendar @537-646
- class_specifier U_I18N_API @537-537
- function_definition IslamicUmalquraCalendar @554-554
- function_definition IslamicRGSACalendar @656-711
- class_specifier U_I18N_API @656-656
- function_definition IslamicRGSACalendar @673-673

### intl/icu/source/i18n/iso8601cal.cpp

Blob: `6bb7579e72da33b07e0015ff17b7ebcc182d6327`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @3
- include "iso8601cal.h" @7
- include "unicode/gregocal.h" @8
- function_definition ISO8601Calendar @14-26
- function_definition ~ISO8601Calendar @28-30
- function_definition clone @32-35
- function_definition getType @37-40

### intl/icu/source/i18n/iso8601cal.h

Blob: `957f12e4f230e7b4ade8630fc0b3113812224a77`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @6
- include "unicode/calendar.h" @10
- include "unicode/gregocal.h" @11
- include "unicode/timezone.h" @12
- function_definition GregorianCalendar @14-99
- function_definition ISO8601Calendar @49-49

### intl/icu/source/i18n/japancal.cpp

Blob: `528bd6520255fe7e71216e51baeda318de5e2328`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @16
- include <stdlib.h> @20
- include <windows.h> @30
- include "cmemory.h" @32
- include "erarules.h" @33
- include "japancal.h" @34
- include "unicode/gregocal.h" @35
- include "umutex.h" @36
- include "uassert.h" @37
- include "ucln_in.h" @38
- include "cstring.h" @39
- function_definition japanese_calendar_cleanup @45-54
- function_definition enableTentativeEra @66-92
- function_definition initializeEras @96-102
- function_definition init @104-107
- function_definition getCurrentEra @110-112
- function_definition JapaneseCalendar @114-118
- function_definition ~JapaneseCalendar @120-122
- function_definition JapaneseCalendar @124-130
- function_definition clone @132-135
- function_definition getType @137-140
- function_definition getDefaultMonthInYear @142-165
- function_definition getDefaultDayInMonth @167-184
- function_definition internalGetEra @187-190
- function_definition handleGetExtendedYear @192-217
- function_definition handleComputeFields @220-242
- function_definition haveDefaultCentury @247-250
- function_definition defaultCenturyStart @252-255
- function_definition defaultCenturyStartYear @257-260
- function_definition handleGetLimit @262-293
- function_definition getActualMaximum @295-320

### intl/icu/source/i18n/japancal.h

Blob: `49f7bfd6ca3a06abdc7835a4729ff02f013d2ec6`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @21
- include "unicode/calendar.h" @25
- include "unicode/gregocal.h" @26
- function_definition GregorianCalendar @28-208
- function_definition isEra0CountingBackward @207-207

### intl/icu/source/i18n/listformatter.cpp

Blob: `06bea83b6ebeeb4ca1bc699289fa1f7452400f6d`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @19
- include "cmemory.h" @23
- include "unicode/fpositer.h" @24
- include "unicode/listformatter.h" @25
- include "unicode/simpleformatter.h" @26
- include "unicode/ulistformatter.h" @27
- include "unicode/uscript.h" @28
- include "fphdlimp.h" @29
- include "mutex.h" @30
- include "hash.h" @31
- include "cstring.h" @32
- include "uarrsort.h" @33
- include "ulocimp.h" @34
- include "charstr.h" @35
- include "ucln_in.h" @36
- include "uresimp.h" @37
- include "resource.h" @38
- include "formattedval_impl.h" @39
- function_definition namespace @41-214
- class_specifier PatternHandler @45-72
- function_definition PatternHandler @47-49
- function_definition PatternHandler @51-53
- function_definition clone @57-57
- function_definition (anonymous) @60-62
- function_definition (anonymous) @65-67
- function_definition ~PatternHandler @74-75
- class_specifier ContextualHandler @77-119
- function_definition ContextualHandler @79-88
- function_definition ContextualHandler @90-96
- function_definition clone @100-103
- function_definition (anonymous) @105-108
- function_definition (anonymous) @110-113
- function_definition ~ContextualHandler @121-122
- function_definition shouldChangeToE @133-145
- function_definition shouldChangeToU @150-163
- function_definition shouldChangeToVavDash @167-171
- function_definition createPatternHandler @173-212
- struct_specifier ListFormatInternal @216-242
- function_definition ListFormatInternal @221-230
- function_definition ListFormatInternal @232-236
- function_definition ListFormatInternal @238-241
- class_specifier FormattedListData @245-249
- function_definition FormattedListData @247-247
- function_definition ~FormattedListData @251-251
- function_definition uprv_listformatter_cleanup @258-263
- function_definition uprv_deleteListFormatInternal @265-268
- function_definition (anonymous) @280-293
- function_definition initializeHash @295-309
- function_definition getListFormatInternal @311-353
- function_definition typeWidthToStyleString @355-397
- enum_specifier (anonymous) @401-404
- struct_specifier ListFormatter::ListPatternsSink @406-459
- function_definition ListPatternsSink @410-410
- function_definition setAliasedStyle @413-425
- function_definition handleValueForPattern @427-437
- function_definition put @439-458
- function_definition ListPatternsSink::~ListPatternsSink @462-462
- function_definition loadListFormatInternal @464-503
- function_definition createInstance @505-508
- function_definition createInstance @510-512
- function_definition createInstance @514-522
- function_definition createInstance @524-535
- function_definition ListFormatter @537-540
- function_definition ListFormatter @542-543
- function_definition ~ListFormatter @545-547
- class_specifier FormattedListBuilder @551-630
- function_definition FormattedListBuilder @556-565
- function_definition FormattedListBuilder @568-570
- function_definition append @572-629
- function_definition (anonymous) @634-641
- function_definition (anonymous) @643-661
- function_definition formatStringsToValue @663-727

### intl/icu/source/i18n/measfmt.cpp

Blob: `ee4bcb9e5be0d71ad12e5c643decbfa36c3ad8f3`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @13
- include "unicode/utypes.h" @14
- include "unicode/measfmt.h" @18
- include "unicode/numfmt.h" @19
- include "currfmt.h" @20
- include "unicode/localpointer.h" @21
- include "resource.h" @22
- include "unicode/simpleformatter.h" @23
- include "quantityformatter.h" @24
- include "unicode/plurrule.h" @25
- include "unicode/decimfmt.h" @26
- include "uresimp.h" @27
- include "unicode/ures.h" @28
- include "unicode/ustring.h" @29
- include "ureslocs.h" @30
- include "cstring.h" @31
- include "mutex.h" @32
- include "ucln_in.h" @33
- include "unicode/listformatter.h" @34
- include "charstr.h" @35
- include "unicode/putil.h" @36
- include "unicode/smpdtfmt.h" @37
- include "uassert.h" @38
- include "unicode/numberformatter.h" @39
- include "number_longnames.h" @40
- include "number_utypes.h" @41
- include "sharednumberformat.h" @43
- include "sharedpluralrules.h" @44
- include "standardplural.h" @45
- include "unifiedcache.h" @46
- class_specifier NumericDateFormatters @58-82
- function_definition NumericDateFormatters @71-78
- function_definition getRegularWidth @84-89
- function_definition getUnitWidth @91-102
- class_specifier MeasureFormatCacheData @114-156
- function_definition adoptCurrencyFormat @127-130
- function_definition getCurrencyFormat @131-133
- function_definition adoptIntegerFormat @134-137
- function_definition getIntegerFormat @138-140
- function_definition adoptNumericDateFormatters @141-144
- function_definition getNumericDateFormatters @145-147
- function_definition MeasureFormatCacheData @158-164
- function_definition ~MeasureFormatCacheData @166-173
- function_definition isCurrency @175-177
- function_definition getString @179-190
- function_definition loadNumericDateFormatterPattern @192-223
- function_definition loadNumericDateFormatters @225-240
- function_definition createObject @243-285
- function_definition isTimeUnit @287-290
- function_definition toHMS @299-350
- function_definition MeasureFormat @353-361
- function_definition MeasureFormat @363-374
- function_definition MeasureFormat @376-389
- function_definition (anonymous) @391-407
- function_definition MeasureFormat @409-415
- function_definition ~MeasureFormat @417-428
- function_definition operator== @430-464
- function_definition clone @466-468
- function_definition (anonymous) @470-486
- function_definition parseObject @488-492
- function_definition (anonymous) @494-520
- function_definition (anonymous) @522-568
- function_definition getUnitDisplayName @570-576
- function_definition initMeasureFormat @578-628
- function_definition adoptNumberFormat @630-643
- function_definition setMeasureFormatLocale @645-651
- function_definition (anonymous) @653-655
- function_definition (anonymous) @657-659
- function_definition (anonymous) @661-663
- function_definition getLocale @665-667
- function_definition getLocaleID @669-671
- function_definition (anonymous) @673-719
- function_definition (anonymous) @723-823
- function_definition (anonymous) @825-872

### intl/icu/source/i18n/measunit.cpp

Blob: `06b2436940ae87ced0475a7228db9e22ce2af79a`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @13
- include "unicode/measunit.h" @15
- include "unicode/uenum.h" @19
- include "unicode/errorcode.h" @20
- include "ustrenum.h" @21
- include "cstring.h" @22
- include "uassert.h" @23
- include "measunit_impl.h" @24
- function_definition createGForce @643-645
- function_definition getGForce @647-649
- function_definition createMeterPerSecondSquared @651-653
- function_definition getMeterPerSecondSquared @655-657
- function_definition createArcMinute @659-661
- function_definition getArcMinute @663-665
- function_definition createArcSecond @667-669
- function_definition getArcSecond @671-673
- function_definition createDegree @675-677
- function_definition getDegree @679-681
- function_definition createRadian @683-685
- function_definition getRadian @687-689
- function_definition createRevolutionAngle @691-693
- function_definition getRevolutionAngle @695-697
- function_definition createSteradian @699-701
- function_definition getSteradian @703-705
- function_definition createAcre @707-709
- function_definition getAcre @711-713
- function_definition createBuJp @715-717
- function_definition getBuJp @719-721
- function_definition createCho @723-725
- function_definition getCho @727-729
- function_definition createDunam @731-733
- function_definition getDunam @735-737
- function_definition createHectare @739-741
- function_definition getHectare @743-745
- function_definition createSeJp @747-749
- function_definition getSeJp @751-753
- function_definition createSquareCentimeter @755-757
- function_definition getSquareCentimeter @759-761
- function_definition createSquareFoot @763-765
- function_definition getSquareFoot @767-769
- function_definition createSquareInch @771-773
- function_definition getSquareInch @775-777
- function_definition createSquareKilometer @779-781
- function_definition getSquareKilometer @783-785
- function_definition createSquareMeter @787-789
- function_definition getSquareMeter @791-793
- function_definition createSquareMile @795-797
- function_definition getSquareMile @799-801
- function_definition createSquareYard @803-805
- function_definition getSquareYard @807-809
- function_definition createItem @811-813
- function_definition getItem @815-817
- function_definition createKarat @819-821
- function_definition getKarat @823-825
- function_definition createKatal @827-829
- function_definition getKatal @831-833
- function_definition createMilligramOfglucosePerDeciliter @835-837
- function_definition getMilligramOfglucosePerDeciliter @839-841
- function_definition createMilligramPerDeciliter @843-845
- function_definition getMilligramPerDeciliter @847-849
- function_definition createMillimolePerLiter @851-853
- function_definition getMillimolePerLiter @855-857
- function_definition createMole @859-861
- function_definition getMole @863-865
- function_definition createOfglucose @867-869
- function_definition getOfglucose @871-873
- function_definition createPart @875-877
- function_definition getPart @879-881
- function_definition createPartPer1E6 @883-885
- function_definition getPartPer1E6 @887-889
- function_definition createPartPerMillion @891-893
- function_definition getPartPerMillion @895-897
- function_definition createPartPer1E9 @899-901
- function_definition getPartPer1E9 @903-905
- function_definition createPercent @907-909
- function_definition getPercent @911-913
- function_definition createPermille @915-917
- function_definition getPermille @919-921
- function_definition createPermyriad @923-925
- function_definition getPermyriad @927-929
- function_definition createLiterPer100Kilometers @931-933
- function_definition getLiterPer100Kilometers @935-937
- function_definition createLiterPerKilometer @939-941
- function_definition getLiterPerKilometer @943-945
- function_definition createMilePerGallon @947-949
- function_definition getMilePerGallon @951-953
- function_definition createMilePerGallonImperial @955-957
- function_definition getMilePerGallonImperial @959-961
- function_definition createBit @963-965
- function_definition getBit @967-969
- function_definition createByte @971-973
- function_definition getByte @975-977
- function_definition createGigabit @979-981
- function_definition getGigabit @983-985
- function_definition createGigabyte @987-989
- function_definition getGigabyte @991-993
- function_definition createKilobit @995-997
- function_definition getKilobit @999-1001
- function_definition createKilobyte @1003-1005
- function_definition getKilobyte @1007-1009
- function_definition createMegabit @1011-1013
- function_definition getMegabit @1015-1017
- function_definition createMegabyte @1019-1021
- function_definition getMegabyte @1023-1025
- function_definition createPetabyte @1027-1029
- function_definition getPetabyte @1031-1033
- function_definition createTerabit @1035-1037
- function_definition getTerabit @1039-1041
- function_definition createTerabyte @1043-1045
- function_definition getTerabyte @1047-1049
- function_definition createCentury @1051-1053
- function_definition getCentury @1055-1057
- function_definition createDay @1059-1061
- function_definition getDay @1063-1065
- function_definition createDayPerson @1067-1069
- function_definition getDayPerson @1071-1073
- function_definition createDecade @1075-1077
- function_definition getDecade @1079-1081
- function_definition createFortnight @1083-1085
- function_definition getFortnight @1087-1089
- function_definition createHour @1091-1093
- function_definition getHour @1095-1097
- function_definition createMicrosecond @1099-1101
- function_definition getMicrosecond @1103-1105
- function_definition createMillisecond @1107-1109
- function_definition getMillisecond @1111-1113
- function_definition createMinute @1115-1117
- function_definition getMinute @1119-1121
- function_definition createMonth @1123-1125
- function_definition getMonth @1127-1129
- function_definition createMonthPerson @1131-1133
- function_definition getMonthPerson @1135-1137
- function_definition createNanosecond @1139-1141
- function_definition getNanosecond @1143-1145
- function_definition createNight @1147-1149
- function_definition getNight @1151-1153
- function_definition createQuarter @1155-1157
- function_definition getQuarter @1159-1161
- function_definition createSecond @1163-1165
- function_definition getSecond @1167-1169
- function_definition createWeek @1171-1173
- function_definition getWeek @1175-1177
- function_definition createWeekPerson @1179-1181
- function_definition getWeekPerson @1183-1185
- function_definition createYear @1187-1189
- function_definition getYear @1191-1193
- function_definition createYearPerson @1195-1197
- function_definition getYearPerson @1199-1201
- function_definition createAmpere @1203-1205
- function_definition getAmpere @1207-1209
- function_definition createCoulomb @1211-1213
- function_definition getCoulomb @1215-1217
- function_definition createFarad @1219-1221
- function_definition getFarad @1223-1225
- function_definition createHenry @1227-1229
- function_definition getHenry @1231-1233
- function_definition createMilliampere @1235-1237
- function_definition getMilliampere @1239-1241
- function_definition createOhm @1243-1245
- function_definition getOhm @1247-1249
- function_definition createSiemens @1251-1253
- function_definition getSiemens @1255-1257
- function_definition createVolt @1259-1261
- function_definition getVolt @1263-1265
- function_definition createBecquerel @1267-1269
- function_definition getBecquerel @1271-1273
- function_definition createBritishThermalUnit @1275-1277
- function_definition getBritishThermalUnit @1279-1281
- function_definition createBritishThermalUnitIt @1283-1285
- function_definition getBritishThermalUnitIt @1287-1289
- function_definition createCalorie @1291-1293
- function_definition getCalorie @1295-1297
- function_definition createCalorieIt @1299-1301
- function_definition getCalorieIt @1303-1305
- function_definition createElectronvolt @1307-1309
- function_definition getElectronvolt @1311-1313
- function_definition createFoodcalorie @1315-1317
- function_definition getFoodcalorie @1319-1321
- function_definition createGray @1323-1325
- function_definition getGray @1327-1329
- function_definition createJoule @1331-1333
- function_definition getJoule @1335-1337
- function_definition createKilocalorie @1339-1341
- function_definition getKilocalorie @1343-1345
- function_definition createKilojoule @1347-1349
- function_definition getKilojoule @1351-1353
- function_definition createKilowattHour @1355-1357
- function_definition getKilowattHour @1359-1361
- function_definition createSievert @1363-1365
- function_definition getSievert @1367-1369
- function_definition createThermUs @1371-1373
- function_definition getThermUs @1375-1377
- function_definition createKilogramForce @1379-1381
- function_definition getKilogramForce @1383-1385
- function_definition createKilowattHourPer100Kilometer @1387-1389
- function_definition getKilowattHourPer100Kilometer @1391-1393
- function_definition createNewton @1395-1397
- function_definition getNewton @1399-1401
- function_definition createPoundForce @1403-1405
- function_definition getPoundForce @1407-1409
- function_definition createGigahertz @1411-1413
- function_definition getGigahertz @1415-1417
- function_definition createHertz @1419-1421
- function_definition getHertz @1423-1425
- function_definition createKilohertz @1427-1429
- function_definition getKilohertz @1431-1433
- function_definition createMegahertz @1435-1437
- function_definition getMegahertz @1439-1441
- function_definition createDot @1443-1445
- function_definition getDot @1447-1449
- function_definition createDotPerCentimeter @1451-1453
- function_definition getDotPerCentimeter @1455-1457
- function_definition createDotPerInch @1459-1461
- function_definition getDotPerInch @1463-1465
- function_definition createEm @1467-1469
- function_definition getEm @1471-1473
- function_definition createMegapixel @1475-1477
- function_definition getMegapixel @1479-1481
- function_definition createPixel @1483-1485
- function_definition getPixel @1487-1489
- function_definition createPixelPerCentimeter @1491-1493
- function_definition getPixelPerCentimeter @1495-1497
- function_definition createPixelPerInch @1499-1501
- function_definition getPixelPerInch @1503-1505
- function_definition createAstronomicalUnit @1507-1509
- function_definition getAstronomicalUnit @1511-1513
- function_definition createCentimeter @1515-1517
- function_definition getCentimeter @1519-1521
- function_definition createChain @1523-1525
- function_definition getChain @1527-1529
- function_definition createDecimeter @1531-1533
- function_definition getDecimeter @1535-1537
- function_definition createEarthRadius @1539-1541
- function_definition getEarthRadius @1543-1545
- function_definition createFathom @1547-1549
- function_definition getFathom @1551-1553
- function_definition createFoot @1555-1557
- function_definition getFoot @1559-1561
- function_definition createFurlong @1563-1565
- function_definition getFurlong @1567-1569
- function_definition createInch @1571-1573
- function_definition getInch @1575-1577
- function_definition createJoJp @1579-1581
- function_definition getJoJp @1583-1585
- function_definition createKen @1587-1589
- function_definition getKen @1591-1593
- function_definition createKilometer @1595-1597
- function_definition getKilometer @1599-1601
- function_definition createLightYear @1603-1605
- function_definition getLightYear @1607-1609
- function_definition createMeter @1611-1613
- function_definition getMeter @1615-1617
- function_definition createMicrometer @1619-1621
- function_definition getMicrometer @1623-1625
- function_definition createMile @1627-1629
- function_definition getMile @1631-1633
- function_definition createMileScandinavian @1635-1637
- function_definition getMileScandinavian @1639-1641
- function_definition createMillimeter @1643-1645
- function_definition getMillimeter @1647-1649
- function_definition createNanometer @1651-1653
- function_definition getNanometer @1655-1657
- function_definition createNauticalMile @1659-1661
- function_definition getNauticalMile @1663-1665
- function_definition createParsec @1667-1669
- function_definition getParsec @1671-1673
- function_definition createPicometer @1675-1677
- function_definition getPicometer @1679-1681
- function_definition createPoint @1683-1685
- function_definition getPoint @1687-1689
- function_definition createRiJp @1691-1693
- function_definition getRiJp @1695-1697
- function_definition createRin @1699-1701
- function_definition getRin @1703-1705
- function_definition createRod @1707-1709
- function_definition getRod @1711-1713
- function_definition createShakuCloth @1715-1717
- function_definition getShakuCloth @1719-1721
- function_definition createShakuLength @1723-1725
- function_definition getShakuLength @1727-1729
- function_definition createSolarRadius @1731-1733
- function_definition getSolarRadius @1735-1737
- function_definition createSun @1739-1741
- function_definition getSun @1743-1745
- function_definition createYard @1747-1749
- function_definition getYard @1751-1753
- function_definition createCandela @1755-1757
- function_definition getCandela @1759-1761
- function_definition createLumen @1763-1765
- function_definition getLumen @1767-1769
- function_definition createLux @1771-1773
- function_definition getLux @1775-1777
- function_definition createSolarLuminosity @1779-1781
- function_definition getSolarLuminosity @1783-1785
- function_definition createTesla @1787-1789
- function_definition getTesla @1791-1793
- function_definition createWeber @1795-1797
- function_definition getWeber @1799-1801
- function_definition createCarat @1803-1805
- function_definition getCarat @1807-1809
- function_definition createDalton @1811-1813
- function_definition getDalton @1815-1817
- function_definition createEarthMass @1819-1821
- function_definition getEarthMass @1823-1825
- function_definition createFun @1827-1829
- function_definition getFun @1831-1833
- function_definition createGrain @1835-1837
- function_definition getGrain @1839-1841
- function_definition createGram @1843-1845
- function_definition getGram @1847-1849
- function_definition createKilogram @1851-1853
- function_definition getKilogram @1855-1857
- function_definition createMicrogram @1859-1861
- function_definition getMicrogram @1863-1865
- function_definition createMilligram @1867-1869
- function_definition getMilligram @1871-1873
- function_definition createOunce @1875-1877
- function_definition getOunce @1879-1881
- function_definition createOunceTroy @1883-1885
- function_definition getOunceTroy @1887-1889
- function_definition createPound @1891-1893
- function_definition getPound @1895-1897
- function_definition createSlug @1899-1901
- function_definition getSlug @1903-1905
- function_definition createSolarMass @1907-1909
- function_definition getSolarMass @1911-1913
- function_definition createStone @1915-1917
- function_definition getStone @1919-1921
- function_definition createTon @1923-1925
- function_definition getTon @1927-1929
- function_definition createTonne @1931-1933
- function_definition getTonne @1935-1937
- function_definition createMetricTon @1939-1941
- function_definition getMetricTon @1943-1945
- function_definition createGigawatt @1947-1949
- function_definition getGigawatt @1951-1953
- function_definition createHorsepower @1955-1957
- function_definition getHorsepower @1959-1961
- function_definition createKilowatt @1963-1965
- function_definition getKilowatt @1967-1969
- function_definition createMegawatt @1971-1973
- function_definition getMegawatt @1975-1977
- function_definition createMilliwatt @1979-1981
- function_definition getMilliwatt @1983-1985
- function_definition createWatt @1987-1989
- function_definition getWatt @1991-1993
- function_definition createAtmosphere @1995-1997
- function_definition getAtmosphere @1999-2001
- function_definition createBar @2003-2005
- function_definition getBar @2007-2009
- function_definition createGasolineEnergyDensity @2011-2013
- function_definition getGasolineEnergyDensity @2015-2017
- function_definition createHectopascal @2019-2021
- function_definition getHectopascal @2023-2025
- function_definition createInchHg @2027-2029
- function_definition getInchHg @2031-2033
- function_definition createKilopascal @2035-2037
- function_definition getKilopascal @2039-2041
- function_definition createMegapascal @2043-2045
- function_definition getMegapascal @2047-2049
- function_definition createMillibar @2051-2053
- function_definition getMillibar @2055-2057
- function_definition createMillimeterOfMercury @2059-2061
- function_definition getMillimeterOfMercury @2063-2065
- function_definition createOfhg @2067-2069
- function_definition getOfhg @2071-2073
- function_definition createPascal @2075-2077
- function_definition getPascal @2079-2081
- function_definition createPoundPerSquareInch @2083-2085
- function_definition getPoundPerSquareInch @2087-2089
- function_definition createBeaufort @2091-2093
- function_definition getBeaufort @2095-2097
- function_definition createKilometerPerHour @2099-2101
- function_definition getKilometerPerHour @2103-2105
- function_definition createKnot @2107-2109
- function_definition getKnot @2111-2113
- function_definition createLightSpeed @2115-2117
- function_definition getLightSpeed @2119-2121
- function_definition createMeterPerSecond @2123-2125
- function_definition getMeterPerSecond @2127-2129
- function_definition createMilePerHour @2131-2133
- function_definition getMilePerHour @2135-2137
- function_definition createCelsius @2139-2141
- function_definition getCelsius @2143-2145
- function_definition createFahrenheit @2147-2149
- function_definition getFahrenheit @2151-2153
- function_definition createGenericTemperature @2155-2157
- function_definition getGenericTemperature @2159-2161
- function_definition createKelvin @2163-2165
- function_definition getKelvin @2167-2169
- function_definition createRankine @2171-2173
- function_definition getRankine @2175-2177
- function_definition createNewtonMeter @2179-2181
- function_definition getNewtonMeter @2183-2185
- function_definition createPoundFoot @2187-2189
- function_definition getPoundFoot @2191-2193
- function_definition createAcreFoot @2195-2197
- function_definition getAcreFoot @2199-2201
- function_definition createBarrel @2203-2205
- function_definition getBarrel @2207-2209
- function_definition createBushel @2211-2213
- function_definition getBushel @2215-2217
- function_definition createCentiliter @2219-2221
- function_definition getCentiliter @2223-2225
- function_definition createCubicCentimeter @2227-2229
- function_definition getCubicCentimeter @2231-2233
- function_definition createCubicFoot @2235-2237
- function_definition getCubicFoot @2239-2241
- function_definition createCubicInch @2243-2245
- function_definition getCubicInch @2247-2249
- function_definition createCubicKilometer @2251-2253
- function_definition getCubicKilometer @2255-2257
- function_definition createCubicMeter @2259-2261
- function_definition getCubicMeter @2263-2265
- function_definition createCubicMile @2267-2269
- function_definition getCubicMile @2271-2273
- function_definition createCubicYard @2275-2277
- function_definition getCubicYard @2279-2281
- function_definition createCup @2283-2285
- function_definition getCup @2287-2289
- function_definition createCupImperial @2291-2293
- function_definition getCupImperial @2295-2297
- function_definition createCupJp @2299-2301
- function_definition getCupJp @2303-2305
- function_definition createCupMetric @2307-2309
- function_definition getCupMetric @2311-2313
- function_definition createDeciliter @2315-2317
- function_definition getDeciliter @2319-2321
- function_definition createDessertSpoon @2323-2325
- function_definition getDessertSpoon @2327-2329
- function_definition createDessertSpoonImperial @2331-2333
- function_definition getDessertSpoonImperial @2335-2337
- function_definition createDram @2339-2341
- function_definition getDram @2343-2345
- function_definition createDrop @2347-2349
- function_definition getDrop @2351-2353
- function_definition createFluidOunce @2355-2357
- function_definition getFluidOunce @2359-2361
- function_definition createFluidOunceImperial @2363-2365
- function_definition getFluidOunceImperial @2367-2369
- function_definition createFluidOunceMetric @2371-2373
- function_definition getFluidOunceMetric @2375-2377
- function_definition createGallon @2379-2381
- function_definition getGallon @2383-2385
- function_definition createGallonImperial @2387-2389
- function_definition getGallonImperial @2391-2393
- function_definition createHectoliter @2395-2397
- function_definition getHectoliter @2399-2401
- function_definition createJigger @2403-2405
- function_definition getJigger @2407-2409
- function_definition createKoku @2411-2413
- function_definition getKoku @2415-2417
- function_definition createKosaji @2419-2421
- function_definition getKosaji @2423-2425
- function_definition createLiter @2427-2429
- function_definition getLiter @2431-2433
- function_definition createMegaliter @2435-2437
- function_definition getMegaliter @2439-2441
- function_definition createMilliliter @2443-2445
- function_definition getMilliliter @2447-2449
- function_definition createOsaji @2451-2453
- function_definition getOsaji @2455-2457
- function_definition createPinch @2459-2461
- function_definition getPinch @2463-2465
- function_definition createPint @2467-2469
- function_definition getPint @2471-2473
- function_definition createPintImperial @2475-2477
- function_definition getPintImperial @2479-2481
- function_definition createPintMetric @2483-2485
- function_definition getPintMetric @2487-2489
- function_definition createQuart @2491-2493
- function_definition getQuart @2495-2497
- function_definition createQuartImperial @2499-2501
- function_definition getQuartImperial @2503-2505
- function_definition createSai @2507-2509
- function_definition getSai @2511-2513
- function_definition createShaku @2515-2517
- function_definition getShaku @2519-2521
- function_definition createTablespoon @2523-2525
- function_definition getTablespoon @2527-2529
- function_definition createTeaspoon @2531-2533
- function_definition getTeaspoon @2535-2537
- function_definition createToJp @2539-2541
- function_definition getToJp @2543-2545
- function_definition binarySearch @2549-2564
- function_definition MeasureUnit @2566-2567
- function_definition MeasureUnit @2569-2571
- function_definition MeasureUnit @2573-2576
- function_definition MeasureUnit @2578-2583
- function_definition MeasureUnit @2585-2590
- function_definition (anonymous) @2592-2611
- function_definition (anonymous) @2613-2623
- function_definition clone @2625-2627
- function_definition ~MeasureUnit @2629-2634
- function_definition getType @2636-2642
- function_definition getSubtype @2644-2650
- function_definition getIdentifier @2652-2654
- function_definition operator== @2656-2665
- function_definition getAvailable @2667-2688
- function_definition getAvailable @2690-2711
- function_definition getAvailableTypes @2713-2727
- function_definition findBySubType @2729-2746
- function_definition create @2748-2757
- function_definition initTime @2759-2766
- function_definition initCurrency @2768-2792
- function_definition setTo @2794-2801
- function_definition getOffset @2803-2808
- function_definition copy @2810-2827

### intl/icu/source/i18n/measunit_extra.cpp

Blob: `2e00146411cdb41ef39cefbf34b028b6b4629246`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @7
- include "charstr.h" @15
- include "cmemory.h" @16
- include "cstring.h" @17
- include "double-conversion/string-to-double.h" @19
- include "double-conversion-string-to-double.h" @21
- include "measunit_impl.h" @23
- include "resource.h" @24
- include "uarrsort.h" @25
- include "uassert.h" @26
- include "ucln_in.h" @27
- include "umutex.h" @28
- include "unicode/bytestrie.h" @29
- include "unicode/bytestriebuilder.h" @30
- include "unicode/localpointer.h" @31
- include "unicode/stringpiece.h" @32
- include "unicode/stringtriebuilder.h" @33
- include "unicode/ures.h" @34
- include "unicode/ustringtrie.h" @35
- include "uresimp.h" @36
- include "util.h" @37
- include <limits.h> @38
- include <cstdlib> @39
- function_definition namespace @40-1155
- enum_specifier CompoundPart @69-76
- enum_specifier InitialCompoundPart @81-85
- enum_specifier PowerPart @90-105
- struct_specifier UnitPrefixStrings @114-117
- class_specifier SimpleUnitIdentifiersSink @172-267
- function_definition SimpleUnitIdentifiersSink @192-196
- function_definition put @207-255
- class_specifier UnitAliasesSink @269-319
- function_definition UnitAliasesSink @276-278
- function_definition put @288-314
- class_specifier CategoriesSink @332-383
- function_definition CategoriesSink @344-345
- function_definition put @347-375
- function_definition cleanupUnitExtras @415-433
- function_definition initUnitExtras @435-581
- class_specifier Token @583-709
- function_definition Token @585-599
- function_definition constantToken @601-610
- enum_specifier Type @612-623
- function_definition getType @627-630
- function_definition getConstantDenominator @633-636
- function_definition getUnitPrefix @638-641
- function_definition getMatch @644-647
- function_definition getInitialCompoundPart @649-657
- function_definition getPower @659-662
- function_definition getSimpleUnitIndex @664-667
- function_definition getAliasIndex @669-672
- function_definition parseStringToLong @678-703
- function_definition Token @706-706
- class_specifier Parser @711-1132
- function_definition from @721-730
- struct_specifier SingleUnitOrConstant @735-774
- enum_specifier ValueType @736-739
- function_definition singleUnitValue @745-751
- function_definition constantDenominatorValue @753-759
- function_definition getConstantDenominator @761-764
- function_definition getSingleUnit @766-769
- function_definition isSingleUnit @771-771
- function_definition isConstantDenominator @773-773
- function_definition parse @776-843
- function_definition Parser @867-867
- function_definition Parser @869-870
- function_definition hasNext @872-874
- function_definition nextToken @879-926
- function_definition nextSingleUnitOrConstant @942-1091
- function_definition processAlias @1100-1131
- function_definition compareSingleUnits @1135-1140
- function_definition getUnitCategoryIndex @1145-1153
- function_definition umeas_getPrefixPower @1157-1166
- function_definition umeas_getPrefixBase @1168-1177
- function_definition getUnitQuantity @1179-1251
- function_definition forMeasureUnit @1254-1268
- function_definition build @1270-1280
- function_definition getSimpleUnitID @1282-1284
- function_definition appendNeutralIdentifier @1286-1328
- function_definition getUnitCategoryIndex @1330-1332
- function_definition MeasureUnitImpl @1334-1336
- function_definition forIdentifier @1338-1340
- function_definition (anonymous) @1342-1350
- function_definition forMeasureUnitMaybeCopy @1352-1359
- function_definition takeReciprocal @1361-1366
- function_definition copyAndSimplify @1368-1393
- function_definition appendSingleUnit @1395-1435
- function_definition extractIndividualUnitsWithIndices @1437-1454
- function_definition countCharacter @1456-1464
- function_definition getConstantsString @1477-1499
- function_definition serialize @1504-1577
- function_definition build @1579-1582
- function_definition forIdentifier @1584-1586
- function_definition getComplexity @1588-1591
- function_definition getPrefix @1593-1595
- function_definition withPrefix @1597-1602
- function_definition getConstantDenominator @1604-1620
- function_definition withConstantDenominator @1622-1648
- function_definition getDimensionality @1650-1657
- function_definition withDimensionality @1659-1663
- function_definition reciprocal @1665-1674
- function_definition product @1676-1707
- function_definition splitToSingleUnitsImpl @1709-1722

### intl/icu/source/i18n/measunit_impl.h

Blob: `36beadc1ea83ed28d9b551b9a64c7c987c389cd2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @7
- include "unicode/measunit.h" @11
- include "cmemory.h" @12
- include "charstr.h" @13
- include "fixedstring.h" @14
- function_definition impl @16-20
- class_specifier LongNameHandler @19-19
- function_definition SingleUnitImpl @43-195
- struct_specifier U_I18N_API_CLASS @43-43
- function_definition compareTo @91-151
- function_definition isCompatibleWith @159-161
- function_definition isDimensionless @168-170
- struct_specifier MeasureUnitImplWithIndex @198-198
- function_definition MeasureUnitImpl @204-337
- class_specifier U_I18N_API_CLASS @204-204
- function_definition MeasureUnitImpl @207-207
- function_definition MeasureUnitImpl @209-209
- function_definition get @215-217
- function_definition forCurrencyCode @253-262
- struct_specifier MeasureUnitImplWithIndex @339-349
- function_definition MeasureUnitImplWithIndex @343-345
- function_definition MeasureUnitImplWithIndex @346-348

### intl/icu/source/i18n/measure.cpp

Blob: `3280bcda467ee01e47c22ab6d88aa4d3acf4c9f3`. Grammar: cpp. Status: contains-errors.

- include "utypeinfo.h" @13
- include "unicode/utypes.h" @15
- include "unicode/measure.h" @19
- include "unicode/measunit.h" @20
- function_definition Measure @26-26
- function_definition Measure @28-35
- function_definition Measure @37-40
- function_definition (anonymous) @42-53
- function_definition clone @55-57
- function_definition ~Measure @59-61
- function_definition operator== @63-74

### intl/icu/source/i18n/messageformat2.cpp

Blob: `b7202ccb8ad6541456c24275e02760080e74f2a2`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_arguments.h" @12
- include "unicode/messageformat2_data_model.h" @13
- include "unicode/messageformat2_formattable.h" @14
- include "unicode/messageformat2.h" @15
- include "unicode/normalizer2.h" @16
- include "unicode/unistr.h" @17
- include "messageformat2_allocation.h" @18
- include "messageformat2_checker.h" @19
- include "messageformat2_evaluation.h" @20
- include "messageformat2_function_registry_internal.h" @21
- include "messageformat2_macros.h" @22
- function_definition namespace @25-785
- function_definition evalLiteral @35-37
- function_definition evalArgument @40-59
- function_definition reserialize @62-80
- function_definition formatLiteral @83-89
- function_definition formatOperand @91-143
- function_definition resolveOptions @146-181
- function_definition evalFunctionCall @184-221
- function_definition evalFunctionCall @225-265
- function_definition formatExpression @268-308
- function_definition formatPattern @311-340
- function_definition resolveSelectors @347-379
- function_definition matchSelectorKeys @383-452
- function_definition resolvePreferences @457-502
- function_definition vectorFind @505-512
- function_definition vectorContains @514-516
- function_definition filterVariants @520-567
- function_definition sortVariants @573-626
- function_definition formatSelectors @628-666
- function_definition formatToString @672-712
- function_definition check @717-724
- function_definition check @726-749
- function_definition check @751-760
- function_definition checkDeclarations @763-784

### intl/icu/source/i18n/messageformat2_allocation.h

Blob: `5b06d0851296a1b96512d4ebddf6212a8eabd7d1`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/unistr.h" @19
- include "uvector.h" @20
- function_definition namespace @22-136
- function_definition copyArray @29-44
- function_definition copyVectorToArray @47-61
- function_definition moveVectorToArray @64-80
- function_definition createUVectorNoAdopt @82-91
- function_definition createUVector @93-100
- function_definition stringsEqual @102-104
- function_definition createStringUVector @106-113
- function_definition createStringVectorNoAdopt @115-122
- function_definition create @125-134

### intl/icu/source/i18n/messageformat2_arguments.cpp

Blob: `bf402fe6d5f0a0491ad1a0affb2165087c8d325b`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2.h" @12
- include "unicode/messageformat2_arguments.h" @13
- include "unicode/messageformat2_data_model_names.h" @14
- include "messageformat2_evaluation.h" @15
- include "messageformat2_function_registry_internal.h" @16
- include "uvector.h" @17
- function_definition namespace @19-61
- function_definition getArgument @30-44
- function_definition ~MessageArguments @46-46
- function_definition (anonymous) @51-59

### intl/icu/source/i18n/messageformat2_checker.cpp

Blob: `1956d78aea61d57ad19460d55791e3b8abd9b6fb`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2.h" @12
- include "messageformat2_allocation.h" @13
- include "messageformat2_checker.h" @14
- include "messageformat2_evaluation.h" @15
- include "messageformat2_function_registry_internal.h" @16
- include "messageformat2_macros.h" @17
- include "uvector.h" @18
- function_definition namespace @20-318
- function_definition TypeEnvironment @43-56
- function_definition has @58-60
- function_definition known @64-66
- function_definition get @68-84
- function_definition extend @86-106
- function_definition ~TypeEnvironment @108-108
- function_definition normalizeNFC @112-118
- function_definition areDefaultKeys @120-128
- function_definition addFreeVars @130-139
- function_definition addFreeVars @141-147
- function_definition addFreeVars @149-153
- function_definition addFreeVars @155-164
- function_definition checkVariants @166-219
- function_definition requireAnnotated @221-231
- function_definition checkSelectors @233-242
- function_definition typeOf @244-255
- function_definition checkDeclarations @257-301
- function_definition check @303-316

### intl/icu/source/i18n/messageformat2_checker.h

Blob: `122f668f4b7e9bc0721b20e81bca26a1138b930f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_data_model.h" @19
- include "messageformat2_errors.h" @20
- function_definition namespace @22-93
- class_specifier TypeEnvironment @31-59
- enum_specifier Type @37-41
- class_specifier MessageFormatter @61-61
- class_specifier Checker @65-91
- function_definition Checker @68-69

### intl/icu/source/i18n/messageformat2_data_model.cpp

Blob: `56c92d3843aabc4d10fc241b6d8acc305396bae5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_data_model.h" @12
- include "messageformat2_allocation.h" @13
- include "messageformat2_macros.h" @14
- include "uvector.h" @15
- function_definition namespace @17-920
- function_definition getKeysInternal @27-29
- function_definition operator< @32-54
- function_definition Builder::Builder @56-58
- function_definition (anonymous) @60-67
- function_definition Builder::build @69-75
- function_definition Builder::~Builder @77-81
- function_definition SelectorKeys @83-89
- function_definition (anonymous) @91-94
- function_definition SelectorKeys @96-104
- function_definition ~SelectorKeys @106-108
- function_definition operator< @112-115
- function_definition operator== @117-120
- function_definition quoted @122-127
- function_definition (anonymous) @129-129
- function_definition (anonymous) @131-135
- function_definition ~Literal @137-139
- function_definition Operand @143-143
- function_definition (anonymous) @145-149
- function_definition isVariable @151-153
- function_definition isLiteral @154-156
- function_definition isNull @157-157
- function_definition (anonymous) @159-162
- function_definition (anonymous) @164-167
- function_definition ~Operand @169-169
- function_definition (anonymous) @173-176
- function_definition operator< @178-187
- function_definition operator== @189-197
- function_definition (anonymous) @199-202
- function_definition ~Key @204-204
- function_definition OptionMap @208-216
- function_definition OptionMap @218-232
- function_definition (anonymous) @234-237
- function_definition (anonymous) @239-249
- function_definition size @251-254
- function_definition ~OptionMap @256-256
- function_definition Builder::build @258-260
- function_definition Builder::Builder @262-264
- function_definition Builder::Builder @266-270
- function_definition (anonymous) @272-275
- function_definition Builder::attributes @277-283
- function_definition hasOptionNamed @285-294
- function_definition (anonymous) @296-307
- function_definition Builder::~Builder @309-313
- function_definition (anonymous) @315-317
- function_definition Option @319-319
- function_definition (anonymous) @321-324
- function_definition ~Option @326-326
- function_definition Builder::Builder @328-328
- function_definition (anonymous) @330-333
- function_definition (anonymous) @335-337
- function_definition (anonymous) @339-344
- function_definition Builder::build @346-348
- function_definition Operator @350-351
- function_definition (anonymous) @353-356
- function_definition Operator @360-360
- function_definition Builder::~Builder @362-362
- function_definition ~Operator @364-364
- function_definition Builder::Builder @368-369
- function_definition Markup @371-372
- function_definition (anonymous) @374-379
- function_definition (anonymous) @381-386
- function_definition Builder::build @388-407
- function_definition Builder::~Builder @409-409
- function_definition ~Markup @411-411
- function_definition Builder::Builder @415-416
- function_definition isStandaloneAnnotation @418-420
- function_definition isFunctionCall @424-426
- function_definition getOperator @428-437
- function_definition (anonymous) @440-440
- function_definition (anonymous) @442-446
- function_definition (anonymous) @448-452
- function_definition (anonymous) @454-459
- function_definition Builder::build @461-483
- function_definition Expression @485-485
- function_definition Expression @487-487
- function_definition (anonymous) @489-492
- function_definition Builder::~Builder @494-494
- function_definition ~Expression @496-496
- function_definition PatternPart @503-503
- function_definition (anonymous) @505-508
- function_definition (anonymous) @510-513
- function_definition (anonymous) @516-519
- function_definition (anonymous) @521-524
- function_definition ~PatternPart @526-526
- function_definition Pattern @530-537
- function_definition Pattern @540-551
- function_definition numParts @553-556
- function_definition (anonymous) @558-561
- function_definition Builder::Builder @563-565
- function_definition Builder::build @567-573
- function_definition (anonymous) @575-582
- function_definition (anonymous) @584-591
- function_definition (anonymous) @593-600
- function_definition (anonymous) @602-606
- function_definition Builder::~Builder @608-612
- function_definition ~Pattern @614-614
- function_definition (anonymous) @618-620
- function_definition input @622-647
- function_definition (anonymous) @649-652
- function_definition updateAnnotation @654-662
- function_definition Binding @664-666
- function_definition (anonymous) @668-671
- function_definition ~Binding @673-673
- function_definition (anonymous) @677-680
- function_definition Variant @682-682
- function_definition ~Variant @684-684
- function_definition (anonymous) @688-691
- function_definition Matcher @693-707
- function_definition Matcher @709-710
- function_definition ~Matcher @712-712
- function_definition (anonymous) @716-722
- function_definition getLocalVariablesInternal @725-729
- function_definition getSelectorsInternal @731-735
- function_definition getVariantsInternal @737-741
- function_definition Builder::Builder @743-745
- function_definition Builder::buildSelectorsMessage @748-758
- function_definition Builder::checkDuplicate @760-774
- function_definition (anonymous) @776-791
- function_definition (anonymous) @793-802
- function_definition (anonymous) @807-814
- function_definition (anonymous) @816-825
- function_definition MFDataModel @827-855
- function_definition MFDataModel @857-886
- function_definition MFDataModel @888-888
- function_definition (anonymous) @890-894
- function_definition Builder::build @896-904
- function_definition ~MFDataModel @906-906
- function_definition Builder::~Builder @907-917

### intl/icu/source/i18n/messageformat2_errors.cpp

Blob: `c4a96544fe68b5ebea069e8b4be531d694e0570f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "messageformat2_allocation.h" @12
- include "messageformat2_errors.h" @13
- include "messageformat2_macros.h" @14
- include "uvector.h" @15
- function_definition namespace @17-310
- function_definition setFormattingError @24-26
- function_definition setFormattingError @28-30
- function_definition setBadOption @32-34
- function_definition setRecoverableBadOption @36-38
- function_definition setOperandMismatchError @40-42
- function_definition setDuplicateOptionName @44-46
- function_definition setMissingSelectorAnnotation @48-50
- function_definition setSelectorError @52-54
- function_definition setUnknownFunction @56-58
- function_definition setUnresolvedVariable @60-62
- function_definition DynamicErrors @64-66
- function_definition StaticErrors @68-70
- function_definition StaticErrors @72-78
- function_definition StaticErrors @80-99
- function_definition count @101-104
- function_definition hasError @106-108
- function_definition hasStaticError @110-113
- function_definition (anonymous) @115-118
- function_definition checkErrors @120-162
- function_definition addSyntaxError @164-166
- function_definition addError @168-208
- function_definition addError @210-254
- function_definition checkErrors @256-292
- function_definition (anonymous) @294-297
- function_definition ~StaticErrors @299-299
- function_definition ~DynamicErrors @300-300
- function_definition ~Error @303-303
- function_definition ~Error @306-306
- function_definition ~Error @308-308

### intl/icu/source/i18n/messageformat2_errors.h

Blob: `42cea5b2b123357e7bee8f53a8632c9c65cdb75f`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_data_model_names.h" @24
- include "unicode/unistr.h" @25
- include "uvector.h" @27
- function_definition namespace @29-163
- class_specifier DynamicErrors @38-38
- class_specifier StaticErrors @39-39
- class_specifier Error @43-54
- function_definition Error @45-45
- function_definition Error @46-46
- enum_specifier StaticErrorType @56-64
- enum_specifier DynamicErrorType @66-83
- class_specifier StaticErrors @95-121
- function_definition hasDataModelError @110-110
- function_definition hasSyntaxError @111-111
- function_definition hasMissingSelectorAnnotationError @112-112
- class_specifier DynamicErrors @123-161
- function_definition hasDataModelError @146-146
- function_definition hasFormattingError @147-147
- function_definition hasBadOptionError @148-148
- function_definition hasSelectorError @149-149
- function_definition hasSyntaxError @150-150
- function_definition hasUnknownFunctionError @151-151
- function_definition hasMissingSelectorAnnotationError @152-152
- function_definition hasUnresolvedVariableError @153-153

### intl/icu/source/i18n/messageformat2_evaluation.cpp

Blob: `1a88ece4724f2ee9879d372dd043bd4e35b002b5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "messageformat2_allocation.h" @12
- include "messageformat2_evaluation.h" @13
- include "messageformat2_function_registry_internal.h" @14
- include "messageformat2_macros.h" @15
- include "uvector.h" @16
- function_definition namespace @18-501
- function_definition ResolvedFunctionOption @29-33
- function_definition ~ResolvedFunctionOption @35-35
- function_definition getResolvedFunctionOptions @38-42
- function_definition FunctionOptions @44-49
- function_definition wasSetFromLiteral @52-63
- function_definition getFunctionOption @65-77
- function_definition getStringFunctionOption @79-93
- function_definition (anonymous) @95-101
- function_definition FunctionOptions @103-105
- function_definition ~FunctionOptions @107-112
- function_definition containsOption @114-122
- function_definition mergeOptions @126-156
- function_definition operator< @161-166
- function_definition ~PrioritizedVariant @168-168
- function_definition create @172-180
- function_definition create @182-190
- function_definition (anonymous) @192-196
- function_definition (anonymous) @198-203
- function_definition has @205-208
- function_definition has @210-215
- function_definition ~Environment @217-217
- function_definition ~NonEmptyEnvironment @218-218
- function_definition ~EmptyEnvironment @219-219
- function_definition ~Closure @221-221
- function_definition checkErrors @225-228
- function_definition getGlobal @230-233
- function_definition MessageContext @235-237
- function_definition ~MessageContext @239-239
- function_definition isFallback @244-247
- function_definition hasNullOperand @249-252
- function_definition takeArgument @254-264
- function_definition (anonymous) @266-271
- function_definition getSelector @273-282
- function_definition InternalValue @284-288
- function_definition InternalValue @290-301
- function_definition forceSelection @304-374
- function_definition checkSelectOption @376-393
- function_definition forceFormatting @395-475
- function_definition (anonymous) @477-488
- function_definition ~InternalValue @490-499

### intl/icu/source/i18n/messageformat2_evaluation.h

Blob: `f73b444229f5e42a938b5a6c0dec94fa92c53f44`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_arguments.h" @23
- include "unicode/messageformat2_data_model.h" @24
- include "unicode/messageformat2_function_registry.h" @25
- include "messageformat2_errors.h" @26
- function_definition namespace @30-219
- class_specifier PrioritizedVariant @52-65
- function_definition PrioritizedVariant @54-54
- function_definition PrioritizedVariant @55-55
- function_definition (anonymous) @56-56
- function_definition PrioritizedVariant @61-63
- function_definition comparePrioritizedVariants @67-77
- class_specifier Environment @82-82
- class_specifier Closure @87-106
- function_definition (anonymous) @89-91
- function_definition (anonymous) @92-94
- function_definition Closure @95-95
- function_definition Closure @96-96
- class_specifier Environment @111-118
- class_specifier NonEmptyEnvironment @120-120
- class_specifier EmptyEnvironment @121-133
- function_definition EmptyEnvironment @123-123
- class_specifier NonEmptyEnvironment @135-153
- function_definition NonEmptyEnvironment @146-146
- class_specifier MessageFormatter @158-158
- class_specifier MessageContext @160-178
- function_definition (anonymous) @168-168
- class_specifier InternalValue @183-217
- function_definition (anonymous) @185-185
- function_definition canSelect @186-186
- function_definition InternalValue @207-207

### intl/icu/source/i18n/messageformat2_formattable.cpp

Blob: `0bbecaf25d773e2d1f08fb3023b7f0d9682c9aa5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2_formattable.h" @12
- include "unicode/smpdtfmt.h" @13
- include "messageformat2_allocation.h" @14
- include "messageformat2_function_registry_internal.h" @15
- include "messageformat2_macros.h" @16
- include "limits.h" @18
- function_definition namespace @20-330
- function_definition fallbackToString @27-33
- function_definition (anonymous) @35-38
- function_definition Formattable @40-42
- function_definition forDecimal @44-55
- function_definition getType @57-87
- function_definition getArray @89-101
- function_definition getInt64 @103-121
- function_definition asICUFormattable @123-158
- function_definition ~Formattable @160-160
- function_definition ~FormattableObject @162-162
- function_definition ~FormattedMessage @164-164
- function_definition FormattedValue @166-169
- function_definition FormattedValue @171-174
- function_definition (anonymous) @176-184
- function_definition ~FormattedValue @186-186
- function_definition (anonymous) @188-197
- function_definition (anonymous) @199-201
- function_definition formatNumberWithDefaults @206-208
- function_definition formatNumberWithDefaults @210-212
- function_definition formatNumberWithDefaults @214-216
- function_definition formatNumberWithDefaults @218-220
- function_definition defaultDateTimeInstance @222-230
- function_definition formatWithDefaults @235-294
- function_definition formatToString @298-328

### intl/icu/source/i18n/messageformat2_formatter.cpp

Blob: `6c555ecbc0e2dc974fb51d2a7b5a51330ccda618`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/messageformat2.h" @12
- include "messageformat2_allocation.h" @13
- include "messageformat2_checker.h" @14
- include "messageformat2_errors.h" @15
- include "messageformat2_evaluation.h" @16
- include "messageformat2_function_registry_internal.h" @17
- include "messageformat2_macros.h" @18
- include "messageformat2_parser.h" @19
- include "messageformat2_serializer.h" @20
- include "uvector.h" @21
- function_definition namespace @23-358
- function_definition Builder::clearState @32-36
- function_definition (anonymous) @38-65
- function_definition (anonymous) @69-72
- function_definition (anonymous) @74-77
- function_definition (anonymous) @79-86
- function_definition (anonymous) @88-93
- function_definition Builder::build @100-102
- function_definition Builder::Builder @104-111
- function_definition Builder::~Builder @113-118
- function_definition MessageFormatter @122-181
- function_definition cleanup @183-188
- function_definition (anonymous) @190-202
- function_definition (anonymous) @204-204
- function_definition getPattern @206-212
- function_definition (anonymous) @215-218
- function_definition ~MessageFormatter @220-222
- function_definition getSelector @228-242
- function_definition getFormatter @245-264
- function_definition getDefaultFormatterNameByType @266-273
- function_definition isBuiltInSelector @278-280
- function_definition isBuiltInFormatter @282-284
- function_definition lookupSelectorFactory @290-317
- function_definition lookupFormatterFactory @319-347
- function_definition isCustomFormatter @349-351
- function_definition isCustomSelector @354-356

### intl/icu/source/i18n/messageformat2_function_registry.cpp

Blob: `3e924ce97804a29e89a52825f3fcc64a9b4f27f5`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include <math.h> @12
- include <cmath> @13
- include "unicode/dtptngen.h" @15
- include "unicode/messageformat2.h" @16
- include "unicode/messageformat2_data_model_names.h" @17
- include "unicode/messageformat2_function_registry.h" @18
- include "unicode/normalizer2.h" @19
- include "unicode/simpletz.h" @20
- include "unicode/smpdtfmt.h" @21
- include "charstr.h" @22
- include "double-conversion.h" @23
- include "messageformat2_allocation.h" @24
- include "messageformat2_function_registry_internal.h" @25
- include "messageformat2_macros.h" @26
- include "hash.h" @27
- include "mutex.h" @28
- include "number_types.h" @29
- include "ucln_in.h" @30
- include "uvector.h" @31
- include <inttypes.h> @40
- include <math.h> @41
- function_definition namespace @43-1909
- function_definition ~Formatter @49-49
- function_definition ~Selector @50-50
- function_definition ~FormatterFactory @51-51
- function_definition ~SelectorFactory @52-52
- function_definition Builder::build @54-61
- function_definition (anonymous) @63-69
- function_definition (anonymous) @71-77
- function_definition (anonymous) @79-86
- function_definition Builder::Builder @88-101
- function_definition Builder::~Builder @103-113
- function_definition getFormatter @119-122
- function_definition getDefaultFormatterNameByType @124-132
- function_definition getSelector @134-137
- function_definition hasFormatter @139-141
- function_definition hasSelector @143-145
- function_definition checkFormatter @147-153
- function_definition checkSelector @155-161
- function_definition checkStandard @164-177
- function_definition normalizeNFC @183-201
- function_definition strToDouble @204-218
- function_definition tryStringAsNumber @220-232
- function_definition getInt64Value @234-251
- function_definition MFFunctionRegistry @254-256
- function_definition (anonymous) @258-269
- function_definition cleanup @271-281
- function_definition ~MFFunctionRegistry @284-286
- function_definition inBounds @292-294
- function_definition isDigit @296-298
- function_definition parseDigits @300-308
- function_definition validateNumberLiteral @311-380
- function_definition isInteger @382-396
- function_definition isDigitSizeOption @398-404
- function_definition validateDigitSizeOptions @406-417
- function_definition formatterForOptions @419-566
- function_definition NumberFactory::createFormatter @568-576
- function_definition IntegerFactory::createFormatter @578-586
- function_definition IntegerFactory::~IntegerFactory @588-588
- function_definition notANumber @590-592
- function_definition parseNumberLiteral @594-628
- function_definition digitToChar @630-662
- function_definition Number::maximumFractionDigits @664-682
- function_definition Number::minimumFractionDigits @684-700
- function_definition Number::minimumIntegerDigits @702-713
- function_definition Number::minimumSignificantDigits @715-731
- function_definition Number::maximumSignificantDigits @733-747
- function_definition Number::usePercent @749-760
- function_definition Number::integer @762-764
- function_definition Number::format @766-832
- function_definition Number::~Number @834-834
- function_definition NumberFactory::~NumberFactory @835-835
- function_definition Plural::pluralType @839-855
- function_definition PluralFactory::createSelector @857-871
- function_definition Plural::selectKey @873-970
- function_definition Plural::Plural @972-979
- function_definition Plural::Plural @981-993
- function_definition Plural::~Plural @995-995
- function_definition PluralFactory::~PluralFactory @997-997
- function_definition getStringOption @1001-1014
- function_definition defaultForOption @1017-1024
- function_definition DateTime::getFunctionOption @1033-1052
- function_definition DateTime::getFunctionOption @1055-1077
- function_definition stringToStyle @1079-1100
- function_definition DateTimeFactory::dateTime @1102-1110
- function_definition DateTimeFactory::date @1112-1120
- function_definition DateTimeFactory::time @1122-1130
- function_definition DateTimeFactory::createFormatter @1132-1140
- function_definition mf2_date_parsers_cleanup @1150-1168
- function_definition initDateParsersOnce @1171-1192
- function_definition initDateParsers @1195-1199
- function_definition DateTime::tryPatterns @1204-1216
- function_definition DateTime::tryTimeZonePatterns @1219-1229
- function_definition createTimeZone @1231-1245
- function_definition hasTzOffset @1251-1259
- function_definition DateTime::createDateInfoFromString @1263-1333
- function_definition formatDateWithDefaults @1335-1347
- function_definition DateTime::format @1349-1584
- function_definition DateTimeFactory::~DateTimeFactory @1586-1586
- function_definition DateTime::~DateTime @1587-1587
- function_definition TextFactory::createSelector @1591-1598
- function_definition TextSelector::selectKey @1600-1637
- function_definition TextFactory::~TextFactory @1639-1639
- function_definition TextSelector::~TextSelector @1640-1640
- function_definition TestFormatFactory::createFormatter @1644-1655
- function_definition TestFormatFactory::~TestFormatFactory @1657-1657
- function_definition TestFormat::~TestFormat @1658-1658
- function_definition formattableToNumber @1662-1700
- function_definition TestFormat::testFunctionParameters @1703-1785
- function_definition TestFormat::format @1787-1841
- function_definition TestSelectFactory::~TestSelectFactory @1845-1845
- function_definition TestSelect::~TestSelect @1846-1846
- function_definition TestSelectFactory::createSelector @1848-1860
- function_definition TestSelect::selectKey @1862-1907

### intl/icu/source/i18n/messageformat2_function_registry_internal.h

Blob: `25d2a467502d76cdf2e7855cf979c9a8d715e462`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/datefmt.h" @19
- include "unicode/messageformat2_function_registry.h" @20
- function_definition namespace @22-338
- class_specifier StandardFunctions @81-329
- class_specifier DateTime @95-95
- class_specifier DateTimeFactory @97-117
- function_definition DateTimeFactory @103-103
- enum_specifier DateTimeType @109-113
- function_definition DateTimeFactory @116-116
- class_specifier DateTime @119-153
- function_definition DateTime @128-129
- class_specifier IntegerFactory @159-163
- class_specifier NumberFactory @165-172
- class_specifier Number @174-198
- function_definition Number @183-183
- function_definition Number @184-184
- class_specifier PluralFactory @204-217
- function_definition PluralFactory @213-213
- function_definition PluralFactory @214-214
- function_definition integer @215-215
- class_specifier Plural @219-248
- enum_specifier PluralType @236-240
- function_definition integer @243-243
- class_specifier TextFactory @250-254
- class_specifier TextSelector @256-274
- function_definition TextSelector @273-273
- class_specifier TestFormatFactory @277-282
- function_definition TestFormatFactory @280-280
- class_specifier TestSelect @284-284
- class_specifier TestFormat @286-303
- function_definition TestFormat @294-294
- class_specifier TestSelectFactory @306-311
- function_definition TestSelectFactory @309-309
- class_specifier TestSelect @313-327
- function_definition TestSelect @326-326

### intl/icu/source/i18n/messageformat2_macros.h

Blob: `20e81377d4d5cf3754bf2b202bf8e0cced7d1f91`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/format.h" @19
- include "unicode/unistr.h" @20
- include "plurrule_impl.h" @21
- function_definition namespace @23-95

### intl/icu/source/i18n/messageformat2_parser.cpp

Blob: `879c7024fc9cd185eac6087555ac0f397f055de0`. Grammar: cpp. Status: contains-errors.

- include "unicode/utypes.h" @4
- include "unicode/uniset.h" @12
- include "messageformat2_errors.h" @13
- include "messageformat2_macros.h" @14
- include "messageformat2_parser.h" @15
- include "ucln_in.h" @16
- include "umutex.h" @17
- include "uvector.h" @18
- function_definition namespace @20-2165
- function_definition maybeAdvanceLine @46-53
- function_definition copyContext @73-80
- function_definition translateParseError @82-87
- function_definition setParseError @89-96
- function_definition getImpl @105-107
- function_definition initContentChars @112-132
- function_definition initWhitespace @134-151
- function_definition initBidiControls @153-162
- function_definition initAlpha @164-171
- function_definition initDigits @173-180
- function_definition initNameStartChars @182-229
- function_definition initNameChars @231-252
- function_definition initTextChars @254-276
- function_definition initQuotedChars @278-311
- function_definition initEscapableChars @313-329
- function_definition cleanupMF2ParseUniSets @333-340
- function_definition initMF2ParseUniSets @342-370
- function_definition get @372-382
- function_definition isContentChar @403-405
- function_definition isBidiControl @408-410
- function_definition isWhitespace @413-415
- function_definition isTextChar @417-419
- function_definition isAlpha @421-423
- function_definition isDigit @425-427
- function_definition isNameStart @429-431
- function_definition isNameChar @433-435
- function_definition isUnquotedStart @437-439
- function_definition isQuotedChar @441-443
- function_definition isEscapableChar @445-447
- function_definition isFunctionStart @450-459
- function_definition isAnnotationStart @462-464
- function_definition isLiteralStart @467-469
- function_definition isKeyStart @472-474
- function_definition isDeclarationStart @476-483
- function_definition parseRequiredWS @611-647
- function_definition parseOptionalBidi @649-660
- function_definition parseRequiredWhitespace @666-671
- function_definition parseOptionalWhitespace @676-689
- function_definition parseToken @693-703
- function_definition parseToken @710-723
- function_definition parseTokenWithWhitespace @731-740
- function_definition parseTokenWithWhitespace @748-757
- function_definition parseNameChars @763-780
- function_definition parseName @791-813
- function_definition parseVariableName @821-832
- function_definition parseIdentifier @837-881
- function_definition parseFunction @889-903
- function_definition parseEscapeSequence @914-944
- function_definition parseQuotedLiteral @950-1000
- function_definition parseDigits @1003-1022
- function_definition parseUnquotedLiteral @1026-1040
- function_definition parseLiteral @1045-1062
- function_definition parseAttribute @1070-1103
- function_definition parseOption @1111-1145
- function_definition parseOptions @1158-1238
- function_definition parseAttributes @1245-1291
- function_definition parseAnnotation @1299-1317
- function_definition parseLiteralOrVariableWithAnnotation @1324-1401
- function_definition exprFallback @1407-1411
- function_definition exprFallback @1413-1428
- function_definition parseExpression @1430-1500
- function_definition parseLocalDeclaration @1506-1548
- function_definition parseInputDeclaration @1554-1594
- function_definition parseDeclarations @1602-1625
- function_definition parseTextChar @1633-1649
- function_definition parseKey @1655-1678
- function_definition parseNonEmptyKeys @1685-1760
- function_definition parseQuotedPattern @1762-1771
- function_definition parseMarkup @1777-1852
- function_definition parsePlaceholder @1858-1887
- function_definition parseSimpleMessage @1894-1939
- function_definition parseVariant @1941-1956
- function_definition parseSelectors @1965-2046
- function_definition errorPattern @2054-2077
- function_definition parseBody @2079-2106
- function_definition parse @2111-2161
- function_definition ~Parser @2163-2163

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [e991744b-5751-4d04-9315-e7dbbd02b209.md](e991744b-5751-4d04-9315-e7dbbd02b209.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `a7d32034dee08052c1867d60ac26a1d9d191baaa4694f6e9beea155f5d3a6ef1`.
