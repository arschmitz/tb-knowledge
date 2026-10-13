<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["js"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["4002eb47b8e5270e0749efb4a8035e2b55f472b848bfeab8368eedfaab76cb12"],"sourceAt":"2026-10-13T04:14:46.642314+00:00","correctionOf":"notes/734891f6-9ff6-4a31-bcfe-0a6ef34285c0.md"}} -->
# firefox/js structural source map 327

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-id-trailing-comma.js` | `c7f99ae8846adb0559677c728eeb72e29e6042ab` | 2672 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-list-err.js` | `2bbdb4261d08e5e157b622265b7e5ea07bcb7da3` | 2820 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@70; C@74

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-ary-init.js` | `26742762cfbca65988d83eab4b21864fac5a8eeb` | 3048 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-ary-trailing-comma.js` | `bfa832e1d04cdd91d90f77a44d705551a6947a24` | 2684 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-ary-value-null.js` | `724095625ccdd0942962ed162cae0ff16e3ecb81` | 2712 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-ary.js` | `4277491363d9cc7432bb8072b9bf01828a4353a2` | 2957 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-eval-err.js` | `873dc625c78ae9204d78f238cce1e2e34a85cbb7` | 2635 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-get-value-err.js` | `55a6fea28ccaab03f72ea25c1a45e2cd1a989ece` | 2813 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@70; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-init-skipped.js` | `668c518f365593305d6a78a301bd5bc3f88b5660` | 3248 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-init-throws.js` | `4036ce4dd1054e5192a2c73d36b27fe5608e6bfd` | 2763 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@71; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-init-unresolvable.js` | `272edfbc9991065fd9c66232e685d0671c14a4d4` | 2944 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-init.js` | `4a4b492bca05e46445f743b10eabb080d7b8fe22` | 2752 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id-trailing-comma.js` | `346669cbd0d5bcfcc266baebb17e8b36339c1619` | 2745 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-id.js` | `b157c716779312219e1b7a596aa3fe3a92db3239` | 2734 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-obj-init.js` | `4b929c3ca3118c52819a93433d0ea4aee68dcdfa` | 3076 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-obj-value-null.js` | `a2b51e2f455c9ebc5bb99f417728059c3781df5f` | 2726 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-obj-value-undef.js` | `62b845667a937eb28d17cc0c52226e4ce4d69865` | 2708 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-prop-obj.js` | `aaf80b4764ca5b48e643de887666109fdae23d7e` | 2977 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-rest-getter.js` | `f73c062841162f01ac794a408ec6d8882e72f7e3` | 2715 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@65

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-rest-skip-non-enumerable.js` | `07bc5f9764ce72f9bc27e0a2f509470c76c73c58` | 2897 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-dflt-obj-ptrn-rest-val-obj.js` | `f4f3d799c5666df8d25d5b66216617fb91b6b9e0` | 2858 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-init-null.js` | `2ef714fd6a30318eda2ec856783729cee3fb99a1` | 2456 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-init-undefined.js` | `9e983ee2cfb22cb135f620c81300ddd3b0352fc1` | 2471 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-empty.js` | `0cb56067ea416047c39de61f3afe4ad761434881` | 2682 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@69; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-get-value-err.js` | `e9185fa545dd4a09fe1a8225fb46e812fdb17773` | 2695 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@70; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-fn-name-arrow.js` | `87997fca056d54516999cc88cdbc3626c63ae725` | 2951 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-fn-name-class.js` | `7e6d35bc59f5a420d80ae77bf85ee014ceef26d0` | 3094 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-fn-name-cover.js` | `21965c66b78fb60982015268022e6417d9652432` | 3067 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-fn-name-fn.js` | `d7b1d4d2c7356395ac46e336c2a55386275dbbe3` | 3014 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-fn-name-gen.js` | `44a81b541fd25be5b8599ca6ad12793281cbffb2` | 3034 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-skipped.js` | `83ff468f2cebeeb08198f5836a1274c27093f52c` | 2945 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@71; C@76

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-throws.js` | `d6e7e9e88314b8c42dea8c9f6ab220cb4d4906d4` | 2714 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@71; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-init-unresolvable.js` | `0e27e7c6834f728e43a4ac5b22efc86e3e5349aa` | 2894 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-id-trailing-comma.js` | `3b09a587ce86f59f169fe8a778166cea290e7acd` | 2624 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-list-err.js` | `248afa936c88563762aeefe5ae7d2b499a2a2e70` | 2772 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@70; C@74

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-ary-init.js` | `1d8e2f1b5c21492a03a48e3836ef7a18518691cf` | 3000 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-ary-trailing-comma.js` | `fdf2ab24767d703dcdffa41b927bdad0753687a8` | 2636 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-ary-value-null.js` | `3ea5b90bc657ed82a5eca6d8f363cd1c744a13d1` | 2664 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-ary.js` | `88b59b373af6a1ebbc02499055dd482a262c89d7` | 2909 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-eval-err.js` | `bfb43c45557ec7a04fabf84f0cee1a769733ceef` | 2587 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-get-value-err.js` | `6f70fc507a0f3bc56ea7382d61fdfa801aa991ef` | 2765 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@70; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-init-skipped.js` | `1d7a5f67f5137b33c4c48cd1a7fb8acd9c2551ea` | 3200 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-init-throws.js` | `c9be76292db129e75805bcd09c586f11764d78a5` | 2715 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@71; C@75

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-init-unresolvable.js` | `3920ec1b9300c69380552d6c692daece14c87b39` | 2896 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-init.js` | `648afc236587774a40564a463ea0cf765518d712` | 2704 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id-trailing-comma.js` | `e049b373ccb405eef3899e1b7f8e1d889c33dc1a` | 2697 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-id.js` | `a444b2498394700f625e1258cff1234fac8a313e` | 2686 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-obj-init.js` | `6dc29d04c4e6f64baf36834231f33e63753c7473` | 3028 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-obj-value-null.js` | `6d5453ea3e00b1a32f7c2be691f379617866c24f` | 2678 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-obj-value-undef.js` | `4af1f1ec0b762b89ec8d54f9dc5e5c0a4bf76d83` | 2660 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-prop-obj.js` | `50eb623cb3fd39ab85b43fad3014ab2cea812b9f` | 2929 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-rest-getter.js` | `3d02788c95acc5a2485f4a280fdea3044f791977` | 2667 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@65

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-rest-skip-non-enumerable.js` | `ceed609fce46db80a4ad3e2a57ddedf8fe984eb6` | 2849 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66

`js/src/tests/test262/language/statements/class/dstr/gen-meth-static-obj-ptrn-rest-val-obj.js` | `a7bba684b381050ea0bfc9f9a9daced36175b24c` | 2810 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64

`js/src/tests/test262/language/statements/class/dstr/meth-ary-init-iter-close.js` | `005ab4212bb45a788a1c872dd8ff63416e02c8dd` | 2712 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-ary-init-iter-get-err-array-prototype.js` | `3ea10b1bba454937c73467ae71f965c3d5ea1c44` | 2567 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@79

