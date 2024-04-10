Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |      15.007 |        14.744 |        8.275 |          3.688 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       7.516 |         5.687 |        3.06  |          1.816 |       0     |
| pytorch/models/bert-large-uncased                |      22.49  |        20.337 |        9.605 |         13.785 |       0.853 |
| pytorch/models/bge-base-en-v1.5                  |       9.313 |         6.634 |        3.656 |          6.427 |       0.335 |
| pytorch/models/deit-small-distilled-patch16-224  |       4.164 |         1.324 |        0.559 |          0.647 |       0     |
| pytorch/models/dlrm                              |      18.463 |        24.958 |       27.02  |         19.225 |       0     |
| pytorch/models/gemma-7b                          |       3.135 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |     762.381 |        68.202 |       43.069 |         51.5   |       3.34  |
| pytorch/models/gpt2                              |      10.935 |         8.839 |        4.45  |          6.73  |       0.395 |
| pytorch/models/llama2-7b-GPTQ                    |    1789.3   |         0     |        0     |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     242.677 |       302.862 |      215.512 |          0     |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       6.588 |         2.831 |        1.258 |          4.229 |       0.157 |
| pytorch/models/mit-b0                            |       3.831 |         0.44  |        0.106 |          0.156 |       0     |
| pytorch/models/mobilebert-uncased                |       2.822 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-1.3b                          |      34.953 |        59.155 |       39.064 |         21.803 |       0     |
| pytorch/models/opt-125M                          |      10.992 |         9.098 |        4.566 |          2.297 |       0     |
| pytorch/models/opt-125m-gptq                     |       6.723 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      12.974 |        20.708 |        9.377 |          4.626 |       0     |
| pytorch/models/phi-1_5                           |      22.984 |         0     |        0     |          0     |       0     |
| pytorch/models/phi-2                             |      48.774 |         0     |        0     |          0     |       0     |
| pytorch/models/resnet50                          |       3.213 |         1.52  |        0.636 |          3.475 |       0.197 |
| pytorch/models/stablelm-3b-4e1t                  |      40.127 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-base                           |       2.188 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-large                          |       2.154 |         0     |        0     |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.597 |         4.344 |        2.217 |          1.439 |       0     |
| pytorch/models/whisper-base                      |       5.66  |         4.401 |        2.087 |          1.101 |       0     |
| pytorch/models/whisper-medium                    |      21.534 |        22.114 |       11.082 |          5.406 |       0     |
| pytorch/models/whisper-small                     |       9.089 |         9.264 |        4.582 |          2.306 |       0     |
