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
| migraphx_agentmodel__AgentModel | Numerics | 1.2180770386750448 | |
| migraphx_bert__bert-large-uncased | PASS | 384.9294316023588 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.02185118446747 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5815.466127047936 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.8680228690306 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5037.904791533947 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 408.04260162015754 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 469.82008839646977 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.97544552172934 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.340333096908793 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.22552348176637 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.32906984857148 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.59876244408743 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 263.7497136990229 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.30424959590469 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.16402016580105 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 250.89924575553997 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.072906900335234 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.83543078766928 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.911622832218804 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1543.264629940192 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.83629482239485 | |
| migraphx_torchvision__inceptioni32 | PASS | 5781.417194753885 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.82141590118408 | |
| migraphx_torchvision__resnet50i64 | PASS | 5425.937814017137 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1418.7453625102837 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3031.883260856072 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4607.491585115591 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 151.92728210240602 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.55069426364366 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 395.3149889906247 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 248.57508556710346 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 469.84227498372394 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 683.6932860314846 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2990.3619351486363 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 6013.41537386179 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9421.085300544897 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 458.1649216512839 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 788.9728732407093 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1244.166443745295 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 762.3029164969921 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1590.222315241893 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2486.618290344874 | |
