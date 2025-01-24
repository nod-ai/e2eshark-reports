## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 78.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.3382911574089 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.041787586931605 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.657880128561278 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.206805228592806 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 176.86249119772887 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.37101233060957 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.63424280975455 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 471.37733549364685 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.58979877929798 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.80531272717934 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.55073877738323 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.07627838050451 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.087383616225754 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.116982828786907 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 61.04067054614212 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.82211387969172 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.903270000254565 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.50722014908332 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.031281514929892 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.743077434563366 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.57638998148333 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.78465406697554 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.212824376968449 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.213154675823525 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 67.31363103172043 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.74081123803762 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 148.78365706730014 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.387142217379903 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.730710182436887 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.281503063661077 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.212566081592858 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.42795293661169 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.60402768635529 | |
