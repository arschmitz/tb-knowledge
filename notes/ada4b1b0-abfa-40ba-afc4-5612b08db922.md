<!-- knowledge: {"repository":"git:314d8065c5ad68c7e5c5f92d","at":"2026-10-13T04:14:46.642314+00:00","paths":["third_party/llama.cpp/ggml/src/ggml-cpu/repack.cpp","third_party/llama.cpp/ggml/src/ggml-cpu/repack.h","third_party/llama.cpp/ggml/src/ggml-cpu/simd-gemm.h","third_party/llama.cpp/ggml/src/ggml-cpu/simd-mappings.h","third_party/llama.cpp/ggml/src/ggml-cpu/traits.cpp","third_party/llama.cpp/ggml/src/ggml-cpu/traits.h","third_party/llama.cpp/ggml/src/ggml-cpu/unary-ops.cpp","third_party/llama.cpp/ggml/src/ggml-cpu/unary-ops.h","third_party/llama.cpp/ggml/src/ggml-cpu/vec.cpp","third_party/llama.cpp/ggml/src/ggml-cpu/vec.h","third_party/llama.cpp/ggml/src/ggml-impl.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-common.cpp","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-common.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-context.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-context.m","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device-m.m","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device.cpp","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-impl.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-ops.cpp","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-ops.h","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal.cpp","third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal.metal","third_party/llama.cpp/ggml/src/ggml-opt.cpp","third_party/llama.cpp/ggml/src/ggml-quants.c","third_party/llama.cpp/ggml/src/ggml-quants.h","third_party/llama.cpp/ggml/src/ggml-threading.cpp","third_party/llama.cpp/ggml/src/ggml-threading.h","third_party/llama.cpp/ggml/src/ggml.cpp","third_party/llama.cpp/ggml/src/gguf.cpp","third_party/llama.cpp/include-order.patch","third_party/llama.cpp/include/llama.h","third_party/llama.cpp/load-from-buffer-or-fd.patch","third_party/llama.cpp/metal-disable.patch","third_party/llama.cpp/metal-event-availability.patch","third_party/llama.cpp/metal-mul-mv-short-fallback.patch","third_party/llama.cpp/missing-includes.patch","third_party/llama.cpp/moz-overrides.h","third_party/llama.cpp/moz.build","third_party/llama.cpp/moz.yaml","third_party/llama.cpp/no-future.patch","third_party/llama.cpp/no-wstring.patch","third_party/llama.cpp/profiler-hooks.patch","third_party/llama.cpp/random_device.patch","third_party/llama.cpp/requirements.txt","third_party/llama.cpp/run_parser.py","third_party/llama.cpp/skip-metadata-dump.patch","third_party/llama.cpp/sources.mozbuild","third_party/llama.cpp/src/CMakeLists.txt","third_party/llama.cpp/src/llama-adapter.cpp","third_party/llama.cpp/src/llama-adapter.h","third_party/llama.cpp/src/llama-arch.cpp","third_party/llama.cpp/src/llama-arch.h","third_party/llama.cpp/src/llama-batch.cpp","third_party/llama.cpp/src/llama-batch.h","third_party/llama.cpp/src/llama-chat.cpp","third_party/llama.cpp/src/llama-chat.h","third_party/llama.cpp/src/llama-context.cpp","third_party/llama.cpp/src/llama-context.h","third_party/llama.cpp/src/llama-cparams.cpp","third_party/llama.cpp/src/llama-cparams.h","third_party/llama.cpp/src/llama-ext.h","third_party/llama.cpp/src/llama-grammar.cpp","third_party/llama.cpp/src/llama-grammar.h","third_party/llama.cpp/src/llama-graph.cpp","third_party/llama.cpp/src/llama-graph.h","third_party/llama.cpp/src/llama-hparams.cpp","third_party/llama.cpp/src/llama-hparams.h","third_party/llama.cpp/src/llama-impl.cpp","third_party/llama.cpp/src/llama-impl.h","third_party/llama.cpp/src/llama-io.cpp","third_party/llama.cpp/src/llama-io.h","third_party/llama.cpp/src/llama-kv-cache-dsa.cpp","third_party/llama.cpp/src/llama-kv-cache-dsa.h","third_party/llama.cpp/src/llama-kv-cache-iswa.cpp","third_party/llama.cpp/src/llama-kv-cache-iswa.h","third_party/llama.cpp/src/llama-kv-cache.cpp","third_party/llama.cpp/src/llama-kv-cache.h","third_party/llama.cpp/src/llama-kv-cells.h","third_party/llama.cpp/src/llama-memory-hybrid-iswa.cpp","third_party/llama.cpp/src/llama-memory-hybrid-iswa.h","third_party/llama.cpp/src/llama-memory-hybrid.cpp","third_party/llama.cpp/src/llama-memory-hybrid.h","third_party/llama.cpp/src/llama-memory-recurrent.cpp","third_party/llama.cpp/src/llama-memory-recurrent.h","third_party/llama.cpp/src/llama-memory.cpp","third_party/llama.cpp/src/llama-memory.h","third_party/llama.cpp/src/llama-mmap.cpp","third_party/llama.cpp/src/llama-mmap.h","third_party/llama.cpp/src/llama-model-loader.cpp","third_party/llama.cpp/src/llama-model-loader.h","third_party/llama.cpp/src/llama-model-saver.cpp","third_party/llama.cpp/src/llama-model-saver.h","third_party/llama.cpp/src/llama-model.cpp","third_party/llama.cpp/src/llama-model.h","third_party/llama.cpp/src/llama-quant.h","third_party/llama.cpp/src/llama-sampler.cpp","third_party/llama.cpp/src/llama-sampler.h","third_party/llama.cpp/src/llama-vocab.cpp","third_party/llama.cpp/src/llama-vocab.h","third_party/llama.cpp/src/llama.cpp","third_party/llama.cpp/src/models/afmoe.cpp","third_party/llama.cpp/src/models/apertus.cpp","third_party/llama.cpp/src/models/arcee.cpp","third_party/llama.cpp/src/models/arctic.cpp","third_party/llama.cpp/src/models/arwkv7.cpp","third_party/llama.cpp/src/models/baichuan.cpp","third_party/llama.cpp/src/models/bailingmoe.cpp","third_party/llama.cpp/src/models/bailingmoe2.cpp","third_party/llama.cpp/src/models/bert.cpp","third_party/llama.cpp/src/models/bitnet.cpp","third_party/llama.cpp/src/models/bloom.cpp","third_party/llama.cpp/src/models/chameleon.cpp","third_party/llama.cpp/src/models/chatglm.cpp","third_party/llama.cpp/src/models/codeshell.cpp","third_party/llama.cpp/src/models/cogvlm.cpp","third_party/llama.cpp/src/models/cohere2.cpp","third_party/llama.cpp/src/models/cohere2moe.cpp","third_party/llama.cpp/src/models/command-r.cpp","third_party/llama.cpp/src/models/dbrx.cpp","third_party/llama.cpp/src/models/deci.cpp","third_party/llama.cpp/src/models/deepseek.cpp","third_party/llama.cpp/src/models/deepseek2.cpp","third_party/llama.cpp/src/models/deepseek2ocr.cpp","third_party/llama.cpp/src/models/deepseek32.cpp","third_party/llama.cpp/src/models/delta-net-base.cpp","third_party/llama.cpp/src/models/dots1.cpp","third_party/llama.cpp/src/models/dream.cpp","third_party/llama.cpp/src/models/eagle3.cpp","third_party/llama.cpp/src/models/ernie4-5-moe.cpp","third_party/llama.cpp/src/models/ernie4-5.cpp","third_party/llama.cpp/src/models/eurobert.cpp","third_party/llama.cpp/src/models/exaone-moe.cpp","third_party/llama.cpp/src/models/exaone.cpp","third_party/llama.cpp/src/models/exaone4.cpp","third_party/llama.cpp/src/models/falcon-h1.cpp","third_party/llama.cpp/src/models/falcon.cpp","third_party/llama.cpp/src/models/gemma-embedding.cpp","third_party/llama.cpp/src/models/gemma.cpp","third_party/llama.cpp/src/models/gemma2.cpp","third_party/llama.cpp/src/models/gemma3.cpp","third_party/llama.cpp/src/models/gemma3n.cpp","third_party/llama.cpp/src/models/gemma4-assistant.cpp","third_party/llama.cpp/src/models/gemma4.cpp","third_party/llama.cpp/src/models/glm-dsa.cpp","third_party/llama.cpp/src/models/glm4-moe.cpp","third_party/llama.cpp/src/models/glm4.cpp","third_party/llama.cpp/src/models/gpt2.cpp","third_party/llama.cpp/src/models/gptneox.cpp","third_party/llama.cpp/src/models/granite-hybrid.cpp","third_party/llama.cpp/src/models/granite-moe.cpp","third_party/llama.cpp/src/models/granite.cpp","third_party/llama.cpp/src/models/grok.cpp","third_party/llama.cpp/src/models/grovemoe.cpp","third_party/llama.cpp/src/models/hunyuan-dense.cpp","third_party/llama.cpp/src/models/hunyuan-moe.cpp","third_party/llama.cpp/src/models/hunyuan-vl.cpp","third_party/llama.cpp/src/models/internlm2.cpp","third_party/llama.cpp/src/models/jais.cpp","third_party/llama.cpp/src/models/jais2.cpp","third_party/llama.cpp/src/models/jamba.cpp","third_party/llama.cpp/src/models/jina-bert-v2.cpp","third_party/llama.cpp/src/models/jina-bert-v3.cpp","third_party/llama.cpp/src/models/kimi-linear.cpp","third_party/llama.cpp/src/models/lfm2.cpp","third_party/llama.cpp/src/models/lfm2moe.cpp","third_party/llama.cpp/src/models/llada-moe.cpp","third_party/llama.cpp/src/models/llada.cpp","third_party/llama.cpp/src/models/llama-embed.cpp","third_party/llama.cpp/src/models/llama4.cpp","third_party/llama.cpp/src/models/maincoder.cpp","third_party/llama.cpp/src/models/mamba-base.cpp","third_party/llama.cpp/src/models/mamba.cpp","third_party/llama.cpp/src/models/mamba2.cpp","third_party/llama.cpp/src/models/mellum.cpp","third_party/llama.cpp/src/models/mimo2.cpp","third_party/llama.cpp/src/models/minicpm.cpp","third_party/llama.cpp/src/models/minicpm3.cpp","third_party/llama.cpp/src/models/minimax-m2.cpp","third_party/llama.cpp/src/models/mistral3.cpp","third_party/llama.cpp/src/models/mistral4.cpp","third_party/llama.cpp/src/models/model-llama.cpp","third_party/llama.cpp/src/models/models.h","third_party/llama.cpp/src/models/modern-bert.cpp","third_party/llama.cpp/src/models/mpt.cpp","third_party/llama.cpp/src/models/nemotron-h-moe.cpp","third_party/llama.cpp/src/models/nemotron-h.cpp","third_party/llama.cpp/src/models/nemotron.cpp","third_party/llama.cpp/src/models/neo-bert.cpp","third_party/llama.cpp/src/models/nomic-bert-moe.cpp","third_party/llama.cpp/src/models/nomic-bert.cpp","third_party/llama.cpp/src/models/olmo.cpp","third_party/llama.cpp/src/models/olmo2.cpp","third_party/llama.cpp/src/models/olmoe.cpp","third_party/llama.cpp/src/models/openai-moe.cpp","third_party/llama.cpp/src/models/openelm.cpp","third_party/llama.cpp/src/models/orion.cpp","third_party/llama.cpp/src/models/paddleocr.cpp","third_party/llama.cpp/src/models/pangu-embed.cpp","third_party/llama.cpp/src/models/phi2.cpp","third_party/llama.cpp/src/models/phi3.cpp","third_party/llama.cpp/src/models/phimoe.cpp","third_party/llama.cpp/src/models/plamo.cpp","third_party/llama.cpp/src/models/plamo2.cpp","third_party/llama.cpp/src/models/plamo3.cpp","third_party/llama.cpp/src/models/plm.cpp","third_party/llama.cpp/src/models/qwen.cpp","third_party/llama.cpp/src/models/qwen2.cpp","third_party/llama.cpp/src/models/qwen2moe.cpp","third_party/llama.cpp/src/models/qwen2vl.cpp","third_party/llama.cpp/src/models/qwen3.cpp","third_party/llama.cpp/src/models/qwen35.cpp","third_party/llama.cpp/src/models/qwen35moe.cpp","third_party/llama.cpp/src/models/qwen3moe.cpp","third_party/llama.cpp/src/models/qwen3next.cpp","third_party/llama.cpp/src/models/qwen3vl.cpp","third_party/llama.cpp/src/models/qwen3vlmoe.cpp","third_party/llama.cpp/src/models/refact.cpp","third_party/llama.cpp/src/models/rnd1.cpp","third_party/llama.cpp/src/models/rwkv6-base.cpp","third_party/llama.cpp/src/models/rwkv6.cpp","third_party/llama.cpp/src/models/rwkv6qwen2.cpp","third_party/llama.cpp/src/models/rwkv7-base.cpp","third_party/llama.cpp/src/models/rwkv7.cpp","third_party/llama.cpp/src/models/seed-oss.cpp","third_party/llama.cpp/src/models/smallthinker.cpp","third_party/llama.cpp/src/models/smollm3.cpp","third_party/llama.cpp/src/models/stablelm.cpp","third_party/llama.cpp/src/models/starcoder.cpp","third_party/llama.cpp/src/models/starcoder2.cpp","third_party/llama.cpp/src/models/step35.cpp","third_party/llama.cpp/src/models/t5.cpp","third_party/llama.cpp/src/models/t5encoder.cpp","third_party/llama.cpp/src/models/talkie.cpp","third_party/llama.cpp/src/models/wavtokenizer-dec.cpp","third_party/llama.cpp/src/models/xverse.cpp","third_party/llama.cpp/src/unicode-data.cpp","third_party/llama.cpp/src/unicode-data.h","third_party/llama.cpp/src/unicode.cpp","third_party/llama.cpp/src/unicode.h","third_party/llama.cpp/static-ctors.patch","third_party/moz.build","third_party/msgpack/LICENSE_1_0.txt","third_party/msgpack/include/msgpack.h","third_party/msgpack/include/msgpack.hpp","third_party/msgpack/include/msgpack/adaptor/adaptor_base.hpp","third_party/msgpack/include/msgpack/adaptor/adaptor_base_decl.hpp","third_party/msgpack/include/msgpack/adaptor/array_ref.hpp","third_party/msgpack/include/msgpack/adaptor/array_ref_decl.hpp","third_party/msgpack/include/msgpack/adaptor/bool.hpp","third_party/msgpack/include/msgpack/adaptor/boost/fusion.hpp","third_party/msgpack/include/msgpack/adaptor/boost/msgpack_variant.hpp","third_party/msgpack/include/msgpack/adaptor/boost/msgpack_variant_decl.hpp","third_party/msgpack/include/msgpack/adaptor/boost/optional.hpp","third_party/msgpack/include/msgpack/adaptor/boost/string_ref.hpp","third_party/msgpack/include/msgpack/adaptor/boost/string_view.hpp","third_party/msgpack/include/msgpack/adaptor/carray.hpp","third_party/msgpack/include/msgpack/adaptor/char_ptr.hpp","third_party/msgpack/include/msgpack/adaptor/check_container_size.hpp","third_party/msgpack/include/msgpack/adaptor/check_container_size_decl.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/array.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/array_char.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/array_unsigned_char.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/chrono.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/forward_list.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/reference_wrapper.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/shared_ptr.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/tuple.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/unique_ptr.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/unordered_map.hpp","third_party/msgpack/include/msgpack/adaptor/cpp11/unordered_set.hpp","third_party/msgpack/include/msgpack/adaptor/cpp17/byte.hpp","third_party/msgpack/include/msgpack/adaptor/cpp17/carray_byte.hpp","third_party/msgpack/include/msgpack/adaptor/cpp17/optional.hpp","third_party/msgpack/include/msgpack/adaptor/cpp17/string_view.hpp","third_party/msgpack/include/msgpack/adaptor/cpp17/vector_byte.hpp","third_party/msgpack/include/msgpack/adaptor/define.hpp","third_party/msgpack/include/msgpack/adaptor/define_decl.hpp","third_party/msgpack/include/msgpack/adaptor/deque.hpp","third_party/msgpack/include/msgpack/adaptor/ext.hpp","third_party/msgpack/include/msgpack/adaptor/ext_decl.hpp","third_party/msgpack/include/msgpack/adaptor/fixint.hpp","third_party/msgpack/include/msgpack/adaptor/fixint_decl.hpp","third_party/msgpack/include/msgpack/adaptor/float.hpp","third_party/msgpack/include/msgpack/adaptor/int.hpp","third_party/msgpack/include/msgpack/adaptor/int_decl.hpp","third_party/msgpack/include/msgpack/adaptor/list.hpp","third_party/msgpack/include/msgpack/adaptor/map.hpp","third_party/msgpack/include/msgpack/adaptor/map_decl.hpp","third_party/msgpack/include/msgpack/adaptor/msgpack_tuple.hpp","third_party/msgpack/include/msgpack/adaptor/msgpack_tuple_decl.hpp","third_party/msgpack/include/msgpack/adaptor/nil.hpp","third_party/msgpack/include/msgpack/adaptor/nil_decl.hpp","third_party/msgpack/include/msgpack/adaptor/pair.hpp","third_party/msgpack/include/msgpack/adaptor/raw.hpp","third_party/msgpack/include/msgpack/adaptor/raw_decl.hpp","third_party/msgpack/include/msgpack/adaptor/set.hpp","third_party/msgpack/include/msgpack/adaptor/size_equal_only.hpp","third_party/msgpack/include/msgpack/adaptor/size_equal_only_decl.hpp","third_party/msgpack/include/msgpack/adaptor/string.hpp","third_party/msgpack/include/msgpack/adaptor/tr1/unordered_map.hpp","third_party/msgpack/include/msgpack/adaptor/tr1/unordered_set.hpp","third_party/msgpack/include/msgpack/adaptor/v4raw.hpp","third_party/msgpack/include/msgpack/adaptor/v4raw_decl.hpp","third_party/msgpack/include/msgpack/adaptor/vector.hpp","third_party/msgpack/include/msgpack/adaptor/vector_bool.hpp","third_party/msgpack/include/msgpack/adaptor/vector_char.hpp","third_party/msgpack/include/msgpack/adaptor/vector_unsigned_char.hpp","third_party/msgpack/include/msgpack/cpp_config.hpp","third_party/msgpack/include/msgpack/cpp_config_decl.hpp","third_party/msgpack/include/msgpack/create_object_visitor.hpp","third_party/msgpack/include/msgpack/create_object_visitor_decl.hpp","third_party/msgpack/include/msgpack/fbuffer.h","third_party/msgpack/include/msgpack/fbuffer.hpp","third_party/msgpack/include/msgpack/fbuffer_decl.hpp","third_party/msgpack/include/msgpack/gcc_atomic.h","third_party/msgpack/include/msgpack/gcc_atomic.hpp","third_party/msgpack/include/msgpack/iterator.hpp","third_party/msgpack/include/msgpack/iterator_decl.hpp","third_party/msgpack/include/msgpack/meta.hpp","third_party/msgpack/include/msgpack/meta_decl.hpp","third_party/msgpack/include/msgpack/null_visitor.hpp","third_party/msgpack/include/msgpack/null_visitor_decl.hpp","third_party/msgpack/include/msgpack/object.h","third_party/msgpack/include/msgpack/object.hpp","third_party/msgpack/include/msgpack/object_decl.hpp","third_party/msgpack/include/msgpack/object_fwd.hpp","third_party/msgpack/include/msgpack/object_fwd_decl.hpp","third_party/msgpack/include/msgpack/pack.h","third_party/msgpack/include/msgpack/pack.hpp","third_party/msgpack/include/msgpack/pack_decl.hpp","third_party/msgpack/include/msgpack/pack_define.h","third_party/msgpack/include/msgpack/pack_template.h","third_party/msgpack/include/msgpack/parse.hpp","third_party/msgpack/include/msgpack/parse_decl.hpp","third_party/msgpack/include/msgpack/parse_return.hpp","third_party/msgpack/include/msgpack/predef.h","third_party/msgpack/include/msgpack/predef/architecture.h","third_party/msgpack/include/msgpack/predef/architecture/alpha.h","third_party/msgpack/include/msgpack/predef/architecture/arm.h","third_party/msgpack/include/msgpack/predef/architecture/blackfin.h","third_party/msgpack/include/msgpack/predef/architecture/convex.h","third_party/msgpack/include/msgpack/predef/architecture/ia64.h","third_party/msgpack/include/msgpack/predef/architecture/m68k.h","third_party/msgpack/include/msgpack/predef/architecture/mips.h","third_party/msgpack/include/msgpack/predef/architecture/parisc.h","third_party/msgpack/include/msgpack/predef/architecture/ppc.h","third_party/msgpack/include/msgpack/predef/architecture/pyramid.h","third_party/msgpack/include/msgpack/predef/architecture/rs6k.h","third_party/msgpack/include/msgpack/predef/architecture/sparc.h","third_party/msgpack/include/msgpack/predef/architecture/superh.h","third_party/msgpack/include/msgpack/predef/architecture/sys370.h","third_party/msgpack/include/msgpack/predef/architecture/sys390.h","third_party/msgpack/include/msgpack/predef/architecture/x86.h","third_party/msgpack/include/msgpack/predef/architecture/x86/32.h","third_party/msgpack/include/msgpack/predef/architecture/x86/64.h","third_party/msgpack/include/msgpack/predef/architecture/z.h","third_party/msgpack/include/msgpack/predef/compiler.h","third_party/msgpack/include/msgpack/predef/compiler/borland.h","third_party/msgpack/include/msgpack/predef/compiler/clang.h","third_party/msgpack/include/msgpack/predef/compiler/comeau.h","third_party/msgpack/include/msgpack/predef/compiler/compaq.h","third_party/msgpack/include/msgpack/predef/compiler/diab.h","third_party/msgpack/include/msgpack/predef/compiler/digitalmars.h","third_party/msgpack/include/msgpack/predef/compiler/dignus.h","third_party/msgpack/include/msgpack/predef/compiler/edg.h","third_party/msgpack/include/msgpack/predef/compiler/ekopath.h","third_party/msgpack/include/msgpack/predef/compiler/gcc.h","third_party/msgpack/include/msgpack/predef/compiler/gcc_xml.h","third_party/msgpack/include/msgpack/predef/compiler/greenhills.h","third_party/msgpack/include/msgpack/predef/compiler/hp_acc.h","third_party/msgpack/include/msgpack/predef/compiler/iar.h","third_party/msgpack/include/msgpack/predef/compiler/ibm.h","third_party/msgpack/include/msgpack/predef/compiler/intel.h","third_party/msgpack/include/msgpack/predef/compiler/kai.h","third_party/msgpack/include/msgpack/predef/compiler/llvm.h"],"source":{"reference":"Git commit 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","revision":"1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b","status":"provisional","study":"architecture-study-20261013"}} -->
# firefox/third_party structural source map 957

Revision: `1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b`. This is an automated navigation map, not a behavior review.
Each row gives the repository-relative path, Git blob ID, byte size, role inferred from the path, declaration candidates, and literal dependency candidates. `@N` is the source line.
Candidates come from line-based patterns. They can miss multiline, anonymous, macro-generated, and language-specific declarations or match comments and fixture text. Dependencies are not resolved imports, runtime calls, or a complete graph. No candidates does not mean no functions or dependencies.
Imported code and tests are included. Binary and non-UTF-8 files have a census entry but no declaration extraction. Symlink contents are scanned as text, not followed. No uncommitted changes, build products, ignored files, or untracked files are studied.

## File map

`third_party/llama.cpp/ggml/src/ggml-cpu/repack.cpp` | `f18758f16bb62040333418bab06ce22efe826b20` | 195918 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: nearest_int@27; ggml_quantize_mat_q8_0_4x1_generic@52; ggml_quantize_mat_q8_K_4x1_generic@90; ggml_quantize_mat_q8_0_4x4_generic@135; ggml_quantize_mat_q8_0_4x8_generic@173; ggml_quantize_mat_q8_K_4x4_generic@211; ggml_quantize_mat_q8_K_4x8_generic@262; ggml_gemv_q4_0_4x4_q8_0_generic@754; ggml_gemv_q4_0_4x8_q8_0_generic@799; ggml_gemv_q4_0_8x8_q8_0_generic@843; ggml_gemv_q4_K_8x4_q8_K_generic@887; ggml_gemv_q4_K_8x8_q8_K_generic@958; ggml_gemv_q2_K_8x8_q8_K_generic@1029; ggml_gemv_q5_K_8x4_q8_K_generic@1105; ggml_gemv_q5_K_8x8_q8_K_generic@1109; ggml_gemv_q6_K_8x4_q8_K_generic@1114; ggml_gemv_q6_K_8x8_q8_K_generic@1118; ggml_gemv_iq4_nl_4x4_q8_0_generic@1122; ggml_gemv_iq4_nl_8x8_q8_0_generic@1160; ggml_gemv_mxfp4_4x4_q8_0_generic@1198; ggml_gemv_mxfp4_8x8_q8_0_generic@1236; ggml_gemv_q4_0_16x1_q8_0_generic@1370; ggml_gemv_q4_K_16x1_q8_K_generic@1414; ggml_gemv_iq4_nl_16x1_q8_0_generic@1487; ggml_gemv_q8_0_16x1_q8_0_generic@1525; ggml_gemv_q2_K_16x1_q8_K_generic@1566; ggml_gemm_q4_0_4x4_q8_0_generic@1658; ggml_gemm_q4_0_4x8_q8_0_generic@1714; ggml_gemm_q4_0_8x8_q8_0_generic@1768; ggml_gemm_q4_K_8x4_q8_K_generic@1822; ggml_gemm_q4_K_8x8_q8_K_generic@1905; ggml_gemm_q2_K_8x8_q8_K_generic@1986; ggml_gemm_q5_K_8x4_q8_K_generic@2076; ggml_gemm_q5_K_8x8_q8_K_generic@2080; ggml_gemm_q6_K_8x4_q8_K_generic@2084; ggml_gemm_q6_K_8x8_q8_K_generic@2088; ggml_gemm_iq4_nl_4x4_q8_0_generic@2092; ggml_gemm_iq4_nl_8x8_q8_0_generic@2148; ggml_gemm_mxfp4_4x4_q8_0_generic@2192; ggml_gemm_mxfp4_8x8_q8_0_generic@2236; ggml_gemm_q4_0_16x1_q8_0_generic@2388; ggml_gemm_q4_K_16x1_q8_K_generic@2442; ggml_gemm_iq4_nl_16x1_q8_0_generic@2536; ggml_gemm_q8_0_16x1_q8_0_generic@2580; ggml_gemm_q2_K_16x1_q8_K_generic@2627; make_block_q8_0x4@2725; make_block_q4_0x4@2742; make_block_q4_0x8@2787; make_block_q4_0x16@2811; make_block_q4_Kx8@2836; make_block_q4_Kx16@2913; make_block_q2_Kx8@2965; make_block_q5_Kx8@3007; make_block_q6_Kx8@3092; make_block_q2_Kx16@3138; repack_q4_0_to_q4_0_4_bl@3200; repack_q4_K_to_q4_K_8_bl@3231; repack_q4_K_to_q4_K_16_bl@3262; repack_q2_K_to_q2_K_8_bl@3292; repack_q2_K_to_q2_K_16_bl@3323; repack_q4_0_to_q4_0_16_bl@3358; repack_q6_K_to_q6_K_8_bl@3420; repack_q4_0_to_q4_0_8_bl@3449; make_block_q8_0x16@3512; make_block_iq4_nlx4@3566; repack_iq4_nl_to_iq4_nl_4_bl@3601; make_block_iq4_nlx8@3634; repack_iq4_nl_to_iq4_nl_8_bl@3658; make_block_iq4_nlx16@3691; repack_iq4_nl_to_iq4_nl_16_bl@3715; make_block_mxfp4x4@3748; repack_mxfp4_to_mxfp4_4_bl@3772; make_block_mxfp4x8@3805; repack_mxfp4_to_mxfp4_8_bl@3829; ggml@3862; tensor_traits_base@4153; forward_mul_mat@4253; forward_mul_mat_id@4386; mmid_row_mapping@4423; mmid_row_mapping@4438; mmid_row_mapping@4499; ggml_status@4726; ggml_backend_cpu_repack_buffer_type_alloc_buffer@4751; ggml_backend_cpu_repack_buffer_type_get_alignment@4766; ggml@4772; extra_buffer_type@4773; ggml_backend_cpu_repack_buffer_type@4821; ggml_backend_buffer_type@4822
Dependencies: ggml-common.h@3; ggml-backend-impl.h@4; ggml-impl.h@6; ggml-cpu.h@7; ggml-cpu-impl.h@8; simd-mappings.h@9; traits.h@10; arch-fallback.h@12; cmath@14; cstring@15; cassert@16; cstdio@17; repack.h@19

`third_party/llama.cpp/ggml/src/ggml-cpu/repack.h` | `cb21edf6239485805df7a2b552c81a5ba9fc9552` | 19905 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: constexpr@14; constexpr@17; block_q4_Kx8@43; block_q4_Kx16@51; block_q2_Kx8@59; block_q2_Kx16@67; block_q5_Kx8@75; block_q6_Kx8@86; block_q8_Kx4@96; block_iq4_nlx4@104; block_iq4_nlx8@111; block_iq4_nlx16@118; block_mxfp4x4@124; block_mxfp4x8@130
Dependencies: ggml-common.h@4; traits.h@6; ggml.h@7

`third_party/llama.cpp/ggml/src/ggml-cpu/simd-gemm.h` | `4119d04f895a8d91ad0ba60b798adb9fd61568d0` | 7467 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: constexpr@161
Dependencies: simd-mappings.h@5

`third_party/llama.cpp/ggml/src/ggml-cpu/simd-mappings.h` | `62e687201efd65dd72f10023c41dc68145b772dd` | 54075 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: neon_compute_fp16_to_fp32@44; neon_compute_fp32_to_fp16@50; power_compute_fp16_to_fp32@71; power_compute_fp32_to_fp16@84; riscv_compute_fp16_to_fp32@96; riscv_compute_fp32_to_fp16@102; ggml_lookup_fp16_to_fp32@134; __avx_f32cx8_load@636; __avx_f32cx8_store@645; __wasm_f16x4_load@827; __wasm_f16x4_store@838; __sse_f16x4_load@943; __sse_f16x4_store@954; __lasx_f32cx8_load@1041; __lasx_f32cx8_store@1048; __lsx_f16x4_load@1127; __lsx_f16x4_store@1131; __lzs_f16cx4_load@1213; __lzs_f16cx4_store@1225
Dependencies: ggml-cpu-impl.h@3; arm_sve.h@6; arm_neon.h@14; riscv_vector.h@18

