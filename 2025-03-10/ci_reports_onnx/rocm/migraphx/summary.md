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
| migraphx_agentmodel__AgentModel | Numerics | 2.1817247338437133 | |
| migraphx_bert__bert-large-uncased | PASS | 18.985730891873974 | |
| migraphx_bert__bertsquad-12 | compilation | None | |
| migraphx_cadene__dpn92i1 | PASS | 5.053332666648203 | |
| migraphx_cadene__inceptionv4i16 | PASS | 29.509199097219607 | |
| migraphx_cadene__resnext101_64x4di1 | PASS | 6.280455513261104 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 29.842149478060055 | |
| migraphx_huggingface-transformers__bert_mrpc8 | PASS | 7.135100722211823 | |
| migraphx_mlperf__bert_large_mlperf | Numerics | 29.166146641075144 | |
| migraphx_mlperf__resnet50_v1 | PASS | 5.243596663403878 | |
| migraphx_models__whisper-tiny-decoder | PASS | 43.642408666528354 | |
| migraphx_models__whisper-tiny-encoder | Numerics | 46.3966950515803 | |
| migraphx_onnx-model-zoo__gpt2-10 | compilation | None | |
| migraphx_ORT__bert_base_cased_1 | PASS | 106.64881623796687 | |
| migraphx_ORT__bert_base_uncased_1 | PASS | 33354.550081333095 | |
| migraphx_ORT__bert_large_uncased_1 | PASS | 27357.038345666904 | |
| migraphx_ORT__distilgpt2_1 | PASS | 249006.78394066865 | |
| migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu | Numerics | 62444.714930999304 | |
| migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu | Numerics | 16196.720205666983 | |
| migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu | Numerics | 36.713528666695574 | |
| migraphx_pytorch-examples__wlang_gru | PASS | 17.33713497026959 | |
| migraphx_pytorch-examples__wlang_lstm | PASS | 8.002393458304544 | |
| migraphx_sd__unet__model | import_model | None | |
| migraphx_sdxl__unet__model | import_model | None | |
| migraphx_torchvision__densenet121i32 | PASS | 18.018277051221677 | |
| migraphx_torchvision__inceptioni1 | PASS | 4.913480861535096 | |
| migraphx_torchvision__inceptioni32 | PASS | 28.165665906514423 | |
| migraphx_torchvision__resnet50i1 | PASS | 3.582756345266574 | |
| migraphx_torchvision__resnet50i64 | PASS | 20.918582009774884 | |
| migx_bench_bert-large-uncased_16_128 | PASS | 25.542694952383457 | |
| migx_bench_bert-large-uncased_16_256 | PASS | 37.698275543733494 | |
| migx_bench_bert-large-uncased_16_384 | PASS | 57.88631355562757 | |
| migx_bench_bert-large-uncased_1_128 | PASS | 12.607390390738814 | |
| migx_bench_bert-large-uncased_1_256 | PASS | 12.438529807047004 | |
| migx_bench_bert-large-uncased_1_384 | PASS | 19.077031252399557 | |
| migx_bench_bert-large-uncased_2_128 | PASS | 12.432122267866708 | |
| migx_bench_bert-large-uncased_2_256 | PASS | 19.065008108120782 | |
| migx_bench_bert-large-uncased_2_384 | PASS | 19.565268564898968 | |
| migx_bench_bert-large-uncased_32_128 | PASS | 36.200051421155074 | |
| migx_bench_bert-large-uncased_32_256 | PASS | 71.84716630017647 | |
| migx_bench_bert-large-uncased_32_384 | PASS | 112.34662249979817 | |
| migx_bench_bert-large-uncased_4_128 | PASS | 19.20587027027953 | |
| migx_bench_bert-large-uncased_4_256 | PASS | 19.833695323783708 | |
| migx_bench_bert-large-uncased_4_384 | PASS | 23.77305389992317 | |
| migx_bench_bert-large-uncased_8_128 | PASS | 19.883376466722915 | |
| migx_bench_bert-large-uncased_8_256 | PASS | 26.035424913533024 | |
| migx_bench_bert-large-uncased_8_384 | PASS | 33.14632923817072 | |
