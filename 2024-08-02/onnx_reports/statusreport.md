Status report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
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
| onnx/models/AlexNet_vaiq_int8                    | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/CSP-DarkNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ConvNeXt_vaiq_int8                   | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/DarkNet53_vaiq_int8                  | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/DenseNet201_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/EfficientNet_v2_s_vaiq_int8          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/FCN_vaiq_int8                        | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/GoogLeNet_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/Inception_v4_vaiq_int8               | passed      | passed        | notrun       | passed         | failed      |
| onnx/models/KeypointRCNN_vaiq_int8               | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/LRASPP_vaiq_int8                     | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/MNASNet_1_3_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/MobileNetV3_small_vaiq_int8          | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/QuantizedMLP                         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/RAFT_vaiq_int8                       | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/RDN_pytorch_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RRDB_ESRGAN_vaiq_int8                | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/RegNet_y_8gf_vaiq_int8               | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/ResNet152_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/SqueezeNet_1_1_vaiq_int8             | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/U-2-Net_vaiq_int8                    | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/VGG11_bn_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VGG19_vaiq_int8                      | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/VideoResNet_vaiq_int8                | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/WideResNet_50_2_vaiq_int8            | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/YoloNetV3_vaiq_int8                  | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/opt-125M-awq                         | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/pytorch-3dunet_vaiq_int8             | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/resnet50_vaiq_int8                   | passed      | passed        | notrun       | passed         | passed      |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     | passed      | passed        | notrun       | failed         | notrun      |
| onnx/models/u-net_brain_mri_vaiq_int8            | passed      | passed        | notrun       | passed         | mismatch    |
| onnx/models/yolov8n_vaiq_int8                    | passed      | passed        | notrun       | passed         | mismatch    |
