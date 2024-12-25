## Passing Summary

**TOTAL TESTS = 47**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 47 | 100.0% | 100.0% |
| IREE Compilation | 39 | 83.0% | 83.0% |
| Gold Inference | 39 | 83.0% | 100.0% |
| IREE Inference Invocation | 39 | 83.0% | 100.0% |
| Inference Comparison (PASS) | 32 | 68.1% | 82.1% |
## Fail Summary

**TOTAL TESTS = 47**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 8 | 17.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 7 | 14.9% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | compilation | None | |
| migraphx_bert__bert-large-uncased | PASS | 19.54284631129768 | |
| migraphx_bert__bertsquad-12 | PASS | 7.8966630911775715 | |
| migraphx_cadene__dpn92i1 | compilation | None | |
| migraphx_cadene__inceptionv4i16 | PASS | 83.28857571662714 | |
| migraphx_cadene__resnext101_64x4di1 | compilation | None | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 187.55323548490801 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.375894623692147 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 24.76346993353218 | |
| migraphx_mlperf__resnet50_v1 | compilation | None | |
| migraphx_models__whisper-tiny-decoder | PASS | 35.106585337780416 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 47.62656936008069 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 101.01040698853986 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 101.00172129681421 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 502.37913406454027 | |
| migraphx_ORT__distilgpt2_1 | PASS | 54.0970228970624 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 63.4542112803143 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 296.3247167256971 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 32.14469736187973 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 15.437211248057858 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 6.504121573938839 | |
| migraphx_sd__unet__model | compilation | None | |
| migraphx_sdxl__unet__model | compilation | None | |
| migraphx_torchvision__densenet121i32 | PASS | 56.280590891320664 | |
| migraphx_torchvision__inceptioni1 | PASS | 16.4297794554989 | |
| migraphx_torchvision__inceptioni32 | PASS | 68.74122062387566 | |
| migraphx_torchvision__resnet50i1 | compilation | None | |
| migraphx_torchvision__resnet50i64 | PASS | 144.24503430103263 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 36.65844255470131 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 60.2403292303077 | |
| migx_bench_bert-large-uncased_16_384 | Numerics | 82.02819846984413 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 13.080494478344917 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 13.268099728760857 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.49442215091376 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.63727955520153 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 13.237035941660592 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 21.93859873417144 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 73.38386417056122 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 115.28370570805338 | |
| migx_bench_bert-large-uncased_32_384 | Numerics | 165.04451170718917 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 14.413922524624533 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 18.27309386104218 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 27.46981791913127 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 20.84403963960415 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 30.376403660014052 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 44.99737819423899 | |
