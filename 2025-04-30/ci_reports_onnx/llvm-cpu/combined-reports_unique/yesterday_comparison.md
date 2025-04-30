# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|369.8524|806.3366|436.4843|118.02%|
|migraphx_cadene__dpn92i1|PASS|regression|200.529|228.0272|27.4982|13.71%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5534.1703|5658.31|124.1397|2.24%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.0188|319.1154|4.0966|1.3%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|398.8094|456.2739|57.4645|14.41%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|429.0772|427.6723|-1.405|-0.33%|
|migraphx_mlperf__resnet50_v1|PASS|regression|86.5018|97.1404|10.6387|12.3%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|57.3159|57.5249|0.209|0.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|208.9441|233.7867|24.8426|11.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|65.7037|58.8634|-6.8403|-10.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.5955|20.7265|2.131|11.46%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1507.0492|1495.0815|-11.9677|-0.79%|
|migraphx_torchvision__inceptioni1|PASS|within tol|198.5868|201.6287|3.0419|1.53%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.5376|84.3044|0.7668|0.92%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1529.4707|1574.5622|45.0915|2.95%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5264.9729|5380.7343|115.7614|2.2%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9583.9948|9305.6212|-278.3736|-2.9%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|152.881|179.7589|26.8779|17.58%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.8194|265.079|3.2597|1.25%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|390.3605|367.2539|-23.1065|-5.92%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|247.3202|242.348|-4.9722|-2.01%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|456.5354|431.5223|-25.0131|-5.48%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|666.8708|667.9362|1.0654|0.16%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5147.8716|5091.5415|-56.3301|-1.09%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|13339.9344|14072.9163|732.9819|5.49%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23615.7154|22977.8865|-637.8288|-2.7%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|405.4992|414.7023|9.2031|2.27%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|798.5473|787.0337|-11.5136|-1.44%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1266.0063|1231.3937|-34.6125|-2.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|791.6392|752.2915|-39.3477|-4.97%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1754.9413|1969.0253|214.084|12.2%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3390.6152|3606.7788|216.1635|6.38%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|mosaic-9|compilation|Numerics|

