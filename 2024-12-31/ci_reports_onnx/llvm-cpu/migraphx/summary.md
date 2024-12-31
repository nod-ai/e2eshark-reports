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
| migraphx_bert__bert-large-uncased | PASS | 373.12867989142734 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 231.5999244650205 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5406.053858498733 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 331.0226903607448 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5127.643873294194 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 391.67169854044914 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 419.5826730380456 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.59765309237298 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.36874032201189 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.29747529079518 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.00186921585173 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.59673538094474 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 250.1245935757955 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.763662894044003 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 88.09966883725589 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.2459759513537 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.92000031636821 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 77.44794877039061 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.221186677614845 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1623.499482870102 | |
| migraphx_torchvision__inceptioni1 | PASS | 225.76301296552023 | |
| migraphx_torchvision__inceptioni32 | PASS | 5459.330644458532 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.46545688559611 | |
| migraphx_torchvision__resnet50i64 | PASS | 5028.796602040529 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 4259.673967957497 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4129.523642361164 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5697.07399730881 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.33803246418634 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.790071139733 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.11375363667804 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 423.3889263123274 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 590.521660943826 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.06437788407 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5020.762532949448 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8020.741942028205 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11301.452048122883 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 730.7773604989052 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1133.8222449024518 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1534.0751993159454 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1297.519814223051 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2067.5193133453527 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2942.8847456971803 | |
