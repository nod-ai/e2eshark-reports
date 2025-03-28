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
| migraphx_agentmodel__AgentModel | Numerics | 2.3190463731067212 | |
| migraphx_bert__bert-large-uncased | PASS | 19.30002817728867 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.322005522701843 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.149684628161292 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 5.889783159364015 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.01674690850727 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.002584782349778 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.682766303396182 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.8154705181743385 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.71377785172727 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.53309584698743 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.89528887129079 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.02672709462543 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 524.3260209293414 | |
| migraphx_ORT__distilgpt2_1 | PASS | 68.4047416706259 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.15183222384163 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.47314602602273 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.14583213937779 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 19.137206413942547 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.745814362764582 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.84182599204409 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.865703260429868 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.965199785927933 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.178414943112484 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.39419700546811 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.93049016539963 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.69962768577453 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.423837763257325 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.224663693950264 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.674068829197196 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.478205263752624 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.569123060010106 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.42766469437629 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.29606454917008 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.76116901547893 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.57036187858492 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.39740407756632 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.487807729833378 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.842850427417194 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.12069125914539 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.8194658249579 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.487979124252423 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.82943427128097 | |
