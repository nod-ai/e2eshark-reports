# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|363.6261|369.9618|6.3357|1.74%|
|migraphx_cadene__dpn92i1|PASS|within tol|167.5047|164.7201|-2.7847|-1.66%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5493.8171|5462.8749|-30.9422|-0.56%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.7578|321.2633|4.5055|1.42%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|392.5603|404.341|11.7807|3.0%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|431.1756|552.9995|121.8239|28.25%|
|migraphx_mlperf__resnet50_v1|PASS|progression|100.5821|94.0466|-6.5355|-6.5%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.072|57.6361|-7.4359|-11.43%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|206.9503|208.6636|1.7132|0.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.2334|78.3615|19.1281|32.29%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|24.5357|20.7574|-3.7784|-15.4%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1629.7042|1564.2104|-65.4938|-4.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|190.5223|196.9008|6.3785|3.35%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.9612|83.1234|-0.8377|-1.0%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1544.0907|1578.9915|34.9008|2.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5327.525|5358.6846|31.1596|0.58%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9602.371|9405.8571|-196.5138|-2.05%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|193.7054|1290.0903|1096.3849|566.01%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|252.3949|256.4351|4.0402|1.6%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|387.5953|406.9706|19.3753|5.0%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|242.2302|259.8148|17.5847|7.26%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|434.5132|452.2488|17.7356|4.08%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|659.17|653.0403|-6.1297|-0.93%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5038.2263|5215.0489|176.8226|3.51%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14164.9526|13860.5059|-304.4467|-2.15%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23578.7201|23330.0521|-248.668|-1.05%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|500.5065|413.8148|-86.6918|-17.32%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|795.9008|818.9242|23.0234|2.89%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1262.8608|1249.8256|-13.0352|-1.03%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|772.7691|736.6714|-36.0977|-4.67%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1723.6334|1676.1216|-47.5118|-2.76%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3463.9342|3472.6162|8.6821|0.25%|

## No Regressions Found

## No Progressions Found

