## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 42 | 89.4% | 89.4% |
| Gold Inference | 42 | 89.4% | 100.0% |
| IREE Inference Invocation | 42 | 89.4% | 100.0% |
| Inference Comparison (PASS) | 35 | 74.5% | 83.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 5 | 10.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 447.20837101340294 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 165.59480565289655 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5646.822395424048 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 466.35876471797627 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5398.905466000239 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 411.7653612047434 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 431.13123377164203 | |
| migraphx_mlperf__resnet50_v1 | PASS | 104.1320055013611 | |
| migraphx_models__whisper-tiny-decoder | PASS | 647.3215765009323 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.31334545877243 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 96.4019837833586 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.24213751157124 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 351.83103010058403 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.72960933913355 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.41680739654434 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 248.31843831472926 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.653904824739406 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.55266580095996 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.06775475486561 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1523.5102077325184 | |
| migraphx_torchvision__inceptioni1 | PASS | 196.6120393739806 | |
| migraphx_torchvision__inceptioni32 | PASS | 5843.772795051336 | |
| migraphx_torchvision__resnet50i1 | PASS | 85.458198769225 | |
| migraphx_torchvision__resnet50i64 | PASS | 5453.214916090171 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2726.9641160964966 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4113.134206583102 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5807.908241947492 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 161.79662942886353 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 291.42987790207064 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 391.1321461200714 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 397.9135037710269 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 633.0082379281521 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 803.961751361688 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5714.888921628396 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8037.91428481539 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11322.278852264086 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 713.7915529310703 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1097.8600805004437 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1533.7530598044395 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1334.179966400067 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2870.1304694016776 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2963.784293582042 | |
