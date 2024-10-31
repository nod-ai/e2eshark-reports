# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.9435|113.4625|0.519|0.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.4602|114.3724|0.9122|0.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|351.8802|353.749|1.8687|0.53%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.6087|71.6128|0.0041|0.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|276.8911|277.6442|0.7532|0.27%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|153.8485|154.1062|0.2577|0.17%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.7339|216.4168|-0.3171|-0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0087|7.0424|0.0338|0.48%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|35.3435|35.5583|0.2148|0.61%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.1876|5.2147|0.0271|0.52%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.6807|29.7029|1.0222|3.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|50.8969|52.6481|1.7511|3.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|63.1614|66.7573|3.5959|5.69%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.8471|7.9921|0.145|1.85%|
|migraphx_torchvision__densenet121i32|PASS|within tol|48.9968|49.2693|0.2725|0.56%|
|migraphx_torchvision__inceptioni1|PASS|within tol|17.9205|17.9764|0.0559|0.31%|
|migraphx_torchvision__inceptioni32|PASS|within tol|129.7087|129.993|0.2842|0.22%|
|migraphx_torchvision__resnet50i64|PASS|within tol|202.6386|202.7832|0.1446|0.07%|

## No Regressions Found

## No Progressions Found

