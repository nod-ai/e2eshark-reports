# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.632|110.7888|25.1568|29.38%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|110.8527|24.7003|28.67%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.9527|511.3361|250.3834|95.95%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2671|68.792|37.525|120.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|progression|83.0977|62.2051|-20.8926|-25.14%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|269.6178|25.5502|10.47%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5572|37.6721|-2.8851|-7.11%|
|migraphx_bert__bert-large-uncased|PASS|progression|410.0501|19.4176|-390.6324|-95.26%|
|migraphx_cadene__dpn92i1|PASS|progression|186.2736|3.4809|-182.7928|-98.13%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|20.0688|-7237.1329|-99.72%|
|migraphx_cadene__resnext101_64x4di1|PASS|progression|330.1171|4.5856|-325.5315|-98.61%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|420.8|7.1028|-413.6972|-98.31%|
|migraphx_mlperf__bert_large_mlperf|PASS|progression|456.7549|27.7088|-429.0462|-93.93%|
|migraphx_mlperf__resnet50_v1|Numerics|progression|100.8666|14.1289|-86.7377|-85.99%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|40.8811|46.9013|6.0202|14.73%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|182.9736|110.8017|-72.1719|-39.44%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|70.2852|18.4284|-51.8568|-73.78%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.0543|8.3645|-32.6898|-79.63%|
|migraphx_torchvision__densenet121i32|PASS|progression|1377.2882|14.2397|-1363.0485|-98.97%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|3.0883|-255.6543|-98.81%|
|migraphx_torchvision__resnet50i1|PASS|progression|99.4756|2.045|-97.4306|-97.94%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2688.5782|25.7282|-2662.85|-99.04%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|4097.8175|37.4454|-4060.3721|-99.09%|
|migx_bench_bert-large-uncased_16_384|PASS|progression|6359.273|55.9528|-6303.3203|-99.12%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|12.5515|-175.7025|-93.33%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|12.6224|-368.2632|-96.69%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|392.6775|19.4274|-373.2501|-95.05%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|12.9717|-451.2058|-97.21%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.0645|19.2794|-626.7852|-97.02%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|845.906|19.6513|-826.2547|-97.68%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|5134.5125|35.7345|-5098.778|-99.3%|
|migx_bench_bert-large-uncased_32_256|PASS|progression|8841.4288|69.279|-8772.1497|-99.22%|
|migx_bench_bert-large-uncased_32_384|PASS|progression|11939.3575|110.745|-11828.6125|-99.07%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|745.4025|19.4557|-725.9468|-97.39%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1125.1086|20.2065|-1104.9021|-98.2%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|23.3269|-1725.9079|-98.67%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|20.2192|-1512.2358|-98.68%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|26.2263|-2377.74|-98.91%|
|migx_bench_bert-large-uncased_8_384|PASS|progression|3127.1362|32.595|-3094.5412|-98.96%|

## 35 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|U-2-Net_vaiq_int8|Numerics|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_1_rw_224.sw_in1k|PASS|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|compilation|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|compilation|
|dm_nfnet_f2.dm_in1k|PASS|compilation|
|dm_nfnet_f3.dm_in1k|PASS|compilation|
|dm_nfnet_f4.dm_in1k|PASS|compilation|
|dpn68b_test_vaiq|PASS|Numerics|
|dpn68b_vaiq|PASS|Numerics|
|gcvit_small|PASS|Numerics|
|migraphx_bert__bertsquad-12|PASS|compilation|
|migraphx_mlperf__resnet50_v1|PASS|Numerics|
|migraphx_sd__unet__model|compilation|import_model|
|migraphx_sdxl__unet__model|compilation|import_model|
|model--IMDB_ELECTRA_5E--pig4431|Numerics|compilation|
|model--bert-base-uncased-squad-v1--csarron|PASS|setup|
|model--deberta-v3-base__sst2__all-train--SetFit|PASS|compilation|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|Numerics|compilation|
|model--outputs--ankitkupadhyay|PASS|compilation|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|PASS|compilation|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|Numerics|
|mvitv2_base|PASS|compilation|
|mvitv2_small|PASS|compilation|
|mvitv2_tiny|PASS|compilation|
|pytorch-3dunet_vaiq_int8|PASS|Numerics|
|resnest200e|PASS|compilation|
|resnest269e|PASS|compilation|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|
|resnet50_gn_test_vaiq|PASS|Numerics|
|resnetv2_50d_gn.ah_in1k_vaiq|PASS|Numerics|

