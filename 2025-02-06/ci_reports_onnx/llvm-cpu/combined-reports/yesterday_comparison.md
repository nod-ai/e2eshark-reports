# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.904|86.8036|-0.1004|-0.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.3333|87.8805|1.5472|1.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|275.7825|250.8993|-24.8832|-9.02%|
|migraphx_ORT__distilgpt2_1|PASS|progression|35.8878|33.887|-2.0008|-5.58%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.0855|87.2207|2.1353|2.51%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|251.2094|247.3479|-3.8615|-1.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.6912|39.4011|-4.29|-9.82%|
|migraphx_bert__bert-large-uncased|PASS|regression|387.1571|585.6797|198.5226|51.28%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.0114|164.3337|-0.6776|-0.41%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5464.101|5561.6939|97.5929|1.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.2752|323.3107|4.0355|1.26%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5092.7284|6563.5889|1470.8605|28.88%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|416.9623|376.2011|-40.7613|-9.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|500.6059|418.0503|-82.5556|-16.49%|
|migraphx_mlperf__resnet50_v1|PASS|regression|97.9492|298.7395|200.7903|204.99%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.1189|31.8191|-5.2998|-14.28%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.0171|181.6256|-2.3914|-1.3%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|122.9011|80.2857|-42.6154|-34.67%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.1418|42.7906|-1.3512|-3.06%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1491.5596|1484.4645|-7.0952|-0.48%|
|migraphx_torchvision__inceptioni1|PASS|within tol|208.9262|198.7028|-10.2235|-4.89%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5768.4141|5780.9931|12.579|0.22%|
|migraphx_torchvision__resnet50i1|PASS|within tol|90.557|90.0486|-0.5084|-0.56%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5340.2176|5418.5957|78.3781|1.47%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|2581.728|2770.2508|188.5228|7.3%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4326.2975|4073.9992|-252.2983|-5.83%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5808.0554|6116.0607|308.0053|5.3%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|163.7189|168.3238|4.6049|2.81%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.9843|263.4612|1.4769|0.56%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|378.7901|370.2551|-8.535|-2.25%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|410.9864|428.8047|17.8183|4.34%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|639.4657|628.7612|-10.7045|-1.67%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|809.5715|848.7977|39.2261|4.85%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5679.5036|5890.1104|210.6068|3.71%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8795.6805|8107.9735|-687.7071|-7.82%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11924.8403|11330.6713|-594.169|-4.98%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|800.9497|1106.2204|305.2707|38.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1082.1753|1091.0488|8.8735|0.82%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1648.3646|1633.5281|-14.8365|-0.9%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1288.4553|3249.2373|1960.782|152.18%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2087.3922|2149.1125|61.7204|2.96%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|2891.427|3127.9037|236.4767|8.18%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|PASS|Numerics|

## No Progressions Found

