# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|1025.8705|368.9772|-656.8933|-64.03%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.9703|166.3516|0.3814|0.23%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5167.3411|5358.025|190.684|3.69%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|308.5461|390.1018|81.5557|26.43%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|399.1553|516.613|117.4577|29.43%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1918.2554|477.6105|-1440.645|-75.1%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|82.9843|82.4871|-0.4972|-0.6%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|70.8846|57.6084|-13.2762|-18.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.6422|217.866|9.2238|4.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|313.4033|57.1984|-256.2048|-81.75%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.2739|21.2107|0.9369|4.62%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1497.2572|1511.2982|14.041|0.94%|
|migraphx_torchvision__inceptioni1|PASS|within tol|227.8935|226.0484|-1.8451|-0.81%|
|migraphx_torchvision__resnet50i1|PASS|progression|179.7368|87.0671|-92.6697|-51.56%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1544.6568|1538.9552|-5.7017|-0.37%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5306.3033|5273.4388|-32.8645|-0.62%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9459.2035|9551.518|92.3146|0.98%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.5555|167.4231|10.8676|6.94%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|251.0556|412.2828|161.2272|64.22%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|355.2088|355.4566|0.2478|0.07%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|297.3796|238.2093|-59.1703|-19.9%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|424.6335|430.115|5.4815|1.29%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|660.8366|665.3161|4.4796|0.68%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4920.1707|5921.7882|1001.6175|20.36%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13903.7499|13799.5484|-104.2015|-0.75%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23130.6199|23141.7702|11.1503|0.05%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|428.2654|405.0598|-23.2056|-5.42%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|798.7365|974.082|175.3455|21.95%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1254.9533|1218.6514|-36.3019|-2.89%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|740.0201|741.0792|1.0591|0.14%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1740.3988|1637.9833|-102.4155|-5.88%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3497.1462|3414.2355|-82.9107|-2.37%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|feastconv_Opset17_graph_convolutions|PASS|compilation|

## No Progressions Found

