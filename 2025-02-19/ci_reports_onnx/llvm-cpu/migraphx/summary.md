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
| migraphx_agentmodel__AgentModel | Numerics | 1.2915379633860928 | |
| migraphx_bert__bert-large-uncased | PASS | 368.87394698957604 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 206.16962605466446 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5709.32258789738 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 430.8039341121912 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5347.920234004657 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 429.3335936963558 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.05541411042213 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.31344473361969 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.325202153036084 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 189.33535863955817 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.10697635156767 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.35255695950416 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.75783443450928 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.99828313139901 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 98.45495348175366 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 247.74464343984923 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.96302790017355 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 85.55416410995853 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.05904430931522 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1491.6357199350994 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.42569776707225 | |
| migraphx_torchvision__inceptioni32 | PASS | 5803.319970766704 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.96666565164924 | |
| migraphx_torchvision__resnet50i64 | PASS | 5489.234158148368 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2653.089808921019 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4067.1078972518444 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5799.6701536079245 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.8622544358174 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 308.20582869152224 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 442.2307995458444 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 409.1578759253025 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 582.4399466315905 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 808.1644649306933 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5085.376276324192 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8073.14287001888 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11115.765079855919 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 743.8905201852322 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1186.8215488890805 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1545.5731836458046 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1322.9528044660885 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2098.6461266875267 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2912.7921971182027 | |
