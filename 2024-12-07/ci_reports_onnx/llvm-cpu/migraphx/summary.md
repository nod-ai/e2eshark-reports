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
| migraphx_bert__bert-large-uncased | PASS | 372.68008788426715 | |
| migraphx_bert__bertsquad-12 | PASS | 95.57209696088518 | |
| migraphx_cadene__dpn92i1 | PASS | 186.09751171121994 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7396.393569807212 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 337.64107152819633 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 385.3724425037702 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 413.340063765645 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.07601032654442 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.25779600576921 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 190.34763456632695 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.11432353797413 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 92.11344200940357 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.9401975704564 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.206949077546597 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.54104017093778 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.54068867696654 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.96874724052571 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.66425261232588 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.59777630493045 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1354.997309545676 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.51291950543722 | |
| migraphx_torchvision__inceptioni32 | PASS | 6095.495952914159 | |
| migraphx_torchvision__resnet50i1 | PASS | 98.96525793841904 | |
| migraphx_torchvision__resnet50i64 | PASS | 5382.619341214498 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2748.046307514111 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4300.698184718688 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5910.749559601148 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.43690407524505 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 281.72401794128945 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 493.28669905662537 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 379.06205529967946 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 603.1932234764099 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 827.8970482448736 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5142.7665154139195 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8053.254110117752 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11816.958593825499 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 718.6601075033346 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1154.1106986502805 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1672.0311182240646 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1317.122376213471 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2079.936778793732 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3171.1773549516997 | |
