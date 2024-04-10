Status report for run: test-onnx using mode:onnx todtype:default backend:llvm-cpu

| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| pytorch/models/bart-large                        | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/bert-large-uncased                | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/bge-base-en-v1.5                  | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/deit-small-distilled-patch16-224  | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/dlrm                              | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/gemma-7b                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gpt2-xl                           | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/gpt2                              | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/llama2-7b-GPTQ                    | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/llama2-7b-hf                      | passed      | passed        | failed       | notrun         | notrun      |
| pytorch/models/miniLM-L12-H384-uncased           | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/mit-b0                            | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/mobilebert-uncased                | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-1.3b                          | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/opt-125M                          | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/opt-125m-gptq                     | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-350m                          | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/phi-1_5                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/phi-2                             | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/resnet50                          | passed      | passed        | passed       | passed         | passed      |
| pytorch/models/stablelm-3b-4e1t                  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/t5-base                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/t5-large                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/vit-base-patch16-224              | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/whisper-base                      | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/whisper-medium                    | passed      | passed        | passed       | failed         | notrun      |
| pytorch/models/whisper-small                     | passed      | passed        | passed       | failed         | notrun      |
