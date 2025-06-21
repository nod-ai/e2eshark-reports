# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.0705|122.2309|0.1604|0.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|121.5853|121.618|0.0327|0.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|538.4295|535.4612|-2.9682|-0.55%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.7585|69.5884|0.8299|1.21%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.1425|66.9235|0.7809|1.18%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.0242|340.1038|0.0796|0.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.3301|34.5428|-0.7872|-2.23%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9344|19.0778|0.1434|0.76%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.6304|3.7038|0.0733|2.02%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.3187|19.5252|0.2065|1.07%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3336|4.235|-0.0986|-2.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9463|6.9008|-0.0455|-0.66%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|24.5514|26.0719|1.5205|6.19%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9664|14.0816|0.1152|0.83%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.6175|41.4744|-0.1431|-0.34%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|101.9236|102.9639|1.0404|1.02%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.113|19.6822|1.5692|8.66%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.5709|9.7934|2.2225|29.36%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.9651|12.8978|-0.0673|-0.52%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.379|3.3401|-0.0389|-1.15%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.23|2.261|0.031|1.39%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.0335|26.1|0.0665|0.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.8325|37.6095|-0.2231|-0.59%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.501|55.8336|-0.6673|-1.18%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2055|12.1759|-0.0296|-0.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.3175|12.2869|-0.0305|-0.25%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|18.9042|18.8822|-0.0219|-0.12%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5372|12.5133|-0.024|-0.19%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.881|19.1533|0.2723|1.44%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6427|19.8826|0.2399|1.22%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|37.0789|36.5295|-0.5494|-1.48%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.7216|71.2075|-0.5141|-0.72%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|116.2524|115.776|-0.4765|-0.41%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.1447|19.1076|-0.037|-0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.9044|19.8871|-0.0173|-0.09%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.0896|23.028|-0.0616|-0.27%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0284|20.2776|0.2491|1.24%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.4493|26.4716|0.0223|0.08%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.4774|32.5307|0.0533|0.16%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|funnelbase_Opset16_transformers|compiled_inference|compilation|
|funnelbase_Opset18_transformers|compiled_inference|compilation|

## No Progressions Found

