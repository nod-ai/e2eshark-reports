# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|100.1446|101.5048|1.3603|1.36%|
|migraphx_ORT__bert_base_uncased_1|PASS|within tol|99.4647|101.2788|1.8141|1.82%|
|migraphx_ORT__bert_large_uncased_1|PASS|regression|502.5753|584.655|82.0797|16.33%|
|migraphx_ORT__distilgpt2_1|PASS|regression|53.8043|57.5741|3.7697|7.01%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|60.9175|63.2403|2.3227|3.81%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|290.3497|296.1164|5.7667|1.99%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|progression|66.5043|37.1163|-29.388|-44.19%|
|migraphx_bert__bert-large-uncased|PASS|within tol|19.3045|19.5548|0.2504|1.3%|
|migraphx_bert__bertsquad-12|PASS|within tol|7.5967|7.6445|0.0478|0.63%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|progression|11.0673|7.9317|-3.1356|-28.33%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|24.2843|25.1508|0.8665|3.57%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|56.536|34.6121|-21.9238|-38.78%|
|migraphx_models__whisper-tiny-encoder|Numerics|progression|132.8781|47.7552|-85.123|-64.06%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|15.0738|19.2696|4.1958|27.84%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|7.5038|6.7985|-0.7052|-9.4%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|35.2876|36.4904|1.2028|3.41%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|58.4088|60.1164|1.7075|2.92%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|79.3576|81.7553|2.3977|3.02%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|13.0941|13.0983|0.0042|0.03%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|13.2137|13.289|0.0753|0.57%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|19.4374|19.4637|0.0263|0.14%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|12.6556|12.6129|-0.0427|-0.34%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|13.215|13.2262|0.0112|0.08%|
|migx_bench_bert-large-uncased_2_384|PASS|progression|56.4063|21.9474|-34.4589|-61.09%|
|migx_bench_bert-large-uncased_32_128|PASS|progression|107.7339|73.1416|-34.5923|-32.11%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|111.2824|114.6984|3.416|3.07%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|159.7439|164.3375|4.5936|2.88%|
|migx_bench_bert-large-uncased_4_128|PASS|progression|16.2421|14.4298|-1.8122|-11.16%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|17.5787|18.2176|0.639|3.63%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|26.4451|27.3185|0.8734|3.3%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|20.1325|20.7194|0.5869|2.92%|
|migx_bench_bert-large-uncased_8_256|PASS|within tol|29.6265|30.516|0.8895|3.0%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|43.3105|44.7572|1.4467|3.34%|

