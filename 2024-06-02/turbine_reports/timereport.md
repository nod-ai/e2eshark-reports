Time (in seconds) report for run: test-turbine using mode:turbine todtype:default backend:llvm-cpu

| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|:-------------------------------------------------|------------:|--------------:|-------------:|---------------:|------------:|
| pytorch/models/bart-large                        |      25.253 |             0 |            0 |         17.111 |       0.982 |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |      16.293 |             0 |            0 |          9.929 |       0.761 |
| pytorch/models/bert-large-uncased                |      42.121 |             0 |            0 |         24.224 |       1.646 |
| pytorch/models/bge-base-en-v1.5                  |      20.839 |             0 |            0 |         11.201 |       0.583 |
| pytorch/models/deit-small-distilled-patch16-224  |      11.973 |             0 |            0 |          5.916 |       0.293 |
| pytorch/models/dlrm                              |       1.369 |             0 |            0 |          0     |       0     |
| pytorch/models/gemma-7b                          |     501.819 |             0 |            0 |        251.262 |       0     |
| pytorch/models/gpt2-xl                           |     125.675 |             0 |            0 |         60.936 |       0     |
| pytorch/models/gpt2                              |      22.014 |             0 |            0 |          7.745 |       0     |
| pytorch/models/llama2-7b-GPTQ                    |    1079.14  |             0 |            0 |         30.631 |       0     |
| pytorch/models/llama2-7b-hf                      |     370.713 |             0 |            0 |        182.006 |       0     |
| pytorch/models/miniLM-L12-H384-uncased           |      16.851 |             0 |            0 |          7.284 |       0.315 |
| pytorch/models/mit-b0                            |      13.832 |             0 |            0 |          7.895 |       0.356 |
| pytorch/models/mobilebert-uncased                |      34.153 |             0 |            0 |         20.422 |       0.3   |
| pytorch/models/opt-1.3b                          |      95.281 |             0 |            0 |         67.518 |       5.638 |
| pytorch/models/opt-125M                          |      18.097 |             0 |            0 |         12.332 |       0.855 |
| pytorch/models/opt-125m-gptq                     |      31.459 |             0 |            0 |         14.535 |       0.658 |
| pytorch/models/opt-350m                          |      38.336 |             0 |            0 |         24.441 |       1.572 |
| pytorch/models/phi-1_5                           |     101.946 |             0 |            0 |         77.472 |      13.982 |
| pytorch/models/phi-2                             |     174.706 |             0 |            0 |        137.21  |      23.433 |
| pytorch/models/resnet50                          |      11.257 |             0 |            0 |          7.692 |       0.287 |
| pytorch/models/stablelm-3b-4e1t                  |     169.945 |             0 |            0 |        142.649 |      24.269 |
| pytorch/models/t5-base                           |      31.935 |             0 |            0 |         20.801 |       2.647 |
| pytorch/models/t5-large                          |      69.513 |             0 |            0 |         55.461 |       7.831 |
| pytorch/models/vit-base-patch16-224              |      14.626 |             0 |            0 |          8.615 |       0.646 |
| pytorch/models/whisper-base                      |      10.742 |             0 |            0 |          6.65  |       0.453 |
| pytorch/models/whisper-medium                    |      35.15  |             0 |            0 |         29.112 |       2.055 |
| pytorch/models/whisper-small                     |      18.599 |             0 |            0 |         13.578 |       0.933 |
