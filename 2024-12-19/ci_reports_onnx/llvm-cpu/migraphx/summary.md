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
| migraphx_bert__bert-large-uncased | PASS | 408.0634682128827 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 176.03186052292585 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5561.265063782533 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.1710801422596 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 6000.823842982451 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 380.58141246438026 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 449.90031855801743 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.97961136414891 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.77636557533627 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 187.49093543738127 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.26222283641495 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.77319669439679 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 537.5107613702614 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.586199322040528 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.41727670530479 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.47988725701967 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.32525436492528 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 88.43399149676164 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.90167107243163 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1556.1634935438633 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.09812168611418 | |
| migraphx_torchvision__inceptioni32 | PASS | 5804.125948498647 | |
| migraphx_torchvision__resnet50i1 | PASS | 116.38623103499413 | |
| migraphx_torchvision__resnet50i64 | PASS | 5929.389335215092 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2549.4897676010924 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4151.844954739014 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5727.784359206756 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.84539623806873 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.03088346785967 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 377.8407722711563 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 386.0178031027317 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 605.5564309159914 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 806.2689105669657 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5074.92654149731 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8129.214437057573 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11256.718357404074 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 722.7383106946945 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1102.7148440480232 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1552.4994196991127 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1282.9960597058136 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2069.771255056063 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3005.51800057292 | |
