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
| migraphx_agentmodel__AgentModel | Numerics | 1.0020875446655577 | |
| migraphx_bert__bert-large-uncased | PASS | 370.5117671440045 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 166.38495152195296 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5540.268858273824 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 313.1309996048609 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5065.006535500288 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 408.57023062805337 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 490.9929782152176 | |
| migraphx_mlperf__resnet50_v1 | PASS | 96.52882069349289 | |
| migraphx_models__whisper-tiny-decoder | PASS | 31.78776631301099 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 190.16013460026844 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 88.00237708621553 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 89.10297090187669 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 330.338245878617 | |
| migraphx_ORT__distilgpt2_1 | PASS | 35.466934802631535 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 85.88648871296925 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 266.1408980687459 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 40.597749399203884 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 79.92336686168399 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 46.12437364024421 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1479.6866575876873 | |
| migraphx_torchvision__inceptioni1 | PASS | 206.01278822869062 | |
| migraphx_torchvision__inceptioni32 | PASS | 5765.701894958814 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.38575037178538 | |
| migraphx_torchvision__resnet50i64 | PASS | 5397.366038213174 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2608.9547822872796 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4149.416123827298 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5824.245141198237 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 156.49443492293358 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 259.14031556910936 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 402.2906130800645 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 402.7849901467562 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 1058.2447052001953 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 1427.4974477787812 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5001.805043468872 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8073.732773462932 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11504.850540310144 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 748.3207322657108 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1100.9354268511136 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1605.345506221056 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1308.9830552538235 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2166.421163827181 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2952.845875173807 | |
