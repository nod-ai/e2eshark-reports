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
| migraphx_bert__bert-large-uncased | PASS | 370.5306562284629 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.33524930228788 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5602.382495999336 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 319.87494975328445 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5080.6141172846155 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 372.9823517302672 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 424.060524130861 | |
| migraphx_mlperf__resnet50_v1 | PASS | 100.81050278885023 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.95666308333908 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.9146793782711 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 120.92988110250896 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.48613128066063 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.7970223327478 | |
| migraphx_ORT__distilgpt2_1 | PASS | 29.955041077401898 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 95.55747711824046 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 249.9069000283877 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 45.68434895740615 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 91.71175529007559 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.80500633135819 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1492.9308009644349 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.0548251544436 | |
| migraphx_torchvision__inceptioni32 | PASS | 5776.591684669256 | |
| migraphx_torchvision__resnet50i1 | PASS | 83.56083743274212 | |
| migraphx_torchvision__resnet50i64 | PASS | 5426.429983228445 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2611.552422245343 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4077.237074573835 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5815.3012829522295 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.05465916047493 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.09465120236075 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 388.8945070405801 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 452.74485771854717 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 581.137220064799 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 843.2372833291689 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5027.395954976479 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8816.002663224936 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11271.75593127807 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 737.3061490555605 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1076.4619298279285 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1552.4080358445644 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1305.3582832217216 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2062.485801676909 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2887.291902055343 | |
