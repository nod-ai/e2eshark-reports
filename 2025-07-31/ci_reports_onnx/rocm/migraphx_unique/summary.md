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
| migraphx_bert__bert-large-uncased | PASS | 19.350865685647385 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.5295249948745298 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.22271369711407 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.214852840389989 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.114271623233759 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 28.239639987392973 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.0998119127471 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.45435368882803 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 109.66134916654683 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 109.73236433185066 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.22955022114587 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 515.1524746712918 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.22571254716338 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.939218368162535 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 269.11552311826705 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.75635950997259 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.79933592908503 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 10.18110864639104 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.12679202000921 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.09122747732711 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.057540649102591 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.831810146624814 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.27114262935509 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 55.84619041635758 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.548548678577864 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.710823824057693 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.454942143580933 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.007041969822351 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.154724752851983 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.671562035606865 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.548744598539386 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 68.89749406545889 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 110.04691389098298 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.43398961264864 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.258166229385616 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.37267256872211 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.284352646615613 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.223681715495285 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.637820275726185 | |
