# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|105.669|105.0056|-0.6634|-0.63%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.7257|104.2278|-3.4979|-3.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|471.6253|468.2113|-3.414|-0.72%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.4139|59.0048|-1.4091|-2.33%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.8198|63.5523|0.7324|1.17%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|268.9543|270.1149|1.1606|0.43%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.6087|34.0862|0.4775|1.42%|
|migraphx_bert__bert-large-uncased|PASS|progression|83.6869|19.5146|-64.1724|-76.68%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2645|7.0477|-0.2168|-2.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|52.4484|27.7707|-24.6777|-47.05%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.2478|4.9561|-0.2917|-5.56%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.5175|42.9138|0.3962|0.93%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.2091|45.9785|-0.2306|-0.5%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.0079|17.4309|0.4231|2.49%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.6775|7.6375|0.96|14.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9325|4.908|-0.0246|-0.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.4048|33.0729|0.6681|2.06%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.7525|55.2948|0.5423|0.99%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.178|73.9197|1.7417|2.41%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9332|12.3517|0.4185|3.51%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2396|12.6668|0.4272|3.49%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.0465|20.5896|1.5431|8.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6452|12.6509|0.0057|0.04%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.235|23.2665|10.0315|75.8%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9051|20.9022|-0.0029|-0.01%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.5209|68.1962|0.6752|1.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|100.9518|102.8813|1.9295|1.91%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|143.9472|143.3095|-0.6377|-0.44%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3027|14.2329|-0.0697|-0.49%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.944|17.0451|0.1012|0.6%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|69.0023|25.9708|-43.0315|-62.36%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.505|19.34|-0.165|-0.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.9964|27.3233|0.3269|1.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.4622|40.5037|0.0416|0.1%|

## No Regressions Found

## No Progressions Found

