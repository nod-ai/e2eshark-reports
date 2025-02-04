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
| migraphx_bert__bert-large-uncased | PASS | 477.5964766740799 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 174.48988681038222 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5724.7323008875055 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.98757645487785 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4967.815397928158 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 419.70753359297913 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 542.2536718348662 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.72999812591644 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.38240915040174 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 187.2774991724226 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.39646250837377 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.13531670400074 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 308.68030401567614 | |
| migraphx_ORT__distilgpt2_1 | PASS | 70.53199050327142 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.0397546576957 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 287.95592424770194 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.48385866048435 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.11616024002433 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 51.58045602341492 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1502.4443070093791 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.37706411878267 | |
| migraphx_torchvision__inceptioni32 | PASS | 5808.837100863457 | |
| migraphx_torchvision__resnet50i1 | PASS | 93.80501477668683 | |
| migraphx_torchvision__resnet50i64 | PASS | 5398.191017409165 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2935.233631481727 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4609.976987044016 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6184.350894143184 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.3293093095223 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.5323017388582 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 396.0953541100025 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 406.82688045005006 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 588.4590794642766 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 874.3804904321829 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5527.509642144044 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8366.275717814762 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11201.940127958855 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 834.4431842366854 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1083.0095075070858 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1527.4691991508007 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1360.8076845606167 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2184.741699447234 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2910.7285564144454 | |
