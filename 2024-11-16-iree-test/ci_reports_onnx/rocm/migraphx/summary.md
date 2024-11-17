## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 20.05957487438406 | |
| migraphx_bert__bertsquad-12 | PASS | 18.569029662086887 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.72094504038492 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 212.59606034598414 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.409086537531071 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.50084721090065 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.542772904757954 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.689868858930737 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.76606532816704 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.86762945747209 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.28245256178907 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 360.021545086056 | |
| migraphx_ORT__distilgpt2_1 | PASS | 64.45620104557635 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.43984208131829 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 273.7331173072259 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 38.56862379311054 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 25.34802279959636 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 16.159436446142152 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.608300404357045 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.8588199551697 | |
| migraphx_torchvision__inceptioni32 | PASS | 137.79563770319024 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.50022871264568 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 33.25459888086669 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 156.85474674683064 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 73.18236177476744 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.591539059929987 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.830192746241496 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.915121390173834 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.357041678271997 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.946114182472227 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.612768376750562 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.76285827408235 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 231.7549429079961 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.50305495411158 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.03677408257169 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.492910268871732 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.51756289653862 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.85340408892149 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.90472753345966 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.34195093430725 | |
