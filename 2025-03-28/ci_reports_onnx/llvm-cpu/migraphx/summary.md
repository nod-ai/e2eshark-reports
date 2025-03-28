## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.3758380576977016 | |
| migraphx_bert__bert-large-uncased | PASS | 380.5730100721121 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 218.53882788370052 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5463.672279069821 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 344.67466299732524 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5040.459897369146 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.3572864631812 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 607.1644276380539 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.82278849539301 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.37193930905962 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.4320965806643 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.2618671485356 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.63557436494598 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 500.66557712852955 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.14753745992978 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.97603083277743 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 256.3651980211337 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 50.5912716810902 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 60.58316708852848 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.22750796732448 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1494.9423459668953 | |
| migraphx_torchvision__inceptioni1 | PASS | 223.62600970599385 | |
| migraphx_torchvision__inceptioni32 | PASS | 5811.833032717307 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.78505027294159 | |
| migraphx_torchvision__resnet50i64 | PASS | 5422.515028466781 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1526.8870232005913 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3085.79903592666 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4922.144754479328 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 216.78952841709057 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 269.0802477300167 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 378.753046815594 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 284.7260414726204 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 429.4487095127503 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 744.3881755073866 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 3113.406249632438 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5789.908482382695 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9100.88674724102 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 505.2133575081825 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 833.0172399679819 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1249.9110102653503 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 740.7254067560037 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1584.995198994875 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2561.7256313562393 | |
