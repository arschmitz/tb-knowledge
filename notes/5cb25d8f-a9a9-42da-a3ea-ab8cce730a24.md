<!-- knowledge: {"repository": "git:314d8065c5ad68c7e5c5f92d", "at": "2026-10-13T04:22:06.018534+00:00", "paths": ["modules/zlib/src/crc32.h", "modules/zlib/src/deflate.c", "modules/zlib/src/deflate.h", "modules/zlib/src/gzclose.c", "modules/zlib/src/gzguts.h", "modules/zlib/src/gzlib.c", "modules/zlib/src/gzread.c", "modules/zlib/src/gzwrite.c", "modules/zlib/src/infback.c", "modules/zlib/src/inffast.c", "modules/zlib/src/inffast.h", "modules/zlib/src/inffixed.h", "modules/zlib/src/inflate.c", "modules/zlib/src/inflate.h", "modules/zlib/src/inftrees.c", "modules/zlib/src/inftrees.h", "modules/zlib/src/mozzconf.h", "modules/zlib/src/trees.c", "modules/zlib/src/trees.h", "modules/zlib/src/uncompr.c", "modules/zlib/src/zconf.h", "modules/zlib/src/zlib.h", "modules/zlib/src/zutil.c", "modules/zlib/src/zutil.h"], "source": {"reference": "Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "revision": "1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b", "status": "provisional", "study": "architecture-study-20261013"}} -->
# firefox/modules native and TypeScript syntax map 189

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### modules/zlib/src/crc32.h

Blob: `137df68d616c5ed38913579ba37b4e4c533fa903`. Grammar: cpp. Status: contains-errors.


### modules/zlib/src/deflate.c

Blob: `d7d2c7c1ee4e84061f94bdd4094a76f05d2bb15a`. Grammar: c. Status: contains-errors.

- include "deflate.h" @52
- enum_specifier block_state @63-68
- struct_specifier config_s @98-104
- function_definition slide_hash @187-210
- function_definition read_buf @219-240
- function_definition if @232-234
- function_definition fill_window @252-376
- function_definition deflateInit_ @379-384
- function_definition deflateInit2_ @387-533
- function_definition if @429-432
- struct_specifier internal_state @443-443
- function_definition deflateStateCheck @538-556
- function_definition deflateSetDictionary @559-622
- function_definition deflateGetDictionary @625-641
- function_definition lm_init @682-701
- function_definition deflateReset @704-711
- function_definition deflateSetHeader @714-719
- function_definition deflatePending @722-734
- function_definition deflateUsed @737-742
- function_definition deflatePrime @745-771
- function_definition deflateParams @774-816
- function_definition deflateTune @819-830
- function_definition deflateBound_z @856-928
- function_definition deflateBound @929-932
- function_definition putShortMSB @939-942
- function_definition flush_pending @950-968
- function_definition deflate @981-1290
- function_definition deflateEnd @1293-1310
- function_definition deflateCopy @1317-1377
- struct_specifier internal_state @1338-1338
- function_definition longest_match @1389-1530
- function_definition longest_match @1537-1586
- function_definition check_match @1598-1621
- function_definition deflate_stored @1668-1848
- function_definition deflate_fast @1857-1948
- function_definition deflate_slow @1956-2076
- function_definition deflate_rle @2084-2149
- function_definition deflate_huff @2155-2185

### modules/zlib/src/deflate.h

Blob: `0732ba83adbdae4e874ee4e66647a8df9dc5f7f1`. Grammar: cpp. Status: contains-errors.

- include "zutil.h" @16
- struct_specifier ct_data_s @72-81
- struct_specifier static_tree_desc_s @88-88
- struct_specifier tree_desc_s @90-94
- struct_specifier internal_state @104-288
- struct_specifier ct_data_s @202-202
- struct_specifier ct_data_s @203-203
- struct_specifier ct_data_s @204-204
- struct_specifier tree_desc_s @206-206
- struct_specifier tree_desc_s @207-207
- struct_specifier tree_desc_s @208-208

### modules/zlib/src/gzclose.c

Blob: `48d6a86f04b6ea57f7158c19694023a9948438da`. Grammar: c. Status: contains-errors.

- include "gzguts.h" @6
- function_definition gzclose @11-23

### modules/zlib/src/gzguts.h

Blob: `266305debc8bac945863ed844adec8d7994ba3f1`. Grammar: cpp. Status: contains-errors.

- include <stdio.h> @32
- include "zlib.h" @33
- include <string.h> @35
- include <stdlib.h> @36
- include <limits.h> @37
- include <fcntl.h> @43
- include <stddef.h> @46
- include <io.h> @50
- include <sys/stat.h> @51
- include <windows.h> @128
- include <errno.h> @132
- struct_specifier gz_state @170-203
- struct_specifier gzFile_s @172-172

### modules/zlib/src/gzlib.c

Blob: `7a37a96cf0a32c907678967f5acc51e2280f24c6`. Grammar: c. Status: contains-errors.

- include "gzguts.h" @6
- function_definition gz_strwinerror @29-64
- function_definition gz_reset @69-84
- function_definition if @250-263
- function_definition gzopen @288-290
- function_definition gzopen64 @293-295
- function_definition gzdopen @298-312
- function_definition gzopen_w @316-318
- function_definition gzbuffer @322-343
- function_definition gzrewind @346-364
- function_definition gzseek64 @367-435
- function_definition gzseek @438-443
- function_definition gztell64 @446-458
- function_definition gztell @461-466
- function_definition gzoffset64 @469-487
- function_definition gzoffset @490-495
- function_definition gzeof @498-510
- function_definition gzerror @513-528
- function_definition gzclearerr @531-547
- function_definition gz_error @555-590
- function_definition gz_intmax @596-609

### modules/zlib/src/gzread.c

Blob: `8b3e369dac10575de9467e13bf6d964cdc07aeba`. Grammar: c. Status: contains-errors.

- include "gzguts.h" @6
- function_definition gz_load @18-47
- function_definition gz_avail @56-82
- function_definition gz_look @93-170
- function_definition gz_decomp @180-240
- function_definition gz_fetch @248-277
- function_definition gz_skip @281-309
- function_definition gz_read @317-393
- function_definition gzread @396-436
- function_definition gzfread @439-465
- function_definition gzgetc @473-498
- function_definition gzgetc_ @500-502
- function_definition gzungetc @505-563
- function_definition gzgets @566-624
- function_definition gzdirect @627-642
- function_definition gzclose_r @645-668

### modules/zlib/src/gzwrite.c

Blob: `13a3700a83c7ca7f35608eda1f68b933c8e2e343`. Grammar: c. Status: contains-errors.

- include "gzguts.h" @6
- function_definition gz_init @11-57
- function_definition gz_comp @65-148
- function_definition gz_zero @154-182
- function_definition gz_write @188-252
- function_definition gzwrite @255-277
- function_definition gzfwrite @280-304
- function_definition gzputc @307-347
- function_definition gzputs @350-372
- function_definition gz_vacate @382-396
- include <stdarg.h> @400
- function_definition gzvprintf @403-485
- function_definition gzprintf @487-495
- function_definition gzprintf @500-598
- function_definition gzflush @603-627
- function_definition gzsetparams @630-664
- function_definition gzclose_w @667-700

### modules/zlib/src/infback.c

Blob: `e6443feb45e1be8a0a7bc3f2d63d208acd5873e9`. Grammar: c. Status: contains-errors.

- include "zutil.h" @13
- include "inftrees.h" @14
- include "inflate.h" @15
- include "inffast.h" @16
- function_definition inflateBackInit_ @25-64
- struct_specifier inflate_state @28-28
- struct_specifier inflate_state @51-51
- struct_specifier inflate_state @52-52
- struct_specifier internal_state @55-55
- function_definition inflateBack @191-572
- struct_specifier inflate_state @193-193
- struct_specifier inflate_state @211-211
- function_definition inflateBackEnd @574-581

### modules/zlib/src/inffast.c

Blob: `d1657f3f30348aedf10add2838004a7ea0344c39`. Grammar: c. Status: contains-errors.

- include "zutil.h" @6
- include "inftrees.h" @7
- include "inflate.h" @8
- include "inffast.h" @9
- function_definition inflate_fast @50-305
- struct_specifier inflate_state @51-51
- struct_specifier inflate_state @78-78

### modules/zlib/src/inffast.h

Blob: `49c6d156c5c652dbd9e2e6aff90e20eb279a2b37`. Grammar: cpp. Status: contains-errors.


### modules/zlib/src/inffixed.h

Blob: `05ce88e4ff5cd4e7ffe05d3a8309af1bf3b0e989`. Grammar: cpp. Status: syntax-clean.


### modules/zlib/src/inflate.c

Blob: `5f5d4922b7157792c817b622acfa95fecf1ba8b2`. Grammar: c. Status: contains-errors.

- include "zutil.h" @83
- include "inftrees.h" @84
- include "inflate.h" @85
- include "inffast.h" @86
- function_definition inflateStateCheck @88-98
- struct_specifier inflate_state @89-89
- struct_specifier inflate_state @93-93
- function_definition inflateResetKeep @100-123
- struct_specifier inflate_state @101-101
- struct_specifier inflate_state @104-104
- function_definition inflateReset @125-134
- struct_specifier inflate_state @126-126
- struct_specifier inflate_state @129-129
- function_definition inflateReset2 @136-171
- struct_specifier inflate_state @138-138
- struct_specifier inflate_state @142-142
- function_definition inflateInit2_ @173-212
- struct_specifier inflate_state @176-176
- struct_specifier inflate_state @197-197
- struct_specifier inflate_state @198-198
- struct_specifier inflate_state @200-200
- struct_specifier internal_state @202-202
- function_definition inflateInit_ @214-217
- function_definition inflatePrime @219-236
- struct_specifier inflate_state @220-220
- struct_specifier inflate_state @225-225
- function_definition updatewindow @252-296
- struct_specifier inflate_state @253-253
- struct_specifier inflate_state @256-256
- struct_specifier inflate_state @475-475
- struct_specifier inflate_state @498-498
- struct_specifier inflate_state @1156-1156
- struct_specifier inflate_state @1159-1159
- struct_specifier inflate_state @1169-1169
- struct_specifier inflate_state @1173-1173
- struct_specifier inflate_state @1189-1189
- struct_specifier inflate_state @1195-1195
- struct_specifier inflate_state @1220-1220
- struct_specifier inflate_state @1224-1224
- struct_specifier inflate_state @1269-1269
- struct_specifier inflate_state @1273-1273
- struct_specifier inflate_state @1321-1321
- struct_specifier inflate_state @1324-1324
- struct_specifier inflate_state @1329-1329
- struct_specifier inflate_state @1330-1330
- struct_specifier inflate_state @1336-1336
- struct_specifier inflate_state @1339-1339
- struct_specifier inflate_state @1340-1340
- struct_specifier inflate_state @1342-1342
- struct_specifier inflate_state @1355-1355
- struct_specifier internal_state @1366-1366
- struct_specifier inflate_state @1371-1371
- struct_specifier inflate_state @1374-1374
- struct_specifier inflate_state @1386-1386
- struct_specifier inflate_state @1389-1389
- struct_specifier inflate_state @1398-1398
- struct_specifier inflate_state @1402-1402
- struct_specifier inflate_state @1409-1409
- struct_specifier inflate_state @1411-1411

### modules/zlib/src/inflate.h

Blob: `f758e0dcc18dc1dcfd875d3df98d71aa5743d349`. Grammar: cpp. Status: contains-errors.

- enum_specifier inflate_mode @20-53
- struct_specifier inflate_state @82-126

### modules/zlib/src/inftrees.c

Blob: `dcbc64e05b15c1083452787519041c0df3004421`. Grammar: c. Status: contains-errors.

- include "zutil.h" @15
- include "inftrees.h" @16
- include "inflate.h" @17
- function_definition inflate_table @46-311
- function_definition buildtables @327-349
- include "inffixed.h" @351
- function_definition inflate_fixed @364-372
- struct_specifier inflate_state @364-364
- include <stdio.h> @375
- function_definition main @386-423
- struct_specifier inflate_state @388-388

### modules/zlib/src/inftrees.h

Blob: `84d053697cd881db2f1d3a303e238a0cce0bf886`. Grammar: cpp. Status: contains-errors.

- struct_specifier code @24-28
- enum_specifier codetype @54-58
- struct_specifier inflate_state @63-63
- struct_specifier inflate_state @64-64

### modules/zlib/src/mozzconf.h

Blob: `cbb7f029581d1a4f52b6ed263402f863a50fdac1`. Grammar: cpp. Status: syntax-clean.


### modules/zlib/src/trees.c

Blob: `8e4da01e9f4790b18c06b8ebbeb57d15c46c5c17`. Grammar: c. Status: contains-errors.

- include "deflate.h" @37
- include <ctype.h> @40
- include "trees.h" @114
- struct_specifier static_tree_desc_s @117-123
- function_definition bi_reverse @154-161
- function_definition bi_flush @166-176
- function_definition bi_windup @181-193
- function_definition gen_codes @203-232
- function_definition send_bits @253-271
- function_definition tr_static_init @295-374
- include <stdio.h> @381
- function_definition gen_trees_header @388-434
- function_definition init_block @440-451
- function_definition _tr_init @456-478
- function_definition pqdownheap @509-528
- function_definition gen_bitlen @540-613
- include <stdio.h> @616
- function_definition build_tree @627-706
- function_definition scan_tree @712-747
- function_definition send_tree @753-794
- function_definition build_bl_tree @800-826
- function_definition send_all_trees @833-855
- function_definition _tr_stored_block @860-875
- function_definition _tr_flush_bits @880-882
- function_definition _tr_align @888-895
- function_definition compress_block @900-951
- function_definition detect_data_type @966-991
- function_definition _tr_tally @1095-1119

### modules/zlib/src/trees.h

Blob: `d35639d82a27807e49ea35c334f8bbcf64720f82`. Grammar: cpp. Status: contains-errors.


### modules/zlib/src/uncompr.c

Blob: `2195e785506457dbcdc72ac9a31c8b1951e3e1c5`. Grammar: c. Status: contains-errors.

- include "zlib.h" @9
- function_definition uncompress2_z @29-82
- function_definition uncompress2 @83-91
- function_definition uncompress_z @92-96
- function_definition uncompress @97-101

### modules/zlib/src/zconf.h

Blob: `3842decc17eb702e74298e67eb88fa6c2ff976e8`. Grammar: cpp. Status: contains-errors.

- include "mozzconf.h" @12
- include <stddef.h> @267
- include <windows.h> @367
- include <limits.h> @433
- include <sys/types.h> @459
- include <stdarg.h> @465
- include <stddef.h> @471
- include <unistd.h> @493
- include <unixio.h> @495

### modules/zlib/src/zlib.h

Blob: `a57d336134217efeddab550ed53df4b89adeca5d`. Grammar: cpp. Status: contains-errors.

- include <zconf.h> @35
- include "zconf.h" @37
- struct_specifier internal_state @88-88
- struct_specifier z_stream_s @90-110
- struct_specifier internal_state @100-100
- struct_specifier gz_header_s @118-133
- struct_specifier gzFile_s @1354-1354
- struct_specifier gzFile_s @1956-1960

### modules/zlib/src/zutil.c

Blob: `4ea02a9c3644eebd10b2b9aec238689c2c32a93c`. Grammar: c. Status: contains-errors.

- include "zutil.h" @8
- include "gzguts.h" @10
- function_definition zlibVersion @27-29
- function_definition zlibCompileFlags @31-121
- include <stdlib.h> @124
- function_definition z_error @130-133
- function_definition zError @139-141
- function_definition zmemcpy @153-160
- function_definition zmemcmp @162-170
- function_definition zmemzero @172-179
- struct_specifier ptr_table_s @203-206
- function_definition zcalloc @216-239
- function_definition zcfree @241-262
- function_definition zcalloc @277-280
- function_definition zcfree @282-285
- function_definition zcalloc @300-304
- function_definition zcfree @306-309

### modules/zlib/src/zutil.h

Blob: `a9bc23ca62956e59b6ee304b0b6889f3ca776d7b`. Grammar: cpp. Status: contains-errors.

- include "zlib.h" @22
- include <stddef.h> @26
- include <string.h> @28
- include <stdlib.h> @29
- include <limits.h> @50
- include <alloc.h> @109
- include <malloc.h> @112
- include <malloc.h> @144
- include <stdio.h> @228
- include <stdatomic.h> @270
- struct_specifier z_once_t @271-274
- function_definition z_once @282-292
- struct_specifier z_once_s @298-301
- function_definition test_and_set @306-312
- function_definition z_once @315-325

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.
