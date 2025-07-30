# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_bert__bert-large-uncased|PASS|within tol|387.9436|375.9953|-11.9483|-3.08%|
|migraphx_cadene__dpn92i1|PASS|within tol|166.5924|166.3471|-0.2453|-0.15%|
|migraphx_cadene__inceptionv4i16|PASS|regression|5344.7171|5741.7573|397.0402|7.43%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|319.1074|317.6264|-1.4811|-0.46%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|414.9823|430.5441|15.5619|3.75%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|437.6396|451.4221|13.7825|3.15%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|96.45|93.2621|-3.1878|-3.31%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|61.2781|65.0221|3.744|6.11%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|217.5571|230.6694|13.1123|6.03%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|1451.6452|66.6039|-1385.0413|-95.41%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|18.1268|19.9172|1.7904|9.88%|
|migraphx_torchvision__densenet121i32|PASS|regression|1551.567|1642.4481|90.8811|5.86%|
|migraphx_torchvision__inceptioni1|PASS|within tol|189.8328|189.6857|-0.147|-0.08%|
|migraphx_torchvision__resnet50i1|PASS|progression|250.6816|83.4684|-167.2132|-66.7%|
|migx_bench_bert-large-uncased_16_128|PASS|regression|1549.4601|1643.7009|94.2408|6.08%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|5335.5735|6621.2505|1285.677|24.1%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9398.108|9595.5387|197.4307|2.1%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|144.9813|147.9065|2.9252|2.02%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|258.243|250.3612|-7.8818|-3.05%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|1130.8785|367.0368|-763.8418|-67.54%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|239.1208|261.689|22.5682|9.44%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|424.646|436.721|12.0749|2.84%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|655.4299|669.431|14.0011|2.14%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5048.2589|5196.697|148.4381|2.94%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|13786.3192|14039.0147|252.6955|1.83%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|24072.9593|23618.0713|-454.888|-1.89%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|447.1994|402.9401|-44.2592|-9.9%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|857.3333|790.9374|-66.3959|-7.74%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1274.3432|1233.0134|-41.3298|-3.24%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|747.2224|1156.9756|409.7533|54.84%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1664.3005|1661.0049|-3.2956|-0.2%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3457.7202|3446.0137|-11.7065|-0.34%|

## 13 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|regnetz_c16_evos.ch_in1k_train_vaiq|Numerics|compilation|
|regnetz_c16_evos.ch_in1k_vaiq|Numerics|compilation|
|regnetz_c16_evos_Opset16_timm|Numerics|compilation|
|regnetz_d8_evos.ch_in1k_train_vaiq|Numerics|compilation|
|regnetz_d8_evos.ch_in1k_vaiq|Numerics|compilation|
|regnetz_d8_evos_Opset16_timm|Numerics|compilation|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|compilation|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|compilation|
|swinv2_base_window8_256_Opset17_timm|PASS|compilation|
|swinv2_small_window8_256_Opset16_timm|PASS|compilation|
|swinv2_small_window8_256_Opset17_timm|PASS|compilation|
|swinv2_tiny_window8_256_Opset16_timm|PASS|compilation|
|swinv2_tiny_window8_256_Opset17_timm|PASS|compilation|

