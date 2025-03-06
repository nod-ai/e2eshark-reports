## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.051910541289074 | |
| migraphx_bert__bert-large-uncased | PASS | 18.92984646943037 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.040318201451251 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.48029876440867 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.250688273206925 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.00561980719584 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.331444376110756 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.641154813484693 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.797319370996336 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.70563077100087 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.64552446144322 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.62412460624343 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.90258959908452 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 453.68099728754413 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.0260192877613 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.134708455904864 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.3712195555369 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.43190175651883 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.286311151702105 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.792282216084474 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.181358539682424 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.889734267231284 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.17975881509483 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.6002749025269787 | |
| migraphx_torchvision__resnet50i64 | PASS | 21.042962144646378 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.29551155265006 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.819952675929436 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 72.03559271680811 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.315226346517434 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.662411205830018 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.251378421257765 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.806037147388311 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.351493094807617 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.05373513151073 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.71224692554183 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 100.63093122360961 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 142.4619017013659 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.652150154088424 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.174011587889655 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.694446301915576 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.45683724221049 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.47641639927259 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.425173824141716 | |
