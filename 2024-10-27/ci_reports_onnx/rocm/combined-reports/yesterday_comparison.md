# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.859|112.0626|0.2036|0.18%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.2654|112.1439|-0.1215|-0.11%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|357.8715|359.4231|1.5516|0.43%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|71.8539|71.6285|-0.2254|-0.31%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|277.0779|275.3159|-1.762|-0.64%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.2233|154.8439|0.6206|0.4%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.4475|217.9362|1.4887|0.69%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0431|7.0169|-0.0262|-0.37%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|41.4604|40.1988|-1.2616|-3.04%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.269|5.2181|-0.0509|-0.97%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.2833|28.2098|-0.0735|-0.26%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|51.3264|50.0801|-1.2463|-2.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|63.0772|63.0373|-0.0399|-0.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.0325|8.1439|0.1114|1.39%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.3517|49.5329|0.1812|0.37%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0108|18.2571|0.2462|1.37%|
|migraphx_torchvision__inceptioni32|PASS|within tol|129.7607|130.4569|0.6962|0.54%|
|migraphx_torchvision__resnet50i64|PASS|within tol|202.184|203.854|1.67|0.83%|

## No Regressions Found

## No Progressions Found

