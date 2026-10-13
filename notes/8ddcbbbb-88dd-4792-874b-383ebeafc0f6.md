<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:18:44.114924+00:00", "paths": ["toolkit/components/workerloader/moz.build", "toolkit/components/xulstore/moz.build", "toolkit/content/gen_license_html.py", "toolkit/content/licenses/moz.build", "toolkit/content/moz.build", "toolkit/content/neterror/gen_aboutneterror_codes.py", "toolkit/content/tests/chrome/file_about_networking_wsh.py", "toolkit/content/tests/moz.build", "toolkit/content/widgets/mach_commands.py", "toolkit/crashreporter/android/export/moz.build", "toolkit/crashreporter/android/moz.build", "toolkit/crashreporter/annotations/generate.py", "toolkit/crashreporter/annotations/load.py", "toolkit/crashreporter/annotations/moz.build", "toolkit/crashreporter/breakpad-client/linux/moz.build", "toolkit/crashreporter/breakpad-client/mac/crash_generation/moz.build", "toolkit/crashreporter/breakpad-client/mac/handler/moz.build", "toolkit/crashreporter/breakpad-client/moz.build", "toolkit/crashreporter/breakpad-client/windows/common/objs.mozbuild", "toolkit/crashreporter/breakpad-client/windows/crash_generation/objs.mozbuild", "toolkit/crashreporter/breakpad-client/windows/handler/objs.mozbuild", "toolkit/crashreporter/breakpad-client/windows/sender/objs.mozbuild", "toolkit/crashreporter/breakpad-windows-libxul/moz.build", "toolkit/crashreporter/breakpad_wrapper/moz.build", "toolkit/crashreporter/client/app/moz.build", "toolkit/crashreporter/crash_helper/moz.build", "toolkit/crashreporter/crash_helper_client/moz.build", "toolkit/crashreporter/crash_helper_server/moz.build", "toolkit/crashreporter/crashping/conversions.py", "toolkit/crashreporter/crashping/glean_metrics.py", "toolkit/crashreporter/crashping/glean_rust.py", "toolkit/crashreporter/crashping/moz.build", "toolkit/crashreporter/crashreporter.mozbuild", "toolkit/crashreporter/google-breakpad/src/common/linux/moz.build", "toolkit/crashreporter/google-breakpad/src/common/mac/moz.build", "toolkit/crashreporter/google-breakpad/src/common/moz.build", "toolkit/crashreporter/google-breakpad/src/common/windows/objs.mozbuild", "toolkit/crashreporter/google-breakpad/src/processor/moz.build", "toolkit/crashreporter/google-breakpad/src/tools/python/deps-to-manifest.py", "toolkit/crashreporter/google-breakpad/src/tools/python/filter_syms.py", "toolkit/crashreporter/google-breakpad/src/tools/python/tests/filter_syms_unittest.py", "toolkit/crashreporter/moz.build", "toolkit/crashreporter/mozannotation_client/moz.build", "toolkit/crashreporter/mozwer-rust/moz.build", "toolkit/crashreporter/mozwer/moz.build", "toolkit/crashreporter/networking/moz.build", "toolkit/crashreporter/rust_minidump_writer_linux/moz.build", "toolkit/crashreporter/test/gtest/moz.build", "toolkit/crashreporter/test/moz.build", "toolkit/crashreporter/test/test_utils/moz.build", "toolkit/crashreporter/tools/symbolstore.py", "toolkit/crashreporter/tools/unit-symbolstore.py", "toolkit/crashreporter/tools/upload_symbols.py", "toolkit/library/build/dependentlibs.py", "toolkit/library/build/moz.build", "toolkit/library/buildid_reader/moz.build", "toolkit/library/gen_buildid.py", "toolkit/library/gtest/libxul_broken_buildid/moz.build", "toolkit/library/gtest/libxul_correct_buildid/moz.build", "toolkit/library/gtest/libxul_missing_buildid/moz.build", "toolkit/library/gtest/moz.build", "toolkit/library/gtest/rust/moz.build", "toolkit/library/libxul.so-gdb.py", "toolkit/library/moz.build", "toolkit/library/rust/gkrust-features.mozbuild", "toolkit/library/rust/moz.build", "toolkit/locales/gen_multilocale.py", "toolkit/locales/generate_default_locale.py", "toolkit/locales/moz.build", "toolkit/modules/launchonlogin/moz.build", "toolkit/modules/moz.build", "toolkit/modules/subprocess/moz.build", "toolkit/modules/subprocess/test/xpcshell/data_test_child.py", "toolkit/modules/subprocess/test/xpcshell/data_test_script.py", "toolkit/modules/tests/marionette/test_first_startup.py", "toolkit/moz.build", "toolkit/moz.configure", "toolkit/mozapps/defaultagent/moz.build", "toolkit/mozapps/defaultagent/proxy/moz.build", "toolkit/mozapps/defaultagent/tests/gtest/moz.build", "toolkit/mozapps/dmgInstallHelper/moz.build", "toolkit/mozapps/downloads/moz.build", "toolkit/mozapps/downloads/tests/moz.build", "toolkit/mozapps/extensions/gen_built_in_addons.py", "toolkit/mozapps/extensions/internal/moz.build", "toolkit/mozapps/extensions/moz.build", "toolkit/mozapps/extensions/test/browser/moz.build", "toolkit/mozapps/extensions/test/create_xpi.py", "toolkit/mozapps/extensions/test/moz.build", "toolkit/mozapps/handling/moz.build", "toolkit/mozapps/installer/find-dupes.py", "toolkit/mozapps/installer/informulate.py", "toolkit/mozapps/installer/moz.build", "toolkit/mozapps/installer/packager.py", "toolkit/mozapps/installer/strip.py", "toolkit/mozapps/installer/unify.py", "toolkit/mozapps/installer/unpack.py", "toolkit/mozapps/installer/windows/nsis/preprocess-locale.py", "toolkit/mozapps/macos-frameworks/ChannelPrefs-localbuild/moz.build", "toolkit/mozapps/macos-frameworks/ChannelPrefs/moz.build"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/toolkit Python and build syntax map 170

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Python AST parser; no source was executed. Functions and classes have source ranges. Imports are written names, not resolved modules. Build entries list assignments with literal string lists and registration calls. Conditions are not evaluated; listed files are not necessarily built or shipped. Dynamic expressions and included build files need separate analysis. Failed parses remain listed.

### toolkit/components/workerloader/moz.build

Blob: `15a1c8e3421db9d579c1f9d4897ad9dbddabe839`. Parse: parsed.

- build assignment MOCHITEST_CHROME_MANIFESTS @5: ["tests/chrome.toml"]
- build assignment EXTRA_JS_MODULES.workers @7: ["require.js"]
- build assignment BUG_COMPONENT @10: ["Toolkit", "Async Tooling"]

### toolkit/components/xulstore/moz.build

Blob: `59ea28bbd618bb83f8471d9ecacf24fdfa200562`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Toolkit", "Startup and Profile System"]
- build assignment MOCHITEST_CHROME_MANIFESTS @8: ["tests/chrome/chrome.toml"]
- build assignment XPCSHELL_TESTS_MANIFESTS @9: ["tests/xpcshell/xpcshell.toml"]
- build assignment XPIDL_SOURCES @13: ["nsIXULStore.idl"]
- build assignment XPCOM_MANIFESTS @17: ["components.conf"]
- build assignment EXTRA_JS_MODULES @21: ["XULStore.sys.mjs"]
- build assignment SOURCE_HEADERS @25: ["XULStore.h"]

### toolkit/content/gen_license_html.py

Blob: `31c73e3cb8c25dc7c507e5021dd7c719d8a72f0f`. Parse: parsed.

- import html @13
- import json @14
- import os @15
- import re @16
- from mako.template import Template @18
- function sort_key @25-29
- function leads_paths @50-57
- function notice_names_paths @63-71
- function read_blocks @74-83
- function render @86-110
- function main @113-144
- import buildconfig @114

### toolkit/content/licenses/moz.build

Blob: `537996f57b2d8c950d0d46dd6f6c945a5e37e56d`. Parse: parsed.

- build assignment LICENSES @9: ["mpl"]
- build assignment LICENSES @14: ["lgpl"]
- build assignment LICENSES @28: ["lgpl-3.0"]
- build assignment LICENSES @40: ["acorn"]
- build assignment LICENSES @49: ["apache"]
- build assignment LICENSES['apache'].paths @56: ["third_party/cups/include", "third_party/rust/calendrical_calculations"]
- build assignment LICENSES['apache'].paths @64: ["third_party/rust/font-types/", "third_party/rust/read-fonts/", "third_party/rust/skrifa/"]
- build assignment LICENSES @71: ["apache-llvm"]
- build assignment LICENSES @76: ["apple"]
- build assignment LICENSES @84: ["apple-password-rules-parser"]
- build assignment LICENSES @92: ["arm"]
- build assignment LICENSES @100: ["boost"]
- build assignment LICENSES['boost'].paths @108: ["third_party/function2"]
- build assignment LICENSES @112: ["bsd2clause"]
- build assignment LICENSES['bsd2clause'].paths @120: ["third_party/dav1d", "third_party/rust/arrayref", "third_party/rust/mach2", "third_party/rust/qlog"]
- build assignment LICENSES @127: ["bsd3clause"]
- build assignment LICENSES['bsd3clause'].paths @136: ["third_party/node/node_modules/react-transition-group/", "third_party/rust/bindgen/", "third_party/rust/subtle/", "third_party/rust/uritemplate-next/", "third_party/xsimd/"]
- build assignment LICENSES['bsd3clause'].paths @144: ["third_party/rust/jxl", "third_party/rust/jxl_macros", "third_party/rust/jxl_simd", "third_party/rust/jxl_transforms"]
- build assignment LICENSES @151: ["bspatch"]
- build assignment LICENSES @161: ["chromium"]
- build assignment LICENSES @169: ["codemirror"]
- build assignment LICENSES @177: ["cryptogams"]
- build assignment LICENSES @186: ["cubic-bezier"]
- build assignment LICENSES @194: ["d3"]
- build assignment LICENSES['d3'].paths @201: ["third_party/js/d3/d3.js"]
- build assignment LICENSES @205: ["dagre-d3"]
- build assignment LICENSES @213: ["diff"]
- build assignment LICENSES @221: ["disconnect.me"]
- build assignment LICENSES @236: ["dtoa"]
- build assignment LICENSES['dtoa'].paths @242: ["nsprpub/pr/src/misc/dtoa.c"]
- build assignment LICENSES @246: ["hunspell-nl"]
- build assignment LICENSES @254: ["hunspell-en"]
- build assignment LICENSES @263: ["hunspell-ee"]
- build assignment LICENSES @271: ["firebug"]
- build assignment LICENSES @278: ["gfx-font-list"]
- build assignment LICENSES @287: ["google-bsd"]
- build assignment LICENSES @295: ["gears-istumbler"]
- build assignment LICENSES @303: ["gyp"]
- build assignment LICENSES['gyp'].paths @310: ["third_party/python/gyp"]
- build assignment LICENSES @314: ["harfbuzz"]
- build assignment LICENSES @330: ["immutable"]
- build assignment LICENSES @335: ["jquery"]
- build assignment LICENSES @343: ["k_exp"]
- build assignment LICENSES @352: ["libc++"]
- build assignment LICENSES @360: ["libevent"]
- build assignment LICENSES @368: ["libffi"]
- build assignment LICENSES @376: ["libjingle"]
- build assignment LICENSES @384: ["hunspell-lt"]
- build assignment LICENSES @392: ["lodash"]
- build assignment LICENSES @400: ["mit"]
- build assignment LICENSES['mit'].paths @409: ["third_party/js/cfworker/json-schema.js", "third_party/node/node_modules/@babel/runtime", "third_party/node/node_modules/dom-helpers", "third_party/node/node_modules/js-tokens", "third_party/node/node_modules/loose-envify", "third_party/node/node_modules/object-assign", "third_party/node/node_modules/prop-types", "third_party/node/node_modules/react", "third_party/node/node_modules/react-dom", "third_party/node/node_modules/react-is", "third_party/node/node_modules/scheduler", "third_party/node/node_modules/use-sync-external-store", "third_party/node/node_modules/webpack", "third_party/node/node_modules/webpack-cli", "third_party/rlbox", "third_party/rust/bincode", "third_party/rust/byteorder", "third_party/rust/lazy_static", "third_party/rust/libm", "third_party/rust/ordered-float", "third_party/rust/phf", "third_party/rust/phf_codegen", "third_party/rust/phf_generator", "third_party/rust/phf_shared", "third_party/rust/precomputed-hash", "third_party/rust/proc-macro2", "third_party/rust/synstructure", "third_party/rust/void"]
- build assignment LICENSES['mit'].paths @440: ["third_party/rust/array-init"]
- build assignment LICENSES['mit'].paths @445: ["CoreMessagingXP.dll", "Microsoft.InputStateManager.dll", "Microsoft.Internal.FrameworkUdk.dll", "Microsoft.UI.Composition.OSSupport.dll", "Microsoft.UI.Input.dll", "Microsoft.UI.Windowing.Core.dll", "Microsoft.UI.Windowing.dll", "Microsoft.WindowsAppRuntime.Insights.Resource.dll", "Microsoft.WindowsAppRuntime.dll", "marshal.dll"]
- build assignment LICENSES['mit'].paths @462: ["onnxruntime.dll"]
- build assignment LICENSES['mit'].paths @464: ["libonnxruntime.dylib"]
- build assignment LICENSES['mit'].paths @466: ["libonnxruntime.so"]
- build assignment LICENSES @468: ["nicer"]
- build assignment LICENSES @476: ["nom"]
- build assignment LICENSES['nom'].paths @483: ["third_party/rust/nom"]
- build assignment LICENSES @487: ["nrappkit"]
- build assignment LICENSES @495: ["nrappkit-cont-1"]
- build assignment LICENSES @503: ["nrappkit-cont-2"]
- build assignment LICENSES @511: ["nrappkit-cont-3"]
- build assignment LICENSES @519: ["openvision"]
- build assignment LICENSES @526: ["praton"]
- build assignment LICENSES['praton'].paths @533: ["nsprpub/pr/src/misc/praton.c"]
- build assignment LICENSES @537: ["praton1"]
- build assignment LICENSES['praton1'].paths @544: ["nsprpub/pr/src/misc/praton.c"]
- build assignment LICENSES @548: ["prosemirror"]
- build assignment LICENSES['prosemirror'].paths @556: ["third_party/js/prosemirror/prosemirror-commands", "third_party/js/prosemirror/prosemirror-history", "third_party/js/prosemirror/prosemirror-keymap", "third_party/js/prosemirror/prosemirror-model", "third_party/js/prosemirror/prosemirror-schema-basic", "third_party/js/prosemirror/prosemirror-state", "third_party/js/prosemirror/prosemirror-suggestions", "third_party/js/prosemirror/prosemirror-transform", "third_party/js/prosemirror/prosemirror-view"]
- build assignment LICENSES @568: ["qrcode-generator"]
- build assignment LICENSES['qrcode-generator'].paths @575: ["third_party/js/qrcode/"]
- build assignment LICENSES @579: ["react"]
- build assignment LICENSES @587: ["react-redux"]
- build assignment LICENSES['react-redux'].paths @594: ["third_party/node/node_modules/react-redux"]
- build assignment LICENSES @598: ["xdg"]
- build assignment LICENSES @606: ["redux"]
- build assignment LICENSES['redux'].paths @613: ["third_party/node/node_modules/redux"]
- build assignment LICENSES @617: ["hunspell-ru"]
- build assignment LICENSES @625: ["sprintf.js"]
- build assignment LICENSES @633: ["sunsoft"]
- build assignment LICENSES @640: ["superfasthash"]
- build assignment LICENSES @649: ["twemoji"]
- build assignment LICENSES @656: ["unicase"]
- build assignment LICENSES['unicase'].paths @663: ["third_party/rust/unicase"]
- build assignment LICENSES @667: ["unicode"]
- build assignment LICENSES @676: ["unicode-v3"]
- build assignment LICENSES['unicode-v3'].paths @683: ["third_party/rust/icu_calendar", "third_party/rust/icu_calendar_data", "third_party/rust/icu_casemap", "third_party/rust/icu_casemap_data", "third_party/rust/icu_collections", "third_party/rust/icu_locale", "third_party/rust/icu_locale_core", "third_party/rust/icu_locale_data", "third_party/rust/icu_normalizer", "third_party/rust/icu_normalizer_data", "third_party/rust/icu_provider", "third_party/rust/icu_provider_adapters", "third_party/rust/icu_segmenter", "third_party/rust/icu_time", "third_party/rust/litemap", "third_party/rust/tinystr", "third_party/rust/writeable", "third_party/rust/yoke", "third_party/rust/yoke-derive", "third_party/rust/zerofrom", "third_party/rust/zerofrom-derive", "third_party/rust/zerovec", "third_party/rust/zerovec-derive"]
- build assignment LICENSES @709: ["ucal"]
- build assignment LICENSES['ucal'].paths @716: ["nsprpub/pr/src/misc/praton.c"]
- build assignment LICENSES @720: ["v8"]
- build assignment LICENSES @728: ["vtune"]
- build assignment LICENSES @736: ["webrtc"]
- build assignment LICENSES @744: ["x264"]
- build assignment LICENSES['x264'].paths @751: ["third_party/aom/third_party/x86inc/x86inc.asm"]
- build assignment LICENSES @756: ["llvm"]
- build assignment LICENSES['llvm'].paths @765: ["dxcompiler.dll", "dxil.dll"]
- build assignment LICENSES @771: ["dxcompiler-deps"]
- build assignment LICENSES['dxcompiler-deps'].paths @782: ["dxcompiler.dll", "dxil.dll"]

