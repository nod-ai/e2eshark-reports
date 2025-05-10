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
| migraphx_bert__bert-large-uncased | PASS | 478.2208128211399 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.4903018952658 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5831.3588802702725 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.71180785633624 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 435.1923636859283 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 422.471354676721 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.23222315440042 | |
| migraphx_models__whisper-tiny-decoder | PASS | 63.81509882178054 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.43373599927872 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 66.7280755458503 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.143993462018745 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1500.8766070241109 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.81582274481966 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.49838177937393 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1666.2088360171765 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5379.678351338953 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9520.604429029238 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.83522466880578 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 520.8287223164613 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.37758815676597 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.23167622565393 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 436.6792741542061 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.5341297450165 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5140.361071370231 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13655.663475898715 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24464.199923405733 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.24968698993325 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 809.9317773400495 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1694.4316457180928 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 758.2404516870156 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1660.1837963486712 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3509.877267604073 | |
