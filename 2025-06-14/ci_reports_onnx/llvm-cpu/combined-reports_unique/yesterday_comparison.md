# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|381.6063|367.5605|-14.0458|-3.68%|
|migraphx_cadene__dpn92i1|PASS|regression|166.5829|189.8455|23.2626|13.96%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5398.8186|5434.504|35.6854|0.66%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|329.1071|343.2342|14.1271|4.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|398.9173|406.8135|7.8963|1.98%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|428.6238|466.1143|37.4905|8.75%|
|migraphx_mlperf__resnet50_v1|PASS|progression|133.1356|88.9914|-44.1441|-33.16%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|59.8347|65.3031|5.4683|9.14%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|207.1091|209.1228|2.0137|0.97%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|59.2479|69.8329|10.585|17.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.493|20.2592|-0.2338|-1.14%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1537.0874|1511.4868|-25.6005|-1.67%|
|migraphx_torchvision__inceptioni1|PASS|progression|232.3485|215.6419|-16.7066|-7.19%|
|migraphx_torchvision__resnet50i1|PASS|regression|95.1989|103.622|8.4231|8.85%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1602.2942|1518.7545|-83.5396|-5.21%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5317.8573|5129.5305|-188.3268|-3.54%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9521.6262|9392.829|-128.7972|-1.35%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|145.8725|149.4132|3.5407|2.43%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|249.427|255.4877|6.0606|2.43%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|372.2999|362.2893|-10.0106|-2.69%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|245.0181|239.23|-5.7881|-2.36%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|447.1378|433.2255|-13.9124|-3.11%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|668.6748|657.9013|-10.7736|-1.61%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5157.2659|4906.1691|-251.0968|-4.87%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13448.4824|13474.4688|25.9863|0.19%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23966.5108|23017.4597|-949.0511|-3.96%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|408.4613|409.0056|0.5443|0.13%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|786.6827|793.2275|6.5448|0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1240.0344|1229.6132|-10.4212|-0.84%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|748.1364|735.848|-12.2884|-1.64%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1696.4087|1661.9654|-34.4433|-2.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3449.5738|3344.502|-105.0717|-3.05%|

## No Regressions Found

## No Progressions Found

