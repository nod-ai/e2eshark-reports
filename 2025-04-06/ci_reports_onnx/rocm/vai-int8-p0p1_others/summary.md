## Passing Summary

**TOTAL TESTS = 59**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 59 | 100.0% | 100.0% |
| IREE Compilation | 59 | 100.0% | 100.0% |
| Gold Inference | 59 | 100.0% | 100.0% |
| IREE Inference Invocation | 0 | 0.0% | 0.0% |
| Inference Comparison (PASS) | 0 | 0.0% | 0.0% |
## Fail Summary

**TOTAL TESTS = 59**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 59 | 100.0% |
| Inference Comparison | 0 | 0.0% |
## Test Run Detail
Test was run with the following arguments:
Namespace(sources=['./e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard1_others_onnx_json/vai-int8-p0p1-shard1_others.json', './e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard2_others_onnx_json/vai-int8-p0p1-shard2_others.json', './e2eshark-reports/ci_reports_rocm_vai-int8-p0p1-shard3_others_onnx_json/vai-int8-p0p1-shard3_others.json'], output='./e2eshark-reports/vai-int8-p0p1_others.json', report=True, report_file='./e2eshark-reports/vai-int8-p0p1_others.md')

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| adv_inception_v3_vaiq | compiled_inference | None | |
| densenet121_vaiq | compiled_inference | None | |
| efficientnet_el.ra_in1k_vaiq | compiled_inference | None | |
| efficientnet_es.ra_in1k_vaiq | compiled_inference | None | |
| gluon_inception_v3_vaiq | compiled_inference | None | |
| gluon_resnet101_v1b_vaiq | compiled_inference | None | |
| gluon_resnet152_v1b_vaiq | compiled_inference | None | |
| gluon_resnet34_v1b_vaiq | compiled_inference | None | |
| gluon_resnet50_v1b_vaiq | compiled_inference | None | |
| gluon_resnext50_32x4d_vaiq | compiled_inference | None | |
| ig_resnext101_32x32d_vaiq | compiled_inference | None | |
| ig_resnext101_32x8d_vaiq | compiled_inference | None | |
| inception_resnet_v2_vaiq | compiled_inference | None | |
| inception_v3_vaiq | compiled_inference | None | |
| mobilenetv3_large_100.miil_in21k_ft_in1k_vaiq | compiled_inference | None | |
| regnetx_008.tv2_in1k_vaiq | compiled_inference | None | |
| regnetx_016.tv2_in1k_vaiq | compiled_inference | None | |
| regnetx_032.tv2_in1k_vaiq | compiled_inference | None | |
| regnetx_080.tv2_in1k_vaiq | compiled_inference | None | |
| regnetx_160.tv2_in1k_vaiq | compiled_inference | None | |
| regnetx_320.tv2_in1k_vaiq | compiled_inference | None | |
| regnety_004.tv2_in1k_vaiq | compiled_inference | None | |
| regnety_016.tv2_in1k_vaiq | compiled_inference | None | |
| regnety_032.tv2_in1k_vaiq | compiled_inference | None | |
| regnety_160.sw_in12k_ft_in1k_train_vaiq | compiled_inference | None | |
| regnety_160.sw_in12k_ft_in1k_vaiq | compiled_inference | None | |
| regnety_160.swag_ft_in1k_vaiq | compiled_inference | None | |
| regnety_160.swag_lc_in1k_vaiq | compiled_inference | None | |
| regnety_160.tv2_in1k_vaiq | compiled_inference | None | |
| regnety_320.swag_ft_in1k_vaiq | compiled_inference | None | |
| regnety_320.swag_lc_in1k_vaiq | compiled_inference | None | |
| regnety_320.tv2_in1k_vaiq | compiled_inference | None | |
| resmlp_12_224.fb_in1k_vaiq | compiled_inference | None | |
| resmlp_24_224.fb_in1k_vaiq | compiled_inference | None | |
| resmlp_36_224.fb_in1k_vaiq | compiled_inference | None | |
| resnet101_vaiq | compiled_inference | None | |
| resnet152_vaiq | compiled_inference | None | |
| resnet18_vaiq | compiled_inference | None | |
| resnet34_vaiq | compiled_inference | None | |
| resnet50_vaiq | compiled_inference | None | |
| resnet50d_vaiq | compiled_inference | None | |
| resnetv2_152x2_bit.goog_teacher_in21k_ft_in1k_384_vaiq | compiled_inference | None | |
| resnext101_32x8d_vaiq | compiled_inference | None | |
| resnext50_32x4d_vaiq | compiled_inference | None | |
| seresnext50_32x4d_vaiq | compiled_inference | None | |
| ssl_resnet18_vaiq | compiled_inference | None | |
| ssl_resnet50_vaiq | compiled_inference | None | |
| ssl_resnext101_32x4d_vaiq | compiled_inference | None | |
| ssl_resnext101_32x8d_vaiq | compiled_inference | None | |
| ssl_resnext50_32x4d_vaiq | compiled_inference | None | |
| swsl_resnet18_vaiq | compiled_inference | None | |
| swsl_resnet50_vaiq | compiled_inference | None | |
| swsl_resnext101_32x16d_vaiq | compiled_inference | None | |
| swsl_resnext101_32x4d_vaiq | compiled_inference | None | |
| swsl_resnext101_32x8d_vaiq | compiled_inference | None | |
| swsl_resnext50_32x4d_vaiq | compiled_inference | None | |
| tf_efficientnetv2_b3.in21k_ft_in1k_train_vaiq | compiled_inference | None | |
| tf_efficientnetv2_b3.in21k_ft_in1k_vaiq | compiled_inference | None | |
| xception_vaiq | compiled_inference | None | |
