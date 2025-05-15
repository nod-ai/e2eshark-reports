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
| migraphx_bert__bert-large-uncased | PASS | 633.6583378724754 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.71354842341194 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5881.528981262818 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.2236218039567 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 454.99230886343867 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.4112753250326 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.8634388712013 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.05094573750264 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 221.7399615328759 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 64.16707101096917 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.557725371704212 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1507.0896616671234 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.7017614301294 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.24949679647882 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1550.817343328769 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5438.0108487481875 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9335.6308923879 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 168.50571582714716 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.8346631716316 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.7438248246908 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.54497275253138 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 423.03521632372093 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 659.1023025102913 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5191.427088963488 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13909.29282642901 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23586.79154732575 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.5174547595282 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 794.8861603314677 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1221.346424349273 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 755.6724279808501 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1673.0891183639567 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3673.663493556281 | |
