# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.7525|104.0413|18.2888|21.33%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.721|90.4307|0.7096|0.79%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.1338|287.1335|26.9997|10.38%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.9025|32.7784|0.8759|2.75%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|84.1024|85.9389|1.8365|2.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|2283.2288|256.6285|-2026.6003|-88.76%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.3188|39.7574|0.4387|1.12%|
|migraphx_bert__bert-large-uncased|PASS|within tol|406.0754|391.3339|-14.7414|-3.63%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.3313|167.9905|-1.3408|-0.79%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5244.3095|5652.6927|408.3832|7.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|323.4675|322.5408|-0.9267|-0.29%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|5005.3084|5522.5773|517.2689|10.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|390.4895|409.9887|19.4993|4.99%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|414.9974|415.4827|0.4854|0.12%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.7692|89.8966|0.1275|0.14%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.631|35.1854|3.5544|11.24%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|180.1081|184.8164|4.7083|2.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.0902|80.5694|1.4792|1.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|48.0243|42.203|-5.8213|-12.12%|
|migraphx_torchvision__densenet121i32|PASS|regression|1553.0156|1645.3992|92.3836|5.95%|
|migraphx_torchvision__inceptioni1|PASS|within tol|195.1233|192.8063|-2.3171|-1.19%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5325.6552|5442.0661|116.4109|2.19%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.7679|85.261|-1.5069|-1.74%|
|migraphx_torchvision__resnet50i64|PASS|progression|5940.4804|5062.2684|-878.212|-14.78%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2541.7333|2573.2272|31.4939|1.24%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4009.5006|3969.8909|-39.6097|-0.99%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5720.4797|5807.2053|86.7256|1.52%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|155.6448|158.6942|3.0494|1.96%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|266.7615|265.0029|-1.7586|-0.66%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|372.324|398.2216|25.8976|6.96%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|389.3338|400.5521|11.2183|2.88%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|584.916|577.9264|-6.9896|-1.19%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|805.4045|805.5518|0.1473|0.02%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5039.3142|5290.025|250.7109|4.98%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8078.3551|8119.7931|41.4379|0.51%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11399.0615|12008.6554|609.5939|5.35%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|713.9392|752.1679|38.2287|5.35%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1068.7346|1149.7174|80.9828|7.58%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1530.3898|1643.7088|113.319|7.4%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1302.6312|1300.3191|-2.3121|-0.18%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2136.3976|2260.4758|124.0781|5.81%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2936.3184|2897.0935|-39.2249|-1.34%|

## No Regressions Found

## No Progressions Found

