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
| migraphx_bert__bert-large-uncased | PASS | 19.24202942151438 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.44863108033314 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.21540766954422 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.30399841628969 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 369.79343586911756 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.361320630112226 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.668396167856244 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.93694271861265 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 146.8451277973751 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.24294851436501 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 100.92170525430923 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.94254813343287 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.93592456881052 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.13594131532943 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 295.85695841039217 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.05077733477633 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.415383656170558 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.592705392526032 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.251486454297 | |
| migraphx_torchvision__inceptioni1 | PASS | 64.51941293629783 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.18735363458592 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.36891449731524 | |
| migraphx_torchvision__resnet50i64 | Numerics | 196.17024005856365 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.56166533759811 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 101.25690529174688 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.84367913054302 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.24507197146706 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 21.57133406192158 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.49578765089865 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.673502466218038 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.257693841983127 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 51.37534295338102 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 72.27905869173507 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.05668721575704 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.93687177232155 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.5246787643474 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.27289153718286 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.43957063350349 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.84797499336156 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.41694389548206 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.924018962774426 | |
