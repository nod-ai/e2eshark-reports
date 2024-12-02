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
| migraphx_bert__bert-large-uncased | PASS | 386.8243011335532 | |
| migraphx_bert__bertsquad-12 | PASS | 86.85382005448143 | |
| migraphx_cadene__dpn92i1 | PASS | 200.06482510103118 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7494.0611521403 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 404.86587149401504 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 388.67764361202717 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 423.53869788348675 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.17493376845403 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.131039058168724 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.97617414262558 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.37848214734169 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.07744692100418 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 261.22052470843 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.90471615755196 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.03074635316928 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 263.49711542328197 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 48.725312920632184 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 84.14181832362104 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.60542596204608 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1314.8344804843266 | |
| migraphx_torchvision__inceptioni1 | PASS | 292.7998705870575 | |
| migraphx_torchvision__inceptioni32 | PASS | 6607.301525771618 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.60883015110379 | |
| migraphx_torchvision__resnet50i64 | PASS | 6060.911014676094 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2502.380936096112 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3987.345685561498 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5821.7540209492045 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.07196550567943 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.3757885992527 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.78773286441964 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 377.12097726762295 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 583.7015770375729 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 832.3192099730173 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5133.125362296899 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8104.1159853339195 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11552.13626474142 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 729.3572314083576 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1100.9176385899384 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1678.4699608882268 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1345.2373519539833 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2096.7914710442224 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3071.0390272239842 | |
