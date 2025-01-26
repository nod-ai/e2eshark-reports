## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 33 | 70.2% | 70.2% |
| Gold Inference | 33 | 70.2% | 100.0% |
| IREE Inference Invocation | 33 | 70.2% | 100.0% |
| Inference Comparison (PASS) | 26 | 55.3% | 78.8% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 14 | 29.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.279595472552398 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.082919663338948 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 72.38838297334344 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.810520603884164 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 144.0766937341929 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.73977961968852 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 106.65879576187024 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 574.9831966604688 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.599620249882314 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 64.32910739430083 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 538.3308645573884 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.20480468137825 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 16.885988368717094 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.078714020539838 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 61.158829728039116 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.974717682742536 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.363319949429034 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.19866413458172 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 11.93996174137199 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.62437820337198 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.924993618641405 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 22.287001434011447 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.55849966029592 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.966316391137546 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.44763945390568 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 99.11672823918273 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 146.47281553188805 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.323221871310203 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.26020956047631 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.728694716235623 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.916442125840614 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.689443001228977 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.49348836963677 | |
