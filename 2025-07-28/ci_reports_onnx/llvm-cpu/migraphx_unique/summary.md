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
| migraphx_bert__bert-large-uncased | PASS | 387.9436155160268 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.59242884876826 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5344.71707760046 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.10743952418363 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 414.98226920763653 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 437.63962977876264 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.4499639701985 | |
| migraphx_models__whisper-tiny-decoder | PASS | 61.27805897483119 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 217.55713183018895 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 1451.6451849291723 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.12677716901689 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1551.566991644601 | |
| migraphx_torchvision__inceptioni1 | PASS | 189.8327588569373 | |
| migraphx_torchvision__resnet50i1 | PASS | 250.68159939514263 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1549.4601459552844 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5335.573542242249 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9398.10797634224 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 144.98129871984324 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 258.2429628819227 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 1130.878533857564 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.12080387688343 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 424.6460398038228 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.4299052804708 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5048.258856870234 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13786.31915555646 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24072.959343281884 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 447.19938732062775 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 857.3332543795308 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1274.3431671212115 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 747.2223537042737 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1664.3004917229216 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3457.720223814249 | |
