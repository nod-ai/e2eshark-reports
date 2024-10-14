# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|801.5506|848.6356|47.0851|5.87%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|1023.3911|907.5498|-115.8413|-11.32%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|2744.8385|2703.1014|-41.737|-1.52%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|2436.3986|2623.2514|186.8527|7.67%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|7094.7893|6725.1431|-369.6463|-5.21%|
|migraphx_cadene__dpn92i1|PASS|regression|463.8861|508.9578|45.0717|9.72%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|28024.6677|28015.9151|-8.7526|-0.03%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|1009.7442|1027.5864|17.8422|1.77%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|6385.4546|6306.1144|-79.3402|-1.24%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|5784.2009|5868.6829|84.482|1.46%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|8237.9007|8539.8057|301.905|3.66%|
|migraphx_mlperf__resnet50_v1|PASS|regression|163.9665|179.8707|15.9042|9.7%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|263.8879|265.641|1.7531|0.66%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.414|65.1886|-7.2254|-9.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|26.8739|27.1123|0.2384|0.89%|
|migraphx_torchvision__inceptioni1|PASS|within tol|614.4001|630.5066|16.1066|2.62%|
|migraphx_torchvision__inceptioni32|PASS|within tol|23101.6265|22945.9844|-155.6421|-0.67%|
|migraphx_torchvision__resnet50i1|PASS|within tol|259.6859|263.2651|3.5791|1.38%|
|migraphx_torchvision__resnet50i64|PASS|within tol|10339.7821|10363.6058|23.8237|0.23%|

## No Regressions Found

## No Progressions Found