## 256 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|coat_lite_mini|Numerics|PASS|
|coat_lite_small|Numerics|PASS|
|coat_lite_tiny|Numerics|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_3_rw_224.sw_in12k|Numerics|PASS|
|coatnet_nano_rw_224.sw_in1k|Numerics|PASS|
|coatnext_nano_rw_224.sw_in1k|Numerics|PASS|
|convnext_atto.d2_in1k|Numerics|PASS|
|convnext_atto_ols.a2_in1k|Numerics|PASS|
|convnext_base.clip_laion2b|Numerics|PASS|
|convnext_base.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_femto.d1_in1k|Numerics|PASS|
|convnext_femto_ols.d1_in1k|Numerics|PASS|
|convnext_large.fb_in1k|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg|Numerics|PASS|
|convnext_large_mlp.clip_laion2b_augreg_ft_in1k|Numerics|PASS|
|convnext_nano.d1h_in1k|Numerics|PASS|
|convnext_nano.in12k|Numerics|PASS|
|convnext_nano_ols.d1h_in1k|Numerics|PASS|
|convnext_pico.d1_in1k|Numerics|PASS|
|convnext_pico_ols.d1_in1k|Numerics|PASS|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|Numerics|PASS|
|convnext_xlarge.fb_in22k_ft_in1k|Numerics|PASS|
|convnextv2_atto.fcmae|Numerics|PASS|
|convnextv2_atto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_base.fcmae|Numerics|PASS|
|convnextv2_base.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_femto.fcmae|Numerics|PASS|
|convnextv2_femto.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_large.fcmae|Numerics|PASS|
|convnextv2_large.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_nano.fcmae|Numerics|PASS|
|convnextv2_nano.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_pico.fcmae|Numerics|PASS|
|convnextv2_pico.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
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
|efficientnet_b5.in12k|Numerics|PASS|
|efficientnet_b5.in12k_ft_in1k|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|maxvit_base_tf_224.in1k|Numerics|PASS|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|maxvit_base_tf_512.in1k|Numerics|PASS|
|maxvit_large_tf_224.in1k|Numerics|PASS|
|maxvit_large_tf_384.in1k|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|maxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|PASS|
|maxvit_small_tf_224.in1k|Numerics|PASS|
|maxvit_small_tf_384.in1k|Numerics|PASS|
|maxvit_small_tf_512.in1k|Numerics|PASS|
|maxvit_tiny_rw_224.sw_in1k|Numerics|PASS|
|maxvit_tiny_tf_224.in1k|Numerics|PASS|
|maxvit_tiny_tf_384.in1k|Numerics|PASS|
|maxvit_tiny_tf_512.in1k|Numerics|PASS|
|maxvit_xlarge_tf_384.in21k_ft_in1k|Numerics|PASS|
|maxxvit_rmlp_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvit_rmlp_small_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_nano_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|migraphx_mlperf__bert_large_mlperf|Numerics|PASS|
|migx_bench_bert-large-uncased_16_384|Numerics|PASS|
|migx_bench_bert-large-uncased_32_384|Numerics|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xxs|Numerics|PASS|
|mobilevitv2_050|Numerics|PASS|
|mobilevitv2_075|Numerics|PASS|
|mobilevitv2_100|Numerics|PASS|
|mobilevitv2_125|Numerics|PASS|
|mobilevitv2_150|Numerics|PASS|
|mobilevitv2_175|Numerics|PASS|
|mobilevitv2_200|Numerics|PASS|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|Numerics|PASS|
|model--CodeGen-350M-Multi--xhyi|Numerics|PASS|
|model--Electra-Large-SQUADV2--titanbot|Numerics|PASS|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|Numerics|PASS|
|model--QAmembert--CATIE-AQ|Numerics|PASS|
|model--SAE-roberta-base-squad--jgammack|Numerics|PASS|
|model--XLMRoberta-Alexa-Intents-NER-NLU--qanastek|Numerics|PASS|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|Numerics|PASS|
|model--albert-base-v2-finetuned-ner--ArBert|Numerics|PASS|
|model--albert-base-v2-finetuned-squad--Firat|Numerics|PASS|
|model--albert-large-v2_ner_conll2003--Gladiator|Numerics|PASS|
|model--albert-large-v2_ner_wikiann--Gladiator|Numerics|PASS|
|model--albert-large-v2_squad--Palak|Numerics|PASS|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|Numerics|PASS|
|model--bart-CaPE-xsum--praf-choub|Numerics|PASS|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|Numerics|PASS|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|Numerics|PASS|
|model--camembert-base-fquad--illuin|Numerics|PASS|
|model--distilcamembert-base-ner--cmarkea|Numerics|PASS|
|model--distilcamembert-base-qa--cmarkea|Numerics|PASS|
|model--distilroberta-base-ner-conll2003--philschmid|Numerics|PASS|
|model--distilroberta-base-ner-wikiann--philschmid|Numerics|PASS|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|Numerics|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|PASS|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|Numerics|PASS|
|model--electra-small-discriminator-finetuned-ner--dbsamu|Numerics|PASS|
|model--electra-srb-ner--Aleksandar|Numerics|PASS|
|model--enlm-roberta-imdb--manirai91|Numerics|PASS|
|model--environmental-claims--climatebert|Numerics|PASS|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|Numerics|PASS|
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--gm-ner-xlmrbase--CLTL|Numerics|PASS|
|model--google_electra-base-discriminator_squad--Palak|Numerics|PASS|
|model--google_electra-small-discriminator_squad--Palak|Numerics|PASS|
|model--ia-detection-tiny-random-gptj--arincon|Numerics|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|PASS|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|PASS|
|model--mobilebert-squadv2--aware-ai|Numerics|PASS|
|model--mobilebert_cola--Alireza1044|Numerics|PASS|
|model--mobilebert_mnli--Alireza1044|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--my_awesome_gptj_model--anandshende|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|model--nd-qna--Trisert|Numerics|PASS|
|model--query_wellformedness_score--Ashishkr|Numerics|PASS|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-base-ca-cased-ner--projecte-aina|Numerics|PASS|
|model--roberta-base-finetuned-mbti-0901--GItaf|Numerics|PASS|
|model--roberta-base-finetuned-ner--dominiqueblok|Numerics|PASS|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|PASS|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|Numerics|PASS|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|PASS|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|PASS|
|model--roberta-large-tweetner7-all--tner|Numerics|PASS|
|model--roberta-ner-multilingual--julian-schelb|Numerics|PASS|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|Numerics|PASS|
|model--roberta_qa_japanese--tsmatz|Numerics|PASS|
|model--slovakbert-ner--crabz|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|compilation|PASS|
|model--summarization-not-evaluated--autoevaluate|Numerics|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|PASS|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|Numerics|PASS|
|model--twitter-roberta-base-emotion--cardiffnlp|Numerics|PASS|
|model--wikibert-finetuned-vsmec--ThuanPhong|Numerics|PASS|
|model--xlm-roberta-base-conll2003-ner--Yaxin|Numerics|PASS|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|Numerics|PASS|
|model--xlm-roberta-base-finetuned-squad--darshana1406|Numerics|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|PASS|
|model--xlm-roberta-imdb--manirai91|Numerics|PASS|
|model--xlm-roberta-large-squad2--deepset|Numerics|PASS|
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
|tf_efficientnet_b0.aa_in1k|Numerics|PASS|
|tf_efficientnet_b1.aa_in1k|Numerics|PASS|
|tf_efficientnet_b2.aa_in1k|Numerics|PASS|
|tf_efficientnet_b3.aa_in1k|Numerics|PASS|
|tf_efficientnet_b4.aa_in1k|Numerics|PASS|
|tf_efficientnet_b5.ap_in1k|Numerics|PASS|
|tf_efficientnet_b6.aa_in1k|Numerics|PASS|
|tf_efficientnet_b7.ap_in1k|Numerics|PASS|
|tf_efficientnet_b8.ap_in1k|Numerics|PASS|
|tf_efficientnet_l2.ns_jft_in1k|Numerics|PASS|
|tf_efficientnetv2_l.in1k|Numerics|PASS|
|tf_efficientnetv2_m.in1k|Numerics|PASS|
|tf_efficientnetv2_s.in1k|Numerics|PASS|
|tf_efficientnetv2_xl.in21k_ft_in1k|Numerics|PASS|
|tf_mixnet_l.in1k|Numerics|PASS|
|tf_mixnet_m.in1k|Numerics|PASS|
|tf_mixnet_s.in1k|Numerics|PASS|
|tf_mobilenetv3_large_075.in1k|Numerics|PASS|
|tf_mobilenetv3_large_100.in1k|Numerics|PASS|
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
|xcit_large_24_p16_384_dist|Numerics|PASS|
|xcit_large_24_p8_224|Numerics|PASS|
|xcit_large_24_p8_384_dist|Numerics|PASS|
|xcit_medium_24_p16_224|Numerics|PASS|
|xcit_medium_24_p16_384_dist|Numerics|PASS|
|xcit_medium_24_p8_224|Numerics|PASS|
|xcit_medium_24_p8_384_dist|Numerics|PASS|
|xcit_nano_12_p16_224|Numerics|PASS|
|xcit_nano_12_p16_384_dist|Numerics|PASS|
|xcit_nano_12_p8_224|Numerics|PASS|
|xcit_nano_12_p8_384_dist|Numerics|PASS|
|xcit_small_12_p16_224|Numerics|PASS|
|xcit_small_12_p16_384_dist|Numerics|PASS|
|xcit_small_12_p8_224|Numerics|PASS|
|xcit_small_12_p8_384_dist|Numerics|PASS|
|xcit_small_24_p16_224|Numerics|PASS|
|xcit_small_24_p16_384_dist|Numerics|PASS|
|xcit_small_24_p8_224|Numerics|PASS|
|xcit_small_24_p8_384_dist|Numerics|PASS|
|xcit_tiny_12_p16_224|Numerics|PASS|
|xcit_tiny_12_p16_384_dist|Numerics|PASS|
|xcit_tiny_12_p8_224|Numerics|PASS|
|xcit_tiny_12_p8_384_dist|Numerics|PASS|
|xcit_tiny_24_p16_224|Numerics|PASS|
|xcit_tiny_24_p16_384_dist|Numerics|PASS|
|xcit_tiny_24_p8_224|Numerics|PASS|
|xcit_tiny_24_p8_384_dist|Numerics|PASS|

