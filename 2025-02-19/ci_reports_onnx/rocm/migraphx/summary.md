## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 25 | 53.2% | 71.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 10 | 21.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.141433392093543 | |
| migraphx_bert__bert-large-uncased | PASS | 19.3167832848202 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.410752284255274 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.69109873507387 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.248407476353653 | |
| migraphx_models__whisper-tiny-decoder | PASS | 47.999676355781645 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.20566692870731 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 121.04735738830641 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 134.64398021137134 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 550.8144149401535 | |
| migraphx_ORT__distilgpt2_1 | PASS | 71.80909153733712 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 65.35455245510532 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.3940922189504 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 180.905413988512 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.31980689386687 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 11.327696945539516 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 5.516829918573809 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.37862005176407 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.38588364083225 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.7984827379696 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.008452596194628 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.99000279724192 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.417358299406867 | |
| migx_bench_bert-large-uncased_2_128 | Numerics | 25.824541963326435 | |
| migx_bench_bert-large-uncased_2_256 | Numerics | 73.29620903757855 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.564946245537914 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.3544087029683 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 102.73383713571263 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.15721537948895 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.189391945601036 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.717626302200774 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.495462347158334 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.81275065487285 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.50619321028726 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.91916649385045 | |
