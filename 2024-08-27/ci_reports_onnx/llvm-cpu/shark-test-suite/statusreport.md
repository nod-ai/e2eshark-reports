Status report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| pytorch/models/bart-large                        | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/bert-large-uncased                | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/bge-base-en-v1.5                  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/deit-small-distilled-patch16-224  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/dlrm                              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gemma-7b                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gpt2-xl                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gpt2                              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/llama2-7b-GPTQ                    | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/llama2-7b-hf                      | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/miniLM-L12-H384-uncased           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/mit-b0                            | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/mobilebert-uncased                | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-1.3b                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-125M                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-125m-gptq                     | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-350m                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/phi-1_5                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/phi-2                             | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/resnet50                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/stablelm-3b-4e1t                  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/t5-base                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/t5-large                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/vit-base-patch16-224              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/whisper-base                      | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/whisper-medium                    | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/whisper-small                     | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/AlexNet_vaiq_int8                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/CSP-DarkNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ConvNeXt_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DarkNet53_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DenseNet201_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_v2_s_vaiq_int8          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/FCN_vaiq_int8                        | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/GoogLeNet_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/Inception_v4_vaiq_int8               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/KeypointRCNN_vaiq_int8               | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/LRASPP_vaiq_int8                     | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/MNASNet_1_3_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV3_small_vaiq_int8          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/QuantizedMLP                         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/RAFT_vaiq_int8                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/RDN_pytorch_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RRDB_ESRGAN_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RegNet_y_8gf_vaiq_int8               | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet152_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/SqueezeNet_1_1_vaiq_int8             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/U-2-Net_vaiq_int8                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG11_bn_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG19_vaiq_int8                      | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VideoResNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/WideResNet_50_2_vaiq_int8            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/YoloNetV3_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/pytorch-3dunet_vaiq_int8             | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/resnet50_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/u-net_brain_mri_vaiq_int8            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/yolov8n_vaiq_int8                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/darknet53                            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DarkNet53                            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/dla169                               | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_b0                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b0.ra_in1k              | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b1                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b1.ft_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b2                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b2.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b3                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b3.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b4                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b4.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_b5                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b5.sw_in12k             | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b6                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b7                      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_el_pruned.in1k          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_el.ra_in1k              | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_em.ra2_in1k             | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnet_es_pruned.in1k          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/efficientnet_es.ra_in1k              | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/efficientnet_lite0.ra_in1k           | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_v2_l                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_v2_m                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnetv2_rw_m.agc_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_s.ra2_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/efficientnetv2_rw_t.ra2_in1k         | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/EfficientNet_v2_s                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/fbnetc_100.rmsp_in1k                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/gernet_l.idstcv_in1k                 | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/gernet_m.idstcv_in1k                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/gernet_s.idstcv_in1k                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/GoogLeNet                            | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/Inception_v3                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/inception_v3.tf_in1k                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/inception_v4.tf_in1k                 | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/lcnet_050.ra2_in1k                   | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/lcnet_075.ra2_in1k                   | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/lcnet_100.ra2_in1k                   | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mnasnet_100.rmsp_in1k                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/mnasnet_small.lamb_in1k              | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV2                          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mobilenetv2_050.lamb_in1k            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/mobilenetv2_100.ra_in1k              | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/mobilenetv2_110d.ra_in1k             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/mobilenetv2_120d.ra_in1k             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/mobilenetv2_140.ra_in1k              | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV3_large                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mobilenetv3_large_100.ra_in1k        | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV3_small                    | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mobilenetv3_small_050.lamb_in1k      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mobilenetv3_small_075.lamb_in1k      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/mobilenetv3_small_100.lamb_in1k      | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/opt-125M-awq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ResNet101                            | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ResNet152                            | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ResNet18                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/resnet32ts.ra2_in1k                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/resnet33ts.ra2_in1k                  | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/ResNet34                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/ResNet50                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/resnet50.a1_in1k                     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/RRDB_ESRGAN                          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/SqueezeNet_1_0                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/SqueezeNet_1_1                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG11                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG11_bn                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG13                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG13_bn                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG16                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG16_bn                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG19                                | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG19_bn                             | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/WideResNet_101_2                     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/WideResNet_50_2                      | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/YoloNetV3                            | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/yolov3-original                      | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/Yolov8m                              | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/Yolov8n                              | passed      | passed        | notrun       | failed         | notrun      |
