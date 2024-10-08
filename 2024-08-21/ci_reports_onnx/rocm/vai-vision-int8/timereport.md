Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/DarkNet53_vaiq                       |       2.852 |         1.282 |            0 |          6.976 |       1.107 |
| onnx/models/dla169_vaiq                          |       3.338 |         0.869 |            0 |         14.047 |       1.117 |
| onnx/models/efficientnet_b0.ra_in1k_vaiq         |       3.241 |         0.411 |            0 |          6.5   |       0     |
| onnx/models/EfficientNet_b0_vaiq                 |       2.705 |         0.421 |            0 |         17.337 |       1.25  |
| onnx/models/efficientnet_b1.ft_in1k_vaiq         |       3.511 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b1_vaiq                 |       3.575 |         0.761 |            0 |         23.567 |       1.205 |
| onnx/models/efficientnet_b2.ra_in1k_vaiq         |       3.579 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2_vaiq                 |       3.617 |         0.878 |            0 |         23.618 |       1.218 |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq        |       3.77  |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3_vaiq                 |       3.618 |         1.062 |            0 |         25.63  |       1.337 |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq        |       3.359 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4_vaiq                 |       4.038 |         1.434 |            0 |         31.246 |       1.239 |
| onnx/models/efficientnet_b5.sw_in12k_vaiq        |       5.357 |         3.676 |            0 |         29.194 |       0     |
| onnx/models/EfficientNet_b5_vaiq                 |       4.9   |         1.862 |            0 |         35.221 |       1.32  |
| onnx/models/EfficientNet_b6_vaiq                 |       5.952 |         2.615 |            0 |         38.545 |       1.358 |
| onnx/models/EfficientNet_b7_vaiq                 |       6.983 |         3.713 |            0 |         47.315 |       1.423 |
| onnx/models/efficientnet_el_pruned.in1k_vaiq     |       3.725 |         0.463 |            0 |          7.585 |       1.12  |
| onnx/models/efficientnet_el.ra_in1k_vaiq         |       3.529 |         0.445 |            0 |          6.548 |       1.167 |
| onnx/models/efficientnet_em.ra2_in1k_vaiq        |       3.304 |         0.418 |            0 |          8.514 |       1.089 |
| onnx/models/efficientnet_es_pruned.in1k_vaiq     |       3.91  |         0.379 |            0 |          5.682 |       1.113 |
| onnx/models/efficientnet_es.ra_in1k_vaiq         |       3.243 |         0.344 |            0 |          5.796 |       1.215 |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq      |       3.461 |         0.351 |            0 |          6.657 |       1.169 |
| onnx/models/EfficientNet_v2_l_vaiq               |       6.896 |         5.792 |            0 |         54.627 |       1.569 |
| onnx/models/EfficientNet_v2_m_vaiq               |       5.056 |         2.912 |            0 |         34.19  |       1.283 |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq    |       3.18  |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq    |       2.972 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq    |       3.18  |         0.594 |            0 |         10.872 |       0     |
| onnx/models/EfficientNet_v2_s_vaiq               |       3.109 |         1.083 |            0 |         21.723 |       1.251 |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq            |       2.748 |         0.339 |            0 |          6.624 |       1.056 |
| onnx/models/gernet_l.idstcv_in1k_vaiq            |       2.79  |         0.481 |            0 |          5.609 |       1.059 |
| onnx/models/gernet_m.idstcv_in1k_vaiq            |       2.576 |         0.404 |            0 |          4.737 |       1.039 |
| onnx/models/gernet_s.idstcv_in1k_vaiq            |       2.437 |         0.336 |            0 |          4.17  |       0.987 |
| onnx/models/GoogLeNet_vaiq                       |       2.846 |         0.459 |            0 |         12.798 |       1.233 |
| onnx/models/inception_v3.tf_in1k_vaiq            |       3.618 |         1.365 |            0 |         15.404 |       1.264 |
| onnx/models/Inception_v3_vaiq                    |       3.382 |         1.023 |            0 |         16.689 |       1.34  |
| onnx/models/inception_v4.tf_in1k_vaiq            |       3.894 |         1.85  |            0 |         21.007 |       1.136 |
| onnx/models/lcnet_050.ra2_in1k_vaiq              |       3.051 |         0.298 |            0 |          4.892 |       1.05  |
| onnx/models/lcnet_075.ra2_in1k_vaiq              |       2.688 |         0.332 |            0 |          4.776 |       1.087 |
| onnx/models/lcnet_100.ra2_in1k_vaiq              |       2.837 |         0.314 |            0 |          4.638 |       1.036 |
| onnx/models/mnasnet_100.rmsp_in1k_vaiq           |       3.093 |         0.385 |            0 |          5.272 |       1.062 |
| onnx/models/mnasnet_small.lamb_in1k_vaiq         |       2.482 |         0.298 |            0 |          4.659 |       0     |
| onnx/models/mobilenetv2_050.lamb_in1k_vaiq       |       2.692 |         0.297 |            0 |          4.522 |       1.106 |
| onnx/models/mobilenetv2_100.ra_in1k_vaiq         |       2.498 |         0.276 |            0 |          5.198 |       1.018 |
| onnx/models/mobilenetv2_110d.ra_in1k_vaiq        |       2.853 |         0.324 |            0 |          6.163 |       1.088 |
| onnx/models/mobilenetv2_120d.ra_in1k_vaiq        |       3.322 |         0.353 |            0 |          6.195 |       1.022 |
| onnx/models/mobilenetv2_140.ra_in1k_vaiq         |       2.593 |         0.344 |            0 |          5.602 |       1.008 |
| onnx/models/MobileNetV2_vaiq                     |       2.753 |         0.341 |            0 |          8.591 |       1.239 |
| onnx/models/mobilenetv3_large_100.ra_in1k_vaiq   |       3.574 |         0.342 |            0 |          5.653 |       0     |
| onnx/models/MobileNetV3_large_vaiq               |       2.517 |         0.418 |            0 |         12.064 |       1.1   |
| onnx/models/mobilenetv3_small_050.lamb_in1k_vaiq |       2.636 |         0.343 |            0 |          4.621 |       0     |
| onnx/models/mobilenetv3_small_075.lamb_in1k_vaiq |       2.498 |         0.301 |            0 |          4.929 |       0     |
| onnx/models/mobilenetv3_small_100.lamb_in1k_vaiq |       2.49  |         0.363 |            0 |          4.779 |       0     |
| onnx/models/MobileNetV3_small_vaiq               |       2.555 |         0.38  |            0 |         10.559 |       1.07  |
| onnx/models/ResNet101_vaiq                       |       2.773 |         1.535 |            0 |         11.453 |       1.047 |
| onnx/models/ResNet152_vaiq                       |       3.207 |         2.123 |            0 |         15.351 |       1.148 |
| onnx/models/ResNet18_vaiq                        |       2.365 |         0.515 |            0 |          3.992 |       1.028 |
| onnx/models/resnet32ts.ra2_in1k_vaiq             |       2.494 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k_vaiq             |       2.888 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34_vaiq                        |       2.78  |         0.822 |            0 |          5.696 |       1.062 |
| onnx/models/resnet50.a1_in1k_vaiq                |       2.685 |         1.056 |            0 |          8.145 |       1.064 |
| onnx/models/ResNet50_vaiq                        |       2.936 |         1.16  |            0 |          7.962 |       1.088 |
| onnx/models/RRDB_ESRGAN_pro_vaiq                 |       3.288 |         0     |            0 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_vaiq                     |      15.133 |         3.06  |            0 |         37.457 |      49.319 |
| onnx/models/SqueezeNet_1_0_vaiq                  |       2.39  |         0.261 |            0 |          5.1   |       1.015 |
| onnx/models/SqueezeNet_1_1_vaiq                  |       2.59  |         0.282 |            0 |          5.422 |       1.04  |
| onnx/models/VGG11_bn_vaiq                        |       3.294 |         3.139 |            0 |          5.093 |       1.028 |
| onnx/models/VGG11_vaiq                           |       3.191 |         2.926 |            0 |          5.685 |       1.046 |
| onnx/models/VGG13_bn_vaiq                        |       3.035 |         2.983 |            0 |          5.651 |       1.047 |
| onnx/models/VGG13_vaiq                           |       2.959 |         2.963 |            0 |          5.494 |       1.027 |
| onnx/models/VGG16_bn_vaiq                        |       3.087 |         3.463 |            0 |          6.084 |       1.042 |
| onnx/models/VGG16_vaiq                           |       2.743 |         3.449 |            0 |          6.221 |       1.04  |
| onnx/models/VGG19_bn_vaiq                        |       2.797 |         3.369 |            0 |          7.523 |       1.348 |
| onnx/models/VGG19_vaiq                           |       4.109 |         3.399 |            0 |          6.095 |       1.03  |
| onnx/models/WideResNet_101_2_vaiq                |       3.378 |         3.346 |            0 |         12.886 |       1.14  |
| onnx/models/WideResNet_50_2_vaiq                 |       2.812 |         1.916 |            0 |          8.68  |       1.106 |
| onnx/models/YoloNetV3_vaiq                       |       3.193 |         1.981 |            0 |         11.966 |       1.122 |
| onnx/models/Yolov8m_vaiq                         |       3.288 |         1.193 |            0 |         13.739 |       1.137 |
| onnx/models/Yolov8n_vaiq                         |       2.559 |         0.497 |            0 |         11.198 |       1.108 |
