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
| migraphx_bert__bert-large-uncased | PASS | 379.4028678288062 | |
| migraphx_bert__bertsquad-12 | PASS | 88.11632490583828 | |
| migraphx_cadene__dpn92i1 | PASS | 178.38852681840459 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6830.452521642049 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 331.2210328876972 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 420.424656321605 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 456.40138039986294 | |
| migraphx_mlperf__resnet50_v1 | PASS | 134.71676515681403 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.420290959259816 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 195.74223645031452 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.76908874227887 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 96.14410020765803 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 274.3764429663618 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.027232472231418 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.55332962754699 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.60041606674588 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.88922691376259 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 72.59944348285596 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.48351938525837 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1342.6501099020243 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.61679702831637 | |
| migraphx_torchvision__inceptioni32 | PASS | 6634.186757728457 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.75122806926568 | |
| migraphx_torchvision__resnet50i64 | PASS | 6058.885213608543 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2707.4504333237805 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4157.014213502407 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5896.730047340195 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.3840016759932 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 271.304485698541 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 368.94241720438004 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 393.0290127173066 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 667.2954497238001 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 839.8719088484844 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5359.545356904467 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8374.723409612972 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11802.214321990808 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 731.2783480932316 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1112.8251142799854 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1585.272587214907 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1333.6263646682103 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2235.4847987492876 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3169.719463214278 | |
