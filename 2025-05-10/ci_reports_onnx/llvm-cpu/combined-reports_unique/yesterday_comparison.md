# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|614.4673|478.2208|-136.2465|-22.17%|
|migraphx_cadene__dpn92i1|PASS|progression|179.0857|168.4903|-10.5954|-5.92%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6109.3183|5831.3589|-277.9594|-4.55%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|310.9493|316.7118|5.7625|1.85%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|552.598|435.1924|-117.4057|-21.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|458.4913|422.4714|-36.02|-7.86%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|86.0868|86.2322|0.1454|0.17%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|58.2194|63.8151|5.5957|9.61%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.7943|208.4337|-0.3606|-0.17%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|58.6347|66.7281|8.0933|13.8%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|19.4013|20.144|0.7427|3.83%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1434.1501|1500.8766|66.7265|4.65%|
|migraphx_torchvision__inceptioni1|PASS|progression|231.1621|200.8158|-30.3462|-13.13%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.0558|90.4984|6.4426|7.66%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1553.528|1666.2088|112.6808|7.25%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5567.3285|5379.6784|-187.6501|-3.37%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9380.7925|9520.6044|139.8119|1.49%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.1713|151.8352|0.664|0.44%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|259.8101|520.8287|261.0186|100.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|374.6567|367.3776|-7.2791|-1.94%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.6711|242.2317|3.5606|1.49%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|455.0878|436.6793|-18.4086|-4.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|653.9793|655.5341|1.5548|0.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5092.6368|5140.3611|47.7243|0.94%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13539.0806|13655.6635|116.5829|0.86%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23442.4888|24464.1999|1021.7111|4.36%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|409.6568|414.2497|4.5928|1.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|791.4453|809.9318|18.4865|2.34%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1307.9713|1694.4316|386.4603|29.55%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|807.7893|758.2405|-49.5489|-6.13%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1794.7018|1660.1838|-134.518|-7.5%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3357.6152|3509.8773|152.2621|4.53%|

## No Regressions Found

## No Progressions Found