`third_party/llama.cpp/ggml/src/ggml-cpu/traits.cpp` | `4f32f10255aa4620484244e98f132a1bb0089d8e` | 1231 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml@6; tensor_traits::~tensor_traits@7; extra_buffer_type::~extra_buffer_type@9; ggml_cpu_extra_compute_forward@12; ggml_cpu_extra_work_size@25
Dependencies: traits.h@1; ggml-backend-impl.h@3; ggml-backend.h@4

`third_party/llama.cpp/ggml/src/ggml-cpu/traits.h` | `f4e0990ddfc95b61c2e38f224aac0fd76475c9c1` | 1157 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml@18; tensor_traits@20; extra_buffer_type@27
Dependencies: ggml-backend-impl.h@2; ggml-cpu-impl.h@3; ggml.h@4; vector@7

`third_party/llama.cpp/ggml/src/ggml-cpu/unary-ops.cpp` | `1d8344436f022cb028418d5d46b56093411083d2` | 11555 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: op_abs@3; op_sgn@7; op_neg@11; op_step@15; op_tanh@19; op_elu@23; op_relu@27; op_sigmoid@31; op_hardsigmoid@35; op_exp@39; op_hardswish@43; op_sqr@47; op_sqrt@51; op_xielu@55; op_sin@64; op_cos@68; op_log@72; op_expm1@76; op_softplus@80; op_floor@84; op_ceil@88; op_round@92; op_trunc@96; vec_unary_op@101; apply_unary_op@111; unary_op@137; unary_op_params@158; vec_unary_op_functor@180; apply_unary_op_functor@191; unary_op_functor@217; ggml_compute_forward_abs@237; ggml_compute_forward_sgn@241; ggml_compute_forward_neg@245; ggml_compute_forward_step@249; ggml_compute_forward_tanh@253; ggml_compute_forward_elu@257; ggml_compute_forward_relu@261; ggml_compute_forward_sigmoid@265; ggml_compute_forward_hardsigmoid@269; ggml_compute_forward_exp@273; ggml_compute_forward_hardswish@277; ggml_compute_forward_sqr@281; ggml_compute_forward_sqrt@285; ggml_compute_forward_sin@289; ggml_compute_forward_cos@293; ggml_compute_forward_log@297; ggml_compute_forward_expm1@301; ggml_compute_forward_softplus@305; ggml_compute_forward_floor@309; ggml_compute_forward_ceil@313; ggml_compute_forward_round@317; ggml_compute_forward_trunc@321; ggml_compute_forward_xielu@325
Dependencies: unary-ops.h@1

`third_party/llama.cpp/ggml/src/ggml-cpu/unary-ops.h` | `bcad5a3af1a9879718c56ef8e4d9438c0797544f` | 2442 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: common.h@3

`third_party/llama.cpp/ggml/src/ggml-cpu/vec.cpp` | `67b6b05cac813acefd8cc78c8f841f220c9fbdb0` | 25309 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_vec_dot_f32@11; ggml_vec_dot_bf16@139; ggml_vec_dot_f16@264; ggml_vec_silu_f32@380; ggml_vec_swiglu_f32@417; ggml_vec_cvar_f32@455; ggml_vec_soft_max_f32@531; ggml_vec_log_soft_max_f32@602
Dependencies: vec.h@1; cassert@3

`third_party/llama.cpp/ggml/src/ggml-cpu/vec.h` | `5de9cb5b7e0969bc10a99e40675ed35b0561637b` | 66060 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: double@15; ggml_sve_sum_f32x2@41; ggml_vec_set_i8@80; ggml_vec_set_i16@81; ggml_vec_set_i32@83; ggml_vec_cpy_i32@84; ggml_vec_set_f16@86; ggml_vec_set_bf16@87; ggml_vec_add_f32@89; ggml_vec_add_f16@104; ggml_vec_add1_f32@109; ggml_vec_acc_f32@110; ggml_vec_acc1_f32@111; ggml_vec_sub_f32@112; ggml_vec_sub_f16@113; ggml_vec_set_f32@118; ggml_vec_cpy_f32@119; ggml_vec_neg_f32@120; ggml_vec_neg_f16@121; ggml_vec_mul_f32@127; ggml_vec_mul_f16@128; ggml_vec_div_f32@133; ggml_vec_div_f16@134; ggml_vec_dot_f16_unroll@142; ggml_vec_mad_f32@319; ggml_vec_mad_f16@439; ggml_vec_mad_f32_unroll@585; ggml_vec_mad1_f32@655; ggml_vec_scale_f32@703; ggml_vec_scale_f16@769; ggml_vec_norm_f32@858; ggml_vec_sqr_f32@859; ggml_vec_sqr_f16@860; ggml_vec_sqrt_f32@866; ggml_vec_sqrt_f16@867; ggml_vec_log_f32@872; ggml_vec_log_f16@873; ggml_vec_sin_f32@878; ggml_vec_sin_f16@879; ggml_vec_cos_f32@884; ggml_vec_cos_f16@885; ggml_vec_abs_f32@890; ggml_vec_abs_f16@891; ggml_vec_sgn_f32@896; ggml_vec_sgn_f16@897; ggml_vec_step_f32@903; ggml_vec_step_f16@904; ggml_vec_tanh_f32@909; ggml_vec_tanh_f16@910; ggml_vec_elu_f32@915; ggml_vec_elu_f16@916; ggml_vec_relu_f32@922; ggml_vec_relu_f16@923; ggml_vec_leaky_relu_f32@929; ggml_vec_leaky_relu_f16@930; ggml_vec_sigmoid_f32@936; ggml_vec_sigmoid_f16@937; ggml_vec_hardswish_f32@943; ggml_vec_hardswish_f16@944; ggml_vec_hardsigmoid_f32@950; ggml_vec_hardsigmoid_f16@951; ggml_vec_exp_f32@956; ggml_vec_exp_f16@957; ggml_gelu_f32@968; ggml_vec_gelu_f16@972; ggml_vec_gelu_erf_f16@979; ggml_vec_gelu_f32@988; ggml_vec_gelu_f32@1003; ggml_vec_gelu_erf_f32@1010; ggml_gelu_quick_f32@1017; ggml_vec_gelu_quick_f16@1021; ggml_vec_gelu_quick_f32@1029; ggml_vec_gelu_quick_f32@1038; ggml_silu_f32@1046; ggml_silu_f16@1049; exp_ps_sve@1062; ggml_v_expf@1097; ggml_v_silu@1118; ggml_v_expf@1133; ggml_v_silu@1157; ggml_v_expf@1172; ggml_v_silu@1200; ggml_v_expf@1215; ggml_v_silu@1255; ggml_v_expf@1278; ggml_v_silu@1309; ggml_v_expf_m2@1324; ggml_v_silu_m2@1363; ggml_vec_silu_f16@1372; ggml_silu_backward_f32@1378; ggml_silu_backward_f16@1383; ggml_vec_silu_backward_f32@1389; ggml_vec_silu_backward_f16@1395; ggml_vec_reglu_f32@1401; ggml_vec_reglu_f16@1407; ggml_vec_geglu_f32@1415; ggml_vec_geglu_f32@1430; ggml_vec_geglu_f16@1437; ggml_vec_swiglu_f16@1447; ggml_vec_geglu_erf_f32@1455; ggml_vec_geglu_erf_f16@1462; ggml_vec_geglu_quick_f32@1471; ggml_vec_geglu_quick_f32@1480; ggml_vec_geglu_quick_f16@1487; ggml_vec_sum_f32@1495; ggml_vec_cumsum_f32@1507; ggml_vec_sum_f32_ggf@1517; ggml_vec_sum_f16_ggf@1525; ggml_vec_sum_bf16_ggf@1533; ggml_vec_max_f32@1541; ggml_vec_norm_inv_f32@1553; ggml_vec_argmax_f32@1558
Dependencies: ggml-impl.h@5; simd-mappings.h@6; ggml.h@7; ggml-cpu.h@8; Accelerate/Accelerate.h@11

`third_party/llama.cpp/ggml/src/ggml-impl.h` | `62b76abbcec9e71c860ba1a99d79b501bad26b93` | 25604 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_up32@60; ggml_up@68; ggml_are_same_layout@75; ggml_op_is_empty@90; ggml_impl_is_view@103; ggml_compute_softplus_f32@107; ggml_set_op_params@147; ggml_get_op_params_i32@153; ggml_get_op_params_f32@158; ggml_set_op_params_i32@163; ggml_set_op_params_f32@168; ggml_map_custom1_op_params@173; ggml_map_custom2_op_params@179; ggml_map_custom3_op_params@185; ggml_custom_op_params@191; uint32_t@199; ggml_bitset_size@205; ggml_bitset_get@209; ggml_bitset_set@213; ggml_bitset_clear@217; ggml_hash_set@226; ggml_tensor@229; ggml_hash_set@232; ggml_hash@254; ggml_hash_find@259; ggml_hash_contains@274; ggml_hash_insert@279; ggml_hash_find_or_insert@300; ggml_cgraph_eval_order@323; ggml_cgraph@329; ggml_tensor@334; ggml_tensor@335; ggml_tensor@336; ggml_tensor@337; ggml_hash_set@340; ggml_cgraph_eval_order@342; ggml_cgraph@352; fp32_from_bits@366; fp32_to_bits@375; ggml_compute_fp16_to_fp32@384; ggml_compute_fp32_to_fp16@407; ggml_e8m0_to_fp32@439; ggml_e8m0_to_fp32_half@477; ggml_ue4m3_to_fp32@502; ggml_fp32_to_ue4m3@517; ggml_compute_bf16_to_fp32@594; ggml_compute_fp32_to_bf16@611; ggml_node_get_use_count@629; ggml_node_has_n_uses@641; ggml_can_fuse_ext@669; ggml_tensor@675; ggml_tensor@686; ggml_can_fuse@699; ggml_can_fuse@754
Dependencies: ggml.h@5; gguf.h@6; assert.h@8; math.h@9; stdlib.h@10; stdbool.h@11; stdint.h@12; string.h@13; arm_sve.h@16; arm_neon.h@24; array@749; initializer_list@750; vector@751

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-common.cpp` | `2eb9820bff91c7e753b7cc72f03a72dd88449199` | 13994 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_mem_range@10; ggml_mem_ranges@19; ggml_mem_ranges_init@25; ggml_mem_ranges_free@34; ggml_mem_ranges_reset@38; ggml_mem_ranges_add@42; ggml_mem_range_from_tensor@48; ggml_mem_range_from_tensor_src@82; ggml_mem_range_from_tensor_dst@86; ggml_mem_ranges_add_src@90; ggml_mem_ranges_add_dst@102; ggml_mem_ranges_add@114; ggml_mem_ranges_check@124; ggml_mem_ranges_check_src@155; ggml_mem_ranges_check_dst@165; ggml_mem_ranges_check@175; node_info@187; op@192; is_empty@200; add_fused@204; ggml_metal_graph_optimize_reorder@209; ggml_graph_optimize@375; ggml_op@380
Dependencies: ggml-metal-common.h@1; ggml-impl.h@3; ggml-backend-impl.h@4; vector@6

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-common.h` | `3acbc6ae174aa043cb5bc0fc1d39c907b15b70af` | 1770 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_tensor@11; ggml_cgraph@12; ggml_mem_range_type@14; struct@28
Dependencies: stdbool.h@5

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-context.h` | `abf4b06ed2ab6093c1e3567319a5464733d933c4` | 1453 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: struct@13; ggml_status@26
Dependencies: ggml-metal-device.h@3

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-context.m` | `32d97cd5d0af187d98c557b57409dcc80b55aa4e` | 25428 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_metal_command_buffer@22; ggml_metal@26; ggml_cgraph@61; ggml_metal_command_buffer@67; ggml_metal_init@84; ggml_metal_free@189; ggml_metal_synchronize@239; ggml_metal_buffer_id@297; ggml_metal_set_tensor_async@307; ggml_metal_buffer_id@317; ggml_metal_get_tensor_async@351; ggml_metal_buffer_id@361; ggml_metal_cpy_tensor_async@395; ggml_metal_buffer_id@397; ggml_metal_buffer_id@398; ggml_status@438; ggml_metal_graph_optimize@617; ggml_metal_event_record@627; ggml_metal_event_wait@643; ggml_metal_get_ev_cpy@659; ggml_metal_set_n_cb@663; ggml_metal_set_abort_callback@724; ggml_metal_supports_family@729; ggml_metal_capture_next_compute@737

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device-m.m` | `d052922932a05b4b48d5b35f199560296793f73e` | 68555 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_metal_cv@40; ggml_metal_cv_init@44; ggml_metal_cv_free@52; ggml_metal_cv_set_int16@57; ggml_metal_cv_set_int32@61; ggml_metal_cv_set_bool@65; ggml_metal_pipeline@73; ggml_metal_pipeline_init@77; ggml_metal_pipeline_free@87; ggml_metal_pipeline_max_theads_per_threadgroup@93; ggml_metal_library@97; ggml_metal_library_init@106; ggml_metal_library_init_from_source@262; ggml_metal_library_free@329; ggml_metal_library_get_device@345; ggml_metal_pipeline_with_params@349; ggml_metal_pipeline_with_params@352; ggml_metal_pipeline_with_params@369; ggml_metal_pipeline_with_params@370; ggml_metal_encoder@459; ggml_metal_encoder_init@463; ggml_metal_encoder_free@479; ggml_metal_encoder_debug_group_push@484; ggml_metal_encoder_debug_group_pop@488; ggml_metal_encoder_set_pipeline@492; ggml_metal_encoder_set_bytes@500; ggml_metal_encoder_set_buffer@504; ggml_metal_encoder_set_threadgroup_memory_size@508; ggml_metal_encoder_dispatch_threadgroups@512; ggml_metal_encoder_memory_barrier@516; ggml_metal_encoder_end_encoding@520; ggml_metal_device@524; ggml_metal_device_props@536; ggml_metal_rsets@546; ggml_metal_rsets_init@564; ggml_metal_rsets_free@620; ggml_metal_device_id@639; ggml_metal_device_id@652; ggml_metal_device_init@683; ggml_metal_pipeline_with_params@771; ggml_metal_pipeline_with_params@821; ggml_metal_device_free@924; ggml_metal_device_get_library@953; ggml_metal_device_rsets_add@957; ggml_metal_device_rsets_rm@971; ggml_metal_device_rsets_keep_alive@985; ggml_metal_event@993; ggml_metal_event_encode_signal@999; ggml_metal_event_encode_wait@1007; ggml_metal_device_event_init@1015; ggml_metal_device_event_free@1026; ggml_metal_device_event_synchronize@1035; ggml_metal_device_get_memory@1057; ggml_metal_device_supports_op@1067; ggml_metal_buffer_wrapper@1376; ggml_metal_buffer@1383; ggml_metal_buffer_wrapper@1393; ggml_metal_log_allocated_size@1405; ggml_metal_buffer_rset_init@1431; ggml_metal_buffer_rset_free@1469; ggml_metal_buffer_init@1503; ggml_metal_buffer_map@1573; ggml_metal_buffer_free@1668; ggml_metal_buffer_is_shared@1692; ggml_metal_buffer_memset_tensor@1696; ggml_metal_buffer_id@1704; ggml_metal_buffer_set_tensor@1724; ggml_metal_buffer_id@1741; ggml_metal_buffer_get_tensor@1778; ggml_metal_buffer_id@1786; ggml_metal_buffer_cpy_tensor@1816; ggml_metal_buffer_id@1829; ggml_metal_buffer_id@1830; ggml_metal_buffer_clear@1857; ggml_metal_buffer_id@1881; ggml_metal_buffer_id@1882
Dependencies: Foundation/Foundation.h@6; Metal/Metal.h@8; stdatomic.h@10

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device.cpp` | `0200337463c1d0ab22c7d983dcf03508c88ae49d` | 69474 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_metal_device_deleter@12; operator@13; std@18; ggml_metal_device_get@20; ggml_metal_pipelines@28; ggml_metal_pipelines_init@32; ggml_metal_pipelines_free@38; ggml_metal_pipelines_add@50; ggml_metal_pipelines_get@54; ggml_metal_pipeline_with_params@62; ggml_metal_library_get_pipeline_cpy@84; ggml_metal_library_get_pipeline_pool_1d@99; ggml_metal_library_get_pipeline_pool_2d@124; ggml_metal_library_get_pipeline_get_rows@149; ggml_metal_library_get_pipeline_set_rows@164; ggml_metal_library_get_pipeline_diag@179; ggml_metal_library_get_pipeline_repeat@199; ggml_metal_library_get_pipeline_unary@214; ggml_metal_library_get_pipeline_glu@286; ggml_metal_library_get_pipeline_sum@318; ggml_metal_library_get_pipeline_sum_rows@335; ggml_metal_library_get_pipeline_cumsum_blk@379; ggml_metal_library_get_pipeline_cumsum_add@396; ggml_metal_library_get_pipeline_tri@413; ggml_metal_library_get_pipeline_soft_max@435; ggml_metal_library_get_pipeline_ssm_conv@462; ggml_metal_library_get_pipeline_ssm_conv_batched@489; ggml_metal_library_get_pipeline_ssm_scan@521; ggml_metal_library_get_pipeline_rwkv@547; ggml_metal_library_get_pipeline_gated_delta_net@585; ggml_metal_library_get_pipeline_solve_tri@623; ggml_metal_library_get_pipeline_mul_mv_ext@653; ggml_metal_library_get_pipeline_mul_mm@686; ggml_metal_library_get_pipeline_mul_mv@748; ggml_metal_library_get_pipeline_mul_mm_id_map0@955; ggml_metal_library_get_pipeline_mul_mm_id@972; ggml_metal_library_get_pipeline_mul_mv_id@1000; ggml_metal_library_get_pipeline_argmax@1175; ggml_metal_library_get_pipeline_argsort@1196; ggml_metal_library_get_pipeline_argsort_merge@1222; ggml_metal_library_get_pipeline_top_k@1249; ggml_metal_library_get_pipeline_top_k_merge@1276; ggml_metal_library_get_pipeline_bin@1544; ggml_metal_library_get_pipeline_bin_one@1590; ggml_metal_library_get_pipeline_l2_norm@1623; ggml_metal_library_get_pipeline_group_norm@1648; ggml_metal_library_get_pipeline_norm@1669; ggml_metal_library_get_pipeline_rope@1712; ggml_metal_library_get_pipeline_im2col@1753; ggml_metal_library_get_pipeline_conv_transpose_1d@1784; ggml_metal_library_get_pipeline_conv_transpose_2d@1807; ggml_metal_library_get_pipeline_conv_2d@1830; ggml_metal_library_get_pipeline_conv_3d@1852; ggml_metal_library_get_pipeline_upscale@1874; ggml_metal_library_get_pipeline_roll@1908; ggml_metal_library_get_pipeline_pad@1925; ggml_metal_library_get_pipeline_pad_reflect_1d@1950; ggml_metal_library_get_pipeline_arange@1967; ggml_metal_library_get_pipeline_timestep_embedding@1984; ggml_metal_library_get_pipeline_opt_step_adamw@2001; ggml_metal_library_get_pipeline_opt_step_sgd@2018; ggml_metal_library_get_pipeline_memset@2035; ggml_metal_library_get_pipeline_count_equal@2052
Dependencies: ggml-metal-device.h@1; ggml-metal-impl.h@3; ggml-impl.h@5; cassert@7; memory@8; string@9; unordered_map@10

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-device.h` | `4a3ebb5569d9f98fd0f9ca66ac038ebf1a720626` | 17160 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_metal_buffer_id@9; struct@14; struct@20; struct@33; struct@39; ggml_metal_pipeline_with_params@47; void@67; struct@73; struct@98; ggml_metal_pipeline_with_params@107; ggml_metal_pipeline_with_params@108; ggml_metal_pipeline_with_params@110; ggml_metal_pipeline_with_params@111; ggml_metal_pipeline_with_params@112; ggml_metal_pipeline_with_params@113; ggml_metal_pipeline_with_params@114; ggml_metal_pipeline_with_params@115; ggml_metal_pipeline_with_params@116; ggml_metal_pipeline_with_params@117; ggml_metal_pipeline_with_params@118; ggml_metal_pipeline_with_params@119; ggml_metal_pipeline_with_params@120; ggml_metal_pipeline_with_params@121; ggml_metal_pipeline_with_params@122; ggml_metal_pipeline_with_params@123; ggml_metal_pipeline_with_params@124; ggml_metal_pipeline_with_params@125; ggml_metal_pipeline_with_params@126; ggml_metal_pipeline_with_params@127; ggml_metal_pipeline_with_params@128; ggml_metal_pipeline_with_params@129; ggml_metal_pipeline_with_params@130; ggml_metal_pipeline_with_params@131; ggml_metal_pipeline_with_params@132; ggml_metal_pipeline_with_params@133; ggml_metal_pipeline_with_params@134; ggml_metal_pipeline_with_params@135; ggml_metal_pipeline_with_params@136; ggml_metal_pipeline_with_params@137; ggml_metal_pipeline_with_params@138; ggml_metal_pipeline_with_params@139; ggml_metal_pipeline_with_params@140; ggml_metal_pipeline_with_params@141; ggml_metal_pipeline_with_params@142; ggml_metal_pipeline_with_params@143; ggml_metal_pipeline_with_params@144; ggml_metal_pipeline_with_params@145; ggml_metal_pipeline_with_params@146; ggml_metal_pipeline_with_params@147; ggml_metal_pipeline_with_params@148; ggml_metal_pipeline_with_params@149; ggml_metal_pipeline_with_params@150; ggml_metal_pipeline_with_params@151; ggml_metal_pipeline_with_params@152; ggml_metal_pipeline_with_params@153; ggml_metal_pipeline_with_params@154; ggml_metal_pipeline_with_params@155; ggml_metal_pipeline_with_params@156; ggml_metal_pipeline_with_params@157; ggml_metal_pipeline_with_params@158; ggml_metal_pipeline_with_params@159; ggml_metal_pipeline_with_params@160; ggml_metal_pipeline_with_params@161; ggml_metal_pipeline_with_params@162; ggml_metal_pipeline_with_params@163; ggml_metal_pipeline_with_params@165; ggml_metal_pipeline_with_params@171; ggml_metal_pipeline_with_params@177; ggml_metal_pipeline_with_params@187; ggml_metal_pipeline_with_params@198; void@206; struct@209; ggml_metal_device_id@218; ggml_metal_device_props@242; ggml_metal_device_id@261; struct@266; struct@299; ggml_metal_buffer_id@318
Dependencies: ggml.h@3

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-impl.h` | `ff74cafb5b7972e1974928274207d1fc712f9052` | 22646 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: struct@155; struct@183; struct@208; struct@237; struct@246; struct@265; struct@285; struct@300; struct@333; struct@351; struct@362; struct@397; struct@432; struct@436; struct@453; struct@475; struct@496; struct@507; struct@526; struct@551; struct@566; struct@586; struct@597; struct@606; struct@619; struct@649; struct@667; struct@703; struct@716; struct@720; struct@739; struct@759; struct@778; struct@801; struct@820; struct@854; struct@892; struct@919; struct@934; struct@950; struct@969; struct@993; struct@1012; struct@1033; struct@1056; struct@1062; struct@1081; struct@1097; struct@1114; struct@1120; struct@1124; struct@1139; struct@1153; struct@1162; struct@1167; struct@1171

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-ops.cpp` | `e2ce56e9e28b6b17cb8a9f7b0508388e275dedbd` | 158744 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_metal_get_buffer_id@16; ggml_metal_op@28; n_nodes@71; can_fuse@80; ggml_metal_op_free@139; ggml_metal_op_n_nodes@143; ggml_metal_op_concurrency_reset@147; ggml_metal_op_concurrency_check@159; ggml_metal_op_concurrency_add@167; ggml_metal_op_encode_impl@175; ggml_tensor@176; ggml_metal_op_encode@498; ggml_metal_op_concat@516; ggml_metal_op_repeat@585; ggml_metal_op_acc@629; ggml_metal_op_unary@746; ggml_metal_op_glu@839; ggml_metal_op_sum@897; ggml_metal_op_sum_rows@934; ggml_metal_op_cumsum@999; ggml_metal_op_get_rows@1142; ggml_metal_op_set_rows@1187; ggml_metal_op_diag@1249; ggml_metal_op_soft_max@1291; ggml_metal_op_ssm_conv@1381; ggml_metal_op_ssm_scan@1454; ggml_metal_op_rwkv@1552; ggml_metal_op_gated_delta_net@1593; ggml_metal_op_solve_tri@1668; ggml_metal_op_set@1725; ggml_metal_op_cpy@1853; ggml_metal_op_pool_1d@1926; ggml_metal_op_pool_2d@1974; ggml_metal_op_mul_mat@2034; ggml_metal_op_mul_mat_id_extra_tpe@2265; ggml_metal_op_mul_mat_id_extra_ids@2273; ggml_metal_op_mul_mat_id@2282; ggml_metal_op_add_id@2470; ggml_metal_op_flash_attn_ext_use_vec@2516; ggml_metal_op_flash_attn_ext_extra_pad@2526; ggml_metal_op_flash_attn_ext_extra_blk@2572; ggml_metal_op_flash_attn_ext_extra_tmp@2611; ggml_metal_op_flash_attn_ext@2640; ggml_metal_op_bin@3070; ggml_metal_pipeline_with_params@3184; ggml_metal_op_l2_norm@3229; ggml_metal_op_group_norm@3297; ggml_metal_op_norm@3348; ggml_metal_op_rope@3486; ggml_metal_op_im2col@3582; ggml_metal_op_conv_2d@3662; ggml_metal_op_conv_3d@3740; ggml_metal_op_conv_transpose_1d@3811; ggml_metal_op_conv_transpose_2d@3856; ggml_metal_op_upscale@3912; ggml_metal_op_roll@3976; ggml_metal_op_pad@4029; ggml_metal_op_pad_reflect_1d@4080; ggml_metal_op_arange@4126; ggml_metal_op_timestep_embedding@4160; ggml_metal_op_argmax@4194; ggml_metal_op_argsort@4233; ggml_metal_op_top_k@4340; ggml_metal_op_tri@4452; ggml_metal_op_opt_step_adamw@4503; ggml_metal_op_opt_step_sgd@4539; ggml_metal_op_count_equal@4573
Dependencies: ggml-metal-ops.h@1; ggml.h@3; ggml-impl.h@4; ggml-backend-impl.h@5; ggml-metal-impl.h@7; ggml-metal-common.h@8; ggml-metal-device.h@9; cassert@11; algorithm@12; limits@13; cmath@14

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal-ops.h` | `36c61071b4faf7db79401c32ca3968e21b5a703a` | 4505 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: struct@9; ggml_cgraph@14
Dependencies: ggml-metal-device.h@3

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal.cpp` | `0274c5c26ef2b99abeba78fc4363d2738f123066` | 34584 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_backend_metal_disable@21; ggml_backend_metal_buffer_shared_free_buffer@34; ggml_backend_metal_buffer_shared_memset_tensor@50; ggml_backend_metal_buffer_shared_set_tensor@58; ggml_backend_metal_buffer_shared_get_tensor@66; ggml_backend_metal_buffer_shared_cpy_tensor@74; ggml_backend_metal_buffer_shared_clear@86; ggml_backend_metal_buffer_private_free_buffer@110; ggml_backend_metal_buffer_private_memset_tensor@126; ggml_backend_metal_buffer_private_set_tensor@134; ggml_backend_metal_buffer_private_get_tensor@142; ggml_backend_metal_buffer_private_cpy_tensor@150; ggml_backend_metal_buffer_private_clear@162; ggml_backend_buffer_is_metal@184; ggml_backend_metal_buffer_type@193; ggml_backend_metal_buffer_type_deleter@198; operator@199; std@204; ggml_backend_metal_buffer_type_alloc_buffer@207; ggml_backend_metal_buffer_type_get_alloc_size@218; ggml_backend_metal_buffer_type_shared_alloc_buffer@260; ggml_backend_metal_buffer_type_shared_get_alignment@264; ggml_backend_metal_buffer_type_shared_get_max_size@270; ggml_backend_metal_buffer_type_shared_get_alloc_size@276; ggml_backend_metal_buffer_type_shared_is_host@280; ggml_backend_metal_buffer_type_shared@286; ggml_backend_metal_buffer_type_private_alloc_buffer@336; ggml_backend_metal_buffer_type_private_get_alignment@340; ggml_backend_metal_buffer_type_private_get_max_size@346; ggml_backend_metal_buffer_type_private_get_alloc_size@352; ggml_backend_metal_buffer_type_private_is_host@356; ggml_backend_metal_buffer_type_private@362; ggml_backend_metal_buffer_type_mapped_alloc_buffer@411; ggml_backend_metal_buffer_type_mapped_get_alignment@416; ggml_backend_metal_buffer_type_mapped_get_max_size@422; ggml_backend_metal_buffer_type_mapped_get_alloc_size@428; ggml_backend_metal_buffer_type_mapped_is_host@432; ggml_backend_metal_buffer_type_mapped@438; ggml_backend_metal_free@489; ggml_backend_metal_synchronize@500; ggml_backend_metal_set_tensor_async@506; ggml_backend_metal_get_tensor_async@512; ggml_backend_metal_cpy_tensor_async@518; ggml_status@539; ggml_backend_metal_event_record@545; ggml_backend_metal_event_wait@552; ggml_backend_metal_graph_optimize@559; ggml_backend_metal_set_n_cb@565; ggml_backend_metal_guid@592; ggml_backend_metal_init@597; ggml_backend_is_metal@621; ggml_backend_metal_set_abort_callback@625; ggml_backend_metal_supports_family@633; ggml_backend_metal_capture_next_compute@641; ggml_backend_metal_device_get_memory@665; ggml_backend_dev_type@671; ggml_backend_metal_device_get_props@677; ggml_backend_metal_device_init_backend@692; ggml_backend_metal_device_get_buffer_type@717; ggml_backend_metal_device_buffer_mapped@725; ggml_backend_metal_device_supports_op@735; ggml_backend_metal_device_supports_buft@741; get_op_batch_size@751; ggml_backend_metal_device_offload_op@762; ggml_backend_metal_device_event_new@770; ggml_backend_metal_device_event_free@784; ggml_backend_metal_device_event_synchronize@794; ggml_backend_metal_reg@822; struct@826; ggml_backend_metal_reg_init@828; ggml_backend_metal_reg_free@834; ggml_backend_metal_reg_deleter@838; operator@839; std@844; ggml_backend_metal_reg_device_count@852; ggml_backend_metal_reg_device_get@857; ggml_backend_metal_device_init@893; ggml_backend_metal_device_free@901; ggml_backend_device_deleter@905; operator@906; std@911; ggml_backend_metal_reg@913
Dependencies: ggml-metal.h@1; ggml-impl.h@3; ggml-backend-impl.h@4; ggml-metal-device.h@6; ggml-metal-context.h@7; ggml-metal-ops.h@8; memory@10; mutex@11; string@12

`third_party/llama.cpp/ggml/src/ggml-metal/ggml-metal.metal` | `072f14e68f00f96b288f49d6d7f681feafb6e5da` | 452292 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/ggml/src/ggml-opt.cpp` | `53903defa8f419069f3046b960f2f057e06e6263` | 42081 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_opt_dataset@16; ggml_context@17; ggml_tensor@19; ggml_tensor@20; ggml_opt_context@30; ggml_context@34; ggml_context@35; ggml_context@36; ggml_context@37; ggml_opt_loss_type@41; ggml_opt_build_type@42; ggml_opt_build_type@43; ggml_tensor@45; ggml_tensor@46; ggml_tensor@47; ggml_tensor@49; ggml_tensor@50; ggml_tensor@51; ggml_cgraph@53; ggml_cgraph@54; ggml_cgraph@55; ggml_tensor@69; ggml_opt_optimizer_type@71; ggml_opt_result@74; ggml_type@87; ggml_type@88; ggml_init_params@103; ggml_opt_dataset_free@132; ggml_opt_dataset_ndata@138; ggml_tensor@142; ggml_tensor@146; ggml_opt_dataset_shuffle@150; ggml_opt_dataset_get_batch@163; ggml_opt_dataset_get_batch_host@196; ggml_opt_optimizer_params@223; ggml_opt_optimizer_params@241; ggml_opt_params@245; ggml_opt_loss_type@247; ggml_opt_build@322; ggml_init_params@358; ggml_init_params@372; ggml_context@384; ggml_tensor@512; ggml_tensor@513; ggml_tensor@516; ggml_tensor@517; ggml_tensor@524; ggml_opt_init@549; ggml_opt_free@584; ggml_opt_reset@596; ggml_opt_static_graphs@605; ggml_tensor@609; ggml_tensor@613; ggml_tensor@617; ggml_tensor@621; ggml_tensor@625; ggml_tensor@629; ggml_tensor@633; ggml_opt_result_init@639; ggml_opt_result_free@643; ggml_opt_result_reset@647; ggml_opt_result_ndata@654; ggml_opt_result_loss@658; ggml_opt_result_pred@693; ggml_opt_result_accuracy@699; ggml_context@714; ggml_cgraph@715; ggml_tensor@716; ggml_tensor@717; ggml_opt_alloc@725; ggml_cgraph@741; ggml_opt_eval@782; ggml_tensor@890; ggml_tensor@891; ggml_tensor@892; ggml_opt_loss_type@1005; ggml_opt_optimizer_type@1006; ggml_opt_optimizer_type@1081
Dependencies: ggml-opt.h@1; ggml.h@3; ggml-alloc.h@4; ggml-backend.h@5; ggml-impl.h@6; algorithm@8; cmath@9; cstdint@10; cinttypes@11; map@12; random@13; vector@14

