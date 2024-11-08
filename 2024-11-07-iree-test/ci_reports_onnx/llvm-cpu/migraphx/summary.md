## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 34 | 72.3% | 87.2% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 5 | 10.6% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 370.60073142250377 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 182.2044545163711 | |
| migraphx_cadene__inceptionv4i16 | PASS | 7229.451260839899 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.36753491312265 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5067.395259315768 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 421.3760985682408 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 465.59895885487396 | |
| migraphx_mlperf__resnet50_v1 | PASS | 106.11583509792884 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.746407745010924 | |
| migraphx_models__whisper-tiny-encoder | compilation | None | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.93121634352775 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 105.30454975863296 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 260.5987675487995 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 97.99586686616142 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 247.68579295939867 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.16169901578515 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.15995701650778 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1392.4372469385464 | |
| migraphx_torchvision__inceptioni1 | PASS | 224.0300927725103 | |
| migraphx_torchvision__inceptioni32 | PASS | 6098.804249738653 | |
| migraphx_torchvision__resnet50i1 | PASS | 95.91031281484497 | |
| migraphx_torchvision__resnet50i64 | PASS | 5233.224525426825 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2515.3535337497788 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4181.501592819889 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6028.094792738557 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 162.4310128390789 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 312.14529027541477 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.0282356565197 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 402.2642429918051 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 591.0040903836489 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 832.2345558553934 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5065.923057496548 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8380.72502054274 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11569.338814044992 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 730.6447916974624 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1126.7061320443947 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1578.4951113164425 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1388.8791278004646 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2129.960671067238 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2991.9364477197328 | |
