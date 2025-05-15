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
| migraphx_bert__bert-large-uncased | PASS | 19.176144779151027 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.8995112265473693 | |
| migraphx_cadene__inceptionv4i16 | PASS | 27.250374121089973 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.588315150754937 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.054784677710486 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 27.406910786596242 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.307642900449636 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.83591083555903 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 128.93323306666892 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.8268673419435 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 117.79257271619927 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 521.0607936605811 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.93307022890076 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.74610100610351 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 308.9931438444182 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.194748728565635 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.325215020217 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.906686356692921 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.671896732794362 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.409039750123157 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1365822770286003 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.448622654610052 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.276062991659806 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 58.41250213496904 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.30010491590725 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.408161182528394 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.350253454090474 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.607420975525331 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.333374494669474 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.09041506375763 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.902230562299096 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.99385512151099 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 116.32552572862348 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.569325629466523 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.674235443128087 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.200334934913815 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.770640946769465 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.029724210500717 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.703110688133165 | |
