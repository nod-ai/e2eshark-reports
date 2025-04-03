# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|115.935|116.4302|0.4952|0.43%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.7581|116.4059|0.6478|0.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|527.3701|536.526|9.1559|1.74%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.2807|68.6462|-0.6345|-0.92%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.0759|62.4202|0.3443|0.55%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|327.1802|327.5003|0.3201|0.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6285|34.2439|-0.3846|-1.11%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4133|19.286|-0.1273|-0.66%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0758|5.0496|-0.0262|-0.52%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.7649|29.5179|-0.247|-0.83%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.1173|5.9782|-0.1391|-2.27%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9303|6.9463|0.016|0.23%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.2923|26.9549|-1.3374|-4.73%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.79|5.1002|0.3102|6.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|40.7306|39.959|-0.7716|-1.89%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|47.1873|46.6465|-0.5408|-1.15%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.4965|19.7042|-0.7924|-3.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.7972|10.041|0.2438|2.49%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1178|17.8619|-0.256|-1.41%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8971|4.8596|-0.0375|-0.76%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1576|3.1687|0.0111|0.35%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.8659|26.8748|0.009|0.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|38.5459|38.2302|-0.3157|-0.82%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|58.1266|57.9847|-0.1419|-0.24%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0014|11.9992|-0.0022|-0.02%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6508|12.5572|-0.0936|-0.74%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5943|19.3772|-0.2171|-1.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.7118|12.8171|0.1053|0.83%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5426|19.4665|-0.0761|-0.39%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.305|20.2343|-0.0707|-0.35%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.9061|36.6036|-0.3025|-0.82%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|77.7051|77.1844|-0.5208|-0.67%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|119.0591|118.0293|-1.0298|-0.86%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4979|19.7055|0.2076|1.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8429|20.8|-0.0429|-0.21%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.0717|24.2808|0.2091|0.87%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8784|21.0779|0.1995|0.96%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.5248|27.5046|-0.0201|-0.07%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.0575|34.7102|-0.3472|-0.99%|

## No Regressions Found

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|switchtransformersencoder_Opset16_transformers|compilation|PASS|

