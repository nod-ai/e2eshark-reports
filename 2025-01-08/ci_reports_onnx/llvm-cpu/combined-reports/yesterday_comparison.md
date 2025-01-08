# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.5288|88.5269|-0.0019|-0.0%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|104.2575|88.8307|-15.4268|-14.8%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|305.2926|362.6464|57.3538|18.79%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.0769|30.9312|-0.1457|-0.47%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|93.9791|82.7602|-11.2189|-11.94%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|246.8237|264.1185|17.2948|7.01%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.2615|40.797|0.5356|1.33%|
|migraphx_bert__bert-large-uncased|PASS|within tol|389.766|380.8598|-8.9063|-2.29%|
|migraphx_cadene__dpn92i1|PASS|within tol|176.0171|170.3673|-5.6498|-3.21%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5288.8137|5379.7176|90.9039|1.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|337.467|342.6177|5.1507|1.53%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5103.5174|5109.8962|6.3789|0.12%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|378.8184|379.8264|1.008|0.27%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1287.0542|455.1114|-831.9428|-64.64%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.4428|89.5441|0.1013|0.11%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|34.6667|33.3247|-1.342|-3.87%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|198.0847|179.7278|-18.3569|-9.27%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|84.2434|77.2967|-6.9467|-8.25%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|40.7148|45.3326|4.6178|11.34%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1610.8466|1621.6976|10.8511|0.67%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.3297|194.7947|-2.535|-1.28%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5402.6857|5496.0982|93.4125|1.73%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.0594|86.5042|-2.5552|-2.87%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5103.7119|5070.3487|-33.3631|-0.65%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2792.067|2686.8134|-105.2536|-3.77%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4117.6671|4246.7513|129.0842|3.13%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5809.6243|5783.0032|-26.6211|-0.46%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|167.0051|346.3536|179.3485|107.39%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|285.5363|273.0708|-12.4655|-4.37%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|373.7518|372.839|-0.9128|-0.24%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|386.8539|386.8941|0.0402|0.01%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|578.7387|639.8195|61.0807|10.55%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|833.8288|819.3633|-14.4655|-1.73%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5037.4221|5120.6753|83.2532|1.65%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7938.7413|8061.6189|122.8776|1.55%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11271.6194|11369.9631|98.3437|0.87%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|710.5995|730.1091|19.5097|2.75%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1081.5039|1134.9163|53.4125|4.94%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1524.8563|1577.0391|52.1828|3.42%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1304.3957|1309.1642|4.7685|0.37%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2081.485|2235.2007|153.7157|7.38%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2907.1098|2908.3059|1.1961|0.04%|

## No Regressions Found

## No Progressions Found

