# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|116.9488|118.164|1.2152|1.04%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.4265|118.0517|1.6253|1.4%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|523.5961|521.1485|-2.4476|-0.47%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.056|69.2524|0.1964|0.28%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.5657|65.5286|0.963|1.49%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|311.7629|312.7072|0.9443|0.3%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3731|35.4559|1.0828|3.15%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.149|19.2083|0.0593|0.31%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7093|3.8638|0.1545|4.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.2942|27.3234|0.0291|0.11%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.3762|4.4315|0.0553|1.26%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0808|7.1956|0.1148|1.62%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|27.5374|27.1824|-0.355|-1.29%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9369|14.0061|0.0693|0.5%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.4696|41.3654|-0.1042|-0.25%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|127.6573|127.3733|-0.2839|-0.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|17.7116|16.7765|-0.935|-5.28%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|7.4147|9.1116|1.6969|22.89%|
|migraphx_torchvision__densenet121i32|PASS|progression|18.7022|17.7357|-0.9665|-5.17%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3707|4.377|0.0063|0.14%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.1342|3.1678|0.0336|1.07%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.7185|27.871|0.1526|0.55%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|40.1552|40.2859|0.1307|0.33%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.4305|59.6903|0.2598|0.44%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.3773|12.2092|-0.1681|-1.36%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4896|12.7598|0.2702|2.16%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2763|19.2211|-0.0552|-0.29%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5519|12.5461|-0.0058|-0.05%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1945|19.3198|0.1254|0.65%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.2906|20.4375|0.147|0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|38.7978|38.7244|-0.0733|-0.19%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|75.3823|75.5382|0.1559|0.21%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|115.9362|118.5757|2.6394|2.28%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4212|19.656|0.2348|1.21%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.7206|20.8801|0.1596|0.77%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.4156|24.6799|0.2642|1.08%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7933|20.9453|0.152|0.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.2393|28.4677|0.2284|0.81%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.5289|35.8507|0.3219|0.91%|

## 3 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|eca_nfnet_l2.ra3_in1k_train_vaiq|PASS|compiled_inference|
|ecaresnet26t_Opset16_timm|PASS|compiled_inference|
|ecaresnetlight_vaiq|PASS|compiled_inference|

## 4 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|dla169_Opset16_timm|Numerics|PASS|
|eca_resnext26ts_Opset17_timm|compiled_inference|PASS|
|ecaresnet26t_train_vaiq|compiled_inference|PASS|
|ecaresnetlight_Opset17_timm|compiled_inference|PASS|

