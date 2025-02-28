## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 81.4% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 8 | 17.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.3989396281629727 | |
| migraphx_bert__bert-large-uncased | PASS | 379.8600696027279 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 163.78372938682634 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5656.086351722479 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.21820156276226 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5054.399728775024 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 403.64721852044266 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 450.1272204021613 | |
| migraphx_mlperf__resnet50_v1 | PASS | 95.53393278093563 | |
| migraphx_models__whisper-tiny-decoder | PASS | 38.63277671237786 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 178.57109424140717 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.62970843059675 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.91715280090769 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 257.55434048672515 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.956109765352622 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.77117867146929 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.06385156181122 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.12600559683947 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 96.40366604758633 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.60211864776081 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1535.5128372708957 | |
| migraphx_torchvision__inceptioni1 | PASS | 213.20932192934882 | |
| migraphx_torchvision__inceptioni32 | PASS | 5821.5239234268665 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.55860383684437 | |
| migraphx_torchvision__resnet50i64 | PASS | 5445.0214964648085 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2630.952339619398 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4098.915650198856 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5983.196294556062 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 159.26334882775942 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 273.78460702796775 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 453.8856539875269 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 381.917592138052 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 596.3098953167597 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 844.6136365334193 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5463.594848910968 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8014.927155027787 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11240.754943341017 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 1216.8648752073445 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1107.6884232461452 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1540.7426493863265 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 3193.637958417336 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2135.0759093960123 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2939.9349888165793 | |
