# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|85.632|200.6067|114.9747|134.27%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|229.0422|142.8898|165.86%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|260.9527|602.1219|341.1692|130.74%|
|migraphx_ORT__distilgpt2_1|PASS|regression|31.2671|87.2818|56.0147|179.15%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|83.0977|189.3218|106.2241|127.83%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|244.0676|696.6661|452.5986|185.44%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|40.5572|89.6262|49.0689|120.99%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|375.9953|-34.0548|-8.31%|
|migraphx_cadene__dpn92i1|PASS|progression|186.2736|166.3471|-19.9265|-10.7%|
|migraphx_cadene__inceptionv4i16|PASS|progression|7257.2016|5741.7573|-1515.4443|-20.88%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|317.6264|-12.4907|-3.78%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|420.8|430.5441|9.7441|2.32%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|451.4221|-5.3329|-1.17%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.8666|93.2621|-7.6044|-7.54%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|40.8811|65.0221|24.141|59.05%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|182.9736|230.6694|47.6958|26.07%|
|migraphx_pytorch-examples__wlang_gru|PASS|within tol|70.2852|66.6039|-3.6813|-5.24%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|41.0543|19.9172|-21.137|-51.49%|
|migraphx_torchvision__densenet121i32|PASS|regression|1377.2882|1642.4481|265.1599|19.25%|
|migraphx_torchvision__inceptioni1|PASS|progression|258.7426|189.6857|-69.0569|-26.69%|
|migraphx_torchvision__resnet50i1|PASS|progression|99.4756|83.4684|-16.0072|-16.09%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|2688.5782|1643.7009|-1044.8773|-38.86%|
|migx_bench_bert-large-uncased_16_256|PASS|regression|4097.8175|6621.2505|2523.433|61.58%|
|migx_bench_bert-large-uncased_16_384|Numerics|regression|6359.273|9595.5387|3236.2656|50.89%|
|migx_bench_bert-large-uncased_1_128|PASS|progression|188.254|147.9065|-40.3475|-21.43%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|250.3612|-130.5244|-34.27%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|367.0368|-25.6407|-6.53%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|464.1775|261.689|-202.4885|-43.62%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|646.0645|436.721|-209.3435|-32.4%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|845.906|669.431|-176.475|-20.86%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5134.5125|5196.697|62.1844|1.21%|
|migx_bench_bert-large-uncased_32_256|PASS|regression|8841.4288|14039.0147|5197.5859|58.79%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11939.3575|23618.0713|11678.7138|97.82%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|745.4025|402.9401|-342.4623|-45.94%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1125.1086|790.9374|-334.1712|-29.7%|
|migx_bench_bert-large-uncased_4_384|PASS|progression|1749.2347|1233.0134|-516.2213|-29.51%|
|migx_bench_bert-large-uncased_8_128|PASS|progression|1532.455|1156.9756|-375.4793|-24.5%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|1661.0049|-742.9613|-30.91%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3127.1362|3446.0137|318.8775|10.2%|