### toolkit/content/moz.build

Blob: `3d6602629247ff8dbc78ad7bb2f495a42fd70eb6`. Parse: parsed.

- build assignment DIRS @5: ["licenses"]
- build assignment TEST_DIRS @7: ["tests"]
- build assignment GENERATED_FILES @39: ["license.html"]
- build assignment GENERATED_FILES['license.html'].inputs @41: ["license.html.mako", "!/licenses.json"]
- build assignment JAR_MANIFESTS @46: ["jar.mn"]
- build assignment BUG_COMPONENT @53: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @56: ["Core", "WebRTC"]
- build assignment BUG_COMPONENT @59: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @62: ["Core", "Audio/Video: Playback"]
- build assignment BUG_COMPONENT @65: ["Core", "Audio/Video: Playback"]
- build assignment BUG_COMPONENT @68: ["Firefox", "Menus"]
- build assignment BUG_COMPONENT @71: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @74: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @77: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @80: ["Core", "Layout"]
- build assignment BUG_COMPONENT @83: ["Toolkit", "Crash Reporting"]
- build assignment BUG_COMPONENT @86: ["Firefox", "File Handling"]
- build assignment BUG_COMPONENT @89: ["Firefox", "Keyboard Navigation"]
- build assignment BUG_COMPONENT @92: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @95: ["Firefox", "Tabbed Browser"]
- build assignment BUG_COMPONENT @98: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @101: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @104: ["Firefox", "File Handling"]
- build assignment BUG_COMPONENT @107: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @110: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @113: ["Core", "Networking"]
- build assignment BUG_COMPONENT @116: ["Toolkit", "Autocomplete"]
- build assignment BUG_COMPONENT @119: ["Core", "DOM: Copy & Paste and Drag & Drop"]
- build assignment BUG_COMPONENT @122: ["Core", "XUL"]
- build assignment BUG_COMPONENT @125: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @128: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @131: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @134: ["Core", "XUL"]
- build assignment BUG_COMPONENT @137: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @140: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @143: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @146: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @149: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @152: ["Firefox", "Menus"]
- build assignment BUG_COMPONENT @154: ["Firefox", "Menus"]
- build assignment BUG_COMPONENT @157: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @160: ["Toolkit", "Preferences"]
- build assignment BUG_COMPONENT @163: ["Toolkit", "Autocomplete"]
- build assignment BUG_COMPONENT @166: ["Core", "DOM: UI Events & Focus Handling"]
- build assignment BUG_COMPONENT @169: ["Toolkit", "Video/Audio Controls"]
- build assignment BUG_COMPONENT @172: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @176: ["Toolkit", "Video/Audio Controls"]
- build assignment BUG_COMPONENT @178: ["Toolkit", "Video/Audio Controls"]
- build assignment BUG_COMPONENT @181: ["Firefox", "Menus"]
- build assignment BUG_COMPONENT @184: ["Core", "XUL"]
- build assignment BUG_COMPONENT @187: ["Core", "XUL"]
- build assignment BUG_COMPONENT @190: ["Core", "DOM: UI Events & Focus Handling"]
- build assignment BUG_COMPONENT @193: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @195: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @198: ["Toolkit", "Video/Audio Controls"]
- build assignment BUG_COMPONENT @201: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @204: ["Toolkit", "Video/Audio Controls"]
- build assignment BUG_COMPONENT @207: ["Firefox", "General"]
- build assignment BUG_COMPONENT @210: ["Toolkit", "Telemetry"]
- build assignment BUG_COMPONENT @213: ["Firefox", "Security"]
- build assignment BUG_COMPONENT @216: ["Core", "Networking"]
- build assignment BUG_COMPONENT @219: ["Core", "XPCOM"]
- build assignment BUG_COMPONENT @222: ["Toolkit", "Startup and Profile System"]
- build assignment BUG_COMPONENT @225: ["Core", "DOM: Workers"]
- build assignment BUG_COMPONENT @228: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @231: ["Toolkit", "Telemetry"]
- build assignment BUG_COMPONENT @234: ["Firefox", "Search"]
- build assignment BUG_COMPONENT @237: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @240: ["Firefox Build System", "General"]
- build assignment BUG_COMPONENT @243: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @246: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @249: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @252: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @255: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @258: ["Firefox", "Migration"]
- build assignment BUG_COMPONENT @261: ["Toolkit", "UI Widgets"]
- build assignment BUG_COMPONENT @264: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @267: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @270: ["Toolkit", "Preferences"]
- build assignment BUG_COMPONENT @273: ["Toolkit", "Preferences"]
- build assignment LICENSED_UNDER @275: ["bsd3clause"]
- build assignment LICENSED_UNDER['bsd3clause'].paths @276: ["vendor/react/react-transition-group.js"]
- build assignment LICENSED_UNDER @280: ["mit"]
- build assignment LICENSED_UNDER['mit'].paths @281: ["vendor/react/prop-types*", "vendor/react/react*"]
- build assignment LICENSED_UNDER @286: ["react-redux"]
- build assignment LICENSED_UNDER['react-redux'].paths @287: ["vendor/react/react-redux.js"]
- build assignment LICENSED_UNDER @291: ["redux"]
- build assignment LICENSED_UNDER['redux'].paths @292: ["vendor/react/Redux.sys.mjs"]

### toolkit/content/neterror/gen_aboutneterror_codes.py

Blob: `528aecff27e640d278ed679a6028e99ee2aa23f1`. Parse: parsed.

- import sys @6
- from fluent.syntax import parse @8
- from fluent.syntax.ast import Message @9
- function find_error_ids @12-16
- function main @19-27

### toolkit/content/tests/chrome/file_about_networking_wsh.py

Blob: `57bd353c21a3bb650c53ef778cb178b83b84bde7`. Parse: parsed.

- from mod_pywebsocket import msgutil @1
- function web_socket_do_extra_handshake @4-5
- function web_socket_transfer_data @8-10

### toolkit/content/tests/moz.build

Blob: `0d4659c8300473b8b2aff28c8157a4ef59b7113d`. Parse: parsed.

- build assignment XPCSHELL_TESTS_MANIFESTS @5: ["unit/xpcshell.toml"]
- build assignment BROWSER_CHROME_MANIFESTS @7: ["browser/browser.toml", "browser/datetime/browser.toml", "widgets/browser.toml"]
- build assignment MOCHITEST_CHROME_MANIFESTS @13: ["chrome/chrome-nova.toml", "chrome/chrome.toml", "widgets/chrome-nova.toml", "widgets/chrome.toml"]
- build assignment MOCHITEST_MANIFESTS @20: ["mochitest/mochitest.toml", "widgets/mochitest.toml"]

### toolkit/content/widgets/mach_commands.py

Blob: `11cf4f7ecb183f5380914468a8291d6bbe909559`. Parse: parsed.

- import os @5
- import re @6
- from mach.decorators import Command,CommandArgument @8
- from mach.util import UserError @9
- function run_mach @85-88
- function run_npm @91-94
- function parse_acorn_elements @97-108
- function add_sorted_entry @111-115
- function update_acorn_elements_in_file @118-147
- function addwidget @160-255
- function addstory @276-296
- function buildtokens @339-388

### toolkit/crashreporter/android/export/moz.build

Blob: `cd5d81be08e17fbf2ff25bccd347b5f61b991e0e`. Parse: parsed.

- build call RustLibrary @1: "crashreporter-android-export"

### toolkit/crashreporter/android/moz.build

Blob: `ecd536266f69d196b983dc3096dd8fd4030ff767`. Parse: parsed.

- build assignment DIRS @1: ["export"]
- build assignment USE_LIBS @2: ["crashreporter-android-export"]
- build assignment OS_LIBS @4: ["m"]
- build assignment SOURCES @6: ["lib.cpp"]
- build call SharedLibrary @7: "crashtools"

### toolkit/crashreporter/annotations/generate.py

Blob: `6d4ed2c499f54cd35bedea4ead0cbfd47032aa85`. Parse: parsed.

- import string @5
- import sys @6
- from os import path @7
- import yaml @9
- function read_template @21-31
- function extract_crash_scope_list @34-40
- function extract_skiplist @43-51
- function type_to_enum @54-68
- function extract_types @71-74
- function content_generator @80-87
- function content_generator.f @83-85
- function generate_strings @95-100
- function generate_enum @103-114
- function generate_annotations_array_initializer @117-122
- function generate_skiplist_initializer @125-132
- function generate_types_initializer @135-140
- function emit_header @144-157
- function javadoc_sanitize @165-173
- function derive_package_and_class @176-186
- function emit_java @190-202
- function main @206-228

### toolkit/crashreporter/annotations/load.py

Blob: `b67572b25811a466ca26ff61c89408c374edd50a`. Parse: parsed.

- import sys @5
- from os import path @6
- import yaml @8
- function sort_annotations @17-20
- function camel_to_snake @25-36
- class AnnotationValidator @39-124
- function AnnotationValidator.__init__ @40-42
- function AnnotationValidator.validate @44-72
- function AnnotationValidator._error @74-79
- function AnnotationValidator._glean @81-124
- function read_annotations @127-146
- function main @149-151

### toolkit/crashreporter/annotations/moz.build

Blob: `d96525d9cb76ed5f53e3ed1ccdbe49b3c69add73`. Parse: parsed.

- build assignment EXPORTS @5: ["!CrashAnnotations.h"]
- build assignment UNIFIED_SOURCES @9: ["CrashAnnotations.cpp"]
- build call GeneratedFile @15: "validated.yaml"
- build call GeneratedFile @18: "CrashAnnotations.h"

### toolkit/crashreporter/breakpad-client/linux/moz.build

Blob: `e4234d804a24d7763f1229e051704e4173cd12f7`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["crash_generation/crash_generation_client.cc", "crash_generation/crash_generation_server.cc", "dump_writer_common/thread_info.cc", "dump_writer_common/ucontext_reader.cc", "handler/exception_handler.cc", "handler/guid_generator.cc", "handler/minidump_descriptor.cc", "log/log.cc", "microdump_writer/microdump_writer.cc", "minidump_writer/linux_dumper.cc", "minidump_writer/linux_ptrace_dumper.cc"]
- build assignment SOURCES @22: ["minidump_writer/minidump_writer.cc"]
- build assignment UNIFIED_SOURCES @24: ["minidump_writer/minidump_writer.cc"]
- build assignment LOCAL_INCLUDES @33: ["/toolkit/crashreporter/google-breakpad/src/common/android/include"]
- build call include @39: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment CXXFLAGS @45: ["-Wno-error=stack-protector"]

### toolkit/crashreporter/breakpad-client/mac/crash_generation/moz.build

Blob: `b652d27540b830b026ea87d8478d572ad281dc8a`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["crash_generation_client.cc", "crash_generation_server.cc"]
- build assignment LOCAL_INCLUDES @12: ["/ipc/chromium/src", "/toolkit/crashreporter/breakpad-client", "/toolkit/crashreporter/google-breakpad/src"]
- build assignment SOURCE_HEADERS @18: ["client_info.h", "crash_generation_client.h", "crash_generation_server.h"]

### toolkit/crashreporter/breakpad-client/mac/handler/moz.build

Blob: `94836b629e9dc32e1558f919cf245a3259134ed3`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["dynamic_images.cc", "exception_handler.cc", "minidump_generator.cc"]
- build assignment LOCAL_INCLUDES @13: ["/toolkit/crashreporter/breakpad-client", "/toolkit/crashreporter/google-breakpad/src"]
- build assignment SOURCE_HEADERS @21: ["dynamic_images.h", "exception_handler.h", "mach_vm_compat.h", "minidump_generator.h", "protected_memory_allocator.h", "ucontext_compat.h"]

### toolkit/crashreporter/breakpad-client/moz.build

Blob: `b40339b31bf2fdaf25ce28e2b9a585525f032b1d`. Parse: parsed.

- build assignment SOURCES @5: ["minidump_file_writer.cc"]
- build assignment USE_LIBS @9: ["breakpad_common_s"]
- build assignment USE_LIBS @14: ["breakpad_mac_common_s"]
- build assignment UNIFIED_SOURCES @18: ["../linux_utils.cc"]
- build assignment USE_LIBS @22: ["breakpad_linux_common_s"]
- build assignment LOCAL_INCLUDES @26: ["/toolkit/crashreporter/google-breakpad/src"]
- build assignment CXXFLAGS @31: ["-Wno-error=stack-protector"]
- build call Library @35: "breakpad_client"
- build assignment SOURCE_HEADERS @37: ["minidump_file_writer-inl.h", "minidump_file_writer.h"]

