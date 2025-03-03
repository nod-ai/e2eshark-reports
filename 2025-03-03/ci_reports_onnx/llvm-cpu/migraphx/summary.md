## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.5799326543005554 | |
| migraphx_bert__bert-large-uncased | PASS | 369.9704532821973 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.20284813890854 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5530.206240713596 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.2317819794019 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5054.082360118628 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 404.13933744033176 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.43575461705524 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.72888229148727 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.91463215197577 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.5949981378184 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.01709551860888 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.60297766611689 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 443.0506092806657 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.408724415561426 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.07630473044183 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.5384923683272 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.101283652362994 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.8292117262328 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.21018089912832 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1479.7072894871235 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.03466068373783 | |
| migraphx_torchvision__inceptioni32 | PASS | 5811.258063962062 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.39356293032567 | |
| migraphx_torchvision__resnet50i64 | PASS | 5445.74877495567 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2624.04249732693 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4089.1084199150405 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5979.473541180293 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 190.260149538517 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 301.0190679795212 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 371.5180270373821 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 403.0104161550601 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 631.5445241828759 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 848.3846038579941 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5164.026944587627 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8653.07141219576 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11205.763015896082 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 747.6230015357336 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1110.0887780388196 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1824.3678559859593 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1311.9947550197442 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2167.86607230703 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2903.1880584855876 | |
