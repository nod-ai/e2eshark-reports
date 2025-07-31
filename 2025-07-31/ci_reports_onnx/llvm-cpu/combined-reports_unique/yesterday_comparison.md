# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|regression|200.6067|242.7406|42.1339|21.0%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|229.0422|200.3591|-28.683|-12.52%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|602.1219|569.8298|-32.2921|-5.36%|
|migraphx_ORT__distilgpt2_1|PASS|progression|87.2818|78.2189|-9.0629|-10.38%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|189.3218|190.2835|0.9617|0.51%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|progression|696.6661|551.3446|-145.3215|-20.86%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|89.6262|105.3453|15.7192|17.54%|
|migraphx_bert__bert-large-uncased|PASS|within tol|375.9953|367.6111|-8.3841|-2.23%|
|migraphx_cadene__dpn92i1|PASS|regression|166.3471|181.7319|15.3848|9.25%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5741.7573|5454.704|-287.0533|-5.0%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|317.6264|361.5867|43.9604|13.84%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|430.5441|432.7529|2.2088|0.51%|
|migraphx_mlperf__bert_large_mlperf|Numerics|regression|451.4221|497.1717|45.7496|10.13%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|93.2621|92.1886|-1.0735|-1.15%|
|migraphx_models__whisper-tiny-decoder|PASS|regression|65.0221|70.4606|5.4385|8.36%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|230.6694|215.2725|-15.3969|-6.67%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|66.6039|107.2358|40.6319|61.01%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|19.9172|18.8483|-1.0689|-5.37%|
|migraphx_torchvision__densenet121i32|PASS|progression|1642.4481|1506.8981|-135.55|-8.25%|
|migraphx_torchvision__inceptioni1|PASS|regression|189.6857|296.0864|106.4007|56.09%|
|migraphx_torchvision__resnet50i1|PASS|within tol|83.4684|83.1276|-0.3408|-0.41%|
|migx_bench_bert-large-uncased_16_128|PASS|progression|1643.7009|1540.3336|-103.3673|-6.29%|
|migx_bench_bert-large-uncased_16_256|PASS|progression|6621.2505|5380.3373|-1240.9133|-18.74%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|9595.5387|9948.2189|352.6802|3.68%|
|migx_bench_bert-large-uncased_1_128|PASS|regression|147.9065|155.6458|7.7393|5.23%|
|migx_bench_bert-large-uncased_1_256|PASS|regression|250.3612|295.2577|44.8965|17.93%|
|migx_bench_bert-large-uncased_1_384|PASS|regression|367.0368|406.4338|39.397|10.73%|
|migx_bench_bert-large-uncased_2_128|PASS|regression|261.689|288.1385|26.4495|10.11%|
|migx_bench_bert-large-uncased_2_256|PASS|regression|436.721|555.467|118.746|27.19%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|669.431|658.8255|-10.6055|-1.58%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5196.697|4985.7115|-210.9855|-4.06%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|14039.0147|13695.9374|-343.0773|-2.44%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|23618.0713|23803.0909|185.0196|0.78%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|402.9401|1076.7315|673.7914|167.22%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|790.9374|787.8997|-3.0377|-0.38%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1233.0134|1261.468|28.4546|2.31%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1156.9756|1188.5729|31.5972|2.73%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|1661.0049|1656.0572|-4.9478|-0.3%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3446.0137|3447.4894|1.4757|0.04%|

## 2 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|resnetv2_50d_evos_Opset17_timm|Numerics|compilation|
|swinv2_base_window8_256_Opset16_timm|PASS|compilation|

