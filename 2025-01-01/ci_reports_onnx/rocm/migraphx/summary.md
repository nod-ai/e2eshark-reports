## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.291083837203953 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.71429262007587 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.33368488276997 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.28060638718307 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 363.74816996976733 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.273897031943004 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.959471999357138 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.87169446666089 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 141.97926862786213 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.81405752755346 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.89453512909155 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.3136301897466 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.49105883700151 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.300122066203386 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 290.86838228007156 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.229588783521578 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.07203698190658 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.76653293435866 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 75.39009304579209 | |
| migraphx_torchvision__inceptioni1 | PASS | 39.687905753790226 | |
| migraphx_torchvision__inceptioni32 | PASS | 98.78585649476872 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.350118687817004 | |
| migraphx_torchvision__resnet50i64 | Numerics | 188.97063378244638 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.366550770898655 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.39901746043728 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.24874151056562 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.03572693184294 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.33082036507673 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.476613650719326 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.657780003445666 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.201652750747757 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.70539713794521 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.81522963320215 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 113.28913571519983 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.03876809372255 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.252144235129258 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.657059784202527 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.697893018046248 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.225836097129754 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.698221465676195 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.412355036707595 | |