`js/src/tests/test262/language/statements/class/dstr/meth-ary-init-iter-get-err.js` | `f35ae02a6b81335954b7e6ef75fe3332c8da2e23` | 2402 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-init-iter-no-close.js` | `ef34711a636767f5a36d1b894076c22ed0cb4ad6` | 2714 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-ary-name-iter-val.js` | `de708238d24b9de2a83407caf6e32ff1b919339e` | 3032 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-elem-init.js` | `0ab7d31f6363e677ca6549316737f7b4309eba74` | 2805 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-elem-iter.js` | `bff42e9ed63298ca43b75269daf3096f4790e71e` | 2776 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-elision-init.js` | `6664c608dc33df24c347b14dd4e75dfc4e663403` | 2878 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-elision-iter.js` | `d039d4a783e48e082e293466712bbb1b7a87e1fe` | 2781 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-empty-init.js` | `ea075f405c30505c5b2afe162518dee59e5fae86` | 2920 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-empty-iter.js` | `afaa677dfad48eda644152c294c09c987065d876` | 2759 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-rest-init.js` | `0d70ed2f3a711acc4c1f74e9f4caeb16b9463ef7` | 2933 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-rest-iter.js` | `973529fd113a373bdb57db5cea1df99d61177c90` | 2982 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-ary-val-null.js` | `17ecd68f3a1f194317cd22bb229f900537ba0a84` | 2689 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-exhausted.js` | `f646aeeb915e57445a40fae7c50bd315903f8c37` | 2728 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-fn-name-arrow.js` | `386cf5f99abbbfb3125ce529521ab5e577e66f95` | 2796 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-fn-name-class.js` | `cbb022ae7f73c7515afeecb95b6642704a476fb1` | 2937 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-fn-name-cover.js` | `3ff3b6d0993d27a2eadb13afc4237f5802986ccd` | 2911 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-fn-name-fn.js` | `cf77ae9bb89e65322125f3e86f0001cdf2fc80eb` | 2857 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-fn-name-gen.js` | `d5d602bcac7460042c7a360097528c633d74237d` | 2889 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-hole.js` | `ffc7ee91502f50a82197062f3288d930be0d4233` | 2663 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-skipped.js` | `e42b431c4f71745470e4819c7171f5ac8a9a1369` | 2829 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-throws.js` | `5d64c1244cd488dc8dad3b4b95aa4885692449c9` | 2531 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-undef.js` | `d637e612232da40b7ba5c669752eafe69a4ffe28` | 2667 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-init-unresolvable.js` | `4e2298f444510379eecd334c46b5dbeb76fc9851` | 2711 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-complete.js` | `ad42383ae3ad3ef296aa88c54e3dbdcebfc203bd` | 2815 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-done.js` | `5104806e2580bb8479edc4c68df97c629eb0a1b9` | 2568 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-step-err.js` | `cf3dfa6ef229a5b056b81d5754316275bc93eb54` | 2657 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-val-array-prototype.js` | `14d0ad72ea3afe6ee0888e0d67da627e1217b70b` | 3330 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@91; method@92

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-val-err.js` | `96b3148560b29ee14e6cb2c87b6ae568c04d4153` | 3021 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@77; function@84; C@90; method@91

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-id-iter-val.js` | `68833d503e85e2effd62f880671216ab2759e9e7` | 3058 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-id-init.js` | `6cbe47422cc730613996a4aed8a62d9ec92859d1` | 2823 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-id.js` | `95650ac4974aec983cf1821c949273bf47483731` | 2845 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-prop-id-init.js` | `db9badd5e6d6da1650f85972904b93ef897a96da` | 3036 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-prop-id.js` | `8304975b938dcfeee7833543ad8390e910516310` | 3061 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-val-null.js` | `7657d0414d54b8476d198c143ec3b8b767785888` | 2698 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elem-obj-val-undef.js` | `df76a7f5378a5fb5c14deb3cfd4b12364ffe79d2` | 2705 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elision-exhausted.js` | `46ac9945fc8b40b8490eedeef68db4b900dc00d5` | 2685 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@80; method@81

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elision-step-err.js` | `ea26c3aaf7109e5398acc2b1bcc2d0a65cf7ea2f` | 2900 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@84

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-elision.js` | `94695ff32134cb5e92655b5a9402272b861b7810` | 3000 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@81; C@88; method@89

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-empty.js` | `fef6b48e0c42113729ab1e18f435af5a8142458b` | 2446 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-ary-elem.js` | `21cd0216f71a59abbc5831955901b6cedca09958` | 3437 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@94; method@95

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-ary-elision.js` | `7522fe40c6e732cbb239a98e3320bb80b6dd6c9d` | 3404 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@94; C@101; method@102

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-ary-empty.js` | `155abede581a2de70761591f67580445476f65bc` | 2833 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-ary-rest.js` | `4bd1b7640c9fdccb9fd8c954c52bff825b505a18` | 2794 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-direct.js` | `88b87499698023fb47b3ddb4deb29d3bfbb52151` | 2574 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-elision-next-err.js` | `aae9152dc8db58ebe536c4288b05c2b99c850424` | 2713 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-elision.js` | `c8e14a5038317e945465fa89d883fea5174210d0` | 2921 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-exhausted.js` | `36b68b678e457ed2c651ce5307c5abc715ddf31f` | 2752 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-iter-step-err.js` | `4e8dbe55875f82e552ce0adf989a9f94ede108a5` | 2941 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id-iter-val-err.js` | `017032252e0abf672a7bcb9848363ff7a237c64e` | 2892 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@72; function@79; C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-id.js` | `2dd80d774bf5caf652f3f25d845f186d7ea2bd7d` | 2642 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-init-ary.js` | `d2bc0a990390ccb7d9d3fab6d7bcd031602b54a9` | 2547 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-init-id.js` | `996eec5e909463e613f14b287f061c1151dd018b` | 2532 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-init-obj.js` | `388e6f26b5ec4f7c9cbc45fc410aaced95d9603b` | 2548 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-not-final-ary.js` | `2a6de08dfa04325e674b5957e689aac52b53f69d` | 2562 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-not-final-id.js` | `0ee09dfa59c635358a91d3e6ed77cae04fa73bea` | 2548 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-not-final-obj.js` | `140b92931975d92963f8a25c87276a98f346e30c` | 2565 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-obj-id.js` | `a9a9252c74fc85af737cf5b72ef0fe2b36860439` | 2624 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-ary-ptrn-rest-obj-prop-id.js` | `a9d8735976fc0ca47f274fd9684db32589308169` | 2881 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-init-iter-close.js` | `d5fd2fde69f54ed8bc92c1179f94eea0b80ffc5c` | 2760 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-init-iter-get-err-array-prototype.js` | `7447e35f813f747d41877cad7f5383341c6795cd` | 2615 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@79

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-init-iter-get-err.js` | `3e33190ed1e69d3e7418dc57d75e28330f2d6974` | 2450 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-init-iter-no-close.js` | `4d2b4afbe33b4ddb69c638725c19ff357dea7299` | 2762 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-name-iter-val.js` | `a750f1a5f973bd6e6693cf277d763b6ff0d78e99` | 3080 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-elem-init.js` | `b9a8aaa625c1932e56f3c3ade310d04a776ccac0` | 2853 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-elem-iter.js` | `ed81931b075c99fdd9c72072efccb678d3190eca` | 2824 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-elision-init.js` | `18a060e4b5e7e820b11c0caa142787b635c11396` | 2926 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-elision-iter.js` | `ca7a23457df89c980b7e9cf16de979bafc3d2506` | 2829 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-empty-init.js` | `7557d56e0a1bd2fdd3e45beed642aaab0a4eecc7` | 2968 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-empty-iter.js` | `5a2e1e20f988701375d4a1103e6bde23b210d69e` | 2807 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-rest-init.js` | `8106d4e1c4d346fb064467fcc60286c6ff4aa442` | 2981 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-rest-iter.js` | `d9739b025602ae9c074b24b6fa102763f98976e0` | 3030 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-ary-val-null.js` | `f52f2de2cc522b00e1fdce145600ac1981a601ba` | 2737 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-exhausted.js` | `401917ddc424da4a317219b494f5e36f2aaaadcd` | 2776 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-fn-name-arrow.js` | `2880a9e9a4cb62d4e580cf2e5fcf99307d662660` | 2844 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-fn-name-class.js` | `127d3c4cc22d2946e8f6ec4e3886c7de47d8d59e` | 2985 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-fn-name-cover.js` | `9879ac042c9aab37512ab51aa1ab5a4d193e1db5` | 2959 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-fn-name-fn.js` | `8981ce4a2aacbc344a7a051bb82734a3f789f27c` | 2905 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-fn-name-gen.js` | `756deb15da7e1d9fcd400cc03e85fa507fa77a11` | 2937 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-hole.js` | `9e2d008c33d432f441e745491c9dfc53edb72d4f` | 2711 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-skipped.js` | `364f518c22bd352d9050ae7fa143212e38083564` | 2877 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-throws.js` | `636e8b17c8935df4afde10767d2aa226cbd9437c` | 2579 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-undef.js` | `0aa4f7af5422ce7b33d67d0ebadecb627647cd8f` | 2715 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-init-unresolvable.js` | `5f3153fb69096bd71133b1060c9f68536fc28ad9` | 2759 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-complete.js` | `4c9d487bd85ec54d442bd3707a0f15ef8b72229d` | 2863 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-done.js` | `9e3930e1c31d5c0d6e5d5c2e8f2a43521e84c6e0` | 2616 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-step-err.js` | `32dd893be0b71ce45f7b1e591ce39b4ad7533de8` | 2705 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-val-array-prototype.js` | `2b19156b416e3fb283463832c3fdae007162f74d` | 3378 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@91; method@92

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-val-err.js` | `75827ac733164643a0dd4615e01010386336dbb2` | 3069 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@77; function@84; C@90; method@91

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-id-iter-val.js` | `e605a400343cbdc3e65eb56311890cc3142b19a0` | 3106 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-id-init.js` | `ed59a156b4e7a8fdbd896290b454051f3c025688` | 2871 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-id.js` | `89f8f2a8904a90b0801c40391add03eb3a73773d` | 2893 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-prop-id-init.js` | `2916687ce2e3b1478cf9c54ec047b437cc762e60` | 3084 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-prop-id.js` | `162a80716560a7d38a80350b57d83553b39c6561` | 3109 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-val-null.js` | `4fca071ff69bca178624b96aeb1e28a26131ad8e` | 2746 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elem-obj-val-undef.js` | `cd17eac0cba1ade34ccfc9282e766a1c4dd5e5da` | 2753 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elision-exhausted.js` | `86f9bbf5b9aad0bdb29a88b6d96dc4ccbaffed3e` | 2733 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@80; method@81

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elision-step-err.js` | `e7be6aac4e46c3b3e4898ec3de222ec072e875ac` | 2948 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@84

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-elision.js` | `4b19df93bfc103091df8d04b5a965b5d7f0e3855` | 3048 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@81; C@88; method@89

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-empty.js` | `7a98296dd60f8421475b2ced40e11cd847b64b62` | 2494 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-ary-elem.js` | `af0957121c4fb89eeea58830f777bc9433f07980` | 3485 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@94; method@95

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-ary-elision.js` | `4b92ccdcb65ada0351a6b1150c2e7bab10f18b80` | 3452 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@94; C@101; method@102

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-ary-empty.js` | `17fc39a2147ff868e87a95bef9f5ea16a2219bed` | 2881 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-ary-rest.js` | `bc541b73f5b3378482a5089597c183cc0bbe2beb` | 2842 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-direct.js` | `129fb000dbcb9198a4e6ba6e3ea7c7eb35c4e14d` | 2622 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-elision-next-err.js` | `987bec94f4efa69f16c80e7e42d96151f284291c` | 2761 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-elision.js` | `6f27b0b9cd745c2973de1cf2807cec527c49c205` | 2969 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-exhausted.js` | `9d7adc641f0e46c35393df1b21e42247108dc97c` | 2800 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-iter-step-err.js` | `aef6bb4a49bc5753e3e3c0902315318b443b94a7` | 2989 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id-iter-val-err.js` | `2e505bfba17c9fb9314a7c27caaee6fdbdf9bc1b` | 2940 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@72; function@79; C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-id.js` | `d4e5e0f892492d0ac3e28f48b56db343f00bcb21` | 2690 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-init-ary.js` | `1d009b33183e594a25771804dc662997a3e40811` | 2595 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-init-id.js` | `d494273cbcc4cd6363c6fc58dfdae4d33f33aa37` | 2580 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-init-obj.js` | `590b6cc240aa1bbd59efc50b9fd574be999f2fbc` | 2596 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-not-final-ary.js` | `cec717b63f050c68a91bcddb4fc76f7b0aa99ca9` | 2610 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-not-final-id.js` | `937a57aaf474744ad36e9c06c0b34c85f70f8a95` | 2596 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-not-final-obj.js` | `9a75b35c3daaf2e6be759d8ac6125d40ee1daef3` | 2613 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-obj-id.js` | `a5ff0b91eb0c4476540c50a561e2c0e5a1225661` | 2672 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-ary-ptrn-rest-obj-prop-id.js` | `40a71661786a05263cffeb8771832bcee6d6bf47` | 2929 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-init-null.js` | `b9991334005fdbbba9230e2a9b0e2b4c70537225` | 2313 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-init-undefined.js` | `11234a1875da9c5730f44617557bb8c680951779` | 2328 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-empty.js` | `01594d544318e659d75e09617ea77efe2724b270` | 2520 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@67; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-get-value-err.js` | `6f39d999694eb207528a65e9d0c97df148f3bf06` | 2552 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-fn-name-arrow.js` | `6cfefaf62fc2bb6c75ddd757b44b24f66b63eb89` | 2789 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-fn-name-class.js` | `aba947c3e44fa745b1a7768ae3c0a57a9556605c` | 2932 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-fn-name-cover.js` | `5a31c9cf3efbfcc5d945a997fdf6abd1216e2307` | 2905 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-fn-name-fn.js` | `7593b3c9474a9047e30da35e0a9a4121101bec65` | 2852 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-fn-name-gen.js` | `80974cc4ef86128c316072d1edb8a6c70eeb21eb` | 2884 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-skipped.js` | `a2754f994408bb38a05632ab896be763d66590c7` | 2783 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@69; C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-throws.js` | `02dde5b5a999a4da21b1379708b190cbcb9ddd2d` | 2571 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-init-unresolvable.js` | `376a67c7e615435bab26c46252323fa3e6b1c57c` | 2751 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-id-trailing-comma.js` | `38236ebb18183e42b2b570eec409563f89a8e412` | 2462 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-list-err.js` | `fadaa36c49bb675346cbd1fc4dc40488e2b1525a` | 2629 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-ary-init.js` | `264340a818d0e55b7d4ee9d3bea8ecb3985087bc` | 2838 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-ary-trailing-comma.js` | `776d3bf0b7583d5f8917f7a51a060691f4a8dd53` | 2474 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-ary-value-null.js` | `d93c5454c1c552789e0a9635a5ed43660e0d5ba8` | 2521 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-ary.js` | `53a57ce4ae794bff11bfae10507e6a37c1518ac1` | 2747 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-eval-err.js` | `b9eb6187955866bb3123a482324b13cf5cad192c` | 2444 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@66; C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-get-value-err.js` | `970e57ae025de7a21abf479c67d6c61e5d157f95` | 2622 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-init-skipped.js` | `273e5687037b8183d19a8942d09b37aa5814e12a` | 3038 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-init-throws.js` | `f0a0b526b46756778b553713e1b2d3d2d34bfed0` | 2572 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-init-unresolvable.js` | `5e6109f2a8ff1a4641a9242630d80ea49269f431` | 2753 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-init.js` | `508b41ffaf34c9245eb20bd931d378d4faff4c97` | 2542 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id-trailing-comma.js` | `360ec7e0925a19fef486d29fac04f7cb1b496f20` | 2535 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-id.js` | `417188f46199c61e2d9d5a9620455bfefb2835ec` | 2524 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-obj-init.js` | `68bf8916e1ab6403f15718553d5d92f901236446` | 2866 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-obj-value-null.js` | `2c78d5ca1912f2ee13e455b45121e023c7e32630` | 2535 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-obj-value-undef.js` | `d182ca74454c2803fd7027e5e637783af73bed27` | 2517 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-prop-obj.js` | `9a01630eab50b3266219b3e95bf7eaa73256c53d` | 2767 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-rest-getter.js` | `89b6da687f8def151bc0c62914ff4e229c5ec598` | 2505 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@63; method@64

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-rest-skip-non-enumerable.js` | `39527291189b582af4a38f14486b7070e30dad41` | 2687 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64; method@65

`js/src/tests/test262/language/statements/class/dstr/meth-dflt-obj-ptrn-rest-val-obj.js` | `18908855dbb440314d5444d84f44d3b76b9631cc` | 2648 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@62; method@63

`js/src/tests/test262/language/statements/class/dstr/meth-obj-init-null.js` | `d6f298a8f72e39ca7fa0249784d6202890063e8a` | 2265 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-obj-init-undefined.js` | `a06de3fe97fac3196c23cb140f7820e5c523e3d5` | 2280 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-empty.js` | `dc950e43ae938652a1eb3696be2896cac81b8a68` | 2472 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@67; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-get-value-err.js` | `1a1937db61e423e47aa7edce38b72a7e99e7843b` | 2504 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-fn-name-arrow.js` | `2d22819e73a642d0ba78d1bb3347bbee04c7ec83` | 2741 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-fn-name-class.js` | `464465222be295264a7479e17dd20ca2273a2e90` | 2884 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-fn-name-cover.js` | `2f5349cdf6bad1e6b73dded59eeadcd3f1176912` | 2857 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-fn-name-fn.js` | `6b3c83bc9d649a585b3b666690c7eab100ae7f2b` | 2804 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-fn-name-gen.js` | `5c33c2810546469b61bc0f2f77b5af1d035ac4f6` | 2836 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-skipped.js` | `c4d4b79c48a4852d66fce2eb4aa64447aad2f4f6` | 2735 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@69; C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-throws.js` | `dd55f4bce69d48a158c75ca5c3d7833bf50966f4` | 2523 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-init-unresolvable.js` | `c8cbe8551ab3a232b1eb5db759f5be2148b80bc8` | 2703 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-id-trailing-comma.js` | `bd345507440ff33ab23b1c88104a065d53893422` | 2414 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-list-err.js` | `d95d4e82b2f4498cff073c414182d40d72c7d967` | 2581 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-ary-init.js` | `b15189fcf495ebbf69a10fb0110fb6aa077dc052` | 2790 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-ary-trailing-comma.js` | `881d22c3383c4143a866901ea712cfd94dd2a9ae` | 2426 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-ary-value-null.js` | `d63a34a3ccc0a9c1768478d3b60ce61c8ed2b1c3` | 2473 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-ary.js` | `d34fdd1ddac8c1324cf189891e49287344278588` | 2699 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-eval-err.js` | `5c3fa0712e0caa342e7a432a83a32b88c7043786` | 2396 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@66; C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-get-value-err.js` | `673cfab5d9eab0d2de9c58789c7435015822b71a` | 2574 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-init-skipped.js` | `46cbd78ea07c4e34ea83a0c174e4075b8b0cbb50` | 2990 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-init-throws.js` | `085d3a2db153ba963642a7c7ccd5de384358518f` | 2524 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-init-unresolvable.js` | `ce537ad84c3dbef5bb0cb871c39a37bc7834c3ad` | 2705 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-init.js` | `3fb9ca6909fc7cdaf26b8d4c03ce838e80670f0c` | 2494 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id-trailing-comma.js` | `77d1feff5780db51a21c27f1d34a83a09a6679b3` | 2487 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-id.js` | `4183736d42bfe6ea24a2f937c477bd50b92215ca` | 2476 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-obj-init.js` | `adf11a5ed1e8f01449275d0941069adc9d009bc1` | 2818 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-obj-value-null.js` | `0055aeac993be24066d3fe8d2854320d563d529d` | 2487 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-obj-value-undef.js` | `fee809c44df0d4609a5316c4a288fa2e7f1cd6be` | 2469 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-prop-obj.js` | `40121ab0d5da16b0182977160fafe351c3a84eb8` | 2719 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-rest-getter.js` | `9bd46cfd6ec75665f2a079beb4f29903fa3bae85` | 2457 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@63; method@64; C@77

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-rest-skip-non-enumerable.js` | `0507093351cab5551b55e7bdeede1339be6acb28` | 2639 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64; method@65

