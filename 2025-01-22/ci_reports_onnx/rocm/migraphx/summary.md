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
| migraphx_bert__bert-large-uncased | PASS | 20.428398414058424 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 69.98385122666757 | |
| migraphx_cadene__inceptionv4i16 | PASS | 160.813993619134 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 188.0378231871873 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 414.3634927459061 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.3007189332404065 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.9468199431132 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.58946889887253 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 148.56287837028503 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 105.68315127775782 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.21598992674122 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 471.0653480142355 | |
| migraphx_ORT__distilgpt2_1 | PASS | 257.57202671633826 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 67.27540418505669 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 278.32218218180867 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.987681365320604 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 14.900238078055727 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.03891872254829 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 68.83136335139473 | |
| migraphx_torchvision__inceptioni1 | PASS | 66.44225244720776 | |
| migraphx_torchvision__inceptioni32 | PASS | 107.90476787628398 | |
| migraphx_torchvision__resnet50i1 | Numerics | 17.044588900739097 | |
| migraphx_torchvision__resnet50i64 | Numerics | 155.2291760065903 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.1684040822207 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 55.58155582119257 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 74.67325849251614 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.63106052735538 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.28323759232302 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.675834971388763 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.519182484835769 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.989102772126593 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.178406371191766 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.35748068988323 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 102.91224172604934 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 151.7671373983224 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.226280451684756 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.685102822347762 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.022682333317324 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.93304485020538 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.550879483803726 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 40.95579908393762 | |
