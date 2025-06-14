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
| migraphx_bert__bert-large-uncased | PASS | 367.5604657425235 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 189.8454762995243 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5434.504031824569 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 343.23418714726967 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.8135137980183 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 466.1142876526962 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.9914266853815 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.3030569665134 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.1228211712506 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 69.83294507436868 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.25922003896067 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1511.4868491267164 | |
| migraphx_torchvision__inceptioni1 | PASS | 215.64188017509878 | |
| migraphx_torchvision__resnet50i1 | PASS | 103.62199665091576 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1518.7545136238139 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5129.530534458657 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9392.828953607628 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 149.41324724350125 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 255.48767991777922 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 362.2893492380778 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.2300176434219 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 433.2254669473817 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 657.9012642614543 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4906.169081572443 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13474.468771833926 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23017.45972254624 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 409.00557798643905 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 793.2275493318836 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1229.6132372381785 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 735.8480206069847 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1661.9653853898246 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3344.50203506276 | |
