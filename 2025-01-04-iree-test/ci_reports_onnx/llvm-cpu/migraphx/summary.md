## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 372.8474223365386 | |
| migraphx_bert__bertsquad-12 | PASS | 88.48770288750529 | |
| migraphx_cadene__dpn92i1 | PASS | 170.5802921205759 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6135.457693288724 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.5874616851409 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5088.849750657876 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 384.8776649683714 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.82499542832375 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.61599604004903 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.82809125809442 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.5746993223826 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 96.99762736757596 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 94.8757566511631 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 269.4993826250235 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.02008693055673 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.3164985999465 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.06874034139844 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.52262212556821 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.16837855676809 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.03392063577971 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1608.8869447509448 | |
| migraphx_torchvision__inceptioni1 | PASS | 202.3287241657575 | |
| migraphx_torchvision__inceptioni32 | PASS | 5366.664799551169 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.8539543201526 | |
| migraphx_torchvision__resnet50i64 | PASS | 4973.933660735686 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2595.9210855265455 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4034.0855307877064 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5656.14324559768 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.42152881870666 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 257.726295126809 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.8285463253657 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 391.05095093448955 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 585.645504295826 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 809.8717331886292 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4949.824023991823 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7960.196619232495 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11258.00065199534 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 718.2766459882259 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1067.5878760715325 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1561.2211724122365 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1319.4354598720868 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2041.0108715295792 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2931.764218956232 | |
