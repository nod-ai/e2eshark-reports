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
| migraphx_bert__bert-large-uncased | PASS | 376.676872993509 | |
| migraphx_bert__bertsquad-12 | PASS | 86.8090625320162 | |
| migraphx_cadene__dpn92i1 | PASS | 171.45566611240307 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5409.033946692944 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 444.21006614963215 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5076.165579259396 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 599.6809278925259 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 420.897309978803 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.77160192103611 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.167886575966165 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 187.72971288611492 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.22799775572048 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.14629595147238 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 258.85767862200737 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.469233334064484 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.51291079695027 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.6227960752116 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.82664838743706 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.73245713280306 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.94110713733567 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1623.3877167105675 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.4299410879612 | |
| migraphx_torchvision__inceptioni32 | PASS | 5335.859663784504 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.41240218033393 | |
| migraphx_torchvision__resnet50i64 | PASS | 4980.449263006449 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2642.9941914975643 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4046.0519889990483 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5557.689507802327 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.48446142425138 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.78711929586194 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.8659339249134 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 456.552742049098 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 584.7978728512923 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 822.7012492716312 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5012.160462637742 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7849.970327069362 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11194.577146321535 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 723.7765491008759 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1091.002388546864 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1506.7096911370754 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1323.965460062027 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2115.81914126873 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2892.878187199434 | |
