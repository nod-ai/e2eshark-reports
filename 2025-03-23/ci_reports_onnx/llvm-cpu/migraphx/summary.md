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
| migraphx_agentmodel__AgentModel | Numerics | 1.086689306375308 | |
| migraphx_bert__bert-large-uncased | PASS | 371.90732049445313 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 215.02860262989998 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5451.797236998876 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 326.71457280715305 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5122.687678784132 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.4838039278984 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.28251359363395 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.74407610013371 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.00560829675558 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.07716646045446 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.37040617494354 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.37305207716093 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 246.80319759580823 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.073743907437805 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.61036986733477 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.96961955891712 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.176529679033486 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.47423558323472 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.157966497482036 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1457.9531600077946 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.2712098658085 | |
| migraphx_torchvision__inceptioni32 | PASS | 5784.967282166083 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.97102045516174 | |
| migraphx_torchvision__resnet50i64 | PASS | 5428.677015006542 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1481.3293715318043 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3027.0911877353988 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4809.212535619736 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.6021041671435 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.93344037731487 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.15890850126743 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 254.48177672094766 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 467.3212505877018 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 781.5715906520685 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2920.3043803572655 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5826.01348310709 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9140.275395164887 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 403.16213356951874 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 790.3963650266329 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1278.4854546189308 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 736.7532067000866 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1625.6741558512051 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2412.732089559237 | |
