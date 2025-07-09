# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|122.4525|123.1552|0.7027|0.57%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|123.323|122.5693|-0.7537|-0.61%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|536.9731|538.0944|1.1213|0.21%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|69.459|69.5261|0.0671|0.1%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|66.5805|66.8712|0.2907|0.44%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|340.5566|352.3244|11.7677|3.46%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|34.6983|36.9188|2.2205|6.4%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.2787|19.2158|-0.0629|-0.33%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.4929|3.5148|0.0218|0.63%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|19.6767|19.7068|0.0301|0.15%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|4.1893|4.2664|0.0772|1.84%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|7.0182|7.5846|0.5664|8.07%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|26.6192|25.9989|-0.6204|-2.33%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.1499|14.009|-0.141|-1.0%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|45.4139|41.759|-3.6548|-8.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|103.4624|103.2747|-0.1877|-0.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|19.029|20.428|1.399|7.35%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|9.0899|9.2986|0.2087|2.3%|
|migraphx_torchvision__densenet121i32|PASS|within tol|13.695|13.59|-0.105|-0.77%|
|migraphx_torchvision__inceptioni1|PASS|within tol|3.1097|3.0531|-0.0566|-1.82%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0099|2.0201|0.0103|0.51%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|25.5441|25.7766|0.2325|0.91%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|37.1479|37.5462|0.3984|1.07%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|56.2926|57.102|0.8094|1.44%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.9872|12.5347|-0.4526|-3.48%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|12.8529|13.4749|0.622|4.84%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.306|19.3169|0.0109|0.06%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|12.9023|14.4645|1.5622|12.11%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.4719|19.3047|-0.1672|-0.86%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|19.794|19.7524|-0.0416|-0.21%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|35.7599|36.0279|0.268|0.75%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|69.7452|70.1101|0.3649|0.52%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|110.6771|110.875|0.1978|0.18%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|19.3003|19.4248|0.1245|0.65%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|20.3073|19.9681|-0.3391|-1.67%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|23.3648|23.4037|0.0389|0.17%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.2052|20.1653|-0.0399|-0.2%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|26.0697|26.1378|0.0681|0.26%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|32.5525|32.5548|0.0023|0.01%|

## 17 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|biogpt_Opset17_transformers|PASS|Numerics|
|cait_m48_448_Opset16_timm|PASS|Numerics|
|convbert_Opset16_transformers|PASS|compilation|
|convbert_Opset17_transformers|PASS|compilation|
|convnext_base.clip_laion2b|PASS|Numerics|
|deit3_large_patch16_224.fb_in1k|PASS|Numerics|
|deit3_large_patch16_384.fb_in1k|PASS|Numerics|
|model--deberta-v3-base-qa-en--LLukas22|PASS|Numerics|
|model--distilbert-base-NER--51la5|PASS|Numerics|
|model--flan-t5-large-samsum--oguuzhansahin|PASS|Numerics|
|model--mbert-bengali-ner--sagorsarker|PASS|Numerics|
|model--pegasus-large-book-summary--pszemraj|PASS|Numerics|
|model--smol_llama-220M-GQA--BEE-spoke-data|PASS|Numerics|
|openaigptlmhead_Opset17_transformers|PASS|Numerics|
|regnet_x_32gf_Opset16_torch_hub|PASS|compilation|
|tf_efficientnet_l2.ns_jft_in1k|PASS|Numerics|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|PASS|Numerics|

## 7 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|migraphx_ORT__bert_large_uncased_1|Numerics|PASS|
|model--bert-base-finetuned-nli--Jihyun22|Numerics|PASS|
|model--distilbart-xsum-12-1--sshleifer|Numerics|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|PASS|
|resnetrs270_Opset17_timm|Numerics|PASS|
|xcit_large_24_p8_224_Opset17_timm|Numerics|PASS|

