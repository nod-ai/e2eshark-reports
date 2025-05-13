# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|117.6346|117.8756|0.2411|0.2%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|117.3087|117.879|0.5702|0.49%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|520.243|521.5084|1.2654|0.24%|
|migraphx_ORT__distilgpt2_1|PASS|progression|74.1283|68.6562|-5.4721|-7.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|64.1158|63.2505|-0.8653|-1.35%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|312.3431|306.4837|-5.8593|-1.88%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8587|35.2994|0.4407|1.26%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1419|19.1504|0.0086|0.04%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.7575|3.7989|0.0414|1.1%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|27.291|27.2163|-0.0746|-0.27%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.4567|4.4403|-0.0164|-0.37%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.4419|6.9908|-0.4511|-6.06%|
|migraphx_mlperf__bert_large_mlperf|PASS|regression|26.866|28.7794|1.9134|7.12%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|13.9356|14.0579|0.1223|0.88%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|39.7716|40.9425|1.1709|2.94%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|128.678|130.2583|1.5803|1.23%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|20.0227|19.2795|-0.7432|-3.71%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.0452|8.6695|-0.3756|-4.15%|
|migraphx_torchvision__densenet121i32|PASS|within tol|17.7346|17.6988|-0.0358|-0.2%|
|migraphx_torchvision__inceptioni1|PASS|within tol|4.3634|4.3396|-0.0237|-0.54%|
|migraphx_torchvision__resnet50i1|PASS|within tol|3.154|3.1925|0.0385|1.22%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|27.8795|27.2784|-0.6011|-2.16%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|40.3003|39.2862|-1.0141|-2.52%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|59.4969|58.2092|-1.2877|-2.16%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.4741|12.2296|-0.2445|-1.96%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.2932|12.5461|0.2529|2.06%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3604|19.3627|0.0022|0.01%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.5934|12.478|-0.1154|-0.92%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4185|19.1834|-0.235|-1.21%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|20.4405|20.1662|-0.2743|-1.34%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|39.0353|38.4689|-0.5663|-1.45%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|75.6286|73.7451|-1.8835|-2.49%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|118.4939|115.3885|-3.1055|-2.62%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.6331|19.6697|0.0366|0.19%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.9321|20.6856|-0.2465|-1.18%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|24.634|24.4091|-0.2248|-0.91%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|20.9104|38.5534|17.643|84.37%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|28.4506|27.898|-0.5526|-1.94%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|35.53|34.5062|-1.0238|-2.88%|

## 21 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_small.in12k|PASS|Numerics|
|dm_nfnet_f2_Opset16_timm|PASS|Numerics|
|eca_nfnet_l1.ra2_in1k_train_vaiq|PASS|compiled_inference|
|eca_resnext26ts_Opset17_timm|PASS|compiled_inference|
|ecaresnet101d_Opset16_timm|PASS|compiled_inference|
|ecaresnet26t_train_vaiq|PASS|compiled_inference|
|ecaresnet26t_vaiq|PASS|compiled_inference|
|ecaresnetlight_Opset17_timm|PASS|compiled_inference|
|gernet_s_Opset18_timm|PASS|compiled_inference|
|migx_bench_bert-large-uncased_16_384|PASS|Numerics|
|migx_bench_bert-large-uncased_32_384|PASS|Numerics|
|mobilevitv2_150_384_in22ft1k_Opset16_timm|PASS|compilation|
|mobilevitv2_175_384_in22ft1k_Opset17_timm|PASS|compilation|
|mobilevitv2_200_384_in22ft1k_Opset18_timm|PASS|compilation|
|model--FinancialBERT-Sentiment-Analysis--ahmedrachid|PASS|Numerics|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|PASS|Numerics|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|PASS|Numerics|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|PASS|compiled_inference|
|swin_base_patch4_window12_384_Opset16_timm|PASS|Numerics|
|swinv2_base_window8_256_Opset16_timm|PASS|Numerics|
|xcit_medium_24_p16_384_dist_Opset16_timm|PASS|Numerics|

## 5 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convit_base|Numerics|PASS|
|ecaresnet50t_Opset16_timm|compiled_inference|PASS|
|migraphx_mlperf__bert_large_mlperf|Numerics|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224_Opset17_timm|Numerics|PASS|

