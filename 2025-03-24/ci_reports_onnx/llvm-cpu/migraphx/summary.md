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
| migraphx_agentmodel__AgentModel | Numerics | 0.970133682462246 | |
| migraphx_bert__bert-large-uncased | PASS | 381.9673943022887 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.00453999390206 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5319.05656059583 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.01488528152305 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6495.788864791393 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 401.0919202119112 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 430.3566875557105 | |
| migraphx_mlperf__resnet50_v1 | PASS | 337.24488229269065 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.70932547161073 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.1977181567086 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.67771084482472 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.8531981292698 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.03945681783887 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.68853005205375 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.3272575352873 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.99681574768488 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 48.000339542826005 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.52174189065893 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.419768770535775 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1468.5480060676734 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.90009527405104 | |
| migraphx_torchvision__inceptioni32 | PASS | 5753.027121225993 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.80459598327677 | |
| migraphx_torchvision__resnet50i64 | PASS | 5454.361559202273 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1410.0978535910447 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3151.9905477762222 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4746.72927459081 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.05801707009473 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.47310001982584 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 361.21562247474986 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 241.09366577532555 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 493.31467412412167 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 686.7582388222218 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2776.8560412029424 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5932.560508449872 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9241.256485382715 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 403.13910755018395 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 796.9322986900806 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1252.3910378416379 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 753.1916983425617 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1530.0204418599606 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2402.800048391024 | |
