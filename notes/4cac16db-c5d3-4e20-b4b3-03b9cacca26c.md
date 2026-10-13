<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:18:44.114924+00:00", "paths": ["python/mozperftest/setup.py", "python/mozrelease/mozrelease/__init__.py", "python/mozrelease/mozrelease/attribute_builds.py", "python/mozrelease/mozrelease/balrog.py", "python/mozrelease/mozrelease/bouncer_check.py", "python/mozrelease/mozrelease/buglist_creator.py", "python/mozrelease/mozrelease/checksums.py", "python/mozrelease/mozrelease/chunking.py", "python/mozrelease/mozrelease/generate_checksums.py", "python/mozrelease/mozrelease/l10n.py", "python/mozrelease/mozrelease/mach_commands.py", "python/mozrelease/mozrelease/merkle.py", "python/mozrelease/mozrelease/partner_repack.py", "python/mozrelease/mozrelease/paths.py", "python/mozrelease/mozrelease/platforms.py", "python/mozrelease/mozrelease/scriptworker_canary.py", "python/mozrelease/mozrelease/update_verify.py", "python/mozrelease/mozrelease/update_verify_config_creator.py", "python/mozrelease/mozrelease/util.py", "python/mozrelease/mozrelease/versions.py", "python/mozrelease/setup.py", "python/mozrelease/test/test_balrog.py", "python/mozrelease/test/test_bouncer_check.py", "python/mozrelease/test/test_branding_urls.py", "python/mozrelease/test/test_buglist_creator.py", "python/mozrelease/test/test_generate_checksums.py", "python/mozrelease/test/test_merkle.py", "python/mozrelease/test/test_update_verify.py", "python/mozrelease/test/test_update_verify_config_creator.py", "python/mozrelease/test/test_versions.py", "python/mozterm/mozterm/__init__.py", "python/mozterm/mozterm/terminal.py", "python/mozterm/setup.py", "python/mozterm/test/test_terminal.py", "python/mozversioncontrol/mozversioncontrol/__init__.py", "python/mozversioncontrol/mozversioncontrol/errors.py", "python/mozversioncontrol/mozversioncontrol/factory.py", "python/mozversioncontrol/mozversioncontrol/repo/base.py", "python/mozversioncontrol/mozversioncontrol/repo/git.py", "python/mozversioncontrol/mozversioncontrol/repo/jj.py", "python/mozversioncontrol/mozversioncontrol/repo/mercurial.py", "python/mozversioncontrol/mozversioncontrol/repo/source.py", "python/mozversioncontrol/mozversioncontrol/repoupdate.py", "python/mozversioncontrol/setup.py", "python/mozversioncontrol/test/conftest.py", "python/mozversioncontrol/test/test_branch.py", "python/mozversioncontrol/test/test_commit.py", "python/mozversioncontrol/test/test_context_manager.py", "python/mozversioncontrol/test/test_diff_stream.py", "python/mozversioncontrol/test/test_get_commit_patches.py", "python/mozversioncontrol/test/test_get_commits.py", "python/mozversioncontrol/test/test_get_mozilla_remote_args.py", "python/mozversioncontrol/test/test_get_remote_url.py", "python/mozversioncontrol/test/test_get_upstream_remotes.py", "python/mozversioncontrol/test/test_notes.py", "python/mozversioncontrol/test/test_prepare_try_push.py", "python/mozversioncontrol/test/test_push.py", "python/mozversioncontrol/test/test_push_to_try.py", "python/mozversioncontrol/test/test_try_commit.py", "python/mozversioncontrol/test/test_update.py", "python/mozversioncontrol/test/test_workdir_outgoing.py", "python/mozversioncontrol/test/test_working_directory.py"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/python Python and build syntax map 56

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Python AST parser; no source was executed. Functions and classes have source ranges. Imports are written names, not resolved modules. Build entries list assignments with literal string lists and registration calls. Conditions are not evaluated; listed files are not necessarily built or shipped. Dynamic expressions and included build files need separate analysis. Failed parses remain listed.

### python/mozperftest/setup.py

Blob: `75ebab930550e4050e8260a0a0506d2b1535cc23`. Parse: parsed.

- from setuptools import setup @5

### python/mozrelease/mozrelease/__init__.py

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Parse: parsed.


### python/mozrelease/mozrelease/attribute_builds.py

Blob: `51c36c382cebd776ec19418198bb13be3c9fe22d`. Parse: parsed.

- import argparse @6
- import logging @7
- import mmap @8
- import os @9
- import shutil @10
- import struct @11
- import sys @12
- import tempfile @13
- import urllib.parse @14
- from pathlib import Path @15
- from mozfile import json @17
- function write_attribution_data @23-86
- function validate_attribution_code @89-147
- function main @150-209

### python/mozrelease/mozrelease/balrog.py

Blob: `dfd6790a94e1123c1639cf20c7d2412b202af7f0`. Parse: parsed.

- function _generate_show_url @6-11
- function _generate_product_details @14-19
- function _generate_conditions @28-55
- function generate_update_properties @58-69

### python/mozrelease/mozrelease/bouncer_check.py

Blob: `b9097f7e7e2d1038b6c03ee95a0507828d5fa949`. Parse: parsed.

- import argparse @6
- import logging @7
- import sys @8
- from concurrent import futures @9
- from urllib.parse import urlparse @10
- import requests @12
- import yaml @13
- from redo import retry @14
- from requests.exceptions import HTTPError @15
- function parse_args @37-90
- function get_json @93-105
- function get_json.fetch @94-97
- function resolve_version @108-116
- function get_urls @119-144
- function check_url @147-173
- function check_url.do_check_url @150-167
- function check_bouncer @176-191
- function main @194-204

### python/mozrelease/mozrelease/buglist_creator.py

Blob: `a970016210213b28064d150583128f6a90051b92`. Parse: parsed.

- import logging @5
- import os @6
- import re @7
- from operator import itemgetter @8
- import requests @10
- from mozilla_version.gecko import GeckoVersion @11
- from taskcluster import Notify,optionsFromEnvironment @12
- function create_bugs_url @33-100
- function get_bugs_in_changeset @103-120
- function is_excluded_change @123-128
- function is_backout_bug @131-132
- function create_buglist_url @135-136
- function tag_version @139-143
- function parse_tag_version @146-148
- function get_previous_tag_version @151-185
- function get_previous_tag_version._invalid_tag_filter @161-170
- function get_repo_by_version @188-201
- function email_release_drivers @204-252

### python/mozrelease/mozrelease/checksums.py

