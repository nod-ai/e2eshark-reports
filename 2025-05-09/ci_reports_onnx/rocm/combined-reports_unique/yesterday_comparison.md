# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|118.164|118.8286|0.6646|0.56%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|118.0517|117.7428|-0.309|-0.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|521.1485|523.3926|2.2441|0.43%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.2524|68.5853|-0.6671|-0.96%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|65.5286|64.0668|-1.4618|-2.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|312.7072|313.2382|0.531|0.17%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.4559|34.6765|-0.7794|-2.2%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2083|19.0963|-0.1121|-0.58%|
|migraphx_cadene__dpn92i1|PASS|regression|3.8638|4.0646|0.2008|5.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.3234|27.4074|0.084|0.31%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.4315|4.6805|0.249|5.62%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1956|7.127|-0.0686|-0.95%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.1824|26.7476|-0.4347|-1.6%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0061|14.1373|0.1311|0.94%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.3654|41.3104|-0.055|-0.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|127.3733|129.1007|1.7273|1.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.7765|20.0224|3.2459|19.35%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.1116|10.0913|0.9797|10.75%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.7357|17.6917|-0.044|-0.25%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.377|4.4016|0.0247|0.56%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1678|3.1586|-0.0092|-0.29%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.871|27.8527|-0.0183|-0.07%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|40.2859|40.2074|-0.0785|-0.19%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.6903|59.4767|-0.2136|-0.36%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2092|12.2905|0.0813|0.67%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7598|12.4083|-0.3515|-2.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2211|19.2152|-0.0059|-0.03%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5461|12.478|-0.0681|-0.54%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3198|19.3495|0.0297|0.15%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.4375|20.3468|-0.0908|-0.44%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.7244|38.7524|0.028|0.07%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|75.5382|75.7216|0.1834|0.24%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|118.5757|118.7217|0.146|0.12%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.656|19.4971|-0.1589|-0.81%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.8801|20.8086|-0.0716|-0.34%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.6799|24.6559|-0.0239|-0.1%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.9453|20.9098|-0.0355|-0.17%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.4677|28.72|0.2524|0.89%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.8507|35.5764|-0.2743|-0.77%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|ecaresnet26t_train_vaiq|PASS|compiled_inference|
|gernet_s_Opset18_timm|PASS|compiled_inference|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ecaresnet26t_Opset16_timm|compiled_inference|PASS|
|ecaresnet50d_vaiq|compiled_inference|Numerics|

