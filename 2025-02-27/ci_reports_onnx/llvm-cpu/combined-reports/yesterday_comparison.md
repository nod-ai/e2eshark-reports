# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.9412|85.6194|-2.3219|-2.64%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|1248.4833|98.8797|-1149.6036|-92.08%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|882.4141|389.9558|-492.4583|-55.81%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.252|31.6286|1.3766|4.55%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|294.9066|85.6956|-209.211|-70.94%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|250.8608|302.5884|51.7275|20.62%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|43.9105|43.5361|-0.3745|-0.85%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.2897|0.8116|-0.4782|-37.07%|
|migraphx_bert__bert-large-uncased|PASS|progression|446.5265|388.6209|-57.9056|-12.97%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.897|168.8711|4.9742|3.03%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5464.5123|5582.8359|118.3235|2.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.1077|318.4912|-5.6164|-1.73%|
|migraphx_cadene__resnext101_64x4di16|PASS|progression|5322.8673|4994.1915|-328.6759|-6.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|401.0515|397.1388|-3.9127|-0.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|428.7916|428.8326|0.041|0.01%|
|migraphx_mlperf__resnet50_v1|PASS|regression|94.5504|102.3365|7.7862|8.23%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.114|33.321|1.207|3.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.8284|184.4399|4.6115|2.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|74.6635|91.3152|16.6517|22.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.5025|45.6884|6.1859|15.66%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1490.5346|1448.1761|-42.3584|-2.84%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.3387|205.8826|8.5439|4.33%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5780.4656|5762.2144|-18.2511|-0.32%|
|migraphx_torchvision__resnet50i1|PASS|progression|91.8357|84.2518|-7.5839|-8.26%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5392.8805|5449.2068|56.3263|1.04%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2485.7443|2549.1274|63.383|2.55%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4233.8683|4046.6068|-187.2615|-4.42%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5837.7181|5736.8504|-100.8678|-1.73%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|153.7266|159.3066|5.58|3.63%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|263.7978|265.4595|1.6617|0.63%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|376.3278|374.6092|-1.7186|-0.46%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|427.9197|403.9141|-24.0056|-5.61%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|637.535|627.1429|-10.3921|-1.63%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|817.7521|823.6496|5.8975|0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5120.9134|5203.5003|82.5869|1.61%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8318.6475|8200.4534|-118.1942|-1.42%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11270.8492|12307.3729|1036.5237|9.2%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|713.1092|878.9617|165.8525|23.26%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1094.187|1109.3586|15.1716|1.39%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1673.7461|2076.3135|402.5675|24.05%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1365.5085|1313.3331|-52.1754|-3.82%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2135.6369|2161.3715|25.7346|1.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3095.2948|3047.3938|-47.901|-1.55%|

## No Regressions Found

## No Progressions Found

