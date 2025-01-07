## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 41 | 87.2% | 87.2% |
| Gold Inference | 41 | 87.2% | 100.0% |
| IREE Inference Invocation | 41 | 87.2% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 68.3% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 6 | 12.8% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 13 | 27.7% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.23998906622054 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | Numerics | 42.446938479164 | |
| migraphx_cadene__inceptionv4i16 | PASS | 149.29524414862195 | |
| migraphx_cadene__resnext101_64x4di1 | Numerics | 114.38183608050974 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 369.97192500469583 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.378436633088211 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.386431514802904 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.33272185631924 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 172.07694699366888 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.4484289279651 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.0803952147918 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 501.18056343247486 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.266878547003635 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.13935139526924 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.11293599009514 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.734227239746936 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.8732795283537 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 5.9095826783612315 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | Numerics | 76.40540824030283 | |
| migraphx_torchvision__inceptioni1 | PASS | 47.42542186788484 | |
| migraphx_torchvision__inceptioni32 | PASS | 100.12746515816873 | |
| migraphx_torchvision__resnet50i1 | Numerics | 11.332747631616167 | |
| migraphx_torchvision__resnet50i64 | Numerics | 193.89422346527377 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.54566483996938 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.177879951273404 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 81.9546154665726 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.033743850012987 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.280981630321193 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 35.728466334856215 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.621642140272472 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.261701530958495 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.912963663150247 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 74.30347856522226 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 114.98713345887761 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 203.11212908321372 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.508422103007227 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.196056366094158 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.375780565377614 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.835059128847778 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.626989219445676 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.9451539995304 | |
