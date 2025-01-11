# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|99.8676|99.2669|-0.6008|-0.6%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.7271|99.3371|-0.39|-0.39%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|502.4833|501.9064|-0.5769|-0.11%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|52.2461|52.5754|0.3293|0.63%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|60.8933|60.7694|-0.1239|-0.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|292.2198|294.0132|1.7934|0.61%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.2718|31.7165|0.4447|1.42%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2692|19.2491|-0.02|-0.1%|
|migraphx_cadene__dpn92i1|Numerics|within tol|42.6276|42.5909|-0.0367|-0.09%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|155.8698|155.6455|-0.2243|-0.14%|
|migraphx_cadene__resnext101_64x4di1|Numerics|within tol|118.0695|117.945|-0.1245|-0.11%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|388.1691|388.1433|-0.0258|-0.01%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2271|7.1879|-0.0392|-0.54%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|24.5545|26.9376|2.3831|9.71%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.1015|33.4139|-0.6876|-2.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|140.1546|68.5652|-71.5894|-51.08%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|14.5282|15.5303|1.0021|6.9%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.665|5.6728|-1.9922|-25.99%|
|migraphx_torchvision__densenet121i32|Numerics|within tol|73.8577|73.6176|-0.2401|-0.33%|
|migraphx_torchvision__inceptioni1|PASS|within tol|41.0714|41.078|0.0066|0.02%|
|migraphx_torchvision__inceptioni32|PASS|within tol|106.9706|106.8353|-0.1352|-0.13%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|12.2064|12.188|-0.0184|-0.15%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|152.3622|151.6353|-0.7269|-0.48%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|36.1539|35.0326|-1.1213|-3.1%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|81.5181|57.6552|-23.8629|-29.27%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.5089|78.4035|-1.1054|-1.39%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.158|13.0669|-0.0911|-0.69%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2694|13.2581|-0.0113|-0.09%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4558|19.4944|0.0386|0.2%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6939|12.6885|-0.0054|-0.04%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2696|13.194|-0.0756|-0.57%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6721|21.5164|-0.1557|-0.72%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.843|70.1281|-0.7149|-1.01%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.3453|109.88|-1.4652|-1.32%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|157.1441|157.5009|0.3568|0.23%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.2647|14.2711|0.0064|0.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6267|17.5843|-0.0424|-0.24%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.5067|26.4785|-0.0282|-0.11%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0299|20.0571|0.0272|0.14%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6778|29.4831|-0.1947|-0.66%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.511|43.145|-0.3661|-0.84%|

## No Regressions Found

## No Progressions Found

