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
| migraphx_agentmodel__AgentModel | Numerics | 2.1436057842809086 | |
| migraphx_bert__bert-large-uncased | PASS | 20.08866440682184 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.013513330680627 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.921979766287322 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.195743684656918 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.54840768426139 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.213440997040141 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.065218156203628 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.740422053668553 | |
| migraphx_models__whisper-tiny-decoder | PASS | 40.226351775884346 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.72464525534047 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 115.6028252120854 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 118.18622299728708 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 518.0624677644421 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.5670657713587 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.76753115998298 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 332.24193926434964 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.012528979374714 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.459201311480587 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.872652309946716 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.933402652255236 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.850331375248589 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.043425918246303 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1574148711190184 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.68956471236441 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.724101921567364 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 39.3067339297246 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 59.442714419371136 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.939416272502582 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.50119407528213 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.52004748939847 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.693643642012916 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.514868874533995 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.582745075408443 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.81939809324971 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 79.73401074263232 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 121.85426886814336 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.50945701294889 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.97285417557666 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.530692927903313 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 21.074052643727022 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.15581530953447 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 35.71831081062555 | |
