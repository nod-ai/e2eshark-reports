## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.285470169658463 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.46720742473068 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.78711427251497 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.4534831918362 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 364.12786529399455 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.318367696722451 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.43492046461023 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.17649043830378 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 146.11365816866356 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.61655249606287 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.34518371823998 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 606.2480024217317 | |
| migraphx_ORT__distilgpt2_1 | PASS | 51.41547687041262 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.34847787237076 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 293.3281083436062 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.220428807886705 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.409065387376865 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.0660774945927045 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.46339161625062 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.72708389887379 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.90288817474527 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.332865969668473 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.12198464386165 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.424105652297534 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 103.47470996849653 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.34563018864502 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 62.72784847605192 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.322706542229689 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.426291618772122 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.6109141412945 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.230432794318071 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.724045422160998 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.01017492823303 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.24631801309685 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.6861221672346 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.264263519953909 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.747949071538944 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.119099598330184 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.281069140349114 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.809941369522775 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.533035612199455 | |
