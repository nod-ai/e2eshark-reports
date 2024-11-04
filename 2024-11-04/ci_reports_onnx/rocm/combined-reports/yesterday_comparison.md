# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|114.2885|113.1607|-1.1278|-0.99%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|112.9528|112.9774|0.0246|0.02%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|353.9312|356.4718|2.5406|0.72%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.8989|72.8007|-0.0981|-0.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|279.7158|279.6242|-0.0916|-0.03%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.4649|154.6369|0.1719|0.11%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|216.9968|217.0877|0.0909|0.04%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9343|6.9692|0.0349|0.5%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|41.7655|35.1234|-6.6421|-15.9%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.2948|5.2755|-0.0193|-0.37%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|27.4372|29.2105|1.7734|6.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.4125|53.6519|1.2394|2.36%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|62.9816|63.3528|0.3712|0.59%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|7.9827|8.0245|0.0418|0.52%|
|migraphx_torchvision__densenet121i32|PASS|within tol|49.5282|49.3286|-0.1996|-0.4%|
|migraphx_torchvision__inceptioni1|PASS|within tol|18.0161|18.0299|0.0139|0.08%|
|migraphx_torchvision__inceptioni32|PASS|within tol|130.809|130.8305|0.0215|0.02%|
|migraphx_torchvision__resnet50i64|PASS|within tol|203.4727|203.3191|-0.1536|-0.08%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|swinv2_cr_small_224.sw_in1k|compiled_inference|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compiled_inference|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compiled_inference|PASS|

