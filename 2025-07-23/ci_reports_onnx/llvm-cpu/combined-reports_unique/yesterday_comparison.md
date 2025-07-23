# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|374.1911|400.3651|26.174|6.99%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.0453|166.1308|1.0855|0.66%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5525.525|5610.955|85.4301|1.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.7075|311.6389|-4.0686|-1.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|407.957|400.6452|-7.3119|-1.79%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.1764|431.4135|7.2371|1.71%|
|migraphx_mlperf__resnet50_v1|PASS|regression|92.8442|106.0577|13.2135|14.23%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|63.0638|59.3969|-3.6668|-5.81%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|234.468|212.8621|-21.6058|-9.21%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|58.7062|60.2641|1.5578|2.65%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.0502|19.4105|1.3602|7.54%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1531.1189|1567.0799|35.961|2.35%|
|migraphx_torchvision__inceptioni1|PASS|progression|657.2785|195.6478|-461.6306|-70.23%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.9847|83.1321|-1.8526|-2.18%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1666.7914|1522.0457|-144.7457|-8.68%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5370.1408|5383.8954|13.7546|0.26%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9241.3925|9418.9549|177.5624|1.92%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|146.1989|153.7707|7.5717|5.18%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|250.711|257.7827|7.0717|2.82%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|360.2738|363.0357|2.7619|0.77%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|242.728|244.6383|1.9103|0.79%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|428.4672|430.9806|2.5134|0.59%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|658.7927|700.8348|42.0421|6.38%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5005.3387|4907.9112|-97.4275|-1.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13432.3129|13995.1909|562.8781|4.19%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24134.6679|24361.4693|226.8015|0.94%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|406.3381|741.0358|334.6977|82.37%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|823.8542|1105.0155|281.1612|34.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1232.7232|1244.4382|11.715|0.95%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|748.5428|996.6599|248.1171|33.15%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1650.486|1624.0736|-26.4124|-1.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3426.2681|3406.6206|-19.6475|-0.57%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|resnetv2_50d_evos.ah_in1k_train_vaiq|Numerics|PASS|
|resnetv2_50d_evos.ah_in1k_vaiq|Numerics|PASS|

