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
| migraphx_bert__bert-large-uncased | PASS | 19.31574681448519 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.041161890015549 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.107576861760105 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.412592786081304 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.266126375660046 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.423377628536684 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.79357390501312 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.66096288860447 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.00041257811892 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.09716050123744 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.52182366843529 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.4706289940901 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.68846596723111 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.007456787713714 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 328.23831000011216 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.20235820614459 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.56412019151321 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.285114918392134 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.861202452791968 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.953702125105876 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.2224403139385114 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.04877665420123 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.285780240753574 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.10668805477487 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.256692047404137 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.742987739329692 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.35109020322906 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.8482385637736 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.535888749925544 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.30077235256266 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.84745673697825 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.7350144813277 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.76605650064043 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.657637231729392 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.709440382608378 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.13883993145207 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.793708098305313 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.339053102201802 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.774384383005476 | |