`third_party/llama.cpp/ggml/src/ggml-quants.c` | `15d231f70c0d080460d2cc973bb356595886d141` | 225748 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: best_index_int8@28; quantize_row_q1_0_ref@40; quantize_row_q4_0_ref@75; quantize_row_q4_1_ref@112; quantize_row_q5_0_ref@149; quantize_row_q5_1_ref@193; quantize_row_q8_0_ref@238; quantize_row_q8_1_ref@264; best_index_mxfp4@299; quantize_row_mxfp4_ref@312; quantize_row_nvfp4_ref@346; dequantize_row_q1_0@381; dequantize_row_q4_0@401; dequantize_row_q4_1@421; dequantize_row_q5_0@442; dequantize_row_q5_1@468; dequantize_row_q8_0@495; dequantize_row_mxfp4@511; dequantize_row_nvfp4@531; nearest_int@563; make_q3_quants@639; get_scale_min_k4@822; quantize_row_q2_K_ref@833; dequantize_row_q2_K@903; make_qp_quants@1018; quantize_row_q2_K_impl@1091; quantize_q2_K@1153; quantize_row_q3_K_ref@1171; dequantize_row_q3_K@1247; quantize_row_q3_K_impl@1297; quantize_q3_K@1381; quantize_row_q4_K_ref@1399; dequantize_row_q4_K@1471; quantize_row_q4_K_impl@1495; quantize_q4_K@1568; quantize_row_q5_K_ref@1586; dequantize_row_q5_K@1673; quantize_row_q5_K_impl@1700; quantize_q5_K@1793; quantize_row_q6_K_ref@1811; dequantize_row_q6_K@1881; quantize_row_q6_K_impl@1912; quantize_q6_K@1996; quantize_row_q4_0_impl@2012; quantize_q1_0@2040; quantize_q4_0@2056; quantize_row_q4_1_impl@2071; quantize_q4_1@2101; quantize_row_q5_0_impl@2116; quantize_q5_0@2155; quantize_row_q5_1_impl@2170; quantize_q5_1@2208; quantize_q8_0@2223; quantize_mxfp4@2230; quantize_nvfp4@2236; quantize_row_tq1_0_ref@2244; quantize_row_tq2_0_ref@2310; quantize_tq1_0@2342; quantize_tq2_0@2349; dequantize_row_tq1_0@2356; dequantize_row_tq2_0@2395; dequantize_row_iq2_xxs@2416; dequantize_row_iq2_xs@2444; dequantize_row_iq2_s@2471; dequantize_row_iq3_xxs@2503; dequantize_row_iq3_s@2535; dequantize_row_iq1_s@2578; dequantize_row_iq1_m@2603; dequantize_row_iq4_nl@2653; dequantize_row_iq4_xs@2671; quantize_row_q8_K_ref@2696; dequantize_row_q8_K@2735; struct@2748; iq2_data_index@2761; iq2_grid_size@2768; iq2_compare_func@2775; iq2xs_init_impl@2781; iq2xs_free_impl@3188; quantize_row_iq2_xxs_impl@3222; quantize_row_iq2_xs_impl@3400; quantize_iq2_xxs@3580; quantize_iq2_xs@3592; struct@3608; iq3_data_index@3619; iq3_compare_func@3625; iq3xs_init_impl@3631; iq3xs_free_impl@3832; quantize_iq3_xxs@4080; quantize_row_iq3_xxs_ref@4092; quantize_iq3_s@4281; quantize_row_iq3_s_ref@4303; iq1_sort_helper@4428; quantize_iq1_s@4600; quantize_iq1_m@4874; quantize_iq4_nl@5005; quantize_row_iq4_nl_ref@5028; quantize_iq4_xs@5043; quantize_row_iq4_xs_ref@5063; quantize_row_iq2_s_impl@5070; quantize_iq2_s@5239; quantize_row_iq2_s_ref@5251; validate_float@5258; isinf_fp16@5272; isnan_fp16@5276; validate_fp16@5280; validate_e_e8m0@5294; ggml_validate_row_data@5337
Dependencies: ggml-common.h@2; ggml-quants.h@4; ggml-impl.h@5; ggml-cpu/ggml-cpu-impl.h@6; ggml-cpu.h@7; math.h@9; string.h@10; assert.h@11; float.h@12; stdlib.h@13; stdio.h@14; omp.h@17

`third_party/llama.cpp/ggml/src/ggml-quants.h` | `d56c86da8909543c9132d1eb39e94e2737a90cf2` | 9440 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: ggml-common.h@4; ggml.h@6

`third_party/llama.cpp/ggml/src/ggml-threading.cpp` | `25a19eedb90535daccd640056175dbbbc58c1ca7` | 250 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_critical_section_start@6; ggml_critical_section_end@10
Dependencies: ggml-threading.h@1; mutex@2

`third_party/llama.cpp/ggml/src/ggml-threading.h` | `dec2c8840aa3669c2f813ba940d192f803e1da5e` | 198 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: ggml.h@3

`third_party/llama.cpp/ggml/src/ggml.cpp` | `8354bb0cc8e85bd8c81be62f2f9184e90423e940` | 751 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: ggml-impl.h@1; cstdlib@3; exception@4

`third_party/llama.cpp/ggml/src/gguf.cpp` | `ffbfccec4a60eafd36ac4023f5a94c89cc0363d0` | 57639 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: type_to_gguf_type@33; type_to_gguf_type@36; type_to_gguf_type@41; type_to_gguf_type@46; type_to_gguf_type@51; type_to_gguf_type@56; type_to_gguf_type@61; type_to_gguf_type@66; type_to_gguf_type@71; type_to_gguf_type@76; type_to_gguf_type@81; type_to_gguf_type@86; type_to_gguf_type@91; gguf_type_size@135; gguf_kv@141; gguf_type@145; key@152; key@160; key@170; key@176; get_ne@189; constexpr@205; cast@215; gguf_tensor_info@222; ggml_tensor@223; gguf_context@227; gguf_reader@240; nbytes_remain@251; file_remain@256; read@277; read@286; constexpr@290; constexpr@308; read@323; read@332; read@341; read@350; read@367; tell@374; seek@378; read_raw@391; gguf_context@431; gguf_read_emplace_helper@436; gguf_context@461; gguf_context@462; gguf_tensor_info@631; ggml_init_params@830; ggml_context@843; ggml_tensor@845; ggml_tensor@876; gguf_context@906; gguf_file_reader@915; gguf_file_reader_callback@920; gguf_context@938; gguf_buffer_reader@956; gguf_buffer_reader_callback@961; gguf_context@976; gguf_context@989; gguf_context@997; gguf_free@1002; gguf_get_version@1015; gguf_get_alignment@1019; gguf_get_data_offset@1023; gguf_get_n_kv@1027; gguf_find_key@1031; gguf_type@1052; gguf_type@1057; gguf_get_arr_n@1075; gguf_get_val_u8@1087; gguf_get_val_i8@1093; gguf_get_val_u16@1099; gguf_get_val_i16@1105; gguf_get_val_u32@1111; gguf_get_val_i32@1117; gguf_get_val_f32@1123; gguf_get_val_u64@1129; gguf_get_val_i64@1135; gguf_get_val_f64@1141; gguf_get_val_bool@1147; gguf_get_n_tensors@1166; gguf_find_tensor@1170; gguf_get_tensor_offset@1186; ggml_type@1196; gguf_get_tensor_size@1201; gguf_remove_key@1206; gguf_check_reserved_keys@1215; constexpr@1217; gguf_set_val_u8@1226; gguf_set_val_i8@1232; gguf_set_val_u16@1238; gguf_set_val_i16@1244; gguf_set_val_u32@1250; gguf_set_val_i32@1256; gguf_set_val_f32@1262; gguf_set_val_u64@1268; gguf_set_val_i64@1274; gguf_set_val_f64@1280; gguf_set_val_bool@1286; gguf_set_val_str@1292; gguf_set_arr_data@1298; gguf_set_arr_str@1311; gguf_set_kv@1323; gguf_context@1378; gguf_tensor_info@1385; gguf_set_tensor_type@1392; ggml_tensor@1397; gguf_set_tensor_data@1417; gguf_writer_base@1426; write@1437; write@1443; write@1448; write@1458; write@1462; write@1466; write@1470; write_tensor_meta@1511; pad@1524; gguf_writer_buf@1533; gguf_writer_buf@1536; gguf_writer_file@1571; gguf_writer_file@1574; gguf_write_out@1615; gguf_write_to_buf@1653; gguf_write_to_file_ptr@1658; gguf_write_to_file@1671; gguf_get_meta_size@1688; gguf_get_meta_data@1695
Dependencies: ggml.h@1; ggml-backend.h@2; ggml-impl.h@3; gguf.h@4; cinttypes@6; cstddef@7; cstdint@8; cstdio@9; cstdlib@10; cstring@11; map@12; new@13; stdexcept@14; string@15; vector@16; cerrno@17; moz-overrides.h@19

`third_party/llama.cpp/include-order.patch` | `565a7391d235fa9bf19fbda3fe6724cc3d72399b` | 6061 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/include/llama.h` | `d7263e125013f4e7ac043cce89facb5c1f985452` | 82182 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_vocab@61; llama_model@62; llama_context@63; llama_sampler@64; struct@66; int32_t@68; int32_t@69; int32_t@70; llama_vocab_type@72; llama_rope_type@82; llama_token_type@91; llama_token_attr@101; llama_ftype@116; llama_rope_scaling_type@162; llama_pooling_type@171; llama_attention_type@180; llama_flash_attn_type@186; llama_split_mode@194; llama_context_type@201; struct@207; struct@213; bool@222; struct@240; llama_model_kv_override_type@251; llama_model_meta_key@258; llama_model_kv_override@273; llama_model_kv_override_type@274; llama_model_tensor_buft_override@286; llama_model_params@291; llama_split_mode@299; llama_sampler_seq_config@329; llama_sampler@331; llama_context_params@336; llama_context_type@346; llama_rope_scaling_type@347; llama_pooling_type@348; llama_attention_type@349; llama_flash_attn_type@350; ggml_type@365; ggml_type@366; llama_sampler_seq_config@389; llama_context@394; llama_model_tensor_override@397; ggml_type@399; llama_model_imatrix_data@402; struct@409; llama_ftype@411; ggml_type@412; ggml_type@413; struct@426; struct@431; struct@436; llama_adapter_lora@442; llama_context@464; void@470; gguf_context@476; llama_model_params@479; llama_model_params@483; llama_model_params@491; llama_model_params@496; llama_model_params@502; llama_model_params@508; llama_model_params@515; llama_model@527; llama_context_params@528; llama_model@531; llama_context_params@532; llama_model@662; llama_context@695; llama_adapter_lora@696; llama_context@707; llama_context@803; llama_context@807; llama_context@814; llama_context@818; llama_context@824; llama_context@830; llama_context@838; llama_context@843; llama_context@851; llama_context@856; llama_context@866; llama_context@872; llama_context@879; uint32_t@898; llama_context@901; llama_context@906; llama_context@913; llama_context@955; llama_batch@956; llama_context@971; llama_batch@972; void@1243; llama_sampler_data@1245; ggml_tensor@1246; ggml_tensor@1247; ggml_tensor@1248; ggml_tensor@1249; llama_sampler_i@1253; llama_sampler@1258; llama_sampler@1270; ggml_context@1271; ggml_cgraph@1272; ggml_tensor@1273; llama_sampler@1277; ggml_context@1278; ggml_cgraph@1279; llama_sampler_data@1280; llama_sampler@1286; llama_sampler_i@1287; llama_perf_context_data@1536; llama_perf_sampler_data@1548; bool@1568; llama_opt_params@1573; ggml_opt_optimizer_type@1582; llama_context@1588
Dependencies: ggml.h@4; ggml-cpu.h@5; ggml-backend.h@6; ggml-opt.h@7; gguf.h@8; stddef.h@10; stdint.h@11; stdio.h@12; stdbool.h@13

`third_party/llama.cpp/load-from-buffer-or-fd.patch` | `1a8390f58b0b071c926fe1c59963a49329838fe2` | 12886 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/metal-disable.patch` | `78046590609da19610aac2ec7369271eb141c3cf` | 744 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/metal-event-availability.patch` | `5a6ac12b5abe333552574b73d1688f027ede0ff1` | 1474 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/metal-mul-mv-short-fallback.patch` | `0ad435998ec4cf12d42c1002a4f5819baa1da61c` | 3904 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/missing-includes.patch` | `23e74e492cc7c4af0c87c61a86eb722e122d18d1` | 875 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/moz-overrides.h` | `1c3d6ea809596d09420fbdd347dc34ce53babc36` | 1201 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: cstdlib@6

`third_party/llama.cpp/moz.build` | `719333c0b9b6e937d8df89a7ef972d2b2d8d0639` | 4544 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/llama.cpp/moz.yaml` | `75712df25b7a5d343b05e5c4faeff47ea3bebec1` | 3504 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/no-future.patch` | `bfd3958425468ad80ab9ee86ab190304becc4cdb` | 2676 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/no-wstring.patch` | `8867c2ca374cbf1454808bdd541eb1a15ed7c203` | 2263 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/profiler-hooks.patch` | `d193e0057cb8c4cad3694e0094c6eac7f2f75805` | 3079 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/random_device.patch` | `aaeb0fb4a0d9037a2e66c5c74a087b478b399d84` | 697 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/requirements.txt` | `2b28a3f33f4131b181155528e7fcf32f0b710a38` | 19 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/run_parser.py` | `807e92bee41eb8dd99dc7b45db623e84a3db41bf` | 6146 bytes | imported-path,source | UTF-8 | mode 100755
Declarations: deduplicate_into@18

`third_party/llama.cpp/skip-metadata-dump.patch` | `26f4e375d9d768ac60f5cd2f7643af98f2f745e2` | 1082 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/sources.mozbuild` | `06440628974e42542efc5771d8d5d50fa5e8acf6` | 6850 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/llama.cpp/src/CMakeLists.txt` | `d15ccfd99f143ef1365259f2ad013a6f9c2ff585` | 1673 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/llama.cpp/src/llama-adapter.cpp` | `95f50e05ccd8e54276cc3c1d2aa98b8f225b2e22` | 18234 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_adapter_cvec::init@33; llama_adapter_lora_init_impl@151; llama_adapter_meta_val_str@437; llama_adapter_meta_count@448; llama_adapter_meta_key_by_index@452; llama_adapter_meta_val_str_by_index@464; llama_adapter_lora_free@476; llama_adapter_get_alora_n_invocation_tokens@489
Dependencies: llama-adapter.h@1; llama-impl.h@3; llama-mmap.h@4; llama-model.h@5; map@7; cassert@8; sstream@9; stdexcept@10; moz-overrides.h@12

`third_party/llama.cpp/src/llama-adapter.h` | `f0b1e50f81695e9b1ef11bbd2db277fc1a921add` | 2240 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_adapter_cvec@17; llama_adapter_lora_weight@48; get_scale@53; llama_adapter_lora_weight@60; llama_adapter_lora@63; llama_adapter_lora@80; get_n_nodes@85
Dependencies: llama.h@3; ggml-cpp.h@5; string@7; unordered_map@8; vector@9

`third_party/llama.cpp/src/llama-arch.cpp` | `b09fe1e25058c7e137a36b1087b886f03d64b2ac` | 66657 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: LLM_KV::LLM_KV@815; LLM_KV::operator@817; arch@829; LLM_TN_IMPL::str@831; llm_arch_all@846; llm_arch_from_string@865; llm_arch_is_recurrent@879; llm_arch_is_hybrid@893; llm_arch_is_diffusion@913; llm_arch_supports_rs_rollback@925; llm_arch_supports_sm_tensor@935
Dependencies: llama-arch.h@1; llama-impl.h@3; map@5; vector@6

`third_party/llama.cpp/src/llama-arch.h` | `989da06d8d5145f54503d4fb76ad8be8ea5b260c` | 19021 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_arch@13; llm_kv@149; llm_tensor@365; llm_tensor_layer@583; LLM_KV@589; LLM_TN_IMPL@607; std::string@618; LLM_TN@631; LLM_TN@632; operator@636; operator@640; llm_tensor_info@646
Dependencies: ggml.h@3; string@5; set@6; vector@7

`third_party/llama.cpp/src/llama-batch.cpp` | `6bf76939cddcbb7c06232ad7e88bf47e5bd57bc0` | 28955 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_batch_allocr::llama_batch_allocr@12; llama_batch_allocr::ubatch_reserve@391; llama_batch_allocr::get_n_tokens@441; llama_batch_allocr::get_n_outputs@445; llama_batch_allocr::get_n_used@449; llama_batch_allocr::seq_pos_min@457; llama_batch_allocr::seq_pos_max@461; llama_batch_allocr::split_reset@465; llama_batch_allocr::split_simple@474; llama_batch_allocr::split_equal@508; llama_batch_allocr::split_seq@613; llama_batch_allocr::clear@655; llama_batch_allocr::ubatch_add@681; llama_batch_allocr::ubatch_print@778; llama_batch@863; llama_batch@877; llama_batch_free@907
Dependencies: llama-batch.h@1; llama-impl.h@3; llama-vocab.h@4; llama-memory.h@5; cassert@7; cstring@8; algorithm@9; sstream@10

`third_party/llama.cpp/src/llama-batch.h` | `f77520e86c3ca45ffb5541597790005b76d5d4cd` | 6470 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_ubatch@15; equal_seqs@16; is_pos_2d@25; data_t@54; llama_batch_allocr@72
Dependencies: llama.h@3; llama-cparams.h@5; array@7; vector@8; set@9; bitset@10; memory@11; unordered_map@12

`third_party/llama.cpp/src/llama-chat.cpp` | `6c16838fda83af09a89586a70103ad2fb357eacd` | 42324 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: trim@18; llm_chat_template_from_str@90; llm_chat_detect_template@94; llama_chat_builtin_templates@962
Dependencies: llama-chat.h@1; llama.h@3; map@5; sstream@6; algorithm@7; moz-overrides.h@9

`third_party/llama.cpp/src/llama-chat.h` | `dc37f919a9680b0887b3aaedef528a6f24ad7237` | 2275 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_chat_template@7; llama_chat_message@66
Dependencies: string@3; vector@4; cstdint@5

`third_party/llama.cpp/src/llama-context.cpp` | `2de0c7ad45f4277270fd87e7fe15b95616ac28b1` | 146387 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ctx_type_to_graph_type@27; balloc@41; llama_context::~llama_context@421; llama_context::sched_reserve@441; llama_context::synchronize@686; llama_context::get_sched@728; llama_context::n_ctx@732; llama_context::n_ctx_seq@736; llama_context::n_batch@740; llama_context::n_ubatch@744; llama_context::n_seq_max@748; llama_context::n_threads@752; llama_context::n_threads_batch@756; llama_context::get_memory@760; llama_context::memory_update@764; llama_pooling_type@820; llama_context::output_resolve_row@830; llama_context::get_sampled_token_ith@963; llama_context::get_sampled_candidates_count@1036; llama_context::get_sampled_logits_count@1055; llama_context::get_sampled_probs_count@1074; llama_context::detach_threadpool@1103; llama_context::set_n_threads@1110; llama_context::set_abort_callback@1117; llama_context::set_embeddings@1134; llama_context::set_embeddings_nextn@1143; llama_context::set_embeddings_layer_inp@1150; llama_context::set_causal_attn@1161; llama_context::set_warmup@1173; llama_context::set_sampler@1186; llama_context::set_adapters_lora@1243; llama_context::adapters_lora_are_same@1261; llama_context::encode@1374; needs_raw_logits@1661; llama_context::decode@1678; llama_context::output_reserve@2060; llama_context::extract_layer_inputs@2222; llama_context::output_reorder@2250; llama_context::graph_max_nodes@2321; llama_context::graph_get_cb@2448; llama_io_write_dummy@2478; llama_io_write_dummy@2480; llama_io_write_host@2504; write_info@2548; llama_io_read_host@2557; llama_io_read_host@2559; read_info@2600; llama_io_write_file@2609; llama_io_write_file@2611; llama_io_read_file@2634; llama_io_read_file@2636; llama_io_write_device@2659; llama_io_write_device@2661; write_info@2780; llama_io_read_device@2791; llama_io_read_device@2793; read_info@2869; llama_context::state_get_size@2880; llama_context::state_get_data@2890; llama_context::state_set_data@2900; llama_context::state_seq_get_size@2912; llama_context::state_seq_get_data@2925; llama_context::state_seq_set_data@2944; llama_context::state_load_file@2983; llama_context::state_save_file@3026; llama_context::state_seq_load_file@3043; llama_context::state_seq_save_file@3086; llama_context::state_write_data@3106; llama_context::state_read_data@3126; llama_context::state_seq_write_data@3152; llama_context::state_seq_read_data@3162; llama_context::perf_get_data@3176; llama_context::perf_reset@3190; llama_context::memory_breakdown@3197; llama_set_param@3227; llama_context::opt_init@3243; ggml_context@3356; ggml_init_params@3360; ggml_tensor@3372; llama_batch@3410; llama_context_default_params@3445; llama_free@3579; llama_n_ctx@3583; llama_n_ctx_seq@3587; llama_n_batch@3591; llama_n_ubatch@3595; llama_n_seq_max@3599; llama_n_rs_seq@3603; llama_pooling_type@3611; llama_detach_threadpool@3622; llama_set_n_threads@3626; llama_n_threads@3630; llama_n_threads_batch@3634; llama_set_abort_callback@3638; llama_set_embeddings@3642; llama_set_causal_attn@3646; llama_set_warmup@3650; llama_synchronize@3654; llama_set_embeddings_nextn@3696; llama_set_embeddings_layer_inp@3700; llama_get_memory@3704; llama_set_sampler@3730; llama_get_sampled_token_ith@3734; llama_get_sampled_candidates_count_ith@3758; llama_get_sampled_logits_count_ith@3764; llama_get_sampled_probs_count_ith@3770; ggml_cgraph@3776; llama_context@3777; llama_memory_clear@3821; llama_memory_can_shift@3910; llama_get_state_size@3921; llama_copy_state_data@3926; llama_set_state_data@3931; llama_load_session_file@3936; llama_save_session_file@3941; llama_state_get_size@3947; llama_state_get_data@3951; llama_state_set_data@3958; llama_state_load_file@3964; llama_state_save_file@3975; llama_state_seq_get_size@3986; llama_state_seq_get_data@3990; llama_state_seq_set_data@3994; llama_state_seq_get_size_ext@3998; llama_state_seq_get_data_ext@4002; llama_state_seq_set_data_ext@4007; llama_state_seq_save_file@4013; llama_state_seq_load_file@4024; llama_perf_context@4063; llama_perf_context_print@4075; llama_perf_context_reset@4089; llama_opt_param_filter_all@4097; llama_opt_init@4103; llama_context@4108; llama_get_memory_breakdown@4128
Dependencies: llama-context.h@1; ggml.h@3; llama-arch.h@4; llama-graph.h@5; llama-impl.h@6; llama-batch.h@7; llama-io.h@8; llama-memory.h@9; llama-mmap.h@10; llama-model.h@11; llama-ext.h@12; llama.h@13; cinttypes@15; cmath@16; cstring@17; limits@18; stdexcept@19; moz-overrides.h@21

`third_party/llama.cpp/src/llama-context.h` | `853052be2cadd9b99948e6c526dc287095dea945` | 12576 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model@17; llama_batch_allocr@18; llama_io_read_i@20; llama_io_write_i@21; llama_memory_i@24; llama_memory_context_i@25; llama_memory_buffer@28; llama_context@42; llama_pooling_type@79; sampling_info@302; swap_info@332
Dependencies: llama.h@3; llama-ext.h@4; llama-cparams.h@5; llama-graph.h@6; llama-adapter.h@7; llama-impl.h@8; llama-memory.h@9; ggml-cpp.h@11; ggml-opt.h@12; map@14; vector@15

`third_party/llama.cpp/src/llama-cparams.cpp` | `a3e7a37ee36d78fd6af7d5e3aba8762ecbb636b6` | 100 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_max_parallel_sequences@3
Dependencies: llama-cparams.h@1

`third_party/llama.cpp/src/llama-cparams.h` | `2b109f909c0b8edf5872b742e74c7ca63806ccf9` | 1846 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_cparams@10; llama_context_type@50; llama_pooling_type@51
Dependencies: llama.h@3; cstdint@5; vector@6

`third_party/llama.cpp/src/llama-ext.h` | `8b5679b690bb286ce5b804426183e489605af55a` | 4536 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_context@14; quantize_state_impl@22; llama_quant_model_desc@31; llama_memory_breakdown_data@67; total@72; llama_device_memory_data@77
Dependencies: llama.h@7; cstdint@9; map@10

`third_party/llama.cpp/src/llama-grammar.cpp` | `3872a7641f70db98549d303d9884c26ed5ef1a78` | 55737 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: is_digit_char@97; is_word_char@101; print_grammar_char@234; is_char_element@243; print_rule_binary@254; llama_grammar_trigger_pattern::find@380; llama_grammar_parser::get_symbol_id@418; llama_grammar_parser::generate_symbol_id@424; llama_grammar_parser::add_rule@430; llama_gretype@548; llama_gretype@561; llama_grammar_parser::parse@690; llama_grammar_parser::print@724; llama_grammar_parser::c_rules@741; llama_grammar_is_end_of_sequence@751; llama_grammar@1020; llama_grammar_accept@1045; llama_grammar@1129; llama_grammar@1198; llama_grammar_free_impl@1304; llama_grammar@1312; llama_grammar_apply_impl@1342; llama_grammar_accept_impl@1385; llama_grammar_accept_str@1444; llama_grammar_accept_token@1459
Dependencies: llama-grammar.h@1; llama-impl.h@3; llama-vocab.h@4; llama-sampler.h@5; cmath@7; algorithm@8; cstdint@9; set@10; stdexcept@11; moz-overrides.h@13

`third_party/llama.cpp/src/llama-grammar.h` | `b5a0e588e903be1f3277026ebfbc81cb966216f2` | 6961 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_vocab@10; llama_gretype@13; struct@47; llama_gretype@48; llama_partial_utf8@52; llama_grammar_candidate@57; llama_grammar_parser@86; llama_grammar_parser@92; llama_grammar_trigger_pattern@119; llama_grammar@126; llama_grammar@158; llama_grammar@164; llama_grammar@176; llama_grammar@184; llama_grammar@188; llama_grammar@192
Dependencies: llama.h@3; map@5; regex@6; string@7; vector@8

