# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|368.9772|504.736|135.7588|36.79%|
|migraphx_cadene__dpn92i1|PASS|regression|166.3516|285.7305|119.3788|71.76%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5358.025|5278.3237|-79.7013|-1.49%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|390.1018|329.8656|-60.2362|-15.44%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|516.613|445.7918|-70.8211|-13.71%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|477.6105|423.2049|-54.4056|-11.39%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|82.4871|84.5567|2.0696|2.51%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.6084|57.9044|0.2959|0.51%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|217.866|805.5592|587.6932|269.75%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|57.1984|74.504|17.3055|30.26%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|21.2107|18.6733|-2.5374|-11.96%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1511.2982|1498.661|-12.6372|-0.84%|
|migraphx_torchvision__inceptioni1|PASS|regression|226.0484|241.7056|15.6572|6.93%|
|migraphx_torchvision__resnet50i1|PASS|regression|87.0671|103.8714|16.8043|19.3%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1538.9552|1545.3101|6.355|0.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5273.4388|5312.4352|38.9964|0.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9551.518|9726.4878|174.9698|1.83%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|167.4231|149.6634|-17.7596|-10.61%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|412.2828|285.2525|-127.0303|-30.81%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|355.4566|447.6193|92.1628|25.93%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.2093|241.5671|3.3577|1.41%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.115|435.6617|5.5467|1.29%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|665.3161|677.5293|12.2132|1.84%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5921.7882|5259.6289|-662.1592|-11.18%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13799.5484|14400.2519|600.7034|4.35%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23141.7702|22871.2588|-270.5114|-1.17%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|405.0598|421.7249|16.6651|4.11%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|974.082|798.5787|-175.5033|-18.02%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1218.6514|1241.6926|23.0412|1.89%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|741.0792|753.0011|11.9219|1.61%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1637.9833|1671.6618|33.6785|2.06%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3414.2355|4146.9416|732.7061|21.46%|

## No Regressions Found

## No Progressions Found

