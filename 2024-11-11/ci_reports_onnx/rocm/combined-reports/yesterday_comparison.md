# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|111.9343|112.9551|1.0208|0.91%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|110.8113|111.3498|0.5385|0.49%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|360.5406|363.4032|2.8626|0.79%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.3184|61.2856|-0.0328|-0.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0945|72.0951|0.0007|0.0%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|273.0165|274.6928|1.6763|0.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.9475|36.6795|-0.2681|-0.73%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.9268|19.8902|-0.0366|-0.18%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|151.2295|152.1375|0.9081|0.6%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.0442|218.3367|0.2925|0.13%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3701|7.4159|0.0459|0.62%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|40.7443|41.7955|1.0512|2.58%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4262|6.4571|0.0309|0.48%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|28.8711|28.4421|-0.429|-1.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|54.4802|54.4365|-0.0437|-0.08%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.9347|20.4472|0.5124|2.57%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|13.151|12.8548|-0.2962|-2.25%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.4203|50.7075|0.2872|0.57%|
|migraphx_torchvision__inceptioni1|PASS|regression|15.7987|19.5709|3.7722|23.88%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.4956|138.2104|0.7148|0.52%|
|migraphx_torchvision__resnet50i64|PASS|within tol|181.9723|183.0042|1.0319|0.57%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.9673|33.5837|0.6164|1.87%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|56.9445|57.8712|0.9267|1.63%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|72.8465|73.3965|0.55|0.76%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4681|13.47|0.0019|0.01%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8717|13.661|-0.2107|-1.52%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.9133|19.9343|0.021|0.11%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.2796|13.2574|-0.0222|-0.17%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|14.0023|13.9458|-0.0564|-0.4%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.4947|21.5473|0.0526|0.24%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|68.3715|69.6231|1.2516|1.83%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|136.3935|104.9811|-31.4124|-23.03%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|144.0269|145.812|1.7851|1.24%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|15.0634|14.9849|-0.0785|-0.52%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|17.2758|18.4598|1.1839|6.85%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.472|26.6111|0.1392|0.53%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.9966|20.8685|0.8719|4.36%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.6692|28.8795|1.2102|4.37%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|40.9502|41.3074|0.3572|0.87%|

## No Regressions Found

## No Progressions Found

