Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/DarkNet53_vaiq                       |       2.778 |         1.367 |            0 |          0.065 |           0 |
| onnx/models/dla169_vaiq                          |       3.146 |         0.945 |            0 |          0.062 |           0 |
| onnx/models/efficientnet_b0.ra_in1k_vaiq         |       3.269 |         0.455 |            0 |          0.074 |           0 |
| onnx/models/EfficientNet_b0_vaiq                 |       3.314 |         0.452 |            0 |          0.07  |           0 |
| onnx/models/efficientnet_b1.ft_in1k_vaiq         |       3.314 |         0     |            0 |          0     |           0 |
| onnx/models/EfficientNet_b1_vaiq                 |       3.611 |         0.588 |            0 |          0.065 |           0 |
| onnx/models/efficientnet_b2.ra_in1k_vaiq         |       3.612 |         0     |            0 |          0     |           0 |
| onnx/models/EfficientNet_b2_vaiq                 |       3.451 |         0.652 |            0 |          0.076 |           0 |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq        |       3.334 |         0     |            0 |          0     |           0 |
| onnx/models/EfficientNet_b3_vaiq                 |       3.929 |         0.691 |            0 |          0.062 |           0 |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq        |       2.832 |         0     |            0 |          0     |           0 |
| onnx/models/EfficientNet_b4_vaiq                 |       3.566 |         0.958 |            0 |          0.061 |           0 |
| onnx/models/efficientnet_b5.sw_in12k_vaiq        |       3.799 |         3.208 |            0 |          0.082 |           0 |
| onnx/models/EfficientNet_b5_vaiq                 |       5.373 |         2.147 |            0 |          0.071 |           0 |
| onnx/models/EfficientNet_b6_vaiq                 |       5.914 |         2.872 |            0 |          0.074 |           0 |
| onnx/models/EfficientNet_b7_vaiq                 |       8.045 |         3.499 |            0 |          0.073 |           0 |
| onnx/models/efficientnet_el_pruned.in1k_vaiq     |       3.593 |         0.418 |            0 |          0.062 |           0 |
| onnx/models/efficientnet_el.ra_in1k_vaiq         |       3.283 |         0.42  |            0 |          0.074 |           0 |
| onnx/models/efficientnet_em.ra2_in1k_vaiq        |       3.644 |         0.407 |            0 |          0.072 |           0 |
| onnx/models/efficientnet_es_pruned.in1k_vaiq     |       3.359 |         0.384 |            0 |          0.068 |           0 |
| onnx/models/efficientnet_es.ra_in1k_vaiq         |       3.581 |         0.379 |            0 |          0.081 |           0 |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq      |       3.548 |         0.364 |            0 |          0.079 |           0 |
| onnx/models/EfficientNet_v2_l_vaiq               |       6.058 |         6.363 |            0 |          0.068 |           0 |
| onnx/models/EfficientNet_v2_m_vaiq               |       5.148 |         3.239 |            0 |          0.065 |           0 |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq    |       4.195 |         0     |            0 |          0     |           0 |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq    |       3.57  |         0     |            0 |          0     |           0 |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq    |       3.78  |         0.729 |            0 |          0.067 |           0 |
| onnx/models/EfficientNet_v2_s_vaiq               |       4.099 |         1.568 |            0 |          0.065 |           0 |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq            |       3.184 |         0.389 |            0 |          0.074 |           0 |
| onnx/models/gernet_l.idstcv_in1k_vaiq            |       3.423 |         0.613 |            0 |          0.063 |           0 |
| onnx/models/gernet_m.idstcv_in1k_vaiq            |       3.296 |         0.544 |            0 |          0.075 |           0 |
| onnx/models/gernet_s.idstcv_in1k_vaiq            |       2.959 |         0.398 |            0 |          0.074 |           0 |
| onnx/models/GoogLeNet_vaiq                       |       3.518 |         0.578 |            0 |          0.072 |           0 |
| onnx/models/inception_v3.tf_in1k_vaiq            |       3.602 |         1.725 |            0 |          0.068 |           0 |
| onnx/models/Inception_v3_vaiq                    |       3.4   |         1.466 |            0 |          0.076 |           0 |
| onnx/models/inception_v4.tf_in1k_vaiq            |       3.815 |         2.902 |            0 |          0.074 |           0 |
| onnx/models/lcnet_050.ra2_in1k_vaiq              |       3.367 |         0.317 |            0 |          0.063 |           0 |
| onnx/models/lcnet_075.ra2_in1k_vaiq              |       3.221 |         0.325 |            0 |          0.073 |           0 |
| onnx/models/lcnet_100.ra2_in1k_vaiq              |       3.37  |         0.336 |            0 |          0.075 |           0 |
| onnx/models/mnasnet_100.rmsp_in1k_vaiq           |       3.55  |         0.344 |            0 |          0.074 |           0 |
| onnx/models/mnasnet_small.lamb_in1k_vaiq         |       3.691 |         0.327 |            0 |          0.064 |           0 |
| onnx/models/mobilenetv2_050.lamb_in1k_vaiq       |       3.381 |         0.426 |            0 |          0.09  |           0 |
| onnx/models/mobilenetv2_100.ra_in1k_vaiq         |       3.417 |         0.351 |            0 |          0.077 |           0 |
| onnx/models/mobilenetv2_110d.ra_in1k_vaiq        |       3.232 |         0.378 |            0 |          0.078 |           0 |
| onnx/models/mobilenetv2_120d.ra_in1k_vaiq        |       3.565 |         0.405 |            0 |          0.074 |           0 |
| onnx/models/mobilenetv2_140.ra_in1k_vaiq         |       3.559 |         0.369 |            0 |          0.071 |           0 |
| onnx/models/MobileNetV2_vaiq                     |       3.019 |         0.41  |            0 |          0.07  |           0 |
| onnx/models/mobilenetv3_large_100.ra_in1k_vaiq   |       3.353 |         0.414 |            0 |          0.083 |           0 |
| onnx/models/MobileNetV3_large_vaiq               |       3.547 |         0.618 |            0 |          0.064 |           0 |
| onnx/models/mobilenetv3_small_050.lamb_in1k_vaiq |       3.328 |         0.412 |            0 |          0.076 |           0 |
| onnx/models/mobilenetv3_small_075.lamb_in1k_vaiq |       3.704 |         0.372 |            0 |          0.061 |           0 |
| onnx/models/mobilenetv3_small_100.lamb_in1k_vaiq |       3.282 |         0.386 |            0 |          0.07  |           0 |
| onnx/models/MobileNetV3_small_vaiq               |       3.148 |         0.472 |            0 |          0.079 |           0 |
| onnx/models/ResNet101_vaiq                       |       4.013 |         2.414 |            0 |          0.08  |           0 |
| onnx/models/ResNet152_vaiq                       |       4.067 |         2.951 |            0 |          0.087 |           0 |
| onnx/models/ResNet18_vaiq                        |       3.503 |         0.782 |            0 |          0.072 |           0 |
| onnx/models/resnet32ts.ra2_in1k_vaiq             |       3.245 |         0     |            0 |          0     |           0 |
| onnx/models/resnet33ts.ra2_in1k_vaiq             |       3.407 |         0     |            0 |          0     |           0 |
| onnx/models/ResNet34_vaiq                        |       3.707 |         1.18  |            0 |          0.071 |           0 |
| onnx/models/resnet50.a1_in1k_vaiq                |       3.501 |         1.507 |            0 |          0.078 |           0 |
| onnx/models/ResNet50_vaiq                        |       3.626 |         1.56  |            0 |          0.071 |           0 |
| onnx/models/RRDB_ESRGAN_pro_vaiq                 |       3.989 |         0     |            0 |          0     |           0 |
| onnx/models/RRDB_ESRGAN_vaiq                     |      18.158 |         3.453 |            0 |          0.082 |           0 |
| onnx/models/SqueezeNet_1_0_vaiq                  |       3.576 |         0.341 |            0 |          0.069 |           0 |
| onnx/models/SqueezeNet_1_1_vaiq                  |       3.467 |         0.312 |            0 |          0.074 |           0 |
| onnx/models/VGG11_bn_vaiq                        |       4.38  |         5.859 |            0 |          0.073 |           0 |
| onnx/models/VGG11_vaiq                           |       4.788 |         5.549 |            0 |          0.08  |           0 |
| onnx/models/VGG13_bn_vaiq                        |       4.403 |         6.008 |            0 |          0.068 |           0 |
| onnx/models/VGG13_vaiq                           |       4.591 |         5.536 |            0 |          0.075 |           0 |
| onnx/models/VGG16_bn_vaiq                        |       4.321 |         5.564 |            0 |          0.068 |           0 |
| onnx/models/VGG16_vaiq                           |       4.976 |         6.895 |            0 |          0.077 |           0 |
| onnx/models/VGG19_bn_vaiq                        |       4.818 |         5.622 |            0 |          0.07  |           0 |
| onnx/models/VGG19_vaiq                           |       4.457 |         6.273 |            0 |          0.074 |           0 |
| onnx/models/WideResNet_101_2_vaiq                |       4.56  |         5.721 |            0 |          0.079 |           0 |
| onnx/models/WideResNet_50_2_vaiq                 |       3.927 |         3.448 |            0 |          0.072 |           0 |
| onnx/models/YoloNetV3_vaiq                       |       4.374 |         3.783 |            0 |          0.08  |           0 |
| onnx/models/Yolov8m_vaiq                         |       4.446 |         1.972 |            0 |          0.076 |           0 |
| onnx/models/Yolov8n_vaiq                         |       4.357 |         0.584 |            0 |          0.079 |           0 |
