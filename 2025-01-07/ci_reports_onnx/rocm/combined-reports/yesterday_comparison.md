# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|253.3962|101.4484|-151.9478|-59.96%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|121.0841|101.0804|-20.0037|-16.52%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|500.9224|501.1806|0.2582|0.05%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|54.0602|54.2669|0.2067|0.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1694|63.1394|-0.0301|-0.05%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|297.3556|296.1129|-1.2426|-0.42%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|46.6328|32.7342|-13.8986|-29.8%|
|migraphx_bert__bert-large-uncased|PASS|progression|40.8976|19.24|-21.6577|-52.96%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4584|42.4469|-0.0114|-0.03%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|150.0442|149.2952|-0.7489|-0.5%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|116.2541|114.3818|-1.8723|-1.61%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|370.6191|369.9719|-0.6472|-0.17%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.389|7.3784|-0.0106|-0.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|25.1238|24.3864|-0.7374|-2.94%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.5883|34.3327|-0.2556|-0.74%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|148.2722|172.0769|23.8048|16.05%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|16.455|15.8733|-0.5817|-3.53%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.5156|5.9096|0.394|7.14%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|77.0232|76.4054|-0.6178|-0.8%|
|migraphx_torchvision__inceptioni1|PASS|regression|41.0244|47.4254|6.401|15.6%|
|migraphx_torchvision__inceptioni32|PASS|within tol|100.6982|100.1275|-0.5707|-0.57%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.319|11.3327|0.0138|0.12%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|194.9108|193.8942|-1.0166|-0.52%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.8104|36.5457|-0.2648|-0.72%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|117.2455|60.1779|-57.0676|-48.67%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|149.6298|81.9546|-67.6752|-45.23%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|25.1611|13.0337|-12.1274|-48.2%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|56.7249|13.281|-43.4439|-76.59%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|32.7468|35.7285|2.9817|9.11%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|58.9901|12.6216|-46.3684|-78.6%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2481|13.2617|0.0136|0.1%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.9044|21.913|0.0086|0.04%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|72.8821|74.3035|1.4214|1.95%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|114.9791|114.9871|0.008|0.01%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|164.5424|203.1121|38.5698|23.44%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4325|14.5084|0.0759|0.53%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.2287|18.1961|-0.0326|-0.18%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|44.8896|27.3758|-17.5138|-39.02%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.7518|20.8351|0.0832|0.4%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|30.4996|30.627|0.1274|0.42%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.8605|44.9452|0.0846|0.19%|

## 6 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|PASS|Numerics|
|convnext_femto_ols.d1_in1k|PASS|Numerics|
|crossvit_base_240|PASS|Numerics|
|levit_192.fb_dist_in1k|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|Numerics|

## 2 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_lite_mini|Numerics|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|

