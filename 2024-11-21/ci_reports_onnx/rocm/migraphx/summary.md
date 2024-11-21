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
| migraphx_bert__bert-large-uncased | PASS | 20.028953714098037 | |
| migraphx_bert__bertsquad-12 | PASS | 19.62506910521162 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.87929119949695 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 213.8599032231367 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.662368934794305 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.549030078849505 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.578665484319445 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.234856757575685 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.922250916305835 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.8798597779306 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.85103333285143 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 367.7064216662984 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.994548818063 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.64188063333373 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 276.0633856665259 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.5441340981194 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 27.18327227975048 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.210841147314806 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.96061688103266 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.910464204573529 | |
| migraphx_torchvision__inceptioni32 | PASS | 138.8277703340767 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 183.8847465002497 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.72004592049975 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.16371955542207 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.67784023287338 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.663712483571098 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.935089366423197 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.0010429713681 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.573464113174142 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.19460362655324 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.806366270690585 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.65171656665916 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 105.0618419519326 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.79965606729576 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.203144681093534 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.63406014160864 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.806073384553503 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.3097567714784 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.233413199729203 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.58935621586245 | |
