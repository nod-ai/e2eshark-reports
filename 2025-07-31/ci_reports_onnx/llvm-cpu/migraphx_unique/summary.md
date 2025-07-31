## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 367.6111459111174 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 181.73192607031925 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5454.704035073519 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 361.58674660449225 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 432.7529400276641 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 497.1716948784888 | |
| migraphx_mlperf__resnet50_v1 | PASS | 92.18859606023346 | |
| migraphx_models__whisper-tiny-decoder | PASS | 70.4606338404119 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 215.27254798760018 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 242.7405615647634 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 200.35911235027015 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 569.8298333833615 | |
| migraphx_ORT__distilgpt2_1 | PASS | 78.21888422283033 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 190.2834886891974 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 551.3446390007932 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 105.34533640990655 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 107.23576948253644 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 18.84828836313988 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1506.8981060758233 | |
| migraphx_torchvision__inceptioni1 | PASS | 296.08644118222094 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.12762136726329 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1540.3336180994909 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5380.3372619052725 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9948.218882704774 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 155.64583715361852 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 295.2577049533526 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 406.43382103492814 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 288.13845943659544 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 555.466969187061 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 658.8254800687233 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4985.711491666734 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13695.937373675406 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23803.090915704768 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1076.7315233436723 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.8997291748723 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1261.4680153007307 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1188.5728718092043 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1656.057171523571 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3447.4894159163036 | |
