# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.3182|87.5911|2.2729|2.66%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.5802|86.6881|-1.8921|-2.14%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|250.0598|276.9994|26.9396|10.77%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.2067|30.4011|0.1944|0.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.6101|92.1112|7.5011|8.87%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|251.7044|242.3886|-9.3158|-3.7%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.5082|41.9818|2.4737|6.26%|
|migraphx_bert__bert-large-uncased|PASS|progression|423.9201|373.7697|-50.1505|-11.83%|
|migraphx_cadene__dpn92i1|PASS|within tol|178.0763|169.3403|-8.736|-4.91%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5288.5379|5346.4808|57.9429|1.1%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|321.8497|324.3817|2.5319|0.79%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5069.8826|5127.0395|57.157|1.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|377.3002|380.2964|2.9962|0.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|423.9021|417.8207|-6.0814|-1.43%|
|migraphx_mlperf__resnet50_v1|PASS|regression|89.0494|109.4143|20.3649|22.87%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.9346|32.345|1.4104|4.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|188.7748|179.5458|-9.229|-4.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.7873|78.1834|-1.604|-2.01%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|44.1247|46.203|2.0784|4.71%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1688.9828|1634.9357|-54.0471|-3.2%|
|migraphx_torchvision__inceptioni1|PASS|regression|195.5978|213.4192|17.8214|9.11%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5399.5417|5381.1677|-18.374|-0.34%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.49|84.7897|0.2997|0.35%|
|migraphx_torchvision__resnet50i64|PASS|regression|5116.9252|5452.8202|335.8951|6.56%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2627.3952|2643.3794|15.9842|0.61%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4150.1982|4121.6132|-28.5849|-0.69%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5806.5694|5770.3073|-36.262|-0.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.0514|162.6092|6.5578|4.2%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|984.1937|261.742|-722.4517|-73.41%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|511.0765|382.4774|-128.5992|-25.16%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|390.7477|392.0816|1.3339|0.34%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|610.433|612.1139|1.6808|0.28%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|809.0029|898.6521|89.6492|11.08%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5987.6983|5149.3818|-838.3166|-14.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8100.7172|8160.4954|59.7782|0.74%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11420.7039|11249.11|-171.5939|-1.5%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|737.2657|790.0152|52.7495|7.15%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1136.8332|1117.862|-18.9712|-1.67%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1523.4103|1538.9166|15.5063|1.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1298.3018|1361.7134|63.4115|4.88%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2115.6595|2039.7029|-75.9566|-3.59%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2898.2042|2923.1843|24.98|0.86%|

## No Regressions Found

## No Progressions Found

