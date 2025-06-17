# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|390.8416|370.7773|-20.0643|-5.13%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.7891|166.7303|-0.0588|-0.04%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5573.771|5474.7407|-99.0303|-1.78%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|317.8906|322.3078|4.4173|1.39%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|400.6257|411.179|10.5533|2.63%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|469.3227|443.5247|-25.7979|-5.5%|
|migraphx_mlperf__resnet50_v1|PASS|regression|87.9509|103.398|15.4471|17.56%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|65.2179|58.1973|-7.0206|-10.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|209.1525|208.9794|-0.1731|-0.08%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|58.1673|62.7113|4.544|7.81%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.6567|23.0309|3.3742|17.17%|
|migraphx_torchvision__densenet121i32|PASS|regression|1541.5624|1688.5376|146.9752|9.53%|
|migraphx_torchvision__inceptioni1|PASS|within tol|193.0212|192.6399|-0.3813|-0.2%|
|migraphx_torchvision__resnet50i1|PASS|regression|94.8177|102.1985|7.3808|7.78%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1530.9329|1573.9636|43.0306|2.81%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5651.0384|5559.7321|-91.3063|-1.62%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9365.7084|9572.6787|206.9703|2.21%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|145.6145|165.9429|20.3284|13.96%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|247.4586|256.5312|9.0726|3.67%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|545.9397|361.4643|-184.4754|-33.79%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|243.3852|806.0487|562.6635|231.18%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|435.2489|426.4189|-8.83|-2.03%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|657.2724|666.0216|8.7492|1.33%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5168.5376|5047.9132|-120.6245|-2.33%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13407.8953|13642.6287|234.7333|1.75%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23263.4136|22993.374|-270.0397|-1.16%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|402.3873|417.0313|14.644|3.64%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|942.4231|866.8245|-75.5986|-8.02%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1228.6182|1233.9262|5.308|0.43%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|743.9256|798.3228|54.3973|7.31%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1701.7913|1658.2179|-43.5733|-2.56%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3475.4106|3374.6099|-100.8006|-2.9%|

## No Regressions Found

## No Progressions Found

