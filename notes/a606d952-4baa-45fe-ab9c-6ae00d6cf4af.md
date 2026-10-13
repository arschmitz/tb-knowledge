<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["b46271430e1426b6a9e42bd4d965e52edd3b09e61c141a67c876447588ebff5c"],"sourceAt":"2026-10-13T04:14:46.642314+00:00","correctionOf":"notes/0aed5687-0522-4300-9dcb-9c462e2da5bb.md"}} -->
# firefox/js structural source map 298

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-fn-name-arrow.js` | `29069b8512ae6ea71e63b162541267e6df505179` | 1502 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-fn-name-class.js` | `ad463414360789d9781a6ea3880f59cf2a3fe267` | 1639 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-fn-name-cover.js` | `976a55fd0d989bf7159ef5a782a556e78d8c3f25` | 1615 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-fn-name-fn.js` | `c3f876d535fadf7cd1dd220d1eb381bdf0d40111` | 1561 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-fn-name-gen.js` | `082991adf523ff5a60c76666fe36b17dcadd3d32` | 1593 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-hole.js` | `5ce49a08c2e726df9beb62f697d60e458bc02cb3` | 1367 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-skipped.js` | `93635563836eaddf1c3fb29b57de9d1095cd3ab3` | 1527 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@31; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-throws.js` | `4e1e78a6d1c2a39e4932847800f589f77ea923d5` | 1191 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-undef.js` | `f5a99edcba87a25e22f24ff28e9c25e4f66144ce` | 1373 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-init-unresolvable.js` | `75a446295c98fd3d3002992ee7c9114e04954354` | 1371 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-complete.js` | `26a57379c7f5a26fa1ac7d4fdc6d34b3ba12e3dc` | 1521 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-done.js` | `2ea2da95af6a707e82d7ff055641b4a6b74fa35e` | 1274 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-step-err.js` | `26a2d14faaa7b45687ddad698cd13458f6ad514b` | 1317 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@32

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-val-array-prototype.js` | `73d25c1705a33dee43290119fcb6ab5d14bfd4d6` | 2032 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@61

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-val-err.js` | `b02564fff17478a8904e689409517738ed1d17de` | 1681 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@36; function@43

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-id-iter-val.js` | `6697962b062b69a93031fc2d42382bc5919036e0` | 1760 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-id-init.js` | `ea0eef697a8c0f07feb9e1788a2b9251fffa8721` | 1525 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-id.js` | `7ff4b3d0669f2c2f3f10823cbded689f1d10bbd5` | 1547 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-prop-id-init.js` | `1e4325e2dbb0a9cce89a28f0dddef8c112916b55` | 1720 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-prop-id.js` | `e2010ffac4ef7885fa007befa6edba91bec4929c` | 1745 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-val-null.js` | `9d1a82fc2a5e6409c049344be9e7e0b4b8f8206f` | 1358 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elem-obj-val-undef.js` | `d580f6a0811d7f1e2955a448ee6a8eca85ff98b5` | 1365 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elision-exhausted.js` | `cd6b7abcabb55cf4694e3ac32c76bb714de909eb` | 1391 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@48

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elision-step-err.js` | `c474cf744f20b92753837ecfabacd01438e19179` | 1560 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-elision.js` | `3c4cb4a8c0dd751a3802c2a09e5079f84362cebb` | 1704 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@42; f@57

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-empty.js` | `023be481b49eea2dd693c9cc8cc1c7f022d62248` | 1152 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-ary-elem.js` | `e13b0cfc47b4a45db92e9cae1641e8fd926c3253` | 2139 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@64

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-ary-elision.js` | `294b44e6699d83c9084f7e6bbc4df6e434ef3377` | 2108 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@55; f@70

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-ary-empty.js` | `63ef39c6507a4a60e3ca01aa6f54e666be7d9208` | 1539 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-ary-rest.js` | `9176882e76c80662c9ea44ae0f93b7dd057c3d7c` | 1490 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-direct.js` | `7bcc2d0d539b80302345284727c57d6336f87cae` | 1278 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-elision-next-err.js` | `9a11688bb77b4534de1c2e03eccc8715703a7853` | 1373 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-elision.js` | `9849f08ca24f41362fe9f8f0d4023961da377be1` | 1617 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-exhausted.js` | `0f5e4b5117eff5b91855502a42bd6e255c611abe` | 1456 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-iter-step-err.js` | `2045ded696cc7b0d23a08a0782bd943b739826f0` | 1601 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id-iter-val-err.js` | `8a82af99836908cd61ab80fb14b7d9744412df82` | 1552 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@31; function@38

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-id.js` | `4f05e3a47cb4864a8f34cacc835d9c98af1464bc` | 1338 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-init-ary.js` | `7a760e18fe46b38a0a55750a07598fd6622ba973` | 1249 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-init-id.js` | `98ed74335e0cd2945c88209cc9e3cfc00017133f` | 1234 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-init-obj.js` | `f94136a18a6617252bdd30975968f9ce78909785` | 1250 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-not-final-ary.js` | `d72f4adf315ba6b0b6e313907e2e11545630c437` | 1264 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-not-final-id.js` | `095c4664ac52d2b251c113f548193669a94955be` | 1250 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-not-final-obj.js` | `0841df9c51766c6df58117cc52468ea89f8cf2ef` | 1267 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-obj-id.js` | `c93cf6858f93c4048c0554d4f61e9024e127c3e2` | 1330 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/ary-ptrn-rest-obj-prop-id.js` | `a7d413e7ce9033a770ae0fe8a6e1ca423645677f` | 1577 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/browser.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-init-iter-close.js` | `2910c7d0ac350add56e5ed5c910f87b827a8ec2d` | 1446 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-init-iter-get-err-array-prototype.js` | `26002b049d749b93eae7f08a92ecc82cb5bfda17` | 1252 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-init-iter-get-err.js` | `7417c77482a9f4003238b5a3e8468972ac5ebae1` | 1087 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-init-iter-no-close.js` | `833b9ce4985202bf0deb227e00197bd95ba142aa` | 1448 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-name-iter-val.js` | `a3fb0f3f8d8d4ad6d2ce27650cd5173d3ab62717` | 1762 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-elem-init.js` | `9fbd8e825d2fa0716838f080bc6be135caac684a` | 1535 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-elem-iter.js` | `c87c1468e7370fecbd13a01ca1cbcc3638466fc3` | 1506 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-elision-init.js` | `e054192528f9aee53cbdca5fd6defe4baa0fad99` | 1610 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-elision-iter.js` | `b4f6260d6ba8a5ee6bb918ebb1ea7207ee552269` | 1515 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-empty-init.js` | `b7975f6bb169238434ee832bf69f62bc362a43ff` | 1652 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-empty-iter.js` | `0a81ca4b2b89b51fc6da433a94cfaeede3cdd691` | 1493 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-rest-init.js` | `249d5d653b12b2017e11afd22718fc2df9b7fd68` | 1657 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-rest-iter.js` | `4830799cded08942aa0000df74f0fe7b96a3e135` | 1704 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-ary-val-null.js` | `352174e9de001c58ad89c174bcc8084796ea0f1b` | 1374 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-exhausted.js` | `f31c183bc39cdfa7bb8763a74ecdb0ddecad3165` | 1462 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-fn-name-arrow.js` | `2f076685d6ab404788a2d52b2fe77763615f6679` | 1530 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-fn-name-class.js` | `2dabdf4fdd155b431c582106e4748e165e45fee8` | 1667 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-fn-name-cover.js` | `9f18d946c0f920a6811237bc367ceb7fe13d598d` | 1643 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-fn-name-fn.js` | `e4a6dcf9f54a00b6b1acc5607abd706eb5560571` | 1589 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-fn-name-gen.js` | `39bae4bba05f0fcea05f9c3d79e458dfaba1741d` | 1621 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-hole.js` | `5bfaec83aa4e5875845b451aecfc4210419909f3` | 1395 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-skipped.js` | `b59d4d5ba8b836a1737b4a2ed74da6b0e2833551` | 1555 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@31; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-throws.js` | `5beda66084797faf4592769575e332333a65a0eb` | 1216 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-undef.js` | `e96638c87407f0582ab31dd8eec9292e880f3258` | 1401 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-init-unresolvable.js` | `fd29d3b01b68137545d197471ac1d8b789aa85f0` | 1396 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-complete.js` | `ea8476aff7375ab583b0c96b3defb81171ec5c2f` | 1549 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-done.js` | `0395e46437dd79c1fd0155d79f8be70c0f0f9d1e` | 1302 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-step-err.js` | `917f389418a676b2a2969fce0ca386feff680601` | 1342 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@32

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-val-array-prototype.js` | `c108a49d6ad7edbf28aa0c3ef9644953022341b1` | 2060 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@61

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-val-err.js` | `cf7f43d6424e652ff9d8af6a795144507c72203f` | 1706 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@36; function@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-id-iter-val.js` | `7547df96783d6960c559989872f8fda604bae692` | 1788 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-id-init.js` | `2a7e7c918cc0335c0a0f80b3c3b4fef617e88d91` | 1553 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-id.js` | `9d701d0cb9d69725b89170995a6d9e38452ac5ac` | 1575 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-prop-id-init.js` | `39aaac977fa5349895e36b2377c7ea2c22902e9f` | 1748 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-prop-id.js` | `8b50023295dcbbae31e4f2e9d678697f6d4ea743` | 1773 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-val-null.js` | `d92839c0af01f24b4f7cc5ee4b467d7a6653e2ee` | 1383 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elem-obj-val-undef.js` | `23f9e50f427a46f4e9ab08ee7b4f9eae4a9872ad` | 1390 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elision-exhausted.js` | `23d7f11e35a76a4be293a54bad7c3ee095d7db3c` | 1419 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@48

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elision-step-err.js` | `91af3f4a52ecc0db6716d12119a1cf2d7300d68c` | 1585 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-elision.js` | `e3030c6fff9d6d680d3b8bb337649674a39d38dd` | 1732 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@42; f@57

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-empty.js` | `c13d5103a564f3917b490b4179725508a6fe59ae` | 1180 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-ary-elem.js` | `fe32d9fec03032489601f5e8623075862f497d01` | 2167 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@64

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-ary-elision.js` | `c8fc278a84a24e6bbaa290d22037b2960049a6c1` | 2136 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@55; f@70

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-ary-empty.js` | `fb0cd8652104a64f86959f25810f14cf10f8b407` | 1567 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-ary-rest.js` | `0d5caadf4914eab37e7cb4a9a63c8ede4991923a` | 1518 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-direct.js` | `5eae1b6f9fd67f2d090d5eeaec2c3902219f8331` | 1306 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-elision-next-err.js` | `aef4362e8b9d79a840e160cb424876165791acd0` | 1398 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-elision.js` | `5c540ce210400de77c6f66e4568c83c4026d3733` | 1645 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-exhausted.js` | `b5ed8bba9461fc7ebd24d2c00ba954fed7428972` | 1484 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-iter-step-err.js` | `7ca7b599e0ca8c7a5f286ab333fe46ac9cf7b8f3` | 1626 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id-iter-val-err.js` | `2ddd428cc7e52fa4022aae59ddf1a984ea2e4b82` | 1577 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@31; function@38

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-id.js` | `6c7eba313639bf001427568b3a508d60e8c485ef` | 1366 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-init-ary.js` | `315022bdb154c69976ad35b4362a5b2f90be9c65` | 1277 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-init-id.js` | `629a101ae84a8b310787bfdad3ba65614ba5cf14` | 1262 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-init-obj.js` | `e8a3d000573619545cffb378987ac0be84793376` | 1278 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-not-final-ary.js` | `1aa8204c801341a399d6f4ce8f1167af8dc0eaff` | 1292 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-not-final-id.js` | `53775afec8ec175663b61bdb3dbdee69fbcff1ab` | 1278 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-not-final-obj.js` | `126f67faf2f4b70d5ab8cd120d30cf0e96f98ffa` | 1295 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-obj-id.js` | `78bb3714dffdb869745a7f4ebdd491b460103ccd` | 1358 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-ary-ptrn-rest-obj-prop-id.js` | `627eb415fd6d5d68b7394f4cddeb07ea5ef7c47a` | 1605 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-init-null.js` | `7dd2ae91892ebbf45d4fdec29f0a7d4d2c6d297c` | 950 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-init-undefined.js` | `1a77f81f97a45e36b9f6428dc69475ec0b48b7b2` | 965 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-empty.js` | `e8bb916fdcc9c2eb38ad20b2ddf0cc77a846d834` | 1206 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@28; f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-get-value-err.js` | `90acbe9178d3e299f6ccbee62513b5f151d17a67` | 1189 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-fn-name-arrow.js` | `2dfd5f0955871f556d7d0d3726e40e496d486ad3` | 1475 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-fn-name-class.js` | `0876058218d38a5847e913c437ae0788ae7ce33e` | 1614 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-fn-name-cover.js` | `6336e2f23f4241cef760a16e9b6f4ce08643f2c4` | 1589 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-fn-name-fn.js` | `aca89b9fa198712a90a80c96fe88b3b5c1d7c887` | 1536 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-fn-name-gen.js` | `6cb51241753772cf1dc5f79195d4666f6df46380` | 1568 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-skipped.js` | `b7eb41b4960105307c7068bacc639752e007eaa7` | 1461 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@30; f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-throws.js` | `125e900d7cfcbb7617efb9f00d4f98083536988e` | 1208 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-init-unresolvable.js` | `1157b327831521e90671f3b680c998288453904f` | 1388 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-id-trailing-comma.js` | `b716aa978dab95fe7790cc041ec38601c7046230` | 1148 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-list-err.js` | `4a78e90510d16718467e5c71c61347e3404bf2ed` | 1266 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@27

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-ary-init.js` | `713379e1a373489e8999a79097d2883b53b1112f` | 1514 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-ary-trailing-comma.js` | `c9f6024c2768ffea12b6be9e5b7af1a4ef79ffa3` | 1160 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-ary-value-null.js` | `f264a3207f14f9db6d467bde316dfe08c019d524` | 1158 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-ary.js` | `26ccfa962ea591d68691a86fcfe00d9b5b46033d` | 1423 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-eval-err.js` | `3833f987959ae3c326168b018502f9c66a0acad0` | 1081 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@25

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-get-value-err.js` | `fa06bd0ff58f6c6dc98b5f0c8ada27da864c5b95` | 1259 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-init-skipped.js` | `a365c90c9ee4b2673cbf9b4750d04cac9f7a941f` | 1692 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@29; f@58

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-init-throws.js` | `b1b612b3dca68e2ba985a2c2a029823e99475ffa` | 1209 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-init-unresolvable.js` | `690abe4d1fc6287da0490b6544dbd755f5c0bf60` | 1390 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-init.js` | `9a48e10248381ac01805b77fda73deb93cf8f339` | 1222 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id-trailing-comma.js` | `e4f05cae8477ede0426a1e66b35979d19477e063` | 1215 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-id.js` | `2849bf8730a85ca5252ba3f6139911cebdd03705` | 1204 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-obj-init.js` | `e21ac340814d5d53b56cf1bb4f0f7e95c4fdeec0` | 1542 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-obj-value-null.js` | `fb94ec3a2af5778bc3ec0141e37772347bbef8a5` | 1172 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-obj-value-undef.js` | `c34e69dd2df9e211d7f0c2456cede3ab952a1486` | 1154 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-prop-obj.js` | `631967b3304870d11803dad1a056fc5da2e1ec84` | 1443 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-rest-getter.js` | `a997f2e2e0e3b50bebf599885b108022600dc2eb` | 1179 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-rest-skip-non-enumerable.js` | `da16d35feb6aa3abb360b837a5fded441096c17f` | 1349 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/dflt-obj-ptrn-rest-val-obj.js` | `1a9fd733fa33e70b626a285e1c89bf40bb6679d9` | 1308 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-init-iter-close.js` | `e643fc2117707328ce1a8ee22345cdd5eb988a63` | 1452 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-init-iter-get-err-array-prototype.js` | `e61c4f9fb2b153f0bf03a2539bce874e1f71bd78` | 1261 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-init-iter-get-err.js` | `3b1ec476c74634e7e4704ca6b872a8eb84acc156` | 1096 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-init-iter-no-close.js` | `ea245d046b2a2c1326f99ec476aa1aaf5be9b39a` | 1454 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-name-iter-val.js` | `6d0148d7c8dbdaf55b73d1f1f3f6745bf31262f5` | 1768 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-elem-init.js` | `7969a3eca15507c32286abcfe6137d36f6233fc6` | 1541 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-elem-iter.js` | `3c579872908abb4162e35c7b03138672aee6d0f1` | 1512 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-elision-init.js` | `7eee91f03b2f0e481def60649701ab56b1e41297` | 1616 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-elision-iter.js` | `f4e5703efc9966f4598c60c09195eba11006adbe` | 1521 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-empty-init.js` | `e2b6dd2eea11721b831c5cf9f8522c4a39744870` | 1658 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-empty-iter.js` | `1006dd8154b4ba761a416b68a34cb8e6d3a61f19` | 1499 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-rest-init.js` | `c60c89885d03f2617d8fa148c405634b48eb7039` | 1663 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-rest-iter.js` | `984a15e9fc25ca2ad6e67661a1de0bd75f354960` | 1710 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-ary-val-null.js` | `66409abe80ec1f46b96efc602e22d83f4ed2955e` | 1383 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-exhausted.js` | `8b5f2427823beb210d2177b23ab7445f82a3ad85` | 1468 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-fn-name-arrow.js` | `454e387c90b854ac18aa3cd0625e6b072405eebc` | 1536 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-fn-name-class.js` | `b1d642afd4ce9ddad2ff214f36fb5cb8e2d2765a` | 1673 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-fn-name-cover.js` | `5623c8ad3d5a5ed2586e30e59fbe1e1e2d061ab1` | 1649 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-fn-name-fn.js` | `775f3c884f400fdba18924a6818ec75d40b8ee4f` | 1595 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-fn-name-gen.js` | `54a90d2fda353c79eafb323c1632fb6bd5ab6f68` | 1627 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-hole.js` | `298b9d26a7dcc98d810dc81d70494e11a0bae3b1` | 1401 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-skipped.js` | `072a5db935d17bce2271650d6df45baa0c459130` | 1561 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@31; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-throws.js` | `6ca55f47f09b414f1d398af0205a636307030c64` | 1225 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-undef.js` | `0e3fc16ad73c375cc452ba278f5546c35e3e12d0` | 1407 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-init-unresolvable.js` | `b872cf898431b8bbe0078cc580fa1d300be54658` | 1405 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-complete.js` | `3eb02deb392093bb7437d7c5f814ddc369fe4a33` | 1555 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-done.js` | `901a1ca51ff5daf86d9be030743d24754fd7a0d8` | 1308 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-step-err.js` | `f40fab78f2aabecf1316e51e9355c41446b9ad5a` | 1351 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@32

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-val-array-prototype.js` | `c4fbfc407c7f8dd9501f1dd20a48feb67d0257d1` | 2066 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@61

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-val-err.js` | `14b3f231cf83ee9b93dd942d7a6dbb4b77e679b6` | 1715 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@36; function@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-id-iter-val.js` | `3c34d924acad4a96bcfa4270d521cc816a0db5e2` | 1794 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-id-init.js` | `7c411d6cb839b36d3bfa2cf9747ca59d71edace6` | 1559 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-id.js` | `253bef3b8e853a1666b9d6154dc1ff3acee7871d` | 1581 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-prop-id-init.js` | `3e4f8eb2d372cff91ebe65e9ad35790d388d13f7` | 1754 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-prop-id.js` | `6b94949151bf414415e1007b5d1ecd4e482a3656` | 1779 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-val-null.js` | `eeb42baac017591aa84093db6efa4d380bcaeb01` | 1392 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elem-obj-val-undef.js` | `6ecf1380f77a1767322c2686d34732d5b14f852a` | 1399 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elision-exhausted.js` | `b286785f7e70acac0d13c1b0373d35c68e06793c` | 1425 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@48

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elision-step-err.js` | `6436a3ff4516429286994a0ce4b7d6ce094da153` | 1594 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-elision.js` | `0a798b11136565d76a339e7ca9a6404bb92b9381` | 1738 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@42; f@57

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-empty.js` | `b064054dea3bd2e1002e19785a0622e086b560f8` | 1186 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-ary-elem.js` | `4c9774e6031d3f54591ae085c6b1fbdbb0224c42` | 2173 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@64

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-ary-elision.js` | `654351cfce4124746871ad0748756058031f77a4` | 2142 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@55; f@70

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-ary-empty.js` | `632010b46c2e9bc613c3dfa9434e84e1113ac60d` | 1573 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-ary-rest.js` | `cfb6f46f72d5e115ef797e820f9942098e7e3fd9` | 1524 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-direct.js` | `701fa07dc9f5e82ffdaad85ed6a8ae93499753c4` | 1312 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-elision-next-err.js` | `e9d1335f5af18c0092604cbbe5bb2f8db1fed6c8` | 1407 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-elision.js` | `93215c250927a4bb28653f42548687430583a8f2` | 1651 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-exhausted.js` | `93753206f823293a57113047f86223d0ae99c143` | 1490 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-iter-step-err.js` | `2375a3d3f27d396b6910271397c96fbae3d4f7a7` | 1635 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id-iter-val-err.js` | `21023db9be952d833378ccd631d453e412ffd888` | 1586 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@31; function@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-id.js` | `41a1db43d579406bbaa4e99a8a29c2aefbd3ecef` | 1372 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-init-ary.js` | `4e327b7d22a2d265269ea2b2338799083afda6de` | 1283 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-init-id.js` | `2ec762492c9c30ece79627ddf3d4f7aeb81123b9` | 1268 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-init-obj.js` | `fa7d8d369ac5252f3dae2103a59049c0b9ece53d` | 1284 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-not-final-ary.js` | `582a9482ad24a2a03ee337bc1eefbf04f3d88f0b` | 1298 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-not-final-id.js` | `6dcef40b7b2c3bcabb1ddf6d5ce505f0304a0374` | 1284 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-not-final-obj.js` | `c82783bab934a9ee95cac6f835e6e5ae280a002d` | 1301 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-obj-id.js` | `c9e59495606d4d8668c4611596b53642709d5ae8` | 1364 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-ary-ptrn-rest-obj-prop-id.js` | `eeaa2bb073b619372b0f743c44d25835f17b6619` | 1611 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-init-iter-close.js` | `97eed460a6278032df74aa0e8461fea7410dc679` | 1480 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-init-iter-get-err-array-prototype.js` | `b1c34faf7fbcc215117039ee1960741147d278cf` | 1289 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-init-iter-get-err.js` | `3d2e6d697d83bbe4704ed1078e9c21a7af1ac92a` | 1124 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-init-iter-no-close.js` | `1312d5b3fd3936a975dd0141602a2e2756e7c97a` | 1482 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@34; function@37; f@52

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-name-iter-val.js` | `327f9a1b71a6ccb4a68b38b35059b8ce8f83e588` | 1796 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-elem-init.js` | `1e9486554268346c64b3e2df8ecc66c5a2a7a92c` | 1569 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-elem-iter.js` | `31c99d280efa0b61f1662a80fbb3412116fbd192` | 1540 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-elision-init.js` | `f583d14e65dfdd5c4e7fc15113e80e394b714b96` | 1644 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-elision-iter.js` | `2ba8f9ff288bab777bcb46702b061efd2476a9e5` | 1549 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@35; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-empty-init.js` | `fee07a23e27562c93af6ec5555898e2003a3598e` | 1686 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-empty-iter.js` | `66fb1273977704ab5c361145a449f28ecccfa0aa` | 1527 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-rest-init.js` | `c9bb825ff7a438f965e3a388a79b1962b2ad3381` | 1691 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-rest-iter.js` | `bb52e4f49f3e20bc33739029cd02fb216846ffee` | 1738 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@50

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-ary-val-null.js` | `120c6e76bb825385e16ad26a931e761cd4a7de7d` | 1411 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-exhausted.js` | `adeaa103e966394186b4dd2552b1beb47ba85399` | 1496 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-fn-name-arrow.js` | `0ac4c493a11e983e8d305206ac3857da581e65b8` | 1564 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-fn-name-class.js` | `324602ee51027bfefd098f0b9d55349e1f9cd86f` | 1701 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-fn-name-cover.js` | `825c0113fe33ba2a4d0106205350e9a11f09b076` | 1677 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-fn-name-fn.js` | `f0aa5d20902367acb4b456266d16d7e015625bb1` | 1623 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-fn-name-gen.js` | `3ce1c5af160f6f74399bdb719877dd7e6c54cb09` | 1655 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-hole.js` | `23a7f9ffd5ae192b29c87717a643ee40b7738c0b` | 1429 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-skipped.js` | `6542568429bb2e5d0576d1be59df6f62d344a711` | 1589 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@31; f@47

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-throws.js` | `2bb0a406b6d39727bf73aca7a2483dc1ffdfd7ed` | 1253 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-undef.js` | `21afd82d2a8bb95ba9fda34137207ac999f2e4d9` | 1435 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-init-unresolvable.js` | `71aca3bb9771fc8f854eb86b7cc618974c2822d9` | 1433 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-complete.js` | `a97fe06963071b85389397771aea33550c7dedc5` | 1583 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-done.js` | `9bbabceafa9edba8e25d9d72d9ab1dedf252a473` | 1336 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-step-err.js` | `31842304c21f1a421b2e2d3c2d60475c08bb45c3` | 1379 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@32

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-val-array-prototype.js` | `6109699b86720c35b769faf8a2cd3c39ecd3803f` | 2094 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@61

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-val-err.js` | `3921b1ca21a34c743565d462308fa9109f2ff0f2` | 1743 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@36; function@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-id-iter-val.js` | `81c79b9e7f386a40b501a093e9fed40f9fd3cb9f` | 1822 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@51

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-id-init.js` | `0ea1e5cbad33d7fbbbf806125f6f02c1e0691456` | 1587 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-id.js` | `aaa1578190e6a61651bed014634a54228046711e` | 1609 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-prop-id-init.js` | `981296a5d9dd07cbd6567d51c63566f0aea9646b` | 1782 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-prop-id.js` | `25e1a68221da2a1c3f2fd6418c74ae1bbf45524f` | 1807 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-val-null.js` | `bfa0bbce60c0f39c33aa139ebba8b3030a725a22` | 1420 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elem-obj-val-undef.js` | `bc1448274308581d56559371c9ec62836ad76523` | 1427 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elision-exhausted.js` | `74f6dfb70e0563be99ddbd4b65177805b6f9fc75` | 1453 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@48

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elision-step-err.js` | `69240fea46518dfc249ca574577a42937fef82dc` | 1622 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-elision.js` | `1d36274ae7aca0fe09ce66af3731f7936cb8bfb5` | 1766 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@42; f@57

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-empty.js` | `7aa5bec2a604b574f68c287f8b4f4fb5f429948c` | 1214 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-ary-elem.js` | `5c7ae5a707341cbaacef46f80df1cc704126e3bb` | 2201 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@64

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-ary-elision.js` | `6c0da079894cbe1ec2521d959a54c76247f71472` | 2170 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@55; f@70

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-ary-empty.js` | `bf3545990bab16064fcaa079bbbfadf8c5d9fb84` | 1601 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@53

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-ary-rest.js` | `b589d8103233b81fadc9574f72497656ea865f45` | 1552 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-direct.js` | `75851e9fe4ffd1c86ab87fcdb2338ec6f350589a` | 1340 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-elision-next-err.js` | `5ed81cbb240b60ee092af4fd0f8fbfcab946fe0f` | 1435 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-elision.js` | `5a2b9ab978cf467d1a2282fc1c060e35ee2323fe` | 1679 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-exhausted.js` | `fb028857bb093368621d485be939e69f0fcad6e3` | 1518 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-iter-step-err.js` | `b3e198190c84ee86f3efe62a45f948900e33ffe2` | 1663 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id-iter-val-err.js` | `43f6f6a8bf9e6dc95816c9ab9d8e94b4abe5a4b2` | 1614 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@31; function@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-id.js` | `97d632498723100f49087cefb9c77748c314dfb7` | 1400 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-init-ary.js` | `23d0961319b5fcd6d6c0395971a645717462b0ba` | 1311 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-init-id.js` | `cf38d6066a09b383feffe3fe6b9b21aaa25d449b` | 1296 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-init-obj.js` | `beb9a382fc3d9ef0c4f95b63e8d396c176b0ff1c` | 1312 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-not-final-ary.js` | `a718a00735794a1d34ae8ef5c1ba107f7ae7ef36` | 1326 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-not-final-id.js` | `e16a19ebefe063d9692cb6e32b75f90749e6d8b4` | 1312 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-not-final-obj.js` | `bce88cfda88234e649ce3c479b84563f182ca377` | 1329 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-obj-id.js` | `7dab2288088bf650ef73f949b124a62001276686` | 1392 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-ary-ptrn-rest-obj-prop-id.js` | `cf048a14be2a23861641471f3b318bcaa51f0950` | 1639 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@49

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-init-null.js` | `bbd8e92f7f44194d00957e03bfadebdeb2d37439` | 987 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-init-undefined.js` | `ab1837b70319249bcde7b7028533d85f5c43f54b` | 1002 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-empty.js` | `4203ec53109c2cf5d51ef9ef5ba9da40c5ef664e` | 1240 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@28; f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-get-value-err.js` | `fedfbe2c1383d7b48a0ed340394d4b43a0d70210` | 1226 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-fn-name-arrow.js` | `4f73b0c6b4521478361a5b5cc709157d81e9ec60` | 1509 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-fn-name-class.js` | `d414404cd69a98cce58231598c68cdae606312a3` | 1648 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-fn-name-cover.js` | `d78ddc2e04a8aca6f7d8d8ef7de54690c70fe847` | 1623 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-fn-name-fn.js` | `26d4ecf6aaacd4d670c3c8e4c1eb12a6cb128d48` | 1570 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-fn-name-gen.js` | `f96d35b7374c6e01e387f4cdba196c7250145654` | 1602 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-skipped.js` | `f64179e60279ca85126c718bd75a518ce5a4ddc4` | 1495 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@30; f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-throws.js` | `fcefde9ed89262ef95516cfd49f0d613c7c8fc82` | 1245 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-init-unresolvable.js` | `49b35989f697c4c58298f6c7017897f0fac01220` | 1425 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-id-trailing-comma.js` | `a52a41e217b6567970713efb8bbc7694c3c87ad8` | 1182 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-list-err.js` | `dbc65e4f9dd129e85d0d7e5837ca789f0230c38f` | 1303 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-ary-init.js` | `6d8179c8e4a6178c95421246485421c09464dcbe` | 1548 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-ary-trailing-comma.js` | `02fd64f2b97dcdebf76e5a84b8db120974fc65da` | 1194 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-ary-value-null.js` | `b3bafbf16e89cce0b4d1dfdaa15a5b94a17d6f5a` | 1195 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-ary.js` | `91e70485c32e8daa6c402de5bc94aefb7eb5e242` | 1457 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-eval-err.js` | `28d659c6fe37c1c848dc36fe556bcffbbf226601` | 1118 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@25

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-get-value-err.js` | `3111195b046f6fb261189250a0f962a79aad83e7` | 1296 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-init-skipped.js` | `b5a09de042068a053f95976ad6d29d939b282cc0` | 1726 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@29; f@58

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-init-throws.js` | `7320fb73bc44eeaa24aa21c62e3ca64c6680e4c7` | 1246 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-init-unresolvable.js` | `aee05d469c0ed44e319130f576eeef1d9ccce6a4` | 1427 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-init.js` | `c4f79f4ee82900342b99c5625b975fde164e1979` | 1256 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id-trailing-comma.js` | `d331e19fe622fef1b94b73854327a5ee8f88a310` | 1249 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-id.js` | `d390aaf442386e6fe0dc62a490e83503e60d2659` | 1238 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-obj-init.js` | `02cb6a3f59ee1cf5e9a9b7c369618090a50de812` | 1576 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-obj-value-null.js` | `b63dc5ff74896dbabce9766f4e30bbcfa0c70553` | 1209 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-obj-value-undef.js` | `5fb1a5326db2ec508b4074391105f8a5438ac499` | 1191 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-prop-obj.js` | `d7f909c240fed8e7129f937da5e562fde4f029c8` | 1477 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-rest-getter.js` | `835028c92755fa7a8aa32fe7d8bed7ac74b2728e` | 1213 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-rest-skip-non-enumerable.js` | `436ad98c52d270f6494bb7292417e53932cb126d` | 1383 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-dflt-obj-ptrn-rest-val-obj.js` | `8e3b2d68d920d037575c47c14bbff5a44df9a1f8` | 1342 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-init-null.js` | `b6064a769c990a7e581e1da3f1e454e3f8212306` | 959 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-init-undefined.js` | `04aa4f1ad31a8b537b9ffb62b01e682a69db08e5` | 974 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-empty.js` | `272465447bd6e1baa24c32f662426630a1145112` | 1212 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@28; f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-get-value-err.js` | `2ce4f8cb03a26b7f84c98c4fb96a1dc90b191554` | 1198 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-fn-name-arrow.js` | `c1b3726490b594f740d73a34b0ff4d6a91fe7859` | 1481 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-fn-name-class.js` | `46bd7d576e56c4a2356cb53485a242f188cff3a5` | 1620 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-fn-name-cover.js` | `d5a02c3d37848868dbbbb227eca9dc67ed1ca570` | 1595 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-fn-name-fn.js` | `5f4250b5c52d0cbc533e14c4ee02a70434c7a988` | 1542 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-fn-name-gen.js` | `af3ec9ce672188ed54706d405ca7d1075479d353` | 1574 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-skipped.js` | `47c7d43e89c39666811aa2c747ac97c86b42cd7f` | 1467 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@30; f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-throws.js` | `c0ca107850cc85716a41b7af5dc9ec2c0d0f6e6e` | 1217 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-init-unresolvable.js` | `e5744abc216070c5e1aaa9320e9a9f10e95c92a0` | 1397 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-id-trailing-comma.js` | `44d8dec12d0d24aa42c5a9a19e5f349e602e768c` | 1154 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-list-err.js` | `dce2e24d1f240dab929de2c108717a1e427e8731` | 1275 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-ary-init.js` | `3d70802764a205ebeb62b65c07a52d14ba2206cd` | 1520 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-ary-trailing-comma.js` | `5404707935bac8e14a124292221ddd5aed4ca38f` | 1166 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-ary-value-null.js` | `1e62e078ffede214d222776496a4c40eac14a9ef` | 1167 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-ary.js` | `690381f4ddba93f7b5c458aa2a9d7fb40d98f996` | 1429 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-eval-err.js` | `67697b9b61fe3c305b1cd9c4d1b81551617b4664` | 1090 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@25

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-get-value-err.js` | `8dc3082a20fedff44a490ff388180a03f0f07486` | 1268 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-init-skipped.js` | `4ecda5b046f9795de649179b578fd0a70f9079dd` | 1698 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@29; f@58

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-init-throws.js` | `b5a8e64958d5971339543f331bbdbbe94bcb487e` | 1218 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-init-unresolvable.js` | `933524d160174f15f37088cdb5077dd2a1a930f0` | 1399 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-init.js` | `330c9c31e01f1185fd7cf427059dd41789a1f9ef` | 1228 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id-trailing-comma.js` | `180b8ad3ffc77a6c856df7176dfe09f063e2de1d` | 1221 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-id.js` | `55a3888db7b783f348b41b6a6ff3e0544284215e` | 1210 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-obj-init.js` | `a45c18df19ffb116c679f90d12bfac4c423fe8f7` | 1548 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-obj-value-null.js` | `0659e717ab2eaed305d14b5945ccb9d77b921723` | 1181 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-obj-value-undef.js` | `dc7f82ff9c13cdbb4a6ccacbca9c766200da19aa` | 1163 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-prop-obj.js` | `306dab2a3502dd1528f5abf9a31884a649588c40` | 1449 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-rest-getter.js` | `b70ccb3c622df12f9f6093b3a015b85272bf675e` | 1185 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-rest-skip-non-enumerable.js` | `c605036f44a687c3c0da042f86306adbf7813e0c` | 1355 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/named-obj-ptrn-rest-val-obj.js` | `588fc7aa2e6d064423ecd4c5c7a79ffc2be6c9a0` | 1314 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-init-null.js` | `5ee8a4d5059ce1b292aaf1b206401ed46012f484` | 925 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-init-undefined.js` | `68a135e842211592c24e39c622c76e5b17b63045` | 940 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-empty.js` | `77f185ecff8670bf41625025905a8d7c29e68465` | 1178 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@28; f@41

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-get-value-err.js` | `d258e6ba13f1a5b9ed19659bbab39d440d13b12a` | 1164 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-fn-name-arrow.js` | `7fef7c2cfa51401653c35d863f17816ad3e3d5ea` | 1447 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@42

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-fn-name-class.js` | `58527f2ae22cc351a639ec06287aa6d6b94f76cd` | 1586 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-fn-name-cover.js` | `b0f0cfc3c3ca9a5c6d9feef1119ab4e2170ca573` | 1561 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-fn-name-fn.js` | `32dcb5b8af78642488c798e69b0f43bbcfcab36b` | 1508 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-fn-name-gen.js` | `af444cc6b4c3f7351a5f76d134ca60cb1b6ecf4a` | 1540 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@44

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-skipped.js` | `3c3c36ac3c5fa99bb2de8af10789e799369cc3d5` | 1433 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@30; f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-throws.js` | `21e1b974c236d44b82429d6b15fe572bf05c5487` | 1183 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-init-unresolvable.js` | `588d2be359bd40959905dd3fefdbbf8f1c3c9ce2` | 1363 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-id-trailing-comma.js` | `2b7e794cf6c27f96ef6619fe58fede87cf437016` | 1120 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-list-err.js` | `c8f8712f506da036e6d8bfd27ba3ee3c7b9cdf97` | 1241 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@27

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-ary-init.js` | `57b8569b9f1fa97b48690eb448d4b1a3f3b5e376` | 1486 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-ary-trailing-comma.js` | `4f12609b64918112bd4e91a4563a04819b70e94d` | 1132 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@36

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-ary-value-null.js` | `43054ce5d6b9c378d01991c0d813fff4b2b359c2` | 1133 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-ary.js` | `5716990e0c63dfa17a29df656d09407dd703e4ca` | 1395 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-eval-err.js` | `0f52b003a3e757ef9689401c44fcf7386a9692c7` | 1056 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@25

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-get-value-err.js` | `9e249c829b2781ed6569d658ace09461c010bdb1` | 1234 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@27

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-init-skipped.js` | `95ac9fcdf005e86f7e81772419daf2eeb715768b` | 1664 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@29; f@58

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-init-throws.js` | `27cc7c83c39f20c5d62a25cb5384e9ca2abc4e3e` | 1184 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@28

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-init-unresolvable.js` | `e9000512202c0b7d9e977f63e955946fc4867a9e` | 1365 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-init.js` | `38fdb1070092ebf7c91d6993a543cce987bc7538` | 1194 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id-trailing-comma.js` | `2ad14b75bc8cdfaf4b752f6a00075dcc0f230c2f` | 1187 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@40

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-id.js` | `3e3ddef41d7125d584b85bd0ad40fb289b7b9d74` | 1176 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@39

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-obj-init.js` | `9e44c37e5f168d79d41f8730c6d3a63a1cc4b267` | 1514 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-obj-value-null.js` | `7d603c62f6b97626854722efc328119179d01a88` | 1147 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-obj-value-undef.js` | `ea685e7b2babd7d77ff2f6fcd5bdbf018adc7669` | 1129 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-prop-obj.js` | `2fb16ded2a3a4565f4bcc22733e697d00ab98f5d` | 1415 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@43

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-rest-getter.js` | `207ba7de4a136a1197b31760c493cb0e4989c6e5` | 1151 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@38

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-rest-skip-non-enumerable.js` | `0b2a97f109f8b96ac4c6a60cb838b3f1a291a979` | 1321 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@46

