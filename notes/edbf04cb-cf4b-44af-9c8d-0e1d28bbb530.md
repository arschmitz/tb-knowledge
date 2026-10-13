<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:22:06.018534+00:00","paths":["dom"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013","portableCopies":["0be6f336983d479b61b75d5d3e09708bd86bbc41f18134759714bb025e79e39a"],"sourceAt":"2026-10-13T04:22:06.018534+00:00","correctionOf":"notes/b0055830-f396-4d1a-80b7-49ccb6a36025.md"}} -->
# firefox/dom native and TypeScript syntax map 56

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. Parser versions: {"tree-sitter": "0.25.2", "tree-sitter-c": "0.24.2", "tree-sitter-cpp": "0.23.4", "tree-sitter-rust": "0.24.2", "tree-sitter-java": "0.23.5", "tree-sitter-typescript": "0.23.2"}.

Tree-sitter parses written syntax without executing it. Entries identify declarations and function bodies with source ranges. Names can be unqualified or inferred from an assignment. They do not resolve overloaded symbols or runtime receivers. C/C++ header files use the C++ grammar. Macros and build flags are not expanded. `contains-errors` means the tree has error or missing nodes; its entries remain partial candidates. A clean syntax tree is not proof that the file compiles. Objective-C, Kotlin, IDL, and embedded code are outside this parser pass and remain in the structural census.

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_addition.cache.ts

Blob: `f179d48a131bfc1733ae45ca2cdec37bf9ee8643`. Grammar: typescript. Status: syntax-clean.

- arrow_function additionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function additionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_addition.spec.ts

Blob: `b184ce41faa2cebddc4f7734e225400c53312a26`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-30
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-47
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-66
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-116
- arrow_function (anonymous) @126-126
- arrow_function (anonymous) @127-141

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_comparison.cache.ts

Blob: `c0c0d4f8a4a65111ab203e7ca1af4f04c03ad446`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @11-33
- arrow_function (anonymous) @23-30
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @36-44
- arrow_function truthFunc @37-39
- arrow_function (anonymous) @41-43
- arrow_function (anonymous) @45-53
- arrow_function truthFunc @46-48
- arrow_function (anonymous) @50-52
- arrow_function (anonymous) @54-62
- arrow_function truthFunc @55-57
- arrow_function (anonymous) @59-61
- arrow_function (anonymous) @63-71
- arrow_function truthFunc @64-66
- arrow_function (anonymous) @68-70
- arrow_function (anonymous) @72-80
- arrow_function truthFunc @73-75
- arrow_function (anonymous) @77-79
- arrow_function (anonymous) @81-89
- arrow_function truthFunc @82-84
- arrow_function (anonymous) @86-88
- arrow_function (anonymous) @90-98
- arrow_function truthFunc @91-93
- arrow_function (anonymous) @95-97
- arrow_function (anonymous) @99-107
- arrow_function truthFunc @100-102
- arrow_function (anonymous) @104-106
- arrow_function (anonymous) @108-116
- arrow_function truthFunc @109-111
- arrow_function (anonymous) @113-115
- arrow_function (anonymous) @117-125
- arrow_function truthFunc @118-120
- arrow_function (anonymous) @122-124
- arrow_function (anonymous) @126-134
- arrow_function truthFunc @127-129
- arrow_function (anonymous) @131-133
- arrow_function (anonymous) @135-143
- arrow_function truthFunc @136-138
- arrow_function (anonymous) @140-142

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_comparison.spec.ts

Blob: `96070776609b3d287cc014dd61ed78639e2a60cf`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-24
- arrow_function (anonymous) @26-32
- arrow_function (anonymous) @42-43
- arrow_function (anonymous) @45-51
- arrow_function (anonymous) @61-62
- arrow_function (anonymous) @64-70
- arrow_function (anonymous) @80-81
- arrow_function (anonymous) @83-89
- arrow_function (anonymous) @99-100
- arrow_function (anonymous) @102-108
- arrow_function (anonymous) @118-119
- arrow_function (anonymous) @121-127

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_division.cache.ts

Blob: `95590ca46789e0305c57331903db325daed6feab`. Grammar: typescript. Status: syntax-clean.

- arrow_function divisionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function divisionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_division.spec.ts

Blob: `c4b473794d11b73823f4ba71f3f70c564b1f98eb`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-30
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-47
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-66
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-116
- arrow_function (anonymous) @126-126
- arrow_function (anonymous) @127-141

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_addition.cache.ts

Blob: `a670b08b0740e882dd44cc87b119c14bc57e852b`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_addition.spec.ts

Blob: `f55a545d74aaa138f31cf7c79b21012cc50eaec0`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-44
- arrow_function (anonymous) @54-58
- arrow_function (anonymous) @60-75

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_matrix_multiplication.cache.ts

Blob: `a31813abb3ba3f54a6a683bce020b37eea4c2fe4`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-21
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @10-19
- arrow_function (anonymous) @11-18
- arrow_function (anonymous) @23-23

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_matrix_multiplication.spec.ts

Blob: `14a81b4d913508a926a3daf318cd940792da9ca6`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-28
- arrow_function (anonymous) @30-50
- arrow_function (anonymous) @60-64
- arrow_function (anonymous) @66-86

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_scalar_multiplication.cache.ts

Blob: `f902a1c8bc8d40836a20b1527432eaf3db37f911`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21
- arrow_function (anonymous) @25-37
- arrow_function (anonymous) @26-36
- arrow_function (anonymous) @27-36
- arrow_function (anonymous) @28-35
- arrow_function (anonymous) @39-39

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_scalar_multiplication.spec.ts

Blob: `0b6cdfcd10f23896b0b7913d87a4181a275aea73`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-46
- arrow_function (anonymous) @56-60
- arrow_function (anonymous) @62-79
- arrow_function (anonymous) @89-93
- arrow_function (anonymous) @95-112

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_subtraction.cache.ts

Blob: `a6edcf7fe500bd64b23e6a15b2fd43f1fe2b76e1`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_subtraction.spec.ts

Blob: `1c2d7388fe0614e692389b1a2727f02db3465932`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-44
- arrow_function (anonymous) @54-58
- arrow_function (anonymous) @60-75

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_vector_multiplication.cache.ts

Blob: `7b822386feb2d8bda6a47c8f662f5906f0ede57a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21
- arrow_function (anonymous) @25-37
- arrow_function (anonymous) @26-36
- arrow_function (anonymous) @27-36
- arrow_function (anonymous) @28-35
- arrow_function (anonymous) @39-39

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_matrix_vector_multiplication.spec.ts

Blob: `98a6b40dcd4ed6f38def07beb983253e724bfa79`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-46
- arrow_function (anonymous) @56-60
- arrow_function (anonymous) @62-79
- arrow_function (anonymous) @89-89
- arrow_function (anonymous) @90-107

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_multiplication.cache.ts

Blob: `a94f55ccf0e5766cf360a6b0ebb9fa564ccd242c`. Grammar: typescript. Status: syntax-clean.

- arrow_function multiplicationVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function multiplicationScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_multiplication.spec.ts

Blob: `82b3b45752887d1234d42498ce13c361edad6695`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-30
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-47
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-66
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-116
- arrow_function (anonymous) @126-126
- arrow_function (anonymous) @127-141

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_remainder.cache.ts

Blob: `2c1cdc0c38b41b19ad0ce079e663d034f268df9f`. Grammar: typescript. Status: syntax-clean.

- arrow_function remainderVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function remainderScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_remainder.spec.ts

Blob: `0328e6ce5d99ae85b616f37c96bd670185902809`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-30
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-47
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-66
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-116
- arrow_function (anonymous) @126-126
- arrow_function (anonymous) @127-141

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_subtraction.cache.ts

Blob: `a68b58449b332c5e53d892683f77091ccb828e87`. Grammar: typescript. Status: syntax-clean.

- arrow_function subtractionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function subtractionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f16_subtraction.spec.ts

Blob: `34bfa73ae251eb0f3c5c34f91337a291bdf82a83`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-30
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-47
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-66
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-116
- arrow_function (anonymous) @126-126
- arrow_function (anonymous) @127-141

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_addition.cache.ts

Blob: `9353671fb028d5b28b56dd313818bbfc73be18de`. Grammar: typescript. Status: syntax-clean.

- arrow_function additionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function additionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_addition.spec.ts

Blob: `f84b0d66c60c91245b9d07da61f1be5f82d09cdd`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-45
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-63
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @74-87
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-111
- arrow_function (anonymous) @121-121
- arrow_function (anonymous) @122-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_comparison.cache.ts

Blob: `28fb22e8202a55cd0e104cfbcaaec45710ff5919`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @11-33
- arrow_function (anonymous) @23-30
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @36-44
- arrow_function truthFunc @37-39
- arrow_function (anonymous) @41-43
- arrow_function (anonymous) @45-53
- arrow_function truthFunc @46-48
- arrow_function (anonymous) @50-52
- arrow_function (anonymous) @54-62
- arrow_function truthFunc @55-57
- arrow_function (anonymous) @59-61
- arrow_function (anonymous) @63-71
- arrow_function truthFunc @64-66
- arrow_function (anonymous) @68-70
- arrow_function (anonymous) @72-80
- arrow_function truthFunc @73-75
- arrow_function (anonymous) @77-79
- arrow_function (anonymous) @81-89
- arrow_function truthFunc @82-84
- arrow_function (anonymous) @86-88
- arrow_function (anonymous) @90-98
- arrow_function truthFunc @91-93
- arrow_function (anonymous) @95-97
- arrow_function (anonymous) @99-107
- arrow_function truthFunc @100-102
- arrow_function (anonymous) @104-106
- arrow_function (anonymous) @108-116
- arrow_function truthFunc @109-111
- arrow_function (anonymous) @113-115
- arrow_function (anonymous) @117-125
- arrow_function truthFunc @118-120
- arrow_function (anonymous) @122-124
- arrow_function (anonymous) @126-134
- arrow_function truthFunc @127-129
- arrow_function (anonymous) @131-133
- arrow_function (anonymous) @135-143
- arrow_function truthFunc @136-138
- arrow_function (anonymous) @140-142

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_comparison.spec.ts

Blob: `a4f9d0388c6766d6f4e1a077503f5adf3cbacc1b`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-24
- arrow_function (anonymous) @26-31
- arrow_function (anonymous) @41-42
- arrow_function (anonymous) @44-49
- arrow_function (anonymous) @59-60
- arrow_function (anonymous) @62-67
- arrow_function (anonymous) @77-78
- arrow_function (anonymous) @80-85
- arrow_function (anonymous) @95-96
- arrow_function (anonymous) @98-103
- arrow_function (anonymous) @113-114
- arrow_function (anonymous) @116-121

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_division.cache.ts

Blob: `017f7a451a3f020e4efa88832d03341883d3bf43`. Grammar: typescript. Status: syntax-clean.

- arrow_function divisionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function divisionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_division.spec.ts

Blob: `40537aa687c0bcf950aba85f56c6b249e928f632`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-45
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-63
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @74-87
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-111
- arrow_function (anonymous) @121-121
- arrow_function (anonymous) @122-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_addition.cache.ts

Blob: `0f3ced975d12e28af85e37c35f4e6b6d803fe574`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_addition.spec.ts

Blob: `41dfcefc387d54ff5257c1c0cb403ee8d7305d9f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-43
- arrow_function (anonymous) @53-57
- arrow_function (anonymous) @59-73

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_matrix_multiplication.cache.ts

