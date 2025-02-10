# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|109.1029|107.5321|-1.5708|-1.44%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.819|107.7339|1.9149|1.81%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|464.3267|475.3457|11.019|2.37%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|58.5398|59.562|1.0222|1.75%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1556|62.4043|-0.7512|-1.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|269.7114|267.8256|-1.8858|-0.7%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.5117|35.0604|0.5487|1.59%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.8903|19.0429|0.1526|0.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0907|7.1015|0.0108|0.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.3083|26.3315|-0.9768|-3.58%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.6952|5.096|0.4008|8.54%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.4815|43.058|0.5765|1.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|54.4388|46.7836|-7.6552|-14.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.6761|16.9404|0.2643|1.58%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.4081|6.9983|-0.4098|-5.53%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.968|4.9353|-0.0326|-0.66%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.4346|31.6435|-0.7911|-2.44%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.8722|53.3838|-1.4884|-2.71%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.2531|69.6597|-2.5934|-3.59%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1567|12.1295|-0.0272|-0.22%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3579|12.6858|0.3279|2.65%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.6379|19.9745|0.3366|1.71%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.2061|12.9861|-0.22|-1.67%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|14.8956|13.4427|-1.4529|-9.75%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.9223|21.0451|0.1228|0.59%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.4828|65.8082|-1.6746|-2.48%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|356.5066|97.9507|-258.5559|-72.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|142.8674|138.3308|-4.5366|-3.18%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3293|14.4002|0.071|0.5%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2929|16.4905|-0.8024|-4.64%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|25.9509|25.749|-0.2018|-0.78%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|46.9418|18.8465|-28.0953|-59.85%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.1261|26.5272|-0.5989|-2.21%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.245|39.4972|-0.7478|-1.86%|

## No Regressions Found

## No Progressions Found

