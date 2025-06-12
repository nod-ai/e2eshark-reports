## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 368.80982814667124 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.4351819694663 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5441.817900010695 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.8563016485423 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.7210083293418 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.4292474662264 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.69397175638005 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.16240072319352 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.1808646519979 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 61.961103476480474 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.411195199626185 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1531.5741064647834 | |
| migraphx_torchvision__inceptioni1 | PASS | 206.35486960721514 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.23645778692192 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1528.1123504973948 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5550.576757484426 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9616.543451944986 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 145.6971979700029 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.14364649645154 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 416.2654018340011 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 248.87632138820155 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 433.4455587280293 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 657.9364648399253 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5202.0691315022605 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13648.415219814828 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23946.203963210184 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 429.2202678819497 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1039.099811731527 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1225.9667647692063 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1227.8512901005645 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1704.5229198411107 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3467.7494447678328 | |