Blob: `cde2d74fdfbe5d5201cbf6b34f74cf039fbdc852`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-21
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @10-19
- arrow_function (anonymous) @11-18
- arrow_function (anonymous) @23-23

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_matrix_multiplication.spec.ts

Blob: `609bb3023464e3f208057790bff58a95ebfb54cf`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-28
- arrow_function (anonymous) @30-49
- arrow_function (anonymous) @59-63
- arrow_function (anonymous) @65-84

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_scalar_multiplication.cache.ts

Blob: `f17dac31e6a95eeae4b3d7e198639cd32a912a58`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21
- arrow_function (anonymous) @25-37
- arrow_function (anonymous) @26-36
- arrow_function (anonymous) @27-36
- arrow_function (anonymous) @28-35
- arrow_function (anonymous) @39-39

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_scalar_multiplication.spec.ts

Blob: `61d5043f4ded50109c286a965f1ec02f1880f20e`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-45
- arrow_function (anonymous) @55-59
- arrow_function (anonymous) @61-77
- arrow_function (anonymous) @87-91
- arrow_function (anonymous) @93-109

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_subtraction.cache.ts

Blob: `2cd2bc1c6d223187badbed8b1ef833cde76b4836`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_subtraction.spec.ts

Blob: `698a1ec39972fdc16db35973217ccea939adec2a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-43
- arrow_function (anonymous) @53-57
- arrow_function (anonymous) @59-73

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_vector_multiplication.cache.ts

Blob: `f20b95029e2e634c1f2fd6d28071dcff42328b32`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @9-18
- arrow_function (anonymous) @10-17
- arrow_function (anonymous) @21-21
- arrow_function (anonymous) @25-37
- arrow_function (anonymous) @26-36
- arrow_function (anonymous) @27-36
- arrow_function (anonymous) @28-35
- arrow_function (anonymous) @39-39

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_matrix_vector_multiplication.spec.ts

Blob: `9c15f52e0e137b3ed5791f0b83729b1aef49ce0a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-27
- arrow_function (anonymous) @29-45
- arrow_function (anonymous) @55-59
- arrow_function (anonymous) @61-77
- arrow_function (anonymous) @87-87
- arrow_function (anonymous) @88-104

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_multiplication.cache.ts

Blob: `6a8c0bd81e9d749b64b3397750782fe91034ce26`. Grammar: typescript. Status: syntax-clean.

- arrow_function multiplicationVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function multiplicationScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_multiplication.spec.ts

Blob: `1c42d385af2e0adbafd1581d56a0c8c69c6b49d3`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-45
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-63
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @74-87
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-111
- arrow_function (anonymous) @121-121
- arrow_function (anonymous) @122-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_remainder.cache.ts

Blob: `2cb1a16f9dcc0734aa23bbd3b6058a7c399f0bb4`. Grammar: typescript. Status: syntax-clean.

- arrow_function remainderVectorScalarInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function remainderScalarVectorInterval @13-15
- arrow_function (anonymous) @14-14
- arrow_function (anonymous) @18-27
- arrow_function (anonymous) @19-26
- arrow_function (anonymous) @28-28
- arrow_function (anonymous) @31-41
- arrow_function (anonymous) @32-41
- arrow_function (anonymous) @33-40
- arrow_function (anonymous) @43-43
- arrow_function (anonymous) @46-56
- arrow_function (anonymous) @47-56
- arrow_function (anonymous) @48-55
- arrow_function (anonymous) @58-58

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_remainder.spec.ts