Blob: `3d268de81146355c49b47fa3cdd77adc3957f62a`. Parse: parsed.

- function parse_checksums_file @6-41

### python/mozrelease/mozrelease/chunking.py

Blob: `8c45f743542bf9c9f7d848ccd2c754352ad388a8`. Parse: parsed.

- from copy import copy @5
- class ChunkingError @8-9
- function getChunk @12-27

### python/mozrelease/mozrelease/generate_checksums.py

Blob: `8f526b7530bd48e1aac666673144f6c10f11807e`. Parse: parsed.

- import argparse @7
- import binascii @8
- import hashlib @9
- import logging @10
- import os @11
- import re @12
- import sys @13
- import xml.etree.ElementTree @14
- from multiprocessing.pool import ThreadPool @15
- import requests @17
- from redo import retry @18
- from mozrelease.checksums import parse_checksums_file @20
- from mozrelease.merkle import MerkleTree @21
- function parse_args @47-78
- function get_file_prefix @81-82
- function get_hash_function @85-88
- function _get @91-103
- function _get.fetch @92-95
- function list_keys @106-122
- function find_checksums_files @125-141
- function collect_individual_checksums @144-183
- function collect_individual_checksums.worker @150-152
- function create_summary @186-204
- function create_big_checksums @207-211
- function write_outputs @214-224
- function main @227-236

### python/mozrelease/mozrelease/l10n.py

Blob: `1e2a15878d9d48b14d5862796e515a71684c7b68`. Parse: parsed.

- function getPlatformLocales @6-17

### python/mozrelease/mozrelease/mach_commands.py

Blob: `28ee66d0df7f8195860a2c909e0ba72b846a967e`. Parse: parsed.

- import logging @6
- import sys @7
- from mach.decorators import Command,CommandArgument,SubCommand @9
- from mozilla_version.gecko import GeckoVersion @10
- function release @18-21
- function buglist @38-49
- from mozrelease.buglist_creator import create_bugs_url @40
- function buglist_email @75-79
- from mozrelease.buglist_creator import email_release_drivers @77
- function push_scriptworker_canary @108-116
- from mozrelease.scriptworker_canary import push_canary @110
- function setup_logging @119-139

### python/mozrelease/mozrelease/merkle.py

Blob: `dba780b73a14aea3454f527c01207942e8bac77f`. Parse: parsed.

- import struct @5
- function _round2 @8-12
- function _leaf_hash @15-16
- function _pair_hash @19-20
- class InclusionProof @23-132
- function InclusionProof.__init__ @52-55
- function InclusionProof.from_rfc6962_bis @58-92
- function InclusionProof.to_rfc6962_bis @94-103
- function InclusionProof._expected_head @105-129
- function InclusionProof.verify @131-132
- class MerkleTree @135-190
- function MerkleTree.__init__ @145-156
- function MerkleTree._node @158-168
- function MerkleTree.head @170-171
- function MerkleTree._relative_proof @173-186
- function MerkleTree.inclusion_proof @188-190

### python/mozrelease/mozrelease/partner_repack.py

Blob: `663805f26002801113c96d337bce04f92a89d290`. Parse: parsed.

- import logging @4
- import os @5
- import re @6
- import stat @7
- import sys @8
- import tarfile @9
- import urllib.parse @10
- import urllib.request @11
- import zipfile @12
- from optparse import OptionParser @13
- from pathlib import Path @14
- from shutil import copy,copytree,move,rmtree,which @15
- from subprocess import Popen @16
- from mozfile import json @18
- from redo import retry @19
- class StrictFancyURLopener @49-57
- function StrictFancyURLopener.http_error_default @54-57
- function rmdirRecursive @60-78
- function rmdirRecursive.rmdir_including_read_only @67-76
- function printSeparator @81-82
- function shellCommand @85-98
- function isLinux @101-102
- function isLinux64 @105-106
- function isMac @109-110
- function isWin @113-114
- function isWin32 @117-118
- function isWin64 @121-122
- function isWin64Aarch64 @125-126
- function isValidPlatform @129-136
- function parseRepackConfig @139-188
- function getFtpPlatform @191-207
- function getFileExtension @210-217
- function getFilename @220-222
- function getAllFilenames @225-235
- function getTaskArtifacts @238-247
- function getUpstreamArtifacts @250-272
- function getArtifactNames @275-283
- function retrieveFile @286-306
- function getBouncerProduct @309-318
- class RepackBase @321-442
- function RepackBase.__init__ @322-350
- function RepackBase.announceStart @352-355
- function RepackBase.announceSuccess @357-361
- function RepackBase.unpackBuild @363-364
- function RepackBase.createOverrideIni @366-396
- function RepackBase.obfuscateCfg @398-406
- function RepackBase.copyFiles @408-421
- function RepackBase.repackBuild @423-424
- function RepackBase.stage @426-428
- function RepackBase.cleanup @430-431
- function RepackBase.doRepack @433-442
- class RepackLinux @445-489
- function RepackLinux.__init__ @446-465
- function RepackLinux.unpackBuild @467-476
- function RepackLinux.copyFiles @478-479
- function RepackLinux.repackBuild @481-489
- class RepackMac @492-552
- function RepackMac.__init__ @493-512
- function RepackMac.unpackBuild @514-521
- function RepackMac.getAppName @523-534
- function RepackMac.copyFiles @536-537
- function RepackMac.repackBuild @539-552
- class RepackWin @555-634
- function RepackWin.__init__ @556-574
- function RepackWin.copyFiles @576-577
- function RepackWin.repackBuild @579-607
- function RepackWin.stage @609-634

### python/mozrelease/mozrelease/paths.py

Blob: `da31818e68efa77f7130ed4fa395ce2dec52c321`. Parse: parsed.

- from datetime import datetime @5
- from urllib.parse import urlunsplit @6
- from .versions import MozillaVersion @8
- function product2ftp @15-16
- function getCandidatesDir @19-31
- function getReleasesDir @34-45
- function getNightlyDir @48-59
- function getReleaseInstallerPath @62-104

### python/mozrelease/mozrelease/platforms.py

Blob: `67b2dfafe03a5fe476f540c96422897787ebf9e7`. Parse: parsed.

- function ftp2updatePlatforms @61-62
- function ftp2shippedLocales @65-66
- function ftp2infoFile @69-70
- function updatePlatform2ftp @73-78
- function buildPlatform2ftp @81-82

### python/mozrelease/mozrelease/scriptworker_canary.py

Blob: `d91b9d4b35f831fc155416fc358fd0b94f8b8df4`. Parse: parsed.

