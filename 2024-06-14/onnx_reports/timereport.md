Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| onnx/models/AlexNet_vaiq_int8                    |       4.991 |         5.007 |            0 |          5.376 |       0.476 |
| onnx/models/CSP-DarkNet_vaiq_int8                |       3.43  |         2.36  |            0 |          9.206 |       0.591 |
| onnx/models/ConvNeXt_vaiq_int8                   |       5.162 |         7.15  |            0 |         19.668 |       0.938 |
| onnx/models/DarkNet53_vaiq_int8                  |       3.603 |         3.333 |            0 |          8.057 |       0.648 |
| onnx/models/DeepLabV3_resnet50_vaiq_int8         |       3.52  |         3.284 |            0 |          9.314 |       1.699 |
| onnx/models/DenseNet201_vaiq_int8                |       3.789 |         3.114 |            0 |         28.541 |       0.382 |
| onnx/models/EfficientNet_v2_s_vaiq_int8          |       3.46  |         2.756 |            0 |         18.821 |       0.387 |
| onnx/models/FCN_vaiq_int8                        |       3.758 |         2.921 |            0 |          8.003 |       0.804 |
| onnx/models/GoogLeNet_vaiq_int8                  |       3.012 |         0.874 |            0 |          9.176 |       0.213 |
| onnx/models/Inception_v4_vaiq_int8               |       5.339 |         3.521 |            0 |          1.456 |       0     |
| onnx/models/KeypointRCNN_vaiq_int8               |      10.044 |         5.982 |            0 |          1.971 |       0     |
| onnx/models/LRASPP_vaiq_int8                     |       2.946 |         0.824 |            0 |          9.599 |       9.997 |
| onnx/models/MNASNet_1_3_vaiq_int8                |       4.071 |         0.841 |            0 |          6.759 |       0.167 |
| onnx/models/MobileNetV3_small_vaiq_int8          |       3.27  |         0.824 |            0 |          8.195 |       0.154 |
| onnx/models/QuantizedMLP                         |       2.531 |         0.288 |            0 |          0.981 |       0.057 |
| onnx/models/RAFT_vaiq_int8                       |       3.475 |         2.496 |            0 |          6.185 |       0     |
| onnx/models/RDN_pytorch_vaiq_int8                |      15.888 |         2.433 |            0 |         15.31  |     103.917 |
| onnx/models/RRDB_ESRGAN_vaiq_int8                |      10.707 |         4.095 |            0 |         32.931 |      66.427 |
| onnx/models/RegNet_y_8gf_vaiq_int8               |       4.215 |         3.234 |            0 |         11.439 |       0.533 |
| onnx/models/ResNet152_vaiq_int8                  |       3.634 |         4.51  |            0 |         14.843 |       0.678 |
| onnx/models/ShuffleNet_v2_x2_0_vaiq_int8         |       3.062 |         1.013 |            0 |          5.578 |       0.165 |
| onnx/models/SqueezeNet_1_1_vaiq_int8             |       3.009 |         0.439 |            0 |          4.53  |       0.134 |
| onnx/models/U-2-Net_vaiq_int8                    |       3.442 |         3.664 |            0 |         17.386 |       1.723 |
| onnx/models/VGG11_bn_vaiq_int8                   |       5.053 |         7.638 |            0 |          8.985 |       0.759 |
| onnx/models/VGG19_vaiq_int8                      |       5.211 |         8.946 |            0 |         10.245 |       1.296 |
| onnx/models/VideoResNet_vaiq_int8                |      10.628 |         4.132 |            0 |          4.063 |      83.221 |
| onnx/models/WideResNet_50_2_vaiq_int8            |       4.185 |         4.712 |            0 |          9.633 |       0.844 |
| onnx/models/YoloNetV3_vaiq_int8                  |       3.423 |         3.671 |            0 |         11.474 |       7.336 |
| onnx/models/opt-125M-awq                         |       3.545 |         5.071 |            0 |          2.313 |       0     |
| onnx/models/pytorch-3dunet_vaiq_int8             |       5.362 |         0.634 |            0 |          3.919 |      26.859 |
| onnx/models/resnet50_vaiq_int8                   |       3.616 |         1.933 |            0 |          7.518 |       0.414 |
| onnx/models/retinanet_resnet50_fpn_vaiq_int8     |       4.916 |         4.623 |            0 |          1.8   |       0     |
| onnx/models/u-net_brain_mri_vaiq_int8            |       5.176 |         0.791 |            0 |          3.787 |       7.694 |
| onnx/models/yolov8n_vaiq_int8                    |       2.433 |         0.82  |            0 |          9.78  |       0.505 |
| pytorch/models/bart-large                        |      18.449 |        16.294 |            0 |          7.608 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      10.242 |         6.886 |            0 |          9.855 |       0.733 |
| pytorch/models/bert-large-uncased                |      26.945 |        21.546 |            0 |         10.8   |       0     |
| pytorch/models/bge-base-en-v1.5                  |      14.01  |         8.482 |            0 |          4.154 |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       6.338 |         1.844 |            0 |          5.523 |       0.277 |
| pytorch/models/dlrm                              |      21.552 |        29.93  |            0 |         17.899 |       0     |
| pytorch/models/gemma-7b                          |     316.494 |       544.066 |            0 |        541.668 |      99.744 |
| pytorch/models/gpt2-xl                           |      70.84  |        87.327 |            0 |         94.093 |      10.808 |
| pytorch/models/gpt2                              |      15.654 |        10.595 |            0 |         12.128 |       4.827 |
| pytorch/models/llama2-7b-GPTQ                    |    1255.9   |         0     |            0 |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     325.347 |       353.786 |            0 |        387.185 |      48.512 |
| pytorch/models/miniLM-L12-H384-uncased           |       9.651 |         3.276 |            0 |          1.52  |       0     |
| pytorch/models/mit-b0                            |       5.482 |         0.616 |            0 |          6.739 |       0.407 |
| pytorch/models/mobilebert-uncased                |       7.831 |         2.159 |            0 |         14.665 |       0.409 |
| pytorch/models/opt-1.3b                          |      46.278 |        66.504 |            0 |         43.397 |       0     |
| pytorch/models/opt-125M                          |      22.857 |        11.336 |            0 |          5.94  |       0     |
| pytorch/models/opt-125m-gptq                     |      23.266 |         0     |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      23.266 |        26.075 |            0 |         17.514 |       0     |
| pytorch/models/phi-1_5                           |      87.955 |        82.038 |            0 |         45.148 |       0     |
| pytorch/models/phi-2                             |     143.307 |       159.035 |            0 |         75.759 |       0     |
| pytorch/models/resnet50                          |       4.622 |         1.99  |            0 |          4.982 |       0.41  |
| pytorch/models/stablelm-3b-4e1t                  |     138.826 |       157.121 |            0 |         80.924 |       0     |
| pytorch/models/t5-base                           |      48.861 |        13.834 |            0 |         19.931 |      12.319 |
| pytorch/models/t5-large                          |      29.898 |        38.294 |            0 |         50.433 |      20.051 |
| pytorch/models/vit-base-patch16-224              |       8.195 |         5.286 |            0 |          8.319 |       0.624 |
| pytorch/models/whisper-base                      |       7.305 |         4.919 |            0 |          2.992 |       0     |
| pytorch/models/whisper-medium                    |      26.171 |        22.385 |            0 |         11.083 |       0     |
| pytorch/models/whisper-small                     |      12.741 |         9.602 |            0 |          5.756 |       0     |
