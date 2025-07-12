## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 34 | 79.1% | 87.2% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 5 | 11.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.34172962878451 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.4970593886148706 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.819219480268657 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.165218349271072 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.992203644522935 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.66748635590444 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.185122108707825 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.5744621035022 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.266733898116 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.73653114587069 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 120.73496734309526 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 538.2247736367086 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.93182024359703 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.3918973567585 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.23615772215027 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.72007437764356 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.450904029820645 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.185900078400184 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.600759996244541 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.091422182128385 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.058041417364811 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.79754918675732 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.08773334265539 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.8842783793807 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.582809514632181 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.694281873039223 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.230754114687443 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.770201940315237 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 25.472111736976156 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.65567101379511 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.07708980174114 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 69.2297400906682 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 110.59099215910665 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.305489603774966 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.116696484564315 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.17690611299541 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.299273387839396 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.017541324512823 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.410417344759814 | |
