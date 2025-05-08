# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|370.1102|376.9364|6.8262|1.84%|
|migraphx_cadene__dpn92i1|PASS|regression|167.7351|276.553|108.8178|64.87%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5552.0132|5770.9452|218.932|3.94%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.8471|334.5707|14.7236|4.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|446.368|403.5442|-42.8239|-9.59%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|427.7162|424.9693|-2.7468|-0.64%|
|migraphx_mlperf__resnet50_v1|PASS|regression|87.606|300.6443|213.0383|243.18%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.8668|58.2246|-7.6422|-11.6%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|228.6677|209.7782|-18.8896|-8.26%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|68.2013|59.0888|-9.1125|-13.36%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|18.9593|19.2084|0.2492|1.31%|
|migraphx_torchvision__densenet121i32|PASS|regression|1437.0102|1618.1364|181.1262|12.6%|
|migraphx_torchvision__inceptioni1|PASS|progression|217.8575|197.2974|-20.5601|-9.44%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.3249|83.555|-0.7699|-0.91%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1692.0887|1585.7033|-106.3854|-6.29%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5348.7693|5371.2549|22.4856|0.42%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9619.6332|9586.9511|-32.6821|-0.34%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|149.1579|174.7123|25.5544|17.13%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|273.6381|262.0004|-11.6377|-4.25%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|377.5878|359.4702|-18.1176|-4.8%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|247.2711|242.2257|-5.0454|-2.04%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|469.843|462.0768|-7.7662|-1.65%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|721.7453|678.8963|-42.849|-5.94%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5241.1779|5067.8385|-173.3394|-3.31%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13969.1677|14042.2474|73.0796|0.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23928.1815|24320.5401|392.3586|1.64%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|428.4203|411.8354|-16.5849|-3.87%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|893.2779|806.4427|-86.8351|-9.72%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1234.1976|1278.1324|43.9347|3.56%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|744.8371|791.9537|47.1167|6.33%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1740.9222|1703.7037|-37.2186|-2.14%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3517.8225|3540.904|23.0815|0.66%|

## No Regressions Found

## No Progressions Found

