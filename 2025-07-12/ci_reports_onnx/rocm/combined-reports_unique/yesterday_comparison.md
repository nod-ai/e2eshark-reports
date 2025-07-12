# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|126.9847|121.7365|-5.2482|-4.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|121.4957|120.735|-0.7607|-0.63%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|856.4622|538.2248|-318.2375|-37.16%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|71.1071|68.9318|-2.1753|-3.06%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|88.7632|66.3919|-22.3713|-25.2%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|339.9636|340.2362|0.2726|0.08%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|34.8396|34.7201|-0.1195|-0.34%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3786|19.3417|-0.0368|-0.19%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.504|3.4971|-0.007|-0.2%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6809|19.8192|0.1383|0.7%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2861|4.1652|-0.1209|-2.82%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|6.9466|6.9922|0.0456|0.66%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.1812|25.6675|-0.5137|-1.96%|
|migraphx_mlperf__resnet50_v1|Numerics|progression|17.2613|14.1851|-3.0761|-17.82%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|42.4958|41.5745|-0.9213|-2.17%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|102.6535|103.2667|0.6132|0.6%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|17.8714|19.4509|1.5795|8.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|10.5528|9.1859|-1.3669|-12.95%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.6772|13.6008|-0.0764|-0.56%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.2375|3.0914|-0.1461|-4.51%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0627|2.058|-0.0046|-0.22%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|35.8955|25.7975|-10.098|-28.13%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.2887|37.0877|-0.201|-0.54%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|56.054|55.8843|-0.1697|-0.3%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|15.5412|12.5828|-2.9584|-19.04%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|21.1804|12.6943|-8.4861|-40.07%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|26.0315|19.2308|-6.8007|-26.12%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.9232|12.7702|-0.153|-1.18%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|19.3734|25.4721|6.0987|31.48%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.6103|19.6557|0.0453|0.23%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|47.6337|36.0771|-11.5566|-24.26%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|68.8339|69.2297|0.3958|0.58%|
|migx_bench_bert-large-uncased_32_384|PASS|progression|153.9666|110.591|-43.3756|-28.17%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.4529|19.3055|-0.1474|-0.76%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.062|20.1167|0.0547|0.27%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|37.5649|23.1769|-14.388|-38.3%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1518|20.2993|0.1474|0.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|25.9434|26.0175|0.0741|0.29%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5025|32.4104|-0.0921|-0.28%|

## 11 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|cait_s36_384|PASS|Numerics|
|convnext_large_in22k_Opset18_timm|PASS|Numerics|
|feastconv_Opset17_graph_convolutions|PASS|compilation|
|nezha_Opset16_transformers|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|resnet101_Opset17_timm|PASS|Numerics|
|robertaprelayernorm_Opset18_transformers|PASS|Numerics|
|tf_efficientnet_l2.ns_jft_in1k|PASS|Numerics|
|tf_efficientnetv2_s_in21k_Opset16_timm|PASS|Numerics|
|xlnetlmhead_Opset16_transformers|PASS|Numerics|
|zfnet512-12|PASS|Numerics|

## 31 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|beit_large_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|convit_base_Opset17_timm|Numerics|PASS|
|convnext_base_384_in22ft1k_Opset16_timm|Numerics|PASS|
|convnext_base_Opset17_torch_hub|Numerics|PASS|
|convnext_tiny_in22k_Opset16_timm|Numerics|PASS|
|convnext_xlarge_in22ft1k_Opset17_timm|Numerics|PASS|
|deit_base_patch16_224.fb_in1k|Numerics|PASS|
|efficientnetv2_rw_m_Opset16_timm|Numerics|PASS|
|encoderdecoder_Opset16_transformers|Numerics|PASS|
|fcn-resnet50-12|Numerics|PASS|
|luke_Opset16_transformers|Numerics|PASS|
|maxvit_small_tf_384.in1k|Numerics|PASS|
|migx_bench_bert-large-uncased_16_384|Numerics|PASS|
|migx_bench_bert-large-uncased_32_384|Numerics|PASS|
|migx_bench_bert-large-uncased_8_256|Numerics|PASS|
|model--bert-german-ner--lunesco|Numerics|PASS|
|model--deberta-v3-large-squad2--deepset|Numerics|PASS|
|model--distilbert-base-cased-distilled-squad--distilbert|Numerics|PASS|
|model--distilcamembert-base-qa--cmarkea|Numerics|PASS|
|model--enlm-roberta-imdb--manirai91|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|regnety_120.sw_in12k|Numerics|PASS|
|regnety_120_Opset17_timm|Numerics|PASS|
|regnety_160_Opset17_timm|Numerics|PASS|
|resnetrs420|Numerics|PASS|
|swin_base_patch4_window7_224_in22k_Opset17_timm|Numerics|PASS|
|swinv2_base_window8_256_Opset16_timm|Numerics|PASS|
|swinv2_small_window8_256_Opset16_timm|Numerics|PASS|
|switchtransformersencoder_Opset16_transformers|Numerics|PASS|
|vit_base_patch16_224_miil.in21k_ft_in1k|Numerics|PASS|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|Numerics|PASS|

