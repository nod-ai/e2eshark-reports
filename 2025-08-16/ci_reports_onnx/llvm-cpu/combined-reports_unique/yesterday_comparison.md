# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|240.1801|199.3828|-40.7974|-16.99%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|219.0372|255.8258|36.7886|16.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|580.8529|559.9071|-20.9458|-3.61%|
|migraphx_ORT__distilgpt2_1|PASS|progression|83.638|78.8293|-4.8087|-5.75%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|191.1271|190.1802|-0.9469|-0.5%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|569.5953|562.3008|-7.2946|-1.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|97.8883|89.5032|-8.385|-8.57%|
|migraphx_bert__bert-large-uncased|PASS|progression|430.9085|390.0207|-40.8878|-9.49%|
|migraphx_cadene__dpn92i1|PASS|progression|195.1568|162.1745|-32.9824|-16.9%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5266.7451|5272.4905|5.7454|0.11%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|315.471|314.8381|-0.6329|-0.2%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|445.8872|419.4389|-26.4483|-5.93%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|461.0009|464.6266|3.6257|0.79%|
|migraphx_mlperf__resnet50_v1|PASS|progression|96.7462|90.9608|-5.7854|-5.98%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|61.495|60.7253|-0.7697|-1.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|211.9341|217.7961|5.862|2.77%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|63.9466|67.597|3.6504|5.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.4973|19.9948|1.4975|8.1%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1838.5566|1843.9467|5.3902|0.29%|
|migraphx_torchvision__inceptioni1|PASS|progression|231.8094|211.0302|-20.7793|-8.96%|
|migraphx_torchvision__resnet50i1|PASS|progression|89.3973|83.5885|-5.8088|-6.5%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1619.5524|1549.7917|-69.7606|-4.31%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|5297.6545|5496.0857|198.4312|3.75%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9346.4852|9685.4668|338.9816|3.63%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|159.9403|148.5567|-11.3836|-7.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|258.501|251.761|-6.7399|-2.61%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|439.0793|375.3021|-63.7772|-14.53%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|247.1337|254.6401|7.5063|3.04%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|1490.6581|424.7899|-1065.8683|-71.5%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|1491.2589|700.0338|-791.2251|-53.06%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5256.1444|5174.2841|-81.8603|-1.56%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14146.1742|13991.0246|-155.1496|-1.1%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23850.5907|23589.5871|-261.0036|-1.09%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|430.4147|412.9816|-17.4331|-4.05%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|800.456|978.6402|178.1841|22.26%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1242.8608|1274.7459|31.8852|2.57%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|2780.5502|734.7914|-2045.7588|-73.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1622.6425|1679.8566|57.2141|3.53%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3577.274|3421.1805|-156.0935|-4.36%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|bat_resnext26ts_Opset17_timm|PASS|compilation|
|model--microsoft_deberta-base_squad--Palak|PASS|compilation|
|model--microsoft_deberta-large_squad--Palak|PASS|compilation|

## 22 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|regnetz_d8_evos_Opset16_timm|compilation|Numerics|
|resnetv2_50d_evos.ah_in1k_train_vaiq|compilation|PASS|
|resnetv2_50d_evos.ah_in1k_vaiq|compilation|PASS|
|resnetv2_50d_evos_Opset17_timm|compilation|Numerics|
|swinv2_base_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_base_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_base_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_base_window8_256_Opset16_timm|compilation|PASS|
|swinv2_base_window8_256_Opset17_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset16_timm|compilation|PASS|
|swinv2_large_window12_192_22k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to16_192to256_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset16_timm|compilation|PASS|
|swinv2_large_window12to24_192to384_22kft1k_Opset17_timm|compilation|PASS|
|swinv2_small_window16_256_Opset16_timm|compilation|PASS|
|swinv2_small_window16_256_Opset17_timm|compilation|PASS|
|swinv2_small_window8_256_Opset17_timm|compilation|PASS|
|swinv2_tiny_window8_256_Opset16_timm|compilation|PASS|

