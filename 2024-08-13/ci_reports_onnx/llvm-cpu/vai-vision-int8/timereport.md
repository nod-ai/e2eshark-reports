Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/DarkNet53_vaiq                       |       6.503 |         4.337 |            0 |         20.626 |       0.075 |
| onnx/models/dla169_vaiq                          |       7.634 |         2.143 |            0 |         37.826 |       0.066 |
| onnx/models/efficientnet_b0.ra_in1k_vaiq         |       7.969 |         1.217 |            0 |         32.604 |       0.056 |
| onnx/models/EfficientNet_b0_vaiq                 |       6.202 |         1.232 |            0 |         35.408 |       0.077 |
| onnx/models/efficientnet_b1.ft_in1k_vaiq         |       6.605 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b1_vaiq                 |       6.304 |         1.451 |            0 |         46.558 |       0.063 |
| onnx/models/efficientnet_b2.ra_in1k_vaiq         |       6.336 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2_vaiq                 |       5.773 |         2.102 |            0 |         44.208 |       0.062 |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq        |       5.318 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3_vaiq                 |       6.592 |         1.829 |            0 |         47.134 |       0.066 |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq        |       7.972 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4_vaiq                 |       7.397 |         2.626 |            0 |         54.751 |       0.054 |
| onnx/models/efficientnet_b5.sw_in12k_vaiq        |       8.812 |         6.585 |            0 |         60.135 |       0.249 |
| onnx/models/EfficientNet_b5_vaiq                 |       7.868 |         3.745 |            0 |         62.788 |       0.058 |
| onnx/models/EfficientNet_b6_vaiq                 |       8.256 |         4.682 |            0 |         71.89  |       0.119 |
| onnx/models/EfficientNet_b7_vaiq                 |      10.637 |         6.352 |            0 |         43.665 |       0.311 |
| onnx/models/efficientnet_el_pruned.in1k_vaiq     |       7.368 |         1.061 |            0 |         13.547 |       0.053 |
| onnx/models/efficientnet_el.ra_in1k_vaiq         |       7.295 |         0.839 |            0 |         10.775 |       0.058 |
| onnx/models/efficientnet_em.ra2_in1k_vaiq        |       6.838 |         0.911 |            0 |          9.915 |       0.201 |
| onnx/models/efficientnet_es_pruned.in1k_vaiq     |       5.58  |         0.924 |            0 |          8.571 |       0.051 |
| onnx/models/efficientnet_es.ra_in1k_vaiq         |       7.045 |         0.919 |            0 |          9.902 |       0.21  |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq      |       6.794 |         0.834 |            0 |          9.425 |       0.067 |
| onnx/models/EfficientNet_v2_l_vaiq               |       9.562 |        11.012 |            0 |         64.111 |       0.058 |
| onnx/models/EfficientNet_v2_m_vaiq               |       8.552 |         5.452 |            0 |         48.709 |       0.054 |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq    |       6.027 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq    |       5.398 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq    |       5.535 |         1.519 |            0 |         25.047 |       0.051 |
| onnx/models/EfficientNet_v2_s_vaiq               |       5.695 |         2.784 |            0 |         32.866 |       0.053 |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq            |       6.026 |         0.905 |            0 |         12.031 |       0.05  |
| onnx/models/gernet_l.idstcv_in1k_vaiq            |       5.355 |         2.656 |            0 |         10.029 |       0.053 |
| onnx/models/gernet_m.idstcv_in1k_vaiq            |       5.226 |         1.22  |            0 |          6.003 |       0.045 |
| onnx/models/gernet_s.idstcv_in1k_vaiq            |       5.025 |         0.75  |            0 |         10.682 |       0.188 |
| onnx/models/GoogLeNet_vaiq                       |       7.412 |         1.227 |            0 |         32.299 |       0.052 |
| onnx/models/inception_v3.tf_in1k_vaiq            |       6.161 |         2.802 |            0 |         36.846 |       0.112 |
| onnx/models/Inception_v3_vaiq                    |       6.254 |         2.667 |            0 |         37.796 |       0.05  |
| onnx/models/inception_v4.tf_in1k_vaiq            |       6.326 |         4.989 |            0 |         48.608 |       0.053 |
| onnx/models/lcnet_050.ra2_in1k_vaiq              |       5.713 |         0.806 |            0 |         14.818 |       0.053 |
| onnx/models/lcnet_075.ra2_in1k_vaiq              |       5.557 |         0.807 |            0 |         15.702 |       0.101 |
| onnx/models/lcnet_100.ra2_in1k_vaiq              |       5.386 |         1.193 |            0 |         15.001 |       0.046 |
| onnx/models/mnasnet_100.rmsp_in1k_vaiq           |       5.27  |         0.836 |            0 |         20.251 |       0.055 |
| onnx/models/mnasnet_small.lamb_in1k_vaiq         |       5.183 |         0.927 |            0 |         12.406 |       0.054 |
| onnx/models/mobilenetv2_050.lamb_in1k_vaiq       |       7.04  |         0.862 |            0 |         18.618 |       0.05  |
| onnx/models/mobilenetv2_100.ra_in1k_vaiq         |       5.849 |         0.912 |            0 |         18.889 |       0.053 |
| onnx/models/mobilenetv2_110d.ra_in1k_vaiq        |       5.949 |         0.935 |            0 |         19.631 |       0.048 |
| onnx/models/mobilenetv2_120d.ra_in1k_vaiq        |       5.571 |         0.784 |            0 |         20.108 |       0.054 |
| onnx/models/mobilenetv2_140.ra_in1k_vaiq         |       5.992 |         0.954 |            0 |         14.767 |       0.055 |
| onnx/models/MobileNetV2_vaiq                     |       5.236 |         1.015 |            0 |         18.235 |       0.091 |
| onnx/models/mobilenetv3_large_100.ra_in1k_vaiq   |       5.341 |         0.924 |            0 |         20.771 |       0.047 |
| onnx/models/MobileNetV3_large_vaiq               |       5.588 |         1.253 |            0 |         22.43  |       0.06  |
| onnx/models/mobilenetv3_small_050.lamb_in1k_vaiq |       5.26  |         0.726 |            0 |         13.796 |       0.053 |
| onnx/models/mobilenetv3_small_075.lamb_in1k_vaiq |       5.552 |         1.013 |            0 |         15.177 |       0.056 |
| onnx/models/mobilenetv3_small_100.lamb_in1k_vaiq |       5.513 |         0.869 |            0 |         14.133 |       0.053 |
| onnx/models/MobileNetV3_small_vaiq               |       5.268 |         1.037 |            0 |         20.118 |       0.051 |
| onnx/models/ResNet101_vaiq                       |       6.088 |         4.439 |            0 |         21.443 |       0.05  |
| onnx/models/ResNet152_vaiq                       |       6.773 |         5.716 |            0 |         26.699 |       0.061 |
| onnx/models/ResNet18_vaiq                        |       5.883 |         1.694 |            0 |          8.834 |       0.122 |
| onnx/models/resnet32ts.ra2_in1k_vaiq             |       5.095 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k_vaiq             |       6.396 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34_vaiq                        |       5.969 |         2.543 |            0 |         11.383 |       0.061 |
| onnx/models/resnet50.a1_in1k_vaiq                |       6.407 |         2.907 |            0 |         16.327 |       0.05  |
| onnx/models/ResNet50_vaiq                        |       5.504 |         2.887 |            0 |         15.859 |       0.062 |
| onnx/models/RRDB_ESRGAN_pro_vaiq                 |       6.651 |         0     |            0 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_vaiq                     |      26.168 |         5.413 |            0 |         60.581 |       0.127 |
| onnx/models/SqueezeNet_1_0_vaiq                  |       6.292 |         0.806 |            0 |          9.733 |       0.049 |
| onnx/models/SqueezeNet_1_1_vaiq                  |       4.97  |         0.781 |            0 |          9.854 |       0.048 |
| onnx/models/VGG11_bn_vaiq                        |       8.012 |        12.496 |            0 |          9.698 |       0.051 |
| onnx/models/VGG11_vaiq                           |       8.027 |        11.81  |            0 |         13.702 |       0.053 |
| onnx/models/VGG13_bn_vaiq                        |       8.313 |        13.008 |            0 |         11.421 |       0.06  |
| onnx/models/VGG13_vaiq                           |       9.226 |        13.637 |            0 |         11.675 |       0.052 |
| onnx/models/VGG16_bn_vaiq                        |       8.636 |        13.727 |            0 |         11.507 |       0.054 |
| onnx/models/VGG16_vaiq                           |       8.654 |        14.002 |            0 |         12.124 |       0.058 |
| onnx/models/VGG19_bn_vaiq                        |       8.495 |        13.991 |            0 |         13.843 |       0.242 |
| onnx/models/VGG19_vaiq                           |       7.86  |        14.59  |            0 |         12.469 |       0.059 |
| onnx/models/WideResNet_101_2_vaiq                |       6.971 |        10.589 |            0 |         25.325 |       0.058 |
| onnx/models/WideResNet_50_2_vaiq                 |       6.853 |         7.429 |            0 |         16.128 |       0.048 |
| onnx/models/YoloNetV3_vaiq                       |       6.535 |         6.476 |            0 |         22.636 |       0.059 |
| onnx/models/Yolov8m_vaiq                         |       7.063 |         3.708 |            0 |         31.115 |       0.047 |
| onnx/models/Yolov8n_vaiq                         |       5.808 |         1.282 |            0 |         20.838 |       0.053 |