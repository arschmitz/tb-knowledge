<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:18:44.114924+00:00","paths":["third_party"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["714f6848978bcac01bda001824ee0baf4cfd2ae38f4a8abb54049ac4a3bbac4c"],"sourceAt":"2026-10-13T04:18:44.114924+00:00","correctionOf":"notes/1054b211-4bdf-4da9-8a15-181ac7e278f8.md"}} -->
# firefox/third_party Python and build syntax map 124

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Python AST parser; no source was executed. Functions and classes have source ranges. Imports are written names, not resolved modules. Build entries list assignments with literal string lists and registration calls. Conditions are not evaluated; listed files are not necessarily built or shipped. Dynamic expressions and included build files need separate analysis. Failed parses remain listed.

### third_party/chromium/build/android/pylib/utils/decorators_test.py

Blob: `f8d9075916ab8c89d9df285578678e98a7edfcc5`. Parse: parsed.

- import unittest @8
- from pylib.utils import decorators @10
- class NoRaiseExceptionDecoratorTest @13-39
- function NoRaiseExceptionDecoratorTest.testFunctionDoesNotRaiseException @15-25
- function NoRaiseExceptionDecoratorTest.testFunctionDoesNotRaiseException.raiseException @19-20
- function NoRaiseExceptionDecoratorTest.testFunctionReturnsCorrectValues @27-39
- function NoRaiseExceptionDecoratorTest.testFunctionReturnsCorrectValues.raiseException @31-32
- function NoRaiseExceptionDecoratorTest.testFunctionReturnsCorrectValues.doesNotRaiseException @35-36
- class MemoizeDecoratorTest @42-100
- function MemoizeDecoratorTest.testFunctionExceptionNotMemoized @44-66
- class MemoizeDecoratorTest.testFunctionExceptionNotMemoized.ExceptionType1 @47-48
- class MemoizeDecoratorTest.testFunctionExceptionNotMemoized.ExceptionType2 @50-51
- function MemoizeDecoratorTest.testFunctionExceptionNotMemoized.raiseExceptions @54-60
- function MemoizeDecoratorTest.testFunctionResultMemoized @68-88
- function MemoizeDecoratorTest.testFunctionResultMemoized.memoized @72-74
- function MemoizeDecoratorTest.testFunctionResultMemoized.notMemoized @77-79
- function MemoizeDecoratorTest.testFunctionMemoizedBasedOnArgs @90-100
- function MemoizeDecoratorTest.testFunctionMemoizedBasedOnArgs.returnValueBasedOnArgsKwargs @94-95

### third_party/chromium/build/android/pylib/utils/device_dependencies.py

Blob: `8bb14cf1781700cc92327705fd27b1e4e89d8d1e`. Parse: parsed.

- import glob @5
- import os @6
- import posixpath @7
- import re @8
- from pylib import constants @10
- function _FilterDataDeps @62-66
- function DevicePathComponentsFor @69-122
- function GetDataDependencies @125-148
- function SubstituteDeviceRootSingle @151-156
- function SubstituteDeviceRoot @159-161
- function ExpandDataDependencies @164-174

### third_party/chromium/build/android/pylib/utils/device_dependencies_test.py

Blob: `136ebd552ada6e57fb629f733a4fc7f37bcd170f`. Parse: parsed.

- import os @6
- import unittest @7
- from pylib import constants @9
- from pylib.utils import device_dependencies @10
- class DevicePathComponentsForTest @13-48
- function DevicePathComponentsForTest.testCheckedInFile @15-21
- function DevicePathComponentsForTest.testOutputDirectoryFile @23-30
- function DevicePathComponentsForTest.testOutputDirectorySubdirFile @32-39
- function DevicePathComponentsForTest.testOutputDirectoryPakFile @41-48
- class SubstituteDeviceRootTest @51-75
- function SubstituteDeviceRootTest.testNoneDevicePath @53-57
- function SubstituteDeviceRootTest.testStringDevicePath @59-63
- function SubstituteDeviceRootTest.testListWithNoneDevicePath @65-69
- function SubstituteDeviceRootTest.testListWithoutNoneDevicePath @71-75

### third_party/chromium/build/android/pylib/utils/dexdump.py

Blob: `0913aad471299db7d984ae71490e23ec78408fa4`. Parse: parsed.

- import os @5
- import re @6
- import shutil @7
- import sys @8
- import tempfile @9
- from xml.etree import ElementTree @10
- from collections import namedtuple @11
- from typing import Dict @12
- from devil.utils import cmd_helper @14
- from pylib import constants @15
- from util import build_utils @18
- function Dump @44-95
- function _ParseAnnotationValues @98-110
- function _ParseAnnotations @113-211
- function _ParseRootNode @214-252
- function _ParsePackageNode @255-284
- function _ParseClassNode @287-313

### third_party/chromium/build/android/pylib/utils/dexdump_test.py

Blob: `2b7c72866db86596c2327dba1d69bf1577976c58`. Parse: parsed.

- import unittest @6
- from xml.etree import ElementTree @7
- from pylib.utils import dexdump @9
- class DexdumpXMLParseTest @17-203
- function DexdumpXMLParseTest.testParseAnnotations @19-65
- function DexdumpXMLParseTest.testParseRootXmlNode @67-150
- function DexdumpXMLParseTest.testParsePackageNode @152-182
- function DexdumpXMLParseTest.testParseClassNode @184-203

### third_party/chromium/build/android/pylib/utils/gold_utils.py

Blob: `316cdc00c2dba5109ebd5f027aa469b0db7e3d18`. Parse: parsed.

- import os @9
- import shutil @10
- import time @11
- from devil.utils import cmd_helper @13
- from pylib.base.output_manager import Datatype @14
- from pylib.constants import host_paths @15
- from pylib.utils import repo_utils @16
- from skia_gold_common import skia_gold_session @19
- from skia_gold_common import skia_gold_session_manager @20
- from skia_gold_common import skia_gold_properties @21
- class AndroidSkiaGoldSession @24-70
- function AndroidSkiaGoldSession._StoreDiffLinks @25-64
- function AndroidSkiaGoldSession._RunCmdForRcAndOutput @67-70
- function _GetTimestamp @73-74
- class AndroidSkiaGoldSessionManager @77-81
- function AndroidSkiaGoldSessionManager.GetSessionClass @80-81
- class AndroidSkiaGoldProperties @84-87
- function AndroidSkiaGoldProperties._GetGitOriginMainHeadSha1 @86-87

### third_party/chromium/build/android/pylib/utils/gold_utils_test.py

Blob: `1f1ec21a2f9953e4e90904ea1651d5ebf6cd25ca`. Parse: parsed.

- import contextlib @9
- import os @10
- import tempfile @11
- import unittest @12
- from pylib.constants import host_paths @14
- from pylib.utils import gold_utils @15
- from skia_gold_common import unittest_utils @18
- import mock @20
- from pyfakefs import fake_filesystem_unittest @21
- function assertArgWith @26-28
- class AndroidSkiaGoldSessionDiffTest @31-65
- function AndroidSkiaGoldSessionDiffTest.setUp @32-35
- function AndroidSkiaGoldSessionDiffTest.test_commandCommonArgs @38-65
- class AndroidSkiaGoldSessionDiffLinksTest @68-209
- class AndroidSkiaGoldSessionDiffLinksTest.FakeArchivedFile @69-74
- function AndroidSkiaGoldSessionDiffLinksTest.FakeArchivedFile.__init__ @70-71
- function AndroidSkiaGoldSessionDiffLinksTest.FakeArchivedFile.Link @73-74
- class AndroidSkiaGoldSessionDiffLinksTest.FakeOutputManager @76-83
- function AndroidSkiaGoldSessionDiffLinksTest.FakeOutputManager.__init__ @77-78
- function AndroidSkiaGoldSessionDiffLinksTest.FakeOutputManager.ArchivedTempfile @81-83
- function AndroidSkiaGoldSessionDiffLinksTest.setUp @85-91
- function AndroidSkiaGoldSessionDiffLinksTest.test_outputManagerUsed @93-124
- function AndroidSkiaGoldSessionDiffLinksTest.test_diffLinksDoNotClobber @126-209
- function AndroidSkiaGoldSessionDiffLinksTest.test_diffLinksDoNotClobber.side_effect @129-131

### third_party/chromium/build/android/pylib/utils/google_storage_helper.py

Blob: `27af7096259cc282e0307681c3f317f3a01befc5`. Parse: parsed.

- import logging @12
- import os @13
- import sys @14
- import time @15
- from urllib.parse import urlparse @17
- from urlparse import urlparse @19
- from pylib.constants import host_paths @21
- from pylib.utils import decorators @22
- from devil.utils import cmd_helper @26
- function upload @35-65
- function read_from_link @69-74
- function exists @78-84
- function unique_name @88-102
- function get_url_link @105-120
- function _format_bucket_name @123-128

