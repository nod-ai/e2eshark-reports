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
| migraphx_bert__bert-large-uncased | PASS | 371.9069759051005 | |
| migraphx_bert__bertsquad-12 | PASS | 86.1338669700282 | |
| migraphx_cadene__dpn92i1 | PASS | 180.74637899796167 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6701.480229695638 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 332.6038631300131 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 384.288143987457 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 445.24744773904484 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.16896877260433 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.12940935609918 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 183.31089243292809 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.76491778805142 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 122.58920871785706 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 280.90988596280414 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.533933493224055 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.12825146317482 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.3030160268148 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.116777410661726 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 84.18691034118335 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 55.304450147292194 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1630.401725570361 | |
| migraphx_torchvision__inceptioni1 | PASS | 246.447601252132 | |
| migraphx_torchvision__inceptioni32 | PASS | 6719.806047777335 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.26816502355393 | |
| migraphx_torchvision__resnet50i64 | PASS | 6004.585985094309 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2919.5236625770726 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4450.213064750035 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6245.829743643601 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 175.67680651942888 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 275.80199825266993 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.9973859935999 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 421.0890047252178 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 668.3821106950442 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 833.1786890824636 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5695.52630931139 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8552.690411607424 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11761.370461434126 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1059.5387257635593 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1138.017002493143 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1661.6247184574604 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1451.2537357707818 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2066.0847636560597 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3133.6532967785993 | |
