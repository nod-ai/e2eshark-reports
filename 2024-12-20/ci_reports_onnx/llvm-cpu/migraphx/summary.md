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
| migraphx_bert__bert-large-uncased | PASS | 564.1679229835669 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 172.68101001779237 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5529.001951217651 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 348.4859907378753 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6030.627777179082 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.8547039429347 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 741.9981366644303 | |
| migraphx_mlperf__resnet50_v1 | PASS | 200.32451736430326 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.96547077194092 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.28262484404775 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.84359217257725 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 93.84847095324879 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 301.9024071594079 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.2995748110846 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.21051516880591 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 867.9161798208952 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.582946443841564 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.97537519865566 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.510217762862645 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1529.3484156330426 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.15501481956903 | |
| migraphx_torchvision__inceptioni32 | PASS | 5737.7901400129 | |
| migraphx_torchvision__resnet50i1 | PASS | 88.495208216565 | |
| migraphx_torchvision__resnet50i64 | PASS | 5848.76865396897 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2652.364704757929 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4364.110447466373 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5737.547572702169 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 155.7103053977092 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.38228513465987 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 424.05410297214985 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 420.69361234704655 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 694.2905187606812 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 838.1043101350466 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5232.975594699383 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8049.553205569584 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11303.105392803749 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 742.6884224017462 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1088.7478291988373 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1516.7793395618598 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1342.9962322115898 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2051.567168285449 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2948.4012871980667 | |
