## Summary

|Stage|Count|
|--|--|
| Total | 3 |
| PASS | 0 |
| Numerics | 0 |
| results-summary | 0 |
| postprocessing | 0 |
| compiled_inference | 0 |
| native_inference | 1 |
| construct_inputs | 0 |
| compilation | 2 |
| preprocessing | 0 |
| import_model | 0 |
| setup | 0 |

## Test Run Detail 
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_nlp-shard1_onnx_json/nlp-shard1.json', './e2eshark-reports/ci_reports_rocm_nlp-shard2_onnx_json/nlp-shard2.json', './e2eshark-reports/ci_reports_rocm_nlp-shard3_onnx_json/nlp-shard3.json'], output='./e2eshark-reports/nlp.json', report=True, report_file='./e2eshark-reports/nlp.md')

| Test | Exit Status | Notes |
|--|--|--|
| model--125M_GPTneo_reward_base--Myashka | compilation | |
| model--bert-finetuned-squad--kenyaari | native_inference | |
| model--finetuning-sentiment-model-3000-samples--nachowdh | compilation | |
