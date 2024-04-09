Time (in seconds) report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |      13.524 |        13.835 |        7.111 |          3.511 |       0     |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       7.488 |         5.276 |        2.826 |          1.434 |       0     |
| pytorch/models/bert-large-uncased                |      18.924 |        20.477 |        9.776 |          4.914 |       0     |
| pytorch/models/bge-base-en-v1.5                  |       8.769 |         6.649 |        3.638 |          1.926 |       0     |
| pytorch/models/deit-small-distilled-patch16-224  |       4.221 |         1.353 |        0.566 |          0.369 |       0     |
| pytorch/models/dlrm                              |      17.731 |        24.107 |       17.02  |          8.447 |       0     |
| pytorch/models/gemma-7b                          |       1.347 |         0     |        0     |          0     |       0     |
| pytorch/models/gpt2-xl                           |      61.784 |        69.623 |       49.707 |         25.471 |       0     |
| pytorch/models/gpt2                              |      10.891 |         9.019 |        4.42  |          2.295 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     490.753 |         0     |        0     |          0     |       0     |
| pytorch/models/llama2-7b-hf                      |     241.02  |       294.664 |      206.299 |        100.998 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |       6.076 |         2.767 |        1.255 |          0.823 |       0     |
| pytorch/models/mit-b0                            |       3.847 |         0.417 |        0.105 |          0.155 |       0     |
| pytorch/models/mobilebert-uncased                |       2.219 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-1.3b                          |      41.613 |        56.617 |       42.82  |         21.325 |       0     |
| pytorch/models/opt-125M                          |      10.5   |         8.994 |        4.525 |          2.278 |       0     |
| pytorch/models/opt-125m-gptq                     |      12.973 |         0     |        0     |          0     |       0     |
| pytorch/models/opt-350m                          |      18.198 |        19.803 |        9.173 |          4.547 |       0     |
| pytorch/models/phi-1_5                           |      23.812 |         0     |        0     |          0     |       0     |
| pytorch/models/phi-2                             |      41.916 |         0     |        0     |          0     |       0     |
| pytorch/models/resnet50                          |       3.107 |         1.433 |        0.62  |          3.819 |       0.201 |
| pytorch/models/stablelm-3b-4e1t                  |      40.941 |         0     |        0     |          0     |       0     |
| pytorch/models/t5-base                           |       2.15  |         0     |        0     |          0     |       0     |
| pytorch/models/t5-large                          |       2.137 |         0     |        0     |          0     |       0     |
| pytorch/models/vit-base-patch16-224              |       5.652 |         4.082 |        2.148 |          1.13  |       0     |
| pytorch/models/whisper-base                      |       5.505 |         4.116 |        2.012 |          1.075 |       0     |
| pytorch/models/whisper-medium                    |      18.156 |        20.233 |       10.557 |          5.233 |       0     |
| pytorch/models/whisper-small                     |      11.302 |         8.572 |        4.396 |          2.241 |       0     |
