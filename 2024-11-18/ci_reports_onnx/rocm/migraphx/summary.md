## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 40 | 85.1% | 85.1% |
| Gold Inference | 40 | 85.1% | 100.0% |
| IREE Inference Invocation | 40 | 85.1% | 100.0% |
| Inference Comparison (PASS) | 33 | 70.2% | 82.5% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 7 | 14.9% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.97899056101839 | |
| migraphx_bert__bertsquad-12 | PASS | 211.0604208687113 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 151.45385799308616 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 212.653423142102 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.515617875805031 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 43.741384676347174 | |
| migraphx_mlperf__resnet50_v1 | PASS | 6.5514186511413675 | |
| migraphx_models__whisper-tiny-decoder | PASS | 32.70426450762898 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 52.61032171069811 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 112.83321678638458 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 113.00505568376845 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 368.5181306209415 | |
| migraphx_ORT__distilgpt2_1 | PASS | 65.59551996884471 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 72.0891410174469 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 274.2828188671006 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 39.271689942289214 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 24.577599614858627 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 17.54112275150733 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 50.83049547725489 | |
| migraphx_torchvision__inceptioni1 | PASS | 15.944098531635419 | |
| migraphx_torchvision__inceptioni32 | PASS | 146.1325948126614 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 182.56099130182216 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.963144740769785 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 57.115836431168844 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 72.77393053906658 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.477905769832432 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.852695459682566 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.792730325744262 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 13.320942946638054 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.970022660990553 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.506202004578274 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 68.25379783598085 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 103.89256745665556 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 144.069349920998 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 15.010143587273275 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 17.26489509190849 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 26.600931687519335 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.976365020764728 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 27.91016213595867 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 41.02971360050872 | |
