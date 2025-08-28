## Passing Summary

**TOTAL TESTS = 12**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 12 | 100.0% | 100.0% |
| IREE Compilation | 2 | 16.7% | 16.7% |
| Gold Inference | 2 | 16.7% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 12**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 10 | 83.3% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 2 | 16.7% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/onnx_model_zoo_validated_text_unique.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/onnx_model_zoo_validated_text_unique.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| bertsquad-10 | compilation | None | |
| bertsquad-12 | compilation | None | |
| bertsquad-12-int8 | compilation | None | |
| bertsquad-8 | compilation | None | |
| bidaf-11-int8 | compilation | None | |
| bidaf-9 | compilation | None | |
| gpt2-10 | compilation | None | |
| gpt2-lm-head-10 | compilation | None | |
| roberta-base-11 | compilation | None | |
| roberta-sequence-classification-9 | compilation | None | |
| t5-decoder-with-lm-head-12 | compiled_inference | None | |
| t5-encoder-12 | compiled_inference | None | |
