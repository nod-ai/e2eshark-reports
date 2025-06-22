## Passing Summary

**TOTAL TESTS = 4**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 4 | 100.0% | 100.0% |
| IREE Compilation | 4 | 100.0% | 100.0% |
| Gold Inference | 4 | 100.0% | 100.0% |
| IREE Inference Invocation | 4 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 4**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 4 | 100.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', target_chip='gfx942', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.7581713942231867 | |
| migraphx_cadene__resnext101_64x4di16 | Numerics | 16.380514568728646 | |
| migraphx_torchvision__inceptioni32 | Numerics | 19.109721236803512 | |
| migraphx_torchvision__resnet50i64 | Numerics | 14.804195240786711 | |
