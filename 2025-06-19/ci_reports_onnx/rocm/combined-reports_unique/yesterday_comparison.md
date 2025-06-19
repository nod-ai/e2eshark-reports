# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.7078|122.4784|-0.2294|-0.19%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|122.707|123.009|0.3021|0.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|537.9138|538.0441|0.1303|0.02%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5242|69.0526|-0.4716|-0.68%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.9194|66.1074|-0.812|-1.21%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.4138|341.8764|1.4626|0.43%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6604|34.7295|0.0691|0.2%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4601|19.3713|-0.0888|-0.46%|
|migraphx_cadene__dpn92i1|Numerics|within tol|3.7479|3.7521|0.0041|0.11%|
|migraphx_cadene__inceptionv4i16|Numerics|within tol|19.4382|19.6837|0.2455|1.26%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|4.3796|4.4283|0.0487|1.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9811|7.0009|0.0198|0.28%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|25.6547|27.4835|1.8289|7.13%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9445|13.9068|-0.0377|-0.27%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|45.4666|42.4763|-2.9903|-6.58%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|104.4249|110.5715|6.1467|5.89%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.0206|16.6471|-1.3734|-7.62%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.45|9.2801|1.83|24.56%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|12.8064|12.8366|0.0302|0.24%|
|migraphx_torchvision__inceptioni1|Numerics|within tol|3.2962|3.3034|0.0073|0.22%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|2.261|2.2422|-0.0188|-0.83%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.612|27.5501|-0.0619|-0.22%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|39.247|39.1055|-0.1415|-0.36%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.9456|56.5943|-0.3513|-0.62%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4885|12.4486|-0.0399|-0.32%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.5291|12.5206|-0.0085|-0.07%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3283|19.3457|0.0174|0.09%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.687|12.917|0.23|1.81%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.5606|19.4865|-0.074|-0.38%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2597|20.2543|-0.0054|-0.03%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.1149|37.8903|-0.2246|-0.59%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|72.4381|72.5925|0.1543|0.21%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|111.5266|112.4011|0.8746|0.78%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.5718|19.5419|-0.0299|-0.15%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9487|20.8988|-0.0499|-0.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.5261|24.3464|-0.1797|-0.73%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|21.0109|21.0114|0.0005|0.0%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0409|28.0034|-0.0375|-0.13%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|34.7634|34.6307|-0.1327|-0.38%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|dm_nfnet_f0_Opset16_timm|Numerics|compilation|
|dm_nfnet_f1_Opset16_timm|Numerics|compilation|
|dm_nfnet_f2.dm_in1k|Numerics|compilation|
|dm_nfnet_f3.dm_in1k|Numerics|compilation|
|dm_nfnet_f3_Opset16_timm|Numerics|compilation|
|dm_nfnet_f4.dm_in1k|PASS|compilation|
|dm_nfnet_f4_Opset16_timm|Numerics|compilation|
|dm_nfnet_f4_Opset17_timm|Numerics|compilation|
|model--IMDB_ELECTRA_5E--pig4431|PASS|compilation|
|model--outputs--ankitkupadhyay|PASS|compilation|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|PASS|compilation|

## No Progressions Found

