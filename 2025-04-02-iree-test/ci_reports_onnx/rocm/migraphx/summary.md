## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 37 | 78.7% | 86.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 6 | 12.8% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.4448254398973375 | |
| migraphx_bert__bert-large-uncased | PASS | 19.369000176084228 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.051306633443649 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.428289499871124 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.009039480098484 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.482087499774124 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.31826251854493 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 29.6943482361611 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.7765847523000895 | |
| migraphx_models__whisper-tiny-decoder | PASS | 39.38730179733182 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.07362495605937 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 114.47365533402059 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 115.94193244349702 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 523.515600337608 | |
| migraphx_ORT__distilgpt2_1 | PASS | 69.08122078686684 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.96800951412032 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 327.5712008301828 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.61277240082078 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.30785044576115 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.276470991225276 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 17.81580075146491 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.886801234215562 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.99379380031799 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.1604420584294126 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.407277146124912 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 27.037016358987717 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 38.422979019136015 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 58.17798541708422 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.035360395310496 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.453931678060648 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.389928476552345 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.751259309013783 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.391738962844503 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.260023400242925 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 37.072560420870495 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 77.50602314707875 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 118.99800027782071 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.519424093030263 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 20.76866347959046 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 24.080479160137205 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.949219880789958 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.682897770062436 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 34.82744648402634 | |
