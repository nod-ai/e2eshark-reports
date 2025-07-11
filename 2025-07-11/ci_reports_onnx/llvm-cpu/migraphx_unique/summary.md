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
| migraphx_bert__bert-large-uncased | PASS | 368.97722926611704 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.35164370139438 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5358.025041098396 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 390.1018107620378 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 516.6129769446949 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 477.6104673122366 | |
| migraphx_mlperf__resnet50_v1 | PASS | 82.48711540363729 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.60844688241681 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 217.86597712586322 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 57.19843336070577 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.21074122431524 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1511.298197011153 | |
| migraphx_torchvision__inceptioni1 | PASS | 226.04842753046088 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.06710095672558 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1538.9551622793078 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5273.438808508217 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9551.518015253047 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.42305612812436 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 412.2827939378719 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 355.4565665932993 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.20932023227215 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.11497985571623 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 665.3161489715178 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5921.7881970107555 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13799.548421055079 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23141.770213842392 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 405.0598052951197 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 974.0820107981563 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1218.6513946702082 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 741.0791789491972 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1637.9833143825333 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3414.235543149213 | |