`js/src/tests/test262/language/expressions/async-generator/dstr/obj-ptrn-rest-val-obj.js` | `fd09928e1697daa950a388afc8bab6702146ea0f` | 1280 bytes | test-path,source | UTF-8 | mode 100644
Declarations: f@45

`js/src/tests/test262/language/expressions/async-generator/dstr/shell.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-NSPL-with-USD.js` | `f09c58e53e3257e62396b3227bfb435865d3b05b` | 584 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-arguments-in-formal-parameters-strict.js` | `f6a7b3a300de646a3767470f35397e58563d1edc` | 550 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-await-as-function-binding-identifier.js` | `fc2b60d1f5b08071e1fd506d9e7fbfd1347453ba` | 485 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-binding-identifier-arguments-strict.js` | `7f9c53b5ce20a531d3654c934599490b5bc2c2ca` | 588 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-binding-identifier-eval-strict.js` | `45a8922d7a1d503344f97c782ad1b2e0bd1a8bd0` | 578 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-body-contains-super-call.js` | `b074cbc7dd662f8d4f44dfb0bb27fcbcbaacded1` | 512 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-body-contains-super-property.js` | `a62022973ee318360884782807391e200aaa9d78` | 519 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-eval-in-formal-parameters-strict.js` | `cd5284a1579721bddfbaaef2643c8b7afe4f2990` | 499 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-body-duplicate-const.js` | `9be10e96014d43faab710d4859ce9b6e75fe0f0d` | 711 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-body-duplicate-let.js` | `aea4309f8e3b31612d48282a3cb483675b4b67d3` | 559 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-await-expr.js` | `5a6677d8e8ce91a481558ee67bbe853aff25bcc4` | 518 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-await.js` | `9bf880d200149b0c7cea38de2e62278abce3f52c` | 545 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-super-call.js` | `07801e74ebc5b9d7362c79edd4d9ec7f6200122d` | 512 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-super-property.js` | `344914d8d6aae1bed1c5ab723d95e78d103f1df4` | 519 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-yield-expr.js` | `3e24c30203a212e1288bdda2f9883ab6ff767d23` | 516 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-formals-contains-yield.js` | `e30271bf70fadf44d9d6d3bbe834482d294a1178` | 545 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-label-name-await.js` | `c19d21c7cec7e0d9161fda5acb9b711f298b2b38` | 627 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-label-name-yield.js` | `3565f700f82f10c8753c5c52c01d1111ce1ecade` | 710 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-not-simple-assignment-target.js` | `7f49ef1285cdbe00e782ebc4bf7c9427ff03f906` | 466 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-yield-as-function-binding-identifier.js` | `36a3a63894fbee2e2fc18fe487e4728c6bed5431` | 510 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/early-errors-expression-yield-star-after-newline.js` | `6867a3aa5b5b7ccca2ac938b0f5894ad3f0983b0` | 476 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/escaped-async.js` | `6d0692ea2939d20ac452bee203ca3404af7c162d` | 890 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/eval-body-proto-realm.js` | `1c48e3b768c80c16f81e33015a55ce60adfa965c` | 2116 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/eval-var-scope-syntax-err.js` | `d157cd3e4bde35395428a2fea06f2339b2abddc9` | 1221 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-await-as-yield-operand.js` | `ece1fe83c9a63ce64e205c9484329d0b6152231c` | 818 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-await-promise-as-yield-operand.js` | `385b014d44b1024da932c44650b84eac4c381030` | 869 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-await-thenable-as-yield-operand.js` | `37877d43334986c11a2585b48c0ac9d4289513f4` | 902 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@15