### third_party/chromium/build/android/pylib/utils/instrumentation_tracing.py

Blob: `3c9304e909150a99fa5821b20419bf6976f4bd1b`. Parse: parsed.

- import contextlib @17
- import functools @18
- import inspect @19
- import os @20
- import re @21
- import sys @22
- import threading @23
- from py_trace_event import trace_event @25
- class _TraceArguments @32-55
- function _TraceArguments.__init__ @33-35
- function _TraceArguments._safeStringify @38-46
- function _TraceArguments.add @48-52
- function _TraceArguments.__repr__ @54-55
- function _shouldTrace @60-103
- function _generate_trace_function @105-167
- function _generate_trace_function.traceFunction @115-165
- function no_tracing @170-181
- function no_tracing.wrapper @172-180
- function start_instrumenting @184-190
- function stop_instrumenting @193-197
- function Instrument @201-206

### third_party/chromium/build/android/pylib/utils/local_utils.py

Blob: `a7d39d6a2305fc5b86aaa824c0829c77e6deba13`. Parse: parsed.

- import os @6
- function IsOnSwarming @9-19

### third_party/chromium/build/android/pylib/utils/logdog_helper.py

Blob: `e1562f51522c4c07bbcd210de1b1066604697d6c`. Parse: parsed.

- import logging @7
- import os @8
- import sys @9
- from pylib import constants @11
- from pylib.utils import decorators @12
- from logdog import bootstrap @18
- function text @24-39
- function open_text @45-55
- function binary @61-75
- function get_viewer_url @81-90
- function get_logdog_client @94-96

### third_party/chromium/build/android/pylib/utils/logging_utils.py

Blob: `fdb0fa6a8b4248eb549a84ac88e4234095d019b1`. Parse: parsed.

- import contextlib @5
- import logging @6
- import os @7
- from pylib.constants import host_paths @9
- import colorama @15
- class _ColorFormatter @22-48
- function _ColorFormatter.__init__ @33-36
- function _ColorFormatter.format @39-41
- function _ColorFormatter.Colorize @43-48
- class ColorStreamHandler @51-98
- function ColorStreamHandler.__init__ @66-69
- function ColorStreamHandler.is_tty @72-77
- function ColorStreamHandler.setFormatter @80-83
- function ColorStreamHandler.MakeDefault @86-98
- function OverrideColor @102-118
- function SuppressLogging @122-140

### third_party/chromium/build/android/pylib/utils/maven_downloader.py

Blob: `fd9d97304f1d64f1e440ec4fd6cc1da0f5276e95`. Parse: parsed.

- import errno @6
- import logging @7
- import os @8
- import shutil @9
- import sys @10
- import devil_chromium @13
- from devil.utils import cmd_helper @14
- from devil.utils import parallelizer @15
- function _MakeDirsIfAbsent @18-23
- class MavenDownloader @26-71
- function MavenDownloader.__init__ @45-48
- function MavenDownloader.Install @50-59
- function MavenDownloader.repo_path @62-63
- function MavenDownloader.remote_url @66-67
- function MavenDownloader.debug @70-71
- class _SingleArtifactDownloader @74-140
- function _SingleArtifactDownloader.__init__ @79-82
- function _SingleArtifactDownloader.Run @84-94
- function _SingleArtifactDownloader._InstallArtifact @96-104
- function _SingleArtifactDownloader._DownloadArtifact @106-131
- function _SingleArtifactDownloader._ImportArtifact @133-140

### third_party/chromium/build/android/pylib/utils/repo_utils.py

Blob: `4e1b7a57c3d63c0b1f42309a233d28aff4a0e0fc`. Parse: parsed.

- from devil.utils import cmd_helper @5
- function GetGitHeadSHA1 @8-16
- function GetGitOriginMasterHeadSHA1 @19-22
- function GetGitOriginMainHeadSHA1 @25-28

### third_party/chromium/build/android/pylib/utils/simpleperf.py

Blob: `f096093c7f1ed38d6035450401e6c9087e1c1a31`. Parse: parsed.

- import contextlib @5
- import logging @6
- import os @7
- import shutil @8
- import subprocess @9
- import sys @10
- import tempfile @11
- from devil import devil_env @13
- from devil.android import device_signal,device_errors @14
- from devil.android.sdk import version_codes @15
- from pylib import constants @16
- function _ProcessType @19-27
- function _GetSpecifiedPID @30-67
- function _ThreadsForProcess @70-95
- function _ThreadType @98-112
- function _GetSpecifiedTID @115-135
- function PrepareDevice @138-145
- function InstallSimpleperf @148-156
- function RunSimpleperf @160-229
- function ConvertSimpleperfToPprof @232-293

### third_party/chromium/build/android/pylib/utils/test_filter.py

Blob: `c532f324e175c14e70e922910a7b7d8611e8d1c4`. Parse: parsed.

- import os @5
- import re @6
- function ParseFilterFile @13-36
- function AddFilterOptions @39-69
- function AppendPatternsToFilter @72-101
- function HasPositivePatterns @104-110
- function InitializeFiltersFromArgs @113-145

### third_party/chromium/build/android/pylib/utils/test_filter_test.py

Blob: `fa0718257b0683862d789dab5acec380c33edde8`. Parse: parsed.

- import argparse @6
- import os @7
- import sys @8
- import tempfile @9
- import unittest @10
- from pylib.utils import test_filter @12
- class ParseFilterFileTest @14-55
- function ParseFilterFileTest.testParseFilterFile_commentsAndBlankLines @16-26
- function ParseFilterFileTest.testParseFilterFile_onlyPositive @28-35
- function ParseFilterFileTest.testParseFilterFile_onlyNegative @37-44
- function ParseFilterFileTest.testParseFilterFile_positiveAndNegative @46-55
- class InitializeFilterFromArgsTest @58-153
- function InitializeFilterFromArgsTest.testInitializeBasicFilter @60-68
- function InitializeFilterFromArgsTest.testInitializeJavaStyleFilter @70-78
- function InitializeFilterFromArgsTest.testInitializeBasicIsolatedScript @80-88
- function InitializeFilterFromArgsTest.testFilterArgWithPositiveFilterInFilterFile @92-104
- function InitializeFilterFromArgsTest.testFilterFileWithPositiveFilterInFilterArg @108-121
- function InitializeFilterFromArgsTest.testPositiveFilterInBothFileAndArg @125-137
- function InitializeFilterFromArgsTest.testFilterArgWithFilterFileAllNegative @141-153
- class AppendPatternsToFilter @156-230
- function AppendPatternsToFilter.testAllEmpty @157-160
- function AppendPatternsToFilter.testAppendOnlyPositiveToEmptyFilter @162-165
- function AppendPatternsToFilter.testAppendOnlyNegativeToEmptyFilter @167-171
- function AppendPatternsToFilter.testAppendToEmptyFilter @173-176
- function AppendPatternsToFilter.testAppendToPositiveOnlyFilter @178-182
- function AppendPatternsToFilter.testAppendToNegativeOnlyFilter @184-188
- function AppendPatternsToFilter.testAppendPositiveToFilter @190-194
- function AppendPatternsToFilter.testAppendNegativeToFilter @196-200
- function AppendPatternsToFilter.testAppendBothToFilter @202-207
- function AppendPatternsToFilter.testAppendMultipleToFilter @209-214
- function AppendPatternsToFilter.testRepeatedAppendToFilter @216-223
- function AppendPatternsToFilter.testAppendHashSeparatedPatternsToFilter @225-230
- class HasPositivePatterns @233-252
- function HasPositivePatterns.testEmpty @234-237
- function HasPositivePatterns.testHasOnlyPositive @239-242
- function HasPositivePatterns.testHasOnlyNegative @244-247
- function HasPositivePatterns.testHasBoth @249-252

### third_party/chromium/build/android/pylib/utils/time_profile.py

Blob: `54b96c290a1da2fb9cb756344a3764bd8f3eb7f2`. Parse: parsed.

- import logging @5
- import time @6
- class TimeProfile @9-45
- function TimeProfile.__init__ @12-16
- function TimeProfile.Start @18-20
- function TimeProfile.GetDelta @22-31
- function TimeProfile.LogResult @33-35
- function TimeProfile.Stop @37-45

### third_party/chromium/build/android/pylib/utils/xvfb.py

Blob: `6ab24afc75d187da229338272c19fa43ee9d5d6b`. Parse: parsed.

