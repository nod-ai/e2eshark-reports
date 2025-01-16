# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.5859|95.5894|-3.9965|-4.01%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|94.4151|91.4883|-2.9268|-3.1%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|289.0242|259.8924|-29.1318|-10.08%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.9903|39.6941|6.7038|20.32%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|82.7608|84.2836|1.5228|1.84%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|242.2416|275.2026|32.961|13.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|42.6612|45.113|2.4519|5.75%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.6518|375.2562|-6.3955|-1.68%|
|migraphx_cadene__dpn92i1|PASS|within tol|174.2721|165.7626|-8.5094|-4.88%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5283.6271|5375.3694|91.7423|1.74%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|346.5701|836.5982|490.0281|141.39%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5084.2861|5109.1225|24.8364|0.49%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|376.229|381.6421|5.4131|1.44%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|427.0422|483.8754|56.8333|13.31%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.5149|91.9057|-4.6093|-4.78%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.9823|37.154|5.1717|16.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.4075|184.1474|3.7399|2.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|82.365|81.9852|-0.3798|-0.46%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|52.5211|43.7669|-8.7541|-16.67%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1577.2036|1615.5658|38.3623|2.43%|
|migraphx_torchvision__inceptioni1|PASS|within tol|195.0211|196.2955|1.2744|0.65%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5423.6835|5393.9027|-29.7808|-0.55%|
|migraphx_torchvision__resnet50i1|PASS|within tol|96.6659|91.9535|-4.7124|-4.87%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5036.6752|5067.3728|30.6976|0.61%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2508.3561|2603.3288|94.9728|3.79%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4171.5284|4186.1143|14.5859|0.35%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5748.4966|5690.0809|-58.4156|-1.02%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|151.1181|162.085|10.9669|7.26%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|260.5098|274.2931|13.7833|5.29%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|381.3087|413.3384|32.0297|8.4%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|387.8872|405.7349|17.8478|4.6%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|660.4135|624.0296|-36.3839|-5.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|854.0566|889.4106|35.354|4.14%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5224.268|5085.0162|-139.2518|-2.67%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8060.1037|7844.2375|-215.8662|-2.68%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12034.9478|11263.192|-771.7558|-6.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|708.5993|703.7546|-4.8447|-0.68%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1151.9038|1086.4545|-65.4494|-5.68%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1622.0537|1562.7674|-59.2862|-3.66%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.2081|1292.1256|-11.0824|-0.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2061.5355|2091.2767|29.7412|1.44%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2908.0851|2886.3697|-21.7154|-0.75%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist|PASS|Numerics|

## No Progressions Found

