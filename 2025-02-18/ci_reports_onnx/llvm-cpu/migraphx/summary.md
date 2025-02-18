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
| migraphx_agentmodel__AgentModel | Numerics | 1.2685263834933125 | |
| migraphx_bert__bert-large-uncased | PASS | 576.516938706239 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.80606902142364 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5563.864044845104 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.06068119903404 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5804.856065660715 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 406.04909261067706 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 436.73656570414704 | |
| migraphx_mlperf__resnet50_v1 | PASS | 99.8886844941548 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.38081317372394 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 210.25905716750356 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 92.62681131561595 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.35315440470974 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.9632373700539 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.05133414674889 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.33992886543274 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 493.27899391452473 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.58246708968107 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.70463005922458 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 38.40336251865934 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1530.4908889035385 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.83325462291637 | |
| migraphx_torchvision__inceptioni32 | PASS | 5859.114916374286 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.71080551296473 | |
| migraphx_torchvision__resnet50i64 | PASS | 5367.455210536718 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2557.925458997488 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4087.069240709146 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5591.276234636704 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 164.56478058050075 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 286.07419691979885 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 383.95883329212666 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 384.95304621756077 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 617.2624168296654 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 871.5606890618801 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5227.480510870615 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8023.459866642952 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11498.898450285196 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 935.8841764430205 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1180.6250351170697 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1969.2587529619534 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 3127.054814249277 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2085.7149213552475 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2989.9097656210265 | |
