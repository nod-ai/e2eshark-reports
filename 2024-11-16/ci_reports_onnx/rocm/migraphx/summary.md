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
| migraphx_bert__bert-large-uncased | PASS | 20.050806188512414 | |
| migraphx_bert__bertsquad-12 | PASS | 212.48484780598017 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.44183887168765 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 211.98609233316446 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.612438464159333 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.78967088895539 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.48014861975371 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.96947515302378 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.429761964445696 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.75123315014771 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.59321927941507 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 368.5736254944156 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.10167636654593 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.02262165956199 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.17284621919197 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.468518777370996 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 27.88890202720769 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.804769896098183 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.66061762738085 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.753401171726482 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.3148987069726 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.32251428222904 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.26735918277076 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.25883880060994 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.79003953250746 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.595037899600962 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.849481502000025 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.914797613663335 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.401828228663176 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.02613610650102 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.596718953029875 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.31847488259275 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 103.62010138730206 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.15936842560765 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.07515200427261 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.292208659152188 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.44409500778868 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 23.957829062073003 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.851925641298294 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.181757251786834 | |
