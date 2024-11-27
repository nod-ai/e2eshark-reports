# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.7866|113.4505|-2.3361|-2.02%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.511|115.8076|0.2967|0.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|367.1795|367.2797|0.1002|0.03%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.4789|65.742|-1.7369|-2.57%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|73.046|72.1779|-0.8681|-1.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|280.7157|274.0233|-6.6924|-2.38%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|40.1179|38.0886|-2.0294|-5.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.2882|20.1868|-0.1014|-0.5%|
|migraphx_bert__bertsquad-12|PASS|progression|19.9453|18.5731|-1.3722|-6.88%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.7787|152.737|-2.0418|-1.32%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.6744|215.1557|-3.5187|-1.61%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6705|7.4966|-0.1739|-2.27%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|42.244|42.7258|0.4818|1.14%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4804|6.4589|-0.0215|-0.33%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.597|32.2124|0.6153|1.95%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.8001|52.3541|-1.446|-2.69%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|22.5018|22.3021|-0.1996|-0.89%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|14.5305|11.4327|-3.0977|-21.32%|
|migraphx_torchvision__densenet121i32|PASS|within tol|52.979|52.161|-0.8181|-1.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.8049|15.9308|0.1259|0.8%|
|migraphx_torchvision__inceptioni32|PASS|within tol|145.0286|142.9626|-2.066|-1.42%|
|migraphx_torchvision__resnet50i64|PASS|within tol|193.4539|189.1703|-4.2836|-2.21%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|34.8008|33.5641|-1.2367|-3.55%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|59.9959|57.9224|-2.0735|-3.46%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.7114|73.2657|-2.4457|-3.23%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5362|13.5814|0.0452|0.33%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8081|13.9669|0.1589|1.15%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.5433|20.0116|-0.5317|-2.59%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4455|13.4069|-0.0387|-0.29%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0014|14.087|0.0855|0.61%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.841|21.6295|-0.2114|-0.97%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|71.7177|69.3779|-2.3398|-3.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|108.3648|104.7366|-3.6282|-3.35%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|150.5962|145.179|-5.4172|-3.6%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.1327|15.0168|-0.1159|-0.77%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.9494|17.4877|-0.4616|-2.57%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.3125|26.6726|-0.6399|-2.34%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.4319|20.1061|-0.3258|-1.59%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.9695|28.0543|-0.9152|-3.16%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.6547|41.3811|-1.2735|-2.99%|

## No Regressions Found

## No Progressions Found

