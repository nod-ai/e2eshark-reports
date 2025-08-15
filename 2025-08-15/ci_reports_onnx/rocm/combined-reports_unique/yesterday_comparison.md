# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|120.8016|117.0747|-3.7268|-3.09%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.9337|116.4701|-1.4637|-1.24%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|71.8826|71.111|-0.7716|-1.07%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|74.8298|74.752|-0.0778|-0.1%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|301.0354|301.1031|0.0677|0.02%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|45.0689|41.5931|-3.4758|-7.71%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2321|19.204|-0.0281|-0.15%|
|migraphx_cadene__dpn92i1|PASS|progression|14.7845|12.7371|-2.0474|-13.85%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|22.7938|22.1275|-0.6663|-2.92%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.4996|6.4385|-0.0611|-0.94%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.6019|7.0893|-0.5126|-6.74%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.4074|27.2723|0.8649|3.28%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|15.1385|14.7649|-0.3736|-2.47%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.6828|43.262|-0.4209|-0.96%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|114.099|109.7676|-4.3314|-3.8%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|18.9866|18.7904|-0.1962|-1.03%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|10.2982|10.6432|0.345|3.35%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.8887|14.9164|0.0277|0.19%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.1253|4.0861|-0.0391|-0.95%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.1499|2.1669|0.0171|0.79%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.8454|25.7617|-0.0838|-0.32%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.0247|37.1616|0.1369|0.37%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.0583|55.4|-0.6583|-1.17%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6099|12.584|-0.0259|-0.21%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6293|12.7012|0.072|0.57%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2733|19.2267|-0.0466|-0.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8268|12.9129|0.0861|0.67%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3473|19.2433|-0.1039|-0.54%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7784|19.5907|-0.1876|-0.95%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.7023|35.6004|-0.1018|-0.29%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|70.2151|69.1549|-1.0602|-1.51%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|109.3232|109.5309|0.2077|0.19%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3654|19.425|0.0597|0.31%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1681|20.1422|-0.0258|-0.13%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3016|23.2858|-0.0158|-0.07%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2606|20.2106|-0.05|-0.25%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.2253|26.2341|0.0087|0.03%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5483|32.4532|-0.0951|-0.29%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_384.in22k_ft_in22k_in1k|PASS|Numerics|

## No Progressions Found

