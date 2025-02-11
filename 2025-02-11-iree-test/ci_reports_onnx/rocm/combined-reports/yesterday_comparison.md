# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.5321|106.7843|-0.7478|-0.7%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|107.7339|106.4814|-1.2526|-1.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|475.3457|474.7552|-0.5904|-0.12%|
|migraphx_ORT__distilgpt2_1|PASS|regression|59.562|64.0823|4.5203|7.59%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.4043|62.2162|-0.1881|-0.3%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.8256|268.1049|0.2793|0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.0604|34.3164|-0.744|-2.12%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0429|19.0286|-0.0143|-0.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1015|7.0745|-0.027|-0.38%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.3315|26.6232|0.2916|1.11%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.096|4.8284|-0.2676|-5.25%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.058|44.6565|1.5986|3.71%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|46.7836|50.1454|3.3619|7.19%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.9404|17.02|0.0795|0.47%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|6.9983|6.9806|-0.0177|-0.25%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9353|5.1695|0.2342|4.74%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|31.6435|32.0759|0.4325|1.37%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.3838|53.8277|0.444|0.83%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|69.6597|71.478|1.8182|2.61%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1295|12.0663|-0.0631|-0.52%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6858|12.3622|-0.3236|-2.55%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9745|19.3962|-0.5783|-2.89%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9861|12.9431|-0.043|-0.33%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4427|13.4892|0.0464|0.35%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0451|20.8349|-0.2103|-1.0%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|65.8082|66.3307|0.5225|0.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|97.9507|100.143|2.1923|2.24%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|138.3308|141.1546|2.8238|2.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4002|14.4166|0.0164|0.11%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.4905|16.458|-0.0325|-0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.749|25.6875|-0.0616|-0.24%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|18.8465|19.6251|0.7787|4.13%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5272|27.1297|0.6025|2.27%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.4972|39.2589|-0.2384|-0.6%|

## No Regressions Found

## No Progressions Found