- import logging @5
- import os @6
- import shutil @7
- import subprocess @8
- import tempfile @9
- from contextlib import contextmanager @10
- from pathlib import Path @11
- import taskcluster @13
- from appdirs import user_config_dir @14
- from gecko_taskgraph import GECKO @15
- from mach.base import FailedCommandError @16
- function get_secret @30-37
- function configure_ssh @41-69
- function push_canary @72-101

### python/mozrelease/mozrelease/update_verify.py

Blob: `1634cdd2c9548642b774843d7fd0bf951831e01b`. Parse: parsed.

- import os @5
- import re @6
- from .chunking import getChunk @8
- class UpdateVerifyError @11-12
- class UpdateVerifyConfig @15-270
- function UpdateVerifyConfig.__init__ @70-89
- function UpdateVerifyConfig.__eq__ @91-94
- function UpdateVerifyConfig.__ne__ @96-97
- function UpdateVerifyConfig._parseLine @99-115
- function UpdateVerifyConfig._addEntry @117-128
- function UpdateVerifyConfig.read @130-140
- function UpdateVerifyConfig.write @142-164
- function UpdateVerifyConfig.addRelease @166-202
- function UpdateVerifyConfig.addLocaleToRelease @204-213
- function UpdateVerifyConfig.getRelease @215-219
- function UpdateVerifyConfig.getFullReleaseTests @221-222
- function UpdateVerifyConfig.getQuickReleaseTests @224-225
- function UpdateVerifyConfig.getChunk @227-270

### python/mozrelease/mozrelease/update_verify_config_creator.py

Blob: `d4a7ed9707db1dc0f2e18ddadcd9f1a79a36b2ef`. Parse: parsed.

- import argparse @5
- import asyncio @6
- import http.client @7
- import json @8
- import logging @9
- import math @10
- import pprint @11
- import re @12
- import socket @13
- import sys @14
- from collections import namedtuple @15
- from urllib.error import HTTPError,URLError @16
- from urllib.parse import urljoin @17
- from urllib.request import urlopen @18
- import aiohttp @20
- import hglib @21
- from hglib.util import cmdbuilder @22
- from looseversion import LooseVersion @23
- from mozilla_version.gecko import GeckoVersion @24
- from mozilla_version.version import VersionType @25
- from redo import retry @26
- from mozrelease.l10n import getPlatformLocales @28
- from mozrelease.paths import getCandidatesDir,getReleaseInstallerPath,getReleasesDir @29
- from mozrelease.platforms import ftp2infoFile,ftp2updatePlatforms @34
- from mozrelease.update_verify import UpdateVerifyConfig @35
- from mozrelease.versions import MozillaVersion,getPrettyVersion @36
- class CompareVersion @43-58
- function CompareVersion.__init__ @46-58
- function is_triangular @64-91
- function retry_download @94-113
- function parse_args @116-287
- class UpdateVerifyConfigCreator @290-722
- function UpdateVerifyConfigCreator.__init__ @291-296
- function UpdateVerifyConfigCreator._setup_hgclient @298-308
- function UpdateVerifyConfigCreator._close_hg_client @310-313
- function UpdateVerifyConfigCreator._get_branch_url @315-327
- async-function UpdateVerifyConfigCreator._download_build_info @329-370
- async-function UpdateVerifyConfigCreator._download_build_info._get @345-349
- function UpdateVerifyConfigCreator._async_download_build_ids @372-394
- async-function UpdateVerifyConfigCreator._async_download_build_ids._run_semaphore @382-392
- function UpdateVerifyConfigCreator._get_update_paths @396-481
- function UpdateVerifyConfigCreator._get_file_from_repo @483-491
- function UpdateVerifyConfigCreator._get_files_from_repo_tag @493-498
- function UpdateVerifyConfigCreator._get_files_from_local_repo @500-536
- function UpdateVerifyConfigCreator._get_files_from_remote_repo @538-558
- function UpdateVerifyConfigCreator.gather_info @560-574
- function UpdateVerifyConfigCreator.create_config @576-708
- function UpdateVerifyConfigCreator.write_config @710-713
- function UpdateVerifyConfigCreator.run @715-722
- function main @725-729

### python/mozrelease/mozrelease/util.py

Blob: `3122a3b95018392eaf1591ab0748eba1c29580d1`. Parse: parsed.

- from yaml.loader import SafeLoader @5
- class UnicodeLoader @8-10
- function UnicodeLoader.construct_yaml_str @9-10
- function load @16-25

### python/mozrelease/mozrelease/versions.py

Blob: `d018500ac68ca29e2c862c77cee26d566b3cdbba`. Parse: parsed.

- import re @5
- from looseversion import LooseVersion @7
- from packaging.version import InvalidVersion @8
- class StrictVersion @11-58
- function StrictVersion.__init__ @12-13
- function StrictVersion.__repr__ @15-16
- function StrictVersion.__eq__ @18-19
- function StrictVersion.__lt__ @21-22
- function StrictVersion.parse @24-31
- function StrictVersion.__str__ @33-36
- function StrictVersion._cmp @38-58
- class MozillaVersionCompareMixin @61-105
- function MozillaVersionCompareMixin.__cmp__ @62-64
- function MozillaVersionCompareMixin._cmp @66-105
- class ModernMozillaVersion @108-118
- class AncientMozillaVersion @121-133
- class LooseModernMozillaVersion @136-144
- function LooseModernMozillaVersion.__repr__ @143-144
- function MozillaVersion @147-161
- function getPrettyVersion @164-168

### python/mozrelease/setup.py

Blob: `d831cb14c5c6f83322528950ffa43e8098bcf4bf`. Parse: parsed.

- from setuptools import find_packages,setup @5

### python/mozrelease/test/test_balrog.py

Blob: `abf74b10c020fa6f60505c26fcef7915eba1bd25`. Parse: parsed.

- from pathlib import Path @5
- import mozunit @7
- import pytest @8
- from mozfile import json @9
- from mozilla_version.gecko import GeckoVersion @10
- from mozrelease.balrog import generate_update_properties @12
- from mozrelease.util import load @13
- function test_update_properties @61-69

### python/mozrelease/test/test_bouncer_check.py

Blob: `c171a21294a39edac59727d38b70bb6800c94ac6`. Parse: parsed.

- from pathlib import Path @5
- from unittest import mock @6
- import mozunit @8
- import pytest @9
- import yaml @10
- from mozrelease.bouncer_check import check_url,get_urls,parse_args @12
- function test_config_files_load @18-24
- function test_get_urls @27-52
- function test_parse_args_defaults @55-70
- function _session @73-79
- function test_check_url @82-89

