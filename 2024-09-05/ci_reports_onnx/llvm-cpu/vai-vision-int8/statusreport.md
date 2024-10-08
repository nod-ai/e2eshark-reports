Status report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                     | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| onnx/models/DarkNet53_vaiq                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_b0_vaiq          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b1_vaiq          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_b2_vaiq          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b3_vaiq          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b4_vaiq          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/efficientnet_b5.sw_in12k_vaiq | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b5_vaiq          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_b6_vaiq          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_b7_vaiq          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_v2_l_vaiq        | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_v2_m_vaiq        | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/EfficientNet_v2_s_vaiq        | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/GoogLeNet_vaiq                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/inception_v3.tf_in1k_vaiq     | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/Inception_v3_vaiq             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/inception_v4.tf_in1k_vaiq     | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV2_vaiq              | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV3_large_vaiq        | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/MobileNetV3_small_vaiq        | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/ResNet101_vaiq                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet152_vaiq                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet18_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet34_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/resnet50.a1_in1k_vaiq         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet50_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/RRDB_ESRGAN_pro_vaiq          | failed      | notrun        | notrun       | notrun         | notrun      |
| onnx/models/RRDB_ESRGAN_vaiq              | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/SqueezeNet_1_0_vaiq           | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/SqueezeNet_1_1_vaiq           | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/VGG11_bn_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG11_vaiq                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG13_bn_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG13_vaiq                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG16_bn_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG16_vaiq                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG19_bn_vaiq                 | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG19_vaiq                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/WideResNet_101_2_vaiq         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/WideResNet_50_2_vaiq          | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/YoloNetV3_vaiq                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/Yolov8m_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/Yolov8n_vaiq                  | passed      | passed        | notrun       | passed         | failed      |
