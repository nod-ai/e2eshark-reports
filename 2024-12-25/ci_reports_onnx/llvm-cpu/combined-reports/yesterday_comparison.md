# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.6733|88.3988|2.7255|3.18%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|93.0272|87.3692|-5.658|-6.08%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|258.431|290.0159|31.5849|12.22%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.0304|32.0092|0.9788|3.15%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|82.3073|89.911|7.6036|9.24%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|274.8296|394.8994|120.0698|43.69%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|39.9241|40.6734|0.7494|1.88%|
|migraphx_bert__bert-large-uncased|PASS|within tol|378.9233|393.2791|14.3558|3.79%|
|migraphx_cadene__dpn92i1|PASS|progression|433.3239|214.7175|-218.6065|-50.45%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5595.699|5719.828|124.129|2.22%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|350.8182|318.7091|-32.1092|-9.15%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5166.5223|5091.4804|-75.0419|-1.45%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|384.8007|389.904|5.1032|1.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|502.3912|623.0276|120.6364|24.01%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|95.5354|94.8517|-0.6837|-0.72%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|31.3145|32.7402|1.4257|4.55%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|180.8036|695.6977|514.8942|284.78%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|77.139|79.8015|2.6625|3.45%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|40.1092|40.9302|0.821|2.05%|
|migraphx_torchvision__densenet121i32|PASS|progression|1664.518|1497.4943|-167.0236|-10.03%|
|migraphx_torchvision__inceptioni1|PASS|within tol|210.5846|219.7085|9.1239|4.33%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5818.3848|5906.0292|87.6444|1.51%|
|migraphx_torchvision__resnet50i1|PASS|regression|87.2771|91.8738|4.5967|5.27%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5847.8817|5877.6781|29.7965|0.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2542.6023|2637.4042|94.8019|3.73%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4104.9566|4095.8736|-9.083|-0.22%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5920.4704|5670.4401|-250.0303|-4.22%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|158.7854|165.5632|6.7777|4.27%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|268.5095|260.8206|-7.6888|-2.86%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|371.229|377.7139|6.4849|1.75%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|410.9941|388.4511|-22.543|-5.48%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|670.2538|630.8761|-39.3777|-5.88%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|852.0254|812.8752|-39.1502|-4.59%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5147.4086|5168.7924|21.3838|0.42%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8135.3355|8045.0534|-90.2822|-1.11%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11252.679|11034.999|-217.68|-1.93%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|710.8082|708.7241|-2.0841|-0.29%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1084.5802|1076.6727|-7.9075|-0.73%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1534.4345|1494.5585|-39.876|-2.6%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1403.7264|1302.8377|-100.8887|-7.19%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2140.1996|2056.0045|-84.1951|-3.93%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2990.1407|2866.9779|-123.1628|-4.12%|

## No Regressions Found

## No Progressions Found