Blob: `97b3f67f054e26e03814c5e42713f386ea24248f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-45
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-63
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @74-87
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-111
- arrow_function (anonymous) @121-121
- arrow_function (anonymous) @122-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_subtraction.cache.ts

Blob: `519c0b37833d5ee54f219425b41386c5021cf70a`. Grammar: typescript. Status: syntax-clean.

- arrow_function subtractionVectorScalarInterval @5-7
- arrow_function (anonymous) @6-6
- arrow_function subtractionScalarVectorInterval @9-11
- arrow_function (anonymous) @10-10
- arrow_function (anonymous) @14-23
- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @27-37
- arrow_function (anonymous) @28-37
- arrow_function (anonymous) @29-36
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @42-52
- arrow_function (anonymous) @43-52
- arrow_function (anonymous) @44-51
- arrow_function (anonymous) @54-54

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/f32_subtraction.spec.ts

Blob: `1b06c5d9123be483211eca32cd1296e318bcad50`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-45
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-63
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @74-87
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-111
- arrow_function (anonymous) @121-121
- arrow_function (anonymous) @122-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/i32_arithmetic.cache.ts

Blob: `2ec09770a2d9aa256542c8f862455bf21738bfdd`. Grammar: typescript. Status: syntax-clean.

- function_declaration i32_add @10-12
- function_declaration i32_subtract @14-16
- function_declaration i32_multiply @18-20
- function_declaration i32_divide_non_const @22-30
- function_declaration i32_divide_const @32-40
- function_declaration i32_remainder_non_const @42-50
- function_declaration i32_remainder_const @52-60
- arrow_function (anonymous) @63-65
- arrow_function (anonymous) @66-68
- arrow_function (anonymous) @69-71
- arrow_function (anonymous) @72-74
- arrow_function (anonymous) @75-77
- arrow_function (anonymous) @78-80
- arrow_function (anonymous) @81-83
- arrow_function (anonymous) @90-96
- arrow_function (anonymous) @97-103
- arrow_function (anonymous) @104-106
- arrow_function (anonymous) @107-109
- arrow_function (anonymous) @110-112
- arrow_function (anonymous) @113-115
- arrow_function (anonymous) @116-118
- arrow_function (anonymous) @119-121
- arrow_function (anonymous) @122-124
- arrow_function (anonymous) @125-127
- arrow_function (anonymous) @128-130
- arrow_function (anonymous) @131-133
- arrow_function (anonymous) @134-136
- arrow_function (anonymous) @137-139
- arrow_function (anonymous) @140-142
- arrow_function (anonymous) @143-145
- arrow_function (anonymous) @146-148
- arrow_function (anonymous) @149-151
- arrow_function (anonymous) @152-154
- arrow_function (anonymous) @155-157
- arrow_function (anonymous) @158-164
- arrow_function (anonymous) @165-171
- arrow_function (anonymous) @172-178
- arrow_function (anonymous) @179-185
- arrow_function (anonymous) @186-192
- arrow_function (anonymous) @193-199
- arrow_function (anonymous) @200-206
- arrow_function (anonymous) @207-213
- arrow_function (anonymous) @214-220
- arrow_function (anonymous) @221-227
- arrow_function (anonymous) @228-234
- arrow_function (anonymous) @235-241
- arrow_function (anonymous) @242-248
- arrow_function (anonymous) @249-255
- arrow_function (anonymous) @256-262
- arrow_function (anonymous) @263-269
- arrow_function (anonymous) @270-276
- arrow_function (anonymous) @277-283
- arrow_function (anonymous) @284-290
- arrow_function (anonymous) @291-297
- arrow_function (anonymous) @298-304
- arrow_function (anonymous) @305-311
- arrow_function (anonymous) @312-318
- arrow_function (anonymous) @319-325

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/i32_arithmetic.spec.ts

Blob: `2caba3f586b068e12e665643771fb7b9f2eb3fa6`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-23
- arrow_function (anonymous) @25-28
- arrow_function (anonymous) @37-38
- arrow_function (anonymous) @40-43
- arrow_function (anonymous) @52-53
- arrow_function (anonymous) @55-58
- arrow_function (anonymous) @67-68
- arrow_function (anonymous) @70-73
- arrow_function (anonymous) @82-83
- arrow_function (anonymous) @85-88
- arrow_function (anonymous) @97-98
- arrow_function (anonymous) @100-103
- arrow_function (anonymous) @112-113
- arrow_function (anonymous) @115-120
- arrow_function (anonymous) @129-130
- arrow_function (anonymous) @132-137
- arrow_function (anonymous) @146-147
- arrow_function (anonymous) @149-154
- arrow_function (anonymous) @163-164
- arrow_function (anonymous) @166-171
- arrow_function (anonymous) @185-186
- arrow_function (anonymous) @188-193
- arrow_function (anonymous) @202-203
- arrow_function (anonymous) @205-210
- arrow_function (anonymous) @219-220
- arrow_function (anonymous) @222-227
- arrow_function (anonymous) @236-237
- arrow_function (anonymous) @239-244
- arrow_function (anonymous) @253-254
- arrow_function (anonymous) @256-261
- arrow_function (anonymous) @270-271
- arrow_function (anonymous) @273-278
- arrow_function (anonymous) @287-288
- arrow_function (anonymous) @290-295
- arrow_function (anonymous) @304-305
- arrow_function (anonymous) @307-312
- arrow_function (anonymous) @321-322
- arrow_function (anonymous) @324-329
- arrow_function (anonymous) @338-339
- arrow_function (anonymous) @341-346
- arrow_function (anonymous) @355-356
- arrow_function (anonymous) @358-364
- arrow_function (anonymous) @373-374
- arrow_function (anonymous) @376-382
- arrow_function (anonymous) @391-392
- arrow_function (anonymous) @394-400
- arrow_function (anonymous) @409-410
- arrow_function (anonymous) @412-418
- arrow_function (anonymous) @427-428
- arrow_function (anonymous) @430-436
- arrow_function (anonymous) @445-446
- arrow_function (anonymous) @448-454

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/i32_comparison.cache.ts

Blob: `de0a6de477c3bb2c15f6e530619303ca1477e650`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @10-12
- arrow_function (anonymous) @15-15
- arrow_function (anonymous) @15-15
- arrow_function (anonymous) @16-16
- arrow_function (anonymous) @16-16
- arrow_function (anonymous) @17-17
- arrow_function (anonymous) @17-17
- arrow_function (anonymous) @18-18
- arrow_function (anonymous) @18-18
- arrow_function (anonymous) @19-19
- arrow_function (anonymous) @19-19
- arrow_function (anonymous) @20-20
- arrow_function (anonymous) @20-20

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/i32_comparison.spec.ts

Blob: `f7a5a1f4088abdc4acc8d525dd1298027b4ac646`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-23
- arrow_function (anonymous) @25-28
- arrow_function (anonymous) @37-38
- arrow_function (anonymous) @40-43
- arrow_function (anonymous) @52-53
- arrow_function (anonymous) @55-58
- arrow_function (anonymous) @67-68
- arrow_function (anonymous) @70-73
- arrow_function (anonymous) @82-83
- arrow_function (anonymous) @85-88
- arrow_function (anonymous) @97-98
- arrow_function (anonymous) @100-103

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/u32_arithmetic.cache.ts

Blob: `91be35a1eeffa1c52f45c8cd0560e90364f6cc5a`. Grammar: typescript. Status: syntax-clean.

- function_declaration u32_add @9-11
- function_declaration u32_subtract @13-15
- function_declaration u32_multiply @17-19
- function_declaration u32_divide_non_const @21-26
- function_declaration u32_divide_const @28-33
- function_declaration u32_remainder_non_const @35-40
- function_declaration u32_remainder_const @42-47
- arrow_function (anonymous) @50-52
- arrow_function (anonymous) @53-55
- arrow_function (anonymous) @56-58
- arrow_function (anonymous) @59-61
- arrow_function (anonymous) @62-64
- arrow_function (anonymous) @65-67
- arrow_function (anonymous) @68-70
- arrow_function (anonymous) @71-73
- arrow_function (anonymous) @74-76
- arrow_function (anonymous) @77-79
- arrow_function (anonymous) @80-82
- arrow_function (anonymous) @83-85
- arrow_function (anonymous) @86-88
- arrow_function (anonymous) @89-91
- arrow_function (anonymous) @92-94
- arrow_function (anonymous) @95-97
- arrow_function (anonymous) @98-100
- arrow_function (anonymous) @101-103
- arrow_function (anonymous) @104-106
- arrow_function (anonymous) @107-109
- arrow_function (anonymous) @110-112
- arrow_function (anonymous) @113-115
- arrow_function (anonymous) @116-118
- arrow_function (anonymous) @119-121
- arrow_function (anonymous) @122-124
- arrow_function (anonymous) @125-131
- arrow_function (anonymous) @132-138
- arrow_function (anonymous) @139-145
- arrow_function (anonymous) @146-152
- arrow_function (anonymous) @153-159
- arrow_function (anonymous) @160-166
- arrow_function (anonymous) @167-173
- arrow_function (anonymous) @174-180
- arrow_function (anonymous) @181-187
- arrow_function (anonymous) @188-194
- arrow_function (anonymous) @195-201
- arrow_function (anonymous) @202-208
- arrow_function (anonymous) @209-215
- arrow_function (anonymous) @216-222
- arrow_function (anonymous) @223-229
- arrow_function (anonymous) @230-236
- arrow_function (anonymous) @237-243
- arrow_function (anonymous) @244-250
- arrow_function (anonymous) @251-257
- arrow_function (anonymous) @258-264
- arrow_function (anonymous) @265-271
- arrow_function (anonymous) @272-278
- arrow_function (anonymous) @279-285
- arrow_function (anonymous) @286-292

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/u32_arithmetic.spec.ts

Blob: `8d5b6218bd94880a8eb71ea36d27baa50705db80`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-23
- arrow_function (anonymous) @25-28
- arrow_function (anonymous) @37-38
- arrow_function (anonymous) @40-43
- arrow_function (anonymous) @52-53
- arrow_function (anonymous) @55-58
- arrow_function (anonymous) @67-68
- arrow_function (anonymous) @70-73
- arrow_function (anonymous) @82-83
- arrow_function (anonymous) @85-88
- arrow_function (anonymous) @97-98
- arrow_function (anonymous) @100-103
- arrow_function (anonymous) @112-113
- arrow_function (anonymous) @115-120
- arrow_function (anonymous) @129-130
- arrow_function (anonymous) @132-137
- arrow_function (anonymous) @146-147
- arrow_function (anonymous) @149-154
- arrow_function (anonymous) @163-164
- arrow_function (anonymous) @166-171
- arrow_function (anonymous) @180-181
- arrow_function (anonymous) @183-188
- arrow_function (anonymous) @197-198
- arrow_function (anonymous) @200-205
- arrow_function (anonymous) @214-215
- arrow_function (anonymous) @217-222
- arrow_function (anonymous) @231-232
- arrow_function (anonymous) @234-239
- arrow_function (anonymous) @248-249
- arrow_function (anonymous) @251-256
- arrow_function (anonymous) @265-266
- arrow_function (anonymous) @268-273
- arrow_function (anonymous) @282-283
- arrow_function (anonymous) @285-290
- arrow_function (anonymous) @299-300
- arrow_function (anonymous) @302-307
- arrow_function (anonymous) @316-317
- arrow_function (anonymous) @319-324
- arrow_function (anonymous) @333-334
- arrow_function (anonymous) @336-342
- arrow_function (anonymous) @351-352
- arrow_function (anonymous) @354-360
- arrow_function (anonymous) @369-370
- arrow_function (anonymous) @372-378
- arrow_function (anonymous) @387-388
- arrow_function (anonymous) @390-396
- arrow_function (anonymous) @405-406
- arrow_function (anonymous) @408-414
- arrow_function (anonymous) @423-424
- arrow_function (anonymous) @426-432

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/u32_comparison.cache.ts

Blob: `93b05004964da39485acfb09ebce7490a8c80386`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @10-12
- arrow_function (anonymous) @15-15
- arrow_function (anonymous) @15-15
- arrow_function (anonymous) @16-16
- arrow_function (anonymous) @16-16
- arrow_function (anonymous) @17-17
- arrow_function (anonymous) @17-17
- arrow_function (anonymous) @18-18
- arrow_function (anonymous) @18-18
- arrow_function (anonymous) @19-19
- arrow_function (anonymous) @19-19
- arrow_function (anonymous) @20-20
- arrow_function (anonymous) @20-20

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/binary/u32_comparison.spec.ts

Blob: `4729a554350999f93137ac5317f44fba9cf2d149`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-23
- arrow_function (anonymous) @25-28
- arrow_function (anonymous) @37-38
- arrow_function (anonymous) @40-43
- arrow_function (anonymous) @52-53
- arrow_function (anonymous) @55-58
- arrow_function (anonymous) @67-68
- arrow_function (anonymous) @70-73
- arrow_function (anonymous) @82-83
- arrow_function (anonymous) @85-88
- arrow_function (anonymous) @97-98
- arrow_function (anonymous) @100-103

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/abs.cache.ts

Blob: `9634ae8f347abc6fc730f897b582c82ae3dde064`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @9-17
- arrow_function (anonymous) @10-16
- arrow_function (anonymous) @18-18
- arrow_function (anonymous) @19-23
- arrow_function (anonymous) @20-22

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/abs.spec.ts

Blob: `ca7c0955fe268c401f9753bd751b4bcc7031646c`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @32-35
- arrow_function (anonymous) @37-40
- arrow_function (anonymous) @45-46
- arrow_function (anonymous) @48-87
- arrow_function (anonymous) @92-93
- arrow_function (anonymous) @95-137
- arrow_function (anonymous) @142-145
- arrow_function (anonymous) @147-157
- arrow_function (anonymous) @162-163
- arrow_function (anonymous) @165-168
- arrow_function (anonymous) @173-174
- arrow_function (anonymous) @176-180

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/acos.cache.ts

Blob: `466618b6db166e88a2c6d48795516b190ab9bc3b`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @22-22

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/acos.spec.ts

Blob: `d9edd3ee38826cae5546d00c2bb7dfac260b5d0a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/acosh.cache.ts

Blob: `587131140da07156a6d5969612a44856a0ee256d`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @22-22

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/acosh.spec.ts

Blob: `a6df8c9d4fc3335ded4b72412f80d697e2059a94`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @27-30
- arrow_function (anonymous) @32-42
- arrow_function (anonymous) @47-48
- arrow_function (anonymous) @50-53
- arrow_function (anonymous) @58-59
- arrow_function (anonymous) @61-65

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/all.spec.ts