`js/src/tests/test262/language/expressions/async-generator/expression-yield-as-operand.js` | `d64aba17153a70f4429057f3e012573c7ead6bc3` | 1052 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-yield-as-statement.js` | `9cff52a2af14f5719b799c1b8b168aca1e20dcf7` | 1519 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-yield-newline.js` | `541f1a862c99e029561cb085b18187f3a41db498` | 809 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/expression-yield-star-before-newline.js` | `f5511e44cff4244bd70ddc0186bfcb3d9aca421f` | 593 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/async-gen-func-expr-forbidden-ext-direct-access-prop-arguments.js` | `36958168926dcbcd67174797d34f6ed94f6e5a2c` | 1753 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/async-gen-func-expr-forbidden-ext-direct-access-prop-caller.js` | `4baefa87a898bfe08443e64b5ca08f6b31a5a167` | 1744 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/async-gen-named-func-expr-forbidden-ext-direct-access-prop-arguments.js` | `01c75de1b49dc6ba89cc730091f85dc456189974` | 1785 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/async-gen-named-func-expr-forbidden-ext-direct-access-prop-caller.js` | `939d7cb830b5ca2d9dbce6d8c97d29fdac0d89df` | 1776 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/browser.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b1/shell.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-func-expr-forbidden-ext-indirect-access-own-prop-caller-get.js` | `3b1af7907af98b179900013535a178d8dafdcbfe` | 2684 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-func-expr-forbidden-ext-indirect-access-own-prop-caller-value.js` | `60f13fe355c609d3f6266065b8017104e7f75742` | 2679 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-func-expr-forbidden-ext-indirect-access-prop-caller.js` | `e15c2928322cd7ad6e3534656a3a144ac6488bd2` | 2663 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-named-func-expr-forbidden-ext-indirect-access-own-prop-caller-get.js` | `b033e2d35930a259d011a3493e2e2ea538ba554e` | 2716 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-named-func-expr-forbidden-ext-indirect-access-own-prop-caller-value.js` | `fd99288e11098af89adef1cd801f9f805bc32332` | 2711 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/async-gen-named-func-expr-forbidden-ext-indirect-access-prop-caller.js` | `24a7c4f53afebdd8ead15f5053411d59081d06ef` | 2695 bytes | test-path,source | UTF-8 | mode 100644
Declarations: inner@22

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/browser.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/b2/shell.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/browser.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/forbidden-ext/shell.js` | `e69de29bb2d1d6434b8b29ae775ad8c2e48c5391` | 0 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/generator-created-after-decl-inst.js` | `9d74e665345788ec14c776f7c1cc32b9ef500c96` | 896 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/name.js` | `4dfd2d458de9d734f49d10edc0a02cf2b8c09adf` | 1425 bytes | test-path,source | UTF-8 | mode 100644
Declarations: verifyProperty@30; verifyProperty@34

