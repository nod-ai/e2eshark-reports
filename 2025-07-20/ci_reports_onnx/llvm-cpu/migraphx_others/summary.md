## Passing Summary

**TOTAL TESTS = 4**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 4 | 100.0% | 100.0% |
| IREE Compilation | 4 | 100.0% | 100.0% |
| Gold Inference | 4 | 100.0% | 100.0% |
| IREE Inference Invocation | 4 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 3 | 75.0% | 75.0% |
## Fail Summary

**TOTAL TESTS = 4**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 1 | 25.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='local-task', backend='llvm-cpu', target_chip='x86_64-linux-gnu', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=True, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/migraphx_others.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/migraphx_others.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| migraphx_agentmodel__AgentModel | Numerics | 1.2434700363389237 | |
| migraphx_cadene__resnext101_64x4di16 | PASS | 4912.456125952303 | |
| migraphx_torchvision__inceptioni32 | PASS | 5263.283517211676 | |
| migraphx_torchvision__resnet50i64 | PASS | 5450.299005024135 | |