Blob: `aef81e8862b5ce8accb6bdfce7c13baa0ea16e10`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-84

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/any.spec.ts

Blob: `60376961a172b18fb3f494bbc59ab082a6efad45`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-84

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/arrayLength.spec.ts

Blob: `9cfd35a10579ddf80a99196b1732d786231bdc5a`. Grammar: typescript. Status: syntax-clean.

- function_declaration runShaderTest @81-132
- function_declaration typeRequiresF16 @139-141
- function_declaration shaderHeader @148-150
- arrow_function (anonymous) @162-162
- arrow_function (anonymous) @163-182
- arrow_function (anonymous) @198-199
- arrow_function (anonymous) @201-217
- arrow_function (anonymous) @233-233
- arrow_function (anonymous) @234-257
- arrow_function (anonymous) @266-280
- arrow_function (anonymous) @288-300

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/asin.cache.ts

Blob: `d9e6280e0d633f5db17d387ebbc2085776725427`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @22-22

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/asin.spec.ts

Blob: `47c7b2b1807269b0e396e2f3b4498f9750147c7d`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/asinh.cache.ts

Blob: `4ee66f1ea65886bdf7e4f4921bd54f2791e1782f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @6-15
- arrow_function (anonymous) @7-14
- arrow_function (anonymous) @16-16

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/asinh.spec.ts

Blob: `064ad9ec921df07da78a695fde025b8f8365ea2f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @26-29
- arrow_function (anonymous) @31-41
- arrow_function (anonymous) @46-47
- arrow_function (anonymous) @49-52
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-64

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atan.cache.ts

Blob: `e39e40448ea2fd4dbc9c1e36c347e86b4fcd65a2`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @8-21
- arrow_function (anonymous) @9-21
- arrow_function (anonymous) @10-20
- arrow_function (anonymous) @23-23

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atan.spec.ts

