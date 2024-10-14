# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|431.7041|430.9679|-0.7362|-0.17%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|1591.7629|1582.7929|-8.9701|-0.56%|
|migraphx_bert__bertsquad-12|Numerics|within tol|855.6516|838.5133|-17.1383|-2.0%|
|migraphx_cadene__dpn92i1|PASS|within tol|54.6044|54.0962|-0.5082|-0.93%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|1065.2446|1044.362|-20.8825|-1.96%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|79.418|77.1297|-2.2882|-2.88%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|1963.0955|1943.3004|-19.7952|-1.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|24.6346|23.5779|-1.0567|-4.29%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|59.6791|56.6876|-2.9915|-5.01%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|27.0774|26.9542|-0.1232|-0.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|657.7467|651.0139|-6.7329|-1.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.4503|8.4605|0.0102|0.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|371.8225|366.7827|-5.0398|-1.36%|
|migraphx_torchvision__inceptioni1|PASS|within tol|45.6972|45.1862|-0.511|-1.12%|
|migraphx_torchvision__inceptioni32|PASS|within tol|849.5016|840.6133|-8.8882|-1.05%|
|migraphx_torchvision__resnet50i1|PASS|within tol|25.7074|25.3725|-0.3349|-1.3%|
|migraphx_torchvision__resnet50i64|PASS|within tol|1667.9086|1650.8065|-17.1021|-1.03%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|dla102x_vaiq|Numerics|PASS|

