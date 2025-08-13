## Passing Summary

**TOTAL TESTS = 43**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 43 | 100.0% | 100.0% |
| IREE Compilation | 39 | 90.7% | 90.7% |
| Gold Inference | 39 | 90.7% | 100.0% |
| IREE Inference Invocation | 39 | 90.7% | 100.0% |
| Inference Comparison (PASS) | 32 | 74.4% | 82.1% |
## Fail Summary

**TOTAL TESTS = 43**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 4 | 9.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 16.3% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_bert__bert-large-uncased | PASS | 377.6139272376895 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 208.45775658057792 | |
| migraphx_cadene__inceptionv4i16 | PASS | 5393.271405249834 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 314.0392638742924 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 426.5687478085359 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 495.6641097863515 | |
| migraphx_mlperf__resnet50_v1 | PASS | 98.3767761361031 | |
| migraphx_models__whisper-tiny-decoder | PASS | 62.4791361165769 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 238.65653036369216 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 196.41414201921884 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 1155.6163057684898 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 601.0846899201472 | |
| migraphx_ORT__distilgpt2_1 | PASS | 869.2971089233955 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 189.2694093597432 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 555.5934067815542 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 89.04421036796909 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 67.7520629018545 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 21.894928437095505 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 1576.2840521832306 | |
| migraphx_torchvision__inceptioni1 | PASS | 214.17161573966345 | |
| migraphx_torchvision__resnet50i1 | PASS | 94.57619721069932 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 1604.493122547865 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 5498.6971492568655 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 9633.340127766132 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 152.67208373794952 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 269.8789820488956 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 368.50447797526914 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 243.63011225230161 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 453.87519150972366 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 655.5957576880852 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 5181.773082042733 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 13647.903878862659 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 23623.54091865321 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 455.54695402582485 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 790.9880553682646 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 1251.8018254389365 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 735.2488885323206 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 1686.9258067260187 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 3446.110574528575 | |