Blob: `523b51d9d0ba34d7b23f7a60a3707ec96bb7560a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-27
- arrow_function (anonymous) @29-39
- arrow_function (anonymous) @50-51
- arrow_function (anonymous) @53-56
- arrow_function (anonymous) @61-62
- arrow_function (anonymous) @64-68

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atan2.cache.ts

Blob: `be25c2dffb4bbc2f335f6c89c03435973b6218a2`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-31
- arrow_function (anonymous) @8-31
- arrow_function (anonymous) @9-30
- arrow_function (anonymous) @33-33

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atan2.spec.ts

Blob: `bfa14590bb25bd29f28d8a3714f88652ac0226a0`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @49-50
- arrow_function (anonymous) @52-55
- arrow_function (anonymous) @60-61
- arrow_function (anonymous) @63-67

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atanh.cache.ts

Blob: `bcd000bf619cd03448ce37b66f09c285d24f26bf`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-28
- arrow_function (anonymous) @8-28
- arrow_function (anonymous) @9-27
- arrow_function (anonymous) @30-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atanh.spec.ts

Blob: `9bc0d1904bfd8add0fc2a51dc87bb57a15203749`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @26-29
- arrow_function (anonymous) @31-41
- arrow_function (anonymous) @46-47
- arrow_function (anonymous) @49-52
- arrow_function (anonymous) @57-58
- arrow_function (anonymous) @60-64

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicAdd.spec.ts

Blob: `5a7a823ef86fcde2bce9ac829613fe531e83f24e`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @34-38
- arrow_function (anonymous) @40-59
- arrow_function (anonymous) @71-75
- arrow_function (anonymous) @77-101

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicAnd.spec.ts

Blob: `8352a87a75fcb3eec2c0f8773ec82aef836dc098`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @36-41
- arrow_function (anonymous) @43-77
- arrow_function (anonymous) @89-94
- arrow_function (anonymous) @96-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicCompareExchangeWeak.spec.ts

Blob: `4a8c328795ca8b54123d12d78719c6f98e4c6c91`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @46-51
- arrow_function (anonymous) @53-165
- arrow_function (anonymous) @111-111
- arrow_function (anonymous) @145-145
- arrow_function (anonymous) @157-163
- arrow_function (anonymous) @182-187
- arrow_function (anonymous) @189-310
- arrow_function (anonymous) @288-288
- arrow_function (anonymous) @302-308
- arrow_function (anonymous) @327-330
- arrow_function (anonymous) @332-529
- arrow_function dumpValues @481-486
- arrow_function (anonymous) @489-489
- arrow_function (anonymous) @492-492
- arrow_function (anonymous) @500-500
- arrow_function (anonymous) @506-506
- arrow_function (anonymous) @520-520
- arrow_function (anonymous) @521-521
- arrow_function (anonymous) @546-549
- arrow_function (anonymous) @551-741
- arrow_function dumpValues @693-698
- arrow_function (anonymous) @701-701
- arrow_function (anonymous) @704-704
- arrow_function (anonymous) @712-712
- arrow_function (anonymous) @718-718
- arrow_function (anonymous) @732-732
- arrow_function (anonymous) @733-733

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicExchange.spec.ts

Blob: `d1104f9457aa3daf3baf7488ad8e323a4a63a7cf`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @31-108
- arrow_function (anonymous) @73-73
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @106-106
- arrow_function (anonymous) @121-126
- arrow_function (anonymous) @128-218
- arrow_function (anonymous) @207-207
- arrow_function (anonymous) @215-215
- arrow_function (anonymous) @230-235
- arrow_function (anonymous) @237-329
- arrow_function (anonymous) @317-323
- arrow_function (anonymous) @342-347
- arrow_function (anonymous) @349-462
- arrow_function (anonymous) @441-447

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicLoad.spec.ts

Blob: `e1809d0068f201bb3e014d98aadbed1de679da41`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-29
- arrow_function (anonymous) @31-100
- arrow_function (anonymous) @70-70
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @113-118
- arrow_function (anonymous) @120-189
- arrow_function (anonymous) @186-186

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicMax.spec.ts

Blob: `944bda00f79ed4ec601b6ea554e8489cd2b12eab`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @34-38
- arrow_function (anonymous) @40-59
- arrow_function (anonymous) @71-75
- arrow_function (anonymous) @77-101

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicMin.spec.ts

Blob: `7677dc1ed37349cf6501e3e6874f580d69aafb9d`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @34-38
- arrow_function (anonymous) @40-58
- arrow_function (anonymous) @70-74
- arrow_function (anonymous) @76-100

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicOr.spec.ts

Blob: `c90ae715d9462788be770b002b79f7b9e110ca9e`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @36-41
- arrow_function (anonymous) @43-76
- arrow_function (anonymous) @88-93
- arrow_function (anonymous) @95-131

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicStore.spec.ts

Blob: `711ba0efb7d7d6e9d727404fce0db778c3bbb441`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @30-35
- arrow_function (anonymous) @37-58
- arrow_function (anonymous) @46-46
- arrow_function (anonymous) @70-75
- arrow_function (anonymous) @77-100
- arrow_function (anonymous) @88-88
- arrow_function (anonymous) @115-120
- arrow_function (anonymous) @122-192
- arrow_function (anonymous) @185-185
- arrow_function (anonymous) @207-212
- arrow_function (anonymous) @214-299
- arrow_function (anonymous) @290-290

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicStoreMax.spec.ts

Blob: `207f042b2d2d427008838b6cde22a8be05d04712`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @25-30
- arrow_function (anonymous) @32-111

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicStoreMin.spec.ts

Blob: `4c466ed18a0f180c8b59e5580ad651f4c63f8645`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @26-31
- arrow_function (anonymous) @33-115

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicSub.spec.ts

Blob: `ab43be597c9fbc1f69c44ad2f12936a0b983d540`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @34-38
- arrow_function (anonymous) @40-59
- arrow_function (anonymous) @71-75
- arrow_function (anonymous) @77-101
- arrow_function (anonymous) @105-124

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/atomicXor.spec.ts

Blob: `6dedb85af5ea0b786873f44c186474b4b569da14`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @36-41
- arrow_function (anonymous) @43-77
- arrow_function (anonymous) @89-94
- arrow_function (anonymous) @96-135

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/atomics/harness.ts

Blob: `cac1f7fa0c89b298013c093e24e72c73af64a4cb`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @17-17
- arrow_function (anonymous) @18-19
- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @23-24
- function_declaration typedArrayCtor @28-37
- function_declaration runStorageVariableTest @39-112
- function_declaration runWorkgroupVariableTest @114-206

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/bitcast.cache.ts

Blob: `76337e4a7ff00af97e15019603165d3443b7dfe9`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @54-54
- arrow_function (anonymous) @55-55
- arrow_function (anonymous) @58-58
- arrow_function (anonymous) @59-59
- arrow_function (anonymous) @69-69
- arrow_function (anonymous) @76-76
- arrow_function (anonymous) @80-80
- arrow_function (anonymous) @84-84
- function_declaration u16x2ToU32 @95-104
- function_declaration u32ToU16x2 @110-117
- function_declaration u16x2ToVec2F16 @122-125
- function_declaration u16x4ToVec4F16 @130-133
- function_declaration canU32BitcastToFiniteVec2F16 @139-143
- arrow_function (anonymous) @141-141
- arrow_function (anonymous) @142-142
- function_declaration slidingSlice @152-162
- arrow_function (anonymous) @170-170
- arrow_function (anonymous) @173-173
- arrow_function (anonymous) @193-194
- arrow_function (anonymous) @204-204
- arrow_function (anonymous) @231-232
- arrow_function (anonymous) @241-242
- function_declaration bitcastF32ToF32Comparator @249-253
- function_declaration bitcastF32ToU32Comparator @259-266
- function_declaration bitcastF32ToI32Comparator @272-279
- function_declaration bitcastI32ToF32Comparator @285-292
- function_declaration bitcastU32ToF32Comparator @298-305
- function_declaration generateF16ExpectationIntervals @312-324
- function_declaration bitcastF16ToF16Comparator @330-333
- function_declaration bitcastU32ToVec2F16Comparator @339-347
- function_declaration bitcastI32ToVec2F16Comparator @353-361
- function_declaration bitcastF32ToVec2F16Comparator @367-380
- function_declaration bitcastVec2U32ToVec4F16Comparator @386-395
- function_declaration bitcastVec2I32ToVec4F16Comparator @401-413
- function_declaration bitcastVec2F32ToVec4F16Comparator @419-431
- interface_declaration ExpectationFor32BitsScalarFromF16x2 @434-439
- function_declaration possibleBitsInU16FromFiniteF16InU16 @446-450
- function_declaration possible32BitScalarIntervalsFromF16x2 @456-509
- arrow_function (anonymous) @465-465
- arrow_function (anonymous) @466-466
- arrow_function (anonymous) @471-471
- arrow_function (anonymous) @472-472
- arrow_function (anonymous) @478-478
- arrow_function (anonymous) @479-491
- arrow_function (anonymous) @504-507
- function_declaration bitcastVec2F16ToU32Comparator @515-523
- function_declaration bitcastVec2F16ToI32Comparator @529-537
- function_declaration bitcastVec2F16ToF32Comparator @543-551
- function_declaration bitcastVec4F16ToVec2U32Comparator @557-573
- arrow_function (anonymous) @559-560
- arrow_function (anonymous) @565-565
- arrow_function (anonymous) @565-565
- arrow_function (anonymous) @569-569
- arrow_function (anonymous) @570-570
- function_declaration bitcastVec4F16ToVec2I32Comparator @579-595
- arrow_function (anonymous) @581-582
- arrow_function (anonymous) @587-587
- arrow_function (anonymous) @587-587
- arrow_function (anonymous) @591-591
- arrow_function (anonymous) @592-592
- function_declaration bitcastVec4F16ToVec2F32Comparator @601-612
- arrow_function (anonymous) @603-604
- arrow_function (anonymous) @607-607
- arrow_function (anonymous) @607-610
- arrow_function (anonymous) @616-616
- arrow_function (anonymous) @616-616
- arrow_function (anonymous) @617-617
- arrow_function (anonymous) @617-617
- arrow_function (anonymous) @618-622
- arrow_function (anonymous) @619-622
- arrow_function (anonymous) @623-624
- arrow_function (anonymous) @624-624
- arrow_function (anonymous) @625-629
- arrow_function (anonymous) @626-629
- arrow_function (anonymous) @630-631
- arrow_function (anonymous) @631-631
- arrow_function (anonymous) @634-634
- arrow_function (anonymous) @634-634
- arrow_function (anonymous) @635-639
- arrow_function (anonymous) @636-639
- arrow_function (anonymous) @640-640
- arrow_function (anonymous) @640-640
- arrow_function (anonymous) @641-641
- arrow_function (anonymous) @641-641
- arrow_function (anonymous) @642-647
- arrow_function (anonymous) @644-647
- arrow_function (anonymous) @648-652
- arrow_function (anonymous) @649-652
- arrow_function (anonymous) @653-653
- arrow_function (anonymous) @653-653
- arrow_function (anonymous) @654-658
- arrow_function (anonymous) @655-658
- arrow_function (anonymous) @659-663
- arrow_function (anonymous) @660-663
- arrow_function (anonymous) @664-668
- arrow_function (anonymous) @665-668
- arrow_function (anonymous) @669-670
- arrow_function (anonymous) @670-670
- arrow_function (anonymous) @672-676
- arrow_function (anonymous) @673-676
- arrow_function (anonymous) @677-678
- arrow_function (anonymous) @678-678
- arrow_function (anonymous) @681-685
- arrow_function (anonymous) @682-685
- arrow_function (anonymous) @686-690
- arrow_function (anonymous) @687-690
- arrow_function (anonymous) @691-695
- arrow_function (anonymous) @692-695
- arrow_function (anonymous) @696-700
- arrow_function (anonymous) @697-700
- arrow_function (anonymous) @701-706
- arrow_function (anonymous) @703-706
- arrow_function (anonymous) @707-711
- arrow_function (anonymous) @708-711
- arrow_function (anonymous) @712-716
- arrow_function (anonymous) @713-716
- arrow_function (anonymous) @717-721
- arrow_function (anonymous) @718-721
- arrow_function (anonymous) @724-728
- arrow_function (anonymous) @725-728
- arrow_function (anonymous) @729-733
- arrow_function (anonymous) @730-733
- arrow_function (anonymous) @734-739
- arrow_function (anonymous) @736-739
- arrow_function (anonymous) @737-737
- arrow_function (anonymous) @740-744
- arrow_function (anonymous) @741-744
- arrow_function (anonymous) @745-749
- arrow_function (anonymous) @746-749
- arrow_function (anonymous) @750-754
- arrow_function (anonymous) @751-754
- arrow_function (anonymous) @755-759
- arrow_function (anonymous) @756-759
- arrow_function (anonymous) @760-764
- arrow_function (anonymous) @761-764
- arrow_function (anonymous) @767-771
- arrow_function (anonymous) @768-771
- arrow_function (anonymous) @772-776
- arrow_function (anonymous) @773-776
- arrow_function (anonymous) @777-781
- arrow_function (anonymous) @778-781
- arrow_function (anonymous) @782-786
- arrow_function (anonymous) @783-786
- arrow_function (anonymous) @787-793
- arrow_function (anonymous) @789-789
- arrow_function (anonymous) @790-793
- arrow_function (anonymous) @794-798
- arrow_function (anonymous) @795-798
- arrow_function (anonymous) @801-805
- arrow_function (anonymous) @802-805
- arrow_function (anonymous) @806-810
- arrow_function (anonymous) @807-810
- arrow_function (anonymous) @811-815
- arrow_function (anonymous) @812-815
- arrow_function (anonymous) @816-820
- arrow_function (anonymous) @817-820
- arrow_function (anonymous) @821-831
- arrow_function (anonymous) @824-826
- arrow_function (anonymous) @828-831
- arrow_function (anonymous) @832-836
- arrow_function (anonymous) @833-836

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/bitcast.spec.ts

Blob: `d5e55a1164b80ced41c81807ba6c8ec995d31561`. Grammar: typescript. Status: syntax-clean.

- function_declaration bitcastBuilder @51-60
- arrow_function (anonymous) @66-70
- arrow_function (anonymous) @72-75
- arrow_function (anonymous) @80-84
- arrow_function (anonymous) @86-89
- arrow_function (anonymous) @94-98
- arrow_function (anonymous) @100-106
- arrow_function (anonymous) @112-116
- arrow_function (anonymous) @118-121
- arrow_function (anonymous) @126-130
- arrow_function (anonymous) @132-138
- arrow_function (anonymous) @144-148
- arrow_function (anonymous) @150-153
- arrow_function (anonymous) @158-162
- arrow_function (anonymous) @164-170
- arrow_function (anonymous) @176-180
- arrow_function (anonymous) @182-188
- arrow_function (anonymous) @193-197
- arrow_function (anonymous) @199-205
- arrow_function (anonymous) @215-219
- arrow_function (anonymous) @221-228
- arrow_function (anonymous) @234-234
- arrow_function (anonymous) @235-242
- arrow_function (anonymous) @247-247
- arrow_function (anonymous) @248-255
- arrow_function (anonymous) @260-260
- arrow_function (anonymous) @261-268
- arrow_function (anonymous) @274-274
- arrow_function (anonymous) @275-282
- arrow_function (anonymous) @287-287
- arrow_function (anonymous) @288-295
- arrow_function (anonymous) @300-300
- arrow_function (anonymous) @301-310
- arrow_function (anonymous) @316-316
- arrow_function (anonymous) @317-324
- arrow_function (anonymous) @329-329
- arrow_function (anonymous) @330-337
- arrow_function (anonymous) @342-342
- arrow_function (anonymous) @343-350
- arrow_function (anonymous) @356-356
- arrow_function (anonymous) @357-364
- arrow_function (anonymous) @369-369
- arrow_function (anonymous) @370-377
- arrow_function (anonymous) @382-382
- arrow_function (anonymous) @383-392
- arrow_function (anonymous) @398-401
- arrow_function (anonymous) @403-415
- arrow_function (anonymous) @404-412
- arrow_function (anonymous) @405-407
- arrow_function (anonymous) @420-423
- arrow_function (anonymous) @425-459
- arrow_function (anonymous) @451-456
- arrow_function (anonymous) @464-467
- arrow_function (anonymous) @469-503
- arrow_function (anonymous) @495-500
- arrow_function (anonymous) @508-508
- arrow_function (anonymous) @509-521
- arrow_function (anonymous) @526-526
- arrow_function (anonymous) @527-539
- arrow_function (anonymous) @545-549
- arrow_function (anonymous) @551-554
- arrow_function (anonymous) @559-563
- arrow_function (anonymous) @565-568
- arrow_function (anonymous) @573-577
- arrow_function (anonymous) @579-582
- arrow_function (anonymous) @587-587
- arrow_function (anonymous) @588-599
- arrow_function (anonymous) @604-604
- arrow_function (anonymous) @605-609

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/bufferArrayView.spec.ts

Blob: `992ca756e352a8325a000397cbe0657734acece4`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @40-57
- arrow_function (anonymous) @49-57
- arrow_function (anonymous) @59-146
- arrow_function (anonymous) @150-163
- arrow_function (anonymous) @158-163
- arrow_function (anonymous) @165-276
- arrow_function (anonymous) @280-292
- arrow_function (anonymous) @286-292
- arrow_function (anonymous) @294-341
- arrow_function (anonymous) @345-358
- arrow_function (anonymous) @352-358
- arrow_function (anonymous) @360-406
- arrow_function (anonymous) @410-453
- arrow_function (anonymous) @418-453
- arrow_function (anonymous) @455-511
- arrow_function (anonymous) @515-557
- arrow_function (anonymous) @525-557
- arrow_function (anonymous) @559-627
- arrow_function (anonymous) @648-660
- arrow_function (anonymous) @653-656
- arrow_function (anonymous) @662-698
- arrow_function view @667-687

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/bufferLength.spec.ts

Blob: `57754cdb55bc7f529dee51092eac319c68d4bc92`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @15-22
- arrow_function (anonymous) @24-222
- arrow_function (anonymous) @226-233
- arrow_function (anonymous) @235-378
- arrow_function (anonymous) @382-388
- arrow_function (anonymous) @386-388
- arrow_function (anonymous) @390-485

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/bufferView.spec.ts

Blob: `97c2bfcca4593e339cb809976a6753f2780c78f7`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @39-56
- arrow_function (anonymous) @48-56
- arrow_function (anonymous) @58-135
- arrow_function (anonymous) @139-152
- arrow_function (anonymous) @147-152
- arrow_function (anonymous) @154-253
- arrow_function (anonymous) @257-269
- arrow_function (anonymous) @263-269
- arrow_function (anonymous) @271-314
- arrow_function (anonymous) @318-331
- arrow_function (anonymous) @325-331
- arrow_function (anonymous) @333-379
- arrow_function (anonymous) @383-423
- arrow_function (anonymous) @391-423
- arrow_function (anonymous) @425-479
- arrow_function (anonymous) @483-525
- arrow_function (anonymous) @493-525
- arrow_function (anonymous) @527-593
- arrow_function (anonymous) @610-622
- arrow_function (anonymous) @615-618
- arrow_function (anonymous) @624-645
- arrow_function view @629-634

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/buffer_view_utils.ts

Blob: `6635f19e992f525e9f2d7f670a3742a654b50de7`. Grammar: typescript. Status: syntax-clean.

- interface_declaration ArrayLengthType @23-31
- function_declaration isValidArrayLengthCase @42-58
- function_declaration calculateArrayLength @69-83
- function_declaration runLengthTest @285-402
- interface_declaration LayoutCase @404-414
- function_declaration runReadLayoutTest @717-786
- arrow_function (anonymous) @736-742
- function_declaration runWriteLayoutTest @798-854
- arrow_function (anonymous) @845-851
- function_declaration runReadWriteTest @869-977
- function_declaration f32Bits @980-982
- type_alias_declaration MixedScalar @985-985
- function_declaration mixedScalarSize @988-990
- interface_declaration MixedLane @993-1000
- interface_declaration MixedType @1007-1021
- function_declaration scalar @1023-1026
- function_declaration vec @1028-1036
- arrow_function (anonymous) @1030-1034
- function_declaration structType @1039-1057
- arrow_function roundUp @1040-1040
- arrow_function (anonymous) @1043-1048
- arrow_function (anonymous) @1049-1054
- arrow_function (anonymous) @1050-1054
- function_declaration mixedTypeUsesF16 @1111-1113
- arrow_function (anonymous) @1112-1112
- function_declaration mixedTypeName @1116-1118
- function_declaration mixedTypeCtorFromLanes @1121-1133
- arrow_function (anonymous) @1124-1129
- function_declaration mixedTypeCtor @1139-1144
- arrow_function (anonymous) @1140-1141
- function_declaration mixedTypeStructDecls @1147-1159
- arrow_function visit @1149-1156
- arrow_function (anonymous) @1153-1153
- arrow_function (anonymous) @1154-1154
- function_declaration mixedTypeDecls @1169-1184
- arrow_function laneWise @1171-1179
- arrow_function (anonymous) @1175-1175
- function_declaration mixedTypeWriteLanes @1190-1194
- arrow_function (anonymous) @1192-1192
- type_alias_declaration MixedTypeOverlap @1270-1270
- function_declaration mixedTypeWords @1276-1313
- arrow_function lanesOverlap @1281-1288
- arrow_function (anonymous) @1282-1287
- arrow_function (anonymous) @1283-1287
- arrow_function viewsOverlap @1289-1290
- interface_declaration MixedTypeMemory @1316-1319
- interface_declaration MixedTypeArgs @1322-1329
- function_declaration simStore @1335-1355
- arrow_function (anonymous) @1336-1354
- function_declaration simLoad @1358-1363
- arrow_function (anonymous) @1359-1362
- interface_declaration MixedTypeOp @1369-1391
- arrow_function (anonymous) @1399-1402
- arrow_function (anonymous) @1403-1407
- arrow_function (anonymous) @1410-1412
- arrow_function (anonymous) @1413-1416
- arrow_function (anonymous) @1419-1422
- arrow_function (anonymous) @1423-1427
- arrow_function (anonymous) @1426-1426
- arrow_function (anonymous) @1431-1435
- arrow_function (anonymous) @1436-1441
- arrow_function (anonymous) @1445-1451
- arrow_function (anonymous) @1452-1461
- arrow_function (anonymous) @1456-1458
- type_alias_declaration MixedTypeBuffer @1487-1487
- interface_declaration MixedTypeAliasingParams @1489-1512
- function_declaration runMixedTypeAliasingTest @1522-1639
- arrow_function (anonymous) @1586-1586
- arrow_function (anonymous) @1587-1587
- arrow_function (anonymous) @1590-1590
- arrow_function (anonymous) @1591-1593
- arrow_function (anonymous) @1600-1602

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/builtin.ts

Blob: `0afd8c398005bfe0ab9eafe26f04534b4d36c2cf`. Grammar: typescript. Status: syntax-clean.

- function_declaration builtin @10-12
- arrow_function (anonymous) @11-11
- function_declaration abstractFloatBuiltin @15-17
- arrow_function (anonymous) @16-16
- function_declaration abstractIntBuiltin @20-22
- arrow_function (anonymous) @21-21
- function_declaration builtinWithPredeclaration @25-30
- arrow_function (anonymous) @27-27

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/ceil.cache.ts

Blob: `c0178d9b83adaa1d71afd4ef68d8a4671f76fc7c`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @15-23
- arrow_function (anonymous) @16-22
- arrow_function (anonymous) @24-24

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/ceil.spec.ts

Blob: `43a4aca0d4273c1ac2eb3a1ff825008830b647bb`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-27
- arrow_function (anonymous) @29-39
- arrow_function (anonymous) @44-45
- arrow_function (anonymous) @47-50
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-62

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/clamp.cache.ts

Blob: `909d15e7e7527762b7dbf6b2b09f0f2ff88cc79f`. Grammar: typescript. Status: syntax-clean.

- function_declaration generateConcreteIntegerTestCases @37-52
- arrow_function (anonymous) @42-50
- arrow_function (anonymous) @43-49
- arrow_function (anonymous) @46-49
- function_declaration generateAbstractIntegerTestCases @55-70
- arrow_function (anonymous) @56-68
- arrow_function (anonymous) @57-67
- arrow_function (anonymous) @60-67
- function_declaration generateFloatTestCases @72-93
- arrow_function (anonymous) @77-91
- arrow_function (anonymous) @78-90
- arrow_function (anonymous) @81-90
- arrow_function (anonymous) @98-110
- arrow_function (anonymous) @99-110
- arrow_function (anonymous) @100-109
- arrow_function (anonymous) @112-112
- arrow_function (anonymous) @115-117
- arrow_function (anonymous) @118-120
- arrow_function (anonymous) @121-123
- arrow_function (anonymous) @124-126
- arrow_function (anonymous) @127-129

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/clamp.spec.ts

Blob: `c4e2fbfacf768002800cac65d057b9bbb44e4c37`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @29-32
- arrow_function (anonymous) @34-44
- arrow_function (anonymous) @49-50
- arrow_function (anonymous) @52-55
- arrow_function (anonymous) @60-61
- arrow_function (anonymous) @63-66
- arrow_function (anonymous) @71-74
- arrow_function (anonymous) @76-86
- arrow_function (anonymous) @91-92
- arrow_function (anonymous) @94-97
- arrow_function (anonymous) @102-103
- arrow_function (anonymous) @105-109

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cos.cache.ts

Blob: `11c9f50a1f73e5335eb46fa89f997adbd087c12f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-19
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cos.spec.ts

