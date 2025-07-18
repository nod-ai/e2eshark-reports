# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|1217.6099|363.6261|-853.9838|-70.14%|
|migraphx_cadene__dpn92i1|PASS|within tol|167.7466|167.5047|-0.2419|-0.14%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5557.5233|5493.8171|-63.7062|-1.15%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.7114|316.7578|0.0464|0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|406.5554|392.5603|-13.9952|-3.44%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|428.0714|431.1756|3.1042|0.73%|
|migraphx_mlperf__resnet50_v1|PASS|regression|92.7257|100.5821|7.8564|8.47%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|64.8724|65.072|0.1996|0.31%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|256.0504|206.9503|-49.1|-19.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|219.3771|59.2334|-160.1437|-73.0%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.8721|24.5357|4.6636|23.47%|
|migraphx_torchvision__densenet121i32|PASS|regression|1517.7902|1629.7042|111.914|7.37%|
|migraphx_torchvision__inceptioni1|PASS|within tol|189.967|190.5223|0.5553|0.29%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.9178|83.9612|0.0433|0.05%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1584.9867|1544.0907|-40.896|-2.58%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5382.1731|5327.525|-54.6482|-1.02%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9566.8636|9602.371|35.5074|0.37%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|235.8701|193.7054|-42.1648|-17.88%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|390.6584|252.3949|-138.2634|-35.39%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|365.5857|387.5953|22.0095|6.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|240.3459|242.2302|1.8843|0.78%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|565.007|434.5132|-130.4939|-23.1%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|655.8313|659.17|3.3387|0.51%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5461.5429|5038.2263|-423.3166|-7.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13868.5515|14164.9526|296.4011|2.14%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23539.0715|23578.7201|39.6486|0.17%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|412.9934|500.5065|87.5132|21.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|810.7135|795.9008|-14.8126|-1.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1316.5863|1262.8608|-53.7255|-4.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|744.0918|772.7691|28.6773|3.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1650.7039|1723.6334|72.9295|4.42%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3414.7021|3463.9342|49.2321|1.44%|

## No Regressions Found

## No Progressions Found