- import os @7
- import signal @8
- import subprocess @9
- import sys @10
- import time @11
- function _IsLinux @14-16
- class Xvfb @19-58
- function Xvfb.__init__ @22-23
- function Xvfb.Start @25-48
- function Xvfb.Stop @50-58

### third_party/chromium/build/android/resource_sizes.py

Blob: `5d7bc6ac00159e106dda18da058a9fd58a3bd3dc`. Parse: parsed.

- import argparse @12
- import collections @13
- from contextlib import contextmanager @14
- import json @15
- import logging @16
- import os @17
- import posixpath @18
- import re @19
- import struct @20
- import sys @21
- import tempfile @22
- import zipfile @23
- import zlib @24
- import devil_chromium @26
- from devil.android.sdk import build_tools @27
- from devil.utils import cmd_helper @28
- from devil.utils import lazy @29
- import method_count @30
- from pylib import constants @31
- from pylib.constants import host_paths @32
- from lib.common import perf_tests_results_helper @42
- from lib.results import result_sink @43
- from lib.results import result_types @44
- from tracing.value import convert_chart_json @47
- from util import build_utils @50
- class _AccumulatingReporter @91-101
- function _AccumulatingReporter.__init__ @92-93
- function _AccumulatingReporter.__call__ @95-96
- function _AccumulatingReporter.DumpReports @98-101
- class _ChartJsonReporter @104-124
- function _ChartJsonReporter.__init__ @105-108
- function _ChartJsonReporter.__call__ @110-115
- function _ChartJsonReporter.SynthesizeTotals @117-124
- function _PercentageDifference @127-130
- function _ReadZipInfoExtraFieldLength @133-141
- function _MeasureApkSignatureBlock @144-165
- function _RunReadobj @168-170
- function _ExtractLibSectionSizesFromApk @173-191
- function _CreateSectionNameSizeMap @194-204
- function _ParseManifestAttributes @207-229
- function _ParseManifestAttributes.parse_attr @212-220
- function _NormalizeLanguagePaks @232-239
- function _NormalizeResourcesArsc @242-277
- function _CreateResourceIdValueMap @280-285
- function _RunAaptDumpResources @288-294
- class _FileGroup @297-337
- function _FileGroup.__init__ @300-303
- function _FileGroup.AddZipInfo @305-307
- function _FileGroup.AllEntries @309-310
- function _FileGroup.GetNumEntries @312-313
- function _FileGroup.FindByPattern @315-317
- function _FileGroup.FindLargest @319-322
- function _FileGroup.ComputeZippedSize @324-325
- function _FileGroup.ComputeUncompressedSize @327-328
- function _FileGroup.ComputeExtractedSize @330-334
- function _FileGroup.ComputeInstallSize @336-337
- function _AnalyzeInternal @340-657
- function _AnalyzeInternal.make_group @354-357
- function _AnalyzeInternal.has_no_extension @359-360
- function _CalculateCompressedSize @660-668
- function Unzip @672-680
- function _ConfigOutDir @683-693
- function _IterSplits @696-705
- function _ExtractToTempFile @708-712
- function _AnalyzeApkOrApks @715-782
- function _AnalyzeApkOrApks.do_measure @740-756
- function _ResourceSizes @785-809
- function _DumpChartJson @812-842
- function main @845-944

### third_party/chromium/build/android/screenshot.py

Blob: `6366e85555aebced02dcbd7ab3c07ccb17f71c46`. Parse: parsed.

- import sys @6
- import devil_chromium @8
- from devil.android.tools import screenshot @9

### third_party/chromium/build/android/stacktrace/crashpad_stackwalker.py

Blob: `9703b7c88da73556e536615ed3b35c682c3bd78c`. Parse: parsed.

- import argparse @11
- import logging @12
- import os @13
- import posixpath @14
- import re @15
- import sys @16
- import shutil @17
- import subprocess @18
- import tempfile @19
- import devil_chromium @24
- from devil.android import device_utils @25
- from devil.utils import timeout_retry @26
- function _CreateSymbolsDir @29-56
- function _ChooseLatestCrashpadDump @59-73
- function _ExtractLibraryNamesFromDump @76-113
- function main @116-171
- function main.CrashpadDumpExists @146-147

### third_party/chromium/build/android/stacktrace/java_deobfuscate.py

Blob: `0a3717964b5584cbc57d62f4a29dbb7d9640ffb8`. Parse: parsed.

- import os @11
- import sys @12
- function main @17-33

### third_party/chromium/build/android/stacktrace/java_deobfuscate_test.py

Blob: `de236efa31d50d295693b911c15fef82dcc0f8fa`. Parse: parsed.

- import argparse @8
- import os @9
- import subprocess @10
- import sys @11
- import tempfile @12
- import unittest @13
- class JavaDeobfuscateTest @103-164
- function JavaDeobfuscateTest.__init__ @105-107
- function JavaDeobfuscateTest.setUp @109-112
- function JavaDeobfuscateTest.tearDown @114-116
- function JavaDeobfuscateTest._testImpl @118-137
- function JavaDeobfuscateTest.testNoPrefix @139-140
- function JavaDeobfuscateTest.testThreadtimePrefix @142-143
- function JavaDeobfuscateTest.testStandardPrefix @145-146
- function JavaDeobfuscateTest.testStandardPrefixWithPadding @148-149
- function JavaDeobfuscateTest.testIndefiniteHang @152-164

### third_party/chromium/build/android/stacktrace/stackwalker.py

Blob: `ad60e998281da1d31d5294ff40284a2eed202f23`. Parse: parsed.

- import argparse @8
- import os @9
- import re @10
- import sys @11
- import tempfile @12
- from pylib.constants import host_paths @16
- from devil.utils import cmd_helper @20
- function GetMicroDumps @37-61
- function SymbolizeMicroDump @64-82
- function AddArguments @85-93
- function _PrintAndLog @96-99
- function main @102-132

### third_party/chromium/build/android/test/incremental_javac_gn/incremental_javac_test_android_library.py

Blob: `28bd064a3c95362b77ff618e8fa708d004037856`. Parse: parsed.

- import argparse @12
- import os @13
- import pathlib @14
- import subprocess @15
- import shutil @16
- import platform @17
- function _raise_command_exception @31-45
- function _run_command @48-59
- function _copy_and_append_gn_args @62-79
- function _run_gn @82-85
- function main @88-157

### third_party/chromium/build/android/test_runner.py

Blob: `db10bc3570d487a39aac9b0aab5fffb4786bfabc`. Parse: parsed.

- from __future__ import absolute_import @9
- import argparse @10
- import collections @11
- import contextlib @12
- import io @13
- import itertools @14
- import logging @15
- import os @16
- import re @17
- import shlex @18
- import shutil @19
- import signal @20
- import sys @21
- import tempfile @22
- import threading @23
- import traceback @24
- import unittest @25
- import _strptime @30
- from pylib.constants import host_paths @33
- from devil import base_error @38
- from devil.utils import reraiser_thread @39
- from devil.utils import run_tests_helper @40
- from pylib import constants @42
- from pylib.base import base_test_result @43
- from pylib.base import environment_factory @44
- from pylib.base import output_manager @45
- from pylib.base import output_manager_factory @46
- from pylib.base import test_instance_factory @47
- from pylib.base import test_run_factory @48
- from pylib.results import json_results @49
- from pylib.results import report_results @50
- from pylib.results.presentation import test_results_presentation @51
- from pylib.utils import local_utils @52
- from pylib.utils import logdog_helper @53
- from pylib.utils import logging_utils @54
- from pylib.utils import test_filter @55
- from py_utils import contextlib_ext @57
- from lib.proto import exception_recorder @59
- from lib.proto import measures @60
- from lib.results import result_sink @61
- function _RealPath @69-73
- function AddTestLauncherOptions @76-110
- function AddCommandLineOptions @113-135
- function AddTracingOptions @138-149
- function AddCommonOptions @152-279
- class AddCommonOptions.FastLocalDevAction @205-213
- function AddCommonOptions.FastLocalDevAction.__call__ @206-213
- function ProcessCommonOptions @282-294
- function AddDeviceOptions @297-368
- function AddEmulatorOptions @371-400
- function AddGTestOptions @403-496
- function AddInstrumentationTestOptions @499-708
- function AddSkiaGoldTestOptions @711-769
- function AddHostsideTestOptions @772-824
- function AddJUnitTestOptions @827-879
- function AddLinkerTestOptions @882-889
- function AddMonkeyTestOptions @892-919
- function AddPythonTestOptions @922-931
- function _CreateClassToFileNameDict @934-956
- function _RunPythonTests @959-973
- function RunTestsCommand @981-1004
- function _SinkTestResult @1007-1041
- function UploadTestScriptRecords @1055-1099
- function RunTestsInPlatformMode @1102-1380
- function RunTestsInPlatformMode.infra_error @1104-1106
- function RunTestsInPlatformMode.unexpected_sigterm @1114-1130
- function RunTestsInPlatformMode.json_finalizer @1155-1164
- function RunTestsInPlatformMode.json_writer @1167-1201
- function RunTestsInPlatformMode.upload_logcats_file @1204-1219
- function RunTestsInPlatformMode.test_script_records_uploader @1230-1234
- function _LogRerunStatement @1383-1440
- function DumpThreadStacks @1443-1445
- function main @1448-1560

