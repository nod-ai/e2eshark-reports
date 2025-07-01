# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|384.6333|387.6909|3.0576|0.79%|
|migraphx_cadene__dpn92i1|PASS|regression|168.8607|704.7615|535.9008|317.36%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5558.2621|5338.5751|-219.687|-3.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|314.6251|313.0168|-1.6083|-0.51%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|853.4824|407.8609|-445.6215|-52.21%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|459.7135|424.836|-34.8775|-7.59%|
|migraphx_mlperf__resnet50_v1|PASS|regression|85.729|90.0365|4.3075|5.02%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.0755|58.4851|-6.5904|-10.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|209.7238|207.2135|-2.5103|-1.2%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.6825|62.8109|3.1284|5.24%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|20.0833|22.0049|1.9215|9.57%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1539.4523|1536.7633|-2.689|-0.17%|
|migraphx_torchvision__inceptioni1|PASS|regression|207.5946|251.938|44.3434|21.36%|
|migraphx_torchvision__resnet50i1|PASS|progression|151.0669|82.6031|-68.4637|-45.32%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1576.9575|1595.8228|18.8653|1.2%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5285.7953|5325.6083|39.813|0.75%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9549.6365|9445.7777|-103.8588|-1.09%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|148.1255|147.9653|-0.1602|-0.11%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|280.9638|251.4864|-29.4774|-10.49%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|560.091|363.1947|-196.8963|-35.15%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|265.9051|247.0404|-18.8647|-7.09%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|437.0642|466.4974|29.4332|6.73%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|651.2397|1310.6646|659.4249|101.26%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5181.1429|5201.0247|19.8817|0.38%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14433.4132|13986.7674|-446.6458|-3.09%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24819.7397|23963.5579|-856.1818|-3.45%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|414.563|418.1658|3.6029|0.87%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|809.3872|802.0844|-7.3027|-0.9%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1242.6049|1225.276|-17.3289|-1.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|743.6346|741.2209|-2.4137|-0.32%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1632.0934|1696.9434|64.85|3.97%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3820.9885|3389.3839|-431.6046|-11.3%|

## No Regressions Found

## No Progressions Found

