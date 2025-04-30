## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 32 | 74.4% | 74.4% |
| Gold Inference | 32 | 74.4% | 100.0% |
| IREE Inference Invocation | 32 | 74.4% | 100.0% |
| Inference Comparison (PASS) | 28 | 65.1% | 87.5% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 11 | 25.6% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 9.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 806.3366313775381 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 228.0271868738863 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5658.31000606219 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.1154481222232 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 456.27385936677456 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 427.6722551633914 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.14042333265145 | |
| migraphx_models__whisper-tiny-decoder | PASS | 57.52494834639407 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 233.78672574957213 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | compilation | None | |
| migraphx_ORT__bert_base_uncased_1 | compilation | None | |
| migraphx_ORT__bert_large_uncased_1 | compilation | None | |
| migraphx_ORT__distilgpt2_1 | compilation | None | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | compilation | None | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | compilation | None | |
| migraphx_pytorch-examples__wlang_gru | PASS | 58.863351845906834 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 20.726494250759 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1495.0815166036289 | |
| migraphx_torchvision__inceptioni1 | PASS | 201.62870610753694 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.30442852633338 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1574.5622391502063 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5380.734262367089 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9305.621174474556 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 179.75890543311834 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 265.0790475308895 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 367.2539424151182 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 242.34800537427267 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 431.52228246132535 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 667.9361909627914 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5091.541485240062 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 14072.916297862927 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 22977.886548886698 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 414.70227638880414 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 787.0336609582106 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1231.3937122623124 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 752.2915005683899 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1969.02526045839 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3606.778754542271 | |