### third_party/chromium/build/android/test_runner_test.py

Blob: `b2a75a93be53c9f1a02612e5963fae939f85f313`. Parse: parsed.

- import unittest @7
- from unittest import mock @9
- import test_runner @11
- class UploadTestScriptRecordsTest @14-80
- function UploadTestScriptRecordsTest.setUp @16-19
- function UploadTestScriptRecordsTest.testNoRecords @21-28
- function UploadTestScriptRecordsTest.testUploadSuccess @30-37
- function UploadTestScriptRecordsTest.testUploadSuccessWithClearStacktrace @39-51
- function UploadTestScriptRecordsTest.testUploadSuccessWithClearRecords @53-66
- function UploadTestScriptRecordsTest.testUploadFailure @68-80

### third_party/chromium/build/android/test_wrapper/logdog_wrapper.py

Blob: `547955aa54d1786790800a32fdefb8db34f415c7`. Parse: parsed.

- import argparse @8
- import contextlib @9
- import json @10
- import logging @11
- import os @12
- import shutil @13
- import signal @14
- import subprocess @15
- import sys @16
- from devil.utils import signal_handler @24
- from devil.utils import timeout_retry @25
- from py_utils import tempfile_ext @26
- function CommandParser @33-52
- function CreateStopTestsMethod @55-59
- function CreateStopTestsMethod.StopTests @56-58
- function NoLeakingProcesses @63-73
- function GetProjectFromLuciContext @76-95
- function main @98-168
- function main.logdog_stopped @157-158

### third_party/chromium/build/android/tombstones.py

Blob: `430b284d1712ebabf1488ffbddd45ad7c017cb78`. Parse: parsed.

- import argparse @12
- import datetime @13
- import logging @14
- import os @15
- import sys @16
- from multiprocessing.pool import ThreadPool @18
- import devil_chromium @20
- from devil.android import device_denylist @22
- from devil.android import device_errors @23
- from devil.android import device_utils @24
- from devil.utils import run_tests_helper @25
- from pylib import constants @26
- from pylib.symbols import stack_symbolizer @27
- function _ListTombstones @33-55
- function _GetDeviceDateTime @58-70
- function _GetTombstoneData @73-84
- function _EraseTombstone @87-96
- function _ResolveTombstone @99-113
- function _ResolveTombstones @116-138
- function _GetTombstonesForDevice @141-185
- function ClearAllTombstones @188-199
- function ResolveTombstones @202-223
- function main @226-276

### third_party/chromium/build/android/update_deps/update_third_party_deps.py

Blob: `50c0e225f095c59092a969e1211d167710655c74`. Parse: parsed.

- import argparse @12
- import logging @13
- import os @14
- import sys @15
- from pylib import constants @20
- from pylib.constants import host_paths @21
- import download_from_google_storage @26
- import upload_to_google_storage @27
- function _AddBasicArguments @30-41
- function _CheckPaths @44-53
- function _CheckFileList @56-64
- function _PurgeSymlinks @67-72
- function Upload @75-88
- function Download @91-109
- function main @112-138

### third_party/chromium/build/android/update_verification.py

Blob: `b6e34e68a2b7508aeddb7be140aea73ff5c3d3a5`. Parse: parsed.

- import argparse @27
- import logging @28
- import sys @29
- import devil_chromium @31
- from devil.android import apk_helper @33
- from devil.android import device_denylist @34
- from devil.android import device_errors @35
- from devil.android import device_utils @36
- from devil.utils import run_tests_helper @37
- function CreateAppData @40-45
- function TestUpdate @47-60
- function main @62-111

### third_party/chromium/build/android/video_recorder.py

Blob: `39387797536ec2e4e498193c70d862468cbc510b`. Parse: parsed.

- import sys @6
- import devil_chromium @8
- from devil.android.tools import video_recorder @9

### third_party/chromium/build/apple/plist_util.py

Blob: `016a06ac4a5e6277a098248033cd1564596ab061`. Parse: parsed.

- import argparse @5
- import codecs @6
- import plistlib @7
- import os @8
- import re @9
- import subprocess @10
- import sys @11
- import tempfile @12
- import shlex @13
- class SubstitutionError @28-34
- function SubstitutionError.__init__ @29-31
- function SubstitutionError.__str__ @33-34
- function InterpolateString @37-68
- function InterpolateString.repl @50-64
- function Interpolate @71-89
- function LoadPList @92-95
- function SavePList @98-110
- function MergePList @113-139
- class Action @142-149
- function Action.Register @146-149
- class MergeAction @152-180
- function MergeAction._Register @159-173
- function MergeAction._Execute @176-180
- class SubstituteAction @183-221
- function SubstituteAction._Register @190-212
- function SubstituteAction._Execute @215-221
- function Main @224-232

### third_party/chromium/build/apple/tweak_info_plist.py

Blob: `2e6c4a752b413ec377976dc1979f10f8db5098fe`. Parse: parsed.

- import optparse @24
- import os @25
- import plistlib @26
- import re @27
- import subprocess @28
- import sys @29
- import tempfile @30
- function _WritePlistIfChanged @37-57
- function _GetOutput @60-65
- function _RemoveKeys @68-74
- function _ApplyVersionOverrides @77-93
- function _GetVersion @96-106
- function _AddVersionKeys @109-142
- function _DoSCMKeys @145-166
- function _AddBreakpadKeys @169-182
- function _RemoveBreakpadKeys @185-189
- function _TagSuffixes @192-207
- function _AddKeystoneKeys @210-222
- function _RemoveKeystoneKeys @225-232
- function _AddGTMKeys @235-241
- function _RemoveGTMKeys @244-246
- function _AddPrivilegedHelperId @249-252
- function _RemovePrivilegedHelperId @255-256
- function Main @259-446

### third_party/chromium/build/apple/write_pkg_info.py

Blob: `2f59c2f732fa0c3c7c3244656f645892bed15a02`. Parse: parsed.

- import argparse @5
- import os @6
- import plist_util @7
- import sys @8
- function Main @15-48

### third_party/chromium/build/apple/xcrun.py

Blob: `011dd477fabd193c9d24b31f1f97b04ba8c6a30c`. Parse: parsed.

- import argparse @11
- import os @12
- import subprocess @13
- import sys @14
- function xcrun @17-38
- function main @41-48

### third_party/chromium/build/autoroll/extract_and_commit_util.py

Blob: `537ec4a5d23c3e8b0a8db3e99fbde6c38c9abe53`. Parse: parsed.

- import argparse @6
- import os @7
- import pathlib @8
- import shutil @9
- import subprocess @10
- import sys @11
- from typing import List @12
- import zipfile @13
- function _HasChanges @20-23
- function main @26-74

### third_party/chromium/build/autoroll/fetch_util.py

Blob: `317558596564d8d1808c37489e6c24037313398b`. Parse: parsed.

- import hashlib @5
- import json @6
- import pathlib @7
- import os @8
- import subprocess @9
- import zipfile @10
- import re @11
- function generate_version_map_str @25-49
- function fill_template @52-81
- function write_cipd_yaml @84-128
- function create_to_commit_zip @131-164
- function run_fetch_all @167-181

### third_party/chromium/build/check_gn_headers.py

Blob: `60beb6dff6b5534b22231c0b58ce77a02569145a`. Parse: parsed.

- import argparse @12
- import json @13
- import os @14
- import re @15
- import shutil @16
- import subprocess @17
- import sys @18
- import tempfile @19
- from multiprocessing import Process,Queue @20
- function IsSisoUsed @30-31
- function GetHeadersFromNinja @34-64
- function GetHeadersFromNinja.NinjaSource @37-57
- function ParseNinjaDepsOutput @67-97
- function GetHeadersFromGN @100-122
- function ParseGNProjectJSON @125-143
- function GetDepsPrefixes @146-163
- function IsBuildClean @166-176
- function ParseAllowlist @179-185
- function FilterOutDepsedRepo @188-189
- function GetNonExistingFiles @192-197
- function main @200-326
- function main.DumpJson @202-205
- function main.PrintError @207-209

