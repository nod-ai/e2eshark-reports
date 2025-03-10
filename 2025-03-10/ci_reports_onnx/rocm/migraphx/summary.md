## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 95.3% |
| Inference Comparison (PASS) | 35 | 74.5% | 85.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.0538796015325365 | |
| migraphx_bert__bert-large-uncased | PASS | 18.90833164865089 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.076527329998346 | |
| migraphx_cadene__inceptionv4i16 | PASS | 30.035051666663055 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.426830564101658 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.395087028981482 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.985308663366286 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.483255217949438 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.987354400001701 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.55558552083257 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.287588688894886 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compiled_inference | None | |
| migraphx_ORT__bert_base_uncased_1 | compiled_inference | None | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 488.2958111666748 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.607791999997296 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.78826627273213 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.42123822220967 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.16365833333389 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.268100972977162 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.394777156623315 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.150583543851887 | |
| migraphx_torchvision__inceptioni1 | PASS | 5.057297023333831 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.10505920000196 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.7199997413512715 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.843573892164514 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.452483523793035 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.43711531579688 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.539488333355216 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.077858632178975 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.463245602341283 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.07402382882972 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.554153499999238 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.84084196396199 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.445197407403864 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 35.81886071665773 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.40116006667085 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 112.5933844999862 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.05603902778281 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.895560142863577 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.259772155549598 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.075002342851107 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 25.96617137036738 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.98087179363724 | |
