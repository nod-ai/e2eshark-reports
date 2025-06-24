# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|372.0586|368.9414|-3.1172|-0.84%|
|migraphx_cadene__dpn92i1|PASS|regression|166.1648|207.9785|41.8136|25.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5504.6406|5641.561|136.9205|2.49%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|321.7518|350.8542|29.1024|9.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|399.3722|409.275|9.9028|2.48%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1092.901|460.0218|-632.8792|-57.91%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|87.0277|86.152|-0.8757|-1.01%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|58.4102|62.0741|3.6639|6.27%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|209.2986|209.089|-0.2096|-0.1%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.1023|68.7474|9.6451|16.32%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.2993|20.8079|1.5086|7.82%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1617.2998|1583.3859|-33.9139|-2.1%|
|migraphx_torchvision__inceptioni1|PASS|progression|211.6937|200.4629|-11.2308|-5.31%|
|migraphx_torchvision__resnet50i1|PASS|regression|93.9857|98.9792|4.9935|5.31%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1656.1074|1651.8543|-4.2531|-0.26%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|6393.8556|5422.8967|-970.9589|-15.19%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|10279.2695|9384.3932|-894.8763|-8.71%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|150.7175|147.9966|-2.721|-1.81%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|286.6372|247.2407|-39.3966|-13.74%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|358.7736|364.5615|5.7879|1.61%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.4714|236.4326|-3.0388|-1.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|423.6363|429.1347|5.4984|1.3%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|662.6716|655.0383|-7.6333|-1.15%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5030.839|5124.7514|93.9124|1.87%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13558.6739|13762.9655|204.2915|1.51%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|22720.7572|25276.3806|2555.6234|11.25%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|411.402|464.1603|52.7583|12.82%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|786.8881|797.1032|10.2151|1.3%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1223.1337|1254.5881|31.4544|2.57%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|807.6016|806.7896|-0.812|-0.1%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1634.3752|1654.076|19.7008|1.21%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3375.6258|3565.7614|190.1356|5.63%|

## No Regressions Found

## No Progressions Found

