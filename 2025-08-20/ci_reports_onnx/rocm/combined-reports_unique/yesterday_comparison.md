# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.6087|120.3082|3.6995|3.17%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.1995|114.4306|-2.7689|-2.36%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|526.6781|527.2236|0.5455|0.1%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|75.6185|73.2244|-2.3941|-3.17%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|70.0939|70.4313|0.3374|0.48%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|288.2818|288.627|0.3452|0.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.12|39.9016|0.7816|2.0%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0736|19.1858|0.1122|0.59%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.6181|3.4616|-0.1565|-4.32%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|20.4186|20.2734|-0.1452|-0.71%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2034|4.2001|-0.0033|-0.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1214|7.1112|-0.0102|-0.14%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|29.4636|27.7753|-1.6884|-5.73%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.767|14.7808|0.0138|0.09%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|46.9236|44.6766|-2.247|-4.79%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|111.0532|109.5645|-1.4887|-1.34%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.7288|19.4711|-1.2577|-6.07%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.5488|11.9461|2.3973|25.11%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.1188|14.3817|0.2629|1.86%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0764|3.1347|0.0583|1.89%|
|migraphx_torchvision__resnet50i1|PASS|regression|2.041|2.1671|0.1261|6.18%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7051|25.8107|0.1057|0.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.3548|37.016|-0.3388|-0.91%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.6147|55.8255|0.2108|0.38%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.7167|12.4877|-0.2289|-1.8%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7686|12.6855|-0.083|-0.65%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2408|19.2835|0.0427|0.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7422|12.9093|0.1671|1.31%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1367|19.3254|0.1887|0.99%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.525|19.5758|0.0508|0.26%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.7782|36.2382|0.46|1.29%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.3189|68.7142|-0.6047|-0.87%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.9513|109.3303|-0.621|-0.56%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4676|19.3743|-0.0933|-0.48%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1354|20.4598|0.3244|1.61%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.1502|23.3272|-0.8231|-3.41%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2076|20.3103|0.1027|0.51%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.1055|26.284|0.1785|0.68%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5758|32.4791|-0.0967|-0.3%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|gcvit_small|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_384.in22k_ft_in22k_in1k|Numerics|PASS|

