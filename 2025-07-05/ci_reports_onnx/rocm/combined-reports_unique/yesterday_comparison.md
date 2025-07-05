# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|121.9358|121.8604|-0.0754|-0.06%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|125.5324|124.4074|-1.1251|-0.9%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|537.7661|540.0792|2.3131|0.43%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|68.7667|69.0172|0.2504|0.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|66.2558|70.7819|4.5261|6.83%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|339.8115|340.7421|0.9306|0.27%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8631|34.5217|-0.3414|-0.98%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2441|19.6303|0.3861|2.01%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.6151|3.4678|-0.1473|-4.07%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6405|19.7949|0.1544|0.79%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1551|4.1855|0.0304|0.73%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0873|7.0474|-0.04|-0.56%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.3917|27.2229|0.8312|3.15%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.0806|14.7031|0.6225|4.42%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.4833|41.7456|0.2623|0.63%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|104.7007|104.9262|0.2255|0.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.6164|20.4312|2.8148|15.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|10.0818|9.6908|-0.391|-3.88%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.643|13.6254|-0.0176|-0.13%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1174|3.1322|0.0148|0.48%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.034|2.0626|0.0286|1.41%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7004|25.7055|0.005|0.02%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|37.2159|41.0722|3.8563|10.36%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.6562|55.8439|-0.8122|-1.43%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5743|12.661|0.0867|0.69%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.787|12.8223|0.0353|0.28%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3881|19.3552|-0.0329|-0.17%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9486|12.9839|0.0354|0.27%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3691|19.2325|-0.1367|-0.71%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.8283|19.7807|-0.0475|-0.24%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|34.2984|41.1275|6.8292|19.91%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.6235|69.0421|-0.5814|-0.84%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|111.0947|110.5622|-0.5324|-0.48%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3437|19.5604|0.2167|1.12%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.0873|20.4018|0.3145|1.57%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2947|23.4102|0.1155|0.5%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.6936|20.2665|-0.4271|-2.06%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|25.9635|26.1384|0.1749|0.67%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.8103|32.6756|-0.1347|-0.41%|

## 4 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|gluon_resnet101_v1c_Opset17_timm|PASS|Numerics|
|model--distilbert-base-cased-distilled-squad--distilbert|PASS|Numerics|
|model--distilbert-base-uncased-finetuned-ner--dbsamu|PASS|Numerics|
|model--megatron-gpt2-345m--robowaifudev|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|deit3_base_patch16_384_in21ft1k_Opset16_timm|Numerics|PASS|
|deit3_large_patch16_224_Opset18_timm|Numerics|PASS|
|encoderdecoder_Opset17_transformers|Numerics|PASS|
|swin_large_patch4_window12_384.ms_in22k_ft_in1k|Numerics|PASS|
|swin_s3_small_224.ms_in1k|Numerics|PASS|
|vit_b_32_Opset16_torch_hub|Numerics|PASS|
|vit_large_patch16_224_in21k_Opset18_timm|Numerics|PASS|

