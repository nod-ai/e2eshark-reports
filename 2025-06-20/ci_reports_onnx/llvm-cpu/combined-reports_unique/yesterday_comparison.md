# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|371.3214|369.0236|-2.2978|-0.62%|
|migraphx_cadene__dpn92i1|PASS|within tol|167.8402|167.8276|-0.0126|-0.01%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5453.0631|5619.9272|166.8641|3.06%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|722.094|335.7868|-386.3072|-53.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|417.2545|405.9851|-11.2694|-2.7%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1675.6333|431.3931|-1244.2402|-74.25%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|88.2458|88.0515|-0.1943|-0.22%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|692.6173|58.3984|-634.2189|-91.57%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|208.7236|206.6203|-2.1033|-1.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|58.3369|58.6645|0.3276|0.56%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|21.1152|19.2304|-1.8848|-8.93%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1551.5736|1587.7453|36.1717|2.33%|
|migraphx_torchvision__inceptioni1|PASS|within tol|192.8226|192.0389|-0.7838|-0.41%|
|migraphx_torchvision__resnet50i1|PASS|progression|223.4266|108.5884|-114.8382|-51.4%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1582.6381|1562.519|-20.1191|-1.27%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5379.1757|5282.9595|-96.2162|-1.79%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9486.6968|9539.9874|53.2906|0.56%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|174.9104|156.2913|-18.6192|-10.64%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|253.2205|249.7457|-3.4748|-1.37%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|360.7352|360.4929|-0.2423|-0.07%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|242.4176|254.5535|12.1359|5.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|435.0648|432.4958|-2.569|-0.59%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|658.6959|705.304|46.6082|7.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5043.6197|5284.4378|240.8181|4.77%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13684.4477|13773.9109|89.4632|0.65%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23760.9372|23437.9476|-322.9896|-1.36%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|462.7992|407.7218|-55.0775|-11.9%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|852.7863|787.0043|-65.782|-7.71%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1230.6171|1237.453|6.8359|0.56%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|754.9295|814.0468|59.1173|7.83%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|1633.5767|1805.6959|172.1193|10.54%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3496.2265|3508.9997|12.7732|0.37%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224_dist_Opset16_timm|Numerics|PASS|

