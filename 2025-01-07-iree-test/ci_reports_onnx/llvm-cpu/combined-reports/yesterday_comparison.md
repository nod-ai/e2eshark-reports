# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|88.5288|86.4354|-2.0934|-2.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|104.2575|89.5489|-14.7086|-14.11%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|305.2926|248.971|-56.3216|-18.45%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.0769|35.0497|3.9728|12.78%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|93.9791|82.8865|-11.0926|-11.8%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|246.8237|253.3641|6.5404|2.65%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.2615|39.1426|-1.1188|-2.78%|
|migraphx_bert__bert-large-uncased|PASS|regression|389.766|478.5017|88.7356|22.77%|
|migraphx_cadene__dpn92i1|PASS|within tol|176.0171|174.3911|-1.626|-0.92%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5288.8137|5332.1583|43.3446|0.82%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|337.467|323.4656|-14.0014|-4.15%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5103.5174|5037.4575|-66.0598|-1.29%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|378.8184|833.7401|454.9217|120.09%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|1287.0542|575.7035|-711.3506|-55.27%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.4428|90.434|0.9912|1.11%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|34.6667|32.7651|-1.9017|-5.49%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|198.0847|181.9387|-16.146|-8.15%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|84.2434|83.6467|-0.5967|-0.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|40.7148|40.0272|-0.6876|-1.69%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1610.8466|1619.3352|8.4887|0.53%|
|migraphx_torchvision__inceptioni1|PASS|within tol|197.3297|194.0136|-3.3161|-1.68%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5402.6857|5401.6767|-1.009|-0.02%|
|migraphx_torchvision__resnet50i1|PASS|within tol|89.0594|87.9115|-1.1479|-1.29%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5103.7119|5200.2773|96.5654|1.89%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2792.067|2596.8288|-195.2382|-6.99%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4117.6671|4131.4642|13.7971|0.34%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5809.6243|5740.354|-69.2703|-1.19%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|167.0051|893.7982|726.7931|435.19%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|285.5363|273.6011|-11.9352|-4.18%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|373.7518|369.6332|-4.1186|-1.1%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|386.8539|385.382|-1.4719|-0.38%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|578.7387|594.8976|16.1589|2.79%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|833.8288|808.1282|-25.7006|-3.08%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5037.4221|5006.7862|-30.636|-0.61%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|7938.7413|8024.6084|85.8672|1.08%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11271.6194|11153.1686|-118.4508|-1.05%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|710.5995|711.4927|0.8933|0.13%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1081.5039|1103.9499|22.446|2.08%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1524.8563|1517.1563|-7.7|-0.5%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1304.3957|1300.6686|-3.7271|-0.29%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|2081.485|2114.792|33.307|1.6%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2907.1098|2899.6721|-7.4376|-0.26%|

## No Regressions Found

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_bert__bertsquad-12|compilation|PASS|
|migraphx_sd__unet__model|import_model|compilation|
|migraphx_sdxl__unet__model|import_model|compilation|

