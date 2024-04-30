Time (in seconds) report for run: test-turbine using mode:turbine todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |      25.587 |             0 |            0 |         18.108 |       1.13  |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      16.273 |             0 |            0 |          9.96  |       0.7   |
| pytorch/models/bert-large-uncased                |      40.326 |             0 |            0 |         24.922 |       2.239 |
| pytorch/models/bge-base-en-v1.5                  |      20.757 |             0 |            0 |         12.975 |       1.199 |
| pytorch/models/deit-small-distilled-patch16-224  |      11.811 |             0 |            0 |          5.848 |       0.298 |
| pytorch/models/dlrm                              |       9.756 |             0 |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |     182.65  |             0 |            0 |          0     |       0     |
| pytorch/models/gpt2-xl                           |     131.701 |             0 |            0 |         83.093 |       0     |
| pytorch/models/gpt2                              |      23.092 |             0 |            0 |          7.857 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |    1125.75  |             0 |            0 |         45.892 |       0     |
| pytorch/models/llama2-7b-hf                      |     418.257 |             0 |            0 |        235.302 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |      17.463 |             0 |            0 |          7.378 |       0.317 |
| pytorch/models/mit-b0                            |      14.586 |             0 |            0 |          7.767 |       0.385 |
| pytorch/models/mobilebert-uncased                |      14.372 |             0 |            0 |          0     |       0     |
| pytorch/models/opt-1.3b                          |      13.902 |             0 |            0 |          0     |       0     |
| pytorch/models/opt-125M                          |      12.454 |             0 |            0 |          0     |       0     |
| pytorch/models/opt-125m-gptq                     |      18.587 |             0 |            0 |          0     |       0     |
| pytorch/models/opt-350m                          |      18.603 |             0 |            0 |          0     |       0     |
| pytorch/models/phi-1_5                           |     104.53  |             0 |            0 |         97.585 |      14.904 |
| pytorch/models/phi-2                             |     192.819 |             0 |            0 |        170.119 |      39.519 |
| pytorch/models/resnet50                          |      11.551 |             0 |            0 |          7.693 |       0.319 |
| pytorch/models/stablelm-3b-4e1t                  |     183.682 |             0 |            0 |        196.625 |      39.486 |
| pytorch/models/t5-base                           |      32.287 |             0 |            0 |         20.64  |       2.601 |
| pytorch/models/t5-large                          |      73.297 |             0 |            0 |         66.771 |      11.23  |
| pytorch/models/vit-base-patch16-224              |      25.394 |             0 |            0 |          9.381 |       0.696 |
| pytorch/models/whisper-base                      |      19.515 |             0 |            0 |         14.531 |       0.969 |
| pytorch/models/whisper-medium                    |      61.433 |             0 |            0 |         37.297 |       4.124 |
| pytorch/models/whisper-small                     |      20.266 |             0 |            0 |         13.55  |       0.924 |
