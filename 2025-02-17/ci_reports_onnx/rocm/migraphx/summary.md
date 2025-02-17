## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 77.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.5561221752199197 | |
| migraphx_bert__bert-large-uncased | PASS | 19.218647036524043 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.478312594922381 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 41.778212899748134 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.905949822007348 | |
| migraphx_models__whisper-tiny-decoder | PASS | 55.411050759721554 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 54.521961606841415 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 134.2379800703687 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 116.01756899229561 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 478.01836017364013 | |
| migraphx_ORT__distilgpt2_1 | PASS | 61.36206704347084 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.74748345732576 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 268.0215400048635 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.819847778960444 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.589489362642976 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.3744782414657735 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 5.342695857592237 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 31.780156782284994 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.968719079887535 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 70.05276690082003 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.093401243397409 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.462726759803289 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.17664344310415 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.750466746122884 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.552860050903968 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.2478607397931 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 66.40278005789061 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.71943362079384 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 139.47214226160818 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.399580977822268 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.60696308529221 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.739813701358884 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.100008882175256 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.56092410864032 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.32721265031162 | |
