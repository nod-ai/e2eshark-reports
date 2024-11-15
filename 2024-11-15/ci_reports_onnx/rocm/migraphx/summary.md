## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 32 | 68.1% | 68.1% |
| Gold Inference | 32 | 68.1% | 100.0% |
| IREE Inference Invocation | 32 | 68.1% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 87.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 15 | 31.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 8.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.13446001247281 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.80245739159483 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 238.96477451651458 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.769533619453347 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 65.91451035637874 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.525541459537905 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.15925815158213 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.74067324204132 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 27.119953161439835 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 16.7281729114653 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.76234518284244 | |
| migraphx_torchvision__inceptioni1 | PASS | 16.740257276758324 | |
| migraphx_torchvision__inceptioni32 | PASS | 138.20507293567061 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 183.11083920222396 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.53971662738966 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.008203218277124 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.87809722718816 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.680136211679065 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.772246237612917 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.078285315650557 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.411400038690404 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.900452844488122 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.903262049211964 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 69.8102416548257 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 104.89991216343782 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 146.3434339656184 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.95002517278524 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.464913103807095 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.966390202944282 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.31801438979095 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 28.015196211636066 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.48174383147967 | |
