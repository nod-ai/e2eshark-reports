# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.1582|374.1911|4.033|1.09%|
|migraphx_cadene__dpn92i1|PASS|progression|181.5051|165.0453|-16.4598|-9.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5586.4766|5525.525|-60.9516|-1.09%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|350.9516|315.7075|-35.2442|-10.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|435.2004|407.957|-27.2433|-6.26%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|425.6015|424.1764|-1.4251|-0.33%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.8355|92.8442|-1.9912|-2.1%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|58.6533|63.0638|4.4104|7.52%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|247.8086|234.468|-13.3406|-5.38%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|71.6496|58.7062|-12.9433|-18.06%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.491|18.0502|-1.4407|-7.39%|
|migraphx_torchvision__densenet121i32|PASS|progression|1722.1474|1531.1189|-191.0285|-11.09%|
|migraphx_torchvision__inceptioni1|PASS|regression|209.9993|657.2785|447.2792|212.99%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.0425|84.9847|0.9422|1.12%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1560.3476|1666.7914|106.4438|6.82%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5598.9439|5370.1408|-228.8032|-4.09%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9691.4289|9241.3925|-450.0364|-4.64%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.5246|146.1989|-4.3257|-2.87%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|252.9906|250.711|-2.2796|-0.9%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|365.1982|360.2738|-4.9243|-1.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|240.7705|242.728|1.9575|0.81%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|485.1444|428.4672|-56.6772|-11.68%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|758.9157|658.7927|-100.123|-13.19%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5044.5484|5005.3387|-39.2097|-0.78%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13550.4865|13432.3129|-118.1736|-0.87%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23913.7795|24134.6679|220.8884|0.92%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|409.5651|406.3381|-3.227|-0.79%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|815.2673|823.8542|8.5869|1.05%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1237.0634|1232.7232|-4.3402|-0.35%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|744.6108|748.5428|3.9319|0.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1645.3721|1650.486|5.1139|0.31%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3429.1002|3426.2681|-2.8321|-0.08%|

## No Regressions Found

## No Progressions Found