### python/mozrelease/test/test_branding_urls.py

Blob: `38c78896e7f1366e31c296b311515cee7c14e587`. Parse: parsed.

- import re @5
- from pathlib import Path @6
- import mozunit @8
- function test_release_notes_urls_use_firefox_com @25-36

### python/mozrelease/test/test_buglist_creator.py

Blob: `53fb5e28708716c1d4cc53474bc3dd5a15a00324`. Parse: parsed.

- from pathlib import Path @9
- import mozunit @11
- import pytest @12
- from mozfile import json @13
- from mozilla_version.gecko import GeckoVersion @14
- from mozrelease.buglist_creator import create_bugs_url,get_bugs_in_changeset,get_previous_tag_version,is_backout_bug,is_excluded_change,parse_tag_version,tag_version @16
- function test_beta_1_release @29-35
- function test_is_excluded_change @48-49
- function test_is_backout_bug @62-63
- function test_tag_version @74-75
- function test_parse_tag_version @86-87
- function test_get_previous_tag_version @115-152
- function test_get_bugs_in_changeset @155-172

### python/mozrelease/test/test_generate_checksums.py

Blob: `79088299208229957ba31c6ba83b02c538c3b577`. Parse: parsed.

- import hashlib @5
- from unittest import mock @6
- import mozunit @8
- import pytest @9
- from mozrelease import generate_checksums @11
- from mozrelease.checksums import parse_checksums_file @12
- function _sums @32-36
- function _beet @39-45
- class FakeResponse @60-65
- function FakeResponse.__init__ @61-62
- function FakeResponse.raise_for_status @64-65
- class FakeSession @68-79
- function FakeSession.__init__ @69-70
- function FakeSession.get @72-79
- function test_list_keys_follows_markers @82-91
- function test_find_checksums_files_prefers_beets @94-96
- function test_collect_individual_checksums_filters_and_dedupes @99-109
- function test_collect_individual_checksums_rejects_conflicts @112-120
- function test_outputs @123-139
- function test_file_prefix @142-146

### python/mozrelease/test/test_merkle.py

Blob: `9795aeba58d6acf5d559d7471ed3303f7ee32b94`. Parse: parsed.

- import codecs @1
- import hashlib @2
- import random @3
- import unittest @4
- import mozunit @6
- from mozrelease.merkle import InclusionProof,MerkleTree @8
- class TestMerkleTree @87-136
- function TestMerkleTree.testPreComputed @88-99
- function TestMerkleTree.testInclusionProofEncodeDecode @101-119
- function TestMerkleTree.testLargeTree @121-136

### python/mozrelease/test/test_update_verify.py

Blob: `e0076f57610cbbcd6d97e55798922a1286e6db3c`. Parse: parsed.

- import os @5
- import unittest @6
- from pathlib import Path @7
- from tempfile import mkstemp @8
- import mozunit @10
- from mozrelease.update_verify import UpdateVerifyConfig,UpdateVerifyError @12
- class TestUpdateVerifyConfig @17-420
- function TestUpdateVerifyConfig.setUp @20-23
- function TestUpdateVerifyConfig.tearDown @25-27
- function TestUpdateVerifyConfig.testEq @29-51
- function TestUpdateVerifyConfig.testNe @53-57
- function TestUpdateVerifyConfig.testAddRelease @59-85
- function TestUpdateVerifyConfig.testAddReleasesWithDifferentPlatforms @87-136
- function TestUpdateVerifyConfig.testRead @138-187
- function TestUpdateVerifyConfig.testWrite @189-238
- function TestUpdateVerifyConfig.testReadInvalidKey @240-242
- function TestUpdateVerifyConfig.testReadDuplicateKey @244-246
- function TestUpdateVerifyConfig.testParseLineBad @248-250
- function TestUpdateVerifyConfig.testGetChunk @252-286
- function TestUpdateVerifyConfig.testGetChunkWithPathWithSpaces @288-325
- function TestUpdateVerifyConfig.testAddLocaleToRelease @327-334
- function TestUpdateVerifyConfig.testAddLocaleToReleaseMultipleBuildIDs @336-343
- function TestUpdateVerifyConfig.testAddLocaleToNonexistentRelease @345-347
- function TestUpdateVerifyConfig.testGetReleaseNonexistenceRelease @349-351
- function TestUpdateVerifyConfig.testGetFullReleaseTests @353-386
- function TestUpdateVerifyConfig.testGetQuickReleaseTests @388-420

### python/mozrelease/test/test_update_verify_config_creator.py

Blob: `4444ffb431af6c6a89be1ef9234ee213caef1019`. Parse: parsed.

- import doctest @5
- from unittest import mock @6
- import mozunit @8
- import pytest @9
- from mozrelease import update_verify_config_creator @11
- function test_is_triangular_doctests @45-47
- function test_compare_version_pads_to_three_parts @50-53
- function test_parse_args_defaults @56-75
- function test_get_branch_url @87-89
- function test_create_config_writes_full_partial_and_quick_checks @92-133

### python/mozrelease/test/test_versions.py

Blob: `45dd94df504456cbd805a47ab413cacb4840fa1f`. Parse: parsed.

- import mozunit @1
- import pytest @2
- from mozrelease.versions import AncientMozillaVersion,ModernMozillaVersion,MozillaVersion @4
- function comparable_versions @72-74
- function test_versions_parseable @78-83
- function test_versions_compare_less @86-89
- function test_versions_compare_greater @92-95
- function test_ModernMozillaVersion @98-102
- function test_AncientMozillaVersion @105-110
- function test_versions_compare_equal @114-116

### python/mozterm/mozterm/__init__.py

Blob: `ff15e588ff44da9acf15abe6aebab943223ab5df`. Parse: parsed.

- from .terminal import NullTerminal,Terminal @4

### python/mozterm/mozterm/terminal.py

Blob: `a094a65f344fb20ff8befae4840d6550f0519924`. Parse: parsed.

- import os @5
- import sys @6
- class NullTerminal @9-36
- function NullTerminal.__init__ @16-21
- class NullTerminal.NullCallableString @23-33
- function NullTerminal.NullCallableString.__new__ @26-28
- function NullTerminal.NullCallableString.__call__ @30-33
- function NullTerminal.__getattr__ @35-36
- function Terminal @39-48
- import blessed @43

### python/mozterm/setup.py

Blob: `d34f8b2d81ace402a770bf6e4534473daa524fb2`. Parse: parsed.

- from setuptools import setup @5

