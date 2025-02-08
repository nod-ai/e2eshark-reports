# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|105.0056|106.316|1.3103|1.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|104.2278|109.4414|5.2136|5.0%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|468.2113|494.456|26.2447|5.61%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.0048|56.9168|-2.0879|-3.54%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.5523|63.1907|-0.3616|-0.57%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|270.1149|270.4207|0.3058|0.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.0862|34.821|0.7348|2.16%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.5146|29.3548|9.8403|50.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0477|7.0711|0.0235|0.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|27.7707|29.6714|1.9008|6.84%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|4.9561|5.0215|0.0654|1.32%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.9138|44.0336|1.1198|2.61%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.9785|46.3206|0.3421|0.74%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.4309|17.3264|-0.1046|-0.6%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.6375|6.9327|-0.7048|-9.23%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.908|4.8366|-0.0714|-1.45%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.0729|32.8967|-0.1761|-0.53%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|55.2948|54.7576|-0.5372|-0.97%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.9197|71.9405|-1.9792|-2.68%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3517|12.1773|-0.1744|-1.41%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6668|12.5009|-0.1659|-1.31%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|20.5896|19.2083|-1.3813|-6.71%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6509|12.7896|0.1388|1.1%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|23.2665|13.1786|-10.0879|-43.36%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9022|21.1642|0.262|1.25%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.1962|67.5925|-0.6037|-0.89%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|102.8813|100.8018|-2.0794|-2.02%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|143.3095|145.5402|2.2307|1.56%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2329|14.4262|0.1933|1.36%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|17.0451|47.3305|30.2854|177.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.9708|26.0782|0.1074|0.41%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.34|19.4418|0.1018|0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|27.3233|47.1968|19.8735|72.73%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.5037|40.318|-0.1857|-0.46%|

## No Regressions Found

## No Progressions Found

