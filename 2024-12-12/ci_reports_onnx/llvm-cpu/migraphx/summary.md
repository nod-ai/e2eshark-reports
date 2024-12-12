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
| migraphx_bert__bert-large-uncased | PASS | 558.4920607507229 | |
| migraphx_bert__bertsquad-12 | PASS | 93.25601000870978 | |
| migraphx_cadene__dpn92i1 | PASS | 348.37569668889046 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5484.3058089415235 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 573.7001430243254 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5176.40749985973 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 405.53852667411167 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1738.8382516801357 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.56597357278777 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.660603353923015 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.50322760144869 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.42861512675881 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.1995682432538 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 269.51543862620986 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.65481272339821 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.27578800668319 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.03781724969545 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 50.482093619230476 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 87.7137535976039 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.891814494505525 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1557.430340598027 | |
| migraphx_torchvision__inceptioni1 | PASS | 295.9094184140364 | |
| migraphx_torchvision__inceptioni32 | PASS | 5435.830369591713 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.77939821407199 | |
| migraphx_torchvision__resnet50i64 | PASS | 5282.4590392410755 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2653.2990634441376 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4125.632567952076 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6253.610221048196 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 177.17560846358538 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 288.6713991562525 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 393.4843639532725 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 441.0320147871971 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 609.7101097305615 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 813.7400696674982 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5090.416384239991 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8847.920009245474 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11651.953406631947 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 716.4382971823215 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1209.4684864083924 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1644.076065470775 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1459.8132831354935 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2096.8997279802957 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2966.671511530876 | |
