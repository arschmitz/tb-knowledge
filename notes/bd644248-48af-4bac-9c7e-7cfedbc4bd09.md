<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:17:22.071Z","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["1bfb612ddceb74a0a0149d6553cc6789cb8daf591a2dc76be3e127237fd8a1aa"],"sourceAt":"2026-10-13T04:17:22.071Z","correctionOf":"notes/2b94dc26-013d-4b7e-b66c-13466d91c4ec.md"}} -->
# firefox/js JavaScript function map 608

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser: Espree 10.3.0.

Each entry records syntax from a parsed file. Functions include anonymous callbacks and arrows. A name inferred from an assignment or property is a navigation aid, not proof of the runtime receiver. Ranges refer to the pinned source. Parameter counts include rest and destructured parameters as one parameter each. Async means the syntax uses async. Generator means the syntax uses function*.

Imports and literal importESModule calls identify written module names. They are not resolved dependencies. This map does not establish function behavior, runtime callers, thread use, side effects, failure handling, or reasons for the design. Parsing a fixture does not make its code production behavior. Failed parses remain listed.

## File map

### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-delete.js

Blob: `9e67531e65fcf02850d41e935f784f3840e9032d`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-get-in-prototype.js

Blob: `8e2435b3f4ec9c549385fc6b63fdd9676347ef40`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-get.js

Blob: `e5d4a194a446a5c703de72564d165412b37146ed`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-getOwnProperty.js

Blob: `9a28daa8dc72761db7cd797128c23cb9d638555e`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-hasProperty-in-prototype.js

Blob: `0825c86ba6585e0dbb41a76bad7649f8f05bdcc1`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-hasProperty.js

Blob: `535f5982ff72aafbce713d4da798ed6cfd99a0f2`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-super-get.js

Blob: `f2e93adcfdda72bbaacf113feda33166ef9fab1f`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-super-property-define.js

Blob: `7556d28805040d3681e1de2d9eb75d39ed1849ec`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-other-super-property-set-exported.js

Blob: `2a31c8d1593146a6098c8f9c5f525bb0735d413e`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-defineOwnProperty.js

Blob: `0125a724a8ec427d314b8bc4fda013ebb411961c`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-delete.js

Blob: `b4bc1913541ee52a36167a62db4dec1bde876761`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-get-in-prototype.js

Blob: `a07faffe1fdffbf6c5b0afef5883b25e85791f22`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-get.js

Blob: `02b332ee450202b110c9d4f9760ef0ca0adb0d60`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-getOwnProperty.js

Blob: `22d4ec8ae43d5ae8ac79ac8cd82275ce56e6f99c`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-hasProperty-in-prototype.js

Blob: `fc826d2fa68c61745cea014983f12c7a98491325`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-hasProperty.js

Blob: `0e88df1075a8ed6e90b663a2326c636722a9bf9a`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-super-get.js

Blob: `61e8a21e44da61f45e543a739f1707b465ce2b57`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-super-property-define.js

Blob: `2e60c11996c2c1fad21b00266ce3ba4f4dc959d1`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/ignore-symbol-toStringTag-super-property-set-exported.js

Blob: `78d0b2e58226fb100dc0d10872e467d595ebacaf`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/setup_FIXTURE.js

Blob: `d71b2fa95eba84f49539e707623154abf43ef7f7`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-defineOwnProperty.js

Blob: `83a485f9d784fbd0ad127778f93a54b59eeaa05f`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-delete.js

Blob: `7190da03851eef34467aa01c16a0b61ba418a7f4`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-get-in-prototype.js

Blob: `5acdcb7f093853f0b882efd1b0303a986a45452f`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-get.js

Blob: `033feee6f8dcc3d09b8d47b433fddb0653cb01c4`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-getOwnProperty.js

Blob: `3cbffe45fc591b4cc64ab46391c0bf44777dd8ba`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-hasProperty-in-prototype.js

Blob: `6d427fe26658a8815248802daba361e0271dd821`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-hasProperty.js

Blob: `dd746c1f365fdc7a59f720a2ca8cd6598d47ac08`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-super-get.js

Blob: `ede1faf9dd516e35335fc3be8af0acb7c1df16be`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-super-property-define.js

Blob: `98a2b032ee95f64d2d6ae457f072b4e7bf2f0e8c`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-exported-string-super-property-set-exported.js