`js/src/tests/test262/language/statements/class/dstr/meth-obj-ptrn-rest-val-obj.js` | `256e56ef0ccc65a822b3395779750618c21cddc5` | 2600 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@62; method@63

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-init-iter-close.js` | `500e8143c742012c52565771e28d62fabeba3eea` | 2716 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-init-iter-get-err-array-prototype.js` | `a0e1a411bb0bd0ec4acd247458b41adfdc1290a4` | 2559 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@79

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-init-iter-get-err.js` | `aabe99798b78dd8074c1d30c99aca2537c7f3ca3` | 2394 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-init-iter-no-close.js` | `f0e2c20b70bcb8a48b6ae35d465d6efd49a76249` | 2718 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-name-iter-val.js` | `2dae5048f0f8851d920feb847d9218c507e827cb` | 3036 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-elem-init.js` | `c2d94c04f93e56d060b41e2e04e38b7e444b9347` | 2809 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-elem-iter.js` | `701808e01d61013151d03335c591b08af709d6bc` | 2780 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-elision-init.js` | `151ced0c8925bb8691dcd2f3af823a76e58394d4` | 2882 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-elision-iter.js` | `60f4dc10d340ab05bd66ce7b95c703e577ec8344` | 2785 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-empty-init.js` | `e5baeeb181ba684ac1840141236c3e6519c2a491` | 2924 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-empty-iter.js` | `96fe933c77d113b02e38718ab58b93463e2ab987` | 2763 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-rest-init.js` | `2dc3a0a2fa710c500c7f2247f288ce0e54888c0a` | 2937 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-rest-iter.js` | `3cb5844ac674d7e6165f7eb8af6949f3ff438ae2` | 2986 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-ary-val-null.js` | `26d4a15eabd45dd5747cb8ad877087fe3838b2a7` | 2681 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-exhausted.js` | `1a855e64e624fd12e28d683859a73b00685f8ab9` | 2732 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-fn-name-arrow.js` | `41822de0037c03965d080766f2bc573e8c87f6b0` | 2800 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-fn-name-class.js` | `1c3a215c7cc56e0607e9d0222e3c9ba57c84c005` | 2941 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-fn-name-cover.js` | `87555c71cef369aa8a9e4226780f66518b9f4032` | 2915 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-fn-name-fn.js` | `cb90504051933441bd12e0c5c21501ac2bee0d52` | 2861 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-fn-name-gen.js` | `123fee6fa68282de9c0c1e4f7f51aed1e26d9ce1` | 2893 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-hole.js` | `008697629ef9ec334ad54d3a54f3aa727ead6c59` | 2667 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-skipped.js` | `61072d87c323d5ef3ac9506b98a210f3476a70f5` | 2833 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-throws.js` | `bf484b08759bbec1ae98c659b6fca92c7ccc3168` | 2523 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-undef.js` | `8581e1c790a2b698888fe7997b928bfb76afadda` | 2671 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-init-unresolvable.js` | `d547915dd499d182ad76c73af361416757806d9f` | 2703 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-complete.js` | `406883eba10876a8bb0dd7cf9bbc400bdfc29877` | 2819 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-done.js` | `366e8bbb4deb83337303d3df54e3a7aae017aa37` | 2572 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-step-err.js` | `bc5e9491c6ca52547cd0d6bcd95708622213e19f` | 2649 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-val-array-prototype.js` | `6c1e06ecc5534df80d7681a51b8e68c82fb19717` | 3334 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@91; method@92

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-val-err.js` | `545132ea442d540834ddbe6fdd10baeee3e89bde` | 3013 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@77; function@84; C@90; method@91

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-id-iter-val.js` | `23fbd2b2250f98e681ff6855c6b3df1a40af232a` | 3062 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-id-init.js` | `d0c76536823b6922c975dab1bad077c2adbf239e` | 2827 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-id.js` | `8bd18483008c633b8f68206d756fbf63befac727` | 2849 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-prop-id-init.js` | `cae912d565fdb1c35a52dd664a8a4cb43b6dcb1d` | 3040 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-prop-id.js` | `f734f70da7109c1c1c60d47edb1c40460ba2f88e` | 3065 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-val-null.js` | `c634ba15663c6de3892fdbb098765a716c363115` | 2690 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elem-obj-val-undef.js` | `f79592341cfa8c2d14d4bc704d7e21ee0a00a657` | 2697 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elision-exhausted.js` | `809296796dbfe24f9798525c291679e854c990d3` | 2689 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@80; method@81

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elision-step-err.js` | `6dec356bd6a0c1233cf242d1ce31a78aa01cdc5e` | 2892 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@84

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-elision.js` | `fb75ef7921e94561608f39dcaf5f62a074975992` | 3004 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@81; C@88; method@89

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-empty.js` | `bfd4073a97b19d6a871af4a8e6aa34919cb75292` | 2450 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-ary-elem.js` | `e53d40f16eb79eb0b605ddb72aad06c38c0b0854` | 3441 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@94; method@95

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-ary-elision.js` | `9ec22d241ca329841850164911ec373b9970385d` | 3408 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@94; C@101; method@102

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-ary-empty.js` | `7f82bd1ad8ca4c929a002c38bc28303cc5be9c5f` | 2837 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-ary-rest.js` | `6e2f19c1fc106daa6ed40746f0da7961ff882c84` | 2798 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-direct.js` | `53b80e77e5a6db1fb1ed4f8d8d8cabd702a02b9a` | 2578 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-elision-next-err.js` | `b272895f4f37d1865d0ef81834770906dbbc7145` | 2705 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-elision.js` | `bfb6ddb88ea2462e12b824f59846be1a28b340a1` | 2925 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-exhausted.js` | `36dcf31e017c8fa71158fa30f97605b616a1824e` | 2756 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-iter-step-err.js` | `f15808f0fd6dcf6054f94b03b0ea1d5fcddc1002` | 2933 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id-iter-val-err.js` | `b030b5c8095918e448785704b4ccd9379a5362d6` | 2884 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@72; function@79; C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-id.js` | `801bd582fdde78a9ba3dc4b8d6536c845a7a129f` | 2646 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-init-ary.js` | `da6176dbf791b7681ffb40bc53e04cf68f8c8cf4` | 2551 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-init-id.js` | `e056fd74a89fe3fc76a3320addddd012cbab559f` | 2536 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-init-obj.js` | `bcc72d51bd7f5b20d3226f4d68ba6162e27aced9` | 2552 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-not-final-ary.js` | `fbead3414b6b19afd0775d8d18268c8a3b757780` | 2566 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-not-final-id.js` | `0c56098718867434e59e2084af1eb0ca3901133b` | 2552 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-not-final-obj.js` | `04dccb553bb018e2d06eed3e254a2b36dba9b0a4` | 2569 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-obj-id.js` | `3eaf12affe44ae2dcefacf3e41f5bfe3a34b5036` | 2628 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-ary-ptrn-rest-obj-prop-id.js` | `580e6e2474c06950d63c04cceae671998d06062d` | 2885 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-init-iter-close.js` | `a2d21847dd1cede7b4707de8b4ff6be66a92d155` | 2764 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-init-iter-get-err-array-prototype.js` | `62bd70103ce41ddb187792a26f30ae6d0a75a1b1` | 2607 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@79

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-init-iter-get-err.js` | `008df29b09e9284e46191b7a4e5efbb00c7f0b00` | 2442 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-init-iter-no-close.js` | `c06666e67b311c3c197609a02926b136a42f8d65` | 2766 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; function@76; C@84; method@85

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-name-iter-val.js` | `87e353dca5fef8b6d7edbafd59d21d84d3775689` | 3084 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-elem-init.js` | `151b7b08ffe6d397378bfe46359ed8576829e10f` | 2857 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-elem-iter.js` | `444eb1131f8de2e5151142e6c42f9f99d1042445` | 2828 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-elision-init.js` | `21a1ece74628a3a1240c6861a385d64329e48a31` | 2930 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-elision-iter.js` | `b2bbd718b6033953b68f3fc4857d47d738c70752` | 2833 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@74; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-empty-init.js` | `fbf6db5f0ce7e4bfbd77556ff205e21efb8df569` | 2972 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-empty-iter.js` | `deed39c61d055abe35d10f6d086b65cdcb6a032a` | 2811 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-rest-init.js` | `ee024c106e99c6204e60cffe81c503b47cc12c8d` | 2985 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-rest-iter.js` | `46d39662c1bfae026fc370bd431ffc5474fff5a7` | 3034 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-ary-val-null.js` | `6f2266bc2c4d07d6279f575ca51deab977cc9f71` | 2729 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-exhausted.js` | `93d288f4bed952a8b9b837ccdd44002e1f66e024` | 2780 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-fn-name-arrow.js` | `41c1c034a4b101984d2fb98513c8007dcafd1538` | 2848 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-fn-name-class.js` | `64fe77970db53bf6cd31202553d0ade605692567` | 2989 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-fn-name-cover.js` | `3ca7b8fa46c3b633d2ebce20727efc7fa81f037b` | 2963 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-fn-name-fn.js` | `ce09d93690ae66a059f35e47d06b215fd8df5a01` | 2909 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-fn-name-gen.js` | `7d3bd26dea33f5cf4d9a10d654dc6bc452050b1e` | 2941 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@77

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-hole.js` | `b54ce90f2d0c3b249a002134a865f8b123afbace` | 2715 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-skipped.js` | `6e132d3fa6dacbc53298f85a798387d25061ca61` | 2881 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@70; C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-throws.js` | `8d7c82bd21e18dd999a3c2072364e9f09e931f9a` | 2571 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-undef.js` | `98be07a5d7a97c1e724e375230923f421b8a8e79` | 2719 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-init-unresolvable.js` | `11660bc235389c3f88a86b48aa0001321717016b` | 2751 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-complete.js` | `0c185833ed1ccd049246e2568f10216a0b42ce84` | 2867 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-done.js` | `1a7875583c141220c2a681d3df0cdaaed4da6dc4` | 2620 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-step-err.js` | `413d2db6cee0131ece4ba0cf536e63383fa1a029` | 2697 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@73; C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-val-array-prototype.js` | `1dbf119c2c1c79a48c62dd9bf4e9923fd5aa10a9` | 3382 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@91; method@92

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-val-err.js` | `78d689ed440ffb6e59ab21d626de3d26381b5c1d` | 3061 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@77; function@84; C@90; method@91

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-id-iter-val.js` | `b687c1d24a9269b437cd8b9c1d91fcfd2dcd27fe` | 3110 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@81; method@82

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-id-init.js` | `8bee682ca78f414c57b5e02da1ce0a4737f65f95` | 2875 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-id.js` | `078ed2493ccf425e1c2257b07e6f201dd4fc134e` | 2897 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-prop-id-init.js` | `7c1e5eeba77a1a58ad2ebf187b92085dd2e2a9d7` | 3088 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-prop-id.js` | `8b0ea301c8f9ce54bdb257d4d4c5ae1913fcc514` | 3113 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-val-null.js` | `824f63ef6bfe066afadd3dd40311959ec8d37ed7` | 2738 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elem-obj-val-undef.js` | `a52286646a7f6e7f1ba2ba5b1ee78c29ed8bc0a4` | 2745 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elision-exhausted.js` | `8d536d8bf9cb978f5e32e86715c9fdebfa491be5` | 2737 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@80; method@81

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elision-step-err.js` | `478c54ebc6041b3b7319229ab62cb89df57ac0b5` | 2940 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@84

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-elision.js` | `974efa1e985849c62438e26ac5f6801d675ebaf1` | 3052 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@81; C@88; method@89

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-empty.js` | `2abad8546c37df3925727d4c0c0b003372245097` | 2498 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-ary-elem.js` | `9d05ce26f7ed6432d8eb5eba254886f6ae263354` | 3489 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@94; method@95

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-ary-elision.js` | `7985bce45441871099515341f6663b0ce639d506` | 3456 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@94; C@101; method@102

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-ary-empty.js` | `82489d494bb25ca59721eef2c633ef83ce5ac76c` | 2885 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-ary-rest.js` | `5532e679b064aa2aef69a9f11f598105b06fd0f3` | 2846 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-direct.js` | `23e357765e6fbfefcb7012ee37b5d88aa7d1d3f3` | 2626 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-elision-next-err.js` | `1fda23354a182ac7755a3ddcfbaac5fba029ff2c` | 2753 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-elision.js` | `bd1bd7237557ef11f5b08d90ed65eee3c94a0396` | 2973 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-exhausted.js` | `4dac070b95ffaf2a991d9303bd2251de3de8b890` | 2804 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-iter-step-err.js` | `789cce3fcc78393f6968692e358229fe4fb68cb1` | 2981 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@80

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id-iter-val-err.js` | `3f8c537878cd7e798153444b55758cd559685ca1` | 2932 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@72; function@79; C@85; method@86

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-id.js` | `9196483b26cf56e7653ff0d38965328902e95e63` | 2694 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-init-ary.js` | `becf98ed27d5ebbcf81172c2d487bd7c3098e8af` | 2599 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-init-id.js` | `cb38592a52414b3fe29db5e9be02f04978fa341c` | 2584 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-init-obj.js` | `8df5adb4b289d31018d23666f33f1cf97ead7ac7` | 2600 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-not-final-ary.js` | `47c21d6b6e74f7ac69b35cb34a88c5163bff482c` | 2614 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-not-final-id.js` | `aa6f0654d5fbfb1d0474a7df6d0ac00098c8c47e` | 2600 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-not-final-obj.js` | `c936e7d16ad5ff5013198b71436bf2e684997b6e` | 2617 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-obj-id.js` | `bfe824cd545da986e89c51bf1ca905466bfbf86b` | 2676 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-ary-ptrn-rest-obj-prop-id.js` | `8616c2eaf91f68f59805ae6b5b4375b43e6be7ce` | 2933 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-init-null.js` | `0df12743b0e5e2b304b6057344671cb4d4b56cc6` | 2305 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-init-undefined.js` | `5482a527dfa2e4d069f322b576ef1c33f216ab2f` | 2320 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-empty.js` | `1dcb78a2f8cd67b5c21281f1c63f7f17d4a14a5b` | 2524 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@67; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-get-value-err.js` | `0c8e610e1f7936ffcd2b9fdfc1906dbfff13fbae` | 2544 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-fn-name-arrow.js` | `db5d64d7c3792306ffe1925ad54736ce87e499df` | 2793 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-fn-name-class.js` | `8a6acdd653e360d38041f80367e7a7cefa06a6a9` | 2936 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-fn-name-cover.js` | `4c92b603eeb3a0cd139135e5bc4db2b84b886a51` | 2909 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-fn-name-fn.js` | `33fe20608eef4fce99cd7dfe9019e78bef05d0ff` | 2856 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-fn-name-gen.js` | `254a45fb305d6a4373da691ae8090ce7a01a9d03` | 2888 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-skipped.js` | `16d7f045a0e9e8532e5a7fa8431b1dc978d56af4` | 2787 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@69; C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-throws.js` | `7f26af06e09b738bdee1c6fa8e7ce5b304610b8f` | 2563 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-init-unresolvable.js` | `3f296a8bbce2574038611574bb0457a9f22e94af` | 2743 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-id-trailing-comma.js` | `09fc7b81f45df74097d65b8888012b21c96070ce` | 2466 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-list-err.js` | `100b54214c061d56fd9c2d1042a89b7021e802f9` | 2621 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-ary-init.js` | `ef6b6e1a8587af7222e6d08780a8fdcc17b0f919` | 2842 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-ary-trailing-comma.js` | `32afec681672c4ee62c6094cc45db46b63d65982` | 2478 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-ary-value-null.js` | `b9fec2f19947f6095b0ebc4620ef4b0ae65f8ace` | 2513 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-ary.js` | `d40c513688251d6cc6aa9f38f957d2169ea948b8` | 2751 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-eval-err.js` | `1f4fd2c0002913b957499d235bd956dcb8624cca` | 2436 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@66; C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-get-value-err.js` | `6d011ce82067a1eacd173a71a641d463439d3485` | 2614 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-init-skipped.js` | `533e81f45e7b97a3c492218b618f7f8b1046d2ce` | 3042 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-init-throws.js` | `331ef4acfd918990121b170be5bf7232a16e1f5a` | 2564 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-init-unresolvable.js` | `34e0fe5d3f01d32dbdab6f9a9a00ed2f50ec7478` | 2745 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-init.js` | `c6cf8b08a77e191909fbbc2bce10931a6e43547c` | 2546 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id-trailing-comma.js` | `657116867022bda4de25e6f2ef4e7a790e35aa36` | 2539 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-id.js` | `4fe67798877847e8602beb2ab3e04be32ed0fa32` | 2528 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-obj-init.js` | `9012ab99f98a3bf9e3f008222d6edea8c70dbd1a` | 2870 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-obj-value-null.js` | `2511427ef0dd9a1b23944c264828451f47998487` | 2527 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-obj-value-undef.js` | `e44cb5afa4c5d88cb2dccfa1fd8d490857f0b0d7` | 2509 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-prop-obj.js` | `fc5fe12ffb2f6813721286885b72d3973da8cef3` | 2771 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-rest-getter.js` | `6c44ed25f6287be62b04d62ec4d1b15c3cfe71eb` | 2509 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@63; method@64

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-rest-skip-non-enumerable.js` | `421c74c656aa8427bdf4e55b5f2f1d9597405cfc` | 2691 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64; method@65

