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
| migraphx_bert__bert-large-uncased | PASS | 384.63334025194246 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 168.8607057246069 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5558.2620889569325 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.62511575470364 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 853.4823612620434 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 459.71345668658614 | |
| migraphx_mlperf__resnet50_v1 | PASS | 85.72901172252993 | |
| migraphx_models__whisper-tiny-decoder | PASS | 65.07551642134786 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 209.72383663886123 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 59.68250155759355 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.083344568099296 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1539.4522935772936 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.59460547318062 | |
| migraphx_torchvision__resnet50i1 | PASS | 151.06685987363255 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1576.9575194766123 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5285.795283814271 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9549.636511132121 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 148.12551136128604 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 280.96380726330807 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 560.0909919788439 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 265.90514834970236 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 437.0642293555041 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 651.2396937857071 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5181.142925284803 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14433.413202563921 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 24819.739695017535 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.56297334904474 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 809.3871657426158 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1242.604891769588 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 743.634601123631 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1632.093387345473 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3820.9884871418276 | |
