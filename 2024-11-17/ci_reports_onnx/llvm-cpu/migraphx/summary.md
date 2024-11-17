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
| migraphx_bert__bert-large-uncased | PASS | 390.7993060226242 | |
| migraphx_bert__bertsquad-12 | PASS | 1418.8174015531938 | |
| migraphx_cadene__dpn92i1 | PASS | 185.37404160532685 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6595.982922241092 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 338.14512348423403 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 412.8858509163062 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 457.57960093518096 | |
| migraphx_mlperf__resnet50_v1 | PASS | 90.98935530831416 | |
| migraphx_models__whisper-tiny-decoder | PASS | 33.90660667509743 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 182.502763138877 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 86.74335417648155 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 120.02467390682015 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 287.6699582363168 | |
| migraphx_ORT__distilgpt2_1 | PASS | 95.47600108716222 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 87.12280176890393 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 265.14376047998667 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.90350546384299 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 73.95830550403505 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 47.31966745522286 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1344.119009251396 | |
| migraphx_torchvision__inceptioni1 | PASS | 218.88214867148133 | |
| migraphx_torchvision__inceptioni32 | PASS | 6161.492897818486 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.03679663004975 | |
| migraphx_torchvision__resnet50i64 | PASS | 5145.551389704147 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2657.1492049843073 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4420.284708340962 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 6122.572069987655 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 158.03683378423253 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 263.8970169549187 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 376.0995290552576 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 397.36116398125887 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 592.6356861988703 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 828.9565692345301 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5184.037442629536 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8443.64307510356 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11646.138537054261 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 737.7743609249592 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1229.0214287738004 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1613.170840467016 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1445.2388919889927 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2488.96691078941 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3046.0350836316743 | |
