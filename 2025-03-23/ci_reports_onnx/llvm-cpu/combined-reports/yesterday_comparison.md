# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|103.1207|90.3704|-12.7503|-12.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|97.9988|90.3731|-7.6258|-7.78%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|255.0958|246.8032|-8.2926|-3.25%|
|migraphx_ORT__distilgpt2_1|PASS|progression|35.2382|30.0737|-5.1645|-14.66%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|89.2036|88.6104|-0.5933|-0.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|276.8322|246.9696|-29.8626|-10.79%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|55.6337|44.1765|-11.4571|-20.59%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.3228|1.0867|-0.2361|-17.85%|
|migraphx_bert__bert-large-uncased|PASS|within tol|365.8486|371.9073|6.0587|1.66%|
|migraphx_cadene__dpn92i1|PASS|progression|232.8185|215.0286|-17.7899|-7.64%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5461.8154|5451.7972|-10.0182|-0.18%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.0761|326.7146|9.6384|3.04%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5168.4443|5122.6877|-45.7566|-0.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|403.3619|412.4838|9.1219|2.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|427.5351|428.2825|0.7474|0.17%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.1585|98.7441|2.5855|2.69%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|37.1098|34.0056|-3.1042|-8.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.3901|181.0772|1.687|0.94%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|88.7593|82.4742|-6.285|-7.08%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|43.3751|42.158|-1.2171|-2.81%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1489.1035|1457.9532|-31.1503|-2.09%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.8839|201.2712|2.3873|1.2%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5714.434|5784.9673|70.5333|1.23%|
|migraphx_torchvision__resnet50i1|PASS|progression|89.3722|83.971|-5.4011|-6.04%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5373.0589|5428.677|55.6181|1.04%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1440.4001|1481.3294|40.9292|2.84%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|2950.5524|3027.0912|76.5388|2.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4819.9858|4809.2125|-10.7733|-0.22%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|176.7474|160.6021|-16.1453|-9.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.987|265.9334|1.9464|0.74%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|358.9411|379.1589|20.2178|5.63%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|236.7842|254.4818|17.6976|7.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|468.1735|467.3213|-0.8523|-0.18%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|1051.4374|781.5716|-269.8658|-25.67%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2820.4063|2920.3044|99.8981|3.54%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5893.2285|5826.0135|-67.215|-1.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9071.8985|9140.2754|68.3769|0.75%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|750.0644|403.1621|-346.9023|-46.25%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|912.7116|790.3964|-122.3152|-13.4%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1257.1991|1278.4855|21.2864|1.69%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|751.2671|736.7532|-14.5139|-1.93%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1543.819|1625.6742|81.8552|5.3%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2382.1325|2412.7321|30.5996|1.28%|

## No Regressions Found

## No Progressions Found

