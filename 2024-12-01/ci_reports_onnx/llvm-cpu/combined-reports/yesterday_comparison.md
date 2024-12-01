# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|89.8916|88.2212|-1.6705|-1.86%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.1816|88.5689|3.3874|3.98%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|256.0638|258.5508|2.4871|0.97%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|33.3817|33.3089|-0.0728|-0.22%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|84.5201|89.7217|5.2016|6.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|251.7971|287.0249|35.2278|13.99%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|45.563|38.9859|-6.5771|-14.44%|
|migraphx_bert__bert-large-uncased|PASS|regression|392.0753|435.1514|43.0761|10.99%|
|migraphx_bert__bertsquad-12|PASS|within tol|85.5971|86.1482|0.5511|0.64%|
|migraphx_cadene__dpn92i1|PASS|regression|179.4707|192.9711|13.5004|7.52%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6956.8683|6951.4036|-5.4647|-0.08%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|413.7348|388.5226|-25.2123|-6.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|378.4233|385.8569|7.4337|1.96%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|477.6531|426.4624|-51.1907|-10.72%|
|migraphx_mlperf__resnet50_v1|PASS|progression|113.0269|100.1351|-12.8918|-11.41%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|34.046|42.6313|8.5853|25.22%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|237.2332|183.1277|-54.1055|-22.81%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|79.7208|83.4827|3.7619|4.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|44.7527|41.9194|-2.8333|-6.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1345.3629|1411.0605|65.6977|4.88%|
|migraphx_torchvision__inceptioni1|PASS|within tol|219.3302|226.1344|6.8042|3.1%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6631.3472|6668.14|36.7928|0.55%|
|migraphx_torchvision__resnet50i1|PASS|within tol|90.353|94.7636|4.4106|4.88%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6061.1269|6110.128|49.0011|0.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2691.0461|2707.8304|16.7843|0.62%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4308.8355|4305.1983|-3.6372|-0.08%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5797.7072|5861.0192|63.3121|1.09%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.789|175.7041|18.9151|12.06%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|281.3423|262.469|-18.8733|-6.71%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|371.5205|381.0584|9.5379|2.57%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|380.417|400.4493|20.0323|5.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|587.905|577.8386|-10.0664|-1.71%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|808.8258|891.2971|82.4714|10.2%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5143.8313|5350.9991|207.1677|4.03%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8270.9624|8623.0956|352.1333|4.26%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11553.9552|11343.0706|-210.8846|-1.83%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|753.9786|720.9187|-33.0599|-4.38%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1113.7307|1116.3798|2.6491|0.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1520.0476|1522.9816|2.934|0.19%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1407.5527|1409.8551|2.3024|0.16%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|3388.4574|2314.3681|-1074.0893|-31.7%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3165.3496|3070.1918|-95.1578|-3.01%|

## No Regressions Found

## No Progressions Found

