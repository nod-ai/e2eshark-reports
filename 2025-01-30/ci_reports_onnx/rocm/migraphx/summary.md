## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 76.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 18.860664679081523 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.944618898247161 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.0293517876129 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.413828097032133 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.69084838233539 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.59058353879178 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.10745590557121 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.82458844042516 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 467.0217755192425 | |
| migraphx_ORT__distilgpt2_1 | PASS | 57.120729860293466 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.702922610862345 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 268.34729799560995 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.766927014637204 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.756881705570283 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.645132949017615 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 61.00024442356597 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.556336215351504 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.39678690040436 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 69.9300000987326 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.92333116682804 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.217922539961384 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.070820992864252 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.896750592908846 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.557799539020515 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.745038594160338 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.64731410154225 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.07338242951249 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 138.76275446188325 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.261521520980056 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.490931917783303 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.921631408970295 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.90719974379953 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.269108121697272 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.19127875512155 | |