Blob: `456cac4bb1454e02f97df03b98f78604fa236b48`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-defineOwnProperty.js

Blob: `360d5fd5f5742cda24218b2180690caca6672147`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-delete.js

Blob: `452bc8226c7ffc8e3ad3aa5cdd951d4756b7e267`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-get-in-prototype.js

Blob: `706a97a4d0f07e6247db059c20c509cea2a0e678`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-get.js

Blob: `435581edaa9068f11f3832a8fb51beaeca1553d3`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-getOwnProperty.js

Blob: `b64d4310afc05d7fb00f40397bc7e59cd9401588`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-hasProperty-in-prototype.js

Blob: `9d631b8c6c2f3b03417bf5bdc369cd5b8c6881b8`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-hasProperty.js

Blob: `1ee0c3bd46cbe97ea81692fc367840bceb18eadb`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-super-get.js

Blob: `f65fdcd4ebf7486fa09d08b016f2be6adaa8fe2f`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-super-property-define.js

Blob: `c27e1ec8801290fe1b1018ba3c067853878925ca`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-not-exported-string-super-property-set-exported.js

Blob: `591ae6fb8f2b12f5d22ecaf3bbde9e593a91bab5`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-ownPropertyKey-names.js

Blob: `7bd160bce89519792a48b6225400a10522258014`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-ownPropertyKeys-symbols.js

Blob: `16cc40f5976cf11c87a16595f3427af720da8d0f`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/evaluation-triggers/trigger-ownPropertyKeys.js

Blob: `e2b00be33f568a391c54dd3ad733a6594c2860b0`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/syntax/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/syntax/dep_FIXTURE.js

Blob: `c0a2af180a57fd9b9fdd6ec17ab2d5d81cce63d8`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/syntax/import-attributes.js

Blob: `8bc844828801c3b8f81d2e259670b421e225b7dd`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-default-and-defer-namespace.js

Blob: `13240623bfe3d0ab27f2c6b5ca17bdc2150da54d`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-defer-as-with-no-asterisk.js

Blob: `e0a7baff23b9df8cbcd78ad4941bfd70301a08e0`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-defer-default-and-namespace.js

Blob: `c2e44ec5cc0fd6ef96327a7f1345869584e2f8e2`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-defer-default.js

Blob: `1cd25c34b6124cb82db9bfa916682e5b5481ca80`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-defer-named.js

Blob: `7608bde96abcc9586d9f1daa55129dda9fcc2d90`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/invalid-export-defer-namespace.js

Blob: `bae39386cd181db1bd9a7b89efb4c72f5088a423`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/import-defer/syntax/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/import/import-defer/syntax/valid-default-binding-named-defer.js

Blob: `e19f074ffa01b10713a208247614d16ee397f5fc`. Role: test-path,source. Parse: module.

- Module ./dep_FIXTURE.js @29; ImportDeclaration

### js/src/tests/test262/language/import/import-defer/syntax/valid-defer-namespace.js

Blob: `2d9d49b52036a32c03e28653cab2c58ecf2f16c4`. Role: test-path,source. Parse: failed.

Failure: 'import' and 'export' may appear only with 'sourceType: module'


### js/src/tests/test262/language/import/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/keywords/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/keywords/ident-ref-break.js

Blob: `af0007cbef9c678a43b57633e6d65588994abb60`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-case.js

Blob: `5140cd46d80d3c9518a5e33d63528983af87c32b`. Role: test-path,source. Parse: failed.

Failure: Unexpected token case


### js/src/tests/test262/language/keywords/ident-ref-catch.js

Blob: `0079c4a873b77307587a8b452aeb019cc4e7e3d5`. Role: test-path,source. Parse: failed.

Failure: Unexpected token catch


### js/src/tests/test262/language/keywords/ident-ref-continue.js

Blob: `abd27743dfa0507064582feb9ad18aa0d812ae8e`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-default.js

Blob: `b7e1cb4a1920f4ef6a5c89b43ba112d9462b965f`. Role: test-path,source. Parse: failed.

Failure: Unexpected token default


### js/src/tests/test262/language/keywords/ident-ref-delete.js

Blob: `9465de9a18a702dd2e50f1b317b839f71859b7af`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-do.js

Blob: `1aa90502896593f677554bbf12711673e50894f4`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-else.js

