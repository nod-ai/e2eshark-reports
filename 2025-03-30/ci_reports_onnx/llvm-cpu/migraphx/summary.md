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
| migraphx_agentmodel__AgentModel | Numerics | 1.2935359700027431 | |
| migraphx_bert__bert-large-uncased | PASS | 371.2269912163417 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.69029879570007 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5416.6560259958105 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 327.887333308657 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5031.099361677964 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 407.4029040833314 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 469.8181288937728 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.68803635949178 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.07932372571844 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.12545419070454 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.47465246253542 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.15844440885952 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 261.3018297900756 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.175820835690566 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.99108850790394 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 247.05154283179175 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 44.938854581000754 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 62.71142522907919 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 24.642349757028352 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1474.9532764156659 | |
| migraphx_torchvision__inceptioni1 | PASS | 199.03230418761572 | |
| migraphx_torchvision__inceptioni32 | PASS | 5907.064768175284 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.82237407689293 | |
| migraphx_torchvision__resnet50i64 | PASS | 5434.427493562301 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1478.1495804588 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2998.962137848139 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4796.065970013538 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 164.52098886171976 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 282.08574321534894 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.9170485287905 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 244.72715291712018 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 430.5294640362263 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 660.7148187855879 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2868.223924189806 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5992.419144759576 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9124.206596364576 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 555.795698116223 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1076.529923826456 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1273.4958827495575 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 753.6251929899057 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1547.7796954413254 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2468.1897486249604 | |
