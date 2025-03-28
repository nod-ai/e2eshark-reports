# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|89.9793|99.2619|9.2826|10.32%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|90.6642|91.6356|0.9714|1.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|255.2931|500.6656|245.3725|96.11%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|33.3788|33.1475|-0.2313|-0.69%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|86.1499|85.976|-0.1738|-0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|254.159|256.3652|2.2062|0.87%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.9683|50.5913|9.6229|23.49%|
|migraphx_agentmodel__AgentModel|Numerics|regression|0.9992|1.3758|0.3767|37.7%|
|migraphx_bert__bert-large-uncased|PASS|within tol|375.7765|380.573|4.7965|1.28%|
|migraphx_cadene__dpn92i1|PASS|regression|164.2869|218.5388|54.2519|33.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5425.8134|5463.6723|37.8589|0.7%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|315.8763|344.6747|28.7984|9.12%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5041.3193|5040.4599|-0.8594|-0.02%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|398.1225|402.3573|4.2347|1.06%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|434.8397|607.1644|172.3248|39.63%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.9498|96.8228|-0.127|-0.13%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.7305|33.3719|-4.3585|-11.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.4482|179.4321|-0.0161|-0.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|70.6601|60.5832|-10.077|-14.26%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|24.1545|21.2275|-2.927|-12.12%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1495.6344|1494.9423|-0.6921|-0.05%|
|migraphx_torchvision__inceptioni1|PASS|regression|203.9353|223.626|19.6907|9.66%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5725.2768|5811.833|86.5562|1.51%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.1466|87.7851|1.6385|1.9%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5465.5841|5422.515|-43.069|-0.79%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1417.8893|1526.887|108.9977|7.69%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3216.6718|3085.799|-130.8728|-4.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4749.1306|4922.1448|173.0141|3.64%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|152.1147|216.7895|64.6749|42.52%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|252.0077|269.0802|17.0725|6.77%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.6653|378.753|6.0877|1.63%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|243.3304|284.726|41.3957|17.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|449.4961|429.4487|-20.0473|-4.46%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|663.0479|744.3882|81.3403|12.27%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|2929.0085|3113.4062|184.3977|6.3%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5786.6509|5789.9085|3.2576|0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9157.6528|9100.8867|-56.766|-0.62%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|408.4262|505.2134|96.7872|23.7%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|802.3531|833.0172|30.6641|3.82%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1900.2161|1249.911|-650.3051|-34.22%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|737.4732|740.7254|3.2522|0.44%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1518.2427|1584.9952|66.7524|4.4%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2634.8574|2561.7256|-73.1317|-2.78%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|PASS|Numerics|

## No Progressions Found

