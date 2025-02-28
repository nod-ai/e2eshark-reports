# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.6194|86.6297|1.0103|1.18%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|98.8797|88.9172|-9.9625|-10.08%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|389.9558|257.5543|-132.4014|-33.95%|
|migraphx_ORT__distilgpt2_1|PASS|progression|31.6286|29.9561|-1.6725|-5.29%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.6956|85.7712|0.0756|0.09%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|302.5884|248.0639|-54.5245|-18.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|43.5361|39.126|-4.4101|-10.13%|
|migraphx_agentmodel__AgentModel|Numerics|regression|0.8116|1.3989|0.5873|72.37%|
|migraphx_bert__bert-large-uncased|PASS|within tol|388.6209|379.8601|-8.7608|-2.25%|
|migraphx_cadene__dpn92i1|PASS|within tol|168.8711|163.7837|-5.0874|-3.01%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5582.8359|5656.0864|73.2505|1.31%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|318.4912|319.2182|0.727|0.23%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|4994.1915|5054.3997|60.2083|1.21%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|397.1388|403.6472|6.5085|1.64%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|428.8326|450.1272|21.2946|4.97%|
|migraphx_mlperf__resnet50_v1|PASS|progression|102.3365|95.5339|-6.8026|-6.65%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.321|38.6328|5.3117|15.94%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|184.4399|178.5711|-5.8688|-3.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|91.3152|96.4037|5.0885|5.57%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|45.6884|39.6021|-6.0863|-13.32%|
|migraphx_torchvision__densenet121i32|PASS|regression|1448.1761|1535.5128|87.3367|6.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|205.8826|213.2093|7.3267|3.56%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5762.2144|5821.5239|59.3095|1.03%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.2518|86.5586|2.3068|2.74%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5449.2068|5445.0215|-4.1853|-0.08%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2549.1274|2630.9523|81.825|3.21%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4046.6068|4098.9157|52.3088|1.29%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5736.8504|5983.1963|246.3459|4.29%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.3066|159.2633|-0.0432|-0.03%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.4595|273.7846|8.3251|3.14%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|374.6092|453.8857|79.2765|21.16%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|403.9141|381.9176|-21.9965|-5.45%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|627.1429|596.3099|-30.833|-4.92%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|823.6496|844.6136|20.964|2.55%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5203.5003|5463.5948|260.0945|5.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8200.4534|8014.9272|-185.5262|-2.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|12307.3729|11240.7549|-1066.6179|-8.67%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|878.9617|1216.8649|337.9032|38.44%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1109.3586|1107.6884|-1.6702|-0.15%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|2076.3135|1540.7426|-535.5709|-25.79%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1313.3331|3193.638|1880.3049|143.17%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2161.3715|2135.0759|-26.2956|-1.22%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3047.3938|2939.935|-107.4588|-3.53%|

## No Regressions Found

## No Progressions Found

