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
| migraphx_bert__bert-large-uncased | PASS | 378.92328513165313 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 433.32394398748875 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5595.698979993661 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.8182323227326 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5166.522317876418 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 384.80074269076187 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 502.39116325974464 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.53535484398405 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.314461068673566 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.80355268385674 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.67326164080036 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 93.02716134559539 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.4309869756301 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.030359819079887 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.30733926649445 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.82955654462177 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.92405451006359 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.1390127914923 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.10919861805935 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1664.517962684234 | |
| migraphx_torchvision__inceptioni1 | PASS | 210.58460449179015 | |
| migraphx_torchvision__inceptioni32 | PASS | 5818.384756644567 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.27706766997774 | |
| migraphx_torchvision__resnet50i64 | PASS | 5847.881652414799 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2542.6023143033185 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4104.956602056821 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5920.470409095287 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.7854466504521 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.5094643384218 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 371.22900287310284 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 410.9940957278013 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 670.2538318932056 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 852.0254231989384 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5147.408578544855 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8135.335547228653 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11252.67898912231 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 710.8081839978695 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1084.5802227656045 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1534.4344551364582 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1403.7264076371987 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2140.1996091008186 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2990.140666564306 | |
