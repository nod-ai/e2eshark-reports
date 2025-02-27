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
| migraphx_agentmodel__AgentModel | Numerics | 0.811598149307987 | |
| migraphx_bert__bert-large-uncased | PASS | 388.6208987484376 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.87110999474922 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5582.8358717262745 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 318.49124344686663 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4994.191466520229 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 397.1387508014838 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.8326123108466 | |
| migraphx_mlperf__resnet50_v1 | PASS | 102.33653378155496 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.321043151238605 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.43994182679387 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.61938504377999 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.8796663781007 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 389.9557602902253 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.628602218848684 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.69559289349449 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 302.58836783468723 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 43.53607321778933 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 91.31520319109161 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.68840586580336 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1448.1761381030083 | |
| migraphx_torchvision__inceptioni1 | PASS | 205.88263165619637 | |
| migraphx_torchvision__inceptioni32 | PASS | 5762.214447061221 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.25181203832229 | |
| migraphx_torchvision__resnet50i64 | PASS | 5449.206841488679 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2549.1273688773313 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4046.606833736101 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5736.850373446941 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.3065857887268 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.4595122569137 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 374.60919097065926 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 403.91413184503716 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 627.142912397782 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 823.6496237417063 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5203.500346591075 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8200.453377018372 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12307.372887929281 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 878.9617208143076 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1109.3585789203644 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 2076.31354033947 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1313.3330990870793 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2161.371484398842 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3047.3937690258026 | |
