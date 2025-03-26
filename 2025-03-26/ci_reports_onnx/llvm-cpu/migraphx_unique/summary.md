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
| migraphx_bert__bert-large-uncased | PASS | 374.49100613594055 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 183.45734228690466 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5335.499657938878 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 369.0059545139472 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.3990609546502 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 426.1526931077242 | |
| migraphx_mlperf__resnet50_v1 | PASS | 120.47012315856085 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.06151694556077 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.89291205008826 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.23956226640276 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.97480819622673 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.80645195643106 | |
| migraphx_ORT__distilgpt2_1 | PASS | 163.42730795343715 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.71558941528201 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.6612560848395 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.33897138469749 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.96495831233483 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.50267387816199 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1471.0274847845237 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.83508566353055 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.1383143949012 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1491.531863808632 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3109.352464477221 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4953.4854255616665 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.90774530917406 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 256.48017186257573 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 358.5570293168227 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 233.542972140842 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 446.25184560815495 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 768.9035820464293 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2971.5828920404115 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 6126.074858009815 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9333.257811764875 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.836344619592 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 831.6820375621319 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1316.207310805718 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 765.4156262675921 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1507.5060712794464 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2444.630564500888 | |
