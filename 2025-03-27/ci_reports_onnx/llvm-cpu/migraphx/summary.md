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
| migraphx_agentmodel__AgentModel | Numerics | 0.9991592718705032 | |
| migraphx_bert__bert-large-uncased | PASS | 375.7765007515748 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 164.2868909984827 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5425.813359518846 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 315.87630324065685 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5041.319275895754 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 398.12254657347995 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 434.8396609226863 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.9497598707676 | |
| migraphx_models__whisper-tiny-decoder | PASS | 37.73048271735509 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 179.44820721944174 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 89.97927254272831 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 90.66416959588726 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 255.29307085606786 | |
| migraphx_ORT__distilgpt2_1 | PASS | 33.37879348841924 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.1498680897057 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 254.1589823861917 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.968329568083085 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 70.66013912359873 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 24.154545946253666 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1495.6344452997048 | |
| migraphx_torchvision__inceptioni1 | PASS | 203.9352709220515 | |
| migraphx_torchvision__inceptioni32 | PASS | 5725.276822845141 | |
| migraphx_torchvision__resnet50i1 | PASS | 86.14656251544754 | |
| migraphx_torchvision__resnet50i64 | PASS | 5465.584070732196 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1417.8893454372883 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3216.6718480487666 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 4749.130625277758 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.11467631161213 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 252.00770340032045 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 372.6653295258681 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 243.33038470811312 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 449.49605378011864 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 663.0478811760743 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 2929.0085025131702 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 5786.650896072388 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 9157.65277420481 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 408.42619103689987 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 802.3530915379524 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1900.2160765230656 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 737.4731699625651 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1518.242749075095 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2634.8573565483093 | |
