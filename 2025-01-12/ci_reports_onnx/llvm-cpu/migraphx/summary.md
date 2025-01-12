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
| migraphx_bert__bert-large-uncased | PASS | 376.767339805762 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 180.7197779417038 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5298.774737864733 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.10305506487686 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5169.2460787793 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.27273474633694 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 419.92363644142944 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.17543119475954 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.18962020720496 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.4442579547564 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 94.59102366651808 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.16176948518978 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 307.5093347579241 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.26338067831415 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 90.86105599999428 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 255.5001750588417 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.26479432341598 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.92013575743745 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.79532913925747 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1571.253312130769 | |
| migraphx_torchvision__inceptioni1 | PASS | 200.91150607913733 | |
| migraphx_torchvision__inceptioni32 | PASS | 5393.381113807361 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.04293595130245 | |
| migraphx_torchvision__resnet50i64 | PASS | 5158.796527733405 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2621.6992375751333 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4152.823078135649 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6013.102625807126 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 157.88158898552257 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 268.20741138524477 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 391.8160671989123 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 388.2296544810136 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 582.4515670537949 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 868.6022162437439 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5299.6859451135 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8065.276131033897 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11359.361028919617 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 711.9371940692266 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1079.8958602050939 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1636.9526100655396 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1317.80306994915 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2077.084396034479 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2850.358199328184 | |
