# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.8443|99.5957|-0.2486|-0.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.2178|99.3376|0.1198|0.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|500.5103|503.7741|3.2638|0.65%|
|migraphx_ORT__distilgpt2_1|PASS|progression|85.2172|53.8292|-31.388|-36.83%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.4774|61.5457|0.0683|0.11%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|291.0747|292.0837|1.009|0.35%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.3408|31.6744|0.3336|1.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2747|19.2836|0.0089|0.05%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.7938|42.4786|-0.3152|-0.74%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.616|148.2945|-0.3215|-0.22%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|116.1346|114.2682|-1.8664|-1.61%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|365.6439|363.6455|-1.9983|-0.55%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|8.1549|7.1891|-0.9658|-11.84%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|148.619|24.0763|-124.5427|-83.8%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|33.731|33.5085|-0.2226|-0.66%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|147.6949|142.5852|-5.1097|-3.46%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.8195|19.4321|3.6127|22.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.2548|6.8494|1.5946|30.35%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|75.2884|76.0998|0.8113|1.08%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7221|39.7121|-0.01|-0.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.9563|98.7626|-0.1937|-0.2%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3541|11.388|0.0339|0.3%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|189.4188|189.244|-0.1748|-0.09%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|35.5303|77.6146|42.0844|118.45%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|58.5936|88.5762|29.9826|51.17%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.5476|82.151|2.6035|3.27%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.093|13.061|-0.0319|-0.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2919|13.5644|0.2725|2.05%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.4286|20.515|1.0865|5.59%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6576|12.7175|0.06|0.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2071|13.2993|0.0922|0.7%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.7385|23.5061|1.7677|8.13%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|71.0698|1980.4001|1909.3302|2686.56%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|111.277|141.9861|30.7092|27.6%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|157.359|200.5577|43.1987|27.45%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2724|14.4664|0.1941|1.36%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.7996|17.6733|-0.1263|-0.71%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|26.7864|46.0615|19.2752|71.96%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2909|20.388|0.0971|0.48%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|38.3851|29.9311|-8.454|-22.02%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|43.6054|46.8497|3.2444|7.44%|

## No Regressions Found

## No Progressions Found

