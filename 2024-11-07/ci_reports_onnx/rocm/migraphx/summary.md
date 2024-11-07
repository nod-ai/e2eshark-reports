## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 37 | 78.7% | 92.5% |
| Inference Comparison (PASS) | 31 | 66.0% | 83.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 3 | 6.4% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.00752826043892 | |
| migraphx_bert__bertsquad-12 | compiled_inference | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.39956109039483 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 216.44490333791407 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.01388472924009 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 38.858088280971124 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.501453129072037 | |
| migraphx_models__whisper-tiny-decoder | PASS | 28.171010467404912 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.67912609120592 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.31600069347769 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 112.45581988866131 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 364.51451647250605 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 71.75335033486286 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.63919399471746 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 72.73477086952576 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.26083556505608 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 49.438576413584606 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.03955717935649 | |
| migraphx_torchvision__inceptioni32 | PASS | 130.7468313102921 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 203.57706265834472 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 30.010059495301295 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 54.23071201389226 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.27319156719992 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.524113730408061 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 14.221893252494432 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.887256378396636 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.980525767039735 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.54175474299909 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.466449257180404 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 61.39387932577819 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 155.08045461250555 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 138.2825030013919 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.244210255351298 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.872198282120127 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.106531588061724 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.450160614999106 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 47.849664418601684 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.92730475255046 | |