### toolkit/crashreporter/breakpad-client/windows/common/objs.mozbuild

Blob: `85a45dcaae052527aa0c35ad549adc1250f6e6db`. Parse: parsed.

- build assignment lobjs_client_common @5: ["minidump_callback.cc"]

### toolkit/crashreporter/breakpad-client/windows/crash_generation/objs.mozbuild

Blob: `276670418ae01cf77396f9695f4c404f30ae518a`. Parse: parsed.

- build assignment lobjs_crash_generation @5: ["client_info.cc", "crash_generation_client.cc", "crash_generation_server.cc", "minidump_generator.cc"]

### toolkit/crashreporter/breakpad-client/windows/handler/objs.mozbuild

Blob: `24b9f8006997ce7515b80adf7b824fd11ba2ff7c`. Parse: parsed.

- build assignment lobjs_handler @5: ["exception_handler.cc"]

### toolkit/crashreporter/breakpad-client/windows/sender/objs.mozbuild

Blob: `c60426b60808f7ca520c89d08d9da970e24e41dd`. Parse: parsed.

- build assignment lobjs_sender @5: ["crash_report_sender.cc"]

### toolkit/crashreporter/breakpad-windows-libxul/moz.build

Blob: `3c500a4f99f9dfe568eac358b721f9e767e5cb0a`. Parse: parsed.

- build call Library @5: "google_breakpad_libxul_s"
- build assignment LOCAL_INCLUDES @12: ["/toolkit/crashreporter/breakpad-client", "/toolkit/crashreporter/google-breakpad/src"]
- build call include @17: "/toolkit/crashreporter/google-breakpad/src/common/windows/objs.mozbuild"
- build call include @18: "/toolkit/crashreporter/breakpad-client/windows/handler/objs.mozbuild"
- build call include @19: "/toolkit/crashreporter/breakpad-client/windows/crash_generation/objs.mozbuild"
- build call include @20: "/toolkit/crashreporter/breakpad-client/windows/common/objs.mozbuild"

### toolkit/crashreporter/breakpad_wrapper/moz.build

Blob: `735e0cebe18e5c57bc02872fd513e7efc9fb7b0e`. Parse: parsed.

- build call Library @5: "breakpad_wrapper"
- build assignment SOURCES @10: ["breakpad_wrapper.cpp"]
- build assignment LOCAL_INCLUDES @14: ["../breakpad-client/", "../google-breakpad/src/"]
- build assignment USE_LIBS @20: ["google_breakpad_libxul_s"]
- build assignment OS_LIBS @24: ["advapi32", "bcrypt", "dbghelp", "ntdll", "userenv", "ws2_32"]
- build assignment USE_LIBS @33: ["breakpad_client"]

### toolkit/crashreporter/client/app/moz.build

Blob: `b1d024fe09a462ee02ac92fc7d588d09c4f03664`. Parse: parsed.

- build call GeneratedFile @11: "InfoPlist.strings"

### toolkit/crashreporter/crash_helper/moz.build

Blob: `78307c3d5f55f5802a75ca18976643195a6c1c95`. Parse: parsed.

- build assignment LOCAL_INCLUDES @5: ["/toolkit/crashreporter"]
- build assignment USE_LIBS @9: ["breakpad_wrapper", "crash_helper_server"]
- build assignment UNIFIED_SOURCES @15: ["../bionic_missing_funcs.cpp", "crashhelper_android.cpp"]
- build assignment OS_LIBS @23: ["-framework Foundation"]
- build assignment OS_LIBS @27: ["advapi32", "bcrypt", "dbghelp", "ntdll", "userenv", "ws2_32"]
- build assignment UNIFIED_SOURCES @36: ["crashhelper.cpp"]

### toolkit/crashreporter/crash_helper_client/moz.build

Blob: `d1cc69ebaa2e2a4579e03d203d451999a305fb9c`. Parse: parsed.

- build assignment EXPORTS.mozilla @13: ["!crash_helper_client_ffi_generated.h"]

### toolkit/crashreporter/crash_helper_server/moz.build

Blob: `266a7207e7f18128c2c3085e3ef0d1779691d597`. Parse: parsed.

- build call RustLibrary @5: "crash_helper_server"
- build assignment OS_LIBS @8: ["ole32", "shell32"]
- build assignment EXPORTS.mozilla @21: ["!crash_helper_ffi_generated.h"]

### toolkit/crashreporter/crashping/conversions.py

Blob: `d9ab1f6eb1ccaa0a12c390fa606428c0ace0779d`. Parse: parsed.

- import yaml @5
- function main @8-62

### toolkit/crashreporter/crashping/glean_metrics.py

Blob: `778b30178cf49f9b103d0710845c953b4fce7e2c`. Parse: parsed.

- import sys @5
- from os import path @6
- import yaml @8
- function make_bugzilla_url @22-23
- function remove_non_glean_fields @26-32
- function generate_string @35-67
- function import_path @70-76
- import importlib.util @71
- function main @79-94
- from mach.decorators import Command @98
- function crash_ping_metrics @105-112

### toolkit/crashreporter/crashping/glean_rust.py

Blob: `5da687441fb6d7cb9b74690500912cc67a99c3e9`. Parse: parsed.

- import shutil @5
- import sys @6
- from contextlib import redirect_stderr,redirect_stdout @7
- from io import StringIO @8
- from pathlib import Path @9
- from tempfile import TemporaryDirectory @10
- function main @13-34
- from glean_parser.translate import translate @26

### toolkit/crashreporter/crashping/moz.build

Blob: `a811eff73e5e1f971b760999b7ed2f2b89fecf90`. Parse: parsed.

- build call GeneratedFile @8: "generated_metrics.yaml"
- build call GeneratedFile @15: "glean_metrics.rs"
- build call GeneratedFile @26: "conversions.rs"

### toolkit/crashreporter/crashreporter.mozbuild

Blob: `02a77e25ec9b53b6e290a078ae88af86c0e71a0e`. Parse: parsed.

- build assignment LOCAL_INCLUDES @5: ["/toolkit/crashreporter/breakpad-client", "/toolkit/crashreporter/google-breakpad/src"]
- build assignment CXXFLAGS @12: ["-Wno-macro-redefined"]
- build assignment CXXFLAGS @16: ["-Wno-unused-local-typedefs", "-Wno-deprecated-declarations", "-Wno-bool-compare", "-Wno-unused-but-set-variable"]
- build assignment CXXFLAGS @24: ["-Wno-c++11-narrowing"]
- build assignment CXXFLAGS @28: ["-Wno-implicit-fallthrough"]

### toolkit/crashreporter/google-breakpad/src/common/linux/moz.build

Blob: `83938c0c3a6bc036152f6dabf8aaf678d125f140`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["elfutils.cc", "linux_libc_support.cc", "memory_mapped_file.cc", "safe_readlink.cc"]
- build assignment SOURCES @13: ["file_id.cc"]
- build assignment UNIFIED_SOURCES @18: ["http_upload.cc"]
- build assignment SOURCES @31: ["breakpad_getcontext.S"]
- build call Library @35: "breakpad_linux_common_s"
- build call include @37: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment CXXFLAGS @40: ["-Wno-error=stack-protector"]
- build assignment SOURCE_HEADERS @42: ["breakpad_getcontext.h", "crc32.h", "dump_symbols.h", "eintr_wrapper.h", "elf_core_dump.h", "elf_gnu_compat.h", "elf_symbols_to_module.h", "elfutils-inl.h", "elfutils.h", "file_id.h", "google_crashdump_uploader.h", "guid_creator.h", "http_upload.h", "ignore_ret.h", "libcurl_wrapper.h", "linux_libc_support.h", "memory_mapped_file.h", "safe_readlink.h", "symbol_collector_client.h", "symbol_upload.h", "synth_elf.h", "ucontext_constants.h"]

### toolkit/crashreporter/google-breakpad/src/common/mac/moz.build

Blob: `2e7d470a14fc7082486164c5fc6e8c3b286af616`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["arch_utilities.cc", "file_id.cc", "macho_id.cc", "macho_reader.cc", "macho_utilities.cc", "macho_walker.cc"]
- build assignment SOURCES @14: ["bootstrap_compat.cc", "HTTPMultipartUpload.m", "MachIPC.mm", "string_utilities.cc"]
- build call Library @21: "breakpad_mac_common_s"
- build call include @23: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment SOURCE_HEADERS @25: ["arch_utilities.h", "bootstrap_compat.h", "byteswap.h", "dump_syms.h", "file_id.h", "GTMDefines.h", "GTMLogger.h", "HTTPMultipartUpload.h", "launch_reporter.h", "MachIPC.h", "macho_id.h", "macho_reader.h", "macho_utilities.h", "macho_walker.h", "scoped_task_suspend-inl.h", "string_utilities.h", "super_fat_arch.h"]

### toolkit/crashreporter/google-breakpad/src/common/moz.build

Blob: `d5d34f5a64b9e1e4fc6a7fc2ae601a70209fef27`. Parse: parsed.

- build assignment UNIFIED_SOURCES @5: ["convert_UTF.cc", "string_conversion.cc"]
- build assignment UNIFIED_SOURCES @11: ["md5.cc"]
- build call Library @15: "breakpad_common_s"
- build call include @17: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment SOURCE_HEADERS @19: ["arm_ex_reader.h", "arm_ex_to_module.h", "basictypes.h", "byte_cursor.h", "convert_UTF.h", "dwarf_cfi_to_module.h", "dwarf_cu_to_module.h", "dwarf_line_to_module.h", "dwarf_range_list_handler.h", "language.h", "long_string_dictionary.h", "macros.h", "md5.h", "memory_allocator.h", "memory_range.h", "minidump_type_helper.h", "module.h", "path_helper.h", "scoped_ptr.h", "simple_string_dictionary.h", "stabs_reader.h", "stabs_to_module.h", "stdio_wrapper.h", "string_conversion.h", "symbol_data.h", "test_assembler.h", "unordered.h", "using_std_string.h"]

### toolkit/crashreporter/google-breakpad/src/common/windows/objs.mozbuild

Blob: `59ec1cb16e305976a039075bf0c86d62c7df7f6f`. Parse: parsed.

- build assignment lobjs_common @5: ["guid_string.cc", "string_utils.cc"]

### toolkit/crashreporter/google-breakpad/src/processor/moz.build

Blob: `7f275623a9561c78f81bc0a4c83d3dc6deb56614`. Parse: parsed.

- build assignment SOURCES @5: ["../third_party/libdisasm/ia32_invariant.c", "../third_party/libdisasm/ia32_reg.c", "disassembler_x86.cc", "exploitability_win.cc"]
- build assignment SOURCES['../third_party/libdisasm/ia32_invariant.c'].flags @16: ["-Wno-tautological-value-range-compare"]
- build assignment SOURCES['../third_party/libdisasm/ia32_reg.c'].flags @19: ["-Wno-stringop-truncation"]
- build assignment UNIFIED_SOURCES @21: ["../third_party/libdisasm/ia32_implicit.c", "../third_party/libdisasm/ia32_insn.c", "../third_party/libdisasm/ia32_modrm.c", "../third_party/libdisasm/ia32_opcode_tables.c", "../third_party/libdisasm/ia32_operand.c", "../third_party/libdisasm/ia32_settings.c", "../third_party/libdisasm/x86_disasm.c", "../third_party/libdisasm/x86_imm.c", "../third_party/libdisasm/x86_insn.c", "../third_party/libdisasm/x86_misc.c", "../third_party/libdisasm/x86_operand_list.c", "basic_code_modules.cc", "basic_source_line_resolver.cc", "call_stack.cc", "cfi_frame_info.cc", "convert_old_arm64_context.cc", "dump_context.cc", "dump_object.cc", "exploitability.cc", "exploitability_linux.cc", "logging.cc", "minidump.cc", "minidump_processor.cc", "pathname_stripper.cc", "proc_maps_linux.cc", "process_state.cc", "source_line_resolver_base.cc", "stack_frame_symbolizer.cc", "stackwalk_common.cc", "stackwalker.cc", "stackwalker_amd64.cc", "stackwalker_arm.cc", "stackwalker_arm64.cc", "stackwalker_mips.cc", "stackwalker_ppc.cc", "stackwalker_ppc64.cc", "stackwalker_sparc.cc", "stackwalker_x86.cc", "symbolic_constants_win.cc", "tokenize.cc"]
- build call Library @66: "breakpad_processor"
- build call include @71: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment CXXFLAGS @77: ["-Wno-mismatched-dealloc", "-Wno-nonnull", "-Wno-maybe-uninitialized"]
- build assignment SOURCE_HEADERS @83: ["address_map-inl.h", "address_map.h", "basic_code_module.h", "basic_code_modules.h", "basic_source_line_resolver_types.h", "cfi_frame_info-inl.h", "cfi_frame_info.h", "contained_range_map-inl.h", "contained_range_map.h", "convert_old_arm64_context.h", "disassembler_x86.h", "exploitability_linux.h", "exploitability_win.h", "fast_source_line_resolver_types.h", "linked_ptr.h", "logging.h", "map_serializers-inl.h", "map_serializers.h", "module_comparer.h", "module_factory.h", "module_serializer.h", "pathname_stripper.h", "postfix_evaluator-inl.h", "postfix_evaluator.h", "range_map-inl.h", "range_map.h", "simple_serializer-inl.h", "simple_serializer.h", "simple_symbol_supplier.h", "source_line_resolver_base_types.h", "stackwalk_common.h", "stackwalker_address_list.h", "stackwalker_amd64.h", "stackwalker_arm.h", "stackwalker_arm64.h", "stackwalker_mips.h", "stackwalker_ppc.h", "stackwalker_ppc64.h", "stackwalker_sparc.h", "stackwalker_unittest_utils.h", "stackwalker_x86.h", "static_address_map-inl.h", "static_address_map.h", "static_contained_range_map-inl.h", "static_contained_range_map.h", "static_map-inl.h", "static_map.h", "static_map_iterator-inl.h", "static_map_iterator.h", "static_range_map-inl.h", "static_range_map.h", "symbolic_constants_win.h", "synth_minidump.h", "synth_minidump_unittest_data.h", "tokenize.h", "windows_frame_info.h"]

### toolkit/crashreporter/google-breakpad/src/tools/python/deps-to-manifest.py

Blob: `b456285431ad5cafdc8c24f24ed987155f1873f3`. Parse: parsed.

- from __future__ import print_function @33
- import argparse @35
- import os @36
- import sys @37
- function ConvertDepsToManifest @76-146
- function GetParser @149-156
- function main @159-163

### toolkit/crashreporter/google-breakpad/src/tools/python/filter_syms.py

Blob: `abddf7893e093128b2000fc7095bce87c758dba3`. Parse: parsed.

