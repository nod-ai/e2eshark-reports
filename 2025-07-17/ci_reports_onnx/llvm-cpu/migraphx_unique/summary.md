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
| migraphx_bert__bert-large-uncased | PASS | 1217.609889805317 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.74659572790065 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5557.523328190048 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.7113517411053 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.55543794855475 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.0713537397484 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.72568777669221 | |
| migraphx_models__whisper-tiny-decoder | PASS | 64.87237941473722 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 256.05036887443725 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 219.37713399529457 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.87214955877055 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1517.7901821831863 | |
| migraphx_torchvision__inceptioni1 | PASS | 189.9670014002671 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.91780965030193 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1584.98668919007 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5382.173145500322 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9566.863604821265 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 235.87013819875816 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 390.6583584224184 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 365.58574391528964 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 240.34590584536394 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 565.0070458650589 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.8312838897109 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5461.542880783479 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13868.55151845763 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23539.071458702285 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.99337707459927 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 810.7134696717063 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1316.5862516810496 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 744.0917938947678 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1650.7038918013375 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3414.7020674621067 | |