`third_party/llama.cpp/src/llama-graph.cpp` | `68c9e606c3e390c5096a99df0d5dd44df2a1996c` | 110166 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_graph_input_embd::set_input@84; llm_graph_input_embd::can_reuse@100; llm_graph_input_embd_h::set_input@109; llm_graph_input_embd_h::can_reuse@132; llm_graph_input_pos::set_input@142; llm_graph_input_pos::can_reuse@164; llm_graph_input_attn_temp::set_input@172; llm_graph_input_pos_bucket::set_input@191; llm_graph_input_pos_bucket_kv::set_input@208; llm_graph_input_out_ids::set_input@214; llm_graph_input_out_ids::can_reuse@241; llm_graph_input_mean::set_input@249; llm_graph_input_cls::set_input@295; llm_graph_input_rs::set_input@344; llm_graph_input_rs::can_reuse@360; llm_graph_input_cross_embd::set_input@378; print_mask@389; llm_graph_input_attn_no_cache::set_input@424; llm_graph_input_attn_kv::set_input@485; llm_graph_input_attn_kv::can_reuse@500; llm_graph_input_attn_k::set_input@515; llm_graph_input_attn_k::can_reuse@521; llm_graph_input_attn_k_dsa::set_input@535; llm_graph_input_attn_k_dsa::can_reuse@547; llm_graph_input_attn_kv_iswa::set_input@563; llm_graph_input_attn_kv_iswa::can_reuse@602; llm_graph_input_attn_cross::set_input@632; llm_graph_input_mem_hybrid::set_input@668; llm_graph_input_mem_hybrid::can_reuse@695; llm_graph_input_mem_hybrid_k::set_input@721; llm_graph_input_mem_hybrid_k::can_reuse@739; llm_graph_input_mem_hybrid_iswa::set_input@761; llm_graph_input_mem_hybrid_iswa::can_reuse@813; llm_graph_input_sampling::set_input@849; llm_graph_input_sampling::can_reuse@872; llm_graph_result::llm_graph_result@890; llm_graph_result::get_max_nodes@897; llm_graph_result::reset@901; llm_graph_result::set_inputs@933; llm_graph_result::set_outputs@939; llm_graph_result::can_reuse@983; llm_graph_result::set_params@1020; gf@1069; llm_graph_context::cb@1073; llm_graph_context::build_sampling@3056; llama_sampler_data@3096; llama_relative_position_bucket@3144
Dependencies: llama-graph.h@1; llama-impl.h@3; llama-model.h@4; llama-batch.h@5; llama-cparams.h@6; llama-kv-cache.h@8; llama-kv-cache-iswa.h@9; llama-kv-cache-dsa.h@10; llama-memory-hybrid.h@11; llama-memory-hybrid-iswa.h@12; llama-memory-recurrent.h@13; cassert@15; cmath@16; cstring@17; numeric@18; sstream@19; unordered_set@20

`third_party/llama.cpp/src/llama-graph.h` | `5e8a658350ac0dce5c4a0c550be472b4633ba883` | 39684 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_cgraph@15; ggml_context@16; ggml_tensor@17; llama_cparams@19; llama_layer@20; llama_memory_context_i@22; llama_kv_cache_context@24; llama_kv_cache_dsa_context@25; llama_kv_cache_iswa_context@26; llama_memory_recurrent_context@27; llama_memory_hybrid_context@28; llama_memory_hybrid_iswa_context@29; llm_graph_type@32; llm_ffn_op_type@39; llm_ffn_gate_type@51; llm_norm_type@56; llama_cross@63; llm_graph_params@79; llm_graph_input_i@85; llm_graph_input_i@87; can_reuse@98; llm_graph_input_embd@111; llm_graph_input_embd@113; llm_graph_input_embd_h@127; llm_graph_input_embd_h@129; llm_graph_input_pos@143; llm_graph_input_pos@145; llm_graph_input_attn_temp@158; n_attn_temp_floor_scale@161; llm_graph_input_pos_bucket@173; llm_graph_input_pos_bucket@175; llm_graph_input_pos_bucket_kv@185; llm_graph_input_out_ids@201; llm_graph_input_mean@221; llm_graph_input_mean@223; llm_graph_input_cls@233; llm_graph_input_cls@235; llm_graph_input_rs@246; llm_graph_input_rs@248; llm_graph_input_cross_embd@269; llm_graph_input_attn_no_cache@282; cparams@286; llm_graph_input_attn_kv@305; mctx@313; llm_graph_input_attn_k@347; mctx@355; llm_graph_input_attn_k_dsa@378; mctx@386; llm_graph_input_attn_kv_iswa@416; mctx@424; llm_graph_input_attn_cross@462; llm_graph_input_attn_cross@464; llm_graph_input_mem_hybrid@477; mctx@487; llm_graph_input_mem_hybrid_k@505; mctx@515; llm_graph_input_mem_hybrid_iswa@533; mctx@543; llm_graph_input_sampling@561; samplers@564; llm_graph_result@586; llm_graph_params@588; allow_reuse@631; llm_graph_result@696; llm_graph_qkv@776; llm_graph_context@782
Dependencies: llama-arch.h@3; llama-batch.h@4; llama-hparams.h@5; llama-adapter.h@6; cstdint@8; vector@9; memory@10; set@11; functional@12; map@13

`third_party/llama.cpp/src/llama-hparams.cpp` | `2bf576873824a434ce9f2e99e9ffabed2aa43967` | 7090 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_hparams::set_swa_pattern@8; llama_hparams::set_recr_pattern@24; llama_hparams::is_swa_any@40; llama_hparams::n_head@50; llama_hparams::n_head_kv@58; llama_hparams::n_ff@66; llama_hparams::n_gqa@74; llama_hparams::n_rot@85; llama_hparams::n_embd_inp@93; llama_hparams::n_embd_out@107; llama_hparams::n_embd_head_k@111; llama_hparams::n_embd_head_v@119; llama_hparams::n_embd_k_gqa@127; llama_hparams::n_embd_v_gqa@133; llama_hparams::is_n_embd_k_gqa_variable@139; llama_hparams::is_n_embd_v_gqa_variable@150; llama_hparams::n_embd_k_gqa_max@161; llama_hparams::n_embd_v_gqa_max@170; llama_hparams::n_embd_r@179; llama_hparams::n_embd_s@203; llama_hparams::is_recr@220; llama_hparams::n_pos_per_embd@228; llama_hparams::is_swa@232; llama_hparams::is_mla@240; llama_hparams::n_embd_head_k_mla@247; llama_hparams::n_embd_head_v_mla@251; llama_hparams::has_kv@255; llama_hparams::n_layer@268; llama_hparams::use_mrope@272
Dependencies: llama-hparams.h@1; ggml.h@3; algorithm@5; cassert@6

`third_party/llama.cpp/src/llama-hparams.h` | `d045059a63e9e2fea106d4abb8bc6a987f281099` | 13242 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_expert_gating_func_type@12; llama_swa_type@19; llm_ffn_op_type@27; llama_hparams_posnet@29; llama_hparams_convnext@34; llama_hparams@39; llama_hparams_posnet@76; llama_hparams_convnext@77; llama_pooling_type@247; llama_rope_type@248; llama_rope_scaling_type@249; llm_ffn_op_type@258; is_masked_swa@353
Dependencies: llama.h@3; array@5; cassert@6

`third_party/llama.cpp/src/llama-impl.cpp` | `b3a94b946d2866940763901a8b2cc014827799e7` | 6131 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_logger_state@13; time_meas::time_meas@20; time_meas::~time_meas@22; llama_log_get@28; llama_log_set@32; llama_log_internal_v@38; llama_log_internal@55; llama_log_callback_default@62; replace_all@69; format@86; llama_format_tensor_shape@101; llama_format_tensor_shape@110; gguf_data_to_str@119; gguf_kv_to_str@136
Dependencies: llama-impl.h@1; gguf.h@3; llama.h@4; cinttypes@6; climits@7; cstdarg@8; cstring@9; vector@10; sstream@11

`third_party/llama.cpp/src/llama-impl.h` | `7923c3f7ed55a1f5ffd52e7c13f5b4d1e55a4154` | 2637 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: no_init@39; llama_cast@45; constexpr@46; time_meas@57; buffer_view@67; has_data@71
Dependencies: ggml.h@3; string@5; type_traits@6; vector@7

`third_party/llama.cpp/src/llama-io.cpp` | `5ec4634943f69b64914e2892cb89efc6fd786bd6` | 447 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_io_write_i::write_string@5; llama_io_read_i::read_string@12
Dependencies: llama-io.h@1; vector@3

`third_party/llama.cpp/src/llama-io.h` | `f276af4fb96fdfff712b3b34204d5b825cfc841c` | 812 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_tensor@7; llama_io_write_i@9; llama_io_read_i@23
Dependencies: cstddef@3; cstdint@4; string@5

`third_party/llama.cpp/src/llama-kv-cache-dsa.cpp` | `916ab65375635d9cca6203f942b7da7bb0d93f1f` | 8285 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: hparams_lid@28; llama_kv_cache_dsa::clear@55; llama_kv_cache_dsa::seq_rm@60; llama_kv_cache_dsa::seq_cp@69; llama_kv_cache_dsa::seq_keep@74; llama_kv_cache_dsa::seq_add@79; llama_kv_cache_dsa::seq_div@84; llama_kv_cache_dsa::seq_pos_min@89; llama_kv_cache_dsa::seq_pos_max@93; llama_kv_cache_dsa::init_full@149; llama_kv_cache_dsa::init_update@153; llama_kv_cache_dsa::get_can_shift@157; llama_kv_cache_dsa::state_write@163; llama_kv_cache_dsa::state_read@168; llama_kv_cache_dsa_context::llama_kv_cache_dsa_context@185; status@191; status@200; status@212; llama_kv_cache_dsa_context::next@217; llama_kv_cache_dsa_context::apply@230; llama_kv_cache_dsa_context::get_status@241
Dependencies: llama-kv-cache-dsa.h@1; llama-impl.h@3; llama-batch.h@4; llama-model.h@5; algorithm@7; cassert@8

`third_party/llama.cpp/src/llama-kv-cache-dsa.h` | `e2b330993b848ed46101807b6d14c53e824053f2` | 4223 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_kv_cache_dsa@15; llama_kv_cache_dsa_context@83
Dependencies: llama-kv-cache.h@3; vector@5

`third_party/llama.cpp/src/llama-kv-cache-iswa.cpp` | `aa1b1b72ebe63d3d33d6c17c1575bc39bb88dcf5` | 10693 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_kv_cache_iswa::clear@87; llama_kv_cache_iswa::seq_rm@92; llama_kv_cache_iswa::seq_cp@101; llama_kv_cache_iswa::seq_keep@106; llama_kv_cache_iswa::seq_add@111; llama_kv_cache_iswa::seq_div@116; llama_kv_cache_iswa::seq_pos_min@121; llama_kv_cache_iswa::seq_pos_max@126; llama_kv_cache_iswa::init_batch@138; llama_kv_cache_iswa::init_full@224; llama_kv_cache_iswa::init_update@228; llama_kv_cache_iswa::get_can_shift@232; llama_kv_cache_iswa::state_write@238; llama_kv_cache_iswa::state_read@246; llama_kv_cache_iswa_context::llama_kv_cache_iswa_context@266; status@272; status@281; status@293; llama_kv_cache_iswa_context::next@298; llama_kv_cache_iswa_context::apply@311; llama_kv_cache_iswa_context::get_status@322
Dependencies: llama-kv-cache-iswa.h@1; llama-impl.h@3; llama-batch.h@4; llama-model.h@5; algorithm@7; cassert@8

`third_party/llama.cpp/src/llama-kv-cache-iswa.h` | `dfafc1ef510b8e9a21c85cd4988c9547f0a8e067` | 4198 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_kv_cache_iswa@14; llama_kv_cache_iswa_context@84
Dependencies: llama-kv-cache.h@3; vector@5

`third_party/llama.cpp/src/llama-kv-cache.cpp` | `289a6a0c086e7f7b9e540c010095e2b47ae759e8` | 86228 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_is_power_of_2@18; ggml_gen_hadamard@24; v_cells@103; ggml_backend_buft_comparator@121; operator@122; llama_kv_cache::clear@381; llama_kv_cache::seq_rm@394; llama_kv_cache::seq_cp@462; llama_kv_cache::seq_keep@554; llama_kv_cache::seq_add@581; llama_kv_cache::seq_div@631; llama_kv_cache::seq_pos_min@670; llama_kv_cache::seq_pos_max@683; llama_kv_cache::init_full@750; llama_kv_cache::init_update@754; llama_kv_cache::prepare@762; state_t@765; llama_kv_cache::update@828; llama_kv_cache::find_slot@909; llama_kv_cache::apply_ubatch@1108; llama_kv_cache::get_can_shift@1186; llama_kv_cache::get_size@1197; llama_kv_cache::get_n_stream@1203; llama_kv_cache::get_has_shift@1207; llama_kv_cache::type_k@1217; llama_kv_cache::type_v@1221; llama_kv_cache::get_n_kv@1225; llama_kv_cache::set_input_k_idxs@1451; llama_kv_cache::set_input_v_idxs@1467; llama_kv_cache::set_input_k_shift@1500; args_set_input_kq_mask@1514; set_input_kq_mask_impl@1530; set_input_kq_mask_impl@1679; set_input_kq_mask_impl@1689; set_input_kq_mask_impl@1699; set_input_kq_mask_impl@1709; llama_kv_cache::set_input_kq_mask@1717; llama_kv_cache::set_input_pos_bucket@1755; llama_kv_cache::set_input_k_rot@1780; llama_kv_cache::set_input_v_rot@1789; llama_kv_cache::total_size@1798; llama_kv_cache::size_k_bytes@1808; llama_kv_cache::size_v_bytes@1818; llm_graph_input_k_shift@1880; llm_graph_input_k_shift@1882; llm_graph_input_k_shift::set_input@1895; llama_kv_cache::state_write@1955; llama_kv_cache::state_read@2025; llama_kv_cache::state_write_meta@2068; llama_kv_cache::state_write_data@2101; llama_kv_cache::state_read_meta@2200; llama_kv_cache::state_read_data@2319; llama_kv_cache_context::llama_kv_cache_context@2491; llama_kv_cache_context::next@2528; llama_kv_cache_context::apply@2538; llama_kv_cache_context::get_status@2554; llama_kv_cache_context::get_n_kv@2564; llama_kv_cache_context::type_k@2568; llama_kv_cache_context::type_v@2572; llama_kv_cache_context::set_input_k_shift@2608; llama_kv_cache_context::set_input_k_idxs@2612; llama_kv_cache_context::set_input_v_idxs@2616; llama_kv_cache_context::set_input_kq_mask@2620; llama_kv_cache_context::set_input_pos_bucket@2624; llama_kv_cache_context::set_input_k_rot@2628; llama_kv_cache_context::set_input_v_rot@2632
Dependencies: llama-kv-cache.h@1; llama-impl.h@3; llama-io.h@4; llama-model.h@5; llama-context.h@6; algorithm@8; cassert@9; cmath@10; cstring@11; limits@12; map@13; stdexcept@14; moz-overrides.h@16

`third_party/llama.cpp/src/llama-kv-cache.h` | `3d68f98c1424d77fbba0090813c872766b3e951c` | 14382 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_cparams@11; llama_hparams@12; llama_model@13; llama_context@14; llama_kv_cache@20; stream_copy_info@22; empty@23; slot_info@34; head@45; resize@52; size@57; n_stream@64; empty@68; clear@72; is_contiguous@77; kv_layer@221; cell_ranges_t@307; llama_kv_cache_context@320
Dependencies: llama-batch.h@3; llama-graph.h@4; llama-kv-cells.h@5; llama-memory.h@6; unordered_map@8; vector@9

`third_party/llama.cpp/src/llama-kv-cells.h` | `fddd31a0b219ea0dd5a81ae4dd605cc964f1a225` | 13245 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_kv_cell_ext@13; is_2d_gt@19; reset@23; llama_kv_cells@32; reset@34; reset_shift@51; size@59; resize@63; is_empty@72; get_used@79; used_min@85; used_max_p1@91; get_has_shift@95; cp@120; cp@141; set@160; set@191; rm@222; seq_rm@238; seq_keep@261; seq_count@293; seq_has@301; seq_add@309; seq_get@320; seq_pos_min@334; seq_pos_max@349; pos_get@363; get_shift@378; pos_in@386; pos_set@395; ext_set@405; pos_add@413; pos_div@442; seq_pos_dec@503; seq_pos_inc@512; seq_pos_rm@517; seq_pos_add@526
Dependencies: llama.h@3; llama-cparams.h@4; bitset@6; cassert@7; cstring@8; map@9; set@10; vector@11

`third_party/llama.cpp/src/llama-memory-hybrid-iswa.cpp` | `c7d4bcd413e8f6d633ea53bd44d4dde5a0457b11` | 10155 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_hybrid_iswa::init_batch@66; llama_memory_hybrid_iswa::init_full@130; llama_memory_hybrid_iswa::init_update@134; llama_memory_hybrid_iswa::get_can_shift@138; llama_memory_hybrid_iswa::clear@143; llama_memory_hybrid_iswa::seq_rm@148; llama_memory_hybrid_iswa::seq_cp@157; llama_memory_hybrid_iswa::seq_keep@162; llama_memory_hybrid_iswa::seq_add@167; llama_memory_hybrid_iswa::seq_div@172; llama_memory_hybrid_iswa::seq_pos_min@177; llama_memory_hybrid_iswa::seq_pos_max@182; llama_memory_hybrid_iswa::state_write@195; llama_memory_hybrid_iswa::state_read@200; llama_memory_hybrid_iswa_context::llama_memory_hybrid_iswa_context@217; status@222; status@231; status@243; llama_memory_hybrid_iswa_context::next@246; llama_memory_hybrid_iswa_context::apply@259; llama_memory_hybrid_iswa_context::get_status@270
Dependencies: llama-memory-hybrid-iswa.h@1; llama-impl.h@3; llama-model.h@4; llama-context.h@5

`third_party/llama.cpp/src/llama-memory-hybrid-iswa.h` | `c9d3f9f57c50489202052f170f30a1a2a6f60c0b` | 4565 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_hybrid_iswa@19; llama_memory_hybrid_iswa_context@93
Dependencies: llama-batch.h@3; llama-graph.h@4; llama-kv-cache-iswa.h@5; llama-memory.h@6; llama-memory-recurrent.h@7; memory@9; vector@10

`third_party/llama.cpp/src/llama-memory-hybrid.cpp` | `f2d49cbce545429bb56e375da6c101c0719e92e5` | 9528 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_hybrid::init_batch@67; llama_memory_hybrid::init_full@125; llama_memory_hybrid::init_update@129; llama_memory_hybrid::get_can_shift@133; llama_memory_hybrid::clear@138; llama_memory_hybrid::seq_rm@143; llama_memory_hybrid::seq_cp@152; llama_memory_hybrid::seq_keep@157; llama_memory_hybrid::seq_add@162; llama_memory_hybrid::seq_div@167; llama_memory_hybrid::seq_pos_min@172; llama_memory_hybrid::seq_pos_max@177; llama_memory_hybrid::state_write@190; llama_memory_hybrid::state_read@197; llama_memory_hybrid_context::llama_memory_hybrid_context@212; status@217; status@226; status@237; llama_memory_hybrid_context::next@240; llama_memory_hybrid_context::apply@253; llama_memory_hybrid_context::get_status@264
Dependencies: llama-memory-hybrid.h@1; llama-impl.h@3; llama-model.h@4; llama-context.h@5

`third_party/llama.cpp/src/llama-memory-hybrid.h` | `484eafb749910567b8c50ec36d46bdb678c75426` | 4382 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_hybrid@19; llama_memory_hybrid_context@93
Dependencies: llama-batch.h@3; llama-graph.h@4; llama-kv-cache.h@5; llama-memory.h@6; llama-memory-recurrent.h@7; memory@9; vector@10

`third_party/llama.cpp/src/llama-memory-recurrent.cpp` | `f300c1afacbb90508f825985424fc560522836ed` | 42263 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_backend_buft_comparator@44; operator@45; llama_memory_recurrent::clear@132; llama_memory_recurrent::seq_rm@152; llama_memory_recurrent::seq_cp@237; llama_memory_recurrent::seq_keep@274; llama_memory_recurrent::seq_add@306; llama_memory_recurrent::seq_div@336; llama_memory_recurrent::seq_pos_min@366; llama_memory_recurrent::seq_pos_max@382; llama_memory_recurrent::set_rs_idx@394; llama_memory_recurrent::init_batch@409; llama_memory_recurrent::init_full@454; llama_memory_recurrent::init_update@458; llama_memory_recurrent::prepare@465; llama_memory_recurrent::find_slot@489; llama_memory_recurrent::get_can_shift@700; llama_memory_recurrent::total_size@705; llama_memory_recurrent::size_r_bytes@714; llama_memory_recurrent::size_s_bytes@726; llama_memory_recurrent::state_write@738; llama_memory_recurrent::state_read@818; llama_memory_recurrent::state_write_meta@847; llama_memory_recurrent::state_write_data@866; llama_memory_recurrent::state_read_meta@950; llama_memory_recurrent::state_read_data@1046; llama_memory_recurrent_context::llama_memory_recurrent_context@1174; llama_memory_recurrent_context::next@1186; llama_memory_recurrent_context::apply@1196; llama_memory_recurrent_context::get_status@1212; llama_memory_recurrent_context::get_n_rs@1222; llama_memory_recurrent_context::get_head@1226; llama_memory_recurrent_context::get_rs_z@1230; llama_memory_recurrent_context::get_size@1234; llama_memory_recurrent_context::s_copy@1246
Dependencies: llama-memory-recurrent.h@1; ggml-backend.h@3; llama-impl.h@4; llama-io.h@5; llama-batch.h@6; llama-model.h@7; algorithm@9; cassert@10; cstring@11; limits@12; map@13; stdexcept@14; moz-overrides.h@16

`third_party/llama.cpp/src/llama-memory-recurrent.h` | `b13b7b748f5efaa8f9c597de214769e90421fa0f` | 6059 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_recurrent@17; mem_cell@88; has_seq_id@96; is_empty@100; is_same_seq@104; llama_memory_recurrent_context@136
Dependencies: llama-batch.h@3; llama-graph.h@4; llama-memory.h@5; map@7; set@8; vector@9

`third_party/llama.cpp/src/llama-memory.cpp` | `ca6844c32a76748cb278d90e1898dfa788dd1e3f` | 1534 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_memory_status_combine@3; llama_memory_status_is_fail@44
Dependencies: llama-memory.h@1

`third_party/llama.cpp/src/llama-memory.h` | `db825396645e61c94213ca1e94b78d71d1538d67` | 4669 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_ubatch@10; llama_batch_allocr@12; llama_io_write_i@14; llama_io_read_i@15; llama_memory_params@17; llama_memory_status@30; llama_memory_context_i@51; llama_memory_i@73
Dependencies: llama.h@3; llama-graph.h@4; map@6; memory@7; functional@8

`third_party/llama.cpp/src/llama-mmap.cpp` | `44c0745ff16dd1d53c327f9c7fbe5c1206c72726` | 25208 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_format_win_err@55; llama_file@70; GetErrorMessageWin32@73; impl@88; impl@99; tell@107; seek@118; read_raw@131; read_u32@148; write_raw@154; write_u32@171; has_direct_io@175; impl@185; init_fd@200; stat@204; init_fp@220; impl@230; tell@237; seek@254; read_raw_unsafe@266; read_aligned_chunk@321; aligned_buffer_deleter@333; operator@334; read_raw@345; read_u32@353; write_raw@359; write_u32@370; has_direct_io@374; read_alignment@389; pimpl@401; llama_file::llama_file@403; llama_file::tell@407; llama_file::size@408; llama_file::read_alignment@410; llama_file::has_direct_io@411; llama_file::file_id@413; llama_file::seek@428; llama_file::read_raw@429; llama_file::read_raw_unsafe@431; llama_file::read_raw_unsafe@433; llama_file::read_u32@436; llama_file::write_raw@438; llama_file::write_u32@439; llama_mmap@443; impl@447; align_range@480; unmap_fragment@492; impl@538; unmap_fragment@582; impl@602; unmap_fragment@610; llama_mmap::llama_mmap@622; llama_mmap::size@625; llama_mmap::unmap_fragment@628; llama_mlock@638; lock_granularity@640; raw_lock@644; rlimit@665; raw_unlock@679; lock_granularity@685; raw_lock@691; raw_unlock@719; lock_granularity@726; raw_lock@730; raw_unlock@735; impl@738; init@740; grow_to@745; llama_mlock::llama_mlock@767; llama_mlock::init@770; llama_mlock::grow_to@771; llama_path_max@779
Dependencies: llama-mmap.h@1; llama-impl.h@3; ggml.h@5; cstring@7; climits@8; stdexcept@9; cerrno@10; algorithm@11; unistd.h@15; fcntl.h@16; sys/stat.h@17; sys/mman.h@19; sys/resource.h@22; windows.h@32; io.h@36; TargetConditionals.h@40; moz-overrides.h@43

`third_party/llama.cpp/src/llama-mmap.h` | `b7d5c61e95ffbaf19c347dadcb062de9664f93a3` | 1663 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_file@8; llama_mmap@9; llama_mlock@10; llama_file@16; impl@39; llama_mmap@43; impl@56; llama_mlock@60; impl@70
Dependencies: cstdint@3; memory@4; vector@5; cstdio@6

`third_party/llama.cpp/src/llama-model-loader.cpp` | `cf3c7fd2945e982a4150575363c05f19d88813cf` | 74359 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_ftype_name@32; llama_get_list_splits@80; GGUFMeta@105; GKV_Base_Type@107; getter@110; getter@133; ArrayInfo@138; getter@147; GKV@158; get_kv@162; validate_override@182; try_override@215; try_override@225; try_override@235; try_override@245; set@253; set@262; set@266; llama_model_loader::get_arr_n@274; GGUFMeta@284; llama_model_loader::get_arr_n@294; llama_model_loader::get_arr@301; GGUFMeta@312; constexpr@325; llama_model_loader::get_arr@342; GGUFMeta@353; constexpr@371; std::transform@381; llama_model_loader::get_arr@393; llama_model_loader::get_key@402; llama_model_loader::get_key@418; llama_model_loader::get_key@428; llama_model_loader::get_key_or_arr@441; GGUFMeta@456; llama_model_loader::get_key_or_arr@481; llama_model_loader::get_key_or_arr@485; gguf_context@515; metadata@529; ggml_context@545; gguf_init_params@546; gguf_init_params@621; ggml_context@671; gguf_init_params@672; ggml_context@702; gguf_init_params@703; ggml_type@751; ggml_type@757; llama_model_loader::get_arch_name@866; llm_arch@870; ggml_tensor@891; ggml_tensor@899; ggml_tensor@900; weight_buft_supported@938; select_weight_buft@1077; ggml_tensor@1090; ggml_tensor@1320; ggml_tensor@1332; ggml_tensor@1348; llama_model_loader::done_getting_tensors@1360; llama_model_loader::init_mappings@1378; llama_model_loader::get_mapping_range@1411; llama_model_loader::load_data_for@1428; ggml_context@1456; llama_model_loader::ftype_name@1742; llama_model_loader::print_info@1746
Dependencies: llama-model-loader.h@1; ggml-alloc.h@3; ggml.h@4; gguf.h@5; llama-hparams.h@6; algorithm@8; array@9; cinttypes@10; cstdint@11; cstring@12; regex@13; mutex@14; moz-overrides.h@16

`third_party/llama.cpp/src/llama-model-loader.h` | `60be6fa6f7b00b8cab0e6e1b1abdb0a9f2b5a69b` | 8887 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_fver@23; llama_model_loader@31; llama_tensor_weight@33; llama_tensor_weight@39; llama_tensor_weight@54; weight_name_comparer@70; operator@71; gguf_context@115; ggml_backend_buft_comparator@128; operator@129; gguf_context@144; llm_arch@192; ggml_tensor@198; ggml_tensor@200; ggml_tensor@204; ggml_tensor@208; ggml_context@221
Dependencies: llama.h@3; llama-impl.h@5; llama-arch.h@6; llama-hparams.h@7; llama-mmap.h@8; ggml-cpp.h@10; cstddef@12; cstring@13; map@14; stdexcept@15; unordered_map@16

`third_party/llama.cpp/src/llama-model-saver.cpp` | `a3928523ba8d2cb8a2e15fe533a5369cbe29cb9c` | 22423 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_saver_supports_arch@15; gguf_ctx@38; gguf_ctx@43; llama_model_saver::~llama_model_saver@45; llama_model_saver::add_kv@51; llama_model_saver::add_kv@55; llama_model_saver::add_kv@59; llama_model_saver::add_kv@63; llama_model_saver::add_kv@67; llama_model_saver::add_kv@72; llama_model_saver::add_kv@79; llama_model_saver::add_kv@123; llama_model_saver::add_tensor@131; llama_model_saver::add_kv_from_model@145; llama_model_saver::add_tensors_from_model@385; std::string@387; llama_model_saver::save@414; llama_model_saver::save@418
Dependencies: llama-model-saver.h@1; ggml.h@3; gguf.h@4; llama-arch.h@6; llama.h@7; llama-hparams.h@8; llama-model.h@9; llama-vocab.h@10; cstdint@12; string@13

`third_party/llama.cpp/src/llama-model-saver.h` | `36a715e2b6bf98ac39b24a2f6e6e93d01b0b9c8a` | 1312 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_saver@12; gguf_context@13
Dependencies: gguf.h@3; llama.h@4; llama-arch.h@5; vector@7

