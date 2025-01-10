# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|89.2295|85.9456|-3.284|-3.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|98.3397|97.0544|-1.2853|-1.31%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|259.7945|270.9263|11.1318|4.28%|
|migraphx_ORT__distilgpt2_1|PASS|regression|29.8135|59.2108|29.3973|98.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|82.8627|89.4806|6.6179|7.99%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|245.3862|249.5805|4.1943|1.71%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.0587|40.4033|1.3446|3.44%|
|migraphx_bert__bert-large-uncased|PASS|within tol|364.493|381.0775|16.5844|4.55%|
|migraphx_cadene__dpn92i1|PASS|within tol|173.1535|173.6667|0.5132|0.3%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5285.5908|5387.7944|102.2036|1.93%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|322.6422|329.2138|6.5716|2.04%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5144.3895|5113.4299|-30.9596|-0.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|383.7371|384.2948|0.5578|0.15%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|569.0706|414.8411|-154.2296|-27.1%|
|migraphx_mlperf__resnet50_v1|PASS|regression|92.476|240.6212|148.1452|160.2%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.1893|31.9399|-0.2494|-0.77%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|262.7091|179.6602|-83.0489|-31.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|90.5278|90.0542|-0.4736|-0.52%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|39.2124|38.6503|-0.5621|-1.43%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1567.794|1591.5437|23.7497|1.51%|
|migraphx_torchvision__inceptioni1|PASS|within tol|203.2103|197.0866|-6.1236|-3.01%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5440.8761|5450.2628|9.3867|0.17%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.7748|85.4098|-4.3649|-4.86%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5083.7553|5057.7288|-26.0265|-0.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2583.8162|2611.5247|27.7086|1.07%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4123.9601|4111.281|-12.6791|-0.31%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5828.4847|5769.4345|-59.0502|-1.01%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|176.3384|204.3055|27.9671|15.86%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|291.1248|278.5797|-12.5451|-4.31%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|379.3044|410.3937|31.0892|8.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|390.1188|384.0331|-6.0858|-1.56%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|621.3708|616.8695|-4.5012|-0.72%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|825.3827|807.7745|-17.6082|-2.13%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5072.1411|5075.0984|2.9573|0.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8157.8015|8074.1199|-83.6817|-1.03%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11496.3136|11490.3701|-5.9435|-0.05%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|707.6997|724.7409|17.0412|2.41%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|1094.9115|1252.6096|157.6981|14.4%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1507.2989|1585.8681|78.5692|5.21%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1303.9638|1303.237|-0.7268|-0.06%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2266.7382|2099.2877|-167.4506|-7.39%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2886.8728|2939.6702|52.7974|1.83%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p8_384_dist|Numerics|PASS|

