## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 82.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.890161991740264 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.1375250381728 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.33668913071355 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.415947614151798 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.795489253234805 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.457053574901473 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.4420643808941 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.436527413483226 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.95508801574921 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 111.34982026285594 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 363.40320281063515 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.28560657250798 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.0951276520888 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.69284426317444 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.67945563057928 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 20.447166883112754 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 12.854754796479732 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.7074783478553 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.57087968131182 | |
| migraphx_torchvision__inceptioni32 | PASS | 138.210395614927 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 183.00420889863744 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.583695253741645 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.87116785197415 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.39645642787218 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.469989853314098 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.660982684871437 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.93427942506969 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.25741545028555 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.945845124658709 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.547260917629107 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.62312524362157 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.98110861295743 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.8120443082104 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.984900817103311 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.459776165680243 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.61112539517956 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.86851395913126 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.879465790750043 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.30742261094935 | |