### third_party/chromium/build/check_gn_headers_unittest.py

Blob: `ab1a250eb403d9aaceaa597a8ccb1d599e78c48d`. Parse: parsed.

- import logging @6
- import json @7
- import unittest @8
- import check_gn_headers @9
- class CheckGnHeadersTest @64-96
- function CheckGnHeadersTest.testNinja @65-74
- function CheckGnHeadersTest.testGn @76-86
- function CheckGnHeadersTest.testAllowlist @88-96

### third_party/chromium/build/check_return_value.py

Blob: `2337e962da1ed175e91a23d102f73664a0915e2a`. Parse: parsed.

- import os @10
- import subprocess @11
- import sys @12

### third_party/chromium/build/chromeos/PRESUBMIT.py

Blob: `2455a0529b43c2cb84b882b1e22f40caf2133ed1`. Parse: parsed.

- function CommonChecks @13-24
- function CheckChangeOnUpload @27-28
- function CheckChangeOnCommit @31-32

### third_party/chromium/build/chromeos/embed_sections.py

Blob: `b6d4df5e6bc428ae75bf4e924317cd6566a2d431`. Parse: parsed.

- import argparse @13
- import os @14
- import subprocess @15
- import sys @16
- import shutil @17
- function parse_endianess @35-43
- function assert_elf_type @46-53
- function parse_section_info @56-64
- function create_symbol_map @67-98
- function overwrite_variable @101-108
- function main @111-150

### third_party/chromium/build/chromeos/generate_skylab_tast_filter.py

Blob: `19c469eba567bcdcad9c398d21959149cc3bffba`. Parse: parsed.

- import argparse @7
- import json @8
- import os @9
- import re @10
- import sys @11
- function build_filter_file @14-75
- function main @78-124

### third_party/chromium/build/chromeos/generate_skylab_tast_filter_test.py

Blob: `e416842883afedb49a37c77fd776977b800128d9`. Parse: parsed.

- import unittest @7
- from unittest import mock @8
- import generate_skylab_tast_filter @10
- class GenerateSkylabTastFilterTest @28-174
- function GenerateSkylabTastFilterTest.testTastExpr @30-40
- function GenerateSkylabTastFilterTest.testTastExprAndDisableTests @42-58
- function GenerateSkylabTastFilterTest.testEnableTests @60-73
- function GenerateSkylabTastFilterTest.testTastControlWithTastExpr @75-92
- function GenerateSkylabTastFilterTest.testTastControlWithTastExprAndDisabledTests @94-122
- function GenerateSkylabTastFilterTest.testTastControlWithTastExprAndEnabledTests @124-147
- function GenerateSkylabTastFilterTest.testTastControlWithEnabledTests @149-174

### third_party/chromium/build/chromeos/test_runner.py

Blob: `dd27ab2d2a968ee637686688d78c56522eb264d9`. Parse: parsed.

- import argparse @7
- import collections @8
- import json @9
- import logging @10
- import os @11
- import re @12
- import shutil @13
- import signal @14
- import socket @15
- import sys @16
- import tempfile @17
- import dateutil.parser @21
- import jsonlines @22
- import psutil @23
- from pylib.base import base_test_result @31
- from pylib.results import json_results @32
- from lib.results import result_sink @36
- import subprocess @38
- class TestFormatError @61-62
- class RemoteTest @65-245
- function RemoteTest.__init__ @81-132
- function RemoteTest.suite_name @135-136
- function RemoteTest.test_cmd @139-140
- function RemoteTest.write_test_script_to_disk @142-156
- function RemoteTest.write_runtime_files_to_disk @158-164
- function RemoteTest.run_test @166-215
- function RemoteTest.run_test._kill_child_procs @173-182
- function RemoteTest.post_run @217-219
- function RemoteTest.get_artifacts @222-245
- class TastTest @248-460
- function TastTest.__init__ @250-274
- function TastTest.suite_name @277-278
- function TastTest.build_test_command @280-344
- function TastTest.post_run @346-428
- function TastTest._maybe_handle_perf_results @430-460
- class GTestTest @463-719
- function GTestTest.__init__ @478-496
- function GTestTest.suite_name @499-500
- function GTestTest.build_test_command @502-694
- function GTestTest._read_runtime_files @696-710
- function GTestTest.post_run @712-719
- function device_test @722-738
- function host_cmd @741-806
- function get_cros_hostname_from_bot_id @809-814
- function get_cros_hostname @817-829
- function setup_env @832-847
- function add_common_args @850-933
- function main @935-1115

### third_party/chromium/build/chromeos/test_runner_test.py

Blob: `f48179b292e9aa7437ef8bf4332deb688fd25b6c`. Parse: parsed.

- import json @6
- import os @7
- import shutil @8
- import sys @9
- import tempfile @10
- from textwrap import dedent @11
- import unittest @12
- import mock @16
- from parameterized import parameterized @17
- import test_runner @19
- class TestRunnerTest @30-51
- function TestRunnerTest.setUp @32-39
- function TestRunnerTest.tearDown @41-44
- function TestRunnerTest.safeAssertItemsEqual @46-51
- class TastTests @54-217
- function TastTests.get_common_tast_args @56-68
- function TastTests.get_common_tast_expectations @70-98
- function TastTests.test_tast_gtest_filter @100-120
- function TastTests.test_tast_attr_expr @127-145
- function TastTests.test_tast_with_vars @152-170
- function TastTests.test_tast_retries @177-194
- function TastTests.test_tast @201-217
- class GTestTest @220-377
- function GTestTest.test_gtest @230-351
- function GTestTest.test_gtest_with_vpython @353-377
- class HostCmdTests @380-436
- function HostCmdTests.test_host_cmd @388-436

### third_party/chromium/build/cipd/cipd_from_file.py

Blob: `979b2b5388952f3d3ac723fce2e2a8190e22c076`. Parse: parsed.

- import argparse @7
- import os @8
- function _ParseFilesCfg @11-18
- function _Process @21-39
- function main @42-61

### third_party/chromium/build/clobber.py

Blob: `99825acf7a30dab6a56898b305e21f7b441ab74f`. Parse: parsed.

- import argparse @8
- import os @9
- import shutil @10
- import subprocess @11
- import sys @12
- function extract_gn_build_commands @15-35
- function _rmtree @38-44
- function _clean_dir @47-54
- function delete_build_dir @57-118
- function clobber @121-129
- function main @132-137

### third_party/chromium/build/clobber_unittest.py

Blob: `d38c447b14434a7c808cfe2e8a5989a2ba3aaa22`. Parse: parsed.

- import os @6
- import pathlib @7
- import shutil @8
- import sys @9
- import tempfile @10
- import textwrap @11
- import unittest @12
- from unittest import mock @13
- import clobber @15
- class TestExtractBuildCommand @18-103
- function TestExtractBuildCommand.setUp @19-20
- function TestExtractBuildCommand.tearDown @22-24
- function TestExtractBuildCommand.test_normal_extraction @26-81
- function TestExtractBuildCommand.test_unexpected_format @83-103
- class TestDelete @106-144
- function TestDelete.setUp @107-111
- function TestDelete.tearDown @113-114
- function TestDelete.test_delete_build_dir_full @116-123
- function TestDelete.test_delete_build_dir_fail @125-130
- function TestDelete.test_delete_build_dir_link @133-144

### third_party/chromium/build/compute_build_timestamp.py

Blob: `838b3fae67cf84e566c4d8638f45e779e0a18599`. Parse: parsed.

- import argparse @31
- import calendar @32
- import datetime @33
- import doctest @34
- import os @35
- import sys @36
- function GetFirstSundayOfMonth @42-54
- function GetUnofficialBuildDate @57-93
- function main @96-134

### third_party/chromium/build/config/apple/codesign.py

Blob: `0c9298ed69875ad714b6f1b0909f14170d9e3bc0`. Parse: parsed.

