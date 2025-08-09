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
| migraphx_bert__bert-large-uncased | PASS | 392.25650237252313 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 175.58883792824213 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5446.281133840482 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.14158317198354 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 454.11967268834513 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 524.7499644756317 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.0373048401541 | |
| migraphx_models__whisper-tiny-decoder | PASS | 74.52831438018215 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 238.13190766506725 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 200.84300740725462 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 250.28166764726242 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 623.7096084902684 | |
| migraphx_ORT__distilgpt2_1 | PASS | 80.24425068426699 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 190.0750940872563 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 638.8273909687996 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 162.5122683536675 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 64.34359757060354 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.76772908275729 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1594.9814996371667 | |
| migraphx_torchvision__inceptioni1 | PASS | 226.76970706217818 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.10060616210103 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1696.1597533275683 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 6140.186423435807 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9781.165634592373 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 146.17261476814747 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.3405982736084 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.3202640687426 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.0509947737058 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 624.2997879162431 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 756.0360580682755 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5073.382483795285 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14547.485932707787 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23356.478962426383 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 460.704297448198 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 874.8393052568039 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1234.3863652398188 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 789.3919218331575 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1721.2936915457249 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3640.067604680856 | |
