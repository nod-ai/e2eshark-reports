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
| migraphx_bert__bert-large-uncased | PASS | 374.1180043046673 | |
| migraphx_bert__bertsquad-12 | PASS | 88.28557955308092 | |
| migraphx_cadene__dpn92i1 | PASS | 174.81188041468462 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6532.857675726215 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 350.620308270057 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 450.97317546606064 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 509.52516682446003 | |
| migraphx_mlperf__resnet50_v1 | PASS | 87.97767847066832 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.455355414161172 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.71969879666963 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.86618131682985 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 84.88999395852996 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 259.40274198849994 | |
| migraphx_ORT__distilgpt2_1 | PASS | 34.38874195311583 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 96.63991329984532 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 262.7378792191545 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.584643009360185 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 76.4773099993666 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 42.076754150912166 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1368.6878979206085 | |
| migraphx_torchvision__inceptioni1 | PASS | 217.46916572252908 | |
| migraphx_torchvision__inceptioni32 | PASS | 6039.246027668317 | |
| migraphx_torchvision__resnet50i1 | PASS | 87.57761229450504 | |
| migraphx_torchvision__resnet50i64 | PASS | 5155.341281245152 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2616.7257577180862 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4227.943877999981 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6309.189238275091 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.92065013820925 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 267.1887542431553 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 473.23966181526583 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 904.9604255706072 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 752.2495264808337 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 927.0072312404712 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5782.0373481760425 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8276.498507708311 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11583.29943070809 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 738.6603479584059 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1145.2850407610335 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1764.38186938564 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1345.1824442793925 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2096.6132382551828 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3233.326790854335 | |
