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
| migraphx_bert__bert-large-uncased | PASS | 368.6304943015178 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 177.30810679495335 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5521.259958545367 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 568.5280126829941 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5170.726104329029 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 379.7214205066363 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 415.422551954786 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.63726770505309 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.25675891836484 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 201.6066999899016 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.7059878295376 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.81950107500666 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.93621871868768 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.081499259972915 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.49862984485095 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 245.36899270282848 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.247784184085 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 86.33619484802087 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.026103879635535 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1533.7310830752056 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.1551800171534 | |
| migraphx_torchvision__inceptioni32 | PASS | 5820.269933591287 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.75996494417389 | |
| migraphx_torchvision__resnet50i64 | PASS | 5948.989844570558 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2489.176833381255 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4102.51852000753 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5839.845585326354 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.74560668816167 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.8511402375168 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 403.27492728829384 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 400.1147747039795 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 602.7569013337294 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 806.233499199152 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5110.604350765546 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7962.2743626435595 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11268.855697164932 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 694.1704067091147 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1137.2264735400677 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1529.1398453215759 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1346.1327391366165 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2088.8535442451634 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2900.3512238462768 | |
