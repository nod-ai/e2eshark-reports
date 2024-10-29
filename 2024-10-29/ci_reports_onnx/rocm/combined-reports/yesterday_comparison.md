# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.0626|112.2892|0.2266|0.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.1439|111.7828|-0.3611|-0.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|359.4231|356.0015|-3.4216|-0.95%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.6285|72.039|0.4105|0.57%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|275.3159|277.3527|2.0367|0.74%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.8439|154.85|0.0061|0.0%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.9362|217.6421|-0.2941|-0.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0169|7.0816|0.0648|0.92%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|40.1988|37.2575|-2.9413|-7.32%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2181|5.1269|-0.0912|-1.75%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.2098|28.0224|-0.1874|-0.66%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|50.0801|52.9486|2.8685|5.73%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|63.0373|67.4505|4.4132|7.0%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|8.1439|8.5955|0.4516|5.55%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.5329|49.6006|0.0677|0.14%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.2571|18.2435|-0.0136|-0.07%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.4569|130.5711|0.1142|0.09%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.854|203.7574|-0.0966|-0.05%|

## No Regressions Found

## No Progressions Found

