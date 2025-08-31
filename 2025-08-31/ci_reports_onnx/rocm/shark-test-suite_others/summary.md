## Passing Summary

**TOTAL TESTS = 2**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 2 | 100.0% | 100.0% |
| IREE Compilation | 1 | 50.0% | 50.0% |
| Gold Inference | 1 | 50.0% | 100.0% |
| IREE Inference Invocation | 1 | 50.0% | 100.0% |
| Inference Comparison (PASS) | 1 | 50.0% | 100.0% |
## Fail Summary

**TOTAL TESTS = 2**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 1 | 50.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/shark-test-suite_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/shark-test-suite_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| resnet50_vaiq_int8 | PASS | None | |
| yolov8n_vaiq_int8 | compilation | None | |
