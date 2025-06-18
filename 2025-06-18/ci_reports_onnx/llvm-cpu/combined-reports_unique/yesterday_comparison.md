# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.7773|379.549|8.7717|2.37%|
|migraphx_cadene__dpn92i1|PASS|regression|166.7303|179.425|12.6947|7.61%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5474.7407|5595.1088|120.3682|2.2%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|322.3078|319.7768|-2.531|-0.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|411.179|463.0647|51.8857|12.62%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|443.5247|561.4942|117.9695|26.6%|
|migraphx_mlperf__resnet50_v1|PASS|progression|103.398|87.5353|-15.8627|-15.34%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.1973|57.9348|-0.2625|-0.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.9794|210.3645|1.3851|0.66%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|62.7113|59.6379|-3.0734|-4.9%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|23.0309|18.2775|-4.7534|-20.64%|
|migraphx_torchvision__densenet121i32|PASS|progression|1688.5376|1582.2301|-106.3075|-6.3%|
|migraphx_torchvision__inceptioni1|PASS|within tol|192.6399|192.679|0.039|0.02%|
|migraphx_torchvision__resnet50i1|PASS|progression|102.1985|94.4901|-7.7084|-7.54%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1573.9636|1598.6971|24.7336|1.57%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5559.7321|5532.462|-27.2701|-0.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9572.6787|9522.4283|-50.2504|-0.52%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|165.9429|171.9146|5.9717|3.6%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|256.5312|250.6624|-5.8687|-2.29%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|361.4643|403.5284|42.0641|11.64%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|806.0487|239.8751|-566.1736|-70.24%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|426.4189|432.7201|6.3012|1.48%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|666.0216|654.7686|-11.253|-1.69%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5047.9132|5073.8794|25.9662|0.51%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13642.6287|13515.5477|-127.081|-0.93%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22993.374|23521.1308|527.7569|2.3%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|417.0313|414.9377|-2.0936|-0.5%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|866.8245|787.9016|-78.9229|-9.1%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1233.9262|1252.3264|18.4002|1.49%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|798.3228|750.2084|-48.1144|-6.03%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1658.2179|2266.5853|608.3673|36.69%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3374.6099|3388.0081|13.3982|0.4%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|PASS|Numerics|

## No Progressions Found

