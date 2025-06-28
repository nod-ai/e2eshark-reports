## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 18.957533546396203 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 3.6661289039069547 | |
| migraphx_cadene__inceptionv4i16 | PASS | 20.037050771393947 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 4.246583196315138 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.939886145378104 | |
| migraphx_mlperf__bert_large_mlperf | PASS | 25.745799598683206 | |
| migraphx_mlperf__resnet50_v1 | Numerics | 14.775392931575574 | |
| migraphx_models__whisper-tiny-decoder | PASS | 42.5219526560064 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 105.64391899646984 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 124.4171154555968 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 123.8223359816604 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 544.5096226564298 | |
| migraphx_ORT__distilgpt2_1 | PASS | 70.01008049895366 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 66.54870608172406 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 340.04742186516523 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.470159879052325 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.50120082381181 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.930067055172204 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 14.061166654961802 | |
| migraphx_torchvision__inceptioni1 | PASS | 3.1834463617771633 | |
| migraphx_torchvision__resnet50i1 | PASS | 2.0536887199247746 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 26.28942576731428 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.913307269806396 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 56.46241421992372 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.344680207342593 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.237477223013052 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.9284860085159 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.644739785519915 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.013474236015934 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.666750182363167 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.38380872170653 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.89047019928692 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 117.07005272102025 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 18.97171724101042 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.84721523753944 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 22.997553525392405 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.959026178167687 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.454700999260865 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 32.51765970013697 | |
