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
| migraphx_agentmodel__AgentModel | Numerics | 2.01148256342149 | |
| migraphx_bert__bert-large-uncased | PASS | 18.910064764723586 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.434980572511751 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.20716097449056 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.255698304453034 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.76933689852659 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.6858575476773 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 27.08554111225645 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.771732129462658 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.57368709073247 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.58271221873852 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.34119779847207 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 108.52939626645473 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 457.2176208797221 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.40296600355455 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.293694726896994 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.43750098078613 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 34.95797999591256 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.665958020071955 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 7.504404880347902 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.05095498760541 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.92434918339347 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.059873875851434 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.57949861101554 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.60387240877996 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.29838968819063 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.42211474019748 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 70.10651470627634 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.06535754602231 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.368639439551366 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.225210399815328 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.94003537695073 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.396208164079162 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.779685398070693 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 65.98120788817829 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.11301551581846 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 138.63006536848843 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.479136805613935 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.517385096801807 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.124963821976312 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 18.94809609186743 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.586416864445727 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 38.89969691065036 | |
