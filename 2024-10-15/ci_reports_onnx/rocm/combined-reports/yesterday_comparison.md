# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|430.9679|427.3585|-3.6094|-0.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|1582.7929|1580.1706|-2.6223|-0.17%|
|migraphx_bert__bertsquad-12|Numerics|within tol|838.5133|850.4026|11.8893|1.42%|
|migraphx_cadene__dpn92i1|PASS|within tol|54.0962|54.6672|0.571|1.06%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|1044.362|1061.6288|17.2668|1.65%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|77.1297|79.3287|2.199|2.85%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|1943.3004|1966.0569|22.7565|1.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|23.5779|23.1461|-0.4318|-1.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|56.6876|56.6557|-0.0319|-0.06%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|26.9542|27.1179|0.1638|0.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|651.0139|654.4208|3.4069|0.52%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.4605|8.3057|-0.1548|-1.83%|
|migraphx_torchvision__densenet121i32|PASS|within tol|366.7827|371.4345|4.6518|1.27%|
|migraphx_torchvision__inceptioni1|PASS|regression|45.1862|47.6316|2.4454|5.41%|
|migraphx_torchvision__inceptioni32|PASS|within tol|840.6133|849.5977|8.9844|1.07%|
|migraphx_torchvision__resnet50i1|PASS|within tol|25.3725|25.6351|0.2627|1.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|1650.8065|1665.2258|14.4193|0.87%|

## No Regressions Found

## No Progressions Found

