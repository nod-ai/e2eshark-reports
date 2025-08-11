# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.091|120.5838|3.4928|2.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.7455|118.0341|1.2886|1.1%|
|migraphx_ORT__distilgpt2_1|PASS|progression|111.727|71.7639|-39.9631|-35.77%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|75.1331|74.7921|-0.341|-0.45%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|302.3383|301.0006|-1.3377|-0.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|44.5961|45.8405|1.2444|2.79%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2617|19.1133|-0.1485|-0.77%|
|migraphx_cadene__dpn92i1|PASS|progression|14.5568|13.2159|-1.3409|-9.21%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.1408|22.0435|-0.0973|-0.44%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.7955|6.6869|-0.1086|-1.6%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.4157|7.2429|-0.1727|-2.33%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|33.0427|42.2437|9.201|27.85%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.8084|15.0864|0.278|1.88%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|44.4225|54.3824|9.9598|22.42%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|109.7881|131.3295|21.5413|19.62%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|18.7437|17.7065|-1.0373|-5.53%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.3426|11.5143|2.1716|23.24%|
|migraphx_torchvision__densenet121i32|PASS|regression|14.8871|17.3822|2.4951|16.76%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.2377|4.0686|-0.1691|-3.99%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1435|2.1765|0.0331|1.54%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7016|25.7527|0.0511|0.2%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|36.7454|37.9376|1.1922|3.24%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|55.685|56.2298|0.5448|0.98%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6934|12.5943|-0.0991|-0.78%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6489|12.9015|0.2526|2.0%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3882|19.2193|-0.1689|-0.87%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.0265|13.3663|0.3398|2.61%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3478|19.2596|-0.0882|-0.46%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8854|19.6128|-0.2726|-1.37%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.4974|36.05|0.5525|1.56%|
|migx_bench_bert-large-uncased_32_256|Numerics|within tol|69.1398|69.3559|0.2161|0.31%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.1943|109.8054|0.6111|0.56%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.7733|19.6112|-0.162|-0.82%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0461|20.1132|0.0672|0.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3545|23.2379|-0.1167|-0.5%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1379|20.4409|0.303|1.5%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2543|26.3262|0.0719|0.27%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.3774|32.4624|0.0849|0.26%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|deberta_Opset17_transformers|PASS|Numerics|
|migx_bench_bert-large-uncased_32_256|PASS|Numerics|
|migx_bench_bert-large-uncased_32_384|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--deberta-v3-xsmall-squad2--nlpconnect|Numerics|PASS|
|model--microsoft_deberta-large_squad--Palak|compiled_inference|PASS|
|resnet10t_train_vaiq|Numerics|PASS|
|resnet14t_train_vaiq|Numerics|PASS|

