# Test Run Comparison Report

## Performance Comparison

regression tolerance: 5.0%

progression tolerance: 5.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|progression|97.5123|90.7917|-6.7207|-6.89%|
|migraphx_ORT__bert_base_uncased_1|PASS|progression|111.0636|104.893|-6.1706|-5.56%|
|migraphx_ORT__bert_large_uncased_1|PASS|progression|311.9866|270.9062|-41.0804|-13.17%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.0586|30.1909|-0.8677|-2.79%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|85.5953|87.8967|2.3014|2.69%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|regression|253.7612|285.3851|31.6239|12.46%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|regression|39.1763|49.2447|10.0684|25.7%|
|migraphx_bert__bert-large-uncased|PASS|progression|915.7402|428.6164|-487.1237|-53.19%|
|migraphx_bert__bertsquad-12|PASS|progression|149.4601|89.214|-60.2461|-40.31%|
|migraphx_cadene__dpn92i1|PASS|within tol|178.612|172.0643|-6.5478|-3.67%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|5896.2644|5781.1398|-115.1246|-1.95%|
|migraphx_cadene__resnext101_64x4di1|PASS|regression|325.2238|349.1881|23.9643|7.37%|
|migraphx_cadene__resnext101_64x4di16|PASS|within tol|5178.9491|5184.2997|5.3506|0.1%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|regression|430.3492|1548.682|1118.3328|259.87%|
|migraphx_mlperf__bert_large_mlperf|Numerics|progression|576.2465|459.5478|-116.6988|-20.25%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|89.3371|86.1456|-3.1915|-3.57%|
|migraphx_models__whisper-tiny-decoder|PASS|within tol|32.1121|32.8176|0.7055|2.2%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|181.4787|181.8778|0.3991|0.22%|
|migraphx_pytorch-examples__wlang_gru|PASS|progression|100.2215|88.676|-11.5455|-11.52%|
|migraphx_pytorch-examples__wlang_lstm|PASS|progression|57.0627|45.6304|-11.4323|-20.03%|
|migraphx_torchvision__densenet121i32|PASS|within tol|1655.065|1629.486|-25.579|-1.55%|
|migraphx_torchvision__inceptioni1|PASS|within tol|201.3802|209.2474|7.8672|3.91%|
|migraphx_torchvision__inceptioni32|PASS|within tol|5844.9753|5975.7002|130.7249|2.24%|
|migraphx_torchvision__resnet50i1|PASS|within tol|86.2895|87.1435|0.8539|0.99%|
|migraphx_torchvision__resnet50i64|PASS|within tol|5886.5782|5944.3478|57.7696|0.98%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2497.9823|2564.7952|66.8129|2.67%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4165.8412|4165.9048|0.0636|0.0%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|5687.7121|5831.3207|143.6086|2.52%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|156.292|157.203|0.911|0.58%|
|migx_bench_bert-large-uncased_1_256|PASS|within tol|265.4975|264.8241|-0.6734|-0.25%|
|migx_bench_bert-large-uncased_1_384|PASS|progression|421.4732|376.132|-45.3412|-10.76%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|382.9409|394.5619|11.621|3.03%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|587.8745|594.1116|6.2371|1.06%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|804.2592|803.3526|-0.9066|-0.11%|
|migx_bench_bert-large-uncased_32_128|PASS|within tol|5117.9919|5076.4529|-41.5391|-0.81%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8145.2506|7821.2691|-323.9815|-3.98%|
|migx_bench_bert-large-uncased_32_384|Numerics|regression|11434.7609|12011.1618|576.4009|5.04%|
|migx_bench_bert-large-uncased_4_128|PASS|within tol|716.5291|722.269|5.7399|0.8%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1104.5579|1091.3033|-13.2546|-1.2%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1517.9009|1554.2234|36.3225|2.39%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1299.2821|1285.7195|-13.5626|-1.04%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2352.8348|2055.1061|-297.7287|-12.65%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|2929.231|2909.0462|-20.1848|-0.69%|

## 203 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|model--Bartlarge--Shubham09|PASS|Numerics|
|model--BioM-ELECTRA-Base-SQuAD2--sultan|PASS|Numerics|
|model--CodeGen-350M-Multi--xhyi|PASS|Numerics|
|model--Electra-Large-SQUADV2--titanbot|PASS|Numerics|
|model--IMDB_ELECTRA_5E--pig4431|PASS|Numerics|
|model--M-TurQA-convbert-base-turkish-cased-finetuned-toqad-aug--meetyildiz|PASS|Numerics|
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
|model--bart-CaPE-xsum--praf-choub|PASS|Numerics|
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
|model--ia-detection-tiny-random-gptj--arincon|PASS|Numerics|
|model--ibert-roberta-base-finetuned-mrpc--VitaliiVrublevskyi|PASS|Numerics|
|model--long-t5-tglobal-base-16384-book-summary--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-base-16384-booksum-V11-big_patent-V2--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-base-16384-booksum-V12--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP13--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP14--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP15--pszemraj|PASS|Numerics|
|model--long-t5-tglobal-large-pubmed-3k-booksum-16384-WIP17--pszemraj|PASS|Numerics|
|model--mT5-base-HunSum-1--SZTAKI-HLT|PASS|Numerics|
|model--mT5_multilingual_XLSum--csebuetnlp|PASS|Numerics|
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
|model--my_awesome_gptj_model--anandshende|PASS|Numerics|
|model--my_xlm-roberta-large-finetuned-conll03--BahAdoR0101|PASS|Numerics|
|model--nd-qna--Trisert|PASS|Numerics|
|model--qa_tquad_convbert-base-turkish--Izzet|PASS|Numerics|
|model--qa_ytu_convbert-base-turkish--Izzet|PASS|Numerics|
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
|model--tglobal-large-booksum-WIP4-r1--pszemraj|PASS|Numerics|
|model--tiny-random-ConvBertForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
|model--tiny-random-GPTJForQuestionAnswering--hf-tiny-model-private|PASS|Numerics|
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

## No Progressions Found

