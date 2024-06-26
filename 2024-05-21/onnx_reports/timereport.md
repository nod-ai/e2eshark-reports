Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       3.82  |         3.956 |            0 |          5.141 |       0.467 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       2.962 |         2.148 |            0 |          8.996 |       0.386 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.908 |         6.101 |            0 |         17.565 |       0.929 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.351 |         2.944 |            0 |          8.135 |       0.449 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.403 |         2.909 |            0 |          1.418 |       0     |
| onnx/models/DenseNet201_vaiq_int8                |       4.005 |         2.845 |            0 |         29.109 |       0.317 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.864 |         2.605 |            0 |         17.014 |       0.322 |
| onnx/models/FCN_vaiq_int8                        |       3.2   |         2.591 |            0 |          1.187 |       0     |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.815 |         0.835 |            0 |          8.954 |       0.164 |
| onnx/models/Inception_v4_vaiq_int8               |       5.443 |         3.095 |            0 |          1.434 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      11.126 |         5.697 |            0 |          1.907 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.035 |         0.813 |            0 |          0.277 |       0     |
| onnx/models/MNASNet_1_3_vaiq_int8                |       2.759 |         0.816 |            0 |          6.61  |       0.16  |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.645 |         0.738 |            0 |          7.777 |       0.122 |
| onnx/models/QuantizedMLP                         |       2.277 |         0.26  |            0 |          0.924 |       0.067 |
| onnx/models/RAFT_vaiq_int8                       |       3.835 |         2.493 |            0 |          0.237 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.552 |         2.209 |            0 |         10.309 |      80.391 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      11.075 |         3.971 |            0 |          0.721 |       0     |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.218 |         3.086 |            0 |         10.991 |       1.069 |
| onnx/models/ResNet152_vaiq_int8                  |       3.573 |         4.418 |            0 |         14.373 |       0.522 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       2.78  |         1.034 |            0 |          0.392 |       0     |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.59  |         0.43  |            0 |          4.233 |       0.137 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.418 |         3.567 |            0 |          1.479 |       0     |
| onnx/models/VGG11_bn_vaiq_int8                   |       4.775 |         7.668 |            0 |          9.332 |       0.615 |
| onnx/models/VGG19_vaiq_int8                      |       4.879 |         8.579 |            0 |         10.334 |       0.725 |
| onnx/models/VideoResNet_vaiq_int8                |       6.498 |         2.357 |            0 |          1.173 |       0     |
| onnx/models/WideResNet_50_2_vaiq_int8            |       3.593 |         4.682 |            0 |          9.904 |       0.665 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.565 |         3.728 |            0 |          1.801 |       0     |
| onnx/models/opt-125M-awq                         |       3.634 |         5.339 |            0 |          2.481 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.169 |         0.638 |            0 |          0.326 |       0     |
| onnx/models/resnet50_vaiq_int8                   |       2.946 |         1.937 |            0 |          7.62  |       0.309 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       9.142 |         4.547 |            0 |          1.788 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.209 |         0.789 |            0 |          4.201 |       4.122 |
| onnx/models/yolov8n_vaiq_int8                    |       2.703 |         0.81  |            0 |          0.295 |       0     |
| pytorch/models/bart-large                        |      16.479 |        14.515 |            0 |          7.087 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       9.198 |         6.294 |            0 |          3.681 |       0     |
| pytorch/models/bert-large-uncased                |      28.384 |        20.673 |            0 |         25.057 |       1.602 |
| pytorch/models/bge-base-en-v1.5                  |      13.261 |         7.727 |            0 |         11.154 |       0.623 |
| pytorch/models/deit-small-distilled-patch16-224  |       5.583 |         1.658 |            0 |          1.258 |       0     |
| pytorch/models/dlrm                              |      21.671 |         7.111 |            0 |          0.096 |       0     |
| pytorch/models/gemma-7b                          |     304.63  |       113.689 |            0 |          0.121 |       0     |
| pytorch/models/gpt2-xl                           |      80.251 |        18.237 |            0 |          0.117 |       0     |
| pytorch/models/gpt2                              |      14.939 |         8.885 |            0 |         11.517 |       0.822 |
| pytorch/models/llama2-7b-GPTQ                    |    1060.4   |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     311.663 |        77.142 |            0 |          0.122 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       8.931 |         2.915 |            0 |          6.544 |       0.353 |
| pytorch/models/mit-b0                            |       4.628 |         0.575 |            0 |          0.304 |       0     |
| pytorch/models/mobilebert-uncased                |      12.028 |         1.978 |            0 |          0.941 |       0     |
| pytorch/models/opt-1.3b                          |      66.321 |        15.677 |            0 |          0.106 |       0     |
| pytorch/models/opt-125M                          |      14.566 |         8.659 |            0 |          4.758 |       0     |
| pytorch/models/opt-125m-gptq                     |      13.153 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      23.821 |        18.523 |            0 |          9.527 |       0     |
| pytorch/models/phi-1_5                           |      74.465 |        15.651 |            0 |          0.106 |       0     |
| pytorch/models/phi-2                             |     139.214 |        34.133 |            0 |          0.106 |       0     |
| pytorch/models/resnet50                          |       4.775 |         1.709 |            0 |          4.934 |       0.31  |
| pytorch/models/stablelm-3b-4e1t                  |     134.838 |        35.356 |            0 |          0.111 |       0     |
| pytorch/models/t5-base                           |      15.374 |        11.165 |            0 |          7.032 |       0     |
| pytorch/models/t5-large                          |      34.904 |         9.005 |            0 |          0.114 |       0     |
| pytorch/models/vit-base-patch16-224              |       7.92  |         4.565 |            0 |          2.951 |       0     |
| pytorch/models/whisper-base                      |       7.272 |         4.036 |            0 |          2.166 |       0     |
| pytorch/models/whisper-medium                    |      28.336 |        19.569 |            0 |         11.89  |       0     |
| pytorch/models/whisper-small                     |      12.217 |         8.763 |            0 |          5.15  |       0     |
