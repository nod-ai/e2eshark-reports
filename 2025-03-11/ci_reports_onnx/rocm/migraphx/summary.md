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
| migraphx_agentmodel__AgentModel | Numerics | 1.975644891839744 | |
| migraphx_bert__bert-large-uncased | PASS | 18.993386062861603 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.461378949958637 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.295260513309685 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.256098123775537 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.713298027773916 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.08318282656061 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.360878862874625 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.777684548482733 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.00558591199418 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.747322600114984 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.00867647597276 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.40982672056674 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 458.07773449632805 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.81609449837318 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.98475060681458 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.5073710019157 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.84112680884307 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.157462220557594 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.953201504024883 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.016716528909765 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.906333213640068 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.103749852743928 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.560019223254885 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.80948158614737 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.676795234580315 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.79615205253082 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.804506471357946 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.157843585879455 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.35107222818075 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.003847719989256 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.347165152463893 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.722081306342467 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.50297512060691 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.14552946649685 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 72.12986056886923 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.50339944571412 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.138877080262613 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.83878883849164 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.169502311470243 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.997647390673155 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.085567469478658 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.2494451907382 | |