- import macpath @42
- import ntpath @43
- import optparse @44
- import os @45
- import posixpath @46
- import sys @47
- class BreakpadParseError @49-51
- class SymbolFileParser @53-170
- function SymbolFileParser.__init__ @60-88
- function SymbolFileParser.Process @90-95
- function SymbolFileParser._ParseRecord @97-112
- function SymbolFileParser._NormalizePath @114-124
- function SymbolFileParser._AdjustPath @126-137
- function SymbolFileParser._ParseFileRecord @139-153
- function SymbolFileParser._IsLineRecord @155-161
- function SymbolFileParser._ParseLineRecord @163-170
- function main @172-201

### toolkit/crashreporter/google-breakpad/src/tools/python/tests/filter_syms_unittest.py

Blob: `b111f34983617db35ff7a333e6b0816002f82330`. Parse: parsed.

- import cStringIO @33
- import ntpath @34
- import os @35
- import StringIO @36
- import sys @37
- import unittest @38
- import filter_syms @44
- class FilterSysmsTest @46-135
- function FilterSysmsTest.assertParsed @47-53
- function FilterSysmsTest.testDuplicateFiles @55-79
- function FilterSysmsTest.testIgnoredPrefix @81-106
- function FilterSysmsTest.testIgnoredPrefixesDuplicateFiles @108-135

### toolkit/crashreporter/moz.build

Blob: `b45df394e659a9735d4371b7e2c224387bd4734a`. Parse: parsed.

- build assignment SCHEDULES.exclusive @8: ["docs"]
- build assignment EXPORTS @10: ["nsExceptionHandler.h"]
- build assignment JAR_MANIFESTS @14: ["jar.mn"]
- build assignment UNIFIED_SOURCES @16: ["ExtraFileParser.cpp", "nsExceptionHandlerUtils.cpp"]
- build assignment PREPROCESSED_IPDL_SOURCES @21: ["ipc/CrashReporterInitArgs.ipdlh"]
- build call include @25: "/ipc/chromium/chromium-config.mozbuild"
- build assignment DIRS @29: ["annotations"]
- build assignment USE_LIBS @33: ["breakpad_client"]
- build assignment DIRS @38: ["breakpad-windows-libxul", "google-breakpad/src/common", "google-breakpad/src/processor", "mozwer", "mozwer-rust"]
- build assignment DIRS @47: ["breakpad-client", "breakpad-client/mac/crash_generation", "breakpad-client/mac/handler", "google-breakpad/src/common", "google-breakpad/src/common/mac", "google-breakpad/src/processor"]
- build assignment DIRS @57: ["breakpad-client", "breakpad-client/linux/", "google-breakpad/src/common", "google-breakpad/src/common/linux", "google-breakpad/src/processor"]
- build assignment EXPORTS @65: ["linux_utils.h"]
- build assignment DIRS @70: ["rust_minidump_writer_linux"]
- build assignment DIRS @73: ["client/app", "networking"]
- build assignment DIRS @78: ["android"]
- build assignment DIRS @80: ["breakpad_wrapper", "crash_helper", "crash_helper_client", "crash_helper_server", "crashping", "mozannotation_client"]
- build assignment TEST_DIRS @89: ["test"]
- build assignment UNIFIED_SOURCES @91: ["nsExceptionHandler.cpp"]
- build assignment UNIFIED_SOURCES @96: ["mac_utils.mm"]
- build assignment SOURCE_HEADERS @99: ["mac_utils.h"]
- build assignment MOZ_SRC_FILES @103: ["CrashReports.sys.mjs", "CrashSubmit.sys.mjs"]
- build assignment LOCAL_INCLUDES @111: ["/toolkit/crashreporter/google-breakpad/src/common/android/include"]
- build assignment UNIFIED_SOURCES @114: ["bionic_missing_funcs.cpp"]
- build assignment LOCAL_INCLUDES @124: ["/toolkit/components/jsoncpp/include", "google-breakpad/src"]
- build assignment USE_LIBS @129: ["jsoncpp"]
- build assignment PYTHON_UNITTEST_MANIFESTS @133: ["tools/python.toml"]
- build call include @137: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment CXXFLAGS @140: ["-Wno-error=stack-protector"]
- build assignment UNIFIED_SOURCES @142: ["nsDummyExceptionHandler.cpp"]
- build assignment BUG_COMPONENT @147: ["Toolkit", "Crash Reporting"]
- build assignment LICENSED_UNDER @149: ["google-bsd"]
- build assignment LICENSED_UNDER['google-bsd'].paths @150: ["google-breakpad"]
- build assignment SOURCE_HEADERS @154: ["ExtraFileParser.h", "nsExceptionHandlerUtils.h"]

### toolkit/crashreporter/mozannotation_client/moz.build

Blob: `9714e4ce864e83e1e04f8c94dcdbdcee5d15ed19`. Parse: parsed.

- build assignment EXPORTS.mozilla.toolkit.crashreporter @13: ["!mozannotation_client_ffi_generated.h"]

### toolkit/crashreporter/mozwer-rust/moz.build

Blob: `241efaf75ab75b08b8c458cae9dd62b8b99d0847`. Parse: parsed.

- build call RustLibrary @1: "mozwer_s"
- build assignment OS_LIBS @3: ["advapi32", "dbghelp", "kernel32", "ntdll", "ole32", "shell32", "user32", "userenv", "ws2_32"]

### toolkit/crashreporter/mozwer/moz.build

Blob: `40663262dba33e655c54f31a00b8fbc073caf75b`. Parse: parsed.

- build assignment UNIFIED_SOURCES @1: ["mozwer.cpp"]
- build assignment USE_LIBS @5: ["mozwer_s"]
- build assignment OS_LIBS @9: ["advapi32", "bcrypt", "synchronization"]
- build call SharedLibrary @18: "mozwer"

### toolkit/crashreporter/networking/moz.build

Blob: `98db895671d29b3c8251d16556045915dc6b70c8`. Parse: parsed.

- build assignment EXTRA_JS_MODULES.backgroundtasks @1: ["BackgroundTask_crashreporterNetworkBackend.sys.mjs"]
- build assignment XPCSHELL_TESTS_MANIFESTS @4: ["tests/xpcshell/xpcshell.toml"]

### toolkit/crashreporter/rust_minidump_writer_linux/moz.build

Blob: `7a0a60b6d92fccca94e6596514ef1578f1695702`. Parse: parsed.

- build assignment EXPORTS.mozilla.toolkit.crashreporter @13: ["!rust_minidump_writer_linux_ffi_generated.h"]

### toolkit/crashreporter/test/gtest/moz.build

Blob: `ff1690f2024721a68e3ef34315d1319b6cfb59bc`. Parse: parsed.

- build call Library @5: "crashreportertest"
- build assignment UNIFIED_SOURCES @8: ["TestElfSoVersion.cpp"]
- build assignment UNIFIED_SOURCES @12: ["TestMacExceptionHandler.cpp", "TestMacExcResource.cpp"]
- build assignment LOCAL_INCLUDES @17: ["/toolkit/crashreporter", "/toolkit/crashreporter/breakpad-client", "/toolkit/crashreporter/google-breakpad/src"]
- build call include @29: "/ipc/chromium/chromium-config.mozbuild"

### toolkit/crashreporter/test/moz.build

Blob: `390d105f15dc867d25f439097c93eda32fa76eda`. Parse: parsed.

- build assignment XPCSHELL_TESTS_MANIFESTS @6: ["unit/xpcshell.toml", "unit_ipc/xpcshell.toml"]
- build assignment XPCSHELL_TESTS_MANIFESTS @8: ["unit/xpcshell-phc.toml", "unit_ipc/xpcshell-phc.toml"]
- build assignment DIRS @10: ["test_utils"]
- build assignment TEST_DIRS @14: ["gtest"]
- build assignment BROWSER_CHROME_MANIFESTS @18: ["browser/browser.toml"]
- build assignment UNIFIED_SOURCES @20: ["../google-breakpad/src/processor/basic_code_modules.cc", "../google-breakpad/src/processor/convert_old_arm64_context.cc", "../google-breakpad/src/processor/dump_context.cc", "../google-breakpad/src/processor/dump_object.cc", "../google-breakpad/src/processor/logging.cc", "../google-breakpad/src/processor/minidump.cc", "../google-breakpad/src/processor/pathname_stripper.cc", "../google-breakpad/src/processor/proc_maps_linux.cc", "dumputils.cpp"]
- build assignment SOURCES @32: ["ExceptionThrower.cpp"]
- build assignment SOURCES @37: ["nsTestCrasher.cpp"]
- build assignment SOURCES['nsTestCrasher.cpp'].flags @40: ["-Wno-array-bounds", "-Wno-use-after-free"]
- build assignment UNIFIED_SOURCES @45: ["nsTestCrasher.cpp"]
- build assignment SOURCES @51: ["win64UnwindInfoTests.asm"]
- build assignment SOURCES['ExceptionThrower.cpp'].flags @56: ["-Xclang", "-fcxx-exceptions"]
- build assignment SOURCES['ExceptionThrower.cpp'].flags @61: ["-fexceptions"]
- build assignment TEST_HARNESS_FILES.xpcshell.toolkit.crashreporter.test.unit @76: ["CrashTestUtils.sys.mjs"]
- build assignment TEST_HARNESS_FILES.xpcshell.toolkit.crashreporter.test.unit_ipc @79: ["CrashTestUtils.sys.mjs"]
- build call include @83: "/toolkit/crashreporter/crashreporter.mozbuild"
- build assignment SOURCE_HEADERS @87: ["ExceptionThrower.h"]

### toolkit/crashreporter/test/test_utils/moz.build

Blob: `8e5bf6f8d724a644e65c36f22adaf388160114d8`. Parse: parsed.

- build assignment XPIDL_SOURCES @5: ["nsICrashReporterTestUtils.idl"]
- build assignment SOURCES @11: ["nsCrashReporterTestUtils.cpp"]
- build assignment XPCOM_MANIFESTS @15: ["components.conf"]
- build call include @21: "/ipc/chromium/chromium-config.mozbuild"
- build assignment SOURCE_HEADERS @23: ["nsCrashReporterTestUtils.h"]

### toolkit/crashreporter/tools/symbolstore.py

Blob: `827fadf2afef540154408aa43fce8341e06f4783`. Parse: parsed.

- import ctypes @24
- import errno @25
- import functools @26
- import os @27
- import platform @28
- import re @29
- import shutil @30
- import subprocess @31
- import sys @32
- import textwrap @33
- import time @34
- from optparse import OptionParser @35
- from pathlib import Path @36
- import buildconfig @38
- from mozbuild.generated_sources import GENERATED_SOURCE_EXTS,get_filename_with_digest,get_s3_region_and_bucket @39
- from mozpack import executables @44
- from mozpack.copier import FileRegistry @45
- from mozpack.manifests import InstallManifest,UnreadableInstallManifest @46
- from variables import get_buildid @47
- class VCSFileInfo @57-125
- function VCSFileInfo.__init__ @70-73
- function VCSFileInfo.__getattr__ @75-105
- function VCSFileInfo.GetRoot @107-110
- function VCSFileInfo.GetCleanRoot @112-115
- function VCSFileInfo.GetRevision @117-120
- function VCSFileInfo.GetFilename @122-125
- function read_output @139-143
- class HGRepoInfo @146-186
- function HGRepoInfo.__init__ @147-183
- function HGRepoInfo.GetFileInfo @185-186
- class HGFileInfo @189-207
- function HGFileInfo.__init__ @190-193
- function HGFileInfo.GetRoot @195-196
- function HGFileInfo.GetCleanRoot @198-199
- function HGFileInfo.GetRevision @201-202
- function HGFileInfo.GetFilename @204-207
- class GitRepoInfo @210-241
- function GitRepoInfo.__init__ @217-238
- function GitRepoInfo.GetFileInfo @240-241
- class GitFileInfo @244-262
- function GitFileInfo.__init__ @245-248
- function GitFileInfo.GetRoot @250-251
- function GitFileInfo.GetCleanRoot @253-254
- function GitFileInfo.GetRevision @256-257
- function GitFileInfo.GetFilename @259-262
- function realpath @274-313
- function IsInDir @320-325
- function TryGetGitRepoInfoFromHg @328-337
- function GetVCSFilenameFromSrcdir @340-352
- function GetVCSFilename @355-388
- function validate_install_manifests @391-409
- function make_file_mapping @412-423
- function get_generated_file_s3_path @427-432
- function GetPlatformSpecificDumper @435-441
- function SourceIndex @444-479
- class Dumper @482-819
- function Dumper.__init__ @500-538
- function Dumper.ShouldProcess @541-542
- function Dumper.SourceServerIndexing @545-548
- function Dumper.CopyExeAndDebugInfo @551-554
- function Dumper.Process @556-559
- function Dumper.ProcessFile @561-575
- function Dumper.dump_syms_cmdline @577-591
- function Dumper.dump_syms_extra_info @593-627
- function Dumper.ProcessFileWork @629-819
- import json @783
- function locate_pdb @826-844
- class Dumper_Win32 @847-910
- function Dumper_Win32.ShouldProcess @850-856
- function Dumper_Win32.CopyExeAndDebugInfo @858-881
- function Dumper_Win32.SourceServerIndexing @883-910
- class Dumper_Linux @913-949
- function Dumper_Linux.ShouldProcess @916-923
- function Dumper_Linux.CopyExeAndDebugInfo @925-949
- class Dumper_Solaris @952-960
- function Dumper_Solaris.ShouldProcess @953-960
- class Dumper_Mac @963-1088
- function Dumper_Mac.ShouldProcess @964-971
- function Dumper_Mac.ProcessFile @973-980
- function Dumper_Mac.dump_syms_cmdline @982-1005
- function Dumper_Mac.GenerateDSYM @1007-1071
- function Dumper_Mac.CopyExeAndDebugInfo @1073-1088
- function main @1094-1215

### toolkit/crashreporter/tools/unit-symbolstore.py

Blob: `b918c3f4f476e3cfae9d1efd9f5f4b57a7a3b9f7`. Parse: parsed.

