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
| migraphx_bert__bert-large-uncased | PASS | 19.24913580080977 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.59087836059431 | |
| migraphx_cadene__inceptionv4i16 | PASS | 155.6455350946635 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 117.94501113601855 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 388.1433194813629 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.18793791851827 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.937646059585465 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.41390423928246 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 68.56523637349406 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 99.2668526069749 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 99.33710288965983 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.90638347218436 | |
| migraphx_ORT__distilgpt2_1 | PASS | 52.57536060664625 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 60.76938179180476 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 294.013199241211 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 31.71649106749982 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.530299969968643 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.672825831056073 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 73.61760228458378 | |
| migraphx_torchvision__inceptioni1 | PASS | 41.077964811348444 | |
| migraphx_torchvision__inceptioni32 | PASS | 106.83534112537188 | |
| migraphx_torchvision__resnet50i1 | Numerics | 12.188049333020187 | |
| migraphx_torchvision__resnet50i64 | Numerics | 151.63528968890506 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 35.032570439701274 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.655245841791235 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 78.40348000603693 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.066923504488335 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.25809140250368 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.494368565372294 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.688501677032383 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.193962562524673 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.51639209213582 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 70.1281148319443 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 109.88004422850078 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 157.50091592781246 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.271085765086063 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.584293374481298 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.47850472756006 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.057097458768457 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 29.483080298329394 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 43.1449572982577 | |
