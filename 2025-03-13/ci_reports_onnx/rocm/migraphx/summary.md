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
| migraphx_agentmodel__AgentModel | Numerics | 1.980922591063263 | |
| migraphx_bert__bert-large-uncased | PASS | 18.9606168843294 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.433692383883017 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.396697966957515 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.293902556366592 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 30.013172814506106 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 6.99645289060085 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.468939335240666 | |
| migraphx_mlperf__resnet50_v1 | PASS | 4.775814909372866 | |
| migraphx_models__whisper-tiny-decoder | PASS | 44.35135140253502 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.02733166696918 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 107.20635399809993 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 110.1750629105871 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 453.4684656634151 | |
| migraphx_ORT__distilgpt2_1 | PASS | 60.15245636646998 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.5429183006089 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 239.90368334084954 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 33.8999562710154 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.3392115869478 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 9.098012797180706 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.043594709478132 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.903327489555781 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.079694797440123 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.5724294541972266 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.774974307962967 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.811729791723646 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.60045149829239 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.96026149376606 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.253512235386578 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.40485999290695 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 18.985860087480898 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.50346257681182 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 18.959874757104092 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.694314627149314 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.684842950770665 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.99631954620902 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 113.38814100599848 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 73.0258292892973 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.895014381368778 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.723075864836574 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.96520682725878 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.465783527075672 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.20456645728665 | |