- import argparse @6
- import codecs @7
- import datetime @8
- import fnmatch @9
- import glob @10
- import json @11
- import os @12
- import plistlib @13
- import shutil @14
- import subprocess @15
- import stat @16
- import sys @17
- import tempfile @18
- function GetProvisioningProfilesDir @37-45
- function ReadPlistFromString @48-60
- function LoadPlistFile @63-78
- function CreateSymlink @81-86
- class Bundle @89-184
- function Bundle.__init__ @92-96
- function Bundle.Load @98-99
- function Bundle.Kind @102-113
- function Bundle.kind @116-117
- function Bundle.path @120-121
- function Bundle.contents_dir @124-129
- function Bundle.executable_dir @132-135
- function Bundle.resources_dir @138-141
- function Bundle.info_plist_path @144-147
- function Bundle.signature_dir @150-151
- function Bundle.identifier @154-155
- function Bundle.binary_name @158-159
- function Bundle.binary_path @162-163
- function Bundle.Validate @165-184
- class ProvisioningProfile @187-245
- function ProvisioningProfile.__init__ @190-197
- function ProvisioningProfile.path @200-201
- function ProvisioningProfile.team_identifier @204-205
- function ProvisioningProfile.name @208-209
- function ProvisioningProfile.application_identifier_pattern @212-213
- function ProvisioningProfile.application_identifier_prefix @216-217
- function ProvisioningProfile.entitlements @220-221
- function ProvisioningProfile.expiration_date @224-225
- function ProvisioningProfile.ValidToSignBundle @227-239
- function ProvisioningProfile.Install @241-245
- class Entitlements @248-290
- function Entitlements.__init__ @251-254
- function Entitlements.path @257-258
- function Entitlements.ExpandVariables @260-261
- function Entitlements._ExpandVariables @263-278
- function Entitlements.LoadDefaults @280-283
- function Entitlements.WriteTo @285-290
- function FindProvisioningProfile @293-343
- function CodeSignBundle @346-362
- function InstallSystemFramework @365-378
- function GenerateEntitlements @381-400
- function GenerateBundleInfoPlist @403-430
- class Action @433-440
- function Action.Register @437-440
- class CodeSignBundleAction @443-599
- function CodeSignBundleAction._Register @450-489
- function CodeSignBundleAction._Execute @492-599
- class CodeSignFileAction @602-641
- function CodeSignFileAction._Register @609-618
- function CodeSignFileAction._Execute @621-641
- class GenerateEntitlementsAction @644-677
- function GenerateEntitlementsAction._Register @651-667
- function GenerateEntitlementsAction._Execute @670-677
- class FindProvisioningProfileAction @680-711
- function FindProvisioningProfileAction._Register @687-699
- function FindProvisioningProfileAction._Execute @702-711
- function Main @714-733

### third_party/chromium/build/config/apple/compile_ib_files.py

Blob: `ca535ca307743f192b9fb17fde82c238af15a12c`. Parse: parsed.

- import argparse @5
- import logging @6
- import os @7
- import re @8
- import subprocess @9
- import sys @10
- function main @13-54

### third_party/chromium/build/config/apple/find_signing_identity.py

Blob: `37b3284e97927a61bd9d9f3c5474c9abb72639ac`. Parse: parsed.

- import argparse @6
- import os @7
- import subprocess @8
- import sys @9
- import re @10
- function Redact @13-15
- class Identity @18-30
- function Identity.__init__ @21-24
- function Identity.redacted @26-27
- function Identity.format @29-30
- function ListIdentities @33-41
- function FindValidIdentity @44-59
- function Main @62-86

### third_party/chromium/build/config/apple/sdk_info.py

Blob: `bbadc12473e36fb056b2b1ef46200c601871af07`. Parse: parsed.

- import argparse @6
- import doctest @7
- import itertools @8
- import os @9
- import plistlib @10
- import re @11
- import subprocess @12
- import sys @13
- function SplitVersion @20-31
- function FormatVersion @34-45
- function FillXcodeVersion @48-65
- function FillMachineOSBuild @68-72
- function FillSDKPathAndVersion @75-91
- function CreateXcodeSymlinkAt @94-112
- function main @115-163

### third_party/chromium/build/config/apple/write_framework_hmap.py

Blob: `88892534981a055c35bc02ffca2a3d94bc5516d5`. Parse: parsed.

- import os @6
- import struct @7
- import sys @8
- function Main @10-27
- function NextGreaterPowerOf2 @30-31
- function WriteHmap @34-98

### third_party/chromium/build/config/apple/write_framework_modulemap.py

Blob: `49f3263d315b6c370735392928f0aa06a8a720ca`. Parse: parsed.

- import os @5
- import sys @6
- function Main @18-24

### third_party/chromium/build/config/fuchsia/build_symbol_archive.py

Blob: `a595ed8a7a4fcfc84261309645a717c8ce313fd1`. Parse: parsed.

- import argparse @10
- import os @11
- import subprocess @12
- import sys @13
- import tarfile @14
- function main @17-58

### third_party/chromium/build/config/fuchsia/extend_fvm.py

Blob: `ae95f6736c0a3f14360a5c301e57c4a857ac8398`. Parse: parsed.

- import os @12
- import shutil @13
- import subprocess @14
- import sys @15
- function ExtendFVM @17-23

### third_party/chromium/build/config/get_host_byteorder.py

Blob: `7cc0cdff804feac2b9a70ab6a8eeb96a067eb8fc`. Parse: parsed.

- import sys @9

### third_party/chromium/build/config/ios/extract_metadata.py

Blob: `175032e6b74219748f4bb2e774df584d7386b53d`. Parse: parsed.

- import argparse @5
- import json @6
- import os @7
- import subprocess @8
- import sys @9
- import shutil @10
- import tempfile @11
- function read_json @21-24
- function add_argument @27-29
- function extract_metadata @32-109
- function main @112-133

### third_party/chromium/build/config/ios/generate_umbrella_header.py

Blob: `587ff17147d7ecfd5ebf5f7bc504e2c0cc6a901b`. Parse: parsed.

- import argparse @7
- import datetime @8
- import os @9
- import re @10
- import string @11
- function ComputeHeaderGuard @30-38
- function WriteUmbrellaHeader @41-60
- function Main @63-71

### third_party/chromium/build/config/ios/hardlink.py

Blob: `8ff6e8f9894bed6f7e133478d561eeadc5ebfb49`. Parse: parsed.

- import argparse @8
- import os @9
- import shutil @10
- import sys @11
- function CreateHardlinkHelper @14-36
- function CreateHardlink @39-58
- function CreateHardlinks @61-79
- function main @82-101

### third_party/chromium/build/config/ios/strip_arm64e.py

Blob: `56e684fd58c5244d24b9219174c9927c00538fae`. Parse: parsed.

- import argparse @6
- import os @7
- import shutil @8
- import subprocess @9
- import sys @10
- function check_output @13-23
- function check_call @26-28
- function parse_args @31-37
- function get_archs @40-43
- function main @46-66

### third_party/chromium/build/config/linux/pkg-config.py

Blob: `4f67c16192f76178fdf216ffc4e2f81e8d7d3fe4`. Parse: parsed.

- import json @7
- import os @8
- import subprocess @9
- import sys @10
- import re @11
- from optparse import OptionParser @12
- function SetConfigPath @45-64
- function GetPkgConfigPrefixToStrip @67-84
- function MatchesAnyRegexp @87-93
- function RewritePath @96-104
- function main @107-243

### third_party/chromium/build/config/mac/package_framework.py

Blob: `a9210eba65b6b45b3c11c16994c7d7a5f8d65d0e`. Parse: parsed.

- import argparse @5
- import errno @6
- import os @7
- import shutil @8
- import sys @9
- function Main @11-45
- function _Relink @48-56

### third_party/chromium/build/config/mac/prepare_framework_version.py

Blob: `0e9daeba989d39e6ff287bd676ec59d3f87b7795`. Parse: parsed.

- import os @5
- import shutil @6
- import sys @7
- function PrepareFrameworkVersion @16-37

### third_party/chromium/build/config/siso/PRESUBMIT.py

Blob: `327541be4acf002c5d62813199ca6a4feb0d87d8`. Parse: parsed.

- function CheckSisoConfigFormat @8-22

### third_party/chromium/build/config/siso/configure_siso.py

Blob: `ca79e8aa5cb197ad3de352f2102f6cd1940e6f58`. Parse: parsed.

- import argparse @7
- import os @8
- import shutil @9
- import sys @10
- function ReadConfig @34-44
- function main @47-85

### third_party/chromium/build/copy_test_data_ios.py

Blob: `69b957a72e20036d78f0015e0e46b57c40df94dd`. Parse: parsed.

- import optparse @9
- import os @10
- import shutil @11
- import sys @12
- class WrongNumberOfArgumentsException @14-15
- function EscapePath @17-19
- function ListFilesForPath @21-39
- function CalcInputs @41-48
- function CopyFiles @50-66
- function DoMain @68-93
- function main @95-103

### third_party/chromium/build/cp.py

Blob: `2bcf55cbc25578f17ac432cc3132eda6d91a61ea`. Parse: parsed.

- import os @12
- import shutil @13
- import sys @14
- function Main @17-19

### third_party/chromium/build/del_ninja_deps_cache.py

Blob: `c2560de660a281f2d73b614d74c3630de4588f02`. Parse: parsed.

- import os @9
- import sys @10
- function main @13-36

### third_party/chromium/build/detect_host_arch.py

