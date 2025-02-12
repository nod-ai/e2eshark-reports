# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|108.1671|105.9148|-2.2523|-2.08%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.1228|108.9753|2.8525|2.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|473.1523|477.9779|4.8256|1.02%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.5305|58.0129|-1.5177|-2.55%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.401|62.23|-0.171|-0.27%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|267.9967|267.6111|-0.3857|-0.14%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|33.9343|34.035|0.1007|0.3%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9882|19.1799|0.1917|1.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0112|7.118|0.1067|1.52%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.157|28.2151|2.0582|7.87%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.2533|4.8261|-0.4272|-8.13%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|47.3851|43.1625|-4.2226|-8.91%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.5974|46.4441|0.8467|1.86%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.3375|17.6177|1.2802|7.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|13.0466|8.6814|-4.3651|-33.46%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.9256|4.9114|-0.0142|-0.29%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.1122|31.7757|-0.3365|-1.05%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.6435|53.962|0.3185|0.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|71.3833|70.5189|-0.8644|-1.21%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1225|12.0231|-0.0994|-0.82%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3474|12.4442|0.0968|0.78%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|51.2331|19.2652|-31.968|-62.4%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8644|12.759|-0.1053|-0.82%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3455|13.3193|-0.0262|-0.2%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.7628|20.952|0.1892|0.91%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|66.0914|65.9259|-0.1655|-0.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.8043|98.4758|-1.3285|-1.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|141.0938|139.126|-1.9678|-1.39%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.416|14.6283|0.2123|1.47%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.3736|16.6852|0.3116|1.9%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|85.362|26.2952|-59.0668|-69.2%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0823|19.0296|-0.0527|-0.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.5195|26.3755|-0.1441|-0.54%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.3453|39.2896|-0.0557|-0.14%|

## No Regressions Found

## No Progressions Found

