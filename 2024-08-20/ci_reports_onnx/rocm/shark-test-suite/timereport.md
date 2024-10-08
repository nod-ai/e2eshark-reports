Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       6.789 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.499 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      11.414 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.757 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.47  |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.35  |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.353 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      31.051 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       6.928 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     359.466 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |      79.466 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       5.804 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       3.431 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       3.517 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      29.45  |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       7.421 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      19.097 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      12.877 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      31.077 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      52.262 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       2.38  |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       2.517 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       3.836 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       4.771 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       3.731 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       3.971 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |       6.383 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       7.464 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       3.187 |         1.576 |            0 |          3.491 |       1.026 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.438 |         1.097 |            0 |         10.378 |       1.055 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.235 |         2.946 |            0 |         11.956 |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       3.029 |         1.384 |            0 |          8.254 |       1.123 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.169 |         1.374 |            0 |          7.834 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       4.032 |         1.735 |            0 |         28.841 |       1.315 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       2.951 |         1.534 |            0 |         22.187 |       1.105 |
| onnx/models/FCN_vaiq_int8                        |       2.888 |         1.208 |            0 |          7.858 |       1.06  |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.668 |         0.516 |            0 |         12.057 |       1.061 |
| onnx/models/Inception_v4_vaiq_int8               |       7.191 |         1.656 |            0 |         16.969 |       1.456 |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.106 |         2.91  |            0 |          0.889 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.555 |         0.565 |            0 |         11.242 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.527 |         0.465 |            0 |          9.266 |       1.003 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.359 |         0.45  |            0 |         11.011 |       1.072 |
| onnx/models/QuantizedMLP                         |       1.859 |         0.218 |            0 |          0.609 |       0.974 |
| onnx/models/RAFT_vaiq_int8                       |       3.135 |         1.871 |            0 |          6.417 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.626 |         1.546 |            0 |         13.111 |      62.162 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      15.529 |         2.986 |            0 |         31.887 |      45.095 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       2.77  |         1.578 |            0 |         11.409 |       1.107 |
| onnx/models/ResNet152_vaiq_int8                  |       3.134 |         2.273 |            0 |         15.603 |       1.138 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.765 |         0.554 |            0 |          6.301 |       1.094 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.625 |         0.319 |            0 |          4.732 |       1.002 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.161 |         1.77  |            0 |         17.609 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.951 |         3.073 |            0 |          4.673 |       1.082 |
| onnx/models/VGG19_vaiq_int8                      |       3.029 |         3.515 |            0 |          5.683 |       1.046 |
| onnx/models/VideoResNet_vaiq_int8                |       5.345 |         1.013 |            0 |          4.743 |       2.412 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.893 |         2.014 |            0 |          8.292 |       1.042 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.209 |         1.736 |            0 |          8.195 |       1.195 |
| onnx/models/pytorch-3dunet_vaiq_int8             |       3.958 |         0.376 |            0 |          4.28  |      12.764 |
| onnx/models/resnet50_vaiq_int8                   |       2.655 |         0.986 |            0 |          7.743 |       1.055 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       5.089 |         2.459 |            0 |          0.912 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.898 |         0.428 |            0 |          4.718 |      44.692 |
| onnx/models/yolov8n_vaiq_int8                    |       2.146 |         0.574 |            0 |         11.56  |       1.054 |
