# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|213.6779|198.1785|-15.4994|-7.25%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|196.1269|229.7131|33.5862|17.12%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|572.7957|870.9975|298.2018|52.06%|
|migraphx_ORT__distilgpt2_1|PASS|progression|239.7029|86.2689|-153.4339|-64.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|200.1743|222.764|22.5897|11.28%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|550.9199|545.9456|-4.9743|-0.9%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|221.2471|97.4694|-123.7777|-55.95%|
|migraphx_bert__bert-large-uncased|PASS|regression|371.0104|608.5696|237.5592|64.03%|
|migraphx_cadene__dpn92i1|PASS|regression|166.2851|176.9603|10.6752|6.42%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5362.6961|5384.065|21.3688|0.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|414.4043|356.0632|-58.341|-14.08%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|429.5539|424.501|-5.0529|-1.18%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|553.7102|504.0913|-49.6189|-8.96%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.0971|97.0975|3.0004|3.19%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|61.9992|60.5098|-1.4894|-2.4%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|215.2577|285.6606|70.4029|32.71%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|65.2687|68.076|2.8073|4.3%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.3384|20.1656|-0.1728|-0.85%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1526.7909|1528.7416|1.9508|0.13%|
|migraphx_torchvision__inceptioni1|PASS|regression|199.815|224.8065|24.9915|12.51%|
|migraphx_torchvision__resnet50i1|PASS|regression|89.247|108.1932|18.9462|21.23%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1624.8027|1749.4488|124.6461|7.67%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|5128.716|5448.2172|319.5011|6.23%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9490.8917|9749.0323|258.1406|2.72%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|151.1458|152.2083|1.0626|0.7%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|256.1062|305.6092|49.503|19.33%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|365.0859|440.8253|75.7394|20.75%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|235.932|246.6156|10.6835|4.53%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|434.9777|430.9781|-3.9995|-0.92%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|663.0911|728.1221|65.031|9.81%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|4977.7319|5217.4438|239.7119|4.82%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13595.9152|14053.9814|458.0662|3.37%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23056.4089|22783.0191|-273.3898|-1.19%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|400.4978|403.8377|3.3399|0.83%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|786.2066|781.9456|-4.261|-0.54%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1230.9645|1233.1389|2.1744|0.18%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|742.0845|806.1525|64.068|8.63%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1629.8401|1688.966|59.1259|3.63%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3333.4638|3513.6938|180.23|5.41%|

## No Regressions Found

## No Progressions Found

