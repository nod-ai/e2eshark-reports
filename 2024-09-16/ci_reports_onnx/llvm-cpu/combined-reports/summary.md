## Summary

|Stage|Count|
|--|--|
| Total | 8 |
| PASS | 3 |
| Numerics | 2 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 0 |
| native_inference | 0 |
| construct_inputs | 0 |
| compilation | 3 |
| preprocessing | 0 |
| import_model | 0 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/vai-int8-p0p1.json', './e2eshark-reports/vai-hf-cnn-fp32.json', './e2eshark-reports/ci_reports_llvm-cpu_shark-test-suite_onnx.json/shark-test-suite.json', './e2eshark-reports/ci_reports_llvm-cpu_vai-vision-int8_onnx.json/vai-vision-int8.json'], output='./e2eshark-reports/combined_reports.json', report=True, report_file='./e2eshark-reports/combined_reports.md')

| Test | Exit Status | Notes |
|--|--|--|
| adv_inception_v3_vaiq | Numerics | |
| inception_resnet_v2_vaiq | Numerics | |
| resnet200d_vaiq | PASS | |
| bat_resnext26ts.ch_in1k | compilation | |
| efficientnet_b3_pruned.in1k | compilation | |
| tf_efficientnet_b0.aa_in1k | compilation | |
| AlexNet_vaiq_int8 | PASS | |
| DarkNet53_vaiq | PASS | |
