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
| migraphx_bert__bert-large-uncased | PASS | 423.9201322197914 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 178.07630418489376 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5288.537908345461 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 321.849732970198 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5069.882561763127 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 377.3001531759898 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.9020912597577 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.04941597332557 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.934573743831027 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.77476081252098 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.31819739275507 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.5802058591729 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 250.05981740024353 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.206746381262075 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.61005271722873 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.70436377326646 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.508182003542224 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.78734912143813 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.124677901466676 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1688.9828170339267 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.59780228883028 | |
| migraphx_torchvision__inceptioni32 | PASS | 5399.541702121496 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.49002029374242 | |
| migraphx_torchvision__resnet50i64 | PASS | 5116.925172507763 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2627.3952064414816 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4150.198159118493 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5806.56936019659 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.05140570551157 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 984.1936603188515 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 511.0765409966309 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.7477104415496 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 610.4330482582251 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 809.0029110511144 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5987.698336442311 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8100.717193136613 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11420.703876763582 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 737.265675018231 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1136.8331958850224 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1523.4102805455525 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1298.301812261343 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2115.6594939529896 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2898.204249640306 | |
