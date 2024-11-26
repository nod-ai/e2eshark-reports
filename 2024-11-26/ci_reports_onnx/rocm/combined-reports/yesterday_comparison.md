# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|112.4365|115.7866|3.35|2.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|114.1116|115.511|1.3994|1.23%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|374.3539|367.1795|-7.1745|-1.92%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|64.9629|67.4789|2.516|3.87%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.6941|73.046|0.3519|0.48%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.5186|280.7157|6.1971|2.26%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.7536|40.1179|0.3643|0.92%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0863|20.2882|0.2019|1.01%|
|migraphx_bert__bertsquad-12|PASS|within tol|19.1515|19.9453|0.7938|4.14%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.9507|154.7787|-0.172|-0.11%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|214.9402|218.6744|3.7342|1.74%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.546|7.6705|0.1245|1.65%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|40.1321|42.244|2.1119|5.26%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5144|6.4804|-0.034|-0.52%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.4939|31.597|-0.8969|-2.76%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.1286|53.8001|-0.3285|-0.61%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|20.8713|22.5018|1.6305|7.81%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|14.0204|14.5305|0.51|3.64%|
|migraphx_torchvision__densenet121i32|PASS|within tol|52.5444|52.979|0.4346|0.83%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9167|15.8049|-0.1119|-0.7%|
|migraphx_torchvision__inceptioni32|PASS|within tol|143.9934|145.0286|1.0352|0.72%|
|migraphx_torchvision__resnet50i64|PASS|within tol|190.5342|193.4539|2.9197|1.53%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4362|34.8008|1.3646|4.08%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.6508|59.9959|2.345|4.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.4186|75.7114|2.2927|3.12%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.5226|13.5362|0.0136|0.1%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.7683|13.8081|0.0397|0.29%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.0435|20.5433|0.4998|2.49%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.5409|13.4455|-0.0954|-0.7%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9644|14.0014|0.0371|0.27%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7394|21.841|0.1016|0.47%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.1521|71.7177|2.5656|3.71%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.615|108.3648|3.7498|3.58%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.1162|150.5962|5.48|3.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0439|15.1327|0.0888|0.59%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6037|17.9494|0.3456|1.96%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5681|27.3125|0.7443|2.8%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9192|20.4319|0.5128|2.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.9167|28.9695|1.0528|3.77%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.2982|42.6547|1.3565|3.28%|

## No Regressions Found

## No Progressions Found