- import os @6
- import shutil @7
- import struct @8
- import subprocess @9
- import sys @10
- import tempfile @11
- import unittest @12
- from unittest import mock @13
- from unittest.mock import patch @14
- import buildconfig @16
- import mozpack.path @17
- import mozunit @18
- import symbolstore @19
- from mozpack.manifests import InstallManifest @20
- from symbolstore import realpath @21
- function write_elf @28-31
- function write_macho @34-35
- function write_dll @38-41
- function target_platform @44-45
- function host_platform @48-49
- function add_extension @68-69
- class HelperMixin @72-110
- function HelperMixin.setUp @77-89
- function HelperMixin.tearDown @91-94
- function HelperMixin.make_dirs @96-99
- function HelperMixin.make_file @101-104
- function HelperMixin.add_test_files @106-110
- function mock_dump_syms @113-118
- class TestCopyDebug @121-220
- function TestCopyDebug.setUp @122-144
- function TestCopyDebug.setUp.next_popen @130-141
- function TestCopyDebug.tearDown @146-149
- function TestCopyDebug.next_mock_stdout @151-155
- function TestCopyDebug.test_copy_debug_universal @157-192
- function TestCopyDebug.test_copy_debug_universal.mock_copy_debug @164-169
- function TestCopyDebug.test_copy_debug_universal.mock_dsymutil @178-181
- function TestCopyDebug.test_copy_debug_copies_binaries @194-220
- function TestCopyDebug.test_copy_debug_copies_binaries.mock_compress @208-211
- class TestGetVCSFilename @223-279
- function TestGetVCSFilename.setUp @224-225
- function TestGetVCSFilename.tearDown @227-228
- function TestGetVCSFilename.testVCSFilenameHg @231-243
- function TestGetVCSFilename.testVCSFilenameHgMultiple @246-268
- function TestGetVCSFilename.testVCSFilenameEnv @270-279
- class TestGeneratedFilePath @289-305
- function TestGeneratedFilePath.setUp @290-291
- function TestGeneratedFilePath.tearDown @293-294
- function TestGeneratedFilePath.test_generated_file_path @296-305
- class TestRealpath @310-330
- function TestRealpath.test_realpath @311-330
- class TestSourceServer @335-444
- function TestSourceServer.test_HGSERVER @339-393
- function TestSourceServer.test_HGSERVER.mock_pdbstr @367-372
- function TestSourceServer.test_pdb_next_to_binary @398-444
- function TestSourceServer.test_pdb_next_to_binary.mock_pdbstr @422-424
- class TestInstallManifest @447-513
- function TestInstallManifest.setUp @448-462
- function TestInstallManifest.testMakeFileMapping @464-478
- function TestInstallManifest.testMissingFiles @480-494
- function TestInstallManifest.testBadManifest @496-506
- function TestInstallManifest.testBadArgument @508-513
- class TestFileMapping @516-564
- function TestFileMapping.setUp @517-524
- function TestFileMapping.testFileMapping @527-564
- function TestFileMapping.testFileMapping.mk_output @546-551
- class TestFunctional @567-662
- function TestFunctional.setUp @576-605
- function TestFunctional.tearDown @607-608
- function TestFunctional.testSymbolstore @610-662
- function TestFunctional.testSymbolstore.check_hg_path @645-655

### toolkit/crashreporter/tools/upload_symbols.py

Blob: `48322369acade80fafc1c9c0af2ef0d4af6197c2`. Parse: parsed.

- import argparse @17
- import logging @18
- import os @19
- import subprocess @20
- import sys @21
- import tarfile @22
- import tempfile @23
- import zipfile @24
- from urllib import parse @25
- import redo @27
- import requests @28
- function print_error @42-50
- function get_taskcluster_secret @53-61
- function get_taskcluster_artifact_urls @64-74
- function main @77-124
- function main.check_file_exists @93-101
- function download_archive @127-137
- function unpack_zst_archives @140-155
- function unpack_zst_archive @158-263
- import concurrent.futures @168
- import gzip @169
- import zstandard @171
- function unpack_zst_archive.iter_files_from_tar @173-188
- function unpack_zst_archive.prepare_from @190-254
- function unpack_zst_archive.prepare_from.handle_file @204-243
- import bz2 @219
- function upload_symbols @266-310

### toolkit/library/build/dependentlibs.py

Blob: `45afdb339d858204a2414c870c41de6afbb52fde`. Parse: parsed.

- import os @9
- import re @10
- import subprocess @11
- import sys @12
- import mozpack.path @13
- from mozpack.executables import get_type,ELF,MACHO @14
- from buildconfig import substs @19
- function dependentlibs_win32_objdump @22-40
- function dependentlibs_readelf @43-67
- function dependentlibs_mac_objdump @70-94
- function is_skiplisted @97-116
- function dependentlibs @119-136
- function gen_list @139-163
- function main @166-167

### toolkit/library/build/moz.build

Blob: `72b02071e56d1c93b6bd8a58b6b0ece29837026b`. Parse: parsed.

- build assignment USE_LIBS @5: ["static:xul"]
- build assignment USE_LIBS @11: ["gkrust"]
- build call GeneratedFile @24: "dependentlibs.list"
- build assignment FINAL_TARGET_FILES @31: ["!dependentlibs.list", "!dependentlibs.list.gtest"]
- build assignment OBJDIR_FILES.dist.bin @40: ["../libxul.so-gdb.py"]
- build assignment DUMP_SYMBOLS_FLAGS @42: ["--count-ctors"]

### toolkit/library/buildid_reader/moz.build

Blob: `7b763b1cb66c52df8e6f1ffbe8c0fe617bb7c187`. Parse: parsed.

- build assignment EXPORTS.mozilla.toolkit.library @5: ["buildid_reader_ffi.h"]

### toolkit/library/gen_buildid.py

Blob: `8c52f6a5a9ef51f16e37105c9e5439fbbfbdbf36`. Parse: parsed.

- import os @6
- import buildconfig @8
- from variables import get_buildid @9
- function main @12-22
- function tests @25-26
- function write_file @29-92

### toolkit/library/gtest/libxul_broken_buildid/moz.build

Blob: `28b86ce1fd32bb42e6df75ad506f80446d415b81`. Parse: parsed.

- build assignment SOURCES @7: ["!xul_broken_buildid.c"]
- build call GeneratedFile @11: "xul_broken_buildid.c"
- build call SharedLibrary @19: "xul_broken_buildid"

### toolkit/library/gtest/libxul_correct_buildid/moz.build

Blob: `85918a777059597cd0fa2d7ff7104b6f852d2e9c`. Parse: parsed.

- build assignment SOURCES @7: ["!xul_correct_buildid.c"]
- build call GeneratedFile @11: "xul_correct_buildid.c"
- build call SharedLibrary @19: "xul_correct_buildid"

### toolkit/library/gtest/libxul_missing_buildid/moz.build

Blob: `db38ae8ad2c43899839ab67acb1d59d8ddb40ff5`. Parse: parsed.

- build assignment SOURCES @7: ["xul_missing_buildid.c"]
- build call SharedLibrary @11: "xul_missing_buildid"

### toolkit/library/gtest/moz.build

Blob: `75ef85f818d8bc80e69960daecce7dcbd7e53331`. Parse: parsed.

- build assignment USE_LIBS @7: ["gkrust-gtest"]
- build assignment DIRS @11: ["libxul_broken_buildid", "libxul_correct_buildid", "libxul_missing_buildid"]
- build assignment UNIFIED_SOURCES @17: ["TestBuildIDReader.cpp"]
- build assignment LOCAL_INCLUDES @21: ["/xpcom/build"]
- build assignment USE_LIBS @25: ["static:xul"]

### toolkit/library/gtest/rust/moz.build

Blob: `abb1ca636fd1654d97fda1a20ed7dd3a689f5445`. Parse: parsed.

- build call include @5: "../../rust/gkrust-features.mozbuild"
- build assignment gkrust_features @8: ["gecko-fuzz-targets"]
- build call RustLibrary @10: "gkrust-gtest"

### toolkit/library/libxul.so-gdb.py

Blob: `53609930cb22d142e019974bab2511b3dae963ff`. Parse: parsed.

- import re @7
- from os.path import abspath,dirname,exists @8

### toolkit/library/moz.build

Blob: `671c32b2d8e28d1c010ffe4533d8350174e96800`. Parse: parsed.

- function Libxul_defines @7-12
- function Libxul @16-109
- build assignment DELAYLOAD_DLLS @26: ["avrt.dll", "bcrypt.dll", "comdlg32.dll", "credui.dll", "crypt32.dll", "d3d11.dll", "D3DCompiler_47.dll", "dhcpcsvc.dll", "dnsapi.dll", "dwmapi.dll", "dxgi.dll", "gdi32.dll", "hid.dll", "imm32.dll", "iphlpapi.dll", "msi.dll", "msimg32.dll", "ncrypt.dll", "netapi32.dll", "ole32.dll", "oleaut32.dll", "secur32.dll", "setupapi.dll", "shell32.dll", "shlwapi.dll", "urlmon.dll", "user32.dll", "userenv.dll", "usp10.dll", "uxtheme.dll", "wininet.dll", "winmm.dll", "winspool.drv", "wintrust.dll", "wtsapi32.dll"]
- build assignment DELAYLOAD_DLLS @65: ["oleacc.dll", "UIAutomationCore.dll"]
- build assignment DELAYLOAD_DLLS @68: ["msdmo.dll"]
- build assignment DELAYLOAD_DLLS @71: ["api-ms-win-core-winrt-l1-1-0.dll", "api-ms-win-core-winrt-string-l1-1-0.dll"]
- build assignment LOCAL_INCLUDES @77: ["!/accessible/interfaces/gecko/"]
- build assignment LOCAL_INCLUDES @80: ["/widget/windows", "/xpcom/base"]
- build assignment LDFLAGS @88: ["-time"]
- build assignment LDFLAGS @95: ["-lresolv"]
- build assignment LDFLAGS @96: ["-Wl,-rpath,@executable_path/../Frameworks/ChannelPrefs.framework"]
- build assignment LDFLAGS @109: ["-fno-lto"]
- build call Library @115: "xul"
- build assignment SOURCES @124: ["nsDllMain.cpp"]
- build assignment LOCAL_INCLUDES @128: ["/config", "/widget/windows"]
- build assignment LOCAL_INCLUDES @135: ["/xpcom/base"]
- build assignment DIRS @139: ["build", "buildid_reader"]
- build assignment TEST_DIRS @144: ["gtest"]
- build assignment USE_LIBS @148: ["js"]
- build assignment USE_LIBS @152: ["abseil", "gkcodecs", "lgpllibs", "nspr", "nss", "psshparser", "sqlite"]
- build assignment USE_LIBS @163: ["zlib"]
- build assignment USE_LIBS @180: ["mozgtk"]
- build assignment USE_LIBS @186: ["mozwayland"]
- build assignment USE_LIBS @191: ["freetype"]
- build assignment OS_LIBS @197: ["secur32", "iphlpapi", "strmiids", "dmoguids", "wmcodecdspuuid", "amstrmid", "msdmo", "wininet"]
- build assignment OS_LIBS @209: ["-framework AudioToolbox", "-framework AVFoundation", "-framework CoreFoundation", "-framework CoreMedia", "-framework CoreVideo", "-framework Foundation", "-framework MediaPlayer", "-framework Metal", "-framework QuartzCore", "-framework Security"]
- build assignment OS_LIBS @223: ["-framework AddressBook", "-framework AppKit", "-framework ApplicationServices", "-framework AudioUnit", "-framework Carbon", "-framework CoreAudio", "-framework CoreLocation", "-framework CoreMIDI", "-framework CoreServices", "-framework IOKit", "-framework OpenGL", "-framework ServiceManagement", "-framework SystemConfiguration", "-weak_framework ScreenCaptureKit", "cups"]
- build assignment USE_LIBS @240: ["ChannelPrefs"]
- build assignment OS_LIBS @245: ["-framework CoreGraphics", "-framework CoreText", "-framework OpenGLES"]
- build assignment OS_LIBS @252: ["mfuuid", "wmcodecdspuuid", "strmiids"]
- build assignment OS_LIBS @259: ["util"]
- build assignment OS_LIBS @264: ["crypt32", "d2d1", "gdi32", "shell32", "ntdll", "ole32", "version", "winspool", "userenv", "uuid"]
- build assignment OS_LIBS @278: ["rt"]
- build assignment OS_LIBS @283: ["-lgvr"]
- build assignment OS_LIBS @316: ["sndio"]
- build assignment OS_LIBS @335: ["util"]
- build assignment OS_LIBS @340: ["shell32", "ole32", "version", "winspool", "comdlg32", "imm32", "msimg32", "netapi32", "shlwapi", "ws2_32", "dnsapi", "dwmapi", "iphlpapi", "uxtheme", "setupapi", "secur32", "sensorsapi", "portabledeviceguids", "wininet", "wintrust", "wtsapi32", "locationapi", "sapi", "dxguid", "dhcpcsvc", "d3dcompiler", "runtimeobject"]
- build assignment OS_LIBS @374: ["oleacc", "uiautomationcore"]
- build assignment OS_LIBS @383: ["usp10", "oleaut32"]
- build assignment OS_LIBS @389: ["mediandk", "sync"]
- build assignment SOURCES @403: ["!buildid.cpp"]
- build call GeneratedFile @411: "buildid.cpp"
- build assignment EXPORTS @415: ["buildid_section.h"]

### toolkit/library/rust/gkrust-features.mozbuild

Blob: `44206cc469a1fa9a44773cb48c64b01e40c90d09`. Parse: parsed.

- build assignment gkrust_features @5: ["for_xul"]
- build assignment gkrust_features @10: ["gecko_debug", "gecko_refcount_logging"]
- build assignment gkrust_features @16: ["thread_sanitizer"]
- build assignment gkrust_features @19: ["webrender_debugger"]
- build assignment gkrust_features @22: ["cubeb_pulse_rust"]
- build assignment gkrust_features @25: ["cubeb_coreaudio_rust"]
- build assignment gkrust_features @28: ["simd-accel"]
- build assignment gkrust_features @37: ["cubeb-remoting"]
- build assignment gkrust_features @40: ["moz_memory"]
- build assignment gkrust_features @43: ["moz_places"]
- build assignment gkrust_features @46: ["gecko_profiler_parse_elf"]
- build assignment gkrust_features @49: ["bitsdownload"]
- build assignment gkrust_features @52: ["libfuzzer"]
- build assignment gkrust_features @55: ["webrtc"]
- build assignment gkrust_features @58: ["glean_with_gecko"]
- build assignment gkrust_features @61: ["glean_disable_upload"]
- build assignment gkrust_features @64: ["with_dbus"]
- build assignment gkrust_features @67: ["crashreporter"]
- build assignment gkrust_features @69: ["oxidized_breakpad"]
- build assignment gkrust_features @72: ["webmidi_midir_impl"]
- build assignment gkrust_features @75: ["uniffi_fixtures"]
- build assignment gkrust_features @78: ["icu4x"]
- build assignment gkrust_features @81: ["libz-rs-sys"]
- build assignment gkrust_features @84: ["fontations"]
- build assignment gkrust_features @87: ["jxl_decoder"]
- build assignment gkrust_features @90: ["shell_windows"]
- build assignment gkrust_features @93: ["backgroundtaskregistrar"]
- build assignment gkrust_features @96: ["enable_tests"]
- build assignment gkrust_features @99: ["noise_xpcom"]

### toolkit/library/rust/moz.build

Blob: `b0c5c51031ce1cc916f9d6668c99c7a677883a83`. Parse: parsed.

