The merge report for time (in seconds) for runs: vai-hf-cnn-fp32, vai-int8-p0p1, shark-test-suite, vai-vision-int8
| tests                                            |   model-run |   onnx-import |   torch-mlir |   iree-compile |   inference |
|--------------------------------------------------|-------------|---------------|--------------|----------------|-------------|
| pytorch/models/beit-base-patch16-224-pt22k-ft22k |       3.662 |         0     |            0 |          0     |       0     |
| onnx/models/DarkNet53_vaiq                       |       2.913 |         1.274 |            0 |          6.912 |       0.026 |
