# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|Numerics|within tol|123.1552|122.2421|-0.9131|-0.74%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|122.5693|250.5464|127.9771|104.41%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|538.0944|921.8019|383.7074|71.31%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.5261|69.1111|-0.4151|-0.6%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.8712|66.9964|0.1251|0.19%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|352.3244|342.4682|-9.8561|-2.8%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|36.9188|34.3149|-2.6039|-7.05%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2158|19.378|0.1622|0.84%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5148|3.4427|-0.0721|-2.05%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.7068|19.7768|0.07|0.36%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.2664|4.1893|-0.0772|-1.81%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|7.5846|7.044|-0.5407|-7.13%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.9989|26.4912|0.4923|1.89%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.009|14.0501|0.0412|0.29%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|41.759|41.8856|0.1265|0.3%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.2747|103.7119|0.4372|0.42%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|20.428|17.599|-2.829|-13.85%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.2986|10.2187|0.92|9.89%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.59|13.633|0.043|0.32%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.0531|3.0677|0.0146|0.48%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0201|2.0362|0.0161|0.8%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.7766|25.8992|0.1227|0.48%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.5462|36.8387|-0.7075|-1.88%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|57.102|55.3445|-1.7575|-3.08%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.5347|12.7427|0.2081|1.66%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|13.4749|12.7461|-0.7288|-5.41%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.3169|19.4066|0.0897|0.46%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|14.4645|12.9175|-1.547|-10.7%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.3047|19.1146|-0.1901|-0.98%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.7524|19.5984|-0.1539|-0.78%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|36.0279|35.5793|-0.4486|-1.25%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|70.1101|68.5793|-1.5308|-2.18%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|110.875|109.5504|-1.3246|-1.19%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|19.4248|30.4163|10.9914|56.58%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|19.9681|20.1256|0.1574|0.79%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.4037|23.2483|-0.1553|-0.66%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1653|20.1587|-0.0066|-0.03%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.1378|26.0757|-0.062|-0.24%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5548|32.3528|-0.202|-0.62%|

## 10 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_xlarge_in22ft1k_Opset17_timm|PASS|Numerics|
|migraphx_ORT__bert_base_cased_1|PASS|Numerics|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|Numerics|
|model--lsg-bart-base-4096-booksum--ccdv|PASS|Numerics|
|mvitv2_base|PASS|compilation|
|mvitv2_small|PASS|compilation|
|mvitv2_tiny|PASS|compilation|
|regnet_x_16gf_Opset18_torch_hub|PASS|Numerics|
|swin_large_patch4_window12_384_Opset16_timm|PASS|Numerics|
|vit_relpos_base_patch16_224_Opset16_timm|PASS|Numerics|

## 15 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset17_transformers|Numerics|PASS|
|cait_m48_448_Opset16_timm|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|deit3_large_patch16_224.fb_in1k|Numerics|PASS|
|deit3_large_patch16_384.fb_in1k|Numerics|PASS|
|gcvit_small|Numerics|PASS|
|model--deberta-v3-base-qa-en--LLukas22|Numerics|PASS|
|model--distilbert-base-NER--51la5|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--mbert-bengali-ner--sagorsarker|Numerics|PASS|
|model--pegasus-large-book-summary--pszemraj|Numerics|PASS|
|model--smol_llama-220M-GQA--BEE-spoke-data|Numerics|PASS|
|openaigptlmhead_Opset17_transformers|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|

