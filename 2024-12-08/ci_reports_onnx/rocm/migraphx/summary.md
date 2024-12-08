## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.078415436936275 | |
| migraphx_bert__bertsquad-12 | PASS | 18.21747132410424 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 163.09455031296238 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 189.65022801421583 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.841548893512004 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.30436463565343 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.420267255270471 | |
| migraphx_models__whisper-tiny-decoder | PASS | 49.80785409653825 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.02694462574063 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.59647106089524 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.23350948623072 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 528.9888085486988 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.26383977445463 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.1062929379669 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 277.0113116130233 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.00463109323755 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 23.59179879228274 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 11.605691520327872 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 73.88335973438289 | |
| migraphx_torchvision__inceptioni1 | PASS | 19.351110642741396 | |
| migraphx_torchvision__inceptioni32 | PASS | 140.9466051341345 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 170.16149391808236 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.499141966768846 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 61.44283151705607 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.21420193822294 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.589379789594275 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.837374150266053 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.926497133980906 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.501170148046162 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.843313640202668 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.171574518627796 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.5672909921656 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 110.93468028896798 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 154.60086877768236 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.993895267041912 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.190284657618427 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 28.114589241643742 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.940786109992647 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.584242079484586 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.83591963657333 | |
