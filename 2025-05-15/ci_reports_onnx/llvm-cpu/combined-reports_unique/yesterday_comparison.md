# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|regression|370.1676|633.6583|263.4907|71.18%|
|migraphx_cadene__dpn92i1|PASS|progression|190.2556|169.7135|-20.542|-10.8%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6112.274|5881.529|-230.745|-3.78%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|390.6285|317.2236|-73.4049|-18.79%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|404.7428|454.9923|50.2495|12.42%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|493.6413|426.4113|-67.23|-13.62%|
|migraphx_mlperf__resnet50_v1|PASS|progression|251.4819|88.8634|-162.6185|-64.66%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|139.4321|58.0509|-81.3811|-58.37%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|209.782|221.74|11.958|5.7%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|65.4607|64.1671|-1.2937|-1.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|20.9905|21.5577|0.5672|2.7%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1441.9322|1507.0897|65.1574|4.52%|
|migraphx_torchvision__inceptioni1|PASS|within tol|200.2671|198.7018|-1.5653|-0.78%|
|migraphx_torchvision__resnet50i1|PASS|within tol|84.5326|87.2495|2.7169|3.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1556.0618|1550.8173|-5.2445|-0.34%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5515.1038|5438.0108|-77.093|-1.4%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9192.8547|9335.6309|142.7762|1.55%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|159.991|168.5057|8.5147|5.32%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|305.9299|273.8347|-32.0953|-10.49%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|387.9329|374.7438|-13.1891|-3.4%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|254.6088|254.545|-0.0639|-0.03%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.7811|423.0352|-223.7459|-34.59%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|683.6289|659.1023|-24.5266|-3.59%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5150.5937|5191.4271|40.8334|0.79%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13690.4379|13909.2928|218.8549|1.6%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23458.4744|23586.7915|128.3171|0.55%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|408.2493|409.5175|1.2682|0.31%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|821.5203|794.8862|-26.6341|-3.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1238.5871|1221.3464|-17.2406|-1.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|740.5072|755.6724|15.1652|2.05%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1755.4089|1673.0891|-82.3198|-4.69%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3499.608|3673.6635|174.0555|4.97%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_224_dist_Opset16_timm|PASS|Numerics|

## No Progressions Found

