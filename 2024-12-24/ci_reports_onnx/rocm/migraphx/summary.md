## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.28361365571618 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.47857637043732 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.29449132084846 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.26823945819503 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.6455407831818 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.189073086207369 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.07628322751926 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.50845325945152 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.58518759161234 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.5956532258008 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.33756733135806 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 503.77410308768344 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.82920868503741 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.545722059566856 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.08366867775715 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.67440779950647 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.432147779245522 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.8494095810439015 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.09975431114435 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.712085534690644 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.7625774217858 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.388010737396733 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.24397738495222 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 77.61464632737139 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 88.57616434235952 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.15104334953206 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.061009758485502 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.564382392749097 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.51504918253394 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.717549068232374 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.299332635840344 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 23.506136780876357 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 1980.4000809478264 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 141.98612882238294 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 200.55765938013792 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.466428137732807 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.67330326838419 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 46.06153402262583 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.38802160393624 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.93107563169259 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 46.84973026936253 | |
