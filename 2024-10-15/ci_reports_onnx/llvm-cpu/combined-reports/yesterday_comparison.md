# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|801.5506|852.6131|51.0625|6.37%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|1023.3911|995.5796|-27.8115|-2.72%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|2744.8385|2673.4971|-71.3414|-2.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|2436.3986|2154.8479|-281.5507|-11.56%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|7094.7893|6710.9791|-383.8102|-5.41%|
|migraphx_cadene__dpn92i1|PASS|within tol|463.8861|476.4595|12.5734|2.71%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|28024.6677|28136.7381|112.0704|0.4%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|1009.7442|1001.7511|-7.9931|-0.79%|
|migraphx_cadene__resnext101_64x4di16|PASS|regression|6385.4546|7608.5124|1223.0578|19.15%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|5784.2009|6150.2927|366.0918|6.33%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|8237.9007|8214.4924|-23.4083|-0.28%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|163.9665|165.5021|1.5356|0.94%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|263.8879|268.9741|5.0862|1.93%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|72.414|68.9989|-3.415|-4.72%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|26.8739|27.6456|0.7717|2.87%|
|migraphx_torchvision__inceptioni1|PASS|within tol|614.4001|613.4417|-0.9584|-0.16%|
|migraphx_torchvision__inceptioni32|PASS|within tol|23101.6265|23077.899|-23.7275|-0.1%|
|migraphx_torchvision__resnet50i1|PASS|within tol|259.6859|255.587|-4.0989|-1.58%|
|migraphx_torchvision__resnet50i64|PASS|within tol|10339.7821|10439.0011|99.2189|0.96%|

## No Regressions Found

## No Progressions Found