`third_party/llama.cpp/src/llama-model.cpp` | `60a9629dc933c7f856e956d4ac03299f3565cd45` | 123323 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ggml_backend_meta_split_state@329; tensor_config@367; std::regex_match@452; std::regex_match@526; std::regex_match@569; std::regex_match@573; std::regex_match@618; std::regex_match@630; llama_rope_scaling_type_name@833; llama_rope_scaling_type_from_string@837; llm_ffn_op_type_from_string@864; make_cpu_buft_list@874; make_gpu_buft_list@936; llama_model@982; layer_dev@1005; llama_model::llama_model@1017; llama_model::~llama_model@1021; llama_model_base::load_stats@1027; llama_model_base::load_hparams@1032; llama_model_base::load_vocab@1212; llama_model_base::load_tensors@1218; llama_model::arch_name@1639; llama_model::type_name@1643; llama_model::desc@1647; llama_model::size@1651; llama_model::n_tensors@1655; llama_model::n_devices@1659; llama_model::n_gpu_layers@1667; llama_model::split_mode@1672; llama_model::n_elements@1695; llama_model::print_info@1699; LLAMA_LOG_INFO@1743; LLAMA_LOG_INFO@1744; LLAMA_LOG_INFO@1750; LLAMA_LOG_INFO@1751; LLAMA_LOG_INFO@1752; LLAMA_LOG_INFO@1760; print_f@1786; llama_model::dev_layer@1915; llama_model::dev_output@1919; buft_supported@1924; select_buft@1951; llama_model::select_buft@1963; llama_model::has_tensor_overrides@1973; llama_model::get_rope_freq_base@1989; llama_model::get_rope_freq_scale@1993; llama_model_default_params@2268; llama_free_model@2296; llama_model_free@2300; llama_model_n_ctx_train@2304; llama_model_n_embd@2308; llama_model_n_embd_inp@2312; llama_model_n_embd_out@2316; llama_model_n_layer@2320; llama_model_n_head@2324; llama_model_n_head_kv@2328; llama_model_n_swa@2332; llama_model_n_cls_out@2337; llama_n_ctx_train@2350; llama_n_embd@2355; llama_n_layer@2360; llama_n_head@2365; llama_model_rope_type@2369; llama_model_rope_freq_scale_train@2528; llama_model_meta_val_str@2532; llama_model_meta_count@2543; llama_model_meta_key_by_index@2565; llama_model_meta_val_str_by_index@2577; llama_model_desc@2589; llama_model_size@2593; llama_model_n_params@2616; llama_model_has_encoder@2620; llama_model_has_decoder@2629; llama_model_decoder_start_token@2636; llama_model_is_recurrent@2640; llama_model_is_hybrid@2644; llama_model_is_diffusion@2648; llama_model_n_expert@2656; llama_model_n_devices@2660; llama_model_get_device@2664; TENSOR_SKIP_IF_VIRTUAL@2679; llama_model_base::create_tensor_gate_up_exps@2686; llama_model_target_layer_ids_n@2716
Dependencies: llama-model.h@1; llama-arch.h@3; llama-ext.h@4; llama-hparams.h@5; llama-impl.h@6; llama-mmap.h@7; llama-cparams.h@8; llama-model-loader.h@9; llama-kv-cache.h@11; llama-kv-cache-iswa.h@12; llama-kv-cache-dsa.h@13; llama-memory-hybrid.h@14; llama-memory-hybrid-iswa.h@15; llama-memory-recurrent.h@16; ggml.h@18; ggml-cpp.h@19; algorithm@21; cassert@22; cfloat@23; cstdint@24; cstring@25; cmath@26; functional@27; map@28; numeric@29; regex@30; sstream@31; stdexcept@32; string@33; vector@34; models/models.h@36; moz-overrides.h@686

`third_party/llama.cpp/src/llama-model.h` | `f4718f6d5842cab145370106d8e7f618be365cac` | 27195 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_cparams@17; llama_ubatch@18; llama_model_loader@19; llm_type@22; llama_layer_posnet@153; ggml_tensor@155; ggml_tensor@156; ggml_tensor@158; ggml_tensor@159; ggml_tensor@161; ggml_tensor@162; ggml_tensor@164; ggml_tensor@165; ggml_tensor@168; ggml_tensor@169; ggml_tensor@171; ggml_tensor@172; ggml_tensor@174; ggml_tensor@175; ggml_tensor@177; ggml_tensor@178; ggml_tensor@180; ggml_tensor@181; ggml_tensor@184; ggml_tensor@185; llama_layer_convnext@188; ggml_tensor@189; ggml_tensor@190; ggml_tensor@192; ggml_tensor@193; ggml_tensor@195; ggml_tensor@196; ggml_tensor@198; ggml_tensor@199; ggml_tensor@201; llama_layer_shortconv@204; ggml_tensor@205; ggml_tensor@206; ggml_tensor@207; llama_layer_nextn@210; ggml_tensor@211; ggml_tensor@212; ggml_tensor@213; ggml_tensor@214; ggml_tensor@215; ggml_tensor@216; ggml_tensor@217; ggml_tensor@218; ggml_tensor@219; ggml_tensor@220; llama_layer@223; ggml_tensor@225; ggml_tensor@226; ggml_tensor@227; ggml_tensor@228; ggml_tensor@229; ggml_tensor@230; ggml_tensor@231; ggml_tensor@232; ggml_tensor@233; ggml_tensor@234; ggml_tensor@235; ggml_tensor@236; ggml_tensor@237; ggml_tensor@238; ggml_tensor@239; ggml_tensor@240; ggml_tensor@241; ggml_tensor@242; ggml_tensor@243; ggml_tensor@244; ggml_tensor@245; ggml_tensor@248; ggml_tensor@249; ggml_tensor@250; ggml_tensor@251; ggml_tensor@252; ggml_tensor@253; ggml_tensor@254; ggml_tensor@255; ggml_tensor@256; ggml_tensor@257; ggml_tensor@258; ggml_tensor@259; ggml_tensor@260; ggml_tensor@261; ggml_tensor@262; ggml_tensor@263; ggml_tensor@264; ggml_tensor@265; ggml_tensor@266; ggml_tensor@267; ggml_tensor@268; ggml_tensor@269; ggml_tensor@272; ggml_tensor@273; ggml_tensor@274; ggml_tensor@277; ggml_tensor@278; ggml_tensor@279; ggml_tensor@280; ggml_tensor@281; ggml_tensor@282; ggml_tensor@283; ggml_tensor@284; ggml_tensor@285; ggml_tensor@286; ggml_tensor@289; ggml_tensor@290; ggml_tensor@291; ggml_tensor@292; ggml_tensor@293; ggml_tensor@294; ggml_tensor@297; ggml_tensor@298; ggml_tensor@299; ggml_tensor@300; ggml_tensor@301; ggml_tensor@302; ggml_tensor@303; ggml_tensor@304; ggml_tensor@305; ggml_tensor@306; ggml_tensor@307; ggml_tensor@310; ggml_tensor@311; ggml_tensor@312; ggml_tensor@315; ggml_tensor@316; ggml_tensor@319; ggml_tensor@320; ggml_tensor@321; ggml_tensor@322; ggml_tensor@325; ggml_tensor@326; ggml_tensor@327; ggml_tensor@330; ggml_tensor@331; ggml_tensor@332; ggml_tensor@333; ggml_tensor@334; ggml_tensor@337; ggml_tensor@338; ggml_tensor@339; ggml_tensor@340; ggml_tensor@343; ggml_tensor@344; ggml_tensor@345; ggml_tensor@348; ggml_tensor@349; ggml_tensor@352; ggml_tensor@355; ggml_tensor@358; ggml_tensor@359; ggml_tensor@360; ggml_tensor@361; ggml_tensor@362; ggml_tensor@363; ggml_tensor@364; ggml_tensor@365; ggml_tensor@366; ggml_tensor@368; ggml_tensor@369; ggml_tensor@370; ggml_tensor@371; ggml_tensor@372; ggml_tensor@373; ggml_tensor@374; ggml_tensor@375; ggml_tensor@376; ggml_tensor@377; ggml_tensor@378; ggml_tensor@381; ggml_tensor@382; ggml_tensor@383; ggml_tensor@384; ggml_tensor@385; ggml_tensor@386; ggml_tensor@387; ggml_tensor@388; ggml_tensor@389; ggml_tensor@390; ggml_tensor@391; ggml_tensor@392; ggml_tensor@394; ggml_tensor@395; ggml_tensor@396; ggml_tensor@398; ggml_tensor@399; ggml_tensor@401; ggml_tensor@402; ggml_tensor@403; ggml_tensor@406; ggml_tensor@407; ggml_tensor@408; ggml_tensor@411; ggml_tensor@412; ggml_tensor@413; ggml_tensor@414; ggml_tensor@415; ggml_tensor@416; ggml_tensor@417; ggml_tensor@418; ggml_tensor@419; ggml_tensor@420; ggml_tensor@421; ggml_tensor@422; ggml_tensor@423; ggml_tensor@424; ggml_tensor@425; ggml_tensor@426; ggml_tensor@429; ggml_tensor@430; ggml_tensor@431; ggml_tensor@432; ggml_tensor@433; ggml_tensor@434; ggml_tensor@435; ggml_tensor@436; ggml_tensor@437; ggml_tensor@438; ggml_tensor@439; ggml_tensor@440; ggml_tensor@441; ggml_tensor@442; ggml_tensor@443; ggml_tensor@444; ggml_tensor@445; ggml_tensor@446; ggml_tensor@447; ggml_tensor@450; ggml_tensor@451; ggml_tensor@452; ggml_tensor@453; ggml_tensor@454; ggml_tensor@455; ggml_tensor@456; ggml_tensor@457; ggml_tensor@458; ggml_tensor@459; ggml_tensor@460; ggml_tensor@463; ggml_tensor@466; ggml_tensor@467; ggml_tensor@468; ggml_tensor@469; ggml_tensor@470; ggml_tensor@473; ggml_tensor@474; ggml_tensor@475; ggml_tensor@476; ggml_tensor@480; ggml_tensor@481; ggml_tensor@482; ggml_tensor@483; ggml_tensor@484; ggml_tensor@485; ggml_tensor@486; ggml_tensor@487; ggml_tensor@488; ggml_tensor@491; ggml_tensor@492; ggml_tensor@493; ggml_tensor@494; ggml_tensor@495; ggml_tensor@498; llama_layer_posnet@500; llama_layer_convnext@502; llama_layer_shortconv@504; llama_layer_nextn@506; llama_device@509; llama_meta_device_get_split_state_userdata@515; ggml_backend_meta_split_state@520; llama_model@522; ggml_tensor@534; ggml_tensor@535; ggml_tensor@536; ggml_tensor@537; ggml_tensor@538; ggml_tensor@540; ggml_tensor@541; ggml_tensor@542; ggml_tensor@543; ggml_tensor@544; ggml_tensor@548; ggml_tensor@549; ggml_tensor@552; ggml_tensor@553; ggml_tensor@556; ggml_tensor@557; ggml_tensor@558; ggml_tensor@559; ggml_tensor@560; ggml_tensor@562; ggml_tensor@563; ggml_tensor@566; ggml_tensor@567; ggml_tensor@568; ggml_tensor@569; ggml_tensor@570; ggml_tensor@573; ggml_tensor@574; ggml_tensor@584; ggml_tensor@585; ggml_tensor@586; llama_meta_device_get_split_state_userdata@601; impl@660; llama_model_base@668
Dependencies: llama.h@3; llama-arch.h@4; llama-graph.h@5; llama-hparams.h@6; llama-memory.h@7; llama-vocab.h@8; map@10; memory@11; string@12; unordered_map@13; unordered_set@14; vector@15

`third_party/llama.cpp/src/llama-quant.h` | `6f70f09beec2219624baeca92e2cd7deaa104fb4` | 13 bytes | imported-path,source | UTF-8 | mode 100644

`third_party/llama.cpp/src/llama-sampler.cpp` | `10c60f7f9b1980df2e2178f16558af2b5b4d99c3` | 131866 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: ring_buffer@27; ring_buffer@28; push_back@58; pop_front@73; to_vector@104; clear@113; empty@120; size@124; llama_token_data_array_partial_sort@137; llama_token_data_array_partial_sort_inplace@195; llama_sample_dist@219; probs_iterator@226; std@227; float@228; float@229; float@230; ptrdiff_t@231; llama_log_softmax@252; llama_sampler_temp_impl@267; llama_sampler_softmax_impl@291; llama_sampler_top_k_impl@319; get_rng_seed@338; llama_sampler@354; llama_sampler_i@355; llama_sampler_accept@371; llama_sampler_apply@381; llama_sampler_reset@390; llama_sampler@400; llama_sampler_free@419; llama_sampler_empty@433; llama_sampler@437; llama_sampler_empty_accept@444; llama_sampler_empty_apply@449; llama_sampler_empty_reset@454; llama_sampler@458; llama_sampler_empty_free@463; llama_sampler@468; llama_sampler@477; ggml_tensor@480; llama_sampler@488; ggml_context@489; ggml_cgraph@490; llama_sampler_data@491; llama_sampler_empty_backend_set_input@498; llama_sampler_i@502; llama_sampler@515; llama_sampler_backend@529; llama_sampler_backend@530; init@546; ggml_tensor@614; llama_sampler_chain_accept@633; llama_sampler_chain_apply@645; llama_sampler_chain_reset@667; llama_sampler@675; llama_sampler_chain_free@687; llama_sampler@698; llama_sampler@731; ggml_tensor@734; llama_sampler@749; ggml_context@750; ggml_cgraph@751; llama_sampler_data@752; llama_sampler_chain_backend_set_input@768; llama_sampler_i@782; llama_sampler@795; llama_sampler_sample@809; llama_sampler_chain_add@879; llama_sampler@887; llama_sampler@909; llama_sampler_chain_n@922; llama_sampler_greedy@934; llama_sampler_greedy_reset@942; llama_sampler@947; llama_sampler_greedy_free@962; llama_sampler_greedy_apply@966; llama_sampler@976; llama_sampler@988; ggml_context@989; ggml_cgraph@990; llama_sampler_data@991; ggml_tensor@995; llama_sampler_i@1001; llama_sampler@1014; llama_sampler_dist@1025; llama_sampler_dist_apply@1039; llama_sampler_dist_reset@1111; llama_sampler@1117; llama_sampler_dist_free@1131; llama_sampler@1136; llama_sampler@1148; ggml_context@1149; ggml_cgraph@1150; llama_sampler_data@1151; ggml_tensor@1160; ggml_tensor@1163; ggml_tensor@1171; ggml_tensor@1178; ggml_tensor@1183; ggml_tensor@1188; ggml_tensor@1192; ggml_tensor@1194; llama_sampler_dist_backend_set_input@1204; llama_sampler_i@1220; llama_sampler@1233; llama_sampler_top_k@1249; llama_sampler_top_k_apply@1258; llama_sampler@1263; llama_sampler_top_k_free@1268; llama_sampler@1273; llama_sampler@1285; ggml_context@1286; ggml_cgraph@1287; llama_sampler_data@1288; ggml_tensor@1291; ggml_tensor@1295; ggml_tensor@1303; ggml_tensor@1304; llama_sampler_i@1311; llama_sampler@1324; llama_sampler_top_p@1342; llama_sampler_top_p_apply@1354; llama_sampler@1409; llama_sampler_top_p_free@1414; llama_sampler@1419; llama_sampler@1431; ggml_context@1432; ggml_cgraph@1433; llama_sampler_data@1434; ggml_tensor@1439; ggml_tensor@1440; ggml_tensor@1445; ggml_tensor@1449; ggml_tensor@1452; ggml_tensor@1464; ggml_tensor@1468; ggml_tensor@1471; ggml_tensor@1476; ggml_tensor@1483; ggml_tensor@1487; ggml_tensor@1494; llama_sampler_i@1503; llama_sampler@1516; llama_sampler_min_p@1536; llama_sampler_min_p_apply@1546; llama_sampler@1600; llama_sampler_min_p_free@1605; llama_sampler@1610; llama_sampler@1622; ggml_context@1623; ggml_cgraph@1624; llama_sampler_data@1625; ggml_tensor@1628; ggml_tensor@1631; ggml_tensor@1634; ggml_tensor@1638; ggml_tensor@1642; ggml_tensor@1646; ggml_tensor@1651; llama_sampler_i@1660; llama_sampler@1673; llama_sampler_typical@1692; llama_sampler_typical_apply@1701; std::sort@1729; llama_sampler@1761; llama_sampler_typical_free@1766; llama_sampler_i@1770; llama_sampler@1783; llama_sampler_temp@1801; llama_sampler_temp_apply@1810; llama_sampler@1816; llama_sampler_temp_free@1821; ggml_context@1826; ggml_cgraph@1827; llama_sampler_data@1828; ggml_tensor@1832; ggml_tensor@1836; ggml_tensor@1842; llama_sampler@1854; llama_sampler@1866; ggml_context@1867; ggml_cgraph@1868; llama_sampler_data@1869; llama_sampler_i@1874; llama_sampler@1887; llama_sampler_temp_ext@1905; llama_sampler_temp_ext_apply@1916; llama_sampler@1987; llama_sampler_temp_ext_free@1992; llama_sampler@1997; llama_sampler@2009; ggml_context@2010; ggml_cgraph@2011; llama_sampler_data@2012; ggml_tensor@2027; ggml_tensor@2031; ggml_tensor@2035; ggml_tensor@2036; ggml_tensor@2037; ggml_tensor@2038; ggml_tensor@2045; ggml_tensor@2053; ggml_tensor@2054; ggml_tensor@2055; ggml_tensor@2058; ggml_tensor@2065; llama_sampler_i@2071; llama_sampler@2084; llama_sampler_xtc@2106; llama_sample_xtc_apply@2121; llama_sampler@2154; llama_sampler_xtc_free@2168; llama_sampler_xtc_reset@2172; llama_sampler_i@2178; llama_sampler@2191; llama_sampler_mirostat@2215; llama_sampler_mirostat_apply@2235; llama_sampler@2271; llama_sampler_mirostat_reset@2286; llama_sampler_mirostat_free@2293; llama_sampler_i@2297; llama_sampler@2310; llama_sampler_mirostat_v2@2330; llama_sampler_mirostat_v2_apply@2346; llama_sampler_mirostat_v2_reset@2374; llama_sampler@2381; llama_sampler_mirostat_v2_free@2397; llama_sampler_i@2401; llama_sampler@2414; llama_sampler_grammar@2431; llama_grammar@2437; llama_sampler_grammar_accept_impl@2444; llama_sampler_grammar_apply@2451; llama_sampler@2459; llama_sampler_grammar_reset@2471; llama_sampler@2491; llama_sampler_grammar_free@2512; llama_sampler_i@2522; llama_sampler@2535; llama_sampler@2594; llama_sampler@2601; llama_sampler@2612; llama_sampler_penalties@2625; llama_sampler_penalties_accept@2641; llama_sampler_penalties_apply@2672; llama_sampler_penalties_reset@2705; llama_sampler@2711; llama_sampler_penalties_free@2729; llama_sampler_i@2733; llama_sampler@2746; llama_sampler_top_n_sigma@2774; llama_sampler_top_n_sigma_apply@2782; llama_sampler@2823; llama_sampler_top_n_sigma_free@2828; llama_sampler_i@2832; llama_sampler@2845; llama_sampler_dry@2862; get_overlapping_token_sequences@2877; llama_sampler_dry_accept@2923; llama_sampler_dry_apply@2933; llama_sampler_dry_reset@3141; llama_sampler@3148; llama_sampler_dry_free@3168; llama_sampler_i@3172; llama_sampler@3185; llama_sampler@3237; llama_sampler_adaptive_p@3274; llama_sampler_adaptive_p_apply@3297; llama_sampler_adaptive_p_accept@3348; llama_sampler_adaptive_p_reset@3361; llama_sampler@3374; llama_sampler_adaptive_p_free@3388; llama_sampler_i@3392; llama_sampler@3405; llama_sampler_logit_bias@3431; ggml_tensor@3438; ggml_tensor@3439; llama_sampler_logit_bias_apply@3447; llama_sampler@3480; llama_sampler_logit_bias_free@3485; llama_sampler@3490; ggml_context@3491; ggml_cgraph@3492; llama_sampler_data@3493; llama_sampler_logit_bias_backend_set_input@3521; llama_sampler@3546; llama_sampler_i@3561; llama_sampler@3574; llama_sampler_infill@3601; llama_sampler_infill_apply@3612; llama_sampler@3795; llama_sampler_infill_free@3800; llama_sampler_i@3804; llama_sampler@3817; llama_sampler_get_seed@3830; llama_perf_sampler_data@3858; llama_perf_sampler_data@3859; llama_perf_sampler_print@3873; llama_perf_sampler_reset@3879
Dependencies: llama-sampler.h@1; llama-impl.h@3; llama-vocab.h@4; llama-grammar.h@5; ggml-cpp.h@7; array@9; algorithm@10; cassert@11; cfloat@12; chrono@13; cmath@14; cstdlib@15; cstring@16; ctime@17; numeric@18; random@19; unordered_map@20; stdexcept@21; moz-overrides.h@23

`third_party/llama.cpp/src/llama-sampler.h` | `b9bfc20d251738289b6c8357c38a0a04178b8b8c` | 854 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_vocab@7; llama_grammar@8; llama_sampler_chain@12; info@18; llama_sampler@36
Dependencies: llama.h@3; vector@5

`third_party/llama.cpp/src/llama-vocab.cpp` | `924957674a26a6524a518cc89090561191c740c2` | 176880 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: naive_trie@30; naive_trie@31; insert@33; llm_tokenizer@77; llm_tokenizer@78; llm_symbol@82; llm_bigram_spm@98; comparator@99; operator@100; llm_tokenizer_spm@112; llm_tokenizer_spm@113; llm_tokenizer_spm_session@116; llm_tokenizer_spm_session@117; tokenize@119; resegment@178; try_add_bigram@204; llama_priority_queue@251; pop_move@255; llm_bigram_bpe@265; comparator@266; operator@267; llm_tokenizer_bpe@281; llm_tokenizer_bpe@282; llm_tokenizer_bpe_session@557; llm_tokenizer_bpe_session@558; append@562; append_bos@566; append_eos@575; check_double_bos_eos@584; tokenize@599; add_new_bigram@722; llm_tokenizer_wpm@760; llm_tokenizer_wpm@761; llm_tokenizer_wpm_session@764; llm_tokenizer_wpm_session@765; tokenize@767; preprocess@814; is_chinese_char@859; llm_tokenizer_ugm@883; llm_tokenizer_ugm@884; naive_trie@939; naive_trie@947; llm_tokenizer_ugm_session@950; llm_tokenizer_ugm_session@951; tokenize@966; best_tokenization@1009; best_tokenization@1011; best_tokenization@1023; best_tokenization@1025; normalization_result@1055; normalize@1061; xcda_array_view@1116; xcda_array_view@1118; get_base@1120; get_lcheck@1124; get_leaf@1128; get_value@1132; get_node@1137; best_tokenization@1148; normalization_result@1154; xcda_array_view@1170; llama_unescape_rwkv_token@1233; llm_tokenizer_rwkv@1287; llm_tokenizer_rwkv@1288; naive_trie@1300; llm_tokenizer_rwkv_session@1303; llm_tokenizer_rwkv_session@1304; tokenize@1306; llm_tokenizer_plamo2@1339; llm_tokenizer_plamo2@1340; build@1344; std::sort@1401; encode@1479; llm_tokenizer_plamo2_session@1606; llm_tokenizer_plamo2_session@1607; tokenize@1609; llm_tokenizer_hybriddna_session@1623; emit_dna_kmers@1671; llm_tokenizer_whitespace_session@1700; enum@1733; fragment_buffer_variant@1738; length@1745; length@1753; llama_vocab@1767; llama_vocab_type@1773; llama_vocab_pre_type@1774; pair_hash@1818; operator@1819; impl@1835; llama_vocab_type@1842; llama_vocab::impl::load@1909; gguf_context@1910; llama_vocab_type@3006; llama_vocab::impl::type_name@3010; llama_vocab::impl::is_normal@3023; llama_vocab::impl::is_unknown@3028; llama_vocab::impl::is_control@3033; llama_vocab::impl::is_byte@3038; llama_vocab::impl::is_user_defined@3043; llama_vocab::impl::is_unused@3048; llama_vocab::impl::is_eog@3053; llama_vocab::impl::token_to_byte@3057; llama_vocab::impl::token_get_attr@3080; llama_vocab::impl::init_tokenizer@3085; llama_vocab::impl::tokenizer_st_partition@3118; llama_vocab::impl::token_to_piece_for_cache@3237; llama_escape_whitespace@3253; llama_unescape_whitespace@3257; llama_decode_text@3261; llama_vocab::impl::token_to_piece@3487; llama_vocab::impl::print_info@3720; llama_vocab::llama_vocab@3751; llama_vocab::load@3756; llama_vocab::get_tokenizer_model@3760; llama_vocab::get_tokenizer_pre@3764; llama_vocab_type@3768; llama_vocab_pre_type@3772; llama_vocab::n_tokens@3776; llama_vocab::n_token_types@3780; llama_vocab::type_name@3784; llama_vocab::is_normal@3788; llama_vocab::is_unknown@3792; llama_vocab::is_control@3796; llama_vocab::is_byte@3800; llama_vocab::is_user_defined@3804; llama_vocab::is_unused@3808; llama_vocab::is_eog@3812; llama_vocab::token_to_byte@3816; llama_vocab::byte_to_token@3820; llama_vocab::text_to_token@3850; llama_vocab::token_get_score@3869; llama_vocab::token_get_attr@3874; llama_vocab::token_bos@3878; llama_vocab::token_eos@3882; llama_vocab::token_eot@3886; llama_vocab::token_eom@3890; llama_vocab::token_unk@3894; llama_vocab::token_sep@3898; llama_vocab::token_nl@3902; llama_vocab::token_pad@3906; llama_vocab::token_prefix@3910; llama_vocab::token_middle@3914; llama_vocab::token_suffix@3918; llama_vocab::token_fim_pre@3922; llama_vocab::token_fim_suf@3926; llama_vocab::token_fim_mid@3930; llama_vocab::token_fim_pad@3934; llama_vocab::token_fim_rep@3938; llama_vocab::token_fim_sep@3942; llama_vocab::token_mask@3946; llama_vocab::get_add_space_prefix@3950; llama_vocab::get_add_bos@3954; llama_vocab::get_add_eos@3958; llama_vocab::get_add_sep@3962; llama_vocab::get_ignore_merges@3966; llama_vocab::get_clean_spaces@3970; llama_vocab::get_remove_extra_whitespaces@3974; llama_vocab::get_escape_whitespaces@3978; llama_vocab::get_treat_whitespace_as_suffix@3982; llama_vocab::max_token_len@3994; llama_vocab::find_bpe_rank@3998; llama_vocab::get_bpe_merges@4010; llama_vocab::get_precompiled_charsmap@4020; llama_vocab::token_to_piece@4060; llama_vocab::detokenize@4074; llama_vocab::print_info@4090; llama_vocab_n_tokens@4098; llama_n_vocab@4103; llama_vocab_type@4107; llama_vocab_get_score@4115; llama_token_attr@4119; llama_vocab_is_eog@4123; llama_vocab_is_control@4127; llama_vocab_bos@4131; llama_vocab_eos@4135; llama_vocab_eot@4139; llama_vocab_cls@4144; llama_vocab_sep@4148; llama_vocab_nl@4152; llama_vocab_pad@4156; llama_vocab_get_add_bos@4160; llama_vocab_get_add_eos@4164; llama_vocab_get_add_sep@4168; llama_vocab_fim_pre@4172; llama_vocab_fim_suf@4176; llama_vocab_fim_mid@4180; llama_vocab_fim_pad@4184; llama_vocab_fim_rep@4188; llama_vocab_fim_sep@4192; llama_vocab_mask@4196; llama_token_get_score@4206; llama_token_attr@4211; llama_token_is_eog@4216; llama_token_is_control@4221; llama_token_bos@4226; llama_token_eos@4231; llama_token_eot@4236; llama_token_cls@4241; llama_token_sep@4247; llama_token_nl@4252; llama_token_pad@4257; llama_add_bos_token@4262; llama_add_eos_token@4267; llama_token_fim_pre@4272; llama_token_fim_suf@4277; llama_token_fim_mid@4282; llama_token_fim_pad@4287; llama_token_fim_rep@4292; llama_token_fim_sep@4297
Dependencies: llama-vocab.h@1; ggml.h@3; gguf.h@4; llama-impl.h@5; llama-model-loader.h@6; unicode.h@8; algorithm@10; cassert@11; cctype@12; cfloat@13; cmath@14; cstdarg@15; cstring@16; forward_list@17; limits@18; map@19; queue@20; set@21; unordered_map@22; moz-overrides.h@24

`third_party/llama.cpp/src/llama-vocab.h` | `707cd4bac4bfa03e2f662baef0a2d4943a1ce584` | 7227 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_vocab_pre_type@10; LLM_KV@69; llama_model_loader@70; llama_vocab@72; token_data@73; normalizer_options@79; llama_vocab_type@93; llama_vocab_pre_type@94; impl@200
Dependencies: llama.h@3; string@5; vector@6; memory@7

`third_party/llama.cpp/src/llama.cpp` | `43044e7ce3885a245279c113b883c4d93315ee65` | 21614 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_sampler_chain_params@51; llama_sampler_chain_params@52; llama_max_devices@59; llama_max_tensor_buft_overrides@63; llama_supports_mmap@67; llama_supports_mlock@71; llama_supports_gpu_offload@75; llama_supports_rpc@84; llama_backend_init@91; ggml_init_params@96; ggml_context@97; llama_numa_init@106; llama_backend_free@118; llama_time_us@122; llama_prepare_model_devices@127; llama_model@343; gguf_context@344; llama_model_params@352; llama_model@414; gguf_context@415; llama_model_params@418; llama_model@427; llama_model_params@429; llama_model@433; llama_model_params@435; llama_model@440; llama_model_params@443; llama_model@456; llama_model@469; llama_model@474; llama_model_save_to_file@484
Dependencies: llama.h@1; llama-impl.h@3; llama-chat.h@5; llama-context.h@6; llama-mmap.h@7; llama-vocab.h@8; llama-model-loader.h@9; llama-model-saver.h@10; llama-model.h@11; ggml.h@13; ggml-cpp.h@14; ggml-backend.h@15; gguf.h@16; algorithm@18; cassert@19; cinttypes@20; cstddef@21; cstdint@22; cstdio@23; cstring@24; ctime@25; stdexcept@26; vector@27; moz-overrides.h@29

`third_party/llama.cpp/src/models/afmoe.cpp` | `063b214256e760f8b7a092c13c31a9ae51d4a667` | 12187 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_afmoe::load_arch_hparams@3; llama_model_afmoe::load_arch_tensors@40; llama_model_afmoe::build_arch_graph@105; llama_model_afmoe::graph::graph@109
Dependencies: models.h@1

`third_party/llama.cpp/src/models/apertus.cpp` | `6dfb8905fbe574ac973f39d446941504c56b8c64` | 7005 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_apertus::load_arch_hparams@3; llama_model_apertus::load_arch_tensors@17; llama_model_apertus::build_arch_graph@56; llama_model_apertus::graph::graph@60
Dependencies: models.h@1

`third_party/llama.cpp/src/models/arcee.cpp` | `9536e7c5d4291ef33923ed8bf1b739ee7b1beefe` | 5443 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_arcee::load_arch_hparams@3; llama_model_arcee::load_arch_tensors@13; llama_model_arcee::build_arch_graph@44; llama_model_arcee::graph::graph@48
Dependencies: models.h@1

`third_party/llama.cpp/src/models/arctic.cpp` | `09ee0f752f0ebb34e42b57b551448998b0745688` | 6371 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_arctic::load_arch_hparams@3; llama_model_arctic::load_arch_tensors@16; llama_model_arctic::build_arch_graph@52; llama_model_arctic::graph::graph@56
Dependencies: models.h@1