## 181 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|gcvit_base|PASS|compilation|
|gcvit_small|PASS|compilation|
|gcvit_tiny|PASS|compilation|
|gcvit_xtiny|PASS|compilation|
|gcvit_xxtiny|PASS|compilation|
|levit_128.fb_dist_in1k|PASS|compilation|
|levit_128s.fb_dist_in1k|PASS|compilation|
|levit_192.fb_dist_in1k|PASS|compilation|
|levit_256.fb_dist_in1k|PASS|compilation|
|levit_384.fb_dist_in1k|PASS|compilation|
|maxvit_base_tf_224.in1k|Numerics|compilation|
|maxvit_large_tf_224.in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k|Numerics|compilation|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|maxvit_rmlp_small_rw_224.sw_in1k|Numerics|compilation|
|maxvit_small_tf_224.in1k|Numerics|compilation|
|maxvit_tiny_rw_224.sw_in1k|Numerics|compilation|
|maxvit_tiny_tf_224.in1k|Numerics|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|Numerics|compilation|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|Numerics|compilation|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|Numerics|compilation|
|migraphx_bert__bertsquad-12|PASS|compilation|
|migraphx_sd__unet__model|compilation|import_model|
|migraphx_sdxl__unet__model|compilation|import_model|
|model--bert-german-ler--elenanereiss|PASS|compilation|
|model--bert-german-ner--lunesco|PASS|compilation|
|model--bert-imdb-1hidden--lannelin|PASS|compilation|
|model--bert-l-squadv1.1-sl256--vuiseng9|PASS|compilation|
|model--bert-large-NER--51la5|PASS|compilation|
|model--bert-large-uncased-en-ner--n6ai|PASS|compilation|
|model--bert-medium-pretrained-finetuned-squad--anas-awadalla|PASS|compilation|
|model--bert-mini-finetuned-squad--anas-awadalla|PASS|compilation|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|PASS|compilation|
|model--bleurt-tiny-128--Elron|PASS|compilation|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|Numerics|compilation|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|Numerics|compilation|
|model--camembert-base-fquad--illuin|Numerics|compilation|
|model--cm_code_clippy--ncoop57|PASS|compilation|
|model--deberta-italian-question-answering--osiria|PASS|compilation|
|model--deberta-v3-base-qa-en--LLukas22|PASS|compilation|
|model--deberta-v3-base__sst2__all-train--SetFit|PASS|compilation|
|model--deberta-v3-large-squad2--deepset|PASS|compilation|
|model--deberta-v3-xsmall-squad2--nlpconnect|PASS|compilation|
|model--distilbert-base-uncased-finetuned-squad--negfir|PASS|compilation|
|model--distilcamembert-base-ner--cmarkea|Numerics|compilation|
|model--distilcamembert-base-qa--cmarkea|Numerics|compilation|
|model--distilgpt2-sd--aabidk|PASS|compilation|
|model--distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es--mrm8488|PASS|compilation|
|model--distilroberta-base-ner-conll2003--philschmid|Numerics|compilation|
|model--distilroberta-base-ner-wikiann--philschmid|Numerics|compilation|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|Numerics|compilation|
|model--dynamic_tinybert--Intel|PASS|compilation|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|Numerics|compilation|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|Numerics|compilation|
|model--electra-small-discriminator-finetuned-ner--dbsamu|Numerics|compilation|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|Numerics|compilation|
|model--electra-srb-ner--Aleksandar|Numerics|compilation|
|model--en-finetuned-squad-qa-minilmv2-32--subhasisj|PASS|compilation|
|model--enlm-roberta-imdb--manirai91|Numerics|compilation|
|model--environmental-claims--climatebert|Numerics|compilation|
|model--finbert--ProsusAI|PASS|compilation|
|model--finetuned-base_mini--muhtasham|PASS|compilation|
|model--finetuned-base_small--muhtasham|PASS|compilation|
|model--finetuned-self_mlm_tiny--muhtasham|PASS|compilation|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|PASS|compilation|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|PASS|compilation|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|PASS|compilation|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|PASS|compilation|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|Numerics|compilation|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|Numerics|compilation|
|model--flaubert-base-uncased-finetuned-cooking--nbouali|PASS|compilation|
|model--gemma-tiny-random--yujiepan|PASS|compilation|
|model--gm-ner-xlmrbase--CLTL|Numerics|compilation|
|model--google_electra-base-discriminator_squad--Palak|Numerics|compilation|
|model--google_electra-small-discriminator_squad--Palak|Numerics|compilation|
|model--gpt2--openai-community|PASS|compilation|
|model--gpt2-alpaca-gpt4--vicgalle|PASS|compilation|
|model--hebrew_poetry-gpt_neo-small--Norod78|PASS|compilation|
|model--ia-detection-tiny-random-gptj--arincon|Numerics|compilation|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|compilation|
|model--llama-160m--JackFram|PASS|compilation|
|model--llama-wikitext--manu|PASS|compilation|
|model--ltgbert-qa--amroadel1|PASS|compilation|
|model--mBERT-squad--intanm|PASS|compilation|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|Numerics|compilation|
|model--mbert-bengali-ner--sagorsarker|PASS|compilation|
|model--mbert-imdb--manirai91|PASS|compilation|
|model--mdeberta-v3-base-squad2--sjrhuschlee|PASS|compilation|
|model--medium-mlm-imdb-target-imdb--muhtasham|PASS|compilation|
|model--megatron-gpt2-345m--robowaifudev|PASS|compilation|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|PASS|compilation|
|model--microsoft_deberta-base_squad--Palak|PASS|compilation|
|model--microsoft_deberta-large_squad--Palak|PASS|compilation|
|model--my_awesome_gptj_model--anandshende|Numerics|compilation|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|compilation|
|model--nbailab-base-ner-scandi--saattrupdan|PASS|compilation|
|model--nd-qna--Trisert|Numerics|compilation|
|model--ner-bert-base-cased-pt-lenerbr--pierreguillou|PASS|compilation|
|model--ner-bert-large-cased-pt-lenerbr--pierreguillou|PASS|compilation|
|model--ner_conll2003--ramybaly|PASS|compilation|
|model--outputs--ankitkupadhyay|PASS|compilation|
|model--phi-2-classifier--roborovski|PASS|compilation|
|model--pythia-410mn-ntoxic--skrishna|PASS|compilation|
|model--pythia-70-m-finetuned--selinerdem|PASS|compilation|
|model--pythia-70m-toxicity-model--skrishna|PASS|compilation|
|model--query_wellformedness_score--Ashishkr|Numerics|compilation|
|model--really-tiny-falcon-testing--fxmarty|PASS|compilation|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|PASS|compilation|
|model--rm_checkpoint--Manoj120|PASS|compilation|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|Numerics|compilation|
|model--roberta-base-ca-cased-ner--projecte-aina|Numerics|compilation|
|model--roberta-base-finetuned-mbti-0901--GItaf|Numerics|compilation|
|model--roberta-base-finetuned-ner--dominiqueblok|Numerics|compilation|
|model--roberta-l-squadv1.1--vuiseng9|Numerics|compilation|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|Numerics|compilation|
|model--roberta-large-finetuned-ner--romainlhardy|Numerics|compilation|
|model--roberta-large-ner-english--Jean-Baptiste|Numerics|compilation|
|model--roberta-large-tweetner7-all--tner|Numerics|compilation|
|model--roberta-med-small_shared-finetuned-bbc_xsum-summarization--mrm8488|PASS|compilation|
|model--roberta-ner-multilingual--julian-schelb|Numerics|compilation|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|Numerics|compilation|
|model--roberta_qa_japanese--tsmatz|Numerics|compilation|
|model--roberta_shared_bbc_xsum--patrickvonplaten|PASS|compilation|
|model--rubert-tiny-toxicity--cointegrated|PASS|compilation|
|model--sberbank-rubert-base-collection3--viktoroo|PASS|compilation|
|model--slovakbert-ner--crabz|Numerics|compilation|
|model--smol_llama-220M-GQA--BEE-spoke-data|PASS|compilation|
|model--smol_llama-81M-tied--BEE-spoke-data|PASS|compilation|
|model--spanbert-large-squad--anas-awadalla|PASS|compilation|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|Numerics|compilation|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|Numerics|compilation|
|model--squad_it_xxl_cased_hub1--luigisaetta|PASS|compilation|
|model--tiny-bert-qa--srcocotero|PASS|compilation|
|model--tiny-gpt2--taufeeque|PASS|compilation|
|model--tiny-gpt2-magicprompt--pszemraj|PASS|compilation|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|compilation|
|model--tiny-random-FalconForCausalLM--illuin|PASS|compilation|
|model--tiny-random-FlaubertForQuestionAnsweringSimple--hf-tiny-model-private|PASS|compilation|
|model--tiny-random-FlaubertForTokenClassification--hf-tiny-model-private|PASS|compilation|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|compilation|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|PASS|compilation|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|Numerics|compilation|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|Numerics|compilation|
|model--tiny-random-llama--IlyasMoutawwakil|PASS|compilation|
|model--tiny-testing-falcon-alibi--fxmarty|PASS|compilation|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|Numerics|compilation|
|model--twitter-roberta-base-emotion--cardiffnlp|Numerics|compilation|
|model--wikibert-finetuned-vsmec--ThuanPhong|Numerics|compilation|
|model--xlm-roberta-base-conll2003-ner--Yaxin|Numerics|compilation|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|Numerics|compilation|
|model--xlm-roberta-base-finetuned-squad--darshana1406|Numerics|compilation|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|Numerics|compilation|
|model--xlm-roberta-imdb--manirai91|Numerics|compilation|
|model--xlm-roberta-large-squad2--deepset|Numerics|compilation|
|model--xtremedistil-l6-h256-uncased-TQUAD-finetuned_lr-2e-05_epochs-3--husnu|PASS|compilation|
|model--xtremedistil-l6-h256-uncased-finetuned_lr-2e-05_epochs-3--husnu|PASS|compilation|
|model--xtremedistil-l6-h384-uncased-finetuned-squad--tachyon-11|PASS|compilation|
|model--yelp_review_rating_reberta_base--Shunian|Numerics|compilation|
|mvitv2_base|PASS|compilation|
|mvitv2_large|PASS|compilation|
|mvitv2_small|PASS|compilation|
|mvitv2_tiny|PASS|compilation|
|regnetz_c16_evos.ch_in1k_train_vaiq|PASS|compilation|
|regnetz_c16_evos.ch_in1k_vaiq|PASS|compilation|
|regnetz_d8_evos.ch_in1k_train_vaiq|PASS|compilation|
|regnetz_d8_evos.ch_in1k_vaiq|PASS|compilation|
|resnet10t_train_vaiq|PASS|Numerics|
|resnet14t_train_vaiq|PASS|Numerics|
|resnetv2_50d_evos.ah_in1k_train_vaiq|PASS|compilation|
|resnetv2_50d_evos.ah_in1k_vaiq|PASS|compilation|
|swin_base_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|PASS|compilation|
|swin_s3_base_224.ms_in1k|PASS|compilation|
|swin_s3_small_224.ms_in1k|PASS|compilation|
|swin_s3_tiny_224.ms_in1k|PASS|compilation|
|swin_small_patch4_window7_224.ms_in1k|PASS|compilation|
|swin_tiny_patch4_window7_224.ms_in1k|PASS|compilation|
|swinv2_cr_small_224.sw_in1k|PASS|compilation|
|swinv2_cr_small_ns_224.sw_in1k|PASS|compilation|
|swinv2_cr_tiny_ns_224.sw_in1k|PASS|compilation|

