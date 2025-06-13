## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 381.60628677966696 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.5828680852428 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5398.818607442081 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 329.10711884809035 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 398.91725157697994 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.6238019509862 | |
| migraphx_mlperf__resnet50_v1 | PASS | 133.13556041213727 | |
| migraphx_models__whisper-tiny-decoder | PASS | 59.834743901673285 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 207.1090969774458 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.24792803772207 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.49300330234509 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1537.0873988916476 | |
| migraphx_torchvision__inceptioni1 | PASS | 232.34848876018077 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.198922454276 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1602.2941591218114 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5317.857306450605 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9521.626156133909 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 145.87250106657544 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 249.42703674443894 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.29991735269624 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 245.0181472943061 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 447.1378316326688 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 668.6748143595954 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5157.265887440492 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13448.482448700815 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23966.51084177817 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 408.4613133066644 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 786.6827448209127 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1240.034396915386 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 748.1363985377053 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1696.4086713269353 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3449.5737800995507 | |