`third_party/llama.cpp/src/models/arwkv7.cpp` | `b38b2064785b2d4ec566a228e01fded680e2a67f` | 9322 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_arwkv7::load_arch_hparams@3; llama_model_arwkv7::load_arch_tensors@46; llama_model_arwkv7::build_arch_graph@116; llama_model_arwkv7::graph::graph@120
Dependencies: models.h@1

`third_party/llama.cpp/src/models/baichuan.cpp` | `585f3614174160bc547bcea00918abc5c407f33a` | 5263 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_baichuan::load_arch_hparams@3; llama_model_baichuan::load_arch_tensors@17; llama_model_baichuan::build_arch_graph@42; llama_model_baichuan::graph::graph@46
Dependencies: models.h@1

`third_party/llama.cpp/src/models/bailingmoe.cpp` | `7faf73c835b64d7387ca77ea11b645074967b8a5` | 6903 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_bailingmoe::load_arch_hparams@3; llama_model_bailingmoe::load_arch_tensors@18; llama_model_bailingmoe::build_arch_graph@58; llama_model_bailingmoe::graph::graph@62
Dependencies: models.h@1

`third_party/llama.cpp/src/models/bailingmoe2.cpp` | `5000e9c6db896427ef73560cb0e8eae8575a7cdf` | 9853 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_bailingmoe2::load_arch_hparams@3; llama_model_bailingmoe2::load_arch_tensors@23; llama_model_bailingmoe2::build_arch_graph@89; llm_graph_context@94
Dependencies: models.h@1

`third_party/llama.cpp/src/models/bert.cpp` | `53ce29f23caec1b312129f7a8a65fdec47b17f5f` | 10160 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_bert::load_arch_hparams@3; llama_model_bert::load_arch_tensors@23; llama_model_bert::build_arch_graph@76; llama_model_bert::graph::graph@80
Dependencies: models.h@1

`third_party/llama.cpp/src/models/bitnet.cpp` | `c83302745806870b61843f80a815206ff0640419` | 6483 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_bitnet::load_arch_hparams@3; llama_model_bitnet::load_arch_tensors@12; llama_model_bitnet::build_arch_graph@47; llama_model_bitnet::graph::graph@51
Dependencies: models.h@1

`third_party/llama.cpp/src/models/bloom.cpp` | `609d2ddf998b7579cbcd4d8a07c09d0bc9f0492b` | 5508 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_bloom::load_arch_hparams@3; llama_model_bloom::load_arch_tensors@21; llama_model_bloom::build_arch_graph@61; llama_model_bloom::graph::graph@65
Dependencies: models.h@1

`third_party/llama.cpp/src/models/chameleon.cpp` | `50f2636e9fabdb0631c96742d60dcbfbe26279a0` | 7540 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_chameleon::load_arch_hparams@4; llama_model_chameleon::load_arch_tensors@16; llama_model_chameleon::build_arch_graph@49; llama_model_chameleon::graph::graph@53
Dependencies: float.h@1; models.h@2

`third_party/llama.cpp/src/models/chatglm.cpp` | `7ae5b938fde36a916b4ccef10584f077a953aa63` | 5296 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_chatglm::load_arch_hparams@3; llama_model_chatglm::load_arch_tensors@25; llama_model_chatglm::build_arch_graph@54; llama_model_chatglm::graph::graph@58
Dependencies: models.h@1

`third_party/llama.cpp/src/models/codeshell.cpp` | `de53bb9818479cefa2f6196d235db0988a59c720` | 5468 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_codeshell::load_arch_hparams@3; llama_model_codeshell::load_arch_tensors@12; llama_model_codeshell::build_arch_graph@49; llama_model_codeshell::graph::graph@53
Dependencies: models.h@1

`third_party/llama.cpp/src/models/cogvlm.cpp` | `750f57a394e3ed6d0bf62b8833b644db17454376` | 6341 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_cogvlm::load_arch_hparams@3; llama_model_cogvlm::load_arch_tensors@12; llama_model_cogvlm::build_arch_graph@49; llm_graph_context@54
Dependencies: models.h@1

`third_party/llama.cpp/src/models/cohere2.cpp` | `e2b3662560df89f443b0e1a8f0fd8a9f05a11bda` | 5815 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_cohere2::load_arch_hparams@3; llama_model_cohere2::load_arch_tensors@23; llama_model_cohere2::build_arch_graph@48; llama_model_cohere2::graph::graph@52
Dependencies: models.h@1

`third_party/llama.cpp/src/models/cohere2moe.cpp` | `499c73a1c49c421d456b134bd3d2c9a094c809ff` | 19624 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_cohere2moe::load_arch_hparams@3; llama_model_cohere2moe::load_arch_tensors@48; llama_model_cohere2moe::build_arch_graph@149; llama_model_cohere2moe::graph::graph@156; llama_model_cohere2moe::graph_mtp::graph_mtp@295
Dependencies: models.h@1

`third_party/llama.cpp/src/models/command-r.cpp` | `94a46188bb89698b40f39ebb7f829ae5a1a4babe` | 5325 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_command_r::load_arch_hparams@3; llama_model_command_r::load_arch_tensors@13; llama_model_command_r::build_arch_graph@42; llm_graph_context@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/dbrx.cpp` | `4f5ac4d06a4542a3dc37b20095c18677c1392aae` | 5250 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_dbrx::load_arch_hparams@3; llama_model_dbrx::load_arch_tensors@13; llama_model_dbrx::build_arch_graph@43; llama_model_dbrx::graph::graph@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/deci.cpp` | `cdfcf29e02f57e6d384f6ce990f39d52fb999cb8` | 7920 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_deci::load_arch_hparams@3; llama_model_deci::load_arch_tensors@14; llama_model_deci::build_arch_graph@76; llama_model_deci::graph::graph@80
Dependencies: models.h@1

`third_party/llama.cpp/src/models/deepseek.cpp` | `f52ec9518b6c27e0e78dd93793fa5ed72d52b664` | 7981 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_deepseek::load_arch_hparams@3; llama_model_deepseek::load_arch_tensors@17; llama_model_deepseek::build_arch_graph@70; llm_graph_context@75
Dependencies: models.h@1

`third_party/llama.cpp/src/models/deepseek2.cpp` | `a9e8bc51403656cf0ddc30792f5dbd6a99509b21` | 20638 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_deepseek2::load_arch_hparams@3; llama_model_deepseek2::load_arch_tensors@55; llama_model_deepseek2::build_arch_graph@142; llm_graph_context@147
Dependencies: models.h@1

`third_party/llama.cpp/src/models/deepseek2ocr.cpp` | `65d31c31b93e710545efa3fde7317557f2b268ff` | 4150 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_deepseek2ocr::load_arch_hparams@3; llama_model_deepseek2ocr::load_arch_tensors@23; llama_model_deepseek2ocr::build_arch_graph@79
Dependencies: models.h@1

`third_party/llama.cpp/src/models/deepseek32.cpp` | `db42784b3d467df4ec3941cbb8c541950c4ee200` | 25880 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_deepseek32::load_arch_hparams@5; llama_model_deepseek32::load_arch_tensors@51; llama_model_deepseek32::build_arch_graph@154; llm_graph_context@159
Dependencies: llama-kv-cache.h@1; llama-kv-cache-dsa.h@2; models.h@3

`third_party/llama.cpp/src/models/delta-net-base.cpp` | `e6e2fe17776b40bbd256c0ead20f999e6b52ffa9` | 23664 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_build_delta_net_base::llm_build_delta_net_base@13
Dependencies: llama-impl.h@1; llama-memory-recurrent.h@2; models.h@3

`third_party/llama.cpp/src/models/dots1.cpp` | `07d6ab1b7cdb25e9a09cbc470748c21a383385fc` | 8250 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_dots1::load_arch_hparams@3; llama_model_dots1::load_arch_tensors@18; llama_model_dots1::build_arch_graph@70; llm_graph_context@75
Dependencies: models.h@1

`third_party/llama.cpp/src/models/dream.cpp` | `abe737c335a4a377c6c44663c82c698d041f0140` | 4951 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_dream::load_arch_hparams@3; llama_model_dream::load_arch_tensors@18; llama_model_dream::build_arch_graph@48; llm_graph_context@53
Dependencies: models.h@1

`third_party/llama.cpp/src/models/eagle3.cpp` | `3321b390515d3caa87cdde5c159b78b1efdc1f44` | 13309 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_eagle3::load_arch_hparams@3; llama_model_eagle3::load_arch_tensors@34; llama_model_eagle3::build_arch_graph@94
Dependencies: models.h@1

`third_party/llama.cpp/src/models/ernie4-5-moe.cpp` | `8d9ff138676426b9ac62238a9f1634ece5546cf7` | 5091 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_ernie4_5_moe::build_arch_graph@3; llm_graph_context@8
Dependencies: models.h@1

`third_party/llama.cpp/src/models/ernie4-5.cpp` | `895cf690bd2d8e9f21ebfcc153ebd77fb73ae32f` | 6933 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_ernie4_5::load_arch_hparams@3; llama_model_ernie4_5::load_arch_tensors@23; llama_model_ernie4_5::build_arch_graph@72; llm_graph_context@77
Dependencies: models.h@1

`third_party/llama.cpp/src/models/eurobert.cpp` | `0948d7de656f1cac68c3ab48248c3bab4b1a302f` | 4167 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_eurobert::load_arch_hparams@3; llama_model_eurobert::load_arch_tensors@11; llama_model_eurobert::build_arch_graph@34; llama_model_eurobert::graph::graph@38
Dependencies: models.h@1

`third_party/llama.cpp/src/models/exaone-moe.cpp` | `5aed9379400c398cccf364fc962d35d292dd53dd` | 11240 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_exaone_moe::load_arch_hparams@3; llama_model_exaone_moe::load_arch_tensors@33; llama_model_exaone_moe::build_arch_graph@109; llm_graph_context@114
Dependencies: models.h@1

`third_party/llama.cpp/src/models/exaone.cpp` | `676fb37b5a63956e1ba2ed07a60288fedcf39eb0` | 5123 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_exaone::load_arch_hparams@3; llama_model_exaone::load_arch_tensors@12; llama_model_exaone::build_arch_graph@42; llm_graph_context@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/exaone4.cpp` | `863268abcef2dd0e45bd085e187a68175de73306` | 7902 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_exaone4::load_arch_hparams@3; llama_model_exaone4::load_arch_tensors@29; llama_model_exaone4::build_arch_graph@78; llm_graph_context@88; constexpr@105
Dependencies: models.h@1

`third_party/llama.cpp/src/models/falcon-h1.cpp` | `d6ef2d51986235c36b66254a5a12b1a844dc9200` | 9017 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_falcon_h1::load_arch_hparams@3; llama_model_falcon_h1::load_arch_tensors@34; llama_model_falcon_h1::build_arch_graph@108; llm_build_mamba_base@113
Dependencies: models.h@1

`third_party/llama.cpp/src/models/falcon.cpp` | `b2ad90b327243c35096f8a596fe82aca6f6ab8d2` | 5607 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_falcon::load_arch_hparams@3; llama_model_falcon::load_arch_tensors@13; llama_model_falcon::build_arch_graph@46; llama_model_falcon::graph::graph@50
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma-embedding.cpp` | `80ed3b1a4605d0e6839eab9e2cf6d0df5f1cd12d` | 7484 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma_embedding::load_arch_hparams@3; llama_model_gemma_embedding::load_arch_tensors@32; llama_model_gemma_embedding::build_arch_graph@71; llm_graph_context@76
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma.cpp` | `651cd7e64de0f6c1f6bd46418d5224ced7388e48` | 4858 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma::load_arch_hparams@3; llama_model_gemma::load_arch_tensors@13; llama_model_gemma::build_arch_graph@37; llama_model_gemma::graph::graph@41
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma2.cpp` | `2fbfb15a94a39a605d2e3ba1426304d7dc922e27` | 6841 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma2::load_arch_hparams@3; llama_model_gemma2::load_arch_tensors@32; llama_model_gemma2::build_arch_graph@58; llama_model_gemma2::graph::graph@62
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma3.cpp` | `690194529e381ff8682b62515973bc2685ada6bd` | 8784 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma3::load_arch_hparams@3; llama_model_gemma3::load_arch_tensors@36; llama_model_gemma3::build_arch_graph@75; constexpr@103; constexpr@115
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma3n.cpp` | `83eb8250aa94b923116c69f72a1a776e8bb6c45b` | 23665 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma3n::load_arch_hparams@3; llama_model_gemma3n::load_arch_tensors@23; llama_model_gemma3n::build_arch_graph@80; i_altup_act@97
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma4-assistant.cpp` | `6378130e79ec55ec72377d3e16bd9ca0b8d6d2ad` | 8758 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma4_assistant::load_arch_hparams@3; llama_model_gemma4_assistant::load_arch_tensors@24; llama_model_gemma4_assistant::build_arch_graph@83; llm_graph_context@88
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gemma4.cpp` | `6a96979cebde316694177ab5f0da4cdff0534493` | 23437 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gemma4::load_arch_hparams@3; llama_model_gemma4::load_arch_tensors@31; llama_model_gemma4::build_arch_graph@134; llm_graph_input_logits_bias@146; llm_graph_input_logits_bias@148; n_embd_per_layer@175
Dependencies: models.h@1

`third_party/llama.cpp/src/models/glm-dsa.cpp` | `11d91312defc072a0c19527936628df5df0a9fa0` | 8836 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_glm_dsa::load_arch_hparams@3; llama_model_glm_dsa::load_arch_tensors@45; llama_model_glm_dsa::build_arch_graph@149
Dependencies: models.h@1

`third_party/llama.cpp/src/models/glm4-moe.cpp` | `d60e47ddf0c6599901c9b01a9c278a2b697839e8` | 13059 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_glm4_moe::load_arch_hparams@3; llama_model_glm4_moe::load_arch_tensors@34; llama_model_glm4_moe::build_arch_graph@129; llama_model_glm4_moe::graph::graph@133
Dependencies: models.h@1

`third_party/llama.cpp/src/models/glm4.cpp` | `b4326c5f2107f70c5fe3d9523c1506f613c67101` | 8019 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_glm4::load_arch_hparams@3; llama_model_glm4::load_arch_tensors@19; llama_model_glm4::build_arch_graph@68; llama_model_glm4::graph::graph@72
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gpt2.cpp` | `45afbccc1210f973038d4455c43a166d98312a3b` | 5368 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gpt2::load_arch_hparams@3; llama_model_gpt2::load_arch_tensors@15; llama_model_gpt2::build_arch_graph@54; llama_model_gpt2::graph::graph@58
Dependencies: models.h@1

`third_party/llama.cpp/src/models/gptneox.cpp` | `ed5e8c50da2f5430315cd0f06ee1f8de219dfb54` | 8009 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_gptneox::load_arch_hparams@3; llama_model_gptneox::load_arch_tensors@50; llama_model_gptneox::build_arch_graph@83; llama_model_gptneox::graph::graph@87
Dependencies: models.h@1

`third_party/llama.cpp/src/models/granite-hybrid.cpp` | `eb23095aece6d5acb9f3b9ce608b6b8449ad1b6d` | 13534 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_granite_hybrid::load_arch_hparams@3; llama_model_granite_hybrid::load_arch_tensors@40; llama_model_granite_hybrid::build_arch_graph@130; llm_build_mamba_base@135; ggml_tensor@155
Dependencies: models.h@1

`third_party/llama.cpp/src/models/granite-moe.cpp` | `115263c418faefb2d07e7d8501b9c16ee4ad6895` | 4807 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_granite_moe::load_arch_hparams@3; llama_model_granite_moe::load_arch_tensors@26; llama_model_granite_moe::build_arch_graph@86
Dependencies: models.h@1

`third_party/llama.cpp/src/models/granite.cpp` | `ab06fca6ab1f510fcda613ba1856b819d23a4440` | 12196 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_granite::load_arch_hparams@4; llama_model_granite::load_arch_tensors@48; llama_model_granite::build_arch_graph@108; llm_graph_context@115
Dependencies: sstream@1; models.h@2

`third_party/llama.cpp/src/models/grok.cpp` | `42f38af672438149dcdac7380436d1e8691515ef` | 8962 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_grok::load_arch_hparams@3; llama_model_grok::load_arch_tensors@35; llama_model_grok::build_arch_graph@82; llama_model_grok::graph::graph@86
Dependencies: models.h@1

`third_party/llama.cpp/src/models/grovemoe.cpp` | `643a448e59ac103c170f6bbbada7cfd597fd4f71` | 7954 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_grovemoe::load_arch_hparams@3; llama_model_grovemoe::load_arch_tensors@16; llama_model_grovemoe::build_arch_graph@63; llm_graph_context@68
Dependencies: models.h@1

`third_party/llama.cpp/src/models/hunyuan-dense.cpp` | `c137bd37c0272465c667563d406e5d6009e000a1` | 195 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_hunyuan_dense::build_arch_graph@3
Dependencies: models.h@1

`third_party/llama.cpp/src/models/hunyuan-moe.cpp` | `4d55f5e7f3170dac75f3d1317c714e6657067f57` | 7274 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_hunyuan_moe::load_arch_hparams@3; llama_model_hunyuan_moe::load_arch_tensors@14; llama_model_hunyuan_moe::build_arch_graph@52; llama_model_hunyuan_moe::graph::graph@56
Dependencies: models.h@1

`third_party/llama.cpp/src/models/hunyuan-vl.cpp` | `da9bb74de7eb777cf88fa31bce244bb91b72fe4e` | 7306 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_hunyuan_vl::load_arch_hparams@3; llama_model_hunyuan_vl::load_arch_tensors@23; llama_model_hunyuan_vl::build_arch_graph@56; llama_model_hunyuan_vl::graph::graph@60
Dependencies: models.h@1

`third_party/llama.cpp/src/models/internlm2.cpp` | `f6cfdfb9458f81c197c2dbf4349522ed43d33187` | 4864 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_internlm2::load_arch_hparams@3; llama_model_internlm2::load_arch_tensors@13; llama_model_internlm2::build_arch_graph@37; llama_model_internlm2::graph::graph@41
Dependencies: models.h@1

`third_party/llama.cpp/src/models/jais.cpp` | `415103ce23a86c475c32e2b60db39575dec669be` | 5002 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_jais::load_arch_hparams@3; llama_model_jais::load_arch_tensors@15; llama_model_jais::build_arch_graph@51; llama_model_jais::graph::graph@55
Dependencies: models.h@1

`third_party/llama.cpp/src/models/jais2.cpp` | `8610fcc9f82f6c854329e8e1ba46d0b845e14b83` | 6300 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_jais2::load_arch_hparams@3; llama_model_jais2::load_arch_tensors@13; llama_model_jais2::build_arch_graph@54; llama_model_jais2::graph::graph@60
Dependencies: models.h@1

`third_party/llama.cpp/src/models/jamba.cpp` | `dba160b014fd630632d3ff2eae687c7c57746e12` | 7853 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_jamba::load_arch_hparams@3; llama_model_jamba::load_arch_tensors@23; llama_model_jamba::build_arch_graph@104; llama_model_jamba::graph::graph@108; ggml_tensor@145
Dependencies: models.h@1

`third_party/llama.cpp/src/models/jina-bert-v2.cpp` | `86ff1c84d1a66b51a3e6638acb17089ff20ffe94` | 3645 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_jina_bert_v2::load_arch_hparams@3; llama_model_jina_bert_v2::load_arch_tensors@14; llama_model_jina_bert_v2::build_arch_graph@63
Dependencies: models.h@1

`third_party/llama.cpp/src/models/jina-bert-v3.cpp` | `1c974a6f16cc04ed8d4d4e83bc05af4e7d668f69` | 3538 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_jina_bert_v3::load_arch_hparams@3; llama_model_jina_bert_v3::load_arch_tensors@13; llama_model_jina_bert_v3::build_arch_graph@66
Dependencies: models.h@1

`third_party/llama.cpp/src/models/kimi-linear.cpp` | `2f60ef583606b39538bc5de24a81b176f361a955` | 30609 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_kimi_linear::load_arch_hparams@4; llama_model_kimi_linear::load_arch_tensors@34; llama_model_kimi_linear::build_arch_graph@169; llm_build_delta_net_base@235
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/lfm2.cpp` | `636c8bc735b1ec1fecb0aeaab0270744e77d8fea` | 13309 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_lfm2::load_arch_hparams@5; llama_model_lfm2::load_arch_tensors@31; llama_model_lfm2::build_arch_graph@86; llm_graph_context@96; constexpr@226
Dependencies: ../llama-memory-hybrid-iswa.h@1; ../llama-memory-hybrid.h@2; models.h@3

`third_party/llama.cpp/src/models/lfm2moe.cpp` | `2e17956737c3e37fd6eb43000b77ecdb7bdfa73c` | 4448 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_lfm2moe::load_arch_hparams@5; llama_model_lfm2moe::load_arch_tensors@23; llama_model_lfm2moe::build_arch_graph@78
Dependencies: ../llama-memory-hybrid-iswa.h@1; ../llama-memory-hybrid.h@2; models.h@3

`third_party/llama.cpp/src/models/llada-moe.cpp` | `2ae893864472cdb21fb8f47687f2203bc0b5669b` | 5948 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_llada_moe::load_arch_hparams@3; llama_model_llada_moe::load_arch_tensors@16; llama_model_llada_moe::build_arch_graph@50; llama_model_llada_moe::graph::graph@54
Dependencies: models.h@1

`third_party/llama.cpp/src/models/llada.cpp` | `87d4259f9a7477f5bb04c33688750c8743308b71` | 6191 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_llada::load_arch_hparams@3; llama_model_llada::load_arch_tensors@19; llama_model_llada::build_arch_graph@67; llama_model_llada::graph::graph@71
Dependencies: models.h@1

`third_party/llama.cpp/src/models/llama-embed.cpp` | `0699e744461b8839f289e3425fbfedc6a3adf930` | 199 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_llama_embed::build_arch_graph@3
Dependencies: models.h@1

`third_party/llama.cpp/src/models/llama4.cpp` | `7194c72a585097bd5e8cfc4b5e51614f691e4723` | 11327 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_llama4::load_arch_hparams@3; llama_model_llama4::load_arch_tensors@46; llama_model_llama4::build_arch_graph@98; constexpr@128
Dependencies: models.h@1

