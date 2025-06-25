# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.9414|368.5756|-0.3658|-0.1%|
|migraphx_cadene__dpn92i1|PASS|regression|207.9785|226.9839|19.0055|9.14%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5641.561|5475.3469|-166.2141|-2.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|350.8542|328.6466|-22.2075|-6.33%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|409.275|443.7898|34.5148|8.43%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|460.0218|420.4867|-39.5351|-8.59%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|86.152|86.6108|0.4588|0.53%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|62.0741|70.1383|8.0642|12.99%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|209.089|208.1526|-0.9364|-0.45%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|68.7474|1391.0885|1322.3412|1923.48%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.8079|23.0348|2.2269|10.7%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1583.3859|1535.3132|-48.0727|-3.04%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.4629|200.6032|0.1402|0.07%|
|migraphx_torchvision__resnet50i1|PASS|regression|98.9792|244.1472|145.168|146.67%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1651.8543|1600.665|-51.1893|-3.1%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5422.8967|5331.5234|-91.3733|-1.68%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9384.3932|9321.9868|-62.4063|-0.67%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|147.9966|150.0879|2.0913|1.41%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|247.2407|252.8937|5.6531|2.29%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|364.5615|365.8535|1.292|0.35%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|236.4326|238.9969|2.5642|1.08%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|429.1347|702.7479|273.6132|63.76%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|655.0383|663.7994|8.7611|1.34%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5124.7514|5405.5361|280.7847|5.48%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13762.9655|13772.3959|9.4305|0.07%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|25276.3806|24139.6364|-1136.7442|-4.5%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|464.1603|407.8879|-56.2724|-12.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|797.1032|790.5159|-6.5873|-0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1254.5881|1228.7264|-25.8617|-2.06%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|806.7896|1035.9041|229.1145|28.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1654.076|1713.7261|59.6501|3.61%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3565.7614|4046.6056|480.8442|13.49%|

## No Regressions Found

## No Progressions Found