Blob: `f24190d9a8bbf44f177cd2c6ae8821d9743fd844`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @49-50
- arrow_function (anonymous) @52-55
- arrow_function (anonymous) @60-61
- arrow_function (anonymous) @63-67

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cosh.cache.ts

Blob: `0c90f178df866f439851faf660df96b3402b0968`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @6-19
- arrow_function (anonymous) @7-19
- arrow_function (anonymous) @8-18
- arrow_function (anonymous) @21-21

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cosh.spec.ts

Blob: `7df2a0a530b4868fd5eafafeef2d64b7698535d0`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/countLeadingZeros.spec.ts

Blob: `e508c91fb8c37c9248baec80ad2ef430def0134b`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @25-26
- arrow_function (anonymous) @28-135
- arrow_function (anonymous) @140-141
- arrow_function (anonymous) @143-250

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/countOneBits.spec.ts

Blob: `89d4177d60138d8f27c1643de44d89ed62850a02`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-25
- arrow_function (anonymous) @27-134
- arrow_function (anonymous) @139-140
- arrow_function (anonymous) @142-249

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/countTrailingZeros.spec.ts

Blob: `b1440631ffcab22d1d872c11b24d59b14f88c003`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @25-26
- arrow_function (anonymous) @28-135
- arrow_function (anonymous) @140-141
- arrow_function (anonymous) @143-250

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cross.cache.ts

Blob: `396789b4ed6471eea6cfb20b004bfb2cf14e5555`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-21
- arrow_function (anonymous) @8-21
- arrow_function (anonymous) @9-20
- arrow_function (anonymous) @23-23

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/cross.spec.ts

