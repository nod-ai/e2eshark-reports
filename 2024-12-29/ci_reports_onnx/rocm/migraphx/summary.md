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
| migraphx_bert__bert-large-uncased | PASS | 19.268594570113 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.448658450488374 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.41184755787253 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.44798613794974 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 364.44451566785574 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.265443873633327 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.537896738778198 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.33524077953327 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.48152999207377 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.73865250746407 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.18696780094785 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 499.6105825218062 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.754492529800956 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.268337593046994 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 791.1571627482772 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 48.16042514852224 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.961841173795243 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.093873655029501 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.3359819796902 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.738629108156864 | |
| migraphx_torchvision__inceptioni32 | PASS | 169.91003059471646 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.354082884887852 | |
| migraphx_torchvision__resnet50i64 | Numerics | 189.35462700513503 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.519839295496546 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.56254095366845 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.53590803124285 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.028204228361078 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 18.029193675040073 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.4732577289903 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.658655948259613 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.237100753511461 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.76687302805173 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 102.17654084165889 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.4759431220591 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 632.2253438023229 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.299625454812633 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 29.485005117021498 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.755250500849424 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.317491108462924 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 45.59595164998124 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 99.93233528609078 | |