### python/mozterm/test/test_terminal.py

Blob: `a24dd01ba4e0a7fc7b02ad69e6c81f8e0acc979d`. Parse: parsed.

- import os @5
- import sys @6
- import mozunit @8
- import pytest @9
- from mozterm import NullTerminal,Terminal @11
- function test_terminal @14-20
- function test_null_terminal @23-31

### python/mozversioncontrol/mozversioncontrol/__init__.py

Blob: `c03b334df1b3e514adf2116439d7741dc2be747d`. Parse: parsed.

- from mozversioncontrol.errors import * @5
- from mozversioncontrol.factory import get_repository_from_build_config,get_repository_from_env,get_repository_object @6
- from mozversioncontrol.repo.base import HG_TRY_URL,Repository @11
- from mozversioncontrol.repo.git import GitRepository @12
- from mozversioncontrol.repo.jj import JujutsuRepository @13
- from mozversioncontrol.repo.mercurial import HgRepository @14
- from mozversioncontrol.repo.source import SrcRepository @15

### python/mozversioncontrol/mozversioncontrol/errors.py

Blob: `d47cc4e6ab0928e1af698fde1b729e7668e55f2c`. Parse: parsed.

- class MissingVCSTool @6-7
- class MissingVCSInfo @10-11
- class MissingConfigureInfo @14-15
- class MissingVCSExtension @18-24
- function MissingVCSExtension.__init__ @21-24
- class InvalidRepoPath @27-28
- class MissingUpstreamRepo @31-32
- class CannotDeleteFromRootOfRepositoryException @35-37
- class StaleWorkspaceError @40-44

### python/mozversioncontrol/mozversioncontrol/factory.py

Blob: `b9792477854c43fbead03c4d92f38a783bedb4b5`. Parse: parsed.

- from __future__ import annotations @5
- import os @7
- import re @8
- import subprocess @9
- from functools import cache @10
- from pathlib import Path @11
- from typing import Literal,Optional,Union,overload @12
- from packaging.version import Version @14
- from mozversioncontrol.errors import InvalidRepoPath,MissingConfigureInfo,MissingVCSInfo,MissingVCSTool @16
- from mozversioncontrol.repo.git import GitRepository @22
- from mozversioncontrol.repo.jj import MINIMUM_SUPPORTED_JJ_VERSION,JjVersionError,JujutsuRepository @23
- from mozversioncontrol.repo.mercurial import HgRepository @28
- from mozversioncontrol.repo.source import SrcRepository @29
- function get_specific_repository_object @40-42
- function get_specific_repository_object @46-48
- function get_specific_repository_object @52-54
- function get_specific_repository_object @58-60
- function get_specific_repository_object @63-73
- function _check_jj_version @77-105
- function get_repository_object @108-128
- function get_repository_from_build_config @131-159
- function get_repository_from_env @162-187
- import buildconfig @171

### python/mozversioncontrol/mozversioncontrol/repo/base.py

Blob: `34d4b60927c1ed762a02d930b453274932cc60ac`. Parse: parsed.

- from __future__ import annotations @5
- import abc @7
- import os @8
- import re @9
- import subprocess @10
- from contextlib import contextmanager @11
- from pathlib import Path @12
- from typing import Callable,Optional,Union @13
- from mach.util import batch_paths,to_optional_path @15
- from mozfile import which @16
- from mozversioncontrol.errors import MissingVCSInfo,MissingVCSTool @18
- function get_tool_path @23-36
- class Repository @39-486
- function Repository.__init__ @49-54
- function Repository.__enter__ @56-57
- function Repository.__exit__ @59-60
- function Repository._repo_root_relative_path @62-71
- function Repository._run @73-99
- function Repository._run_batched @101-103
- function Repository._pipefrom @105-113
- function Repository.tool_version @116-126
- function Repository.has_git_cinnabar @129-131
- function Repository.name @135-136
- function Repository.head_ref @140-141
- function Repository.head_rev @145-146
- function Repository.is_cinnabar_repo @150-151
- function Repository.base_ref @155-156
- function Repository.base_ref_as_hg @159-163
- function Repository.base_ref_as_commit @166-167
- function Repository.branch @171-172
- function Repository.get_commit_time @175-176
- function Repository.sparse_checkout_present @179-186
- function Repository.get_user_email @189-193
- function Repository.get_remote_url @196-197
- function Repository.get_changed_files @200-218
- function Repository.diff_stream @221-222
- function Repository.get_outgoing_files @225-232
- function Repository.add_remove_files @235-236
- function Repository.forget_add_remove_files @239-240
- function Repository.get_tracked_files_finder @243-250
- function Repository.get_ignored_files_finder @253-260
- function Repository.working_directory_clean @263-272
- function Repository.clean_directory @275-278
- function Repository.push @281-296
- function Repository.add_note @298-310
- function Repository._resolve_try_branch @313-314
- function Repository._push_to_git_try @316-338
- function Repository._push_to_hg_try @341-342
- function Repository.push_to_try @344-367
- function Repository.update @370-371
- function Repository.commit @373-393
- function Repository._push_to_try_with_log_capture @395-421
- function Repository.get_commits @424-430
- function Repository.get_commit_patches @433-434
- function Repository.try_commit @438-448
- function Repository.prepare_try_push @451-454
- function Repository.stage_changes @456-471
- function Repository.get_last_modified_time_for_file @474-476
- function Repository.configure @479-486

### python/mozversioncontrol/mozversioncontrol/repo/git.py

Blob: `76fdf5a6132ebca777e5b9ccf3cd662039b3c3ef`. Parse: parsed.

