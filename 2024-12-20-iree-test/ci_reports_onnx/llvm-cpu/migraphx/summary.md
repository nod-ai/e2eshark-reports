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
| migraphx_bert__bert-large-uncased | PASS | 379.60734590888023 | |
| migraphx_bert__bertsquad-12 | PASS | 86.93987669216261 | |
| migraphx_cadene__dpn92i1 | PASS | 174.4462102651596 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6473.7617547313375 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 398.2593820740779 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5008.305810391903 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 385.3815086185932 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.63932934900123 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.93107395205232 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.399390225845664 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 188.61565324995252 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.27162551737966 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 103.19196202215693 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 252.42249853909016 | |
| migraphx_ORT__distilgpt2_1 | PASS | 36.61931394821121 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.60330074156325 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.44508008162177 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.013534943262734 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 82.90500612929463 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.01473911135805 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1483.6730261643727 | |
| migraphx_torchvision__inceptioni1 | PASS | 214.77947218550574 | |
| migraphx_torchvision__inceptioni32 | PASS | 5868.476054320733 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.88060647958798 | |
| migraphx_torchvision__resnet50i64 | PASS | 5912.537368635337 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2598.791285107533 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3992.7495482067266 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5677.220539500316 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 153.4076670805613 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.88668327530223 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.66546118756133 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 391.6255744795005 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 824.5970954497656 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 805.9478377302488 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5137.549633781115 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8072.032865136862 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11364.13057645162 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 743.1031614542007 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1093.2272523641586 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1519.2573132614295 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1312.76594226559 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2150.185340394576 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2912.1164133151374 | |
