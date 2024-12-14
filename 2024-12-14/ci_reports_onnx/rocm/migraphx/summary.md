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
| migraphx_bert__bert-large-uncased | PASS | 19.499658326687356 | |
| migraphx_bert__bertsquad-12 | PASS | 8.12886456162276 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 159.5219847707388 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 185.27159440175942 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.23003810015587 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.115682708927327 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 6.140183539630855 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.06113783301165 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.78757978189322 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 97.89606641667582 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.32379446985819 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 494.03891297212493 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.98881612789063 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.580157069715135 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 263.8972769750075 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 30.922646998711254 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 14.56873858981627 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.014523049040386 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 71.72793740561852 | |
| migraphx_torchvision__inceptioni1 | PASS | 18.945065224207603 | |
| migraphx_torchvision__inceptioni32 | PASS | 136.86132522610328 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 166.13489461209002 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.77631938247571 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.97171880092679 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.96916665695608 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.113591396019872 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.315118742380408 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.43429833476397 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.89690964148138 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.510054257961038 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.359029044914575 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.58950213249773 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 106.98943713768607 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 149.11438537140688 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.49034498040823 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.273352093373735 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.683125958348125 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.86494896441905 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.20092418851952 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.84767962250786 | |
