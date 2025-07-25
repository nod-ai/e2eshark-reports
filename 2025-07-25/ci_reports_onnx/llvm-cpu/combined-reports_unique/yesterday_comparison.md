# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|367.8908|554.5658|186.6751|50.74%|
|migraphx_cadene__dpn92i1|PASS|progression|340.5317|172.8443|-167.6873|-49.24%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5437.8641|5490.1264|52.2624|0.96%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.1378|330.4054|11.2676|3.53%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|436.7901|529.8573|93.0671|21.31%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|684.0925|466.4416|-217.6509|-31.82%|
|migraphx_mlperf__resnet50_v1|PASS|regression|95.527|335.5489|240.0219|251.26%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.0711|57.8389|-0.2321|-0.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|210.2704|207.7363|-2.5341|-1.21%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|489.317|63.9868|-425.3301|-86.92%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.7429|25.9225|8.1796|46.1%|
|migraphx_torchvision__densenet121i32|PASS|regression|1511.3281|1608.6665|97.3384|6.44%|
|migraphx_torchvision__inceptioni1|PASS|regression|189.9141|217.4096|27.4955|14.48%|
|migraphx_torchvision__resnet50i1|PASS|progression|107.4199|96.331|-11.0889|-10.32%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1605.8373|1699.7734|93.9361|5.85%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5462.3591|5421.5127|-40.8464|-0.75%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9491.7477|9663.1206|171.3729|1.81%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|162.0478|363.9288|201.881|124.58%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|275.3602|269.9579|-5.4023|-1.96%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|363.5648|372.2087|8.6439|2.38%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|284.9862|245.4621|-39.524|-13.87%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|424.0603|431.9562|7.896|1.86%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|900.9682|660.8371|-240.1311|-26.65%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5469.9791|5020.4186|-449.5605|-8.22%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14443.1935|13765.5824|-677.611|-4.69%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|22587.7391|23068.1654|480.4263|2.13%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|411.586|421.8914|10.3054|2.5%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|789.022|787.4374|-1.5846|-0.2%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1449.568|1232.2346|-217.3334|-14.99%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|733.2127|752.8722|19.6595|2.68%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1631.9369|1705.8337|73.8968|4.53%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3360.6808|3483.7681|123.0873|3.66%|

## No Regressions Found

## No Progressions Found

