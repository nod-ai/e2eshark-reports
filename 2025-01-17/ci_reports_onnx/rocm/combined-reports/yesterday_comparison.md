# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|104.9154|105.1419|0.2265|0.22%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|104.2585|105.0129|0.7544|0.72%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|468.659|468.902|0.2429|0.05%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.9171|60.3677|0.4506|0.75%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.8662|64.7238|-0.1424|-0.22%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|272.163|272.3891|0.2262|0.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|32.1215|32.0677|-0.0538|-0.17%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.4497|19.4552|0.0055|0.03%|
|migraphx_cadene__dpn92i1|Numerics|within tol|64.7155|64.9673|0.2518|0.39%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|154.1809|154.0178|-0.1631|-0.11%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|173.5548|173.488|-0.0668|-0.04%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|387.5817|387.3001|-0.2816|-0.07%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.1895|7.564|0.3746|5.21%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.8883|25.3367|0.4484|1.8%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.8731|42.2099|-0.6632|-1.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|142.8684|143.3944|0.526|0.37%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|16.6375|15.4951|-1.1425|-6.87%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.9748|6.541|-1.4338|-17.98%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|69.0149|69.0875|0.0726|0.11%|
|migraphx_torchvision__inceptioni1|PASS|within tol|62.2161|62.3615|0.1454|0.23%|
|migraphx_torchvision__inceptioni32|PASS|within tol|105.7796|105.7045|-0.0751|-0.07%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|17.124|16.8827|-0.2414|-1.41%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|148.077|147.9916|-0.0854|-0.06%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|33.4837|33.3972|-0.0865|-0.26%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|57.0522|57.083|0.0307|0.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|75.8827|76.0444|0.1617|0.21%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1022|12.0703|-0.032|-0.26%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.7756|12.6874|-0.0881|-0.69%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.6206|19.625|0.0044|0.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8439|12.8232|-0.0207|-0.16%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.3652|13.4162|0.051|0.38%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6407|21.7128|0.072|0.33%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|69.0899|69.0314|-0.0585|-0.08%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|104.6748|104.7369|0.0622|0.06%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|154.1271|154.0616|-0.0655|-0.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4459|14.4319|-0.014|-0.1%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|17.0856|88.7676|71.682|419.55%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|27.0122|26.9834|-0.0288|-0.11%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.6553|19.6011|-0.0543|-0.28%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.1444|28.208|0.0636|0.23%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|42.1224|42.206|0.0836|0.2%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|tf_efficientnet_b7.ap_in1k|PASS|compilation|

## One Progression Found:

|model name|old_status|new_status|
|---|---|---|
|mvitv2_small|compilation|PASS|

