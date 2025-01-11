# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.9456|101.346|15.4004|17.92%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|97.0544|95.5034|-1.5509|-1.6%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|270.9263|290.4439|19.5176|7.2%|
|migraphx_ORT__distilgpt2_1|PASS|progression|59.2108|35.1049|-24.106|-40.71%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|89.4806|84.7752|-4.7055|-5.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|249.5805|249.3368|-0.2437|-0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.4033|39.3233|-1.0801|-2.67%|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.0775|387.8339|6.7564|1.77%|
|migraphx_cadene__dpn92i1|PASS|within tol|173.6667|171.3971|-2.2696|-1.31%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5387.7944|5298.7931|-89.0013|-1.65%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|329.2138|324.3148|-4.899|-1.49%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5113.4299|5154.7909|41.361|0.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|384.2948|380.4204|-3.8745|-1.01%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|414.8411|445.5365|30.6954|7.4%|
|migraphx_mlperf__resnet50_v1|PASS|progression|240.6212|91.4229|-149.1983|-62.01%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.9399|32.7553|0.8154|2.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.6602|183.9992|4.339|2.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|90.0542|82.4427|-7.6115|-8.45%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|38.6503|43.7445|5.0943|13.18%|
|migraphx_torchvision__densenet121i32|PASS|regression|1591.5437|1673.4347|81.891|5.15%|
|migraphx_torchvision__inceptioni1|PASS|regression|197.0866|221.348|24.2614|12.31%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5450.2628|5388.9789|-61.284|-1.12%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.4098|85.5755|0.1657|0.19%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5057.7288|5126.1681|68.4393|1.35%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2611.5247|2641.8773|30.3526|1.16%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4111.281|4073.775|-37.5059|-0.91%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5769.4345|5809.7522|40.3176|0.7%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|204.3055|176.9675|-27.338|-13.38%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|278.5797|267.4712|-11.1085|-3.99%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|410.3937|369.0756|-41.3181|-10.07%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|384.0331|402.2398|18.2067|4.74%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|616.8695|578.1443|-38.7253|-6.28%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|807.7745|983.5079|175.7333|21.76%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5075.0984|5096.0184|20.92|0.41%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8074.1199|7975.8941|-98.2257|-1.22%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11490.3701|11607.9535|117.5834|1.02%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|724.7409|714.5921|-10.1489|-1.4%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1252.6096|1115.7697|-136.8399|-10.92%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1585.8681|1518.8999|-66.9682|-4.22%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.237|1296.358|-6.879|-0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2099.2877|2048.0947|-51.193|-2.44%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2939.6702|3012.4891|72.8189|2.48%|

## No Regressions Found

## No Progressions Found

