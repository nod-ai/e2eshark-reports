## Summary

|Stage|Count|
|--|--|
| Total | 12 |
| PASS | 0 |
| Numerics | 0 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 5 |
| native_inference | 1 |
| construct_inputs | 0 |
| compilation | 4 |
| preprocessing | 0 |
| import_model | 2 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/vai-int8-p0p1.json', './e2eshark-reports/vai-hf-cnn-fp32.json', './e2eshark-reports/nlp.json', './e2eshark-reports/ci_reports_rocm_shark-test-suite_onnx_json/shark-test-suite.json', './e2eshark-reports/ci_reports_rocm_vai-vision-int8_onnx_json/vai-vision-int8.json', './e2eshark-reports/ci_reports_rocm_migraphx_onnx_json/migraphx.json'], output='./e2eshark-reports/combined_reports.json', report=True, report_file='./e2eshark-reports/combined_reports.md')

| Test | Exit Status | Notes |
|--|--|--|
| adv_inception_v3_vaiq | compiled_inference | |
| inception_resnet_v2_vaiq | compiled_inference | |
| resnet200d_vaiq | compiled_inference | |
| bat_resnext26ts.ch_in1k | compilation | |
| efficientnet_b3_pruned.in1k | import_model | |
| tf_efficientnet_b0.aa_in1k | import_model | |
| model--125M_GPTneo_reward_base--Myashka | compilation | |
| model--bert-finetuned-squad--kenyaari | native_inference | |
| model--finetuning-sentiment-model-3000-samples--nachowdh | compilation | |
| AlexNet_vaiq_int8 | compiled_inference | |
| DarkNet53_vaiq | compiled_inference | |
| migraphx_agentmodel__AgentModel | compilation | |
