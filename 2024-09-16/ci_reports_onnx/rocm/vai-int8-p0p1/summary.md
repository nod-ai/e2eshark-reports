## Summary

|Stage|Count|
|--|--|
| Total | 3 |
| PASS | 1 |
| Numerics | 2 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 0 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 0 |
| preprocessing | 0 |
| import_model | 0 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard1_onnx.json/vai-int8-p0p1-shard1.json', './e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard2_onnx.json/vai-int8-p0p1-shard2.json', './e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard3_onnx.json/vai-int8-p0p1-shard3.json'], output='./e2eshark-reports/vai-int8-p0p1.json', report=True, report_file='./e2eshark-reports/vai-int8-p0p1.md')

| Test | Exit Status | Notes |
|--|--|--|
| adv_inception_v3_vaiq | Numerics | |
| inception_resnet_v2_vaiq | Numerics | |
| resnet200d_vaiq | PASS | |
