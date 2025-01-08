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
| migraphx_bert__bert-large-uncased | PASS | 19.33765610576504 | |
| migraphx_bert__bertsquad-12 | PASS | 7.624278691384876 | |
| migraphx_cadene__dpn92i1 | Numerics | 42.517248880661406 | |
| migraphx_cadene__inceptionv4i16 | PASS | 148.45417914912105 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.05896165201233 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 364.1906992997974 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.220194271775251 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.321383362335542 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.29080652209028 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 142.4226458184421 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.74458875755467 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.79180631555971 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 503.8715613385041 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.52625801251867 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.36433626383993 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 291.2354210857302 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.26032025355732 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 10.781430411503036 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.515097856107686 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 81.56062571409468 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.85632037400615 | |
| migraphx_torchvision__inceptioni32 | PASS | 112.2084435644663 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.22906038161021 | |
| migraphx_torchvision__resnet50i64 | Numerics | 190.78394277797392 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 72.64226792557606 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.92814800608903 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.43767700689257 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.184728629795123 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 17.456322671177816 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.429116225284005 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.662463951291459 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 32.271013425299955 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 40.477139918948524 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.94047352050741 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 285.9087199386623 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.27207507006824 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.272774807272517 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.713380379912753 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.785120570984407 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.123775578325702 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 81.85688883531839 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.52837571059354 | |
