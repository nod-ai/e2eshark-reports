# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.2421|126.9847|4.7426|3.88%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|250.5464|121.4957|-129.0507|-51.51%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|921.8019|856.4622|-65.3396|-7.09%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.1111|71.1071|1.996|2.89%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|66.9964|88.7632|21.7668|32.49%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|342.4682|339.9636|-2.5046|-0.73%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.3149|34.8396|0.5247|1.53%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.378|19.3786|0.0006|0.0%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4427|3.504|0.0613|1.78%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.7768|19.6809|-0.0959|-0.48%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1893|4.2861|0.0968|2.31%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.044|6.9466|-0.0974|-1.38%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.4912|26.1812|-0.31|-1.17%|
|migraphx_mlperf__resnet50_v1|Numerics|regression|14.0501|17.2613|3.2112|22.85%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.8856|42.4958|0.6102|1.46%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.7119|102.6535|-1.0584|-1.02%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|17.599|17.8714|0.2724|1.55%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|10.2187|10.5528|0.3341|3.27%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.633|13.6772|0.0442|0.32%|
|migraphx_torchvision__inceptioni1|PASS|regression|3.0677|3.2375|0.1698|5.54%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0362|2.0627|0.0264|1.3%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|25.8992|35.8955|9.9963|38.6%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|36.8387|37.2887|0.45|1.22%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|55.3445|56.054|0.7095|1.28%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|12.7427|15.5412|2.7984|21.96%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|12.7461|21.1804|8.4343|66.17%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|19.4066|26.0315|6.6249|34.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9175|12.9232|0.0058|0.04%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.1146|19.3734|0.2589|1.35%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.5984|19.6103|0.0119|0.06%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|35.5793|47.6337|12.0544|33.88%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|68.5793|68.8339|0.2546|0.37%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|109.5504|153.9666|44.4162|40.54%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|30.4163|19.4529|-10.9633|-36.04%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.1256|20.062|-0.0636|-0.32%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|23.2483|37.5649|14.3166|61.58%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1587|20.1518|-0.0069|-0.03%|
|migx_bench_bert-large-uncased_8_256|Numerics|within tol|26.0757|25.9434|-0.1323|-0.51%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.3528|32.5025|0.1497|0.46%|

## 29 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_224.in22k_ft_in22k_in1k|PASS|Numerics|
|convit_base_Opset17_timm|PASS|Numerics|
|convnext_base_384_in22ft1k_Opset16_timm|PASS|Numerics|
|convnext_base_Opset17_torch_hub|PASS|Numerics|
|convnext_tiny_in22k_Opset16_timm|PASS|Numerics|
|deit_base_patch16_224.fb_in1k|PASS|Numerics|
|efficientnetv2_rw_m_Opset16_timm|PASS|Numerics|
|encoderdecoder_Opset16_transformers|PASS|Numerics|
|fcn-resnet50-12|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|luke_Opset16_transformers|PASS|Numerics|
|maxvit_small_tf_384.in1k|PASS|Numerics|
|migx_bench_bert-large-uncased_8_256|PASS|Numerics|
|model--bert-german-ner--lunesco|PASS|Numerics|
|model--deberta-v3-large-squad2--deepset|PASS|Numerics|
|model--distilbert-base-cased-distilled-squad--distilbert|PASS|Numerics|
|model--distilcamembert-base-qa--cmarkea|PASS|Numerics|
|model--enlm-roberta-imdb--manirai91|PASS|Numerics|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|PASS|Numerics|
|regnety_120.sw_in12k|PASS|Numerics|
|regnety_120_Opset17_timm|PASS|Numerics|
|regnety_160_Opset17_timm|PASS|Numerics|
|resnetrs420|PASS|Numerics|
|swin_base_patch4_window7_224_in22k_Opset17_timm|PASS|Numerics|
|swinv2_base_window8_256_Opset16_timm|PASS|Numerics|
|swinv2_small_window8_256_Opset16_timm|PASS|Numerics|
|switchtransformersencoder_Opset16_transformers|PASS|Numerics|
|vit_base_patch16_224_miil.in21k_ft_in1k|PASS|Numerics|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|migraphx_ORT__bert_base_cased_1|Numerics|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|Numerics|PASS|
|model--lsg-bart-base-4096-booksum--ccdv|Numerics|PASS|
|regnet_x_16gf_Opset18_torch_hub|Numerics|PASS|
|regnet_x_32gf_Opset16_torch_hub|compilation|PASS|
|swin_large_patch4_window12_384_Opset16_timm|Numerics|PASS|
|vit_relpos_base_patch16_224_Opset16_timm|Numerics|PASS|