Blob: `c9d47e9139fb5dd41b30b3b1208b9ebe7263316f`. Parse: parsed.

- import platform @9
- import re @10
- import sys @11
- function HostArch @14-46
- function DoMain @48-51

### third_party/chromium/build/dir_exists.py

Blob: `da9813f6093f8b17979d7ac6de8fa06b859a0118`. Parse: parsed.

- import os.path @7
- import sys @8
- function main @10-12
- function _is_dir @14-15
- function DoMain @17-20

### third_party/chromium/build/download_nacl_toolchains.py

Blob: `1b86a4bb9e19c54325636e2b9ee6e8ec42b7e0e8`. Parse: parsed.

- import os @9
- import shutil @10
- import sys @11
- function Main @14-51
- import package_version @27

### third_party/chromium/build/env_dump.py

Blob: `17d30a74d1cddbabc65729eda363e75d75e58204`. Parse: parsed.

- import json @9
- import optparse @10
- import os @11
- import shlex @12
- import subprocess @13
- import sys @14
- function main @17-52

### third_party/chromium/build/extract_from_cab.py

Blob: `c7ae6d9f499f0518ae86e71e6cd57d691b1241dd`. Parse: parsed.

- import os @9
- import shutil @10
- import subprocess @11
- import sys @12
- import tempfile @13
- function run_quiet @15-22
- function main @24-60

### third_party/chromium/build/extract_partition.py

Blob: `5b8267a3f559424f0b55c01600fb8fc69f9bb429`. Parse: parsed.

- import argparse @7
- import hashlib @8
- import os @9
- import struct @10
- import subprocess @11
- import sys @12
- import tempfile @13
- function _ComputeNewBuildId @16-35
- function _ExtractPartition @38-116
- function main @119-162

### third_party/chromium/build/find_depot_tools.py

Blob: `f891a414837a507759bb3591b0cecf2b79300d1a`. Parse: parsed.

- import os @15
- import sys @16
- function IsRealDepotTools @23-25
- function add_depot_tools_to_path @28-58
- import breakpad @63
- function main @66-70

### third_party/chromium/build/fix_gn_headers.py

Blob: `5111b5db4d4ccfb5603d45e435cf2800df07180d`. Parse: parsed.

- import argparse @14
- import os @15
- import re @16
- import subprocess @17
- import sys @18
- function GitGrep @21-26
- function ValidMatches @29-45
- function AddHeadersNextToCC @48-99
- function AddHeadersToSources @102-133
- function RemoveHeader @136-192
- function main @195-215

### third_party/chromium/build/fuchsia/PRESUBMIT.py

Blob: `898783f7212c64867c4061b54480276a0024a4a0`. Parse: parsed.

- import os @11
- function CommonChecks @14-34
- function CommonChecks.J @17-19
- function CheckChangeOnUpload @37-38
- function CheckChangeOnCommit @41-42

### third_party/chromium/build/fuchsia/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### third_party/chromium/build/fuchsia/binary_size_differ.py

Blob: `cc9007bd65b05f02929b2a521302d8b9cb44a2ee`. Parse: parsed.

- import argparse @8
- import json @9
- import os @10
- import sys @11
- import traceback @12
- from binary_sizes import ReadPackageSizesJson @14
- from binary_sizes import PACKAGES_SIZES_FILE @15
- function ComputePackageDiffs @31-81
- function main @84-149

### third_party/chromium/build/fuchsia/binary_size_differ_test.py

Blob: `162194ab8140c3795b67566d4697104acccf3a68`. Parse: parsed.

- import copy @6
- import os @7
- import tempfile @8
- from typing import MutableMapping,Optional @9
- import unittest @10
- import binary_size_differ @12
- import binary_sizes @13
- class BinarySizeDifferTest @51-167
- function BinarySizeDifferTest.ChangePackageSize @52-64
- function BinarySizeDifferTest.testComputePackageDiffs @66-167

### third_party/chromium/build/fuchsia/binary_sizes.py

Blob: `d64887c47755beff4030e64c5fc0ffeb04a96b28`. Parse: parsed.

- import argparse @8
- import collections @9
- import json @10
- import math @11
- import os @12
- import re @13
- import shutil @14
- import subprocess @15
- import sys @16
- import tempfile @17
- import time @18
- import traceback @19
- import uuid @20
- from common import DIR_SRC_ROOT,SDK_ROOT,get_host_tool_path @25
- function CreateSizesExternalDiagnostic @41-50
- function CreateSizesHistogramItem @53-77
- function CreateSizesHistogram @80-92
- function CreateTestResults @95-122
- function GetTestStatus @125-149
- function WriteSimpleTestResults @152-164
- function WriteTestResults @167-175
- function WriteGerritPluginSizeData @178-184
- function ReadPackageBlobsJson @187-207
- function WritePackageBlobsJson @210-237
- function WritePackageSizesJson @240-255
- function ReadPackageSizesJson @258-272
- function GetCompressedSize @275-310
- function ExtractFarFile @313-327
- function GetBlobNameHashes @330-341
- function GetSdkModules @348-368
- function FarBaseName @371-374
- function GetPackageMerkleRoot @377-383
- function GetBlobs @386-430
- function GetPackageBlobs @433-457
- function GetPackageSizes @460-487
- function GetBinarySizesAndBlobs @490-511
- function main @514-614

### third_party/chromium/build/fuchsia/binary_sizes_test.py

Blob: `0efce9d79a8147aee951727608b6748d5cef73b7`. Parse: parsed.

- import json @6
- import os @7
- import shutil @8
- import tempfile @9
- import unittest @10
- import binary_sizes @12
- class TestBinarySizes @51-128
- function TestBinarySizes.setUpClass @55-56
- function TestBinarySizes.tearDownClass @59-60
- function TestBinarySizes.testReadAndWritePackageBlobs @63-82
- function TestBinarySizes.testReadAndWritePackageSizes @84-101
- function TestBinarySizes.testGetPackageSizesUsesBlobMerklesForCount @103-128

### third_party/chromium/build/fuchsia/gcs_download.py

Blob: `8d28fc5034881529719c5576f5ddb276c6e5d2b9`. Parse: parsed.

- import os @5
- import sys @6
- import tarfile @7
- import tempfile @8
- from gs_util_wrapper import run_gsutil @12
- function DownloadAndUnpackFromCloudStorage @14-22

### third_party/chromium/build/fuchsia/gcs_download_test.py

Blob: `48db5e376e6076bde05bbcfa3e4839090ab65151`. Parse: parsed.

- import os @6
- import subprocess @7
- import tarfile @8
- import unittest @9
- from unittest import mock @10
- from gcs_download import DownloadAndUnpackFromCloudStorage @12
- function _mock_task @15-24
- class TestDownloadAndUnpackFromCloudStorage @31-81
- function TestDownloadAndUnpackFromCloudStorage.testHappyPath @32-61
- function TestDownloadAndUnpackFromCloudStorage.testFailedTarOpen @63-71
- function TestDownloadAndUnpackFromCloudStorage.testBadTaskStatusCode @73-81

### third_party/chromium/build/fuchsia/gen_build_defs.py

Blob: `b67cbc107d8f046e55c4019c654c41298d52cfa4`. Parse: parsed.

- import json @12
- import logging @13
- import os @14
- import sys @15
- from common import DIR_SRC_ROOT,SDK_ROOT,GN_SDK_ROOT,get_host_os @20
- function ReformatTargetName @39-42
- function FormatGNTarget @45-78
- function MetaRootRelativePaths @81-82
- function ConvertCommonFields @85-105
- function ConvertFidlLibrary @108-123
- function ConvertCcPrebuiltLibrary @126-149
- function ConvertCcSourceLibrary @152-177
- function ConvertLoadableModule @180-257
- function ConvertLoadableModule._filename_no_ext @197-198
- function ConvertPackage @260-283
- function ConvertNoOp @286-289
- function ConvertMeta @317-342
- function ProcessSdkManifest @345-351
- function main @354-376

### third_party/chromium/build/fuchsia/get_auth_token.py

Blob: `3f5569b9ea58f78caf85c438bcdf61a3b677b3de`. Parse: parsed.

- from __future__ import absolute_import @7
- import os @8
- import subprocess @9
- import sys @10
- from common import DIR_SRC_ROOT @14
- import find_depot_tools @17
- function main @20-27

### third_party/chromium/build/fuchsia/test/PRESUBMIT.py

Blob: `076d1b0a48367df93a2672ff55e80a01e91791ea`. Parse: parsed.

- function CommonChecks @14-42
- function CheckChangeOnUpload @45-46
- function CheckChangeOnCommit @49-50

### third_party/chromium/build/fuchsia/test/boot_device.py

