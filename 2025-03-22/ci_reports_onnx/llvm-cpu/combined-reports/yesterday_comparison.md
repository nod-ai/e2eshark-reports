# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|91.8498|103.1207|11.2709|12.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|103.8118|97.9988|-5.813|-5.6%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.0861|255.0958|-1.9903|-0.77%|
|migraphx_ORT__distilgpt2_1|PASS|regression|32.7725|35.2382|2.4657|7.52%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.5537|89.2036|3.65|4.27%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|260.5854|276.8322|16.2469|6.23%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|43.3885|55.6337|12.2451|28.22%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|1.344|1.3228|-0.0211|-1.57%|
|migraphx_bert__bert-large-uncased|PASS|progression|385.6681|365.8486|-19.8194|-5.14%|
|migraphx_cadene__dpn92i1|PASS|regression|219.3155|232.8185|13.503|6.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5418.9938|5461.8154|42.8217|0.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|326.0242|317.0761|-8.9481|-2.74%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5192.0728|5168.4443|-23.6285|-0.46%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|401.4459|403.3619|1.916|0.48%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|421.4613|427.5351|6.0739|1.44%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.3181|96.1585|0.8404|0.88%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.0664|37.1098|3.0434|8.93%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|189.3703|179.3901|-9.9801|-5.27%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|80.3825|88.7593|8.3768|10.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|43.2576|43.3751|0.1175|0.27%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1439.1858|1489.1035|49.9177|3.47%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.0967|198.8839|0.7872|0.4%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5706.3755|5714.434|8.0585|0.14%|
|migraphx_torchvision__resnet50i1|PASS|progression|94.6686|89.3722|-5.2965|-5.59%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5439.7977|5373.0589|-66.7388|-1.23%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1521.6218|1440.4001|-81.2216|-5.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2960.7283|2950.5524|-10.1758|-0.34%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4694.1204|4819.9858|125.8654|2.68%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|149.5207|176.7474|27.2267|18.21%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|297.3271|263.987|-33.3401|-11.21%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|361.8664|358.9411|-2.9253|-0.81%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.9282|236.7842|-3.144|-1.31%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|457.7505|468.1735|10.423|2.28%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|1118.8348|1051.4374|-67.3974|-6.02%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2856.1157|2820.4063|-35.7094|-1.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5866.7522|5893.2285|26.4763|0.45%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9060.007|9071.8985|11.8915|0.13%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|422.4337|750.0644|327.6307|77.56%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|819.3767|912.7116|93.3348|11.39%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1228.3063|1257.1991|28.8928|2.35%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|739.9245|751.2671|11.3426|1.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1517.9188|1543.819|25.9002|1.71%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2461.0138|2382.1325|-78.8814|-3.21%|

## No Regressions Found

## No Progressions Found

