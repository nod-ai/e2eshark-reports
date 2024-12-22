# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|100.4483|101.5737|1.1254|1.12%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.7823|100.7767|0.9944|1.0%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|500.8876|504.1239|3.2364|0.65%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|53.3095|54.3553|1.0458|1.96%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.1842|63.5604|2.3762|3.88%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|291.0455|297.2543|6.2088|2.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.1002|32.5029|1.4026|4.51%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2687|19.2428|-0.0259|-0.13%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4707|42.4603|-0.0104|-0.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.2117|149.5145|1.3028|0.88%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3096|114.2418|-0.0678|-0.06%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|363.9283|370.4438|6.5156|1.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2337|7.4262|0.1925|2.66%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.5361|23.3803|-1.1558|-4.71%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.7916|38.7598|5.9682|18.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.1247|144.2511|2.1264|1.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.0494|17.0095|1.9601|13.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.5342|6.6798|0.1456|2.23%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.6382|76.4726|0.8344|1.1%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7187|39.7281|0.0094|0.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.9534|100.3248|1.3713|1.39%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3525|11.3505|-0.0021|-0.02%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.171|194.1786|5.0076|2.65%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.4455|36.6808|1.2353|3.49%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.4963|60.3596|1.8634|3.19%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|79.4189|175.0931|95.6741|120.47%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0856|13.0864|0.0008|0.01%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.3677|13.3598|-0.0079|-0.06%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4233|19.5635|0.1402|0.72%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.661|12.6013|-0.0597|-0.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2127|13.2683|0.0557|0.42%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6896|21.9913|0.3018|1.39%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.9406|73.6232|2.6827|3.78%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|111.1536|387.3443|276.1906|248.48%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.5918|165.926|6.3342|3.97%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2283|14.3756|0.1473|1.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7541|18.3076|0.5535|3.12%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.7176|27.5208|0.8032|3.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.215|20.9058|0.6908|3.42%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.7788|30.716|0.9372|3.15%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.555|45.2159|1.6609|3.81%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|regnety_640.seer|Numerics|PASS|

