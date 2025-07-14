## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 372.3941861341397 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.8293531642606 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6102.560135535896 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.0304855555296 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 489.7703031698863 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 2547.11011548837 | |
| migraphx_mlperf__resnet50_v1 | PASS | 166.64724300305048 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.96002635421852 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 211.15134780605635 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 57.87888508186572 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 25.31874773329964 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1488.0910164987047 | |
| migraphx_torchvision__inceptioni1 | PASS | 249.8195884335372 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.46285644776763 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1586.1371920133631 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5272.248623582223 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9611.591476015747 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.38866016827524 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.8593028394712 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.44413953398663 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.54399648391538 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 425.358515077581 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 742.1054166431228 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5028.263199143112 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13445.530798596641 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23109.155488200486 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.91076188037795 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 783.7658937399586 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1237.4467641736069 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 735.534492880106 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1669.2600700383384 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3402.5171532606087 | |
