## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 497.1041080231468 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 179.5934538046519 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6557.622333988547 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 362.38934316982824 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5105.986629302302 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 469.52798248579103 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 510.43227625389886 | |
| migraphx_mlperf__resnet50_v1 | PASS | 165.5112166578571 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.71624499373138 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.90190312680271 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.4648220397177 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 273.32951376835507 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.81323057599366 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.38290613641342 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.06632921099661 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.31550253762139 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1324.3635321656861 | |
| migraphx_torchvision__inceptioni1 | PASS | 220.14359053638245 | |
| migraphx_torchvision__inceptioni32 | PASS | 6101.523235440254 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.5452907619377 | |
| migraphx_torchvision__resnet50i64 | PASS | 5345.407128954927 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2669.6909901996455 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4233.703909441829 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5860.806825260322 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.9279906153679 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 271.45302047332126 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 471.7001573493083 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 428.71396616101265 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 634.2931302885214 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 872.1571161101261 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5194.514323025942 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8288.125430544216 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11238.198963925242 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 737.4482365945975 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1114.0148844569921 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1573.3939974258344 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.3019804954529 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2062.857535978158 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3056.8423507114253 | |
