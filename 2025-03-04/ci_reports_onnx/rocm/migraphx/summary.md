## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.004604701145021 | |
| migraphx_bert__bert-large-uncased | PASS | 18.952216663574045 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.072498674659679 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.732855334360565 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.258007335396905 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.758693171768552 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.090940647343597 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.634198604151607 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.79058073643519 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.536683331088476 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.798598447193704 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.21914989075488 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.5430362664518 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 457.64757801468176 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.603150840622895 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.17475858296859 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.51772675435575 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.29553880899523 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.273995512421582 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.844870841257612 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.02660426339851 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.944033460022593 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.979256498316925 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.575423228733651 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.611882278257433 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.254317574287676 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.289665816686096 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 70.07673849972585 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.243209516458299 | |
| migx_bench_bert-large-uncased_1_256 | Numerics | 12.425911308012225 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.328348787018545 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.837622697098235 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.493783580951202 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.777810750730044 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.00755186412822 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.15143559881972 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 138.62545643933115 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.59780059101629 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.66281080501223 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.992786372812194 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.06967494945623 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 60.745501538547565 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.85183151794114 | |