Blob: `0f5bdfe9321c390f090f98d05d39355f574f61b6`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @23-33
- arrow_function (anonymous) @38-38
- arrow_function (anonymous) @39-42
- arrow_function (anonymous) @47-47
- arrow_function (anonymous) @48-52

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/degrees.cache.ts

Blob: `16abe41f347452aac2afed951a0f7363d23f6a1f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-20
- arrow_function (anonymous) @9-19
- arrow_function (anonymous) @22-22

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/degrees.spec.ts

Blob: `f3fb4b97503e69f79858cbcc849da2d3f48cb98f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/derivatives.cache.ts

Blob: `ebd414f395fe32342e1049c2262a9a8180ce8407`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @6-13

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/derivatives.ts

Blob: `b3d1f9d64ca5ebf7a8919d5e2352352a7d0ff610`. Grammar: typescript. Status: syntax-clean.

- function_declaration runDerivativeTest @16-234
- arrow_function (anonymous) @182-233
- arrow_function (anonymous) @185-227

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/determinant.cache.ts

Blob: `3c677444c43052f020364f639d51543ac3d66e19`. Grammar: typescript. Status: syntax-clean.

- type_alias_declaration Dim @63-63
- type_alias_declaration FPWidth @64-64
- function_declaration randomMatrixEntry @71-89
- function_declaration randomSquareMatrix @96-107
- arrow_function (anonymous) @97-97
- type_alias_declaration detFnType @109-109
- function_declaration nonTrivialMatrices @112-117
- arrow_function detInterval @113-113
- arrow_function (anonymous) @114-114
- arrow_function (anonymous) @115-115
- arrow_function (anonymous) @121-135
- arrow_function (anonymous) @122-135
- arrow_function (anonymous) @123-134
- arrow_function (anonymous) @125-126
- arrow_function (anonymous) @137-137
- arrow_function (anonymous) @141-155
- arrow_function (anonymous) @142-155
- arrow_function (anonymous) @143-154
- arrow_function (anonymous) @145-146
- arrow_function (anonymous) @157-157
- arrow_function (anonymous) @161-176
- arrow_function (anonymous) @162-175
- arrow_function (anonymous) @165-166
- arrow_function (anonymous) @177-177

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/determinant.spec.ts

Blob: `8341988109cec131b777e8587de0fb32d126b47b`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @23-34
- arrow_function (anonymous) @39-39
- arrow_function (anonymous) @40-48
- arrow_function (anonymous) @53-53
- arrow_function (anonymous) @54-63

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/distance.cache.ts

Blob: `0b37190cf7af92d6c2ed33836861fe8d676be229`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @6-20
- arrow_function (anonymous) @7-20
- arrow_function (anonymous) @8-19
- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @26-42
- arrow_function (anonymous) @27-41
- arrow_function (anonymous) @28-41
- arrow_function (anonymous) @29-40
- arrow_function (anonymous) @44-44

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/distance.spec.ts

Blob: `87956bb677d358bb58ecf54e3848d800bdcd11ba`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-24
- arrow_function (anonymous) @25-35
- arrow_function (anonymous) @40-40
- arrow_function (anonymous) @41-51
- arrow_function (anonymous) @56-56
- arrow_function (anonymous) @57-67
- arrow_function (anonymous) @72-72
- arrow_function (anonymous) @73-83
- arrow_function (anonymous) @88-88
- arrow_function (anonymous) @89-92
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-103
- arrow_function (anonymous) @108-108
- arrow_function (anonymous) @109-114
- arrow_function (anonymous) @119-119
- arrow_function (anonymous) @120-125
- arrow_function (anonymous) @130-130
- arrow_function (anonymous) @131-135
- arrow_function (anonymous) @140-140
- arrow_function (anonymous) @141-147
- arrow_function (anonymous) @152-152
- arrow_function (anonymous) @153-159
- arrow_function (anonymous) @164-164
- arrow_function (anonymous) @165-171

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dot.cache.ts

Blob: `6d1f22def1375e96823bda23896566f9d7df2e88`. Grammar: typescript. Status: syntax-clean.

- function_declaration ai_dot @21-53
- arrow_function (anonymous) @23-23
- arrow_function (anonymous) @26-26
- arrow_function (anonymous) @37-47
- arrow_function (anonymous) @39-45
- function_declaration ci_dot @55-58
- arrow_function (anonymous) @57-57
- arrow_function (anonymous) @62-83
- arrow_function (anonymous) @63-82
- arrow_function (anonymous) @64-82
- arrow_function (anonymous) @67-81
- arrow_function (anonymous) @85-85
- arrow_function (anonymous) @89-91
- arrow_function (anonymous) @92-94
- arrow_function (anonymous) @95-97
- arrow_function (anonymous) @98-100
- arrow_function (anonymous) @101-103
- arrow_function (anonymous) @104-106
- arrow_function (anonymous) @107-109
- arrow_function (anonymous) @110-112
- arrow_function (anonymous) @113-115

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dot.spec.ts

Blob: `a6155e01afbd4b71cb608549db1276ad6c2e0152`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @23-33
- arrow_function (anonymous) @38-38
- arrow_function (anonymous) @39-49
- arrow_function (anonymous) @54-54
- arrow_function (anonymous) @55-65
- arrow_function (anonymous) @70-70
- arrow_function (anonymous) @71-74
- arrow_function (anonymous) @79-79
- arrow_function (anonymous) @80-83
- arrow_function (anonymous) @88-88
- arrow_function (anonymous) @89-92
- arrow_function (anonymous) @97-97
- arrow_function (anonymous) @98-101
- arrow_function (anonymous) @106-106
- arrow_function (anonymous) @107-110
- arrow_function (anonymous) @115-115
- arrow_function (anonymous) @116-119
- arrow_function (anonymous) @124-124
- arrow_function (anonymous) @125-135
- arrow_function (anonymous) @140-140
- arrow_function (anonymous) @141-151
- arrow_function (anonymous) @156-156
- arrow_function (anonymous) @157-167
- arrow_function (anonymous) @172-172
- arrow_function (anonymous) @173-178
- arrow_function (anonymous) @183-183
- arrow_function (anonymous) @184-189
- arrow_function (anonymous) @194-194
- arrow_function (anonymous) @195-200
- arrow_function (anonymous) @205-205
- arrow_function (anonymous) @206-212
- arrow_function (anonymous) @217-217
- arrow_function (anonymous) @218-224
- arrow_function (anonymous) @229-229
- arrow_function (anonymous) @230-236

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dot4I8Packed.spec.ts

Blob: `4403d46f11748ee7f67dda77c99b3b6798141f9d`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @27-27
- arrow_function (anonymous) @28-74
- arrow_function dot4I8Packed @31-45
- arrow_function makeCase @66-68
- arrow_function (anonymous) @69-71

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dot4U8Packed.spec.ts

