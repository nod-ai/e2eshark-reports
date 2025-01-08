# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|101.4484|99.7446|-1.7038|-1.68%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|101.0804|98.7918|-2.2886|-2.26%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|501.1806|503.8716|2.691|0.54%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|54.2669|53.5263|-0.7406|-1.36%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.1394|61.3643|-1.775|-2.81%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|296.1129|291.2354|-4.8775|-1.65%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.7342|31.2603|-1.4739|-4.5%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.24|19.3377|0.0977|0.51%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.4469|42.5172|0.0703|0.17%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|149.2952|148.4542|-0.8411|-0.56%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|114.3818|114.059|-0.3229|-0.28%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|369.9719|364.1907|-5.7812|-1.56%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3784|7.2202|-0.1582|-2.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.3864|23.3214|-1.065|-4.37%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.3327|33.2908|-1.0419|-3.03%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|172.0769|142.4226|-29.6543|-17.23%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|15.8733|10.7814|-5.0918|-32.08%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|5.9096|6.5151|0.6055|10.25%|
|migraphx_torchvision__densenet121i32|Numerics|regression|76.4054|81.5606|5.1552|6.75%|
|migraphx_torchvision__inceptioni1|PASS|progression|47.4254|41.8563|-5.5691|-11.74%|
|migraphx_torchvision__inceptioni32|PASS|regression|100.1275|112.2084|12.081|12.07%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3327|11.2291|-0.1037|-0.91%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|193.8942|190.7839|-3.1103|-1.6%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|36.5457|72.6423|36.0966|98.77%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|60.1779|58.9281|-1.2497|-2.08%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|81.9546|79.4377|-2.5169|-3.07%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0337|13.1847|0.151|1.16%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|13.281|17.4563|4.1753|31.44%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|35.7285|19.4291|-16.2994|-45.62%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6216|12.6625|0.0408|0.32%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.2617|32.271|19.0093|143.34%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.913|40.4771|18.5642|84.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|74.3035|70.9405|-3.363|-4.53%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|114.9871|285.9087|170.9216|148.64%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|203.1121|157.2721|-45.8401|-22.57%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.5084|14.2728|-0.2356|-1.62%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|18.1961|17.7134|-0.4827|-2.65%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.3758|26.7851|-0.5907|-2.16%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.8351|20.1238|-0.7113|-3.41%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|30.627|81.8569|51.2299|167.27%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|44.9452|43.5284|-1.4168|-3.15%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|xcit_nano_12_p8_384_dist|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_femto_ols.d1_in1k|Numerics|PASS|
|crossvit_base_240|Numerics|PASS|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|Numerics|PASS|