`js/src/tests/test262/language/statements/class/dstr/meth-static-dflt-obj-ptrn-rest-val-obj.js` | `920a42ae46e68699b583664609b58afca6e23521` | 2652 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@62; method@63

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-init-null.js` | `1dcebc3119c0b5e9a0b838b53fe7fedf7e7f3753` | 2257 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-init-undefined.js` | `0d4062380621ef238f28da52cf302c928cb2199b` | 2272 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@66; method@67

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-empty.js` | `430b92a74834a4566c244cd99382b2375ed09b68` | 2476 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@67; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-get-value-err.js` | `8a0bbac390004e5c0f068ca627215e622cf3091e` | 2496 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-fn-name-arrow.js` | `23866529edc55ff68581fe11171cbf2a7147a1d2` | 2745 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-fn-name-class.js` | `38873156c9189d677c52972af486b36e0a631cdc` | 2888 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-fn-name-cover.js` | `2a32fa47d0e4a80837c18ae119436cfddf33c965` | 2861 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-fn-name-fn.js` | `0eb3c8a31d654fa280c39cea625719c65700939f` | 2808 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-fn-name-gen.js` | `0c91023450e17ce30d49051c4af0e2e3bc488cd4` | 2840 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@76

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-skipped.js` | `e1bd4dd9518b59787480621b7ea17d6441f5eb5b` | 2739 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@69; C@74; method@75

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-throws.js` | `8527fddbf54f4a49b008a93c109bb4f4eb1eebb4` | 2515 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-init-unresolvable.js` | `02566d98d9254eb6d9f247b05ef63252a5212609` | 2695 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-id-trailing-comma.js` | `293689da4c6b278f2dcad98dda220b1978e646df` | 2418 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-list-err.js` | `99f50db21a329385dffae6f5173b8460eeb76f08` | 2573 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@68; C@72; method@73

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-ary-init.js` | `ab3d9d65c778f55902a077a6575ee37a1e750f45` | 2794 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-ary-trailing-comma.js` | `958a69030d7a24bbb1713df084b694d18b062078` | 2430 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-ary-value-null.js` | `ab18550b2a9bd05e721f6d7c85ed740d146b8e25` | 2465 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-ary.js` | `c650a387f9439c46e24941d3f6d017d9818f4602` | 2703 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-eval-err.js` | `65afb213f182cf497d1cc1a36be30af202e5833e` | 2388 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@66; C@70; method@71

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-get-value-err.js` | `77c09b30e624e0ccdae5a5072b1b4e6181c9591c` | 2566 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-init-skipped.js` | `e98bd1afb5a141a4b3a8155dda2087bbd1b00542` | 2994 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@68; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-init-throws.js` | `bf83fa005ba0d4f48c6ab7c7bd532c40b99b4f7d` | 2516 bytes | test-path,source | UTF-8 | mode 100644
Declarations: thrower@69; C@73; method@74

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-init-unresolvable.js` | `2ee5ed2af0d9cacc8758dcbfd366d52b748d92f2` | 2697 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@78

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-init.js` | `3cd7d23406b3e7eacf34cf46282b258211fab6b0` | 2498 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id-trailing-comma.js` | `b1c8a4d136b88c8b7e13f9a8961ac72dc721f401` | 2491 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-id.js` | `3ee0df407fea822149e1e5ac7eca8f2d1b89171c` | 2480 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-obj-init.js` | `49f17c6bbc7431d56e862b15e0420a9d76c71800` | 2822 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@72

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-obj-value-null.js` | `ae37b91542916f8f638ad92d79137e59af0db1a5` | 2479 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-obj-value-undef.js` | `da1f92780473973ce017a25767f3a7fc95ae37cf` | 2461 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@68; method@69

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-prop-obj.js` | `fea57dfe98d37415782f61c3e9d6955cfe946ab0` | 2723 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@69; method@70

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-rest-getter.js` | `a770ea90a571155aa68c6e630f3a2beffca3e339` | 2461 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@63; method@64

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-rest-skip-non-enumerable.js` | `8072fe7119d0d2ecbd146bc3ddfc7547d6a137e6` | 2643 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@64; method@65

