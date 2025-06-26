# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.5756|368.7395|0.1639|0.04%|
|migraphx_cadene__dpn92i1|PASS|regression|226.9839|810.6182|583.6342|257.13%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5475.3469|5623.9197|148.5728|2.71%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|328.6466|311.7367|-16.9099|-5.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|443.7898|400.3088|-43.481|-9.8%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|420.4867|514.5991|94.1124|22.38%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|86.6108|90.9011|4.2904|4.95%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|70.1383|61.9548|-8.1836|-11.67%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.1526|206.9892|-1.1634|-0.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|1391.0885|58.8773|-1332.2113|-95.77%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|23.0348|20.709|-2.3258|-10.1%|
|migraphx_torchvision__densenet121i32|PASS|regression|1535.3132|1657.1511|121.8379|7.94%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.6032|196.4592|-4.144|-2.07%|
|migraphx_torchvision__resnet50i1|PASS|progression|244.1472|111.2386|-132.9086|-54.44%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1600.665|1894.1816|293.5167|18.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5331.5234|5282.1973|-49.3261|-0.93%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9321.9868|9727.0706|405.0838|4.35%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|150.0879|182.925|32.8371|21.88%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|252.8937|250.3915|-2.5022|-0.99%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|365.8535|491.8543|126.0007|34.44%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.9969|240.006|1.0091|0.42%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|702.7479|462.5319|-240.216|-34.18%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|663.7994|693.2319|29.4325|4.43%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5405.5361|5135.3102|-270.2259|-5.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13772.3959|13794.0324|21.6365|0.16%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24139.6364|23782.7968|-356.8397|-1.48%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.8879|412.0171|4.1292|1.01%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|790.5159|799.0586|8.5428|1.08%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1228.7264|1242.1834|13.4569|1.1%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1035.9041|738.8654|-297.0387|-28.67%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1713.7261|1749.9531|36.227|2.11%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|4046.6056|3497.5834|-549.0222|-13.57%|

## No Regressions Found

## No Progressions Found

