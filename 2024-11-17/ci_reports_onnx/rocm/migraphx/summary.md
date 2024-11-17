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
| migraphx_bert__bert-large-uncased | PASS | 20.15538845832149 | |
| migraphx_bert__bertsquad-12 | PASS | 211.91214739034572 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.1636577012638 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 212.97879486034313 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.55268292781967 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 44.06903909208874 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.573628269158946 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.23168598228331 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.61097948711653 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.89456516897512 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 114.70168246887624 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.7793416989346 | |
| migraphx_ORT__distilgpt2_1 | PASS | 63.05268706020079 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.15458533416192 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.54432586414947 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.857510106431114 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 28.321359145383422 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.157672066064105 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.88284466459992 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.811453319408676 | |
| migraphx_torchvision__inceptioni32 | PASS | 138.59166984135905 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.7947012692069 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.4548411802167 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.777592136214174 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.55800226020315 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.570251391054347 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.849725861564957 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.0889204273976 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.334010788574327 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.880366322894888 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.623101318255067 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.58526525025566 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.93776494903223 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.43636500214535 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.016051302866442 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.46108746383248 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.79984431522779 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.148255746989022 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.955463770776984 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.450957804187844 | |
