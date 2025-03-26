## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.3415141672384543 | |
| migraphx_bert__bert-large-uncased | PASS | 366.83453309039277 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 162.9488921413819 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5401.166229198377 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 330.4617777466774 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5032.55491082867 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 421.284727131327 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 441.66719044248265 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.53497000819159 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.28166811755209 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 216.3623571395874 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.19521201319164 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.60927343936191 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 298.91607103248435 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.36156567067339 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.06059945481162 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.78104220827421 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.548609267782275 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.6320680860016 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.106281006806775 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1445.1794425646465 | |
| migraphx_torchvision__inceptioni1 | PASS | 204.89206165075302 | |
| migraphx_torchvision__inceptioni32 | PASS | 5840.474183360736 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.1640462167561 | |
| migraphx_torchvision__resnet50i64 | PASS | 5392.8710706532 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1519.9289880692959 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3025.4458660880723 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4610.896863043308 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.26719497392574 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 254.80412484871013 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 383.73179112871486 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 243.68824271692168 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 447.3532202343146 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 702.7477932473024 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2806.6880193849406 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5912.363739063342 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9434.412876764933 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 425.3967609256506 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 832.6608998080095 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1280.2208214998245 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 745.4394958913326 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1527.0518064498901 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2433.200405289729 | |
