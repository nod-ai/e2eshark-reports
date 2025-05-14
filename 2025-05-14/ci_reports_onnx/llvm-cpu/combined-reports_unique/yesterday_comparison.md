# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|552.9318|370.1676|-182.7641|-33.05%|
|migraphx_cadene__dpn92i1|PASS|within tol|185.8459|190.2556|4.4097|2.37%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6155.06|6112.274|-42.7861|-0.7%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|395.167|390.6285|-4.5385|-1.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|430.4875|404.7428|-25.7447|-5.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|431.5371|493.6413|62.1042|14.39%|
|migraphx_mlperf__resnet50_v1|PASS|regression|85.6596|251.4819|165.8223|193.58%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|57.8582|139.4321|81.5739|140.99%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.9423|209.782|0.8396|0.4%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|62.1864|65.4607|3.2744|5.27%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.7031|20.9905|0.2874|1.39%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1494.2119|1441.9322|-52.2797|-3.5%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.7097|200.2671|2.5573|1.29%|
|migraphx_torchvision__resnet50i1|PASS|progression|89.6652|84.5326|-5.1327|-5.72%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1615.865|1556.0618|-59.8032|-3.7%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5516.2178|5515.1038|-1.1139|-0.02%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9440.7319|9192.8547|-247.8772|-2.63%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|147.1568|159.991|12.8342|8.72%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|254.6074|305.9299|51.3226|20.16%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|357.3122|387.9329|30.6208|8.57%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|240.3789|254.6088|14.2299|5.92%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|430.4742|646.7811|216.307|50.25%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|662.3074|683.6289|21.3215|3.22%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5225.1237|5150.5937|-74.53|-1.43%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13736.3256|13690.4379|-45.8877|-0.33%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22647.0243|23458.4744|811.4501|3.58%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.6725|408.2493|0.5768|0.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|788.4119|821.5203|33.1083|4.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1217.722|1238.5871|20.865|1.71%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|744.0802|740.5072|-3.573|-0.48%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1764.5278|1755.4089|-9.119|-0.52%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3539.3932|3499.608|-39.7852|-1.12%|

## No Regressions Found

## No Progressions Found

