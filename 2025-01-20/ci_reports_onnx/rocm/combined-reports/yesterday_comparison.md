# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.1599|106.5441|-0.6158|-0.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.7762|106.0439|-0.7323|-0.69%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|472.1002|471.1258|-0.9744|-0.21%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.2858|62.1848|0.8989|1.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.7885|64.9281|0.1396|0.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.4453|272.7044|0.259|0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.2578|32.2797|0.0219|0.07%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.38|19.2781|-0.1019|-0.53%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.4705|64.6403|0.1698|0.26%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.2934|149.1888|-0.1046|-0.07%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|173.418|173.4822|0.0642|0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0392|7.1178|0.0786|1.12%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.8535|24.7278|-0.1257|-0.51%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.3836|42.3853|0.0017|0.0%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.5567|144.5909|2.0343|1.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.291|16.4928|-0.7982|-4.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|6.7988|6.3158|-0.483|-7.1%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|64.8904|65.0722|0.1818|0.28%|
|migraphx_torchvision__inceptioni1|PASS|within tol|61.212|61.1318|-0.0802|-0.13%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.986|101.013|0.0269|0.03%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|15.8955|15.8742|-0.0213|-0.13%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|145.4885|145.5165|0.028|0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.6538|32.5947|-0.0591|-0.18%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|54.9235|54.9789|0.0554|0.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.996|74.0297|0.0337|0.05%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|11.9303|11.9638|0.0335|0.28%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5681|12.5397|-0.0284|-0.23%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5376|19.5174|-0.0203|-0.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7675|12.6854|-0.082|-0.64%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2494|13.2321|-0.0172|-0.13%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.2021|21.1251|-0.0769|-0.36%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|67.3805|67.4258|0.0453|0.07%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|101.6408|101.7351|0.0942|0.09%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|149.9855|150.4086|0.4231|0.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.3724|14.3754|0.003|0.02%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.7087|16.6697|-0.039|-0.23%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.0894|26.1382|0.0488|0.19%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.0635|19.1542|0.0908|0.48%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.2436|27.2435|-0.0002|-0.0%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.6415|40.6187|-0.0228|-0.06%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_cadene__resnext101_64x4di16|compilation|Numerics|

