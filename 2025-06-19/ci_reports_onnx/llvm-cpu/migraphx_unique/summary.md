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
| migraphx_bert__bert-large-uncased | PASS | 371.32140326624113 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 167.8401540654401 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5453.063089090089 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 722.0940440893173 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 417.2544665634632 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1675.633295128743 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.24584162276652 | |
| migraphx_models__whisper-tiny-decoder | PASS | 692.617254331708 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 208.7236458642615 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.33689325178663 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.115176545988238 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1551.573610554139 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.82264790187278 | |
| migraphx_torchvision__resnet50i1 | PASS | 223.4265700293084 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1582.6380516712863 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5379.175730670492 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9486.696844920516 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 174.910415817673 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 253.22051563610634 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.7351731819411 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.4176243237323 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 435.06481622656185 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 658.6958669746915 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5043.619688600302 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13684.447687119246 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23760.9372480462 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 462.7992400589089 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 852.7862882862488 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1230.61707491676 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 754.9295003215472 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1633.5766504829128 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3496.226488612592 | |
