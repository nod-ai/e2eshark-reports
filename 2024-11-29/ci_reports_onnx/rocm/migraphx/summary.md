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
| migraphx_bert__bert-large-uncased | PASS | 20.21029771394318 | |
| migraphx_bert__bertsquad-12 | PASS | 20.084104560059952 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.92132618185133 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.70837373979802 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.644695899216458 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.30161888639365 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.522384242953755 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.709026172018 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.58828863917063 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 116.70117472789974 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.98204057110058 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.8730363394134 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.29630070504251 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.24363500423108 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 279.6002575713727 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.47403593281028 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 25.94948427923511 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.467563085964752 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 72.68702643147358 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.978209450347066 | |
| migraphx_torchvision__inceptioni32 | PASS | 146.07724618787566 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 193.16613993335827 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.90193150161455 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.613743205166735 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.5312208612277 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.603245981264477 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 14.399316950147252 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.13253043183968 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.46271517776096 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.956806131172925 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.879926240217173 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.61716157570481 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.04171242662483 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.16876555358368 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.98869343144495 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.76781466905959 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.233937999997764 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.720077917098486 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.829172714419354 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.67498352419352 | |
