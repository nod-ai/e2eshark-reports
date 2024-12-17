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
| migraphx_bert__bert-large-uncased | PASS | 428.61643495659035 | |
| migraphx_bert__bertsquad-12 | PASS | 89.21399481949351 | |
| migraphx_cadene__dpn92i1 | PASS | 172.06425437082848 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5781.139808396499 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 349.18808937072754 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5184.2997421820955 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1548.6820203562577 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 459.5477692782879 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.14560045922796 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.81758172493992 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.87777491079433 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.79166324365707 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.89298734400006 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 270.9062111874421 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.190887658492375 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.89665034661691 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 285.38514239092666 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 49.244697309202614 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.67598275343578 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.63035677168884 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1629.48598091801 | |
| migraphx_torchvision__inceptioni1 | PASS | 209.24739498231145 | |
| migraphx_torchvision__inceptioni32 | PASS | 5975.700194636981 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.14346871489568 | |
| migraphx_torchvision__resnet50i64 | PASS | 5944.3477764725685 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2564.7951749463873 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4165.904836108287 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5831.320654600859 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.2029696156581 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.8241277784109 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.13201327621937 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 394.56192528208095 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 594.1115642587343 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 803.3526204526424 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5076.452851295471 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7821.269103636344 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12011.161784331003 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 722.2689886887869 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1091.303315013647 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1554.2234107851982 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1285.7194567720094 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2055.106128255526 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2909.0462351838746 | |
