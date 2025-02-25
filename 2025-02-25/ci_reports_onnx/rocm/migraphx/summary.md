## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 35 | 74.5% | 74.5% |
| Gold Inference | 35 | 74.5% | 100.0% |
| IREE Inference Invocation | 35 | 74.5% | 100.0% |
| Inference Comparison (PASS) | 28 | 59.6% | 80.0% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 12 | 25.5% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.7200590109847445 | |
| migraphx_bert__bert-large-uncased | PASS | 19.56165332726582 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | compilation | None | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | compilation | None | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.078407788649201 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 28.378193555964206 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.096083455719053 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.81779597800536 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.49203498728382 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.93610035296943 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 107.95907199471479 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 458.7626891831557 | |
| migraphx_ORT__distilgpt2_1 | PASS | 59.49513242942177 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 61.79694501175121 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 240.72664031862382 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 35.69077158738908 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 18.208421267535503 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.010547357921799 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | compilation | None | |
| migraphx_torchvision__inceptioni1 | PASS | 4.8999430135213755 | |
| migraphx_torchvision__inceptioni32 | compilation | None | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | compilation | None | |
| migx_bench_bert-large-uncased_16_128 | PASS | 32.3466197340608 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 53.56086317736369 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 69.01765121147037 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.116668856938253 | |
| migx_bench_bert-large-uncased_1_256 | Numerics | 43.176073798288904 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.27272949790306 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.800472296040617 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 295.49420949382085 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 20.868649411782187 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 237.7794760730907 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 98.02541153372398 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 138.15363535347083 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.413123959865496 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 16.565193774091988 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 25.182272914597494 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.12418130558689 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.98609398570485 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 39.09358815117566 | |
