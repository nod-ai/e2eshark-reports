# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|86.2343|85.6354|-0.5989|-0.69%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|89.3641|90.05|0.6859|0.77%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|288.0662|257.8653|-30.2009|-10.48%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.4536|30.6471|0.1935|0.64%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|99.9059|87.2111|-12.6948|-12.71%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|252.4035|498.8842|246.4807|97.65%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|307.7231|39.6674|-268.0557|-87.11%|
|migraphx_bert__bert-large-uncased|PASS|regression|369.7435|404.8893|35.1458|9.51%|
|migraphx_cadene__dpn92i1|PASS|within tol|168.0101|164.2045|-3.8056|-2.27%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5356.6548|6078.8385|722.1837|13.48%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.0579|322.7273|-1.3306|-0.41%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5214.1125|5088.3962|-125.7163|-2.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.0678|371.6306|-8.4373|-2.22%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|416.043|418.5758|2.5328|0.61%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|92.0426|91.9156|-0.127|-0.14%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|31.5853|42.3405|10.7552|34.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|511.4263|186.0104|-325.416|-63.63%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|84.1417|83.4654|-0.6763|-0.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|47.3789|49.8363|2.4575|5.19%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1589.2855|1612.4539|23.1684|1.46%|
|migraphx_torchvision__inceptioni1|PASS|regression|191.204|202.9915|11.7875|6.16%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5390.8876|5373.2301|-17.6575|-0.33%|
|migraphx_torchvision__resnet50i1|PASS|within tol|85.2113|84.8826|-0.3286|-0.39%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5014.8474|5007.7643|-7.0831|-0.14%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2673.5434|2496.795|-176.7484|-6.61%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4196.1467|4213.2965|17.1498|0.41%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5823.0431|5712.8762|-110.1669|-1.89%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|165.6155|178.1273|12.5118|7.55%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.2465|261.1311|-12.1155|-4.43%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|375.6087|373.4917|-2.117|-0.56%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|388.1502|423.1505|35.0004|9.02%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|586.9483|598.4826|11.5344|1.97%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|864.6249|816.2125|-48.4124|-5.6%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5003.4327|5641.9187|638.486|12.76%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8635.0167|7967.6437|-667.373|-7.73%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11778.2794|11383.4274|-394.8521|-3.35%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|713.194|789.8769|76.683|10.75%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1081.8913|1091.3267|9.4354|0.87%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1551.9377|1512.3499|-39.5878|-2.55%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1308.2743|1304.7716|-3.5028|-0.27%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2241.8476|2015.6957|-226.1519|-10.09%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2884.1955|2917.0481|32.8526|1.14%|

## No Regressions Found

## No Progressions Found

