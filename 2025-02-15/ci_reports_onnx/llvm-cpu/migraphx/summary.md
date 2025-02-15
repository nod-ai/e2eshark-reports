## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 34 | 72.3% | 79.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.4694097141424816 | |
| migraphx_bert__bert-large-uncased | PASS | 383.2235913723707 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 179.6936703224977 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5536.544058471918 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 332.94599006573355 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5494.114960233371 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 400.4678347458442 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 422.8954625626405 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.29543414286202 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.350781036274775 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 177.94640082865953 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 95.08508727664037 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.49858470048224 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.99253637260858 | |
| migraphx_ORT__distilgpt2_1 | Numerics | 31.5038521328698 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 316.2643528646893 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.3779060294231 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.95336026505187 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 89.11298781081483 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.12883654623119 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1460.0443914532661 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.67730757345757 | |
| migraphx_torchvision__inceptioni32 | PASS | 5680.595035354297 | |
| migraphx_torchvision__resnet50i1 | PASS | 104.4427181283633 | |
| migraphx_torchvision__resnet50i64 | PASS | 5448.626854767402 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2539.2707735300064 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4374.17326743404 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5938.0421961347265 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 171.27516958862543 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 274.7338327268759 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.336833824714 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 413.3772471298774 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 654.5838316281636 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 863.0398847162724 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5479.547239840031 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8957.889029135305 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12253.003526479006 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 732.1593873202801 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1129.2089348038037 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1680.810881157716 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1339.8557640612125 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2104.6647876501083 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3222.4395920832953 | |
