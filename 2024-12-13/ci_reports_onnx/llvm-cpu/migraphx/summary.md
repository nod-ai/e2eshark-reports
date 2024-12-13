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
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 399.67635336021584 | |
| migraphx_bert__bertsquad-12 | PASS | 89.51646497561818 | |
| migraphx_cadene__dpn92i1 | PASS | 174.4636483490467 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5765.418540686369 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.50648841261864 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5083.54098846515 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 1467.317168911298 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 464.64431285858154 | |
| migraphx_mlperf__resnet50_v1 | PASS | 94.01771053671837 | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.94293010731538 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 950.8281263212363 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 94.79667530173344 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.96100723743439 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 278.12247288723785 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.1493129617926 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 91.2386456814905 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 270.04272449347707 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 42.1864942268089 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 83.0846991803911 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 89.52281295376667 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1652.0718100170295 | |
| migraphx_torchvision__inceptioni1 | PASS | 213.66815889875093 | |
| migraphx_torchvision__inceptioni32 | PASS | 5878.1210494538145 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.60065979510546 | |
| migraphx_torchvision__resnet50i64 | PASS | 5966.740569720666 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2692.6236574848494 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 3942.4433323244252 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5809.370527664821 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 154.60385878880817 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 270.13174444437027 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 425.05844744543236 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 416.7534951120615 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 591.0844467580318 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 844.6551561355591 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5139.190497497717 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8146.080990632374 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 12336.882028728724 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 705.6837566196918 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1081.754925350348 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1498.906551549832 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1303.430831680695 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2107.7124836544194 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2859.5586282511554 | |
