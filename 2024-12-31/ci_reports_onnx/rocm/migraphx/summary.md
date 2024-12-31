## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 36 | 76.6% | 76.6% |
| Gold Inference | 36 | 76.6% | 100.0% |
| IREE Inference Invocation | 36 | 76.6% | 100.0% |
| Inference Comparison (PASS) | 24 | 51.1% | 66.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 23.4% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 12 | 25.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.240528332172996 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.78058318669596 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.30332672575281 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.9564708961795 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.5596345847834145 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 29.147438492560592 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.042093422382116 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 143.03020692119995 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.00679078077276 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.20464136770791 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.02766773973894 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.14679813977236 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.20601674598274 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.42012717885274 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 30.664256773889065 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.722053828077357 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.4789446264083645 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.37341803422679 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.75135817502936 | |
| migraphx_torchvision__inceptioni32 | PASS | 121.86507372895164 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.32345670003003 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.82392305042595 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 339.5020389463752 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.4146050710438 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 218.4441216393477 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 36.69497905080609 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 40.04701445136899 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 30.452325621067924 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 15.740103825616337 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.249394393074999 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.697400171736565 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 142.064644365261 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 239.14041840988727 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 1203.7945580668747 | |
| migx_bench_bert-large-uncased_4_128 | compilation | None | |
| migx_bench_bert-large-uncased_4_256 | compilation | None | |
| migx_bench_bert-large-uncased_4_384 | compilation | None | |
| migx_bench_bert-large-uncased_8_128 | compilation | None | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.64607803409712 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.44928114248129 | |
