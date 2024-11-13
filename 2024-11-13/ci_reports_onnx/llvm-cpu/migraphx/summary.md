## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 95.1% |
| Inference Comparison (PASS) | 33 | 70.2% | 84.6% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 4.3% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 375.50200149416924 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 184.46600204333663 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6742.056808123986 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 335.18800760308903 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 418.59688113133114 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 463.3843004703522 | |
| migraphx_mlperf__resnet50_v1 | PASS | 88.45871030574752 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.79155548684524 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 588.774710893631 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 90.88580336953913 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 87.2976447322539 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 253.13815660774708 | |
| migraphx_ORT__distilgpt2_1 | compiled_inference | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.36486803657478 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.35850550234318 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compiled_inference | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 71.97397557042893 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.25055955350399 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1343.5283216337364 | |
| migraphx_torchvision__inceptioni1 | PASS | 219.06391075915758 | |
| migraphx_torchvision__inceptioni32 | PASS | 6161.23915463686 | |
| migraphx_torchvision__resnet50i1 | PASS | 90.52799818002514 | |
| migraphx_torchvision__resnet50i64 | PASS | 5209.251801172892 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2686.1470782508454 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4186.262010286251 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5769.8122151196 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 346.13936704893905 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.4073308135072 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 379.8342365771532 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 390.24549070745707 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 632.3998725662628 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 898.5146743555864 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4944.15479277571 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8166.679182400305 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11766.649075473348 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 791.5566433221102 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1971.4230926086504 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1635.6418213496606 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1350.4075159629185 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2127.0778129498162 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3271.0701978454986 | |
