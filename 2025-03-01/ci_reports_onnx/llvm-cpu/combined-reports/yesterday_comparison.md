# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|86.6297|99.102|12.4723|14.4%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.9172|88.3669|-0.5502|-0.62%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|257.5543|251.4167|-6.1376|-2.38%|
|migraphx_ORT__distilgpt2_1|PASS|regression|29.9561|34.0865|4.1304|13.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.7712|92.0651|6.2939|7.34%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|248.0639|250.8175|2.7536|1.11%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.126|41.6967|2.5707|6.57%|
|migraphx_agentmodel__AgentModel|Numerics|progression|1.3989|1.2045|-0.1945|-13.9%|
|migraphx_bert__bert-large-uncased|PASS|within tol|379.8601|389.4774|9.6173|2.53%|
|migraphx_cadene__dpn92i1|PASS|within tol|163.7837|162.7133|-1.0704|-0.65%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5656.0864|5549.922|-106.1644|-1.88%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|319.2182|360.0584|40.8402|12.79%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5054.3997|5185.8881|131.4884|2.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|403.6472|401.3073|-2.3399|-0.58%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|450.1272|2068.0058|1617.8786|359.43%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.5339|96.8108|1.2769|1.34%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|38.6328|36.1224|-2.5104|-6.5%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|178.5711|185.6731|7.102|3.98%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|96.4037|74.9819|-21.4218|-22.22%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|39.6021|46.408|6.8059|17.19%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1535.5128|1550.032|14.5192|0.95%|
|migraphx_torchvision__inceptioni1|PASS|progression|213.2093|196.0999|-17.1094|-8.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5821.5239|5789.3658|-32.1581|-0.55%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.5586|85.727|-0.8316|-0.96%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5445.0215|5362.7119|-82.3096|-1.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2630.9523|2608.0395|-22.9128|-0.87%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4098.9157|4245.9807|147.065|3.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5983.1963|5862.0465|-121.1498|-2.02%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|159.2633|161.4252|2.1619|1.36%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.7846|283.1746|9.39|3.43%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|453.8857|372.1469|-81.7388|-18.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|381.9176|384.9579|3.0403|0.8%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|596.3099|620.6578|24.3479|4.08%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|844.6136|826.2266|-18.387|-2.18%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5463.5948|4894.4229|-569.172|-10.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8014.9272|8010.0282|-4.8989|-0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11240.7549|11241.8571|1.1021|0.01%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|1216.8649|735.6813|-481.1836|-39.54%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1107.6884|1108.7672|1.0788|0.1%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1540.7426|1514.201|-26.5416|-1.72%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|3193.638|1291.2673|-1902.3707|-59.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2135.0759|2169.7596|34.6836|1.62%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2939.935|2945.0092|5.0742|0.17%|

## No Regressions Found

## No Progressions Found