## 202 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ConvNeXt_vaiq_int8|compilation|Numerics|
|coat_lite_mini|compilation|PASS|
|coat_lite_mini_Opset18_timm|compilation|PASS|
|coat_lite_small|compilation|PASS|
|coat_lite_small_Opset16_timm|compilation|PASS|
|coat_lite_small_Opset17_timm|compilation|PASS|
|coat_lite_tiny|compilation|PASS|
|coat_lite_tiny_Opset16_timm|compilation|PASS|
|coat_lite_tiny_Opset17_timm|compilation|PASS|
|coat_mini|compilation|PASS|
|coat_mini_Opset16_timm|compilation|PASS|
|coat_mini_Opset18_timm|compilation|PASS|
|coat_tiny|compilation|PASS|
|coat_tiny_Opset16_timm|compilation|PASS|
|coat_tiny_Opset18_timm|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_1_rw_224.sw_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|compilation|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|compilation|PASS|
|convnext_base_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_base_384_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_base_Opset16_torch_hub|compilation|PASS|
|convnext_base_Opset17_torch_hub|compilation|PASS|
|convnext_base_in22ft1k_Opset17_timm|compilation|PASS|
|convnext_base_in22k_Opset16_timm|compilation|PASS|
|convnext_base_in22k_Opset17_timm|compilation|PASS|
|convnext_large.fb_in1k|compilation|PASS|
|convnext_large_384_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_large_Opset16_timm|compilation|PASS|
|convnext_large_Opset16_torch_hub|compilation|PASS|
|convnext_large_Opset18_torch_hub|compilation|PASS|
|convnext_large_in22k_Opset16_timm|compilation|PASS|
|convnext_small.fb_in1k|compilation|PASS|
|convnext_small.in12k|compilation|PASS|
|convnext_small_Opset16_timm|compilation|PASS|
|convnext_small_Opset16_torch_hub|compilation|PASS|
|convnext_small_Opset17_timm|compilation|PASS|
|convnext_small_Opset17_torch_hub|compilation|PASS|
|convnext_small_Opset18_torch_hub|compilation|PASS|
|convnext_small_in22k_Opset16_timm|compilation|PASS|
|convnext_small_in22k_Opset17_timm|compilation|PASS|
|convnext_tiny.fb_in1k|compilation|PASS|
|convnext_tiny.in12k|compilation|PASS|
|convnext_tiny_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_tiny_Opset16_timm|compilation|PASS|
|convnext_tiny_Opset16_torch_hub|compilation|PASS|
|convnext_tiny_Opset18_torch_hub|compilation|PASS|
|convnext_tiny_in22ft1k_Opset18_timm|compilation|PASS|
|convnext_tiny_in22k_Opset16_timm|compilation|PASS|
|convnext_tiny_in22k_Opset17_timm|compilation|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|compilation|PASS|
|convnext_xlarge_in22k_Opset16_timm|compilation|PASS|
|davit_base.msft_in1k|compilation|PASS|
|davit_small.msft_in1k|compilation|PASS|
|davit_tiny.msft_in1k|compilation|PASS|
|edgenext_base|compilation|PASS|
|edgenext_small|compilation|PASS|
|edgenext_small_rw|compilation|PASS|
|edgenext_x_small|compilation|PASS|
|edgenext_xx_small|compilation|PASS|
|efficientformer_l1.snap_dist_in1k|compilation|PASS|
|efficientformer_l3.snap_dist_in1k|compilation|PASS|
|efficientformer_l7.snap_dist_in1k|compilation|PASS|
|gpt2-lm-head-10|compilation|PASS|
|levit_128s_Opset16_timm|compilation|PASS|
|levit_192_Opset16_timm|compilation|PASS|
|levit_256_Opset16_timm|compilation|PASS|
|levit_384_Opset16_timm|compilation|PASS|
|migraphx_ORT__bert_base_cased_1|compilation|PASS|
|migraphx_ORT__bert_base_uncased_1|compilation|PASS|
|migraphx_ORT__bert_large_uncased_1|compilation|PASS|
|migraphx_ORT__distilgpt2_1|compilation|PASS|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|compilation|Numerics|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|compilation|Numerics|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|compilation|Numerics|
|model--125M_GPTneo_reward_base--Myashka|compilation|PASS|
|model--BERT_summary--Shobhank-iiitdwd|compilation|PASS|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|compilation|PASS|
|model--CodeGen-350M-Multi--xhyi|compilation|PASS|
|model--Electra-Large-SQUADV2--titanbot|compilation|PASS|
|model--EstBERT128_sentiment--tartuNLP|compilation|PASS|
|model--FinancialBERT-Sentiment-Analysis--ahmedrachid|compilation|PASS|
|model--GPyT--Sentdex|compilation|PASS|
|model--IMDB_ELECTRA_5E--pig4431|compilation|PASS|
|model--Jasmine-350M--UBC-NLP|compilation|PASS|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|compilation|PASS|
|model--MEDIA_NLU-flaubert_oral_mixed--vpelloin|compilation|PASS|
|model--Microllama_Char_200k_step--Corianas|compilation|PASS|
|model--MiniLM-L12-H384-uncased-squad--haritzpuerto|compilation|PASS|
|model--QAmembert--CATIE-AQ|compilation|PASS|
|model--SAE-roberta-base-squad--jgammack|compilation|PASS|
|model--SEAD-L-6_H-384_A-12-wnli--course5i|compilation|PASS|
|model--TinyBERT_General_4L_312D-squad--haritzpuerto|compilation|PASS|
|model--TinyMistral-248M-v2-cleaner--M4-ai|compilation|PASS|
|model--TinyStories-1Layer-21M--roneneldan|compilation|PASS|
|model--TinyStories-1M--roneneldan|compilation|PASS|
|model--TinyStories-2Layers-33M--roneneldan|compilation|PASS|
|model--TinyStories-33M--roneneldan|compilation|PASS|
|model--TinyStories-3M--roneneldan|compilation|PASS|
|model--TinyStories-8M--roneneldan|compilation|PASS|
|model--XLMRoberta-Alexa-Intents-NER-NLU--qanastek|compilation|PASS|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|compilation|PASS|
|model--YuisekinAI-mistral-0.7B--yuiseki|compilation|PASS|
|model--albert-base-v2-finetuned-ner--ArBert|compilation|PASS|
|model--albert-base-v2-finetuned-squad--Firat|compilation|PASS|
|model--albert-large-v2_ner_conll2003--Gladiator|compilation|PASS|
|model--albert-large-v2_ner_wikiann--Gladiator|compilation|PASS|
|model--albert-large-v2_squad--Palak|compilation|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|compilation|PASS|
|model--bengali_language_NER--Suchandra|compilation|PASS|
|model--bert-base-cased-cefr--LordCoffee|compilation|PASS|
|model--bert-base-finetuned-nli--Jihyun22|compilation|PASS|
|model--bert-base-multilingual-uncased-finetuned-squad--Martin97Bozic|compilation|PASS|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3--husnu|compilation|PASS|
|model--bert-base-turkish-128k-cased-finetuned_lr-2e-05_epochs-3TQUAD2-finetuned_lr-2e-05_epochs-1--husnu|compilation|PASS|
|model--bert-base-tweetner7-2021--tner|compilation|PASS|
|model--bert-base-uncased-imdb--fabriceyhc|compilation|PASS|
|model--bert-base-uncased-squad-v1--csarron|compilation|PASS|
|model--bert-cased-ner-fcit499--Ahmed87|compilation|PASS|
|model--bert-finetuned-chunking--ish97|compilation|PASS|
|model--bert-finetuned-imdb--Wakaka|compilation|PASS|
|model--bert-finetuned-ner--jatinshah|compilation|PASS|
|model--bert-finetuned-ner_offres--bileldh|compilation|PASS|
|model--bert-finetuned-squad--Aaroosh|compilation|PASS|
|pit_b_224_Opset16_timm|compilation|PASS|
|pit_b_224_Opset17_timm|compilation|PASS|
|pit_b_distilled_224_Opset16_timm|compilation|PASS|
|pit_b_distilled_224_Opset18_timm|compilation|PASS|
|pit_s_224_Opset16_timm|compilation|PASS|
|pit_s_distilled_224_Opset16_timm|compilation|PASS|
|pit_s_distilled_224_Opset17_timm|compilation|PASS|
|pit_ti_224_Opset16_timm|compilation|PASS|
|pit_ti_224_Opset17_timm|compilation|PASS|
|pit_ti_distilled_224_Opset16_timm|compilation|PASS|
|pit_ti_distilled_224_Opset17_timm|compilation|PASS|
|pit_xs_224_Opset16_timm|compilation|PASS|
|pit_xs_224_Opset18_timm|compilation|PASS|
|pit_xs_distilled_224_Opset18_timm|compilation|PASS|
|roberta-base-11|compilation|PASS|
|roberta-sequence-classification-9|compilation|PASS|
|swin_b_Opset16_torch_hub|compilation|PASS|
|swin_base_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_base_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_base_patch4_window7_224_in22k_Opset17_timm|compilation|PASS|
|swin_large_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_large_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_large_patch4_window7_224_in22k_Opset17_timm|compilation|PASS|
|swin_s3_base_224_Opset16_timm|compilation|PASS|
|swin_s3_base_224_Opset17_timm|compilation|PASS|
|swin_s3_small_224_Opset16_timm|compilation|PASS|
|swin_s3_small_224_Opset17_timm|compilation|PASS|
|swin_s3_tiny_224_Opset16_timm|compilation|PASS|
|swin_s3_tiny_224_Opset17_timm|compilation|PASS|
|swin_s_Opset16_torch_hub|compilation|PASS|
|swin_small_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_small_patch4_window7_224_Opset17_timm|compilation|PASS|
|swin_t_Opset16_torch_hub|compilation|PASS|
|swin_t_Opset18_torch_hub|compilation|PASS|
|swin_tiny_patch4_window7_224_Opset16_timm|compilation|PASS|
|swin_tiny_patch4_window7_224_Opset17_timm|compilation|PASS|
|swinv2_cr_small_224_Opset16_timm|compilation|PASS|
|swinv2_cr_small_224_Opset18_timm|compilation|PASS|
|swinv2_cr_small_ns_224_Opset16_timm|compilation|PASS|
|swinv2_cr_tiny_ns_224_Opset16_timm|compilation|PASS|
|swinv2_cr_tiny_ns_224_Opset18_timm|compilation|PASS|
|twins_pcpvt_base|compilation|PASS|
|twins_pcpvt_base_Opset17_timm|compilation|PASS|
|twins_pcpvt_large|compilation|PASS|
|twins_pcpvt_large_Opset16_timm|compilation|PASS|
|twins_pcpvt_large_Opset17_timm|compilation|PASS|
|twins_pcpvt_small|compilation|PASS|
|twins_pcpvt_small_Opset16_timm|compilation|PASS|
|twins_svt_base|compilation|PASS|
|twins_svt_base_Opset16_timm|compilation|PASS|
|twins_svt_large|compilation|PASS|
|twins_svt_large_Opset17_timm|compilation|PASS|
|twins_svt_small|compilation|PASS|
|twins_svt_small_Opset16_timm|compilation|PASS|
|twins_svt_small_Opset17_timm|compilation|PASS|
|vit_b_32_Opset18_torch_hub|compilation|PASS|
|vit_base_patch32_224.augreg_in1k|compilation|PASS|
|vit_base_patch32_224_Opset16_timm|compilation|PASS|
|vit_base_patch32_224_in21k_Opset16_timm|compilation|PASS|
|vit_base_patch32_224_in21k_Opset17_timm|compilation|PASS|
|vit_base_patch32_clip_224.laion2b|compilation|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|compilation|PASS|
|vit_l_32_Opset17_torch_hub|compilation|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_small_patch32_224_Opset17_timm|compilation|PASS|
|vit_small_patch32_224_in21k_Opset17_timm|compilation|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_medium_patch16_224_Opset17_timm|compilation|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset16_timm|compilation|PASS|
|vit_srelpos_small_patch16_224_Opset17_timm|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|

