## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 844.0105669821302 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 178.9237060584128 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5156.42913710326 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.4802109748125 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 453.09477113187313 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 425.6060665162901 | |
| migraphx_mlperf__resnet50_v1 | PASS | 86.73757365128647 | |
| migraphx_models__whisper-tiny-decoder | PASS | 69.92329150024388 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 211.06999605480166 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.56361502305501 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.99575283109873 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1442.0175589621067 | |
| migraphx_torchvision__inceptioni1 | PASS | 212.87183153132597 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.11980522113542 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1557.584219922622 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5172.8401677683 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9523.283171157042 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 306.3556492949525 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.2113412030869 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 456.751624122262 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 258.94063773254555 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 434.4229685763518 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 665.2960895250241 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5165.155774913728 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13798.161390858391 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24045.84048036486 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 433.87920890624326 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 800.6763731439909 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1241.9230345015724 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 786.1218995725116 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1663.6505564674735 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3444.8753107960024 | |
