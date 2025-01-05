## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 69.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 36.314182307607695 | |
| migraphx_bert__bertsquad-12 | PASS | 6.377900875176409 | |
| migraphx_cadene__dpn92i1 | Numerics | 8.191677757763657 | |
| migraphx_cadene__inceptionv4i16 | PASS | 42.26033155824624 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 10.73217986103816 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 131.4372284648319 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.842389928846106 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 91.41421289227547 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.56510379336892 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.63208646909334 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 98.90346395383989 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.50560557522944 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 499.6251674213757 | |
| migraphx_ORT__distilgpt2_1 | PASS | 66.42233462826836 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.36426826318104 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 292.3222268000245 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.63806480270895 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.028601374339173 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.473786396478924 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 45.63961938644449 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.594136584848488 | |
| migraphx_torchvision__inceptioni32 | PASS | 42.28805453863506 | |
| migraphx_torchvision__resnet50i1 | Numerics | 3.3635247703223747 | |
| migraphx_torchvision__resnet50i64 | Numerics | 112.02510733467837 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.43099091233065 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 51.65841504453848 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 76.16699819832488 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 8.810293053587278 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 78.8056517097478 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.620003433934613 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 10.22371937462313 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 11.11452618525142 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 22.708965260134907 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 124.79128285000719 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.70561204779716 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 138.6403650045395 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 12.017203060815396 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.278299523580845 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 28.268141020089384 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.568915241446934 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.197766448244632 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 46.54589504072511 | |
