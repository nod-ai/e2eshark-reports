## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 373.274317321678 | |
| migraphx_bert__bertsquad-12 | PASS | 83.8040287295977 | |
| migraphx_cadene__dpn92i1 | PASS | 179.73510129377246 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6746.143628532688 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 341.3506569340825 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.07658627877635 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 420.1941977565487 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.61241944914771 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.73975760714402 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.67735528449217 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.63283916882104 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.23416453032264 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.60765303836925 | |
| migraphx_ORT__distilgpt2_1 | PASS | 36.34665140675174 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.54397480272583 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 243.47477033734322 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.57016414238347 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.39924520502488 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.39887072973781 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1328.3798185487587 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.31520299282337 | |
| migraphx_torchvision__inceptioni32 | PASS | 6695.214482645194 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.41121081200738 | |
| migraphx_torchvision__resnet50i64 | PASS | 6219.257547830542 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2710.164808978637 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4023.5635228455067 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6182.348622009158 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 173.729475432386 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 262.05028448667787 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.93562999367714 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 422.21337649971247 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 583.0037848403056 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 866.2185072898865 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5170.5052840212975 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8144.265484685699 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12217.27436222136 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 721.230685710907 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1194.1016173611083 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1628.6459552745025 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1366.4575697233279 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2086.6900204370418 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3125.874115154147 | |
