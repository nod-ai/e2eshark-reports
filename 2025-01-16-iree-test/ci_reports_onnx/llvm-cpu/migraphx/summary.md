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
| migraphx_bert__bert-large-uncased | PASS | 375.87555187443894 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 173.2807413985332 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5337.361627568801 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.716222162048 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5099.228923519452 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.41488577922183 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 474.67110492289066 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.63027019633186 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.305424412091575 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.38137588236066 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.7067216308344 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.19218580353828 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.44956346352893 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.665718239365194 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.49848851685722 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 261.22432822982466 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.59959575358559 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 222.02003772060075 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 51.57407166229354 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1576.1168338358402 | |
| migraphx_torchvision__inceptioni1 | PASS | 194.10034331182638 | |
| migraphx_torchvision__inceptioni32 | PASS | 5348.836043228705 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.88521517978774 | |
| migraphx_torchvision__resnet50i64 | PASS | 5089.055258780718 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2659.0231793622174 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4070.6536074479422 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5796.774532645941 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 169.9531472598513 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 275.26073281963664 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 375.88221455613774 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 388.0458374818166 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 646.1055899659792 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 840.048611164093 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5042.731806635857 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8492.403481155634 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11224.796310067177 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 712.1993452310562 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1074.8798636098702 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1563.6368704338868 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1330.6109445790448 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2081.3202373683453 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2886.0003712276616 | |
