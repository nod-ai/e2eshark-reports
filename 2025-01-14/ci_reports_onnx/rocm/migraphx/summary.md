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
| migraphx_bert__bert-large-uncased | PASS | 19.32080287520808 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.61856011968727 | |
| migraphx_cadene__inceptionv4i16 | PASS | 156.36649797670543 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 118.08827395240466 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 392.60368530328077 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.367155285060612 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.75634196923039 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.72704502443472 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 141.72532589485246 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.45276713938938 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.082010372054 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 503.13577118019265 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.35818111380706 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.04459177860707 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 297.4354390365382 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.32485043223608 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.516861168624358 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.748383350402506 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 74.6613463938788 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.09807595537574 | |
| migraphx_torchvision__inceptioni32 | PASS | 107.67512339063815 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.179091229642692 | |
| migraphx_torchvision__resnet50i64 | Numerics | 153.6948726667712 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.48092899994369 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 317.5767974815133 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.66297276814778 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.07406954260336 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.33274573978013 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.44942285168778 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 21.936766193470074 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.359861653415287 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.926555472115677 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.10630561163028 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.75076547099484 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 164.3660591604809 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.412368774464746 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.223758014794598 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.317956281013977 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.740025685917512 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.580721741569217 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.80308022660514 | |
