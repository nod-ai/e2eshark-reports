# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|100.0199|111.5105|11.4906|11.49%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.4033|100.8908|1.4875|1.5%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|503.6045|500.4231|-3.1814|-0.63%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|54.1352|54.0124|-0.1227|-0.23%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.0113|63.3239|2.3126|3.79%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|290.66|296.7436|6.0836|2.09%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|31.2024|32.2091|1.0067|3.23%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2986|19.4052|0.1066|0.55%|
|migraphx_cadene__dpn92i1|Numerics|progression|58.7181|42.4594|-16.2587|-27.69%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|148.1801|149.3453|1.1653|0.79%|
|migraphx_cadene__resnext101_64x4di1|Numerics|progression|177.3287|114.1818|-63.1469|-35.61%|
|migraphx_cadene__resnext101_64x4di16|Numerics|within tol|362.6372|370.2828|7.6456|2.11%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.2474|7.3801|0.1327|1.83%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|26.2616|23.4891|-2.7725|-10.56%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|35.2113|34.6995|-0.5118|-1.45%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|141.8663|145.8738|4.0075|2.82%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|15.6085|16.0733|0.4648|2.98%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.2684|6.0951|-1.1733|-16.14%|
|migraphx_torchvision__densenet121i32|Numerics|progression|92.4333|76.6063|-15.827|-17.12%|
|migraphx_torchvision__inceptioni1|PASS|within tol|39.7012|39.6974|-0.0037|-0.01%|
|migraphx_torchvision__inceptioni32|PASS|within tol|98.6849|100.2415|1.5566|1.58%|
|migraphx_torchvision__resnet50i1|Numerics|within tol|11.3433|11.3212|-0.0221|-0.2%|
|migraphx_torchvision__resnet50i64|Numerics|within tol|188.5413|193.8748|5.3335|2.83%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|35.323|38.4031|3.0801|8.72%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.5031|60.2861|1.7831|3.05%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.5772|82.2096|2.6323|3.31%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0779|13.0464|-0.0315|-0.24%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2062|13.3409|0.1347|1.02%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.5605|19.5084|-0.0521|-0.27%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|14.1018|12.6017|-1.5001|-10.64%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.2645|13.2779|0.0135|0.1%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.6518|21.9592|0.3074|1.42%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|70.8497|73.5083|2.6586|3.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.4232|115.763|4.3398|3.89%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|239.1195|165.1401|-73.9794|-30.94%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|16.5387|14.4657|-2.073|-12.53%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.6155|18.2864|0.6708|3.81%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.6872|27.4489|0.7617|2.85%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.0822|20.8119|0.7296|3.63%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6596|30.7624|1.1029|3.72%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|121.7647|45.0643|-76.7004|-62.99%|

## One Regression Found:

|model name|old_status|new_status|
|---|---|---|
|levit_192.fb_dist_in1k|PASS|Numerics|

## 3 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|levit_256.fb_dist_in1k|Numerics|PASS|
|model--flaubert-base-uncased-finetuned-cooking--nbouali|Numerics|PASS|
|model--spanbert-base-cased-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|

