# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|456.1513|488.2958|32.1445|7.05%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|60.7957|61.6078|0.8121|1.34%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|62.2723|61.7883|-0.484|-0.78%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|240.7142|239.4212|-1.293|-0.54%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|35.5748|34.1637|-1.4111|-3.97%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.1332|2.0539|-0.0793|-3.72%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.874|18.9083|0.0343|0.18%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0282|5.0765|0.0484|0.96%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.3986|30.0351|0.6365|2.17%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.3718|6.4268|0.055|0.86%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.8136|30.3951|0.5814|1.95%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.1735|6.9853|-0.1882|-2.62%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|28.7499|27.4833|-1.2666|-4.41%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|5.0595|4.9874|-0.0722|-1.43%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.9229|43.5556|0.6327|1.47%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|45.3773|46.2876|0.9102|2.01%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.2939|19.2681|0.9742|5.33%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|8.1346|8.3948|0.2602|3.2%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.1462|18.1506|0.0044|0.02%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.8889|5.0573|0.1684|3.44%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.1257|28.1051|-0.0207|-0.07%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5572|3.72|0.1628|4.58%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.8282|20.8436|0.0154|0.07%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|32.2878|25.4525|-6.8353|-21.17%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|52.218|37.4371|-14.7809|-28.31%|
|migx_bench_bert-large-uncased_16_384|PASS|progression|70.1519|57.5395|-12.6124|-17.98%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.1425|12.0779|-0.0646|-0.53%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.464|12.4632|-0.0007|-0.01%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.2337|19.074|-0.1597|-0.83%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.8684|12.5542|-0.3142|-2.44%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|13.4221|18.8408|5.4187|40.37%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|20.7085|19.4452|-1.2633|-6.1%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|65.0137|35.8189|-29.1948|-44.91%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|98.4232|71.4012|-27.0221|-27.45%|
|migx_bench_bert-large-uncased_32_384|PASS|progression|139.4752|112.5934|-26.8818|-19.27%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|14.431|19.056|4.625|32.05%|
|migx_bench_bert-large-uncased_4_256|PASS|regression|16.3025|19.8956|3.5931|22.04%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|25.0381|23.2598|-1.7784|-7.1%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|18.8448|20.075|1.2302|6.53%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.7445|25.9662|-0.7783|-2.91%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|39.7868|32.9809|-6.8059|-17.11%|

## 24 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|AlexNet_vaiq_int8|PASS|compiled_inference|
|CSP-DarkNet_vaiq_int8|PASS|compiled_inference|
|DarkNet53_vaiq|PASS|compiled_inference|
|EfficientNet_b0_vaiq|Numerics|compiled_inference|
|EfficientNet_b1_vaiq|PASS|compiled_inference|
|EfficientNet_b2_vaiq|Numerics|compiled_inference|
|bat_resnext26ts.ch_in1k|PASS|compiled_inference|
|beit_base_patch16_224.in22k_ft_in22k_in1k|PASS|compiled_inference|
|beit_base_patch16_384.in22k_ft_in22k_in1k|PASS|compiled_inference|
|migraphx_ORT__bert_base_cased_1|PASS|compiled_inference|
|migraphx_ORT__bert_base_uncased_1|PASS|compiled_inference|
|model--Bartlarge--Shubham09|PASS|Numerics|
|model--bert-finetuned-squad--kenyaari|PASS|compiled_inference|
|model--bert-finetuned-squad--krolis|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nachowdh|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nastorian|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nazirzhumakhan|PASS|compiled_inference|
|model--finetuning-sentiment-model-3000-samples--nhero|PASS|compiled_inference|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|
|resnet200d_train_vaiq|PASS|compiled_inference|
|resnet200d_vaiq|PASS|compiled_inference|
|resnet26_test_vaiq|PASS|compiled_inference|
|resnet26_vaiq|PASS|compiled_inference|

## 14 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ecaresnetlight_vaiq|compiled_inference|PASS|
|model--deberta-italian-question-answering--osiria|Numerics|PASS|
|model--deberta-v3-base-qa-en--LLukas22|Numerics|PASS|
|model--deberta-v3-base-squad2--deepset|Numerics|PASS|
|model--deberta-v3-base-squad2--navteca|Numerics|PASS|
|model--deberta-v3-base__sst2__all-train--SetFit|Numerics|PASS|
|model--deberta-v3-large-squad2--deepset|Numerics|PASS|
|model--deberta-v3-large-squad2--sjrhuschlee|Numerics|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|Numerics|PASS|
|model--deberta_squadnewsqa--sophiebottani|Numerics|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|Numerics|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|Numerics|PASS|
|model--outputs--ankitkupadhyay|Numerics|PASS|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|Numerics|PASS|