Blob: `6436984a2aaceb78e97fb3fa24e785c6cd7485be`. Role: test-path,source. Parse: failed.

Failure: Unexpected token else


### js/src/tests/test262/language/keywords/ident-ref-finally.js

Blob: `fef8034d1a25fe18fd0360b0a3da6964b4d6bc95`. Role: test-path,source. Parse: failed.

Failure: Unexpected token finally


### js/src/tests/test262/language/keywords/ident-ref-for.js

Blob: `9f228836a9b01395f9ea9da7d06bf2e7461fd63a`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-function.js

Blob: `5567fb4aa913832f836986de995bc25a0428a6b4`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-if.js

Blob: `8648fe5632b2a8fa0386499d08b28314144c137e`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-in.js

Blob: `852a703f755e14cb2737a85f05307d662125b13c`. Role: test-path,source. Parse: failed.

Failure: Unexpected token in


### js/src/tests/test262/language/keywords/ident-ref-instanceof.js

Blob: `ca9a2c5a8e67842bbe516fe0b11fef2bf4628573`. Role: test-path,source. Parse: failed.

Failure: Unexpected token instanceof


### js/src/tests/test262/language/keywords/ident-ref-new.js

Blob: `0b98569cf1112f6a91b9ba0a403b024086af031f`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-return.js

Blob: `ca6cd62ddf45968df69e79b45c33cdee2aa70a26`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-switch.js

Blob: `0fbeb95b26655c42587f9e7d90122f146d3f6217`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-this.js

Blob: `c990b5a34c47920d4a508569dfc20b8dc88a3ab9`. Role: test-path,source. Parse: failed.

Failure: Unexpected keyword 'this'


### js/src/tests/test262/language/keywords/ident-ref-throw.js

Blob: `7e7c056beb295030f85719e811ac0ad5c9219f0b`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-try.js

Blob: `d073bd6309f0fef39d3403a57fcbd395f505c83d`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-typeof.js

Blob: `c36d7e98d1e9a149f748ea9a93e1b2e35485d705`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-var.js

Blob: `9170ba7b68f8a240e186fc16784870d3b9daa6d7`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-void.js

Blob: `06c8087a0a2cb8a8626094948c4fe0d6f4a74228`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-while.js

Blob: `8b6398aa79e315fca56a22054bf4bfdc1895e526`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/ident-ref-with.js

Blob: `5ea4ddf4c0c9c81593fe86757cb254dc20e4ace3`. Role: test-path,source. Parse: failed.

Failure: Unexpected token =


### js/src/tests/test262/language/keywords/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/7.3-15.js

Blob: `5b06ddbd09657ff44f18982397ed8a04a8368098`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/7.3-5.js

Blob: `1ad7cc8ee3acdb0bae824775c58a501d7d1ba981`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/7.3-6.js

Blob: `611ba8f36aac7b5b62e18f8897650a45194a3843`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A2.1_T2.js

Blob: `e4f501f8448c66e5ee1df523aa8b7399374d90a7`. Role: test-path,source. Parse: failed.

Failure: Unterminated string constant


### js/src/tests/test262/language/line-terminators/S7.3_A2.2_T2.js

Blob: `374a289ab00261fb0c67eaffa10a2b2397138981`. Role: test-path,source. Parse: failed.

Failure: Unterminated string constant


### js/src/tests/test262/language/line-terminators/S7.3_A3.2_T1.js

Blob: `ccd9d06b5a40d174ca6e4059cef11ee4b19d65cb`. Role: test-path,source. Parse: failed.

Failure: Unexpected token ??


### js/src/tests/test262/language/line-terminators/S7.3_A5.4.js

Blob: `2f574d8121ee0e234706d4a30e4a107e7b510e69`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A6_T1.js

Blob: `209ba8d956177dd7affe81cb6336b88c554a0723`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/line-terminators/S7.3_A6_T2.js

Blob: `221e2b173eb77f8205d65909ffe817b4c9093bba`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/line-terminators/S7.3_A6_T3.js

Blob: `1e88e4421dfd72804bb113428d80f8e4636cc26c`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/line-terminators/S7.3_A6_T4.js

Blob: `d82e67e0971e1ba4606dc546150f157ec71fb4ab`. Role: test-path,source. Parse: failed.

