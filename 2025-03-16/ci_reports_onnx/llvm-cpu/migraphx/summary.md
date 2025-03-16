## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.0565690703742574 | |
| migraphx_bert__bert-large-uncased | PASS | 368.19728774329025 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.5718418682615 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5546.953023721774 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.1281918485959 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4968.3000308771925 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.4075859536727 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 433.99504634241265 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.74905802806217 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.74360971034519 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 196.61279395222664 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 102.04988055759004 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 97.25632270177205 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 254.46341248850024 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.9234462368722 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.20396877328555 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 278.581701633003 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.104288064771225 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 92.21032075583935 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.27954020765092 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1507.27899496754 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.86277867108583 | |
| migraphx_torchvision__inceptioni32 | PASS | 5723.264556378126 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.53585185979803 | |
| migraphx_torchvision__resnet50i64 | PASS | 5416.842022289832 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1481.786201397578 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3080.0038278102875 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4799.196920047203 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.3840231820941 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 269.59620871477654 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 359.816928083698 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 239.24906593230034 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 428.7239344169696 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.5285379985968 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2806.417635331551 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5955.038972198963 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9180.818473299343 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 406.07852675020695 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 811.0931441187859 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1250.0325279931226 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 746.2524349490801 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1511.3481481870015 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3034.1496728360653 | |
