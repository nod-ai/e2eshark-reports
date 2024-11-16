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
| migraphx_bert__bert-large-uncased | PASS | 398.76720402389765 | |
| migraphx_bert__bertsquad-12 | PASS | 89.3713053729799 | |
| migraphx_cadene__dpn92i1 | PASS | 255.57702236498392 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6452.914640307426 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 373.13040904700756 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1043.8922382891178 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 513.2748372852802 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.15924994505586 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.50847867864464 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.476928293705 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.64374677836895 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.87702429294586 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 298.1252844134967 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.49180238639963 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.31208941712976 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 261.33737733794584 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.6174986122383 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.56283745604256 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.947260473613376 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1362.0063699781895 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.09086345798437 | |
| migraphx_torchvision__inceptioni32 | PASS | 6134.758412837982 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.2605475940638 | |
| migraphx_torchvision__resnet50i64 | PASS | 5212.51255646348 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2626.4118210723 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4153.925480941931 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5982.1334555745125 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.65795672188202 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 267.83300501604873 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.11900810648996 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 431.1777176335454 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 597.1035013596216 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 853.4895218908787 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5183.020630230506 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8091.139113530517 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11337.517591193318 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 723.5141781469187 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1107.4868657936652 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1585.3592846542597 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1328.4377809613943 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2105.957416817546 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3023.59283529222 | |