## 188 Progressions Found:

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
|coatnet_rmlp_1_rw2_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_1_rw2_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k|Numerics|PASS|
|coatnet_rmlp_2_rw_224.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_2_rw_384.sw_in12k_ft_in1k|Numerics|PASS|
|coatnet_rmlp_nano_rw_224.sw_in1k|Numerics|PASS|
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
|efficientformerv2_l.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s0.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s1.snap_dist_in1k|Numerics|PASS|
|efficientformerv2_s2.snap_dist_in1k|Numerics|PASS|
|efficientnet_b1_pruned.in1k|Numerics|PASS|
|efficientnet_b2_pruned.in1k|Numerics|PASS|
|efficientnet_b3_pruned.in1k|Numerics|PASS|
|efficientnet_b5.in12k|Numerics|PASS|
|efficientnet_b5.in12k_ft_in1k|Numerics|PASS|
|gluon_xception65|Numerics|PASS|
|lambda_resnet26t|Numerics|PASS|
|lambda_resnet50ts|Numerics|PASS|
|maxvit_base_tf_384.in1k|Numerics|PASS|
|maxvit_base_tf_512.in1k|Numerics|PASS|
|maxvit_large_tf_384.in1k|Numerics|PASS|
|maxvit_large_tf_512.in1k|Numerics|PASS|
|maxvit_nano_rw_256.sw_in1k|Numerics|PASS|
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
|model--IMDB_ELECTRA_5E--pig4431|Numerics|PASS|
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
|model--flan-t5-large-samsum--oguuzhansahin|Numerics|PASS|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--mobilebert-squadv2--aware-ai|Numerics|PASS|
|model--mobilebert_cola--Alireza1044|Numerics|PASS|
|model--mobilebert_mnli--Alireza1044|Numerics|PASS|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|Numerics|PASS|
|model--summarization-not-evaluated--autoevaluate|Numerics|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
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

