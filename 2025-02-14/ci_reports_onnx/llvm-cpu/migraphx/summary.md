## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 43 | 91.5% | 91.5% |
| Gold Inference | 43 | 91.5% | 100.0% |
| IREE Inference Invocation | 43 | 91.5% | 100.0% |
| Inference Comparison (PASS) | 34 | 72.3% | 79.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 8.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 9 | 19.1% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.1590024724826677 | |
| migraphx_bert__bert-large-uncased | PASS | 372.8687750796477 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 207.73782829443613 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5594.797703127067 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 317.9216453184684 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 5230.705134570599 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 399.71549560626346 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 428.0043902496497 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.80196728876656 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.05111684898535 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 181.07491607467333 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 84.58433495390982 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 88.79848108405156 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 261.2007353454828 | |
| migraphx_ORT__distilgpt2_1 | Numerics | 29.433999469296797 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 84.4315270272394 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 278.3343444267909 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 46.63718460748593 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 78.35053555943347 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 44.17443803201119 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1485.1101860404015 | |
| migraphx_torchvision__inceptioni1 | PASS | 207.45477390786013 | |
| migraphx_torchvision__inceptioni32 | PASS | 5724.737197160721 | |
| migraphx_torchvision__resnet50i1 | PASS | 89.94819611931841 | |
| migraphx_torchvision__resnet50i64 | PASS | 5467.13574975729 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 2633.9031644165516 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 4216.717407107353 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 5915.085298319657 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 165.05984030663967 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 293.3155025045077 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 402.48433500528336 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 434.61058971782523 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 663.1765775382519 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 820.5432544151942 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5086.406676719585 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 8259.018305689096 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 11567.634304364523 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 875.1494859655699 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 1226.195546487967 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 2005.1393347481887 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 1343.7190502882004 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 2099.697617193063 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3098.3794617156186 | |
