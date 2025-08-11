# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|200.843|213.6779|12.8349|6.39%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|250.2817|196.1269|-54.1548|-21.64%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|623.7096|572.7957|-50.9139|-8.16%|
|migraphx_ORT__distilgpt2_1|PASS|regression|80.2443|239.7029|159.4586|198.72%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|190.0751|200.1743|10.0992|5.31%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|638.8274|550.9199|-87.9075|-13.76%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|162.5123|221.2471|58.7348|36.14%|
|migraphx_bert__bert-large-uncased|PASS|progression|392.2565|371.0104|-21.2461|-5.42%|
|migraphx_cadene__dpn92i1|PASS|progression|175.5888|166.2851|-9.3037|-5.3%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5446.2811|5362.6961|-83.585|-1.53%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|315.1416|414.4043|99.2627|31.5%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|454.1197|429.5539|-24.5658|-5.41%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|524.75|553.7102|28.9603|5.52%|
|migraphx_mlperf__resnet50_v1|PASS|progression|106.0373|94.0971|-11.9402|-11.26%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|74.5283|61.9992|-12.5291|-16.81%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|238.1319|215.2577|-22.8742|-9.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|64.3436|65.2687|0.9251|1.44%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.7677|20.3384|1.5706|8.37%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1594.9815|1526.7909|-68.1906|-4.28%|
|migraphx_torchvision__inceptioni1|PASS|progression|226.7697|199.815|-26.9547|-11.89%|
|migraphx_torchvision__resnet50i1|PASS|progression|94.1006|89.247|-4.8536|-5.16%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1696.1598|1624.8027|-71.357|-4.21%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|6140.1864|5128.716|-1011.4704|-16.47%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9781.1656|9490.8917|-290.2739|-2.97%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|146.1726|151.1458|4.9731|3.4%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|256.3406|256.1062|-0.2344|-0.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|367.3203|365.0859|-2.2343|-0.61%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|238.051|235.932|-2.119|-0.89%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|624.2998|434.9777|-189.3221|-30.33%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|756.0361|663.0911|-92.9449|-12.29%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5073.3825|4977.7319|-95.6506|-1.89%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|14547.4859|13595.9152|-951.5707|-6.54%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23356.479|23056.4089|-300.0701|-1.28%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|460.7043|400.4978|-60.2065|-13.07%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|874.8393|786.2066|-88.6327|-10.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1234.3864|1230.9645|-3.4219|-0.28%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|789.3919|742.0845|-47.3074|-5.99%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|1721.2937|1629.8401|-91.4536|-5.31%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3640.0676|3333.4638|-306.6038|-8.42%|

## No Regressions Found

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|resnet10t_train_vaiq|Numerics|PASS|
|resnet14t_train_vaiq|Numerics|PASS|

