# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.1607|115.0111|1.8504|1.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.9774|113.5034|0.526|0.47%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|356.4718|354.8093|-1.6625|-0.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.8007|72.9425|0.1418|0.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|279.6242|279.8237|0.1995|0.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.6369|154.5853|-0.0516|-0.03%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.0877|216.9987|-0.089|-0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9692|7.0214|0.0522|0.75%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|35.1234|38.9099|3.7865|10.78%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2755|5.2808|0.0054|0.1%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|29.2105|27.4028|-1.8078|-6.19%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.6519|54.113|0.4612|0.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|63.3528|63.8898|0.537|0.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.0245|7.941|-0.0835|-1.04%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.3286|49.4701|0.1416|0.29%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0299|18.0782|0.0483|0.27%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.8305|137.1265|6.296|4.81%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.3191|203.2834|-0.0357|-0.02%|

## No Regressions Found

## No Progressions Found

