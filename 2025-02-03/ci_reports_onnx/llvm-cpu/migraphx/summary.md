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
| migraphx_bert__bert-large-uncased | PASS | 387.15713409086067 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.01136279354492 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5464.101012796164 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.27521899342537 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5092.728397498528 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 416.9623404741287 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 500.6058936317761 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.9492375183673 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.1188639352719 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.01708991991146 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.904002353549 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.33332575360932 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 275.7825112591187 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.88775536488919 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.08546070920096 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 251.2094390889009 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.69118982167154 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 122.90112084398667 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.14180972509914 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1491.5596445401509 | |
| migraphx_torchvision__inceptioni1 | PASS | 208.92621173212925 | |
| migraphx_torchvision__inceptioni32 | PASS | 5768.414116154115 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.55700541163485 | |
| migraphx_torchvision__resnet50i64 | PASS | 5340.217597782612 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2581.7279952267804 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4326.297532767057 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5808.055388430755 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 163.71891399224597 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 261.9842882785532 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 378.7901134540637 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 410.9864104539156 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 639.4657256702582 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 809.5715132852396 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5679.503573725621 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8795.680532852808 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11924.84025284648 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 800.9496567149957 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1082.1753193934758 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1648.364604761203 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1288.4553211430707 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2087.3921637733774 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2891.426991671324 | |
