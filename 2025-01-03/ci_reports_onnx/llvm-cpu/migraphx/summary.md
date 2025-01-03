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
| migraphx_bert__bert-large-uncased | PASS | 374.4006771594286 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.40351005643606 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5313.618376851082 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 322.89365865290165 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5191.336092849572 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 394.9628671010335 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 421.08792004485923 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.6613552769025 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.229873175658874 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.55962522824606 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.75997444738944 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.5874306644712 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 307.7635783702135 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.416184370716415 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 93.53091071049373 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.65153232879106 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.71890884417074 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.67304378858317 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 55.10171204805374 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1620.3382797539234 | |
| migraphx_torchvision__inceptioni1 | PASS | 223.59331283304425 | |
| migraphx_torchvision__inceptioni32 | PASS | 5326.207544654608 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.19333388904731 | |
| migraphx_torchvision__resnet50i64 | PASS | 5046.220909804106 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2608.2757487893105 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4163.80605722467 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5818.045329302549 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.06586965421835 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 293.33930172853997 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.47901380558807 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 391.3238849490881 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 580.1326197882493 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 812.851489832004 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5102.063109477361 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8111.594698081414 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11092.182857294878 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 703.6385200917721 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1079.230268796285 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1525.3681354224682 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1334.4667876760166 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2058.3182585736113 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2957.1137142678103 | |
