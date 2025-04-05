# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.1754|89.3189|2.1435|2.46%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|85.4021|87.1249|1.7228|2.02%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|499.8021|254.5284|-245.2738|-49.07%|
|migraphx_ORT__distilgpt2_1|PASS|regression|29.9071|39.8513|9.9442|33.25%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|87.8382|85.5951|-2.2431|-2.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|256.1269|253.2415|-2.8855|-1.13%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.7808|46.8027|6.0219|14.77%|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.4188|384.5049|14.0862|3.8%|
|migraphx_cadene__dpn92i1|PASS|within tol|164.4086|163.1378|-1.2708|-0.77%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5728.0116|5980.1964|252.1848|4.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|319.9642|802.8356|482.8714|150.91%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|399.9757|624.7736|224.7979|56.2%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|487.3119|425.3133|-61.9986|-12.72%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.502|96.4094|0.9074|0.95%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|1047.3331|31.3544|-1015.9787|-97.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|179.5255|178.6144|-0.9111|-0.51%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.3708|59.7723|-12.5985|-17.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|23.1388|20.4637|-2.6752|-11.56%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1571.8273|1572.3498|0.5225|0.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|190.8564|196.6489|5.7925|3.04%|
|migraphx_torchvision__resnet50i1|PASS|progression|92.9198|83.6143|-9.3055|-10.01%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1429.7559|1573.7472|143.9912|10.07%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|3021.6578|2988.3227|-33.3351|-1.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4820.2589|4756.5455|-63.7134|-1.32%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|149.5862|156.284|6.6978|4.48%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|282.4405|302.0027|19.5622|6.93%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|446.1265|394.8699|-51.2566|-11.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|241.0269|241.0055|-0.0213|-0.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|424.9964|428.6249|3.6285|0.85%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|657.4966|720.0937|62.5971|9.52%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2827.7323|2843.5303|15.7981|0.56%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5818.849|5875.3007|56.4517|0.97%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|8991.279|9030.4514|39.1724|0.44%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|404.3125|414.8446|10.5321|2.6%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|818.9248|795.9256|-22.9992|-2.81%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1232.5903|1240.739|8.1487|0.66%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|749.3892|747.097|-2.2922|-0.31%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1601.173|1976.6288|375.4558|23.45%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3099.6422|2374.5875|-725.0547|-23.39%|

## No Regressions Found

## No Progressions Found

