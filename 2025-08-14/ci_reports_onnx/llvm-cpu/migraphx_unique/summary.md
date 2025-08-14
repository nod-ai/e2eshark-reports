## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 368.36411338299513 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.03874879951277 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5449.8141289999085 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.4651418725649 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 433.57015618433553 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 448.0607770383358 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.58504679302375 | |
| migraphx_models__whisper-tiny-decoder | PASS | 62.62402043298437 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 221.0923143559032 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 200.41683626671633 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 322.8737496667438 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 569.804420073827 | |
| migraphx_ORT__distilgpt2_1 | PASS | 84.63106164708734 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 220.72692360315057 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 594.8126763105392 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 102.45504930970213 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 65.22358237116624 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 19.17805038047609 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1553.7536373982828 | |
| migraphx_torchvision__inceptioni1 | PASS | 224.16222116185557 | |
| migraphx_torchvision__resnet50i1 | PASS | 100.71787664977212 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1537.2543632984161 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5461.521340534091 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9690.537651379902 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.09321281065542 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 251.87579707966907 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.05359639724094 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 246.0565711889002 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 443.879001463453 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 774.9698764334122 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5072.218988711635 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13744.118311131993 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23942.080789556105 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 423.9108385518193 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 902.0543769001961 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1676.5212398022413 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 868.1580865134796 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1631.1536921809118 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3536.169091860453 | |
