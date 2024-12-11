# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|227.5444|85.5296|-142.0149|-62.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|98.161|83.7223|-14.4387|-14.71%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|290.8358|252.164|-38.6718|-13.3%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.218|32.4818|1.2637|4.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.2295|90.8356|6.6061|7.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.7424|264.5608|19.8183|8.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3337|39.5206|0.1869|0.48%|
|migraphx_bert__bert-large-uncased|PASS|within tol|378.1868|388.4222|10.2354|2.71%|
|migraphx_bert__bertsquad-12|PASS|within tol|85.8549|86.3987|0.5438|0.63%|
|migraphx_cadene__dpn92i1|PASS|progression|188.911|176.8261|-12.0849|-6.4%|
|migraphx_cadene__inceptionv4i16|PASS|progression|6198.4661|5694.3707|-504.0953|-8.13%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|333.9066|338.7006|4.794|1.44%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|387.2015|417.9246|30.7231|7.93%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|513.1036|1094.3903|581.2867|113.29%|
|migraphx_mlperf__resnet50_v1|PASS|progression|101.2473|90.6974|-10.5499|-10.42%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.2273|35.4059|3.1786|9.86%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|184.9955|245.8018|60.8063|32.87%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|96.8867|351.4709|254.5843|262.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.3625|42.1359|2.7734|7.05%|
|migraphx_torchvision__densenet121i32|PASS|regression|1375.1098|1482.5379|107.4281|7.81%|
|migraphx_torchvision__inceptioni1|PASS|regression|192.1643|204.4806|12.3163|6.41%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6112.0461|6169.1417|57.0956|0.93%|
|migraphx_torchvision__resnet50i1|PASS|within tol|96.3448|95.6871|-0.6578|-0.68%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5351.1651|5402.1001|50.935|0.95%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2565.2835|2641.7931|76.5096|2.98%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4086.0913|4129.7429|43.6516|1.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5724.1897|5915.2185|191.0288|3.34%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|160.011|166.1411|6.1301|3.83%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|264.3755|272.3764|8.0009|3.03%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|406.6593|380.9218|-25.7375|-6.33%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|428.4633|399.8579|-28.6053|-6.68%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|598.4349|621.3137|22.8788|3.82%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|812.715|819.1289|6.4139|0.79%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4976.4198|5128.2701|151.8503|3.05%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8165.1504|8155.7454|-9.405|-0.12%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11393.5426|12663.8393|1270.2966|11.15%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|709.7419|716.6984|6.9565|0.98%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1113.305|1186.952|73.647|6.62%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1508.9547|1544.1271|35.1725|2.33%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1331.4213|1749.6355|418.2142|31.41%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2084.3553|2070.4688|-13.8865|-0.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3000.7303|3107.452|106.7217|3.56%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_cadene__resnext101_64x4di16|compilation|PASS|

