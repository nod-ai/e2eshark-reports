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
| migraphx_bert__bert-large-uncased | PASS | 369.852377101779 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 200.5289737135172 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5534.170303493738 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.0188395132621 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 398.8094025601943 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 429.07723349829513 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.50176972150803 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.31590506103303 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.94414517614575 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.70368405017588 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.59553359650277 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1507.049173116684 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.5868150368333 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.53760962684949 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1529.4707231223583 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5264.972861856222 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9583.99477476875 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.8809828062852 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.8193597429328 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 390.3604665150245 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 247.32020704282652 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 456.5353902677695 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 666.8707591791948 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5147.871567557255 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13339.93443970879 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23615.715354681015 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 405.49916711946327 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 798.547292749087 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1266.0062598685422 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 791.6392063101133 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1754.941279689471 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3390.615231047074 | |
