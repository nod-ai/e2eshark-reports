Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       4.399 |         4.223 |            0 |          4.795 |       0.255 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.234 |         2.213 |            0 |          9.577 |       0.573 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.921 |         6.374 |            0 |         12.001 |       0     |
| onnx/models/DarkNet53                            |       2.354 |         0     |            0 |          0     |       0     |
| onnx/models/DarkNet53_vaiq                       |       2.291 |         0     |            0 |          0     |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       3.127 |         2.986 |            0 |          8.614 |       0.831 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.46  |         2.945 |            0 |          7.34  |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.792 |         2.943 |            0 |         28.332 |       0.458 |
| onnx/models/EfficientNet_b0                      |       2.544 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b0_vaiq                 |       2.179 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b1                      |       2.253 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b1_vaiq                 |       2.336 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2                      |       2.275 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b2_vaiq                 |       2.347 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3                      |       2.356 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b3_vaiq                 |       2.269 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4                      |       2.32  |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b4_vaiq                 |       2.237 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b5                      |       2.255 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b5_vaiq                 |       2.369 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b6                      |       2.192 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b6_vaiq                 |       2.263 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b7                      |       2.175 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_b7_vaiq                 |       3.125 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_l                    |       2.169 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_l_vaiq               |       2.319 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_m                    |       2.176 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_m_vaiq               |       2.152 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_s                    |       2.172 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_s_vaiq               |       2.239 |         0     |            0 |          0     |       0     |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.194 |         2.572 |            0 |         17.982 |       0.457 |
| onnx/models/FCN_vaiq_int8                        |       3.222 |         2.608 |            0 |          8.098 |       3.005 |
| onnx/models/GoogLeNet                            |       2.702 |         0     |            0 |          0     |       0     |
| onnx/models/GoogLeNet_vaiq                       |       2.226 |         0     |            0 |          0     |       0     |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.867 |         0.84  |            0 |         10.099 |       0.262 |
| onnx/models/Inception_v3                         |       2.197 |         0     |            0 |          0     |       0     |
| onnx/models/Inception_v3_vaiq                    |       2.291 |         0     |            0 |          0     |       0     |
| onnx/models/Inception_v4_vaiq_int8               |       6.007 |         3.045 |            0 |         16.698 |      13.643 |
| onnx/models/KeypointRCNN_vaiq_int8               |      11.17  |         6.348 |            0 |          1.958 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.217 |         1.489 |            0 |          9.879 |      10.202 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.905 |         0.818 |            0 |          7.087 |       0.194 |
| onnx/models/MobileNetV2                          |       2.407 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV2_vaiq                     |       2.287 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV3_large                    |       2.256 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV3_large_vaiq               |       4.614 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV3_small                    |       2.299 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV3_small_vaiq               |       2.222 |         0     |            0 |          0     |       0     |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.785 |         0.767 |            0 |          7.923 |       0.125 |
| onnx/models/QuantizedMLP                         |       2.19  |         0.253 |            0 |          0.904 |       0.066 |
| onnx/models/RAFT_vaiq_int8                       |       3.608 |         2.572 |            0 |          7.925 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.904 |         2.237 |            0 |         14.795 |     127.622 |
| onnx/models/RRDB_ESRGAN                          |       2.755 |         0     |            0 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_pro_vaiq                 |       2.259 |         0     |            0 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_vaiq                     |       2.307 |         0     |            0 |          0     |       0     |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |       9.93  |         3.886 |            0 |         37.432 |      89.833 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.671 |         3.002 |            0 |         11.029 |       0.649 |
| onnx/models/ResNet101                            |       2.194 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet101_vaiq                       |       2.286 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet152                            |       2.406 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet152_vaiq                       |       2.406 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet152_vaiq_int8                  |       3.53  |         4.174 |            0 |         17.304 |       1.114 |
| onnx/models/ResNet18                             |       2.384 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet18_vaiq                        |       2.426 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34                             |       2.366 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet34_vaiq                        |       2.257 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet50                             |       2.269 |         0     |            0 |          0     |       0     |
| onnx/models/ResNet50_vaiq                        |       2.51  |         0     |            0 |          0     |       0     |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.785 |         1.016 |            0 |          6.56  |       0.166 |
| onnx/models/SqueezeNet_1_0                       |       2.352 |         0     |            0 |          0     |       0     |
| onnx/models/SqueezeNet_1_0_vaiq                  |       2.262 |         0     |            0 |          0     |       0     |
| onnx/models/SqueezeNet_1_1                       |       2.223 |         0     |            0 |          0     |       0     |
| onnx/models/SqueezeNet_1_1_vaiq                  |       2.156 |         0     |            0 |          0     |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.842 |         0.489 |            0 |          4.513 |       0.141 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.608 |         3.381 |            0 |         15.065 |       0     |
| onnx/models/VGG11                                |       2.329 |         0     |            0 |          0     |       0     |
| onnx/models/VGG11_bn                             |       2.339 |         0     |            0 |          0     |       0     |
| onnx/models/VGG11_bn_vaiq                        |       2.258 |         0     |            0 |          0     |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.393 |         7.106 |            0 |          7.434 |       1.029 |
| onnx/models/VGG11_vaiq                           |       2.26  |         0     |            0 |          0     |       0     |
| onnx/models/VGG13                                |       2.388 |         0     |            0 |          0     |       0     |
| onnx/models/VGG13_bn                             |       2.446 |         0     |            0 |          0     |       0     |
| onnx/models/VGG13_bn_vaiq                        |       2.303 |         0     |            0 |          0     |       0     |
| onnx/models/VGG13_vaiq                           |       2.2   |         0     |            0 |          0     |       0     |
| onnx/models/VGG16                                |       2.396 |         0     |            0 |          0     |       0     |
| onnx/models/VGG16_bn                             |       2.383 |         0     |            0 |          0     |       0     |
| onnx/models/VGG16_bn_vaiq                        |       2.429 |         0     |            0 |          0     |       0     |
| onnx/models/VGG16_vaiq                           |       2.262 |         0     |            0 |          0     |       0     |
| onnx/models/VGG19                                |       2.199 |         0     |            0 |          0     |       0     |
| onnx/models/VGG19_bn                             |       2.343 |         0     |            0 |          0     |       0     |
| onnx/models/VGG19_bn_vaiq                        |       2.282 |         0     |            0 |          0     |       0     |
| onnx/models/VGG19_vaiq                           |       2.259 |         0     |            0 |          0     |       0     |
| onnx/models/VGG19_vaiq_int8                      |       4.493 |         8.286 |            0 |          8.853 |       1.949 |
| onnx/models/VideoResNet_vaiq_int8                |       6.799 |         2.25  |            0 |          4.64  |      73.163 |
| onnx/models/WideResNet_101_2                     |       2.599 |         0     |            0 |          0     |       0     |
| onnx/models/WideResNet_101_2_vaiq                |       2.476 |         0     |            0 |          0     |       0     |
| onnx/models/WideResNet_50_2                      |       2.232 |         0     |            0 |          0     |       0     |
| onnx/models/WideResNet_50_2_vaiq                 |       2.218 |         0     |            0 |          0     |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       3.674 |         4.582 |            0 |          8.965 |       1.268 |
| onnx/models/YoloNetV3                            |       2.401 |         0     |            0 |          0     |       0     |
| onnx/models/YoloNetV3_vaiq                       |       2.354 |         0     |            0 |          0     |       0     |
| onnx/models/YoloNetV3_vaiq_int8                  |       4.194 |         3.62  |            0 |          8.996 |      17.783 |
| onnx/models/Yolov8m                              |       2.662 |         0     |            0 |          0     |       0     |
| onnx/models/Yolov8m_vaiq                         |       2.355 |         0     |            0 |          0     |       0     |
| onnx/models/Yolov8n                              |       2.141 |         0     |            0 |          0     |       0     |
| onnx/models/Yolov8n_vaiq                         |       2.18  |         0     |            0 |          0     |       0     |
| onnx/models/dla169                               |       2.139 |         0     |            0 |          0     |       0     |
| onnx/models/dla169_vaiq                          |       2.433 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b0.ra_in1k              |       2.274 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b0.ra_in1k_vaiq         |       2.179 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b1.ft_in1k              |       2.182 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b1.ft_in1k_vaiq         |       2.175 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b2.ra_in1k              |       2.369 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b2.ra_in1k_vaiq         |       2.362 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b3.ra2_in1k             |       2.199 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq        |       2.167 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b4.ra2_in1k             |       2.317 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq        |       2.18  |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b5.sw_in12k             |       2.233 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_b5.sw_in12k_vaiq        |       2.333 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_el.ra_in1k              |       2.329 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_el.ra_in1k_vaiq         |       2.179 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_el_pruned.in1k          |       2.402 |         0     |            0 |          0     |       0     |
| onnx/models/opt-125M-awq                         |       3.66  |         4.938 |            0 |          5.755 |       0     |
| onnx/models/efficientnet_el_pruned.in1k_vaiq     |       2.206 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_em.ra2_in1k             |       2.435 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_em.ra2_in1k_vaiq        |       2.428 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es.ra_in1k              |       2.245 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es.ra_in1k_vaiq         |       2.283 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es_pruned.in1k          |       2.24  |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_es_pruned.in1k_vaiq     |       2.244 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_lite0.ra_in1k           |       3.034 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq      |       2.498 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_m.agc_in1k         |       3.408 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq    |       2.318 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k         |       2.385 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq    |       2.419 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k         |       2.321 |         0     |            0 |          0     |       0     |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq    |       2.237 |         0     |            0 |          0     |       0     |
| onnx/models/fbnetc_100.rmsp_in1k                 |       2.188 |         0     |            0 |          0     |       0     |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq            |       2.154 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_l.idstcv_in1k                 |       2.211 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_l.idstcv_in1k_vaiq            |       2.391 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_m.idstcv_in1k                 |       2.269 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_m.idstcv_in1k_vaiq            |       2.172 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_s.idstcv_in1k                 |       2.133 |         0     |            0 |          0     |       0     |
| onnx/models/gernet_s.idstcv_in1k_vaiq            |       2.326 |         0     |            0 |          0     |       0     |
| onnx/models/inception_v3.tf_in1k                 |       2.15  |         0     |            0 |          0     |       0     |
| onnx/models/inception_v3.tf_in1k_vaiq            |       2.153 |         0     |            0 |          0     |       0     |
| onnx/models/inception_v4.tf_in1k                 |       2.146 |         0     |            0 |          0     |       0     |
| onnx/models/inception_v4.tf_in1k_vaiq            |       2.393 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_050.ra2_in1k                   |       2.247 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_050.ra2_in1k_vaiq              |       2.134 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_075.ra2_in1k                   |       2.287 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_075.ra2_in1k_vaiq              |       2.314 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_100.ra2_in1k                   |       2.179 |         0     |            0 |          0     |       0     |
| onnx/models/lcnet_100.ra2_in1k_vaiq              |       2.268 |         0     |            0 |          0     |       0     |
| onnx/models/mnasnet_100.rmsp_in1k                |       2.2   |         0     |            0 |          0     |       0     |
| onnx/models/mnasnet_100.rmsp_in1k_vaiq           |       2.336 |         0     |            0 |          0     |       0     |
| onnx/models/mnasnet_small.lamb_in1k              |       2.368 |         0     |            0 |          0     |       0     |
| onnx/models/mnasnet_small.lamb_in1k_vaiq         |       2.371 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_050.lamb_in1k            |       2.406 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_050.lamb_in1k_vaiq       |       2.382 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_100.ra_in1k              |       2.313 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_100.ra_in1k_vaiq         |       2.381 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_110d.ra_in1k             |       2.259 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_110d.ra_in1k_vaiq        |       2.215 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_120d.ra_in1k             |       2.327 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_120d.ra_in1k_vaiq        |       2.293 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_140.ra_in1k              |       2.48  |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv2_140.ra_in1k_vaiq         |       2.306 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_large_100.ra_in1k        |       2.27  |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_large_100.ra_in1k_vaiq   |       2.335 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_050.lamb_in1k      |       2.441 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_050.lamb_in1k_vaiq |       2.193 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_075.lamb_in1k      |       2.2   |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_075.lamb_in1k_vaiq |       2.36  |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_100.lamb_in1k      |       2.423 |         0     |            0 |          0     |       0     |
| onnx/models/mobilenetv3_small_100.lamb_in1k_vaiq |       2.394 |         0     |            0 |          0     |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.586 |         0.605 |            0 |          4.479 |      25.755 |
| onnx/models/resnet32ts.ra2_in1k                  |       2.768 |         0     |            0 |          0     |       0     |
| onnx/models/resnet32ts.ra2_in1k_vaiq             |       2.366 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k                  |       2.463 |         0     |            0 |          0     |       0     |
| onnx/models/resnet33ts.ra2_in1k_vaiq             |       2.245 |         0     |            0 |          0     |       0     |
| onnx/models/resnet50.a1_in1k                     |       2.452 |         0     |            0 |          0     |       0     |
| onnx/models/resnet50.a1_in1k_vaiq                |       2.28  |         0     |            0 |          0     |       0     |
| onnx/models/resnet50_vaiq_int8                   |       3.1   |         1.823 |            0 |          7.521 |       0.459 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.827 |         4.427 |            0 |          1.703 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.676 |         0.809 |            0 |          4.497 |      77.811 |
| onnx/models/yolov3-original                      |       2.995 |         0     |            0 |          0     |       0     |
| onnx/models/yolov8n_vaiq_int8                    |       2.791 |         0.798 |            0 |         10.071 |       5.326 |
| pytorch/models/bart-large                        |      16.773 |        13.687 |            0 |          7.363 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      11.011 |         6.983 |            0 |          4.327 |       0     |
| pytorch/models/bert-large-uncased                |      26.157 |        19.876 |            0 |         10.424 |       0     |
| pytorch/models/bge-base-en-v1.5                  |      12.329 |         7.164 |            0 |          3.905 |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       5.027 |         1.595 |            0 |          5.518 |       0.49  |
| pytorch/models/dlrm                              |      20.683 |        25.794 |            0 |         15.04  |       0     |
| pytorch/models/gemma-7b                          |     174.531 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      67.539 |        76.791 |            0 |         64.736 |       0     |
| pytorch/models/gpt2                              |      14.334 |         9.905 |            0 |          4.63  |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     929.535 |        56.007 |            0 |         65.699 |      15.043 |
| pytorch/models/llama2-7b-hf                      |     297.39  |       324.984 |            0 |        372.299 |      47.963 |
| pytorch/models/miniLM-L12-H384-uncased           |       9.623 |         3.009 |            0 |          1.557 |       0     |
| pytorch/models/mit-b0                            |       4.35  |         0.58  |            0 |          6.797 |       0.402 |
| pytorch/models/mobilebert-uncased                |       6.897 |         2.016 |            0 |         14.125 |       0.396 |
| pytorch/models/opt-1.3b                          |      60.251 |        61.25  |            0 |         49.867 |       0     |
| pytorch/models/opt-125M                          |      11.331 |         9.125 |            0 |          5.259 |       0     |
| pytorch/models/opt-125m-gptq                     |      19.957 |         6.571 |            0 |          3.595 |       0     |
| pytorch/models/opt-350m                          |      12.752 |        20.339 |            0 |         10.105 |       0     |
| pytorch/models/phi-1_5                           |      58.132 |        67.596 |            0 |         81.211 |      14.703 |
| pytorch/models/phi-2                             |     125.413 |       133.186 |            0 |        157.506 |      25.866 |
| pytorch/models/resnet50                          |       4.565 |         1.788 |            0 |          4.902 |       0.424 |
| pytorch/models/stablelm-3b-4e1t                  |     120.705 |       126.377 |            0 |        150.642 |      24.572 |
| pytorch/models/t5-base                           |      13.641 |        11.822 |            0 |         18.793 |      17.959 |
| pytorch/models/t5-large                          |      28.512 |        34.347 |            0 |         50.22  |      38.89  |
| pytorch/models/vit-base-patch16-224              |       7.908 |         5.043 |            0 |          9.026 |       1.492 |
| pytorch/models/whisper-base                      |       6.372 |         4.634 |            0 |          6.796 |       8.125 |
| pytorch/models/whisper-medium                    |      25.014 |        21.55  |            0 |         26.928 |      21.693 |
| pytorch/models/whisper-small                     |      15.139 |         9.807 |            0 |         12.915 |      20.972 |