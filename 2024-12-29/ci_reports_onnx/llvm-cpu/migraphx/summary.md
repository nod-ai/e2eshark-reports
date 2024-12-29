## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 370.8576572438081 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 175.3930076956749 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5526.951115578413 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 324.64596442878246 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5147.97118678689 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 374.07342592875165 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 418.6285734176636 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.02159396665435 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.066336070949376 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.17579412460327 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.3601289377326 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.56966703988256 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 283.8232057789961 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.44648514580035 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 83.74619546035926 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.79313789804777 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.76473617553711 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.50661626347788 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.96227707114875 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1507.6316210130851 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.62776910265288 | |
| migraphx_torchvision__inceptioni32 | PASS | 5741.284598906835 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.72540216644605 | |
| migraphx_torchvision__resnet50i64 | PASS | 5916.535906493664 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2635.23742929101 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4166.580596317847 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5892.493827889363 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.3619278470675 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.9988173676862 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.811261271437 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 380.9713292866945 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 595.8972846468289 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 810.922467460235 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4978.02834585309 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7982.990380376577 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11366.008004794518 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 714.4057589272658 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1166.572636614243 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1534.7671297689278 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1348.0229750275612 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2113.1010117630162 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3035.895852992932 | |