- from __future__ import annotations @5
- import os @7
- import platform @8
- import re @9
- import shutil @10
- import stat @11
- import subprocess @12
- import sys @13
- import uuid @14
- from collections.abc import Iterator @15
- from contextlib import contextmanager @16
- from datetime import datetime @17
- from pathlib import Path @18
- from typing import Callable,Optional,Union @19
- from mach.util import to_optional_path,win_to_msys_path @21
- from mozfile import which @25
- from mozpack.files import FileListFinder @26
- from packaging.version import Version @27
- from mozversioncontrol.errors import CannotDeleteFromRootOfRepositoryException,MissingVCSExtension @29
- from mozversioncontrol.repo.base import Repository @33
- class GitVersionError @51-54
- class GitRepository @57-841
- function GitRepository.__init__ @60-61
- function GitRepository.name @64-65
- function GitRepository.head_ref @68-69
- function GitRepository.head_rev @72-73
- function GitRepository.is_cinnabar_repo @75-89
- function GitRepository.get_mozilla_upstream_remotes @91-136
- function GitRepository.get_mozilla_upstream_remotes.is_official_remote @103-122
- function GitRepository.get_mozilla_remote_args @138-144
- function GitRepository.base_ref @147-155
- function GitRepository.base_ref_as_hg @157-162
- function GitRepository.base_ref_as_commit @164-165
- function GitRepository.branch @168-173
- function GitRepository.has_git_cinnabar @176-181
- function GitRepository.get_commit_time @183-184
- function GitRepository.sparse_checkout_present @186-188
- function GitRepository.get_user_email @190-194
- function GitRepository.get_user_name @196-200
- function GitRepository.get_remote_url @202-220
- function GitRepository.get_changed_files @222-237
- function GitRepository.get_outgoing_files @239-255
- function GitRepository.add_remove_files @257-268
- function GitRepository.forget_add_remove_files @270-276
- function GitRepository.get_tracked_files_finder @278-280
- function GitRepository.get_ignored_files_finder @282-290
- function GitRepository._translate_exclude_expr @292-300
- function GitRepository.diff_stream @302-318
- function GitRepository.working_directory_clean @320-334
- function GitRepository.clean_directory @336-341
- function GitRepository.update @343-344
- function GitRepository.push @346-379
- function GitRepository._resolve_try_branch @381-386
- function GitRepository._push_to_hg_try @388-416
- function GitRepository.add_note @418-426
- function GitRepository.set_config @428-429
- function GitRepository.get_commits @431-453
- function GitRepository.get_commit_patches @455-468
- function GitRepository.try_commit @471-484
- function GitRepository.prepare_try_push @486-564
- function GitRepository.prepare_try_push.data @502-503
- function GitRepository.prepare_try_push.cleanup @544-562
- function GitRepository.get_last_modified_time_for_file @566-570
- function GitRepository.get_config_key_value @572-576
- function GitRepository.set_config_key_value @578-584
- function GitRepository.configure @586-680
- function GitRepository._update_git_cinnabar @682-756
- function GitRepository._update_git_cinnabar.onerror @709-714
- import ssl @730
- from urllib.request import urlopen @731
- import certifi @733
- function GitRepository._ensure_watchman @758-803
- function GitRepository.get_patches_after_ref @805-812
- function GitRepository.get_patch_for_uncommitted_changes @814-841

### python/mozversioncontrol/mozversioncontrol/repo/jj.py

Blob: `3ddb22c8e9511e92b715b3263cc8c75e758d73e5`. Parse: parsed.

- from __future__ import annotations @5
- import json @7
- import re @8
- import string @9
- import subprocess @10
- import sys @11
- from contextlib import contextmanager @12
- from datetime import datetime @13
- from pathlib import Path @14
- from typing import Any,Callable,Optional,Union @15
- import mozpack.path @17
- from mozfile import which @18
- from mozpack.files import FileListFinder @19
- from packaging.version import Version @20
- from mozversioncontrol.errors import CannotDeleteFromRootOfRepositoryException,MissingVCSExtension,MissingVCSInfo,StaleWorkspaceError @24
- from mozversioncontrol.repo.base import Repository @30
- from mozversioncontrol.repo.git import GitRepository @31
- class JjVersionError @34-37
- class JujutsuRepository @40-773
- function JujutsuRepository.__init__ @48-68
- function JujutsuRepository._run @70-72
- function JujutsuRepository._run_read_only @74-79
- function JujutsuRepository._snapshot @81-91
- function JujutsuRepository._resolve_to_change @93-103
- function JujutsuRepository.name @106-107
- function JujutsuRepository.head_ref @110-119
- function JujutsuRepository.head_rev @122-123
- function JujutsuRepository.is_cinnabar_repo @125-126
- function JujutsuRepository.base_ref @129-130
- function JujutsuRepository._resolve_to_commit @132-141
- function JujutsuRepository.base_ref_as_hg @143-144
- function JujutsuRepository.base_ref_as_commit @146-147
- function JujutsuRepository.branch @150-163
- function JujutsuRepository.has_git_cinnabar @166-167
- function JujutsuRepository.get_commit_time @169-178
- function JujutsuRepository.sparse_checkout_present @180-181
- function JujutsuRepository.get_user_email @183-187
- function JujutsuRepository.get_remote_url @189-208
- function JujutsuRepository.get_changed_files @210-244
- function JujutsuRepository._translate_exclude_expr @253-270
- function JujutsuRepository.diff_stream @272-294
- function JujutsuRepository.get_outgoing_files @296-316
- function JujutsuRepository.add_remove_files @318-323
- function JujutsuRepository.forget_add_remove_files @325-330
- function JujutsuRepository.get_tracked_files_finder @332-334
- function JujutsuRepository.get_ignored_files_finder @336-337
- function JujutsuRepository.working_directory_clean @339-341
- function JujutsuRepository.update @343-344
- function JujutsuRepository.edit @346-347
- function JujutsuRepository.clean_directory @349-353
- function JujutsuRepository.commit @355-365
- function JujutsuRepository.add_note @367-374
- function JujutsuRepository.push @376-391
- function JujutsuRepository._resolve_try_branch @393-414
- function JujutsuRepository._push_to_hg_try @416-452
- function JujutsuRepository.set_config @454-455
- function JujutsuRepository.get_commits @457-478
- function JujutsuRepository._looks_like_change_id @480-481
- function JujutsuRepository._looks_like_commit_id @483-484
- function JujutsuRepository.get_commit_patches @486-505
- function JujutsuRepository.try_commit @508-526
- function JujutsuRepository.prepare_try_push @528-591
- function JujutsuRepository.prepare_try_push.cleanup @580-581
- function JujutsuRepository.get_last_modified_time_for_file @593-604
- function JujutsuRepository.config_key_list_value_missing @606-620
- function JujutsuRepository.set_config_key_value @622-625
- function JujutsuRepository._set_default_if_missing @627-634
- function JujutsuRepository._get_config_value @636-641
- function JujutsuRepository._migrate_config_value @643-652
- function JujutsuRepository._copy_from_git_if_missing @654-663
- function JujutsuRepository.configure @665-773

### python/mozversioncontrol/mozversioncontrol/repo/mercurial.py

Blob: `177bac3794a73c526aef227f42ac742f0ad40b1c`. Parse: parsed.

