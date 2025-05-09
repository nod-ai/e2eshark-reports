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
| migraphx_bert__bert-large-uncased | PASS | 614.467305849151 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 179.08572564677647 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6109.3182520320015 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 310.9492804893913 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 552.5980243304123 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 458.4913333528675 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.0868199129722 | |
| migraphx_models__whisper-tiny-decoder | PASS | 58.21936552658573 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.79428956605906 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.634747159279264 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.401342057614798 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1434.1501319625725 | |
| migraphx_torchvision__inceptioni1 | PASS | 231.16205330976905 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.05583000017536 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1553.5280323432137 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5567.328494042158 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9380.792519659735 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.17126357896873 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.8100801179599 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.65666434339556 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.67108719423413 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 455.08783784074086 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 653.9793356787413 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5092.636794627954 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13539.080602660155 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23442.48884326468 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.6568413466836 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 791.4452553183461 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1307.9713397116088 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 807.7893426331381 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1794.7017647481214 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3357.6152006474636 | |
