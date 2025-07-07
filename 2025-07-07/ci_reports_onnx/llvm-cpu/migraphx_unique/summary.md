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
| migraphx_bert__bert-large-uncased | PASS | 615.297268765668 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 170.12731808548173 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5419.445551310976 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.99175091832876 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 409.2947264822821 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.893028439333 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.91394304980832 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.618029691554874 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 213.302926470836 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.46969088270432 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.496681376936888 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1433.5328579569857 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.25790586322546 | |
| migraphx_torchvision__resnet50i1 | PASS | 105.5576077972849 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1610.1155746728182 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5271.17957547307 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9330.985558529694 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.65796736255288 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.2407309065262 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 439.05779377867776 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.74271650695138 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.9732660787801 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 664.105203313132 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5180.651673736671 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13576.71035733074 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23980.49709604432 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 516.9534644422431 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 799.7317956760526 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1267.2696594769754 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 765.1608729114135 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1624.1111957157652 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3553.0017636095486 | |