- build call include @5: "gkrust-features.mozbuild"
- build call RustLibrary @7: "gkrust"
- build assignment RUST_TESTS @22: ["crashreporter", "crash_helper_common", "firefox-on-glean", "l10nregistry", "noise", "rsclientcerts-util", "selectors", "servo_arc", "qcms", "gkrust"]
- build assignment RUST_TESTS @38: ["nmhproxy"]
- build assignment RUST_TESTS @40: ["win32_process_mitigations"]
- build assignment RUST_TESTS @43: ["crash_helper_server"]
- build assignment RUST_TESTS @46: ["pushnotificationhelper"]
- build assignment RUST_TESTS @58: ["stylo_tests"]
- build assignment RUST_TESTS @62: ["style"]
- build assignment RUST_TESTS @65: ["dom_fragmentdirectives"]
- build assignment RUST_TESTS @67: ["dom_speculationrules"]
- build assignment RUST_TESTS @73: ["crashping"]
- build assignment RUST_TESTS @78: ["malloc_size_of_derive"]
- build assignment RUST_TESTS @81: ["bits_client"]
- build assignment RUST_TESTS @87: ["lockstore_rs"]
- build assignment USE_LIBS @96: ["mozglue", "nss"]
- build assignment USE_LIBS @103: ["sqlite"]
- build assignment USE_LIBS @107: ["freebl3", "softokn3"]
- build assignment USE_LIBS @113: ["freeblpriv3"]
- build assignment EXPORTS @119: ["/third_party/rust/rure/include/rure.h"]

### toolkit/locales/gen_multilocale.py

Blob: `1d151b68bf7d66ee4576cd97a5b7d453e31e2ace`. Parse: parsed.

- import sys @5
- function main @8-13

### toolkit/locales/generate_default_locale.py

Blob: `dc01af0bf1979c8c6a102e95c72aec58190ea966`. Parse: parsed.

- function main @8-11

### toolkit/locales/moz.build

Blob: `0929f5136756bb239218c03e69ed7f869b856f44`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Firefox Build System", "General"]
- build assignment JAR_MANIFESTS @11: ["jar.mn"]
- build call GeneratedFile @13: "multilocale.txt"
- build assignment FINAL_TARGET_FILES.res @14: ["!multilocale.txt"]
- build assignment LOCALIZED_GENERATED_FILES @18: ["default.locale"]
- build assignment LOCALIZED_FILES @21: ["!default.locale"]

### toolkit/modules/launchonlogin/moz.build

Blob: `5679aad0ab7c280e24f3fe8226739c4260be4fcc`. Parse: parsed.

- build assignment EXTRA_JS_MODULES @5: ["LaunchOnLogin.sys.mjs"]
- build assignment EXTRA_JS_MODULES.launchonlogin @10: ["WindowsLaunchOnLogin.sys.mjs"]
- build assignment EXTRA_JS_MODULES.launchonlogin @14: ["MacOSLaunchOnLogin.sys.mjs"]
- build assignment EXTRA_JS_MODULES.launchonlogin @18: ["UnsupportedLaunchOnLogin.sys.mjs"]

### toolkit/modules/moz.build

Blob: `d560cc59e36bf9c4acb6de8e6095929385b877b3`. Parse: parsed.

- build call include @5: "../components/telemetry/telemetry-constants.mozbuild"
- build assignment BUG_COMPONENT @8: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @11: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @14: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @17: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @20: ["Core", "Security: Process Sandboxing"]
- build assignment BUG_COMPONENT @23: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @26: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @29: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @32: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @35: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @38: ["Toolkit", "Form Manager"]
- build assignment BUG_COMPONENT @41: ["WebExtensions", "General"]
- build assignment BUG_COMPONENT @44: ["Firefox", "New Tab Page"]
- build assignment BUG_COMPONENT @47: ["Toolkit", "Application Update"]
- build assignment BUG_COMPONENT @50: ["Core", "Security: Process Sandboxing"]
- build assignment BUG_COMPONENT @53: ["Firefox Build System", "General"]
- build assignment BUG_COMPONENT @56: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @59: ["DevTools", "Console"]
- build assignment BUG_COMPONENT @62: ["Core", "Layout: Form Controls"]
- build assignment BUG_COMPONENT @65: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @68: ["Core", "Security: Process Sandboxing"]
- build assignment BUG_COMPONENT @71: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @74: ["Toolkit", "Password Manager"]
- build assignment BUG_COMPONENT @77: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @80: ["Core", "Spelling checker"]
- build assignment BUG_COMPONENT @83: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @86: ["Toolkit", "Form Manager"]
- build assignment BUG_COMPONENT @89: ["Firefox", "Toolbars and Customization"]
- build assignment BUG_COMPONENT @92: ["Toolkit", "Find Toolbar"]
- build assignment BUG_COMPONENT @95: ["Firefox", "Tabbed Browser"]
- build assignment BUG_COMPONENT @98: ["Toolkit", "Telemetry"]
- build assignment BUG_COMPONENT @101: ["Toolkit", "Add-ons Manager"]
- build assignment BUG_COMPONENT @104: ["Toolkit", "PopupNotifications and Notification Bars"]
- build assignment BUG_COMPONENT @107: ["Firefox", "Private Browsing"]
- build assignment BUG_COMPONENT @110: ["Core", "Widget: Cocoa"]
- build assignment BUG_COMPONENT @113: ["Toolkit", "Async Tooling"]
- build assignment BUG_COMPONENT @116: ["Application Services", "Remote Settings"]
- build assignment BUG_COMPONENT @119: ["Firefox", "Toolbars and Customization"]
- build assignment BUG_COMPONENT @122: ["Core", "SQLite and Embedded Database Bindings"]
- build assignment BUG_COMPONENT @125: ["Toolkit", "Content Prompts"]
- build assignment BUG_COMPONENT @128: ["Toolkit", "Application Update"]
- build assignment BUG_COMPONENT @131: ["Toolkit", "General"]
- build assignment XPCSHELL_TESTS_MANIFESTS @133: ["tests/xpcshell/xpcshell.toml"]
- build assignment BROWSER_CHROME_MANIFESTS @134: ["tests/browser/browser.toml"]
- build assignment MOCHITEST_CHROME_MANIFESTS @135: ["tests/chrome/chrome.toml"]
- build assignment MARIONETTE_MANIFESTS @136: ["tests/marionette/manifest.toml"]
- build assignment TESTING_JS_MODULES @138: ["tests/modules/MockDocument.sys.mjs", "tests/modules/OSKeyStoreTestUtils.sys.mjs", "tests/modules/PromiseTestUtils.sys.mjs", "tests/xpcshell/RegionTestUtils.sys.mjs", "tests/xpcshell/TestIntegration.sys.mjs"]
- build assignment SCHEDULES.exclusive @149: ["docs"]
- build assignment EXTRA_JS_MODULES @151: ["AboutPagesUtils.sys.mjs", "ActorManagerParent.sys.mjs", "AppMenuNotifications.sys.mjs", "AppServicesTracing.sys.mjs", "AsyncPrefs.sys.mjs", "BinarySearch.sys.mjs", "BrowserTelemetryUtils.sys.mjs", "BrowserUtils.sys.mjs", "CanonicalJSON.sys.mjs", "CertUtils.sys.mjs", "Color.sys.mjs", "Console.sys.mjs", "ContentDOMReference.sys.mjs", "CreditCard.sys.mjs", "DateNormalizationUtils.sys.mjs", "DeferredTask.sys.mjs", "E10SUtils.sys.mjs", "EventEmitter.sys.mjs", "FileUtils.sys.mjs", "FindBarContent.sys.mjs", "Finder.sys.mjs", "FinderHighlighter.sys.mjs", "FinderIterator.sys.mjs", "FinderParent.sys.mjs", "FinderSound.sys.mjs", "FirstStartup.sys.mjs", "FormLikeFactory.sys.mjs", "Geometry.sys.mjs", "HiddenFrame.sys.mjs", "IgnoreLists.sys.mjs", "IndexedDB.sys.mjs", "InlineSpellChecker.sys.mjs", "InlineSpellCheckerContent.sys.mjs", "Integration.sys.mjs", "JSONFile.sys.mjs", "JsonSchema.sys.mjs", "KeyboardLockUtils.sys.mjs", "KeywordUtils.sys.mjs", "Log.sys.mjs", "LogManager.sys.mjs", "NewTabUtils.sys.mjs", "NLP.sys.mjs", "ObjectUtils.sys.mjs", "OsEnvironment.sys.mjs", "OSKeyStore.sys.mjs", "PermissionsUtils.sys.mjs", "PopupNotifications.sys.mjs", "Preferences.sys.mjs", "PrivateBrowsingUtils.sys.mjs", "ProcessType.sys.mjs", "ProfileAge.sys.mjs", "ProfileKekPassword.sys.mjs", "Region.sys.mjs", "RemotePageAccessManager.sys.mjs", "ResetProfile.sys.mjs", "RustSharedRemoteSettingsService.sys.mjs", "SelectionUtils.sys.mjs", "ServiceRequest.sys.mjs", "ShortcutUtils.sys.mjs", "Sqlite.sys.mjs", "SubDialog.sys.mjs", "Timer.sys.mjs", "Troubleshoot.sys.mjs", "UpdateUtils.sys.mjs", "URLKeywordAnalyzer.sys.mjs", "URLKeywordStopWords.sys.mjs", "UrlUtils.sys.mjs", "WebChannel.sys.mjs"]
- build assignment MOZ_SRC_FILES @222: ["ColorPickerPanel.sys.mjs", "DateTimePickerPanel.sys.mjs", "FaviconUtils.sys.mjs", "InputPickerPanelCommon.sys.mjs", "RegionLocaleMap.sys.mjs"]
- build assignment EXTRA_JS_MODULES @231: ["AsanReporter.sys.mjs"]
- build assignment EXTRA_JS_MODULES @236: ["PropertyListUtils.sys.mjs", "RosettaUtils.sys.mjs"]
- build assignment EXTRA_JS_MODULES.third_party.jsesc @241: ["third_party/jsesc/jsesc.mjs"]
- build assignment EXTRA_JS_MODULES.sessionstore @242: ["sessionstore/PrivacyFilter.sys.mjs", "sessionstore/PrivacyLevel.sys.mjs", "sessionstore/SessionHistory.sys.mjs", "sessionstore/SessionStoreHelper.sys.mjs"]
- build assignment EXTRA_JS_MODULES.third_party.fathom @249: ["third_party/fathom/fathom.mjs"]
- build assignment EXTRA_PP_JS_MODULES @256: ["AppConstants.sys.mjs"]
- build assignment PP_FILES_EXTRA_DEPS @262: ["!/buildid.h", "!/source-repo.h"]
- build assignment EXTRA_JS_MODULES @265: ["ClipboardContextMenu.sys.mjs", "GMPExtractor.worker.js", "GMPInstallManager.sys.mjs", "GMPUtils.sys.mjs", "LightweightThemeConsumer.sys.mjs", "ScheduledTask.sys.mjs"]
- build assignment TESTING_JS_MODULES @273: ["tests/modules/SystemDelay.sys.mjs"]
- build assignment DIRS @276: ["launchonlogin", "subprocess"]
- build assignment EXTRA_JS_MODULES @287: ["WindowsRegistry.sys.mjs"]
- build assignment JAR_MANIFESTS @370: ["jar.mn"]
- build assignment XPIDL_SOURCES @374: ["nsIBrowserWindowTracker.idl", "nsIRegion.idl"]
- build assignment MOZ_SRC_FILES @381: ["PrefUtils.sys.mjs", "WebAuthnPromptHelper.sys.mjs"]

### toolkit/modules/subprocess/moz.build

Blob: `074f21a12fab7a6d305b033c4f5bc2cd3771db51`. Parse: parsed.

- build assignment EXTRA_JS_MODULES @5: ["Subprocess.sys.mjs"]
- build assignment EXTRA_JS_MODULES.subprocess @9: ["subprocess_common.sys.mjs", "subprocess_shared.js", "subprocess_worker_common.js"]
- build assignment EXTRA_JS_MODULES.subprocess @16: ["subprocess_shared_win.js", "subprocess_win.sys.mjs", "subprocess_win.worker.js"]
- build assignment EXTRA_JS_MODULES.subprocess @22: ["subprocess_shared_unix.js", "subprocess_unix.sys.mjs", "subprocess_unix.worker.js"]
- build assignment XPCSHELL_TESTS_MANIFESTS @28: ["test/xpcshell/xpcshell.toml"]
- build assignment SPHINX_TREES['toolkit_modules/subprocess'] @30: ["docs"]
- build assignment SCHEDULES.exclusive @33: ["docs"]

### toolkit/modules/subprocess/test/xpcshell/data_test_child.py

Blob: `27467cf64110935778c6e6c81afd63fc04c2809e`. Parse: parsed.

- import sys @10
- import time @11
- function sleep_for_a_little_bit @14-15
- function spawn_child_and_exit @18-87
- import subprocess @38
- function spawned_child @90-149
- import http.server @91
- import socketserver @92
- function spawned_child.print_to_parent_stdout @94-96
- class spawned_child.RequestHandler @101-135
- function spawned_child.RequestHandler.log_message @102-103
- function spawned_child.RequestHandler.do_DELETE @105-129
- function spawned_child.RequestHandler.do_GET @131-135

### toolkit/modules/subprocess/test/xpcshell/data_test_script.py

Blob: `2fc2a7e2248234d29b6a381421c6c44b52cb3eda`. Parse: parsed.

- import os @3
- import signal @4
- import struct @5
- import sys @6
- function output @9-15
- function echo_loop @18-24
- import msvcrt @28
- import psutil @47
- import time @62

### toolkit/modules/tests/marionette/test_first_startup.py

Blob: `6d8bbce02d15753e051815ca7a9303ff406bdc60`. Parse: parsed.

- from marionette_harness import MarionetteTestCase @5
- class TestFirstStartup @8-54
- function TestFirstStartup.setUp @9-15
- function TestFirstStartup.test_new_profile @17-36
- function TestFirstStartup.test_existing_profile @38-54

### toolkit/moz.build

Blob: `a7d7361df4cff67c548bb3f99a25bdd7ef285769`. Parse: parsed.

- build assignment EXTRA_COMPONENTS @7: ["l10n-registry.manifest"]
- build assignment DIRS @11: ["actors", "components", "content", "crashreporter", "locales", "modules", "mozapps/downloads", "mozapps/extensions", "mozapps/preferences", "profile", "themes"]
- build assignment DIRS @29: ["mozapps/notificationserver"]
- build assignment DIRS @32: ["mozapps/msixcomserver", "mozapps/msixcomserver-rust"]
- build assignment DIRS @38: ["mozapps/pushnotificationhelper"]
- build assignment DIRS @44: ["mozapps/defaultagent"]
- build assignment DIRS @47: ["mozapps/update"]
- build assignment DIRS @50: ["mozapps/update/common"]
- build assignment DIRS @55: ["components/maintenanceservice"]
- build assignment DIRS @57: ["xre"]
- build assignment DIRS @60: ["mozapps/handling"]
- build assignment DIRS @62: ["system/commonproxy", "system/unixproxy"]
- build assignment DIRS @67: ["mozapps/dmgInstallHelper", "mozapps/macos-frameworks", "system/commonproxy", "system/osxproxy"]
- build assignment DIRS @74: ["system/commonproxy", "system/windowsproxy", "system/windowsDHCPClient", "system/windowsPackageManager"]
- build assignment DIRS @81: ["system/androidproxy", "system/commonproxy"]
- build assignment TEST_HARNESS_FILES.testing.mochitest.browser.toolkit.crashreporter.test.browser @86: ["crashreporter/test/browser/crashreport.sjs"]
- build assignment DIRS @91: ["tests/gtest"]
- build assignment BUG_COMPONENT @94: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @97: ["Toolkit", "General"]
- build assignment BUG_COMPONENT @100: ["Firefox Build System", "General"]
- build assignment BUG_COMPONENT @103: ["Firefox Build System", "General"]
- build assignment BUG_COMPONENT @106: ["Firefox Build System", "General"]
- build assignment BUG_COMPONENT @109: ["Toolkit", "Preferences"]
- build assignment BUG_COMPONENT @112: ["Core", "Internationalization: Localization"]
- build assignment BUG_COMPONENT @115: ["Developer Infrastructure", "Lint and Formatting"]
- build call GeneratedFile @117: "content/neterror/aboutNetErrorCodes.js"

