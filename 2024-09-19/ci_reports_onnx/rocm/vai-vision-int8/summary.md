## Summary

|Stage|Count|
|--|--|
| Total | 1 |
| PASS | 0 |
| Numerics | 0 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 1 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 0 |
| preprocessing | 0 |
| import_model | 0 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/vai-vision-int8.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, report=True, report_file='reports/vai-vision-int8.md')

| Test | Exit Status | Notes |
|--|--|--|
| DarkNet53_vaiq | compiled_inference | |
