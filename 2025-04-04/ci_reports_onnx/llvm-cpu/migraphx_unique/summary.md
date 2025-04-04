## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 370.418772722284 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.40857108682394 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5728.011557211478 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.9641971538464 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.97569285333157 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 487.31191953023273 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.50200367257708 | |
| migraphx_models__whisper-tiny-decoder | PASS | 1047.3331461350122 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.52549871471192 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.17540899912514 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.4020518147283 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 499.8021386563778 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.907110713276207 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.83820830285549 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 256.1269470800956 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.78079840424014 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 72.37076645510064 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 23.138836522897083 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1571.8272539476554 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.8563661078612 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.91975836579998 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1429.755948483944 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3021.657817065716 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4820.258946468432 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.5862208927671 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 282.44050964713097 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 446.1264784137408 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.02686428361469 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.9964226037264 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 657.4965976178646 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2827.7322786549726 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5818.8489601016045 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 8991.279040773708 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 404.31253674129647 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 818.9248045285543 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1232.5903413196404 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 749.389169116815 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1601.173035800457 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3099.6421885987124 | |
