# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|368.8098|381.6063|12.7965|3.47%|
|migraphx_cadene__dpn92i1|PASS|within tol|165.4352|166.5829|1.1477|0.69%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5441.8179|5398.8186|-42.9993|-0.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.8563|329.1071|9.2508|2.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|407.721|398.9173|-8.8038|-2.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|424.4292|428.6238|4.1946|0.99%|
|migraphx_mlperf__resnet50_v1|PASS|regression|87.694|133.1356|45.4416|51.82%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.1624|59.8347|1.6723|2.88%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.1809|207.1091|-1.0718|-0.51%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|61.9611|59.2479|-2.7132|-4.38%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|17.4112|20.493|3.0818|17.7%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1531.5741|1537.0874|5.5133|0.36%|
|migraphx_torchvision__inceptioni1|PASS|regression|206.3549|232.3485|25.9936|12.6%|
|migraphx_torchvision__resnet50i1|PASS|within tol|94.2365|95.1989|0.9625|1.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1528.1124|1602.2942|74.1818|4.85%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5550.5768|5317.8573|-232.7195|-4.19%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9616.5435|9521.6262|-94.9173|-0.99%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|145.6972|145.8725|0.1753|0.12%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|265.1436|249.427|-15.7166|-5.93%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|416.2654|372.2999|-43.9655|-10.56%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|248.8763|245.0181|-3.8582|-1.55%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|433.4456|447.1378|13.6923|3.16%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|657.9365|668.6748|10.7383|1.63%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5202.0691|5157.2659|-44.8032|-0.86%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13648.4152|13448.4824|-199.9328|-1.46%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23946.204|23966.5108|20.3069|0.08%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|429.2203|408.4613|-20.759|-4.84%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1039.0998|786.6827|-252.4171|-24.29%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1225.9668|1240.0344|14.0676|1.15%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1227.8513|748.1364|-479.7149|-39.07%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1704.5229|1696.4087|-8.1142|-0.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3467.7494|3449.5738|-18.1757|-0.52%|

## No Regressions Found

## No Progressions Found

