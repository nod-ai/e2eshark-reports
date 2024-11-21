## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 384.36650453756255 | |
| migraphx_bert__bertsquad-12 | PASS | 90.28925436238445 | |
| migraphx_cadene__dpn92i1 | PASS | 179.5863445020384 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6798.98042914768 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 335.81056259572506 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 447.32702523469925 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 484.5266869912545 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.03326311707497 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.61983509248856 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.94824721912542 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.24886406647663 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.05156042746133 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 283.12305578341085 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.805635428617865 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.03845524622334 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 253.52996277312434 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 58.08263878319778 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.75186053967033 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.59001236843566 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1326.3217229396105 | |
| migraphx_torchvision__inceptioni1 | PASS | 236.1918460163805 | |
| migraphx_torchvision__inceptioni32 | PASS | 6608.937112614512 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.33796624484516 | |
| migraphx_torchvision__resnet50i64 | PASS | 6100.310257946451 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2559.2035334557295 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4056.543222938975 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6011.246712878346 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 169.05358516507678 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 274.2719839637478 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 394.7380244111021 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 395.0192689274748 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 649.3724764635165 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 978.3330236872038 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5242.666264375051 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8985.549971461296 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12320.326822499434 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 737.4805708726248 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1198.6713235576947 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1770.8801844467719 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1779.0931692967813 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2325.734918316205 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3034.202483172218 | |
