# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|101.5737|99.8443|-1.7294|-1.7%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|100.7767|99.2178|-1.5589|-1.55%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|504.1239|500.5103|-3.6136|-0.72%|
|migraphx_ORT__distilgpt2_1|PASS|regression|54.3553|85.2172|30.8619|56.78%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.5604|61.4774|-2.083|-3.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|297.2543|291.0747|-6.1796|-2.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.5029|31.3408|-1.1621|-3.58%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2428|19.2747|0.0319|0.17%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4603|42.7938|0.3335|0.79%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.5145|148.616|-0.8985|-0.6%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.2418|116.1346|1.8928|1.66%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|370.4438|365.6439|-4.8|-1.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.4262|8.1549|0.7286|9.81%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|23.3803|148.619|125.2386|535.66%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|38.7598|33.731|-5.0288|-12.97%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.2511|147.6949|3.4438|2.39%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.0095|15.8195|-1.1901|-7.0%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|6.6798|5.2548|-1.425|-21.33%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|76.4726|75.2884|-1.1842|-1.55%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7281|39.7221|-0.006|-0.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.3248|98.9563|-1.3685|-1.36%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3505|11.3541|0.0036|0.03%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|194.1786|189.4188|-4.7598|-2.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.6808|35.5303|-1.1505|-3.14%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|60.3596|58.5936|-1.766|-2.93%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|175.0931|79.5476|-95.5455|-54.57%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0864|13.093|0.0065|0.05%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3598|13.2919|-0.0679|-0.51%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5635|19.4286|-0.135|-0.69%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6013|12.6576|0.0563|0.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2683|13.2071|-0.0612|-0.46%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9913|21.7385|-0.2529|-1.15%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|73.6232|71.0698|-2.5534|-3.47%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|387.3443|111.277|-276.0673|-71.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|165.926|157.359|-8.567|-5.16%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3756|14.2724|-0.1032|-0.72%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.3076|17.7996|-0.508|-2.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.5208|26.7864|-0.7345|-2.67%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9058|20.2909|-0.6148|-2.94%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|30.716|38.3851|7.6691|24.97%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|45.2159|43.6054|-1.6105|-3.56%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|regnety_640.seer|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_24_224.fb_distilled_in1k_vaiq|compilation|PASS|