`js/src/tests/test262/language/statements/class/dstr/meth-static-obj-ptrn-rest-val-obj.js` | `32f93bfb90ba47e6e05e85b710fc22ed31ced7af` | 2604 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@62; method@63

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-init-iter-close.js` | `5c392dcaa9c19928d0c8e6d1b2ddf4b7cec7fcc3` | 2998 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@75; function@78; C@86; method@92

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-init-iter-no-close.js` | `c7afd6535434b1c84cb4c6616db199bb0658b9fb` | 3000 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@75; function@78; C@86; method@92

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-name-iter-val.js` | `b6c8621b1abdbb22b2dc7065a623fa16e3ac643b` | 3318 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@91

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-elem-init.js` | `b766f517944257eba5d2cfee3fd53c6004d5e896` | 3091 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-elem-iter.js` | `79277a3f43b1e0e93b9e4c47e128cf32bce18344` | 3062 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-elision-init.js` | `6cf6800fa68adf8537df6894ae5aaf0a256c3e77` | 3152 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@76; C@83; method@90

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-elision-iter.js` | `7ce755b4bb4c5b3c2bc1420d3f8d03d66e158964` | 3055 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@76; C@81; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-empty-init.js` | `4c0acc17f82d1e8b1d1da0f620377a2e52781b60` | 3194 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@86

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-empty-iter.js` | `ee466b298134ef61b701268dc46a9619b2713e9c` | 3045 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-rest-init.js` | `ade7fd21b93bbc87c571022e5b328824ccd0e6e8` | 3219 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-ary-rest-iter.js` | `c74564f74e74bbb43993a9ca57236e9196dfd1df` | 3268 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@90

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-exhausted.js` | `022cfb465a634d4cf77030c00efaa19bc9cb30d4` | 3014 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@82

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-fn-name-arrow.js` | `4a73424ab567918bea8d9fc216df464f990dbe56` | 3082 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-fn-name-class.js` | `abba0898ec4e0b84b42abeca77405944c21a6d77` | 3223 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-fn-name-cover.js` | `2ac4a448a90d02d0d26248b774998e85d0f781b1` | 3197 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-fn-name-fn.js` | `33ea96854c2e8dfbce41ca83583d9484d2c875b9` | 3143 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-fn-name-gen.js` | `f9305418c340cbfe664138afa3ccafdf6d16449f` | 3163 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-hole.js` | `5ead11567a47ef878f43aa6ccd17ad64ad3d8cf4` | 2949 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@78

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-skipped.js` | `4db37e6b11a35d37e96e5ed07640d363e2d43df5` | 3115 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@72; C@77; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-init-undef.js` | `b4f31dcd6c93d5764947a4850a6c08c2462ba00b` | 2953 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@81

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-iter-complete.js` | `079828c06a8328e99629ce93def8924ffadf8b69` | 3101 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-iter-done.js` | `d58b13b9e3ef8fb1b7fcd843cb055028ed8c9f50` | 2854 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-iter-val-array-prototype.js` | `d2234a84ddc859171d369c2e418642bd3a2a9ed3` | 3604 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@93; method@101

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-id-iter-val.js` | `b67ef130027c768f6862e49e11f728fe5af08f50` | 3344 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@91

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-obj-id-init.js` | `4ebaa3fa2a8b22d02b929b5357949d46fcf3806e` | 3109 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-obj-id.js` | `91a9a0a15790e3b3b7f52462e962c64b26fd3e54` | 3131 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-obj-prop-id-init.js` | `c80fbbeae065c86536e6cd4611a27f82540e0443` | 3322 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@93

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elem-obj-prop-id.js` | `8df54c1df551ebf2d04383b36a6c4e3d73a6dbba` | 3347 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@93

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elision-exhausted.js` | `744d5fc2c897d9bee1a25654034056704c10ae93` | 2959 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@82; method@88

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-elision.js` | `5c9a25c3701c38b715cc2aa4b8490bad200469a1` | 3274 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@83; C@90; method@97

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-empty.js` | `73d1f05312bb770a6584b3e14cb5b7771b46d545` | 2720 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-ary-elem.js` | `e75150ffba6b2d80a9e27dbd19b41f41e7556723` | 3723 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@96; method@104

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-ary-elision.js` | `fdc96022588a55776d4d080eeacc9b3890b9c7df` | 3678 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@96; C@103; method@110

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-ary-empty.js` | `df1a672ec384c027dd08356a37998eadfe77212a` | 3107 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@87; method@93

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-ary-rest.js` | `5dd8852652ce234964f296da361271be25991df2` | 3080 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@89

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-id-direct.js` | `85c1ac7d593ddcba8668b87c2af8cd42d92c1d6e` | 2860 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-id-elision.js` | `7dbcd84d6a9b89cdc628ee1d979df5b7c5fe7346` | 3207 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-id-exhausted.js` | `f2838c5b39920701055c3ea8042bc6e4e27ac0c4` | 3038 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@81

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-id.js` | `770a9a20eca7fd2932ac2686c68d2db58deb3ac7` | 2928 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@82

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-init-ary.js` | `c2d7216d9adc65a5d4ea60ce4a85e675e3d681d9` | 2833 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-init-id.js` | `c7549dac21f91c76b991460e022a21e8cfaa5025` | 2818 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-init-obj.js` | `a10e288457199ab3a3d5e6899083d6cf2fb10222` | 2834 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-not-final-ary.js` | `8ef03afce7548b1d94d3ec58b915ce724eb1cb21` | 2848 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-not-final-id.js` | `1c358e07fe2b09b5f14c842ac1e4e3cb5412c697` | 2834 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-not-final-obj.js` | `166f55992c98c60f1c837bba32c7ee17c63723b3` | 2851 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-obj-id.js` | `96b737df5d5340177998885922f9b095897b8fff` | 2910 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@82

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-ary-ptrn-rest-obj-prop-id.js` | `3924bf84cfe55ca83bda5467b91373c28275d38b` | 3167 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@89

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-init-iter-close.js` | `14cde88b29f03afbe68889517ab7bf799a0dbf27` | 3047 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@75; function@78; C@86; method@92

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-init-iter-no-close.js` | `3d6c1e35dbe82d47436db79eeeb587bda64110a0` | 3049 bytes | test-path,source | UTF-8 | mode 100644
Declarations: function@75; function@78; C@86; method@92

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-name-iter-val.js` | `54f160cf23225d3d959a87419dcb60dd182260a8` | 3367 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@91

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-elem-init.js` | `3823e65211c1fb6a4cc256d83ebd57cb79e22bae` | 3140 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-elem-iter.js` | `24c7ad7b418a80f158f30dcb390a7f5868ad6309` | 3111 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-elision-init.js` | `4d53cf4f3b29201ad75b7a8c4c60303134eb0ced` | 3201 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@76; C@83; method@90

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-elision-iter.js` | `f8963641df25241fa374b4e2ca8c21fe30e9765e` | 3104 bytes | test-path,source | UTF-8 | mode 100644
Declarations: g@76; C@81; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-empty-init.js` | `3e6b0f7fc70e1327a858da9d6cd589cc14e9beaa` | 3243 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@86

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-empty-iter.js` | `88ee6b1757b583922d7064868dc8ce20348ae01b` | 3094 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-rest-init.js` | `57e549ed5e1d5fa6669f6cadaedd09b8c5d1d979` | 3268 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-ary-rest-iter.js` | `ddc9a9ad8e2b8d37a201362d3ac7af78bc9a9a6d` | 3317 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@90

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-exhausted.js` | `8720e6173acb26dd7e7c388e922bff4ed88871e0` | 3063 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@76; method@82

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-fn-name-arrow.js` | `b6a784c5f551750ef59f0410ccf54d9464b9289d` | 3131 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-fn-name-class.js` | `de6eba1e62dbfd0591d0e0db70b1ba49372bab1f` | 3272 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-fn-name-cover.js` | `a73ce6334433261d6e588462be6d37552966ca2b` | 3246 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-fn-name-fn.js` | `12632d7677942d95f75a821d709ce22a2f9d3e91` | 3192 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@77; method@84

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-fn-name-gen.js` | `ffdbd3602b2fdad63e5bc86f5e24f4de688a7885` | 3212 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@78; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-hole.js` | `9523fa58b694ac9595f401d854bd6b9c9a52fa9f` | 2998 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@71; method@78

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-skipped.js` | `b55a511180269c47351de5a7824a458b7ae0d097` | 3164 bytes | test-path,source | UTF-8 | mode 100644
Declarations: counter@72; C@77; method@87

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-init-undef.js` | `fc619299e876500c8667b960ee6d4b51d645cc37` | 3002 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@81

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-iter-complete.js` | `e7d42ad2808bf5426e28b242724a63b8ab9e79e6` | 3150 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@79; method@85

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-iter-done.js` | `7248cb7412a096c527793af6955521070c4a9cbe` | 2903 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@74; method@80

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-iter-val-array-prototype.js` | `2d918abaa8127b33acb6fc1c13fb76b23f9a1436` | 3653 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@93; method@101

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-id-iter-val.js` | `de945caba904b217d6c28ad7989bbb9eb0112c3d` | 3393 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@83; method@91

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-obj-id-init.js` | `da7b8871d65baad9451129f737d6273e98a2be0c` | 3158 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-obj-id.js` | `7769013735495a0fc61af2c76a35ab146564ea9e` | 3180 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@83

`js/src/tests/test262/language/statements/class/dstr/private-gen-meth-dflt-ary-ptrn-elem-obj-prop-id-init.js` | `c56193ac1788e0de8c58967c02a9baeb0b1a7cdf` | 3371 bytes | test-path,source | UTF-8 | mode 100644
Declarations: C@75; method@93

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.

## Retrieval correction

This copy preserves the source map in [734891f6-9ff6-4a31-bcfe-0a6ef34285c0.md](734891f6-9ff6-4a31-bcfe-0a6ef34285c0.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `4002eb47b8e5270e0749efb4a8035e2b55f472b848bfeab8368eedfaab76cb12`.
