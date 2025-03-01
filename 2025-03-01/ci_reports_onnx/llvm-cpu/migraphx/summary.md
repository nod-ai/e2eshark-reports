## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.2044681946842675 | |
| migraphx_bert__bert-large-uncased | PASS | 389.4773628562689 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 162.71333148082095 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5549.92197578152 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 360.0584001590808 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5185.888132701317 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 401.3073065628608 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 2068.0058126648264 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.81084947217079 | |
| migraphx_models__whisper-tiny-decoder | PASS | 36.1224218375153 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.67305182417235 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.1019649165017 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.36691826581955 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 251.41670803229013 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.08652198487433 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 92.06506030427084 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.81746156016982 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 41.69670324407372 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 74.98190607185715 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.407983203728996 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1550.0320307910442 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.09992909762593 | |
| migraphx_torchvision__inceptioni32 | PASS | 5789.36584542195 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.72701944245232 | |
| migraphx_torchvision__resnet50i64 | PASS | 5362.711855520804 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2608.039492120345 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4245.980673780044 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5862.046537299951 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.42520991464454 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 283.17463191019164 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.1468908091386 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 384.9578872323036 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 620.6578376392523 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 826.2266019980112 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4894.422888755798 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8010.028220713139 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11241.857050607601 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 735.6813189884027 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1108.767244964838 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1514.2010475198429 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1291.2672994037468 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2169.759552925825 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2945.009188105663 | |
