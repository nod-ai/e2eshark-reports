Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |     342.553 |         0     |            0 |          0     |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      19.768 |         0     |            0 |          0     |       0     |
| pytorch/models/bert-large-uncased                |     702.742 |         0     |            0 |          0     |       0     |
| pytorch/models/bge-base-en-v1.5                  |     338.603 |         0     |            0 |          0     |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |      11.489 |         0     |            0 |          0     |       0     |
| pytorch/models/dlrm                              |      17.261 |         0     |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |       5.202 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |     461.858 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2                              |     120.819 |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-GPTQ                    |    3554.32  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     129.703 |         0     |            0 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       8.226 |         0     |            0 |          0     |       0     |
| pytorch/models/mit-b0                            |       5.703 |         0     |            0 |          0     |       0     |
| pytorch/models/mobilebert-uncased                |       6.225 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      33.636 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |      10.749 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      21.534 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |       7.633 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |      32.911 |         0     |            0 |          0     |       0     |
| pytorch/models/phi-2                             |      61.523 |         0     |            0 |          0     |       0     |
| pytorch/models/resnet50                          |       4.885 |         0     |            0 |          0     |       0     |
| pytorch/models/stablelm-3b-4e1t                  |       4.93  |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |       6.576 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-large                          |       8.227 |         0     |            0 |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.663 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-base                      |       6.898 |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-medium                    |      10.12  |         0     |            0 |          0     |       0     |
| pytorch/models/whisper-small                     |      11.369 |         0     |            0 |          0     |       0     |
| onnx/models/AlexNet_vaiq_int8                    |       6.132 |         5.43  |            0 |          4.678 |       0.203 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       4.687 |         2.919 |            0 |         11.673 |       0.559 |
| onnx/models/ConvNeXt_vaiq_int8                   |       6.802 |         8.679 |            0 |         13.207 |       0     |
| onnx/models/DarkNet53_vaiq_int8                  |       4.694 |         4.129 |            0 |          9.826 |       0.807 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       4.876 |         3.909 |            0 |         10.921 |       3.83  |
| onnx/models/DenseNet201_vaiq_int8                |       5.465 |         3.757 |            0 |         34.018 |       0.433 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       4.774 |         3.375 |            0 |         25.566 |       0.391 |
| onnx/models/FCN_vaiq_int8                        |       5.374 |         3.58  |            0 |          9.483 |       3.544 |
| onnx/models/GoogLeNet_vaiq_int8                  |       4.406 |         1.081 |            0 |         12.877 |       0.194 |
| onnx/models/Inception_v4_vaiq_int8               |       6.893 |         4.134 |            0 |         19.109 |      14.122 |
| onnx/models/KeypointRCNN_vaiq_int8               |      11.428 |         7.452 |            0 |          1.59  |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       4.588 |         1.087 |            0 |         13.614 |      11.22  |
| onnx/models/MNASNet_1_3_vaiq_int8                |       4.253 |         1.061 |            0 |          9.944 |       0.138 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       4.236 |         0.934 |            0 |         11.476 |       0.086 |
| onnx/models/QuantizedMLP                         |       4.081 |         0.392 |            0 |          0.816 |       0.064 |
| onnx/models/RAFT_vaiq_int8                       |       5.143 |         3.217 |            0 |         19.348 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      15.679 |         3.014 |            0 |         14.074 |     149.265 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      11.697 |         5.069 |            0 |         40.194 |     103.815 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       5.015 |         4.137 |            0 |         13.173 |       0.635 |
| onnx/models/ResNet152_vaiq_int8                  |       5.028 |         5.737 |            0 |         19.043 |       1.134 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       4.288 |         1.303 |            0 |          8.097 |       0.137 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       4.332 |         0.58  |            0 |          5.671 |       0.108 |
| onnx/models/U-2-Net_vaiq_int8                    |       4.863 |         4.808 |            0 |         16.638 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       6.396 |        10.624 |            0 |          7.552 |       1.046 |
| onnx/models/VGG19_vaiq_int8                      |       6.871 |        12.801 |            0 |          8.633 |       2.011 |
| onnx/models/VideoResNet_vaiq_int8                |       8.096 |         3.109 |            0 |          5.164 |      83.645 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       5.252 |         6.562 |            0 |         10.392 |       1.311 |
| onnx/models/YoloNetV3_vaiq_int8                  |       5.14  |         5.111 |            0 |         10.177 |      11.331 |
| onnx/models/opt-125M-awq                         |       5.455 |         7.154 |            0 |          7.669 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       7.204 |         0.801 |            0 |          5.053 |      27.232 |
| onnx/models/resnet50_vaiq_int8                   |       4.474 |         2.459 |            0 |          9.071 |       0.473 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       6.409 |         6.146 |            0 |          1.385 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       6.839 |         1.081 |            0 |          5.46  |      30.026 |
| onnx/models/yolov8n_vaiq_int8                    |       4.326 |         1.088 |            0 |         12.99  |       5.873 |