### toolkit/moz.configure

Blob: `20b0ec30a5472bcf15432ae6f10df79396230808`. Parse: parsed.

- function check_moz_app_id @16-18
- function nsis_toolkit_files @58-59
- function nsis_custom_plugins @67-68
- function nsis_custom_ui @76-77
- function disable_profile_pkcs11_modules @150-152
- function enable_enterprise @170-172
- function enterprise_console_url @198-216
- function check_moz_app_vendor @223-225
- function all_configure_options @235-275
- function fold_libs @282-283
- function gecko_profiler_parse_elf @302-313
- function dmd_default @332-333
- function dmd @346-348
- function midir_linux_support @361-364
- function midir_support @368-370
- function audio_backends_default @379-398
- function imply_aaudio @422-425
- function imply_alsa @429-436
- function imply_audiounit @440-443
- function imply_jack @447-448
- function imply_opensl @452-455
- function imply_oss @459-464
- function imply_pulseaudio @468-473
- function imply_sndio @477-482
- function imply_sunaudio @486-491
- function imply_wasapi @495-498
- function enable_alsa_option @543-544
- function enable_alsa_or_midir_linux_support @548-549
- build call include @599: "../js/moz.configure"
- build call include @604: "../build/moz.configure/node.configure"
- function l10n_base @619-633
- function toolkit_choices @642-661
- function toolkit_default @665-666
- function full_toolkit @679-681
- function toolkit @685-690
- function toolkit_define @697-699
- function toolkit_gtk @706-707
- function toolkit_gtk_x11 @711-712
- function toolkit_gtk_x11_optional @716-717
- function toolkit_gtk_wayland @721-722
- function toolkit_gtk_wayland_optional @726-727
- function wayland_headers @741-746
- function v4l2 @763-767
- function gl_provider @833-835
- function gl_provider_define @839-841
- function pdf_printing @851-853
- function fc_freetype @865-867
- function check_for_freetype2 @884-886
- function freetype2_combined_info @896-904
- function applemedia @913-915
- function wmf @925-926
- function wmfmediaengine @930-933
- function ffmpeg @946-947
- function dav1d_asm @962-964
- function dav1d_nasm @968-970
- function jxl @983-985
- function fontations @997-1000
- function openmax @1024-1027
- function eme_choices @1037-1049
- function eme_default @1054-1056
- function eme_modules @1070-1071
- function wmfcdm @1082-1084
- function packager_format @1101-1102
- function enable_minify_default @1117-1120
- function enable_minify @1133-1139
- function enable_minify_pdfjs_default @1147-1148
- function jar_maker_format @1162-1167
- function omnijar_name @1174-1179
- function check_places_and_geckoview_history @1233-1237
- function telemetry_on_by_default @1250-1251
- build call include @1264: "../build/moz.configure/keyfiles.configure"
- function webrender_debugger @1291-1293
- function app_system_headers @1310-1312
- function no_speechd_on_non_gtk @1321-1323
- function webspeech @1340-1342
- function tree_freetype @1375-1377
- function ft2_info @1388-1394
- function enable_cairo_ft @1401-1404
- function webdriver @1458-1460
- function geckodriver_default @1479-1486
- function geckodriver @1498-1500
- function webrtc_default @1509-1539
- function webrtc @1550-1552
- function raw_media_default @1570-1574
- function x11_libs @1589-1608
- build assignment libs @1590: ["x11", "xcb", "xcb-shm", "x11-xcb", "xext", "xfixes", "xrandr >= 1.4.0"]
- build assignment libs @1602: ["xcomposite", "xcursor", "xdamage", "xi"]
- function moz_x11_libs @1621-1630
- function enable_asan_reporter @1656-1658
- function has_elfhack @1698-1703
- function may_enable_legacy_elfhack @1714-1716
- function may_enable_relrhack @1719-1721
- function may_use_pack_relative_relocs @1735-1751
- function has_pack_relative_relocs @1764-1814
- build assignment pack_rel_relocs @1771: ["-Wl,-z,pack-relative-relocs"]
- function pack_relative_relocs_flags @1823-1838
- function which_elf_hack @1848-1875
- function relrhack_linker @1885-1890
- function relrhack_real_linker @1895-1899
- function relrhack_ldflags @1923-1930
- build assignment flags @1924: ["-B"]
- function idl_roots @1936-1941
- function proxy_bypass_protection @1958-1959
- function proxy_direct_failover @1974-1976
- function midl_names @1986-1995
- build assignment widl @1989: ["widl"]
- function check_for_midl @1999-2004
- function midl_flags @2027-2048
- function accessibility @2060-2079
- function a11y_log @2087-2088
- function require_signing @2098-2099
- function unsigned_addon_scopes @2120-2124
- function extensions_webidl_bindings_default @2147-2150
- function extensions_webidl_enabled @2161-2162
- function launcher_process_default @2172-2173
- function launcher @2184-2189
- function bundled_fonts_default @2219-2220
- function allow_bundled_fonts @2224-2225
- function reflow_perf @2245-2247
- function layout_debugger @2266-2268
- function with_system_libvpx_option @2307-2308
- function in_tree_vpx @2335-2340
- function vpx_nasm @2343-2348
- function vpx_as_flags @2351-2357
- function jpeg_flags @2374-2382
- function in_tree_jpeg_arm @2434-2441
- function in_tree_jpeg_mips64 @2444-2449
- function in_tree_jpeg @2466-2491
- function jpeg_nasm @2494-2497
- function deprecated_system_png_path @2550-2555
- function ffvpx @2576-2635
- build assignment flags @2588: ["-DPIC", "-DWIN32", "-DPREFIX", "-Pconfig_win32.asm"]
- build assignment flags @2590: ["-D__x86_64__", "-DPIC", "-DWIN64", "-DMSVC", "-Pconfig_win64.asm"]
- build assignment flags @2598: ["-DPIC", "-DWIN64"]
- build assignment flags @2603: ["-DPIC", "-DMACHO", "-DPREFIX"]
- build assignment flags @2605: ["-D__x86_64__", "-Pconfig_darwin64.asm"]
- build assignment flags @2613: ["-D__x86_64__", "-DPIC", "-DELF", "-Pconfig_android_x86_64.asm"]
- build assignment flags @2617: ["-DPIC", "-DELF"]
- build assignment flags @2620: ["-D__x86_64__", "-DPIC", "-DELF", "-Pconfig_unix64.asm"]
- build assignment flags @2623: ["-DPIC", "-DELF"]
- function ffvpx_nasm @2639-2641
- function ffvpx @2647-2650
- function need_nasm @2662-2673
- function check_nasm @2686-2689
- function nasm_version @2694-2700
- function check_nasm_version @2704-2711
- function nasm_asflags @2715-2729
- build assignment asflags @2726: ["-f", "elf32"]
- build assignment asflags @2728: ["-f", "elf64"]
- function dxc_supports_target @2741-2742
- function dxcompiler @2753-2777
- function windows_app_sdk_task_job_name @2794-2795
- function windows_app_sdk @2806-2822
- function has_remote @2832-2834
- function wasm_sandboxing_libraries @2844-2852
- function default_wasm_sandboxing_libraries @2856-2860
- function requires_wasm_sandboxing @2874-2876
- function bootstrap_wasi_sysroot @2891-2892
- function wasi_sysroot @2899-2909
- function wasi_sysroot_flags @2912-2916
- function wasm_compiler_with_flags @2918-2922
- function wasm_compiler_error @2925-2933
- function wasm_compiler_error.wasm_compiler_error @2927-2931
- function check_wasm_compiler @2936-2954
- function wasm_cc_with_flags @2960-2961
- function wasm_cxx_with_flags @2975-2976
- function wasm_cflags @2985-2989
- function wasm_cxxflags @2997-3001
- function wasm_sandboxing @3007-3011
- function wasm_sandboxing_config_defines @3015-3022
- function glean_android @3080-3081
- function pdbstr_paths @3102-3115
- function allow_missing_wintools @3119-3123
- function forkserver_default @3147-3152
- function forkserver_flag @3164-3172
- build call include @3189: "../build/moz.configure/nss.configure"
- function enable_startupcache @3224-3226
- function check_official_branding_directory @3272-3276
- function moz_branding_directory @3285-3296
- function real_branding_directory @3303-3306
- function mangled_username @3328-3332
- function moz_app_displayname @3336-3343
- function moz_backgroundtask_activatable_class_id @3354-3355
- function moz_app_remotingname @3380-3385
- function moz_child_process_name @3394-3402
- function oxidized_breakpad @3449-3452
- function want_wine @3466-3467
- function deprecated_system_libevent_path @3488-3493
- function crashreporter_default @3503-3510
- function data_reporting @3541-3542
- function enable_dbus_option @3573-3574
- function necko_wifi_when @3586-3589
- function necko_wifi_dbus @3604-3610
- function moz_pkg_platform @3707-3729
- function pkg_langpack_path @3736-3739
- function moz_pkg_appname @3753-3756
- function moz_pkg_version @3770-3773
- function moz_pkg_format @3787-3803
- function pkg_suffix @3811-3812
- function moz_pkg_dir_default @3819-3822
- function pkg_jsshell_name @3830-3834
- function no_pkg_files @3842-3843
- function package_toolkit_defines @3857-3872
- build assignment defines @3864: ["-DDIR_MACOS=Contents/MacOS/", "-DDIR_RESOURCES=Contents/Resources/"]
- build assignment defines @3869: ["-DDIR_MACOS=", "-DDIR_RESOURCES="]
- function moz_langpack_eid_host @3881-3884
- function disable_smart_cards @3897-3898
- function test_package_archive_choices @3911-3912
- function test_package_configuration @3931-3967
- build assignment stage_targets @3940: ["stage-config", "stage-mach", "stage-extensions", "stage-mochitest"]
- function mac_bundle_name @3991-3995
- function moz_mac_bundle_id @4003-4012
- function moz_eme_process_bundle_id @4036-4041
- function moz_gpu_process_bundle_id @4070-4075
- function moz_pkcs11_process_bundle_id @4107-4116
- function moz_pkg_binpath @4122-4125
- function moz_pkg_respath @4133-4136
- build call include @4145: "../build/moz.configure/update-programs.configure"
- function moz_package_extra_args @4161-4189
- build assignment args @4176: ["--app-name"]
- build assignment args @4179: ["--dsstore", "--background", "--icon", "--volume-name"]
- function sandbox_default @4208-4217
- function enable_system_pixman_option @4252-4253
- function in_tree_pixman @4256-4257
- function default_user_appdir @4289-4294
- function user_appdir @4304-4309
- function forced_or_dotted_user_appdir @4312-4313
- function need_perl @4450-4452
- function perl_version_check @4459-4490
- function perl_version_check.get_perl_version @4462-4470
- function perl_version_check.check_perl_version @4473-4475
- function perl_version_check.has_full_perl_installation @4480-4482
- function perl_version_check.require_full_perl_installation @4485-4490
- function windows_rs_dir @4560-4596
- function onnxruntime_task_name @4606-4618
- function need_boostrap_onnxruntime @4629-4632
- function onnx_runtime_path @4642-4664
- function is_onnxruntime_supported_by_taskcluster @4674-4682
- function desktop_launcher_enabled @4703-4704
- function enable_appservices_in_tree @4718-4720
- function libmegazord_artifacts @4733-4735

### toolkit/mozapps/defaultagent/moz.build

Blob: `c1f7ca3e55e7de94fff0180afb2e1de2597e5f54`. Parse: parsed.

- build assignment JAR_MANIFESTS @7: ["jar.mn"]
- build assignment DIRS @9: ["proxy"]
- build assignment UNIFIED_SOURCES @11: ["Cache.cpp", "common.cpp", "DefaultAgent.cpp", "DefaultBrowser.cpp", "DefaultPDF.cpp", "EventLog.cpp", "Notification.cpp", "Policy.cpp", "Registry.cpp", "ScheduledTask.cpp", "ScheduledTaskRemove.cpp", "SetDefaultBrowser.cpp", "Telemetry.cpp", "UtfConvert.cpp", "WindowsMutex.cpp"]
- build assignment EXPORTS.mozilla @29: ["DefaultAgent.h", "WindowsMutex.h"]
- build assignment USE_LIBS @34: ["jsoncpp"]
- build assignment LOCAL_INCLUDES @38: ["/browser/components/shell/", "/other-licenses/nsis/Contrib/CityHash/cityhash", "/toolkit/components/jsoncpp/include"]
- build assignment OS_LIBS @44: ["advapi32", "bcrypt", "comsupp", "crypt32", "kernel32", "netapi32", "ole32", "oleaut32", "rpcrt4", "shell32", "shlwapi", "taskschd", "userenv", "wininet", "ws2_32", "ntdll"]
- build assignment XPIDL_SOURCES @63: ["nsIDefaultAgent.idl", "nsIWindowsMutex.idl"]
- build assignment XPCOM_MANIFESTS @70: ["components.conf"]
- build assignment XPCSHELL_TESTS_MANIFESTS @74: ["tests/xpcshell/xpcshell.toml"]
- build assignment TEST_DIRS @87: ["tests/gtest"]
- build assignment BUG_COMPONENT @90: ["Toolkit", "Default Browser Agent"]
- build assignment EXTRA_JS_MODULES.backgroundtasks @92: ["BackgroundTask_defaultagent.sys.mjs"]
- build assignment EXTRA_JS_MODULES @96: ["DefaultAgentScheduler.sys.mjs"]
- build assignment SOURCE_HEADERS @100: ["Cache.h", "common.h", "DefaultBrowser.h", "DefaultPDF.h", "EventLog.h", "Notification.h", "Policy.h", "Registry.h", "ScheduledTask.h", "ScheduledTaskRemove.h", "SetDefaultBrowser.h", "Telemetry.h", "UtfConvert.h"]

### toolkit/mozapps/defaultagent/proxy/moz.build

Blob: `acaab7bac7ad789b45d5c0996026ded159c745d2`. Parse: parsed.

