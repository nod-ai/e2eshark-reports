# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.5296|88.4286|2.8991|3.39%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|83.7223|85.1996|1.4773|1.76%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|252.164|269.5154|17.3514|6.88%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|32.4818|33.6548|1.1731|3.61%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|90.8356|84.2758|-6.5598|-7.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|264.5608|246.0378|-18.523|-7.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.5206|50.4821|10.9615|27.74%|
|migraphx_bert__bert-large-uncased|PASS|regression|388.4222|558.4921|170.0698|43.78%|
|migraphx_bert__bertsquad-12|PASS|regression|86.3987|93.256|6.8573|7.94%|
|migraphx_cadene__dpn92i1|PASS|regression|176.8261|348.3757|171.5496|97.02%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5694.3707|5484.3058|-210.0649|-3.69%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|338.7006|573.7001|234.9995|69.38%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5272.6357|5176.4075|-96.2282|-1.83%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|417.9246|405.5385|-12.3861|-2.96%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|1094.3903|1738.8383|644.4479|58.89%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|90.6974|94.566|3.8686|4.27%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|35.4059|32.6606|-2.7453|-7.75%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|245.8018|181.5032|-64.2986|-26.16%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|351.4709|87.7138|-263.7572|-75.04%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|42.1359|47.8918|5.7559|13.66%|
|migraphx_torchvision__densenet121i32|PASS|regression|1482.5379|1557.4303|74.8924|5.05%|
|migraphx_torchvision__inceptioni1|PASS|regression|204.4806|295.9094|91.4289|44.71%|
|migraphx_torchvision__inceptioni32|PASS|progression|6169.1417|5435.8304|-733.3114|-11.89%|
|migraphx_torchvision__resnet50i1|PASS|progression|95.6871|85.7794|-9.9077|-10.35%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5402.1001|5282.459|-119.6411|-2.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2641.7931|2653.2991|11.5059|0.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4129.7429|4125.6326|-4.1103|-0.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|5915.2185|6253.6102|338.3917|5.72%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|166.1411|177.1756|11.0345|6.64%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|272.3764|288.6714|16.295|5.98%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|380.9218|393.4844|12.5625|3.3%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|399.8579|441.032|41.1741|10.3%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|621.3137|609.7101|-11.6036|-1.87%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|819.1289|813.7401|-5.3888|-0.66%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5128.2701|5090.4164|-37.8537|-0.74%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8155.7454|8847.92|692.1746|8.49%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12663.8393|11651.9534|-1011.8858|-7.99%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|716.6984|716.4383|-0.2602|-0.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1186.952|1209.4685|22.5164|1.9%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1544.1271|1644.0761|99.949|6.47%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1749.6355|1459.8133|-289.8223|-16.56%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2070.4688|2096.8997|26.4309|1.28%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3107.452|2966.6715|-140.7805|-4.53%|

## No Regressions Found

## No Progressions Found

