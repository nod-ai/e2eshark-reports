# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|88.4286|94.7967|6.3681|7.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|85.1996|89.961|4.7614|5.59%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|269.5154|278.1225|8.607|3.19%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.6548|31.1493|-2.5055|-7.44%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.2758|91.2386|6.9629|8.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|246.0378|270.0427|24.0049|9.76%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|50.4821|42.1865|-8.2956|-16.43%|
|migraphx_bert__bert-large-uncased|PASS|progression|558.4921|399.6764|-158.8157|-28.44%|
|migraphx_bert__bertsquad-12|PASS|within tol|93.256|89.5165|-3.7395|-4.01%|
|migraphx_cadene__dpn92i1|PASS|progression|348.3757|174.4636|-173.912|-49.92%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5484.3058|5765.4185|281.1127|5.13%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|573.7001|317.5065|-256.1937|-44.66%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5176.4075|5083.541|-92.8665|-1.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|405.5385|1467.3172|1061.7786|261.82%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1738.8383|464.6443|-1274.1939|-73.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.566|94.0177|-0.5483|-0.58%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.6606|35.9429|3.2823|10.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|181.5032|950.8281|769.3249|423.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|87.7138|83.0847|-4.6291|-5.28%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|47.8918|89.5228|41.631|86.93%|
|migraphx_torchvision__densenet121i32|PASS|regression|1557.4303|1652.0718|94.6415|6.08%|
|migraphx_torchvision__inceptioni1|PASS|progression|295.9094|213.6682|-82.2413|-27.79%|
|migraphx_torchvision__inceptioni32|PASS|regression|5435.8304|5878.121|442.2907|8.14%|
|migraphx_torchvision__resnet50i1|PASS|regression|85.7794|94.6007|8.8213|10.28%|
|migraphx_torchvision__resnet50i64|PASS|regression|5282.459|5966.7406|684.2815|12.95%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2653.2991|2692.6237|39.3246|1.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4125.6326|3942.4433|-183.1892|-4.44%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6253.6102|5809.3705|-444.2397|-7.1%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|177.1756|154.6039|-22.5717|-12.74%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|288.6714|270.1317|-18.5397|-6.42%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|393.4844|425.0584|31.5741|8.02%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|441.032|416.7535|-24.2785|-5.5%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|609.7101|591.0844|-18.6257|-3.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|813.7401|844.6552|30.9151|3.8%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5090.4164|5139.1905|48.7741|0.96%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8847.92|8146.081|-701.839|-7.93%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11651.9534|12336.882|684.9286|5.88%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|716.4383|705.6838|-10.7545|-1.5%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1209.4685|1081.7549|-127.7136|-10.56%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1644.0761|1498.9066|-145.1695|-8.83%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1459.8133|1303.4308|-156.3825|-10.71%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2096.8997|2107.7125|10.8128|0.52%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2966.6715|2859.5586|-107.1129|-3.61%|

## No Regressions Found

## No Progressions Found

