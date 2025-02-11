## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.028645512482218 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.074453003597736 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.623165653630465 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.828361944923038 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.656539458628686 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 50.145446235061776 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.78431200046492 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.4813685238949 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 474.75524416465004 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.08226402790105 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.21622760516985 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 268.1049037782941 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.31635618496026 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.01999527160711 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.980565944294676 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 5.169492886440517 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.075939712575 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.82774497542041 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 71.47797373521219 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.066339784877975 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.362159426853042 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.396198928269122 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.943059969535325 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.489153294643735 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.834888637467635 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.33065272939292 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.14304747788368 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 141.15459693227118 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.416598503439857 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.458020737086056 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.68748550680696 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.62514987920898 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.129713172649236 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.25889601830729 | |
