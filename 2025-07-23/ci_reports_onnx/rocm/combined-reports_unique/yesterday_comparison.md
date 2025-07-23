# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|112.4615|648.8072|536.3457|476.91%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|111.9553|129.2595|17.3041|15.46%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|1051.6694|1274.6361|222.9667|21.2%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|67.4808|68.1733|0.6925|1.03%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|63.7039|62.56|-1.1439|-1.8%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|271.167|293.7102|22.5432|8.31%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|36.0265|36.5099|0.4834|1.34%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.1719|19.2929|0.121|0.63%|
|migraphx_cadene__dpn92i1|PASS|within tol|3.5013|3.4915|-0.0099|-0.28%|
|migraphx_cadene__inceptionv4i16|PASS|progression|90.0738|20.2984|-69.7754|-77.46%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|4.2129|4.4888|0.2759|6.55%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|7.3267|7.3274|0.0007|0.01%|
|migraphx_mlperf__bert_large_mlperf|PASS|within tol|25.9853|26.9016|0.9163|3.53%|
|migraphx_mlperf__resnet50_v1|Numerics|within tol|14.2472|14.056|-0.1912|-1.34%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|45.9773|42.6121|-3.3652|-7.32%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|105.4887|104.0652|-1.4236|-1.35%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|18.3698|20.1938|1.824|9.93%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|9.93|13.3971|3.4671|34.92%|
|migraphx_torchvision__densenet121i32|PASS|within tol|14.0264|14.6091|0.5827|4.15%|
|migraphx_torchvision__inceptioni1|PASS|progression|3.2646|3.0793|-0.1852|-5.67%|
|migraphx_torchvision__resnet50i1|PASS|within tol|2.0206|2.0884|0.0678|3.35%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|26.2166|26.7212|0.5046|1.92%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|41.8107|40.5316|-1.2791|-3.06%|
|migx_bench_bert-large-uncased_16_384|PASS|within tol|59.1589|59.2469|0.088|0.15%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|12.6015|12.8806|0.2791|2.21%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|39.4486|15.6475|-23.8011|-60.33%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|20.0159|22.35|2.3341|11.66%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|13.3785|13.7116|0.3331|2.49%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|19.0127|19.0318|0.0191|0.1%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|21.0413|23.2538|2.2125|10.52%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|41.2818|38.8773|-2.4045|-5.82%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|84.4984|72.3753|-12.1231|-14.35%|
|migx_bench_bert-large-uncased_32_384|PASS|within tol|114.8031|115.1253|0.3221|0.28%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|20.8558|19.4888|-1.3671|-6.55%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|21.4494|20.4684|-0.981|-4.57%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|27.1995|23.5882|-3.6113|-13.28%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|28.0199|20.4265|-7.5934|-27.1%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|27.4132|26.5378|-0.8754|-3.19%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|46.639|34.1014|-12.5375|-26.88%|

## 16 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_small_in22k_Opset17_timm|PASS|Numerics|
|gluon_resnet152_v1c_Opset17_timm|PASS|Numerics|
|model--bert-cased-ner-fcit499--Ahmed87|PASS|Numerics|
|model--dynamic_tinybert--Intel|PASS|Numerics|
|model--enlm-roberta-imdb--manirai91|PASS|Numerics|
|model--mdeberta-v3-base-squad2--sjrhuschlee|PASS|Numerics|
|mt5encoder_Opset17_transformers|PASS|Numerics|
|pit_s_distilled_224_Opset17_timm|PASS|Numerics|
|resnetrs101_Opset17_timm|PASS|Numerics|
|roformer_Opset16_transformers|PASS|Numerics|
|swin_base_patch4_window7_224_in22k_Opset17_timm|PASS|Numerics|
|swinv2_large_window12_192_22k_Opset17_timm|PASS|Numerics|
|tf_efficientnet_l2_ns_475_Opset17_timm|PASS|Numerics|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|PASS|Numerics|
|vit_large_patch16_224_Opset18_timm|PASS|Numerics|
|xcit_medium_24_p8_384_dist|PASS|Numerics|

## 23 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|crossvit_18_240_Opset16_timm|Numerics|PASS|
|deit_base_distilled_patch16_384_Opset18_timm|Numerics|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|migx_bench_bert-large-uncased_4_128|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|model--nbailab-base-ner-scandi--saattrupdan|Numerics|PASS|
|model--ner-bert-base-cased-pt-lenerbr--pierreguillou|Numerics|PASS|
|model--pythia-70m-toxicity-model--skrishna|Numerics|PASS|
|model--roberta-base-finetuned-mbti-0901--GItaf|Numerics|PASS|
|model--sberbank-rubert-base-collection3--viktoroo|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|openaigpt_Opset16_transformers|Numerics|PASS|
|opt_Opset18_transformers|Numerics|PASS|
|pit_s_224_Opset18_timm|Numerics|PASS|
|pit_xs_224|Numerics|PASS|
|pit_xs_224_Opset16_timm|Numerics|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|switchtransformersencoder_Opset16_transformers|Numerics|PASS|
|tf_efficientnetv2_l_in21ft1k_Opset17_timm|Numerics|PASS|
|twins_svt_large_Opset16_timm|Numerics|PASS|
|xlmroberta_Opset17_transformers|Numerics|PASS|

