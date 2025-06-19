# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|379.549|371.3214|-8.2276|-2.17%|
|migraphx_cadene__dpn92i1|PASS|progression|179.425|167.8402|-11.5848|-6.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5595.1088|5453.0631|-142.0458|-2.54%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|319.7768|722.094|402.3172|125.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|463.0647|417.2545|-45.8103|-9.89%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|561.4942|1675.6333|1114.1391|198.42%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|87.5353|88.2458|0.7105|0.81%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|57.9348|692.6173|634.6824|1095.51%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|210.3645|208.7236|-1.6408|-0.78%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|59.6379|58.3369|-1.301|-2.18%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.2775|21.1152|2.8376|15.53%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1582.2301|1551.5736|-30.6565|-1.94%|
|migraphx_torchvision__inceptioni1|PASS|within tol|192.679|192.8226|0.1437|0.07%|
|migraphx_torchvision__resnet50i1|PASS|regression|94.4901|223.4266|128.9365|136.46%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1598.6971|1582.6381|-16.0591|-1.0%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5532.462|5379.1757|-153.2862|-2.77%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9522.4283|9486.6968|-35.7315|-0.38%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|171.9146|174.9104|2.9958|1.74%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|250.6624|253.2205|2.5581|1.02%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|403.5284|360.7352|-42.7932|-10.6%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|239.8751|242.4176|2.5426|1.06%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|432.7201|435.0648|2.3447|0.54%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|654.7686|658.6959|3.9272|0.6%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5073.8794|5043.6197|-30.2597|-0.6%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13515.5477|13684.4477|168.9|1.25%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23521.1308|23760.9372|239.8064|1.02%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|414.9377|462.7992|47.8615|11.53%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|787.9016|852.7863|64.8847|8.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1252.3264|1230.6171|-21.7093|-1.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|750.2084|754.9295|4.7211|0.63%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2266.5853|1633.5767|-633.0086|-27.93%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3388.0081|3496.2265|108.2184|3.19%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224_dist_Opset16_timm|PASS|Numerics|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_224|Numerics|PASS|