## 184 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|PASS|Numerics|
|model--CodeGen-350M-Multi--xhyi|PASS|Numerics|
|model--Electra-Large-SQUADV2--titanbot|PASS|Numerics|
|model--IMDB_ELECTRA_5E--pig4431|PASS|Numerics|
|model--QAmembert--CATIE-AQ|PASS|Numerics|
|model--SAE-roberta-base-squad--jgammack|PASS|Numerics|
|model--XLMRoberta-Alexa-Intents-NER-NLU--qanastek|PASS|Numerics|
|model--XLMRobertaLongForQuestionAnswering-base-squad2-512-4096--sadaqabdo|PASS|Numerics|
|model--albert-base-v2-finetuned-ner--ArBert|PASS|Numerics|
|model--albert-base-v2-finetuned-ner--Jorgeutd|PASS|Numerics|
|model--albert-base-v2-finetuned-squad--Firat|PASS|Numerics|
|model--albert-base-v2-finetuned-squad--bdickson|PASS|Numerics|
|model--albert-base-v2-imdb--textattack|PASS|Numerics|
|model--albert-base-v2-imdb-calssification--XSY|PASS|Numerics|
|model--albert-base-v2-squad2--twmkn9|PASS|Numerics|
|model--albert-base-v2-squad_v2--squirro|PASS|Numerics|
|model--albert-base-v2_squad--Palak|PASS|Numerics|
|model--albert-large-v2_ner_conll2003--Gladiator|PASS|Numerics|
|model--albert-large-v2_ner_wikiann--Gladiator|PASS|Numerics|
|model--albert-large-v2_squad--Palak|PASS|Numerics|
|model--albert-xxl-v2-finetuned-squad--anas-awadalla|PASS|Numerics|
|model--bart-large-cnn-samsum--philschmid|PASS|Numerics|
|model--bert-finetuned-squad22--makdong|PASS|Numerics|
|model--bsc-bio-ehr-es-cantemist--PlanTL-GOB-ES|PASS|Numerics|
|model--bsc-bio-ehr-es-pharmaconer--PlanTL-GOB-ES|PASS|Numerics|
|model--camembert-base-fquad--illuin|PASS|Numerics|
|model--camembert-base-squad-finetuned-on-runaways-fr--Nadav|PASS|Numerics|
|model--camembert-base-squad-fr--Nadav|PASS|Numerics|
|model--camembert-base-squadFR-fquad-piaf--etalab-ia|PASS|Numerics|
|model--camembert_squadFR_question_answering_tools_fr--AntoineD|PASS|Numerics|
|model--codegen-350M-mono--Salesforce|PASS|Numerics|
|model--codegen-350M-mono-4bit-qlora--iamtarun|PASS|Numerics|
|model--distilcamembert-base-ner--cmarkea|PASS|Numerics|
|model--distilcamembert-base-qa--cmarkea|PASS|Numerics|
|model--distilroberta-base-finetuned-wikitext2-SQuAD-qa-WandB2--Madhana|PASS|Numerics|
|model--distilroberta-base-ner-conll2003--philschmid|PASS|Numerics|
|model--distilroberta-base-ner-wikiann--philschmid|PASS|Numerics|
|model--distilroberta-base-squad_v2--squirro|PASS|Numerics|
|model--distilroberta-base_squad--Palak|PASS|Numerics|
|model--distilroberta-finetuned-financial-text-classification--nickmuchi|PASS|Numerics|
|model--distilroberta-squad--UKP-SQuARE|PASS|Numerics|
|model--electra-adversarial-squad--mlxen|PASS|Numerics|
|model--electra-base-discriminator-finetuned-conll03-english--bhadresh-savani|PASS|Numerics|
|model--electra-base-discriminator_mod_quoref--damapika|PASS|Numerics|
|model--electra-base-discriminator_squad_mod--damapika|PASS|Numerics|
|model--electra-base-irish-cased-discriminator-v1-finetuned-ner--jimregan|PASS|Numerics|
|model--electra-base-squad2--deepset|PASS|Numerics|
|model--electra-contrastdata-squad--mlxen|PASS|Numerics|
|model--electra-distilled-qa--kasohrab|PASS|Numerics|
|model--electra-finetuned-cpgqa--hung200504|PASS|Numerics|
|model--electra-large-synqa--mbartolo|PASS|Numerics|
|model--electra-small-discriminator-finetuned-ner--dbsamu|PASS|Numerics|
|model--electra-small-discriminator-finetuned-squad--hankzhong|PASS|Numerics|
|model--electra-small-finetuned-squadv2--mrm8488|PASS|Numerics|
|model--electra-small-turkish-uncased-discriminator-finetuned_lr-2e-05_epochs-3--husnu|PASS|Numerics|
|model--electra-srb-ner--Aleksandar|PASS|Numerics|
|model--enlm-roberta-imdb--manirai91|PASS|Numerics|
|model--environmental-claims--climatebert|PASS|Numerics|
|model--finetuning-albert-base-v2-on-imdb--Ibrahim-Alam|PASS|Numerics|
|model--finetuning-movie-roberta--RIYAN94182|PASS|Numerics|
|model--finetuning-roberta-base-on-imdb--Ibrahim-Alam|PASS|Numerics|
|model--finetuning-sentiment-model--Saberi|PASS|Numerics|
|model--flan-t5-large-samsum--oguuzhansahin|PASS|Numerics|
|model--gm-ner-xlmrbase--CLTL|PASS|Numerics|
|model--google_electra-base-discriminator_squad--Palak|PASS|Numerics|
|model--google_electra-small-discriminator_squad--Palak|PASS|Numerics|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|PASS|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|PASS|Numerics|
|model--manifestoberta-xlm-roberta-56policy-topics-sentence-2023-1-1--manifesto-project|PASS|Numerics|
|model--mobilebert-squadv2--aware-ai|PASS|Numerics|
|model--mobilebert-uncased-finetuned-squadv2--mrm8488|PASS|Numerics|
|model--mobilebert_cola--Alireza1044|PASS|Numerics|
|model--mobilebert_mnli--Alireza1044|PASS|Numerics|
|model--mobilebert_mrpc--Alireza1044|PASS|Numerics|
|model--mobilebert_rte--Alireza1044|PASS|Numerics|
|model--mobilebert_sst2--Alireza1044|PASS|Numerics|
|model--mt5-small-sum-de-en-v1--deutsche-telekom|PASS|Numerics|
|model--mt5-small-sum-de-en-v2--T-Systems-onsite|PASS|Numerics|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|PASS|Numerics|
|model--nd-qna--Trisert|PASS|Numerics|
|model--query_wellformedness_score--Ashishkr|PASS|Numerics|
|model--roberta-base-bne-sqac--PlanTL-GOB-ES|PASS|Numerics|
|model--roberta-base-ca-cased-ner--projecte-aina|PASS|Numerics|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-42--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-1024-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-42--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-128-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-256-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-32-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-10--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-512-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-6--anas-awadalla|PASS|Numerics|
|model--roberta-base-few-shot-k-64-finetuned-squad-seed-8--anas-awadalla|PASS|Numerics|
|model--roberta-base-finetuned-deletion-squad-10--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-imdb--wrmurray|PASS|Numerics|
|model--roberta-base-finetuned-mbti-0901--GItaf|PASS|Numerics|
|model--roberta-base-finetuned-ner--dominiqueblok|PASS|Numerics|
|model--roberta-base-finetuned-scrambled-squad-10-new--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-scrambled-squad-15-new--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-scrambled-squad-5-new--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-squad--Firat|PASS|Numerics|
|model--roberta-base-finetuned-squad-1--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-squad-3--huxxx657|PASS|Numerics|
|model--roberta-base-finetuned-squad8000--HASAN55|PASS|Numerics|
|model--roberta-base-finetuned-squad_roberta_v3--seviladiguzel|PASS|Numerics|
|model--roberta-base-imdb--aychang|PASS|Numerics|
|model--roberta-base-spanish-sqac--IIC|PASS|Numerics|
|model--roberta-base-spanish-squades--IIC|PASS|Numerics|
|model--roberta-base-squad2--NewBreaker|PASS|Numerics|
|model--roberta-base-squad2--deepset|PASS|Numerics|
|model--roberta-base-squad2--syndi-models|PASS|Numerics|
|model--roberta-base-squad2-distilled--deepset|PASS|Numerics|
|model--roberta-base-squad2-nq--nlpconnect|PASS|Numerics|
|model--roberta-base_mod_quoref--damapika|PASS|Numerics|
|model--roberta-base_mod_squad--damapika|PASS|Numerics|
|model--roberta-l-squadv1.1--vuiseng9|PASS|Numerics|
|model--roberta-large-bne-sqac--PlanTL-GOB-ES|PASS|Numerics|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-1024-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-128-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--roberta-large-few-shot-k-64-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--roberta-large-finetuned-ner--romainlhardy|PASS|Numerics|
|model--roberta-large-ner-english--Jean-Baptiste|PASS|Numerics|
|model--roberta-large-synqa--mbartolo|PASS|Numerics|
|model--roberta-large-synqa-ext--mbartolo|PASS|Numerics|
|model--roberta-large-tweetner7-all--tner|PASS|Numerics|
|model--roberta-large_ner_conll2003--Gladiator|PASS|Numerics|
|model--roberta-ner-multilingual--julian-schelb|PASS|Numerics|
|model--roberta_large-filtered_simple-chunk-conll2003_0907_v1--mariolinml|PASS|Numerics|
|model--roberta_large-ner-conll2003_0818_v0--mariolinml|PASS|Numerics|
|model--roberta_large-unbalanced_simple-ner-conll2003_0908_v0--mariolinml|PASS|Numerics|
|model--roberta_qa_japanese--tsmatz|PASS|Numerics|
|model--slovakbert-ner--crabz|PASS|Numerics|
|model--small-e-czech-finetuned-ner-wikiann--richielo|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-0--anas-awadalla|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--splinter-large-few-shot-k-16-finetuned-squad-seed-4--anas-awadalla|PASS|Numerics|
|model--splinter-large-few-shot-k-32-finetuned-squad-seed-2--anas-awadalla|PASS|Numerics|
|model--summarization-not-evaluated--autoevaluate|PASS|Numerics|
|model--t5-base-fr-sum-cnndm--plguillou|PASS|Numerics|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|PASS|Numerics|
|model--t5-small-booksum--cnicu|PASS|Numerics|
|model--t5-small-finetuned-cnn--ubikpt|PASS|Numerics|
|model--tiny-random-RoFormerForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-gptj-for-sequence-classification--ydshieh|PASS|Numerics|
|model--tinyroberta-squad2--deepset|PASS|Numerics|
|model--twitter-roberta-base-dec2021-tweetner7-random--tner|PASS|Numerics|
|model--twitter-roberta-base-emotion--cardiffnlp|PASS|Numerics|
|model--wikibert-finetuned-vsmec--ThuanPhong|PASS|Numerics|
|model--xlm-roberta-base-conll2003-en--Amir13|PASS|Numerics|
|model--xlm-roberta-base-conll2003-ner--Yaxin|PASS|Numerics|
|model--xlm-roberta-base-esg-ner--santoshvutukuri|PASS|Numerics|
|model--xlm-roberta-base-finetuned-conll2003--LecJackS|PASS|Numerics|
|model--xlm-roberta-base-finetuned-panx-de--chaewonlee|PASS|Numerics|
|model--xlm-roberta-base-finetuned-squad--darshana1406|PASS|Numerics|
|model--xlm-roberta-base-kyrgyzNER--the-cramer-project|PASS|Numerics|
|model--xlm-roberta-base-squad2--deepset|PASS|Numerics|
|model--xlm-roberta-base-squad2-distilled--deepset|PASS|Numerics|
|model--xlm-roberta-base_squad--Palak|PASS|Numerics|
|model--xlm-roberta-conll2003--manirai91|PASS|Numerics|
|model--xlm-roberta-imdb--manirai91|PASS|Numerics|
|model--xlm-roberta-large-squad2--deepset|PASS|Numerics|
|model--xlm-roberta-ner-japanese--tsmatz|PASS|Numerics|
|model--xlm-roberta-qa-chaii--gokulkarthik|PASS|Numerics|
|model--xlmr-large-qa-fa--m3hrdadfi|PASS|Numerics|
|model--yelp_review_rating_reberta_base--Shunian|PASS|Numerics|

