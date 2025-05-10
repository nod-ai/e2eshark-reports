# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|118.8286|117.4571|-1.3714|-1.15%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.7428|120.4054|2.6627|2.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|523.3926|522.3589|-1.0337|-0.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.5853|69.4968|0.9115|1.33%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.0668|63.9709|-0.0959|-0.15%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|313.2382|312.2709|-0.9673|-0.31%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.6765|35.3302|0.6536|1.88%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.0963|19.121|0.0247|0.13%|
|migraphx_cadene__dpn92i1|PASS|progression|4.0646|3.8427|-0.2219|-5.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.4074|27.2789|-0.1285|-0.47%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.6805|4.4739|-0.2066|-4.41%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.127|7.226|0.099|1.39%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|26.7476|27.2355|0.4879|1.82%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1373|14.5219|0.3847|2.72%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.3104|41.4329|0.1225|0.3%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|129.1007|130.8485|1.7478|1.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.0224|18.9983|-1.0242|-5.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.0913|8.9371|-1.1542|-11.44%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.6917|17.7784|0.0868|0.49%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.4016|4.3686|-0.033|-0.75%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1586|3.188|0.0294|0.93%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.8527|27.8643|0.0116|0.04%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|40.2074|40.2954|0.088|0.22%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4767|59.5217|0.045|0.08%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2905|12.1946|-0.0959|-0.78%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4083|12.4124|0.0042|0.03%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2152|19.4083|0.1932|1.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.478|12.4762|-0.0019|-0.01%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3495|19.2966|-0.0529|-0.27%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.3468|20.3794|0.0326|0.16%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.7524|38.7957|0.0433|0.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|75.7216|75.7641|0.0425|0.06%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.7217|118.8101|0.0884|0.07%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4971|19.4848|-0.0123|-0.06%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8086|21.0167|0.2081|1.0%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.6559|24.5998|-0.0562|-0.23%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9098|20.979|0.0692|0.33%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.72|28.5539|-0.1661|-0.58%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.5764|35.7911|0.2146|0.6%|

## 4 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|ecaresnet26t_Opset16_timm|PASS|compiled_inference|
|ecaresnet50d_vaiq|Numerics|compiled_inference|
|ecaresnetlight_Opset17_timm|PASS|compiled_inference|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l0.ra2_in1k_vaiq|compiled_inference|PASS|
|ecaresnet26t_train_vaiq|compiled_inference|PASS|
|ecaresnet50t_Opset16_timm|compiled_inference|PASS|
|ecaresnetlight_vaiq|compiled_inference|PASS|

