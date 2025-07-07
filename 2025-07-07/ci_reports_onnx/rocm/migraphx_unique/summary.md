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
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 19.455799117201455 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.477137373639873 | |
| migraphx_cadene__inceptionv4i16 | PASS | 19.66530917626288 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.183574531451021 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.967020306273613 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 26.55107123204149 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.051014563689627 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.15437836440591 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 103.4834259633152 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.74989572829669 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.7347671519965 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 537.4297803888718 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.80688502080739 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.19304070023423 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.04652849398553 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.29963012070706 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.492605168826696 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.06401763293965 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 13.73201014342694 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1145827101898327 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0271656874887003 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.562702883256687 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.314109275476966 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 55.22986659063742 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.562435631996685 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.065079636307376 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.275605743233527 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.055788761257757 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.454646221775974 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.740034334568513 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.672378640932344 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 70.31924642312029 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 109.42381372054417 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.759311340749264 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.092509704686346 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.220630367803906 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.16469677023235 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 25.894980561448094 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.272564734078266 | |
