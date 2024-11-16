# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.7512|113.6321|-1.1191|-0.98%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|115.5932|115.4024|-0.1908|-0.17%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|368.5736|369.7539|1.1802|0.32%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|65.1017|65.0588|-0.0429|-0.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0226|72.189|0.1664|0.23%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.1728|273.1691|-0.0037|-0.0%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.4685|38.7452|-0.7234|-1.83%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0508|19.9879|-0.0629|-0.31%|
|migraphx_bert__bertsquad-12|PASS|progression|212.4848|16.3874|-196.0975|-92.29%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.4418|151.5275|0.0856|0.06%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|211.9861|212.236|0.25|0.12%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.6124|7.3876|-0.2248|-2.95%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|44.7897|47.6406|2.8509|6.37%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4801|6.4993|0.0191|0.3%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|30.9695|31.7993|0.8299|2.68%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.4298|52.7124|0.2826|0.54%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|27.8889|25.2003|-2.6886|-9.64%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.8048|17.8757|-1.9291|-9.74%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.6606|50.4907|-0.1699|-0.34%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.7534|15.9126|0.1592|1.01%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.3149|137.7125|0.3976|0.29%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.3225|182.5114|0.1889|0.1%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.2674|33.2328|-0.0345|-0.1%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.2588|57.0345|-0.2243|-0.39%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.79|72.8392|0.0492|0.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.595|13.5791|-0.016|-0.12%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8495|13.8321|-0.0174|-0.13%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9148|19.9313|0.0165|0.08%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4018|13.4495|0.0476|0.36%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0261|14.0749|0.0488|0.35%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.5967|21.5645|-0.0322|-0.15%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3185|68.5661|0.2476|0.36%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|103.6201|103.7807|0.1606|0.15%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.1594|144.1869|0.0276|0.02%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0752|15.0945|0.0194|0.13%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.2922|17.2496|-0.0426|-0.25%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.4441|26.4737|0.0296|0.11%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|23.9578|19.9489|-4.0089|-16.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.8519|27.7437|-0.1082|-0.39%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.1818|40.932|-0.2497|-0.61%|

## No Regressions Found

## No Progressions Found

