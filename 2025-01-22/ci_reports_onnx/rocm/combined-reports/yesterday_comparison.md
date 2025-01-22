# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.5441|105.6832|-0.8609|-0.81%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.0439|106.216|0.1721|0.16%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|471.1258|471.0653|-0.0605|-0.01%|
|migraphx_ORT__distilgpt2_1|PASS|regression|62.1848|257.572|195.3872|314.2%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.9281|67.2754|2.3473|3.62%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.7044|278.3222|5.6178|2.06%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.2797|32.9877|0.708|2.19%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.2781|20.4284|1.1503|5.97%|
|migraphx_cadene__dpn92i1|Numerics|regression|64.6403|69.9839|5.3436|8.27%|
|migraphx_cadene__inceptionv4i16|PASS|regression|149.1888|160.814|11.6252|7.79%|
|migraphx_cadene__resnext101_64x4di1|Numerics|regression|173.4822|188.0378|14.5557|8.39%|
|migraphx_cadene__resnext101_64x4di16|Numerics|regression|386.9976|414.3635|27.3659|7.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1178|7.3007|0.1829|2.57%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.7278|24.9468|0.2191|0.89%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|42.3853|44.5895|2.2042|5.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.5909|148.5629|3.9719|2.75%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.4928|14.9002|-1.5925|-9.66%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.3158|8.0389|1.7231|27.28%|
|migraphx_torchvision__densenet121i32|Numerics|regression|65.0722|68.8314|3.7592|5.78%|
|migraphx_torchvision__inceptioni1|PASS|regression|61.1318|66.4423|5.3104|8.69%|
|migraphx_torchvision__inceptioni32|PASS|regression|101.013|107.9048|6.8918|6.82%|
|migraphx_torchvision__resnet50i1|Numerics|regression|15.8742|17.0446|1.1704|7.37%|
|migraphx_torchvision__resnet50i64|Numerics|regression|145.5165|155.2292|9.7127|6.67%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.5947|33.1684|0.5737|1.76%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.9789|55.5816|0.6026|1.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.0297|74.6733|0.6436|0.87%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|11.9638|12.6311|0.6673|5.58%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.5397|13.2832|0.7435|5.93%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.5174|20.6758|1.1585|5.94%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.6854|13.5192|0.8337|6.57%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.2321|13.9891|0.757|5.72%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.1251|22.1784|1.0533|4.99%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.4258|68.3575|0.9317|1.38%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.7351|102.9122|1.1772|1.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.4086|151.7671|1.3586|0.9%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.3754|15.2263|0.8509|5.92%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.6697|16.6851|0.0154|0.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.1382|27.0227|0.8845|3.38%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|19.1542|21.933|2.7788|14.51%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.2435|27.5509|0.3074|1.13%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.6187|40.9558|0.3371|0.83%|

## No Regressions Found

## No Progressions Found

