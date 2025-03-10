# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|488.2958|27357.0383|26868.7425|5502.55%|
|migraphx_ORT__distilgpt2_1|PASS|regression|61.6078|249006.7839|248945.1761|404080.67%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|61.7883|62444.7149|62382.9267|100962.42%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|239.4212|16196.7202|15957.299|6664.95%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.1637|36.7135|2.5499|7.46%|
|migraphx_agentmodel__AgentModel|Numerics|regression|2.0539|2.1817|0.1278|6.22%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9083|18.9857|0.0774|0.41%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0765|5.0533|-0.0232|-0.46%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|30.0351|29.5092|-0.5259|-1.75%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.4268|6.2805|-0.1464|-2.28%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|30.3951|29.8421|-0.5529|-1.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9853|7.1351|0.1498|2.14%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|27.4833|29.1661|1.6829|6.12%|
|migraphx_mlperf__resnet50_v1|PASS|regression|4.9874|5.2436|0.2562|5.14%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|43.5556|43.6424|0.0868|0.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.2876|46.3967|0.1091|0.24%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|19.2681|17.3371|-1.931|-10.02%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.3948|8.0024|-0.3924|-4.67%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1506|18.0183|-0.1323|-0.73%|
|migraphx_torchvision__inceptioni1|PASS|within tol|5.0573|4.9135|-0.1438|-2.84%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1051|28.1657|0.0606|0.22%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.72|3.5828|-0.1372|-3.69%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8436|20.9186|0.075|0.36%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.4525|25.5427|0.0902|0.35%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.4371|37.6983|0.2612|0.7%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|57.5395|57.8863|0.3468|0.6%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.0779|12.6074|0.5295|4.38%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.4632|12.4385|-0.0247|-0.2%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.074|19.077|0.003|0.02%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5542|12.4321|-0.122|-0.97%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|18.8408|19.065|0.2242|1.19%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.4452|19.5653|0.1201|0.62%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.8189|36.2001|0.3812|1.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|71.4012|71.8472|0.446|0.62%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|112.5934|112.3466|-0.2468|-0.22%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.056|19.2059|0.1498|0.79%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.8956|19.8337|-0.0619|-0.31%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.2598|23.7731|0.5133|2.21%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.075|19.8834|-0.1916|-0.95%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|25.9662|26.0354|0.0693|0.27%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.9809|33.1463|0.1655|0.5%|

## No Regressions Found

## 21 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|AlexNet_vaiq_int8|compiled_inference|PASS|
|CSP-DarkNet_vaiq_int8|compiled_inference|PASS|
|DarkNet53_vaiq|compiled_inference|PASS|
|EfficientNet_b0_vaiq|compiled_inference|Numerics|
|EfficientNet_b1_vaiq|compiled_inference|PASS|
|EfficientNet_b2_vaiq|compiled_inference|Numerics|
|bat_resnext26ts.ch_in1k|compiled_inference|PASS|
|beit_base_patch16_224.in22k_ft_in22k_in1k|compiled_inference|PASS|
|beit_base_patch16_384.in22k_ft_in22k_in1k|compiled_inference|PASS|
|migraphx_ORT__bert_base_cased_1|compiled_inference|PASS|
|migraphx_ORT__bert_base_uncased_1|compiled_inference|PASS|
|model--bert-finetuned-squad--kenyaari|compiled_inference|PASS|
|model--bert-finetuned-squad--krolis|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nachowdh|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nastorian|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|compiled_inference|PASS|
|model--finetuning-sentiment-model-3000-samples--nhero|compiled_inference|PASS|
|resnet200d_train_vaiq|compiled_inference|PASS|
|resnet200d_vaiq|compiled_inference|PASS|
|resnet26_test_vaiq|compiled_inference|PASS|
|resnet26_vaiq|compiled_inference|PASS|

