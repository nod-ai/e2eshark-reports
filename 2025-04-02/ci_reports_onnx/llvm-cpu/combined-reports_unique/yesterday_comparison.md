# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|87.9337|93.9684|6.0347|6.86%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|88.4826|92.764|4.2814|4.84%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|249.3528|252.3977|3.0449|1.22%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.4996|30.7497|-0.7499|-2.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|85.4584|91.318|5.8596|6.86%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|250.8241|251.3207|0.4965|0.2%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|44.5704|63.3148|18.7444|42.06%|
|migraphx_bert__bert-large-uncased|PASS|within tol|369.869|368.7704|-1.0986|-0.3%|
|migraphx_cadene__dpn92i1|PASS|regression|160.545|196.7094|36.1644|22.53%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5458.452|6261.0407|802.5886|14.7%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|316.8869|417.9848|101.0979|31.9%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|404.3841|600.3358|195.9518|48.46%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|448.9047|447.6904|-1.2142|-0.27%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|94.9171|94.7543|-0.1627|-0.17%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|30.7629|939.2312|908.4683|2953.13%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|177.1292|178.4386|1.3094|0.74%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|61.3385|59.9646|-1.3739|-2.24%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|20.3579|17.4722|-2.8857|-14.17%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1551.5861|1582.2464|30.6602|1.98%|
|migraphx_torchvision__inceptioni1|PASS|regression|190.2132|208.0923|17.8791|9.4%|
|migraphx_torchvision__resnet50i1|PASS|within tol|88.5635|85.9623|-2.6012|-2.94%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|1415.273|1460.3615|45.0886|3.19%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|2967.5434|3275.5178|307.9745|10.38%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|4625.4001|4695.6866|70.2866|1.52%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|149.3784|161.4012|12.0228|8.05%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|251.1327|274.4397|23.3069|9.28%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|356.6167|365.5608|8.9441|2.51%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|242.1887|357.9796|115.7909|47.81%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|426.8844|476.0503|49.1659|11.52%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|669.0304|665.2509|-3.7795|-0.56%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|2760.8474|2788.5094|27.662|1.0%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|5677.8681|5664.446|-13.4221|-0.24%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|9091.2521|9063.2488|-28.0033|-0.31%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|401.0472|544.8052|143.758|35.85%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|799.0986|799.7359|0.6373|0.08%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1237.22|1297.1455|59.9256|4.84%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|745.276|760.8807|15.6047|2.09%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1502.2704|1502.2214|-0.049|-0.0%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2379.9502|2400.7283|20.7781|0.87%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|xcit_nano_12_p16_384_dist_Opset16_timm|PASS|Numerics|

## No Progressions Found

