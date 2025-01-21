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
| migraphx_bert__bert-large-uncased | PASS | 406.0753757754962 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.33129883060852 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5244.309501101573 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 323.46745890875656 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5005.308418224255 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 390.4894919445117 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 414.9973765015602 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.76919523307255 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.63102410282149 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.10811714662444 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 85.75245525155748 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.72104798470224 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.1337557037671 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.902495416856947 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.10235618551572 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 2283.2287934919195 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.31875651081403 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.09015855855411 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 48.02429055174192 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1553.015620758136 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.12334248671928 | |
| migraphx_torchvision__inceptioni32 | PASS | 5325.655189653237 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.7679111349086 | |
| migraphx_torchvision__resnet50i64 | PASS | 5940.480403602123 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2541.733328253031 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4009.5006078481674 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5720.479701956113 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 155.64475736270347 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 266.76150825288556 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.3239842802286 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 389.3337932725747 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 584.9159595866997 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 805.4045041402181 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5039.3141793708 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8078.355145951111 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11399.061469982067 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 713.9392010867596 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1068.7345638871193 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1530.3897894918919 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1302.6312167445817 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2136.3976324597993 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2936.3184049725533 | |
