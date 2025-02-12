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
| migraphx_bert__bert-large-uncased | PASS | 377.46303776899975 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 213.17046973854303 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5589.887630194426 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 327.6704040666421 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5447.6033834119635 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 396.71681200464565 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 853.1962881485621 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.3097431602932 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.7718961193706 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 190.87319200237593 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.45714932431777 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.26368986424944 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.83057481547195 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.90222094979202 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.36107325057189 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 285.6893427670002 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.42998532343793 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.66628606893397 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.64520959866544 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1459.854560593764 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.6343660056591 | |
| migraphx_torchvision__inceptioni32 | PASS | 5760.16525303324 | |
| migraphx_torchvision__resnet50i1 | PASS | 92.51699596643448 | |
| migraphx_torchvision__resnet50i64 | PASS | 5547.348069647948 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2568.8803444306054 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4150.913727780183 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5750.3373970588045 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 196.59525031844774 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 267.78625365760587 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 397.7101556956768 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 413.41678239405155 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 581.1753794550896 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 861.5293527642885 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5280.367949356635 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8791.427080829937 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12055.738863845667 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 727.5331281125546 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1073.8776351014772 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1538.3225257198017 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1499.431349337101 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2195.465906212727 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2859.1175228357315 | |
