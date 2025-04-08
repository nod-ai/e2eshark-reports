## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 454.0518435339133 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.40340481698513 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5935.229210803906 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.96095618605614 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 811.8872692187628 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.6127307762702 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.64555846509478 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.10106928073443 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.09520396259094 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.62664522585413 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.87316279042335 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 269.413985311985 | |
| migraphx_ORT__distilgpt2_1 | PASS | 38.167349263733506 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 95.48236657347944 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.637028714021 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.09366101201843 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 66.80247752052364 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.651224110880467 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1622.0080070197582 | |
| migraphx_torchvision__inceptioni1 | PASS | 190.58914482593536 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.05552977820237 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1594.9716232717037 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3068.595471481482 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4780.058663338423 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 214.97215051203966 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 303.69013713465796 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 364.20659596721333 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 234.13719154066507 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 525.3074392676353 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 686.2235640486082 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 3146.568264812231 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5799.329162885745 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9136.417523026466 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 419.59261521697044 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 887.5050743420919 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1236.3552177945771 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 759.5423658688863 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1648.9079544941585 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2372.173932691415 | |
