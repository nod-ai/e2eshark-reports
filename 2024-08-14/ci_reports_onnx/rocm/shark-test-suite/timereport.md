Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:rocm

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |       7.545 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.551 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |      11.687 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |       6.791 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       3.326 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |       7.414 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       2.216 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      31.018 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |       6.811 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     187.987 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     106.328 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       7.123 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       4.406 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       3.741 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      31.559 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |       7.287 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      18.297 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      15.354 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      31.309 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      55.023 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       2.728 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       2.531 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       3.819 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       4.77  |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       3.935 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       3.824 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |       4.636 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |       4.203 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       2.593 |         1.561 |            0 |          3.194 |       0.025 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.807 |         1.079 |            0 |          9.839 |       0.024 |
| onnx/models/ConvNeXt_vaiq_int8                   |       3.818 |         3.044 |            0 |         11.16  |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       2.786 |         1.344 |            0 |          8.42  |       0.025 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       2.97  |         1.408 |            0 |          8.546 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       3.759 |         1.943 |            0 |         30.794 |       0.024 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       2.906 |         1.516 |            0 |         20.8   |       0.024 |
| onnx/models/FCN_vaiq_int8                        |       2.828 |         1.407 |            0 |          8.164 |       0.025 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.59  |         0.464 |            0 |         12.965 |       0.025 |
| onnx/models/Inception_v4_vaiq_int8               |       6.938 |         1.76  |            0 |         17.426 |       0.026 |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.345 |         3.131 |            0 |          0.943 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.41  |         0.544 |            0 |         11.517 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.462 |         0.499 |            0 |          8.953 |       0.025 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.591 |         0.455 |            0 |         11.091 |       0.025 |
| onnx/models/QuantizedMLP                         |       1.956 |         0.203 |            0 |          0.656 |       0.025 |
| onnx/models/RAFT_vaiq_int8                       |       3.084 |         1.848 |            0 |         17.782 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.663 |         1.286 |            0 |         11.898 |       0.024 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      16.226 |         2.766 |            0 |         36.332 |       0.028 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.543 |         1.787 |            0 |         11.841 |       0.025 |
| onnx/models/ResNet152_vaiq_int8                  |       3.169 |         2.323 |            0 |         15.877 |       0.029 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.614 |         0.568 |            0 |          6.725 |       0.026 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.236 |         0.285 |            0 |          5.177 |       0.025 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.349 |         1.788 |            0 |         16.868 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       2.838 |         3.224 |            0 |          5.231 |       0.025 |
| onnx/models/VGG19_vaiq_int8                      |       2.949 |         3.571 |            0 |          6.036 |       0.025 |
| onnx/models/VideoResNet_vaiq_int8                |       5.321 |         1.054 |            0 |          4.398 |       0.025 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       2.96  |         1.989 |            0 |          8.343 |       0.025 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.332 |         1.672 |            0 |          8.588 |       0.025 |
| onnx/models/opt-125M-awq                         |       2.316 |         2.206 |            0 |          6.517 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       4.056 |         0.358 |            0 |          4.301 |       0.027 |
| onnx/models/resnet50_vaiq_int8                   |       2.701 |         1.067 |            0 |          7.611 |       0.026 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.931 |         2.501 |            0 |          0.867 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       4.798 |         0.433 |            0 |          4.577 |       0.025 |
| onnx/models/yolov8n_vaiq_int8                    |       2.328 |         0.484 |            0 |         11.442 |       0.025 |