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
| migraphx_bert__bert-large-uncased | PASS | 381.52967517574626 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 169.68165586392084 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5685.881434629361 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 313.3411705493927 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5075.374501446882 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 402.87413199742633 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 446.8884964783986 | |
| migraphx_mlperf__resnet50_v1 | PASS | 97.83047499756019 | |
| migraphx_models__whisper-tiny-decoder | PASS | 30.857136014147077 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 180.84898994614682 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 102.4599816236231 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 97.34889084384554 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 286.3767432669798 | |
| migraphx_ORT__distilgpt2_1 | PASS | 32.42920069158941 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 86.75198722630739 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 368.9528629183769 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.55461871292856 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 75.4455058938927 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 41.43054841780195 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1497.0353121558826 | |
| migraphx_torchvision__inceptioni1 | PASS | 198.61329098542532 | |
| migraphx_torchvision__inceptioni32 | PASS | 5731.271805862586 | |
| migraphx_torchvision__resnet50i1 | PASS | 84.77828232571483 | |
| migraphx_torchvision__resnet50i64 | PASS | 5480.234038084745 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2604.086315880219 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4385.568694521983 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5825.949841489394 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 176.74913660933575 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 278.53293096025783 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 381.0063097625971 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 379.0163993835449 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 616.472332427899 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 849.2529665430387 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5125.982792427142 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8013.210441917181 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11334.727222720781 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 718.4609634180864 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1097.0802493393421 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1512.3020137349765 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1332.6846087972322 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2181.5539350112276 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 2987.683154642582 | |