- from __future__ import annotations @5
- import errno @7
- import os @8
- import re @9
- import shutil @10
- import subprocess @11
- from contextlib import contextmanager @12
- from datetime import datetime @13
- from pathlib import Path @14
- from typing import Callable,Optional,Union @15
- from mozpack.files import FileListFinder @17
- from mozversioncontrol.errors import CannotDeleteFromRootOfRepositoryException,MissingVCSExtension @19
- from mozversioncontrol.repo.base import HG_TRY_URL,Repository @23
- class HgRepository @26-533
- function HgRepository.__init__ @29-45
- import hglib.client @30
- function HgRepository.name @48-49
- function HgRepository.head_ref @52-53
- function HgRepository.head_rev @56-57
- function HgRepository.is_cinnabar_repo @59-60
- function HgRepository.base_ref @63-64
- function HgRepository.base_ref_as_hg @66-67
- function HgRepository.base_ref_as_commit @69-70
- function HgRepository.branch @73-80
- function HgRepository.__enter__ @82-93
- function HgRepository.__exit__ @95-96
- function HgRepository._run @98-104
- function HgRepository.get_commit_time @106-125
- function HgRepository.sparse_checkout_present @127-142
- function HgRepository.get_user_email @144-154
- function HgRepository.get_remote_url @156-162
- function HgRepository._format_diff_filter @164-171
- function HgRepository._files_template @173-182
- function HgRepository.get_changed_files @184-191
- function HgRepository.get_outgoing_files @193-210
- function HgRepository.add_remove_files @212-223
- function HgRepository.forget_add_remove_files @225-231
- function HgRepository.get_tracked_files_finder @233-238
- function HgRepository.get_ignored_files_finder @240-247
- function HgRepository.diff_stream @249-259
- function HgRepository.working_directory_clean @261-270
- function HgRepository.clean_directory @272-281
- function HgRepository.update @283-284
- function HgRepository.raise_for_missing_extension @286-291
- function HgRepository.push @293-313
- function HgRepository._resolve_try_branch @315-316
- function HgRepository._push_to_git_try @318-319
- function HgRepository._push_to_hg_try @321-355
- function HgRepository.get_commits @357-382
- function HgRepository.get_commit_patches @384-412
- function HgRepository.try_commit @415-428
- function HgRepository.prepare_try_push @430-459
- function HgRepository.prepare_try_push.cleanup @451-457
- function HgRepository.get_last_modified_time_for_file @461-473
- function HgRepository._update_mercurial_repo @475-502
- function HgRepository._update_vct @504-513
- function HgRepository.configure @515-533

### python/mozversioncontrol/mozversioncontrol/repo/source.py

Blob: `c469b0c41e3f041b805ac443961993f375f1d6e8`. Parse: parsed.

- from __future__ import annotations @5
- import contextlib @7
- import os @8
- from pathlib import Path @9
- from typing import Callable,Optional,Union @10
- from mozpack.files import FileListFinder @12
- from mozversioncontrol.errors import MissingVCSTool @14
- from mozversioncontrol.repo.base import Repository @15
- class SrcRepository @18-198
- function SrcRepository.__init__ @21-22
- function SrcRepository.name @25-26
- function SrcRepository.head_ref @29-30
- function SrcRepository.head_rev @33-34
- function SrcRepository.is_cinnabar_repo @36-37
- function SrcRepository.base_ref @40-41
- function SrcRepository.base_ref_as_hg @43-44
- function SrcRepository.base_ref_as_commit @46-47
- function SrcRepository.branch @50-51
- function SrcRepository.has_git_cinnabar @54-55
- function SrcRepository.get_commit_time @57-58
- function SrcRepository.sparse_checkout_present @60-61
- function SrcRepository.get_user_email @63-64
- function SrcRepository.get_upstream @66-67
- function SrcRepository.get_remote_url @69-70
- function SrcRepository.get_changed_files @72-73
- function SrcRepository.diff_stream @75-76
- function SrcRepository.get_outgoing_files @78-79
- function SrcRepository.add_remove_files @81-82
- function SrcRepository.forget_add_remove_files @84-85
- function SrcRepository.get_ignored_files_finder @87-88
- function SrcRepository.git_ignore @90-105
- function SrcRepository.get_files @107-117
- function SrcRepository.get_tracked_files_finder @119-141
- import fnmatch @124
- function SrcRepository.working_directory_clean @143-144
- function SrcRepository.clean_directory @146-147
- function SrcRepository.update @149-150
- function SrcRepository.push @152-160
- function SrcRepository._resolve_try_branch @162-163
- function SrcRepository._push_to_git_try @165-166
- function SrcRepository._push_to_hg_try @168-169
- function SrcRepository.set_config @171-172
- function SrcRepository.get_commits @174-175
- function SrcRepository.get_commit_patches @177-178
- function SrcRepository.try_commit @180-181
- function SrcRepository.prepare_try_push @183-186
- function SrcRepository.get_last_modified_time_for_file @188-190
- function SrcRepository.configure @192-198

### python/mozversioncontrol/mozversioncontrol/repoupdate.py

Blob: `5f8af8f8b7a7af8997150a8e4f854235632b5e0d`. Parse: parsed.

- import subprocess @5
- from pathlib import Path @6
- from typing import Union @7
- from mozversioncontrol.repo.base import get_tool_path @9
- function update_git_repo @14-21
- function update_mercurial_repo @24-49

### python/mozversioncontrol/setup.py

Blob: `c0e1aa643f8979476220c5ae6c8bbc47937f658c`. Parse: parsed.

- from setuptools import find_packages,setup @5

### python/mozversioncontrol/test/conftest.py

Blob: `c1932b73cbf5ab4c9c622a00c4cdbab76c2f8db4`. Parse: parsed.

- from __future__ import annotations @5
- import os @7
- import platform @8
- import shutil @9
- import subprocess @10
- import tempfile @11
- from pathlib import Path @12
- import pytest @14
- function setup_hg_default_path @17-23
- class RepoTestFixture @90-100
- function RepoTestFixture.__init__ @91-97
- function RepoTestFixture.execute_next_step @99-100
- function shell @103-112
- function repo @116-179

### python/mozversioncontrol/test/test_branch.py

Blob: `5403953a9d0a3b82d5dd14a6a7457f2341ba9793`. Parse: parsed.

- import re @5
- import mozunit @7
- from mozversioncontrol import get_repository_object @9
- function test_branch @34-54
- function test_jj_branch_diverged_bookmark @57-75
- function test_head_rev @78-80

### python/mozversioncontrol/test/test_commit.py

Blob: `62eeca76076ef64f3b1c9160f0a81309b6fa800e`. Parse: parsed.

