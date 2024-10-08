Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       6.852 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.759 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      11.223 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.408 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.194 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.358 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.325 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      29.479 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       7.147 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     515.473 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     108.266 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       6.903 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       3.452 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       3.638 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      25.654 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       6.868 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      17.752 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      13.28  |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      30.887 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      56.511 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       2.567 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       2.421 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       4.11  |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       5.955 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       3.356 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       3.741 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |      11.684 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       7.634 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       2.802 |         1.614 |            0 |          3.479 |       0.988 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.749 |         1.075 |            0 |         10.709 |       1.067 |
| onnx/models/ConvNeXt_vaiq_int8                   |       3.798 |         2.949 |            0 |         11.889 |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       2.759 |         1.398 |            0 |          8.603 |       1.127 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.314 |         1.417 |            0 |          8.169 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.502 |         1.82  |            0 |         31.018 |       1.158 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.39  |         1.949 |            0 |         25.332 |       1.089 |
| onnx/models/FCN_vaiq_int8                        |       2.9   |         1.259 |            0 |         10.058 |       1.163 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.631 |         0.52  |            0 |         12.243 |       1.147 |
| onnx/models/Inception_v4_vaiq_int8               |       7.437 |         1.578 |            0 |         18.029 |       1.28  |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.794 |         3.038 |            0 |          1.204 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.684 |         0.509 |            0 |         11.038 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.594 |         0.474 |            0 |          8.911 |       1.021 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.877 |         0.438 |            0 |         12.701 |       1.032 |
| onnx/models/QuantizedMLP                         |       2.107 |         0.2   |            0 |          0.781 |       0.975 |
| onnx/models/RAFT_vaiq_int8                       |       3.274 |         1.869 |            0 |          6.86  |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.614 |         1.328 |            0 |         13.355 |      61.471 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      17.795 |         2.817 |            0 |         31.417 |      43.654 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       2.788 |         1.648 |            0 |         11.801 |       1.098 |
| onnx/models/ResNet152_vaiq_int8                  |       3.263 |         2.202 |            0 |         17.495 |       1.101 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.601 |         0.552 |            0 |          6.647 |       1.023 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.577 |         0.287 |            0 |          4.659 |       1.038 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.121 |         1.771 |            0 |         16.425 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       3.527 |         3.168 |            0 |          5.119 |       1.024 |
| onnx/models/VGG19_vaiq_int8                      |       3.462 |         3.628 |            0 |          5.915 |       1.063 |
| onnx/models/VideoResNet_vaiq_int8                |       5.438 |         1.021 |            0 |          4.484 |       2.759 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.871 |         1.942 |            0 |          9.863 |       1.048 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.56  |         1.81  |            0 |          8.798 |       8.488 |
| onnx/models/pytorch-3dunet_vaiq_int8             |       4.274 |         0.381 |            0 |          4.199 |      12.889 |
| onnx/models/resnet50_vaiq_int8                   |       2.78  |         0.943 |            0 |          8.507 |       1.035 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.962 |         2.534 |            0 |          1.045 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.873 |         0.428 |            0 |          4.844 |      46.973 |
| onnx/models/yolov8n_vaiq_int8                    |       3.021 |         0.516 |            0 |       2839.23  |       1.082 |
