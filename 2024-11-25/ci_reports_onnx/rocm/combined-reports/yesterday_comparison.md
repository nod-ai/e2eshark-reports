# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.2077|112.4365|-2.7712|-2.41%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|113.9467|114.1116|0.1649|0.14%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|369.5639|374.3539|4.79|1.3%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|64.6469|64.9629|0.316|0.49%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.5031|72.6941|0.191|0.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.3616|274.5186|1.1569|0.42%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.2036|39.7536|0.55|1.4%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0833|20.0863|0.003|0.02%|
|migraphx_bert__bertsquad-12|PASS|regression|17.3004|19.1515|1.8511|10.7%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.5652|154.9507|-0.6145|-0.4%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|215.3143|214.9402|-0.3741|-0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.5629|7.546|-0.0169|-0.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|43.0461|40.1321|-2.9139|-6.77%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.7811|6.5144|-0.2668|-3.93%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.9267|32.4939|0.5672|1.78%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.761|54.1286|1.3676|2.59%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.9018|20.8713|-0.0306|-0.15%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.9249|14.0204|-0.9045|-6.06%|
|migraphx_torchvision__densenet121i32|PASS|within tol|52.7186|52.5444|-0.1741|-0.33%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.8452|15.9167|0.0716|0.45%|
|migraphx_torchvision__inceptioni32|PASS|within tol|144.1714|143.9934|-0.178|-0.12%|
|migraphx_torchvision__resnet50i64|PASS|within tol|190.7822|190.5342|-0.2479|-0.13%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.5461|33.4362|-0.1099|-0.33%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.966|57.6508|-0.3152|-0.54%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.5668|73.4186|-0.1482|-0.2%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5601|13.5226|-0.0375|-0.28%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8698|13.7683|-0.1014|-0.73%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.1016|20.0435|-0.0581|-0.29%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4166|13.5409|0.1244|0.93%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1263|13.9644|-0.1619|-1.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7805|21.7394|-0.0411|-0.19%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.3343|69.1521|-0.1822|-0.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.6799|104.615|-0.065|-0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.096|145.1162|0.0202|0.01%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1866|15.0439|-0.1427|-0.94%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.5464|17.6037|0.0573|0.33%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8922|26.5681|-0.3241|-1.21%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3256|19.9192|-0.4064|-2.0%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.106|27.9167|-0.1893|-0.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.4158|41.2982|-0.1176|-0.28%|

## No Regressions Found

## No Progressions Found