## 326 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|Inception_v4_vaiq_int8|Numerics|PASS|
|ShuffleNet_v2_x2_0_vaiq_int8|Numerics|PASS|
|bat_resnext26ts.ch_in1k|Numerics|PASS|
|beit_base_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|beit_base_patch16_384.in22k_ft_in22k_in1k|Numerics|PASS|
|beit_large_patch16_224.in22k_ft_in22k_in1k|Numerics|PASS|
|beit_large_patch16_384.in22k_ft_in22k_in1k|Numerics|PASS|
|beitv2_base_patch16_224.in1k_ft_in22k_in1k|Numerics|PASS|
|beitv2_large_patch16_224.in1k_ft_in22k_in1k|Numerics|PASS|
|botnet26t_256|Numerics|PASS|
|cait_s24_224|Numerics|PASS|
|cait_xs24_384|Numerics|PASS|
|cait_xxs24_224|compilation|PASS|
|cait_xxs24_384|Numerics|PASS|
|cait_xxs36_224|compilation|PASS|
|cait_xxs36_384|Numerics|PASS|
|coat_lite_mini|compilation|PASS|
|coat_lite_small|compilation|PASS|
|coat_lite_tiny|compilation|PASS|
|coat_mini|Numerics|PASS|
|coat_tiny|Numerics|PASS|
|coatnext_nano_rw_224.sw_in1k|compilation|PASS|
|convit_base|Numerics|PASS|
|convit_small|compilation|PASS|
|convit_tiny|compilation|PASS|
|convnext_atto.d2_in1k|compilation|PASS|
|convnext_atto_ols.a2_in1k|compilation|PASS|
|convnext_femto.d1_in1k|compilation|PASS|
|convnext_femto_ols.d1_in1k|compilation|PASS|
|convnext_nano.d1h_in1k|compilation|PASS|
|convnext_nano.in12k|compilation|PASS|
|convnext_nano.in12k_ft_in1k|compilation|PASS|
|convnext_nano_ols.d1h_in1k|compilation|PASS|
|convnext_pico.d1_in1k|compilation|PASS|
|convnext_pico_ols.d1_in1k|compilation|PASS|
|convnext_small.fb_in1k|Numerics|PASS|
|convnext_small.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_small.in12k|Numerics|PASS|
|convnext_small.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny.fb_in1k|Numerics|PASS|
|convnext_tiny.fb_in22k_ft_in1k|Numerics|PASS|
|convnext_tiny.in12k|Numerics|PASS|
|convnext_tiny.in12k_ft_in1k|Numerics|PASS|
|convnext_tiny_hnf.a2h_in1k|compilation|PASS|
|convnextv2_atto.fcmae|compilation|PASS|
|convnextv2_atto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_femto.fcmae|compilation|PASS|
|convnextv2_femto.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae|compilation|PASS|
|convnextv2_nano.fcmae_ft_in1k|compilation|PASS|
|convnextv2_nano.fcmae_ft_in22k_in1k|compilation|PASS|
|convnextv2_pico.fcmae|compilation|PASS|
|convnextv2_pico.fcmae_ft_in1k|compilation|PASS|
|convnextv2_tiny.fcmae|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in1k|Numerics|PASS|
|convnextv2_tiny.fcmae_ft_in22k_in1k|Numerics|PASS|
|crossvit_15_240|compilation|PASS|
|crossvit_15_dagger_240|compilation|PASS|
|crossvit_15_dagger_408|compilation|PASS|
|crossvit_18_240|compilation|PASS|
|crossvit_18_dagger_240|compilation|PASS|
|crossvit_18_dagger_408|compilation|PASS|
|crossvit_9_240|Numerics|PASS|
|crossvit_9_dagger_240|Numerics|PASS|
|crossvit_base_240|Numerics|PASS|
|crossvit_small_240|compilation|PASS|
|crossvit_tiny_240|compilation|PASS|
|davit_base.msft_in1k|Numerics|PASS|
|davit_small.msft_in1k|compilation|PASS|
|davit_tiny.msft_in1k|compilation|PASS|
|deit3_base_patch16_224.fb_in1k|Numerics|PASS|
|deit3_base_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_base_patch16_384.fb_in1k|Numerics|PASS|
|deit3_base_patch16_384.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_large_patch16_224.fb_in1k|Numerics|PASS|
|deit3_large_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_large_patch16_384.fb_in1k|Numerics|PASS|
|deit3_large_patch16_384.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_medium_patch16_224.fb_in1k|Numerics|PASS|
|deit3_medium_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_small_patch16_224.fb_in1k|Numerics|PASS|
|deit3_small_patch16_224.fb_in22k_ft_in1k|Numerics|PASS|
|deit3_small_patch16_384.fb_in1k|Numerics|PASS|
|deit3_small_patch16_384.fb_in22k_ft_in1k|Numerics|PASS|
|deit_base_distilled_patch16_224.fb_in1k|Numerics|PASS|
|deit_base_distilled_patch16_384.fb_in1k|Numerics|PASS|
|deit_base_patch16_224.fb_in1k|Numerics|PASS|
|deit_base_patch16_384.fb_in1k|Numerics|PASS|
|deit_small_distilled_patch16_224.fb_in1k|Numerics|PASS|
|deit_small_patch16_224.fb_in1k|Numerics|PASS|
|deit_tiny_distilled_patch16_224.fb_in1k|compilation|PASS|
|deit_tiny_patch16_224.fb_in1k|compilation|PASS|
|edgenext_base|Numerics|PASS|
|edgenext_small|Numerics|PASS|
|edgenext_small_rw|Numerics|PASS|
|edgenext_x_small|Numerics|PASS|
|edgenext_xx_small|Numerics|PASS|
|efficientnet_b2_pruned.in1k|compilation|PASS|
|eva_large_patch14_196.in22k_ft_in1k|Numerics|PASS|
|eva_large_patch14_196.in22k_ft_in22k_in1k|Numerics|PASS|
|eva_large_patch14_336.in22k_ft_in1k|Numerics|PASS|
|eva_large_patch14_336.in22k_ft_in22k_in1k|Numerics|PASS|
|flexivit_base.1200ep_in1k|Numerics|PASS|
|flexivit_base.300ep_in1k|Numerics|PASS|
|flexivit_base.600ep_in1k|Numerics|PASS|
|flexivit_large.1200ep_in1k|Numerics|PASS|
|flexivit_large.300ep_in1k|Numerics|PASS|
|flexivit_large.600ep_in1k|Numerics|PASS|
|flexivit_small.1200ep_in1k|Numerics|PASS|
|flexivit_small.300ep_in1k|Numerics|PASS|
|flexivit_small.600ep_in1k|Numerics|PASS|
|gmixer_24_224.ra3_in1k|compilation|PASS|
|gmlp_s16_224.ra3_in1k|Numerics|PASS|
|jx_nest_base|Numerics|PASS|
|jx_nest_small|compilation|PASS|
|jx_nest_tiny|compilation|PASS|
|lambda_resnet50ts|Numerics|PASS|
|levit_128.fb_dist_in1k|Numerics|PASS|
|levit_128s.fb_dist_in1k|Numerics|PASS|
|levit_192.fb_dist_in1k|compilation|PASS|
|levit_256.fb_dist_in1k|Numerics|PASS|
|levit_384.fb_dist_in1k|Numerics|PASS|
|levit_conv_128.fb_dist_in1k|compilation|PASS|
|levit_conv_128s.fb_dist_in1k|compilation|PASS|
|levit_conv_192.fb_dist_in1k|compilation|PASS|
|levit_conv_256.fb_dist_in1k|compilation|PASS|
|levit_conv_384.fb_dist_in1k|compilation|PASS|
|maxvit_rmlp_pico_rw_256.sw_in1k|Numerics|PASS|
|maxvit_rmlp_tiny_rw_256.sw_in1k|Numerics|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k|compilation|PASS|
|maxxvitv2_rmlp_base_rw_224.sw_in12k_ft_in1k|compilation|PASS|
|migraphx_bert__bert-large-uncased|Numerics|PASS|
|migraphx_bert__bertsquad-12|Numerics|PASS|
|migraphx_cadene__inceptionv4i16|compilation|PASS|
|migraphx_cadene__resnext101_64x4di16|compilation|PASS|
|migraphx_mlperf__resnet50_v1|compilation|Numerics|
|migraphx_pytorch-examples__wlang_lstm|Numerics|PASS|
|migraphx_torchvision__densenet121i32|compilation|PASS|
|migraphx_torchvision__inceptioni1|compilation|PASS|
|migraphx_torchvision__inceptioni32|compilation|PASS|
|migraphx_torchvision__resnet50i64|compilation|PASS|
|mixer_b16_224.goog_in21k_ft_in1k|compilation|PASS|
|mixer_b16_224.miil_in21k_ft_in1k|compilation|PASS|
|mixer_l16_224.goog_in21k_ft_in1k|compilation|PASS|
|mobilevit_s|Numerics|PASS|
|mobilevit_xs|Numerics|PASS|
|mobilevit_xxs|Numerics|PASS|
|mobilevitv2_050|Numerics|PASS|
|mobilevitv2_075|Numerics|PASS|
|mobilevitv2_100|compilation|PASS|
|mobilevitv2_125|Numerics|PASS|
|mobilevitv2_150|compilation|PASS|
|mobilevitv2_150_in22ft1k|compilation|PASS|
|mobilevitv2_175|Numerics|PASS|
|mobilevitv2_175_in22ft1k|Numerics|PASS|
|mobilevitv2_200|compilation|PASS|
|mobilevitv2_200_in22ft1k|compilation|PASS|
|model--Bartlarge--Shubham09|Numerics|PASS|
|model--TinyStories-1M--roneneldan|Numerics|PASS|
|model--TinyStories-3M--roneneldan|Numerics|PASS|
|model--TinyStories-8M--roneneldan|Numerics|PASS|
|model--bart-large-cnn--facebook|Numerics|PASS|
|model--bert-finetuned-squad--Lexie79|Numerics|PASS|
|model--really-tiny-falcon-testing--fxmarty|Numerics|PASS|
|model--tiny-gpt2--taufeeque|Numerics|PASS|
|model--tiny-random-FalconForCausalLM--illuin|Numerics|PASS|
|model--tiny-testing-falcon-alibi--fxmarty|Numerics|PASS|
|mvitv2_base|Numerics|PASS|
|mvitv2_large|compilation|PASS|
|mvitv2_small|Numerics|PASS|
|mvitv2_tiny|Numerics|PASS|
|nasnetalarge|compilation|Numerics|
|pit_b_224|Numerics|PASS|
|pit_b_distilled_224|Numerics|PASS|
|pit_s_224|compilation|PASS|
|pit_s_distilled_224|compilation|PASS|
|pit_ti_224|Numerics|PASS|
|pit_ti_distilled_224|Numerics|PASS|
|pit_xs_224|compilation|PASS|
|pit_xs_distilled_224|compilation|PASS|
|pnasnet5large|compilation|Numerics|
|pvt_v2_b0|compilation|PASS|
|pvt_v2_b1|compilation|PASS|
|pvt_v2_b2|compilation|PASS|
|pvt_v2_b2_li|compilation|PASS|
|pvt_v2_b3|compilation|PASS|
|pvt_v2_b4|compilation|PASS|
|pvt_v2_b5|compilation|PASS|
|resmlp_12_224.fb_distilled_in1k_vaiq|Numerics|PASS|
|resmlp_12_224.fb_in1k_vaiq|Numerics|PASS|
|resmlp_24_224.fb_distilled_in1k_vaiq|Numerics|PASS|
|resmlp_24_224.fb_in1k_vaiq|Numerics|PASS|
|resmlp_36_224.fb_distilled_in1k_vaiq|Numerics|PASS|
|resmlp_36_224.fb_in1k_vaiq|Numerics|PASS|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|Numerics|PASS|
|rexnetr_200.sw_in12k|compilation|PASS|
|sebotnet33ts_256|Numerics|PASS|
|swin_base_patch4_window7_224.ms_in1k|Numerics|PASS|
|swin_base_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|swin_large_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|swin_s3_base_224.ms_in1k|Numerics|PASS|
|swin_s3_small_224.ms_in1k|Numerics|PASS|
|swin_s3_tiny_224.ms_in1k|Numerics|PASS|
|swin_small_patch4_window7_224.ms_in1k|Numerics|PASS|
|swin_small_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|swin_tiny_patch4_window7_224.ms_in1k|Numerics|PASS|
|swin_tiny_patch4_window7_224.ms_in22k_ft_in1k|Numerics|PASS|
|swinv2_cr_small_224.sw_in1k|compilation|PASS|
|swinv2_cr_small_ns_224.sw_in1k|compilation|PASS|
|swinv2_cr_tiny_ns_224.sw_in1k|compilation|PASS|
|tf_efficientnet_b2.aa_in1k|compilation|PASS|
|tf_efficientnet_b2.ap_in1k|compilation|PASS|
|tf_efficientnet_b2.ns_jft_in1k|compilation|PASS|
|tf_efficientnet_b5.ap_in1k|compilation|PASS|
|tf_efficientnet_b5.ns_jft_in1k|compilation|PASS|
|tf_efficientnet_b5.ra_in1k|compilation|PASS|
|tf_efficientnet_b6.aa_in1k|compilation|PASS|
|tf_efficientnet_b6.ap_in1k|compilation|PASS|
|tf_efficientnet_b6.ns_jft_in1k|compilation|PASS|
|tf_efficientnet_b7.ap_in1k|compilation|PASS|
|tf_efficientnet_b7.ns_jft_in1k|compilation|PASS|
|tf_efficientnet_b7.ra_in1k|compilation|PASS|
|tf_efficientnet_b8.ap_in1k|compilation|PASS|
|tf_efficientnet_b8.ra_in1k|compilation|PASS|
|tf_efficientnet_l2.ns_jft_in1k|compilation|PASS|
|tinynet_c.in1k|compilation|PASS|
|tinynet_e.in1k|compilation|PASS|
|tnt_s_patch16_224|Numerics|PASS|
|twins_pcpvt_base|compilation|PASS|
|twins_pcpvt_large|compilation|PASS|
|twins_pcpvt_small|compilation|PASS|
|twins_svt_base|Numerics|PASS|
|twins_svt_large|Numerics|PASS|
|twins_svt_small|Numerics|PASS|
|vit_base_patch16_224.augreg2_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_224.augreg_in1k|Numerics|PASS|
|vit_base_patch16_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_224.orig_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_224.sam|Numerics|PASS|
|vit_base_patch16_224_miil.in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_384.augreg_in1k|Numerics|PASS|
|vit_base_patch16_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_384.orig_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in12k|Numerics|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch16_clip_224.laion2b_ft_in1k|Numerics|PASS|
|vit_base_patch16_clip_224.openai|Numerics|PASS|
|vit_base_patch16_clip_224.openai_ft_in12k|Numerics|PASS|
|vit_base_patch16_clip_224.openai_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch16_clip_224.openai_ft_in1k|Numerics|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch16_clip_384.laion2b_ft_in1k|Numerics|PASS|
|vit_base_patch16_clip_384.openai_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch16_clip_384.openai_ft_in1k|Numerics|PASS|
|vit_base_patch16_rpn_224.in1k|Numerics|PASS|
|vit_base_patch32_224.augreg_in1k|Numerics|PASS|
|vit_base_patch32_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch32_224.sam|Numerics|PASS|
|vit_base_patch32_384.augreg_in1k|Numerics|PASS|
|vit_base_patch32_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch32_clip_224.laion2b|Numerics|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch32_clip_224.laion2b_ft_in1k|Numerics|PASS|
|vit_base_patch32_clip_224.openai|Numerics|PASS|
|vit_base_patch32_clip_224.openai_ft_in1k|Numerics|PASS|
|vit_base_patch32_clip_384.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch32_clip_384.openai_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch32_clip_448.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_base_patch8_224.augreg2_in21k_ft_in1k|Numerics|PASS|
|vit_base_patch8_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_base_r50_s16_384.orig_in21k_ft_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.laion2b_ft_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.openai|Numerics|PASS|
|vit_large_patch14_clip_224.openai_ft_in12k|Numerics|PASS|
|vit_large_patch14_clip_224.openai_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch14_clip_224.openai_ft_in1k|Numerics|PASS|
|vit_large_patch14_clip_336.laion2b_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch14_clip_336.laion2b_ft_in1k|Numerics|PASS|
|vit_large_patch14_clip_336.openai_ft_in12k_in1k|Numerics|PASS|
|vit_large_patch16_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_large_patch16_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_large_patch32_384.orig_in21k_ft_in1k|Numerics|PASS|
|vit_large_r50_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_large_r50_s32_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_medium_patch16_gap_240.in12k|Numerics|PASS|
|vit_relpos_base_patch16_224.sw_in1k|Numerics|PASS|
|vit_relpos_base_patch16_clsgap_224.sw_in1k|Numerics|PASS|
|vit_relpos_medium_patch16_224.sw_in1k|Numerics|PASS|
|vit_relpos_medium_patch16_cls_224.sw_in1k|Numerics|PASS|
|vit_relpos_medium_patch16_rpn_224.sw_in1k|Numerics|PASS|
|vit_relpos_small_patch16_224.sw_in1k|Numerics|PASS|
|vit_small_patch16_224.augreg_in1k|Numerics|PASS|
|vit_small_patch16_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_small_patch16_384.augreg_in1k|Numerics|PASS|
|vit_small_patch16_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_small_patch32_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_small_patch32_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_small_r26_s32_224.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_small_r26_s32_384.augreg_in21k_ft_in1k|Numerics|PASS|
|vit_srelpos_medium_patch16_224.sw_in1k|Numerics|PASS|
|vit_srelpos_small_patch16_224.sw_in1k|Numerics|PASS|
|vit_tiny_patch16_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_patch16_384.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_224.augreg_in21k_ft_in1k|compilation|PASS|
|vit_tiny_r_s16_p8_384.augreg_in21k_ft_in1k|compilation|PASS|
|xcit_large_24_p16_224|Numerics|PASS|
|xcit_large_24_p16_224_dist|Numerics|PASS|
|xcit_small_12_p16_224|Numerics|PASS|
|xcit_small_12_p16_224_dist|Numerics|PASS|
|xcit_small_24_p16_224|Numerics|PASS|
|xcit_small_24_p16_224_dist|Numerics|PASS|
|xcit_tiny_12_p16_224|compilation|PASS|
|xcit_tiny_12_p16_224_dist|compilation|PASS|
|xcit_tiny_12_p16_384_dist|Numerics|PASS|
|xcit_tiny_12_p8_224|Numerics|PASS|
|xcit_tiny_12_p8_224_dist|Numerics|PASS|
|xcit_tiny_12_p8_384_dist|Numerics|PASS|
|xcit_tiny_24_p16_224|compilation|PASS|
|xcit_tiny_24_p16_224_dist|compilation|PASS|
|xcit_tiny_24_p16_384_dist|Numerics|PASS|
|xcit_tiny_24_p8_224|Numerics|PASS|
|xcit_tiny_24_p8_224_dist|Numerics|PASS|
|xcit_tiny_24_p8_384_dist|Numerics|PASS|
