# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|801.5506|785.2736|-16.277|-2.03%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|1023.3911|946.213|-77.178|-7.54%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|2744.8385|2760.8341|15.9956|0.58%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|2436.3986|2255.898|-180.5006|-7.41%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|7094.7893|7046.6098|-48.1796|-0.68%|
|migraphx_cadene__dpn92i1|PASS|within tol|463.8861|470.6702|6.7841|1.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|28024.6677|28139.6932|115.0255|0.41%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|1009.7442|1015.3186|5.5744|0.55%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|6385.4546|6343.3778|-42.0768|-0.66%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|5784.2009|5936.275|152.0741|2.63%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|8237.9007|8235.0451|-2.8556|-0.03%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|163.9665|164.128|0.1615|0.1%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|263.8879|265.8975|2.0096|0.76%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|72.414|64.6864|-7.7276|-10.67%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|26.8739|26.4917|-0.3822|-1.42%|
|migraphx_torchvision__inceptioni1|PASS|within tol|614.4001|622.1083|7.7083|1.25%|
|migraphx_torchvision__inceptioni32|PASS|within tol|23101.6265|22871.3331|-230.2934|-1.0%|
|migraphx_torchvision__resnet50i1|PASS|within tol|259.6859|269.3692|9.6832|3.73%|
|migraphx_torchvision__resnet50i64|PASS|within tol|10339.7821|10371.283|31.5009|0.3%|

## No Regressions Found

## No Progressions Found

