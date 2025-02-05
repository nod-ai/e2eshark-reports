## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.03048844017961 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.29877732440152 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.385745457603516 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.956475174675385 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.57604097217029 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.202887978424165 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 117.84890551740922 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 109.50264633477975 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 476.77056132427725 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.55760282166819 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.742382522446626 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 271.57305888572915 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.366260150757924 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.350615423101072 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.042551311995033 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.854962071854929 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.28193915963527 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.56199116668163 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 80.79843458081423 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.982928472176447 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 14.323350555282467 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.07526295179048 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.740126625408953 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.241792903076737 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 34.6923632256221 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.39864247788985 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 103.76376691939574 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 146.44501971391338 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.306203365170708 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.919694733732037 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 144.6119436412118 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.52660665955153 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.769151013619148 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 82.24217131113012 | |