`third_party/llama.cpp/src/models/maincoder.cpp` | `ae56a26a1f640fd98d3d23159aee02d5051102bd` | 5427 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_maincoder::load_arch_hparams@3; llama_model_maincoder::load_arch_tensors@12; llama_model_maincoder::build_arch_graph@43; llama_model_maincoder::graph::graph@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mamba-base.cpp` | `82b9c2187c063c50f369ef6031ab0079511aa17c` | 14624 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_build_mamba_base::llm_build_mamba_base@4
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/mamba.cpp` | `0d94e98281cec02cad7cd3efe23137044a42a6fe` | 4918 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mamba::load_arch_hparams@3; llama_model_mamba::load_arch_tensors@34; llama_model_mamba::build_arch_graph@83; llama_model_mamba::graph::graph@87
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mamba2.cpp` | `c5951cf0f7fccaf805d157844709f549de12b5f0` | 3509 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mamba2::load_arch_hparams@3; llama_model_mamba2::load_arch_tensors@35; llama_model_mamba2::build_arch_graph@84
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mellum.cpp` | `28823018bc0b4504d8a7290e0fd43e05ca983637` | 8442 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mellum::load_arch_hparams@3; llama_model_mellum::load_arch_tensors@33; llama_model_mellum::build_arch_graph@72; constexpr@97
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mimo2.cpp` | `88989160570138947678a55ba4acf4b65d487a71` | 9906 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mimo2::load_arch_hparams@3; llama_model_mimo2::load_arch_tensors@28; llama_model_mimo2::build_arch_graph@77; llama_model_mimo2::graph::graph@81
Dependencies: models.h@1

`third_party/llama.cpp/src/models/minicpm.cpp` | `fc3e5b171d524ef9504894a17cd8c9147f4f99e4` | 4737 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_minicpm::load_arch_hparams@3; llama_model_minicpm::load_arch_tensors@26; llama_model_minicpm::build_arch_graph@86
Dependencies: models.h@1

`third_party/llama.cpp/src/models/minicpm3.cpp` | `e011b1ff0a84cca17022bb4c08e9a0263b66a4f3` | 11320 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_minicpm3::load_arch_hparams@3; llama_model_minicpm3::load_arch_tensors@14; llama_model_minicpm3::build_arch_graph@59; llama_model_minicpm3::graph::graph@63
Dependencies: models.h@1

`third_party/llama.cpp/src/models/minimax-m2.cpp` | `b25435e4d97c750920ed2d218f308914ea6605fe` | 6331 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_minimax_m2::load_arch_hparams@3; llama_model_minimax_m2::load_arch_tensors@14; llama_model_minimax_m2::build_arch_graph@43; llama_model_minimax_m2::graph::graph@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mistral3.cpp` | `9a8e3f9a50b79820b583e5e66712fd9d956762d5` | 9878 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mistral3::load_arch_hparams@3; llama_model_mistral3::load_arch_tensors@29; llama_model_mistral3::build_arch_graph@89; llama_model_mistral3::graph::graph@93
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mistral4.cpp` | `3d9190650e37aabf7c286df01f5ff720a14443ca` | 190 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mistral4::build_arch_graph@3
Dependencies: models.h@1

`third_party/llama.cpp/src/models/model-llama.cpp` | `4bfebc8843c655e122e5f2064a791c583ad3779b` | 10554 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_llama::load_arch_hparams@3; llama_model_llama::load_arch_tensors@34; llama_model_llama::build_arch_graph@94; constexpr@116; constexpr@238
Dependencies: models.h@1

`third_party/llama.cpp/src/models/models.h` | `19a4d3c5eaf4724b6bf0c1797b0c17a82cc859b2` | 78525 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llm_build_mamba_base@16; llm_build_delta_net_base@26; llm_build_rwkv6_base@95; llm_build_rwkv7_base@115; llama_model_llama@139; llama_model_llama@140; graph@145; llama_model_llama4@153; llama_model_llama4@154; graph@159; llama_model_llama_embed@167; llama_model_llama_embed@168; llama_model_maincoder@178; llama_model_maincoder@179; graph@183; llama_model_talkie@191; llama_model_talkie@192; graph@196; llama_model_deci@204; llama_model_deci@205; graph@209; llama_model_baichuan@217; llama_model_baichuan@218; graph@222; llama_model_falcon@230; llama_model_falcon@231; graph@235; llama_model_grok@243; llama_model_grok@244; graph@248; llama_model_starcoder@256; llama_model_starcoder@257; graph@261; llama_model_refact@269; llama_model_refact@270; graph@274; llama_model_bert@282; llama_model_bert@283; graph@287; llama_model_jina_bert_v2@295; llama_model_jina_bert_v2@296; llama_model_jina_bert_v3@306; llama_model_jina_bert_v3@307; llama_model_nomic_bert@317; llama_model_nomic_bert@318; llama_model_nomic_bert_moe@328; llama_model_nomic_bert_moe@329; llama_model_modern_bert@339; llama_model_modern_bert@340; graph@344; llama_model_neo_bert@352; llama_model_neo_bert@353; graph@357; llama_model_eurobert@365; llama_model_eurobert@366; graph@370; llama_model_bloom@378; llama_model_bloom@379; graph@383; llama_model_mpt@391; llama_model_mpt@392; graph@396; llama_model_stablelm@404; llama_model_stablelm@405; graph@409; llama_model_mellum@416; llama_model_mellum@417; graph@422; llama_model_qwen@429; llama_model_qwen@430; graph@434; llama_model_qwen2@442; llama_model_qwen2@443; graph@447; llama_model_dream@455; llama_model_dream@456; graph@460; llama_model_llada@468; llama_model_llada@469; graph@473; llama_model_llada_moe@481; llama_model_llada_moe@482; graph@486; llama_model_rnd1@494; llama_model_rnd1@495; graph@499; llama_model_qwen2vl@507; llama_model_qwen2vl@508; graph@512; llama_model_qwen2moe@520; llama_model_qwen2moe@521; graph@525; llama_model_qwen3@533; llama_model_qwen3@534; graph@538; llama_model_qwen3moe@546; llama_model_qwen3moe@547; graph@551; llama_model_qwen3vl@559; llama_model_qwen3vl@560; graph@564; llama_model_qwen3vlmoe@572; llama_model_qwen3vlmoe@573; graph@577; llama_model_phi2@585; llama_model_phi2@586; graph@590; llama_model_phi3@598; llama_model_phi3@599; graph@604; llama_model_phimoe@612; llama_model_phimoe@613; llama_model_plamo@624; llama_model_plamo@625; graph@629; llama_model_plamo2@637; llama_model_plamo2@638; graph@642; llama_model_plamo3@654; llama_model_plamo3@655; graph@660; llama_model_gpt2@668; llama_model_gpt2@669; graph@673; llama_model_codeshell@681; llama_model_codeshell@682; graph@686; llama_model_orion@694; llama_model_orion@695; graph@699; llama_model_internlm2@707; llama_model_internlm2@708; graph@712; llama_model_minicpm3@720; llama_model_minicpm3@721; graph@725; llama_model_gemma@733; llama_model_gemma@734; graph@738; llama_model_gemma2@746; llama_model_gemma2@747; graph@751; llama_model_gemma3@759; llama_model_gemma3@760; graph@765; llama_model_gemma3n@773; llama_model_gemma3n@774; graph@778; llama_model_gemma4@806; llama_model_gemma4@807; graph@811; llama_model_gemma4_assistant@827; llama_model_gemma4_assistant@828; graph@832; llama_model_gemma_embedding@840; llama_model_gemma_embedding@841; graph@845; llama_model_starcoder2@853; llama_model_starcoder2@854; graph@858; llama_model_mamba@866; llama_model_mamba@867; graph@871; llama_model_mamba2@879; llama_model_mamba2@880; llama_model_jamba@890; llama_model_jamba@891; graph@895; llama_model_xverse@903; llama_model_xverse@904; graph@908; llama_model_command_r@916; llama_model_command_r@917; graph@921; llama_model_cohere2@929; llama_model_cohere2@930; graph@934; llama_model_cohere2moe@942; llama_model_cohere2moe@943; graph@947; graph_mtp@951; llama_model_dbrx@959; llama_model_dbrx@960; graph@964; llama_model_olmo@972; llama_model_olmo@973; graph@977; llama_model_olmo2@985; llama_model_olmo2@986; graph@991; llama_model_olmoe@999; llama_model_olmoe@1000; graph@1004; llama_model_openelm@1012; llama_model_openelm@1013; graph@1017; llama_model_gptneox@1025; llama_model_gptneox@1026; graph@1030; llama_model_arctic@1038; llama_model_arctic@1039; graph@1043; llama_model_deepseek@1051; llama_model_deepseek@1052; graph@1056; llama_model_deepseek2@1064; llama_model_deepseek2@1065; graph@1069; llama_model_deepseek32@1077; llama_model_deepseek32@1078; graph@1082; llama_model_deepseek2ocr@1090; llama_model_deepseek2ocr@1091; llama_model_glm_dsa@1101; llama_model_glm_dsa@1102; llama_model_eagle3@1111; llama_model_eagle3@1112; graph@1117; llama_model_mistral4@1127; llama_model_mistral4@1128; llama_model_chatglm@1137; llama_model_chatglm@1138; graph@1142; llama_model_glm4@1150; llama_model_glm4@1151; graph@1155; llama_model_glm4_moe@1163; llama_model_glm4_moe@1164; graph@1168; llama_model_bitnet@1176; llama_model_bitnet@1177; graph@1181; llama_model_t5@1189; llama_model_t5@1190; graph@1195; llama_model_t5encoder@1203; llama_model_t5encoder@1204; llama_model_jais@1214; llama_model_jais@1215; graph@1219; llama_model_jais2@1227; llama_model_jais2@1228; graph@1232; llama_model_nemotron@1240; llama_model_nemotron@1241; graph@1245; llama_model_nemotron_h@1253; llama_model_nemotron_h@1254; graph@1258; llama_model_nemotron_h_moe@1269; llama_model_nemotron_h_moe@1270; llama_model_exaone@1279; llama_model_exaone@1280; graph@1284; llama_model_exaone4@1292; llama_model_exaone4@1293; graph@1298; llama_model_exaone_moe@1306; llama_model_exaone_moe@1307; graph@1311; llama_model_rwkv6@1319; llama_model_rwkv6@1320; graph@1324; llama_model_rwkv6qwen2@1332; llama_model_rwkv6qwen2@1333; graph@1337; llama_model_rwkv7@1345; llama_model_rwkv7@1346; graph@1350; llama_model_arwkv7@1358; llama_model_arwkv7@1359; graph@1363; llama_model_granite@1371; llama_model_granite@1372; graph@1376; llama_model_granite_moe@1399; llama_model_granite_moe@1400; llama_model_minicpm@1410; llama_model_minicpm@1411; llama_model_granite_hybrid@1421; llama_model_granite_hybrid@1422; graph@1426; llama_model_chameleon@1437; llama_model_chameleon@1438; graph@1442; llama_model_wavtokenizer_dec@1450; llama_model_wavtokenizer_dec@1451; graph@1455; llama_model_plm@1463; llama_model_plm@1464; graph@1468; llama_model_bailingmoe@1476; llama_model_bailingmoe@1477; graph@1481; llama_model_bailingmoe2@1489; llama_model_bailingmoe2@1490; graph@1494; llama_model_seed_oss@1502; llama_model_seed_oss@1503; graph@1507; llama_model_dots1@1515; llama_model_dots1@1516; graph@1520; llama_model_arcee@1528; llama_model_arcee@1529; graph@1533; llama_model_afmoe@1541; llama_model_afmoe@1542; graph@1546; llama_model_ernie4_5@1554; llama_model_ernie4_5@1555; graph@1559; llama_model_ernie4_5_moe@1567; llama_model_ernie4_5_moe@1568; graph@1571; llama_model_paddleocr@1579; llama_model_paddleocr@1580; graph@1583; llama_model_hunyuan_moe@1591; llama_model_hunyuan_moe@1592; graph@1596; llama_model_hunyuan_vl@1604; llama_model_hunyuan_vl@1605; graph@1609; llama_model_hunyuan_dense@1617; llama_model_hunyuan_dense@1618; llama_model_smollm3@1627; llama_model_smollm3@1628; graph@1632; llama_model_openai_moe@1640; llama_model_openai_moe@1641; graph@1645; llama_model_falcon_h1@1653; llama_model_falcon_h1@1654; graph@1658; llama_model_lfm2@1666; llama_model_lfm2@1667; graph@1672; llama_model_lfm2moe@1680; llama_model_lfm2moe@1681; llama_model_smallthinker@1692; llama_model_smallthinker@1693; graph@1698; llama_model_grovemoe@1706; llama_model_grovemoe@1707; graph@1711; llama_model_apertus@1719; llama_model_apertus@1720; graph@1724; llama_model_minimax_m2@1732; llama_model_minimax_m2@1733; graph@1737; llama_model_cogvlm@1745; llama_model_cogvlm@1746; graph@1750; llama_model_pangu_embed@1758; llama_model_pangu_embed@1759; graph@1763; llama_model_qwen3next@1771; llama_model_qwen3next@1772; graph@1776; llama_model_qwen35@1812; llama_model_qwen35@1813; graph@1817; graph_mtp@1850; llama_model_qwen35moe@1858; llama_model_qwen35moe@1859; graph@1863; graph_mtp@1896; llama_model_mistral3@1904; llama_model_mistral3@1905; graph@1909; llama_model_mimo2@1917; llama_model_mimo2@1918; graph@1922; llama_model_kimi_linear@1930; llama_model_kimi_linear@1931; graph@1935; llama_model_step35@1966; llama_model_step35@1967; graph@1971; graph_mtp@1975
Dependencies: llama-model.h@3; llama-graph.h@4; llama-model-loader.h@5; cmath@8; moz-overrides.h@10

`third_party/llama.cpp/src/models/modern-bert.cpp` | `f3e9407e0125cca79bd040d3e88ecb4c58b43168` | 6483 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_modern_bert::load_arch_hparams@3; llama_model_modern_bert::load_arch_tensors@36; llama_model_modern_bert::build_arch_graph@70; llama_model_modern_bert::graph::graph@74
Dependencies: models.h@1

`third_party/llama.cpp/src/models/mpt.cpp` | `d094fd9f80bcf757b0fda0b30922c07605e52374` | 6991 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_mpt::load_arch_hparams@3; llama_model_mpt::load_arch_tensors@15; llama_model_mpt::build_arch_graph@63; llama_model_mpt::graph::graph@67
Dependencies: models.h@1

`third_party/llama.cpp/src/models/nemotron-h-moe.cpp` | `a59cc6c9fbd7fe60de129ae2995d84af847020ae` | 196 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_nemotron_h_moe::build_arch_graph@3
Dependencies: models.h@1

`third_party/llama.cpp/src/models/nemotron-h.cpp` | `a456269347b9aec0711d0c31100f9f528f437c61` | 11812 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_nemotron_h::load_arch_hparams@3; llama_model_nemotron_h::load_arch_tensors@33; llama_model_nemotron_h::build_arch_graph@120; llm_build_mamba_base@125; ggml_tensor@140
Dependencies: models.h@1

`third_party/llama.cpp/src/models/nemotron.cpp` | `6e2bd9a33ca88e62d4757b81f1d04108526f23a9` | 5406 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_nemotron::load_arch_hparams@3; llama_model_nemotron::load_arch_tensors@12; llama_model_nemotron::build_arch_graph@46; llama_model_nemotron::graph::graph@50
Dependencies: models.h@1

`third_party/llama.cpp/src/models/neo-bert.cpp` | `4a08d7abd40f1ba2fd658c6fe4e048dda88f30a3` | 4730 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_neo_bert::load_arch_hparams@3; llama_model_neo_bert::load_arch_tensors@11; llama_model_neo_bert::build_arch_graph@39; llama_model_neo_bert::graph::graph@43
Dependencies: models.h@1

`third_party/llama.cpp/src/models/nomic-bert-moe.cpp` | `da4b62919bb97aa6422d2a9d0199eabeb9e7f6a8` | 3763 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_nomic_bert_moe::load_arch_hparams@3; llama_model_nomic_bert_moe::load_arch_tensors@16; llama_model_nomic_bert_moe::build_arch_graph@69
Dependencies: models.h@1

`third_party/llama.cpp/src/models/nomic-bert.cpp` | `e7fc72286a6d615a8f8b4f208f509819b8ea7bb5` | 3751 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_nomic_bert::load_arch_hparams@3; llama_model_nomic_bert::load_arch_tensors@16; llama_model_nomic_bert::build_arch_graph@69
Dependencies: models.h@1

`third_party/llama.cpp/src/models/olmo.cpp` | `9f7a2ba60efb8af5f4e521e22ed42a1be054a19e` | 4728 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_olmo::load_arch_hparams@3; llama_model_olmo::load_arch_tensors@15; llama_model_olmo::build_arch_graph@39; llama_model_olmo::graph::graph@43
Dependencies: models.h@1

`third_party/llama.cpp/src/models/olmo2.cpp` | `cb52cdef720486f4b99f033acee0b76ba215e628` | 7933 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_olmo2::load_arch_hparams@3; llama_model_olmo2::load_arch_tensors@29; llama_model_olmo2::build_arch_graph@56; constexpr@82
Dependencies: models.h@1

`third_party/llama.cpp/src/models/olmoe.cpp` | `1e2baeb207ff8ab1e6f48be4f9e91c56c157340c` | 6205 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_olmoe::load_arch_hparams@3; llama_model_olmoe::load_arch_tensors@12; llama_model_olmoe::build_arch_graph@49; llama_model_olmoe::graph::graph@53
Dependencies: models.h@1

`third_party/llama.cpp/src/models/openai-moe.cpp` | `6d74f9c7e6ef8152f48ed26f608aa41105fbe6e9` | 6733 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_openai_moe::load_arch_hparams@3; llama_model_openai_moe::load_arch_tensors@24; llama_model_openai_moe::build_arch_graph@60; llama_model_openai_moe::graph::graph@64
Dependencies: models.h@1

`third_party/llama.cpp/src/models/openelm.cpp` | `13120bd3236d9b35a780235ba8a1fa19674b2c9b` | 6334 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_openelm::load_arch_hparams@3; llama_model_openelm::load_arch_tensors@15; llama_model_openelm::build_arch_graph@46; llama_model_openelm::graph::graph@50
Dependencies: models.h@1

`third_party/llama.cpp/src/models/orion.cpp` | `863a2822269b62e67a6a3ab700ce2ffa4267a6f8` | 4986 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_orion::load_arch_hparams@3; llama_model_orion::load_arch_tensors@12; llama_model_orion::build_arch_graph@39; llama_model_orion::graph::graph@43
Dependencies: models.h@1

`third_party/llama.cpp/src/models/paddleocr.cpp` | `d39220bd7781179b74be848993b3bc5a43556c71` | 3495 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_paddleocr::build_arch_graph@3; llm_graph_context@8
Dependencies: models.h@1

`third_party/llama.cpp/src/models/pangu-embed.cpp` | `90f05c088c10755d9eafeb489efe28a95900d311` | 5938 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_pangu_embed::load_arch_hparams@3; llama_model_pangu_embed::load_arch_tensors@13; llama_model_pangu_embed::build_arch_graph@54; llama_model_pangu_embed::graph::graph@58
Dependencies: models.h@1

`third_party/llama.cpp/src/models/phi2.cpp` | `81b1ad12cc02526f264001614f8ccaf0466e33de` | 5461 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_phi2::load_arch_hparams@3; llama_model_phi2::load_arch_tensors@13; llama_model_phi2::build_arch_graph@43; llama_model_phi2::graph::graph@47
Dependencies: models.h@1

`third_party/llama.cpp/src/models/phi3.cpp` | `716ff814cc12601666e9051856d96462b304e0ea` | 7368 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_phi3::load_arch_hparams@3; llama_model_phi3::load_arch_tensors@27; llama_model_phi3::build_arch_graph@59; constexpr@84
Dependencies: models.h@1

`third_party/llama.cpp/src/models/phimoe.cpp` | `c332553bc7d124b926a37dd8d327fdfc5b1b177e` | 2764 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_phimoe::load_arch_hparams@3; llama_model_phimoe::load_arch_tensors@12; llama_model_phimoe::build_arch_graph@48
Dependencies: models.h@1

`third_party/llama.cpp/src/models/plamo.cpp` | `246144519e43fff01c5d569be6083848cad72c28` | 4560 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_plamo::load_arch_hparams@3; llama_model_plamo::load_arch_tensors@12; llama_model_plamo::build_arch_graph@35; llama_model_plamo::graph::graph@39
Dependencies: models.h@1

`third_party/llama.cpp/src/models/plamo2.cpp` | `9f67ca6a39f78cf9ee7c35eeedebf3b293762421` | 19838 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_plamo2::load_arch_hparams@4; llama_model_plamo2::load_arch_tensors@35; llama_model_plamo2::build_arch_graph@106; llm_build_mamba_base@111
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/plamo3.cpp` | `16d0b1dcef71097371474bb1a204a81d3ec9bf2c` | 7986 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_plamo3::load_arch_hparams@3; llama_model_plamo3::load_arch_tensors@22; llama_model_plamo3::build_arch_graph@62; llm_graph_context@72; constexpr@83; constexpr@96
Dependencies: models.h@1

`third_party/llama.cpp/src/models/plm.cpp` | `8ca325f5e2cfd1d6875a6f62e07ba5f7260b229c` | 9119 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_plm::load_arch_hparams@3; llama_model_plm::load_arch_tensors@13; llama_model_plm::build_arch_graph@44; llama_model_plm::graph::graph@48
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen.cpp` | `1f5dff3843cf385b487a5de76da867e5d1e9a3eb` | 4831 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen::load_arch_hparams@3; llama_model_qwen::load_arch_tensors@13; llama_model_qwen::build_arch_graph@39; llama_model_qwen::graph::graph@43
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen2.cpp` | `e9c2ea80a6bec381f2d432357ab00e6c4494ddf6` | 5535 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen2::load_arch_hparams@3; llama_model_qwen2::load_arch_tensors@19; llama_model_qwen2::build_arch_graph@49; llama_model_qwen2::graph::graph@53
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen2moe.cpp` | `e831ed11aad62528d9aaea8f0bf5cf3b472f1308` | 7300 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen2moe::load_arch_hparams@3; llama_model_qwen2moe::load_arch_tensors@16; llama_model_qwen2moe::build_arch_graph@61; llama_model_qwen2moe::graph::graph@65
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen2vl.cpp` | `d79db682cd416997f12dc0e55227e9d9fcd21672` | 5062 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen2vl::load_arch_hparams@3; llama_model_qwen2vl::load_arch_tensors@8; llama_model_qwen2vl::build_arch_graph@38; llama_model_qwen2vl::graph::graph@42
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen3.cpp` | `f4b2a2aebe0f8ce8df355314e5b0429111d25254` | 5872 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen3::load_arch_hparams@3; llama_model_qwen3::load_arch_tensors@15; llama_model_qwen3::build_arch_graph@49; llama_model_qwen3::graph::graph@53
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen35.cpp` | `b05a15d0a4a598d8e5f22d21156e6a576ab1a392` | 28258 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen35::load_arch_hparams@4; llama_model_qwen35::load_arch_tensors@37; llama_model_qwen35::build_arch_graph@129; llm_build_delta_net_base@137; llm_graph_context@487
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/qwen35moe.cpp` | `286adc3ebe69d53ee22a33042e82bc059989cb7c` | 32820 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen35moe::load_arch_hparams@4; llama_model_qwen35moe::load_arch_tensors@40; llama_model_qwen35moe::build_arch_graph@152; llm_build_delta_net_base@160; llm_graph_context@552
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/qwen3moe.cpp` | `6f6df5390e33305ee42c153031a989958bcacf13` | 6603 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen3moe::load_arch_hparams@3; llama_model_qwen3moe::load_arch_tensors@14; llama_model_qwen3moe::build_arch_graph@58; llama_model_qwen3moe::graph::graph@62
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen3next.cpp` | `2c93d1d0b02ae284bf82c0970807fa02aedf4177` | 27365 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen3next::load_arch_hparams@4; llama_model_qwen3next::load_arch_tensors@31; llama_model_qwen3next::build_arch_graph@106; llm_build_delta_net_base@111
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/qwen3vl.cpp` | `724d6140d193655f7b477317c38bccd7ee840078` | 6405 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen3vl::load_arch_hparams@3; llama_model_qwen3vl::load_arch_tensors@16; llama_model_qwen3vl::build_arch_graph@50; llama_model_qwen3vl::graph::graph@54
Dependencies: models.h@1

`third_party/llama.cpp/src/models/qwen3vlmoe.cpp` | `7c41592f772713a80f27495586085bd8767eab30` | 7090 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_qwen3vlmoe::load_arch_hparams@3; llama_model_qwen3vlmoe::load_arch_tensors@16; llama_model_qwen3vlmoe::build_arch_graph@60; llama_model_qwen3vlmoe::graph::graph@64
Dependencies: models.h@1

`third_party/llama.cpp/src/models/refact.cpp` | `a46c358fa68ae45a2e6c9c023422b74abde4be67` | 6546 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_refact::load_arch_hparams@3; llama_model_refact::load_arch_tensors@15; llama_model_refact::build_arch_graph@75; llama_model_refact::graph::graph@79
Dependencies: models.h@1

`third_party/llama.cpp/src/models/rnd1.cpp` | `fc276ce591bfd14a381993fa3088c8b1d31616ac` | 6495 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_rnd1::load_arch_hparams@3; llama_model_rnd1::load_arch_tensors@16; llama_model_rnd1::build_arch_graph@60; llama_model_rnd1::graph::graph@65
Dependencies: models.h@1

`third_party/llama.cpp/src/models/rwkv6-base.cpp` | `bcbde4690415906ac85946bd5dbde2da2fa34ab9` | 8063 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: model@6
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/rwkv6.cpp` | `0b5013dc7585f6beb1e7f1e985e286a5c8dc70ba` | 9800 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_rwkv6::load_arch_hparams@3; llama_model_rwkv6::load_arch_tensors@26; llama_model_rwkv6::build_arch_graph@90; llm_build_rwkv6_base@95
Dependencies: models.h@1

`third_party/llama.cpp/src/models/rwkv6qwen2.cpp` | `6c7db514435e72f794ec07859231df80607e03d1` | 7691 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_rwkv6qwen2::load_arch_hparams@3; llama_model_rwkv6qwen2::load_arch_tensors@26; llama_model_rwkv6qwen2::build_arch_graph@80; llama_model_rwkv6qwen2::graph::graph@84
Dependencies: models.h@1

`third_party/llama.cpp/src/models/rwkv7-base.cpp` | `0616f15e045b1e0173d27e2923a98e09ac856780` | 6912 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: model@6
Dependencies: llama-memory-recurrent.h@1; models.h@2

`third_party/llama.cpp/src/models/rwkv7.cpp` | `67c51f5b59c631ac05480bf9167b736b76e6d899` | 10418 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_rwkv7::load_arch_hparams@3; llama_model_rwkv7::load_arch_tensors@46; llama_model_rwkv7::build_arch_graph@120; llm_build_rwkv7_base@125
Dependencies: models.h@1

`third_party/llama.cpp/src/models/seed-oss.cpp` | `57de881a091f251702879f01342a34e82305822b` | 5306 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_seed_oss::load_arch_hparams@3; llama_model_seed_oss::load_arch_tensors@12; llama_model_seed_oss::build_arch_graph@45; llama_model_seed_oss::graph::graph@49
Dependencies: models.h@1

`third_party/llama.cpp/src/models/smallthinker.cpp` | `a8e3d957f1f0f8ce921c879670359edae91f8a7e` | 7677 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_smallthinker::load_arch_hparams@3; llama_model_smallthinker::load_arch_tensors@32; llama_model_smallthinker::build_arch_graph@68; constexpr@94
Dependencies: models.h@1

`third_party/llama.cpp/src/models/smollm3.cpp` | `c67d967b2040ff6eb34d98eb33241810e881c40d` | 5448 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_smollm3::load_arch_hparams@3; llama_model_smollm3::load_arch_tensors@13; llama_model_smollm3::build_arch_graph@42; llama_model_smollm3::graph::graph@46
Dependencies: models.h@1

`third_party/llama.cpp/src/models/stablelm.cpp` | `bf6087b87960da66787c09fe37114526e7821e4a` | 6378 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_stablelm::load_arch_hparams@3; llama_model_stablelm::load_arch_tensors@14; llama_model_stablelm::build_arch_graph@47; llama_model_stablelm::graph::graph@51
Dependencies: models.h@1

`third_party/llama.cpp/src/models/starcoder.cpp` | `f73a88fd4e9041fa1eb0aa328cd0ddebda1aabac` | 5361 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_starcoder::load_arch_hparams@3; llama_model_starcoder::load_arch_tensors@15; llama_model_starcoder::build_arch_graph@56; llama_model_starcoder::graph::graph@60
Dependencies: models.h@1

`third_party/llama.cpp/src/models/starcoder2.cpp` | `b81b469374a40d489472eaaeedb77eb33a040f71` | 5745 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_starcoder2::load_arch_hparams@3; llama_model_starcoder2::load_arch_tensors@16; llama_model_starcoder2::build_arch_graph@55; llama_model_starcoder2::graph::graph@59
Dependencies: models.h@1

`third_party/llama.cpp/src/models/step35.cpp` | `e2218c5870449c3cf516fcdd566a637321d26c95` | 27555 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_step35::load_arch_hparams@3; llama_model_step35::load_arch_tensors@41; llama_model_step35::build_arch_graph@189; llama_model_step35::graph::graph@196; llm_graph_context@372
Dependencies: models.h@1

`third_party/llama.cpp/src/models/t5.cpp` | `b0e3f062572f63ad5e5a92941ef15b5894c96fcd` | 15012 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_t5::load_arch_hparams@3; llama_model_t5::load_arch_tensors@38; llama_model_t5::build_arch_graph@109
Dependencies: models.h@1

`third_party/llama.cpp/src/models/t5encoder.cpp` | `23c5f9b6a1cad2e822b6cc3c0561dc077dbde361` | 2292 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_t5encoder::load_arch_hparams@3; llama_model_t5encoder::load_arch_tensors@9; llama_model_t5encoder::build_arch_graph@42
Dependencies: models.h@1

`third_party/llama.cpp/src/models/talkie.cpp` | `393e8f65bf4d54618ec19afc4e430873ea1bbb9b` | 5243 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_talkie::load_arch_hparams@3; llama_model_talkie::load_arch_tensors@13; llama_model_talkie::build_arch_graph@36; llama_model_talkie::graph::graph@40
Dependencies: models.h@1

`third_party/llama.cpp/src/models/wavtokenizer-dec.cpp` | `214fed99bad8e2e0ace07700706323bdd85213b1` | 10558 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_wavtokenizer_dec::load_arch_hparams@3; llama_model_wavtokenizer_dec::load_arch_tensors@9; llama_model_wavtokenizer_dec::build_arch_graph@114; llama_model_wavtokenizer_dec::graph::graph@118
Dependencies: models.h@1

`third_party/llama.cpp/src/models/xverse.cpp` | `3135001293a8de7da4d7c5c275fd4cdbd0b6e1c9` | 4732 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: llama_model_xverse::load_arch_hparams@3; llama_model_xverse::load_arch_tensors@14; llama_model_xverse::build_arch_graph@37; llama_model_xverse::graph::graph@41
Dependencies: models.h@1

`third_party/llama.cpp/src/unicode-data.cpp` | `8904adf6a1159510cdb531710169e2c15643d1fe` | 168494 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: unicode-data.h@3; cstdint@5; vector@6; unordered_map@7; unordered_set@8

`third_party/llama.cpp/src/unicode-data.h` | `cafaa0064ea10140e1760cfbef96b6133851b7dc` | 902 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: range_nfd@8
Dependencies: cstdint@3; vector@4; unordered_map@5; unordered_set@6

`third_party/llama.cpp/src/unicode.cpp` | `052d0fa8c670f984eb1724c573828c19a25868d2` | 55494 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: unicode_len_utf8@18; unicode_cpts_to_utf8@24; unicode_cpt_from_utf8@32; unicode_cpt_flags_array@118; unicode_byte_encoding_process@199; unicode_regex_split_custom_gpt2@218; unicode_regex_split_custom_llama3@336; unicode_regex_split_custom_qwen2@477; unicode_regex_split_custom_qwen35@613; unicode_regex_split_stl@742; unicode_regex_split_custom_kimi_k2@780; unicode_regex_split_custom_afmoe@951; unicode_regex_split_custom_newlines@1026; unicode_regex_split_custom@1053; unicode_cpt_to_utf8@1091; unicode_cpts_normalize_nfd@1120; unicode_cpts_from_utf8@1133; unicode_cpt_flags_from_cpt@1150; unicode_cpt_flags_from_utf8@1156; unicode_byte_to_utf8@1165; unicode_utf8_to_byte@1170; unicode_tolower@1175; unicode_cpt_is_han@1187; unicode_regex_split@1219
Dependencies: unicode.h@1; unicode-data.h@2; algorithm@4; cassert@5; cstddef@6; cstdint@7; map@8; regex@9; stdexcept@10; string@11; unordered_map@12; utility@13; vector@14; moz-overrides.h@16

`third_party/llama.cpp/src/unicode.h` | `600ab9216b94dfac172ed771b3e9c1bdb42f5a2c` | 3967 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: unicode_cpt_flags@8; unicode_cpt_flags@41; as_uint@62; category_flag@87
Dependencies: cstdint@3; string@4; vector@5

`third_party/llama.cpp/static-ctors.patch` | `7aa5a9ab6a88501439328d9bb22ee8a4a4a504f8` | 16762 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/moz.build` | `a242f2ae990413dbaf80fb81209b972fc88b1346` | 3576 bytes | imported-path,build-registration | UTF-8 | mode 100644

`third_party/msgpack/LICENSE_1_0.txt` | `36b7cd93cdfbac762f5be4c6ce276df2ea6305c2` | 1338 bytes | imported-path,data-or-other | UTF-8 | mode 100644

`third_party/msgpack/include/msgpack.h` | `af557a5cdb275515e7845f275d7595912d14f3cb` | 526 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/util.h@16; msgpack/object.h@17; msgpack/zone.h@18; msgpack/pack.h@19; msgpack/unpack.h@20; msgpack/sbuffer.h@21; msgpack/vrefbuffer.h@22; msgpack/version.h@23

`third_party/msgpack/include/msgpack.hpp` | `74ae1f6635ad65f53e1ebf5f9a1b397d63dffa5c` | 648 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/object.hpp@10; msgpack/iterator.hpp@11; msgpack/zone.hpp@12; msgpack/pack.hpp@13; msgpack/null_visitor.hpp@14; msgpack/parse.hpp@15; msgpack/unpack.hpp@16; msgpack/x3_parse.hpp@17; msgpack/x3_unpack.hpp@18; msgpack/sbuffer.hpp@19; msgpack/vrefbuffer.hpp@20; msgpack/version.hpp@21; msgpack/type.hpp@22

`third_party/msgpack/include/msgpack/adaptor/adaptor_base.hpp` | `4cf4fd4451eb3fc8c96ab8cae9c42cbec7300345` | 563 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/adaptor_base_decl.hpp@13; msgpack/v1/adaptor/adaptor_base.hpp@15; msgpack/v2/adaptor/adaptor_base.hpp@16; msgpack/v3/adaptor/adaptor_base.hpp@17

`third_party/msgpack/include/msgpack/adaptor/adaptor_base_decl.hpp` | `753cfb91e25caba3819e0b1de306c540244821a3` | 538 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/adaptor_base_decl.hpp@13; msgpack/v2/adaptor/adaptor_base_decl.hpp@14; msgpack/v3/adaptor/adaptor_base_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/array_ref.hpp` | `2a3f61fbfa5a30a341eb6c8d13073ffe8996d9f0` | 493 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/array_ref_decl.hpp@13; msgpack/v1/adaptor/array_ref.hpp@15

`third_party/msgpack/include/msgpack/adaptor/array_ref_decl.hpp` | `43eaa98d71dee545104b8b0da24d3567e7e184fb` | 563 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/array_ref_decl.hpp@13; msgpack/v2/adaptor/array_ref_decl.hpp@14; msgpack/v3/adaptor/array_ref_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/bool.hpp` | `f904fb98f0c164ecb0480c9ac8a16a0b1363698b` | 425 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/bool.hpp@13

`third_party/msgpack/include/msgpack/adaptor/boost/fusion.hpp` | `c6191f139f948b304c9234b776fd78da6f5d7a24` | 429 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/boost/fusion.hpp@13

`third_party/msgpack/include/msgpack/adaptor/boost/msgpack_variant.hpp` | `b20f1ac93885baba84e33788e169685f141f2905` | 587 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/boost/msgpack_variant_decl.hpp@13; msgpack/v1/adaptor/boost/msgpack_variant.hpp@15

`third_party/msgpack/include/msgpack/adaptor/boost/msgpack_variant_decl.hpp` | `ada6c913b3bb2442c7b7d2817b8d61d8430efb47` | 607 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/boost/msgpack_variant_decl.hpp@13; msgpack/v2/adaptor/boost/msgpack_variant_decl.hpp@14; msgpack/v3/adaptor/boost/msgpack_variant_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/boost/optional.hpp` | `e4b53cebf3f588d2c5f6606ca0f0404f9640e845` | 437 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/boost/optional.hpp@13

`third_party/msgpack/include/msgpack/adaptor/boost/string_ref.hpp` | `43bf70f4521cad36e81fa00950d92f8afa8a96fc` | 445 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/boost/string_ref.hpp@13

`third_party/msgpack/include/msgpack/adaptor/boost/string_view.hpp` | `ccf272cf124657e50514ee9157292d57a8448aa6` | 449 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/boost/string_view.hpp@13

`third_party/msgpack/include/msgpack/adaptor/carray.hpp` | `b1caf53d53481aa5e5cd3d322cd4f5d69de77c1b` | 405 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/carray.hpp@13

`third_party/msgpack/include/msgpack/adaptor/char_ptr.hpp` | `71cce6ccf5af5ad243ed9a9db9bcf52393b69fd2` | 413 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/char_ptr.hpp@13

`third_party/msgpack/include/msgpack/adaptor/check_container_size.hpp` | `a464419fc4e2cf23a296e783a9e33d6ae6f37762` | 509 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/check_container_size_decl.hpp@13; msgpack/v1/adaptor/check_container_size.hpp@15

`third_party/msgpack/include/msgpack/adaptor/check_container_size_decl.hpp` | `e61334af73cb43e65ea7fc5ea726748fe22cd719` | 586 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/check_container_size_decl.hpp@13; msgpack/v2/adaptor/check_container_size_decl.hpp@14; msgpack/v3/adaptor/check_container_size_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/cpp11/array.hpp` | `fdc49022f9a918c57e12f27f8c78dea5639091fa` | 426 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/array.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/array_char.hpp` | `8a9bc6dfe7195c73107609cbaebb897a0354c4cd` | 446 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/array_char.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/array_unsigned_char.hpp` | `0860a88af516eba6a810a81475b588ff68413f89` | 482 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/array_unsigned_char.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/chrono.hpp` | `48d93974573ca21c041c67ce002b632e0661793f` | 430 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/chrono.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/forward_list.hpp` | `27ac9c0d1fa3f6375d785cdaa17dbb0b888deed2` | 454 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/forward_list.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/reference_wrapper.hpp` | `6b09429c5e1d634b41bdf541ab76653377074af7` | 474 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/reference_wrapper.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/shared_ptr.hpp` | `2199a499d08d8f79e924b762b77e5553d39c3334` | 446 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/shared_ptr.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/tuple.hpp` | `b833c2a26ba7246db3319826408a1215ba8f8213` | 426 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/tuple.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/unique_ptr.hpp` | `ef1001283e6dcd21a3ca6556b5386ccb818ecbfd` | 446 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/unique_ptr.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/unordered_map.hpp` | `dadbf2e2558c2844410e1925bafc0e29d3614d70` | 458 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/unordered_map.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp11/unordered_set.hpp` | `f2e58621109df5b6f11a5c3d809eb77952983781` | 458 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp11/unordered_set.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp17/byte.hpp` | `eebaa9603037eb71f44ebbf4ea8ca221df2cc440` | 422 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp17/byte.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp17/carray_byte.hpp` | `c41bccac7748d095977ba2cf73d4251a5c51c3b3` | 450 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp17/carray_byte.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp17/optional.hpp` | `5df17d9f491fa359a81ce36cd974bbe664d751eb` | 438 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp17/optional.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp17/string_view.hpp` | `3f77e1bb1587fde4d2786415e84b4cbb7dff5688` | 450 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp17/string_view.hpp@14

