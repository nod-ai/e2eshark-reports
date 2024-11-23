# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|90.3449|91.3681|1.0233|1.13%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.8042|101.0944|14.2902|16.46%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|280.7138|291.1345|10.4206|3.71%|
|migraphx_ORT__distilgpt2_1|PASS|progression|33.9991|30.9644|-3.0347|-8.93%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|regression|86.2848|94.6335|8.3486|9.68%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|265.0549|261.8163|-3.2386|-1.22%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|41.2926|39.5591|-1.7336|-4.2%|
|migraphx_bert__bert-large-uncased|PASS|within tol|398.202|405.363|7.161|1.8%|
|migraphx_bert__bertsquad-12|PASS|within tol|86.8644|86.6443|-0.2201|-0.25%|
|migraphx_cadene__dpn92i1|PASS|regression|363.4492|409.6754|46.2262|12.72%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|6851.1933|6807.4223|-43.771|-0.64%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|316.3572|328.8083|12.4511|3.94%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|424.9328|586.2923|161.3595|37.97%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|445.3302|455.7345|10.4043|2.34%|
|migraphx_mlperf__resnet50_v1|PASS|progression|111.3024|103.7069|-7.5954|-6.82%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|38.1558|34.3991|-3.7567|-9.85%|
|migraphx_models__whisper-tiny-encoder|Numerics|regression|201.4482|227.3899|25.9417|12.88%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|96.6838|88.7316|-7.9523|-8.23%|
|migraphx_pytorch-examples__wlang_lstm|PASS|within tol|46.1934|45.763|-0.4303|-0.93%|
|migraphx_torchvision__densenet121i32|PASS|regression|1312.1755|1454.3972|142.2217|10.84%|
|migraphx_torchvision__inceptioni1|PASS|progression|229.9945|217.2708|-12.7237|-5.53%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6582.8115|6571.4364|-11.3751|-0.17%|
|migraphx_torchvision__resnet50i1|PASS|within tol|92.8842|93.0314|0.1471|0.16%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6218.3269|6043.8751|-174.4517|-2.81%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2815.1919|2800.963|-14.2289|-0.51%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4593.8239|4456.8927|-136.9312|-2.98%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5820.1679|5659.9175|-160.2504|-2.75%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|167.3264|162.4657|-4.8607|-2.9%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|259.6628|265.4944|5.8316|2.25%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|403.5369|380.1578|-23.3791|-5.79%|
|migx_bench_bert-large-uncased_2_128|PASS|progression|428.0262|382.2558|-45.7705|-10.69%|
|migx_bench_bert-large-uncased_2_256|PASS|progression|690.8333|590.1653|-100.6681|-14.57%|
|migx_bench_bert-large-uncased_2_384|PASS|regression|907.619|967.6964|60.0774|6.62%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5323.1451|5089.8199|-233.3252|-4.38%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8096.2312|8291.8839|195.6527|2.42%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11143.7281|11517.8016|374.0735|3.36%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|788.5566|900.2144|111.6577|14.16%|
|migx_bench_bert-large-uncased_4_256|PASS|progression|1229.2148|1139.6666|-89.5483|-7.28%|
|migx_bench_bert-large-uncased_4_384|PASS|regression|1824.5955|2581.4483|756.8528|41.48%|
|migx_bench_bert-large-uncased_8_128|PASS|regression|1349.8454|2598.1307|1248.2853|92.48%|
|migx_bench_bert-large-uncased_8_256|PASS|regression|2145.8108|2582.9622|437.1514|20.37%|
|migx_bench_bert-large-uncased_8_384|PASS|regression|3020.5815|3529.0726|508.4911|16.83%|

## No Regressions Found

## 203 Progressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--Bartlarge--Shubham09|Numerics|PASS|
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
|model--ia-detection-tiny-random-gptj--arincon|Numerics|PASS|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|Numerics|PASS|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|Numerics|PASS|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|Numerics|PASS|
|model--mT5-base-HunSum-1--SZTAKI-HLT|Numerics|PASS|
|model--mT5_multilingual_XLSum--csebuetnlp|Numerics|PASS|
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
|model--my_awesome_gptj_model--anandshende|Numerics|PASS|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|Numerics|PASS|
|model--nd-qna--Trisert|Numerics|PASS|
|model--qa_tquad_convbert-base-turkish--Izzet|Numerics|PASS|
|model--qa_ytu_convbert-base-turkish--Izzet|Numerics|PASS|
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
|model--summarization-not-evaluated--autoevaluate|Numerics|PASS|
|model--t5-base-fr-sum-cnndm--plguillou|Numerics|PASS|
|model--t5-large-finetuned-xsum-cnn--sysresearch101|Numerics|PASS|
|model--t5-small-booksum--cnicu|Numerics|PASS|
|model--t5-small-finetuned-cnn--ubikpt|Numerics|PASS|
|model--tglobal-large-booksum-WIP4-r1--pszemraj|Numerics|PASS|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|Numerics|PASS|
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

