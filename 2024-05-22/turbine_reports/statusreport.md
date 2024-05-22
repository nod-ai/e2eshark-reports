Status report for run: test-turbine using mode:turbine todtype:default backend:llvm-cpu

| tests                                            | model-run   | onnx-import   | torch-mlir   | iree-compile   | inference   |
|:-------------------------------------------------|:------------|:--------------|:-------------|:---------------|:------------|
| pytorch/models/bart-large                        | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/beit-base-patch16-224-pt22k-ft22k | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/bert-large-uncased                | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/bge-base-en-v1.5                  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/deit-small-distilled-patch16-224  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/dlrm                              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gemma-7b                          | passed      | notrun        | notrun       | failed         | notrun      |
| pytorch/models/gpt2-xl                           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/gpt2                              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/llama2-7b-GPTQ                    | passed      | notrun        | notrun       | failed         | notrun      |
| pytorch/models/llama2-7b-hf                      | passed      | notrun        | notrun       | failed         | notrun      |
| pytorch/models/miniLM-L12-H384-uncased           | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/mit-b0                            | passed      | notrun        | notrun       | passed         | mismatch    |
| pytorch/models/mobilebert-uncased                | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/opt-1.3b                          | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/opt-125M                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/opt-125m-gptq                     | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/opt-350m                          | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/phi-1_5                           | passed      | notrun        | notrun       | passed         | mismatch    |
| pytorch/models/phi-2                             | passed      | notrun        | notrun       | passed         | mismatch    |
| pytorch/models/resnet50                          | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/stablelm-3b-4e1t                  | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/t5-base                           | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/t5-large                          | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/vit-base-patch16-224              | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/whisper-base                      | failed      | notrun        | notrun       | notrun         | notrun      |
| pytorch/models/whisper-medium                    | passed      | notrun        | notrun       | passed         | passed      |
| pytorch/models/whisper-small                     | passed      | notrun        | notrun       | passed         | passed      |
