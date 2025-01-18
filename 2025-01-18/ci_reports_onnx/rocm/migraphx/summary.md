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
| migraphx_bert__bert-large-uncased | PASS | 19.574835430830717 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 64.4244991637992 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.19587932527065 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 172.813471329088 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 387.5401077481608 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.20215875490689 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 25.62373032837751 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.35811952579146 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.1466689730684 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.36940225958824 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.95445204951933 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 476.48839683582383 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.15597413660901 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.80578592780864 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 272.71301206201315 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.4594225790916 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.484906645639548 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.394176247742092 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 64.93796444864886 | |
| migraphx_torchvision__inceptioni1 | PASS | 61.255453041557104 | |
| migraphx_torchvision__inceptioni32 | PASS | 101.07500123835744 | |
| migraphx_torchvision__resnet50i1 | Numerics | 15.83151259657108 | |
| migraphx_torchvision__resnet50i64 | Numerics | 145.63634159664312 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.72728197820602 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.509817803899445 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.9730367594295 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.177076527913071 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.783396430313585 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.70952584546197 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.945343567817298 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.422286143908515 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.64232192444615 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.54747367029388 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 106.21585985202165 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 156.09753550961614 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.501808398765407 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.100069800588656 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.98635884250204 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.63253059700407 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.351262832681332 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.314152269825044 | |
