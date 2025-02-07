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
| migraphx_bert__bert-large-uncased | PASS | 371.22887559235096 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.49044130908115 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5614.239933590095 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 320.32252537707484 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5809.475187212229 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 474.82662089169025 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 414.88903760910034 | |
| migraphx_mlperf__resnet50_v1 | PASS | 320.645355929931 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.04781234715924 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 189.83975880675845 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 110.94478910995853 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 92.75159845128655 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 370.6138651404115 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.785774601974346 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.22107468545437 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 263.805013977819 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.12965478223783 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 96.80319080750148 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.16904439348162 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1468.6411134898663 | |
| migraphx_torchvision__inceptioni1 | PASS | 218.0746822721428 | |
| migraphx_torchvision__inceptioni32 | PASS | 5772.341477374236 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.93011324976881 | |
| migraphx_torchvision__resnet50i64 | PASS | 5412.2093841433525 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2537.099865575631 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4135.098863393068 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5810.242787003517 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.97461494306722 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 260.23162239127686 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 411.84715554118156 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 402.54749295612174 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 654.036782681942 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 809.108713020881 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5655.026250829299 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8369.744037588436 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11325.480312108994 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 720.8712709446748 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1079.8160185416539 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1499.6332513789337 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1286.606571326653 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2088.302181412776 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2885.179294894139 | |
