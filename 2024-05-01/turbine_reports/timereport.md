Time (in seconds) report for run: test-turbine using mode:turbine todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |      27.689 |             0 |            0 |         25.861 |       2.26  |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      18.86  |             0 |            0 |         10.218 |       1.209 |
| pytorch/models/bert-large-uncased                |      53.357 |             0 |            0 |         38.014 |       3.334 |
| pytorch/models/bge-base-en-v1.5                  |      72.936 |             0 |            0 |         12.677 |       1.569 |
| pytorch/models/deit-small-distilled-patch16-224  |      15.45  |             0 |            0 |          5.957 |       0.306 |
| pytorch/models/dlrm                              |       9.849 |             0 |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |     566.975 |             0 |            0 |        327.984 |       0     |
| pytorch/models/gpt2-xl                           |     154.558 |             0 |            0 |         84.035 |       0     |
| pytorch/models/gpt2                              |      23.101 |             0 |            0 |          7.755 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |     797.765 |             0 |            0 |         43.449 |       0     |
| pytorch/models/llama2-7b-hf                      |     421.359 |             0 |            0 |        258.846 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |      17.371 |             0 |            0 |          7.443 |       0.451 |
| pytorch/models/mit-b0                            |      13.555 |             0 |            0 |          7.908 |       0.379 |
| pytorch/models/mobilebert-uncased                |      33.773 |             0 |            0 |         20.428 |       0.329 |
| pytorch/models/opt-1.3b                          |      98.008 |             0 |            0 |         95.226 |      11.815 |
| pytorch/models/opt-125M                          |      22.815 |             0 |            0 |         13.719 |       1.26  |
| pytorch/models/opt-125m-gptq                     |      29.53  |             0 |            0 |         14.832 |       0.632 |
| pytorch/models/opt-350m                          |      44.992 |             0 |            0 |         31.863 |       1.584 |
| pytorch/models/phi-1_5                           |     105.498 |             0 |            0 |         99.681 |      19.168 |
| pytorch/models/phi-2                             |     192.067 |             0 |            0 |        173.872 |      41.856 |
| pytorch/models/resnet50                          |      13.586 |             0 |            0 |          7.918 |       0.368 |
| pytorch/models/stablelm-3b-4e1t                  |     262.746 |             0 |            0 |        199.417 |      39.716 |
| pytorch/models/t5-base                           |      35.987 |             0 |            0 |         29.634 |       3.356 |
| pytorch/models/t5-large                          |      74.288 |             0 |            0 |         72.165 |      10.768 |
| pytorch/models/vit-base-patch16-224              |      14.864 |             0 |            0 |          8.977 |       0.757 |
| pytorch/models/whisper-base                      |      12.098 |             0 |            0 |          7.015 |       0.532 |
| pytorch/models/whisper-medium                    |      44.866 |             0 |            0 |         37.485 |       2.951 |
| pytorch/models/whisper-small                     |      25.174 |             0 |            0 |         13.114 |       0.897 |
