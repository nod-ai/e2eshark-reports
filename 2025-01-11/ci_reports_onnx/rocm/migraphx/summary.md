## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.30462180947264 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.561321305887155 | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.64117200362185 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 117.9113379265699 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 388.22036267568666 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.666840266513948 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 23.788643411050245 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.648724712076636 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 140.53319692611691 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.28012829983516 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.507522237088 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 503.80898422251147 | |
| migraphx_ORT__distilgpt2_1 | PASS | 53.20570080612715 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.92943482552513 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 294.8988163843751 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.067961516479645 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.821164488674155 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.231343708311517 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 74.13522885353476 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.07217852245359 | |
| migraphx_torchvision__inceptioni32 | PASS | 106.95781474489542 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.18519812961768 | |
| migraphx_torchvision__resnet50i64 | Numerics | 152.04494167119265 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.224140575155616 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 58.34978981874883 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 79.3782291519973 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.092716195747071 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.380506386359533 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.468095282920533 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.656450028898135 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.251653321837104 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.66227416525926 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.95658630132675 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 111.52315967612795 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 159.58020285082358 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.309128416942903 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.621120802747708 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.460751465717212 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.12262216636113 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.562259493913086 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.30505770243084 | |