Failure: Invalid Unicode escape


### js/src/tests/test262/language/line-terminators/S7.3_A7_T1.js

Blob: `e1c4dee545929f54ca3511cfc65b2b7b9211fef2`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T2.js

Blob: `a78d79085af87cef0e554b39d2fd686b59dab9b0`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T3.js

Blob: `63127757cfba1cbcf21a12f54e79d5346737f43b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T4.js

Blob: `6478bc5b436942356454f9201635c448088a0d58`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T5.js

Blob: `90edced9ee4e1d285bffd2d432da2aee0e485724`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T6.js

Blob: `c6a75ab0b195b55175e3c6dac5c7b8e13185097b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T7.js

Blob: `a73dc1b91c109e65e53a4f7052c4e625be8f8e2f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/S7.3_A7_T8.js

Blob: `81f783b0e8c7683d60f1534535113127c5b6f58b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/between-tokens-cr.js

Blob: `01afeede79116f71ecaefde68192609f0ce085fd`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/between-tokens-lf.js

Blob: `f852b834ed196a3f6c0179564a264124041607f6`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/between-tokens-ls.js

Blob: `798314aabf2d510a9522f973e5c2896d4bd1af9d`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/between-tokens-ps.js

Blob: `399eb10453ab9dfafbafbcde13e3da69b93f0bdd`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-multi-cr.js

Blob: `7b0bab357712bf2de67b3c1d420ed588fad38066`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-multi-lf.js

Blob: `cb5d1eb16e2345ec2c022b22267d7d1bfa0eb7c3`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-multi-ls.js

Blob: `d504c1396cacefb77bed4441c6487ce6a5c4af6e`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-multi-ps.js

Blob: `4718cb6031bda1fd3f493b263f31965d5180fb9a`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-single-cr.js

Blob: `e4a2d11bfff45d9bcd6b8b7b3a13b394e23ab750`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-single-lf.js

Blob: `3b1f71bfe05b7fe1d46d326ee69e86641e993f5b`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-single-ls.js

Blob: `9c9dabc25444e9e09448aebd6cbc3560f83503aa`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/comment-single-ps.js

Blob: `de3506c442f0f79b9eba2c98626012e11bc9bfac`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/line-terminators/invalid-comment-single-cr.js

Blob: `7a7f26f14e870e02dbfea0ee051215898a1630b1`. Role: test-path,source. Parse: failed.

Failure: Unexpected token text


### js/src/tests/test262/language/line-terminators/invalid-comment-single-lf.js

Blob: `a684d42eb5aafe3e177713c39cfe65a388d3d3d1`. Role: test-path,source. Parse: failed.

Failure: Unexpected token comment


### js/src/tests/test262/language/line-terminators/invalid-comment-single-ls.js

Blob: `766ed198e3acad0621d99fe5641b78eb52b0753c`. Role: test-path,source. Parse: failed.

Failure: Unexpected token ??


### js/src/tests/test262/language/line-terminators/invalid-comment-single-ps.js

Blob: `5846a73994e84838f00a36771b2560c85df2a018`. Role: test-path,source. Parse: failed.

Failure: Unexpected token ??


### js/src/tests/test262/language/line-terminators/invalid-regexp-cr.js

Blob: `e70d92b080feafa0e50af89164e39deef256c487`. Role: test-path,source. Parse: failed.

Failure: Unterminated regular expression


### js/src/tests/test262/language/line-terminators/invalid-regexp-lf.js

Blob: `db792c701f72a69e18b27b9e3ab82382971d18ad`. Role: test-path,source. Parse: failed.

Failure: Unterminated regular expression


### js/src/tests/test262/language/line-terminators/invalid-regexp-ls.js

Blob: `b50836ce1f2b785fca8f5c274544a39151d514c0`. Role: test-path,source. Parse: failed.

Failure: Unterminated regular expression


### js/src/tests/test262/language/line-terminators/invalid-regexp-ps.js

Blob: `870b902c2f2ecdf32a9737b9cac72af1b1d2e01d`. Role: test-path,source. Parse: failed.

Failure: Unterminated regular expression


### js/src/tests/test262/language/line-terminators/invalid-string-cr.js

Blob: `ff869d45dd991a9cd2453b87be44091a8aba8747`. Role: test-path,source. Parse: failed.

Failure: Unterminated string constant


