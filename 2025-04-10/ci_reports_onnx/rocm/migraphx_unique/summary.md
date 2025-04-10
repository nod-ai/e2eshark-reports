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
| migraphx_bert__bert-large-uncased | PASS | 19.299868234493594 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.4647218620673454 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.27889342621589 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.095154529793331 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.917273926376862 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.791655400709715 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.0201269290082635 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.33932320669513 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.838988552594344 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.73865294081365 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.06308316529935 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 554.1034976292091 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.0254283331645 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.10025987644312 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 328.1115354814877 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.37860111155295 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.354955579032534 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.559507166777305 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.21322728269847 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.810054197695208 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.155802819490866 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.837178028355808 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.7952644239964 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.2305862782135 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.143173829210385 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.719005100408161 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.353042343195906 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.84210979374069 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.5322671783355 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.352612118300634 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.57078665064386 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 76.4214679279744 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 116.81378238588674 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.694854379520702 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.966869009106293 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.06226251349281 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.69835132273261 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.288214946076128 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.47489481768571 | |
