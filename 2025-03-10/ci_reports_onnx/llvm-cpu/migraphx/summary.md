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
| migraphx_agentmodel__AgentModel | Numerics | 1.208493394818807 | |
| migraphx_bert__bert-large-uncased | PASS | 385.67186892032623 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.24725453058878 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5523.618094623089 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.1115934650103 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5947.245296090841 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 405.62275672952336 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 429.6431851883729 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.3923092044535 | |
| migraphx_models__whisper-tiny-decoder | PASS | 46.29072832564513 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 185.11681134502092 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 93.79534392307202 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 95.04034308095773 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 280.1273583124081 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.86790833697803 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.56213912864526 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.0117765135235 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.674879500159506 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.89561031703595 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.02768931848308 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1555.2952823539574 | |
| migraphx_torchvision__inceptioni1 | PASS | 211.08029327458803 | |
| migraphx_torchvision__inceptioni32 | PASS | 5847.744129598141 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.15468955536683 | |
| migraphx_torchvision__resnet50i64 | PASS | 5477.2961636384325 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1624.5271178583305 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 2983.485364665588 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4892.536499847968 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 150.63269063830376 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 250.65521026651064 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.8319378743569 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 236.4835896425777 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 448.35036993026733 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.5265784263611 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2810.861493150393 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5869.0566048026085 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9429.076955964167 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 407.55449173351127 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 797.5468064347903 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1254.7032547493775 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 734.8352186381817 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1534.4990293184917 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2428.446720043818 | |