### js/src/tests/test262/language/line-terminators/invalid-string-lf.js

Blob: `f8ef9e43f884fa692221300d8e0317768681ff81`. Role: test-path,source. Parse: failed.

Failure: Unterminated string constant


### js/src/tests/test262/language/line-terminators/shell.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/binary-invalid-digit.js

Blob: `475bdde372bf7d6e95bfdfc73c66099664f6832b`. Role: test-path,source. Parse: failed.

Failure: Expected number in radix 2


### js/src/tests/test262/language/literals/bigint/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/exponent-part.js

Blob: `f5e945b0c71bc302413776850c2b73b694067285`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/hexadecimal-invalid-digit.js

Blob: `52510868743cffb4733273367855760c1fef982e`. Role: test-path,source. Parse: failed.

Failure: Expected number in radix 16


### js/src/tests/test262/language/literals/bigint/legacy-octal-like-invalid-00n.js

Blob: `b59313113bc25ee1fbd6c6128919d08cd99a69f6`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/legacy-octal-like-invalid-01n.js

Blob: `7a47db58565501bee0c467399cbc84b1c44e4297`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/legacy-octal-like-invalid-07n.js

Blob: `aa36be30d36275e4b1f731f1be0d15d6d9a360ba`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/mv-is-not-integer-dil-dot-dds.js

Blob: `0531675bafaafd71c1a2f6363958dc947bc98aee`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/mv-is-not-integer-dot-dds.js

Blob: `c276b4249cebf2c393ed7a55fbcefec24c332061`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/non-octal-like-invalid-0008n.js

Blob: `a624cc5abb49bcb3f001484fd83dd780624f6614`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/non-octal-like-invalid-012348n.js

Blob: `c98d65cfc0e5643635e1223768286ae02190a4b7`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/non-octal-like-invalid-08n.js

Blob: `edea3cc0d69b0c166fbd61d0415a71cc9a2daf42`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/non-octal-like-invalid-09n.js

Blob: `ab537a83ea4f5caea2ad45aeda6f524728fd84bd`. Role: test-path,source. Parse: failed.

Failure: Identifier directly after number


### js/src/tests/test262/language/literals/bigint/numeric-separators/browser.js

Blob: `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-bd-nsl-bd-err.js

Blob: `350b8cec107ca3045d9ffe7a43cf82f14d636109`. Role: test-path,source. Parse: failed.

Failure: Numeric separator is not allowed at the first of digits


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-bd-nsl-bd.js

Blob: `b0b51ccfca764852065818002f502a1b87f7228f`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-bd-nsl-bds.js

Blob: `1419a21c55999285281d054759239a62905b3964`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-bds-nsl-bd.js

Blob: `9169b37d4bbdfe29b9c42f7ee98296efc9a249a4`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-bds-nsl-bds.js

Blob: `810de95606b7315d6791bd0a31d02907d7acb74c`. Role: test-path,source. Parse: module.


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-nsl-bd-dunder-err.js

Blob: `f7b39f745e7ec6b2cce40a5c3b16bacdf261be89`. Role: test-path,source. Parse: failed.

Failure: Numeric separator must be exactly one underscore


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-bil-nsl-bd-err.js

Blob: `b1e010bee2d4bbafe0a95949531bd53e492eba5e`. Role: test-path,source. Parse: failed.

Failure: Numeric separator is not allowed at the last of digits


### js/src/tests/test262/language/literals/bigint/numeric-separators/numeric-separator-literal-dd-nsl-dd-one-of.js

Blob: `722fc928e41a451359ce8dbb1c5d4e6b4fc9f63c`. Role: test-path,source. Parse: module.


## Validation and limits

Every successful file was parsed as a module or script with locations. Module parsing is attempted first. Preprocessing, unsupported syntax, and intentionally invalid fixtures can prevent parsing. Embedded scripts in markup and TypeScript are not parsed in this pass. Read the implementation and actual callers before relying on a inferred function name. No source was executed. No product tests ran for this map.

## Retrieval correction

This copy preserves the source map in [2b94dc26-013d-4b7e-b66c-13466d91c4ec.md](2b94dc26-013d-4b7e-b66c-13466d91c4ec.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `1bfb612ddceb74a0a0149d6553cc6789cb8daf591a2dc76be3e127237fd8a1aa`.
