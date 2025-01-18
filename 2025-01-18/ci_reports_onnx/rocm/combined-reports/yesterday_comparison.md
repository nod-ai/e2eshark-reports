# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|105.1419|106.3694|1.2275|1.17%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|105.0129|106.9545|1.9415|1.85%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|468.902|476.4884|7.5864|1.62%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.3677|60.156|-0.2117|-0.35%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.7238|64.8058|0.082|0.13%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.3891|272.713|0.3239|0.12%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.0677|32.4594|0.3917|1.22%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4552|19.5748|0.1196|0.61%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.9673|64.4245|-0.5428|-0.84%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.0178|149.1959|-4.8219|-3.13%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|173.488|172.8135|-0.6745|-0.39%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|387.3001|387.5401|0.24|0.06%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.564|7.2022|-0.3619|-4.78%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|25.3367|25.6237|0.287|1.13%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.2099|42.3581|0.1482|0.35%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|143.3944|144.1467|0.7523|0.52%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.4951|16.4849|0.9898|6.39%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|6.541|7.3942|0.8532|13.04%|
|migraphx_torchvision__densenet121i32|Numerics|progression|69.0875|64.938|-4.1495|-6.01%|
|migraphx_torchvision__inceptioni1|PASS|within tol|62.3615|61.2555|-1.1061|-1.77%|
|migraphx_torchvision__inceptioni32|PASS|within tol|105.7045|101.075|-4.6295|-4.38%|
|migraphx_torchvision__resnet50i1|Numerics|progression|16.8827|15.8315|-1.0512|-6.23%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|147.9916|145.6363|-2.3552|-1.59%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.3972|33.7273|0.3301|0.99%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.083|57.5098|0.4268|0.75%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|76.0444|76.973|0.9286|1.22%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0703|12.1771|0.1068|0.88%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.6874|12.7834|0.096|0.76%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.625|19.7095|0.0845|0.43%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8232|12.9453|0.1222|0.95%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4162|13.4223|0.0061|0.05%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.7128|21.6423|-0.0704|-0.32%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.0314|69.5475|0.5161|0.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.7369|106.2159|1.4789|1.41%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.0616|156.0975|2.0359|1.32%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4319|14.5018|0.0699|0.48%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|88.7676|17.1001|-71.6675|-80.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.9834|26.9864|0.003|0.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.6011|19.6325|0.0315|0.16%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.208|28.3513|0.1433|0.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.206|42.3142|0.1081|0.26%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|tf_mixnet_s.in1k|PASS|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|tf_efficientnet_b7.ap_in1k|compilation|PASS|

