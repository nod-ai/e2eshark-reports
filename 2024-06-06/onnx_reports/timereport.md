Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       4.452 |         5.005 |            0 |          5.482 |       0.51  |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.218 |         2.397 |            0 |          9.144 |       0.606 |
| onnx/models/ConvNeXt_vaiq_int8                   |       4.824 |         6.921 |            0 |         19.613 |       0.989 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.367 |         3.299 |            0 |          8.014 |       0.661 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.339 |         3.385 |            0 |          9.211 |       1.739 |
| onnx/models/DenseNet201_vaiq_int8                |       3.744 |         3.152 |            0 |         28.402 |       0.35  |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.164 |         2.735 |            0 |         17.963 |       0.412 |
| onnx/models/FCN_vaiq_int8                        |       3.852 |         2.987 |            0 |          8.483 |       0.785 |
| onnx/models/GoogLeNet_vaiq_int8                  |       2.961 |         0.886 |            0 |          8.914 |       0.214 |
| onnx/models/Inception_v4_vaiq_int8               |       5.094 |         3.447 |            0 |          1.424 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.1   |         6.567 |            0 |          2.014 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       3.092 |         0.868 |            0 |          9.485 |      10.067 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       3.025 |         0.863 |            0 |          6.609 |       0.164 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       2.75  |         0.762 |            0 |          7.65  |       0.131 |
| onnx/models/QuantizedMLP                         |       2.374 |         0.265 |            0 |          0.917 |       0.069 |
| onnx/models/RAFT_vaiq_int8                       |       3.642 |         2.557 |            0 |         32.286 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      16.558 |         2.53  |            0 |         15.137 |     101.021 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.528 |         4.196 |            0 |         32.538 |      38.137 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       3.435 |         3.475 |            0 |         11.283 |       0.568 |
| onnx/models/ResNet152_vaiq_int8                  |       3.736 |         4.959 |            0 |         14.998 |       0.674 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       3.01  |         1.085 |            0 |          5.703 |       0.167 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       2.605 |         0.466 |            0 |          4.345 |       0.143 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.55  |         3.983 |            0 |         17.781 |       1.736 |
| onnx/models/VGG11_bn_vaiq_int8                   |       5.048 |         8.318 |            0 |          9.247 |       0.804 |
| onnx/models/VGG19_vaiq_int8                      |       4.919 |         9.515 |            0 |         10.402 |       1.089 |
| onnx/models/VideoResNet_vaiq_int8                |       6.959 |         2.542 |            0 |          4.106 |      83.402 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       4.152 |         5.547 |            0 |          9.867 |       0.859 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.742 |         4.07  |            0 |         11.492 |       7.238 |
| onnx/models/opt-125M-awq                         |       5.17  |         5.924 |            0 |          2.337 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.292 |         0.608 |            0 |          3.821 |      38.932 |
| onnx/models/resnet50_vaiq_int8                   |       3.377 |         2.224 |            0 |          7.87  |       0.417 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.85  |         5.131 |            0 |          1.667 |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.304 |         0.846 |            0 |          3.801 |       7.49  |
| onnx/models/yolov8n_vaiq_int8                    |       2.621 |         0.865 |            0 |          9.91  |       0.494 |
| pytorch/models/bart-large                        |      17.256 |        16.136 |            0 |          7.571 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       9.626 |         6.974 |            0 |         10.324 |       0.833 |
| pytorch/models/bert-large-uncased                |      29.595 |        22.38  |            0 |         25.532 |       8.492 |
| pytorch/models/bge-base-en-v1.5                  |      13.628 |         8.14  |            0 |         11.254 |       7.638 |
| pytorch/models/deit-small-distilled-patch16-224  |       5.543 |         1.839 |            0 |          5.54  |       0.292 |
| pytorch/models/dlrm                              |      22.774 |        29.004 |            0 |         17.873 |       0     |
| pytorch/models/gemma-7b                          |       4.444 |         0     |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |      85.489 |        86.594 |            0 |         95.758 |      21.809 |
| pytorch/models/gpt2                              |      15.515 |        10.25  |            0 |         11.831 |       8.768 |
| pytorch/models/llama2-7b-GPTQ                    |    1136.79  |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     330.193 |       341.732 |            0 |        202.021 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       9.332 |         3.464 |            0 |          6.635 |       7.192 |
| pytorch/models/mit-b0                            |       5.131 |         0.596 |            0 |          6.959 |       0.433 |
| pytorch/models/mobilebert-uncased                |      11.959 |         2.269 |            0 |         14.352 |       0.272 |
| pytorch/models/opt-1.3b                          |      66.427 |        67.494 |            0 |         39.902 |       0     |
| pytorch/models/opt-125M                          |      11.941 |        10.197 |            0 |          4.793 |       0     |
| pytorch/models/opt-125m-gptq                     |      18.779 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      24.412 |        22.129 |            0 |         10.092 |       0     |
| pytorch/models/phi-1_5                           |      79.23  |        72.842 |            0 |         42.795 |       0     |
| pytorch/models/phi-2                             |     145.067 |       142.491 |            0 |         79.137 |       0     |
| pytorch/models/resnet50                          |       4.427 |         1.954 |            0 |          5.133 |       0.419 |
| pytorch/models/stablelm-3b-4e1t                  |       3.228 |         0     |            0 |          0     |       0     |
| pytorch/models/t5-base                           |      15.11  |        13.075 |            0 |         19.179 |      12.475 |
| pytorch/models/t5-large                          |      48.438 |        39.846 |            0 |         58.311 |      20.632 |
| pytorch/models/vit-base-patch16-224              |       8.674 |         5.528 |            0 |          8.672 |       0.651 |
| pytorch/models/whisper-base                      |       7.196 |         4.96  |            0 |          2.127 |       0     |
| pytorch/models/whisper-medium                    |      28.829 |        23.499 |            0 |         11.456 |       0     |
| pytorch/models/whisper-small                     |      12.348 |        10.275 |            0 |          4.571 |       0     |