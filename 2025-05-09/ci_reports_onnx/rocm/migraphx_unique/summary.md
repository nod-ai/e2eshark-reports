## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 33 | 76.7% | 84.6% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 14.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.096284306887117 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 4.064595274837865 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.407385217091544 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.680502967676149 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.126964172251366 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.747615387818467 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.137254673071167 | |
| migraphx_models__whisper-tiny-decoder | PASS | 41.310429313280444 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 129.1006940559277 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 118.82856739329225 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.74275710760976 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.3926116682899 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.58531609662653 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.066801027035 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 313.23818432671635 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.676528085644044 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.02243135021664 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.091272948541615 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.691652297313944 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.401616382953458 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.158601638885807 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.852732159274936 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 40.207410590718844 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.47670941612967 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.290488214007226 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.408264585336623 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.215166630467 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.47802999415925 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.349507923632498 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.346778790311266 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 38.75241001919171 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 75.72160792726747 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.7216748900634 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.49710657289769 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.808552363899185 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.65594663142879 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.909765733556608 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.720040440869823 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.576440050499514 | |
