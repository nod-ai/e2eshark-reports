# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|87.5911|88.0331|0.442|0.5%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|86.6881|87.6128|0.9247|1.07%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|276.9994|257.5493|-19.4502|-7.02%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|30.4011|30.9404|0.5393|1.77%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|92.1112|90.0254|-2.0858|-2.26%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|242.3886|246.9459|4.5573|1.88%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.9818|42.7863|0.8044|1.92%|
|migraphx_bert__bert-large-uncased|PASS|regression|373.7697|488.8848|115.1151|30.8%|
|migraphx_cadene__dpn92i1|PASS|within tol|169.3403|169.5145|0.1742|0.1%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5346.4808|5265.3699|-81.1109|-1.52%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|324.3817|324.972|0.5903|0.18%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5127.0395|5114.2881|-12.7514|-0.25%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|380.2964|379.3742|-0.9221|-0.24%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|417.8207|424.0269|6.2062|1.49%|
|migraphx_mlperf__resnet50_v1|PASS|progression|109.4143|103.882|-5.5323|-5.06%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|32.345|38.3144|5.9694|18.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|179.5458|190.0075|10.4617|5.83%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|78.1834|81.4357|3.2523|4.16%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|46.203|39.1193|-7.0838|-15.33%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1634.9357|1577.6506|-57.2851|-3.5%|
|migraphx_torchvision__inceptioni1|PASS|progression|213.4192|199.4682|-13.951|-6.54%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5381.1677|5398.6326|17.4649|0.32%|
|migraphx_torchvision__resnet50i1|PASS|regression|84.7897|89.5025|4.7128|5.56%|
|migraphx_torchvision__resnet50i64|PASS|progression|5452.8202|5058.6621|-394.1581|-7.23%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2643.3794|2563.3831|-79.9963|-3.03%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4121.6132|4087.2503|-34.3629|-0.83%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5770.3073|5813.2613|42.954|0.74%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|162.6092|172.0915|9.4823|5.83%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|261.742|265.1819|3.4399|1.31%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|382.4774|399.4563|16.9789|4.44%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|392.0816|385.1619|-6.9197|-1.76%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|612.1139|595.5503|-16.5636|-2.71%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|898.6521|814.207|-84.4451|-9.4%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5149.3818|5046.7728|-102.6089|-1.99%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8160.4954|7839.2557|-321.2397|-3.94%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11249.11|11228.7841|-20.326|-0.18%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|790.0152|711.0369|-78.9783|-10.0%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1117.862|1086.6882|-31.1738|-2.79%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1538.9166|1515.6857|-23.2309|-1.51%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1361.7134|1291.0623|-70.6511|-5.19%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2039.7029|2152.693|112.9901|5.54%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2923.1843|2865.0735|-58.1108|-1.99%|

## 26 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|coatnet_0_rw_224.sw_in1k|PASS|compilation|
|coatnet_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_3_rw_224.sw_in12k|PASS|compilation|
|coatnet_bn_0_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|PASS|compilation|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|resnest101e_vaiq|PASS|compilation|
|resnest14d_vaiq|PASS|compilation|
|resnest26d_vaiq|PASS|compilation|
|resnest50d_4s2x40d_vaiq|PASS|compilation|
|resnest50d_vaiq|PASS|compilation|
|skresnext50_32x4d_vaiq|PASS|compilation|
|visformer_small|PASS|compilation|
|xcit_nano_12_p8_224_dist|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|

