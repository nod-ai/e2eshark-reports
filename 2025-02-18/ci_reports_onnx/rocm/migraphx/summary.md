## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 77.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.4479662100647803 | |
| migraphx_bert__bert-large-uncased | PASS | 19.17559458201544 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.235530220993067 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 32.12728161856325 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.89165466868629 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.42552387869606 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 64.63273310671663 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 122.94434533557957 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 127.64140790871654 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 509.3315049695472 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.88861328964897 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 402.33629068825394 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 267.1329299143205 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.98413176745104 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.813502614224102 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.24065627223885 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 5.324585754847662 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.9689242892447 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.854913585102906 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.61081570573151 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.537971978616396 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.303948427609939 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.317779132811765 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.724823181785252 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.51188472765 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.424068827364668 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.93511024738352 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.05637818193505 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 140.1745623986547 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.808245917368266 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.261652460921006 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.592494299014408 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.21242622261828 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.413599000507848 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.4134625568986 | |
