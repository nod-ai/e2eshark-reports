## Passing Summary

**TOTAL TESTS = 5**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 5 | 100.0% | 100.0% |
| IREE Compilation | 2 | 40.0% | 40.0% |
| Gold Inference | 2 | 40.0% | 100.0% |
| IREE Inference Invocation | 2 | 40.0% | 100.0% |
| Inference Comparison (PASS) | 1 | 20.0% | 50.0% |
## Fail Summary

**TOTAL TESTS = 5**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 3 | 60.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 1 | 20.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/vai-vision-int8_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/vai-vision-int8_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| DarkNet53_vaiq | compilation | None | |
| efficientnet_el.ra_in1k_vaiq | compilation | None | |
| efficientnet_es.ra_in1k_vaiq | PASS | None | |
| SqueezeNet_1_1_vaiq | Numerics | None | |
| Yolov8n_vaiq | compilation | None | |
