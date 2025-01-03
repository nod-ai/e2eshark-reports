# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|100.2429|286.6985|186.4556|186.0%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|100.9217|120.635|19.7133|19.53%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.9425|501.2147|-1.7278|-0.34%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.9359|53.343|-0.5929|-1.1%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1359|63.2358|0.0998|0.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|295.857|295.9212|0.0643|0.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|42.0508|32.0776|-9.9732|-23.72%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.242|66.7325|47.4905|246.81%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4486|42.4586|0.01|0.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.2154|149.3747|0.1593|0.11%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.304|114.3798|0.0758|0.07%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|369.7934|370.0614|0.268|0.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3613|7.3855|0.0242|0.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.6684|25.21|0.5416|2.2%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|42.9369|35.43|-7.5069|-17.48%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|146.8451|143.5233|-3.3218|-2.26%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.4154|15.1853|-1.2301|-7.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.5927|7.4613|1.8686|33.41%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.2515|76.3776|0.1261|0.17%|
|migraphx_torchvision__inceptioni1|PASS|progression|64.5194|39.6866|-24.8328|-38.49%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.1874|100.2244|0.0371|0.04%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3689|11.3341|-0.0349|-0.31%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|196.1702|193.499|-2.6712|-1.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.5617|36.644|0.0823|0.23%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|101.2569|60.2837|-40.9732|-40.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|81.8437|82.044|0.2003|0.24%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.2451|13.0578|-0.1873|-1.41%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|21.5713|13.3042|-8.2672|-38.32%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4958|19.4978|0.0021|0.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6735|12.6432|-0.0303|-0.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2577|13.2924|0.0347|0.26%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|51.3753|21.9212|-29.4541|-57.33%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|72.2791|73.3561|1.0771|1.49%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|115.0567|115.13|0.0733|0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|164.9369|165.0034|0.0665|0.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5247|14.4397|-0.085|-0.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2729|18.2393|-0.0336|-0.18%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|27.4396|163.6106|136.171|496.26%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.848|20.7941|-0.0538|-0.26%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.4169|30.7148|0.2979|0.98%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.924|44.9143|-0.0097|-0.02%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|regnety_640.seer|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|

