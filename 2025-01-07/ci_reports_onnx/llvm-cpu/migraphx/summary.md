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
| migraphx_bert__bert-large-uncased | PASS | 389.76604988177615 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 176.0170947139462 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5288.8137102127075 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 337.4669731905063 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5103.517357259989 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 378.8184020668268 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 1287.0541599889596 | |
| migraphx_mlperf__resnet50_v1 | PASS | 89.44282908406522 | |
| migraphx_models__whisper-tiny-decoder | PASS | 34.66671965424977 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 198.08474431435266 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.52876900207427 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 104.25750609664688 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 305.2925964196523 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.076891912203838 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 93.97913282737136 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 246.82365771796967 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.26147332929428 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 84.24339086438219 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 40.714822709560394 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1610.8465604484081 | |
| migraphx_torchvision__inceptioni1 | PASS | 197.3296900590261 | |
| migraphx_torchvision__inceptioni32 | PASS | 5402.685673286517 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.05942877754569 | |
| migraphx_torchvision__resnet50i64 | PASS | 5103.7118546664715 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2792.0670049885907 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4117.667117466529 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5809.624293198188 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 167.00510339190564 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 285.5362830062707 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 373.751833414038 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 386.8539184331894 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 578.7387403349081 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 833.8287994265556 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5037.422134230534 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 7938.741263002157 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11271.619394421577 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 710.5994572242101 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1081.5038656195004 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1524.8563053707283 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1304.3957091867924 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2081.4850069582462 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2907.1097721656165 | |