Blob: `5cc9d35ae59ef87b300505d86d45fb5cae993c5a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @26-26
- arrow_function (anonymous) @27-59
- arrow_function dot4U8Packed @30-38
- arrow_function makeCase @51-53
- arrow_function (anonymous) @54-56

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdx.spec.ts

Blob: `5da2b3f81bc9fc014cbc07e7d601dc26a1390848`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-31

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdxCoarse.spec.ts

Blob: `03fe32150f15f5d257844801c825450a89c6cd63`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-25
- arrow_function (anonymous) @27-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdxFine.spec.ts

Blob: `b3ee64ceadbbc7171f4e4cb2435d3e81a0234ae9`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @21-24
- arrow_function (anonymous) @26-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdy.spec.ts

Blob: `a236f0d0f1607f339a85310b482660d46f3c3ae2`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-25
- arrow_function (anonymous) @27-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdyCoarse.spec.ts

Blob: `c49382a8bae66fef00b39cbad966a2e8e4f82f40`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-25
- arrow_function (anonymous) @27-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/dpdyFine.spec.ts

Blob: `598e55ae591b2de7b6f3adb77d0ef8d41392ad93`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @21-24
- arrow_function (anonymous) @26-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/exp.cache.ts

Blob: `5ecc8b2d978c8bf5219f1e21ba289ff2a63b10da`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @28-30
- arrow_function (anonymous) @31-33
- arrow_function (anonymous) @34-36
- arrow_function (anonymous) @37-39
- arrow_function (anonymous) @40-43

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/exp.spec.ts

Blob: `d11fb726293f88d202b3fb13c9faf59020c11caf`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/exp2.cache.ts

Blob: `e2d0f1c16c97039ca331b2eb9882308c48534d8e`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @28-30
- arrow_function (anonymous) @31-33
- arrow_function (anonymous) @34-36
- arrow_function (anonymous) @37-39
- arrow_function (anonymous) @40-43

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/exp2.spec.ts

Blob: `a1e7bfadd613db3b636fcd684a07edb6bfd54d22`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/extractBits.spec.ts

Blob: `701709e9fc924bda59db11595b13cd9fa40a2177`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @46-46
- arrow_function (anonymous) @47-192
- arrow_function V @52-67
- arrow_function (anonymous) @197-197
- arrow_function (anonymous) @198-337
- arrow_function V @203-218

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/faceForward.cache.ts

Blob: `17a5d0fd8f0b0bf0ff7fe55ee0f9f8a3161f2b6f`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @28-59
- arrow_function (anonymous) @42-42
- arrow_function (anonymous) @49-49
- function_declaration generateCases @71-83
- arrow_function (anonymous) @81-81
- arrow_function (anonymous) @82-82
- arrow_function (anonymous) @87-121
- arrow_function (anonymous) @88-120
- arrow_function (anonymous) @89-120
- arrow_function (anonymous) @90-119
- arrow_function (anonymous) @123-123

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/faceForward.spec.ts

Blob: `aaf4f58ac03d6f422dca7e5134e50ec3cee3cac9`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @23-33
- arrow_function (anonymous) @38-38
- arrow_function (anonymous) @39-49
- arrow_function (anonymous) @54-54
- arrow_function (anonymous) @55-65
- arrow_function (anonymous) @70-70
- arrow_function (anonymous) @71-83
- arrow_function (anonymous) @88-88
- arrow_function (anonymous) @89-101
- arrow_function (anonymous) @106-106
- arrow_function (anonymous) @107-119
- arrow_function (anonymous) @124-124
- arrow_function (anonymous) @125-138
- arrow_function (anonymous) @143-143
- arrow_function (anonymous) @144-157
- arrow_function (anonymous) @162-162
- arrow_function (anonymous) @163-176

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/firstLeadingBit.spec.ts

Blob: `4ce90b7eb6780b15d03629561066075bb163be42`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @29-30
- arrow_function (anonymous) @32-139
- arrow_function (anonymous) @144-145
- arrow_function (anonymous) @147-350

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/firstTrailingBit.spec.ts

Blob: `04dcf4e60b7cf21691fb066602ef225aef6cf482`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @25-26
- arrow_function (anonymous) @28-135
- arrow_function (anonymous) @140-141
- arrow_function (anonymous) @143-250

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/floor.cache.ts

Blob: `0af966cfd257fdc9420d642416b0e83040ff9f66`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @15-23
- arrow_function (anonymous) @16-22
- arrow_function (anonymous) @24-24

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/floor.spec.ts

Blob: `78a5f33337d7164e6665f9c2ae2f716090e8bf0f`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fma.cache.ts

Blob: `20a61ce83794af4e07a935ba4c182d13cc0aa2ab`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-22
- arrow_function (anonymous) @8-22
- arrow_function (anonymous) @9-21
- arrow_function (anonymous) @24-24

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fma.spec.ts

Blob: `0905fcc45885c4464ce70fcc791cdb248004cde7`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fract.cache.ts

Blob: `02c9ebfcdf4db5b76fef0155feb79de5f6aab363`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @36-44
- arrow_function (anonymous) @37-43
- arrow_function (anonymous) @45-45
- arrow_function abstract_cases @48-57
- arrow_function (anonymous) @52-55

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fract.spec.ts

Blob: `b015b35412f2785b117e0e221e2865a456136e93`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @24-27
- arrow_function (anonymous) @29-39
- arrow_function (anonymous) @44-45
- arrow_function (anonymous) @47-50
- arrow_function (anonymous) @55-56
- arrow_function (anonymous) @58-62

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/frexp.cache.ts

Blob: `2211e2adc9cd836c12354b5fcbf17b57f3f088c2`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCaseFract @15-40
- arrow_function (anonymous) @21-21
- arrow_function (anonymous) @22-22
- arrow_function (anonymous) @26-26
- arrow_function (anonymous) @27-27
- arrow_function (anonymous) @31-31
- arrow_function (anonymous) @35-37
- function_declaration makeCaseExp @43-70
- arrow_function (anonymous) @49-49
- arrow_function (anonymous) @50-51
- arrow_function (anonymous) @51-51
- arrow_function (anonymous) @55-55
- arrow_function (anonymous) @56-57
- arrow_function (anonymous) @61-61
- arrow_function (anonymous) @65-67
- arrow_function (anonymous) @74-83
- arrow_function (anonymous) @75-82
- arrow_function (anonymous) @76-82
- arrow_function (anonymous) @77-81
- arrow_function (anonymous) @80-80
- arrow_function (anonymous) @85-85
- arrow_function (anonymous) @89-96
- arrow_function (anonymous) @90-96
- arrow_function (anonymous) @91-95
- arrow_function (anonymous) @94-94
- arrow_function (anonymous) @98-98

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/frexp.spec.ts

Blob: `b98299ae20303c43cf51aba2b1decaea7090a74a`. Grammar: typescript. Status: syntax-clean.

- function_declaration fractBuilder @34-36
- arrow_function (anonymous) @35-35
- function_declaration expBuilder @39-41
- arrow_function (anonymous) @40-40
- function_declaration abstractFractBuilder @44-46
- arrow_function (anonymous) @45-45
- function_declaration abstractExpBuilder @49-51
- arrow_function (anonymous) @50-50
- arrow_function (anonymous) @65-65
- arrow_function (anonymous) @66-69
- arrow_function (anonymous) @83-83
- arrow_function (anonymous) @84-87
- arrow_function (anonymous) @101-101
- arrow_function (anonymous) @102-105
- arrow_function (anonymous) @119-119
- arrow_function (anonymous) @120-123
- arrow_function (anonymous) @137-137
- arrow_function (anonymous) @138-141
- arrow_function (anonymous) @155-155
- arrow_function (anonymous) @156-159
- arrow_function (anonymous) @173-173
- arrow_function (anonymous) @174-177
- arrow_function (anonymous) @191-191
- arrow_function (anonymous) @192-195
- arrow_function (anonymous) @209-209
- arrow_function (anonymous) @210-213
- arrow_function (anonymous) @227-227
- arrow_function (anonymous) @228-231
- arrow_function (anonymous) @245-245
- arrow_function (anonymous) @246-249
- arrow_function (anonymous) @263-263
- arrow_function (anonymous) @264-267
- arrow_function (anonymous) @281-281
- arrow_function (anonymous) @282-285
- arrow_function (anonymous) @299-299
- arrow_function (anonymous) @300-303
- arrow_function (anonymous) @317-317
- arrow_function (anonymous) @318-321
- arrow_function (anonymous) @335-335
- arrow_function (anonymous) @336-339
- arrow_function (anonymous) @353-353
- arrow_function (anonymous) @354-358
- arrow_function (anonymous) @372-372
- arrow_function (anonymous) @373-377
- arrow_function (anonymous) @391-391
- arrow_function (anonymous) @392-396
- arrow_function (anonymous) @410-410
- arrow_function (anonymous) @411-415
- arrow_function (anonymous) @429-429
- arrow_function (anonymous) @430-434
- arrow_function (anonymous) @448-448
- arrow_function (anonymous) @449-453
- arrow_function (anonymous) @467-467
- arrow_function (anonymous) @468-472
- arrow_function (anonymous) @486-486
- arrow_function (anonymous) @487-491

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fwidth.cache.ts

Blob: `5877c396ba4c56f6571cf8e4d8914cf0efc95c4a`. Grammar: typescript. Status: syntax-clean.

- function_declaration makeCase @7-35
- arrow_function (anonymous) @9-13
- arrow_function (anonymous) @14-18
- arrow_function (anonymous) @19-23
- arrow_function (anonymous) @24-28
- arrow_function (anonymous) @29-29
- arrow_function (anonymous) @38-51
- arrow_function (anonymous) @44-50

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fwidth.spec.ts

Blob: `8d50cca688c9f2a9de6a465c8f6fe8ca5f0bbf0d`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @21-24
- arrow_function (anonymous) @26-29

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fwidth.ts

Blob: `2f75b73084eed75636be24140415463c55253180`. Grammar: typescript. Status: syntax-clean.

- function_declaration runFWidthTest @18-238
- arrow_function (anonymous) @185-237
- arrow_function (anonymous) @189-231

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fwidthCoarse.spec.ts

Blob: `54e2d1a9bd3a526cfb55f9789e2dad5c38e350aa`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @21-24
- arrow_function (anonymous) @26-29

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/fwidthFine.spec.ts

Blob: `eab55f1b2dc794e9abc98917926c54a21837d003`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @21-24
- arrow_function (anonymous) @26-30

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/insertBits.spec.ts

Blob: `802a94a3b6fe446a50c59fbf782512b379f6856a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @31-35
- arrow_function (anonymous) @37-380
- arrow_function V @42-70
- arrow_function (anonymous) @384-423

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/inversesqrt.cache.ts

Blob: `e50d6d486694791707b39dd24a0a814f2ed8733a`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @7-18
- arrow_function (anonymous) @19-30
- arrow_function (anonymous) @31-43

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/inversesqrt.spec.ts

Blob: `da10bfa08054799f820a9ff6df83fd53ed6fc9b3`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @23-26
- arrow_function (anonymous) @28-38
- arrow_function (anonymous) @43-44
- arrow_function (anonymous) @46-49
- arrow_function (anonymous) @54-55
- arrow_function (anonymous) @57-61

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/ldexp.cache.ts

Blob: `cf9194319b17d24f870a83e7e3759da3ca32e1c2`. Grammar: typescript. Status: syntax-clean.

- arrow_function makeCase @13-32
- arrow_function (anonymous) @36-57
- arrow_function (anonymous) @37-57
- arrow_function (anonymous) @38-56
- arrow_function (anonymous) @45-45
- arrow_function (anonymous) @45-45
- arrow_function (anonymous) @51-54
- arrow_function (anonymous) @52-53
- arrow_function (anonymous) @59-59

### dom/webgpu/tests/cts/checkout/src/webgpu/shader/execution/expression/call/builtin/ldexp.spec.ts

Blob: `6864d68eef06f13d1f4b108b690ba3f7dedc8b25`. Grammar: typescript. Status: syntax-clean.

- arrow_function (anonymous) @31-34
- arrow_function (anonymous) @36-46
- arrow_function (anonymous) @51-52
- arrow_function (anonymous) @54-57
- arrow_function (anonymous) @62-63
- arrow_function (anonymous) @65-69

## Validation and limits

This is a declaration map. Function contracts, callers, memory ownership, thread use, generated bindings, feature selection, cleanup, and reasons need implementation and caller review. No compilation or runtime tests ran. Imports and includes are literal navigation hints only. No complete call graph is claimed.

## Retrieval correction

This copy preserves the source map in [b0055830-f396-4d1a-80b7-49ccb6a36025.md](b0055830-f396-4d1a-80b7-49ccb6a36025.md). The original was imported and committed by concurrent console maintenance during this study. Its full path metadata could exceed the console search budget. This copy uses component scope metadata while keeping every file path in the body. It adds no independent behavior evidence. Original record: `0be6f336983d479b61b75d5d3e09708bd86bbc41f18134759714bb025e79e39a`.
