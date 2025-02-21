## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 29 | 61.7% | 82.9% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.9327306668752973 | |
| migraphx_bert__bert-large-uncased | PASS | 18.96456798836421 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.111933887936175 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 26.66001721547964 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.803883189284433 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.571297501330264 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.57624275940987 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 108.97418072757621 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.09829902711014 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 461.3215224817395 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.10642433668383 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62.30522511230612 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.2909947775511 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 37.094730726333665 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.35597974616879 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.41419496251508 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.893040270991435 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.25830391007052 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.2056635681492 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 67.79092199867591 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.081666764050807 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.560556342330885 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.210812291717744 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.950313954162551 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.397520728922713 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.918649695494086 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.95045357420476 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.13649499185738 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 137.47852706195164 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.419729493520393 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.93347881840499 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.364464046322695 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.084108078869075 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.501698323157555 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.03148657237006 | |
