## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.057123318491946 | |
| migraphx_bert__bertsquad-12 | PASS | 17.66470776727566 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 163.07387760995576 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 188.83745073496053 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.7276932793727395 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.04515533335507 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.587006289324482 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.531281451779332 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.370620237472345 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.19419162161648 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.34533706597155 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.743584189564 | |
| migraphx_ORT__distilgpt2_1 | PASS | 62.972678570076816 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 74.1122426137466 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 283.2191610165561 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.01094504971715 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 23.951599525068612 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 13.3452784714543 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 73.63331334285989 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.428770146246446 | |
| migraphx_torchvision__inceptioni32 | PASS | 140.84811674741405 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 170.39140302222222 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.65357538172975 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 61.243102638841115 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 77.92097068805661 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.581945104341882 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.787012139420492 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.051597111991473 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.393686570895786 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.133628217192985 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.102052178133718 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.74098978471011 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.79528559154521 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.5239753400286 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.12151824283427 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.168975720500463 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.719653394694124 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.02796733379364 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.53913655882287 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.53306860624192 | |
