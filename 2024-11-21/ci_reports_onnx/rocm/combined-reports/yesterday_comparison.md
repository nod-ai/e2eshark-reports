# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.8799|115.5421|0.6622|0.58%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|116.851|113.9671|-2.8839|-2.47%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|367.7064|377.3402|9.6338|2.62%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|64.9945|63.7545|-1.2401|-1.91%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.6419|73.5396|0.8977|1.24%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|276.0634|280.8389|4.7755|1.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.5441|40.7787|1.2346|3.12%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.029|20.1548|0.1258|0.63%|
|migraphx_bert__bertsquad-12|PASS|progression|19.6251|17.7274|-1.8977|-9.67%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.8793|156.3501|3.4709|2.27%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|213.8599|217.7479|3.888|1.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6624|7.6058|-0.0566|-0.74%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|41.549|45.6398|4.0908|9.85%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.5787|6.5646|-0.0141|-0.21%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|33.2349|35.2971|2.0623|6.21%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|53.9223|56.5242|2.6019|4.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|27.1833|29.4979|2.3146|8.51%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|18.2108|18.5703|0.3594|1.97%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.9606|51.8522|0.8915|1.75%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.9105|15.9058|-0.0047|-0.03%|
|migraphx_torchvision__inceptioni32|PASS|within tol|138.8278|142.0941|3.2663|2.35%|
|migraphx_torchvision__resnet50i64|PASS|within tol|183.8847|188.0397|4.155|2.26%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.72|34.9659|1.2458|3.69%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.1637|60.1555|1.9918|3.42%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.6778|76.3353|2.6574|3.61%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.6637|13.6196|-0.0441|-0.32%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.9351|13.8693|-0.0658|-0.47%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|20.001|20.0|-0.001|-0.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.5735|13.4308|-0.1427|-1.05%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.1946|14.0888|-0.1058|-0.75%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.8064|21.9064|0.1|0.46%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.6517|71.853|2.2013|3.16%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|105.0618|108.5958|3.5339|3.36%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.7997|150.9831|5.1835|3.56%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.2031|15.1853|-0.0179|-0.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6341|17.9711|0.3371|1.91%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.8061|27.5486|0.7425|2.77%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.3098|20.6641|0.3544|1.74%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.2334|29.0523|0.8188|2.9%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.5894|42.6821|1.0928|2.63%|

## No Regressions Found

## No Progressions Found

