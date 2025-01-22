# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|106.5441|105.9174|-0.6267|-0.59%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.0439|106.4921|0.4482|0.42%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|471.1258|474.2843|3.1585|0.67%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|62.1848|60.0031|-2.1817|-3.51%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.9281|66.9829|2.0548|3.16%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.7044|277.4143|4.7099|1.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.2797|33.3996|1.1199|3.47%|
|migraphx_bert__bert-large-uncased|PASS|regression|19.2781|20.4321|1.154|5.99%|
|migraphx_cadene__dpn92i1|Numerics|regression|64.6403|70.3287|5.6885|8.8%|
|migraphx_cadene__inceptionv4i16|PASS|regression|149.1888|160.7174|11.5286|7.73%|
|migraphx_cadene__resnext101_64x4di1|Numerics|regression|173.4822|197.1996|23.7175|13.67%|
|migraphx_cadene__resnext101_64x4di16|Numerics|regression|386.9976|414.4727|27.4751|7.1%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1178|7.2716|0.1538|2.16%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|24.7278|26.386|1.6582|6.71%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|42.3853|46.5816|4.1963|9.9%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|144.5909|149.7502|5.1592|3.57%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.4928|16.2018|-0.2909|-1.76%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.3158|7.6583|1.3425|21.26%|
|migraphx_torchvision__densenet121i32|Numerics|regression|65.0722|68.6071|3.5349|5.43%|
|migraphx_torchvision__inceptioni1|PASS|regression|61.1318|66.223|5.0912|8.33%|
|migraphx_torchvision__inceptioni32|PASS|regression|101.013|107.8831|6.8701|6.8%|
|migraphx_torchvision__resnet50i1|Numerics|regression|15.8742|17.1116|1.2374|7.79%|
|migraphx_torchvision__resnet50i64|Numerics|regression|145.5165|155.0524|9.5359|6.55%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.5947|32.924|0.3293|1.01%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.9789|55.582|0.603|1.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|74.0297|73.878|-0.1518|-0.2%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|11.9638|12.6496|0.6858|5.73%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.5397|13.2639|0.7242|5.77%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.5174|20.6497|1.1324|5.8%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.6854|13.4893|0.8039|6.34%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.2321|14.0247|0.7925|5.99%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.1251|22.3422|1.2171|5.76%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.4258|68.1899|0.764|1.13%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.7351|101.9411|0.2061|0.2%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.4086|150.3149|-0.0937|-0.06%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.3754|15.1752|0.7998|5.56%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.6697|16.8878|0.2181|1.31%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.1382|27.1601|1.0219|3.91%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1542|19.399|0.2447|1.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.2435|27.4092|0.1657|0.61%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.6187|40.9357|0.3171|0.78%|

## No Regressions Found

## No Progressions Found

