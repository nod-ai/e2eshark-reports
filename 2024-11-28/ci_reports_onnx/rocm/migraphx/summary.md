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
| migraphx_bert__bert-large-uncased | PASS | 20.118793572432228 | |
| migraphx_bert__bertsquad-12 | PASS | 19.733267688813307 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.97023972465345 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 217.77040269484533 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.555373073939406 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 45.907870658473776 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.594025497281245 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.036441660471375 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 53.355822103838314 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 111.31476770646663 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.64615411528696 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 369.5718781285298 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.09161172575797 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 73.27404431222628 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 279.98294531264236 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.65936445510359 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 27.423656542903217 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 15.688746334570977 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 52.78003282355479 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.99939879220487 | |
| migraphx_torchvision__inceptioni32 | PASS | 146.30366945639253 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 193.19675661002597 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 34.69864232853676 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 59.79123811185773 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 75.82483374237738 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.610331340863373 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.818891611698943 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 20.40399187079847 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.451690055752318 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.9735484852766 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.981274502953358 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 71.56024199988072 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 108.09506153288697 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 150.3559639289354 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.125475812320273 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.790788310006835 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.42858811651762 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.476972407084844 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.006975442623823 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 42.82174141796228 | |
