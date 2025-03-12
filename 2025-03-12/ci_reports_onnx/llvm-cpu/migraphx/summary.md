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
| migraphx_agentmodel__AgentModel | Numerics | 1.3476204411238586 | |
| migraphx_bert__bert-large-uncased | PASS | 375.12570184965927 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 189.53159234176078 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5389.870384087165 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 338.8330340385437 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5123.540402700503 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.2900184392929 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.3926213433345 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.37971985198202 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.180710250896116 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 177.95655721177658 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.94607163468994 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.87509008248645 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 283.0797727737162 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.353524571743563 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.23793891072273 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.52172202534143 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.754368364810944 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.74242364697986 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.687282514922764 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1443.0803656578064 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.63250097963544 | |
| migraphx_torchvision__inceptioni32 | PASS | 5789.237204939127 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.44921345512073 | |
| migraphx_torchvision__resnet50i64 | PASS | 5539.765529334545 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1505.1713561018307 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2952.0720479389033 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4779.050961136818 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.2935950110356 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.4496250682407 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 370.83748541772366 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.3278181552887 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 466.0519106934468 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 674.9441561599573 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2897.7736296753087 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 6294.8537568251295 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9123.744569718838 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 489.4341652592023 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 804.6202374001344 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1346.2299133340518 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 749.8105975488821 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1523.0498959620793 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2369.265186289946 | |
