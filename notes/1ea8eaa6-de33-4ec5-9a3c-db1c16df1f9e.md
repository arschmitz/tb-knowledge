<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:18:44.114924+00:00", "paths": ["nsprpub/automation/release/nspr-release-helper.py", "nsprpub/build/win32/pgomerge.py", "nsprpub/prdepend.py"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/nsprpub Python and build syntax map 42

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Python AST parser; no source was executed. Functions and classes have source ranges. Imports are written names, not resolved modules. Build entries list assignments with literal string lists and registration calls. Conditions are not evaluated; listed files are not necessarily built or shipped. Dynamic expressions and included build files need separate analysis. Failed parses remain listed.

### nsprpub/automation/release/nspr-release-helper.py

Blob: `65292395c071edad47a1ab983360e0dbc5ffd8ba`. Parse: parsed.

- import os @7
- import sys @8
- from optparse import OptionParser @9
- from subprocess import check_call @10
- function check_call_noisy @17-19
- function exit_with_failure @34-36
- function check_files_exist @39-43
- function sed_inplace @46-49
- function toggle_beta_status @52-67
- function print_beta_versions @70-71
- function remove_beta_status @74-79
- function set_beta_status @82-87
- function print_library_versions @90-98
- function ensure_arguments_after_action @101-105
- function set_major_versions @108-111
- function set_minor_versions @114-117
- function set_patch_versions @120-123
- function set_full_lib_versions @126-132
- function set_all_lib_versions @135-150
- function set_version_to_minor_release @153-159
- function set_version_to_patch_release @162-168
- function create_nspr_release_archive @171-199

### nsprpub/build/win32/pgomerge.py

Blob: `6206387c68776a25dc00c57a619ed9b9e24a6d50`. Parse: parsed.

- import os @11
- import os.path @12
- import subprocess @13
- import sys @14
- function MergePGOFiles @20-41

### nsprpub/prdepend.py

Blob: `bb4ec9fa1bed081b5d74bc57c87e7ed4a93afdf6`. Parse: parsed.


## Validation and limits

The parser checked syntax only. This pass cannot prove runtime contracts, ownership, selected build settings, executed branches, or design reasons. Build files use a Python-based domain-specific language; parsing them as Python does not validate the build system. Byte decoding uses UTF-8; special encoding declarations and intentionally invalid fixtures may fail.
