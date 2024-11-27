## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.186829466062285 | |
| migraphx_bert__bertsquad-12 | PASS | 18.57308509560036 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 152.73698098802316 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 215.15568221608797 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.4966038543043325 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 42.7258094738742 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.458900429932144 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.21237018111754 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.354124058276795 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 113.45051077660173 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.80762433974694 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 367.27968166815117 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.7419544171937 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.17791733176757 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.0232986656742 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.08855247054318 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.302124051687617 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 11.432708543277561 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 52.1609509566751 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.930761749835007 | |
| migraphx_torchvision__inceptioni32 | PASS | 142.96255986361453 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 189.17033789330162 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.564094343178326 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.92238763468857 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.26569417879605 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.581394408202657 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.966911897684135 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.01157965222817 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.406855032558388 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.086996594754355 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.62954267623718 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.37788010497266 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.73657805760877 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 145.1789892744273 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.01678135031372 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.487722371394433 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.67258664195498 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.106119354299846 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.05427430042376 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.38113379332365 | |
