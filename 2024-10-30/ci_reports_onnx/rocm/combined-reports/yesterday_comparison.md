# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.2892|112.9435|0.6543|0.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.7828|113.4602|1.6774|1.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|356.0015|351.8802|-4.1212|-1.16%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.039|71.6087|-0.4304|-0.6%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|277.3527|276.8911|-0.4616|-0.17%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.85|153.8485|-1.0015|-0.65%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|217.6421|216.7339|-0.9082|-0.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0816|7.0087|-0.073|-1.03%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|37.2575|35.3435|-1.914|-5.14%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.1269|5.1876|0.0607|1.18%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.0224|28.6807|0.6583|2.35%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.9486|50.8969|-2.0517|-3.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|67.4505|63.1614|-4.2891|-6.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|8.5955|7.8471|-0.7484|-8.71%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.6006|48.9968|-0.6038|-1.22%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.2435|17.9205|-0.323|-1.77%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.5711|129.7087|-0.8623|-0.66%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.7574|202.6386|-1.1188|-0.55%|

## No Regressions Found

## 9 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|hrnet_w18_small_v2_vaiq|compilation|Numerics|
|hrnet_w18_small_vaiq|compilation|Numerics|
|hrnet_w18_vaiq|compilation|Numerics|
|hrnet_w30_vaiq|compilation|Numerics|
|hrnet_w32_vaiq|compilation|PASS|
|hrnet_w40_vaiq|compilation|Numerics|
|hrnet_w44_vaiq|compilation|Numerics|
|hrnet_w48_vaiq|compilation|Numerics|
|hrnet_w64_vaiq|compilation|PASS|

