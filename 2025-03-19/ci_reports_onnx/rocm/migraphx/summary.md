## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 34 | 72.3% | 72.3% |
| Gold Inference | 34 | 72.3% | 100.0% |
| IREE Inference Invocation | 34 | 72.3% | 100.0% |
| Inference Comparison (PASS) | 27 | 57.4% | 79.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 13 | 27.7% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.004605553188437 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.996053265950952 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.45384649764229 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.760464650408485 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.504975268635526 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 45.64378772241374 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.50301782233225 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.16019040491017 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 482.6916121528484 | |
| migraphx_ORT__distilgpt2_1 | PASS | 58.95173161924402 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.30418260957142 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 286.481679443063 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.5096757945915 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.51999284565579 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.03591369760487 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.993987706738654 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.374770682815107 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.61796485122155 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 58.85964791781993 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.063478891007948 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.317928434512984 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.13240974399823 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.37413181557453 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.929319876783133 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.734885598558723 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.50175194713499 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 73.36640609342052 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 115.61542310260442 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 18.942950807327218 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.061631546178386 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.038697109857424 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.080631538959487 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 25.864866937303706 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.97716391122057 | |
