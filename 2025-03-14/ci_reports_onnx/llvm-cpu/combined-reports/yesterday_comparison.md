# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.4696|88.2162|2.7466|3.21%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|104.1034|91.529|-12.5743|-12.08%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|282.4921|293.1888|10.6967|3.79%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.3726|35.5384|4.1659|13.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|86.0234|91.3804|5.357|6.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|527.9971|266.2616|-261.7356|-49.57%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.9723|39.3392|-1.6331|-3.99%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.5844|1.3315|-0.2528|-15.96%|
|migraphx_bert__bert-large-uncased|PASS|regression|370.672|612.1171|241.4452|65.14%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.8485|165.2197|0.3712|0.23%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5424.6079|5351.1721|-73.4358|-1.35%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|333.8852|330.8479|-3.0373|-0.91%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5123.6551|5823.8426|700.1875|13.67%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|418.982|403.9844|-14.9976|-3.58%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|426.7037|2654.0209|2227.3171|521.98%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.5784|94.5784|-2.0|-2.07%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|43.5713|33.2355|-10.3358|-23.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.2371|179.3621|-8.875|-4.71%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|76.7643|77.02|0.2557|0.33%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.4094|52.3365|11.9271|29.52%|
|migraphx_torchvision__densenet121i32|PASS|regression|1430.7475|1528.6794|97.9319|6.84%|
|migraphx_torchvision__inceptioni1|PASS|within tol|201.0084|198.4926|-2.5159|-1.25%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5775.4371|5865.2582|89.8212|1.56%|
|migraphx_torchvision__resnet50i1|PASS|within tol|87.424|83.9391|-3.4848|-3.99%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5470.0628|5397.8785|-72.1843|-1.32%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1470.5388|1479.9757|9.437|0.64%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|2966.226|3211.7308|245.5048|8.28%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|4733.2649|5009.5488|276.2839|5.84%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|154.3145|159.1022|4.7877|3.1%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|246.9219|413.4099|166.488|67.43%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|382.6073|367.714|-14.8933|-3.89%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|237.0282|233.9766|-3.0516|-1.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.8405|446.8601|16.0196|3.72%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|664.5306|761.6814|97.1508|14.62%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2799.8792|2799.5526|-0.3266|-0.01%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5911.7435|6041.9405|130.197|2.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9172.2163|9305.3367|133.1204|1.45%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|460.884|749.6109|288.727|62.65%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|816.0015|843.4654|27.4638|3.37%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1268.2272|1248.3481|-19.8791|-1.57%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|785.361|754.3527|-31.0084|-3.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1644.9365|1590.4561|-54.4805|-3.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2453.1144|2395.9678|-57.1466|-2.33%|

## No Regressions Found

## No Progressions Found

