# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.632|101.4484|15.8164|18.47%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|101.0804|14.928|17.33%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.9527|501.1806|240.2279|92.06%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2671|54.2669|22.9998|73.56%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|83.0977|63.1394|-19.9584|-24.02%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|296.1129|52.0454|21.32%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|40.5572|32.7342|-7.823|-19.29%|
|migraphx_bert__bert-large-uncased|PASS|progression|410.0501|19.24|-390.8101|-95.31%|
|migraphx_cadene__dpn92i1|Numerics|progression|186.2736|42.4469|-143.8267|-77.21%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|149.2952|-7107.9064|-97.94%|
|migraphx_cadene__resnext101_64x4di1|Numerics|progression|330.1171|114.3818|-215.7353|-65.35%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|420.8|7.3784|-413.4216|-98.25%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|456.7549|24.3864|-432.3685|-94.66%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|34.3327|-6.5484|-16.02%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9736|172.0769|-10.8967|-5.96%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|70.2852|15.8733|-54.4119|-77.42%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.0543|5.9096|-35.1447|-85.61%|
|migraphx_torchvision__densenet121i32|Numerics|progression|1377.2882|76.4054|-1300.8828|-94.45%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|47.4254|-211.3172|-81.67%|
|migraphx_torchvision__inceptioni32|PASS|progression|6648.7116|100.1275|-6548.5842|-98.49%|
|migraphx_torchvision__resnet50i1|Numerics|progression|99.4756|11.3327|-88.1429|-88.61%|
|migraphx_torchvision__resnet50i64|Numerics|progression|6088.0794|193.8942|-5894.1852|-96.82%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2688.5782|36.5457|-2652.0326|-98.64%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4097.8175|60.1779|-4037.6396|-98.53%|
|migx_bench_bert-large-uncased_16_384|Numerics|progression|6359.273|81.9546|-6277.3184|-98.71%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|13.0337|-175.2202|-93.08%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|13.281|-367.6046|-96.51%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|392.6775|35.7285|-356.9491|-90.9%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|12.6216|-451.5558|-97.28%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.0645|13.2617|-632.8028|-97.95%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|845.906|21.913|-823.993|-97.41%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5134.5125|74.3035|-5060.209|-98.55%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8841.4288|114.9871|-8726.4416|-98.7%|
|migx_bench_bert-large-uncased_32_384|Numerics|progression|11939.3575|203.1121|-11736.2454|-98.3%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|745.4025|14.5084|-730.8941|-98.05%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1125.1086|18.1961|-1106.9126|-98.38%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|27.3758|-1721.8589|-98.43%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|20.8351|-1511.6199|-98.64%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|30.627|-2373.3393|-98.73%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3127.1362|44.9452|-3082.1911|-98.56%|

