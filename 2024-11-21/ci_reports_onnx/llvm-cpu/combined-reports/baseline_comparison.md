# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.632|90.2489|4.6168|5.39%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.1524|91.0516|4.8992|5.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.9527|283.1231|22.1704|8.5%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.2671|30.8056|-0.4614|-1.48%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.0977|84.0385|0.9407|1.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.0676|253.53|9.4624|3.88%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.5572|58.0826|17.5254|43.21%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|384.3665|-25.6836|-6.26%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.476|90.2893|-5.1868|-5.43%|
|migraphx_cadene__dpn92i1|PASS|within tol|186.2736|179.5863|-6.6873|-3.59%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|7257.2016|6798.9804|-458.2212|-6.31%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|335.8106|5.6935|1.72%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|420.8|447.327|26.527|6.3%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|484.5267|27.7718|6.08%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.8666|100.0333|-0.8333|-0.83%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|34.6198|-6.2613|-15.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9736|182.9482|-0.0254|-0.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|70.2852|73.7519|3.4667|4.93%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|41.0543|40.59|-0.4643|-1.13%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1377.2882|1326.3217|-50.9665|-3.7%|
|migraphx_torchvision__inceptioni1|PASS|within tol|258.7426|236.1918|-22.5507|-8.72%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6648.7116|6608.9371|-39.7745|-0.6%|
|migraphx_torchvision__resnet50i1|PASS|within tol|99.4756|91.338|-8.1377|-8.18%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6088.0794|6100.3103|12.2309|0.2%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2688.5782|2559.2035|-129.3747|-4.81%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.8175|4056.5432|-41.2743|-1.01%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6359.273|6011.2467|-348.0263|-5.47%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|169.0536|-19.2004|-10.2%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|274.272|-106.6136|-27.99%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|394.738|2.0605|0.52%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|395.0193|-69.1582|-14.9%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|646.0645|649.3725|3.3079|0.51%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|845.906|978.333|132.4271|15.66%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5134.5125|5242.6663|108.1537|2.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8841.4288|8985.55|144.1212|1.63%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11939.3575|12320.3268|380.9693|3.19%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|745.4025|737.4806|-7.9219|-1.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1125.1086|1198.6713|73.5627|6.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1749.2347|1770.8802|21.6455|1.24%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1532.455|1779.0932|246.6382|16.09%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2403.9663|2325.7349|-78.2313|-3.25%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3127.1362|3034.2025|-92.9338|-2.97%|

## No Regressions Found

## No Progressions Found

