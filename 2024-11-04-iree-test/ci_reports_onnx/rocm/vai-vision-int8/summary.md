## Passing Summary

**TOTAL TESTS = 78**
|Stage|# Passing|% of Total|% of Attempted|
|--|--|--|--|
| Setup | 78 | 100.0% | 100.0% |
| IREE Compilation | 78 | 100.0% | 100.0% |
| Gold Inference | 78 | 100.0% | 100.0% |
| IREE Inference Invocation | 78 | 100.0% | 100.0% |
| Inference Comparison (PASS) | 16 | 20.5% | 20.5% |
## Fail Summary

**TOTAL TESTS = 78**
|Stage|# Failed at Stage|% of Total|
|--|--|--|
| Setup | 0 | 0.0% |
| IREE Compilation | 0 | 0.0% |
| Gold Inference | 0 | 0.0% |
| IREE Inference Invocation | 0 | 0.0% |
| Inference Comparison | 62 | 79.5% |
## Test Run Detail
Test was run with the following arguments:
Namespace(device='hip', backend='rocm', iree_compile_args=None, mode='cl-onnx-iree', torchtolinalg=False, stages=None, skip_stages=None, benchmark=False, load_inputs=False, groups='all', test_filter=None, testsfile='onnx_tests/models/external_lists/vai-vision-int8.txt', tolerance=None, verbose=True, rundirectory='./test-onnx', no_artifacts=False, cleanup='3', report=True, report_file='reports/vai-vision-int8.md', get_metadata=True)

| Test | Exit Status | Mean Benchmark Time (ms) | Notes |
|--|--|--|--|
| DarkNet53_vaiq | Numerics | None | |
| dla169_vaiq | Numerics | None | |
| efficientnet_b0.ra_in1k_vaiq | Numerics | None | |
| EfficientNet_b0_vaiq | Numerics | None | |
| efficientnet_b1.ft_in1k_vaiq | PASS | None | |
| EfficientNet_b1_vaiq | PASS | None | |
| efficientnet_b2.ra_in1k_vaiq | Numerics | None | |
| EfficientNet_b2_vaiq | Numerics | None | |
| efficientnet_b3.ra2_in1k_vaiq | Numerics | None | |
| EfficientNet_b3_vaiq | Numerics | None | |
| efficientnet_b4.ra2_in1k_vaiq | Numerics | None | |
| EfficientNet_b4_vaiq | Numerics | None | |
| efficientnet_b5.sw_in12k_vaiq | Numerics | None | |
| EfficientNet_b5_vaiq | PASS | None | |
| EfficientNet_b6_vaiq | PASS | None | |
| EfficientNet_b7_vaiq | Numerics | None | |
| efficientnet_el.ra_in1k_vaiq | Numerics | None | |
| efficientnet_el_pruned.in1k_vaiq | Numerics | None | |
| efficientnet_em.ra2_in1k_vaiq | Numerics | None | |
| efficientnet_es.ra_in1k_vaiq | Numerics | None | |
| efficientnet_es_pruned.in1k_vaiq | Numerics | None | |
| efficientnet_lite0.ra_in1k_vaiq | PASS | None | |
| EfficientNet_v2_l_vaiq | Numerics | None | |
| EfficientNet_v2_m_vaiq | Numerics | None | |
| EfficientNet_v2_s_vaiq | Numerics | None | |
| efficientnetv2_rw_m.agc_in1k_vaiq | Numerics | None | |
| efficientnetv2_rw_s.ra2_in1k_vaiq | Numerics | None | |
| efficientnetv2_rw_t.ra2_in1k_vaiq | Numerics | None | |
| fbnetc_100.rmsp_in1k_vaiq | PASS | None | |
| gernet_l.idstcv_in1k_vaiq | Numerics | None | |
| gernet_m.idstcv_in1k_vaiq | Numerics | None | |
| gernet_s.idstcv_in1k_vaiq | Numerics | None | |
| GoogLeNet_vaiq | Numerics | None | |
| inception_v3.tf_in1k_vaiq | Numerics | None | |
| Inception_v3_vaiq | Numerics | None | |
| inception_v4.tf_in1k_vaiq | Numerics | None | |
| lcnet_050.ra2_in1k_vaiq | Numerics | None | |
| lcnet_075.ra2_in1k_vaiq | Numerics | None | |
| lcnet_100.ra2_in1k_vaiq | Numerics | None | |
| mnasnet_100.rmsp_in1k_vaiq | PASS | None | |
| mnasnet_small.lamb_in1k_vaiq | PASS | None | |
| mobilenetv2_050.lamb_in1k_vaiq | PASS | None | |
| mobilenetv2_100.ra_in1k_vaiq | PASS | None | |
| mobilenetv2_110d.ra_in1k_vaiq | PASS | None | |
| mobilenetv2_120d.ra_in1k_vaiq | PASS | None | |
| mobilenetv2_140.ra_in1k_vaiq | PASS | None | |
| MobileNetV2_vaiq | PASS | None | |
| mobilenetv3_large_100.ra_in1k_vaiq | PASS | None | |
| MobileNetV3_large_vaiq | PASS | None | |
| mobilenetv3_small_050.lamb_in1k_vaiq | Numerics | None | |
| mobilenetv3_small_075.lamb_in1k_vaiq | Numerics | None | |
| mobilenetv3_small_100.lamb_in1k_vaiq | Numerics | None | |
| MobileNetV3_small_vaiq | Numerics | None | |
| ResNet101_vaiq | Numerics | None | |
| ResNet152_vaiq | Numerics | None | |
| ResNet18_vaiq | Numerics | None | |
| resnet32ts.ra2_in1k_vaiq | Numerics | None | |
| resnet33ts.ra2_in1k_vaiq | Numerics | None | |
| ResNet34_vaiq | Numerics | None | |
| resnet50.a1_in1k_vaiq | Numerics | None | |
| ResNet50_vaiq | Numerics | None | |
| RRDB_ESRGAN_pro_vaiq | Numerics | None | |
| RRDB_ESRGAN_vaiq | Numerics | None | |
| SqueezeNet_1_0_vaiq | Numerics | None | |
| SqueezeNet_1_1_vaiq | Numerics | None | |
| VGG11_bn_vaiq | Numerics | None | |
| VGG11_vaiq | Numerics | None | |
| VGG13_bn_vaiq | Numerics | None | |
| VGG13_vaiq | Numerics | None | |
| VGG16_bn_vaiq | Numerics | None | |
| VGG16_vaiq | Numerics | None | |
| VGG19_bn_vaiq | Numerics | None | |
| VGG19_vaiq | Numerics | None | |
| WideResNet_101_2_vaiq | Numerics | None | |
| WideResNet_50_2_vaiq | Numerics | None | |
| YoloNetV3_vaiq | Numerics | None | |
| Yolov8m_vaiq | Numerics | None | |
| Yolov8n_vaiq | Numerics | None | |