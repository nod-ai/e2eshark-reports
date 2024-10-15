# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|431.7041|427.3585|-4.3456|-1.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|1591.7629|1580.1706|-11.5924|-0.73%|
|migraphx_bert__bertsquad-12|Numerics|within tol|855.6516|850.4026|-5.249|-0.61%|
|migraphx_cadene__dpn92i1|PASS|within tol|54.6044|54.6672|0.0628|0.12%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|1065.2446|1061.6288|-3.6157|-0.34%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|79.418|79.3287|-0.0892|-0.11%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|1963.0955|1966.0569|2.9613|0.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|24.6346|23.1461|-1.4884|-6.04%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|59.6791|56.6557|-3.0234|-5.07%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|27.0774|27.1179|0.0405|0.15%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|657.7467|654.4208|-3.3259|-0.51%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.4503|8.3057|-0.1447|-1.71%|
|migraphx_torchvision__densenet121i32|PASS|within tol|371.8225|371.4345|-0.388|-0.1%|
|migraphx_torchvision__inceptioni1|PASS|within tol|45.6972|47.6316|1.9344|4.23%|
|migraphx_torchvision__inceptioni32|PASS|within tol|849.5016|849.5977|0.0961|0.01%|
|migraphx_torchvision__resnet50i1|PASS|within tol|25.7074|25.6351|-0.0722|-0.28%|
|migraphx_torchvision__resnet50i64|PASS|within tol|1667.9086|1665.2258|-2.6827|-0.16%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|dla102x_vaiq|Numerics|PASS|

