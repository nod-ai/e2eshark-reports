# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|376.9364|614.4673|237.5309|63.02%|
|migraphx_cadene__dpn92i1|PASS|progression|276.553|179.0857|-97.4673|-35.24%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5770.9452|6109.3183|338.3731|5.86%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|334.5707|310.9493|-23.6214|-7.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|403.5442|552.598|149.0538|36.94%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|424.9693|458.4913|33.522|7.89%|
|migraphx_mlperf__resnet50_v1|PASS|progression|300.6443|86.0868|-214.5575|-71.37%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.2246|58.2194|-0.0052|-0.01%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|209.7782|208.7943|-0.9839|-0.47%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|59.0888|58.6347|-0.4541|-0.77%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.2084|19.4013|0.1929|1.0%|
|migraphx_torchvision__densenet121i32|PASS|progression|1618.1364|1434.1501|-183.9863|-11.37%|
|migraphx_torchvision__inceptioni1|PASS|regression|197.2974|231.1621|33.8647|17.16%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.555|84.0558|0.5009|0.6%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1585.7033|1553.528|-32.1752|-2.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5371.2549|5567.3285|196.0736|3.65%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9586.9511|9380.7925|-206.1586|-2.15%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|174.7123|151.1713|-23.541|-13.47%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|262.0004|259.8101|-2.1903|-0.84%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|359.4702|374.6567|15.1864|4.22%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|242.2257|238.6711|-3.5546|-1.47%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|462.0768|455.0878|-6.989|-1.51%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|678.8963|653.9793|-24.917|-3.67%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5067.8385|5092.6368|24.7983|0.49%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14042.2474|13539.0806|-503.1668|-3.58%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24320.5401|23442.4888|-878.0512|-3.61%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|411.8354|409.6568|-2.1786|-0.53%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|806.4427|791.4453|-14.9975|-1.86%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1278.1324|1307.9713|29.839|2.33%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|791.9537|807.7893|15.8356|2.0%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1703.7037|1794.7018|90.9981|5.34%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3540.904|3357.6152|-183.2888|-5.18%|

## No Regressions Found

## No Progressions Found

