# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|progression|400.3651|367.8908|-32.4744|-8.11%|
|migraphx_cadene__dpn92i1|PASS|regression|166.1308|340.5317|174.4009|104.98%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5610.955|5437.8641|-173.091|-3.08%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|311.6389|319.1378|7.4989|2.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|400.6452|436.7901|36.145|9.02%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|431.4135|684.0925|252.679|58.57%|
|migraphx_mlperf__resnet50_v1|PASS|progression|106.0577|95.527|-10.5307|-9.93%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|59.3969|58.0711|-1.3258|-2.23%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|212.8621|210.2704|-2.5918|-1.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|60.2641|489.317|429.0529|711.95%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.4105|17.7429|-1.6676|-8.59%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1567.0799|1511.3281|-55.7518|-3.56%|
|migraphx_torchvision__inceptioni1|PASS|within tol|195.6478|189.9141|-5.7337|-2.93%|
|migraphx_torchvision__resnet50i1|PASS|regression|83.1321|107.4199|24.2878|29.22%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1522.0457|1605.8373|83.7917|5.51%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5383.8954|5462.3591|78.4638|1.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9418.9549|9491.7477|72.7928|0.77%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|153.7707|162.0478|8.2772|5.38%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|257.7827|275.3602|17.5775|6.82%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|363.0357|363.5648|0.5291|0.15%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|244.6383|284.9862|40.3478|16.49%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|430.9806|424.0603|-6.9203|-1.61%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|700.8348|900.9682|200.1333|28.56%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|4907.9112|5469.9791|562.0679|11.45%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13995.1909|14443.1935|448.0025|3.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|24361.4693|22587.7391|-1773.7303|-7.28%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|741.0358|411.586|-329.4498|-44.46%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1105.0155|789.022|-315.9935|-28.6%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1244.4382|1449.568|205.1298|16.48%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|996.6599|733.2127|-263.4472|-26.43%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1624.0736|1631.9369|7.8633|0.48%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3406.6206|3360.6808|-45.9397|-1.35%|

## No Regressions Found

## No Progressions Found