## 82 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|VideoResNet_vaiq_int8|PASS|Numerics|
|crossvit_18_dagger_408|PASS|compilation|
|crossvit_base_240|PASS|Numerics|
|densenet201|PASS|Numerics|
|dm_nfnet_f2.dm_in1k|PASS|Numerics|
|dm_nfnet_f3.dm_in1k|PASS|Numerics|
|dpn68b_test_vaiq|PASS|Numerics|
|dpn68b_vaiq|PASS|Numerics|
|ecaresnet269d|PASS|Numerics|
|efficientformer_l1.snap_dist_in1k|PASS|Numerics|
|efficientformer_l3.snap_dist_in1k|PASS|Numerics|
|focalnet_base_lrf.ms_in1k|PASS|Numerics|
|focalnet_base_srf.ms_in1k|PASS|Numerics|
|focalnet_small_lrf.ms_in1k|PASS|Numerics|
|focalnet_small_srf.ms_in1k|PASS|Numerics|
|focalnet_tiny_lrf.ms_in1k|PASS|Numerics|
|focalnet_tiny_srf.ms_in1k|PASS|Numerics|
|gcvit_base|PASS|Numerics|
|levit_128.fb_dist_in1k|PASS|Numerics|
|levit_128s.fb_dist_in1k|PASS|Numerics|
|levit_192.fb_dist_in1k|PASS|Numerics|
|levit_384.fb_dist_in1k|PASS|Numerics|
|levit_conv_128.fb_dist_in1k|PASS|Numerics|
|levit_conv_128s.fb_dist_in1k|PASS|Numerics|
|levit_conv_192.fb_dist_in1k|PASS|Numerics|
|levit_conv_384.fb_dist_in1k|PASS|Numerics|
|migraphx_bert__bertsquad-12|PASS|compilation|
|migraphx_cadene__dpn92i1|PASS|Numerics|
|migraphx_cadene__resnext101_64x4di1|PASS|Numerics|
|migraphx_mlperf__resnet50_v1|PASS|compilation|
|migraphx_sd__unet__model|compilation|import_model|
|migraphx_sdxl__unet__model|compilation|import_model|
|migraphx_torchvision__densenet121i32|PASS|Numerics|
|migraphx_torchvision__resnet50i1|PASS|Numerics|
|migraphx_torchvision__resnet50i64|PASS|Numerics|
|mobilevitv2_150_384_in22ft1k|Numerics|compilation|
|model--TinyStories-1M--roneneldan|PASS|Numerics|
|model--TinyStories-3M--roneneldan|PASS|Numerics|
|model--TinyStories-8M--roneneldan|PASS|Numerics|
|model--bart-large-cnn--facebook|PASS|Numerics|
|model--bert-base-uncased-squad-v1--csarron|PASS|setup|
|model--gemma-tiny-random--yujiepan|PASS|Numerics|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|Numerics|compilation|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|Numerics|compilation|
|model--m2m100_418M-fr--NDugar|PASS|setup|
|model--mT5_multilingual_XLSum--csebuetnlp|Numerics|setup|
|model--really-tiny-falcon-testing--fxmarty|PASS|Numerics|
|model--s2t-medium-librispeech-asr--facebook|PASS|compilation|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|Numerics|compilation|
|model--tiny-gpt2--taufeeque|PASS|Numerics|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|Numerics|
|model--tiny-random-FalconForCausalLM--illuin|PASS|Numerics|
|model--tiny-random-llama--IlyasMoutawwakil|PASS|Numerics|
|model--tiny-testing-falcon-alibi--fxmarty|PASS|Numerics|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|regnety_120.sw_in12k|PASS|Numerics|
|regnety_160.sw_in12k|PASS|Numerics|
|regnety_320.seer|PASS|Numerics|
|regnety_640.seer|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_c16_evos.ch_in1k_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_train_vaiq|PASS|Numerics|
|regnetz_d8_evos.ch_in1k_vaiq|PASS|Numerics|
|resnest200e|PASS|Numerics|
|resnet50_gn_test_vaiq|PASS|Numerics|
|resnetrs420|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|Numerics|
|resnetv2_50d_gn.ah_in1k_vaiq|PASS|Numerics|
|visformer_small|PASS|Numerics|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|PASS|Numerics|
|xcit_nano_12_p16_384_dist|Numerics|compilation|
|xcit_small_12_p16_384_dist|Numerics|compilation|
|xcit_small_24_p16_384_dist|Numerics|compilation|
|xcit_tiny_12_p8_384_dist|Numerics|compilation|
|xcit_tiny_24_p8_384_dist|Numerics|compilation|

