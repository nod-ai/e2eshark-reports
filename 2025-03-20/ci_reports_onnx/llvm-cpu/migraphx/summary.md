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
| migraphx_agentmodel__AgentModel | Numerics | 1.0905858522520298 | |
| migraphx_bert__bert-large-uncased | PASS | 439.68177897234756 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 205.37254307419062 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5419.349958499272 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 325.83262398838997 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5076.098093142112 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.2170174866915 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 441.1856587976217 | |
| migraphx_mlperf__resnet50_v1 | PASS | 93.92928476962777 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.29837536721518 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 177.88530482600132 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 100.78502756853898 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 85.04985350494583 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 246.59328245454364 | |
| migraphx_ORT__distilgpt2_1 | PASS | 30.607807191295752 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.86115790548779 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 252.2700900832812 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.025468838435636 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.62785555146358 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 45.09892248932053 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1444.2200896640618 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.34740004605715 | |
| migraphx_torchvision__inceptioni32 | PASS | 5796.601547549169 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.47754770268996 | |
| migraphx_torchvision__resnet50i64 | PASS | 5404.210198670626 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1506.2077393134434 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3005.7287886738777 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4806.168069442113 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 177.94189353783926 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 279.4548802905612 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 360.2050586293141 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 238.41983286870848 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 448.63777545591194 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 664.3086535235245 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2800.748411566019 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5763.761669397354 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9146.990083158016 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 412.8970118860404 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 796.6872826218605 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1406.0665555298328 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 745.839054385821 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1571.113691975673 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2628.668924172719 | |