- build call Program @5: "default-browser-agent"
- build assignment UNIFIED_SOURCES @9: ["../EventLog.cpp", "../ScheduledTaskRemove.cpp", "main.cpp"]
- build assignment SOURCES @15: ["/browser/components/shell/WindowsDefaultBrowser.cpp", "/other-licenses/nsis/Contrib/CityHash/cityhash/city.cpp"]
- build assignment LOCAL_INCLUDES @20: ["../", "/browser/components/shell/", "/mfbt/", "/other-licenses/nsis/Contrib/CityHash/cityhash", "/toolkit/mozapps/update/common/"]
- build assignment OS_LIBS @28: ["advapi32", "comsupp", "netapi32", "ole32", "oleaut32", "shell32", "shlwapi", "taskschd", "user32"]
- build assignment WIN32_EXE_LDFLAGS @61: ["-ENTRY:wmainCRTStartup"]
- build assignment WIN32_EXE_LDFLAGS @63: ["-municode"]
- build assignment BUG_COMPONENT @74: ["Toolkit", "Default Browser Agent"]

### toolkit/mozapps/defaultagent/tests/gtest/moz.build

Blob: `0c097d950c8937fa3ce81bcd4ff5fbe817e7d1b0`. Parse: parsed.

- build call Library @5: "DefaultAgentTest"
- build assignment UNIFIED_SOURCES @7: ["CacheTest.cpp", "DefaultAgentTest.cpp", "SetDefaultBrowserTest.cpp"]
- build assignment LOCAL_INCLUDES @13: ["/browser/components/shell/", "/toolkit/mozapps/defaultagent"]
- build assignment OS_LIBS @18: ["advapi32", "bcrypt", "crypt32", "kernel32", "rpcrt4"]

### toolkit/mozapps/dmgInstallHelper/moz.build

Blob: `74de6806ba5df913af8b62c5a49c5f71eacc5ecf`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Firefox", "Installer"]
- build call Program @11: "org.mozilla.dmgInstallHelper"
- build assignment SOURCES @13: ["dmgInstallHelper.mm"]
- build assignment OS_LIBS @15: ["-framework Cocoa", "-framework Security"]
- build assignment CMMFLAGS @17: ["-fobjc-arc"]
- build call GeneratedFile @21: "dmgInstallHelper-Info.plist"
- build assignment LDFLAGS @32: ["-sectcreate", "__TEXT", "__info_plist", "-sectcreate", "__TEXT", "__launchd_plist"]
- build assignment EXTRA_LINK_DEPS @43: ["!dmgInstallHelper-Info.plist", "Launchd.plist"]
- build assignment EXPORTS @45: ["dmgInstallProtocol.h"]

### toolkit/mozapps/downloads/moz.build

Blob: `9f53972a0a68b32b49d5f638f02be4200e61020a`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Toolkit", "Downloads API"]
- build assignment TEST_DIRS @8: ["tests"]
- build assignment EXTRA_JS_MODULES @10: ["DownloadLastDir.sys.mjs", "DownloadUtils.sys.mjs", "HelperAppDlg.sys.mjs"]
- build assignment XPCOM_MANIFESTS @16: ["components.conf"]
- build assignment JAR_MANIFESTS @20: ["jar.mn"]

### toolkit/mozapps/downloads/tests/moz.build

Blob: `e39c58ff27a9f524ee11da125109b3fabda12e79`. Parse: parsed.

- build assignment XPCSHELL_TESTS_MANIFESTS @5: ["unit/xpcshell.toml"]
- build assignment BROWSER_CHROME_MANIFESTS @6: ["browser/browser.toml"]

### toolkit/mozapps/extensions/gen_built_in_addons.py

Blob: `830cb6b26ebc4ae15b9215b02edf4a63bed127f1`. Parse: parsed.

- import argparse @5
- import json @6
- import os.path @7
- import sys @8
- import buildconfig @10
- import mozpack.path @11
- from mozpack.copier import FileRegistry @13
- from mozpack.manifests import InstallManifest @14
- function get_registry @27-48
- function get_child @51-59
- function main @62-109
- function main.sort_by_dirname @102-103

### toolkit/mozapps/extensions/internal/moz.build

Blob: `2d89b848c5dc0db9aa5241df0200fb5cdef0c82f`. Parse: parsed.

- build assignment EXTRA_JS_MODULES.addons @5: ["AddonRepository.sys.mjs", "AddonSettings.sys.mjs", "AddonUpdateChecker.sys.mjs", "crypto-utils.sys.mjs", "ProductAddonChecker.sys.mjs", "siteperms-addon-utils.sys.mjs", "ThemesBundledLocalization.sys.mjs", "XPIDatabase.sys.mjs", "XPIExports.sys.mjs", "XPIInstall.sys.mjs", "XPIProvider.sys.mjs"]
- build assignment EXTRA_JS_MODULES.addons @20: ["GMPProvider.sys.mjs", "ModelHubProvider.sys.mjs", "SitePermsAddonProvider.sys.mjs"]
- build assignment TESTING_JS_MODULES @27: ["AboutAddonsTestUtils.sys.mjs", "AddonTestUtils.sys.mjs"]

### toolkit/mozapps/extensions/moz.build

Blob: `5df39c37dbf7da2d7556de30e8588e8a9dcb7370`. Parse: parsed.

- build assignment SCHEDULES.exclusive @8: ["docs"]
- build assignment DIRS @13: ["internal"]
- build assignment TEST_DIRS @16: ["test"]
- build assignment XPIDL_SOURCES @18: ["amIAddonManagerStartup.idl", "amIWebInstallPrompt.idl"]
- build assignment manifest.flags @33: ["--builtin-addons=browser/chrome/browser/builtin-addons"]
- build assignment manifest.flags @52: ["--builtin-addons=chrome/messenger/builtin-addons"]
- build assignment EXTRA_PP_COMPONENTS @61: ["extensions.manifest"]
- build assignment EXTRA_JS_MODULES @65: ["AbuseReporter.sys.mjs", "AddonManager.sys.mjs", "amContentHandler.sys.mjs", "amManager.sys.mjs", "amWebAPI.sys.mjs", "Blocklist.sys.mjs", "LightweightThemeManager.sys.mjs"]
- build assignment JAR_MANIFESTS @75: ["jar.mn"]
- build assignment EXPORTS.mozilla @77: ["AddonContentPolicy.h", "AddonManagerStartup.h", "AddonManagerWebAPI.h"]
- build assignment UNIFIED_SOURCES @83: ["AddonContentPolicy.cpp", "AddonManagerStartup.cpp", "AddonManagerWebAPI.cpp"]
- build assignment XPCOM_MANIFESTS @89: ["components.conf"]
- build assignment LOCAL_INCLUDES @93: ["/chrome", "/dom/base"]
- build assignment BUG_COMPONENT @101: ["Toolkit", "Add-ons Manager"]
- build assignment BUG_COMPONENT @104: ["Toolkit", "Blocklist Implementation"]
- build assignment BUG_COMPONENT @107: ["Toolkit", "Blocklist Implementation"]
- build assignment SOURCE_HEADERS @109: ["AddonManagerStartup-inlines.h"]

### toolkit/mozapps/extensions/test/browser/moz.build

Blob: `8ede9844e3f1904096a8ab65988e1b2eacc1991d`. Parse: parsed.

- build assignment BROWSER_CHROME_MANIFESTS @5: ["browser.toml"]
- build assignment addons @9: ["browser_dragdrop1", "browser_dragdrop1.1", "browser_dragdrop2", "browser_dragdrop_incompat", "browser_installssl", "browser_theme"]

### toolkit/mozapps/extensions/test/create_xpi.py

Blob: `21a6d260d3072ab80fc4ff7ac90a9786933b4003`. Parse: parsed.

- from os.path import abspath,relpath @5
- from mozbuild.action.zip import main @7
- function main @10-19

### toolkit/mozapps/extensions/test/moz.build

Blob: `c6f52bd15642cfc83d891a7e1f6a507cfa0baa4c`. Parse: parsed.

- build assignment DIRS @5: ["browser"]
- build assignment BROWSER_CHROME_MANIFESTS @7: ["xpinstall/browser.toml"]
- build assignment MOCHITEST_MANIFESTS @8: ["mochitest/mochitest.toml"]
- build assignment MOCHITEST_CHROME_MANIFESTS @9: ["mochitest/chrome.toml"]
- build assignment XPCSHELL_TESTS_MANIFESTS @11: ["xpcshell/rs-blocklist/xpcshell.toml", "xpcshell/xpcshell-unpack.toml", "xpcshell/xpcshell.toml"]
- build assignment BUG_COMPONENT @18: ["Toolkit", "Blocklist Implementation"]

### toolkit/mozapps/handling/moz.build

Blob: `95d59d7e6e6e37f94d679db59d226f852474a575`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Firefox", "File Handling"]
- build assignment EXTRA_JS_MODULES @8: ["ContentDispatchChooser.sys.mjs"]
- build assignment XPCOM_MANIFESTS @12: ["components.conf"]
- build assignment JAR_MANIFESTS @16: ["jar.mn"]

### toolkit/mozapps/installer/find-dupes.py

Blob: `bf94da270d401a0c9dc78cd58625f4bce7df21b4`. Parse: parsed.

- import sys @5
- import hashlib @6
- import functools @7
- from mozbuild.preprocessor import Preprocessor @8
- from mozbuild.util import DefinesAction @9
- from mozpack.packager.unpack import UnpackFinder @10
- from mozpack.files import DeflatedFile @11
- from io import StringIO @12
- import argparse @13
- import buildconfig @14
- function normalize_osx_path @22-32
- function is_l10n_file @35-40
- function normalize_path @43-44
- class AllowedDupes @47-63
- function AllowedDupes.add @51-55
- function AllowedDupes.is_allowed @57-63
- function find_dupes @66-122
- function main @125-162

### toolkit/mozapps/installer/informulate.py

Blob: `06bf0c553da49138bd06fbd687748e0965abe0bb`. Parse: parsed.

- from argparse import ArgumentParser @9
- import datetime @10
- import buildconfig @11
- import json @12
- import mozinfo @13
- import os @14
- import sys @15
- function main @18-122
- function main.stringify @53-56

### toolkit/mozapps/installer/moz.build

Blob: `273b0818cc0f2dc530df2f6866e2819d69b72b6c`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Firefox", "Installer"]

### toolkit/mozapps/installer/packager.py

Blob: `baee8962509c39f5279a0c9b314dfbf1a6aacfe3`. Parse: parsed.

- from mozpack.packager.formats import FlatFormatter,JarFormatter,OmniJarFormatter @5
- from mozpack.packager import preprocess_manifest,preprocess,Component,SimpleManifestSink @10
- from mozpack.files import GeneratedFile,FileFinder,File @16
- from mozpack.copier import FileCopier,Jarrer @21
- from mozpack.errors import errors @25
- from mozpack.files import ExecutableFile @26
- import mozpack.path @27
- import buildconfig @28
- from argparse import ArgumentParser @29
- from createprecomplete import generate_precomplete @30
- import os @31
- import plistlib @32
- from io import StringIO @33
- import subprocess @34
- class PackagerFileFinder @37-47
- function PackagerFileFinder.get @38-47
- class RemovedFiles @50-65
- function RemovedFiles.__init__ @55-57
- function RemovedFiles.handle_line @59-65
- function split_define @68-80
- class NoPkgFilesRemover @83-112
- function NoPkgFilesRemover.__init__ @88-97
- function NoPkgFilesRemover.add_base @99-100
- function NoPkgFilesRemover.add @102-106
- function NoPkgFilesRemover.add_manifest @108-109
- function NoPkgFilesRemover.contains @111-112
- function main @115-293
- from mozpack.mozjar import JarLog @279

### toolkit/mozapps/installer/strip.py

Blob: `ef81b1a2b62b6e5aa57cbecdd54adec28bac9a4f`. Parse: parsed.

- import sys @9
- from mozpack.files import FileFinder @10
- from mozpack.copier import FileCopier @11
- function strip @14-21

### toolkit/mozapps/installer/unify.py

Blob: `8b93a8dcea527384451f0856837655a6c71ed8fb`. Parse: parsed.

- import argparse @5
- import os @6
- import buildconfig @7
- from mozpack.packager.formats import FlatFormatter,JarFormatter,OmniJarFormatter @8
- from mozpack.packager import SimplePackager @13
- from mozpack.copier import FileCopier,Jarrer @14
- from mozpack.errors import errors @18
- from mozpack.files import FileFinder @19
- from mozpack.mozjar import JAR_DEFLATED @20
- from mozpack.packager.unpack import UnpackFinder @21
- from mozpack.unify import UnifiedBuildFinder @22
- function main @25-73

### toolkit/mozapps/installer/unpack.py

Blob: `34edb59e38442447ea73f68476ecd14df17ab0f3`. Parse: parsed.

- import argparse @5
- import sys @6
- import os @7
- from mozpack.packager.unpack import unpack @8
- import buildconfig @9
- function main @12-21

### toolkit/mozapps/installer/windows/nsis/preprocess-locale.py

Blob: `280ab3d0855d26cd588d1fa4f3c229c438badb47`. Parse: parsed.

- from codecs import BOM_UTF16_LE @14
- import io @15
- from os.path import join,isfile @16
- import sys @17
- from optparse import OptionParser @18
- function open_utf16le_file @21-27
- function get_locale_strings @30-65
- function lookup @68-72
- function preprocess_locale_files @75-118
- function create_nlf_file @121-168
- function preprocess_locale_file @171-189
- function convert_utf8_utf16le @192-204

### toolkit/mozapps/macos-frameworks/ChannelPrefs-localbuild/moz.build

Blob: `65e005d4478129b5f8bd9f1457db7e23f2c9eb83`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Toolkit", "Application Update"]
- build assignment UNIFIED_SOURCES @13: ["../ChannelPrefs/ChannelPrefs.mm"]
- build assignment OS_LIBS @17: ["-framework Foundation"]
- build assignment framework.Resources @30: ["../ChannelPrefs/Info.plist"]

### toolkit/mozapps/macos-frameworks/ChannelPrefs/moz.build

Blob: `cb0a120dafbdacac19dcbdd91cf4ff7ee87e04a5`. Parse: parsed.

- build assignment BUG_COMPONENT @6: ["Toolkit", "Application Update"]
- build assignment EXPORTS @10: ["ChannelPrefs.h"]
- build assignment UNIFIED_SOURCES @14: ["ChannelPrefs.mm"]
- build assignment OS_LIBS @18: ["-framework Foundation"]
- build assignment FINAL_TARGET_FILES['ChannelPrefs.framework'] @31: ["!/dist/update_framework_artifacts/ChannelPrefs-localbuild.framework/ChannelPrefs"]
- build assignment FINAL_TARGET_FILES['ChannelPrefs.framework'].Resources @34: ["Info.plist"]

## Validation and limits

The parser checked syntax only. This pass cannot prove runtime contracts, ownership, selected build settings, executed branches, or design reasons. Build files use a Python-based domain-specific language; parsing them as Python does not validate the build system. Byte decoding uses UTF-8; special encoding declarations and intentionally invalid fixtures may fail.
