# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|107.631|107.6241|-0.0069|-0.01%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|106.738|108.9026|2.1646|2.03%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|457.5128|453.681|-3.8318|-0.84%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|59.972|60.026|0.0541|0.09%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|61.1253|63.1347|2.0094|3.29%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|241.2926|246.3712|5.0786|2.1%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.2669|34.4319|0.165|0.48%|
|migraphx_agentmodel__AgentModel|Numerics|within tol|2.145|2.0519|-0.0931|-4.34%|
|migraphx_bert__bert-large-uncased|PASS|within tol|18.9668|18.9298|-0.0369|-0.19%|
|migraphx_cadene__dpn92i1|PASS|within tol|5.0482|5.0403|-0.0079|-0.16%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|29.237|29.4803|0.2433|0.83%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|6.2345|6.2507|0.0162|0.26%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|29.7414|30.0056|0.2642|0.89%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.0276|7.3314|0.3038|4.32%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|26.7699|28.6412|1.8712|6.99%|
|migraphx_mlperf__resnet50_v1|PASS|progression|5.058|4.7973|-0.2607|-5.15%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|44.3993|43.7056|-0.6936|-1.56%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|46.3865|46.6455|0.259|0.56%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|16.2004|17.2863|1.0859|6.7%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.1149|5.7923|-1.3226|-18.59%|
|migraphx_torchvision__densenet121i32|PASS|within tol|18.0834|18.1814|0.098|0.54%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.922|4.8897|-0.0322|-0.66%|
|migraphx_torchvision__inceptioni32|PASS|within tol|28.0209|28.1798|0.1589|0.57%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.5653|3.6003|0.035|0.98%|
|migraphx_torchvision__resnet50i64|PASS|within tol|20.6315|21.043|0.4114|1.99%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|32.4628|33.2955|0.8327|2.57%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|53.3028|53.82|0.5172|0.97%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|70.2934|72.0356|1.7422|2.48%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.2651|12.3152|0.0501|0.41%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8087|12.6624|-0.1463|-1.14%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|45.3848|19.2514|-26.1334|-57.58%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.815|12.806|-0.0089|-0.07%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.4177|13.3515|-0.0663|-0.49%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|21.0591|21.0537|-0.0054|-0.03%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|60.6674|66.7122|6.0449|9.96%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|99.5659|100.6309|1.0651|1.07%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|140.9094|142.4619|1.5525|1.1%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|14.4932|14.6522|0.159|1.1%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|16.3726|17.174|0.8014|4.89%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.9866|25.6944|0.7079|2.83%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|19.1261|19.4568|0.3308|1.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.8049|27.4764|0.6715|2.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|39.0981|40.4252|1.3271|3.39%|

## No Regressions Found

## 13 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_2_256|Numerics|PASS|
|model--bart-base-cnn--ainize|Numerics|PASS|
|model--bert-finetuned-ner--Arthuerwang|Numerics|PASS|
|model--bert-finetuned-ner--lddczcn|Numerics|PASS|
|model--distilbert-base-cased-finetuned-ner--swardiantara|Numerics|PASS|
|model--distilbert-base-uncased_mod_squad--damapika|Numerics|PASS|
|model--marian-finetuned-kde4-en-to-fr--Yuch|Numerics|PASS|
|model--roberta-base-finetuned-squad-1--huxxx657|Numerics|PASS|
|regnety_160.sw_in12k|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|