`js/src/tests/test262/language/expressions/async-generator/named-array-destructuring-param-strict-body.js` | `55d242fd7b4aca0387af10b3a1f8c60db3e448c4` | 4723 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-binding-identifier-escaped.js` | `4653cf575eb35b71255bb363033bc0153bc03b9d` | 950 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-binding-identifier.js` | `cac883210c3a7d08009396a42703b1a8399a2a02` | 937 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-identifier-reference-escaped.js` | `b4d9f6e00e71fd061afccb4619fdf4575c57ea66` | 958 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-identifier-reference.js` | `ebc00efaae6a13b247a65004bdf16d074ea64819` | 945 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-label-identifier-escaped.js` | `e15ea1760c5dcb011f663fa6a34bc3b1982b502b` | 942 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-await-as-label-identifier.js` | `d189f17d064f57d3d63e18046b9a5d39afd9e649` | 929 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-abrupt.js` | `d3c1e3b4a2c0257bd8a06897c49e2b38ed536832` | 1468 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-arg-val-not-undefined.js` | `9599a0990774fdeb05cc01da938d41ab95dd9be1` | 2366 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@57

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-arg-val-undefined.js` | `a1822f2d5a00f3ef544a1fdb730bc0f428dc21f3` | 1635 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@47

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-duplicates.js` | `9fd77d7680ab220f976ee2f75e71359ab58822bb` | 1310 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-ref-later.js` | `a57df156aacc2e49df69cb0cae0824a199c5982b` | 1451 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-ref-prior.js` | `6b23c62f38000bfb321dd2402635ccbaaf6e8952` | 1668 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@44

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-ref-self.js` | `06abd430c8a3b788d59c22edcc694f7da422aece` | 1440 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-rest.js` | `67e8ee7e84136a5e7b82ec3839e5e60221ad6737` | 1129 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-dflt-params-trailing-comma.js` | `7697a9613b26a54414bb56899005dfbaf40c51d0` | 1336 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@37

`js/src/tests/test262/language/expressions/async-generator/named-eval-var-scope-syntax-err.js` | `1f80e5ff9dadeab7eb3844ed53d05609e7050cb2` | 1255 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-no-strict-reassign-fn-name-in-body-in-arrow.js` | `27c70d438ac8b082dc299fd86bc9889d8b1093c1` | 1022 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@13; asyncTest@27

