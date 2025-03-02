## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 36 | 76.6% | 83.7% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 2.1661594797873147 | |
| migraphx_bert__bert-large-uncased | PASS | 18.88548365273924 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.08920555419158 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.218106495035396 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.613023558225578 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.802987882350052 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.082248769743558 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.44984966081877 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.727464640099141 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.61025308996128 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.07562544859118 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 109.20272098802444 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.2991873760604 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 461.0630093763272 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.754040331527996 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.502079627561294 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 241.56919677948784 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.988633375459656 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.63580293635406 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.357055677871507 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.115237112451567 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.888569978489117 | |
| migraphx_torchvision__inceptioni32 | PASS | 27.965081368262563 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5535563996877966 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.590857408630352 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.26207664490423 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.33598081667264 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 69.76343578814217 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.243008800386184 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.438338400908941 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.260216030283825 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.084754057115674 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 23.594261145617505 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.872595334224698 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.96778817192622 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 97.8964011938799 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 137.8710664032648 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.468845318514084 | |
| migx_bench_bert-large-uncased_4_256 | Numerics | 16.484573746980853 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.0458037037225 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.048211208821552 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.532856333586903 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.13810132157609 | |
