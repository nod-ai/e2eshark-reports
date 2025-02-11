# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.5321|108.1671|0.635|0.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.7339|106.1228|-1.6111|-1.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|475.3457|473.1523|-2.1934|-0.46%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.562|59.5305|-0.0315|-0.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.4043|62.401|-0.0033|-0.01%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.8256|267.9967|0.1711|0.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.0604|33.9343|-1.1261|-3.21%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0429|18.9882|-0.0547|-0.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1015|7.0112|-0.0902|-1.27%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.3315|26.157|-0.1745|-0.66%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.096|5.2533|0.1573|3.09%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|43.058|47.3851|4.3272|10.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.7836|45.5974|-1.1861|-2.54%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.9404|16.3375|-0.603|-3.56%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.9983|13.0466|6.0483|86.43%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9353|4.9256|-0.0098|-0.2%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.6435|32.1122|0.4687|1.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.3838|53.6435|0.2597|0.49%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|69.6597|71.3833|1.7236|2.47%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1295|12.1225|-0.007|-0.06%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6858|12.3474|-0.3384|-2.67%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.9745|51.2331|31.2587|156.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9861|12.8644|-0.1217|-0.94%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4427|13.3455|-0.0972|-0.72%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0451|20.7628|-0.2824|-1.34%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.8082|66.0914|0.2833|0.43%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.9507|99.8043|1.8536|1.89%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|138.3308|141.0938|2.763|2.0%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4002|14.416|0.0157|0.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4905|16.3736|-0.1169|-0.71%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|25.749|85.362|59.6129|231.52%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.8465|19.0823|0.2358|1.25%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5272|26.5195|-0.0076|-0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.4972|39.3453|-0.1519|-0.38%|

## No Regressions Found

## No Progressions Found

