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
| migraphx_bert__bert-large-uncased | PASS | 375.25624595582485 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.7626445715626 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5375.369422137737 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 836.5981926520666 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5109.122451394796 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 381.642069046696 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 483.87544974684715 | |
| migraphx_mlperf__resnet50_v1 | PASS | 91.90566926485015 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.154004667644145 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.14743575784894 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 95.58944173512003 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 91.48829896003008 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.89242270588875 | |
| migraphx_ORT__distilgpt2_1 | PASS | 39.694078320610345 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.28359673255018 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 275.2025682065222 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.11303765078386 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 81.98521162072818 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 43.766939172557755 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1615.5658115943272 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.29549204061428 | |
| migraphx_torchvision__inceptioni32 | PASS | 5393.902658174436 | |
| migraphx_torchvision__resnet50i1 | PASS | 91.95348698024948 | |
| migraphx_torchvision__resnet50i64 | PASS | 5067.372822513183 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2603.328825285037 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4186.114265273014 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5690.080928305785 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.0849746589859 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 274.2930721077654 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 413.33841904997826 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 405.73494260509807 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 624.0295854707558 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 889.4105715056261 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5085.0161872804165 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7844.237484037876 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11263.192022840181 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 703.7545628845692 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1086.4544523259003 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1562.7674087882042 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1292.1256236732006 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2091.276707748572 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2886.3696915407977 | |
