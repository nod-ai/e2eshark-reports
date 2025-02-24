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
| migraphx_agentmodel__AgentModel | Numerics | 1.3900379646350884 | |
| migraphx_bert__bert-large-uncased | PASS | 373.47178036967915 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 184.81755008300146 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5553.540664414565 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.77261416614056 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5471.161477267742 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.41545873383683 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 3639.8064518968263 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.33408879808015 | |
| migraphx_models__whisper-tiny-decoder | PASS | 36.56562293569247 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.87248417072826 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 84.13134941032953 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.83592456295376 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 256.057217096289 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.2037036107345 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 419.93193825085956 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 1422.7972539762657 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.31962822874387 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.90890455080402 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.5471555742563 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1486.0512303809326 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.29224113126597 | |
| migraphx_torchvision__inceptioni32 | PASS | 5818.002667278051 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.22671941419442 | |
| migraphx_torchvision__resnet50i64 | PASS | 5644.788544625044 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2592.540810505549 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4304.645795375109 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5672.630995512009 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.56059394031763 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.1210384517908 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 383.99672880768776 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 468.23594098289806 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 628.7754947940508 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 862.5862250725428 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5716.531082987785 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8430.203940719366 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12169.693994025389 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 741.941437125206 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1493.1494481861591 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1548.0210818350315 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1471.4269066850345 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2150.1498334109783 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3383.7216744820275 | |