## 396 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|bat_resnext26ts.ch_in1k|compilation|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|coatnet_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnext_nano_rw_224.sw_in1k|Numerics|PASS|
|convnext_atto.d2_in1k|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|convnext_base.clip_laion2b_augreg|Numerics|PASS|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_base.clip_laiona|Numerics|PASS|
|convnext_base.clip_laiona_320|Numerics|PASS|
|convnext_base.clip_laiona_augreg_320|Numerics|PASS|
|convnext_base.clip_laiona_augreg_ft_in1k_384|Numerics|PASS|
|convnext_base.fb_in1k|Numerics|PASS|
|convnext_base.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_base.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_femto.d1_in1k|Numerics|PASS|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_large.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k_384|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_320|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_ft_soup_320|Numerics|PASS|
|convnext_nano.d1h_in1k|Numerics|PASS|
|convnext_nano.in12k|Numerics|PASS|
|convnext_nano.in12k_ft_in1k|Numerics|PASS|
|convnext_pico.d1_in1k|Numerics|PASS|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_small.in12k_ft_in1k|Numerics|PASS|
|convnext_small.in12k_ft_in1k_384|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k_384|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k_384|Numerics|PASS|
|convnextv2_atto.fcmae|Numerics|PASS|
|convnextv2_atto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_base.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_femto.fcmae|Numerics|PASS|
|convnextv2_femto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_large.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_nano.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|convnextv2_pico.fcmae|Numerics|PASS|
|convnextv2_pico.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k_384|Numerics|PASS|
|davit_base.msft_in1k|Numerics|PASS|
|davit_small.msft_in1k|Numerics|PASS|
|davit_tiny.msft_in1k|Numerics|PASS|
|edgenext_base|Numerics|PASS|
|edgenext_small|Numerics|PASS|
|edgenext_x_small|Numerics|PASS|
|edgenext_xx_small|Numerics|PASS|
|efficientnet_b1_pruned.in1k|Numerics|PASS|
|efficientnet_b2_pruned.in1k|Numerics|PASS|
|efficientnet_b3_pruned.in1k|Numerics|PASS|
|efficientnet_b5.in12k_ft_in1k|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|maxvit_base_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxvit_base_tf_512.in1k|Numerics|PASS|
|maxvit_base_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_384.in1k|Numerics|PASS|
|maxvit_large_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxvit_large_tf_512.in21k_ft_in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|PASS|
|maxvit_small_tf_384.in1k|Numerics|PASS|
|maxvit_small_tf_512.in1k|Numerics|PASS|
|maxvit_tiny_tf_384.in1k|Numerics|PASS|
|maxvit_tiny_tf_512.in1k|Numerics|PASS|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|Numerics|
|mobilevitv2_075|Numerics|PASS|
|mobilevitv2_100|Numerics|PASS|
|mobilevitv2_125|Numerics|PASS|
|mobilevitv2_150|Numerics|PASS|
|mobilevitv2_150_in22ft1k|Numerics|PASS|
|mobilevitv2_175|Numerics|PASS|
|mobilevitv2_175_in22ft1k|Numerics|PASS|
|mobilevitv2_200|Numerics|PASS|
|mobilevitv2_200_in22ft1k|Numerics|PASS|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--Electra-Large-SQUADV2--titanbot|Numerics|PASS|
|model--IMDB_ELECTRA_5E--pig4431|Numerics|PASS|
|model--QAmembert--CATIE-AQ|Numerics|PASS|
|model--SAE-roberta-base-squad--jgammack|Numerics|PASS|
|model--XLMRoberta-Alexa-Intents-NER-NLU--qanastek|Numerics|PASS|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--ArBert|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--Jorgeutd|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--Firat|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--bdickson|Numerics|PASS|
|model--albert-base-v2-imdb--textattack|Numerics|PASS|
|model--albert-base-v2-imdb-calssification--XSY|Numerics|PASS|
|model--albert-base-v2-squad2--twmkn9|Numerics|PASS|
|model--albert-base-v2-squad_v2--squirro|Numerics|PASS|
|model--albert-base-v2_squad--Palak|Numerics|PASS|
|model--albert-large-v2_ner_conll2003--Gladiator|Numerics|PASS|
|model--albert-large-v2_ner_wikiann--Gladiator|Numerics|PASS|
|model--albert-large-v2_squad--Palak|Numerics|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|Numerics|PASS|
|model--bart-CaPE-xsum--praf-choub|Numerics|PASS|
|model--bart-large-cnn-samsum--philschmid|Numerics|PASS|
|model--bert-finetuned-squad22--makdong|Numerics|PASS|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|Numerics|PASS|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|Numerics|PASS|
|model--camembert-base-fquad--illuin|Numerics|PASS|
|model--camembert-base-squad-finetuned-on-runaways-fr--Nadav|Numerics|PASS|
|model--camembert-base-squad-fr--Nadav|Numerics|PASS|
|model--camembert-base-squadFR-fquad-piaf--etalab-ia|Numerics|PASS|
|model--camembert_squadFR_question_answering_tools_fr--AntoineD|Numerics|PASS|
|model--codegen-350M-mono--Salesforce|Numerics|PASS|
|model--codegen-350M-mono-4bit-qlora--iamtarun|Numerics|PASS|
|model--distilcamembert-base-ner--cmarkea|Numerics|PASS|
|model--distilcamembert-base-qa--cmarkea|Numerics|PASS|
|model--distilroberta-base-finetuned-wikitext2-SQuAD-qa-WandB2--Madhana|Numerics|PASS|
|model--distilroberta-base-ner-conll2003--philschmid|Numerics|PASS|
|model--distilroberta-base-ner-wikiann--philschmid|Numerics|PASS|
|model--distilroberta-base-squad_v2--squirro|Numerics|PASS|
|model--distilroberta-base_squad--Palak|Numerics|PASS|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|Numerics|PASS|
|model--distilroberta-squad--UKP-SQuARE|Numerics|PASS|
|model--electra-adversarial-squad--mlxen|Numerics|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|PASS|
|model--electra-base-discriminator_mod_quoref--damapika|Numerics|PASS|
|model--electra-base-discriminator_squad_mod--damapika|Numerics|PASS|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|Numerics|PASS|
|model--electra-base-squad2--deepset|Numerics|PASS|
|model--electra-contrastdata-squad--mlxen|Numerics|PASS|
|model--electra-distilled-qa--kasohrab|Numerics|PASS|
|model--electra-finetuned-cpgqa--hung200504|Numerics|PASS|
|model--electra-large-synqa--mbartolo|Numerics|PASS|
|model--electra-small-discriminator-finetuned-ner--dbsamu|Numerics|PASS|
|model--electra-small-discriminator-finetuned-squad--hankzhong|Numerics|PASS|
|model--electra-small-finetuned-squadv2--mrm8488|Numerics|PASS|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|Numerics|PASS|
|model--electra-srb-ner--Aleksandar|Numerics|PASS|
|model--enlm-roberta-imdb--manirai91|Numerics|PASS|
|model--environmental-claims--climatebert|Numerics|PASS|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--finetuning-movie-roberta--RIYAN94182|Numerics|PASS|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--finetuning-sentiment-model--Saberi|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--gm-ner-xlmrbase--CLTL|Numerics|PASS|
|model--google_electra-base-discriminator_squad--Palak|Numerics|PASS|
|model--google_electra-small-discriminator_squad--Palak|Numerics|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|PASS|
|model--mobilebert-squadv2--aware-ai|Numerics|PASS|
|model--mobilebert-uncased-finetuned-squadv2--mrm8488|Numerics|PASS|
|model--mobilebert_cola--Alireza1044|Numerics|PASS|
|model--mobilebert_mnli--Alireza1044|Numerics|PASS|
|model--mobilebert_mrpc--Alireza1044|Numerics|PASS|
|model--mobilebert_rte--Alireza1044|Numerics|PASS|
|model--mobilebert_sst2--Alireza1044|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|model--nd-qna--Trisert|Numerics|PASS|
|model--query_wellformedness_score--Ashishkr|Numerics|PASS|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-base-ca-cased-ner--projecte-aina|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-42--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-6--anas-awadalla|Numerics|PASS|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-8--anas-awadalla|Numerics|PASS|
|model--roberta-base-finetuned-deletion-squad-10--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-imdb--wrmurray|Numerics|PASS|
|model--roberta-base-finetuned-mbti-0901--GItaf|Numerics|PASS|
|model--roberta-base-finetuned-ner--dominiqueblok|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-10-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-15-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-scrambled-squad-5-new--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad--Firat|Numerics|PASS|
|model--roberta-base-finetuned-squad-1--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad-3--huxxx657|Numerics|PASS|
|model--roberta-base-finetuned-squad8000--HASAN55|Numerics|PASS|
|model--roberta-base-finetuned-squad_roberta_v3--seviladiguzel|Numerics|PASS|
|model--roberta-base-imdb--aychang|Numerics|PASS|
|model--roberta-base-spanish-sqac--IIC|Numerics|PASS|
|model--roberta-base-spanish-squades--IIC|Numerics|PASS|
|model--roberta-base-squad2--NewBreaker|Numerics|PASS|
|model--roberta-base-squad2--deepset|Numerics|PASS|
|model--roberta-base-squad2--syndi-models|Numerics|PASS|
|model--roberta-base-squad2-distilled--deepset|Numerics|PASS|
|model--roberta-base-squad2-nq--nlpconnect|Numerics|PASS|
|model--roberta-base_mod_quoref--damapika|Numerics|PASS|
|model--roberta-base_mod_squad--damapika|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--roberta-large-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|PASS|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|PASS|
|model--roberta-large-synqa--mbartolo|Numerics|PASS|
|model--roberta-large-synqa-ext--mbartolo|Numerics|PASS|
|model--roberta-large-tweetner7-all--tner|Numerics|PASS|
|model--roberta-large_ner_conll2003--Gladiator|Numerics|PASS|
|model--roberta-ner-multilingual--julian-schelb|Numerics|PASS|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|Numerics|PASS|
|model--roberta_large-ner-conll2003_0818_v0--mariolinml|Numerics|PASS|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|Numerics|PASS|
|model--roberta_qa_japanese--tsmatz|Numerics|PASS|
|model--slovakbert-ner--crabz|Numerics|PASS|
|model--small-e-czech-finetuned-ner-wikiann--richielo|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|compilation|PASS|
|model--summarization-not-evaluated--autoevaluate|Numerics|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|model--t5-small-booksum--cnicu|Numerics|PASS|
|model--t5-small-finetuned-cnn--ubikpt|Numerics|PASS|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|PASS|
|model--tinyroberta-squad2--deepset|Numerics|PASS|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|Numerics|PASS|
|model--twitter-roberta-base-emotion--cardiffnlp|Numerics|PASS|
|model--wikibert-finetuned-vsmec--ThuanPhong|Numerics|PASS|
|model--xlm-roberta-base-conll2003-en--Amir13|Numerics|PASS|
|model--xlm-roberta-base-conll2003-ner--Yaxin|Numerics|PASS|
|model--xlm-roberta-base-esg-ner--santoshvutukuri|Numerics|PASS|
|model--xlm-roberta-base-finetuned-conll2003--LecJackS|Numerics|PASS|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|Numerics|PASS|
|model--xlm-roberta-base-finetuned-squad--darshana1406|Numerics|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|PASS|
|model--xlm-roberta-base-squad2--deepset|Numerics|PASS|
|model--xlm-roberta-base-squad2-distilled--deepset|Numerics|PASS|
|model--xlm-roberta-base_squad--Palak|Numerics|PASS|
|model--xlm-roberta-conll2003--manirai91|Numerics|PASS|
|model--xlm-roberta-imdb--manirai91|Numerics|PASS|
|model--xlm-roberta-large-squad2--deepset|Numerics|PASS|
|model--xlm-roberta-ner-japanese--tsmatz|Numerics|PASS|
|model--xlm-roberta-qa-chaii--gokulkarthik|Numerics|PASS|
|model--xlmr-large-qa-fa--m3hrdadfi|Numerics|PASS|
|model--yelp_review_rating_reberta_base--Shunian|Numerics|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pvt_v2_b0|Numerics|PASS|
|pvt_v2_b1|Numerics|PASS|
|pvt_v2_b2|Numerics|PASS|
|pvt_v2_b2_li|Numerics|PASS|
|pvt_v2_b3|Numerics|PASS|
|pvt_v2_b4|Numerics|PASS|
|pvt_v2_b5|Numerics|PASS|
|rexnetr_200.sw_in12k|Numerics|PASS|
|rexnetr_300.sw_in12k|Numerics|PASS|
|tf_efficientnet_b1.aa_in1k|Numerics|PASS|
|tf_efficientnet_b1.ap_in1k|Numerics|PASS|
|tf_efficientnet_b1.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b2.aa_in1k|Numerics|PASS|
|tf_efficientnet_b2.ap_in1k|Numerics|PASS|
|tf_efficientnet_b2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b3.aa_in1k|Numerics|PASS|
|tf_efficientnet_b3.ap_in1k|Numerics|PASS|
|tf_efficientnet_b3.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b4.aa_in1k|Numerics|PASS|
|tf_efficientnet_b4.ap_in1k|Numerics|PASS|
|tf_efficientnet_b4.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ap_in1k|Numerics|PASS|
|tf_efficientnet_b5.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b5.ra_in1k|Numerics|PASS|
|tf_efficientnet_b6.aa_in1k|Numerics|PASS|
|tf_efficientnet_b6.ap_in1k|Numerics|PASS|
|tf_efficientnet_b6.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ap_in1k|Numerics|PASS|
|tf_efficientnet_b7.ns_jft_in1k|Numerics|PASS|
|tf_efficientnet_b7.ra_in1k|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|tf_efficientnet_b8.ra_in1k|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnetv2_l.in1k|Numerics|PASS|
|tf_efficientnetv2_l.in21k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_s.in1k|Numerics|PASS|
|tf_efficientnetv2_s.in21k_ft_in1k|Numerics|PASS|
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|PASS|
|tinynet_b.in1k|Numerics|PASS|
|tinynet_c.in1k|Numerics|PASS|
|tinynet_e.in1k|Numerics|PASS|
|twins_pcpvt_base|Numerics|PASS|
|twins_pcpvt_large|Numerics|PASS|
|twins_pcpvt_small|Numerics|PASS|
|twins_svt_base|Numerics|PASS|
|twins_svt_large|Numerics|PASS|
|twins_svt_small|Numerics|PASS|
|xcit_large_24_p16_224|Numerics|PASS|
|xcit_large_24_p16_224_dist|Numerics|PASS|
|xcit_large_24_p16_384_dist|Numerics|PASS|
|xcit_large_24_p8_224|Numerics|PASS|
|xcit_large_24_p8_224_dist|Numerics|PASS|
|xcit_large_24_p8_384_dist|Numerics|PASS|
|xcit_medium_24_p16_224|Numerics|PASS|
|xcit_medium_24_p16_224_dist|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|
|xcit_medium_24_p8_224|Numerics|PASS|
|xcit_medium_24_p8_224_dist|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|
|xcit_nano_12_p8_224|Numerics|PASS|
|xcit_nano_12_p8_224_dist|Numerics|PASS|
|xcit_nano_12_p8_384_dist|Numerics|PASS|
|xcit_small_12_p8_224|Numerics|PASS|
|xcit_small_12_p8_224_dist|Numerics|PASS|
|xcit_small_12_p8_384_dist|Numerics|PASS|
|xcit_small_24_p8_224|Numerics|PASS|
|xcit_small_24_p8_224_dist|Numerics|PASS|
|xcit_small_24_p8_384_dist|Numerics|PASS|
|xcit_tiny_12_p16_224|Numerics|PASS|
|xcit_tiny_12_p16_224_dist|Numerics|PASS|
|xcit_tiny_12_p16_384_dist|Numerics|PASS|
|xcit_tiny_24_p16_224|Numerics|PASS|
|xcit_tiny_24_p16_224_dist|Numerics|PASS|
|xcit_tiny_24_p16_384_dist|Numerics|PASS|