`js/src/tests/test262/language/expressions/async-generator/named-no-strict-reassign-fn-name-in-body-in-eval.js` | `f707a29d64bca805797e988b8e186c98ff7d921e` | 1008 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@13; asyncTest@25

`js/src/tests/test262/language/expressions/async-generator/named-no-strict-reassign-fn-name-in-body.js` | `2d5733f65a1f8770328baac6f285a8c2ec9d04ab` | 992 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@13; asyncTest@25

`js/src/tests/test262/language/expressions/async-generator/named-object-destructuring-param-strict-body.js` | `1b6d5ef9dddf9550e39ccc4f1a0d0d6ee73006d6` | 4726 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-params-trailing-comma-multiple.js` | `2206c44438055f44785a8ef12e0b88e13e0e4944` | 1329 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@37

`js/src/tests/test262/language/expressions/async-generator/named-params-trailing-comma-single.js` | `30f73b4433858c4128e07cf0d7fbf0fb07c57f9e` | 1293 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@36

`js/src/tests/test262/language/expressions/async-generator/named-rest-param-strict-body.js` | `11675d2870da90d0a882f689ca0067e6f4e1a58d` | 4732 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-rest-params-trailing-comma-early-error.js` | `1c760b6354d753b85f24c9ac0bf3ab65a6e22a14` | 1238 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-strict-error-reassign-fn-name-in-body-in-arrow-strict.js` | `edadb9d94a2bf492eb39a082a87a9f79ae8d5753` | 1129 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@14; asyncTest@28

`js/src/tests/test262/language/expressions/async-generator/named-strict-error-reassign-fn-name-in-body-in-eval-strict.js` | `f59feecf43e1d67fd22901f5f591e09021769e00` | 1115 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@14; asyncTest@26

`js/src/tests/test262/language/expressions/async-generator/named-strict-error-reassign-fn-name-in-body-strict.js` | `0a2df195c82117c85a1e4b6451dcffcb3922180d` | 1099 bytes | test-path,source | UTF-8 | mode 100644
Declarations: BindingIdentifier@14; asyncTest@26

`js/src/tests/test262/language/expressions/async-generator/named-unscopables-with-in-nested-fn.js` | `f32c2a08defef125c6427414684acb2f8c5cdc29` | 2306 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@77

`js/src/tests/test262/language/expressions/async-generator/named-unscopables-with.js` | `1656b3cbc62823da70c4db219256d3138ea67a8f` | 2131 bytes | test-path,source | UTF-8 | mode 100644
Declarations: ref@71

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-binding-identifier-escaped.js` | `bc6d42832532c130072167d4e4251bc9f541a2f1` | 950 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-binding-identifier.js` | `7c1f9011cce3c840a893c013ba6e63cb979b215d` | 937 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-identifier-reference-escaped.js` | `a91e7d984da13fd473efe1ac8042247049ef60e8` | 958 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-identifier-reference.js` | `9e03c21bca7b6ff3d6f59f7b5ada236edbdb5c8f` | 945 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-label-identifier-escaped.js` | `77e30f20308009c2fbb35c00348c51a229533d27` | 942 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-as-label-identifier.js` | `b4acf9c3b1d89f65e7fc5e38bf1e15d490d72fac` | 929 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-identifier-non-strict.js` | `ac8b2ffa0e1d1053b346453200e1f26f804fb729` | 1197 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-identifier-spread-non-strict.js` | `89894af8836780e1ccfe4a3038a72dcb63b33f9a` | 1764 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-identifier-spread-strict-strict.js` | `1a05d4e18c3477a78099b581c0ec3f39c943038b` | 1135 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-identifier-strict-strict.js` | `d621ad6e86164eb02625b55fc3da2e295c9581da` | 967 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next-catch.js` | `4bdac14bffc47bfff3b84b72ab3284f5f9389a2b` | 1280 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next-for-await-of-async-iterator.js` | `0a842022b9a47b86fcec81dbf1f9c8d7fe44f739` | 1405 bytes | test-path,source | UTF-8 | mode 100644
Declarations: readFile@19; await@29

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next-for-await-of-sync-iterator.js` | `ff27edf1714d2b87f867a2858d579f0357ae5f71` | 1390 bytes | test-path,source | UTF-8 | mode 100644
Declarations: await@29

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next-yield-star-async-iterator.js` | `b1acb229410bd59dfd6a8b269b01c02c9adc2222` | 1366 bytes | test-path,source | UTF-8 | mode 100644
Declarations: readFile@19

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next-yield-star-sync-iterator.js` | `615c0251b4b14fb5489517798f5db95fba2abe6d` | 1330 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-promise-reject-next.js` | `85ab17c6cd9a62697497356fdcd53f60ebaf4456` | 1281 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-spread-arr-multiple.js` | `ddc969ef1e05863b5a9414963f4a9c0760a11c89` | 1195 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-spread-arr-single.js` | `52db92dd160d31551ebc35b62087b3d4e7846ca3` | 1287 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-spread-obj.js` | `3ebc8fa656654a6b069544e4f6227653eb2eb303` | 1214 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-async-next.js` | `904c856d7fce85626e62f4ab63fc682bc2ac458e` | 7214 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@30; next@39; function@44; then@55; function@60; value@69; done@76; then@91; function@96; value@105; done@112

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-async-return.js` | `4c56c20d31dd4121cc5e07a76e90a90c4f883bd1` | 7933 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@50; function@52; function@64; then@75; function@80; value@89; done@96; then@111; function@116; value@125; done@132

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-async-throw.js` | `87d3da40901198746fc5429edeb59129fefa4330` | 7955 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@50; function@52; throw@59; function@64; then@75; function@80; value@89; done@96; then@111; function@116; value@125; done@132

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-expr-abrupt.js` | `4a28cca3db7842e7d5f93ae78f1cf49f3734e89d` | 1391 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-get-abrupt.js` | `2d0300fa3c3e543297fae0815b80565d2679ee02` | 1898 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-not-callable-boolean-throw.js` | `931d2763b7a08b58855fd7bd080e151cf8f19573` | 2028 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-not-callable-number-throw.js` | `087a62f01e60e2a136eb16c70d7d1c2e64cd4252` | 2022 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-not-callable-object-throw.js` | `d8dc7764a758e3446b1c96b6dcf2663af618b5ee` | 2023 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-not-callable-string-throw.js` | `162bbdd0775185ab5d214e387b66ba018ca81988` | 2023 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-not-callable-symbol-throw.js` | `239b0de71ba3288609c8719e921074cab694708e` | 2041 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-null-sync-get-abrupt.js` | `d65a2828552a6dcfcab7b92cbff69961a34a229c` | 2028 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-abrupt.js` | `d210513355d7ff0cffd99b66c5cbd3a615034c65` | 1876 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-boolean-throw.js` | `1cd251b3b9ac45c335fd132064dda5419c8c5b50` | 1948 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-null-throw.js` | `fd65d736538f87cf23425d151f0803ac287f0c44` | 1942 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-number-throw.js` | `2eb11f2b2a18fc2f5e326e37ba46eb49eec0d539` | 1944 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-string-throw.js` | `76cfafb451fe1a3bd2ddadf2c480822ab37c6a5c` | 1946 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-symbol-throw.js` | `8ea49287061c6094ef94ebf0d90cfbde29370471` | 1962 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-returns-undefined-throw.js` | `5ab7266b495f29f8dbc32868cd2dd549338324ae` | 1957 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-async-undefined-sync-get-abrupt.js` | `25c39663246a6c02701c4e3f137479d2b7ac4d79` | 2043 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-get-abrupt.js` | `efcfbbf402c304c4fbc48942ee5f2c7aa21d0231` | 1881 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-not-callable-boolean-throw.js` | `48a010d224b52182d7f3ddb5d8e194571ffca931` | 1935 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-not-callable-number-throw.js` | `f987249e10dbf251b4d4b4f00ab032f788b2e279` | 1929 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-not-callable-object-throw.js` | `a35d12ecb7b350ee1065d256debef8ec51244a7a` | 1930 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-not-callable-string-throw.js` | `fb7056aeb0ffb94bbf6f8b17fb93aa6089cee4c5` | 1930 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-not-callable-symbol-throw.js` | `4aac64994665f225adceb59dc6bfb4ef24a6126a` | 1965 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-abrupt.js` | `9052274aafcdce71261a80749a84eeab83d64f86` | 1831 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-boolean-throw.js` | `e4ca23f72866e50857e43ca2db3292f0438e7322` | 2006 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-null-throw.js` | `f6c22f9aeb0b397e3e6081b88b27b9814effc38b` | 2000 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-number-throw.js` | `e9777aa6f466f7e0b254a59da7f8eb32acea9b98` | 2001 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-string-throw.js` | `c58d7874f2f9315b8e56253c8284b8f88e026870` | 2002 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-symbol-throw.js` | `fea53d164bf803f1ce16c400e3b575db80f6c8a5` | 2015 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-getiter-sync-returns-undefined-throw.js` | `5c11a72ea0ef1ca827ebee9594adf9a6756d6cf3` | 2015 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-call-done-get-abrupt.js` | `0f111bb1497a1dff0a8e73ba87d6bf6243495857` | 1892 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@38; done@40

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-call-returns-abrupt.js` | `87744633df166d4d132f30888ea1626e478c264a` | 1657 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@34

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-call-value-get-abrupt.js` | `ffc74aec9b19a01eadb4be035515e4547b201af2` | 1946 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@39; value@42

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-get-abrupt.js` | `e731e31103294ed88410285cca766c0d15370238` | 1652 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@34

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-non-object-ignores-then.js` | `0051905a6b4f72273b7147b80ccbc0e2a968d377` | 2328 bytes | test-path,source | UTF-8 | mode 100644
Declarations: next@54

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-boolean-throw.js` | `64076a393ce1b7c1e87374d82a50ba7498896967` | 1652 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-null-throw.js` | `f31869aca3c5cf7a85e789c60aa87c020929cb9c` | 1646 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-number-throw.js` | `b94fad4ed0ae065edb9055901d87966f2dce6988` | 1648 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-object-throw.js` | `3dbcfe3777e1903d248019dfc9857834d8f430ec` | 1648 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-string-throw.js` | `2374798265df0985f26c08a338f82a589aeeb5f5` | 1648 bytes | test-path,source | UTF-8 | mode 100644

`js/src/tests/test262/language/expressions/async-generator/named-yield-star-next-not-callable-symbol-throw.js` | `a93dbe73538f352f8db08f5ce3a8837dca7e50fa` | 1658 bytes | test-path,source | UTF-8 | mode 100644

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.

## Retrieval correction

This copy preserves the source map in [0aed5687-0522-4300-9dcb-9c462e2da5bb.md](0aed5687-0522-4300-9dcb-9c462e2da5bb.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `b46271430e1426b6a9e42bd4d965e52edd3b09e61c141a67c876447588ebff5c`.
