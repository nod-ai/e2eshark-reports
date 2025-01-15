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
| migraphx_bert__bert-large-uncased | PASS | 381.65176659822464 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.27205832468135 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5283.627149959405 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 346.5700739373763 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5084.28605645895 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 376.22895278036594 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.0421527326107 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.51493529478707 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.98233914251129 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.40754894415537 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.58590602590924 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 94.41512988673315 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 289.0241748342911 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.99026143929314 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 82.76079734787345 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 242.24158997337022 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.66116633597347 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.364982407954 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 52.521074345956244 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1577.203559378783 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.02106681466103 | |
| migraphx_torchvision__inceptioni32 | PASS | 5423.68346452713 | |
| migraphx_torchvision__resnet50i1 | PASS | 96.66585301359494 | |
| migraphx_torchvision__resnet50i64 | PASS | 5036.675222218037 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2508.3560695250826 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4171.528356770674 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5748.496577143669 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.11807050804296 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.5097809185584 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.3087195158005 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 387.8871730218331 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 660.4135173062483 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 854.0565595030785 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5224.267990638812 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8060.103674729664 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12034.947774062553 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 708.5992768406868 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1151.9038466115792 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1622.0536567270756 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1303.2080580790837 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2061.5355434517064 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2908.0850606163344 | |
