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
| migraphx_agentmodel__AgentModel | Numerics | 1.2140226666279101 | |
| migraphx_bert__bert-large-uncased | PASS | 375.05905143916607 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.82130392392475 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5511.567777643601 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 316.79302702347434 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5031.2386353810625 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.64302939673263 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 429.8793648680051 | |
| migraphx_mlperf__resnet50_v1 | PASS | 147.30315854152045 | |
| migraphx_models__whisper-tiny-decoder | PASS | 56.935577060688615 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.75266696015993 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 87.4785825255371 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 86.7559053003788 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 251.61913078692223 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.255394245403398 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 230.88113591074944 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 868.9975378413995 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.89143236336253 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 80.89256397000064 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.158562868069374 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1634.3910271922748 | |
| migraphx_torchvision__inceptioni1 | PASS | 195.98167886336645 | |
| migraphx_torchvision__inceptioni32 | PASS | 5862.559776753187 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.18517188106973 | |
| migraphx_torchvision__resnet50i64 | PASS | 5378.632054974635 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2614.9403639137745 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4131.386922051509 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5880.261632303397 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 164.02366974701482 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 287.52754256129265 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 382.37418606877327 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.3375981996457 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 636.5287291506926 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 832.8903454045454 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4902.977539847294 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7957.495504369338 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11278.93794948856 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 766.1575364569823 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1143.0770469208558 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1510.9561358888943 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1306.2626384198666 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2273.5104399422803 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2954.2873861889043 | |