## 198 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|coat_lite_mini_Opset16_timm|compilation|PASS|
|convnext_large_in22k_Opset18_timm|compilation|PASS|
|convnext_xlarge_384_in22ft1k_Opset16_timm|compilation|PASS|
|convnext_xlarge_in22ft1k_Opset17_timm|compilation|PASS|
|convnext_xlarge_in22k_Opset17_timm|compilation|PASS|
|gcvit_base|compilation|PASS|
|gcvit_small|compilation|PASS|
|gcvit_tiny|compilation|PASS|
|gcvit_xtiny|compilation|PASS|
|gcvit_xxtiny|compilation|PASS|
|levit_128.fb_dist_in1k|compilation|PASS|
|levit_128_Opset16_timm|compilation|PASS|
|levit_128s.fb_dist_in1k|compilation|PASS|
|levit_192.fb_dist_in1k|compilation|PASS|
|levit_256.fb_dist_in1k|compilation|PASS|
|levit_384.fb_dist_in1k|compilation|PASS|
|maxvit_base_tf_224.in1k|compilation|PASS|
|maxvit_large_tf_224.in1k|compilation|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxvit_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxvit_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|maxvit_rmlp_small_rw_224.sw_in1k|compilation|PASS|
|maxvit_small_tf_224.in1k|compilation|PASS|
|maxvit_tiny_rw_224.sw_in1k|compilation|PASS|
|maxvit_tiny_tf_224.in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_384.sw_in12k_ft_in1k|compilation|PASS|
|model--bert-german-ler--elenanereiss|compilation|PASS|
|model--bert-german-ner--lunesco|compilation|PASS|
|model--bert-imdb-1hidden--lannelin|compilation|PASS|
|model--bert-l-squadv1.1-sl256--vuiseng9|compilation|PASS|
|model--bert-large-NER--51la5|compilation|PASS|
|model--bert-large-uncased-en-ner--n6ai|compilation|PASS|
|model--bert-medium-pretrained-finetuned-squad--anas-awadalla|compilation|PASS|
|model--bert-mini-finetuned-squad--anas-awadalla|compilation|PASS|
|model--biobert-base-cased-v1.2-bc2gm-ner--chintagunta85|compilation|PASS|
|model--bleurt-tiny-128--Elron|compilation|PASS|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|compilation|PASS|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|compilation|PASS|
|model--camembert-base-fquad--illuin|compilation|PASS|
|model--cm_code_clippy--ncoop57|compilation|PASS|
|model--deberta-italian-question-answering--osiria|compilation|PASS|
|model--deberta-v3-base-qa-en--LLukas22|compilation|PASS|
|model--deberta-v3-base__sst2__all-train--SetFit|compilation|PASS|
|model--deberta-v3-large-squad2--deepset|compilation|PASS|
|model--deberta-v3-xsmall-squad2--nlpconnect|compilation|PASS|
|model--distilbert-base-uncased-finetuned-squad--negfir|compilation|PASS|
|model--distilcamembert-base-ner--cmarkea|compilation|PASS|
|model--distilcamembert-base-qa--cmarkea|compilation|PASS|
|model--distilgpt2-sd--aabidk|compilation|PASS|
|model--distill-bert-base-spanish-wwm-cased-finetuned-spa-squad2-es--mrm8488|compilation|PASS|
|model--distilroberta-base-ner-conll2003--philschmid|compilation|PASS|
|model--distilroberta-base-ner-wikiann--philschmid|compilation|PASS|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|compilation|PASS|
|model--dynamic_tinybert--Intel|compilation|PASS|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|compilation|PASS|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|compilation|PASS|
|model--electra-small-discriminator-finetuned-ner--dbsamu|compilation|PASS|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|compilation|PASS|
|model--electra-srb-ner--Aleksandar|compilation|PASS|
|model--en-finetuned-squad-qa-minilmv2-32--subhasisj|compilation|PASS|
|model--enlm-roberta-imdb--manirai91|compilation|PASS|
|model--environmental-claims--climatebert|compilation|PASS|
|model--finbert--ProsusAI|compilation|PASS|
|model--finetuned-base_mini--muhtasham|compilation|PASS|
|model--finetuned-base_small--muhtasham|compilation|PASS|
|model--finetuned-self_mlm_tiny--muhtasham|compilation|PASS|
|model--finetuned_distilgpt2_sst2_negation0.0001_pretrainedTrue_epochs1--jhaochenz|compilation|PASS|
|model--finetuned_gpt2-large_sst2_negation0.0_pretrainedFalse--yuhuizhang|compilation|PASS|
|model--finetuned_gpt2-medium_sst2_negation0.0001_pretrainedTrue--yuhuizhang|compilation|PASS|
|model--finetuned_gpt2_sst2_negation0.0001_pretrainedFalse_epochs1--yuhuizhang|compilation|PASS|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|compilation|PASS|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|compilation|PASS|
|model--flaubert-base-uncased-finetuned-cooking--nbouali|compilation|PASS|
|model--gemma-tiny-random--yujiepan|compilation|PASS|
|model--gm-ner-xlmrbase--CLTL|compilation|PASS|
|model--google_electra-base-discriminator_squad--Palak|compilation|PASS|
|model--google_electra-small-discriminator_squad--Palak|compilation|PASS|
|model--gpt2--openai-community|compilation|PASS|
|model--gpt2-alpaca-gpt4--vicgalle|compilation|PASS|
|model--hebrew_poetry-gpt_neo-small--Norod78|compilation|PASS|
|model--ia-detection-tiny-random-gptj--arincon|compilation|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|compilation|PASS|
|model--llama-160m--JackFram|compilation|PASS|
|model--llama-wikitext--manu|compilation|PASS|
|model--ltgbert-qa--amroadel1|compilation|PASS|
|model--mBERT-squad--intanm|compilation|PASS|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|compilation|PASS|
|model--mbert-bengali-ner--sagorsarker|compilation|PASS|
|model--mbert-imdb--manirai91|compilation|PASS|
|model--mdeberta-v3-base-squad2--sjrhuschlee|compilation|PASS|
|model--medium-mlm-imdb-target-imdb--muhtasham|compilation|PASS|
|model--megatron-gpt2-345m--robowaifudev|compilation|PASS|
|model--microsoft-deberta-v3-large_ner_conll2003--Gladiator|compilation|PASS|
|model--microsoft_deberta-base_squad--Palak|compilation|PASS|
|model--microsoft_deberta-large_squad--Palak|compilation|PASS|
|model--my_awesome_gptj_model--anandshende|compilation|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|compilation|PASS|
|model--nbailab-base-ner-scandi--saattrupdan|compilation|PASS|
|model--nd-qna--Trisert|compilation|PASS|
|model--ner-bert-base-cased-pt-lenerbr--pierreguillou|compilation|PASS|
|model--ner-bert-large-cased-pt-lenerbr--pierreguillou|compilation|PASS|
|model--ner_conll2003--ramybaly|compilation|PASS|
|model--outputs--ankitkupadhyay|compilation|PASS|
|model--phi-2-classifier--roborovski|compilation|PASS|
|model--pythia-410mn-ntoxic--skrishna|compilation|PASS|
|model--pythia-70-m-finetuned--selinerdem|compilation|PASS|
|model--pythia-70m-toxicity-model--skrishna|compilation|PASS|
|model--query_wellformedness_score--Ashishkr|compilation|PASS|
|model--really-tiny-falcon-testing--fxmarty|compilation|PASS|
|model--reward-model-deberta-v3-large-v2--OpenAssistant|compilation|PASS|
|model--rm_checkpoint--Manoj120|compilation|PASS|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|compilation|PASS|
|model--roberta-base-ca-cased-ner--projecte-aina|compilation|PASS|
|model--roberta-base-finetuned-mbti-0901--GItaf|compilation|PASS|
|model--roberta-base-finetuned-ner--dominiqueblok|compilation|PASS|
|model--roberta-l-squadv1.1--vuiseng9|compilation|PASS|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|compilation|PASS|
|model--roberta-large-finetuned-ner--romainlhardy|compilation|PASS|
|model--roberta-large-ner-english--Jean-Baptiste|compilation|PASS|
|model--roberta-large-tweetner7-all--tner|compilation|PASS|
|model--roberta-med-small_shared-finetuned-bbc_xsum-summarization--mrm8488|compilation|PASS|
|model--roberta-ner-multilingual--julian-schelb|compilation|PASS|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|compilation|PASS|
|model--roberta_qa_japanese--tsmatz|compilation|PASS|
|model--roberta_shared_bbc_xsum--patrickvonplaten|compilation|PASS|
|model--rubert-tiny-toxicity--cointegrated|compilation|PASS|
|model--sberbank-rubert-base-collection3--viktoroo|compilation|PASS|
|model--slovakbert-ner--crabz|compilation|PASS|
|model--smol_llama-220M-GQA--BEE-spoke-data|compilation|PASS|
|model--smol_llama-81M-tied--BEE-spoke-data|compilation|PASS|
|model--spanbert-large-squad--anas-awadalla|compilation|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|compilation|PASS|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|compilation|PASS|
|model--squad_it_xxl_cased_hub1--luigisaetta|compilation|PASS|
|model--squeezebert-uncased-finetuned-squad--SupriyaArun|compilation|PASS|
|model--tiny-bert-qa--srcocotero|compilation|PASS|
|model--tiny-gpt2--taufeeque|compilation|PASS|
|model--tiny-gpt2-magicprompt--pszemraj|compilation|PASS|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-FalconForCausalLM--illuin|compilation|PASS|
|model--tiny-random-FlaubertForQuestionAnsweringSimple--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-FlaubertForTokenClassification--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-GPTNeoForSequenceClassification--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|compilation|PASS|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|compilation|PASS|
|model--tiny-random-llama--IlyasMoutawwakil|compilation|PASS|
|model--tiny-testing-falcon-alibi--fxmarty|compilation|PASS|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|compilation|PASS|
|model--twitter-roberta-base-emotion--cardiffnlp|compilation|PASS|
|model--wikibert-finetuned-vsmec--ThuanPhong|compilation|PASS|
|model--xlm-roberta-base-conll2003-ner--Yaxin|compilation|PASS|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|compilation|PASS|
|model--xlm-roberta-base-finetuned-squad--darshana1406|compilation|PASS|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|compilation|PASS|
|model--xlm-roberta-imdb--manirai91|compilation|PASS|
|model--xlm-roberta-large-squad2--deepset|compilation|PASS|
|model--xtremedistil-l6-h256-uncased-TQUAD-finetuned_lr-2e-05_epochs-3--husnu|compilation|PASS|
|model--xtremedistil-l6-h256-uncased-finetuned_lr-2e-05_epochs-3--husnu|compilation|PASS|
|model--xtremedistil-l6-h384-uncased-finetuned-squad--tachyon-11|compilation|PASS|
|model--yelp_review_rating_reberta_base--Shunian|compilation|PASS|
|mvitv2_large|compilation|PASS|
|pit_b_224|compilation|PASS|
|pit_b_distilled_224|compilation|PASS|
|pit_s_224|compilation|PASS|
|pit_s_224_Opset18_timm|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|compilation|PASS|
|pit_ti_distilled_224|compilation|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pit_xs_distilled_224_Opset16_timm|compilation|PASS|
|swin_b_Opset18_torch_hub|compilation|PASS|
|swin_base_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_base_patch4_window7_224_in22k_Opset16_timm|compilation|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|compilation|PASS|
|swin_large_patch4_window7_224_in22k_Opset16_timm|compilation|PASS|
|swin_s3_base_224.ms_in1k|compilation|PASS|
|swin_s3_small_224.ms_in1k|compilation|PASS|
|swin_s3_tiny_224.ms_in1k|compilation|PASS|
|swin_s_Opset18_torch_hub|compilation|PASS|
|swin_small_patch4_window7_224.ms_in1k|compilation|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|compilation|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224_Opset18_timm|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|twins_pcpvt_base_Opset16_timm|compilation|PASS|
|twins_pcpvt_small_Opset17_timm|compilation|PASS|
|twins_svt_base_Opset17_timm|compilation|PASS|
|twins_svt_large_Opset16_timm|compilation|PASS|
|vit_b_32_Opset16_torch_hub|compilation|PASS|
|vit_base_patch32_224_Opset17_timm|compilation|PASS|
|vit_l_32_Opset16_torch_hub|compilation|PASS|
|vit_small_patch32_224_Opset16_timm|compilation|PASS|
|vit_small_patch32_224_in21k_Opset16_timm|compilation|PASS|

