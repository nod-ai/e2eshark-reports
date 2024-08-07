Status report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| onnx/models/AlexNet_vaiq_int8                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/CSP-DarkNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ConvNeXt_vaiq_int8                   | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/DarkNet53                            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/DarkNet53_vaiq                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/DarkNet53_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/DenseNet201_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_b0                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b0_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b1                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b1_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b2                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b2_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b3                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b3_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b4                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b4_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b5                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b5_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b6                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b6_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b7                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b7_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_l                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_l_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_m                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_m_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_s                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_s_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_s_vaiq_int8          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/FCN_vaiq_int8                        | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/GoogLeNet                            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/GoogLeNet_vaiq                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/GoogLeNet_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/Inception_v3                         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/Inception_v3_vaiq                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/Inception_v4_vaiq_int8               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/KeypointRCNN_vaiq_int8               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/LRASPP_vaiq_int8                     | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/MNASNet_1_3_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/MobileNetV2                          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV2_vaiq                     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV3_large                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV3_large_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV3_small                    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV3_small_vaiq               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/MobileNetV3_small_vaiq_int8          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/QuantizedMLP                         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/RAFT_vaiq_int8                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/RDN_pytorch_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RRDB_ESRGAN                          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/RRDB_ESRGAN_pro_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/RRDB_ESRGAN_vaiq                     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/RRDB_ESRGAN_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RegNet_y_8gf_vaiq_int8               | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet101                            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet101_vaiq                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet152                            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet152_vaiq                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet152_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/ResNet18                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet18_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet34                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet34_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet50                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet50_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/SqueezeNet_1_0                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/SqueezeNet_1_0_vaiq                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/SqueezeNet_1_1                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/SqueezeNet_1_1_vaiq                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/SqueezeNet_1_1_vaiq_int8             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/U-2-Net_vaiq_int8                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG11                                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG11_bn                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG11_bn_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG11_bn_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG11_vaiq                           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG13                                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG13_bn                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG13_bn_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG13_vaiq                           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG16                                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG16_bn                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG16_bn_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG16_vaiq                           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG19                                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG19_bn                             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG19_bn_vaiq                        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG19_vaiq                           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/VGG19_vaiq_int8                      | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VideoResNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/WideResNet_101_2                     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/WideResNet_101_2_vaiq                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/WideResNet_50_2                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/WideResNet_50_2_vaiq                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/WideResNet_50_2_vaiq_int8            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/YoloNetV3                            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/YoloNetV3_vaiq                       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/YoloNetV3_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/Yolov8m                              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/Yolov8m_vaiq                         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/Yolov8n                              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/Yolov8n_vaiq                         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/dla169                               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/dla169_vaiq                          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b0.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b0.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b1.ft_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b1.ft_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b2.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b2.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b3.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b3.ra2_in1k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b4.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b4.ra2_in1k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b5.sw_in12k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_b5.sw_in12k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_el.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_el.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_el_pruned.in1k          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/opt-125M-awq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/efficientnet_el_pruned.in1k_vaiq     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_em.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_em.ra2_in1k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_es.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_es.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_es_pruned.in1k          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_es_pruned.in1k_vaiq     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_lite0.ra_in1k           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_lite0.ra_in1k_vaiq      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_m.agc_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_m.agc_in1k_vaiq    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_s.ra2_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_s.ra2_in1k_vaiq    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_t.ra2_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_t.ra2_in1k_vaiq    | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/fbnetc_100.rmsp_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/fbnetc_100.rmsp_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_l.idstcv_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_l.idstcv_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_m.idstcv_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_m.idstcv_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_s.idstcv_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_s.idstcv_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/inception_v3.tf_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/inception_v3.tf_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/inception_v4.tf_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/inception_v4.tf_in1k_vaiq            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_050.ra2_in1k                   | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_050.ra2_in1k_vaiq              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_075.ra2_in1k                   | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_075.ra2_in1k_vaiq              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_100.ra2_in1k                   | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/lcnet_100.ra2_in1k_vaiq              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mnasnet_100.rmsp_in1k                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mnasnet_100.rmsp_in1k_vaiq           | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mnasnet_small.lamb_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mnasnet_small.lamb_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_050.lamb_in1k            | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_050.lamb_in1k_vaiq       | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_100.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_100.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_110d.ra_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_110d.ra_in1k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_120d.ra_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_120d.ra_in1k_vaiq        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_140.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv2_140.ra_in1k_vaiq         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_large_100.ra_in1k        | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_large_100.ra_in1k_vaiq   | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_050.lamb_in1k      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_050.lamb_in1k_vaiq | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_075.lamb_in1k      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_075.lamb_in1k_vaiq | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_100.lamb_in1k      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/mobilenetv3_small_100.lamb_in1k_vaiq | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/pytorch-3dunet_vaiq_int8             | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/resnet32ts.ra2_in1k                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet32ts.ra2_in1k_vaiq             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet33ts.ra2_in1k                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet33ts.ra2_in1k_vaiq             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet50.a1_in1k                     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet50.a1_in1k_vaiq                | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet50_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/u-net_brain_mri_vaiq_int8            | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/yolov3-original                      | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/yolov8n_vaiq_int8                    | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/bart-large                        | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/bert-large-uncased                | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/bge-base-en-v1.5                  | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/deit-small-distilled-patch16-224  | passed      | passed        | notrun       | passed         | passed      |
| pytorch/models/dlrm                              | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/gemma-7b                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gpt2-xl                           | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/gpt2                              | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/llama2-7b-GPTQ                    | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/llama2-7b-hf                      | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/miniLM-L12-H384-uncased           | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/mit-b0                            | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/mobilebert-uncased                | passed      | passed        | notrun       | passed         | passed      |
| pytorch/models/opt-1.3b                          | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/opt-125M                          | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/opt-125m-gptq                     | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/opt-350m                          | passed      | passed        | notrun       | failed         | notrun      |
| pytorch/models/phi-1_5                           | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/phi-2                             | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/resnet50                          | passed      | passed        | notrun       | passed         | passed      |
| pytorch/models/stablelm-3b-4e1t                  | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/t5-base                           | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/t5-large                          | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/vit-base-patch16-224              | passed      | passed        | notrun       | passed         | passed      |
| pytorch/models/whisper-base                      | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/whisper-medium                    | passed      | passed        | notrun       | passed         | mismatch    |
| pytorch/models/whisper-small                     | passed      | passed        | notrun       | passed         | mismatch    |
