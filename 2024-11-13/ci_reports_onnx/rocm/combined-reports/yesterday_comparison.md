# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|113.1868|111.1523|-2.0345|-1.8%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|111.9171|112.1985|0.2815|0.25%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|363.7123|364.593|0.8807|0.24%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|61.4629|61.1809|-0.282|-0.46%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|72.0441|71.9526|-0.0915|-0.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|274.9079|274.1448|-0.7632|-0.28%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|37.2943|36.3194|-0.975|-2.61%|
|migraphx_bert__bert-large-uncased|PASS|within tol|20.0903|20.651|0.5607|2.79%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|152.0132|152.1333|0.1201|0.08%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|218.2506|218.4394|0.1888|0.09%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3946|7.4243|0.0297|0.4%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|37.9168|41.7835|3.8667|10.2%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|6.4203|6.4696|0.0493|0.77%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|27.3759|28.562|1.186|4.33%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|52.6863|52.9139|0.2276|0.43%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|19.5434|19.9585|0.4151|2.12%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|12.8703|12.0838|-0.7865|-6.11%|
|migraphx_torchvision__densenet121i32|PASS|within tol|50.7128|50.3898|-0.323|-0.64%|
|migraphx_torchvision__inceptioni1|PASS|within tol|15.7148|15.7074|-0.0074|-0.05%|
|migraphx_torchvision__inceptioni32|PASS|within tol|137.8446|137.7119|-0.1326|-0.1%|
|migraphx_torchvision__resnet50i64|PASS|within tol|182.7376|182.6936|-0.044|-0.02%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4565|33.425|-0.0314|-0.09%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.7903|57.718|-0.0722|-0.12%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|73.3507|73.4524|0.1017|0.14%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.4096|13.5243|0.1147|0.86%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.8879|13.707|-0.181|-1.3%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.8253|19.8652|0.0399|0.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.4566|13.2372|-0.2195|-1.63%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.9402|13.9334|-0.0068|-0.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7554|21.8185|0.0631|0.29%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.2432|69.3034|0.0602|0.09%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.6539|104.7354|0.0814|0.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|145.6737|145.5186|-0.1551|-0.11%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.894|15.0096|0.1155|0.78%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.4304|17.5749|0.1445|0.83%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6743|26.6371|-0.0372|-0.14%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2498|20.134|-0.1159|-0.57%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.0058|28.0|-0.0058|-0.02%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|41.2697|41.2972|0.0275|0.07%|

## No Regressions Found

## No Progressions Found