`third_party/msgpack/include/msgpack/adaptor/cpp17/vector_byte.hpp` | `8c5e6230a91274a746733a89818d3aac2a4f5290` | 450 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/cpp17/vector_byte.hpp@14

`third_party/msgpack/include/msgpack/adaptor/define.hpp` | `1599100824474e4f96ce359483fcf4c9ee29f0e2` | 462 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/define_decl.hpp@13; msgpack/v1/adaptor/define.hpp@15

`third_party/msgpack/include/msgpack/adaptor/define_decl.hpp` | `1880a8616500b3ed5eed4f5c6062b06eb0c3f72b` | 5109 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: msgpack@90; MSGPACK_API_VERSION_NAMESPACE@92; adaptor@94; convert@96; object@105; operator@106; object_with_zone@112; operator@113; pack@119; operator@121
Dependencies: msgpack/preprocessor.hpp@21; msgpack/versioning.hpp@23; msgpack/adaptor/int.hpp@26; msgpack/v1/adaptor/define_decl.hpp@140; msgpack/v2/adaptor/define_decl.hpp@141; msgpack/v3/adaptor/define_decl.hpp@142

`third_party/msgpack/include/msgpack/adaptor/deque.hpp` | `dfb61b6bffd0d6aff99e96d04b27588c4f951756` | 401 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/deque.hpp@13

`third_party/msgpack/include/msgpack/adaptor/ext.hpp` | `37658dc9d694c3a82ac09d36b066148f322583a8` | 435 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/ext_decl.hpp@13; msgpack/v1/adaptor/ext.hpp@15

`third_party/msgpack/include/msgpack/adaptor/ext_decl.hpp` | `7da30427be4aa6ed8193ff3df5ba051b375af9ca` | 499 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/ext_decl.hpp@13; msgpack/v2/adaptor/ext_decl.hpp@14; msgpack/v3/adaptor/ext_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/fixint.hpp` | `1c49116e27b6129275a581d06b88ffb237c8e12f` | 472 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/fixint_decl.hpp@13; msgpack/v1/adaptor/fixint.hpp@15

`third_party/msgpack/include/msgpack/adaptor/fixint_decl.hpp` | `3e73ded258973f0ec64b6a03e24bafe23ff580e5` | 540 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/fixint_decl.hpp@13; msgpack/v2/adaptor/fixint_decl.hpp@14; msgpack/v3/adaptor/fixint_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/float.hpp` | `5683c96d5c5b160810e56629b43553acd7a4992d` | 401 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/float.hpp@13

`third_party/msgpack/include/msgpack/adaptor/int.hpp` | `e2213e7e364ef9c767b9f5554811b522b8987b60` | 434 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/int_decl.hpp@13; msgpack/v1/adaptor/int.hpp@15

`third_party/msgpack/include/msgpack/adaptor/int_decl.hpp` | `f68ef8bc05125c680be91db5e02ef3424e9f1bde` | 499 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/int_decl.hpp@13; msgpack/v2/adaptor/int_decl.hpp@14; msgpack/v3/adaptor/int_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/list.hpp` | `8761da3a9c8d03e9220a2867687018ae1bfa4765` | 397 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/list.hpp@13

`third_party/msgpack/include/msgpack/adaptor/map.hpp` | `7f0e22e22bb6aa25273ed9790f1a12669664d320` | 463 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/map_decl.hpp@13; msgpack/v1/adaptor/map.hpp@15

`third_party/msgpack/include/msgpack/adaptor/map_decl.hpp` | `757688ec4f7de247ac93a2d1bc107ea2247e4a18` | 527 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/map_decl.hpp@13; msgpack/v2/adaptor/map_decl.hpp@14; msgpack/v3/adaptor/map_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/msgpack_tuple.hpp` | `a63927761453126a6f2e1214adbbe5bbed626c88` | 497 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/msgpack_tuple_decl.hpp@13; msgpack/v1/adaptor/msgpack_tuple.hpp@15

`third_party/msgpack/include/msgpack/adaptor/msgpack_tuple_decl.hpp` | `0c70b22654d6acbc7b7e33f5b91e917fce57ebab` | 544 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/msgpack_tuple_decl.hpp@13; msgpack/v2/adaptor/msgpack_tuple_decl.hpp@14; msgpack/v3/adaptor/msgpack_tuple_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/nil.hpp` | `92f308125dcfb656e4c9f07824a7f10922f32883` | 462 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/nil_decl.hpp@13; msgpack/v1/adaptor/nil.hpp@15

`third_party/msgpack/include/msgpack/adaptor/nil_decl.hpp` | `d45f45bb9f95b625b647aceae90e1d06b7d61bac` | 499 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/nil_decl.hpp@13; msgpack/v2/adaptor/nil_decl.hpp@14; msgpack/v3/adaptor/nil_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/pair.hpp` | `0956aa9a6639855b9797f3bfde8e7d2653aefb7d` | 397 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/pair.hpp@13

`third_party/msgpack/include/msgpack/adaptor/raw.hpp` | `f85f882cca678ed6e93e3f96141f4a48087c77ae` | 462 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/raw_decl.hpp@13; msgpack/v1/adaptor/raw.hpp@15

`third_party/msgpack/include/msgpack/adaptor/raw_decl.hpp` | `60777bddcc1ed19b5d04c79cd00c5ec28f6a060d` | 499 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/raw_decl.hpp@13; msgpack/v2/adaptor/raw_decl.hpp@14; msgpack/v3/adaptor/raw_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/set.hpp` | `fbf820aba976a909deae87239f238bb01b9c02db` | 393 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/set.hpp@13

`third_party/msgpack/include/msgpack/adaptor/size_equal_only.hpp` | `de9d24731232a079e59e68bf079c97bb560e7bd2` | 495 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/size_equal_only_decl.hpp@13; msgpack/v1/adaptor/size_equal_only.hpp@15

`third_party/msgpack/include/msgpack/adaptor/size_equal_only_decl.hpp` | `d3e5dcf7591a6d9de3c321a018dc16b3a0f49992` | 571 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/size_equal_only_decl.hpp@13; msgpack/v2/adaptor/size_equal_only_decl.hpp@14; msgpack/v3/adaptor/size_equal_only_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/string.hpp` | `8e3182548a8334d7b0327559bc4f7d43c160b056` | 405 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/string.hpp@13

`third_party/msgpack/include/msgpack/adaptor/tr1/unordered_map.hpp` | `9c8190e855c11624c2fe13d10c4992c8c19f4cf8` | 6435 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: msgpack@38; MSGPACK_API_VERSION_NAMESPACE@41; adaptor@44; convert@47; pack@64; operator@66; object_with_zone@79; operator@80; convert@103; pack@121; operator@123; object_with_zone@136; operator@137
Dependencies: msgpack/versioning.hpp@13; msgpack/adaptor/adaptor_base.hpp@14; msgpack/adaptor/check_container_size.hpp@15; unordered_map@20; tr1/unordered_map@29

`third_party/msgpack/include/msgpack/adaptor/tr1/unordered_set.hpp` | `dd6c0448fc631e1907fa49c41f275e46113033a4` | 6023 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: msgpack@38; MSGPACK_API_VERSION_NAMESPACE@41; adaptor@44; convert@47; pack@63; operator@65; object_with_zone@77; operator@78; convert@101; pack@117; operator@119; object_with_zone@131; operator@132
Dependencies: msgpack/versioning.hpp@13; msgpack/adaptor/adaptor_base.hpp@14; msgpack/adaptor/check_container_size.hpp@15; unordered_set@20; tr1/unordered_set@29

`third_party/msgpack/include/msgpack/adaptor/v4raw.hpp` | `52c0de37eebd39807f0eadf40b6347704ec37636` | 472 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/adaptor/v4raw_decl.hpp@13; msgpack/v1/adaptor/v4raw.hpp@15

`third_party/msgpack/include/msgpack/adaptor/v4raw_decl.hpp` | `989351832299462323e0f5981101a2634760361e` | 511 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/v4raw_decl.hpp@13; msgpack/v2/adaptor/v4raw_decl.hpp@14; msgpack/v3/adaptor/v4raw_decl.hpp@15

`third_party/msgpack/include/msgpack/adaptor/vector.hpp` | `5eb6caca016f727d9bd151ffcfc6c7838a3d2f19` | 405 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/vector.hpp@13

`third_party/msgpack/include/msgpack/adaptor/vector_bool.hpp` | `f259ac9b82ad8659abc02bb835975e972add0acd` | 425 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/vector_bool.hpp@13

`third_party/msgpack/include/msgpack/adaptor/vector_char.hpp` | `d196efa4d90a765d34dee389b23e20a794085cdc` | 425 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/vector_char.hpp@13

`third_party/msgpack/include/msgpack/adaptor/vector_unsigned_char.hpp` | `e71e0d369a1818e61610a6a96ae84274aeb17d3c` | 461 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/adaptor/vector_unsigned_char.hpp@13

`third_party/msgpack/include/msgpack/cpp_config.hpp` | `0b36d7ef086404ebce2311ea9f10231259842b94` | 440 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/cpp_config_decl.hpp@13; msgpack/v1/cpp_config.hpp@15

`third_party/msgpack/include/msgpack/cpp_config_decl.hpp` | `332e2a81f3890a31d8cd1eec220363eab560118b` | 499 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/cpp_config_decl.hpp@13; msgpack/v2/cpp_config_decl.hpp@14; msgpack/v3/cpp_config_decl.hpp@15

`third_party/msgpack/include/msgpack/create_object_visitor.hpp` | `40d69974a78924a33b1ae27bb751fc3d97544400` | 489 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/create_object_visitor_decl.hpp@13; msgpack/v2/create_object_visitor.hpp@15

`third_party/msgpack/include/msgpack/create_object_visitor_decl.hpp` | `56e81e1bbeca62ba4458540f87354d4b6812d690` | 511 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v2/create_object_visitor_decl.hpp@13; msgpack/v3/create_object_visitor_decl.hpp@14

`third_party/msgpack/include/msgpack/fbuffer.h` | `d766c839e62da7dc11437c357ffce2acfa7e663e` | 679 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: msgpack_fbuffer_write@26
Dependencies: stdio.h@13

`third_party/msgpack/include/msgpack/fbuffer.hpp` | `6d51cd541d58c43f319956bec78dccf22eaca108` | 419 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/fbuffer_decl.hpp@13; msgpack/v1/fbuffer.hpp@15

`third_party/msgpack/include/msgpack/fbuffer_decl.hpp` | `d1a5a6a52fc3739e9bb56dac27b23b4165a87aba` | 479 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/fbuffer_decl.hpp@13; msgpack/v2/fbuffer_decl.hpp@14; msgpack/v3/fbuffer_decl.hpp@15

`third_party/msgpack/include/msgpack/gcc_atomic.h` | `6b1b1a799654fd4ecc975617bac56ff51488b60e` | 537 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: int@14

`third_party/msgpack/include/msgpack/gcc_atomic.hpp` | `9656e5331bc9105e330a535c390d8e71e9c37a27` | 822 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: _msgpack_sync_decr_and_fetch@19; _msgpack_sync_incr_and_fetch@24
Dependencies: msgpack/gcc_atomic.h@16; bits/atomicity.h@17

`third_party/msgpack/include/msgpack/iterator.hpp` | `a118b59257074d248ed885fe92e5e360e247a640` | 432 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/iterator_decl.hpp@14; msgpack/v1/iterator.hpp@16

`third_party/msgpack/include/msgpack/iterator_decl.hpp` | `5bf28cb10ee7447138f1fd0662a98b26aab8ce4a` | 491 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/iterator_decl.hpp@14; msgpack/v2/iterator_decl.hpp@15; msgpack/v3/iterator_decl.hpp@16

`third_party/msgpack/include/msgpack/meta.hpp` | `7062cc55158505ea488158a0a454f15172dff105` | 414 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/meta_decl.hpp@14; msgpack/v1/meta.hpp@16

`third_party/msgpack/include/msgpack/meta_decl.hpp` | `54380f8c836964d0510937e05938b3ea901d20cf` | 472 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/meta_decl.hpp@14; msgpack/v2/meta_decl.hpp@15; msgpack/v3/meta_decl.hpp@16

`third_party/msgpack/include/msgpack/null_visitor.hpp` | `523d0dd19227f9ca5c37f3a4ff215b30a930a7d3` | 444 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/null_visitor_decl.hpp@13; msgpack/v2/null_visitor.hpp@15

`third_party/msgpack/include/msgpack/null_visitor_decl.hpp` | `b398ed245eb195ef9a465adcba860999646d88ed` | 466 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v2/null_visitor_decl.hpp@13; msgpack/v3/null_visitor_decl.hpp@14

`third_party/msgpack/include/msgpack/object.h` | `0da280f560f0830167e1b39c0f238ef74118db59` | 2707 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: enum@27; msgpack_object@46; msgpack_object_kv@47; struct@49; msgpack_object@51; struct@54; msgpack_object_kv@56; struct@59; struct@64; struct@69; union@75; struct@90; struct@95
Dependencies: zone.h@13; stdio.h@14

`third_party/msgpack/include/msgpack/object.hpp` | `32799926661e1a0d1f773e68551e03a2bddb5a15` | 479 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/object_decl.hpp@13; msgpack/v1/object.hpp@15; msgpack/v2/object.hpp@16

`third_party/msgpack/include/msgpack/object_decl.hpp` | `7aab1288da2b99834e75f2afe70bd561dc383642` | 479 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/object_decl.hpp@14; msgpack/v2/object_decl.hpp@15; msgpack/v3/object_decl.hpp@16

`third_party/msgpack/include/msgpack/object_fwd.hpp` | `515df9dc6cfe69c70914b9b1f4e8638b329b8ac0` | 541 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/object_fwd_decl.hpp@14; msgpack/v1/object_fwd.hpp@16; msgpack/v2/object_fwd.hpp@17; msgpack/v3/object_fwd.hpp@18

`third_party/msgpack/include/msgpack/object_fwd_decl.hpp` | `c933c34516acb287743d88b983ea4147616d9372` | 503 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/object_fwd_decl.hpp@14; msgpack/v2/object_fwd_decl.hpp@15; msgpack/v3/object_fwd_decl.hpp@16

`third_party/msgpack/include/msgpack/pack.h` | `f2dddb3c5fb215e92c6817a54eed248cb6aad6e4` | 4929 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: int@36; struct@38; msgpack_packer_init@127; msgpack_packer_new@133; msgpack_packer_free@141
Dependencies: pack_define.h@13; object.h@14; timestamp.h@15; stdlib.h@16; pack_template.h@125

`third_party/msgpack/include/msgpack/pack.hpp` | `518b457848a1395b780d9466c2fa8053014f4d52` | 430 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/pack_decl.hpp@13; msgpack/v1/pack.hpp@15

`third_party/msgpack/include/msgpack/pack_decl.hpp` | `5aaec94a859a23a3d2e64cd08a86d82f2d322504` | 460 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/pack_decl.hpp@13; msgpack/v2/pack_decl.hpp@14; msgpack/v3/pack_decl.hpp@15

`third_party/msgpack/include/msgpack/pack_define.h` | `ce98b67558a3bb053d7ec5ca1098e16b255b75cc` | 432 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/sysdep.h@13; limits.h@14; string.h@15

`third_party/msgpack/include/msgpack/pack_template.h` | `5e2313cb2d1992f951e99ea94906b148d47ba04d` | 24466 bytes | imported-path,source | UTF-8 | mode 100644
Declarations: msgpack_pack_inline_func_fixint@271; msgpack_pack_inline_func_fixint@277; msgpack_pack_inline_func_fixint@284; msgpack_pack_inline_func_fixint@291; msgpack_pack_inline_func_fixint@298; msgpack_pack_inline_func_fixint@304; msgpack_pack_inline_func_fixint@311; msgpack_pack_inline_func_fixint@318; msgpack_pack_inline_func@329; msgpack_pack_inline_func@334; msgpack_pack_inline_func@339; msgpack_pack_inline_func@344; msgpack_pack_inline_func@349; msgpack_pack_inline_func@354; msgpack_pack_inline_func@359; msgpack_pack_inline_func@364; msgpack_pack_inline_func@369; msgpack_pack_inline_func@382; msgpack_pack_inline_func@387; msgpack_pack_inline_func_cint@394; msgpack_pack_inline_func_cint@425; msgpack_pack_inline_func_cint@456; msgpack_pack_inline_func_cint@487; msgpack_pack_inline_func_cint@518; msgpack_pack_inline_func_cint@549; msgpack_pack_inline_func_cint@580; msgpack_pack_inline_func_cint@611; msgpack_pack_inline_func@651; msgpack_pack_inline_func@660; msgpack_pack_inline_func@681; msgpack_pack_inline_func@692; msgpack_pack_inline_func@698; msgpack_pack_inline_func@709; msgpack_pack_inline_func@730; msgpack_pack_inline_func@751; msgpack_pack_inline_func@771; msgpack_pack_inline_func@780; msgpack_pack_inline_func@796; msgpack_pack_inline_func@805; msgpack_pack_inline_func@822; msgpack_pack_inline_func@831; msgpack_pack_inline_func@888; msgpack_pack_inline_func@893

`third_party/msgpack/include/msgpack/parse.hpp` | `90e140276fce633574e58bcb54d268e128b3e34c` | 441 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/parse_decl.hpp@13; msgpack/v2/parse.hpp@15; msgpack/v3/parse.hpp@16

`third_party/msgpack/include/msgpack/parse_decl.hpp` | `381aa1a4ffdec68217ff675d2321659fcf16881e` | 431 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v2/parse_decl.hpp@13; msgpack/v3/parse_decl.hpp@14

`third_party/msgpack/include/msgpack/parse_return.hpp` | `c06d1891ad6898817cf1fca443f9e23943f0d5cf` | 480 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/v1/parse_return.hpp@13; msgpack/v2/parse_return.hpp@14; msgpack/v3/parse_return.hpp@15

`third_party/msgpack/include/msgpack/predef.h` | `0f8d5f589582ab838d25393424bc2987f2e3c663` | 661 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/language.h@13; msgpack/predef/architecture.h@14; msgpack/predef/compiler.h@15; msgpack/predef/library.h@16; msgpack/predef/os.h@17; msgpack/predef/other.h@18; msgpack/predef/platform.h@19; msgpack/predef/hardware.h@20; msgpack/predef/version.h@22

`third_party/msgpack/include/msgpack/predef/architecture.h` | `63879a032fa4c69ce50b8278e75a6ef433244d7f` | 1214 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/architecture/alpha.h@13; msgpack/predef/architecture/arm.h@14; msgpack/predef/architecture/blackfin.h@15; msgpack/predef/architecture/convex.h@16; msgpack/predef/architecture/ia64.h@17; msgpack/predef/architecture/m68k.h@18; msgpack/predef/architecture/mips.h@19; msgpack/predef/architecture/parisc.h@20; msgpack/predef/architecture/ppc.h@21; msgpack/predef/architecture/pyramid.h@22; msgpack/predef/architecture/rs6k.h@23; msgpack/predef/architecture/sparc.h@24; msgpack/predef/architecture/superh.h@25; msgpack/predef/architecture/sys370.h@26; msgpack/predef/architecture/sys390.h@27; msgpack/predef/architecture/x86.h@28; msgpack/predef/architecture/z.h@29

`third_party/msgpack/include/msgpack/predef/architecture/alpha.h` | `e1a39d0e13198251c7d750b786960b01f7d87a70` | 1672 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@58

`third_party/msgpack/include/msgpack/predef/architecture/arm.h` | `c37f2d13064f6fb0553e763000735d78f4ed8323` | 2126 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@13; msgpack/predef/make.h@14; msgpack/predef/detail/test.h@69

`third_party/msgpack/include/msgpack/predef/architecture/blackfin.h` | `c3e580d87e502a3b7269c94dd0a425d564022fb8` | 1172 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@45

`third_party/msgpack/include/msgpack/predef/architecture/convex.h` | `6509ffd2a45ce12a33b2ce9d0023da6e1aad3d2a` | 1927 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@64

`third_party/msgpack/include/msgpack/predef/architecture/ia64.h` | `f6a0da03df7df9a9397bea873b8b0451f8784589` | 1305 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@48

`third_party/msgpack/include/msgpack/predef/architecture/m68k.h` | `0112a47358ef76d5b38bc01ee4d117d624285efd` | 2648 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@81

`third_party/msgpack/include/msgpack/predef/architecture/mips.h` | `c83021a6583034f338b8959a7235486606aba16c` | 2260 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@72

`third_party/msgpack/include/msgpack/predef/architecture/parisc.h` | `bbd8aa162429a10dfc970b4a02495d53ea5e593f` | 1944 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@63

`third_party/msgpack/include/msgpack/predef/architecture/ppc.h` | `29cad9298bef752d7673a7d68d2237a1e75c6150` | 2199 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@71

`third_party/msgpack/include/msgpack/predef/architecture/pyramid.h` | `5799d831b03fd66e30c972c1bb3204656e34393f` | 962 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@41

`third_party/msgpack/include/msgpack/predef/architecture/rs6k.h` | `241876059eb728590c94e92e1a1fa9e0dcb55eb7` | 1426 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@55

`third_party/msgpack/include/msgpack/predef/architecture/sparc.h` | `4cb764e59db1e3ba6cee08e1cb36223c5bb7a769` | 1408 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@53

`third_party/msgpack/include/msgpack/predef/architecture/superh.h` | `8256d2b8b7253292bea930bbcf173541b59960bb` | 1859 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@66

`third_party/msgpack/include/msgpack/predef/architecture/sys370.h` | `a03b6911379c5b2387e826148e1e35ab66ebf78e` | 1067 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@42

`third_party/msgpack/include/msgpack/predef/architecture/sys390.h` | `20fbb1d3493e65c71d61ff5208faf1ffd1a60da0` | 1065 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@42

`third_party/msgpack/include/msgpack/predef/architecture/x86.h` | `02353b15d8450176d31e2b6ef79f92b479527765` | 1002 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/architecture/x86/32.h@8; msgpack/predef/architecture/x86/64.h@9; msgpack/predef/detail/test.h@37

`third_party/msgpack/include/msgpack/predef/architecture/x86/32.h` | `82cff0195e8eb39f7b21c68ed794e2b0d99909e4` | 2768 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/architecture/x86.h@82; msgpack/predef/detail/test.h@86

`third_party/msgpack/include/msgpack/predef/architecture/x86/64.h` | `72a05c26b2fc15befffb65dbaed9be570de39bc9` | 1307 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/architecture/x86.h@45; msgpack/predef/detail/test.h@49

`third_party/msgpack/include/msgpack/predef/architecture/z.h` | `f5e9f859ca0c8e9f9efeea118586ab71bf764c0e` | 969 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/test.h@41

`third_party/msgpack/include/msgpack/predef/compiler.h` | `56058166744f6c5786bb9017366004117382202f` | 1634 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/compiler/borland.h@13; msgpack/predef/compiler/clang.h@14; msgpack/predef/compiler/comeau.h@15; msgpack/predef/compiler/compaq.h@16; msgpack/predef/compiler/diab.h@17; msgpack/predef/compiler/digitalmars.h@18; msgpack/predef/compiler/dignus.h@19; msgpack/predef/compiler/edg.h@20; msgpack/predef/compiler/ekopath.h@21; msgpack/predef/compiler/gcc_xml.h@22; msgpack/predef/compiler/gcc.h@23; msgpack/predef/compiler/greenhills.h@24; msgpack/predef/compiler/hp_acc.h@25; msgpack/predef/compiler/iar.h@26; msgpack/predef/compiler/ibm.h@27; msgpack/predef/compiler/intel.h@28; msgpack/predef/compiler/kai.h@29; msgpack/predef/compiler/llvm.h@30; msgpack/predef/compiler/metaware.h@31; msgpack/predef/compiler/metrowerks.h@32; msgpack/predef/compiler/microtec.h@33; msgpack/predef/compiler/mpw.h@34; msgpack/predef/compiler/palm.h@35; msgpack/predef/compiler/pgi.h@36; msgpack/predef/compiler/sgi_mipspro.h@37; msgpack/predef/compiler/sunpro.h@38; msgpack/predef/compiler/tendra.h@39; msgpack/predef/compiler/visualc.h@40; msgpack/predef/compiler/watcom.h@41

`third_party/msgpack/include/msgpack/predef/compiler/borland.h` | `89e0d9f2ceb484f1b2d3242aaf6aa77b8236bb37` | 1917 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@50; msgpack/predef/detail/test.h@57; msgpack/predef/detail/test.h@61

`third_party/msgpack/include/msgpack/predef/compiler/clang.h` | `93616cf53fe47bf11ccde04ef885f0f09136b936` | 1588 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/comeau.h` | `f944bca863d5a3d647a5a4a85e19020b5811059a` | 1738 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@48; msgpack/predef/detail/test.h@55; msgpack/predef/detail/test.h@59

`third_party/msgpack/include/msgpack/predef/compiler/compaq.h` | `b2771a73c8ea502f8d5542d763c71588b3cfe03b` | 1980 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@53; msgpack/predef/detail/test.h@60; msgpack/predef/detail/test.h@64

`third_party/msgpack/include/msgpack/predef/compiler/diab.h` | `a365a35c52b72ff94d1d6a0d4552874c4752a465` | 1545 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/digitalmars.h` | `eca2a3123ecd6824b577c250e7f1c64723a68226` | 1493 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/dignus.h` | `8040baa9b444977cefc8c39f04b44fb68687ba6c` | 1511 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/edg.h` | `700f8bdc4dc6e945ec1b90873786804231983d87` | 1508 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/ekopath.h` | `72fda2723b77739266b0fcb5afc8deca93a02e0b` | 1590 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@44; msgpack/predef/detail/test.h@51; msgpack/predef/detail/test.h@55

`third_party/msgpack/include/msgpack/predef/compiler/gcc.h` | `03fcd2a7848b194d01d8af6d1c876ab05447ae7c` | 2025 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/compiler/clang.h@13; msgpack/predef/version_number.h@15; msgpack/predef/make.h@16; msgpack/predef/detail/comp_detected.h@55; msgpack/predef/detail/test.h@62; msgpack/predef/detail/test.h@66

`third_party/msgpack/include/msgpack/predef/compiler/gcc_xml.h` | `678cf71c7651f131bf2d2290489102dfb1e4091b` | 1427 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@40; msgpack/predef/detail/test.h@47; msgpack/predef/detail/test.h@51

`third_party/msgpack/include/msgpack/predef/compiler/greenhills.h` | `f99784367339fb69397a2b9dbf2153e8159fbb13` | 1990 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@53; msgpack/predef/detail/test.h@60; msgpack/predef/detail/test.h@64

`third_party/msgpack/include/msgpack/predef/compiler/hp_acc.h` | `5a47ae4df9601c90a83e56ccd9c7838324c699b6` | 1678 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@48; msgpack/predef/detail/test.h@55; msgpack/predef/detail/test.h@59

`third_party/msgpack/include/msgpack/predef/compiler/iar.h` | `2cce96003cc7a1be3c4bf8740e020851e7f2970e` | 1451 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/ibm.h` | `fc4ecfae03a37d9aef9cb25f77cb5924bf669cba` | 2233 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@59; msgpack/predef/detail/test.h@66; msgpack/predef/detail/test.h@70

`third_party/msgpack/include/msgpack/predef/compiler/intel.h` | `7a1d76efeeb4ecc72ec00443864eaa42ffcb0a46` | 1947 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@52; msgpack/predef/detail/test.h@59; msgpack/predef/detail/test.h@63

`third_party/msgpack/include/msgpack/predef/compiler/kai.h` | `232d54d5f0b3d4e0598dee0d818e956c6efcb59e` | 1431 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/version_number.h@11; msgpack/predef/make.h@12; msgpack/predef/detail/comp_detected.h@43; msgpack/predef/detail/test.h@50; msgpack/predef/detail/test.h@54

`third_party/msgpack/include/msgpack/predef/compiler/llvm.h` | `873d3087316b7bc8cd427f97f4f5ecf51f2e6ffe` | 1506 bytes | imported-path,source | UTF-8 | mode 100644
Dependencies: msgpack/predef/compiler/clang.h@13; msgpack/predef/version_number.h@15; msgpack/predef/make.h@16; msgpack/predef/detail/comp_detected.h@44; msgpack/predef/detail/test.h@51; msgpack/predef/detail/test.h@55

## Validation and limits

Every listed blob was read from the pinned Git tree and its Git SHA-1 was recomputed. Extraction is structural only. Read implementations, callers, build conditions, and tests before making a behavior claim. Runtime behavior and historical reasons remain unverified. Reproduce a file with `git show 1a097ed8d31f6b307a5d0ebc34a82ceaf7f3727b:path` in the corresponding source clone. The full study coverage and navigation note records aggregate results.
