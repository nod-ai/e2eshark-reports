# Test Run Comparison Report

## Performance Comparison

regression tolerance: 10.0%

progression tolerance: 10.0%

|model name|exit_status|analysis|old_time_ms|new_time_ms|change_ms|percent_change|
|---|---|---|---|---|---|---|
|migraphx_ORT__bert_base_cased_1|PASS|within tol|85.632|90.7649|5.1329|5.99%|
|migraphx_ORT__bert_base_uncased_1|PASS|regression|86.1524|122.5892|36.4368|42.29%|
|migraphx_ORT__bert_large_uncased_1|PASS|within tol|260.9527|280.9099|19.9572|7.65%|
|migraphx_ORT__distilgpt2_1|PASS|within tol|31.2671|32.5339|1.2669|4.05%|
|migraphx_ORT__onnx_models__bert_base_cased_1_fp16_gpu|Numerics|within tol|83.0977|85.1283|2.0305|2.44%|
|migraphx_ORT__onnx_models__bert_large_uncased_1_fp16_gpu|Numerics|within tol|244.0676|248.303|4.2354|1.74%|
|migraphx_ORT__onnx_models__distilgpt2_1_fp16_gpu|Numerics|within tol|40.5572|39.1168|-1.4404|-3.55%|
|migraphx_bert__bert-large-uncased|PASS|within tol|410.0501|371.907|-38.1431|-9.3%|
|migraphx_bert__bertsquad-12|PASS|within tol|95.476|86.1339|-9.3421|-9.78%|
|migraphx_cadene__dpn92i1|PASS|within tol|186.2736|180.7464|-5.5273|-2.97%|
|migraphx_cadene__inceptionv4i16|PASS|within tol|7257.2016|6701.4802|-555.7214|-7.66%|
|migraphx_cadene__resnext101_64x4di1|PASS|within tol|330.1171|332.6039|2.4868|0.75%|
|migraphx_huggingface-transformers__bert_mrpc8|PASS|within tol|420.8|384.2881|-36.5118|-8.68%|
|migraphx_mlperf__bert_large_mlperf|Numerics|within tol|456.7549|445.2474|-11.5075|-2.52%|
|migraphx_mlperf__resnet50_v1|PASS|within tol|100.8666|100.169|-0.6976|-0.69%|
|migraphx_models__whisper-tiny-decoder|PASS|progression|40.8811|32.1294|-8.7517|-21.41%|
|migraphx_models__whisper-tiny-encoder|Numerics|within tol|182.9736|183.3109|0.3373|0.18%|
|migraphx_pytorch-examples__wlang_gru|PASS|regression|70.2852|84.1869|13.9017|19.78%|
|migraphx_pytorch-examples__wlang_lstm|PASS|regression|41.0543|55.3045|14.2502|34.71%|
|migraphx_torchvision__densenet121i32|PASS|regression|1377.2882|1630.4017|253.1135|18.38%|
|migraphx_torchvision__inceptioni1|PASS|within tol|258.7426|246.4476|-12.295|-4.75%|
|migraphx_torchvision__inceptioni32|PASS|within tol|6648.7116|6719.806|71.0944|1.07%|
|migraphx_torchvision__resnet50i1|PASS|within tol|99.4756|92.2682|-7.2075|-7.25%|
|migraphx_torchvision__resnet50i64|PASS|within tol|6088.0794|6004.586|-83.4934|-1.37%|
|migx_bench_bert-large-uncased_16_128|PASS|within tol|2688.5782|2919.5237|230.9454|8.59%|
|migx_bench_bert-large-uncased_16_256|PASS|within tol|4097.8175|4450.2131|352.3956|8.6%|
|migx_bench_bert-large-uncased_16_384|Numerics|within tol|6359.273|6245.8297|-113.4433|-1.78%|
|migx_bench_bert-large-uncased_1_128|PASS|within tol|188.254|175.6768|-12.5771|-6.68%|
|migx_bench_bert-large-uncased_1_256|PASS|progression|380.8856|275.802|-105.0836|-27.59%|
|migx_bench_bert-large-uncased_1_384|PASS|within tol|392.6775|381.9974|-10.6801|-2.72%|
|migx_bench_bert-large-uncased_2_128|PASS|within tol|464.1775|421.089|-43.0885|-9.28%|
|migx_bench_bert-large-uncased_2_256|PASS|within tol|646.0645|668.3821|22.3176|3.45%|
|migx_bench_bert-large-uncased_2_384|PASS|within tol|845.906|833.1787|-12.7273|-1.5%|
|migx_bench_bert-large-uncased_32_128|PASS|regression|5134.5125|5695.5263|561.0138|10.93%|
|migx_bench_bert-large-uncased_32_256|PASS|within tol|8841.4288|8552.6904|-288.7384|-3.27%|
|migx_bench_bert-large-uncased_32_384|Numerics|within tol|11939.3575|11761.3705|-177.987|-1.49%|
|migx_bench_bert-large-uncased_4_128|PASS|regression|745.4025|1059.5387|314.1362|42.14%|
|migx_bench_bert-large-uncased_4_256|PASS|within tol|1125.1086|1138.017|12.9084|1.15%|
|migx_bench_bert-large-uncased_4_384|PASS|within tol|1749.2347|1661.6247|-87.61|-5.01%|
|migx_bench_bert-large-uncased_8_128|PASS|within tol|1532.455|1451.2537|-81.2012|-5.3%|
|migx_bench_bert-large-uncased_8_256|PASS|progression|2403.9663|2066.0848|-337.8815|-14.06%|
|migx_bench_bert-large-uncased_8_384|PASS|within tol|3127.1362|3133.6533|6.517|0.21%|

## 7 Regressions Found:

|model name|old_status|new_status|
|---|---|---|
|resmlp_12_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_12_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_24_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_distilled_in1k_vaiq|PASS|compilation|
|resmlp_36_224.fb_in1k_vaiq|PASS|compilation|
|resmlp_big_24_224.fb_distilled_in1k_vaiq|PASS|compilation|

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

