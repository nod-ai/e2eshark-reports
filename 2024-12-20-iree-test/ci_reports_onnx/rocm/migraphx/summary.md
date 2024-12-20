## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.28961857791162 | |
| migraphx_bert__bertsquad-12 | PASS | 8.033213174952438 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.43343763907129 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.28954724843302 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 279.3484856374562 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 852.9383310427269 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.380020993878134 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.575460143387318 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.873934633408986 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.1960765669743 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.29816074013 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.54502262316998 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.9610955777268 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.41034091244905 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 106.7874228553564 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 295.46449558498955 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.32640653820426 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.5262692396275 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.958709820173681 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 77.07719242683162 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.6798708545113 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.07322133917893 | |
| migraphx_torchvision__resnet50i1 | Numerics | 19.426282348663165 | |
| migraphx_torchvision__resnet50i64 | Numerics | 323.4365413663909 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.594721660214034 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 135.30116353649646 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.9447284426402 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 23.644901038848868 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.195379153948346 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.409589676393402 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.718197162030265 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.274012060261933 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.92950790534572 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 155.13751300362247 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.11728250318102 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.7448317380622 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.35488017694074 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 21.074777075017874 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 37.28290803682727 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.794036469477067 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 55.24497297592461 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 46.703459240407454 | |