- import re @5
- from datetime import datetime @6
- from pathlib import Path @7
- import mozunit @9
- from mozversioncontrol import get_repository_object @11
- function test_commit @42-142
- function test_commit.find_diff_marker @111-130

### python/mozversioncontrol/test/test_context_manager.py

Blob: `865194eabd70449789557a0c55e7225f197623ea`. Parse: parsed.

- import mozunit @5
- from mozversioncontrol import get_repository_object @7
- function test_context_manager @10-35

### python/mozversioncontrol/test/test_diff_stream.py

Blob: `fa19114ecd47b338e24cd8dfb1180ab653e709d7`. Parse: parsed.

- import re @5
- import mozunit @7
- from mozversioncontrol import get_repository_object @9
- function test_diff_stream @94-160
- function test_diff_stream.changed_files @104-114

### python/mozversioncontrol/test/test_get_commit_patches.py

Blob: `84526e7477ca26f5446b609ad041e2e94314d5b8`. Parse: parsed.

- import mozunit @5
- from mozversioncontrol import get_repository_object @7
- function test_get_commit_patches @48-66

### python/mozversioncontrol/test/test_get_commits.py

Blob: `52b2c63dc8d567c636805214bac00e970cb9b9e6`. Parse: parsed.

- import mozunit @5
- from mozversioncontrol import get_repository_object @7
- function test_get_commits @42-52

### python/mozversioncontrol/test/test_get_mozilla_remote_args.py

Blob: `07fd17440a78ad20c272207b538a29a076967086`. Parse: parsed.

- from unittest import mock @5
- import mozunit @7
- import pytest @8
- from mozversioncontrol import get_repository_object @10
- function test_get_mozilla_remote_args @41-64

### python/mozversioncontrol/test/test_get_remote_url.py

Blob: `e8501f9d12608bbbaec1d0eefb2393e5ac31311f`. Parse: parsed.

- import subprocess @5
- from pathlib import Path @6
- import mozunit @8
- import pytest @9
- from mozversioncontrol import get_repository_object @11
- function setup_hg_test_paths @14-22
- function test_get_remote_url_default @53-68
- function test_get_remote_url_push @71-89
- function test_get_remote_url_specific @119-134
- function test_get_remote_url_unconfigured @137-145
- function test_get_remote_url_with_no_branch_tracking @148-163

### python/mozversioncontrol/test/test_get_upstream_remotes.py

Blob: `a27aaa9e283d734ede305cdb0dec8c95f6247cee`. Parse: parsed.

- from unittest import mock @5
- import mozunit @7
- import pytest @8
- from mozversioncontrol import get_repository_object @10
- function test_get_upstream_remotes @41-60

### python/mozversioncontrol/test/test_notes.py

Blob: `4f6daaa4c0c992f5db14d5927d07c2c78a6cc967`. Parse: parsed.

- import subprocess @5
- import mozunit @7
- import pytest @8
- from mozversioncontrol import get_repository_object @10
- function test_add_note @13-29

### python/mozversioncontrol/test/test_prepare_try_push.py

Blob: `5e3240cde2e4006d5f9b32e35ccef161ba943ad4`. Parse: parsed.

- import mozunit @1
- import pytest @2
- from mozversioncontrol import get_repository_object @4
- from mozversioncontrol.errors import MissingVCSExtension @5
- function test_prepare_try_push_cleanup_restores_state @8-27
- function test_prepare_try_push_cleanup_idempotent @30-46

### python/mozversioncontrol/test/test_push.py

Blob: `bf8ae251159c6d88abe9a4c8e5bd815fd8a73354`. Parse: parsed.

- import subprocess @5
- import unittest.mock @6
- import mozunit @8
- import pytest @9
- from mozversioncontrol import get_repository_object @11
- function verify_push_succeeded @39-83
- function test_push @95-120
- function test_push_ref_without_remote_raises @123-129
- function test_jj_push_url_to_name_translation @132-156
- function test_push_dest_branch @163-218
- function test_jj_push_change_id_with_dest_branch @221-246
- function test_push_env_passthrough @249-267

### python/mozversioncontrol/test/test_push_to_try.py

Blob: `3bba0165357495eb149e5ab94cadffb5d81d88d5`. Parse: parsed.

- import os @5
- import subprocess @6
- import textwrap @7
- import uuid @8
- import mozunit @10
- import pytest @11
- from mozversioncontrol import MissingVCSExtension,get_repository_object @13
- function test_push_to_try @16-258
- function test_push_to_try.fake_run @26-39
- function test_push_to_try.fake_subprocess_run @41-42
- function test_push_to_try.normalize_fake_run @44-53
- function test_push_to_try.fake_uuid @55-56
- function test_push_to_git_try @261-276
- function test_push_to_git_try_creates_bookmark @279-312
- function test_push_to_git_try_creates_bookmark.fake_run_read_only @290-297
- function test_push_to_git_try_bookmark_persists @315-342
- function test_push_to_try_missing_extensions @345-364
- function test_push_to_try_missing_extensions.cinnabar_raises @353-357

### python/mozversioncontrol/test/test_try_commit.py

Blob: `9c847a612507731e77822d3f7fb8f4bc84fc9c7f`. Parse: parsed.

- import mozunit @5
- import pytest @6
- from mozversioncontrol import get_repository_object @8
- from mozversioncontrol.errors import MissingVCSExtension @9
- function test_try_commit @12-35

### python/mozversioncontrol/test/test_update.py

Blob: `53657ac6907e70d6b508a8430ac602346b9f16d5`. Parse: parsed.

- from subprocess import CalledProcessError @5
- import mozunit @7
- import pytest @8
- from mozversioncontrol import get_repository_object @10
- function test_update @47-75

### python/mozversioncontrol/test/test_workdir_outgoing.py

Blob: `0ebcc91b34003ea07b3109e61152ec70a0326f09`. Parse: parsed.

- import os @5
- import mozunit @7
- from mozversioncontrol import get_repository_object @9
- function assert_files @73-74
- function test_workdir_outgoing @77-142

### python/mozversioncontrol/test/test_working_directory.py

Blob: `6314fc71736b58c7b28aac68c42a133b894f1119`. Parse: parsed.

- import mozunit @5
- from mozversioncontrol import get_repository_object @7
- function test_working_directory_clean_untracked_files @34-46

## Validation and limits

The parser checked syntax only. This pass cannot prove runtime contracts, ownership, selected build settings, executed branches, or design reasons. Build files use a Python-based domain-specific language; parsing them as Python does not validate the build system. Byte decoding uses UTF-8; special encoding declarations and intentionally invalid fixtures may fail.
