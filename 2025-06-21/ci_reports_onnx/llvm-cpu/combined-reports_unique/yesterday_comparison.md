# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.0236|378.7826|9.759|2.64%|
|migraphx_cadene__dpn92i1|PASS|within tol|167.8276|168.8133|0.9858|0.59%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5619.9272|5665.1769|45.2498|0.81%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|335.7868|364.8291|29.0423|8.65%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|405.9851|417.4583|11.4732|2.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|431.3931|481.8782|50.4851|11.7%|
|migraphx_mlperf__resnet50_v1|PASS|regression|88.0515|104.0067|15.9551|18.12%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|58.3984|57.3955|-1.0029|-1.72%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|206.6203|236.6053|29.985|14.51%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|58.6645|59.2077|0.5432|0.93%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|19.2304|22.9236|3.6932|19.2%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1587.7453|1542.105|-45.6403|-2.87%|
|migraphx_torchvision__inceptioni1|PASS|within tol|192.0389|196.773|4.7341|2.47%|
|migraphx_torchvision__resnet50i1|PASS|progression|108.5884|95.1413|-13.4471|-12.38%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1562.519|1566.1675|3.6485|0.23%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5282.9595|5536.4836|253.5241|4.8%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9539.9874|9369.0186|-170.9689|-1.79%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|156.2913|166.3969|10.1056|6.47%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|249.7457|250.8646|1.1189|0.45%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|360.4929|981.9205|621.4276|172.38%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|254.5535|238.918|-15.6355|-6.14%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|432.4958|450.933|18.4372|4.26%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|705.304|743.8104|38.5064|5.46%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5284.4378|5116.6389|-167.7989|-3.18%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|13773.9109|14547.8806|773.9697|5.62%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23437.9476|23260.4946|-177.453|-0.76%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|407.7218|410.9909|3.2692|0.8%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|787.0043|786.4426|-0.5617|-0.07%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1237.453|1235.3509|-2.1021|-0.17%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|814.0468|1097.1546|283.1078|34.78%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1805.6959|2006.0394|200.3435|11.1%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3508.9997|3473.5012|-35.4985|-1.01%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|funnelbase_Opset16_transformers|compiled_inference|compilation|
|funnelbase_Opset18_transformers|compiled_inference|compilation|

## No Progressions Found

