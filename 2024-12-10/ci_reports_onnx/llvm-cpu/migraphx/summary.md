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
| migraphx_bert__bert-large-uncased | PASS | 378.1868287672599 | |
| migraphx_bert__bertsquad-12 | PASS | 85.8548812213398 | |
| migraphx_cadene__dpn92i1 | PASS | 188.9109800880154 | |
| migraphx_cadene__inceptionv4i16 | PASS | 6198.46606751283 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 333.9066331585248 | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 387.2014867762725 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 513.1036092837651 | |
| migraphx_mlperf__resnet50_v1 | PASS | 101.24731208715173 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.22730812249761 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 184.9954629109965 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 227.54444767321857 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 98.16102311015129 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 290.8357555667559 | |
| migraphx_ORT__distilgpt2_1 | PASS | 31.218010045233225 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.22949599723022 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 244.74244978692795 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.33373303749622 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 96.8866868255039 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 39.362462444437874 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1375.1098290085793 | |
| migraphx_torchvision__inceptioni1 | PASS | 192.16427703698477 | |
| migraphx_torchvision__inceptioni32 | PASS | 6112.0460865398245 | |
| migraphx_torchvision__resnet50i1 | PASS | 96.34481352709588 | |
| migraphx_torchvision__resnet50i64 | PASS | 5351.1651294926805 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2565.283514559269 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4086.0912936429177 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5724.1897359490395 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 160.01102110991874 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 264.3754573331939 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 406.6593386232853 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 428.46326157450676 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 598.4348965187867 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 812.715026239554 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 4976.4197903374825 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8165.150405218203 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11393.542632460594 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 709.7419438262781 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1113.3050099015236 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1508.9546603461106 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1331.4213119447231 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2084.3552698691683 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3000.730324536562 | |
