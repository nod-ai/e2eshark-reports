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
| migraphx_bert__bert-large-uncased | PASS | 20.288218600520242 | |
| migraphx_bert__bertsquad-12 | PASS | 19.945303923266597 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 154.77873220418888 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 218.67440600180998 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.670539190850989 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 42.24404856480154 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.480408263704612 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.59702584944721 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.80008753705531 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.78656883729207 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.51095394275357 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 367.17946782785776 | |
| migraphx_ORT__distilgpt2_1 | PASS | 67.47885982357812 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.04601339856161 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 280.71567710463165 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.11792821841606 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 22.50175247761598 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 14.530453570764195 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 52.979015979545714 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.804868500157623 | |
| migraphx_torchvision__inceptioni32 | PASS | 145.02858978618556 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 193.4539318269041 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.800802204214655 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.99587666236847 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.71135003645732 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.536238064541697 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.80805720862768 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.543266683706037 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.445528067397673 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 14.001448242537053 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.840973471019726 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.717719710432 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.36477024159171 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.5961914702008 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.13272309017813 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.949351354521543 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.31246067112527 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.43194838174089 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.969518730365152 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.65466429084578 | |
