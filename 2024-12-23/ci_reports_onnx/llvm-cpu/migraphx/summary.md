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
| migraphx_bert__bert-large-uncased | PASS | 404.01181019842625 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 171.06320646901926 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5674.248254547517 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.80172358453274 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5188.777117679516 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.8405273507039 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 615.0844643513361 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.51872864862283 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.23008474849519 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 197.06630996531908 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 91.96506171590751 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.8482964507171 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.1904248197873 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.506527580466926 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.92606530752447 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.75376242399216 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.36262817680836 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.52576721376842 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.92930865287781 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1481.098232169946 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.59071926275888 | |
| migraphx_torchvision__inceptioni32 | PASS | 5786.96483746171 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.83266586916785 | |
| migraphx_torchvision__resnet50i64 | PASS | 5937.408608694871 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2741.5057867765427 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4038.2567134996257 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5797.982085496187 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 320.2883231764038 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.7635234793027 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 368.0642346541087 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 400.24595086773235 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 596.3193116088707 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 828.2750472426414 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5221.457462757826 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8206.613077471653 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11264.989527563253 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 719.0820301572481 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1126.6968908409276 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1579.0317145486672 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1283.7214755515256 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2104.290311535199 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2988.8713185985885 | |