Blob: `8bebba25387aa93f301ae1f38b2e8e7319086080`. Parse: parsed.

- import enum @6
- from typing import Optional @8
- class BootMode @10-14
- class StateTransitionError @17-18
- function boot_device @21-44
- import serial_boot_device @40

### third_party/chromium/build/fuchsia/test/browser_runner.py

Blob: `3d2e111d58fc81e3d7b9c7144a597e4989d3759b`. Parse: parsed.

- import os @6
- import re @7
- import subprocess @8
- import tempfile @9
- import time @10
- from typing import List,Optional @11
- from urllib.parse import urlparse @12
- from common import run_continuous_ffx_command,ssh_run,REPO_ALIAS @14
- from ffx_integration import run_symbolizer @15
- class BrowserRunner @21-183
- function BrowserRunner.__init__ @24-52
- function BrowserRunner.browser_type @55-57
- function BrowserRunner.devtools_port @60-64
- function BrowserRunner.log_file @67-71
- function BrowserRunner.browser_pid @74-78
- function BrowserRunner._read_devtools_port @80-104
- function BrowserRunner._read_devtools_port.try_reading_port @85-93
- function BrowserRunner.start @106-152
- function BrowserRunner.stop_browser @154-167
- function BrowserRunner.is_browser_running @169-177
- function BrowserRunner.close @179-183

### third_party/chromium/build/fuchsia/test/bundled_test_runner.py

Blob: `44ccfbb80ba965dffc5a30c3b89d14f49f74c383`. Parse: parsed.

- import argparse @13
- import logging @14
- import os @15
- import sys @16
- from subprocess import CompletedProcess @18
- from typing import List,NamedTuple,Optional @19
- from urllib.parse import urlparse @20
- import run_test @22
- from run_executable_test import ExecutableTestRunner @23
- from test_runner import TestRunner @24
- class TestCase @27-35
- class _BundledTestRunner @38-87
- function _BundledTestRunner.__init__ @48-59
- function _BundledTestRunner._merge_packages @62-71
- function _BundledTestRunner.run_test @73-87
- function run_tests @90-122
- function run_tests.get_test_runner @112-118

### third_party/chromium/build/fuchsia/test/bundled_test_runner_unittests.py

Blob: `cd213003fae8f522917e3134c142226c9a5b9a1b`. Parse: parsed.

- import unittest @8
- from bundled_test_runner import _BundledTestRunner,TestCase @10
- class BundledTestRunnerTests @16-98
- function BundledTestRunnerTests._default_test_case @20-23
- function BundledTestRunnerTests.test_resolve_test_package_into_far @25-31
- function BundledTestRunnerTests.test_dedupe_fars @33-39
- function BundledTestRunnerTests.test_absolute_path @41-48
- function BundledTestRunnerTests.test_different_cm @50-58
- function BundledTestRunnerTests.test_join_relative_path @60-66
- function BundledTestRunnerTests.test_current_dir_as_out_dir @68-74
- function BundledTestRunnerTests.test_empty_out_dir @76-82
- function BundledTestRunnerTests.test_none_out_dir @84-89
- function BundledTestRunnerTests.test_conflict_fars @91-98

### third_party/chromium/build/fuchsia/test/chrome_driver_wrapper.py

Blob: `59242a0d7dc9993e3dc9f6fb3714200fdda99185`. Parse: parsed.

- import logging @7
- import os @8
- import subprocess @9
- from contextlib import AbstractContextManager @11
- from typing import List @12
- from selenium import webdriver @16
- from selenium.webdriver import ChromeOptions @17
- from selenium.webdriver.chrome.service import Service @18
- from selenium.webdriver.common.by import By @19
- from common import get_ffx_isolate_dir,get_free_local_port @22
- from isolate_daemon import IsolateDaemon @23
- from run_webpage_test import capture_devtools_addr @24
- class ChromeDriverWrapper @29-100
- function ChromeDriverWrapper.__init__ @34-47
- function ChromeDriverWrapper.__enter__ @49-77
- function ChromeDriverWrapper.__exit__ @79-87
- function ChromeDriverWrapper.__getattr__ @89-91
- function ChromeDriverWrapper.find_element_by_id @98-100

### third_party/chromium/build/fuchsia/test/common.py

Blob: `9dd90be0b74233f6aecb10cd08912b4572cf378e`. Parse: parsed.

- import ipaddress @6
- import json @7
- import logging @8
- import os @9
- import signal @10
- import shutil @11
- import socket @12
- import subprocess @13
- import sys @14
- import time @15
- from argparse import ArgumentParser @17
- from typing import Iterable,List,Optional,Tuple @18
- from dataclasses import dataclass @19
- from compatible_utils import get_ssh_prefix,get_host_arch @21
- function _find_src_root @24-29
- function _find_fuchsia_images_root @38-42
- function _find_fuchsia_internal_images_root @48-52
- function _find_fuchsia_sdk_root @60-64
- function _find_fuchsia_gn_sdk_root @70-74
- function set_ffx_isolate_dir @84-88
- function get_ffx_isolate_dir @91-94
- function has_ffx_isolate_dir @97-99
- function get_hash_from_sdk @102-109
- function get_host_tool_path @112-115
- function get_host_os @118-126
- function make_clean_directory @129-134
- function _get_daemon_status @137-148
- function is_daemon_running @151-153
- function _wait_for_daemon @156-179
- function start_ffx_daemon @184-197
- function stop_ffx_daemon @200-203
- function run_ffx_command @206-252
- function run_continuous_ffx_command @255-285
- function read_package_paths @288-300
- function register_common_args @303-310
- function register_device_args @313-323
- function register_log_args @326-332
- function get_component_uri @335-340
- function ssh_run @343-349
- function resolve_packages @352-379
- import monitors @358
- function resolve_packages._retry_resolve @363-375
- function get_ip_address @382-385
- function get_ssh_address @388-407
- function find_in_dir @410-426
- function find_image_in_sdk @429-442
- function catch_sigterm @445-450
- function catch_sigterm._sigterm_handler @447-448
- function wait_for_sigterm @453-469
- class BuildInfo @473-479
- function get_build_info @482-507
- function get_system_info @510-521
- function get_free_local_port @524-539

### third_party/chromium/build/fuchsia/test/common_unittests.py

Blob: `0391f9d8510bf741b9a6ca41dbf5c11c6fff66df`. Parse: parsed.

- import os @7
- import tempfile @8
- import unittest @9
- import unittest.mock @10
- from types import SimpleNamespace @12
- import common @14
- class CommonTest @21-110
- function CommonTest.test_find_in_dir_returns_file_or_dir_if_searching @23-42
- function CommonTest.test_find_image_in_sdk_searches_images_in_product_bundle @44-55
- function CommonTest.test_images_root_should_not_end_with_path_sep @57-63
- function CommonTest.test_get_system_info_parse_version_and_product @66-69
- function CommonTest.test_get_system_info_parse_version_only @72-75
- function CommonTest.test_get_system_info_ffx_error @78-81
- function CommonTest.test_get_system_info_never_returns_none @84-87
- function CommonTest.test_get_system_info_ignore_no_build @90-93
- function CommonTest.test_get_system_info_ignore_bad_build_type @96-99
- function CommonTest.test_get_system_info_ignore_bad_build_type2 @102-105
- function CommonTest.test_get_system_info_not_a_json @108-110

### third_party/chromium/build/fuchsia/test/compatible_utils.py

Blob: `21ed6f4f7e8fc01b9402ff8b31562ab6e7891c95`. Parse: parsed.

- import json @6
- import os @7
- import platform @8
- import stat @9
- from typing import Iterable,List,Tuple @11
- class VersionNotFoundError @19-20
- function get_ssh_keys @23-26
- function running_unattended @29-38
- function force_running_unattended @41-45
- function force_running_attended @48-53
- function get_host_arch @56-64
- function add_exec_to_file @67-74
- function get_ssh_prefix @77-84
- function install_symbols @87-111
- function map_filter_file_to_package_file @116-122
- function get_sdk_hash @126-137

## Validation and limits

The parser checked syntax only. This pass cannot prove runtime contracts, ownership, selected build settings, executed branches, or design reasons. Build files use a Python-based domain-specific language; parsing them as Python does not validate the build system. Byte decoding uses UTF-8; special encoding declarations and intentionally invalid fixtures may fail.

## Retrieval correction

This copy preserves the source map in [1054b211-4bdf-4da9-8a15-181ac7e278f8.md](1054b211-4bdf-4da9-8a15-181ac7e278f8.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `714f6848978bcac01bda001824ee0baf4cfd2ae38f4a8abb54049ac4a3bbac4c`.
